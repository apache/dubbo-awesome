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
# Warmup Iteration   1: 4.501 ops/ms
# Warmup Iteration   2: 8.861 ops/ms
# Warmup Iteration   3: 10.104 ops/ms
Iteration   1: 10.352 ops/ms
Iteration   2: 10.423 ops/ms
Iteration   3: 10.187 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.321 ±(99.9%) 2.204 ops/ms [Average]
  (min, avg, max) = (10.187, 10.321, 10.423), stdev = 0.121
  CI (99.9%): [8.117, 12.525] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 7.759 ops/ms
# Warmup Iteration   2: 10.513 ops/ms
# Warmup Iteration   3: 10.872 ops/ms
Iteration   1: 10.771 ops/ms
Iteration   2: 10.624 ops/ms
Iteration   3: 10.561 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.652 ±(99.9%) 1.973 ops/ms [Average]
  (min, avg, max) = (10.561, 10.652, 10.771), stdev = 0.108
  CI (99.9%): [8.679, 12.625] (assumes normal distribution)


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
# Warmup Iteration   1: 7.246 ops/ms
# Warmup Iteration   2: 10.084 ops/ms
# Warmup Iteration   3: 10.229 ops/ms
Iteration   1: 10.208 ops/ms
Iteration   2: 10.461 ops/ms
Iteration   3: 10.388 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.352 ±(99.9%) 2.378 ops/ms [Average]
  (min, avg, max) = (10.208, 10.352, 10.461), stdev = 0.130
  CI (99.9%): [7.974, 12.731] (assumes normal distribution)


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
# Warmup Iteration   1: 5.500 ops/ms
# Warmup Iteration   2: 7.536 ops/ms
# Warmup Iteration   3: 7.837 ops/ms
Iteration   1: 7.971 ops/ms
Iteration   2: 7.956 ops/ms
Iteration   3: 7.997 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.975 ±(99.9%) 0.378 ops/ms [Average]
  (min, avg, max) = (7.956, 7.975, 7.997), stdev = 0.021
  CI (99.9%): [7.596, 8.353] (assumes normal distribution)


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
# Warmup Iteration   1: 4.131 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.144 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.092 ±(99.9%) 0.007 ms/op
Iteration   1: 3.104 ±(99.9%) 0.003 ms/op
Iteration   2: 3.126 ±(99.9%) 0.002 ms/op
Iteration   3: 3.115 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.115 ±(99.9%) 0.206 ms/op [Average]
  (min, avg, max) = (3.104, 3.115, 3.126), stdev = 0.011
  CI (99.9%): [2.909, 3.321] (assumes normal distribution)


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
# Warmup Iteration   1: 3.750 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.018 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.049 ±(99.9%) 0.003 ms/op
Iteration   1: 2.979 ±(99.9%) 0.003 ms/op
Iteration   2: 3.013 ±(99.9%) 0.003 ms/op
Iteration   3: 3.013 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.002 ±(99.9%) 0.361 ms/op [Average]
  (min, avg, max) = (2.979, 3.002, 3.013), stdev = 0.020
  CI (99.9%): [2.641, 3.363] (assumes normal distribution)


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
# Warmup Iteration   1: 3.848 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.240 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.156 ±(99.9%) 0.002 ms/op
Iteration   1: 3.084 ±(99.9%) 0.003 ms/op
Iteration   2: 3.150 ±(99.9%) 0.002 ms/op
Iteration   3: 3.169 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.135 ±(99.9%) 0.813 ms/op [Average]
  (min, avg, max) = (3.084, 3.135, 3.169), stdev = 0.045
  CI (99.9%): [2.322, 3.947] (assumes normal distribution)


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
# Warmup Iteration   1: 4.899 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 4.146 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.040 ±(99.9%) 0.020 ms/op
Iteration   1: 4.228 ±(99.9%) 0.015 ms/op
Iteration   2: 3.906 ±(99.9%) 0.013 ms/op
Iteration   3: 3.967 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.034 ±(99.9%) 3.119 ms/op [Average]
  (min, avg, max) = (3.906, 4.034, 4.228), stdev = 0.171
  CI (99.9%): [0.915, 7.152] (assumes normal distribution)


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
# Warmup Iteration   1: 4.014 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.190 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.093 ±(99.9%) 0.008 ms/op
Iteration   1: 3.079 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.748 ms/op
                 createUser·p0.50:   3.064 ms/op
                 createUser·p0.90:   3.662 ms/op
                 createUser·p0.95:   3.871 ms/op
                 createUser·p0.99:   4.375 ms/op
                 createUser·p0.999:  6.751 ms/op
                 createUser·p0.9999: 12.953 ms/op
                 createUser·p1.00:   13.353 ms/op

