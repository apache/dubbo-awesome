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
# Warmup Iteration   1: 4.474 ops/ms
# Warmup Iteration   2: 9.613 ops/ms
# Warmup Iteration   3: 10.421 ops/ms
Iteration   1: 10.661 ops/ms
Iteration   2: 10.617 ops/ms
Iteration   3: 10.808 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.695 ±(99.9%) 1.819 ops/ms [Average]
  (min, avg, max) = (10.617, 10.695, 10.808), stdev = 0.100
  CI (99.9%): [8.876, 12.514] (assumes normal distribution)


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
# Warmup Iteration   1: 7.896 ops/ms
# Warmup Iteration   2: 10.964 ops/ms
# Warmup Iteration   3: 11.239 ops/ms
Iteration   1: 11.420 ops/ms
Iteration   2: 11.207 ops/ms
Iteration   3: 11.121 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.249 ±(99.9%) 2.807 ops/ms [Average]
  (min, avg, max) = (11.121, 11.249, 11.420), stdev = 0.154
  CI (99.9%): [8.443, 14.056] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 8.123 ops/ms
# Warmup Iteration   2: 10.459 ops/ms
# Warmup Iteration   3: 10.743 ops/ms
Iteration   1: 10.744 ops/ms
Iteration   2: 10.875 ops/ms
Iteration   3: 10.648 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.755 ±(99.9%) 2.072 ops/ms [Average]
  (min, avg, max) = (10.648, 10.755, 10.875), stdev = 0.114
  CI (99.9%): [8.683, 12.828] (assumes normal distribution)


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
# Warmup Iteration   1: 5.855 ops/ms
# Warmup Iteration   2: 8.142 ops/ms
# Warmup Iteration   3: 8.321 ops/ms
Iteration   1: 8.406 ops/ms
Iteration   2: 8.398 ops/ms
Iteration   3: 8.457 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.420 ±(99.9%) 0.588 ops/ms [Average]
  (min, avg, max) = (8.398, 8.420, 8.457), stdev = 0.032
  CI (99.9%): [7.832, 9.009] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 4.049 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.067 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.859 ±(99.9%) 0.004 ms/op
Iteration   1: 2.976 ±(99.9%) 0.003 ms/op
Iteration   2: 2.972 ±(99.9%) 0.003 ms/op
Iteration   3: 2.920 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.956 ±(99.9%) 0.575 ms/op [Average]
  (min, avg, max) = (2.920, 2.956, 2.976), stdev = 0.032
  CI (99.9%): [2.381, 3.531] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.798 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 2.941 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.856 ±(99.9%) 0.004 ms/op
Iteration   1: 2.927 ±(99.9%) 0.003 ms/op
Iteration   2: 2.861 ±(99.9%) 0.004 ms/op
Iteration   3: 2.888 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.892 ±(99.9%) 0.601 ms/op [Average]
  (min, avg, max) = (2.861, 2.892, 2.927), stdev = 0.033
  CI (99.9%): [2.291, 3.493] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.812 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.112 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.041 ±(99.9%) 0.003 ms/op
Iteration   1: 3.031 ±(99.9%) 0.002 ms/op
Iteration   2: 2.981 ±(99.9%) 0.002 ms/op
Iteration   3: 2.957 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.990 ±(99.9%) 0.689 ms/op [Average]
  (min, avg, max) = (2.957, 2.990, 3.031), stdev = 0.038
  CI (99.9%): [2.301, 3.679] (assumes normal distribution)


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
# Warmup Iteration   1: 4.522 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.968 ±(99.9%) 0.036 ms/op
# Warmup Iteration   3: 3.837 ±(99.9%) 0.005 ms/op
Iteration   1: 3.851 ±(99.9%) 0.016 ms/op
Iteration   2: 3.766 ±(99.9%) 0.015 ms/op
Iteration   3: 3.825 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.814 ±(99.9%) 0.800 ms/op [Average]
  (min, avg, max) = (3.766, 3.814, 3.851), stdev = 0.044
  CI (99.9%): [3.014, 4.614] (assumes normal distribution)


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
# Warmup Iteration   1: 3.805 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.181 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.932 ±(99.9%) 0.007 ms/op
Iteration   1: 2.969 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.682 ms/op
                 createUser·p0.50:   2.978 ms/op
                 createUser·p0.90:   3.388 ms/op
                 createUser·p0.95:   3.572 ms/op
                 createUser·p0.99:   4.100 ms/op
                 createUser·p0.999:  6.335 ms/op
                 createUser·p0.9999: 16.011 ms/op
                 createUser·p1.00:   16.253 ms/op

