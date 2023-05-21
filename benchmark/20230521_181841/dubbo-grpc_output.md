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
# Warmup Iteration   1: 4.177 ops/ms
# Warmup Iteration   2: 8.890 ops/ms
# Warmup Iteration   3: 10.244 ops/ms
Iteration   1: 10.690 ops/ms
Iteration   2: 10.815 ops/ms
Iteration   3: 10.718 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.741 ±(99.9%) 1.203 ops/ms [Average]
  (min, avg, max) = (10.690, 10.741, 10.815), stdev = 0.066
  CI (99.9%): [9.538, 11.944] (assumes normal distribution)


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
# Warmup Iteration   1: 7.721 ops/ms
# Warmup Iteration   2: 10.850 ops/ms
# Warmup Iteration   3: 11.132 ops/ms
Iteration   1: 11.137 ops/ms
Iteration   2: 11.222 ops/ms
Iteration   3: 11.048 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.136 ±(99.9%) 1.583 ops/ms [Average]
  (min, avg, max) = (11.048, 11.136, 11.222), stdev = 0.087
  CI (99.9%): [9.552, 12.719] (assumes normal distribution)


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
# Warmup Iteration   1: 6.950 ops/ms
# Warmup Iteration   2: 10.095 ops/ms
# Warmup Iteration   3: 10.408 ops/ms
Iteration   1: 10.698 ops/ms
Iteration   2: 10.517 ops/ms
Iteration   3: 10.640 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.619 ±(99.9%) 1.685 ops/ms [Average]
  (min, avg, max) = (10.517, 10.619, 10.698), stdev = 0.092
  CI (99.9%): [8.934, 12.304] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.434 ops/ms
# Warmup Iteration   2: 7.914 ops/ms
# Warmup Iteration   3: 8.190 ops/ms
Iteration   1: 8.271 ops/ms
Iteration   2: 8.026 ops/ms
Iteration   3: 8.074 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.124 ±(99.9%) 2.374 ops/ms [Average]
  (min, avg, max) = (8.026, 8.124, 8.271), stdev = 0.130
  CI (99.9%): [5.749, 10.498] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.621 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.160 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.031 ±(99.9%) 0.003 ms/op
Iteration   1: 3.016 ±(99.9%) 0.002 ms/op
Iteration   2: 3.008 ±(99.9%) 0.002 ms/op
Iteration   3: 2.991 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.005 ±(99.9%) 0.235 ms/op [Average]
  (min, avg, max) = (2.991, 3.005, 3.016), stdev = 0.013
  CI (99.9%): [2.770, 3.240] (assumes normal distribution)


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
# Warmup Iteration   1: 3.718 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.951 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.945 ±(99.9%) 0.002 ms/op
Iteration   1: 2.919 ±(99.9%) 0.003 ms/op
Iteration   2: 2.842 ±(99.9%) 0.001 ms/op
Iteration   3: 2.752 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.838 ±(99.9%) 1.521 ms/op [Average]
  (min, avg, max) = (2.752, 2.838, 2.919), stdev = 0.083
  CI (99.9%): [1.317, 4.359] (assumes normal distribution)


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
# Warmup Iteration   1: 4.260 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.101 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.992 ±(99.9%) 0.002 ms/op
Iteration   1: 2.985 ±(99.9%) 0.004 ms/op
Iteration   2: 3.015 ±(99.9%) 0.002 ms/op
Iteration   3: 2.980 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.993 ±(99.9%) 0.346 ms/op [Average]
  (min, avg, max) = (2.980, 2.993, 3.015), stdev = 0.019
  CI (99.9%): [2.647, 3.340] (assumes normal distribution)


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
# Warmup Iteration   1: 5.381 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.037 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.946 ±(99.9%) 0.014 ms/op
Iteration   1: 3.904 ±(99.9%) 0.007 ms/op
Iteration   2: 3.931 ±(99.9%) 0.037 ms/op
Iteration   3: 3.825 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.887 ±(99.9%) 1.004 ms/op [Average]
  (min, avg, max) = (3.825, 3.887, 3.931), stdev = 0.055
  CI (99.9%): [2.883, 4.891] (assumes normal distribution)


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
# Warmup Iteration   1: 4.406 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.192 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.031 ±(99.9%) 0.006 ms/op
Iteration   1: 2.997 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.603 ms/op
                 createUser·p0.50:   2.982 ms/op
                 createUser·p0.90:   3.494 ms/op
                 createUser·p0.95:   3.641 ms/op
                 createUser·p0.99:   4.108 ms/op
                 createUser·p0.999:  6.554 ms/op
                 createUser·p0.9999: 13.014 ms/op
                 createUser·p1.00:   13.550 ms/op

