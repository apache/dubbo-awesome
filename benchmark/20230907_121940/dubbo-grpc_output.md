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
# Warmup Iteration   1: 3.029 ops/ms
# Warmup Iteration   2: 7.370 ops/ms
# Warmup Iteration   3: 8.399 ops/ms
Iteration   1: 8.427 ops/ms
Iteration   2: 9.091 ops/ms
Iteration   3: 8.837 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.785 ±(99.9%) 6.112 ops/ms [Average]
  (min, avg, max) = (8.427, 8.785, 9.091), stdev = 0.335
  CI (99.9%): [2.673, 14.897] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:01
# Fork: 1 of 1
# Warmup Iteration   1: 5.090 ops/ms
# Warmup Iteration   2: 8.592 ops/ms
# Warmup Iteration   3: 8.393 ops/ms
Iteration   1: 8.391 ops/ms
Iteration   2: 9.519 ops/ms
Iteration   3: 8.987 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.966 ±(99.9%) 10.296 ops/ms [Average]
  (min, avg, max) = (8.391, 8.966, 9.519), stdev = 0.564
  CI (99.9%): [≈ 0, 19.262] (assumes normal distribution)


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
# Warmup Iteration   1: 4.720 ops/ms
# Warmup Iteration   2: 7.567 ops/ms
# Warmup Iteration   3: 7.670 ops/ms
Iteration   1: 7.710 ops/ms
Iteration   2: 7.933 ops/ms
Iteration   3: 7.895 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.846 ±(99.9%) 2.179 ops/ms [Average]
  (min, avg, max) = (7.710, 7.846, 7.933), stdev = 0.119
  CI (99.9%): [5.667, 10.025] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 3.935 ops/ms
# Warmup Iteration   2: 5.549 ops/ms
# Warmup Iteration   3: 5.958 ops/ms
Iteration   1: 6.185 ops/ms
Iteration   2: 6.223 ops/ms
Iteration   3: 6.111 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.173 ±(99.9%) 1.040 ops/ms [Average]
  (min, avg, max) = (6.111, 6.173, 6.223), stdev = 0.057
  CI (99.9%): [5.133, 7.214] (assumes normal distribution)


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
# Warmup Iteration   1: 5.764 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 4.390 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.104 ±(99.9%) 0.010 ms/op
Iteration   1: 3.953 ±(99.9%) 0.005 ms/op
Iteration   2: 4.023 ±(99.9%) 0.003 ms/op
Iteration   3: 4.157 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.044 ±(99.9%) 1.889 ms/op [Average]
  (min, avg, max) = (3.953, 4.044, 4.157), stdev = 0.104
  CI (99.9%): [2.154, 5.933] (assumes normal distribution)


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
# Warmup Iteration   1: 5.303 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.847 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 3.794 ±(99.9%) 0.004 ms/op
Iteration   1: 3.440 ±(99.9%) 0.002 ms/op
Iteration   2: 3.317 ±(99.9%) 0.003 ms/op
Iteration   3: 3.627 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.461 ±(99.9%) 2.854 ms/op [Average]
  (min, avg, max) = (3.317, 3.461, 3.627), stdev = 0.156
  CI (99.9%): [0.608, 6.315] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 5.679 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 4.259 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.162 ±(99.9%) 0.003 ms/op
Iteration   1: 3.953 ±(99.9%) 0.004 ms/op
Iteration   2: 3.906 ±(99.9%) 0.004 ms/op
Iteration   3: 3.933 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.930 ±(99.9%) 0.434 ms/op [Average]
  (min, avg, max) = (3.906, 3.930, 3.953), stdev = 0.024
  CI (99.9%): [3.497, 4.364] (assumes normal distribution)


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
# Warmup Iteration   1: 6.985 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 5.581 ±(99.9%) 0.033 ms/op
# Warmup Iteration   3: 5.092 ±(99.9%) 0.013 ms/op
Iteration   1: 5.064 ±(99.9%) 0.009 ms/op
Iteration   2: 4.802 ±(99.9%) 0.011 ms/op
Iteration   3: 4.860 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.909 ±(99.9%) 2.504 ms/op [Average]
  (min, avg, max) = (4.802, 4.909, 5.064), stdev = 0.137
  CI (99.9%): [2.405, 7.412] (assumes normal distribution)


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
# Warmup Iteration   1: 5.798 ±(99.9%) 0.061 ms/op
# Warmup Iteration   2: 4.055 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.812 ±(99.9%) 0.011 ms/op
Iteration   1: 3.798 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.734 ms/op
                 createUser·p0.50:   3.645 ms/op
                 createUser·p0.90:   4.768 ms/op
                 createUser·p0.95:   5.259 ms/op
                 createUser·p0.99:   7.784 ms/op
                 createUser·p0.999:  13.495 ms/op
                 createUser·p0.9999: 15.542 ms/op
                 createUser·p1.00:   15.794 ms/op

