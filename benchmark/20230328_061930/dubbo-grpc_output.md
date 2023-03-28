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
# Warmup Iteration   1: 4.024 ops/ms
# Warmup Iteration   2: 9.191 ops/ms
# Warmup Iteration   3: 10.121 ops/ms
Iteration   1: 10.378 ops/ms
Iteration   2: 10.245 ops/ms
Iteration   3: 10.632 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.418 ±(99.9%) 3.585 ops/ms [Average]
  (min, avg, max) = (10.245, 10.418, 10.632), stdev = 0.197
  CI (99.9%): [6.833, 14.003] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.965 ops/ms
# Warmup Iteration   2: 10.473 ops/ms
# Warmup Iteration   3: 11.142 ops/ms
Iteration   1: 11.131 ops/ms
Iteration   2: 10.992 ops/ms
Iteration   3: 11.079 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.068 ±(99.9%) 1.285 ops/ms [Average]
  (min, avg, max) = (10.992, 11.068, 11.131), stdev = 0.070
  CI (99.9%): [9.783, 12.352] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.350 ops/ms
# Warmup Iteration   2: 10.112 ops/ms
# Warmup Iteration   3: 10.511 ops/ms
Iteration   1: 10.451 ops/ms
Iteration   2: 10.712 ops/ms
Iteration   3: 10.451 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.538 ±(99.9%) 2.752 ops/ms [Average]
  (min, avg, max) = (10.451, 10.538, 10.712), stdev = 0.151
  CI (99.9%): [7.786, 13.290] (assumes normal distribution)


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
# Warmup Iteration   1: 5.338 ops/ms
# Warmup Iteration   2: 7.814 ops/ms
# Warmup Iteration   3: 8.132 ops/ms
Iteration   1: 8.072 ops/ms
Iteration   2: 8.014 ops/ms
Iteration   3: 8.055 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.047 ±(99.9%) 0.542 ops/ms [Average]
  (min, avg, max) = (8.014, 8.047, 8.072), stdev = 0.030
  CI (99.9%): [7.505, 8.589] (assumes normal distribution)


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
# Warmup Iteration   1: 4.076 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.208 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.081 ±(99.9%) 0.003 ms/op
Iteration   1: 3.026 ±(99.9%) 0.004 ms/op
Iteration   2: 2.996 ±(99.9%) 0.002 ms/op
Iteration   3: 3.038 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.020 ±(99.9%) 0.390 ms/op [Average]
  (min, avg, max) = (2.996, 3.020, 3.038), stdev = 0.021
  CI (99.9%): [2.630, 3.409] (assumes normal distribution)


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
# Warmup Iteration   1: 3.930 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.061 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.911 ±(99.9%) 0.002 ms/op
Iteration   1: 2.849 ±(99.9%) 0.002 ms/op
Iteration   2: 2.797 ±(99.9%) 0.002 ms/op
Iteration   3: 2.868 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.838 ±(99.9%) 0.673 ms/op [Average]
  (min, avg, max) = (2.797, 2.838, 2.868), stdev = 0.037
  CI (99.9%): [2.164, 3.511] (assumes normal distribution)


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
# Warmup Iteration   1: 4.129 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.116 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.046 ±(99.9%) 0.004 ms/op
Iteration   1: 3.042 ±(99.9%) 0.004 ms/op
Iteration   2: 3.017 ±(99.9%) 0.002 ms/op
Iteration   3: 3.012 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.024 ±(99.9%) 0.298 ms/op [Average]
  (min, avg, max) = (3.012, 3.024, 3.042), stdev = 0.016
  CI (99.9%): [2.725, 3.322] (assumes normal distribution)


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
# Warmup Iteration   1: 4.859 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 4.071 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.012 ±(99.9%) 0.049 ms/op
Iteration   1: 3.955 ±(99.9%) 0.014 ms/op
Iteration   2: 3.964 ±(99.9%) 0.016 ms/op
Iteration   3: 4.015 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.978 ±(99.9%) 0.591 ms/op [Average]
  (min, avg, max) = (3.955, 3.978, 4.015), stdev = 0.032
  CI (99.9%): [3.387, 4.569] (assumes normal distribution)


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
# Warmup Iteration   1: 4.071 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.222 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.007 ±(99.9%) 0.006 ms/op
Iteration   1: 2.958 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.814 ms/op
                 createUser·p0.50:   2.941 ms/op
                 createUser·p0.90:   3.432 ms/op
                 createUser·p0.95:   3.662 ms/op
                 createUser·p0.99:   4.620 ms/op
                 createUser·p0.999:  6.799 ms/op
                 createUser·p0.9999: 13.468 ms/op
                 createUser·p1.00:   13.697 ms/op

