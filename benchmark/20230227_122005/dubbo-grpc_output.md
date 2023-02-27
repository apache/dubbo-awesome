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
# Warmup Iteration   1: 5.041 ops/ms
# Warmup Iteration   2: 9.438 ops/ms
# Warmup Iteration   3: 10.739 ops/ms
Iteration   1: 10.515 ops/ms
Iteration   2: 10.341 ops/ms
Iteration   3: 10.083 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.313 ±(99.9%) 3.966 ops/ms [Average]
  (min, avg, max) = (10.083, 10.313, 10.515), stdev = 0.217
  CI (99.9%): [6.347, 14.279] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 9.699 ops/ms
# Warmup Iteration   2: 10.900 ops/ms
# Warmup Iteration   3: 11.141 ops/ms
Iteration   1: 11.290 ops/ms
Iteration   2: 10.943 ops/ms
Iteration   3: 10.810 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.014 ±(99.9%) 4.517 ops/ms [Average]
  (min, avg, max) = (10.810, 11.014, 11.290), stdev = 0.248
  CI (99.9%): [6.497, 15.532] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.441 ops/ms
# Warmup Iteration   2: 10.260 ops/ms
# Warmup Iteration   3: 10.590 ops/ms
Iteration   1: 10.611 ops/ms
Iteration   2: 10.424 ops/ms
Iteration   3: 10.183 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.406 ±(99.9%) 3.915 ops/ms [Average]
  (min, avg, max) = (10.183, 10.406, 10.611), stdev = 0.215
  CI (99.9%): [6.490, 14.321] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.858 ops/ms
# Warmup Iteration   2: 7.735 ops/ms
# Warmup Iteration   3: 7.779 ops/ms
Iteration   1: 7.963 ops/ms
Iteration   2: 7.969 ops/ms
Iteration   3: 8.019 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.984 ±(99.9%) 0.561 ops/ms [Average]
  (min, avg, max) = (7.963, 7.984, 8.019), stdev = 0.031
  CI (99.9%): [7.423, 8.545] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.770 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.089 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.032 ±(99.9%) 0.009 ms/op
Iteration   1: 3.032 ±(99.9%) 0.003 ms/op
Iteration   2: 3.149 ±(99.9%) 0.002 ms/op
Iteration   3: 3.114 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.098 ±(99.9%) 1.098 ms/op [Average]
  (min, avg, max) = (3.032, 3.098, 3.149), stdev = 0.060
  CI (99.9%): [2.000, 4.197] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.621 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.985 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.969 ±(99.9%) 0.007 ms/op
Iteration   1: 2.906 ±(99.9%) 0.008 ms/op
Iteration   2: 2.913 ±(99.9%) 0.004 ms/op
Iteration   3: 2.997 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.939 ±(99.9%) 0.919 ms/op [Average]
  (min, avg, max) = (2.906, 2.939, 2.997), stdev = 0.050
  CI (99.9%): [2.019, 3.858] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.972 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.207 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.090 ±(99.9%) 0.003 ms/op
Iteration   1: 3.139 ±(99.9%) 0.003 ms/op
Iteration   2: 3.044 ±(99.9%) 0.003 ms/op
Iteration   3: 3.110 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.098 ±(99.9%) 0.888 ms/op [Average]
  (min, avg, max) = (3.044, 3.098, 3.139), stdev = 0.049
  CI (99.9%): [2.209, 3.986] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 5.071 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 4.049 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 3.924 ±(99.9%) 0.018 ms/op
Iteration   1: 3.915 ±(99.9%) 0.009 ms/op
Iteration   2: 3.900 ±(99.9%) 0.004 ms/op
Iteration   3: 3.826 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.880 ±(99.9%) 0.870 ms/op [Average]
  (min, avg, max) = (3.826, 3.880, 3.915), stdev = 0.048
  CI (99.9%): [3.011, 4.750] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.064 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.144 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.097 ±(99.9%) 0.006 ms/op
Iteration   1: 3.049 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.644 ms/op
                 createUser·p0.50:   3.035 ms/op
                 createUser·p0.90:   3.670 ms/op
                 createUser·p0.95:   3.899 ms/op
                 createUser·p0.99:   4.407 ms/op
                 createUser·p0.999:  9.294 ms/op
                 createUser·p0.9999: 11.757 ms/op
                 createUser·p1.00:   12.288 ms/op

Iteration   2: 2.992 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.521 ms/op
                 createUser·p0.50:   3.052 ms/op
                 createUser·p0.90:   3.547 ms/op
                 createUser·p0.95:   3.756 ms/op
                 createUser·p0.99:   4.235 ms/op
                 createUser·p0.999:  6.119 ms/op
                 createUser·p0.9999: 12.838 ms/op
                 createUser·p1.00:   14.123 ms/op

