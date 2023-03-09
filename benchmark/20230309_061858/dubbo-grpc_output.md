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
# Warmup Iteration   1: 4.841 ops/ms
# Warmup Iteration   2: 9.408 ops/ms
# Warmup Iteration   3: 10.273 ops/ms
Iteration   1: 10.647 ops/ms
Iteration   2: 10.918 ops/ms
Iteration   3: 10.946 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.837 ±(99.9%) 3.015 ops/ms [Average]
  (min, avg, max) = (10.647, 10.837, 10.946), stdev = 0.165
  CI (99.9%): [7.822, 13.852] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 7.696 ops/ms
# Warmup Iteration   2: 10.723 ops/ms
# Warmup Iteration   3: 11.041 ops/ms
Iteration   1: 11.455 ops/ms
Iteration   2: 11.202 ops/ms
Iteration   3: 11.528 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.395 ±(99.9%) 3.123 ops/ms [Average]
  (min, avg, max) = (11.202, 11.395, 11.528), stdev = 0.171
  CI (99.9%): [8.272, 14.518] (assumes normal distribution)


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
# Warmup Iteration   1: 7.489 ops/ms
# Warmup Iteration   2: 10.499 ops/ms
# Warmup Iteration   3: 10.947 ops/ms
Iteration   1: 10.651 ops/ms
Iteration   2: 10.932 ops/ms
Iteration   3: 10.780 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.788 ±(99.9%) 2.569 ops/ms [Average]
  (min, avg, max) = (10.651, 10.788, 10.932), stdev = 0.141
  CI (99.9%): [8.218, 13.357] (assumes normal distribution)


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
# Warmup Iteration   1: 6.343 ops/ms
# Warmup Iteration   2: 7.988 ops/ms
# Warmup Iteration   3: 8.241 ops/ms
Iteration   1: 8.078 ops/ms
Iteration   2: 8.134 ops/ms
Iteration   3: 8.277 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.163 ±(99.9%) 1.873 ops/ms [Average]
  (min, avg, max) = (8.078, 8.163, 8.277), stdev = 0.103
  CI (99.9%): [6.290, 10.036] (assumes normal distribution)


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
# Warmup Iteration   1: 3.791 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.080 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.030 ±(99.9%) 0.003 ms/op
Iteration   1: 3.033 ±(99.9%) 0.002 ms/op
Iteration   2: 3.004 ±(99.9%) 0.002 ms/op
Iteration   3: 2.989 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.009 ±(99.9%) 0.416 ms/op [Average]
  (min, avg, max) = (2.989, 3.009, 3.033), stdev = 0.023
  CI (99.9%): [2.592, 3.425] (assumes normal distribution)


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
# Warmup Iteration   1: 3.796 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.938 ±(99.9%) 0.001 ms/op
# Warmup Iteration   3: 2.887 ±(99.9%) 0.004 ms/op
Iteration   1: 2.843 ±(99.9%) 0.003 ms/op
Iteration   2: 2.864 ±(99.9%) 0.004 ms/op
Iteration   3: 2.887 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.865 ±(99.9%) 0.395 ms/op [Average]
  (min, avg, max) = (2.843, 2.865, 2.887), stdev = 0.022
  CI (99.9%): [2.470, 3.259] (assumes normal distribution)


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
# Warmup Iteration   1: 3.914 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.022 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.976 ±(99.9%) 0.005 ms/op
Iteration   1: 2.972 ±(99.9%) 0.002 ms/op
Iteration   2: 2.973 ±(99.9%) 0.002 ms/op
Iteration   3: 2.921 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.955 ±(99.9%) 0.538 ms/op [Average]
  (min, avg, max) = (2.921, 2.955, 2.973), stdev = 0.029
  CI (99.9%): [2.418, 3.493] (assumes normal distribution)


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
# Warmup Iteration   1: 5.424 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.899 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.841 ±(99.9%) 0.025 ms/op
Iteration   1: 3.874 ±(99.9%) 0.028 ms/op
Iteration   2: 3.854 ±(99.9%) 0.023 ms/op
Iteration   3: 3.813 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.847 ±(99.9%) 0.566 ms/op [Average]
  (min, avg, max) = (3.813, 3.847, 3.874), stdev = 0.031
  CI (99.9%): [3.281, 4.413] (assumes normal distribution)


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
# Warmup Iteration   1: 3.856 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.141 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.990 ±(99.9%) 0.007 ms/op
Iteration   1: 2.959 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.760 ms/op
                 createUser·p0.50:   2.945 ms/op
                 createUser·p0.90:   3.387 ms/op
                 createUser·p0.95:   3.535 ms/op
                 createUser·p0.99:   4.268 ms/op
                 createUser·p0.999:  6.229 ms/op
                 createUser·p0.9999: 17.340 ms/op
                 createUser·p1.00:   18.350 ms/op

