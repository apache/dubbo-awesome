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
# Warmup Iteration   1: 4.973 ops/ms
# Warmup Iteration   2: 9.567 ops/ms
# Warmup Iteration   3: 10.561 ops/ms
Iteration   1: 10.862 ops/ms
Iteration   2: 10.875 ops/ms
Iteration   3: 10.928 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.888 ±(99.9%) 0.642 ops/ms [Average]
  (min, avg, max) = (10.862, 10.888, 10.928), stdev = 0.035
  CI (99.9%): [10.247, 11.530] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 8.076 ops/ms
# Warmup Iteration   2: 10.985 ops/ms
# Warmup Iteration   3: 11.387 ops/ms
Iteration   1: 11.555 ops/ms
Iteration   2: 11.331 ops/ms
Iteration   3: 11.458 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.448 ±(99.9%) 2.052 ops/ms [Average]
  (min, avg, max) = (11.331, 11.448, 11.555), stdev = 0.112
  CI (99.9%): [9.396, 13.500] (assumes normal distribution)


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
# Warmup Iteration   1: 7.937 ops/ms
# Warmup Iteration   2: 10.670 ops/ms
# Warmup Iteration   3: 10.486 ops/ms
Iteration   1: 10.927 ops/ms
Iteration   2: 10.911 ops/ms
Iteration   3: 11.080 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.973 ±(99.9%) 1.702 ops/ms [Average]
  (min, avg, max) = (10.911, 10.973, 11.080), stdev = 0.093
  CI (99.9%): [9.271, 12.675] (assumes normal distribution)


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
# Warmup Iteration   1: 6.120 ops/ms
# Warmup Iteration   2: 8.345 ops/ms
# Warmup Iteration   3: 8.474 ops/ms
Iteration   1: 8.510 ops/ms
Iteration   2: 8.447 ops/ms
Iteration   3: 8.817 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.592 ±(99.9%) 3.611 ops/ms [Average]
  (min, avg, max) = (8.447, 8.592, 8.817), stdev = 0.198
  CI (99.9%): [4.981, 12.202] (assumes normal distribution)


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
# Warmup Iteration   1: 4.002 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.009 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.004 ±(99.9%) 0.004 ms/op
Iteration   1: 2.926 ±(99.9%) 0.003 ms/op
Iteration   2: 2.943 ±(99.9%) 0.002 ms/op
Iteration   3: 2.882 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.917 ±(99.9%) 0.571 ms/op [Average]
  (min, avg, max) = (2.882, 2.917, 2.943), stdev = 0.031
  CI (99.9%): [2.346, 3.489] (assumes normal distribution)


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
# Warmup Iteration   1: 3.856 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 2.907 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.723 ±(99.9%) 0.003 ms/op
Iteration   1: 2.853 ±(99.9%) 0.004 ms/op
Iteration   2: 2.855 ±(99.9%) 0.001 ms/op
Iteration   3: 2.838 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.849 ±(99.9%) 0.165 ms/op [Average]
  (min, avg, max) = (2.838, 2.849, 2.855), stdev = 0.009
  CI (99.9%): [2.684, 3.014] (assumes normal distribution)


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
# Warmup Iteration   1: 3.873 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.978 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.962 ±(99.9%) 0.004 ms/op
Iteration   1: 2.886 ±(99.9%) 0.003 ms/op
Iteration   2: 2.949 ±(99.9%) 0.002 ms/op
Iteration   3: 2.887 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.908 ±(99.9%) 0.657 ms/op [Average]
  (min, avg, max) = (2.886, 2.908, 2.949), stdev = 0.036
  CI (99.9%): [2.251, 3.564] (assumes normal distribution)


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
# Warmup Iteration   1: 4.178 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.836 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 3.708 ±(99.9%) 0.017 ms/op
Iteration   1: 3.743 ±(99.9%) 0.035 ms/op
Iteration   2: 3.667 ±(99.9%) 0.032 ms/op
Iteration   3: 3.731 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.714 ±(99.9%) 0.742 ms/op [Average]
  (min, avg, max) = (3.667, 3.714, 3.743), stdev = 0.041
  CI (99.9%): [2.972, 4.455] (assumes normal distribution)


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
# Warmup Iteration   1: 3.918 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.038 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.948 ±(99.9%) 0.006 ms/op
Iteration   1: 2.963 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.716 ms/op
                 createUser·p0.50:   2.945 ms/op
                 createUser·p0.90:   3.432 ms/op
                 createUser·p0.95:   3.572 ms/op
                 createUser·p0.99:   4.448 ms/op
                 createUser·p0.999:  9.699 ms/op
                 createUser·p0.9999: 11.292 ms/op
                 createUser·p1.00:   11.633 ms/op

