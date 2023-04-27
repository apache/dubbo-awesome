# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.103 ops/ms
# Warmup Iteration   2: 5.015 ops/ms
# Warmup Iteration   3: 7.314 ops/ms
Iteration   1: 7.478 ops/ms
Iteration   2: 7.441 ops/ms
Iteration   3: 7.546 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.488 ±(99.9%) 0.974 ops/ms [Average]
  (min, avg, max) = (7.441, 7.488, 7.546), stdev = 0.053
  CI (99.9%): [6.514, 8.462] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:12:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.442 ops/ms
# Warmup Iteration   2: 7.341 ops/ms
# Warmup Iteration   3: 8.018 ops/ms
Iteration   1: 8.599 ops/ms
Iteration   2: 8.336 ops/ms
Iteration   3: 8.415 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.450 ±(99.9%) 2.464 ops/ms [Average]
  (min, avg, max) = (8.336, 8.450, 8.599), stdev = 0.135
  CI (99.9%): [5.987, 10.914] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 4.009 ops/ms
# Warmup Iteration   2: 7.006 ops/ms
# Warmup Iteration   3: 7.593 ops/ms
Iteration   1: 7.542 ops/ms
Iteration   2: 7.866 ops/ms
Iteration   3: 7.768 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.725 ±(99.9%) 3.028 ops/ms [Average]
  (min, avg, max) = (7.542, 7.725, 7.866), stdev = 0.166
  CI (99.9%): [4.697, 10.753] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.716 ops/ms
# Warmup Iteration   2: 5.490 ops/ms
# Warmup Iteration   3: 5.860 ops/ms
Iteration   1: 6.199 ops/ms
Iteration   2: 6.123 ops/ms
Iteration   3: 6.018 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.113 ±(99.9%) 1.659 ops/ms [Average]
  (min, avg, max) = (6.018, 6.113, 6.199), stdev = 0.091
  CI (99.9%): [4.454, 7.773] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 6.673 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 4.551 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.353 ±(99.9%) 0.004 ms/op
Iteration   1: 4.206 ±(99.9%) 0.004 ms/op
Iteration   2: 4.146 ±(99.9%) 0.004 ms/op
Iteration   3: 4.098 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.150 ±(99.9%) 0.982 ms/op [Average]
  (min, avg, max) = (4.098, 4.150, 4.206), stdev = 0.054
  CI (99.9%): [3.168, 5.133] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 5.890 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 4.169 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.880 ±(99.9%) 0.003 ms/op
Iteration   1: 3.760 ±(99.9%) 0.004 ms/op
Iteration   2: 3.934 ±(99.9%) 0.003 ms/op
Iteration   3: 3.785 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.826 ±(99.9%) 1.719 ms/op [Average]
  (min, avg, max) = (3.760, 3.826, 3.934), stdev = 0.094
  CI (99.9%): [2.108, 5.545] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 6.554 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 4.237 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.033 ±(99.9%) 0.017 ms/op
Iteration   1: 4.032 ±(99.9%) 0.003 ms/op
Iteration   2: 3.987 ±(99.9%) 0.004 ms/op
Iteration   3: 4.191 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.070 ±(99.9%) 1.954 ms/op [Average]
  (min, avg, max) = (3.987, 4.070, 4.191), stdev = 0.107
  CI (99.9%): [2.116, 6.024] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 7.927 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 5.563 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 5.301 ±(99.9%) 0.011 ms/op
Iteration   1: 5.451 ±(99.9%) 0.010 ms/op
Iteration   2: 5.420 ±(99.9%) 0.025 ms/op
Iteration   3: 5.212 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.361 ±(99.9%) 2.377 ms/op [Average]
  (min, avg, max) = (5.212, 5.361, 5.451), stdev = 0.130
  CI (99.9%): [2.983, 7.738] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 6.482 ±(99.9%) 0.078 ms/op
# Warmup Iteration   2: 4.483 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.095 ±(99.9%) 0.013 ms/op
Iteration   1: 4.015 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.884 ms/op
                 createUser·p0.50:   3.924 ms/op
                 createUser·p0.90:   4.940 ms/op
                 createUser·p0.95:   5.341 ms/op
                 createUser·p0.99:   7.007 ms/op
                 createUser·p0.999:  11.909 ms/op
                 createUser·p0.9999: 15.565 ms/op
                 createUser·p1.00:   15.794 ms/op

Iteration   2: 4.024 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.028 ms/op
                 createUser·p0.50:   3.920 ms/op
                 createUser·p0.90:   4.997 ms/op
                 createUser·p0.95:   5.374 ms/op
                 createUser·p0.99:   6.791 ms/op
                 createUser·p0.999:  11.387 ms/op
                 createUser·p0.9999: 27.268 ms/op
                 createUser·p1.00:   27.853 ms/op