Iteration   2: 2.965 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.338 ms/op
                 createUser·p0.50:   2.941 ms/op
                 createUser·p0.90:   3.322 ms/op
                 createUser·p0.95:   3.478 ms/op
                 createUser·p0.99:   4.342 ms/op
                 createUser·p0.999:  6.980 ms/op
                 createUser·p0.9999: 14.556 ms/op
                 createUser·p1.00:   15.139 ms/op

Iteration   3: 3.011 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.304 ms/op
                 createUser·p0.50:   2.970 ms/op
                 createUser·p0.90:   3.428 ms/op
                 createUser·p0.95:   3.633 ms/op
                 createUser·p0.99:   4.554 ms/op
                 createUser·p0.999:  7.873 ms/op
                 createUser·p0.9999: 24.588 ms/op
                 createUser·p1.00:   25.002 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 322543
  mean =      2.978 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26750 
    [ 2.500,  5.000) = 294269 
    [ 5.000,  7.500) = 1240 
    [ 7.500, 10.000) = 60 
    [10.000, 12.500) = 56 
    [12.500, 15.000) = 104 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.304 ms/op
     p(50.0000) =      2.949 ms/op
     p(90.0000) =      3.396 ms/op
     p(95.0000) =      3.600 ms/op
     p(99.0000) =      4.514 ms/op
     p(99.9000) =      7.192 ms/op
     p(99.9900) =     21.354 ms/op
     p(99.9990) =     24.823 ms/op
     p(99.9999) =     25.002 ms/op
    p(100.0000) =     25.002 ms/op


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
# Warmup Iteration   1: 3.492 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 2.962 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.857 ±(99.9%) 0.006 ms/op
Iteration   1: 2.881 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.818 ms/op
                 existUser·p0.50:   2.867 ms/op
                 existUser·p0.90:   3.363 ms/op
                 existUser·p0.95:   3.551 ms/op
                 existUser·p0.99:   4.514 ms/op
                 existUser·p0.999:  7.118 ms/op
                 existUser·p0.9999: 14.562 ms/op
                 existUser·p1.00:   14.991 ms/op

Iteration   2: 2.904 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.396 ms/op
                 existUser·p0.50:   2.871 ms/op
                 existUser·p0.90:   3.355 ms/op
                 existUser·p0.95:   3.633 ms/op
                 existUser·p0.99:   4.612 ms/op
                 existUser·p0.999:  6.865 ms/op
                 existUser·p0.9999: 19.202 ms/op
                 existUser·p1.00:   19.857 ms/op

Iteration   3: 2.886 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.600 ms/op
                 existUser·p0.50:   2.863 ms/op
                 existUser·p0.90:   3.293 ms/op
                 existUser·p0.95:   3.461 ms/op
                 existUser·p0.99:   4.131 ms/op
                 existUser·p0.999:  6.865 ms/op
                 existUser·p0.9999: 18.773 ms/op
                 existUser·p1.00:   19.137 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 332322
  mean =      2.890 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1469 
    [ 1.250,  2.500) = 42355 
    [ 2.500,  3.750) = 278815 
    [ 3.750,  5.000) = 8242 
    [ 5.000,  6.250) = 822 
    [ 6.250,  7.500) = 420 
    [ 7.500,  8.750) = 38 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 26 
    [13.750, 15.000) = 38 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 32 
    [17.500, 18.750) = 41 

  Percentiles, ms/op:
      p(0.0000) =      0.396 ms/op
     p(50.0000) =      2.867 ms/op
     p(90.0000) =      3.334 ms/op
     p(95.0000) =      3.543 ms/op
     p(99.0000) =      4.489 ms/op
     p(99.9000) =      6.928 ms/op
     p(99.9900) =     18.146 ms/op
     p(99.9990) =     19.662 ms/op
     p(99.9999) =     19.857 ms/op
    p(100.0000) =     19.857 ms/op


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
# Warmup Iteration   1: 4.122 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.161 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.024 ±(99.9%) 0.007 ms/op
Iteration   1: 3.058 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.788 ms/op
                 getUser·p0.50:   3.019 ms/op
                 getUser·p0.90:   3.584 ms/op
                 getUser·p0.95:   3.764 ms/op
                 getUser·p0.99:   4.424 ms/op
                 getUser·p0.999:  7.571 ms/op
                 getUser·p0.9999: 19.729 ms/op
                 getUser·p1.00:   20.185 ms/op

Iteration   2: 3.012 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.886 ms/op
                 getUser·p0.50:   2.966 ms/op
                 getUser·p0.90:   3.432 ms/op
                 getUser·p0.95:   3.727 ms/op
                 getUser·p0.99:   4.792 ms/op
                 getUser·p0.999:  8.730 ms/op
                 getUser·p0.9999: 23.769 ms/op
                 getUser·p1.00:   24.084 ms/op

