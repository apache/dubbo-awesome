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
# Warmup Iteration   1: 3.371 ops/ms
# Warmup Iteration   2: 7.198 ops/ms
# Warmup Iteration   3: 8.365 ops/ms
Iteration   1: 8.852 ops/ms
Iteration   2: 8.743 ops/ms
Iteration   3: 8.904 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.833 ±(99.9%) 1.501 ops/ms [Average]
  (min, avg, max) = (8.743, 8.833, 8.904), stdev = 0.082
  CI (99.9%): [7.332, 10.334] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:04
# Fork: 1 of 1
# Warmup Iteration   1: 6.121 ops/ms
# Warmup Iteration   2: 8.763 ops/ms
# Warmup Iteration   3: 9.325 ops/ms
Iteration   1: 9.591 ops/ms
Iteration   2: 9.596 ops/ms
Iteration   3: 9.522 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.570 ±(99.9%) 0.750 ops/ms [Average]
  (min, avg, max) = (9.522, 9.570, 9.596), stdev = 0.041
  CI (99.9%): [8.820, 10.319] (assumes normal distribution)


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
# Warmup Iteration   1: 5.582 ops/ms
# Warmup Iteration   2: 8.316 ops/ms
# Warmup Iteration   3: 8.609 ops/ms
Iteration   1: 8.727 ops/ms
Iteration   2: 8.782 ops/ms
Iteration   3: 8.922 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.810 ±(99.9%) 1.835 ops/ms [Average]
  (min, avg, max) = (8.727, 8.810, 8.922), stdev = 0.101
  CI (99.9%): [6.975, 10.646] (assumes normal distribution)


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
# Warmup Iteration   1: 4.272 ops/ms
# Warmup Iteration   2: 6.186 ops/ms
# Warmup Iteration   3: 6.853 ops/ms
Iteration   1: 6.824 ops/ms
Iteration   2: 6.771 ops/ms
Iteration   3: 6.797 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.797 ±(99.9%) 0.484 ops/ms [Average]
  (min, avg, max) = (6.771, 6.797, 6.824), stdev = 0.027
  CI (99.9%): [6.314, 7.281] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 4.945 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.797 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.587 ±(99.9%) 0.002 ms/op
Iteration   1: 3.559 ±(99.9%) 0.004 ms/op
Iteration   2: 3.522 ±(99.9%) 0.005 ms/op
Iteration   3: 3.629 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.570 ±(99.9%) 0.983 ms/op [Average]
  (min, avg, max) = (3.522, 3.570, 3.629), stdev = 0.054
  CI (99.9%): [2.587, 4.553] (assumes normal distribution)


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
# Warmup Iteration   1: 4.870 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.533 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.402 ±(99.9%) 0.002 ms/op
Iteration   1: 3.331 ±(99.9%) 0.003 ms/op
Iteration   2: 3.433 ±(99.9%) 0.004 ms/op
Iteration   3: 3.405 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.390 ±(99.9%) 0.963 ms/op [Average]
  (min, avg, max) = (3.331, 3.390, 3.433), stdev = 0.053
  CI (99.9%): [2.427, 4.353] (assumes normal distribution)


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
# Warmup Iteration   1: 5.137 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.718 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.630 ±(99.9%) 0.003 ms/op
Iteration   1: 3.675 ±(99.9%) 0.004 ms/op
Iteration   2: 3.713 ±(99.9%) 0.003 ms/op
Iteration   3: 3.686 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.691 ±(99.9%) 0.359 ms/op [Average]
  (min, avg, max) = (3.675, 3.691, 3.713), stdev = 0.020
  CI (99.9%): [3.332, 4.050] (assumes normal distribution)


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
# Warmup Iteration   1: 5.820 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 5.042 ±(99.9%) 0.039 ms/op
# Warmup Iteration   3: 4.722 ±(99.9%) 0.011 ms/op
Iteration   1: 4.617 ±(99.9%) 0.014 ms/op
Iteration   2: 4.611 ±(99.9%) 0.010 ms/op
Iteration   3: 4.591 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.606 ±(99.9%) 0.253 ms/op [Average]
  (min, avg, max) = (4.591, 4.606, 4.617), stdev = 0.014
  CI (99.9%): [4.353, 4.859] (assumes normal distribution)


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
# Warmup Iteration   1: 5.182 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.873 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.735 ±(99.9%) 0.009 ms/op
Iteration   1: 3.562 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.795 ms/op
                 createUser·p0.50:   3.518 ms/op
                 createUser·p0.90:   4.202 ms/op
                 createUser·p0.95:   4.547 ms/op
                 createUser·p0.99:   5.702 ms/op
                 createUser·p0.999:  12.403 ms/op
                 createUser·p0.9999: 16.335 ms/op
                 createUser·p1.00:   16.695 ms/op

