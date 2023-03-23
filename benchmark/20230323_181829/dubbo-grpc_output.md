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
# Warmup Iteration   1: 4.273 ops/ms
# Warmup Iteration   2: 9.392 ops/ms
# Warmup Iteration   3: 10.265 ops/ms
Iteration   1: 10.664 ops/ms
Iteration   2: 10.873 ops/ms
Iteration   3: 10.458 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.665 ±(99.9%) 3.792 ops/ms [Average]
  (min, avg, max) = (10.458, 10.665, 10.873), stdev = 0.208
  CI (99.9%): [6.873, 14.457] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.463 ops/ms
# Warmup Iteration   2: 10.824 ops/ms
# Warmup Iteration   3: 11.185 ops/ms
Iteration   1: 11.347 ops/ms
Iteration   2: 11.130 ops/ms
Iteration   3: 11.301 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.259 ±(99.9%) 2.079 ops/ms [Average]
  (min, avg, max) = (11.130, 11.259, 11.347), stdev = 0.114
  CI (99.9%): [9.180, 13.339] (assumes normal distribution)


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
# Warmup Iteration   1: 7.108 ops/ms
# Warmup Iteration   2: 10.505 ops/ms
# Warmup Iteration   3: 10.559 ops/ms
Iteration   1: 10.572 ops/ms
Iteration   2: 10.671 ops/ms
Iteration   3: 10.784 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.675 ±(99.9%) 1.929 ops/ms [Average]
  (min, avg, max) = (10.572, 10.675, 10.784), stdev = 0.106
  CI (99.9%): [8.746, 12.605] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.321 ops/ms
# Warmup Iteration   2: 7.889 ops/ms
# Warmup Iteration   3: 7.975 ops/ms
Iteration   1: 8.193 ops/ms
Iteration   2: 8.005 ops/ms
Iteration   3: 8.130 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.109 ±(99.9%) 1.747 ops/ms [Average]
  (min, avg, max) = (8.005, 8.109, 8.193), stdev = 0.096
  CI (99.9%): [6.362, 9.856] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.016 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.147 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.084 ±(99.9%) 0.003 ms/op
Iteration   1: 3.021 ±(99.9%) 0.003 ms/op
Iteration   2: 3.005 ±(99.9%) 0.003 ms/op
Iteration   3: 3.025 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.017 ±(99.9%) 0.192 ms/op [Average]
  (min, avg, max) = (3.005, 3.017, 3.025), stdev = 0.011
  CI (99.9%): [2.825, 3.209] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.907 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.027 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.967 ±(99.9%) 0.004 ms/op
Iteration   1: 2.863 ±(99.9%) 0.003 ms/op
Iteration   2: 2.854 ±(99.9%) 0.003 ms/op
Iteration   3: 2.863 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.860 ±(99.9%) 0.098 ms/op [Average]
  (min, avg, max) = (2.854, 2.860, 2.863), stdev = 0.005
  CI (99.9%): [2.762, 2.958] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 3.896 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.064 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.973 ±(99.9%) 0.003 ms/op
Iteration   1: 2.989 ±(99.9%) 0.003 ms/op
Iteration   2: 2.977 ±(99.9%) 0.004 ms/op
Iteration   3: 3.022 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.996 ±(99.9%) 0.427 ms/op [Average]
  (min, avg, max) = (2.977, 2.996, 3.022), stdev = 0.023
  CI (99.9%): [2.569, 3.423] (assumes normal distribution)


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
# Warmup Iteration   1: 5.184 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 4.066 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 3.912 ±(99.9%) 0.014 ms/op
Iteration   1: 3.925 ±(99.9%) 0.012 ms/op
Iteration   2: 3.887 ±(99.9%) 0.024 ms/op
Iteration   3: 3.845 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.886 ±(99.9%) 0.734 ms/op [Average]
  (min, avg, max) = (3.845, 3.886, 3.925), stdev = 0.040
  CI (99.9%): [3.152, 4.619] (assumes normal distribution)


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
# Warmup Iteration   1: 4.073 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.170 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.034 ±(99.9%) 0.007 ms/op
Iteration   1: 3.000 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.710 ms/op
                 createUser·p0.50:   2.990 ms/op
                 createUser·p0.90:   3.465 ms/op
                 createUser·p0.95:   3.637 ms/op
                 createUser·p0.99:   4.350 ms/op
                 createUser·p0.999:  10.496 ms/op
                 createUser·p0.9999: 21.725 ms/op
                 createUser·p1.00:   22.053 ms/op

