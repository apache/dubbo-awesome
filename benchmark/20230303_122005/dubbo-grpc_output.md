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
# Warmup Iteration   1: 4.089 ops/ms
# Warmup Iteration   2: 8.734 ops/ms
# Warmup Iteration   3: 9.915 ops/ms
Iteration   1: 9.864 ops/ms
Iteration   2: 10.039 ops/ms
Iteration   3: 9.976 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.960 ±(99.9%) 1.610 ops/ms [Average]
  (min, avg, max) = (9.864, 9.960, 10.039), stdev = 0.088
  CI (99.9%): [8.350, 11.569] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 7.011 ops/ms
# Warmup Iteration   2: 9.916 ops/ms
# Warmup Iteration   3: 10.129 ops/ms
Iteration   1: 10.476 ops/ms
Iteration   2: 10.662 ops/ms
Iteration   3: 10.416 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.518 ±(99.9%) 2.341 ops/ms [Average]
  (min, avg, max) = (10.416, 10.518, 10.662), stdev = 0.128
  CI (99.9%): [8.178, 12.859] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 6.609 ops/ms
# Warmup Iteration   2: 9.731 ops/ms
# Warmup Iteration   3: 10.310 ops/ms
Iteration   1: 10.144 ops/ms
Iteration   2: 10.045 ops/ms
Iteration   3: 9.906 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.031 ±(99.9%) 2.179 ops/ms [Average]
  (min, avg, max) = (9.906, 10.031, 10.144), stdev = 0.119
  CI (99.9%): [7.853, 12.210] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.294 ops/ms
# Warmup Iteration   2: 7.479 ops/ms
# Warmup Iteration   3: 7.968 ops/ms
Iteration   1: 7.980 ops/ms
Iteration   2: 7.982 ops/ms
Iteration   3: 8.014 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.992 ±(99.9%) 0.354 ops/ms [Average]
  (min, avg, max) = (7.980, 7.992, 8.014), stdev = 0.019
  CI (99.9%): [7.638, 8.346] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.417 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 3.182 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.151 ±(99.9%) 0.003 ms/op
Iteration   1: 3.214 ±(99.9%) 0.002 ms/op
Iteration   2: 3.201 ±(99.9%) 0.002 ms/op
Iteration   3: 3.206 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.207 ±(99.9%) 0.123 ms/op [Average]
  (min, avg, max) = (3.201, 3.207, 3.214), stdev = 0.007
  CI (99.9%): [3.084, 3.330] (assumes normal distribution)


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
# Warmup Iteration   1: 4.021 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.144 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.089 ±(99.9%) 0.003 ms/op
Iteration   1: 3.036 ±(99.9%) 0.005 ms/op
Iteration   2: 3.107 ±(99.9%) 0.002 ms/op
Iteration   3: 3.090 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.078 ±(99.9%) 0.682 ms/op [Average]
  (min, avg, max) = (3.036, 3.078, 3.107), stdev = 0.037
  CI (99.9%): [2.395, 3.760] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.187 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.202 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.142 ±(99.9%) 0.002 ms/op
Iteration   1: 3.175 ±(99.9%) 0.001 ms/op
Iteration   2: 3.184 ±(99.9%) 0.002 ms/op
Iteration   3: 3.214 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.191 ±(99.9%) 0.373 ms/op [Average]
  (min, avg, max) = (3.175, 3.191, 3.214), stdev = 0.020
  CI (99.9%): [2.818, 3.564] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.389 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 4.089 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.149 ±(99.9%) 0.009 ms/op
Iteration   1: 4.093 ±(99.9%) 0.007 ms/op
Iteration   2: 3.992 ±(99.9%) 0.009 ms/op
Iteration   3: 3.989 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.025 ±(99.9%) 1.072 ms/op [Average]
  (min, avg, max) = (3.989, 4.025, 4.093), stdev = 0.059
  CI (99.9%): [2.953, 5.097] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 3.935 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.354 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.213 ±(99.9%) 0.007 ms/op
Iteration   1: 3.159 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.872 ms/op
                 createUser·p0.50:   3.129 ms/op
                 createUser·p0.90:   3.863 ms/op
                 createUser·p0.95:   4.088 ms/op
                 createUser·p0.99:   4.489 ms/op
                 createUser·p0.999:  7.488 ms/op
                 createUser·p0.9999: 12.861 ms/op
                 createUser·p1.00:   13.353 ms/op

Iteration   2: 3.143 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.902 ms/op
                 createUser·p0.50:   3.121 ms/op
                 createUser·p0.90:   3.826 ms/op
                 createUser·p0.95:   4.055 ms/op
                 createUser·p0.99:   4.555 ms/op
                 createUser·p0.999:  6.808 ms/op
                 createUser·p0.9999: 14.527 ms/op
                 createUser·p1.00:   14.991 ms/op

