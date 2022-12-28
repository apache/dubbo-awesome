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
# Warmup Iteration   1: 4.967 ops/ms
# Warmup Iteration   2: 9.521 ops/ms
# Warmup Iteration   3: 10.546 ops/ms
Iteration   1: 10.591 ops/ms
Iteration   2: 10.851 ops/ms
Iteration   3: 10.192 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.545 ±(99.9%) 6.060 ops/ms [Average]
  (min, avg, max) = (10.192, 10.545, 10.851), stdev = 0.332
  CI (99.9%): [4.485, 16.605] (assumes normal distribution)


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
# Warmup Iteration   1: 8.370 ops/ms
# Warmup Iteration   2: 11.059 ops/ms
# Warmup Iteration   3: 10.961 ops/ms
Iteration   1: 10.650 ops/ms
Iteration   2: 11.158 ops/ms
Iteration   3: 10.751 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.853 ±(99.9%) 4.907 ops/ms [Average]
  (min, avg, max) = (10.650, 10.853, 11.158), stdev = 0.269
  CI (99.9%): [5.946, 15.760] (assumes normal distribution)


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
# Warmup Iteration   1: 7.278 ops/ms
# Warmup Iteration   2: 10.429 ops/ms
# Warmup Iteration   3: 10.653 ops/ms
Iteration   1: 10.269 ops/ms
Iteration   2: 10.532 ops/ms
Iteration   3: 10.287 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.363 ±(99.9%) 2.682 ops/ms [Average]
  (min, avg, max) = (10.269, 10.363, 10.532), stdev = 0.147
  CI (99.9%): [7.681, 13.045] (assumes normal distribution)


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
# Warmup Iteration   1: 5.872 ops/ms
# Warmup Iteration   2: 7.918 ops/ms
# Warmup Iteration   3: 7.886 ops/ms
Iteration   1: 7.967 ops/ms
Iteration   2: 7.827 ops/ms
Iteration   3: 7.844 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.879 ±(99.9%) 1.396 ops/ms [Average]
  (min, avg, max) = (7.827, 7.879, 7.967), stdev = 0.077
  CI (99.9%): [6.483, 9.276] (assumes normal distribution)


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
# Warmup Iteration   1: 4.206 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.181 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.067 ±(99.9%) 0.003 ms/op
Iteration   1: 3.060 ±(99.9%) 0.003 ms/op
Iteration   2: 3.089 ±(99.9%) 0.002 ms/op
Iteration   3: 3.131 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.094 ±(99.9%) 0.653 ms/op [Average]
  (min, avg, max) = (3.060, 3.094, 3.131), stdev = 0.036
  CI (99.9%): [2.441, 3.746] (assumes normal distribution)


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
# Warmup Iteration   1: 3.801 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.011 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.025 ±(99.9%) 0.002 ms/op
Iteration   1: 2.949 ±(99.9%) 0.003 ms/op
Iteration   2: 2.978 ±(99.9%) 0.002 ms/op
Iteration   3: 2.993 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.973 ±(99.9%) 0.404 ms/op [Average]
  (min, avg, max) = (2.949, 2.973, 2.993), stdev = 0.022
  CI (99.9%): [2.569, 3.378] (assumes normal distribution)


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
# Warmup Iteration   1: 3.998 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.158 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.073 ±(99.9%) 0.003 ms/op
Iteration   1: 3.104 ±(99.9%) 0.002 ms/op
Iteration   2: 3.071 ±(99.9%) 0.004 ms/op
Iteration   3: 3.066 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.080 ±(99.9%) 0.377 ms/op [Average]
  (min, avg, max) = (3.066, 3.080, 3.104), stdev = 0.021
  CI (99.9%): [2.703, 3.457] (assumes normal distribution)


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
# Warmup Iteration   1: 4.115 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 4.085 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.070 ±(99.9%) 0.011 ms/op
Iteration   1: 3.889 ±(99.9%) 0.006 ms/op
Iteration   2: 3.954 ±(99.9%) 0.011 ms/op
Iteration   3: 3.924 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.922 ±(99.9%) 0.588 ms/op [Average]
  (min, avg, max) = (3.889, 3.922, 3.954), stdev = 0.032
  CI (99.9%): [3.334, 4.510] (assumes normal distribution)


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
# Warmup Iteration   1: 4.073 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.164 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.988 ±(99.9%) 0.006 ms/op
Iteration   1: 3.088 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.597 ms/op
                 createUser·p0.50:   3.052 ms/op
                 createUser·p0.90:   3.715 ms/op
                 createUser·p0.95:   3.879 ms/op
                 createUser·p0.99:   4.293 ms/op
                 createUser·p0.999:  10.289 ms/op
                 createUser·p0.9999: 17.126 ms/op
                 createUser·p1.00:   17.695 ms/op

