# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.923 ops/ms
# Warmup Iteration   2: 10.094 ops/ms
# Warmup Iteration   3: 10.250 ops/ms
Iteration   1: 10.344 ops/ms
Iteration   2: 10.456 ops/ms
Iteration   3: 10.328 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.376 ±(99.9%) 1.275 ops/ms [Average]
  (min, avg, max) = (10.328, 10.376, 10.456), stdev = 0.070
  CI (99.9%): [9.101, 11.650] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 7.995 ops/ms
# Warmup Iteration   2: 10.822 ops/ms
# Warmup Iteration   3: 11.113 ops/ms
Iteration   1: 10.823 ops/ms
Iteration   2: 11.156 ops/ms
Iteration   3: 10.834 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.938 ±(99.9%) 3.460 ops/ms [Average]
  (min, avg, max) = (10.823, 10.938, 11.156), stdev = 0.190
  CI (99.9%): [7.478, 14.397] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.531 ops/ms
# Warmup Iteration   2: 10.443 ops/ms
# Warmup Iteration   3: 10.351 ops/ms
Iteration   1: 10.266 ops/ms
Iteration   2: 10.279 ops/ms
Iteration   3: 10.215 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.253 ±(99.9%) 0.619 ops/ms [Average]
  (min, avg, max) = (10.215, 10.253, 10.279), stdev = 0.034
  CI (99.9%): [9.634, 10.872] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 5.463 ops/ms
# Warmup Iteration   2: 8.023 ops/ms
# Warmup Iteration   3: 8.025 ops/ms
Iteration   1: 8.206 ops/ms
Iteration   2: 8.062 ops/ms
Iteration   3: 8.073 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.114 ±(99.9%) 1.458 ops/ms [Average]
  (min, avg, max) = (8.062, 8.114, 8.206), stdev = 0.080
  CI (99.9%): [6.656, 9.571] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 3.982 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.099 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.095 ±(99.9%) 0.003 ms/op
Iteration   1: 3.181 ±(99.9%) 0.012 ms/op
Iteration   2: 3.136 ±(99.9%) 0.002 ms/op
Iteration   3: 2.959 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.092 ±(99.9%) 2.140 ms/op [Average]
  (min, avg, max) = (2.959, 3.092, 3.181), stdev = 0.117
  CI (99.9%): [0.952, 5.232] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.759 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 3.022 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.960 ±(99.9%) 0.002 ms/op
Iteration   1: 2.878 ±(99.9%) 0.002 ms/op
Iteration   2: 2.854 ±(99.9%) 0.002 ms/op
Iteration   3: 2.901 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.878 ±(99.9%) 0.435 ms/op [Average]
  (min, avg, max) = (2.854, 2.878, 2.901), stdev = 0.024
  CI (99.9%): [2.442, 3.313] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.996 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.128 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.017 ±(99.9%) 0.002 ms/op
Iteration   1: 3.016 ±(99.9%) 0.003 ms/op
Iteration   2: 3.047 ±(99.9%) 0.002 ms/op
Iteration   3: 3.001 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.022 ±(99.9%) 0.426 ms/op [Average]
  (min, avg, max) = (3.001, 3.022, 3.047), stdev = 0.023
  CI (99.9%): [2.596, 3.447] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.845 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.990 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.940 ±(99.9%) 0.025 ms/op
Iteration   1: 3.899 ±(99.9%) 0.017 ms/op
Iteration   2: 3.842 ±(99.9%) 0.028 ms/op
Iteration   3: 3.806 ±(99.9%) 0.024 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.849 ±(99.9%) 0.857 ms/op [Average]
  (min, avg, max) = (3.806, 3.849, 3.899), stdev = 0.047
  CI (99.9%): [2.992, 4.706] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.718 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.070 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.020 ±(99.9%) 0.006 ms/op
Iteration   1: 3.148 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.788 ms/op
                 createUser·p0.50:   3.138 ms/op
                 createUser·p0.90:   3.863 ms/op
                 createUser·p0.95:   4.030 ms/op
                 createUser·p0.99:   4.325 ms/op
                 createUser·p0.999:  8.072 ms/op
                 createUser·p0.9999: 13.787 ms/op
                 createUser·p1.00:   14.008 ms/op

Iteration   2: 3.126 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.838 ms/op
                 createUser·p0.50:   3.101 ms/op
                 createUser·p0.90:   3.797 ms/op
                 createUser·p0.95:   3.965 ms/op
                 createUser·p0.99:   4.243 ms/op
                 createUser·p0.999:  7.000 ms/op
                 createUser·p0.9999: 14.586 ms/op
                 createUser·p1.00:   15.024 ms/op

