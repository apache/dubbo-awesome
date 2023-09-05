# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.170 ops/ms
# Warmup Iteration   2: 8.616 ops/ms
# Warmup Iteration   3: 9.944 ops/ms
Iteration   1: 10.356 ops/ms
Iteration   2: 10.290 ops/ms
Iteration   3: 10.503 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.383 ±(99.9%) 1.993 ops/ms [Average]
  (min, avg, max) = (10.290, 10.383, 10.503), stdev = 0.109
  CI (99.9%): [8.390, 12.376] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.500 ops/ms
# Warmup Iteration   2: 10.433 ops/ms
# Warmup Iteration   3: 10.823 ops/ms
Iteration   1: 10.878 ops/ms
Iteration   2: 10.815 ops/ms
Iteration   3: 11.000 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.898 ±(99.9%) 1.716 ops/ms [Average]
  (min, avg, max) = (10.815, 10.898, 11.000), stdev = 0.094
  CI (99.9%): [9.181, 12.614] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
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
# Warmup Iteration   2: 9.605 ops/ms
# Warmup Iteration   3: 10.222 ops/ms
Iteration   1: 10.252 ops/ms
Iteration   2: 10.397 ops/ms
Iteration   3: 10.492 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.380 ±(99.9%) 2.207 ops/ms [Average]
  (min, avg, max) = (10.252, 10.380, 10.492), stdev = 0.121
  CI (99.9%): [8.173, 12.587] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.339 ops/ms
# Warmup Iteration   2: 7.196 ops/ms
# Warmup Iteration   3: 7.768 ops/ms
Iteration   1: 7.992 ops/ms
Iteration   2: 7.973 ops/ms
Iteration   3: 8.083 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.016 ±(99.9%) 1.077 ops/ms [Average]
  (min, avg, max) = (7.973, 8.016, 8.083), stdev = 0.059
  CI (99.9%): [6.939, 9.093] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.512 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.199 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.085 ±(99.9%) 0.003 ms/op
Iteration   1: 3.112 ±(99.9%) 0.004 ms/op
Iteration   2: 3.075 ±(99.9%) 0.003 ms/op
Iteration   3: 3.076 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.088 ±(99.9%) 0.381 ms/op [Average]
  (min, avg, max) = (3.075, 3.088, 3.112), stdev = 0.021
  CI (99.9%): [2.707, 3.468] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 4.171 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.062 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.974 ±(99.9%) 0.002 ms/op
Iteration   1: 2.875 ±(99.9%) 0.004 ms/op
Iteration   2: 2.947 ±(99.9%) 0.002 ms/op
Iteration   3: 2.877 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.900 ±(99.9%) 0.744 ms/op [Average]
  (min, avg, max) = (2.875, 2.900, 2.947), stdev = 0.041
  CI (99.9%): [2.155, 3.644] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.126 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.199 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.083 ±(99.9%) 0.004 ms/op
Iteration   1: 3.021 ±(99.9%) 0.003 ms/op
Iteration   2: 3.051 ±(99.9%) 0.004 ms/op
Iteration   3: 3.063 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.045 ±(99.9%) 0.401 ms/op [Average]
  (min, avg, max) = (3.021, 3.045, 3.063), stdev = 0.022
  CI (99.9%): [2.644, 3.446] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.633 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.225 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.842 ±(99.9%) 0.024 ms/op
Iteration   1: 3.907 ±(99.9%) 0.014 ms/op
Iteration   2: 3.963 ±(99.9%) 0.010 ms/op
Iteration   3: 3.836 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.902 ±(99.9%) 1.162 ms/op [Average]
  (min, avg, max) = (3.836, 3.902, 3.963), stdev = 0.064
  CI (99.9%): [2.740, 5.064] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.416 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.215 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.096 ±(99.9%) 0.007 ms/op
Iteration   1: 3.043 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.964 ms/op
                 createUser·p0.50:   3.031 ms/op
                 createUser·p0.90:   3.523 ms/op
                 createUser·p0.95:   3.723 ms/op
                 createUser·p0.99:   4.530 ms/op
                 createUser·p0.999:  8.328 ms/op
                 createUser·p0.9999: 12.984 ms/op
                 createUser·p1.00:   13.500 ms/op

Iteration   2: 3.101 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.855 ms/op
                 createUser·p0.50:   3.072 ms/op
                 createUser·p0.90:   3.654 ms/op
                 createUser·p0.95:   3.830 ms/op
                 createUser·p0.99:   4.497 ms/op
                 createUser·p0.999:  8.418 ms/op
                 createUser·p0.9999: 14.654 ms/op
                 createUser·p1.00:   14.975 ms/op

