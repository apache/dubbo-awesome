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
# Warmup Iteration   1: 4.326 ops/ms
# Warmup Iteration   2: 9.685 ops/ms
# Warmup Iteration   3: 10.468 ops/ms
Iteration   1: 10.827 ops/ms
Iteration   2: 10.886 ops/ms
Iteration   3: 10.525 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.746 ±(99.9%) 3.537 ops/ms [Average]
  (min, avg, max) = (10.525, 10.746, 10.886), stdev = 0.194
  CI (99.9%): [7.209, 14.283] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 8.013 ops/ms
# Warmup Iteration   2: 10.999 ops/ms
# Warmup Iteration   3: 11.159 ops/ms
Iteration   1: 11.267 ops/ms
Iteration   2: 11.568 ops/ms
Iteration   3: 11.104 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.313 ±(99.9%) 4.296 ops/ms [Average]
  (min, avg, max) = (11.104, 11.313, 11.568), stdev = 0.236
  CI (99.9%): [7.016, 15.609] (assumes normal distribution)


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
# Warmup Iteration   1: 7.227 ops/ms
# Warmup Iteration   2: 10.415 ops/ms
# Warmup Iteration   3: 10.707 ops/ms
Iteration   1: 10.922 ops/ms
Iteration   2: 10.964 ops/ms
Iteration   3: 10.736 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.874 ±(99.9%) 2.221 ops/ms [Average]
  (min, avg, max) = (10.736, 10.874, 10.964), stdev = 0.122
  CI (99.9%): [8.653, 13.095] (assumes normal distribution)


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
# Warmup Iteration   1: 5.797 ops/ms
# Warmup Iteration   2: 8.069 ops/ms
# Warmup Iteration   3: 8.569 ops/ms
Iteration   1: 8.391 ops/ms
Iteration   2: 8.511 ops/ms
Iteration   3: 8.424 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.442 ±(99.9%) 1.127 ops/ms [Average]
  (min, avg, max) = (8.391, 8.442, 8.511), stdev = 0.062
  CI (99.9%): [7.315, 9.569] (assumes normal distribution)


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
# Warmup Iteration   1: 4.104 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.055 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.986 ±(99.9%) 0.012 ms/op
Iteration   1: 2.878 ±(99.9%) 0.003 ms/op
Iteration   2: 2.989 ±(99.9%) 0.002 ms/op
Iteration   3: 2.982 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.950 ±(99.9%) 1.128 ms/op [Average]
  (min, avg, max) = (2.878, 2.950, 2.989), stdev = 0.062
  CI (99.9%): [1.821, 4.078] (assumes normal distribution)


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
# Warmup Iteration   1: 3.780 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.985 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.850 ±(99.9%) 0.009 ms/op
Iteration   1: 2.866 ±(99.9%) 0.003 ms/op
Iteration   2: 2.825 ±(99.9%) 0.003 ms/op
Iteration   3: 2.888 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.859 ±(99.9%) 0.580 ms/op [Average]
  (min, avg, max) = (2.825, 2.859, 2.888), stdev = 0.032
  CI (99.9%): [2.279, 3.440] (assumes normal distribution)


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
# Warmup Iteration   1: 3.905 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.061 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.992 ±(99.9%) 0.003 ms/op
Iteration   1: 2.954 ±(99.9%) 0.003 ms/op
Iteration   2: 2.907 ±(99.9%) 0.003 ms/op
Iteration   3: 2.975 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.946 ±(99.9%) 0.634 ms/op [Average]
  (min, avg, max) = (2.907, 2.946, 2.975), stdev = 0.035
  CI (99.9%): [2.311, 3.580] (assumes normal distribution)


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
# Warmup Iteration   1: 4.187 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.995 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.841 ±(99.9%) 0.012 ms/op
Iteration   1: 3.724 ±(99.9%) 0.007 ms/op
Iteration   2: 3.750 ±(99.9%) 0.033 ms/op
Iteration   3: 3.810 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.761 ±(99.9%) 0.804 ms/op [Average]
  (min, avg, max) = (3.724, 3.761, 3.810), stdev = 0.044
  CI (99.9%): [2.958, 4.565] (assumes normal distribution)


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
# Warmup Iteration   1: 3.997 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.134 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.019 ±(99.9%) 0.007 ms/op
Iteration   1: 3.021 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.577 ms/op
                 createUser·p0.50:   2.998 ms/op
                 createUser·p0.90:   3.613 ms/op
                 createUser·p0.95:   3.764 ms/op
                 createUser·p0.99:   4.260 ms/op
                 createUser·p0.999:  7.276 ms/op
                 createUser·p0.9999: 12.433 ms/op
                 createUser·p1.00:   14.762 ms/op

