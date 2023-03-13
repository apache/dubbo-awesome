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
# Warmup Iteration   1: 3.719 ops/ms
# Warmup Iteration   2: 8.326 ops/ms
# Warmup Iteration   3: 9.807 ops/ms
Iteration   1: 10.098 ops/ms
Iteration   2: 10.206 ops/ms
Iteration   3: 10.212 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.172 ±(99.9%) 1.171 ops/ms [Average]
  (min, avg, max) = (10.098, 10.172, 10.212), stdev = 0.064
  CI (99.9%): [9.001, 11.343] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 6.600 ops/ms
# Warmup Iteration   2: 9.883 ops/ms
# Warmup Iteration   3: 10.523 ops/ms
Iteration   1: 10.909 ops/ms
Iteration   2: 10.548 ops/ms
Iteration   3: 10.995 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.817 ±(99.9%) 4.334 ops/ms [Average]
  (min, avg, max) = (10.548, 10.817, 10.995), stdev = 0.238
  CI (99.9%): [6.483, 15.152] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 6.129 ops/ms
# Warmup Iteration   2: 9.873 ops/ms
# Warmup Iteration   3: 10.032 ops/ms
Iteration   1: 10.481 ops/ms
Iteration   2: 10.315 ops/ms
Iteration   3: 10.310 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.368 ±(99.9%) 1.775 ops/ms [Average]
  (min, avg, max) = (10.310, 10.368, 10.481), stdev = 0.097
  CI (99.9%): [8.593, 12.144] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 5.975 ops/ms
# Warmup Iteration   2: 7.420 ops/ms
# Warmup Iteration   3: 7.888 ops/ms
Iteration   1: 8.076 ops/ms
Iteration   2: 7.878 ops/ms
Iteration   3: 7.924 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.959 ±(99.9%) 1.887 ops/ms [Average]
  (min, avg, max) = (7.878, 7.959, 8.076), stdev = 0.103
  CI (99.9%): [6.072, 9.846] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.565 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.189 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.207 ±(99.9%) 0.002 ms/op
Iteration   1: 3.189 ±(99.9%) 0.002 ms/op
Iteration   2: 3.265 ±(99.9%) 0.002 ms/op
Iteration   3: 3.213 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.222 ±(99.9%) 0.701 ms/op [Average]
  (min, avg, max) = (3.189, 3.222, 3.265), stdev = 0.038
  CI (99.9%): [2.521, 3.924] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.360 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.162 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.030 ±(99.9%) 0.003 ms/op
Iteration   1: 2.951 ±(99.9%) 0.002 ms/op
Iteration   2: 3.011 ±(99.9%) 0.003 ms/op
Iteration   3: 2.949 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.970 ±(99.9%) 0.643 ms/op [Average]
  (min, avg, max) = (2.949, 2.970, 3.011), stdev = 0.035
  CI (99.9%): [2.328, 3.613] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 4.445 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.288 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.218 ±(99.9%) 0.003 ms/op
Iteration   1: 3.138 ±(99.9%) 0.002 ms/op
Iteration   2: 3.094 ±(99.9%) 0.004 ms/op
Iteration   3: 3.131 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.121 ±(99.9%) 0.431 ms/op [Average]
  (min, avg, max) = (3.094, 3.121, 3.138), stdev = 0.024
  CI (99.9%): [2.690, 3.552] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.838 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.278 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.073 ±(99.9%) 0.008 ms/op
Iteration   1: 4.136 ±(99.9%) 0.015 ms/op
Iteration   2: 4.109 ±(99.9%) 0.009 ms/op
Iteration   3: 4.160 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.135 ±(99.9%) 0.466 ms/op [Average]
  (min, avg, max) = (4.109, 4.135, 4.160), stdev = 0.026
  CI (99.9%): [3.669, 4.601] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.748 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.312 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.128 ±(99.9%) 0.006 ms/op
Iteration   1: 3.126 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.840 ms/op
                 createUser·p0.50:   3.109 ms/op
                 createUser·p0.90:   3.785 ms/op
                 createUser·p0.95:   4.067 ms/op
                 createUser·p0.99:   4.866 ms/op
                 createUser·p0.999:  8.674 ms/op
                 createUser·p0.9999: 14.156 ms/op
                 createUser·p1.00:   14.746 ms/op

Iteration   2: 3.148 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.980 ms/op
                 createUser·p0.50:   3.121 ms/op
                 createUser·p0.90:   3.633 ms/op
                 createUser·p0.95:   3.871 ms/op
                 createUser·p0.99:   4.473 ms/op
                 createUser·p0.999:  7.327 ms/op
                 createUser·p0.9999: 23.358 ms/op
                 createUser·p1.00:   23.527 ms/op

