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
# Warmup Iteration   1: 4.432 ops/ms
# Warmup Iteration   2: 9.198 ops/ms
# Warmup Iteration   3: 10.073 ops/ms
Iteration   1: 10.600 ops/ms
Iteration   2: 10.720 ops/ms
Iteration   3: 10.653 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.658 ±(99.9%) 1.093 ops/ms [Average]
  (min, avg, max) = (10.600, 10.658, 10.720), stdev = 0.060
  CI (99.9%): [9.565, 11.750] (assumes normal distribution)


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
# Warmup Iteration   1: 7.366 ops/ms
# Warmup Iteration   2: 10.550 ops/ms
# Warmup Iteration   3: 11.172 ops/ms
Iteration   1: 11.230 ops/ms
Iteration   2: 10.819 ops/ms
Iteration   3: 10.956 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.002 ±(99.9%) 3.812 ops/ms [Average]
  (min, avg, max) = (10.819, 11.002, 11.230), stdev = 0.209
  CI (99.9%): [7.190, 14.814] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 6.753 ops/ms
# Warmup Iteration   2: 9.907 ops/ms
# Warmup Iteration   3: 10.509 ops/ms
Iteration   1: 10.616 ops/ms
Iteration   2: 10.538 ops/ms
Iteration   3: 10.346 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.500 ±(99.9%) 2.528 ops/ms [Average]
  (min, avg, max) = (10.346, 10.500, 10.616), stdev = 0.139
  CI (99.9%): [7.972, 13.028] (assumes normal distribution)


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
# Warmup Iteration   1: 5.723 ops/ms
# Warmup Iteration   2: 7.641 ops/ms
# Warmup Iteration   3: 8.117 ops/ms
Iteration   1: 8.217 ops/ms
Iteration   2: 8.243 ops/ms
Iteration   3: 8.037 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.166 ±(99.9%) 2.045 ops/ms [Average]
  (min, avg, max) = (8.037, 8.166, 8.243), stdev = 0.112
  CI (99.9%): [6.121, 10.211] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.211 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.145 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.052 ±(99.9%) 0.002 ms/op
Iteration   1: 3.065 ±(99.9%) 0.002 ms/op
Iteration   2: 3.043 ±(99.9%) 0.002 ms/op
Iteration   3: 3.062 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.057 ±(99.9%) 0.215 ms/op [Average]
  (min, avg, max) = (3.043, 3.057, 3.065), stdev = 0.012
  CI (99.9%): [2.842, 3.272] (assumes normal distribution)


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
# Warmup Iteration   1: 4.035 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 2.990 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.907 ±(99.9%) 0.002 ms/op
Iteration   1: 2.899 ±(99.9%) 0.002 ms/op
Iteration   2: 2.895 ±(99.9%) 0.002 ms/op
Iteration   3: 2.890 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.894 ±(99.9%) 0.088 ms/op [Average]
  (min, avg, max) = (2.890, 2.894, 2.899), stdev = 0.005
  CI (99.9%): [2.807, 2.982] (assumes normal distribution)


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
# Warmup Iteration   1: 4.182 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.129 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.048 ±(99.9%) 0.003 ms/op
Iteration   1: 2.971 ±(99.9%) 0.003 ms/op
Iteration   2: 3.015 ±(99.9%) 0.003 ms/op
Iteration   3: 3.011 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.999 ±(99.9%) 0.447 ms/op [Average]
  (min, avg, max) = (2.971, 2.999, 3.015), stdev = 0.024
  CI (99.9%): [2.552, 3.446] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.288 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 4.267 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.886 ±(99.9%) 0.010 ms/op
Iteration   1: 3.975 ±(99.9%) 0.017 ms/op
Iteration   2: 3.927 ±(99.9%) 0.026 ms/op
Iteration   3: 3.912 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.938 ±(99.9%) 0.609 ms/op [Average]
  (min, avg, max) = (3.912, 3.938, 3.975), stdev = 0.033
  CI (99.9%): [3.329, 4.547] (assumes normal distribution)


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
# Warmup Iteration   1: 4.487 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.239 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.028 ±(99.9%) 0.006 ms/op
Iteration   1: 3.101 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.889 ms/op
                 createUser·p0.50:   3.035 ms/op
                 createUser·p0.90:   3.690 ms/op
                 createUser·p0.95:   3.957 ms/op
                 createUser·p0.99:   4.784 ms/op
                 createUser·p0.999:  7.642 ms/op
                 createUser·p0.9999: 13.752 ms/op
                 createUser·p1.00:   14.074 ms/op

Iteration   2: 3.114 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.680 ms/op
                 createUser·p0.50:   3.060 ms/op
                 createUser·p0.90:   3.674 ms/op
                 createUser·p0.95:   3.899 ms/op
                 createUser·p0.99:   4.735 ms/op
                 createUser·p0.999:  8.770 ms/op
                 createUser·p0.9999: 14.814 ms/op
                 createUser·p1.00:   15.696 ms/op