Iteration   3: 3.152 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.682 ms/op
                 createUser·p0.50:   3.142 ms/op
                 createUser·p0.90:   3.838 ms/op
                 createUser·p0.95:   3.990 ms/op
                 createUser·p0.99:   4.260 ms/op
                 createUser·p0.999:  9.735 ms/op
                 createUser·p0.9999: 25.245 ms/op
                 createUser·p1.00:   25.919 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 313354
  mean =      3.063 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 30552 
    [ 2.500,  5.000) = 281809 
    [ 5.000,  7.500) = 590 
    [ 7.500, 10.000) = 165 
    [10.000, 12.500) = 114 
    [12.500, 15.000) = 79 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      0.521 ms/op
     p(50.0000) =      3.064 ms/op
     p(90.0000) =      3.703 ms/op
     p(95.0000) =      3.912 ms/op
     p(99.0000) =      4.284 ms/op
     p(99.9000) =      8.579 ms/op
     p(99.9900) =     24.270 ms/op
     p(99.9990) =     25.817 ms/op
     p(99.9999) =     25.919 ms/op
    p(100.0000) =     25.919 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.867 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 2.963 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.955 ±(99.9%) 0.006 ms/op
Iteration   1: 2.838 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.607 ms/op
                 existUser·p0.50:   2.888 ms/op
                 existUser·p0.90:   3.441 ms/op
                 existUser·p0.95:   3.727 ms/op
                 existUser·p0.99:   4.293 ms/op
                 existUser·p0.999:  6.205 ms/op
                 existUser·p0.9999: 13.667 ms/op
                 existUser·p1.00:   14.123 ms/op

Iteration   2: 2.951 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.639 ms/op
                 existUser·p0.50:   2.929 ms/op
                 existUser·p0.90:   3.543 ms/op
                 existUser·p0.95:   3.736 ms/op
                 existUser·p0.99:   4.170 ms/op
                 existUser·p0.999:  6.628 ms/op
                 existUser·p0.9999: 14.573 ms/op
                 existUser·p1.00:   15.041 ms/op

Iteration   3: 2.968 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.618 ms/op
                 existUser·p0.50:   2.941 ms/op
                 existUser·p0.90:   3.535 ms/op
                 existUser·p0.95:   3.736 ms/op
                 existUser·p0.99:   4.084 ms/op
                 existUser·p0.999:  7.676 ms/op
                 existUser·p0.9999: 26.957 ms/op
                 existUser·p1.00:   27.296 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 329085
  mean =      2.918 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 49579 
    [ 2.500,  5.000) = 278829 
    [ 5.000,  7.500) = 446 
    [ 7.500, 10.000) = 70 
    [10.000, 12.500) = 12 
    [12.500, 15.000) = 84 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.607 ms/op
     p(50.0000) =      2.920 ms/op
     p(90.0000) =      3.510 ms/op
     p(95.0000) =      3.731 ms/op
     p(99.0000) =      4.182 ms/op
     p(99.9000) =      6.815 ms/op
     p(99.9900) =     18.681 ms/op
     p(99.9990) =     27.211 ms/op
     p(99.9999) =     27.296 ms/op
    p(100.0000) =     27.296 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.962 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.174 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.109 ±(99.9%) 0.006 ms/op
Iteration   1: 3.061 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.677 ms/op
                 getUser·p0.50:   3.064 ms/op
                 getUser·p0.90:   3.719 ms/op
                 getUser·p0.95:   3.891 ms/op
                 getUser·p0.99:   4.284 ms/op
                 getUser·p0.999:  7.304 ms/op
                 getUser·p0.9999: 12.241 ms/op
                 getUser·p1.00:   12.714 ms/op

Iteration   2: 2.979 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.528 ms/op
                 getUser·p0.50:   2.990 ms/op
                 getUser·p0.90:   3.523 ms/op
                 getUser·p0.95:   3.760 ms/op
                 getUser·p0.99:   4.366 ms/op
                 getUser·p0.999:  5.669 ms/op
                 getUser·p0.9999: 12.771 ms/op
                 getUser·p1.00:   13.091 ms/op

