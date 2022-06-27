# 背景
FASTJSON 2.0 是 FASTJSON 项目的重要升级，目标是为下一个十年提供一个高性能的 JSON 库，同一套 API 支持 JSON / JSONB 两种协议，JSONPath 是一等公民，支持全量解析和部分解析，支持 Java 服务端、客户端 Android、大数据场景。

而 Dubbo 当前的默认序列化协议为 Hessian 协议，存在长时间无人维护的问题，无法为未来的安全性以及兼容性做保障。

# 优势

1. FASTJSON 2.0 作为普通工具类的时候已经在缺省情况下禁用 autotype ，缺省是安全的。

2. FASTJSON 2.0 性能有了很大提升，性能非常卓越，较 Hessian 有较大的性能提升，网络传输方面 JSONB 协议较 Hessian 在复杂对象下有较大的数据压缩

3. FASTJSON 2.0 在 RPC 场景下，打开 autotype 功能后，能够实现比较完整的序列化的功能，能够覆盖 Hessian 所支持的场景（和 Hessian、JDK 序列化等一样，在 RPC 场景下无法避免存在任意反序列化问题，未来需要探索一套机制来保障通信安全）

4. FASTJSON 2.0 原生支持 JDK 17，Dubbo 可以在不添加任何特殊配置的情况下正常运行在 JDK 17 下

5. FASTJSON 2.0 支持 GraalVM Native-Image、JDK14 Record 等

# 迁移方案

TBD
