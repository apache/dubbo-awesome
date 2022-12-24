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
# Warmup Iteration   1: 3.739 ops/ms
# Warmup Iteration   2: 8.086 ops/ms
# Warmup Iteration   3: 9.747 ops/ms
Iteration   1: 10.094 ops/ms
Iteration   2: 9.888 ops/ms
Iteration   3: 10.007 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.997 ±(99.9%) 1.888 ops/ms [Average]
  (min, avg, max) = (9.888, 9.997, 10.094), stdev = 0.103
  CI (99.9%): [8.109, 11.884] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 7.094 ops/ms
# Warmup Iteration   2: 9.971 ops/ms
# Warmup Iteration   3: 10.505 ops/ms
Iteration   1: 10.538 ops/ms
Iteration   2: 10.366 ops/ms
Iteration   3: 10.349 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.418 ±(99.9%) 1.905 ops/ms [Average]
  (min, avg, max) = (10.349, 10.418, 10.538), stdev = 0.104
  CI (99.9%): [8.513, 12.323] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 6.823 ops/ms
# Warmup Iteration   2: 9.616 ops/ms
# Warmup Iteration   3: 9.968 ops/ms
Iteration   1: 10.080 ops/ms
Iteration   2: 10.276 ops/ms
Iteration   3: 10.107 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.154 ±(99.9%) 1.934 ops/ms [Average]
  (min, avg, max) = (10.080, 10.154, 10.276), stdev = 0.106
  CI (99.9%): [8.221, 12.088] (assumes normal distribution)


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
# Warmup Iteration   1: 5.493 ops/ms
# Warmup Iteration   2: 7.371 ops/ms
# Warmup Iteration   3: 7.635 ops/ms
Iteration   1: 7.675 ops/ms
Iteration   2: 7.674 ops/ms
Iteration   3: 7.861 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.737 ±(99.9%) 1.970 ops/ms [Average]
  (min, avg, max) = (7.674, 7.737, 7.861), stdev = 0.108
  CI (99.9%): [5.767, 9.707] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.494 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.321 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.216 ±(99.9%) 0.002 ms/op
Iteration   1: 3.192 ±(99.9%) 0.003 ms/op
Iteration   2: 3.233 ±(99.9%) 0.002 ms/op
Iteration   3: 3.219 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.215 ±(99.9%) 0.385 ms/op [Average]
  (min, avg, max) = (3.192, 3.215, 3.233), stdev = 0.021
  CI (99.9%): [2.830, 3.600] (assumes normal distribution)


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
# Warmup Iteration   1: 4.009 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.172 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.013 ±(99.9%) 0.003 ms/op
Iteration   1: 3.036 ±(99.9%) 0.004 ms/op
Iteration   2: 3.070 ±(99.9%) 0.003 ms/op
Iteration   3: 3.064 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.057 ±(99.9%) 0.330 ms/op [Average]
  (min, avg, max) = (3.036, 3.057, 3.070), stdev = 0.018
  CI (99.9%): [2.726, 3.387] (assumes normal distribution)


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
# Warmup Iteration   1: 4.293 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.282 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.187 ±(99.9%) 0.003 ms/op
Iteration   1: 3.216 ±(99.9%) 0.002 ms/op
Iteration   2: 3.171 ±(99.9%) 0.002 ms/op
Iteration   3: 3.159 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.182 ±(99.9%) 0.549 ms/op [Average]
  (min, avg, max) = (3.159, 3.182, 3.216), stdev = 0.030
  CI (99.9%): [2.634, 3.731] (assumes normal distribution)


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
# Warmup Iteration   1: 5.643 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.152 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 4.077 ±(99.9%) 0.017 ms/op
Iteration   1: 3.999 ±(99.9%) 0.019 ms/op
Iteration   2: 3.995 ±(99.9%) 0.008 ms/op
Iteration   3: 3.934 ±(99.9%) 0.031 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.976 ±(99.9%) 0.663 ms/op [Average]
  (min, avg, max) = (3.934, 3.976, 3.999), stdev = 0.036
  CI (99.9%): [3.313, 4.639] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.380 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.299 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.246 ±(99.9%) 0.008 ms/op
Iteration   1: 3.263 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.881 ms/op
                 createUser·p0.50:   3.240 ms/op
                 createUser·p0.90:   4.018 ms/op
                 createUser·p0.95:   4.194 ms/op
                 createUser·p0.99:   4.579 ms/op
                 createUser·p0.999:  7.922 ms/op
                 createUser·p0.9999: 15.833 ms/op
                 createUser·p1.00:   16.105 ms/op

Iteration   2: 3.170 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.796 ms/op
                 createUser·p0.50:   3.138 ms/op
                 createUser·p0.90:   3.801 ms/op
                 createUser·p0.95:   4.006 ms/op
                 createUser·p0.99:   4.418 ms/op
                 createUser·p0.999:  7.193 ms/op
                 createUser·p0.9999: 14.285 ms/op
                 createUser·p1.00:   14.778 ms/op

