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
# Warmup Iteration   1: 4.629 ops/ms
# Warmup Iteration   2: 9.300 ops/ms
# Warmup Iteration   3: 10.505 ops/ms
Iteration   1: 10.500 ops/ms
Iteration   2: 10.497 ops/ms
Iteration   3: 10.568 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.521 ±(99.9%) 0.735 ops/ms [Average]
  (min, avg, max) = (10.497, 10.521, 10.568), stdev = 0.040
  CI (99.9%): [9.787, 11.256] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.568 ops/ms
# Warmup Iteration   2: 10.625 ops/ms
# Warmup Iteration   3: 11.155 ops/ms
Iteration   1: 11.371 ops/ms
Iteration   2: 11.213 ops/ms
Iteration   3: 11.125 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.237 ±(99.9%) 2.277 ops/ms [Average]
  (min, avg, max) = (11.125, 11.237, 11.371), stdev = 0.125
  CI (99.9%): [8.960, 13.513] (assumes normal distribution)


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
# Warmup Iteration   1: 8.282 ops/ms
# Warmup Iteration   2: 10.334 ops/ms
# Warmup Iteration   3: 10.352 ops/ms
Iteration   1: 10.483 ops/ms
Iteration   2: 10.582 ops/ms
Iteration   3: 10.559 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.541 ±(99.9%) 0.942 ops/ms [Average]
  (min, avg, max) = (10.483, 10.541, 10.582), stdev = 0.052
  CI (99.9%): [9.599, 11.483] (assumes normal distribution)


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
# Warmup Iteration   1: 5.457 ops/ms
# Warmup Iteration   2: 8.094 ops/ms
# Warmup Iteration   3: 8.118 ops/ms
Iteration   1: 8.182 ops/ms
Iteration   2: 8.260 ops/ms
Iteration   3: 8.673 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.372 ±(99.9%) 4.818 ops/ms [Average]
  (min, avg, max) = (8.182, 8.372, 8.673), stdev = 0.264
  CI (99.9%): [3.554, 13.189] (assumes normal distribution)


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
# Warmup Iteration   1: 4.100 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.132 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 3.057 ±(99.9%) 0.003 ms/op
Iteration   1: 3.051 ±(99.9%) 0.002 ms/op
Iteration   2: 3.022 ±(99.9%) 0.003 ms/op
Iteration   3: 2.992 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.022 ±(99.9%) 0.537 ms/op [Average]
  (min, avg, max) = (2.992, 3.022, 3.051), stdev = 0.029
  CI (99.9%): [2.484, 3.559] (assumes normal distribution)


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
# Warmup Iteration   1: 3.853 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.985 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.751 ±(99.9%) 0.005 ms/op
Iteration   1: 2.850 ±(99.9%) 0.005 ms/op
Iteration   2: 2.875 ±(99.9%) 0.003 ms/op
Iteration   3: 2.852 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.859 ±(99.9%) 0.259 ms/op [Average]
  (min, avg, max) = (2.850, 2.859, 2.875), stdev = 0.014
  CI (99.9%): [2.600, 3.118] (assumes normal distribution)


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
# Warmup Iteration   1: 4.032 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.075 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.016 ±(99.9%) 0.003 ms/op
Iteration   1: 3.041 ±(99.9%) 0.003 ms/op
Iteration   2: 2.982 ±(99.9%) 0.003 ms/op
Iteration   3: 2.963 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.995 ±(99.9%) 0.744 ms/op [Average]
  (min, avg, max) = (2.963, 2.995, 3.041), stdev = 0.041
  CI (99.9%): [2.251, 3.740] (assumes normal distribution)


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
# Warmup Iteration   1: 5.125 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 3.969 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 3.781 ±(99.9%) 0.047 ms/op
Iteration   1: 3.898 ±(99.9%) 0.017 ms/op
Iteration   2: 3.849 ±(99.9%) 0.017 ms/op
Iteration   3: 3.876 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.874 ±(99.9%) 0.450 ms/op [Average]
  (min, avg, max) = (3.849, 3.874, 3.898), stdev = 0.025
  CI (99.9%): [3.425, 4.324] (assumes normal distribution)


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
# Warmup Iteration   1: 4.039 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.134 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.033 ±(99.9%) 0.006 ms/op
Iteration   1: 3.077 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.803 ms/op
                 createUser·p0.50:   3.035 ms/op
                 createUser·p0.90:   3.629 ms/op
                 createUser·p0.95:   3.797 ms/op
                 createUser·p0.99:   4.358 ms/op
                 createUser·p0.999:  8.038 ms/op
                 createUser·p0.9999: 11.725 ms/op
                 createUser·p1.00:   11.928 ms/op

