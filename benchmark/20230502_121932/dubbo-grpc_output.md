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
# Warmup Iteration   1: 1.995 ops/ms
# Warmup Iteration   2: 4.926 ops/ms
# Warmup Iteration   3: 6.806 ops/ms
Iteration   1: 6.741 ops/ms
Iteration   2: 6.878 ops/ms
Iteration   3: 7.132 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  6.917 ±(99.9%) 3.625 ops/ms [Average]
  (min, avg, max) = (6.741, 6.917, 7.132), stdev = 0.199
  CI (99.9%): [3.292, 10.542] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 4.547 ops/ms
# Warmup Iteration   2: 7.105 ops/ms
# Warmup Iteration   3: 7.633 ops/ms
Iteration   1: 7.845 ops/ms
Iteration   2: 7.951 ops/ms
Iteration   3: 7.925 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.907 ±(99.9%) 1.014 ops/ms [Average]
  (min, avg, max) = (7.845, 7.907, 7.951), stdev = 0.056
  CI (99.9%): [6.893, 8.921] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 4.003 ops/ms
# Warmup Iteration   2: 6.543 ops/ms
# Warmup Iteration   3: 6.833 ops/ms
Iteration   1: 6.991 ops/ms
Iteration   2: 7.070 ops/ms
Iteration   3: 6.864 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  6.975 ±(99.9%) 1.896 ops/ms [Average]
  (min, avg, max) = (6.864, 6.975, 7.070), stdev = 0.104
  CI (99.9%): [5.079, 8.871] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 3.730 ops/ms
# Warmup Iteration   2: 5.077 ops/ms
# Warmup Iteration   3: 5.521 ops/ms
Iteration   1: 5.680 ops/ms
Iteration   2: 5.588 ops/ms
Iteration   3: 5.673 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.647 ±(99.9%) 0.933 ops/ms [Average]
  (min, avg, max) = (5.588, 5.647, 5.680), stdev = 0.051
  CI (99.9%): [4.714, 6.580] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 7.158 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 5.051 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.553 ±(99.9%) 0.008 ms/op
Iteration   1: 4.502 ±(99.9%) 0.003 ms/op
Iteration   2: 4.491 ±(99.9%) 0.003 ms/op
Iteration   3: 4.328 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.441 ±(99.9%) 1.775 ms/op [Average]
  (min, avg, max) = (4.328, 4.441, 4.502), stdev = 0.097
  CI (99.9%): [2.666, 6.216] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.086 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.616 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.157 ±(99.9%) 0.004 ms/op
Iteration   1: 4.309 ±(99.9%) 0.003 ms/op
Iteration   2: 4.342 ±(99.9%) 0.002 ms/op
Iteration   3: 4.276 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.309 ±(99.9%) 0.601 ms/op [Average]
  (min, avg, max) = (4.276, 4.309, 4.342), stdev = 0.033
  CI (99.9%): [3.707, 4.910] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 7.175 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.820 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.470 ±(99.9%) 0.006 ms/op
Iteration   1: 4.365 ±(99.9%) 0.004 ms/op
Iteration   2: 4.475 ±(99.9%) 0.003 ms/op
Iteration   3: 4.464 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.434 ±(99.9%) 1.108 ms/op [Average]
  (min, avg, max) = (4.365, 4.434, 4.475), stdev = 0.061
  CI (99.9%): [3.327, 5.542] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 7.793 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 6.138 ±(99.9%) 0.032 ms/op
# Warmup Iteration   3: 5.651 ±(99.9%) 0.022 ms/op
Iteration   1: 5.518 ±(99.9%) 0.014 ms/op
Iteration   2: 5.766 ±(99.9%) 0.013 ms/op
Iteration   3: 5.623 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.636 ±(99.9%) 2.269 ms/op [Average]
  (min, avg, max) = (5.518, 5.636, 5.766), stdev = 0.124
  CI (99.9%): [3.367, 7.904] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 7.351 ±(99.9%) 0.091 ms/op
# Warmup Iteration   2: 5.007 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.571 ±(99.9%) 0.014 ms/op
Iteration   1: 4.470 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   0.703 ms/op
                 createUser·p0.50:   4.342 ms/op
                 createUser·p0.90:   5.734 ms/op
                 createUser·p0.95:   6.259 ms/op
                 createUser·p0.99:   7.946 ms/op
                 createUser·p0.999:  14.286 ms/op
                 createUser·p0.9999: 33.320 ms/op
                 createUser·p1.00:   33.620 ms/op

Iteration   2: 4.461 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.325 ms/op
                 createUser·p0.50:   4.325 ms/op
                 createUser·p0.90:   5.407 ms/op
                 createUser·p0.95:   5.865 ms/op
                 createUser·p0.99:   7.856 ms/op
                 createUser·p0.999:  14.057 ms/op
                 createUser·p0.9999: 26.465 ms/op
                 createUser·p1.00:   27.623 ms/op

