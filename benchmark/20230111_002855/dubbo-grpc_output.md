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
# Warmup Iteration   1: 2.823 ops/ms
# Warmup Iteration   2: 6.454 ops/ms
# Warmup Iteration   3: 7.766 ops/ms
Iteration   1: 7.900 ops/ms
Iteration   2: 7.910 ops/ms
Iteration   3: 7.891 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.900 ±(99.9%) 0.180 ops/ms [Average]
  (min, avg, max) = (7.891, 7.900, 7.910), stdev = 0.010
  CI (99.9%): [7.721, 8.080] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:04
# Fork: 1 of 1
# Warmup Iteration   1: 5.837 ops/ms
# Warmup Iteration   2: 7.951 ops/ms
# Warmup Iteration   3: 8.246 ops/ms
Iteration   1: 8.224 ops/ms
Iteration   2: 8.522 ops/ms
Iteration   3: 8.304 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.350 ±(99.9%) 2.818 ops/ms [Average]
  (min, avg, max) = (8.224, 8.350, 8.522), stdev = 0.154
  CI (99.9%): [5.532, 11.168] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 4.788 ops/ms
# Warmup Iteration   2: 7.639 ops/ms
# Warmup Iteration   3: 7.919 ops/ms
Iteration   1: 7.796 ops/ms
Iteration   2: 7.773 ops/ms
Iteration   3: 7.783 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.784 ±(99.9%) 0.204 ops/ms [Average]
  (min, avg, max) = (7.773, 7.784, 7.796), stdev = 0.011
  CI (99.9%): [7.580, 7.988] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 4.284 ops/ms
# Warmup Iteration   2: 5.835 ops/ms
# Warmup Iteration   3: 6.290 ops/ms
Iteration   1: 6.363 ops/ms
Iteration   2: 6.569 ops/ms
Iteration   3: 6.423 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.452 ±(99.9%) 1.936 ops/ms [Average]
  (min, avg, max) = (6.363, 6.452, 6.569), stdev = 0.106
  CI (99.9%): [4.516, 8.387] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 5.534 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.196 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 4.091 ±(99.9%) 0.016 ms/op
Iteration   1: 4.038 ±(99.9%) 0.004 ms/op
Iteration   2: 4.018 ±(99.9%) 0.003 ms/op
Iteration   3: 4.113 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.056 ±(99.9%) 0.909 ms/op [Average]
  (min, avg, max) = (4.018, 4.056, 4.113), stdev = 0.050
  CI (99.9%): [3.148, 4.965] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 5.221 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 4.027 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.919 ±(99.9%) 0.004 ms/op
Iteration   1: 3.862 ±(99.9%) 0.004 ms/op
Iteration   2: 3.655 ±(99.9%) 0.003 ms/op
Iteration   3: 3.762 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.760 ±(99.9%) 1.893 ms/op [Average]
  (min, avg, max) = (3.655, 3.760, 3.862), stdev = 0.104
  CI (99.9%): [1.866, 5.653] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 5.681 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 4.168 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.983 ±(99.9%) 0.005 ms/op
Iteration   1: 3.727 ±(99.9%) 0.005 ms/op
Iteration   2: 3.563 ±(99.9%) 0.006 ms/op
Iteration   3: 3.676 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.656 ±(99.9%) 1.530 ms/op [Average]
  (min, avg, max) = (3.563, 3.656, 3.727), stdev = 0.084
  CI (99.9%): [2.126, 5.185] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 7.374 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 5.555 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 5.300 ±(99.9%) 0.016 ms/op
Iteration   1: 5.290 ±(99.9%) 0.022 ms/op
Iteration   2: 5.310 ±(99.9%) 0.030 ms/op
Iteration   3: 5.226 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.275 ±(99.9%) 0.801 ms/op [Average]
  (min, avg, max) = (5.226, 5.275, 5.310), stdev = 0.044
  CI (99.9%): [4.475, 6.076] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 5.829 ±(99.9%) 0.061 ms/op
# Warmup Iteration   2: 3.988 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.761 ±(99.9%) 0.010 ms/op
Iteration   1: 3.700 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.783 ms/op
                 createUser·p0.50:   3.695 ms/op
                 createUser·p0.90:   4.391 ms/op
                 createUser·p0.95:   4.751 ms/op
                 createUser·p0.99:   6.160 ms/op
                 createUser·p0.999:  14.451 ms/op
                 createUser·p0.9999: 15.637 ms/op
                 createUser·p1.00:   16.368 ms/op

