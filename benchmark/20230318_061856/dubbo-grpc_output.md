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
# Warmup Iteration   1: 2.284 ops/ms
# Warmup Iteration   2: 5.827 ops/ms
# Warmup Iteration   3: 7.786 ops/ms
Iteration   1: 8.178 ops/ms
Iteration   2: 8.328 ops/ms
Iteration   3: 8.264 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.256 ±(99.9%) 1.375 ops/ms [Average]
  (min, avg, max) = (8.178, 8.256, 8.328), stdev = 0.075
  CI (99.9%): [6.881, 9.632] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 5.480 ops/ms
# Warmup Iteration   2: 8.029 ops/ms
# Warmup Iteration   3: 8.890 ops/ms
Iteration   1: 8.933 ops/ms
Iteration   2: 9.031 ops/ms
Iteration   3: 9.171 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.045 ±(99.9%) 2.184 ops/ms [Average]
  (min, avg, max) = (8.933, 9.045, 9.171), stdev = 0.120
  CI (99.9%): [6.860, 11.229] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 4.704 ops/ms
# Warmup Iteration   2: 7.489 ops/ms
# Warmup Iteration   3: 7.932 ops/ms
Iteration   1: 8.340 ops/ms
Iteration   2: 8.309 ops/ms
Iteration   3: 8.024 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.224 ±(99.9%) 3.179 ops/ms [Average]
  (min, avg, max) = (8.024, 8.224, 8.340), stdev = 0.174
  CI (99.9%): [5.045, 11.403] (assumes normal distribution)


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
# Warmup Iteration   1: 3.986 ops/ms
# Warmup Iteration   2: 5.714 ops/ms
# Warmup Iteration   3: 6.219 ops/ms
Iteration   1: 6.307 ops/ms
Iteration   2: 6.170 ops/ms
Iteration   3: 6.503 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.327 ±(99.9%) 3.055 ops/ms [Average]
  (min, avg, max) = (6.170, 6.327, 6.503), stdev = 0.167
  CI (99.9%): [3.272, 9.381] (assumes normal distribution)


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
# Warmup Iteration   1: 6.275 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.156 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.996 ±(99.9%) 0.015 ms/op
Iteration   1: 3.901 ±(99.9%) 0.003 ms/op
Iteration   2: 3.873 ±(99.9%) 0.002 ms/op
Iteration   3: 3.906 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.893 ±(99.9%) 0.316 ms/op [Average]
  (min, avg, max) = (3.873, 3.893, 3.906), stdev = 0.017
  CI (99.9%): [3.577, 4.210] (assumes normal distribution)


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
# Warmup Iteration   1: 5.589 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 4.128 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.677 ±(99.9%) 0.004 ms/op
Iteration   1: 3.605 ±(99.9%) 0.002 ms/op
Iteration   2: 3.646 ±(99.9%) 0.003 ms/op
Iteration   3: 3.698 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.650 ±(99.9%) 0.843 ms/op [Average]
  (min, avg, max) = (3.605, 3.650, 3.698), stdev = 0.046
  CI (99.9%): [2.807, 4.493] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 6.357 ±(99.9%) 0.064 ms/op
# Warmup Iteration   2: 4.302 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.920 ±(99.9%) 0.005 ms/op
Iteration   1: 3.806 ±(99.9%) 0.005 ms/op
Iteration   2: 3.739 ±(99.9%) 0.002 ms/op
Iteration   3: 3.726 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.757 ±(99.9%) 0.787 ms/op [Average]
  (min, avg, max) = (3.726, 3.757, 3.806), stdev = 0.043
  CI (99.9%): [2.970, 4.544] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 7.316 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 5.386 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 5.065 ±(99.9%) 0.013 ms/op
Iteration   1: 5.006 ±(99.9%) 0.016 ms/op
Iteration   2: 4.948 ±(99.9%) 0.018 ms/op
Iteration   3: 5.150 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.035 ±(99.9%) 1.897 ms/op [Average]
  (min, avg, max) = (4.948, 5.035, 5.150), stdev = 0.104
  CI (99.9%): [3.138, 6.932] (assumes normal distribution)


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
# Warmup Iteration   1: 6.067 ±(99.9%) 0.075 ms/op
# Warmup Iteration   2: 4.114 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.750 ±(99.9%) 0.011 ms/op
Iteration   1: 3.867 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.916 ms/op
                 createUser·p0.50:   3.744 ms/op
                 createUser·p0.90:   4.825 ms/op
                 createUser·p0.95:   5.235 ms/op
                 createUser·p0.99:   7.410 ms/op
                 createUser·p0.999:  13.451 ms/op
                 createUser·p0.9999: 16.979 ms/op
                 createUser·p1.00:   18.055 ms/op

