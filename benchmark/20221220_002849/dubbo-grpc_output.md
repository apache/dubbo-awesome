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
# Warmup Iteration   1: 4.791 ops/ms
# Warmup Iteration   2: 9.261 ops/ms
# Warmup Iteration   3: 10.348 ops/ms
Iteration   1: 10.642 ops/ms
Iteration   2: 10.592 ops/ms
Iteration   3: 10.648 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.627 ±(99.9%) 0.558 ops/ms [Average]
  (min, avg, max) = (10.592, 10.627, 10.648), stdev = 0.031
  CI (99.9%): [10.069, 11.185] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:55
# Fork: 1 of 1
# Warmup Iteration   1: 7.816 ops/ms
# Warmup Iteration   2: 10.481 ops/ms
# Warmup Iteration   3: 10.790 ops/ms
Iteration   1: 10.797 ops/ms
Iteration   2: 10.850 ops/ms
Iteration   3: 10.721 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.789 ±(99.9%) 1.176 ops/ms [Average]
  (min, avg, max) = (10.721, 10.789, 10.850), stdev = 0.064
  CI (99.9%): [9.614, 11.965] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:50
# Fork: 1 of 1
# Warmup Iteration   1: 7.890 ops/ms
# Warmup Iteration   2: 10.442 ops/ms
# Warmup Iteration   3: 10.623 ops/ms
Iteration   1: 10.588 ops/ms
Iteration   2: 10.796 ops/ms
Iteration   3: 10.930 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.771 ±(99.9%) 3.139 ops/ms [Average]
  (min, avg, max) = (10.588, 10.771, 10.930), stdev = 0.172
  CI (99.9%): [7.633, 13.910] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 7.065 ops/ms
# Warmup Iteration   2: 7.876 ops/ms
# Warmup Iteration   3: 8.095 ops/ms
Iteration   1: 8.485 ops/ms
Iteration   2: 8.471 ops/ms
Iteration   3: 8.340 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.432 ±(99.9%) 1.453 ops/ms [Average]
  (min, avg, max) = (8.340, 8.432, 8.485), stdev = 0.080
  CI (99.9%): [6.979, 9.885] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 3.874 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.091 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.957 ±(99.9%) 0.003 ms/op
Iteration   1: 3.043 ±(99.9%) 0.002 ms/op
Iteration   2: 3.084 ±(99.9%) 0.003 ms/op
Iteration   3: 3.011 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.046 ±(99.9%) 0.675 ms/op [Average]
  (min, avg, max) = (3.011, 3.046, 3.084), stdev = 0.037
  CI (99.9%): [2.370, 3.721] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.715 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.971 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.836 ±(99.9%) 0.002 ms/op
Iteration   1: 2.880 ±(99.9%) 0.004 ms/op
Iteration   2: 2.861 ±(99.9%) 0.004 ms/op
Iteration   3: 2.849 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.863 ±(99.9%) 0.292 ms/op [Average]
  (min, avg, max) = (2.849, 2.863, 2.880), stdev = 0.016
  CI (99.9%): [2.571, 3.155] (assumes normal distribution)


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
# Warmup Iteration   1: 3.879 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.104 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.011 ±(99.9%) 0.002 ms/op
Iteration   1: 2.994 ±(99.9%) 0.003 ms/op
Iteration   2: 3.000 ±(99.9%) 0.002 ms/op
Iteration   3: 2.999 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.998 ±(99.9%) 0.056 ms/op [Average]
  (min, avg, max) = (2.994, 2.998, 3.000), stdev = 0.003
  CI (99.9%): [2.942, 3.053] (assumes normal distribution)


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
# Warmup Iteration   1: 5.158 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 4.027 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.989 ±(99.9%) 0.012 ms/op
Iteration   1: 3.809 ±(99.9%) 0.017 ms/op
Iteration   2: 3.708 ±(99.9%) 0.006 ms/op
Iteration   3: 3.868 ±(99.9%) 0.036 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.795 ±(99.9%) 1.476 ms/op [Average]
  (min, avg, max) = (3.708, 3.795, 3.868), stdev = 0.081
  CI (99.9%): [2.319, 5.271] (assumes normal distribution)


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
# Warmup Iteration   1: 3.892 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.141 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.102 ±(99.9%) 0.007 ms/op
Iteration   1: 3.091 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.713 ms/op
                 createUser·p0.50:   3.072 ms/op
                 createUser·p0.90:   3.785 ms/op
                 createUser·p0.95:   3.949 ms/op
                 createUser·p0.99:   4.366 ms/op
                 createUser·p0.999:  8.313 ms/op
                 createUser·p0.9999: 11.631 ms/op
                 createUser·p1.00:   11.911 ms/op

