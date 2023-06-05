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
# Warmup Iteration   1: 4.394 ops/ms
# Warmup Iteration   2: 9.579 ops/ms
# Warmup Iteration   3: 9.984 ops/ms
Iteration   1: 10.814 ops/ms
Iteration   2: 10.511 ops/ms
Iteration   3: 10.687 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.671 ±(99.9%) 2.777 ops/ms [Average]
  (min, avg, max) = (10.511, 10.671, 10.814), stdev = 0.152
  CI (99.9%): [7.894, 13.447] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 8.576 ops/ms
# Warmup Iteration   2: 10.625 ops/ms
# Warmup Iteration   3: 11.079 ops/ms
Iteration   1: 10.960 ops/ms
Iteration   2: 11.125 ops/ms
Iteration   3: 10.862 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.983 ±(99.9%) 2.425 ops/ms [Average]
  (min, avg, max) = (10.862, 10.983, 11.125), stdev = 0.133
  CI (99.9%): [8.557, 13.408] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.497 ops/ms
# Warmup Iteration   2: 10.493 ops/ms
# Warmup Iteration   3: 10.528 ops/ms
Iteration   1: 10.600 ops/ms
Iteration   2: 10.594 ops/ms
Iteration   3: 10.390 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.528 ±(99.9%) 2.181 ops/ms [Average]
  (min, avg, max) = (10.390, 10.528, 10.600), stdev = 0.120
  CI (99.9%): [8.347, 12.709] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 5.549 ops/ms
# Warmup Iteration   2: 7.899 ops/ms
# Warmup Iteration   3: 8.067 ops/ms
Iteration   1: 8.072 ops/ms
Iteration   2: 7.993 ops/ms
Iteration   3: 8.221 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.095 ±(99.9%) 2.108 ops/ms [Average]
  (min, avg, max) = (7.993, 8.095, 8.221), stdev = 0.116
  CI (99.9%): [5.987, 10.203] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 4.070 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.142 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.071 ±(99.9%) 0.004 ms/op
Iteration   1: 3.037 ±(99.9%) 0.002 ms/op
Iteration   2: 2.986 ±(99.9%) 0.003 ms/op
Iteration   3: 2.965 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.996 ±(99.9%) 0.670 ms/op [Average]
  (min, avg, max) = (2.965, 2.996, 3.037), stdev = 0.037
  CI (99.9%): [2.326, 3.666] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.405 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.015 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.914 ±(99.9%) 0.005 ms/op
Iteration   1: 2.847 ±(99.9%) 0.004 ms/op
Iteration   2: 2.928 ±(99.9%) 0.003 ms/op
Iteration   3: 2.781 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.852 ±(99.9%) 1.346 ms/op [Average]
  (min, avg, max) = (2.781, 2.852, 2.928), stdev = 0.074
  CI (99.9%): [1.506, 4.199] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.953 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.170 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.059 ±(99.9%) 0.003 ms/op
Iteration   1: 3.011 ±(99.9%) 0.009 ms/op
Iteration   2: 3.036 ±(99.9%) 0.002 ms/op
Iteration   3: 3.032 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.026 ±(99.9%) 0.245 ms/op [Average]
  (min, avg, max) = (3.011, 3.026, 3.036), stdev = 0.013
  CI (99.9%): [2.781, 3.271] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 5.218 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 4.136 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.020 ±(99.9%) 0.014 ms/op
Iteration   1: 3.954 ±(99.9%) 0.015 ms/op
Iteration   2: 3.934 ±(99.9%) 0.022 ms/op
Iteration   3: 3.797 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.895 ±(99.9%) 1.552 ms/op [Average]
  (min, avg, max) = (3.797, 3.895, 3.954), stdev = 0.085
  CI (99.9%): [2.343, 5.447] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.016 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.215 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.063 ±(99.9%) 0.007 ms/op
Iteration   1: 3.041 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.682 ms/op
                 createUser·p0.50:   3.019 ms/op
                 createUser·p0.90:   3.568 ms/op
                 createUser·p0.95:   3.793 ms/op
                 createUser·p0.99:   4.440 ms/op
                 createUser·p0.999:  7.317 ms/op
                 createUser·p0.9999: 15.154 ms/op
                 createUser·p1.00:   15.598 ms/op

Iteration   2: 3.023 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.565 ms/op
                 createUser·p0.50:   3.019 ms/op
                 createUser·p0.90:   3.596 ms/op
                 createUser·p0.95:   3.813 ms/op
                 createUser·p0.99:   4.563 ms/op
                 createUser·p0.999:  8.234 ms/op
                 createUser·p0.9999: 32.585 ms/op
                 createUser·p1.00:   34.079 ms/op

