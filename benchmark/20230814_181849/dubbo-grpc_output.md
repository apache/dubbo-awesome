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
# Warmup Iteration   1: 3.171 ops/ms
# Warmup Iteration   2: 6.768 ops/ms
# Warmup Iteration   3: 8.121 ops/ms
Iteration   1: 8.556 ops/ms
Iteration   2: 8.889 ops/ms
Iteration   3: 8.549 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.665 ±(99.9%) 3.548 ops/ms [Average]
  (min, avg, max) = (8.549, 8.665, 8.889), stdev = 0.194
  CI (99.9%): [5.116, 12.213] (assumes normal distribution)


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
# Warmup Iteration   1: 5.822 ops/ms
# Warmup Iteration   2: 8.591 ops/ms
# Warmup Iteration   3: 9.000 ops/ms
Iteration   1: 9.152 ops/ms
Iteration   2: 9.217 ops/ms
Iteration   3: 9.221 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.197 ±(99.9%) 0.706 ops/ms [Average]
  (min, avg, max) = (9.152, 9.197, 9.221), stdev = 0.039
  CI (99.9%): [8.491, 9.903] (assumes normal distribution)


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
# Warmup Iteration   1: 6.025 ops/ms
# Warmup Iteration   2: 8.373 ops/ms
# Warmup Iteration   3: 8.784 ops/ms
Iteration   1: 8.775 ops/ms
Iteration   2: 8.631 ops/ms
Iteration   3: 8.869 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.758 ±(99.9%) 2.186 ops/ms [Average]
  (min, avg, max) = (8.631, 8.758, 8.869), stdev = 0.120
  CI (99.9%): [6.573, 10.944] (assumes normal distribution)


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
# Warmup Iteration   1: 4.732 ops/ms
# Warmup Iteration   2: 5.912 ops/ms
# Warmup Iteration   3: 6.639 ops/ms
Iteration   1: 6.711 ops/ms
Iteration   2: 6.668 ops/ms
Iteration   3: 6.727 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.702 ±(99.9%) 0.558 ops/ms [Average]
  (min, avg, max) = (6.668, 6.702, 6.727), stdev = 0.031
  CI (99.9%): [6.143, 7.260] (assumes normal distribution)


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
# Warmup Iteration   1: 4.838 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.951 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.734 ±(99.9%) 0.004 ms/op
Iteration   1: 3.651 ±(99.9%) 0.003 ms/op
Iteration   2: 3.703 ±(99.9%) 0.003 ms/op
Iteration   3: 3.700 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.685 ±(99.9%) 0.532 ms/op [Average]
  (min, avg, max) = (3.651, 3.685, 3.703), stdev = 0.029
  CI (99.9%): [3.153, 4.216] (assumes normal distribution)


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
# Warmup Iteration   1: 5.119 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.701 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.534 ±(99.9%) 0.003 ms/op
Iteration   1: 3.566 ±(99.9%) 0.004 ms/op
Iteration   2: 3.457 ±(99.9%) 0.004 ms/op
Iteration   3: 3.546 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.523 ±(99.9%) 1.057 ms/op [Average]
  (min, avg, max) = (3.457, 3.523, 3.566), stdev = 0.058
  CI (99.9%): [2.466, 4.580] (assumes normal distribution)


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
# Warmup Iteration   1: 5.250 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.938 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.750 ±(99.9%) 0.009 ms/op
Iteration   1: 3.645 ±(99.9%) 0.004 ms/op
Iteration   2: 3.617 ±(99.9%) 0.005 ms/op
Iteration   3: 3.648 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.637 ±(99.9%) 0.310 ms/op [Average]
  (min, avg, max) = (3.617, 3.637, 3.648), stdev = 0.017
  CI (99.9%): [3.326, 3.947] (assumes normal distribution)


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
# Warmup Iteration   1: 6.832 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 5.021 ±(99.9%) 0.047 ms/op
# Warmup Iteration   3: 4.928 ±(99.9%) 0.025 ms/op
Iteration   1: 4.679 ±(99.9%) 0.020 ms/op
Iteration   2: 4.747 ±(99.9%) 0.032 ms/op
Iteration   3: 4.711 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.712 ±(99.9%) 0.625 ms/op [Average]
  (min, avg, max) = (4.679, 4.712, 4.747), stdev = 0.034
  CI (99.9%): [4.088, 5.337] (assumes normal distribution)


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
# Warmup Iteration   1: 5.287 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 3.857 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.618 ±(99.9%) 0.009 ms/op
Iteration   1: 3.723 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.973 ms/op
                 createUser·p0.50:   3.650 ms/op
                 createUser·p0.90:   4.473 ms/op
                 createUser·p0.95:   4.792 ms/op
                 createUser·p0.99:   6.390 ms/op
                 createUser·p0.999:  10.354 ms/op
                 createUser·p0.9999: 14.819 ms/op
                 createUser·p1.00:   16.450 ms/op

