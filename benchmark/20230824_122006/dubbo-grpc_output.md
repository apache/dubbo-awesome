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
# Warmup Iteration   1: 4.312 ops/ms
# Warmup Iteration   2: 8.857 ops/ms
# Warmup Iteration   3: 10.066 ops/ms
Iteration   1: 10.546 ops/ms
Iteration   2: 10.634 ops/ms
Iteration   3: 10.692 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.624 ±(99.9%) 1.336 ops/ms [Average]
  (min, avg, max) = (10.546, 10.624, 10.692), stdev = 0.073
  CI (99.9%): [9.288, 11.961] (assumes normal distribution)


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
# Warmup Iteration   1: 7.247 ops/ms
# Warmup Iteration   2: 10.472 ops/ms
# Warmup Iteration   3: 11.066 ops/ms
Iteration   1: 10.889 ops/ms
Iteration   2: 11.122 ops/ms
Iteration   3: 11.041 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.017 ±(99.9%) 2.157 ops/ms [Average]
  (min, avg, max) = (10.889, 11.017, 11.122), stdev = 0.118
  CI (99.9%): [8.860, 13.175] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 6.835 ops/ms
# Warmup Iteration   2: 10.277 ops/ms
# Warmup Iteration   3: 10.457 ops/ms
Iteration   1: 10.529 ops/ms
Iteration   2: 10.400 ops/ms
Iteration   3: 10.495 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.475 ±(99.9%) 1.221 ops/ms [Average]
  (min, avg, max) = (10.400, 10.475, 10.529), stdev = 0.067
  CI (99.9%): [9.254, 11.696] (assumes normal distribution)


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
# Warmup Iteration   1: 5.485 ops/ms
# Warmup Iteration   2: 7.658 ops/ms
# Warmup Iteration   3: 7.997 ops/ms
Iteration   1: 8.112 ops/ms
Iteration   2: 8.139 ops/ms
Iteration   3: 7.977 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.076 ±(99.9%) 1.583 ops/ms [Average]
  (min, avg, max) = (7.977, 8.076, 8.139), stdev = 0.087
  CI (99.9%): [6.494, 9.659] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.993 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.155 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.119 ±(99.9%) 0.002 ms/op
Iteration   1: 3.130 ±(99.9%) 0.002 ms/op
Iteration   2: 3.083 ±(99.9%) 0.003 ms/op
Iteration   3: 3.145 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.119 ±(99.9%) 0.591 ms/op [Average]
  (min, avg, max) = (3.083, 3.119, 3.145), stdev = 0.032
  CI (99.9%): [2.529, 3.710] (assumes normal distribution)


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
# Warmup Iteration   1: 3.776 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.982 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.897 ±(99.9%) 0.003 ms/op
Iteration   1: 2.909 ±(99.9%) 0.003 ms/op
Iteration   2: 2.942 ±(99.9%) 0.003 ms/op
Iteration   3: 2.877 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.909 ±(99.9%) 0.598 ms/op [Average]
  (min, avg, max) = (2.877, 2.909, 2.942), stdev = 0.033
  CI (99.9%): [2.311, 3.507] (assumes normal distribution)


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
# Warmup Iteration   1: 4.187 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.128 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.996 ±(99.9%) 0.004 ms/op
Iteration   1: 3.001 ±(99.9%) 0.004 ms/op
Iteration   2: 2.998 ±(99.9%) 0.004 ms/op
Iteration   3: 3.014 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.004 ±(99.9%) 0.158 ms/op [Average]
  (min, avg, max) = (2.998, 3.004, 3.014), stdev = 0.009
  CI (99.9%): [2.846, 3.163] (assumes normal distribution)


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
# Warmup Iteration   1: 5.287 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 4.105 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.978 ±(99.9%) 0.013 ms/op
Iteration   1: 3.987 ±(99.9%) 0.018 ms/op
Iteration   2: 3.997 ±(99.9%) 0.018 ms/op
Iteration   3: 3.917 ±(99.9%) 0.023 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.967 ±(99.9%) 0.790 ms/op [Average]
  (min, avg, max) = (3.917, 3.967, 3.997), stdev = 0.043
  CI (99.9%): [3.177, 4.757] (assumes normal distribution)


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
# Warmup Iteration   1: 4.165 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.199 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.094 ±(99.9%) 0.006 ms/op
Iteration   1: 3.068 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.813 ms/op
                 createUser·p0.50:   3.023 ms/op
                 createUser·p0.90:   3.715 ms/op
                 createUser·p0.95:   3.977 ms/op
                 createUser·p0.99:   4.776 ms/op
                 createUser·p0.999:  8.421 ms/op
                 createUser·p0.9999: 14.896 ms/op
                 createUser·p1.00:   15.335 ms/op

