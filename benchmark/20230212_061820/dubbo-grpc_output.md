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
# Warmup Iteration   1: 4.922 ops/ms
# Warmup Iteration   2: 9.335 ops/ms
# Warmup Iteration   3: 10.721 ops/ms
Iteration   1: 10.333 ops/ms
Iteration   2: 10.668 ops/ms
Iteration   3: 10.340 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.447 ±(99.9%) 3.500 ops/ms [Average]
  (min, avg, max) = (10.333, 10.447, 10.668), stdev = 0.192
  CI (99.9%): [6.947, 13.947] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.901 ops/ms
# Warmup Iteration   2: 10.883 ops/ms
# Warmup Iteration   3: 11.176 ops/ms
Iteration   1: 10.845 ops/ms
Iteration   2: 10.741 ops/ms
Iteration   3: 10.712 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.766 ±(99.9%) 1.276 ops/ms [Average]
  (min, avg, max) = (10.712, 10.766, 10.845), stdev = 0.070
  CI (99.9%): [9.490, 12.042] (assumes normal distribution)


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
# Warmup Iteration   1: 7.482 ops/ms
# Warmup Iteration   2: 10.414 ops/ms
# Warmup Iteration   3: 10.235 ops/ms
Iteration   1: 10.330 ops/ms
Iteration   2: 10.442 ops/ms
Iteration   3: 10.466 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.413 ±(99.9%) 1.317 ops/ms [Average]
  (min, avg, max) = (10.330, 10.413, 10.466), stdev = 0.072
  CI (99.9%): [9.095, 11.730] (assumes normal distribution)


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
# Warmup Iteration   1: 5.648 ops/ms
# Warmup Iteration   2: 7.634 ops/ms
# Warmup Iteration   3: 8.102 ops/ms
Iteration   1: 8.046 ops/ms
Iteration   2: 8.075 ops/ms
Iteration   3: 7.934 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.018 ±(99.9%) 1.352 ops/ms [Average]
  (min, avg, max) = (7.934, 8.018, 8.075), stdev = 0.074
  CI (99.9%): [6.666, 9.371] (assumes normal distribution)


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
# Warmup Iteration   1: 3.882 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.172 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.016 ±(99.9%) 0.008 ms/op
Iteration   1: 3.093 ±(99.9%) 0.002 ms/op
Iteration   2: 3.061 ±(99.9%) 0.003 ms/op
Iteration   3: 3.080 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.078 ±(99.9%) 0.298 ms/op [Average]
  (min, avg, max) = (3.061, 3.078, 3.093), stdev = 0.016
  CI (99.9%): [2.780, 3.376] (assumes normal distribution)


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
# Warmup Iteration   1: 3.828 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.021 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.902 ±(99.9%) 0.003 ms/op
Iteration   1: 2.876 ±(99.9%) 0.002 ms/op
Iteration   2: 2.997 ±(99.9%) 0.001 ms/op
Iteration   3: 2.970 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.948 ±(99.9%) 1.158 ms/op [Average]
  (min, avg, max) = (2.876, 2.948, 2.997), stdev = 0.063
  CI (99.9%): [1.790, 4.106] (assumes normal distribution)


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
# Warmup Iteration   1: 3.769 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.100 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.004 ±(99.9%) 0.003 ms/op
Iteration   1: 2.988 ±(99.9%) 0.002 ms/op
Iteration   2: 2.953 ±(99.9%) 0.004 ms/op
Iteration   3: 3.036 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.992 ±(99.9%) 0.759 ms/op [Average]
  (min, avg, max) = (2.953, 2.992, 3.036), stdev = 0.042
  CI (99.9%): [2.233, 3.752] (assumes normal distribution)


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
# Warmup Iteration   1: 4.218 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 4.254 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 4.015 ±(99.9%) 0.009 ms/op
Iteration   1: 3.989 ±(99.9%) 0.011 ms/op
Iteration   2: 3.970 ±(99.9%) 0.006 ms/op
Iteration   3: 3.969 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.976 ±(99.9%) 0.206 ms/op [Average]
  (min, avg, max) = (3.969, 3.976, 3.989), stdev = 0.011
  CI (99.9%): [3.770, 4.182] (assumes normal distribution)


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
# Warmup Iteration   1: 4.005 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.090 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.122 ±(99.9%) 0.006 ms/op
Iteration   1: 3.168 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.721 ms/op
                 createUser·p0.50:   3.174 ms/op
                 createUser·p0.90:   3.932 ms/op
                 createUser·p0.95:   4.100 ms/op
                 createUser·p0.99:   4.448 ms/op
                 createUser·p0.999:  9.455 ms/op
                 createUser·p0.9999: 13.071 ms/op
                 createUser·p1.00:   13.517 ms/op