Iteration   2: 3.597 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.961 ms/op
                 createUser·p0.50:   3.543 ms/op
                 createUser·p0.90:   4.243 ms/op
                 createUser·p0.95:   4.547 ms/op
                 createUser·p0.99:   5.767 ms/op
                 createUser·p0.999:  10.928 ms/op
                 createUser·p0.9999: 17.406 ms/op
                 createUser·p1.00:   17.859 ms/op

Iteration   3: 3.649 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.947 ms/op
                 createUser·p0.50:   3.592 ms/op
                 createUser·p0.90:   4.243 ms/op
                 createUser·p0.95:   4.563 ms/op
                 createUser·p0.99:   5.738 ms/op
                 createUser·p0.999:  10.341 ms/op
                 createUser·p0.9999: 18.619 ms/op
                 createUser·p1.00:   19.792 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 262995
  mean =      3.656 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 80 
    [ 1.250,  2.500) = 6423 
    [ 2.500,  3.750) = 160140 
    [ 3.750,  5.000) = 89461 
    [ 5.000,  6.250) = 4801 
    [ 6.250,  7.500) = 1005 
    [ 7.500,  8.750) = 495 
    [ 8.750, 10.000) = 229 
    [10.000, 11.250) = 185 
    [11.250, 12.500) = 15 
    [12.500, 13.750) = 29 
    [13.750, 15.000) = 31 
    [15.000, 16.250) = 12 
    [16.250, 17.500) = 44 
    [17.500, 18.750) = 39 

  Percentiles, ms/op:
      p(0.0000) =      0.947 ms/op
     p(50.0000) =      3.588 ms/op
     p(90.0000) =      4.334 ms/op
     p(95.0000) =      4.645 ms/op
     p(99.0000) =      5.939 ms/op
     p(99.9000) =     10.519 ms/op
     p(99.9900) =     17.826 ms/op
     p(99.9990) =     19.607 ms/op
     p(99.9999) =     19.792 ms/op
    p(100.0000) =     19.792 ms/op


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
# Warmup Iteration   1: 5.080 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.646 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.455 ±(99.9%) 0.008 ms/op
Iteration   1: 3.493 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.626 ms/op
                 existUser·p0.50:   3.445 ms/op
                 existUser·p0.90:   4.202 ms/op
                 existUser·p0.95:   4.538 ms/op
                 existUser·p0.99:   5.874 ms/op
                 existUser·p0.999:  10.100 ms/op
                 existUser·p0.9999: 17.090 ms/op
                 existUser·p1.00:   17.498 ms/op

Iteration   2: 3.547 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.852 ms/op
                 existUser·p0.50:   3.482 ms/op
                 existUser·p0.90:   4.235 ms/op
                 existUser·p0.95:   4.555 ms/op
                 existUser·p0.99:   5.759 ms/op
                 existUser·p0.999:  9.404 ms/op
                 existUser·p0.9999: 16.643 ms/op
                 existUser·p1.00:   17.302 ms/op

Iteration   3: 3.502 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.732 ms/op
                 existUser·p0.50:   3.437 ms/op
                 existUser·p0.90:   4.125 ms/op
                 existUser·p0.95:   4.456 ms/op
                 existUser·p0.99:   5.808 ms/op
                 existUser·p0.999:  9.252 ms/op
                 existUser·p0.9999: 22.606 ms/op
                 existUser·p1.00:   23.167 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 273195
  mean =      3.514 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10770 
    [ 2.500,  5.000) = 256142 
    [ 5.000,  7.500) = 5405 
    [ 7.500, 10.000) = 678 
    [10.000, 12.500) = 40 
    [12.500, 15.000) = 55 
    [15.000, 17.500) = 73 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.626 ms/op
     p(50.0000) =      3.453 ms/op
     p(90.0000) =      4.190 ms/op
     p(95.0000) =      4.522 ms/op
     p(99.0000) =      5.808 ms/op
     p(99.9000) =      9.535 ms/op
     p(99.9900) =     18.711 ms/op
     p(99.9990) =     22.901 ms/op
     p(99.9999) =     23.167 ms/op
    p(100.0000) =     23.167 ms/op


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
# Warmup Iteration   1: 5.416 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.832 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.664 ±(99.9%) 0.009 ms/op
Iteration   1: 3.721 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.799 ms/op
                 getUser·p0.50:   3.654 ms/op
                 getUser·p0.90:   4.440 ms/op
                 getUser·p0.95:   4.727 ms/op
                 getUser·p0.99:   5.849 ms/op
                 getUser·p0.999:  11.365 ms/op
                 getUser·p0.9999: 15.401 ms/op
                 getUser·p1.00:   15.565 ms/op

Iteration   2: 3.625 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.959 ms/op
                 getUser·p0.50:   3.580 ms/op
                 getUser·p0.90:   4.325 ms/op
                 getUser·p0.95:   4.604 ms/op
                 getUser·p0.99:   5.838 ms/op
                 getUser·p0.999:  11.638 ms/op
                 getUser·p0.9999: 14.525 ms/op
                 getUser·p1.00:   16.531 ms/op

