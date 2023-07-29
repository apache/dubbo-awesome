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
# Warmup Iteration   1: 4.502 ops/ms
# Warmup Iteration   2: 8.952 ops/ms
# Warmup Iteration   3: 10.356 ops/ms
Iteration   1: 10.575 ops/ms
Iteration   2: 10.574 ops/ms
Iteration   3: 10.572 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.574 ±(99.9%) 0.031 ops/ms [Average]
  (min, avg, max) = (10.572, 10.574, 10.575), stdev = 0.002
  CI (99.9%): [10.543, 10.605] (assumes normal distribution)


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
# Warmup Iteration   1: 7.395 ops/ms
# Warmup Iteration   2: 10.664 ops/ms
# Warmup Iteration   3: 11.115 ops/ms
Iteration   1: 11.402 ops/ms
Iteration   2: 11.234 ops/ms
Iteration   3: 10.945 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.193 ±(99.9%) 4.222 ops/ms [Average]
  (min, avg, max) = (10.945, 11.193, 11.402), stdev = 0.231
  CI (99.9%): [6.972, 15.415] (assumes normal distribution)


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
# Warmup Iteration   1: 7.693 ops/ms
# Warmup Iteration   2: 10.494 ops/ms
# Warmup Iteration   3: 10.634 ops/ms
Iteration   1: 10.421 ops/ms
Iteration   2: 10.589 ops/ms
Iteration   3: 10.621 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.544 ±(99.9%) 1.962 ops/ms [Average]
  (min, avg, max) = (10.421, 10.544, 10.621), stdev = 0.108
  CI (99.9%): [8.582, 12.505] (assumes normal distribution)


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
# Warmup Iteration   1: 5.696 ops/ms
# Warmup Iteration   2: 8.167 ops/ms
# Warmup Iteration   3: 8.281 ops/ms
Iteration   1: 8.257 ops/ms
Iteration   2: 8.317 ops/ms
Iteration   3: 8.330 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.301 ±(99.9%) 0.705 ops/ms [Average]
  (min, avg, max) = (8.257, 8.301, 8.330), stdev = 0.039
  CI (99.9%): [7.596, 9.007] (assumes normal distribution)


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
# Warmup Iteration   1: 4.220 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.183 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.053 ±(99.9%) 0.003 ms/op
Iteration   1: 3.016 ±(99.9%) 0.003 ms/op
Iteration   2: 3.002 ±(99.9%) 0.002 ms/op
Iteration   3: 3.008 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.009 ±(99.9%) 0.126 ms/op [Average]
  (min, avg, max) = (3.002, 3.009, 3.016), stdev = 0.007
  CI (99.9%): [2.883, 3.135] (assumes normal distribution)


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
# Warmup Iteration   1: 3.715 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.024 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 2.910 ±(99.9%) 0.003 ms/op
Iteration   1: 2.900 ±(99.9%) 0.003 ms/op
Iteration   2: 2.887 ±(99.9%) 0.003 ms/op
Iteration   3: 2.921 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.903 ±(99.9%) 0.314 ms/op [Average]
  (min, avg, max) = (2.887, 2.903, 2.921), stdev = 0.017
  CI (99.9%): [2.589, 3.217] (assumes normal distribution)


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
# Warmup Iteration   1: 3.951 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.070 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.002 ±(99.9%) 0.002 ms/op
Iteration   1: 2.998 ±(99.9%) 0.003 ms/op
Iteration   2: 2.981 ±(99.9%) 0.004 ms/op
Iteration   3: 3.005 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.995 ±(99.9%) 0.226 ms/op [Average]
  (min, avg, max) = (2.981, 2.995, 3.005), stdev = 0.012
  CI (99.9%): [2.769, 3.220] (assumes normal distribution)


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
# Warmup Iteration   1: 4.928 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.858 ±(99.9%) 0.043 ms/op
# Warmup Iteration   3: 3.830 ±(99.9%) 0.014 ms/op
Iteration   1: 3.877 ±(99.9%) 0.014 ms/op
Iteration   2: 3.878 ±(99.9%) 0.014 ms/op
Iteration   3: 3.842 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.866 ±(99.9%) 0.375 ms/op [Average]
  (min, avg, max) = (3.842, 3.866, 3.878), stdev = 0.021
  CI (99.9%): [3.491, 4.240] (assumes normal distribution)


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
# Warmup Iteration   1: 4.214 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.149 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.990 ±(99.9%) 0.006 ms/op
Iteration   1: 2.995 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.791 ms/op
                 createUser·p0.50:   2.990 ms/op
                 createUser·p0.90:   3.527 ms/op
                 createUser·p0.95:   3.760 ms/op
                 createUser·p0.99:   4.555 ms/op
                 createUser·p0.999:  8.119 ms/op
                 createUser·p0.9999: 10.879 ms/op
                 createUser·p1.00:   11.289 ms/op

