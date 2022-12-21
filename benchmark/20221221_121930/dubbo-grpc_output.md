# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.108 ops/ms
# Warmup Iteration   2: 6.581 ops/ms
# Warmup Iteration   3: 8.365 ops/ms
Iteration   1: 8.347 ops/ms
Iteration   2: 8.671 ops/ms
Iteration   3: 8.707 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.575 ±(99.9%) 3.618 ops/ms [Average]
  (min, avg, max) = (8.347, 8.575, 8.707), stdev = 0.198
  CI (99.9%): [4.957, 12.193] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 6.058 ops/ms
# Warmup Iteration   2: 9.090 ops/ms
# Warmup Iteration   3: 9.034 ops/ms
Iteration   1: 9.354 ops/ms
Iteration   2: 9.293 ops/ms
Iteration   3: 9.355 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.334 ±(99.9%) 0.649 ops/ms [Average]
  (min, avg, max) = (9.293, 9.334, 9.355), stdev = 0.036
  CI (99.9%): [8.685, 9.983] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 6.048 ops/ms
# Warmup Iteration   2: 9.082 ops/ms
# Warmup Iteration   3: 9.275 ops/ms
Iteration   1: 9.314 ops/ms
Iteration   2: 9.109 ops/ms
Iteration   3: 9.274 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.232 ±(99.9%) 1.984 ops/ms [Average]
  (min, avg, max) = (9.109, 9.232, 9.314), stdev = 0.109
  CI (99.9%): [7.249, 11.216] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 4.235 ops/ms
# Warmup Iteration   2: 6.024 ops/ms
# Warmup Iteration   3: 6.427 ops/ms
Iteration   1: 6.464 ops/ms
Iteration   2: 6.444 ops/ms
Iteration   3: 6.515 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.474 ±(99.9%) 0.668 ops/ms [Average]
  (min, avg, max) = (6.444, 6.474, 6.515), stdev = 0.037
  CI (99.9%): [5.806, 7.143] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 5.754 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.097 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.878 ±(99.9%) 0.012 ms/op
Iteration   1: 3.829 ±(99.9%) 0.002 ms/op
Iteration   2: 3.807 ±(99.9%) 0.002 ms/op
Iteration   3: 4.046 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.894 ±(99.9%) 2.413 ms/op [Average]
  (min, avg, max) = (3.807, 3.894, 4.046), stdev = 0.132
  CI (99.9%): [1.482, 6.307] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 5.384 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.879 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.728 ±(99.9%) 0.003 ms/op
Iteration   1: 3.808 ±(99.9%) 0.002 ms/op
Iteration   2: 3.735 ±(99.9%) 0.002 ms/op
Iteration   3: 3.739 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.760 ±(99.9%) 0.745 ms/op [Average]
  (min, avg, max) = (3.735, 3.760, 3.808), stdev = 0.041
  CI (99.9%): [3.015, 4.505] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 5.370 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 4.131 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.943 ±(99.9%) 0.003 ms/op
Iteration   1: 3.887 ±(99.9%) 0.004 ms/op
Iteration   2: 3.994 ±(99.9%) 0.003 ms/op
Iteration   3: 3.820 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.900 ±(99.9%) 1.603 ms/op [Average]
  (min, avg, max) = (3.820, 3.900, 3.994), stdev = 0.088
  CI (99.9%): [2.297, 5.504] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 7.762 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 5.172 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.039 ±(99.9%) 0.016 ms/op
Iteration   1: 4.865 ±(99.9%) 0.011 ms/op
Iteration   2: 4.933 ±(99.9%) 0.006 ms/op
Iteration   3: 4.915 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.904 ±(99.9%) 0.638 ms/op [Average]
  (min, avg, max) = (4.865, 4.904, 4.933), stdev = 0.035
  CI (99.9%): [4.267, 5.542] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 5.673 ±(99.9%) 0.065 ms/op
# Warmup Iteration   2: 4.159 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.873 ±(99.9%) 0.009 ms/op
Iteration   1: 3.905 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.013 ms/op
                 createUser·p0.50:   3.813 ms/op
                 createUser·p0.90:   4.809 ms/op
                 createUser·p0.95:   5.145 ms/op
                 createUser·p0.99:   6.728 ms/op
                 createUser·p0.999:  14.914 ms/op
                 createUser·p0.9999: 16.929 ms/op
                 createUser·p1.00:   17.203 ms/op

Iteration   2: 3.965 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.916 ms/op
                 createUser·p0.50:   3.895 ms/op
                 createUser·p0.90:   4.964 ms/op
                 createUser·p0.95:   5.284 ms/op
                 createUser·p0.99:   6.693 ms/op
                 createUser·p0.999:  10.801 ms/op
                 createUser·p0.9999: 17.990 ms/op
                 createUser·p1.00:   20.087 ms/op