Iteration   2: 3.022 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.549 ms/op
                 createUser·p0.50:   3.006 ms/op
                 createUser·p0.90:   3.600 ms/op
                 createUser·p0.95:   3.781 ms/op
                 createUser·p0.99:   4.375 ms/op
                 createUser·p0.999:  7.071 ms/op
                 createUser·p0.9999: 13.140 ms/op
                 createUser·p1.00:   13.435 ms/op

Iteration   3: 2.994 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.646 ms/op
                 createUser·p0.50:   2.978 ms/op
                 createUser·p0.90:   3.543 ms/op
                 createUser·p0.95:   3.731 ms/op
                 createUser·p0.99:   4.412 ms/op
                 createUser·p0.999:  7.235 ms/op
                 createUser·p0.9999: 22.293 ms/op
                 createUser·p1.00:   22.479 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 320786
  mean =      2.991 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 29034 
    [ 2.500,  5.000) = 290544 
    [ 5.000,  7.500) = 961 
    [ 7.500, 10.000) = 23 
    [10.000, 12.500) = 22 
    [12.500, 15.000) = 126 
    [15.000, 17.500) = 39 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.549 ms/op
     p(50.0000) =      2.974 ms/op
     p(90.0000) =      3.510 ms/op
     p(95.0000) =      3.715 ms/op
     p(99.0000) =      4.358 ms/op
     p(99.9000) =      6.857 ms/op
     p(99.9900) =     20.010 ms/op
     p(99.9990) =     22.413 ms/op
     p(99.9999) =     22.479 ms/op
    p(100.0000) =     22.479 ms/op


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
# Warmup Iteration   1: 3.768 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 2.930 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.831 ±(99.9%) 0.006 ms/op
Iteration   1: 2.832 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.584 ms/op
                 existUser·p0.50:   2.830 ms/op
                 existUser·p0.90:   3.363 ms/op
                 existUser·p0.95:   3.572 ms/op
                 existUser·p0.99:   4.400 ms/op
                 existUser·p0.999:  6.733 ms/op
                 existUser·p0.9999: 16.772 ms/op
                 existUser·p1.00:   17.269 ms/op

Iteration   2: 2.909 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.647 ms/op
                 existUser·p0.50:   2.884 ms/op
                 existUser·p0.90:   3.437 ms/op
                 existUser·p0.95:   3.645 ms/op
                 existUser·p0.99:   4.219 ms/op
                 existUser·p0.999:  6.496 ms/op
                 existUser·p0.9999: 15.450 ms/op
                 existUser·p1.00:   15.860 ms/op

Iteration   3: 2.870 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.638 ms/op
                 existUser·p0.50:   2.851 ms/op
                 existUser·p0.90:   3.424 ms/op
                 existUser·p0.95:   3.674 ms/op
                 existUser·p0.99:   4.465 ms/op
                 existUser·p0.999:  8.646 ms/op
                 existUser·p0.9999: 25.554 ms/op
                 existUser·p1.00:   25.952 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 334715
  mean =      2.870 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 54121 
    [ 2.500,  5.000) = 279480 
    [ 5.000,  7.500) = 830 
    [ 7.500, 10.000) = 108 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 80 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 29 

  Percentiles, ms/op:
      p(0.0000) =      0.584 ms/op
     p(50.0000) =      2.851 ms/op
     p(90.0000) =      3.408 ms/op
     p(95.0000) =      3.633 ms/op
     p(99.0000) =      4.383 ms/op
     p(99.9000) =      7.102 ms/op
     p(99.9900) =     17.253 ms/op
     p(99.9990) =     25.843 ms/op
     p(99.9999) =     25.952 ms/op
    p(100.0000) =     25.952 ms/op


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
# Warmup Iteration   1: 3.356 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.064 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.995 ±(99.9%) 0.006 ms/op
Iteration   1: 2.941 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.630 ms/op
                 getUser·p0.50:   2.929 ms/op
                 getUser·p0.90:   3.432 ms/op
                 getUser·p0.95:   3.682 ms/op
                 getUser·p0.99:   4.456 ms/op
                 getUser·p0.999:  9.060 ms/op
                 getUser·p0.9999: 13.535 ms/op
                 getUser·p1.00:   13.910 ms/op

Iteration   2: 2.969 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.863 ms/op
                 getUser·p0.50:   2.949 ms/op
                 getUser·p0.90:   3.453 ms/op
                 getUser·p0.95:   3.641 ms/op
                 getUser·p0.99:   4.358 ms/op
                 getUser·p0.999:  7.727 ms/op
                 getUser·p0.9999: 15.352 ms/op
                 getUser·p1.00:   16.728 ms/op