Iteration   2: 3.763 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.006 ms/op
                 createUser·p0.50:   3.650 ms/op
                 createUser·p0.90:   4.628 ms/op
                 createUser·p0.95:   5.079 ms/op
                 createUser·p0.99:   6.259 ms/op
                 createUser·p0.999:  11.862 ms/op
                 createUser·p0.9999: 17.941 ms/op
                 createUser·p1.00:   18.514 ms/op

Iteration   3: 3.835 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.964 ms/op
                 createUser·p0.50:   3.690 ms/op
                 createUser·p0.90:   4.776 ms/op
                 createUser·p0.95:   5.267 ms/op
                 createUser·p0.99:   7.287 ms/op
                 createUser·p0.999:  16.204 ms/op
                 createUser·p0.9999: 27.218 ms/op
                 createUser·p1.00:   27.918 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 251249
  mean =      3.821 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5617 
    [ 2.500,  5.000) = 228698 
    [ 5.000,  7.500) = 14904 
    [ 7.500, 10.000) = 1378 
    [10.000, 12.500) = 321 
    [12.500, 15.000) = 151 
    [15.000, 17.500) = 99 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 49 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.916 ms/op
     p(50.0000) =      3.690 ms/op
     p(90.0000) =      4.751 ms/op
     p(95.0000) =      5.194 ms/op
     p(99.0000) =      7.090 ms/op
     p(99.9000) =     13.533 ms/op
     p(99.9900) =     21.950 ms/op
     p(99.9990) =     27.803 ms/op
     p(99.9999) =     27.918 ms/op
    p(100.0000) =     27.918 ms/op


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
# Warmup Iteration   1: 5.419 ±(99.9%) 0.061 ms/op
# Warmup Iteration   2: 4.012 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.702 ±(99.9%) 0.009 ms/op
Iteration   1: 3.629 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.384 ms/op
                 existUser·p0.50:   3.547 ms/op
                 existUser·p0.90:   4.538 ms/op
                 existUser·p0.95:   5.030 ms/op
                 existUser·p0.99:   6.414 ms/op
                 existUser·p0.999:  10.060 ms/op
                 existUser·p0.9999: 14.427 ms/op
                 existUser·p1.00:   16.630 ms/op

Iteration   2: 3.612 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.754 ms/op
                 existUser·p0.50:   3.514 ms/op
                 existUser·p0.90:   4.375 ms/op
                 existUser·p0.95:   4.850 ms/op
                 existUser·p0.99:   7.496 ms/op
                 existUser·p0.999:  13.599 ms/op
                 existUser·p0.9999: 25.765 ms/op
                 existUser·p1.00:   28.705 ms/op

Iteration   3: 3.692 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.727 ms/op
                 existUser·p0.50:   3.609 ms/op
                 existUser·p0.90:   4.604 ms/op
                 existUser·p0.95:   4.940 ms/op
                 existUser·p0.99:   6.144 ms/op
                 existUser·p0.999:  12.160 ms/op
                 existUser·p0.9999: 18.121 ms/op
                 existUser·p1.00:   19.431 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 263454
  mean =      3.644 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11575 
    [ 2.500,  5.000) = 239814 
    [ 5.000,  7.500) = 10360 
    [ 7.500, 10.000) = 1166 
    [10.000, 12.500) = 272 
    [12.500, 15.000) = 167 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.384 ms/op
     p(50.0000) =      3.551 ms/op
     p(90.0000) =      4.522 ms/op
     p(95.0000) =      4.940 ms/op
     p(99.0000) =      6.578 ms/op
     p(99.9000) =     12.723 ms/op
     p(99.9900) =     24.773 ms/op
     p(99.9990) =     26.161 ms/op
     p(99.9999) =     28.705 ms/op
    p(100.0000) =     28.705 ms/op


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
# Warmup Iteration   1: 5.766 ±(99.9%) 0.063 ms/op
# Warmup Iteration   2: 4.258 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.171 ±(99.9%) 0.015 ms/op
Iteration   1: 3.942 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.188 ms/op
                 getUser·p0.50:   3.822 ms/op
                 getUser·p0.90:   4.981 ms/op
                 getUser·p0.95:   5.366 ms/op
                 getUser·p0.99:   6.390 ms/op
                 getUser·p0.999:  12.108 ms/op
                 getUser·p0.9999: 15.684 ms/op
                 getUser·p1.00:   16.138 ms/op

Iteration   2: 3.846 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.929 ms/op
                 getUser·p0.50:   3.731 ms/op
                 getUser·p0.90:   4.686 ms/op
                 getUser·p0.95:   5.030 ms/op
                 getUser·p0.99:   6.054 ms/op
                 getUser·p0.999:  10.101 ms/op
                 getUser·p0.9999: 25.866 ms/op
                 getUser·p1.00:   26.116 ms/op

