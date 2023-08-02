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
# Warmup Iteration   1: 3.978 ops/ms
# Warmup Iteration   2: 9.135 ops/ms
# Warmup Iteration   3: 9.887 ops/ms
Iteration   1: 10.453 ops/ms
Iteration   2: 10.596 ops/ms
Iteration   3: 10.349 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.466 ±(99.9%) 2.259 ops/ms [Average]
  (min, avg, max) = (10.349, 10.466, 10.596), stdev = 0.124
  CI (99.9%): [8.207, 12.725] (assumes normal distribution)


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
# Warmup Iteration   1: 7.178 ops/ms
# Warmup Iteration   2: 10.160 ops/ms
# Warmup Iteration   3: 10.974 ops/ms
Iteration   1: 11.183 ops/ms
Iteration   2: 10.910 ops/ms
Iteration   3: 11.274 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.123 ±(99.9%) 3.455 ops/ms [Average]
  (min, avg, max) = (10.910, 11.123, 11.274), stdev = 0.189
  CI (99.9%): [7.667, 14.578] (assumes normal distribution)


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
# Warmup Iteration   1: 6.977 ops/ms
# Warmup Iteration   2: 10.148 ops/ms
# Warmup Iteration   3: 10.463 ops/ms
Iteration   1: 10.564 ops/ms
Iteration   2: 10.457 ops/ms
Iteration   3: 10.518 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.513 ±(99.9%) 0.981 ops/ms [Average]
  (min, avg, max) = (10.457, 10.513, 10.564), stdev = 0.054
  CI (99.9%): [9.532, 11.494] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.307 ops/ms
# Warmup Iteration   2: 7.610 ops/ms
# Warmup Iteration   3: 7.870 ops/ms
Iteration   1: 7.943 ops/ms
Iteration   2: 8.062 ops/ms
Iteration   3: 8.092 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.032 ±(99.9%) 1.437 ops/ms [Average]
  (min, avg, max) = (7.943, 8.032, 8.092), stdev = 0.079
  CI (99.9%): [6.595, 9.469] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.537 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.245 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.106 ±(99.9%) 0.003 ms/op
Iteration   1: 3.069 ±(99.9%) 0.003 ms/op
Iteration   2: 3.049 ±(99.9%) 0.002 ms/op
Iteration   3: 3.053 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.057 ±(99.9%) 0.194 ms/op [Average]
  (min, avg, max) = (3.049, 3.057, 3.069), stdev = 0.011
  CI (99.9%): [2.864, 3.251] (assumes normal distribution)


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
# Warmup Iteration   1: 3.987 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.051 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.957 ±(99.9%) 0.002 ms/op
Iteration   1: 3.031 ±(99.9%) 0.002 ms/op
Iteration   2: 2.955 ±(99.9%) 0.002 ms/op
Iteration   3: 2.936 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.974 ±(99.9%) 0.914 ms/op [Average]
  (min, avg, max) = (2.936, 2.974, 3.031), stdev = 0.050
  CI (99.9%): [2.060, 3.888] (assumes normal distribution)


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
# Warmup Iteration   1: 4.364 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.169 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.051 ±(99.9%) 0.004 ms/op
Iteration   1: 3.014 ±(99.9%) 0.002 ms/op
Iteration   2: 3.062 ±(99.9%) 0.004 ms/op
Iteration   3: 3.052 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.043 ±(99.9%) 0.466 ms/op [Average]
  (min, avg, max) = (3.014, 3.043, 3.062), stdev = 0.026
  CI (99.9%): [2.577, 3.508] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 5.874 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 4.052 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.991 ±(99.9%) 0.018 ms/op
Iteration   1: 3.961 ±(99.9%) 0.027 ms/op
Iteration   2: 3.978 ±(99.9%) 0.027 ms/op
Iteration   3: 3.951 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.963 ±(99.9%) 0.245 ms/op [Average]
  (min, avg, max) = (3.951, 3.963, 3.978), stdev = 0.013
  CI (99.9%): [3.718, 4.208] (assumes normal distribution)


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
# Warmup Iteration   1: 4.267 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.238 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.092 ±(99.9%) 0.006 ms/op
Iteration   1: 3.039 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.928 ms/op
                 createUser·p0.50:   3.011 ms/op
                 createUser·p0.90:   3.580 ms/op
                 createUser·p0.95:   3.809 ms/op
                 createUser·p0.99:   4.874 ms/op
                 createUser·p0.999:  11.469 ms/op
                 createUser·p0.9999: 12.624 ms/op
                 createUser·p1.00:   12.960 ms/op

Iteration   2: 3.052 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.802 ms/op
                 createUser·p0.50:   3.015 ms/op
                 createUser·p0.90:   3.564 ms/op
                 createUser·p0.95:   3.768 ms/op
                 createUser·p0.99:   4.628 ms/op
                 createUser·p0.999:  8.249 ms/op
                 createUser·p0.9999: 15.278 ms/op
                 createUser·p1.00:   15.696 ms/op

