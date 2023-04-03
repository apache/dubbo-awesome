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
# Warmup Iteration   1: 3.347 ops/ms
# Warmup Iteration   2: 6.941 ops/ms
# Warmup Iteration   3: 8.461 ops/ms
Iteration   1: 8.342 ops/ms
Iteration   2: 8.574 ops/ms
Iteration   3: 8.568 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.495 ±(99.9%) 2.415 ops/ms [Average]
  (min, avg, max) = (8.342, 8.495, 8.574), stdev = 0.132
  CI (99.9%): [6.080, 10.910] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 6.064 ops/ms
# Warmup Iteration   2: 8.460 ops/ms
# Warmup Iteration   3: 8.760 ops/ms
Iteration   1: 8.820 ops/ms
Iteration   2: 9.018 ops/ms
Iteration   3: 8.996 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.945 ±(99.9%) 1.980 ops/ms [Average]
  (min, avg, max) = (8.820, 8.945, 9.018), stdev = 0.109
  CI (99.9%): [6.965, 10.925] (assumes normal distribution)


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
# Warmup Iteration   1: 5.399 ops/ms
# Warmup Iteration   2: 8.127 ops/ms
# Warmup Iteration   3: 8.435 ops/ms
Iteration   1: 8.312 ops/ms
Iteration   2: 8.718 ops/ms
Iteration   3: 8.707 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.579 ±(99.9%) 4.217 ops/ms [Average]
  (min, avg, max) = (8.312, 8.579, 8.718), stdev = 0.231
  CI (99.9%): [4.362, 12.796] (assumes normal distribution)


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
# Warmup Iteration   1: 4.471 ops/ms
# Warmup Iteration   2: 6.138 ops/ms
# Warmup Iteration   3: 6.793 ops/ms
Iteration   1: 6.941 ops/ms
Iteration   2: 6.822 ops/ms
Iteration   3: 6.872 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.879 ±(99.9%) 1.088 ops/ms [Average]
  (min, avg, max) = (6.822, 6.879, 6.941), stdev = 0.060
  CI (99.9%): [5.790, 7.967] (assumes normal distribution)


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
# Warmup Iteration   1: 5.301 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.879 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.851 ±(99.9%) 0.006 ms/op
Iteration   1: 3.776 ±(99.9%) 0.009 ms/op
Iteration   2: 3.721 ±(99.9%) 0.003 ms/op
Iteration   3: 3.680 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.726 ±(99.9%) 0.875 ms/op [Average]
  (min, avg, max) = (3.680, 3.726, 3.776), stdev = 0.048
  CI (99.9%): [2.851, 4.600] (assumes normal distribution)


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
# Warmup Iteration   1: 4.897 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.805 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.607 ±(99.9%) 0.002 ms/op
Iteration   1: 3.448 ±(99.9%) 0.004 ms/op
Iteration   2: 3.544 ±(99.9%) 0.003 ms/op
Iteration   3: 3.474 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.489 ±(99.9%) 0.910 ms/op [Average]
  (min, avg, max) = (3.448, 3.489, 3.544), stdev = 0.050
  CI (99.9%): [2.579, 4.399] (assumes normal distribution)


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
# Warmup Iteration   1: 5.325 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.824 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.714 ±(99.9%) 0.009 ms/op
Iteration   1: 3.682 ±(99.9%) 0.004 ms/op
Iteration   2: 3.658 ±(99.9%) 0.004 ms/op
Iteration   3: 3.760 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.700 ±(99.9%) 0.975 ms/op [Average]
  (min, avg, max) = (3.658, 3.700, 3.760), stdev = 0.053
  CI (99.9%): [2.725, 4.675] (assumes normal distribution)


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
# Warmup Iteration   1: 6.162 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 5.057 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 4.712 ±(99.9%) 0.028 ms/op
Iteration   1: 4.739 ±(99.9%) 0.026 ms/op
Iteration   2: 4.726 ±(99.9%) 0.014 ms/op
Iteration   3: 4.628 ±(99.9%) 0.027 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.698 ±(99.9%) 1.107 ms/op [Average]
  (min, avg, max) = (4.628, 4.698, 4.739), stdev = 0.061
  CI (99.9%): [3.590, 5.805] (assumes normal distribution)


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
# Warmup Iteration   1: 5.359 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 3.939 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.680 ±(99.9%) 0.009 ms/op
Iteration   1: 3.669 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.023 ms/op
                 createUser·p0.50:   3.604 ms/op
                 createUser·p0.90:   4.317 ms/op
                 createUser·p0.95:   4.653 ms/op
                 createUser·p0.99:   5.603 ms/op
                 createUser·p0.999:  11.092 ms/op
                 createUser·p0.9999: 15.796 ms/op
                 createUser·p1.00:   16.237 ms/op

