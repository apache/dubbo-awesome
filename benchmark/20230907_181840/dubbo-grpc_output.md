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
# Warmup Iteration   1: 4.165 ops/ms
# Warmup Iteration   2: 8.786 ops/ms
# Warmup Iteration   3: 9.800 ops/ms
Iteration   1: 10.116 ops/ms
Iteration   2: 10.308 ops/ms
Iteration   3: 10.205 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.210 ±(99.9%) 1.751 ops/ms [Average]
  (min, avg, max) = (10.116, 10.210, 10.308), stdev = 0.096
  CI (99.9%): [8.459, 11.961] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 7.048 ops/ms
# Warmup Iteration   2: 9.941 ops/ms
# Warmup Iteration   3: 10.949 ops/ms
Iteration   1: 10.891 ops/ms
Iteration   2: 11.130 ops/ms
Iteration   3: 10.739 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.920 ±(99.9%) 3.598 ops/ms [Average]
  (min, avg, max) = (10.739, 10.920, 11.130), stdev = 0.197
  CI (99.9%): [7.322, 14.518] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 7.053 ops/ms
# Warmup Iteration   2: 10.118 ops/ms
# Warmup Iteration   3: 10.379 ops/ms
Iteration   1: 10.351 ops/ms
Iteration   2: 10.237 ops/ms
Iteration   3: 10.323 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.304 ±(99.9%) 1.087 ops/ms [Average]
  (min, avg, max) = (10.237, 10.304, 10.351), stdev = 0.060
  CI (99.9%): [9.217, 11.391] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 5.207 ops/ms
# Warmup Iteration   2: 7.371 ops/ms
# Warmup Iteration   3: 7.720 ops/ms
Iteration   1: 7.555 ops/ms
Iteration   2: 7.515 ops/ms
Iteration   3: 7.773 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.614 ±(99.9%) 2.528 ops/ms [Average]
  (min, avg, max) = (7.515, 7.614, 7.773), stdev = 0.139
  CI (99.9%): [5.086, 10.142] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.423 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.225 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.094 ±(99.9%) 0.003 ms/op
Iteration   1: 3.090 ±(99.9%) 0.002 ms/op
Iteration   2: 3.029 ±(99.9%) 0.002 ms/op
Iteration   3: 3.110 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.076 ±(99.9%) 0.774 ms/op [Average]
  (min, avg, max) = (3.029, 3.076, 3.110), stdev = 0.042
  CI (99.9%): [2.302, 3.850] (assumes normal distribution)


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
# Warmup Iteration   1: 4.264 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.006 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.033 ±(99.9%) 0.002 ms/op
Iteration   1: 2.991 ±(99.9%) 0.004 ms/op
Iteration   2: 2.925 ±(99.9%) 0.002 ms/op
Iteration   3: 3.031 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.983 ±(99.9%) 0.980 ms/op [Average]
  (min, avg, max) = (2.925, 2.983, 3.031), stdev = 0.054
  CI (99.9%): [2.003, 3.962] (assumes normal distribution)


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
# Warmup Iteration   1: 4.215 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.171 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.114 ±(99.9%) 0.002 ms/op
Iteration   1: 3.120 ±(99.9%) 0.003 ms/op
Iteration   2: 3.039 ±(99.9%) 0.003 ms/op
Iteration   3: 3.056 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.072 ±(99.9%) 0.772 ms/op [Average]
  (min, avg, max) = (3.039, 3.072, 3.120), stdev = 0.042
  CI (99.9%): [2.300, 3.843] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.643 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 4.316 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 4.100 ±(99.9%) 0.018 ms/op
Iteration   1: 4.087 ±(99.9%) 0.011 ms/op
Iteration   2: 4.067 ±(99.9%) 0.013 ms/op
Iteration   3: 4.184 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.113 ±(99.9%) 1.135 ms/op [Average]
  (min, avg, max) = (4.067, 4.113, 4.184), stdev = 0.062
  CI (99.9%): [2.978, 5.248] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.291 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.253 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.087 ±(99.9%) 0.007 ms/op
Iteration   1: 3.055 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.813 ms/op
                 createUser·p0.50:   3.019 ms/op
                 createUser·p0.90:   3.658 ms/op
                 createUser·p0.95:   3.895 ms/op
                 createUser·p0.99:   4.727 ms/op
                 createUser·p0.999:  9.339 ms/op
                 createUser·p0.9999: 13.985 ms/op
                 createUser·p1.00:   15.909 ms/op

Iteration   2: 3.120 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.787 ms/op
                 createUser·p0.50:   3.064 ms/op
                 createUser·p0.90:   3.633 ms/op
                 createUser·p0.95:   3.871 ms/op
                 createUser·p0.99:   4.514 ms/op
                 createUser·p0.999:  10.633 ms/op
                 createUser·p0.9999: 23.134 ms/op
                 createUser·p1.00:   23.626 ms/op

