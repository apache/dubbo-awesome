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
# Warmup Iteration   1: 4.696 ops/ms
# Warmup Iteration   2: 9.265 ops/ms
# Warmup Iteration   3: 10.349 ops/ms
Iteration   1: 10.864 ops/ms
Iteration   2: 10.703 ops/ms
Iteration   3: 10.549 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.705 ±(99.9%) 2.868 ops/ms [Average]
  (min, avg, max) = (10.549, 10.705, 10.864), stdev = 0.157
  CI (99.9%): [7.837, 13.573] (assumes normal distribution)


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
# Warmup Iteration   1: 8.109 ops/ms
# Warmup Iteration   2: 10.823 ops/ms
# Warmup Iteration   3: 11.456 ops/ms
Iteration   1: 11.252 ops/ms
Iteration   2: 11.438 ops/ms
Iteration   3: 11.589 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.426 ±(99.9%) 3.079 ops/ms [Average]
  (min, avg, max) = (11.252, 11.426, 11.589), stdev = 0.169
  CI (99.9%): [8.347, 14.506] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.030 ops/ms
# Warmup Iteration   2: 10.433 ops/ms
# Warmup Iteration   3: 10.751 ops/ms
Iteration   1: 10.660 ops/ms
Iteration   2: 10.718 ops/ms
Iteration   3: 10.718 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.699 ±(99.9%) 0.620 ops/ms [Average]
  (min, avg, max) = (10.660, 10.699, 10.718), stdev = 0.034
  CI (99.9%): [10.079, 11.319] (assumes normal distribution)


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
# Warmup Iteration   1: 6.056 ops/ms
# Warmup Iteration   2: 7.931 ops/ms
# Warmup Iteration   3: 8.307 ops/ms
Iteration   1: 8.396 ops/ms
Iteration   2: 8.347 ops/ms
Iteration   3: 8.319 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.354 ±(99.9%) 0.713 ops/ms [Average]
  (min, avg, max) = (8.319, 8.354, 8.396), stdev = 0.039
  CI (99.9%): [7.641, 9.067] (assumes normal distribution)


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
# Warmup Iteration   1: 4.262 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.151 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.029 ±(99.9%) 0.002 ms/op
Iteration   1: 3.076 ±(99.9%) 0.003 ms/op
Iteration   2: 3.075 ±(99.9%) 0.003 ms/op
Iteration   3: 2.966 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.039 ±(99.9%) 1.154 ms/op [Average]
  (min, avg, max) = (2.966, 3.039, 3.076), stdev = 0.063
  CI (99.9%): [1.884, 4.193] (assumes normal distribution)


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
# Warmup Iteration   1: 3.661 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.943 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.851 ±(99.9%) 0.002 ms/op
Iteration   1: 2.906 ±(99.9%) 0.002 ms/op
Iteration   2: 2.889 ±(99.9%) 0.002 ms/op
Iteration   3: 2.893 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.896 ±(99.9%) 0.160 ms/op [Average]
  (min, avg, max) = (2.889, 2.896, 2.906), stdev = 0.009
  CI (99.9%): [2.736, 3.056] (assumes normal distribution)


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
# Warmup Iteration   1: 3.738 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 3.012 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.046 ±(99.9%) 0.003 ms/op
Iteration   1: 3.011 ±(99.9%) 0.004 ms/op
Iteration   2: 2.965 ±(99.9%) 0.003 ms/op
Iteration   3: 2.949 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.975 ±(99.9%) 0.595 ms/op [Average]
  (min, avg, max) = (2.949, 2.975, 3.011), stdev = 0.033
  CI (99.9%): [2.380, 3.570] (assumes normal distribution)


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
# Warmup Iteration   1: 5.168 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.915 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.848 ±(99.9%) 0.016 ms/op
Iteration   1: 3.907 ±(99.9%) 0.015 ms/op
Iteration   2: 3.930 ±(99.9%) 0.054 ms/op
Iteration   3: 3.819 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.886 ±(99.9%) 1.069 ms/op [Average]
  (min, avg, max) = (3.819, 3.886, 3.930), stdev = 0.059
  CI (99.9%): [2.816, 4.955] (assumes normal distribution)


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
# Warmup Iteration   1: 4.107 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.145 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.033 ±(99.9%) 0.007 ms/op
Iteration   1: 3.034 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.855 ms/op
                 createUser·p0.50:   2.994 ms/op
                 createUser·p0.90:   3.588 ms/op
                 createUser·p0.95:   3.801 ms/op
                 createUser·p0.99:   4.514 ms/op
                 createUser·p0.999:  9.463 ms/op
                 createUser·p0.9999: 13.393 ms/op
                 createUser·p1.00:   13.566 ms/op

