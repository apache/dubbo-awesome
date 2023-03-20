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
# Warmup Iteration   1: 2.850 ops/ms
# Warmup Iteration   2: 6.768 ops/ms
# Warmup Iteration   3: 8.089 ops/ms
Iteration   1: 8.218 ops/ms
Iteration   2: 8.668 ops/ms
Iteration   3: 8.205 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.364 ±(99.9%) 4.807 ops/ms [Average]
  (min, avg, max) = (8.205, 8.364, 8.668), stdev = 0.264
  CI (99.9%): [3.556, 13.171] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 5.430 ops/ms
# Warmup Iteration   2: 7.949 ops/ms
# Warmup Iteration   3: 8.442 ops/ms
Iteration   1: 9.160 ops/ms
Iteration   2: 9.102 ops/ms
Iteration   3: 8.850 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.037 ±(99.9%) 3.009 ops/ms [Average]
  (min, avg, max) = (8.850, 9.037, 9.160), stdev = 0.165
  CI (99.9%): [6.028, 12.047] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 5.267 ops/ms
# Warmup Iteration   2: 7.479 ops/ms
# Warmup Iteration   3: 7.896 ops/ms
Iteration   1: 7.924 ops/ms
Iteration   2: 8.406 ops/ms
Iteration   3: 7.987 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.106 ±(99.9%) 4.774 ops/ms [Average]
  (min, avg, max) = (7.924, 8.106, 8.406), stdev = 0.262
  CI (99.9%): [3.332, 12.880] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 4.417 ops/ms
# Warmup Iteration   2: 5.848 ops/ms
# Warmup Iteration   3: 6.322 ops/ms
Iteration   1: 6.470 ops/ms
Iteration   2: 6.601 ops/ms
Iteration   3: 6.284 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.451 ±(99.9%) 2.906 ops/ms [Average]
  (min, avg, max) = (6.284, 6.451, 6.601), stdev = 0.159
  CI (99.9%): [3.545, 9.357] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.994 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 4.251 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.886 ±(99.9%) 0.005 ms/op
Iteration   1: 3.840 ±(99.9%) 0.006 ms/op
Iteration   2: 3.727 ±(99.9%) 0.004 ms/op
Iteration   3: 3.838 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.802 ±(99.9%) 1.175 ms/op [Average]
  (min, avg, max) = (3.727, 3.802, 3.840), stdev = 0.064
  CI (99.9%): [2.627, 4.976] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 5.134 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.941 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.715 ±(99.9%) 0.002 ms/op
Iteration   1: 3.788 ±(99.9%) 0.003 ms/op
Iteration   2: 3.671 ±(99.9%) 0.002 ms/op
Iteration   3: 3.747 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.735 ±(99.9%) 1.087 ms/op [Average]
  (min, avg, max) = (3.671, 3.735, 3.788), stdev = 0.060
  CI (99.9%): [2.648, 4.822] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 5.920 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.215 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 3.990 ±(99.9%) 0.003 ms/op
Iteration   1: 3.887 ±(99.9%) 0.002 ms/op
Iteration   2: 3.778 ±(99.9%) 0.003 ms/op
Iteration   3: 3.779 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.815 ±(99.9%) 1.145 ms/op [Average]
  (min, avg, max) = (3.778, 3.815, 3.887), stdev = 0.063
  CI (99.9%): [2.670, 4.960] (assumes normal distribution)


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
# Warmup Iteration   1: 6.649 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 5.334 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 4.974 ±(99.9%) 0.012 ms/op
Iteration   1: 4.815 ±(99.9%) 0.011 ms/op
Iteration   2: 4.785 ±(99.9%) 0.014 ms/op
Iteration   3: 4.942 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.847 ±(99.9%) 1.516 ms/op [Average]
  (min, avg, max) = (4.785, 4.847, 4.942), stdev = 0.083
  CI (99.9%): [3.331, 6.364] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 6.140 ±(99.9%) 0.073 ms/op
# Warmup Iteration   2: 4.317 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.040 ±(99.9%) 0.011 ms/op
Iteration   1: 3.947 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.071 ms/op
                 createUser·p0.50:   3.817 ms/op
                 createUser·p0.90:   4.833 ms/op
                 createUser·p0.95:   5.226 ms/op
                 createUser·p0.99:   6.570 ms/op
                 createUser·p0.999:  12.221 ms/op
                 createUser·p0.9999: 22.538 ms/op
                 createUser·p1.00:   23.855 ms/op

Iteration   2: 3.912 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.013 ms/op
                 createUser·p0.50:   3.793 ms/op
                 createUser·p0.90:   4.817 ms/op
                 createUser·p0.95:   5.194 ms/op
                 createUser·p0.99:   6.365 ms/op
                 createUser·p0.999:  11.309 ms/op
                 createUser·p0.9999: 21.850 ms/op
                 createUser·p1.00:   22.118 ms/op

