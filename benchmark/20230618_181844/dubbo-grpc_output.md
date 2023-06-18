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
# Warmup Iteration   1: 3.949 ops/ms
# Warmup Iteration   2: 8.948 ops/ms
# Warmup Iteration   3: 9.941 ops/ms
Iteration   1: 10.572 ops/ms
Iteration   2: 10.521 ops/ms
Iteration   3: 10.673 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.589 ±(99.9%) 1.414 ops/ms [Average]
  (min, avg, max) = (10.521, 10.589, 10.673), stdev = 0.078
  CI (99.9%): [9.174, 12.003] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 7.698 ops/ms
# Warmup Iteration   2: 10.530 ops/ms
# Warmup Iteration   3: 11.061 ops/ms
Iteration   1: 11.063 ops/ms
Iteration   2: 11.005 ops/ms
Iteration   3: 10.982 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.016 ±(99.9%) 0.761 ops/ms [Average]
  (min, avg, max) = (10.982, 11.016, 11.063), stdev = 0.042
  CI (99.9%): [10.255, 11.778] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 6.941 ops/ms
# Warmup Iteration   2: 10.137 ops/ms
# Warmup Iteration   3: 10.434 ops/ms
Iteration   1: 10.643 ops/ms
Iteration   2: 10.325 ops/ms
Iteration   3: 10.554 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.507 ±(99.9%) 2.990 ops/ms [Average]
  (min, avg, max) = (10.325, 10.507, 10.643), stdev = 0.164
  CI (99.9%): [7.518, 13.497] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.632 ops/ms
# Warmup Iteration   2: 7.576 ops/ms
# Warmup Iteration   3: 7.935 ops/ms
Iteration   1: 8.162 ops/ms
Iteration   2: 7.988 ops/ms
Iteration   3: 8.039 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.063 ±(99.9%) 1.626 ops/ms [Average]
  (min, avg, max) = (7.988, 8.063, 8.162), stdev = 0.089
  CI (99.9%): [6.437, 9.689] (assumes normal distribution)


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
# Warmup Iteration   1: 4.422 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.220 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.038 ±(99.9%) 0.002 ms/op
Iteration   1: 3.047 ±(99.9%) 0.003 ms/op
Iteration   2: 2.987 ±(99.9%) 0.004 ms/op
Iteration   3: 3.014 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.016 ±(99.9%) 0.552 ms/op [Average]
  (min, avg, max) = (2.987, 3.016, 3.047), stdev = 0.030
  CI (99.9%): [2.464, 3.568] (assumes normal distribution)


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
# Warmup Iteration   1: 4.164 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.025 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.892 ±(99.9%) 0.002 ms/op
Iteration   1: 2.962 ±(99.9%) 0.002 ms/op
Iteration   2: 2.905 ±(99.9%) 0.003 ms/op
Iteration   3: 2.904 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.923 ±(99.9%) 0.607 ms/op [Average]
  (min, avg, max) = (2.904, 2.923, 2.962), stdev = 0.033
  CI (99.9%): [2.317, 3.530] (assumes normal distribution)


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
# Warmup Iteration   1: 4.110 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.142 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.106 ±(99.9%) 0.004 ms/op
Iteration   1: 3.066 ±(99.9%) 0.003 ms/op
Iteration   2: 3.073 ±(99.9%) 0.003 ms/op
Iteration   3: 3.033 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.057 ±(99.9%) 0.382 ms/op [Average]
  (min, avg, max) = (3.033, 3.057, 3.073), stdev = 0.021
  CI (99.9%): [2.675, 3.440] (assumes normal distribution)


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
# Warmup Iteration   1: 5.486 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 4.052 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.963 ±(99.9%) 0.008 ms/op
Iteration   1: 4.002 ±(99.9%) 0.016 ms/op
Iteration   2: 3.868 ±(99.9%) 0.030 ms/op
Iteration   3: 3.895 ±(99.9%) 0.026 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.922 ±(99.9%) 1.287 ms/op [Average]
  (min, avg, max) = (3.868, 3.922, 4.002), stdev = 0.071
  CI (99.9%): [2.634, 5.209] (assumes normal distribution)


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
# Warmup Iteration   1: 4.191 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.170 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.087 ±(99.9%) 0.006 ms/op
Iteration   1: 3.035 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.005 ms/op
                 createUser·p0.50:   2.998 ms/op
                 createUser·p0.90:   3.486 ms/op
                 createUser·p0.95:   3.658 ms/op
                 createUser·p0.99:   4.301 ms/op
                 createUser·p0.999:  6.687 ms/op
                 createUser·p0.9999: 13.222 ms/op
                 createUser·p1.00:   13.615 ms/op

Iteration   2: 3.075 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.558 ms/op
                 createUser·p0.50:   3.039 ms/op
                 createUser·p0.90:   3.629 ms/op
                 createUser·p0.95:   3.838 ms/op
                 createUser·p0.99:   4.473 ms/op
                 createUser·p0.999:  7.437 ms/op
                 createUser·p0.9999: 14.486 ms/op
                 createUser·p1.00:   14.680 ms/op