Iteration   3: 3.216 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.981 ms/op
                 createUser·p0.50:   3.170 ms/op
                 createUser·p0.90:   3.756 ms/op
                 createUser·p0.95:   3.932 ms/op
                 createUser·p0.99:   4.555 ms/op
                 createUser·p0.999:  15.148 ms/op
                 createUser·p0.9999: 17.663 ms/op
                 createUser·p1.00:   18.776 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 303642
  mean =      3.163 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14010 
    [ 2.500,  5.000) = 287741 
    [ 5.000,  7.500) = 1447 
    [ 7.500, 10.000) = 164 
    [10.000, 12.500) = 63 
    [12.500, 15.000) = 82 
    [15.000, 17.500) = 90 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.840 ms/op
     p(50.0000) =      3.133 ms/op
     p(90.0000) =      3.727 ms/op
     p(95.0000) =      3.957 ms/op
     p(99.0000) =      4.645 ms/op
     p(99.9000) =      8.575 ms/op
     p(99.9900) =     22.795 ms/op
     p(99.9990) =     23.492 ms/op
     p(99.9999) =     23.527 ms/op
    p(100.0000) =     23.527 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.815 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.219 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.036 ±(99.9%) 0.006 ms/op
Iteration   1: 3.004 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.676 ms/op
                 existUser·p0.50:   2.986 ms/op
                 existUser·p0.90:   3.486 ms/op
                 existUser·p0.95:   3.695 ms/op
                 existUser·p0.99:   4.301 ms/op
                 existUser·p0.999:  6.870 ms/op
                 existUser·p0.9999: 14.593 ms/op
                 existUser·p1.00:   14.909 ms/op

Iteration   2: 2.982 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.948 ms/op
                 existUser·p0.50:   2.957 ms/op
                 existUser·p0.90:   3.351 ms/op
                 existUser·p0.95:   3.547 ms/op
                 existUser·p0.99:   4.071 ms/op
                 existUser·p0.999:  7.214 ms/op
                 existUser·p0.9999: 14.197 ms/op
                 existUser·p1.00:   14.565 ms/op

Iteration   3: 3.001 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.692 ms/op
                 existUser·p0.50:   2.986 ms/op
                 existUser·p0.90:   3.432 ms/op
                 existUser·p0.95:   3.650 ms/op
                 existUser·p0.99:   4.407 ms/op
                 existUser·p0.999:  6.816 ms/op
                 existUser·p0.9999: 32.299 ms/op
                 existUser·p1.00:   32.834 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 320361
  mean =      2.996 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19241 
    [ 2.500,  5.000) = 300208 
    [ 5.000,  7.500) = 673 
    [ 7.500, 10.000) = 20 
    [10.000, 12.500) = 66 
    [12.500, 15.000) = 121 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 26 
    [32.500, 35.000) = 6 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.676 ms/op
     p(50.0000) =      2.974 ms/op
     p(90.0000) =      3.424 ms/op
     p(95.0000) =      3.633 ms/op
     p(99.0000) =      4.276 ms/op
     p(99.9000) =      6.955 ms/op
     p(99.9900) =     30.511 ms/op
     p(99.9990) =     32.689 ms/op
     p(99.9999) =     32.834 ms/op
    p(100.0000) =     32.834 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.401 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.302 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.133 ±(99.9%) 0.006 ms/op
Iteration   1: 3.111 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.943 ms/op
                 getUser·p0.50:   3.076 ms/op
                 getUser·p0.90:   3.609 ms/op
                 getUser·p0.95:   3.854 ms/op
                 getUser·p0.99:   4.506 ms/op
                 getUser·p0.999:  11.556 ms/op
                 getUser·p0.9999: 14.189 ms/op
                 getUser·p1.00:   14.516 ms/op

Iteration   2: 3.105 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.784 ms/op
                 getUser·p0.50:   3.084 ms/op
                 getUser·p0.90:   3.564 ms/op
                 getUser·p0.95:   3.768 ms/op
                 getUser·p0.99:   4.375 ms/op
                 getUser·p0.999:  7.372 ms/op
                 getUser·p0.9999: 14.949 ms/op
                 getUser·p1.00:   15.532 ms/op

