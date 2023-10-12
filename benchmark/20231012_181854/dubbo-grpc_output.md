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
# Warmup Iteration   1: 3.761 ops/ms
# Warmup Iteration   2: 8.535 ops/ms
# Warmup Iteration   3: 9.545 ops/ms
Iteration   1: 9.894 ops/ms
Iteration   2: 10.052 ops/ms
Iteration   3: 10.088 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.011 ±(99.9%) 1.883 ops/ms [Average]
  (min, avg, max) = (9.894, 10.011, 10.088), stdev = 0.103
  CI (99.9%): [8.128, 11.895] (assumes normal distribution)


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
# Warmup Iteration   1: 6.852 ops/ms
# Warmup Iteration   2: 10.005 ops/ms
# Warmup Iteration   3: 10.479 ops/ms
Iteration   1: 10.541 ops/ms
Iteration   2: 10.572 ops/ms
Iteration   3: 10.763 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.625 ±(99.9%) 2.196 ops/ms [Average]
  (min, avg, max) = (10.541, 10.625, 10.763), stdev = 0.120
  CI (99.9%): [8.430, 12.821] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:54
# Fork: 1 of 1
# Warmup Iteration   1: 6.170 ops/ms
# Warmup Iteration   2: 9.666 ops/ms
# Warmup Iteration   3: 10.017 ops/ms
Iteration   1: 10.024 ops/ms
Iteration   2: 10.045 ops/ms
Iteration   3: 10.120 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.063 ±(99.9%) 0.927 ops/ms [Average]
  (min, avg, max) = (10.024, 10.063, 10.120), stdev = 0.051
  CI (99.9%): [9.136, 10.990] (assumes normal distribution)


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
# Warmup Iteration   1: 5.102 ops/ms
# Warmup Iteration   2: 7.846 ops/ms
# Warmup Iteration   3: 7.992 ops/ms
Iteration   1: 8.155 ops/ms
Iteration   2: 7.975 ops/ms
Iteration   3: 8.138 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.089 ±(99.9%) 1.815 ops/ms [Average]
  (min, avg, max) = (7.975, 8.089, 8.155), stdev = 0.100
  CI (99.9%): [6.274, 9.904] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 4.733 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.360 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.214 ±(99.9%) 0.002 ms/op
Iteration   1: 3.178 ±(99.9%) 0.012 ms/op
Iteration   2: 3.134 ±(99.9%) 0.003 ms/op
Iteration   3: 3.150 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.154 ±(99.9%) 0.411 ms/op [Average]
  (min, avg, max) = (3.134, 3.154, 3.178), stdev = 0.023
  CI (99.9%): [2.743, 3.565] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.045 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.168 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.989 ±(99.9%) 0.003 ms/op
Iteration   1: 3.006 ±(99.9%) 0.004 ms/op
Iteration   2: 3.047 ±(99.9%) 0.004 ms/op
Iteration   3: 3.027 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.026 ±(99.9%) 0.377 ms/op [Average]
  (min, avg, max) = (3.006, 3.026, 3.047), stdev = 0.021
  CI (99.9%): [2.649, 3.403] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 4.549 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.386 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.225 ±(99.9%) 0.005 ms/op
Iteration   1: 3.179 ±(99.9%) 0.004 ms/op
Iteration   2: 3.105 ±(99.9%) 0.003 ms/op
Iteration   3: 3.157 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.147 ±(99.9%) 0.688 ms/op [Average]
  (min, avg, max) = (3.105, 3.147, 3.179), stdev = 0.038
  CI (99.9%): [2.459, 3.836] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 5.338 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.228 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.979 ±(99.9%) 0.019 ms/op
Iteration   1: 3.997 ±(99.9%) 0.025 ms/op
Iteration   2: 3.907 ±(99.9%) 0.018 ms/op
Iteration   3: 3.912 ±(99.9%) 0.028 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.939 ±(99.9%) 0.920 ms/op [Average]
  (min, avg, max) = (3.907, 3.939, 3.997), stdev = 0.050
  CI (99.9%): [3.019, 4.858] (assumes normal distribution)


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
# Warmup Iteration   1: 4.715 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.402 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.177 ±(99.9%) 0.006 ms/op
Iteration   1: 3.143 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.820 ms/op
                 createUser·p0.50:   3.088 ms/op
                 createUser·p0.90:   3.613 ms/op
                 createUser·p0.95:   3.809 ms/op
                 createUser·p0.99:   4.817 ms/op
                 createUser·p0.999:  9.994 ms/op
                 createUser·p0.9999: 25.062 ms/op
                 createUser·p1.00:   25.592 ms/op

