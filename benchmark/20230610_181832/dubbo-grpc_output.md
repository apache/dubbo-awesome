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
# Warmup Iteration   1: 4.711 ops/ms
# Warmup Iteration   2: 9.234 ops/ms
# Warmup Iteration   3: 10.399 ops/ms
Iteration   1: 10.761 ops/ms
Iteration   2: 10.519 ops/ms
Iteration   3: 10.679 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.653 ±(99.9%) 2.248 ops/ms [Average]
  (min, avg, max) = (10.519, 10.653, 10.761), stdev = 0.123
  CI (99.9%): [8.404, 12.901] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 7.907 ops/ms
# Warmup Iteration   2: 10.777 ops/ms
# Warmup Iteration   3: 11.267 ops/ms
Iteration   1: 11.089 ops/ms
Iteration   2: 11.217 ops/ms
Iteration   3: 11.401 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.236 ±(99.9%) 2.860 ops/ms [Average]
  (min, avg, max) = (11.089, 11.236, 11.401), stdev = 0.157
  CI (99.9%): [8.375, 14.096] (assumes normal distribution)


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
# Warmup Iteration   1: 8.317 ops/ms
# Warmup Iteration   2: 10.434 ops/ms
# Warmup Iteration   3: 10.666 ops/ms
Iteration   1: 10.798 ops/ms
Iteration   2: 10.774 ops/ms
Iteration   3: 10.944 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.839 ±(99.9%) 1.676 ops/ms [Average]
  (min, avg, max) = (10.774, 10.839, 10.944), stdev = 0.092
  CI (99.9%): [9.163, 12.514] (assumes normal distribution)


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
# Warmup Iteration   1: 5.962 ops/ms
# Warmup Iteration   2: 8.157 ops/ms
# Warmup Iteration   3: 8.030 ops/ms
Iteration   1: 8.324 ops/ms
Iteration   2: 8.473 ops/ms
Iteration   3: 8.375 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.391 ±(99.9%) 1.380 ops/ms [Average]
  (min, avg, max) = (8.324, 8.391, 8.473), stdev = 0.076
  CI (99.9%): [7.011, 9.771] (assumes normal distribution)


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
# Warmup Iteration   1: 4.077 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.121 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.973 ±(99.9%) 0.004 ms/op
Iteration   1: 2.981 ±(99.9%) 0.006 ms/op
Iteration   2: 2.970 ±(99.9%) 0.003 ms/op
Iteration   3: 2.958 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.970 ±(99.9%) 0.206 ms/op [Average]
  (min, avg, max) = (2.958, 2.970, 2.981), stdev = 0.011
  CI (99.9%): [2.764, 3.176] (assumes normal distribution)


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
# Warmup Iteration   1: 3.849 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.912 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.853 ±(99.9%) 0.003 ms/op
Iteration   1: 2.855 ±(99.9%) 0.004 ms/op
Iteration   2: 2.843 ±(99.9%) 0.003 ms/op
Iteration   3: 2.771 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.823 ±(99.9%) 0.831 ms/op [Average]
  (min, avg, max) = (2.771, 2.823, 2.855), stdev = 0.046
  CI (99.9%): [1.992, 3.654] (assumes normal distribution)


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
# Warmup Iteration   1: 3.979 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.141 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.014 ±(99.9%) 0.003 ms/op
Iteration   1: 3.031 ±(99.9%) 0.002 ms/op
Iteration   2: 3.036 ±(99.9%) 0.003 ms/op
Iteration   3: 2.995 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.021 ±(99.9%) 0.412 ms/op [Average]
  (min, avg, max) = (2.995, 3.021, 3.036), stdev = 0.023
  CI (99.9%): [2.609, 3.433] (assumes normal distribution)


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
# Warmup Iteration   1: 4.748 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 4.048 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.913 ±(99.9%) 0.022 ms/op
Iteration   1: 3.941 ±(99.9%) 0.031 ms/op
Iteration   2: 3.900 ±(99.9%) 0.022 ms/op
Iteration   3: 3.975 ±(99.9%) 0.028 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.939 ±(99.9%) 0.682 ms/op [Average]
  (min, avg, max) = (3.900, 3.939, 3.975), stdev = 0.037
  CI (99.9%): [3.256, 4.621] (assumes normal distribution)


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
# Warmup Iteration   1: 3.995 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.196 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.055 ±(99.9%) 0.006 ms/op
Iteration   1: 3.062 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.692 ms/op
                 createUser·p0.50:   3.031 ms/op
                 createUser·p0.90:   3.523 ms/op
                 createUser·p0.95:   3.719 ms/op
                 createUser·p0.99:   4.391 ms/op
                 createUser·p0.999:  7.832 ms/op
                 createUser·p0.9999: 15.983 ms/op
                 createUser·p1.00:   17.334 ms/op