Iteration   2: 3.169 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.829 ms/op
                 createUser·p0.50:   3.166 ms/op
                 createUser·p0.90:   3.899 ms/op
                 createUser·p0.95:   4.051 ms/op
                 createUser·p0.99:   4.309 ms/op
                 createUser·p0.999:  7.072 ms/op
                 createUser·p0.9999: 12.894 ms/op
                 createUser·p1.00:   13.222 ms/op

Iteration   3: 3.110 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.746 ms/op
                 createUser·p0.50:   3.105 ms/op
                 createUser·p0.90:   3.813 ms/op
                 createUser·p0.95:   3.981 ms/op
                 createUser·p0.99:   4.252 ms/op
                 createUser·p0.999:  6.318 ms/op
                 createUser·p0.9999: 18.275 ms/op
                 createUser·p1.00:   19.988 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 304722
  mean =      3.149 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1299 
    [ 1.250,  2.500) = 30555 
    [ 2.500,  3.750) = 226048 
    [ 3.750,  5.000) = 45946 
    [ 5.000,  6.250) = 359 
    [ 6.250,  7.500) = 146 
    [ 7.500,  8.750) = 92 
    [ 8.750, 10.000) = 55 
    [10.000, 11.250) = 61 
    [11.250, 12.500) = 43 
    [12.500, 13.750) = 56 
    [13.750, 15.000) = 10 
    [15.000, 16.250) = 20 
    [16.250, 17.500) = 7 
    [17.500, 18.750) = 19 

  Percentiles, ms/op:
      p(0.0000) =      0.721 ms/op
     p(50.0000) =      3.146 ms/op
     p(90.0000) =      3.883 ms/op
     p(95.0000) =      4.047 ms/op
     p(99.0000) =      4.342 ms/op
     p(99.9000) =      8.235 ms/op
     p(99.9900) =     17.286 ms/op
     p(99.9990) =     19.784 ms/op
     p(99.9999) =     19.988 ms/op
    p(100.0000) =     19.988 ms/op


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
# Warmup Iteration   1: 3.467 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 2.970 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.895 ±(99.9%) 0.006 ms/op
Iteration   1: 2.968 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.673 ms/op
                 existUser·p0.50:   2.945 ms/op
                 existUser·p0.90:   3.604 ms/op
                 existUser·p0.95:   3.801 ms/op
                 existUser·p0.99:   4.096 ms/op
                 existUser·p0.999:  6.205 ms/op
                 existUser·p0.9999: 11.682 ms/op
                 existUser·p1.00:   11.960 ms/op

Iteration   2: 2.932 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.706 ms/op
                 existUser·p0.50:   2.945 ms/op
                 existUser·p0.90:   3.572 ms/op
                 existUser·p0.95:   3.760 ms/op
                 existUser·p0.99:   4.166 ms/op
                 existUser·p0.999:  9.534 ms/op
                 existUser·p0.9999: 15.270 ms/op
                 existUser·p1.00:   15.745 ms/op

Iteration   3: 2.916 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.601 ms/op
                 existUser·p0.50:   2.933 ms/op
                 existUser·p0.90:   3.453 ms/op
                 existUser·p0.95:   3.641 ms/op
                 existUser·p0.99:   4.063 ms/op
                 existUser·p0.999:  5.635 ms/op
                 existUser·p0.9999: 25.461 ms/op
                 existUser·p1.00:   25.985 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 326697
  mean =      2.939 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 47793 
    [ 2.500,  5.000) = 278160 
    [ 5.000,  7.500) = 487 
    [ 7.500, 10.000) = 33 
    [10.000, 12.500) = 128 
    [12.500, 15.000) = 15 
    [15.000, 17.500) = 49 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 19 

  Percentiles, ms/op:
      p(0.0000) =      0.601 ms/op
     p(50.0000) =      2.941 ms/op
     p(90.0000) =      3.543 ms/op
     p(95.0000) =      3.744 ms/op
     p(99.0000) =      4.108 ms/op
     p(99.9000) =      6.488 ms/op
     p(99.9900) =     18.688 ms/op
     p(99.9990) =     25.756 ms/op
     p(99.9999) =     25.985 ms/op
    p(100.0000) =     25.985 ms/op


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
# Warmup Iteration   1: 4.012 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.112 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.111 ±(99.9%) 0.006 ms/op
Iteration   1: 3.071 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.622 ms/op
                 getUser·p0.50:   3.068 ms/op
                 getUser·p0.90:   3.674 ms/op
                 getUser·p0.95:   3.842 ms/op
                 getUser·p0.99:   4.149 ms/op
                 getUser·p0.999:  5.952 ms/op
                 getUser·p0.9999: 14.316 ms/op
                 getUser·p1.00:   14.615 ms/op

Iteration   2: 3.045 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.730 ms/op
                 getUser·p0.50:   3.047 ms/op
                 getUser·p0.90:   3.609 ms/op
                 getUser·p0.95:   3.793 ms/op
                 getUser·p0.99:   4.166 ms/op
                 getUser·p0.999:  5.998 ms/op
                 getUser·p0.9999: 12.657 ms/op
                 getUser·p1.00:   13.009 ms/op

