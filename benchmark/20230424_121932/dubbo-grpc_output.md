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
# Warmup Iteration   1: 3.276 ops/ms
# Warmup Iteration   2: 6.724 ops/ms
# Warmup Iteration   3: 8.437 ops/ms
Iteration   1: 8.589 ops/ms
Iteration   2: 8.678 ops/ms
Iteration   3: 8.888 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.718 ±(99.9%) 2.799 ops/ms [Average]
  (min, avg, max) = (8.589, 8.718, 8.888), stdev = 0.153
  CI (99.9%): [5.919, 11.517] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 6.246 ops/ms
# Warmup Iteration   2: 8.521 ops/ms
# Warmup Iteration   3: 8.908 ops/ms
Iteration   1: 9.002 ops/ms
Iteration   2: 9.259 ops/ms
Iteration   3: 9.345 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.202 ±(99.9%) 3.254 ops/ms [Average]
  (min, avg, max) = (9.002, 9.202, 9.345), stdev = 0.178
  CI (99.9%): [5.948, 12.456] (assumes normal distribution)


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
# Warmup Iteration   1: 5.585 ops/ms
# Warmup Iteration   2: 8.097 ops/ms
# Warmup Iteration   3: 8.520 ops/ms
Iteration   1: 8.755 ops/ms
Iteration   2: 8.738 ops/ms
Iteration   3: 9.017 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.837 ±(99.9%) 2.849 ops/ms [Average]
  (min, avg, max) = (8.738, 8.837, 9.017), stdev = 0.156
  CI (99.9%): [5.988, 11.686] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 4.646 ops/ms
# Warmup Iteration   2: 6.543 ops/ms
# Warmup Iteration   3: 6.727 ops/ms
Iteration   1: 6.862 ops/ms
Iteration   2: 6.860 ops/ms
Iteration   3: 6.964 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.895 ±(99.9%) 1.084 ops/ms [Average]
  (min, avg, max) = (6.860, 6.895, 6.964), stdev = 0.059
  CI (99.9%): [5.811, 7.979] (assumes normal distribution)


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
# Warmup Iteration   1: 5.114 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 4.133 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.860 ±(99.9%) 0.004 ms/op
Iteration   1: 3.741 ±(99.9%) 0.020 ms/op
Iteration   2: 3.630 ±(99.9%) 0.003 ms/op
Iteration   3: 3.634 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.668 ±(99.9%) 1.146 ms/op [Average]
  (min, avg, max) = (3.630, 3.668, 3.741), stdev = 0.063
  CI (99.9%): [2.522, 4.814] (assumes normal distribution)


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
# Warmup Iteration   1: 4.767 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.628 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.399 ±(99.9%) 0.003 ms/op
Iteration   1: 3.490 ±(99.9%) 0.003 ms/op
Iteration   2: 3.449 ±(99.9%) 0.003 ms/op
Iteration   3: 3.476 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.472 ±(99.9%) 0.380 ms/op [Average]
  (min, avg, max) = (3.449, 3.472, 3.490), stdev = 0.021
  CI (99.9%): [3.092, 3.852] (assumes normal distribution)


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
# Warmup Iteration   1: 5.437 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.795 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.680 ±(99.9%) 0.003 ms/op
Iteration   1: 3.807 ±(99.9%) 0.003 ms/op
Iteration   2: 3.713 ±(99.9%) 0.004 ms/op
Iteration   3: 3.662 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.727 ±(99.9%) 1.346 ms/op [Average]
  (min, avg, max) = (3.662, 3.727, 3.807), stdev = 0.074
  CI (99.9%): [2.382, 5.073] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 6.295 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 4.860 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.712 ±(99.9%) 0.016 ms/op
Iteration   1: 4.749 ±(99.9%) 0.010 ms/op
Iteration   2: 4.717 ±(99.9%) 0.008 ms/op
Iteration   3: 4.727 ±(99.9%) 0.027 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.731 ±(99.9%) 0.297 ms/op [Average]
  (min, avg, max) = (4.717, 4.731, 4.749), stdev = 0.016
  CI (99.9%): [4.434, 5.028] (assumes normal distribution)


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
# Warmup Iteration   1: 5.351 ±(99.9%) 0.064 ms/op
# Warmup Iteration   2: 4.077 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.790 ±(99.9%) 0.010 ms/op
Iteration   1: 3.691 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.786 ms/op
                 createUser·p0.50:   3.576 ms/op
                 createUser·p0.90:   4.465 ms/op
                 createUser·p0.95:   4.932 ms/op
                 createUser·p0.99:   6.488 ms/op
                 createUser·p0.999:  12.040 ms/op
                 createUser·p0.9999: 19.114 ms/op
                 createUser·p1.00:   22.577 ms/op

