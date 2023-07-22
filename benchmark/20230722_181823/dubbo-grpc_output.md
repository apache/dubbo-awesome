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
# Warmup Iteration   1: 3.111 ops/ms
# Warmup Iteration   2: 6.024 ops/ms
# Warmup Iteration   3: 8.325 ops/ms
Iteration   1: 8.384 ops/ms
Iteration   2: 8.637 ops/ms
Iteration   3: 8.703 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.575 ±(99.9%) 3.070 ops/ms [Average]
  (min, avg, max) = (8.384, 8.575, 8.703), stdev = 0.168
  CI (99.9%): [5.505, 11.645] (assumes normal distribution)


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
# Warmup Iteration   1: 5.840 ops/ms
# Warmup Iteration   2: 8.717 ops/ms
# Warmup Iteration   3: 9.004 ops/ms
Iteration   1: 9.188 ops/ms
Iteration   2: 9.119 ops/ms
Iteration   3: 9.217 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.174 ±(99.9%) 0.922 ops/ms [Average]
  (min, avg, max) = (9.119, 9.174, 9.217), stdev = 0.051
  CI (99.9%): [8.253, 10.096] (assumes normal distribution)


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
# Warmup Iteration   1: 5.708 ops/ms
# Warmup Iteration   2: 8.005 ops/ms
# Warmup Iteration   3: 8.536 ops/ms
Iteration   1: 8.635 ops/ms
Iteration   2: 8.508 ops/ms
Iteration   3: 8.505 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.549 ±(99.9%) 1.351 ops/ms [Average]
  (min, avg, max) = (8.505, 8.549, 8.635), stdev = 0.074
  CI (99.9%): [7.198, 9.900] (assumes normal distribution)


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
# Warmup Iteration   1: 4.423 ops/ms
# Warmup Iteration   2: 6.077 ops/ms
# Warmup Iteration   3: 6.711 ops/ms
Iteration   1: 6.659 ops/ms
Iteration   2: 6.773 ops/ms
Iteration   3: 6.580 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.671 ±(99.9%) 1.768 ops/ms [Average]
  (min, avg, max) = (6.580, 6.671, 6.773), stdev = 0.097
  CI (99.9%): [4.903, 8.439] (assumes normal distribution)


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
# Warmup Iteration   1: 5.221 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.935 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 3.842 ±(99.9%) 0.004 ms/op
Iteration   1: 3.710 ±(99.9%) 0.003 ms/op
Iteration   2: 3.684 ±(99.9%) 0.002 ms/op
Iteration   3: 3.632 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.676 ±(99.9%) 0.721 ms/op [Average]
  (min, avg, max) = (3.632, 3.676, 3.710), stdev = 0.040
  CI (99.9%): [2.955, 4.396] (assumes normal distribution)


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
# Warmup Iteration   1: 5.167 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.809 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.572 ±(99.9%) 0.003 ms/op
Iteration   1: 3.468 ±(99.9%) 0.003 ms/op
Iteration   2: 3.468 ±(99.9%) 0.003 ms/op
Iteration   3: 3.557 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.498 ±(99.9%) 0.932 ms/op [Average]
  (min, avg, max) = (3.468, 3.498, 3.557), stdev = 0.051
  CI (99.9%): [2.565, 4.430] (assumes normal distribution)


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
# Warmup Iteration   1: 5.341 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.832 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.828 ±(99.9%) 0.003 ms/op
Iteration   1: 3.690 ±(99.9%) 0.003 ms/op
Iteration   2: 3.766 ±(99.9%) 0.004 ms/op
Iteration   3: 3.785 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.747 ±(99.9%) 0.913 ms/op [Average]
  (min, avg, max) = (3.690, 3.747, 3.785), stdev = 0.050
  CI (99.9%): [2.834, 4.659] (assumes normal distribution)


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
# Warmup Iteration   1: 5.678 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 5.348 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.886 ±(99.9%) 0.011 ms/op
Iteration   1: 4.898 ±(99.9%) 0.011 ms/op
Iteration   2: 4.776 ±(99.9%) 0.013 ms/op
Iteration   3: 4.778 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.817 ±(99.9%) 1.273 ms/op [Average]
  (min, avg, max) = (4.776, 4.817, 4.898), stdev = 0.070
  CI (99.9%): [3.544, 6.090] (assumes normal distribution)


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
# Warmup Iteration   1: 5.106 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 3.915 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.796 ±(99.9%) 0.008 ms/op
Iteration   1: 3.615 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.010 ms/op
                 createUser·p0.50:   3.637 ms/op
                 createUser·p0.90:   4.350 ms/op
                 createUser·p0.95:   4.563 ms/op
                 createUser·p0.99:   5.677 ms/op
                 createUser·p0.999:  12.717 ms/op
                 createUser·p0.9999: 22.844 ms/op
                 createUser·p1.00:   23.691 ms/op

