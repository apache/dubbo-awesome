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
# Warmup Iteration   1: 3.721 ops/ms
# Warmup Iteration   2: 8.436 ops/ms
# Warmup Iteration   3: 9.856 ops/ms
Iteration   1: 10.066 ops/ms
Iteration   2: 9.823 ops/ms
Iteration   3: 10.226 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.038 ±(99.9%) 3.698 ops/ms [Average]
  (min, avg, max) = (9.823, 10.038, 10.226), stdev = 0.203
  CI (99.9%): [6.340, 13.736] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.434 ops/ms
# Warmup Iteration   2: 10.501 ops/ms
# Warmup Iteration   3: 10.780 ops/ms
Iteration   1: 10.101 ops/ms
Iteration   2: 10.816 ops/ms
Iteration   3: 10.606 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.508 ±(99.9%) 6.706 ops/ms [Average]
  (min, avg, max) = (10.101, 10.508, 10.816), stdev = 0.368
  CI (99.9%): [3.801, 17.214] (assumes normal distribution)


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
# Warmup Iteration   1: 7.943 ops/ms
# Warmup Iteration   2: 9.584 ops/ms
# Warmup Iteration   3: 10.085 ops/ms
Iteration   1: 10.145 ops/ms
Iteration   2: 10.671 ops/ms
Iteration   3: 10.185 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.334 ±(99.9%) 5.336 ops/ms [Average]
  (min, avg, max) = (10.145, 10.334, 10.671), stdev = 0.293
  CI (99.9%): [4.997, 15.670] (assumes normal distribution)


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
# Warmup Iteration   1: 5.465 ops/ms
# Warmup Iteration   2: 6.981 ops/ms
# Warmup Iteration   3: 7.637 ops/ms
Iteration   1: 7.655 ops/ms
Iteration   2: 7.806 ops/ms
Iteration   3: 7.852 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.771 ±(99.9%) 1.883 ops/ms [Average]
  (min, avg, max) = (7.655, 7.771, 7.852), stdev = 0.103
  CI (99.9%): [5.888, 9.653] (assumes normal distribution)


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
# Warmup Iteration   1: 4.295 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 3.154 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.050 ±(99.9%) 0.003 ms/op
Iteration   1: 3.072 ±(99.9%) 0.002 ms/op
Iteration   2: 3.050 ±(99.9%) 0.003 ms/op
Iteration   3: 3.014 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.045 ±(99.9%) 0.526 ms/op [Average]
  (min, avg, max) = (3.014, 3.045, 3.072), stdev = 0.029
  CI (99.9%): [2.519, 3.571] (assumes normal distribution)


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
# Warmup Iteration   1: 4.011 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.132 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.031 ±(99.9%) 0.003 ms/op
Iteration   1: 3.000 ±(99.9%) 0.003 ms/op
Iteration   2: 3.016 ±(99.9%) 0.002 ms/op
Iteration   3: 2.982 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.999 ±(99.9%) 0.311 ms/op [Average]
  (min, avg, max) = (2.982, 2.999, 3.016), stdev = 0.017
  CI (99.9%): [2.689, 3.310] (assumes normal distribution)


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
# Warmup Iteration   1: 4.114 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.200 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.105 ±(99.9%) 0.003 ms/op
Iteration   1: 3.129 ±(99.9%) 0.003 ms/op
Iteration   2: 3.089 ±(99.9%) 0.002 ms/op
Iteration   3: 3.182 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.134 ±(99.9%) 0.847 ms/op [Average]
  (min, avg, max) = (3.089, 3.134, 3.182), stdev = 0.046
  CI (99.9%): [2.286, 3.981] (assumes normal distribution)


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
# Warmup Iteration   1: 5.457 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 4.290 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.947 ±(99.9%) 0.008 ms/op
Iteration   1: 3.995 ±(99.9%) 0.044 ms/op
Iteration   2: 3.947 ±(99.9%) 0.021 ms/op
Iteration   3: 4.013 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.985 ±(99.9%) 0.620 ms/op [Average]
  (min, avg, max) = (3.947, 3.985, 4.013), stdev = 0.034
  CI (99.9%): [3.365, 4.605] (assumes normal distribution)


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
# Warmup Iteration   1: 4.243 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.225 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.058 ±(99.9%) 0.007 ms/op
Iteration   1: 2.993 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.425 ms/op
                 createUser·p0.50:   3.002 ms/op
                 createUser·p0.90:   3.514 ms/op
                 createUser·p0.95:   3.772 ms/op
                 createUser·p0.99:   4.448 ms/op
                 createUser·p0.999:  10.207 ms/op
                 createUser·p0.9999: 15.504 ms/op
                 createUser·p1.00:   17.695 ms/op

