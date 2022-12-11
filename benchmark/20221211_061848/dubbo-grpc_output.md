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
# Warmup Iteration   1: 4.210 ops/ms
# Warmup Iteration   2: 8.902 ops/ms
# Warmup Iteration   3: 9.714 ops/ms
Iteration   1: 10.059 ops/ms
Iteration   2: 9.916 ops/ms
Iteration   3: 9.760 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.912 ±(99.9%) 2.726 ops/ms [Average]
  (min, avg, max) = (9.760, 9.912, 10.059), stdev = 0.149
  CI (99.9%): [7.185, 12.638] (assumes normal distribution)


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
# Warmup Iteration   1: 7.294 ops/ms
# Warmup Iteration   2: 10.202 ops/ms
# Warmup Iteration   3: 10.338 ops/ms
Iteration   1: 10.330 ops/ms
Iteration   2: 10.352 ops/ms
Iteration   3: 10.453 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.379 ±(99.9%) 1.191 ops/ms [Average]
  (min, avg, max) = (10.330, 10.379, 10.453), stdev = 0.065
  CI (99.9%): [9.188, 11.569] (assumes normal distribution)


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
# Warmup Iteration   1: 6.991 ops/ms
# Warmup Iteration   2: 9.794 ops/ms
# Warmup Iteration   3: 10.010 ops/ms
Iteration   1: 9.919 ops/ms
Iteration   2: 9.973 ops/ms
Iteration   3: 10.057 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.983 ±(99.9%) 1.265 ops/ms [Average]
  (min, avg, max) = (9.919, 9.983, 10.057), stdev = 0.069
  CI (99.9%): [8.717, 11.248] (assumes normal distribution)


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
# Warmup Iteration   1: 5.581 ops/ms
# Warmup Iteration   2: 7.659 ops/ms
# Warmup Iteration   3: 7.777 ops/ms
Iteration   1: 7.823 ops/ms
Iteration   2: 8.015 ops/ms
Iteration   3: 7.853 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.897 ±(99.9%) 1.889 ops/ms [Average]
  (min, avg, max) = (7.823, 7.897, 8.015), stdev = 0.104
  CI (99.9%): [6.008, 9.785] (assumes normal distribution)


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
# Warmup Iteration   1: 4.689 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.286 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.319 ±(99.9%) 0.002 ms/op
Iteration   1: 3.237 ±(99.9%) 0.010 ms/op
Iteration   2: 3.147 ±(99.9%) 0.002 ms/op
Iteration   3: 3.227 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.204 ±(99.9%) 0.896 ms/op [Average]
  (min, avg, max) = (3.147, 3.204, 3.237), stdev = 0.049
  CI (99.9%): [2.308, 4.100] (assumes normal distribution)


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
# Warmup Iteration   1: 3.833 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.118 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 2.988 ±(99.9%) 0.003 ms/op
Iteration   1: 3.038 ±(99.9%) 0.001 ms/op
Iteration   2: 2.969 ±(99.9%) 0.002 ms/op
Iteration   3: 2.950 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.986 ±(99.9%) 0.843 ms/op [Average]
  (min, avg, max) = (2.950, 2.986, 3.038), stdev = 0.046
  CI (99.9%): [2.143, 3.829] (assumes normal distribution)


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
# Warmup Iteration   1: 4.186 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.197 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.052 ±(99.9%) 0.004 ms/op
Iteration   1: 3.139 ±(99.9%) 0.003 ms/op
Iteration   2: 3.075 ±(99.9%) 0.003 ms/op
Iteration   3: 3.140 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.118 ±(99.9%) 0.675 ms/op [Average]
  (min, avg, max) = (3.075, 3.118, 3.140), stdev = 0.037
  CI (99.9%): [2.443, 3.793] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.336 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.117 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.019 ±(99.9%) 0.006 ms/op
Iteration   1: 3.984 ±(99.9%) 0.012 ms/op
Iteration   2: 3.944 ±(99.9%) 0.007 ms/op
Iteration   3: 4.020 ±(99.9%) 0.048 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.982 ±(99.9%) 0.691 ms/op [Average]
  (min, avg, max) = (3.944, 3.982, 4.020), stdev = 0.038
  CI (99.9%): [3.292, 4.673] (assumes normal distribution)


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
# Warmup Iteration   1: 4.476 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.231 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.149 ±(99.9%) 0.007 ms/op
Iteration   1: 3.165 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.918 ms/op
                 createUser·p0.50:   3.133 ms/op
                 createUser·p0.90:   3.858 ms/op
                 createUser·p0.95:   4.076 ms/op
                 createUser·p0.99:   4.555 ms/op
                 createUser·p0.999:  6.480 ms/op
                 createUser·p0.9999: 13.130 ms/op
                 createUser·p1.00:   13.779 ms/op

