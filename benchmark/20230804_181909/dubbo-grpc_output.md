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
# Warmup Iteration   1: 3.554 ops/ms
# Warmup Iteration   2: 8.301 ops/ms
# Warmup Iteration   3: 9.648 ops/ms
Iteration   1: 10.173 ops/ms
Iteration   2: 10.227 ops/ms
Iteration   3: 10.388 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.263 ±(99.9%) 2.044 ops/ms [Average]
  (min, avg, max) = (10.173, 10.263, 10.388), stdev = 0.112
  CI (99.9%): [8.219, 12.307] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 7.208 ops/ms
# Warmup Iteration   2: 10.147 ops/ms
# Warmup Iteration   3: 10.646 ops/ms
Iteration   1: 10.750 ops/ms
Iteration   2: 10.862 ops/ms
Iteration   3: 10.825 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.812 ±(99.9%) 1.036 ops/ms [Average]
  (min, avg, max) = (10.750, 10.812, 10.862), stdev = 0.057
  CI (99.9%): [9.776, 11.849] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 6.819 ops/ms
# Warmup Iteration   2: 9.865 ops/ms
# Warmup Iteration   3: 10.177 ops/ms
Iteration   1: 10.281 ops/ms
Iteration   2: 10.195 ops/ms
Iteration   3: 10.328 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.268 ±(99.9%) 1.221 ops/ms [Average]
  (min, avg, max) = (10.195, 10.268, 10.328), stdev = 0.067
  CI (99.9%): [9.047, 11.489] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.256 ops/ms
# Warmup Iteration   2: 7.523 ops/ms
# Warmup Iteration   3: 7.861 ops/ms
Iteration   1: 7.879 ops/ms
Iteration   2: 7.939 ops/ms
Iteration   3: 7.928 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.915 ±(99.9%) 0.579 ops/ms [Average]
  (min, avg, max) = (7.879, 7.915, 7.939), stdev = 0.032
  CI (99.9%): [7.336, 8.495] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.406 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.264 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.107 ±(99.9%) 0.003 ms/op
Iteration   1: 3.158 ±(99.9%) 0.002 ms/op
Iteration   2: 3.113 ±(99.9%) 0.002 ms/op
Iteration   3: 3.107 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.126 ±(99.9%) 0.510 ms/op [Average]
  (min, avg, max) = (3.107, 3.126, 3.158), stdev = 0.028
  CI (99.9%): [2.616, 3.636] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.300 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.095 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.924 ±(99.9%) 0.003 ms/op
Iteration   1: 2.890 ±(99.9%) 0.003 ms/op
Iteration   2: 2.736 ±(99.9%) 0.003 ms/op
Iteration   3: 2.947 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.858 ±(99.9%) 1.994 ms/op [Average]
  (min, avg, max) = (2.736, 2.858, 2.947), stdev = 0.109
  CI (99.9%): [0.863, 4.852] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.423 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.229 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.115 ±(99.9%) 0.004 ms/op
Iteration   1: 3.092 ±(99.9%) 0.004 ms/op
Iteration   2: 3.054 ±(99.9%) 0.004 ms/op
Iteration   3: 3.059 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.068 ±(99.9%) 0.383 ms/op [Average]
  (min, avg, max) = (3.054, 3.068, 3.092), stdev = 0.021
  CI (99.9%): [2.685, 3.452] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 4.929 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 4.222 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 3.984 ±(99.9%) 0.012 ms/op
Iteration   1: 4.014 ±(99.9%) 0.023 ms/op
Iteration   2: 3.994 ±(99.9%) 0.019 ms/op
Iteration   3: 3.954 ±(99.9%) 0.024 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.988 ±(99.9%) 0.556 ms/op [Average]
  (min, avg, max) = (3.954, 3.988, 4.014), stdev = 0.030
  CI (99.9%): [3.432, 4.543] (assumes normal distribution)


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
# Warmup Iteration   1: 4.297 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.342 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.098 ±(99.9%) 0.007 ms/op
Iteration   1: 3.044 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.725 ms/op
                 createUser·p0.50:   3.019 ms/op
                 createUser·p0.90:   3.527 ms/op
                 createUser·p0.95:   3.777 ms/op
                 createUser·p0.99:   4.727 ms/op
                 createUser·p0.999:  8.552 ms/op
                 createUser·p0.9999: 12.886 ms/op
                 createUser·p1.00:   15.073 ms/op

Iteration   2: 3.096 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.891 ms/op
                 createUser·p0.50:   3.043 ms/op
                 createUser·p0.90:   3.604 ms/op
                 createUser·p0.95:   3.834 ms/op
                 createUser·p0.99:   4.571 ms/op
                 createUser·p0.999:  9.322 ms/op
                 createUser·p0.9999: 14.298 ms/op
                 createUser·p1.00:   14.533 ms/op

