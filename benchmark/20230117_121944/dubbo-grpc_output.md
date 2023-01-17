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
# Warmup Iteration   1: 3.119 ops/ms
# Warmup Iteration   2: 6.891 ops/ms
# Warmup Iteration   3: 8.012 ops/ms
Iteration   1: 8.392 ops/ms
Iteration   2: 8.411 ops/ms
Iteration   3: 8.559 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.454 ±(99.9%) 1.666 ops/ms [Average]
  (min, avg, max) = (8.392, 8.454, 8.559), stdev = 0.091
  CI (99.9%): [6.787, 10.120] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:01
# Fork: 1 of 1
# Warmup Iteration   1: 6.512 ops/ms
# Warmup Iteration   2: 8.370 ops/ms
# Warmup Iteration   3: 8.453 ops/ms
Iteration   1: 8.475 ops/ms
Iteration   2: 8.549 ops/ms
Iteration   3: 8.683 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.569 ±(99.9%) 1.923 ops/ms [Average]
  (min, avg, max) = (8.475, 8.569, 8.683), stdev = 0.105
  CI (99.9%): [6.646, 10.492] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 5.294 ops/ms
# Warmup Iteration   2: 7.969 ops/ms
# Warmup Iteration   3: 8.321 ops/ms
Iteration   1: 8.322 ops/ms
Iteration   2: 8.422 ops/ms
Iteration   3: 8.131 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.292 ±(99.9%) 2.695 ops/ms [Average]
  (min, avg, max) = (8.131, 8.292, 8.422), stdev = 0.148
  CI (99.9%): [5.597, 10.986] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 4.172 ops/ms
# Warmup Iteration   2: 6.093 ops/ms
# Warmup Iteration   3: 6.204 ops/ms
Iteration   1: 6.183 ops/ms
Iteration   2: 6.419 ops/ms
Iteration   3: 6.317 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.306 ±(99.9%) 2.160 ops/ms [Average]
  (min, avg, max) = (6.183, 6.306, 6.419), stdev = 0.118
  CI (99.9%): [4.147, 8.466] (assumes normal distribution)


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
# Warmup Iteration   1: 5.211 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 4.064 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.849 ±(99.9%) 0.013 ms/op
Iteration   1: 3.811 ±(99.9%) 0.004 ms/op
Iteration   2: 3.754 ±(99.9%) 0.003 ms/op
Iteration   3: 3.838 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.801 ±(99.9%) 0.774 ms/op [Average]
  (min, avg, max) = (3.754, 3.801, 3.838), stdev = 0.042
  CI (99.9%): [3.026, 4.575] (assumes normal distribution)


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
# Warmup Iteration   1: 5.190 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.879 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.647 ±(99.9%) 0.003 ms/op
Iteration   1: 3.715 ±(99.9%) 0.004 ms/op
Iteration   2: 3.666 ±(99.9%) 0.003 ms/op
Iteration   3: 3.696 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.692 ±(99.9%) 0.445 ms/op [Average]
  (min, avg, max) = (3.666, 3.692, 3.715), stdev = 0.024
  CI (99.9%): [3.248, 4.137] (assumes normal distribution)


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
# Warmup Iteration   1: 5.685 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.044 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.848 ±(99.9%) 0.005 ms/op
Iteration   1: 3.720 ±(99.9%) 0.007 ms/op
Iteration   2: 3.712 ±(99.9%) 0.006 ms/op
Iteration   3: 3.637 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.690 ±(99.9%) 0.841 ms/op [Average]
  (min, avg, max) = (3.637, 3.690, 3.720), stdev = 0.046
  CI (99.9%): [2.849, 4.531] (assumes normal distribution)


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
# Warmup Iteration   1: 7.212 ±(99.9%) 0.100 ms/op
# Warmup Iteration   2: 5.465 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 5.419 ±(99.9%) 0.020 ms/op
Iteration   1: 5.176 ±(99.9%) 0.019 ms/op
Iteration   2: 5.306 ±(99.9%) 0.026 ms/op
Iteration   3: 5.231 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.238 ±(99.9%) 1.192 ms/op [Average]
  (min, avg, max) = (5.176, 5.238, 5.306), stdev = 0.065
  CI (99.9%): [4.046, 6.429] (assumes normal distribution)


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
# Warmup Iteration   1: 5.394 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 4.025 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.860 ±(99.9%) 0.011 ms/op
Iteration   1: 3.877 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.791 ms/op
                 createUser·p0.50:   3.772 ms/op
                 createUser·p0.90:   4.784 ms/op
                 createUser·p0.95:   5.186 ms/op
                 createUser·p0.99:   7.217 ms/op
                 createUser·p0.999:  12.950 ms/op
                 createUser·p0.9999: 21.217 ms/op
                 createUser·p1.00:   24.281 ms/op