Iteration   3: 3.037 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.823 ms/op
                 createUser·p0.50:   3.006 ms/op
                 createUser·p0.90:   3.653 ms/op
                 createUser·p0.95:   3.875 ms/op
                 createUser·p0.99:   4.653 ms/op
                 createUser·p0.999:  8.892 ms/op
                 createUser·p0.9999: 15.712 ms/op
                 createUser·p1.00:   16.777 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 311181
  mean =      3.083 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 499 
    [ 1.250,  2.500) = 20585 
    [ 2.500,  3.750) = 264882 
    [ 3.750,  5.000) = 22975 
    [ 5.000,  6.250) = 1467 
    [ 6.250,  7.500) = 339 
    [ 7.500,  8.750) = 157 
    [ 8.750, 10.000) = 52 
    [10.000, 11.250) = 25 
    [11.250, 12.500) = 8 
    [12.500, 13.750) = 55 
    [13.750, 15.000) = 96 
    [15.000, 16.250) = 40 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.680 ms/op
     p(50.0000) =      3.035 ms/op
     p(90.0000) =      3.670 ms/op
     p(95.0000) =      3.912 ms/op
     p(99.0000) =      4.727 ms/op
     p(99.9000) =      8.345 ms/op
     p(99.9900) =     15.493 ms/op
     p(99.9990) =     15.925 ms/op
     p(99.9999) =     16.777 ms/op
    p(100.0000) =     16.777 ms/op


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
# Warmup Iteration   1: 4.302 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.015 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.938 ±(99.9%) 0.006 ms/op
Iteration   1: 2.891 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.794 ms/op
                 existUser·p0.50:   2.855 ms/op
                 existUser·p0.90:   3.297 ms/op
                 existUser·p0.95:   3.506 ms/op
                 existUser·p0.99:   4.653 ms/op
                 existUser·p0.999:  7.196 ms/op
                 existUser·p0.9999: 22.575 ms/op
                 existUser·p1.00:   23.101 ms/op

Iteration   2: 2.898 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.786 ms/op
                 existUser·p0.50:   2.888 ms/op
                 existUser·p0.90:   3.330 ms/op
                 existUser·p0.95:   3.506 ms/op
                 existUser·p0.99:   4.092 ms/op
                 existUser·p0.999:  6.414 ms/op
                 existUser·p0.9999: 17.792 ms/op
                 existUser·p1.00:   18.383 ms/op

Iteration   3: 2.887 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.658 ms/op
                 existUser·p0.50:   2.863 ms/op
                 existUser·p0.90:   3.387 ms/op
                 existUser·p0.95:   3.600 ms/op
                 existUser·p0.99:   4.653 ms/op
                 existUser·p0.999:  8.503 ms/op
                 existUser·p0.9999: 19.265 ms/op
                 existUser·p1.00:   19.759 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 331797
  mean =      2.892 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 43889 
    [ 2.500,  5.000) = 286077 
    [ 5.000,  7.500) = 1494 
    [ 7.500, 10.000) = 171 
    [10.000, 12.500) = 6 
    [12.500, 15.000) = 15 
    [15.000, 17.500) = 36 
    [17.500, 20.000) = 77 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.658 ms/op
     p(50.0000) =      2.867 ms/op
     p(90.0000) =      3.338 ms/op
     p(95.0000) =      3.539 ms/op
     p(99.0000) =      4.465 ms/op
     p(99.9000) =      7.520 ms/op
     p(99.9900) =     19.747 ms/op
     p(99.9990) =     22.950 ms/op
     p(99.9999) =     23.101 ms/op
    p(100.0000) =     23.101 ms/op


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
# Warmup Iteration   1: 4.317 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.167 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.074 ±(99.9%) 0.006 ms/op
Iteration   1: 3.031 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.916 ms/op
                 getUser·p0.50:   2.990 ms/op
                 getUser·p0.90:   3.629 ms/op
                 getUser·p0.95:   3.846 ms/op
                 getUser·p0.99:   4.612 ms/op
                 getUser·p0.999:  7.715 ms/op
                 getUser·p0.9999: 13.812 ms/op
                 getUser·p1.00:   14.025 ms/op

Iteration   2: 3.022 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.561 ms/op
                 getUser·p0.50:   2.978 ms/op
                 getUser·p0.90:   3.576 ms/op
                 getUser·p0.95:   3.809 ms/op
                 getUser·p0.99:   4.891 ms/op
                 getUser·p0.999:  7.669 ms/op
                 getUser·p0.9999: 14.481 ms/op
                 getUser·p1.00:   14.696 ms/op