Iteration   2: 3.022 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.691 ms/op
                 createUser·p0.50:   2.982 ms/op
                 createUser·p0.90:   3.629 ms/op
                 createUser·p0.95:   3.789 ms/op
                 createUser·p0.99:   4.372 ms/op
                 createUser·p0.999:  7.163 ms/op
                 createUser·p0.9999: 23.030 ms/op
                 createUser·p1.00:   23.560 ms/op

Iteration   3: 2.982 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.033 ms/op
                 createUser·p0.50:   2.957 ms/op
                 createUser·p0.90:   3.351 ms/op
                 createUser·p0.95:   3.514 ms/op
                 createUser·p0.99:   3.973 ms/op
                 createUser·p0.999:  7.354 ms/op
                 createUser·p0.9999: 19.211 ms/op
                 createUser·p1.00:   20.382 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 319684
  mean =      3.000 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24351 
    [ 2.500,  5.000) = 294235 
    [ 5.000,  7.500) = 845 
    [ 7.500, 10.000) = 46 
    [10.000, 12.500) = 49 
    [12.500, 15.000) = 63 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 35 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.603 ms/op
     p(50.0000) =      2.974 ms/op
     p(90.0000) =      3.490 ms/op
     p(95.0000) =      3.682 ms/op
     p(99.0000) =      4.149 ms/op
     p(99.9000) =      7.020 ms/op
     p(99.9900) =     21.958 ms/op
     p(99.9990) =     23.488 ms/op
     p(99.9999) =     23.560 ms/op
    p(100.0000) =     23.560 ms/op


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
# Warmup Iteration   1: 4.044 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.966 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.914 ±(99.9%) 0.005 ms/op
Iteration   1: 2.863 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.530 ms/op
                 existUser·p0.50:   2.851 ms/op
                 existUser·p0.90:   3.310 ms/op
                 existUser·p0.95:   3.453 ms/op
                 existUser·p0.99:   4.129 ms/op
                 existUser·p0.999:  6.157 ms/op
                 existUser·p0.9999: 25.521 ms/op
                 existUser·p1.00:   26.345 ms/op

Iteration   2: 2.845 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.725 ms/op
                 existUser·p0.50:   2.851 ms/op
                 existUser·p0.90:   3.387 ms/op
                 existUser·p0.95:   3.547 ms/op
                 existUser·p0.99:   4.076 ms/op
                 existUser·p0.999:  7.392 ms/op
                 existUser·p0.9999: 16.868 ms/op
                 existUser·p1.00:   17.531 ms/op

Iteration   3: 2.860 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.725 ms/op
                 existUser·p0.50:   2.863 ms/op
                 existUser·p0.90:   3.305 ms/op
                 existUser·p0.95:   3.506 ms/op
                 existUser·p0.99:   4.219 ms/op
                 existUser·p0.999:  5.880 ms/op
                 existUser·p0.9999: 19.431 ms/op
                 existUser·p1.00:   19.857 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 335899
  mean =      2.856 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 51054 
    [ 2.500,  5.000) = 283961 
    [ 5.000,  7.500) = 650 
    [ 7.500, 10.000) = 32 
    [10.000, 12.500) = 42 
    [12.500, 15.000) = 10 
    [15.000, 17.500) = 85 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 24 

  Percentiles, ms/op:
      p(0.0000) =      0.530 ms/op
     p(50.0000) =      2.855 ms/op
     p(90.0000) =      3.330 ms/op
     p(95.0000) =      3.510 ms/op
     p(99.0000) =      4.133 ms/op
     p(99.9000) =      6.554 ms/op
     p(99.9900) =     19.838 ms/op
     p(99.9990) =     26.115 ms/op
     p(99.9999) =     26.345 ms/op
    p(100.0000) =     26.345 ms/op


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
# Warmup Iteration   1: 4.097 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.133 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.066 ±(99.9%) 0.007 ms/op
Iteration   1: 2.995 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.841 ms/op
                 getUser·p0.50:   2.957 ms/op
                 getUser·p0.90:   3.555 ms/op
                 getUser·p0.95:   3.809 ms/op
                 getUser·p0.99:   4.497 ms/op
                 getUser·p0.999:  10.604 ms/op
                 getUser·p0.9999: 18.842 ms/op
                 getUser·p1.00:   19.071 ms/op

Iteration   2: 3.014 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.718 ms/op
                 getUser·p0.50:   2.982 ms/op
                 getUser·p0.90:   3.564 ms/op
                 getUser·p0.95:   3.764 ms/op
                 getUser·p0.99:   4.538 ms/op
                 getUser·p0.999:  6.037 ms/op
                 getUser·p0.9999: 15.129 ms/op
                 getUser·p1.00:   15.204 ms/op