Iteration   2: 3.011 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.631 ms/op
                 createUser·p0.50:   2.998 ms/op
                 createUser·p0.90:   3.383 ms/op
                 createUser·p0.95:   3.551 ms/op
                 createUser·p0.99:   4.133 ms/op
                 createUser·p0.999:  11.122 ms/op
                 createUser·p0.9999: 13.562 ms/op
                 createUser·p1.00:   13.861 ms/op

Iteration   3: 3.007 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.764 ms/op
                 createUser·p0.50:   2.986 ms/op
                 createUser·p0.90:   3.482 ms/op
                 createUser·p0.95:   3.744 ms/op
                 createUser·p0.99:   4.301 ms/op
                 createUser·p0.999:  7.456 ms/op
                 createUser·p0.9999: 18.186 ms/op
                 createUser·p1.00:   19.595 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 319387
  mean =      3.006 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19762 
    [ 2.500,  5.000) = 298489 
    [ 5.000,  7.500) = 711 
    [ 7.500, 10.000) = 80 
    [10.000, 12.500) = 130 
    [12.500, 15.000) = 92 
    [15.000, 17.500) = 59 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.631 ms/op
     p(50.0000) =      2.990 ms/op
     p(90.0000) =      3.441 ms/op
     p(95.0000) =      3.645 ms/op
     p(99.0000) =      4.268 ms/op
     p(99.9000) =     10.752 ms/op
     p(99.9900) =     20.420 ms/op
     p(99.9990) =     22.020 ms/op
     p(99.9999) =     22.053 ms/op
    p(100.0000) =     22.053 ms/op


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
# Warmup Iteration   1: 3.739 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 2.987 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.896 ±(99.9%) 0.006 ms/op
Iteration   1: 2.804 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.544 ms/op
                 existUser·p0.50:   2.867 ms/op
                 existUser·p0.90:   3.396 ms/op
                 existUser·p0.95:   3.543 ms/op
                 existUser·p0.99:   4.358 ms/op
                 existUser·p0.999:  5.865 ms/op
                 existUser·p0.9999: 14.886 ms/op
                 existUser·p1.00:   16.253 ms/op

Iteration   2: 2.880 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.615 ms/op
                 existUser·p0.50:   2.879 ms/op
                 existUser·p0.90:   3.375 ms/op
                 existUser·p0.95:   3.613 ms/op
                 existUser·p0.99:   4.436 ms/op
                 existUser·p0.999:  6.232 ms/op
                 existUser·p0.9999: 13.186 ms/op
                 existUser·p1.00:   13.304 ms/op

Iteration   3: 2.848 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.714 ms/op
                 existUser·p0.50:   2.847 ms/op
                 existUser·p0.90:   3.330 ms/op
                 existUser·p0.95:   3.654 ms/op
                 existUser·p0.99:   4.555 ms/op
                 existUser·p0.999:  7.063 ms/op
                 existUser·p0.9999: 14.283 ms/op
                 existUser·p1.00:   14.418 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 337537
  mean =      2.843 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 6794 
    [ 1.250,  2.500) = 48301 
    [ 2.500,  3.750) = 271022 
    [ 3.750,  5.000) = 10350 
    [ 5.000,  6.250) = 706 
    [ 6.250,  7.500) = 104 
    [ 7.500,  8.750) = 36 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 33 
    [11.250, 12.500) = 61 
    [12.500, 13.750) = 68 
    [13.750, 15.000) = 51 
    [15.000, 16.250) = 8 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.544 ms/op
     p(50.0000) =      2.863 ms/op
     p(90.0000) =      3.371 ms/op
     p(95.0000) =      3.588 ms/op
     p(99.0000) =      4.481 ms/op
     p(99.9000) =      6.369 ms/op
     p(99.9900) =     14.254 ms/op
     p(99.9990) =     15.331 ms/op
     p(99.9999) =     16.253 ms/op
    p(100.0000) =     16.253 ms/op


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
# Warmup Iteration   1: 3.838 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.086 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.017 ±(99.9%) 0.007 ms/op
Iteration   1: 3.010 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.911 ms/op
                 getUser·p0.50:   2.998 ms/op
                 getUser·p0.90:   3.424 ms/op
                 getUser·p0.95:   3.695 ms/op
                 getUser·p0.99:   4.415 ms/op
                 getUser·p0.999:  9.388 ms/op
                 getUser·p0.9999: 12.763 ms/op
                 getUser·p1.00:   14.352 ms/op

Iteration   2: 2.986 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.539 ms/op
                 getUser·p0.50:   2.990 ms/op
                 getUser·p0.90:   3.453 ms/op
                 getUser·p0.95:   3.719 ms/op
                 getUser·p0.99:   4.432 ms/op
                 getUser·p0.999:  6.469 ms/op
                 getUser·p0.9999: 14.631 ms/op
                 getUser·p1.00:   14.877 ms/op

