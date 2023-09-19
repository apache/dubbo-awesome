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
# Warmup Iteration   1: 3.754 ops/ms
# Warmup Iteration   2: 8.836 ops/ms
# Warmup Iteration   3: 9.814 ops/ms
Iteration   1: 9.891 ops/ms
Iteration   2: 10.213 ops/ms
Iteration   3: 10.115 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.073 ±(99.9%) 3.003 ops/ms [Average]
  (min, avg, max) = (9.891, 10.073, 10.213), stdev = 0.165
  CI (99.9%): [7.070, 13.076] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 7.043 ops/ms
# Warmup Iteration   2: 10.012 ops/ms
# Warmup Iteration   3: 10.810 ops/ms
Iteration   1: 10.591 ops/ms
Iteration   2: 10.646 ops/ms
Iteration   3: 10.798 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.678 ±(99.9%) 1.958 ops/ms [Average]
  (min, avg, max) = (10.591, 10.678, 10.798), stdev = 0.107
  CI (99.9%): [8.720, 12.636] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:54
# Fork: 1 of 1
# Warmup Iteration   1: 6.726 ops/ms
# Warmup Iteration   2: 9.747 ops/ms
# Warmup Iteration   3: 10.121 ops/ms
Iteration   1: 10.185 ops/ms
Iteration   2: 10.119 ops/ms
Iteration   3: 10.180 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.161 ±(99.9%) 0.666 ops/ms [Average]
  (min, avg, max) = (10.119, 10.161, 10.185), stdev = 0.037
  CI (99.9%): [9.495, 10.827] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 5.209 ops/ms
# Warmup Iteration   2: 7.623 ops/ms
# Warmup Iteration   3: 7.898 ops/ms
Iteration   1: 8.046 ops/ms
Iteration   2: 7.937 ops/ms
Iteration   3: 7.895 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.960 ±(99.9%) 1.419 ops/ms [Average]
  (min, avg, max) = (7.895, 7.960, 8.046), stdev = 0.078
  CI (99.9%): [6.541, 9.378] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.549 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.307 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.202 ±(99.9%) 0.001 ms/op
Iteration   1: 3.145 ±(99.9%) 0.004 ms/op
Iteration   2: 3.161 ±(99.9%) 0.002 ms/op
Iteration   3: 3.180 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.162 ±(99.9%) 0.321 ms/op [Average]
  (min, avg, max) = (3.145, 3.162, 3.180), stdev = 0.018
  CI (99.9%): [2.841, 3.483] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 3.975 ±(99.9%) 0.008 ms/op
# Warmup Iteration   2: 3.106 ±(99.9%) 0.001 ms/op
# Warmup Iteration   3: 3.056 ±(99.9%) 0.002 ms/op
Iteration   1: 2.945 ±(99.9%) 0.002 ms/op
Iteration   2: 2.934 ±(99.9%) 0.002 ms/op
Iteration   3: 3.006 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.962 ±(99.9%) 0.705 ms/op [Average]
  (min, avg, max) = (2.934, 2.962, 3.006), stdev = 0.039
  CI (99.9%): [2.257, 3.667] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 4.374 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.219 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.131 ±(99.9%) 0.003 ms/op
Iteration   1: 3.163 ±(99.9%) 0.003 ms/op
Iteration   2: 3.145 ±(99.9%) 0.003 ms/op
Iteration   3: 3.066 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.124 ±(99.9%) 0.946 ms/op [Average]
  (min, avg, max) = (3.066, 3.124, 3.163), stdev = 0.052
  CI (99.9%): [2.179, 4.070] (assumes normal distribution)


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
# Warmup Iteration   1: 5.292 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 4.093 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 3.940 ±(99.9%) 0.010 ms/op
Iteration   1: 3.951 ±(99.9%) 0.013 ms/op
Iteration   2: 3.854 ±(99.9%) 0.011 ms/op
Iteration   3: 3.581 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.795 ±(99.9%) 3.499 ms/op [Average]
  (min, avg, max) = (3.581, 3.795, 3.951), stdev = 0.192
  CI (99.9%): [0.296, 7.294] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.561 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.310 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.134 ±(99.9%) 0.006 ms/op
Iteration   1: 3.165 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.939 ms/op
                 createUser·p0.50:   3.138 ms/op
                 createUser·p0.90:   3.670 ms/op
                 createUser·p0.95:   3.867 ms/op
                 createUser·p0.99:   4.514 ms/op
                 createUser·p0.999:  7.053 ms/op
                 createUser·p0.9999: 15.083 ms/op
                 createUser·p1.00:   16.761 ms/op

Iteration   2: 3.168 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.775 ms/op
                 createUser·p0.50:   3.129 ms/op
                 createUser·p0.90:   3.731 ms/op
                 createUser·p0.95:   3.858 ms/op
                 createUser·p0.99:   4.440 ms/op
                 createUser·p0.999:  10.863 ms/op
                 createUser·p0.9999: 25.359 ms/op
                 createUser·p1.00:   25.788 ms/op

