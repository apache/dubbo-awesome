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
# Warmup Iteration   1: 4.501 ops/ms
# Warmup Iteration   2: 9.571 ops/ms
# Warmup Iteration   3: 11.103 ops/ms
Iteration   1: 11.536 ops/ms
Iteration   2: 10.859 ops/ms
Iteration   3: 10.987 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  11.128 ±(99.9%) 6.563 ops/ms [Average]
  (min, avg, max) = (10.859, 11.128, 11.536), stdev = 0.360
  CI (99.9%): [4.565, 17.690] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 8.404 ops/ms
# Warmup Iteration   2: 10.132 ops/ms
# Warmup Iteration   3: 10.660 ops/ms
Iteration   1: 10.552 ops/ms
Iteration   2: 11.053 ops/ms
Iteration   3: 10.267 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.624 ±(99.9%) 7.256 ops/ms [Average]
  (min, avg, max) = (10.267, 10.624, 11.053), stdev = 0.398
  CI (99.9%): [3.368, 17.879] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 6.632 ops/ms
# Warmup Iteration   2: 9.699 ops/ms
# Warmup Iteration   3: 9.877 ops/ms
Iteration   1: 10.005 ops/ms
Iteration   2: 9.996 ops/ms
Iteration   3: 9.843 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.948 ±(99.9%) 1.667 ops/ms [Average]
  (min, avg, max) = (9.843, 9.948, 10.005), stdev = 0.091
  CI (99.9%): [8.281, 11.615] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.332 ops/ms
# Warmup Iteration   2: 7.608 ops/ms
# Warmup Iteration   3: 7.803 ops/ms
Iteration   1: 7.797 ops/ms
Iteration   2: 7.763 ops/ms
Iteration   3: 8.017 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.859 ±(99.9%) 2.520 ops/ms [Average]
  (min, avg, max) = (7.763, 7.859, 8.017), stdev = 0.138
  CI (99.9%): [5.339, 10.379] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.495 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.233 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.220 ±(99.9%) 0.002 ms/op
Iteration   1: 3.048 ±(99.9%) 0.002 ms/op
Iteration   2: 3.110 ±(99.9%) 0.002 ms/op
Iteration   3: 3.003 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.053 ±(99.9%) 0.980 ms/op [Average]
  (min, avg, max) = (3.003, 3.053, 3.110), stdev = 0.054
  CI (99.9%): [2.074, 4.033] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.782 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.959 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.904 ±(99.9%) 0.002 ms/op
Iteration   1: 2.913 ±(99.9%) 0.002 ms/op
Iteration   2: 2.861 ±(99.9%) 0.002 ms/op
Iteration   3: 2.885 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.886 ±(99.9%) 0.469 ms/op [Average]
  (min, avg, max) = (2.861, 2.886, 2.913), stdev = 0.026
  CI (99.9%): [2.417, 3.355] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.853 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.037 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.050 ±(99.9%) 0.004 ms/op
Iteration   1: 2.957 ±(99.9%) 0.002 ms/op
Iteration   2: 3.040 ±(99.9%) 0.003 ms/op
Iteration   3: 2.954 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.984 ±(99.9%) 0.885 ms/op [Average]
  (min, avg, max) = (2.954, 2.984, 3.040), stdev = 0.049
  CI (99.9%): [2.099, 3.869] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 5.443 ±(99.9%) 0.076 ms/op
# Warmup Iteration   2: 4.038 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.830 ±(99.9%) 0.011 ms/op
Iteration   1: 3.751 ±(99.9%) 0.021 ms/op
Iteration   2: 3.905 ±(99.9%) 0.012 ms/op
Iteration   3: 3.787 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.815 ±(99.9%) 1.475 ms/op [Average]
  (min, avg, max) = (3.751, 3.815, 3.905), stdev = 0.081
  CI (99.9%): [2.339, 5.290] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.156 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.071 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.974 ±(99.9%) 0.006 ms/op
Iteration   1: 3.074 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.800 ms/op
                 createUser·p0.50:   3.056 ms/op
                 createUser·p0.90:   3.752 ms/op
                 createUser·p0.95:   3.899 ms/op
                 createUser·p0.99:   4.219 ms/op
                 createUser·p0.999:  6.372 ms/op
                 createUser·p0.9999: 14.790 ms/op
                 createUser·p1.00:   15.090 ms/op

Iteration   2: 3.013 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.931 ms/op
                 createUser·p0.50:   2.974 ms/op
                 createUser·p0.90:   3.523 ms/op
                 createUser·p0.95:   3.703 ms/op
                 createUser·p0.99:   4.055 ms/op
                 createUser·p0.999:  8.758 ms/op
                 createUser·p0.9999: 15.354 ms/op
                 createUser·p1.00:   15.630 ms/op

