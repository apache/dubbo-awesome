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
# Warmup Iteration   1: 4.488 ops/ms
# Warmup Iteration   2: 8.874 ops/ms
# Warmup Iteration   3: 9.911 ops/ms
Iteration   1: 10.451 ops/ms
Iteration   2: 10.620 ops/ms
Iteration   3: 10.527 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.533 ±(99.9%) 1.542 ops/ms [Average]
  (min, avg, max) = (10.451, 10.533, 10.620), stdev = 0.085
  CI (99.9%): [8.990, 12.075] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.981 ops/ms
# Warmup Iteration   2: 10.522 ops/ms
# Warmup Iteration   3: 11.125 ops/ms
Iteration   1: 11.162 ops/ms
Iteration   2: 11.061 ops/ms
Iteration   3: 11.356 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.193 ±(99.9%) 2.735 ops/ms [Average]
  (min, avg, max) = (11.061, 11.193, 11.356), stdev = 0.150
  CI (99.9%): [8.458, 13.928] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.392 ops/ms
# Warmup Iteration   2: 10.363 ops/ms
# Warmup Iteration   3: 10.624 ops/ms
Iteration   1: 10.704 ops/ms
Iteration   2: 10.777 ops/ms
Iteration   3: 10.765 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.749 ±(99.9%) 0.708 ops/ms [Average]
  (min, avg, max) = (10.704, 10.749, 10.777), stdev = 0.039
  CI (99.9%): [10.041, 11.456] (assumes normal distribution)


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
# Warmup Iteration   1: 6.088 ops/ms
# Warmup Iteration   2: 7.925 ops/ms
# Warmup Iteration   3: 8.222 ops/ms
Iteration   1: 8.135 ops/ms
Iteration   2: 8.256 ops/ms
Iteration   3: 8.069 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.153 ±(99.9%) 1.732 ops/ms [Average]
  (min, avg, max) = (8.069, 8.153, 8.256), stdev = 0.095
  CI (99.9%): [6.421, 9.885] (assumes normal distribution)


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
# Warmup Iteration   1: 4.189 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.034 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 2.980 ±(99.9%) 0.020 ms/op
Iteration   1: 2.972 ±(99.9%) 0.002 ms/op
Iteration   2: 3.001 ±(99.9%) 0.002 ms/op
Iteration   3: 2.975 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.982 ±(99.9%) 0.295 ms/op [Average]
  (min, avg, max) = (2.972, 2.982, 3.001), stdev = 0.016
  CI (99.9%): [2.687, 3.277] (assumes normal distribution)


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
# Warmup Iteration   1: 3.897 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.012 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.924 ±(99.9%) 0.003 ms/op
Iteration   1: 2.788 ±(99.9%) 0.003 ms/op
Iteration   2: 2.923 ±(99.9%) 0.003 ms/op
Iteration   3: 2.849 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.853 ±(99.9%) 1.228 ms/op [Average]
  (min, avg, max) = (2.788, 2.853, 2.923), stdev = 0.067
  CI (99.9%): [1.625, 4.081] (assumes normal distribution)


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
# Warmup Iteration   1: 3.956 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.072 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.030 ±(99.9%) 0.003 ms/op
Iteration   1: 3.002 ±(99.9%) 0.003 ms/op
Iteration   2: 2.948 ±(99.9%) 0.004 ms/op
Iteration   3: 2.872 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.941 ±(99.9%) 1.197 ms/op [Average]
  (min, avg, max) = (2.872, 2.941, 3.002), stdev = 0.066
  CI (99.9%): [1.744, 4.138] (assumes normal distribution)


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
# Warmup Iteration   1: 4.833 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 4.054 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 3.896 ±(99.9%) 0.012 ms/op
Iteration   1: 3.908 ±(99.9%) 0.035 ms/op
Iteration   2: 3.848 ±(99.9%) 0.009 ms/op
Iteration   3: 3.844 ±(99.9%) 0.031 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.867 ±(99.9%) 0.651 ms/op [Average]
  (min, avg, max) = (3.844, 3.867, 3.908), stdev = 0.036
  CI (99.9%): [3.216, 4.517] (assumes normal distribution)


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
# Warmup Iteration   1: 3.840 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.148 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.045 ±(99.9%) 0.007 ms/op
Iteration   1: 2.991 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.671 ms/op
                 createUser·p0.50:   2.974 ms/op
                 createUser·p0.90:   3.592 ms/op
                 createUser·p0.95:   3.883 ms/op
                 createUser·p0.99:   4.579 ms/op
                 createUser·p0.999:  8.258 ms/op
                 createUser·p0.9999: 18.907 ms/op
                 createUser·p1.00:   19.202 ms/op

Iteration   2: 2.980 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.623 ms/op
                 createUser·p0.50:   2.982 ms/op
                 createUser·p0.90:   3.453 ms/op
                 createUser·p0.95:   3.686 ms/op
                 createUser·p0.99:   4.350 ms/op
                 createUser·p0.999:  8.010 ms/op
                 createUser·p0.9999: 15.958 ms/op
                 createUser·p1.00:   16.351 ms/op