Iteration   3: 3.070 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.835 ms/op
                 getUser·p0.50:   3.023 ms/op
                 getUser·p0.90:   3.547 ms/op
                 getUser·p0.95:   3.731 ms/op
                 getUser·p0.99:   4.713 ms/op
                 getUser·p0.999:  8.389 ms/op
                 getUser·p0.9999: 17.176 ms/op
                 getUser·p1.00:   17.596 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 315588
  mean =      3.041 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 518 
    [ 1.250,  2.500) = 20933 
    [ 2.500,  3.750) = 275297 
    [ 3.750,  5.000) = 16577 
    [ 5.000,  6.250) = 1298 
    [ 6.250,  7.500) = 591 
    [ 7.500,  8.750) = 139 
    [ 8.750, 10.000) = 11 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 43 
    [12.500, 13.750) = 53 
    [13.750, 15.000) = 64 
    [15.000, 16.250) = 19 
    [16.250, 17.500) = 43 
    [17.500, 18.750) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.561 ms/op
     p(50.0000) =      2.998 ms/op
     p(90.0000) =      3.580 ms/op
     p(95.0000) =      3.801 ms/op
     p(99.0000) =      4.727 ms/op
     p(99.9000) =      7.786 ms/op
     p(99.9900) =     16.466 ms/op
     p(99.9990) =     17.450 ms/op
     p(99.9999) =     17.596 ms/op
    p(100.0000) =     17.596 ms/op


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
# Warmup Iteration   1: 5.544 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 4.143 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.819 ±(99.9%) 0.012 ms/op
Iteration   1: 3.916 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.311 ms/op
                 listUser·p0.50:   3.748 ms/op
                 listUser·p0.90:   4.891 ms/op
                 listUser·p0.95:   5.784 ms/op
                 listUser·p0.99:   7.045 ms/op
                 listUser·p0.999:  16.941 ms/op
                 listUser·p0.9999: 23.872 ms/op
                 listUser·p1.00:   24.412 ms/op

Iteration   2: 3.998 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.151 ms/op
                 listUser·p0.50:   3.813 ms/op
                 listUser·p0.90:   5.194 ms/op
                 listUser·p0.95:   5.939 ms/op
                 listUser·p0.99:   7.078 ms/op
                 listUser·p0.999:  17.152 ms/op
                 listUser·p0.9999: 27.197 ms/op
                 listUser·p1.00:   27.329 ms/op

Iteration   3: 3.946 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.190 ms/op
                 listUser·p0.50:   3.777 ms/op
                 listUser·p0.90:   4.932 ms/op
                 listUser·p0.95:   5.628 ms/op
                 listUser·p0.99:   6.971 ms/op
                 listUser·p0.999:  16.122 ms/op
                 listUser·p0.9999: 24.860 ms/op
                 listUser·p1.00:   26.345 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 242883
  mean =      3.953 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3648 
    [ 2.500,  5.000) = 214745 
    [ 5.000,  7.500) = 22981 
    [ 7.500, 10.000) = 1056 
    [10.000, 12.500) = 66 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 162 
    [17.500, 20.000) = 79 
    [20.000, 22.500) = 37 
    [22.500, 25.000) = 41 
    [25.000, 27.500) = 36 

  Percentiles, ms/op:
      p(0.0000) =      1.151 ms/op
     p(50.0000) =      3.777 ms/op
     p(90.0000) =      5.014 ms/op
     p(95.0000) =      5.800 ms/op
     p(99.0000) =      7.030 ms/op
     p(99.9000) =     16.679 ms/op
     p(99.9900) =     26.542 ms/op
     p(99.9990) =     27.314 ms/op
     p(99.9999) =     27.329 ms/op
    p(100.0000) =     27.329 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.658 ± 1.093  ops/ms
ClientGrpc.existUser                       thrpt       3  11.002 ± 3.812  ops/ms
ClientGrpc.getUser                         thrpt       3  10.500 ± 2.528  ops/ms
ClientGrpc.listUser                        thrpt       3   8.166 ± 2.045  ops/ms
ClientGrpc.createUser                       avgt       3   3.057 ± 0.215   ms/op
ClientGrpc.existUser                        avgt       3   2.894 ± 0.088   ms/op
ClientGrpc.getUser                          avgt       3   2.999 ± 0.447   ms/op
ClientGrpc.listUser                         avgt       3   3.938 ± 0.609   ms/op
ClientGrpc.createUser                     sample  311181   3.083 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.680           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.035           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.670           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.912           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.727           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.345           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          15.493           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          16.777           ms/op
ClientGrpc.existUser                      sample  331797   2.892 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.658           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.867           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.338           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.539           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.465           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.520           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.747           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          23.101           ms/op
ClientGrpc.getUser                        sample  315588   3.041 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.561           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.998           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.580           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.801           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.727           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.786           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.466           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          17.596           ms/op
ClientGrpc.listUser                       sample  242883   3.953 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.151           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.777           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.014           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.800           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.030           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.679           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          26.542           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.329           ms/op