Iteration   3: 3.166 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.396 ms/op
                 createUser·p0.50:   3.121 ms/op
                 createUser·p0.90:   3.654 ms/op
                 createUser·p0.95:   3.772 ms/op
                 createUser·p0.99:   4.309 ms/op
                 createUser·p0.999:  8.355 ms/op
                 createUser·p0.9999: 23.200 ms/op
                 createUser·p1.00:   23.560 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 303147
  mean =      3.167 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6967 
    [ 2.500,  5.000) = 294369 
    [ 5.000,  7.500) = 1452 
    [ 7.500, 10.000) = 154 
    [10.000, 12.500) = 24 
    [12.500, 15.000) = 42 
    [15.000, 17.500) = 57 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 37 
    [25.000, 27.500) = 23 

  Percentiles, ms/op:
      p(0.0000) =      0.396 ms/op
     p(50.0000) =      3.129 ms/op
     p(90.0000) =      3.686 ms/op
     p(95.0000) =      3.834 ms/op
     p(99.0000) =      4.415 ms/op
     p(99.9000) =      7.798 ms/op
     p(99.9900) =     24.850 ms/op
     p(99.9990) =     25.591 ms/op
     p(99.9999) =     25.788 ms/op
    p(100.0000) =     25.788 ms/op


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
# Warmup Iteration   1: 4.124 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.147 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.000 ±(99.9%) 0.007 ms/op
Iteration   1: 3.007 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.828 ms/op
                 existUser·p0.50:   2.986 ms/op
                 existUser·p0.90:   3.547 ms/op
                 existUser·p0.95:   3.781 ms/op
                 existUser·p0.99:   4.588 ms/op
                 existUser·p0.999:  7.705 ms/op
                 existUser·p0.9999: 27.537 ms/op
                 existUser·p1.00:   28.049 ms/op

Iteration   2: 3.051 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.987 ms/op
                 existUser·p0.50:   2.990 ms/op
                 existUser·p0.90:   3.531 ms/op
                 existUser·p0.95:   3.690 ms/op
                 existUser·p0.99:   4.932 ms/op
                 existUser·p0.999:  9.166 ms/op
                 existUser·p0.9999: 18.024 ms/op
                 existUser·p1.00:   18.448 ms/op

Iteration   3: 3.003 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.720 ms/op
                 existUser·p0.50:   2.970 ms/op
                 existUser·p0.90:   3.416 ms/op
                 existUser·p0.95:   3.690 ms/op
                 existUser·p0.99:   4.522 ms/op
                 existUser·p0.999:  11.576 ms/op
                 existUser·p0.9999: 20.152 ms/op
                 existUser·p1.00:   20.218 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 317744
  mean =      3.020 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21439 
    [ 2.500,  5.000) = 294001 
    [ 5.000,  7.500) = 1782 
    [ 7.500, 10.000) = 234 
    [10.000, 12.500) = 117 
    [12.500, 15.000) = 11 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 78 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 21 

  Percentiles, ms/op:
      p(0.0000) =      0.720 ms/op
     p(50.0000) =      2.982 ms/op
     p(90.0000) =      3.502 ms/op
     p(95.0000) =      3.723 ms/op
     p(99.0000) =      4.645 ms/op
     p(99.9000) =      8.856 ms/op
     p(99.9900) =     26.739 ms/op
     p(99.9990) =     27.907 ms/op
     p(99.9999) =     28.049 ms/op
    p(100.0000) =     28.049 ms/op


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
# Warmup Iteration   1: 4.373 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.325 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.196 ±(99.9%) 0.007 ms/op
Iteration   1: 3.129 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.766 ms/op
                 getUser·p0.50:   3.080 ms/op
                 getUser·p0.90:   3.621 ms/op
                 getUser·p0.95:   3.817 ms/op
                 getUser·p0.99:   4.915 ms/op
                 getUser·p0.999:  8.712 ms/op
                 getUser·p0.9999: 16.650 ms/op
                 getUser·p1.00:   17.531 ms/op

Iteration   2: 3.203 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.777 ms/op
                 getUser·p0.50:   3.138 ms/op
                 getUser·p0.90:   3.777 ms/op
                 getUser·p0.95:   4.002 ms/op
                 getUser·p0.99:   5.351 ms/op
                 getUser·p0.999:  11.135 ms/op
                 getUser·p0.9999: 21.594 ms/op
                 getUser·p1.00:   22.577 ms/op