Iteration   2: 3.726 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.011 ms/op
                 createUser·p0.50:   3.650 ms/op
                 createUser·p0.90:   4.440 ms/op
                 createUser·p0.95:   4.751 ms/op
                 createUser·p0.99:   5.865 ms/op
                 createUser·p0.999:  8.300 ms/op
                 createUser·p0.9999: 29.073 ms/op
                 createUser·p1.00:   29.524 ms/op

Iteration   3: 3.670 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.951 ms/op
                 createUser·p0.50:   3.613 ms/op
                 createUser·p0.90:   4.235 ms/op
                 createUser·p0.95:   4.489 ms/op
                 createUser·p0.99:   5.652 ms/op
                 createUser·p0.999:  13.559 ms/op
                 createUser·p0.9999: 28.882 ms/op
                 createUser·p1.00:   29.360 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 260227
  mean =      3.688 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3523 
    [ 2.500,  5.000) = 250448 
    [ 5.000,  7.500) = 5540 
    [ 7.500, 10.000) = 472 
    [10.000, 12.500) = 42 
    [12.500, 15.000) = 70 
    [15.000, 17.500) = 36 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 18 

  Percentiles, ms/op:
      p(0.0000) =      0.951 ms/op
     p(50.0000) =      3.621 ms/op
     p(90.0000) =      4.334 ms/op
     p(95.0000) =      4.637 ms/op
     p(99.0000) =      5.726 ms/op
     p(99.9000) =      9.672 ms/op
     p(99.9900) =     28.606 ms/op
     p(99.9990) =     29.419 ms/op
     p(99.9999) =     29.524 ms/op
    p(100.0000) =     29.524 ms/op


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
# Warmup Iteration   1: 4.971 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.912 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.438 ±(99.9%) 0.007 ms/op
Iteration   1: 3.459 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.740 ms/op
                 existUser·p0.50:   3.432 ms/op
                 existUser·p0.90:   3.969 ms/op
                 existUser·p0.95:   4.219 ms/op
                 existUser·p0.99:   5.338 ms/op
                 existUser·p0.999:  8.840 ms/op
                 existUser·p0.9999: 14.135 ms/op
                 existUser·p1.00:   14.352 ms/op

Iteration   2: 3.439 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.737 ms/op
                 existUser·p0.50:   3.400 ms/op
                 existUser·p0.90:   3.797 ms/op
                 existUser·p0.95:   3.928 ms/op
                 existUser·p0.99:   4.882 ms/op
                 existUser·p0.999:  12.521 ms/op
                 existUser·p0.9999: 27.483 ms/op
                 existUser·p1.00:   28.639 ms/op

Iteration   3: 3.486 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.969 ms/op
                 existUser·p0.50:   3.432 ms/op
                 existUser·p0.90:   3.953 ms/op
                 existUser·p0.95:   4.211 ms/op
                 existUser·p0.99:   5.554 ms/op
                 existUser·p0.999:  11.141 ms/op
                 existUser·p0.9999: 18.639 ms/op
                 existUser·p1.00:   18.842 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 277275
  mean =      3.461 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4947 
    [ 2.500,  5.000) = 268733 
    [ 5.000,  7.500) = 2873 
    [ 7.500, 10.000) = 406 
    [10.000, 12.500) = 125 
    [12.500, 15.000) = 63 
    [15.000, 17.500) = 61 
    [17.500, 20.000) = 35 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.737 ms/op
     p(50.0000) =      3.420 ms/op
     p(90.0000) =      3.899 ms/op
     p(95.0000) =      4.133 ms/op
     p(99.0000) =      5.300 ms/op
     p(99.9000) =     10.121 ms/op
     p(99.9900) =     24.454 ms/op
     p(99.9990) =     28.259 ms/op
     p(99.9999) =     28.639 ms/op
    p(100.0000) =     28.639 ms/op


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
# Warmup Iteration   1: 5.416 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.894 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.725 ±(99.9%) 0.009 ms/op
Iteration   1: 3.674 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.861 ms/op
                 getUser·p0.50:   3.613 ms/op
                 getUser·p0.90:   4.309 ms/op
                 getUser·p0.95:   4.661 ms/op
                 getUser·p0.99:   6.013 ms/op
                 getUser·p0.999:  12.920 ms/op
                 getUser·p0.9999: 14.829 ms/op
                 getUser·p1.00:   15.090 ms/op

Iteration   2: 3.684 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.773 ms/op
                 getUser·p0.50:   3.621 ms/op
                 getUser·p0.90:   4.317 ms/op
                 getUser·p0.95:   4.588 ms/op
                 getUser·p0.99:   5.677 ms/op
                 getUser·p0.999:  8.416 ms/op
                 getUser·p0.9999: 16.754 ms/op
                 getUser·p1.00:   16.974 ms/op

