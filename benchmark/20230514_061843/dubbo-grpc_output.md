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
# Warmup Iteration   1: 1.991 ops/ms
# Warmup Iteration   2: 4.709 ops/ms
# Warmup Iteration   3: 6.876 ops/ms
Iteration   1: 6.809 ops/ms
Iteration   2: 6.731 ops/ms
Iteration   3: 6.874 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  6.805 ±(99.9%) 1.305 ops/ms [Average]
  (min, avg, max) = (6.731, 6.805, 6.874), stdev = 0.072
  CI (99.9%): [5.500, 8.109] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 4.332 ops/ms
# Warmup Iteration   2: 6.730 ops/ms
# Warmup Iteration   3: 7.108 ops/ms
Iteration   1: 7.579 ops/ms
Iteration   2: 7.496 ops/ms
Iteration   3: 7.712 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.596 ±(99.9%) 1.985 ops/ms [Average]
  (min, avg, max) = (7.496, 7.596, 7.712), stdev = 0.109
  CI (99.9%): [5.610, 9.581] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 3.775 ops/ms
# Warmup Iteration   2: 6.353 ops/ms
# Warmup Iteration   3: 6.824 ops/ms
Iteration   1: 7.067 ops/ms
Iteration   2: 7.014 ops/ms
Iteration   3: 7.115 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.065 ±(99.9%) 0.917 ops/ms [Average]
  (min, avg, max) = (7.014, 7.065, 7.115), stdev = 0.050
  CI (99.9%): [6.148, 7.983] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.386 ops/ms
# Warmup Iteration   2: 4.603 ops/ms
# Warmup Iteration   3: 5.203 ops/ms
Iteration   1: 5.293 ops/ms
Iteration   2: 5.314 ops/ms
Iteration   3: 5.414 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.340 ±(99.9%) 1.174 ops/ms [Average]
  (min, avg, max) = (5.293, 5.340, 5.414), stdev = 0.064
  CI (99.9%): [4.166, 6.514] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 7.888 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 4.887 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.804 ±(99.9%) 0.014 ms/op
Iteration   1: 4.667 ±(99.9%) 0.003 ms/op
Iteration   2: 4.688 ±(99.9%) 0.003 ms/op
Iteration   3: 4.586 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.647 ±(99.9%) 0.981 ms/op [Average]
  (min, avg, max) = (4.586, 4.647, 4.688), stdev = 0.054
  CI (99.9%): [3.666, 5.629] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.946 ±(99.9%) 0.113 ms/op
# Warmup Iteration   2: 4.684 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.574 ±(99.9%) 0.004 ms/op
Iteration   1: 4.539 ±(99.9%) 0.003 ms/op
Iteration   2: 4.356 ±(99.9%) 0.002 ms/op
Iteration   3: 4.255 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.383 ±(99.9%) 2.617 ms/op [Average]
  (min, avg, max) = (4.255, 4.383, 4.539), stdev = 0.143
  CI (99.9%): [1.766, 7.001] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 7.061 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 4.959 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.618 ±(99.9%) 0.003 ms/op
Iteration   1: 4.651 ±(99.9%) 0.003 ms/op
Iteration   2: 4.609 ±(99.9%) 0.004 ms/op
Iteration   3: 4.922 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.727 ±(99.9%) 3.097 ms/op [Average]
  (min, avg, max) = (4.609, 4.727, 4.922), stdev = 0.170
  CI (99.9%): [1.630, 7.825] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 8.468 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 6.760 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 6.136 ±(99.9%) 0.016 ms/op
Iteration   1: 5.916 ±(99.9%) 0.010 ms/op
Iteration   2: 5.978 ±(99.9%) 0.016 ms/op
Iteration   3: 5.740 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.878 ±(99.9%) 2.254 ms/op [Average]
  (min, avg, max) = (5.740, 5.878, 5.978), stdev = 0.124
  CI (99.9%): [3.623, 8.132] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 7.240 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 5.184 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.638 ±(99.9%) 0.014 ms/op
Iteration   1: 4.677 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.419 ms/op
                 createUser·p0.50:   4.555 ms/op
                 createUser·p0.90:   5.718 ms/op
                 createUser·p0.95:   6.136 ms/op
                 createUser·p0.99:   7.819 ms/op
                 createUser·p0.999:  13.554 ms/op
                 createUser·p0.9999: 18.000 ms/op
                 createUser·p1.00:   18.383 ms/op

Iteration   2: 4.632 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.276 ms/op
                 createUser·p0.50:   4.538 ms/op
                 createUser·p0.90:   5.716 ms/op
                 createUser·p0.95:   6.103 ms/op
                 createUser·p0.99:   7.329 ms/op
                 createUser·p0.999:  9.798 ms/op
                 createUser·p0.9999: 17.216 ms/op
                 createUser·p1.00:   18.907 ms/op