Iteration   2: 3.775 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.963 ms/op
                 createUser·p0.50:   3.715 ms/op
                 createUser·p0.90:   4.440 ms/op
                 createUser·p0.95:   4.792 ms/op
                 createUser·p0.99:   6.144 ms/op
                 createUser·p0.999:  13.767 ms/op
                 createUser·p0.9999: 16.706 ms/op
                 createUser·p1.00:   17.039 ms/op

Iteration   3: 3.695 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.831 ms/op
                 createUser·p0.50:   3.666 ms/op
                 createUser·p0.90:   4.252 ms/op
                 createUser·p0.95:   4.530 ms/op
                 createUser·p0.99:   5.890 ms/op
                 createUser·p0.999:  12.814 ms/op
                 createUser·p0.9999: 22.413 ms/op
                 createUser·p1.00:   22.675 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 257607
  mean =      3.723 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9220 
    [ 2.500,  5.000) = 240224 
    [ 5.000,  7.500) = 6952 
    [ 7.500, 10.000) = 621 
    [10.000, 12.500) = 242 
    [12.500, 15.000) = 214 
    [15.000, 17.500) = 70 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.783 ms/op
     p(50.0000) =      3.690 ms/op
     p(90.0000) =      4.358 ms/op
     p(95.0000) =      4.702 ms/op
     p(99.0000) =      6.078 ms/op
     p(99.9000) =     13.828 ms/op
     p(99.9900) =     19.202 ms/op
     p(99.9990) =     22.675 ms/op
     p(99.9999) =     22.675 ms/op
    p(100.0000) =     22.675 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.145 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.817 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.697 ±(99.9%) 0.009 ms/op
Iteration   1: 3.634 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.355 ms/op
                 existUser·p0.50:   3.580 ms/op
                 existUser·p0.90:   4.440 ms/op
                 existUser·p0.95:   4.719 ms/op
                 existUser·p0.99:   5.767 ms/op
                 existUser·p0.999:  11.219 ms/op
                 existUser·p0.9999: 16.052 ms/op
                 existUser·p1.00:   22.381 ms/op

Iteration   2: 3.583 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.867 ms/op
                 existUser·p0.50:   3.531 ms/op
                 existUser·p0.90:   4.415 ms/op
                 existUser·p0.95:   4.727 ms/op
                 existUser·p0.99:   5.628 ms/op
                 existUser·p0.999:  10.720 ms/op
                 existUser·p0.9999: 14.971 ms/op
                 existUser·p1.00:   17.760 ms/op

