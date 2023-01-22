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
# Warmup Iteration   1: 4.730 ops/ms
# Warmup Iteration   2: 9.639 ops/ms
# Warmup Iteration   3: 10.772 ops/ms
Iteration   1: 10.504 ops/ms
Iteration   2: 9.990 ops/ms
Iteration   3: 10.156 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.217 ±(99.9%) 4.783 ops/ms [Average]
  (min, avg, max) = (9.990, 10.217, 10.504), stdev = 0.262
  CI (99.9%): [5.434, 14.999] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 8.238 ops/ms
# Warmup Iteration   2: 10.349 ops/ms
# Warmup Iteration   3: 10.836 ops/ms
Iteration   1: 10.590 ops/ms
Iteration   2: 10.951 ops/ms
Iteration   3: 10.906 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.815 ±(99.9%) 3.589 ops/ms [Average]
  (min, avg, max) = (10.590, 10.815, 10.951), stdev = 0.197
  CI (99.9%): [7.226, 14.405] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.939 ops/ms
# Warmup Iteration   2: 10.217 ops/ms
# Warmup Iteration   3: 10.684 ops/ms
Iteration   1: 10.195 ops/ms
Iteration   2: 10.110 ops/ms
Iteration   3: 10.094 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.133 ±(99.9%) 0.993 ops/ms [Average]
  (min, avg, max) = (10.094, 10.133, 10.195), stdev = 0.054
  CI (99.9%): [9.140, 11.126] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 5.733 ops/ms
# Warmup Iteration   2: 7.752 ops/ms
# Warmup Iteration   3: 7.810 ops/ms
Iteration   1: 7.993 ops/ms
Iteration   2: 7.923 ops/ms
Iteration   3: 8.149 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.022 ±(99.9%) 2.112 ops/ms [Average]
  (min, avg, max) = (7.923, 8.022, 8.149), stdev = 0.116
  CI (99.9%): [5.910, 10.134] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 3.822 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.114 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.052 ±(99.9%) 0.009 ms/op
Iteration   1: 3.134 ±(99.9%) 0.002 ms/op
Iteration   2: 3.120 ±(99.9%) 0.003 ms/op
Iteration   3: 3.148 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.134 ±(99.9%) 0.257 ms/op [Average]
  (min, avg, max) = (3.120, 3.134, 3.148), stdev = 0.014
  CI (99.9%): [2.878, 3.391] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.823 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.011 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.969 ±(99.9%) 0.002 ms/op
Iteration   1: 2.935 ±(99.9%) 0.003 ms/op
Iteration   2: 2.969 ±(99.9%) 0.002 ms/op
Iteration   3: 2.929 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.944 ±(99.9%) 0.389 ms/op [Average]
  (min, avg, max) = (2.929, 2.944, 2.969), stdev = 0.021
  CI (99.9%): [2.556, 3.333] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.907 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.092 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.090 ±(99.9%) 0.002 ms/op
Iteration   1: 3.098 ±(99.9%) 0.002 ms/op
Iteration   2: 3.131 ±(99.9%) 0.002 ms/op
Iteration   3: 3.090 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.106 ±(99.9%) 0.398 ms/op [Average]
  (min, avg, max) = (3.090, 3.106, 3.131), stdev = 0.022
  CI (99.9%): [2.708, 3.504] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.786 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 4.252 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 4.128 ±(99.9%) 0.017 ms/op
Iteration   1: 3.906 ±(99.9%) 0.021 ms/op
Iteration   2: 4.010 ±(99.9%) 0.011 ms/op
Iteration   3: 4.019 ±(99.9%) 0.025 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.978 ±(99.9%) 1.143 ms/op [Average]
  (min, avg, max) = (3.906, 3.978, 4.019), stdev = 0.063
  CI (99.9%): [2.835, 5.121] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.956 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.190 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.982 ±(99.9%) 0.006 ms/op
Iteration   1: 3.166 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.718 ms/op
                 createUser·p0.50:   3.146 ms/op
                 createUser·p0.90:   3.846 ms/op
                 createUser·p0.95:   4.039 ms/op
                 createUser·p0.99:   4.325 ms/op
                 createUser·p0.999:  7.233 ms/op
                 createUser·p0.9999: 18.343 ms/op
                 createUser·p1.00:   18.711 ms/op

Iteration   2: 3.065 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.331 ms/op
                 createUser·p0.50:   3.039 ms/op
                 createUser·p0.90:   3.711 ms/op
                 createUser·p0.95:   3.940 ms/op
                 createUser·p0.99:   4.334 ms/op
                 createUser·p0.999:  7.169 ms/op
                 createUser·p0.9999: 13.584 ms/op
                 createUser·p1.00:   13.976 ms/op

