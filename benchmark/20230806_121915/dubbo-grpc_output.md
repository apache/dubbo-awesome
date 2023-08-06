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
# Warmup Iteration   1: 2.885 ops/ms
# Warmup Iteration   2: 6.881 ops/ms
# Warmup Iteration   3: 8.188 ops/ms
Iteration   1: 8.443 ops/ms
Iteration   2: 8.507 ops/ms
Iteration   3: 8.744 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.565 ±(99.9%) 2.893 ops/ms [Average]
  (min, avg, max) = (8.443, 8.565, 8.744), stdev = 0.159
  CI (99.9%): [5.672, 11.457] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 5.701 ops/ms
# Warmup Iteration   2: 8.737 ops/ms
# Warmup Iteration   3: 8.987 ops/ms
Iteration   1: 9.399 ops/ms
Iteration   2: 9.428 ops/ms
Iteration   3: 9.414 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.413 ±(99.9%) 0.266 ops/ms [Average]
  (min, avg, max) = (9.399, 9.413, 9.428), stdev = 0.015
  CI (99.9%): [9.148, 9.679] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 5.514 ops/ms
# Warmup Iteration   2: 8.281 ops/ms
# Warmup Iteration   3: 8.422 ops/ms
Iteration   1: 8.700 ops/ms
Iteration   2: 8.901 ops/ms
Iteration   3: 8.934 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.845 ±(99.9%) 2.304 ops/ms [Average]
  (min, avg, max) = (8.700, 8.845, 8.934), stdev = 0.126
  CI (99.9%): [6.541, 11.149] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 4.366 ops/ms
# Warmup Iteration   2: 6.182 ops/ms
# Warmup Iteration   3: 6.197 ops/ms
Iteration   1: 6.522 ops/ms
Iteration   2: 6.626 ops/ms
Iteration   3: 6.652 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.600 ±(99.9%) 1.256 ops/ms [Average]
  (min, avg, max) = (6.522, 6.600, 6.652), stdev = 0.069
  CI (99.9%): [5.344, 7.856] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 5.441 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.941 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.882 ±(99.9%) 0.010 ms/op
Iteration   1: 3.806 ±(99.9%) 0.002 ms/op
Iteration   2: 3.636 ±(99.9%) 0.002 ms/op
Iteration   3: 3.757 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.733 ±(99.9%) 1.597 ms/op [Average]
  (min, avg, max) = (3.636, 3.733, 3.806), stdev = 0.088
  CI (99.9%): [2.136, 5.330] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 4.843 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.792 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.578 ±(99.9%) 0.003 ms/op
Iteration   1: 3.554 ±(99.9%) 0.002 ms/op
Iteration   2: 3.505 ±(99.9%) 0.003 ms/op
Iteration   3: 3.233 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.431 ±(99.9%) 3.157 ms/op [Average]
  (min, avg, max) = (3.233, 3.431, 3.554), stdev = 0.173
  CI (99.9%): [0.273, 6.588] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 5.601 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.915 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.770 ±(99.9%) 0.004 ms/op
Iteration   1: 3.606 ±(99.9%) 0.003 ms/op
Iteration   2: 3.912 ±(99.9%) 0.003 ms/op
Iteration   3: 3.677 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.732 ±(99.9%) 2.922 ms/op [Average]
  (min, avg, max) = (3.606, 3.732, 3.912), stdev = 0.160
  CI (99.9%): [0.809, 6.654] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 6.801 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 5.102 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.802 ±(99.9%) 0.027 ms/op
Iteration   1: 4.875 ±(99.9%) 0.020 ms/op
Iteration   2: 4.853 ±(99.9%) 0.022 ms/op
Iteration   3: 4.670 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.799 ±(99.9%) 2.049 ms/op [Average]
  (min, avg, max) = (4.670, 4.799, 4.875), stdev = 0.112
  CI (99.9%): [2.750, 6.848] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 5.540 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 4.064 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.923 ±(99.9%) 0.012 ms/op
Iteration   1: 3.696 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.948 ms/op
                 createUser·p0.50:   3.592 ms/op
                 createUser·p0.90:   4.686 ms/op
                 createUser·p0.95:   5.112 ms/op
                 createUser·p0.99:   6.234 ms/op
                 createUser·p0.999:  9.232 ms/op
                 createUser·p0.9999: 16.298 ms/op
                 createUser·p1.00:   17.334 ms/op

Iteration   2: 3.678 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.829 ms/op
                 createUser·p0.50:   3.596 ms/op
                 createUser·p0.90:   4.678 ms/op
                 createUser·p0.95:   5.071 ms/op
                 createUser·p0.99:   6.160 ms/op
                 createUser·p0.999:  11.645 ms/op
                 createUser·p0.9999: 18.271 ms/op
                 createUser·p1.00:   18.743 ms/op

