# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.076 ops/ms
# Warmup Iteration   2: 5.148 ops/ms
# Warmup Iteration   3: 6.409 ops/ms
Iteration   1: 6.783 ops/ms
Iteration   2: 6.760 ops/ms
Iteration   3: 6.766 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  6.770 ±(99.9%) 0.221 ops/ms [Average]
  (min, avg, max) = (6.760, 6.770, 6.783), stdev = 0.012
  CI (99.9%): [6.549, 6.991] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 4.218 ops/ms
# Warmup Iteration   2: 6.939 ops/ms
# Warmup Iteration   3: 7.198 ops/ms
Iteration   1: 7.284 ops/ms
Iteration   2: 7.296 ops/ms
Iteration   3: 7.177 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.252 ±(99.9%) 1.200 ops/ms [Average]
  (min, avg, max) = (7.177, 7.252, 7.296), stdev = 0.066
  CI (99.9%): [6.053, 8.452] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.873 ops/ms
# Warmup Iteration   2: 6.024 ops/ms
# Warmup Iteration   3: 6.590 ops/ms
Iteration   1: 6.654 ops/ms
Iteration   2: 6.507 ops/ms
Iteration   3: 6.647 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  6.603 ±(99.9%) 1.514 ops/ms [Average]
  (min, avg, max) = (6.507, 6.603, 6.654), stdev = 0.083
  CI (99.9%): [5.088, 8.117] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 3.406 ops/ms
# Warmup Iteration   2: 4.705 ops/ms
# Warmup Iteration   3: 5.326 ops/ms
Iteration   1: 5.299 ops/ms
Iteration   2: 5.282 ops/ms
Iteration   3: 5.355 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.312 ±(99.9%) 0.695 ops/ms [Average]
  (min, avg, max) = (5.282, 5.312, 5.355), stdev = 0.038
  CI (99.9%): [4.618, 6.007] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.053 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.903 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.851 ±(99.9%) 0.017 ms/op
Iteration   1: 4.749 ±(99.9%) 0.002 ms/op
Iteration   2: 4.941 ±(99.9%) 0.006 ms/op
Iteration   3: 4.757 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.816 ±(99.9%) 1.985 ms/op [Average]
  (min, avg, max) = (4.749, 4.816, 4.941), stdev = 0.109
  CI (99.9%): [2.830, 6.801] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 6.235 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.675 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.586 ±(99.9%) 0.012 ms/op
Iteration   1: 4.559 ±(99.9%) 0.003 ms/op
Iteration   2: 4.599 ±(99.9%) 0.002 ms/op
Iteration   3: 4.527 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.562 ±(99.9%) 0.658 ms/op [Average]
  (min, avg, max) = (4.527, 4.562, 4.599), stdev = 0.036
  CI (99.9%): [3.904, 5.219] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 6.947 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 5.034 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.862 ±(99.9%) 0.005 ms/op
Iteration   1: 4.848 ±(99.9%) 0.005 ms/op
Iteration   2: 4.695 ±(99.9%) 0.011 ms/op
Iteration   3: 4.824 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.789 ±(99.9%) 1.505 ms/op [Average]
  (min, avg, max) = (4.695, 4.789, 4.848), stdev = 0.082
  CI (99.9%): [3.284, 6.294] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 8.706 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 6.327 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 5.994 ±(99.9%) 0.020 ms/op
Iteration   1: 5.970 ±(99.9%) 0.014 ms/op
Iteration   2: 5.903 ±(99.9%) 0.027 ms/op
Iteration   3: 5.905 ±(99.9%) 0.038 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.926 ±(99.9%) 0.696 ms/op [Average]
  (min, avg, max) = (5.903, 5.926, 5.970), stdev = 0.038
  CI (99.9%): [5.230, 6.622] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 6.340 ±(99.9%) 0.086 ms/op
# Warmup Iteration   2: 5.012 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.801 ±(99.9%) 0.016 ms/op
Iteration   1: 4.797 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   0.981 ms/op
                 createUser·p0.50:   4.653 ms/op
                 createUser·p0.90:   6.160 ms/op
                 createUser·p0.95:   6.627 ms/op
                 createUser·p0.99:   8.318 ms/op
                 createUser·p0.999:  16.619 ms/op
                 createUser·p0.9999: 22.534 ms/op
                 createUser·p1.00:   23.101 ms/op

Iteration   2: 4.750 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.128 ms/op
                 createUser·p0.50:   4.669 ms/op
                 createUser·p0.90:   5.939 ms/op
                 createUser·p0.95:   6.357 ms/op
                 createUser·p0.99:   7.713 ms/op
                 createUser·p0.999:  14.690 ms/op
                 createUser·p0.9999: 19.851 ms/op
                 createUser·p1.00:   20.677 ms/op

