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
# Warmup Iteration   1: 3.977 ops/ms
# Warmup Iteration   2: 9.166 ops/ms
# Warmup Iteration   3: 10.206 ops/ms
Iteration   1: 10.267 ops/ms
Iteration   2: 10.730 ops/ms
Iteration   3: 10.323 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.440 ±(99.9%) 4.605 ops/ms [Average]
  (min, avg, max) = (10.267, 10.440, 10.730), stdev = 0.252
  CI (99.9%): [5.835, 15.045] (assumes normal distribution)


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
# Warmup Iteration   1: 7.438 ops/ms
# Warmup Iteration   2: 10.591 ops/ms
# Warmup Iteration   3: 11.035 ops/ms
Iteration   1: 10.980 ops/ms
Iteration   2: 10.960 ops/ms
Iteration   3: 10.874 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.938 ±(99.9%) 1.031 ops/ms [Average]
  (min, avg, max) = (10.874, 10.938, 10.980), stdev = 0.057
  CI (99.9%): [9.907, 11.969] (assumes normal distribution)


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
# Warmup Iteration   1: 6.616 ops/ms
# Warmup Iteration   2: 9.981 ops/ms
# Warmup Iteration   3: 10.616 ops/ms
Iteration   1: 10.427 ops/ms
Iteration   2: 10.400 ops/ms
Iteration   3: 10.472 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.433 ±(99.9%) 0.665 ops/ms [Average]
  (min, avg, max) = (10.400, 10.433, 10.472), stdev = 0.036
  CI (99.9%): [9.768, 11.098] (assumes normal distribution)


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
# Warmup Iteration   1: 5.750 ops/ms
# Warmup Iteration   2: 7.541 ops/ms
# Warmup Iteration   3: 8.003 ops/ms
Iteration   1: 8.121 ops/ms
Iteration   2: 8.224 ops/ms
Iteration   3: 8.089 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.145 ±(99.9%) 1.287 ops/ms [Average]
  (min, avg, max) = (8.089, 8.145, 8.224), stdev = 0.071
  CI (99.9%): [6.857, 9.432] (assumes normal distribution)


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
# Warmup Iteration   1: 4.339 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.180 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.071 ±(99.9%) 0.003 ms/op
Iteration   1: 3.044 ±(99.9%) 0.003 ms/op
Iteration   2: 3.060 ±(99.9%) 0.003 ms/op
Iteration   3: 2.993 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.032 ±(99.9%) 0.635 ms/op [Average]
  (min, avg, max) = (2.993, 3.032, 3.060), stdev = 0.035
  CI (99.9%): [2.397, 3.667] (assumes normal distribution)


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
# Warmup Iteration   1: 3.982 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.057 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.960 ±(99.9%) 0.002 ms/op
Iteration   1: 2.948 ±(99.9%) 0.002 ms/op
Iteration   2: 2.964 ±(99.9%) 0.003 ms/op
Iteration   3: 2.922 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.944 ±(99.9%) 0.390 ms/op [Average]
  (min, avg, max) = (2.922, 2.944, 2.964), stdev = 0.021
  CI (99.9%): [2.555, 3.334] (assumes normal distribution)


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
# Warmup Iteration   1: 4.278 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.150 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.013 ±(99.9%) 0.016 ms/op
Iteration   1: 3.076 ±(99.9%) 0.003 ms/op
Iteration   2: 3.043 ±(99.9%) 0.002 ms/op
Iteration   3: 3.036 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.052 ±(99.9%) 0.391 ms/op [Average]
  (min, avg, max) = (3.036, 3.052, 3.076), stdev = 0.021
  CI (99.9%): [2.661, 3.442] (assumes normal distribution)


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
# Warmup Iteration   1: 5.598 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 4.068 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.006 ±(99.9%) 0.009 ms/op
Iteration   1: 3.930 ±(99.9%) 0.017 ms/op
Iteration   2: 3.996 ±(99.9%) 0.031 ms/op
Iteration   3: 3.985 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.971 ±(99.9%) 0.644 ms/op [Average]
  (min, avg, max) = (3.930, 3.971, 3.996), stdev = 0.035
  CI (99.9%): [3.326, 4.615] (assumes normal distribution)


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
# Warmup Iteration   1: 4.239 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.213 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.037 ±(99.9%) 0.007 ms/op
Iteration   1: 3.049 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.612 ms/op
                 createUser·p0.50:   3.002 ms/op
                 createUser·p0.90:   3.576 ms/op
                 createUser·p0.95:   3.801 ms/op
                 createUser·p0.99:   4.579 ms/op
                 createUser·p0.999:  8.945 ms/op
                 createUser·p0.9999: 18.645 ms/op
                 createUser·p1.00:   19.005 ms/op

