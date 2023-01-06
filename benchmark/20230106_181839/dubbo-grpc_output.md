# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.861 ops/ms
# Warmup Iteration   2: 9.482 ops/ms
# Warmup Iteration   3: 10.254 ops/ms
Iteration   1: 10.311 ops/ms
Iteration   2: 10.630 ops/ms
Iteration   3: 10.120 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.354 ±(99.9%) 4.703 ops/ms [Average]
  (min, avg, max) = (10.120, 10.354, 10.630), stdev = 0.258
  CI (99.9%): [5.651, 15.056] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 8.027 ops/ms
# Warmup Iteration   2: 10.749 ops/ms
# Warmup Iteration   3: 10.858 ops/ms
Iteration   1: 10.896 ops/ms
Iteration   2: 10.890 ops/ms
Iteration   3: 11.050 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.945 ±(99.9%) 1.658 ops/ms [Average]
  (min, avg, max) = (10.890, 10.945, 11.050), stdev = 0.091
  CI (99.9%): [9.288, 12.603] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.443 ops/ms
# Warmup Iteration   2: 10.485 ops/ms
# Warmup Iteration   3: 10.502 ops/ms
Iteration   1: 10.416 ops/ms
Iteration   2: 10.396 ops/ms
Iteration   3: 10.702 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.505 ±(99.9%) 3.124 ops/ms [Average]
  (min, avg, max) = (10.396, 10.505, 10.702), stdev = 0.171
  CI (99.9%): [7.381, 13.629] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 5.668 ops/ms
# Warmup Iteration   2: 7.852 ops/ms
# Warmup Iteration   3: 7.895 ops/ms
Iteration   1: 7.945 ops/ms
Iteration   2: 8.009 ops/ms
Iteration   3: 8.064 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.006 ±(99.9%) 1.086 ops/ms [Average]
  (min, avg, max) = (7.945, 8.006, 8.064), stdev = 0.060
  CI (99.9%): [6.920, 9.092] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 3.773 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.100 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.100 ±(99.9%) 0.002 ms/op
Iteration   1: 3.072 ±(99.9%) 0.001 ms/op
Iteration   2: 3.135 ±(99.9%) 0.002 ms/op
Iteration   3: 3.095 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.101 ±(99.9%) 0.587 ms/op [Average]
  (min, avg, max) = (3.072, 3.101, 3.135), stdev = 0.032
  CI (99.9%): [2.514, 3.687] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.472 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.000 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.935 ±(99.9%) 0.002 ms/op
Iteration   1: 2.886 ±(99.9%) 0.003 ms/op
Iteration   2: 2.948 ±(99.9%) 0.002 ms/op
Iteration   3: 2.988 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.940 ±(99.9%) 0.931 ms/op [Average]
  (min, avg, max) = (2.886, 2.940, 2.988), stdev = 0.051
  CI (99.9%): [2.009, 3.872] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.922 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.070 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.029 ±(99.9%) 0.002 ms/op
Iteration   1: 3.083 ±(99.9%) 0.002 ms/op
Iteration   2: 2.947 ±(99.9%) 0.002 ms/op
Iteration   3: 3.079 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.036 ±(99.9%) 1.415 ms/op [Average]
  (min, avg, max) = (2.947, 3.036, 3.083), stdev = 0.078
  CI (99.9%): [1.621, 4.452] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 3.912 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 4.164 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.014 ±(99.9%) 0.011 ms/op
Iteration   1: 3.974 ±(99.9%) 0.028 ms/op
Iteration   2: 4.033 ±(99.9%) 0.013 ms/op
Iteration   3: 4.004 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.004 ±(99.9%) 0.537 ms/op [Average]
  (min, avg, max) = (3.974, 4.004, 4.033), stdev = 0.029
  CI (99.9%): [3.467, 4.540] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.032 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.125 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.031 ±(99.9%) 0.006 ms/op
Iteration   1: 3.048 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.566 ms/op
                 createUser·p0.50:   3.039 ms/op
                 createUser·p0.90:   3.695 ms/op
                 createUser·p0.95:   3.916 ms/op
                 createUser·p0.99:   4.284 ms/op
                 createUser·p0.999:  6.883 ms/op
                 createUser·p0.9999: 18.579 ms/op
                 createUser·p1.00:   18.940 ms/op

Iteration   2: 3.138 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.482 ms/op
                 createUser·p0.50:   3.121 ms/op
                 createUser·p0.90:   3.822 ms/op
                 createUser·p0.95:   4.018 ms/op
                 createUser·p0.99:   4.317 ms/op
                 createUser·p0.999:  7.915 ms/op
                 createUser·p0.9999: 19.104 ms/op
                 createUser·p1.00:   19.497 ms/op