Iteration   3: 3.147 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.829 ms/op
                 createUser·p0.50:   3.129 ms/op
                 createUser·p0.90:   3.834 ms/op
                 createUser·p0.95:   4.010 ms/op
                 createUser·p0.99:   4.424 ms/op
                 createUser·p0.999:  11.158 ms/op
                 createUser·p0.9999: 18.142 ms/op
                 createUser·p1.00:   19.399 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 304651
  mean =      3.150 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 578 
    [ 1.250,  2.500) = 27796 
    [ 2.500,  3.750) = 236733 
    [ 3.750,  5.000) = 38293 
    [ 5.000,  6.250) = 623 
    [ 6.250,  7.500) = 276 
    [ 7.500,  8.750) = 51 
    [ 8.750, 10.000) = 20 
    [10.000, 11.250) = 55 
    [11.250, 12.500) = 37 
    [12.500, 13.750) = 80 
    [13.750, 15.000) = 55 
    [15.000, 16.250) = 7 
    [16.250, 17.500) = 19 
    [17.500, 18.750) = 25 

  Percentiles, ms/op:
      p(0.0000) =      0.829 ms/op
     p(50.0000) =      3.125 ms/op
     p(90.0000) =      3.842 ms/op
     p(95.0000) =      4.047 ms/op
     p(99.0000) =      4.497 ms/op
     p(99.9000) =      8.728 ms/op
     p(99.9900) =     17.369 ms/op
     p(99.9990) =     19.018 ms/op
     p(99.9999) =     19.399 ms/op
    p(100.0000) =     19.399 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.097 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.100 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.013 ±(99.9%) 0.007 ms/op
Iteration   1: 2.990 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.680 ms/op
                 existUser·p0.50:   3.006 ms/op
                 existUser·p0.90:   3.695 ms/op
                 existUser·p0.95:   3.867 ms/op
                 existUser·p0.99:   4.268 ms/op
                 existUser·p0.999:  6.619 ms/op
                 existUser·p0.9999: 12.321 ms/op
                 existUser·p1.00:   12.763 ms/op

Iteration   2: 3.108 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.911 ms/op
                 existUser·p0.50:   3.092 ms/op
                 existUser·p0.90:   3.793 ms/op
                 existUser·p0.95:   3.965 ms/op
                 existUser·p0.99:   4.260 ms/op
                 existUser·p0.999:  7.505 ms/op
                 existUser·p0.9999: 14.130 ms/op
                 existUser·p1.00:   14.336 ms/op

Iteration   3: 3.009 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.748 ms/op
                 existUser·p0.50:   2.966 ms/op
                 existUser·p0.90:   3.600 ms/op
                 existUser·p0.95:   3.830 ms/op
                 existUser·p0.99:   4.564 ms/op
                 existUser·p0.999:  10.742 ms/op
                 existUser·p0.9999: 16.648 ms/op
                 existUser·p1.00:   18.383 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 316390
  mean =      3.035 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1809 
    [ 1.250,  2.500) = 38433 
    [ 2.500,  3.750) = 248723 
    [ 3.750,  5.000) = 26302 
    [ 5.000,  6.250) = 546 
    [ 6.250,  7.500) = 229 
    [ 7.500,  8.750) = 113 
    [ 8.750, 10.000) = 11 
    [10.000, 11.250) = 44 
    [11.250, 12.500) = 46 
    [12.500, 13.750) = 45 
    [13.750, 15.000) = 25 
    [15.000, 16.250) = 51 
    [16.250, 17.500) = 11 
    [17.500, 18.750) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.680 ms/op
     p(50.0000) =      3.015 ms/op
     p(90.0000) =      3.707 ms/op
     p(95.0000) =      3.895 ms/op
     p(99.0000) =      4.309 ms/op
     p(99.9000) =      7.817 ms/op
     p(99.9900) =     15.811 ms/op
     p(99.9990) =     17.292 ms/op
     p(99.9999) =     18.383 ms/op
    p(100.0000) =     18.383 ms/op


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
# Warmup Iteration   1: 4.476 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.296 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.188 ±(99.9%) 0.007 ms/op
Iteration   1: 3.203 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.901 ms/op
                 getUser·p0.50:   3.174 ms/op
                 getUser·p0.90:   3.858 ms/op
                 getUser·p0.95:   4.063 ms/op
                 getUser·p0.99:   4.506 ms/op
                 getUser·p0.999:  9.980 ms/op
                 getUser·p0.9999: 13.566 ms/op
                 getUser·p1.00:   14.451 ms/op

Iteration   2: 3.168 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.905 ms/op
                 getUser·p0.50:   3.146 ms/op
                 getUser·p0.90:   3.793 ms/op
                 getUser·p0.95:   3.969 ms/op
                 getUser·p0.99:   4.317 ms/op
                 getUser·p0.999:  7.422 ms/op
                 getUser·p0.9999: 15.630 ms/op
                 getUser·p1.00:   16.368 ms/op