Iteration   3: 4.085 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   0.809 ms/op
                 createUser·p0.50:   3.994 ms/op
                 createUser·p0.90:   5.104 ms/op
                 createUser·p0.95:   5.423 ms/op
                 createUser·p0.99:   7.038 ms/op
                 createUser·p0.999:  15.904 ms/op
                 createUser·p0.9999: 23.014 ms/op
                 createUser·p1.00:   23.495 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 240910
  mean =      3.984 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6448 
    [ 2.500,  5.000) = 211957 
    [ 5.000,  7.500) = 20798 
    [ 7.500, 10.000) = 1000 
    [10.000, 12.500) = 368 
    [12.500, 15.000) = 141 
    [15.000, 17.500) = 112 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 35 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.809 ms/op
     p(50.0000) =      3.895 ms/op
     p(90.0000) =      4.964 ms/op
     p(95.0000) =      5.300 ms/op
     p(99.0000) =      6.824 ms/op
     p(99.9000) =     14.256 ms/op
     p(99.9900) =     20.805 ms/op
     p(99.9990) =     23.402 ms/op
     p(99.9999) =     23.495 ms/op
    p(100.0000) =     23.495 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.076 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 3.988 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.812 ±(99.9%) 0.010 ms/op
Iteration   1: 3.796 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.658 ms/op
                 existUser·p0.50:   3.715 ms/op
                 existUser·p0.90:   4.727 ms/op
                 existUser·p0.95:   5.005 ms/op
                 existUser·p0.99:   5.988 ms/op
                 existUser·p0.999:  9.376 ms/op
                 existUser·p0.9999: 17.896 ms/op
                 existUser·p1.00:   18.612 ms/op

Iteration   2: 3.707 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.756 ms/op
                 existUser·p0.50:   3.637 ms/op
                 existUser·p0.90:   4.628 ms/op
                 existUser·p0.95:   4.948 ms/op
                 existUser·p0.99:   6.038 ms/op
                 existUser·p0.999:  11.835 ms/op
                 existUser·p0.9999: 22.397 ms/op
                 existUser·p1.00:   23.003 ms/op

Iteration   3: 3.777 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.876 ms/op
                 existUser·p0.50:   3.703 ms/op
                 existUser·p0.90:   4.653 ms/op
                 existUser·p0.95:   4.973 ms/op
                 existUser·p0.99:   5.988 ms/op
                 existUser·p0.999:  11.633 ms/op
                 existUser·p0.9999: 25.021 ms/op
                 existUser·p1.00:   26.771 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 255165
  mean =      3.760 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8022 
    [ 2.500,  5.000) = 235000 
    [ 5.000,  7.500) = 11127 
    [ 7.500, 10.000) = 648 
    [10.000, 12.500) = 199 
    [12.500, 15.000) = 29 
    [15.000, 17.500) = 62 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.658 ms/op
     p(50.0000) =      3.686 ms/op
     p(90.0000) =      4.669 ms/op
     p(95.0000) =      4.981 ms/op
     p(99.0000) =      5.997 ms/op
     p(99.9000) =     11.515 ms/op
     p(99.9900) =     24.673 ms/op
     p(99.9990) =     26.062 ms/op
     p(99.9999) =     26.771 ms/op
    p(100.0000) =     26.771 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.550 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 4.154 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.883 ±(99.9%) 0.010 ms/op
Iteration   1: 3.956 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.026 ms/op
                 getUser·p0.50:   3.834 ms/op
                 getUser·p0.90:   4.948 ms/op
                 getUser·p0.95:   5.333 ms/op
                 getUser·p0.99:   7.512 ms/op
                 getUser·p0.999:  12.780 ms/op
                 getUser·p0.9999: 17.656 ms/op
                 getUser·p1.00:   18.186 ms/op

Iteration   2: 4.007 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.887 ms/op
                 getUser·p0.50:   3.949 ms/op
                 getUser·p0.90:   4.948 ms/op
                 getUser·p0.95:   5.251 ms/op
                 getUser·p0.99:   6.398 ms/op
                 getUser·p0.999:  10.969 ms/op
                 getUser·p0.9999: 21.463 ms/op
                 getUser·p1.00:   25.362 ms/op

