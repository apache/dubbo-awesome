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
# Warmup Iteration   1: 3.249 ops/ms
# Warmup Iteration   2: 6.442 ops/ms
# Warmup Iteration   3: 8.066 ops/ms
Iteration   1: 8.466 ops/ms
Iteration   2: 8.830 ops/ms
Iteration   3: 8.685 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.661 ±(99.9%) 3.348 ops/ms [Average]
  (min, avg, max) = (8.466, 8.661, 8.830), stdev = 0.184
  CI (99.9%): [5.313, 12.009] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 6.043 ops/ms
# Warmup Iteration   2: 8.426 ops/ms
# Warmup Iteration   3: 9.077 ops/ms
Iteration   1: 9.131 ops/ms
Iteration   2: 9.028 ops/ms
Iteration   3: 9.003 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.054 ±(99.9%) 1.241 ops/ms [Average]
  (min, avg, max) = (9.003, 9.054, 9.131), stdev = 0.068
  CI (99.9%): [7.813, 10.295] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 5.238 ops/ms
# Warmup Iteration   2: 7.903 ops/ms
# Warmup Iteration   3: 8.378 ops/ms
Iteration   1: 8.387 ops/ms
Iteration   2: 8.501 ops/ms
Iteration   3: 8.522 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.470 ±(99.9%) 1.322 ops/ms [Average]
  (min, avg, max) = (8.387, 8.470, 8.522), stdev = 0.072
  CI (99.9%): [7.149, 9.792] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 4.536 ops/ms
# Warmup Iteration   2: 5.848 ops/ms
# Warmup Iteration   3: 6.500 ops/ms
Iteration   1: 6.461 ops/ms
Iteration   2: 6.648 ops/ms
Iteration   3: 6.759 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.623 ±(99.9%) 2.740 ops/ms [Average]
  (min, avg, max) = (6.461, 6.623, 6.759), stdev = 0.150
  CI (99.9%): [3.883, 9.363] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 5.588 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 4.045 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.763 ±(99.9%) 0.017 ms/op
Iteration   1: 3.769 ±(99.9%) 0.004 ms/op
Iteration   2: 3.788 ±(99.9%) 0.004 ms/op
Iteration   3: 3.761 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.772 ±(99.9%) 0.258 ms/op [Average]
  (min, avg, max) = (3.761, 3.772, 3.788), stdev = 0.014
  CI (99.9%): [3.514, 4.030] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 5.288 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.858 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.724 ±(99.9%) 0.004 ms/op
Iteration   1: 3.567 ±(99.9%) 0.003 ms/op
Iteration   2: 3.642 ±(99.9%) 0.003 ms/op
Iteration   3: 3.607 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.605 ±(99.9%) 0.678 ms/op [Average]
  (min, avg, max) = (3.567, 3.605, 3.642), stdev = 0.037
  CI (99.9%): [2.928, 4.283] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 5.446 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.065 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.874 ±(99.9%) 0.004 ms/op
Iteration   1: 3.800 ±(99.9%) 0.005 ms/op
Iteration   2: 3.665 ±(99.9%) 0.004 ms/op
Iteration   3: 3.688 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.718 ±(99.9%) 1.322 ms/op [Average]
  (min, avg, max) = (3.665, 3.718, 3.800), stdev = 0.072
  CI (99.9%): [2.396, 5.040] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 7.573 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 5.295 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.980 ±(99.9%) 0.019 ms/op
Iteration   1: 4.872 ±(99.9%) 0.010 ms/op
Iteration   2: 4.934 ±(99.9%) 0.028 ms/op
Iteration   3: 4.787 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.864 ±(99.9%) 1.348 ms/op [Average]
  (min, avg, max) = (4.787, 4.864, 4.934), stdev = 0.074
  CI (99.9%): [3.517, 6.212] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 5.635 ±(99.9%) 0.065 ms/op
# Warmup Iteration   2: 4.038 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.838 ±(99.9%) 0.011 ms/op
Iteration   1: 3.776 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.157 ms/op
                 createUser·p0.50:   3.678 ms/op
                 createUser·p0.90:   4.497 ms/op
                 createUser·p0.95:   4.760 ms/op
                 createUser·p0.99:   6.136 ms/op
                 createUser·p0.999:  10.617 ms/op
                 createUser·p0.9999: 14.779 ms/op
                 createUser·p1.00:   15.385 ms/op

Iteration   2: 3.642 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.709 ms/op
                 createUser·p0.50:   3.588 ms/op
                 createUser·p0.90:   4.252 ms/op
                 createUser·p0.95:   4.571 ms/op
                 createUser·p0.99:   5.997 ms/op
                 createUser·p0.999:  10.848 ms/op
                 createUser·p0.9999: 15.788 ms/op
                 createUser·p1.00:   17.629 ms/op

