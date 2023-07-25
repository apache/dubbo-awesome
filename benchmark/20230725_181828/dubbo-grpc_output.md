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
# Warmup Iteration   1: 4.830 ops/ms
# Warmup Iteration   2: 9.326 ops/ms
# Warmup Iteration   3: 10.284 ops/ms
Iteration   1: 10.754 ops/ms
Iteration   2: 10.841 ops/ms
Iteration   3: 10.823 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.806 ±(99.9%) 0.833 ops/ms [Average]
  (min, avg, max) = (10.754, 10.806, 10.841), stdev = 0.046
  CI (99.9%): [9.973, 11.639] (assumes normal distribution)


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
# Warmup Iteration   1: 8.090 ops/ms
# Warmup Iteration   2: 10.967 ops/ms
# Warmup Iteration   3: 11.341 ops/ms
Iteration   1: 11.181 ops/ms
Iteration   2: 11.262 ops/ms
Iteration   3: 11.092 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.178 ±(99.9%) 1.548 ops/ms [Average]
  (min, avg, max) = (11.092, 11.178, 11.262), stdev = 0.085
  CI (99.9%): [9.631, 12.726] (assumes normal distribution)


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
# Warmup Iteration   1: 7.348 ops/ms
# Warmup Iteration   2: 10.498 ops/ms
# Warmup Iteration   3: 10.667 ops/ms
Iteration   1: 10.912 ops/ms
Iteration   2: 10.997 ops/ms
Iteration   3: 10.810 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.906 ±(99.9%) 1.711 ops/ms [Average]
  (min, avg, max) = (10.810, 10.906, 10.997), stdev = 0.094
  CI (99.9%): [9.196, 12.617] (assumes normal distribution)


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
# Warmup Iteration   1: 5.676 ops/ms
# Warmup Iteration   2: 8.063 ops/ms
# Warmup Iteration   3: 8.419 ops/ms
Iteration   1: 8.284 ops/ms
Iteration   2: 8.288 ops/ms
Iteration   3: 8.147 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.240 ±(99.9%) 1.470 ops/ms [Average]
  (min, avg, max) = (8.147, 8.240, 8.288), stdev = 0.081
  CI (99.9%): [6.769, 9.710] (assumes normal distribution)


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
# Warmup Iteration   1: 3.822 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.102 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.037 ±(99.9%) 0.002 ms/op
Iteration   1: 3.041 ±(99.9%) 0.002 ms/op
Iteration   2: 3.013 ±(99.9%) 0.002 ms/op
Iteration   3: 2.963 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.006 ±(99.9%) 0.716 ms/op [Average]
  (min, avg, max) = (2.963, 3.006, 3.041), stdev = 0.039
  CI (99.9%): [2.290, 3.722] (assumes normal distribution)


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
# Warmup Iteration   1: 3.792 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.895 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.860 ±(99.9%) 0.003 ms/op
Iteration   1: 2.766 ±(99.9%) 0.004 ms/op
Iteration   2: 2.893 ±(99.9%) 0.002 ms/op
Iteration   3: 2.847 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.835 ±(99.9%) 1.167 ms/op [Average]
  (min, avg, max) = (2.766, 2.835, 2.893), stdev = 0.064
  CI (99.9%): [1.668, 4.002] (assumes normal distribution)


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
# Warmup Iteration   1: 3.772 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 3.071 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.001 ±(99.9%) 0.003 ms/op
Iteration   1: 2.957 ±(99.9%) 0.003 ms/op
Iteration   2: 2.976 ±(99.9%) 0.003 ms/op
Iteration   3: 2.914 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.949 ±(99.9%) 0.584 ms/op [Average]
  (min, avg, max) = (2.914, 2.949, 2.976), stdev = 0.032
  CI (99.9%): [2.365, 3.533] (assumes normal distribution)


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
# Warmup Iteration   1: 5.061 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.953 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 3.872 ±(99.9%) 0.011 ms/op
Iteration   1: 3.932 ±(99.9%) 0.008 ms/op
Iteration   2: 3.830 ±(99.9%) 0.022 ms/op
Iteration   3: 3.900 ±(99.9%) 0.037 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.887 ±(99.9%) 0.946 ms/op [Average]
  (min, avg, max) = (3.830, 3.887, 3.932), stdev = 0.052
  CI (99.9%): [2.941, 4.833] (assumes normal distribution)


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
# Warmup Iteration   1: 3.605 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.139 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.987 ±(99.9%) 0.008 ms/op
Iteration   1: 2.958 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.643 ms/op
                 createUser·p0.50:   2.941 ms/op
                 createUser·p0.90:   3.346 ms/op
                 createUser·p0.95:   3.580 ms/op
                 createUser·p0.99:   4.243 ms/op
                 createUser·p0.999:  7.044 ms/op
                 createUser·p0.9999: 16.510 ms/op
                 createUser·p1.00:   17.007 ms/op

