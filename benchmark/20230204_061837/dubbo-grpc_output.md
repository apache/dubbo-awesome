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
# Warmup Iteration   1: 3.126 ops/ms
# Warmup Iteration   2: 6.714 ops/ms
# Warmup Iteration   3: 8.217 ops/ms
Iteration   1: 8.137 ops/ms
Iteration   2: 8.472 ops/ms
Iteration   3: 8.512 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.374 ±(99.9%) 3.751 ops/ms [Average]
  (min, avg, max) = (8.137, 8.374, 8.512), stdev = 0.206
  CI (99.9%): [4.622, 12.125] (assumes normal distribution)


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
# Warmup Iteration   1: 5.795 ops/ms
# Warmup Iteration   2: 8.741 ops/ms
# Warmup Iteration   3: 8.761 ops/ms
Iteration   1: 8.970 ops/ms
Iteration   2: 9.114 ops/ms
Iteration   3: 9.027 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.037 ±(99.9%) 1.326 ops/ms [Average]
  (min, avg, max) = (8.970, 9.037, 9.114), stdev = 0.073
  CI (99.9%): [7.711, 10.363] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 5.484 ops/ms
# Warmup Iteration   2: 8.320 ops/ms
# Warmup Iteration   3: 8.252 ops/ms
Iteration   1: 8.384 ops/ms
Iteration   2: 8.685 ops/ms
Iteration   3: 8.554 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.541 ±(99.9%) 2.753 ops/ms [Average]
  (min, avg, max) = (8.384, 8.541, 8.685), stdev = 0.151
  CI (99.9%): [5.787, 11.294] (assumes normal distribution)


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
# Warmup Iteration   1: 4.233 ops/ms
# Warmup Iteration   2: 6.316 ops/ms
# Warmup Iteration   3: 6.742 ops/ms
Iteration   1: 7.079 ops/ms
Iteration   2: 6.587 ops/ms
Iteration   3: 6.930 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.865 ±(99.9%) 4.604 ops/ms [Average]
  (min, avg, max) = (6.587, 6.865, 7.079), stdev = 0.252
  CI (99.9%): [2.262, 11.469] (assumes normal distribution)


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
# Warmup Iteration   1: 5.252 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.860 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.747 ±(99.9%) 0.016 ms/op
Iteration   1: 3.809 ±(99.9%) 0.002 ms/op
Iteration   2: 3.782 ±(99.9%) 0.003 ms/op
Iteration   3: 3.697 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.762 ±(99.9%) 1.066 ms/op [Average]
  (min, avg, max) = (3.697, 3.762, 3.809), stdev = 0.058
  CI (99.9%): [2.696, 4.828] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 5.052 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.587 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.559 ±(99.9%) 0.003 ms/op
Iteration   1: 3.724 ±(99.9%) 0.003 ms/op
Iteration   2: 3.614 ±(99.9%) 0.003 ms/op
Iteration   3: 3.450 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.596 ±(99.9%) 2.518 ms/op [Average]
  (min, avg, max) = (3.450, 3.596, 3.724), stdev = 0.138
  CI (99.9%): [1.078, 6.114] (assumes normal distribution)


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
# Warmup Iteration   1: 5.050 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.811 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.754 ±(99.9%) 0.002 ms/op
Iteration   1: 3.678 ±(99.9%) 0.004 ms/op
Iteration   2: 3.769 ±(99.9%) 0.004 ms/op
Iteration   3: 3.728 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.725 ±(99.9%) 0.835 ms/op [Average]
  (min, avg, max) = (3.678, 3.725, 3.769), stdev = 0.046
  CI (99.9%): [2.890, 4.561] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 6.650 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 4.888 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.695 ±(99.9%) 0.044 ms/op
Iteration   1: 4.776 ±(99.9%) 0.029 ms/op
Iteration   2: 4.785 ±(99.9%) 0.009 ms/op
Iteration   3: 4.719 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.760 ±(99.9%) 0.653 ms/op [Average]
  (min, avg, max) = (4.719, 4.760, 4.785), stdev = 0.036
  CI (99.9%): [4.107, 5.413] (assumes normal distribution)


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
# Warmup Iteration   1: 5.316 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.831 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.753 ±(99.9%) 0.009 ms/op
Iteration   1: 3.799 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.925 ms/op
                 createUser·p0.50:   3.768 ms/op
                 createUser·p0.90:   4.661 ms/op
                 createUser·p0.95:   4.899 ms/op
                 createUser·p0.99:   5.448 ms/op
                 createUser·p0.999:  11.630 ms/op
                 createUser·p0.9999: 15.294 ms/op
                 createUser·p1.00:   15.647 ms/op

