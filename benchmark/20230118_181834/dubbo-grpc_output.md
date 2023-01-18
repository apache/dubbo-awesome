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
# Warmup Iteration   1: 4.260 ops/ms
# Warmup Iteration   2: 8.989 ops/ms
# Warmup Iteration   3: 10.178 ops/ms
Iteration   1: 10.499 ops/ms
Iteration   2: 10.096 ops/ms
Iteration   3: 10.375 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.323 ±(99.9%) 3.765 ops/ms [Average]
  (min, avg, max) = (10.096, 10.323, 10.499), stdev = 0.206
  CI (99.9%): [6.558, 14.088] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.562 ops/ms
# Warmup Iteration   2: 10.320 ops/ms
# Warmup Iteration   3: 10.633 ops/ms
Iteration   1: 10.884 ops/ms
Iteration   2: 10.741 ops/ms
Iteration   3: 10.530 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.718 ±(99.9%) 3.253 ops/ms [Average]
  (min, avg, max) = (10.530, 10.718, 10.884), stdev = 0.178
  CI (99.9%): [7.465, 13.971] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.396 ops/ms
# Warmup Iteration   2: 9.803 ops/ms
# Warmup Iteration   3: 9.980 ops/ms
Iteration   1: 10.181 ops/ms
Iteration   2: 10.171 ops/ms
Iteration   3: 10.036 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.129 ±(99.9%) 1.472 ops/ms [Average]
  (min, avg, max) = (10.036, 10.129, 10.181), stdev = 0.081
  CI (99.9%): [8.657, 11.602] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.418 ops/ms
# Warmup Iteration   2: 7.634 ops/ms
# Warmup Iteration   3: 7.715 ops/ms
Iteration   1: 8.024 ops/ms
Iteration   2: 8.171 ops/ms
Iteration   3: 7.843 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.012 ±(99.9%) 3.000 ops/ms [Average]
  (min, avg, max) = (7.843, 8.012, 8.171), stdev = 0.164
  CI (99.9%): [5.013, 11.012] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.350 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.167 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.091 ±(99.9%) 0.003 ms/op
Iteration   1: 3.103 ±(99.9%) 0.006 ms/op
Iteration   2: 3.149 ±(99.9%) 0.003 ms/op
Iteration   3: 3.099 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.117 ±(99.9%) 0.507 ms/op [Average]
  (min, avg, max) = (3.099, 3.117, 3.149), stdev = 0.028
  CI (99.9%): [2.611, 3.624] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.979 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.181 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.972 ±(99.9%) 0.004 ms/op
Iteration   1: 2.980 ±(99.9%) 0.003 ms/op
Iteration   2: 3.037 ±(99.9%) 0.001 ms/op
Iteration   3: 2.882 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.967 ±(99.9%) 1.429 ms/op [Average]
  (min, avg, max) = (2.882, 2.967, 3.037), stdev = 0.078
  CI (99.9%): [1.537, 4.396] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.127 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.120 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.144 ±(99.9%) 0.002 ms/op
Iteration   1: 3.178 ±(99.9%) 0.002 ms/op
Iteration   2: 3.188 ±(99.9%) 0.001 ms/op
Iteration   3: 3.144 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.170 ±(99.9%) 0.425 ms/op [Average]
  (min, avg, max) = (3.144, 3.170, 3.188), stdev = 0.023
  CI (99.9%): [2.745, 3.595] (assumes normal distribution)


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
# Warmup Iteration   1: 5.658 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 4.154 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.117 ±(99.9%) 0.025 ms/op
Iteration   1: 4.172 ±(99.9%) 0.007 ms/op
Iteration   2: 4.413 ±(99.9%) 0.006 ms/op
Iteration   3: 4.152 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.246 ±(99.9%) 2.648 ms/op [Average]
  (min, avg, max) = (4.152, 4.246, 4.413), stdev = 0.145
  CI (99.9%): [1.597, 6.894] (assumes normal distribution)


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
# Warmup Iteration   1: 5.022 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.514 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.422 ±(99.9%) 0.008 ms/op
Iteration   1: 3.265 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.768 ms/op
                 createUser·p0.50:   3.256 ms/op
                 createUser·p0.90:   3.965 ms/op
                 createUser·p0.95:   4.162 ms/op
                 createUser·p0.99:   4.588 ms/op
                 createUser·p0.999:  7.203 ms/op
                 createUser·p0.9999: 12.659 ms/op
                 createUser·p1.00:   12.927 ms/op

Iteration   2: 3.387 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.408 ms/op
                 createUser·p0.50:   3.326 ms/op
                 createUser·p0.90:   4.174 ms/op
                 createUser·p0.95:   4.424 ms/op
                 createUser·p0.99:   4.907 ms/op
                 createUser·p0.999:  7.511 ms/op
                 createUser·p0.9999: 15.099 ms/op
                 createUser·p1.00:   15.745 ms/op