Iteration   3: 3.701 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.925 ms/op
                 createUser·p0.50:   3.572 ms/op
                 createUser·p0.90:   4.702 ms/op
                 createUser·p0.95:   5.177 ms/op
                 createUser·p0.99:   6.693 ms/op
                 createUser·p0.999:  12.042 ms/op
                 createUser·p0.9999: 20.764 ms/op
                 createUser·p1.00:   21.496 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 260209
  mean =      3.692 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10313 
    [ 2.500,  5.000) = 234090 
    [ 5.000,  7.500) = 14664 
    [ 7.500, 10.000) = 787 
    [10.000, 12.500) = 154 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 79 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.829 ms/op
     p(50.0000) =      3.588 ms/op
     p(90.0000) =      4.686 ms/op
     p(95.0000) =      5.120 ms/op
     p(99.0000) =      6.324 ms/op
     p(99.9000) =     11.560 ms/op
     p(99.9900) =     19.758 ms/op
     p(99.9990) =     21.240 ms/op
     p(99.9999) =     21.496 ms/op
    p(100.0000) =     21.496 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 5.131 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.668 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.503 ±(99.9%) 0.009 ms/op
Iteration   1: 3.425 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.870 ms/op
                 existUser·p0.50:   3.351 ms/op
                 existUser·p0.90:   4.227 ms/op
                 existUser·p0.95:   4.555 ms/op
                 existUser·p0.99:   5.644 ms/op
                 existUser·p0.999:  9.431 ms/op
                 existUser·p0.9999: 16.597 ms/op
                 existUser·p1.00:   17.334 ms/op

Iteration   2: 3.469 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.128 ms/op
                 existUser·p0.50:   3.367 ms/op
                 existUser·p0.90:   4.243 ms/op
                 existUser·p0.95:   4.596 ms/op
                 existUser·p0.99:   5.775 ms/op
                 existUser·p0.999:  11.394 ms/op
                 existUser·p0.9999: 14.587 ms/op
                 existUser·p1.00:   15.892 ms/op

Iteration   3: 3.412 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.739 ms/op
                 existUser·p0.50:   3.314 ms/op
                 existUser·p0.90:   4.202 ms/op
                 existUser·p0.95:   4.563 ms/op
                 existUser·p0.99:   5.636 ms/op
                 existUser·p0.999:  10.715 ms/op
                 existUser·p0.9999: 20.730 ms/op
                 existUser·p1.00:   22.217 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 279453
  mean =      3.435 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12148 
    [ 2.500,  5.000) = 260638 
    [ 5.000,  7.500) = 5653 
    [ 7.500, 10.000) = 689 
    [10.000, 12.500) = 123 
    [12.500, 15.000) = 121 
    [15.000, 17.500) = 40 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.739 ms/op
     p(50.0000) =      3.346 ms/op
     p(90.0000) =      4.227 ms/op
     p(95.0000) =      4.571 ms/op
     p(99.0000) =      5.685 ms/op
     p(99.9000) =     10.682 ms/op
     p(99.9900) =     19.892 ms/op
     p(99.9990) =     21.988 ms/op
     p(99.9999) =     22.217 ms/op
    p(100.0000) =     22.217 ms/op


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
# Warmup Iteration   1: 5.556 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 3.940 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.631 ±(99.9%) 0.010 ms/op
Iteration   1: 3.629 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.831 ms/op
                 getUser·p0.50:   3.572 ms/op
                 getUser·p0.90:   4.620 ms/op
                 getUser·p0.95:   5.071 ms/op
                 getUser·p0.99:   6.406 ms/op
                 getUser·p0.999:  11.059 ms/op
                 getUser·p0.9999: 14.421 ms/op
                 getUser·p1.00:   17.629 ms/op

Iteration   2: 3.724 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.023 ms/op
                 getUser·p0.50:   3.596 ms/op
                 getUser·p0.90:   4.661 ms/op
                 getUser·p0.95:   5.095 ms/op
                 getUser·p0.99:   6.365 ms/op
                 getUser·p0.999:  11.832 ms/op
                 getUser·p0.9999: 19.530 ms/op
                 getUser·p1.00:   19.890 ms/op