Iteration   2: 3.753 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.159 ms/op
                 createUser·p0.50:   3.699 ms/op
                 createUser·p0.90:   4.538 ms/op
                 createUser·p0.95:   4.825 ms/op
                 createUser·p0.99:   5.505 ms/op
                 createUser·p0.999:  11.033 ms/op
                 createUser·p0.9999: 16.318 ms/op
                 createUser·p1.00:   16.679 ms/op

Iteration   3: 3.716 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.753 ms/op
                 createUser·p0.50:   3.674 ms/op
                 createUser·p0.90:   4.514 ms/op
                 createUser·p0.95:   4.768 ms/op
                 createUser·p0.99:   5.431 ms/op
                 createUser·p0.999:  16.389 ms/op
                 createUser·p0.9999: 22.774 ms/op
                 createUser·p1.00:   22.839 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 255555
  mean =      3.756 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6864 
    [ 2.500,  5.000) = 241070 
    [ 5.000,  7.500) = 6856 
    [ 7.500, 10.000) = 351 
    [10.000, 12.500) = 185 
    [12.500, 15.000) = 70 
    [15.000, 17.500) = 110 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.753 ms/op
     p(50.0000) =      3.711 ms/op
     p(90.0000) =      4.579 ms/op
     p(95.0000) =      4.833 ms/op
     p(99.0000) =      5.456 ms/op
     p(99.9000) =     12.026 ms/op
     p(99.9900) =     22.479 ms/op
     p(99.9990) =     22.807 ms/op
     p(99.9999) =     22.839 ms/op
    p(100.0000) =     22.839 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 5.308 ±(99.9%) 0.064 ms/op
# Warmup Iteration   2: 3.848 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.710 ±(99.9%) 0.009 ms/op
Iteration   1: 3.683 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.768 ms/op
                 existUser·p0.50:   3.641 ms/op
                 existUser·p0.90:   4.547 ms/op
                 existUser·p0.95:   4.801 ms/op
                 existUser·p0.99:   5.489 ms/op
                 existUser·p0.999:  11.275 ms/op
                 existUser·p0.9999: 16.394 ms/op
                 existUser·p1.00:   16.679 ms/op

Iteration   2: 3.607 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.034 ms/op
                 existUser·p0.50:   3.613 ms/op
                 existUser·p0.90:   4.522 ms/op
                 existUser·p0.95:   4.768 ms/op
                 existUser·p0.99:   5.399 ms/op
                 existUser·p0.999:  8.713 ms/op
                 existUser·p0.9999: 15.333 ms/op
                 existUser·p1.00:   17.367 ms/op

Iteration   3: 3.657 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.787 ms/op
                 existUser·p0.50:   3.621 ms/op
                 existUser·p0.90:   4.448 ms/op
                 existUser·p0.95:   4.678 ms/op
                 existUser·p0.99:   5.538 ms/op
                 existUser·p0.999:  12.419 ms/op
                 existUser·p0.9999: 17.899 ms/op
                 existUser·p1.00:   18.612 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 263142
  mean =      3.649 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 244 
    [ 1.250,  2.500) = 12771 
    [ 2.500,  3.750) = 137791 
    [ 3.750,  5.000) = 105722 
    [ 5.000,  6.250) = 5439 
    [ 6.250,  7.500) = 554 
    [ 7.500,  8.750) = 210 
    [ 8.750, 10.000) = 106 
    [10.000, 11.250) = 58 
    [11.250, 12.500) = 64 
    [12.500, 13.750) = 35 
    [13.750, 15.000) = 35 
    [15.000, 16.250) = 23 
    [16.250, 17.500) = 63 
    [17.500, 18.750) = 27 

  Percentiles, ms/op:
      p(0.0000) =      0.768 ms/op
     p(50.0000) =      3.625 ms/op
     p(90.0000) =      4.506 ms/op
     p(95.0000) =      4.751 ms/op
     p(99.0000) =      5.477 ms/op
     p(99.9000) =     10.891 ms/op
     p(99.9900) =     17.553 ms/op
     p(99.9990) =     18.088 ms/op
     p(99.9999) =     18.612 ms/op
    p(100.0000) =     18.612 ms/op


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
# Warmup Iteration   1: 5.198 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.875 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.808 ±(99.9%) 0.008 ms/op
Iteration   1: 3.866 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.027 ms/op
                 getUser·p0.50:   3.817 ms/op
                 getUser·p0.90:   4.751 ms/op
                 getUser·p0.95:   5.038 ms/op
                 getUser·p0.99:   5.821 ms/op
                 getUser·p0.999:  13.656 ms/op
                 getUser·p0.9999: 15.364 ms/op
                 getUser·p1.00:   18.317 ms/op

Iteration   2: 3.729 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.964 ms/op
                 getUser·p0.50:   3.699 ms/op
                 getUser·p0.90:   4.547 ms/op
                 getUser·p0.95:   4.792 ms/op
                 getUser·p0.99:   5.326 ms/op
                 getUser·p0.999:  9.417 ms/op
                 getUser·p0.9999: 15.185 ms/op
                 getUser·p1.00:   17.170 ms/op

