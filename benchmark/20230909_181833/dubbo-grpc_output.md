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
# Warmup Iteration   1: 4.700 ops/ms
# Warmup Iteration   2: 9.527 ops/ms
# Warmup Iteration   3: 10.138 ops/ms
Iteration   1: 10.424 ops/ms
Iteration   2: 10.661 ops/ms
Iteration   3: 10.497 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.527 ±(99.9%) 2.212 ops/ms [Average]
  (min, avg, max) = (10.424, 10.527, 10.661), stdev = 0.121
  CI (99.9%): [8.315, 12.739] (assumes normal distribution)


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
# Warmup Iteration   1: 8.019 ops/ms
# Warmup Iteration   2: 10.876 ops/ms
# Warmup Iteration   3: 11.253 ops/ms
Iteration   1: 11.360 ops/ms
Iteration   2: 11.264 ops/ms
Iteration   3: 11.406 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.344 ±(99.9%) 1.326 ops/ms [Average]
  (min, avg, max) = (11.264, 11.344, 11.406), stdev = 0.073
  CI (99.9%): [10.018, 12.669] (assumes normal distribution)


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
# Warmup Iteration   1: 7.977 ops/ms
# Warmup Iteration   2: 10.504 ops/ms
# Warmup Iteration   3: 10.534 ops/ms
Iteration   1: 10.693 ops/ms
Iteration   2: 10.910 ops/ms
Iteration   3: 10.733 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.779 ±(99.9%) 2.108 ops/ms [Average]
  (min, avg, max) = (10.693, 10.779, 10.910), stdev = 0.116
  CI (99.9%): [8.671, 12.886] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 6.025 ops/ms
# Warmup Iteration   2: 8.102 ops/ms
# Warmup Iteration   3: 8.426 ops/ms
Iteration   1: 8.393 ops/ms
Iteration   2: 8.408 ops/ms
Iteration   3: 8.291 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.364 ±(99.9%) 1.160 ops/ms [Average]
  (min, avg, max) = (8.291, 8.364, 8.408), stdev = 0.064
  CI (99.9%): [7.204, 9.524] (assumes normal distribution)


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
# Warmup Iteration   1: 3.720 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.090 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.038 ±(99.9%) 0.003 ms/op
Iteration   1: 2.942 ±(99.9%) 0.003 ms/op
Iteration   2: 2.982 ±(99.9%) 0.004 ms/op
Iteration   3: 2.957 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.960 ±(99.9%) 0.375 ms/op [Average]
  (min, avg, max) = (2.942, 2.960, 2.982), stdev = 0.021
  CI (99.9%): [2.586, 3.335] (assumes normal distribution)


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
# Warmup Iteration   1: 3.782 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.946 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 2.850 ±(99.9%) 0.003 ms/op
Iteration   1: 2.808 ±(99.9%) 0.003 ms/op
Iteration   2: 2.828 ±(99.9%) 0.004 ms/op
Iteration   3: 2.828 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.821 ±(99.9%) 0.217 ms/op [Average]
  (min, avg, max) = (2.808, 2.821, 2.828), stdev = 0.012
  CI (99.9%): [2.604, 3.038] (assumes normal distribution)


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
# Warmup Iteration   1: 3.762 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 3.040 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.933 ±(99.9%) 0.003 ms/op
Iteration   1: 2.944 ±(99.9%) 0.002 ms/op
Iteration   2: 2.962 ±(99.9%) 0.002 ms/op
Iteration   3: 2.956 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.954 ±(99.9%) 0.168 ms/op [Average]
  (min, avg, max) = (2.944, 2.954, 2.962), stdev = 0.009
  CI (99.9%): [2.786, 3.122] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.717 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.937 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 3.831 ±(99.9%) 0.013 ms/op
Iteration   1: 3.829 ±(99.9%) 0.016 ms/op
Iteration   2: 3.861 ±(99.9%) 0.005 ms/op
Iteration   3: 3.806 ±(99.9%) 0.023 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.832 ±(99.9%) 0.507 ms/op [Average]
  (min, avg, max) = (3.806, 3.832, 3.861), stdev = 0.028
  CI (99.9%): [3.325, 4.339] (assumes normal distribution)


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
# Warmup Iteration   1: 4.141 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.187 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.021 ±(99.9%) 0.007 ms/op
Iteration   1: 2.962 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.616 ms/op
                 createUser·p0.50:   2.966 ms/op
                 createUser·p0.90:   3.465 ms/op
                 createUser·p0.95:   3.699 ms/op
                 createUser·p0.99:   4.456 ms/op
                 createUser·p0.999:  7.176 ms/op
                 createUser·p0.9999: 15.326 ms/op
                 createUser·p1.00:   15.663 ms/op

