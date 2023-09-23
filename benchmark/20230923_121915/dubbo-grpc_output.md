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
# Warmup Iteration   1: 3.095 ops/ms
# Warmup Iteration   2: 6.746 ops/ms
# Warmup Iteration   3: 7.905 ops/ms
Iteration   1: 8.215 ops/ms
Iteration   2: 8.265 ops/ms
Iteration   3: 8.329 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.270 ±(99.9%) 1.045 ops/ms [Average]
  (min, avg, max) = (8.215, 8.270, 8.329), stdev = 0.057
  CI (99.9%): [7.225, 9.314] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.904 ops/ms
# Warmup Iteration   2: 8.466 ops/ms
# Warmup Iteration   3: 8.913 ops/ms
Iteration   1: 8.952 ops/ms
Iteration   2: 8.965 ops/ms
Iteration   3: 9.143 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.020 ±(99.9%) 1.949 ops/ms [Average]
  (min, avg, max) = (8.952, 9.020, 9.143), stdev = 0.107
  CI (99.9%): [7.072, 10.969] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 5.468 ops/ms
# Warmup Iteration   2: 8.051 ops/ms
# Warmup Iteration   3: 8.383 ops/ms
Iteration   1: 8.323 ops/ms
Iteration   2: 8.713 ops/ms
Iteration   3: 8.640 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.559 ±(99.9%) 3.777 ops/ms [Average]
  (min, avg, max) = (8.323, 8.559, 8.713), stdev = 0.207
  CI (99.9%): [4.782, 12.335] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 4.089 ops/ms
# Warmup Iteration   2: 6.273 ops/ms
# Warmup Iteration   3: 6.810 ops/ms
Iteration   1: 6.800 ops/ms
Iteration   2: 6.824 ops/ms
Iteration   3: 7.011 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.878 ±(99.9%) 2.107 ops/ms [Average]
  (min, avg, max) = (6.800, 6.878, 7.011), stdev = 0.116
  CI (99.9%): [4.771, 8.986] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.473 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.866 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.771 ±(99.9%) 0.010 ms/op
Iteration   1: 3.616 ±(99.9%) 0.003 ms/op
Iteration   2: 3.701 ±(99.9%) 0.003 ms/op
Iteration   3: 3.639 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.652 ±(99.9%) 0.807 ms/op [Average]
  (min, avg, max) = (3.616, 3.652, 3.701), stdev = 0.044
  CI (99.9%): [2.844, 4.459] (assumes normal distribution)


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
# Warmup Iteration   1: 4.909 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.743 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.464 ±(99.9%) 0.004 ms/op
Iteration   1: 3.533 ±(99.9%) 0.003 ms/op
Iteration   2: 3.515 ±(99.9%) 0.003 ms/op
Iteration   3: 3.484 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.511 ±(99.9%) 0.453 ms/op [Average]
  (min, avg, max) = (3.484, 3.511, 3.533), stdev = 0.025
  CI (99.9%): [3.058, 3.964] (assumes normal distribution)


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
# Warmup Iteration   1: 5.177 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.746 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.755 ±(99.9%) 0.006 ms/op
Iteration   1: 3.629 ±(99.9%) 0.006 ms/op
Iteration   2: 3.617 ±(99.9%) 0.004 ms/op
Iteration   3: 3.670 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.639 ±(99.9%) 0.509 ms/op [Average]
  (min, avg, max) = (3.617, 3.639, 3.670), stdev = 0.028
  CI (99.9%): [3.129, 4.148] (assumes normal distribution)


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
# Warmup Iteration   1: 6.552 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.825 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.665 ±(99.9%) 0.012 ms/op
Iteration   1: 4.633 ±(99.9%) 0.013 ms/op
Iteration   2: 4.607 ±(99.9%) 0.013 ms/op
Iteration   3: 4.568 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.602 ±(99.9%) 0.598 ms/op [Average]
  (min, avg, max) = (4.568, 4.602, 4.633), stdev = 0.033
  CI (99.9%): [4.004, 5.201] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 5.250 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 3.850 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.715 ±(99.9%) 0.009 ms/op
Iteration   1: 3.684 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.928 ms/op
                 createUser·p0.50:   3.641 ms/op
                 createUser·p0.90:   4.432 ms/op
                 createUser·p0.95:   4.686 ms/op
                 createUser·p0.99:   5.620 ms/op
                 createUser·p0.999:  11.131 ms/op
                 createUser·p0.9999: 18.219 ms/op
                 createUser·p1.00:   18.448 ms/op

Iteration   2: 3.596 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.713 ms/op
                 createUser·p0.50:   3.543 ms/op
                 createUser·p0.90:   4.108 ms/op
                 createUser·p0.95:   4.334 ms/op
                 createUser·p0.99:   5.734 ms/op
                 createUser·p0.999:  12.550 ms/op
                 createUser·p0.9999: 20.385 ms/op
                 createUser·p1.00:   20.873 ms/op