Iteration   2: 3.040 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.650 ms/op
                 createUser·p0.50:   2.998 ms/op
                 createUser·p0.90:   3.535 ms/op
                 createUser·p0.95:   3.674 ms/op
                 createUser·p0.99:   4.514 ms/op
                 createUser·p0.999:  12.932 ms/op
                 createUser·p0.9999: 16.703 ms/op
                 createUser·p1.00:   17.039 ms/op

Iteration   3: 2.993 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.550 ms/op
                 createUser·p0.50:   2.978 ms/op
                 createUser·p0.90:   3.514 ms/op
                 createUser·p0.95:   3.830 ms/op
                 createUser·p0.99:   4.514 ms/op
                 createUser·p0.999:  9.175 ms/op
                 createUser·p0.9999: 21.310 ms/op
                 createUser·p1.00:   21.660 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 318937
  mean =      3.008 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27532 
    [ 2.500,  5.000) = 289512 
    [ 5.000,  7.500) = 1225 
    [ 7.500, 10.000) = 274 
    [10.000, 12.500) = 110 
    [12.500, 15.000) = 96 
    [15.000, 17.500) = 133 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.425 ms/op
     p(50.0000) =      2.994 ms/op
     p(90.0000) =      3.523 ms/op
     p(95.0000) =      3.756 ms/op
     p(99.0000) =      4.489 ms/op
     p(99.9000) =     10.947 ms/op
     p(99.9900) =     19.894 ms/op
     p(99.9990) =     21.516 ms/op
     p(99.9999) =     21.660 ms/op
    p(100.0000) =     21.660 ms/op


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
# Warmup Iteration   1: 4.022 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.039 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.948 ±(99.9%) 0.006 ms/op
Iteration   1: 3.023 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.740 ms/op
                 existUser·p0.50:   2.994 ms/op
                 existUser·p0.90:   3.609 ms/op
                 existUser·p0.95:   3.805 ms/op
                 existUser·p0.99:   4.424 ms/op
                 existUser·p0.999:  6.868 ms/op
                 existUser·p0.9999: 15.192 ms/op
                 existUser·p1.00:   16.810 ms/op

Iteration   2: 3.051 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.642 ms/op
                 existUser·p0.50:   3.039 ms/op
                 existUser·p0.90:   3.510 ms/op
                 existUser·p0.95:   3.736 ms/op
                 existUser·p0.99:   4.407 ms/op
                 existUser·p0.999:  7.561 ms/op
                 existUser·p0.9999: 14.696 ms/op
                 existUser·p1.00:   16.777 ms/op

Iteration   3: 2.961 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.810 ms/op
                 existUser·p0.50:   2.970 ms/op
                 existUser·p0.90:   3.486 ms/op
                 existUser·p0.95:   3.674 ms/op
                 existUser·p0.99:   4.399 ms/op
                 existUser·p0.999:  5.853 ms/op
                 existUser·p0.9999: 14.601 ms/op
                 existUser·p1.00:   15.548 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 318812
  mean =      3.011 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1654 
    [ 1.250,  2.500) = 24481 
    [ 2.500,  3.750) = 276683 
    [ 3.750,  5.000) = 14776 
    [ 5.000,  6.250) = 767 
    [ 6.250,  7.500) = 167 
    [ 7.500,  8.750) = 64 
    [ 8.750, 10.000) = 28 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 41 
    [12.500, 13.750) = 56 
    [13.750, 15.000) = 73 
    [15.000, 16.250) = 16 
    [16.250, 17.500) = 6 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.642 ms/op
     p(50.0000) =      2.998 ms/op
     p(90.0000) =      3.531 ms/op
     p(95.0000) =      3.752 ms/op
     p(99.0000) =      4.407 ms/op
     p(99.9000) =      7.201 ms/op
     p(99.9900) =     14.828 ms/op
     p(99.9990) =     16.777 ms/op
     p(99.9999) =     16.810 ms/op
    p(100.0000) =     16.810 ms/op


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
# Warmup Iteration   1: 4.029 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.324 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.243 ±(99.9%) 0.006 ms/op
Iteration   1: 3.239 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.731 ms/op
                 getUser·p0.50:   3.219 ms/op
                 getUser·p0.90:   3.719 ms/op
                 getUser·p0.95:   3.940 ms/op
                 getUser·p0.99:   4.710 ms/op
                 getUser·p0.999:  8.296 ms/op
                 getUser·p0.9999: 13.764 ms/op
                 getUser·p1.00:   14.008 ms/op

Iteration   2: 3.063 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.260 ms/op
                 getUser·p0.50:   3.064 ms/op
                 getUser·p0.90:   3.555 ms/op
                 getUser·p0.95:   3.801 ms/op
                 getUser·p0.99:   4.350 ms/op
                 getUser·p0.999:  7.676 ms/op
                 getUser·p0.9999: 15.615 ms/op
                 getUser·p1.00:   15.892 ms/op

