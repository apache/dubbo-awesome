# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.389 ops/ms
# Warmup Iteration   2: 9.339 ops/ms
# Warmup Iteration   3: 10.296 ops/ms
Iteration   1: 10.461 ops/ms
Iteration   2: 10.534 ops/ms
Iteration   3: 10.625 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.540 ±(99.9%) 1.498 ops/ms [Average]
  (min, avg, max) = (10.461, 10.540, 10.625), stdev = 0.082
  CI (99.9%): [9.042, 12.039] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 7.906 ops/ms
# Warmup Iteration   2: 10.471 ops/ms
# Warmup Iteration   3: 11.081 ops/ms
Iteration   1: 11.153 ops/ms
Iteration   2: 10.877 ops/ms
Iteration   3: 11.075 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.035 ±(99.9%) 2.594 ops/ms [Average]
  (min, avg, max) = (10.877, 11.035, 11.153), stdev = 0.142
  CI (99.9%): [8.441, 13.629] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 7.328 ops/ms
# Warmup Iteration   2: 10.131 ops/ms
# Warmup Iteration   3: 10.606 ops/ms
Iteration   1: 10.473 ops/ms
Iteration   2: 10.703 ops/ms
Iteration   3: 10.549 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.575 ±(99.9%) 2.137 ops/ms [Average]
  (min, avg, max) = (10.473, 10.575, 10.703), stdev = 0.117
  CI (99.9%): [8.438, 12.712] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.638 ops/ms
# Warmup Iteration   2: 7.685 ops/ms
# Warmup Iteration   3: 7.913 ops/ms
Iteration   1: 7.960 ops/ms
Iteration   2: 8.099 ops/ms
Iteration   3: 8.070 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.043 ±(99.9%) 1.340 ops/ms [Average]
  (min, avg, max) = (7.960, 8.043, 8.099), stdev = 0.073
  CI (99.9%): [6.702, 9.383] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.095 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.184 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.008 ±(99.9%) 0.002 ms/op
Iteration   1: 3.031 ±(99.9%) 0.002 ms/op
Iteration   2: 2.991 ±(99.9%) 0.002 ms/op
Iteration   3: 3.057 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.026 ±(99.9%) 0.602 ms/op [Average]
  (min, avg, max) = (2.991, 3.026, 3.057), stdev = 0.033
  CI (99.9%): [2.425, 3.628] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.886 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.962 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.889 ±(99.9%) 0.004 ms/op
Iteration   1: 2.917 ±(99.9%) 0.003 ms/op
Iteration   2: 2.889 ±(99.9%) 0.003 ms/op
Iteration   3: 2.871 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.892 ±(99.9%) 0.425 ms/op [Average]
  (min, avg, max) = (2.871, 2.892, 2.917), stdev = 0.023
  CI (99.9%): [2.467, 3.318] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.307 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.127 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.037 ±(99.9%) 0.002 ms/op
Iteration   1: 2.986 ±(99.9%) 0.003 ms/op
Iteration   2: 3.018 ±(99.9%) 0.006 ms/op
Iteration   3: 2.962 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.988 ±(99.9%) 0.515 ms/op [Average]
  (min, avg, max) = (2.962, 2.988, 3.018), stdev = 0.028
  CI (99.9%): [2.474, 3.503] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.097 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 4.005 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 3.932 ±(99.9%) 0.007 ms/op
Iteration   1: 3.909 ±(99.9%) 0.015 ms/op
Iteration   2: 3.933 ±(99.9%) 0.008 ms/op
Iteration   3: 3.960 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.934 ±(99.9%) 0.473 ms/op [Average]
  (min, avg, max) = (3.909, 3.934, 3.960), stdev = 0.026
  CI (99.9%): [3.462, 4.407] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.862 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.122 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.058 ±(99.9%) 0.007 ms/op
Iteration   1: 3.020 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.707 ms/op
                 createUser·p0.50:   3.002 ms/op
                 createUser·p0.90:   3.543 ms/op
                 createUser·p0.95:   3.883 ms/op
                 createUser·p0.99:   4.628 ms/op
                 createUser·p0.999:  8.996 ms/op
                 createUser·p0.9999: 19.445 ms/op
                 createUser·p1.00:   19.726 ms/op

Iteration   2: 3.058 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.687 ms/op
                 createUser·p0.50:   3.027 ms/op
                 createUser·p0.90:   3.662 ms/op
                 createUser·p0.95:   3.871 ms/op
                 createUser·p0.99:   4.440 ms/op
                 createUser·p0.999:  8.813 ms/op
                 createUser·p0.9999: 15.468 ms/op
                 createUser·p1.00:   16.613 ms/op

