# D10 - Dubbo2 Protocol Specification
* Authors: Jun Liu

## Background
Dubbo2 遗留系统运行的 RPC 协议规范

## Related Proposals
[D0-triple](./D0-triple.md)

## Specification

![dubbo_protocol_header](../images/protocol/dubbo_protocol_header.png)


- Magic - Magic High & Magic Low (16 bits)

  Identifies dubbo protocol with value: 0xdabb

- Req/Res (1 bit)

  Identifies this is a request or response. Request - 1; Response - 0.

- 2 Way (1 bit)

  Only useful when Req/Res is 1 (Request), expect for a return value from server or not. Set to 1 if need a return value from server.

- Event (1 bit)

  Identifies an event message or not, for example, heartbeat event. Set to 1 if this is an event.

- Serialization ID (5 bit)

  Identifies serialization type: the value for fastjson is 6.

- Status (8 bits)

  Only useful when  Req/Res is 0 (Response), identifies the status of response

  - 20 - OK
  - 30 - CLIENT_TIMEOUT
  - 31 - SERVER_TIMEOUT
  - 40 - BAD_REQUEST
  - 50 - BAD_RESPONSE
  - 60 - SERVICE_NOT_FOUND
  - 70 - SERVICE_ERROR
  - 80 - SERVER_ERROR
  - 90 - CLIENT_ERROR
  - 100 - SERVER_THREADPOOL_EXHAUSTED_ERROR

- Request ID (64 bits)

  Identifies an unique request. Numeric (long).

- Data Length (32)

  Length of the content (the variable part) after serialization, counted by bytes. Numeric (integer).

- Variable Part

  Each part is a byte[] after serialization with specific serialization type, identifies by Serialization ID.

Every part is a byte[] after serialization with specific serialization type, identifies by Serialization ID

1. If the content is a Request (Req/Res = 1), each part consists of the content, in turn is:
   - Dubbo version
   - Service name
   - Service version
   - Method name
   - Method parameter types
   - Method arguments
   - Attachments

1. If the content is a Response (Req/Res = 0), each part consists of the content, in turn is:
   - Return value type, identifies what kind of value returns from server side: RESPONSE_NULL_VALUE - 2, RESPONSE_VALUE - 1, RESPONSE_WITH_EXCEPTION - 0.
   -  Return value, the real value returns from server.


**注意：** 对于(Variable Part)变长部分，当前版本的dubbo框架使用json序列化时，在每部分内容间额外增加了换行符作为分隔，请选手在Variable Part的每个part后额外增加换行符， 如：
```
Dubbo version bytes (换行符)
Service name bytes  (换行符)
...
```