Iteration   2: 3.572 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.063 ms/op
                 createUser·p0.50:   3.518 ms/op
                 createUser·p0.90:   4.190 ms/op
                 createUser·p0.95:   4.432 ms/op
                 createUser·p0.99:   4.973 ms/op
                 createUser·p0.999:  9.190 ms/op
                 createUser·p0.9999: 16.172 ms/op
                 createUser·p1.00:   16.417 ms/op

Iteration   3: 3.635 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.122 ms/op
                 createUser·p0.50:   3.564 ms/op
                 createUser·p0.90:   4.268 ms/op
                 createUser·p0.95:   4.514 ms/op
                 createUser·p0.99:   5.472 ms/op
                 createUser·p0.999:  13.877 ms/op
                 createUser·p0.9999: 32.375 ms/op
                 createUser·p1.00:   32.670 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 267461
  mean =      3.589 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5323 
    [ 2.500,  5.000) = 257987 
    [ 5.000,  7.500) = 3376 
    [ 7.500, 10.000) = 480 
    [10.000, 12.500) = 21 
    [12.500, 15.000) = 141 
    [15.000, 17.500) = 69 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 60 
    [32.500, 35.000) = 4 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.795 ms/op
     p(50.0000) =      3.531 ms/op
     p(90.0000) =      4.227 ms/op
     p(95.0000) =      4.489 ms/op
     p(99.0000) =      5.349 ms/op
     p(99.9000) =     12.559 ms/op
     p(99.9900) =     31.957 ms/op
     p(99.9990) =     32.560 ms/op
     p(99.9999) =     32.670 ms/op
    p(100.0000) =     32.670 ms/op


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
# Warmup Iteration   1: 4.581 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.696 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.564 ±(99.9%) 0.008 ms/op
Iteration   1: 3.458 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.791 ms/op
                 existUser·p0.50:   3.437 ms/op
                 existUser·p0.90:   4.071 ms/op
                 existUser·p0.95:   4.366 ms/op
                 existUser·p0.99:   5.620 ms/op
                 existUser·p0.999:  9.046 ms/op
                 existUser·p0.9999: 14.512 ms/op
                 existUser·p1.00:   17.564 ms/op

Iteration   2: 3.487 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.874 ms/op
                 existUser·p0.50:   3.437 ms/op
                 existUser·p0.90:   4.190 ms/op
                 existUser·p0.95:   4.481 ms/op
                 existUser·p0.99:   5.218 ms/op
                 existUser·p0.999:  8.149 ms/op
                 existUser·p0.9999: 17.164 ms/op
                 existUser·p1.00:   17.465 ms/op

Iteration   3: 3.384 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.835 ms/op
                 existUser·p0.50:   3.375 ms/op
                 existUser·p0.90:   4.059 ms/op
                 existUser·p0.95:   4.424 ms/op
                 existUser·p0.99:   5.571 ms/op
                 existUser·p0.999:  13.107 ms/op
                 existUser·p0.9999: 18.567 ms/op
                 existUser·p1.00:   19.202 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 279034
  mean =      3.442 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 420 
    [ 1.250,  2.500) = 14890 
    [ 2.500,  3.750) = 197160 
    [ 3.750,  5.000) = 61914 
    [ 5.000,  6.250) = 3220 
    [ 6.250,  7.500) = 740 
    [ 7.500,  8.750) = 344 
    [ 8.750, 10.000) = 105 
    [10.000, 11.250) = 31 
    [11.250, 12.500) = 21 
    [12.500, 13.750) = 61 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 17 
    [16.250, 17.500) = 44 
    [17.500, 18.750) = 29 

  Percentiles, ms/op:
      p(0.0000) =      0.791 ms/op
     p(50.0000) =      3.416 ms/op
     p(90.0000) =      4.108 ms/op
     p(95.0000) =      4.432 ms/op
     p(99.0000) =      5.464 ms/op
     p(99.9000) =      9.486 ms/op
     p(99.9900) =     17.760 ms/op
     p(99.9990) =     19.085 ms/op
     p(99.9999) =     19.202 ms/op
    p(100.0000) =     19.202 ms/op


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
# Warmup Iteration   1: 5.372 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 3.807 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.676 ±(99.9%) 0.009 ms/op
Iteration   1: 3.618 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.954 ms/op
                 getUser·p0.50:   3.555 ms/op
                 getUser·p0.90:   4.284 ms/op
                 getUser·p0.95:   4.571 ms/op
                 getUser·p0.99:   5.548 ms/op
                 getUser·p0.999:  8.911 ms/op
                 getUser·p0.9999: 19.802 ms/op
                 getUser·p1.00:   20.185 ms/op

Iteration   2: 3.636 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.957 ms/op
                 getUser·p0.50:   3.564 ms/op
                 getUser·p0.90:   4.342 ms/op
                 getUser·p0.95:   4.612 ms/op
                 getUser·p0.99:   5.448 ms/op
                 getUser·p0.999:  11.422 ms/op
                 getUser·p0.9999: 16.709 ms/op
                 getUser·p1.00:   17.007 ms/op

