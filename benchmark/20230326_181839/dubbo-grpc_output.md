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
# Warmup Iteration   1: 2.009 ops/ms
# Warmup Iteration   2: 4.922 ops/ms
# Warmup Iteration   3: 6.767 ops/ms
Iteration   1: 7.116 ops/ms
Iteration   2: 7.377 ops/ms
Iteration   3: 7.349 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.281 ±(99.9%) 2.615 ops/ms [Average]
  (min, avg, max) = (7.116, 7.281, 7.377), stdev = 0.143
  CI (99.9%): [4.666, 9.896] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:09
# Fork: 1 of 1
# Warmup Iteration   1: 4.531 ops/ms
# Warmup Iteration   2: 7.101 ops/ms
# Warmup Iteration   3: 7.653 ops/ms
Iteration   1: 7.845 ops/ms
Iteration   2: 8.005 ops/ms
Iteration   3: 7.704 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.851 ±(99.9%) 2.750 ops/ms [Average]
  (min, avg, max) = (7.704, 7.851, 8.005), stdev = 0.151
  CI (99.9%): [5.101, 10.601] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 4.058 ops/ms
# Warmup Iteration   2: 6.745 ops/ms
# Warmup Iteration   3: 6.935 ops/ms
Iteration   1: 6.867 ops/ms
Iteration   2: 7.071 ops/ms
Iteration   3: 7.148 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.028 ±(99.9%) 2.650 ops/ms [Average]
  (min, avg, max) = (6.867, 7.028, 7.148), stdev = 0.145
  CI (99.9%): [4.379, 9.678] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.428 ops/ms
# Warmup Iteration   2: 4.716 ops/ms
# Warmup Iteration   3: 5.128 ops/ms
Iteration   1: 5.438 ops/ms
Iteration   2: 5.166 ops/ms
Iteration   3: 5.158 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.254 ±(99.9%) 2.909 ops/ms [Average]
  (min, avg, max) = (5.158, 5.254, 5.438), stdev = 0.159
  CI (99.9%): [2.346, 8.163] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 7.210 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 4.896 ±(99.9%) 0.080 ms/op
# Warmup Iteration   3: 4.699 ±(99.9%) 0.008 ms/op
Iteration   1: 4.409 ±(99.9%) 0.005 ms/op
Iteration   2: 4.539 ±(99.9%) 0.006 ms/op
Iteration   3: 4.577 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.508 ±(99.9%) 1.611 ms/op [Average]
  (min, avg, max) = (4.409, 4.508, 4.577), stdev = 0.088
  CI (99.9%): [2.897, 6.120] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.450 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 4.531 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.314 ±(99.9%) 0.007 ms/op
Iteration   1: 4.287 ±(99.9%) 0.006 ms/op
Iteration   2: 4.218 ±(99.9%) 0.004 ms/op
Iteration   3: 4.115 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.207 ±(99.9%) 1.582 ms/op [Average]
  (min, avg, max) = (4.115, 4.207, 4.287), stdev = 0.087
  CI (99.9%): [2.625, 5.789] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 7.137 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 4.892 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.723 ±(99.9%) 0.005 ms/op
Iteration   1: 4.656 ±(99.9%) 0.006 ms/op
Iteration   2: 4.505 ±(99.9%) 0.004 ms/op
Iteration   3: 4.445 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.535 ±(99.9%) 1.988 ms/op [Average]
  (min, avg, max) = (4.445, 4.535, 4.656), stdev = 0.109
  CI (99.9%): [2.548, 6.523] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 9.023 ±(99.9%) 0.070 ms/op
# Warmup Iteration   2: 6.376 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 6.042 ±(99.9%) 0.017 ms/op
Iteration   1: 5.889 ±(99.9%) 0.022 ms/op
Iteration   2: 5.819 ±(99.9%) 0.015 ms/op
Iteration   3: 5.934 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.881 ±(99.9%) 1.051 ms/op [Average]
  (min, avg, max) = (5.819, 5.881, 5.934), stdev = 0.058
  CI (99.9%): [4.830, 6.931] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 7.361 ±(99.9%) 0.097 ms/op
# Warmup Iteration   2: 4.951 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.601 ±(99.9%) 0.020 ms/op
Iteration   1: 4.429 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   1.223 ms/op
                 createUser·p0.50:   4.260 ms/op
                 createUser·p0.90:   5.554 ms/op
                 createUser·p0.95:   6.169 ms/op
                 createUser·p0.99:   10.404 ms/op
                 createUser·p0.999:  17.361 ms/op
                 createUser·p0.9999: 19.075 ms/op
                 createUser·p1.00:   19.661 ms/op

Iteration   2: 4.387 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   1.047 ms/op
                 createUser·p0.50:   4.227 ms/op
                 createUser·p0.90:   5.431 ms/op
                 createUser·p0.95:   6.013 ms/op
                 createUser·p0.99:   10.653 ms/op
                 createUser·p0.999:  16.206 ms/op
                 createUser·p0.9999: 19.469 ms/op
                 createUser·p1.00:   20.775 ms/op

