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
# Warmup Iteration   1: 5.028 ops/ms
# Warmup Iteration   2: 9.550 ops/ms
# Warmup Iteration   3: 10.248 ops/ms
Iteration   1: 10.092 ops/ms
Iteration   2: 10.508 ops/ms
Iteration   3: 10.339 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.313 ±(99.9%) 3.810 ops/ms [Average]
  (min, avg, max) = (10.092, 10.313, 10.508), stdev = 0.209
  CI (99.9%): [6.503, 14.123] (assumes normal distribution)


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
# Warmup Iteration   1: 8.154 ops/ms
# Warmup Iteration   2: 10.882 ops/ms
# Warmup Iteration   3: 10.752 ops/ms
Iteration   1: 10.932 ops/ms
Iteration   2: 10.826 ops/ms
Iteration   3: 10.936 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.898 ±(99.9%) 1.141 ops/ms [Average]
  (min, avg, max) = (10.826, 10.898, 10.936), stdev = 0.063
  CI (99.9%): [9.756, 12.039] (assumes normal distribution)


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
# Warmup Iteration   1: 7.974 ops/ms
# Warmup Iteration   2: 10.405 ops/ms
# Warmup Iteration   3: 10.677 ops/ms
Iteration   1: 10.704 ops/ms
Iteration   2: 10.686 ops/ms
Iteration   3: 10.624 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.671 ±(99.9%) 0.769 ops/ms [Average]
  (min, avg, max) = (10.624, 10.671, 10.704), stdev = 0.042
  CI (99.9%): [9.902, 11.441] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.205 ops/ms
# Warmup Iteration   2: 7.684 ops/ms
# Warmup Iteration   3: 7.948 ops/ms
Iteration   1: 7.924 ops/ms
Iteration   2: 8.130 ops/ms
Iteration   3: 8.013 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.023 ±(99.9%) 1.887 ops/ms [Average]
  (min, avg, max) = (7.924, 8.023, 8.130), stdev = 0.103
  CI (99.9%): [6.135, 9.910] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.003 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.105 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.189 ±(99.9%) 0.001 ms/op
Iteration   1: 3.078 ±(99.9%) 0.003 ms/op
Iteration   2: 3.107 ±(99.9%) 0.003 ms/op
Iteration   3: 3.174 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.120 ±(99.9%) 0.901 ms/op [Average]
  (min, avg, max) = (3.078, 3.120, 3.174), stdev = 0.049
  CI (99.9%): [2.219, 4.021] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.696 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.954 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.952 ±(99.9%) 0.002 ms/op
Iteration   1: 2.984 ±(99.9%) 0.002 ms/op
Iteration   2: 2.948 ±(99.9%) 0.002 ms/op
Iteration   3: 2.944 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.959 ±(99.9%) 0.402 ms/op [Average]
  (min, avg, max) = (2.944, 2.959, 2.984), stdev = 0.022
  CI (99.9%): [2.557, 3.361] (assumes normal distribution)


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
# Warmup Iteration   1: 4.053 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.150 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.055 ±(99.9%) 0.002 ms/op
Iteration   1: 3.132 ±(99.9%) 0.003 ms/op
Iteration   2: 2.949 ±(99.9%) 0.003 ms/op
Iteration   3: 3.115 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.065 ±(99.9%) 1.849 ms/op [Average]
  (min, avg, max) = (2.949, 3.065, 3.132), stdev = 0.101
  CI (99.9%): [1.216, 4.914] (assumes normal distribution)


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
# Warmup Iteration   1: 4.988 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 4.072 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 4.138 ±(99.9%) 0.038 ms/op
Iteration   1: 3.908 ±(99.9%) 0.016 ms/op
Iteration   2: 3.963 ±(99.9%) 0.027 ms/op
Iteration   3: 3.900 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.924 ±(99.9%) 0.629 ms/op [Average]
  (min, avg, max) = (3.900, 3.924, 3.963), stdev = 0.034
  CI (99.9%): [3.295, 4.553] (assumes normal distribution)


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
# Warmup Iteration   1: 3.999 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.081 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.011 ±(99.9%) 0.006 ms/op
Iteration   1: 3.086 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.749 ms/op
                 createUser·p0.50:   3.060 ms/op
                 createUser·p0.90:   3.731 ms/op
                 createUser·p0.95:   3.895 ms/op
                 createUser·p0.99:   4.202 ms/op
                 createUser·p0.999:  6.027 ms/op
                 createUser·p0.9999: 11.698 ms/op
                 createUser·p1.00:   11.993 ms/op

Iteration   2: 3.083 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.616 ms/op
                 createUser·p0.50:   3.068 ms/op
                 createUser·p0.90:   3.756 ms/op
                 createUser·p0.95:   3.932 ms/op
                 createUser·p0.99:   4.202 ms/op
                 createUser·p0.999:  11.911 ms/op
                 createUser·p0.9999: 14.694 ms/op
                 createUser·p1.00:   15.155 ms/op