Iteration   2: 3.024 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.615 ms/op
                 createUser·p0.50:   3.006 ms/op
                 createUser·p0.90:   3.490 ms/op
                 createUser·p0.95:   3.772 ms/op
                 createUser·p0.99:   4.596 ms/op
                 createUser·p0.999:  9.306 ms/op
                 createUser·p0.9999: 16.718 ms/op
                 createUser·p1.00:   16.876 ms/op

Iteration   3: 3.073 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.760 ms/op
                 createUser·p0.50:   3.047 ms/op
                 createUser·p0.90:   3.682 ms/op
                 createUser·p0.95:   3.899 ms/op
                 createUser·p0.99:   4.669 ms/op
                 createUser·p0.999:  7.478 ms/op
                 createUser·p0.9999: 29.229 ms/op
                 createUser·p1.00:   29.458 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 314388
  mean =      3.053 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21474 
    [ 2.500,  5.000) = 291053 
    [ 5.000,  7.500) = 1445 
    [ 7.500, 10.000) = 174 
    [10.000, 12.500) = 18 
    [12.500, 15.000) = 53 
    [15.000, 17.500) = 117 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.615 ms/op
     p(50.0000) =      3.027 ms/op
     p(90.0000) =      3.572 ms/op
     p(95.0000) =      3.805 ms/op
     p(99.0000) =      4.555 ms/op
     p(99.9000) =      8.831 ms/op
     p(99.9900) =     27.445 ms/op
     p(99.9990) =     29.360 ms/op
     p(99.9999) =     29.458 ms/op
    p(100.0000) =     29.458 ms/op


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
# Warmup Iteration   1: 3.964 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.000 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.840 ±(99.9%) 0.006 ms/op
Iteration   1: 2.948 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.771 ms/op
                 existUser·p0.50:   2.920 ms/op
                 existUser·p0.90:   3.457 ms/op
                 existUser·p0.95:   3.621 ms/op
                 existUser·p0.99:   4.366 ms/op
                 existUser·p0.999:  6.584 ms/op
                 existUser·p0.9999: 12.831 ms/op
                 existUser·p1.00:   13.206 ms/op

Iteration   2: 2.948 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.749 ms/op
                 existUser·p0.50:   2.925 ms/op
                 existUser·p0.90:   3.457 ms/op
                 existUser·p0.95:   3.641 ms/op
                 existUser·p0.99:   4.588 ms/op
                 existUser·p0.999:  7.354 ms/op
                 existUser·p0.9999: 21.108 ms/op
                 existUser·p1.00:   22.053 ms/op

Iteration   3: 2.935 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.746 ms/op
                 existUser·p0.50:   2.904 ms/op
                 existUser·p0.90:   3.441 ms/op
                 existUser·p0.95:   3.715 ms/op
                 existUser·p0.99:   4.645 ms/op
                 existUser·p0.999:  6.743 ms/op
                 existUser·p0.9999: 15.255 ms/op
                 existUser·p1.00:   16.073 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 325997
  mean =      2.944 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 37177 
    [ 2.500,  5.000) = 287416 
    [ 5.000,  7.500) = 1142 
    [ 7.500, 10.000) = 102 
    [10.000, 12.500) = 42 
    [12.500, 15.000) = 66 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.746 ms/op
     p(50.0000) =      2.916 ms/op
     p(90.0000) =      3.453 ms/op
     p(95.0000) =      3.650 ms/op
     p(99.0000) =      4.563 ms/op
     p(99.9000) =      6.881 ms/op
     p(99.9900) =     17.771 ms/op
     p(99.9990) =     21.946 ms/op
     p(99.9999) =     22.053 ms/op
    p(100.0000) =     22.053 ms/op


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
# Warmup Iteration   1: 4.104 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.060 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.034 ±(99.9%) 0.006 ms/op
Iteration   1: 3.008 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.880 ms/op
                 getUser·p0.50:   2.998 ms/op
                 getUser·p0.90:   3.453 ms/op
                 getUser·p0.95:   3.727 ms/op
                 getUser·p0.99:   4.489 ms/op
                 getUser·p0.999:  6.722 ms/op
                 getUser·p0.9999: 11.698 ms/op
                 getUser·p1.00:   11.977 ms/op

Iteration   2: 3.026 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.724 ms/op
                 getUser·p0.50:   3.019 ms/op
                 getUser·p0.90:   3.604 ms/op
                 getUser·p0.95:   3.809 ms/op
                 getUser·p0.99:   4.465 ms/op
                 getUser·p0.999:  8.671 ms/op
                 getUser·p0.9999: 13.105 ms/op
                 getUser·p1.00:   13.255 ms/op