Iteration   3: 3.042 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.324 ms/op
                 createUser·p0.50:   3.015 ms/op
                 createUser·p0.90:   3.383 ms/op
                 createUser·p0.95:   3.555 ms/op
                 createUser·p0.99:   4.235 ms/op
                 createUser·p0.999:  11.670 ms/op
                 createUser·p0.9999: 30.900 ms/op
                 createUser·p1.00:   31.064 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 316292
  mean =      3.035 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23441 
    [ 2.500,  5.000) = 291407 
    [ 5.000,  7.500) = 995 
    [ 7.500, 10.000) = 69 
    [10.000, 12.500) = 165 
    [12.500, 15.000) = 100 
    [15.000, 17.500) = 19 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 48 
    [32.500, 35.000) = 16 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.324 ms/op
     p(50.0000) =      3.019 ms/op
     p(90.0000) =      3.518 ms/op
     p(95.0000) =      3.748 ms/op
     p(99.0000) =      4.465 ms/op
     p(99.9000) =     11.267 ms/op
     p(99.9900) =     31.383 ms/op
     p(99.9990) =     34.013 ms/op
     p(99.9999) =     34.079 ms/op
    p(100.0000) =     34.079 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.871 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 2.942 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.872 ±(99.9%) 0.006 ms/op
Iteration   1: 2.913 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.569 ms/op
                 existUser·p0.50:   2.888 ms/op
                 existUser·p0.90:   3.351 ms/op
                 existUser·p0.95:   3.596 ms/op
                 existUser·p0.99:   4.121 ms/op
                 existUser·p0.999:  5.632 ms/op
                 existUser·p0.9999: 11.174 ms/op
                 existUser·p1.00:   11.370 ms/op

Iteration   2: 2.921 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.556 ms/op
                 existUser·p0.50:   2.900 ms/op
                 existUser·p0.90:   3.482 ms/op
                 existUser·p0.95:   3.645 ms/op
                 existUser·p0.99:   4.358 ms/op
                 existUser·p0.999:  5.853 ms/op
                 existUser·p0.9999: 18.383 ms/op
                 existUser·p1.00:   19.595 ms/op

Iteration   3: 2.811 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.579 ms/op
                 existUser·p0.50:   2.839 ms/op
                 existUser·p0.90:   3.355 ms/op
                 existUser·p0.95:   3.637 ms/op
                 existUser·p0.99:   4.596 ms/op
                 existUser·p0.999:  7.304 ms/op
                 existUser·p0.9999: 15.231 ms/op
                 existUser·p1.00:   15.679 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 333034
  mean =      2.881 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 4056 
    [ 1.250,  2.500) = 40606 
    [ 2.500,  3.750) = 277746 
    [ 3.750,  5.000) = 9564 
    [ 5.000,  6.250) = 728 
    [ 6.250,  7.500) = 92 
    [ 7.500,  8.750) = 43 
    [ 8.750, 10.000) = 33 
    [10.000, 11.250) = 33 
    [11.250, 12.500) = 31 
    [12.500, 13.750) = 27 
    [13.750, 15.000) = 18 
    [15.000, 16.250) = 25 
    [16.250, 17.500) = 16 
    [17.500, 18.750) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.556 ms/op
     p(50.0000) =      2.875 ms/op
     p(90.0000) =      3.412 ms/op
     p(95.0000) =      3.629 ms/op
     p(99.0000) =      4.415 ms/op
     p(99.9000) =      6.267 ms/op
     p(99.9900) =     15.665 ms/op
     p(99.9990) =     18.579 ms/op
     p(99.9999) =     19.595 ms/op
    p(100.0000) =     19.595 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.018 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.090 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.061 ±(99.9%) 0.007 ms/op
Iteration   1: 3.059 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.804 ms/op
                 getUser·p0.50:   3.039 ms/op
                 getUser·p0.90:   3.588 ms/op
                 getUser·p0.95:   3.785 ms/op
                 getUser·p0.99:   4.399 ms/op
                 getUser·p0.999:  7.077 ms/op
                 getUser·p0.9999: 11.911 ms/op
                 getUser·p1.00:   12.255 ms/op

Iteration   2: 2.992 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.763 ms/op
                 getUser·p0.50:   2.970 ms/op
                 getUser·p0.90:   3.600 ms/op
                 getUser·p0.95:   3.957 ms/op
                 getUser·p0.99:   4.668 ms/op
                 getUser·p0.999:  8.929 ms/op
                 getUser·p0.9999: 12.866 ms/op
                 getUser·p1.00:   13.353 ms/op