Iteration   3: 3.225 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.939 ms/op
                 createUser·p0.50:   3.199 ms/op
                 createUser·p0.90:   3.883 ms/op
                 createUser·p0.95:   4.076 ms/op
                 createUser·p0.99:   4.547 ms/op
                 createUser·p0.999:  7.347 ms/op
                 createUser·p0.9999: 16.572 ms/op
                 createUser·p1.00:   17.531 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 291685
  mean =      3.290 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 367 
    [ 1.250,  2.500) = 14947 
    [ 2.500,  3.750) = 220884 
    [ 3.750,  5.000) = 53958 
    [ 5.000,  6.250) = 1016 
    [ 6.250,  7.500) = 239 
    [ 7.500,  8.750) = 44 
    [ 8.750, 10.000) = 6 
    [10.000, 11.250) = 25 
    [11.250, 12.500) = 54 
    [12.500, 13.750) = 18 
    [13.750, 15.000) = 58 
    [15.000, 16.250) = 43 
    [16.250, 17.500) = 25 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.408 ms/op
     p(50.0000) =      3.256 ms/op
     p(90.0000) =      4.002 ms/op
     p(95.0000) =      4.235 ms/op
     p(99.0000) =      4.735 ms/op
     p(99.9000) =      7.302 ms/op
     p(99.9900) =     16.165 ms/op
     p(99.9990) =     17.334 ms/op
     p(99.9999) =     17.531 ms/op
    p(100.0000) =     17.531 ms/op


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
# Warmup Iteration   1: 3.702 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.133 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.961 ±(99.9%) 0.006 ms/op
Iteration   1: 3.025 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.652 ms/op
                 existUser·p0.50:   3.023 ms/op
                 existUser·p0.90:   3.666 ms/op
                 existUser·p0.95:   3.817 ms/op
                 existUser·p0.99:   4.145 ms/op
                 existUser·p0.999:  6.193 ms/op
                 existUser·p0.9999: 13.201 ms/op
                 existUser·p1.00:   13.795 ms/op

Iteration   2: 3.001 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.849 ms/op
                 existUser·p0.50:   3.019 ms/op
                 existUser·p0.90:   3.727 ms/op
                 existUser·p0.95:   3.895 ms/op
                 existUser·p0.99:   4.211 ms/op
                 existUser·p0.999:  7.540 ms/op
                 existUser·p0.9999: 16.144 ms/op
                 existUser·p1.00:   16.515 ms/op

Iteration   3: 3.022 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.507 ms/op
                 existUser·p0.50:   3.002 ms/op
                 existUser·p0.90:   3.731 ms/op
                 existUser·p0.95:   3.903 ms/op
                 existUser·p0.99:   4.153 ms/op
                 existUser·p0.999:  5.699 ms/op
                 existUser·p0.9999: 17.826 ms/op
                 existUser·p1.00:   18.252 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 318109
  mean =      3.016 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1508 
    [ 1.250,  2.500) = 46252 
    [ 2.500,  3.750) = 243121 
    [ 3.750,  5.000) = 26597 
    [ 5.000,  6.250) = 320 
    [ 6.250,  7.500) = 139 
    [ 7.500,  8.750) = 44 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 10 
    [12.500, 13.750) = 22 
    [13.750, 15.000) = 19 
    [15.000, 16.250) = 49 
    [16.250, 17.500) = 11 
    [17.500, 18.750) = 17 

  Percentiles, ms/op:
      p(0.0000) =      0.507 ms/op
     p(50.0000) =      3.015 ms/op
     p(90.0000) =      3.707 ms/op
     p(95.0000) =      3.871 ms/op
     p(99.0000) =      4.170 ms/op
     p(99.9000) =      6.217 ms/op
     p(99.9900) =     16.161 ms/op
     p(99.9990) =     18.115 ms/op
     p(99.9999) =     18.252 ms/op
    p(100.0000) =     18.252 ms/op


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
# Warmup Iteration   1: 4.223 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.234 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.084 ±(99.9%) 0.006 ms/op
Iteration   1: 3.140 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.895 ms/op
                 getUser·p0.50:   3.105 ms/op
                 getUser·p0.90:   3.760 ms/op
                 getUser·p0.95:   3.969 ms/op
                 getUser·p0.99:   4.465 ms/op
                 getUser·p0.999:  7.512 ms/op
                 getUser·p0.9999: 12.354 ms/op
                 getUser·p1.00:   12.648 ms/op

Iteration   2: 3.128 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.794 ms/op
                 getUser·p0.50:   3.092 ms/op
                 getUser·p0.90:   3.781 ms/op
                 getUser·p0.95:   3.969 ms/op
                 getUser·p0.99:   4.342 ms/op
                 getUser·p0.999:  7.360 ms/op
                 getUser·p0.9999: 15.521 ms/op
                 getUser·p1.00:   16.482 ms/op