Iteration   3: 4.477 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.174 ms/op
                 createUser·p0.50:   4.375 ms/op
                 createUser·p0.90:   5.554 ms/op
                 createUser·p0.95:   5.947 ms/op
                 createUser·p0.99:   7.414 ms/op
                 createUser·p0.999:  11.625 ms/op
                 createUser·p0.9999: 24.496 ms/op
                 createUser·p1.00:   25.625 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 214716
  mean =      4.469 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4072 
    [ 2.500,  5.000) = 162977 
    [ 5.000,  7.500) = 45061 
    [ 7.500, 10.000) = 1909 
    [10.000, 12.500) = 431 
    [12.500, 15.000) = 105 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 76 
    [25.000, 27.500) = 15 
    [27.500, 30.000) = 5 
    [30.000, 32.500) = 12 
    [32.500, 35.000) = 20 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.703 ms/op
     p(50.0000) =      4.342 ms/op
     p(90.0000) =      5.562 ms/op
     p(95.0000) =      6.038 ms/op
     p(99.0000) =      7.774 ms/op
     p(99.9000) =     13.374 ms/op
     p(99.9900) =     32.110 ms/op
     p(99.9990) =     33.550 ms/op
     p(99.9999) =     33.620 ms/op
    p(100.0000) =     33.620 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.358 ±(99.9%) 0.078 ms/op
# Warmup Iteration   2: 4.546 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.230 ±(99.9%) 0.012 ms/op
Iteration   1: 4.348 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.038 ms/op
                 existUser·p0.50:   4.178 ms/op
                 existUser·p0.90:   5.530 ms/op
                 existUser·p0.95:   6.046 ms/op
                 existUser·p0.99:   7.791 ms/op
                 existUser·p0.999:  12.631 ms/op
                 existUser·p0.9999: 21.722 ms/op
                 existUser·p1.00:   22.086 ms/op

Iteration   2: 4.109 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.866 ms/op
                 existUser·p0.50:   3.969 ms/op
                 existUser·p0.90:   5.169 ms/op
                 existUser·p0.95:   5.751 ms/op
                 existUser·p0.99:   8.036 ms/op
                 existUser·p0.999:  14.134 ms/op
                 existUser·p0.9999: 18.030 ms/op
                 existUser·p1.00:   18.547 ms/op

