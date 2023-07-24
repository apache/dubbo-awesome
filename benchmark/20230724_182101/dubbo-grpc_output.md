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
# Warmup Iteration   1: 2.425 ops/ms
# Warmup Iteration   2: 5.377 ops/ms
# Warmup Iteration   3: 7.200 ops/ms
Iteration   1: 7.797 ops/ms
Iteration   2: 7.789 ops/ms
Iteration   3: 7.864 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.817 ±(99.9%) 0.749 ops/ms [Average]
  (min, avg, max) = (7.789, 7.817, 7.864), stdev = 0.041
  CI (99.9%): [7.068, 8.566] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.951 ops/ms
# Warmup Iteration   2: 7.249 ops/ms
# Warmup Iteration   3: 8.129 ops/ms
Iteration   1: 7.817 ops/ms
Iteration   2: 7.796 ops/ms
Iteration   3: 8.391 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.001 ±(99.9%) 6.166 ops/ms [Average]
  (min, avg, max) = (7.796, 8.001, 8.391), stdev = 0.338
  CI (99.9%): [1.835, 14.167] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 3.838 ops/ms
# Warmup Iteration   2: 6.899 ops/ms
# Warmup Iteration   3: 7.169 ops/ms
Iteration   1: 7.338 ops/ms
Iteration   2: 7.524 ops/ms
Iteration   3: 7.546 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.470 ±(99.9%) 2.088 ops/ms [Average]
  (min, avg, max) = (7.338, 7.470, 7.546), stdev = 0.114
  CI (99.9%): [5.381, 9.558] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.796 ops/ms
# Warmup Iteration   2: 5.203 ops/ms
# Warmup Iteration   3: 5.737 ops/ms
Iteration   1: 5.864 ops/ms
Iteration   2: 5.944 ops/ms
Iteration   3: 6.161 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.989 ±(99.9%) 2.807 ops/ms [Average]
  (min, avg, max) = (5.864, 5.989, 6.161), stdev = 0.154
  CI (99.9%): [3.183, 8.796] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.078 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 4.422 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.326 ±(99.9%) 0.005 ms/op
Iteration   1: 4.145 ±(99.9%) 0.003 ms/op
Iteration   2: 4.255 ±(99.9%) 0.003 ms/op
Iteration   3: 4.132 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.177 ±(99.9%) 1.236 ms/op [Average]
  (min, avg, max) = (4.132, 4.177, 4.255), stdev = 0.068
  CI (99.9%): [2.941, 5.413] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 5.860 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.055 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.923 ±(99.9%) 0.003 ms/op
Iteration   1: 3.885 ±(99.9%) 0.003 ms/op
Iteration   2: 3.793 ±(99.9%) 0.004 ms/op
Iteration   3: 3.875 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.851 ±(99.9%) 0.920 ms/op [Average]
  (min, avg, max) = (3.793, 3.851, 3.885), stdev = 0.050
  CI (99.9%): [2.931, 4.771] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 5.966 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.086 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.772 ±(99.9%) 0.003 ms/op
Iteration   1: 3.803 ±(99.9%) 0.002 ms/op
Iteration   2: 3.766 ±(99.9%) 0.004 ms/op
Iteration   3: 4.434 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.001 ±(99.9%) 6.844 ms/op [Average]
  (min, avg, max) = (3.766, 4.001, 4.434), stdev = 0.375
  CI (99.9%): [≈ 0, 10.846] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 8.575 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 6.112 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 5.326 ±(99.9%) 0.034 ms/op
Iteration   1: 4.950 ±(99.9%) 0.023 ms/op
Iteration   2: 5.238 ±(99.9%) 0.017 ms/op
Iteration   3: 5.870 ±(99.9%) 0.027 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.353 ±(99.9%) 8.589 ms/op [Average]
  (min, avg, max) = (4.950, 5.353, 5.870), stdev = 0.471
  CI (99.9%): [≈ 0, 13.942] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 6.759 ±(99.9%) 0.078 ms/op
# Warmup Iteration   2: 4.516 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.999 ±(99.9%) 0.013 ms/op
Iteration   1: 3.794 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.925 ms/op
                 createUser·p0.50:   3.695 ms/op
                 createUser·p0.90:   4.694 ms/op
                 createUser·p0.95:   5.145 ms/op
                 createUser·p0.99:   6.709 ms/op
                 createUser·p0.999:  14.315 ms/op
                 createUser·p0.9999: 22.123 ms/op
                 createUser·p1.00:   24.347 ms/op

Iteration   2: 4.032 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   0.908 ms/op
                 createUser·p0.50:   3.887 ms/op
                 createUser·p0.90:   5.014 ms/op
                 createUser·p0.95:   5.546 ms/op
                 createUser·p0.99:   7.660 ms/op
                 createUser·p0.999:  11.534 ms/op
                 createUser·p0.9999: 23.862 ms/op
                 createUser·p1.00:   24.445 ms/op