Iteration   3: 3.004 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.777 ms/op
                 createUser·p0.50:   2.990 ms/op
                 createUser·p0.90:   3.473 ms/op
                 createUser·p0.95:   3.645 ms/op
                 createUser·p0.99:   4.365 ms/op
                 createUser·p0.999:  7.595 ms/op
                 createUser·p0.9999: 17.990 ms/op
                 createUser·p1.00:   18.776 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 315864
  mean =      3.038 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 576 
    [ 1.250,  2.500) = 20690 
    [ 2.500,  3.750) = 279928 
    [ 3.750,  5.000) = 13083 
    [ 5.000,  6.250) = 909 
    [ 6.250,  7.500) = 407 
    [ 7.500,  8.750) = 56 
    [ 8.750, 10.000) = 3 
    [10.000, 11.250) = 20 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 72 
    [13.750, 15.000) = 66 
    [15.000, 16.250) = 24 
    [16.250, 17.500) = 8 
    [17.500, 18.750) = 21 

  Percentiles, ms/op:
      p(0.0000) =      0.558 ms/op
     p(50.0000) =      3.006 ms/op
     p(90.0000) =      3.535 ms/op
     p(95.0000) =      3.727 ms/op
     p(99.0000) =      4.375 ms/op
     p(99.9000) =      7.193 ms/op
     p(99.9900) =     16.208 ms/op
     p(99.9990) =     18.269 ms/op
     p(99.9999) =     18.776 ms/op
    p(100.0000) =     18.776 ms/op


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
# Warmup Iteration   1: 4.036 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.050 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.916 ±(99.9%) 0.006 ms/op
Iteration   1: 2.884 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.538 ms/op
                 existUser·p0.50:   2.871 ms/op
                 existUser·p0.90:   3.277 ms/op
                 existUser·p0.95:   3.441 ms/op
                 existUser·p0.99:   3.924 ms/op
                 existUser·p0.999:  5.883 ms/op
                 existUser·p0.9999: 22.181 ms/op
                 existUser·p1.00:   23.003 ms/op

Iteration   2: 2.913 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.819 ms/op
                 existUser·p0.50:   2.908 ms/op
                 existUser·p0.90:   3.383 ms/op
                 existUser·p0.95:   3.559 ms/op
                 existUser·p0.99:   4.186 ms/op
                 existUser·p0.999:  9.835 ms/op
                 existUser·p0.9999: 14.140 ms/op
                 existUser·p1.00:   16.482 ms/op

Iteration   3: 2.924 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.602 ms/op
                 existUser·p0.50:   2.896 ms/op
                 existUser·p0.90:   3.346 ms/op
                 existUser·p0.95:   3.555 ms/op
                 existUser·p0.99:   4.157 ms/op
                 existUser·p0.999:  9.912 ms/op
                 existUser·p0.9999: 16.813 ms/op
                 existUser·p1.00:   17.826 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 330321
  mean =      2.907 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 38961 
    [ 2.500,  5.000) = 290254 
    [ 5.000,  7.500) = 771 
    [ 7.500, 10.000) = 91 
    [10.000, 12.500) = 90 
    [12.500, 15.000) = 57 
    [15.000, 17.500) = 79 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.538 ms/op
     p(50.0000) =      2.892 ms/op
     p(90.0000) =      3.334 ms/op
     p(95.0000) =      3.531 ms/op
     p(99.0000) =      4.080 ms/op
     p(99.9000) =      7.556 ms/op
     p(99.9900) =     16.712 ms/op
     p(99.9990) =     22.786 ms/op
     p(99.9999) =     23.003 ms/op
    p(100.0000) =     23.003 ms/op


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
# Warmup Iteration   1: 4.375 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.164 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.039 ±(99.9%) 0.007 ms/op
Iteration   1: 3.070 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.765 ms/op
                 getUser·p0.50:   3.033 ms/op
                 getUser·p0.90:   3.654 ms/op
                 getUser·p0.95:   3.903 ms/op
                 getUser·p0.99:   4.841 ms/op
                 getUser·p0.999:  8.812 ms/op
                 getUser·p0.9999: 14.303 ms/op
                 getUser·p1.00:   14.549 ms/op

Iteration   2: 3.034 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.728 ms/op
                 getUser·p0.50:   3.002 ms/op
                 getUser·p0.90:   3.600 ms/op
                 getUser·p0.95:   3.822 ms/op
                 getUser·p0.99:   4.669 ms/op
                 getUser·p0.999:  8.259 ms/op
                 getUser·p0.9999: 14.278 ms/op
                 getUser·p1.00:   14.565 ms/op

