# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.098 ops/ms
# Warmup Iteration   2: 8.727 ops/ms
# Warmup Iteration   3: 10.288 ops/ms
Iteration   1: 10.420 ops/ms
Iteration   2: 10.689 ops/ms
Iteration   3: 10.512 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.540 ±(99.9%) 2.492 ops/ms [Average]
  (min, avg, max) = (10.420, 10.540, 10.689), stdev = 0.137
  CI (99.9%): [8.048, 13.032] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.691 ops/ms
# Warmup Iteration   2: 10.523 ops/ms
# Warmup Iteration   3: 11.370 ops/ms
Iteration   1: 11.139 ops/ms
Iteration   2: 11.208 ops/ms
Iteration   3: 11.078 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.141 ±(99.9%) 1.186 ops/ms [Average]
  (min, avg, max) = (11.078, 11.141, 11.208), stdev = 0.065
  CI (99.9%): [9.956, 12.327] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.545 ops/ms
# Warmup Iteration   2: 10.302 ops/ms
# Warmup Iteration   3: 10.449 ops/ms
Iteration   1: 10.623 ops/ms
Iteration   2: 10.656 ops/ms
Iteration   3: 10.615 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.632 ±(99.9%) 0.400 ops/ms [Average]
  (min, avg, max) = (10.615, 10.632, 10.656), stdev = 0.022
  CI (99.9%): [10.232, 11.031] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.363 ops/ms
# Warmup Iteration   2: 7.925 ops/ms
# Warmup Iteration   3: 8.041 ops/ms
Iteration   1: 7.912 ops/ms
Iteration   2: 8.051 ops/ms
Iteration   3: 8.015 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.993 ±(99.9%) 1.317 ops/ms [Average]
  (min, avg, max) = (7.912, 7.993, 8.051), stdev = 0.072
  CI (99.9%): [6.676, 9.310] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.631 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.205 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.055 ±(99.9%) 0.007 ms/op
Iteration   1: 3.008 ±(99.9%) 0.001 ms/op
Iteration   2: 3.076 ±(99.9%) 0.003 ms/op
Iteration   3: 3.028 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.037 ±(99.9%) 0.643 ms/op [Average]
  (min, avg, max) = (3.008, 3.037, 3.076), stdev = 0.035
  CI (99.9%): [2.394, 3.680] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 4.043 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.049 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.851 ±(99.9%) 0.003 ms/op
Iteration   1: 2.830 ±(99.9%) 0.004 ms/op
Iteration   2: 2.848 ±(99.9%) 0.003 ms/op
Iteration   3: 2.914 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.864 ±(99.9%) 0.807 ms/op [Average]
  (min, avg, max) = (2.830, 2.864, 2.914), stdev = 0.044
  CI (99.9%): [2.057, 3.671] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.285 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.071 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.068 ±(99.9%) 0.003 ms/op
Iteration   1: 2.988 ±(99.9%) 0.003 ms/op
Iteration   2: 3.008 ±(99.9%) 0.003 ms/op
Iteration   3: 2.953 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.983 ±(99.9%) 0.507 ms/op [Average]
  (min, avg, max) = (2.953, 2.983, 3.008), stdev = 0.028
  CI (99.9%): [2.476, 3.489] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 5.356 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 4.147 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.008 ±(99.9%) 0.019 ms/op
Iteration   1: 3.995 ±(99.9%) 0.010 ms/op
Iteration   2: 3.939 ±(99.9%) 0.014 ms/op
Iteration   3: 3.872 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.935 ±(99.9%) 1.122 ms/op [Average]
  (min, avg, max) = (3.872, 3.935, 3.995), stdev = 0.061
  CI (99.9%): [2.813, 5.057] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.159 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.212 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.017 ±(99.9%) 0.007 ms/op
Iteration   1: 2.994 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.735 ms/op
                 createUser·p0.50:   2.961 ms/op
                 createUser·p0.90:   3.400 ms/op
                 createUser·p0.95:   3.645 ms/op
                 createUser·p0.99:   4.588 ms/op
                 createUser·p0.999:  7.307 ms/op
                 createUser·p0.9999: 20.523 ms/op
                 createUser·p1.00:   20.873 ms/op

Iteration   2: 3.014 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.842 ms/op
                 createUser·p0.50:   2.978 ms/op
                 createUser·p0.90:   3.498 ms/op
                 createUser·p0.95:   3.768 ms/op
                 createUser·p0.99:   4.628 ms/op
                 createUser·p0.999:  7.614 ms/op
                 createUser·p0.9999: 35.193 ms/op
                 createUser·p1.00:   35.586 ms/op

