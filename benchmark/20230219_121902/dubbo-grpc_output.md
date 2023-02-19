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
# Warmup Iteration   1: 5.107 ops/ms
# Warmup Iteration   2: 9.613 ops/ms
# Warmup Iteration   3: 10.505 ops/ms
Iteration   1: 10.352 ops/ms
Iteration   2: 10.306 ops/ms
Iteration   3: 10.280 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.312 ±(99.9%) 0.670 ops/ms [Average]
  (min, avg, max) = (10.280, 10.312, 10.352), stdev = 0.037
  CI (99.9%): [9.643, 10.982] (assumes normal distribution)


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
# Warmup Iteration   1: 8.217 ops/ms
# Warmup Iteration   2: 10.524 ops/ms
# Warmup Iteration   3: 10.692 ops/ms
Iteration   1: 10.633 ops/ms
Iteration   2: 10.549 ops/ms
Iteration   3: 10.685 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.622 ±(99.9%) 1.259 ops/ms [Average]
  (min, avg, max) = (10.549, 10.622, 10.685), stdev = 0.069
  CI (99.9%): [9.363, 11.882] (assumes normal distribution)


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
# Warmup Iteration   1: 8.303 ops/ms
# Warmup Iteration   2: 10.290 ops/ms
# Warmup Iteration   3: 10.268 ops/ms
Iteration   1: 10.369 ops/ms
Iteration   2: 10.672 ops/ms
Iteration   3: 10.793 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.612 ±(99.9%) 3.983 ops/ms [Average]
  (min, avg, max) = (10.369, 10.612, 10.793), stdev = 0.218
  CI (99.9%): [6.629, 14.594] (assumes normal distribution)


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
# Warmup Iteration   1: 5.740 ops/ms
# Warmup Iteration   2: 7.603 ops/ms
# Warmup Iteration   3: 7.733 ops/ms
Iteration   1: 7.604 ops/ms
Iteration   2: 7.889 ops/ms
Iteration   3: 7.940 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.811 ±(99.9%) 3.305 ops/ms [Average]
  (min, avg, max) = (7.604, 7.811, 7.940), stdev = 0.181
  CI (99.9%): [4.506, 11.116] (assumes normal distribution)


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
# Warmup Iteration   1: 4.117 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.127 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.071 ±(99.9%) 0.003 ms/op
Iteration   1: 3.056 ±(99.9%) 0.002 ms/op
Iteration   2: 3.134 ±(99.9%) 0.002 ms/op
Iteration   3: 3.026 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.072 ±(99.9%) 1.015 ms/op [Average]
  (min, avg, max) = (3.026, 3.072, 3.134), stdev = 0.056
  CI (99.9%): [2.057, 4.087] (assumes normal distribution)


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
# Warmup Iteration   1: 3.817 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.031 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.988 ±(99.9%) 0.002 ms/op
Iteration   1: 2.961 ±(99.9%) 0.002 ms/op
Iteration   2: 3.020 ±(99.9%) 0.002 ms/op
Iteration   3: 2.942 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.974 ±(99.9%) 0.749 ms/op [Average]
  (min, avg, max) = (2.942, 2.974, 3.020), stdev = 0.041
  CI (99.9%): [2.225, 3.723] (assumes normal distribution)


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
# Warmup Iteration   1: 3.978 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.184 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.137 ±(99.9%) 0.003 ms/op
Iteration   1: 3.210 ±(99.9%) 0.002 ms/op
Iteration   2: 3.097 ±(99.9%) 0.002 ms/op
Iteration   3: 3.139 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.149 ±(99.9%) 1.039 ms/op [Average]
  (min, avg, max) = (3.097, 3.149, 3.210), stdev = 0.057
  CI (99.9%): [2.110, 4.187] (assumes normal distribution)


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
# Warmup Iteration   1: 4.880 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 4.190 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.069 ±(99.9%) 0.012 ms/op
Iteration   1: 3.927 ±(99.9%) 0.008 ms/op
Iteration   2: 4.042 ±(99.9%) 0.011 ms/op
Iteration   3: 3.865 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.944 ±(99.9%) 1.636 ms/op [Average]
  (min, avg, max) = (3.865, 3.944, 4.042), stdev = 0.090
  CI (99.9%): [2.308, 5.580] (assumes normal distribution)


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
# Warmup Iteration   1: 3.993 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.194 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.008 ±(99.9%) 0.008 ms/op
Iteration   1: 3.071 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.503 ms/op
                 createUser·p0.50:   3.056 ms/op
                 createUser·p0.90:   3.625 ms/op
                 createUser·p0.95:   3.891 ms/op
                 createUser·p0.99:   4.637 ms/op
                 createUser·p0.999:  7.846 ms/op
                 createUser·p0.9999: 17.550 ms/op
                 createUser·p1.00:   17.891 ms/op

