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
# Warmup Iteration   1: 3.988 ops/ms
# Warmup Iteration   2: 9.028 ops/ms
# Warmup Iteration   3: 10.359 ops/ms
Iteration   1: 10.485 ops/ms
Iteration   2: 10.511 ops/ms
Iteration   3: 10.810 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.602 ±(99.9%) 3.292 ops/ms [Average]
  (min, avg, max) = (10.485, 10.602, 10.810), stdev = 0.180
  CI (99.9%): [7.309, 13.894] (assumes normal distribution)


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
# Warmup Iteration   1: 7.597 ops/ms
# Warmup Iteration   2: 10.689 ops/ms
# Warmup Iteration   3: 11.021 ops/ms
Iteration   1: 11.273 ops/ms
Iteration   2: 11.071 ops/ms
Iteration   3: 11.271 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.205 ±(99.9%) 2.116 ops/ms [Average]
  (min, avg, max) = (11.071, 11.205, 11.273), stdev = 0.116
  CI (99.9%): [9.089, 13.321] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.158 ops/ms
# Warmup Iteration   2: 10.247 ops/ms
# Warmup Iteration   3: 10.612 ops/ms
Iteration   1: 10.630 ops/ms
Iteration   2: 10.554 ops/ms
Iteration   3: 10.578 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.587 ±(99.9%) 0.710 ops/ms [Average]
  (min, avg, max) = (10.554, 10.587, 10.630), stdev = 0.039
  CI (99.9%): [9.878, 11.297] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.768 ops/ms
# Warmup Iteration   2: 7.556 ops/ms
# Warmup Iteration   3: 8.008 ops/ms
Iteration   1: 8.006 ops/ms
Iteration   2: 8.013 ops/ms
Iteration   3: 7.937 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.985 ±(99.9%) 0.764 ops/ms [Average]
  (min, avg, max) = (7.937, 7.985, 8.013), stdev = 0.042
  CI (99.9%): [7.221, 8.749] (assumes normal distribution)


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
# Warmup Iteration   1: 4.104 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.206 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.072 ±(99.9%) 0.003 ms/op
Iteration   1: 3.022 ±(99.9%) 0.002 ms/op
Iteration   2: 3.025 ±(99.9%) 0.002 ms/op
Iteration   3: 3.037 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.028 ±(99.9%) 0.141 ms/op [Average]
  (min, avg, max) = (3.022, 3.028, 3.037), stdev = 0.008
  CI (99.9%): [2.887, 3.168] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 4.063 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 2.999 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.932 ±(99.9%) 0.002 ms/op
Iteration   1: 2.937 ±(99.9%) 0.002 ms/op
Iteration   2: 2.823 ±(99.9%) 0.002 ms/op
Iteration   3: 2.886 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.882 ±(99.9%) 1.039 ms/op [Average]
  (min, avg, max) = (2.823, 2.882, 2.937), stdev = 0.057
  CI (99.9%): [1.843, 3.921] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.234 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.140 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.055 ±(99.9%) 0.002 ms/op
Iteration   1: 3.033 ±(99.9%) 0.002 ms/op
Iteration   2: 3.009 ±(99.9%) 0.002 ms/op
Iteration   3: 2.997 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.013 ±(99.9%) 0.336 ms/op [Average]
  (min, avg, max) = (2.997, 3.013, 3.033), stdev = 0.018
  CI (99.9%): [2.678, 3.349] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.380 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.062 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.995 ±(99.9%) 0.030 ms/op
Iteration   1: 3.953 ±(99.9%) 0.007 ms/op
Iteration   2: 3.900 ±(99.9%) 0.013 ms/op
Iteration   3: 3.958 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.937 ±(99.9%) 0.590 ms/op [Average]
  (min, avg, max) = (3.900, 3.937, 3.958), stdev = 0.032
  CI (99.9%): [3.347, 4.527] (assumes normal distribution)


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
# Warmup Iteration   1: 3.964 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.184 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.075 ±(99.9%) 0.006 ms/op
Iteration   1: 3.075 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.878 ms/op
                 createUser·p0.50:   3.039 ms/op
                 createUser·p0.90:   3.711 ms/op
                 createUser·p0.95:   3.949 ms/op
                 createUser·p0.99:   4.628 ms/op
                 createUser·p0.999:  6.857 ms/op
                 createUser·p0.9999: 16.928 ms/op
                 createUser·p1.00:   17.400 ms/op

Iteration   2: 3.035 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.880 ms/op
                 createUser·p0.50:   3.019 ms/op
                 createUser·p0.90:   3.494 ms/op
                 createUser·p0.95:   3.695 ms/op
                 createUser·p0.99:   4.174 ms/op
                 createUser·p0.999:  6.998 ms/op
                 createUser·p0.9999: 17.579 ms/op
                 createUser·p1.00:   18.973 ms/op

