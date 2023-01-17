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
# Warmup Iteration   1: 5.150 ops/ms
# Warmup Iteration   2: 9.493 ops/ms
# Warmup Iteration   3: 10.097 ops/ms
Iteration   1: 10.667 ops/ms
Iteration   2: 10.597 ops/ms
Iteration   3: 9.997 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.420 ±(99.9%) 6.721 ops/ms [Average]
  (min, avg, max) = (9.997, 10.420, 10.667), stdev = 0.368
  CI (99.9%): [3.699, 17.142] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 8.396 ops/ms
# Warmup Iteration   2: 10.794 ops/ms
# Warmup Iteration   3: 10.875 ops/ms
Iteration   1: 11.163 ops/ms
Iteration   2: 10.895 ops/ms
Iteration   3: 10.707 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.922 ±(99.9%) 4.181 ops/ms [Average]
  (min, avg, max) = (10.707, 10.922, 11.163), stdev = 0.229
  CI (99.9%): [6.740, 15.103] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.461 ops/ms
# Warmup Iteration   2: 10.549 ops/ms
# Warmup Iteration   3: 10.394 ops/ms
Iteration   1: 10.710 ops/ms
Iteration   2: 10.770 ops/ms
Iteration   3: 10.791 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.757 ±(99.9%) 0.771 ops/ms [Average]
  (min, avg, max) = (10.710, 10.757, 10.791), stdev = 0.042
  CI (99.9%): [9.987, 11.528] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.237 ops/ms
# Warmup Iteration   2: 7.782 ops/ms
# Warmup Iteration   3: 7.949 ops/ms
Iteration   1: 7.918 ops/ms
Iteration   2: 8.167 ops/ms
Iteration   3: 7.869 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.985 ±(99.9%) 2.914 ops/ms [Average]
  (min, avg, max) = (7.869, 7.985, 8.167), stdev = 0.160
  CI (99.9%): [5.071, 10.898] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 3.910 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.103 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.035 ±(99.9%) 0.003 ms/op
Iteration   1: 3.169 ±(99.9%) 0.002 ms/op
Iteration   2: 3.151 ±(99.9%) 0.001 ms/op
Iteration   3: 3.087 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.135 ±(99.9%) 0.784 ms/op [Average]
  (min, avg, max) = (3.087, 3.135, 3.169), stdev = 0.043
  CI (99.9%): [2.352, 3.919] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.782 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.006 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.976 ±(99.9%) 0.004 ms/op
Iteration   1: 2.913 ±(99.9%) 0.003 ms/op
Iteration   2: 2.959 ±(99.9%) 0.002 ms/op
Iteration   3: 2.869 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.914 ±(99.9%) 0.819 ms/op [Average]
  (min, avg, max) = (2.869, 2.914, 2.959), stdev = 0.045
  CI (99.9%): [2.095, 3.733] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 4.021 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.111 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.051 ±(99.9%) 0.003 ms/op
Iteration   1: 3.115 ±(99.9%) 0.002 ms/op
Iteration   2: 2.962 ±(99.9%) 0.002 ms/op
Iteration   3: 3.055 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.044 ±(99.9%) 1.410 ms/op [Average]
  (min, avg, max) = (2.962, 3.044, 3.115), stdev = 0.077
  CI (99.9%): [1.634, 4.454] (assumes normal distribution)


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
# Warmup Iteration   1: 4.525 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.071 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.941 ±(99.9%) 0.009 ms/op
Iteration   1: 3.964 ±(99.9%) 0.010 ms/op
Iteration   2: 3.862 ±(99.9%) 0.007 ms/op
Iteration   3: 3.896 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.907 ±(99.9%) 0.942 ms/op [Average]
  (min, avg, max) = (3.862, 3.907, 3.964), stdev = 0.052
  CI (99.9%): [2.965, 4.849] (assumes normal distribution)


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
# Warmup Iteration   1: 3.919 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.150 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.040 ±(99.9%) 0.007 ms/op
Iteration   1: 2.970 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.564 ms/op
                 createUser·p0.50:   3.015 ms/op
                 createUser·p0.90:   3.379 ms/op
                 createUser·p0.95:   3.547 ms/op
                 createUser·p0.99:   4.407 ms/op
                 createUser·p0.999:  7.389 ms/op
                 createUser·p0.9999: 20.152 ms/op
                 createUser·p1.00:   21.004 ms/op

Iteration   2: 3.159 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.687 ms/op
                 createUser·p0.50:   3.113 ms/op
                 createUser·p0.90:   3.822 ms/op
                 createUser·p0.95:   3.961 ms/op
                 createUser·p0.99:   4.407 ms/op
                 createUser·p0.999:  8.946 ms/op
                 createUser·p0.9999: 45.474 ms/op
                 createUser·p1.00:   47.317 ms/op