Iteration   2: 3.222 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.896 ms/op
                 createUser·p0.50:   3.207 ms/op
                 createUser·p0.90:   3.932 ms/op
                 createUser·p0.95:   4.080 ms/op
                 createUser·p0.99:   4.407 ms/op
                 createUser·p0.999:  8.805 ms/op
                 createUser·p0.9999: 16.744 ms/op
                 createUser·p1.00:   16.974 ms/op

Iteration   3: 3.165 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.814 ms/op
                 createUser·p0.50:   3.138 ms/op
                 createUser·p0.90:   3.822 ms/op
                 createUser·p0.95:   4.010 ms/op
                 createUser·p0.99:   4.399 ms/op
                 createUser·p0.999:  8.634 ms/op
                 createUser·p0.9999: 17.426 ms/op
                 createUser·p1.00:   18.547 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 301570
  mean =      3.184 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 339 
    [ 1.250,  2.500) = 24081 
    [ 2.500,  3.750) = 233445 
    [ 3.750,  5.000) = 42440 
    [ 5.000,  6.250) = 629 
    [ 6.250,  7.500) = 285 
    [ 7.500,  8.750) = 127 
    [ 8.750, 10.000) = 62 
    [10.000, 11.250) = 2 
    [11.250, 12.500) = 5 
    [12.500, 13.750) = 34 
    [13.750, 15.000) = 37 
    [15.000, 16.250) = 30 
    [16.250, 17.500) = 46 
    [17.500, 18.750) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.814 ms/op
     p(50.0000) =      3.158 ms/op
     p(90.0000) =      3.879 ms/op
     p(95.0000) =      4.059 ms/op
     p(99.0000) =      4.448 ms/op
     p(99.9000) =      7.937 ms/op
     p(99.9900) =     16.758 ms/op
     p(99.9990) =     18.153 ms/op
     p(99.9999) =     18.547 ms/op
    p(100.0000) =     18.547 ms/op


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
# Warmup Iteration   1: 3.863 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.148 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.107 ±(99.9%) 0.006 ms/op
Iteration   1: 3.040 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.850 ms/op
                 existUser·p0.50:   3.019 ms/op
                 existUser·p0.90:   3.662 ms/op
                 existUser·p0.95:   3.838 ms/op
                 existUser·p0.99:   4.219 ms/op
                 existUser·p0.999:  6.789 ms/op
                 existUser·p0.9999: 12.993 ms/op
                 existUser·p1.00:   14.565 ms/op

Iteration   2: 2.993 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.811 ms/op
                 existUser·p0.50:   2.982 ms/op
                 existUser·p0.90:   3.592 ms/op
                 existUser·p0.95:   3.789 ms/op
                 existUser·p0.99:   4.260 ms/op
                 existUser·p0.999:  7.668 ms/op
                 existUser·p0.9999: 14.138 ms/op
                 existUser·p1.00:   16.089 ms/op

Iteration   3: 3.009 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.671 ms/op
                 existUser·p0.50:   3.002 ms/op
                 existUser·p0.90:   3.715 ms/op
                 existUser·p0.95:   3.920 ms/op
                 existUser·p0.99:   4.252 ms/op
                 existUser·p0.999:  7.171 ms/op
                 existUser·p0.9999: 15.069 ms/op
                 existUser·p1.00:   16.105 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 318487
  mean =      3.014 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1317 
    [ 1.250,  2.500) = 40071 
    [ 2.500,  3.750) = 253830 
    [ 3.750,  5.000) = 22296 
    [ 5.000,  6.250) = 456 
    [ 6.250,  7.500) = 243 
    [ 7.500,  8.750) = 70 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 17 
    [11.250, 12.500) = 38 
    [12.500, 13.750) = 99 
    [13.750, 15.000) = 27 
    [15.000, 16.250) = 23 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.671 ms/op
     p(50.0000) =      2.998 ms/op
     p(90.0000) =      3.654 ms/op
     p(95.0000) =      3.850 ms/op
     p(99.0000) =      4.243 ms/op
     p(99.9000) =      7.234 ms/op
     p(99.9900) =     14.737 ms/op
     p(99.9990) =     16.065 ms/op
     p(99.9999) =     16.105 ms/op
    p(100.0000) =     16.105 ms/op


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
# Warmup Iteration   1: 4.300 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.224 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.149 ±(99.9%) 0.006 ms/op
Iteration   1: 3.148 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.714 ms/op
                 getUser·p0.50:   3.117 ms/op
                 getUser·p0.90:   3.871 ms/op
                 getUser·p0.95:   4.055 ms/op
                 getUser·p0.99:   4.547 ms/op
                 getUser·p0.999:  8.488 ms/op
                 getUser·p0.9999: 13.659 ms/op
                 getUser·p1.00:   13.861 ms/op

Iteration   2: 3.150 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.830 ms/op
                 getUser·p0.50:   3.109 ms/op
                 getUser·p0.90:   3.838 ms/op
                 getUser·p0.95:   4.018 ms/op
                 getUser·p0.99:   4.407 ms/op
                 getUser·p0.999:  7.618 ms/op
                 getUser·p0.9999: 15.937 ms/op
                 getUser·p1.00:   16.433 ms/op

