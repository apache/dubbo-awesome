# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.525 ops/ms
# Warmup Iteration   2: 9.363 ops/ms
# Warmup Iteration   3: 10.121 ops/ms
Iteration   1: 10.759 ops/ms
Iteration   2: 11.248 ops/ms
Iteration   3: 10.659 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.889 ±(99.9%) 5.743 ops/ms [Average]
  (min, avg, max) = (10.659, 10.889, 11.248), stdev = 0.315
  CI (99.9%): [5.146, 16.632] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.819 ops/ms
# Warmup Iteration   2: 10.905 ops/ms
# Warmup Iteration   3: 11.320 ops/ms
Iteration   1: 11.044 ops/ms
Iteration   2: 11.109 ops/ms
Iteration   3: 11.463 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.205 ±(99.9%) 4.111 ops/ms [Average]
  (min, avg, max) = (11.044, 11.205, 11.463), stdev = 0.225
  CI (99.9%): [7.094, 15.317] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 8.268 ops/ms
# Warmup Iteration   2: 10.416 ops/ms
# Warmup Iteration   3: 10.921 ops/ms
Iteration   1: 10.763 ops/ms
Iteration   2: 10.899 ops/ms
Iteration   3: 10.718 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.793 ±(99.9%) 1.721 ops/ms [Average]
  (min, avg, max) = (10.718, 10.793, 10.899), stdev = 0.094
  CI (99.9%): [9.072, 12.514] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 6.006 ops/ms
# Warmup Iteration   2: 8.231 ops/ms
# Warmup Iteration   3: 8.250 ops/ms
Iteration   1: 8.303 ops/ms
Iteration   2: 8.231 ops/ms
Iteration   3: 8.251 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.262 ±(99.9%) 0.677 ops/ms [Average]
  (min, avg, max) = (8.231, 8.262, 8.303), stdev = 0.037
  CI (99.9%): [7.585, 8.939] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.995 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.075 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.007 ±(99.9%) 0.003 ms/op
Iteration   1: 2.925 ±(99.9%) 0.003 ms/op
Iteration   2: 2.983 ±(99.9%) 0.002 ms/op
Iteration   3: 2.955 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.954 ±(99.9%) 0.524 ms/op [Average]
  (min, avg, max) = (2.925, 2.954, 2.983), stdev = 0.029
  CI (99.9%): [2.430, 3.479] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.177 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 2.941 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.891 ±(99.9%) 0.003 ms/op
Iteration   1: 2.848 ±(99.9%) 0.003 ms/op
Iteration   2: 2.853 ±(99.9%) 0.003 ms/op
Iteration   3: 2.910 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.870 ±(99.9%) 0.629 ms/op [Average]
  (min, avg, max) = (2.848, 2.870, 2.910), stdev = 0.034
  CI (99.9%): [2.241, 3.499] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.969 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.041 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.037 ±(99.9%) 0.003 ms/op
Iteration   1: 2.980 ±(99.9%) 0.003 ms/op
Iteration   2: 2.930 ±(99.9%) 0.002 ms/op
Iteration   3: 2.922 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.944 ±(99.9%) 0.575 ms/op [Average]
  (min, avg, max) = (2.922, 2.944, 2.980), stdev = 0.031
  CI (99.9%): [2.369, 3.519] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 5.036 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.832 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.805 ±(99.9%) 0.018 ms/op
Iteration   1: 3.757 ±(99.9%) 0.004 ms/op
Iteration   2: 3.765 ±(99.9%) 0.031 ms/op
Iteration   3: 3.746 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.756 ±(99.9%) 0.174 ms/op [Average]
  (min, avg, max) = (3.746, 3.756, 3.765), stdev = 0.010
  CI (99.9%): [3.582, 3.930] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.915 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.093 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.050 ±(99.9%) 0.007 ms/op
Iteration   1: 2.958 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.645 ms/op
                 createUser·p0.50:   2.949 ms/op
                 createUser·p0.90:   3.498 ms/op
                 createUser·p0.95:   3.764 ms/op
                 createUser·p0.99:   4.440 ms/op
                 createUser·p0.999:  7.647 ms/op
                 createUser·p0.9999: 15.109 ms/op
                 createUser·p1.00:   15.352 ms/op

Iteration   2: 3.000 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.741 ms/op
                 createUser·p0.50:   2.982 ms/op
                 createUser·p0.90:   3.502 ms/op
                 createUser·p0.95:   3.711 ms/op
                 createUser·p0.99:   4.178 ms/op
                 createUser·p0.999:  6.736 ms/op
                 createUser·p0.9999: 26.618 ms/op
                 createUser·p1.00:   26.837 ms/op

