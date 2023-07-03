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
# Warmup Iteration   1: 4.718 ops/ms
# Warmup Iteration   2: 9.297 ops/ms
# Warmup Iteration   3: 10.210 ops/ms
Iteration   1: 10.948 ops/ms
Iteration   2: 10.684 ops/ms
Iteration   3: 10.572 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.735 ±(99.9%) 3.525 ops/ms [Average]
  (min, avg, max) = (10.572, 10.735, 10.948), stdev = 0.193
  CI (99.9%): [7.210, 14.260] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.634 ops/ms
# Warmup Iteration   2: 10.639 ops/ms
# Warmup Iteration   3: 11.256 ops/ms
Iteration   1: 11.183 ops/ms
Iteration   2: 11.390 ops/ms
Iteration   3: 11.184 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.252 ±(99.9%) 2.171 ops/ms [Average]
  (min, avg, max) = (11.183, 11.252, 11.390), stdev = 0.119
  CI (99.9%): [9.082, 13.423] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 8.338 ops/ms
# Warmup Iteration   2: 10.426 ops/ms
# Warmup Iteration   3: 10.790 ops/ms
Iteration   1: 10.655 ops/ms
Iteration   2: 10.539 ops/ms
Iteration   3: 10.806 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.667 ±(99.9%) 2.434 ops/ms [Average]
  (min, avg, max) = (10.539, 10.667, 10.806), stdev = 0.133
  CI (99.9%): [8.232, 13.101] (assumes normal distribution)


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
# Warmup Iteration   1: 5.955 ops/ms
# Warmup Iteration   2: 8.135 ops/ms
# Warmup Iteration   3: 8.598 ops/ms
Iteration   1: 8.479 ops/ms
Iteration   2: 8.766 ops/ms
Iteration   3: 8.513 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.586 ±(99.9%) 2.861 ops/ms [Average]
  (min, avg, max) = (8.479, 8.586, 8.766), stdev = 0.157
  CI (99.9%): [5.725, 11.447] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.092 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.101 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.039 ±(99.9%) 0.003 ms/op
Iteration   1: 2.973 ±(99.9%) 0.003 ms/op
Iteration   2: 3.011 ±(99.9%) 0.004 ms/op
Iteration   3: 3.008 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.997 ±(99.9%) 0.386 ms/op [Average]
  (min, avg, max) = (2.973, 2.997, 3.011), stdev = 0.021
  CI (99.9%): [2.612, 3.383] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.806 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.984 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.841 ±(99.9%) 0.004 ms/op
Iteration   1: 2.864 ±(99.9%) 0.003 ms/op
Iteration   2: 2.856 ±(99.9%) 0.004 ms/op
Iteration   3: 2.895 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.872 ±(99.9%) 0.375 ms/op [Average]
  (min, avg, max) = (2.856, 2.872, 2.895), stdev = 0.021
  CI (99.9%): [2.497, 3.247] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.213 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 3.067 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.945 ±(99.9%) 0.003 ms/op
Iteration   1: 2.944 ±(99.9%) 0.002 ms/op
Iteration   2: 2.925 ±(99.9%) 0.002 ms/op
Iteration   3: 3.000 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.956 ±(99.9%) 0.717 ms/op [Average]
  (min, avg, max) = (2.925, 2.956, 3.000), stdev = 0.039
  CI (99.9%): [2.240, 3.673] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 3.954 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.079 ±(99.9%) 0.031 ms/op
# Warmup Iteration   3: 3.817 ±(99.9%) 0.007 ms/op
Iteration   1: 3.856 ±(99.9%) 0.018 ms/op
Iteration   2: 3.878 ±(99.9%) 0.033 ms/op
Iteration   3: 3.762 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.832 ±(99.9%) 1.116 ms/op [Average]
  (min, avg, max) = (3.762, 3.832, 3.878), stdev = 0.061
  CI (99.9%): [2.716, 4.948] (assumes normal distribution)


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
# Warmup Iteration   1: 3.981 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.114 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.983 ±(99.9%) 0.006 ms/op
Iteration   1: 3.015 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.699 ms/op
                 createUser·p0.50:   2.990 ms/op
                 createUser·p0.90:   3.584 ms/op
                 createUser·p0.95:   3.777 ms/op
                 createUser·p0.99:   4.571 ms/op
                 createUser·p0.999:  7.622 ms/op
                 createUser·p0.9999: 12.665 ms/op
                 createUser·p1.00:   13.091 ms/op

Iteration   2: 2.988 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.734 ms/op
                 createUser·p0.50:   2.978 ms/op
                 createUser·p0.90:   3.523 ms/op
                 createUser·p0.95:   3.690 ms/op
                 createUser·p0.99:   4.375 ms/op
                 createUser·p0.999:  6.724 ms/op
                 createUser·p0.9999: 16.450 ms/op
                 createUser·p1.00:   16.761 ms/op