Iteration   3: 3.027 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.773 ms/op
                 createUser·p0.50:   3.019 ms/op
                 createUser·p0.90:   3.670 ms/op
                 createUser·p0.95:   3.858 ms/op
                 createUser·p0.99:   4.157 ms/op
                 createUser·p0.999:  10.720 ms/op
                 createUser·p0.9999: 26.083 ms/op
                 createUser·p1.00:   26.903 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 316039
  mean =      3.038 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 37483 
    [ 2.500,  5.000) = 277695 
    [ 5.000,  7.500) = 517 
    [ 7.500, 10.000) = 69 
    [10.000, 12.500) = 90 
    [12.500, 15.000) = 106 
    [15.000, 17.500) = 47 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 30 

  Percentiles, ms/op:
      p(0.0000) =      0.773 ms/op
     p(50.0000) =      3.011 ms/op
     p(90.0000) =      3.662 ms/op
     p(95.0000) =      3.838 ms/op
     p(99.0000) =      4.149 ms/op
     p(99.9000) =      8.003 ms/op
     p(99.9900) =     24.897 ms/op
     p(99.9990) =     26.816 ms/op
     p(99.9999) =     26.903 ms/op
    p(100.0000) =     26.903 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.815 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 2.990 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.858 ±(99.9%) 0.007 ms/op
Iteration   1: 2.876 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.510 ms/op
                 existUser·p0.50:   2.900 ms/op
                 existUser·p0.90:   3.600 ms/op
                 existUser·p0.95:   3.760 ms/op
                 existUser·p0.99:   4.100 ms/op
                 existUser·p0.999:  5.550 ms/op
                 existUser·p0.9999: 19.259 ms/op
                 existUser·p1.00:   20.054 ms/op

Iteration   2: 3.036 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.681 ms/op
                 existUser·p0.50:   3.015 ms/op
                 existUser·p0.90:   3.645 ms/op
                 existUser·p0.95:   3.789 ms/op
                 existUser·p0.99:   4.047 ms/op
                 existUser·p0.999:  10.360 ms/op
                 existUser·p0.9999: 25.557 ms/op
                 existUser·p1.00:   26.083 ms/op

Iteration   3: 2.690 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.605 ms/op
                 existUser·p0.50:   2.732 ms/op
                 existUser·p0.90:   3.527 ms/op
                 existUser·p0.95:   3.707 ms/op
                 existUser·p0.99:   4.063 ms/op
                 existUser·p0.999:  6.176 ms/op
                 existUser·p0.9999: 16.142 ms/op
                 existUser·p1.00:   18.547 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 335625
  mean =      2.860 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 81787 
    [ 2.500,  5.000) = 253025 
    [ 5.000,  7.500) = 540 
    [ 7.500, 10.000) = 58 
    [10.000, 12.500) = 55 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 72 
    [17.500, 20.000) = 55 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.510 ms/op
     p(50.0000) =      2.884 ms/op
     p(90.0000) =      3.596 ms/op
     p(95.0000) =      3.756 ms/op
     p(99.0000) =      4.071 ms/op
     p(99.9000) =      6.652 ms/op
     p(99.9900) =     20.017 ms/op
     p(99.9990) =     25.962 ms/op
     p(99.9999) =     26.083 ms/op
    p(100.0000) =     26.083 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.869 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.002 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.009 ±(99.9%) 0.008 ms/op
Iteration   1: 3.197 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.538 ms/op
                 getUser·p0.50:   3.154 ms/op
                 getUser·p0.90:   3.854 ms/op
                 getUser·p0.95:   4.055 ms/op
                 getUser·p0.99:   4.815 ms/op
                 getUser·p0.999:  9.469 ms/op
                 getUser·p0.9999: 25.723 ms/op
                 getUser·p1.00:   25.952 ms/op

Iteration   2: 3.160 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.774 ms/op
                 getUser·p0.50:   3.125 ms/op
                 getUser·p0.90:   3.793 ms/op
                 getUser·p0.95:   4.006 ms/op
                 getUser·p0.99:   4.407 ms/op
                 getUser·p0.999:  7.286 ms/op
                 getUser·p0.9999: 24.994 ms/op
                 getUser·p1.00:   25.035 ms/op