Iteration   3: 3.255 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.254 ms/op
                 createUser·p0.50:   3.203 ms/op
                 createUser·p0.90:   3.940 ms/op
                 createUser·p0.95:   4.137 ms/op
                 createUser·p0.99:   4.489 ms/op
                 createUser·p0.999:  9.691 ms/op
                 createUser·p0.9999: 32.192 ms/op
                 createUser·p1.00:   32.965 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 297497
  mean =      3.229 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15404 
    [ 2.500,  5.000) = 280762 
    [ 5.000,  7.500) = 965 
    [ 7.500, 10.000) = 149 
    [10.000, 12.500) = 62 
    [12.500, 15.000) = 59 
    [15.000, 17.500) = 40 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 24 
    [32.500, 35.000) = 8 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.254 ms/op
     p(50.0000) =      3.187 ms/op
     p(90.0000) =      3.928 ms/op
     p(95.0000) =      4.129 ms/op
     p(99.0000) =      4.506 ms/op
     p(99.9000) =      7.922 ms/op
     p(99.9900) =     30.565 ms/op
     p(99.9990) =     32.901 ms/op
     p(99.9999) =     32.965 ms/op
    p(100.0000) =     32.965 ms/op


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
# Warmup Iteration   1: 3.924 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.159 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.090 ±(99.9%) 0.007 ms/op
Iteration   1: 3.050 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.743 ms/op
                 existUser·p0.50:   3.031 ms/op
                 existUser·p0.90:   3.777 ms/op
                 existUser·p0.95:   3.977 ms/op
                 existUser·p0.99:   4.383 ms/op
                 existUser·p0.999:  6.939 ms/op
                 existUser·p0.9999: 12.902 ms/op
                 existUser·p1.00:   13.189 ms/op

Iteration   2: 3.063 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.708 ms/op
                 existUser·p0.50:   3.039 ms/op
                 existUser·p0.90:   3.744 ms/op
                 existUser·p0.95:   3.949 ms/op
                 existUser·p0.99:   4.309 ms/op
                 existUser·p0.999:  6.714 ms/op
                 existUser·p0.9999: 16.810 ms/op
                 existUser·p1.00:   16.843 ms/op

Iteration   3: 3.067 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.719 ms/op
                 existUser·p0.50:   3.023 ms/op
                 existUser·p0.90:   3.707 ms/op
                 existUser·p0.95:   3.912 ms/op
                 existUser·p0.99:   4.260 ms/op
                 existUser·p0.999:  6.691 ms/op
                 existUser·p0.9999: 16.679 ms/op
                 existUser·p1.00:   17.990 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 313626
  mean =      3.060 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1184 
    [ 1.250,  2.500) = 32739 
    [ 2.500,  3.750) = 248779 
    [ 3.750,  5.000) = 29889 
    [ 5.000,  6.250) = 558 
    [ 6.250,  7.500) = 321 
    [ 7.500,  8.750) = 28 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 9 
    [12.500, 13.750) = 47 
    [13.750, 15.000) = 13 
    [15.000, 16.250) = 19 
    [16.250, 17.500) = 37 
    [17.500, 18.750) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.708 ms/op
     p(50.0000) =      3.031 ms/op
     p(90.0000) =      3.744 ms/op
     p(95.0000) =      3.944 ms/op
     p(99.0000) =      4.325 ms/op
     p(99.9000) =      6.786 ms/op
     p(99.9900) =     16.663 ms/op
     p(99.9990) =     17.474 ms/op
     p(99.9999) =     17.990 ms/op
    p(100.0000) =     17.990 ms/op


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
# Warmup Iteration   1: 4.123 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.195 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.203 ±(99.9%) 0.006 ms/op
Iteration   1: 3.124 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.839 ms/op
                 getUser·p0.50:   3.105 ms/op
                 getUser·p0.90:   3.703 ms/op
                 getUser·p0.95:   3.953 ms/op
                 getUser·p0.99:   4.538 ms/op
                 getUser·p0.999:  7.088 ms/op
                 getUser·p0.9999: 18.596 ms/op
                 getUser·p1.00:   18.940 ms/op

Iteration   2: 3.165 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.858 ms/op
                 getUser·p0.50:   3.150 ms/op
                 getUser·p0.90:   3.789 ms/op
                 getUser·p0.95:   3.965 ms/op
                 getUser·p0.99:   4.301 ms/op
                 getUser·p0.999:  6.996 ms/op
                 getUser·p0.9999: 14.613 ms/op
                 getUser·p1.00:   15.188 ms/op