Iteration   3: 3.099 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.740 ms/op
                 createUser·p0.50:   3.043 ms/op
                 createUser·p0.90:   3.617 ms/op
                 createUser·p0.95:   3.822 ms/op
                 createUser·p0.99:   4.596 ms/op
                 createUser·p0.999:  9.306 ms/op
                 createUser·p0.9999: 51.028 ms/op
                 createUser·p1.00:   52.167 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 311027
  mean =      3.091 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 308826 
    [ 5.000, 10.000) = 1900 
    [10.000, 15.000) = 158 
    [15.000, 20.000) = 48 
    [20.000, 25.000) = 63 
    [25.000, 30.000) = 1 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 0 
    [45.000, 50.000) = 13 
    [50.000, 55.000) = 18 

  Percentiles, ms/op:
      p(0.0000) =      0.740 ms/op
     p(50.0000) =      3.043 ms/op
     p(90.0000) =      3.637 ms/op
     p(95.0000) =      3.863 ms/op
     p(99.0000) =      4.612 ms/op
     p(99.9000) =      9.634 ms/op
     p(99.9900) =     47.069 ms/op
     p(99.9990) =     51.839 ms/op
     p(99.9999) =     52.167 ms/op
    p(100.0000) =     52.167 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.403 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.169 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.993 ±(99.9%) 0.006 ms/op
Iteration   1: 3.008 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.846 ms/op
                 existUser·p0.50:   2.957 ms/op
                 existUser·p0.90:   3.486 ms/op
                 existUser·p0.95:   3.744 ms/op
                 existUser·p0.99:   4.997 ms/op
                 existUser·p0.999:  10.285 ms/op
                 existUser·p0.9999: 13.644 ms/op
                 existUser·p1.00:   16.138 ms/op

Iteration   2: 3.022 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.745 ms/op
                 existUser·p0.50:   2.974 ms/op
                 existUser·p0.90:   3.490 ms/op
                 existUser·p0.95:   3.711 ms/op
                 existUser·p0.99:   4.833 ms/op
                 existUser·p0.999:  10.472 ms/op
                 existUser·p0.9999: 14.422 ms/op
                 existUser·p1.00:   14.729 ms/op

Iteration   3: 2.976 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.736 ms/op
                 existUser·p0.50:   2.941 ms/op
                 existUser·p0.90:   3.437 ms/op
                 existUser·p0.95:   3.637 ms/op
                 existUser·p0.99:   4.481 ms/op
                 existUser·p0.999:  8.249 ms/op
                 existUser·p0.9999: 18.547 ms/op
                 existUser·p1.00:   18.678 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 319623
  mean =      3.002 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 854 
    [ 1.250,  2.500) = 23917 
    [ 2.500,  3.750) = 281060 
    [ 3.750,  5.000) = 11135 
    [ 5.000,  6.250) = 1263 
    [ 6.250,  7.500) = 739 
    [ 7.500,  8.750) = 248 
    [ 8.750, 10.000) = 106 
    [10.000, 11.250) = 86 
    [11.250, 12.500) = 53 
    [12.500, 13.750) = 60 
    [13.750, 15.000) = 36 
    [15.000, 16.250) = 21 
    [16.250, 17.500) = 18 
    [17.500, 18.750) = 27 

  Percentiles, ms/op:
      p(0.0000) =      0.736 ms/op
     p(50.0000) =      2.957 ms/op
     p(90.0000) =      3.469 ms/op
     p(95.0000) =      3.695 ms/op
     p(99.0000) =      4.727 ms/op
     p(99.9000) =      9.636 ms/op
     p(99.9900) =     17.007 ms/op
     p(99.9990) =     18.547 ms/op
     p(99.9999) =     18.678 ms/op
    p(100.0000) =     18.678 ms/op


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
# Warmup Iteration   1: 4.412 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.263 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.182 ±(99.9%) 0.007 ms/op
Iteration   1: 3.166 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.662 ms/op
                 getUser·p0.50:   3.097 ms/op
                 getUser·p0.90:   3.748 ms/op
                 getUser·p0.95:   4.002 ms/op
                 getUser·p0.99:   5.874 ms/op
                 getUser·p0.999:  9.585 ms/op
                 getUser·p0.9999: 12.925 ms/op
                 getUser·p1.00:   13.124 ms/op

Iteration   2: 3.150 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.899 ms/op
                 getUser·p0.50:   3.088 ms/op
                 getUser·p0.90:   3.707 ms/op
                 getUser·p0.95:   3.994 ms/op
                 getUser·p0.99:   5.054 ms/op
                 getUser·p0.999:  9.503 ms/op
                 getUser·p0.9999: 14.882 ms/op
                 getUser·p1.00:   15.909 ms/op

