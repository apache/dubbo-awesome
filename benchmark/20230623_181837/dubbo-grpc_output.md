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
# Warmup Iteration   1: 3.115 ops/ms
# Warmup Iteration   2: 6.892 ops/ms
# Warmup Iteration   3: 8.175 ops/ms
Iteration   1: 8.643 ops/ms
Iteration   2: 8.767 ops/ms
Iteration   3: 8.670 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.693 ±(99.9%) 1.192 ops/ms [Average]
  (min, avg, max) = (8.643, 8.693, 8.767), stdev = 0.065
  CI (99.9%): [7.501, 9.886] (assumes normal distribution)


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
# Warmup Iteration   1: 5.932 ops/ms
# Warmup Iteration   2: 8.564 ops/ms
# Warmup Iteration   3: 9.131 ops/ms
Iteration   1: 9.201 ops/ms
Iteration   2: 9.193 ops/ms
Iteration   3: 9.159 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.185 ±(99.9%) 0.404 ops/ms [Average]
  (min, avg, max) = (9.159, 9.185, 9.201), stdev = 0.022
  CI (99.9%): [8.780, 9.589] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 5.373 ops/ms
# Warmup Iteration   2: 8.265 ops/ms
# Warmup Iteration   3: 8.525 ops/ms
Iteration   1: 8.853 ops/ms
Iteration   2: 8.823 ops/ms
Iteration   3: 8.636 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.771 ±(99.9%) 2.147 ops/ms [Average]
  (min, avg, max) = (8.636, 8.771, 8.853), stdev = 0.118
  CI (99.9%): [6.623, 10.918] (assumes normal distribution)


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
# Warmup Iteration   1: 4.659 ops/ms
# Warmup Iteration   2: 6.092 ops/ms
# Warmup Iteration   3: 6.657 ops/ms
Iteration   1: 6.829 ops/ms
Iteration   2: 6.847 ops/ms
Iteration   3: 6.654 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.777 ±(99.9%) 1.939 ops/ms [Average]
  (min, avg, max) = (6.654, 6.777, 6.847), stdev = 0.106
  CI (99.9%): [4.837, 8.716] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 5.637 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.996 ±(99.9%) 0.031 ms/op
# Warmup Iteration   3: 3.990 ±(99.9%) 0.015 ms/op
Iteration   1: 3.861 ±(99.9%) 0.005 ms/op
Iteration   2: 3.853 ±(99.9%) 0.005 ms/op
Iteration   3: 3.799 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.838 ±(99.9%) 0.612 ms/op [Average]
  (min, avg, max) = (3.799, 3.838, 3.861), stdev = 0.034
  CI (99.9%): [3.225, 4.450] (assumes normal distribution)


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
# Warmup Iteration   1: 5.103 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 3.730 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.553 ±(99.9%) 0.005 ms/op
Iteration   1: 3.602 ±(99.9%) 0.003 ms/op
Iteration   2: 3.596 ±(99.9%) 0.003 ms/op
Iteration   3: 3.659 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.619 ±(99.9%) 0.636 ms/op [Average]
  (min, avg, max) = (3.596, 3.619, 3.659), stdev = 0.035
  CI (99.9%): [2.982, 4.255] (assumes normal distribution)


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
# Warmup Iteration   1: 5.193 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.008 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.788 ±(99.9%) 0.003 ms/op
Iteration   1: 3.728 ±(99.9%) 0.003 ms/op
Iteration   2: 3.719 ±(99.9%) 0.005 ms/op
Iteration   3: 3.714 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.721 ±(99.9%) 0.133 ms/op [Average]
  (min, avg, max) = (3.714, 3.721, 3.728), stdev = 0.007
  CI (99.9%): [3.588, 3.853] (assumes normal distribution)


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
# Warmup Iteration   1: 7.512 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 5.417 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.964 ±(99.9%) 0.010 ms/op
Iteration   1: 4.809 ±(99.9%) 0.013 ms/op
Iteration   2: 4.657 ±(99.9%) 0.024 ms/op
Iteration   3: 4.667 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.711 ±(99.9%) 1.546 ms/op [Average]
  (min, avg, max) = (4.657, 4.711, 4.809), stdev = 0.085
  CI (99.9%): [3.165, 6.257] (assumes normal distribution)


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
# Warmup Iteration   1: 4.943 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 4.038 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.734 ±(99.9%) 0.011 ms/op
Iteration   1: 3.687 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.061 ms/op
                 createUser·p0.50:   3.621 ms/op
                 createUser·p0.90:   4.260 ms/op
                 createUser·p0.95:   4.604 ms/op
                 createUser·p0.99:   6.029 ms/op
                 createUser·p0.999:  10.355 ms/op
                 createUser·p0.9999: 16.280 ms/op
                 createUser·p1.00:   16.417 ms/op

