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
# Warmup Iteration   1: 3.234 ops/ms
# Warmup Iteration   2: 6.916 ops/ms
# Warmup Iteration   3: 8.464 ops/ms
Iteration   1: 8.501 ops/ms
Iteration   2: 8.142 ops/ms
Iteration   3: 8.448 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.364 ±(99.9%) 3.529 ops/ms [Average]
  (min, avg, max) = (8.142, 8.364, 8.501), stdev = 0.193
  CI (99.9%): [4.835, 11.892] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 5.948 ops/ms
# Warmup Iteration   2: 8.088 ops/ms
# Warmup Iteration   3: 8.877 ops/ms
Iteration   1: 9.009 ops/ms
Iteration   2: 8.704 ops/ms
Iteration   3: 9.359 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.024 ±(99.9%) 5.983 ops/ms [Average]
  (min, avg, max) = (8.704, 9.024, 9.359), stdev = 0.328
  CI (99.9%): [3.042, 15.007] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 5.304 ops/ms
# Warmup Iteration   2: 8.267 ops/ms
# Warmup Iteration   3: 8.372 ops/ms
Iteration   1: 8.338 ops/ms
Iteration   2: 8.214 ops/ms
Iteration   3: 8.196 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.249 ±(99.9%) 1.409 ops/ms [Average]
  (min, avg, max) = (8.196, 8.249, 8.338), stdev = 0.077
  CI (99.9%): [6.840, 9.658] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 4.637 ops/ms
# Warmup Iteration   2: 6.188 ops/ms
# Warmup Iteration   3: 6.605 ops/ms
Iteration   1: 7.105 ops/ms
Iteration   2: 6.960 ops/ms
Iteration   3: 6.978 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.014 ±(99.9%) 1.446 ops/ms [Average]
  (min, avg, max) = (6.960, 7.014, 7.105), stdev = 0.079
  CI (99.9%): [5.569, 8.460] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 5.310 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 4.086 ±(99.9%) 0.057 ms/op
# Warmup Iteration   3: 3.869 ±(99.9%) 0.004 ms/op
Iteration   1: 3.961 ±(99.9%) 0.003 ms/op
Iteration   2: 3.785 ±(99.9%) 0.002 ms/op
Iteration   3: 3.910 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.886 ±(99.9%) 1.657 ms/op [Average]
  (min, avg, max) = (3.785, 3.886, 3.961), stdev = 0.091
  CI (99.9%): [2.228, 5.543] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 5.048 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.994 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.637 ±(99.9%) 0.002 ms/op
Iteration   1: 3.746 ±(99.9%) 0.003 ms/op
Iteration   2: 3.478 ±(99.9%) 0.003 ms/op
Iteration   3: 3.718 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.648 ±(99.9%) 2.688 ms/op [Average]
  (min, avg, max) = (3.478, 3.648, 3.746), stdev = 0.147
  CI (99.9%): [0.960, 6.336] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 5.397 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.987 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.770 ±(99.9%) 0.005 ms/op
Iteration   1: 3.842 ±(99.9%) 0.003 ms/op
Iteration   2: 3.718 ±(99.9%) 0.003 ms/op
Iteration   3: 3.915 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.825 ±(99.9%) 1.821 ms/op [Average]
  (min, avg, max) = (3.718, 3.825, 3.915), stdev = 0.100
  CI (99.9%): [2.004, 5.646] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 7.029 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.764 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.664 ±(99.9%) 0.015 ms/op
Iteration   1: 4.694 ±(99.9%) 0.010 ms/op
Iteration   2: 4.743 ±(99.9%) 0.014 ms/op
Iteration   3: 4.947 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.794 ±(99.9%) 2.450 ms/op [Average]
  (min, avg, max) = (4.694, 4.794, 4.947), stdev = 0.134
  CI (99.9%): [2.344, 7.244] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 5.356 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 3.691 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.742 ±(99.9%) 0.009 ms/op
Iteration   1: 3.662 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.883 ms/op
                 createUser·p0.50:   3.600 ms/op
                 createUser·p0.90:   4.424 ms/op
                 createUser·p0.95:   4.743 ms/op
                 createUser·p0.99:   5.595 ms/op
                 createUser·p0.999:  10.343 ms/op
                 createUser·p0.9999: 17.048 ms/op
                 createUser·p1.00:   17.465 ms/op

Iteration   2: 3.836 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.660 ms/op
                 createUser·p0.50:   3.768 ms/op
                 createUser·p0.90:   4.645 ms/op
                 createUser·p0.95:   4.956 ms/op
                 createUser·p0.99:   6.013 ms/op
                 createUser·p0.999:  13.288 ms/op
                 createUser·p0.9999: 16.705 ms/op
                 createUser·p1.00:   17.105 ms/op

