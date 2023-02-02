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
# Warmup Iteration   1: 3.302 ops/ms
# Warmup Iteration   2: 7.066 ops/ms
# Warmup Iteration   3: 8.252 ops/ms
Iteration   1: 8.359 ops/ms
Iteration   2: 8.304 ops/ms
Iteration   3: 8.240 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.301 ±(99.9%) 1.080 ops/ms [Average]
  (min, avg, max) = (8.240, 8.301, 8.359), stdev = 0.059
  CI (99.9%): [7.221, 9.381] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:01
# Fork: 1 of 1
# Warmup Iteration   1: 5.905 ops/ms
# Warmup Iteration   2: 8.396 ops/ms
# Warmup Iteration   3: 8.473 ops/ms
Iteration   1: 8.623 ops/ms
Iteration   2: 8.817 ops/ms
Iteration   3: 8.695 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.712 ±(99.9%) 1.790 ops/ms [Average]
  (min, avg, max) = (8.623, 8.712, 8.817), stdev = 0.098
  CI (99.9%): [6.921, 10.502] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 5.297 ops/ms
# Warmup Iteration   2: 7.927 ops/ms
# Warmup Iteration   3: 8.195 ops/ms
Iteration   1: 8.358 ops/ms
Iteration   2: 8.198 ops/ms
Iteration   3: 8.235 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.264 ±(99.9%) 1.530 ops/ms [Average]
  (min, avg, max) = (8.198, 8.264, 8.358), stdev = 0.084
  CI (99.9%): [6.733, 9.794] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 4.755 ops/ms
# Warmup Iteration   2: 6.214 ops/ms
# Warmup Iteration   3: 6.639 ops/ms
Iteration   1: 6.828 ops/ms
Iteration   2: 6.647 ops/ms
Iteration   3: 6.876 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.784 ±(99.9%) 2.208 ops/ms [Average]
  (min, avg, max) = (6.647, 6.784, 6.876), stdev = 0.121
  CI (99.9%): [4.576, 8.992] (assumes normal distribution)


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
# Warmup Iteration   1: 5.397 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 4.115 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.816 ±(99.9%) 0.005 ms/op
Iteration   1: 3.972 ±(99.9%) 0.002 ms/op
Iteration   2: 3.831 ±(99.9%) 0.004 ms/op
Iteration   3: 3.909 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.904 ±(99.9%) 1.288 ms/op [Average]
  (min, avg, max) = (3.831, 3.904, 3.972), stdev = 0.071
  CI (99.9%): [2.617, 5.192] (assumes normal distribution)


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
# Warmup Iteration   1: 5.096 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.776 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.592 ±(99.9%) 0.005 ms/op
Iteration   1: 3.759 ±(99.9%) 0.002 ms/op
Iteration   2: 3.687 ±(99.9%) 0.003 ms/op
Iteration   3: 3.650 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.699 ±(99.9%) 1.010 ms/op [Average]
  (min, avg, max) = (3.650, 3.699, 3.759), stdev = 0.055
  CI (99.9%): [2.688, 4.709] (assumes normal distribution)


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
# Warmup Iteration   1: 5.270 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 4.026 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.744 ±(99.9%) 0.005 ms/op
Iteration   1: 3.748 ±(99.9%) 0.003 ms/op
Iteration   2: 3.943 ±(99.9%) 0.004 ms/op
Iteration   3: 3.982 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.891 ±(99.9%) 2.291 ms/op [Average]
  (min, avg, max) = (3.748, 3.891, 3.982), stdev = 0.126
  CI (99.9%): [1.600, 6.182] (assumes normal distribution)


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
# Warmup Iteration   1: 5.930 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.864 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.898 ±(99.9%) 0.027 ms/op
Iteration   1: 4.775 ±(99.9%) 0.010 ms/op
Iteration   2: 4.795 ±(99.9%) 0.025 ms/op
Iteration   3: 4.670 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.747 ±(99.9%) 1.224 ms/op [Average]
  (min, avg, max) = (4.670, 4.747, 4.795), stdev = 0.067
  CI (99.9%): [3.523, 5.971] (assumes normal distribution)


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
# Warmup Iteration   1: 5.194 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 3.871 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.858 ±(99.9%) 0.010 ms/op
Iteration   1: 3.674 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.456 ms/op
                 createUser·p0.50:   3.658 ms/op
                 createUser·p0.90:   4.325 ms/op
                 createUser·p0.95:   4.637 ms/op
                 createUser·p0.99:   5.620 ms/op
                 createUser·p0.999:  7.724 ms/op
                 createUser·p0.9999: 14.519 ms/op
                 createUser·p1.00:   14.795 ms/op