Iteration   2: 3.807 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.982 ms/op
                 createUser·p0.50:   3.736 ms/op
                 createUser·p0.90:   4.465 ms/op
                 createUser·p0.95:   4.760 ms/op
                 createUser·p0.99:   6.062 ms/op
                 createUser·p0.999:  10.797 ms/op
                 createUser·p0.9999: 18.062 ms/op
                 createUser·p1.00:   18.350 ms/op

Iteration   3: 3.661 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.793 ms/op
                 createUser·p0.50:   3.604 ms/op
                 createUser·p0.90:   4.227 ms/op
                 createUser·p0.95:   4.628 ms/op
                 createUser·p0.99:   6.152 ms/op
                 createUser·p0.999:  10.359 ms/op
                 createUser·p0.9999: 20.840 ms/op
                 createUser·p1.00:   21.496 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 258115
  mean =      3.717 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4881 
    [ 2.500,  5.000) = 245383 
    [ 5.000,  7.500) = 6875 
    [ 7.500, 10.000) = 652 
    [10.000, 12.500) = 152 
    [12.500, 15.000) = 5 
    [15.000, 17.500) = 76 
    [17.500, 20.000) = 72 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.793 ms/op
     p(50.0000) =      3.645 ms/op
     p(90.0000) =      4.350 ms/op
     p(95.0000) =      4.669 ms/op
     p(99.0000) =      6.078 ms/op
     p(99.9000) =     10.451 ms/op
     p(99.9900) =     19.726 ms/op
     p(99.9990) =     21.254 ms/op
     p(99.9999) =     21.496 ms/op
    p(100.0000) =     21.496 ms/op


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
# Warmup Iteration   1: 5.260 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.799 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.549 ±(99.9%) 0.008 ms/op
Iteration   1: 3.583 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.854 ms/op
                 existUser·p0.50:   3.535 ms/op
                 existUser·p0.90:   4.399 ms/op
                 existUser·p0.95:   4.735 ms/op
                 existUser·p0.99:   5.988 ms/op
                 existUser·p0.999:  10.879 ms/op
                 existUser·p0.9999: 13.718 ms/op
                 existUser·p1.00:   14.123 ms/op

Iteration   2: 3.490 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.708 ms/op
                 existUser·p0.50:   3.473 ms/op
                 existUser·p0.90:   4.100 ms/op
                 existUser·p0.95:   4.588 ms/op
                 existUser·p0.99:   6.054 ms/op
                 existUser·p0.999:  13.198 ms/op
                 existUser·p0.9999: 17.743 ms/op
                 existUser·p1.00:   19.562 ms/op

Iteration   3: 3.498 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.899 ms/op
                 existUser·p0.50:   3.461 ms/op
                 existUser·p0.90:   4.168 ms/op
                 existUser·p0.95:   4.547 ms/op
                 existUser·p0.99:   5.726 ms/op
                 existUser·p0.999:  11.354 ms/op
                 existUser·p0.9999: 19.562 ms/op
                 existUser·p1.00:   20.349 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 272562
  mean =      3.523 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16642 
    [ 2.500,  5.000) = 247828 
    [ 5.000,  7.500) = 7237 
    [ 7.500, 10.000) = 509 
    [10.000, 12.500) = 150 
    [12.500, 15.000) = 100 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 71 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.708 ms/op
     p(50.0000) =      3.486 ms/op
     p(90.0000) =      4.227 ms/op
     p(95.0000) =      4.637 ms/op
     p(99.0000) =      5.931 ms/op
     p(99.9000) =     11.108 ms/op
     p(99.9900) =     19.111 ms/op
     p(99.9990) =     19.595 ms/op
     p(99.9999) =     20.349 ms/op
    p(100.0000) =     20.349 ms/op


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
# Warmup Iteration   1: 5.630 ±(99.9%) 0.061 ms/op
# Warmup Iteration   2: 3.935 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.752 ±(99.9%) 0.010 ms/op
Iteration   1: 3.761 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.922 ms/op
                 getUser·p0.50:   3.690 ms/op
                 getUser·p0.90:   4.530 ms/op
                 getUser·p0.95:   4.882 ms/op
                 getUser·p0.99:   6.562 ms/op
                 getUser·p0.999:  13.598 ms/op
                 getUser·p0.9999: 16.490 ms/op
                 getUser·p1.00:   16.843 ms/op

Iteration   2: 3.642 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.914 ms/op
                 getUser·p0.50:   3.621 ms/op
                 getUser·p0.90:   4.375 ms/op
                 getUser·p0.95:   4.727 ms/op
                 getUser·p0.99:   5.841 ms/op
                 getUser·p0.999:  9.257 ms/op
                 getUser·p0.9999: 16.493 ms/op
                 getUser·p1.00:   16.974 ms/op

