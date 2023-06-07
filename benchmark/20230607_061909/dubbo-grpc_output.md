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
# Warmup Iteration   1: 2.975 ops/ms
# Warmup Iteration   2: 6.904 ops/ms
# Warmup Iteration   3: 8.088 ops/ms
Iteration   1: 8.592 ops/ms
Iteration   2: 8.687 ops/ms
Iteration   3: 8.534 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.605 ±(99.9%) 1.401 ops/ms [Average]
  (min, avg, max) = (8.534, 8.605, 8.687), stdev = 0.077
  CI (99.9%): [7.203, 10.006] (assumes normal distribution)


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
# Warmup Iteration   1: 5.606 ops/ms
# Warmup Iteration   2: 8.293 ops/ms
# Warmup Iteration   3: 9.083 ops/ms
Iteration   1: 9.254 ops/ms
Iteration   2: 9.208 ops/ms
Iteration   3: 9.248 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.237 ±(99.9%) 0.459 ops/ms [Average]
  (min, avg, max) = (9.208, 9.237, 9.254), stdev = 0.025
  CI (99.9%): [8.778, 9.696] (assumes normal distribution)


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
# Warmup Iteration   1: 5.472 ops/ms
# Warmup Iteration   2: 8.319 ops/ms
# Warmup Iteration   3: 8.763 ops/ms
Iteration   1: 8.707 ops/ms
Iteration   2: 8.835 ops/ms
Iteration   3: 8.711 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.751 ±(99.9%) 1.327 ops/ms [Average]
  (min, avg, max) = (8.707, 8.751, 8.835), stdev = 0.073
  CI (99.9%): [7.424, 10.079] (assumes normal distribution)


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
# Warmup Iteration   1: 5.013 ops/ms
# Warmup Iteration   2: 5.862 ops/ms
# Warmup Iteration   3: 6.451 ops/ms
Iteration   1: 6.651 ops/ms
Iteration   2: 6.652 ops/ms
Iteration   3: 6.844 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.716 ±(99.9%) 2.022 ops/ms [Average]
  (min, avg, max) = (6.651, 6.716, 6.844), stdev = 0.111
  CI (99.9%): [4.694, 8.737] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 5.677 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 4.003 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 3.936 ±(99.9%) 0.010 ms/op
Iteration   1: 3.640 ±(99.9%) 0.004 ms/op
Iteration   2: 3.551 ±(99.9%) 0.003 ms/op
Iteration   3: 3.584 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.591 ±(99.9%) 0.825 ms/op [Average]
  (min, avg, max) = (3.551, 3.591, 3.640), stdev = 0.045
  CI (99.9%): [2.767, 4.416] (assumes normal distribution)


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
# Warmup Iteration   1: 4.914 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.699 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.529 ±(99.9%) 0.003 ms/op
Iteration   1: 3.357 ±(99.9%) 0.005 ms/op
Iteration   2: 3.479 ±(99.9%) 0.003 ms/op
Iteration   3: 3.351 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.396 ±(99.9%) 1.316 ms/op [Average]
  (min, avg, max) = (3.351, 3.396, 3.479), stdev = 0.072
  CI (99.9%): [2.079, 4.712] (assumes normal distribution)


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
# Warmup Iteration   1: 5.122 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.890 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.780 ±(99.9%) 0.003 ms/op
Iteration   1: 3.640 ±(99.9%) 0.007 ms/op
Iteration   2: 3.612 ±(99.9%) 0.003 ms/op
Iteration   3: 3.625 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.626 ±(99.9%) 0.263 ms/op [Average]
  (min, avg, max) = (3.612, 3.626, 3.640), stdev = 0.014
  CI (99.9%): [3.363, 3.889] (assumes normal distribution)


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
# Warmup Iteration   1: 6.860 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 4.933 ±(99.9%) 0.033 ms/op
# Warmup Iteration   3: 4.763 ±(99.9%) 0.028 ms/op
Iteration   1: 4.492 ±(99.9%) 0.016 ms/op
Iteration   2: 4.599 ±(99.9%) 0.013 ms/op
Iteration   3: 4.727 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.606 ±(99.9%) 2.143 ms/op [Average]
  (min, avg, max) = (4.492, 4.606, 4.727), stdev = 0.117
  CI (99.9%): [2.463, 6.748] (assumes normal distribution)


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
# Warmup Iteration   1: 5.662 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 4.074 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.920 ±(99.9%) 0.009 ms/op
Iteration   1: 3.718 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.925 ms/op
                 createUser·p0.50:   3.604 ms/op
                 createUser·p0.90:   4.432 ms/op
                 createUser·p0.95:   4.882 ms/op
                 createUser·p0.99:   7.102 ms/op
                 createUser·p0.999:  13.297 ms/op
                 createUser·p0.9999: 16.475 ms/op
                 createUser·p1.00:   16.777 ms/op

