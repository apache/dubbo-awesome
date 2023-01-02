# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.366 ops/ms
# Warmup Iteration   2: 9.459 ops/ms
# Warmup Iteration   3: 10.561 ops/ms
Iteration   1: 10.666 ops/ms
Iteration   2: 10.270 ops/ms
Iteration   3: 10.361 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.432 ±(99.9%) 3.780 ops/ms [Average]
  (min, avg, max) = (10.270, 10.432, 10.666), stdev = 0.207
  CI (99.9%): [6.652, 14.213] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.812 ops/ms
# Warmup Iteration   2: 10.785 ops/ms
# Warmup Iteration   3: 10.877 ops/ms
Iteration   1: 10.727 ops/ms
Iteration   2: 10.842 ops/ms
Iteration   3: 10.912 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.827 ±(99.9%) 1.703 ops/ms [Average]
  (min, avg, max) = (10.727, 10.827, 10.912), stdev = 0.093
  CI (99.9%): [9.124, 12.530] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.570 ops/ms
# Warmup Iteration   2: 10.189 ops/ms
# Warmup Iteration   3: 10.486 ops/ms
Iteration   1: 10.522 ops/ms
Iteration   2: 10.488 ops/ms
Iteration   3: 10.481 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.497 ±(99.9%) 0.398 ops/ms [Average]
  (min, avg, max) = (10.481, 10.497, 10.522), stdev = 0.022
  CI (99.9%): [10.099, 10.895] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.189 ops/ms
# Warmup Iteration   2: 7.672 ops/ms
# Warmup Iteration   3: 7.866 ops/ms
Iteration   1: 7.867 ops/ms
Iteration   2: 7.941 ops/ms
Iteration   3: 7.960 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.923 ±(99.9%) 0.899 ops/ms [Average]
  (min, avg, max) = (7.867, 7.923, 7.960), stdev = 0.049
  CI (99.9%): [7.024, 8.822] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.025 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.148 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.017 ±(99.9%) 0.003 ms/op
Iteration   1: 3.113 ±(99.9%) 0.002 ms/op
Iteration   2: 2.955 ±(99.9%) 0.002 ms/op
Iteration   3: 3.116 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.061 ±(99.9%) 1.672 ms/op [Average]
  (min, avg, max) = (2.955, 3.061, 3.116), stdev = 0.092
  CI (99.9%): [1.390, 4.733] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.730 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.989 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.943 ±(99.9%) 0.002 ms/op
Iteration   1: 2.995 ±(99.9%) 0.003 ms/op
Iteration   2: 2.872 ±(99.9%) 0.002 ms/op
Iteration   3: 2.951 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.939 ±(99.9%) 1.137 ms/op [Average]
  (min, avg, max) = (2.872, 2.939, 2.995), stdev = 0.062
  CI (99.9%): [1.802, 4.076] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.867 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.100 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.017 ±(99.9%) 0.002 ms/op
Iteration   1: 3.061 ±(99.9%) 0.003 ms/op
Iteration   2: 2.950 ±(99.9%) 0.003 ms/op
Iteration   3: 3.013 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.008 ±(99.9%) 1.015 ms/op [Average]
  (min, avg, max) = (2.950, 3.008, 3.061), stdev = 0.056
  CI (99.9%): [1.993, 4.023] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 5.060 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 4.141 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.991 ±(99.9%) 0.037 ms/op
Iteration   1: 4.063 ±(99.9%) 0.020 ms/op
Iteration   2: 3.966 ±(99.9%) 0.035 ms/op
Iteration   3: 3.936 ±(99.9%) 0.038 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.988 ±(99.9%) 1.205 ms/op [Average]
  (min, avg, max) = (3.936, 3.988, 4.063), stdev = 0.066
  CI (99.9%): [2.783, 5.194] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.044 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.084 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.032 ±(99.9%) 0.007 ms/op
Iteration   1: 2.993 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.531 ms/op
                 createUser·p0.50:   3.006 ms/op
                 createUser·p0.90:   3.523 ms/op
                 createUser·p0.95:   3.690 ms/op
                 createUser·p0.99:   4.211 ms/op
                 createUser·p0.999:  7.438 ms/op
                 createUser·p0.9999: 16.797 ms/op
                 createUser·p1.00:   17.302 ms/op

Iteration   2: 3.108 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.851 ms/op
                 createUser·p0.50:   3.092 ms/op
                 createUser·p0.90:   3.838 ms/op
                 createUser·p0.95:   4.014 ms/op
                 createUser·p0.99:   4.358 ms/op
                 createUser·p0.999:  7.678 ms/op
                 createUser·p0.9999: 15.429 ms/op
                 createUser·p1.00:   15.811 ms/op