Iteration   2: 2.939 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.244 ms/op
                 createUser·p0.50:   2.925 ms/op
                 createUser·p0.90:   3.289 ms/op
                 createUser·p0.95:   3.416 ms/op
                 createUser·p0.99:   4.202 ms/op
                 createUser·p0.999:  7.436 ms/op
                 createUser·p0.9999: 18.055 ms/op
                 createUser·p1.00:   18.547 ms/op

Iteration   3: 3.011 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.583 ms/op
                 createUser·p0.50:   2.998 ms/op
                 createUser·p0.90:   3.572 ms/op
                 createUser·p0.95:   3.759 ms/op
                 createUser·p0.99:   4.284 ms/op
                 createUser·p0.999:  9.173 ms/op
                 createUser·p0.9999: 18.080 ms/op
                 createUser·p1.00:   18.809 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 323131
  mean =      2.969 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1090 
    [ 1.250,  2.500) = 21894 
    [ 2.500,  3.750) = 289034 
    [ 3.750,  5.000) = 10048 
    [ 5.000,  6.250) = 465 
    [ 6.250,  7.500) = 235 
    [ 7.500,  8.750) = 81 
    [ 8.750, 10.000) = 60 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 27 
    [13.750, 15.000) = 29 
    [15.000, 16.250) = 58 
    [16.250, 17.500) = 33 
    [17.500, 18.750) = 41 

  Percentiles, ms/op:
      p(0.0000) =      0.244 ms/op
     p(50.0000) =      2.949 ms/op
     p(90.0000) =      3.408 ms/op
     p(95.0000) =      3.637 ms/op
     p(99.0000) =      4.243 ms/op
     p(99.9000) =      7.987 ms/op
     p(99.9900) =     17.848 ms/op
     p(99.9990) =     18.723 ms/op
     p(99.9999) =     18.809 ms/op
    p(100.0000) =     18.809 ms/op


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
# Warmup Iteration   1: 3.354 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 2.940 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.898 ±(99.9%) 0.006 ms/op
Iteration   1: 2.836 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.654 ms/op
                 existUser·p0.50:   2.875 ms/op
                 existUser·p0.90:   3.424 ms/op
                 existUser·p0.95:   3.580 ms/op
                 existUser·p0.99:   4.350 ms/op
                 existUser·p0.999:  6.613 ms/op
                 existUser·p0.9999: 12.176 ms/op
                 existUser·p1.00:   12.583 ms/op

Iteration   2: 2.848 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.618 ms/op
                 existUser·p0.50:   2.855 ms/op
                 existUser·p0.90:   3.314 ms/op
                 existUser·p0.95:   3.514 ms/op
                 existUser·p0.99:   4.208 ms/op
                 existUser·p0.999:  6.909 ms/op
                 existUser·p0.9999: 25.813 ms/op
                 existUser·p1.00:   26.214 ms/op

Iteration   3: 2.854 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.712 ms/op
                 existUser·p0.50:   2.863 ms/op
                 existUser·p0.90:   3.445 ms/op
                 existUser·p0.95:   3.641 ms/op
                 existUser·p0.99:   4.334 ms/op
                 existUser·p0.999:  6.601 ms/op
                 existUser·p0.9999: 23.790 ms/op
                 existUser·p1.00:   23.921 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 337261
  mean =      2.846 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 55799 
    [ 2.500,  5.000) = 280516 
    [ 5.000,  7.500) = 702 
    [ 7.500, 10.000) = 94 
    [10.000, 12.500) = 52 
    [12.500, 15.000) = 25 
    [15.000, 17.500) = 9 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.618 ms/op
     p(50.0000) =      2.863 ms/op
     p(90.0000) =      3.400 ms/op
     p(95.0000) =      3.588 ms/op
     p(99.0000) =      4.301 ms/op
     p(99.9000) =      6.636 ms/op
     p(99.9900) =     23.921 ms/op
     p(99.9990) =     26.104 ms/op
     p(99.9999) =     26.214 ms/op
    p(100.0000) =     26.214 ms/op


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
# Warmup Iteration   1: 3.841 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.056 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.988 ±(99.9%) 0.007 ms/op
Iteration   1: 2.968 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.616 ms/op
                 getUser·p0.50:   2.949 ms/op
                 getUser·p0.90:   3.379 ms/op
                 getUser·p0.95:   3.604 ms/op
                 getUser·p0.99:   4.375 ms/op
                 getUser·p0.999:  7.207 ms/op
                 getUser·p0.9999: 15.232 ms/op
                 getUser·p1.00:   15.876 ms/op

Iteration   2: 3.006 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.632 ms/op
                 getUser·p0.50:   2.986 ms/op
                 getUser·p0.90:   3.531 ms/op
                 getUser·p0.95:   3.699 ms/op
                 getUser·p0.99:   4.309 ms/op
                 getUser·p0.999:  8.183 ms/op
                 getUser·p0.9999: 17.826 ms/op
                 getUser·p1.00:   19.628 ms/op

