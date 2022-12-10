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
# Warmup Iteration   1: 4.783 ops/ms
# Warmup Iteration   2: 9.524 ops/ms
# Warmup Iteration   3: 10.443 ops/ms
Iteration   1: 10.262 ops/ms
Iteration   2: 10.259 ops/ms
Iteration   3: 10.076 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.199 ±(99.9%) 1.945 ops/ms [Average]
  (min, avg, max) = (10.076, 10.199, 10.262), stdev = 0.107
  CI (99.9%): [8.254, 12.144] (assumes normal distribution)


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
# Warmup Iteration   1: 7.874 ops/ms
# Warmup Iteration   2: 10.522 ops/ms
# Warmup Iteration   3: 10.723 ops/ms
Iteration   1: 10.803 ops/ms
Iteration   2: 10.926 ops/ms
Iteration   3: 10.708 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.812 ±(99.9%) 1.990 ops/ms [Average]
  (min, avg, max) = (10.708, 10.812, 10.926), stdev = 0.109
  CI (99.9%): [8.822, 12.802] (assumes normal distribution)


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
# Warmup Iteration   1: 7.479 ops/ms
# Warmup Iteration   2: 10.372 ops/ms
# Warmup Iteration   3: 10.285 ops/ms
Iteration   1: 10.356 ops/ms
Iteration   2: 10.653 ops/ms
Iteration   3: 10.347 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.452 ±(99.9%) 3.183 ops/ms [Average]
  (min, avg, max) = (10.347, 10.452, 10.653), stdev = 0.174
  CI (99.9%): [7.269, 13.635] (assumes normal distribution)


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
# Warmup Iteration   1: 6.182 ops/ms
# Warmup Iteration   2: 7.784 ops/ms
# Warmup Iteration   3: 7.941 ops/ms
Iteration   1: 8.044 ops/ms
Iteration   2: 8.122 ops/ms
Iteration   3: 8.042 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.069 ±(99.9%) 0.834 ops/ms [Average]
  (min, avg, max) = (8.042, 8.069, 8.122), stdev = 0.046
  CI (99.9%): [7.236, 8.903] (assumes normal distribution)


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
# Warmup Iteration   1: 3.891 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.121 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.003 ±(99.9%) 0.004 ms/op
Iteration   1: 3.012 ±(99.9%) 0.005 ms/op
Iteration   2: 3.143 ±(99.9%) 0.002 ms/op
Iteration   3: 3.163 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.106 ±(99.9%) 1.495 ms/op [Average]
  (min, avg, max) = (3.012, 3.106, 3.163), stdev = 0.082
  CI (99.9%): [1.611, 4.601] (assumes normal distribution)


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
# Warmup Iteration   1: 3.779 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.986 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.943 ±(99.9%) 0.002 ms/op
Iteration   1: 2.934 ±(99.9%) 0.008 ms/op
Iteration   2: 2.964 ±(99.9%) 0.002 ms/op
Iteration   3: 3.007 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.969 ±(99.9%) 0.668 ms/op [Average]
  (min, avg, max) = (2.934, 2.969, 3.007), stdev = 0.037
  CI (99.9%): [2.300, 3.637] (assumes normal distribution)


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
# Warmup Iteration   1: 3.802 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.152 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.961 ±(99.9%) 0.003 ms/op
Iteration   1: 3.025 ±(99.9%) 0.002 ms/op
Iteration   2: 3.046 ±(99.9%) 0.003 ms/op
Iteration   3: 3.099 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.057 ±(99.9%) 0.695 ms/op [Average]
  (min, avg, max) = (3.025, 3.057, 3.099), stdev = 0.038
  CI (99.9%): [2.362, 3.751] (assumes normal distribution)


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
# Warmup Iteration   1: 4.663 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 4.047 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.128 ±(99.9%) 0.014 ms/op
Iteration   1: 3.970 ±(99.9%) 0.037 ms/op
Iteration   2: 3.917 ±(99.9%) 0.008 ms/op
Iteration   3: 3.987 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.958 ±(99.9%) 0.672 ms/op [Average]
  (min, avg, max) = (3.917, 3.958, 3.987), stdev = 0.037
  CI (99.9%): [3.286, 4.630] (assumes normal distribution)


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
# Warmup Iteration   1: 3.796 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.092 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.991 ±(99.9%) 0.007 ms/op
Iteration   1: 3.137 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.552 ms/op
                 createUser·p0.50:   3.113 ms/op
                 createUser·p0.90:   3.867 ms/op
                 createUser·p0.95:   4.039 ms/op
                 createUser·p0.99:   4.317 ms/op
                 createUser·p0.999:  6.528 ms/op
                 createUser·p0.9999: 12.304 ms/op
                 createUser·p1.00:   12.452 ms/op

