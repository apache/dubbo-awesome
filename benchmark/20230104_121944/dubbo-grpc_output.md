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
# Warmup Iteration   1: 4.252 ops/ms
# Warmup Iteration   2: 9.150 ops/ms
# Warmup Iteration   3: 10.492 ops/ms
Iteration   1: 10.647 ops/ms
Iteration   2: 10.011 ops/ms
Iteration   3: 10.262 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.307 ±(99.9%) 5.846 ops/ms [Average]
  (min, avg, max) = (10.011, 10.307, 10.647), stdev = 0.320
  CI (99.9%): [4.461, 16.153] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.833 ops/ms
# Warmup Iteration   2: 10.786 ops/ms
# Warmup Iteration   3: 11.143 ops/ms
Iteration   1: 11.065 ops/ms
Iteration   2: 10.758 ops/ms
Iteration   3: 10.710 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.844 ±(99.9%) 3.512 ops/ms [Average]
  (min, avg, max) = (10.710, 10.844, 11.065), stdev = 0.193
  CI (99.9%): [7.332, 14.357] (assumes normal distribution)


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
# Warmup Iteration   1: 7.276 ops/ms
# Warmup Iteration   2: 10.218 ops/ms
# Warmup Iteration   3: 10.558 ops/ms
Iteration   1: 10.440 ops/ms
Iteration   2: 10.656 ops/ms
Iteration   3: 10.376 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.491 ±(99.9%) 2.676 ops/ms [Average]
  (min, avg, max) = (10.376, 10.491, 10.656), stdev = 0.147
  CI (99.9%): [7.815, 13.166] (assumes normal distribution)


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
# Warmup Iteration   1: 6.334 ops/ms
# Warmup Iteration   2: 7.598 ops/ms
# Warmup Iteration   3: 7.861 ops/ms
Iteration   1: 8.061 ops/ms
Iteration   2: 8.085 ops/ms
Iteration   3: 8.231 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.125 ±(99.9%) 1.679 ops/ms [Average]
  (min, avg, max) = (8.061, 8.125, 8.231), stdev = 0.092
  CI (99.9%): [6.447, 9.804] (assumes normal distribution)


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
# Warmup Iteration   1: 4.123 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.106 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.032 ±(99.9%) 0.003 ms/op
Iteration   1: 3.058 ±(99.9%) 0.002 ms/op
Iteration   2: 3.016 ±(99.9%) 0.003 ms/op
Iteration   3: 3.088 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.054 ±(99.9%) 0.661 ms/op [Average]
  (min, avg, max) = (3.016, 3.054, 3.088), stdev = 0.036
  CI (99.9%): [2.393, 3.715] (assumes normal distribution)


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
# Warmup Iteration   1: 3.682 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.015 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.989 ±(99.9%) 0.007 ms/op
Iteration   1: 2.954 ±(99.9%) 0.005 ms/op
Iteration   2: 3.012 ±(99.9%) 0.002 ms/op
Iteration   3: 2.969 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.978 ±(99.9%) 0.551 ms/op [Average]
  (min, avg, max) = (2.954, 2.978, 3.012), stdev = 0.030
  CI (99.9%): [2.427, 3.529] (assumes normal distribution)


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
# Warmup Iteration   1: 3.914 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.127 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.085 ±(99.9%) 0.002 ms/op
Iteration   1: 3.114 ±(99.9%) 0.002 ms/op
Iteration   2: 3.054 ±(99.9%) 0.003 ms/op
Iteration   3: 3.126 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.098 ±(99.9%) 0.698 ms/op [Average]
  (min, avg, max) = (3.054, 3.098, 3.126), stdev = 0.038
  CI (99.9%): [2.400, 3.796] (assumes normal distribution)


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
# Warmup Iteration   1: 5.365 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 4.137 ±(99.9%) 0.034 ms/op
# Warmup Iteration   3: 4.141 ±(99.9%) 0.034 ms/op
Iteration   1: 4.028 ±(99.9%) 0.027 ms/op
Iteration   2: 4.050 ±(99.9%) 0.014 ms/op
Iteration   3: 4.080 ±(99.9%) 0.024 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.053 ±(99.9%) 0.477 ms/op [Average]
  (min, avg, max) = (4.028, 4.053, 4.080), stdev = 0.026
  CI (99.9%): [3.576, 4.530] (assumes normal distribution)


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
# Warmup Iteration   1: 4.108 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.212 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.168 ±(99.9%) 0.007 ms/op
Iteration   1: 3.096 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.786 ms/op
                 createUser·p0.50:   3.084 ms/op
                 createUser·p0.90:   3.576 ms/op
                 createUser·p0.95:   3.752 ms/op
                 createUser·p0.99:   4.243 ms/op
                 createUser·p0.999:  8.075 ms/op
                 createUser·p0.9999: 12.266 ms/op
                 createUser·p1.00:   13.992 ms/op

