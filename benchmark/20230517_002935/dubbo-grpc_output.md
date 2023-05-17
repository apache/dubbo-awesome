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
# Warmup Iteration   1: 4.300 ops/ms
# Warmup Iteration   2: 9.450 ops/ms
# Warmup Iteration   3: 10.378 ops/ms
Iteration   1: 10.368 ops/ms
Iteration   2: 10.830 ops/ms
Iteration   3: 10.721 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.640 ±(99.9%) 4.410 ops/ms [Average]
  (min, avg, max) = (10.368, 10.640, 10.830), stdev = 0.242
  CI (99.9%): [6.230, 15.049] (assumes normal distribution)


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
# Warmup Iteration   1: 7.647 ops/ms
# Warmup Iteration   2: 10.882 ops/ms
# Warmup Iteration   3: 11.260 ops/ms
Iteration   1: 11.317 ops/ms
Iteration   2: 11.390 ops/ms
Iteration   3: 11.497 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.401 ±(99.9%) 1.655 ops/ms [Average]
  (min, avg, max) = (11.317, 11.401, 11.497), stdev = 0.091
  CI (99.9%): [9.746, 13.056] (assumes normal distribution)


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
# Warmup Iteration   1: 7.146 ops/ms
# Warmup Iteration   2: 10.213 ops/ms
# Warmup Iteration   3: 10.467 ops/ms
Iteration   1: 10.567 ops/ms
Iteration   2: 10.749 ops/ms
Iteration   3: 10.497 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.604 ±(99.9%) 2.373 ops/ms [Average]
  (min, avg, max) = (10.497, 10.604, 10.749), stdev = 0.130
  CI (99.9%): [8.232, 12.977] (assumes normal distribution)


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
# Warmup Iteration   1: 6.044 ops/ms
# Warmup Iteration   2: 7.531 ops/ms
# Warmup Iteration   3: 8.048 ops/ms
Iteration   1: 8.177 ops/ms
Iteration   2: 8.144 ops/ms
Iteration   3: 8.192 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.171 ±(99.9%) 0.453 ops/ms [Average]
  (min, avg, max) = (8.144, 8.171, 8.192), stdev = 0.025
  CI (99.9%): [7.718, 8.624] (assumes normal distribution)


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
# Warmup Iteration   1: 4.087 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.172 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.039 ±(99.9%) 0.003 ms/op
Iteration   1: 3.030 ±(99.9%) 0.003 ms/op
Iteration   2: 3.038 ±(99.9%) 0.002 ms/op
Iteration   3: 3.061 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.043 ±(99.9%) 0.292 ms/op [Average]
  (min, avg, max) = (3.030, 3.043, 3.061), stdev = 0.016
  CI (99.9%): [2.750, 3.335] (assumes normal distribution)


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
# Warmup Iteration   1: 3.909 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.976 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.889 ±(99.9%) 0.002 ms/op
Iteration   1: 2.886 ±(99.9%) 0.002 ms/op
Iteration   2: 2.911 ±(99.9%) 0.002 ms/op
Iteration   3: 2.899 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.898 ±(99.9%) 0.223 ms/op [Average]
  (min, avg, max) = (2.886, 2.898, 2.911), stdev = 0.012
  CI (99.9%): [2.675, 3.122] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 4.136 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.059 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.961 ±(99.9%) 0.003 ms/op
Iteration   1: 2.999 ±(99.9%) 0.002 ms/op
Iteration   2: 2.973 ±(99.9%) 0.004 ms/op
Iteration   3: 2.993 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.988 ±(99.9%) 0.253 ms/op [Average]
  (min, avg, max) = (2.973, 2.988, 2.999), stdev = 0.014
  CI (99.9%): [2.735, 3.242] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 5.201 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.059 ±(99.9%) 0.032 ms/op
# Warmup Iteration   3: 3.885 ±(99.9%) 0.031 ms/op
Iteration   1: 3.948 ±(99.9%) 0.022 ms/op
Iteration   2: 3.920 ±(99.9%) 0.033 ms/op
Iteration   3: 3.883 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.917 ±(99.9%) 0.594 ms/op [Average]
  (min, avg, max) = (3.883, 3.917, 3.948), stdev = 0.033
  CI (99.9%): [3.323, 4.511] (assumes normal distribution)


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
# Warmup Iteration   1: 4.371 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.201 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.056 ±(99.9%) 0.007 ms/op
Iteration   1: 3.058 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.933 ms/op
                 createUser·p0.50:   3.019 ms/op
                 createUser·p0.90:   3.588 ms/op
                 createUser·p0.95:   3.748 ms/op
                 createUser·p0.99:   4.432 ms/op
                 createUser·p0.999:  8.198 ms/op
                 createUser·p0.9999: 13.633 ms/op
                 createUser·p1.00:   13.976 ms/op

