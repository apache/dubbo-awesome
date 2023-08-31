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
# Warmup Iteration   1: 4.414 ops/ms
# Warmup Iteration   2: 9.213 ops/ms
# Warmup Iteration   3: 10.245 ops/ms
Iteration   1: 10.612 ops/ms
Iteration   2: 10.370 ops/ms
Iteration   3: 11.164 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.716 ±(99.9%) 7.425 ops/ms [Average]
  (min, avg, max) = (10.370, 10.716, 11.164), stdev = 0.407
  CI (99.9%): [3.290, 18.141] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 8.317 ops/ms
# Warmup Iteration   2: 10.633 ops/ms
# Warmup Iteration   3: 11.114 ops/ms
Iteration   1: 11.472 ops/ms
Iteration   2: 11.227 ops/ms
Iteration   3: 11.338 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.346 ±(99.9%) 2.234 ops/ms [Average]
  (min, avg, max) = (11.227, 11.346, 11.472), stdev = 0.122
  CI (99.9%): [9.112, 13.579] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:50
# Fork: 1 of 1
# Warmup Iteration   1: 7.182 ops/ms
# Warmup Iteration   2: 10.312 ops/ms
# Warmup Iteration   3: 10.694 ops/ms
Iteration   1: 10.858 ops/ms
Iteration   2: 10.833 ops/ms
Iteration   3: 10.760 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.817 ±(99.9%) 0.925 ops/ms [Average]
  (min, avg, max) = (10.760, 10.817, 10.858), stdev = 0.051
  CI (99.9%): [9.891, 11.742] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 6.341 ops/ms
# Warmup Iteration   2: 7.942 ops/ms
# Warmup Iteration   3: 8.385 ops/ms
Iteration   1: 8.405 ops/ms
Iteration   2: 8.327 ops/ms
Iteration   3: 8.263 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.332 ±(99.9%) 1.302 ops/ms [Average]
  (min, avg, max) = (8.263, 8.332, 8.405), stdev = 0.071
  CI (99.9%): [7.030, 9.634] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 4.067 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.103 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 2.986 ±(99.9%) 0.003 ms/op
Iteration   1: 3.035 ±(99.9%) 0.002 ms/op
Iteration   2: 2.939 ±(99.9%) 0.003 ms/op
Iteration   3: 2.934 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.970 ±(99.9%) 1.037 ms/op [Average]
  (min, avg, max) = (2.934, 2.970, 3.035), stdev = 0.057
  CI (99.9%): [1.932, 4.007] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.868 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 2.999 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.839 ±(99.9%) 0.003 ms/op
Iteration   1: 2.864 ±(99.9%) 0.004 ms/op
Iteration   2: 2.850 ±(99.9%) 0.004 ms/op
Iteration   3: 2.789 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.834 ±(99.9%) 0.726 ms/op [Average]
  (min, avg, max) = (2.789, 2.834, 2.864), stdev = 0.040
  CI (99.9%): [2.108, 3.560] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.885 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.054 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.016 ±(99.9%) 0.003 ms/op
Iteration   1: 3.019 ±(99.9%) 0.003 ms/op
Iteration   2: 2.950 ±(99.9%) 0.002 ms/op
Iteration   3: 3.004 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.991 ±(99.9%) 0.659 ms/op [Average]
  (min, avg, max) = (2.950, 2.991, 3.019), stdev = 0.036
  CI (99.9%): [2.332, 3.650] (assumes normal distribution)


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
# Warmup Iteration   1: 5.266 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.898 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.836 ±(99.9%) 0.016 ms/op
Iteration   1: 3.837 ±(99.9%) 0.023 ms/op
Iteration   2: 3.867 ±(99.9%) 0.019 ms/op
Iteration   3: 3.873 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.859 ±(99.9%) 0.346 ms/op [Average]
  (min, avg, max) = (3.837, 3.859, 3.873), stdev = 0.019
  CI (99.9%): [3.513, 4.205] (assumes normal distribution)


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
# Warmup Iteration   1: 4.114 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.110 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.975 ±(99.9%) 0.008 ms/op
Iteration   1: 2.988 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.717 ms/op
                 createUser·p0.50:   2.982 ms/op
                 createUser·p0.90:   3.482 ms/op
                 createUser·p0.95:   3.719 ms/op
                 createUser·p0.99:   4.538 ms/op
                 createUser·p0.999:  7.791 ms/op
                 createUser·p0.9999: 13.150 ms/op
                 createUser·p1.00:   13.418 ms/op