Iteration   3: 4.024 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.903 ms/op
                 createUser·p0.50:   3.887 ms/op
                 createUser·p0.90:   4.907 ms/op
                 createUser·p0.95:   5.341 ms/op
                 createUser·p0.99:   6.668 ms/op
                 createUser·p0.999:  10.945 ms/op
                 createUser·p0.9999: 33.065 ms/op
                 createUser·p1.00:   33.620 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 242273
  mean =      3.961 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4512 
    [ 2.500,  5.000) = 219177 
    [ 5.000,  7.500) = 17408 
    [ 7.500, 10.000) = 748 
    [10.000, 12.500) = 215 
    [12.500, 15.000) = 53 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 97 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 2 
    [30.000, 32.500) = 14 
    [32.500, 35.000) = 16 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.903 ms/op
     p(50.0000) =      3.830 ms/op
     p(90.0000) =      4.850 ms/op
     p(95.0000) =      5.251 ms/op
     p(99.0000) =      6.529 ms/op
     p(99.9000) =     11.685 ms/op
     p(99.9900) =     31.074 ms/op
     p(99.9990) =     33.489 ms/op
     p(99.9999) =     33.620 ms/op
    p(100.0000) =     33.620 ms/op


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
# Warmup Iteration   1: 5.658 ±(99.9%) 0.063 ms/op
# Warmup Iteration   2: 3.931 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.968 ±(99.9%) 0.010 ms/op
Iteration   1: 3.700 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.806 ms/op
                 existUser·p0.50:   3.613 ms/op
                 existUser·p0.90:   4.399 ms/op
                 existUser·p0.95:   4.801 ms/op
                 existUser·p0.99:   6.226 ms/op
                 existUser·p0.999:  9.925 ms/op
                 existUser·p0.9999: 15.407 ms/op
                 existUser·p1.00:   15.679 ms/op

Iteration   2: 3.724 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.386 ms/op
                 existUser·p0.50:   3.613 ms/op
                 existUser·p0.90:   4.424 ms/op
                 existUser·p0.95:   4.850 ms/op
                 existUser·p0.99:   6.413 ms/op
                 existUser·p0.999:  10.354 ms/op
                 existUser·p0.9999: 25.231 ms/op
                 existUser·p1.00:   25.461 ms/op

