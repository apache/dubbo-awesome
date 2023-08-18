# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.442 ops/ms
# Warmup Iteration   2: 9.266 ops/ms
# Warmup Iteration   3: 9.956 ops/ms
Iteration   1: 10.494 ops/ms
Iteration   2: 10.353 ops/ms
Iteration   3: 10.666 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.504 ±(99.9%) 2.863 ops/ms [Average]
  (min, avg, max) = (10.353, 10.504, 10.666), stdev = 0.157
  CI (99.9%): [7.641, 13.367] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.528 ops/ms
# Warmup Iteration   2: 10.677 ops/ms
# Warmup Iteration   3: 11.015 ops/ms
Iteration   1: 11.469 ops/ms
Iteration   2: 11.236 ops/ms
Iteration   3: 11.062 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.256 ±(99.9%) 3.726 ops/ms [Average]
  (min, avg, max) = (11.062, 11.256, 11.469), stdev = 0.204
  CI (99.9%): [7.530, 14.981] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.247 ops/ms
# Warmup Iteration   2: 10.105 ops/ms
# Warmup Iteration   3: 10.439 ops/ms
Iteration   1: 10.385 ops/ms
Iteration   2: 10.593 ops/ms
Iteration   3: 10.490 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.489 ±(99.9%) 1.898 ops/ms [Average]
  (min, avg, max) = (10.385, 10.489, 10.593), stdev = 0.104
  CI (99.9%): [8.591, 12.387] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.360 ops/ms
# Warmup Iteration   2: 7.676 ops/ms
# Warmup Iteration   3: 8.220 ops/ms
Iteration   1: 8.463 ops/ms
Iteration   2: 8.310 ops/ms
Iteration   3: 8.042 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.272 ±(99.9%) 3.889 ops/ms [Average]
  (min, avg, max) = (8.042, 8.272, 8.463), stdev = 0.213
  CI (99.9%): [4.383, 12.161] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.134 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.121 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.041 ±(99.9%) 0.004 ms/op
Iteration   1: 3.061 ±(99.9%) 0.009 ms/op
Iteration   2: 3.013 ±(99.9%) 0.002 ms/op
Iteration   3: 2.985 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.019 ±(99.9%) 0.695 ms/op [Average]
  (min, avg, max) = (2.985, 3.019, 3.061), stdev = 0.038
  CI (99.9%): [2.325, 3.714] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.994 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.971 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 2.893 ±(99.9%) 0.003 ms/op
Iteration   1: 2.864 ±(99.9%) 0.003 ms/op
Iteration   2: 2.843 ±(99.9%) 0.004 ms/op
Iteration   3: 2.823 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.843 ±(99.9%) 0.376 ms/op [Average]
  (min, avg, max) = (2.823, 2.843, 2.864), stdev = 0.021
  CI (99.9%): [2.468, 3.219] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 3.988 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 3.136 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.058 ±(99.9%) 0.004 ms/op
Iteration   1: 3.037 ±(99.9%) 0.005 ms/op
Iteration   2: 3.075 ±(99.9%) 0.002 ms/op
Iteration   3: 3.011 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.041 ±(99.9%) 0.586 ms/op [Average]
  (min, avg, max) = (3.011, 3.041, 3.075), stdev = 0.032
  CI (99.9%): [2.455, 3.627] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.066 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 4.106 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.965 ±(99.9%) 0.019 ms/op
Iteration   1: 3.922 ±(99.9%) 0.016 ms/op
Iteration   2: 3.952 ±(99.9%) 0.012 ms/op
Iteration   3: 3.937 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.937 ±(99.9%) 0.274 ms/op [Average]
  (min, avg, max) = (3.922, 3.937, 3.952), stdev = 0.015
  CI (99.9%): [3.663, 4.212] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.078 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.257 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.019 ±(99.9%) 0.006 ms/op
Iteration   1: 2.957 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.665 ms/op
                 createUser·p0.50:   2.978 ms/op
                 createUser·p0.90:   3.518 ms/op
                 createUser·p0.95:   3.764 ms/op
                 createUser·p0.99:   4.735 ms/op
                 createUser·p0.999:  9.263 ms/op
                 createUser·p0.9999: 13.962 ms/op
                 createUser·p1.00:   14.729 ms/op

Iteration   2: 3.073 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.916 ms/op
                 createUser·p0.50:   3.023 ms/op
                 createUser·p0.90:   3.637 ms/op
                 createUser·p0.95:   3.842 ms/op
                 createUser·p0.99:   4.694 ms/op
                 createUser·p0.999:  9.093 ms/op
                 createUser·p0.9999: 14.814 ms/op
                 createUser·p1.00:   15.385 ms/op