Iteration   3: 3.106 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.753 ms/op
                 createUser·p0.50:   3.080 ms/op
                 createUser·p0.90:   3.777 ms/op
                 createUser·p0.95:   3.944 ms/op
                 createUser·p0.99:   4.260 ms/op
                 createUser·p0.999:  9.470 ms/op
                 createUser·p0.9999: 16.495 ms/op
                 createUser·p1.00:   18.678 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 312975
  mean =      3.068 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1569 
    [ 1.250,  2.500) = 30563 
    [ 2.500,  3.750) = 252137 
    [ 3.750,  5.000) = 27696 
    [ 5.000,  6.250) = 548 
    [ 6.250,  7.500) = 117 
    [ 7.500,  8.750) = 57 
    [ 8.750, 10.000) = 64 
    [10.000, 11.250) = 5 
    [11.250, 12.500) = 38 
    [12.500, 13.750) = 47 
    [13.750, 15.000) = 45 
    [15.000, 16.250) = 51 
    [16.250, 17.500) = 33 
    [17.500, 18.750) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.531 ms/op
     p(50.0000) =      3.052 ms/op
     p(90.0000) =      3.723 ms/op
     p(95.0000) =      3.916 ms/op
     p(99.0000) =      4.293 ms/op
     p(99.9000) =      7.946 ms/op
     p(99.9900) =     16.423 ms/op
     p(99.9990) =     18.604 ms/op
     p(99.9999) =     18.678 ms/op
    p(100.0000) =     18.678 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.823 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.064 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.047 ±(99.9%) 0.006 ms/op
Iteration   1: 2.984 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.726 ms/op
                 existUser·p0.50:   2.986 ms/op
                 existUser·p0.90:   3.658 ms/op
                 existUser·p0.95:   3.846 ms/op
                 existUser·p0.99:   4.211 ms/op
                 existUser·p0.999:  5.716 ms/op
                 existUser·p0.9999: 11.385 ms/op
                 existUser·p1.00:   11.796 ms/op

Iteration   2: 3.014 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.741 ms/op
                 existUser·p0.50:   3.002 ms/op
                 existUser·p0.90:   3.645 ms/op
                 existUser·p0.95:   3.797 ms/op
                 existUser·p0.99:   4.219 ms/op
                 existUser·p0.999:  8.438 ms/op
                 existUser·p0.9999: 13.520 ms/op
                 existUser·p1.00:   14.008 ms/op

Iteration   3: 2.922 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.708 ms/op
                 existUser·p0.50:   2.920 ms/op
                 existUser·p0.90:   3.551 ms/op
                 existUser·p0.95:   3.736 ms/op
                 existUser·p0.99:   4.190 ms/op
                 existUser·p0.999:  8.358 ms/op
                 existUser·p0.9999: 14.584 ms/op
                 existUser·p1.00:   14.893 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 322782
  mean =      2.973 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2693 
    [ 1.250,  2.500) = 44699 
    [ 2.500,  3.750) = 255572 
    [ 3.750,  5.000) = 18864 
    [ 5.000,  6.250) = 415 
    [ 6.250,  7.500) = 211 
    [ 7.500,  8.750) = 122 
    [ 8.750, 10.000) = 46 
    [10.000, 11.250) = 21 
    [11.250, 12.500) = 58 
    [12.500, 13.750) = 41 
    [13.750, 15.000) = 40 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.708 ms/op
     p(50.0000) =      2.966 ms/op
     p(90.0000) =      3.621 ms/op
     p(95.0000) =      3.801 ms/op
     p(99.0000) =      4.202 ms/op
     p(99.9000) =      7.637 ms/op
     p(99.9900) =     13.852 ms/op
     p(99.9990) =     14.787 ms/op
     p(99.9999) =     14.893 ms/op
    p(100.0000) =     14.893 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.976 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.100 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.150 ±(99.9%) 0.007 ms/op
Iteration   1: 3.093 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.734 ms/op
                 getUser·p0.50:   3.105 ms/op
                 getUser·p0.90:   3.756 ms/op
                 getUser·p0.95:   3.925 ms/op
                 getUser·p0.99:   4.325 ms/op
                 getUser·p0.999:  6.601 ms/op
                 getUser·p0.9999: 14.673 ms/op
                 getUser·p1.00:   15.958 ms/op

Iteration   2: 2.994 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.678 ms/op
                 getUser·p0.50:   3.006 ms/op
                 getUser·p0.90:   3.531 ms/op
                 getUser·p0.95:   3.744 ms/op
                 getUser·p0.99:   4.227 ms/op
                 getUser·p0.999:  6.981 ms/op
                 getUser·p0.9999: 13.873 ms/op
                 getUser·p1.00:   14.860 ms/op

