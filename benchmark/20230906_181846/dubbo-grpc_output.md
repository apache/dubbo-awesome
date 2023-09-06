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
# Warmup Iteration   1: 4.252 ops/ms
# Warmup Iteration   2: 9.113 ops/ms
# Warmup Iteration   3: 9.895 ops/ms
Iteration   1: 10.178 ops/ms
Iteration   2: 10.099 ops/ms
Iteration   3: 10.344 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.207 ±(99.9%) 2.278 ops/ms [Average]
  (min, avg, max) = (10.099, 10.207, 10.344), stdev = 0.125
  CI (99.9%): [7.929, 12.485] (assumes normal distribution)


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
# Warmup Iteration   1: 7.386 ops/ms
# Warmup Iteration   2: 10.387 ops/ms
# Warmup Iteration   3: 11.393 ops/ms
Iteration   1: 11.227 ops/ms
Iteration   2: 11.328 ops/ms
Iteration   3: 11.418 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.324 ±(99.9%) 1.745 ops/ms [Average]
  (min, avg, max) = (11.227, 11.324, 11.418), stdev = 0.096
  CI (99.9%): [9.579, 13.069] (assumes normal distribution)


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
# Warmup Iteration   1: 7.233 ops/ms
# Warmup Iteration   2: 10.049 ops/ms
# Warmup Iteration   3: 10.669 ops/ms
Iteration   1: 10.525 ops/ms
Iteration   2: 10.651 ops/ms
Iteration   3: 10.666 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.614 ±(99.9%) 1.413 ops/ms [Average]
  (min, avg, max) = (10.525, 10.614, 10.666), stdev = 0.077
  CI (99.9%): [9.201, 12.027] (assumes normal distribution)


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
# Warmup Iteration   1: 5.427 ops/ms
# Warmup Iteration   2: 8.005 ops/ms
# Warmup Iteration   3: 8.058 ops/ms
Iteration   1: 8.213 ops/ms
Iteration   2: 8.298 ops/ms
Iteration   3: 8.007 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.173 ±(99.9%) 2.731 ops/ms [Average]
  (min, avg, max) = (8.007, 8.173, 8.298), stdev = 0.150
  CI (99.9%): [5.442, 10.903] (assumes normal distribution)


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
# Warmup Iteration   1: 4.218 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.138 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.971 ±(99.9%) 0.004 ms/op
Iteration   1: 2.968 ±(99.9%) 0.005 ms/op
Iteration   2: 3.069 ±(99.9%) 0.007 ms/op
Iteration   3: 3.003 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.013 ±(99.9%) 0.935 ms/op [Average]
  (min, avg, max) = (2.968, 3.013, 3.069), stdev = 0.051
  CI (99.9%): [2.078, 3.949] (assumes normal distribution)


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
# Warmup Iteration   1: 3.559 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.991 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.945 ±(99.9%) 0.003 ms/op
Iteration   1: 2.805 ±(99.9%) 0.003 ms/op
Iteration   2: 2.923 ±(99.9%) 0.002 ms/op
Iteration   3: 2.790 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.840 ±(99.9%) 1.328 ms/op [Average]
  (min, avg, max) = (2.790, 2.840, 2.923), stdev = 0.073
  CI (99.9%): [1.511, 4.168] (assumes normal distribution)


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
# Warmup Iteration   1: 4.094 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.138 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.008 ±(99.9%) 0.003 ms/op
Iteration   1: 3.006 ±(99.9%) 0.002 ms/op
Iteration   2: 3.042 ±(99.9%) 0.003 ms/op
Iteration   3: 3.043 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.030 ±(99.9%) 0.389 ms/op [Average]
  (min, avg, max) = (3.006, 3.030, 3.043), stdev = 0.021
  CI (99.9%): [2.642, 3.419] (assumes normal distribution)


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
# Warmup Iteration   1: 5.138 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 4.106 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.967 ±(99.9%) 0.026 ms/op
Iteration   1: 4.009 ±(99.9%) 0.023 ms/op
Iteration   2: 3.901 ±(99.9%) 0.014 ms/op
Iteration   3: 3.982 ±(99.9%) 0.042 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.964 ±(99.9%) 1.026 ms/op [Average]
  (min, avg, max) = (3.901, 3.964, 4.009), stdev = 0.056
  CI (99.9%): [2.938, 4.991] (assumes normal distribution)


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
# Warmup Iteration   1: 4.101 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.202 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.035 ±(99.9%) 0.006 ms/op
Iteration   1: 3.023 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.796 ms/op
                 createUser·p0.50:   2.986 ms/op
                 createUser·p0.90:   3.518 ms/op
                 createUser·p0.95:   3.842 ms/op
                 createUser·p0.99:   4.555 ms/op
                 createUser·p0.999:  6.814 ms/op
                 createUser·p0.9999: 12.509 ms/op
                 createUser·p1.00:   12.878 ms/op