Iteration   2: 3.661 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.846 ms/op
                 createUser·p0.50:   3.588 ms/op
                 createUser·p0.90:   4.391 ms/op
                 createUser·p0.95:   4.850 ms/op
                 createUser·p0.99:   6.267 ms/op
                 createUser·p0.999:  10.462 ms/op
                 createUser·p0.9999: 16.773 ms/op
                 createUser·p1.00:   17.334 ms/op

Iteration   3: 3.665 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.977 ms/op
                 createUser·p0.50:   3.600 ms/op
                 createUser·p0.90:   4.284 ms/op
                 createUser·p0.95:   4.604 ms/op
                 createUser·p0.99:   6.152 ms/op
                 createUser·p0.999:  10.858 ms/op
                 createUser·p0.9999: 18.687 ms/op
                 createUser·p1.00:   19.169 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 260884
  mean =      3.681 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 95 
    [ 1.250,  2.500) = 7103 
    [ 2.500,  3.750) = 156335 
    [ 3.750,  5.000) = 87570 
    [ 5.000,  6.250) = 6767 
    [ 6.250,  7.500) = 1638 
    [ 7.500,  8.750) = 721 
    [ 8.750, 10.000) = 251 
    [10.000, 11.250) = 127 
    [11.250, 12.500) = 24 
    [12.500, 13.750) = 61 
    [13.750, 15.000) = 58 
    [15.000, 16.250) = 64 
    [16.250, 17.500) = 45 
    [17.500, 18.750) = 20 

  Percentiles, ms/op:
      p(0.0000) =      0.846 ms/op
     p(50.0000) =      3.596 ms/op
     p(90.0000) =      4.366 ms/op
     p(95.0000) =      4.784 ms/op
     p(99.0000) =      6.447 ms/op
     p(99.9000) =     11.525 ms/op
     p(99.9900) =     17.328 ms/op
     p(99.9990) =     18.985 ms/op
     p(99.9999) =     19.169 ms/op
    p(100.0000) =     19.169 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.133 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.678 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.536 ±(99.9%) 0.008 ms/op
Iteration   1: 3.533 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.924 ms/op
                 existUser·p0.50:   3.449 ms/op
                 existUser·p0.90:   4.293 ms/op
                 existUser·p0.95:   4.784 ms/op
                 existUser·p0.99:   6.463 ms/op
                 existUser·p0.999:  11.336 ms/op
                 existUser·p0.9999: 18.510 ms/op
                 existUser·p1.00:   18.809 ms/op

Iteration   2: 3.498 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.559 ms/op
                 existUser·p0.50:   3.441 ms/op
                 existUser·p0.90:   4.133 ms/op
                 existUser·p0.95:   4.350 ms/op
                 existUser·p0.99:   5.472 ms/op
                 existUser·p0.999:  8.184 ms/op
                 existUser·p0.9999: 17.649 ms/op
                 existUser·p1.00:   18.088 ms/op

Iteration   3: 3.516 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.778 ms/op
                 existUser·p0.50:   3.428 ms/op
                 existUser·p0.90:   4.112 ms/op
                 existUser·p0.95:   4.522 ms/op
                 existUser·p0.99:   6.144 ms/op
                 existUser·p0.999:  11.911 ms/op
                 existUser·p0.9999: 20.120 ms/op
                 existUser·p1.00:   20.316 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 272797
  mean =      3.516 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9023 
    [ 2.500,  5.000) = 256428 
    [ 5.000,  7.500) = 6304 
    [ 7.500, 10.000) = 683 
    [10.000, 12.500) = 195 
    [12.500, 15.000) = 34 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 75 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.559 ms/op
     p(50.0000) =      3.441 ms/op
     p(90.0000) =      4.170 ms/op
     p(95.0000) =      4.547 ms/op
     p(99.0000) =      6.038 ms/op
     p(99.9000) =     10.964 ms/op
     p(99.9900) =     19.890 ms/op
     p(99.9990) =     20.227 ms/op
     p(99.9999) =     20.316 ms/op
    p(100.0000) =     20.316 ms/op


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
# Warmup Iteration   1: 5.374 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 3.972 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.719 ±(99.9%) 0.009 ms/op
Iteration   1: 3.736 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.063 ms/op
                 getUser·p0.50:   3.617 ms/op
                 getUser·p0.90:   4.547 ms/op
                 getUser·p0.95:   5.030 ms/op
                 getUser·p0.99:   6.447 ms/op
                 getUser·p0.999:  11.345 ms/op
                 getUser·p0.9999: 21.066 ms/op
                 getUser·p1.00:   21.332 ms/op

Iteration   2: 3.750 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.820 ms/op
                 getUser·p0.50:   3.641 ms/op
                 getUser·p0.90:   4.555 ms/op
                 getUser·p0.95:   4.956 ms/op
                 getUser·p0.99:   6.622 ms/op
                 getUser·p0.999:  11.038 ms/op
                 getUser·p0.9999: 15.843 ms/op
                 getUser·p1.00:   16.531 ms/op

