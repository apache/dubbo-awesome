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
# Warmup Iteration   1: 4.041 ops/ms
# Warmup Iteration   2: 8.585 ops/ms
# Warmup Iteration   3: 10.072 ops/ms
Iteration   1: 10.557 ops/ms
Iteration   2: 10.447 ops/ms
Iteration   3: 10.553 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.519 ±(99.9%) 1.132 ops/ms [Average]
  (min, avg, max) = (10.447, 10.519, 10.557), stdev = 0.062
  CI (99.9%): [9.387, 11.650] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.308 ops/ms
# Warmup Iteration   2: 10.270 ops/ms
# Warmup Iteration   3: 10.826 ops/ms
Iteration   1: 11.053 ops/ms
Iteration   2: 10.909 ops/ms
Iteration   3: 11.602 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.188 ±(99.9%) 6.673 ops/ms [Average]
  (min, avg, max) = (10.909, 11.188, 11.602), stdev = 0.366
  CI (99.9%): [4.515, 17.861] (assumes normal distribution)


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
# Warmup Iteration   1: 6.514 ops/ms
# Warmup Iteration   2: 10.239 ops/ms
# Warmup Iteration   3: 10.442 ops/ms
Iteration   1: 10.452 ops/ms
Iteration   2: 10.602 ops/ms
Iteration   3: 10.545 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.533 ±(99.9%) 1.385 ops/ms [Average]
  (min, avg, max) = (10.452, 10.533, 10.602), stdev = 0.076
  CI (99.9%): [9.148, 11.918] (assumes normal distribution)


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
# Warmup Iteration   1: 5.399 ops/ms
# Warmup Iteration   2: 7.619 ops/ms
# Warmup Iteration   3: 7.904 ops/ms
Iteration   1: 7.898 ops/ms
Iteration   2: 8.118 ops/ms
Iteration   3: 7.993 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.003 ±(99.9%) 2.012 ops/ms [Average]
  (min, avg, max) = (7.898, 8.003, 8.118), stdev = 0.110
  CI (99.9%): [5.991, 10.016] (assumes normal distribution)


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
# Warmup Iteration   1: 4.241 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.151 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.108 ±(99.9%) 0.002 ms/op
Iteration   1: 3.057 ±(99.9%) 0.003 ms/op
Iteration   2: 2.988 ±(99.9%) 0.001 ms/op
Iteration   3: 2.996 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.013 ±(99.9%) 0.686 ms/op [Average]
  (min, avg, max) = (2.988, 3.013, 3.057), stdev = 0.038
  CI (99.9%): [2.328, 3.699] (assumes normal distribution)


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
# Warmup Iteration   1: 4.330 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.054 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.902 ±(99.9%) 0.003 ms/op
Iteration   1: 2.962 ±(99.9%) 0.002 ms/op
Iteration   2: 2.854 ±(99.9%) 0.003 ms/op
Iteration   3: 2.882 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.899 ±(99.9%) 1.028 ms/op [Average]
  (min, avg, max) = (2.854, 2.899, 2.962), stdev = 0.056
  CI (99.9%): [1.872, 3.927] (assumes normal distribution)


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
# Warmup Iteration   1: 4.515 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.138 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.027 ±(99.9%) 0.004 ms/op
Iteration   1: 3.001 ±(99.9%) 0.002 ms/op
Iteration   2: 3.045 ±(99.9%) 0.003 ms/op
Iteration   3: 3.046 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.031 ±(99.9%) 0.472 ms/op [Average]
  (min, avg, max) = (3.001, 3.031, 3.046), stdev = 0.026
  CI (99.9%): [2.559, 3.502] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.966 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 4.123 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 3.988 ±(99.9%) 0.026 ms/op
Iteration   1: 4.105 ±(99.9%) 0.030 ms/op
Iteration   2: 3.893 ±(99.9%) 0.009 ms/op
Iteration   3: 3.999 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.999 ±(99.9%) 1.936 ms/op [Average]
  (min, avg, max) = (3.893, 3.999, 4.105), stdev = 0.106
  CI (99.9%): [2.064, 5.935] (assumes normal distribution)


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
# Warmup Iteration   1: 4.438 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.132 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.021 ±(99.9%) 0.006 ms/op
Iteration   1: 2.973 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.651 ms/op
                 createUser·p0.50:   2.953 ms/op
                 createUser·p0.90:   3.359 ms/op
                 createUser·p0.95:   3.576 ms/op
                 createUser·p0.99:   4.465 ms/op
                 createUser·p0.999:  8.017 ms/op
                 createUser·p0.9999: 14.750 ms/op
                 createUser·p1.00:   15.352 ms/op

Iteration   2: 3.055 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.813 ms/op
                 createUser·p0.50:   3.015 ms/op
                 createUser·p0.90:   3.609 ms/op
                 createUser·p0.95:   3.799 ms/op
                 createUser·p0.99:   4.440 ms/op
                 createUser·p0.999:  8.220 ms/op
                 createUser·p0.9999: 18.220 ms/op
                 createUser·p1.00:   18.973 ms/op