Iteration   2: 2.962 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.656 ms/op
                 createUser·p0.50:   2.966 ms/op
                 createUser·p0.90:   3.351 ms/op
                 createUser·p0.95:   3.584 ms/op
                 createUser·p0.99:   4.407 ms/op
                 createUser·p0.999:  5.920 ms/op
                 createUser·p0.9999: 16.390 ms/op
                 createUser·p1.00:   16.810 ms/op

Iteration   3: 3.032 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.643 ms/op
                 createUser·p0.50:   3.002 ms/op
                 createUser·p0.90:   3.559 ms/op
                 createUser·p0.95:   3.748 ms/op
                 createUser·p0.99:   4.375 ms/op
                 createUser·p0.999:  13.288 ms/op
                 createUser·p0.9999: 22.217 ms/op
                 createUser·p1.00:   22.249 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 320564
  mean =      2.996 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26271 
    [ 2.500,  5.000) = 292820 
    [ 5.000,  7.500) = 1083 
    [ 7.500, 10.000) = 107 
    [10.000, 12.500) = 133 
    [12.500, 15.000) = 69 
    [15.000, 17.500) = 49 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.643 ms/op
     p(50.0000) =      2.986 ms/op
     p(90.0000) =      3.490 ms/op
     p(95.0000) =      3.715 ms/op
     p(99.0000) =      4.456 ms/op
     p(99.9000) =      8.773 ms/op
     p(99.9900) =     20.520 ms/op
     p(99.9990) =     22.249 ms/op
     p(99.9999) =     22.249 ms/op
    p(100.0000) =     22.249 ms/op


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
# Warmup Iteration   1: 3.766 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 2.975 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.889 ±(99.9%) 0.006 ms/op
Iteration   1: 2.865 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.523 ms/op
                 existUser·p0.50:   2.875 ms/op
                 existUser·p0.90:   3.363 ms/op
                 existUser·p0.95:   3.592 ms/op
                 existUser·p0.99:   4.342 ms/op
                 existUser·p0.999:  6.226 ms/op
                 existUser·p0.9999: 15.204 ms/op
                 existUser·p1.00:   15.385 ms/op

Iteration   2: 2.866 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.508 ms/op
                 existUser·p0.50:   2.863 ms/op
                 existUser·p0.90:   3.265 ms/op
                 existUser·p0.95:   3.457 ms/op
                 existUser·p0.99:   4.171 ms/op
                 existUser·p0.999:  5.971 ms/op
                 existUser·p0.9999: 12.826 ms/op
                 existUser·p1.00:   12.927 ms/op

Iteration   3: 2.856 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.652 ms/op
                 existUser·p0.50:   2.863 ms/op
                 existUser·p0.90:   3.293 ms/op
                 existUser·p0.95:   3.498 ms/op
                 existUser·p0.99:   4.301 ms/op
                 existUser·p0.999:  9.964 ms/op
                 existUser·p0.9999: 20.408 ms/op
                 existUser·p1.00:   20.808 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 335305
  mean =      2.863 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 44974 
    [ 2.500,  5.000) = 289251 
    [ 5.000,  7.500) = 749 
    [ 7.500, 10.000) = 92 
    [10.000, 12.500) = 112 
    [12.500, 15.000) = 74 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.508 ms/op
     p(50.0000) =      2.867 ms/op
     p(90.0000) =      3.305 ms/op
     p(95.0000) =      3.518 ms/op
     p(99.0000) =      4.260 ms/op
     p(99.9000) =      7.450 ms/op
     p(99.9900) =     15.385 ms/op
     p(99.9990) =     20.653 ms/op
     p(99.9999) =     20.808 ms/op
    p(100.0000) =     20.808 ms/op


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
# Warmup Iteration   1: 3.970 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.101 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.006 ±(99.9%) 0.007 ms/op
Iteration   1: 2.977 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.686 ms/op
                 getUser·p0.50:   2.970 ms/op
                 getUser·p0.90:   3.449 ms/op
                 getUser·p0.95:   3.682 ms/op
                 getUser·p0.99:   4.276 ms/op
                 getUser·p0.999:  8.216 ms/op
                 getUser·p0.9999: 17.670 ms/op
                 getUser·p1.00:   18.645 ms/op

Iteration   2: 2.986 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.751 ms/op
                 getUser·p0.50:   2.978 ms/op
                 getUser·p0.90:   3.465 ms/op
                 getUser·p0.95:   3.600 ms/op
                 getUser·p0.99:   4.350 ms/op
                 getUser·p0.999:  6.660 ms/op
                 getUser·p0.9999: 14.612 ms/op
                 getUser·p1.00:   15.057 ms/op

