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
# Warmup Iteration   1: 4.674 ops/ms
# Warmup Iteration   2: 9.543 ops/ms
# Warmup Iteration   3: 10.425 ops/ms
Iteration   1: 10.704 ops/ms
Iteration   2: 10.823 ops/ms
Iteration   3: 10.619 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.716 ±(99.9%) 1.867 ops/ms [Average]
  (min, avg, max) = (10.619, 10.716, 10.823), stdev = 0.102
  CI (99.9%): [8.848, 12.583] (assumes normal distribution)


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
# Warmup Iteration   1: 8.315 ops/ms
# Warmup Iteration   2: 10.837 ops/ms
# Warmup Iteration   3: 11.599 ops/ms
Iteration   1: 11.172 ops/ms
Iteration   2: 11.306 ops/ms
Iteration   3: 11.283 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.254 ±(99.9%) 1.306 ops/ms [Average]
  (min, avg, max) = (11.172, 11.254, 11.306), stdev = 0.072
  CI (99.9%): [9.948, 12.560] (assumes normal distribution)


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
# Warmup Iteration   1: 7.623 ops/ms
# Warmup Iteration   2: 10.396 ops/ms
# Warmup Iteration   3: 10.615 ops/ms
Iteration   1: 10.769 ops/ms
Iteration   2: 10.527 ops/ms
Iteration   3: 10.663 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.653 ±(99.9%) 2.219 ops/ms [Average]
  (min, avg, max) = (10.527, 10.653, 10.769), stdev = 0.122
  CI (99.9%): [8.434, 12.872] (assumes normal distribution)


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
# Warmup Iteration   1: 5.966 ops/ms
# Warmup Iteration   2: 8.205 ops/ms
# Warmup Iteration   3: 8.169 ops/ms
Iteration   1: 8.339 ops/ms
Iteration   2: 8.285 ops/ms
Iteration   3: 8.306 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.310 ±(99.9%) 0.493 ops/ms [Average]
  (min, avg, max) = (8.285, 8.310, 8.339), stdev = 0.027
  CI (99.9%): [7.816, 8.803] (assumes normal distribution)


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
# Warmup Iteration   1: 3.881 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.110 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.001 ±(99.9%) 0.003 ms/op
Iteration   1: 3.015 ±(99.9%) 0.001 ms/op
Iteration   2: 3.012 ±(99.9%) 0.002 ms/op
Iteration   3: 2.955 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.994 ±(99.9%) 0.620 ms/op [Average]
  (min, avg, max) = (2.955, 2.994, 3.015), stdev = 0.034
  CI (99.9%): [2.374, 3.614] (assumes normal distribution)


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
# Warmup Iteration   1: 3.569 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.886 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.918 ±(99.9%) 0.003 ms/op
Iteration   1: 2.912 ±(99.9%) 0.003 ms/op
Iteration   2: 2.894 ±(99.9%) 0.002 ms/op
Iteration   3: 2.789 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.865 ±(99.9%) 1.209 ms/op [Average]
  (min, avg, max) = (2.789, 2.865, 2.912), stdev = 0.066
  CI (99.9%): [1.656, 4.074] (assumes normal distribution)


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
# Warmup Iteration   1: 4.021 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.044 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.978 ±(99.9%) 0.003 ms/op
Iteration   1: 2.976 ±(99.9%) 0.003 ms/op
Iteration   2: 2.936 ±(99.9%) 0.009 ms/op
Iteration   3: 2.958 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.957 ±(99.9%) 0.371 ms/op [Average]
  (min, avg, max) = (2.936, 2.957, 2.976), stdev = 0.020
  CI (99.9%): [2.586, 3.327] (assumes normal distribution)


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
# Warmup Iteration   1: 5.185 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.946 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.986 ±(99.9%) 0.014 ms/op
Iteration   1: 3.879 ±(99.9%) 0.010 ms/op
Iteration   2: 3.853 ±(99.9%) 0.019 ms/op
Iteration   3: 3.822 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.851 ±(99.9%) 0.522 ms/op [Average]
  (min, avg, max) = (3.822, 3.851, 3.879), stdev = 0.029
  CI (99.9%): [3.329, 4.374] (assumes normal distribution)


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
# Warmup Iteration   1: 4.137 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.140 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.005 ±(99.9%) 0.006 ms/op
Iteration   1: 3.021 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.659 ms/op
                 createUser·p0.50:   2.994 ms/op
                 createUser·p0.90:   3.580 ms/op
                 createUser·p0.95:   3.830 ms/op
                 createUser·p0.99:   4.448 ms/op
                 createUser·p0.999:  10.429 ms/op
                 createUser·p0.9999: 14.802 ms/op
                 createUser·p1.00:   16.417 ms/op