Iteration   2: 2.955 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.687 ms/op
                 createUser·p0.50:   2.933 ms/op
                 createUser·p0.90:   3.432 ms/op
                 createUser·p0.95:   3.633 ms/op
                 createUser·p0.99:   4.235 ms/op
                 createUser·p0.999:  10.858 ms/op
                 createUser·p0.9999: 13.599 ms/op
                 createUser·p1.00:   13.746 ms/op

Iteration   3: 2.943 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.778 ms/op
                 createUser·p0.50:   2.900 ms/op
                 createUser·p0.90:   3.445 ms/op
                 createUser·p0.95:   3.617 ms/op
                 createUser·p0.99:   4.477 ms/op
                 createUser·p0.999:  11.966 ms/op
                 createUser·p0.9999: 24.116 ms/op
                 createUser·p1.00:   24.969 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 324907
  mean =      2.954 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 34842 
    [ 2.500,  5.000) = 288614 
    [ 5.000,  7.500) = 1028 
    [ 7.500, 10.000) = 97 
    [10.000, 12.500) = 197 
    [12.500, 15.000) = 33 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.687 ms/op
     p(50.0000) =      2.929 ms/op
     p(90.0000) =      3.437 ms/op
     p(95.0000) =      3.604 ms/op
     p(99.0000) =      4.391 ms/op
     p(99.9000) =     10.029 ms/op
     p(99.9900) =     20.702 ms/op
     p(99.9990) =     24.896 ms/op
     p(99.9999) =     24.969 ms/op
    p(100.0000) =     24.969 ms/op


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
# Warmup Iteration   1: 3.225 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 2.931 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.800 ±(99.9%) 0.006 ms/op
Iteration   1: 2.842 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.314 ms/op
                 existUser·p0.50:   2.826 ms/op
                 existUser·p0.90:   3.326 ms/op
                 existUser·p0.95:   3.588 ms/op
                 existUser·p0.99:   4.407 ms/op
                 existUser·p0.999:  8.050 ms/op
                 existUser·p0.9999: 19.259 ms/op
                 existUser·p1.00:   19.431 ms/op

Iteration   2: 2.848 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.470 ms/op
                 existUser·p0.50:   2.830 ms/op
                 existUser·p0.90:   3.346 ms/op
                 existUser·p0.95:   3.527 ms/op
                 existUser·p0.99:   4.211 ms/op
                 existUser·p0.999:  5.975 ms/op
                 existUser·p0.9999: 12.837 ms/op
                 existUser·p1.00:   13.074 ms/op

Iteration   3: 2.841 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.627 ms/op
                 existUser·p0.50:   2.806 ms/op
                 existUser·p0.90:   3.314 ms/op
                 existUser·p0.95:   3.531 ms/op
                 existUser·p0.99:   4.290 ms/op
                 existUser·p0.999:  9.053 ms/op
                 existUser·p0.9999: 16.974 ms/op
                 existUser·p1.00:   19.071 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 337865
  mean =      2.843 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2405 
    [ 1.250,  2.500) = 56115 
    [ 2.500,  3.750) = 270019 
    [ 3.750,  5.000) = 8516 
    [ 5.000,  6.250) = 332 
    [ 6.250,  7.500) = 138 
    [ 7.500,  8.750) = 88 
    [ 8.750, 10.000) = 22 
    [10.000, 11.250) = 11 
    [11.250, 12.500) = 29 
    [12.500, 13.750) = 81 
    [13.750, 15.000) = 15 
    [15.000, 16.250) = 11 
    [16.250, 17.500) = 48 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.314 ms/op
     p(50.0000) =      2.822 ms/op
     p(90.0000) =      3.330 ms/op
     p(95.0000) =      3.543 ms/op
     p(99.0000) =      4.309 ms/op
     p(99.9000) =      7.513 ms/op
     p(99.9900) =     18.921 ms/op
     p(99.9990) =     19.386 ms/op
     p(99.9999) =     19.431 ms/op
    p(100.0000) =     19.431 ms/op


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
# Warmup Iteration   1: 3.966 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.026 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.961 ±(99.9%) 0.006 ms/op
Iteration   1: 2.949 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.500 ms/op
                 getUser·p0.50:   2.953 ms/op
                 getUser·p0.90:   3.531 ms/op
                 getUser·p0.95:   3.682 ms/op
                 getUser·p0.99:   4.219 ms/op
                 getUser·p0.999:  6.453 ms/op
                 getUser·p0.9999: 10.900 ms/op
                 getUser·p1.00:   12.141 ms/op

Iteration   2: 2.929 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.780 ms/op
                 getUser·p0.50:   2.912 ms/op
                 getUser·p0.90:   3.367 ms/op
                 getUser·p0.95:   3.551 ms/op
                 getUser·p0.99:   4.121 ms/op
                 getUser·p0.999:  6.706 ms/op
                 getUser·p0.9999: 20.846 ms/op
                 getUser·p1.00:   21.365 ms/op

