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
# Warmup Iteration   1: 5.327 ops/ms
# Warmup Iteration   2: 9.478 ops/ms
# Warmup Iteration   3: 10.435 ops/ms
Iteration   1: 10.695 ops/ms
Iteration   2: 10.346 ops/ms
Iteration   3: 10.346 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.462 ±(99.9%) 3.676 ops/ms [Average]
  (min, avg, max) = (10.346, 10.462, 10.695), stdev = 0.201
  CI (99.9%): [6.787, 14.138] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 7.859 ops/ms
# Warmup Iteration   2: 11.228 ops/ms
# Warmup Iteration   3: 10.861 ops/ms
Iteration   1: 10.835 ops/ms
Iteration   2: 10.573 ops/ms
Iteration   3: 10.631 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.680 ±(99.9%) 2.515 ops/ms [Average]
  (min, avg, max) = (10.573, 10.680, 10.835), stdev = 0.138
  CI (99.9%): [8.165, 13.194] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.968 ops/ms
# Warmup Iteration   2: 10.154 ops/ms
# Warmup Iteration   3: 10.393 ops/ms
Iteration   1: 10.250 ops/ms
Iteration   2: 10.207 ops/ms
Iteration   3: 10.408 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.288 ±(99.9%) 1.934 ops/ms [Average]
  (min, avg, max) = (10.207, 10.288, 10.408), stdev = 0.106
  CI (99.9%): [8.355, 12.222] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 7.525 ops/ms
# Warmup Iteration   2: 7.623 ops/ms
# Warmup Iteration   3: 8.031 ops/ms
Iteration   1: 7.871 ops/ms
Iteration   2: 7.941 ops/ms
Iteration   3: 8.122 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.978 ±(99.9%) 2.361 ops/ms [Average]
  (min, avg, max) = (7.871, 7.978, 8.122), stdev = 0.129
  CI (99.9%): [5.617, 10.339] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 4.071 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.086 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.065 ±(99.9%) 0.002 ms/op
Iteration   1: 3.067 ±(99.9%) 0.003 ms/op
Iteration   2: 3.050 ±(99.9%) 0.002 ms/op
Iteration   3: 3.025 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.047 ±(99.9%) 0.382 ms/op [Average]
  (min, avg, max) = (3.025, 3.047, 3.067), stdev = 0.021
  CI (99.9%): [2.665, 3.430] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.595 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.087 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.996 ±(99.9%) 0.006 ms/op
Iteration   1: 2.983 ±(99.9%) 0.002 ms/op
Iteration   2: 3.009 ±(99.9%) 0.002 ms/op
Iteration   3: 2.979 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.990 ±(99.9%) 0.299 ms/op [Average]
  (min, avg, max) = (2.979, 2.990, 3.009), stdev = 0.016
  CI (99.9%): [2.691, 3.289] (assumes normal distribution)


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
# Warmup Iteration   1: 3.738 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.119 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.020 ±(99.9%) 0.002 ms/op
Iteration   1: 3.098 ±(99.9%) 0.002 ms/op
Iteration   2: 3.047 ±(99.9%) 0.002 ms/op
Iteration   3: 3.117 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.088 ±(99.9%) 0.658 ms/op [Average]
  (min, avg, max) = (3.047, 3.088, 3.117), stdev = 0.036
  CI (99.9%): [2.429, 3.746] (assumes normal distribution)


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
# Warmup Iteration   1: 5.027 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 4.139 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 3.989 ±(99.9%) 0.022 ms/op
Iteration   1: 3.858 ±(99.9%) 0.013 ms/op
Iteration   2: 3.897 ±(99.9%) 0.003 ms/op
Iteration   3: 3.973 ±(99.9%) 0.033 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.910 ±(99.9%) 1.063 ms/op [Average]
  (min, avg, max) = (3.858, 3.910, 3.973), stdev = 0.058
  CI (99.9%): [2.846, 4.973] (assumes normal distribution)


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
# Warmup Iteration   1: 4.016 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.159 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.095 ±(99.9%) 0.006 ms/op
Iteration   1: 3.111 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.792 ms/op
                 createUser·p0.50:   3.088 ms/op
                 createUser·p0.90:   3.772 ms/op
                 createUser·p0.95:   3.961 ms/op
                 createUser·p0.99:   4.243 ms/op
                 createUser·p0.999:  6.662 ms/op
                 createUser·p0.9999: 16.534 ms/op
                 createUser·p1.00:   16.761 ms/op

Iteration   2: 3.137 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.678 ms/op
                 createUser·p0.50:   3.105 ms/op
                 createUser·p0.90:   3.789 ms/op
                 createUser·p0.95:   3.981 ms/op
                 createUser·p0.99:   4.284 ms/op
                 createUser·p0.999:  7.766 ms/op
                 createUser·p0.9999: 19.032 ms/op
                 createUser·p1.00:   19.530 ms/op