Iteration   3: 3.158 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.481 ms/op
                 getUser·p0.50:   3.109 ms/op
                 getUser·p0.90:   3.863 ms/op
                 getUser·p0.95:   4.059 ms/op
                 getUser·p0.99:   4.456 ms/op
                 getUser·p0.999:  8.286 ms/op
                 getUser·p0.9999: 16.341 ms/op
                 getUser·p1.00:   17.400 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 304725
  mean =      3.149 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 547 
    [ 1.250,  2.500) = 19748 
    [ 2.500,  3.750) = 249912 
    [ 3.750,  5.000) = 33434 
    [ 5.000,  6.250) = 499 
    [ 6.250,  7.500) = 303 
    [ 7.500,  8.750) = 52 
    [ 8.750, 10.000) = 23 
    [10.000, 11.250) = 23 
    [11.250, 12.500) = 19 
    [12.500, 13.750) = 23 
    [13.750, 15.000) = 56 
    [15.000, 16.250) = 43 
    [16.250, 17.500) = 12 
    [17.500, 18.750) = 26 

  Percentiles, ms/op:
      p(0.0000) =      0.481 ms/op
     p(50.0000) =      3.121 ms/op
     p(90.0000) =      3.793 ms/op
     p(95.0000) =      3.998 ms/op
     p(99.0000) =      4.440 ms/op
     p(99.9000) =      7.397 ms/op
     p(99.9900) =     17.596 ms/op
     p(99.9990) =     18.871 ms/op
     p(99.9999) =     18.940 ms/op
    p(100.0000) =     18.940 ms/op


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
# Warmup Iteration   1: 5.421 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 4.272 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.018 ±(99.9%) 0.011 ms/op
Iteration   1: 4.099 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.270 ms/op
                 listUser·p0.50:   3.936 ms/op
                 listUser·p0.90:   5.104 ms/op
                 listUser·p0.95:   5.988 ms/op
                 listUser·p0.99:   7.135 ms/op
                 listUser·p0.999:  14.974 ms/op
                 listUser·p0.9999: 19.248 ms/op
                 listUser·p1.00:   20.185 ms/op

Iteration   2: 4.135 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.274 ms/op
                 listUser·p0.50:   3.936 ms/op
                 listUser·p0.90:   5.349 ms/op
                 listUser·p0.95:   6.038 ms/op
                 listUser·p0.99:   7.184 ms/op
                 listUser·p0.999:  14.041 ms/op
                 listUser·p0.9999: 16.935 ms/op
                 listUser·p1.00:   18.874 ms/op

Iteration   3: 4.098 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.065 ms/op
                 listUser·p0.50:   3.912 ms/op
                 listUser·p0.90:   5.407 ms/op
                 listUser·p0.95:   6.087 ms/op
                 listUser·p0.99:   7.029 ms/op
                 listUser·p0.999:  17.433 ms/op
                 listUser·p0.9999: 27.040 ms/op
                 listUser·p1.00:   27.558 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 233401
  mean =      4.111 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2823 
    [ 2.500,  5.000) = 201343 
    [ 5.000,  7.500) = 27688 
    [ 7.500, 10.000) = 1089 
    [10.000, 12.500) = 104 
    [12.500, 15.000) = 117 
    [15.000, 17.500) = 130 
    [17.500, 20.000) = 72 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 30 

  Percentiles, ms/op:
      p(0.0000) =      1.065 ms/op
     p(50.0000) =      3.928 ms/op
     p(90.0000) =      5.308 ms/op
     p(95.0000) =      6.038 ms/op
     p(99.0000) =      7.111 ms/op
     p(99.9000) =     15.096 ms/op
     p(99.9900) =     25.482 ms/op
     p(99.9990) =     27.460 ms/op
     p(99.9999) =     27.558 ms/op
    p(100.0000) =     27.558 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.997 ± 1.888  ops/ms
ClientGrpc.existUser                       thrpt       3  10.418 ± 1.905  ops/ms
ClientGrpc.getUser                         thrpt       3  10.154 ± 1.934  ops/ms
ClientGrpc.listUser                        thrpt       3   7.737 ± 1.970  ops/ms
ClientGrpc.createUser                       avgt       3   3.215 ± 0.385   ms/op
ClientGrpc.existUser                        avgt       3   3.057 ± 0.330   ms/op
ClientGrpc.getUser                          avgt       3   3.182 ± 0.549   ms/op
ClientGrpc.listUser                         avgt       3   3.976 ± 0.663   ms/op
ClientGrpc.createUser                     sample  297497   3.229 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.254           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.187           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.928           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.129           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.506           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.922           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          30.565           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          32.965           ms/op
ClientGrpc.existUser                      sample  313626   3.060 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.708           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.031           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.744           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.944           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.325           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.786           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.663           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.990           ms/op
ClientGrpc.getUser                        sample  304725   3.149 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.481           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.121           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.793           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.998           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.440           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.397           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.596           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.940           ms/op
ClientGrpc.listUser                       sample  233401   4.111 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.065           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.928           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.308           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.038           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.111           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.096           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.482           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.558           ms/op
