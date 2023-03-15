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
# Warmup Iteration   1: 4.494 ops/ms
# Warmup Iteration   2: 9.041 ops/ms
# Warmup Iteration   3: 10.277 ops/ms
Iteration   1: 10.379 ops/ms
Iteration   2: 10.610 ops/ms
Iteration   3: 10.509 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.499 ±(99.9%) 2.110 ops/ms [Average]
  (min, avg, max) = (10.379, 10.499, 10.610), stdev = 0.116
  CI (99.9%): [8.389, 12.610] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 7.951 ops/ms
# Warmup Iteration   2: 10.786 ops/ms
# Warmup Iteration   3: 11.329 ops/ms
Iteration   1: 11.147 ops/ms
Iteration   2: 11.268 ops/ms
Iteration   3: 11.105 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.173 ±(99.9%) 1.547 ops/ms [Average]
  (min, avg, max) = (11.105, 11.173, 11.268), stdev = 0.085
  CI (99.9%): [9.626, 12.721] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 7.226 ops/ms
# Warmup Iteration   2: 10.300 ops/ms
# Warmup Iteration   3: 10.645 ops/ms
Iteration   1: 10.670 ops/ms
Iteration   2: 10.794 ops/ms
Iteration   3: 10.793 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.752 ±(99.9%) 1.305 ops/ms [Average]
  (min, avg, max) = (10.670, 10.752, 10.794), stdev = 0.072
  CI (99.9%): [9.448, 12.057] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 5.833 ops/ms
# Warmup Iteration   2: 8.240 ops/ms
# Warmup Iteration   3: 8.411 ops/ms
Iteration   1: 8.573 ops/ms
Iteration   2: 8.528 ops/ms
Iteration   3: 8.558 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.553 ±(99.9%) 0.420 ops/ms [Average]
  (min, avg, max) = (8.528, 8.553, 8.573), stdev = 0.023
  CI (99.9%): [8.133, 8.972] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.894 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.053 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.972 ±(99.9%) 0.003 ms/op
Iteration   1: 2.978 ±(99.9%) 0.002 ms/op
Iteration   2: 2.977 ±(99.9%) 0.002 ms/op
Iteration   3: 2.969 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.975 ±(99.9%) 0.086 ms/op [Average]
  (min, avg, max) = (2.969, 2.975, 2.978), stdev = 0.005
  CI (99.9%): [2.888, 3.061] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 3.804 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.901 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.720 ±(99.9%) 0.003 ms/op
Iteration   1: 2.829 ±(99.9%) 0.004 ms/op
Iteration   2: 2.896 ±(99.9%) 0.003 ms/op
Iteration   3: 2.825 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.850 ±(99.9%) 0.726 ms/op [Average]
  (min, avg, max) = (2.825, 2.850, 2.896), stdev = 0.040
  CI (99.9%): [2.124, 3.576] (assumes normal distribution)


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
# Warmup Iteration   1: 3.998 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.092 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.979 ±(99.9%) 0.003 ms/op
Iteration   1: 2.946 ±(99.9%) 0.003 ms/op
Iteration   2: 2.986 ±(99.9%) 0.004 ms/op
Iteration   3: 2.940 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.958 ±(99.9%) 0.460 ms/op [Average]
  (min, avg, max) = (2.940, 2.958, 2.986), stdev = 0.025
  CI (99.9%): [2.497, 3.418] (assumes normal distribution)


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
# Warmup Iteration   1: 4.713 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.964 ±(99.9%) 0.038 ms/op
# Warmup Iteration   3: 3.759 ±(99.9%) 0.015 ms/op
Iteration   1: 3.700 ±(99.9%) 0.005 ms/op
Iteration   2: 3.650 ±(99.9%) 0.011 ms/op
Iteration   3: 3.728 ±(99.9%) 0.068 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.693 ±(99.9%) 0.714 ms/op [Average]
  (min, avg, max) = (3.650, 3.693, 3.728), stdev = 0.039
  CI (99.9%): [2.979, 4.406] (assumes normal distribution)


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
# Warmup Iteration   1: 4.088 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.072 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.971 ±(99.9%) 0.007 ms/op
Iteration   1: 2.956 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.630 ms/op
                 createUser·p0.50:   2.957 ms/op
                 createUser·p0.90:   3.396 ms/op
                 createUser·p0.95:   3.629 ms/op
                 createUser·p0.99:   4.276 ms/op
                 createUser·p0.999:  9.070 ms/op
                 createUser·p0.9999: 16.914 ms/op
                 createUser·p1.00:   18.612 ms/op

Iteration   2: 2.972 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.636 ms/op
                 createUser·p0.50:   2.974 ms/op
                 createUser·p0.90:   3.453 ms/op
                 createUser·p0.95:   3.703 ms/op
                 createUser·p0.99:   4.334 ms/op
                 createUser·p0.999:  6.451 ms/op
                 createUser·p0.9999: 33.005 ms/op
                 createUser·p1.00:   33.292 ms/op