Iteration   2: 3.060 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.885 ms/op
                 createUser·p0.50:   3.035 ms/op
                 createUser·p0.90:   3.609 ms/op
                 createUser·p0.95:   3.797 ms/op
                 createUser·p0.99:   4.645 ms/op
                 createUser·p0.999:  8.659 ms/op
                 createUser·p0.9999: 14.207 ms/op
                 createUser·p1.00:   14.451 ms/op

Iteration   3: 3.078 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.448 ms/op
                 createUser·p0.50:   3.043 ms/op
                 createUser·p0.90:   3.555 ms/op
                 createUser·p0.95:   3.748 ms/op
                 createUser·p0.99:   4.506 ms/op
                 createUser·p0.999:  14.401 ms/op
                 createUser·p0.9999: 30.704 ms/op
                 createUser·p1.00:   30.769 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 313179
  mean =      3.065 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21104 
    [ 2.500,  5.000) = 290302 
    [ 5.000,  7.500) = 1355 
    [ 7.500, 10.000) = 115 
    [10.000, 12.500) = 100 
    [12.500, 15.000) = 123 
    [15.000, 17.500) = 51 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 1 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 17 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.448 ms/op
     p(50.0000) =      3.031 ms/op
     p(90.0000) =      3.584 ms/op
     p(95.0000) =      3.764 ms/op
     p(99.0000) =      4.522 ms/op
     p(99.9000) =      9.136 ms/op
     p(99.9900) =     16.704 ms/op
     p(99.9990) =     30.736 ms/op
     p(99.9999) =     30.769 ms/op
    p(100.0000) =     30.769 ms/op


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
# Warmup Iteration   1: 4.078 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.005 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.837 ±(99.9%) 0.006 ms/op
Iteration   1: 2.859 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.698 ms/op
                 existUser·p0.50:   2.863 ms/op
                 existUser·p0.90:   3.191 ms/op
                 existUser·p0.95:   3.318 ms/op
                 existUser·p0.99:   4.121 ms/op
                 existUser·p0.999:  6.971 ms/op
                 existUser·p0.9999: 16.571 ms/op
                 existUser·p1.00:   16.908 ms/op

Iteration   2: 2.876 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.643 ms/op
                 existUser·p0.50:   2.875 ms/op
                 existUser·p0.90:   3.297 ms/op
                 existUser·p0.95:   3.437 ms/op
                 existUser·p0.99:   4.035 ms/op
                 existUser·p0.999:  10.398 ms/op
                 existUser·p0.9999: 16.974 ms/op
                 existUser·p1.00:   17.564 ms/op

Iteration   3: 2.870 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.771 ms/op
                 existUser·p0.50:   2.863 ms/op
                 existUser·p0.90:   3.248 ms/op
                 existUser·p0.95:   3.465 ms/op
                 existUser·p0.99:   4.189 ms/op
                 existUser·p0.999:  6.517 ms/op
                 existUser·p0.9999: 20.995 ms/op
                 existUser·p1.00:   21.463 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 334496
  mean =      2.868 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 38001 
    [ 2.500,  5.000) = 295589 
    [ 5.000,  7.500) = 578 
    [ 7.500, 10.000) = 40 
    [10.000, 12.500) = 96 
    [12.500, 15.000) = 8 
    [15.000, 17.500) = 119 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 40 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.643 ms/op
     p(50.0000) =      2.863 ms/op
     p(90.0000) =      3.244 ms/op
     p(95.0000) =      3.413 ms/op
     p(99.0000) =      4.129 ms/op
     p(99.9000) =      7.451 ms/op
     p(99.9900) =     20.421 ms/op
     p(99.9990) =     21.342 ms/op
     p(99.9999) =     21.463 ms/op
    p(100.0000) =     21.463 ms/op


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
# Warmup Iteration   1: 4.246 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.170 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.060 ±(99.9%) 0.006 ms/op
Iteration   1: 3.001 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.645 ms/op
                 getUser·p0.50:   2.978 ms/op
                 getUser·p0.90:   3.523 ms/op
                 getUser·p0.95:   3.809 ms/op
                 getUser·p0.99:   4.702 ms/op
                 getUser·p0.999:  7.609 ms/op
                 getUser·p0.9999: 19.061 ms/op
                 getUser·p1.00:   19.661 ms/op

Iteration   2: 3.019 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.846 ms/op
                 getUser·p0.50:   2.982 ms/op
                 getUser·p0.90:   3.559 ms/op
                 getUser·p0.95:   3.777 ms/op
                 getUser·p0.99:   4.596 ms/op
                 getUser·p0.999:  6.832 ms/op
                 getUser·p0.9999: 18.001 ms/op
                 getUser·p1.00:   19.726 ms/op