Iteration   3: 3.034 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.665 ms/op
                 createUser·p0.50:   2.998 ms/op
                 createUser·p0.90:   3.568 ms/op
                 createUser·p0.95:   3.842 ms/op
                 createUser·p0.99:   4.432 ms/op
                 createUser·p0.999:  12.112 ms/op
                 createUser·p0.9999: 23.853 ms/op
                 createUser·p1.00:   24.478 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 309490
  mean =      3.102 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 28135 
    [ 2.500,  5.000) = 280148 
    [ 5.000,  7.500) = 635 
    [ 7.500, 10.000) = 288 
    [10.000, 12.500) = 90 
    [12.500, 15.000) = 128 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 61 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.665 ms/op
     p(50.0000) =      3.072 ms/op
     p(90.0000) =      3.772 ms/op
     p(95.0000) =      3.969 ms/op
     p(99.0000) =      4.317 ms/op
     p(99.9000) =      9.699 ms/op
     p(99.9900) =     23.429 ms/op
     p(99.9990) =     24.337 ms/op
     p(99.9999) =     24.478 ms/op
    p(100.0000) =     24.478 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.696 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 2.988 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.913 ±(99.9%) 0.006 ms/op
Iteration   1: 2.896 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.696 ms/op
                 existUser·p0.50:   2.912 ms/op
                 existUser·p0.90:   3.543 ms/op
                 existUser·p0.95:   3.740 ms/op
                 existUser·p0.99:   4.202 ms/op
                 existUser·p0.999:  6.123 ms/op
                 existUser·p0.9999: 11.484 ms/op
                 existUser·p1.00:   11.829 ms/op

Iteration   2: 2.995 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.752 ms/op
                 existUser·p0.50:   2.966 ms/op
                 existUser·p0.90:   3.645 ms/op
                 existUser·p0.95:   3.838 ms/op
                 existUser·p0.99:   4.149 ms/op
                 existUser·p0.999:  6.580 ms/op
                 existUser·p0.9999: 14.898 ms/op
                 existUser·p1.00:   15.204 ms/op

Iteration   3: 2.970 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.649 ms/op
                 existUser·p0.50:   2.949 ms/op
                 existUser·p0.90:   3.584 ms/op
                 existUser·p0.95:   3.764 ms/op
                 existUser·p0.99:   4.170 ms/op
                 existUser·p0.999:  10.453 ms/op
                 existUser·p0.9999: 14.486 ms/op
                 existUser·p1.00:   16.155 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 325052
  mean =      2.953 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3155 
    [ 1.250,  2.500) = 46780 
    [ 2.500,  3.750) = 256559 
    [ 3.750,  5.000) = 17693 
    [ 5.000,  6.250) = 428 
    [ 6.250,  7.500) = 111 
    [ 7.500,  8.750) = 38 
    [ 8.750, 10.000) = 36 
    [10.000, 11.250) = 64 
    [11.250, 12.500) = 69 
    [12.500, 13.750) = 40 
    [13.750, 15.000) = 69 
    [15.000, 16.250) = 10 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.649 ms/op
     p(50.0000) =      2.941 ms/op
     p(90.0000) =      3.592 ms/op
     p(95.0000) =      3.785 ms/op
     p(99.0000) =      4.174 ms/op
     p(99.9000) =      7.535 ms/op
     p(99.9900) =     14.565 ms/op
     p(99.9990) =     15.421 ms/op
     p(99.9999) =     16.155 ms/op
    p(100.0000) =     16.155 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.070 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.125 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.052 ±(99.9%) 0.007 ms/op
Iteration   1: 3.104 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.676 ms/op
                 getUser·p0.50:   3.080 ms/op
                 getUser·p0.90:   3.736 ms/op
                 getUser·p0.95:   3.936 ms/op
                 getUser·p0.99:   4.252 ms/op
                 getUser·p0.999:  7.222 ms/op
                 getUser·p0.9999: 11.633 ms/op
                 getUser·p1.00:   12.550 ms/op

Iteration   2: 2.995 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.658 ms/op
                 getUser·p0.50:   3.011 ms/op
                 getUser·p0.90:   3.473 ms/op
                 getUser·p0.95:   3.703 ms/op
                 getUser·p0.99:   4.211 ms/op
                 getUser·p0.999:  7.420 ms/op
                 getUser·p0.9999: 13.282 ms/op
                 getUser·p1.00:   14.680 ms/op