Iteration   2: 3.019 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.823 ms/op
                 createUser·p0.50:   2.990 ms/op
                 createUser·p0.90:   3.543 ms/op
                 createUser·p0.95:   3.830 ms/op
                 createUser·p0.99:   4.514 ms/op
                 createUser·p0.999:  7.259 ms/op
                 createUser·p0.9999: 12.645 ms/op
                 createUser·p1.00:   13.009 ms/op

Iteration   3: 3.010 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.588 ms/op
                 createUser·p0.50:   2.998 ms/op
                 createUser·p0.90:   3.400 ms/op
                 createUser·p0.95:   3.523 ms/op
                 createUser·p0.99:   4.075 ms/op
                 createUser·p0.999:  6.213 ms/op
                 createUser·p0.9999: 14.670 ms/op
                 createUser·p1.00:   15.073 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 316168
  mean =      3.035 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 594 
    [ 1.250,  2.500) = 16915 
    [ 2.500,  3.750) = 283729 
    [ 3.750,  5.000) = 13684 
    [ 5.000,  6.250) = 710 
    [ 6.250,  7.500) = 254 
    [ 7.500,  8.750) = 52 
    [ 8.750, 10.000) = 34 
    [10.000, 11.250) = 27 
    [11.250, 12.500) = 98 
    [12.500, 13.750) = 27 
    [13.750, 15.000) = 42 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.588 ms/op
     p(50.0000) =      3.006 ms/op
     p(90.0000) =      3.514 ms/op
     p(95.0000) =      3.736 ms/op
     p(99.0000) =      4.399 ms/op
     p(99.9000) =      7.209 ms/op
     p(99.9900) =     14.332 ms/op
     p(99.9990) =     14.932 ms/op
     p(99.9999) =     15.073 ms/op
    p(100.0000) =     15.073 ms/op


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
# Warmup Iteration   1: 3.677 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 2.962 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.800 ±(99.9%) 0.006 ms/op
Iteration   1: 2.900 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.546 ms/op
                 existUser·p0.50:   2.884 ms/op
                 existUser·p0.90:   3.342 ms/op
                 existUser·p0.95:   3.572 ms/op
                 existUser·p0.99:   4.317 ms/op
                 existUser·p0.999:  6.480 ms/op
                 existUser·p0.9999: 11.336 ms/op
                 existUser·p1.00:   11.911 ms/op

Iteration   2: 2.885 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.640 ms/op
                 existUser·p0.50:   2.892 ms/op
                 existUser·p0.90:   3.297 ms/op
                 existUser·p0.95:   3.502 ms/op
                 existUser·p0.99:   4.350 ms/op
                 existUser·p0.999:  9.880 ms/op
                 existUser·p0.9999: 21.788 ms/op
                 existUser·p1.00:   22.446 ms/op

Iteration   3: 2.865 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.638 ms/op
                 existUser·p0.50:   2.863 ms/op
                 existUser·p0.90:   3.224 ms/op
                 existUser·p0.95:   3.387 ms/op
                 existUser·p0.99:   4.153 ms/op
                 existUser·p0.999:  6.877 ms/op
                 existUser·p0.9999: 14.694 ms/op
                 existUser·p1.00:   17.498 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 332939
  mean =      2.883 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 38562 
    [ 2.500,  5.000) = 293395 
    [ 5.000,  7.500) = 597 
    [ 7.500, 10.000) = 149 
    [10.000, 12.500) = 108 
    [12.500, 15.000) = 95 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.546 ms/op
     p(50.0000) =      2.879 ms/op
     p(90.0000) =      3.289 ms/op
     p(95.0000) =      3.498 ms/op
     p(99.0000) =      4.284 ms/op
     p(99.9000) =      8.667 ms/op
     p(99.9900) =     16.742 ms/op
     p(99.9990) =     22.337 ms/op
     p(99.9999) =     22.446 ms/op
    p(100.0000) =     22.446 ms/op


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
# Warmup Iteration   1: 4.061 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.076 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.994 ±(99.9%) 0.006 ms/op
Iteration   1: 2.998 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.484 ms/op
                 getUser·p0.50:   2.994 ms/op
                 getUser·p0.90:   3.523 ms/op
                 getUser·p0.95:   3.785 ms/op
                 getUser·p0.99:   4.497 ms/op
                 getUser·p0.999:  6.734 ms/op
                 getUser·p0.9999: 12.451 ms/op
                 getUser·p1.00:   12.911 ms/op

Iteration   2: 2.985 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.605 ms/op
                 getUser·p0.50:   2.986 ms/op
                 getUser·p0.90:   3.576 ms/op
                 getUser·p0.95:   3.801 ms/op
                 getUser·p0.99:   4.383 ms/op
                 getUser·p0.999:  7.040 ms/op
                 getUser·p0.9999: 13.956 ms/op
                 getUser·p1.00:   14.451 ms/op