Iteration   3: 3.658 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.727 ms/op
                 getUser·p0.50:   3.559 ms/op
                 getUser·p0.90:   4.588 ms/op
                 getUser·p0.95:   5.014 ms/op
                 getUser·p0.99:   6.562 ms/op
                 getUser·p0.999:  10.788 ms/op
                 getUser·p0.9999: 18.268 ms/op
                 getUser·p1.00:   18.743 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 261497
  mean =      3.670 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 134 
    [ 1.250,  2.500) = 11702 
    [ 2.500,  3.750) = 146068 
    [ 3.750,  5.000) = 89252 
    [ 5.000,  6.250) = 11315 
    [ 6.250,  7.500) = 1699 
    [ 7.500,  8.750) = 645 
    [ 8.750, 10.000) = 295 
    [10.000, 11.250) = 133 
    [11.250, 12.500) = 62 
    [12.500, 13.750) = 44 
    [13.750, 15.000) = 62 
    [15.000, 16.250) = 18 
    [16.250, 17.500) = 10 
    [17.500, 18.750) = 38 

  Percentiles, ms/op:
      p(0.0000) =      0.727 ms/op
     p(50.0000) =      3.576 ms/op
     p(90.0000) =      4.620 ms/op
     p(95.0000) =      5.063 ms/op
     p(99.0000) =      6.431 ms/op
     p(99.9000) =     11.158 ms/op
     p(99.9900) =     18.476 ms/op
     p(99.9990) =     19.772 ms/op
     p(99.9999) =     19.890 ms/op
    p(100.0000) =     19.890 ms/op


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
# Warmup Iteration   1: 7.647 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 5.071 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 5.050 ±(99.9%) 0.018 ms/op
Iteration   1: 5.121 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.686 ms/op
                 listUser·p0.50:   4.874 ms/op
                 listUser·p0.90:   6.636 ms/op
                 listUser·p0.95:   7.520 ms/op
                 listUser·p0.99:   9.732 ms/op
                 listUser·p0.999:  16.041 ms/op
                 listUser·p0.9999: 18.416 ms/op
                 listUser·p1.00:   20.447 ms/op

Iteration   2: 4.995 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.421 ms/op
                 listUser·p0.50:   4.768 ms/op
                 listUser·p0.90:   6.439 ms/op
                 listUser·p0.95:   7.242 ms/op
                 listUser·p0.99:   9.733 ms/op
                 listUser·p0.999:  17.957 ms/op
                 listUser·p0.9999: 19.889 ms/op
                 listUser·p1.00:   20.939 ms/op

Iteration   3: 4.730 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.018 ms/op
                 listUser·p0.50:   4.530 ms/op
                 listUser·p0.90:   5.980 ms/op
                 listUser·p0.95:   6.873 ms/op
                 listUser·p0.99:   8.946 ms/op
                 listUser·p0.999:  19.268 ms/op
                 listUser·p0.9999: 26.820 ms/op
                 listUser·p1.00:   27.623 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 194195
  mean =      4.943 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 484 
    [ 2.500,  5.000) = 120946 
    [ 5.000,  7.500) = 64991 
    [ 7.500, 10.000) = 6276 
    [10.000, 12.500) = 846 
    [12.500, 15.000) = 227 
    [15.000, 17.500) = 215 
    [17.500, 20.000) = 149 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 27 

  Percentiles, ms/op:
      p(0.0000) =      1.018 ms/op
     p(50.0000) =      4.710 ms/op
     p(90.0000) =      6.373 ms/op
     p(95.0000) =      7.225 ms/op
     p(99.0000) =      9.486 ms/op
     p(99.9000) =     17.695 ms/op
     p(99.9900) =     25.494 ms/op
     p(99.9990) =     27.500 ms/op
     p(99.9999) =     27.623 ms/op
    p(100.0000) =     27.623 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.565 ± 2.893  ops/ms
ClientGrpc.existUser                       thrpt       3   9.413 ± 0.266  ops/ms
ClientGrpc.getUser                         thrpt       3   8.845 ± 2.304  ops/ms
ClientGrpc.listUser                        thrpt       3   6.600 ± 1.256  ops/ms
ClientGrpc.createUser                       avgt       3   3.733 ± 1.597   ms/op
ClientGrpc.existUser                        avgt       3   3.431 ± 3.157   ms/op
ClientGrpc.getUser                          avgt       3   3.732 ± 2.922   ms/op
ClientGrpc.listUser                         avgt       3   4.799 ± 2.049   ms/op
ClientGrpc.createUser                     sample  260209   3.692 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.829           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.588           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.686           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.120           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.324           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.560           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.758           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.496           ms/op
ClientGrpc.existUser                      sample  279453   3.435 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.739           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.346           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.227           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.571           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.685           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.682           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.892           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.217           ms/op
ClientGrpc.getUser                        sample  261497   3.670 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.727           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.576           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.620           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.063           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.431           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.158           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.476           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.890           ms/op
ClientGrpc.listUser                       sample  194195   4.943 ± 0.010   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.018           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.710           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.373           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.225           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.486           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.695           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.494           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.623           ms/op