Iteration   3: 3.075 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.715 ms/op
                 createUser·p0.50:   3.039 ms/op
                 createUser·p0.90:   3.654 ms/op
                 createUser·p0.95:   3.846 ms/op
                 createUser·p0.99:   4.711 ms/op
                 createUser·p0.999:  8.798 ms/op
                 createUser·p0.9999: 16.495 ms/op
                 createUser·p1.00:   17.760 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 314099
  mean =      3.055 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 851 
    [ 1.250,  2.500) = 22651 
    [ 2.500,  3.750) = 271241 
    [ 3.750,  5.000) = 16948 
    [ 5.000,  6.250) = 1078 
    [ 6.250,  7.500) = 697 
    [ 7.500,  8.750) = 278 
    [ 8.750, 10.000) = 67 
    [10.000, 11.250) = 20 
    [11.250, 12.500) = 112 
    [12.500, 13.750) = 52 
    [13.750, 15.000) = 41 
    [15.000, 16.250) = 50 
    [16.250, 17.500) = 11 
    [17.500, 18.750) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.715 ms/op
     p(50.0000) =      3.019 ms/op
     p(90.0000) =      3.604 ms/op
     p(95.0000) =      3.809 ms/op
     p(99.0000) =      4.760 ms/op
     p(99.9000) =      9.077 ms/op
     p(99.9900) =     15.647 ms/op
     p(99.9990) =     17.498 ms/op
     p(99.9999) =     17.760 ms/op
    p(100.0000) =     17.760 ms/op


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
# Warmup Iteration   1: 4.161 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.973 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.808 ±(99.9%) 0.007 ms/op
Iteration   1: 3.020 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.779 ms/op
                 existUser·p0.50:   2.982 ms/op
                 existUser·p0.90:   3.527 ms/op
                 existUser·p0.95:   3.670 ms/op
                 existUser·p0.99:   4.547 ms/op
                 existUser·p0.999:  7.946 ms/op
                 existUser·p0.9999: 12.970 ms/op
                 existUser·p1.00:   13.500 ms/op

Iteration   2: 2.861 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.679 ms/op
                 existUser·p0.50:   2.859 ms/op
                 existUser·p0.90:   3.285 ms/op
                 existUser·p0.95:   3.457 ms/op
                 existUser·p0.99:   4.338 ms/op
                 existUser·p0.999:  6.513 ms/op
                 existUser·p0.9999: 14.002 ms/op
                 existUser·p1.00:   14.516 ms/op

Iteration   3: 2.912 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.740 ms/op
                 existUser·p0.50:   2.871 ms/op
                 existUser·p0.90:   3.293 ms/op
                 existUser·p0.95:   3.494 ms/op
                 existUser·p0.99:   4.202 ms/op
                 existUser·p0.999:  7.468 ms/op
                 existUser·p0.9999: 18.089 ms/op
                 existUser·p1.00:   19.399 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 327596
  mean =      2.930 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1299 
    [ 1.250,  2.500) = 35839 
    [ 2.500,  3.750) = 281638 
    [ 3.750,  5.000) = 7151 
    [ 5.000,  6.250) = 857 
    [ 6.250,  7.500) = 512 
    [ 7.500,  8.750) = 89 
    [ 8.750, 10.000) = 50 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 23 
    [12.500, 13.750) = 53 
    [13.750, 15.000) = 23 
    [15.000, 16.250) = 22 
    [16.250, 17.500) = 16 
    [17.500, 18.750) = 20 

  Percentiles, ms/op:
      p(0.0000) =      0.679 ms/op
     p(50.0000) =      2.896 ms/op
     p(90.0000) =      3.396 ms/op
     p(95.0000) =      3.572 ms/op
     p(99.0000) =      4.375 ms/op
     p(99.9000) =      7.373 ms/op
     p(99.9900) =     17.186 ms/op
     p(99.9990) =     19.012 ms/op
     p(99.9999) =     19.399 ms/op
    p(100.0000) =     19.399 ms/op


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
# Warmup Iteration   1: 4.263 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.251 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.130 ±(99.9%) 0.007 ms/op
Iteration   1: 3.074 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.007 ms/op
                 getUser·p0.50:   3.031 ms/op
                 getUser·p0.90:   3.568 ms/op
                 getUser·p0.95:   3.805 ms/op
                 getUser·p0.99:   4.888 ms/op
                 getUser·p0.999:  8.552 ms/op
                 getUser·p0.9999: 12.966 ms/op
                 getUser·p1.00:   13.222 ms/op

Iteration   2: 3.091 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.705 ms/op
                 getUser·p0.50:   3.043 ms/op
                 getUser·p0.90:   3.641 ms/op
                 getUser·p0.95:   3.899 ms/op
                 getUser·p0.99:   4.915 ms/op
                 getUser·p0.999:  7.887 ms/op
                 getUser·p0.9999: 15.172 ms/op
                 getUser·p1.00:   15.516 ms/op