Iteration   3: 2.958 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.730 ms/op
                 getUser·p0.50:   2.974 ms/op
                 getUser·p0.90:   3.432 ms/op
                 getUser·p0.95:   3.695 ms/op
                 getUser·p0.99:   4.415 ms/op
                 getUser·p0.999:  6.184 ms/op
                 getUser·p0.9999: 15.590 ms/op
                 getUser·p1.00:   15.860 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 320360
  mean =      2.997 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2055 
    [ 1.250,  2.500) = 24026 
    [ 2.500,  3.750) = 277825 
    [ 3.750,  5.000) = 15271 
    [ 5.000,  6.250) = 685 
    [ 6.250,  7.500) = 204 
    [ 7.500,  8.750) = 64 
    [ 8.750, 10.000) = 38 
    [10.000, 11.250) = 36 
    [11.250, 12.500) = 59 
    [12.500, 13.750) = 58 
    [13.750, 15.000) = 4 
    [15.000, 16.250) = 35 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.724 ms/op
     p(50.0000) =      2.994 ms/op
     p(90.0000) =      3.498 ms/op
     p(95.0000) =      3.760 ms/op
     p(99.0000) =      4.456 ms/op
     p(99.9000) =      7.069 ms/op
     p(99.9900) =     15.153 ms/op
     p(99.9990) =     15.761 ms/op
     p(99.9999) =     15.860 ms/op
    p(100.0000) =     15.860 ms/op


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
# Warmup Iteration   1: 5.662 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 4.016 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.930 ±(99.9%) 0.010 ms/op
Iteration   1: 3.908 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.053 ms/op
                 listUser·p0.50:   3.748 ms/op
                 listUser·p0.90:   4.989 ms/op
                 listUser·p0.95:   5.811 ms/op
                 listUser·p0.99:   6.709 ms/op
                 listUser·p0.999:  12.274 ms/op
                 listUser·p0.9999: 18.344 ms/op
                 listUser·p1.00:   18.907 ms/op

Iteration   2: 3.821 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.241 ms/op
                 listUser·p0.50:   3.703 ms/op
                 listUser·p0.90:   4.760 ms/op
                 listUser·p0.95:   5.399 ms/op
                 listUser·p0.99:   6.439 ms/op
                 listUser·p0.999:  13.388 ms/op
                 listUser·p0.9999: 20.283 ms/op
                 listUser·p1.00:   20.775 ms/op

Iteration   3: 3.897 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.923 ms/op
                 listUser·p0.50:   3.748 ms/op
                 listUser·p0.90:   4.932 ms/op
                 listUser·p0.95:   5.497 ms/op
                 listUser·p0.99:   6.668 ms/op
                 listUser·p0.999:  20.183 ms/op
                 listUser·p0.9999: 24.228 ms/op
                 listUser·p1.00:   25.264 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 247861
  mean =      3.875 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5692 
    [ 2.500,  5.000) = 219927 
    [ 5.000,  7.500) = 21314 
    [ 7.500, 10.000) = 511 
    [10.000, 12.500) = 108 
    [12.500, 15.000) = 147 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 53 
    [20.000, 22.500) = 76 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.923 ms/op
     p(50.0000) =      3.731 ms/op
     p(90.0000) =      4.899 ms/op
     p(95.0000) =      5.579 ms/op
     p(99.0000) =      6.619 ms/op
     p(99.9000) =     13.175 ms/op
     p(99.9900) =     22.643 ms/op
     p(99.9990) =     25.248 ms/op
     p(99.9999) =     25.264 ms/op
    p(100.0000) =     25.264 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.653 ± 2.248  ops/ms
ClientGrpc.existUser                       thrpt       3  11.236 ± 2.860  ops/ms
ClientGrpc.getUser                         thrpt       3  10.839 ± 1.676  ops/ms
ClientGrpc.listUser                        thrpt       3   8.391 ± 1.380  ops/ms
ClientGrpc.createUser                       avgt       3   2.970 ± 0.206   ms/op
ClientGrpc.existUser                        avgt       3   2.823 ± 0.831   ms/op
ClientGrpc.getUser                          avgt       3   3.021 ± 0.412   ms/op
ClientGrpc.listUser                         avgt       3   3.939 ± 0.682   ms/op
ClientGrpc.createUser                     sample  314388   3.053 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.615           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.027           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.572           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.805           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.555           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.831           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          27.445           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          29.458           ms/op
ClientGrpc.existUser                      sample  325997   2.944 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.746           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.916           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.453           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.650           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.563           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.881           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.771           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.053           ms/op
ClientGrpc.getUser                        sample  320360   2.997 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.724           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.994           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.498           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.760           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.456           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.069           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          15.153           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          15.860           ms/op
ClientGrpc.listUser                       sample  247861   3.875 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.923           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.731           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.899           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.579           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.619           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.175           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.643           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.264           ms/op