Iteration   3: 3.136 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.809 ms/op
                 createUser·p0.50:   3.097 ms/op
                 createUser·p0.90:   3.842 ms/op
                 createUser·p0.95:   4.026 ms/op
                 createUser·p0.99:   4.284 ms/op
                 createUser·p0.999:  6.659 ms/op
                 createUser·p0.9999: 19.530 ms/op
                 createUser·p1.00:   19.988 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 309587
  mean =      3.101 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 855 
    [ 1.250,  2.500) = 27392 
    [ 2.500,  3.750) = 247885 
    [ 3.750,  5.000) = 32740 
    [ 5.000,  6.250) = 293 
    [ 6.250,  7.500) = 130 
    [ 7.500,  8.750) = 36 
    [ 8.750, 10.000) = 27 
    [10.000, 11.250) = 22 
    [11.250, 12.500) = 108 
    [12.500, 13.750) = 37 
    [13.750, 15.000) = 27 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.616 ms/op
     p(50.0000) =      3.076 ms/op
     p(90.0000) =      3.777 ms/op
     p(95.0000) =      3.957 ms/op
     p(99.0000) =      4.235 ms/op
     p(99.9000) =      7.102 ms/op
     p(99.9900) =     18.713 ms/op
     p(99.9990) =     19.857 ms/op
     p(99.9999) =     19.988 ms/op
    p(100.0000) =     19.988 ms/op


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
# Warmup Iteration   1: 3.836 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 2.952 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.880 ±(99.9%) 0.007 ms/op
Iteration   1: 2.865 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.660 ms/op
                 existUser·p0.50:   2.929 ms/op
                 existUser·p0.90:   3.641 ms/op
                 existUser·p0.95:   3.830 ms/op
                 existUser·p0.99:   4.227 ms/op
                 existUser·p0.999:  5.784 ms/op
                 existUser·p0.9999: 11.886 ms/op
                 existUser·p1.00:   12.386 ms/op

Iteration   2: 2.988 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.675 ms/op
                 existUser·p0.50:   2.982 ms/op
                 existUser·p0.90:   3.666 ms/op
                 existUser·p0.95:   3.846 ms/op
                 existUser·p0.99:   4.174 ms/op
                 existUser·p0.999:  5.184 ms/op
                 existUser·p0.9999: 14.362 ms/op
                 existUser·p1.00:   16.744 ms/op

Iteration   3: 2.922 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.498 ms/op
                 existUser·p0.50:   2.908 ms/op
                 existUser·p0.90:   3.502 ms/op
                 existUser·p0.95:   3.727 ms/op
                 existUser·p0.99:   4.276 ms/op
                 existUser·p0.999:  6.692 ms/op
                 existUser·p0.9999: 26.412 ms/op
                 existUser·p1.00:   27.197 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 328551
  mean =      2.924 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 56573 
    [ 2.500,  5.000) = 271268 
    [ 5.000,  7.500) = 549 
    [ 7.500, 10.000) = 1 
    [10.000, 12.500) = 64 
    [12.500, 15.000) = 25 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 33 

  Percentiles, ms/op:
      p(0.0000) =      0.498 ms/op
     p(50.0000) =      2.941 ms/op
     p(90.0000) =      3.613 ms/op
     p(95.0000) =      3.813 ms/op
     p(99.0000) =      4.227 ms/op
     p(99.9000) =      6.000 ms/op
     p(99.9900) =     25.386 ms/op
     p(99.9990) =     26.598 ms/op
     p(99.9999) =     27.197 ms/op
    p(100.0000) =     27.197 ms/op


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
# Warmup Iteration   1: 4.079 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.102 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.026 ±(99.9%) 0.006 ms/op
Iteration   1: 3.033 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.607 ms/op
                 getUser·p0.50:   3.019 ms/op
                 getUser·p0.90:   3.502 ms/op
                 getUser·p0.95:   3.719 ms/op
                 getUser·p0.99:   4.260 ms/op
                 getUser·p0.999:  8.385 ms/op
                 getUser·p0.9999: 18.856 ms/op
                 getUser·p1.00:   19.300 ms/op

Iteration   2: 3.043 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.768 ms/op
                 getUser·p0.50:   3.056 ms/op
                 getUser·p0.90:   3.690 ms/op
                 getUser·p0.95:   3.867 ms/op
                 getUser·p0.99:   4.219 ms/op
                 getUser·p0.999:  6.750 ms/op
                 getUser·p0.9999: 14.811 ms/op
                 getUser·p1.00:   15.188 ms/op