Iteration   2: 3.120 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.597 ms/op
                 createUser·p0.50:   3.092 ms/op
                 createUser·p0.90:   3.838 ms/op
                 createUser·p0.95:   4.010 ms/op
                 createUser·p0.99:   4.276 ms/op
                 createUser·p0.999:  9.513 ms/op
                 createUser·p0.9999: 14.209 ms/op
                 createUser·p1.00:   14.680 ms/op

Iteration   3: 3.089 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.678 ms/op
                 createUser·p0.50:   3.064 ms/op
                 createUser·p0.90:   3.777 ms/op
                 createUser·p0.95:   3.949 ms/op
                 createUser·p0.99:   4.252 ms/op
                 createUser·p0.999:  7.466 ms/op
                 createUser·p0.9999: 15.696 ms/op
                 createUser·p1.00:   16.646 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 309626
  mean =      3.100 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1088 
    [ 1.250,  2.500) = 31314 
    [ 2.500,  3.750) = 240756 
    [ 3.750,  5.000) = 35369 
    [ 5.000,  6.250) = 451 
    [ 6.250,  7.500) = 272 
    [ 7.500,  8.750) = 105 
    [ 8.750, 10.000) = 64 
    [10.000, 11.250) = 52 
    [11.250, 12.500) = 40 
    [12.500, 13.750) = 57 
    [13.750, 15.000) = 28 
    [15.000, 16.250) = 29 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.597 ms/op
     p(50.0000) =      3.076 ms/op
     p(90.0000) =      3.801 ms/op
     p(95.0000) =      3.973 ms/op
     p(99.0000) =      4.293 ms/op
     p(99.9000) =      8.004 ms/op
     p(99.9900) =     14.960 ms/op
     p(99.9990) =     15.899 ms/op
     p(99.9999) =     16.646 ms/op
    p(100.0000) =     16.646 ms/op


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
# Warmup Iteration   1: 3.706 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 2.959 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.905 ±(99.9%) 0.006 ms/op
Iteration   1: 2.959 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.672 ms/op
                 existUser·p0.50:   2.920 ms/op
                 existUser·p0.90:   3.637 ms/op
                 existUser·p0.95:   3.863 ms/op
                 existUser·p0.99:   4.424 ms/op
                 existUser·p0.999:  6.570 ms/op
                 existUser·p0.9999: 11.852 ms/op
                 existUser·p1.00:   12.108 ms/op

Iteration   2: 2.953 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.443 ms/op
                 existUser·p0.50:   2.945 ms/op
                 existUser·p0.90:   3.613 ms/op
                 existUser·p0.95:   3.797 ms/op
                 existUser·p0.99:   4.063 ms/op
                 existUser·p0.999:  5.126 ms/op
                 existUser·p0.9999: 14.565 ms/op
                 existUser·p1.00:   14.811 ms/op

Iteration   3: 2.810 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.606 ms/op
                 existUser·p0.50:   2.806 ms/op
                 existUser·p0.90:   3.420 ms/op
                 existUser·p0.95:   3.756 ms/op
                 existUser·p0.99:   4.563 ms/op
                 existUser·p0.999:  6.398 ms/op
                 existUser·p0.9999: 23.830 ms/op
                 existUser·p1.00:   25.330 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 330284
  mean =      2.905 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 64778 
    [ 2.500,  5.000) = 264529 
    [ 5.000,  7.500) = 785 
    [ 7.500, 10.000) = 38 
    [10.000, 12.500) = 58 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.443 ms/op
     p(50.0000) =      2.884 ms/op
     p(90.0000) =      3.580 ms/op
     p(95.0000) =      3.809 ms/op
     p(99.0000) =      4.391 ms/op
     p(99.9000) =      6.242 ms/op
     p(99.9900) =     14.810 ms/op
     p(99.9990) =     25.320 ms/op
     p(99.9999) =     25.330 ms/op
    p(100.0000) =     25.330 ms/op


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
# Warmup Iteration   1: 3.411 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.145 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.023 ±(99.9%) 0.006 ms/op
Iteration   1: 3.197 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.221 ms/op
                 getUser·p0.50:   3.101 ms/op
                 getUser·p0.90:   3.998 ms/op
                 getUser·p0.95:   4.415 ms/op
                 getUser·p0.99:   5.489 ms/op
                 getUser·p0.999:  11.437 ms/op
                 getUser·p0.9999: 18.219 ms/op
                 getUser·p1.00:   18.547 ms/op

Iteration   2: 2.980 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.372 ms/op
                 getUser·p0.50:   2.974 ms/op
                 getUser·p0.90:   3.650 ms/op
                 getUser·p0.95:   3.887 ms/op
                 getUser·p0.99:   4.596 ms/op
                 getUser·p0.999:  11.372 ms/op
                 getUser·p0.9999: 27.673 ms/op
                 getUser·p1.00:   28.049 ms/op