Iteration   3: 2.970 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.779 ms/op
                 getUser·p0.50:   2.941 ms/op
                 getUser·p0.90:   3.473 ms/op
                 getUser·p0.95:   3.678 ms/op
                 getUser·p0.99:   4.342 ms/op
                 getUser·p0.999:  8.343 ms/op
                 getUser·p0.9999: 25.436 ms/op
                 getUser·p1.00:   25.657 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 325266
  mean =      2.949 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 34056 
    [ 2.500,  5.000) = 290182 
    [ 5.000,  7.500) = 736 
    [ 7.500, 10.000) = 111 
    [10.000, 12.500) = 80 
    [12.500, 15.000) = 24 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      0.500 ms/op
     p(50.0000) =      2.937 ms/op
     p(90.0000) =      3.461 ms/op
     p(95.0000) =      3.650 ms/op
     p(99.0000) =      4.219 ms/op
     p(99.9000) =      7.152 ms/op
     p(99.9900) =     22.466 ms/op
     p(99.9990) =     25.616 ms/op
     p(99.9999) =     25.657 ms/op
    p(100.0000) =     25.657 ms/op


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
# Warmup Iteration   1: 5.113 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.831 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.792 ±(99.9%) 0.009 ms/op
Iteration   1: 3.783 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.738 ms/op
                 listUser·p0.50:   3.662 ms/op
                 listUser·p0.90:   4.792 ms/op
                 listUser·p0.95:   5.431 ms/op
                 listUser·p0.99:   6.690 ms/op
                 listUser·p0.999:  12.230 ms/op
                 listUser·p0.9999: 16.027 ms/op
                 listUser·p1.00:   16.531 ms/op

Iteration   2: 3.764 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.106 ms/op
                 listUser·p0.50:   3.666 ms/op
                 listUser·p0.90:   4.588 ms/op
                 listUser·p0.95:   5.218 ms/op
                 listUser·p0.99:   6.373 ms/op
                 listUser·p0.999:  12.568 ms/op
                 listUser·p0.9999: 16.286 ms/op
                 listUser·p1.00:   16.466 ms/op

Iteration   3: 3.802 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.898 ms/op
                 listUser·p0.50:   3.633 ms/op
                 listUser·p0.90:   4.964 ms/op
                 listUser·p0.95:   5.685 ms/op
                 listUser·p0.99:   6.578 ms/op
                 listUser·p0.999:  13.676 ms/op
                 listUser·p0.9999: 20.602 ms/op
                 listUser·p1.00:   21.037 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 253761
  mean =      3.783 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8069 
    [ 2.500,  5.000) = 225735 
    [ 5.000,  7.500) = 18994 
    [ 7.500, 10.000) = 521 
    [10.000, 12.500) = 156 
    [12.500, 15.000) = 139 
    [15.000, 17.500) = 91 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.738 ms/op
     p(50.0000) =      3.654 ms/op
     p(90.0000) =      4.776 ms/op
     p(95.0000) =      5.472 ms/op
     p(99.0000) =      6.545 ms/op
     p(99.9000) =     12.812 ms/op
     p(99.9900) =     20.042 ms/op
     p(99.9990) =     20.904 ms/op
     p(99.9999) =     21.037 ms/op
    p(100.0000) =     21.037 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.888 ± 0.642  ops/ms
ClientGrpc.existUser                       thrpt       3  11.448 ± 2.052  ops/ms
ClientGrpc.getUser                         thrpt       3  10.973 ± 1.702  ops/ms
ClientGrpc.listUser                        thrpt       3   8.592 ± 3.611  ops/ms
ClientGrpc.createUser                       avgt       3   2.917 ± 0.571   ms/op
ClientGrpc.existUser                        avgt       3   2.849 ± 0.165   ms/op
ClientGrpc.getUser                          avgt       3   2.908 ± 0.657   ms/op
ClientGrpc.listUser                         avgt       3   3.714 ± 0.742   ms/op
ClientGrpc.createUser                     sample  324907   2.954 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.687           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.929           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.437           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.604           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.391           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.029           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.702           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          24.969           ms/op
ClientGrpc.existUser                      sample  337865   2.843 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.314           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.822           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.330           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.543           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.309           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.513           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.921           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.431           ms/op
ClientGrpc.getUser                        sample  325266   2.949 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.500           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.937           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.461           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.650           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.219           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.152           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          22.466           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          25.657           ms/op
ClientGrpc.listUser                       sample  253761   3.783 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.738           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.654           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.776           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.472           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.545           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          12.812           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          20.042           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          21.037           ms/op