Iteration   3: 4.223 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   0.938 ms/op
                 createUser·p0.50:   4.080 ms/op
                 createUser·p0.90:   5.415 ms/op
                 createUser·p0.95:   6.021 ms/op
                 createUser·p0.99:   8.077 ms/op
                 createUser·p0.999:  12.260 ms/op
                 createUser·p0.9999: 24.211 ms/op
                 createUser·p1.00:   24.674 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 239315
  mean =      4.009 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7387 
    [ 2.500,  5.000) = 205626 
    [ 5.000,  7.500) = 23762 
    [ 7.500, 10.000) = 1939 
    [10.000, 12.500) = 357 
    [12.500, 15.000) = 49 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 48 
    [20.000, 22.500) = 60 
    [22.500, 25.000) = 58 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.908 ms/op
     p(50.0000) =      3.863 ms/op
     p(90.0000) =      5.071 ms/op
     p(95.0000) =      5.612 ms/op
     p(99.0000) =      7.602 ms/op
     p(99.9000) =     12.808 ms/op
     p(99.9900) =     23.953 ms/op
     p(99.9990) =     24.570 ms/op
     p(99.9999) =     24.674 ms/op
    p(100.0000) =     24.674 ms/op


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
# Warmup Iteration   1: 6.483 ±(99.9%) 0.077 ms/op
# Warmup Iteration   2: 4.197 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.266 ±(99.9%) 0.012 ms/op
Iteration   1: 3.771 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.748 ms/op
                 existUser·p0.50:   3.711 ms/op
                 existUser·p0.90:   4.645 ms/op
                 existUser·p0.95:   5.063 ms/op
                 existUser·p0.99:   6.398 ms/op
                 existUser·p0.999:  10.977 ms/op
                 existUser·p0.9999: 19.235 ms/op
                 existUser·p1.00:   20.742 ms/op

Iteration   2: 3.687 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.954 ms/op
                 existUser·p0.50:   3.576 ms/op
                 existUser·p0.90:   4.538 ms/op
                 existUser·p0.95:   4.973 ms/op
                 existUser·p0.99:   6.627 ms/op
                 existUser·p0.999:  12.687 ms/op
                 existUser·p0.9999: 19.147 ms/op
                 existUser·p1.00:   19.628 ms/op

Iteration   3: 3.814 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.830 ms/op
                 existUser·p0.50:   3.715 ms/op
                 existUser·p0.90:   4.751 ms/op
                 existUser·p0.95:   5.210 ms/op
                 existUser·p0.99:   6.521 ms/op
                 existUser·p0.999:  10.586 ms/op
                 existUser·p0.9999: 17.813 ms/op
                 existUser·p1.00:   18.121 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 255595
  mean =      3.757 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8637 
    [ 2.500,  5.000) = 232380 
    [ 5.000,  7.500) = 13279 
    [ 7.500, 10.000) = 851 
    [10.000, 12.500) = 280 
    [12.500, 15.000) = 40 
    [15.000, 17.500) = 52 
    [17.500, 20.000) = 69 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.748 ms/op
     p(50.0000) =      3.666 ms/op
     p(90.0000) =      4.653 ms/op
     p(95.0000) =      5.087 ms/op
     p(99.0000) =      6.521 ms/op
     p(99.9000) =     11.600 ms/op
     p(99.9900) =     18.987 ms/op
     p(99.9990) =     20.575 ms/op
     p(99.9999) =     20.742 ms/op
    p(100.0000) =     20.742 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 6.320 ±(99.9%) 0.082 ms/op
# Warmup Iteration   2: 4.633 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.378 ±(99.9%) 0.015 ms/op
Iteration   1: 4.420 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.210 ms/op
                 getUser·p0.50:   4.301 ms/op
                 getUser·p0.90:   5.554 ms/op
                 getUser·p0.95:   6.095 ms/op
                 getUser·p0.99:   8.421 ms/op
                 getUser·p0.999:  13.450 ms/op
                 getUser·p0.9999: 15.495 ms/op
                 getUser·p1.00:   16.171 ms/op

Iteration   2: 4.415 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.031 ms/op
                 getUser·p0.50:   4.309 ms/op
                 getUser·p0.90:   5.554 ms/op
                 getUser·p0.95:   6.136 ms/op
                 getUser·p0.99:   7.720 ms/op
                 getUser·p0.999:  17.302 ms/op
                 getUser·p0.9999: 28.081 ms/op
                 getUser·p1.00:   28.901 ms/op