Iteration   3: 3.882 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.046 ms/op
                 createUser·p0.50:   3.813 ms/op
                 createUser·p0.90:   4.661 ms/op
                 createUser·p0.95:   4.941 ms/op
                 createUser·p0.99:   6.398 ms/op
                 createUser·p0.999:  14.222 ms/op
                 createUser·p0.9999: 26.075 ms/op
                 createUser·p1.00:   26.411 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 253335
  mean =      3.791 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5382 
    [ 2.500,  5.000) = 238108 
    [ 5.000,  7.500) = 8785 
    [ 7.500, 10.000) = 590 
    [10.000, 12.500) = 170 
    [12.500, 15.000) = 157 
    [15.000, 17.500) = 92 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.660 ms/op
     p(50.0000) =      3.723 ms/op
     p(90.0000) =      4.588 ms/op
     p(95.0000) =      4.891 ms/op
     p(99.0000) =      5.956 ms/op
     p(99.9000) =     13.140 ms/op
     p(99.9900) =     25.635 ms/op
     p(99.9990) =     26.280 ms/op
     p(99.9999) =     26.411 ms/op
    p(100.0000) =     26.411 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.941 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.953 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.679 ±(99.9%) 0.009 ms/op
Iteration   1: 3.738 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.985 ms/op
                 existUser·p0.50:   3.686 ms/op
                 existUser·p0.90:   4.547 ms/op
                 existUser·p0.95:   4.817 ms/op
                 existUser·p0.99:   6.152 ms/op
                 existUser·p0.999:  11.671 ms/op
                 existUser·p0.9999: 15.209 ms/op
                 existUser·p1.00:   15.548 ms/op

Iteration   2: 3.733 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.904 ms/op
                 existUser·p0.50:   3.686 ms/op
                 existUser·p0.90:   4.596 ms/op
                 existUser·p0.95:   4.841 ms/op
                 existUser·p0.99:   5.693 ms/op
                 existUser·p0.999:  9.520 ms/op
                 existUser·p0.9999: 16.974 ms/op
                 existUser·p1.00:   17.302 ms/op

Iteration   3: 3.597 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.924 ms/op
                 existUser·p0.50:   3.547 ms/op
                 existUser·p0.90:   4.407 ms/op
                 existUser·p0.95:   4.669 ms/op
                 existUser·p0.99:   5.497 ms/op
                 existUser·p0.999:  11.947 ms/op
                 existUser·p0.9999: 19.209 ms/op
                 existUser·p1.00:   19.628 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 260203
  mean =      3.688 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 185 
    [ 1.250,  2.500) = 8912 
    [ 2.500,  3.750) = 139494 
    [ 3.750,  5.000) = 104314 
    [ 5.000,  6.250) = 5383 
    [ 6.250,  7.500) = 910 
    [ 7.500,  8.750) = 454 
    [ 8.750, 10.000) = 139 
    [10.000, 11.250) = 106 
    [11.250, 12.500) = 126 
    [12.500, 13.750) = 35 
    [13.750, 15.000) = 52 
    [15.000, 16.250) = 40 
    [16.250, 17.500) = 21 
    [17.500, 18.750) = 11 

  Percentiles, ms/op:
      p(0.0000) =      0.904 ms/op
     p(50.0000) =      3.633 ms/op
     p(90.0000) =      4.522 ms/op
     p(95.0000) =      4.784 ms/op
     p(99.0000) =      5.767 ms/op
     p(99.9000) =     11.633 ms/op
     p(99.9900) =     18.678 ms/op
     p(99.9990) =     19.510 ms/op
     p(99.9999) =     19.628 ms/op
    p(100.0000) =     19.628 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.423 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.012 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.955 ±(99.9%) 0.011 ms/op
Iteration   1: 4.007 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.067 ms/op
                 getUser·p0.50:   3.936 ms/op
                 getUser·p0.90:   4.915 ms/op
                 getUser·p0.95:   5.235 ms/op
                 getUser·p0.99:   7.285 ms/op
                 getUser·p0.999:  13.617 ms/op
                 getUser·p0.9999: 16.188 ms/op
                 getUser·p1.00:   16.613 ms/op

Iteration   2: 3.908 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.964 ms/op
                 getUser·p0.50:   3.875 ms/op
                 getUser·p0.90:   4.801 ms/op
                 getUser·p0.95:   5.087 ms/op
                 getUser·p0.99:   6.136 ms/op
                 getUser·p0.999:  9.210 ms/op
                 getUser·p0.9999: 16.004 ms/op
                 getUser·p1.00:   16.237 ms/op

