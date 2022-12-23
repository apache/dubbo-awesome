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
# Warmup Iteration   1: 5.171 ops/ms
# Warmup Iteration   2: 9.821 ops/ms
# Warmup Iteration   3: 10.388 ops/ms
Iteration   1: 10.297 ops/ms
Iteration   2: 10.852 ops/ms
Iteration   3: 10.529 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.559 ±(99.9%) 5.084 ops/ms [Average]
  (min, avg, max) = (10.297, 10.559, 10.852), stdev = 0.279
  CI (99.9%): [5.475, 15.644] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 7.647 ops/ms
# Warmup Iteration   2: 10.680 ops/ms
# Warmup Iteration   3: 11.054 ops/ms
Iteration   1: 10.997 ops/ms
Iteration   2: 10.894 ops/ms
Iteration   3: 11.026 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.973 ±(99.9%) 1.267 ops/ms [Average]
  (min, avg, max) = (10.894, 10.973, 11.026), stdev = 0.069
  CI (99.9%): [9.706, 12.240] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:50
# Fork: 1 of 1
# Warmup Iteration   1: 8.285 ops/ms
# Warmup Iteration   2: 10.514 ops/ms
# Warmup Iteration   3: 10.388 ops/ms
Iteration   1: 10.524 ops/ms
Iteration   2: 10.635 ops/ms
Iteration   3: 10.687 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.616 ±(99.9%) 1.525 ops/ms [Average]
  (min, avg, max) = (10.524, 10.616, 10.687), stdev = 0.084
  CI (99.9%): [9.090, 12.141] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 6.826 ops/ms
# Warmup Iteration   2: 7.925 ops/ms
# Warmup Iteration   3: 7.819 ops/ms
Iteration   1: 7.987 ops/ms
Iteration   2: 7.895 ops/ms
Iteration   3: 7.968 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.950 ±(99.9%) 0.886 ops/ms [Average]
  (min, avg, max) = (7.895, 7.950, 7.987), stdev = 0.049
  CI (99.9%): [7.064, 8.836] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 4.042 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.106 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.111 ±(99.9%) 0.002 ms/op
Iteration   1: 3.058 ±(99.9%) 0.003 ms/op
Iteration   2: 3.078 ±(99.9%) 0.003 ms/op
Iteration   3: 3.114 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.083 ±(99.9%) 0.525 ms/op [Average]
  (min, avg, max) = (3.058, 3.083, 3.114), stdev = 0.029
  CI (99.9%): [2.558, 3.609] (assumes normal distribution)


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
# Warmup Iteration   1: 3.712 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.972 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.988 ±(99.9%) 0.006 ms/op
Iteration   1: 2.851 ±(99.9%) 0.003 ms/op
Iteration   2: 2.919 ±(99.9%) 0.003 ms/op
Iteration   3: 2.849 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.873 ±(99.9%) 0.725 ms/op [Average]
  (min, avg, max) = (2.849, 2.873, 2.919), stdev = 0.040
  CI (99.9%): [2.148, 3.598] (assumes normal distribution)


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
# Warmup Iteration   1: 3.971 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.097 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.018 ±(99.9%) 0.003 ms/op
Iteration   1: 3.053 ±(99.9%) 0.003 ms/op
Iteration   2: 2.985 ±(99.9%) 0.004 ms/op
Iteration   3: 3.027 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.022 ±(99.9%) 0.627 ms/op [Average]
  (min, avg, max) = (2.985, 3.022, 3.053), stdev = 0.034
  CI (99.9%): [2.395, 3.648] (assumes normal distribution)


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
# Warmup Iteration   1: 5.201 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 4.114 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 4.033 ±(99.9%) 0.014 ms/op
Iteration   1: 3.977 ±(99.9%) 0.038 ms/op
Iteration   2: 3.983 ±(99.9%) 0.020 ms/op
Iteration   3: 4.054 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.004 ±(99.9%) 0.780 ms/op [Average]
  (min, avg, max) = (3.977, 4.004, 4.054), stdev = 0.043
  CI (99.9%): [3.225, 4.784] (assumes normal distribution)


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
# Warmup Iteration   1: 3.992 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.113 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.038 ±(99.9%) 0.007 ms/op
Iteration   1: 3.001 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.636 ms/op
                 createUser·p0.50:   3.019 ms/op
                 createUser·p0.90:   3.506 ms/op
                 createUser·p0.95:   3.731 ms/op
                 createUser·p0.99:   4.530 ms/op
                 createUser·p0.999:  7.758 ms/op
                 createUser·p0.9999: 19.694 ms/op
                 createUser·p1.00:   20.120 ms/op