Iteration   3: 4.393 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.010 ms/op
                 getUser·p0.50:   4.268 ms/op
                 getUser·p0.90:   5.439 ms/op
                 getUser·p0.95:   6.021 ms/op
                 getUser·p0.99:   8.210 ms/op
                 getUser·p0.999:  18.004 ms/op
                 getUser·p0.9999: 24.352 ms/op
                 getUser·p1.00:   24.510 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 217687
  mean =      4.409 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6403 
    [ 2.500,  5.000) = 168986 
    [ 5.000,  7.500) = 39287 
    [ 7.500, 10.000) = 2291 
    [10.000, 12.500) = 370 
    [12.500, 15.000) = 121 
    [15.000, 17.500) = 82 
    [17.500, 20.000) = 68 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 22 

  Percentiles, ms/op:
      p(0.0000) =      1.010 ms/op
     p(50.0000) =      4.293 ms/op
     p(90.0000) =      5.521 ms/op
     p(95.0000) =      6.087 ms/op
     p(99.0000) =      8.102 ms/op
     p(99.9000) =     15.041 ms/op
     p(99.9900) =     26.837 ms/op
     p(99.9990) =     28.791 ms/op
     p(99.9999) =     28.901 ms/op
    p(100.0000) =     28.901 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 8.231 ±(99.9%) 0.099 ms/op
# Warmup Iteration   2: 6.207 ±(99.9%) 0.032 ms/op
# Warmup Iteration   3: 5.478 ±(99.9%) 0.021 ms/op
Iteration   1: 5.693 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   2.017 ms/op
                 listUser·p0.50:   5.366 ms/op
                 listUser·p0.90:   7.692 ms/op
                 listUser·p0.95:   8.602 ms/op
                 listUser·p0.99:   10.764 ms/op
                 listUser·p0.999:  16.996 ms/op
                 listUser·p0.9999: 30.290 ms/op
                 listUser·p1.00:   30.933 ms/op

Iteration   2: 5.588 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.282 ms/op
                 listUser·p0.50:   5.267 ms/op
                 listUser·p0.90:   7.553 ms/op
                 listUser·p0.95:   8.569 ms/op
                 listUser·p0.99:   10.846 ms/op
                 listUser·p0.999:  19.936 ms/op
                 listUser·p0.9999: 25.044 ms/op
                 listUser·p1.00:   30.474 ms/op

Iteration   3: 5.719 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.376 ms/op
                 listUser·p0.50:   5.431 ms/op
                 listUser·p0.90:   7.356 ms/op
                 listUser·p0.95:   8.487 ms/op
                 listUser·p0.99:   11.059 ms/op
                 listUser·p0.999:  21.889 ms/op
                 listUser·p0.9999: 25.173 ms/op
                 listUser·p1.00:   26.313 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 169275
  mean =      5.666 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 140 
    [ 2.500,  5.000) = 59600 
    [ 5.000,  7.500) = 92132 
    [ 7.500, 10.000) = 14444 
    [10.000, 12.500) = 2178 
    [12.500, 15.000) = 380 
    [15.000, 17.500) = 166 
    [17.500, 20.000) = 53 
    [20.000, 22.500) = 81 
    [22.500, 25.000) = 53 
    [25.000, 27.500) = 13 
    [27.500, 30.000) = 23 
    [30.000, 32.500) = 12 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.282 ms/op
     p(50.0000) =      5.358 ms/op
     p(90.0000) =      7.537 ms/op
     p(95.0000) =      8.569 ms/op
     p(99.0000) =     10.879 ms/op
     p(99.9000) =     20.715 ms/op
     p(99.9900) =     29.498 ms/op
     p(99.9990) =     30.888 ms/op
     p(99.9999) =     30.933 ms/op
    p(100.0000) =     30.933 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.817 ± 0.749  ops/ms
ClientGrpc.existUser                       thrpt       3   8.001 ± 6.166  ops/ms
ClientGrpc.getUser                         thrpt       3   7.470 ± 2.088  ops/ms
ClientGrpc.listUser                        thrpt       3   5.989 ± 2.807  ops/ms
ClientGrpc.createUser                       avgt       3   4.177 ± 1.236   ms/op
ClientGrpc.existUser                        avgt       3   3.851 ± 0.920   ms/op
ClientGrpc.getUser                          avgt       3   4.001 ± 6.844   ms/op
ClientGrpc.listUser                         avgt       3   5.353 ± 8.589   ms/op
ClientGrpc.createUser                     sample  239315   4.009 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.908           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.863           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.071           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.612           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.602           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.808           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          23.953           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          24.674           ms/op
ClientGrpc.existUser                      sample  255595   3.757 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.748           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.666           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.653           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.087           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.521           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.600           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.987           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.742           ms/op
ClientGrpc.getUser                        sample  217687   4.409 ± 0.008   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           1.010           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.293           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.521           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.087           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           8.102           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          15.041           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          26.837           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          28.901           ms/op
ClientGrpc.listUser                       sample  169275   5.666 ± 0.013   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.282           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.358           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.537           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.569           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.879           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          20.715           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          29.498           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          30.933           ms/op