Iteration   3: 2.980 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.682 ms/op
                 getUser·p0.50:   2.986 ms/op
                 getUser·p0.90:   3.482 ms/op
                 getUser·p0.95:   3.666 ms/op
                 getUser·p0.99:   4.189 ms/op
                 getUser·p0.999:  6.625 ms/op
                 getUser·p0.9999: 16.213 ms/op
                 getUser·p1.00:   16.597 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 317560
  mean =      3.021 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2226 
    [ 1.250,  2.500) = 28755 
    [ 2.500,  3.750) = 266626 
    [ 3.750,  5.000) = 19089 
    [ 5.000,  6.250) = 491 
    [ 6.250,  7.500) = 147 
    [ 7.500,  8.750) = 22 
    [ 8.750, 10.000) = 20 
    [10.000, 11.250) = 11 
    [11.250, 12.500) = 46 
    [12.500, 13.750) = 42 
    [13.750, 15.000) = 51 
    [15.000, 16.250) = 25 
    [16.250, 17.500) = 9 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.678 ms/op
     p(50.0000) =      3.023 ms/op
     p(90.0000) =      3.604 ms/op
     p(95.0000) =      3.817 ms/op
     p(99.0000) =      4.243 ms/op
     p(99.9000) =      6.680 ms/op
     p(99.9900) =     15.331 ms/op
     p(99.9990) =     16.471 ms/op
     p(99.9999) =     16.597 ms/op
    p(100.0000) =     16.597 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.088 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 4.127 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.946 ±(99.9%) 0.010 ms/op
Iteration   1: 4.043 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.739 ms/op
                 listUser·p0.50:   3.817 ms/op
                 listUser·p0.90:   5.456 ms/op
                 listUser·p0.95:   6.021 ms/op
                 listUser·p0.99:   7.045 ms/op
                 listUser·p0.999:  12.354 ms/op
                 listUser·p0.9999: 13.961 ms/op
                 listUser·p1.00:   16.253 ms/op

Iteration   2: 4.020 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.947 ms/op
                 listUser·p0.50:   3.813 ms/op
                 listUser·p0.90:   5.194 ms/op
                 listUser·p0.95:   5.644 ms/op
                 listUser·p0.99:   6.849 ms/op
                 listUser·p0.999:  15.565 ms/op
                 listUser·p0.9999: 22.809 ms/op
                 listUser·p1.00:   23.003 ms/op

Iteration   3: 4.142 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.760 ms/op
                 listUser·p0.50:   3.912 ms/op
                 listUser·p0.90:   5.349 ms/op
                 listUser·p0.95:   5.726 ms/op
                 listUser·p0.99:   7.062 ms/op
                 listUser·p0.999:  16.295 ms/op
                 listUser·p0.9999: 20.662 ms/op
                 listUser·p1.00:   21.266 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 235998
  mean =      4.068 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6021 
    [ 2.500,  5.000) = 190795 
    [ 5.000,  7.500) = 37869 
    [ 7.500, 10.000) = 875 
    [10.000, 12.500) = 158 
    [12.500, 15.000) = 102 
    [15.000, 17.500) = 109 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.739 ms/op
     p(50.0000) =      3.842 ms/op
     p(90.0000) =      5.341 ms/op
     p(95.0000) =      5.800 ms/op
     p(99.0000) =      6.988 ms/op
     p(99.9000) =     13.320 ms/op
     p(99.9900) =     21.902 ms/op
     p(99.9990) =     23.003 ms/op
     p(99.9999) =     23.003 ms/op
    p(100.0000) =     23.003 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.432 ± 3.780  ops/ms
ClientGrpc.existUser                       thrpt       3  10.827 ± 1.703  ops/ms
ClientGrpc.getUser                         thrpt       3  10.497 ± 0.398  ops/ms
ClientGrpc.listUser                        thrpt       3   7.923 ± 0.899  ops/ms
ClientGrpc.createUser                       avgt       3   3.061 ± 1.672   ms/op
ClientGrpc.existUser                        avgt       3   2.939 ± 1.137   ms/op
ClientGrpc.getUser                          avgt       3   3.008 ± 1.015   ms/op
ClientGrpc.listUser                         avgt       3   3.988 ± 1.205   ms/op
ClientGrpc.createUser                     sample  312975   3.068 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.531           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.052           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.723           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.916           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.293           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.946           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          16.423           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          18.678           ms/op
ClientGrpc.existUser                      sample  322782   2.973 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.708           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.966           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.621           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.801           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.202           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.637           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          13.852           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          14.893           ms/op
ClientGrpc.getUser                        sample  317560   3.021 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.678           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.023           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.604           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.817           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.243           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.680           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          15.331           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          16.597           ms/op
ClientGrpc.listUser                       sample  235998   4.068 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.739           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.842           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.341           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.800           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.988           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.320           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.902           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.003           ms/op
