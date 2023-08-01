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
# Warmup Iteration   1: 3.062 ops/ms
# Warmup Iteration   2: 6.709 ops/ms
# Warmup Iteration   3: 8.353 ops/ms
Iteration   1: 8.619 ops/ms
Iteration   2: 8.815 ops/ms
Iteration   3: 8.823 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.753 ±(99.9%) 2.104 ops/ms [Average]
  (min, avg, max) = (8.619, 8.753, 8.823), stdev = 0.115
  CI (99.9%): [6.649, 10.856] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 5.824 ops/ms
# Warmup Iteration   2: 8.889 ops/ms
# Warmup Iteration   3: 9.090 ops/ms
Iteration   1: 9.234 ops/ms
Iteration   2: 9.459 ops/ms
Iteration   3: 9.594 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.429 ±(99.9%) 3.320 ops/ms [Average]
  (min, avg, max) = (9.234, 9.429, 9.594), stdev = 0.182
  CI (99.9%): [6.109, 12.748] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 5.261 ops/ms
# Warmup Iteration   2: 8.242 ops/ms
# Warmup Iteration   3: 8.813 ops/ms
Iteration   1: 8.812 ops/ms
Iteration   2: 8.751 ops/ms
Iteration   3: 8.804 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.789 ±(99.9%) 0.605 ops/ms [Average]
  (min, avg, max) = (8.751, 8.789, 8.812), stdev = 0.033
  CI (99.9%): [8.184, 9.394] (assumes normal distribution)


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
# Warmup Iteration   1: 5.271 ops/ms
# Warmup Iteration   2: 6.099 ops/ms
# Warmup Iteration   3: 6.620 ops/ms
Iteration   1: 6.614 ops/ms
Iteration   2: 6.511 ops/ms
Iteration   3: 6.755 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.627 ±(99.9%) 2.233 ops/ms [Average]
  (min, avg, max) = (6.511, 6.627, 6.755), stdev = 0.122
  CI (99.9%): [4.394, 8.860] (assumes normal distribution)


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
# Warmup Iteration   1: 5.501 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.973 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.698 ±(99.9%) 0.006 ms/op
Iteration   1: 3.720 ±(99.9%) 0.004 ms/op
Iteration   2: 3.605 ±(99.9%) 0.004 ms/op
Iteration   3: 3.655 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.660 ±(99.9%) 1.049 ms/op [Average]
  (min, avg, max) = (3.605, 3.660, 3.720), stdev = 0.058
  CI (99.9%): [2.611, 4.709] (assumes normal distribution)


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
# Warmup Iteration   1: 4.927 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.619 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.452 ±(99.9%) 0.004 ms/op
Iteration   1: 3.429 ±(99.9%) 0.003 ms/op
Iteration   2: 3.503 ±(99.9%) 0.003 ms/op
Iteration   3: 3.399 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.444 ±(99.9%) 0.971 ms/op [Average]
  (min, avg, max) = (3.399, 3.444, 3.503), stdev = 0.053
  CI (99.9%): [2.472, 4.415] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 5.456 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.838 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.671 ±(99.9%) 0.011 ms/op
Iteration   1: 3.743 ±(99.9%) 0.005 ms/op
Iteration   2: 3.806 ±(99.9%) 0.005 ms/op
Iteration   3: 3.559 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.703 ±(99.9%) 2.346 ms/op [Average]
  (min, avg, max) = (3.559, 3.703, 3.806), stdev = 0.129
  CI (99.9%): [1.357, 6.048] (assumes normal distribution)


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
# Warmup Iteration   1: 6.997 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.939 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 4.821 ±(99.9%) 0.014 ms/op
Iteration   1: 4.628 ±(99.9%) 0.011 ms/op
Iteration   2: 4.689 ±(99.9%) 0.011 ms/op
Iteration   3: 4.744 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.687 ±(99.9%) 1.058 ms/op [Average]
  (min, avg, max) = (4.628, 4.687, 4.744), stdev = 0.058
  CI (99.9%): [3.629, 5.746] (assumes normal distribution)


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
# Warmup Iteration   1: 5.314 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 3.961 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.723 ±(99.9%) 0.009 ms/op
Iteration   1: 3.647 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.940 ms/op
                 createUser·p0.50:   3.580 ms/op
                 createUser·p0.90:   4.260 ms/op
                 createUser·p0.95:   4.588 ms/op
                 createUser·p0.99:   5.833 ms/op
                 createUser·p0.999:  9.868 ms/op
                 createUser·p0.9999: 28.581 ms/op
                 createUser·p1.00:   29.098 ms/op

