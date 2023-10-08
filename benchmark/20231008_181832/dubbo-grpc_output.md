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
# Warmup Iteration   1: 3.190 ops/ms
# Warmup Iteration   2: 6.623 ops/ms
# Warmup Iteration   3: 8.130 ops/ms
Iteration   1: 8.406 ops/ms
Iteration   2: 8.701 ops/ms
Iteration   3: 8.447 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.518 ±(99.9%) 2.920 ops/ms [Average]
  (min, avg, max) = (8.406, 8.518, 8.701), stdev = 0.160
  CI (99.9%): [5.598, 11.438] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:04
# Fork: 1 of 1
# Warmup Iteration   1: 5.875 ops/ms
# Warmup Iteration   2: 8.687 ops/ms
# Warmup Iteration   3: 8.732 ops/ms
Iteration   1: 8.883 ops/ms
Iteration   2: 9.095 ops/ms
Iteration   3: 8.909 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.962 ±(99.9%) 2.104 ops/ms [Average]
  (min, avg, max) = (8.883, 8.962, 9.095), stdev = 0.115
  CI (99.9%): [6.858, 11.066] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 5.364 ops/ms
# Warmup Iteration   2: 8.150 ops/ms
# Warmup Iteration   3: 8.443 ops/ms
Iteration   1: 8.643 ops/ms
Iteration   2: 8.681 ops/ms
Iteration   3: 8.579 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.634 ±(99.9%) 0.941 ops/ms [Average]
  (min, avg, max) = (8.579, 8.634, 8.681), stdev = 0.052
  CI (99.9%): [7.693, 9.576] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 4.307 ops/ms
# Warmup Iteration   2: 6.363 ops/ms
# Warmup Iteration   3: 6.764 ops/ms
Iteration   1: 6.866 ops/ms
Iteration   2: 6.769 ops/ms
Iteration   3: 6.631 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.755 ±(99.9%) 2.156 ops/ms [Average]
  (min, avg, max) = (6.631, 6.755, 6.866), stdev = 0.118
  CI (99.9%): [4.600, 8.911] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 4.954 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.971 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.790 ±(99.9%) 0.009 ms/op
Iteration   1: 3.762 ±(99.9%) 0.004 ms/op
Iteration   2: 3.713 ±(99.9%) 0.004 ms/op
Iteration   3: 3.738 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.738 ±(99.9%) 0.442 ms/op [Average]
  (min, avg, max) = (3.713, 3.738, 3.762), stdev = 0.024
  CI (99.9%): [3.296, 4.180] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 5.195 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.695 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.569 ±(99.9%) 0.003 ms/op
Iteration   1: 3.525 ±(99.9%) 0.004 ms/op
Iteration   2: 3.570 ±(99.9%) 0.003 ms/op
Iteration   3: 3.571 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.555 ±(99.9%) 0.482 ms/op [Average]
  (min, avg, max) = (3.525, 3.555, 3.571), stdev = 0.026
  CI (99.9%): [3.073, 4.038] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 4.870 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.938 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.681 ±(99.9%) 0.004 ms/op
Iteration   1: 3.797 ±(99.9%) 0.004 ms/op
Iteration   2: 3.760 ±(99.9%) 0.003 ms/op
Iteration   3: 3.751 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.769 ±(99.9%) 0.448 ms/op [Average]
  (min, avg, max) = (3.751, 3.769, 3.797), stdev = 0.025
  CI (99.9%): [3.321, 4.217] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 6.857 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 4.883 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 4.736 ±(99.9%) 0.022 ms/op
Iteration   1: 4.801 ±(99.9%) 0.015 ms/op
Iteration   2: 4.705 ±(99.9%) 0.009 ms/op
Iteration   3: 4.694 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.733 ±(99.9%) 1.070 ms/op [Average]
  (min, avg, max) = (4.694, 4.733, 4.801), stdev = 0.059
  CI (99.9%): [3.663, 5.803] (assumes normal distribution)


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
# Warmup Iteration   1: 5.498 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 4.010 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.760 ±(99.9%) 0.009 ms/op
Iteration   1: 3.773 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.174 ms/op
                 createUser·p0.50:   3.715 ms/op
                 createUser·p0.90:   4.489 ms/op
                 createUser·p0.95:   4.776 ms/op
                 createUser·p0.99:   6.070 ms/op
                 createUser·p0.999:  11.567 ms/op
                 createUser·p0.9999: 14.975 ms/op
                 createUser·p1.00:   15.204 ms/op

Iteration   2: 3.764 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.987 ms/op
                 createUser·p0.50:   3.703 ms/op
                 createUser·p0.90:   4.489 ms/op
                 createUser·p0.95:   4.809 ms/op
                 createUser·p0.99:   6.583 ms/op
                 createUser·p0.999:  14.404 ms/op
                 createUser·p0.9999: 16.892 ms/op
                 createUser·p1.00:   17.564 ms/op