Iteration   3: 3.125 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.572 ms/op
                 getUser·p0.50:   3.109 ms/op
                 getUser·p0.90:   3.662 ms/op
                 getUser·p0.95:   3.920 ms/op
                 getUser·p0.99:   4.694 ms/op
                 getUser·p0.999:  8.191 ms/op
                 getUser·p0.9999: 14.542 ms/op
                 getUser·p1.00:   15.188 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 305751
  mean =      3.140 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1056 
    [ 1.250,  2.500) = 14420 
    [ 2.500,  3.750) = 267365 
    [ 3.750,  5.000) = 21174 
    [ 5.000,  6.250) = 1041 
    [ 6.250,  7.500) = 299 
    [ 7.500,  8.750) = 151 
    [ 8.750, 10.000) = 28 
    [10.000, 11.250) = 25 
    [11.250, 12.500) = 38 
    [12.500, 13.750) = 101 
    [13.750, 15.000) = 18 
    [15.000, 16.250) = 35 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.260 ms/op
     p(50.0000) =      3.125 ms/op
     p(90.0000) =      3.662 ms/op
     p(95.0000) =      3.887 ms/op
     p(99.0000) =      4.637 ms/op
     p(99.9000) =      8.020 ms/op
     p(99.9900) =     15.188 ms/op
     p(99.9990) =     15.775 ms/op
     p(99.9999) =     15.892 ms/op
    p(100.0000) =     15.892 ms/op


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
# Warmup Iteration   1: 5.827 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 4.070 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.092 ±(99.9%) 0.012 ms/op
Iteration   1: 4.001 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.758 ms/op
                 listUser·p0.50:   3.834 ms/op
                 listUser·p0.90:   5.104 ms/op
                 listUser·p0.95:   5.775 ms/op
                 listUser·p0.99:   6.889 ms/op
                 listUser·p0.999:  12.770 ms/op
                 listUser·p0.9999: 14.565 ms/op
                 listUser·p1.00:   15.892 ms/op

Iteration   2: 4.116 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.307 ms/op
                 listUser·p0.50:   3.912 ms/op
                 listUser·p0.90:   5.292 ms/op
                 listUser·p0.95:   5.808 ms/op
                 listUser·p0.99:   7.078 ms/op
                 listUser·p0.999:  15.379 ms/op
                 listUser·p0.9999: 23.698 ms/op
                 listUser·p1.00:   24.117 ms/op

Iteration   3: 4.022 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.785 ms/op
                 listUser·p0.50:   3.854 ms/op
                 listUser·p0.90:   4.932 ms/op
                 listUser·p0.95:   5.743 ms/op
                 listUser·p0.99:   7.078 ms/op
                 listUser·p0.999:  18.350 ms/op
                 listUser·p0.9999: 26.053 ms/op
                 listUser·p1.00:   26.477 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 237521
  mean =      4.046 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3110 
    [ 2.500,  5.000) = 207129 
    [ 5.000,  7.500) = 25810 
    [ 7.500, 10.000) = 995 
    [10.000, 12.500) = 104 
    [12.500, 15.000) = 140 
    [15.000, 17.500) = 79 
    [17.500, 20.000) = 67 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 48 
    [25.000, 27.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.307 ms/op
     p(50.0000) =      3.867 ms/op
     p(90.0000) =      5.136 ms/op
     p(95.0000) =      5.784 ms/op
     p(99.0000) =      7.021 ms/op
     p(99.9000) =     14.844 ms/op
     p(99.9900) =     24.543 ms/op
     p(99.9990) =     26.386 ms/op
     p(99.9999) =     26.477 ms/op
    p(100.0000) =     26.477 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.038 ± 3.698  ops/ms
ClientGrpc.existUser                       thrpt       3  10.508 ± 6.706  ops/ms
ClientGrpc.getUser                         thrpt       3  10.334 ± 5.336  ops/ms
ClientGrpc.listUser                        thrpt       3   7.771 ± 1.883  ops/ms
ClientGrpc.createUser                       avgt       3   3.045 ± 0.526   ms/op
ClientGrpc.existUser                        avgt       3   2.999 ± 0.311   ms/op
ClientGrpc.getUser                          avgt       3   3.134 ± 0.847   ms/op
ClientGrpc.listUser                         avgt       3   3.985 ± 0.620   ms/op
ClientGrpc.createUser                     sample  318937   3.008 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.425           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.994           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.523           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.756           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.489           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.947           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.894           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.660           ms/op
ClientGrpc.existUser                      sample  318812   3.011 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.642           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.998           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.531           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.752           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.407           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.201           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.828           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          16.810           ms/op
ClientGrpc.getUser                        sample  305751   3.140 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.260           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.125           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.662           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.887           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.637           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.020           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          15.188           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          15.892           ms/op
ClientGrpc.listUser                       sample  237521   4.046 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.307           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.867           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.136           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.784           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.021           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.844           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.543           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.477           ms/op