Iteration   2: 3.091 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.570 ms/op
                 createUser·p0.50:   3.064 ms/op
                 createUser·p0.90:   3.703 ms/op
                 createUser·p0.95:   3.920 ms/op
                 createUser·p0.99:   4.506 ms/op
                 createUser·p0.999:  7.793 ms/op
                 createUser·p0.9999: 25.788 ms/op
                 createUser·p1.00:   26.608 ms/op

Iteration   3: 3.151 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.621 ms/op
                 createUser·p0.50:   3.133 ms/op
                 createUser·p0.90:   3.846 ms/op
                 createUser·p0.95:   4.030 ms/op
                 createUser·p0.99:   4.522 ms/op
                 createUser·p0.999:  6.521 ms/op
                 createUser·p0.9999: 16.941 ms/op
                 createUser·p1.00:   21.037 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 309404
  mean =      3.104 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24911 
    [ 2.500,  5.000) = 282831 
    [ 5.000,  7.500) = 1371 
    [ 7.500, 10.000) = 125 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 20 
    [15.000, 17.500) = 95 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.503 ms/op
     p(50.0000) =      3.076 ms/op
     p(90.0000) =      3.740 ms/op
     p(95.0000) =      3.965 ms/op
     p(99.0000) =      4.555 ms/op
     p(99.9000) =      7.406 ms/op
     p(99.9900) =     25.054 ms/op
     p(99.9990) =     26.438 ms/op
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
# Warmup Iteration   1: 3.909 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.038 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.003 ±(99.9%) 0.006 ms/op
Iteration   1: 2.956 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.707 ms/op
                 existUser·p0.50:   2.941 ms/op
                 existUser·p0.90:   3.617 ms/op
                 existUser·p0.95:   3.805 ms/op
                 existUser·p0.99:   4.243 ms/op
                 existUser·p0.999:  6.790 ms/op
                 existUser·p0.9999: 11.046 ms/op
                 existUser·p1.00:   11.272 ms/op

Iteration   2: 2.955 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.497 ms/op
                 existUser·p0.50:   2.925 ms/op
                 existUser·p0.90:   3.584 ms/op
                 existUser·p0.95:   3.777 ms/op
                 existUser·p0.99:   4.211 ms/op
                 existUser·p0.999:  7.219 ms/op
                 existUser·p0.9999: 13.050 ms/op
                 existUser·p1.00:   13.386 ms/op

Iteration   3: 2.971 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.518 ms/op
                 existUser·p0.50:   2.949 ms/op
                 existUser·p0.90:   3.658 ms/op
                 existUser·p0.95:   3.908 ms/op
                 existUser·p0.99:   4.841 ms/op
                 existUser·p0.999:  8.897 ms/op
                 existUser·p0.9999: 14.799 ms/op
                 existUser·p1.00:   15.204 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 324071
  mean =      2.961 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2577 
    [ 1.250,  2.500) = 48577 
    [ 2.500,  3.750) = 251736 
    [ 3.750,  5.000) = 19380 
    [ 5.000,  6.250) = 944 
    [ 6.250,  7.500) = 494 
    [ 7.500,  8.750) = 147 
    [ 8.750, 10.000) = 27 
    [10.000, 11.250) = 58 
    [11.250, 12.500) = 34 
    [12.500, 13.750) = 50 
    [13.750, 15.000) = 42 
    [15.000, 16.250) = 5 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.497 ms/op
     p(50.0000) =      2.941 ms/op
     p(90.0000) =      3.617 ms/op
     p(95.0000) =      3.826 ms/op
     p(99.0000) =      4.407 ms/op
     p(99.9000) =      7.635 ms/op
     p(99.9900) =     14.231 ms/op
     p(99.9990) =     15.123 ms/op
     p(99.9999) =     15.204 ms/op
    p(100.0000) =     15.204 ms/op


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
# Warmup Iteration   1: 3.900 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.122 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.999 ±(99.9%) 0.007 ms/op
Iteration   1: 3.081 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.780 ms/op
                 getUser·p0.50:   3.060 ms/op
                 getUser·p0.90:   3.699 ms/op
                 getUser·p0.95:   3.912 ms/op
                 getUser·p0.99:   4.686 ms/op
                 getUser·p0.999:  8.109 ms/op
                 getUser·p0.9999: 16.181 ms/op
                 getUser·p1.00:   18.121 ms/op

Iteration   2: 3.014 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.723 ms/op
                 getUser·p0.50:   3.015 ms/op
                 getUser·p0.90:   3.600 ms/op
                 getUser·p0.95:   3.879 ms/op
                 getUser·p0.99:   4.760 ms/op
                 getUser·p0.999:  11.350 ms/op
                 getUser·p0.9999: 17.105 ms/op
                 getUser·p1.00:   17.498 ms/op