Iteration   2: 2.995 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.460 ms/op
                 createUser·p0.50:   2.982 ms/op
                 createUser·p0.90:   3.428 ms/op
                 createUser·p0.95:   3.613 ms/op
                 createUser·p0.99:   4.350 ms/op
                 createUser·p0.999:  9.034 ms/op
                 createUser·p0.9999: 14.904 ms/op
                 createUser·p1.00:   15.270 ms/op

Iteration   3: 3.033 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.721 ms/op
                 createUser·p0.50:   3.002 ms/op
                 createUser·p0.90:   3.600 ms/op
                 createUser·p0.95:   3.797 ms/op
                 createUser·p0.99:   4.628 ms/op
                 createUser·p0.999:  7.651 ms/op
                 createUser·p0.9999: 14.643 ms/op
                 createUser·p1.00:   16.597 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 317686
  mean =      3.020 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 983 
    [ 1.250,  2.500) = 23263 
    [ 2.500,  3.750) = 277261 
    [ 3.750,  5.000) = 14459 
    [ 5.000,  6.250) = 875 
    [ 6.250,  7.500) = 403 
    [ 7.500,  8.750) = 107 
    [ 8.750, 10.000) = 115 
    [10.000, 11.250) = 8 
    [11.250, 12.500) = 64 
    [12.500, 13.750) = 61 
    [13.750, 15.000) = 71 
    [15.000, 16.250) = 9 
    [16.250, 17.500) = 7 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.460 ms/op
     p(50.0000) =      2.990 ms/op
     p(90.0000) =      3.543 ms/op
     p(95.0000) =      3.756 ms/op
     p(99.0000) =      4.506 ms/op
     p(99.9000) =      9.000 ms/op
     p(99.9900) =     14.586 ms/op
     p(99.9990) =     16.487 ms/op
     p(99.9999) =     16.597 ms/op
    p(100.0000) =     16.597 ms/op


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
# Warmup Iteration   1: 3.879 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.025 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.906 ±(99.9%) 0.006 ms/op
Iteration   1: 2.937 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.562 ms/op
                 existUser·p0.50:   2.904 ms/op
                 existUser·p0.90:   3.482 ms/op
                 existUser·p0.95:   3.707 ms/op
                 existUser·p0.99:   4.522 ms/op
                 existUser·p0.999:  7.726 ms/op
                 existUser·p0.9999: 14.713 ms/op
                 existUser·p1.00:   14.860 ms/op

Iteration   2: 2.921 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.342 ms/op
                 existUser·p0.50:   2.912 ms/op
                 existUser·p0.90:   3.338 ms/op
                 existUser·p0.95:   3.547 ms/op
                 existUser·p0.99:   4.334 ms/op
                 existUser·p0.999:  7.301 ms/op
                 existUser·p0.9999: 17.041 ms/op
                 existUser·p1.00:   17.170 ms/op

Iteration   3: 2.918 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.518 ms/op
                 existUser·p0.50:   2.912 ms/op
                 existUser·p0.90:   3.564 ms/op
                 existUser·p0.95:   3.809 ms/op
                 existUser·p0.99:   4.678 ms/op
                 existUser·p0.999:  11.017 ms/op
                 existUser·p0.9999: 27.690 ms/op
                 existUser·p1.00:   29.426 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 327916
  mean =      2.925 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 42271 
    [ 2.500,  5.000) = 284156 
    [ 5.000,  7.500) = 1064 
    [ 7.500, 10.000) = 141 
    [10.000, 12.500) = 92 
    [12.500, 15.000) = 81 
    [15.000, 17.500) = 64 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.342 ms/op
     p(50.0000) =      2.912 ms/op
     p(90.0000) =      3.465 ms/op
     p(95.0000) =      3.707 ms/op
     p(99.0000) =      4.538 ms/op
     p(99.9000) =      8.569 ms/op
     p(99.9900) =     20.835 ms/op
     p(99.9990) =     29.187 ms/op
     p(99.9999) =     29.426 ms/op
    p(100.0000) =     29.426 ms/op


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
# Warmup Iteration   1: 3.954 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.245 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.146 ±(99.9%) 0.007 ms/op
Iteration   1: 3.115 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.695 ms/op
                 getUser·p0.50:   3.064 ms/op
                 getUser·p0.90:   3.572 ms/op
                 getUser·p0.95:   3.826 ms/op
                 getUser·p0.99:   4.722 ms/op
                 getUser·p0.999:  11.873 ms/op
                 getUser·p0.9999: 15.781 ms/op
                 getUser·p1.00:   16.728 ms/op

Iteration   2: 3.090 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.727 ms/op
                 getUser·p0.50:   3.064 ms/op
                 getUser·p0.90:   3.588 ms/op
                 getUser·p0.95:   3.842 ms/op
                 getUser·p0.99:   4.784 ms/op
                 getUser·p0.999:  9.253 ms/op
                 getUser·p0.9999: 21.153 ms/op
                 getUser·p1.00:   22.249 ms/op

