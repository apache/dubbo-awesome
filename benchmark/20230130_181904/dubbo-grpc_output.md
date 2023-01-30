# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.261 ops/ms
# Warmup Iteration   2: 5.670 ops/ms
# Warmup Iteration   3: 7.278 ops/ms
Iteration   1: 7.448 ops/ms
Iteration   2: 7.381 ops/ms
Iteration   3: 7.125 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.318 ±(99.9%) 3.107 ops/ms [Average]
  (min, avg, max) = (7.125, 7.318, 7.448), stdev = 0.170
  CI (99.9%): [4.212, 10.425] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:12:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.023 ops/ms
# Warmup Iteration   2: 6.811 ops/ms
# Warmup Iteration   3: 7.270 ops/ms
Iteration   1: 7.520 ops/ms
Iteration   2: 8.004 ops/ms
Iteration   3: 7.780 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.768 ±(99.9%) 4.418 ops/ms [Average]
  (min, avg, max) = (7.520, 7.768, 8.004), stdev = 0.242
  CI (99.9%): [3.350, 12.185] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 3.964 ops/ms
# Warmup Iteration   2: 6.732 ops/ms
# Warmup Iteration   3: 6.948 ops/ms
Iteration   1: 7.628 ops/ms
Iteration   2: 7.407 ops/ms
Iteration   3: 7.644 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.560 ±(99.9%) 2.414 ops/ms [Average]
  (min, avg, max) = (7.407, 7.560, 7.644), stdev = 0.132
  CI (99.9%): [5.146, 9.973] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.704 ops/ms
# Warmup Iteration   2: 5.153 ops/ms
# Warmup Iteration   3: 5.714 ops/ms
Iteration   1: 5.759 ops/ms
Iteration   2: 5.597 ops/ms
Iteration   3: 5.715 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.690 ±(99.9%) 1.527 ops/ms [Average]
  (min, avg, max) = (5.597, 5.690, 5.759), stdev = 0.084
  CI (99.9%): [4.163, 7.218] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.219 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.737 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.458 ±(99.9%) 0.006 ms/op
Iteration   1: 4.374 ±(99.9%) 0.003 ms/op
Iteration   2: 4.340 ±(99.9%) 0.004 ms/op
Iteration   3: 4.425 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.379 ±(99.9%) 0.783 ms/op [Average]
  (min, avg, max) = (4.340, 4.379, 4.425), stdev = 0.043
  CI (99.9%): [3.596, 5.163] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 5.901 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.275 ±(99.9%) 0.112 ms/op
# Warmup Iteration   3: 4.262 ±(99.9%) 0.007 ms/op
Iteration   1: 4.143 ±(99.9%) 0.004 ms/op
Iteration   2: 4.171 ±(99.9%) 0.005 ms/op
Iteration   3: 3.985 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.100 ±(99.9%) 1.830 ms/op [Average]
  (min, avg, max) = (3.985, 4.100, 4.171), stdev = 0.100
  CI (99.9%): [2.270, 5.929] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 6.955 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.599 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.187 ±(99.9%) 0.004 ms/op
Iteration   1: 4.208 ±(99.9%) 0.005 ms/op
Iteration   2: 4.322 ±(99.9%) 0.003 ms/op
Iteration   3: 4.299 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.276 ±(99.9%) 1.095 ms/op [Average]
  (min, avg, max) = (4.208, 4.276, 4.322), stdev = 0.060
  CI (99.9%): [3.181, 5.372] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 7.693 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 5.953 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 5.706 ±(99.9%) 0.033 ms/op
Iteration   1: 5.587 ±(99.9%) 0.018 ms/op
Iteration   2: 5.576 ±(99.9%) 0.024 ms/op
Iteration   3: 5.531 ±(99.9%) 0.043 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.565 ±(99.9%) 0.546 ms/op [Average]
  (min, avg, max) = (5.531, 5.565, 5.587), stdev = 0.030
  CI (99.9%): [5.019, 6.111] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 6.770 ±(99.9%) 0.082 ms/op
# Warmup Iteration   2: 4.712 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.398 ±(99.9%) 0.013 ms/op
Iteration   1: 4.320 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.106 ms/op
                 createUser·p0.50:   4.182 ms/op
                 createUser·p0.90:   5.521 ms/op
                 createUser·p0.95:   6.021 ms/op
                 createUser·p0.99:   7.905 ms/op
                 createUser·p0.999:  12.269 ms/op
                 createUser·p0.9999: 15.161 ms/op
                 createUser·p1.00:   15.466 ms/op

Iteration   2: 4.381 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   0.647 ms/op
                 createUser·p0.50:   4.268 ms/op
                 createUser·p0.90:   5.636 ms/op
                 createUser·p0.95:   6.111 ms/op
                 createUser·p0.99:   7.930 ms/op
                 createUser·p0.999:  15.384 ms/op
                 createUser·p0.9999: 21.260 ms/op
                 createUser·p1.00:   21.889 ms/op