Iteration   3: 2.951 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.850 ms/op
                 createUser·p0.50:   2.941 ms/op
                 createUser·p0.90:   3.461 ms/op
                 createUser·p0.95:   3.682 ms/op
                 createUser·p0.99:   4.319 ms/op
                 createUser·p0.999:  6.469 ms/op
                 createUser·p0.9999: 14.767 ms/op
                 createUser·p1.00:   16.089 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 323198
  mean =      2.969 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 29872 
    [ 2.500,  5.000) = 292223 
    [ 5.000,  7.500) = 845 
    [ 7.500, 10.000) = 55 
    [10.000, 12.500) = 43 
    [12.500, 15.000) = 106 
    [15.000, 17.500) = 22 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.645 ms/op
     p(50.0000) =      2.957 ms/op
     p(90.0000) =      3.486 ms/op
     p(95.0000) =      3.719 ms/op
     p(99.0000) =      4.325 ms/op
     p(99.9000) =      6.963 ms/op
     p(99.9900) =     22.730 ms/op
     p(99.9990) =     26.797 ms/op
     p(99.9999) =     26.837 ms/op
    p(100.0000) =     26.837 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.920 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.945 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.858 ±(99.9%) 0.006 ms/op
Iteration   1: 2.845 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.613 ms/op
                 existUser·p0.50:   2.839 ms/op
                 existUser·p0.90:   3.334 ms/op
                 existUser·p0.95:   3.654 ms/op
                 existUser·p0.99:   4.432 ms/op
                 existUser·p0.999:  7.255 ms/op
                 existUser·p0.9999: 11.911 ms/op
                 existUser·p1.00:   14.221 ms/op

Iteration   2: 2.842 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.581 ms/op
                 existUser·p0.50:   2.843 ms/op
                 existUser·p0.90:   3.322 ms/op
                 existUser·p0.95:   3.506 ms/op
                 existUser·p0.99:   4.391 ms/op
                 existUser·p0.999:  6.692 ms/op
                 existUser·p0.9999: 16.129 ms/op
                 existUser·p1.00:   17.302 ms/op

Iteration   3: 2.878 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.736 ms/op
                 existUser·p0.50:   2.859 ms/op
                 existUser·p0.90:   3.367 ms/op
                 existUser·p0.95:   3.604 ms/op
                 existUser·p0.99:   4.440 ms/op
                 existUser·p0.999:  6.955 ms/op
                 existUser·p0.9999: 13.466 ms/op
                 existUser·p1.00:   13.877 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 336226
  mean =      2.855 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3050 
    [ 1.250,  2.500) = 50052 
    [ 2.500,  3.750) = 272019 
    [ 3.750,  5.000) = 9995 
    [ 5.000,  6.250) = 553 
    [ 6.250,  7.500) = 332 
    [ 7.500,  8.750) = 64 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 23 
    [11.250, 12.500) = 42 
    [12.500, 13.750) = 27 
    [13.750, 15.000) = 27 
    [15.000, 16.250) = 31 
    [16.250, 17.500) = 10 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.581 ms/op
     p(50.0000) =      2.847 ms/op
     p(90.0000) =      3.338 ms/op
     p(95.0000) =      3.592 ms/op
     p(99.0000) =      4.424 ms/op
     p(99.9000) =      6.963 ms/op
     p(99.9900) =     15.266 ms/op
     p(99.9990) =     17.269 ms/op
     p(99.9999) =     17.302 ms/op
    p(100.0000) =     17.302 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.688 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.062 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.987 ±(99.9%) 0.006 ms/op
Iteration   1: 2.986 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.472 ms/op
                 getUser·p0.50:   2.986 ms/op
                 getUser·p0.90:   3.518 ms/op
                 getUser·p0.95:   3.740 ms/op
                 getUser·p0.99:   4.366 ms/op
                 getUser·p0.999:  8.279 ms/op
                 getUser·p0.9999: 13.308 ms/op
                 getUser·p1.00:   13.484 ms/op

Iteration   2: 2.990 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.726 ms/op
                 getUser·p0.50:   2.982 ms/op
                 getUser·p0.90:   3.469 ms/op
                 getUser·p0.95:   3.711 ms/op
                 getUser·p0.99:   4.125 ms/op
                 getUser·p0.999:  7.217 ms/op
                 getUser·p0.9999: 14.641 ms/op
                 getUser·p1.00:   14.942 ms/op