Iteration   3: 3.721 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.016 ms/op
                 existUser·p0.50:   3.641 ms/op
                 existUser·p0.90:   4.473 ms/op
                 existUser·p0.95:   4.866 ms/op
                 existUser·p0.99:   6.169 ms/op
                 existUser·p0.999:  13.567 ms/op
                 existUser·p0.9999: 23.396 ms/op
                 existUser·p1.00:   23.626 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 258400
  mean =      3.715 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6062 
    [ 2.500,  5.000) = 242210 
    [ 5.000,  7.500) = 8931 
    [ 7.500, 10.000) = 769 
    [10.000, 12.500) = 218 
    [12.500, 15.000) = 65 
    [15.000, 17.500) = 79 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 53 
    [25.000, 27.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      0.386 ms/op
     p(50.0000) =      3.621 ms/op
     p(90.0000) =      4.432 ms/op
     p(95.0000) =      4.841 ms/op
     p(99.0000) =      6.242 ms/op
     p(99.9000) =     11.488 ms/op
     p(99.9900) =     24.592 ms/op
     p(99.9990) =     25.390 ms/op
     p(99.9999) =     25.461 ms/op
    p(100.0000) =     25.461 ms/op


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
# Warmup Iteration   1: 5.580 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 4.045 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.146 ±(99.9%) 0.012 ms/op
Iteration   1: 3.855 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.977 ms/op
                 getUser·p0.50:   3.785 ms/op
                 getUser·p0.90:   4.825 ms/op
                 getUser·p0.95:   5.194 ms/op
                 getUser·p0.99:   6.463 ms/op
                 getUser·p0.999:  11.191 ms/op
                 getUser·p0.9999: 15.855 ms/op
                 getUser·p1.00:   16.269 ms/op

Iteration   2: 3.847 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.031 ms/op
                 getUser·p0.50:   3.781 ms/op
                 getUser·p0.90:   4.645 ms/op
                 getUser·p0.95:   4.989 ms/op
                 getUser·p0.99:   6.013 ms/op
                 getUser·p0.999:  9.729 ms/op
                 getUser·p0.9999: 18.100 ms/op
                 getUser·p1.00:   18.579 ms/op

Iteration   3: 3.823 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.024 ms/op
                 getUser·p0.50:   3.744 ms/op
                 getUser·p0.90:   4.579 ms/op
                 getUser·p0.95:   4.923 ms/op
                 getUser·p0.99:   6.179 ms/op
                 getUser·p0.999:  10.469 ms/op
                 getUser·p0.9999: 19.853 ms/op
                 getUser·p1.00:   20.382 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 249884
  mean =      3.842 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8505 
    [ 2.500,  5.000) = 227820 
    [ 5.000,  7.500) = 12379 
    [ 7.500, 10.000) = 791 
    [10.000, 12.500) = 229 
    [12.500, 15.000) = 43 
    [15.000, 17.500) = 66 
    [17.500, 20.000) = 45 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.977 ms/op
     p(50.0000) =      3.768 ms/op
     p(90.0000) =      4.694 ms/op
     p(95.0000) =      5.046 ms/op
     p(99.0000) =      6.193 ms/op
     p(99.9000) =     10.897 ms/op
     p(99.9900) =     19.072 ms/op
     p(99.9990) =     20.218 ms/op
     p(99.9999) =     20.382 ms/op
    p(100.0000) =     20.382 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 6.632 ±(99.9%) 0.072 ms/op
# Warmup Iteration   2: 4.998 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.800 ±(99.9%) 0.016 ms/op
Iteration   1: 4.830 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.790 ms/op
                 listUser·p0.50:   4.604 ms/op
                 listUser·p0.90:   6.070 ms/op
                 listUser·p0.95:   6.963 ms/op
                 listUser·p0.99:   8.978 ms/op
                 listUser·p0.999:  16.434 ms/op
                 listUser·p0.9999: 18.952 ms/op
                 listUser·p1.00:   19.333 ms/op

Iteration   2: 4.781 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.845 ms/op
                 listUser·p0.50:   4.571 ms/op
                 listUser·p0.90:   6.005 ms/op
                 listUser·p0.95:   6.980 ms/op
                 listUser·p0.99:   8.454 ms/op
                 listUser·p0.999:  16.402 ms/op
                 listUser·p0.9999: 19.157 ms/op
                 listUser·p1.00:   21.430 ms/op

Iteration   3: 4.890 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.069 ms/op
                 listUser·p0.50:   4.604 ms/op
                 listUser·p0.90:   6.439 ms/op
                 listUser·p0.95:   7.389 ms/op
                 listUser·p0.99:   9.617 ms/op
                 listUser·p0.999:  21.463 ms/op
                 listUser·p0.9999: 34.895 ms/op
                 listUser·p1.00:   35.979 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 198612
  mean =      4.834 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 285 
    [ 2.500,  5.000) = 144756 
    [ 5.000,  7.500) = 46796 
    [ 7.500, 10.000) = 5737 
    [10.000, 12.500) = 590 
    [12.500, 15.000) = 133 
    [15.000, 17.500) = 111 
    [17.500, 20.000) = 109 
    [20.000, 22.500) = 47 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 29 
    [35.000, 37.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.069 ms/op
     p(50.0000) =      4.596 ms/op
     p(90.0000) =      6.169 ms/op
     p(95.0000) =      7.111 ms/op
     p(99.0000) =      8.962 ms/op
     p(99.9000) =     17.642 ms/op
     p(99.9900) =     34.481 ms/op
     p(99.9990) =     35.785 ms/op
     p(99.9999) =     35.979 ms/op
    p(100.0000) =     35.979 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.364 ± 4.807  ops/ms
ClientGrpc.existUser                       thrpt       3   9.037 ± 3.009  ops/ms
ClientGrpc.getUser                         thrpt       3   8.106 ± 4.774  ops/ms
ClientGrpc.listUser                        thrpt       3   6.451 ± 2.906  ops/ms
ClientGrpc.createUser                       avgt       3   3.802 ± 1.175   ms/op
ClientGrpc.existUser                        avgt       3   3.735 ± 1.087   ms/op
ClientGrpc.getUser                          avgt       3   3.815 ± 1.145   ms/op
ClientGrpc.listUser                         avgt       3   4.847 ± 1.516   ms/op
ClientGrpc.createUser                     sample  242273   3.961 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.903           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.830           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.850           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.251           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.529           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.685           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          31.074           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          33.620           ms/op
ClientGrpc.existUser                      sample  258400   3.715 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.386           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.621           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.432           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.841           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.242           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.488           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          24.592           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          25.461           ms/op
ClientGrpc.getUser                        sample  249884   3.842 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.977           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.768           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.694           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.046           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.193           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.897           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.072           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.382           ms/op
ClientGrpc.listUser                       sample  198612   4.834 ± 0.009   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.069           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.596           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.169           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.111           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.962           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.642           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          34.481           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          35.979           ms/op