Iteration   3: 3.107 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.703 ms/op
                 createUser·p0.50:   3.092 ms/op
                 createUser·p0.90:   3.756 ms/op
                 createUser·p0.95:   3.924 ms/op
                 createUser·p0.99:   4.227 ms/op
                 createUser·p0.999:  7.232 ms/op
                 createUser·p0.9999: 14.528 ms/op
                 createUser·p1.00:   15.008 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 309719
  mean =      3.097 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1117 
    [ 1.250,  2.500) = 28817 
    [ 2.500,  3.750) = 247451 
    [ 3.750,  5.000) = 31525 
    [ 5.000,  6.250) = 387 
    [ 6.250,  7.500) = 123 
    [ 7.500,  8.750) = 71 
    [ 8.750, 10.000) = 6 
    [10.000, 11.250) = 21 
    [11.250, 12.500) = 42 
    [12.500, 13.750) = 39 
    [13.750, 15.000) = 55 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 38 

  Percentiles, ms/op:
      p(0.0000) =      0.482 ms/op
     p(50.0000) =      3.080 ms/op
     p(90.0000) =      3.764 ms/op
     p(95.0000) =      3.953 ms/op
     p(99.0000) =      4.284 ms/op
     p(99.9000) =      7.380 ms/op
     p(99.9900) =     18.711 ms/op
     p(99.9990) =     19.395 ms/op
     p(99.9999) =     19.497 ms/op
    p(100.0000) =     19.497 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.710 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 2.944 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.953 ±(99.9%) 0.006 ms/op
Iteration   1: 2.983 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.666 ms/op
                 existUser·p0.50:   2.970 ms/op
                 existUser·p0.90:   3.670 ms/op
                 existUser·p0.95:   3.854 ms/op
                 existUser·p0.99:   4.202 ms/op
                 existUser·p0.999:  5.961 ms/op
                 existUser·p0.9999: 11.215 ms/op
                 existUser·p1.00:   11.567 ms/op

Iteration   2: 2.906 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.674 ms/op
                 existUser·p0.50:   2.908 ms/op
                 existUser·p0.90:   3.473 ms/op
                 existUser·p0.95:   3.674 ms/op
                 existUser·p0.99:   4.190 ms/op
                 existUser·p0.999:  8.004 ms/op
                 existUser·p0.9999: 13.238 ms/op
                 existUser·p1.00:   13.451 ms/op

Iteration   3: 2.955 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.734 ms/op
                 existUser·p0.50:   2.908 ms/op
                 existUser·p0.90:   3.592 ms/op
                 existUser·p0.95:   3.789 ms/op
                 existUser·p0.99:   4.283 ms/op
                 existUser·p0.999:  11.026 ms/op
                 existUser·p0.9999: 14.296 ms/op
                 existUser·p1.00:   14.549 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 325783
  mean =      2.948 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2290 
    [ 1.250,  2.500) = 47168 
    [ 2.500,  3.750) = 257634 
    [ 3.750,  5.000) = 17705 
    [ 5.000,  6.250) = 507 
    [ 6.250,  7.500) = 130 
    [ 7.500,  8.750) = 35 
    [ 8.750, 10.000) = 63 
    [10.000, 11.250) = 76 
    [11.250, 12.500) = 46 
    [12.500, 13.750) = 93 
    [13.750, 15.000) = 36 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.666 ms/op
     p(50.0000) =      2.929 ms/op
     p(90.0000) =      3.584 ms/op
     p(95.0000) =      3.785 ms/op
     p(99.0000) =      4.219 ms/op
     p(99.9000) =      8.227 ms/op
     p(99.9900) =     13.851 ms/op
     p(99.9990) =     14.504 ms/op
     p(99.9999) =     14.549 ms/op
    p(100.0000) =     14.549 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.059 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.128 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.021 ±(99.9%) 0.007 ms/op
Iteration   1: 3.038 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.642 ms/op
                 getUser·p0.50:   3.027 ms/op
                 getUser·p0.90:   3.559 ms/op
                 getUser·p0.95:   3.740 ms/op
                 getUser·p0.99:   4.194 ms/op
                 getUser·p0.999:  7.025 ms/op
                 getUser·p0.9999: 14.998 ms/op
                 getUser·p1.00:   15.434 ms/op

Iteration   2: 3.037 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.780 ms/op
                 getUser·p0.50:   3.019 ms/op
                 getUser·p0.90:   3.555 ms/op
                 getUser·p0.95:   3.809 ms/op
                 getUser·p0.99:   4.182 ms/op
                 getUser·p0.999:  7.122 ms/op
                 getUser·p0.9999: 16.448 ms/op
                 getUser·p1.00:   16.695 ms/op

