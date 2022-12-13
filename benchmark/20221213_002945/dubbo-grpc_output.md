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
# Warmup Iteration   1: 4.709 ops/ms
# Warmup Iteration   2: 9.328 ops/ms
# Warmup Iteration   3: 10.665 ops/ms
Iteration   1: 10.528 ops/ms
Iteration   2: 10.626 ops/ms
Iteration   3: 10.100 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.418 ±(99.9%) 5.108 ops/ms [Average]
  (min, avg, max) = (10.100, 10.418, 10.626), stdev = 0.280
  CI (99.9%): [5.310, 15.526] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 8.038 ops/ms
# Warmup Iteration   2: 10.987 ops/ms
# Warmup Iteration   3: 11.257 ops/ms
Iteration   1: 11.051 ops/ms
Iteration   2: 11.537 ops/ms
Iteration   3: 11.280 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.289 ±(99.9%) 4.442 ops/ms [Average]
  (min, avg, max) = (11.051, 11.289, 11.537), stdev = 0.243
  CI (99.9%): [6.847, 15.731] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.765 ops/ms
# Warmup Iteration   2: 10.596 ops/ms
# Warmup Iteration   3: 10.611 ops/ms
Iteration   1: 10.363 ops/ms
Iteration   2: 10.700 ops/ms
Iteration   3: 10.828 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.630 ±(99.9%) 4.386 ops/ms [Average]
  (min, avg, max) = (10.363, 10.630, 10.828), stdev = 0.240
  CI (99.9%): [6.245, 15.016] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.930 ops/ms
# Warmup Iteration   2: 7.999 ops/ms
# Warmup Iteration   3: 8.007 ops/ms
Iteration   1: 8.042 ops/ms
Iteration   2: 8.034 ops/ms
Iteration   3: 8.125 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.067 ±(99.9%) 0.921 ops/ms [Average]
  (min, avg, max) = (8.034, 8.067, 8.125), stdev = 0.050
  CI (99.9%): [7.146, 8.987] (assumes normal distribution)


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
# Warmup Iteration   1: 3.827 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 3.041 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.042 ±(99.9%) 0.002 ms/op
Iteration   1: 3.015 ±(99.9%) 0.002 ms/op
Iteration   2: 2.993 ±(99.9%) 0.002 ms/op
Iteration   3: 3.052 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.020 ±(99.9%) 0.545 ms/op [Average]
  (min, avg, max) = (2.993, 3.020, 3.052), stdev = 0.030
  CI (99.9%): [2.475, 3.566] (assumes normal distribution)


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
# Warmup Iteration   1: 3.579 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.005 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.838 ±(99.9%) 0.003 ms/op
Iteration   1: 2.916 ±(99.9%) 0.002 ms/op
Iteration   2: 2.842 ±(99.9%) 0.002 ms/op
Iteration   3: 2.888 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.882 ±(99.9%) 0.686 ms/op [Average]
  (min, avg, max) = (2.842, 2.882, 2.916), stdev = 0.038
  CI (99.9%): [2.196, 3.568] (assumes normal distribution)


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
# Warmup Iteration   1: 3.845 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 3.127 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.000 ±(99.9%) 0.003 ms/op
Iteration   1: 3.109 ±(99.9%) 0.002 ms/op
Iteration   2: 2.995 ±(99.9%) 0.002 ms/op
Iteration   3: 3.071 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.058 ±(99.9%) 1.059 ms/op [Average]
  (min, avg, max) = (2.995, 3.058, 3.109), stdev = 0.058
  CI (99.9%): [1.999, 4.118] (assumes normal distribution)


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
# Warmup Iteration   1: 4.291 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 4.164 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 3.987 ±(99.9%) 0.009 ms/op
Iteration   1: 4.041 ±(99.9%) 0.007 ms/op
Iteration   2: 4.058 ±(99.9%) 0.026 ms/op
Iteration   3: 4.185 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.095 ±(99.9%) 1.437 ms/op [Average]
  (min, avg, max) = (4.041, 4.095, 4.185), stdev = 0.079
  CI (99.9%): [2.657, 5.532] (assumes normal distribution)


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
# Warmup Iteration   1: 3.992 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.121 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.993 ±(99.9%) 0.006 ms/op
Iteration   1: 2.971 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.817 ms/op
                 createUser·p0.50:   2.978 ms/op
                 createUser·p0.90:   3.498 ms/op
                 createUser·p0.95:   3.707 ms/op
                 createUser·p0.99:   4.227 ms/op
                 createUser·p0.999:  7.526 ms/op
                 createUser·p0.9999: 10.595 ms/op
                 createUser·p1.00:   10.895 ms/op

Iteration   2: 3.134 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.368 ms/op
                 createUser·p0.50:   3.117 ms/op
                 createUser·p0.90:   3.817 ms/op
                 createUser·p0.95:   3.961 ms/op
                 createUser·p0.99:   4.194 ms/op
                 createUser·p0.999:  6.930 ms/op
                 createUser·p0.9999: 12.714 ms/op
                 createUser·p1.00:   12.993 ms/op

