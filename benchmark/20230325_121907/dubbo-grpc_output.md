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
# Warmup Iteration   1: 4.459 ops/ms
# Warmup Iteration   2: 9.724 ops/ms
# Warmup Iteration   3: 10.215 ops/ms
Iteration   1: 10.666 ops/ms
Iteration   2: 10.800 ops/ms
Iteration   3: 10.493 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.653 ±(99.9%) 2.808 ops/ms [Average]
  (min, avg, max) = (10.493, 10.653, 10.800), stdev = 0.154
  CI (99.9%): [7.845, 13.461] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 7.555 ops/ms
# Warmup Iteration   2: 10.706 ops/ms
# Warmup Iteration   3: 11.192 ops/ms
Iteration   1: 11.205 ops/ms
Iteration   2: 11.189 ops/ms
Iteration   3: 11.141 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.179 ±(99.9%) 0.606 ops/ms [Average]
  (min, avg, max) = (11.141, 11.179, 11.205), stdev = 0.033
  CI (99.9%): [10.573, 11.785] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.479 ops/ms
# Warmup Iteration   2: 10.234 ops/ms
# Warmup Iteration   3: 10.777 ops/ms
Iteration   1: 10.736 ops/ms
Iteration   2: 10.661 ops/ms
Iteration   3: 10.778 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.725 ±(99.9%) 1.077 ops/ms [Average]
  (min, avg, max) = (10.661, 10.725, 10.778), stdev = 0.059
  CI (99.9%): [9.647, 11.802] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.365 ops/ms
# Warmup Iteration   2: 8.049 ops/ms
# Warmup Iteration   3: 8.199 ops/ms
Iteration   1: 8.172 ops/ms
Iteration   2: 8.308 ops/ms
Iteration   3: 8.127 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.202 ±(99.9%) 1.716 ops/ms [Average]
  (min, avg, max) = (8.127, 8.202, 8.308), stdev = 0.094
  CI (99.9%): [6.486, 9.918] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.071 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.087 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.981 ±(99.9%) 0.002 ms/op
Iteration   1: 2.964 ±(99.9%) 0.003 ms/op
Iteration   2: 2.968 ±(99.9%) 0.003 ms/op
Iteration   3: 2.925 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.953 ±(99.9%) 0.432 ms/op [Average]
  (min, avg, max) = (2.925, 2.953, 2.968), stdev = 0.024
  CI (99.9%): [2.520, 3.385] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.822 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.027 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 2.873 ±(99.9%) 0.002 ms/op
Iteration   1: 2.909 ±(99.9%) 0.001 ms/op
Iteration   2: 2.864 ±(99.9%) 0.002 ms/op
Iteration   3: 2.910 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.894 ±(99.9%) 0.484 ms/op [Average]
  (min, avg, max) = (2.864, 2.894, 2.910), stdev = 0.027
  CI (99.9%): [2.410, 3.378] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 4.016 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.082 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.993 ±(99.9%) 0.003 ms/op
Iteration   1: 2.969 ±(99.9%) 0.003 ms/op
Iteration   2: 3.018 ±(99.9%) 0.003 ms/op
Iteration   3: 2.965 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.984 ±(99.9%) 0.535 ms/op [Average]
  (min, avg, max) = (2.965, 2.984, 3.018), stdev = 0.029
  CI (99.9%): [2.449, 3.519] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 5.556 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.995 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 3.955 ±(99.9%) 0.022 ms/op
Iteration   1: 3.937 ±(99.9%) 0.024 ms/op
Iteration   2: 3.897 ±(99.9%) 0.020 ms/op
Iteration   3: 3.889 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.907 ±(99.9%) 0.470 ms/op [Average]
  (min, avg, max) = (3.889, 3.907, 3.937), stdev = 0.026
  CI (99.9%): [3.438, 4.377] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.134 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.158 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.064 ±(99.9%) 0.006 ms/op
Iteration   1: 3.020 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.848 ms/op
                 createUser·p0.50:   2.982 ms/op
                 createUser·p0.90:   3.580 ms/op
                 createUser·p0.95:   3.789 ms/op
                 createUser·p0.99:   4.415 ms/op
                 createUser·p0.999:  6.865 ms/op
                 createUser·p0.9999: 23.626 ms/op
                 createUser·p1.00:   24.510 ms/op

Iteration   2: 2.983 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.595 ms/op
                 createUser·p0.50:   2.953 ms/op
                 createUser·p0.90:   3.432 ms/op
                 createUser·p0.95:   3.682 ms/op
                 createUser·p0.99:   4.358 ms/op
                 createUser·p0.999:  6.896 ms/op
                 createUser·p0.9999: 14.652 ms/op
                 createUser·p1.00:   15.204 ms/op

