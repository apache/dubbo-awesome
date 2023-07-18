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
# Warmup Iteration   1: 3.665 ops/ms
# Warmup Iteration   2: 8.520 ops/ms
# Warmup Iteration   3: 9.380 ops/ms
Iteration   1: 9.993 ops/ms
Iteration   2: 10.090 ops/ms
Iteration   3: 10.025 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.036 ±(99.9%) 0.907 ops/ms [Average]
  (min, avg, max) = (9.993, 10.036, 10.090), stdev = 0.050
  CI (99.9%): [9.129, 10.942] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:01
# Fork: 1 of 1
# Warmup Iteration   1: 6.974 ops/ms
# Warmup Iteration   2: 10.372 ops/ms
# Warmup Iteration   3: 11.004 ops/ms
Iteration   1: 10.907 ops/ms
Iteration   2: 11.026 ops/ms
Iteration   3: 10.876 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.936 ±(99.9%) 1.442 ops/ms [Average]
  (min, avg, max) = (10.876, 10.936, 11.026), stdev = 0.079
  CI (99.9%): [9.494, 12.378] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:54
# Fork: 1 of 1
# Warmup Iteration   1: 6.691 ops/ms
# Warmup Iteration   2: 10.096 ops/ms
# Warmup Iteration   3: 10.313 ops/ms
Iteration   1: 10.207 ops/ms
Iteration   2: 10.615 ops/ms
Iteration   3: 10.562 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.462 ±(99.9%) 4.048 ops/ms [Average]
  (min, avg, max) = (10.207, 10.462, 10.615), stdev = 0.222
  CI (99.9%): [6.414, 14.509] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 5.187 ops/ms
# Warmup Iteration   2: 7.639 ops/ms
# Warmup Iteration   3: 7.937 ops/ms
Iteration   1: 7.695 ops/ms
Iteration   2: 7.742 ops/ms
Iteration   3: 8.050 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.829 ±(99.9%) 3.522 ops/ms [Average]
  (min, avg, max) = (7.695, 7.829, 8.050), stdev = 0.193
  CI (99.9%): [4.307, 11.351] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 4.309 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.213 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.092 ±(99.9%) 0.002 ms/op
Iteration   1: 3.040 ±(99.9%) 0.002 ms/op
Iteration   2: 3.053 ±(99.9%) 0.001 ms/op
Iteration   3: 3.051 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.048 ±(99.9%) 0.128 ms/op [Average]
  (min, avg, max) = (3.040, 3.048, 3.053), stdev = 0.007
  CI (99.9%): [2.920, 3.176] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.125 ±(99.9%) 0.065 ms/op
# Warmup Iteration   2: 3.069 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.941 ±(99.9%) 0.003 ms/op
Iteration   1: 2.907 ±(99.9%) 0.002 ms/op
Iteration   2: 2.837 ±(99.9%) 0.003 ms/op
Iteration   3: 2.916 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.887 ±(99.9%) 0.788 ms/op [Average]
  (min, avg, max) = (2.837, 2.887, 2.916), stdev = 0.043
  CI (99.9%): [2.099, 3.675] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.232 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.158 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.115 ±(99.9%) 0.003 ms/op
Iteration   1: 3.034 ±(99.9%) 0.002 ms/op
Iteration   2: 3.068 ±(99.9%) 0.002 ms/op
Iteration   3: 3.062 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.055 ±(99.9%) 0.334 ms/op [Average]
  (min, avg, max) = (3.034, 3.055, 3.068), stdev = 0.018
  CI (99.9%): [2.721, 3.389] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.523 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 4.205 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.084 ±(99.9%) 0.012 ms/op
Iteration   1: 4.032 ±(99.9%) 0.026 ms/op
Iteration   2: 4.022 ±(99.9%) 0.013 ms/op
Iteration   3: 4.045 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.033 ±(99.9%) 0.215 ms/op [Average]
  (min, avg, max) = (4.022, 4.033, 4.045), stdev = 0.012
  CI (99.9%): [3.818, 4.248] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.354 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.186 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.014 ±(99.9%) 0.005 ms/op
Iteration   1: 3.008 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.782 ms/op
                 createUser·p0.50:   2.990 ms/op
                 createUser·p0.90:   3.559 ms/op
                 createUser·p0.95:   3.924 ms/op
                 createUser·p0.99:   4.833 ms/op
                 createUser·p0.999:  6.896 ms/op
                 createUser·p0.9999: 19.083 ms/op
                 createUser·p1.00:   19.431 ms/op

Iteration   2: 3.035 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.946 ms/op
                 createUser·p0.50:   2.998 ms/op
                 createUser·p0.90:   3.531 ms/op
                 createUser·p0.95:   3.772 ms/op
                 createUser·p0.99:   4.399 ms/op
                 createUser·p0.999:  7.840 ms/op
                 createUser·p0.9999: 15.465 ms/op
                 createUser·p1.00:   15.811 ms/op