Iteration   3: 3.027 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.580 ms/op
                 createUser·p0.50:   2.998 ms/op
                 createUser·p0.90:   3.523 ms/op
                 createUser·p0.95:   3.719 ms/op
                 createUser·p0.99:   4.620 ms/op
                 createUser·p0.999:  8.137 ms/op
                 createUser·p0.9999: 14.778 ms/op
                 createUser·p1.00:   15.155 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 316223
  mean =      3.035 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1507 
    [ 1.250,  2.500) = 23360 
    [ 2.500,  3.750) = 271645 
    [ 3.750,  5.000) = 17704 
    [ 5.000,  6.250) = 959 
    [ 6.250,  7.500) = 474 
    [ 7.500,  8.750) = 262 
    [ 8.750, 10.000) = 58 
    [10.000, 11.250) = 40 
    [11.250, 12.500) = 40 
    [12.500, 13.750) = 27 
    [13.750, 15.000) = 84 
    [15.000, 16.250) = 26 
    [16.250, 17.500) = 5 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.580 ms/op
     p(50.0000) =      3.011 ms/op
     p(90.0000) =      3.584 ms/op
     p(95.0000) =      3.826 ms/op
     p(99.0000) =      4.563 ms/op
     p(99.9000) =      8.680 ms/op
     p(99.9900) =     18.821 ms/op
     p(99.9990) =     19.655 ms/op
     p(99.9999) =     19.726 ms/op
    p(100.0000) =     19.726 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.649 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 2.999 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.937 ±(99.9%) 0.007 ms/op
Iteration   1: 2.920 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.625 ms/op
                 existUser·p0.50:   2.912 ms/op
                 existUser·p0.90:   3.441 ms/op
                 existUser·p0.95:   3.625 ms/op
                 existUser·p0.99:   4.376 ms/op
                 existUser·p0.999:  8.022 ms/op
                 existUser·p0.9999: 17.696 ms/op
                 existUser·p1.00:   18.219 ms/op

Iteration   2: 2.933 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.828 ms/op
                 existUser·p0.50:   2.904 ms/op
                 existUser·p0.90:   3.416 ms/op
                 existUser·p0.95:   3.629 ms/op
                 existUser·p0.99:   4.503 ms/op
                 existUser·p0.999:  8.433 ms/op
                 existUser·p0.9999: 12.928 ms/op
                 existUser·p1.00:   14.615 ms/op

Iteration   3: 2.962 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.698 ms/op
                 existUser·p0.50:   2.920 ms/op
                 existUser·p0.90:   3.416 ms/op
                 existUser·p0.95:   3.568 ms/op
                 existUser·p0.99:   4.358 ms/op
                 existUser·p0.999:  8.930 ms/op
                 existUser·p0.9999: 25.559 ms/op
                 existUser·p1.00:   27.034 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 326795
  mean =      2.938 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 36529 
    [ 2.500,  5.000) = 288483 
    [ 5.000,  7.500) = 1244 
    [ 7.500, 10.000) = 331 
    [10.000, 12.500) = 65 
    [12.500, 15.000) = 73 
    [15.000, 17.500) = 23 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 23 

  Percentiles, ms/op:
      p(0.0000) =      0.625 ms/op
     p(50.0000) =      2.912 ms/op
     p(90.0000) =      3.424 ms/op
     p(95.0000) =      3.609 ms/op
     p(99.0000) =      4.415 ms/op
     p(99.9000) =      8.382 ms/op
     p(99.9900) =     20.308 ms/op
     p(99.9990) =     25.729 ms/op
     p(99.9999) =     27.034 ms/op
    p(100.0000) =     27.034 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.189 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.194 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.102 ±(99.9%) 0.006 ms/op
Iteration   1: 3.011 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.722 ms/op
                 getUser·p0.50:   3.015 ms/op
                 getUser·p0.90:   3.564 ms/op
                 getUser·p0.95:   3.785 ms/op
                 getUser·p0.99:   4.473 ms/op
                 getUser·p0.999:  8.128 ms/op
                 getUser·p0.9999: 11.502 ms/op
                 getUser·p1.00:   11.747 ms/op

Iteration   2: 3.018 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.760 ms/op
                 getUser·p0.50:   3.006 ms/op
                 getUser·p0.90:   3.580 ms/op
                 getUser·p0.95:   3.793 ms/op
                 getUser·p0.99:   4.641 ms/op
                 getUser·p0.999:  7.864 ms/op
                 getUser·p0.9999: 19.137 ms/op
                 getUser·p1.00:   19.333 ms/op