Iteration   2: 2.993 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.596 ms/op
                 createUser·p0.50:   2.966 ms/op
                 createUser·p0.90:   3.551 ms/op
                 createUser·p0.95:   3.781 ms/op
                 createUser·p0.99:   4.506 ms/op
                 createUser·p0.999:  8.118 ms/op
                 createUser·p0.9999: 16.457 ms/op
                 createUser·p1.00:   18.186 ms/op

Iteration   3: 2.977 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.637 ms/op
                 createUser·p0.50:   2.957 ms/op
                 createUser·p0.90:   3.445 ms/op
                 createUser·p0.95:   3.703 ms/op
                 createUser·p0.99:   4.489 ms/op
                 createUser·p0.999:  8.066 ms/op
                 createUser·p0.9999: 20.399 ms/op
                 createUser·p1.00:   21.135 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 322255
  mean =      2.977 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 30773 
    [ 2.500,  5.000) = 289843 
    [ 5.000,  7.500) = 1209 
    [ 7.500, 10.000) = 206 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 70 
    [15.000, 17.500) = 91 
    [17.500, 20.000) = 35 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.596 ms/op
     p(50.0000) =      2.961 ms/op
     p(90.0000) =      3.490 ms/op
     p(95.0000) =      3.731 ms/op
     p(99.0000) =      4.481 ms/op
     p(99.9000) =      7.870 ms/op
     p(99.9900) =     19.437 ms/op
     p(99.9990) =     20.775 ms/op
     p(99.9999) =     21.135 ms/op
    p(100.0000) =     21.135 ms/op


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
# Warmup Iteration   1: 3.899 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 2.962 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.858 ±(99.9%) 0.006 ms/op
Iteration   1: 2.866 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.755 ms/op
                 existUser·p0.50:   2.843 ms/op
                 existUser·p0.90:   3.338 ms/op
                 existUser·p0.95:   3.654 ms/op
                 existUser·p0.99:   4.522 ms/op
                 existUser·p0.999:  6.922 ms/op
                 existUser·p0.9999: 11.108 ms/op
                 existUser·p1.00:   11.911 ms/op

Iteration   2: 2.896 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.537 ms/op
                 existUser·p0.50:   2.888 ms/op
                 existUser·p0.90:   3.482 ms/op
                 existUser·p0.95:   3.727 ms/op
                 existUser·p0.99:   4.473 ms/op
                 existUser·p0.999:  7.014 ms/op
                 existUser·p0.9999: 12.304 ms/op
                 existUser·p1.00:   12.567 ms/op

Iteration   3: 2.911 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.764 ms/op
                 existUser·p0.50:   2.892 ms/op
                 existUser·p0.90:   3.432 ms/op
                 existUser·p0.95:   3.600 ms/op
                 existUser·p0.99:   4.284 ms/op
                 existUser·p0.999:  7.463 ms/op
                 existUser·p0.9999: 23.527 ms/op
                 existUser·p1.00:   23.953 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 331847
  mean =      2.891 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 48206 
    [ 2.500,  5.000) = 282090 
    [ 5.000,  7.500) = 1266 
    [ 7.500, 10.000) = 93 
    [10.000, 12.500) = 126 
    [12.500, 15.000) = 2 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 63 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.537 ms/op
     p(50.0000) =      2.871 ms/op
     p(90.0000) =      3.432 ms/op
     p(95.0000) =      3.658 ms/op
     p(99.0000) =      4.473 ms/op
     p(99.9000) =      7.258 ms/op
     p(99.9900) =     23.259 ms/op
     p(99.9990) =     23.746 ms/op
     p(99.9999) =     23.953 ms/op
    p(100.0000) =     23.953 ms/op


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
# Warmup Iteration   1: 3.906 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.056 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.967 ±(99.9%) 0.006 ms/op
Iteration   1: 2.991 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.762 ms/op
                 getUser·p0.50:   2.966 ms/op
                 getUser·p0.90:   3.523 ms/op
                 getUser·p0.95:   3.797 ms/op
                 getUser·p0.99:   4.694 ms/op
                 getUser·p0.999:  7.576 ms/op
                 getUser·p0.9999: 14.275 ms/op
                 getUser·p1.00:   14.500 ms/op

Iteration   2: 2.937 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.554 ms/op
                 getUser·p0.50:   2.957 ms/op
                 getUser·p0.90:   3.437 ms/op
                 getUser·p0.95:   3.678 ms/op
                 getUser·p0.99:   4.375 ms/op
                 getUser·p0.999:  9.093 ms/op
                 getUser·p0.9999: 15.712 ms/op
                 getUser·p1.00:   17.138 ms/op