Iteration   3: 3.519 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.854 ms/op
                 getUser·p0.50:   3.490 ms/op
                 getUser·p0.90:   4.092 ms/op
                 getUser·p0.95:   4.399 ms/op
                 getUser·p0.99:   5.399 ms/op
                 getUser·p0.999:  7.997 ms/op
                 getUser·p0.9999: 22.279 ms/op
                 getUser·p1.00:   23.691 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 267269
  mean =      3.590 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6505 
    [ 2.500,  5.000) = 255864 
    [ 5.000,  7.500) = 4292 
    [ 7.500, 10.000) = 342 
    [10.000, 12.500) = 105 
    [12.500, 15.000) = 33 
    [15.000, 17.500) = 43 
    [17.500, 20.000) = 49 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.854 ms/op
     p(50.0000) =      3.531 ms/op
     p(90.0000) =      4.252 ms/op
     p(95.0000) =      4.547 ms/op
     p(99.0000) =      5.472 ms/op
     p(99.9000) =      9.960 ms/op
     p(99.9900) =     21.636 ms/op
     p(99.9990) =     23.658 ms/op
     p(99.9999) =     23.691 ms/op
    p(100.0000) =     23.691 ms/op


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
# Warmup Iteration   1: 6.599 ±(99.9%) 0.072 ms/op
# Warmup Iteration   2: 5.023 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.652 ±(99.9%) 0.016 ms/op
Iteration   1: 4.643 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   0.820 ms/op
                 listUser·p0.50:   4.407 ms/op
                 listUser·p0.90:   5.997 ms/op
                 listUser·p0.95:   6.767 ms/op
                 listUser·p0.99:   8.733 ms/op
                 listUser·p0.999:  15.436 ms/op
                 listUser·p0.9999: 19.300 ms/op
                 listUser·p1.00:   19.857 ms/op

Iteration   2: 4.810 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.114 ms/op
                 listUser·p0.50:   4.571 ms/op
                 listUser·p0.90:   6.136 ms/op
                 listUser·p0.95:   6.824 ms/op
                 listUser·p0.99:   8.421 ms/op
                 listUser·p0.999:  17.629 ms/op
                 listUser·p0.9999: 20.634 ms/op
                 listUser·p1.00:   20.939 ms/op

Iteration   3: 4.692 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.225 ms/op
                 listUser·p0.50:   4.489 ms/op
                 listUser·p0.90:   5.890 ms/op
                 listUser·p0.95:   6.554 ms/op
                 listUser·p0.99:   8.118 ms/op
                 listUser·p0.999:  22.211 ms/op
                 listUser·p0.9999: 27.308 ms/op
                 listUser·p1.00:   27.558 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 203609
  mean =      4.714 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 584 
    [ 2.500,  5.000) = 151399 
    [ 5.000,  7.500) = 46863 
    [ 7.500, 10.000) = 3937 
    [10.000, 12.500) = 455 
    [12.500, 15.000) = 95 
    [15.000, 17.500) = 92 
    [17.500, 20.000) = 80 
    [20.000, 22.500) = 42 
    [22.500, 25.000) = 46 
    [25.000, 27.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      0.820 ms/op
     p(50.0000) =      4.489 ms/op
     p(90.0000) =      6.013 ms/op
     p(95.0000) =      6.726 ms/op
     p(99.0000) =      8.389 ms/op
     p(99.9000) =     16.908 ms/op
     p(99.9900) =     24.597 ms/op
     p(99.9990) =     27.557 ms/op
     p(99.9999) =     27.558 ms/op
    p(100.0000) =     27.558 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.833 ± 1.501  ops/ms
ClientGrpc.existUser                       thrpt       3   9.570 ± 0.750  ops/ms
ClientGrpc.getUser                         thrpt       3   8.810 ± 1.835  ops/ms
ClientGrpc.listUser                        thrpt       3   6.797 ± 0.484  ops/ms
ClientGrpc.createUser                       avgt       3   3.570 ± 0.983   ms/op
ClientGrpc.existUser                        avgt       3   3.390 ± 0.963   ms/op
ClientGrpc.getUser                          avgt       3   3.691 ± 0.359   ms/op
ClientGrpc.listUser                         avgt       3   4.606 ± 0.253   ms/op
ClientGrpc.createUser                     sample  267461   3.589 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.795           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.531           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.227           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.489           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.349           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.559           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          31.957           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          32.670           ms/op
ClientGrpc.existUser                      sample  279034   3.442 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.791           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.416           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.108           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.432           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.464           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.486           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.760           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.202           ms/op
ClientGrpc.getUser                        sample  267269   3.590 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.854           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.531           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.252           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.547           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.472           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.960           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.636           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.691           ms/op
ClientGrpc.listUser                       sample  203609   4.714 ± 0.009   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.820           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.489           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.013           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.726           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.389           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.908           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.597           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.558           ms/op
