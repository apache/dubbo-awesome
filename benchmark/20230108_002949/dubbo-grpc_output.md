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
# Warmup Iteration   1: 4.186 ops/ms
# Warmup Iteration   2: 9.241 ops/ms
# Warmup Iteration   3: 10.001 ops/ms
Iteration   1: 10.117 ops/ms
Iteration   2: 10.187 ops/ms
Iteration   3: 10.544 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.282 ±(99.9%) 4.174 ops/ms [Average]
  (min, avg, max) = (10.117, 10.282, 10.544), stdev = 0.229
  CI (99.9%): [6.109, 14.456] (assumes normal distribution)


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
# Warmup Iteration   1: 7.359 ops/ms
# Warmup Iteration   2: 10.095 ops/ms
# Warmup Iteration   3: 10.616 ops/ms
Iteration   1: 10.563 ops/ms
Iteration   2: 10.781 ops/ms
Iteration   3: 10.701 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.681 ±(99.9%) 2.012 ops/ms [Average]
  (min, avg, max) = (10.563, 10.681, 10.781), stdev = 0.110
  CI (99.9%): [8.669, 12.694] (assumes normal distribution)


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
# Warmup Iteration   1: 6.802 ops/ms
# Warmup Iteration   2: 9.939 ops/ms
# Warmup Iteration   3: 10.005 ops/ms
Iteration   1: 10.044 ops/ms
Iteration   2: 9.991 ops/ms
Iteration   3: 10.041 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.026 ±(99.9%) 0.541 ops/ms [Average]
  (min, avg, max) = (9.991, 10.026, 10.044), stdev = 0.030
  CI (99.9%): [9.485, 10.567] (assumes normal distribution)


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
# Warmup Iteration   1: 5.419 ops/ms
# Warmup Iteration   2: 7.529 ops/ms
# Warmup Iteration   3: 7.850 ops/ms
Iteration   1: 7.938 ops/ms
Iteration   2: 7.886 ops/ms
Iteration   3: 7.870 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.898 ±(99.9%) 0.648 ops/ms [Average]
  (min, avg, max) = (7.870, 7.898, 7.938), stdev = 0.036
  CI (99.9%): [7.250, 8.546] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.325 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.211 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.165 ±(99.9%) 0.002 ms/op
Iteration   1: 3.109 ±(99.9%) 0.002 ms/op
Iteration   2: 3.116 ±(99.9%) 0.004 ms/op
Iteration   3: 3.216 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.147 ±(99.9%) 1.089 ms/op [Average]
  (min, avg, max) = (3.109, 3.147, 3.216), stdev = 0.060
  CI (99.9%): [2.058, 4.236] (assumes normal distribution)


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
# Warmup Iteration   1: 3.919 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.147 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.067 ±(99.9%) 0.002 ms/op
Iteration   1: 3.039 ±(99.9%) 0.002 ms/op
Iteration   2: 2.891 ±(99.9%) 0.001 ms/op
Iteration   3: 2.949 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.960 ±(99.9%) 1.362 ms/op [Average]
  (min, avg, max) = (2.891, 2.960, 3.039), stdev = 0.075
  CI (99.9%): [1.598, 4.321] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.136 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.237 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.265 ±(99.9%) 0.002 ms/op
Iteration   1: 3.130 ±(99.9%) 0.003 ms/op
Iteration   2: 3.138 ±(99.9%) 0.009 ms/op
Iteration   3: 3.185 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.151 ±(99.9%) 0.540 ms/op [Average]
  (min, avg, max) = (3.130, 3.151, 3.185), stdev = 0.030
  CI (99.9%): [2.611, 3.691] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.467 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 4.194 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.045 ±(99.9%) 0.013 ms/op
Iteration   1: 4.052 ±(99.9%) 0.009 ms/op
Iteration   2: 4.020 ±(99.9%) 0.008 ms/op
Iteration   3: 3.976 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.016 ±(99.9%) 0.703 ms/op [Average]
  (min, avg, max) = (3.976, 4.016, 4.052), stdev = 0.039
  CI (99.9%): [3.313, 4.719] (assumes normal distribution)


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
# Warmup Iteration   1: 4.327 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.237 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.145 ±(99.9%) 0.007 ms/op
Iteration   1: 3.181 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.696 ms/op
                 createUser·p0.50:   3.166 ms/op
                 createUser·p0.90:   3.879 ms/op
                 createUser·p0.95:   4.030 ms/op
                 createUser·p0.99:   4.309 ms/op
                 createUser·p0.999:  7.455 ms/op
                 createUser·p0.9999: 19.888 ms/op
                 createUser·p1.00:   20.218 ms/op

