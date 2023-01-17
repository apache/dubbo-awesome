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
# Warmup Iteration   1: 3.529 ops/ms
# Warmup Iteration   2: 8.110 ops/ms
# Warmup Iteration   3: 9.886 ops/ms
Iteration   1: 10.249 ops/ms
Iteration   2: 9.987 ops/ms
Iteration   3: 9.909 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.048 ±(99.9%) 3.250 ops/ms [Average]
  (min, avg, max) = (9.909, 10.048, 10.249), stdev = 0.178
  CI (99.9%): [6.798, 13.298] (assumes normal distribution)


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
# Warmup Iteration   1: 6.999 ops/ms
# Warmup Iteration   2: 10.063 ops/ms
# Warmup Iteration   3: 10.508 ops/ms
Iteration   1: 10.328 ops/ms
Iteration   2: 10.400 ops/ms
Iteration   3: 10.397 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.375 ±(99.9%) 0.744 ops/ms [Average]
  (min, avg, max) = (10.328, 10.375, 10.400), stdev = 0.041
  CI (99.9%): [9.631, 11.119] (assumes normal distribution)


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
# Warmup Iteration   1: 6.369 ops/ms
# Warmup Iteration   2: 9.618 ops/ms
# Warmup Iteration   3: 9.926 ops/ms
Iteration   1: 10.008 ops/ms
Iteration   2: 9.995 ops/ms
Iteration   3: 10.092 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.032 ±(99.9%) 0.962 ops/ms [Average]
  (min, avg, max) = (9.995, 10.032, 10.092), stdev = 0.053
  CI (99.9%): [9.070, 10.993] (assumes normal distribution)


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
# Warmup Iteration   1: 4.754 ops/ms
# Warmup Iteration   2: 7.156 ops/ms
# Warmup Iteration   3: 7.535 ops/ms
Iteration   1: 7.541 ops/ms
Iteration   2: 7.610 ops/ms
Iteration   3: 7.721 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.624 ±(99.9%) 1.661 ops/ms [Average]
  (min, avg, max) = (7.541, 7.624, 7.721), stdev = 0.091
  CI (99.9%): [5.963, 9.285] (assumes normal distribution)


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
# Warmup Iteration   1: 4.431 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.308 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.185 ±(99.9%) 0.003 ms/op
Iteration   1: 3.261 ±(99.9%) 0.002 ms/op
Iteration   2: 3.299 ±(99.9%) 0.002 ms/op
Iteration   3: 3.208 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.256 ±(99.9%) 0.831 ms/op [Average]
  (min, avg, max) = (3.208, 3.256, 3.299), stdev = 0.046
  CI (99.9%): [2.425, 4.087] (assumes normal distribution)


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
# Warmup Iteration   1: 4.392 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.270 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.068 ±(99.9%) 0.003 ms/op
Iteration   1: 3.149 ±(99.9%) 0.002 ms/op
Iteration   2: 3.119 ±(99.9%) 0.002 ms/op
Iteration   3: 3.156 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.142 ±(99.9%) 0.358 ms/op [Average]
  (min, avg, max) = (3.119, 3.142, 3.156), stdev = 0.020
  CI (99.9%): [2.783, 3.500] (assumes normal distribution)


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
# Warmup Iteration   1: 4.411 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.353 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.238 ±(99.9%) 0.002 ms/op
Iteration   1: 3.265 ±(99.9%) 0.002 ms/op
Iteration   2: 3.237 ±(99.9%) 0.004 ms/op
Iteration   3: 3.236 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.246 ±(99.9%) 0.303 ms/op [Average]
  (min, avg, max) = (3.236, 3.246, 3.265), stdev = 0.017
  CI (99.9%): [2.943, 3.549] (assumes normal distribution)


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
# Warmup Iteration   1: 6.016 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 4.410 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.172 ±(99.9%) 0.006 ms/op
Iteration   1: 4.154 ±(99.9%) 0.008 ms/op
Iteration   2: 4.086 ±(99.9%) 0.007 ms/op
Iteration   3: 4.207 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.149 ±(99.9%) 1.109 ms/op [Average]
  (min, avg, max) = (4.086, 4.149, 4.207), stdev = 0.061
  CI (99.9%): [3.040, 5.258] (assumes normal distribution)


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
# Warmup Iteration   1: 4.747 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.418 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.183 ±(99.9%) 0.008 ms/op
Iteration   1: 3.227 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.570 ms/op
                 createUser·p0.50:   3.215 ms/op
                 createUser·p0.90:   3.924 ms/op
                 createUser·p0.95:   4.145 ms/op
                 createUser·p0.99:   4.690 ms/op
                 createUser·p0.999:  8.127 ms/op
                 createUser·p0.9999: 19.401 ms/op
                 createUser·p1.00:   20.054 ms/op

