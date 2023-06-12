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
# Warmup Iteration   1: 4.371 ops/ms
# Warmup Iteration   2: 9.017 ops/ms
# Warmup Iteration   3: 9.979 ops/ms
Iteration   1: 10.787 ops/ms
Iteration   2: 10.315 ops/ms
Iteration   3: 10.613 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.572 ±(99.9%) 4.353 ops/ms [Average]
  (min, avg, max) = (10.315, 10.572, 10.787), stdev = 0.239
  CI (99.9%): [6.219, 14.924] (assumes normal distribution)


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
# Warmup Iteration   1: 7.275 ops/ms
# Warmup Iteration   2: 10.732 ops/ms
# Warmup Iteration   3: 11.191 ops/ms
Iteration   1: 11.342 ops/ms
Iteration   2: 11.049 ops/ms
Iteration   3: 10.927 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.106 ±(99.9%) 3.888 ops/ms [Average]
  (min, avg, max) = (10.927, 11.106, 11.342), stdev = 0.213
  CI (99.9%): [7.218, 14.993] (assumes normal distribution)


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
# Warmup Iteration   1: 6.836 ops/ms
# Warmup Iteration   2: 10.159 ops/ms
# Warmup Iteration   3: 10.342 ops/ms
Iteration   1: 10.625 ops/ms
Iteration   2: 10.599 ops/ms
Iteration   3: 10.546 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.590 ±(99.9%) 0.731 ops/ms [Average]
  (min, avg, max) = (10.546, 10.590, 10.625), stdev = 0.040
  CI (99.9%): [9.859, 11.321] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.635 ops/ms
# Warmup Iteration   2: 7.956 ops/ms
# Warmup Iteration   3: 7.986 ops/ms
Iteration   1: 8.067 ops/ms
Iteration   2: 8.258 ops/ms
Iteration   3: 8.117 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.147 ±(99.9%) 1.808 ops/ms [Average]
  (min, avg, max) = (8.067, 8.147, 8.258), stdev = 0.099
  CI (99.9%): [6.339, 9.956] (assumes normal distribution)


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
# Warmup Iteration   1: 4.074 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.149 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.019 ±(99.9%) 0.003 ms/op
Iteration   1: 3.041 ±(99.9%) 0.002 ms/op
Iteration   2: 3.018 ±(99.9%) 0.003 ms/op
Iteration   3: 3.046 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.035 ±(99.9%) 0.270 ms/op [Average]
  (min, avg, max) = (3.018, 3.035, 3.046), stdev = 0.015
  CI (99.9%): [2.765, 3.305] (assumes normal distribution)


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
# Warmup Iteration   1: 4.225 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.978 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.860 ±(99.9%) 0.002 ms/op
Iteration   1: 2.953 ±(99.9%) 0.002 ms/op
Iteration   2: 2.896 ±(99.9%) 0.003 ms/op
Iteration   3: 2.872 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.907 ±(99.9%) 0.753 ms/op [Average]
  (min, avg, max) = (2.872, 2.907, 2.953), stdev = 0.041
  CI (99.9%): [2.154, 3.660] (assumes normal distribution)


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
# Warmup Iteration   1: 4.348 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.142 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.024 ±(99.9%) 0.003 ms/op
Iteration   1: 3.036 ±(99.9%) 0.003 ms/op
Iteration   2: 3.032 ±(99.9%) 0.002 ms/op
Iteration   3: 3.036 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.035 ±(99.9%) 0.046 ms/op [Average]
  (min, avg, max) = (3.032, 3.035, 3.036), stdev = 0.003
  CI (99.9%): [2.988, 3.081] (assumes normal distribution)


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
# Warmup Iteration   1: 5.224 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.109 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 3.917 ±(99.9%) 0.008 ms/op
Iteration   1: 3.784 ±(99.9%) 0.014 ms/op
Iteration   2: 3.884 ±(99.9%) 0.012 ms/op
Iteration   3: 3.855 ±(99.9%) 0.023 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.841 ±(99.9%) 0.937 ms/op [Average]
  (min, avg, max) = (3.784, 3.841, 3.884), stdev = 0.051
  CI (99.9%): [2.904, 4.778] (assumes normal distribution)


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
# Warmup Iteration   1: 4.590 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.155 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.045 ±(99.9%) 0.006 ms/op
Iteration   1: 3.065 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.925 ms/op
                 createUser·p0.50:   3.027 ms/op
                 createUser·p0.90:   3.592 ms/op
                 createUser·p0.95:   3.817 ms/op
                 createUser·p0.99:   4.424 ms/op
                 createUser·p0.999:  7.963 ms/op
                 createUser·p0.9999: 14.658 ms/op
                 createUser·p1.00:   15.090 ms/op