Iteration   3: 4.405 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   0.962 ms/op
                 createUser·p0.50:   4.227 ms/op
                 createUser·p0.90:   5.513 ms/op
                 createUser·p0.95:   6.111 ms/op
                 createUser·p0.99:   11.239 ms/op
                 createUser·p0.999:  17.851 ms/op
                 createUser·p0.9999: 28.631 ms/op
                 createUser·p1.00:   29.032 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 217678
  mean =      4.407 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7515 
    [ 2.500,  5.000) = 168126 
    [ 5.000,  7.500) = 37848 
    [ 7.500, 10.000) = 1757 
    [10.000, 12.500) = 873 
    [12.500, 15.000) = 900 
    [15.000, 17.500) = 489 
    [17.500, 20.000) = 124 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.962 ms/op
     p(50.0000) =      4.243 ms/op
     p(90.0000) =      5.505 ms/op
     p(95.0000) =      6.095 ms/op
     p(99.0000) =     10.732 ms/op
     p(99.9000) =     17.138 ms/op
     p(99.9900) =     28.228 ms/op
     p(99.9990) =     28.923 ms/op
     p(99.9999) =     29.032 ms/op
    p(100.0000) =     29.032 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.331 ±(99.9%) 0.072 ms/op
# Warmup Iteration   2: 4.663 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.338 ±(99.9%) 0.017 ms/op
Iteration   1: 4.345 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   0.888 ms/op
                 existUser·p0.50:   4.186 ms/op
                 existUser·p0.90:   5.439 ms/op
                 existUser·p0.95:   5.931 ms/op
                 existUser·p0.99:   9.306 ms/op
                 existUser·p0.999:  17.498 ms/op
                 existUser·p0.9999: 27.841 ms/op
                 existUser·p1.00:   28.049 ms/op

Iteration   2: 4.293 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   1.155 ms/op
                 existUser·p0.50:   4.133 ms/op
                 existUser·p0.90:   5.210 ms/op
                 existUser·p0.95:   5.677 ms/op
                 existUser·p0.99:   8.722 ms/op
                 existUser·p0.999:  16.621 ms/op
                 existUser·p0.9999: 29.622 ms/op
                 existUser·p1.00:   30.540 ms/op

Iteration   3: 4.192 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   1.165 ms/op
                 existUser·p0.50:   4.063 ms/op
                 existUser·p0.90:   5.071 ms/op
                 existUser·p0.95:   5.562 ms/op
                 existUser·p0.99:   8.684 ms/op
                 existUser·p0.999:  18.938 ms/op
                 existUser·p0.9999: 24.399 ms/op
                 existUser·p1.00:   28.180 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 224530
  mean =      4.276 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5178 
    [ 2.500,  5.000) = 186654 
    [ 5.000,  7.500) = 29304 
    [ 7.500, 10.000) = 1542 
    [10.000, 12.500) = 690 
    [12.500, 15.000) = 670 
    [15.000, 17.500) = 281 
    [17.500, 20.000) = 108 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 5 
    [27.500, 30.000) = 58 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.888 ms/op
     p(50.0000) =      4.121 ms/op
     p(90.0000) =      5.251 ms/op
     p(95.0000) =      5.743 ms/op
     p(99.0000) =      8.831 ms/op
     p(99.9000) =     17.367 ms/op
     p(99.9900) =     29.214 ms/op
     p(99.9990) =     30.466 ms/op
     p(99.9999) =     30.540 ms/op
    p(100.0000) =     30.540 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 7.121 ±(99.9%) 0.086 ms/op
# Warmup Iteration   2: 4.815 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.659 ±(99.9%) 0.019 ms/op
Iteration   1: 4.410 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   0.958 ms/op
                 getUser·p0.50:   4.243 ms/op
                 getUser·p0.90:   5.587 ms/op
                 getUser·p0.95:   6.218 ms/op
                 getUser·p0.99:   11.730 ms/op
                 getUser·p0.999:  17.809 ms/op
                 getUser·p0.9999: 21.496 ms/op
                 getUser·p1.00:   22.053 ms/op

Iteration   2: 4.394 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   1.055 ms/op
                 getUser·p0.50:   4.243 ms/op
                 getUser·p0.90:   5.456 ms/op
                 getUser·p0.95:   6.005 ms/op
                 getUser·p0.99:   9.442 ms/op
                 getUser·p0.999:  16.452 ms/op
                 getUser·p0.9999: 22.404 ms/op
                 getUser·p1.00:   23.953 ms/op