Iteration   3: 3.818 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.937 ms/op
                 getUser·p0.50:   3.727 ms/op
                 getUser·p0.90:   4.678 ms/op
                 getUser·p0.95:   4.948 ms/op
                 getUser·p0.99:   5.734 ms/op
                 getUser·p0.999:  9.535 ms/op
                 getUser·p0.9999: 33.432 ms/op
                 getUser·p1.00:   34.013 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 252273
  mean =      3.803 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6826 
    [ 2.500,  5.000) = 235107 
    [ 5.000,  7.500) = 9680 
    [ 7.500, 10.000) = 342 
    [10.000, 12.500) = 70 
    [12.500, 15.000) = 159 
    [15.000, 17.500) = 49 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 8 
    [32.500, 35.000) = 24 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.937 ms/op
     p(50.0000) =      3.744 ms/op
     p(90.0000) =      4.661 ms/op
     p(95.0000) =      4.932 ms/op
     p(99.0000) =      5.652 ms/op
     p(99.9000) =     12.286 ms/op
     p(99.9900) =     32.473 ms/op
     p(99.9990) =     33.848 ms/op
     p(99.9999) =     34.013 ms/op
    p(100.0000) =     34.013 ms/op


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
# Warmup Iteration   1: 5.497 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 5.308 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.714 ±(99.9%) 0.014 ms/op
Iteration   1: 4.765 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   2.009 ms/op
                 listUser·p0.50:   4.530 ms/op
                 listUser·p0.90:   6.160 ms/op
                 listUser·p0.95:   6.825 ms/op
                 listUser·p0.99:   8.256 ms/op
                 listUser·p0.999:  13.434 ms/op
                 listUser·p0.9999: 16.567 ms/op
                 listUser·p1.00:   16.810 ms/op

Iteration   2: 4.646 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.511 ms/op
                 listUser·p0.50:   4.489 ms/op
                 listUser·p0.90:   5.587 ms/op
                 listUser·p0.95:   6.480 ms/op
                 listUser·p0.99:   8.271 ms/op
                 listUser·p0.999:  17.411 ms/op
                 listUser·p0.9999: 37.618 ms/op
                 listUser·p1.00:   38.076 ms/op

Iteration   3: 4.709 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.063 ms/op
                 listUser·p0.50:   4.522 ms/op
                 listUser·p0.90:   5.980 ms/op
                 listUser·p0.95:   6.619 ms/op
                 listUser·p0.99:   8.307 ms/op
                 listUser·p0.999:  18.907 ms/op
                 listUser·p0.9999: 22.944 ms/op
                 listUser·p1.00:   23.167 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 203848
  mean =      4.706 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 229 
    [ 2.500,  5.000) = 154358 
    [ 5.000,  7.500) = 44762 
    [ 7.500, 10.000) = 3935 
    [10.000, 12.500) = 219 
    [12.500, 15.000) = 108 
    [15.000, 17.500) = 79 
    [17.500, 20.000) = 63 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 10 
    [35.000, 37.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      1.063 ms/op
     p(50.0000) =      4.514 ms/op
     p(90.0000) =      5.947 ms/op
     p(95.0000) =      6.652 ms/op
     p(99.0000) =      8.274 ms/op
     p(99.9000) =     16.368 ms/op
     p(99.9900) =     32.801 ms/op
     p(99.9990) =     37.996 ms/op
     p(99.9999) =     38.076 ms/op
    p(100.0000) =     38.076 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.374 ± 3.751  ops/ms
ClientGrpc.existUser                       thrpt       3   9.037 ± 1.326  ops/ms
ClientGrpc.getUser                         thrpt       3   8.541 ± 2.753  ops/ms
ClientGrpc.listUser                        thrpt       3   6.865 ± 4.604  ops/ms
ClientGrpc.createUser                       avgt       3   3.762 ± 1.066   ms/op
ClientGrpc.existUser                        avgt       3   3.596 ± 2.518   ms/op
ClientGrpc.getUser                          avgt       3   3.725 ± 0.835   ms/op
ClientGrpc.listUser                         avgt       3   4.760 ± 0.653   ms/op
ClientGrpc.createUser                     sample  255555   3.756 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.753           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.711           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.579           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.833           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.456           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.026           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          22.479           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.839           ms/op
ClientGrpc.existUser                      sample  263142   3.649 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.768           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.625           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.506           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.751           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.477           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.891           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.553           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.612           ms/op
ClientGrpc.getUser                        sample  252273   3.803 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.937           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.744           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.661           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.932           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.652           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.286           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          32.473           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          34.013           ms/op
ClientGrpc.listUser                       sample  203848   4.706 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.063           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.514           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.947           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.652           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.274           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.368           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          32.801           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          38.076           ms/op