Iteration   3: 3.890 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.029 ms/op
                 getUser·p0.50:   3.801 ms/op
                 getUser·p0.90:   4.784 ms/op
                 getUser·p0.95:   5.177 ms/op
                 getUser·p0.99:   6.241 ms/op
                 getUser·p0.999:  11.431 ms/op
                 getUser·p0.9999: 19.227 ms/op
                 getUser·p1.00:   19.562 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 246677
  mean =      3.892 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3104 
    [ 2.500,  5.000) = 225736 
    [ 5.000,  7.500) = 16832 
    [ 7.500, 10.000) = 681 
    [10.000, 12.500) = 134 
    [12.500, 15.000) = 71 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 62 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.929 ms/op
     p(50.0000) =      3.785 ms/op
     p(90.0000) =      4.817 ms/op
     p(95.0000) =      5.202 ms/op
     p(99.0000) =      6.259 ms/op
     p(99.9000) =     11.403 ms/op
     p(99.9900) =     25.330 ms/op
     p(99.9990) =     26.053 ms/op
     p(99.9999) =     26.116 ms/op
    p(100.0000) =     26.116 ms/op


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
# Warmup Iteration   1: 7.094 ±(99.9%) 0.080 ms/op
# Warmup Iteration   2: 5.488 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 5.147 ±(99.9%) 0.018 ms/op
Iteration   1: 5.036 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.163 ms/op
                 listUser·p0.50:   4.825 ms/op
                 listUser·p0.90:   6.521 ms/op
                 listUser·p0.95:   7.479 ms/op
                 listUser·p0.99:   9.912 ms/op
                 listUser·p0.999:  15.811 ms/op
                 listUser·p0.9999: 21.288 ms/op
                 listUser·p1.00:   23.101 ms/op

Iteration   2: 4.877 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   2.150 ms/op
                 listUser·p0.50:   4.628 ms/op
                 listUser·p0.90:   6.283 ms/op
                 listUser·p0.95:   7.209 ms/op
                 listUser·p0.99:   9.175 ms/op
                 listUser·p0.999:  15.785 ms/op
                 listUser·p0.9999: 29.222 ms/op
                 listUser·p1.00:   29.786 ms/op

Iteration   3: 5.051 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.382 ms/op
                 listUser·p0.50:   4.792 ms/op
                 listUser·p0.90:   6.545 ms/op
                 listUser·p0.95:   7.389 ms/op
                 listUser·p0.99:   9.716 ms/op
                 listUser·p0.999:  21.823 ms/op
                 listUser·p0.9999: 26.772 ms/op
                 listUser·p1.00:   27.165 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 192353
  mean =      4.987 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 287 
    [ 2.500,  5.000) = 119763 
    [ 5.000,  7.500) = 63728 
    [ 7.500, 10.000) = 7025 
    [10.000, 12.500) = 902 
    [12.500, 15.000) = 336 
    [15.000, 17.500) = 124 
    [17.500, 20.000) = 34 
    [20.000, 22.500) = 67 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 29 

  Percentiles, ms/op:
      p(0.0000) =      1.163 ms/op
     p(50.0000) =      4.743 ms/op
     p(90.0000) =      6.455 ms/op
     p(95.0000) =      7.356 ms/op
     p(99.0000) =      9.617 ms/op
     p(99.9000) =     16.906 ms/op
     p(99.9900) =     28.369 ms/op
     p(99.9990) =     29.756 ms/op
     p(99.9999) =     29.786 ms/op
    p(100.0000) =     29.786 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.256 ± 1.375  ops/ms
ClientGrpc.existUser                       thrpt       3   9.045 ± 2.184  ops/ms
ClientGrpc.getUser                         thrpt       3   8.224 ± 3.179  ops/ms
ClientGrpc.listUser                        thrpt       3   6.327 ± 3.055  ops/ms
ClientGrpc.createUser                       avgt       3   3.893 ± 0.316   ms/op
ClientGrpc.existUser                        avgt       3   3.650 ± 0.843   ms/op
ClientGrpc.getUser                          avgt       3   3.757 ± 0.787   ms/op
ClientGrpc.listUser                         avgt       3   5.035 ± 1.897   ms/op
ClientGrpc.createUser                     sample  251249   3.821 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.916           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.690           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.751           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.194           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.090           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.533           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.950           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          27.918           ms/op
ClientGrpc.existUser                      sample  263454   3.644 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.384           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.551           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.522           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.940           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.578           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          12.723           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          24.773           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          28.705           ms/op
ClientGrpc.getUser                        sample  246677   3.892 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.929           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.785           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.817           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.202           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.259           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.403           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          25.330           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          26.116           ms/op
ClientGrpc.listUser                       sample  192353   4.987 ± 0.010   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.163           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.743           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.455           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.356           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.617           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.906           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          28.369           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          29.786           ms/op
