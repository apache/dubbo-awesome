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
# Warmup Iteration   1: 2.929 ops/ms
# Warmup Iteration   2: 6.163 ops/ms
# Warmup Iteration   3: 7.892 ops/ms
Iteration   1: 8.118 ops/ms
Iteration   2: 8.487 ops/ms
Iteration   3: 8.844 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.483 ±(99.9%) 6.620 ops/ms [Average]
  (min, avg, max) = (8.118, 8.483, 8.844), stdev = 0.363
  CI (99.9%): [1.863, 15.103] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 5.659 ops/ms
# Warmup Iteration   2: 8.252 ops/ms
# Warmup Iteration   3: 8.877 ops/ms
Iteration   1: 8.808 ops/ms
Iteration   2: 8.987 ops/ms
Iteration   3: 9.031 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.942 ±(99.9%) 2.156 ops/ms [Average]
  (min, avg, max) = (8.808, 8.942, 9.031), stdev = 0.118
  CI (99.9%): [6.786, 11.099] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 6.072 ops/ms
# Warmup Iteration   2: 7.900 ops/ms
# Warmup Iteration   3: 8.380 ops/ms
Iteration   1: 8.534 ops/ms
Iteration   2: 8.670 ops/ms
Iteration   3: 8.533 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.579 ±(99.9%) 1.443 ops/ms [Average]
  (min, avg, max) = (8.533, 8.579, 8.670), stdev = 0.079
  CI (99.9%): [7.136, 10.022] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 4.914 ops/ms
# Warmup Iteration   2: 6.230 ops/ms
# Warmup Iteration   3: 6.667 ops/ms
Iteration   1: 6.642 ops/ms
Iteration   2: 6.699 ops/ms
Iteration   3: 6.819 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.720 ±(99.9%) 1.649 ops/ms [Average]
  (min, avg, max) = (6.642, 6.720, 6.819), stdev = 0.090
  CI (99.9%): [5.072, 8.369] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 5.173 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.959 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.811 ±(99.9%) 0.013 ms/op
Iteration   1: 3.663 ±(99.9%) 0.004 ms/op
Iteration   2: 3.619 ±(99.9%) 0.003 ms/op
Iteration   3: 3.650 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.644 ±(99.9%) 0.414 ms/op [Average]
  (min, avg, max) = (3.619, 3.644, 3.663), stdev = 0.023
  CI (99.9%): [3.230, 4.058] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 5.127 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.793 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.581 ±(99.9%) 0.002 ms/op
Iteration   1: 3.521 ±(99.9%) 0.003 ms/op
Iteration   2: 3.452 ±(99.9%) 0.003 ms/op
Iteration   3: 3.527 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.500 ±(99.9%) 0.761 ms/op [Average]
  (min, avg, max) = (3.452, 3.500, 3.527), stdev = 0.042
  CI (99.9%): [2.739, 4.261] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 5.106 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.951 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.718 ±(99.9%) 0.003 ms/op
Iteration   1: 3.664 ±(99.9%) 0.005 ms/op
Iteration   2: 3.613 ±(99.9%) 0.003 ms/op
Iteration   3: 3.660 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.646 ±(99.9%) 0.514 ms/op [Average]
  (min, avg, max) = (3.613, 3.646, 3.664), stdev = 0.028
  CI (99.9%): [3.131, 4.160] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 5.716 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 5.186 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.888 ±(99.9%) 0.014 ms/op
Iteration   1: 4.674 ±(99.9%) 0.014 ms/op
Iteration   2: 4.800 ±(99.9%) 0.014 ms/op
Iteration   3: 4.650 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.708 ±(99.9%) 1.478 ms/op [Average]
  (min, avg, max) = (4.650, 4.708, 4.800), stdev = 0.081
  CI (99.9%): [3.230, 6.186] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 5.604 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 3.986 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.791 ±(99.9%) 0.010 ms/op
Iteration   1: 3.721 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.041 ms/op
                 createUser·p0.50:   3.658 ms/op
                 createUser·p0.90:   4.432 ms/op
                 createUser·p0.95:   4.784 ms/op
                 createUser·p0.99:   6.172 ms/op
                 createUser·p0.999:  10.654 ms/op
                 createUser·p0.9999: 19.510 ms/op
                 createUser·p1.00:   19.759 ms/op

Iteration   2: 3.693 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.952 ms/op
                 createUser·p0.50:   3.645 ms/op
                 createUser·p0.90:   4.415 ms/op
                 createUser·p0.95:   4.735 ms/op
                 createUser·p0.99:   5.702 ms/op
                 createUser·p0.999:  8.837 ms/op
                 createUser·p0.9999: 20.644 ms/op
                 createUser·p1.00:   21.266 ms/op