Iteration   3: 2.985 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.625 ms/op
                 createUser·p0.50:   2.961 ms/op
                 createUser·p0.90:   3.416 ms/op
                 createUser·p0.95:   3.613 ms/op
                 createUser·p0.99:   4.225 ms/op
                 createUser·p0.999:  8.184 ms/op
                 createUser·p0.9999: 22.390 ms/op
                 createUser·p1.00:   22.872 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 320390
  mean =      2.996 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27485 
    [ 2.500,  5.000) = 291738 
    [ 5.000,  7.500) = 884 
    [ 7.500, 10.000) = 91 
    [10.000, 12.500) = 56 
    [12.500, 15.000) = 84 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.625 ms/op
     p(50.0000) =      2.978 ms/op
     p(90.0000) =      3.510 ms/op
     p(95.0000) =      3.707 ms/op
     p(99.0000) =      4.407 ms/op
     p(99.9000) =      7.140 ms/op
     p(99.9900) =     19.831 ms/op
     p(99.9990) =     22.865 ms/op
     p(99.9999) =     22.872 ms/op
    p(100.0000) =     22.872 ms/op


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
# Warmup Iteration   1: 3.230 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.005 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.895 ±(99.9%) 0.006 ms/op
Iteration   1: 2.843 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.431 ms/op
                 existUser·p0.50:   2.867 ms/op
                 existUser·p0.90:   3.379 ms/op
                 existUser·p0.95:   3.650 ms/op
                 existUser·p0.99:   4.418 ms/op
                 existUser·p0.999:  6.112 ms/op
                 existUser·p0.9999: 11.907 ms/op
                 existUser·p1.00:   12.288 ms/op

Iteration   2: 2.846 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.699 ms/op
                 existUser·p0.50:   2.855 ms/op
                 existUser·p0.90:   3.285 ms/op
                 existUser·p0.95:   3.518 ms/op
                 existUser·p0.99:   4.579 ms/op
                 existUser·p0.999:  10.076 ms/op
                 existUser·p0.9999: 14.344 ms/op
                 existUser·p1.00:   14.926 ms/op

Iteration   3: 2.922 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.589 ms/op
                 existUser·p0.50:   2.900 ms/op
                 existUser·p0.90:   3.432 ms/op
                 existUser·p0.95:   3.613 ms/op
                 existUser·p0.99:   4.197 ms/op
                 existUser·p0.999:  7.267 ms/op
                 existUser·p0.9999: 15.860 ms/op
                 existUser·p1.00:   17.007 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 334401
  mean =      2.870 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 4378 
    [ 1.250,  2.500) = 42189 
    [ 2.500,  3.750) = 276354 
    [ 3.750,  5.000) = 10491 
    [ 5.000,  6.250) = 543 
    [ 6.250,  7.500) = 126 
    [ 7.500,  8.750) = 27 
    [ 8.750, 10.000) = 8 
    [10.000, 11.250) = 128 
    [11.250, 12.500) = 61 
    [12.500, 13.750) = 46 
    [13.750, 15.000) = 18 
    [15.000, 16.250) = 29 
    [16.250, 17.500) = 3 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.431 ms/op
     p(50.0000) =      2.871 ms/op
     p(90.0000) =      3.367 ms/op
     p(95.0000) =      3.604 ms/op
     p(99.0000) =      4.424 ms/op
     p(99.9000) =      7.284 ms/op
     p(99.9900) =     14.904 ms/op
     p(99.9990) =     16.648 ms/op
     p(99.9999) =     17.007 ms/op
    p(100.0000) =     17.007 ms/op


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
# Warmup Iteration   1: 3.932 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.041 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.026 ±(99.9%) 0.007 ms/op
Iteration   1: 2.965 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.628 ms/op
                 getUser·p0.50:   2.961 ms/op
                 getUser·p0.90:   3.551 ms/op
                 getUser·p0.95:   3.723 ms/op
                 getUser·p0.99:   4.424 ms/op
                 getUser·p0.999:  9.444 ms/op
                 getUser·p0.9999: 19.137 ms/op
                 getUser·p1.00:   19.595 ms/op

Iteration   2: 2.966 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.644 ms/op
                 getUser·p0.50:   2.957 ms/op
                 getUser·p0.90:   3.461 ms/op
                 getUser·p0.95:   3.650 ms/op
                 getUser·p0.99:   4.383 ms/op
                 getUser·p0.999:  6.628 ms/op
                 getUser·p0.9999: 33.299 ms/op
                 getUser·p1.00:   33.554 ms/op