Iteration   2: 3.649 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.036 ms/op
                 createUser·p0.50:   3.609 ms/op
                 createUser·p0.90:   4.211 ms/op
                 createUser·p0.95:   4.530 ms/op
                 createUser·p0.99:   5.292 ms/op
                 createUser·p0.999:  8.111 ms/op
                 createUser·p0.9999: 15.995 ms/op
                 createUser·p1.00:   16.581 ms/op

Iteration   3: 3.649 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.882 ms/op
                 createUser·p0.50:   3.629 ms/op
                 createUser·p0.90:   4.284 ms/op
                 createUser·p0.95:   4.596 ms/op
                 createUser·p0.99:   5.702 ms/op
                 createUser·p0.999:  17.683 ms/op
                 createUser·p0.9999: 23.936 ms/op
                 createUser·p1.00:   24.281 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 263903
  mean =      3.637 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13100 
    [ 2.500,  5.000) = 245312 
    [ 5.000,  7.500) = 4929 
    [ 7.500, 10.000) = 281 
    [10.000, 12.500) = 27 
    [12.500, 15.000) = 49 
    [15.000, 17.500) = 69 
    [17.500, 20.000) = 56 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 53 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.882 ms/op
     p(50.0000) =      3.625 ms/op
     p(90.0000) =      4.293 ms/op
     p(95.0000) =      4.563 ms/op
     p(99.0000) =      5.554 ms/op
     p(99.9000) =     10.951 ms/op
     p(99.9900) =     23.626 ms/op
     p(99.9990) =     24.141 ms/op
     p(99.9999) =     24.281 ms/op
    p(100.0000) =     24.281 ms/op


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
# Warmup Iteration   1: 4.838 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.844 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.482 ±(99.9%) 0.008 ms/op
Iteration   1: 3.558 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.915 ms/op
                 existUser·p0.50:   3.506 ms/op
                 existUser·p0.90:   4.096 ms/op
                 existUser·p0.95:   4.366 ms/op
                 existUser·p0.99:   5.284 ms/op
                 existUser·p0.999:  9.323 ms/op
                 existUser·p0.9999: 25.035 ms/op
                 existUser·p1.00:   27.132 ms/op

Iteration   2: 3.568 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.768 ms/op
                 existUser·p0.50:   3.514 ms/op
                 existUser·p0.90:   4.133 ms/op
                 existUser·p0.95:   4.383 ms/op
                 existUser·p0.99:   5.382 ms/op
                 existUser·p0.999:  8.261 ms/op
                 existUser·p0.9999: 15.958 ms/op
                 existUser·p1.00:   17.367 ms/op

Iteration   3: 3.493 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.021 ms/op
                 existUser·p0.50:   3.478 ms/op
                 existUser·p0.90:   3.977 ms/op
                 existUser·p0.95:   4.211 ms/op
                 existUser·p0.99:   5.112 ms/op
                 existUser·p0.999:  7.663 ms/op
                 existUser·p0.9999: 16.611 ms/op
                 existUser·p1.00:   17.170 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 271313
  mean =      3.539 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5013 
    [ 2.500,  5.000) = 262490 
    [ 5.000,  7.500) = 3384 
    [ 7.500, 10.000) = 286 
    [10.000, 12.500) = 12 
    [12.500, 15.000) = 19 
    [15.000, 17.500) = 77 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      0.768 ms/op
     p(50.0000) =      3.498 ms/op
     p(90.0000) =      4.071 ms/op
     p(95.0000) =      4.334 ms/op
     p(99.0000) =      5.284 ms/op
     p(99.9000) =      7.938 ms/op
     p(99.9900) =     24.118 ms/op
     p(99.9990) =     25.926 ms/op
     p(99.9999) =     27.132 ms/op
    p(100.0000) =     27.132 ms/op


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
# Warmup Iteration   1: 5.642 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 4.034 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.811 ±(99.9%) 0.008 ms/op
Iteration   1: 3.768 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.874 ms/op
                 getUser·p0.50:   3.711 ms/op
                 getUser·p0.90:   4.448 ms/op
                 getUser·p0.95:   4.768 ms/op
                 getUser·p0.99:   5.890 ms/op
                 getUser·p0.999:  9.903 ms/op
                 getUser·p0.9999: 14.828 ms/op
                 getUser·p1.00:   15.352 ms/op

Iteration   2: 3.668 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.108 ms/op
                 getUser·p0.50:   3.666 ms/op
                 getUser·p0.90:   4.334 ms/op
                 getUser·p0.95:   4.588 ms/op
                 getUser·p0.99:   5.605 ms/op
                 getUser·p0.999:  14.399 ms/op
                 getUser·p0.9999: 16.393 ms/op
                 getUser·p1.00:   17.564 ms/op