Iteration   3: 3.041 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.416 ms/op
                 createUser·p0.50:   2.994 ms/op
                 createUser·p0.90:   3.502 ms/op
                 createUser·p0.95:   3.711 ms/op
                 createUser·p0.99:   4.415 ms/op
                 createUser·p0.999:  13.836 ms/op
                 createUser·p0.9999: 23.003 ms/op
                 createUser·p1.00:   23.101 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 314733
  mean =      3.051 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20758 
    [ 2.500,  5.000) = 292454 
    [ 5.000,  7.500) = 1130 
    [ 7.500, 10.000) = 131 
    [10.000, 12.500) = 4 
    [12.500, 15.000) = 46 
    [15.000, 17.500) = 109 
    [17.500, 20.000) = 36 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 33 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.416 ms/op
     p(50.0000) =      3.015 ms/op
     p(90.0000) =      3.559 ms/op
     p(95.0000) =      3.797 ms/op
     p(99.0000) =      4.407 ms/op
     p(99.9000) =      9.167 ms/op
     p(99.9900) =     22.544 ms/op
     p(99.9990) =     23.036 ms/op
     p(99.9999) =     23.101 ms/op
    p(100.0000) =     23.101 ms/op


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
# Warmup Iteration   1: 4.046 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.022 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.916 ±(99.9%) 0.005 ms/op
Iteration   1: 2.945 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.819 ms/op
                 existUser·p0.50:   2.929 ms/op
                 existUser·p0.90:   3.478 ms/op
                 existUser·p0.95:   3.674 ms/op
                 existUser·p0.99:   4.084 ms/op
                 existUser·p0.999:  6.989 ms/op
                 existUser·p0.9999: 12.847 ms/op
                 existUser·p1.00:   13.042 ms/op

Iteration   2: 2.864 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.599 ms/op
                 existUser·p0.50:   2.875 ms/op
                 existUser·p0.90:   3.289 ms/op
                 existUser·p0.95:   3.461 ms/op
                 existUser·p0.99:   4.252 ms/op
                 existUser·p0.999:  7.586 ms/op
                 existUser·p0.9999: 15.677 ms/op
                 existUser·p1.00:   16.466 ms/op

Iteration   3: 2.956 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.760 ms/op
                 existUser·p0.50:   2.916 ms/op
                 existUser·p0.90:   3.432 ms/op
                 existUser·p0.95:   3.596 ms/op
                 existUser·p0.99:   4.047 ms/op
                 existUser·p0.999:  7.196 ms/op
                 existUser·p0.9999: 19.235 ms/op
                 existUser·p1.00:   19.530 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 328585
  mean =      2.921 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1726 
    [ 1.250,  2.500) = 35750 
    [ 2.500,  3.750) = 281754 
    [ 3.750,  5.000) = 8110 
    [ 5.000,  6.250) = 598 
    [ 6.250,  7.500) = 376 
    [ 7.500,  8.750) = 26 
    [ 8.750, 10.000) = 48 
    [10.000, 11.250) = 37 
    [11.250, 12.500) = 25 
    [12.500, 13.750) = 39 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 35 
    [16.250, 17.500) = 28 
    [17.500, 18.750) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.599 ms/op
     p(50.0000) =      2.904 ms/op
     p(90.0000) =      3.404 ms/op
     p(95.0000) =      3.588 ms/op
     p(99.0000) =      4.121 ms/op
     p(99.9000) =      7.204 ms/op
     p(99.9900) =     17.568 ms/op
     p(99.9990) =     19.455 ms/op
     p(99.9999) =     19.530 ms/op
    p(100.0000) =     19.530 ms/op


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
# Warmup Iteration   1: 4.236 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.161 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.095 ±(99.9%) 0.006 ms/op
Iteration   1: 3.035 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.777 ms/op
                 getUser·p0.50:   3.023 ms/op
                 getUser·p0.90:   3.555 ms/op
                 getUser·p0.95:   3.846 ms/op
                 getUser·p0.99:   4.653 ms/op
                 getUser·p0.999:  7.609 ms/op
                 getUser·p0.9999: 19.658 ms/op
                 getUser·p1.00:   19.956 ms/op

Iteration   2: 3.033 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.883 ms/op
                 getUser·p0.50:   3.011 ms/op
                 getUser·p0.90:   3.523 ms/op
                 getUser·p0.95:   3.768 ms/op
                 getUser·p0.99:   4.268 ms/op
                 getUser·p0.999:  6.173 ms/op
                 getUser·p0.9999: 21.707 ms/op
                 getUser·p1.00:   21.955 ms/op