Iteration   3: 3.012 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.593 ms/op
                 createUser·p0.50:   2.986 ms/op
                 createUser·p0.90:   3.514 ms/op
                 createUser·p0.95:   3.715 ms/op
                 createUser·p0.99:   4.506 ms/op
                 createUser·p0.999:  9.126 ms/op
                 createUser·p0.9999: 29.622 ms/op
                 createUser·p1.00:   29.950 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 319348
  mean =      3.005 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 28036 
    [ 2.500,  5.000) = 290030 
    [ 5.000,  7.500) = 983 
    [ 7.500, 10.000) = 75 
    [10.000, 12.500) = 31 
    [12.500, 15.000) = 114 
    [15.000, 17.500) = 15 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.593 ms/op
     p(50.0000) =      2.974 ms/op
     p(90.0000) =      3.514 ms/op
     p(95.0000) =      3.740 ms/op
     p(99.0000) =      4.424 ms/op
     p(99.9000) =      7.370 ms/op
     p(99.9900) =     28.904 ms/op
     p(99.9990) =     29.813 ms/op
     p(99.9999) =     29.950 ms/op
    p(100.0000) =     29.950 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 4.019 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 2.953 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.904 ±(99.9%) 0.005 ms/op
Iteration   1: 2.903 ±(99.9%) 0.004 ms/op
                 existUser·p0.00:   0.988 ms/op
                 existUser·p0.50:   2.855 ms/op
                 existUser·p0.90:   3.359 ms/op
                 existUser·p0.95:   3.613 ms/op
                 existUser·p0.99:   3.879 ms/op
                 existUser·p0.999:  7.625 ms/op
                 existUser·p0.9999: 12.386 ms/op
                 existUser·p1.00:   12.648 ms/op

Iteration   2: 2.918 ±(99.9%) 0.004 ms/op
                 existUser·p0.00:   0.870 ms/op
                 existUser·p0.50:   2.888 ms/op
                 existUser·p0.90:   3.375 ms/op
                 existUser·p0.95:   3.527 ms/op
                 existUser·p0.99:   3.953 ms/op
                 existUser·p0.999:  6.033 ms/op
                 existUser·p0.9999: 12.977 ms/op
                 existUser·p1.00:   13.238 ms/op

Iteration   3: 2.880 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.772 ms/op
                 existUser·p0.50:   2.863 ms/op
                 existUser·p0.90:   3.285 ms/op
                 existUser·p0.95:   3.412 ms/op
                 existUser·p0.99:   4.022 ms/op
                 existUser·p0.999:  9.060 ms/op
                 existUser·p0.9999: 24.156 ms/op
                 existUser·p1.00:   24.904 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 331105
  mean =      2.900 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 40550 
    [ 2.500,  5.000) = 289755 
    [ 5.000,  7.500) = 489 
    [ 7.500, 10.000) = 119 
    [10.000, 12.500) = 98 
    [12.500, 15.000) = 62 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.772 ms/op
     p(50.0000) =      2.867 ms/op
     p(90.0000) =      3.338 ms/op
     p(95.0000) =      3.523 ms/op
     p(99.0000) =      3.953 ms/op
     p(99.9000) =      7.070 ms/op
     p(99.9900) =     13.253 ms/op
     p(99.9990) =     24.609 ms/op
     p(99.9999) =     24.904 ms/op
    p(100.0000) =     24.904 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.952 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.094 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.002 ±(99.9%) 0.007 ms/op
Iteration   1: 3.011 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.568 ms/op
                 getUser·p0.50:   2.990 ms/op
                 getUser·p0.90:   3.555 ms/op
                 getUser·p0.95:   3.817 ms/op
                 getUser·p0.99:   4.415 ms/op
                 getUser·p0.999:  8.973 ms/op
                 getUser·p0.9999: 16.843 ms/op
                 getUser·p1.00:   19.268 ms/op

Iteration   2: 3.028 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.308 ms/op
                 getUser·p0.50:   2.990 ms/op
                 getUser·p0.90:   3.572 ms/op
                 getUser·p0.95:   3.744 ms/op
                 getUser·p0.99:   4.465 ms/op
                 getUser·p0.999:  6.868 ms/op
                 getUser·p0.9999: 33.227 ms/op
                 getUser·p1.00:   33.554 ms/op