Iteration   3: 3.087 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.927 ms/op
                 createUser·p0.50:   3.019 ms/op
                 createUser·p0.90:   3.490 ms/op
                 createUser·p0.95:   3.686 ms/op
                 createUser·p0.99:   4.473 ms/op
                 createUser·p0.999:  17.641 ms/op
                 createUser·p0.9999: 58.893 ms/op
                 createUser·p1.00:   60.621 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 311856
  mean =      3.077 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 309827 
    [ 5.000, 10.000) = 1651 
    [10.000, 15.000) = 249 
    [15.000, 20.000) = 78 
    [20.000, 25.000) = 15 
    [25.000, 30.000) = 3 
    [30.000, 35.000) = 3 
    [35.000, 40.000) = 4 
    [40.000, 45.000) = 5 
    [45.000, 50.000) = 3 
    [50.000, 55.000) = 5 
    [55.000, 60.000) = 4 
    [60.000, 65.000) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.855 ms/op
     p(50.0000) =      3.039 ms/op
     p(90.0000) =      3.564 ms/op
     p(95.0000) =      3.760 ms/op
     p(99.0000) =      4.497 ms/op
     p(99.9000) =     11.146 ms/op
     p(99.9900) =     34.303 ms/op
     p(99.9990) =     60.555 ms/op
     p(99.9999) =     60.621 ms/op
    p(100.0000) =     60.621 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 4.077 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.057 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.921 ±(99.9%) 0.006 ms/op
Iteration   1: 2.904 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.783 ms/op
                 existUser·p0.50:   2.896 ms/op
                 existUser·p0.90:   3.322 ms/op
                 existUser·p0.95:   3.510 ms/op
                 existUser·p0.99:   4.301 ms/op
                 existUser·p0.999:  8.897 ms/op
                 existUser·p0.9999: 12.796 ms/op
                 existUser·p1.00:   12.993 ms/op

Iteration   2: 2.937 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.267 ms/op
                 existUser·p0.50:   2.925 ms/op
                 existUser·p0.90:   3.420 ms/op
                 existUser·p0.95:   3.613 ms/op
                 existUser·p0.99:   4.211 ms/op
                 existUser·p0.999:  7.873 ms/op
                 existUser·p0.9999: 14.844 ms/op
                 existUser·p1.00:   15.008 ms/op

Iteration   3: 2.922 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.526 ms/op
                 existUser·p0.50:   2.945 ms/op
                 existUser·p0.90:   3.416 ms/op
                 existUser·p0.95:   3.555 ms/op
                 existUser·p0.99:   4.194 ms/op
                 existUser·p0.999:  7.335 ms/op
                 existUser·p0.9999: 27.856 ms/op
                 existUser·p1.00:   28.279 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 328723
  mean =      2.921 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 34323 
    [ 2.500,  5.000) = 292931 
    [ 5.000,  7.500) = 1006 
    [ 7.500, 10.000) = 272 
    [10.000, 12.500) = 64 
    [12.500, 15.000) = 94 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 19 

  Percentiles, ms/op:
      p(0.0000) =      0.267 ms/op
     p(50.0000) =      2.920 ms/op
     p(90.0000) =      3.387 ms/op
     p(95.0000) =      3.564 ms/op
     p(99.0000) =      4.235 ms/op
     p(99.9000) =      8.121 ms/op
     p(99.9900) =     16.417 ms/op
     p(99.9990) =     28.171 ms/op
     p(99.9999) =     28.279 ms/op
    p(100.0000) =     28.279 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.450 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.192 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.067 ±(99.9%) 0.007 ms/op
Iteration   1: 3.116 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.738 ms/op
                 getUser·p0.50:   3.056 ms/op
                 getUser·p0.90:   3.711 ms/op
                 getUser·p0.95:   3.863 ms/op
                 getUser·p0.99:   4.620 ms/op
                 getUser·p0.999:  7.887 ms/op
                 getUser·p0.9999: 21.201 ms/op
                 getUser·p1.00:   21.955 ms/op

Iteration   2: 3.068 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.767 ms/op
                 getUser·p0.50:   3.027 ms/op
                 getUser·p0.90:   3.609 ms/op
                 getUser·p0.95:   3.822 ms/op
                 getUser·p0.99:   4.530 ms/op
                 getUser·p0.999:  7.387 ms/op
                 getUser·p0.9999: 22.661 ms/op
                 getUser·p1.00:   22.970 ms/op

