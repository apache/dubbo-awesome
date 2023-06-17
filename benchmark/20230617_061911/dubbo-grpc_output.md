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
# Warmup Iteration   1: 4.511 ops/ms
# Warmup Iteration   2: 8.957 ops/ms
# Warmup Iteration   3: 10.481 ops/ms
Iteration   1: 10.651 ops/ms
Iteration   2: 10.696 ops/ms
Iteration   3: 10.536 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.628 ±(99.9%) 1.509 ops/ms [Average]
  (min, avg, max) = (10.536, 10.628, 10.696), stdev = 0.083
  CI (99.9%): [9.118, 12.137] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 8.252 ops/ms
# Warmup Iteration   2: 10.925 ops/ms
# Warmup Iteration   3: 11.278 ops/ms
Iteration   1: 11.288 ops/ms
Iteration   2: 11.282 ops/ms
Iteration   3: 11.333 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.301 ±(99.9%) 0.505 ops/ms [Average]
  (min, avg, max) = (11.282, 11.301, 11.333), stdev = 0.028
  CI (99.9%): [10.796, 11.806] (assumes normal distribution)


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
# Warmup Iteration   1: 7.557 ops/ms
# Warmup Iteration   2: 10.630 ops/ms
# Warmup Iteration   3: 10.802 ops/ms
Iteration   1: 10.864 ops/ms
Iteration   2: 10.813 ops/ms
Iteration   3: 10.704 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.793 ±(99.9%) 1.491 ops/ms [Average]
  (min, avg, max) = (10.704, 10.793, 10.864), stdev = 0.082
  CI (99.9%): [9.303, 12.284] (assumes normal distribution)


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
# Warmup Iteration   1: 6.843 ops/ms
# Warmup Iteration   2: 7.971 ops/ms
# Warmup Iteration   3: 8.383 ops/ms
Iteration   1: 8.707 ops/ms
Iteration   2: 8.404 ops/ms
Iteration   3: 8.597 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.569 ±(99.9%) 2.804 ops/ms [Average]
  (min, avg, max) = (8.404, 8.569, 8.707), stdev = 0.154
  CI (99.9%): [5.765, 11.373] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 4.073 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.076 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.015 ±(99.9%) 0.003 ms/op
Iteration   1: 2.951 ±(99.9%) 0.004 ms/op
Iteration   2: 2.993 ±(99.9%) 0.003 ms/op
Iteration   3: 2.953 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.966 ±(99.9%) 0.425 ms/op [Average]
  (min, avg, max) = (2.951, 2.966, 2.993), stdev = 0.023
  CI (99.9%): [2.540, 3.391] (assumes normal distribution)


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
# Warmup Iteration   1: 3.581 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 2.968 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.880 ±(99.9%) 0.003 ms/op
Iteration   1: 2.857 ±(99.9%) 0.004 ms/op
Iteration   2: 2.856 ±(99.9%) 0.003 ms/op
Iteration   3: 2.859 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.857 ±(99.9%) 0.027 ms/op [Average]
  (min, avg, max) = (2.856, 2.857, 2.859), stdev = 0.001
  CI (99.9%): [2.830, 2.884] (assumes normal distribution)


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
# Warmup Iteration   1: 3.859 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.018 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.021 ±(99.9%) 0.003 ms/op
Iteration   1: 3.014 ±(99.9%) 0.003 ms/op
Iteration   2: 2.966 ±(99.9%) 0.003 ms/op
Iteration   3: 3.016 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.999 ±(99.9%) 0.518 ms/op [Average]
  (min, avg, max) = (2.966, 2.999, 3.016), stdev = 0.028
  CI (99.9%): [2.481, 3.516] (assumes normal distribution)


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
# Warmup Iteration   1: 5.016 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.923 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 3.787 ±(99.9%) 0.028 ms/op
Iteration   1: 3.761 ±(99.9%) 0.012 ms/op
Iteration   2: 3.749 ±(99.9%) 0.025 ms/op
Iteration   3: 3.786 ±(99.9%) 0.026 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.765 ±(99.9%) 0.340 ms/op [Average]
  (min, avg, max) = (3.749, 3.765, 3.786), stdev = 0.019
  CI (99.9%): [3.425, 4.106] (assumes normal distribution)


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
# Warmup Iteration   1: 4.101 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.080 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.972 ±(99.9%) 0.007 ms/op
Iteration   1: 2.937 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.337 ms/op
                 createUser·p0.50:   2.945 ms/op
                 createUser·p0.90:   3.355 ms/op
                 createUser·p0.95:   3.600 ms/op
                 createUser·p0.99:   4.522 ms/op
                 createUser·p0.999:  7.925 ms/op
                 createUser·p0.9999: 24.358 ms/op
                 createUser·p1.00:   25.461 ms/op

