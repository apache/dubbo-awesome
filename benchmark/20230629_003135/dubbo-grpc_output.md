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
# Warmup Iteration   1: 3.089 ops/ms
# Warmup Iteration   2: 6.963 ops/ms
# Warmup Iteration   3: 8.139 ops/ms
Iteration   1: 8.435 ops/ms
Iteration   2: 8.643 ops/ms
Iteration   3: 8.594 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.558 ±(99.9%) 1.985 ops/ms [Average]
  (min, avg, max) = (8.435, 8.558, 8.643), stdev = 0.109
  CI (99.9%): [6.573, 10.543] (assumes normal distribution)


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
# Warmup Iteration   1: 5.302 ops/ms
# Warmup Iteration   2: 8.483 ops/ms
# Warmup Iteration   3: 8.739 ops/ms
Iteration   1: 8.728 ops/ms
Iteration   2: 9.050 ops/ms
Iteration   3: 9.173 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.984 ±(99.9%) 4.196 ops/ms [Average]
  (min, avg, max) = (8.728, 8.984, 9.173), stdev = 0.230
  CI (99.9%): [4.788, 13.179] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 5.395 ops/ms
# Warmup Iteration   2: 8.235 ops/ms
# Warmup Iteration   3: 8.530 ops/ms
Iteration   1: 8.778 ops/ms
Iteration   2: 8.834 ops/ms
Iteration   3: 8.529 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.714 ±(99.9%) 2.955 ops/ms [Average]
  (min, avg, max) = (8.529, 8.714, 8.834), stdev = 0.162
  CI (99.9%): [5.759, 11.668] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 4.121 ops/ms
# Warmup Iteration   2: 5.962 ops/ms
# Warmup Iteration   3: 6.575 ops/ms
Iteration   1: 6.438 ops/ms
Iteration   2: 6.712 ops/ms
Iteration   3: 6.489 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.546 ±(99.9%) 2.663 ops/ms [Average]
  (min, avg, max) = (6.438, 6.546, 6.712), stdev = 0.146
  CI (99.9%): [3.884, 9.209] (assumes normal distribution)


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
# Warmup Iteration   1: 5.501 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.932 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.820 ±(99.9%) 0.033 ms/op
Iteration   1: 3.731 ±(99.9%) 0.002 ms/op
Iteration   2: 3.636 ±(99.9%) 0.004 ms/op
Iteration   3: 3.675 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.680 ±(99.9%) 0.870 ms/op [Average]
  (min, avg, max) = (3.636, 3.680, 3.731), stdev = 0.048
  CI (99.9%): [2.810, 4.551] (assumes normal distribution)


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
# Warmup Iteration   1: 4.864 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.758 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.523 ±(99.9%) 0.004 ms/op
Iteration   1: 3.609 ±(99.9%) 0.004 ms/op
Iteration   2: 3.472 ±(99.9%) 0.003 ms/op
Iteration   3: 3.495 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.525 ±(99.9%) 1.338 ms/op [Average]
  (min, avg, max) = (3.472, 3.525, 3.609), stdev = 0.073
  CI (99.9%): [2.187, 4.863] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 5.174 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.891 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.811 ±(99.9%) 0.004 ms/op
Iteration   1: 3.689 ±(99.9%) 0.003 ms/op
Iteration   2: 3.790 ±(99.9%) 0.004 ms/op
Iteration   3: 3.720 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.733 ±(99.9%) 0.943 ms/op [Average]
  (min, avg, max) = (3.689, 3.733, 3.790), stdev = 0.052
  CI (99.9%): [2.790, 4.676] (assumes normal distribution)


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
# Warmup Iteration   1: 6.848 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 5.231 ±(99.9%) 0.040 ms/op
# Warmup Iteration   3: 4.724 ±(99.9%) 0.016 ms/op
Iteration   1: 4.669 ±(99.9%) 0.006 ms/op
Iteration   2: 4.754 ±(99.9%) 0.011 ms/op
Iteration   3: 4.909 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.777 ±(99.9%) 2.222 ms/op [Average]
  (min, avg, max) = (4.669, 4.777, 4.909), stdev = 0.122
  CI (99.9%): [2.555, 6.999] (assumes normal distribution)


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
# Warmup Iteration   1: 5.522 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 3.968 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.757 ±(99.9%) 0.010 ms/op
Iteration   1: 3.755 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   0.950 ms/op
                 createUser·p0.50:   3.662 ms/op
                 createUser·p0.90:   4.612 ms/op
                 createUser·p0.95:   4.989 ms/op
                 createUser·p0.99:   6.496 ms/op
                 createUser·p0.999:  14.598 ms/op
                 createUser·p0.9999: 39.878 ms/op
                 createUser·p1.00:   40.894 ms/op

