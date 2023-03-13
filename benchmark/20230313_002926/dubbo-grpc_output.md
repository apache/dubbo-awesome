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
# Warmup Iteration   1: 4.668 ops/ms
# Warmup Iteration   2: 9.408 ops/ms
# Warmup Iteration   3: 10.373 ops/ms
Iteration   1: 10.657 ops/ms
Iteration   2: 10.695 ops/ms
Iteration   3: 10.770 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.707 ±(99.9%) 1.057 ops/ms [Average]
  (min, avg, max) = (10.657, 10.707, 10.770), stdev = 0.058
  CI (99.9%): [9.651, 11.764] (assumes normal distribution)


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
# Warmup Iteration   1: 8.149 ops/ms
# Warmup Iteration   2: 10.991 ops/ms
# Warmup Iteration   3: 11.728 ops/ms
Iteration   1: 11.352 ops/ms
Iteration   2: 11.284 ops/ms
Iteration   3: 11.395 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.344 ±(99.9%) 1.021 ops/ms [Average]
  (min, avg, max) = (11.284, 11.344, 11.395), stdev = 0.056
  CI (99.9%): [10.323, 12.365] (assumes normal distribution)


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
# Warmup Iteration   1: 8.611 ops/ms
# Warmup Iteration   2: 10.599 ops/ms
# Warmup Iteration   3: 10.678 ops/ms
Iteration   1: 10.769 ops/ms
Iteration   2: 10.719 ops/ms
Iteration   3: 10.779 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.755 ±(99.9%) 0.592 ops/ms [Average]
  (min, avg, max) = (10.719, 10.755, 10.779), stdev = 0.032
  CI (99.9%): [10.164, 11.347] (assumes normal distribution)


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
# Warmup Iteration   1: 5.713 ops/ms
# Warmup Iteration   2: 8.262 ops/ms
# Warmup Iteration   3: 8.245 ops/ms
Iteration   1: 8.296 ops/ms
Iteration   2: 8.353 ops/ms
Iteration   3: 8.477 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.375 ±(99.9%) 1.688 ops/ms [Average]
  (min, avg, max) = (8.296, 8.375, 8.477), stdev = 0.093
  CI (99.9%): [6.687, 10.063] (assumes normal distribution)


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
# Warmup Iteration   1: 3.872 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.073 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.988 ±(99.9%) 0.002 ms/op
Iteration   1: 2.917 ±(99.9%) 0.004 ms/op
Iteration   2: 2.949 ±(99.9%) 0.002 ms/op
Iteration   3: 2.938 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.935 ±(99.9%) 0.296 ms/op [Average]
  (min, avg, max) = (2.917, 2.935, 2.949), stdev = 0.016
  CI (99.9%): [2.639, 3.231] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.724 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.939 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.790 ±(99.9%) 0.003 ms/op
Iteration   1: 2.819 ±(99.9%) 0.004 ms/op
Iteration   2: 2.850 ±(99.9%) 0.002 ms/op
Iteration   3: 2.801 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.823 ±(99.9%) 0.459 ms/op [Average]
  (min, avg, max) = (2.801, 2.823, 2.850), stdev = 0.025
  CI (99.9%): [2.364, 3.283] (assumes normal distribution)


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
# Warmup Iteration   1: 4.039 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.983 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.992 ±(99.9%) 0.003 ms/op
Iteration   1: 2.963 ±(99.9%) 0.003 ms/op
Iteration   2: 2.969 ±(99.9%) 0.002 ms/op
Iteration   3: 2.966 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.966 ±(99.9%) 0.060 ms/op [Average]
  (min, avg, max) = (2.963, 2.966, 2.969), stdev = 0.003
  CI (99.9%): [2.906, 3.026] (assumes normal distribution)


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
# Warmup Iteration   1: 5.361 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.922 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.922 ±(99.9%) 0.010 ms/op
Iteration   1: 3.862 ±(99.9%) 0.022 ms/op
Iteration   2: 3.862 ±(99.9%) 0.015 ms/op
Iteration   3: 3.831 ±(99.9%) 0.031 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.852 ±(99.9%) 0.324 ms/op [Average]
  (min, avg, max) = (3.831, 3.852, 3.862), stdev = 0.018
  CI (99.9%): [3.528, 4.175] (assumes normal distribution)


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
# Warmup Iteration   1: 4.117 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.179 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.061 ±(99.9%) 0.007 ms/op
Iteration   1: 2.997 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.706 ms/op
                 createUser·p0.50:   2.990 ms/op
                 createUser·p0.90:   3.539 ms/op
                 createUser·p0.95:   3.777 ms/op
                 createUser·p0.99:   4.497 ms/op
                 createUser·p0.999:  8.143 ms/op
                 createUser·p0.9999: 14.893 ms/op
                 createUser·p1.00:   16.187 ms/op

