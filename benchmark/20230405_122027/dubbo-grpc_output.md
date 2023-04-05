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
# Warmup Iteration   1: 3.213 ops/ms
# Warmup Iteration   2: 6.972 ops/ms
# Warmup Iteration   3: 8.220 ops/ms
Iteration   1: 8.553 ops/ms
Iteration   2: 8.584 ops/ms
Iteration   3: 8.493 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.543 ±(99.9%) 0.838 ops/ms [Average]
  (min, avg, max) = (8.493, 8.543, 8.584), stdev = 0.046
  CI (99.9%): [7.706, 9.381] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 5.835 ops/ms
# Warmup Iteration   2: 8.551 ops/ms
# Warmup Iteration   3: 9.323 ops/ms
Iteration   1: 9.293 ops/ms
Iteration   2: 9.490 ops/ms
Iteration   3: 9.673 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.486 ±(99.9%) 3.472 ops/ms [Average]
  (min, avg, max) = (9.293, 9.486, 9.673), stdev = 0.190
  CI (99.9%): [6.014, 12.958] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 5.195 ops/ms
# Warmup Iteration   2: 8.064 ops/ms
# Warmup Iteration   3: 8.685 ops/ms
Iteration   1: 8.815 ops/ms
Iteration   2: 8.802 ops/ms
Iteration   3: 8.748 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.788 ±(99.9%) 0.651 ops/ms [Average]
  (min, avg, max) = (8.748, 8.788, 8.815), stdev = 0.036
  CI (99.9%): [8.137, 9.439] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 4.257 ops/ms
# Warmup Iteration   2: 6.175 ops/ms
# Warmup Iteration   3: 6.659 ops/ms
Iteration   1: 6.913 ops/ms
Iteration   2: 6.904 ops/ms
Iteration   3: 6.701 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.839 ±(99.9%) 2.184 ops/ms [Average]
  (min, avg, max) = (6.701, 6.839, 6.913), stdev = 0.120
  CI (99.9%): [4.656, 9.023] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 5.382 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.925 ±(99.9%) 0.043 ms/op
# Warmup Iteration   3: 3.756 ±(99.9%) 0.005 ms/op
Iteration   1: 3.718 ±(99.9%) 0.003 ms/op
Iteration   2: 3.672 ±(99.9%) 0.003 ms/op
Iteration   3: 3.683 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.691 ±(99.9%) 0.442 ms/op [Average]
  (min, avg, max) = (3.672, 3.691, 3.718), stdev = 0.024
  CI (99.9%): [3.249, 4.133] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 5.032 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.595 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.523 ±(99.9%) 0.003 ms/op
Iteration   1: 3.421 ±(99.9%) 0.003 ms/op
Iteration   2: 3.420 ±(99.9%) 0.002 ms/op
Iteration   3: 3.427 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.423 ±(99.9%) 0.077 ms/op [Average]
  (min, avg, max) = (3.420, 3.423, 3.427), stdev = 0.004
  CI (99.9%): [3.346, 3.500] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 5.374 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.759 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.681 ±(99.9%) 0.005 ms/op
Iteration   1: 3.659 ±(99.9%) 0.007 ms/op
Iteration   2: 3.570 ±(99.9%) 0.004 ms/op
Iteration   3: 3.612 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.613 ±(99.9%) 0.814 ms/op [Average]
  (min, avg, max) = (3.570, 3.613, 3.659), stdev = 0.045
  CI (99.9%): [2.799, 4.427] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 5.922 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 5.060 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 4.667 ±(99.9%) 0.011 ms/op
Iteration   1: 4.503 ±(99.9%) 0.008 ms/op
Iteration   2: 4.705 ±(99.9%) 0.017 ms/op
Iteration   3: 4.423 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.544 ±(99.9%) 2.656 ms/op [Average]
  (min, avg, max) = (4.423, 4.544, 4.705), stdev = 0.146
  CI (99.9%): [1.888, 7.200] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 5.845 ±(99.9%) 0.061 ms/op
# Warmup Iteration   2: 3.913 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.676 ±(99.9%) 0.010 ms/op
Iteration   1: 3.593 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.673 ms/op
                 createUser·p0.50:   3.531 ms/op
                 createUser·p0.90:   4.219 ms/op
                 createUser·p0.95:   4.645 ms/op
                 createUser·p0.99:   6.128 ms/op
                 createUser·p0.999:  9.614 ms/op
                 createUser·p0.9999: 18.612 ms/op
                 createUser·p1.00:   20.382 ms/op