Iteration   3: 3.682 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.824 ms/op
                 existUser·p0.50:   3.625 ms/op
                 existUser·p0.90:   4.489 ms/op
                 existUser·p0.95:   4.751 ms/op
                 existUser·p0.99:   5.620 ms/op
                 existUser·p0.999:  10.783 ms/op
                 existUser·p0.9999: 34.120 ms/op
                 existUser·p1.00:   35.389 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 264314
  mean =      3.633 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10444 
    [ 2.500,  5.000) = 246913 
    [ 5.000,  7.500) = 5990 
    [ 7.500, 10.000) = 571 
    [10.000, 12.500) = 246 
    [12.500, 15.000) = 52 
    [15.000, 17.500) = 43 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 27 
    [35.000, 37.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.355 ms/op
     p(50.0000) =      3.576 ms/op
     p(90.0000) =      4.448 ms/op
     p(95.0000) =      4.735 ms/op
     p(99.0000) =      5.677 ms/op
     p(99.9000) =     10.895 ms/op
     p(99.9900) =     33.217 ms/op
     p(99.9990) =     35.240 ms/op
     p(99.9999) =     35.389 ms/op
    p(100.0000) =     35.389 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.585 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 3.917 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.841 ±(99.9%) 0.010 ms/op
Iteration   1: 3.844 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.774 ms/op
                 getUser·p0.50:   3.768 ms/op
                 getUser·p0.90:   4.760 ms/op
                 getUser·p0.95:   5.095 ms/op
                 getUser·p0.99:   6.537 ms/op
                 getUser·p0.999:  13.049 ms/op
                 getUser·p0.9999: 15.002 ms/op
                 getUser·p1.00:   17.236 ms/op

Iteration   2: 3.883 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.971 ms/op
                 getUser·p0.50:   3.822 ms/op
                 getUser·p0.90:   4.710 ms/op
                 getUser·p0.95:   4.981 ms/op
                 getUser·p0.99:   6.013 ms/op
                 getUser·p0.999:  12.740 ms/op
                 getUser·p0.9999: 16.958 ms/op
                 getUser·p1.00:   17.236 ms/op

Iteration   3: 3.944 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.014 ms/op
                 getUser·p0.50:   3.858 ms/op
                 getUser·p0.90:   4.817 ms/op
                 getUser·p0.95:   5.095 ms/op
                 getUser·p0.99:   6.562 ms/op
                 getUser·p0.999:  13.351 ms/op
                 getUser·p0.9999: 20.640 ms/op
                 getUser·p1.00:   20.972 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 246831
  mean =      3.890 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6126 
    [ 2.500,  5.000) = 226565 
    [ 5.000,  7.500) = 12735 
    [ 7.500, 10.000) = 790 
    [10.000, 12.500) = 322 
    [12.500, 15.000) = 189 
    [15.000, 17.500) = 57 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.774 ms/op
     p(50.0000) =      3.813 ms/op
     p(90.0000) =      4.768 ms/op
     p(95.0000) =      5.054 ms/op
     p(99.0000) =      6.332 ms/op
     p(99.9000) =     13.009 ms/op
     p(99.9900) =     20.327 ms/op
     p(99.9990) =     20.825 ms/op
     p(99.9999) =     20.972 ms/op
    p(100.0000) =     20.972 ms/op


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
# Warmup Iteration   1: 7.059 ±(99.9%) 0.075 ms/op
# Warmup Iteration   2: 5.058 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.921 ±(99.9%) 0.015 ms/op
Iteration   1: 4.887 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.745 ms/op
                 listUser·p0.50:   4.694 ms/op
                 listUser·p0.90:   6.136 ms/op
                 listUser·p0.95:   6.775 ms/op
                 listUser·p0.99:   8.438 ms/op
                 listUser·p0.999:  14.942 ms/op
                 listUser·p0.9999: 17.215 ms/op
                 listUser·p1.00:   17.498 ms/op

Iteration   2: 4.810 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.225 ms/op
                 listUser·p0.50:   4.555 ms/op
                 listUser·p0.90:   6.234 ms/op
                 listUser·p0.95:   6.971 ms/op
                 listUser·p0.99:   8.831 ms/op
                 listUser·p0.999:  22.235 ms/op
                 listUser·p0.9999: 26.172 ms/op
                 listUser·p1.00:   34.734 ms/op

Iteration   3: 4.890 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.442 ms/op
                 listUser·p0.50:   4.612 ms/op
                 listUser·p0.90:   6.480 ms/op
                 listUser·p0.95:   7.152 ms/op
                 listUser·p0.99:   9.110 ms/op
                 listUser·p0.999:  18.606 ms/op
                 listUser·p0.9999: 21.410 ms/op
                 listUser·p1.00:   23.069 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 197305
  mean =      4.862 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 407 
    [ 2.500,  5.000) = 133777 
    [ 5.000,  7.500) = 57015 
    [ 7.500, 10.000) = 5107 
    [10.000, 12.500) = 504 
    [12.500, 15.000) = 178 
    [15.000, 17.500) = 111 
    [17.500, 20.000) = 91 
    [20.000, 22.500) = 50 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 30 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.225 ms/op
     p(50.0000) =      4.620 ms/op
     p(90.0000) =      6.291 ms/op
     p(95.0000) =      6.980 ms/op
     p(99.0000) =      8.831 ms/op
     p(99.9000) =     17.793 ms/op
     p(99.9900) =     25.520 ms/op
     p(99.9990) =     32.247 ms/op
     p(99.9999) =     34.734 ms/op
    p(100.0000) =     34.734 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.900 ± 0.180  ops/ms
ClientGrpc.existUser                       thrpt       3   8.350 ± 2.818  ops/ms
ClientGrpc.getUser                         thrpt       3   7.784 ± 0.204  ops/ms
ClientGrpc.listUser                        thrpt       3   6.452 ± 1.936  ops/ms
ClientGrpc.createUser                       avgt       3   4.056 ± 0.909   ms/op
ClientGrpc.existUser                        avgt       3   3.760 ± 1.893   ms/op
ClientGrpc.getUser                          avgt       3   3.656 ± 1.530   ms/op
ClientGrpc.listUser                         avgt       3   5.275 ± 0.801   ms/op
ClientGrpc.createUser                     sample  257607   3.723 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.783           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.690           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.358           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.702           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.078           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.828           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.202           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.675           ms/op
ClientGrpc.existUser                      sample  264314   3.633 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.355           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.576           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.448           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.735           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.677           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.895           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          33.217           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          35.389           ms/op
ClientGrpc.getUser                        sample  246831   3.890 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.774           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.813           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.768           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.054           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.332           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          13.009           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.327           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.972           ms/op
ClientGrpc.listUser                       sample  197305   4.862 ± 0.009   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.225           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.620           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.291           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.980           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.831           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.793           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.520           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          34.734           ms/op