Iteration   3: 3.649 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.015 ms/op
                 getUser·p0.50:   3.604 ms/op
                 getUser·p0.90:   4.243 ms/op
                 getUser·p0.95:   4.628 ms/op
                 getUser·p0.99:   5.988 ms/op
                 getUser·p0.999:  9.355 ms/op
                 getUser·p0.9999: 23.863 ms/op
                 getUser·p1.00:   24.183 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 260434
  mean =      3.683 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10768 
    [ 2.500,  5.000) = 241051 
    [ 5.000,  7.500) = 7594 
    [ 7.500, 10.000) = 730 
    [10.000, 12.500) = 71 
    [12.500, 15.000) = 74 
    [15.000, 17.500) = 82 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 45 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.914 ms/op
     p(50.0000) =      3.637 ms/op
     p(90.0000) =      4.391 ms/op
     p(95.0000) =      4.751 ms/op
     p(99.0000) =      6.095 ms/op
     p(99.9000) =     10.996 ms/op
     p(99.9900) =     22.184 ms/op
     p(99.9990) =     24.130 ms/op
     p(99.9999) =     24.183 ms/op
    p(100.0000) =     24.183 ms/op


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
# Warmup Iteration   1: 7.050 ±(99.9%) 0.081 ms/op
# Warmup Iteration   2: 5.191 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.834 ±(99.9%) 0.016 ms/op
Iteration   1: 4.688 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.352 ms/op
                 listUser·p0.50:   4.481 ms/op
                 listUser·p0.90:   5.923 ms/op
                 listUser·p0.95:   6.873 ms/op
                 listUser·p0.99:   8.618 ms/op
                 listUser·p0.999:  15.905 ms/op
                 listUser·p0.9999: 18.930 ms/op
                 listUser·p1.00:   19.431 ms/op

Iteration   2: 4.674 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.438 ms/op
                 listUser·p0.50:   4.465 ms/op
                 listUser·p0.90:   5.956 ms/op
                 listUser·p0.95:   6.750 ms/op
                 listUser·p0.99:   8.536 ms/op
                 listUser·p0.999:  17.943 ms/op
                 listUser·p0.9999: 27.072 ms/op
                 listUser·p1.00:   27.296 ms/op

Iteration   3: 4.878 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.323 ms/op
                 listUser·p0.50:   4.620 ms/op
                 listUser·p0.90:   6.095 ms/op
                 listUser·p0.95:   6.988 ms/op
                 listUser·p0.99:   8.836 ms/op
                 listUser·p0.999:  22.507 ms/op
                 listUser·p0.9999: 34.042 ms/op
                 listUser·p1.00:   34.406 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 202215
  mean =      4.745 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 375 
    [ 2.500,  5.000) = 152358 
    [ 5.000,  7.500) = 43721 
    [ 7.500, 10.000) = 4824 
    [10.000, 12.500) = 450 
    [12.500, 15.000) = 143 
    [15.000, 17.500) = 154 
    [17.500, 20.000) = 84 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 23 
    [27.500, 30.000) = 18 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 14 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.323 ms/op
     p(50.0000) =      4.522 ms/op
     p(90.0000) =      6.005 ms/op
     p(95.0000) =      6.865 ms/op
     p(99.0000) =      8.684 ms/op
     p(99.9000) =     17.098 ms/op
     p(99.9900) =     32.171 ms/op
     p(99.9990) =     34.338 ms/op
     p(99.9999) =     34.406 ms/op
    p(100.0000) =     34.406 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.693 ± 1.192  ops/ms
ClientGrpc.existUser                       thrpt       3   9.185 ± 0.404  ops/ms
ClientGrpc.getUser                         thrpt       3   8.771 ± 2.147  ops/ms
ClientGrpc.listUser                        thrpt       3   6.777 ± 1.939  ops/ms
ClientGrpc.createUser                       avgt       3   3.838 ± 0.612   ms/op
ClientGrpc.existUser                        avgt       3   3.619 ± 0.636   ms/op
ClientGrpc.getUser                          avgt       3   3.721 ± 0.133   ms/op
ClientGrpc.listUser                         avgt       3   4.711 ± 1.546   ms/op
ClientGrpc.createUser                     sample  258115   3.717 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.793           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.645           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.350           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.669           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.078           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.451           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.726           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.496           ms/op
ClientGrpc.existUser                      sample  272562   3.523 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.708           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.486           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.227           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.637           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.931           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.108           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.111           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.349           ms/op
ClientGrpc.getUser                        sample  260434   3.683 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.914           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.637           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.391           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.751           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.095           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.996           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          22.184           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          24.183           ms/op
ClientGrpc.listUser                       sample  202215   4.745 ± 0.009   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.323           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.522           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.005           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.865           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.684           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.098           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          32.171           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          34.406           ms/op