Iteration   3: 3.009 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.829 ms/op
                 getUser·p0.50:   2.990 ms/op
                 getUser·p0.90:   3.514 ms/op
                 getUser·p0.95:   3.830 ms/op
                 getUser·p0.99:   4.489 ms/op
                 getUser·p0.999:  7.021 ms/op
                 getUser·p0.9999: 15.249 ms/op
                 getUser·p1.00:   16.515 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 320349
  mean =      2.997 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1338 
    [ 1.250,  2.500) = 30598 
    [ 2.500,  3.750) = 270040 
    [ 3.750,  5.000) = 17049 
    [ 5.000,  6.250) = 762 
    [ 6.250,  7.500) = 349 
    [ 7.500,  8.750) = 42 
    [ 8.750, 10.000) = 11 
    [10.000, 11.250) = 5 
    [11.250, 12.500) = 18 
    [12.500, 13.750) = 68 
    [13.750, 15.000) = 49 
    [15.000, 16.250) = 16 
    [16.250, 17.500) = 4 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.484 ms/op
     p(50.0000) =      2.990 ms/op
     p(90.0000) =      3.543 ms/op
     p(95.0000) =      3.805 ms/op
     p(99.0000) =      4.448 ms/op
     p(99.9000) =      6.933 ms/op
     p(99.9900) =     14.746 ms/op
     p(99.9990) =     16.377 ms/op
     p(99.9999) =     16.515 ms/op
    p(100.0000) =     16.515 ms/op


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
# Warmup Iteration   1: 4.450 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 4.061 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.808 ±(99.9%) 0.010 ms/op
Iteration   1: 3.916 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.118 ms/op
                 listUser·p0.50:   3.781 ms/op
                 listUser·p0.90:   4.899 ms/op
                 listUser·p0.95:   5.685 ms/op
                 listUser·p0.99:   6.717 ms/op
                 listUser·p0.999:  12.081 ms/op
                 listUser·p0.9999: 17.629 ms/op
                 listUser·p1.00:   19.104 ms/op

Iteration   2: 3.833 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.706 ms/op
                 listUser·p0.50:   3.690 ms/op
                 listUser·p0.90:   4.907 ms/op
                 listUser·p0.95:   5.489 ms/op
                 listUser·p0.99:   6.685 ms/op
                 listUser·p0.999:  12.861 ms/op
                 listUser·p0.9999: 16.722 ms/op
                 listUser·p1.00:   16.941 ms/op

Iteration   3: 3.850 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.935 ms/op
                 listUser·p0.50:   3.719 ms/op
                 listUser·p0.90:   4.612 ms/op
                 listUser·p0.95:   5.489 ms/op
                 listUser·p0.99:   6.627 ms/op
                 listUser·p0.999:  14.068 ms/op
                 listUser·p0.9999: 21.868 ms/op
                 listUser·p1.00:   22.184 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 248302
  mean =      3.866 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5278 
    [ 2.500,  5.000) = 221951 
    [ 5.000,  7.500) = 20099 
    [ 7.500, 10.000) = 564 
    [10.000, 12.500) = 109 
    [12.500, 15.000) = 146 
    [15.000, 17.500) = 94 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.706 ms/op
     p(50.0000) =      3.731 ms/op
     p(90.0000) =      4.833 ms/op
     p(95.0000) =      5.554 ms/op
     p(99.0000) =      6.676 ms/op
     p(99.9000) =     13.201 ms/op
     p(99.9900) =     20.578 ms/op
     p(99.9990) =     22.135 ms/op
     p(99.9999) =     22.184 ms/op
    p(100.0000) =     22.184 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.521 ± 0.735  ops/ms
ClientGrpc.existUser                       thrpt       3  11.237 ± 2.277  ops/ms
ClientGrpc.getUser                         thrpt       3  10.541 ± 0.942  ops/ms
ClientGrpc.listUser                        thrpt       3   8.372 ± 4.818  ops/ms
ClientGrpc.createUser                       avgt       3   3.022 ± 0.537   ms/op
ClientGrpc.existUser                        avgt       3   2.859 ± 0.259   ms/op
ClientGrpc.getUser                          avgt       3   2.995 ± 0.744   ms/op
ClientGrpc.listUser                         avgt       3   3.874 ± 0.450   ms/op
ClientGrpc.createUser                     sample  316168   3.035 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.588           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.006           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.514           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.736           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.399           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.209           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          14.332           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          15.073           ms/op
ClientGrpc.existUser                      sample  332939   2.883 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.546           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.879           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.289           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.498           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.284           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.667           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.742           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.446           ms/op
ClientGrpc.getUser                        sample  320349   2.997 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.484           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.990           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.543           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.805           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.448           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.933           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          14.746           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          16.515           ms/op
ClientGrpc.listUser                       sample  248302   3.866 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.706           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.731           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.833           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.554           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.676           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.201           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          20.578           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          22.184           ms/op