Iteration   3: 3.207 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.726 ms/op
                 getUser·p0.50:   3.162 ms/op
                 getUser·p0.90:   3.920 ms/op
                 getUser·p0.95:   4.108 ms/op
                 getUser·p0.99:   4.506 ms/op
                 getUser·p0.999:  8.706 ms/op
                 getUser·p0.9999: 27.461 ms/op
                 getUser·p1.00:   30.343 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 300901
  mean =      3.188 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19879 
    [ 2.500,  5.000) = 279243 
    [ 5.000,  7.500) = 1420 
    [ 7.500, 10.000) = 116 
    [10.000, 12.500) = 40 
    [12.500, 15.000) = 11 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 71 
    [25.000, 27.500) = 85 
    [27.500, 30.000) = 4 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.538 ms/op
     p(50.0000) =      3.146 ms/op
     p(90.0000) =      3.858 ms/op
     p(95.0000) =      4.059 ms/op
     p(99.0000) =      4.522 ms/op
     p(99.9000) =      8.176 ms/op
     p(99.9900) =     26.804 ms/op
     p(99.9990) =     30.015 ms/op
     p(99.9999) =     30.343 ms/op
    p(100.0000) =     30.343 ms/op


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
# Warmup Iteration   1: 5.108 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.004 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.067 ±(99.9%) 0.011 ms/op
Iteration   1: 3.922 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.311 ms/op
                 listUser·p0.50:   3.785 ms/op
                 listUser·p0.90:   4.940 ms/op
                 listUser·p0.95:   5.587 ms/op
                 listUser·p0.99:   7.004 ms/op
                 listUser·p0.999:  13.440 ms/op
                 listUser·p0.9999: 21.386 ms/op
                 listUser·p1.00:   21.856 ms/op

Iteration   2: 4.050 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.329 ms/op
                 listUser·p0.50:   3.891 ms/op
                 listUser·p0.90:   5.104 ms/op
                 listUser·p0.95:   5.825 ms/op
                 listUser·p0.99:   7.135 ms/op
                 listUser·p0.999:  15.467 ms/op
                 listUser·p0.9999: 17.072 ms/op
                 listUser·p1.00:   17.957 ms/op

Iteration   3: 4.017 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.233 ms/op
                 listUser·p0.50:   3.858 ms/op
                 listUser·p0.90:   5.022 ms/op
                 listUser·p0.95:   5.833 ms/op
                 listUser·p0.99:   6.922 ms/op
                 listUser·p0.999:  16.093 ms/op
                 listUser·p0.9999: 19.825 ms/op
                 listUser·p1.00:   20.382 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 240395
  mean =      3.995 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1806 
    [ 2.500,  5.000) = 214102 
    [ 5.000,  7.500) = 23143 
    [ 7.500, 10.000) = 948 
    [10.000, 12.500) = 51 
    [12.500, 15.000) = 77 
    [15.000, 17.500) = 170 
    [17.500, 20.000) = 75 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.233 ms/op
     p(50.0000) =      3.842 ms/op
     p(90.0000) =      5.022 ms/op
     p(95.0000) =      5.751 ms/op
     p(99.0000) =      7.021 ms/op
     p(99.9000) =     15.352 ms/op
     p(99.9900) =     19.987 ms/op
     p(99.9990) =     21.751 ms/op
     p(99.9999) =     21.856 ms/op
    p(100.0000) =     21.856 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  11.128 ± 6.563  ops/ms
ClientGrpc.existUser                       thrpt       3  10.624 ± 7.256  ops/ms
ClientGrpc.getUser                         thrpt       3   9.948 ± 1.667  ops/ms
ClientGrpc.listUser                        thrpt       3   7.859 ± 2.520  ops/ms
ClientGrpc.createUser                       avgt       3   3.053 ± 0.980   ms/op
ClientGrpc.existUser                        avgt       3   2.886 ± 0.469   ms/op
ClientGrpc.getUser                          avgt       3   2.984 ± 0.885   ms/op
ClientGrpc.listUser                         avgt       3   3.815 ± 1.475   ms/op
ClientGrpc.createUser                     sample  316039   3.038 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.773           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.011           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.662           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.838           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.149           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.003           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          24.897           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          26.903           ms/op
ClientGrpc.existUser                      sample  335625   2.860 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.510           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.884           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.596           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.756           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.071           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.652           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.017           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          26.083           ms/op
ClientGrpc.getUser                        sample  300901   3.188 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.538           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.146           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.858           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.059           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.522           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.176           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          26.804           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          30.343           ms/op
ClientGrpc.listUser                       sample  240395   3.995 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.233           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.842           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.022           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.751           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.021           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.352           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          19.987           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          21.856           ms/op