Iteration   3: 3.808 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.843 ms/op
                 createUser·p0.50:   3.731 ms/op
                 createUser·p0.90:   4.497 ms/op
                 createUser·p0.95:   4.751 ms/op
                 createUser·p0.99:   6.242 ms/op
                 createUser·p0.999:  11.501 ms/op
                 createUser·p0.9999: 30.789 ms/op
                 createUser·p1.00:   31.130 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 256738
  mean =      3.740 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4071 
    [ 2.500,  5.000) = 244733 
    [ 5.000,  7.500) = 6938 
    [ 7.500, 10.000) = 651 
    [10.000, 12.500) = 168 
    [12.500, 15.000) = 90 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 34 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 10 
    [30.000, 32.500) = 22 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.709 ms/op
     p(50.0000) =      3.658 ms/op
     p(90.0000) =      4.440 ms/op
     p(95.0000) =      4.710 ms/op
     p(99.0000) =      6.119 ms/op
     p(99.9000) =     10.977 ms/op
     p(99.9900) =     29.807 ms/op
     p(99.9990) =     31.027 ms/op
     p(99.9999) =     31.130 ms/op
    p(100.0000) =     31.130 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 4.925 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.815 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.684 ±(99.9%) 0.010 ms/op
Iteration   1: 3.660 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.919 ms/op
                 existUser·p0.50:   3.584 ms/op
                 existUser·p0.90:   4.293 ms/op
                 existUser·p0.95:   4.571 ms/op
                 existUser·p0.99:   6.156 ms/op
                 existUser·p0.999:  10.332 ms/op
                 existUser·p0.9999: 16.749 ms/op
                 existUser·p1.00:   17.072 ms/op

Iteration   2: 3.515 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.850 ms/op
                 existUser·p0.50:   3.482 ms/op
                 existUser·p0.90:   4.092 ms/op
                 existUser·p0.95:   4.358 ms/op
                 existUser·p0.99:   5.702 ms/op
                 existUser·p0.999:  14.727 ms/op
                 existUser·p0.9999: 21.288 ms/op
                 existUser·p1.00:   21.791 ms/op

Iteration   3: 3.602 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.872 ms/op
                 existUser·p0.50:   3.535 ms/op
                 existUser·p0.90:   4.243 ms/op
                 existUser·p0.95:   4.571 ms/op
                 existUser·p0.99:   6.070 ms/op
                 existUser·p0.999:  11.078 ms/op
                 existUser·p0.9999: 19.694 ms/op
                 existUser·p1.00:   19.792 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 267333
  mean =      3.591 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8370 
    [ 2.500,  5.000) = 252533 
    [ 5.000,  7.500) = 5186 
    [ 7.500, 10.000) = 737 
    [10.000, 12.500) = 265 
    [12.500, 15.000) = 96 
    [15.000, 17.500) = 100 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.850 ms/op
     p(50.0000) =      3.535 ms/op
     p(90.0000) =      4.211 ms/op
     p(95.0000) =      4.514 ms/op
     p(99.0000) =      5.986 ms/op
     p(99.9000) =     12.217 ms/op
     p(99.9900) =     19.759 ms/op
     p(99.9990) =     21.648 ms/op
     p(99.9999) =     21.791 ms/op
    p(100.0000) =     21.791 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.291 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 4.117 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.850 ±(99.9%) 0.010 ms/op
Iteration   1: 3.879 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.219 ms/op
                 getUser·p0.50:   3.781 ms/op
                 getUser·p0.90:   4.555 ms/op
                 getUser·p0.95:   5.022 ms/op
                 getUser·p0.99:   6.767 ms/op
                 getUser·p0.999:  12.359 ms/op
                 getUser·p0.9999: 16.933 ms/op
                 getUser·p1.00:   17.465 ms/op

Iteration   2: 3.727 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.014 ms/op
                 getUser·p0.50:   3.666 ms/op
                 getUser·p0.90:   4.465 ms/op
                 getUser·p0.95:   4.932 ms/op
                 getUser·p0.99:   6.611 ms/op
                 getUser·p0.999:  10.076 ms/op
                 getUser·p0.9999: 19.098 ms/op
                 getUser·p1.00:   19.661 ms/op