Iteration   2: 3.198 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.620 ms/op
                 createUser·p0.50:   3.125 ms/op
                 createUser·p0.90:   3.797 ms/op
                 createUser·p0.95:   4.014 ms/op
                 createUser·p0.99:   4.956 ms/op
                 createUser·p0.999:  12.189 ms/op
                 createUser·p0.9999: 18.314 ms/op
                 createUser·p1.00:   18.809 ms/op

Iteration   3: 3.157 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.539 ms/op
                 createUser·p0.50:   3.109 ms/op
                 createUser·p0.90:   3.695 ms/op
                 createUser·p0.95:   3.858 ms/op
                 createUser·p0.99:   4.645 ms/op
                 createUser·p0.999:  10.670 ms/op
                 createUser·p0.9999: 20.503 ms/op
                 createUser·p1.00:   20.840 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 303229
  mean =      3.166 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8447 
    [ 2.500,  5.000) = 292184 
    [ 5.000,  7.500) = 1791 
    [ 7.500, 10.000) = 387 
    [10.000, 12.500) = 174 
    [12.500, 15.000) = 49 
    [15.000, 17.500) = 95 
    [17.500, 20.000) = 58 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.539 ms/op
     p(50.0000) =      3.105 ms/op
     p(90.0000) =      3.699 ms/op
     p(95.0000) =      3.903 ms/op
     p(99.0000) =      4.801 ms/op
     p(99.9000) =     11.396 ms/op
     p(99.9900) =     20.830 ms/op
     p(99.9990) =     25.425 ms/op
     p(99.9999) =     25.592 ms/op
    p(100.0000) =     25.592 ms/op


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
# Warmup Iteration   1: 4.241 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.147 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.028 ±(99.9%) 0.006 ms/op
Iteration   1: 3.039 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.440 ms/op
                 existUser·p0.50:   2.998 ms/op
                 existUser·p0.90:   3.564 ms/op
                 existUser·p0.95:   3.703 ms/op
                 existUser·p0.99:   4.448 ms/op
                 existUser·p0.999:  8.656 ms/op
                 existUser·p0.9999: 17.955 ms/op
                 existUser·p1.00:   18.481 ms/op

Iteration   2: 3.038 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.565 ms/op
                 existUser·p0.50:   3.006 ms/op
                 existUser·p0.90:   3.604 ms/op
                 existUser·p0.95:   3.764 ms/op
                 existUser·p0.99:   4.371 ms/op
                 existUser·p0.999:  9.453 ms/op
                 existUser·p0.9999: 22.509 ms/op
                 existUser·p1.00:   22.905 ms/op

Iteration   3: 3.025 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.638 ms/op
                 existUser·p0.50:   3.002 ms/op
                 existUser·p0.90:   3.535 ms/op
                 existUser·p0.95:   3.699 ms/op
                 existUser·p0.99:   4.243 ms/op
                 existUser·p0.999:  7.809 ms/op
                 existUser·p0.9999: 18.822 ms/op
                 existUser·p1.00:   19.268 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 316415
  mean =      3.034 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22876 
    [ 2.500,  5.000) = 291887 
    [ 5.000,  7.500) = 1217 
    [ 7.500, 10.000) = 178 
    [10.000, 12.500) = 57 
    [12.500, 15.000) = 60 
    [15.000, 17.500) = 54 
    [17.500, 20.000) = 54 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.440 ms/op
     p(50.0000) =      3.002 ms/op
     p(90.0000) =      3.568 ms/op
     p(95.0000) =      3.723 ms/op
     p(99.0000) =      4.342 ms/op
     p(99.9000) =      8.431 ms/op
     p(99.9900) =     21.999 ms/op
     p(99.9990) =     22.861 ms/op
     p(99.9999) =     22.905 ms/op
    p(100.0000) =     22.905 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 4.932 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 3.292 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.170 ±(99.9%) 0.008 ms/op
Iteration   1: 3.224 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.899 ms/op
                 getUser·p0.50:   3.162 ms/op
                 getUser·p0.90:   3.838 ms/op
                 getUser·p0.95:   4.026 ms/op
                 getUser·p0.99:   4.940 ms/op
                 getUser·p0.999:  9.771 ms/op
                 getUser·p0.9999: 18.219 ms/op
                 getUser·p1.00:   19.562 ms/op

Iteration   2: 3.047 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.708 ms/op
                 getUser·p0.50:   3.031 ms/op
                 getUser·p0.90:   3.428 ms/op
                 getUser·p0.95:   3.600 ms/op
                 getUser·p0.99:   4.295 ms/op
                 getUser·p0.999:  6.988 ms/op
                 getUser·p0.9999: 16.318 ms/op
                 getUser·p1.00:   18.743 ms/op