Iteration   3: 3.041 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.736 ms/op
                 getUser·p0.50:   3.027 ms/op
                 getUser·p0.90:   3.682 ms/op
                 getUser·p0.95:   3.891 ms/op
                 getUser·p0.99:   4.317 ms/op
                 getUser·p0.999:  7.847 ms/op
                 getUser·p0.9999: 16.720 ms/op
                 getUser·p1.00:   16.876 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 314891
  mean =      3.046 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1684 
    [ 1.250,  2.500) = 25253 
    [ 2.500,  3.750) = 264990 
    [ 3.750,  5.000) = 21990 
    [ 5.000,  6.250) = 386 
    [ 6.250,  7.500) = 264 
    [ 7.500,  8.750) = 91 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 65 
    [11.250, 12.500) = 72 
    [12.500, 13.750) = 51 
    [13.750, 15.000) = 13 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 32 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.658 ms/op
     p(50.0000) =      3.035 ms/op
     p(90.0000) =      3.645 ms/op
     p(95.0000) =      3.871 ms/op
     p(99.0000) =      4.268 ms/op
     p(99.9000) =      7.554 ms/op
     p(99.9900) =     16.351 ms/op
     p(99.9990) =     16.838 ms/op
     p(99.9999) =     16.876 ms/op
    p(100.0000) =     16.876 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.921 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.983 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.002 ±(99.9%) 0.011 ms/op
Iteration   1: 3.943 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.859 ms/op
                 listUser·p0.50:   3.781 ms/op
                 listUser·p0.90:   5.046 ms/op
                 listUser·p0.95:   5.505 ms/op
                 listUser·p0.99:   6.521 ms/op
                 listUser·p0.999:  13.106 ms/op
                 listUser·p0.9999: 16.581 ms/op
                 listUser·p1.00:   16.941 ms/op

Iteration   2: 3.908 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.908 ms/op
                 listUser·p0.50:   3.731 ms/op
                 listUser·p0.90:   4.997 ms/op
                 listUser·p0.95:   5.497 ms/op
                 listUser·p0.99:   6.865 ms/op
                 listUser·p0.999:  14.484 ms/op
                 listUser·p0.9999: 22.184 ms/op
                 listUser·p1.00:   22.708 ms/op

Iteration   3: 3.906 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.913 ms/op
                 listUser·p0.50:   3.768 ms/op
                 listUser·p0.90:   4.915 ms/op
                 listUser·p0.95:   5.456 ms/op
                 listUser·p0.99:   6.619 ms/op
                 listUser·p0.999:  13.649 ms/op
                 listUser·p0.9999: 19.464 ms/op
                 listUser·p1.00:   25.068 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 245000
  mean =      3.919 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4102 
    [ 2.500,  5.000) = 216741 
    [ 5.000,  7.500) = 23172 
    [ 7.500, 10.000) = 568 
    [10.000, 12.500) = 54 
    [12.500, 15.000) = 227 
    [15.000, 17.500) = 83 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.859 ms/op
     p(50.0000) =      3.760 ms/op
     p(90.0000) =      4.989 ms/op
     p(95.0000) =      5.480 ms/op
     p(99.0000) =      6.660 ms/op
     p(99.9000) =     13.730 ms/op
     p(99.9900) =     18.989 ms/op
     p(99.9990) =     22.708 ms/op
     p(99.9999) =     25.068 ms/op
    p(100.0000) =     25.068 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.376 ± 1.275  ops/ms
ClientGrpc.existUser                       thrpt       3  10.938 ± 3.460  ops/ms
ClientGrpc.getUser                         thrpt       3  10.253 ± 0.619  ops/ms
ClientGrpc.listUser                        thrpt       3   8.114 ± 1.458  ops/ms
ClientGrpc.createUser                       avgt       3   3.092 ± 2.140   ms/op
ClientGrpc.existUser                        avgt       3   2.878 ± 0.435   ms/op
ClientGrpc.getUser                          avgt       3   3.022 ± 0.426   ms/op
ClientGrpc.listUser                         avgt       3   3.849 ± 0.857   ms/op
ClientGrpc.createUser                     sample  309490   3.102 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.665           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.072           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.772           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.969           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.317           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.699           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          23.429           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          24.478           ms/op
ClientGrpc.existUser                      sample  325052   2.953 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.649           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.941           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.592           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.785           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.174           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.535           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.565           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          16.155           ms/op
ClientGrpc.getUser                        sample  314891   3.046 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.658           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.035           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.645           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.871           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.268           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.554           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.351           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          16.876           ms/op
ClientGrpc.listUser                       sample  245000   3.919 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.859           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.760           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.989           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.480           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.660           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.730           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          18.989           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.068           ms/op