Iteration   2: 3.149 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.392 ms/op
                 createUser·p0.50:   3.125 ms/op
                 createUser·p0.90:   3.801 ms/op
                 createUser·p0.95:   3.969 ms/op
                 createUser·p0.99:   4.317 ms/op
                 createUser·p0.999:  8.213 ms/op
                 createUser·p0.9999: 21.098 ms/op
                 createUser·p1.00:   21.692 ms/op

Iteration   3: 3.149 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.648 ms/op
                 createUser·p0.50:   3.113 ms/op
                 createUser·p0.90:   3.809 ms/op
                 createUser·p0.95:   3.965 ms/op
                 createUser·p0.99:   4.301 ms/op
                 createUser·p0.999:  6.505 ms/op
                 createUser·p0.9999: 33.391 ms/op
                 createUser·p1.00:   33.686 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 303995
  mean =      3.160 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25549 
    [ 2.500,  5.000) = 277497 
    [ 5.000,  7.500) = 632 
    [ 7.500, 10.000) = 156 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 12 
    [17.500, 20.000) = 45 
    [20.000, 22.500) = 65 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 17 
    [32.500, 35.000) = 15 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.392 ms/op
     p(50.0000) =      3.133 ms/op
     p(90.0000) =      3.834 ms/op
     p(95.0000) =      3.994 ms/op
     p(99.0000) =      4.309 ms/op
     p(99.9000) =      7.586 ms/op
     p(99.9900) =     31.602 ms/op
     p(99.9990) =     33.617 ms/op
     p(99.9999) =     33.686 ms/op
    p(100.0000) =     33.686 ms/op


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
# Warmup Iteration   1: 3.936 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.142 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.027 ±(99.9%) 0.006 ms/op
Iteration   1: 3.033 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.689 ms/op
                 existUser·p0.50:   2.998 ms/op
                 existUser·p0.90:   3.690 ms/op
                 existUser·p0.95:   3.908 ms/op
                 existUser·p0.99:   4.415 ms/op
                 existUser·p0.999:  7.739 ms/op
                 existUser·p0.9999: 19.643 ms/op
                 existUser·p1.00:   20.316 ms/op

Iteration   2: 3.057 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.666 ms/op
                 existUser·p0.50:   3.027 ms/op
                 existUser·p0.90:   3.764 ms/op
                 existUser·p0.95:   3.940 ms/op
                 existUser·p0.99:   4.334 ms/op
                 existUser·p0.999:  7.191 ms/op
                 existUser·p0.9999: 14.689 ms/op
                 existUser·p1.00:   17.105 ms/op

Iteration   3: 2.989 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.846 ms/op
                 existUser·p0.50:   2.961 ms/op
                 existUser·p0.90:   3.645 ms/op
                 existUser·p0.95:   3.830 ms/op
                 existUser·p0.99:   4.190 ms/op
                 existUser·p0.999:  6.152 ms/op
                 existUser·p0.9999: 15.799 ms/op
                 existUser·p1.00:   17.891 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 317144
  mean =      3.026 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 42947 
    [ 2.500,  5.000) = 273230 
    [ 5.000,  7.500) = 729 
    [ 7.500, 10.000) = 54 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 86 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.666 ms/op
     p(50.0000) =      2.994 ms/op
     p(90.0000) =      3.703 ms/op
     p(95.0000) =      3.895 ms/op
     p(99.0000) =      4.309 ms/op
     p(99.9000) =      6.749 ms/op
     p(99.9900) =     18.336 ms/op
     p(99.9990) =     20.141 ms/op
     p(99.9999) =     20.316 ms/op
    p(100.0000) =     20.316 ms/op


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
# Warmup Iteration   1: 4.218 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.192 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.125 ±(99.9%) 0.007 ms/op
Iteration   1: 3.106 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.560 ms/op
                 getUser·p0.50:   3.060 ms/op
                 getUser·p0.90:   3.777 ms/op
                 getUser·p0.95:   3.985 ms/op
                 getUser·p0.99:   4.522 ms/op
                 getUser·p0.999:  7.437 ms/op
                 getUser·p0.9999: 16.810 ms/op
                 getUser·p1.00:   17.531 ms/op

Iteration   2: 3.185 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.692 ms/op
                 getUser·p0.50:   3.142 ms/op
                 getUser·p0.90:   3.887 ms/op
                 getUser·p0.95:   4.055 ms/op
                 getUser·p0.99:   4.309 ms/op
                 getUser·p0.999:  7.327 ms/op
                 getUser·p0.9999: 18.383 ms/op
                 getUser·p1.00:   18.809 ms/op

