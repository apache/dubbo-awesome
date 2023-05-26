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
# Warmup Iteration   1: 4.139 ops/ms
# Warmup Iteration   2: 8.362 ops/ms
# Warmup Iteration   3: 9.859 ops/ms
Iteration   1: 10.222 ops/ms
Iteration   2: 10.460 ops/ms
Iteration   3: 10.509 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.397 ±(99.9%) 2.798 ops/ms [Average]
  (min, avg, max) = (10.222, 10.397, 10.509), stdev = 0.153
  CI (99.9%): [7.599, 13.196] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.716 ops/ms
# Warmup Iteration   2: 10.716 ops/ms
# Warmup Iteration   3: 11.020 ops/ms
Iteration   1: 10.857 ops/ms
Iteration   2: 11.188 ops/ms
Iteration   3: 11.379 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.141 ±(99.9%) 4.825 ops/ms [Average]
  (min, avg, max) = (10.857, 11.141, 11.379), stdev = 0.264
  CI (99.9%): [6.316, 15.966] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 6.701 ops/ms
# Warmup Iteration   2: 10.169 ops/ms
# Warmup Iteration   3: 10.512 ops/ms
Iteration   1: 10.607 ops/ms
Iteration   2: 10.689 ops/ms
Iteration   3: 10.713 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.670 ±(99.9%) 1.018 ops/ms [Average]
  (min, avg, max) = (10.607, 10.670, 10.713), stdev = 0.056
  CI (99.9%): [9.652, 11.688] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.943 ops/ms
# Warmup Iteration   2: 7.704 ops/ms
# Warmup Iteration   3: 8.113 ops/ms
Iteration   1: 8.241 ops/ms
Iteration   2: 8.054 ops/ms
Iteration   3: 8.324 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.207 ±(99.9%) 2.524 ops/ms [Average]
  (min, avg, max) = (8.054, 8.207, 8.324), stdev = 0.138
  CI (99.9%): [5.683, 10.730] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.189 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.178 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.077 ±(99.9%) 0.003 ms/op
Iteration   1: 3.023 ±(99.9%) 0.002 ms/op
Iteration   2: 3.021 ±(99.9%) 0.002 ms/op
Iteration   3: 3.005 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.017 ±(99.9%) 0.180 ms/op [Average]
  (min, avg, max) = (3.005, 3.017, 3.023), stdev = 0.010
  CI (99.9%): [2.837, 3.196] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.582 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.027 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.941 ±(99.9%) 0.003 ms/op
Iteration   1: 2.905 ±(99.9%) 0.002 ms/op
Iteration   2: 2.898 ±(99.9%) 0.002 ms/op
Iteration   3: 2.868 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.890 ±(99.9%) 0.356 ms/op [Average]
  (min, avg, max) = (2.868, 2.890, 2.905), stdev = 0.020
  CI (99.9%): [2.534, 3.247] (assumes normal distribution)


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
# Warmup Iteration   1: 4.456 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.157 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.052 ±(99.9%) 0.002 ms/op
Iteration   1: 3.047 ±(99.9%) 0.004 ms/op
Iteration   2: 3.014 ±(99.9%) 0.002 ms/op
Iteration   3: 3.004 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.022 ±(99.9%) 0.403 ms/op [Average]
  (min, avg, max) = (3.004, 3.022, 3.047), stdev = 0.022
  CI (99.9%): [2.619, 3.425] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 5.286 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.149 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.930 ±(99.9%) 0.016 ms/op
Iteration   1: 3.931 ±(99.9%) 0.020 ms/op
Iteration   2: 3.912 ±(99.9%) 0.014 ms/op
Iteration   3: 3.950 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.931 ±(99.9%) 0.345 ms/op [Average]
  (min, avg, max) = (3.912, 3.931, 3.950), stdev = 0.019
  CI (99.9%): [3.586, 4.276] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.444 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.241 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.044 ±(99.9%) 0.006 ms/op
Iteration   1: 3.063 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.868 ms/op
                 createUser·p0.50:   3.027 ms/op
                 createUser·p0.90:   3.645 ms/op
                 createUser·p0.95:   3.846 ms/op
                 createUser·p0.99:   4.530 ms/op
                 createUser·p0.999:  7.120 ms/op
                 createUser·p0.9999: 18.041 ms/op
                 createUser·p1.00:   18.547 ms/op

Iteration   2: 2.997 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.732 ms/op
                 createUser·p0.50:   2.978 ms/op
                 createUser·p0.90:   3.502 ms/op
                 createUser·p0.95:   3.682 ms/op
                 createUser·p0.99:   4.424 ms/op
                 createUser·p0.999:  7.542 ms/op
                 createUser·p0.9999: 15.505 ms/op
                 createUser·p1.00:   17.433 ms/op

