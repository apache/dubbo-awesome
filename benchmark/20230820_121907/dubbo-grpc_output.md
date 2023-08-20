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
# Warmup Iteration   1: 3.328 ops/ms
# Warmup Iteration   2: 7.268 ops/ms
# Warmup Iteration   3: 8.398 ops/ms
Iteration   1: 8.762 ops/ms
Iteration   2: 8.799 ops/ms
Iteration   3: 8.775 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.779 ±(99.9%) 0.344 ops/ms [Average]
  (min, avg, max) = (8.762, 8.779, 8.799), stdev = 0.019
  CI (99.9%): [8.434, 9.123] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 5.919 ops/ms
# Warmup Iteration   2: 8.815 ops/ms
# Warmup Iteration   3: 9.061 ops/ms
Iteration   1: 9.347 ops/ms
Iteration   2: 9.357 ops/ms
Iteration   3: 9.240 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.315 ±(99.9%) 1.181 ops/ms [Average]
  (min, avg, max) = (9.240, 9.315, 9.357), stdev = 0.065
  CI (99.9%): [8.134, 10.496] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 6.177 ops/ms
# Warmup Iteration   2: 8.173 ops/ms
# Warmup Iteration   3: 8.788 ops/ms
Iteration   1: 8.873 ops/ms
Iteration   2: 8.800 ops/ms
Iteration   3: 8.927 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.867 ±(99.9%) 1.159 ops/ms [Average]
  (min, avg, max) = (8.800, 8.867, 8.927), stdev = 0.064
  CI (99.9%): [7.708, 10.025] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 4.929 ops/ms
# Warmup Iteration   2: 6.597 ops/ms
# Warmup Iteration   3: 6.695 ops/ms
Iteration   1: 6.670 ops/ms
Iteration   2: 6.874 ops/ms
Iteration   3: 6.817 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.787 ±(99.9%) 1.920 ops/ms [Average]
  (min, avg, max) = (6.670, 6.787, 6.874), stdev = 0.105
  CI (99.9%): [4.867, 8.707] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 5.500 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.890 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 3.778 ±(99.9%) 0.013 ms/op
Iteration   1: 3.764 ±(99.9%) 0.004 ms/op
Iteration   2: 3.672 ±(99.9%) 0.004 ms/op
Iteration   3: 3.720 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.719 ±(99.9%) 0.839 ms/op [Average]
  (min, avg, max) = (3.672, 3.719, 3.764), stdev = 0.046
  CI (99.9%): [2.879, 4.558] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 5.226 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.554 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.445 ±(99.9%) 0.004 ms/op
Iteration   1: 3.423 ±(99.9%) 0.005 ms/op
Iteration   2: 3.369 ±(99.9%) 0.003 ms/op
Iteration   3: 3.442 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.411 ±(99.9%) 0.691 ms/op [Average]
  (min, avg, max) = (3.369, 3.411, 3.442), stdev = 0.038
  CI (99.9%): [2.720, 4.102] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 5.434 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.801 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.709 ±(99.9%) 0.003 ms/op
Iteration   1: 3.593 ±(99.9%) 0.005 ms/op
Iteration   2: 3.615 ±(99.9%) 0.004 ms/op
Iteration   3: 3.570 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.593 ±(99.9%) 0.411 ms/op [Average]
  (min, avg, max) = (3.570, 3.593, 3.615), stdev = 0.023
  CI (99.9%): [3.182, 4.003] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 6.729 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 4.967 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.673 ±(99.9%) 0.015 ms/op
Iteration   1: 4.691 ±(99.9%) 0.008 ms/op
Iteration   2: 4.741 ±(99.9%) 0.017 ms/op
Iteration   3: 4.691 ±(99.9%) 0.024 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.708 ±(99.9%) 0.521 ms/op [Average]
  (min, avg, max) = (4.691, 4.708, 4.741), stdev = 0.029
  CI (99.9%): [4.187, 5.228] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 5.336 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 3.895 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.657 ±(99.9%) 0.008 ms/op
Iteration   1: 3.645 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.809 ms/op
                 createUser·p0.50:   3.584 ms/op
                 createUser·p0.90:   4.260 ms/op
                 createUser·p0.95:   4.612 ms/op
                 createUser·p0.99:   6.005 ms/op
                 createUser·p0.999:  8.768 ms/op
                 createUser·p0.9999: 16.080 ms/op
                 createUser·p1.00:   16.302 ms/op

Iteration   2: 3.623 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.828 ms/op
                 createUser·p0.50:   3.568 ms/op
                 createUser·p0.90:   4.252 ms/op
                 createUser·p0.95:   4.588 ms/op
                 createUser·p0.99:   5.831 ms/op
                 createUser·p0.999:  13.108 ms/op
                 createUser·p0.9999: 16.351 ms/op
                 createUser·p1.00:   16.712 ms/op