Iteration   2: 3.040 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.810 ms/op
                 createUser·p0.50:   3.002 ms/op
                 createUser·p0.90:   3.523 ms/op
                 createUser·p0.95:   3.731 ms/op
                 createUser·p0.99:   4.555 ms/op
                 createUser·p0.999:  8.426 ms/op
                 createUser·p0.9999: 13.901 ms/op
                 createUser·p1.00:   14.205 ms/op

Iteration   3: 3.027 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.840 ms/op
                 createUser·p0.50:   2.982 ms/op
                 createUser·p0.90:   3.441 ms/op
                 createUser·p0.95:   3.707 ms/op
                 createUser·p0.99:   4.704 ms/op
                 createUser·p0.999:  10.018 ms/op
                 createUser·p0.9999: 24.360 ms/op
                 createUser·p1.00:   24.707 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 316988
  mean =      3.030 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21477 
    [ 2.500,  5.000) = 293463 
    [ 5.000,  7.500) = 1554 
    [ 7.500, 10.000) = 258 
    [10.000, 12.500) = 66 
    [12.500, 15.000) = 89 
    [15.000, 17.500) = 48 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.796 ms/op
     p(50.0000) =      2.990 ms/op
     p(90.0000) =      3.494 ms/op
     p(95.0000) =      3.768 ms/op
     p(99.0000) =      4.597 ms/op
     p(99.9000) =      8.667 ms/op
     p(99.9900) =     23.832 ms/op
     p(99.9990) =     24.510 ms/op
     p(99.9999) =     24.707 ms/op
    p(100.0000) =     24.707 ms/op


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
# Warmup Iteration   1: 4.035 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.026 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.926 ±(99.9%) 0.006 ms/op
Iteration   1: 2.912 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.733 ms/op
                 existUser·p0.50:   2.892 ms/op
                 existUser·p0.90:   3.338 ms/op
                 existUser·p0.95:   3.539 ms/op
                 existUser·p0.99:   4.325 ms/op
                 existUser·p0.999:  8.030 ms/op
                 existUser·p0.9999: 11.895 ms/op
                 existUser·p1.00:   12.190 ms/op

Iteration   2: 2.939 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.851 ms/op
                 existUser·p0.50:   2.900 ms/op
                 existUser·p0.90:   3.391 ms/op
                 existUser·p0.95:   3.576 ms/op
                 existUser·p0.99:   4.219 ms/op
                 existUser·p0.999:  7.165 ms/op
                 existUser·p0.9999: 14.174 ms/op
                 existUser·p1.00:   14.615 ms/op

Iteration   3: 2.909 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.662 ms/op
                 existUser·p0.50:   2.884 ms/op
                 existUser·p0.90:   3.322 ms/op
                 existUser·p0.95:   3.510 ms/op
                 existUser·p0.99:   4.563 ms/op
                 existUser·p0.999:  8.028 ms/op
                 existUser·p0.9999: 15.631 ms/op
                 existUser·p1.00:   17.662 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 328544
  mean =      2.920 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1108 
    [ 1.250,  2.500) = 31488 
    [ 2.500,  3.750) = 288334 
    [ 3.750,  5.000) = 5773 
    [ 5.000,  6.250) = 920 
    [ 6.250,  7.500) = 458 
    [ 7.500,  8.750) = 203 
    [ 8.750, 10.000) = 22 
    [10.000, 11.250) = 77 
    [11.250, 12.500) = 73 
    [12.500, 13.750) = 30 
    [13.750, 15.000) = 26 
    [15.000, 16.250) = 23 
    [16.250, 17.500) = 7 
    [17.500, 18.750) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.662 ms/op
     p(50.0000) =      2.892 ms/op
     p(90.0000) =      3.351 ms/op
     p(95.0000) =      3.547 ms/op
     p(99.0000) =      4.375 ms/op
     p(99.9000) =      7.963 ms/op
     p(99.9900) =     14.677 ms/op
     p(99.9990) =     17.456 ms/op
     p(99.9999) =     17.662 ms/op
    p(100.0000) =     17.662 ms/op


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
# Warmup Iteration   1: 4.116 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.086 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.004 ±(99.9%) 0.007 ms/op
Iteration   1: 3.022 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.844 ms/op
                 getUser·p0.50:   2.998 ms/op
                 getUser·p0.90:   3.580 ms/op
                 getUser·p0.95:   3.838 ms/op
                 getUser·p0.99:   4.653 ms/op
                 getUser·p0.999:  9.093 ms/op
                 getUser·p0.9999: 14.418 ms/op
                 getUser·p1.00:   14.434 ms/op

