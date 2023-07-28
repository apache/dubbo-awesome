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
# Warmup Iteration   1: 3.582 ops/ms
# Warmup Iteration   2: 8.884 ops/ms
# Warmup Iteration   3: 10.036 ops/ms
Iteration   1: 10.600 ops/ms
Iteration   2: 10.427 ops/ms
Iteration   3: 10.643 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.557 ±(99.9%) 2.089 ops/ms [Average]
  (min, avg, max) = (10.427, 10.557, 10.643), stdev = 0.114
  CI (99.9%): [8.468, 12.646] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.064 ops/ms
# Warmup Iteration   2: 10.184 ops/ms
# Warmup Iteration   3: 10.818 ops/ms
Iteration   1: 10.841 ops/ms
Iteration   2: 10.981 ops/ms
Iteration   3: 10.747 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.856 ±(99.9%) 2.147 ops/ms [Average]
  (min, avg, max) = (10.747, 10.856, 10.981), stdev = 0.118
  CI (99.9%): [8.710, 13.003] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.166 ops/ms
# Warmup Iteration   2: 10.080 ops/ms
# Warmup Iteration   3: 10.143 ops/ms
Iteration   1: 10.209 ops/ms
Iteration   2: 10.660 ops/ms
Iteration   3: 10.364 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.411 ±(99.9%) 4.177 ops/ms [Average]
  (min, avg, max) = (10.209, 10.411, 10.660), stdev = 0.229
  CI (99.9%): [6.234, 14.588] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.217 ops/ms
# Warmup Iteration   2: 7.674 ops/ms
# Warmup Iteration   3: 7.729 ops/ms
Iteration   1: 7.826 ops/ms
Iteration   2: 8.084 ops/ms
Iteration   3: 7.805 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.905 ±(99.9%) 2.839 ops/ms [Average]
  (min, avg, max) = (7.805, 7.905, 8.084), stdev = 0.156
  CI (99.9%): [5.066, 10.744] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.560 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.215 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.084 ±(99.9%) 0.003 ms/op
Iteration   1: 3.168 ±(99.9%) 0.002 ms/op
Iteration   2: 3.065 ±(99.9%) 0.002 ms/op
Iteration   3: 3.092 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.108 ±(99.9%) 0.977 ms/op [Average]
  (min, avg, max) = (3.065, 3.108, 3.168), stdev = 0.054
  CI (99.9%): [2.132, 4.085] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.912 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.996 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.930 ±(99.9%) 0.002 ms/op
Iteration   1: 2.949 ±(99.9%) 0.002 ms/op
Iteration   2: 2.907 ±(99.9%) 0.003 ms/op
Iteration   3: 2.924 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.927 ±(99.9%) 0.390 ms/op [Average]
  (min, avg, max) = (2.907, 2.927, 2.949), stdev = 0.021
  CI (99.9%): [2.536, 3.317] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.558 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.251 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.082 ±(99.9%) 0.002 ms/op
Iteration   1: 3.090 ±(99.9%) 0.004 ms/op
Iteration   2: 3.083 ±(99.9%) 0.002 ms/op
Iteration   3: 3.099 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.091 ±(99.9%) 0.141 ms/op [Average]
  (min, avg, max) = (3.083, 3.091, 3.099), stdev = 0.008
  CI (99.9%): [2.949, 3.232] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.549 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 4.202 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.074 ±(99.9%) 0.024 ms/op
Iteration   1: 4.045 ±(99.9%) 0.009 ms/op
Iteration   2: 4.015 ±(99.9%) 0.030 ms/op
Iteration   3: 4.077 ±(99.9%) 0.034 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.045 ±(99.9%) 0.568 ms/op [Average]
  (min, avg, max) = (4.015, 4.045, 4.077), stdev = 0.031
  CI (99.9%): [3.478, 4.613] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.355 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.223 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.139 ±(99.9%) 0.007 ms/op
Iteration   1: 3.098 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.786 ms/op
                 createUser·p0.50:   3.060 ms/op
                 createUser·p0.90:   3.613 ms/op
                 createUser·p0.95:   3.850 ms/op
                 createUser·p0.99:   4.694 ms/op
                 createUser·p0.999:  12.055 ms/op
                 createUser·p0.9999: 18.962 ms/op
                 createUser·p1.00:   19.530 ms/op

Iteration   2: 3.021 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.725 ms/op
                 createUser·p0.50:   2.994 ms/op
                 createUser·p0.90:   3.408 ms/op
                 createUser·p0.95:   3.555 ms/op
                 createUser·p0.99:   4.184 ms/op
                 createUser·p0.999:  7.104 ms/op
                 createUser·p0.9999: 14.041 ms/op
                 createUser·p1.00:   14.270 ms/op

