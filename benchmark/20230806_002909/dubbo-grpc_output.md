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
# Warmup Iteration   1: 3.403 ops/ms
# Warmup Iteration   2: 7.079 ops/ms
# Warmup Iteration   3: 8.291 ops/ms
Iteration   1: 8.378 ops/ms
Iteration   2: 8.455 ops/ms
Iteration   3: 8.518 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.451 ±(99.9%) 1.281 ops/ms [Average]
  (min, avg, max) = (8.378, 8.451, 8.518), stdev = 0.070
  CI (99.9%): [7.170, 9.732] (assumes normal distribution)


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
# Warmup Iteration   1: 6.018 ops/ms
# Warmup Iteration   2: 8.635 ops/ms
# Warmup Iteration   3: 8.990 ops/ms
Iteration   1: 9.195 ops/ms
Iteration   2: 9.321 ops/ms
Iteration   3: 9.108 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.208 ±(99.9%) 1.959 ops/ms [Average]
  (min, avg, max) = (9.108, 9.208, 9.321), stdev = 0.107
  CI (99.9%): [7.249, 11.167] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 6.078 ops/ms
# Warmup Iteration   2: 8.068 ops/ms
# Warmup Iteration   3: 8.364 ops/ms
Iteration   1: 8.496 ops/ms
Iteration   2: 8.573 ops/ms
Iteration   3: 8.659 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.576 ±(99.9%) 1.485 ops/ms [Average]
  (min, avg, max) = (8.496, 8.576, 8.659), stdev = 0.081
  CI (99.9%): [7.091, 10.061] (assumes normal distribution)


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
# Warmup Iteration   1: 4.020 ops/ms
# Warmup Iteration   2: 6.380 ops/ms
# Warmup Iteration   3: 6.842 ops/ms
Iteration   1: 6.795 ops/ms
Iteration   2: 6.812 ops/ms
Iteration   3: 6.876 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.828 ±(99.9%) 0.779 ops/ms [Average]
  (min, avg, max) = (6.795, 6.828, 6.876), stdev = 0.043
  CI (99.9%): [6.049, 7.607] (assumes normal distribution)


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
# Warmup Iteration   1: 5.429 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.949 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.794 ±(99.9%) 0.007 ms/op
Iteration   1: 3.696 ±(99.9%) 0.003 ms/op
Iteration   2: 3.680 ±(99.9%) 0.005 ms/op
Iteration   3: 3.652 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.676 ±(99.9%) 0.402 ms/op [Average]
  (min, avg, max) = (3.652, 3.676, 3.696), stdev = 0.022
  CI (99.9%): [3.274, 4.077] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 4.650 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.696 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.393 ±(99.9%) 0.005 ms/op
Iteration   1: 3.571 ±(99.9%) 0.003 ms/op
Iteration   2: 3.476 ±(99.9%) 0.003 ms/op
Iteration   3: 3.447 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.498 ±(99.9%) 1.183 ms/op [Average]
  (min, avg, max) = (3.447, 3.498, 3.571), stdev = 0.065
  CI (99.9%): [2.315, 4.682] (assumes normal distribution)


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
# Warmup Iteration   1: 5.132 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 3.815 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.736 ±(99.9%) 0.006 ms/op
Iteration   1: 3.686 ±(99.9%) 0.003 ms/op
Iteration   2: 3.705 ±(99.9%) 0.003 ms/op
Iteration   3: 3.612 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.668 ±(99.9%) 0.900 ms/op [Average]
  (min, avg, max) = (3.612, 3.668, 3.705), stdev = 0.049
  CI (99.9%): [2.768, 4.568] (assumes normal distribution)


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
# Warmup Iteration   1: 6.738 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 4.913 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.655 ±(99.9%) 0.011 ms/op
Iteration   1: 4.658 ±(99.9%) 0.012 ms/op
Iteration   2: 4.755 ±(99.9%) 0.015 ms/op
Iteration   3: 4.665 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.693 ±(99.9%) 0.985 ms/op [Average]
  (min, avg, max) = (4.658, 4.693, 4.755), stdev = 0.054
  CI (99.9%): [3.708, 5.678] (assumes normal distribution)


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
# Warmup Iteration   1: 5.202 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 3.910 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.731 ±(99.9%) 0.009 ms/op
Iteration   1: 3.705 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.953 ms/op
                 createUser·p0.50:   3.604 ms/op
                 createUser·p0.90:   4.334 ms/op
                 createUser·p0.95:   4.669 ms/op
                 createUser·p0.99:   6.160 ms/op
                 createUser·p0.999:  13.200 ms/op
                 createUser·p0.9999: 20.996 ms/op
                 createUser·p1.00:   21.496 ms/op