Iteration   3: 3.066 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.830 ms/op
                 createUser·p0.50:   3.047 ms/op
                 createUser·p0.90:   3.633 ms/op
                 createUser·p0.95:   3.838 ms/op
                 createUser·p0.99:   4.334 ms/op
                 createUser·p0.999:  7.419 ms/op
                 createUser·p0.9999: 15.811 ms/op
                 createUser·p1.00:   16.204 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 309786
  mean =      3.098 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 948 
    [ 1.250,  2.500) = 25741 
    [ 2.500,  3.750) = 252588 
    [ 3.750,  5.000) = 29492 
    [ 5.000,  6.250) = 519 
    [ 6.250,  7.500) = 220 
    [ 7.500,  8.750) = 78 
    [ 8.750, 10.000) = 13 
    [10.000, 11.250) = 27 
    [11.250, 12.500) = 5 
    [12.500, 13.750) = 34 
    [13.750, 15.000) = 51 
    [15.000, 16.250) = 17 
    [16.250, 17.500) = 20 
    [17.500, 18.750) = 33 

  Percentiles, ms/op:
      p(0.0000) =      0.331 ms/op
     p(50.0000) =      3.072 ms/op
     p(90.0000) =      3.744 ms/op
     p(95.0000) =      3.953 ms/op
     p(99.0000) =      4.334 ms/op
     p(99.9000) =      7.332 ms/op
     p(99.9900) =     17.629 ms/op
     p(99.9990) =     18.573 ms/op
     p(99.9999) =     18.711 ms/op
    p(100.0000) =     18.711 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.783 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.018 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.919 ±(99.9%) 0.006 ms/op
Iteration   1: 2.951 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.727 ms/op
                 existUser·p0.50:   2.953 ms/op
                 existUser·p0.90:   3.527 ms/op
                 existUser·p0.95:   3.764 ms/op
                 existUser·p0.99:   4.260 ms/op
                 existUser·p0.999:  6.417 ms/op
                 existUser·p0.9999: 17.444 ms/op
                 existUser·p1.00:   19.857 ms/op

Iteration   2: 2.967 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.804 ms/op
                 existUser·p0.50:   2.953 ms/op
                 existUser·p0.90:   3.547 ms/op
                 existUser·p0.95:   3.723 ms/op
                 existUser·p0.99:   4.088 ms/op
                 existUser·p0.999:  5.513 ms/op
                 existUser·p0.9999: 13.451 ms/op
                 existUser·p1.00:   13.795 ms/op

Iteration   3: 2.947 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.631 ms/op
                 existUser·p0.50:   2.941 ms/op
                 existUser·p0.90:   3.555 ms/op
                 existUser·p0.95:   3.760 ms/op
                 existUser·p0.99:   4.276 ms/op
                 existUser·p0.999:  7.557 ms/op
                 existUser·p0.9999: 15.029 ms/op
                 existUser·p1.00:   15.729 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 324774
  mean =      2.955 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2223 
    [ 1.250,  2.500) = 41073 
    [ 2.500,  3.750) = 265494 
    [ 3.750,  5.000) = 15060 
    [ 5.000,  6.250) = 509 
    [ 6.250,  7.500) = 174 
    [ 7.500,  8.750) = 48 
    [ 8.750, 10.000) = 33 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 17 
    [12.500, 13.750) = 85 
    [13.750, 15.000) = 15 
    [15.000, 16.250) = 11 
    [16.250, 17.500) = 23 
    [17.500, 18.750) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.631 ms/op
     p(50.0000) =      2.949 ms/op
     p(90.0000) =      3.543 ms/op
     p(95.0000) =      3.744 ms/op
     p(99.0000) =      4.219 ms/op
     p(99.9000) =      6.767 ms/op
     p(99.9900) =     16.063 ms/op
     p(99.9990) =     19.289 ms/op
     p(99.9999) =     19.857 ms/op
    p(100.0000) =     19.857 ms/op


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
# Warmup Iteration   1: 4.018 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.126 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.042 ±(99.9%) 0.006 ms/op
Iteration   1: 3.010 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.769 ms/op
                 getUser·p0.50:   3.015 ms/op
                 getUser·p0.90:   3.555 ms/op
                 getUser·p0.95:   3.760 ms/op
                 getUser·p0.99:   4.284 ms/op
                 getUser·p0.999:  6.289 ms/op
                 getUser·p0.9999: 11.522 ms/op
                 getUser·p1.00:   11.977 ms/op

Iteration   2: 3.115 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.682 ms/op
                 getUser·p0.50:   3.097 ms/op
                 getUser·p0.90:   3.719 ms/op
                 getUser·p0.95:   3.899 ms/op
                 getUser·p0.99:   4.366 ms/op
                 getUser·p0.999:  7.720 ms/op
                 getUser·p0.9999: 13.099 ms/op
                 getUser·p1.00:   13.369 ms/op

