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
# Warmup Iteration   1: 3.002 ops/ms
# Warmup Iteration   2: 6.276 ops/ms
# Warmup Iteration   3: 8.081 ops/ms
Iteration   1: 8.538 ops/ms
Iteration   2: 8.670 ops/ms
Iteration   3: 8.507 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.571 ±(99.9%) 1.581 ops/ms [Average]
  (min, avg, max) = (8.507, 8.571, 8.670), stdev = 0.087
  CI (99.9%): [6.990, 10.152] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 5.500 ops/ms
# Warmup Iteration   2: 8.554 ops/ms
# Warmup Iteration   3: 9.123 ops/ms
Iteration   1: 9.080 ops/ms
Iteration   2: 9.341 ops/ms
Iteration   3: 9.145 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.189 ±(99.9%) 2.476 ops/ms [Average]
  (min, avg, max) = (9.080, 9.189, 9.341), stdev = 0.136
  CI (99.9%): [6.713, 11.665] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 5.422 ops/ms
# Warmup Iteration   2: 7.915 ops/ms
# Warmup Iteration   3: 8.637 ops/ms
Iteration   1: 8.530 ops/ms
Iteration   2: 8.788 ops/ms
Iteration   3: 9.034 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.784 ±(99.9%) 4.599 ops/ms [Average]
  (min, avg, max) = (8.530, 8.784, 9.034), stdev = 0.252
  CI (99.9%): [4.185, 13.384] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 5.206 ops/ms
# Warmup Iteration   2: 6.210 ops/ms
# Warmup Iteration   3: 6.477 ops/ms
Iteration   1: 6.603 ops/ms
Iteration   2: 6.678 ops/ms
Iteration   3: 6.434 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.572 ±(99.9%) 2.283 ops/ms [Average]
  (min, avg, max) = (6.434, 6.572, 6.678), stdev = 0.125
  CI (99.9%): [4.288, 8.855] (assumes normal distribution)


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
# Warmup Iteration   1: 5.695 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.924 ±(99.9%) 0.036 ms/op
# Warmup Iteration   3: 3.829 ±(99.9%) 0.003 ms/op
Iteration   1: 3.739 ±(99.9%) 0.003 ms/op
Iteration   2: 3.612 ±(99.9%) 0.004 ms/op
Iteration   3: 3.638 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.663 ±(99.9%) 1.220 ms/op [Average]
  (min, avg, max) = (3.612, 3.663, 3.739), stdev = 0.067
  CI (99.9%): [2.442, 4.883] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 4.987 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.664 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.458 ±(99.9%) 0.003 ms/op
Iteration   1: 3.499 ±(99.9%) 0.002 ms/op
Iteration   2: 3.521 ±(99.9%) 0.004 ms/op
Iteration   3: 3.523 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.515 ±(99.9%) 0.241 ms/op [Average]
  (min, avg, max) = (3.499, 3.515, 3.523), stdev = 0.013
  CI (99.9%): [3.273, 3.756] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 5.261 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.825 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.645 ±(99.9%) 0.006 ms/op
Iteration   1: 3.605 ±(99.9%) 0.004 ms/op
Iteration   2: 3.749 ±(99.9%) 0.003 ms/op
Iteration   3: 3.679 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.678 ±(99.9%) 1.309 ms/op [Average]
  (min, avg, max) = (3.605, 3.678, 3.749), stdev = 0.072
  CI (99.9%): [2.369, 4.987] (assumes normal distribution)


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
# Warmup Iteration   1: 7.038 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 4.933 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.816 ±(99.9%) 0.011 ms/op
Iteration   1: 4.765 ±(99.9%) 0.009 ms/op
Iteration   2: 4.834 ±(99.9%) 0.015 ms/op
Iteration   3: 4.659 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.753 ±(99.9%) 1.616 ms/op [Average]
  (min, avg, max) = (4.659, 4.753, 4.834), stdev = 0.089
  CI (99.9%): [3.136, 6.369] (assumes normal distribution)


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
# Warmup Iteration   1: 5.180 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 3.810 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.731 ±(99.9%) 0.010 ms/op
Iteration   1: 3.623 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.711 ms/op
                 createUser·p0.50:   3.572 ms/op
                 createUser·p0.90:   4.325 ms/op
                 createUser·p0.95:   4.768 ms/op
                 createUser·p0.99:   6.603 ms/op
                 createUser·p0.999:  9.534 ms/op
                 createUser·p0.9999: 33.494 ms/op
                 createUser·p1.00:   34.341 ms/op

Iteration   2: 3.636 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.930 ms/op
                 createUser·p0.50:   3.576 ms/op
                 createUser·p0.90:   4.235 ms/op
                 createUser·p0.95:   4.612 ms/op
                 createUser·p0.99:   5.915 ms/op
                 createUser·p0.999:  10.404 ms/op
                 createUser·p0.9999: 20.775 ms/op
                 createUser·p1.00:   20.840 ms/op