Iteration   3: 2.953 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.592 ms/op
                 getUser·p0.50:   2.941 ms/op
                 getUser·p0.90:   3.351 ms/op
                 getUser·p0.95:   3.510 ms/op
                 getUser·p0.99:   4.366 ms/op
                 getUser·p0.999:  7.272 ms/op
                 getUser·p0.9999: 15.128 ms/op
                 getUser·p1.00:   15.581 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 324263
  mean =      2.960 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1997 
    [ 1.250,  2.500) = 29291 
    [ 2.500,  3.750) = 279583 
    [ 3.750,  5.000) = 11615 
    [ 5.000,  6.250) = 917 
    [ 6.250,  7.500) = 528 
    [ 7.500,  8.750) = 83 
    [ 8.750, 10.000) = 29 
    [10.000, 11.250) = 40 
    [11.250, 12.500) = 20 
    [12.500, 13.750) = 38 
    [13.750, 15.000) = 72 
    [15.000, 16.250) = 41 
    [16.250, 17.500) = 9 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.554 ms/op
     p(50.0000) =      2.953 ms/op
     p(90.0000) =      3.432 ms/op
     p(95.0000) =      3.666 ms/op
     p(99.0000) =      4.473 ms/op
     p(99.9000) =      7.528 ms/op
     p(99.9900) =     15.352 ms/op
     p(99.9990) =     17.023 ms/op
     p(99.9999) =     17.138 ms/op
    p(100.0000) =     17.138 ms/op


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
# Warmup Iteration   1: 4.958 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.974 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.850 ±(99.9%) 0.010 ms/op
Iteration   1: 3.856 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.037 ms/op
                 listUser·p0.50:   3.699 ms/op
                 listUser·p0.90:   4.809 ms/op
                 listUser·p0.95:   5.734 ms/op
                 listUser·p0.99:   6.816 ms/op
                 listUser·p0.999:  12.895 ms/op
                 listUser·p0.9999: 20.657 ms/op
                 listUser·p1.00:   21.332 ms/op

Iteration   2: 3.837 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.768 ms/op
                 listUser·p0.50:   3.699 ms/op
                 listUser·p0.90:   4.891 ms/op
                 listUser·p0.95:   5.595 ms/op
                 listUser·p0.99:   6.611 ms/op
                 listUser·p0.999:  14.008 ms/op
                 listUser·p0.9999: 18.306 ms/op
                 listUser·p1.00:   18.579 ms/op

Iteration   3: 3.858 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.253 ms/op
                 listUser·p0.50:   3.686 ms/op
                 listUser·p0.90:   4.850 ms/op
                 listUser·p0.95:   5.472 ms/op
                 listUser·p0.99:   6.767 ms/op
                 listUser·p0.999:  14.469 ms/op
                 listUser·p0.9999: 16.077 ms/op
                 listUser·p1.00:   18.055 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 249199
  mean =      3.850 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6431 
    [ 2.500,  5.000) = 221231 
    [ 5.000,  7.500) = 20234 
    [ 7.500, 10.000) = 814 
    [10.000, 12.500) = 79 
    [12.500, 15.000) = 252 
    [15.000, 17.500) = 87 
    [17.500, 20.000) = 58 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.768 ms/op
     p(50.0000) =      3.695 ms/op
     p(90.0000) =      4.850 ms/op
     p(95.0000) =      5.612 ms/op
     p(99.0000) =      6.734 ms/op
     p(99.9000) =     14.021 ms/op
     p(99.9900) =     19.046 ms/op
     p(99.9990) =     21.219 ms/op
     p(99.9999) =     21.332 ms/op
    p(100.0000) =     21.332 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.527 ± 2.212  ops/ms
ClientGrpc.existUser                       thrpt       3  11.344 ± 1.326  ops/ms
ClientGrpc.getUser                         thrpt       3  10.779 ± 2.108  ops/ms
ClientGrpc.listUser                        thrpt       3   8.364 ± 1.160  ops/ms
ClientGrpc.createUser                       avgt       3   2.960 ± 0.375   ms/op
ClientGrpc.existUser                        avgt       3   2.821 ± 0.217   ms/op
ClientGrpc.getUser                          avgt       3   2.954 ± 0.168   ms/op
ClientGrpc.listUser                         avgt       3   3.832 ± 0.507   ms/op
ClientGrpc.createUser                     sample  322255   2.977 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.596           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.961           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.490           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.731           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.481           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.870           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.437           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.135           ms/op
ClientGrpc.existUser                      sample  331847   2.891 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.537           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.871           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.432           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.658           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.473           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.258           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          23.259           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          23.953           ms/op
ClientGrpc.getUser                        sample  324263   2.960 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.554           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.953           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.432           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.666           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.473           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.528           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          15.352           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          17.138           ms/op
ClientGrpc.listUser                       sample  249199   3.850 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.768           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.695           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.850           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.612           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.734           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.021           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          19.046           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          21.332           ms/op
