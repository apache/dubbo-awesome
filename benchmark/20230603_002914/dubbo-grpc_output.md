# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.176 ops/ms
# Warmup Iteration   2: 9.047 ops/ms
# Warmup Iteration   3: 10.161 ops/ms
Iteration   1: 10.560 ops/ms
Iteration   2: 10.461 ops/ms
Iteration   3: 10.253 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.424 ±(99.9%) 2.859 ops/ms [Average]
  (min, avg, max) = (10.253, 10.424, 10.560), stdev = 0.157
  CI (99.9%): [7.565, 13.284] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.861 ops/ms
# Warmup Iteration   2: 10.755 ops/ms
# Warmup Iteration   3: 11.072 ops/ms
Iteration   1: 11.082 ops/ms
Iteration   2: 10.896 ops/ms
Iteration   3: 11.280 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.086 ±(99.9%) 3.502 ops/ms [Average]
  (min, avg, max) = (10.896, 11.086, 11.280), stdev = 0.192
  CI (99.9%): [7.584, 14.588] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 6.919 ops/ms
# Warmup Iteration   2: 10.074 ops/ms
# Warmup Iteration   3: 10.555 ops/ms
Iteration   1: 10.518 ops/ms
Iteration   2: 10.496 ops/ms
Iteration   3: 10.802 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.605 ±(99.9%) 3.111 ops/ms [Average]
  (min, avg, max) = (10.496, 10.605, 10.802), stdev = 0.171
  CI (99.9%): [7.494, 13.717] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.613 ops/ms
# Warmup Iteration   2: 8.066 ops/ms
# Warmup Iteration   3: 8.089 ops/ms
Iteration   1: 8.210 ops/ms
Iteration   2: 8.125 ops/ms
Iteration   3: 8.030 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.122 ±(99.9%) 1.651 ops/ms [Average]
  (min, avg, max) = (8.030, 8.122, 8.210), stdev = 0.090
  CI (99.9%): [6.471, 9.772] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.549 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.213 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.051 ±(99.9%) 0.003 ms/op
Iteration   1: 3.055 ±(99.9%) 0.004 ms/op
Iteration   2: 3.019 ±(99.9%) 0.004 ms/op
Iteration   3: 2.967 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.014 ±(99.9%) 0.811 ms/op [Average]
  (min, avg, max) = (2.967, 3.014, 3.055), stdev = 0.044
  CI (99.9%): [2.202, 3.825] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 4.368 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.085 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.056 ±(99.9%) 0.003 ms/op
Iteration   1: 2.912 ±(99.9%) 0.002 ms/op
Iteration   2: 2.963 ±(99.9%) 0.002 ms/op
Iteration   3: 2.910 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.928 ±(99.9%) 0.548 ms/op [Average]
  (min, avg, max) = (2.910, 2.928, 2.963), stdev = 0.030
  CI (99.9%): [2.380, 3.476] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.464 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.182 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.033 ±(99.9%) 0.002 ms/op
Iteration   1: 3.143 ±(99.9%) 0.003 ms/op
Iteration   2: 3.137 ±(99.9%) 0.002 ms/op
Iteration   3: 3.047 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.109 ±(99.9%) 0.976 ms/op [Average]
  (min, avg, max) = (3.047, 3.109, 3.143), stdev = 0.053
  CI (99.9%): [2.133, 4.085] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 5.066 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 4.345 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.980 ±(99.9%) 0.015 ms/op
Iteration   1: 3.928 ±(99.9%) 0.007 ms/op
Iteration   2: 3.986 ±(99.9%) 0.017 ms/op
Iteration   3: 3.967 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.960 ±(99.9%) 0.539 ms/op [Average]
  (min, avg, max) = (3.928, 3.960, 3.986), stdev = 0.030
  CI (99.9%): [3.421, 4.499] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.428 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.385 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.141 ±(99.9%) 0.007 ms/op
Iteration   1: 3.009 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.531 ms/op
                 createUser·p0.50:   2.978 ms/op
                 createUser·p0.90:   3.486 ms/op
                 createUser·p0.95:   3.727 ms/op
                 createUser·p0.99:   4.547 ms/op
                 createUser·p0.999:  7.876 ms/op
                 createUser·p0.9999: 16.855 ms/op
                 createUser·p1.00:   17.138 ms/op

Iteration   2: 3.055 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.690 ms/op
                 createUser·p0.50:   2.994 ms/op
                 createUser·p0.90:   3.576 ms/op
                 createUser·p0.95:   3.912 ms/op
                 createUser·p0.99:   4.661 ms/op
                 createUser·p0.999:  12.403 ms/op
                 createUser·p0.9999: 22.905 ms/op
                 createUser·p1.00:   24.773 ms/op

