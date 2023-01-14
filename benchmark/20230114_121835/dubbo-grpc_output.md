# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 5.220 ops/ms
# Warmup Iteration   2: 9.610 ops/ms
# Warmup Iteration   3: 10.560 ops/ms
Iteration   1: 10.353 ops/ms
Iteration   2: 10.411 ops/ms
Iteration   3: 10.132 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.299 ±(99.9%) 2.688 ops/ms [Average]
  (min, avg, max) = (10.132, 10.299, 10.411), stdev = 0.147
  CI (99.9%): [7.611, 12.987] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 8.061 ops/ms
# Warmup Iteration   2: 10.618 ops/ms
# Warmup Iteration   3: 10.600 ops/ms
Iteration   1: 10.642 ops/ms
Iteration   2: 10.983 ops/ms
Iteration   3: 10.958 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.861 ±(99.9%) 3.469 ops/ms [Average]
  (min, avg, max) = (10.642, 10.861, 10.983), stdev = 0.190
  CI (99.9%): [7.392, 14.330] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.607 ops/ms
# Warmup Iteration   2: 10.524 ops/ms
# Warmup Iteration   3: 10.559 ops/ms
Iteration   1: 10.409 ops/ms
Iteration   2: 10.317 ops/ms
Iteration   3: 10.282 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.336 ±(99.9%) 1.196 ops/ms [Average]
  (min, avg, max) = (10.282, 10.336, 10.409), stdev = 0.066
  CI (99.9%): [9.140, 11.533] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.960 ops/ms
# Warmup Iteration   2: 7.724 ops/ms
# Warmup Iteration   3: 7.691 ops/ms
Iteration   1: 7.840 ops/ms
Iteration   2: 7.800 ops/ms
Iteration   3: 7.741 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.794 ±(99.9%) 0.902 ops/ms [Average]
  (min, avg, max) = (7.741, 7.794, 7.840), stdev = 0.049
  CI (99.9%): [6.892, 8.695] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.151 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.073 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.027 ±(99.9%) 0.003 ms/op
Iteration   1: 3.189 ±(99.9%) 0.003 ms/op
Iteration   2: 3.202 ±(99.9%) 0.002 ms/op
Iteration   3: 3.213 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.201 ±(99.9%) 0.221 ms/op [Average]
  (min, avg, max) = (3.189, 3.201, 3.213), stdev = 0.012
  CI (99.9%): [2.980, 3.423] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.828 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.944 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.880 ±(99.9%) 0.003 ms/op
Iteration   1: 2.885 ±(99.9%) 0.003 ms/op
Iteration   2: 2.972 ±(99.9%) 0.004 ms/op
Iteration   3: 2.998 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.952 ±(99.9%) 1.082 ms/op [Average]
  (min, avg, max) = (2.885, 2.952, 2.998), stdev = 0.059
  CI (99.9%): [1.869, 4.034] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.909 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.096 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.144 ±(99.9%) 0.004 ms/op
Iteration   1: 3.107 ±(99.9%) 0.002 ms/op
Iteration   2: 3.134 ±(99.9%) 0.002 ms/op
Iteration   3: 3.078 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.106 ±(99.9%) 0.515 ms/op [Average]
  (min, avg, max) = (3.078, 3.106, 3.134), stdev = 0.028
  CI (99.9%): [2.592, 3.621] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 5.318 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 4.145 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 4.076 ±(99.9%) 0.014 ms/op
Iteration   1: 4.018 ±(99.9%) 0.005 ms/op
Iteration   2: 4.016 ±(99.9%) 0.010 ms/op
Iteration   3: 4.015 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.016 ±(99.9%) 0.024 ms/op [Average]
  (min, avg, max) = (4.015, 4.016, 4.018), stdev = 0.001
  CI (99.9%): [3.992, 4.041] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.936 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.231 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.039 ±(99.9%) 0.006 ms/op
Iteration   1: 3.136 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.764 ms/op
                 createUser·p0.50:   3.125 ms/op
                 createUser·p0.90:   3.719 ms/op
                 createUser·p0.95:   3.891 ms/op
                 createUser·p0.99:   4.318 ms/op
                 createUser·p0.999:  7.799 ms/op
                 createUser·p0.9999: 11.937 ms/op
                 createUser·p1.00:   12.157 ms/op

Iteration   2: 3.079 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.590 ms/op
                 createUser·p0.50:   3.092 ms/op
                 createUser·p0.90:   3.666 ms/op
                 createUser·p0.95:   3.858 ms/op
                 createUser·p0.99:   4.211 ms/op
                 createUser·p0.999:  6.672 ms/op
                 createUser·p0.9999: 13.879 ms/op
                 createUser·p1.00:   15.565 ms/op

