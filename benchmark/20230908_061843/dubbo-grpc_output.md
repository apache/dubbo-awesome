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
# Warmup Iteration   1: 3.196 ops/ms
# Warmup Iteration   2: 7.077 ops/ms
# Warmup Iteration   3: 8.223 ops/ms
Iteration   1: 8.662 ops/ms
Iteration   2: 8.958 ops/ms
Iteration   3: 8.749 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.790 ±(99.9%) 2.778 ops/ms [Average]
  (min, avg, max) = (8.662, 8.790, 8.958), stdev = 0.152
  CI (99.9%): [6.012, 11.568] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 5.013 ops/ms
# Warmup Iteration   2: 8.343 ops/ms
# Warmup Iteration   3: 9.353 ops/ms
Iteration   1: 9.263 ops/ms
Iteration   2: 9.055 ops/ms
Iteration   3: 9.191 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.170 ±(99.9%) 1.933 ops/ms [Average]
  (min, avg, max) = (9.055, 9.170, 9.263), stdev = 0.106
  CI (99.9%): [7.237, 11.102] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 5.208 ops/ms
# Warmup Iteration   2: 7.885 ops/ms
# Warmup Iteration   3: 8.299 ops/ms
Iteration   1: 8.393 ops/ms
Iteration   2: 8.699 ops/ms
Iteration   3: 8.531 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.541 ±(99.9%) 2.799 ops/ms [Average]
  (min, avg, max) = (8.393, 8.541, 8.699), stdev = 0.153
  CI (99.9%): [5.742, 11.340] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 4.215 ops/ms
# Warmup Iteration   2: 6.090 ops/ms
# Warmup Iteration   3: 6.677 ops/ms
Iteration   1: 6.411 ops/ms
Iteration   2: 6.585 ops/ms
Iteration   3: 6.445 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.480 ±(99.9%) 1.678 ops/ms [Average]
  (min, avg, max) = (6.411, 6.480, 6.585), stdev = 0.092
  CI (99.9%): [4.802, 8.158] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 5.152 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 4.062 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 3.843 ±(99.9%) 0.003 ms/op
Iteration   1: 3.950 ±(99.9%) 0.014 ms/op
Iteration   2: 3.944 ±(99.9%) 0.005 ms/op
Iteration   3: 3.943 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.946 ±(99.9%) 0.072 ms/op [Average]
  (min, avg, max) = (3.943, 3.946, 3.950), stdev = 0.004
  CI (99.9%): [3.874, 4.017] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 4.788 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.735 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.576 ±(99.9%) 0.004 ms/op
Iteration   1: 3.568 ±(99.9%) 0.002 ms/op
Iteration   2: 3.497 ±(99.9%) 0.003 ms/op
Iteration   3: 3.375 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.480 ±(99.9%) 1.781 ms/op [Average]
  (min, avg, max) = (3.375, 3.480, 3.568), stdev = 0.098
  CI (99.9%): [1.700, 5.261] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 5.490 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.925 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.905 ±(99.9%) 0.004 ms/op
Iteration   1: 3.736 ±(99.9%) 0.003 ms/op
Iteration   2: 3.624 ±(99.9%) 0.003 ms/op
Iteration   3: 3.665 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.675 ±(99.9%) 1.032 ms/op [Average]
  (min, avg, max) = (3.624, 3.675, 3.736), stdev = 0.057
  CI (99.9%): [2.643, 4.707] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 6.760 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 5.280 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.946 ±(99.9%) 0.012 ms/op
Iteration   1: 4.796 ±(99.9%) 0.007 ms/op
Iteration   2: 4.739 ±(99.9%) 0.016 ms/op
Iteration   3: 4.730 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.755 ±(99.9%) 0.654 ms/op [Average]
  (min, avg, max) = (4.730, 4.755, 4.796), stdev = 0.036
  CI (99.9%): [4.101, 5.409] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 5.577 ±(99.9%) 0.061 ms/op
# Warmup Iteration   2: 4.112 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.818 ±(99.9%) 0.010 ms/op
Iteration   1: 3.672 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.609 ms/op
                 createUser·p0.50:   3.629 ms/op
                 createUser·p0.90:   4.481 ms/op
                 createUser·p0.95:   4.866 ms/op
                 createUser·p0.99:   6.103 ms/op
                 createUser·p0.999:  10.469 ms/op
                 createUser·p0.9999: 14.240 ms/op
                 createUser·p1.00:   14.500 ms/op

