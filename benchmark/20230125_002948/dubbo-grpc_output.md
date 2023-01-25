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
# Warmup Iteration   1: 2.504 ops/ms
# Warmup Iteration   2: 5.878 ops/ms
# Warmup Iteration   3: 6.927 ops/ms
Iteration   1: 6.859 ops/ms
Iteration   2: 7.169 ops/ms
Iteration   3: 7.067 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.032 ±(99.9%) 2.880 ops/ms [Average]
  (min, avg, max) = (6.859, 7.032, 7.169), stdev = 0.158
  CI (99.9%): [4.151, 9.912] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.644 ops/ms
# Warmup Iteration   2: 6.760 ops/ms
# Warmup Iteration   3: 7.621 ops/ms
Iteration   1: 7.894 ops/ms
Iteration   2: 7.385 ops/ms
Iteration   3: 7.184 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.488 ±(99.9%) 6.676 ops/ms [Average]
  (min, avg, max) = (7.184, 7.488, 7.894), stdev = 0.366
  CI (99.9%): [0.812, 14.163] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 4.026 ops/ms
# Warmup Iteration   2: 6.951 ops/ms
# Warmup Iteration   3: 6.898 ops/ms
Iteration   1: 6.957 ops/ms
Iteration   2: 6.952 ops/ms
Iteration   3: 7.231 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.047 ±(99.9%) 2.917 ops/ms [Average]
  (min, avg, max) = (6.952, 7.047, 7.231), stdev = 0.160
  CI (99.9%): [4.130, 9.963] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 3.638 ops/ms
# Warmup Iteration   2: 5.003 ops/ms
# Warmup Iteration   3: 5.802 ops/ms
Iteration   1: 5.812 ops/ms
Iteration   2: 5.551 ops/ms
Iteration   3: 5.508 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.624 ±(99.9%) 2.996 ops/ms [Average]
  (min, avg, max) = (5.508, 5.624, 5.812), stdev = 0.164
  CI (99.9%): [2.628, 8.619] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 6.663 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.668 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.429 ±(99.9%) 0.007 ms/op
Iteration   1: 4.444 ±(99.9%) 0.004 ms/op
Iteration   2: 4.509 ±(99.9%) 0.004 ms/op
Iteration   3: 4.675 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.543 ±(99.9%) 2.171 ms/op [Average]
  (min, avg, max) = (4.444, 4.543, 4.675), stdev = 0.119
  CI (99.9%): [2.371, 6.714] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 6.213 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.407 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.220 ±(99.9%) 0.003 ms/op
Iteration   1: 4.200 ±(99.9%) 0.003 ms/op
Iteration   2: 4.159 ±(99.9%) 0.003 ms/op
Iteration   3: 4.199 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.186 ±(99.9%) 0.430 ms/op [Average]
  (min, avg, max) = (4.159, 4.186, 4.200), stdev = 0.024
  CI (99.9%): [3.756, 4.616] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 6.015 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.673 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.486 ±(99.9%) 0.005 ms/op
Iteration   1: 4.399 ±(99.9%) 0.005 ms/op
Iteration   2: 4.546 ±(99.9%) 0.004 ms/op
Iteration   3: 4.570 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.505 ±(99.9%) 1.688 ms/op [Average]
  (min, avg, max) = (4.399, 4.505, 4.570), stdev = 0.093
  CI (99.9%): [2.817, 6.193] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 8.490 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 6.693 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 5.973 ±(99.9%) 0.010 ms/op
Iteration   1: 5.852 ±(99.9%) 0.019 ms/op
Iteration   2: 5.609 ±(99.9%) 0.011 ms/op
Iteration   3: 5.721 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.728 ±(99.9%) 2.217 ms/op [Average]
  (min, avg, max) = (5.609, 5.728, 5.852), stdev = 0.122
  CI (99.9%): [3.510, 7.945] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 7.148 ±(99.9%) 0.085 ms/op
# Warmup Iteration   2: 4.907 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.665 ±(99.9%) 0.016 ms/op
Iteration   1: 4.543 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.026 ms/op
                 createUser·p0.50:   4.415 ms/op
                 createUser·p0.90:   5.849 ms/op
                 createUser·p0.95:   6.390 ms/op
                 createUser·p0.99:   8.151 ms/op
                 createUser·p0.999:  14.916 ms/op
                 createUser·p0.9999: 21.561 ms/op
                 createUser·p1.00:   22.151 ms/op

Iteration   2: 4.496 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.032 ms/op
                 createUser·p0.50:   4.399 ms/op
                 createUser·p0.90:   5.849 ms/op
                 createUser·p0.95:   6.349 ms/op
                 createUser·p0.99:   8.036 ms/op
                 createUser·p0.999:  10.715 ms/op
                 createUser·p0.9999: 19.679 ms/op
                 createUser·p1.00:   20.316 ms/op