Iteration   2: 3.008 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.616 ms/op
                 createUser·p0.50:   3.002 ms/op
                 createUser·p0.90:   3.510 ms/op
                 createUser·p0.95:   3.670 ms/op
                 createUser·p0.99:   4.284 ms/op
                 createUser·p0.999:  6.648 ms/op
                 createUser·p0.9999: 16.318 ms/op
                 createUser·p1.00:   16.548 ms/op

Iteration   3: 3.018 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.612 ms/op
                 createUser·p0.50:   2.998 ms/op
                 createUser·p0.90:   3.473 ms/op
                 createUser·p0.95:   3.674 ms/op
                 createUser·p0.99:   4.284 ms/op
                 createUser·p0.999:  14.559 ms/op
                 createUser·p0.9999: 21.978 ms/op
                 createUser·p1.00:   22.184 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 318750
  mean =      3.016 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24391 
    [ 2.500,  5.000) = 292933 
    [ 5.000,  7.500) = 994 
    [ 7.500, 10.000) = 56 
    [10.000, 12.500) = 88 
    [12.500, 15.000) = 131 
    [15.000, 17.500) = 100 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.612 ms/op
     p(50.0000) =      2.998 ms/op
     p(90.0000) =      3.514 ms/op
     p(95.0000) =      3.731 ms/op
     p(99.0000) =      4.342 ms/op
     p(99.9000) =     11.121 ms/op
     p(99.9900) =     19.669 ms/op
     p(99.9990) =     22.184 ms/op
     p(99.9999) =     22.184 ms/op
    p(100.0000) =     22.184 ms/op


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
# Warmup Iteration   1: 3.876 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 2.976 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.821 ±(99.9%) 0.007 ms/op
Iteration   1: 2.834 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.658 ms/op
                 existUser·p0.50:   2.851 ms/op
                 existUser·p0.90:   3.301 ms/op
                 existUser·p0.95:   3.531 ms/op
                 existUser·p0.99:   4.022 ms/op
                 existUser·p0.999:  6.210 ms/op
                 existUser·p0.9999: 11.464 ms/op
                 existUser·p1.00:   11.616 ms/op

Iteration   2: 2.745 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.436 ms/op
                 existUser·p0.50:   2.822 ms/op
                 existUser·p0.90:   3.269 ms/op
                 existUser·p0.95:   3.502 ms/op
                 existUser·p0.99:   4.194 ms/op
                 existUser·p0.999:  6.780 ms/op
                 existUser·p0.9999: 17.215 ms/op
                 existUser·p1.00:   17.695 ms/op

Iteration   3: 2.840 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.605 ms/op
                 existUser·p0.50:   2.871 ms/op
                 existUser·p0.90:   3.199 ms/op
                 existUser·p0.95:   3.383 ms/op
                 existUser·p0.99:   3.883 ms/op
                 existUser·p0.999:  5.808 ms/op
                 existUser·p0.9999: 14.921 ms/op
                 existUser·p1.00:   15.237 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 342114
  mean =      2.806 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 7534 
    [ 1.250,  2.500) = 42535 
    [ 2.500,  3.750) = 284649 
    [ 3.750,  5.000) = 6692 
    [ 5.000,  6.250) = 368 
    [ 6.250,  7.500) = 123 
    [ 7.500,  8.750) = 46 
    [ 8.750, 10.000) = 7 
    [10.000, 11.250) = 70 
    [11.250, 12.500) = 26 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 24 
    [15.000, 16.250) = 8 
    [16.250, 17.500) = 29 
    [17.500, 18.750) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.436 ms/op
     p(50.0000) =      2.851 ms/op
     p(90.0000) =      3.256 ms/op
     p(95.0000) =      3.473 ms/op
     p(99.0000) =      4.063 ms/op
     p(99.9000) =      6.226 ms/op
     p(99.9900) =     15.185 ms/op
     p(99.9990) =     17.536 ms/op
     p(99.9999) =     17.695 ms/op
    p(100.0000) =     17.695 ms/op


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
# Warmup Iteration   1: 4.032 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.112 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.039 ±(99.9%) 0.006 ms/op
Iteration   1: 2.981 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.710 ms/op
                 getUser·p0.50:   2.974 ms/op
                 getUser·p0.90:   3.437 ms/op
                 getUser·p0.95:   3.715 ms/op
                 getUser·p0.99:   4.391 ms/op
                 getUser·p0.999:  7.844 ms/op
                 getUser·p0.9999: 20.686 ms/op
                 getUser·p1.00:   21.135 ms/op

Iteration   2: 3.021 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.650 ms/op
                 getUser·p0.50:   3.019 ms/op
                 getUser·p0.90:   3.514 ms/op
                 getUser·p0.95:   3.699 ms/op
                 getUser·p0.99:   4.243 ms/op
                 getUser·p0.999:  6.856 ms/op
                 getUser·p0.9999: 12.924 ms/op
                 getUser·p1.00:   13.189 ms/op