Iteration   3: 2.997 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.508 ms/op
                 createUser·p0.50:   2.970 ms/op
                 createUser·p0.90:   3.461 ms/op
                 createUser·p0.95:   3.768 ms/op
                 createUser·p0.99:   4.432 ms/op
                 createUser·p0.999:  8.867 ms/op
                 createUser·p0.9999: 20.939 ms/op
                 createUser·p1.00:   21.463 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 322749
  mean =      2.975 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26916 
    [ 2.500,  5.000) = 294670 
    [ 5.000,  7.500) = 762 
    [ 7.500, 10.000) = 174 
    [10.000, 12.500) = 25 
    [12.500, 15.000) = 24 
    [15.000, 17.500) = 46 
    [17.500, 20.000) = 70 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 32 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.508 ms/op
     p(50.0000) =      2.970 ms/op
     p(90.0000) =      3.432 ms/op
     p(95.0000) =      3.699 ms/op
     p(99.0000) =      4.350 ms/op
     p(99.9000) =      8.327 ms/op
     p(99.9900) =     29.564 ms/op
     p(99.9990) =     33.252 ms/op
     p(99.9999) =     33.292 ms/op
    p(100.0000) =     33.292 ms/op


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
# Warmup Iteration   1: 3.915 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 2.980 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.902 ±(99.9%) 0.005 ms/op
Iteration   1: 2.861 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.521 ms/op
                 existUser·p0.50:   2.847 ms/op
                 existUser·p0.90:   3.285 ms/op
                 existUser·p0.95:   3.518 ms/op
                 existUser·p0.99:   4.227 ms/op
                 existUser·p0.999:  5.923 ms/op
                 existUser·p0.9999: 13.560 ms/op
                 existUser·p1.00:   13.812 ms/op

Iteration   2: 2.844 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.517 ms/op
                 existUser·p0.50:   2.851 ms/op
                 existUser·p0.90:   3.367 ms/op
                 existUser·p0.95:   3.559 ms/op
                 existUser·p0.99:   4.391 ms/op
                 existUser·p0.999:  6.857 ms/op
                 existUser·p0.9999: 12.813 ms/op
                 existUser·p1.00:   13.582 ms/op

Iteration   3: 2.947 ±(99.9%) 0.004 ms/op
                 existUser·p0.00:   0.823 ms/op
                 existUser·p0.50:   2.920 ms/op
                 existUser·p0.90:   3.396 ms/op
                 existUser·p0.95:   3.535 ms/op
                 existUser·p0.99:   3.985 ms/op
                 existUser·p0.999:  6.466 ms/op
                 existUser·p0.9999: 13.999 ms/op
                 existUser·p1.00:   14.369 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 332849
  mean =      2.884 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2717 
    [ 1.250,  2.500) = 41496 
    [ 2.500,  3.750) = 280307 
    [ 3.750,  5.000) = 7510 
    [ 5.000,  6.250) = 390 
    [ 6.250,  7.500) = 232 
    [ 7.500,  8.750) = 19 
    [ 8.750, 10.000) = 18 
    [10.000, 11.250) = 44 
    [11.250, 12.500) = 30 
    [12.500, 13.750) = 66 
    [13.750, 15.000) = 20 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.517 ms/op
     p(50.0000) =      2.871 ms/op
     p(90.0000) =      3.363 ms/op
     p(95.0000) =      3.535 ms/op
     p(99.0000) =      4.219 ms/op
     p(99.9000) =      6.481 ms/op
     p(99.9900) =     13.566 ms/op
     p(99.9990) =     14.320 ms/op
     p(99.9999) =     14.369 ms/op
    p(100.0000) =     14.369 ms/op


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
# Warmup Iteration   1: 3.916 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.062 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.999 ±(99.9%) 0.006 ms/op
Iteration   1: 3.000 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.379 ms/op
                 getUser·p0.50:   2.986 ms/op
                 getUser·p0.90:   3.580 ms/op
                 getUser·p0.95:   3.805 ms/op
                 getUser·p0.99:   4.563 ms/op
                 getUser·p0.999:  8.128 ms/op
                 getUser·p0.9999: 16.264 ms/op
                 getUser·p1.00:   17.170 ms/op

Iteration   2: 3.021 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.860 ms/op
                 getUser·p0.50:   2.986 ms/op
                 getUser·p0.90:   3.576 ms/op
                 getUser·p0.95:   3.760 ms/op
                 getUser·p0.99:   4.219 ms/op
                 getUser·p0.999:  8.020 ms/op
                 getUser·p0.9999: 22.460 ms/op
                 getUser·p1.00:   22.970 ms/op