Iteration   2: 3.721 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.605 ms/op
                 createUser·p0.50:   3.690 ms/op
                 createUser·p0.90:   4.432 ms/op
                 createUser·p0.95:   4.694 ms/op
                 createUser·p0.99:   5.153 ms/op
                 createUser·p0.999:  8.816 ms/op
                 createUser·p0.9999: 15.657 ms/op
                 createUser·p1.00:   17.236 ms/op

Iteration   3: 3.785 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.335 ms/op
                 createUser·p0.50:   3.719 ms/op
                 createUser·p0.90:   4.604 ms/op
                 createUser·p0.95:   4.882 ms/op
                 createUser·p0.99:   5.767 ms/op
                 createUser·p0.999:  14.849 ms/op
                 createUser·p0.9999: 20.152 ms/op
                 createUser·p1.00:   20.316 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 257741
  mean =      3.726 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6425 
    [ 2.500,  5.000) = 244510 
    [ 5.000,  7.500) = 6187 
    [ 7.500, 10.000) = 409 
    [10.000, 12.500) = 18 
    [12.500, 15.000) = 102 
    [15.000, 17.500) = 63 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.335 ms/op
     p(50.0000) =      3.686 ms/op
     p(90.0000) =      4.456 ms/op
     p(95.0000) =      4.760 ms/op
     p(99.0000) =      5.464 ms/op
     p(99.9000) =      9.388 ms/op
     p(99.9900) =     19.020 ms/op
     p(99.9990) =     20.297 ms/op
     p(99.9999) =     20.316 ms/op
    p(100.0000) =     20.316 ms/op


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
# Warmup Iteration   1: 5.313 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 3.900 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.631 ±(99.9%) 0.008 ms/op
Iteration   1: 3.623 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.812 ms/op
                 existUser·p0.50:   3.604 ms/op
                 existUser·p0.90:   4.432 ms/op
                 existUser·p0.95:   4.661 ms/op
                 existUser·p0.99:   5.212 ms/op
                 existUser·p0.999:  7.656 ms/op
                 existUser·p0.9999: 15.382 ms/op
                 existUser·p1.00:   15.892 ms/op

Iteration   2: 3.686 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.995 ms/op
                 existUser·p0.50:   3.682 ms/op
                 existUser·p0.90:   4.489 ms/op
                 existUser·p0.95:   4.694 ms/op
                 existUser·p0.99:   5.120 ms/op
                 existUser·p0.999:  7.558 ms/op
                 existUser·p0.9999: 15.925 ms/op
                 existUser·p1.00:   17.007 ms/op

Iteration   3: 3.561 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.826 ms/op
                 existUser·p0.50:   3.527 ms/op
                 existUser·p0.90:   4.350 ms/op
                 existUser·p0.95:   4.563 ms/op
                 existUser·p0.99:   5.101 ms/op
                 existUser·p0.999:  16.466 ms/op
                 existUser·p0.9999: 19.857 ms/op
                 existUser·p1.00:   20.218 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 264906
  mean =      3.622 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11728 
    [ 2.500,  5.000) = 249436 
    [ 5.000,  7.500) = 3198 
    [ 7.500, 10.000) = 272 
    [10.000, 12.500) = 92 
    [12.500, 15.000) = 35 
    [15.000, 17.500) = 104 
    [17.500, 20.000) = 39 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.812 ms/op
     p(50.0000) =      3.600 ms/op
     p(90.0000) =      4.432 ms/op
     p(95.0000) =      4.645 ms/op
     p(99.0000) =      5.145 ms/op
     p(99.9000) =     10.110 ms/op
     p(99.9900) =     19.432 ms/op
     p(99.9990) =     20.069 ms/op
     p(99.9999) =     20.218 ms/op
    p(100.0000) =     20.218 ms/op


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
# Warmup Iteration   1: 5.100 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.924 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.822 ±(99.9%) 0.008 ms/op
Iteration   1: 3.691 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.873 ms/op
                 getUser·p0.50:   3.650 ms/op
                 getUser·p0.90:   4.301 ms/op
                 getUser·p0.95:   4.637 ms/op
                 getUser·p0.99:   5.849 ms/op
                 getUser·p0.999:  12.211 ms/op
                 getUser·p0.9999: 17.706 ms/op
                 getUser·p1.00:   17.990 ms/op

Iteration   2: 3.798 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.891 ms/op
                 getUser·p0.50:   3.756 ms/op
                 getUser·p0.90:   4.620 ms/op
                 getUser·p0.95:   4.882 ms/op
                 getUser·p0.99:   5.652 ms/op
                 getUser·p0.999:  8.430 ms/op
                 getUser·p0.9999: 15.282 ms/op
                 getUser·p1.00:   17.105 ms/op

