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
# Warmup Iteration   1: 3.817 ops/ms
# Warmup Iteration   2: 7.829 ops/ms
# Warmup Iteration   3: 9.739 ops/ms
Iteration   1: 10.235 ops/ms
Iteration   2: 10.281 ops/ms
Iteration   3: 10.272 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.263 ±(99.9%) 0.445 ops/ms [Average]
  (min, avg, max) = (10.235, 10.263, 10.281), stdev = 0.024
  CI (99.9%): [9.817, 10.708] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.105 ops/ms
# Warmup Iteration   2: 10.303 ops/ms
# Warmup Iteration   3: 10.829 ops/ms
Iteration   1: 11.114 ops/ms
Iteration   2: 10.915 ops/ms
Iteration   3: 10.977 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.002 ±(99.9%) 1.862 ops/ms [Average]
  (min, avg, max) = (10.915, 11.002, 11.114), stdev = 0.102
  CI (99.9%): [9.140, 12.864] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 6.144 ops/ms
# Warmup Iteration   2: 9.589 ops/ms
# Warmup Iteration   3: 10.134 ops/ms
Iteration   1: 10.330 ops/ms
Iteration   2: 10.234 ops/ms
Iteration   3: 10.299 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.288 ±(99.9%) 0.891 ops/ms [Average]
  (min, avg, max) = (10.234, 10.288, 10.330), stdev = 0.049
  CI (99.9%): [9.396, 11.179] (assumes normal distribution)


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
# Warmup Iteration   1: 4.794 ops/ms
# Warmup Iteration   2: 7.497 ops/ms
# Warmup Iteration   3: 7.927 ops/ms
Iteration   1: 8.057 ops/ms
Iteration   2: 8.095 ops/ms
Iteration   3: 8.070 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.074 ±(99.9%) 0.352 ops/ms [Average]
  (min, avg, max) = (8.057, 8.074, 8.095), stdev = 0.019
  CI (99.9%): [7.722, 8.425] (assumes normal distribution)


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
# Warmup Iteration   1: 4.390 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.186 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.056 ±(99.9%) 0.003 ms/op
Iteration   1: 3.093 ±(99.9%) 0.022 ms/op
Iteration   2: 3.043 ±(99.9%) 0.002 ms/op
Iteration   3: 3.109 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.081 ±(99.9%) 0.627 ms/op [Average]
  (min, avg, max) = (3.043, 3.081, 3.109), stdev = 0.034
  CI (99.9%): [2.454, 3.709] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 4.126 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.965 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 2.871 ±(99.9%) 0.003 ms/op
Iteration   1: 2.833 ±(99.9%) 0.002 ms/op
Iteration   2: 2.937 ±(99.9%) 0.002 ms/op
Iteration   3: 2.965 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.912 ±(99.9%) 1.267 ms/op [Average]
  (min, avg, max) = (2.833, 2.912, 2.965), stdev = 0.069
  CI (99.9%): [1.645, 4.179] (assumes normal distribution)


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
# Warmup Iteration   1: 4.287 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.131 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.108 ±(99.9%) 0.006 ms/op
Iteration   1: 3.019 ±(99.9%) 0.004 ms/op
Iteration   2: 3.068 ±(99.9%) 0.002 ms/op
Iteration   3: 3.076 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.054 ±(99.9%) 0.563 ms/op [Average]
  (min, avg, max) = (3.019, 3.054, 3.076), stdev = 0.031
  CI (99.9%): [2.491, 3.618] (assumes normal distribution)


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
# Warmup Iteration   1: 5.340 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 4.131 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.989 ±(99.9%) 0.035 ms/op
Iteration   1: 3.982 ±(99.9%) 0.022 ms/op
Iteration   2: 4.014 ±(99.9%) 0.022 ms/op
Iteration   3: 3.947 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.981 ±(99.9%) 0.607 ms/op [Average]
  (min, avg, max) = (3.947, 3.981, 4.014), stdev = 0.033
  CI (99.9%): [3.374, 4.589] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.223 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.196 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.099 ±(99.9%) 0.007 ms/op
Iteration   1: 3.060 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.733 ms/op
                 createUser·p0.50:   3.031 ms/op
                 createUser·p0.90:   3.629 ms/op
                 createUser·p0.95:   3.850 ms/op
                 createUser·p0.99:   4.760 ms/op
                 createUser·p0.999:  9.206 ms/op
                 createUser·p0.9999: 12.362 ms/op
                 createUser·p1.00:   12.665 ms/op