Iteration   3: 3.088 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.580 ms/op
                 createUser·p0.50:   3.047 ms/op
                 createUser·p0.90:   3.678 ms/op
                 createUser·p0.95:   3.850 ms/op
                 createUser·p0.99:   4.149 ms/op
                 createUser·p0.999:  13.484 ms/op
                 createUser·p0.9999: 16.225 ms/op
                 createUser·p1.00:   19.005 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 313641
  mean =      3.063 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1144 
    [ 1.250,  2.500) = 28543 
    [ 2.500,  3.750) = 258294 
    [ 3.750,  5.000) = 24787 
    [ 5.000,  6.250) = 334 
    [ 6.250,  7.500) = 157 
    [ 7.500,  8.750) = 77 
    [ 8.750, 10.000) = 53 
    [10.000, 11.250) = 73 
    [11.250, 12.500) = 46 
    [12.500, 13.750) = 55 
    [13.750, 15.000) = 61 
    [15.000, 16.250) = 7 
    [16.250, 17.500) = 6 
    [17.500, 18.750) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.368 ms/op
     p(50.0000) =      3.039 ms/op
     p(90.0000) =      3.690 ms/op
     p(95.0000) =      3.875 ms/op
     p(99.0000) =      4.190 ms/op
     p(99.9000) =      8.293 ms/op
     p(99.9900) =     14.854 ms/op
     p(99.9990) =     18.533 ms/op
     p(99.9999) =     19.005 ms/op
    p(100.0000) =     19.005 ms/op


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
# Warmup Iteration   1: 3.704 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.999 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.945 ±(99.9%) 0.006 ms/op
Iteration   1: 2.942 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.731 ms/op
                 existUser·p0.50:   2.966 ms/op
                 existUser·p0.90:   3.723 ms/op
                 existUser·p0.95:   3.891 ms/op
                 existUser·p0.99:   4.235 ms/op
                 existUser·p0.999:  6.047 ms/op
                 existUser·p0.9999: 12.161 ms/op
                 existUser·p1.00:   12.927 ms/op

Iteration   2: 2.922 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.725 ms/op
                 existUser·p0.50:   2.916 ms/op
                 existUser·p0.90:   3.469 ms/op
                 existUser·p0.95:   3.686 ms/op
                 existUser·p0.99:   4.383 ms/op
                 existUser·p0.999:  6.976 ms/op
                 existUser·p0.9999: 13.387 ms/op
                 existUser·p1.00:   13.910 ms/op

Iteration   3: 2.912 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.679 ms/op
                 existUser·p0.50:   2.929 ms/op
                 existUser·p0.90:   3.555 ms/op
                 existUser·p0.95:   3.760 ms/op
                 existUser·p0.99:   4.166 ms/op
                 existUser·p0.999:  6.440 ms/op
                 existUser·p0.9999: 16.206 ms/op
                 existUser·p1.00:   16.450 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 328025
  mean =      2.925 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3677 
    [ 1.250,  2.500) = 51627 
    [ 2.500,  3.750) = 252572 
    [ 3.750,  5.000) = 19217 
    [ 5.000,  6.250) = 513 
    [ 6.250,  7.500) = 206 
    [ 7.500,  8.750) = 10 
    [ 8.750, 10.000) = 11 
    [10.000, 11.250) = 17 
    [11.250, 12.500) = 77 
    [12.500, 13.750) = 60 
    [13.750, 15.000) = 16 
    [15.000, 16.250) = 12 
    [16.250, 17.500) = 10 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.679 ms/op
     p(50.0000) =      2.933 ms/op
     p(90.0000) =      3.600 ms/op
     p(95.0000) =      3.805 ms/op
     p(99.0000) =      4.260 ms/op
     p(99.9000) =      6.742 ms/op
     p(99.9900) =     13.992 ms/op
     p(99.9990) =     16.412 ms/op
     p(99.9999) =     16.450 ms/op
    p(100.0000) =     16.450 ms/op


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
# Warmup Iteration   1: 3.882 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.076 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.994 ±(99.9%) 0.006 ms/op
Iteration   1: 3.044 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.680 ms/op
                 getUser·p0.50:   3.035 ms/op
                 getUser·p0.90:   3.613 ms/op
                 getUser·p0.95:   3.760 ms/op
                 getUser·p0.99:   4.129 ms/op
                 getUser·p0.999:  6.144 ms/op
                 getUser·p0.9999: 14.926 ms/op
                 getUser·p1.00:   15.466 ms/op