Iteration   3: 3.167 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.621 ms/op
                 getUser·p0.50:   3.146 ms/op
                 getUser·p0.90:   3.903 ms/op
                 getUser·p0.95:   4.059 ms/op
                 getUser·p0.99:   4.325 ms/op
                 getUser·p0.999:  6.013 ms/op
                 getUser·p0.9999: 22.970 ms/op
                 getUser·p1.00:   23.364 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 309877
  mean =      3.096 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24576 
    [ 2.500,  5.000) = 284367 
    [ 5.000,  7.500) = 686 
    [ 7.500, 10.000) = 74 
    [10.000, 12.500) = 84 
    [12.500, 15.000) = 58 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.621 ms/op
     p(50.0000) =      3.076 ms/op
     p(90.0000) =      3.748 ms/op
     p(95.0000) =      3.949 ms/op
     p(99.0000) =      4.334 ms/op
     p(99.9000) =      6.841 ms/op
     p(99.9900) =     21.039 ms/op
     p(99.9990) =     23.193 ms/op
     p(99.9999) =     23.364 ms/op
    p(100.0000) =     23.364 ms/op


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
# Warmup Iteration   1: 5.799 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.021 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.933 ±(99.9%) 0.010 ms/op
Iteration   1: 4.111 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.848 ms/op
                 listUser·p0.50:   3.912 ms/op
                 listUser·p0.90:   5.341 ms/op
                 listUser·p0.95:   5.743 ms/op
                 listUser·p0.99:   7.053 ms/op
                 listUser·p0.999:  11.993 ms/op
                 listUser·p0.9999: 14.887 ms/op
                 listUser·p1.00:   15.598 ms/op

Iteration   2: 3.980 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.249 ms/op
                 listUser·p0.50:   3.809 ms/op
                 listUser·p0.90:   5.112 ms/op
                 listUser·p0.95:   5.677 ms/op
                 listUser·p0.99:   6.750 ms/op
                 listUser·p0.999:  16.777 ms/op
                 listUser·p0.9999: 24.019 ms/op
                 listUser·p1.00:   24.609 ms/op

Iteration   3: 3.876 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.969 ms/op
                 listUser·p0.50:   3.781 ms/op
                 listUser·p0.90:   4.325 ms/op
                 listUser·p0.95:   5.120 ms/op
                 listUser·p0.99:   6.406 ms/op
                 listUser·p0.999:  18.366 ms/op
                 listUser·p0.9999: 22.340 ms/op
                 listUser·p1.00:   23.757 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 240798
  mean =      3.987 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4532 
    [ 2.500,  5.000) = 208526 
    [ 5.000,  7.500) = 26654 
    [ 7.500, 10.000) = 640 
    [10.000, 12.500) = 118 
    [12.500, 15.000) = 89 
    [15.000, 17.500) = 84 
    [17.500, 20.000) = 37 
    [20.000, 22.500) = 72 
    [22.500, 25.000) = 46 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.848 ms/op
     p(50.0000) =      3.817 ms/op
     p(90.0000) =      5.104 ms/op
     p(95.0000) =      5.595 ms/op
     p(99.0000) =      6.758 ms/op
     p(99.9000) =     14.887 ms/op
     p(99.9900) =     23.364 ms/op
     p(99.9990) =     24.444 ms/op
     p(99.9999) =     24.609 ms/op
    p(100.0000) =     24.609 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.217 ± 4.783  ops/ms
ClientGrpc.existUser                       thrpt       3  10.815 ± 3.589  ops/ms
ClientGrpc.getUser                         thrpt       3  10.133 ± 0.993  ops/ms
ClientGrpc.listUser                        thrpt       3   8.022 ± 2.112  ops/ms
ClientGrpc.createUser                       avgt       3   3.134 ± 0.257   ms/op
ClientGrpc.existUser                        avgt       3   2.944 ± 0.389   ms/op
ClientGrpc.getUser                          avgt       3   3.106 ± 0.398   ms/op
ClientGrpc.listUser                         avgt       3   3.978 ± 1.143   ms/op
ClientGrpc.createUser                     sample  309786   3.098 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.331           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.072           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.744           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.953           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.334           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.332           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.629           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          18.711           ms/op
ClientGrpc.existUser                      sample  324774   2.955 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.631           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.949           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.543           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.744           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.219           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.767           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.063           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.857           ms/op
ClientGrpc.getUser                        sample  309877   3.096 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.621           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.076           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.748           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.949           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.334           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.841           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.039           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.364           ms/op
ClientGrpc.listUser                       sample  240798   3.987 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.848           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.817           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.104           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.595           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.758           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.887           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.364           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.609           ms/op
