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
# Warmup Iteration   1: 3.290 ops/ms
# Warmup Iteration   2: 6.932 ops/ms
# Warmup Iteration   3: 7.956 ops/ms
Iteration   1: 8.483 ops/ms
Iteration   2: 8.492 ops/ms
Iteration   3: 8.607 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.527 ±(99.9%) 1.261 ops/ms [Average]
  (min, avg, max) = (8.483, 8.527, 8.607), stdev = 0.069
  CI (99.9%): [7.266, 9.788] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 5.596 ops/ms
# Warmup Iteration   2: 8.507 ops/ms
# Warmup Iteration   3: 8.956 ops/ms
Iteration   1: 9.161 ops/ms
Iteration   2: 9.107 ops/ms
Iteration   3: 8.903 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.057 ±(99.9%) 2.486 ops/ms [Average]
  (min, avg, max) = (8.903, 9.057, 9.161), stdev = 0.136
  CI (99.9%): [6.571, 11.543] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 6.073 ops/ms
# Warmup Iteration   2: 7.820 ops/ms
# Warmup Iteration   3: 8.336 ops/ms
Iteration   1: 8.551 ops/ms
Iteration   2: 8.744 ops/ms
Iteration   3: 8.624 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.640 ±(99.9%) 1.774 ops/ms [Average]
  (min, avg, max) = (8.551, 8.640, 8.744), stdev = 0.097
  CI (99.9%): [6.866, 10.413] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 5.126 ops/ms
# Warmup Iteration   2: 6.042 ops/ms
# Warmup Iteration   3: 6.547 ops/ms
Iteration   1: 7.028 ops/ms
Iteration   2: 6.606 ops/ms
Iteration   3: 6.733 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.789 ±(99.9%) 3.954 ops/ms [Average]
  (min, avg, max) = (6.606, 6.789, 7.028), stdev = 0.217
  CI (99.9%): [2.835, 10.743] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 5.320 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.982 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.802 ±(99.9%) 0.023 ms/op
Iteration   1: 3.741 ±(99.9%) 0.004 ms/op
Iteration   2: 3.749 ±(99.9%) 0.004 ms/op
Iteration   3: 3.631 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.707 ±(99.9%) 1.200 ms/op [Average]
  (min, avg, max) = (3.631, 3.707, 3.749), stdev = 0.066
  CI (99.9%): [2.507, 4.907] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 5.039 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.709 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.532 ±(99.9%) 0.003 ms/op
Iteration   1: 3.512 ±(99.9%) 0.004 ms/op
Iteration   2: 3.519 ±(99.9%) 0.004 ms/op
Iteration   3: 3.541 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.524 ±(99.9%) 0.280 ms/op [Average]
  (min, avg, max) = (3.512, 3.524, 3.541), stdev = 0.015
  CI (99.9%): [3.244, 3.804] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 5.404 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.789 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.725 ±(99.9%) 0.006 ms/op
Iteration   1: 3.604 ±(99.9%) 0.003 ms/op
Iteration   2: 3.667 ±(99.9%) 0.003 ms/op
Iteration   3: 3.602 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.624 ±(99.9%) 0.673 ms/op [Average]
  (min, avg, max) = (3.602, 3.624, 3.667), stdev = 0.037
  CI (99.9%): [2.951, 4.297] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 5.728 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 5.017 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.755 ±(99.9%) 0.012 ms/op
Iteration   1: 4.689 ±(99.9%) 0.012 ms/op
Iteration   2: 4.736 ±(99.9%) 0.023 ms/op
Iteration   3: 4.764 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.730 ±(99.9%) 0.698 ms/op [Average]
  (min, avg, max) = (4.689, 4.730, 4.764), stdev = 0.038
  CI (99.9%): [4.031, 5.428] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 5.292 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 4.102 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.818 ±(99.9%) 0.009 ms/op
Iteration   1: 3.765 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.037 ms/op
                 createUser·p0.50:   3.723 ms/op
                 createUser·p0.90:   4.473 ms/op
                 createUser·p0.95:   4.768 ms/op
                 createUser·p0.99:   5.767 ms/op
                 createUser·p0.999:  11.159 ms/op
                 createUser·p0.9999: 16.384 ms/op
                 createUser·p1.00:   16.843 ms/op

Iteration   2: 3.808 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.110 ms/op
                 createUser·p0.50:   3.723 ms/op
                 createUser·p0.90:   4.555 ms/op
                 createUser·p0.95:   4.948 ms/op
                 createUser·p0.99:   6.439 ms/op
                 createUser·p0.999:  11.583 ms/op
                 createUser·p0.9999: 16.050 ms/op
                 createUser·p1.00:   16.744 ms/op