Iteration   3: 3.186 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.776 ms/op
                 getUser·p0.50:   3.170 ms/op
                 getUser·p0.90:   3.834 ms/op
                 getUser·p0.95:   3.998 ms/op
                 getUser·p0.99:   4.334 ms/op
                 getUser·p0.999:  7.937 ms/op
                 getUser·p0.9999: 16.514 ms/op
                 getUser·p1.00:   16.876 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 304516
  mean =      3.151 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 360 
    [ 1.250,  2.500) = 21098 
    [ 2.500,  3.750) = 247380 
    [ 3.750,  5.000) = 34581 
    [ 5.000,  6.250) = 607 
    [ 6.250,  7.500) = 158 
    [ 7.500,  8.750) = 133 
    [ 8.750, 10.000) = 36 
    [10.000, 11.250) = 5 
    [11.250, 12.500) = 56 
    [12.500, 13.750) = 29 
    [13.750, 15.000) = 36 
    [15.000, 16.250) = 20 
    [16.250, 17.500) = 17 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.776 ms/op
     p(50.0000) =      3.121 ms/op
     p(90.0000) =      3.797 ms/op
     p(95.0000) =      3.981 ms/op
     p(99.0000) =      4.375 ms/op
     p(99.9000) =      7.803 ms/op
     p(99.9900) =     15.370 ms/op
     p(99.9990) =     16.759 ms/op
     p(99.9999) =     16.876 ms/op
    p(100.0000) =     16.876 ms/op


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
# Warmup Iteration   1: 4.942 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 4.144 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.065 ±(99.9%) 0.011 ms/op
Iteration   1: 3.916 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.243 ms/op
                 listUser·p0.50:   3.781 ms/op
                 listUser·p0.90:   4.932 ms/op
                 listUser·p0.95:   5.775 ms/op
                 listUser·p0.99:   6.934 ms/op
                 listUser·p0.999:  13.091 ms/op
                 listUser·p0.9999: 19.071 ms/op
                 listUser·p1.00:   19.497 ms/op

Iteration   2: 4.017 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.782 ms/op
                 listUser·p0.50:   3.895 ms/op
                 listUser·p0.90:   5.022 ms/op
                 listUser·p0.95:   5.628 ms/op
                 listUser·p0.99:   6.758 ms/op
                 listUser·p0.999:  16.325 ms/op
                 listUser·p0.9999: 22.389 ms/op
                 listUser·p1.00:   23.790 ms/op

Iteration   3: 4.043 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.037 ms/op
                 listUser·p0.50:   3.871 ms/op
                 listUser·p0.90:   5.300 ms/op
                 listUser·p0.95:   5.939 ms/op
                 listUser·p0.99:   6.922 ms/op
                 listUser·p0.999:  17.072 ms/op
                 listUser·p0.9999: 24.484 ms/op
                 listUser·p1.00:   24.904 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 240336
  mean =      3.991 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4649 
    [ 2.500,  5.000) = 209464 
    [ 5.000,  7.500) = 25062 
    [ 7.500, 10.000) = 775 
    [10.000, 12.500) = 38 
    [12.500, 15.000) = 76 
    [15.000, 17.500) = 149 
    [17.500, 20.000) = 58 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 33 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.782 ms/op
     p(50.0000) =      3.850 ms/op
     p(90.0000) =      5.104 ms/op
     p(95.0000) =      5.784 ms/op
     p(99.0000) =      6.865 ms/op
     p(99.9000) =     15.969 ms/op
     p(99.9900) =     23.034 ms/op
     p(99.9990) =     24.779 ms/op
     p(99.9999) =     24.904 ms/op
    p(100.0000) =     24.904 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.323 ± 3.765  ops/ms
ClientGrpc.existUser                       thrpt       3  10.718 ± 3.253  ops/ms
ClientGrpc.getUser                         thrpt       3  10.129 ± 1.472  ops/ms
ClientGrpc.listUser                        thrpt       3   8.012 ± 3.000  ops/ms
ClientGrpc.createUser                       avgt       3   3.117 ± 0.507   ms/op
ClientGrpc.existUser                        avgt       3   2.967 ± 1.429   ms/op
ClientGrpc.getUser                          avgt       3   3.170 ± 0.425   ms/op
ClientGrpc.listUser                         avgt       3   4.246 ± 2.648   ms/op
ClientGrpc.createUser                     sample  291685   3.290 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.408           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.256           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.002           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.235           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.735           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.302           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          16.165           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          17.531           ms/op
ClientGrpc.existUser                      sample  318109   3.016 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.507           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.015           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.707           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.871           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.170           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.217           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.161           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.252           ms/op
ClientGrpc.getUser                        sample  304516   3.151 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.776           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.121           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.797           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.981           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.375           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.803           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          15.370           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          16.876           ms/op
ClientGrpc.listUser                       sample  240336   3.991 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.782           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.850           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.104           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.784           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.865           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.969           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.034           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.904           ms/op
