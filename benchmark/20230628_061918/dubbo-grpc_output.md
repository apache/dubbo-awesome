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
# Warmup Iteration   1: 4.470 ops/ms
# Warmup Iteration   2: 9.007 ops/ms
# Warmup Iteration   3: 9.854 ops/ms
Iteration   1: 10.476 ops/ms
Iteration   2: 10.500 ops/ms
Iteration   3: 10.481 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.486 ±(99.9%) 0.232 ops/ms [Average]
  (min, avg, max) = (10.476, 10.486, 10.500), stdev = 0.013
  CI (99.9%): [10.254, 10.718] (assumes normal distribution)


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
# Warmup Iteration   1: 7.423 ops/ms
# Warmup Iteration   2: 10.580 ops/ms
# Warmup Iteration   3: 10.985 ops/ms
Iteration   1: 11.176 ops/ms
Iteration   2: 11.003 ops/ms
Iteration   3: 11.197 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.125 ±(99.9%) 1.939 ops/ms [Average]
  (min, avg, max) = (11.003, 11.125, 11.197), stdev = 0.106
  CI (99.9%): [9.186, 13.065] (assumes normal distribution)


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
# Warmup Iteration   1: 6.868 ops/ms
# Warmup Iteration   2: 9.929 ops/ms
# Warmup Iteration   3: 10.486 ops/ms
Iteration   1: 10.398 ops/ms
Iteration   2: 10.690 ops/ms
Iteration   3: 10.607 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.565 ±(99.9%) 2.748 ops/ms [Average]
  (min, avg, max) = (10.398, 10.565, 10.690), stdev = 0.151
  CI (99.9%): [7.817, 13.313] (assumes normal distribution)


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
# Warmup Iteration   1: 5.371 ops/ms
# Warmup Iteration   2: 7.580 ops/ms
# Warmup Iteration   3: 7.941 ops/ms
Iteration   1: 7.884 ops/ms
Iteration   2: 8.016 ops/ms
Iteration   3: 8.052 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.984 ±(99.9%) 1.611 ops/ms [Average]
  (min, avg, max) = (7.884, 7.984, 8.052), stdev = 0.088
  CI (99.9%): [6.373, 9.595] (assumes normal distribution)


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
# Warmup Iteration   1: 4.334 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.139 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.056 ±(99.9%) 0.002 ms/op
Iteration   1: 2.994 ±(99.9%) 0.003 ms/op
Iteration   2: 3.059 ±(99.9%) 0.003 ms/op
Iteration   3: 2.986 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.013 ±(99.9%) 0.731 ms/op [Average]
  (min, avg, max) = (2.986, 3.013, 3.059), stdev = 0.040
  CI (99.9%): [2.282, 3.744] (assumes normal distribution)


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
# Warmup Iteration   1: 4.103 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.061 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.989 ±(99.9%) 0.002 ms/op
Iteration   1: 2.880 ±(99.9%) 0.001 ms/op
Iteration   2: 2.930 ±(99.9%) 0.002 ms/op
Iteration   3: 2.959 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.923 ±(99.9%) 0.735 ms/op [Average]
  (min, avg, max) = (2.880, 2.923, 2.959), stdev = 0.040
  CI (99.9%): [2.188, 3.658] (assumes normal distribution)


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
# Warmup Iteration   1: 4.475 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.188 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.117 ±(99.9%) 0.003 ms/op
Iteration   1: 3.029 ±(99.9%) 0.002 ms/op
Iteration   2: 3.031 ±(99.9%) 0.002 ms/op
Iteration   3: 3.079 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.046 ±(99.9%) 0.522 ms/op [Average]
  (min, avg, max) = (3.029, 3.046, 3.079), stdev = 0.029
  CI (99.9%): [2.525, 3.568] (assumes normal distribution)


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
# Warmup Iteration   1: 5.637 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 4.163 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 3.990 ±(99.9%) 0.018 ms/op
Iteration   1: 4.045 ±(99.9%) 0.020 ms/op
Iteration   2: 4.053 ±(99.9%) 0.003 ms/op
Iteration   3: 4.009 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.036 ±(99.9%) 0.424 ms/op [Average]
  (min, avg, max) = (4.009, 4.036, 4.053), stdev = 0.023
  CI (99.9%): [3.611, 4.460] (assumes normal distribution)


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
# Warmup Iteration   1: 4.631 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.222 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.083 ±(99.9%) 0.006 ms/op
Iteration   1: 3.053 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.869 ms/op
                 createUser·p0.50:   3.027 ms/op
                 createUser·p0.90:   3.654 ms/op
                 createUser·p0.95:   3.846 ms/op
                 createUser·p0.99:   4.653 ms/op
                 createUser·p0.999:  6.558 ms/op
                 createUser·p0.9999: 14.148 ms/op
                 createUser·p1.00:   14.320 ms/op