Iteration   3: 3.722 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.905 ms/op
                 getUser·p0.50:   3.629 ms/op
                 getUser·p0.90:   4.465 ms/op
                 getUser·p0.95:   4.833 ms/op
                 getUser·p0.99:   6.537 ms/op
                 getUser·p0.999:  12.616 ms/op
                 getUser·p0.9999: 19.576 ms/op
                 getUser·p1.00:   20.873 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 256875
  mean =      3.736 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6574 
    [ 2.500,  5.000) = 238487 
    [ 5.000,  7.500) = 10475 
    [ 7.500, 10.000) = 905 
    [10.000, 12.500) = 230 
    [12.500, 15.000) = 70 
    [15.000, 17.500) = 42 
    [17.500, 20.000) = 63 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.820 ms/op
     p(50.0000) =      3.629 ms/op
     p(90.0000) =      4.514 ms/op
     p(95.0000) =      4.940 ms/op
     p(99.0000) =      6.537 ms/op
     p(99.9000) =     11.538 ms/op
     p(99.9900) =     20.457 ms/op
     p(99.9990) =     21.266 ms/op
     p(99.9999) =     21.332 ms/op
    p(100.0000) =     21.332 ms/op


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
# Warmup Iteration   1: 6.472 ±(99.9%) 0.078 ms/op
# Warmup Iteration   2: 4.999 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.890 ±(99.9%) 0.016 ms/op
Iteration   1: 4.789 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.444 ms/op
                 listUser·p0.50:   4.547 ms/op
                 listUser·p0.90:   6.087 ms/op
                 listUser·p0.95:   6.930 ms/op
                 listUser·p0.99:   8.700 ms/op
                 listUser·p0.999:  14.287 ms/op
                 listUser·p0.9999: 18.547 ms/op
                 listUser·p1.00:   20.087 ms/op

Iteration   2: 4.755 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.094 ms/op
                 listUser·p0.50:   4.497 ms/op
                 listUser·p0.90:   6.160 ms/op
                 listUser·p0.95:   7.070 ms/op
                 listUser·p0.99:   8.634 ms/op
                 listUser·p0.999:  17.424 ms/op
                 listUser·p0.9999: 21.219 ms/op
                 listUser·p1.00:   24.576 ms/op

Iteration   3: 4.872 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.036 ms/op
                 listUser·p0.50:   4.637 ms/op
                 listUser·p0.90:   6.144 ms/op
                 listUser·p0.95:   7.004 ms/op
                 listUser·p0.99:   8.700 ms/op
                 listUser·p0.999:  18.973 ms/op
                 listUser·p0.9999: 23.790 ms/op
                 listUser·p1.00:   24.117 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 199784
  mean =      4.805 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 502 
    [ 2.500,  5.000) = 145306 
    [ 5.000,  7.500) = 47645 
    [ 7.500, 10.000) = 5444 
    [10.000, 12.500) = 477 
    [12.500, 15.000) = 129 
    [15.000, 17.500) = 94 
    [17.500, 20.000) = 117 
    [20.000, 22.500) = 42 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.036 ms/op
     p(50.0000) =      4.563 ms/op
     p(90.0000) =      6.136 ms/op
     p(95.0000) =      7.004 ms/op
     p(99.0000) =      8.684 ms/op
     p(99.9000) =     17.236 ms/op
     p(99.9900) =     23.202 ms/op
     p(99.9990) =     24.347 ms/op
     p(99.9999) =     24.576 ms/op
    p(100.0000) =     24.576 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.605 ± 1.401  ops/ms
ClientGrpc.existUser                       thrpt       3   9.237 ± 0.459  ops/ms
ClientGrpc.getUser                         thrpt       3   8.751 ± 1.327  ops/ms
ClientGrpc.listUser                        thrpt       3   6.716 ± 2.022  ops/ms
ClientGrpc.createUser                       avgt       3   3.591 ± 0.825   ms/op
ClientGrpc.existUser                        avgt       3   3.396 ± 1.316   ms/op
ClientGrpc.getUser                          avgt       3   3.626 ± 0.263   ms/op
ClientGrpc.listUser                         avgt       3   4.606 ± 2.143   ms/op
ClientGrpc.createUser                     sample  260884   3.681 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.846           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.596           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.366           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.784           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.447           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.525           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.328           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          19.169           ms/op
ClientGrpc.existUser                      sample  272797   3.516 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.559           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.441           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.170           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.547           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.038           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.964           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.890           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.316           ms/op
ClientGrpc.getUser                        sample  256875   3.736 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.820           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.629           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.514           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.940           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.537           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.538           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.457           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.332           ms/op
ClientGrpc.listUser                       sample  199784   4.805 ± 0.009   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.036           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.563           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.136           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.004           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.684           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.236           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.202           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.576           ms/op