Iteration   3: 3.020 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.616 ms/op
                 getUser·p0.50:   2.978 ms/op
                 getUser·p0.90:   3.527 ms/op
                 getUser·p0.95:   3.817 ms/op
                 getUser·p0.99:   4.833 ms/op
                 getUser·p0.999:  9.523 ms/op
                 getUser·p0.9999: 21.345 ms/op
                 getUser·p1.00:   21.692 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 318058
  mean =      3.020 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 28975 
    [ 2.500,  5.000) = 287525 
    [ 5.000,  7.500) = 1176 
    [ 7.500, 10.000) = 125 
    [10.000, 12.500) = 19 
    [12.500, 15.000) = 46 
    [15.000, 17.500) = 63 
    [17.500, 20.000) = 69 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 29 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.308 ms/op
     p(50.0000) =      2.986 ms/op
     p(90.0000) =      3.555 ms/op
     p(95.0000) =      3.785 ms/op
     p(99.0000) =      4.604 ms/op
     p(99.9000) =      8.995 ms/op
     p(99.9900) =     32.381 ms/op
     p(99.9990) =     33.477 ms/op
     p(99.9999) =     33.554 ms/op
    p(100.0000) =     33.554 ms/op


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
# Warmup Iteration   1: 5.214 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 4.046 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.911 ±(99.9%) 0.010 ms/op
Iteration   1: 3.881 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.079 ms/op
                 listUser·p0.50:   3.727 ms/op
                 listUser·p0.90:   4.874 ms/op
                 listUser·p0.95:   5.439 ms/op
                 listUser·p0.99:   6.799 ms/op
                 listUser·p0.999:  13.049 ms/op
                 listUser·p0.9999: 15.995 ms/op
                 listUser·p1.00:   16.187 ms/op

Iteration   2: 3.891 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.176 ms/op
                 listUser·p0.50:   3.748 ms/op
                 listUser·p0.90:   4.833 ms/op
                 listUser·p0.95:   5.743 ms/op
                 listUser·p0.99:   6.693 ms/op
                 listUser·p0.999:  14.513 ms/op
                 listUser·p0.9999: 21.311 ms/op
                 listUser·p1.00:   21.561 ms/op

Iteration   3: 3.863 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.352 ms/op
                 listUser·p0.50:   3.711 ms/op
                 listUser·p0.90:   4.817 ms/op
                 listUser·p0.95:   5.718 ms/op
                 listUser·p0.99:   6.742 ms/op
                 listUser·p0.999:  15.583 ms/op
                 listUser·p0.9999: 25.259 ms/op
                 listUser·p1.00:   26.083 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 247610
  mean =      3.879 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3615 
    [ 2.500,  5.000) = 222600 
    [ 5.000,  7.500) = 20292 
    [ 7.500, 10.000) = 688 
    [10.000, 12.500) = 52 
    [12.500, 15.000) = 167 
    [15.000, 17.500) = 121 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      1.079 ms/op
     p(50.0000) =      3.727 ms/op
     p(90.0000) =      4.841 ms/op
     p(95.0000) =      5.644 ms/op
     p(99.0000) =      6.750 ms/op
     p(99.9000) =     14.260 ms/op
     p(99.9900) =     24.117 ms/op
     p(99.9990) =     25.860 ms/op
     p(99.9999) =     26.083 ms/op
    p(100.0000) =     26.083 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.653 ± 2.808  ops/ms
ClientGrpc.existUser                       thrpt       3  11.179 ± 0.606  ops/ms
ClientGrpc.getUser                         thrpt       3  10.725 ± 1.077  ops/ms
ClientGrpc.listUser                        thrpt       3   8.202 ± 1.716  ops/ms
ClientGrpc.createUser                       avgt       3   2.953 ± 0.432   ms/op
ClientGrpc.existUser                        avgt       3   2.894 ± 0.484   ms/op
ClientGrpc.getUser                          avgt       3   2.984 ± 0.535   ms/op
ClientGrpc.listUser                         avgt       3   3.907 ± 0.470   ms/op
ClientGrpc.createUser                     sample  319348   3.005 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.593           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.974           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.514           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.740           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.424           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.370           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          28.904           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          29.950           ms/op
ClientGrpc.existUser                      sample  331105   2.900 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.772           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.867           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.338           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.523           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           3.953           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.070           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          13.253           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          24.904           ms/op
ClientGrpc.getUser                        sample  318058   3.020 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.308           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.986           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.555           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.785           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.604           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.995           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          32.381           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          33.554           ms/op
ClientGrpc.listUser                       sample  247610   3.879 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.079           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.727           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.841           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.644           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.750           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.260           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.117           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.083           ms/op
