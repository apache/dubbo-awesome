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
# Warmup Iteration   1: 4.729 ops/ms
# Warmup Iteration   2: 9.578 ops/ms
# Warmup Iteration   3: 10.238 ops/ms
Iteration   1: 10.591 ops/ms
Iteration   2: 10.910 ops/ms
Iteration   3: 10.984 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.828 ±(99.9%) 3.802 ops/ms [Average]
  (min, avg, max) = (10.591, 10.828, 10.984), stdev = 0.208
  CI (99.9%): [7.026, 14.630] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.767 ops/ms
# Warmup Iteration   2: 10.986 ops/ms
# Warmup Iteration   3: 11.377 ops/ms
Iteration   1: 11.197 ops/ms
Iteration   2: 11.788 ops/ms
Iteration   3: 11.250 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.411 ±(99.9%) 5.966 ops/ms [Average]
  (min, avg, max) = (11.197, 11.411, 11.788), stdev = 0.327
  CI (99.9%): [5.446, 17.377] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.734 ops/ms
# Warmup Iteration   2: 10.582 ops/ms
# Warmup Iteration   3: 10.789 ops/ms
Iteration   1: 10.760 ops/ms
Iteration   2: 10.887 ops/ms
Iteration   3: 10.688 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.778 ±(99.9%) 1.833 ops/ms [Average]
  (min, avg, max) = (10.688, 10.778, 10.887), stdev = 0.100
  CI (99.9%): [8.945, 12.611] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.862 ops/ms
# Warmup Iteration   2: 8.068 ops/ms
# Warmup Iteration   3: 8.317 ops/ms
Iteration   1: 8.311 ops/ms
Iteration   2: 8.536 ops/ms
Iteration   3: 8.377 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.408 ±(99.9%) 2.108 ops/ms [Average]
  (min, avg, max) = (8.311, 8.408, 8.536), stdev = 0.116
  CI (99.9%): [6.300, 10.516] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.049 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.104 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 2.999 ±(99.9%) 0.003 ms/op
Iteration   1: 2.987 ±(99.9%) 0.002 ms/op
Iteration   2: 2.922 ±(99.9%) 0.003 ms/op
Iteration   3: 2.975 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.961 ±(99.9%) 0.634 ms/op [Average]
  (min, avg, max) = (2.922, 2.961, 2.987), stdev = 0.035
  CI (99.9%): [2.327, 3.595] (assumes normal distribution)


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
# Warmup Iteration   1: 3.711 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.021 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.886 ±(99.9%) 0.002 ms/op
Iteration   1: 2.797 ±(99.9%) 0.003 ms/op
Iteration   2: 2.782 ±(99.9%) 0.003 ms/op
Iteration   3: 2.854 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.811 ±(99.9%) 0.691 ms/op [Average]
  (min, avg, max) = (2.782, 2.811, 2.854), stdev = 0.038
  CI (99.9%): [2.120, 3.502] (assumes normal distribution)


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
# Warmup Iteration   1: 3.760 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 3.048 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 2.967 ±(99.9%) 0.005 ms/op
Iteration   1: 2.941 ±(99.9%) 0.003 ms/op
Iteration   2: 2.960 ±(99.9%) 0.002 ms/op
Iteration   3: 2.920 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.941 ±(99.9%) 0.362 ms/op [Average]
  (min, avg, max) = (2.920, 2.941, 2.960), stdev = 0.020
  CI (99.9%): [2.578, 3.303] (assumes normal distribution)


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
# Warmup Iteration   1: 4.551 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.938 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 3.791 ±(99.9%) 0.025 ms/op
Iteration   1: 3.825 ±(99.9%) 0.017 ms/op
Iteration   2: 3.722 ±(99.9%) 0.015 ms/op
Iteration   3: 3.865 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.804 ±(99.9%) 1.349 ms/op [Average]
  (min, avg, max) = (3.722, 3.804, 3.865), stdev = 0.074
  CI (99.9%): [2.455, 5.152] (assumes normal distribution)


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
# Warmup Iteration   1: 3.883 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.036 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.955 ±(99.9%) 0.006 ms/op
Iteration   1: 2.970 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.856 ms/op
                 createUser·p0.50:   2.941 ms/op
                 createUser·p0.90:   3.461 ms/op
                 createUser·p0.95:   3.654 ms/op
                 createUser·p0.99:   4.186 ms/op
                 createUser·p0.999:  7.755 ms/op
                 createUser·p0.9999: 12.636 ms/op
                 createUser·p1.00:   12.829 ms/op

Iteration   2: 3.002 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.531 ms/op
                 createUser·p0.50:   2.966 ms/op
                 createUser·p0.90:   3.588 ms/op
                 createUser·p0.95:   3.813 ms/op
                 createUser·p0.99:   4.497 ms/op
                 createUser·p0.999:  8.517 ms/op
                 createUser·p0.9999: 12.796 ms/op
                 createUser·p1.00:   12.878 ms/op

