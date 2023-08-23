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
# Warmup Iteration   1: 3.124 ops/ms
# Warmup Iteration   2: 6.777 ops/ms
# Warmup Iteration   3: 8.567 ops/ms
Iteration   1: 9.007 ops/ms
Iteration   2: 8.979 ops/ms
Iteration   3: 8.884 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.957 ±(99.9%) 1.175 ops/ms [Average]
  (min, avg, max) = (8.884, 8.957, 9.007), stdev = 0.064
  CI (99.9%): [7.781, 10.132] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:01
# Fork: 1 of 1
# Warmup Iteration   1: 6.182 ops/ms
# Warmup Iteration   2: 8.579 ops/ms
# Warmup Iteration   3: 8.819 ops/ms
Iteration   1: 9.245 ops/ms
Iteration   2: 9.345 ops/ms
Iteration   3: 9.303 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.298 ±(99.9%) 0.913 ops/ms [Average]
  (min, avg, max) = (9.245, 9.298, 9.345), stdev = 0.050
  CI (99.9%): [8.385, 10.211] (assumes normal distribution)


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
# Warmup Iteration   1: 5.591 ops/ms
# Warmup Iteration   2: 8.460 ops/ms
# Warmup Iteration   3: 8.990 ops/ms
Iteration   1: 8.730 ops/ms
Iteration   2: 8.948 ops/ms
Iteration   3: 8.808 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.829 ±(99.9%) 2.013 ops/ms [Average]
  (min, avg, max) = (8.730, 8.829, 8.948), stdev = 0.110
  CI (99.9%): [6.816, 10.841] (assumes normal distribution)


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
# Warmup Iteration   1: 4.173 ops/ms
# Warmup Iteration   2: 6.306 ops/ms
# Warmup Iteration   3: 6.761 ops/ms
Iteration   1: 6.808 ops/ms
Iteration   2: 6.804 ops/ms
Iteration   3: 6.743 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.785 ±(99.9%) 0.659 ops/ms [Average]
  (min, avg, max) = (6.743, 6.785, 6.808), stdev = 0.036
  CI (99.9%): [6.126, 7.444] (assumes normal distribution)


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
# Warmup Iteration   1: 5.280 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.778 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.714 ±(99.9%) 0.010 ms/op
Iteration   1: 3.698 ±(99.9%) 0.003 ms/op
Iteration   2: 3.623 ±(99.9%) 0.004 ms/op
Iteration   3: 3.557 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.626 ±(99.9%) 1.289 ms/op [Average]
  (min, avg, max) = (3.557, 3.626, 3.698), stdev = 0.071
  CI (99.9%): [2.337, 4.915] (assumes normal distribution)


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
# Warmup Iteration   1: 4.467 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.741 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.503 ±(99.9%) 0.003 ms/op
Iteration   1: 3.455 ±(99.9%) 0.003 ms/op
Iteration   2: 3.419 ±(99.9%) 0.004 ms/op
Iteration   3: 3.460 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.444 ±(99.9%) 0.410 ms/op [Average]
  (min, avg, max) = (3.419, 3.444, 3.460), stdev = 0.022
  CI (99.9%): [3.034, 3.855] (assumes normal distribution)


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
# Warmup Iteration   1: 5.461 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.969 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.738 ±(99.9%) 0.004 ms/op
Iteration   1: 3.724 ±(99.9%) 0.005 ms/op
Iteration   2: 3.613 ±(99.9%) 0.003 ms/op
Iteration   3: 3.648 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.662 ±(99.9%) 1.042 ms/op [Average]
  (min, avg, max) = (3.613, 3.662, 3.724), stdev = 0.057
  CI (99.9%): [2.620, 4.703] (assumes normal distribution)


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
# Warmup Iteration   1: 5.760 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 5.314 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.891 ±(99.9%) 0.032 ms/op
Iteration   1: 4.712 ±(99.9%) 0.015 ms/op
Iteration   2: 4.683 ±(99.9%) 0.019 ms/op
Iteration   3: 4.782 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.725 ±(99.9%) 0.932 ms/op [Average]
  (min, avg, max) = (4.683, 4.725, 4.782), stdev = 0.051
  CI (99.9%): [3.794, 5.657] (assumes normal distribution)


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
# Warmup Iteration   1: 5.446 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 4.051 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.709 ±(99.9%) 0.008 ms/op
Iteration   1: 3.654 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.757 ms/op
                 createUser·p0.50:   3.596 ms/op
                 createUser·p0.90:   4.301 ms/op
                 createUser·p0.95:   4.760 ms/op
                 createUser·p0.99:   5.911 ms/op
                 createUser·p0.999:  10.222 ms/op
                 createUser·p0.9999: 20.922 ms/op
                 createUser·p1.00:   21.135 ms/op