Iteration   3: 3.716 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.217 ms/op
                 createUser·p0.50:   3.633 ms/op
                 createUser·p0.90:   4.260 ms/op
                 createUser·p0.95:   4.620 ms/op
                 createUser·p0.99:   5.530 ms/op
                 createUser·p0.999:  11.794 ms/op
                 createUser·p0.9999: 24.458 ms/op
                 createUser·p1.00:   24.871 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 258634
  mean =      3.710 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5855 
    [ 2.500,  5.000) = 245609 
    [ 5.000,  7.500) = 6245 
    [ 7.500, 10.000) = 636 
    [10.000, 12.500) = 76 
    [12.500, 15.000) = 30 
    [15.000, 17.500) = 23 
    [17.500, 20.000) = 73 
    [20.000, 22.500) = 51 
    [22.500, 25.000) = 36 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.952 ms/op
     p(50.0000) =      3.645 ms/op
     p(90.0000) =      4.375 ms/op
     p(95.0000) =      4.719 ms/op
     p(99.0000) =      5.825 ms/op
     p(99.9000) =     11.016 ms/op
     p(99.9900) =     23.101 ms/op
     p(99.9990) =     24.657 ms/op
     p(99.9999) =     24.871 ms/op
    p(100.0000) =     24.871 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 4.916 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.751 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.477 ±(99.9%) 0.009 ms/op
Iteration   1: 3.580 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.820 ms/op
                 existUser·p0.50:   3.514 ms/op
                 existUser·p0.90:   4.301 ms/op
                 existUser·p0.95:   4.571 ms/op
                 existUser·p0.99:   5.874 ms/op
                 existUser·p0.999:  8.962 ms/op
                 existUser·p0.9999: 16.814 ms/op
                 existUser·p1.00:   17.138 ms/op

Iteration   2: 3.513 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.874 ms/op
                 existUser·p0.50:   3.461 ms/op
                 existUser·p0.90:   4.039 ms/op
                 existUser·p0.95:   4.358 ms/op
                 existUser·p0.99:   5.710 ms/op
                 existUser·p0.999:  12.321 ms/op
                 existUser·p0.9999: 18.772 ms/op
                 existUser·p1.00:   18.973 ms/op

Iteration   3: 3.524 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.771 ms/op
                 existUser·p0.50:   3.465 ms/op
                 existUser·p0.90:   4.166 ms/op
                 existUser·p0.95:   4.571 ms/op
                 existUser·p0.99:   5.849 ms/op
                 existUser·p0.999:  11.028 ms/op
                 existUser·p0.9999: 20.543 ms/op
                 existUser·p1.00:   21.201 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 271297
  mean =      3.539 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9502 
    [ 2.500,  5.000) = 255134 
    [ 5.000,  7.500) = 5715 
    [ 7.500, 10.000) = 624 
    [10.000, 12.500) = 156 
    [12.500, 15.000) = 38 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 79 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.771 ms/op
     p(50.0000) =      3.482 ms/op
     p(90.0000) =      4.178 ms/op
     p(95.0000) =      4.522 ms/op
     p(99.0000) =      5.816 ms/op
     p(99.9000) =     10.617 ms/op
     p(99.9900) =     18.968 ms/op
     p(99.9990) =     20.874 ms/op
     p(99.9999) =     21.201 ms/op
    p(100.0000) =     21.201 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.386 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 4.026 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.857 ±(99.9%) 0.010 ms/op
Iteration   1: 3.683 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.771 ms/op
                 getUser·p0.50:   3.633 ms/op
                 getUser·p0.90:   4.473 ms/op
                 getUser·p0.95:   4.850 ms/op
                 getUser·p0.99:   6.119 ms/op
                 getUser·p0.999:  13.131 ms/op
                 getUser·p0.9999: 15.930 ms/op
                 getUser·p1.00:   17.072 ms/op

Iteration   2: 3.676 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.935 ms/op
                 getUser·p0.50:   3.633 ms/op
                 getUser·p0.90:   4.489 ms/op
                 getUser·p0.95:   4.858 ms/op
                 getUser·p0.99:   5.947 ms/op
                 getUser·p0.999:  8.959 ms/op
                 getUser·p0.9999: 17.494 ms/op
                 getUser·p1.00:   18.252 ms/op