Iteration   3: 3.157 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.702 ms/op
                 createUser·p0.50:   3.142 ms/op
                 createUser·p0.90:   3.842 ms/op
                 createUser·p0.95:   4.026 ms/op
                 createUser·p0.99:   4.375 ms/op
                 createUser·p0.999:  6.922 ms/op
                 createUser·p0.9999: 16.382 ms/op
                 createUser·p1.00:   17.039 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 307337
  mean =      3.124 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1128 
    [ 1.250,  2.500) = 20927 
    [ 2.500,  3.750) = 254676 
    [ 3.750,  5.000) = 29656 
    [ 5.000,  6.250) = 481 
    [ 6.250,  7.500) = 210 
    [ 7.500,  8.750) = 66 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 18 
    [11.250, 12.500) = 63 
    [12.500, 13.750) = 68 
    [13.750, 15.000) = 9 
    [15.000, 16.250) = 22 
    [16.250, 17.500) = 12 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.590 ms/op
     p(50.0000) =      3.117 ms/op
     p(90.0000) =      3.748 ms/op
     p(95.0000) =      3.932 ms/op
     p(99.0000) =      4.325 ms/op
     p(99.9000) =      7.127 ms/op
     p(99.9900) =     15.655 ms/op
     p(99.9990) =     16.690 ms/op
     p(99.9999) =     17.039 ms/op
    p(100.0000) =     17.039 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.911 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.007 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.024 ±(99.9%) 0.006 ms/op
Iteration   1: 3.016 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.688 ms/op
                 existUser·p0.50:   3.015 ms/op
                 existUser·p0.90:   3.629 ms/op
                 existUser·p0.95:   3.805 ms/op
                 existUser·p0.99:   4.133 ms/op
                 existUser·p0.999:  5.038 ms/op
                 existUser·p0.9999: 12.144 ms/op
                 existUser·p1.00:   12.452 ms/op

Iteration   2: 2.957 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.720 ms/op
                 existUser·p0.50:   2.949 ms/op
                 existUser·p0.90:   3.592 ms/op
                 existUser·p0.95:   3.760 ms/op
                 existUser·p0.99:   4.141 ms/op
                 existUser·p0.999:  6.560 ms/op
                 existUser·p0.9999: 12.346 ms/op
                 existUser·p1.00:   12.747 ms/op

Iteration   3: 3.022 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.579 ms/op
                 existUser·p0.50:   3.011 ms/op
                 existUser·p0.90:   3.690 ms/op
                 existUser·p0.95:   3.875 ms/op
                 existUser·p0.99:   4.153 ms/op
                 existUser·p0.999:  11.421 ms/op
                 existUser·p0.9999: 16.076 ms/op
                 existUser·p1.00:   16.548 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 320255
  mean =      2.998 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2408 
    [ 1.250,  2.500) = 36265 
    [ 2.500,  3.750) = 260231 
    [ 3.750,  5.000) = 20656 
    [ 5.000,  6.250) = 280 
    [ 6.250,  7.500) = 147 
    [ 7.500,  8.750) = 43 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 65 
    [11.250, 12.500) = 68 
    [12.500, 13.750) = 28 
    [13.750, 15.000) = 34 
    [15.000, 16.250) = 22 
    [16.250, 17.500) = 7 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.579 ms/op
     p(50.0000) =      2.990 ms/op
     p(90.0000) =      3.637 ms/op
     p(95.0000) =      3.817 ms/op
     p(99.0000) =      4.145 ms/op
     p(99.9000) =      6.945 ms/op
     p(99.9900) =     14.679 ms/op
     p(99.9990) =     16.440 ms/op
     p(99.9999) =     16.548 ms/op
    p(100.0000) =     16.548 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.989 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.110 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.022 ±(99.9%) 0.006 ms/op
Iteration   1: 3.070 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.732 ms/op
                 getUser·p0.50:   3.068 ms/op
                 getUser·p0.90:   3.654 ms/op
                 getUser·p0.95:   3.871 ms/op
                 getUser·p0.99:   4.268 ms/op
                 getUser·p0.999:  6.147 ms/op
                 getUser·p0.9999: 14.451 ms/op
                 getUser·p1.00:   14.795 ms/op

Iteration   2: 2.997 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.529 ms/op
                 getUser·p0.50:   3.019 ms/op
                 getUser·p0.90:   3.437 ms/op
                 getUser·p0.95:   3.592 ms/op
                 getUser·p0.99:   4.252 ms/op
                 getUser·p0.999:  6.865 ms/op
                 getUser·p0.9999: 26.061 ms/op
                 getUser·p1.00:   26.378 ms/op