Iteration   3: 2.991 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.687 ms/op
                 getUser·p0.50:   2.982 ms/op
                 getUser·p0.90:   3.432 ms/op
                 getUser·p0.95:   3.662 ms/op
                 getUser·p0.99:   4.112 ms/op
                 getUser·p0.999:  6.598 ms/op
                 getUser·p0.9999: 21.196 ms/op
                 getUser·p1.00:   21.791 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 322742
  mean =      2.974 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 30931 
    [ 2.500,  5.000) = 290789 
    [ 5.000,  7.500) = 735 
    [ 7.500, 10.000) = 66 
    [10.000, 12.500) = 29 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 97 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 19 
    [32.500, 35.000) = 13 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.628 ms/op
     p(50.0000) =      2.970 ms/op
     p(90.0000) =      3.490 ms/op
     p(95.0000) =      3.682 ms/op
     p(99.0000) =      4.325 ms/op
     p(99.9000) =      6.965 ms/op
     p(99.9900) =     28.568 ms/op
     p(99.9990) =     33.449 ms/op
     p(99.9999) =     33.554 ms/op
    p(100.0000) =     33.554 ms/op


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
# Warmup Iteration   1: 5.468 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 3.937 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.871 ±(99.9%) 0.010 ms/op
Iteration   1: 3.843 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.358 ms/op
                 listUser·p0.50:   3.715 ms/op
                 listUser·p0.90:   4.792 ms/op
                 listUser·p0.95:   5.579 ms/op
                 listUser·p0.99:   6.726 ms/op
                 listUser·p0.999:  12.346 ms/op
                 listUser·p0.9999: 19.596 ms/op
                 listUser·p1.00:   21.463 ms/op

Iteration   2: 3.833 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.159 ms/op
                 listUser·p0.50:   3.682 ms/op
                 listUser·p0.90:   4.694 ms/op
                 listUser·p0.95:   5.407 ms/op
                 listUser·p0.99:   6.627 ms/op
                 listUser·p0.999:  14.607 ms/op
                 listUser·p0.9999: 18.339 ms/op
                 listUser·p1.00:   18.973 ms/op

Iteration   3: 3.846 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.468 ms/op
                 listUser·p0.50:   3.666 ms/op
                 listUser·p0.90:   4.956 ms/op
                 listUser·p0.95:   5.407 ms/op
                 listUser·p0.99:   7.119 ms/op
                 listUser·p0.999:  19.231 ms/op
                 listUser·p0.9999: 22.163 ms/op
                 listUser·p1.00:   22.643 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 249789
  mean =      3.840 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5170 
    [ 2.500,  5.000) = 223748 
    [ 5.000,  7.500) = 19717 
    [ 7.500, 10.000) = 589 
    [10.000, 12.500) = 147 
    [12.500, 15.000) = 166 
    [15.000, 17.500) = 112 
    [17.500, 20.000) = 59 
    [20.000, 22.500) = 79 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.468 ms/op
     p(50.0000) =      3.690 ms/op
     p(90.0000) =      4.833 ms/op
     p(95.0000) =      5.456 ms/op
     p(99.0000) =      6.799 ms/op
     p(99.9000) =     15.064 ms/op
     p(99.9900) =     21.463 ms/op
     p(99.9990) =     22.528 ms/op
     p(99.9999) =     22.643 ms/op
    p(100.0000) =     22.643 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.735 ± 3.525  ops/ms
ClientGrpc.existUser                       thrpt       3  11.252 ± 2.171  ops/ms
ClientGrpc.getUser                         thrpt       3  10.667 ± 2.434  ops/ms
ClientGrpc.listUser                        thrpt       3   8.586 ± 2.861  ops/ms
ClientGrpc.createUser                       avgt       3   2.997 ± 0.386   ms/op
ClientGrpc.existUser                        avgt       3   2.872 ± 0.375   ms/op
ClientGrpc.getUser                          avgt       3   2.956 ± 0.717   ms/op
ClientGrpc.listUser                         avgt       3   3.832 ± 1.116   ms/op
ClientGrpc.createUser                     sample  320390   2.996 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.625           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.978           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.510           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.707           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.407           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.140           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.831           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.872           ms/op
ClientGrpc.existUser                      sample  334401   2.870 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.431           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.871           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.367           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.604           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.424           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.284           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.904           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.007           ms/op
ClientGrpc.getUser                        sample  322742   2.974 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.628           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.970           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.490           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.682           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.325           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.965           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          28.568           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          33.554           ms/op
ClientGrpc.listUser                       sample  249789   3.840 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.468           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.690           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.833           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.456           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.799           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.064           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.463           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          22.643           ms/op