Iteration   3: 3.711 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.434 ms/op
                 createUser·p0.50:   3.654 ms/op
                 createUser·p0.90:   4.375 ms/op
                 createUser·p0.95:   4.686 ms/op
                 createUser·p0.99:   6.218 ms/op
                 createUser·p0.999:  13.986 ms/op
                 createUser·p0.9999: 28.136 ms/op
                 createUser·p1.00:   31.162 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 256137
  mean =      3.749 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7869 
    [ 2.500,  5.000) = 239975 
    [ 5.000,  7.500) = 7041 
    [ 7.500, 10.000) = 785 
    [10.000, 12.500) = 189 
    [12.500, 15.000) = 164 
    [15.000, 17.500) = 49 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 24 
    [27.500, 30.000) = 7 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.434 ms/op
     p(50.0000) =      3.690 ms/op
     p(90.0000) =      4.448 ms/op
     p(95.0000) =      4.760 ms/op
     p(99.0000) =      6.275 ms/op
     p(99.9000) =     12.937 ms/op
     p(99.9900) =     27.112 ms/op
     p(99.9990) =     29.524 ms/op
     p(99.9999) =     31.162 ms/op
    p(100.0000) =     31.162 ms/op


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
# Warmup Iteration   1: 5.240 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 3.764 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.614 ±(99.9%) 0.008 ms/op
Iteration   1: 3.590 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.784 ms/op
                 existUser·p0.50:   3.523 ms/op
                 existUser·p0.90:   4.227 ms/op
                 existUser·p0.95:   4.596 ms/op
                 existUser·p0.99:   5.825 ms/op
                 existUser·p0.999:  9.939 ms/op
                 existUser·p0.9999: 19.628 ms/op
                 existUser·p1.00:   19.890 ms/op

Iteration   2: 3.565 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.856 ms/op
                 existUser·p0.50:   3.514 ms/op
                 existUser·p0.90:   4.260 ms/op
                 existUser·p0.95:   4.612 ms/op
                 existUser·p0.99:   6.185 ms/op
                 existUser·p0.999:  11.256 ms/op
                 existUser·p0.9999: 17.762 ms/op
                 existUser·p1.00:   18.022 ms/op

Iteration   3: 3.632 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.722 ms/op
                 existUser·p0.50:   3.543 ms/op
                 existUser·p0.90:   4.301 ms/op
                 existUser·p0.95:   4.588 ms/op
                 existUser·p0.99:   6.160 ms/op
                 existUser·p0.999:  13.583 ms/op
                 existUser·p0.9999: 19.431 ms/op
                 existUser·p1.00:   19.497 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 267134
  mean =      3.595 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 301 
    [ 1.250,  2.500) = 8758 
    [ 2.500,  3.750) = 171711 
    [ 3.750,  5.000) = 79468 
    [ 5.000,  6.250) = 4608 
    [ 6.250,  7.500) = 1041 
    [ 7.500,  8.750) = 529 
    [ 8.750, 10.000) = 223 
    [10.000, 11.250) = 195 
    [11.250, 12.500) = 81 
    [12.500, 13.750) = 44 
    [13.750, 15.000) = 43 
    [15.000, 16.250) = 21 
    [16.250, 17.500) = 11 
    [17.500, 18.750) = 47 

  Percentiles, ms/op:
      p(0.0000) =      0.722 ms/op
     p(50.0000) =      3.527 ms/op
     p(90.0000) =      4.260 ms/op
     p(95.0000) =      4.596 ms/op
     p(99.0000) =      6.013 ms/op
     p(99.9000) =     11.502 ms/op
     p(99.9900) =     19.399 ms/op
     p(99.9990) =     19.835 ms/op
     p(99.9999) =     19.890 ms/op
    p(100.0000) =     19.890 ms/op


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
# Warmup Iteration   1: 5.414 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 3.974 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.777 ±(99.9%) 0.009 ms/op
Iteration   1: 3.793 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.862 ms/op
                 getUser·p0.50:   3.711 ms/op
                 getUser·p0.90:   4.506 ms/op
                 getUser·p0.95:   4.825 ms/op
                 getUser·p0.99:   6.488 ms/op
                 getUser·p0.999:  9.994 ms/op
                 getUser·p0.9999: 14.708 ms/op
                 getUser·p1.00:   15.008 ms/op

Iteration   2: 3.731 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.042 ms/op
                 getUser·p0.50:   3.654 ms/op
                 getUser·p0.90:   4.383 ms/op
                 getUser·p0.95:   4.719 ms/op
                 getUser·p0.99:   6.242 ms/op
                 getUser·p0.999:  8.475 ms/op
                 getUser·p0.9999: 15.410 ms/op
                 getUser·p1.00:   17.826 ms/op