Iteration   3: 3.953 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.100 ms/op
                 getUser·p0.50:   3.879 ms/op
                 getUser·p0.90:   4.841 ms/op
                 getUser·p0.95:   5.161 ms/op
                 getUser·p0.99:   6.128 ms/op
                 getUser·p0.999:  9.519 ms/op
                 getUser·p0.9999: 19.753 ms/op
                 getUser·p1.00:   22.610 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 242699
  mean =      3.956 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7124 
    [ 2.500,  5.000) = 218218 
    [ 5.000,  7.500) = 15986 
    [ 7.500, 10.000) = 978 
    [10.000, 12.500) = 205 
    [12.500, 15.000) = 79 
    [15.000, 17.500) = 77 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.964 ms/op
     p(50.0000) =      3.895 ms/op
     p(90.0000) =      4.858 ms/op
     p(95.0000) =      5.161 ms/op
     p(99.0000) =      6.447 ms/op
     p(99.9000) =     11.752 ms/op
     p(99.9900) =     19.357 ms/op
     p(99.9990) =     21.176 ms/op
     p(99.9999) =     22.610 ms/op
    p(100.0000) =     22.610 ms/op


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
# Warmup Iteration   1: 7.284 ±(99.9%) 0.076 ms/op
# Warmup Iteration   2: 5.154 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.760 ±(99.9%) 0.015 ms/op
Iteration   1: 4.622 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.481 ms/op
                 listUser·p0.50:   4.415 ms/op
                 listUser·p0.90:   5.956 ms/op
                 listUser·p0.95:   6.832 ms/op
                 listUser·p0.99:   8.421 ms/op
                 listUser·p0.999:  16.182 ms/op
                 listUser·p0.9999: 22.186 ms/op
                 listUser·p1.00:   22.675 ms/op

Iteration   2: 4.737 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.950 ms/op
                 listUser·p0.50:   4.555 ms/op
                 listUser·p0.90:   5.841 ms/op
                 listUser·p0.95:   6.636 ms/op
                 listUser·p0.99:   8.405 ms/op
                 listUser·p0.999:  16.450 ms/op
                 listUser·p0.9999: 23.798 ms/op
                 listUser·p1.00:   24.117 ms/op

Iteration   3: 4.771 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.120 ms/op
                 listUser·p0.50:   4.538 ms/op
                 listUser·p0.90:   6.242 ms/op
                 listUser·p0.95:   6.898 ms/op
                 listUser·p0.99:   8.651 ms/op
                 listUser·p0.999:  21.234 ms/op
                 listUser·p0.9999: 25.851 ms/op
                 listUser·p1.00:   26.345 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 203810
  mean =      4.709 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 272 
    [ 2.500,  5.000) = 152848 
    [ 5.000,  7.500) = 45681 
    [ 7.500, 10.000) = 4087 
    [10.000, 12.500) = 400 
    [12.500, 15.000) = 191 
    [15.000, 17.500) = 149 
    [17.500, 20.000) = 42 
    [20.000, 22.500) = 62 
    [22.500, 25.000) = 68 
    [25.000, 27.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      1.120 ms/op
     p(50.0000) =      4.506 ms/op
     p(90.0000) =      6.038 ms/op
     p(95.0000) =      6.791 ms/op
     p(99.0000) =      8.487 ms/op
     p(99.9000) =     16.914 ms/op
     p(99.9900) =     24.117 ms/op
     p(99.9990) =     26.243 ms/op
     p(99.9999) =     26.345 ms/op
    p(100.0000) =     26.345 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.364 ± 3.529  ops/ms
ClientGrpc.existUser                       thrpt       3   9.024 ± 5.983  ops/ms
ClientGrpc.getUser                         thrpt       3   8.249 ± 1.409  ops/ms
ClientGrpc.listUser                        thrpt       3   7.014 ± 1.446  ops/ms
ClientGrpc.createUser                       avgt       3   3.886 ± 1.657   ms/op
ClientGrpc.existUser                        avgt       3   3.648 ± 2.688   ms/op
ClientGrpc.getUser                          avgt       3   3.825 ± 1.821   ms/op
ClientGrpc.listUser                         avgt       3   4.794 ± 2.450   ms/op
ClientGrpc.createUser                     sample  253335   3.791 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.660           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.723           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.588           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.891           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.956           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.140           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          25.635           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          26.411           ms/op
ClientGrpc.existUser                      sample  260203   3.688 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.904           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.633           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.522           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.784           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.767           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.633           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.678           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.628           ms/op
ClientGrpc.getUser                        sample  242699   3.956 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.964           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.895           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.858           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.161           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.447           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.752           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.357           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.610           ms/op
ClientGrpc.listUser                       sample  203810   4.709 ± 0.009   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.120           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.506           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.038           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.791           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.487           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.914           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.117           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.345           ms/op