Iteration   2: 2.930 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.730 ms/op
                 createUser·p0.50:   2.945 ms/op
                 createUser·p0.90:   3.457 ms/op
                 createUser·p0.95:   3.686 ms/op
                 createUser·p0.99:   4.530 ms/op
                 createUser·p0.999:  8.094 ms/op
                 createUser·p0.9999: 15.373 ms/op
                 createUser·p1.00:   15.778 ms/op

Iteration   3: 3.002 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.663 ms/op
                 createUser·p0.50:   2.970 ms/op
                 createUser·p0.90:   3.572 ms/op
                 createUser·p0.95:   3.764 ms/op
                 createUser·p0.99:   4.644 ms/op
                 createUser·p0.999:  9.650 ms/op
                 createUser·p0.9999: 26.771 ms/op
                 createUser·p1.00:   28.770 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 321633
  mean =      2.984 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 35674 
    [ 2.500,  5.000) = 284390 
    [ 5.000,  7.500) = 1108 
    [ 7.500, 10.000) = 212 
    [10.000, 12.500) = 113 
    [12.500, 15.000) = 83 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 27 

  Percentiles, ms/op:
      p(0.0000) =      0.577 ms/op
     p(50.0000) =      2.970 ms/op
     p(90.0000) =      3.555 ms/op
     p(95.0000) =      3.748 ms/op
     p(99.0000) =      4.489 ms/op
     p(99.9000) =      8.624 ms/op
     p(99.9900) =     24.427 ms/op
     p(99.9990) =     28.472 ms/op
     p(99.9999) =     28.770 ms/op
    p(100.0000) =     28.770 ms/op


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
# Warmup Iteration   1: 3.624 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 2.976 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.842 ±(99.9%) 0.006 ms/op
Iteration   1: 2.827 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.528 ms/op
                 existUser·p0.50:   2.822 ms/op
                 existUser·p0.90:   3.387 ms/op
                 existUser·p0.95:   3.633 ms/op
                 existUser·p0.99:   4.415 ms/op
                 existUser·p0.999:  7.321 ms/op
                 existUser·p0.9999: 12.602 ms/op
                 existUser·p1.00:   13.042 ms/op

Iteration   2: 2.872 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.593 ms/op
                 existUser·p0.50:   2.863 ms/op
                 existUser·p0.90:   3.383 ms/op
                 existUser·p0.95:   3.559 ms/op
                 existUser·p0.99:   4.329 ms/op
                 existUser·p0.999:  7.140 ms/op
                 existUser·p0.9999: 14.200 ms/op
                 existUser·p1.00:   14.418 ms/op

Iteration   3: 2.872 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.589 ms/op
                 existUser·p0.50:   2.847 ms/op
                 existUser·p0.90:   3.420 ms/op
                 existUser·p0.95:   3.633 ms/op
                 existUser·p0.99:   4.317 ms/op
                 existUser·p0.999:  9.604 ms/op
                 existUser·p0.9999: 18.346 ms/op
                 existUser·p1.00:   18.383 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 336094
  mean =      2.857 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3062 
    [ 1.250,  2.500) = 55924 
    [ 2.500,  3.750) = 265563 
    [ 3.750,  5.000) = 10481 
    [ 5.000,  6.250) = 516 
    [ 6.250,  7.500) = 227 
    [ 7.500,  8.750) = 68 
    [ 8.750, 10.000) = 55 
    [10.000, 11.250) = 51 
    [11.250, 12.500) = 40 
    [12.500, 13.750) = 23 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 19 
    [16.250, 17.500) = 14 
    [17.500, 18.750) = 19 

  Percentiles, ms/op:
      p(0.0000) =      0.528 ms/op
     p(50.0000) =      2.843 ms/op
     p(90.0000) =      3.400 ms/op
     p(95.0000) =      3.613 ms/op
     p(99.0000) =      4.358 ms/op
     p(99.9000) =      7.429 ms/op
     p(99.9900) =     16.192 ms/op
     p(99.9990) =     18.383 ms/op
     p(99.9999) =     18.383 ms/op
    p(100.0000) =     18.383 ms/op


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
# Warmup Iteration   1: 3.756 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.150 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.020 ±(99.9%) 0.007 ms/op
Iteration   1: 3.046 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.697 ms/op
                 getUser·p0.50:   3.031 ms/op
                 getUser·p0.90:   3.588 ms/op
                 getUser·p0.95:   3.805 ms/op
                 getUser·p0.99:   4.276 ms/op
                 getUser·p0.999:  9.733 ms/op
                 getUser·p0.9999: 12.100 ms/op
                 getUser·p1.00:   14.483 ms/op

Iteration   2: 2.989 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.568 ms/op
                 getUser·p0.50:   2.990 ms/op
                 getUser·p0.90:   3.596 ms/op
                 getUser·p0.95:   3.805 ms/op
                 getUser·p0.99:   4.252 ms/op
                 getUser·p0.999:  7.381 ms/op
                 getUser·p0.9999: 13.222 ms/op
                 getUser·p1.00:   13.418 ms/op