Iteration   2: 3.270 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.859 ms/op
                 createUser·p0.50:   3.252 ms/op
                 createUser·p0.90:   3.940 ms/op
                 createUser·p0.95:   4.121 ms/op
                 createUser·p0.99:   4.555 ms/op
                 createUser·p0.999:  7.842 ms/op
                 createUser·p0.9999: 20.520 ms/op
                 createUser·p1.00:   20.840 ms/op

Iteration   3: 3.334 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.796 ms/op
                 createUser·p0.50:   3.305 ms/op
                 createUser·p0.90:   4.080 ms/op
                 createUser·p0.95:   4.276 ms/op
                 createUser·p0.99:   4.686 ms/op
                 createUser·p0.999:  10.961 ms/op
                 createUser·p0.9999: 23.626 ms/op
                 createUser·p1.00:   23.658 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 292832
  mean =      3.277 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16934 
    [ 2.500,  5.000) = 274494 
    [ 5.000,  7.500) = 1032 
    [ 7.500, 10.000) = 125 
    [10.000, 12.500) = 54 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 79 
    [20.000, 22.500) = 45 
    [22.500, 25.000) = 39 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.570 ms/op
     p(50.0000) =      3.256 ms/op
     p(90.0000) =      3.985 ms/op
     p(95.0000) =      4.186 ms/op
     p(99.0000) =      4.645 ms/op
     p(99.9000) =      8.036 ms/op
     p(99.9900) =     23.074 ms/op
     p(99.9990) =     23.658 ms/op
     p(99.9999) =     23.658 ms/op
    p(100.0000) =     23.658 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.469 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.304 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.153 ±(99.9%) 0.007 ms/op
Iteration   1: 3.143 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.902 ms/op
                 existUser·p0.50:   3.129 ms/op
                 existUser·p0.90:   3.838 ms/op
                 existUser·p0.95:   4.002 ms/op
                 existUser·p0.99:   4.375 ms/op
                 existUser·p0.999:  7.000 ms/op
                 existUser·p0.9999: 13.776 ms/op
                 existUser·p1.00:   14.238 ms/op

Iteration   2: 3.104 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.782 ms/op
                 existUser·p0.50:   3.068 ms/op
                 existUser·p0.90:   3.850 ms/op
                 existUser·p0.95:   4.063 ms/op
                 existUser·p0.99:   4.497 ms/op
                 existUser·p0.999:  7.793 ms/op
                 existUser·p0.9999: 15.986 ms/op
                 existUser·p1.00:   16.450 ms/op

Iteration   3: 3.084 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.784 ms/op
                 existUser·p0.50:   3.060 ms/op
                 existUser·p0.90:   3.752 ms/op
                 existUser·p0.95:   3.953 ms/op
                 existUser·p0.99:   4.415 ms/op
                 existUser·p0.999:  9.840 ms/op
                 existUser·p0.9999: 17.596 ms/op
                 existUser·p1.00:   18.022 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 308643
  mean =      3.110 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 985 
    [ 1.250,  2.500) = 31460 
    [ 2.500,  3.750) = 238176 
    [ 3.750,  5.000) = 36959 
    [ 5.000,  6.250) = 504 
    [ 6.250,  7.500) = 145 
    [ 7.500,  8.750) = 135 
    [ 8.750, 10.000) = 87 
    [10.000, 11.250) = 35 
    [11.250, 12.500) = 29 
    [12.500, 13.750) = 21 
    [13.750, 15.000) = 33 
    [15.000, 16.250) = 39 
    [16.250, 17.500) = 22 
    [17.500, 18.750) = 13 

  Percentiles, ms/op:
      p(0.0000) =      0.782 ms/op
     p(50.0000) =      3.084 ms/op
     p(90.0000) =      3.817 ms/op
     p(95.0000) =      4.006 ms/op
     p(99.0000) =      4.424 ms/op
     p(99.9000) =      8.206 ms/op
     p(99.9900) =     17.081 ms/op
     p(99.9990) =     17.888 ms/op
     p(99.9999) =     18.022 ms/op
    p(100.0000) =     18.022 ms/op


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
# Warmup Iteration   1: 4.707 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.429 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.286 ±(99.9%) 0.007 ms/op
Iteration   1: 3.292 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.818 ms/op
                 getUser·p0.50:   3.244 ms/op
                 getUser·p0.90:   3.977 ms/op
                 getUser·p0.95:   4.202 ms/op
                 getUser·p0.99:   4.923 ms/op
                 getUser·p0.999:  9.159 ms/op
                 getUser·p0.9999: 14.366 ms/op
                 getUser·p1.00:   14.942 ms/op

Iteration   2: 3.281 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.950 ms/op
                 getUser·p0.50:   3.252 ms/op
                 getUser·p0.90:   4.014 ms/op
                 getUser·p0.95:   4.243 ms/op
                 getUser·p0.99:   4.702 ms/op
                 getUser·p0.999:  7.466 ms/op
                 getUser·p0.9999: 15.733 ms/op
                 getUser·p1.00:   15.991 ms/op