Iteration   3: 3.021 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.697 ms/op
                 getUser·p0.50:   3.015 ms/op
                 getUser·p0.90:   3.600 ms/op
                 getUser·p0.95:   3.772 ms/op
                 getUser·p0.99:   4.407 ms/op
                 getUser·p0.999:  6.767 ms/op
                 getUser·p0.9999: 14.831 ms/op
                 getUser·p1.00:   15.172 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 319139
  mean =      3.007 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23411 
    [ 2.500,  5.000) = 294380 
    [ 5.000,  7.500) = 1084 
    [ 7.500, 10.000) = 104 
    [10.000, 12.500) = 55 
    [12.500, 15.000) = 68 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.650 ms/op
     p(50.0000) =      2.998 ms/op
     p(90.0000) =      3.527 ms/op
     p(95.0000) =      3.740 ms/op
     p(99.0000) =      4.334 ms/op
     p(99.9000) =      7.209 ms/op
     p(99.9900) =     19.735 ms/op
     p(99.9990) =     21.045 ms/op
     p(99.9999) =     21.135 ms/op
    p(100.0000) =     21.135 ms/op


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
# Warmup Iteration   1: 4.843 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 4.118 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.936 ±(99.9%) 0.011 ms/op
Iteration   1: 3.913 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.155 ms/op
                 listUser·p0.50:   3.777 ms/op
                 listUser·p0.90:   4.981 ms/op
                 listUser·p0.95:   5.620 ms/op
                 listUser·p0.99:   7.070 ms/op
                 listUser·p0.999:  14.800 ms/op
                 listUser·p0.9999: 17.984 ms/op
                 listUser·p1.00:   19.956 ms/op

Iteration   2: 3.939 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.796 ms/op
                 listUser·p0.50:   3.797 ms/op
                 listUser·p0.90:   4.981 ms/op
                 listUser·p0.95:   5.636 ms/op
                 listUser·p0.99:   6.652 ms/op
                 listUser·p0.999:  15.179 ms/op
                 listUser·p0.9999: 25.577 ms/op
                 listUser·p1.00:   25.919 ms/op

Iteration   3: 3.993 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.540 ms/op
                 listUser·p0.50:   3.834 ms/op
                 listUser·p0.90:   4.907 ms/op
                 listUser·p0.95:   5.652 ms/op
                 listUser·p0.99:   7.201 ms/op
                 listUser·p0.999:  16.935 ms/op
                 listUser·p0.9999: 21.428 ms/op
                 listUser·p1.00:   22.970 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 243522
  mean =      3.948 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6055 
    [ 2.500,  5.000) = 214194 
    [ 5.000,  7.500) = 21717 
    [ 7.500, 10.000) = 974 
    [10.000, 12.500) = 144 
    [12.500, 15.000) = 141 
    [15.000, 17.500) = 173 
    [17.500, 20.000) = 60 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      0.540 ms/op
     p(50.0000) =      3.801 ms/op
     p(90.0000) =      4.964 ms/op
     p(95.0000) =      5.636 ms/op
     p(99.0000) =      6.988 ms/op
     p(99.9000) =     15.499 ms/op
     p(99.9900) =     23.287 ms/op
     p(99.9990) =     25.840 ms/op
     p(99.9999) =     25.919 ms/op
    p(100.0000) =     25.919 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.716 ± 1.867  ops/ms
ClientGrpc.existUser                       thrpt       3  11.254 ± 1.306  ops/ms
ClientGrpc.getUser                         thrpt       3  10.653 ± 2.219  ops/ms
ClientGrpc.listUser                        thrpt       3   8.310 ± 0.493  ops/ms
ClientGrpc.createUser                       avgt       3   2.994 ± 0.620   ms/op
ClientGrpc.existUser                        avgt       3   2.865 ± 1.209   ms/op
ClientGrpc.getUser                          avgt       3   2.957 ± 0.371   ms/op
ClientGrpc.listUser                         avgt       3   3.851 ± 0.522   ms/op
ClientGrpc.createUser                     sample  318750   3.016 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.612           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.998           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.514           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.731           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.342           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.121           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.669           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.184           ms/op
ClientGrpc.existUser                      sample  342114   2.806 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.436           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.851           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.256           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.473           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.063           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.226           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.185           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.695           ms/op
ClientGrpc.getUser                        sample  319139   3.007 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.650           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.998           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.527           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.740           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.334           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.209           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.735           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.135           ms/op
ClientGrpc.listUser                       sample  243522   3.948 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.540           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.801           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.964           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.636           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.988           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.499           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.287           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.919           ms/op