Iteration   3: 3.679 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.942 ms/op
                 createUser·p0.50:   3.633 ms/op
                 createUser·p0.90:   4.252 ms/op
                 createUser·p0.95:   4.563 ms/op
                 createUser·p0.99:   5.456 ms/op
                 createUser·p0.999:  16.843 ms/op
                 createUser·p0.9999: 19.363 ms/op
                 createUser·p1.00:   20.316 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 255855
  mean =      3.750 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5861 
    [ 2.500,  5.000) = 241961 
    [ 5.000,  7.500) = 7081 
    [ 7.500, 10.000) = 543 
    [10.000, 12.500) = 185 
    [12.500, 15.000) = 76 
    [15.000, 17.500) = 119 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.942 ms/op
     p(50.0000) =      3.690 ms/op
     p(90.0000) =      4.440 ms/op
     p(95.0000) =      4.760 ms/op
     p(99.0000) =      5.931 ms/op
     p(99.9000) =     11.338 ms/op
     p(99.9900) =     17.544 ms/op
     p(99.9990) =     20.141 ms/op
     p(99.9999) =     20.316 ms/op
    p(100.0000) =     20.316 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 4.701 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.741 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.489 ±(99.9%) 0.008 ms/op
Iteration   1: 3.533 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.674 ms/op
                 existUser·p0.50:   3.494 ms/op
                 existUser·p0.90:   4.121 ms/op
                 existUser·p0.95:   4.391 ms/op
                 existUser·p0.99:   5.325 ms/op
                 existUser·p0.999:  8.760 ms/op
                 existUser·p0.9999: 15.286 ms/op
                 existUser·p1.00:   18.055 ms/op

Iteration   2: 3.475 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.851 ms/op
                 existUser·p0.50:   3.445 ms/op
                 existUser·p0.90:   4.035 ms/op
                 existUser·p0.95:   4.383 ms/op
                 existUser·p0.99:   5.546 ms/op
                 existUser·p0.999:  9.353 ms/op
                 existUser·p0.9999: 17.262 ms/op
                 existUser·p1.00:   19.628 ms/op

Iteration   3: 3.566 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.856 ms/op
                 existUser·p0.50:   3.502 ms/op
                 existUser·p0.90:   4.071 ms/op
                 existUser·p0.95:   4.383 ms/op
                 existUser·p0.99:   5.194 ms/op
                 existUser·p0.999:  9.814 ms/op
                 existUser·p0.9999: 27.199 ms/op
                 existUser·p1.00:   27.492 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 272448
  mean =      3.524 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6914 
    [ 2.500,  5.000) = 261125 
    [ 5.000,  7.500) = 3912 
    [ 7.500, 10.000) = 275 
    [10.000, 12.500) = 94 
    [12.500, 15.000) = 14 
    [15.000, 17.500) = 80 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 27 

  Percentiles, ms/op:
      p(0.0000) =      0.674 ms/op
     p(50.0000) =      3.482 ms/op
     p(90.0000) =      4.080 ms/op
     p(95.0000) =      4.391 ms/op
     p(99.0000) =      5.366 ms/op
     p(99.9000) =      9.037 ms/op
     p(99.9900) =     25.258 ms/op
     p(99.9990) =     27.436 ms/op
     p(99.9999) =     27.492 ms/op
    p(100.0000) =     27.492 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.069 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.889 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.817 ±(99.9%) 0.010 ms/op
Iteration   1: 3.838 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.073 ms/op
                 getUser·p0.50:   3.748 ms/op
                 getUser·p0.90:   4.645 ms/op
                 getUser·p0.95:   5.095 ms/op
                 getUser·p0.99:   7.119 ms/op
                 getUser·p0.999:  10.633 ms/op
                 getUser·p0.9999: 15.041 ms/op
                 getUser·p1.00:   15.450 ms/op

Iteration   2: 3.711 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.032 ms/op
                 getUser·p0.50:   3.670 ms/op
                 getUser·p0.90:   4.407 ms/op
                 getUser·p0.95:   4.702 ms/op
                 getUser·p0.99:   5.595 ms/op
                 getUser·p0.999:  8.301 ms/op
                 getUser·p0.9999: 16.599 ms/op
                 getUser·p1.00:   17.269 ms/op