Iteration   3: 3.025 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.413 ms/op
                 createUser·p0.50:   2.998 ms/op
                 createUser·p0.90:   3.650 ms/op
                 createUser·p0.95:   3.912 ms/op
                 createUser·p0.99:   4.768 ms/op
                 createUser·p0.999:  11.322 ms/op
                 createUser·p0.9999: 16.715 ms/op
                 createUser·p1.00:   17.596 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 314407
  mean =      3.055 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 615 
    [ 1.250,  2.500) = 20708 
    [ 2.500,  3.750) = 271998 
    [ 3.750,  5.000) = 18731 
    [ 5.000,  6.250) = 1232 
    [ 6.250,  7.500) = 513 
    [ 7.500,  8.750) = 220 
    [ 8.750, 10.000) = 107 
    [10.000, 11.250) = 29 
    [11.250, 12.500) = 97 
    [12.500, 13.750) = 34 
    [13.750, 15.000) = 62 
    [15.000, 16.250) = 24 
    [16.250, 17.500) = 36 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.413 ms/op
     p(50.0000) =      3.023 ms/op
     p(90.0000) =      3.588 ms/op
     p(95.0000) =      3.846 ms/op
     p(99.0000) =      4.710 ms/op
     p(99.9000) =      9.463 ms/op
     p(99.9900) =     16.318 ms/op
     p(99.9990) =     17.259 ms/op
     p(99.9999) =     17.596 ms/op
    p(100.0000) =     17.596 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 4.161 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.102 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.016 ±(99.9%) 0.006 ms/op
Iteration   1: 2.940 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.632 ms/op
                 existUser·p0.50:   2.925 ms/op
                 existUser·p0.90:   3.387 ms/op
                 existUser·p0.95:   3.596 ms/op
                 existUser·p0.99:   4.415 ms/op
                 existUser·p0.999:  7.136 ms/op
                 existUser·p0.9999: 16.386 ms/op
                 existUser·p1.00:   16.777 ms/op

Iteration   2: 2.997 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.685 ms/op
                 existUser·p0.50:   2.953 ms/op
                 existUser·p0.90:   3.490 ms/op
                 existUser·p0.95:   3.686 ms/op
                 existUser·p0.99:   4.997 ms/op
                 existUser·p0.999:  10.196 ms/op
                 existUser·p0.9999: 17.584 ms/op
                 existUser·p1.00:   19.038 ms/op

Iteration   3: 2.955 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.654 ms/op
                 existUser·p0.50:   2.929 ms/op
                 existUser·p0.90:   3.518 ms/op
                 existUser·p0.95:   3.813 ms/op
                 existUser·p0.99:   4.424 ms/op
                 existUser·p0.999:  7.674 ms/op
                 existUser·p0.9999: 21.534 ms/op
                 existUser·p1.00:   21.889 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 323948
  mean =      2.964 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 32121 
    [ 2.500,  5.000) = 289689 
    [ 5.000,  7.500) = 1522 
    [ 7.500, 10.000) = 376 
    [10.000, 12.500) = 46 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 87 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 57 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.632 ms/op
     p(50.0000) =      2.933 ms/op
     p(90.0000) =      3.461 ms/op
     p(95.0000) =      3.711 ms/op
     p(99.0000) =      4.620 ms/op
     p(99.9000) =      8.815 ms/op
     p(99.9900) =     20.808 ms/op
     p(99.9990) =     21.783 ms/op
     p(99.9999) =     21.889 ms/op
    p(100.0000) =     21.889 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.468 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.240 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.089 ±(99.9%) 0.007 ms/op
Iteration   1: 3.094 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.748 ms/op
                 getUser·p0.50:   3.043 ms/op
                 getUser·p0.90:   3.674 ms/op
                 getUser·p0.95:   3.887 ms/op
                 getUser·p0.99:   4.735 ms/op
                 getUser·p0.999:  9.773 ms/op
                 getUser·p0.9999: 21.681 ms/op
                 getUser·p1.00:   22.020 ms/op

Iteration   2: 3.007 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.684 ms/op
                 getUser·p0.50:   3.006 ms/op
                 getUser·p0.90:   3.486 ms/op
                 getUser·p0.95:   3.736 ms/op
                 getUser·p0.99:   4.850 ms/op
                 getUser·p0.999:  8.569 ms/op
                 getUser·p0.9999: 14.647 ms/op
                 getUser·p1.00:   15.237 ms/op