Iteration   3: 3.697 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.478 ms/op
                 getUser·p0.50:   3.658 ms/op
                 getUser·p0.90:   4.235 ms/op
                 getUser·p0.95:   4.538 ms/op
                 getUser·p0.99:   5.464 ms/op
                 getUser·p0.999:  8.212 ms/op
                 getUser·p0.9999: 21.201 ms/op
                 getUser·p1.00:   21.987 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 258540
  mean =      3.711 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7650 
    [ 2.500,  5.000) = 244951 
    [ 5.000,  7.500) = 5380 
    [ 7.500, 10.000) = 316 
    [10.000, 12.500) = 29 
    [12.500, 15.000) = 112 
    [15.000, 17.500) = 68 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.478 ms/op
     p(50.0000) =      3.674 ms/op
     p(90.0000) =      4.342 ms/op
     p(95.0000) =      4.637 ms/op
     p(99.0000) =      5.669 ms/op
     p(99.9000) =      9.518 ms/op
     p(99.9900) =     20.588 ms/op
     p(99.9990) =     21.799 ms/op
     p(99.9999) =     21.987 ms/op
    p(100.0000) =     21.987 ms/op


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
# Warmup Iteration   1: 6.235 ±(99.9%) 0.066 ms/op
# Warmup Iteration   2: 5.105 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.878 ±(99.9%) 0.015 ms/op
Iteration   1: 4.845 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.743 ms/op
                 listUser·p0.50:   4.653 ms/op
                 listUser·p0.90:   6.128 ms/op
                 listUser·p0.95:   7.111 ms/op
                 listUser·p0.99:   8.569 ms/op
                 listUser·p0.999:  15.434 ms/op
                 listUser·p0.9999: 21.017 ms/op
                 listUser·p1.00:   22.938 ms/op

Iteration   2: 4.794 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.397 ms/op
                 listUser·p0.50:   4.588 ms/op
                 listUser·p0.90:   6.169 ms/op
                 listUser·p0.95:   7.152 ms/op
                 listUser·p0.99:   8.847 ms/op
                 listUser·p0.999:  18.678 ms/op
                 listUser·p0.9999: 24.302 ms/op
                 listUser·p1.00:   31.425 ms/op

Iteration   3: 4.819 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.395 ms/op
                 listUser·p0.50:   4.637 ms/op
                 listUser·p0.90:   5.964 ms/op
                 listUser·p0.95:   6.685 ms/op
                 listUser·p0.99:   8.585 ms/op
                 listUser·p0.999:  20.895 ms/op
                 listUser·p0.9999: 24.195 ms/op
                 listUser·p1.00:   25.100 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 199115
  mean =      4.819 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 441 
    [ 2.500,  5.000) = 143160 
    [ 5.000,  7.500) = 49244 
    [ 7.500, 10.000) = 5448 
    [10.000, 12.500) = 423 
    [12.500, 15.000) = 88 
    [15.000, 17.500) = 76 
    [17.500, 20.000) = 50 
    [20.000, 22.500) = 137 
    [22.500, 25.000) = 46 
    [25.000, 27.500) = 1 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.395 ms/op
     p(50.0000) =      4.628 ms/op
     p(90.0000) =      6.078 ms/op
     p(95.0000) =      7.012 ms/op
     p(99.0000) =      8.667 ms/op
     p(99.9000) =     19.595 ms/op
     p(99.9900) =     23.465 ms/op
     p(99.9990) =     25.156 ms/op
     p(99.9999) =     31.425 ms/op
    p(100.0000) =     31.425 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.575 ± 3.070  ops/ms
ClientGrpc.existUser                       thrpt       3   9.174 ± 0.922  ops/ms
ClientGrpc.getUser                         thrpt       3   8.549 ± 1.351  ops/ms
ClientGrpc.listUser                        thrpt       3   6.671 ± 1.768  ops/ms
ClientGrpc.createUser                       avgt       3   3.676 ± 0.721   ms/op
ClientGrpc.existUser                        avgt       3   3.498 ± 0.932   ms/op
ClientGrpc.getUser                          avgt       3   3.747 ± 0.913   ms/op
ClientGrpc.listUser                         avgt       3   4.817 ± 1.273   ms/op
ClientGrpc.createUser                     sample  263903   3.637 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.882           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.625           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.293           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.563           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.554           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.951           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          23.626           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          24.281           ms/op
ClientGrpc.existUser                      sample  271313   3.539 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.768           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.498           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.071           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.334           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.284           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.938           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          24.118           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          27.132           ms/op
ClientGrpc.getUser                        sample  258540   3.711 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.478           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.674           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.342           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.637           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.669           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.518           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.588           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.987           ms/op
ClientGrpc.listUser                       sample  199115   4.819 ± 0.009   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.395           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.628           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.078           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.012           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.667           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          19.595           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.465           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          31.425           ms/op