Iteration   2: 3.000 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.257 ms/op
                 createUser·p0.50:   2.990 ms/op
                 createUser·p0.90:   3.506 ms/op
                 createUser·p0.95:   3.744 ms/op
                 createUser·p0.99:   4.299 ms/op
                 createUser·p0.999:  6.142 ms/op
                 createUser·p0.9999: 19.038 ms/op
                 createUser·p1.00:   19.366 ms/op

Iteration   3: 3.008 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.627 ms/op
                 createUser·p0.50:   2.970 ms/op
                 createUser·p0.90:   3.494 ms/op
                 createUser·p0.95:   3.748 ms/op
                 createUser·p0.99:   4.522 ms/op
                 createUser·p0.999:  11.201 ms/op
                 createUser·p0.9999: 16.269 ms/op
                 createUser·p1.00:   16.630 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 319711
  mean =      3.002 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1425 
    [ 1.250,  2.500) = 25446 
    [ 2.500,  3.750) = 276534 
    [ 3.750,  5.000) = 15028 
    [ 5.000,  6.250) = 683 
    [ 6.250,  7.500) = 188 
    [ 7.500,  8.750) = 100 
    [ 8.750, 10.000) = 23 
    [10.000, 11.250) = 90 
    [11.250, 12.500) = 37 
    [12.500, 13.750) = 29 
    [13.750, 15.000) = 56 
    [15.000, 16.250) = 27 
    [16.250, 17.500) = 13 
    [17.500, 18.750) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.257 ms/op
     p(50.0000) =      2.982 ms/op
     p(90.0000) =      3.514 ms/op
     p(95.0000) =      3.756 ms/op
     p(99.0000) =      4.424 ms/op
     p(99.9000) =      8.557 ms/op
     p(99.9900) =     18.351 ms/op
     p(99.9990) =     19.255 ms/op
     p(99.9999) =     19.366 ms/op
    p(100.0000) =     19.366 ms/op


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
# Warmup Iteration   1: 3.564 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 2.978 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.828 ±(99.9%) 0.006 ms/op
Iteration   1: 2.840 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.530 ms/op
                 existUser·p0.50:   2.834 ms/op
                 existUser·p0.90:   3.305 ms/op
                 existUser·p0.95:   3.600 ms/op
                 existUser·p0.99:   4.481 ms/op
                 existUser·p0.999:  8.639 ms/op
                 existUser·p0.9999: 11.633 ms/op
                 existUser·p1.00:   11.944 ms/op

Iteration   2: 2.856 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.520 ms/op
                 existUser·p0.50:   2.843 ms/op
                 existUser·p0.90:   3.416 ms/op
                 existUser·p0.95:   3.650 ms/op
                 existUser·p0.99:   4.530 ms/op
                 existUser·p0.999:  7.086 ms/op
                 existUser·p0.9999: 24.471 ms/op
                 existUser·p1.00:   25.756 ms/op

Iteration   3: 2.889 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.552 ms/op
                 existUser·p0.50:   2.863 ms/op
                 existUser·p0.90:   3.432 ms/op
                 existUser·p0.95:   3.654 ms/op
                 existUser·p0.99:   4.497 ms/op
                 existUser·p0.999:  6.390 ms/op
                 existUser·p0.9999: 18.938 ms/op
                 existUser·p1.00:   19.005 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 335391
  mean =      2.861 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 56028 
    [ 2.500,  5.000) = 278096 
    [ 5.000,  7.500) = 932 
    [ 7.500, 10.000) = 86 
    [10.000, 12.500) = 154 
    [12.500, 15.000) = 30 
    [15.000, 17.500) = 11 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.520 ms/op
     p(50.0000) =      2.847 ms/op
     p(90.0000) =      3.396 ms/op
     p(95.0000) =      3.637 ms/op
     p(99.0000) =      4.497 ms/op
     p(99.9000) =      7.502 ms/op
     p(99.9900) =     19.005 ms/op
     p(99.9990) =     25.690 ms/op
     p(99.9999) =     25.756 ms/op
    p(100.0000) =     25.756 ms/op


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
# Warmup Iteration   1: 3.864 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.051 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.986 ±(99.9%) 0.006 ms/op
Iteration   1: 3.005 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.687 ms/op
                 getUser·p0.50:   2.990 ms/op
                 getUser·p0.90:   3.420 ms/op
                 getUser·p0.95:   3.645 ms/op
                 getUser·p0.99:   4.334 ms/op
                 getUser·p0.999:  7.177 ms/op
                 getUser·p0.9999: 17.379 ms/op
                 getUser·p1.00:   17.596 ms/op

Iteration   2: 2.984 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.778 ms/op
                 getUser·p0.50:   2.978 ms/op
                 getUser·p0.90:   3.461 ms/op
                 getUser·p0.95:   3.617 ms/op
                 getUser·p0.99:   4.268 ms/op
                 getUser·p0.999:  6.757 ms/op
                 getUser·p0.9999: 13.231 ms/op
                 getUser·p1.00:   13.468 ms/op

