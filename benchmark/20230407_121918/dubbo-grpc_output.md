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
# Warmup Iteration   1: 4.070 ops/ms
# Warmup Iteration   2: 8.336 ops/ms
# Warmup Iteration   3: 10.095 ops/ms
Iteration   1: 10.279 ops/ms
Iteration   2: 10.800 ops/ms
Iteration   3: 10.432 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.504 ±(99.9%) 4.884 ops/ms [Average]
  (min, avg, max) = (10.279, 10.504, 10.800), stdev = 0.268
  CI (99.9%): [5.620, 15.387] (assumes normal distribution)


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
# Warmup Iteration   1: 7.552 ops/ms
# Warmup Iteration   2: 10.479 ops/ms
# Warmup Iteration   3: 10.895 ops/ms
Iteration   1: 11.027 ops/ms
Iteration   2: 11.200 ops/ms
Iteration   3: 10.988 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.072 ±(99.9%) 2.057 ops/ms [Average]
  (min, avg, max) = (10.988, 11.072, 11.200), stdev = 0.113
  CI (99.9%): [9.014, 13.129] (assumes normal distribution)


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
# Warmup Iteration   1: 6.734 ops/ms
# Warmup Iteration   2: 9.935 ops/ms
# Warmup Iteration   3: 10.305 ops/ms
Iteration   1: 10.475 ops/ms
Iteration   2: 10.479 ops/ms
Iteration   3: 10.566 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.507 ±(99.9%) 0.937 ops/ms [Average]
  (min, avg, max) = (10.475, 10.507, 10.566), stdev = 0.051
  CI (99.9%): [9.569, 11.444] (assumes normal distribution)


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
# Warmup Iteration   1: 5.732 ops/ms
# Warmup Iteration   2: 7.758 ops/ms
# Warmup Iteration   3: 7.982 ops/ms
Iteration   1: 7.889 ops/ms
Iteration   2: 8.191 ops/ms
Iteration   3: 8.205 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.095 ±(99.9%) 3.256 ops/ms [Average]
  (min, avg, max) = (7.889, 8.095, 8.205), stdev = 0.178
  CI (99.9%): [4.839, 11.351] (assumes normal distribution)


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
# Warmup Iteration   1: 4.078 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.183 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.085 ±(99.9%) 0.003 ms/op
Iteration   1: 3.070 ±(99.9%) 0.008 ms/op
Iteration   2: 3.064 ±(99.9%) 0.003 ms/op
Iteration   3: 3.027 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.054 ±(99.9%) 0.423 ms/op [Average]
  (min, avg, max) = (3.027, 3.054, 3.070), stdev = 0.023
  CI (99.9%): [2.631, 3.477] (assumes normal distribution)


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
# Warmup Iteration   1: 4.101 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.924 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.851 ±(99.9%) 0.004 ms/op
Iteration   1: 2.830 ±(99.9%) 0.003 ms/op
Iteration   2: 2.915 ±(99.9%) 0.003 ms/op
Iteration   3: 2.951 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.899 ±(99.9%) 1.134 ms/op [Average]
  (min, avg, max) = (2.830, 2.899, 2.951), stdev = 0.062
  CI (99.9%): [1.765, 4.033] (assumes normal distribution)


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
# Warmup Iteration   1: 4.079 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.165 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.074 ±(99.9%) 0.002 ms/op
Iteration   1: 3.017 ±(99.9%) 0.003 ms/op
Iteration   2: 3.036 ±(99.9%) 0.003 ms/op
Iteration   3: 3.006 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.020 ±(99.9%) 0.279 ms/op [Average]
  (min, avg, max) = (3.006, 3.020, 3.036), stdev = 0.015
  CI (99.9%): [2.741, 3.298] (assumes normal distribution)


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
# Warmup Iteration   1: 5.157 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 4.117 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.964 ±(99.9%) 0.012 ms/op
Iteration   1: 3.886 ±(99.9%) 0.014 ms/op
Iteration   2: 3.936 ±(99.9%) 0.018 ms/op
Iteration   3: 3.923 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.915 ±(99.9%) 0.469 ms/op [Average]
  (min, avg, max) = (3.886, 3.915, 3.936), stdev = 0.026
  CI (99.9%): [3.446, 4.384] (assumes normal distribution)


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
# Warmup Iteration   1: 4.180 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.190 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.019 ±(99.9%) 0.006 ms/op
Iteration   1: 3.058 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.673 ms/op
                 createUser·p0.50:   3.027 ms/op
                 createUser·p0.90:   3.535 ms/op
                 createUser·p0.95:   3.711 ms/op
                 createUser·p0.99:   4.202 ms/op
                 createUser·p0.999:  7.193 ms/op
                 createUser·p0.9999: 16.278 ms/op
                 createUser·p1.00:   16.777 ms/op