Iteration   3: 2.964 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.706 ms/op
                 createUser·p0.50:   2.933 ms/op
                 createUser·p0.90:   3.363 ms/op
                 createUser·p0.95:   3.486 ms/op
                 createUser·p0.99:   4.010 ms/op
                 createUser·p0.999:  9.158 ms/op
                 createUser·p0.9999: 22.354 ms/op
                 createUser·p1.00:   26.608 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 322270
  mean =      2.979 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23884 
    [ 2.500,  5.000) = 297239 
    [ 5.000,  7.500) = 715 
    [ 7.500, 10.000) = 186 
    [10.000, 12.500) = 91 
    [12.500, 15.000) = 91 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.531 ms/op
     p(50.0000) =      2.945 ms/op
     p(90.0000) =      3.457 ms/op
     p(95.0000) =      3.662 ms/op
     p(99.0000) =      4.301 ms/op
     p(99.9000) =      8.380 ms/op
     p(99.9900) =     20.963 ms/op
     p(99.9990) =     22.537 ms/op
     p(99.9999) =     26.608 ms/op
    p(100.0000) =     26.608 ms/op


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
# Warmup Iteration   1: 3.736 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 2.928 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.874 ±(99.9%) 0.006 ms/op
Iteration   1: 2.831 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.529 ms/op
                 existUser·p0.50:   2.855 ms/op
                 existUser·p0.90:   3.334 ms/op
                 existUser·p0.95:   3.568 ms/op
                 existUser·p0.99:   4.157 ms/op
                 existUser·p0.999:  7.810 ms/op
                 existUser·p0.9999: 13.666 ms/op
                 existUser·p1.00:   14.549 ms/op

Iteration   2: 2.813 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.676 ms/op
                 existUser·p0.50:   2.818 ms/op
                 existUser·p0.90:   3.351 ms/op
                 existUser·p0.95:   3.563 ms/op
                 existUser·p0.99:   4.141 ms/op
                 existUser·p0.999:  5.169 ms/op
                 existUser·p0.9999: 12.511 ms/op
                 existUser·p1.00:   14.795 ms/op

Iteration   3: 2.840 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.653 ms/op
                 existUser·p0.50:   2.847 ms/op
                 existUser·p0.90:   3.359 ms/op
                 existUser·p0.95:   3.547 ms/op
                 existUser·p0.99:   4.194 ms/op
                 existUser·p0.999:  7.181 ms/op
                 existUser·p0.9999: 16.134 ms/op
                 existUser·p1.00:   16.384 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 339374
  mean =      2.828 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 4181 
    [ 1.250,  2.500) = 54037 
    [ 2.500,  3.750) = 272704 
    [ 3.750,  5.000) = 7456 
    [ 5.000,  6.250) = 516 
    [ 6.250,  7.500) = 194 
    [ 7.500,  8.750) = 57 
    [ 8.750, 10.000) = 26 
    [10.000, 11.250) = 10 
    [11.250, 12.500) = 95 
    [12.500, 13.750) = 38 
    [13.750, 15.000) = 25 
    [15.000, 16.250) = 29 
    [16.250, 17.500) = 6 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.529 ms/op
     p(50.0000) =      2.843 ms/op
     p(90.0000) =      3.346 ms/op
     p(95.0000) =      3.559 ms/op
     p(99.0000) =      4.162 ms/op
     p(99.9000) =      6.955 ms/op
     p(99.9900) =     15.077 ms/op
     p(99.9990) =     16.338 ms/op
     p(99.9999) =     16.384 ms/op
    p(100.0000) =     16.384 ms/op


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
# Warmup Iteration   1: 3.945 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.041 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.978 ±(99.9%) 0.008 ms/op
Iteration   1: 2.935 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.569 ms/op
                 getUser·p0.50:   2.912 ms/op
                 getUser·p0.90:   3.379 ms/op
                 getUser·p0.95:   3.699 ms/op
                 getUser·p0.99:   4.375 ms/op
                 getUser·p0.999:  8.225 ms/op
                 getUser·p0.9999: 23.606 ms/op
                 getUser·p1.00:   25.297 ms/op

Iteration   2: 2.938 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.239 ms/op
                 getUser·p0.50:   2.933 ms/op
                 getUser·p0.90:   3.342 ms/op
                 getUser·p0.95:   3.576 ms/op
                 getUser·p0.99:   4.284 ms/op
                 getUser·p0.999:  6.554 ms/op
                 getUser·p0.9999: 33.099 ms/op
                 getUser·p1.00:   33.325 ms/op