Iteration   3: 2.969 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.736 ms/op
                 getUser·p0.50:   2.957 ms/op
                 getUser·p0.90:   3.346 ms/op
                 getUser·p0.95:   3.510 ms/op
                 getUser·p0.99:   4.162 ms/op
                 getUser·p0.999:  6.692 ms/op
                 getUser·p0.9999: 15.650 ms/op
                 getUser·p1.00:   16.482 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 321288
  mean =      2.986 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1326 
    [ 1.250,  2.500) = 17466 
    [ 2.500,  3.750) = 292456 
    [ 3.750,  5.000) = 8752 
    [ 5.000,  6.250) = 820 
    [ 6.250,  7.500) = 262 
    [ 7.500,  8.750) = 33 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 5 
    [11.250, 12.500) = 50 
    [12.500, 13.750) = 54 
    [13.750, 15.000) = 8 
    [15.000, 16.250) = 20 
    [16.250, 17.500) = 32 
    [17.500, 18.750) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.687 ms/op
     p(50.0000) =      2.974 ms/op
     p(90.0000) =      3.408 ms/op
     p(95.0000) =      3.592 ms/op
     p(99.0000) =      4.252 ms/op
     p(99.9000) =      6.783 ms/op
     p(99.9900) =     16.853 ms/op
     p(99.9990) =     17.531 ms/op
     p(99.9999) =     17.596 ms/op
    p(100.0000) =     17.596 ms/op


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
# Warmup Iteration   1: 4.796 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.950 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.845 ±(99.9%) 0.011 ms/op
Iteration   1: 3.863 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.092 ms/op
                 listUser·p0.50:   3.711 ms/op
                 listUser·p0.90:   4.817 ms/op
                 listUser·p0.95:   5.554 ms/op
                 listUser·p0.99:   6.701 ms/op
                 listUser·p0.999:  16.279 ms/op
                 listUser·p0.9999: 20.513 ms/op
                 listUser·p1.00:   21.758 ms/op

Iteration   2: 3.854 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.903 ms/op
                 listUser·p0.50:   3.744 ms/op
                 listUser·p0.90:   4.555 ms/op
                 listUser·p0.95:   5.415 ms/op
                 listUser·p0.99:   6.496 ms/op
                 listUser·p0.999:  14.344 ms/op
                 listUser·p0.9999: 18.186 ms/op
                 listUser·p1.00:   21.922 ms/op

Iteration   3: 3.853 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.878 ms/op
                 listUser·p0.50:   3.703 ms/op
                 listUser·p0.90:   4.866 ms/op
                 listUser·p0.95:   5.448 ms/op
                 listUser·p0.99:   6.791 ms/op
                 listUser·p0.999:  18.285 ms/op
                 listUser·p0.9999: 23.649 ms/op
                 listUser·p1.00:   24.609 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 248851
  mean =      3.857 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5511 
    [ 2.500,  5.000) = 224123 
    [ 5.000,  7.500) = 18120 
    [ 7.500, 10.000) = 579 
    [10.000, 12.500) = 61 
    [12.500, 15.000) = 183 
    [15.000, 17.500) = 108 
    [17.500, 20.000) = 109 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.878 ms/op
     p(50.0000) =      3.719 ms/op
     p(90.0000) =      4.768 ms/op
     p(95.0000) =      5.480 ms/op
     p(99.0000) =      6.664 ms/op
     p(99.9000) =     16.059 ms/op
     p(99.9900) =     23.200 ms/op
     p(99.9990) =     24.332 ms/op
     p(99.9999) =     24.609 ms/op
    p(100.0000) =     24.609 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.707 ± 1.057  ops/ms
ClientGrpc.existUser                       thrpt       3  11.344 ± 1.021  ops/ms
ClientGrpc.getUser                         thrpt       3  10.755 ± 0.592  ops/ms
ClientGrpc.listUser                        thrpt       3   8.375 ± 1.688  ops/ms
ClientGrpc.createUser                       avgt       3   2.935 ± 0.296   ms/op
ClientGrpc.existUser                        avgt       3   2.823 ± 0.459   ms/op
ClientGrpc.getUser                          avgt       3   2.966 ± 0.060   ms/op
ClientGrpc.listUser                         avgt       3   3.852 ± 0.324   ms/op
ClientGrpc.createUser                     sample  319711   3.002 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.257           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.982           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.514           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.756           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.424           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.557           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.351           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          19.366           ms/op
ClientGrpc.existUser                      sample  335391   2.861 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.520           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.847           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.396           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.637           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.497           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.502           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.005           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          25.756           ms/op
ClientGrpc.getUser                        sample  321288   2.986 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.687           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.974           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.408           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.592           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.252           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.783           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.853           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          17.596           ms/op
ClientGrpc.listUser                       sample  248851   3.857 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.878           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.719           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.768           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.480           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.664           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.059           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.200           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.609           ms/op