Iteration   3: 4.032 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.892 ms/op
                 createUser·p0.50:   3.895 ms/op
                 createUser·p0.90:   4.989 ms/op
                 createUser·p0.95:   5.415 ms/op
                 createUser·p0.99:   7.635 ms/op
                 createUser·p0.999:  13.637 ms/op
                 createUser·p0.9999: 18.743 ms/op
                 createUser·p1.00:   18.973 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 238481
  mean =      4.024 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7121 
    [ 2.500,  5.000) = 208475 
    [ 5.000,  7.500) = 20923 
    [ 7.500, 10.000) = 1346 
    [10.000, 12.500) = 372 
    [12.500, 15.000) = 93 
    [15.000, 17.500) = 42 
    [17.500, 20.000) = 77 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 27 

  Percentiles, ms/op:
      p(0.0000) =      0.884 ms/op
     p(50.0000) =      3.912 ms/op
     p(90.0000) =      4.973 ms/op
     p(95.0000) =      5.374 ms/op
     p(99.0000) =      7.143 ms/op
     p(99.9000) =     12.542 ms/op
     p(99.9900) =     25.985 ms/op
     p(99.9990) =     27.815 ms/op
     p(99.9999) =     27.853 ms/op
    p(100.0000) =     27.853 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.093 ±(99.9%) 0.071 ms/op
# Warmup Iteration   2: 4.413 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.049 ±(99.9%) 0.012 ms/op
Iteration   1: 3.975 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.087 ms/op
                 existUser·p0.50:   3.817 ms/op
                 existUser·p0.90:   4.915 ms/op
                 existUser·p0.95:   5.390 ms/op
                 existUser·p0.99:   7.799 ms/op
                 existUser·p0.999:  15.161 ms/op
                 existUser·p0.9999: 16.694 ms/op
                 existUser·p1.00:   17.990 ms/op

Iteration   2: 3.883 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.991 ms/op
                 existUser·p0.50:   3.768 ms/op
                 existUser·p0.90:   4.735 ms/op
                 existUser·p0.95:   5.161 ms/op
                 existUser·p0.99:   7.209 ms/op
                 existUser·p0.999:  11.738 ms/op
                 existUser·p0.9999: 18.252 ms/op
                 existUser·p1.00:   19.530 ms/op

Iteration   3: 3.995 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.908 ms/op
                 existUser·p0.50:   3.854 ms/op
                 existUser·p0.90:   4.948 ms/op
                 existUser·p0.95:   5.415 ms/op
                 existUser·p0.99:   7.340 ms/op
                 existUser·p0.999:  12.730 ms/op
                 existUser·p0.9999: 22.607 ms/op
                 existUser·p1.00:   23.921 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 243280
  mean =      3.950 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5415 
    [ 2.500,  5.000) = 218169 
    [ 5.000,  7.500) = 17305 
    [ 7.500, 10.000) = 1744 
    [10.000, 12.500) = 260 
    [12.500, 15.000) = 223 
    [15.000, 17.500) = 80 
    [17.500, 20.000) = 49 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.908 ms/op
     p(50.0000) =      3.809 ms/op
     p(90.0000) =      4.866 ms/op
     p(95.0000) =      5.325 ms/op
     p(99.0000) =      7.471 ms/op
     p(99.9000) =     13.414 ms/op
     p(99.9900) =     20.840 ms/op
     p(99.9990) =     23.845 ms/op
     p(99.9999) =     23.921 ms/op
    p(100.0000) =     23.921 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 7.169 ±(99.9%) 0.084 ms/op
# Warmup Iteration   2: 4.567 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.066 ±(99.9%) 0.011 ms/op
Iteration   1: 4.158 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.147 ms/op
                 getUser·p0.50:   4.010 ms/op
                 getUser·p0.90:   5.194 ms/op
                 getUser·p0.95:   5.661 ms/op
                 getUser·p0.99:   7.561 ms/op
                 getUser·p0.999:  12.587 ms/op
                 getUser·p0.9999: 19.999 ms/op
                 getUser·p1.00:   20.349 ms/op

Iteration   2: 4.051 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.001 ms/op
                 getUser·p0.50:   3.932 ms/op
                 getUser·p0.90:   4.989 ms/op
                 getUser·p0.95:   5.399 ms/op
                 getUser·p0.99:   7.127 ms/op
                 getUser·p0.999:  13.632 ms/op
                 getUser·p0.9999: 21.372 ms/op
                 getUser·p1.00:   22.741 ms/op