Iteration   3: 3.746 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.969 ms/op
                 getUser·p0.50:   3.690 ms/op
                 getUser·p0.90:   4.522 ms/op
                 getUser·p0.95:   4.874 ms/op
                 getUser·p0.99:   6.021 ms/op
                 getUser·p0.999:  10.895 ms/op
                 getUser·p0.9999: 22.294 ms/op
                 getUser·p1.00:   22.610 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 255032
  mean =      3.764 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8424 
    [ 2.500,  5.000) = 236257 
    [ 5.000,  7.500) = 9195 
    [ 7.500, 10.000) = 844 
    [10.000, 12.500) = 182 
    [12.500, 15.000) = 46 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.969 ms/op
     p(50.0000) =      3.699 ms/op
     p(90.0000) =      4.522 ms/op
     p(95.0000) =      4.882 ms/op
     p(99.0000) =      6.210 ms/op
     p(99.9000) =     10.633 ms/op
     p(99.9900) =     19.480 ms/op
     p(99.9990) =     22.544 ms/op
     p(99.9999) =     22.610 ms/op
    p(100.0000) =     22.610 ms/op


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
# Warmup Iteration   1: 6.577 ±(99.9%) 0.069 ms/op
# Warmup Iteration   2: 4.946 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.903 ±(99.9%) 0.015 ms/op
Iteration   1: 4.861 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.272 ms/op
                 listUser·p0.50:   4.653 ms/op
                 listUser·p0.90:   5.956 ms/op
                 listUser·p0.95:   6.881 ms/op
                 listUser·p0.99:   8.946 ms/op
                 listUser·p0.999:  16.582 ms/op
                 listUser·p0.9999: 23.273 ms/op
                 listUser·p1.00:   23.626 ms/op

Iteration   2: 4.747 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.010 ms/op
                 listUser·p0.50:   4.579 ms/op
                 listUser·p0.90:   5.628 ms/op
                 listUser·p0.95:   6.545 ms/op
                 listUser·p0.99:   8.331 ms/op
                 listUser·p0.999:  16.974 ms/op
                 listUser·p0.9999: 33.964 ms/op
                 listUser·p1.00:   34.406 ms/op

Iteration   3: 4.816 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   0.585 ms/op
                 listUser·p0.50:   4.628 ms/op
                 listUser·p0.90:   5.825 ms/op
                 listUser·p0.95:   6.783 ms/op
                 listUser·p0.99:   8.537 ms/op
                 listUser·p0.999:  20.729 ms/op
                 listUser·p0.9999: 28.237 ms/op
                 listUser·p1.00:   28.672 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 199738
  mean =      4.808 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 224 
    [ 2.500,  5.000) = 150142 
    [ 5.000,  7.500) = 44031 
    [ 7.500, 10.000) = 4470 
    [10.000, 12.500) = 454 
    [12.500, 15.000) = 148 
    [15.000, 17.500) = 92 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 59 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 18 
    [27.500, 30.000) = 14 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 27 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.585 ms/op
     p(50.0000) =      4.620 ms/op
     p(90.0000) =      5.816 ms/op
     p(95.0000) =      6.750 ms/op
     p(99.0000) =      8.569 ms/op
     p(99.9000) =     17.269 ms/op
     p(99.9900) =     32.902 ms/op
     p(99.9990) =     34.276 ms/op
     p(99.9999) =     34.406 ms/op
    p(100.0000) =     34.406 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.527 ± 1.261  ops/ms
ClientGrpc.existUser                       thrpt       3   9.057 ± 2.486  ops/ms
ClientGrpc.getUser                         thrpt       3   8.640 ± 1.774  ops/ms
ClientGrpc.listUser                        thrpt       3   6.789 ± 3.954  ops/ms
ClientGrpc.createUser                       avgt       3   3.707 ± 1.200   ms/op
ClientGrpc.existUser                        avgt       3   3.524 ± 0.280   ms/op
ClientGrpc.getUser                          avgt       3   3.624 ± 0.673   ms/op
ClientGrpc.listUser                         avgt       3   4.730 ± 0.698   ms/op
ClientGrpc.createUser                     sample  255855   3.750 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.942           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.690           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.440           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.760           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.931           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.338           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.544           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          20.316           ms/op
ClientGrpc.existUser                      sample  272448   3.524 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.674           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.482           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.080           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.391           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.366           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.037           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          25.258           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          27.492           ms/op
ClientGrpc.getUser                        sample  255032   3.764 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.969           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.699           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.522           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.882           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.210           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.633           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.480           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.610           ms/op
ClientGrpc.listUser                       sample  199738   4.808 ± 0.009   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.585           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.620           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.816           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.750           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.569           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.269           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          32.902           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          34.406           ms/op
