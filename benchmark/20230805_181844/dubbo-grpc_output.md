# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.728 ops/ms
# Warmup Iteration   2: 8.997 ops/ms
# Warmup Iteration   3: 10.802 ops/ms
Iteration   1: 10.592 ops/ms
Iteration   2: 10.608 ops/ms
Iteration   3: 10.488 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.563 ±(99.9%) 1.187 ops/ms [Average]
  (min, avg, max) = (10.488, 10.563, 10.608), stdev = 0.065
  CI (99.9%): [9.375, 11.750] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 7.744 ops/ms
# Warmup Iteration   2: 10.915 ops/ms
# Warmup Iteration   3: 11.031 ops/ms
Iteration   1: 11.276 ops/ms
Iteration   2: 11.367 ops/ms
Iteration   3: 11.285 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.310 ±(99.9%) 0.913 ops/ms [Average]
  (min, avg, max) = (11.276, 11.310, 11.367), stdev = 0.050
  CI (99.9%): [10.397, 12.222] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 8.272 ops/ms
# Warmup Iteration   2: 10.454 ops/ms
# Warmup Iteration   3: 10.543 ops/ms
Iteration   1: 10.636 ops/ms
Iteration   2: 10.591 ops/ms
Iteration   3: 10.891 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.706 ±(99.9%) 2.952 ops/ms [Average]
  (min, avg, max) = (10.591, 10.706, 10.891), stdev = 0.162
  CI (99.9%): [7.754, 13.658] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.870 ops/ms
# Warmup Iteration   2: 7.999 ops/ms
# Warmup Iteration   3: 8.122 ops/ms
Iteration   1: 8.148 ops/ms
Iteration   2: 8.204 ops/ms
Iteration   3: 8.309 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.220 ±(99.9%) 1.495 ops/ms [Average]
  (min, avg, max) = (8.148, 8.220, 8.309), stdev = 0.082
  CI (99.9%): [6.725, 9.715] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.975 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.135 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.031 ±(99.9%) 0.003 ms/op
Iteration   1: 3.051 ±(99.9%) 0.003 ms/op
Iteration   2: 3.018 ±(99.9%) 0.002 ms/op
Iteration   3: 3.051 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.040 ±(99.9%) 0.347 ms/op [Average]
  (min, avg, max) = (3.018, 3.040, 3.051), stdev = 0.019
  CI (99.9%): [2.693, 3.387] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.880 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.867 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.848 ±(99.9%) 0.003 ms/op
Iteration   1: 2.867 ±(99.9%) 0.004 ms/op
Iteration   2: 2.855 ±(99.9%) 0.003 ms/op
Iteration   3: 2.804 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.842 ±(99.9%) 0.604 ms/op [Average]
  (min, avg, max) = (2.804, 2.842, 2.867), stdev = 0.033
  CI (99.9%): [2.238, 3.446] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.196 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.074 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.964 ±(99.9%) 0.003 ms/op
Iteration   1: 3.010 ±(99.9%) 0.004 ms/op
Iteration   2: 2.983 ±(99.9%) 0.002 ms/op
Iteration   3: 2.995 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.996 ±(99.9%) 0.246 ms/op [Average]
  (min, avg, max) = (2.983, 2.996, 3.010), stdev = 0.013
  CI (99.9%): [2.750, 3.242] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.692 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 4.089 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.969 ±(99.9%) 0.025 ms/op
Iteration   1: 3.921 ±(99.9%) 0.008 ms/op
Iteration   2: 3.888 ±(99.9%) 0.015 ms/op
Iteration   3: 3.975 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.928 ±(99.9%) 0.805 ms/op [Average]
  (min, avg, max) = (3.888, 3.928, 3.975), stdev = 0.044
  CI (99.9%): [3.123, 4.733] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.983 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.177 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.042 ±(99.9%) 0.007 ms/op
Iteration   1: 2.994 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.809 ms/op
                 createUser·p0.50:   2.978 ms/op
                 createUser·p0.90:   3.457 ms/op
                 createUser·p0.95:   3.686 ms/op
                 createUser·p0.99:   4.350 ms/op
                 createUser·p0.999:  7.276 ms/op
                 createUser·p0.9999: 15.979 ms/op
                 createUser·p1.00:   16.302 ms/op

Iteration   2: 2.966 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.555 ms/op
                 createUser·p0.50:   2.961 ms/op
                 createUser·p0.90:   3.334 ms/op
                 createUser·p0.95:   3.465 ms/op
                 createUser·p0.99:   4.325 ms/op
                 createUser·p0.999:  7.234 ms/op
                 createUser·p0.9999: 14.343 ms/op
                 createUser·p1.00:   14.565 ms/op