Iteration   2: 3.666 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.031 ms/op
                 createUser·p0.50:   3.592 ms/op
                 createUser·p0.90:   4.252 ms/op
                 createUser·p0.95:   4.694 ms/op
                 createUser·p0.99:   6.171 ms/op
                 createUser·p0.999:  12.478 ms/op
                 createUser·p0.9999: 26.791 ms/op
                 createUser·p1.00:   28.410 ms/op

Iteration   3: 3.668 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.669 ms/op
                 createUser·p0.50:   3.600 ms/op
                 createUser·p0.90:   4.334 ms/op
                 createUser·p0.95:   4.604 ms/op
                 createUser·p0.99:   6.013 ms/op
                 createUser·p0.999:  12.485 ms/op
                 createUser·p0.9999: 43.862 ms/op
                 createUser·p1.00:   44.302 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 260922
  mean =      3.680 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 253396 
    [ 5.000, 10.000) = 7049 
    [10.000, 15.000) = 288 
    [15.000, 20.000) = 56 
    [20.000, 25.000) = 75 
    [25.000, 30.000) = 26 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.669 ms/op
     p(50.0000) =      3.600 ms/op
     p(90.0000) =      4.317 ms/op
     p(95.0000) =      4.653 ms/op
     p(99.0000) =      6.109 ms/op
     p(99.9000) =     12.812 ms/op
     p(99.9900) =     43.111 ms/op
     p(99.9990) =     44.197 ms/op
     p(99.9999) =     44.302 ms/op
    p(100.0000) =     44.302 ms/op


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
# Warmup Iteration   1: 5.103 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.622 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.578 ±(99.9%) 0.008 ms/op
Iteration   1: 3.411 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.612 ms/op
                 existUser·p0.50:   3.437 ms/op
                 existUser·p0.90:   4.104 ms/op
                 existUser·p0.95:   4.424 ms/op
                 existUser·p0.99:   5.751 ms/op
                 existUser·p0.999:  13.980 ms/op
                 existUser·p0.9999: 18.645 ms/op
                 existUser·p1.00:   18.907 ms/op

Iteration   2: 3.634 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.053 ms/op
                 existUser·p0.50:   3.568 ms/op
                 existUser·p0.90:   4.334 ms/op
                 existUser·p0.95:   4.620 ms/op
                 existUser·p0.99:   5.677 ms/op
                 existUser·p0.999:  9.585 ms/op
                 existUser·p0.9999: 20.094 ms/op
                 existUser·p1.00:   20.578 ms/op

Iteration   3: 3.449 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.851 ms/op
                 existUser·p0.50:   3.453 ms/op
                 existUser·p0.90:   4.182 ms/op
                 existUser·p0.95:   4.489 ms/op
                 existUser·p0.99:   5.513 ms/op
                 existUser·p0.999:  11.017 ms/op
                 existUser·p0.9999: 20.805 ms/op
                 existUser·p1.00:   21.561 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 274480
  mean =      3.496 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17784 
    [ 2.500,  5.000) = 251517 
    [ 5.000,  7.500) = 4349 
    [ 7.500, 10.000) = 550 
    [10.000, 12.500) = 88 
    [12.500, 15.000) = 96 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 76 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.612 ms/op
     p(50.0000) =      3.482 ms/op
     p(90.0000) =      4.219 ms/op
     p(95.0000) =      4.522 ms/op
     p(99.0000) =      5.636 ms/op
     p(99.9000) =     10.060 ms/op
     p(99.9900) =     19.169 ms/op
     p(99.9990) =     21.423 ms/op
     p(99.9999) =     21.561 ms/op
    p(100.0000) =     21.561 ms/op


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
# Warmup Iteration   1: 5.059 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.894 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.793 ±(99.9%) 0.009 ms/op
Iteration   1: 3.687 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.006 ms/op
                 getUser·p0.50:   3.609 ms/op
                 getUser·p0.90:   4.317 ms/op
                 getUser·p0.95:   4.669 ms/op
                 getUser·p0.99:   6.111 ms/op
                 getUser·p0.999:  10.928 ms/op
                 getUser·p0.9999: 17.804 ms/op
                 getUser·p1.00:   19.137 ms/op

Iteration   2: 3.716 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.705 ms/op
                 getUser·p0.50:   3.670 ms/op
                 getUser·p0.90:   4.440 ms/op
                 getUser·p0.95:   4.776 ms/op
                 getUser·p0.99:   6.029 ms/op
                 getUser·p0.999:  9.729 ms/op
                 getUser·p0.9999: 15.385 ms/op
                 getUser·p1.00:   16.040 ms/op