Iteration   3: 3.092 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.777 ms/op
                 createUser·p0.50:   3.088 ms/op
                 createUser·p0.90:   3.731 ms/op
                 createUser·p0.95:   3.903 ms/op
                 createUser·p0.99:   4.252 ms/op
                 createUser·p0.999:  6.061 ms/op
                 createUser·p0.9999: 20.010 ms/op
                 createUser·p1.00:   20.513 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 308197
  mean =      3.113 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24493 
    [ 2.500,  5.000) = 282816 
    [ 5.000,  7.500) = 598 
    [ 7.500, 10.000) = 66 
    [10.000, 12.500) = 28 
    [12.500, 15.000) = 36 
    [15.000, 17.500) = 79 
    [17.500, 20.000) = 71 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.678 ms/op
     p(50.0000) =      3.097 ms/op
     p(90.0000) =      3.764 ms/op
     p(95.0000) =      3.953 ms/op
     p(99.0000) =      4.260 ms/op
     p(99.9000) =      7.348 ms/op
     p(99.9900) =     18.842 ms/op
     p(99.9990) =     20.406 ms/op
     p(99.9999) =     20.513 ms/op
    p(100.0000) =     20.513 ms/op


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
# Warmup Iteration   1: 3.834 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 2.936 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.940 ±(99.9%) 0.006 ms/op
Iteration   1: 2.982 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.757 ms/op
                 existUser·p0.50:   2.978 ms/op
                 existUser·p0.90:   3.686 ms/op
                 existUser·p0.95:   3.883 ms/op
                 existUser·p0.99:   4.194 ms/op
                 existUser·p0.999:  5.730 ms/op
                 existUser·p0.9999: 11.794 ms/op
                 existUser·p1.00:   12.190 ms/op

Iteration   2: 3.026 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.646 ms/op
                 existUser·p0.50:   3.002 ms/op
                 existUser·p0.90:   3.719 ms/op
                 existUser·p0.95:   3.891 ms/op
                 existUser·p0.99:   4.219 ms/op
                 existUser·p0.999:  6.507 ms/op
                 existUser·p0.9999: 13.222 ms/op
                 existUser·p1.00:   13.418 ms/op

Iteration   3: 2.948 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.553 ms/op
                 existUser·p0.50:   2.912 ms/op
                 existUser·p0.90:   3.613 ms/op
                 existUser·p0.95:   3.854 ms/op
                 existUser·p0.99:   4.481 ms/op
                 existUser·p0.999:  7.079 ms/op
                 existUser·p0.9999: 18.785 ms/op
                 existUser·p1.00:   19.661 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 321468
  mean =      2.985 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1883 
    [ 1.250,  2.500) = 46083 
    [ 2.500,  3.750) = 247715 
    [ 3.750,  5.000) = 25008 
    [ 5.000,  6.250) = 426 
    [ 6.250,  7.500) = 120 
    [ 7.500,  8.750) = 69 
    [ 8.750, 10.000) = 3 
    [10.000, 11.250) = 11 
    [11.250, 12.500) = 47 
    [12.500, 13.750) = 52 
    [13.750, 15.000) = 8 
    [15.000, 16.250) = 11 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 17 

  Percentiles, ms/op:
      p(0.0000) =      0.553 ms/op
     p(50.0000) =      2.961 ms/op
     p(90.0000) =      3.678 ms/op
     p(95.0000) =      3.879 ms/op
     p(99.0000) =      4.268 ms/op
     p(99.9000) =      6.636 ms/op
     p(99.9900) =     17.873 ms/op
     p(99.9990) =     19.122 ms/op
     p(99.9999) =     19.661 ms/op
    p(100.0000) =     19.661 ms/op


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
# Warmup Iteration   1: 3.953 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.095 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.062 ±(99.9%) 0.007 ms/op
Iteration   1: 3.090 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.568 ms/op
                 getUser·p0.50:   3.068 ms/op
                 getUser·p0.90:   3.715 ms/op
                 getUser·p0.95:   3.908 ms/op
                 getUser·p0.99:   4.293 ms/op
                 getUser·p0.999:  9.013 ms/op
                 getUser·p0.9999: 13.298 ms/op
                 getUser·p1.00:   13.550 ms/op

Iteration   2: 3.038 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.686 ms/op
                 getUser·p0.50:   3.047 ms/op
                 getUser·p0.90:   3.592 ms/op
                 getUser·p0.95:   3.801 ms/op
                 getUser·p0.99:   4.219 ms/op
                 getUser·p0.999:  6.419 ms/op
                 getUser·p0.9999: 12.369 ms/op
                 getUser·p1.00:   12.648 ms/op