Iteration   3: 3.198 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.886 ms/op
                 getUser·p0.50:   3.162 ms/op
                 getUser·p0.90:   3.887 ms/op
                 getUser·p0.95:   4.092 ms/op
                 getUser·p0.99:   4.448 ms/op
                 getUser·p0.999:  7.340 ms/op
                 getUser·p0.9999: 16.450 ms/op
                 getUser·p1.00:   16.974 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 300933
  mean =      3.189 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 387 
    [ 1.250,  2.500) = 16487 
    [ 2.500,  3.750) = 243925 
    [ 3.750,  5.000) = 38981 
    [ 5.000,  6.250) = 518 
    [ 6.250,  7.500) = 289 
    [ 7.500,  8.750) = 95 
    [ 8.750, 10.000) = 24 
    [10.000, 11.250) = 19 
    [11.250, 12.500) = 46 
    [12.500, 13.750) = 44 
    [13.750, 15.000) = 53 
    [15.000, 16.250) = 37 
    [16.250, 17.500) = 28 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.886 ms/op
     p(50.0000) =      3.158 ms/op
     p(90.0000) =      3.846 ms/op
     p(95.0000) =      4.039 ms/op
     p(99.0000) =      4.440 ms/op
     p(99.9000) =      7.775 ms/op
     p(99.9900) =     16.219 ms/op
     p(99.9990) =     16.905 ms/op
     p(99.9999) =     16.974 ms/op
    p(100.0000) =     16.974 ms/op


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
# Warmup Iteration   1: 5.184 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.303 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.082 ±(99.9%) 0.011 ms/op
Iteration   1: 4.047 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.893 ms/op
                 listUser·p0.50:   3.850 ms/op
                 listUser·p0.90:   5.169 ms/op
                 listUser·p0.95:   5.800 ms/op
                 listUser·p0.99:   7.111 ms/op
                 listUser·p0.999:  14.115 ms/op
                 listUser·p0.9999: 16.533 ms/op
                 listUser·p1.00:   17.138 ms/op

Iteration   2: 3.980 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.087 ms/op
                 listUser·p0.50:   3.838 ms/op
                 listUser·p0.90:   4.792 ms/op
                 listUser·p0.95:   5.628 ms/op
                 listUser·p0.99:   6.968 ms/op
                 listUser·p0.999:  15.373 ms/op
                 listUser·p0.9999: 21.066 ms/op
                 listUser·p1.00:   21.955 ms/op

Iteration   3: 4.056 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.000 ms/op
                 listUser·p0.50:   3.891 ms/op
                 listUser·p0.90:   5.054 ms/op
                 listUser·p0.95:   5.652 ms/op
                 listUser·p0.99:   6.949 ms/op
                 listUser·p0.999:  19.017 ms/op
                 listUser·p0.9999: 28.250 ms/op
                 listUser·p1.00:   28.672 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 238392
  mean =      4.027 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1527 
    [ 2.500,  5.000) = 212089 
    [ 5.000,  7.500) = 23345 
    [ 7.500, 10.000) = 918 
    [10.000, 12.500) = 109 
    [12.500, 15.000) = 129 
    [15.000, 17.500) = 155 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 52 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 18 

  Percentiles, ms/op:
      p(0.0000) =      0.893 ms/op
     p(50.0000) =      3.858 ms/op
     p(90.0000) =      5.046 ms/op
     p(95.0000) =      5.693 ms/op
     p(99.0000) =      7.012 ms/op
     p(99.9000) =     15.476 ms/op
     p(99.9900) =     26.083 ms/op
     p(99.9990) =     28.581 ms/op
     p(99.9999) =     28.672 ms/op
    p(100.0000) =     28.672 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.960 ± 1.610  ops/ms
ClientGrpc.existUser                       thrpt       3  10.518 ± 2.341  ops/ms
ClientGrpc.getUser                         thrpt       3  10.031 ± 2.179  ops/ms
ClientGrpc.listUser                        thrpt       3   7.992 ± 0.354  ops/ms
ClientGrpc.createUser                       avgt       3   3.207 ± 0.123   ms/op
ClientGrpc.existUser                        avgt       3   3.078 ± 0.682   ms/op
ClientGrpc.getUser                          avgt       3   3.191 ± 0.373   ms/op
ClientGrpc.listUser                         avgt       3   4.025 ± 1.072   ms/op
ClientGrpc.createUser                     sample  304651   3.150 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.829           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.125           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.842           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.047           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.497           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.728           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.369           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          19.399           ms/op
ClientGrpc.existUser                      sample  316390   3.035 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.680           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.015           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.707           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.895           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.309           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.817           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.811           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.383           ms/op
ClientGrpc.getUser                        sample  300933   3.189 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.886           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.158           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.846           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.039           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.440           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.775           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.219           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          16.974           ms/op
ClientGrpc.listUser                       sample  238392   4.027 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.893           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.858           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.046           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.693           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.012           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.476           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          26.083           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          28.672           ms/op