Iteration   3: 4.632 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.100 ms/op
                 createUser·p0.50:   4.506 ms/op
                 createUser·p0.90:   5.603 ms/op
                 createUser·p0.95:   6.078 ms/op
                 createUser·p0.99:   8.164 ms/op
                 createUser·p0.999:  17.367 ms/op
                 createUser·p0.9999: 34.275 ms/op
                 createUser·p1.00:   35.652 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 206533
  mean =      4.647 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1622 
    [ 2.500,  5.000) = 147400 
    [ 5.000,  7.500) = 55180 
    [ 7.500, 10.000) = 1716 
    [10.000, 12.500) = 299 
    [12.500, 15.000) = 124 
    [15.000, 17.500) = 111 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 10 
    [32.500, 35.000) = 21 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.100 ms/op
     p(50.0000) =      4.530 ms/op
     p(90.0000) =      5.685 ms/op
     p(95.0000) =      6.103 ms/op
     p(99.0000) =      7.717 ms/op
     p(99.9000) =     14.507 ms/op
     p(99.9900) =     33.135 ms/op
     p(99.9990) =     34.275 ms/op
     p(99.9999) =     35.652 ms/op
    p(100.0000) =     35.652 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.369 ±(99.9%) 0.072 ms/op
# Warmup Iteration   2: 4.768 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.377 ±(99.9%) 0.011 ms/op
Iteration   1: 4.381 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.979 ms/op
                 existUser·p0.50:   4.276 ms/op
                 existUser·p0.90:   5.538 ms/op
                 existUser·p0.95:   6.070 ms/op
                 existUser·p0.99:   7.463 ms/op
                 existUser·p0.999:  14.057 ms/op
                 existUser·p0.9999: 19.039 ms/op
                 existUser·p1.00:   19.661 ms/op

Iteration   2: 4.207 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.981 ms/op
                 existUser·p0.50:   4.174 ms/op
                 existUser·p0.90:   4.964 ms/op
                 existUser·p0.95:   5.382 ms/op
                 existUser·p0.99:   6.840 ms/op
                 existUser·p0.999:  11.893 ms/op
                 existUser·p0.9999: 19.117 ms/op
                 existUser·p1.00:   19.792 ms/op

Iteration   3: 4.448 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.936 ms/op
                 existUser·p0.50:   4.334 ms/op
                 existUser·p0.90:   5.401 ms/op
                 existUser·p0.95:   5.906 ms/op
                 existUser·p0.99:   8.684 ms/op
                 existUser·p0.999:  13.500 ms/op
                 existUser·p0.9999: 22.184 ms/op
                 existUser·p1.00:   25.985 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 220961
  mean =      4.343 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6568 
    [ 2.500,  5.000) = 178961 
    [ 5.000,  7.500) = 33058 
    [ 7.500, 10.000) = 1679 
    [10.000, 12.500) = 423 
    [12.500, 15.000) = 143 
    [15.000, 17.500) = 55 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.936 ms/op
     p(50.0000) =      4.252 ms/op
     p(90.0000) =      5.317 ms/op
     p(95.0000) =      5.833 ms/op
     p(99.0000) =      7.635 ms/op
     p(99.9000) =     13.501 ms/op
     p(99.9900) =     21.496 ms/op
     p(99.9990) =     24.411 ms/op
     p(99.9999) =     25.985 ms/op
    p(100.0000) =     25.985 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 7.006 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 5.404 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.771 ±(99.9%) 0.016 ms/op
Iteration   1: 4.625 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.128 ms/op
                 getUser·p0.50:   4.530 ms/op
                 getUser·p0.90:   5.685 ms/op
                 getUser·p0.95:   6.128 ms/op
                 getUser·p0.99:   7.422 ms/op
                 getUser·p0.999:  11.696 ms/op
                 getUser·p0.9999: 26.616 ms/op
                 getUser·p1.00:   27.263 ms/op

Iteration   2: 4.624 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.145 ms/op
                 getUser·p0.50:   4.522 ms/op
                 getUser·p0.90:   5.775 ms/op
                 getUser·p0.95:   6.267 ms/op
                 getUser·p0.99:   7.619 ms/op
                 getUser·p0.999:  11.037 ms/op
                 getUser·p0.9999: 27.563 ms/op
                 getUser·p1.00:   28.180 ms/op