Iteration   3: 3.165 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.642 ms/op
                 createUser·p0.50:   3.142 ms/op
                 createUser·p0.90:   3.846 ms/op
                 createUser·p0.95:   3.981 ms/op
                 createUser·p0.99:   4.243 ms/op
                 createUser·p0.999:  7.086 ms/op
                 createUser·p0.9999: 25.494 ms/op
                 createUser·p1.00:   26.051 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 310315
  mean =      3.095 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 309172 
    [ 5.000, 10.000) = 942 
    [10.000, 15.000) = 9 
    [15.000, 20.000) = 49 
    [20.000, 25.000) = 91 
    [25.000, 30.000) = 20 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 11 

  Percentiles, ms/op:
      p(0.0000) =      0.564 ms/op
     p(50.0000) =      3.060 ms/op
     p(90.0000) =      3.748 ms/op
     p(95.0000) =      3.928 ms/op
     p(99.0000) =      4.334 ms/op
     p(99.9000) =      8.547 ms/op
     p(99.9900) =     44.564 ms/op
     p(99.9990) =     47.186 ms/op
     p(99.9999) =     47.317 ms/op
    p(100.0000) =     47.317 ms/op


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
# Warmup Iteration   1: 3.579 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.006 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.897 ±(99.9%) 0.006 ms/op
Iteration   1: 3.006 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.797 ms/op
                 existUser·p0.50:   2.990 ms/op
                 existUser·p0.90:   3.690 ms/op
                 existUser·p0.95:   3.871 ms/op
                 existUser·p0.99:   4.227 ms/op
                 existUser·p0.999:  6.189 ms/op
                 existUser·p0.9999: 11.759 ms/op
                 existUser·p1.00:   12.173 ms/op

Iteration   2: 2.931 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.498 ms/op
                 existUser·p0.50:   2.949 ms/op
                 existUser·p0.90:   3.564 ms/op
                 existUser·p0.95:   3.756 ms/op
                 existUser·p0.99:   4.167 ms/op
                 existUser·p0.999:  7.110 ms/op
                 existUser·p0.9999: 14.848 ms/op
                 existUser·p1.00:   15.352 ms/op

Iteration   3: 2.975 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.366 ms/op
                 existUser·p0.50:   2.941 ms/op
                 existUser·p0.90:   3.596 ms/op
                 existUser·p0.95:   3.809 ms/op
                 existUser·p0.99:   4.149 ms/op
                 existUser·p0.999:  9.716 ms/op
                 existUser·p0.9999: 22.806 ms/op
                 existUser·p1.00:   24.084 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 323259
  mean =      2.970 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 47011 
    [ 2.500,  5.000) = 275369 
    [ 5.000,  7.500) = 570 
    [ 7.500, 10.000) = 100 
    [10.000, 12.500) = 81 
    [12.500, 15.000) = 57 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.366 ms/op
     p(50.0000) =      2.957 ms/op
     p(90.0000) =      3.625 ms/op
     p(95.0000) =      3.817 ms/op
     p(99.0000) =      4.194 ms/op
     p(99.9000) =      7.209 ms/op
     p(99.9900) =     20.839 ms/op
     p(99.9990) =     23.815 ms/op
     p(99.9999) =     24.084 ms/op
    p(100.0000) =     24.084 ms/op


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
# Warmup Iteration   1: 3.943 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.141 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.057 ±(99.9%) 0.006 ms/op
Iteration   1: 3.035 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.702 ms/op
                 getUser·p0.50:   3.031 ms/op
                 getUser·p0.90:   3.604 ms/op
                 getUser·p0.95:   3.772 ms/op
                 getUser·p0.99:   4.178 ms/op
                 getUser·p0.999:  8.164 ms/op
                 getUser·p0.9999: 12.746 ms/op
                 getUser·p1.00:   12.993 ms/op

Iteration   2: 2.919 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.247 ms/op
                 getUser·p0.50:   2.994 ms/op
                 getUser·p0.90:   3.359 ms/op
                 getUser·p0.95:   3.490 ms/op
                 getUser·p0.99:   4.125 ms/op
                 getUser·p0.999:  6.472 ms/op
                 getUser·p0.9999: 12.420 ms/op
                 getUser·p1.00:   13.697 ms/op