Iteration   3: 4.133 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.031 ms/op
                 createUser·p0.50:   4.002 ms/op
                 createUser·p0.90:   5.202 ms/op
                 createUser·p0.95:   5.857 ms/op
                 createUser·p0.99:   7.774 ms/op
                 createUser·p0.999:  12.407 ms/op
                 createUser·p0.9999: 19.592 ms/op
                 createUser·p1.00:   25.821 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 224864
  mean =      4.275 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6715 
    [ 2.500,  5.000) = 176680 
    [ 5.000,  7.500) = 38571 
    [ 7.500, 10.000) = 2157 
    [10.000, 12.500) = 447 
    [12.500, 15.000) = 135 
    [15.000, 17.500) = 92 
    [17.500, 20.000) = 37 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.647 ms/op
     p(50.0000) =      4.129 ms/op
     p(90.0000) =      5.489 ms/op
     p(95.0000) =      6.013 ms/op
     p(99.0000) =      7.889 ms/op
     p(99.9000) =     13.814 ms/op
     p(99.9900) =     20.710 ms/op
     p(99.9990) =     25.584 ms/op
     p(99.9999) =     25.821 ms/op
    p(100.0000) =     25.821 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.680 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 4.308 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.125 ±(99.9%) 0.014 ms/op
Iteration   1: 4.094 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.059 ms/op
                 existUser·p0.50:   3.957 ms/op
                 existUser·p0.90:   5.210 ms/op
                 existUser·p0.95:   5.718 ms/op
                 existUser·p0.99:   7.330 ms/op
                 existUser·p0.999:  13.169 ms/op
                 existUser·p0.9999: 21.529 ms/op
                 existUser·p1.00:   21.791 ms/op

Iteration   2: 4.017 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.974 ms/op
                 existUser·p0.50:   3.899 ms/op
                 existUser·p0.90:   5.030 ms/op
                 existUser·p0.95:   5.521 ms/op
                 existUser·p0.99:   6.849 ms/op
                 existUser·p0.999:  12.469 ms/op
                 existUser·p0.9999: 18.353 ms/op
                 existUser·p1.00:   18.579 ms/op

Iteration   3: 4.203 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.664 ms/op
                 existUser·p0.50:   4.121 ms/op
                 existUser·p0.90:   5.325 ms/op
                 existUser·p0.95:   5.759 ms/op
                 existUser·p0.99:   7.291 ms/op
                 existUser·p0.999:  12.776 ms/op
                 existUser·p0.9999: 21.443 ms/op
                 existUser·p1.00:   21.594 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 234054
  mean =      4.103 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6698 
    [ 2.500,  5.000) = 195582 
    [ 5.000,  7.500) = 30002 
    [ 7.500, 10.000) = 1262 
    [10.000, 12.500) = 241 
    [12.500, 15.000) = 135 
    [15.000, 17.500) = 58 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 49 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.664 ms/op
     p(50.0000) =      3.977 ms/op
     p(90.0000) =      5.210 ms/op
     p(95.0000) =      5.669 ms/op
     p(99.0000) =      7.168 ms/op
     p(99.9000) =     12.960 ms/op
     p(99.9900) =     21.332 ms/op
     p(99.9990) =     21.703 ms/op
     p(99.9999) =     21.791 ms/op
    p(100.0000) =     21.791 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 6.352 ±(99.9%) 0.075 ms/op
# Warmup Iteration   2: 4.897 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.367 ±(99.9%) 0.013 ms/op
Iteration   1: 4.340 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.000 ms/op
                 getUser·p0.50:   4.186 ms/op
                 getUser·p0.90:   5.538 ms/op
                 getUser·p0.95:   5.972 ms/op
                 getUser·p0.99:   7.692 ms/op
                 getUser·p0.999:  14.177 ms/op
                 getUser·p0.9999: 23.165 ms/op
                 getUser·p1.00:   25.297 ms/op

Iteration   2: 4.350 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   0.799 ms/op
                 getUser·p0.50:   4.227 ms/op
                 getUser·p0.90:   5.546 ms/op
                 getUser·p0.95:   6.103 ms/op
                 getUser·p0.99:   8.151 ms/op
                 getUser·p0.999:  15.015 ms/op
                 getUser·p0.9999: 24.705 ms/op
                 getUser·p1.00:   25.559 ms/op