Iteration   3: 3.048 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.819 ms/op
                 createUser·p0.50:   2.998 ms/op
                 createUser·p0.90:   3.613 ms/op
                 createUser·p0.95:   3.830 ms/op
                 createUser·p0.99:   4.448 ms/op
                 createUser·p0.999:  8.748 ms/op
                 createUser·p0.9999: 21.512 ms/op
                 createUser·p1.00:   21.627 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 315993
  mean =      3.037 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24346 
    [ 2.500,  5.000) = 290000 
    [ 5.000,  7.500) = 1185 
    [ 7.500, 10.000) = 176 
    [10.000, 12.500) = 56 
    [12.500, 15.000) = 26 
    [15.000, 17.500) = 63 
    [17.500, 20.000) = 81 
    [20.000, 22.500) = 43 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.531 ms/op
     p(50.0000) =      2.990 ms/op
     p(90.0000) =      3.559 ms/op
     p(95.0000) =      3.826 ms/op
     p(99.0000) =      4.563 ms/op
     p(99.9000) =      8.684 ms/op
     p(99.9900) =     21.561 ms/op
     p(99.9990) =     24.440 ms/op
     p(99.9999) =     24.773 ms/op
    p(100.0000) =     24.773 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.678 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 2.991 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.989 ±(99.9%) 0.006 ms/op
Iteration   1: 2.896 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.760 ms/op
                 existUser·p0.50:   2.867 ms/op
                 existUser·p0.90:   3.269 ms/op
                 existUser·p0.95:   3.449 ms/op
                 existUser·p0.99:   4.456 ms/op
                 existUser·p0.999:  7.100 ms/op
                 existUser·p0.9999: 26.407 ms/op
                 existUser·p1.00:   26.608 ms/op

Iteration   2: 3.016 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.734 ms/op
                 existUser·p0.50:   2.966 ms/op
                 existUser·p0.90:   3.547 ms/op
                 existUser·p0.95:   3.830 ms/op
                 existUser·p0.99:   5.087 ms/op
                 existUser·p0.999:  9.683 ms/op
                 existUser·p0.9999: 17.262 ms/op
                 existUser·p1.00:   17.629 ms/op

Iteration   3: 2.936 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.801 ms/op
                 existUser·p0.50:   2.884 ms/op
                 existUser·p0.90:   3.322 ms/op
                 existUser·p0.95:   3.527 ms/op
                 existUser·p0.99:   4.338 ms/op
                 existUser·p0.999:  11.239 ms/op
                 existUser·p0.9999: 20.388 ms/op
                 existUser·p1.00:   20.840 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 325648
  mean =      2.948 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 33158 
    [ 2.500,  5.000) = 290100 
    [ 5.000,  7.500) = 1837 
    [ 7.500, 10.000) = 242 
    [10.000, 12.500) = 126 
    [12.500, 15.000) = 25 
    [15.000, 17.500) = 91 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.734 ms/op
     p(50.0000) =      2.900 ms/op
     p(90.0000) =      3.387 ms/op
     p(95.0000) =      3.621 ms/op
     p(99.0000) =      4.669 ms/op
     p(99.9000) =      9.781 ms/op
     p(99.9900) =     23.036 ms/op
     p(99.9990) =     26.534 ms/op
     p(99.9999) =     26.608 ms/op
    p(100.0000) =     26.608 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.188 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.147 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.073 ±(99.9%) 0.007 ms/op
Iteration   1: 3.094 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.965 ms/op
                 getUser·p0.50:   3.056 ms/op
                 getUser·p0.90:   3.650 ms/op
                 getUser·p0.95:   3.834 ms/op
                 getUser·p0.99:   4.547 ms/op
                 getUser·p0.999:  8.855 ms/op
                 getUser·p0.9999: 16.171 ms/op
                 getUser·p1.00:   16.515 ms/op

Iteration   2: 3.064 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.845 ms/op
                 getUser·p0.50:   3.011 ms/op
                 getUser·p0.90:   3.609 ms/op
                 getUser·p0.95:   3.879 ms/op
                 getUser·p0.99:   4.637 ms/op
                 getUser·p0.999:  10.132 ms/op
                 getUser·p0.9999: 14.600 ms/op
                 getUser·p1.00:   14.942 ms/op