Iteration   3: 3.899 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.791 ms/op
                 getUser·p0.50:   3.842 ms/op
                 getUser·p0.90:   4.817 ms/op
                 getUser·p0.95:   5.112 ms/op
                 getUser·p0.99:   6.226 ms/op
                 getUser·p0.999:  11.468 ms/op
                 getUser·p0.9999: 22.787 ms/op
                 getUser·p1.00:   25.395 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 242785
  mean =      3.953 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6382 
    [ 2.500,  5.000) = 216577 
    [ 5.000,  7.500) = 18276 
    [ 7.500, 10.000) = 1044 
    [10.000, 12.500) = 271 
    [12.500, 15.000) = 90 
    [15.000, 17.500) = 40 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 45 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.791 ms/op
     p(50.0000) =      3.875 ms/op
     p(90.0000) =      4.907 ms/op
     p(95.0000) =      5.235 ms/op
     p(99.0000) =      6.685 ms/op
     p(99.9000) =     12.452 ms/op
     p(99.9900) =     22.175 ms/op
     p(99.9990) =     25.334 ms/op
     p(99.9999) =     25.395 ms/op
    p(100.0000) =     25.395 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 6.315 ±(99.9%) 0.075 ms/op
# Warmup Iteration   2: 5.469 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 5.014 ±(99.9%) 0.016 ms/op
Iteration   1: 5.068 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   0.430 ms/op
                 listUser·p0.50:   4.801 ms/op
                 listUser·p0.90:   6.513 ms/op
                 listUser·p0.95:   7.528 ms/op
                 listUser·p0.99:   9.994 ms/op
                 listUser·p0.999:  21.714 ms/op
                 listUser·p0.9999: 26.544 ms/op
                 listUser·p1.00:   27.820 ms/op

Iteration   2: 4.997 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.532 ms/op
                 listUser·p0.50:   4.719 ms/op
                 listUser·p0.90:   6.496 ms/op
                 listUser·p0.95:   7.193 ms/op
                 listUser·p0.99:   9.568 ms/op
                 listUser·p0.999:  18.578 ms/op
                 listUser·p0.9999: 22.348 ms/op
                 listUser·p1.00:   24.609 ms/op

Iteration   3: 5.075 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.384 ms/op
                 listUser·p0.50:   4.817 ms/op
                 listUser·p0.90:   6.496 ms/op
                 listUser·p0.95:   7.332 ms/op
                 listUser·p0.99:   9.601 ms/op
                 listUser·p0.999:  22.872 ms/op
                 listUser·p0.9999: 32.030 ms/op
                 listUser·p1.00:   32.571 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 190162
  mean =      5.046 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 290 
    [ 2.500,  5.000) = 115692 
    [ 5.000,  7.500) = 65605 
    [ 7.500, 10.000) = 6952 
    [10.000, 12.500) = 988 
    [12.500, 15.000) = 257 
    [15.000, 17.500) = 108 
    [17.500, 20.000) = 67 
    [20.000, 22.500) = 77 
    [22.500, 25.000) = 63 
    [25.000, 27.500) = 28 
    [27.500, 30.000) = 16 
    [30.000, 32.500) = 18 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.430 ms/op
     p(50.0000) =      4.784 ms/op
     p(90.0000) =      6.496 ms/op
     p(95.0000) =      7.348 ms/op
     p(99.0000) =      9.732 ms/op
     p(99.9000) =     20.873 ms/op
     p(99.9900) =     30.015 ms/op
     p(99.9990) =     32.335 ms/op
     p(99.9999) =     32.571 ms/op
    p(100.0000) =     32.571 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.575 ± 3.618  ops/ms
ClientGrpc.existUser                       thrpt       3   9.334 ± 0.649  ops/ms
ClientGrpc.getUser                         thrpt       3   9.232 ± 1.984  ops/ms
ClientGrpc.listUser                        thrpt       3   6.474 ± 0.668  ops/ms
ClientGrpc.createUser                       avgt       3   3.894 ± 2.413   ms/op
ClientGrpc.existUser                        avgt       3   3.760 ± 0.745   ms/op
ClientGrpc.getUser                          avgt       3   3.900 ± 1.603   ms/op
ClientGrpc.listUser                         avgt       3   4.904 ± 0.638   ms/op
ClientGrpc.createUser                     sample  240910   3.984 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.809           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.895           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.964           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.300           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.824           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          14.256           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.805           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.495           ms/op
ClientGrpc.existUser                      sample  255165   3.760 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.658           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.686           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.669           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.981           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.997           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.515           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          24.673           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          26.771           ms/op
ClientGrpc.getUser                        sample  242785   3.953 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.791           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.875           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.907           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.235           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.685           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.452           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          22.175           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          25.395           ms/op
ClientGrpc.listUser                       sample  190162   5.046 ± 0.011   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.430           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.784           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.496           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.348           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.732           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          20.873           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          30.015           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          32.571           ms/op