Iteration   3: 3.162 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.738 ms/op
                 getUser·p0.50:   3.138 ms/op
                 getUser·p0.90:   3.654 ms/op
                 getUser·p0.95:   3.781 ms/op
                 getUser·p0.99:   4.383 ms/op
                 getUser·p0.999:  7.389 ms/op
                 getUser·p0.9999: 18.252 ms/op
                 getUser·p1.00:   18.874 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 305617
  mean =      3.143 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 293 
    [ 1.250,  2.500) = 8068 
    [ 2.500,  3.750) = 274566 
    [ 3.750,  5.000) = 20720 
    [ 5.000,  6.250) = 1059 
    [ 6.250,  7.500) = 462 
    [ 7.500,  8.750) = 161 
    [ 8.750, 10.000) = 67 
    [10.000, 11.250) = 16 
    [11.250, 12.500) = 27 
    [12.500, 13.750) = 51 
    [13.750, 15.000) = 53 
    [15.000, 16.250) = 25 
    [16.250, 17.500) = 8 
    [17.500, 18.750) = 37 

  Percentiles, ms/op:
      p(0.0000) =      0.708 ms/op
     p(50.0000) =      3.101 ms/op
     p(90.0000) =      3.666 ms/op
     p(95.0000) =      3.871 ms/op
     p(99.0000) =      4.506 ms/op
     p(99.9000) =      8.526 ms/op
     p(99.9900) =     18.219 ms/op
     p(99.9990) =     18.809 ms/op
     p(99.9999) =     19.562 ms/op
    p(100.0000) =     19.562 ms/op


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
# Warmup Iteration   1: 6.131 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 4.175 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.048 ±(99.9%) 0.011 ms/op
Iteration   1: 3.996 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.243 ms/op
                 listUser·p0.50:   3.899 ms/op
                 listUser·p0.90:   4.456 ms/op
                 listUser·p0.95:   5.489 ms/op
                 listUser·p0.99:   6.832 ms/op
                 listUser·p0.999:  13.415 ms/op
                 listUser·p0.9999: 19.332 ms/op
                 listUser·p1.00:   19.792 ms/op

Iteration   2: 4.003 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.133 ms/op
                 listUser·p0.50:   3.871 ms/op
                 listUser·p0.90:   4.694 ms/op
                 listUser·p0.95:   5.480 ms/op
                 listUser·p0.99:   6.767 ms/op
                 listUser·p0.999:  15.204 ms/op
                 listUser·p0.9999: 16.531 ms/op
                 listUser·p1.00:   16.974 ms/op

Iteration   3: 4.019 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.167 ms/op
                 listUser·p0.50:   3.895 ms/op
                 listUser·p0.90:   4.637 ms/op
                 listUser·p0.95:   5.636 ms/op
                 listUser·p0.99:   7.021 ms/op
                 listUser·p0.999:  16.129 ms/op
                 listUser·p0.9999: 24.872 ms/op
                 listUser·p1.00:   31.588 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 239815
  mean =      4.006 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2385 
    [ 2.500,  5.000) = 220740 
    [ 5.000,  7.500) = 15314 
    [ 7.500, 10.000) = 741 
    [10.000, 12.500) = 162 
    [12.500, 15.000) = 214 
    [15.000, 17.500) = 225 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 4 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.133 ms/op
     p(50.0000) =      3.891 ms/op
     p(90.0000) =      4.588 ms/op
     p(95.0000) =      5.530 ms/op
     p(99.0000) =      6.873 ms/op
     p(99.9000) =     15.155 ms/op
     p(99.9900) =     19.399 ms/op
     p(99.9990) =     25.304 ms/op
     p(99.9999) =     31.588 ms/op
    p(100.0000) =     31.588 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.011 ± 1.883  ops/ms
ClientGrpc.existUser                       thrpt       3  10.625 ± 2.196  ops/ms
ClientGrpc.getUser                         thrpt       3  10.063 ± 0.927  ops/ms
ClientGrpc.listUser                        thrpt       3   8.089 ± 1.815  ops/ms
ClientGrpc.createUser                       avgt       3   3.154 ± 0.411   ms/op
ClientGrpc.existUser                        avgt       3   3.026 ± 0.377   ms/op
ClientGrpc.getUser                          avgt       3   3.147 ± 0.688   ms/op
ClientGrpc.listUser                         avgt       3   3.939 ± 0.920   ms/op
ClientGrpc.createUser                     sample  303229   3.166 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.539           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.105           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.699           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.903           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.801           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.396           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.830           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          25.592           ms/op
ClientGrpc.existUser                      sample  316415   3.034 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.440           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.002           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.568           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.723           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.342           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.431           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          21.999           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.905           ms/op
ClientGrpc.getUser                        sample  305617   3.143 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.708           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.101           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.666           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.871           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.506           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.526           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.219           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.562           ms/op
ClientGrpc.listUser                       sample  239815   4.006 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.133           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.891           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.588           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.530           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.873           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.155           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          19.399           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          31.588           ms/op