Iteration   3: 3.073 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.558 ms/op
                 getUser·p0.50:   3.060 ms/op
                 getUser·p0.90:   3.666 ms/op
                 getUser·p0.95:   3.875 ms/op
                 getUser·p0.99:   4.276 ms/op
                 getUser·p0.999:  7.233 ms/op
                 getUser·p0.9999: 15.316 ms/op
                 getUser·p1.00:   16.613 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 314719
  mean =      3.050 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1701 
    [ 1.250,  2.500) = 24446 
    [ 2.500,  3.750) = 267484 
    [ 3.750,  5.000) = 20160 
    [ 5.000,  6.250) = 383 
    [ 6.250,  7.500) = 239 
    [ 7.500,  8.750) = 89 
    [ 8.750, 10.000) = 23 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 34 
    [12.500, 13.750) = 31 
    [13.750, 15.000) = 41 
    [15.000, 16.250) = 16 
    [16.250, 17.500) = 8 
    [17.500, 18.750) = 18 

  Percentiles, ms/op:
      p(0.0000) =      0.558 ms/op
     p(50.0000) =      3.043 ms/op
     p(90.0000) =      3.633 ms/op
     p(95.0000) =      3.834 ms/op
     p(99.0000) =      4.252 ms/op
     p(99.9000) =      7.408 ms/op
     p(99.9900) =     18.254 ms/op
     p(99.9990) =     19.160 ms/op
     p(99.9999) =     19.300 ms/op
    p(100.0000) =     19.300 ms/op


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
# Warmup Iteration   1: 5.584 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.127 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.100 ±(99.9%) 0.011 ms/op
Iteration   1: 4.017 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.023 ms/op
                 listUser·p0.50:   3.817 ms/op
                 listUser·p0.90:   5.202 ms/op
                 listUser·p0.95:   5.702 ms/op
                 listUser·p0.99:   6.930 ms/op
                 listUser·p0.999:  11.782 ms/op
                 listUser·p0.9999: 13.551 ms/op
                 listUser·p1.00:   13.877 ms/op

Iteration   2: 4.071 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.010 ms/op
                 listUser·p0.50:   3.867 ms/op
                 listUser·p0.90:   5.259 ms/op
                 listUser·p0.95:   5.661 ms/op
                 listUser·p0.99:   6.963 ms/op
                 listUser·p0.999:  13.669 ms/op
                 listUser·p0.9999: 16.064 ms/op
                 listUser·p1.00:   16.499 ms/op

Iteration   3: 3.864 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.114 ms/op
                 listUser·p0.50:   3.756 ms/op
                 listUser·p0.90:   4.506 ms/op
                 listUser·p0.95:   5.325 ms/op
                 listUser·p0.99:   6.603 ms/op
                 listUser·p0.999:  15.179 ms/op
                 listUser·p0.9999: 22.315 ms/op
                 listUser·p1.00:   24.117 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 241163
  mean =      3.982 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2513 
    [ 2.500,  5.000) = 211241 
    [ 5.000,  7.500) = 26294 
    [ 7.500, 10.000) = 728 
    [10.000, 12.500) = 107 
    [12.500, 15.000) = 158 
    [15.000, 17.500) = 58 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 40 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.010 ms/op
     p(50.0000) =      3.809 ms/op
     p(90.0000) =      5.095 ms/op
     p(95.0000) =      5.612 ms/op
     p(99.0000) =      6.832 ms/op
     p(99.9000) =     13.124 ms/op
     p(99.9900) =     21.750 ms/op
     p(99.9990) =     23.439 ms/op
     p(99.9999) =     24.117 ms/op
    p(100.0000) =     24.117 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.313 ± 3.810  ops/ms
ClientGrpc.existUser                       thrpt       3  10.898 ± 1.141  ops/ms
ClientGrpc.getUser                         thrpt       3  10.671 ± 0.769  ops/ms
ClientGrpc.listUser                        thrpt       3   8.023 ± 1.887  ops/ms
ClientGrpc.createUser                       avgt       3   3.120 ± 0.901   ms/op
ClientGrpc.existUser                        avgt       3   2.959 ± 0.402   ms/op
ClientGrpc.getUser                          avgt       3   3.065 ± 1.849   ms/op
ClientGrpc.listUser                         avgt       3   3.924 ± 0.629   ms/op
ClientGrpc.createUser                     sample  309587   3.101 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.616           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.076           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.777           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.957           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.235           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.102           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.713           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          19.988           ms/op
ClientGrpc.existUser                      sample  328551   2.924 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.498           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.941           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.613           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.813           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.227           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.000           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          25.386           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          27.197           ms/op
ClientGrpc.getUser                        sample  314719   3.050 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.558           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.043           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.633           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.834           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.252           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.408           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.254           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.300           ms/op
ClientGrpc.listUser                       sample  241163   3.982 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.010           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.809           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.095           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.612           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.832           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.124           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.750           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.117           ms/op