Iteration   2: 3.032 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.740 ms/op
                 createUser·p0.50:   3.002 ms/op
                 createUser·p0.90:   3.539 ms/op
                 createUser·p0.95:   3.711 ms/op
                 createUser·p0.99:   4.211 ms/op
                 createUser·p0.999:  9.264 ms/op
                 createUser·p0.9999: 13.426 ms/op
                 createUser·p1.00:   13.812 ms/op

Iteration   3: 2.979 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.733 ms/op
                 createUser·p0.50:   2.978 ms/op
                 createUser·p0.90:   3.514 ms/op
                 createUser·p0.95:   3.723 ms/op
                 createUser·p0.99:   4.489 ms/op
                 createUser·p0.999:  7.582 ms/op
                 createUser·p0.9999: 23.044 ms/op
                 createUser·p1.00:   23.331 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 320111
  mean =      2.999 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26206 
    [ 2.500,  5.000) = 292223 
    [ 5.000,  7.500) = 1236 
    [ 7.500, 10.000) = 222 
    [10.000, 12.500) = 102 
    [12.500, 15.000) = 89 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.717 ms/op
     p(50.0000) =      2.986 ms/op
     p(90.0000) =      3.518 ms/op
     p(95.0000) =      3.715 ms/op
     p(99.0000) =      4.424 ms/op
     p(99.9000) =      8.028 ms/op
     p(99.9900) =     21.035 ms/op
     p(99.9990) =     23.226 ms/op
     p(99.9999) =     23.331 ms/op
    p(100.0000) =     23.331 ms/op


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
# Warmup Iteration   1: 3.783 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 2.974 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.899 ±(99.9%) 0.005 ms/op
Iteration   1: 2.881 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.665 ms/op
                 existUser·p0.50:   2.875 ms/op
                 existUser·p0.90:   3.457 ms/op
                 existUser·p0.95:   3.695 ms/op
                 existUser·p0.99:   4.497 ms/op
                 existUser·p0.999:  8.551 ms/op
                 existUser·p0.9999: 11.531 ms/op
                 existUser·p1.00:   11.813 ms/op

Iteration   2: 2.858 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.698 ms/op
                 existUser·p0.50:   2.859 ms/op
                 existUser·p0.90:   3.445 ms/op
                 existUser·p0.95:   3.658 ms/op
                 existUser·p0.99:   4.399 ms/op
                 existUser·p0.999:  7.602 ms/op
                 existUser·p0.9999: 20.047 ms/op
                 existUser·p1.00:   20.414 ms/op

Iteration   3: 2.855 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.549 ms/op
                 existUser·p0.50:   2.871 ms/op
                 existUser·p0.90:   3.326 ms/op
                 existUser·p0.95:   3.625 ms/op
                 existUser·p0.99:   4.383 ms/op
                 existUser·p0.999:  7.782 ms/op
                 existUser·p0.9999: 14.103 ms/op
                 existUser·p1.00:   14.909 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 335132
  mean =      2.864 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 52882 
    [ 2.500,  5.000) = 280508 
    [ 5.000,  7.500) = 1320 
    [ 7.500, 10.000) = 192 
    [10.000, 12.500) = 115 
    [12.500, 15.000) = 83 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.549 ms/op
     p(50.0000) =      2.867 ms/op
     p(90.0000) =      3.408 ms/op
     p(95.0000) =      3.666 ms/op
     p(99.0000) =      4.432 ms/op
     p(99.9000) =      7.954 ms/op
     p(99.9900) =     14.909 ms/op
     p(99.9990) =     20.326 ms/op
     p(99.9999) =     20.414 ms/op
    p(100.0000) =     20.414 ms/op


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
# Warmup Iteration   1: 4.015 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.106 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.026 ±(99.9%) 0.007 ms/op
Iteration   1: 2.970 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.679 ms/op
                 getUser·p0.50:   2.998 ms/op
                 getUser·p0.90:   3.547 ms/op
                 getUser·p0.95:   3.740 ms/op
                 getUser·p0.99:   4.432 ms/op
                 getUser·p0.999:  8.962 ms/op
                 getUser·p0.9999: 17.138 ms/op
                 getUser·p1.00:   17.531 ms/op

Iteration   2: 2.942 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.726 ms/op
                 getUser·p0.50:   2.974 ms/op
                 getUser·p0.90:   3.453 ms/op
                 getUser·p0.95:   3.678 ms/op
                 getUser·p0.99:   4.497 ms/op
                 getUser·p0.999:  8.309 ms/op
                 getUser·p0.9999: 21.897 ms/op
                 getUser·p1.00:   22.348 ms/op