Iteration   3: 3.019 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.624 ms/op
                 createUser·p0.50:   2.994 ms/op
                 createUser·p0.90:   3.551 ms/op
                 createUser·p0.95:   3.797 ms/op
                 createUser·p0.99:   4.448 ms/op
                 createUser·p0.999:  8.330 ms/op
                 createUser·p0.9999: 16.577 ms/op
                 createUser·p1.00:   17.072 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 317844
  mean =      3.020 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 894 
    [ 1.250,  2.500) = 25359 
    [ 2.500,  3.750) = 272740 
    [ 3.750,  5.000) = 17283 
    [ 5.000,  6.250) = 1010 
    [ 6.250,  7.500) = 221 
    [ 7.500,  8.750) = 104 
    [ 8.750, 10.000) = 9 
    [10.000, 11.250) = 24 
    [11.250, 12.500) = 37 
    [12.500, 13.750) = 19 
    [13.750, 15.000) = 35 
    [15.000, 16.250) = 53 
    [16.250, 17.500) = 24 
    [17.500, 18.750) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.624 ms/op
     p(50.0000) =      2.994 ms/op
     p(90.0000) =      3.547 ms/op
     p(95.0000) =      3.822 ms/op
     p(99.0000) =      4.620 ms/op
     p(99.9000) =      7.662 ms/op
     p(99.9900) =     18.645 ms/op
     p(99.9990) =     19.327 ms/op
     p(99.9999) =     19.431 ms/op
    p(100.0000) =     19.431 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 3.908 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.062 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.900 ±(99.9%) 0.005 ms/op
Iteration   1: 2.992 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.908 ms/op
                 existUser·p0.50:   2.957 ms/op
                 existUser·p0.90:   3.510 ms/op
                 existUser·p0.95:   3.674 ms/op
                 existUser·p0.99:   4.051 ms/op
                 existUser·p0.999:  6.360 ms/op
                 existUser·p0.9999: 12.637 ms/op
                 existUser·p1.00:   12.943 ms/op

Iteration   2: 2.965 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.822 ms/op
                 existUser·p0.50:   2.916 ms/op
                 existUser·p0.90:   3.506 ms/op
                 existUser·p0.95:   3.686 ms/op
                 existUser·p0.99:   4.428 ms/op
                 existUser·p0.999:  6.905 ms/op
                 existUser·p0.9999: 14.933 ms/op
                 existUser·p1.00:   15.401 ms/op

Iteration   3: 2.944 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.671 ms/op
                 existUser·p0.50:   2.920 ms/op
                 existUser·p0.90:   3.424 ms/op
                 existUser·p0.95:   3.588 ms/op
                 existUser·p0.99:   4.153 ms/op
                 existUser·p0.999:  7.000 ms/op
                 existUser·p0.9999: 15.846 ms/op
                 existUser·p1.00:   16.302 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 323282
  mean =      2.967 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 769 
    [ 1.250,  2.500) = 30438 
    [ 2.500,  3.750) = 281614 
    [ 3.750,  5.000) = 9466 
    [ 5.000,  6.250) = 544 
    [ 6.250,  7.500) = 196 
    [ 7.500,  8.750) = 49 
    [ 8.750, 10.000) = 13 
    [10.000, 11.250) = 2 
    [11.250, 12.500) = 38 
    [12.500, 13.750) = 59 
    [13.750, 15.000) = 68 
    [15.000, 16.250) = 25 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.671 ms/op
     p(50.0000) =      2.929 ms/op
     p(90.0000) =      3.478 ms/op
     p(95.0000) =      3.658 ms/op
     p(99.0000) =      4.219 ms/op
     p(99.9000) =      6.660 ms/op
     p(99.9900) =     14.850 ms/op
     p(99.9990) =     16.053 ms/op
     p(99.9999) =     16.302 ms/op
    p(100.0000) =     16.302 ms/op


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
# Warmup Iteration   1: 3.897 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.187 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.062 ±(99.9%) 0.006 ms/op
Iteration   1: 3.043 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.891 ms/op
                 getUser·p0.50:   2.998 ms/op
                 getUser·p0.90:   3.580 ms/op
                 getUser·p0.95:   3.834 ms/op
                 getUser·p0.99:   4.628 ms/op
                 getUser·p0.999:  7.782 ms/op
                 getUser·p0.9999: 22.118 ms/op
                 getUser·p1.00:   22.512 ms/op

Iteration   2: 3.018 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.851 ms/op
                 getUser·p0.50:   2.990 ms/op
                 getUser·p0.90:   3.490 ms/op
                 getUser·p0.95:   3.723 ms/op
                 getUser·p0.99:   4.366 ms/op
                 getUser·p0.999:  6.333 ms/op
                 getUser·p0.9999: 17.531 ms/op
                 getUser·p1.00:   18.022 ms/op