Iteration   3: 2.886 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.258 ms/op
                 getUser·p0.50:   2.896 ms/op
                 getUser·p0.90:   3.301 ms/op
                 getUser·p0.95:   3.555 ms/op
                 getUser·p0.99:   4.325 ms/op
                 getUser·p0.999:  7.188 ms/op
                 getUser·p0.9999: 24.604 ms/op
                 getUser·p1.00:   25.494 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 328771
  mean =      2.920 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 33077 
    [ 2.500,  5.000) = 294502 
    [ 5.000,  7.500) = 836 
    [ 7.500, 10.000) = 158 
    [10.000, 12.500) = 6 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 61 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 54 
    [25.000, 27.500) = 10 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 32 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.239 ms/op
     p(50.0000) =      2.916 ms/op
     p(90.0000) =      3.338 ms/op
     p(95.0000) =      3.613 ms/op
     p(99.0000) =      4.334 ms/op
     p(99.9000) =      7.858 ms/op
     p(99.9900) =     26.363 ms/op
     p(99.9990) =     33.292 ms/op
     p(99.9999) =     33.325 ms/op
    p(100.0000) =     33.325 ms/op


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
# Warmup Iteration   1: 4.274 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 4.099 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.847 ±(99.9%) 0.010 ms/op
Iteration   1: 3.878 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.194 ms/op
                 listUser·p0.50:   3.764 ms/op
                 listUser·p0.90:   4.760 ms/op
                 listUser·p0.95:   5.480 ms/op
                 listUser·p0.99:   6.513 ms/op
                 listUser·p0.999:  13.426 ms/op
                 listUser·p0.9999: 18.202 ms/op
                 listUser·p1.00:   18.448 ms/op

Iteration   2: 3.878 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.792 ms/op
                 listUser·p0.50:   3.756 ms/op
                 listUser·p0.90:   4.850 ms/op
                 listUser·p0.95:   5.505 ms/op
                 listUser·p0.99:   6.701 ms/op
                 listUser·p0.999:  14.287 ms/op
                 listUser·p0.9999: 17.605 ms/op
                 listUser·p1.00:   17.957 ms/op

Iteration   3: 3.790 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.067 ms/op
                 listUser·p0.50:   3.666 ms/op
                 listUser·p0.90:   4.727 ms/op
                 listUser·p0.95:   5.333 ms/op
                 listUser·p0.99:   6.595 ms/op
                 listUser·p0.999:  13.088 ms/op
                 listUser·p0.9999: 16.332 ms/op
                 listUser·p1.00:   16.810 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 249419
  mean =      3.848 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 10 
    [ 1.250,  2.500) = 4808 
    [ 2.500,  3.750) = 124385 
    [ 3.750,  5.000) = 100221 
    [ 5.000,  6.250) = 15822 
    [ 6.250,  7.500) = 3251 
    [ 7.500,  8.750) = 385 
    [ 8.750, 10.000) = 110 
    [10.000, 11.250) = 45 
    [11.250, 12.500) = 54 
    [12.500, 13.750) = 108 
    [13.750, 15.000) = 99 
    [15.000, 16.250) = 42 
    [16.250, 17.500) = 42 
    [17.500, 18.750) = 37 

  Percentiles, ms/op:
      p(0.0000) =      0.792 ms/op
     p(50.0000) =      3.731 ms/op
     p(90.0000) =      4.784 ms/op
     p(95.0000) =      5.448 ms/op
     p(99.0000) =      6.603 ms/op
     p(99.9000) =     13.444 ms/op
     p(99.9900) =     17.793 ms/op
     p(99.9990) =     18.350 ms/op
     p(99.9999) =     18.448 ms/op
    p(100.0000) =     18.448 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.828 ± 3.802  ops/ms
ClientGrpc.existUser                       thrpt       3  11.411 ± 5.966  ops/ms
ClientGrpc.getUser                         thrpt       3  10.778 ± 1.833  ops/ms
ClientGrpc.listUser                        thrpt       3   8.408 ± 2.108  ops/ms
ClientGrpc.createUser                       avgt       3   2.961 ± 0.634   ms/op
ClientGrpc.existUser                        avgt       3   2.811 ± 0.691   ms/op
ClientGrpc.getUser                          avgt       3   2.941 ± 0.362   ms/op
ClientGrpc.listUser                         avgt       3   3.804 ± 1.349   ms/op
ClientGrpc.createUser                     sample  322270   2.979 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.531           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.945           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.457           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.662           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.301           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.380           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.963           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          26.608           ms/op
ClientGrpc.existUser                      sample  339374   2.828 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.529           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.843           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.346           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.559           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.162           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.955           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.077           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          16.384           ms/op
ClientGrpc.getUser                        sample  328771   2.920 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.239           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.916           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.338           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.613           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.334           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.858           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          26.363           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          33.325           ms/op
ClientGrpc.listUser                       sample  249419   3.848 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.792           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.731           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.784           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.448           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.603           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.444           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          17.793           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          18.448           ms/op