Iteration   2: 2.956 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.528 ms/op
                 createUser·p0.50:   2.937 ms/op
                 createUser·p0.90:   3.469 ms/op
                 createUser·p0.95:   3.756 ms/op
                 createUser·p0.99:   4.448 ms/op
                 createUser·p0.999:  6.697 ms/op
                 createUser·p0.9999: 18.317 ms/op
                 createUser·p1.00:   19.497 ms/op

Iteration   3: 2.977 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.793 ms/op
                 createUser·p0.50:   2.974 ms/op
                 createUser·p0.90:   3.486 ms/op
                 createUser·p0.95:   3.670 ms/op
                 createUser·p0.99:   4.170 ms/op
                 createUser·p0.999:  7.553 ms/op
                 createUser·p0.9999: 18.981 ms/op
                 createUser·p1.00:   19.562 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 323278
  mean =      2.967 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1821 
    [ 1.250,  2.500) = 25277 
    [ 2.500,  3.750) = 284665 
    [ 3.750,  5.000) = 10535 
    [ 5.000,  6.250) = 478 
    [ 6.250,  7.500) = 221 
    [ 7.500,  8.750) = 41 
    [ 8.750, 10.000) = 5 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 25 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 67 
    [16.250, 17.500) = 55 
    [17.500, 18.750) = 53 

  Percentiles, ms/op:
      p(0.0000) =      0.528 ms/op
     p(50.0000) =      2.961 ms/op
     p(90.0000) =      3.445 ms/op
     p(95.0000) =      3.662 ms/op
     p(99.0000) =      4.252 ms/op
     p(99.9000) =      7.207 ms/op
     p(99.9900) =     18.722 ms/op
     p(99.9990) =     19.466 ms/op
     p(99.9999) =     19.562 ms/op
    p(100.0000) =     19.562 ms/op


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
# Warmup Iteration   1: 3.929 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 2.954 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.909 ±(99.9%) 0.005 ms/op
Iteration   1: 2.933 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.657 ms/op
                 existUser·p0.50:   2.912 ms/op
                 existUser·p0.90:   3.473 ms/op
                 existUser·p0.95:   3.682 ms/op
                 existUser·p0.99:   4.350 ms/op
                 existUser·p0.999:  6.503 ms/op
                 existUser·p0.9999: 13.620 ms/op
                 existUser·p1.00:   14.057 ms/op

Iteration   2: 2.895 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.647 ms/op
                 existUser·p0.50:   2.888 ms/op
                 existUser·p0.90:   3.346 ms/op
                 existUser·p0.95:   3.539 ms/op
                 existUser·p0.99:   4.227 ms/op
                 existUser·p0.999:  5.603 ms/op
                 existUser·p0.9999: 12.599 ms/op
                 existUser·p1.00:   13.009 ms/op

Iteration   3: 2.800 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.438 ms/op
                 existUser·p0.50:   2.863 ms/op
                 existUser·p0.90:   3.277 ms/op
                 existUser·p0.95:   3.527 ms/op
                 existUser·p0.99:   4.366 ms/op
                 existUser·p0.999:  6.283 ms/op
                 existUser·p0.9999: 13.713 ms/op
                 existUser·p1.00:   13.828 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 334026
  mean =      2.875 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 4821 
    [ 1.250,  2.500) = 38844 
    [ 2.500,  3.750) = 279674 
    [ 3.750,  5.000) = 9618 
    [ 5.000,  6.250) = 754 
    [ 6.250,  7.500) = 137 
    [ 7.500,  8.750) = 50 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 16 
    [11.250, 12.500) = 26 
    [12.500, 13.750) = 71 
    [13.750, 15.000) = 15 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.438 ms/op
     p(50.0000) =      2.884 ms/op
     p(90.0000) =      3.371 ms/op
     p(95.0000) =      3.596 ms/op
     p(99.0000) =      4.317 ms/op
     p(99.9000) =      6.168 ms/op
     p(99.9900) =     13.484 ms/op
     p(99.9990) =     13.942 ms/op
     p(99.9999) =     14.057 ms/op
    p(100.0000) =     14.057 ms/op


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
# Warmup Iteration   1: 3.985 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.161 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.962 ±(99.9%) 0.006 ms/op
Iteration   1: 2.963 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.720 ms/op
                 getUser·p0.50:   2.941 ms/op
                 getUser·p0.90:   3.518 ms/op
                 getUser·p0.95:   3.781 ms/op
                 getUser·p0.99:   4.342 ms/op
                 getUser·p0.999:  7.105 ms/op
                 getUser·p0.9999: 11.882 ms/op
                 getUser·p1.00:   12.124 ms/op

Iteration   2: 2.942 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.658 ms/op
                 getUser·p0.50:   2.937 ms/op
                 getUser·p0.90:   3.412 ms/op
                 getUser·p0.95:   3.604 ms/op
                 getUser·p0.99:   4.301 ms/op
                 getUser·p0.999:  6.169 ms/op
                 getUser·p0.9999: 20.189 ms/op
                 getUser·p1.00:   20.414 ms/op