Iteration   2: 3.706 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.933 ms/op
                 createUser·p0.50:   3.609 ms/op
                 createUser·p0.90:   4.481 ms/op
                 createUser·p0.95:   4.841 ms/op
                 createUser·p0.99:   6.616 ms/op
                 createUser·p0.999:  17.463 ms/op
                 createUser·p0.9999: 27.110 ms/op
                 createUser·p1.00:   27.951 ms/op

Iteration   3: 3.685 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.835 ms/op
                 createUser·p0.50:   3.613 ms/op
                 createUser·p0.90:   4.424 ms/op
                 createUser·p0.95:   4.776 ms/op
                 createUser·p0.99:   6.119 ms/op
                 createUser·p0.999:  11.126 ms/op
                 createUser·p0.9999: 21.145 ms/op
                 createUser·p1.00:   21.660 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 258653
  mean =      3.715 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 248343 
    [ 5.000, 10.000) = 9854 
    [10.000, 15.000) = 224 
    [15.000, 20.000) = 118 
    [20.000, 25.000) = 51 
    [25.000, 30.000) = 33 
    [30.000, 35.000) = 3 
    [35.000, 40.000) = 23 
    [40.000, 45.000) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.835 ms/op
     p(50.0000) =      3.629 ms/op
     p(90.0000) =      4.506 ms/op
     p(95.0000) =      4.874 ms/op
     p(99.0000) =      6.398 ms/op
     p(99.9000) =     14.298 ms/op
     p(99.9900) =     38.615 ms/op
     p(99.9990) =     40.162 ms/op
     p(99.9999) =     40.894 ms/op
    p(100.0000) =     40.894 ms/op


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
# Warmup Iteration   1: 5.339 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 3.770 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.568 ±(99.9%) 0.009 ms/op
Iteration   1: 3.487 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.726 ms/op
                 existUser·p0.50:   3.424 ms/op
                 existUser·p0.90:   4.121 ms/op
                 existUser·p0.95:   4.530 ms/op
                 existUser·p0.99:   5.652 ms/op
                 existUser·p0.999:  8.638 ms/op
                 existUser·p0.9999: 14.709 ms/op
                 existUser·p1.00:   15.663 ms/op

Iteration   2: 3.605 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.970 ms/op
                 existUser·p0.50:   3.527 ms/op
                 existUser·p0.90:   4.276 ms/op
                 existUser·p0.95:   4.620 ms/op
                 existUser·p0.99:   6.193 ms/op
                 existUser·p0.999:  11.516 ms/op
                 existUser·p0.9999: 15.469 ms/op
                 existUser·p1.00:   16.105 ms/op

Iteration   3: 3.482 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.823 ms/op
                 existUser·p0.50:   3.449 ms/op
                 existUser·p0.90:   4.043 ms/op
                 existUser·p0.95:   4.334 ms/op
                 existUser·p0.99:   5.652 ms/op
                 existUser·p0.999:  11.403 ms/op
                 existUser·p0.9999: 31.386 ms/op
                 existUser·p1.00:   33.030 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 272345
  mean =      3.524 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9019 
    [ 2.500,  5.000) = 257284 
    [ 5.000,  7.500) = 5118 
    [ 7.500, 10.000) = 655 
    [10.000, 12.500) = 131 
    [12.500, 15.000) = 76 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 29 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.726 ms/op
     p(50.0000) =      3.465 ms/op
     p(90.0000) =      4.149 ms/op
     p(95.0000) =      4.514 ms/op
     p(99.0000) =      5.759 ms/op
     p(99.9000) =      9.857 ms/op
     p(99.9900) =     31.162 ms/op
     p(99.9990) =     32.633 ms/op
     p(99.9999) =     33.030 ms/op
    p(100.0000) =     33.030 ms/op


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
# Warmup Iteration   1: 5.421 ±(99.9%) 0.061 ms/op
# Warmup Iteration   2: 4.112 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.805 ±(99.9%) 0.010 ms/op
Iteration   1: 3.766 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.941 ms/op
                 getUser·p0.50:   3.682 ms/op
                 getUser·p0.90:   4.489 ms/op
                 getUser·p0.95:   4.858 ms/op
                 getUser·p0.99:   6.357 ms/op
                 getUser·p0.999:  11.355 ms/op
                 getUser·p0.9999: 16.524 ms/op
                 getUser·p1.00:   16.908 ms/op

Iteration   2: 3.754 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.049 ms/op
                 getUser·p0.50:   3.670 ms/op
                 getUser·p0.90:   4.522 ms/op
                 getUser·p0.95:   4.891 ms/op
                 getUser·p0.99:   6.332 ms/op
                 getUser·p0.999:  10.623 ms/op
                 getUser·p0.9999: 19.251 ms/op
                 getUser·p1.00:   19.595 ms/op