Iteration   2: 3.002 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.644 ms/op
                 getUser·p0.50:   3.002 ms/op
                 getUser·p0.90:   3.518 ms/op
                 getUser·p0.95:   3.740 ms/op
                 getUser·p0.99:   4.170 ms/op
                 getUser·p0.999:  8.253 ms/op
                 getUser·p0.9999: 17.727 ms/op
                 getUser·p1.00:   19.530 ms/op

Iteration   3: 2.984 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.732 ms/op
                 getUser·p0.50:   3.006 ms/op
                 getUser·p0.90:   3.453 ms/op
                 getUser·p0.95:   3.650 ms/op
                 getUser·p0.99:   4.227 ms/op
                 getUser·p0.999:  7.113 ms/op
                 getUser·p0.9999: 29.533 ms/op
                 getUser·p1.00:   30.638 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 318740
  mean =      3.010 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 28859 
    [ 2.500,  5.000) = 288841 
    [ 5.000,  7.500) = 804 
    [ 7.500, 10.000) = 62 
    [10.000, 12.500) = 13 
    [12.500, 15.000) = 26 
    [15.000, 17.500) = 83 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 27 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.644 ms/op
     p(50.0000) =      3.015 ms/op
     p(90.0000) =      3.535 ms/op
     p(95.0000) =      3.727 ms/op
     p(99.0000) =      4.166 ms/op
     p(99.9000) =      6.670 ms/op
     p(99.9900) =     27.927 ms/op
     p(99.9990) =     30.540 ms/op
     p(99.9999) =     30.638 ms/op
    p(100.0000) =     30.638 ms/op


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
# Warmup Iteration   1: 4.906 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 4.123 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.021 ±(99.9%) 0.011 ms/op
Iteration   1: 4.044 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.281 ms/op
                 listUser·p0.50:   3.867 ms/op
                 listUser·p0.90:   5.128 ms/op
                 listUser·p0.95:   5.612 ms/op
                 listUser·p0.99:   7.004 ms/op
                 listUser·p0.999:  14.675 ms/op
                 listUser·p0.9999: 19.988 ms/op
                 listUser·p1.00:   20.972 ms/op

Iteration   2: 3.982 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.161 ms/op
                 listUser·p0.50:   3.813 ms/op
                 listUser·p0.90:   5.104 ms/op
                 listUser·p0.95:   5.734 ms/op
                 listUser·p0.99:   6.750 ms/op
                 listUser·p0.999:  13.074 ms/op
                 listUser·p0.9999: 16.809 ms/op
                 listUser·p1.00:   17.990 ms/op

Iteration   3: 3.865 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.536 ms/op
                 listUser·p0.50:   3.740 ms/op
                 listUser·p0.90:   4.760 ms/op
                 listUser·p0.95:   5.382 ms/op
                 listUser·p0.99:   6.463 ms/op
                 listUser·p0.999:  13.738 ms/op
                 listUser·p0.9999: 19.839 ms/op
                 listUser·p1.00:   21.561 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 242154
  mean =      3.962 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3839 
    [ 2.500,  5.000) = 213500 
    [ 5.000,  7.500) = 23727 
    [ 7.500, 10.000) = 633 
    [10.000, 12.500) = 151 
    [12.500, 15.000) = 168 
    [15.000, 17.500) = 66 
    [17.500, 20.000) = 63 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.281 ms/op
     p(50.0000) =      3.805 ms/op
     p(90.0000) =      5.022 ms/op
     p(95.0000) =      5.595 ms/op
     p(99.0000) =      6.717 ms/op
     p(99.9000) =     13.362 ms/op
     p(99.9900) =     19.759 ms/op
     p(99.9990) =     20.737 ms/op
     p(99.9999) =     21.561 ms/op
    p(100.0000) =     21.561 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.418 ± 5.108  ops/ms
ClientGrpc.existUser                       thrpt       3  11.289 ± 4.442  ops/ms
ClientGrpc.getUser                         thrpt       3  10.630 ± 4.386  ops/ms
ClientGrpc.listUser                        thrpt       3   8.067 ± 0.921  ops/ms
ClientGrpc.createUser                       avgt       3   3.020 ± 0.545   ms/op
ClientGrpc.existUser                        avgt       3   2.882 ± 0.686   ms/op
ClientGrpc.getUser                          avgt       3   3.058 ± 1.059   ms/op
ClientGrpc.listUser                         avgt       3   4.095 ± 1.437   ms/op
ClientGrpc.createUser                     sample  313641   3.063 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.368           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.039           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.690           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.875           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.190           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.293           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          14.854           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          19.005           ms/op
ClientGrpc.existUser                      sample  328025   2.925 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.679           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.933           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.600           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.805           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.260           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.742           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          13.992           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          16.450           ms/op
ClientGrpc.getUser                        sample  318740   3.010 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.644           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.015           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.535           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.727           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.166           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.670           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          27.927           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          30.638           ms/op
ClientGrpc.listUser                       sample  242154   3.962 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.281           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.805           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.022           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.595           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.717           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.362           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          19.759           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          21.561           ms/op