Iteration   3: 3.283 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.819 ms/op
                 getUser·p0.50:   3.265 ms/op
                 getUser·p0.90:   4.026 ms/op
                 getUser·p0.95:   4.227 ms/op
                 getUser·p0.99:   4.710 ms/op
                 getUser·p0.999:  8.099 ms/op
                 getUser·p0.9999: 19.440 ms/op
                 getUser·p1.00:   19.792 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 292022
  mean =      3.285 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 316 
    [ 1.250,  2.500) = 15184 
    [ 2.500,  3.750) = 219357 
    [ 3.750,  5.000) = 55318 
    [ 5.000,  6.250) = 1087 
    [ 6.250,  7.500) = 366 
    [ 7.500,  8.750) = 126 
    [ 8.750, 10.000) = 57 
    [10.000, 11.250) = 19 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 23 
    [13.750, 15.000) = 37 
    [15.000, 16.250) = 46 
    [16.250, 17.500) = 53 
    [17.500, 18.750) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.818 ms/op
     p(50.0000) =      3.252 ms/op
     p(90.0000) =      4.006 ms/op
     p(95.0000) =      4.227 ms/op
     p(99.0000) =      4.760 ms/op
     p(99.9000) =      8.143 ms/op
     p(99.9900) =     18.428 ms/op
     p(99.9990) =     19.726 ms/op
     p(99.9999) =     19.792 ms/op
    p(100.0000) =     19.792 ms/op


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
# Warmup Iteration   1: 6.664 ±(99.9%) 0.070 ms/op
# Warmup Iteration   2: 4.427 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.180 ±(99.9%) 0.012 ms/op
Iteration   1: 4.241 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.425 ms/op
                 listUser·p0.50:   4.043 ms/op
                 listUser·p0.90:   5.456 ms/op
                 listUser·p0.95:   6.078 ms/op
                 listUser·p0.99:   7.365 ms/op
                 listUser·p0.999:  14.877 ms/op
                 listUser·p0.9999: 16.760 ms/op
                 listUser·p1.00:   18.678 ms/op

Iteration   2: 4.267 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.182 ms/op
                 listUser·p0.50:   4.071 ms/op
                 listUser·p0.90:   5.399 ms/op
                 listUser·p0.95:   6.046 ms/op
                 listUser·p0.99:   7.345 ms/op
                 listUser·p0.999:  16.712 ms/op
                 listUser·p0.9999: 18.252 ms/op
                 listUser·p1.00:   20.513 ms/op

Iteration   3: 4.211 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.274 ms/op
                 listUser·p0.50:   4.035 ms/op
                 listUser·p0.90:   5.366 ms/op
                 listUser·p0.95:   6.021 ms/op
                 listUser·p0.99:   7.258 ms/op
                 listUser·p0.999:  15.974 ms/op
                 listUser·p0.9999: 21.339 ms/op
                 listUser·p1.00:   21.922 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 226278
  mean =      4.240 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1630 
    [ 2.500,  5.000) = 191966 
    [ 5.000,  7.500) = 30870 
    [ 7.500, 10.000) = 1399 
    [10.000, 12.500) = 63 
    [12.500, 15.000) = 62 
    [15.000, 17.500) = 227 
    [17.500, 20.000) = 47 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.182 ms/op
     p(50.0000) =      4.051 ms/op
     p(90.0000) =      5.415 ms/op
     p(95.0000) =      6.046 ms/op
     p(99.0000) =      7.324 ms/op
     p(99.9000) =     16.003 ms/op
     p(99.9900) =     18.657 ms/op
     p(99.9990) =     21.813 ms/op
     p(99.9999) =     21.922 ms/op
    p(100.0000) =     21.922 ms/op


# Run complete. Total time: 00:13:06

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.048 ± 3.250  ops/ms
ClientGrpc.existUser                       thrpt       3  10.375 ± 0.744  ops/ms
ClientGrpc.getUser                         thrpt       3  10.032 ± 0.962  ops/ms
ClientGrpc.listUser                        thrpt       3   7.624 ± 1.661  ops/ms
ClientGrpc.createUser                       avgt       3   3.256 ± 0.831   ms/op
ClientGrpc.existUser                        avgt       3   3.142 ± 0.358   ms/op
ClientGrpc.getUser                          avgt       3   3.246 ± 0.303   ms/op
ClientGrpc.listUser                         avgt       3   4.149 ± 1.109   ms/op
ClientGrpc.createUser                     sample  292832   3.277 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.570           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.256           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.985           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.186           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.645           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.036           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          23.074           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.658           ms/op
ClientGrpc.existUser                      sample  308643   3.110 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.782           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.084           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.817           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.006           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.424           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.206           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.081           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.022           ms/op
ClientGrpc.getUser                        sample  292022   3.285 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.818           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.252           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.006           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.227           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.760           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.143           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.428           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.792           ms/op
ClientGrpc.listUser                       sample  226278   4.240 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.182           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.051           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.415           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.046           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.324           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.003           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          18.657           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          21.922           ms/op