Iteration   2: 3.646 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.081 ms/op
                 createUser·p0.50:   3.568 ms/op
                 createUser·p0.90:   4.350 ms/op
                 createUser·p0.95:   4.710 ms/op
                 createUser·p0.99:   6.152 ms/op
                 createUser·p0.999:  11.614 ms/op
                 createUser·p0.9999: 16.424 ms/op
                 createUser·p1.00:   16.941 ms/op

Iteration   3: 3.783 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.946 ms/op
                 createUser·p0.50:   3.682 ms/op
                 createUser·p0.90:   4.588 ms/op
                 createUser·p0.95:   5.120 ms/op
                 createUser·p0.99:   7.094 ms/op
                 createUser·p0.999:  15.228 ms/op
                 createUser·p0.9999: 20.221 ms/op
                 createUser·p1.00:   20.480 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 259323
  mean =      3.699 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11057 
    [ 2.500,  5.000) = 237061 
    [ 5.000,  7.500) = 9800 
    [ 7.500, 10.000) = 841 
    [10.000, 12.500) = 292 
    [12.500, 15.000) = 139 
    [15.000, 17.500) = 81 
    [17.500, 20.000) = 36 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.609 ms/op
     p(50.0000) =      3.625 ms/op
     p(90.0000) =      4.473 ms/op
     p(95.0000) =      4.899 ms/op
     p(99.0000) =      6.496 ms/op
     p(99.9000) =     12.594 ms/op
     p(99.9900) =     19.630 ms/op
     p(99.9990) =     20.362 ms/op
     p(99.9999) =     20.480 ms/op
    p(100.0000) =     20.480 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.147 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 3.841 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.692 ±(99.9%) 0.008 ms/op
Iteration   1: 3.610 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.849 ms/op
                 existUser·p0.50:   3.535 ms/op
                 existUser·p0.90:   4.243 ms/op
                 existUser·p0.95:   4.563 ms/op
                 existUser·p0.99:   5.890 ms/op
                 existUser·p0.999:  11.649 ms/op
                 existUser·p0.9999: 15.114 ms/op
                 existUser·p1.00:   15.483 ms/op

Iteration   2: 3.633 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.382 ms/op
                 existUser·p0.50:   3.580 ms/op
                 existUser·p0.90:   4.596 ms/op
                 existUser·p0.95:   5.095 ms/op
                 existUser·p0.99:   7.196 ms/op
                 existUser·p0.999:  11.158 ms/op
                 existUser·p0.9999: 17.412 ms/op
                 existUser·p1.00:   18.317 ms/op

Iteration   3: 3.552 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.865 ms/op
                 existUser·p0.50:   3.494 ms/op
                 existUser·p0.90:   4.220 ms/op
                 existUser·p0.95:   4.596 ms/op
                 existUser·p0.99:   5.882 ms/op
                 existUser·p0.999:  8.895 ms/op
                 existUser·p0.9999: 18.547 ms/op
                 existUser·p1.00:   20.840 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 266819
  mean =      3.598 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14089 
    [ 2.500,  5.000) = 243319 
    [ 5.000,  7.500) = 8019 
    [ 7.500, 10.000) = 950 
    [10.000, 12.500) = 303 
    [12.500, 15.000) = 33 
    [15.000, 17.500) = 68 
    [17.500, 20.000) = 35 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.382 ms/op
     p(50.0000) =      3.531 ms/op
     p(90.0000) =      4.358 ms/op
     p(95.0000) =      4.760 ms/op
     p(99.0000) =      6.480 ms/op
     p(99.9000) =     10.964 ms/op
     p(99.9900) =     17.935 ms/op
     p(99.9990) =     20.469 ms/op
     p(99.9999) =     20.840 ms/op
    p(100.0000) =     20.840 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.303 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.875 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.861 ±(99.9%) 0.010 ms/op
Iteration   1: 3.812 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.700 ms/op
                 getUser·p0.50:   3.752 ms/op
                 getUser·p0.90:   4.628 ms/op
                 getUser·p0.95:   5.022 ms/op
                 getUser·p0.99:   6.537 ms/op
                 getUser·p0.999:  11.667 ms/op
                 getUser·p0.9999: 14.982 ms/op
                 getUser·p1.00:   15.499 ms/op

Iteration   2: 3.879 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.985 ms/op
                 getUser·p0.50:   3.785 ms/op
                 getUser·p0.90:   4.694 ms/op
                 getUser·p0.95:   5.063 ms/op
                 getUser·p0.99:   6.488 ms/op
                 getUser·p0.999:  10.363 ms/op
                 getUser·p0.9999: 18.047 ms/op
                 getUser·p1.00:   18.416 ms/op