Iteration   3: 3.141 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.698 ms/op
                 getUser·p0.50:   3.125 ms/op
                 getUser·p0.90:   3.727 ms/op
                 getUser·p0.95:   3.940 ms/op
                 getUser·p0.99:   4.801 ms/op
                 getUser·p0.999:  10.375 ms/op
                 getUser·p0.9999: 18.377 ms/op
                 getUser·p1.00:   18.809 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 308120
  mean =      3.115 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16773 
    [ 2.500,  5.000) = 289005 
    [ 5.000,  7.500) = 1587 
    [ 7.500, 10.000) = 450 
    [10.000, 12.500) = 133 
    [12.500, 15.000) = 50 
    [15.000, 17.500) = 65 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.695 ms/op
     p(50.0000) =      3.080 ms/op
     p(90.0000) =      3.637 ms/op
     p(95.0000) =      3.879 ms/op
     p(99.0000) =      4.751 ms/op
     p(99.9000) =      9.976 ms/op
     p(99.9900) =     19.358 ms/op
     p(99.9990) =     22.032 ms/op
     p(99.9999) =     22.249 ms/op
    p(100.0000) =     22.249 ms/op


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
# Warmup Iteration   1: 4.993 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 4.034 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.935 ±(99.9%) 0.011 ms/op
Iteration   1: 3.923 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.233 ms/op
                 listUser·p0.50:   3.752 ms/op
                 listUser·p0.90:   5.054 ms/op
                 listUser·p0.95:   5.964 ms/op
                 listUser·p0.99:   7.111 ms/op
                 listUser·p0.999:  15.028 ms/op
                 listUser·p0.9999: 18.935 ms/op
                 listUser·p1.00:   19.169 ms/op

Iteration   2: 4.034 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.985 ms/op
                 listUser·p0.50:   3.854 ms/op
                 listUser·p0.90:   5.095 ms/op
                 listUser·p0.95:   5.784 ms/op
                 listUser·p0.99:   7.348 ms/op
                 listUser·p0.999:  15.574 ms/op
                 listUser·p0.9999: 24.906 ms/op
                 listUser·p1.00:   25.362 ms/op

Iteration   3: 3.959 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.822 ms/op
                 listUser·p0.50:   3.740 ms/op
                 listUser·p0.90:   5.104 ms/op
                 listUser·p0.95:   5.628 ms/op
                 listUser·p0.99:   7.700 ms/op
                 listUser·p0.999:  15.499 ms/op
                 listUser·p0.9999: 19.661 ms/op
                 listUser·p1.00:   20.447 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 241714
  mean =      3.971 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3803 
    [ 2.500,  5.000) = 211486 
    [ 5.000,  7.500) = 24234 
    [ 7.500, 10.000) = 1561 
    [10.000, 12.500) = 198 
    [12.500, 15.000) = 157 
    [15.000, 17.500) = 143 
    [17.500, 20.000) = 64 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.822 ms/op
     p(50.0000) =      3.789 ms/op
     p(90.0000) =      5.087 ms/op
     p(95.0000) =      5.800 ms/op
     p(99.0000) =      7.373 ms/op
     p(99.9000) =     15.422 ms/op
     p(99.9900) =     23.942 ms/op
     p(99.9990) =     25.297 ms/op
     p(99.9999) =     25.362 ms/op
    p(100.0000) =     25.362 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.705 ± 2.868  ops/ms
ClientGrpc.existUser                       thrpt       3  11.426 ± 3.079  ops/ms
ClientGrpc.getUser                         thrpt       3  10.699 ± 0.620  ops/ms
ClientGrpc.listUser                        thrpt       3   8.354 ± 0.713  ops/ms
ClientGrpc.createUser                       avgt       3   3.039 ± 1.154   ms/op
ClientGrpc.existUser                        avgt       3   2.896 ± 0.160   ms/op
ClientGrpc.getUser                          avgt       3   2.975 ± 0.595   ms/op
ClientGrpc.listUser                         avgt       3   3.886 ± 1.069   ms/op
ClientGrpc.createUser                     sample  317686   3.020 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.460           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.990           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.543           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.756           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.506           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.000           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          14.586           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          16.597           ms/op
ClientGrpc.existUser                      sample  327916   2.925 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.342           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.912           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.465           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.707           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.538           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.569           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.835           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          29.426           ms/op
ClientGrpc.getUser                        sample  308120   3.115 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.695           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.080           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.637           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.879           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.751           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.976           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.358           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.249           ms/op
ClientGrpc.listUser                       sample  241714   3.971 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.822           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.789           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.087           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.800           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.373           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.422           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.942           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.362           ms/op