Iteration   2: 3.119 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.703 ms/op
                 createUser·p0.50:   3.068 ms/op
                 createUser·p0.90:   3.715 ms/op
                 createUser·p0.95:   3.879 ms/op
                 createUser·p0.99:   4.653 ms/op
                 createUser·p0.999:  8.888 ms/op
                 createUser·p0.9999: 13.795 ms/op
                 createUser·p1.00:   14.090 ms/op

Iteration   3: 3.075 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.771 ms/op
                 createUser·p0.50:   3.043 ms/op
                 createUser·p0.90:   3.531 ms/op
                 createUser·p0.95:   3.695 ms/op
                 createUser·p0.99:   4.204 ms/op
                 createUser·p0.999:  7.335 ms/op
                 createUser·p0.9999: 24.904 ms/op
                 createUser·p1.00:   25.297 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 311733
  mean =      3.081 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18234 
    [ 2.500,  5.000) = 291862 
    [ 5.000,  7.500) = 1217 
    [ 7.500, 10.000) = 192 
    [10.000, 12.500) = 5 
    [12.500, 15.000) = 96 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 45 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.612 ms/op
     p(50.0000) =      3.035 ms/op
     p(90.0000) =      3.609 ms/op
     p(95.0000) =      3.809 ms/op
     p(99.0000) =      4.465 ms/op
     p(99.9000) =      8.815 ms/op
     p(99.9900) =     22.965 ms/op
     p(99.9990) =     25.158 ms/op
     p(99.9999) =     25.297 ms/op
    p(100.0000) =     25.297 ms/op


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
# Warmup Iteration   1: 3.701 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.008 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.951 ±(99.9%) 0.005 ms/op
Iteration   1: 2.959 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.761 ms/op
                 existUser·p0.50:   2.925 ms/op
                 existUser·p0.90:   3.441 ms/op
                 existUser·p0.95:   3.629 ms/op
                 existUser·p0.99:   4.514 ms/op
                 existUser·p0.999:  7.578 ms/op
                 existUser·p0.9999: 18.265 ms/op
                 existUser·p1.00:   18.940 ms/op

Iteration   2: 2.918 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.831 ms/op
                 existUser·p0.50:   2.892 ms/op
                 existUser·p0.90:   3.420 ms/op
                 existUser·p0.95:   3.613 ms/op
                 existUser·p0.99:   4.448 ms/op
                 existUser·p0.999:  5.938 ms/op
                 existUser·p0.9999: 13.812 ms/op
                 existUser·p1.00:   14.123 ms/op

Iteration   3: 2.890 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.765 ms/op
                 existUser·p0.50:   2.892 ms/op
                 existUser·p0.90:   3.318 ms/op
                 existUser·p0.95:   3.518 ms/op
                 existUser·p0.99:   4.260 ms/op
                 existUser·p0.999:  7.071 ms/op
                 existUser·p0.9999: 17.528 ms/op
                 existUser·p1.00:   17.793 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 328386
  mean =      2.922 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1459 
    [ 1.250,  2.500) = 36387 
    [ 2.500,  3.750) = 280690 
    [ 3.750,  5.000) = 8590 
    [ 5.000,  6.250) = 770 
    [ 6.250,  7.500) = 241 
    [ 7.500,  8.750) = 54 
    [ 8.750, 10.000) = 18 
    [10.000, 11.250) = 11 
    [11.250, 12.500) = 38 
    [12.500, 13.750) = 15 
    [13.750, 15.000) = 23 
    [15.000, 16.250) = 4 
    [16.250, 17.500) = 48 
    [17.500, 18.750) = 36 

  Percentiles, ms/op:
      p(0.0000) =      0.761 ms/op
     p(50.0000) =      2.900 ms/op
     p(90.0000) =      3.400 ms/op
     p(95.0000) =      3.592 ms/op
     p(99.0000) =      4.407 ms/op
     p(99.9000) =      6.955 ms/op
     p(99.9900) =     17.596 ms/op
     p(99.9990) =     18.725 ms/op
     p(99.9999) =     18.940 ms/op
    p(100.0000) =     18.940 ms/op


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
# Warmup Iteration   1: 4.318 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.159 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.065 ±(99.9%) 0.007 ms/op
Iteration   1: 3.090 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.852 ms/op
                 getUser·p0.50:   3.043 ms/op
                 getUser·p0.90:   3.719 ms/op
                 getUser·p0.95:   3.949 ms/op
                 getUser·p0.99:   4.555 ms/op
                 getUser·p0.999:  7.542 ms/op
                 getUser·p0.9999: 15.323 ms/op
                 getUser·p1.00:   15.811 ms/op

Iteration   2: 3.052 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.740 ms/op
                 getUser·p0.50:   3.023 ms/op
                 getUser·p0.90:   3.453 ms/op
                 getUser·p0.95:   3.633 ms/op
                 getUser·p0.99:   4.383 ms/op
                 getUser·p0.999:  8.131 ms/op
                 getUser·p0.9999: 16.876 ms/op
                 getUser·p1.00:   17.662 ms/op