Iteration   3: 3.119 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.610 ms/op
                 createUser·p0.50:   3.068 ms/op
                 createUser·p0.90:   3.699 ms/op
                 createUser·p0.95:   3.883 ms/op
                 createUser·p0.99:   4.563 ms/op
                 createUser·p0.999:  16.056 ms/op
                 createUser·p0.9999: 28.410 ms/op
                 createUser·p1.00:   28.606 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 314851
  mean =      3.048 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27926 
    [ 2.500,  5.000) = 284777 
    [ 5.000,  7.500) = 1630 
    [ 7.500, 10.000) = 206 
    [10.000, 12.500) = 84 
    [12.500, 15.000) = 94 
    [15.000, 17.500) = 64 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.610 ms/op
     p(50.0000) =      3.019 ms/op
     p(90.0000) =      3.629 ms/op
     p(95.0000) =      3.842 ms/op
     p(99.0000) =      4.669 ms/op
     p(99.9000) =      9.903 ms/op
     p(99.9900) =     27.919 ms/op
     p(99.9990) =     28.536 ms/op
     p(99.9999) =     28.606 ms/op
    p(100.0000) =     28.606 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.876 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.080 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.861 ±(99.9%) 0.006 ms/op
Iteration   1: 2.916 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.726 ms/op
                 existUser·p0.50:   2.912 ms/op
                 existUser·p0.90:   3.346 ms/op
                 existUser·p0.95:   3.531 ms/op
                 existUser·p0.99:   4.096 ms/op
                 existUser·p0.999:  8.421 ms/op
                 existUser·p0.9999: 13.992 ms/op
                 existUser·p1.00:   14.221 ms/op

Iteration   2: 2.976 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.671 ms/op
                 existUser·p0.50:   2.937 ms/op
                 existUser·p0.90:   3.514 ms/op
                 existUser·p0.95:   3.760 ms/op
                 existUser·p0.99:   4.149 ms/op
                 existUser·p0.999:  7.455 ms/op
                 existUser·p0.9999: 18.850 ms/op
                 existUser·p1.00:   19.038 ms/op

Iteration   3: 2.932 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.696 ms/op
                 existUser·p0.50:   2.896 ms/op
                 existUser·p0.90:   3.334 ms/op
                 existUser·p0.95:   3.674 ms/op
                 existUser·p0.99:   4.497 ms/op
                 existUser·p0.999:  10.191 ms/op
                 existUser·p0.9999: 17.727 ms/op
                 existUser·p1.00:   17.957 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 326069
  mean =      2.941 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1434 
    [ 1.250,  2.500) = 29786 
    [ 2.500,  3.750) = 282010 
    [ 3.750,  5.000) = 11472 
    [ 5.000,  6.250) = 607 
    [ 6.250,  7.500) = 295 
    [ 7.500,  8.750) = 141 
    [ 8.750, 10.000) = 71 
    [10.000, 11.250) = 59 
    [11.250, 12.500) = 64 
    [12.500, 13.750) = 9 
    [13.750, 15.000) = 25 
    [15.000, 16.250) = 6 
    [16.250, 17.500) = 40 
    [17.500, 18.750) = 33 

  Percentiles, ms/op:
      p(0.0000) =      0.671 ms/op
     p(50.0000) =      2.912 ms/op
     p(90.0000) =      3.408 ms/op
     p(95.0000) =      3.654 ms/op
     p(99.0000) =      4.260 ms/op
     p(99.9000) =      8.733 ms/op
     p(99.9900) =     18.189 ms/op
     p(99.9990) =     18.997 ms/op
     p(99.9999) =     19.038 ms/op
    p(100.0000) =     19.038 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.184 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.109 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.050 ±(99.9%) 0.006 ms/op
Iteration   1: 3.027 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.849 ms/op
                 getUser·p0.50:   2.990 ms/op
                 getUser·p0.90:   3.580 ms/op
                 getUser·p0.95:   3.813 ms/op
                 getUser·p0.99:   4.694 ms/op
                 getUser·p0.999:  8.888 ms/op
                 getUser·p0.9999: 13.590 ms/op
                 getUser·p1.00:   14.057 ms/op

Iteration   2: 3.000 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.433 ms/op
                 getUser·p0.50:   2.949 ms/op
                 getUser·p0.90:   3.404 ms/op
                 getUser·p0.95:   3.637 ms/op
                 getUser·p0.99:   4.973 ms/op
                 getUser·p0.999:  13.167 ms/op
                 getUser·p0.9999: 25.526 ms/op
                 getUser·p1.00:   25.690 ms/op