Iteration   3: 4.566 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.190 ms/op
                 createUser·p0.50:   4.481 ms/op
                 createUser·p0.90:   5.702 ms/op
                 createUser·p0.95:   6.103 ms/op
                 createUser·p0.99:   7.225 ms/op
                 createUser·p0.999:  11.735 ms/op
                 createUser·p0.9999: 23.888 ms/op
                 createUser·p1.00:   24.216 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 204188
  mean =      4.702 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2109 
    [ 2.500,  5.000) = 132656 
    [ 5.000,  7.500) = 66960 
    [ 7.500, 10.000) = 1896 
    [10.000, 12.500) = 227 
    [12.500, 15.000) = 129 
    [15.000, 17.500) = 127 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.981 ms/op
     p(50.0000) =      4.596 ms/op
     p(90.0000) =      5.939 ms/op
     p(95.0000) =      6.382 ms/op
     p(99.0000) =      7.733 ms/op
     p(99.9000) =     15.244 ms/op
     p(99.9900) =     22.577 ms/op
     p(99.9990) =     24.083 ms/op
     p(99.9999) =     24.216 ms/op
    p(100.0000) =     24.216 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.142 ±(99.9%) 0.073 ms/op
# Warmup Iteration   2: 4.702 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.627 ±(99.9%) 0.014 ms/op
Iteration   1: 4.503 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.143 ms/op
                 existUser·p0.50:   4.407 ms/op
                 existUser·p0.90:   5.767 ms/op
                 existUser·p0.95:   6.185 ms/op
                 existUser·p0.99:   7.537 ms/op
                 existUser·p0.999:  10.174 ms/op
                 existUser·p0.9999: 22.181 ms/op
                 existUser·p1.00:   23.921 ms/op

Iteration   2: 4.622 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.223 ms/op
                 existUser·p0.50:   4.530 ms/op
                 existUser·p0.90:   5.841 ms/op
                 existUser·p0.95:   6.267 ms/op
                 existUser·p0.99:   8.119 ms/op
                 existUser·p0.999:  13.121 ms/op
                 existUser·p0.9999: 21.204 ms/op
                 existUser·p1.00:   21.791 ms/op

Iteration   3: 4.438 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   1.055 ms/op
                 existUser·p0.50:   4.375 ms/op
                 existUser·p0.90:   5.677 ms/op
                 existUser·p0.95:   6.087 ms/op
                 existUser·p0.99:   7.702 ms/op
                 existUser·p0.999:  14.136 ms/op
                 existUser·p0.9999: 24.201 ms/op
                 existUser·p1.00:   24.740 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 212375
  mean =      4.520 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5804 
    [ 2.500,  5.000) = 144787 
    [ 5.000,  7.500) = 59269 
    [ 7.500, 10.000) = 2028 
    [10.000, 12.500) = 208 
    [12.500, 15.000) = 177 
    [15.000, 17.500) = 6 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 73 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.055 ms/op
     p(50.0000) =      4.440 ms/op
     p(90.0000) =      5.759 ms/op
     p(95.0000) =      6.177 ms/op
     p(99.0000) =      7.774 ms/op
     p(99.9000) =     13.445 ms/op
     p(99.9900) =     23.520 ms/op
     p(99.9990) =     24.564 ms/op
     p(99.9999) =     24.740 ms/op
    p(100.0000) =     24.740 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 7.326 ±(99.9%) 0.093 ms/op
# Warmup Iteration   2: 4.903 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.841 ±(99.9%) 0.016 ms/op
Iteration   1: 4.692 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.141 ms/op
                 getUser·p0.50:   4.596 ms/op
                 getUser·p0.90:   5.874 ms/op
                 getUser·p0.95:   6.316 ms/op
                 getUser·p0.99:   7.603 ms/op
                 getUser·p0.999:  11.431 ms/op
                 getUser·p0.9999: 25.839 ms/op
                 getUser·p1.00:   26.214 ms/op

Iteration   2: 4.722 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   0.709 ms/op
                 getUser·p0.50:   4.620 ms/op
                 getUser·p0.90:   5.980 ms/op
                 getUser·p0.95:   6.406 ms/op
                 getUser·p0.99:   8.061 ms/op
                 getUser·p0.999:  14.657 ms/op
                 getUser·p0.9999: 29.939 ms/op
                 getUser·p1.00:   31.162 ms/op