Iteration   3: 3.085 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.650 ms/op
                 getUser·p0.50:   3.039 ms/op
                 getUser·p0.90:   3.621 ms/op
                 getUser·p0.95:   3.875 ms/op
                 getUser·p0.99:   4.588 ms/op
                 getUser·p0.999:  8.521 ms/op
                 getUser·p0.9999: 31.130 ms/op
                 getUser·p1.00:   32.866 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 310578
  mean =      3.090 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17351 
    [ 2.500,  5.000) = 291367 
    [ 5.000,  7.500) = 1417 
    [ 7.500, 10.000) = 251 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 92 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 5 
    [30.000, 32.500) = 55 
    [32.500, 35.000) = 4 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.650 ms/op
     p(50.0000) =      3.043 ms/op
     p(90.0000) =      3.654 ms/op
     p(95.0000) =      3.854 ms/op
     p(99.0000) =      4.579 ms/op
     p(99.9000) =      8.153 ms/op
     p(99.9900) =     30.835 ms/op
     p(99.9990) =     32.711 ms/op
     p(99.9999) =     32.866 ms/op
    p(100.0000) =     32.866 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.913 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.150 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.002 ±(99.9%) 0.012 ms/op
Iteration   1: 4.002 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.286 ms/op
                 listUser·p0.50:   3.817 ms/op
                 listUser·p0.90:   5.038 ms/op
                 listUser·p0.95:   5.759 ms/op
                 listUser·p0.99:   7.283 ms/op
                 listUser·p0.999:  14.420 ms/op
                 listUser·p0.9999: 22.676 ms/op
                 listUser·p1.00:   23.396 ms/op

Iteration   2: 3.976 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.936 ms/op
                 listUser·p0.50:   3.813 ms/op
                 listUser·p0.90:   5.046 ms/op
                 listUser·p0.95:   5.833 ms/op
                 listUser·p0.99:   7.094 ms/op
                 listUser·p0.999:  16.377 ms/op
                 listUser·p0.9999: 22.379 ms/op
                 listUser·p1.00:   22.708 ms/op

Iteration   3: 3.966 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.979 ms/op
                 listUser·p0.50:   3.789 ms/op
                 listUser·p0.90:   5.030 ms/op
                 listUser·p0.95:   5.923 ms/op
                 listUser·p0.99:   7.037 ms/op
                 listUser·p0.999:  16.807 ms/op
                 listUser·p0.9999: 18.512 ms/op
                 listUser·p1.00:   20.087 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 241077
  mean =      3.981 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4008 
    [ 2.500,  5.000) = 212026 
    [ 5.000,  7.500) = 23270 
    [ 7.500, 10.000) = 1316 
    [10.000, 12.500) = 105 
    [12.500, 15.000) = 52 
    [15.000, 17.500) = 121 
    [17.500, 20.000) = 104 
    [20.000, 22.500) = 57 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.936 ms/op
     p(50.0000) =      3.805 ms/op
     p(90.0000) =      5.038 ms/op
     p(95.0000) =      5.841 ms/op
     p(99.0000) =      7.127 ms/op
     p(99.9000) =     16.138 ms/op
     p(99.9900) =     22.410 ms/op
     p(99.9990) =     23.171 ms/op
     p(99.9999) =     23.396 ms/op
    p(100.0000) =     23.396 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.383 ± 1.993  ops/ms
ClientGrpc.existUser                       thrpt       3  10.898 ± 1.716  ops/ms
ClientGrpc.getUser                         thrpt       3  10.380 ± 2.207  ops/ms
ClientGrpc.listUser                        thrpt       3   8.016 ± 1.077  ops/ms
ClientGrpc.createUser                       avgt       3   3.088 ± 0.381   ms/op
ClientGrpc.existUser                        avgt       3   2.900 ± 0.744   ms/op
ClientGrpc.getUser                          avgt       3   3.045 ± 0.401   ms/op
ClientGrpc.listUser                         avgt       3   3.902 ± 1.162   ms/op
ClientGrpc.createUser                     sample  311856   3.077 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.855           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.039           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.564           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.760           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.497           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.146           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          34.303           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          60.621           ms/op
ClientGrpc.existUser                      sample  328723   2.921 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.267           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.920           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.387           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.564           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.235           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.121           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.417           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          28.279           ms/op
ClientGrpc.getUser                        sample  310578   3.090 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.650           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.043           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.654           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.854           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.579           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.153           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          30.835           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          32.866           ms/op
ClientGrpc.listUser                       sample  241077   3.981 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.936           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.805           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.038           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.841           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.127           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.138           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.410           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.396           ms/op