Iteration   2: 3.007 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.858 ms/op
                 createUser·p0.50:   2.990 ms/op
                 createUser·p0.90:   3.469 ms/op
                 createUser·p0.95:   3.703 ms/op
                 createUser·p0.99:   4.678 ms/op
                 createUser·p0.999:  8.004 ms/op
                 createUser·p0.9999: 14.303 ms/op
                 createUser·p1.00:   14.565 ms/op

Iteration   3: 3.027 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.745 ms/op
                 createUser·p0.50:   2.982 ms/op
                 createUser·p0.90:   3.441 ms/op
                 createUser·p0.95:   3.760 ms/op
                 createUser·p0.99:   4.987 ms/op
                 createUser·p0.999:  10.698 ms/op
                 createUser·p0.9999: 22.381 ms/op
                 createUser·p1.00:   23.822 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 316538
  mean =      3.031 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24627 
    [ 2.500,  5.000) = 289467 
    [ 5.000,  7.500) = 1715 
    [ 7.500, 10.000) = 464 
    [10.000, 12.500) = 100 
    [12.500, 15.000) = 105 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.733 ms/op
     p(50.0000) =      2.998 ms/op
     p(90.0000) =      3.523 ms/op
     p(95.0000) =      3.789 ms/op
     p(99.0000) =      4.817 ms/op
     p(99.9000) =      9.248 ms/op
     p(99.9900) =     21.856 ms/op
     p(99.9990) =     23.489 ms/op
     p(99.9999) =     23.822 ms/op
    p(100.0000) =     23.822 ms/op


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
# Warmup Iteration   1: 3.988 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.063 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.952 ±(99.9%) 0.006 ms/op
Iteration   1: 3.005 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.797 ms/op
                 existUser·p0.50:   2.961 ms/op
                 existUser·p0.90:   3.543 ms/op
                 existUser·p0.95:   3.748 ms/op
                 existUser·p0.99:   4.484 ms/op
                 existUser·p0.999:  8.077 ms/op
                 existUser·p0.9999: 16.433 ms/op
                 existUser·p1.00:   17.990 ms/op

Iteration   2: 2.929 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.678 ms/op
                 existUser·p0.50:   2.916 ms/op
                 existUser·p0.90:   3.400 ms/op
                 existUser·p0.95:   3.613 ms/op
                 existUser·p0.99:   4.481 ms/op
                 existUser·p0.999:  11.466 ms/op
                 existUser·p0.9999: 22.479 ms/op
                 existUser·p1.00:   22.643 ms/op

Iteration   3: 2.991 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.836 ms/op
                 existUser·p0.50:   2.949 ms/op
                 existUser·p0.90:   3.437 ms/op
                 existUser·p0.95:   3.576 ms/op
                 existUser·p0.99:   4.190 ms/op
                 existUser·p0.999:  7.880 ms/op
                 existUser·p0.9999: 24.595 ms/op
                 existUser·p1.00:   25.035 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 322798
  mean =      2.975 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 28654 
    [ 2.500,  5.000) = 292256 
    [ 5.000,  7.500) = 1339 
    [ 7.500, 10.000) = 291 
    [10.000, 12.500) = 85 
    [12.500, 15.000) = 76 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 36 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.678 ms/op
     p(50.0000) =      2.945 ms/op
     p(90.0000) =      3.453 ms/op
     p(95.0000) =      3.666 ms/op
     p(99.0000) =      4.391 ms/op
     p(99.9000) =      9.093 ms/op
     p(99.9900) =     22.577 ms/op
     p(99.9990) =     24.805 ms/op
     p(99.9999) =     25.035 ms/op
    p(100.0000) =     25.035 ms/op


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
# Warmup Iteration   1: 4.352 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.153 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.077 ±(99.9%) 0.007 ms/op
Iteration   1: 3.062 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.918 ms/op
                 getUser·p0.50:   3.027 ms/op
                 getUser·p0.90:   3.457 ms/op
                 getUser·p0.95:   3.736 ms/op
                 getUser·p0.99:   4.489 ms/op
                 getUser·p0.999:  7.980 ms/op
                 getUser·p0.9999: 19.137 ms/op
                 getUser·p1.00:   19.464 ms/op

Iteration   2: 3.077 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.443 ms/op
                 getUser·p0.50:   3.027 ms/op
                 getUser·p0.90:   3.666 ms/op
                 getUser·p0.95:   3.928 ms/op
                 getUser·p0.99:   5.163 ms/op
                 getUser·p0.999:  8.330 ms/op
                 getUser·p0.9999: 15.067 ms/op
                 getUser·p1.00:   15.221 ms/op