Iteration   3: 3.013 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.924 ms/op
                 createUser·p0.50:   2.986 ms/op
                 createUser·p0.90:   3.428 ms/op
                 createUser·p0.95:   3.600 ms/op
                 createUser·p0.99:   4.268 ms/op
                 createUser·p0.999:  7.385 ms/op
                 createUser·p0.9999: 17.216 ms/op
                 createUser·p1.00:   17.727 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 318520
  mean =      3.013 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 390 
    [ 1.250,  2.500) = 22882 
    [ 2.500,  3.750) = 281825 
    [ 3.750,  5.000) = 12091 
    [ 5.000,  6.250) = 668 
    [ 6.250,  7.500) = 313 
    [ 7.500,  8.750) = 63 
    [ 8.750, 10.000) = 46 
    [10.000, 11.250) = 24 
    [11.250, 12.500) = 47 
    [12.500, 13.750) = 12 
    [13.750, 15.000) = 49 
    [15.000, 16.250) = 52 
    [16.250, 17.500) = 40 
    [17.500, 18.750) = 10 

  Percentiles, ms/op:
      p(0.0000) =      0.651 ms/op
     p(50.0000) =      2.982 ms/op
     p(90.0000) =      3.478 ms/op
     p(95.0000) =      3.695 ms/op
     p(99.0000) =      4.391 ms/op
     p(99.9000) =      7.946 ms/op
     p(99.9900) =     17.236 ms/op
     p(99.9990) =     18.874 ms/op
     p(99.9999) =     18.973 ms/op
    p(100.0000) =     18.973 ms/op


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
# Warmup Iteration   1: 4.101 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.099 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.018 ±(99.9%) 0.006 ms/op
Iteration   1: 2.905 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.665 ms/op
                 existUser·p0.50:   2.884 ms/op
                 existUser·p0.90:   3.412 ms/op
                 existUser·p0.95:   3.621 ms/op
                 existUser·p0.99:   4.473 ms/op
                 existUser·p0.999:  6.526 ms/op
                 existUser·p0.9999: 12.878 ms/op
                 existUser·p1.00:   13.304 ms/op

Iteration   2: 2.930 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.709 ms/op
                 existUser·p0.50:   2.896 ms/op
                 existUser·p0.90:   3.453 ms/op
                 existUser·p0.95:   3.613 ms/op
                 existUser·p0.99:   4.268 ms/op
                 existUser·p0.999:  6.308 ms/op
                 existUser·p0.9999: 13.453 ms/op
                 existUser·p1.00:   13.828 ms/op

Iteration   3: 2.853 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.521 ms/op
                 existUser·p0.50:   2.855 ms/op
                 existUser·p0.90:   3.293 ms/op
                 existUser·p0.95:   3.453 ms/op
                 existUser·p0.99:   4.141 ms/op
                 existUser·p0.999:  7.442 ms/op
                 existUser·p0.9999: 28.107 ms/op
                 existUser·p1.00:   28.639 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 331496
  mean =      2.895 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 44555 
    [ 2.500,  5.000) = 285712 
    [ 5.000,  7.500) = 1001 
    [ 7.500, 10.000) = 99 
    [10.000, 12.500) = 12 
    [12.500, 15.000) = 71 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.521 ms/op
     p(50.0000) =      2.879 ms/op
     p(90.0000) =      3.383 ms/op
     p(95.0000) =      3.572 ms/op
     p(99.0000) =      4.309 ms/op
     p(99.9000) =      6.742 ms/op
     p(99.9900) =     16.861 ms/op
     p(99.9990) =     28.498 ms/op
     p(99.9999) =     28.639 ms/op
    p(100.0000) =     28.639 ms/op


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
# Warmup Iteration   1: 4.369 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.163 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.065 ±(99.9%) 0.007 ms/op
Iteration   1: 3.032 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.700 ms/op
                 getUser·p0.50:   3.006 ms/op
                 getUser·p0.90:   3.465 ms/op
                 getUser·p0.95:   3.736 ms/op
                 getUser·p0.99:   4.506 ms/op
                 getUser·p0.999:  7.070 ms/op
                 getUser·p0.9999: 13.246 ms/op
                 getUser·p1.00:   13.517 ms/op

Iteration   2: 3.010 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.842 ms/op
                 getUser·p0.50:   2.990 ms/op
                 getUser·p0.90:   3.473 ms/op
                 getUser·p0.95:   3.695 ms/op
                 getUser·p0.99:   4.399 ms/op
                 getUser·p0.999:  6.973 ms/op
                 getUser·p0.9999: 14.481 ms/op
                 getUser·p1.00:   14.909 ms/op