Iteration   3: 3.068 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.932 ms/op
                 getUser·p0.50:   3.031 ms/op
                 getUser·p0.90:   3.527 ms/op
                 getUser·p0.95:   3.723 ms/op
                 getUser·p0.99:   4.932 ms/op
                 getUser·p0.999:  9.163 ms/op
                 getUser·p0.9999: 20.087 ms/op
                 getUser·p1.00:   20.251 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 314167
  mean =      3.056 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22612 
    [ 2.500,  5.000) = 288934 
    [ 5.000,  7.500) = 1870 
    [ 7.500, 10.000) = 458 
    [10.000, 12.500) = 133 
    [12.500, 15.000) = 26 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 45 
    [20.000, 22.500) = 55 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.684 ms/op
     p(50.0000) =      3.027 ms/op
     p(90.0000) =      3.572 ms/op
     p(95.0000) =      3.797 ms/op
     p(99.0000) =      4.833 ms/op
     p(99.9000) =      8.795 ms/op
     p(99.9900) =     20.977 ms/op
     p(99.9990) =     21.913 ms/op
     p(99.9999) =     22.020 ms/op
    p(100.0000) =     22.020 ms/op


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
# Warmup Iteration   1: 5.374 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 4.237 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.991 ±(99.9%) 0.011 ms/op
Iteration   1: 3.983 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.890 ms/op
                 listUser·p0.50:   3.781 ms/op
                 listUser·p0.90:   5.079 ms/op
                 listUser·p0.95:   5.890 ms/op
                 listUser·p0.99:   7.438 ms/op
                 listUser·p0.999:  13.877 ms/op
                 listUser·p0.9999: 16.431 ms/op
                 listUser·p1.00:   16.744 ms/op

Iteration   2: 4.049 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.831 ms/op
                 listUser·p0.50:   3.834 ms/op
                 listUser·p0.90:   5.276 ms/op
                 listUser·p0.95:   6.013 ms/op
                 listUser·p0.99:   7.275 ms/op
                 listUser·p0.999:  17.433 ms/op
                 listUser·p0.9999: 25.499 ms/op
                 listUser·p1.00:   25.887 ms/op

Iteration   3: 3.981 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.988 ms/op
                 listUser·p0.50:   3.842 ms/op
                 listUser·p0.90:   4.596 ms/op
                 listUser·p0.95:   5.562 ms/op
                 listUser·p0.99:   7.299 ms/op
                 listUser·p0.999:  16.559 ms/op
                 listUser·p0.9999: 20.867 ms/op
                 listUser·p1.00:   21.561 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 239746
  mean =      4.004 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2857 
    [ 2.500,  5.000) = 212058 
    [ 5.000,  7.500) = 22779 
    [ 7.500, 10.000) = 1556 
    [10.000, 12.500) = 127 
    [12.500, 15.000) = 90 
    [15.000, 17.500) = 166 
    [17.500, 20.000) = 69 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      0.831 ms/op
     p(50.0000) =      3.822 ms/op
     p(90.0000) =      5.038 ms/op
     p(95.0000) =      5.857 ms/op
     p(99.0000) =      7.332 ms/op
     p(99.9000) =     15.749 ms/op
     p(99.9900) =     24.019 ms/op
     p(99.9990) =     25.854 ms/op
     p(99.9999) =     25.887 ms/op
    p(100.0000) =     25.887 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.263 ± 2.044  ops/ms
ClientGrpc.existUser                       thrpt       3  10.812 ± 1.036  ops/ms
ClientGrpc.getUser                         thrpt       3  10.268 ± 1.221  ops/ms
ClientGrpc.listUser                        thrpt       3   7.915 ± 0.579  ops/ms
ClientGrpc.createUser                       avgt       3   3.126 ± 0.510   ms/op
ClientGrpc.existUser                        avgt       3   2.858 ± 1.994   ms/op
ClientGrpc.getUser                          avgt       3   3.068 ± 0.383   ms/op
ClientGrpc.listUser                         avgt       3   3.988 ± 0.556   ms/op
ClientGrpc.createUser                     sample  314407   3.055 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.413           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.023           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.588           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.846           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.710           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.463           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          16.318           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          17.596           ms/op
ClientGrpc.existUser                      sample  323948   2.964 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.632           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.933           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.461           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.711           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.620           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.815           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.808           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.889           ms/op
ClientGrpc.getUser                        sample  314167   3.056 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.684           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.027           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.572           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.797           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.833           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.795           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.977           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.020           ms/op
ClientGrpc.listUser                       sample  239746   4.004 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.831           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.822           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.038           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.857           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.332           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.749           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.019           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.887           ms/op