Iteration   2: 3.080 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.632 ms/op
                 createUser·p0.50:   3.043 ms/op
                 createUser·p0.90:   3.634 ms/op
                 createUser·p0.95:   3.863 ms/op
                 createUser·p0.99:   4.375 ms/op
                 createUser·p0.999:  7.523 ms/op
                 createUser·p0.9999: 14.252 ms/op
                 createUser·p1.00:   15.565 ms/op

Iteration   3: 3.044 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.673 ms/op
                 createUser·p0.50:   3.011 ms/op
                 createUser·p0.90:   3.576 ms/op
                 createUser·p0.95:   3.756 ms/op
                 createUser·p0.99:   4.284 ms/op
                 createUser·p0.999:  11.436 ms/op
                 createUser·p0.9999: 23.232 ms/op
                 createUser·p1.00:   24.904 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 313607
  mean =      3.059 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23447 
    [ 2.500,  5.000) = 288907 
    [ 5.000,  7.500) = 912 
    [ 7.500, 10.000) = 98 
    [10.000, 12.500) = 19 
    [12.500, 15.000) = 122 
    [15.000, 17.500) = 39 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.632 ms/op
     p(50.0000) =      3.027 ms/op
     p(90.0000) =      3.621 ms/op
     p(95.0000) =      3.826 ms/op
     p(99.0000) =      4.456 ms/op
     p(99.9000) =      7.733 ms/op
     p(99.9900) =     22.554 ms/op
     p(99.9990) =     23.551 ms/op
     p(99.9999) =     24.904 ms/op
    p(100.0000) =     24.904 ms/op


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
# Warmup Iteration   1: 4.144 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.052 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.971 ±(99.9%) 0.005 ms/op
Iteration   1: 2.900 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.639 ms/op
                 existUser·p0.50:   2.884 ms/op
                 existUser·p0.90:   3.344 ms/op
                 existUser·p0.95:   3.535 ms/op
                 existUser·p0.99:   4.243 ms/op
                 existUser·p0.999:  7.397 ms/op
                 existUser·p0.9999: 12.534 ms/op
                 existUser·p1.00:   12.714 ms/op

Iteration   2: 2.987 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.721 ms/op
                 existUser·p0.50:   2.945 ms/op
                 existUser·p0.90:   3.617 ms/op
                 existUser·p0.95:   3.789 ms/op
                 existUser·p0.99:   4.162 ms/op
                 existUser·p0.999:  8.780 ms/op
                 existUser·p0.9999: 14.226 ms/op
                 existUser·p1.00:   14.746 ms/op

Iteration   3: 2.895 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.844 ms/op
                 existUser·p0.50:   2.888 ms/op
                 existUser·p0.90:   3.359 ms/op
                 existUser·p0.95:   3.527 ms/op
                 existUser·p0.99:   3.957 ms/op
                 existUser·p0.999:  7.107 ms/op
                 existUser·p0.9999: 26.049 ms/op
                 existUser·p1.00:   26.280 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 327704
  mean =      2.927 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 39980 
    [ 2.500,  5.000) = 286894 
    [ 5.000,  7.500) = 505 
    [ 7.500, 10.000) = 88 
    [10.000, 12.500) = 93 
    [12.500, 15.000) = 80 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.639 ms/op
     p(50.0000) =      2.900 ms/op
     p(90.0000) =      3.453 ms/op
     p(95.0000) =      3.650 ms/op
     p(99.0000) =      4.125 ms/op
     p(99.9000) =      7.490 ms/op
     p(99.9900) =     21.648 ms/op
     p(99.9990) =     26.187 ms/op
     p(99.9999) =     26.280 ms/op
    p(100.0000) =     26.280 ms/op


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
# Warmup Iteration   1: 4.156 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.179 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.113 ±(99.9%) 0.007 ms/op
Iteration   1: 3.035 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.750 ms/op
                 getUser·p0.50:   3.027 ms/op
                 getUser·p0.90:   3.482 ms/op
                 getUser·p0.95:   3.752 ms/op
                 getUser·p0.99:   4.604 ms/op
                 getUser·p0.999:  10.027 ms/op
                 getUser·p0.9999: 12.574 ms/op
                 getUser·p1.00:   14.500 ms/op

Iteration   2: 3.095 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.590 ms/op
                 getUser·p0.50:   3.068 ms/op
                 getUser·p0.90:   3.625 ms/op
                 getUser·p0.95:   3.805 ms/op
                 getUser·p0.99:   4.522 ms/op
                 getUser·p0.999:  7.225 ms/op
                 getUser·p0.9999: 15.663 ms/op
                 getUser·p1.00:   15.729 ms/op