Iteration   2: 3.129 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.748 ms/op
                 createUser·p0.50:   3.113 ms/op
                 createUser·p0.90:   3.875 ms/op
                 createUser·p0.95:   4.051 ms/op
                 createUser·p0.99:   4.407 ms/op
                 createUser·p0.999:  7.002 ms/op
                 createUser·p0.9999: 19.490 ms/op
                 createUser·p1.00:   19.956 ms/op

Iteration   3: 3.094 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.648 ms/op
                 createUser·p0.50:   3.068 ms/op
                 createUser·p0.90:   3.584 ms/op
                 createUser·p0.95:   3.789 ms/op
                 createUser·p0.99:   4.334 ms/op
                 createUser·p0.999:  6.430 ms/op
                 createUser·p0.9999: 16.067 ms/op
                 createUser·p1.00:   16.499 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 309631
  mean =      3.101 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 971 
    [ 1.250,  2.500) = 23050 
    [ 2.500,  3.750) = 257451 
    [ 3.750,  5.000) = 27044 
    [ 5.000,  6.250) = 696 
    [ 6.250,  7.500) = 179 
    [ 7.500,  8.750) = 47 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 23 
    [11.250, 12.500) = 39 
    [12.500, 13.750) = 34 
    [13.750, 15.000) = 40 
    [15.000, 16.250) = 19 
    [16.250, 17.500) = 5 
    [17.500, 18.750) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.648 ms/op
     p(50.0000) =      3.076 ms/op
     p(90.0000) =      3.715 ms/op
     p(95.0000) =      3.940 ms/op
     p(99.0000) =      4.375 ms/op
     p(99.9000) =      6.758 ms/op
     p(99.9900) =     18.550 ms/op
     p(99.9990) =     19.851 ms/op
     p(99.9999) =     19.956 ms/op
    p(100.0000) =     19.956 ms/op


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
# Warmup Iteration   1: 3.826 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.039 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.974 ±(99.9%) 0.007 ms/op
Iteration   1: 3.017 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.728 ms/op
                 existUser·p0.50:   2.990 ms/op
                 existUser·p0.90:   3.723 ms/op
                 existUser·p0.95:   3.932 ms/op
                 existUser·p0.99:   4.440 ms/op
                 existUser·p0.999:  6.354 ms/op
                 existUser·p0.9999: 11.717 ms/op
                 existUser·p1.00:   12.091 ms/op

Iteration   2: 2.975 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.678 ms/op
                 existUser·p0.50:   2.986 ms/op
                 existUser·p0.90:   3.695 ms/op
                 existUser·p0.95:   3.867 ms/op
                 existUser·p0.99:   4.219 ms/op
                 existUser·p0.999:  5.878 ms/op
                 existUser·p0.9999: 16.011 ms/op
                 existUser·p1.00:   16.269 ms/op

Iteration   3: 3.032 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.733 ms/op
                 existUser·p0.50:   3.006 ms/op
                 existUser·p0.90:   3.654 ms/op
                 existUser·p0.95:   3.850 ms/op
                 existUser·p0.99:   4.639 ms/op
                 existUser·p0.999:  9.732 ms/op
                 existUser·p0.9999: 29.095 ms/op
                 existUser·p1.00:   29.721 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 319113
  mean =      3.008 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 42522 
    [ 2.500,  5.000) = 275145 
    [ 5.000,  7.500) = 1018 
    [ 7.500, 10.000) = 202 
    [10.000, 12.500) = 98 
    [12.500, 15.000) = 65 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.678 ms/op
     p(50.0000) =      2.994 ms/op
     p(90.0000) =      3.690 ms/op
     p(95.0000) =      3.883 ms/op
     p(99.0000) =      4.375 ms/op
     p(99.9000) =      8.272 ms/op
     p(99.9900) =     28.252 ms/op
     p(99.9990) =     29.583 ms/op
     p(99.9999) =     29.721 ms/op
    p(100.0000) =     29.721 ms/op


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
# Warmup Iteration   1: 3.986 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.208 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.124 ±(99.9%) 0.006 ms/op
Iteration   1: 3.056 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.705 ms/op
                 getUser·p0.50:   3.064 ms/op
                 getUser·p0.90:   3.625 ms/op
                 getUser·p0.95:   3.805 ms/op
                 getUser·p0.99:   4.432 ms/op
                 getUser·p0.999:  7.242 ms/op
                 getUser·p0.9999: 12.289 ms/op
                 getUser·p1.00:   12.567 ms/op

Iteration   2: 3.151 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.697 ms/op
                 getUser·p0.50:   3.125 ms/op
                 getUser·p0.90:   3.793 ms/op
                 getUser·p0.95:   3.994 ms/op
                 getUser·p0.99:   4.473 ms/op
                 getUser·p0.999:  8.602 ms/op
                 getUser·p0.9999: 14.593 ms/op
                 getUser·p1.00:   15.483 ms/op