Iteration   2: 3.109 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.896 ms/op
                 createUser·p0.50:   3.072 ms/op
                 createUser·p0.90:   3.625 ms/op
                 createUser·p0.95:   3.793 ms/op
                 createUser·p0.99:   4.354 ms/op
                 createUser·p0.999:  8.366 ms/op
                 createUser·p0.9999: 15.450 ms/op
                 createUser·p1.00:   16.138 ms/op

Iteration   3: 3.086 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.793 ms/op
                 createUser·p0.50:   3.052 ms/op
                 createUser·p0.90:   3.621 ms/op
                 createUser·p0.95:   3.768 ms/op
                 createUser·p0.99:   4.284 ms/op
                 createUser·p0.999:  8.643 ms/op
                 createUser·p0.9999: 17.320 ms/op
                 createUser·p1.00:   18.121 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 310701
  mean =      3.088 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 536 
    [ 1.250,  2.500) = 20451 
    [ 2.500,  3.750) = 268257 
    [ 3.750,  5.000) = 19659 
    [ 5.000,  6.250) = 865 
    [ 6.250,  7.500) = 413 
    [ 7.500,  8.750) = 244 
    [ 8.750, 10.000) = 17 
    [10.000, 11.250) = 65 
    [11.250, 12.500) = 5 
    [12.500, 13.750) = 45 
    [13.750, 15.000) = 52 
    [15.000, 16.250) = 60 
    [16.250, 17.500) = 25 
    [17.500, 18.750) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.793 ms/op
     p(50.0000) =      3.047 ms/op
     p(90.0000) =      3.645 ms/op
     p(95.0000) =      3.846 ms/op
     p(99.0000) =      4.506 ms/op
     p(99.9000) =      8.421 ms/op
     p(99.9900) =     16.299 ms/op
     p(99.9990) =     18.070 ms/op
     p(99.9999) =     18.121 ms/op
    p(100.0000) =     18.121 ms/op


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
# Warmup Iteration   1: 3.951 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.030 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.983 ±(99.9%) 0.006 ms/op
Iteration   1: 2.851 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.729 ms/op
                 existUser·p0.50:   2.879 ms/op
                 existUser·p0.90:   3.400 ms/op
                 existUser·p0.95:   3.633 ms/op
                 existUser·p0.99:   4.310 ms/op
                 existUser·p0.999:  7.159 ms/op
                 existUser·p0.9999: 15.578 ms/op
                 existUser·p1.00:   15.761 ms/op

Iteration   2: 2.888 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.730 ms/op
                 existUser·p0.50:   2.875 ms/op
                 existUser·p0.90:   3.281 ms/op
                 existUser·p0.95:   3.473 ms/op
                 existUser·p0.99:   4.456 ms/op
                 existUser·p0.999:  9.650 ms/op
                 existUser·p0.9999: 14.975 ms/op
                 existUser·p1.00:   15.221 ms/op

Iteration   3: 2.944 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.483 ms/op
                 existUser·p0.50:   2.904 ms/op
                 existUser·p0.90:   3.449 ms/op
                 existUser·p0.95:   3.621 ms/op
                 existUser·p0.99:   4.325 ms/op
                 existUser·p0.999:  8.460 ms/op
                 existUser·p0.9999: 27.361 ms/op
                 existUser·p1.00:   27.623 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 331472
  mean =      2.894 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 42079 
    [ 2.500,  5.000) = 287706 
    [ 5.000,  7.500) = 1237 
    [ 7.500, 10.000) = 224 
    [10.000, 12.500) = 66 
    [12.500, 15.000) = 54 
    [15.000, 17.500) = 74 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 29 

  Percentiles, ms/op:
      p(0.0000) =      0.483 ms/op
     p(50.0000) =      2.888 ms/op
     p(90.0000) =      3.375 ms/op
     p(95.0000) =      3.592 ms/op
     p(99.0000) =      4.366 ms/op
     p(99.9000) =      8.471 ms/op
     p(99.9900) =     16.300 ms/op
     p(99.9990) =     27.515 ms/op
     p(99.9999) =     27.623 ms/op
    p(100.0000) =     27.623 ms/op


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
# Warmup Iteration   1: 4.219 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.197 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.061 ±(99.9%) 0.006 ms/op
Iteration   1: 3.071 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.794 ms/op
                 getUser·p0.50:   3.031 ms/op
                 getUser·p0.90:   3.576 ms/op
                 getUser·p0.95:   3.817 ms/op
                 getUser·p0.99:   4.768 ms/op
                 getUser·p0.999:  8.487 ms/op
                 getUser·p0.9999: 13.880 ms/op
                 getUser·p1.00:   14.139 ms/op

Iteration   2: 3.011 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.842 ms/op
                 getUser·p0.50:   2.994 ms/op
                 getUser·p0.90:   3.396 ms/op
                 getUser·p0.95:   3.596 ms/op
                 getUser·p0.99:   4.424 ms/op
                 getUser·p0.999:  8.291 ms/op
                 getUser·p0.9999: 17.280 ms/op
                 getUser·p1.00:   17.662 ms/op