Iteration   3: 4.099 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.986 ms/op
                 existUser·p0.50:   4.014 ms/op
                 existUser·p0.90:   5.038 ms/op
                 existUser·p0.95:   5.456 ms/op
                 existUser·p0.99:   7.159 ms/op
                 existUser·p0.999:  12.894 ms/op
                 existUser·p0.9999: 36.582 ms/op
                 existUser·p1.00:   41.288 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 229502
  mean =      4.182 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 196998 
    [ 5.000, 10.000) = 31947 
    [10.000, 15.000) = 441 
    [15.000, 20.000) = 52 
    [20.000, 25.000) = 32 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 31 
    [40.000, 45.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.866 ms/op
     p(50.0000) =      4.043 ms/op
     p(90.0000) =      5.259 ms/op
     p(95.0000) =      5.775 ms/op
     p(99.0000) =      7.586 ms/op
     p(99.9000) =     13.386 ms/op
     p(99.9900) =     35.983 ms/op
     p(99.9990) =     38.701 ms/op
     p(99.9999) =     41.288 ms/op
    p(100.0000) =     41.288 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 7.125 ±(99.9%) 0.091 ms/op
# Warmup Iteration   2: 4.763 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.460 ±(99.9%) 0.015 ms/op
Iteration   1: 4.505 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.000 ms/op
                 getUser·p0.50:   4.383 ms/op
                 getUser·p0.90:   5.668 ms/op
                 getUser·p0.95:   6.160 ms/op
                 getUser·p0.99:   8.242 ms/op
                 getUser·p0.999:  11.207 ms/op
                 getUser·p0.9999: 17.003 ms/op
                 getUser·p1.00:   17.302 ms/op

Iteration   2: 4.383 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.102 ms/op
                 getUser·p0.50:   4.293 ms/op
                 getUser·p0.90:   5.374 ms/op
                 getUser·p0.95:   5.784 ms/op
                 getUser·p0.99:   6.950 ms/op
                 getUser·p0.999:  11.863 ms/op
                 getUser·p0.9999: 19.553 ms/op
                 getUser·p1.00:   20.808 ms/op

Iteration   3: 4.417 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.871 ms/op
                 getUser·p0.50:   4.293 ms/op
                 getUser·p0.90:   5.497 ms/op
                 getUser·p0.95:   5.931 ms/op
                 getUser·p0.99:   7.274 ms/op
                 getUser·p0.999:  11.348 ms/op
                 getUser·p0.9999: 24.707 ms/op
                 getUser·p1.00:   25.199 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 216339
  mean =      4.434 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4288 
    [ 2.500,  5.000) = 167696 
    [ 5.000,  7.500) = 42140 
    [ 7.500, 10.000) = 1751 
    [10.000, 12.500) = 320 
    [12.500, 15.000) = 33 
    [15.000, 17.500) = 44 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.871 ms/op
     p(50.0000) =      4.317 ms/op
     p(90.0000) =      5.513 ms/op
     p(95.0000) =      5.964 ms/op
     p(99.0000) =      7.537 ms/op
     p(99.9000) =     11.420 ms/op
     p(99.9900) =     23.018 ms/op
     p(99.9990) =     25.166 ms/op
     p(99.9999) =     25.199 ms/op
    p(100.0000) =     25.199 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 7.971 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 6.391 ±(99.9%) 0.031 ms/op
# Warmup Iteration   3: 5.653 ±(99.9%) 0.021 ms/op
Iteration   1: 5.693 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.343 ms/op
                 listUser·p0.50:   5.382 ms/op
                 listUser·p0.90:   7.602 ms/op
                 listUser·p0.95:   8.552 ms/op
                 listUser·p0.99:   10.973 ms/op
                 listUser·p0.999:  19.096 ms/op
                 listUser·p0.9999: 27.665 ms/op
                 listUser·p1.00:   28.574 ms/op

Iteration   2: 5.652 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.829 ms/op
                 listUser·p0.50:   5.325 ms/op
                 listUser·p0.90:   7.700 ms/op
                 listUser·p0.95:   8.749 ms/op
                 listUser·p0.99:   11.013 ms/op
                 listUser·p0.999:  18.429 ms/op
                 listUser·p0.9999: 21.201 ms/op
                 listUser·p1.00:   22.905 ms/op

Iteration   3: 5.720 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   2.015 ms/op
                 listUser·p0.50:   5.366 ms/op
                 listUser·p0.90:   7.782 ms/op
                 listUser·p0.95:   8.749 ms/op
                 listUser·p0.99:   10.994 ms/op
                 listUser·p0.999:  21.446 ms/op
                 listUser·p0.9999: 25.119 ms/op
                 listUser·p1.00:   26.149 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 168865
  mean =      5.688 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 102 
    [ 2.500,  5.000) = 58755 
    [ 5.000,  7.500) = 90986 
    [ 7.500, 10.000) = 15796 
    [10.000, 12.500) = 2459 
    [12.500, 15.000) = 321 
    [15.000, 17.500) = 169 
    [17.500, 20.000) = 138 
    [20.000, 22.500) = 75 
    [22.500, 25.000) = 50 
    [25.000, 27.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      1.343 ms/op
     p(50.0000) =      5.358 ms/op
     p(90.0000) =      7.700 ms/op
     p(95.0000) =      8.684 ms/op
     p(99.0000) =     10.994 ms/op
     p(99.9000) =     19.595 ms/op
     p(99.9900) =     23.968 ms/op
     p(99.9990) =     28.348 ms/op
     p(99.9999) =     28.574 ms/op
    p(100.0000) =     28.574 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   6.917 ± 3.625  ops/ms
ClientGrpc.existUser                       thrpt       3   7.907 ± 1.014  ops/ms
ClientGrpc.getUser                         thrpt       3   6.975 ± 1.896  ops/ms
ClientGrpc.listUser                        thrpt       3   5.647 ± 0.933  ops/ms
ClientGrpc.createUser                       avgt       3   4.441 ± 1.775   ms/op
ClientGrpc.existUser                        avgt       3   4.309 ± 0.601   ms/op
ClientGrpc.getUser                          avgt       3   4.434 ± 1.108   ms/op
ClientGrpc.listUser                         avgt       3   5.636 ± 2.269   ms/op
ClientGrpc.createUser                     sample  214716   4.469 ± 0.008   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.703           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.342           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.562           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           6.038           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.774           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.374           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          32.110           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          33.620           ms/op
ClientGrpc.existUser                      sample  229502   4.182 ± 0.008   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.866           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.043           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.259           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.775           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.586           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          13.386           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          35.983           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          41.288           ms/op
ClientGrpc.getUser                        sample  216339   4.434 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.871           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.317           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.513           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.964           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.537           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.420           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          23.018           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          25.199           ms/op
ClientGrpc.listUser                       sample  168865   5.688 ± 0.013   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.343           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.358           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.700           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.684           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.994           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          19.595           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.968           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          28.574           ms/op