Iteration   3: 3.045 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.583 ms/op
                 getUser·p0.50:   2.998 ms/op
                 getUser·p0.90:   3.609 ms/op
                 getUser·p0.95:   3.867 ms/op
                 getUser·p0.99:   4.751 ms/op
                 getUser·p0.999:  8.781 ms/op
                 getUser·p0.9999: 29.049 ms/op
                 getUser·p1.00:   30.802 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 317132
  mean =      3.024 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24545 
    [ 2.500,  5.000) = 290058 
    [ 5.000,  7.500) = 1818 
    [ 7.500, 10.000) = 393 
    [10.000, 12.500) = 82 
    [12.500, 15.000) = 79 
    [15.000, 17.500) = 55 
    [17.500, 20.000) = 35 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 
    [27.500, 30.000) = 24 
    [30.000, 32.500) = 8 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.433 ms/op
     p(50.0000) =      2.978 ms/op
     p(90.0000) =      3.531 ms/op
     p(95.0000) =      3.789 ms/op
     p(99.0000) =      4.776 ms/op
     p(99.9000) =     10.088 ms/op
     p(99.9900) =     28.298 ms/op
     p(99.9990) =     30.698 ms/op
     p(99.9999) =     30.802 ms/op
    p(100.0000) =     30.802 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.770 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 4.277 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.023 ±(99.9%) 0.012 ms/op
Iteration   1: 3.950 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.966 ms/op
                 listUser·p0.50:   3.797 ms/op
                 listUser·p0.90:   4.710 ms/op
                 listUser·p0.95:   5.685 ms/op
                 listUser·p0.99:   6.947 ms/op
                 listUser·p0.999:  15.270 ms/op
                 listUser·p0.9999: 22.607 ms/op
                 listUser·p1.00:   23.036 ms/op

Iteration   2: 3.932 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.012 ms/op
                 listUser·p0.50:   3.736 ms/op
                 listUser·p0.90:   4.997 ms/op
                 listUser·p0.95:   5.628 ms/op
                 listUser·p0.99:   7.086 ms/op
                 listUser·p0.999:  16.344 ms/op
                 listUser·p0.9999: 21.786 ms/op
                 listUser·p1.00:   23.331 ms/op

Iteration   3: 4.006 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.982 ms/op
                 listUser·p0.50:   3.793 ms/op
                 listUser·p0.90:   5.202 ms/op
                 listUser·p0.95:   5.923 ms/op
                 listUser·p0.99:   7.209 ms/op
                 listUser·p0.999:  19.333 ms/op
                 listUser·p0.9999: 26.608 ms/op
                 listUser·p1.00:   27.329 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 242386
  mean =      3.963 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2884 
    [ 2.500,  5.000) = 215447 
    [ 5.000,  7.500) = 22382 
    [ 7.500, 10.000) = 1089 
    [10.000, 12.500) = 200 
    [12.500, 15.000) = 35 
    [15.000, 17.500) = 157 
    [17.500, 20.000) = 63 
    [20.000, 22.500) = 49 
    [22.500, 25.000) = 45 
    [25.000, 27.500) = 35 

  Percentiles, ms/op:
      p(0.0000) =      0.982 ms/op
     p(50.0000) =      3.777 ms/op
     p(90.0000) =      4.989 ms/op
     p(95.0000) =      5.751 ms/op
     p(99.0000) =      7.086 ms/op
     p(99.9000) =     16.679 ms/op
     p(99.9900) =     25.412 ms/op
     p(99.9990) =     27.268 ms/op
     p(99.9999) =     27.329 ms/op
    p(100.0000) =     27.329 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.504 ± 2.863  ops/ms
ClientGrpc.existUser                       thrpt       3  11.256 ± 3.726  ops/ms
ClientGrpc.getUser                         thrpt       3  10.489 ± 1.898  ops/ms
ClientGrpc.listUser                        thrpt       3   8.272 ± 3.889  ops/ms
ClientGrpc.createUser                       avgt       3   3.019 ± 0.695   ms/op
ClientGrpc.existUser                        avgt       3   2.843 ± 0.376   ms/op
ClientGrpc.getUser                          avgt       3   3.041 ± 0.586   ms/op
ClientGrpc.listUser                         avgt       3   3.937 ± 0.274   ms/op
ClientGrpc.createUser                     sample  314851   3.048 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.610           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.019           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.629           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.842           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.669           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.903           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          27.919           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          28.606           ms/op
ClientGrpc.existUser                      sample  326069   2.941 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.671           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.912           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.408           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.654           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.260           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.733           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.189           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.038           ms/op
ClientGrpc.getUser                        sample  317132   3.024 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.433           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.978           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.531           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.789           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.776           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.088           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          28.298           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          30.802           ms/op
ClientGrpc.listUser                       sample  242386   3.963 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.982           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.777           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.989           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.751           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.086           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.679           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.412           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.329           ms/op