Iteration   2: 3.899 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.892 ms/op
                 createUser·p0.50:   3.760 ms/op
                 createUser·p0.90:   4.907 ms/op
                 createUser·p0.95:   5.341 ms/op
                 createUser·p0.99:   7.583 ms/op
                 createUser·p0.999:  13.828 ms/op
                 createUser·p0.9999: 19.300 ms/op
                 createUser·p1.00:   19.366 ms/op

Iteration   3: 3.891 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.827 ms/op
                 createUser·p0.50:   3.781 ms/op
                 createUser·p0.90:   4.891 ms/op
                 createUser·p0.95:   5.300 ms/op
                 createUser·p0.99:   6.726 ms/op
                 createUser·p0.999:  9.137 ms/op
                 createUser·p0.9999: 20.904 ms/op
                 createUser·p1.00:   22.872 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 248509
  mean =      3.862 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4735 
    [ 2.500,  5.000) = 224035 
    [ 5.000,  7.500) = 17471 
    [ 7.500, 10.000) = 1755 
    [10.000, 12.500) = 248 
    [12.500, 15.000) = 132 
    [15.000, 17.500) = 78 
    [17.500, 20.000) = 44 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.734 ms/op
     p(50.0000) =      3.727 ms/op
     p(90.0000) =      4.866 ms/op
     p(95.0000) =      5.300 ms/op
     p(99.0000) =      7.315 ms/op
     p(99.9000) =     12.853 ms/op
     p(99.9900) =     19.446 ms/op
     p(99.9990) =     22.200 ms/op
     p(99.9999) =     22.872 ms/op
    p(100.0000) =     22.872 ms/op


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
# Warmup Iteration   1: 5.093 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.842 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.614 ±(99.9%) 0.010 ms/op
Iteration   1: 3.800 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.976 ms/op
                 existUser·p0.50:   3.629 ms/op
                 existUser·p0.90:   4.817 ms/op
                 existUser·p0.95:   5.415 ms/op
                 existUser·p0.99:   8.110 ms/op
                 existUser·p0.999:  11.551 ms/op
                 existUser·p0.9999: 16.190 ms/op
                 existUser·p1.00:   16.728 ms/op

Iteration   2: 3.642 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.531 ms/op
                 existUser·p0.50:   3.510 ms/op
                 existUser·p0.90:   4.596 ms/op
                 existUser·p0.95:   5.112 ms/op
                 existUser·p0.99:   7.012 ms/op
                 existUser·p0.999:  11.731 ms/op
                 existUser·p0.9999: 17.971 ms/op
                 existUser·p1.00:   18.416 ms/op

Iteration   3: 3.479 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.843 ms/op
                 existUser·p0.50:   3.367 ms/op
                 existUser·p0.90:   4.252 ms/op
                 existUser·p0.95:   4.604 ms/op
                 existUser·p0.99:   6.463 ms/op
                 existUser·p0.999:  10.976 ms/op
                 existUser·p0.9999: 20.197 ms/op
                 existUser·p1.00:   20.840 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 264235
  mean =      3.636 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8960 
    [ 2.500,  5.000) = 241130 
    [ 5.000,  7.500) = 11698 
    [ 7.500, 10.000) = 1877 
    [10.000, 12.500) = 368 
    [12.500, 15.000) = 109 
    [15.000, 17.500) = 44 
    [17.500, 20.000) = 39 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.531 ms/op
     p(50.0000) =      3.494 ms/op
     p(90.0000) =      4.555 ms/op
     p(95.0000) =      5.054 ms/op
     p(99.0000) =      7.356 ms/op
     p(99.9000) =     11.338 ms/op
     p(99.9900) =     19.005 ms/op
     p(99.9990) =     20.646 ms/op
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
# Warmup Iteration   1: 5.331 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 3.901 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.810 ±(99.9%) 0.011 ms/op
Iteration   1: 3.680 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.728 ms/op
                 getUser·p0.50:   3.580 ms/op
                 getUser·p0.90:   4.702 ms/op
                 getUser·p0.95:   5.218 ms/op
                 getUser·p0.99:   7.193 ms/op
                 getUser·p0.999:  11.174 ms/op
                 getUser·p0.9999: 14.915 ms/op
                 getUser·p1.00:   15.319 ms/op

Iteration   2: 3.700 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.057 ms/op
                 getUser·p0.50:   3.596 ms/op
                 getUser·p0.90:   4.563 ms/op
                 getUser·p0.95:   4.948 ms/op
                 getUser·p0.99:   6.496 ms/op
                 getUser·p0.999:  10.276 ms/op
                 getUser·p0.9999: 17.084 ms/op
                 getUser·p1.00:   17.400 ms/op