Iteration   2: 2.991 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.768 ms/op
                 createUser·p0.50:   2.978 ms/op
                 createUser·p0.90:   3.314 ms/op
                 createUser·p0.95:   3.437 ms/op
                 createUser·p0.99:   4.141 ms/op
                 createUser·p0.999:  8.503 ms/op
                 createUser·p0.9999: 17.738 ms/op
                 createUser·p1.00:   18.252 ms/op

Iteration   3: 3.059 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.734 ms/op
                 createUser·p0.50:   3.023 ms/op
                 createUser·p0.90:   3.568 ms/op
                 createUser·p0.95:   3.686 ms/op
                 createUser·p0.99:   4.342 ms/op
                 createUser·p0.999:  10.197 ms/op
                 createUser·p0.9999: 19.562 ms/op
                 createUser·p1.00:   19.661 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 316230
  mean =      3.036 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 236 
    [ 1.250,  2.500) = 15668 
    [ 2.500,  3.750) = 289755 
    [ 3.750,  5.000) = 9164 
    [ 5.000,  6.250) = 754 
    [ 6.250,  7.500) = 231 
    [ 7.500,  8.750) = 140 
    [ 8.750, 10.000) = 45 
    [10.000, 11.250) = 18 
    [11.250, 12.500) = 7 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 36 
    [15.000, 16.250) = 55 
    [16.250, 17.500) = 54 
    [17.500, 18.750) = 47 

  Percentiles, ms/op:
      p(0.0000) =      0.673 ms/op
     p(50.0000) =      3.002 ms/op
     p(90.0000) =      3.494 ms/op
     p(95.0000) =      3.654 ms/op
     p(99.0000) =      4.211 ms/op
     p(99.9000) =      8.315 ms/op
     p(99.9900) =     18.252 ms/op
     p(99.9990) =     19.628 ms/op
     p(99.9999) =     19.661 ms/op
    p(100.0000) =     19.661 ms/op


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
# Warmup Iteration   1: 3.867 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.104 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.020 ±(99.9%) 0.006 ms/op
Iteration   1: 2.983 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.845 ms/op
                 existUser·p0.50:   2.961 ms/op
                 existUser·p0.90:   3.396 ms/op
                 existUser·p0.95:   3.535 ms/op
                 existUser·p0.99:   4.076 ms/op
                 existUser·p0.999:  5.839 ms/op
                 existUser·p0.9999: 19.857 ms/op
                 existUser·p1.00:   20.087 ms/op

Iteration   2: 3.022 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.787 ms/op
                 existUser·p0.50:   2.978 ms/op
                 existUser·p0.90:   3.482 ms/op
                 existUser·p0.95:   3.690 ms/op
                 existUser·p0.99:   4.309 ms/op
                 existUser·p0.999:  11.305 ms/op
                 existUser·p0.9999: 14.544 ms/op
                 existUser·p1.00:   15.008 ms/op

Iteration   3: 2.945 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.826 ms/op
                 existUser·p0.50:   2.945 ms/op
                 existUser·p0.90:   3.408 ms/op
                 existUser·p0.95:   3.572 ms/op
                 existUser·p0.99:   4.125 ms/op
                 existUser·p0.999:  6.660 ms/op
                 existUser·p0.9999: 16.031 ms/op
                 existUser·p1.00:   16.548 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 321489
  mean =      2.983 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21362 
    [ 2.500,  5.000) = 299179 
    [ 5.000,  7.500) = 679 
    [ 7.500, 10.000) = 26 
    [10.000, 12.500) = 52 
    [12.500, 15.000) = 114 
    [15.000, 17.500) = 45 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.787 ms/op
     p(50.0000) =      2.961 ms/op
     p(90.0000) =      3.424 ms/op
     p(95.0000) =      3.600 ms/op
     p(99.0000) =      4.162 ms/op
     p(99.9000) =      6.918 ms/op
     p(99.9900) =     18.918 ms/op
     p(99.9990) =     19.981 ms/op
     p(99.9999) =     20.087 ms/op
    p(100.0000) =     20.087 ms/op


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
# Warmup Iteration   1: 4.180 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.148 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.038 ±(99.9%) 0.006 ms/op
Iteration   1: 3.042 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.983 ms/op
                 getUser·p0.50:   3.019 ms/op
                 getUser·p0.90:   3.633 ms/op
                 getUser·p0.95:   3.850 ms/op
                 getUser·p0.99:   4.530 ms/op
                 getUser·p0.999:  7.602 ms/op
                 getUser·p0.9999: 13.098 ms/op
                 getUser·p1.00:   13.451 ms/op

Iteration   2: 3.048 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.307 ms/op
                 getUser·p0.50:   3.023 ms/op
                 getUser·p0.90:   3.551 ms/op
                 getUser·p0.95:   3.740 ms/op
                 getUser·p0.99:   4.678 ms/op
                 getUser·p0.999:  6.752 ms/op
                 getUser·p0.9999: 18.941 ms/op
                 getUser·p1.00:   20.546 ms/op