Iteration   2: 3.075 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.651 ms/op
                 createUser·p0.50:   3.072 ms/op
                 createUser·p0.90:   3.768 ms/op
                 createUser·p0.95:   3.981 ms/op
                 createUser·p0.99:   4.481 ms/op
                 createUser·p0.999:  8.454 ms/op
                 createUser·p0.9999: 19.372 ms/op
                 createUser·p1.00:   19.792 ms/op

Iteration   3: 3.141 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.558 ms/op
                 createUser·p0.50:   3.117 ms/op
                 createUser·p0.90:   3.834 ms/op
                 createUser·p0.95:   4.030 ms/op
                 createUser·p0.99:   4.383 ms/op
                 createUser·p0.999:  10.486 ms/op
                 createUser·p0.9999: 23.521 ms/op
                 createUser·p1.00:   24.084 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 312482
  mean =      3.071 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 30697 
    [ 2.500,  5.000) = 280506 
    [ 5.000,  7.500) = 884 
    [ 7.500, 10.000) = 143 
    [10.000, 12.500) = 60 
    [12.500, 15.000) = 66 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 60 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.558 ms/op
     p(50.0000) =      3.060 ms/op
     p(90.0000) =      3.719 ms/op
     p(95.0000) =      3.949 ms/op
     p(99.0000) =      4.448 ms/op
     p(99.9000) =      8.430 ms/op
     p(99.9900) =     22.528 ms/op
     p(99.9990) =     23.982 ms/op
     p(99.9999) =     24.084 ms/op
    p(100.0000) =     24.084 ms/op


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
# Warmup Iteration   1: 3.912 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.056 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.971 ±(99.9%) 0.006 ms/op
Iteration   1: 2.891 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.606 ms/op
                 existUser·p0.50:   2.912 ms/op
                 existUser·p0.90:   3.576 ms/op
                 existUser·p0.95:   3.781 ms/op
                 existUser·p0.99:   4.211 ms/op
                 existUser·p0.999:  6.272 ms/op
                 existUser·p0.9999: 11.089 ms/op
                 existUser·p1.00:   11.518 ms/op

Iteration   2: 2.993 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.686 ms/op
                 existUser·p0.50:   2.986 ms/op
                 existUser·p0.90:   3.625 ms/op
                 existUser·p0.95:   3.822 ms/op
                 existUser·p0.99:   4.194 ms/op
                 existUser·p0.999:  7.189 ms/op
                 existUser·p0.9999: 12.763 ms/op
                 existUser·p1.00:   13.074 ms/op

Iteration   3: 2.967 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.762 ms/op
                 existUser·p0.50:   2.949 ms/op
                 existUser·p0.90:   3.572 ms/op
                 existUser·p0.95:   3.727 ms/op
                 existUser·p0.99:   4.088 ms/op
                 existUser·p0.999:  6.809 ms/op
                 existUser·p0.9999: 16.060 ms/op
                 existUser·p1.00:   16.646 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 325380
  mean =      2.949 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 4181 
    [ 1.250,  2.500) = 43090 
    [ 2.500,  3.750) = 260073 
    [ 3.750,  5.000) = 17244 
    [ 5.000,  6.250) = 391 
    [ 6.250,  7.500) = 158 
    [ 7.500,  8.750) = 42 
    [ 8.750, 10.000) = 29 
    [10.000, 11.250) = 68 
    [11.250, 12.500) = 24 
    [12.500, 13.750) = 24 
    [13.750, 15.000) = 7 
    [15.000, 16.250) = 43 
    [16.250, 17.500) = 6 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.606 ms/op
     p(50.0000) =      2.949 ms/op
     p(90.0000) =      3.592 ms/op
     p(95.0000) =      3.772 ms/op
     p(99.0000) =      4.182 ms/op
     p(99.9000) =      6.816 ms/op
     p(99.9900) =     15.498 ms/op
     p(99.9990) =     16.314 ms/op
     p(99.9999) =     16.646 ms/op
    p(100.0000) =     16.646 ms/op


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
# Warmup Iteration   1: 3.942 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.174 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.149 ±(99.9%) 0.007 ms/op
Iteration   1: 3.042 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.667 ms/op
                 getUser·p0.50:   3.039 ms/op
                 getUser·p0.90:   3.535 ms/op
                 getUser·p0.95:   3.805 ms/op
                 getUser·p0.99:   4.502 ms/op
                 getUser·p0.999:  8.550 ms/op
                 getUser·p0.9999: 16.015 ms/op
                 getUser·p1.00:   16.368 ms/op

Iteration   2: 3.104 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.419 ms/op
                 getUser·p0.50:   3.080 ms/op
                 getUser·p0.90:   3.699 ms/op
                 getUser·p0.95:   3.891 ms/op
                 getUser·p0.99:   4.260 ms/op
                 getUser·p0.999:  6.267 ms/op
                 getUser·p0.9999: 14.567 ms/op
                 getUser·p1.00:   14.844 ms/op