Iteration   3: 3.082 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.271 ms/op
                 getUser·p0.50:   3.056 ms/op
                 getUser·p0.90:   3.707 ms/op
                 getUser·p0.95:   3.899 ms/op
                 getUser·p0.99:   4.243 ms/op
                 getUser·p0.999:  7.087 ms/op
                 getUser·p0.9999: 21.012 ms/op
                 getUser·p1.00:   21.463 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 311407
  mean =      3.084 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 36165 
    [ 2.500,  5.000) = 272300 
    [ 5.000,  7.500) = 2416 
    [ 7.500, 10.000) = 226 
    [10.000, 12.500) = 72 
    [12.500, 15.000) = 65 
    [15.000, 17.500) = 82 
    [17.500, 20.000) = 37 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 18 

  Percentiles, ms/op:
      p(0.0000) =      0.221 ms/op
     p(50.0000) =      3.039 ms/op
     p(90.0000) =      3.781 ms/op
     p(95.0000) =      4.043 ms/op
     p(99.0000) =      4.964 ms/op
     p(99.9000) =      9.627 ms/op
     p(99.9900) =     25.849 ms/op
     p(99.9990) =     27.976 ms/op
     p(99.9999) =     28.049 ms/op
    p(100.0000) =     28.049 ms/op


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
# Warmup Iteration   1: 4.907 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 4.032 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.736 ±(99.9%) 0.009 ms/op
Iteration   1: 3.885 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.010 ms/op
                 listUser·p0.50:   3.711 ms/op
                 listUser·p0.90:   4.973 ms/op
                 listUser·p0.95:   5.439 ms/op
                 listUser·p0.99:   6.586 ms/op
                 listUser·p0.999:  12.386 ms/op
                 listUser·p0.9999: 19.890 ms/op
                 listUser·p1.00:   20.218 ms/op

Iteration   2: 3.945 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.885 ms/op
                 listUser·p0.50:   3.748 ms/op
                 listUser·p0.90:   5.063 ms/op
                 listUser·p0.95:   5.448 ms/op
                 listUser·p0.99:   6.603 ms/op
                 listUser·p0.999:  13.678 ms/op
                 listUser·p0.9999: 18.019 ms/op
                 listUser·p1.00:   18.940 ms/op

Iteration   3: 4.018 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.867 ms/op
                 listUser·p0.50:   3.809 ms/op
                 listUser·p0.90:   5.186 ms/op
                 listUser·p0.95:   5.472 ms/op
                 listUser·p0.99:   6.832 ms/op
                 listUser·p0.999:  15.696 ms/op
                 listUser·p0.9999: 19.859 ms/op
                 listUser·p1.00:   20.152 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 243293
  mean =      3.948 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4503 
    [ 2.500,  5.000) = 210737 
    [ 5.000,  7.500) = 27082 
    [ 7.500, 10.000) = 560 
    [10.000, 12.500) = 67 
    [12.500, 15.000) = 137 
    [15.000, 17.500) = 102 
    [17.500, 20.000) = 96 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.867 ms/op
     p(50.0000) =      3.752 ms/op
     p(90.0000) =      5.087 ms/op
     p(95.0000) =      5.456 ms/op
     p(99.0000) =      6.668 ms/op
     p(99.9000) =     13.938 ms/op
     p(99.9900) =     19.748 ms/op
     p(99.9990) =     20.171 ms/op
     p(99.9999) =     20.218 ms/op
    p(100.0000) =     20.218 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.627 ± 0.558  ops/ms
ClientGrpc.existUser                       thrpt       3  10.789 ± 1.176  ops/ms
ClientGrpc.getUser                         thrpt       3  10.771 ± 3.139  ops/ms
ClientGrpc.listUser                        thrpt       3   8.432 ± 1.453  ops/ms
ClientGrpc.createUser                       avgt       3   3.046 ± 0.675   ms/op
ClientGrpc.existUser                        avgt       3   2.863 ± 0.292   ms/op
ClientGrpc.getUser                          avgt       3   2.998 ± 0.056   ms/op
ClientGrpc.listUser                         avgt       3   3.795 ± 1.476   ms/op
ClientGrpc.createUser                     sample  309626   3.100 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.597           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.076           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.801           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.973           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.293           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.004           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          14.960           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          16.646           ms/op
ClientGrpc.existUser                      sample  330284   2.905 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.443           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.884           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.580           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.809           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.391           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.242           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.810           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          25.330           ms/op
ClientGrpc.getUser                        sample  311407   3.084 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.221           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.039           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.781           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.043           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.964           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.627           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          25.849           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          28.049           ms/op
ClientGrpc.listUser                       sample  243293   3.948 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.867           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.752           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.087           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.456           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.668           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.938           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          19.748           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          20.218           ms/op