Iteration   3: 3.565 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.071 ms/op
                 createUser·p0.50:   3.527 ms/op
                 createUser·p0.90:   4.202 ms/op
                 createUser·p0.95:   4.530 ms/op
                 createUser·p0.99:   5.816 ms/op
                 createUser·p0.999:  10.655 ms/op
                 createUser·p0.9999: 19.431 ms/op
                 createUser·p1.00:   19.628 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 265870
  mean =      3.611 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 127 
    [ 1.250,  2.500) = 7840 
    [ 2.500,  3.750) = 168349 
    [ 3.750,  5.000) = 83058 
    [ 5.000,  6.250) = 4540 
    [ 6.250,  7.500) = 885 
    [ 7.500,  8.750) = 503 
    [ 8.750, 10.000) = 275 
    [10.000, 11.250) = 73 
    [11.250, 12.500) = 27 
    [12.500, 13.750) = 39 
    [13.750, 15.000) = 24 
    [15.000, 16.250) = 53 
    [16.250, 17.500) = 26 
    [17.500, 18.750) = 13 

  Percentiles, ms/op:
      p(0.0000) =      0.809 ms/op
     p(50.0000) =      3.559 ms/op
     p(90.0000) =      4.243 ms/op
     p(95.0000) =      4.579 ms/op
     p(99.0000) =      5.882 ms/op
     p(99.9000) =     10.422 ms/op
     p(99.9900) =     19.071 ms/op
     p(99.9990) =     19.628 ms/op
     p(99.9999) =     19.628 ms/op
    p(100.0000) =     19.628 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 4.969 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.595 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.462 ±(99.9%) 0.008 ms/op
Iteration   1: 3.519 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.893 ms/op
                 existUser·p0.50:   3.469 ms/op
                 existUser·p0.90:   4.030 ms/op
                 existUser·p0.95:   4.293 ms/op
                 existUser·p0.99:   5.153 ms/op
                 existUser·p0.999:  8.964 ms/op
                 existUser·p0.9999: 19.953 ms/op
                 existUser·p1.00:   20.873 ms/op

Iteration   2: 3.436 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.672 ms/op
                 existUser·p0.50:   3.424 ms/op
                 existUser·p0.90:   3.936 ms/op
                 existUser·p0.95:   4.194 ms/op
                 existUser·p0.99:   5.194 ms/op
                 existUser·p0.999:  9.009 ms/op
                 existUser·p0.9999: 16.451 ms/op
                 existUser·p1.00:   16.810 ms/op

Iteration   3: 3.405 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.811 ms/op
                 existUser·p0.50:   3.391 ms/op
                 existUser·p0.90:   4.043 ms/op
                 existUser·p0.95:   4.350 ms/op
                 existUser·p0.99:   5.530 ms/op
                 existUser·p0.999:  11.455 ms/op
                 existUser·p0.9999: 19.431 ms/op
                 existUser·p1.00:   19.694 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 277889
  mean =      3.453 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10031 
    [ 2.500,  5.000) = 263987 
    [ 5.000,  7.500) = 3167 
    [ 7.500, 10.000) = 437 
    [10.000, 12.500) = 107 
    [12.500, 15.000) = 5 
    [15.000, 17.500) = 61 
    [17.500, 20.000) = 87 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.672 ms/op
     p(50.0000) =      3.428 ms/op
     p(90.0000) =      4.006 ms/op
     p(95.0000) =      4.276 ms/op
     p(99.0000) =      5.358 ms/op
     p(99.9000) =      9.867 ms/op
     p(99.9900) =     19.406 ms/op
     p(99.9990) =     20.094 ms/op
     p(99.9999) =     20.873 ms/op
    p(100.0000) =     20.873 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.246 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 3.780 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.670 ±(99.9%) 0.008 ms/op
Iteration   1: 3.613 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.938 ms/op
                 getUser·p0.50:   3.555 ms/op
                 getUser·p0.90:   4.317 ms/op
                 getUser·p0.95:   4.710 ms/op
                 getUser·p0.99:   5.931 ms/op
                 getUser·p0.999:  12.015 ms/op
                 getUser·p0.9999: 15.291 ms/op
                 getUser·p1.00:   15.696 ms/op

Iteration   2: 3.646 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.728 ms/op
                 getUser·p0.50:   3.592 ms/op
                 getUser·p0.90:   4.375 ms/op
                 getUser·p0.95:   4.751 ms/op
                 getUser·p0.99:   5.792 ms/op
                 getUser·p0.999:  9.299 ms/op
                 getUser·p0.9999: 18.915 ms/op
                 getUser·p1.00:   19.956 ms/op