Iteration   2: 3.643 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.922 ms/op
                 createUser·p0.50:   3.604 ms/op
                 createUser·p0.90:   4.350 ms/op
                 createUser·p0.95:   4.719 ms/op
                 createUser·p0.99:   5.964 ms/op
                 createUser·p0.999:  12.011 ms/op
                 createUser·p0.9999: 21.936 ms/op
                 createUser·p1.00:   22.479 ms/op

Iteration   3: 3.632 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.174 ms/op
                 createUser·p0.50:   3.568 ms/op
                 createUser·p0.90:   4.104 ms/op
                 createUser·p0.95:   4.342 ms/op
                 createUser·p0.99:   5.800 ms/op
                 createUser·p0.999:  12.517 ms/op
                 createUser·p0.9999: 25.231 ms/op
                 createUser·p1.00:   26.640 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 263686
  mean =      3.643 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8079 
    [ 2.500,  5.000) = 248254 
    [ 5.000,  7.500) = 6291 
    [ 7.500, 10.000) = 635 
    [10.000, 12.500) = 209 
    [12.500, 15.000) = 58 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 60 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 26 

  Percentiles, ms/op:
      p(0.0000) =      0.757 ms/op
     p(50.0000) =      3.588 ms/op
     p(90.0000) =      4.243 ms/op
     p(95.0000) =      4.628 ms/op
     p(99.0000) =      5.890 ms/op
     p(99.9000) =     12.162 ms/op
     p(99.9900) =     24.990 ms/op
     p(99.9990) =     25.877 ms/op
     p(99.9999) =     26.640 ms/op
    p(100.0000) =     26.640 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 5.124 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.649 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.497 ±(99.9%) 0.008 ms/op
Iteration   1: 3.493 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.920 ms/op
                 existUser·p0.50:   3.432 ms/op
                 existUser·p0.90:   4.100 ms/op
                 existUser·p0.95:   4.383 ms/op
                 existUser·p0.99:   5.677 ms/op
                 existUser·p0.999:  8.805 ms/op
                 existUser·p0.9999: 14.972 ms/op
                 existUser·p1.00:   15.368 ms/op

Iteration   2: 3.459 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.781 ms/op
                 existUser·p0.50:   3.408 ms/op
                 existUser·p0.90:   3.961 ms/op
                 existUser·p0.95:   4.260 ms/op
                 existUser·p0.99:   5.501 ms/op
                 existUser·p0.999:  9.242 ms/op
                 existUser·p0.9999: 18.877 ms/op
                 existUser·p1.00:   20.873 ms/op

Iteration   3: 3.459 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.586 ms/op
                 existUser·p0.50:   3.432 ms/op
                 existUser·p0.90:   4.043 ms/op
                 existUser·p0.95:   4.293 ms/op
                 existUser·p0.99:   5.521 ms/op
                 existUser·p0.999:  10.081 ms/op
                 existUser·p0.9999: 42.237 ms/op
                 existUser·p1.00:   42.729 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 276590
  mean =      3.470 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 271731 
    [ 5.000, 10.000) = 4643 
    [10.000, 15.000) = 77 
    [15.000, 20.000) = 72 
    [20.000, 25.000) = 4 
    [25.000, 30.000) = 36 
    [30.000, 35.000) = 2 
    [35.000, 40.000) = 2 
    [40.000, 45.000) = 23 

  Percentiles, ms/op:
      p(0.0000) =      0.586 ms/op
     p(50.0000) =      3.424 ms/op
     p(90.0000) =      4.030 ms/op
     p(95.0000) =      4.317 ms/op
     p(99.0000) =      5.562 ms/op
     p(99.9000) =      9.159 ms/op
     p(99.9900) =     31.112 ms/op
     p(99.9990) =     42.614 ms/op
     p(99.9999) =     42.729 ms/op
    p(100.0000) =     42.729 ms/op


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
# Warmup Iteration   1: 5.114 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 3.846 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.667 ±(99.9%) 0.007 ms/op
Iteration   1: 3.614 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.737 ms/op
                 getUser·p0.50:   3.588 ms/op
                 getUser·p0.90:   4.342 ms/op
                 getUser·p0.95:   4.653 ms/op
                 getUser·p0.99:   5.874 ms/op
                 getUser·p0.999:  9.454 ms/op
                 getUser·p0.9999: 14.352 ms/op
                 getUser·p1.00:   14.631 ms/op

Iteration   2: 3.591 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.845 ms/op
                 getUser·p0.50:   3.551 ms/op
                 getUser·p0.90:   4.035 ms/op
                 getUser·p0.95:   4.399 ms/op
                 getUser·p0.99:   5.661 ms/op
                 getUser·p0.999:  8.988 ms/op
                 getUser·p0.9999: 22.872 ms/op
                 getUser·p1.00:   23.036 ms/op