Iteration   2: 3.031 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.842 ms/op
                 createUser·p0.50:   2.990 ms/op
                 createUser·p0.90:   3.547 ms/op
                 createUser·p0.95:   3.842 ms/op
                 createUser·p0.99:   4.620 ms/op
                 createUser·p0.999:  10.306 ms/op
                 createUser·p0.9999: 14.744 ms/op
                 createUser·p1.00:   14.909 ms/op

Iteration   3: 3.062 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.774 ms/op
                 createUser·p0.50:   3.027 ms/op
                 createUser·p0.90:   3.600 ms/op
                 createUser·p0.95:   3.801 ms/op
                 createUser·p0.99:   4.473 ms/op
                 createUser·p0.999:  10.662 ms/op
                 createUser·p0.9999: 19.221 ms/op
                 createUser·p1.00:   25.231 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 314816
  mean =      3.052 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23902 
    [ 2.500,  5.000) = 289241 
    [ 5.000,  7.500) = 1185 
    [ 7.500, 10.000) = 187 
    [10.000, 12.500) = 77 
    [12.500, 15.000) = 126 
    [15.000, 17.500) = 73 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.774 ms/op
     p(50.0000) =      3.015 ms/op
     p(90.0000) =      3.584 ms/op
     p(95.0000) =      3.817 ms/op
     p(99.0000) =      4.514 ms/op
     p(99.9000) =      9.546 ms/op
     p(99.9900) =     17.368 ms/op
     p(99.9990) =     25.161 ms/op
     p(99.9999) =     25.231 ms/op
    p(100.0000) =     25.231 ms/op


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
# Warmup Iteration   1: 4.216 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.091 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.961 ±(99.9%) 0.006 ms/op
Iteration   1: 2.864 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.797 ms/op
                 existUser·p0.50:   2.843 ms/op
                 existUser·p0.90:   3.199 ms/op
                 existUser·p0.95:   3.342 ms/op
                 existUser·p0.99:   3.801 ms/op
                 existUser·p0.999:  6.467 ms/op
                 existUser·p0.9999: 17.760 ms/op
                 existUser·p1.00:   17.793 ms/op

Iteration   2: 2.930 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.537 ms/op
                 existUser·p0.50:   2.896 ms/op
                 existUser·p0.90:   3.416 ms/op
                 existUser·p0.95:   3.584 ms/op
                 existUser·p0.99:   4.055 ms/op
                 existUser·p0.999:  6.368 ms/op
                 existUser·p0.9999: 17.828 ms/op
                 existUser·p1.00:   18.383 ms/op

Iteration   3: 2.888 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.469 ms/op
                 existUser·p0.50:   2.871 ms/op
                 existUser·p0.90:   3.318 ms/op
                 existUser·p0.95:   3.457 ms/op
                 existUser·p0.99:   4.076 ms/op
                 existUser·p0.999:  6.693 ms/op
                 existUser·p0.9999: 31.648 ms/op
                 existUser·p1.00:   31.982 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 331910
  mean =      2.894 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 37669 
    [ 2.500,  5.000) = 293588 
    [ 5.000,  7.500) = 471 
    [ 7.500, 10.000) = 13 
    [10.000, 12.500) = 9 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 55 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.469 ms/op
     p(50.0000) =      2.867 ms/op
     p(90.0000) =      3.314 ms/op
     p(95.0000) =      3.473 ms/op
     p(99.0000) =      3.990 ms/op
     p(99.9000) =      6.521 ms/op
     p(99.9900) =     23.855 ms/op
     p(99.9990) =     31.906 ms/op
     p(99.9999) =     31.982 ms/op
    p(100.0000) =     31.982 ms/op


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
# Warmup Iteration   1: 4.307 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.128 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.073 ±(99.9%) 0.008 ms/op
Iteration   1: 3.075 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.902 ms/op
                 getUser·p0.50:   3.031 ms/op
                 getUser·p0.90:   3.625 ms/op
                 getUser·p0.95:   3.801 ms/op
                 getUser·p0.99:   4.424 ms/op
                 getUser·p0.999:  7.603 ms/op
                 getUser·p0.9999: 23.816 ms/op
                 getUser·p1.00:   24.314 ms/op

Iteration   2: 3.020 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.564 ms/op
                 getUser·p0.50:   2.982 ms/op
                 getUser·p0.90:   3.572 ms/op
                 getUser·p0.95:   3.785 ms/op
                 getUser·p0.99:   4.555 ms/op
                 getUser·p0.999:  7.194 ms/op
                 getUser·p0.9999: 33.391 ms/op
                 getUser·p1.00:   33.554 ms/op