Iteration   2: 3.125 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.817 ms/op
                 createUser·p0.50:   3.121 ms/op
                 createUser·p0.90:   3.842 ms/op
                 createUser·p0.95:   4.014 ms/op
                 createUser·p0.99:   4.284 ms/op
                 createUser·p0.999:  6.215 ms/op
                 createUser·p0.9999: 14.418 ms/op
                 createUser·p1.00:   14.713 ms/op

Iteration   3: 3.157 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.721 ms/op
                 createUser·p0.50:   3.129 ms/op
                 createUser·p0.90:   3.858 ms/op
                 createUser·p0.95:   4.030 ms/op
                 createUser·p0.99:   4.317 ms/op
                 createUser·p0.999:  9.432 ms/op
                 createUser·p0.9999: 15.605 ms/op
                 createUser·p1.00:   16.695 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 305677
  mean =      3.140 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 912 
    [ 1.250,  2.500) = 26799 
    [ 2.500,  3.750) = 235444 
    [ 3.750,  5.000) = 41816 
    [ 5.000,  6.250) = 326 
    [ 6.250,  7.500) = 94 
    [ 7.500,  8.750) = 53 
    [ 8.750, 10.000) = 9 
    [10.000, 11.250) = 3 
    [11.250, 12.500) = 72 
    [12.500, 13.750) = 19 
    [13.750, 15.000) = 96 
    [15.000, 16.250) = 31 
    [16.250, 17.500) = 3 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.552 ms/op
     p(50.0000) =      3.121 ms/op
     p(90.0000) =      3.858 ms/op
     p(95.0000) =      4.026 ms/op
     p(99.0000) =      4.309 ms/op
     p(99.9000) =      7.231 ms/op
     p(99.9900) =     15.169 ms/op
     p(99.9990) =     16.362 ms/op
     p(99.9999) =     16.695 ms/op
    p(100.0000) =     16.695 ms/op


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
# Warmup Iteration   1: 3.743 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 2.940 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.906 ±(99.9%) 0.007 ms/op
Iteration   1: 2.962 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.581 ms/op
                 existUser·p0.50:   2.966 ms/op
                 existUser·p0.90:   3.645 ms/op
                 existUser·p0.95:   3.842 ms/op
                 existUser·p0.99:   4.194 ms/op
                 existUser·p0.999:  6.406 ms/op
                 existUser·p0.9999: 22.294 ms/op
                 existUser·p1.00:   22.544 ms/op

Iteration   2: 2.941 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.532 ms/op
                 existUser·p0.50:   2.949 ms/op
                 existUser·p0.90:   3.551 ms/op
                 existUser·p0.95:   3.785 ms/op
                 existUser·p0.99:   4.276 ms/op
                 existUser·p0.999:  6.332 ms/op
                 existUser·p0.9999: 14.270 ms/op
                 existUser·p1.00:   14.500 ms/op

Iteration   3: 3.033 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.648 ms/op
                 existUser·p0.50:   3.031 ms/op
                 existUser·p0.90:   3.662 ms/op
                 existUser·p0.95:   3.801 ms/op
                 existUser·p0.99:   4.104 ms/op
                 existUser·p0.999:  8.994 ms/op
                 existUser·p0.9999: 14.098 ms/op
                 existUser·p1.00:   15.499 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 322683
  mean =      2.978 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 44293 
    [ 2.500,  5.000) = 277564 
    [ 5.000,  7.500) = 519 
    [ 7.500, 10.000) = 111 
    [10.000, 12.500) = 44 
    [12.500, 15.000) = 82 
    [15.000, 17.500) = 6 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.532 ms/op
     p(50.0000) =      2.978 ms/op
     p(90.0000) =      3.629 ms/op
     p(95.0000) =      3.813 ms/op
     p(99.0000) =      4.202 ms/op
     p(99.9000) =      7.406 ms/op
     p(99.9900) =     20.884 ms/op
     p(99.9990) =     22.504 ms/op
     p(99.9999) =     22.544 ms/op
    p(100.0000) =     22.544 ms/op


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
# Warmup Iteration   1: 4.056 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.086 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.041 ±(99.9%) 0.006 ms/op
Iteration   1: 3.051 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.627 ms/op
                 getUser·p0.50:   3.052 ms/op
                 getUser·p0.90:   3.621 ms/op
                 getUser·p0.95:   3.883 ms/op
                 getUser·p0.99:   4.350 ms/op
                 getUser·p0.999:  6.038 ms/op
                 getUser·p0.9999: 11.199 ms/op
                 getUser·p1.00:   11.452 ms/op

Iteration   2: 3.039 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.466 ms/op
                 getUser·p0.50:   3.035 ms/op
                 getUser·p0.90:   3.543 ms/op
                 getUser·p0.95:   3.789 ms/op
                 getUser·p0.99:   4.350 ms/op
                 getUser·p0.999:  7.894 ms/op
                 getUser·p0.9999: 13.770 ms/op
                 getUser·p1.00:   14.041 ms/op