Iteration   3: 4.268 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.098 ms/op
                 getUser·p0.50:   4.133 ms/op
                 getUser·p0.90:   5.407 ms/op
                 getUser·p0.95:   5.964 ms/op
                 getUser·p0.99:   7.905 ms/op
                 getUser·p0.999:  12.681 ms/op
                 getUser·p0.9999: 30.852 ms/op
                 getUser·p1.00:   33.489 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 222101
  mean =      4.319 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6133 
    [ 2.500,  5.000) = 170110 
    [ 5.000,  7.500) = 42859 
    [ 7.500, 10.000) = 2166 
    [10.000, 12.500) = 495 
    [12.500, 15.000) = 164 
    [15.000, 17.500) = 68 
    [17.500, 20.000) = 34 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 8 
    [27.500, 30.000) = 5 
    [30.000, 32.500) = 25 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.799 ms/op
     p(50.0000) =      4.182 ms/op
     p(90.0000) =      5.505 ms/op
     p(95.0000) =      6.005 ms/op
     p(99.0000) =      7.913 ms/op
     p(99.9000) =     13.777 ms/op
     p(99.9900) =     30.343 ms/op
     p(99.9990) =     32.446 ms/op
     p(99.9999) =     33.489 ms/op
    p(100.0000) =     33.489 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 8.284 ±(99.9%) 0.103 ms/op
# Warmup Iteration   2: 6.088 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 5.406 ±(99.9%) 0.018 ms/op
Iteration   1: 5.459 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.825 ms/op
                 listUser·p0.50:   5.136 ms/op
                 listUser·p0.90:   7.299 ms/op
                 listUser·p0.95:   8.143 ms/op
                 listUser·p0.99:   10.682 ms/op
                 listUser·p0.999:  16.512 ms/op
                 listUser·p0.9999: 25.526 ms/op
                 listUser·p1.00:   25.887 ms/op

Iteration   2: 5.526 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.284 ms/op
                 listUser·p0.50:   5.218 ms/op
                 listUser·p0.90:   7.479 ms/op
                 listUser·p0.95:   8.274 ms/op
                 listUser·p0.99:   10.191 ms/op
                 listUser·p0.999:  17.760 ms/op
                 listUser·p0.9999: 22.828 ms/op
                 listUser·p1.00:   23.298 ms/op

Iteration   3: 5.602 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   1.516 ms/op
                 listUser·p0.50:   5.235 ms/op
                 listUser·p0.90:   7.651 ms/op
                 listUser·p0.95:   8.569 ms/op
                 listUser·p0.99:   10.685 ms/op
                 listUser·p0.999:  19.426 ms/op
                 listUser·p0.9999: 22.531 ms/op
                 listUser·p1.00:   24.576 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 173532
  mean =      5.529 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 190 
    [ 2.500,  5.000) = 73061 
    [ 5.000,  7.500) = 83376 
    [ 7.500, 10.000) = 14421 
    [10.000, 12.500) = 1816 
    [12.500, 15.000) = 341 
    [15.000, 17.500) = 129 
    [17.500, 20.000) = 84 
    [20.000, 22.500) = 68 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 18 

  Percentiles, ms/op:
      p(0.0000) =      1.284 ms/op
     p(50.0000) =      5.194 ms/op
     p(90.0000) =      7.463 ms/op
     p(95.0000) =      8.339 ms/op
     p(99.0000) =     10.530 ms/op
     p(99.9000) =     17.874 ms/op
     p(99.9900) =     25.023 ms/op
     p(99.9990) =     25.790 ms/op
     p(99.9999) =     25.887 ms/op
    p(100.0000) =     25.887 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.318 ± 3.107  ops/ms
ClientGrpc.existUser                       thrpt       3   7.768 ± 4.418  ops/ms
ClientGrpc.getUser                         thrpt       3   7.560 ± 2.414  ops/ms
ClientGrpc.listUser                        thrpt       3   5.690 ± 1.527  ops/ms
ClientGrpc.createUser                       avgt       3   4.379 ± 0.783   ms/op
ClientGrpc.existUser                        avgt       3   4.100 ± 1.830   ms/op
ClientGrpc.getUser                          avgt       3   4.276 ± 1.095   ms/op
ClientGrpc.listUser                         avgt       3   5.565 ± 0.546   ms/op
ClientGrpc.createUser                     sample  224864   4.275 ± 0.008   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.647           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.129           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.489           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           6.013           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.889           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.814           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.710           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          25.821           ms/op
ClientGrpc.existUser                      sample  234054   4.103 ± 0.007   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.664           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.977           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.210           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.669           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.168           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          12.960           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          21.332           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.791           ms/op
ClientGrpc.getUser                        sample  222101   4.319 ± 0.008   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.799           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.182           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.505           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.005           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.913           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          13.777           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          30.343           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          33.489           ms/op
ClientGrpc.listUser                       sample  173532   5.529 ± 0.012   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.284           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.194           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.463           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.339           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.530           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.874           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.023           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.887           ms/op