Iteration   3: 3.017 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.820 ms/op
                 getUser·p0.50:   3.002 ms/op
                 getUser·p0.90:   3.478 ms/op
                 getUser·p0.95:   3.650 ms/op
                 getUser·p0.99:   4.153 ms/op
                 getUser·p0.999:  10.208 ms/op
                 getUser·p0.9999: 22.099 ms/op
                 getUser·p1.00:   22.675 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 320059
  mean =      2.998 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23323 
    [ 2.500,  5.000) = 295541 
    [ 5.000,  7.500) = 879 
    [ 7.500, 10.000) = 96 
    [10.000, 12.500) = 84 
    [12.500, 15.000) = 103 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.472 ms/op
     p(50.0000) =      2.990 ms/op
     p(90.0000) =      3.486 ms/op
     p(95.0000) =      3.703 ms/op
     p(99.0000) =      4.243 ms/op
     p(99.9000) =      7.487 ms/op
     p(99.9900) =     20.188 ms/op
     p(99.9990) =     22.531 ms/op
     p(99.9999) =     22.675 ms/op
    p(100.0000) =     22.675 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.863 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.967 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.837 ±(99.9%) 0.010 ms/op
Iteration   1: 3.820 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.610 ms/op
                 listUser·p0.50:   3.674 ms/op
                 listUser·p0.90:   4.891 ms/op
                 listUser·p0.95:   5.759 ms/op
                 listUser·p0.99:   6.472 ms/op
                 listUser·p0.999:  12.117 ms/op
                 listUser·p0.9999: 19.235 ms/op
                 listUser·p1.00:   19.923 ms/op

Iteration   2: 3.733 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.061 ms/op
                 listUser·p0.50:   3.613 ms/op
                 listUser·p0.90:   4.379 ms/op
                 listUser·p0.95:   5.374 ms/op
                 listUser·p0.99:   6.496 ms/op
                 listUser·p0.999:  14.469 ms/op
                 listUser·p0.9999: 24.900 ms/op
                 listUser·p1.00:   25.231 ms/op

Iteration   3: 3.772 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.077 ms/op
                 listUser·p0.50:   3.633 ms/op
                 listUser·p0.90:   4.809 ms/op
                 listUser·p0.95:   5.603 ms/op
                 listUser·p0.99:   7.037 ms/op
                 listUser·p0.999:  15.008 ms/op
                 listUser·p0.9999: 28.018 ms/op
                 listUser·p1.00:   28.672 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 254111
  mean =      3.775 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7129 
    [ 2.500,  5.000) = 226363 
    [ 5.000,  7.500) = 19388 
    [ 7.500, 10.000) = 659 
    [10.000, 12.500) = 192 
    [12.500, 15.000) = 195 
    [15.000, 17.500) = 57 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 39 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 26 

  Percentiles, ms/op:
      p(0.0000) =      1.061 ms/op
     p(50.0000) =      3.637 ms/op
     p(90.0000) =      4.735 ms/op
     p(95.0000) =      5.603 ms/op
     p(99.0000) =      6.685 ms/op
     p(99.9000) =     13.875 ms/op
     p(99.9900) =     25.362 ms/op
     p(99.9990) =     28.551 ms/op
     p(99.9999) =     28.672 ms/op
    p(100.0000) =     28.672 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.889 ± 5.743  ops/ms
ClientGrpc.existUser                       thrpt       3  11.205 ± 4.111  ops/ms
ClientGrpc.getUser                         thrpt       3  10.793 ± 1.721  ops/ms
ClientGrpc.listUser                        thrpt       3   8.262 ± 0.677  ops/ms
ClientGrpc.createUser                       avgt       3   2.954 ± 0.524   ms/op
ClientGrpc.existUser                        avgt       3   2.870 ± 0.629   ms/op
ClientGrpc.getUser                          avgt       3   2.944 ± 0.575   ms/op
ClientGrpc.listUser                         avgt       3   3.756 ± 0.174   ms/op
ClientGrpc.createUser                     sample  323198   2.969 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.645           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.957           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.486           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.719           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.325           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           6.963           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          22.730           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          26.837           ms/op
ClientGrpc.existUser                      sample  336226   2.855 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.581           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.847           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.338           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.592           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.424           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.963           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.266           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.302           ms/op
ClientGrpc.getUser                        sample  320059   2.998 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.472           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.990           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.486           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.703           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.243           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.487           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.188           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.675           ms/op
ClientGrpc.listUser                       sample  254111   3.775 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.061           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.637           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.735           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.603           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.685           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.875           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.362           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          28.672           ms/op