Iteration   3: 3.731 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.991 ms/op
                 getUser·p0.50:   3.650 ms/op
                 getUser·p0.90:   4.415 ms/op
                 getUser·p0.95:   4.768 ms/op
                 getUser·p0.99:   6.095 ms/op
                 getUser·p0.999:  10.442 ms/op
                 getUser·p0.9999: 20.606 ms/op
                 getUser·p1.00:   21.103 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 259646
  mean =      3.697 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10371 
    [ 2.500,  5.000) = 239559 
    [ 5.000,  7.500) = 8781 
    [ 7.500, 10.000) = 608 
    [10.000, 12.500) = 126 
    [12.500, 15.000) = 55 
    [15.000, 17.500) = 94 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.771 ms/op
     p(50.0000) =      3.641 ms/op
     p(90.0000) =      4.456 ms/op
     p(95.0000) =      4.833 ms/op
     p(99.0000) =      6.046 ms/op
     p(99.9000) =     10.977 ms/op
     p(99.9900) =     19.435 ms/op
     p(99.9990) =     20.978 ms/op
     p(99.9999) =     21.103 ms/op
    p(100.0000) =     21.103 ms/op


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
# Warmup Iteration   1: 6.350 ±(99.9%) 0.069 ms/op
# Warmup Iteration   2: 5.091 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.690 ±(99.9%) 0.015 ms/op
Iteration   1: 4.821 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.657 ms/op
                 listUser·p0.50:   4.612 ms/op
                 listUser·p0.90:   5.988 ms/op
                 listUser·p0.95:   7.037 ms/op
                 listUser·p0.99:   8.978 ms/op
                 listUser·p0.999:  17.212 ms/op
                 listUser·p0.9999: 23.453 ms/op
                 listUser·p1.00:   23.757 ms/op

Iteration   2: 4.734 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.677 ms/op
                 listUser·p0.50:   4.506 ms/op
                 listUser·p0.90:   5.972 ms/op
                 listUser·p0.95:   6.709 ms/op
                 listUser·p0.99:   8.421 ms/op
                 listUser·p0.999:  16.777 ms/op
                 listUser·p0.9999: 21.004 ms/op
                 listUser·p1.00:   23.069 ms/op

Iteration   3: 4.809 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.251 ms/op
                 listUser·p0.50:   4.596 ms/op
                 listUser·p0.90:   5.947 ms/op
                 listUser·p0.95:   6.947 ms/op
                 listUser·p0.99:   8.651 ms/op
                 listUser·p0.999:  20.414 ms/op
                 listUser·p0.9999: 46.924 ms/op
                 listUser·p1.00:   49.086 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 200507
  mean =      4.788 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 152799 
    [ 5.000, 10.000) = 46746 
    [10.000, 15.000) = 597 
    [15.000, 20.000) = 232 
    [20.000, 25.000) = 101 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 4 
    [35.000, 40.000) = 1 
    [40.000, 45.000) = 10 

  Percentiles, ms/op:
      p(0.0000) =      1.251 ms/op
     p(50.0000) =      4.571 ms/op
     p(90.0000) =      5.964 ms/op
     p(95.0000) =      6.906 ms/op
     p(99.0000) =      8.700 ms/op
     p(99.9000) =     18.350 ms/op
     p(99.9900) =     44.823 ms/op
     p(99.9990) =     48.685 ms/op
     p(99.9999) =     49.086 ms/op
    p(100.0000) =     49.086 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.483 ± 6.620  ops/ms
ClientGrpc.existUser                       thrpt       3   8.942 ± 2.156  ops/ms
ClientGrpc.getUser                         thrpt       3   8.579 ± 1.443  ops/ms
ClientGrpc.listUser                        thrpt       3   6.720 ± 1.649  ops/ms
ClientGrpc.createUser                       avgt       3   3.644 ± 0.414   ms/op
ClientGrpc.existUser                        avgt       3   3.500 ± 0.761   ms/op
ClientGrpc.getUser                          avgt       3   3.646 ± 0.514   ms/op
ClientGrpc.listUser                         avgt       3   4.708 ± 1.478   ms/op
ClientGrpc.createUser                     sample  258634   3.710 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.952           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.645           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.375           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.719           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.825           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.016           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          23.101           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          24.871           ms/op
ClientGrpc.existUser                      sample  271297   3.539 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.771           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.482           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.178           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.522           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.816           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.617           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.968           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.201           ms/op
ClientGrpc.getUser                        sample  259646   3.697 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.771           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.641           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.456           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.833           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.046           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.977           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.435           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.103           ms/op
ClientGrpc.listUser                       sample  200507   4.788 ± 0.009   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.251           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.571           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.964           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.906           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.700           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.350           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          44.823           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          49.086           ms/op