Iteration   3: 3.690 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.653 ms/op
                 getUser·p0.50:   3.625 ms/op
                 getUser·p0.90:   4.334 ms/op
                 getUser·p0.95:   4.661 ms/op
                 getUser·p0.99:   5.587 ms/op
                 getUser·p0.999:  11.502 ms/op
                 getUser·p0.9999: 18.088 ms/op
                 getUser·p1.00:   18.252 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 259656
  mean =      3.698 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 61 
    [ 1.250,  2.500) = 6455 
    [ 2.500,  3.750) = 147261 
    [ 3.750,  5.000) = 98472 
    [ 5.000,  6.250) = 5395 
    [ 6.250,  7.500) = 1042 
    [ 7.500,  8.750) = 500 
    [ 8.750, 10.000) = 168 
    [10.000, 11.250) = 85 
    [11.250, 12.500) = 57 
    [12.500, 13.750) = 3 
    [13.750, 15.000) = 45 
    [15.000, 16.250) = 29 
    [16.250, 17.500) = 28 
    [17.500, 18.750) = 52 

  Percentiles, ms/op:
      p(0.0000) =      0.653 ms/op
     p(50.0000) =      3.633 ms/op
     p(90.0000) =      4.366 ms/op
     p(95.0000) =      4.702 ms/op
     p(99.0000) =      5.939 ms/op
     p(99.9000) =     10.846 ms/op
     p(99.9900) =     17.891 ms/op
     p(99.9990) =     18.980 ms/op
     p(99.9999) =     19.137 ms/op
    p(100.0000) =     19.137 ms/op


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
# Warmup Iteration   1: 6.683 ±(99.9%) 0.072 ms/op
# Warmup Iteration   2: 4.948 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.663 ±(99.9%) 0.013 ms/op
Iteration   1: 4.749 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.341 ms/op
                 listUser·p0.50:   4.538 ms/op
                 listUser·p0.90:   5.898 ms/op
                 listUser·p0.95:   6.840 ms/op
                 listUser·p0.99:   8.733 ms/op
                 listUser·p0.999:  15.286 ms/op
                 listUser·p0.9999: 16.974 ms/op
                 listUser·p1.00:   17.170 ms/op

Iteration   2: 4.776 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.382 ms/op
                 listUser·p0.50:   4.547 ms/op
                 listUser·p0.90:   6.087 ms/op
                 listUser·p0.95:   6.889 ms/op
                 listUser·p0.99:   8.684 ms/op
                 listUser·p0.999:  21.006 ms/op
                 listUser·p0.9999: 25.372 ms/op
                 listUser·p1.00:   25.788 ms/op

Iteration   3: 4.642 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.126 ms/op
                 listUser·p0.50:   4.456 ms/op
                 listUser·p0.90:   5.865 ms/op
                 listUser·p0.95:   6.701 ms/op
                 listUser·p0.99:   8.268 ms/op
                 listUser·p0.999:  18.620 ms/op
                 listUser·p0.9999: 21.248 ms/op
                 listUser·p1.00:   22.381 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 203158
  mean =      4.721 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 650 
    [ 2.500,  5.000) = 156225 
    [ 5.000,  7.500) = 41260 
    [ 7.500, 10.000) = 4015 
    [10.000, 12.500) = 566 
    [12.500, 15.000) = 156 
    [15.000, 17.500) = 83 
    [17.500, 20.000) = 100 
    [20.000, 22.500) = 67 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      1.126 ms/op
     p(50.0000) =      4.514 ms/op
     p(90.0000) =      5.964 ms/op
     p(95.0000) =      6.816 ms/op
     p(99.0000) =      8.520 ms/op
     p(99.9000) =     17.608 ms/op
     p(99.9900) =     23.674 ms/op
     p(99.9990) =     25.720 ms/op
     p(99.9999) =     25.788 ms/op
    p(100.0000) =     25.788 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.451 ± 1.281  ops/ms
ClientGrpc.existUser                       thrpt       3   9.208 ± 1.959  ops/ms
ClientGrpc.getUser                         thrpt       3   8.576 ± 1.485  ops/ms
ClientGrpc.listUser                        thrpt       3   6.828 ± 0.779  ops/ms
ClientGrpc.createUser                       avgt       3   3.676 ± 0.402   ms/op
ClientGrpc.existUser                        avgt       3   3.498 ± 1.183   ms/op
ClientGrpc.getUser                          avgt       3   3.668 ± 0.900   ms/op
ClientGrpc.listUser                         avgt       3   4.693 ± 0.985   ms/op
ClientGrpc.createUser                     sample  260922   3.680 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.669           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.600           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.317           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.653           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.109           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.812           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          43.111           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          44.302           ms/op
ClientGrpc.existUser                      sample  274480   3.496 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.612           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.482           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.219           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.522           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.636           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.060           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.169           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.561           ms/op
ClientGrpc.getUser                        sample  259656   3.698 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.653           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.633           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.366           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.702           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.939           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.846           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.891           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.137           ms/op
ClientGrpc.listUser                       sample  203158   4.721 ± 0.009   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.126           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.514           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.964           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.816           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.520           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.608           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.674           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.788           ms/op