Iteration   3: 3.680 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.797 ms/op
                 getUser·p0.50:   3.580 ms/op
                 getUser·p0.90:   4.612 ms/op
                 getUser·p0.95:   5.063 ms/op
                 getUser·p0.99:   7.160 ms/op
                 getUser·p0.999:  12.207 ms/op
                 getUser·p0.9999: 19.288 ms/op
                 getUser·p1.00:   20.120 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 260197
  mean =      3.687 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11409 
    [ 2.500,  5.000) = 234281 
    [ 5.000,  7.500) = 12519 
    [ 7.500, 10.000) = 1561 
    [10.000, 12.500) = 223 
    [12.500, 15.000) = 106 
    [15.000, 17.500) = 63 
    [17.500, 20.000) = 34 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.728 ms/op
     p(50.0000) =      3.584 ms/op
     p(90.0000) =      4.620 ms/op
     p(95.0000) =      5.079 ms/op
     p(99.0000) =      6.980 ms/op
     p(99.9000) =     11.010 ms/op
     p(99.9900) =     18.087 ms/op
     p(99.9990) =     19.850 ms/op
     p(99.9999) =     20.120 ms/op
    p(100.0000) =     20.120 ms/op


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
# Warmup Iteration   1: 6.319 ±(99.9%) 0.073 ms/op
# Warmup Iteration   2: 5.270 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.926 ±(99.9%) 0.018 ms/op
Iteration   1: 5.095 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.495 ms/op
                 listUser·p0.50:   4.760 ms/op
                 listUser·p0.90:   7.012 ms/op
                 listUser·p0.95:   7.897 ms/op
                 listUser·p0.99:   10.387 ms/op
                 listUser·p0.999:  18.292 ms/op
                 listUser·p0.9999: 23.640 ms/op
                 listUser·p1.00:   24.052 ms/op

Iteration   2: 5.416 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.423 ms/op
                 listUser·p0.50:   5.030 ms/op
                 listUser·p0.90:   7.283 ms/op
                 listUser·p0.95:   8.356 ms/op
                 listUser·p0.99:   10.994 ms/op
                 listUser·p0.999:  21.460 ms/op
                 listUser·p0.9999: 23.828 ms/op
                 listUser·p1.00:   24.117 ms/op

Iteration   3: 5.447 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   1.178 ms/op
                 listUser·p0.50:   5.046 ms/op
                 listUser·p0.90:   7.430 ms/op
                 listUser·p0.95:   8.405 ms/op
                 listUser·p0.99:   11.125 ms/op
                 listUser·p0.999:  21.663 ms/op
                 listUser·p0.9999: 27.312 ms/op
                 listUser·p1.00:   27.918 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 180570
  mean =      5.314 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 608 
    [ 2.500,  5.000) = 93375 
    [ 5.000,  7.500) = 71777 
    [ 7.500, 10.000) = 12019 
    [10.000, 12.500) = 1900 
    [12.500, 15.000) = 494 
    [15.000, 17.500) = 101 
    [17.500, 20.000) = 81 
    [20.000, 22.500) = 120 
    [22.500, 25.000) = 63 
    [25.000, 27.500) = 28 

  Percentiles, ms/op:
      p(0.0000) =      1.178 ms/op
     p(50.0000) =      4.948 ms/op
     p(90.0000) =      7.242 ms/op
     p(95.0000) =      8.233 ms/op
     p(99.0000) =     10.846 ms/op
     p(99.9000) =     21.149 ms/op
     p(99.9900) =     26.147 ms/op
     p(99.9990) =     27.813 ms/op
     p(99.9999) =     27.918 ms/op
    p(100.0000) =     27.918 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score    Error   Units
ClientGrpc.createUser                      thrpt       3   8.785 ±  6.112  ops/ms
ClientGrpc.existUser                       thrpt       3   8.966 ± 10.296  ops/ms
ClientGrpc.getUser                         thrpt       3   7.846 ±  2.179  ops/ms
ClientGrpc.listUser                        thrpt       3   6.173 ±  1.040  ops/ms
ClientGrpc.createUser                       avgt       3   4.044 ±  1.889   ms/op
ClientGrpc.existUser                        avgt       3   3.461 ±  2.854   ms/op
ClientGrpc.getUser                          avgt       3   3.930 ±  0.434   ms/op
ClientGrpc.listUser                         avgt       3   4.909 ±  2.504   ms/op
ClientGrpc.createUser                     sample  248509   3.862 ±  0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.734            ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.727            ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.866            ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.300            ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.315            ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.853            ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.446            ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.872            ms/op
ClientGrpc.existUser                      sample  264235   3.636 ±  0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.531            ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.494            ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.555            ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.054            ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.356            ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.338            ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.005            ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.840            ms/op
ClientGrpc.getUser                        sample  260197   3.687 ±  0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.728            ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.584            ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.620            ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.079            ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.980            ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.010            ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.087            ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.120            ms/op
ClientGrpc.listUser                       sample  180570   5.314 ±  0.013   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.178            ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.948            ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.242            ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.233            ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.846            ms/op
ClientGrpc.listUser:listUser·p0.999       sample          21.149            ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          26.147            ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.918            ms/op