Iteration   3: 3.014 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.745 ms/op
                 getUser·p0.50:   2.998 ms/op
                 getUser·p0.90:   3.592 ms/op
                 getUser·p0.95:   3.805 ms/op
                 getUser·p0.99:   4.530 ms/op
                 getUser·p0.999:  7.995 ms/op
                 getUser·p0.9999: 27.525 ms/op
                 getUser·p1.00:   27.689 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 319433
  mean =      3.003 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26228 
    [ 2.500,  5.000) = 291532 
    [ 5.000,  7.500) = 1280 
    [ 7.500, 10.000) = 149 
    [10.000, 12.500) = 69 
    [12.500, 15.000) = 111 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 21 

  Percentiles, ms/op:
      p(0.0000) =      0.539 ms/op
     p(50.0000) =      2.994 ms/op
     p(90.0000) =      3.502 ms/op
     p(95.0000) =      3.744 ms/op
     p(99.0000) =      4.456 ms/op
     p(99.9000) =      8.599 ms/op
     p(99.9900) =     27.232 ms/op
     p(99.9990) =     27.617 ms/op
     p(99.9999) =     27.689 ms/op
    p(100.0000) =     27.689 ms/op


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
# Warmup Iteration   1: 5.303 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 4.028 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.902 ±(99.9%) 0.010 ms/op
Iteration   1: 3.862 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.714 ms/op
                 listUser·p0.50:   3.719 ms/op
                 listUser·p0.90:   4.948 ms/op
                 listUser·p0.95:   5.546 ms/op
                 listUser·p0.99:   6.758 ms/op
                 listUser·p0.999:  12.488 ms/op
                 listUser·p0.9999: 15.063 ms/op
                 listUser·p1.00:   16.810 ms/op

Iteration   2: 3.906 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.758 ms/op
                 listUser·p0.50:   3.760 ms/op
                 listUser·p0.90:   4.981 ms/op
                 listUser·p0.95:   5.562 ms/op
                 listUser·p0.99:   6.849 ms/op
                 listUser·p0.999:  14.155 ms/op
                 listUser·p0.9999: 22.865 ms/op
                 listUser·p1.00:   23.233 ms/op

Iteration   3: 3.915 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.744 ms/op
                 listUser·p0.50:   3.797 ms/op
                 listUser·p0.90:   4.784 ms/op
                 listUser·p0.95:   5.374 ms/op
                 listUser·p0.99:   6.603 ms/op
                 listUser·p0.999:  14.975 ms/op
                 listUser·p0.9999: 24.587 ms/op
                 listUser·p1.00:   25.199 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 246650
  mean =      3.894 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5065 
    [ 2.500,  5.000) = 219686 
    [ 5.000,  7.500) = 20877 
    [ 7.500, 10.000) = 594 
    [10.000, 12.500) = 102 
    [12.500, 15.000) = 189 
    [15.000, 17.500) = 66 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 40 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.714 ms/op
     p(50.0000) =      3.760 ms/op
     p(90.0000) =      4.899 ms/op
     p(95.0000) =      5.513 ms/op
     p(99.0000) =      6.726 ms/op
     p(99.9000) =     13.785 ms/op
     p(99.9900) =     23.080 ms/op
     p(99.9990) =     25.102 ms/op
     p(99.9999) =     25.199 ms/op
    p(100.0000) =     25.199 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.665 ± 3.792  ops/ms
ClientGrpc.existUser                       thrpt       3  11.259 ± 2.079  ops/ms
ClientGrpc.getUser                         thrpt       3  10.675 ± 1.929  ops/ms
ClientGrpc.listUser                        thrpt       3   8.109 ± 1.747  ops/ms
ClientGrpc.createUser                       avgt       3   3.017 ± 0.192   ms/op
ClientGrpc.existUser                        avgt       3   2.860 ± 0.098   ms/op
ClientGrpc.getUser                          avgt       3   2.996 ± 0.427   ms/op
ClientGrpc.listUser                         avgt       3   3.886 ± 0.734   ms/op
ClientGrpc.createUser                     sample  319387   3.006 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.631           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.990           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.441           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.645           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.268           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.752           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.420           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.053           ms/op
ClientGrpc.existUser                      sample  337537   2.843 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.544           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.863           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.371           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.588           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.481           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.369           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.254           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          16.253           ms/op
ClientGrpc.getUser                        sample  319433   3.003 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.539           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.994           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.502           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.744           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.456           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.599           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          27.232           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          27.689           ms/op
ClientGrpc.listUser                       sample  246650   3.894 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.714           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.760           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.899           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.513           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.726           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.785           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.080           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.199           ms/op