Iteration   3: 2.987 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.922 ms/op
                 getUser·p0.50:   2.953 ms/op
                 getUser·p0.90:   3.506 ms/op
                 getUser·p0.95:   3.777 ms/op
                 getUser·p0.99:   4.727 ms/op
                 getUser·p0.999:  8.912 ms/op
                 getUser·p0.9999: 15.865 ms/op
                 getUser·p1.00:   18.252 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 319676
  mean =      3.002 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 891 
    [ 1.250,  2.500) = 28834 
    [ 2.500,  3.750) = 272400 
    [ 3.750,  5.000) = 15712 
    [ 5.000,  6.250) = 1212 
    [ 6.250,  7.500) = 293 
    [ 7.500,  8.750) = 74 
    [ 8.750, 10.000) = 37 
    [10.000, 11.250) = 24 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 42 
    [13.750, 15.000) = 19 
    [15.000, 16.250) = 58 
    [16.250, 17.500) = 24 
    [17.500, 18.750) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.645 ms/op
     p(50.0000) =      2.974 ms/op
     p(90.0000) =      3.531 ms/op
     p(95.0000) =      3.785 ms/op
     p(99.0000) =      4.686 ms/op
     p(99.9000) =      7.700 ms/op
     p(99.9900) =     18.385 ms/op
     p(99.9990) =     19.615 ms/op
     p(99.9999) =     19.726 ms/op
    p(100.0000) =     19.726 ms/op


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
# Warmup Iteration   1: 4.699 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 4.062 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.936 ±(99.9%) 0.010 ms/op
Iteration   1: 3.951 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.126 ms/op
                 listUser·p0.50:   3.797 ms/op
                 listUser·p0.90:   4.907 ms/op
                 listUser·p0.95:   5.792 ms/op
                 listUser·p0.99:   6.767 ms/op
                 listUser·p0.999:  13.976 ms/op
                 listUser·p0.9999: 18.737 ms/op
                 listUser·p1.00:   20.873 ms/op

Iteration   2: 3.899 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.421 ms/op
                 listUser·p0.50:   3.772 ms/op
                 listUser·p0.90:   4.678 ms/op
                 listUser·p0.95:   5.693 ms/op
                 listUser·p0.99:   6.791 ms/op
                 listUser·p0.999:  14.696 ms/op
                 listUser·p0.9999: 18.619 ms/op
                 listUser·p1.00:   20.185 ms/op

Iteration   3: 3.843 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.634 ms/op
                 listUser·p0.50:   3.686 ms/op
                 listUser·p0.90:   4.686 ms/op
                 listUser·p0.95:   5.415 ms/op
                 listUser·p0.99:   6.865 ms/op
                 listUser·p0.999:  16.150 ms/op
                 listUser·p0.9999: 26.138 ms/op
                 listUser·p1.00:   27.492 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 246290
  mean =      3.897 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3130 
    [ 2.500,  5.000) = 223079 
    [ 5.000,  7.500) = 18925 
    [ 7.500, 10.000) = 638 
    [10.000, 12.500) = 94 
    [12.500, 15.000) = 174 
    [15.000, 17.500) = 130 
    [17.500, 20.000) = 82 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 18 

  Percentiles, ms/op:
      p(0.0000) =      0.634 ms/op
     p(50.0000) =      3.756 ms/op
     p(90.0000) =      4.768 ms/op
     p(95.0000) =      5.652 ms/op
     p(99.0000) =      6.808 ms/op
     p(99.9000) =     15.047 ms/op
     p(99.9900) =     23.724 ms/op
     p(99.9990) =     27.429 ms/op
     p(99.9999) =     27.492 ms/op
    p(100.0000) =     27.492 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.640 ± 4.410  ops/ms
ClientGrpc.existUser                       thrpt       3  11.401 ± 1.655  ops/ms
ClientGrpc.getUser                         thrpt       3  10.604 ± 2.373  ops/ms
ClientGrpc.listUser                        thrpt       3   8.171 ± 0.453  ops/ms
ClientGrpc.createUser                       avgt       3   3.043 ± 0.292   ms/op
ClientGrpc.existUser                        avgt       3   2.898 ± 0.223   ms/op
ClientGrpc.getUser                          avgt       3   2.988 ± 0.253   ms/op
ClientGrpc.listUser                         avgt       3   3.917 ± 0.594   ms/op
ClientGrpc.createUser                     sample  313179   3.065 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.448           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.031           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.584           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.764           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.522           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.136           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          16.704           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          30.769           ms/op
ClientGrpc.existUser                      sample  334496   2.868 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.643           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.863           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.244           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.413           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.129           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.451           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.421           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.463           ms/op
ClientGrpc.getUser                        sample  319676   3.002 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.645           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.974           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.531           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.785           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.686           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.700           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.385           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.726           ms/op
ClientGrpc.listUser                       sample  246290   3.897 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.634           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.756           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.768           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.652           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.808           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.047           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.724           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.492           ms/op