Iteration   3: 2.963 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.626 ms/op
                 getUser·p0.50:   2.974 ms/op
                 getUser·p0.90:   3.506 ms/op
                 getUser·p0.95:   3.695 ms/op
                 getUser·p0.99:   4.227 ms/op
                 getUser·p0.999:  6.547 ms/op
                 getUser·p0.9999: 15.129 ms/op
                 getUser·p1.00:   15.385 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 324492
  mean =      2.956 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 32969 
    [ 2.500,  5.000) = 290542 
    [ 5.000,  7.500) = 735 
    [ 7.500, 10.000) = 85 
    [10.000, 12.500) = 53 
    [12.500, 15.000) = 59 
    [15.000, 17.500) = 17 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.626 ms/op
     p(50.0000) =      2.953 ms/op
     p(90.0000) =      3.478 ms/op
     p(95.0000) =      3.695 ms/op
     p(99.0000) =      4.301 ms/op
     p(99.9000) =      6.545 ms/op
     p(99.9900) =     17.776 ms/op
     p(99.9990) =     20.374 ms/op
     p(99.9999) =     20.414 ms/op
    p(100.0000) =     20.414 ms/op


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
# Warmup Iteration   1: 5.073 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.873 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.889 ±(99.9%) 0.010 ms/op
Iteration   1: 3.908 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.641 ms/op
                 listUser·p0.50:   3.744 ms/op
                 listUser·p0.90:   4.989 ms/op
                 listUser·p0.95:   5.513 ms/op
                 listUser·p0.99:   6.767 ms/op
                 listUser·p0.999:  13.124 ms/op
                 listUser·p0.9999: 20.840 ms/op
                 listUser·p1.00:   24.379 ms/op

Iteration   2: 3.763 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.888 ms/op
                 listUser·p0.50:   3.674 ms/op
                 listUser·p0.90:   4.301 ms/op
                 listUser·p0.95:   5.071 ms/op
                 listUser·p0.99:   6.562 ms/op
                 listUser·p0.999:  15.532 ms/op
                 listUser·p0.9999: 24.297 ms/op
                 listUser·p1.00:   24.871 ms/op

Iteration   3: 3.819 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.908 ms/op
                 listUser·p0.50:   3.719 ms/op
                 listUser·p0.90:   4.506 ms/op
                 listUser·p0.95:   5.448 ms/op
                 listUser·p0.99:   6.595 ms/op
                 listUser·p0.999:  14.664 ms/op
                 listUser·p0.9999: 21.874 ms/op
                 listUser·p1.00:   22.282 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 250633
  mean =      3.829 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5665 
    [ 2.500,  5.000) = 226666 
    [ 5.000,  7.500) = 17264 
    [ 7.500, 10.000) = 566 
    [10.000, 12.500) = 114 
    [12.500, 15.000) = 158 
    [15.000, 17.500) = 58 
    [17.500, 20.000) = 42 
    [20.000, 22.500) = 65 
    [22.500, 25.000) = 35 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.641 ms/op
     p(50.0000) =      3.711 ms/op
     p(90.0000) =      4.694 ms/op
     p(95.0000) =      5.390 ms/op
     p(99.0000) =      6.644 ms/op
     p(99.9000) =     13.982 ms/op
     p(99.9900) =     23.658 ms/op
     p(99.9990) =     24.690 ms/op
     p(99.9999) =     24.871 ms/op
    p(100.0000) =     24.871 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.695 ± 1.819  ops/ms
ClientGrpc.existUser                       thrpt       3  11.249 ± 2.807  ops/ms
ClientGrpc.getUser                         thrpt       3  10.755 ± 2.072  ops/ms
ClientGrpc.listUser                        thrpt       3   8.420 ± 0.588  ops/ms
ClientGrpc.createUser                       avgt       3   2.956 ± 0.575   ms/op
ClientGrpc.existUser                        avgt       3   2.892 ± 0.601   ms/op
ClientGrpc.getUser                          avgt       3   2.990 ± 0.689   ms/op
ClientGrpc.listUser                         avgt       3   3.814 ± 0.800   ms/op
ClientGrpc.createUser                     sample  323278   2.967 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.528           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.961           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.445           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.662           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.252           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.207           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.722           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          19.562           ms/op
ClientGrpc.existUser                      sample  334026   2.875 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.438           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.884           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.371           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.596           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.317           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.168           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          13.484           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          14.057           ms/op
ClientGrpc.getUser                        sample  324492   2.956 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.626           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.953           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.478           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.695           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.301           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.545           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.776           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.414           ms/op
ClientGrpc.listUser                       sample  250633   3.829 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.641           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.711           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.694           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.390           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.644           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.982           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.658           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.871           ms/op