Iteration   3: 3.164 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.883 ms/op
                 getUser·p0.50:   3.121 ms/op
                 getUser·p0.90:   3.846 ms/op
                 getUser·p0.95:   4.092 ms/op
                 getUser·p0.99:   4.637 ms/op
                 getUser·p0.999:  7.847 ms/op
                 getUser·p0.9999: 25.228 ms/op
                 getUser·p1.00:   25.494 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 307182
  mean =      3.123 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24837 
    [ 2.500,  5.000) = 280682 
    [ 5.000,  7.500) = 1245 
    [ 7.500, 10.000) = 258 
    [10.000, 12.500) = 30 
    [12.500, 15.000) = 90 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 19 

  Percentiles, ms/op:
      p(0.0000) =      0.697 ms/op
     p(50.0000) =      3.101 ms/op
     p(90.0000) =      3.756 ms/op
     p(95.0000) =      3.981 ms/op
     p(99.0000) =      4.522 ms/op
     p(99.9000) =      8.028 ms/op
     p(99.9900) =     24.618 ms/op
     p(99.9990) =     25.426 ms/op
     p(99.9999) =     25.494 ms/op
    p(100.0000) =     25.494 ms/op


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
# Warmup Iteration   1: 4.053 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 4.329 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.967 ±(99.9%) 0.012 ms/op
Iteration   1: 4.178 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.409 ms/op
                 listUser·p0.50:   3.953 ms/op
                 listUser·p0.90:   5.456 ms/op
                 listUser·p0.95:   5.997 ms/op
                 listUser·p0.99:   7.520 ms/op
                 listUser·p0.999:  16.741 ms/op
                 listUser·p0.9999: 19.607 ms/op
                 listUser·p1.00:   21.496 ms/op

Iteration   2: 4.126 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.918 ms/op
                 listUser·p0.50:   3.912 ms/op
                 listUser·p0.90:   5.366 ms/op
                 listUser·p0.95:   5.882 ms/op
                 listUser·p0.99:   7.315 ms/op
                 listUser·p0.999:  14.823 ms/op
                 listUser·p0.9999: 23.780 ms/op
                 listUser·p1.00:   24.216 ms/op

Iteration   3: 4.116 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   0.843 ms/op
                 listUser·p0.50:   3.903 ms/op
                 listUser·p0.90:   5.353 ms/op
                 listUser·p0.95:   5.939 ms/op
                 listUser·p0.99:   7.430 ms/op
                 listUser·p0.999:  17.394 ms/op
                 listUser·p0.9999: 22.068 ms/op
                 listUser·p1.00:   23.233 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 231901
  mean =      4.140 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4159 
    [ 2.500,  5.000) = 189863 
    [ 5.000,  7.500) = 35732 
    [ 7.500, 10.000) = 1592 
    [10.000, 12.500) = 137 
    [12.500, 15.000) = 106 
    [15.000, 17.500) = 136 
    [17.500, 20.000) = 110 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 38 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.843 ms/op
     p(50.0000) =      3.920 ms/op
     p(90.0000) =      5.390 ms/op
     p(95.0000) =      5.939 ms/op
     p(99.0000) =      7.422 ms/op
     p(99.9000) =     16.780 ms/op
     p(99.9900) =     23.233 ms/op
     p(99.9990) =     24.119 ms/op
     p(99.9999) =     24.216 ms/op
    p(100.0000) =     24.216 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.321 ± 2.204  ops/ms
ClientGrpc.existUser                       thrpt       3  10.652 ± 1.973  ops/ms
ClientGrpc.getUser                         thrpt       3  10.352 ± 2.378  ops/ms
ClientGrpc.listUser                        thrpt       3   7.975 ± 0.378  ops/ms
ClientGrpc.createUser                       avgt       3   3.115 ± 0.206   ms/op
ClientGrpc.existUser                        avgt       3   3.002 ± 0.361   ms/op
ClientGrpc.getUser                          avgt       3   3.135 ± 0.813   ms/op
ClientGrpc.listUser                         avgt       3   4.034 ± 3.119   ms/op
ClientGrpc.createUser                     sample  309631   3.101 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.648           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.076           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.715           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.940           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.375           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           6.758           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.550           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          19.956           ms/op
ClientGrpc.existUser                      sample  319113   3.008 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.678           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.994           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.690           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.883           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.375           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.272           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          28.252           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          29.721           ms/op
ClientGrpc.getUser                        sample  307182   3.123 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.697           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.101           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.756           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.981           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.522           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.028           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          24.618           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          25.494           ms/op
ClientGrpc.listUser                       sample  231901   4.140 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.843           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.920           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.390           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.939           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.422           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.780           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.233           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.216           ms/op