Iteration   3: 4.380 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   0.826 ms/op
                 createUser·p0.50:   4.243 ms/op
                 createUser·p0.90:   5.751 ms/op
                 createUser·p0.95:   6.332 ms/op
                 createUser·p0.99:   8.094 ms/op
                 createUser·p0.999:  14.444 ms/op
                 createUser·p0.9999: 25.919 ms/op
                 createUser·p1.00:   26.771 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 214686
  mean =      4.472 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5346 
    [ 2.500,  5.000) = 150147 
    [ 5.000,  7.500) = 55746 
    [ 7.500, 10.000) = 2734 
    [10.000, 12.500) = 402 
    [12.500, 15.000) = 145 
    [15.000, 17.500) = 71 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 35 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.826 ms/op
     p(50.0000) =      4.350 ms/op
     p(90.0000) =      5.825 ms/op
     p(95.0000) =      6.357 ms/op
     p(99.0000) =      8.086 ms/op
     p(99.9000) =     14.128 ms/op
     p(99.9900) =     23.792 ms/op
     p(99.9990) =     26.556 ms/op
     p(99.9999) =     26.771 ms/op
    p(100.0000) =     26.771 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.485 ±(99.9%) 0.075 ms/op
# Warmup Iteration   2: 4.703 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.407 ±(99.9%) 0.013 ms/op
Iteration   1: 4.198 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   0.692 ms/op
                 existUser·p0.50:   4.149 ms/op
                 existUser·p0.90:   5.530 ms/op
                 existUser·p0.95:   5.956 ms/op
                 existUser·p0.99:   7.569 ms/op
                 existUser·p0.999:  10.617 ms/op
                 existUser·p0.9999: 25.702 ms/op
                 existUser·p1.00:   29.524 ms/op

Iteration   2: 4.199 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.004 ms/op
                 existUser·p0.50:   4.092 ms/op
                 existUser·p0.90:   5.464 ms/op
                 existUser·p0.95:   5.890 ms/op
                 existUser·p0.99:   7.160 ms/op
                 existUser·p0.999:  10.223 ms/op
                 existUser·p0.9999: 20.636 ms/op
                 existUser·p1.00:   21.103 ms/op

Iteration   3: 4.140 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   0.432 ms/op
                 existUser·p0.50:   4.067 ms/op
                 existUser·p0.90:   5.431 ms/op
                 existUser·p0.95:   5.898 ms/op
                 existUser·p0.99:   7.324 ms/op
                 existUser·p0.999:  14.575 ms/op
                 existUser·p0.9999: 21.833 ms/op
                 existUser·p1.00:   23.364 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 229726
  mean =      4.179 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12686 
    [ 2.500,  5.000) = 172228 
    [ 5.000,  7.500) = 42806 
    [ 7.500, 10.000) = 1707 
    [10.000, 12.500) = 152 
    [12.500, 15.000) = 13 
    [15.000, 17.500) = 6 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 73 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 19 

  Percentiles, ms/op:
      p(0.0000) =      0.432 ms/op
     p(50.0000) =      4.104 ms/op
     p(90.0000) =      5.480 ms/op
     p(95.0000) =      5.915 ms/op
     p(99.0000) =      7.348 ms/op
     p(99.9000) =     10.675 ms/op
     p(99.9900) =     24.840 ms/op
     p(99.9990) =     26.110 ms/op
     p(99.9999) =     29.524 ms/op
    p(100.0000) =     29.524 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 6.643 ±(99.9%) 0.084 ms/op
# Warmup Iteration   2: 4.955 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.688 ±(99.9%) 0.014 ms/op
Iteration   1: 4.674 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.073 ms/op
                 getUser·p0.50:   4.538 ms/op
                 getUser·p0.90:   5.898 ms/op
                 getUser·p0.95:   6.414 ms/op
                 getUser·p0.99:   8.109 ms/op
                 getUser·p0.999:  14.001 ms/op
                 getUser·p0.9999: 17.890 ms/op
                 getUser·p1.00:   23.298 ms/op

Iteration   2: 4.649 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   0.551 ms/op
                 getUser·p0.50:   4.497 ms/op
                 getUser·p0.90:   5.906 ms/op
                 getUser·p0.95:   6.357 ms/op
                 getUser·p0.99:   7.994 ms/op
                 getUser·p0.999:  13.602 ms/op
                 getUser·p0.9999: 23.342 ms/op
                 getUser·p1.00:   24.740 ms/op