Iteration   3: 3.010 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.698 ms/op
                 getUser·p0.50:   3.002 ms/op
                 getUser·p0.90:   3.502 ms/op
                 getUser·p0.95:   3.690 ms/op
                 getUser·p0.99:   4.116 ms/op
                 getUser·p0.999:  5.900 ms/op
                 getUser·p0.9999: 19.796 ms/op
                 getUser·p1.00:   20.775 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 316767
  mean =      3.029 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23693 
    [ 2.500,  5.000) = 292255 
    [ 5.000,  7.500) = 573 
    [ 7.500, 10.000) = 49 
    [10.000, 12.500) = 5 
    [12.500, 15.000) = 63 
    [15.000, 17.500) = 97 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.642 ms/op
     p(50.0000) =      3.015 ms/op
     p(90.0000) =      3.539 ms/op
     p(95.0000) =      3.748 ms/op
     p(99.0000) =      4.170 ms/op
     p(99.9000) =      6.728 ms/op
     p(99.9900) =     17.869 ms/op
     p(99.9990) =     20.632 ms/op
     p(99.9999) =     20.775 ms/op
    p(100.0000) =     20.775 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.053 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 4.150 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.964 ±(99.9%) 0.010 ms/op
Iteration   1: 4.011 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.884 ms/op
                 listUser·p0.50:   3.838 ms/op
                 listUser·p0.90:   5.112 ms/op
                 listUser·p0.95:   5.767 ms/op
                 listUser·p0.99:   6.914 ms/op
                 listUser·p0.999:  11.358 ms/op
                 listUser·p0.9999: 18.908 ms/op
                 listUser·p1.00:   19.202 ms/op

Iteration   2: 4.094 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.693 ms/op
                 listUser·p0.50:   3.924 ms/op
                 listUser·p0.90:   5.251 ms/op
                 listUser·p0.95:   5.603 ms/op
                 listUser·p0.99:   6.881 ms/op
                 listUser·p0.999:  12.468 ms/op
                 listUser·p0.9999: 15.302 ms/op
                 listUser·p1.00:   16.253 ms/op

Iteration   3: 4.050 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.836 ms/op
                 listUser·p0.50:   3.879 ms/op
                 listUser·p0.90:   5.136 ms/op
                 listUser·p0.95:   5.808 ms/op
                 listUser·p0.99:   6.939 ms/op
                 listUser·p0.999:  14.567 ms/op
                 listUser·p0.9999: 22.846 ms/op
                 listUser·p1.00:   24.117 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 236833
  mean =      4.051 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3241 
    [ 2.500,  5.000) = 203849 
    [ 5.000,  7.500) = 28443 
    [ 7.500, 10.000) = 845 
    [10.000, 12.500) = 167 
    [12.500, 15.000) = 178 
    [15.000, 17.500) = 22 
    [17.500, 20.000) = 47 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.693 ms/op
     p(50.0000) =      3.879 ms/op
     p(90.0000) =      5.177 ms/op
     p(95.0000) =      5.718 ms/op
     p(99.0000) =      6.914 ms/op
     p(99.9000) =     13.402 ms/op
     p(99.9900) =     21.637 ms/op
     p(99.9990) =     23.208 ms/op
     p(99.9999) =     24.117 ms/op
    p(100.0000) =     24.117 ms/op


# Run complete. Total time: 00:13:02

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.354 ± 4.703  ops/ms
ClientGrpc.existUser                       thrpt       3  10.945 ± 1.658  ops/ms
ClientGrpc.getUser                         thrpt       3  10.505 ± 3.124  ops/ms
ClientGrpc.listUser                        thrpt       3   8.006 ± 1.086  ops/ms
ClientGrpc.createUser                       avgt       3   3.101 ± 0.587   ms/op
ClientGrpc.existUser                        avgt       3   2.940 ± 0.931   ms/op
ClientGrpc.getUser                          avgt       3   3.036 ± 1.415   ms/op
ClientGrpc.listUser                         avgt       3   4.004 ± 0.537   ms/op
ClientGrpc.createUser                     sample  309719   3.097 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.482           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.080           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.764           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.953           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.284           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.380           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.711           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          19.497           ms/op
ClientGrpc.existUser                      sample  325783   2.948 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.666           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.929           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.584           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.785           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.219           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.227           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          13.851           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          14.549           ms/op
ClientGrpc.getUser                        sample  316767   3.029 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.642           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.015           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.539           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.748           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.170           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.728           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.869           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.775           ms/op
ClientGrpc.listUser                       sample  236833   4.051 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.693           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.879           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.177           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.718           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.914           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.402           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.637           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.117           ms/op