Iteration   3: 3.047 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.802 ms/op
                 getUser·p0.50:   2.994 ms/op
                 getUser·p0.90:   3.556 ms/op
                 getUser·p0.95:   3.789 ms/op
                 getUser·p0.99:   4.547 ms/op
                 getUser·p0.999:  9.390 ms/op
                 getUser·p0.9999: 28.131 ms/op
                 getUser·p1.00:   28.508 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 314846
  mean =      3.047 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24141 
    [ 2.500,  5.000) = 289076 
    [ 5.000,  7.500) = 1268 
    [ 7.500, 10.000) = 105 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 37 
    [22.500, 25.000) = 49 
    [25.000, 27.500) = 55 
    [27.500, 30.000) = 20 
    [30.000, 32.500) = 14 
    [32.500, 35.000) = 18 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.564 ms/op
     p(50.0000) =      3.002 ms/op
     p(90.0000) =      3.588 ms/op
     p(95.0000) =      3.793 ms/op
     p(99.0000) =      4.506 ms/op
     p(99.9000) =      7.848 ms/op
     p(99.9900) =     31.671 ms/op
     p(99.9990) =     33.479 ms/op
     p(99.9999) =     33.554 ms/op
    p(100.0000) =     33.554 ms/op


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
# Warmup Iteration   1: 4.958 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.367 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.044 ±(99.9%) 0.012 ms/op
Iteration   1: 3.992 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.348 ms/op
                 listUser·p0.50:   3.813 ms/op
                 listUser·p0.90:   4.997 ms/op
                 listUser·p0.95:   5.743 ms/op
                 listUser·p0.99:   7.135 ms/op
                 listUser·p0.999:  15.021 ms/op
                 listUser·p0.9999: 18.907 ms/op
                 listUser·p1.00:   19.137 ms/op

Iteration   2: 3.964 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.022 ms/op
                 listUser·p0.50:   3.826 ms/op
                 listUser·p0.90:   4.604 ms/op
                 listUser·p0.95:   5.399 ms/op
                 listUser·p0.99:   7.037 ms/op
                 listUser·p0.999:  18.121 ms/op
                 listUser·p0.9999: 26.502 ms/op
                 listUser·p1.00:   26.968 ms/op

Iteration   3: 3.827 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.155 ms/op
                 listUser·p0.50:   3.703 ms/op
                 listUser·p0.90:   4.645 ms/op
                 listUser·p0.95:   5.505 ms/op
                 listUser·p0.99:   6.840 ms/op
                 listUser·p0.999:  15.383 ms/op
                 listUser·p0.9999: 19.813 ms/op
                 listUser·p1.00:   20.120 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 244399
  mean =      3.926 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1961 
    [ 2.500,  5.000) = 222561 
    [ 5.000,  7.500) = 18388 
    [ 7.500, 10.000) = 1025 
    [10.000, 12.500) = 61 
    [12.500, 15.000) = 100 
    [15.000, 17.500) = 153 
    [17.500, 20.000) = 111 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 21 

  Percentiles, ms/op:
      p(0.0000) =      1.022 ms/op
     p(50.0000) =      3.785 ms/op
     p(90.0000) =      4.784 ms/op
     p(95.0000) =      5.554 ms/op
     p(99.0000) =      7.012 ms/op
     p(99.9000) =     16.361 ms/op
     p(99.9900) =     24.824 ms/op
     p(99.9990) =     26.873 ms/op
     p(99.9999) =     26.968 ms/op
    p(100.0000) =     26.968 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.572 ± 4.353  ops/ms
ClientGrpc.existUser                       thrpt       3  11.106 ± 3.888  ops/ms
ClientGrpc.getUser                         thrpt       3  10.590 ± 0.731  ops/ms
ClientGrpc.listUser                        thrpt       3   8.147 ± 1.808  ops/ms
ClientGrpc.createUser                       avgt       3   3.035 ± 0.270   ms/op
ClientGrpc.existUser                        avgt       3   2.907 ± 0.753   ms/op
ClientGrpc.getUser                          avgt       3   3.035 ± 0.046   ms/op
ClientGrpc.listUser                         avgt       3   3.841 ± 0.937   ms/op
ClientGrpc.createUser                     sample  314816   3.052 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.774           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.015           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.584           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.817           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.514           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.546           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.368           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          25.231           ms/op
ClientGrpc.existUser                      sample  331910   2.894 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.469           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.867           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.314           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.473           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           3.990           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.521           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          23.855           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          31.982           ms/op
ClientGrpc.getUser                        sample  314846   3.047 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.564           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.002           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.588           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.793           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.506           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.848           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          31.671           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          33.554           ms/op
ClientGrpc.listUser                       sample  244399   3.926 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.022           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.785           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.784           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.554           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.012           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.361           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.824           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.968           ms/op