Iteration   3: 3.010 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.693 ms/op
                 createUser·p0.50:   2.988 ms/op
                 createUser·p0.90:   3.613 ms/op
                 createUser·p0.95:   3.887 ms/op
                 createUser·p0.99:   4.579 ms/op
                 createUser·p0.999:  12.280 ms/op
                 createUser·p0.9999: 17.598 ms/op
                 createUser·p1.00:   18.907 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 320809
  mean =      2.994 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2337 
    [ 1.250,  2.500) = 31269 
    [ 2.500,  3.750) = 267813 
    [ 3.750,  5.000) = 17714 
    [ 5.000,  6.250) = 749 
    [ 6.250,  7.500) = 423 
    [ 7.500,  8.750) = 193 
    [ 8.750, 10.000) = 35 
    [10.000, 11.250) = 20 
    [11.250, 12.500) = 67 
    [12.500, 13.750) = 28 
    [13.750, 15.000) = 72 
    [15.000, 16.250) = 23 
    [16.250, 17.500) = 24 
    [17.500, 18.750) = 23 

  Percentiles, ms/op:
      p(0.0000) =      0.623 ms/op
     p(50.0000) =      2.982 ms/op
     p(90.0000) =      3.551 ms/op
     p(95.0000) =      3.830 ms/op
     p(99.0000) =      4.514 ms/op
     p(99.9000) =      8.637 ms/op
     p(99.9900) =     18.446 ms/op
     p(99.9990) =     19.097 ms/op
     p(99.9999) =     19.202 ms/op
    p(100.0000) =     19.202 ms/op


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
# Warmup Iteration   1: 3.573 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 2.974 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.835 ±(99.9%) 0.007 ms/op
Iteration   1: 2.960 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.543 ms/op
                 existUser·p0.50:   2.925 ms/op
                 existUser·p0.90:   3.527 ms/op
                 existUser·p0.95:   3.686 ms/op
                 existUser·p0.99:   4.530 ms/op
                 existUser·p0.999:  7.381 ms/op
                 existUser·p0.9999: 12.304 ms/op
                 existUser·p1.00:   12.468 ms/op

Iteration   2: 2.910 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.418 ms/op
                 existUser·p0.50:   2.879 ms/op
                 existUser·p0.90:   3.367 ms/op
                 existUser·p0.95:   3.555 ms/op
                 existUser·p0.99:   4.596 ms/op
                 existUser·p0.999:  7.512 ms/op
                 existUser·p0.9999: 15.597 ms/op
                 existUser·p1.00:   15.958 ms/op

Iteration   3: 2.869 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.502 ms/op
                 existUser·p0.50:   2.871 ms/op
                 existUser·p0.90:   3.248 ms/op
                 existUser·p0.95:   3.482 ms/op
                 existUser·p0.99:   4.563 ms/op
                 existUser·p0.999:  7.810 ms/op
                 existUser·p0.9999: 17.859 ms/op
                 existUser·p1.00:   18.645 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 329781
  mean =      2.913 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2139 
    [ 1.250,  2.500) = 37051 
    [ 2.500,  3.750) = 279243 
    [ 3.750,  5.000) = 9471 
    [ 5.000,  6.250) = 1132 
    [ 6.250,  7.500) = 410 
    [ 7.500,  8.750) = 107 
    [ 8.750, 10.000) = 14 
    [10.000, 11.250) = 26 
    [11.250, 12.500) = 60 
    [12.500, 13.750) = 10 
    [13.750, 15.000) = 64 
    [15.000, 16.250) = 22 
    [16.250, 17.500) = 4 
    [17.500, 18.750) = 28 

  Percentiles, ms/op:
      p(0.0000) =      0.418 ms/op
     p(50.0000) =      2.888 ms/op
     p(90.0000) =      3.396 ms/op
     p(95.0000) =      3.617 ms/op
     p(99.0000) =      4.555 ms/op
     p(99.9000) =      7.512 ms/op
     p(99.9900) =     15.987 ms/op
     p(99.9990) =     18.593 ms/op
     p(99.9999) =     18.645 ms/op
    p(100.0000) =     18.645 ms/op


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
# Warmup Iteration   1: 4.039 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.129 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.056 ±(99.9%) 0.006 ms/op
Iteration   1: 3.023 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.609 ms/op
                 getUser·p0.50:   3.002 ms/op
                 getUser·p0.90:   3.510 ms/op
                 getUser·p0.95:   3.748 ms/op
                 getUser·p0.99:   4.440 ms/op
                 getUser·p0.999:  10.743 ms/op
                 getUser·p0.9999: 15.661 ms/op
                 getUser·p1.00:   16.646 ms/op