Iteration   3: 3.595 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.642 ms/op
                 getUser·p0.50:   3.551 ms/op
                 getUser·p0.90:   4.211 ms/op
                 getUser·p0.95:   4.555 ms/op
                 getUser·p0.99:   5.751 ms/op
                 getUser·p0.999:  8.537 ms/op
                 getUser·p0.9999: 24.248 ms/op
                 getUser·p1.00:   24.576 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 263019
  mean =      3.650 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6823 
    [ 2.500,  5.000) = 249719 
    [ 5.000,  7.500) = 5782 
    [ 7.500, 10.000) = 469 
    [10.000, 12.500) = 21 
    [12.500, 15.000) = 105 
    [15.000, 17.500) = 36 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.642 ms/op
     p(50.0000) =      3.596 ms/op
     p(90.0000) =      4.284 ms/op
     p(95.0000) =      4.604 ms/op
     p(99.0000) =      5.825 ms/op
     p(99.9000) =      8.847 ms/op
     p(99.9900) =     24.052 ms/op
     p(99.9990) =     24.445 ms/op
     p(99.9999) =     24.576 ms/op
    p(100.0000) =     24.576 ms/op


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
# Warmup Iteration   1: 6.662 ±(99.9%) 0.075 ms/op
# Warmup Iteration   2: 5.029 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.721 ±(99.9%) 0.014 ms/op
Iteration   1: 4.655 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.647 ms/op
                 listUser·p0.50:   4.489 ms/op
                 listUser·p0.90:   5.513 ms/op
                 listUser·p0.95:   6.578 ms/op
                 listUser·p0.99:   8.069 ms/op
                 listUser·p0.999:  14.833 ms/op
                 listUser·p0.9999: 18.186 ms/op
                 listUser·p1.00:   18.776 ms/op

Iteration   2: 4.665 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.616 ms/op
                 listUser·p0.50:   4.489 ms/op
                 listUser·p0.90:   5.554 ms/op
                 listUser·p0.95:   6.496 ms/op
                 listUser·p0.99:   8.118 ms/op
                 listUser·p0.999:  15.992 ms/op
                 listUser·p0.9999: 24.384 ms/op
                 listUser·p1.00:   24.740 ms/op

Iteration   3: 4.748 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.227 ms/op
                 listUser·p0.50:   4.547 ms/op
                 listUser·p0.90:   5.808 ms/op
                 listUser·p0.95:   6.865 ms/op
                 listUser·p0.99:   8.378 ms/op
                 listUser·p0.999:  22.161 ms/op
                 listUser·p0.9999: 30.212 ms/op
                 listUser·p1.00:   30.540 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 204592
  mean =      4.689 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 234 
    [ 2.500,  5.000) = 167034 
    [ 5.000,  7.500) = 33046 
    [ 7.500, 10.000) = 3595 
    [10.000, 12.500) = 294 
    [12.500, 15.000) = 78 
    [15.000, 17.500) = 148 
    [17.500, 20.000) = 51 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 58 
    [25.000, 27.500) = 8 
    [27.500, 30.000) = 23 
    [30.000, 32.500) = 9 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.227 ms/op
     p(50.0000) =      4.514 ms/op
     p(90.0000) =      5.628 ms/op
     p(95.0000) =      6.668 ms/op
     p(99.0000) =      8.184 ms/op
     p(99.9000) =     16.253 ms/op
     p(99.9900) =     28.869 ms/op
     p(99.9990) =     30.409 ms/op
     p(99.9999) =     30.540 ms/op
    p(100.0000) =     30.540 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.495 ± 2.415  ops/ms
ClientGrpc.existUser                       thrpt       3   8.945 ± 1.980  ops/ms
ClientGrpc.getUser                         thrpt       3   8.579 ± 4.217  ops/ms
ClientGrpc.listUser                        thrpt       3   6.879 ± 1.088  ops/ms
ClientGrpc.createUser                       avgt       3   3.726 ± 0.875   ms/op
ClientGrpc.existUser                        avgt       3   3.489 ± 0.910   ms/op
ClientGrpc.getUser                          avgt       3   3.700 ± 0.975   ms/op
ClientGrpc.listUser                         avgt       3   4.698 ± 1.107   ms/op
ClientGrpc.createUser                     sample  260227   3.688 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.951           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.621           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.334           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.637           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.726           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.672           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          28.606           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          29.524           ms/op
ClientGrpc.existUser                      sample  277275   3.461 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.737           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.420           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.899           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.133           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.300           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.121           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          24.454           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          28.639           ms/op
ClientGrpc.getUser                        sample  263019   3.650 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.642           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.596           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.284           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.604           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.825           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.847           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          24.052           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          24.576           ms/op
ClientGrpc.listUser                       sample  204592   4.689 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.227           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.514           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.628           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.668           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.184           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.253           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          28.869           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          30.540           ms/op