Iteration   3: 3.094 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.574 ms/op
                 createUser·p0.50:   3.056 ms/op
                 createUser·p0.90:   3.666 ms/op
                 createUser·p0.95:   3.895 ms/op
                 createUser·p0.99:   4.773 ms/op
                 createUser·p0.999:  8.946 ms/op
                 createUser·p0.9999: 25.130 ms/op
                 createUser·p1.00:   25.919 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 312674
  mean =      3.071 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17712 
    [ 2.500,  5.000) = 292992 
    [ 5.000,  7.500) = 1496 
    [ 7.500, 10.000) = 201 
    [10.000, 12.500) = 60 
    [12.500, 15.000) = 105 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 44 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.574 ms/op
     p(50.0000) =      3.035 ms/op
     p(90.0000) =      3.564 ms/op
     p(95.0000) =      3.793 ms/op
     p(99.0000) =      4.588 ms/op
     p(99.9000) =      9.032 ms/op
     p(99.9900) =     24.674 ms/op
     p(99.9990) =     25.846 ms/op
     p(99.9999) =     25.919 ms/op
    p(100.0000) =     25.919 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.868 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.046 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.019 ±(99.9%) 0.006 ms/op
Iteration   1: 2.903 ±(99.9%) 0.004 ms/op
                 existUser·p0.00:   1.065 ms/op
                 existUser·p0.50:   2.867 ms/op
                 existUser·p0.90:   3.269 ms/op
                 existUser·p0.95:   3.416 ms/op
                 existUser·p0.99:   3.858 ms/op
                 existUser·p0.999:  6.174 ms/op
                 existUser·p0.9999: 16.122 ms/op
                 existUser·p1.00:   16.581 ms/op

Iteration   2: 2.931 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.727 ms/op
                 existUser·p0.50:   2.900 ms/op
                 existUser·p0.90:   3.375 ms/op
                 existUser·p0.95:   3.551 ms/op
                 existUser·p0.99:   4.235 ms/op
                 existUser·p0.999:  8.498 ms/op
                 existUser·p0.9999: 14.929 ms/op
                 existUser·p1.00:   15.614 ms/op

Iteration   3: 2.982 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.760 ms/op
                 existUser·p0.50:   2.941 ms/op
                 existUser·p0.90:   3.498 ms/op
                 existUser·p0.95:   3.731 ms/op
                 existUser·p0.99:   4.465 ms/op
                 existUser·p0.999:  10.964 ms/op
                 existUser·p0.9999: 15.311 ms/op
                 existUser·p1.00:   15.679 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 326681
  mean =      2.938 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 629 
    [ 1.250,  2.500) = 31780 
    [ 2.500,  3.750) = 284875 
    [ 3.750,  5.000) = 8098 
    [ 5.000,  6.250) = 537 
    [ 6.250,  7.500) = 327 
    [ 7.500,  8.750) = 122 
    [ 8.750, 10.000) = 28 
    [10.000, 11.250) = 57 
    [11.250, 12.500) = 71 
    [12.500, 13.750) = 60 
    [13.750, 15.000) = 40 
    [15.000, 16.250) = 49 
    [16.250, 17.500) = 8 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.727 ms/op
     p(50.0000) =      2.900 ms/op
     p(90.0000) =      3.371 ms/op
     p(95.0000) =      3.584 ms/op
     p(99.0000) =      4.154 ms/op
     p(99.9000) =      8.536 ms/op
     p(99.9900) =     15.554 ms/op
     p(99.9990) =     16.453 ms/op
     p(99.9999) =     16.581 ms/op
    p(100.0000) =     16.581 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.706 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.330 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.114 ±(99.9%) 0.006 ms/op
Iteration   1: 3.074 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.723 ms/op
                 getUser·p0.50:   3.056 ms/op
                 getUser·p0.90:   3.453 ms/op
                 getUser·p0.95:   3.707 ms/op
                 getUser·p0.99:   4.612 ms/op
                 getUser·p0.999:  8.200 ms/op
                 getUser·p0.9999: 13.527 ms/op
                 getUser·p1.00:   13.681 ms/op

Iteration   2: 3.115 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.779 ms/op
                 getUser·p0.50:   3.076 ms/op
                 getUser·p0.90:   3.658 ms/op
                 getUser·p0.95:   3.932 ms/op
                 getUser·p0.99:   5.063 ms/op
                 getUser·p0.999:  10.021 ms/op
                 getUser·p0.9999: 21.937 ms/op
                 getUser·p1.00:   22.577 ms/op