Iteration   3: 3.136 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.626 ms/op
                 getUser·p0.50:   3.129 ms/op
                 getUser·p0.90:   3.817 ms/op
                 getUser·p0.95:   4.002 ms/op
                 getUser·p0.99:   4.325 ms/op
                 getUser·p0.999:  7.012 ms/op
                 getUser·p0.9999: 27.060 ms/op
                 getUser·p1.00:   27.460 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 310150
  mean =      3.094 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21469 
    [ 2.500,  5.000) = 287724 
    [ 5.000,  7.500) = 689 
    [ 7.500, 10.000) = 124 
    [10.000, 12.500) = 35 
    [12.500, 15.000) = 46 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 16 

  Percentiles, ms/op:
      p(0.0000) =      0.419 ms/op
     p(50.0000) =      3.076 ms/op
     p(90.0000) =      3.707 ms/op
     p(95.0000) =      3.924 ms/op
     p(99.0000) =      4.350 ms/op
     p(99.9000) =      7.183 ms/op
     p(99.9900) =     24.182 ms/op
     p(99.9990) =     27.358 ms/op
     p(99.9999) =     27.460 ms/op
    p(100.0000) =     27.460 ms/op


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
# Warmup Iteration   1: 4.982 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.113 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.993 ±(99.9%) 0.010 ms/op
Iteration   1: 3.977 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.956 ms/op
                 listUser·p0.50:   3.826 ms/op
                 listUser·p0.90:   4.989 ms/op
                 listUser·p0.95:   5.677 ms/op
                 listUser·p0.99:   6.769 ms/op
                 listUser·p0.999:  12.673 ms/op
                 listUser·p0.9999: 15.974 ms/op
                 listUser·p1.00:   17.400 ms/op

Iteration   2: 3.967 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.100 ms/op
                 listUser·p0.50:   3.793 ms/op
                 listUser·p0.90:   5.054 ms/op
                 listUser·p0.95:   5.644 ms/op
                 listUser·p0.99:   6.758 ms/op
                 listUser·p0.999:  13.337 ms/op
                 listUser·p0.9999: 14.724 ms/op
                 listUser·p1.00:   18.252 ms/op

Iteration   3: 3.976 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.454 ms/op
                 listUser·p0.50:   3.793 ms/op
                 listUser·p0.90:   5.120 ms/op
                 listUser·p0.95:   5.644 ms/op
                 listUser·p0.99:   6.824 ms/op
                 listUser·p0.999:  14.527 ms/op
                 listUser·p0.9999: 17.531 ms/op
                 listUser·p1.00:   20.611 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 241444
  mean =      3.973 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3250 
    [ 2.500,  5.000) = 212189 
    [ 5.000,  7.500) = 24760 
    [ 7.500, 10.000) = 811 
    [10.000, 12.500) = 133 
    [12.500, 15.000) = 214 
    [15.000, 17.500) = 75 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.454 ms/op
     p(50.0000) =      3.805 ms/op
     p(90.0000) =      5.063 ms/op
     p(95.0000) =      5.652 ms/op
     p(99.0000) =      6.783 ms/op
     p(99.9000) =     13.240 ms/op
     p(99.9900) =     16.742 ms/op
     p(99.9990) =     19.519 ms/op
     p(99.9999) =     20.611 ms/op
    p(100.0000) =     20.611 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.559 ± 5.084  ops/ms
ClientGrpc.existUser                       thrpt       3  10.973 ± 1.267  ops/ms
ClientGrpc.getUser                         thrpt       3  10.616 ± 1.525  ops/ms
ClientGrpc.listUser                        thrpt       3   7.950 ± 0.886  ops/ms
ClientGrpc.createUser                       avgt       3   3.083 ± 0.525   ms/op
ClientGrpc.existUser                        avgt       3   2.873 ± 0.725   ms/op
ClientGrpc.getUser                          avgt       3   3.022 ± 0.627   ms/op
ClientGrpc.listUser                         avgt       3   4.004 ± 0.780   ms/op
ClientGrpc.createUser                     sample  312482   3.071 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.558           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.060           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.719           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.949           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.448           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.430           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          22.528           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          24.084           ms/op
ClientGrpc.existUser                      sample  325380   2.949 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.606           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.949           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.592           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.772           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.182           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.816           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.498           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          16.646           ms/op
ClientGrpc.getUser                        sample  310150   3.094 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.419           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.076           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.707           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.924           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.350           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.183           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          24.182           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          27.460           ms/op
ClientGrpc.listUser                       sample  241444   3.973 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.454           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.805           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.063           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.652           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.783           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.240           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          16.742           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          20.611           ms/op