Iteration   3: 2.994 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.586 ms/op
                 getUser·p0.50:   2.966 ms/op
                 getUser·p0.90:   3.473 ms/op
                 getUser·p0.95:   3.723 ms/op
                 getUser·p0.99:   4.432 ms/op
                 getUser·p0.999:  7.160 ms/op
                 getUser·p0.9999: 17.542 ms/op
                 getUser·p1.00:   18.219 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 321266
  mean =      2.989 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 869 
    [ 1.250,  2.500) = 25899 
    [ 2.500,  3.750) = 281206 
    [ 3.750,  5.000) = 12153 
    [ 5.000,  6.250) = 572 
    [ 6.250,  7.500) = 261 
    [ 7.500,  8.750) = 49 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 16 
    [12.500, 13.750) = 25 
    [13.750, 15.000) = 102 
    [15.000, 16.250) = 55 
    [16.250, 17.500) = 18 
    [17.500, 18.750) = 35 

  Percentiles, ms/op:
      p(0.0000) =      0.586 ms/op
     p(50.0000) =      2.966 ms/op
     p(90.0000) =      3.469 ms/op
     p(95.0000) =      3.682 ms/op
     p(99.0000) =      4.383 ms/op
     p(99.9000) =      7.309 ms/op
     p(99.9900) =     17.695 ms/op
     p(99.9990) =     19.076 ms/op
     p(99.9999) =     19.628 ms/op
    p(100.0000) =     19.628 ms/op


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
# Warmup Iteration   1: 5.091 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 4.045 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.949 ±(99.9%) 0.010 ms/op
Iteration   1: 3.946 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.262 ms/op
                 listUser·p0.50:   3.817 ms/op
                 listUser·p0.90:   4.833 ms/op
                 listUser·p0.95:   5.571 ms/op
                 listUser·p0.99:   6.865 ms/op
                 listUser·p0.999:  11.747 ms/op
                 listUser·p0.9999: 13.967 ms/op
                 listUser·p1.00:   14.516 ms/op

Iteration   2: 3.902 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.522 ms/op
                 listUser·p0.50:   3.764 ms/op
                 listUser·p0.90:   4.653 ms/op
                 listUser·p0.95:   5.521 ms/op
                 listUser·p0.99:   6.914 ms/op
                 listUser·p0.999:  15.664 ms/op
                 listUser·p0.9999: 19.917 ms/op
                 listUser·p1.00:   20.152 ms/op

Iteration   3: 3.907 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.204 ms/op
                 listUser·p0.50:   3.756 ms/op
                 listUser·p0.90:   4.850 ms/op
                 listUser·p0.95:   5.546 ms/op
                 listUser·p0.99:   6.857 ms/op
                 listUser·p0.999:  15.863 ms/op
                 listUser·p0.9999: 20.985 ms/op
                 listUser·p1.00:   21.692 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 244967
  mean =      3.918 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3840 
    [ 2.500,  5.000) = 221158 
    [ 5.000,  7.500) = 18676 
    [ 7.500, 10.000) = 773 
    [10.000, 12.500) = 135 
    [12.500, 15.000) = 193 
    [15.000, 17.500) = 119 
    [17.500, 20.000) = 42 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.204 ms/op
     p(50.0000) =      3.781 ms/op
     p(90.0000) =      4.784 ms/op
     p(95.0000) =      5.546 ms/op
     p(99.0000) =      6.881 ms/op
     p(99.9000) =     13.977 ms/op
     p(99.9900) =     20.218 ms/op
     p(99.9990) =     21.403 ms/op
     p(99.9999) =     21.692 ms/op
    p(100.0000) =     21.692 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.806 ± 0.833  ops/ms
ClientGrpc.existUser                       thrpt       3  11.178 ± 1.548  ops/ms
ClientGrpc.getUser                         thrpt       3  10.906 ± 1.711  ops/ms
ClientGrpc.listUser                        thrpt       3   8.240 ± 1.470  ops/ms
ClientGrpc.createUser                       avgt       3   3.006 ± 0.716   ms/op
ClientGrpc.existUser                        avgt       3   2.835 ± 1.167   ms/op
ClientGrpc.getUser                          avgt       3   2.949 ± 0.584   ms/op
ClientGrpc.listUser                         avgt       3   3.887 ± 0.946   ms/op
ClientGrpc.createUser                     sample  323131   2.969 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.244           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.949           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.408           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.637           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.243           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.987           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.848           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          18.809           ms/op
ClientGrpc.existUser                      sample  337261   2.846 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.618           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.863           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.400           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.588           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.301           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.636           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          23.921           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          26.214           ms/op
ClientGrpc.getUser                        sample  321266   2.989 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.586           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.966           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.469           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.682           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.383           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.309           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.695           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.628           ms/op
ClientGrpc.listUser                       sample  244967   3.918 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.204           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.781           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.784           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.546           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.881           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.977           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          20.218           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          21.692           ms/op