Iteration   2: 3.586 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.777 ms/op
                 createUser·p0.50:   3.555 ms/op
                 createUser·p0.90:   4.375 ms/op
                 createUser·p0.95:   4.710 ms/op
                 createUser·p0.99:   5.882 ms/op
                 createUser·p0.999:  10.864 ms/op
                 createUser·p0.9999: 25.203 ms/op
                 createUser·p1.00:   26.477 ms/op

Iteration   3: 3.672 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.974 ms/op
                 createUser·p0.50:   3.572 ms/op
                 createUser·p0.90:   4.350 ms/op
                 createUser·p0.95:   4.809 ms/op
                 createUser·p0.99:   6.382 ms/op
                 createUser·p0.999:  17.624 ms/op
                 createUser·p0.9999: 28.101 ms/op
                 createUser·p1.00:   28.705 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 264181
  mean =      3.635 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9350 
    [ 2.500,  5.000) = 246994 
    [ 5.000,  7.500) = 6920 
    [ 7.500, 10.000) = 568 
    [10.000, 12.500) = 106 
    [12.500, 15.000) = 19 
    [15.000, 17.500) = 6 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 82 
    [25.000, 27.500) = 47 

  Percentiles, ms/op:
      p(0.0000) =      0.777 ms/op
     p(50.0000) =      3.568 ms/op
     p(90.0000) =      4.325 ms/op
     p(95.0000) =      4.702 ms/op
     p(99.0000) =      6.046 ms/op
     p(99.9000) =     11.594 ms/op
     p(99.9900) =     28.527 ms/op
     p(99.9990) =     29.044 ms/op
     p(99.9999) =     29.098 ms/op
    p(100.0000) =     29.098 ms/op


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
# Warmup Iteration   1: 4.841 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.718 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.470 ±(99.9%) 0.008 ms/op
Iteration   1: 3.475 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.783 ms/op
                 existUser·p0.50:   3.416 ms/op
                 existUser·p0.90:   4.170 ms/op
                 existUser·p0.95:   4.563 ms/op
                 existUser·p0.99:   5.832 ms/op
                 existUser·p0.999:  9.304 ms/op
                 existUser·p0.9999: 24.948 ms/op
                 existUser·p1.00:   26.083 ms/op

Iteration   2: 3.550 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.863 ms/op
                 existUser·p0.50:   3.478 ms/op
                 existUser·p0.90:   4.235 ms/op
                 existUser·p0.95:   4.612 ms/op
                 existUser·p0.99:   6.062 ms/op
                 existUser·p0.999:  14.512 ms/op
                 existUser·p0.9999: 22.413 ms/op
                 existUser·p1.00:   22.610 ms/op