Iteration   3: 3.012 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.668 ms/op
                 createUser·p0.50:   2.970 ms/op
                 createUser·p0.90:   3.510 ms/op
                 createUser·p0.95:   3.744 ms/op
                 createUser·p0.99:   4.817 ms/op
                 createUser·p0.999:  8.382 ms/op
                 createUser·p0.9999: 17.990 ms/op
                 createUser·p1.00:   18.383 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 317257
  mean =      3.024 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 789 
    [ 1.250,  2.500) = 28777 
    [ 2.500,  3.750) = 271188 
    [ 3.750,  5.000) = 14658 
    [ 5.000,  6.250) = 1134 
    [ 6.250,  7.500) = 382 
    [ 7.500,  8.750) = 75 
    [ 8.750, 10.000) = 30 
    [10.000, 11.250) = 28 
    [11.250, 12.500) = 4 
    [12.500, 13.750) = 49 
    [13.750, 15.000) = 33 
    [15.000, 16.250) = 38 
    [16.250, 17.500) = 26 
    [17.500, 18.750) = 46 

  Percentiles, ms/op:
      p(0.0000) =      0.668 ms/op
     p(50.0000) =      2.990 ms/op
     p(90.0000) =      3.559 ms/op
     p(95.0000) =      3.760 ms/op
     p(99.0000) =      4.596 ms/op
     p(99.9000) =      7.594 ms/op
     p(99.9900) =     17.826 ms/op
     p(99.9990) =     18.312 ms/op
     p(99.9999) =     18.547 ms/op
    p(100.0000) =     18.547 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 4.035 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.076 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.880 ±(99.9%) 0.005 ms/op
Iteration   1: 2.864 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.665 ms/op
                 existUser·p0.50:   2.859 ms/op
                 existUser·p0.90:   3.260 ms/op
                 existUser·p0.95:   3.461 ms/op
                 existUser·p0.99:   4.094 ms/op
                 existUser·p0.999:  6.581 ms/op
                 existUser·p0.9999: 12.386 ms/op
                 existUser·p1.00:   12.632 ms/op

Iteration   2: 2.861 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.640 ms/op
                 existUser·p0.50:   2.839 ms/op
                 existUser·p0.90:   3.391 ms/op
                 existUser·p0.95:   3.625 ms/op
                 existUser·p0.99:   4.375 ms/op
                 existUser·p0.999:  9.628 ms/op
                 existUser·p0.9999: 15.651 ms/op
                 existUser·p1.00:   16.024 ms/op

Iteration   3: 2.907 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.840 ms/op
                 existUser·p0.50:   2.875 ms/op
                 existUser·p0.90:   3.281 ms/op
                 existUser·p0.95:   3.490 ms/op
                 existUser·p0.99:   4.063 ms/op
                 existUser·p0.999:  7.094 ms/op
                 existUser·p0.9999: 17.465 ms/op
                 existUser·p1.00:   17.826 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 333642
  mean =      2.877 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1088 
    [ 1.250,  2.500) = 42766 
    [ 2.500,  3.750) = 281032 
    [ 3.750,  5.000) = 7834 
    [ 5.000,  6.250) = 306 
    [ 6.250,  7.500) = 233 
    [ 7.500,  8.750) = 65 
    [ 8.750, 10.000) = 59 
    [10.000, 11.250) = 39 
    [11.250, 12.500) = 75 
    [12.500, 13.750) = 25 
    [13.750, 15.000) = 24 
    [15.000, 16.250) = 64 
    [16.250, 17.500) = 24 
    [17.500, 18.750) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.640 ms/op
     p(50.0000) =      2.859 ms/op
     p(90.0000) =      3.314 ms/op
     p(95.0000) =      3.531 ms/op
     p(99.0000) =      4.162 ms/op
     p(99.9000) =      8.716 ms/op
     p(99.9900) =     16.138 ms/op
     p(99.9990) =     17.705 ms/op
     p(99.9999) =     17.826 ms/op
    p(100.0000) =     17.826 ms/op


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
# Warmup Iteration   1: 4.276 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.154 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.011 ±(99.9%) 0.006 ms/op
Iteration   1: 3.017 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.633 ms/op
                 getUser·p0.50:   2.986 ms/op
                 getUser·p0.90:   3.498 ms/op
                 getUser·p0.95:   3.760 ms/op
                 getUser·p0.99:   4.522 ms/op
                 getUser·p0.999:  9.486 ms/op
                 getUser·p0.9999: 16.394 ms/op
                 getUser·p1.00:   17.138 ms/op

Iteration   2: 3.021 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.859 ms/op
                 getUser·p0.50:   2.998 ms/op
                 getUser·p0.90:   3.490 ms/op
                 getUser·p0.95:   3.674 ms/op
                 getUser·p0.99:   4.233 ms/op
                 getUser·p0.999:  10.718 ms/op
                 getUser·p0.9999: 19.084 ms/op
                 getUser·p1.00:   19.497 ms/op