Iteration   3: 3.045 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.780 ms/op
                 getUser·p0.50:   3.035 ms/op
                 getUser·p0.90:   3.686 ms/op
                 getUser·p0.95:   3.858 ms/op
                 getUser·p0.99:   4.265 ms/op
                 getUser·p0.999:  6.897 ms/op
                 getUser·p0.9999: 17.137 ms/op
                 getUser·p1.00:   17.596 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 320019
  mean =      2.999 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2546 
    [ 1.250,  2.500) = 29544 
    [ 2.500,  3.750) = 271268 
    [ 3.750,  5.000) = 15839 
    [ 5.000,  6.250) = 391 
    [ 6.250,  7.500) = 137 
    [ 7.500,  8.750) = 38 
    [ 8.750, 10.000) = 32 
    [10.000, 11.250) = 40 
    [11.250, 12.500) = 93 
    [12.500, 13.750) = 41 
    [13.750, 15.000) = 18 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 30 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.247 ms/op
     p(50.0000) =      3.015 ms/op
     p(90.0000) =      3.559 ms/op
     p(95.0000) =      3.760 ms/op
     p(99.0000) =      4.202 ms/op
     p(99.9000) =      7.069 ms/op
     p(99.9900) =     15.971 ms/op
     p(99.9990) =     17.367 ms/op
     p(99.9999) =     17.596 ms/op
    p(100.0000) =     17.596 ms/op


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
# Warmup Iteration   1: 5.020 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.072 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.051 ±(99.9%) 0.011 ms/op
Iteration   1: 3.960 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.362 ms/op
                 listUser·p0.50:   3.809 ms/op
                 listUser·p0.90:   4.891 ms/op
                 listUser·p0.95:   5.603 ms/op
                 listUser·p0.99:   6.898 ms/op
                 listUser·p0.999:  14.731 ms/op
                 listUser·p0.9999: 17.725 ms/op
                 listUser·p1.00:   18.121 ms/op

Iteration   2: 3.879 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.907 ms/op
                 listUser·p0.50:   3.764 ms/op
                 listUser·p0.90:   4.620 ms/op
                 listUser·p0.95:   5.374 ms/op
                 listUser·p0.99:   6.480 ms/op
                 listUser·p0.999:  14.147 ms/op
                 listUser·p0.9999: 21.881 ms/op
                 listUser·p1.00:   22.315 ms/op

Iteration   3: 4.126 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.239 ms/op
                 listUser·p0.50:   3.883 ms/op
                 listUser·p0.90:   5.300 ms/op
                 listUser·p0.95:   5.571 ms/op
                 listUser·p0.99:   7.037 ms/op
                 listUser·p0.999:  14.541 ms/op
                 listUser·p0.9999: 17.891 ms/op
                 listUser·p1.00:   18.383 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 240823
  mean =      3.986 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3451 
    [ 2.500,  5.000) = 209740 
    [ 5.000,  7.500) = 26427 
    [ 7.500, 10.000) = 650 
    [10.000, 12.500) = 183 
    [12.500, 15.000) = 161 
    [15.000, 17.500) = 122 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 61 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.907 ms/op
     p(50.0000) =      3.805 ms/op
     p(90.0000) =      5.087 ms/op
     p(95.0000) =      5.538 ms/op
     p(99.0000) =      6.767 ms/op
     p(99.9000) =     14.352 ms/op
     p(99.9900) =     20.808 ms/op
     p(99.9990) =     22.184 ms/op
     p(99.9999) =     22.315 ms/op
    p(100.0000) =     22.315 ms/op


# Run complete. Total time: 00:13:02

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.420 ± 6.721  ops/ms
ClientGrpc.existUser                       thrpt       3  10.922 ± 4.181  ops/ms
ClientGrpc.getUser                         thrpt       3  10.757 ± 0.771  ops/ms
ClientGrpc.listUser                        thrpt       3   7.985 ± 2.914  ops/ms
ClientGrpc.createUser                       avgt       3   3.135 ± 0.784   ms/op
ClientGrpc.existUser                        avgt       3   2.914 ± 0.819   ms/op
ClientGrpc.getUser                          avgt       3   3.044 ± 1.410   ms/op
ClientGrpc.listUser                         avgt       3   3.907 ± 0.942   ms/op
ClientGrpc.createUser                     sample  310315   3.095 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.564           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.060           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.748           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.928           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.334           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.547           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          44.564           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          47.317           ms/op
ClientGrpc.existUser                      sample  323259   2.970 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.366           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.957           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.625           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.817           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.194           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.209           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.839           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          24.084           ms/op
ClientGrpc.getUser                        sample  320019   2.999 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.247           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.015           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.559           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.760           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.202           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.069           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          15.971           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          17.596           ms/op
ClientGrpc.listUser                       sample  240823   3.986 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.907           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.805           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.087           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.538           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.767           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.352           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          20.808           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          22.315           ms/op