Iteration   3: 3.053 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.667 ms/op
                 getUser·p0.50:   3.015 ms/op
                 getUser·p0.90:   3.543 ms/op
                 getUser·p0.95:   3.756 ms/op
                 getUser·p0.99:   4.741 ms/op
                 getUser·p0.999:  10.390 ms/op
                 getUser·p0.9999: 18.318 ms/op
                 getUser·p1.00:   18.678 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 312420
  mean =      3.073 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 543 
    [ 1.250,  2.500) = 17824 
    [ 2.500,  3.750) = 274847 
    [ 3.750,  5.000) = 16691 
    [ 5.000,  6.250) = 1534 
    [ 6.250,  7.500) = 486 
    [ 7.500,  8.750) = 209 
    [ 8.750, 10.000) = 76 
    [10.000, 11.250) = 45 
    [11.250, 12.500) = 14 
    [12.500, 13.750) = 26 
    [13.750, 15.000) = 57 
    [15.000, 16.250) = 28 
    [16.250, 17.500) = 20 
    [17.500, 18.750) = 20 

  Percentiles, ms/op:
      p(0.0000) =      0.667 ms/op
     p(50.0000) =      3.031 ms/op
     p(90.0000) =      3.584 ms/op
     p(95.0000) =      3.830 ms/op
     p(99.0000) =      4.858 ms/op
     p(99.9000) =      8.618 ms/op
     p(99.9900) =     16.466 ms/op
     p(99.9990) =     18.579 ms/op
     p(99.9999) =     18.678 ms/op
    p(100.0000) =     18.678 ms/op


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
# Warmup Iteration   1: 5.894 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 4.047 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.002 ±(99.9%) 0.012 ms/op
Iteration   1: 3.955 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.892 ms/op
                 listUser·p0.50:   3.801 ms/op
                 listUser·p0.90:   4.768 ms/op
                 listUser·p0.95:   5.521 ms/op
                 listUser·p0.99:   7.135 ms/op
                 listUser·p0.999:  13.420 ms/op
                 listUser·p0.9999: 15.653 ms/op
                 listUser·p1.00:   16.433 ms/op

Iteration   2: 4.015 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.202 ms/op
                 listUser·p0.50:   3.830 ms/op
                 listUser·p0.90:   5.120 ms/op
                 listUser·p0.95:   5.833 ms/op
                 listUser·p0.99:   7.176 ms/op
                 listUser·p0.999:  14.598 ms/op
                 listUser·p0.9999: 16.143 ms/op
                 listUser·p1.00:   18.809 ms/op

Iteration   3: 3.992 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.980 ms/op
                 listUser·p0.50:   3.822 ms/op
                 listUser·p0.90:   5.046 ms/op
                 listUser·p0.95:   5.718 ms/op
                 listUser·p0.99:   6.947 ms/op
                 listUser·p0.999:  16.710 ms/op
                 listUser·p0.9999: 18.645 ms/op
                 listUser·p1.00:   18.907 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 240697
  mean =      3.987 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 20 
    [ 1.250,  2.500) = 2633 
    [ 2.500,  3.750) = 102292 
    [ 3.750,  5.000) = 111954 
    [ 5.000,  6.250) = 17597 
    [ 6.250,  7.500) = 4574 
    [ 7.500,  8.750) = 877 
    [ 8.750, 10.000) = 289 
    [10.000, 11.250) = 85 
    [11.250, 12.500) = 8 
    [12.500, 13.750) = 55 
    [13.750, 15.000) = 122 
    [15.000, 16.250) = 78 
    [16.250, 17.500) = 65 
    [17.500, 18.750) = 41 

  Percentiles, ms/op:
      p(0.0000) =      0.892 ms/op
     p(50.0000) =      3.817 ms/op
     p(90.0000) =      4.989 ms/op
     p(95.0000) =      5.710 ms/op
     p(99.0000) =      7.086 ms/op
     p(99.9000) =     14.390 ms/op
     p(99.9900) =     18.217 ms/op
     p(99.9990) =     18.894 ms/op
     p(99.9999) =     18.907 ms/op
    p(100.0000) =     18.907 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.466 ± 2.259  ops/ms
ClientGrpc.existUser                       thrpt       3  11.123 ± 3.455  ops/ms
ClientGrpc.getUser                         thrpt       3  10.513 ± 0.981  ops/ms
ClientGrpc.listUser                        thrpt       3   8.032 ± 1.437  ops/ms
ClientGrpc.createUser                       avgt       3   3.057 ± 0.194   ms/op
ClientGrpc.existUser                        avgt       3   2.974 ± 0.914   ms/op
ClientGrpc.getUser                          avgt       3   3.043 ± 0.466   ms/op
ClientGrpc.listUser                         avgt       3   3.963 ± 0.245   ms/op
ClientGrpc.createUser                     sample  314099   3.055 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.715           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.019           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.604           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.809           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.760           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.077           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          15.647           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          17.760           ms/op
ClientGrpc.existUser                      sample  327596   2.930 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.679           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.896           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.396           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.572           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.375           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.373           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.186           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.399           ms/op
ClientGrpc.getUser                        sample  312420   3.073 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.667           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.031           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.584           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.830           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.858           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.618           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.466           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.678           ms/op
ClientGrpc.listUser                       sample  240697   3.987 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.892           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.817           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.989           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.710           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.086           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.390           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          18.217           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          18.907           ms/op