Iteration   3: 3.055 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.852 ms/op
                 getUser·p0.50:   3.023 ms/op
                 getUser·p0.90:   3.494 ms/op
                 getUser·p0.95:   3.715 ms/op
                 getUser·p0.99:   4.481 ms/op
                 getUser·p0.999:  7.784 ms/op
                 getUser·p0.9999: 23.265 ms/op
                 getUser·p1.00:   23.658 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 311542
  mean =      3.081 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15556 
    [ 2.500,  5.000) = 293625 
    [ 5.000,  7.500) = 1898 
    [ 7.500, 10.000) = 224 
    [10.000, 12.500) = 79 
    [12.500, 15.000) = 57 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 33 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.723 ms/op
     p(50.0000) =      3.052 ms/op
     p(90.0000) =      3.543 ms/op
     p(95.0000) =      3.797 ms/op
     p(99.0000) =      4.748 ms/op
     p(99.9000) =      8.487 ms/op
     p(99.9900) =     22.660 ms/op
     p(99.9990) =     23.454 ms/op
     p(99.9999) =     23.658 ms/op
    p(100.0000) =     23.658 ms/op


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
# Warmup Iteration   1: 5.118 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 4.513 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.133 ±(99.9%) 0.012 ms/op
Iteration   1: 4.089 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.217 ms/op
                 listUser·p0.50:   3.895 ms/op
                 listUser·p0.90:   5.161 ms/op
                 listUser·p0.95:   5.734 ms/op
                 listUser·p0.99:   7.324 ms/op
                 listUser·p0.999:  14.013 ms/op
                 listUser·p0.9999: 15.503 ms/op
                 listUser·p1.00:   16.810 ms/op

Iteration   2: 3.986 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.999 ms/op
                 listUser·p0.50:   3.850 ms/op
                 listUser·p0.90:   4.768 ms/op
                 listUser·p0.95:   5.519 ms/op
                 listUser·p0.99:   6.922 ms/op
                 listUser·p0.999:  15.039 ms/op
                 listUser·p0.9999: 17.595 ms/op
                 listUser·p1.00:   18.383 ms/op

Iteration   3: 4.062 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.210 ms/op
                 listUser·p0.50:   3.887 ms/op
                 listUser·p0.90:   4.997 ms/op
                 listUser·p0.95:   5.825 ms/op
                 listUser·p0.99:   7.102 ms/op
                 listUser·p0.999:  14.710 ms/op
                 listUser·p0.9999: 32.146 ms/op
                 listUser·p1.00:   33.194 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 237338
  mean =      4.045 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1512 
    [ 2.500,  5.000) = 212024 
    [ 5.000,  7.500) = 22203 
    [ 7.500, 10.000) = 1142 
    [10.000, 12.500) = 71 
    [12.500, 15.000) = 220 
    [15.000, 17.500) = 112 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 26 
    [32.500, 35.000) = 6 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.999 ms/op
     p(50.0000) =      3.879 ms/op
     p(90.0000) =      5.005 ms/op
     p(95.0000) =      5.693 ms/op
     p(99.0000) =      7.127 ms/op
     p(99.9000) =     14.500 ms/op
     p(99.9900) =     31.287 ms/op
     p(99.9990) =     32.821 ms/op
     p(99.9999) =     33.194 ms/op
    p(100.0000) =     33.194 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.557 ± 2.089  ops/ms
ClientGrpc.existUser                       thrpt       3  10.856 ± 2.147  ops/ms
ClientGrpc.getUser                         thrpt       3  10.411 ± 4.177  ops/ms
ClientGrpc.listUser                        thrpt       3   7.905 ± 2.839  ops/ms
ClientGrpc.createUser                       avgt       3   3.108 ± 0.977   ms/op
ClientGrpc.existUser                        avgt       3   2.927 ± 0.390   ms/op
ClientGrpc.getUser                          avgt       3   3.091 ± 0.141   ms/op
ClientGrpc.listUser                         avgt       3   4.045 ± 0.568   ms/op
ClientGrpc.createUser                     sample  312674   3.071 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.574           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.035           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.564           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.793           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.588           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.032           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          24.674           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          25.919           ms/op
ClientGrpc.existUser                      sample  326681   2.938 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.727           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.900           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.371           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.584           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.154           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.536           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.554           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          16.581           ms/op
ClientGrpc.getUser                        sample  311542   3.081 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.723           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.052           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.543           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.797           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.748           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.487           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          22.660           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.658           ms/op
ClientGrpc.listUser                       sample  237338   4.045 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.999           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.879           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.005           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.693           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.127           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.500           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          31.287           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          33.194           ms/op