Iteration   2: 2.996 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.465 ms/op
                 getUser·p0.50:   3.011 ms/op
                 getUser·p0.90:   3.572 ms/op
                 getUser·p0.95:   3.764 ms/op
                 getUser·p0.99:   4.448 ms/op
                 getUser·p0.999:  7.906 ms/op
                 getUser·p0.9999: 17.967 ms/op
                 getUser·p1.00:   18.285 ms/op

Iteration   3: 3.026 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.584 ms/op
                 getUser·p0.50:   2.998 ms/op
                 getUser·p0.90:   3.551 ms/op
                 getUser·p0.95:   3.756 ms/op
                 getUser·p0.99:   4.325 ms/op
                 getUser·p0.999:  7.966 ms/op
                 getUser·p0.9999: 26.916 ms/op
                 getUser·p1.00:   27.296 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 318438
  mean =      3.015 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26803 
    [ 2.500,  5.000) = 289830 
    [ 5.000,  7.500) = 1290 
    [ 7.500, 10.000) = 260 
    [10.000, 12.500) = 48 
    [12.500, 15.000) = 65 
    [15.000, 17.500) = 80 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.465 ms/op
     p(50.0000) =      3.002 ms/op
     p(90.0000) =      3.547 ms/op
     p(95.0000) =      3.756 ms/op
     p(99.0000) =      4.407 ms/op
     p(99.9000) =      8.151 ms/op
     p(99.9900) =     26.316 ms/op
     p(99.9990) =     27.159 ms/op
     p(99.9999) =     27.296 ms/op
    p(100.0000) =     27.296 ms/op


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
# Warmup Iteration   1: 4.394 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 4.015 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.892 ±(99.9%) 0.010 ms/op
Iteration   1: 3.958 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.737 ms/op
                 listUser·p0.50:   3.772 ms/op
                 listUser·p0.90:   5.063 ms/op
                 listUser·p0.95:   5.636 ms/op
                 listUser·p0.99:   6.783 ms/op
                 listUser·p0.999:  13.338 ms/op
                 listUser·p0.9999: 17.531 ms/op
                 listUser·p1.00:   18.940 ms/op

Iteration   2: 3.910 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.857 ms/op
                 listUser·p0.50:   3.760 ms/op
                 listUser·p0.90:   5.022 ms/op
                 listUser·p0.95:   5.808 ms/op
                 listUser·p0.99:   6.955 ms/op
                 listUser·p0.999:  14.470 ms/op
                 listUser·p0.9999: 17.525 ms/op
                 listUser·p1.00:   17.990 ms/op

Iteration   3: 3.897 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.981 ms/op
                 listUser·p0.50:   3.740 ms/op
                 listUser·p0.90:   5.112 ms/op
                 listUser·p0.95:   5.816 ms/op
                 listUser·p0.99:   7.225 ms/op
                 listUser·p0.999:  15.547 ms/op
                 listUser·p0.9999: 23.684 ms/op
                 listUser·p1.00:   23.790 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 244848
  mean =      3.921 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6364 
    [ 2.500,  5.000) = 212215 
    [ 5.000,  7.500) = 24736 
    [ 7.500, 10.000) = 1018 
    [10.000, 12.500) = 121 
    [12.500, 15.000) = 195 
    [15.000, 17.500) = 146 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.737 ms/op
     p(50.0000) =      3.760 ms/op
     p(90.0000) =      5.063 ms/op
     p(95.0000) =      5.759 ms/op
     p(99.0000) =      6.988 ms/op
     p(99.9000) =     14.238 ms/op
     p(99.9900) =     22.905 ms/op
     p(99.9990) =     23.742 ms/op
     p(99.9999) =     23.790 ms/op
    p(100.0000) =     23.790 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.533 ± 1.542  ops/ms
ClientGrpc.existUser                       thrpt       3  11.193 ± 2.735  ops/ms
ClientGrpc.getUser                         thrpt       3  10.749 ± 0.708  ops/ms
ClientGrpc.listUser                        thrpt       3   8.153 ± 1.732  ops/ms
ClientGrpc.createUser                       avgt       3   2.982 ± 0.295   ms/op
ClientGrpc.existUser                        avgt       3   2.853 ± 1.228   ms/op
ClientGrpc.getUser                          avgt       3   2.941 ± 1.197   ms/op
ClientGrpc.listUser                         avgt       3   3.867 ± 0.651   ms/op
ClientGrpc.createUser                     sample  320809   2.994 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.623           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.982           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.551           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.830           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.514           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.637           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.446           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          19.202           ms/op
ClientGrpc.existUser                      sample  329781   2.913 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.418           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.888           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.396           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.617           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.555           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.512           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.987           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.645           ms/op
ClientGrpc.getUser                        sample  318438   3.015 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.465           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.002           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.547           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.756           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.407           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.151           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          26.316           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          27.296           ms/op
ClientGrpc.listUser                       sample  244848   3.921 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.737           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.760           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.063           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.759           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.988           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.238           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.905           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.790           ms/op