Iteration   3: 3.009 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.387 ms/op
                 getUser·p0.50:   2.990 ms/op
                 getUser·p0.90:   3.490 ms/op
                 getUser·p0.95:   3.633 ms/op
                 getUser·p0.99:   4.235 ms/op
                 getUser·p0.999:  6.776 ms/op
                 getUser·p0.9999: 24.936 ms/op
                 getUser·p1.00:   25.297 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 318745
  mean =      3.010 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25652 
    [ 2.500,  5.000) = 291574 
    [ 5.000,  7.500) = 1159 
    [ 7.500, 10.000) = 135 
    [10.000, 12.500) = 39 
    [12.500, 15.000) = 82 
    [15.000, 17.500) = 40 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 33 
    [25.000, 27.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.379 ms/op
     p(50.0000) =      2.986 ms/op
     p(90.0000) =      3.543 ms/op
     p(95.0000) =      3.736 ms/op
     p(99.0000) =      4.399 ms/op
     p(99.9000) =      7.946 ms/op
     p(99.9900) =     24.449 ms/op
     p(99.9990) =     25.192 ms/op
     p(99.9999) =     25.297 ms/op
    p(100.0000) =     25.297 ms/op


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
# Warmup Iteration   1: 5.360 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.870 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.773 ±(99.9%) 0.011 ms/op
Iteration   1: 3.810 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.301 ms/op
                 listUser·p0.50:   3.690 ms/op
                 listUser·p0.90:   4.465 ms/op
                 listUser·p0.95:   5.407 ms/op
                 listUser·p0.99:   6.496 ms/op
                 listUser·p0.999:  13.242 ms/op
                 listUser·p0.9999: 19.602 ms/op
                 listUser·p1.00:   20.054 ms/op

Iteration   2: 3.780 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.034 ms/op
                 listUser·p0.50:   3.654 ms/op
                 listUser·p0.90:   4.448 ms/op
                 listUser·p0.95:   5.169 ms/op
                 listUser·p0.99:   6.463 ms/op
                 listUser·p0.999:  13.605 ms/op
                 listUser·p0.9999: 23.298 ms/op
                 listUser·p1.00:   23.593 ms/op

Iteration   3: 3.826 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.155 ms/op
                 listUser·p0.50:   3.690 ms/op
                 listUser·p0.90:   4.620 ms/op
                 listUser·p0.95:   5.480 ms/op
                 listUser·p0.99:   6.529 ms/op
                 listUser·p0.999:  13.628 ms/op
                 listUser·p0.9999: 30.081 ms/op
                 listUser·p1.00:   30.605 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 252157
  mean =      3.805 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4041 
    [ 2.500,  5.000) = 231515 
    [ 5.000,  7.500) = 15759 
    [ 7.500, 10.000) = 394 
    [10.000, 12.500) = 100 
    [12.500, 15.000) = 181 
    [15.000, 17.500) = 38 
    [17.500, 20.000) = 59 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 11 
    [27.500, 30.000) = 12 
    [30.000, 32.500) = 9 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.301 ms/op
     p(50.0000) =      3.678 ms/op
     p(90.0000) =      4.514 ms/op
     p(95.0000) =      5.374 ms/op
     p(99.0000) =      6.504 ms/op
     p(99.9000) =     13.514 ms/op
     p(99.9900) =     26.495 ms/op
     p(99.9990) =     30.437 ms/op
     p(99.9999) =     30.605 ms/op
    p(100.0000) =     30.605 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.499 ± 2.110  ops/ms
ClientGrpc.existUser                       thrpt       3  11.173 ± 1.547  ops/ms
ClientGrpc.getUser                         thrpt       3  10.752 ± 1.305  ops/ms
ClientGrpc.listUser                        thrpt       3   8.553 ± 0.420  ops/ms
ClientGrpc.createUser                       avgt       3   2.975 ± 0.086   ms/op
ClientGrpc.existUser                        avgt       3   2.850 ± 0.726   ms/op
ClientGrpc.getUser                          avgt       3   2.958 ± 0.460   ms/op
ClientGrpc.listUser                         avgt       3   3.693 ± 0.714   ms/op
ClientGrpc.createUser                     sample  322749   2.975 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.508           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.970           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.432           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.699           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.350           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.327           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          29.564           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          33.292           ms/op
ClientGrpc.existUser                      sample  332849   2.884 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.517           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.871           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.363           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.535           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.219           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.481           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          13.566           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          14.369           ms/op
ClientGrpc.getUser                        sample  318745   3.010 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.379           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.986           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.543           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.736           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.399           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.946           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          24.449           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          25.297           ms/op
ClientGrpc.listUser                       sample  252157   3.805 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.301           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.678           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.514           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.374           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.504           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.514           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          26.495           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          30.605           ms/op