Iteration   3: 4.669 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.018 ms/op
                 getUser·p0.50:   4.563 ms/op
                 getUser·p0.90:   5.964 ms/op
                 getUser·p0.95:   6.423 ms/op
                 getUser·p0.99:   7.864 ms/op
                 getUser·p0.999:  10.479 ms/op
                 getUser·p0.9999: 22.063 ms/op
                 getUser·p1.00:   22.577 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 205695
  mean =      4.664 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2506 
    [ 2.500,  5.000) = 136699 
    [ 5.000,  7.500) = 63401 
    [ 7.500, 10.000) = 2562 
    [10.000, 12.500) = 274 
    [12.500, 15.000) = 101 
    [15.000, 17.500) = 73 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 34 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.551 ms/op
     p(50.0000) =      4.530 ms/op
     p(90.0000) =      5.923 ms/op
     p(95.0000) =      6.398 ms/op
     p(99.0000) =      7.971 ms/op
     p(99.9000) =     13.150 ms/op
     p(99.9900) =     22.919 ms/op
     p(99.9990) =     24.392 ms/op
     p(99.9999) =     24.740 ms/op
    p(100.0000) =     24.740 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 8.569 ±(99.9%) 0.121 ms/op
# Warmup Iteration   2: 6.438 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 5.927 ±(99.9%) 0.022 ms/op
Iteration   1: 5.629 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.194 ms/op
                 listUser·p0.50:   5.333 ms/op
                 listUser·p0.90:   7.528 ms/op
                 listUser·p0.95:   8.405 ms/op
                 listUser·p0.99:   10.938 ms/op
                 listUser·p0.999:  19.368 ms/op
                 listUser·p0.9999: 22.358 ms/op
                 listUser·p1.00:   22.708 ms/op

Iteration   2: 5.784 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.309 ms/op
                 listUser·p0.50:   5.521 ms/op
                 listUser·p0.90:   7.537 ms/op
                 listUser·p0.95:   8.503 ms/op
                 listUser·p0.99:   10.699 ms/op
                 listUser·p0.999:  17.994 ms/op
                 listUser·p0.9999: 24.198 ms/op
                 listUser·p1.00:   24.707 ms/op

Iteration   3: 5.865 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   1.855 ms/op
                 listUser·p0.50:   5.497 ms/op
                 listUser·p0.90:   7.971 ms/op
                 listUser·p0.95:   8.995 ms/op
                 listUser·p0.99:   11.272 ms/op
                 listUser·p0.999:  20.904 ms/op
                 listUser·p0.9999: 27.609 ms/op
                 listUser·p1.00:   29.295 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 166782
  mean =      5.758 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 72 
    [ 2.500,  5.000) = 53255 
    [ 5.000,  7.500) = 94678 
    [ 7.500, 10.000) = 15596 
    [10.000, 12.500) = 2550 
    [12.500, 15.000) = 345 
    [15.000, 17.500) = 54 
    [17.500, 20.000) = 82 
    [20.000, 22.500) = 81 
    [22.500, 25.000) = 42 
    [25.000, 27.500) = 21 

  Percentiles, ms/op:
      p(0.0000) =      1.194 ms/op
     p(50.0000) =      5.456 ms/op
     p(90.0000) =      7.668 ms/op
     p(95.0000) =      8.634 ms/op
     p(99.0000) =     10.994 ms/op
     p(99.9000) =     19.366 ms/op
     p(99.9900) =     25.832 ms/op
     p(99.9990) =     28.463 ms/op
     p(99.9999) =     29.295 ms/op
    p(100.0000) =     29.295 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.032 ± 2.880  ops/ms
ClientGrpc.existUser                       thrpt       3   7.488 ± 6.676  ops/ms
ClientGrpc.getUser                         thrpt       3   7.047 ± 2.917  ops/ms
ClientGrpc.listUser                        thrpt       3   5.624 ± 2.996  ops/ms
ClientGrpc.createUser                       avgt       3   4.543 ± 2.171   ms/op
ClientGrpc.existUser                        avgt       3   4.186 ± 0.430   ms/op
ClientGrpc.getUser                          avgt       3   4.505 ± 1.688   ms/op
ClientGrpc.listUser                         avgt       3   5.728 ± 2.217   ms/op
ClientGrpc.createUser                     sample  214686   4.472 ± 0.009   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.826           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.350           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.825           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           6.357           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           8.086           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          14.128           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          23.792           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          26.771           ms/op
ClientGrpc.existUser                      sample  229726   4.179 ± 0.008   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.432           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.104           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.480           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.915           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.348           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.675           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          24.840           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          29.524           ms/op
ClientGrpc.getUser                        sample  205695   4.664 ± 0.008   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.551           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.530           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.923           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.398           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.971           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          13.150           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          22.919           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          24.740           ms/op
ClientGrpc.listUser                       sample  166782   5.758 ± 0.013   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.194           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.456           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.668           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.634           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.994           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          19.366           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.832           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          29.295           ms/op