Iteration   3: 3.816 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.854 ms/op
                 getUser·p0.50:   3.740 ms/op
                 getUser·p0.90:   4.620 ms/op
                 getUser·p0.95:   4.874 ms/op
                 getUser·p0.99:   5.489 ms/op
                 getUser·p0.999:  8.321 ms/op
                 getUser·p0.9999: 23.089 ms/op
                 getUser·p1.00:   23.495 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 254698
  mean =      3.767 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5930 
    [ 2.500,  5.000) = 240532 
    [ 5.000,  7.500) = 7575 
    [ 7.500, 10.000) = 442 
    [10.000, 12.500) = 42 
    [12.500, 15.000) = 78 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 35 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.854 ms/op
     p(50.0000) =      3.711 ms/op
     p(90.0000) =      4.547 ms/op
     p(95.0000) =      4.833 ms/op
     p(99.0000) =      5.652 ms/op
     p(99.9000) =      9.595 ms/op
     p(99.9900) =     21.939 ms/op
     p(99.9990) =     23.411 ms/op
     p(99.9999) =     23.495 ms/op
    p(100.0000) =     23.495 ms/op


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
# Warmup Iteration   1: 5.862 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 5.048 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.726 ±(99.9%) 0.013 ms/op
Iteration   1: 4.858 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.833 ms/op
                 listUser·p0.50:   4.645 ms/op
                 listUser·p0.90:   6.062 ms/op
                 listUser·p0.95:   6.783 ms/op
                 listUser·p0.99:   8.634 ms/op
                 listUser·p0.999:  20.120 ms/op
                 listUser·p0.9999: 23.620 ms/op
                 listUser·p1.00:   24.412 ms/op

Iteration   2: 4.748 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.208 ms/op
                 listUser·p0.50:   4.571 ms/op
                 listUser·p0.90:   5.841 ms/op
                 listUser·p0.95:   6.554 ms/op
                 listUser·p0.99:   8.195 ms/op
                 listUser·p0.999:  15.978 ms/op
                 listUser·p0.9999: 21.480 ms/op
                 listUser·p1.00:   21.823 ms/op

Iteration   3: 4.842 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.393 ms/op
                 listUser·p0.50:   4.645 ms/op
                 listUser·p0.90:   6.119 ms/op
                 listUser·p0.95:   6.717 ms/op
                 listUser·p0.99:   8.197 ms/op
                 listUser·p0.999:  19.364 ms/op
                 listUser·p0.9999: 21.036 ms/op
                 listUser·p1.00:   22.348 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 199337
  mean =      4.815 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 243 
    [ 2.500,  5.000) = 144538 
    [ 5.000,  7.500) = 49877 
    [ 7.500, 10.000) = 4068 
    [10.000, 12.500) = 250 
    [12.500, 15.000) = 65 
    [15.000, 17.500) = 82 
    [17.500, 20.000) = 100 
    [20.000, 22.500) = 83 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.208 ms/op
     p(50.0000) =      4.620 ms/op
     p(90.0000) =      6.021 ms/op
     p(95.0000) =      6.693 ms/op
     p(99.0000) =      8.364 ms/op
     p(99.9000) =     18.590 ms/op
     p(99.9900) =     23.007 ms/op
     p(99.9990) =     24.119 ms/op
     p(99.9999) =     24.412 ms/op
    p(100.0000) =     24.412 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.301 ± 1.080  ops/ms
ClientGrpc.existUser                       thrpt       3   8.712 ± 1.790  ops/ms
ClientGrpc.getUser                         thrpt       3   8.264 ± 1.530  ops/ms
ClientGrpc.listUser                        thrpt       3   6.784 ± 2.208  ops/ms
ClientGrpc.createUser                       avgt       3   3.904 ± 1.288   ms/op
ClientGrpc.existUser                        avgt       3   3.699 ± 1.010   ms/op
ClientGrpc.getUser                          avgt       3   3.891 ± 2.291   ms/op
ClientGrpc.listUser                         avgt       3   4.747 ± 1.224   ms/op
ClientGrpc.createUser                     sample  257741   3.726 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.335           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.686           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.456           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.760           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.464           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.388           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.020           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          20.316           ms/op
ClientGrpc.existUser                      sample  264906   3.622 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.812           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.600           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.432           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.645           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.145           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.110           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.432           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.218           ms/op
ClientGrpc.getUser                        sample  254698   3.767 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.854           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.711           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.547           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.833           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.652           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.595           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.939           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.495           ms/op
ClientGrpc.listUser                       sample  199337   4.815 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.208           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.620           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.021           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.693           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.364           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.590           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.007           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.412           ms/op
