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
# Warmup Iteration   1: 4.425 ops/ms
# Warmup Iteration   2: 8.723 ops/ms
# Warmup Iteration   3: 10.085 ops/ms
Iteration   1: 10.599 ops/ms
Iteration   2: 10.395 ops/ms
Iteration   3: 10.478 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.490 ±(99.9%) 1.867 ops/ms [Average]
  (min, avg, max) = (10.395, 10.490, 10.599), stdev = 0.102
  CI (99.9%): [8.623, 12.358] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 6.774 ops/ms
# Warmup Iteration   2: 10.241 ops/ms
# Warmup Iteration   3: 10.953 ops/ms
Iteration   1: 10.833 ops/ms
Iteration   2: 11.068 ops/ms
Iteration   3: 11.008 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.970 ±(99.9%) 2.226 ops/ms [Average]
  (min, avg, max) = (10.833, 10.970, 11.068), stdev = 0.122
  CI (99.9%): [8.743, 13.196] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.354 ops/ms
# Warmup Iteration   2: 9.709 ops/ms
# Warmup Iteration   3: 10.246 ops/ms
Iteration   1: 10.489 ops/ms
Iteration   2: 10.282 ops/ms
Iteration   3: 10.280 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.350 ±(99.9%) 2.188 ops/ms [Average]
  (min, avg, max) = (10.280, 10.350, 10.489), stdev = 0.120
  CI (99.9%): [8.163, 12.538] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.941 ops/ms
# Warmup Iteration   2: 7.433 ops/ms
# Warmup Iteration   3: 8.113 ops/ms
Iteration   1: 8.089 ops/ms
Iteration   2: 7.968 ops/ms
Iteration   3: 7.983 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.013 ±(99.9%) 1.200 ops/ms [Average]
  (min, avg, max) = (7.968, 8.013, 8.089), stdev = 0.066
  CI (99.9%): [6.814, 9.213] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.532 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.175 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 3.160 ±(99.9%) 0.002 ms/op
Iteration   1: 3.095 ±(99.9%) 0.009 ms/op
Iteration   2: 3.095 ±(99.9%) 0.002 ms/op
Iteration   3: 3.158 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.116 ±(99.9%) 0.665 ms/op [Average]
  (min, avg, max) = (3.095, 3.116, 3.158), stdev = 0.036
  CI (99.9%): [2.452, 3.781] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 4.213 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.038 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.956 ±(99.9%) 0.003 ms/op
Iteration   1: 2.955 ±(99.9%) 0.003 ms/op
Iteration   2: 2.998 ±(99.9%) 0.003 ms/op
Iteration   3: 2.908 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.954 ±(99.9%) 0.815 ms/op [Average]
  (min, avg, max) = (2.908, 2.954, 2.998), stdev = 0.045
  CI (99.9%): [2.139, 3.769] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.010 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.191 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.149 ±(99.9%) 0.002 ms/op
Iteration   1: 3.109 ±(99.9%) 0.002 ms/op
Iteration   2: 3.098 ±(99.9%) 0.002 ms/op
Iteration   3: 3.069 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.092 ±(99.9%) 0.376 ms/op [Average]
  (min, avg, max) = (3.069, 3.092, 3.109), stdev = 0.021
  CI (99.9%): [2.716, 3.468] (assumes normal distribution)


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
# Warmup Iteration   1: 4.760 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 4.250 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.096 ±(99.9%) 0.030 ms/op
Iteration   1: 4.107 ±(99.9%) 0.019 ms/op
Iteration   2: 3.947 ±(99.9%) 0.016 ms/op
Iteration   3: 3.989 ±(99.9%) 0.023 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.014 ±(99.9%) 1.515 ms/op [Average]
  (min, avg, max) = (3.947, 4.014, 4.107), stdev = 0.083
  CI (99.9%): [2.500, 5.529] (assumes normal distribution)


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
# Warmup Iteration   1: 4.707 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.418 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.186 ±(99.9%) 0.007 ms/op
Iteration   1: 3.121 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.787 ms/op
                 createUser·p0.50:   3.060 ms/op
                 createUser·p0.90:   3.682 ms/op
                 createUser·p0.95:   3.977 ms/op
                 createUser·p0.99:   4.956 ms/op
                 createUser·p0.999:  9.840 ms/op
                 createUser·p0.9999: 28.500 ms/op
                 createUser·p1.00:   29.655 ms/op

Iteration   2: 3.082 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.900 ms/op
                 createUser·p0.50:   3.049 ms/op
                 createUser·p0.90:   3.629 ms/op
                 createUser·p0.95:   3.916 ms/op
                 createUser·p0.99:   4.784 ms/op
                 createUser·p0.999:  8.241 ms/op
                 createUser·p0.9999: 14.713 ms/op
                 createUser·p1.00:   15.303 ms/op