Iteration   3: 4.626 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   0.951 ms/op
                 getUser·p0.50:   4.530 ms/op
                 getUser·p0.90:   5.612 ms/op
                 getUser·p0.95:   6.005 ms/op
                 getUser·p0.99:   7.266 ms/op
                 getUser·p0.999:  11.627 ms/op
                 getUser·p0.9999: 29.349 ms/op
                 getUser·p1.00:   30.802 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 207471
  mean =      4.625 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3110 
    [ 2.500,  5.000) = 147009 
    [ 5.000,  7.500) = 55372 
    [ 7.500, 10.000) = 1553 
    [10.000, 12.500) = 256 
    [12.500, 15.000) = 42 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 52 
    [27.500, 30.000) = 37 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.951 ms/op
     p(50.0000) =      4.530 ms/op
     p(90.0000) =      5.685 ms/op
     p(95.0000) =      6.136 ms/op
     p(99.0000) =      7.447 ms/op
     p(99.9000) =     11.387 ms/op
     p(99.9900) =     28.459 ms/op
     p(99.9990) =     30.465 ms/op
     p(99.9999) =     30.802 ms/op
    p(100.0000) =     30.802 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 8.456 ±(99.9%) 0.112 ms/op
# Warmup Iteration   2: 6.727 ±(99.9%) 0.033 ms/op
# Warmup Iteration   3: 6.021 ±(99.9%) 0.021 ms/op
Iteration   1: 5.810 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   2.003 ms/op
                 listUser·p0.50:   5.562 ms/op
                 listUser·p0.90:   7.496 ms/op
                 listUser·p0.95:   8.503 ms/op
                 listUser·p0.99:   10.846 ms/op
                 listUser·p0.999:  16.062 ms/op
                 listUser·p0.9999: 20.266 ms/op
                 listUser·p1.00:   21.332 ms/op

Iteration   2: 5.750 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.315 ms/op
                 listUser·p0.50:   5.513 ms/op
                 listUser·p0.90:   7.561 ms/op
                 listUser·p0.95:   8.536 ms/op
                 listUser·p0.99:   10.830 ms/op
                 listUser·p0.999:  19.202 ms/op
                 listUser·p0.9999: 22.635 ms/op
                 listUser·p1.00:   25.559 ms/op

Iteration   3: 6.078 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.806 ms/op
                 listUser·p0.50:   5.784 ms/op
                 listUser·p0.90:   7.938 ms/op
                 listUser·p0.95:   9.028 ms/op
                 listUser·p0.99:   10.928 ms/op
                 listUser·p0.999:  20.290 ms/op
                 listUser·p0.9999: 27.286 ms/op
                 listUser·p1.00:   28.082 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 163258
  mean =      5.876 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 58 
    [ 2.500,  5.000) = 41814 
    [ 5.000,  7.500) = 103047 
    [ 7.500, 10.000) = 15202 
    [10.000, 12.500) = 2542 
    [12.500, 15.000) = 336 
    [15.000, 17.500) = 74 
    [17.500, 20.000) = 84 
    [20.000, 22.500) = 54 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 25 

  Percentiles, ms/op:
      p(0.0000) =      1.315 ms/op
     p(50.0000) =      5.620 ms/op
     p(90.0000) =      7.684 ms/op
     p(95.0000) =      8.700 ms/op
     p(99.0000) =     10.879 ms/op
     p(99.9000) =     18.538 ms/op
     p(99.9900) =     25.679 ms/op
     p(99.9990) =     27.751 ms/op
     p(99.9999) =     28.082 ms/op
    p(100.0000) =     28.082 ms/op


# Run complete. Total time: 00:13:16

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   6.805 ± 1.305  ops/ms
ClientGrpc.existUser                       thrpt       3   7.596 ± 1.985  ops/ms
ClientGrpc.getUser                         thrpt       3   7.065 ± 0.917  ops/ms
ClientGrpc.listUser                        thrpt       3   5.340 ± 1.174  ops/ms
ClientGrpc.createUser                       avgt       3   4.647 ± 0.981   ms/op
ClientGrpc.existUser                        avgt       3   4.383 ± 2.617   ms/op
ClientGrpc.getUser                          avgt       3   4.727 ± 3.097   ms/op
ClientGrpc.listUser                         avgt       3   5.878 ± 2.254   ms/op
ClientGrpc.createUser                     sample  206533   4.647 ± 0.008   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           1.100           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.530           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.685           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           6.103           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.717           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          14.507           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          33.135           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          35.652           ms/op
ClientGrpc.existUser                      sample  220961   4.343 ± 0.007   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.936           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.252           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.317           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.833           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.635           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          13.501           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          21.496           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          25.985           ms/op
ClientGrpc.getUser                        sample  207471   4.625 ± 0.008   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.951           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.530           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.685           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.136           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.447           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.387           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          28.459           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          30.802           ms/op
ClientGrpc.listUser                       sample  163258   5.876 ± 0.012   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.315           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.620           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.684           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.700           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.879           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.538           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.679           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          28.082           ms/op