Iteration   3: 3.683 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.932 ms/op
                 createUser·p0.50:   3.604 ms/op
                 createUser·p0.90:   4.317 ms/op
                 createUser·p0.95:   4.547 ms/op
                 createUser·p0.99:   6.103 ms/op
                 createUser·p0.999:  20.612 ms/op
                 createUser·p0.9999: 28.813 ms/op
                 createUser·p1.00:   29.196 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 262907
  mean =      3.654 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5725 
    [ 2.500,  5.000) = 252427 
    [ 5.000,  7.500) = 3668 
    [ 7.500, 10.000) = 617 
    [10.000, 12.500) = 148 
    [12.500, 15.000) = 96 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 83 
    [20.000, 22.500) = 65 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.713 ms/op
     p(50.0000) =      3.592 ms/op
     p(90.0000) =      4.293 ms/op
     p(95.0000) =      4.563 ms/op
     p(99.0000) =      5.775 ms/op
     p(99.9000) =     13.684 ms/op
     p(99.9900) =     28.368 ms/op
     p(99.9990) =     29.134 ms/op
     p(99.9999) =     29.196 ms/op
    p(100.0000) =     29.196 ms/op


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
# Warmup Iteration   1: 5.179 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.802 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.591 ±(99.9%) 0.008 ms/op
Iteration   1: 3.478 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.862 ms/op
                 existUser·p0.50:   3.473 ms/op
                 existUser·p0.90:   4.194 ms/op
                 existUser·p0.95:   4.497 ms/op
                 existUser·p0.99:   5.431 ms/op
                 existUser·p0.999:  9.306 ms/op
                 existUser·p0.9999: 18.547 ms/op
                 existUser·p1.00:   23.593 ms/op

Iteration   2: 3.514 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.942 ms/op
                 existUser·p0.50:   3.465 ms/op
                 existUser·p0.90:   4.039 ms/op
                 existUser·p0.95:   4.194 ms/op
                 existUser·p0.99:   4.923 ms/op
                 existUser·p0.999:  14.334 ms/op
                 existUser·p0.9999: 26.866 ms/op
                 existUser·p1.00:   27.230 ms/op

Iteration   3: 3.474 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.885 ms/op
                 existUser·p0.50:   3.469 ms/op
                 existUser·p0.90:   4.047 ms/op
                 existUser·p0.95:   4.211 ms/op
                 existUser·p0.99:   4.997 ms/op
                 existUser·p0.999:  11.829 ms/op
                 existUser·p0.9999: 24.110 ms/op
                 existUser·p1.00:   24.445 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 275267
  mean =      3.489 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10522 
    [ 2.500,  5.000) = 261617 
    [ 5.000,  7.500) = 2371 
    [ 7.500, 10.000) = 417 
    [10.000, 12.500) = 108 
    [12.500, 15.000) = 72 
    [15.000, 17.500) = 75 
    [17.500, 20.000) = 47 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.862 ms/op
     p(50.0000) =      3.469 ms/op
     p(90.0000) =      4.080 ms/op
     p(95.0000) =      4.284 ms/op
     p(99.0000) =      5.136 ms/op
     p(99.9000) =     11.952 ms/op
     p(99.9900) =     24.019 ms/op
     p(99.9990) =     27.042 ms/op
     p(99.9999) =     27.230 ms/op
    p(100.0000) =     27.230 ms/op


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
# Warmup Iteration   1: 5.287 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.826 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.688 ±(99.9%) 0.011 ms/op
Iteration   1: 3.704 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.008 ms/op
                 getUser·p0.50:   3.666 ms/op
                 getUser·p0.90:   4.334 ms/op
                 getUser·p0.95:   4.588 ms/op
                 getUser·p0.99:   5.497 ms/op
                 getUser·p0.999:  10.337 ms/op
                 getUser·p0.9999: 20.152 ms/op
                 getUser·p1.00:   20.840 ms/op

Iteration   2: 3.681 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.852 ms/op
                 getUser·p0.50:   3.658 ms/op
                 getUser·p0.90:   4.284 ms/op
                 getUser·p0.95:   4.456 ms/op
                 getUser·p0.99:   5.226 ms/op
                 getUser·p0.999:  8.995 ms/op
                 getUser·p0.9999: 22.194 ms/op
                 getUser·p1.00:   22.479 ms/op