Iteration   3: 3.011 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.336 ms/op
                 getUser·p0.50:   3.015 ms/op
                 getUser·p0.90:   3.535 ms/op
                 getUser·p0.95:   3.744 ms/op
                 getUser·p0.99:   4.301 ms/op
                 getUser·p0.999:  7.247 ms/op
                 getUser·p0.9999: 15.141 ms/op
                 getUser·p1.00:   15.598 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 318354
  mean =      3.016 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1446 
    [ 1.250,  2.500) = 31526 
    [ 2.500,  3.750) = 265134 
    [ 3.750,  5.000) = 19435 
    [ 5.000,  6.250) = 385 
    [ 6.250,  7.500) = 173 
    [ 7.500,  8.750) = 41 
    [ 8.750, 10.000) = 42 
    [10.000, 11.250) = 39 
    [11.250, 12.500) = 42 
    [12.500, 13.750) = 42 
    [13.750, 15.000) = 35 
    [15.000, 16.250) = 14 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.336 ms/op
     p(50.0000) =      3.023 ms/op
     p(90.0000) =      3.604 ms/op
     p(95.0000) =      3.817 ms/op
     p(99.0000) =      4.317 ms/op
     p(99.9000) =      6.755 ms/op
     p(99.9900) =     14.156 ms/op
     p(99.9990) =     15.539 ms/op
     p(99.9999) =     15.598 ms/op
    p(100.0000) =     15.598 ms/op


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
# Warmup Iteration   1: 4.703 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 4.163 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.055 ±(99.9%) 0.012 ms/op
Iteration   1: 4.010 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.016 ms/op
                 listUser·p0.50:   3.826 ms/op
                 listUser·p0.90:   5.243 ms/op
                 listUser·p0.95:   5.767 ms/op
                 listUser·p0.99:   6.873 ms/op
                 listUser·p0.999:  11.415 ms/op
                 listUser·p0.9999: 15.242 ms/op
                 listUser·p1.00:   20.087 ms/op

Iteration   2: 3.984 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.706 ms/op
                 listUser·p0.50:   3.809 ms/op
                 listUser·p0.90:   5.120 ms/op
                 listUser·p0.95:   5.669 ms/op
                 listUser·p0.99:   6.767 ms/op
                 listUser·p0.999:  16.167 ms/op
                 listUser·p0.9999: 22.314 ms/op
                 listUser·p1.00:   23.626 ms/op

Iteration   3: 3.946 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.079 ms/op
                 listUser·p0.50:   3.817 ms/op
                 listUser·p0.90:   4.882 ms/op
                 listUser·p0.95:   5.652 ms/op
                 listUser·p0.99:   6.775 ms/op
                 listUser·p0.999:  16.089 ms/op
                 listUser·p0.9999: 21.001 ms/op
                 listUser·p1.00:   22.577 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 241105
  mean =      3.980 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4505 
    [ 2.500,  5.000) = 209116 
    [ 5.000,  7.500) = 26317 
    [ 7.500, 10.000) = 703 
    [10.000, 12.500) = 132 
    [12.500, 15.000) = 115 
    [15.000, 17.500) = 75 
    [17.500, 20.000) = 42 
    [20.000, 22.500) = 95 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.706 ms/op
     p(50.0000) =      3.817 ms/op
     p(90.0000) =      5.120 ms/op
     p(95.0000) =      5.702 ms/op
     p(99.0000) =      6.799 ms/op
     p(99.9000) =     14.627 ms/op
     p(99.9900) =     21.496 ms/op
     p(99.9990) =     23.154 ms/op
     p(99.9999) =     23.626 ms/op
    p(100.0000) =     23.626 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.313 ± 3.966  ops/ms
ClientGrpc.existUser                       thrpt       3  11.014 ± 4.517  ops/ms
ClientGrpc.getUser                         thrpt       3  10.406 ± 3.915  ops/ms
ClientGrpc.listUser                        thrpt       3   7.984 ± 0.561  ops/ms
ClientGrpc.createUser                       avgt       3   3.098 ± 1.098   ms/op
ClientGrpc.existUser                        avgt       3   2.939 ± 0.919   ms/op
ClientGrpc.getUser                          avgt       3   3.098 ± 0.888   ms/op
ClientGrpc.listUser                         avgt       3   3.880 ± 0.870   ms/op
ClientGrpc.createUser                     sample  313354   3.063 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.521           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.064           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.703           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.912           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.284           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.579           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          24.270           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          25.919           ms/op
ClientGrpc.existUser                      sample  329085   2.918 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.607           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.920           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.510           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.731           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.182           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.815           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.681           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          27.296           ms/op
ClientGrpc.getUser                        sample  318354   3.016 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.336           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.023           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.604           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.817           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.317           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.755           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          14.156           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          15.598           ms/op
ClientGrpc.listUser                       sample  241105   3.980 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.706           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.817           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.120           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.702           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.799           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.627           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.496           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.626           ms/op