Iteration   3: 3.054 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.754 ms/op
                 createUser·p0.50:   3.006 ms/op
                 createUser·p0.90:   3.535 ms/op
                 createUser·p0.95:   3.801 ms/op
                 createUser·p0.99:   4.325 ms/op
                 createUser·p0.999:  8.620 ms/op
                 createUser·p0.9999: 23.888 ms/op
                 createUser·p1.00:   24.314 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 317849
  mean =      3.020 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21389 
    [ 2.500,  5.000) = 294994 
    [ 5.000,  7.500) = 1142 
    [ 7.500, 10.000) = 128 
    [10.000, 12.500) = 4 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 51 
    [20.000, 22.500) = 81 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 13 
    [35.000, 37.500) = 19 

  Percentiles, ms/op:
      p(0.0000) =      0.735 ms/op
     p(50.0000) =      2.982 ms/op
     p(90.0000) =      3.482 ms/op
     p(95.0000) =      3.740 ms/op
     p(99.0000) =      4.506 ms/op
     p(99.9000) =      7.562 ms/op
     p(99.9900) =     34.669 ms/op
     p(99.9990) =     35.443 ms/op
     p(99.9999) =     35.586 ms/op
    p(100.0000) =     35.586 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.704 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.063 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.918 ±(99.9%) 0.005 ms/op
Iteration   1: 2.971 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.977 ms/op
                 existUser·p0.50:   2.920 ms/op
                 existUser·p0.90:   3.478 ms/op
                 existUser·p0.95:   3.670 ms/op
                 existUser·p0.99:   4.211 ms/op
                 existUser·p0.999:  6.898 ms/op
                 existUser·p0.9999: 22.036 ms/op
                 existUser·p1.00:   22.512 ms/op

Iteration   2: 2.895 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.628 ms/op
                 existUser·p0.50:   2.892 ms/op
                 existUser·p0.90:   3.432 ms/op
                 existUser·p0.95:   3.654 ms/op
                 existUser·p0.99:   4.301 ms/op
                 existUser·p0.999:  6.442 ms/op
                 existUser·p0.9999: 14.120 ms/op
                 existUser·p1.00:   14.746 ms/op

Iteration   3: 2.939 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.767 ms/op
                 existUser·p0.50:   2.888 ms/op
                 existUser·p0.90:   3.449 ms/op
                 existUser·p0.95:   3.641 ms/op
                 existUser·p0.99:   4.202 ms/op
                 existUser·p0.999:  10.454 ms/op
                 existUser·p0.9999: 16.651 ms/op
                 existUser·p1.00:   16.777 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 327122
  mean =      2.935 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 38346 
    [ 2.500,  5.000) = 287583 
    [ 5.000,  7.500) = 853 
    [ 7.500, 10.000) = 115 
    [10.000, 12.500) = 72 
    [12.500, 15.000) = 62 
    [15.000, 17.500) = 59 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.628 ms/op
     p(50.0000) =      2.900 ms/op
     p(90.0000) =      3.453 ms/op
     p(95.0000) =      3.654 ms/op
     p(99.0000) =      4.243 ms/op
     p(99.9000) =      7.689 ms/op
     p(99.9900) =     18.040 ms/op
     p(99.9990) =     22.413 ms/op
     p(99.9999) =     22.512 ms/op
    p(100.0000) =     22.512 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.412 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.157 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.055 ±(99.9%) 0.006 ms/op
Iteration   1: 3.011 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.884 ms/op
                 getUser·p0.50:   2.970 ms/op
                 getUser·p0.90:   3.531 ms/op
                 getUser·p0.95:   3.850 ms/op
                 getUser·p0.99:   4.735 ms/op
                 getUser·p0.999:  7.099 ms/op
                 getUser·p0.9999: 12.595 ms/op
                 getUser·p1.00:   12.845 ms/op

Iteration   2: 3.039 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.876 ms/op
                 getUser·p0.50:   2.998 ms/op
                 getUser·p0.90:   3.555 ms/op
                 getUser·p0.95:   3.834 ms/op
                 getUser·p0.99:   4.833 ms/op
                 getUser·p0.999:  7.664 ms/op
                 getUser·p0.9999: 14.786 ms/op
                 getUser·p1.00:   15.106 ms/op

