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
# Warmup Iteration   1: 4.684 ops/ms
# Warmup Iteration   2: 9.419 ops/ms
# Warmup Iteration   3: 10.565 ops/ms
Iteration   1: 10.671 ops/ms
Iteration   2: 10.780 ops/ms
Iteration   3: 10.787 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.746 ±(99.9%) 1.178 ops/ms [Average]
  (min, avg, max) = (10.671, 10.746, 10.787), stdev = 0.065
  CI (99.9%): [9.567, 11.924] (assumes normal distribution)


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
# Warmup Iteration   1: 7.883 ops/ms
# Warmup Iteration   2: 10.892 ops/ms
# Warmup Iteration   3: 11.047 ops/ms
Iteration   1: 11.167 ops/ms
Iteration   2: 11.435 ops/ms
Iteration   3: 11.300 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.301 ±(99.9%) 2.443 ops/ms [Average]
  (min, avg, max) = (11.167, 11.301, 11.435), stdev = 0.134
  CI (99.9%): [8.857, 13.744] (assumes normal distribution)


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
# Warmup Iteration   1: 7.530 ops/ms
# Warmup Iteration   2: 10.500 ops/ms
# Warmup Iteration   3: 10.652 ops/ms
Iteration   1: 10.687 ops/ms
Iteration   2: 10.944 ops/ms
Iteration   3: 10.661 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.764 ±(99.9%) 2.855 ops/ms [Average]
  (min, avg, max) = (10.661, 10.764, 10.944), stdev = 0.156
  CI (99.9%): [7.909, 13.618] (assumes normal distribution)


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
# Warmup Iteration   2: 8.251 ops/ms
# Warmup Iteration   3: 8.177 ops/ms
Iteration   1: 8.400 ops/ms
Iteration   2: 8.272 ops/ms
Iteration   3: 8.152 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.275 ±(99.9%) 2.259 ops/ms [Average]
  (min, avg, max) = (8.152, 8.275, 8.400), stdev = 0.124
  CI (99.9%): [6.016, 10.533] (assumes normal distribution)


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
# Warmup Iteration   1: 3.419 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 3.080 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.992 ±(99.9%) 0.002 ms/op
Iteration   1: 2.900 ±(99.9%) 0.003 ms/op
Iteration   2: 2.999 ±(99.9%) 0.003 ms/op
Iteration   3: 2.915 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.938 ±(99.9%) 0.974 ms/op [Average]
  (min, avg, max) = (2.900, 2.938, 2.999), stdev = 0.053
  CI (99.9%): [1.964, 3.912] (assumes normal distribution)


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
# Warmup Iteration   1: 3.620 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 2.964 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.867 ±(99.9%) 0.003 ms/op
Iteration   1: 2.862 ±(99.9%) 0.004 ms/op
Iteration   2: 2.845 ±(99.9%) 0.004 ms/op
Iteration   3: 2.878 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.862 ±(99.9%) 0.302 ms/op [Average]
  (min, avg, max) = (2.845, 2.862, 2.878), stdev = 0.017
  CI (99.9%): [2.559, 3.164] (assumes normal distribution)


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
# Warmup Iteration   1: 3.676 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 3.024 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.975 ±(99.9%) 0.002 ms/op
Iteration   1: 2.938 ±(99.9%) 0.002 ms/op
Iteration   2: 2.952 ±(99.9%) 0.002 ms/op
Iteration   3: 2.974 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.955 ±(99.9%) 0.338 ms/op [Average]
  (min, avg, max) = (2.938, 2.955, 2.974), stdev = 0.019
  CI (99.9%): [2.617, 3.293] (assumes normal distribution)


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
# Warmup Iteration   1: 5.084 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.007 ±(99.9%) 0.052 ms/op
# Warmup Iteration   3: 3.953 ±(99.9%) 0.006 ms/op
Iteration   1: 3.868 ±(99.9%) 0.038 ms/op
Iteration   2: 3.799 ±(99.9%) 0.023 ms/op
Iteration   3: 3.898 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.855 ±(99.9%) 0.928 ms/op [Average]
  (min, avg, max) = (3.799, 3.855, 3.898), stdev = 0.051
  CI (99.9%): [2.928, 4.783] (assumes normal distribution)


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
# Warmup Iteration   1: 4.123 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.112 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.943 ±(99.9%) 0.007 ms/op
Iteration   1: 2.961 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.727 ms/op
                 createUser·p0.50:   2.953 ms/op
                 createUser·p0.90:   3.539 ms/op
                 createUser·p0.95:   3.793 ms/op
                 createUser·p0.99:   4.497 ms/op
                 createUser·p0.999:  7.676 ms/op
                 createUser·p0.9999: 12.016 ms/op
                 createUser·p1.00:   12.386 ms/op