Iteration   3: 3.024 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.852 ms/op
                 getUser·p0.50:   2.986 ms/op
                 getUser·p0.90:   3.523 ms/op
                 getUser·p0.95:   3.756 ms/op
                 getUser·p0.99:   4.514 ms/op
                 getUser·p0.999:  7.506 ms/op
                 getUser·p0.9999: 16.889 ms/op
                 getUser·p1.00:   17.170 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 317599
  mean =      3.022 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 592 
    [ 1.250,  2.500) = 19410 
    [ 2.500,  3.750) = 282591 
    [ 3.750,  5.000) = 13442 
    [ 5.000,  6.250) = 890 
    [ 6.250,  7.500) = 403 
    [ 7.500,  8.750) = 81 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 3 
    [11.250, 12.500) = 35 
    [12.500, 13.750) = 65 
    [13.750, 15.000) = 35 
    [15.000, 16.250) = 15 
    [16.250, 17.500) = 37 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.700 ms/op
     p(50.0000) =      2.994 ms/op
     p(90.0000) =      3.490 ms/op
     p(95.0000) =      3.727 ms/op
     p(99.0000) =      4.481 ms/op
     p(99.9000) =      7.171 ms/op
     p(99.9900) =     16.441 ms/op
     p(99.9990) =     17.099 ms/op
     p(99.9999) =     17.170 ms/op
    p(100.0000) =     17.170 ms/op


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
# Warmup Iteration   1: 5.775 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.269 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.010 ±(99.9%) 0.011 ms/op
Iteration   1: 4.030 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.106 ms/op
                 listUser·p0.50:   3.854 ms/op
                 listUser·p0.90:   5.136 ms/op
                 listUser·p0.95:   5.931 ms/op
                 listUser·p0.99:   7.274 ms/op
                 listUser·p0.999:  13.953 ms/op
                 listUser·p0.9999: 16.746 ms/op
                 listUser·p1.00:   17.334 ms/op

Iteration   2: 4.120 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   0.968 ms/op
                 listUser·p0.50:   3.920 ms/op
                 listUser·p0.90:   5.243 ms/op
                 listUser·p0.95:   5.874 ms/op
                 listUser·p0.99:   7.250 ms/op
                 listUser·p0.999:  23.396 ms/op
                 listUser·p0.9999: 25.961 ms/op
                 listUser·p1.00:   27.165 ms/op

Iteration   3: 4.113 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.689 ms/op
                 listUser·p0.50:   3.899 ms/op
                 listUser·p0.90:   5.259 ms/op
                 listUser·p0.95:   5.882 ms/op
                 listUser·p0.99:   7.271 ms/op
                 listUser·p0.999:  14.357 ms/op
                 listUser·p0.9999: 22.887 ms/op
                 listUser·p1.00:   23.265 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 234899
  mean =      4.087 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2712 
    [ 2.500,  5.000) = 202415 
    [ 5.000,  7.500) = 27898 
    [ 7.500, 10.000) = 1326 
    [10.000, 12.500) = 174 
    [12.500, 15.000) = 150 
    [15.000, 17.500) = 48 
    [17.500, 20.000) = 36 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 65 
    [25.000, 27.500) = 41 

  Percentiles, ms/op:
      p(0.0000) =      0.689 ms/op
     p(50.0000) =      3.891 ms/op
     p(90.0000) =      5.218 ms/op
     p(95.0000) =      5.890 ms/op
     p(99.0000) =      7.266 ms/op
     p(99.9000) =     14.587 ms/op
     p(99.9900) =     25.526 ms/op
     p(99.9990) =     27.055 ms/op
     p(99.9999) =     27.165 ms/op
    p(100.0000) =     27.165 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.519 ± 1.132  ops/ms
ClientGrpc.existUser                       thrpt       3  11.188 ± 6.673  ops/ms
ClientGrpc.getUser                         thrpt       3  10.533 ± 1.385  ops/ms
ClientGrpc.listUser                        thrpt       3   8.003 ± 2.012  ops/ms
ClientGrpc.createUser                       avgt       3   3.013 ± 0.686   ms/op
ClientGrpc.existUser                        avgt       3   2.899 ± 1.028   ms/op
ClientGrpc.getUser                          avgt       3   3.031 ± 0.472   ms/op
ClientGrpc.listUser                         avgt       3   3.999 ± 1.936   ms/op
ClientGrpc.createUser                     sample  318520   3.013 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.651           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.982           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.478           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.695           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.391           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.946           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.236           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          18.973           ms/op
ClientGrpc.existUser                      sample  331496   2.895 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.521           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.879           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.383           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.572           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.309           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.742           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.861           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          28.639           ms/op
ClientGrpc.getUser                        sample  317599   3.022 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.700           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.994           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.490           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.727           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.481           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.171           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.441           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          17.170           ms/op
ClientGrpc.listUser                       sample  234899   4.087 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.689           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.891           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.218           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.890           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.266           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.587           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.526           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.165           ms/op