Iteration   3: 3.032 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.506 ms/op
                 getUser·p0.50:   3.015 ms/op
                 getUser·p0.90:   3.428 ms/op
                 getUser·p0.95:   3.629 ms/op
                 getUser·p0.99:   4.850 ms/op
                 getUser·p0.999:  8.008 ms/op
                 getUser·p0.9999: 17.054 ms/op
                 getUser·p1.00:   17.302 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 313953
  mean =      3.057 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 643 
    [ 1.250,  2.500) = 18079 
    [ 2.500,  3.750) = 277747 
    [ 3.750,  5.000) = 14835 
    [ 5.000,  6.250) = 1474 
    [ 6.250,  7.500) = 646 
    [ 7.500,  8.750) = 272 
    [ 8.750, 10.000) = 33 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 30 
    [13.750, 15.000) = 52 
    [15.000, 16.250) = 23 
    [16.250, 17.500) = 23 
    [17.500, 18.750) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.443 ms/op
     p(50.0000) =      3.023 ms/op
     p(90.0000) =      3.514 ms/op
     p(95.0000) =      3.797 ms/op
     p(99.0000) =      4.874 ms/op
     p(99.9000) =      8.102 ms/op
     p(99.9900) =     18.186 ms/op
     p(99.9990) =     19.324 ms/op
     p(99.9999) =     19.464 ms/op
    p(100.0000) =     19.464 ms/op


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
# Warmup Iteration   1: 5.834 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 4.100 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.977 ±(99.9%) 0.011 ms/op
Iteration   1: 3.942 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.323 ms/op
                 listUser·p0.50:   3.768 ms/op
                 listUser·p0.90:   5.063 ms/op
                 listUser·p0.95:   5.554 ms/op
                 listUser·p0.99:   7.078 ms/op
                 listUser·p0.999:  13.402 ms/op
                 listUser·p0.9999: 20.723 ms/op
                 listUser·p1.00:   21.332 ms/op

Iteration   2: 3.912 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.882 ms/op
                 listUser·p0.50:   3.785 ms/op
                 listUser·p0.90:   4.489 ms/op
                 listUser·p0.95:   5.439 ms/op
                 listUser·p0.99:   6.914 ms/op
                 listUser·p0.999:  14.691 ms/op
                 listUser·p0.9999: 23.385 ms/op
                 listUser·p1.00:   23.790 ms/op

Iteration   3: 3.965 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.143 ms/op
                 listUser·p0.50:   3.785 ms/op
                 listUser·p0.90:   5.120 ms/op
                 listUser·p0.95:   5.751 ms/op
                 listUser·p0.99:   7.045 ms/op
                 listUser·p0.999:  15.578 ms/op
                 listUser·p0.9999: 19.298 ms/op
                 listUser·p1.00:   19.825 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 243633
  mean =      3.940 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3473 
    [ 2.500,  5.000) = 216644 
    [ 5.000,  7.500) = 21981 
    [ 7.500, 10.000) = 1050 
    [10.000, 12.500) = 92 
    [12.500, 15.000) = 166 
    [15.000, 17.500) = 130 
    [17.500, 20.000) = 57 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.882 ms/op
     p(50.0000) =      3.781 ms/op
     p(90.0000) =      4.964 ms/op
     p(95.0000) =      5.595 ms/op
     p(99.0000) =      7.012 ms/op
     p(99.9000) =     14.860 ms/op
     p(99.9900) =     22.631 ms/op
     p(99.9990) =     23.677 ms/op
     p(99.9999) =     23.790 ms/op
    p(100.0000) =     23.790 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.263 ± 0.445  ops/ms
ClientGrpc.existUser                       thrpt       3  11.002 ± 1.862  ops/ms
ClientGrpc.getUser                         thrpt       3  10.288 ± 0.891  ops/ms
ClientGrpc.listUser                        thrpt       3   8.074 ± 0.352  ops/ms
ClientGrpc.createUser                       avgt       3   3.081 ± 0.627   ms/op
ClientGrpc.existUser                        avgt       3   2.912 ± 1.267   ms/op
ClientGrpc.getUser                          avgt       3   3.054 ± 0.563   ms/op
ClientGrpc.listUser                         avgt       3   3.981 ± 0.607   ms/op
ClientGrpc.createUser                     sample  316538   3.031 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.733           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.998           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.523           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.789           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.817           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.248           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.856           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.822           ms/op
ClientGrpc.existUser                      sample  322798   2.975 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.678           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.945           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.453           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.666           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.391           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.093           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          22.577           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          25.035           ms/op
ClientGrpc.getUser                        sample  313953   3.057 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.443           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.023           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.514           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.797           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.874           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.102           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.186           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.464           ms/op
ClientGrpc.listUser                       sample  243633   3.940 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.882           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.781           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.964           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.595           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.012           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.860           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.631           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.790           ms/op