Iteration   3: 2.997 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.584 ms/op
                 getUser·p0.50:   2.978 ms/op
                 getUser·p0.90:   3.457 ms/op
                 getUser·p0.95:   3.654 ms/op
                 getUser·p0.99:   4.190 ms/op
                 getUser·p0.999:  7.938 ms/op
                 getUser·p0.9999: 25.625 ms/op
                 getUser·p1.00:   25.985 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 323131
  mean =      2.969 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 32709 
    [ 2.500,  5.000) = 288679 
    [ 5.000,  7.500) = 1363 
    [ 7.500, 10.000) = 184 
    [10.000, 12.500) = 36 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 63 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 28 

  Percentiles, ms/op:
      p(0.0000) =      0.584 ms/op
     p(50.0000) =      2.982 ms/op
     p(90.0000) =      3.490 ms/op
     p(95.0000) =      3.690 ms/op
     p(99.0000) =      4.383 ms/op
     p(99.9000) =      8.151 ms/op
     p(99.9900) =     23.225 ms/op
     p(99.9990) =     25.846 ms/op
     p(99.9999) =     25.985 ms/op
    p(100.0000) =     25.985 ms/op


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
# Warmup Iteration   1: 4.645 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.939 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.865 ±(99.9%) 0.010 ms/op
Iteration   1: 3.732 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.130 ms/op
                 listUser·p0.50:   3.568 ms/op
                 listUser·p0.90:   4.932 ms/op
                 listUser·p0.95:   5.644 ms/op
                 listUser·p0.99:   6.955 ms/op
                 listUser·p0.999:  12.766 ms/op
                 listUser·p0.9999: 16.447 ms/op
                 listUser·p1.00:   17.662 ms/op

Iteration   2: 3.752 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.756 ms/op
                 listUser·p0.50:   3.580 ms/op
                 listUser·p0.90:   4.948 ms/op
                 listUser·p0.95:   5.644 ms/op
                 listUser·p0.99:   6.726 ms/op
                 listUser·p0.999:  15.427 ms/op
                 listUser·p0.9999: 23.298 ms/op
                 listUser·p1.00:   25.362 ms/op

Iteration   3: 3.796 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.903 ms/op
                 listUser·p0.50:   3.654 ms/op
                 listUser·p0.90:   4.817 ms/op
                 listUser·p0.95:   5.390 ms/op
                 listUser·p0.99:   6.771 ms/op
                 listUser·p0.999:  15.820 ms/op
                 listUser·p0.9999: 24.025 ms/op
                 listUser·p1.00:   24.543 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 255372
  mean =      3.760 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8848 
    [ 2.500,  5.000) = 223680 
    [ 5.000,  7.500) = 21458 
    [ 7.500, 10.000) = 836 
    [10.000, 12.500) = 185 
    [12.500, 15.000) = 155 
    [15.000, 17.500) = 111 
    [17.500, 20.000) = 35 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 54 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.756 ms/op
     p(50.0000) =      3.604 ms/op
     p(90.0000) =      4.899 ms/op
     p(95.0000) =      5.562 ms/op
     p(99.0000) =      6.840 ms/op
     p(99.9000) =     14.238 ms/op
     p(99.9900) =     23.674 ms/op
     p(99.9990) =     24.945 ms/op
     p(99.9999) =     25.362 ms/op
    p(100.0000) =     25.362 ms/op


# Run complete. Total time: 00:13:02

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.716 ± 7.425  ops/ms
ClientGrpc.existUser                       thrpt       3  11.346 ± 2.234  ops/ms
ClientGrpc.getUser                         thrpt       3  10.817 ± 0.925  ops/ms
ClientGrpc.listUser                        thrpt       3   8.332 ± 1.302  ops/ms
ClientGrpc.createUser                       avgt       3   2.970 ± 1.037   ms/op
ClientGrpc.existUser                        avgt       3   2.834 ± 0.726   ms/op
ClientGrpc.getUser                          avgt       3   2.991 ± 0.659   ms/op
ClientGrpc.listUser                         avgt       3   3.859 ± 0.346   ms/op
ClientGrpc.createUser                     sample  320111   2.999 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.717           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.986           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.518           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.715           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.424           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.028           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.035           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.331           ms/op
ClientGrpc.existUser                      sample  335132   2.864 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.549           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.867           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.408           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.666           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.432           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.954           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.909           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.414           ms/op
ClientGrpc.getUser                        sample  323131   2.969 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.584           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.982           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.490           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.690           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.383           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.151           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          23.225           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          25.985           ms/op
ClientGrpc.listUser                       sample  255372   3.760 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.756           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.604           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.899           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.562           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.840           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.238           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.674           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.362           ms/op