Iteration   2: 2.964 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.580 ms/op
                 createUser·p0.50:   2.937 ms/op
                 createUser·p0.90:   3.424 ms/op
                 createUser·p0.95:   3.654 ms/op
                 createUser·p0.99:   4.399 ms/op
                 createUser·p0.999:  20.709 ms/op
                 createUser·p0.9999: 23.370 ms/op
                 createUser·p1.00:   23.986 ms/op

Iteration   3: 2.966 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.504 ms/op
                 createUser·p0.50:   2.949 ms/op
                 createUser·p0.90:   3.453 ms/op
                 createUser·p0.95:   3.671 ms/op
                 createUser·p0.99:   4.399 ms/op
                 createUser·p0.999:  7.005 ms/op
                 createUser·p0.9999: 27.434 ms/op
                 createUser·p1.00:   27.754 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 324730
  mean =      2.956 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 32067 
    [ 2.500,  5.000) = 291094 
    [ 5.000,  7.500) = 1186 
    [ 7.500, 10.000) = 123 
    [10.000, 12.500) = 4 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 101 
    [22.500, 25.000) = 76 
    [25.000, 27.500) = 30 

  Percentiles, ms/op:
      p(0.0000) =      0.337 ms/op
     p(50.0000) =      2.945 ms/op
     p(90.0000) =      3.412 ms/op
     p(95.0000) =      3.645 ms/op
     p(99.0000) =      4.432 ms/op
     p(99.9000) =      8.049 ms/op
     p(99.9900) =     25.478 ms/op
     p(99.9990) =     27.681 ms/op
     p(99.9999) =     27.754 ms/op
    p(100.0000) =     27.754 ms/op


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
# Warmup Iteration   1: 3.518 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 2.937 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.798 ±(99.9%) 0.006 ms/op
Iteration   1: 2.855 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.697 ms/op
                 existUser·p0.50:   2.843 ms/op
                 existUser·p0.90:   3.314 ms/op
                 existUser·p0.95:   3.555 ms/op
                 existUser·p0.99:   4.268 ms/op
                 existUser·p0.999:  8.421 ms/op
                 existUser·p0.9999: 13.399 ms/op
                 existUser·p1.00:   14.533 ms/op

Iteration   2: 2.839 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.650 ms/op
                 existUser·p0.50:   2.843 ms/op
                 existUser·p0.90:   3.359 ms/op
                 existUser·p0.95:   3.592 ms/op
                 existUser·p0.99:   4.342 ms/op
                 existUser·p0.999:  6.429 ms/op
                 existUser·p0.9999: 12.980 ms/op
                 existUser·p1.00:   13.451 ms/op

Iteration   3: 2.826 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.633 ms/op
                 existUser·p0.50:   2.826 ms/op
                 existUser·p0.90:   3.342 ms/op
                 existUser·p0.95:   3.637 ms/op
                 existUser·p0.99:   4.489 ms/op
                 existUser·p0.999:  5.923 ms/op
                 existUser·p0.9999: 25.516 ms/op
                 existUser·p1.00:   25.919 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 337713
  mean =      2.840 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 53421 
    [ 2.500,  5.000) = 283300 
    [ 5.000,  7.500) = 725 
    [ 7.500, 10.000) = 98 
    [10.000, 12.500) = 79 
    [12.500, 15.000) = 58 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.633 ms/op
     p(50.0000) =      2.839 ms/op
     p(90.0000) =      3.338 ms/op
     p(95.0000) =      3.596 ms/op
     p(99.0000) =      4.391 ms/op
     p(99.9000) =      6.339 ms/op
     p(99.9900) =     14.495 ms/op
     p(99.9990) =     25.842 ms/op
     p(99.9999) =     25.919 ms/op
    p(100.0000) =     25.919 ms/op


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
# Warmup Iteration   1: 3.965 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.088 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.962 ±(99.9%) 0.006 ms/op
Iteration   1: 2.944 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.781 ms/op
                 getUser·p0.50:   2.937 ms/op
                 getUser·p0.90:   3.502 ms/op
                 getUser·p0.95:   3.789 ms/op
                 getUser·p0.99:   4.481 ms/op
                 getUser·p0.999:  10.098 ms/op
                 getUser·p0.9999: 11.518 ms/op
                 getUser·p1.00:   11.813 ms/op

Iteration   2: 2.931 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.357 ms/op
                 getUser·p0.50:   2.941 ms/op
                 getUser·p0.90:   3.396 ms/op
                 getUser·p0.95:   3.670 ms/op
                 getUser·p0.99:   4.342 ms/op
                 getUser·p0.999:  6.782 ms/op
                 getUser·p0.9999: 20.090 ms/op
                 getUser·p1.00:   20.447 ms/op

