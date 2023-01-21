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
# Warmup Iteration   1: 4.783 ops/ms
# Warmup Iteration   2: 9.322 ops/ms
# Warmup Iteration   3: 10.080 ops/ms
Iteration   1: 10.158 ops/ms
Iteration   2: 10.190 ops/ms
Iteration   3: 10.265 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.204 ±(99.9%) 1.001 ops/ms [Average]
  (min, avg, max) = (10.158, 10.204, 10.265), stdev = 0.055
  CI (99.9%): [9.203, 11.205] (assumes normal distribution)


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
# Warmup Iteration   1: 7.738 ops/ms
# Warmup Iteration   2: 10.644 ops/ms
# Warmup Iteration   3: 10.870 ops/ms
Iteration   1: 10.625 ops/ms
Iteration   2: 10.621 ops/ms
Iteration   3: 10.848 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.698 ±(99.9%) 2.370 ops/ms [Average]
  (min, avg, max) = (10.621, 10.698, 10.848), stdev = 0.130
  CI (99.9%): [8.329, 13.068] (assumes normal distribution)


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
# Warmup Iteration   1: 7.073 ops/ms
# Warmup Iteration   2: 10.174 ops/ms
# Warmup Iteration   3: 10.136 ops/ms
Iteration   1: 10.001 ops/ms
Iteration   2: 10.116 ops/ms
Iteration   3: 10.266 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.128 ±(99.9%) 2.422 ops/ms [Average]
  (min, avg, max) = (10.001, 10.128, 10.266), stdev = 0.133
  CI (99.9%): [7.705, 12.550] (assumes normal distribution)


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
# Warmup Iteration   1: 7.159 ops/ms
# Warmup Iteration   2: 7.689 ops/ms
# Warmup Iteration   3: 7.668 ops/ms
Iteration   1: 8.009 ops/ms
Iteration   2: 8.161 ops/ms
Iteration   3: 7.948 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.040 ±(99.9%) 2.001 ops/ms [Average]
  (min, avg, max) = (7.948, 8.040, 8.161), stdev = 0.110
  CI (99.9%): [6.038, 10.041] (assumes normal distribution)


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
# Warmup Iteration   1: 4.420 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.157 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.043 ±(99.9%) 0.002 ms/op
Iteration   1: 3.207 ±(99.9%) 0.002 ms/op
Iteration   2: 3.161 ±(99.9%) 0.002 ms/op
Iteration   3: 3.114 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.161 ±(99.9%) 0.852 ms/op [Average]
  (min, avg, max) = (3.114, 3.161, 3.207), stdev = 0.047
  CI (99.9%): [2.309, 4.012] (assumes normal distribution)


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
# Warmup Iteration   1: 3.907 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.027 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.995 ±(99.9%) 0.003 ms/op
Iteration   1: 3.026 ±(99.9%) 0.002 ms/op
Iteration   2: 2.994 ±(99.9%) 0.002 ms/op
Iteration   3: 2.998 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.006 ±(99.9%) 0.321 ms/op [Average]
  (min, avg, max) = (2.994, 3.006, 3.026), stdev = 0.018
  CI (99.9%): [2.685, 3.328] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 3.968 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.180 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.108 ±(99.9%) 0.002 ms/op
Iteration   1: 3.126 ±(99.9%) 0.003 ms/op
Iteration   2: 3.148 ±(99.9%) 0.003 ms/op
Iteration   3: 3.192 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.155 ±(99.9%) 0.615 ms/op [Average]
  (min, avg, max) = (3.126, 3.155, 3.192), stdev = 0.034
  CI (99.9%): [2.540, 3.770] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 4.520 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 4.198 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.166 ±(99.9%) 0.013 ms/op
Iteration   1: 3.998 ±(99.9%) 0.018 ms/op
Iteration   2: 3.967 ±(99.9%) 0.006 ms/op
Iteration   3: 4.067 ±(99.9%) 0.071 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.011 ±(99.9%) 0.926 ms/op [Average]
  (min, avg, max) = (3.967, 4.011, 4.067), stdev = 0.051
  CI (99.9%): [3.085, 4.936] (assumes normal distribution)


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
# Warmup Iteration   1: 3.857 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.238 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.062 ±(99.9%) 0.006 ms/op
Iteration   1: 3.125 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.779 ms/op
                 createUser·p0.50:   3.121 ms/op
                 createUser·p0.90:   3.801 ms/op
                 createUser·p0.95:   3.990 ms/op
                 createUser·p0.99:   4.415 ms/op
                 createUser·p0.999:  9.357 ms/op
                 createUser·p0.9999: 13.095 ms/op
                 createUser·p1.00:   13.402 ms/op