Iteration   3: 3.095 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.518 ms/op
                 getUser·p0.50:   3.072 ms/op
                 getUser·p0.90:   3.654 ms/op
                 getUser·p0.95:   3.854 ms/op
                 getUser·p0.99:   4.268 ms/op
                 getUser·p0.999:  7.993 ms/op
                 getUser·p0.9999: 21.561 ms/op
                 getUser·p1.00:   22.839 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 306486
  mean =      3.131 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24883 
    [ 2.500,  5.000) = 280277 
    [ 5.000,  7.500) = 913 
    [ 7.500, 10.000) = 197 
    [10.000, 12.500) = 29 
    [12.500, 15.000) = 93 
    [15.000, 17.500) = 56 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.518 ms/op
     p(50.0000) =      3.097 ms/op
     p(90.0000) =      3.793 ms/op
     p(95.0000) =      3.994 ms/op
     p(99.0000) =      4.424 ms/op
     p(99.9000) =      8.151 ms/op
     p(99.9900) =     20.623 ms/op
     p(99.9990) =     21.625 ms/op
     p(99.9999) =     22.839 ms/op
    p(100.0000) =     22.839 ms/op


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
# Warmup Iteration   1: 5.643 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 4.038 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.018 ±(99.9%) 0.011 ms/op
Iteration   1: 3.925 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.327 ms/op
                 listUser·p0.50:   3.764 ms/op
                 listUser·p0.90:   5.046 ms/op
                 listUser·p0.95:   5.751 ms/op
                 listUser·p0.99:   7.060 ms/op
                 listUser·p0.999:  15.204 ms/op
                 listUser·p0.9999: 18.438 ms/op
                 listUser·p1.00:   18.874 ms/op

Iteration   2: 3.987 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.114 ms/op
                 listUser·p0.50:   3.801 ms/op
                 listUser·p0.90:   5.194 ms/op
                 listUser·p0.95:   5.800 ms/op
                 listUser·p0.99:   6.934 ms/op
                 listUser·p0.999:  16.569 ms/op
                 listUser·p0.9999: 26.922 ms/op
                 listUser·p1.00:   27.394 ms/op

Iteration   3: 3.923 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.779 ms/op
                 listUser·p0.50:   3.781 ms/op
                 listUser·p0.90:   4.751 ms/op
                 listUser·p0.95:   5.448 ms/op
                 listUser·p0.99:   6.783 ms/op
                 listUser·p0.999:  19.449 ms/op
                 listUser·p0.9999: 26.062 ms/op
                 listUser·p1.00:   26.804 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 243343
  mean =      3.945 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2877 
    [ 2.500,  5.000) = 215773 
    [ 5.000,  7.500) = 23382 
    [ 7.500, 10.000) = 803 
    [10.000, 12.500) = 118 
    [12.500, 15.000) = 65 
    [15.000, 17.500) = 118 
    [17.500, 20.000) = 67 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 69 
    [25.000, 27.500) = 47 

  Percentiles, ms/op:
      p(0.0000) =      0.779 ms/op
     p(50.0000) =      3.781 ms/op
     p(90.0000) =      5.014 ms/op
     p(95.0000) =      5.693 ms/op
     p(99.0000) =      6.922 ms/op
     p(99.9000) =     16.477 ms/op
     p(99.9900) =     25.493 ms/op
     p(99.9990) =     27.347 ms/op
     p(99.9999) =     27.394 ms/op
    p(100.0000) =     27.394 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.912 ± 2.726  ops/ms
ClientGrpc.existUser                       thrpt       3  10.379 ± 1.191  ops/ms
ClientGrpc.getUser                         thrpt       3   9.983 ± 1.265  ops/ms
ClientGrpc.listUser                        thrpt       3   7.897 ± 1.889  ops/ms
ClientGrpc.createUser                       avgt       3   3.204 ± 0.896   ms/op
ClientGrpc.existUser                        avgt       3   2.986 ± 0.843   ms/op
ClientGrpc.getUser                          avgt       3   3.118 ± 0.675   ms/op
ClientGrpc.listUser                         avgt       3   3.982 ± 0.691   ms/op
ClientGrpc.createUser                     sample  301570   3.184 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.814           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.158           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.879           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.059           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.448           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.937           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          16.758           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          18.547           ms/op
ClientGrpc.existUser                      sample  318487   3.014 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.671           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.998           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.654           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.850           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.243           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.234           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.737           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          16.105           ms/op
ClientGrpc.getUser                        sample  306486   3.131 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.518           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.097           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.793           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.994           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.424           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.151           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.623           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.839           ms/op
ClientGrpc.listUser                       sample  243343   3.945 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.779           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.781           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.014           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.693           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.922           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.477           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.493           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.394           ms/op