Iteration   3: 3.805 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.031 ms/op
                 getUser·p0.50:   3.715 ms/op
                 getUser·p0.90:   4.555 ms/op
                 getUser·p0.95:   4.932 ms/op
                 getUser·p0.99:   6.521 ms/op
                 getUser·p0.999:  10.411 ms/op
                 getUser·p0.9999: 28.888 ms/op
                 getUser·p1.00:   29.327 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 252542
  mean =      3.803 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7355 
    [ 2.500,  5.000) = 233308 
    [ 5.000,  7.500) = 10412 
    [ 7.500, 10.000) = 1058 
    [10.000, 12.500) = 195 
    [12.500, 15.000) = 68 
    [15.000, 17.500) = 81 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      1.014 ms/op
     p(50.0000) =      3.719 ms/op
     p(90.0000) =      4.530 ms/op
     p(95.0000) =      4.956 ms/op
     p(99.0000) =      6.636 ms/op
     p(99.9000) =     11.715 ms/op
     p(99.9900) =     25.256 ms/op
     p(99.9990) =     29.195 ms/op
     p(99.9999) =     29.327 ms/op
    p(100.0000) =     29.327 ms/op


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
# Warmup Iteration   1: 6.138 ±(99.9%) 0.073 ms/op
# Warmup Iteration   2: 5.338 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.940 ±(99.9%) 0.015 ms/op
Iteration   1: 4.917 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.731 ms/op
                 listUser·p0.50:   4.645 ms/op
                 listUser·p0.90:   6.480 ms/op
                 listUser·p0.95:   7.307 ms/op
                 listUser·p0.99:   9.667 ms/op
                 listUser·p0.999:  17.224 ms/op
                 listUser·p0.9999: 22.577 ms/op
                 listUser·p1.00:   25.297 ms/op

Iteration   2: 4.896 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.470 ms/op
                 listUser·p0.50:   4.620 ms/op
                 listUser·p0.90:   6.300 ms/op
                 listUser·p0.95:   7.258 ms/op
                 listUser·p0.99:   9.257 ms/op
                 listUser·p0.999:  18.722 ms/op
                 listUser·p0.9999: 31.646 ms/op
                 listUser·p1.00:   32.702 ms/op

Iteration   3: 4.906 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.161 ms/op
                 listUser·p0.50:   4.637 ms/op
                 listUser·p0.90:   6.349 ms/op
                 listUser·p0.95:   7.324 ms/op
                 listUser·p0.99:   9.290 ms/op
                 listUser·p0.999:  19.694 ms/op
                 listUser·p0.9999: 22.364 ms/op
                 listUser·p1.00:   22.577 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 195695
  mean =      4.906 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 568 
    [ 2.500,  5.000) = 136229 
    [ 5.000,  7.500) = 50710 
    [ 7.500, 10.000) = 6851 
    [10.000, 12.500) = 801 
    [12.500, 15.000) = 174 
    [15.000, 17.500) = 107 
    [17.500, 20.000) = 115 
    [20.000, 22.500) = 113 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 8 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.161 ms/op
     p(50.0000) =      4.637 ms/op
     p(90.0000) =      6.382 ms/op
     p(95.0000) =      7.299 ms/op
     p(99.0000) =      9.388 ms/op
     p(99.9000) =     18.632 ms/op
     p(99.9900) =     22.807 ms/op
     p(99.9990) =     32.577 ms/op
     p(99.9999) =     32.702 ms/op
    p(100.0000) =     32.702 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.661 ± 3.348  ops/ms
ClientGrpc.existUser                       thrpt       3   9.054 ± 1.241  ops/ms
ClientGrpc.getUser                         thrpt       3   8.470 ± 1.322  ops/ms
ClientGrpc.listUser                        thrpt       3   6.623 ± 2.740  ops/ms
ClientGrpc.createUser                       avgt       3   3.772 ± 0.258   ms/op
ClientGrpc.existUser                        avgt       3   3.605 ± 0.678   ms/op
ClientGrpc.getUser                          avgt       3   3.718 ± 1.322   ms/op
ClientGrpc.listUser                         avgt       3   4.864 ± 1.348   ms/op
ClientGrpc.createUser                     sample  256738   3.740 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.709           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.658           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.440           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.710           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.119           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.977           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          29.807           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          31.130           ms/op
ClientGrpc.existUser                      sample  267333   3.591 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.850           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.535           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.211           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.514           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.986           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          12.217           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.759           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.791           ms/op
ClientGrpc.getUser                        sample  252542   3.803 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           1.014           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.719           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.530           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.956           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.636           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.715           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          25.256           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          29.327           ms/op
ClientGrpc.listUser                       sample  195695   4.906 ± 0.010   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.161           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.637           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.382           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.299           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.388           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.632           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.807           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          32.702           ms/op