Iteration   3: 3.120 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.793 ms/op
                 getUser·p0.50:   3.076 ms/op
                 getUser·p0.90:   3.813 ms/op
                 getUser·p0.95:   3.985 ms/op
                 getUser·p0.99:   4.317 ms/op
                 getUser·p0.999:  6.771 ms/op
                 getUser·p0.9999: 22.315 ms/op
                 getUser·p1.00:   22.479 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 306160
  mean =      3.137 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23307 
    [ 2.500,  5.000) = 281858 
    [ 5.000,  7.500) = 758 
    [ 7.500, 10.000) = 77 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 50 
    [17.500, 20.000) = 65 
    [20.000, 22.500) = 45 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.560 ms/op
     p(50.0000) =      3.088 ms/op
     p(90.0000) =      3.830 ms/op
     p(95.0000) =      4.014 ms/op
     p(99.0000) =      4.366 ms/op
     p(99.9000) =      7.209 ms/op
     p(99.9900) =     21.312 ms/op
     p(99.9990) =     22.442 ms/op
     p(99.9999) =     22.479 ms/op
    p(100.0000) =     22.479 ms/op


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
# Warmup Iteration   1: 5.363 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 4.393 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.115 ±(99.9%) 0.013 ms/op
Iteration   1: 4.122 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.397 ms/op
                 listUser·p0.50:   3.949 ms/op
                 listUser·p0.90:   5.243 ms/op
                 listUser·p0.95:   5.816 ms/op
                 listUser·p0.99:   6.947 ms/op
                 listUser·p0.999:  14.621 ms/op
                 listUser·p0.9999: 22.358 ms/op
                 listUser·p1.00:   23.265 ms/op

Iteration   2: 4.049 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.997 ms/op
                 listUser·p0.50:   3.875 ms/op
                 listUser·p0.90:   5.136 ms/op
                 listUser·p0.95:   5.751 ms/op
                 listUser·p0.99:   6.922 ms/op
                 listUser·p0.999:  16.499 ms/op
                 listUser·p0.9999: 24.619 ms/op
                 listUser·p1.00:   25.264 ms/op

Iteration   3: 4.122 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.918 ms/op
                 listUser·p0.50:   3.928 ms/op
                 listUser·p0.90:   5.308 ms/op
                 listUser·p0.95:   5.939 ms/op
                 listUser·p0.99:   7.184 ms/op
                 listUser·p0.999:  17.280 ms/op
                 listUser·p0.9999: 19.341 ms/op
                 listUser·p1.00:   19.759 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 234231
  mean =      4.097 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1840 
    [ 2.500,  5.000) = 202799 
    [ 5.000,  7.500) = 28256 
    [ 7.500, 10.000) = 849 
    [10.000, 12.500) = 59 
    [12.500, 15.000) = 88 
    [15.000, 17.500) = 205 
    [17.500, 20.000) = 71 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 36 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.918 ms/op
     p(50.0000) =      3.916 ms/op
     p(90.0000) =      5.226 ms/op
     p(95.0000) =      5.841 ms/op
     p(99.0000) =      7.021 ms/op
     p(99.9000) =     16.593 ms/op
     p(99.9900) =     23.448 ms/op
     p(99.9990) =     25.132 ms/op
     p(99.9999) =     25.264 ms/op
    p(100.0000) =     25.264 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.282 ± 4.174  ops/ms
ClientGrpc.existUser                       thrpt       3  10.681 ± 2.012  ops/ms
ClientGrpc.getUser                         thrpt       3  10.026 ± 0.541  ops/ms
ClientGrpc.listUser                        thrpt       3   7.898 ± 0.648  ops/ms
ClientGrpc.createUser                       avgt       3   3.147 ± 1.089   ms/op
ClientGrpc.existUser                        avgt       3   2.960 ± 1.362   ms/op
ClientGrpc.getUser                          avgt       3   3.151 ± 0.540   ms/op
ClientGrpc.listUser                         avgt       3   4.016 ± 0.703   ms/op
ClientGrpc.createUser                     sample  303995   3.160 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.392           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.133           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.834           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.994           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.309           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.586           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          31.602           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          33.686           ms/op
ClientGrpc.existUser                      sample  317144   3.026 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.666           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.994           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.703           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.895           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.309           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.749           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.336           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.316           ms/op
ClientGrpc.getUser                        sample  306160   3.137 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.560           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.088           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.830           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.014           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.366           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.209           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.312           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.479           ms/op
ClientGrpc.listUser                       sample  234231   4.097 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.918           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.916           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.226           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.841           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.021           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.593           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.448           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.264           ms/op