Iteration   3: 3.064 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.752 ms/op
                 getUser·p0.50:   3.031 ms/op
                 getUser·p0.90:   3.531 ms/op
                 getUser·p0.95:   3.746 ms/op
                 getUser·p0.99:   4.911 ms/op
                 getUser·p0.999:  8.880 ms/op
                 getUser·p0.9999: 21.842 ms/op
                 getUser·p1.00:   23.200 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 306468
  mean =      3.131 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13285 
    [ 2.500,  5.000) = 290013 
    [ 5.000,  7.500) = 2502 
    [ 7.500, 10.000) = 411 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 54 
    [15.000, 17.500) = 55 
    [17.500, 20.000) = 39 
    [20.000, 22.500) = 73 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.752 ms/op
     p(50.0000) =      3.080 ms/op
     p(90.0000) =      3.654 ms/op
     p(95.0000) =      3.883 ms/op
     p(99.0000) =      5.041 ms/op
     p(99.9000) =      9.135 ms/op
     p(99.9900) =     21.540 ms/op
     p(99.9990) =     22.542 ms/op
     p(99.9999) =     23.200 ms/op
    p(100.0000) =     23.200 ms/op


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
# Warmup Iteration   1: 5.712 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 4.200 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.106 ±(99.9%) 0.011 ms/op
Iteration   1: 4.081 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.495 ms/op
                 listUser·p0.50:   3.920 ms/op
                 listUser·p0.90:   5.046 ms/op
                 listUser·p0.95:   5.865 ms/op
                 listUser·p0.99:   7.078 ms/op
                 listUser·p0.999:  13.543 ms/op
                 listUser·p0.9999: 17.574 ms/op
                 listUser·p1.00:   18.383 ms/op

Iteration   2: 4.001 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.090 ms/op
                 listUser·p0.50:   3.879 ms/op
                 listUser·p0.90:   4.686 ms/op
                 listUser·p0.95:   5.546 ms/op
                 listUser·p0.99:   6.914 ms/op
                 listUser·p0.999:  13.812 ms/op
                 listUser·p0.9999: 16.318 ms/op
                 listUser·p1.00:   17.367 ms/op

Iteration   3: 3.999 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.200 ms/op
                 listUser·p0.50:   3.891 ms/op
                 listUser·p0.90:   4.588 ms/op
                 listUser·p0.95:   5.276 ms/op
                 listUser·p0.99:   6.865 ms/op
                 listUser·p0.999:  14.172 ms/op
                 listUser·p0.9999: 18.972 ms/op
                 listUser·p1.00:   19.694 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 238510
  mean =      4.027 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 4 
    [ 1.250,  2.500) = 1541 
    [ 2.500,  3.750) = 84424 
    [ 3.750,  5.000) = 133116 
    [ 5.000,  6.250) = 12493 
    [ 6.250,  7.500) = 5580 
    [ 7.500,  8.750) = 719 
    [ 8.750, 10.000) = 157 
    [10.000, 11.250) = 68 
    [11.250, 12.500) = 37 
    [12.500, 13.750) = 126 
    [13.750, 15.000) = 143 
    [15.000, 16.250) = 64 
    [16.250, 17.500) = 16 
    [17.500, 18.750) = 14 

  Percentiles, ms/op:
      p(0.0000) =      1.090 ms/op
     p(50.0000) =      3.895 ms/op
     p(90.0000) =      4.768 ms/op
     p(95.0000) =      5.587 ms/op
     p(99.0000) =      6.955 ms/op
     p(99.9000) =     13.828 ms/op
     p(99.9900) =     17.367 ms/op
     p(99.9990) =     19.520 ms/op
     p(99.9999) =     19.694 ms/op
    p(100.0000) =     19.694 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.073 ± 3.003  ops/ms
ClientGrpc.existUser                       thrpt       3  10.678 ± 1.958  ops/ms
ClientGrpc.getUser                         thrpt       3  10.161 ± 0.666  ops/ms
ClientGrpc.listUser                        thrpt       3   7.960 ± 1.419  ops/ms
ClientGrpc.createUser                       avgt       3   3.162 ± 0.321   ms/op
ClientGrpc.existUser                        avgt       3   2.962 ± 0.705   ms/op
ClientGrpc.getUser                          avgt       3   3.124 ± 0.946   ms/op
ClientGrpc.listUser                         avgt       3   3.795 ± 3.499   ms/op
ClientGrpc.createUser                     sample  303147   3.167 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.396           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.129           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.686           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.834           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.415           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.798           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          24.850           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          25.788           ms/op
ClientGrpc.existUser                      sample  317744   3.020 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.720           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.982           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.502           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.723           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.645           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.856           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          26.739           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          28.049           ms/op
ClientGrpc.getUser                        sample  306468   3.131 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.752           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.080           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.654           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.883           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.041           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.135           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.540           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.200           ms/op
ClientGrpc.listUser                       sample  238510   4.027 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.090           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.895           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.768           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.587           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.955           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.828           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          17.367           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          19.694           ms/op