Iteration   3: 2.969 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.618 ms/op
                 getUser·p0.50:   2.978 ms/op
                 getUser·p0.90:   3.453 ms/op
                 getUser·p0.95:   3.670 ms/op
                 getUser·p0.99:   4.506 ms/op
                 getUser·p0.999:  7.080 ms/op
                 getUser·p0.9999: 15.388 ms/op
                 getUser·p1.00:   15.794 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 320072
  mean =      2.999 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2772 
    [ 1.250,  2.500) = 25183 
    [ 2.500,  3.750) = 275210 
    [ 3.750,  5.000) = 14995 
    [ 5.000,  6.250) = 1055 
    [ 6.250,  7.500) = 447 
    [ 7.500,  8.750) = 209 
    [ 8.750, 10.000) = 9 
    [10.000, 11.250) = 30 
    [11.250, 12.500) = 34 
    [12.500, 13.750) = 34 
    [13.750, 15.000) = 33 
    [15.000, 16.250) = 29 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.618 ms/op
     p(50.0000) =      2.998 ms/op
     p(90.0000) =      3.531 ms/op
     p(95.0000) =      3.768 ms/op
     p(99.0000) =      4.547 ms/op
     p(99.9000) =      7.782 ms/op
     p(99.9900) =     18.592 ms/op
     p(99.9990) =     19.294 ms/op
     p(99.9999) =     19.333 ms/op
    p(100.0000) =     19.333 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.918 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.167 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.941 ±(99.9%) 0.011 ms/op
Iteration   1: 3.955 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.145 ms/op
                 listUser·p0.50:   3.789 ms/op
                 listUser·p0.90:   5.022 ms/op
                 listUser·p0.95:   5.759 ms/op
                 listUser·p0.99:   7.070 ms/op
                 listUser·p0.999:  13.173 ms/op
                 listUser·p0.9999: 19.028 ms/op
                 listUser·p1.00:   19.530 ms/op

Iteration   2: 3.849 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.963 ms/op
                 listUser·p0.50:   3.740 ms/op
                 listUser·p0.90:   4.342 ms/op
                 listUser·p0.95:   5.161 ms/op
                 listUser·p0.99:   6.734 ms/op
                 listUser·p0.999:  13.597 ms/op
                 listUser·p0.9999: 20.120 ms/op
                 listUser·p1.00:   21.922 ms/op

Iteration   3: 3.944 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.247 ms/op
                 listUser·p0.50:   3.768 ms/op
                 listUser·p0.90:   5.005 ms/op
                 listUser·p0.95:   5.710 ms/op
                 listUser·p0.99:   7.053 ms/op
                 listUser·p0.999:  14.040 ms/op
                 listUser·p0.9999: 17.367 ms/op
                 listUser·p1.00:   20.316 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 245159
  mean =      3.915 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3525 
    [ 2.500,  5.000) = 220609 
    [ 5.000,  7.500) = 19518 
    [ 7.500, 10.000) = 988 
    [10.000, 12.500) = 113 
    [12.500, 15.000) = 285 
    [15.000, 17.500) = 51 
    [17.500, 20.000) = 49 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.963 ms/op
     p(50.0000) =      3.764 ms/op
     p(90.0000) =      4.850 ms/op
     p(95.0000) =      5.620 ms/op
     p(99.0000) =      6.955 ms/op
     p(99.9000) =     13.681 ms/op
     p(99.9900) =     19.677 ms/op
     p(99.9990) =     21.797 ms/op
     p(99.9999) =     21.922 ms/op
    p(100.0000) =     21.922 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.540 ± 1.498  ops/ms
ClientGrpc.existUser                       thrpt       3  11.035 ± 2.594  ops/ms
ClientGrpc.getUser                         thrpt       3  10.575 ± 2.137  ops/ms
ClientGrpc.listUser                        thrpt       3   8.043 ± 1.340  ops/ms
ClientGrpc.createUser                       avgt       3   3.026 ± 0.602   ms/op
ClientGrpc.existUser                        avgt       3   2.892 ± 0.425   ms/op
ClientGrpc.getUser                          avgt       3   2.988 ± 0.515   ms/op
ClientGrpc.listUser                         avgt       3   3.934 ± 0.473   ms/op
ClientGrpc.createUser                     sample  316223   3.035 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.580           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.011           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.584           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.826           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.563           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.680           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.821           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          19.726           ms/op
ClientGrpc.existUser                      sample  326795   2.938 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.625           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.912           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.424           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.609           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.415           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.382           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.308           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          27.034           ms/op
ClientGrpc.getUser                        sample  320072   2.999 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.618           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.998           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.531           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.768           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.547           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.782           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.592           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.333           ms/op
ClientGrpc.listUser                       sample  245159   3.915 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.963           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.764           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.850           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.620           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.955           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.681           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          19.677           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          21.922           ms/op
