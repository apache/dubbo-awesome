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
# Warmup Iteration   1: 3.885 ops/ms
# Warmup Iteration   2: 8.310 ops/ms
# Warmup Iteration   3: 9.709 ops/ms
Iteration   1: 9.930 ops/ms
Iteration   2: 10.158 ops/ms
Iteration   3: 10.295 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.127 ±(99.9%) 3.365 ops/ms [Average]
  (min, avg, max) = (9.930, 10.127, 10.295), stdev = 0.184
  CI (99.9%): [6.762, 13.492] (assumes normal distribution)


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
# Warmup Iteration   1: 7.072 ops/ms
# Warmup Iteration   2: 10.051 ops/ms
# Warmup Iteration   3: 10.615 ops/ms
Iteration   1: 10.578 ops/ms
Iteration   2: 10.565 ops/ms
Iteration   3: 10.679 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.607 ±(99.9%) 1.140 ops/ms [Average]
  (min, avg, max) = (10.565, 10.607, 10.679), stdev = 0.062
  CI (99.9%): [9.467, 11.747] (assumes normal distribution)


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
# Warmup Iteration   1: 6.969 ops/ms
# Warmup Iteration   2: 9.894 ops/ms
# Warmup Iteration   3: 10.298 ops/ms
Iteration   1: 10.471 ops/ms
Iteration   2: 10.309 ops/ms
Iteration   3: 10.255 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.345 ±(99.9%) 2.049 ops/ms [Average]
  (min, avg, max) = (10.255, 10.345, 10.471), stdev = 0.112
  CI (99.9%): [8.295, 12.394] (assumes normal distribution)


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
# Warmup Iteration   1: 5.755 ops/ms
# Warmup Iteration   2: 7.134 ops/ms
# Warmup Iteration   3: 7.584 ops/ms
Iteration   1: 7.730 ops/ms
Iteration   2: 7.767 ops/ms
Iteration   3: 7.863 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.787 ±(99.9%) 1.255 ops/ms [Average]
  (min, avg, max) = (7.730, 7.787, 7.863), stdev = 0.069
  CI (99.9%): [6.531, 9.042] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.333 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.326 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 3.192 ±(99.9%) 0.002 ms/op
Iteration   1: 3.147 ±(99.9%) 0.003 ms/op
Iteration   2: 3.132 ±(99.9%) 0.002 ms/op
Iteration   3: 3.224 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.168 ±(99.9%) 0.895 ms/op [Average]
  (min, avg, max) = (3.132, 3.168, 3.224), stdev = 0.049
  CI (99.9%): [2.273, 4.063] (assumes normal distribution)


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
# Warmup Iteration   1: 3.800 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.076 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.984 ±(99.9%) 0.003 ms/op
Iteration   1: 2.967 ±(99.9%) 0.002 ms/op
Iteration   2: 2.955 ±(99.9%) 0.002 ms/op
Iteration   3: 2.962 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.961 ±(99.9%) 0.109 ms/op [Average]
  (min, avg, max) = (2.955, 2.961, 2.967), stdev = 0.006
  CI (99.9%): [2.852, 3.071] (assumes normal distribution)


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
# Warmup Iteration   1: 4.315 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.213 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.141 ±(99.9%) 0.003 ms/op
Iteration   1: 3.123 ±(99.9%) 0.003 ms/op
Iteration   2: 3.199 ±(99.9%) 0.003 ms/op
Iteration   3: 3.127 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.149 ±(99.9%) 0.790 ms/op [Average]
  (min, avg, max) = (3.123, 3.149, 3.199), stdev = 0.043
  CI (99.9%): [2.360, 3.939] (assumes normal distribution)


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
# Warmup Iteration   1: 5.122 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 4.318 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.074 ±(99.9%) 0.014 ms/op
Iteration   1: 4.053 ±(99.9%) 0.013 ms/op
Iteration   2: 4.034 ±(99.9%) 0.021 ms/op
Iteration   3: 4.007 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.031 ±(99.9%) 0.427 ms/op [Average]
  (min, avg, max) = (4.007, 4.031, 4.053), stdev = 0.023
  CI (99.9%): [3.604, 4.458] (assumes normal distribution)


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
# Warmup Iteration   1: 4.531 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.373 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.103 ±(99.9%) 0.007 ms/op
Iteration   1: 3.143 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.723 ms/op
                 createUser·p0.50:   3.080 ms/op
                 createUser·p0.90:   3.772 ms/op
                 createUser·p0.95:   4.051 ms/op
                 createUser·p0.99:   5.562 ms/op
                 createUser·p0.999:  12.247 ms/op
                 createUser·p0.9999: 15.775 ms/op
                 createUser·p1.00:   16.384 ms/op

Iteration   2: 3.084 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.904 ms/op
                 createUser·p0.50:   3.047 ms/op
                 createUser·p0.90:   3.650 ms/op
                 createUser·p0.95:   3.891 ms/op
                 createUser·p0.99:   5.044 ms/op
                 createUser·p0.999:  9.312 ms/op
                 createUser·p0.9999: 15.066 ms/op
                 createUser·p1.00:   15.794 ms/op