Iteration   3: 3.674 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.511 ms/op
                 getUser·p0.50:   3.613 ms/op
                 getUser·p0.90:   4.301 ms/op
                 getUser·p0.95:   4.571 ms/op
                 getUser·p0.99:   5.628 ms/op
                 getUser·p0.999:  12.467 ms/op
                 getUser·p0.9999: 23.429 ms/op
                 getUser·p1.00:   23.822 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 260288
  mean =      3.686 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4450 
    [ 2.500,  5.000) = 251627 
    [ 5.000,  7.500) = 3490 
    [ 7.500, 10.000) = 415 
    [10.000, 12.500) = 103 
    [12.500, 15.000) = 17 
    [15.000, 17.500) = 17 
    [17.500, 20.000) = 66 
    [20.000, 22.500) = 70 
    [22.500, 25.000) = 33 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.511 ms/op
     p(50.0000) =      3.645 ms/op
     p(90.0000) =      4.309 ms/op
     p(95.0000) =      4.530 ms/op
     p(99.0000) =      5.439 ms/op
     p(99.9000) =     10.502 ms/op
     p(99.9900) =     22.838 ms/op
     p(99.9990) =     23.743 ms/op
     p(99.9999) =     23.822 ms/op
    p(100.0000) =     23.822 ms/op


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
# Warmup Iteration   1: 7.635 ±(99.9%) 0.085 ms/op
# Warmup Iteration   2: 4.910 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.727 ±(99.9%) 0.013 ms/op
Iteration   1: 4.621 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.692 ms/op
                 listUser·p0.50:   4.424 ms/op
                 listUser·p0.90:   5.554 ms/op
                 listUser·p0.95:   6.799 ms/op
                 listUser·p0.99:   8.915 ms/op
                 listUser·p0.999:  16.610 ms/op
                 listUser·p0.9999: 20.747 ms/op
                 listUser·p1.00:   25.231 ms/op

Iteration   2: 4.641 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.155 ms/op
                 listUser·p0.50:   4.514 ms/op
                 listUser·p0.90:   5.448 ms/op
                 listUser·p0.95:   6.586 ms/op
                 listUser·p0.99:   7.856 ms/op
                 listUser·p0.999:  16.304 ms/op
                 listUser·p0.9999: 19.956 ms/op
                 listUser·p1.00:   21.037 ms/op

Iteration   3: 4.653 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.214 ms/op
                 listUser·p0.50:   4.530 ms/op
                 listUser·p0.90:   5.177 ms/op
                 listUser·p0.95:   6.595 ms/op
                 listUser·p0.99:   8.020 ms/op
                 listUser·p0.999:  19.699 ms/op
                 listUser·p0.9999: 31.600 ms/op
                 listUser·p1.00:   32.276 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 206908
  mean =      4.638 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 396 
    [ 2.500,  5.000) = 172692 
    [ 5.000,  7.500) = 29400 
    [ 7.500, 10.000) = 3467 
    [10.000, 12.500) = 368 
    [12.500, 15.000) = 172 
    [15.000, 17.500) = 217 
    [17.500, 20.000) = 116 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 12 
    [27.500, 30.000) = 9 
    [30.000, 32.500) = 15 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.155 ms/op
     p(50.0000) =      4.489 ms/op
     p(90.0000) =      5.382 ms/op
     p(95.0000) =      6.660 ms/op
     p(99.0000) =      8.126 ms/op
     p(99.9000) =     17.147 ms/op
     p(99.9900) =     28.670 ms/op
     p(99.9990) =     32.158 ms/op
     p(99.9999) =     32.276 ms/op
    p(100.0000) =     32.276 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.270 ± 1.045  ops/ms
ClientGrpc.existUser                       thrpt       3   9.020 ± 1.949  ops/ms
ClientGrpc.getUser                         thrpt       3   8.559 ± 3.777  ops/ms
ClientGrpc.listUser                        thrpt       3   6.878 ± 2.107  ops/ms
ClientGrpc.createUser                       avgt       3   3.652 ± 0.807   ms/op
ClientGrpc.existUser                        avgt       3   3.511 ± 0.453   ms/op
ClientGrpc.getUser                          avgt       3   3.639 ± 0.509   ms/op
ClientGrpc.listUser                         avgt       3   4.602 ± 0.598   ms/op
ClientGrpc.createUser                     sample  262907   3.654 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.713           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.592           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.293           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.563           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.775           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.684           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          28.368           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          29.196           ms/op
ClientGrpc.existUser                      sample  275267   3.489 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.862           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.469           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.080           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.284           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.136           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.952           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          24.019           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          27.230           ms/op
ClientGrpc.getUser                        sample  260288   3.686 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.511           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.645           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.309           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.530           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.439           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.502           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          22.838           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.822           ms/op
ClientGrpc.listUser                       sample  206908   4.638 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.155           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.489           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.382           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.660           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.126           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.147           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          28.670           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          32.276           ms/op