Iteration   3: 3.068 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.607 ms/op
                 getUser·p0.50:   3.019 ms/op
                 getUser·p0.90:   3.592 ms/op
                 getUser·p0.95:   3.817 ms/op
                 getUser·p0.99:   4.686 ms/op
                 getUser·p0.999:  8.699 ms/op
                 getUser·p0.9999: 25.563 ms/op
                 getUser·p1.00:   26.640 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 315343
  mean =      3.043 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19984 
    [ 2.500,  5.000) = 293783 
    [ 5.000,  7.500) = 1176 
    [ 7.500, 10.000) = 175 
    [10.000, 12.500) = 54 
    [12.500, 15.000) = 11 
    [15.000, 17.500) = 71 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 29 

  Percentiles, ms/op:
      p(0.0000) =      0.607 ms/op
     p(50.0000) =      3.002 ms/op
     p(90.0000) =      3.555 ms/op
     p(95.0000) =      3.793 ms/op
     p(99.0000) =      4.571 ms/op
     p(99.9000) =      8.061 ms/op
     p(99.9900) =     24.019 ms/op
     p(99.9990) =     26.565 ms/op
     p(99.9999) =     26.640 ms/op
    p(100.0000) =     26.640 ms/op


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
# Warmup Iteration   1: 5.456 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 4.105 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.053 ±(99.9%) 0.011 ms/op
Iteration   1: 4.033 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.124 ms/op
                 listUser·p0.50:   3.875 ms/op
                 listUser·p0.90:   5.038 ms/op
                 listUser·p0.95:   5.562 ms/op
                 listUser·p0.99:   6.922 ms/op
                 listUser·p0.999:  15.405 ms/op
                 listUser·p0.9999: 21.529 ms/op
                 listUser·p1.00:   21.889 ms/op

Iteration   2: 4.072 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.848 ms/op
                 listUser·p0.50:   3.912 ms/op
                 listUser·p0.90:   4.940 ms/op
                 listUser·p0.95:   5.620 ms/op
                 listUser·p0.99:   7.176 ms/op
                 listUser·p0.999:  15.395 ms/op
                 listUser·p0.9999: 21.636 ms/op
                 listUser·p1.00:   22.675 ms/op

Iteration   3: 4.021 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.537 ms/op
                 listUser·p0.50:   3.846 ms/op
                 listUser·p0.90:   5.063 ms/op
                 listUser·p0.95:   5.833 ms/op
                 listUser·p0.99:   7.242 ms/op
                 listUser·p0.999:  17.671 ms/op
                 listUser·p0.9999: 23.137 ms/op
                 listUser·p1.00:   24.543 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 237732
  mean =      4.042 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1799 
    [ 2.500,  5.000) = 211718 
    [ 5.000,  7.500) = 22556 
    [ 7.500, 10.000) = 1146 
    [10.000, 12.500) = 108 
    [12.500, 15.000) = 83 
    [15.000, 17.500) = 206 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 57 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.537 ms/op
     p(50.0000) =      3.879 ms/op
     p(90.0000) =      5.022 ms/op
     p(95.0000) =      5.669 ms/op
     p(99.0000) =      7.102 ms/op
     p(99.9000) =     15.925 ms/op
     p(99.9900) =     22.978 ms/op
     p(99.9990) =     23.568 ms/op
     p(99.9999) =     24.543 ms/op
    p(100.0000) =     24.543 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.036 ± 0.907  ops/ms
ClientGrpc.existUser                       thrpt       3  10.936 ± 1.442  ops/ms
ClientGrpc.getUser                         thrpt       3  10.462 ± 4.048  ops/ms
ClientGrpc.listUser                        thrpt       3   7.829 ± 3.522  ops/ms
ClientGrpc.createUser                       avgt       3   3.048 ± 0.128   ms/op
ClientGrpc.existUser                        avgt       3   2.887 ± 0.788   ms/op
ClientGrpc.getUser                          avgt       3   3.055 ± 0.334   ms/op
ClientGrpc.listUser                         avgt       3   4.033 ± 0.215   ms/op
ClientGrpc.createUser                     sample  317844   3.020 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.624           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.994           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.547           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.822           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.620           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.662           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.645           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          19.431           ms/op
ClientGrpc.existUser                      sample  323282   2.967 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.671           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.929           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.478           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.658           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.219           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.660           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.850           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          16.302           ms/op
ClientGrpc.getUser                        sample  315343   3.043 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.607           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.002           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.555           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.793           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.571           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.061           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          24.019           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          26.640           ms/op
ClientGrpc.listUser                       sample  237732   4.042 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.537           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.879           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.022           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.669           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.102           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.925           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.978           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.543           ms/op