Iteration   3: 3.122 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.713 ms/op
                 createUser·p0.50:   3.080 ms/op
                 createUser·p0.90:   3.707 ms/op
                 createUser·p0.95:   3.981 ms/op
                 createUser·p0.99:   4.858 ms/op
                 createUser·p0.999:  13.853 ms/op
                 createUser·p0.9999: 18.416 ms/op
                 createUser·p1.00:   18.874 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 308662
  mean =      3.108 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20998 
    [ 2.500,  5.000) = 285012 
    [ 5.000,  7.500) = 2033 
    [ 7.500, 10.000) = 257 
    [10.000, 12.500) = 37 
    [12.500, 15.000) = 161 
    [15.000, 17.500) = 101 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.713 ms/op
     p(50.0000) =      3.064 ms/op
     p(90.0000) =      3.674 ms/op
     p(95.0000) =      3.957 ms/op
     p(99.0000) =      4.866 ms/op
     p(99.9000) =     12.769 ms/op
     p(99.9900) =     20.389 ms/op
     p(99.9990) =     29.483 ms/op
     p(99.9999) =     29.655 ms/op
    p(100.0000) =     29.655 ms/op


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
# Warmup Iteration   1: 4.300 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.102 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.909 ±(99.9%) 0.006 ms/op
Iteration   1: 2.949 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.679 ms/op
                 existUser·p0.50:   2.941 ms/op
                 existUser·p0.90:   3.314 ms/op
                 existUser·p0.95:   3.531 ms/op
                 existUser·p0.99:   4.383 ms/op
                 existUser·p0.999:  7.245 ms/op
                 existUser·p0.9999: 13.030 ms/op
                 existUser·p1.00:   13.484 ms/op

Iteration   2: 2.949 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.810 ms/op
                 existUser·p0.50:   2.916 ms/op
                 existUser·p0.90:   3.379 ms/op
                 existUser·p0.95:   3.588 ms/op
                 existUser·p0.99:   4.375 ms/op
                 existUser·p0.999:  7.557 ms/op
                 existUser·p0.9999: 14.281 ms/op
                 existUser·p1.00:   14.828 ms/op

Iteration   3: 2.927 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.642 ms/op
                 existUser·p0.50:   2.900 ms/op
                 existUser·p0.90:   3.285 ms/op
                 existUser·p0.95:   3.547 ms/op
                 existUser·p0.99:   4.604 ms/op
                 existUser·p0.999:  9.318 ms/op
                 existUser·p0.9999: 18.418 ms/op
                 existUser·p1.00:   18.678 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 326295
  mean =      2.941 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 967 
    [ 1.250,  2.500) = 26353 
    [ 2.500,  3.750) = 288763 
    [ 3.750,  5.000) = 8543 
    [ 5.000,  6.250) = 703 
    [ 6.250,  7.500) = 536 
    [ 7.500,  8.750) = 140 
    [ 8.750, 10.000) = 35 
    [10.000, 11.250) = 31 
    [11.250, 12.500) = 41 
    [12.500, 13.750) = 87 
    [13.750, 15.000) = 48 
    [15.000, 16.250) = 5 
    [16.250, 17.500) = 11 
    [17.500, 18.750) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.642 ms/op
     p(50.0000) =      2.920 ms/op
     p(90.0000) =      3.326 ms/op
     p(95.0000) =      3.559 ms/op
     p(99.0000) =      4.481 ms/op
     p(99.9000) =      8.053 ms/op
     p(99.9900) =     17.606 ms/op
     p(99.9990) =     18.547 ms/op
     p(99.9999) =     18.678 ms/op
    p(100.0000) =     18.678 ms/op


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
# Warmup Iteration   1: 4.124 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.168 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.069 ±(99.9%) 0.006 ms/op
Iteration   1: 3.073 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.505 ms/op
                 getUser·p0.50:   3.045 ms/op
                 getUser·p0.90:   3.564 ms/op
                 getUser·p0.95:   3.744 ms/op
                 getUser·p0.99:   4.432 ms/op
                 getUser·p0.999:  8.149 ms/op
                 getUser·p0.9999: 18.369 ms/op
                 getUser·p1.00:   19.431 ms/op

Iteration   2: 3.044 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.891 ms/op
                 getUser·p0.50:   3.006 ms/op
                 getUser·p0.90:   3.461 ms/op
                 getUser·p0.95:   3.604 ms/op
                 getUser·p0.99:   4.211 ms/op
                 getUser·p0.999:  7.550 ms/op
                 getUser·p0.9999: 17.743 ms/op
                 getUser·p1.00:   17.826 ms/op