Iteration   3: 3.111 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.866 ms/op
                 getUser·p0.50:   3.072 ms/op
                 getUser·p0.90:   3.674 ms/op
                 getUser·p0.95:   3.834 ms/op
                 getUser·p0.99:   4.530 ms/op
                 getUser·p0.999:  7.661 ms/op
                 getUser·p0.9999: 17.882 ms/op
                 getUser·p1.00:   18.350 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 313519
  mean =      3.064 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 460 
    [ 1.250,  2.500) = 17409 
    [ 2.500,  3.750) = 278551 
    [ 3.750,  5.000) = 15116 
    [ 5.000,  6.250) = 1005 
    [ 6.250,  7.500) = 501 
    [ 7.500,  8.750) = 205 
    [ 8.750, 10.000) = 79 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 45 
    [13.750, 15.000) = 19 
    [15.000, 16.250) = 49 
    [16.250, 17.500) = 51 
    [17.500, 18.750) = 28 

  Percentiles, ms/op:
      p(0.0000) =      0.794 ms/op
     p(50.0000) =      3.031 ms/op
     p(90.0000) =      3.572 ms/op
     p(95.0000) =      3.777 ms/op
     p(99.0000) =      4.579 ms/op
     p(99.9000) =      8.298 ms/op
     p(99.9900) =     17.367 ms/op
     p(99.9990) =     18.240 ms/op
     p(99.9999) =     18.350 ms/op
    p(100.0000) =     18.350 ms/op


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
# Warmup Iteration   1: 4.966 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 4.169 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.943 ±(99.9%) 0.012 ms/op
Iteration   1: 3.988 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.130 ms/op
                 listUser·p0.50:   3.813 ms/op
                 listUser·p0.90:   5.054 ms/op
                 listUser·p0.95:   5.890 ms/op
                 listUser·p0.99:   7.201 ms/op
                 listUser·p0.999:  14.605 ms/op
                 listUser·p0.9999: 19.201 ms/op
                 listUser·p1.00:   19.431 ms/op

Iteration   2: 3.952 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.667 ms/op
                 listUser·p0.50:   3.801 ms/op
                 listUser·p0.90:   4.981 ms/op
                 listUser·p0.95:   5.808 ms/op
                 listUser·p0.99:   7.012 ms/op
                 listUser·p0.999:  16.807 ms/op
                 listUser·p0.9999: 19.464 ms/op
                 listUser·p1.00:   19.759 ms/op

Iteration   3: 3.988 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.133 ms/op
                 listUser·p0.50:   3.846 ms/op
                 listUser·p0.90:   4.801 ms/op
                 listUser·p0.95:   5.587 ms/op
                 listUser·p0.99:   7.062 ms/op
                 listUser·p0.999:  15.853 ms/op
                 listUser·p0.9999: 27.589 ms/op
                 listUser·p1.00:   27.918 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 241462
  mean =      3.976 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3619 
    [ 2.500,  5.000) = 214956 
    [ 5.000,  7.500) = 21232 
    [ 7.500, 10.000) = 1188 
    [10.000, 12.500) = 108 
    [12.500, 15.000) = 90 
    [15.000, 17.500) = 137 
    [17.500, 20.000) = 100 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 23 

  Percentiles, ms/op:
      p(0.0000) =      0.667 ms/op
     p(50.0000) =      3.822 ms/op
     p(90.0000) =      4.932 ms/op
     p(95.0000) =      5.784 ms/op
     p(99.0000) =      7.086 ms/op
     p(99.9000) =     15.630 ms/op
     p(99.9900) =     26.079 ms/op
     p(99.9990) =     27.774 ms/op
     p(99.9999) =     27.918 ms/op
    p(100.0000) =     27.918 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.624 ± 1.336  ops/ms
ClientGrpc.existUser                       thrpt       3  11.017 ± 2.157  ops/ms
ClientGrpc.getUser                         thrpt       3  10.475 ± 1.221  ops/ms
ClientGrpc.listUser                        thrpt       3   8.076 ± 1.583  ops/ms
ClientGrpc.createUser                       avgt       3   3.119 ± 0.591   ms/op
ClientGrpc.existUser                        avgt       3   2.909 ± 0.598   ms/op
ClientGrpc.getUser                          avgt       3   3.004 ± 0.158   ms/op
ClientGrpc.listUser                         avgt       3   3.967 ± 0.790   ms/op
ClientGrpc.createUser                     sample  310701   3.088 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.793           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.047           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.645           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.846           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.506           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.421           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          16.299           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          18.121           ms/op
ClientGrpc.existUser                      sample  331472   2.894 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.483           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.888           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.375           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.592           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.366           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.471           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.300           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          27.623           ms/op
ClientGrpc.getUser                        sample  313519   3.064 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.794           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.031           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.572           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.777           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.579           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.298           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.367           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.350           ms/op
ClientGrpc.listUser                       sample  241462   3.976 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.667           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.822           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.932           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.784           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.086           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.630           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          26.079           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.918           ms/op