Iteration   2: 2.976 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.317 ms/op
                 createUser·p0.50:   2.953 ms/op
                 createUser·p0.90:   3.424 ms/op
                 createUser·p0.95:   3.662 ms/op
                 createUser·p0.99:   4.456 ms/op
                 createUser·p0.999:  9.675 ms/op
                 createUser·p0.9999: 18.784 ms/op
                 createUser·p1.00:   20.382 ms/op

Iteration   3: 3.012 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.542 ms/op
                 createUser·p0.50:   2.974 ms/op
                 createUser·p0.90:   3.478 ms/op
                 createUser·p0.95:   3.690 ms/op
                 createUser·p0.99:   4.399 ms/op
                 createUser·p0.999:  11.556 ms/op
                 createUser·p0.9999: 17.170 ms/op
                 createUser·p1.00:   21.955 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 321634
  mean =      2.983 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 30161 
    [ 2.500,  5.000) = 290074 
    [ 5.000,  7.500) = 964 
    [ 7.500, 10.000) = 108 
    [10.000, 12.500) = 159 
    [12.500, 15.000) = 84 
    [15.000, 17.500) = 53 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.317 ms/op
     p(50.0000) =      2.961 ms/op
     p(90.0000) =      3.478 ms/op
     p(95.0000) =      3.719 ms/op
     p(99.0000) =      4.456 ms/op
     p(99.9000) =     10.403 ms/op
     p(99.9900) =     17.170 ms/op
     p(99.9990) =     18.966 ms/op
     p(99.9999) =     21.955 ms/op
    p(100.0000) =     21.955 ms/op


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
# Warmup Iteration   1: 3.489 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 2.950 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.838 ±(99.9%) 0.006 ms/op
Iteration   1: 2.863 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.626 ms/op
                 existUser·p0.50:   2.863 ms/op
                 existUser·p0.90:   3.330 ms/op
                 existUser·p0.95:   3.510 ms/op
                 existUser·p0.99:   4.375 ms/op
                 existUser·p0.999:  6.034 ms/op
                 existUser·p0.9999: 13.282 ms/op
                 existUser·p1.00:   13.648 ms/op

Iteration   2: 2.807 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.553 ms/op
                 existUser·p0.50:   2.834 ms/op
                 existUser·p0.90:   3.351 ms/op
                 existUser·p0.95:   3.600 ms/op
                 existUser·p0.99:   4.391 ms/op
                 existUser·p0.999:  5.659 ms/op
                 existUser·p0.9999: 23.429 ms/op
                 existUser·p1.00:   23.658 ms/op

Iteration   3: 2.827 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.627 ms/op
                 existUser·p0.50:   2.847 ms/op
                 existUser·p0.90:   3.142 ms/op
                 existUser·p0.95:   3.269 ms/op
                 existUser·p0.99:   3.985 ms/op
                 existUser·p0.999:  6.741 ms/op
                 existUser·p0.9999: 13.730 ms/op
                 existUser·p1.00:   15.106 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 338949
  mean =      2.832 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 49020 
    [ 2.500,  5.000) = 288945 
    [ 5.000,  7.500) = 768 
    [ 7.500, 10.000) = 14 
    [10.000, 12.500) = 47 
    [12.500, 15.000) = 121 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.553 ms/op
     p(50.0000) =      2.847 ms/op
     p(90.0000) =      3.273 ms/op
     p(95.0000) =      3.498 ms/op
     p(99.0000) =      4.309 ms/op
     p(99.9000) =      6.029 ms/op
     p(99.9900) =     15.077 ms/op
     p(99.9990) =     23.547 ms/op
     p(99.9999) =     23.658 ms/op
    p(100.0000) =     23.658 ms/op


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
# Warmup Iteration   1: 3.867 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.031 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.970 ±(99.9%) 0.006 ms/op
Iteration   1: 2.974 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.741 ms/op
                 getUser·p0.50:   2.974 ms/op
                 getUser·p0.90:   3.449 ms/op
                 getUser·p0.95:   3.584 ms/op
                 getUser·p0.99:   4.194 ms/op
                 getUser·p0.999:  6.310 ms/op
                 getUser·p0.9999: 11.563 ms/op
                 getUser·p1.00:   11.928 ms/op

Iteration   2: 2.974 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.726 ms/op
                 getUser·p0.50:   2.970 ms/op
                 getUser·p0.90:   3.523 ms/op
                 getUser·p0.95:   3.719 ms/op
                 getUser·p0.99:   4.284 ms/op
                 getUser·p0.999:  7.254 ms/op
                 getUser·p0.9999: 13.054 ms/op
                 getUser·p1.00:   13.533 ms/op