Iteration   3: 2.961 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.298 ms/op
                 getUser·p0.50:   3.015 ms/op
                 getUser·p0.90:   3.502 ms/op
                 getUser·p0.95:   3.748 ms/op
                 getUser·p0.99:   4.276 ms/op
                 getUser·p0.999:  6.414 ms/op
                 getUser·p0.9999: 20.264 ms/op
                 getUser·p1.00:   21.496 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 318284
  mean =      3.016 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27516 
    [ 2.500,  5.000) = 289828 
    [ 5.000,  7.500) = 683 
    [ 7.500, 10.000) = 67 
    [10.000, 12.500) = 73 
    [12.500, 15.000) = 80 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.298 ms/op
     p(50.0000) =      3.031 ms/op
     p(90.0000) =      3.555 ms/op
     p(95.0000) =      3.813 ms/op
     p(99.0000) =      4.325 ms/op
     p(99.9000) =      6.959 ms/op
     p(99.9900) =     19.601 ms/op
     p(99.9990) =     21.392 ms/op
     p(99.9999) =     21.496 ms/op
    p(100.0000) =     21.496 ms/op


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
# Warmup Iteration   1: 4.908 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 4.067 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.084 ±(99.9%) 0.011 ms/op
Iteration   1: 3.985 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.069 ms/op
                 listUser·p0.50:   3.797 ms/op
                 listUser·p0.90:   5.243 ms/op
                 listUser·p0.95:   5.693 ms/op
                 listUser·p0.99:   6.849 ms/op
                 listUser·p0.999:  14.525 ms/op
                 listUser·p0.9999: 19.104 ms/op
                 listUser·p1.00:   19.497 ms/op

Iteration   2: 3.891 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.776 ms/op
                 listUser·p0.50:   3.764 ms/op
                 listUser·p0.90:   4.809 ms/op
                 listUser·p0.95:   5.390 ms/op
                 listUser·p0.99:   6.726 ms/op
                 listUser·p0.999:  14.795 ms/op
                 listUser·p0.9999: 20.342 ms/op
                 listUser·p1.00:   20.840 ms/op

Iteration   3: 3.958 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.896 ms/op
                 listUser·p0.50:   3.772 ms/op
                 listUser·p0.90:   5.226 ms/op
                 listUser·p0.95:   5.792 ms/op
                 listUser·p0.99:   6.676 ms/op
                 listUser·p0.999:  15.044 ms/op
                 listUser·p0.9999: 18.678 ms/op
                 listUser·p1.00:   23.888 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 243234
  mean =      3.944 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5300 
    [ 2.500,  5.000) = 209836 
    [ 5.000,  7.500) = 26997 
    [ 7.500, 10.000) = 615 
    [10.000, 12.500) = 126 
    [12.500, 15.000) = 126 
    [15.000, 17.500) = 85 
    [17.500, 20.000) = 136 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.776 ms/op
     p(50.0000) =      3.777 ms/op
     p(90.0000) =      5.112 ms/op
     p(95.0000) =      5.644 ms/op
     p(99.0000) =      6.750 ms/op
     p(99.9000) =     14.893 ms/op
     p(99.9900) =     19.300 ms/op
     p(99.9990) =     21.944 ms/op
     p(99.9999) =     23.888 ms/op
    p(100.0000) =     23.888 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.199 ± 1.945  ops/ms
ClientGrpc.existUser                       thrpt       3  10.812 ± 1.990  ops/ms
ClientGrpc.getUser                         thrpt       3  10.452 ± 3.183  ops/ms
ClientGrpc.listUser                        thrpt       3   8.069 ± 0.834  ops/ms
ClientGrpc.createUser                       avgt       3   3.106 ± 1.495   ms/op
ClientGrpc.existUser                        avgt       3   2.969 ± 0.668   ms/op
ClientGrpc.getUser                          avgt       3   3.057 ± 0.695   ms/op
ClientGrpc.listUser                         avgt       3   3.958 ± 0.672   ms/op
ClientGrpc.createUser                     sample  305677   3.140 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.552           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.121           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.858           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.026           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.309           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.231           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          15.169           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          16.695           ms/op
ClientGrpc.existUser                      sample  322683   2.978 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.532           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.978           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.629           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.813           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.202           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.406           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.884           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.544           ms/op
ClientGrpc.getUser                        sample  318284   3.016 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.298           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.031           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.555           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.813           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.325           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.959           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.601           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.496           ms/op
ClientGrpc.listUser                       sample  243234   3.944 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.776           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.777           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.112           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.644           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.750           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.893           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          19.300           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.888           ms/op