Iteration   2: 3.722 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.967 ms/op
                 createUser·p0.50:   3.613 ms/op
                 createUser·p0.90:   4.530 ms/op
                 createUser·p0.95:   4.948 ms/op
                 createUser·p0.99:   6.652 ms/op
                 createUser·p0.999:  10.098 ms/op
                 createUser·p0.9999: 20.409 ms/op
                 createUser·p1.00:   20.644 ms/op

Iteration   3: 3.666 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.902 ms/op
                 createUser·p0.50:   3.572 ms/op
                 createUser·p0.90:   4.489 ms/op
                 createUser·p0.95:   5.030 ms/op
                 createUser·p0.99:   6.988 ms/op
                 createUser·p0.999:  10.706 ms/op
                 createUser·p0.9999: 22.544 ms/op
                 createUser·p1.00:   25.035 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 259821
  mean =      3.693 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7936 
    [ 2.500,  5.000) = 239476 
    [ 5.000,  7.500) = 10947 
    [ 7.500, 10.000) = 1126 
    [10.000, 12.500) = 139 
    [12.500, 15.000) = 30 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 77 
    [20.000, 22.500) = 52 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.786 ms/op
     p(50.0000) =      3.588 ms/op
     p(90.0000) =      4.497 ms/op
     p(95.0000) =      4.964 ms/op
     p(99.0000) =      6.693 ms/op
     p(99.9000) =     10.666 ms/op
     p(99.9900) =     21.175 ms/op
     p(99.9990) =     22.787 ms/op
     p(99.9999) =     25.035 ms/op
    p(100.0000) =     25.035 ms/op


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
# Warmup Iteration   1: 4.892 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.721 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.519 ±(99.9%) 0.010 ms/op
Iteration   1: 3.456 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.581 ms/op
                 existUser·p0.50:   3.387 ms/op
                 existUser·p0.90:   4.137 ms/op
                 existUser·p0.95:   4.637 ms/op
                 existUser·p0.99:   6.211 ms/op
                 existUser·p0.999:  9.765 ms/op
                 existUser·p0.9999: 24.108 ms/op
                 existUser·p1.00:   24.445 ms/op

Iteration   2: 3.424 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.904 ms/op
                 existUser·p0.50:   3.359 ms/op
                 existUser·p0.90:   3.957 ms/op
                 existUser·p0.95:   4.407 ms/op
                 existUser·p0.99:   5.785 ms/op
                 existUser·p0.999:  8.536 ms/op
                 existUser·p0.9999: 17.553 ms/op
                 existUser·p1.00:   17.891 ms/op

Iteration   3: 3.462 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.793 ms/op
                 existUser·p0.50:   3.408 ms/op
                 existUser·p0.90:   4.174 ms/op
                 existUser·p0.95:   4.596 ms/op
                 existUser·p0.99:   6.193 ms/op
                 existUser·p0.999:  12.984 ms/op
                 existUser·p0.9999: 18.973 ms/op
                 existUser·p1.00:   20.021 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 278442
  mean =      3.447 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13835 
    [ 2.500,  5.000) = 256892 
    [ 5.000,  7.500) = 6488 
    [ 7.500, 10.000) = 931 
    [10.000, 12.500) = 110 
    [12.500, 15.000) = 39 
    [15.000, 17.500) = 73 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.581 ms/op
     p(50.0000) =      3.383 ms/op
     p(90.0000) =      4.100 ms/op
     p(95.0000) =      4.547 ms/op
     p(99.0000) =      6.029 ms/op
     p(99.9000) =     10.158 ms/op
     p(99.9900) =     23.664 ms/op
     p(99.9990) =     24.255 ms/op
     p(99.9999) =     24.445 ms/op
    p(100.0000) =     24.445 ms/op


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
# Warmup Iteration   1: 5.064 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 4.042 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.875 ±(99.9%) 0.011 ms/op
Iteration   1: 3.917 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.933 ms/op
                 getUser·p0.50:   3.760 ms/op
                 getUser·p0.90:   4.923 ms/op
                 getUser·p0.95:   5.480 ms/op
                 getUser·p0.99:   7.283 ms/op
                 getUser·p0.999:  11.392 ms/op
                 getUser·p0.9999: 25.455 ms/op
                 getUser·p1.00:   25.788 ms/op

Iteration   2: 3.790 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.020 ms/op
                 getUser·p0.50:   3.666 ms/op
                 getUser·p0.90:   4.628 ms/op
                 getUser·p0.95:   5.161 ms/op
                 getUser·p0.99:   7.458 ms/op
                 getUser·p0.999:  14.968 ms/op
                 getUser·p0.9999: 24.183 ms/op
                 getUser·p1.00:   28.148 ms/op