Iteration   2: 3.049 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.521 ms/op
                 createUser·p0.50:   3.027 ms/op
                 createUser·p0.90:   3.662 ms/op
                 createUser·p0.95:   3.854 ms/op
                 createUser·p0.99:   4.125 ms/op
                 createUser·p0.999:  5.505 ms/op
                 createUser·p0.9999: 19.350 ms/op
                 createUser·p1.00:   19.857 ms/op

Iteration   3: 2.963 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.349 ms/op
                 createUser·p0.50:   2.986 ms/op
                 createUser·p0.90:   3.355 ms/op
                 createUser·p0.95:   3.502 ms/op
                 createUser·p0.99:   4.133 ms/op
                 createUser·p0.999:  7.881 ms/op
                 createUser·p0.9999: 20.709 ms/op
                 createUser·p1.00:   21.692 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 316530
  mean =      3.032 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24088 
    [ 2.500,  5.000) = 291569 
    [ 5.000,  7.500) = 446 
    [ 7.500, 10.000) = 183 
    [10.000, 12.500) = 33 
    [12.500, 15.000) = 65 
    [15.000, 17.500) = 78 
    [17.500, 20.000) = 53 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.349 ms/op
     p(50.0000) =      3.019 ms/op
     p(90.0000) =      3.588 ms/op
     p(95.0000) =      3.805 ms/op
     p(99.0000) =      4.174 ms/op
     p(99.9000) =      8.429 ms/op
     p(99.9900) =     19.628 ms/op
     p(99.9990) =     21.354 ms/op
     p(99.9999) =     21.692 ms/op
    p(100.0000) =     21.692 ms/op


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
# Warmup Iteration   1: 3.859 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 2.970 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.026 ±(99.9%) 0.007 ms/op
Iteration   1: 2.909 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.806 ms/op
                 existUser·p0.50:   2.896 ms/op
                 existUser·p0.90:   3.502 ms/op
                 existUser·p0.95:   3.707 ms/op
                 existUser·p0.99:   4.276 ms/op
                 existUser·p0.999:  6.332 ms/op
                 existUser·p0.9999: 11.469 ms/op
                 existUser·p1.00:   11.813 ms/op

Iteration   2: 2.962 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.808 ms/op
                 existUser·p0.50:   2.945 ms/op
                 existUser·p0.90:   3.617 ms/op
                 existUser·p0.95:   3.789 ms/op
                 existUser·p0.99:   4.096 ms/op
                 existUser·p0.999:  5.185 ms/op
                 existUser·p0.9999: 12.556 ms/op
                 existUser·p1.00:   12.976 ms/op

Iteration   3: 2.932 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.629 ms/op
                 existUser·p0.50:   2.929 ms/op
                 existUser·p0.90:   3.461 ms/op
                 existUser·p0.95:   3.629 ms/op
                 existUser·p0.99:   4.014 ms/op
                 existUser·p0.999:  13.074 ms/op
                 existUser·p0.9999: 24.019 ms/op
                 existUser·p1.00:   25.690 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 327380
  mean =      2.934 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 47640 
    [ 2.500,  5.000) = 279076 
    [ 5.000,  7.500) = 344 
    [ 7.500, 10.000) = 96 
    [10.000, 12.500) = 84 
    [12.500, 15.000) = 76 
    [15.000, 17.500) = 19 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.629 ms/op
     p(50.0000) =      2.925 ms/op
     p(90.0000) =      3.531 ms/op
     p(95.0000) =      3.715 ms/op
     p(99.0000) =      4.121 ms/op
     p(99.9000) =      6.976 ms/op
     p(99.9900) =     19.222 ms/op
     p(99.9990) =     25.476 ms/op
     p(99.9999) =     25.690 ms/op
    p(100.0000) =     25.690 ms/op


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
# Warmup Iteration   1: 3.897 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.075 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.007 ±(99.9%) 0.007 ms/op
Iteration   1: 3.045 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.767 ms/op
                 getUser·p0.50:   3.031 ms/op
                 getUser·p0.90:   3.568 ms/op
                 getUser·p0.95:   3.744 ms/op
                 getUser·p0.99:   4.199 ms/op
                 getUser·p0.999:  7.880 ms/op
                 getUser·p0.9999: 18.596 ms/op
                 getUser·p1.00:   19.137 ms/op

Iteration   2: 3.085 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.676 ms/op
                 getUser·p0.50:   3.056 ms/op
                 getUser·p0.90:   3.690 ms/op
                 getUser·p0.95:   3.883 ms/op
                 getUser·p0.99:   4.260 ms/op
                 getUser·p0.999:  10.895 ms/op
                 getUser·p0.9999: 20.369 ms/op
                 getUser·p1.00:   21.037 ms/op