Iteration   2: 3.825 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.876 ms/op
                 createUser·p0.50:   3.744 ms/op
                 createUser·p0.90:   4.669 ms/op
                 createUser·p0.95:   5.014 ms/op
                 createUser·p0.99:   6.564 ms/op
                 createUser·p0.999:  16.231 ms/op
                 createUser·p0.9999: 23.961 ms/op
                 createUser·p1.00:   25.494 ms/op

Iteration   3: 3.900 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.785 ms/op
                 createUser·p0.50:   3.801 ms/op
                 createUser·p0.90:   4.801 ms/op
                 createUser·p0.95:   5.186 ms/op
                 createUser·p0.99:   7.119 ms/op
                 createUser·p0.999:  13.812 ms/op
                 createUser·p0.9999: 25.952 ms/op
                 createUser·p1.00:   26.378 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 248343
  mean =      3.867 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8917 
    [ 2.500,  5.000) = 223951 
    [ 5.000,  7.500) = 13482 
    [ 7.500, 10.000) = 1022 
    [10.000, 12.500) = 512 
    [12.500, 15.000) = 272 
    [15.000, 17.500) = 74 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 65 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 38 

  Percentiles, ms/op:
      p(0.0000) =      0.785 ms/op
     p(50.0000) =      3.772 ms/op
     p(90.0000) =      4.751 ms/op
     p(95.0000) =      5.136 ms/op
     p(99.0000) =      7.017 ms/op
     p(99.9000) =     14.232 ms/op
     p(99.9900) =     25.433 ms/op
     p(99.9990) =     26.281 ms/op
     p(99.9999) =     26.378 ms/op
    p(100.0000) =     26.378 ms/op


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
# Warmup Iteration   1: 5.350 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 3.939 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.585 ±(99.9%) 0.011 ms/op
Iteration   1: 3.726 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.756 ms/op
                 existUser·p0.50:   3.666 ms/op
                 existUser·p0.90:   4.645 ms/op
                 existUser·p0.95:   5.014 ms/op
                 existUser·p0.99:   6.889 ms/op
                 existUser·p0.999:  13.703 ms/op
                 existUser·p0.9999: 15.925 ms/op
                 existUser·p1.00:   17.826 ms/op

Iteration   2: 3.571 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.897 ms/op
                 existUser·p0.50:   3.514 ms/op
                 existUser·p0.90:   4.399 ms/op
                 existUser·p0.95:   4.760 ms/op
                 existUser·p0.99:   6.134 ms/op
                 existUser·p0.999:  12.222 ms/op
                 existUser·p0.9999: 30.507 ms/op
                 existUser·p1.00:   30.802 ms/op

Iteration   3: 3.644 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.780 ms/op
                 existUser·p0.50:   3.588 ms/op
                 existUser·p0.90:   4.424 ms/op
                 existUser·p0.95:   4.768 ms/op
                 existUser·p0.99:   6.218 ms/op
                 existUser·p0.999:  12.703 ms/op
                 existUser·p0.9999: 31.425 ms/op
                 existUser·p1.00:   32.309 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 263227
  mean =      3.646 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14946 
    [ 2.500,  5.000) = 237828 
    [ 5.000,  7.500) = 8977 
    [ 7.500, 10.000) = 849 
    [10.000, 12.500) = 333 
    [12.500, 15.000) = 139 
    [15.000, 17.500) = 57 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 10 
    [30.000, 32.500) = 54 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.756 ms/op
     p(50.0000) =      3.584 ms/op
     p(90.0000) =      4.497 ms/op
     p(95.0000) =      4.858 ms/op
     p(99.0000) =      6.398 ms/op
     p(99.9000) =     12.743 ms/op
     p(99.9900) =     30.693 ms/op
     p(99.9990) =     32.276 ms/op
     p(99.9999) =     32.309 ms/op
    p(100.0000) =     32.309 ms/op


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
# Warmup Iteration   1: 5.345 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 3.888 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.840 ±(99.9%) 0.011 ms/op
Iteration   1: 3.829 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.021 ms/op
                 getUser·p0.50:   3.768 ms/op
                 getUser·p0.90:   4.678 ms/op
                 getUser·p0.95:   4.973 ms/op
                 getUser·p0.99:   6.224 ms/op
                 getUser·p0.999:  10.695 ms/op
                 getUser·p0.9999: 19.767 ms/op
                 getUser·p1.00:   20.251 ms/op

Iteration   2: 3.736 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.846 ms/op
                 getUser·p0.50:   3.666 ms/op
                 getUser·p0.90:   4.547 ms/op
                 getUser·p0.95:   4.874 ms/op
                 getUser·p0.99:   6.226 ms/op
                 getUser·p0.999:  10.566 ms/op
                 getUser·p0.9999: 24.928 ms/op
                 getUser·p1.00:   25.461 ms/op