Iteration   3: 2.998 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.810 ms/op
                 getUser·p0.50:   2.998 ms/op
                 getUser·p0.90:   3.490 ms/op
                 getUser·p0.95:   3.699 ms/op
                 getUser·p0.99:   4.284 ms/op
                 getUser·p0.999:  7.045 ms/op
                 getUser·p0.9999: 16.308 ms/op
                 getUser·p1.00:   16.712 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 318219
  mean =      3.016 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1138 
    [ 1.250,  2.500) = 27995 
    [ 2.500,  3.750) = 270977 
    [ 3.750,  5.000) = 16905 
    [ 5.000,  6.250) = 545 
    [ 6.250,  7.500) = 322 
    [ 7.500,  8.750) = 78 
    [ 8.750, 10.000) = 35 
    [10.000, 11.250) = 52 
    [11.250, 12.500) = 64 
    [12.500, 13.750) = 44 
    [13.750, 15.000) = 6 
    [15.000, 16.250) = 45 
    [16.250, 17.500) = 13 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.763 ms/op
     p(50.0000) =      3.002 ms/op
     p(90.0000) =      3.559 ms/op
     p(95.0000) =      3.801 ms/op
     p(99.0000) =      4.497 ms/op
     p(99.9000) =      7.609 ms/op
     p(99.9900) =     15.371 ms/op
     p(99.9990) =     16.631 ms/op
     p(99.9999) =     16.712 ms/op
    p(100.0000) =     16.712 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.435 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 4.197 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.009 ±(99.9%) 0.011 ms/op
Iteration   1: 3.989 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.118 ms/op
                 listUser·p0.50:   3.850 ms/op
                 listUser·p0.90:   4.809 ms/op
                 listUser·p0.95:   5.472 ms/op
                 listUser·p0.99:   6.955 ms/op
                 listUser·p0.999:  13.039 ms/op
                 listUser·p0.9999: 19.462 ms/op
                 listUser·p1.00:   19.759 ms/op

Iteration   2: 3.888 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.145 ms/op
                 listUser·p0.50:   3.740 ms/op
                 listUser·p0.90:   4.858 ms/op
                 listUser·p0.95:   5.587 ms/op
                 listUser·p0.99:   6.799 ms/op
                 listUser·p0.999:  14.151 ms/op
                 listUser·p0.9999: 20.840 ms/op
                 listUser·p1.00:   22.675 ms/op

Iteration   3: 3.955 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.169 ms/op
                 listUser·p0.50:   3.838 ms/op
                 listUser·p0.90:   4.817 ms/op
                 listUser·p0.95:   5.628 ms/op
                 listUser·p0.99:   6.808 ms/op
                 listUser·p0.999:  14.125 ms/op
                 listUser·p0.9999: 27.186 ms/op
                 listUser·p1.00:   27.722 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 243351
  mean =      3.943 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2979 
    [ 2.500,  5.000) = 219476 
    [ 5.000,  7.500) = 19773 
    [ 7.500, 10.000) = 696 
    [10.000, 12.500) = 61 
    [12.500, 15.000) = 227 
    [15.000, 17.500) = 42 
    [17.500, 20.000) = 47 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 29 

  Percentiles, ms/op:
      p(0.0000) =      1.118 ms/op
     p(50.0000) =      3.813 ms/op
     p(90.0000) =      4.825 ms/op
     p(95.0000) =      5.562 ms/op
     p(99.0000) =      6.840 ms/op
     p(99.9000) =     13.746 ms/op
     p(99.9900) =     25.286 ms/op
     p(99.9990) =     27.614 ms/op
     p(99.9999) =     27.722 ms/op
    p(100.0000) =     27.722 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.671 ± 2.777  ops/ms
ClientGrpc.existUser                       thrpt       3  10.983 ± 2.425  ops/ms
ClientGrpc.getUser                         thrpt       3  10.528 ± 2.181  ops/ms
ClientGrpc.listUser                        thrpt       3   8.095 ± 2.108  ops/ms
ClientGrpc.createUser                       avgt       3   2.996 ± 0.670   ms/op
ClientGrpc.existUser                        avgt       3   2.852 ± 1.346   ms/op
ClientGrpc.getUser                          avgt       3   3.026 ± 0.245   ms/op
ClientGrpc.listUser                         avgt       3   3.895 ± 1.552   ms/op
ClientGrpc.createUser                     sample  316292   3.035 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.324           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.019           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.518           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.748           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.465           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.267           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          31.383           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          34.079           ms/op
ClientGrpc.existUser                      sample  333034   2.881 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.556           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.875           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.412           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.629           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.415           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.267           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.665           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.595           ms/op
ClientGrpc.getUser                        sample  318219   3.016 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.763           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.002           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.559           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.801           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.497           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.609           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          15.371           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          16.712           ms/op
ClientGrpc.listUser                       sample  243351   3.943 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.118           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.813           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.825           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.562           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.840           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.746           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.286           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.722           ms/op