Iteration   3: 3.674 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.092 ms/op
                 getUser·p0.50:   3.604 ms/op
                 getUser·p0.90:   4.350 ms/op
                 getUser·p0.95:   4.678 ms/op
                 getUser·p0.99:   6.062 ms/op
                 getUser·p0.999:  10.027 ms/op
                 getUser·p0.9999: 20.101 ms/op
                 getUser·p1.00:   20.316 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 261447
  mean =      3.673 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7842 
    [ 2.500,  5.000) = 246446 
    [ 5.000,  7.500) = 6101 
    [ 7.500, 10.000) = 752 
    [10.000, 12.500) = 94 
    [12.500, 15.000) = 122 
    [15.000, 17.500) = 43 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.799 ms/op
     p(50.0000) =      3.613 ms/op
     p(90.0000) =      4.375 ms/op
     p(95.0000) =      4.669 ms/op
     p(99.0000) =      5.923 ms/op
     p(99.9000) =     10.790 ms/op
     p(99.9900) =     18.762 ms/op
     p(99.9990) =     20.296 ms/op
     p(99.9999) =     20.316 ms/op
    p(100.0000) =     20.316 ms/op


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
# Warmup Iteration   1: 5.999 ±(99.9%) 0.066 ms/op
# Warmup Iteration   2: 5.206 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.733 ±(99.9%) 0.015 ms/op
Iteration   1: 4.819 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.025 ms/op
                 listUser·p0.50:   4.641 ms/op
                 listUser·p0.90:   5.775 ms/op
                 listUser·p0.95:   6.783 ms/op
                 listUser·p0.99:   8.585 ms/op
                 listUser·p0.999:  16.461 ms/op
                 listUser·p0.9999: 20.147 ms/op
                 listUser·p1.00:   20.513 ms/op

Iteration   2: 4.746 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.051 ms/op
                 listUser·p0.50:   4.530 ms/op
                 listUser·p0.90:   5.931 ms/op
                 listUser·p0.95:   6.783 ms/op
                 listUser·p0.99:   8.864 ms/op
                 listUser·p0.999:  17.778 ms/op
                 listUser·p0.9999: 20.464 ms/op
                 listUser·p1.00:   21.070 ms/op

Iteration   3: 4.782 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   0.957 ms/op
                 listUser·p0.50:   4.563 ms/op
                 listUser·p0.90:   5.906 ms/op
                 listUser·p0.95:   6.660 ms/op
                 listUser·p0.99:   8.405 ms/op
                 listUser·p0.999:  20.480 ms/op
                 listUser·p0.9999: 32.877 ms/op
                 listUser·p1.00:   33.325 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 200658
  mean =      4.782 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 287 
    [ 2.500,  5.000) = 151419 
    [ 5.000,  7.500) = 43645 
    [ 7.500, 10.000) = 4375 
    [10.000, 12.500) = 485 
    [12.500, 15.000) = 108 
    [15.000, 17.500) = 91 
    [17.500, 20.000) = 147 
    [20.000, 22.500) = 59 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 22 
    [32.500, 35.000) = 10 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.957 ms/op
     p(50.0000) =      4.588 ms/op
     p(90.0000) =      5.874 ms/op
     p(95.0000) =      6.742 ms/op
     p(99.0000) =      8.618 ms/op
     p(99.9000) =     18.088 ms/op
     p(99.9900) =     31.226 ms/op
     p(99.9990) =     33.226 ms/op
     p(99.9999) =     33.325 ms/op
    p(100.0000) =     33.325 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.665 ± 3.548  ops/ms
ClientGrpc.existUser                       thrpt       3   9.197 ± 0.706  ops/ms
ClientGrpc.getUser                         thrpt       3   8.758 ± 2.186  ops/ms
ClientGrpc.listUser                        thrpt       3   6.702 ± 0.558  ops/ms
ClientGrpc.createUser                       avgt       3   3.685 ± 0.532   ms/op
ClientGrpc.existUser                        avgt       3   3.523 ± 1.057   ms/op
ClientGrpc.getUser                          avgt       3   3.637 ± 0.310   ms/op
ClientGrpc.listUser                         avgt       3   4.712 ± 0.625   ms/op
ClientGrpc.createUser                     sample  262995   3.656 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.947           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.588           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.334           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.645           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.939           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.519           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.826           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          19.792           ms/op
ClientGrpc.existUser                      sample  273195   3.514 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.626           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.453           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.190           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.522           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.808           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.535           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.711           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          23.167           ms/op
ClientGrpc.getUser                        sample  261447   3.673 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.799           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.613           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.375           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.669           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.923           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.790           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.762           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.316           ms/op
ClientGrpc.listUser                       sample  200658   4.782 ± 0.009   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.957           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.588           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.874           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.742           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.618           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.088           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          31.226           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          33.325           ms/op