Iteration   2: 3.061 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.798 ms/op
                 getUser·p0.50:   3.006 ms/op
                 getUser·p0.90:   3.641 ms/op
                 getUser·p0.95:   3.875 ms/op
                 getUser·p0.99:   4.948 ms/op
                 getUser·p0.999:  9.290 ms/op
                 getUser·p0.9999: 14.451 ms/op
                 getUser·p1.00:   14.696 ms/op

Iteration   3: 3.024 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.751 ms/op
                 getUser·p0.50:   2.990 ms/op
                 getUser·p0.90:   3.506 ms/op
                 getUser·p0.95:   3.789 ms/op
                 getUser·p0.99:   4.669 ms/op
                 getUser·p0.999:  9.318 ms/op
                 getUser·p0.9999: 22.281 ms/op
                 getUser·p1.00:   23.364 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 316013
  mean =      3.036 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26368 
    [ 2.500,  5.000) = 287237 
    [ 5.000,  7.500) = 1664 
    [ 7.500, 10.000) = 460 
    [10.000, 12.500) = 60 
    [12.500, 15.000) = 168 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.751 ms/op
     p(50.0000) =      2.998 ms/op
     p(90.0000) =      3.584 ms/op
     p(95.0000) =      3.834 ms/op
     p(99.0000) =      4.743 ms/op
     p(99.9000) =      9.191 ms/op
     p(99.9900) =     18.842 ms/op
     p(99.9990) =     23.326 ms/op
     p(99.9999) =     23.364 ms/op
    p(100.0000) =     23.364 ms/op


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
# Warmup Iteration   1: 5.529 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 4.031 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.926 ±(99.9%) 0.010 ms/op
Iteration   1: 3.909 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.814 ms/op
                 listUser·p0.50:   3.768 ms/op
                 listUser·p0.90:   4.833 ms/op
                 listUser·p0.95:   5.612 ms/op
                 listUser·p0.99:   6.804 ms/op
                 listUser·p0.999:  14.985 ms/op
                 listUser·p0.9999: 21.326 ms/op
                 listUser·p1.00:   21.955 ms/op

Iteration   2: 3.990 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.133 ms/op
                 listUser·p0.50:   3.838 ms/op
                 listUser·p0.90:   5.005 ms/op
                 listUser·p0.95:   5.603 ms/op
                 listUser·p0.99:   6.908 ms/op
                 listUser·p0.999:  14.319 ms/op
                 listUser·p0.9999: 16.383 ms/op
                 listUser·p1.00:   17.236 ms/op

Iteration   3: 3.936 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.806 ms/op
                 listUser·p0.50:   3.785 ms/op
                 listUser·p0.90:   4.915 ms/op
                 listUser·p0.95:   5.661 ms/op
                 listUser·p0.99:   7.000 ms/op
                 listUser·p0.999:  17.034 ms/op
                 listUser·p0.9999: 21.099 ms/op
                 listUser·p1.00:   21.496 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 243172
  mean =      3.945 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3934 
    [ 2.500,  5.000) = 216767 
    [ 5.000,  7.500) = 21088 
    [ 7.500, 10.000) = 845 
    [10.000, 12.500) = 167 
    [12.500, 15.000) = 111 
    [15.000, 17.500) = 173 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 46 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.806 ms/op
     p(50.0000) =      3.797 ms/op
     p(90.0000) =      4.923 ms/op
     p(95.0000) =      5.620 ms/op
     p(99.0000) =      6.881 ms/op
     p(99.9000) =     15.152 ms/op
     p(99.9900) =     21.070 ms/op
     p(99.9990) =     21.743 ms/op
     p(99.9999) =     21.955 ms/op
    p(100.0000) =     21.955 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.207 ± 2.278  ops/ms
ClientGrpc.existUser                       thrpt       3  11.324 ± 1.745  ops/ms
ClientGrpc.getUser                         thrpt       3  10.614 ± 1.413  ops/ms
ClientGrpc.listUser                        thrpt       3   8.173 ± 2.731  ops/ms
ClientGrpc.createUser                       avgt       3   3.013 ± 0.935   ms/op
ClientGrpc.existUser                        avgt       3   2.840 ± 1.328   ms/op
ClientGrpc.getUser                          avgt       3   3.030 ± 0.389   ms/op
ClientGrpc.listUser                         avgt       3   3.964 ± 1.026   ms/op
ClientGrpc.createUser                     sample  316988   3.030 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.796           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.990           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.494           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.768           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.597           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.667           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          23.832           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          24.707           ms/op
ClientGrpc.existUser                      sample  328544   2.920 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.662           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.892           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.351           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.547           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.375           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.963           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.677           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.662           ms/op
ClientGrpc.getUser                        sample  316013   3.036 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.751           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.998           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.584           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.834           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.743           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.191           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.842           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.364           ms/op
ClientGrpc.listUser                       sample  243172   3.945 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.806           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.797           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.923           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.620           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.881           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.152           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.070           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          21.955           ms/op