Iteration   3: 2.987 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.676 ms/op
                 getUser·p0.50:   2.982 ms/op
                 getUser·p0.90:   3.363 ms/op
                 getUser·p0.95:   3.539 ms/op
                 getUser·p0.99:   4.211 ms/op
                 getUser·p0.999:  7.045 ms/op
                 getUser·p0.9999: 17.302 ms/op
                 getUser·p1.00:   17.727 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 317069
  mean =      3.025 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21403 
    [ 2.500,  5.000) = 294253 
    [ 5.000,  7.500) = 1124 
    [ 7.500, 10.000) = 97 
    [10.000, 12.500) = 35 
    [12.500, 15.000) = 30 
    [15.000, 17.500) = 91 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.307 ms/op
     p(50.0000) =      3.006 ms/op
     p(90.0000) =      3.523 ms/op
     p(95.0000) =      3.736 ms/op
     p(99.0000) =      4.483 ms/op
     p(99.9000) =      7.340 ms/op
     p(99.9900) =     18.153 ms/op
     p(99.9990) =     20.277 ms/op
     p(99.9999) =     20.546 ms/op
    p(100.0000) =     20.546 ms/op


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
# Warmup Iteration   1: 4.643 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 4.254 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.924 ±(99.9%) 0.010 ms/op
Iteration   1: 4.033 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.239 ms/op
                 listUser·p0.50:   3.838 ms/op
                 listUser·p0.90:   5.276 ms/op
                 listUser·p0.95:   5.964 ms/op
                 listUser·p0.99:   7.223 ms/op
                 listUser·p0.999:  14.158 ms/op
                 listUser·p0.9999: 17.926 ms/op
                 listUser·p1.00:   18.383 ms/op

Iteration   2: 3.904 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.327 ms/op
                 listUser·p0.50:   3.781 ms/op
                 listUser·p0.90:   4.522 ms/op
                 listUser·p0.95:   5.292 ms/op
                 listUser·p0.99:   6.726 ms/op
                 listUser·p0.999:  14.516 ms/op
                 listUser·p0.9999: 18.987 ms/op
                 listUser·p1.00:   19.595 ms/op

Iteration   3: 3.899 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.241 ms/op
                 listUser·p0.50:   3.744 ms/op
                 listUser·p0.90:   4.792 ms/op
                 listUser·p0.95:   5.784 ms/op
                 listUser·p0.99:   6.660 ms/op
                 listUser·p0.999:  16.285 ms/op
                 listUser·p0.9999: 23.134 ms/op
                 listUser·p1.00:   23.495 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 243375
  mean =      3.944 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3692 
    [ 2.500,  5.000) = 217040 
    [ 5.000,  7.500) = 21532 
    [ 7.500, 10.000) = 648 
    [10.000, 12.500) = 133 
    [12.500, 15.000) = 83 
    [15.000, 17.500) = 151 
    [17.500, 20.000) = 57 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.239 ms/op
     p(50.0000) =      3.785 ms/op
     p(90.0000) =      4.923 ms/op
     p(95.0000) =      5.759 ms/op
     p(99.0000) =      6.849 ms/op
     p(99.9000) =     15.116 ms/op
     p(99.9900) =     22.632 ms/op
     p(99.9990) =     23.339 ms/op
     p(99.9999) =     23.495 ms/op
    p(100.0000) =     23.495 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.504 ± 4.884  ops/ms
ClientGrpc.existUser                       thrpt       3  11.072 ± 2.057  ops/ms
ClientGrpc.getUser                         thrpt       3  10.507 ± 0.937  ops/ms
ClientGrpc.listUser                        thrpt       3   8.095 ± 3.256  ops/ms
ClientGrpc.createUser                       avgt       3   3.054 ± 0.423   ms/op
ClientGrpc.existUser                        avgt       3   2.899 ± 1.134   ms/op
ClientGrpc.getUser                          avgt       3   3.020 ± 0.279   ms/op
ClientGrpc.listUser                         avgt       3   3.915 ± 0.469   ms/op
ClientGrpc.createUser                     sample  316230   3.036 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.673           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.002           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.494           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.654           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.211           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.315           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.252           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          19.661           ms/op
ClientGrpc.existUser                      sample  321489   2.983 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.787           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.961           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.424           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.600           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.162           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.918           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.918           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.087           ms/op
ClientGrpc.getUser                        sample  317069   3.025 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.307           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.006           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.523           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.736           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.483           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.340           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.153           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.546           ms/op
ClientGrpc.listUser                       sample  243375   3.944 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.239           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.785           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.923           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.759           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.849           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.116           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.632           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.495           ms/op