Iteration   3: 3.009 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.733 ms/op
                 getUser·p0.50:   2.974 ms/op
                 getUser·p0.90:   3.482 ms/op
                 getUser·p0.95:   3.731 ms/op
                 getUser·p0.99:   4.547 ms/op
                 getUser·p0.999:  6.791 ms/op
                 getUser·p0.9999: 30.376 ms/op
                 getUser·p1.00:   30.704 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 317159
  mean =      3.026 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22321 
    [ 2.500,  5.000) = 293068 
    [ 5.000,  7.500) = 1447 
    [ 7.500, 10.000) = 140 
    [10.000, 12.500) = 23 
    [12.500, 15.000) = 56 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 21 
    [30.000, 32.500) = 11 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.733 ms/op
     p(50.0000) =      2.986 ms/op
     p(90.0000) =      3.514 ms/op
     p(95.0000) =      3.744 ms/op
     p(99.0000) =      4.604 ms/op
     p(99.9000) =      7.635 ms/op
     p(99.9900) =     28.155 ms/op
     p(99.9990) =     30.605 ms/op
     p(99.9999) =     30.704 ms/op
    p(100.0000) =     30.704 ms/op


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
# Warmup Iteration   1: 5.327 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 4.070 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.988 ±(99.9%) 0.011 ms/op
Iteration   1: 3.952 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.733 ms/op
                 listUser·p0.50:   3.793 ms/op
                 listUser·p0.90:   4.989 ms/op
                 listUser·p0.95:   5.595 ms/op
                 listUser·p0.99:   6.914 ms/op
                 listUser·p0.999:  14.449 ms/op
                 listUser·p0.9999: 22.105 ms/op
                 listUser·p1.00:   22.807 ms/op

Iteration   2: 3.958 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.937 ms/op
                 listUser·p0.50:   3.809 ms/op
                 listUser·p0.90:   4.727 ms/op
                 listUser·p0.95:   5.652 ms/op
                 listUser·p0.99:   6.890 ms/op
                 listUser·p0.999:  17.236 ms/op
                 listUser·p0.9999: 24.404 ms/op
                 listUser·p1.00:   24.904 ms/op

Iteration   3: 3.965 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.977 ms/op
                 listUser·p0.50:   3.805 ms/op
                 listUser·p0.90:   4.825 ms/op
                 listUser·p0.95:   5.702 ms/op
                 listUser·p0.99:   6.980 ms/op
                 listUser·p0.999:  15.843 ms/op
                 listUser·p0.9999: 22.531 ms/op
                 listUser·p1.00:   23.200 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 242643
  mean =      3.959 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2656 
    [ 2.500,  5.000) = 218930 
    [ 5.000,  7.500) = 19734 
    [ 7.500, 10.000) = 866 
    [10.000, 12.500) = 83 
    [12.500, 15.000) = 95 
    [15.000, 17.500) = 118 
    [17.500, 20.000) = 57 
    [20.000, 22.500) = 63 
    [22.500, 25.000) = 41 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.733 ms/op
     p(50.0000) =      3.801 ms/op
     p(90.0000) =      4.866 ms/op
     p(95.0000) =      5.652 ms/op
     p(99.0000) =      6.922 ms/op
     p(99.9000) =     15.898 ms/op
     p(99.9900) =     22.994 ms/op
     p(99.9990) =     24.777 ms/op
     p(99.9999) =     24.904 ms/op
    p(100.0000) =     24.904 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.418 ± 3.585  ops/ms
ClientGrpc.existUser                       thrpt       3  11.068 ± 1.285  ops/ms
ClientGrpc.getUser                         thrpt       3  10.538 ± 2.752  ops/ms
ClientGrpc.listUser                        thrpt       3   8.047 ± 0.542  ops/ms
ClientGrpc.createUser                       avgt       3   3.020 ± 0.390   ms/op
ClientGrpc.existUser                        avgt       3   2.838 ± 0.673   ms/op
ClientGrpc.getUser                          avgt       3   3.024 ± 0.298   ms/op
ClientGrpc.listUser                         avgt       3   3.978 ± 0.591   ms/op
ClientGrpc.createUser                     sample  322543   2.978 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.304           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.949           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.396           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.600           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.514           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.192           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.354           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          25.002           ms/op
ClientGrpc.existUser                      sample  332322   2.890 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.396           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.867           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.334           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.543           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.489           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.928           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.146           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.857           ms/op
ClientGrpc.getUser                        sample  317159   3.026 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.733           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.986           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.514           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.744           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.604           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.635           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          28.155           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          30.704           ms/op
ClientGrpc.listUser                       sample  242643   3.959 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.733           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.801           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.866           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.652           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.922           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.898           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.994           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.904           ms/op