Iteration   3: 3.003 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.853 ms/op
                 getUser·p0.50:   2.982 ms/op
                 getUser·p0.90:   3.482 ms/op
                 getUser·p0.95:   3.674 ms/op
                 getUser·p0.99:   4.432 ms/op
                 getUser·p0.999:  9.195 ms/op
                 getUser·p0.9999: 17.891 ms/op
                 getUser·p1.00:   19.759 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 318125
  mean =      3.017 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 877 
    [ 1.250,  2.500) = 22966 
    [ 2.500,  3.750) = 277108 
    [ 3.750,  5.000) = 15277 
    [ 5.000,  6.250) = 1113 
    [ 6.250,  7.500) = 428 
    [ 7.500,  8.750) = 63 
    [ 8.750, 10.000) = 50 
    [10.000, 11.250) = 18 
    [11.250, 12.500) = 69 
    [12.500, 13.750) = 29 
    [13.750, 15.000) = 77 
    [15.000, 16.250) = 15 
    [16.250, 17.500) = 7 
    [17.500, 18.750) = 26 

  Percentiles, ms/op:
      p(0.0000) =      0.853 ms/op
     p(50.0000) =      2.986 ms/op
     p(90.0000) =      3.518 ms/op
     p(95.0000) =      3.785 ms/op
     p(99.0000) =      4.702 ms/op
     p(99.9000) =      8.158 ms/op
     p(99.9900) =     16.974 ms/op
     p(99.9990) =     17.891 ms/op
     p(99.9999) =     19.759 ms/op
    p(100.0000) =     19.759 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.248 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.038 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.847 ±(99.9%) 0.011 ms/op
Iteration   1: 3.936 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.047 ms/op
                 listUser·p0.50:   3.777 ms/op
                 listUser·p0.90:   5.054 ms/op
                 listUser·p0.95:   5.956 ms/op
                 listUser·p0.99:   6.966 ms/op
                 listUser·p0.999:  12.939 ms/op
                 listUser·p0.9999: 21.881 ms/op
                 listUser·p1.00:   22.282 ms/op

Iteration   2: 4.095 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.176 ms/op
                 listUser·p0.50:   3.887 ms/op
                 listUser·p0.90:   5.128 ms/op
                 listUser·p0.95:   5.988 ms/op
                 listUser·p0.99:   7.438 ms/op
                 listUser·p0.999:  17.720 ms/op
                 listUser·p0.9999: 28.088 ms/op
                 listUser·p1.00:   28.508 ms/op

Iteration   3: 4.007 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.356 ms/op
                 listUser·p0.50:   3.838 ms/op
                 listUser·p0.90:   4.932 ms/op
                 listUser·p0.95:   5.792 ms/op
                 listUser·p0.99:   7.119 ms/op
                 listUser·p0.999:  14.503 ms/op
                 listUser·p0.9999: 17.007 ms/op
                 listUser·p1.00:   19.235 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 239334
  mean =      4.012 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2819 
    [ 2.500,  5.000) = 211986 
    [ 5.000,  7.500) = 22745 
    [ 7.500, 10.000) = 1258 
    [10.000, 12.500) = 139 
    [12.500, 15.000) = 166 
    [15.000, 17.500) = 97 
    [17.500, 20.000) = 46 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 40 

  Percentiles, ms/op:
      p(0.0000) =      1.047 ms/op
     p(50.0000) =      3.834 ms/op
     p(90.0000) =      5.030 ms/op
     p(95.0000) =      5.917 ms/op
     p(99.0000) =      7.176 ms/op
     p(99.9000) =     14.718 ms/op
     p(99.9900) =     27.562 ms/op
     p(99.9990) =     28.424 ms/op
     p(99.9999) =     28.508 ms/op
    p(100.0000) =     28.508 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.540 ± 2.492  ops/ms
ClientGrpc.existUser                       thrpt       3  11.141 ± 1.186  ops/ms
ClientGrpc.getUser                         thrpt       3  10.632 ± 0.400  ops/ms
ClientGrpc.listUser                        thrpt       3   7.993 ± 1.317  ops/ms
ClientGrpc.createUser                       avgt       3   3.037 ± 0.643   ms/op
ClientGrpc.existUser                        avgt       3   2.864 ± 0.807   ms/op
ClientGrpc.getUser                          avgt       3   2.983 ± 0.507   ms/op
ClientGrpc.listUser                         avgt       3   3.935 ± 1.122   ms/op
ClientGrpc.createUser                     sample  317849   3.020 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.735           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.982           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.482           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.740           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.506           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.562           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          34.669           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          35.586           ms/op
ClientGrpc.existUser                      sample  327122   2.935 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.628           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.900           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.453           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.654           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.243           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.689           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.040           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.512           ms/op
ClientGrpc.getUser                        sample  318125   3.017 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.853           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.986           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.518           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.785           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.702           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.158           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.974           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.759           ms/op
ClientGrpc.listUser                       sample  239334   4.012 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.047           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.834           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.030           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.917           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.176           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.718           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          27.562           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          28.508           ms/op