Iteration   3: 3.021 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.610 ms/op
                 getUser·p0.50:   2.986 ms/op
                 getUser·p0.90:   3.478 ms/op
                 getUser·p0.95:   3.703 ms/op
                 getUser·p0.99:   4.604 ms/op
                 getUser·p0.999:  7.669 ms/op
                 getUser·p0.9999: 17.039 ms/op
                 getUser·p1.00:   17.170 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 313738
  mean =      3.060 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 493 
    [ 1.250,  2.500) = 18687 
    [ 2.500,  3.750) = 275267 
    [ 3.750,  5.000) = 17401 
    [ 5.000,  6.250) = 1062 
    [ 6.250,  7.500) = 360 
    [ 7.500,  8.750) = 140 
    [ 8.750, 10.000) = 94 
    [10.000, 11.250) = 10 
    [11.250, 12.500) = 18 
    [12.500, 13.750) = 44 
    [13.750, 15.000) = 82 
    [15.000, 16.250) = 51 
    [16.250, 17.500) = 29 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.610 ms/op
     p(50.0000) =      3.015 ms/op
     p(90.0000) =      3.584 ms/op
     p(95.0000) =      3.822 ms/op
     p(99.0000) =      4.604 ms/op
     p(99.9000) =      8.852 ms/op
     p(99.9900) =     16.202 ms/op
     p(99.9990) =     17.138 ms/op
     p(99.9999) =     17.170 ms/op
    p(100.0000) =     17.170 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 6.051 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 4.207 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.050 ±(99.9%) 0.012 ms/op
Iteration   1: 4.060 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.110 ms/op
                 listUser·p0.50:   3.867 ms/op
                 listUser·p0.90:   5.194 ms/op
                 listUser·p0.95:   5.898 ms/op
                 listUser·p0.99:   7.383 ms/op
                 listUser·p0.999:  15.372 ms/op
                 listUser·p0.9999: 20.189 ms/op
                 listUser·p1.00:   20.840 ms/op

Iteration   2: 4.191 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.202 ms/op
                 listUser·p0.50:   3.932 ms/op
                 listUser·p0.90:   5.574 ms/op
                 listUser·p0.95:   6.332 ms/op
                 listUser·p0.99:   7.971 ms/op
                 listUser·p0.999:  14.822 ms/op
                 listUser·p0.9999: 19.232 ms/op
                 listUser·p1.00:   21.856 ms/op

Iteration   3: 4.077 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.180 ms/op
                 listUser·p0.50:   3.867 ms/op
                 listUser·p0.90:   5.267 ms/op
                 listUser·p0.95:   5.939 ms/op
                 listUser·p0.99:   7.170 ms/op
                 listUser·p0.999:  16.871 ms/op
                 listUser·p0.9999: 19.202 ms/op
                 listUser·p1.00:   20.185 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 233698
  mean =      4.108 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1847 
    [ 2.500,  5.000) = 200355 
    [ 5.000,  7.500) = 29119 
    [ 7.500, 10.000) = 1880 
    [10.000, 12.500) = 131 
    [12.500, 15.000) = 106 
    [15.000, 17.500) = 141 
    [17.500, 20.000) = 99 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.110 ms/op
     p(50.0000) =      3.887 ms/op
     p(90.0000) =      5.333 ms/op
     p(95.0000) =      6.070 ms/op
     p(99.0000) =      7.520 ms/op
     p(99.9000) =     15.532 ms/op
     p(99.9900) =     19.956 ms/op
     p(99.9990) =     20.818 ms/op
     p(99.9999) =     21.856 ms/op
    p(100.0000) =     21.856 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.424 ± 2.859  ops/ms
ClientGrpc.existUser                       thrpt       3  11.086 ± 3.502  ops/ms
ClientGrpc.getUser                         thrpt       3  10.605 ± 3.111  ops/ms
ClientGrpc.listUser                        thrpt       3   8.122 ± 1.651  ops/ms
ClientGrpc.createUser                       avgt       3   3.014 ± 0.811   ms/op
ClientGrpc.existUser                        avgt       3   2.928 ± 0.548   ms/op
ClientGrpc.getUser                          avgt       3   3.109 ± 0.976   ms/op
ClientGrpc.listUser                         avgt       3   3.960 ± 0.539   ms/op
ClientGrpc.createUser                     sample  315993   3.037 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.531           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.990           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.559           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.826           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.563           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.684           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.561           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          24.773           ms/op
ClientGrpc.existUser                      sample  325648   2.948 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.734           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.900           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.387           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.621           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.669           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.781           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          23.036           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          26.608           ms/op
ClientGrpc.getUser                        sample  313738   3.060 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.610           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.015           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.584           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.822           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.604           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.852           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.202           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          17.170           ms/op
ClientGrpc.listUser                       sample  233698   4.108 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.110           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.887           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.333           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.070           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.520           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.532           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          19.956           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          21.856           ms/op