Iteration   3: 3.644 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.752 ms/op
                 createUser·p0.50:   3.580 ms/op
                 createUser·p0.90:   4.432 ms/op
                 createUser·p0.95:   4.891 ms/op
                 createUser·p0.99:   6.808 ms/op
                 createUser·p0.999:  11.456 ms/op
                 createUser·p0.9999: 23.862 ms/op
                 createUser·p1.00:   24.445 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 264114
  mean =      3.634 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12415 
    [ 2.500,  5.000) = 242384 
    [ 5.000,  7.500) = 7949 
    [ 7.500, 10.000) = 1061 
    [10.000, 12.500) = 111 
    [12.500, 15.000) = 25 
    [15.000, 17.500) = 9 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 79 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 32 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.711 ms/op
     p(50.0000) =      3.576 ms/op
     p(90.0000) =      4.325 ms/op
     p(95.0000) =      4.768 ms/op
     p(99.0000) =      6.504 ms/op
     p(99.9000) =     10.453 ms/op
     p(99.9900) =     32.834 ms/op
     p(99.9990) =     34.149 ms/op
     p(99.9999) =     34.341 ms/op
    p(100.0000) =     34.341 ms/op


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
# Warmup Iteration   1: 4.793 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.697 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.463 ±(99.9%) 0.009 ms/op
Iteration   1: 3.395 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.666 ms/op
                 existUser·p0.50:   3.416 ms/op
                 existUser·p0.90:   4.104 ms/op
                 existUser·p0.95:   4.424 ms/op
                 existUser·p0.99:   5.734 ms/op
                 existUser·p0.999:  11.079 ms/op
                 existUser·p0.9999: 15.876 ms/op
                 existUser·p1.00:   16.351 ms/op

Iteration   2: 3.437 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.919 ms/op
                 existUser·p0.50:   3.400 ms/op
                 existUser·p0.90:   3.949 ms/op
                 existUser·p0.95:   4.219 ms/op
                 existUser·p0.99:   5.595 ms/op
                 existUser·p0.999:  7.750 ms/op
                 existUser·p0.9999: 16.130 ms/op
                 existUser·p1.00:   16.499 ms/op

Iteration   3: 3.484 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.825 ms/op
                 existUser·p0.50:   3.428 ms/op
                 existUser·p0.90:   3.985 ms/op
                 existUser·p0.95:   4.293 ms/op
                 existUser·p0.99:   5.759 ms/op
                 existUser·p0.999:  12.151 ms/op
                 existUser·p0.9999: 21.767 ms/op
                 existUser·p1.00:   22.086 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 279034
  mean =      3.438 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13632 
    [ 2.500,  5.000) = 260610 
    [ 5.000,  7.500) = 3963 
    [ 7.500, 10.000) = 473 
    [10.000, 12.500) = 157 
    [12.500, 15.000) = 60 
    [15.000, 17.500) = 75 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.666 ms/op
     p(50.0000) =      3.416 ms/op
     p(90.0000) =      4.014 ms/op
     p(95.0000) =      4.325 ms/op
     p(99.0000) =      5.685 ms/op
     p(99.9000) =     10.961 ms/op
     p(99.9900) =     20.844 ms/op
     p(99.9990) =     21.994 ms/op
     p(99.9999) =     22.086 ms/op
    p(100.0000) =     22.086 ms/op


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
# Warmup Iteration   1: 5.005 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.847 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.777 ±(99.9%) 0.010 ms/op
Iteration   1: 3.762 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.913 ms/op
                 getUser·p0.50:   3.658 ms/op
                 getUser·p0.90:   4.481 ms/op
                 getUser·p0.95:   4.858 ms/op
                 getUser·p0.99:   6.791 ms/op
                 getUser·p0.999:  13.781 ms/op
                 getUser·p0.9999: 23.446 ms/op
                 getUser·p1.00:   24.642 ms/op

Iteration   2: 3.708 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.925 ms/op
                 getUser·p0.50:   3.633 ms/op
                 getUser·p0.90:   4.448 ms/op
                 getUser·p0.95:   4.841 ms/op
                 getUser·p0.99:   6.382 ms/op
                 getUser·p0.999:  9.431 ms/op
                 getUser·p0.9999: 30.039 ms/op
                 getUser·p1.00:   30.573 ms/op