Iteration   2: 3.631 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.749 ms/op
                 createUser·p0.50:   3.555 ms/op
                 createUser·p0.90:   4.243 ms/op
                 createUser·p0.95:   4.596 ms/op
                 createUser·p0.99:   5.980 ms/op
                 createUser·p0.999:  13.249 ms/op
                 createUser·p0.9999: 19.972 ms/op
                 createUser·p1.00:   20.316 ms/op

Iteration   3: 3.587 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.687 ms/op
                 createUser·p0.50:   3.564 ms/op
                 createUser·p0.90:   4.219 ms/op
                 createUser·p0.95:   4.481 ms/op
                 createUser·p0.99:   5.284 ms/op
                 createUser·p0.999:  13.730 ms/op
                 createUser·p0.9999: 26.385 ms/op
                 createUser·p1.00:   27.034 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 266510
  mean =      3.603 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8379 
    [ 2.500,  5.000) = 251614 
    [ 5.000,  7.500) = 5424 
    [ 7.500, 10.000) = 783 
    [10.000, 12.500) = 79 
    [12.500, 15.000) = 71 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 73 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 23 

  Percentiles, ms/op:
      p(0.0000) =      0.673 ms/op
     p(50.0000) =      3.551 ms/op
     p(90.0000) =      4.227 ms/op
     p(95.0000) =      4.563 ms/op
     p(99.0000) =      5.890 ms/op
     p(99.9000) =     11.624 ms/op
     p(99.9900) =     24.543 ms/op
     p(99.9990) =     26.892 ms/op
     p(99.9999) =     27.034 ms/op
    p(100.0000) =     27.034 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.124 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.768 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.536 ±(99.9%) 0.009 ms/op
Iteration   1: 3.512 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.817 ms/op
                 existUser·p0.50:   3.437 ms/op
                 existUser·p0.90:   4.227 ms/op
                 existUser·p0.95:   4.628 ms/op
                 existUser·p0.99:   6.250 ms/op
                 existUser·p0.999:  11.153 ms/op
                 existUser·p0.9999: 16.710 ms/op
                 existUser·p1.00:   20.349 ms/op

Iteration   2: 3.509 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.033 ms/op
                 existUser·p0.50:   3.441 ms/op
                 existUser·p0.90:   4.076 ms/op
                 existUser·p0.95:   4.456 ms/op
                 existUser·p0.99:   6.078 ms/op
                 existUser·p0.999:  9.110 ms/op
                 existUser·p0.9999: 17.560 ms/op
                 existUser·p1.00:   18.285 ms/op

Iteration   3: 3.500 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.855 ms/op
                 existUser·p0.50:   3.424 ms/op
                 existUser·p0.90:   4.080 ms/op
                 existUser·p0.95:   4.465 ms/op
                 existUser·p0.99:   5.934 ms/op
                 existUser·p0.999:  12.104 ms/op
                 existUser·p0.9999: 19.193 ms/op
                 existUser·p1.00:   19.595 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 273602
  mean =      3.507 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9261 
    [ 2.500,  5.000) = 257217 
    [ 5.000,  7.500) = 5849 
    [ 7.500, 10.000) = 910 
    [10.000, 12.500) = 148 
    [12.500, 15.000) = 104 
    [15.000, 17.500) = 77 
    [17.500, 20.000) = 35 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.817 ms/op
     p(50.0000) =      3.432 ms/op
     p(90.0000) =      4.125 ms/op
     p(95.0000) =      4.530 ms/op
     p(99.0000) =      6.070 ms/op
     p(99.9000) =     11.393 ms/op
     p(99.9900) =     18.184 ms/op
     p(99.9990) =     19.595 ms/op
     p(99.9999) =     20.349 ms/op
    p(100.0000) =     20.349 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.299 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.002 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.750 ±(99.9%) 0.009 ms/op
Iteration   1: 3.722 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.023 ms/op
                 getUser·p0.50:   3.629 ms/op
                 getUser·p0.90:   4.473 ms/op
                 getUser·p0.95:   4.776 ms/op
                 getUser·p0.99:   5.956 ms/op
                 getUser·p0.999:  10.886 ms/op
                 getUser·p0.9999: 16.640 ms/op
                 getUser·p1.00:   17.105 ms/op

Iteration   2: 3.668 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.143 ms/op
                 getUser·p0.50:   3.596 ms/op
                 getUser·p0.90:   4.309 ms/op
                 getUser·p0.95:   4.645 ms/op
                 getUser·p0.99:   5.636 ms/op
                 getUser·p0.999:  8.077 ms/op
                 getUser·p0.9999: 17.933 ms/op
                 getUser·p1.00:   18.481 ms/op