Iteration   3: 3.446 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.736 ms/op
                 existUser·p0.50:   3.400 ms/op
                 existUser·p0.90:   4.080 ms/op
                 existUser·p0.95:   4.415 ms/op
                 existUser·p0.99:   5.480 ms/op
                 existUser·p0.999:  9.011 ms/op
                 existUser·p0.9999: 23.921 ms/op
                 existUser·p1.00:   24.314 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 274988
  mean =      3.490 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12414 
    [ 2.500,  5.000) = 256337 
    [ 5.000,  7.500) = 5142 
    [ 7.500, 10.000) = 732 
    [10.000, 12.500) = 125 
    [12.500, 15.000) = 110 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 45 
    [22.500, 25.000) = 48 
    [25.000, 27.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.736 ms/op
     p(50.0000) =      3.428 ms/op
     p(90.0000) =      4.170 ms/op
     p(95.0000) =      4.530 ms/op
     p(99.0000) =      5.759 ms/op
     p(99.9000) =     11.190 ms/op
     p(99.9900) =     23.822 ms/op
     p(99.9990) =     25.829 ms/op
     p(99.9999) =     26.083 ms/op
    p(100.0000) =     26.083 ms/op


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
# Warmup Iteration   1: 5.434 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 3.809 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.588 ±(99.9%) 0.009 ms/op
Iteration   1: 3.581 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.670 ms/op
                 getUser·p0.50:   3.535 ms/op
                 getUser·p0.90:   4.186 ms/op
                 getUser·p0.95:   4.514 ms/op
                 getUser·p0.99:   5.915 ms/op
                 getUser·p0.999:  11.009 ms/op
                 getUser·p0.9999: 13.961 ms/op
                 getUser·p1.00:   16.499 ms/op

Iteration   2: 3.553 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.911 ms/op
                 getUser·p0.50:   3.510 ms/op
                 getUser·p0.90:   4.116 ms/op
                 getUser·p0.95:   4.415 ms/op
                 getUser·p0.99:   5.341 ms/op
                 getUser·p0.999:  8.208 ms/op
                 getUser·p0.9999: 21.495 ms/op
                 getUser·p1.00:   22.053 ms/op

Iteration   3: 3.604 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.874 ms/op
                 getUser·p0.50:   3.551 ms/op
                 getUser·p0.90:   4.268 ms/op
                 getUser·p0.95:   4.596 ms/op
                 getUser·p0.99:   5.865 ms/op
                 getUser·p0.999:  8.360 ms/op
                 getUser·p0.9999: 29.426 ms/op
                 getUser·p1.00:   29.884 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 268254
  mean =      3.579 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7403 
    [ 2.500,  5.000) = 255118 
    [ 5.000,  7.500) = 4969 
    [ 7.500, 10.000) = 560 
    [10.000, 12.500) = 52 
    [12.500, 15.000) = 79 
    [15.000, 17.500) = 9 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.670 ms/op
     p(50.0000) =      3.531 ms/op
     p(90.0000) =      4.190 ms/op
     p(95.0000) =      4.514 ms/op
     p(99.0000) =      5.734 ms/op
     p(99.9000) =      8.909 ms/op
     p(99.9900) =     28.710 ms/op
     p(99.9990) =     29.764 ms/op
     p(99.9999) =     29.884 ms/op
    p(100.0000) =     29.884 ms/op


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
# Warmup Iteration   1: 6.925 ±(99.9%) 0.074 ms/op
# Warmup Iteration   2: 4.993 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.924 ±(99.9%) 0.016 ms/op
Iteration   1: 4.669 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.559 ms/op
                 listUser·p0.50:   4.456 ms/op
                 listUser·p0.90:   5.857 ms/op
                 listUser·p0.95:   6.881 ms/op
                 listUser·p0.99:   8.258 ms/op
                 listUser·p0.999:  14.975 ms/op
                 listUser·p0.9999: 16.630 ms/op
                 listUser·p1.00:   18.317 ms/op

Iteration   2: 4.380 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.180 ms/op
                 listUser·p0.50:   4.260 ms/op
                 listUser·p0.90:   5.038 ms/op
                 listUser·p0.95:   5.987 ms/op
                 listUser·p0.99:   7.856 ms/op
                 listUser·p0.999:  14.768 ms/op
                 listUser·p0.9999: 22.274 ms/op
                 listUser·p1.00:   22.938 ms/op

Iteration   3: 4.605 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.399 ms/op
                 listUser·p0.50:   4.456 ms/op
                 listUser·p0.90:   5.374 ms/op
                 listUser·p0.95:   6.488 ms/op
                 listUser·p0.99:   8.217 ms/op
                 listUser·p0.999:  18.255 ms/op
                 listUser·p0.9999: 22.581 ms/op
                 listUser·p1.00:   24.707 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 211068
  mean =      4.548 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 418 
    [ 2.500,  5.000) = 178481 
    [ 5.000,  7.500) = 28146 
    [ 7.500, 10.000) = 3371 
    [10.000, 12.500) = 260 
    [12.500, 15.000) = 148 
    [15.000, 17.500) = 109 
    [17.500, 20.000) = 62 
    [20.000, 22.500) = 61 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.180 ms/op
     p(50.0000) =      4.391 ms/op
     p(90.0000) =      5.431 ms/op
     p(95.0000) =      6.504 ms/op
     p(99.0000) =      8.094 ms/op
     p(99.9000) =     15.629 ms/op
     p(99.9900) =     22.242 ms/op
     p(99.9990) =     22.967 ms/op
     p(99.9999) =     24.707 ms/op
    p(100.0000) =     24.707 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.753 ± 2.104  ops/ms
ClientGrpc.existUser                       thrpt       3   9.429 ± 3.320  ops/ms
ClientGrpc.getUser                         thrpt       3   8.789 ± 0.605  ops/ms
ClientGrpc.listUser                        thrpt       3   6.627 ± 2.233  ops/ms
ClientGrpc.createUser                       avgt       3   3.660 ± 1.049   ms/op
ClientGrpc.existUser                        avgt       3   3.444 ± 0.971   ms/op
ClientGrpc.getUser                          avgt       3   3.703 ± 2.346   ms/op
ClientGrpc.listUser                         avgt       3   4.687 ± 1.058   ms/op
ClientGrpc.createUser                     sample  264181   3.635 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.777           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.568           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.325           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.702           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.046           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.594           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          28.527           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          29.098           ms/op
ClientGrpc.existUser                      sample  274988   3.490 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.736           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.428           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.170           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.530           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.759           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.190           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          23.822           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          26.083           ms/op
ClientGrpc.getUser                        sample  268254   3.579 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.670           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.531           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.190           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.514           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.734           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.909           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          28.710           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          29.884           ms/op
ClientGrpc.listUser                       sample  211068   4.548 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.180           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.391           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.431           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.504           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.094           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.629           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.242           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.707           ms/op