Iteration   3: 3.019 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.861 ms/op
                 getUser·p0.50:   2.998 ms/op
                 getUser·p0.90:   3.486 ms/op
                 getUser·p0.95:   3.781 ms/op
                 getUser·p0.99:   4.694 ms/op
                 getUser·p0.999:  6.792 ms/op
                 getUser·p0.9999: 16.220 ms/op
                 getUser·p1.00:   19.137 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 315462
  mean =      3.041 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 785 
    [ 1.250,  2.500) = 24906 
    [ 2.500,  3.750) = 269523 
    [ 3.750,  5.000) = 18186 
    [ 5.000,  6.250) = 1295 
    [ 6.250,  7.500) = 320 
    [ 7.500,  8.750) = 180 
    [ 8.750, 10.000) = 54 
    [10.000, 11.250) = 16 
    [11.250, 12.500) = 4 
    [12.500, 13.750) = 53 
    [13.750, 15.000) = 94 
    [15.000, 16.250) = 37 
    [16.250, 17.500) = 4 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.728 ms/op
     p(50.0000) =      3.011 ms/op
     p(90.0000) =      3.588 ms/op
     p(95.0000) =      3.838 ms/op
     p(99.0000) =      4.743 ms/op
     p(99.9000) =      8.221 ms/op
     p(99.9900) =     15.778 ms/op
     p(99.9990) =     19.131 ms/op
     p(99.9999) =     19.137 ms/op
    p(100.0000) =     19.137 ms/op


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
# Warmup Iteration   1: 4.645 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 4.272 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.994 ±(99.9%) 0.011 ms/op
Iteration   1: 3.995 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.237 ms/op
                 listUser·p0.50:   3.834 ms/op
                 listUser·p0.90:   4.923 ms/op
                 listUser·p0.95:   5.612 ms/op
                 listUser·p0.99:   7.070 ms/op
                 listUser·p0.999:  14.710 ms/op
                 listUser·p0.9999: 17.072 ms/op
                 listUser·p1.00:   17.957 ms/op

Iteration   2: 4.056 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.382 ms/op
                 listUser·p0.50:   3.891 ms/op
                 listUser·p0.90:   5.104 ms/op
                 listUser·p0.95:   5.661 ms/op
                 listUser·p0.99:   7.111 ms/op
                 listUser·p0.999:  14.959 ms/op
                 listUser·p0.9999: 16.456 ms/op
                 listUser·p1.00:   16.777 ms/op

Iteration   3: 4.009 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.346 ms/op
                 listUser·p0.50:   3.854 ms/op
                 listUser·p0.90:   4.841 ms/op
                 listUser·p0.95:   5.693 ms/op
                 listUser·p0.99:   7.042 ms/op
                 listUser·p0.999:  19.235 ms/op
                 listUser·p0.9999: 28.345 ms/op
                 listUser·p1.00:   29.622 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 238759
  mean =      4.020 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1710 
    [ 2.500,  5.000) = 213796 
    [ 5.000,  7.500) = 21771 
    [ 7.500, 10.000) = 1049 
    [10.000, 12.500) = 49 
    [12.500, 15.000) = 121 
    [15.000, 17.500) = 140 
    [17.500, 20.000) = 58 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 19 

  Percentiles, ms/op:
      p(0.0000) =      0.346 ms/op
     p(50.0000) =      3.858 ms/op
     p(90.0000) =      4.973 ms/op
     p(95.0000) =      5.652 ms/op
     p(99.0000) =      7.070 ms/op
     p(99.9000) =     15.225 ms/op
     p(99.9900) =     26.833 ms/op
     p(99.9990) =     28.647 ms/op
     p(99.9999) =     29.622 ms/op
    p(100.0000) =     29.622 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.589 ± 1.414  ops/ms
ClientGrpc.existUser                       thrpt       3  11.016 ± 0.761  ops/ms
ClientGrpc.getUser                         thrpt       3  10.507 ± 2.990  ops/ms
ClientGrpc.listUser                        thrpt       3   8.063 ± 1.626  ops/ms
ClientGrpc.createUser                       avgt       3   3.016 ± 0.552   ms/op
ClientGrpc.existUser                        avgt       3   2.923 ± 0.607   ms/op
ClientGrpc.getUser                          avgt       3   3.057 ± 0.382   ms/op
ClientGrpc.listUser                         avgt       3   3.922 ± 1.287   ms/op
ClientGrpc.createUser                     sample  315864   3.038 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.558           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.006           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.535           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.727           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.375           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.193           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          16.208           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          18.776           ms/op
ClientGrpc.existUser                      sample  330321   2.907 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.538           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.892           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.334           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.531           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.080           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.556           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.712           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          23.003           ms/op
ClientGrpc.getUser                        sample  315462   3.041 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.728           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.011           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.588           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.838           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.743           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.221           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          15.778           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.137           ms/op
ClientGrpc.listUser                       sample  238759   4.020 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.346           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.858           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.973           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.652           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.070           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.225           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          26.833           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          29.622           ms/op