Iteration   3: 3.129 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.753 ms/op
                 getUser·p0.50:   3.080 ms/op
                 getUser·p0.90:   3.736 ms/op
                 getUser·p0.95:   3.895 ms/op
                 getUser·p0.99:   4.489 ms/op
                 getUser·p0.999:  7.621 ms/op
                 getUser·p0.9999: 17.490 ms/op
                 getUser·p1.00:   18.022 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 313167
  mean =      3.065 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19594 
    [ 2.500,  5.000) = 291845 
    [ 5.000,  7.500) = 1465 
    [ 7.500, 10.000) = 103 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 57 
    [17.500, 20.000) = 39 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.753 ms/op
     p(50.0000) =      3.035 ms/op
     p(90.0000) =      3.625 ms/op
     p(95.0000) =      3.846 ms/op
     p(99.0000) =      4.467 ms/op
     p(99.9000) =      7.373 ms/op
     p(99.9900) =     20.961 ms/op
     p(99.9990) =     21.823 ms/op
     p(99.9999) =     21.955 ms/op
    p(100.0000) =     21.955 ms/op


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
# Warmup Iteration   1: 5.447 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 4.128 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.947 ±(99.9%) 0.010 ms/op
Iteration   1: 3.955 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.290 ms/op
                 listUser·p0.50:   3.822 ms/op
                 listUser·p0.90:   4.735 ms/op
                 listUser·p0.95:   5.743 ms/op
                 listUser·p0.99:   6.963 ms/op
                 listUser·p0.999:  14.257 ms/op
                 listUser·p0.9999: 16.660 ms/op
                 listUser·p1.00:   16.876 ms/op

Iteration   2: 3.997 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.973 ms/op
                 listUser·p0.50:   3.846 ms/op
                 listUser·p0.90:   4.907 ms/op
                 listUser·p0.95:   5.702 ms/op
                 listUser·p0.99:   6.898 ms/op
                 listUser·p0.999:  16.383 ms/op
                 listUser·p0.9999: 22.904 ms/op
                 listUser·p1.00:   24.576 ms/op

Iteration   3: 3.934 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.867 ms/op
                 listUser·p0.50:   3.793 ms/op
                 listUser·p0.90:   4.882 ms/op
                 listUser·p0.95:   5.366 ms/op
                 listUser·p0.99:   6.881 ms/op
                 listUser·p0.999:  16.267 ms/op
                 listUser·p0.9999: 20.992 ms/op
                 listUser·p1.00:   21.430 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 242238
  mean =      3.962 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2203 
    [ 2.500,  5.000) = 219205 
    [ 5.000,  7.500) = 19582 
    [ 7.500, 10.000) = 746 
    [10.000, 12.500) = 62 
    [12.500, 15.000) = 182 
    [15.000, 17.500) = 151 
    [17.500, 20.000) = 49 
    [20.000, 22.500) = 38 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.867 ms/op
     p(50.0000) =      3.817 ms/op
     p(90.0000) =      4.850 ms/op
     p(95.0000) =      5.587 ms/op
     p(99.0000) =      6.914 ms/op
     p(99.9000) =     15.204 ms/op
     p(99.9900) =     22.351 ms/op
     p(99.9990) =     23.612 ms/op
     p(99.9999) =     24.576 ms/op
    p(100.0000) =     24.576 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.602 ± 3.292  ops/ms
ClientGrpc.existUser                       thrpt       3  11.205 ± 2.116  ops/ms
ClientGrpc.getUser                         thrpt       3  10.587 ± 0.710  ops/ms
ClientGrpc.listUser                        thrpt       3   7.985 ± 0.764  ops/ms
ClientGrpc.createUser                       avgt       3   3.028 ± 0.141   ms/op
ClientGrpc.existUser                        avgt       3   2.882 ± 1.039   ms/op
ClientGrpc.getUser                          avgt       3   3.013 ± 0.336   ms/op
ClientGrpc.listUser                         avgt       3   3.937 ± 0.590   ms/op
ClientGrpc.createUser                     sample  314733   3.051 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.416           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.015           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.559           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.797           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.407           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.167           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          22.544           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.101           ms/op
ClientGrpc.existUser                      sample  328585   2.921 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.599           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.904           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.404           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.588           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.121           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.204           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.568           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.530           ms/op
ClientGrpc.getUser                        sample  313167   3.065 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.753           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.035           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.625           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.846           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.467           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.373           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.961           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.955           ms/op
ClientGrpc.listUser                       sample  242238   3.962 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.867           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.817           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.850           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.587           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.914           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.204           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.351           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.576           ms/op