Iteration   3: 3.105 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.770 ms/op
                 getUser·p0.50:   3.084 ms/op
                 getUser·p0.90:   3.592 ms/op
                 getUser·p0.95:   3.813 ms/op
                 getUser·p0.99:   4.465 ms/op
                 getUser·p0.999:  7.896 ms/op
                 getUser·p0.9999: 17.629 ms/op
                 getUser·p1.00:   17.957 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 308889
  mean =      3.107 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 447 
    [ 1.250,  2.500) = 11950 
    [ 2.500,  3.750) = 277867 
    [ 3.750,  5.000) = 17174 
    [ 5.000,  6.250) = 702 
    [ 6.250,  7.500) = 371 
    [ 7.500,  8.750) = 89 
    [ 8.750, 10.000) = 31 
    [10.000, 11.250) = 9 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 96 
    [13.750, 15.000) = 57 
    [15.000, 16.250) = 26 
    [16.250, 17.500) = 14 
    [17.500, 18.750) = 24 

  Percentiles, ms/op:
      p(0.0000) =      0.770 ms/op
     p(50.0000) =      3.080 ms/op
     p(90.0000) =      3.588 ms/op
     p(95.0000) =      3.813 ms/op
     p(99.0000) =      4.448 ms/op
     p(99.9000) =      8.324 ms/op
     p(99.9900) =     17.214 ms/op
     p(99.9990) =     17.692 ms/op
     p(99.9999) =     17.957 ms/op
    p(100.0000) =     17.957 ms/op


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
# Warmup Iteration   1: 5.299 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 4.344 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.162 ±(99.9%) 0.011 ms/op
Iteration   1: 4.178 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.403 ms/op
                 listUser·p0.50:   3.969 ms/op
                 listUser·p0.90:   5.325 ms/op
                 listUser·p0.95:   6.144 ms/op
                 listUser·p0.99:   7.381 ms/op
                 listUser·p0.999:  13.982 ms/op
                 listUser·p0.9999: 16.640 ms/op
                 listUser·p1.00:   19.005 ms/op

Iteration   2: 4.071 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.114 ms/op
                 listUser·p0.50:   3.891 ms/op
                 listUser·p0.90:   5.005 ms/op
                 listUser·p0.95:   5.751 ms/op
                 listUser·p0.99:   7.307 ms/op
                 listUser·p0.999:  16.843 ms/op
                 listUser·p0.9999: 18.625 ms/op
                 listUser·p1.00:   23.429 ms/op

Iteration   3: 4.026 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.276 ms/op
                 listUser·p0.50:   3.813 ms/op
                 listUser·p0.90:   5.169 ms/op
                 listUser·p0.95:   5.743 ms/op
                 listUser·p0.99:   7.078 ms/op
                 listUser·p0.999:  16.165 ms/op
                 listUser·p0.9999: 18.913 ms/op
                 listUser·p1.00:   19.497 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 234615
  mean =      4.091 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1559 
    [ 2.500,  5.000) = 204944 
    [ 5.000,  7.500) = 26254 
    [ 7.500, 10.000) = 1234 
    [10.000, 12.500) = 192 
    [12.500, 15.000) = 134 
    [15.000, 17.500) = 199 
    [17.500, 20.000) = 95 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.114 ms/op
     p(50.0000) =      3.891 ms/op
     p(90.0000) =      5.177 ms/op
     p(95.0000) =      5.890 ms/op
     p(99.0000) =      7.258 ms/op
     p(99.9000) =     16.056 ms/op
     p(99.9900) =     18.612 ms/op
     p(99.9990) =     23.418 ms/op
     p(99.9999) =     23.429 ms/op
    p(100.0000) =     23.429 ms/op


# Run complete. Total time: 00:13:06

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.172 ± 1.171  ops/ms
ClientGrpc.existUser                       thrpt       3  10.817 ± 4.334  ops/ms
ClientGrpc.getUser                         thrpt       3  10.368 ± 1.775  ops/ms
ClientGrpc.listUser                        thrpt       3   7.959 ± 1.887  ops/ms
ClientGrpc.createUser                       avgt       3   3.222 ± 0.701   ms/op
ClientGrpc.existUser                        avgt       3   2.970 ± 0.643   ms/op
ClientGrpc.getUser                          avgt       3   3.121 ± 0.431   ms/op
ClientGrpc.listUser                         avgt       3   4.135 ± 0.466   ms/op
ClientGrpc.createUser                     sample  303642   3.163 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.840           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.133           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.727           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.957           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.645           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.575           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          22.795           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.527           ms/op
ClientGrpc.existUser                      sample  320361   2.996 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.676           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.974           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.424           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.633           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.276           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.955           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          30.511           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          32.834           ms/op
ClientGrpc.getUser                        sample  308889   3.107 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.770           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.080           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.588           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.813           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.448           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.324           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.214           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          17.957           ms/op
ClientGrpc.listUser                       sample  234615   4.091 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.114           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.891           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.177           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.890           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.258           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.056           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          18.612           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.429           ms/op