Iteration   3: 2.987 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.557 ms/op
                 createUser·p0.50:   2.966 ms/op
                 createUser·p0.90:   3.478 ms/op
                 createUser·p0.95:   3.715 ms/op
                 createUser·p0.99:   4.628 ms/op
                 createUser·p0.999:  10.577 ms/op
                 createUser·p0.9999: 30.835 ms/op
                 createUser·p1.00:   30.867 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 321995
  mean =      2.982 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25042 
    [ 2.500,  5.000) = 295031 
    [ 5.000,  7.500) = 1513 
    [ 7.500, 10.000) = 153 
    [10.000, 12.500) = 91 
    [12.500, 15.000) = 41 
    [15.000, 17.500) = 60 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 27 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.555 ms/op
     p(50.0000) =      2.970 ms/op
     p(90.0000) =      3.412 ms/op
     p(95.0000) =      3.645 ms/op
     p(99.0000) =      4.440 ms/op
     p(99.9000) =      8.372 ms/op
     p(99.9900) =     29.369 ms/op
     p(99.9990) =     30.867 ms/op
     p(99.9999) =     30.867 ms/op
    p(100.0000) =     30.867 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.900 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 2.977 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.893 ±(99.9%) 0.006 ms/op
Iteration   1: 2.839 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.696 ms/op
                 existUser·p0.50:   2.826 ms/op
                 existUser·p0.90:   3.289 ms/op
                 existUser·p0.95:   3.609 ms/op
                 existUser·p0.99:   4.538 ms/op
                 existUser·p0.999:  7.567 ms/op
                 existUser·p0.9999: 11.804 ms/op
                 existUser·p1.00:   12.255 ms/op

Iteration   2: 2.864 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.771 ms/op
                 existUser·p0.50:   2.843 ms/op
                 existUser·p0.90:   3.359 ms/op
                 existUser·p0.95:   3.654 ms/op
                 existUser·p0.99:   4.430 ms/op
                 existUser·p0.999:  7.053 ms/op
                 existUser·p0.9999: 19.650 ms/op
                 existUser·p1.00:   19.890 ms/op

Iteration   3: 2.884 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.818 ms/op
                 existUser·p0.50:   2.867 ms/op
                 existUser·p0.90:   3.265 ms/op
                 existUser·p0.95:   3.473 ms/op
                 existUser·p0.99:   4.383 ms/op
                 existUser·p0.999:  7.235 ms/op
                 existUser·p0.9999: 17.760 ms/op
                 existUser·p1.00:   18.022 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 335154
  mean =      2.862 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2400 
    [ 1.250,  2.500) = 47205 
    [ 2.500,  3.750) = 273963 
    [ 3.750,  5.000) = 9956 
    [ 5.000,  6.250) = 869 
    [ 6.250,  7.500) = 498 
    [ 7.500,  8.750) = 82 
    [ 8.750, 10.000) = 21 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 12 
    [16.250, 17.500) = 8 
    [17.500, 18.750) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.696 ms/op
     p(50.0000) =      2.847 ms/op
     p(90.0000) =      3.301 ms/op
     p(95.0000) =      3.584 ms/op
     p(99.0000) =      4.473 ms/op
     p(99.9000) =      7.184 ms/op
     p(99.9900) =     18.022 ms/op
     p(99.9990) =     19.813 ms/op
     p(99.9999) =     19.890 ms/op
    p(100.0000) =     19.890 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.837 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.117 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.001 ±(99.9%) 0.006 ms/op
Iteration   1: 2.972 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.781 ms/op
                 getUser·p0.50:   2.974 ms/op
                 getUser·p0.90:   3.482 ms/op
                 getUser·p0.95:   3.695 ms/op
                 getUser·p0.99:   4.268 ms/op
                 getUser·p0.999:  7.248 ms/op
                 getUser·p0.9999: 11.952 ms/op
                 getUser·p1.00:   12.255 ms/op

Iteration   2: 2.977 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.494 ms/op
                 getUser·p0.50:   2.961 ms/op
                 getUser·p0.90:   3.465 ms/op
                 getUser·p0.95:   3.731 ms/op
                 getUser·p0.99:   4.424 ms/op
                 getUser·p0.999:  8.978 ms/op
                 getUser·p0.9999: 19.775 ms/op
                 getUser·p1.00:   20.152 ms/op