Iteration   3: 2.986 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.602 ms/op
                 getUser·p0.50:   2.978 ms/op
                 getUser·p0.90:   3.576 ms/op
                 getUser·p0.95:   3.764 ms/op
                 getUser·p0.99:   4.342 ms/op
                 getUser·p0.999:  7.663 ms/op
                 getUser·p0.9999: 16.384 ms/op
                 getUser·p1.00:   17.007 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 324952
  mean =      2.954 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 36125 
    [ 2.500,  5.000) = 287564 
    [ 5.000,  7.500) = 943 
    [ 7.500, 10.000) = 66 
    [10.000, 12.500) = 130 
    [12.500, 15.000) = 81 
    [15.000, 17.500) = 11 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.357 ms/op
     p(50.0000) =      2.953 ms/op
     p(90.0000) =      3.498 ms/op
     p(95.0000) =      3.744 ms/op
     p(99.0000) =      4.383 ms/op
     p(99.9000) =      7.422 ms/op
     p(99.9900) =     18.148 ms/op
     p(99.9990) =     20.374 ms/op
     p(99.9999) =     20.447 ms/op
    p(100.0000) =     20.447 ms/op


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
# Warmup Iteration   1: 5.172 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.835 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.762 ±(99.9%) 0.010 ms/op
Iteration   1: 3.781 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.063 ms/op
                 listUser·p0.50:   3.662 ms/op
                 listUser·p0.90:   4.399 ms/op
                 listUser·p0.95:   5.210 ms/op
                 listUser·p0.99:   6.529 ms/op
                 listUser·p0.999:  12.295 ms/op
                 listUser·p0.9999: 13.608 ms/op
                 listUser·p1.00:   15.466 ms/op

Iteration   2: 3.778 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.757 ms/op
                 listUser·p0.50:   3.686 ms/op
                 listUser·p0.90:   4.407 ms/op
                 listUser·p0.95:   5.382 ms/op
                 listUser·p0.99:   6.619 ms/op
                 listUser·p0.999:  13.423 ms/op
                 listUser·p0.9999: 16.597 ms/op
                 listUser·p1.00:   17.105 ms/op

Iteration   3: 3.766 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.171 ms/op
                 listUser·p0.50:   3.633 ms/op
                 listUser·p0.90:   4.710 ms/op
                 listUser·p0.95:   5.464 ms/op
                 listUser·p0.99:   6.521 ms/op
                 listUser·p0.999:  14.485 ms/op
                 listUser·p0.9999: 26.182 ms/op
                 listUser·p1.00:   27.132 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 254120
  mean =      3.775 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6000 
    [ 2.500,  5.000) = 231235 
    [ 5.000,  7.500) = 15788 
    [ 7.500, 10.000) = 522 
    [10.000, 12.500) = 241 
    [12.500, 15.000) = 246 
    [15.000, 17.500) = 60 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 22 

  Percentiles, ms/op:
      p(0.0000) =      0.757 ms/op
     p(50.0000) =      3.662 ms/op
     p(90.0000) =      4.522 ms/op
     p(95.0000) =      5.366 ms/op
     p(99.0000) =      6.562 ms/op
     p(99.9000) =     13.058 ms/op
     p(99.9900) =     19.132 ms/op
     p(99.9990) =     27.079 ms/op
     p(99.9999) =     27.132 ms/op
    p(100.0000) =     27.132 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.628 ± 1.509  ops/ms
ClientGrpc.existUser                       thrpt       3  11.301 ± 0.505  ops/ms
ClientGrpc.getUser                         thrpt       3  10.793 ± 1.491  ops/ms
ClientGrpc.listUser                        thrpt       3   8.569 ± 2.804  ops/ms
ClientGrpc.createUser                       avgt       3   2.966 ± 0.425   ms/op
ClientGrpc.existUser                        avgt       3   2.857 ± 0.027   ms/op
ClientGrpc.getUser                          avgt       3   2.999 ± 0.518   ms/op
ClientGrpc.listUser                         avgt       3   3.765 ± 0.340   ms/op
ClientGrpc.createUser                     sample  324730   2.956 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.337           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.945           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.412           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.645           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.432           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.049           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          25.478           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          27.754           ms/op
ClientGrpc.existUser                      sample  337713   2.840 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.633           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.839           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.338           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.596           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.391           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.339           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.495           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          25.919           ms/op
ClientGrpc.getUser                        sample  324952   2.954 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.357           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.953           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.498           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.744           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.383           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.422           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.148           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.447           ms/op
ClientGrpc.listUser                       sample  254120   3.775 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.757           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.662           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.522           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.366           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.562           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.058           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          19.132           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.132           ms/op