Iteration   3: 4.425 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   1.122 ms/op
                 getUser·p0.50:   4.276 ms/op
                 getUser·p0.90:   5.554 ms/op
                 getUser·p0.95:   6.128 ms/op
                 getUser·p0.99:   9.847 ms/op
                 getUser·p0.999:  16.429 ms/op
                 getUser·p0.9999: 28.967 ms/op
                 getUser·p1.00:   29.196 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 217624
  mean =      4.410 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8094 
    [ 2.500,  5.000) = 166684 
    [ 5.000,  7.500) = 38893 
    [ 7.500, 10.000) = 1678 
    [10.000, 12.500) = 697 
    [12.500, 15.000) = 1010 
    [15.000, 17.500) = 411 
    [17.500, 20.000) = 61 
    [20.000, 22.500) = 61 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 21 

  Percentiles, ms/op:
      p(0.0000) =      0.958 ms/op
     p(50.0000) =      4.252 ms/op
     p(90.0000) =      5.530 ms/op
     p(95.0000) =      6.119 ms/op
     p(99.0000) =     10.256 ms/op
     p(99.9000) =     16.701 ms/op
     p(99.9900) =     25.559 ms/op
     p(99.9990) =     29.065 ms/op
     p(99.9999) =     29.196 ms/op
    p(100.0000) =     29.196 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 9.106 ±(99.9%) 0.117 ms/op
# Warmup Iteration   2: 6.594 ±(99.9%) 0.037 ms/op
# Warmup Iteration   3: 6.159 ±(99.9%) 0.029 ms/op
Iteration   1: 6.078 ±(99.9%) 0.029 ms/op
                 listUser·p0.00:   1.376 ms/op
                 listUser·p0.50:   5.636 ms/op
                 listUser·p0.90:   8.520 ms/op
                 listUser·p0.95:   9.650 ms/op
                 listUser·p0.99:   13.418 ms/op
                 listUser·p0.999:  19.202 ms/op
                 listUser·p0.9999: 23.739 ms/op
                 listUser·p1.00:   24.216 ms/op

Iteration   2: 6.178 ±(99.9%) 0.030 ms/op
                 listUser·p0.00:   1.309 ms/op
                 listUser·p0.50:   5.718 ms/op
                 listUser·p0.90:   8.569 ms/op
                 listUser·p0.95:   9.667 ms/op
                 listUser·p0.99:   14.123 ms/op
                 listUser·p0.999:  22.978 ms/op
                 listUser·p0.9999: 30.364 ms/op
                 listUser·p1.00:   31.850 ms/op

Iteration   3: 6.217 ±(99.9%) 0.031 ms/op
                 listUser·p0.00:   1.876 ms/op
                 listUser·p0.50:   5.743 ms/op
                 listUser·p0.90:   8.700 ms/op
                 listUser·p0.95:   9.880 ms/op
                 listUser·p0.99:   14.639 ms/op
                 listUser·p0.999:  21.907 ms/op
                 listUser·p0.9999: 32.065 ms/op
                 listUser·p1.00:   34.472 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 155910
  mean =      6.157 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 302 
    [ 2.500,  5.000) = 43305 
    [ 5.000,  7.500) = 83366 
    [ 7.500, 10.000) = 22205 
    [10.000, 12.500) = 4352 
    [12.500, 15.000) = 1157 
    [15.000, 17.500) = 691 
    [17.500, 20.000) = 290 
    [20.000, 22.500) = 124 
    [22.500, 25.000) = 57 
    [25.000, 27.500) = 41 
    [27.500, 30.000) = 3 
    [30.000, 32.500) = 13 
    [32.500, 35.000) = 4 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.309 ms/op
     p(50.0000) =      5.702 ms/op
     p(90.0000) =      8.602 ms/op
     p(95.0000) =      9.732 ms/op
     p(99.0000) =     14.138 ms/op
     p(99.9000) =     21.594 ms/op
     p(99.9900) =     30.403 ms/op
     p(99.9990) =     34.289 ms/op
     p(99.9999) =     34.472 ms/op
    p(100.0000) =     34.472 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.281 ± 2.615  ops/ms
ClientGrpc.existUser                       thrpt       3   7.851 ± 2.750  ops/ms
ClientGrpc.getUser                         thrpt       3   7.028 ± 2.650  ops/ms
ClientGrpc.listUser                        thrpt       3   5.254 ± 2.909  ops/ms
ClientGrpc.createUser                       avgt       3   4.508 ± 1.611   ms/op
ClientGrpc.existUser                        avgt       3   4.207 ± 1.582   ms/op
ClientGrpc.getUser                          avgt       3   4.535 ± 1.988   ms/op
ClientGrpc.listUser                         avgt       3   5.881 ± 1.051   ms/op
ClientGrpc.createUser                     sample  217678   4.407 ± 0.010   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.962           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.243           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.505           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           6.095           ms/op
ClientGrpc.createUser:createUser·p0.99    sample          10.732           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          17.138           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          28.228           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          29.032           ms/op
ClientGrpc.existUser                      sample  224530   4.276 ± 0.009   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.888           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.121           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.251           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.743           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           8.831           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          17.367           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          29.214           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          30.540           ms/op
ClientGrpc.getUser                        sample  217624   4.410 ± 0.010   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.958           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.252           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.530           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.119           ms/op
ClientGrpc.getUser:getUser·p0.99          sample          10.256           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          16.701           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          25.559           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          29.196           ms/op
ClientGrpc.listUser                       sample  155910   6.157 ± 0.017   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.309           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.702           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           8.602           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           9.732           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          14.138           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          21.594           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          30.403           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          34.472           ms/op