Iteration   3: 4.713 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   0.787 ms/op
                 getUser·p0.50:   4.645 ms/op
                 getUser·p0.90:   5.964 ms/op
                 getUser·p0.95:   6.362 ms/op
                 getUser·p0.99:   7.643 ms/op
                 getUser·p0.999:  10.782 ms/op
                 getUser·p0.9999: 29.884 ms/op
                 getUser·p1.00:   29.950 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 203898
  mean =      4.709 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3320 
    [ 2.500,  5.000) = 129987 
    [ 5.000,  7.500) = 68138 
    [ 7.500, 10.000) = 1982 
    [10.000, 12.500) = 285 
    [12.500, 15.000) = 45 
    [15.000, 17.500) = 12 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 52 
    [27.500, 30.000) = 19 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.709 ms/op
     p(50.0000) =      4.620 ms/op
     p(90.0000) =      5.947 ms/op
     p(95.0000) =      6.365 ms/op
     p(99.0000) =      7.733 ms/op
     p(99.9000) =     12.239 ms/op
     p(99.9900) =     29.191 ms/op
     p(99.9990) =     31.082 ms/op
     p(99.9999) =     31.162 ms/op
    p(100.0000) =     31.162 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 8.362 ±(99.9%) 0.104 ms/op
# Warmup Iteration   2: 6.195 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 6.242 ±(99.9%) 0.026 ms/op
Iteration   1: 6.139 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   1.780 ms/op
                 listUser·p0.50:   5.767 ms/op
                 listUser·p0.90:   8.323 ms/op
                 listUser·p0.95:   9.306 ms/op
                 listUser·p0.99:   11.862 ms/op
                 listUser·p0.999:  16.314 ms/op
                 listUser·p0.9999: 29.386 ms/op
                 listUser·p1.00:   29.983 ms/op

Iteration   2: 6.179 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   1.481 ms/op
                 listUser·p0.50:   5.825 ms/op
                 listUser·p0.90:   8.298 ms/op
                 listUser·p0.95:   9.257 ms/op
                 listUser·p0.99:   11.387 ms/op
                 listUser·p0.999:  21.045 ms/op
                 listUser·p0.9999: 28.759 ms/op
                 listUser·p1.00:   29.032 ms/op

Iteration   3: 6.245 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   1.933 ms/op
                 listUser·p0.50:   5.849 ms/op
                 listUser·p0.90:   8.634 ms/op
                 listUser·p0.95:   9.519 ms/op
                 listUser·p0.99:   11.616 ms/op
                 listUser·p0.999:  21.772 ms/op
                 listUser·p0.9999: 27.230 ms/op
                 listUser·p1.00:   27.525 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 155132
  mean =      6.187 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 58 
    [ 2.500,  5.000) = 34639 
    [ 5.000,  7.500) = 92848 
    [ 7.500, 10.000) = 22815 
    [10.000, 12.500) = 3800 
    [12.500, 15.000) = 618 
    [15.000, 17.500) = 146 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 69 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 47 

  Percentiles, ms/op:
      p(0.0000) =      1.481 ms/op
     p(50.0000) =      5.816 ms/op
     p(90.0000) =      8.421 ms/op
     p(95.0000) =      9.355 ms/op
     p(99.0000) =     11.633 ms/op
     p(99.9000) =     20.893 ms/op
     p(99.9900) =     29.016 ms/op
     p(99.9990) =     29.802 ms/op
     p(99.9999) =     29.983 ms/op
    p(100.0000) =     29.983 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   6.770 ± 0.221  ops/ms
ClientGrpc.existUser                       thrpt       3   7.252 ± 1.200  ops/ms
ClientGrpc.getUser                         thrpt       3   6.603 ± 1.514  ops/ms
ClientGrpc.listUser                        thrpt       3   5.312 ± 0.695  ops/ms
ClientGrpc.createUser                       avgt       3   4.816 ± 1.985   ms/op
ClientGrpc.existUser                        avgt       3   4.562 ± 0.658   ms/op
ClientGrpc.getUser                          avgt       3   4.789 ± 1.505   ms/op
ClientGrpc.listUser                         avgt       3   5.926 ± 0.696   ms/op
ClientGrpc.createUser                     sample  204188   4.702 ± 0.008   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.981           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.596           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.939           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           6.382           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.733           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          15.244           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          22.577           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          24.216           ms/op
ClientGrpc.existUser                      sample  212375   4.520 ± 0.008   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           1.055           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.440           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.759           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           6.177           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.774           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          13.445           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          23.520           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          24.740           ms/op
ClientGrpc.getUser                        sample  203898   4.709 ± 0.008   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.709           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.620           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.947           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.365           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.733           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.239           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          29.191           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          31.162           ms/op
ClientGrpc.listUser                       sample  155132   6.187 ± 0.015   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.481           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.816           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           8.421           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           9.355           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          11.633           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          20.893           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          29.016           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          29.983           ms/op