Iteration   3: 3.033 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.518 ms/op
                 getUser·p0.50:   3.039 ms/op
                 getUser·p0.90:   3.617 ms/op
                 getUser·p0.95:   3.777 ms/op
                 getUser·p0.99:   4.162 ms/op
                 getUser·p0.999:  6.660 ms/op
                 getUser·p0.9999: 23.608 ms/op
                 getUser·p1.00:   24.183 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 314632
  mean =      3.050 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27920 
    [ 2.500,  5.000) = 285974 
    [ 5.000,  7.500) = 563 
    [ 7.500, 10.000) = 15 
    [10.000, 12.500) = 35 
    [12.500, 15.000) = 61 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.518 ms/op
     p(50.0000) =      3.052 ms/op
     p(90.0000) =      3.637 ms/op
     p(95.0000) =      3.805 ms/op
     p(99.0000) =      4.162 ms/op
     p(99.9000) =      6.106 ms/op
     p(99.9900) =     22.958 ms/op
     p(99.9990) =     23.780 ms/op
     p(99.9999) =     24.183 ms/op
    p(100.0000) =     24.183 ms/op


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
# Warmup Iteration   1: 4.967 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 4.085 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.986 ±(99.9%) 0.010 ms/op
Iteration   1: 3.899 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.098 ms/op
                 listUser·p0.50:   3.772 ms/op
                 listUser·p0.90:   4.989 ms/op
                 listUser·p0.95:   5.489 ms/op
                 listUser·p0.99:   6.758 ms/op
                 listUser·p0.999:  12.905 ms/op
                 listUser·p0.9999: 18.441 ms/op
                 listUser·p1.00:   18.809 ms/op

Iteration   2: 3.951 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.169 ms/op
                 listUser·p0.50:   3.797 ms/op
                 listUser·p0.90:   4.973 ms/op
                 listUser·p0.95:   5.759 ms/op
                 listUser·p0.99:   6.742 ms/op
                 listUser·p0.999:  14.844 ms/op
                 listUser·p0.9999: 22.401 ms/op
                 listUser·p1.00:   23.101 ms/op

Iteration   3: 3.864 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.198 ms/op
                 listUser·p0.50:   3.748 ms/op
                 listUser·p0.90:   4.448 ms/op
                 listUser·p0.95:   5.251 ms/op
                 listUser·p0.99:   6.545 ms/op
                 listUser·p0.999:  14.434 ms/op
                 listUser·p0.9999: 24.347 ms/op
                 listUser·p1.00:   24.510 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 245870
  mean =      3.904 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5051 
    [ 2.500,  5.000) = 219900 
    [ 5.000,  7.500) = 19875 
    [ 7.500, 10.000) = 595 
    [10.000, 12.500) = 112 
    [12.500, 15.000) = 164 
    [15.000, 17.500) = 66 
    [17.500, 20.000) = 48 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 39 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.098 ms/op
     p(50.0000) =      3.772 ms/op
     p(90.0000) =      4.874 ms/op
     p(95.0000) =      5.525 ms/op
     p(99.0000) =      6.676 ms/op
     p(99.9000) =     14.144 ms/op
     p(99.9900) =     23.738 ms/op
     p(99.9990) =     24.463 ms/op
     p(99.9999) =     24.510 ms/op
    p(100.0000) =     24.510 ms/op


# Run complete. Total time: 00:13:02

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.447 ± 3.500  ops/ms
ClientGrpc.existUser                       thrpt       3  10.766 ± 1.276  ops/ms
ClientGrpc.getUser                         thrpt       3  10.413 ± 1.317  ops/ms
ClientGrpc.listUser                        thrpt       3   8.018 ± 1.352  ops/ms
ClientGrpc.createUser                       avgt       3   3.078 ± 0.298   ms/op
ClientGrpc.existUser                        avgt       3   2.948 ± 1.158   ms/op
ClientGrpc.getUser                          avgt       3   2.992 ± 0.759   ms/op
ClientGrpc.listUser                         avgt       3   3.976 ± 0.206   ms/op
ClientGrpc.createUser                     sample  304722   3.149 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.721           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.146           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.883           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.047           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.342           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.235           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.286           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          19.988           ms/op
ClientGrpc.existUser                      sample  326697   2.939 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.601           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.941           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.543           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.744           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.108           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.488           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.688           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          25.985           ms/op
ClientGrpc.getUser                        sample  314632   3.050 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.518           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.052           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.637           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.805           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.162           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.106           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          22.958           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          24.183           ms/op
ClientGrpc.listUser                       sample  245870   3.904 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.098           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.772           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.874           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.525           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.676           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.144           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.738           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.510           ms/op