Iteration   3: 3.828 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.742 ms/op
                 getUser·p0.50:   3.723 ms/op
                 getUser·p0.90:   4.702 ms/op
                 getUser·p0.95:   5.202 ms/op
                 getUser·p0.99:   7.160 ms/op
                 getUser·p0.999:  12.599 ms/op
                 getUser·p0.9999: 20.751 ms/op
                 getUser·p1.00:   21.168 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 250033
  mean =      3.839 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9248 
    [ 2.500,  5.000) = 226477 
    [ 5.000,  7.500) = 12655 
    [ 7.500, 10.000) = 1084 
    [10.000, 12.500) = 399 
    [12.500, 15.000) = 68 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 57 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.700 ms/op
     p(50.0000) =      3.752 ms/op
     p(90.0000) =      4.678 ms/op
     p(95.0000) =      5.087 ms/op
     p(99.0000) =      6.701 ms/op
     p(99.9000) =     12.042 ms/op
     p(99.9900) =     19.595 ms/op
     p(99.9990) =     21.103 ms/op
     p(99.9999) =     21.168 ms/op
    p(100.0000) =     21.168 ms/op


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
# Warmup Iteration   1: 6.383 ±(99.9%) 0.069 ms/op
# Warmup Iteration   2: 5.049 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.915 ±(99.9%) 0.016 ms/op
Iteration   1: 4.808 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.397 ms/op
                 listUser·p0.50:   4.579 ms/op
                 listUser·p0.90:   6.300 ms/op
                 listUser·p0.95:   7.143 ms/op
                 listUser·p0.99:   8.897 ms/op
                 listUser·p0.999:  14.582 ms/op
                 listUser·p0.9999: 17.476 ms/op
                 listUser·p1.00:   17.924 ms/op

Iteration   2: 4.807 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.401 ms/op
                 listUser·p0.50:   4.530 ms/op
                 listUser·p0.90:   6.365 ms/op
                 listUser·p0.95:   7.250 ms/op
                 listUser·p0.99:   9.339 ms/op
                 listUser·p0.999:  16.876 ms/op
                 listUser·p0.9999: 20.626 ms/op
                 listUser·p1.00:   22.512 ms/op

Iteration   3: 4.756 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.298 ms/op
                 listUser·p0.50:   4.563 ms/op
                 listUser·p0.90:   5.980 ms/op
                 listUser·p0.95:   6.906 ms/op
                 listUser·p0.99:   8.438 ms/op
                 listUser·p0.999:  20.704 ms/op
                 listUser·p0.9999: 26.391 ms/op
                 listUser·p1.00:   26.837 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 200387
  mean =      4.790 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 632 
    [ 2.500,  5.000) = 145820 
    [ 5.000,  7.500) = 46996 
    [ 7.500, 10.000) = 5896 
    [10.000, 12.500) = 603 
    [12.500, 15.000) = 163 
    [15.000, 17.500) = 124 
    [17.500, 20.000) = 51 
    [20.000, 22.500) = 66 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      1.298 ms/op
     p(50.0000) =      4.555 ms/op
     p(90.0000) =      6.234 ms/op
     p(95.0000) =      7.102 ms/op
     p(99.0000) =      8.929 ms/op
     p(99.9000) =     16.531 ms/op
     p(99.9900) =     23.560 ms/op
     p(99.9990) =     26.706 ms/op
     p(99.9999) =     26.837 ms/op
    p(100.0000) =     26.837 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.790 ± 2.778  ops/ms
ClientGrpc.existUser                       thrpt       3   9.170 ± 1.933  ops/ms
ClientGrpc.getUser                         thrpt       3   8.541 ± 2.799  ops/ms
ClientGrpc.listUser                        thrpt       3   6.480 ± 1.678  ops/ms
ClientGrpc.createUser                       avgt       3   3.946 ± 0.072   ms/op
ClientGrpc.existUser                        avgt       3   3.480 ± 1.781   ms/op
ClientGrpc.getUser                          avgt       3   3.675 ± 1.032   ms/op
ClientGrpc.listUser                         avgt       3   4.755 ± 0.654   ms/op
ClientGrpc.createUser                     sample  259323   3.699 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.609           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.625           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.473           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.899           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.496           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.594           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.630           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          20.480           ms/op
ClientGrpc.existUser                      sample  266819   3.598 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.382           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.531           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.358           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.760           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.480           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.964           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.935           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.840           ms/op
ClientGrpc.getUser                        sample  250033   3.839 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.700           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.752           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.678           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.087           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.701           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.042           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.595           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.168           ms/op
ClientGrpc.listUser                       sample  200387   4.790 ± 0.009   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.298           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.555           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.234           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.102           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.929           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.531           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.560           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.837           ms/op
