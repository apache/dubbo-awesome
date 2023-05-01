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
# Warmup Iteration   1: 3.312 ops/ms
# Warmup Iteration   2: 6.905 ops/ms
# Warmup Iteration   3: 8.249 ops/ms
Iteration   1: 8.799 ops/ms
Iteration   2: 9.148 ops/ms
Iteration   3: 8.755 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.901 ±(99.9%) 3.922 ops/ms [Average]
  (min, avg, max) = (8.755, 8.901, 9.148), stdev = 0.215
  CI (99.9%): [4.979, 12.823] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 7.233 ops/ms
# Warmup Iteration   2: 8.632 ops/ms
# Warmup Iteration   3: 9.141 ops/ms
Iteration   1: 9.322 ops/ms
Iteration   2: 9.314 ops/ms
Iteration   3: 9.285 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.307 ±(99.9%) 0.352 ops/ms [Average]
  (min, avg, max) = (9.285, 9.307, 9.322), stdev = 0.019
  CI (99.9%): [8.955, 9.659] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 5.310 ops/ms
# Warmup Iteration   2: 8.572 ops/ms
# Warmup Iteration   3: 8.815 ops/ms
Iteration   1: 8.671 ops/ms
Iteration   2: 8.971 ops/ms
Iteration   3: 8.694 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.779 ±(99.9%) 3.046 ops/ms [Average]
  (min, avg, max) = (8.671, 8.779, 8.971), stdev = 0.167
  CI (99.9%): [5.733, 11.824] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 4.628 ops/ms
# Warmup Iteration   2: 6.597 ops/ms
# Warmup Iteration   3: 6.962 ops/ms
Iteration   1: 6.961 ops/ms
Iteration   2: 6.775 ops/ms
Iteration   3: 6.949 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.895 ±(99.9%) 1.900 ops/ms [Average]
  (min, avg, max) = (6.775, 6.895, 6.961), stdev = 0.104
  CI (99.9%): [4.995, 8.795] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 5.228 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.911 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.790 ±(99.9%) 0.017 ms/op
Iteration   1: 3.668 ±(99.9%) 0.003 ms/op
Iteration   2: 3.599 ±(99.9%) 0.003 ms/op
Iteration   3: 3.579 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.615 ±(99.9%) 0.857 ms/op [Average]
  (min, avg, max) = (3.579, 3.615, 3.668), stdev = 0.047
  CI (99.9%): [2.758, 4.473] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 4.948 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.557 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.434 ±(99.9%) 0.006 ms/op
Iteration   1: 3.451 ±(99.9%) 0.003 ms/op
Iteration   2: 3.427 ±(99.9%) 0.004 ms/op
Iteration   3: 3.442 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.440 ±(99.9%) 0.217 ms/op [Average]
  (min, avg, max) = (3.427, 3.440, 3.451), stdev = 0.012
  CI (99.9%): [3.223, 3.657] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 5.557 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.690 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.672 ±(99.9%) 0.004 ms/op
Iteration   1: 3.585 ±(99.9%) 0.005 ms/op
Iteration   2: 3.543 ±(99.9%) 0.004 ms/op
Iteration   3: 3.468 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.532 ±(99.9%) 1.075 ms/op [Average]
  (min, avg, max) = (3.468, 3.532, 3.585), stdev = 0.059
  CI (99.9%): [2.457, 4.608] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 6.752 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 5.080 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.689 ±(99.9%) 0.028 ms/op
Iteration   1: 4.705 ±(99.9%) 0.015 ms/op
Iteration   2: 4.611 ±(99.9%) 0.011 ms/op
Iteration   3: 4.607 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.641 ±(99.9%) 1.011 ms/op [Average]
  (min, avg, max) = (4.607, 4.641, 4.705), stdev = 0.055
  CI (99.9%): [3.631, 5.652] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 5.187 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 3.787 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.627 ±(99.9%) 0.009 ms/op
Iteration   1: 3.564 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.963 ms/op
                 createUser·p0.50:   3.568 ms/op
                 createUser·p0.90:   4.358 ms/op
                 createUser·p0.95:   4.604 ms/op
                 createUser·p0.99:   5.784 ms/op
                 createUser·p0.999:  9.191 ms/op
                 createUser·p0.9999: 15.140 ms/op
                 createUser·p1.00:   16.499 ms/op

Iteration   2: 3.615 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.048 ms/op
                 createUser·p0.50:   3.564 ms/op
                 createUser·p0.90:   4.211 ms/op
                 createUser·p0.95:   4.456 ms/op
                 createUser·p0.99:   5.439 ms/op
                 createUser·p0.999:  12.206 ms/op
                 createUser·p0.9999: 16.405 ms/op
                 createUser·p1.00:   16.679 ms/op