Iteration   3: 3.088 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.790 ms/op
                 createUser·p0.50:   3.043 ms/op
                 createUser·p0.90:   3.678 ms/op
                 createUser·p0.95:   3.981 ms/op
                 createUser·p0.99:   5.087 ms/op
                 createUser·p0.999:  9.716 ms/op
                 createUser·p0.9999: 18.796 ms/op
                 createUser·p1.00:   19.333 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 309375
  mean =      3.104 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 753 
    [ 1.250,  2.500) = 23221 
    [ 2.500,  3.750) = 258029 
    [ 3.750,  5.000) = 23691 
    [ 5.000,  6.250) = 1967 
    [ 6.250,  7.500) = 1011 
    [ 7.500,  8.750) = 270 
    [ 8.750, 10.000) = 105 
    [10.000, 11.250) = 64 
    [11.250, 12.500) = 46 
    [12.500, 13.750) = 74 
    [13.750, 15.000) = 37 
    [15.000, 16.250) = 42 
    [16.250, 17.500) = 28 
    [17.500, 18.750) = 25 

  Percentiles, ms/op:
      p(0.0000) =      0.723 ms/op
     p(50.0000) =      3.056 ms/op
     p(90.0000) =      3.703 ms/op
     p(95.0000) =      3.985 ms/op
     p(99.0000) =      5.186 ms/op
     p(99.9000) =     10.588 ms/op
     p(99.9900) =     18.031 ms/op
     p(99.9990) =     19.071 ms/op
     p(99.9999) =     19.333 ms/op
    p(100.0000) =     19.333 ms/op


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
# Warmup Iteration   1: 3.705 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.009 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.970 ±(99.9%) 0.006 ms/op
Iteration   1: 2.949 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.544 ms/op
                 existUser·p0.50:   2.912 ms/op
                 existUser·p0.90:   3.490 ms/op
                 existUser·p0.95:   3.723 ms/op
                 existUser·p0.99:   4.596 ms/op
                 existUser·p0.999:  8.004 ms/op
                 existUser·p0.9999: 13.011 ms/op
                 existUser·p1.00:   13.337 ms/op

Iteration   2: 2.942 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.740 ms/op
                 existUser·p0.50:   2.916 ms/op
                 existUser·p0.90:   3.424 ms/op
                 existUser·p0.95:   3.658 ms/op
                 existUser·p0.99:   4.604 ms/op
                 existUser·p0.999:  7.549 ms/op
                 existUser·p0.9999: 14.862 ms/op
                 existUser·p1.00:   16.482 ms/op

Iteration   3: 2.953 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.536 ms/op
                 existUser·p0.50:   2.908 ms/op
                 existUser·p0.90:   3.412 ms/op
                 existUser·p0.95:   3.670 ms/op
                 existUser·p0.99:   4.975 ms/op
                 existUser·p0.999:  11.530 ms/op
                 existUser·p0.9999: 17.810 ms/op
                 existUser·p1.00:   18.809 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 325648
  mean =      2.948 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1631 
    [ 1.250,  2.500) = 35294 
    [ 2.500,  3.750) = 275257 
    [ 3.750,  5.000) = 11069 
    [ 5.000,  6.250) = 1156 
    [ 6.250,  7.500) = 616 
    [ 7.500,  8.750) = 262 
    [ 8.750, 10.000) = 63 
    [10.000, 11.250) = 47 
    [11.250, 12.500) = 98 
    [12.500, 13.750) = 64 
    [13.750, 15.000) = 17 
    [15.000, 16.250) = 10 
    [16.250, 17.500) = 44 
    [17.500, 18.750) = 19 

  Percentiles, ms/op:
      p(0.0000) =      0.536 ms/op
     p(50.0000) =      2.912 ms/op
     p(90.0000) =      3.441 ms/op
     p(95.0000) =      3.686 ms/op
     p(99.0000) =      4.686 ms/op
     p(99.9000) =      9.224 ms/op
     p(99.9900) =     16.908 ms/op
     p(99.9990) =     18.578 ms/op
     p(99.9999) =     18.809 ms/op
    p(100.0000) =     18.809 ms/op


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
# Warmup Iteration   1: 4.306 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.250 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.083 ±(99.9%) 0.007 ms/op
Iteration   1: 3.103 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.641 ms/op
                 getUser·p0.50:   3.064 ms/op
                 getUser·p0.90:   3.654 ms/op
                 getUser·p0.95:   3.920 ms/op
                 getUser·p0.99:   4.817 ms/op
                 getUser·p0.999:  9.630 ms/op
                 getUser·p0.9999: 20.152 ms/op
                 getUser·p1.00:   21.561 ms/op