Iteration   3: 3.148 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.679 ms/op
                 getUser·p0.50:   3.125 ms/op
                 getUser·p0.90:   3.813 ms/op
                 getUser·p0.95:   3.981 ms/op
                 getUser·p0.99:   4.235 ms/op
                 getUser·p0.999:  7.641 ms/op
                 getUser·p0.9999: 19.525 ms/op
                 getUser·p1.00:   19.857 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 312531
  mean =      3.070 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22872 
    [ 2.500,  5.000) = 288697 
    [ 5.000,  7.500) = 707 
    [ 7.500, 10.000) = 63 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 76 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.529 ms/op
     p(50.0000) =      3.064 ms/op
     p(90.0000) =      3.658 ms/op
     p(95.0000) =      3.868 ms/op
     p(99.0000) =      4.252 ms/op
     p(99.9000) =      6.774 ms/op
     p(99.9900) =     25.452 ms/op
     p(99.9990) =     26.313 ms/op
     p(99.9999) =     26.378 ms/op
    p(100.0000) =     26.378 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.143 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 4.232 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.053 ±(99.9%) 0.011 ms/op
Iteration   1: 4.061 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.049 ms/op
                 listUser·p0.50:   3.895 ms/op
                 listUser·p0.90:   5.210 ms/op
                 listUser·p0.95:   5.743 ms/op
                 listUser·p0.99:   7.045 ms/op
                 listUser·p0.999:  14.248 ms/op
                 listUser·p0.9999: 19.071 ms/op
                 listUser·p1.00:   20.021 ms/op

Iteration   2: 3.944 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.130 ms/op
                 listUser·p0.50:   3.830 ms/op
                 listUser·p0.90:   4.801 ms/op
                 listUser·p0.95:   5.669 ms/op
                 listUser·p0.99:   6.636 ms/op
                 listUser·p0.999:  15.514 ms/op
                 listUser·p0.9999: 19.195 ms/op
                 listUser·p1.00:   19.530 ms/op

Iteration   3: 4.009 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.872 ms/op
                 listUser·p0.50:   3.871 ms/op
                 listUser·p0.90:   5.005 ms/op
                 listUser·p0.95:   5.620 ms/op
                 listUser·p0.99:   6.832 ms/op
                 listUser·p0.999:  16.245 ms/op
                 listUser·p0.9999: 21.988 ms/op
                 listUser·p1.00:   22.381 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 239727
  mean =      4.004 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5099 
    [ 2.500,  5.000) = 208890 
    [ 5.000,  7.500) = 24576 
    [ 7.500, 10.000) = 734 
    [10.000, 12.500) = 65 
    [12.500, 15.000) = 76 
    [15.000, 17.500) = 151 
    [17.500, 20.000) = 91 
    [20.000, 22.500) = 45 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.872 ms/op
     p(50.0000) =      3.863 ms/op
     p(90.0000) =      5.063 ms/op
     p(95.0000) =      5.677 ms/op
     p(99.0000) =      6.824 ms/op
     p(99.9000) =     15.700 ms/op
     p(99.9900) =     21.398 ms/op
     p(99.9990) =     22.250 ms/op
     p(99.9999) =     22.381 ms/op
    p(100.0000) =     22.381 ms/op


# Run complete. Total time: 00:13:02

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.299 ± 2.688  ops/ms
ClientGrpc.existUser                       thrpt       3  10.861 ± 3.469  ops/ms
ClientGrpc.getUser                         thrpt       3  10.336 ± 1.196  ops/ms
ClientGrpc.listUser                        thrpt       3   7.794 ± 0.902  ops/ms
ClientGrpc.createUser                       avgt       3   3.201 ± 0.221   ms/op
ClientGrpc.existUser                        avgt       3   2.952 ± 1.082   ms/op
ClientGrpc.getUser                          avgt       3   3.106 ± 0.515   ms/op
ClientGrpc.listUser                         avgt       3   4.016 ± 0.024   ms/op
ClientGrpc.createUser                     sample  307337   3.124 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.590           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.117           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.748           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.932           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.325           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.127           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          15.655           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          17.039           ms/op
ClientGrpc.existUser                      sample  320255   2.998 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.579           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.990           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.637           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.817           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.145           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.945           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.679           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          16.548           ms/op
ClientGrpc.getUser                        sample  312531   3.070 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.529           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.064           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.658           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.868           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.252           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.774           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          25.452           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          26.378           ms/op
ClientGrpc.listUser                       sample  239727   4.004 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.872           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.863           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.063           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.677           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.824           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.700           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.398           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          22.381           ms/op