Iteration   3: 3.794 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.768 ms/op
                 getUser·p0.50:   3.711 ms/op
                 getUser·p0.90:   4.555 ms/op
                 getUser·p0.95:   4.940 ms/op
                 getUser·p0.99:   6.726 ms/op
                 getUser·p0.999:  10.709 ms/op
                 getUser·p0.9999: 19.122 ms/op
                 getUser·p1.00:   19.759 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 254508
  mean =      3.771 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 102 
    [ 1.250,  2.500) = 6401 
    [ 2.500,  3.750) = 132740 
    [ 3.750,  5.000) = 104641 
    [ 5.000,  6.250) = 7647 
    [ 6.250,  7.500) = 1608 
    [ 7.500,  8.750) = 725 
    [ 8.750, 10.000) = 300 
    [10.000, 11.250) = 123 
    [11.250, 12.500) = 90 
    [12.500, 13.750) = 3 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 39 
    [16.250, 17.500) = 33 
    [17.500, 18.750) = 25 

  Percentiles, ms/op:
      p(0.0000) =      0.768 ms/op
     p(50.0000) =      3.686 ms/op
     p(90.0000) =      4.522 ms/op
     p(95.0000) =      4.899 ms/op
     p(99.0000) =      6.447 ms/op
     p(99.9000) =     10.789 ms/op
     p(99.9900) =     19.005 ms/op
     p(99.9990) =     19.560 ms/op
     p(99.9999) =     19.759 ms/op
    p(100.0000) =     19.759 ms/op


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
# Warmup Iteration   1: 7.044 ±(99.9%) 0.079 ms/op
# Warmup Iteration   2: 5.133 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.971 ±(99.9%) 0.020 ms/op
Iteration   1: 4.919 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.005 ms/op
                 listUser·p0.50:   4.571 ms/op
                 listUser·p0.90:   6.660 ms/op
                 listUser·p0.95:   7.537 ms/op
                 listUser·p0.99:   9.777 ms/op
                 listUser·p0.999:  20.053 ms/op
                 listUser·p0.9999: 23.986 ms/op
                 listUser·p1.00:   25.068 ms/op

Iteration   2: 4.882 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.368 ms/op
                 listUser·p0.50:   4.604 ms/op
                 listUser·p0.90:   6.308 ms/op
                 listUser·p0.95:   7.201 ms/op
                 listUser·p0.99:   9.093 ms/op
                 listUser·p0.999:  23.738 ms/op
                 listUser·p0.9999: 32.604 ms/op
                 listUser·p1.00:   33.358 ms/op

Iteration   3: 4.908 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.017 ms/op
                 listUser·p0.50:   4.563 ms/op
                 listUser·p0.90:   6.595 ms/op
                 listUser·p0.95:   7.504 ms/op
                 listUser·p0.99:   9.306 ms/op
                 listUser·p0.999:  19.912 ms/op
                 listUser·p0.9999: 23.904 ms/op
                 listUser·p1.00:   24.609 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 195781
  mean =      4.903 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 798 
    [ 2.500,  5.000) = 133000 
    [ 5.000,  7.500) = 52724 
    [ 7.500, 10.000) = 7969 
    [10.000, 12.500) = 823 
    [12.500, 15.000) = 133 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 93 
    [20.000, 22.500) = 104 
    [22.500, 25.000) = 58 
    [25.000, 27.500) = 1 
    [27.500, 30.000) = 45 
    [30.000, 32.500) = 11 
    [32.500, 35.000) = 8 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.005 ms/op
     p(50.0000) =      4.579 ms/op
     p(90.0000) =      6.529 ms/op
     p(95.0000) =      7.430 ms/op
     p(99.0000) =      9.372 ms/op
     p(99.9000) =     20.822 ms/op
     p(99.9900) =     29.997 ms/op
     p(99.9990) =     33.326 ms/op
     p(99.9999) =     33.358 ms/op
    p(100.0000) =     33.358 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.558 ± 1.985  ops/ms
ClientGrpc.existUser                       thrpt       3   8.984 ± 4.196  ops/ms
ClientGrpc.getUser                         thrpt       3   8.714 ± 2.955  ops/ms
ClientGrpc.listUser                        thrpt       3   6.546 ± 2.663  ops/ms
ClientGrpc.createUser                       avgt       3   3.680 ± 0.870   ms/op
ClientGrpc.existUser                        avgt       3   3.525 ± 1.338   ms/op
ClientGrpc.getUser                          avgt       3   3.733 ± 0.943   ms/op
ClientGrpc.listUser                         avgt       3   4.777 ± 2.222   ms/op
ClientGrpc.createUser                     sample  258653   3.715 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.835           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.629           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.506           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.874           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.398           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          14.298           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          38.615           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          40.894           ms/op
ClientGrpc.existUser                      sample  272345   3.524 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.726           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.465           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.149           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.514           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.759           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.857           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          31.162           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          33.030           ms/op
ClientGrpc.getUser                        sample  254508   3.771 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.768           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.686           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.522           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.899           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.447           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.789           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.005           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.759           ms/op
ClientGrpc.listUser                       sample  195781   4.903 ± 0.011   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.005           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.579           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.529           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.430           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.372           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          20.822           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          29.997           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          33.358           ms/op