Iteration   3: 3.616 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.946 ms/op
                 createUser·p0.50:   3.547 ms/op
                 createUser·p0.90:   4.194 ms/op
                 createUser·p0.95:   4.604 ms/op
                 createUser·p0.99:   5.906 ms/op
                 createUser·p0.999:  15.008 ms/op
                 createUser·p0.9999: 19.801 ms/op
                 createUser·p1.00:   20.251 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 266870
  mean =      3.598 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10934 
    [ 2.500,  5.000) = 249878 
    [ 5.000,  7.500) = 5204 
    [ 7.500, 10.000) = 432 
    [10.000, 12.500) = 187 
    [12.500, 15.000) = 95 
    [15.000, 17.500) = 87 
    [17.500, 20.000) = 48 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.946 ms/op
     p(50.0000) =      3.559 ms/op
     p(90.0000) =      4.260 ms/op
     p(95.0000) =      4.555 ms/op
     p(99.0000) =      5.734 ms/op
     p(99.9000) =     12.206 ms/op
     p(99.9900) =     18.907 ms/op
     p(99.9990) =     20.163 ms/op
     p(99.9999) =     20.251 ms/op
    p(100.0000) =     20.251 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.685 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.810 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.550 ±(99.9%) 0.007 ms/op
Iteration   1: 3.449 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.760 ms/op
                 existUser·p0.50:   3.428 ms/op
                 existUser·p0.90:   4.006 ms/op
                 existUser·p0.95:   4.284 ms/op
                 existUser·p0.99:   5.251 ms/op
                 existUser·p0.999:  10.556 ms/op
                 existUser·p0.9999: 17.653 ms/op
                 existUser·p1.00:   19.464 ms/op

Iteration   2: 3.438 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.697 ms/op
                 existUser·p0.50:   3.416 ms/op
                 existUser·p0.90:   4.022 ms/op
                 existUser·p0.95:   4.391 ms/op
                 existUser·p0.99:   5.725 ms/op
                 existUser·p0.999:  11.468 ms/op
                 existUser·p0.9999: 15.381 ms/op
                 existUser·p1.00:   15.876 ms/op

Iteration   3: 3.519 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.888 ms/op
                 existUser·p0.50:   3.449 ms/op
                 existUser·p0.90:   4.174 ms/op
                 existUser·p0.95:   4.424 ms/op
                 existUser·p0.99:   5.563 ms/op
                 existUser·p0.999:  7.710 ms/op
                 existUser·p0.9999: 24.442 ms/op
                 existUser·p1.00:   25.133 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 276618
  mean =      3.468 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11523 
    [ 2.500,  5.000) = 260202 
    [ 5.000,  7.500) = 4257 
    [ 7.500, 10.000) = 304 
    [10.000, 12.500) = 137 
    [12.500, 15.000) = 74 
    [15.000, 17.500) = 51 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.697 ms/op
     p(50.0000) =      3.432 ms/op
     p(90.0000) =      4.071 ms/op
     p(95.0000) =      4.375 ms/op
     p(99.0000) =      5.546 ms/op
     p(99.9000) =     10.551 ms/op
     p(99.9900) =     23.309 ms/op
     p(99.9990) =     25.035 ms/op
     p(99.9999) =     25.133 ms/op
    p(100.0000) =     25.133 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.042 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.819 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.615 ±(99.9%) 0.008 ms/op
Iteration   1: 3.694 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.034 ms/op
                 getUser·p0.50:   3.637 ms/op
                 getUser·p0.90:   4.440 ms/op
                 getUser·p0.95:   4.768 ms/op
                 getUser·p0.99:   5.890 ms/op
                 getUser·p0.999:  8.539 ms/op
                 getUser·p0.9999: 21.211 ms/op
                 getUser·p1.00:   21.856 ms/op

Iteration   2: 3.573 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.145 ms/op
                 getUser·p0.50:   3.564 ms/op
                 getUser·p0.90:   4.194 ms/op
                 getUser·p0.95:   4.473 ms/op
                 getUser·p0.99:   5.603 ms/op
                 getUser·p0.999:  8.602 ms/op
                 getUser·p0.9999: 19.431 ms/op
                 getUser·p1.00:   19.792 ms/op