Iteration   3: 3.031 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.709 ms/op
                 getUser·p0.50:   3.023 ms/op
                 getUser·p0.90:   3.666 ms/op
                 getUser·p0.95:   3.863 ms/op
                 getUser·p0.99:   4.235 ms/op
                 getUser·p0.999:  6.884 ms/op
                 getUser·p0.9999: 17.232 ms/op
                 getUser·p1.00:   17.596 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 314349
  mean =      3.053 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1540 
    [ 1.250,  2.500) = 25538 
    [ 2.500,  3.750) = 263604 
    [ 3.750,  5.000) = 22782 
    [ 5.000,  6.250) = 405 
    [ 6.250,  7.500) = 136 
    [ 7.500,  8.750) = 99 
    [ 8.750, 10.000) = 43 
    [10.000, 11.250) = 52 
    [11.250, 12.500) = 48 
    [12.500, 13.750) = 42 
    [13.750, 15.000) = 21 
    [15.000, 16.250) = 19 
    [16.250, 17.500) = 16 
    [17.500, 18.750) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.568 ms/op
     p(50.0000) =      3.047 ms/op
     p(90.0000) =      3.662 ms/op
     p(95.0000) =      3.863 ms/op
     p(99.0000) =      4.252 ms/op
     p(99.9000) =      8.001 ms/op
     p(99.9900) =     15.132 ms/op
     p(99.9990) =     17.564 ms/op
     p(99.9999) =     17.596 ms/op
    p(100.0000) =     17.596 ms/op


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
# Warmup Iteration   1: 4.391 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 4.040 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.959 ±(99.9%) 0.011 ms/op
Iteration   1: 4.136 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   0.603 ms/op
                 listUser·p0.50:   3.912 ms/op
                 listUser·p0.90:   5.497 ms/op
                 listUser·p0.95:   5.980 ms/op
                 listUser·p0.99:   7.299 ms/op
                 listUser·p0.999:  15.976 ms/op
                 listUser·p0.9999: 22.118 ms/op
                 listUser·p1.00:   22.675 ms/op

Iteration   2: 4.196 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.051 ms/op
                 listUser·p0.50:   3.965 ms/op
                 listUser·p0.90:   5.480 ms/op
                 listUser·p0.95:   5.923 ms/op
                 listUser·p0.99:   7.299 ms/op
                 listUser·p0.999:  18.048 ms/op
                 listUser·p0.9999: 29.590 ms/op
                 listUser·p1.00:   32.276 ms/op

Iteration   3: 4.056 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.225 ms/op
                 listUser·p0.50:   3.834 ms/op
                 listUser·p0.90:   5.243 ms/op
                 listUser·p0.95:   5.677 ms/op
                 listUser·p0.99:   6.849 ms/op
                 listUser·p0.999:  14.880 ms/op
                 listUser·p0.9999: 17.873 ms/op
                 listUser·p1.00:   18.612 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 232580
  mean =      4.128 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5574 
    [ 2.500,  5.000) = 183627 
    [ 5.000,  7.500) = 41747 
    [ 7.500, 10.000) = 1172 
    [10.000, 12.500) = 82 
    [12.500, 15.000) = 124 
    [15.000, 17.500) = 100 
    [17.500, 20.000) = 58 
    [20.000, 22.500) = 47 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 31 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.603 ms/op
     p(50.0000) =      3.895 ms/op
     p(90.0000) =      5.423 ms/op
     p(95.0000) =      5.874 ms/op
     p(99.0000) =      7.152 ms/op
     p(99.9000) =     15.686 ms/op
     p(99.9900) =     28.860 ms/op
     p(99.9990) =     29.732 ms/op
     p(99.9999) =     32.276 ms/op
    p(100.0000) =     32.276 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.462 ± 3.676  ops/ms
ClientGrpc.existUser                       thrpt       3  10.680 ± 2.515  ops/ms
ClientGrpc.getUser                         thrpt       3  10.288 ± 1.934  ops/ms
ClientGrpc.listUser                        thrpt       3   7.978 ± 2.361  ops/ms
ClientGrpc.createUser                       avgt       3   3.047 ± 0.382   ms/op
ClientGrpc.existUser                        avgt       3   2.990 ± 0.299   ms/op
ClientGrpc.getUser                          avgt       3   3.088 ± 0.658   ms/op
ClientGrpc.listUser                         avgt       3   3.910 ± 1.063   ms/op
ClientGrpc.createUser                     sample  308197   3.113 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.678           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.097           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.764           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.953           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.260           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.348           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.842           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          20.513           ms/op
ClientGrpc.existUser                      sample  321468   2.985 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.553           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.961           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.678           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.879           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.268           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.636           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.873           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.661           ms/op
ClientGrpc.getUser                        sample  314349   3.053 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.568           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.047           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.662           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.863           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.252           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.001           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          15.132           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          17.596           ms/op
ClientGrpc.listUser                       sample  232580   4.128 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.603           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.895           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.423           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.874           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.152           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.686           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          28.860           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          32.276           ms/op