Iteration   3: 2.946 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.346 ms/op
                 getUser·p0.50:   2.937 ms/op
                 getUser·p0.90:   3.510 ms/op
                 getUser·p0.95:   3.707 ms/op
                 getUser·p0.99:   4.396 ms/op
                 getUser·p0.999:  6.312 ms/op
                 getUser·p0.9999: 13.650 ms/op
                 getUser·p1.00:   15.172 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 325154
  mean =      2.952 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1801 
    [ 1.250,  2.500) = 32419 
    [ 2.500,  3.750) = 277764 
    [ 3.750,  5.000) = 11989 
    [ 5.000,  6.250) = 686 
    [ 6.250,  7.500) = 215 
    [ 7.500,  8.750) = 55 
    [ 8.750, 10.000) = 65 
    [10.000, 11.250) = 28 
    [11.250, 12.500) = 11 
    [12.500, 13.750) = 67 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 17 
    [16.250, 17.500) = 5 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.346 ms/op
     p(50.0000) =      2.937 ms/op
     p(90.0000) =      3.461 ms/op
     p(95.0000) =      3.678 ms/op
     p(99.0000) =      4.399 ms/op
     p(99.9000) =      6.765 ms/op
     p(99.9900) =     14.663 ms/op
     p(99.9990) =     16.585 ms/op
     p(99.9999) =     16.728 ms/op
    p(100.0000) =     16.728 ms/op


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
# Warmup Iteration   1: 4.240 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 4.058 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.826 ±(99.9%) 0.009 ms/op
Iteration   1: 3.727 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.292 ms/op
                 listUser·p0.50:   3.625 ms/op
                 listUser·p0.90:   4.538 ms/op
                 listUser·p0.95:   5.374 ms/op
                 listUser·p0.99:   6.455 ms/op
                 listUser·p0.999:  12.145 ms/op
                 listUser·p0.9999: 14.927 ms/op
                 listUser·p1.00:   15.204 ms/op

Iteration   2: 3.771 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.204 ms/op
                 listUser·p0.50:   3.625 ms/op
                 listUser·p0.90:   4.694 ms/op
                 listUser·p0.95:   5.202 ms/op
                 listUser·p0.99:   6.615 ms/op
                 listUser·p0.999:  14.796 ms/op
                 listUser·p0.9999: 21.299 ms/op
                 listUser·p1.00:   22.544 ms/op

Iteration   3: 3.745 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.018 ms/op
                 listUser·p0.50:   3.625 ms/op
                 listUser·p0.90:   4.637 ms/op
                 listUser·p0.95:   5.456 ms/op
                 listUser·p0.99:   6.439 ms/op
                 listUser·p0.999:  20.521 ms/op
                 listUser·p0.9999: 24.362 ms/op
                 listUser·p1.00:   24.773 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 256199
  mean =      3.748 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5364 
    [ 2.500,  5.000) = 233428 
    [ 5.000,  7.500) = 16409 
    [ 7.500, 10.000) = 548 
    [10.000, 12.500) = 126 
    [12.500, 15.000) = 135 
    [15.000, 17.500) = 61 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 75 
    [22.500, 25.000) = 33 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.018 ms/op
     p(50.0000) =      3.625 ms/op
     p(90.0000) =      4.628 ms/op
     p(95.0000) =      5.333 ms/op
     p(99.0000) =      6.496 ms/op
     p(99.9000) =     13.776 ms/op
     p(99.9900) =     23.364 ms/op
     p(99.9990) =     24.707 ms/op
     p(99.9999) =     24.773 ms/op
    p(100.0000) =     24.773 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.837 ± 3.015  ops/ms
ClientGrpc.existUser                       thrpt       3  11.395 ± 3.123  ops/ms
ClientGrpc.getUser                         thrpt       3  10.788 ± 2.569  ops/ms
ClientGrpc.listUser                        thrpt       3   8.163 ± 1.873  ops/ms
ClientGrpc.createUser                       avgt       3   3.009 ± 0.416   ms/op
ClientGrpc.existUser                        avgt       3   2.865 ± 0.395   ms/op
ClientGrpc.getUser                          avgt       3   2.955 ± 0.538   ms/op
ClientGrpc.listUser                         avgt       3   3.847 ± 0.566   ms/op
ClientGrpc.createUser                     sample  320786   2.991 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.549           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.974           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.510           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.715           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.358           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           6.857           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.010           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.479           ms/op
ClientGrpc.existUser                      sample  334715   2.870 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.584           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.851           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.408           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.633           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.383           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.102           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.253           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          25.952           ms/op
ClientGrpc.getUser                        sample  325154   2.952 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.346           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.937           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.461           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.678           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.399           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.765           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          14.663           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          16.728           ms/op
ClientGrpc.listUser                       sample  256199   3.748 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.018           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.625           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.628           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.333           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.496           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.776           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.364           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.773           ms/op