Iteration   3: 2.994 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.817 ms/op
                 getUser·p0.50:   2.982 ms/op
                 getUser·p0.90:   3.473 ms/op
                 getUser·p0.95:   3.670 ms/op
                 getUser·p0.99:   4.235 ms/op
                 getUser·p0.999:  5.817 ms/op
                 getUser·p0.9999: 17.355 ms/op
                 getUser·p1.00:   17.957 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 318806
  mean =      3.010 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 570 
    [ 1.250,  2.500) = 21672 
    [ 2.500,  3.750) = 283196 
    [ 3.750,  5.000) = 12185 
    [ 5.000,  6.250) = 643 
    [ 6.250,  7.500) = 158 
    [ 7.500,  8.750) = 69 
    [ 8.750, 10.000) = 59 
    [10.000, 11.250) = 46 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 23 
    [13.750, 15.000) = 85 
    [15.000, 16.250) = 33 
    [16.250, 17.500) = 27 
    [17.500, 18.750) = 21 

  Percentiles, ms/op:
      p(0.0000) =      0.633 ms/op
     p(50.0000) =      2.990 ms/op
     p(90.0000) =      3.486 ms/op
     p(95.0000) =      3.699 ms/op
     p(99.0000) =      4.317 ms/op
     p(99.9000) =      8.677 ms/op
     p(99.9900) =     18.256 ms/op
     p(99.9990) =     19.386 ms/op
     p(99.9999) =     19.497 ms/op
    p(100.0000) =     19.497 ms/op


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
# Warmup Iteration   1: 5.545 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 4.114 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.957 ±(99.9%) 0.010 ms/op
Iteration   1: 4.026 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.079 ms/op
                 listUser·p0.50:   3.838 ms/op
                 listUser·p0.90:   5.071 ms/op
                 listUser·p0.95:   5.693 ms/op
                 listUser·p0.99:   7.168 ms/op
                 listUser·p0.999:  14.281 ms/op
                 listUser·p0.9999: 19.468 ms/op
                 listUser·p1.00:   20.087 ms/op

Iteration   2: 3.967 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.083 ms/op
                 listUser·p0.50:   3.850 ms/op
                 listUser·p0.90:   4.719 ms/op
                 listUser·p0.95:   5.571 ms/op
                 listUser·p0.99:   6.734 ms/op
                 listUser·p0.999:  14.446 ms/op
                 listUser·p0.9999: 16.876 ms/op
                 listUser·p1.00:   17.203 ms/op

Iteration   3: 4.039 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.180 ms/op
                 listUser·p0.50:   3.871 ms/op
                 listUser·p0.90:   5.169 ms/op
                 listUser·p0.95:   6.013 ms/op
                 listUser·p0.99:   7.193 ms/op
                 listUser·p0.999:  14.628 ms/op
                 listUser·p0.9999: 20.745 ms/op
                 listUser·p1.00:   22.151 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 239284
  mean =      4.011 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3077 
    [ 2.500,  5.000) = 212434 
    [ 5.000,  7.500) = 22258 
    [ 7.500, 10.000) = 1039 
    [10.000, 12.500) = 91 
    [12.500, 15.000) = 219 
    [15.000, 17.500) = 70 
    [17.500, 20.000) = 59 
    [20.000, 22.500) = 37 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.079 ms/op
     p(50.0000) =      3.850 ms/op
     p(90.0000) =      4.997 ms/op
     p(95.0000) =      5.792 ms/op
     p(99.0000) =      7.053 ms/op
     p(99.9000) =     14.512 ms/op
     p(99.9900) =     20.447 ms/op
     p(99.9990) =     21.589 ms/op
     p(99.9999) =     22.151 ms/op
    p(100.0000) =     22.151 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.397 ± 2.798  ops/ms
ClientGrpc.existUser                       thrpt       3  11.141 ± 4.825  ops/ms
ClientGrpc.getUser                         thrpt       3  10.670 ± 1.018  ops/ms
ClientGrpc.listUser                        thrpt       3   8.207 ± 2.524  ops/ms
ClientGrpc.createUser                       avgt       3   3.017 ± 0.180   ms/op
ClientGrpc.existUser                        avgt       3   2.890 ± 0.356   ms/op
ClientGrpc.getUser                          avgt       3   3.022 ± 0.403   ms/op
ClientGrpc.listUser                         avgt       3   3.931 ± 0.345   ms/op
ClientGrpc.createUser                     sample  317257   3.024 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.668           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.990           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.559           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.760           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.596           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.594           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.826           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          18.547           ms/op
ClientGrpc.existUser                      sample  333642   2.877 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.640           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.859           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.314           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.531           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.162           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.716           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.138           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.826           ms/op
ClientGrpc.getUser                        sample  318806   3.010 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.633           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.990           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.486           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.699           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.317           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.677           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.256           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.497           ms/op
ClientGrpc.listUser                       sample  239284   4.011 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.079           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.850           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.997           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.792           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.053           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.512           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          20.447           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          22.151           ms/op