Iteration   3: 2.961 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.708 ms/op
                 getUser·p0.50:   2.949 ms/op
                 getUser·p0.90:   3.342 ms/op
                 getUser·p0.95:   3.568 ms/op
                 getUser·p0.99:   4.375 ms/op
                 getUser·p0.999:  7.707 ms/op
                 getUser·p0.9999: 24.609 ms/op
                 getUser·p1.00:   24.838 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 319865
  mean =      2.998 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24683 
    [ 2.500,  5.000) = 294030 
    [ 5.000,  7.500) = 798 
    [ 7.500, 10.000) = 126 
    [10.000, 12.500) = 130 
    [12.500, 15.000) = 52 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.568 ms/op
     p(50.0000) =      2.990 ms/op
     p(90.0000) =      3.523 ms/op
     p(95.0000) =      3.764 ms/op
     p(99.0000) =      4.301 ms/op
     p(99.9000) =      7.700 ms/op
     p(99.9900) =     23.824 ms/op
     p(99.9990) =     24.773 ms/op
     p(99.9999) =     24.838 ms/op
    p(100.0000) =     24.838 ms/op


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
# Warmup Iteration   1: 4.322 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 4.023 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.841 ±(99.9%) 0.009 ms/op
Iteration   1: 3.828 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.844 ms/op
                 listUser·p0.50:   3.707 ms/op
                 listUser·p0.90:   4.760 ms/op
                 listUser·p0.95:   5.562 ms/op
                 listUser·p0.99:   6.685 ms/op
                 listUser·p0.999:  12.482 ms/op
                 listUser·p0.9999: 17.409 ms/op
                 listUser·p1.00:   18.678 ms/op

Iteration   2: 3.828 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.057 ms/op
                 listUser·p0.50:   3.686 ms/op
                 listUser·p0.90:   4.792 ms/op
                 listUser·p0.95:   5.431 ms/op
                 listUser·p0.99:   6.693 ms/op
                 listUser·p0.999:  14.784 ms/op
                 listUser·p0.9999: 21.789 ms/op
                 listUser·p1.00:   22.381 ms/op

Iteration   3: 3.862 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.018 ms/op
                 listUser·p0.50:   3.703 ms/op
                 listUser·p0.90:   4.932 ms/op
                 listUser·p0.95:   5.480 ms/op
                 listUser·p0.99:   6.791 ms/op
                 listUser·p0.999:  15.380 ms/op
                 listUser·p0.9999: 23.747 ms/op
                 listUser·p1.00:   24.248 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 249929
  mean =      3.840 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6056 
    [ 2.500,  5.000) = 222684 
    [ 5.000,  7.500) = 20022 
    [ 7.500, 10.000) = 623 
    [10.000, 12.500) = 160 
    [12.500, 15.000) = 175 
    [15.000, 17.500) = 108 
    [17.500, 20.000) = 37 
    [20.000, 22.500) = 45 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.844 ms/op
     p(50.0000) =      3.699 ms/op
     p(90.0000) =      4.841 ms/op
     p(95.0000) =      5.489 ms/op
     p(99.0000) =      6.717 ms/op
     p(99.9000) =     14.108 ms/op
     p(99.9900) =     22.282 ms/op
     p(99.9990) =     24.150 ms/op
     p(99.9999) =     24.248 ms/op
    p(100.0000) =     24.248 ms/op


# Run complete. Total time: 00:13:02

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.746 ± 3.537  ops/ms
ClientGrpc.existUser                       thrpt       3  11.313 ± 4.296  ops/ms
ClientGrpc.getUser                         thrpt       3  10.874 ± 2.221  ops/ms
ClientGrpc.listUser                        thrpt       3   8.442 ± 1.127  ops/ms
ClientGrpc.createUser                       avgt       3   2.950 ± 1.128   ms/op
ClientGrpc.existUser                        avgt       3   2.859 ± 0.580   ms/op
ClientGrpc.getUser                          avgt       3   2.946 ± 0.634   ms/op
ClientGrpc.listUser                         avgt       3   3.761 ± 0.804   ms/op
ClientGrpc.createUser                     sample  321633   2.984 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.577           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.970           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.555           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.748           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.489           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.624           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          24.427           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          28.770           ms/op
ClientGrpc.existUser                      sample  336094   2.857 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.528           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.843           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.400           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.613           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.358           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.429           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.192           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.383           ms/op
ClientGrpc.getUser                        sample  319865   2.998 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.568           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.990           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.523           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.764           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.301           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.700           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          23.824           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          24.838           ms/op
ClientGrpc.listUser                       sample  249929   3.840 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.844           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.699           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.841           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.489           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.717           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.108           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.282           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.248           ms/op
