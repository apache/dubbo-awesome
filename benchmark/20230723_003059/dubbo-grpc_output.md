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
# Warmup Iteration   1: 4.429 ops/ms
# Warmup Iteration   2: 9.136 ops/ms
# Warmup Iteration   3: 9.838 ops/ms
Iteration   1: 10.292 ops/ms
Iteration   2: 10.469 ops/ms
Iteration   3: 10.384 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.382 ±(99.9%) 1.619 ops/ms [Average]
  (min, avg, max) = (10.292, 10.382, 10.469), stdev = 0.089
  CI (99.9%): [8.763, 12.001] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.721 ops/ms
# Warmup Iteration   2: 10.617 ops/ms
# Warmup Iteration   3: 10.957 ops/ms
Iteration   1: 10.961 ops/ms
Iteration   2: 11.167 ops/ms
Iteration   3: 10.833 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.987 ±(99.9%) 3.077 ops/ms [Average]
  (min, avg, max) = (10.833, 10.987, 11.167), stdev = 0.169
  CI (99.9%): [7.911, 14.064] (assumes normal distribution)


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
# Warmup Iteration   1: 6.809 ops/ms
# Warmup Iteration   2: 9.838 ops/ms
# Warmup Iteration   3: 10.374 ops/ms
Iteration   1: 10.291 ops/ms
Iteration   2: 10.371 ops/ms
Iteration   3: 10.323 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.329 ±(99.9%) 0.737 ops/ms [Average]
  (min, avg, max) = (10.291, 10.329, 10.371), stdev = 0.040
  CI (99.9%): [9.591, 11.066] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.381 ops/ms
# Warmup Iteration   2: 7.681 ops/ms
# Warmup Iteration   3: 7.815 ops/ms
Iteration   1: 8.074 ops/ms
Iteration   2: 7.861 ops/ms
Iteration   3: 7.845 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.927 ±(99.9%) 2.330 ops/ms [Average]
  (min, avg, max) = (7.845, 7.927, 8.074), stdev = 0.128
  CI (99.9%): [5.597, 10.257] (assumes normal distribution)


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
# Warmup Iteration   1: 4.442 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.245 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.119 ±(99.9%) 0.011 ms/op
Iteration   1: 3.100 ±(99.9%) 0.002 ms/op
Iteration   2: 3.101 ±(99.9%) 0.002 ms/op
Iteration   3: 3.088 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.096 ±(99.9%) 0.131 ms/op [Average]
  (min, avg, max) = (3.088, 3.096, 3.101), stdev = 0.007
  CI (99.9%): [2.965, 3.228] (assumes normal distribution)


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
# Warmup Iteration   1: 4.262 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.054 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.012 ±(99.9%) 0.003 ms/op
Iteration   1: 2.952 ±(99.9%) 0.003 ms/op
Iteration   2: 2.945 ±(99.9%) 0.003 ms/op
Iteration   3: 2.906 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.934 ±(99.9%) 0.455 ms/op [Average]
  (min, avg, max) = (2.906, 2.934, 2.952), stdev = 0.025
  CI (99.9%): [2.479, 3.390] (assumes normal distribution)


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
# Warmup Iteration   1: 4.366 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.217 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.123 ±(99.9%) 0.003 ms/op
Iteration   1: 3.062 ±(99.9%) 0.003 ms/op
Iteration   2: 3.088 ±(99.9%) 0.004 ms/op
Iteration   3: 3.047 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.066 ±(99.9%) 0.384 ms/op [Average]
  (min, avg, max) = (3.047, 3.066, 3.088), stdev = 0.021
  CI (99.9%): [2.681, 3.450] (assumes normal distribution)


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
# Warmup Iteration   1: 5.540 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 4.172 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.226 ±(99.9%) 0.015 ms/op
Iteration   1: 4.030 ±(99.9%) 0.006 ms/op
Iteration   2: 4.122 ±(99.9%) 0.013 ms/op
Iteration   3: 4.085 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.079 ±(99.9%) 0.844 ms/op [Average]
  (min, avg, max) = (4.030, 4.079, 4.122), stdev = 0.046
  CI (99.9%): [3.235, 4.923] (assumes normal distribution)


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
# Warmup Iteration   1: 4.477 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.296 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.085 ±(99.9%) 0.006 ms/op
Iteration   1: 3.054 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.556 ms/op
                 createUser·p0.50:   3.023 ms/op
                 createUser·p0.90:   3.494 ms/op
                 createUser·p0.95:   3.752 ms/op
                 createUser·p0.99:   4.432 ms/op
                 createUser·p0.999:  7.394 ms/op
                 createUser·p0.9999: 18.695 ms/op
                 createUser·p1.00:   18.907 ms/op

Iteration   2: 3.059 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.911 ms/op
                 createUser·p0.50:   3.019 ms/op
                 createUser·p0.90:   3.551 ms/op
                 createUser·p0.95:   3.752 ms/op
                 createUser·p0.99:   4.399 ms/op
                 createUser·p0.999:  7.482 ms/op
                 createUser·p0.9999: 14.312 ms/op
                 createUser·p1.00:   15.090 ms/op