Iteration   2: 3.183 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.760 ms/op
                 createUser·p0.50:   3.158 ms/op
                 createUser·p0.90:   3.858 ms/op
                 createUser·p0.95:   4.043 ms/op
                 createUser·p0.99:   4.375 ms/op
                 createUser·p0.999:  9.140 ms/op
                 createUser·p0.9999: 13.959 ms/op
                 createUser·p1.00:   14.238 ms/op

Iteration   3: 3.181 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.558 ms/op
                 createUser·p0.50:   3.158 ms/op
                 createUser·p0.90:   3.826 ms/op
                 createUser·p0.95:   4.014 ms/op
                 createUser·p0.99:   4.342 ms/op
                 createUser·p0.999:  8.292 ms/op
                 createUser·p0.9999: 21.493 ms/op
                 createUser·p1.00:   22.020 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 303818
  mean =      3.163 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20732 
    [ 2.500,  5.000) = 281979 
    [ 5.000,  7.500) = 733 
    [ 7.500, 10.000) = 92 
    [10.000, 12.500) = 121 
    [12.500, 15.000) = 123 
    [15.000, 17.500) = 6 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.558 ms/op
     p(50.0000) =      3.146 ms/op
     p(90.0000) =      3.826 ms/op
     p(95.0000) =      4.014 ms/op
     p(99.0000) =      4.366 ms/op
     p(99.9000) =      8.971 ms/op
     p(99.9900) =     19.550 ms/op
     p(99.9990) =     21.854 ms/op
     p(99.9999) =     22.020 ms/op
    p(100.0000) =     22.020 ms/op


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
# Warmup Iteration   1: 3.986 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.980 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.965 ±(99.9%) 0.006 ms/op
Iteration   1: 2.984 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.755 ms/op
                 existUser·p0.50:   2.986 ms/op
                 existUser·p0.90:   3.473 ms/op
                 existUser·p0.95:   3.699 ms/op
                 existUser·p0.99:   4.260 ms/op
                 existUser·p0.999:  6.332 ms/op
                 existUser·p0.9999: 12.026 ms/op
                 existUser·p1.00:   12.222 ms/op

Iteration   2: 3.024 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.696 ms/op
                 existUser·p0.50:   3.002 ms/op
                 existUser·p0.90:   3.641 ms/op
                 existUser·p0.95:   3.830 ms/op
                 existUser·p0.99:   4.162 ms/op
                 existUser·p0.999:  5.603 ms/op
                 existUser·p0.9999: 13.669 ms/op
                 existUser·p1.00:   14.090 ms/op

Iteration   3: 2.956 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.718 ms/op
                 existUser·p0.50:   2.945 ms/op
                 existUser·p0.90:   3.502 ms/op
                 existUser·p0.95:   3.690 ms/op
                 existUser·p0.99:   4.067 ms/op
                 existUser·p0.999:  6.969 ms/op
                 existUser·p0.9999: 15.193 ms/op
                 existUser·p1.00:   15.745 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 321322
  mean =      2.988 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1741 
    [ 1.250,  2.500) = 32124 
    [ 2.500,  3.750) = 271333 
    [ 3.750,  5.000) = 15482 
    [ 5.000,  6.250) = 322 
    [ 6.250,  7.500) = 79 
    [ 7.500,  8.750) = 35 
    [ 8.750, 10.000) = 10 
    [10.000, 11.250) = 10 
    [11.250, 12.500) = 75 
    [12.500, 13.750) = 60 
    [13.750, 15.000) = 37 
    [15.000, 16.250) = 14 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.696 ms/op
     p(50.0000) =      2.978 ms/op
     p(90.0000) =      3.539 ms/op
     p(95.0000) =      3.752 ms/op
     p(99.0000) =      4.157 ms/op
     p(99.9000) =      6.231 ms/op
     p(99.9900) =     14.119 ms/op
     p(99.9990) =     15.603 ms/op
     p(99.9999) =     15.745 ms/op
    p(100.0000) =     15.745 ms/op


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
# Warmup Iteration   1: 4.144 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.200 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.066 ±(99.9%) 0.007 ms/op
Iteration   1: 3.019 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.274 ms/op
                 getUser·p0.50:   3.060 ms/op
                 getUser·p0.90:   3.539 ms/op
                 getUser·p0.95:   3.760 ms/op
                 getUser·p0.99:   4.219 ms/op
                 getUser·p0.999:  8.103 ms/op
                 getUser·p0.9999: 15.699 ms/op
                 getUser·p1.00:   16.204 ms/op

Iteration   2: 3.078 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.372 ms/op
                 getUser·p0.50:   3.056 ms/op
                 getUser·p0.90:   3.699 ms/op
                 getUser·p0.95:   3.940 ms/op
                 getUser·p0.99:   4.391 ms/op
                 getUser·p0.999:  6.236 ms/op
                 getUser·p0.9999: 16.142 ms/op
                 getUser·p1.00:   17.302 ms/op