Iteration   3: 3.620 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.907 ms/op
                 getUser·p0.50:   3.572 ms/op
                 getUser·p0.90:   4.227 ms/op
                 getUser·p0.95:   4.571 ms/op
                 getUser·p0.99:   5.702 ms/op
                 getUser·p0.999:  9.470 ms/op
                 getUser·p0.9999: 19.988 ms/op
                 getUser·p1.00:   20.021 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 261441
  mean =      3.670 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5012 
    [ 2.500,  5.000) = 249577 
    [ 5.000,  7.500) = 5978 
    [ 7.500, 10.000) = 644 
    [10.000, 12.500) = 55 
    [12.500, 15.000) = 47 
    [15.000, 17.500) = 44 
    [17.500, 20.000) = 77 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.907 ms/op
     p(50.0000) =      3.596 ms/op
     p(90.0000) =      4.350 ms/op
     p(95.0000) =      4.678 ms/op
     p(99.0000) =      5.751 ms/op
     p(99.9000) =      9.650 ms/op
     p(99.9900) =     19.319 ms/op
     p(99.9990) =     20.021 ms/op
     p(99.9999) =     20.021 ms/op
    p(100.0000) =     20.021 ms/op


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
# Warmup Iteration   1: 7.197 ±(99.9%) 0.080 ms/op
# Warmup Iteration   2: 5.096 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.722 ±(99.9%) 0.014 ms/op
Iteration   1: 4.722 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.049 ms/op
                 listUser·p0.50:   4.522 ms/op
                 listUser·p0.90:   5.947 ms/op
                 listUser·p0.95:   6.775 ms/op
                 listUser·p0.99:   8.454 ms/op
                 listUser·p0.999:  15.736 ms/op
                 listUser·p0.9999: 24.190 ms/op
                 listUser·p1.00:   24.740 ms/op

Iteration   2: 4.769 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.141 ms/op
                 listUser·p0.50:   4.530 ms/op
                 listUser·p0.90:   6.193 ms/op
                 listUser·p0.95:   6.963 ms/op
                 listUser·p0.99:   8.471 ms/op
                 listUser·p0.999:  15.826 ms/op
                 listUser·p0.9999: 18.802 ms/op
                 listUser·p1.00:   19.366 ms/op

Iteration   3: 4.712 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.151 ms/op
                 listUser·p0.50:   4.506 ms/op
                 listUser·p0.90:   5.849 ms/op
                 listUser·p0.95:   6.824 ms/op
                 listUser·p0.99:   8.471 ms/op
                 listUser·p0.999:  19.661 ms/op
                 listUser·p0.9999: 29.800 ms/op
                 listUser·p1.00:   30.081 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 202607
  mean =      4.734 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 275 
    [ 2.500,  5.000) = 153727 
    [ 5.000,  7.500) = 43566 
    [ 7.500, 10.000) = 4280 
    [10.000, 12.500) = 411 
    [12.500, 15.000) = 66 
    [15.000, 17.500) = 115 
    [17.500, 20.000) = 97 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 10 
    [27.500, 30.000) = 26 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.049 ms/op
     p(50.0000) =      4.522 ms/op
     p(90.0000) =      6.013 ms/op
     p(95.0000) =      6.857 ms/op
     p(99.0000) =      8.471 ms/op
     p(99.9000) =     16.646 ms/op
     p(99.9900) =     27.779 ms/op
     p(99.9990) =     30.078 ms/op
     p(99.9999) =     30.081 ms/op
    p(100.0000) =     30.081 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.543 ± 0.838  ops/ms
ClientGrpc.existUser                       thrpt       3   9.486 ± 3.472  ops/ms
ClientGrpc.getUser                         thrpt       3   8.788 ± 0.651  ops/ms
ClientGrpc.listUser                        thrpt       3   6.839 ± 2.184  ops/ms
ClientGrpc.createUser                       avgt       3   3.691 ± 0.442   ms/op
ClientGrpc.existUser                        avgt       3   3.423 ± 0.077   ms/op
ClientGrpc.getUser                          avgt       3   3.613 ± 0.814   ms/op
ClientGrpc.listUser                         avgt       3   4.544 ± 2.656   ms/op
ClientGrpc.createUser                     sample  266510   3.603 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.673           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.551           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.227           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.563           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.890           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.624           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          24.543           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          27.034           ms/op
ClientGrpc.existUser                      sample  273602   3.507 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.817           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.432           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.125           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.530           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.070           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.393           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.184           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.349           ms/op
ClientGrpc.getUser                        sample  261441   3.670 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.907           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.596           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.350           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.678           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.751           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.650           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.319           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.021           ms/op
ClientGrpc.listUser                       sample  202607   4.734 ± 0.009   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.049           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.522           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.013           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.857           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.471           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.646           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          27.779           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          30.081           ms/op