Iteration   3: 3.725 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.791 ms/op
                 getUser·p0.50:   3.645 ms/op
                 getUser·p0.90:   4.440 ms/op
                 getUser·p0.95:   4.743 ms/op
                 getUser·p0.99:   6.465 ms/op
                 getUser·p0.999:  9.273 ms/op
                 getUser·p0.9999: 33.437 ms/op
                 getUser·p1.00:   33.882 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 257204
  mean =      3.731 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6437 
    [ 2.500,  5.000) = 241343 
    [ 5.000,  7.500) = 8088 
    [ 7.500, 10.000) = 1053 
    [10.000, 12.500) = 65 
    [12.500, 15.000) = 58 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 48 
    [25.000, 27.500) = 15 
    [27.500, 30.000) = 24 
    [30.000, 32.500) = 19 
    [32.500, 35.000) = 22 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.791 ms/op
     p(50.0000) =      3.645 ms/op
     p(90.0000) =      4.456 ms/op
     p(95.0000) =      4.817 ms/op
     p(99.0000) =      6.554 ms/op
     p(99.9000) =     10.568 ms/op
     p(99.9900) =     32.014 ms/op
     p(99.9990) =     33.779 ms/op
     p(99.9999) =     33.882 ms/op
    p(100.0000) =     33.882 ms/op


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
# Warmup Iteration   1: 6.805 ±(99.9%) 0.074 ms/op
# Warmup Iteration   2: 5.128 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.880 ±(99.9%) 0.016 ms/op
Iteration   1: 4.765 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.419 ms/op
                 listUser·p0.50:   4.530 ms/op
                 listUser·p0.90:   6.144 ms/op
                 listUser·p0.95:   7.168 ms/op
                 listUser·p0.99:   9.137 ms/op
                 listUser·p0.999:  15.963 ms/op
                 listUser·p0.9999: 23.591 ms/op
                 listUser·p1.00:   24.412 ms/op

Iteration   2: 4.769 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.352 ms/op
                 listUser·p0.50:   4.579 ms/op
                 listUser·p0.90:   5.849 ms/op
                 listUser·p0.95:   6.636 ms/op
                 listUser·p0.99:   8.405 ms/op
                 listUser·p0.999:  19.951 ms/op
                 listUser·p0.9999: 23.069 ms/op
                 listUser·p1.00:   23.364 ms/op

Iteration   3: 4.476 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   0.625 ms/op
                 listUser·p0.50:   4.276 ms/op
                 listUser·p0.90:   5.743 ms/op
                 listUser·p0.95:   6.693 ms/op
                 listUser·p0.99:   8.339 ms/op
                 listUser·p0.999:  19.514 ms/op
                 listUser·p0.9999: 28.358 ms/op
                 listUser·p1.00:   29.557 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 205759
  mean =      4.666 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 571 
    [ 2.500,  5.000) = 159712 
    [ 5.000,  7.500) = 39813 
    [ 7.500, 10.000) = 4747 
    [10.000, 12.500) = 405 
    [12.500, 15.000) = 122 
    [15.000, 17.500) = 110 
    [17.500, 20.000) = 102 
    [20.000, 22.500) = 91 
    [22.500, 25.000) = 54 
    [25.000, 27.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.625 ms/op
     p(50.0000) =      4.473 ms/op
     p(90.0000) =      5.898 ms/op
     p(95.0000) =      6.840 ms/op
     p(99.0000) =      8.618 ms/op
     p(99.9000) =     18.907 ms/op
     p(99.9900) =     27.356 ms/op
     p(99.9990) =     29.453 ms/op
     p(99.9999) =     29.557 ms/op
    p(100.0000) =     29.557 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.571 ± 1.581  ops/ms
ClientGrpc.existUser                       thrpt       3   9.189 ± 2.476  ops/ms
ClientGrpc.getUser                         thrpt       3   8.784 ± 4.599  ops/ms
ClientGrpc.listUser                        thrpt       3   6.572 ± 2.283  ops/ms
ClientGrpc.createUser                       avgt       3   3.663 ± 1.220   ms/op
ClientGrpc.existUser                        avgt       3   3.515 ± 0.241   ms/op
ClientGrpc.getUser                          avgt       3   3.678 ± 1.309   ms/op
ClientGrpc.listUser                         avgt       3   4.753 ± 1.616   ms/op
ClientGrpc.createUser                     sample  264114   3.634 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.711           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.576           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.325           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.768           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.504           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.453           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          32.834           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          34.341           ms/op
ClientGrpc.existUser                      sample  279034   3.438 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.666           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.416           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.014           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.325           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.685           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.961           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.844           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.086           ms/op
ClientGrpc.getUser                        sample  257204   3.731 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.791           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.645           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.456           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.817           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.554           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.568           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          32.014           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          33.882           ms/op
ClientGrpc.listUser                       sample  205759   4.666 ± 0.009   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.625           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.473           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.898           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.840           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.618           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.907           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          27.356           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          29.557           ms/op