Iteration   3: 3.118 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.768 ms/op
                 getUser·p0.50:   3.109 ms/op
                 getUser·p0.90:   3.813 ms/op
                 getUser·p0.95:   4.018 ms/op
                 getUser·p0.99:   4.399 ms/op
                 getUser·p0.999:  6.429 ms/op
                 getUser·p0.9999: 20.234 ms/op
                 getUser·p1.00:   20.709 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 312392
  mean =      3.071 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27560 
    [ 2.500,  5.000) = 283919 
    [ 5.000,  7.500) = 634 
    [ 7.500, 10.000) = 85 
    [10.000, 12.500) = 2 
    [12.500, 15.000) = 48 
    [15.000, 17.500) = 85 
    [17.500, 20.000) = 42 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.274 ms/op
     p(50.0000) =      3.068 ms/op
     p(90.0000) =      3.699 ms/op
     p(95.0000) =      3.924 ms/op
     p(99.0000) =      4.358 ms/op
     p(99.9000) =      6.837 ms/op
     p(99.9900) =     19.661 ms/op
     p(99.9990) =     20.603 ms/op
     p(99.9999) =     20.709 ms/op
    p(100.0000) =     20.709 ms/op


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
# Warmup Iteration   1: 5.204 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 4.135 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.926 ±(99.9%) 0.012 ms/op
Iteration   1: 4.015 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.120 ms/op
                 listUser·p0.50:   3.817 ms/op
                 listUser·p0.90:   5.341 ms/op
                 listUser·p0.95:   5.825 ms/op
                 listUser·p0.99:   6.980 ms/op
                 listUser·p0.999:  13.094 ms/op
                 listUser·p0.9999: 15.599 ms/op
                 listUser·p1.00:   16.007 ms/op

Iteration   2: 3.984 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.742 ms/op
                 listUser·p0.50:   3.813 ms/op
                 listUser·p0.90:   5.186 ms/op
                 listUser·p0.95:   5.734 ms/op
                 listUser·p0.99:   6.947 ms/op
                 listUser·p0.999:  15.948 ms/op
                 listUser·p0.9999: 23.495 ms/op
                 listUser·p1.00:   23.822 ms/op

Iteration   3: 4.034 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.877 ms/op
                 listUser·p0.50:   3.785 ms/op
                 listUser·p0.90:   5.341 ms/op
                 listUser·p0.95:   5.669 ms/op
                 listUser·p0.99:   6.979 ms/op
                 listUser·p0.999:  15.312 ms/op
                 listUser·p0.9999: 21.955 ms/op
                 listUser·p1.00:   23.396 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 239516
  mean =      4.011 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5072 
    [ 2.500,  5.000) = 197771 
    [ 5.000,  7.500) = 35437 
    [ 7.500, 10.000) = 835 
    [10.000, 12.500) = 72 
    [12.500, 15.000) = 131 
    [15.000, 17.500) = 82 
    [17.500, 20.000) = 45 
    [20.000, 22.500) = 42 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.742 ms/op
     p(50.0000) =      3.805 ms/op
     p(90.0000) =      5.300 ms/op
     p(95.0000) =      5.734 ms/op
     p(99.0000) =      6.971 ms/op
     p(99.9000) =     14.033 ms/op
     p(99.9900) =     22.679 ms/op
     p(99.9990) =     23.646 ms/op
     p(99.9999) =     23.822 ms/op
    p(100.0000) =     23.822 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.204 ± 1.001  ops/ms
ClientGrpc.existUser                       thrpt       3  10.698 ± 2.370  ops/ms
ClientGrpc.getUser                         thrpt       3  10.128 ± 2.422  ops/ms
ClientGrpc.listUser                        thrpt       3   8.040 ± 2.001  ops/ms
ClientGrpc.createUser                       avgt       3   3.161 ± 0.852   ms/op
ClientGrpc.existUser                        avgt       3   3.006 ± 0.321   ms/op
ClientGrpc.getUser                          avgt       3   3.155 ± 0.615   ms/op
ClientGrpc.listUser                         avgt       3   4.011 ± 0.926   ms/op
ClientGrpc.createUser                     sample  303818   3.163 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.558           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.146           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.826           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.014           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.366           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.971           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.550           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.020           ms/op
ClientGrpc.existUser                      sample  321322   2.988 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.696           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.978           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.539           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.752           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.157           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.231           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.119           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          15.745           ms/op
ClientGrpc.getUser                        sample  312392   3.071 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.274           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.068           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.699           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.924           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.358           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.837           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.661           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.709           ms/op
ClientGrpc.listUser                       sample  239516   4.011 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.742           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.805           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.300           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.734           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.971           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.033           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.679           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.822           ms/op