Iteration   3: 3.051 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.020 ms/op
                 getUser·p0.50:   3.006 ms/op
                 getUser·p0.90:   3.514 ms/op
                 getUser·p0.95:   3.797 ms/op
                 getUser·p0.99:   4.547 ms/op
                 getUser·p0.999:  8.412 ms/op
                 getUser·p0.9999: 21.021 ms/op
                 getUser·p1.00:   21.299 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 313136
  mean =      3.064 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15342 
    [ 2.500,  5.000) = 296407 
    [ 5.000,  7.500) = 1017 
    [ 7.500, 10.000) = 192 
    [10.000, 12.500) = 18 
    [12.500, 15.000) = 24 
    [15.000, 17.500) = 67 
    [17.500, 20.000) = 36 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.740 ms/op
     p(50.0000) =      3.023 ms/op
     p(90.0000) =      3.559 ms/op
     p(95.0000) =      3.830 ms/op
     p(99.0000) =      4.506 ms/op
     p(99.9000) =      7.922 ms/op
     p(99.9900) =     20.361 ms/op
     p(99.9990) =     21.291 ms/op
     p(99.9999) =     21.299 ms/op
    p(100.0000) =     21.299 ms/op


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
# Warmup Iteration   1: 5.410 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 4.124 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.010 ±(99.9%) 0.011 ms/op
Iteration   1: 4.001 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.049 ms/op
                 listUser·p0.50:   3.846 ms/op
                 listUser·p0.90:   4.997 ms/op
                 listUser·p0.95:   5.767 ms/op
                 listUser·p0.99:   6.944 ms/op
                 listUser·p0.999:  12.225 ms/op
                 listUser·p0.9999: 19.792 ms/op
                 listUser·p1.00:   20.087 ms/op

Iteration   2: 3.996 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.380 ms/op
                 listUser·p0.50:   3.830 ms/op
                 listUser·p0.90:   5.038 ms/op
                 listUser·p0.95:   5.865 ms/op
                 listUser·p0.99:   6.947 ms/op
                 listUser·p0.999:  14.707 ms/op
                 listUser·p0.9999: 21.756 ms/op
                 listUser·p1.00:   22.217 ms/op

Iteration   3: 3.994 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.268 ms/op
                 listUser·p0.50:   3.817 ms/op
                 listUser·p0.90:   5.087 ms/op
                 listUser·p0.95:   5.530 ms/op
                 listUser·p0.99:   6.774 ms/op
                 listUser·p0.999:  15.348 ms/op
                 listUser·p0.9999: 20.312 ms/op
                 listUser·p1.00:   21.463 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 240334
  mean =      3.997 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2472 
    [ 2.500,  5.000) = 212624 
    [ 5.000,  7.500) = 24022 
    [ 7.500, 10.000) = 842 
    [10.000, 12.500) = 46 
    [12.500, 15.000) = 120 
    [15.000, 17.500) = 97 
    [17.500, 20.000) = 75 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.049 ms/op
     p(50.0000) =      3.834 ms/op
     p(90.0000) =      5.046 ms/op
     p(95.0000) =      5.702 ms/op
     p(99.0000) =      6.898 ms/op
     p(99.9000) =     14.565 ms/op
     p(99.9900) =     20.283 ms/op
     p(99.9990) =     22.125 ms/op
     p(99.9999) =     22.217 ms/op
    p(100.0000) =     22.217 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.440 ± 4.605  ops/ms
ClientGrpc.existUser                       thrpt       3  10.938 ± 1.031  ops/ms
ClientGrpc.getUser                         thrpt       3  10.433 ± 0.665  ops/ms
ClientGrpc.listUser                        thrpt       3   8.145 ± 1.287  ops/ms
ClientGrpc.createUser                       avgt       3   3.032 ± 0.635   ms/op
ClientGrpc.existUser                        avgt       3   2.944 ± 0.390   ms/op
ClientGrpc.getUser                          avgt       3   3.052 ± 0.391   ms/op
ClientGrpc.listUser                         avgt       3   3.971 ± 0.644   ms/op
ClientGrpc.createUser                     sample  311733   3.081 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.612           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.035           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.609           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.809           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.465           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.815           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          22.965           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          25.297           ms/op
ClientGrpc.existUser                      sample  328386   2.922 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.761           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.900           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.400           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.592           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.407           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.955           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.596           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.940           ms/op
ClientGrpc.getUser                        sample  313136   3.064 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.740           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.023           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.559           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.830           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.506           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.922           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.361           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.299           ms/op
ClientGrpc.listUser                       sample  240334   3.997 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.049           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.834           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.046           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.702           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.898           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.565           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          20.283           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          22.217           ms/op