Iteration   3: 3.679 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.894 ms/op
                 getUser·p0.50:   3.625 ms/op
                 getUser·p0.90:   4.415 ms/op
                 getUser·p0.95:   4.735 ms/op
                 getUser·p0.99:   5.808 ms/op
                 getUser·p0.999:  10.878 ms/op
                 getUser·p0.9999: 29.730 ms/op
                 getUser·p1.00:   30.015 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 263389
  mean =      3.646 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9954 
    [ 2.500,  5.000) = 246185 
    [ 5.000,  7.500) = 6300 
    [ 7.500, 10.000) = 637 
    [10.000, 12.500) = 163 
    [12.500, 15.000) = 39 
    [15.000, 17.500) = 35 
    [17.500, 20.000) = 42 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 1 
    [27.500, 30.000) = 29 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.728 ms/op
     p(50.0000) =      3.588 ms/op
     p(90.0000) =      4.375 ms/op
     p(95.0000) =      4.735 ms/op
     p(99.0000) =      5.849 ms/op
     p(99.9000) =     10.463 ms/op
     p(99.9900) =     28.027 ms/op
     p(99.9990) =     29.995 ms/op
     p(99.9999) =     30.015 ms/op
    p(100.0000) =     30.015 ms/op


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
# Warmup Iteration   1: 6.746 ±(99.9%) 0.078 ms/op
# Warmup Iteration   2: 5.095 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.792 ±(99.9%) 0.015 ms/op
Iteration   1: 4.827 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.360 ms/op
                 listUser·p0.50:   4.620 ms/op
                 listUser·p0.90:   6.103 ms/op
                 listUser·p0.95:   6.930 ms/op
                 listUser·p0.99:   8.749 ms/op
                 listUser·p0.999:  16.544 ms/op
                 listUser·p0.9999: 26.033 ms/op
                 listUser·p1.00:   26.444 ms/op

Iteration   2: 4.692 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.366 ms/op
                 listUser·p0.50:   4.547 ms/op
                 listUser·p0.90:   5.349 ms/op
                 listUser·p0.95:   6.128 ms/op
                 listUser·p0.99:   8.128 ms/op
                 listUser·p0.999:  18.611 ms/op
                 listUser·p0.9999: 24.326 ms/op
                 listUser·p1.00:   24.510 ms/op

Iteration   3: 4.738 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.171 ms/op
                 listUser·p0.50:   4.547 ms/op
                 listUser·p0.90:   5.865 ms/op
                 listUser·p0.95:   6.742 ms/op
                 listUser·p0.99:   8.438 ms/op
                 listUser·p0.999:  20.189 ms/op
                 listUser·p0.9999: 23.101 ms/op
                 listUser·p1.00:   23.331 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 202025
  mean =      4.752 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 491 
    [ 2.500,  5.000) = 155692 
    [ 5.000,  7.500) = 40965 
    [ 7.500, 10.000) = 4112 
    [10.000, 12.500) = 429 
    [12.500, 15.000) = 40 
    [15.000, 17.500) = 62 
    [17.500, 20.000) = 47 
    [20.000, 22.500) = 117 
    [22.500, 25.000) = 57 
    [25.000, 27.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      1.171 ms/op
     p(50.0000) =      4.571 ms/op
     p(90.0000) =      5.800 ms/op
     p(95.0000) =      6.676 ms/op
     p(99.0000) =      8.487 ms/op
     p(99.9000) =     18.873 ms/op
     p(99.9900) =     24.307 ms/op
     p(99.9990) =     26.407 ms/op
     p(99.9999) =     26.444 ms/op
    p(100.0000) =     26.444 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.779 ± 0.344  ops/ms
ClientGrpc.existUser                       thrpt       3   9.315 ± 1.181  ops/ms
ClientGrpc.getUser                         thrpt       3   8.867 ± 1.159  ops/ms
ClientGrpc.listUser                        thrpt       3   6.787 ± 1.920  ops/ms
ClientGrpc.createUser                       avgt       3   3.719 ± 0.839   ms/op
ClientGrpc.existUser                        avgt       3   3.411 ± 0.691   ms/op
ClientGrpc.getUser                          avgt       3   3.593 ± 0.411   ms/op
ClientGrpc.listUser                         avgt       3   4.708 ± 0.521   ms/op
ClientGrpc.createUser                     sample  265870   3.611 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.809           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.559           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.243           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.579           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.882           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.422           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.071           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          19.628           ms/op
ClientGrpc.existUser                      sample  277889   3.453 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.672           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.428           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.006           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.276           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.358           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.867           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.406           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.873           ms/op
ClientGrpc.getUser                        sample  263389   3.646 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.728           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.588           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.375           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.735           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.849           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.463           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          28.027           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          30.015           ms/op
ClientGrpc.listUser                       sample  202025   4.752 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.171           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.571           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.800           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.676           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.487           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.873           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.307           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.444           ms/op