Iteration   3: 3.014 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.748 ms/op
                 getUser·p0.50:   2.994 ms/op
                 getUser·p0.90:   3.486 ms/op
                 getUser·p0.95:   3.715 ms/op
                 getUser·p0.99:   4.415 ms/op
                 getUser·p0.999:  7.495 ms/op
                 getUser·p0.9999: 15.768 ms/op
                 getUser·p1.00:   16.155 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 320863
  mean =      2.992 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1103 
    [ 1.250,  2.500) = 25944 
    [ 2.500,  3.750) = 281047 
    [ 3.750,  5.000) = 11600 
    [ 5.000,  6.250) = 554 
    [ 6.250,  7.500) = 310 
    [ 7.500,  8.750) = 64 
    [ 8.750, 10.000) = 35 
    [10.000, 11.250) = 21 
    [11.250, 12.500) = 44 
    [12.500, 13.750) = 14 
    [13.750, 15.000) = 73 
    [15.000, 16.250) = 22 
    [16.250, 17.500) = 16 
    [17.500, 18.750) = 16 

  Percentiles, ms/op:
      p(0.0000) =      0.686 ms/op
     p(50.0000) =      2.982 ms/op
     p(90.0000) =      3.465 ms/op
     p(95.0000) =      3.666 ms/op
     p(99.0000) =      4.342 ms/op
     p(99.9000) =      7.381 ms/op
     p(99.9900) =     16.664 ms/op
     p(99.9990) =     18.271 ms/op
     p(99.9999) =     18.645 ms/op
    p(100.0000) =     18.645 ms/op


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
# Warmup Iteration   1: 4.731 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 3.970 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.843 ±(99.9%) 0.010 ms/op
Iteration   1: 3.759 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.120 ms/op
                 listUser·p0.50:   3.641 ms/op
                 listUser·p0.90:   4.596 ms/op
                 listUser·p0.95:   5.460 ms/op
                 listUser·p0.99:   6.693 ms/op
                 listUser·p0.999:  14.235 ms/op
                 listUser·p0.9999: 19.086 ms/op
                 listUser·p1.00:   19.431 ms/op

Iteration   2: 3.783 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.029 ms/op
                 listUser·p0.50:   3.686 ms/op
                 listUser·p0.90:   4.325 ms/op
                 listUser·p0.95:   5.292 ms/op
                 listUser·p0.99:   6.554 ms/op
                 listUser·p0.999:  15.784 ms/op
                 listUser·p0.9999: 25.216 ms/op
                 listUser·p1.00:   25.461 ms/op

Iteration   3: 3.862 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.914 ms/op
                 listUser·p0.50:   3.756 ms/op
                 listUser·p0.90:   4.268 ms/op
                 listUser·p0.95:   5.128 ms/op
                 listUser·p0.99:   6.480 ms/op
                 listUser·p0.999:  14.061 ms/op
                 listUser·p0.9999: 22.331 ms/op
                 listUser·p1.00:   22.741 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 252535
  mean =      3.801 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4424 
    [ 2.500,  5.000) = 232393 
    [ 5.000,  7.500) = 14584 
    [ 7.500, 10.000) = 667 
    [10.000, 12.500) = 76 
    [12.500, 15.000) = 177 
    [15.000, 17.500) = 71 
    [17.500, 20.000) = 62 
    [20.000, 22.500) = 52 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.914 ms/op
     p(50.0000) =      3.699 ms/op
     p(90.0000) =      4.399 ms/op
     p(95.0000) =      5.333 ms/op
     p(99.0000) =      6.570 ms/op
     p(99.9000) =     14.311 ms/op
     p(99.9900) =     22.544 ms/op
     p(99.9990) =     25.411 ms/op
     p(99.9999) =     25.461 ms/op
    p(100.0000) =     25.461 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.574 ± 0.031  ops/ms
ClientGrpc.existUser                       thrpt       3  11.193 ± 4.222  ops/ms
ClientGrpc.getUser                         thrpt       3  10.544 ± 1.962  ops/ms
ClientGrpc.listUser                        thrpt       3   8.301 ± 0.705  ops/ms
ClientGrpc.createUser                       avgt       3   3.009 ± 0.126   ms/op
ClientGrpc.existUser                        avgt       3   2.903 ± 0.314   ms/op
ClientGrpc.getUser                          avgt       3   2.995 ± 0.226   ms/op
ClientGrpc.listUser                         avgt       3   3.866 ± 0.375   ms/op
ClientGrpc.createUser                     sample  320564   2.996 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.643           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.986           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.490           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.715           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.456           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.773           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.520           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.249           ms/op
ClientGrpc.existUser                      sample  335305   2.863 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.508           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.867           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.305           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.518           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.260           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.450           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.385           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.808           ms/op
ClientGrpc.getUser                        sample  320863   2.992 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.686           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.982           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.465           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.666           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.342           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.381           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.664           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.645           ms/op
ClientGrpc.listUser                       sample  252535   3.801 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.914           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.699           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.399           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.333           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.570           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.311           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.544           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.461           ms/op