Iteration   2: 3.018 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.487 ms/op
                 createUser·p0.50:   3.072 ms/op
                 createUser·p0.90:   3.441 ms/op
                 createUser·p0.95:   3.621 ms/op
                 createUser·p0.99:   4.235 ms/op
                 createUser·p0.999:  7.365 ms/op
                 createUser·p0.9999: 13.330 ms/op
                 createUser·p1.00:   13.664 ms/op

Iteration   3: 3.026 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.605 ms/op
                 createUser·p0.50:   3.047 ms/op
                 createUser·p0.90:   3.613 ms/op
                 createUser·p0.95:   3.793 ms/op
                 createUser·p0.99:   4.268 ms/op
                 createUser·p0.999:  13.767 ms/op
                 createUser·p0.9999: 17.442 ms/op
                 createUser·p1.00:   18.219 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 315054
  mean =      3.046 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2792 
    [ 1.250,  2.500) = 22167 
    [ 2.500,  3.750) = 274781 
    [ 3.750,  5.000) = 14302 
    [ 5.000,  6.250) = 383 
    [ 6.250,  7.500) = 174 
    [ 7.500,  8.750) = 64 
    [ 8.750, 10.000) = 28 
    [10.000, 11.250) = 70 
    [11.250, 12.500) = 99 
    [12.500, 13.750) = 86 
    [13.750, 15.000) = 29 
    [15.000, 16.250) = 23 
    [16.250, 17.500) = 47 
    [17.500, 18.750) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.487 ms/op
     p(50.0000) =      3.068 ms/op
     p(90.0000) =      3.547 ms/op
     p(95.0000) =      3.744 ms/op
     p(99.0000) =      4.252 ms/op
     p(99.9000) =     10.994 ms/op
     p(99.9900) =     16.974 ms/op
     p(99.9990) =     17.937 ms/op
     p(99.9999) =     18.219 ms/op
    p(100.0000) =     18.219 ms/op


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
# Warmup Iteration   1: 3.747 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.040 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.941 ±(99.9%) 0.006 ms/op
Iteration   1: 2.927 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.607 ms/op
                 existUser·p0.50:   2.929 ms/op
                 existUser·p0.90:   3.473 ms/op
                 existUser·p0.95:   3.678 ms/op
                 existUser·p0.99:   4.084 ms/op
                 existUser·p0.999:  6.337 ms/op
                 existUser·p0.9999: 21.597 ms/op
                 existUser·p1.00:   22.020 ms/op

Iteration   2: 2.975 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.570 ms/op
                 existUser·p0.50:   2.945 ms/op
                 existUser·p0.90:   3.568 ms/op
                 existUser·p0.95:   3.760 ms/op
                 existUser·p0.99:   4.276 ms/op
                 existUser·p0.999:  9.628 ms/op
                 existUser·p0.9999: 13.276 ms/op
                 existUser·p1.00:   16.433 ms/op

Iteration   3: 3.011 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.738 ms/op
                 existUser·p0.50:   2.990 ms/op
                 existUser·p0.90:   3.674 ms/op
                 existUser·p0.95:   3.850 ms/op
                 existUser·p0.99:   4.243 ms/op
                 existUser·p0.999:  7.423 ms/op
                 existUser·p0.9999: 14.555 ms/op
                 existUser·p1.00:   15.090 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 322804
  mean =      2.971 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 43408 
    [ 2.500,  5.000) = 278278 
    [ 5.000,  7.500) = 705 
    [ 7.500, 10.000) = 212 
    [10.000, 12.500) = 98 
    [12.500, 15.000) = 68 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.570 ms/op
     p(50.0000) =      2.953 ms/op
     p(90.0000) =      3.580 ms/op
     p(95.0000) =      3.777 ms/op
     p(99.0000) =      4.211 ms/op
     p(99.9000) =      8.932 ms/op
     p(99.9900) =     19.486 ms/op
     p(99.9990) =     21.940 ms/op
     p(99.9999) =     22.020 ms/op
    p(100.0000) =     22.020 ms/op


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
# Warmup Iteration   1: 3.891 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.161 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.115 ±(99.9%) 0.007 ms/op
Iteration   1: 3.039 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.286 ms/op
                 getUser·p0.50:   3.039 ms/op
                 getUser·p0.90:   3.502 ms/op
                 getUser·p0.95:   3.723 ms/op
                 getUser·p0.99:   4.301 ms/op
                 getUser·p0.999:  6.613 ms/op
                 getUser·p0.9999: 13.885 ms/op
                 getUser·p1.00:   16.876 ms/op

Iteration   2: 3.057 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.760 ms/op
                 getUser·p0.50:   3.047 ms/op
                 getUser·p0.90:   3.703 ms/op
                 getUser·p0.95:   3.908 ms/op
                 getUser·p0.99:   4.325 ms/op
                 getUser·p0.999:  8.320 ms/op
                 getUser·p0.9999: 19.137 ms/op
                 getUser·p1.00:   19.497 ms/op