Iteration   3: 4.114 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.971 ms/op
                 getUser·p0.50:   4.022 ms/op
                 getUser·p0.90:   5.054 ms/op
                 getUser·p0.95:   5.423 ms/op
                 getUser·p0.99:   6.955 ms/op
                 getUser·p0.999:  10.064 ms/op
                 getUser·p0.9999: 27.631 ms/op
                 getUser·p1.00:   27.722 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 233577
  mean =      4.107 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5376 
    [ 2.500,  5.000) = 201584 
    [ 5.000,  7.500) = 24562 
    [ 7.500, 10.000) = 1635 
    [10.000, 12.500) = 182 
    [12.500, 15.000) = 99 
    [15.000, 17.500) = 19 
    [17.500, 20.000) = 61 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      0.971 ms/op
     p(50.0000) =      3.985 ms/op
     p(90.0000) =      5.079 ms/op
     p(95.0000) =      5.497 ms/op
     p(99.0000) =      7.268 ms/op
     p(99.9000) =     12.534 ms/op
     p(99.9900) =     23.548 ms/op
     p(99.9990) =     27.711 ms/op
     p(99.9999) =     27.722 ms/op
    p(100.0000) =     27.722 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 8.472 ±(99.9%) 0.109 ms/op
# Warmup Iteration   2: 5.943 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 5.568 ±(99.9%) 0.022 ms/op
Iteration   1: 5.492 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   1.790 ms/op
                 listUser·p0.50:   5.104 ms/op
                 listUser·p0.90:   7.627 ms/op
                 listUser·p0.95:   8.552 ms/op
                 listUser·p0.99:   11.296 ms/op
                 listUser·p0.999:  16.765 ms/op
                 listUser·p0.9999: 24.961 ms/op
                 listUser·p1.00:   28.508 ms/op

Iteration   2: 5.464 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.532 ms/op
                 listUser·p0.50:   5.128 ms/op
                 listUser·p0.90:   7.291 ms/op
                 listUser·p0.95:   8.208 ms/op
                 listUser·p0.99:   10.551 ms/op
                 listUser·p0.999:  17.465 ms/op
                 listUser·p0.9999: 20.340 ms/op
                 listUser·p1.00:   20.906 ms/op

Iteration   3: 5.500 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.391 ms/op
                 listUser·p0.50:   5.161 ms/op
                 listUser·p0.90:   7.217 ms/op
                 listUser·p0.95:   8.159 ms/op
                 listUser·p0.99:   10.748 ms/op
                 listUser·p0.999:  21.780 ms/op
                 listUser·p0.9999: 25.964 ms/op
                 listUser·p1.00:   26.968 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 174943
  mean =      5.485 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 199 
    [ 2.500,  5.000) = 77033 
    [ 5.000,  7.500) = 81657 
    [ 7.500, 10.000) = 13248 
    [10.000, 12.500) = 1967 
    [12.500, 15.000) = 434 
    [15.000, 17.500) = 193 
    [17.500, 20.000) = 97 
    [20.000, 22.500) = 54 
    [22.500, 25.000) = 43 
    [25.000, 27.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      1.391 ms/op
     p(50.0000) =      5.136 ms/op
     p(90.0000) =      7.381 ms/op
     p(95.0000) =      8.315 ms/op
     p(99.0000) =     10.895 ms/op
     p(99.9000) =     17.990 ms/op
     p(99.9900) =     25.166 ms/op
     p(99.9990) =     27.354 ms/op
     p(99.9999) =     28.508 ms/op
    p(100.0000) =     28.508 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.488 ± 0.974  ops/ms
ClientGrpc.existUser                       thrpt       3   8.450 ± 2.464  ops/ms
ClientGrpc.getUser                         thrpt       3   7.725 ± 3.028  ops/ms
ClientGrpc.listUser                        thrpt       3   6.113 ± 1.659  ops/ms
ClientGrpc.createUser                       avgt       3   4.150 ± 0.982   ms/op
ClientGrpc.existUser                        avgt       3   3.826 ± 1.719   ms/op
ClientGrpc.getUser                          avgt       3   4.070 ± 1.954   ms/op
ClientGrpc.listUser                         avgt       3   5.361 ± 2.377   ms/op
ClientGrpc.createUser                     sample  238481   4.024 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.884           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.912           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.973           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.374           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.143           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.542           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          25.985           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          27.853           ms/op
ClientGrpc.existUser                      sample  243280   3.950 ± 0.007   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.908           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.809           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.866           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.325           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.471           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          13.414           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.840           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          23.921           ms/op
ClientGrpc.getUser                        sample  233577   4.107 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.971           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.985           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.079           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.497           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.268           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.534           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          23.548           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          27.722           ms/op
ClientGrpc.listUser                       sample  174943   5.485 ± 0.012   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.391           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.136           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.381           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.315           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.895           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.990           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.166           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          28.508           ms/op