Iteration   3: 3.643 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.901 ms/op
                 getUser·p0.50:   3.600 ms/op
                 getUser·p0.90:   4.301 ms/op
                 getUser·p0.95:   4.588 ms/op
                 getUser·p0.99:   5.923 ms/op
                 getUser·p0.999:  11.586 ms/op
                 getUser·p0.9999: 18.416 ms/op
                 getUser·p1.00:   18.907 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 265718
  mean =      3.616 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9972 
    [ 2.500,  5.000) = 249534 
    [ 5.000,  7.500) = 5255 
    [ 7.500, 10.000) = 745 
    [10.000, 12.500) = 52 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 39 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.737 ms/op
     p(50.0000) =      3.576 ms/op
     p(90.0000) =      4.243 ms/op
     p(95.0000) =      4.571 ms/op
     p(99.0000) =      5.825 ms/op
     p(99.9000) =      9.634 ms/op
     p(99.9900) =     22.296 ms/op
     p(99.9990) =     22.949 ms/op
     p(99.9999) =     23.036 ms/op
    p(100.0000) =     23.036 ms/op


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
# Warmup Iteration   1: 5.894 ±(99.9%) 0.067 ms/op
# Warmup Iteration   2: 5.199 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.785 ±(99.9%) 0.014 ms/op
Iteration   1: 4.798 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.882 ms/op
                 listUser·p0.50:   4.612 ms/op
                 listUser·p0.90:   5.931 ms/op
                 listUser·p0.95:   6.944 ms/op
                 listUser·p0.99:   8.684 ms/op
                 listUser·p0.999:  15.445 ms/op
                 listUser·p0.9999: 19.923 ms/op
                 listUser·p1.00:   20.414 ms/op

Iteration   2: 4.758 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.323 ms/op
                 listUser·p0.50:   4.563 ms/op
                 listUser·p0.90:   5.865 ms/op
                 listUser·p0.95:   6.906 ms/op
                 listUser·p0.99:   8.618 ms/op
                 listUser·p0.999:  17.269 ms/op
                 listUser·p0.9999: 19.423 ms/op
                 listUser·p1.00:   22.643 ms/op

Iteration   3: 4.817 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.143 ms/op
                 listUser·p0.50:   4.612 ms/op
                 listUser·p0.90:   5.964 ms/op
                 listUser·p0.95:   7.029 ms/op
                 listUser·p0.99:   8.765 ms/op
                 listUser·p0.999:  18.863 ms/op
                 listUser·p0.9999: 21.552 ms/op
                 listUser·p1.00:   22.184 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 200265
  mean =      4.791 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 230 
    [ 2.500,  5.000) = 152186 
    [ 5.000,  7.500) = 41878 
    [ 7.500, 10.000) = 4990 
    [10.000, 12.500) = 538 
    [12.500, 15.000) = 119 
    [15.000, 17.500) = 142 
    [17.500, 20.000) = 143 
    [20.000, 22.500) = 37 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.143 ms/op
     p(50.0000) =      4.596 ms/op
     p(90.0000) =      5.923 ms/op
     p(95.0000) =      6.971 ms/op
     p(99.0000) =      8.673 ms/op
     p(99.9000) =     17.260 ms/op
     p(99.9900) =     21.328 ms/op
     p(99.9990) =     22.609 ms/op
     p(99.9999) =     22.643 ms/op
    p(100.0000) =     22.643 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.957 ± 1.175  ops/ms
ClientGrpc.existUser                       thrpt       3   9.298 ± 0.913  ops/ms
ClientGrpc.getUser                         thrpt       3   8.829 ± 2.013  ops/ms
ClientGrpc.listUser                        thrpt       3   6.785 ± 0.659  ops/ms
ClientGrpc.createUser                       avgt       3   3.626 ± 1.289   ms/op
ClientGrpc.existUser                        avgt       3   3.444 ± 0.410   ms/op
ClientGrpc.getUser                          avgt       3   3.662 ± 1.042   ms/op
ClientGrpc.listUser                         avgt       3   4.725 ± 0.932   ms/op
ClientGrpc.createUser                     sample  263686   3.643 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.757           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.588           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.243           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.628           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.890           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.162           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          24.990           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          26.640           ms/op
ClientGrpc.existUser                      sample  276590   3.470 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.586           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.424           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.030           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.317           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.562           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.159           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          31.112           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          42.729           ms/op
ClientGrpc.getUser                        sample  265718   3.616 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.737           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.576           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.243           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.571           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.825           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.634           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          22.296           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.036           ms/op
ClientGrpc.listUser                       sample  200265   4.791 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.143           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.596           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.923           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.971           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.673           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.260           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.328           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          22.643           ms/op