Iteration   3: 3.029 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.801 ms/op
                 getUser·p0.50:   3.006 ms/op
                 getUser·p0.90:   3.572 ms/op
                 getUser·p0.95:   3.748 ms/op
                 getUser·p0.99:   4.219 ms/op
                 getUser·p0.999:  7.291 ms/op
                 getUser·p0.9999: 24.969 ms/op
                 getUser·p1.00:   27.460 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 320632
  mean =      2.993 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26215 
    [ 2.500,  5.000) = 292838 
    [ 5.000,  7.500) = 1188 
    [ 7.500, 10.000) = 197 
    [10.000, 12.500) = 74 
    [12.500, 15.000) = 39 
    [15.000, 17.500) = 17 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.494 ms/op
     p(50.0000) =      2.978 ms/op
     p(90.0000) =      3.510 ms/op
     p(95.0000) =      3.727 ms/op
     p(99.0000) =      4.309 ms/op
     p(99.9000) =      7.744 ms/op
     p(99.9900) =     24.327 ms/op
     p(99.9990) =     27.267 ms/op
     p(99.9999) =     27.460 ms/op
    p(100.0000) =     27.460 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.203 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 4.070 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.934 ±(99.9%) 0.011 ms/op
Iteration   1: 3.926 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.874 ms/op
                 listUser·p0.50:   3.760 ms/op
                 listUser·p0.90:   4.981 ms/op
                 listUser·p0.95:   5.729 ms/op
                 listUser·p0.99:   6.939 ms/op
                 listUser·p0.999:  11.903 ms/op
                 listUser·p0.9999: 15.066 ms/op
                 listUser·p1.00:   16.630 ms/op

Iteration   2: 3.808 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.055 ms/op
                 listUser·p0.50:   3.690 ms/op
                 listUser·p0.90:   4.809 ms/op
                 listUser·p0.95:   5.693 ms/op
                 listUser·p0.99:   6.750 ms/op
                 listUser·p0.999:  13.910 ms/op
                 listUser·p0.9999: 26.418 ms/op
                 listUser·p1.00:   26.837 ms/op

Iteration   3: 3.911 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.210 ms/op
                 listUser·p0.50:   3.781 ms/op
                 listUser·p0.90:   4.604 ms/op
                 listUser·p0.95:   5.513 ms/op
                 listUser·p0.99:   6.849 ms/op
                 listUser·p0.999:  15.966 ms/op
                 listUser·p0.9999: 20.054 ms/op
                 listUser·p1.00:   23.364 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 247202
  mean =      3.881 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5092 
    [ 2.500,  5.000) = 221069 
    [ 5.000,  7.500) = 19741 
    [ 7.500, 10.000) = 838 
    [10.000, 12.500) = 161 
    [12.500, 15.000) = 118 
    [15.000, 17.500) = 100 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.874 ms/op
     p(50.0000) =      3.748 ms/op
     p(90.0000) =      4.817 ms/op
     p(95.0000) =      5.661 ms/op
     p(99.0000) =      6.840 ms/op
     p(99.9000) =     13.251 ms/op
     p(99.9900) =     25.919 ms/op
     p(99.9990) =     26.708 ms/op
     p(99.9999) =     26.837 ms/op
    p(100.0000) =     26.837 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.563 ± 1.187  ops/ms
ClientGrpc.existUser                       thrpt       3  11.310 ± 0.913  ops/ms
ClientGrpc.getUser                         thrpt       3  10.706 ± 2.952  ops/ms
ClientGrpc.listUser                        thrpt       3   8.220 ± 1.495  ops/ms
ClientGrpc.createUser                       avgt       3   3.040 ± 0.347   ms/op
ClientGrpc.existUser                        avgt       3   2.842 ± 0.604   ms/op
ClientGrpc.getUser                          avgt       3   2.996 ± 0.246   ms/op
ClientGrpc.listUser                         avgt       3   3.928 ± 0.805   ms/op
ClientGrpc.createUser                     sample  321995   2.982 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.555           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.970           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.412           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.645           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.440           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.372           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          29.369           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          30.867           ms/op
ClientGrpc.existUser                      sample  335154   2.862 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.696           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.847           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.301           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.584           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.473           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.184           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.022           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.890           ms/op
ClientGrpc.getUser                        sample  320632   2.993 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.494           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.978           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.510           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.727           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.309           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.744           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          24.327           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          27.460           ms/op
ClientGrpc.listUser                       sample  247202   3.881 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.874           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.748           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.817           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.661           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.840           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.251           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.919           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.837           ms/op