Iteration   3: 3.127 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.709 ms/op
                 getUser·p0.50:   3.101 ms/op
                 getUser·p0.90:   3.781 ms/op
                 getUser·p0.95:   3.965 ms/op
                 getUser·p0.99:   4.399 ms/op
                 getUser·p0.999:  10.292 ms/op
                 getUser·p0.9999: 18.499 ms/op
                 getUser·p1.00:   18.874 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 312220
  mean =      3.073 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1975 
    [ 1.250,  2.500) = 27015 
    [ 2.500,  3.750) = 255788 
    [ 3.750,  5.000) = 25304 
    [ 5.000,  6.250) = 1319 
    [ 6.250,  7.500) = 391 
    [ 7.500,  8.750) = 82 
    [ 8.750, 10.000) = 37 
    [10.000, 11.250) = 65 
    [11.250, 12.500) = 30 
    [12.500, 13.750) = 10 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 80 
    [16.250, 17.500) = 70 
    [17.500, 18.750) = 50 

  Percentiles, ms/op:
      p(0.0000) =      0.709 ms/op
     p(50.0000) =      3.052 ms/op
     p(90.0000) =      3.707 ms/op
     p(95.0000) =      3.928 ms/op
     p(99.0000) =      4.579 ms/op
     p(99.9000) =      9.991 ms/op
     p(99.9900) =     18.055 ms/op
     p(99.9990) =     18.707 ms/op
     p(99.9999) =     18.874 ms/op
    p(100.0000) =     18.874 ms/op


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
# Warmup Iteration   1: 4.255 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 4.227 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.011 ±(99.9%) 0.011 ms/op
Iteration   1: 4.046 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.011 ms/op
                 listUser·p0.50:   3.850 ms/op
                 listUser·p0.90:   5.210 ms/op
                 listUser·p0.95:   5.808 ms/op
                 listUser·p0.99:   7.012 ms/op
                 listUser·p0.999:  12.810 ms/op
                 listUser·p0.9999: 18.946 ms/op
                 listUser·p1.00:   22.446 ms/op

Iteration   2: 4.096 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.857 ms/op
                 listUser·p0.50:   3.863 ms/op
                 listUser·p0.90:   5.300 ms/op
                 listUser·p0.95:   5.808 ms/op
                 listUser·p0.99:   7.258 ms/op
                 listUser·p0.999:  18.708 ms/op
                 listUser·p0.9999: 24.429 ms/op
                 listUser·p1.00:   25.526 ms/op

Iteration   3: 3.900 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.044 ms/op
                 listUser·p0.50:   3.727 ms/op
                 listUser·p0.90:   5.030 ms/op
                 listUser·p0.95:   5.628 ms/op
                 listUser·p0.99:   6.930 ms/op
                 listUser·p0.999:  14.730 ms/op
                 listUser·p0.9999: 23.187 ms/op
                 listUser·p1.00:   23.626 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 239105
  mean =      4.012 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3113 
    [ 2.500,  5.000) = 205989 
    [ 5.000,  7.500) = 28400 
    [ 7.500, 10.000) = 1029 
    [10.000, 12.500) = 182 
    [12.500, 15.000) = 132 
    [15.000, 17.500) = 69 
    [17.500, 20.000) = 112 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 63 
    [25.000, 27.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.857 ms/op
     p(50.0000) =      3.813 ms/op
     p(90.0000) =      5.186 ms/op
     p(95.0000) =      5.751 ms/op
     p(99.0000) =      7.086 ms/op
     p(99.9000) =     16.395 ms/op
     p(99.9900) =     23.301 ms/op
     p(99.9990) =     25.331 ms/op
     p(99.9999) =     25.526 ms/op
    p(100.0000) =     25.526 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.312 ± 0.670  ops/ms
ClientGrpc.existUser                       thrpt       3  10.622 ± 1.259  ops/ms
ClientGrpc.getUser                         thrpt       3  10.612 ± 3.983  ops/ms
ClientGrpc.listUser                        thrpt       3   7.811 ± 3.305  ops/ms
ClientGrpc.createUser                       avgt       3   3.072 ± 1.015   ms/op
ClientGrpc.existUser                        avgt       3   2.974 ± 0.749   ms/op
ClientGrpc.getUser                          avgt       3   3.149 ± 1.039   ms/op
ClientGrpc.listUser                         avgt       3   3.944 ± 1.636   ms/op
ClientGrpc.createUser                     sample  309404   3.104 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.503           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.076           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.740           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.965           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.555           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.406           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          25.054           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          26.608           ms/op
ClientGrpc.existUser                      sample  324071   2.961 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.497           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.941           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.617           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.826           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.407           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.635           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.231           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          15.204           ms/op
ClientGrpc.getUser                        sample  312220   3.073 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.709           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.052           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.707           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.928           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.579           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.991           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.055           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.874           ms/op
ClientGrpc.listUser                       sample  239105   4.012 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.857           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.813           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.186           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.751           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.086           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.395           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.301           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.526           ms/op