Iteration   3: 2.977 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.604 ms/op
                 getUser·p0.50:   2.966 ms/op
                 getUser·p0.90:   3.539 ms/op
                 getUser·p0.95:   3.752 ms/op
                 getUser·p0.99:   4.301 ms/op
                 getUser·p0.999:  6.763 ms/op
                 getUser·p0.9999: 15.524 ms/op
                 getUser·p1.00:   16.187 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 322509
  mean =      2.975 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1980 
    [ 1.250,  2.500) = 25003 
    [ 2.500,  3.750) = 282334 
    [ 3.750,  5.000) = 12047 
    [ 5.000,  6.250) = 702 
    [ 6.250,  7.500) = 217 
    [ 7.500,  8.750) = 60 
    [ 8.750, 10.000) = 6 
    [10.000, 11.250) = 45 
    [11.250, 12.500) = 22 
    [12.500, 13.750) = 50 
    [13.750, 15.000) = 17 
    [15.000, 16.250) = 26 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.604 ms/op
     p(50.0000) =      2.970 ms/op
     p(90.0000) =      3.498 ms/op
     p(95.0000) =      3.695 ms/op
     p(99.0000) =      4.276 ms/op
     p(99.9000) =      6.791 ms/op
     p(99.9900) =     14.156 ms/op
     p(99.9990) =     15.763 ms/op
     p(99.9999) =     16.187 ms/op
    p(100.0000) =     16.187 ms/op


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
# Warmup Iteration   1: 5.132 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.908 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.946 ±(99.9%) 0.010 ms/op
Iteration   1: 3.860 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.981 ms/op
                 listUser·p0.50:   3.736 ms/op
                 listUser·p0.90:   4.907 ms/op
                 listUser·p0.95:   5.573 ms/op
                 listUser·p0.99:   6.963 ms/op
                 listUser·p0.999:  12.419 ms/op
                 listUser·p0.9999: 14.711 ms/op
                 listUser·p1.00:   15.598 ms/op

Iteration   2: 3.867 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.834 ms/op
                 listUser·p0.50:   3.707 ms/op
                 listUser·p0.90:   5.005 ms/op
                 listUser·p0.95:   5.505 ms/op
                 listUser·p0.99:   6.892 ms/op
                 listUser·p0.999:  14.860 ms/op
                 listUser·p0.9999: 21.978 ms/op
                 listUser·p1.00:   25.264 ms/op

Iteration   3: 3.875 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.016 ms/op
                 listUser·p0.50:   3.727 ms/op
                 listUser·p0.90:   4.825 ms/op
                 listUser·p0.95:   5.448 ms/op
                 listUser·p0.99:   6.955 ms/op
                 listUser·p0.999:  14.079 ms/op
                 listUser·p0.9999: 18.758 ms/op
                 listUser·p1.00:   19.268 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 248396
  mean =      3.867 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5767 
    [ 2.500,  5.000) = 220314 
    [ 5.000,  7.500) = 20828 
    [ 7.500, 10.000) = 890 
    [10.000, 12.500) = 230 
    [12.500, 15.000) = 243 
    [15.000, 17.500) = 81 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.834 ms/op
     p(50.0000) =      3.723 ms/op
     p(90.0000) =      4.915 ms/op
     p(95.0000) =      5.513 ms/op
     p(99.0000) =      6.931 ms/op
     p(99.9000) =     13.795 ms/op
     p(99.9900) =     21.529 ms/op
     p(99.9990) =     22.004 ms/op
     p(99.9999) =     25.264 ms/op
    p(100.0000) =     25.264 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.746 ± 1.178  ops/ms
ClientGrpc.existUser                       thrpt       3  11.301 ± 2.443  ops/ms
ClientGrpc.getUser                         thrpt       3  10.764 ± 2.855  ops/ms
ClientGrpc.listUser                        thrpt       3   8.275 ± 2.259  ops/ms
ClientGrpc.createUser                       avgt       3   2.938 ± 0.974   ms/op
ClientGrpc.existUser                        avgt       3   2.862 ± 0.302   ms/op
ClientGrpc.getUser                          avgt       3   2.955 ± 0.338   ms/op
ClientGrpc.listUser                         avgt       3   3.855 ± 0.928   ms/op
ClientGrpc.createUser                     sample  321634   2.983 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.317           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.961           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.478           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.719           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.456           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.403           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.170           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.955           ms/op
ClientGrpc.existUser                      sample  338949   2.832 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.553           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.847           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.273           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.498           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.309           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.029           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.077           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          23.658           ms/op
ClientGrpc.getUser                        sample  322509   2.975 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.604           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.970           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.498           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.695           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.276           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.791           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          14.156           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          16.187           ms/op
ClientGrpc.listUser                       sample  248396   3.867 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.834           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.723           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.915           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.513           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.931           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.795           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.529           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.264           ms/op