Iteration   3: 3.092 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.749 ms/op
                 getUser·p0.50:   3.056 ms/op
                 getUser·p0.90:   3.576 ms/op
                 getUser·p0.95:   3.834 ms/op
                 getUser·p0.99:   4.899 ms/op
                 getUser·p0.999:  8.571 ms/op
                 getUser·p0.9999: 17.138 ms/op
                 getUser·p1.00:   19.792 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 305959
  mean =      3.135 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 497 
    [ 1.250,  2.500) = 13510 
    [ 2.500,  3.750) = 266159 
    [ 3.750,  5.000) = 22157 
    [ 5.000,  6.250) = 1892 
    [ 6.250,  7.500) = 881 
    [ 7.500,  8.750) = 458 
    [ 8.750, 10.000) = 178 
    [10.000, 11.250) = 34 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 44 
    [13.750, 15.000) = 44 
    [15.000, 16.250) = 32 
    [16.250, 17.500) = 37 
    [17.500, 18.750) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.662 ms/op
     p(50.0000) =      3.080 ms/op
     p(90.0000) =      3.682 ms/op
     p(95.0000) =      3.940 ms/op
     p(99.0000) =      5.194 ms/op
     p(99.9000) =      9.404 ms/op
     p(99.9900) =     16.790 ms/op
     p(99.9990) =     18.024 ms/op
     p(99.9999) =     19.792 ms/op
    p(100.0000) =     19.792 ms/op


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
# Warmup Iteration   1: 5.182 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 4.438 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.142 ±(99.9%) 0.012 ms/op
Iteration   1: 4.187 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.401 ms/op
                 listUser·p0.50:   3.990 ms/op
                 listUser·p0.90:   5.251 ms/op
                 listUser·p0.95:   6.119 ms/op
                 listUser·p0.99:   7.739 ms/op
                 listUser·p0.999:  15.458 ms/op
                 listUser·p0.9999: 20.447 ms/op
                 listUser·p1.00:   20.709 ms/op

Iteration   2: 4.165 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.114 ms/op
                 listUser·p0.50:   3.973 ms/op
                 listUser·p0.90:   5.448 ms/op
                 listUser·p0.95:   6.160 ms/op
                 listUser·p0.99:   7.455 ms/op
                 listUser·p0.999:  16.672 ms/op
                 listUser·p0.9999: 32.214 ms/op
                 listUser·p1.00:   33.358 ms/op

Iteration   3: 4.176 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.077 ms/op
                 listUser·p0.50:   3.994 ms/op
                 listUser·p0.90:   5.177 ms/op
                 listUser·p0.95:   6.062 ms/op
                 listUser·p0.99:   7.692 ms/op
                 listUser·p0.999:  17.359 ms/op
                 listUser·p0.9999: 28.422 ms/op
                 listUser·p1.00:   31.162 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 229838
  mean =      4.176 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2446 
    [ 2.500,  5.000) = 198296 
    [ 5.000,  7.500) = 26531 
    [ 7.500, 10.000) = 2022 
    [10.000, 12.500) = 160 
    [12.500, 15.000) = 67 
    [15.000, 17.500) = 149 
    [17.500, 20.000) = 70 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 13 
    [27.500, 30.000) = 16 
    [30.000, 32.500) = 28 
    [32.500, 35.000) = 7 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.077 ms/op
     p(50.0000) =      3.985 ms/op
     p(90.0000) =      5.284 ms/op
     p(95.0000) =      6.119 ms/op
     p(99.0000) =      7.627 ms/op
     p(99.9000) =     16.548 ms/op
     p(99.9900) =     31.359 ms/op
     p(99.9990) =     33.230 ms/op
     p(99.9999) =     33.358 ms/op
    p(100.0000) =     33.358 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.210 ± 1.751  ops/ms
ClientGrpc.existUser                       thrpt       3  10.920 ± 3.598  ops/ms
ClientGrpc.getUser                         thrpt       3  10.304 ± 1.087  ops/ms
ClientGrpc.listUser                        thrpt       3   7.614 ± 2.528  ops/ms
ClientGrpc.createUser                       avgt       3   3.076 ± 0.774   ms/op
ClientGrpc.existUser                        avgt       3   2.983 ± 0.980   ms/op
ClientGrpc.getUser                          avgt       3   3.072 ± 0.772   ms/op
ClientGrpc.listUser                         avgt       3   4.113 ± 1.135   ms/op
ClientGrpc.createUser                     sample  311027   3.091 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.740           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.043           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.637           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.863           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.612           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.634           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          47.069           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          52.167           ms/op
ClientGrpc.existUser                      sample  319623   3.002 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.736           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.957           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.469           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.695           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.727           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.636           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.007           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.678           ms/op
ClientGrpc.getUser                        sample  305959   3.135 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.662           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.080           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.682           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.940           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.194           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.404           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.790           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.792           ms/op
ClientGrpc.listUser                       sample  229838   4.176 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.077           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.985           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.284           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.119           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.627           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.548           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          31.359           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          33.358           ms/op