Iteration   2: 3.111 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.808 ms/op
                 getUser·p0.50:   3.072 ms/op
                 getUser·p0.90:   3.662 ms/op
                 getUser·p0.95:   3.871 ms/op
                 getUser·p0.99:   4.801 ms/op
                 getUser·p0.999:  7.955 ms/op
                 getUser·p0.9999: 15.010 ms/op
                 getUser·p1.00:   15.368 ms/op

Iteration   3: 3.047 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.844 ms/op
                 getUser·p0.50:   3.011 ms/op
                 getUser·p0.90:   3.494 ms/op
                 getUser·p0.95:   3.764 ms/op
                 getUser·p0.99:   4.841 ms/op
                 getUser·p0.999:  8.633 ms/op
                 getUser·p0.9999: 20.562 ms/op
                 getUser·p1.00:   21.037 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 311240
  mean =      3.087 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17909 
    [ 2.500,  5.000) = 290840 
    [ 5.000,  7.500) = 1996 
    [ 7.500, 10.000) = 319 
    [10.000, 12.500) = 16 
    [12.500, 15.000) = 54 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 53 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.641 ms/op
     p(50.0000) =      3.047 ms/op
     p(90.0000) =      3.616 ms/op
     p(95.0000) =      3.858 ms/op
     p(99.0000) =      4.817 ms/op
     p(99.9000) =      8.581 ms/op
     p(99.9900) =     19.988 ms/op
     p(99.9990) =     21.026 ms/op
     p(99.9999) =     21.561 ms/op
    p(100.0000) =     21.561 ms/op


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
# Warmup Iteration   1: 5.598 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 4.234 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.128 ±(99.9%) 0.014 ms/op
Iteration   1: 4.154 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.118 ms/op
                 listUser·p0.50:   3.883 ms/op
                 listUser·p0.90:   5.497 ms/op
                 listUser·p0.95:   6.177 ms/op
                 listUser·p0.99:   8.073 ms/op
                 listUser·p0.999:  16.154 ms/op
                 listUser·p0.9999: 21.581 ms/op
                 listUser·p1.00:   22.020 ms/op

Iteration   2: 4.112 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.927 ms/op
                 listUser·p0.50:   3.883 ms/op
                 listUser·p0.90:   5.333 ms/op
                 listUser·p0.95:   6.185 ms/op
                 listUser·p0.99:   7.668 ms/op
                 listUser·p0.999:  16.335 ms/op
                 listUser·p0.9999: 17.990 ms/op
                 listUser·p1.00:   18.416 ms/op

Iteration   3: 4.152 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   0.852 ms/op
                 listUser·p0.50:   3.903 ms/op
                 listUser·p0.90:   5.407 ms/op
                 listUser·p0.95:   6.144 ms/op
                 listUser·p0.99:   7.512 ms/op
                 listUser·p0.999:  18.776 ms/op
                 listUser·p0.9999: 25.490 ms/op
                 listUser·p1.00:   26.018 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 231835
  mean =      4.139 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2989 
    [ 2.500,  5.000) = 194025 
    [ 5.000,  7.500) = 31991 
    [ 7.500, 10.000) = 2000 
    [10.000, 12.500) = 346 
    [12.500, 15.000) = 78 
    [15.000, 17.500) = 229 
    [17.500, 20.000) = 99 
    [20.000, 22.500) = 60 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.852 ms/op
     p(50.0000) =      3.891 ms/op
     p(90.0000) =      5.423 ms/op
     p(95.0000) =      6.169 ms/op
     p(99.0000) =      7.758 ms/op
     p(99.9000) =     16.679 ms/op
     p(99.9900) =     21.680 ms/op
     p(99.9990) =     25.966 ms/op
     p(99.9999) =     26.018 ms/op
    p(100.0000) =     26.018 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.127 ± 3.365  ops/ms
ClientGrpc.existUser                       thrpt       3  10.607 ± 1.140  ops/ms
ClientGrpc.getUser                         thrpt       3  10.345 ± 2.049  ops/ms
ClientGrpc.listUser                        thrpt       3   7.787 ± 1.255  ops/ms
ClientGrpc.createUser                       avgt       3   3.168 ± 0.895   ms/op
ClientGrpc.existUser                        avgt       3   2.961 ± 0.109   ms/op
ClientGrpc.getUser                          avgt       3   3.149 ± 0.790   ms/op
ClientGrpc.listUser                         avgt       3   4.031 ± 0.427   ms/op
ClientGrpc.createUser                     sample  309375   3.104 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.723           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.056           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.703           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.985           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.186           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.588           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.031           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          19.333           ms/op
ClientGrpc.existUser                      sample  325648   2.948 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.536           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.912           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.441           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.686           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.686           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.224           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.908           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.809           ms/op
ClientGrpc.getUser                        sample  311240   3.087 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.641           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.047           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.616           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.858           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.817           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.581           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.988           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.561           ms/op
ClientGrpc.listUser                       sample  231835   4.139 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.852           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.891           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.423           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.169           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.758           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.679           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.680           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.018           ms/op