Iteration   3: 3.050 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.872 ms/op
                 getUser·p0.50:   3.023 ms/op
                 getUser·p0.90:   3.486 ms/op
                 getUser·p0.95:   3.748 ms/op
                 getUser·p0.99:   4.489 ms/op
                 getUser·p0.999:  7.898 ms/op
                 getUser·p0.9999: 18.645 ms/op
                 getUser·p1.00:   20.316 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 314313
  mean =      3.056 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13237 
    [ 2.500,  5.000) = 299624 
    [ 5.000,  7.500) = 1063 
    [ 7.500, 10.000) = 197 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 15 
    [15.000, 17.500) = 72 
    [17.500, 20.000) = 103 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.505 ms/op
     p(50.0000) =      3.023 ms/op
     p(90.0000) =      3.502 ms/op
     p(95.0000) =      3.699 ms/op
     p(99.0000) =      4.391 ms/op
     p(99.9000) =      7.892 ms/op
     p(99.9900) =     18.514 ms/op
     p(99.9990) =     19.839 ms/op
     p(99.9999) =     20.316 ms/op
    p(100.0000) =     20.316 ms/op


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
# Warmup Iteration   1: 5.203 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 4.076 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.997 ±(99.9%) 0.011 ms/op
Iteration   1: 3.912 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.671 ms/op
                 listUser·p0.50:   3.781 ms/op
                 listUser·p0.90:   4.547 ms/op
                 listUser·p0.95:   5.399 ms/op
                 listUser·p0.99:   6.832 ms/op
                 listUser·p0.999:  13.730 ms/op
                 listUser·p0.9999: 15.300 ms/op
                 listUser·p1.00:   17.170 ms/op

Iteration   2: 3.992 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.231 ms/op
                 listUser·p0.50:   3.793 ms/op
                 listUser·p0.90:   5.112 ms/op
                 listUser·p0.95:   5.751 ms/op
                 listUser·p0.99:   7.029 ms/op
                 listUser·p0.999:  15.954 ms/op
                 listUser·p0.9999: 27.590 ms/op
                 listUser·p1.00:   28.901 ms/op

Iteration   3: 3.941 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.705 ms/op
                 listUser·p0.50:   3.777 ms/op
                 listUser·p0.90:   4.907 ms/op
                 listUser·p0.95:   5.636 ms/op
                 listUser·p0.99:   7.012 ms/op
                 listUser·p0.999:  16.426 ms/op
                 listUser·p0.9999: 18.969 ms/op
                 listUser·p1.00:   19.431 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 243161
  mean =      3.948 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2494 
    [ 2.500,  5.000) = 218680 
    [ 5.000,  7.500) = 20597 
    [ 7.500, 10.000) = 974 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 175 
    [15.000, 17.500) = 105 
    [17.500, 20.000) = 63 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 22 

  Percentiles, ms/op:
      p(0.0000) =      0.705 ms/op
     p(50.0000) =      3.785 ms/op
     p(90.0000) =      4.907 ms/op
     p(95.0000) =      5.628 ms/op
     p(99.0000) =      6.963 ms/op
     p(99.9000) =     14.721 ms/op
     p(99.9900) =     26.675 ms/op
     p(99.9990) =     28.760 ms/op
     p(99.9999) =     28.901 ms/op
    p(100.0000) =     28.901 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.490 ± 1.867  ops/ms
ClientGrpc.existUser                       thrpt       3  10.970 ± 2.226  ops/ms
ClientGrpc.getUser                         thrpt       3  10.350 ± 2.188  ops/ms
ClientGrpc.listUser                        thrpt       3   8.013 ± 1.200  ops/ms
ClientGrpc.createUser                       avgt       3   3.116 ± 0.665   ms/op
ClientGrpc.existUser                        avgt       3   2.954 ± 0.815   ms/op
ClientGrpc.getUser                          avgt       3   3.092 ± 0.376   ms/op
ClientGrpc.listUser                         avgt       3   4.014 ± 1.515   ms/op
ClientGrpc.createUser                     sample  308662   3.108 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.713           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.064           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.674           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.957           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.866           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.769           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.389           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          29.655           ms/op
ClientGrpc.existUser                      sample  326295   2.941 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.642           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.920           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.326           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.559           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.481           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.053           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.606           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.678           ms/op
ClientGrpc.getUser                        sample  314313   3.056 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.505           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.023           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.502           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.699           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.391           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.892           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.514           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.316           ms/op
ClientGrpc.listUser                       sample  243161   3.948 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.705           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.785           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.907           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.628           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.963           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.721           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          26.675           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          28.901           ms/op