Iteration   3: 2.972 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.693 ms/op
                 getUser·p0.50:   2.949 ms/op
                 getUser·p0.90:   3.420 ms/op
                 getUser·p0.95:   3.654 ms/op
                 getUser·p0.99:   4.350 ms/op
                 getUser·p0.999:  5.847 ms/op
                 getUser·p0.9999: 14.892 ms/op
                 getUser·p1.00:   16.138 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 320473
  mean =      2.994 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 575 
    [ 1.250,  2.500) = 27950 
    [ 2.500,  3.750) = 275804 
    [ 3.750,  5.000) = 14774 
    [ 5.000,  6.250) = 960 
    [ 6.250,  7.500) = 165 
    [ 7.500,  8.750) = 21 
    [ 8.750, 10.000) = 6 
    [10.000, 11.250) = 26 
    [11.250, 12.500) = 29 
    [12.500, 13.750) = 20 
    [13.750, 15.000) = 57 
    [15.000, 16.250) = 53 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 19 

  Percentiles, ms/op:
      p(0.0000) =      0.693 ms/op
     p(50.0000) =      2.961 ms/op
     p(90.0000) =      3.518 ms/op
     p(95.0000) =      3.752 ms/op
     p(99.0000) =      4.473 ms/op
     p(99.9000) =      6.623 ms/op
     p(99.9900) =     17.876 ms/op
     p(99.9990) =     19.031 ms/op
     p(99.9999) =     19.071 ms/op
    p(100.0000) =     19.071 ms/op


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
# Warmup Iteration   1: 5.502 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 4.019 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.969 ±(99.9%) 0.012 ms/op
Iteration   1: 3.943 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.178 ms/op
                 listUser·p0.50:   3.768 ms/op
                 listUser·p0.90:   4.989 ms/op
                 listUser·p0.95:   5.652 ms/op
                 listUser·p0.99:   6.873 ms/op
                 listUser·p0.999:  13.450 ms/op
                 listUser·p0.9999: 14.990 ms/op
                 listUser·p1.00:   15.319 ms/op

Iteration   2: 3.931 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.376 ms/op
                 listUser·p0.50:   3.777 ms/op
                 listUser·p0.90:   4.719 ms/op
                 listUser·p0.95:   5.538 ms/op
                 listUser·p0.99:   6.832 ms/op
                 listUser·p0.999:  15.477 ms/op
                 listUser·p0.9999: 23.429 ms/op
                 listUser·p1.00:   24.281 ms/op

Iteration   3: 3.909 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.031 ms/op
                 listUser·p0.50:   3.719 ms/op
                 listUser·p0.90:   5.079 ms/op
                 listUser·p0.95:   5.710 ms/op
                 listUser·p0.99:   7.086 ms/op
                 listUser·p0.999:  15.286 ms/op
                 listUser·p0.9999: 20.069 ms/op
                 listUser·p1.00:   21.463 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 244234
  mean =      3.928 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2452 
    [ 2.500,  5.000) = 218672 
    [ 5.000,  7.500) = 21742 
    [ 7.500, 10.000) = 860 
    [10.000, 12.500) = 109 
    [12.500, 15.000) = 185 
    [15.000, 17.500) = 134 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.031 ms/op
     p(50.0000) =      3.756 ms/op
     p(90.0000) =      4.948 ms/op
     p(95.0000) =      5.644 ms/op
     p(99.0000) =      6.939 ms/op
     p(99.9000) =     14.820 ms/op
     p(99.9900) =     22.694 ms/op
     p(99.9990) =     24.139 ms/op
     p(99.9999) =     24.281 ms/op
    p(100.0000) =     24.281 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.741 ± 1.203  ops/ms
ClientGrpc.existUser                       thrpt       3  11.136 ± 1.583  ops/ms
ClientGrpc.getUser                         thrpt       3  10.619 ± 1.685  ops/ms
ClientGrpc.listUser                        thrpt       3   8.124 ± 2.374  ops/ms
ClientGrpc.createUser                       avgt       3   3.005 ± 0.235   ms/op
ClientGrpc.existUser                        avgt       3   2.838 ± 1.521   ms/op
ClientGrpc.getUser                          avgt       3   2.993 ± 0.346   ms/op
ClientGrpc.listUser                         avgt       3   3.887 ± 1.004   ms/op
ClientGrpc.createUser                     sample  319684   3.000 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.603           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.974           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.490           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.682           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.149           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.020           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.958           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.560           ms/op
ClientGrpc.existUser                      sample  335899   2.856 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.530           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.855           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.330           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.510           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.133           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.554           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.838           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          26.345           ms/op
ClientGrpc.getUser                        sample  320473   2.994 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.693           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.961           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.518           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.752           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.473           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.623           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.876           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.071           ms/op
ClientGrpc.listUser                       sample  244234   3.928 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.031           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.756           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.948           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.644           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.939           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.820           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.694           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.281           ms/op