Iteration   3: 3.752 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.863 ms/op
                 getUser·p0.50:   3.690 ms/op
                 getUser·p0.90:   4.407 ms/op
                 getUser·p0.95:   4.678 ms/op
                 getUser·p0.99:   5.726 ms/op
                 getUser·p0.999:  10.105 ms/op
                 getUser·p0.9999: 20.610 ms/op
                 getUser·p1.00:   21.168 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 261660
  mean =      3.671 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8749 
    [ 2.500,  5.000) = 246401 
    [ 5.000,  7.500) = 5841 
    [ 7.500, 10.000) = 447 
    [10.000, 12.500) = 62 
    [12.500, 15.000) = 28 
    [15.000, 17.500) = 52 
    [17.500, 20.000) = 49 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.863 ms/op
     p(50.0000) =      3.625 ms/op
     p(90.0000) =      4.358 ms/op
     p(95.0000) =      4.653 ms/op
     p(99.0000) =      5.738 ms/op
     p(99.9000) =      9.552 ms/op
     p(99.9900) =     20.442 ms/op
     p(99.9990) =     21.836 ms/op
     p(99.9999) =     21.856 ms/op
    p(100.0000) =     21.856 ms/op


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
# Warmup Iteration   1: 7.264 ±(99.9%) 0.078 ms/op
# Warmup Iteration   2: 4.859 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.623 ±(99.9%) 0.015 ms/op
Iteration   1: 4.659 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.288 ms/op
                 listUser·p0.50:   4.448 ms/op
                 listUser·p0.90:   5.931 ms/op
                 listUser·p0.95:   6.644 ms/op
                 listUser·p0.99:   8.225 ms/op
                 listUser·p0.999:  15.224 ms/op
                 listUser·p0.9999: 18.473 ms/op
                 listUser·p1.00:   18.907 ms/op

Iteration   2: 4.624 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.190 ms/op
                 listUser·p0.50:   4.424 ms/op
                 listUser·p0.90:   5.816 ms/op
                 listUser·p0.95:   6.734 ms/op
                 listUser·p0.99:   8.094 ms/op
                 listUser·p0.999:  16.653 ms/op
                 listUser·p0.9999: 19.931 ms/op
                 listUser·p1.00:   20.251 ms/op

Iteration   3: 4.551 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.866 ms/op
                 listUser·p0.50:   4.391 ms/op
                 listUser·p0.90:   5.505 ms/op
                 listUser·p0.95:   6.406 ms/op
                 listUser·p0.99:   8.118 ms/op
                 listUser·p0.999:  17.206 ms/op
                 listUser·p0.9999: 22.112 ms/op
                 listUser·p1.00:   22.512 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 208223
  mean =      4.611 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 583 
    [ 2.500,  5.000) = 167027 
    [ 5.000,  7.500) = 36359 
    [ 7.500, 10.000) = 3643 
    [10.000, 12.500) = 248 
    [12.500, 15.000) = 78 
    [15.000, 17.500) = 136 
    [17.500, 20.000) = 121 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.866 ms/op
     p(50.0000) =      4.424 ms/op
     p(90.0000) =      5.759 ms/op
     p(95.0000) =      6.611 ms/op
     p(99.0000) =      8.143 ms/op
     p(99.9000) =     16.335 ms/op
     p(99.9900) =     20.550 ms/op
     p(99.9990) =     22.452 ms/op
     p(99.9999) =     22.512 ms/op
    p(100.0000) =     22.512 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.901 ± 3.922  ops/ms
ClientGrpc.existUser                       thrpt       3   9.307 ± 0.352  ops/ms
ClientGrpc.getUser                         thrpt       3   8.779 ± 3.046  ops/ms
ClientGrpc.listUser                        thrpt       3   6.895 ± 1.900  ops/ms
ClientGrpc.createUser                       avgt       3   3.615 ± 0.857   ms/op
ClientGrpc.existUser                        avgt       3   3.440 ± 0.217   ms/op
ClientGrpc.getUser                          avgt       3   3.532 ± 1.075   ms/op
ClientGrpc.listUser                         avgt       3   4.641 ± 1.011   ms/op
ClientGrpc.createUser                     sample  266870   3.598 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.946           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.559           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.260           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.555           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.734           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.206           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.907           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          20.251           ms/op
ClientGrpc.existUser                      sample  276618   3.468 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.697           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.432           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.071           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.375           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.546           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.551           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          23.309           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          25.133           ms/op
ClientGrpc.getUser                        sample  261660   3.671 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.863           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.625           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.358           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.653           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.738           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.552           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.442           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.856           ms/op
ClientGrpc.listUser                       sample  208223   4.611 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.866           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.424           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.759           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.611           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.143           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.335           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          20.550           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          22.512           ms/op