Iteration   3: 3.052 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.791 ms/op
                 getUser·p0.50:   3.006 ms/op
                 getUser·p0.90:   3.596 ms/op
                 getUser·p0.95:   3.801 ms/op
                 getUser·p0.99:   4.555 ms/op
                 getUser·p0.999:  11.062 ms/op
                 getUser·p0.9999: 18.105 ms/op
                 getUser·p1.00:   18.612 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 313709
  mean =      3.061 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 722 
    [ 1.250,  2.500) = 18896 
    [ 2.500,  3.750) = 276199 
    [ 3.750,  5.000) = 16144 
    [ 5.000,  6.250) = 948 
    [ 6.250,  7.500) = 381 
    [ 7.500,  8.750) = 94 
    [ 8.750, 10.000) = 36 
    [10.000, 11.250) = 64 
    [11.250, 12.500) = 79 
    [12.500, 13.750) = 37 
    [13.750, 15.000) = 33 
    [15.000, 16.250) = 34 
    [16.250, 17.500) = 25 
    [17.500, 18.750) = 17 

  Percentiles, ms/op:
      p(0.0000) =      0.590 ms/op
     p(50.0000) =      3.035 ms/op
     p(90.0000) =      3.580 ms/op
     p(95.0000) =      3.793 ms/op
     p(99.0000) =      4.555 ms/op
     p(99.9000) =      9.138 ms/op
     p(99.9900) =     16.732 ms/op
     p(99.9990) =     18.590 ms/op
     p(99.9999) =     18.612 ms/op
    p(100.0000) =     18.612 ms/op


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
# Warmup Iteration   1: 5.188 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.263 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.112 ±(99.9%) 0.011 ms/op
Iteration   1: 4.079 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.272 ms/op
                 listUser·p0.50:   3.916 ms/op
                 listUser·p0.90:   5.014 ms/op
                 listUser·p0.95:   5.882 ms/op
                 listUser·p0.99:   7.381 ms/op
                 listUser·p0.999:  13.713 ms/op
                 listUser·p0.9999: 16.113 ms/op
                 listUser·p1.00:   18.055 ms/op

Iteration   2: 4.131 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.044 ms/op
                 listUser·p0.50:   3.940 ms/op
                 listUser·p0.90:   5.251 ms/op
                 listUser·p0.95:   5.915 ms/op
                 listUser·p0.99:   7.172 ms/op
                 listUser·p0.999:  15.818 ms/op
                 listUser·p0.9999: 18.300 ms/op
                 listUser·p1.00:   18.842 ms/op

Iteration   3: 4.079 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.444 ms/op
                 listUser·p0.50:   3.916 ms/op
                 listUser·p0.90:   5.005 ms/op
                 listUser·p0.95:   5.579 ms/op
                 listUser·p0.99:   6.914 ms/op
                 listUser·p0.999:  18.281 ms/op
                 listUser·p0.9999: 31.795 ms/op
                 listUser·p1.00:   32.440 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 234379
  mean =      4.096 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1947 
    [ 2.500,  5.000) = 206137 
    [ 5.000,  7.500) = 24594 
    [ 7.500, 10.000) = 1225 
    [10.000, 12.500) = 87 
    [12.500, 15.000) = 145 
    [15.000, 17.500) = 129 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.044 ms/op
     p(50.0000) =      3.924 ms/op
     p(90.0000) =      5.104 ms/op
     p(95.0000) =      5.808 ms/op
     p(99.0000) =      7.176 ms/op
     p(99.9000) =     15.280 ms/op
     p(99.9900) =     31.345 ms/op
     p(99.9990) =     32.306 ms/op
     p(99.9999) =     32.440 ms/op
    p(100.0000) =     32.440 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.486 ± 0.232  ops/ms
ClientGrpc.existUser                       thrpt       3  11.125 ± 1.939  ops/ms
ClientGrpc.getUser                         thrpt       3  10.565 ± 2.748  ops/ms
ClientGrpc.listUser                        thrpt       3   7.984 ± 1.611  ops/ms
ClientGrpc.createUser                       avgt       3   3.013 ± 0.731   ms/op
ClientGrpc.existUser                        avgt       3   2.923 ± 0.735   ms/op
ClientGrpc.getUser                          avgt       3   3.046 ± 0.522   ms/op
ClientGrpc.listUser                         avgt       3   4.036 ± 0.424   ms/op
ClientGrpc.createUser                     sample  313607   3.059 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.632           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.027           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.621           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.826           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.456           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.733           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          22.554           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          24.904           ms/op
ClientGrpc.existUser                      sample  327704   2.927 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.639           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.900           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.453           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.650           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.125           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.490           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          21.648           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          26.280           ms/op
ClientGrpc.getUser                        sample  313709   3.061 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.590           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.035           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.580           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.793           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.555           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.138           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.732           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.612           ms/op
ClientGrpc.listUser                       sample  234379   4.096 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.044           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.924           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.104           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.808           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.176           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.280           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          31.345           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          32.440           ms/op