Iteration   3: 2.992 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.547 ms/op
                 getUser·p0.50:   3.006 ms/op
                 getUser·p0.90:   3.498 ms/op
                 getUser·p0.95:   3.736 ms/op
                 getUser·p0.99:   4.415 ms/op
                 getUser·p0.999:  7.487 ms/op
                 getUser·p0.9999: 21.529 ms/op
                 getUser·p1.00:   21.823 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 315812
  mean =      3.040 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26999 
    [ 2.500,  5.000) = 287887 
    [ 5.000,  7.500) = 567 
    [ 7.500, 10.000) = 103 
    [10.000, 12.500) = 62 
    [12.500, 15.000) = 2 
    [15.000, 17.500) = 39 
    [17.500, 20.000) = 106 
    [20.000, 22.500) = 47 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.547 ms/op
     p(50.0000) =      3.027 ms/op
     p(90.0000) =      3.592 ms/op
     p(95.0000) =      3.797 ms/op
     p(99.0000) =      4.293 ms/op
     p(99.9000) =      8.054 ms/op
     p(99.9900) =     20.218 ms/op
     p(99.9990) =     21.660 ms/op
     p(99.9999) =     21.823 ms/op
    p(100.0000) =     21.823 ms/op


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
# Warmup Iteration   1: 4.380 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 4.162 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.965 ±(99.9%) 0.011 ms/op
Iteration   1: 4.040 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.354 ms/op
                 listUser·p0.50:   3.838 ms/op
                 listUser·p0.90:   5.169 ms/op
                 listUser·p0.95:   5.571 ms/op
                 listUser·p0.99:   7.045 ms/op
                 listUser·p0.999:  11.787 ms/op
                 listUser·p0.9999: 14.932 ms/op
                 listUser·p1.00:   16.286 ms/op

Iteration   2: 4.076 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.902 ms/op
                 listUser·p0.50:   3.858 ms/op
                 listUser·p0.90:   5.210 ms/op
                 listUser·p0.95:   5.538 ms/op
                 listUser·p0.99:   6.955 ms/op
                 listUser·p0.999:  14.064 ms/op
                 listUser·p0.9999: 18.060 ms/op
                 listUser·p1.00:   19.595 ms/op

Iteration   3: 4.076 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.104 ms/op
                 listUser·p0.50:   3.867 ms/op
                 listUser·p0.90:   5.317 ms/op
                 listUser·p0.95:   5.890 ms/op
                 listUser·p0.99:   7.250 ms/op
                 listUser·p0.999:  15.108 ms/op
                 listUser·p0.9999: 19.923 ms/op
                 listUser·p1.00:   21.889 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 236256
  mean =      4.064 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3669 
    [ 2.500,  5.000) = 198268 
    [ 5.000,  7.500) = 32752 
    [ 7.500, 10.000) = 1038 
    [10.000, 12.500) = 149 
    [12.500, 15.000) = 210 
    [15.000, 17.500) = 124 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.354 ms/op
     p(50.0000) =      3.854 ms/op
     p(90.0000) =      5.226 ms/op
     p(95.0000) =      5.644 ms/op
     p(99.0000) =      7.070 ms/op
     p(99.9000) =     14.135 ms/op
     p(99.9900) =     19.005 ms/op
     p(99.9990) =     21.773 ms/op
     p(99.9999) =     21.889 ms/op
    p(100.0000) =     21.889 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.545 ± 6.060  ops/ms
ClientGrpc.existUser                       thrpt       3  10.853 ± 4.907  ops/ms
ClientGrpc.getUser                         thrpt       3  10.363 ± 2.682  ops/ms
ClientGrpc.listUser                        thrpt       3   7.879 ± 1.396  ops/ms
ClientGrpc.createUser                       avgt       3   3.094 ± 0.653   ms/op
ClientGrpc.existUser                        avgt       3   2.973 ± 0.404   ms/op
ClientGrpc.getUser                          avgt       3   3.080 ± 0.377   ms/op
ClientGrpc.listUser                         avgt       3   3.922 ± 0.588   ms/op
ClientGrpc.createUser                     sample  316530   3.032 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.349           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.019           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.588           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.805           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.174           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.429           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.628           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.692           ms/op
ClientGrpc.existUser                      sample  327380   2.934 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.629           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.925           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.531           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.715           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.121           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.976           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.222           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          25.690           ms/op
ClientGrpc.getUser                        sample  315812   3.040 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.547           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.027           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.592           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.797           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.293           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.054           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.218           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.823           ms/op
ClientGrpc.listUser                       sample  236256   4.064 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.354           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.854           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.226           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.644           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.070           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.135           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          19.005           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          21.889           ms/op