Iteration   3: 3.051 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.598 ms/op
                 getUser·p0.50:   3.047 ms/op
                 getUser·p0.90:   3.621 ms/op
                 getUser·p0.95:   3.809 ms/op
                 getUser·p0.99:   4.235 ms/op
                 getUser·p0.999:  6.647 ms/op
                 getUser·p0.9999: 14.427 ms/op
                 getUser·p1.00:   14.696 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 314777
  mean =      3.049 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1458 
    [ 1.250,  2.500) = 24564 
    [ 2.500,  3.750) = 268384 
    [ 3.750,  5.000) = 19356 
    [ 5.000,  6.250) = 511 
    [ 6.250,  7.500) = 247 
    [ 7.500,  8.750) = 64 
    [ 8.750, 10.000) = 32 
    [10.000, 11.250) = 33 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 24 
    [13.750, 15.000) = 38 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 40 

  Percentiles, ms/op:
      p(0.0000) =      0.286 ms/op
     p(50.0000) =      3.043 ms/op
     p(90.0000) =      3.617 ms/op
     p(95.0000) =      3.826 ms/op
     p(99.0000) =      4.293 ms/op
     p(99.9000) =      7.041 ms/op
     p(99.9900) =     18.465 ms/op
     p(99.9990) =     19.384 ms/op
     p(99.9999) =     19.497 ms/op
    p(100.0000) =     19.497 ms/op


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
# Warmup Iteration   1: 4.707 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 4.207 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.064 ±(99.9%) 0.011 ms/op
Iteration   1: 4.010 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.133 ms/op
                 listUser·p0.50:   3.809 ms/op
                 listUser·p0.90:   5.325 ms/op
                 listUser·p0.95:   5.841 ms/op
                 listUser·p0.99:   7.037 ms/op
                 listUser·p0.999:  12.983 ms/op
                 listUser·p0.9999: 18.645 ms/op
                 listUser·p1.00:   21.791 ms/op

Iteration   2: 4.008 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.895 ms/op
                 listUser·p0.50:   3.863 ms/op
                 listUser·p0.90:   4.956 ms/op
                 listUser·p0.95:   5.767 ms/op
                 listUser·p0.99:   6.914 ms/op
                 listUser·p0.999:  15.029 ms/op
                 listUser·p0.9999: 20.709 ms/op
                 listUser·p1.00:   22.348 ms/op

Iteration   3: 4.066 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.774 ms/op
                 listUser·p0.50:   3.867 ms/op
                 listUser·p0.90:   5.202 ms/op
                 listUser·p0.95:   5.620 ms/op
                 listUser·p0.99:   6.816 ms/op
                 listUser·p0.999:  19.333 ms/op
                 listUser·p0.9999: 23.527 ms/op
                 listUser·p1.00:   24.216 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 238229
  mean =      4.028 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3242 
    [ 2.500,  5.000) = 204464 
    [ 5.000,  7.500) = 29107 
    [ 7.500, 10.000) = 889 
    [10.000, 12.500) = 116 
    [12.500, 15.000) = 145 
    [15.000, 17.500) = 86 
    [17.500, 20.000) = 78 
    [20.000, 22.500) = 88 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.774 ms/op
     p(50.0000) =      3.846 ms/op
     p(90.0000) =      5.194 ms/op
     p(95.0000) =      5.743 ms/op
     p(99.0000) =      6.922 ms/op
     p(99.9000) =     15.630 ms/op
     p(99.9900) =     22.282 ms/op
     p(99.9990) =     23.863 ms/op
     p(99.9999) =     24.216 ms/op
    p(100.0000) =     24.216 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.307 ± 5.846  ops/ms
ClientGrpc.existUser                       thrpt       3  10.844 ± 3.512  ops/ms
ClientGrpc.getUser                         thrpt       3  10.491 ± 2.676  ops/ms
ClientGrpc.listUser                        thrpt       3   8.125 ± 1.679  ops/ms
ClientGrpc.createUser                       avgt       3   3.054 ± 0.661   ms/op
ClientGrpc.existUser                        avgt       3   2.978 ± 0.551   ms/op
ClientGrpc.getUser                          avgt       3   3.098 ± 0.698   ms/op
ClientGrpc.listUser                         avgt       3   4.053 ± 0.477   ms/op
ClientGrpc.createUser                     sample  315054   3.046 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.487           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.068           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.547           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.744           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.252           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.994           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          16.974           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          18.219           ms/op
ClientGrpc.existUser                      sample  322804   2.971 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.570           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.953           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.580           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.777           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.211           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.932           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.486           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.020           ms/op
ClientGrpc.getUser                        sample  314777   3.049 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.286           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.043           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.617           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.826           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.293           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.041           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.465           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.497           ms/op
ClientGrpc.listUser                       sample  238229   4.028 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.774           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.846           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.194           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.743           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.922           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.630           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.282           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.216           ms/op