Iteration   3: 3.079 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.651 ms/op
                 createUser·p0.50:   3.056 ms/op
                 createUser·p0.90:   3.457 ms/op
                 createUser·p0.95:   3.682 ms/op
                 createUser·p0.99:   4.211 ms/op
                 createUser·p0.999:  7.209 ms/op
                 createUser·p0.9999: 16.551 ms/op
                 createUser·p1.00:   17.138 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 313077
  mean =      3.064 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 251 
    [ 1.250,  2.500) = 12962 
    [ 2.500,  3.750) = 285199 
    [ 3.750,  5.000) = 13357 
    [ 5.000,  6.250) = 694 
    [ 6.250,  7.500) = 324 
    [ 7.500,  8.750) = 32 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 45 
    [11.250, 12.500) = 46 
    [12.500, 13.750) = 28 
    [13.750, 15.000) = 49 
    [15.000, 16.250) = 22 
    [16.250, 17.500) = 35 
    [17.500, 18.750) = 27 

  Percentiles, ms/op:
      p(0.0000) =      0.556 ms/op
     p(50.0000) =      3.035 ms/op
     p(90.0000) =      3.502 ms/op
     p(95.0000) =      3.727 ms/op
     p(99.0000) =      4.358 ms/op
     p(99.9000) =      7.299 ms/op
     p(99.9900) =     17.904 ms/op
     p(99.9990) =     18.837 ms/op
     p(99.9999) =     18.907 ms/op
    p(100.0000) =     18.907 ms/op


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
# Warmup Iteration   1: 3.815 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.064 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.957 ±(99.9%) 0.005 ms/op
Iteration   1: 2.921 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.766 ms/op
                 existUser·p0.50:   2.937 ms/op
                 existUser·p0.90:   3.400 ms/op
                 existUser·p0.95:   3.568 ms/op
                 existUser·p0.99:   4.219 ms/op
                 existUser·p0.999:  7.594 ms/op
                 existUser·p0.9999: 12.338 ms/op
                 existUser·p1.00:   12.993 ms/op

Iteration   2: 2.911 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.597 ms/op
                 existUser·p0.50:   2.929 ms/op
                 existUser·p0.90:   3.523 ms/op
                 existUser·p0.95:   3.731 ms/op
                 existUser·p0.99:   4.620 ms/op
                 existUser·p0.999:  10.584 ms/op
                 existUser·p0.9999: 13.828 ms/op
                 existUser·p1.00:   14.189 ms/op

Iteration   3: 2.990 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.591 ms/op
                 existUser·p0.50:   2.961 ms/op
                 existUser·p0.90:   3.514 ms/op
                 existUser·p0.95:   3.641 ms/op
                 existUser·p0.99:   4.096 ms/op
                 existUser·p0.999:  6.029 ms/op
                 existUser·p0.9999: 16.597 ms/op
                 existUser·p1.00:   16.974 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 326362
  mean =      2.940 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2978 
    [ 1.250,  2.500) = 33828 
    [ 2.500,  3.750) = 278606 
    [ 3.750,  5.000) = 9502 
    [ 5.000,  6.250) = 825 
    [ 6.250,  7.500) = 273 
    [ 7.500,  8.750) = 50 
    [ 8.750, 10.000) = 69 
    [10.000, 11.250) = 67 
    [11.250, 12.500) = 37 
    [12.500, 13.750) = 49 
    [13.750, 15.000) = 33 
    [15.000, 16.250) = 10 
    [16.250, 17.500) = 35 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.591 ms/op
     p(50.0000) =      2.941 ms/op
     p(90.0000) =      3.478 ms/op
     p(95.0000) =      3.654 ms/op
     p(99.0000) =      4.309 ms/op
     p(99.9000) =      7.817 ms/op
     p(99.9900) =     16.292 ms/op
     p(99.9990) =     16.825 ms/op
     p(99.9999) =     16.974 ms/op
    p(100.0000) =     16.974 ms/op


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
# Warmup Iteration   1: 4.315 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.130 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.075 ±(99.9%) 0.006 ms/op
Iteration   1: 3.087 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.810 ms/op
                 getUser·p0.50:   3.052 ms/op
                 getUser·p0.90:   3.621 ms/op
                 getUser·p0.95:   3.863 ms/op
                 getUser·p0.99:   4.841 ms/op
                 getUser·p0.999:  8.773 ms/op
                 getUser·p0.9999: 18.404 ms/op
                 getUser·p1.00:   18.907 ms/op

Iteration   2: 3.008 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.902 ms/op
                 getUser·p0.50:   2.994 ms/op
                 getUser·p0.90:   3.383 ms/op
                 getUser·p0.95:   3.564 ms/op
                 getUser·p0.99:   4.342 ms/op
                 getUser·p0.999:  7.256 ms/op
                 getUser·p0.9999: 19.104 ms/op
                 getUser·p1.00:   19.333 ms/op