Iteration   3: 3.802 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.887 ms/op
                 getUser·p0.50:   3.678 ms/op
                 getUser·p0.90:   4.678 ms/op
                 getUser·p0.95:   5.128 ms/op
                 getUser·p0.99:   6.521 ms/op
                 getUser·p0.999:  11.672 ms/op
                 getUser·p0.9999: 27.577 ms/op
                 getUser·p1.00:   27.886 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 250187
  mean =      3.836 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8227 
    [ 2.500,  5.000) = 224404 
    [ 5.000,  7.500) = 15582 
    [ 7.500, 10.000) = 1392 
    [10.000, 12.500) = 342 
    [12.500, 15.000) = 60 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 103 
    [25.000, 27.500) = 43 

  Percentiles, ms/op:
      p(0.0000) =      0.887 ms/op
     p(50.0000) =      3.703 ms/op
     p(90.0000) =      4.743 ms/op
     p(95.0000) =      5.259 ms/op
     p(99.0000) =      7.111 ms/op
     p(99.9000) =     12.252 ms/op
     p(99.9900) =     27.065 ms/op
     p(99.9990) =     27.984 ms/op
     p(99.9999) =     28.148 ms/op
    p(100.0000) =     28.148 ms/op


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
# Warmup Iteration   1: 6.190 ±(99.9%) 0.065 ms/op
# Warmup Iteration   2: 5.189 ±(99.9%) 0.042 ms/op
# Warmup Iteration   3: 4.675 ±(99.9%) 0.014 ms/op
Iteration   1: 4.765 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.677 ms/op
                 listUser·p0.50:   4.506 ms/op
                 listUser·p0.90:   6.185 ms/op
                 listUser·p0.95:   7.021 ms/op
                 listUser·p0.99:   8.700 ms/op
                 listUser·p0.999:  17.199 ms/op
                 listUser·p0.9999: 25.008 ms/op
                 listUser·p1.00:   26.149 ms/op

Iteration   2: 4.537 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.354 ms/op
                 listUser·p0.50:   4.301 ms/op
                 listUser·p0.90:   5.939 ms/op
                 listUser·p0.95:   6.767 ms/op
                 listUser·p0.99:   8.782 ms/op
                 listUser·p0.999:  18.547 ms/op
                 listUser·p0.9999: 22.281 ms/op
                 listUser·p1.00:   22.970 ms/op

Iteration   3: 4.808 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.025 ms/op
                 listUser·p0.50:   4.530 ms/op
                 listUser·p0.90:   6.349 ms/op
                 listUser·p0.95:   7.283 ms/op
                 listUser·p0.99:   9.191 ms/op
                 listUser·p0.999:  19.358 ms/op
                 listUser·p0.9999: 27.405 ms/op
                 listUser·p1.00:   27.984 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 204418
  mean =      4.700 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 436 
    [ 2.500,  5.000) = 154685 
    [ 5.000,  7.500) = 42530 
    [ 7.500, 10.000) = 5776 
    [10.000, 12.500) = 565 
    [12.500, 15.000) = 70 
    [15.000, 17.500) = 79 
    [17.500, 20.000) = 143 
    [20.000, 22.500) = 52 
    [22.500, 25.000) = 58 
    [25.000, 27.500) = 21 

  Percentiles, ms/op:
      p(0.0000) =      1.025 ms/op
     p(50.0000) =      4.448 ms/op
     p(90.0000) =      6.152 ms/op
     p(95.0000) =      7.037 ms/op
     p(99.0000) =      8.897 ms/op
     p(99.9000) =     18.842 ms/op
     p(99.9900) =     25.581 ms/op
     p(99.9990) =     27.880 ms/op
     p(99.9999) =     27.984 ms/op
    p(100.0000) =     27.984 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.718 ± 2.799  ops/ms
ClientGrpc.existUser                       thrpt       3   9.202 ± 3.254  ops/ms
ClientGrpc.getUser                         thrpt       3   8.837 ± 2.849  ops/ms
ClientGrpc.listUser                        thrpt       3   6.895 ± 1.084  ops/ms
ClientGrpc.createUser                       avgt       3   3.668 ± 1.146   ms/op
ClientGrpc.existUser                        avgt       3   3.472 ± 0.380   ms/op
ClientGrpc.getUser                          avgt       3   3.727 ± 1.346   ms/op
ClientGrpc.listUser                         avgt       3   4.731 ± 0.297   ms/op
ClientGrpc.createUser                     sample  259821   3.693 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.786           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.588           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.497           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.964           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.693           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.666           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.175           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          25.035           ms/op
ClientGrpc.existUser                      sample  278442   3.447 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.581           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.383           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.100           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.547           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.029           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.158           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          23.664           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          24.445           ms/op
ClientGrpc.getUser                        sample  250187   3.836 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.887           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.703           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.743           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.259           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.111           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.252           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          27.065           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          28.148           ms/op
ClientGrpc.listUser                       sample  204418   4.700 ± 0.009   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.025           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.448           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.152           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.037           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.897           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.842           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.581           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.984           ms/op