Iteration   3: 3.851 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.814 ms/op
                 getUser·p0.50:   3.740 ms/op
                 getUser·p0.90:   4.645 ms/op
                 getUser·p0.95:   5.071 ms/op
                 getUser·p0.99:   7.046 ms/op
                 getUser·p0.999:  13.874 ms/op
                 getUser·p0.9999: 26.345 ms/op
                 getUser·p1.00:   26.444 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 252310
  mean =      3.805 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7576 
    [ 2.500,  5.000) = 232948 
    [ 5.000,  7.500) = 10389 
    [ 7.500, 10.000) = 919 
    [10.000, 12.500) = 209 
    [12.500, 15.000) = 109 
    [15.000, 17.500) = 41 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.814 ms/op
     p(50.0000) =      3.723 ms/op
     p(90.0000) =      4.620 ms/op
     p(95.0000) =      4.964 ms/op
     p(99.0000) =      6.472 ms/op
     p(99.9000) =     13.338 ms/op
     p(99.9900) =     25.428 ms/op
     p(99.9990) =     26.411 ms/op
     p(99.9999) =     26.444 ms/op
    p(100.0000) =     26.444 ms/op


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
# Warmup Iteration   1: 6.732 ±(99.9%) 0.078 ms/op
# Warmup Iteration   2: 5.204 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 5.032 ±(99.9%) 0.019 ms/op
Iteration   1: 5.104 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   0.973 ms/op
                 listUser·p0.50:   4.727 ms/op
                 listUser·p0.90:   6.799 ms/op
                 listUser·p0.95:   7.660 ms/op
                 listUser·p0.99:   9.962 ms/op
                 listUser·p0.999:  19.825 ms/op
                 listUser·p0.9999: 36.302 ms/op
                 listUser·p1.00:   36.766 ms/op

Iteration   2: 5.286 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   1.190 ms/op
                 listUser·p0.50:   4.915 ms/op
                 listUser·p0.90:   7.152 ms/op
                 listUser·p0.95:   7.963 ms/op
                 listUser·p0.99:   10.071 ms/op
                 listUser·p0.999:  27.551 ms/op
                 listUser·p0.9999: 34.865 ms/op
                 listUser·p1.00:   35.455 ms/op

Iteration   3: 5.294 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   1.278 ms/op
                 listUser·p0.50:   4.923 ms/op
                 listUser·p0.90:   7.070 ms/op
                 listUser·p0.95:   7.995 ms/op
                 listUser·p0.99:   10.355 ms/op
                 listUser·p0.999:  25.284 ms/op
                 listUser·p0.9999: 30.535 ms/op
                 listUser·p1.00:   35.521 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 183628
  mean =      5.227 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1114 
    [ 2.500,  5.000) = 99382 
    [ 5.000,  7.500) = 70713 
    [ 7.500, 10.000) = 10434 
    [10.000, 12.500) = 1075 
    [12.500, 15.000) = 397 
    [15.000, 17.500) = 158 
    [17.500, 20.000) = 67 
    [20.000, 22.500) = 70 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 75 
    [27.500, 30.000) = 35 
    [30.000, 32.500) = 13 
    [32.500, 35.000) = 31 
    [35.000, 37.500) = 33 

  Percentiles, ms/op:
      p(0.0000) =      0.973 ms/op
     p(50.0000) =      4.841 ms/op
     p(90.0000) =      7.012 ms/op
     p(95.0000) =      7.873 ms/op
     p(99.0000) =     10.174 ms/op
     p(99.9000) =     25.092 ms/op
     p(99.9900) =     35.521 ms/op
     p(99.9990) =     36.656 ms/op
     p(99.9999) =     36.766 ms/op
    p(100.0000) =     36.766 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.454 ± 1.666  ops/ms
ClientGrpc.existUser                       thrpt       3   8.569 ± 1.923  ops/ms
ClientGrpc.getUser                         thrpt       3   8.292 ± 2.695  ops/ms
ClientGrpc.listUser                        thrpt       3   6.306 ± 2.160  ops/ms
ClientGrpc.createUser                       avgt       3   3.801 ± 0.774   ms/op
ClientGrpc.existUser                        avgt       3   3.692 ± 0.445   ms/op
ClientGrpc.getUser                          avgt       3   3.690 ± 0.841   ms/op
ClientGrpc.listUser                         avgt       3   5.238 ± 1.192   ms/op
ClientGrpc.createUser                     sample  248343   3.867 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.785           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.772           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.751           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.136           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.017           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          14.232           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          25.433           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          26.378           ms/op
ClientGrpc.existUser                      sample  263227   3.646 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.756           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.584           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.497           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.858           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.398           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          12.743           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          30.693           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          32.309           ms/op
ClientGrpc.getUser                        sample  252310   3.805 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.814           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.723           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.620           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.964           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.472           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          13.338           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          25.428           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          26.444           ms/op
ClientGrpc.listUser                       sample  183628   5.227 ± 0.013   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.973           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.841           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.012           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.873           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.174           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          25.092           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          35.521           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          36.766           ms/op