Iteration   3: 3.047 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.692 ms/op
                 getUser·p0.50:   3.015 ms/op
                 getUser·p0.90:   3.527 ms/op
                 getUser·p0.95:   3.748 ms/op
                 getUser·p0.99:   4.375 ms/op
                 getUser·p0.999:  7.349 ms/op
                 getUser·p0.9999: 17.597 ms/op
                 getUser·p1.00:   19.235 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 314881
  mean =      3.047 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 555 
    [ 1.250,  2.500) = 16854 
    [ 2.500,  3.750) = 281765 
    [ 3.750,  5.000) = 14038 
    [ 5.000,  6.250) = 1101 
    [ 6.250,  7.500) = 219 
    [ 7.500,  8.750) = 72 
    [ 8.750, 10.000) = 41 
    [10.000, 11.250) = 42 
    [11.250, 12.500) = 29 
    [12.500, 13.750) = 20 
    [13.750, 15.000) = 35 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 33 
    [17.500, 18.750) = 47 

  Percentiles, ms/op:
      p(0.0000) =      0.692 ms/op
     p(50.0000) =      3.019 ms/op
     p(90.0000) =      3.510 ms/op
     p(95.0000) =      3.748 ms/op
     p(99.0000) =      4.612 ms/op
     p(99.9000) =      8.178 ms/op
     p(99.9900) =     18.678 ms/op
     p(99.9990) =     19.291 ms/op
     p(99.9999) =     19.333 ms/op
    p(100.0000) =     19.333 ms/op


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
# Warmup Iteration   1: 5.499 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 4.060 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.972 ±(99.9%) 0.010 ms/op
Iteration   1: 3.947 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.657 ms/op
                 listUser·p0.50:   3.764 ms/op
                 listUser·p0.90:   4.866 ms/op
                 listUser·p0.95:   5.759 ms/op
                 listUser·p0.99:   7.154 ms/op
                 listUser·p0.999:  14.183 ms/op
                 listUser·p0.9999: 16.085 ms/op
                 listUser·p1.00:   20.972 ms/op

Iteration   2: 3.959 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.196 ms/op
                 listUser·p0.50:   3.834 ms/op
                 listUser·p0.90:   4.669 ms/op
                 listUser·p0.95:   5.718 ms/op
                 listUser·p0.99:   6.765 ms/op
                 listUser·p0.999:  14.110 ms/op
                 listUser·p0.9999: 22.381 ms/op
                 listUser·p1.00:   23.036 ms/op

Iteration   3: 3.956 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.848 ms/op
                 listUser·p0.50:   3.793 ms/op
                 listUser·p0.90:   4.940 ms/op
                 listUser·p0.95:   5.382 ms/op
                 listUser·p0.99:   6.758 ms/op
                 listUser·p0.999:  15.514 ms/op
                 listUser·p0.9999: 22.708 ms/op
                 listUser·p1.00:   23.003 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 242820
  mean =      3.954 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2509 
    [ 2.500,  5.000) = 219638 
    [ 5.000,  7.500) = 19315 
    [ 7.500, 10.000) = 847 
    [10.000, 12.500) = 107 
    [12.500, 15.000) = 213 
    [15.000, 17.500) = 95 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 47 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.848 ms/op
     p(50.0000) =      3.801 ms/op
     p(90.0000) =      4.858 ms/op
     p(95.0000) =      5.620 ms/op
     p(99.0000) =      6.881 ms/op
     p(99.9000) =     14.500 ms/op
     p(99.9900) =     22.381 ms/op
     p(99.9990) =     22.961 ms/op
     p(99.9999) =     23.036 ms/op
    p(100.0000) =     23.036 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.382 ± 1.619  ops/ms
ClientGrpc.existUser                       thrpt       3  10.987 ± 3.077  ops/ms
ClientGrpc.getUser                         thrpt       3  10.329 ± 0.737  ops/ms
ClientGrpc.listUser                        thrpt       3   7.927 ± 2.330  ops/ms
ClientGrpc.createUser                       avgt       3   3.096 ± 0.131   ms/op
ClientGrpc.existUser                        avgt       3   2.934 ± 0.455   ms/op
ClientGrpc.getUser                          avgt       3   3.066 ± 0.384   ms/op
ClientGrpc.listUser                         avgt       3   4.079 ± 0.844   ms/op
ClientGrpc.createUser                     sample  313077   3.064 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.556           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.035           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.502           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.727           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.358           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.299           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.904           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          18.907           ms/op
ClientGrpc.existUser                      sample  326362   2.940 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.591           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.941           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.478           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.654           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.309           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.817           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.292           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          16.974           ms/op
ClientGrpc.getUser                        sample  314881   3.047 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.692           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.019           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.510           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.748           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.612           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.178           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.678           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.333           ms/op
ClientGrpc.listUser                       sample  242820   3.954 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.848           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.801           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.858           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.620           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.881           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.500           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.381           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.036           ms/op