Iteration   3: 3.743 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.506 ms/op
                 getUser·p0.50:   3.670 ms/op
                 getUser·p0.90:   4.424 ms/op
                 getUser·p0.95:   4.735 ms/op
                 getUser·p0.99:   6.373 ms/op
                 getUser·p0.999:  12.740 ms/op
                 getUser·p0.9999: 32.291 ms/op
                 getUser·p1.00:   32.571 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 255560
  mean =      3.755 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5411 
    [ 2.500,  5.000) = 241865 
    [ 5.000,  7.500) = 7030 
    [ 7.500, 10.000) = 1009 
    [10.000, 12.500) = 59 
    [12.500, 15.000) = 81 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 30 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.506 ms/op
     p(50.0000) =      3.678 ms/op
     p(90.0000) =      4.440 ms/op
     p(95.0000) =      4.768 ms/op
     p(99.0000) =      6.349 ms/op
     p(99.9000) =      9.929 ms/op
     p(99.9900) =     31.293 ms/op
     p(99.9990) =     32.488 ms/op
     p(99.9999) =     32.571 ms/op
    p(100.0000) =     32.571 ms/op


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
# Warmup Iteration   1: 6.954 ±(99.9%) 0.079 ms/op
# Warmup Iteration   2: 5.236 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.867 ±(99.9%) 0.015 ms/op
Iteration   1: 4.899 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   0.976 ms/op
                 listUser·p0.50:   4.678 ms/op
                 listUser·p0.90:   6.169 ms/op
                 listUser·p0.95:   7.127 ms/op
                 listUser·p0.99:   9.377 ms/op
                 listUser·p0.999:  16.052 ms/op
                 listUser·p0.9999: 19.856 ms/op
                 listUser·p1.00:   19.988 ms/op

Iteration   2: 4.741 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.294 ms/op
                 listUser·p0.50:   4.604 ms/op
                 listUser·p0.90:   5.333 ms/op
                 listUser·p0.95:   6.250 ms/op
                 listUser·p0.99:   8.167 ms/op
                 listUser·p0.999:  16.234 ms/op
                 listUser·p0.9999: 20.546 ms/op
                 listUser·p1.00:   20.709 ms/op

Iteration   3: 4.783 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.194 ms/op
                 listUser·p0.50:   4.645 ms/op
                 listUser·p0.90:   5.603 ms/op
                 listUser·p0.95:   6.357 ms/op
                 listUser·p0.99:   8.159 ms/op
                 listUser·p0.999:  19.432 ms/op
                 listUser·p0.9999: 21.889 ms/op
                 listUser·p1.00:   22.249 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 199823
  mean =      4.807 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 234 
    [ 2.500,  5.000) = 150120 
    [ 5.000,  7.500) = 44251 
    [ 7.500, 10.000) = 4408 
    [10.000, 12.500) = 389 
    [12.500, 15.000) = 107 
    [15.000, 17.500) = 163 
    [17.500, 20.000) = 92 
    [20.000, 22.500) = 59 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.976 ms/op
     p(50.0000) =      4.637 ms/op
     p(90.0000) =      5.726 ms/op
     p(95.0000) =      6.644 ms/op
     p(99.0000) =      8.569 ms/op
     p(99.9000) =     16.671 ms/op
     p(99.9900) =     21.170 ms/op
     p(99.9990) =     22.151 ms/op
     p(99.9999) =     22.249 ms/op
    p(100.0000) =     22.249 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.518 ± 2.920  ops/ms
ClientGrpc.existUser                       thrpt       3   8.962 ± 2.104  ops/ms
ClientGrpc.getUser                         thrpt       3   8.634 ± 0.941  ops/ms
ClientGrpc.listUser                        thrpt       3   6.755 ± 2.156  ops/ms
ClientGrpc.createUser                       avgt       3   3.738 ± 0.442   ms/op
ClientGrpc.existUser                        avgt       3   3.555 ± 0.482   ms/op
ClientGrpc.getUser                          avgt       3   3.769 ± 0.448   ms/op
ClientGrpc.listUser                         avgt       3   4.733 ± 1.070   ms/op
ClientGrpc.createUser                     sample  256137   3.749 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.434           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.690           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.448           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.760           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.275           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.937           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          27.112           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          31.162           ms/op
ClientGrpc.existUser                      sample  267134   3.595 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.722           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.527           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.260           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.596           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.013           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.502           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.399           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.890           ms/op
ClientGrpc.getUser                        sample  255560   3.755 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.506           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.678           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.440           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.768           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.349           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.929           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          31.293           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          32.571           ms/op
ClientGrpc.listUser                       sample  199823   4.807 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.976           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.637           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.726           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.644           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.569           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.671           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.170           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          22.249           ms/op
