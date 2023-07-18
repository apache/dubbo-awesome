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
# Warmup Iteration   1: 3.855 ops/ms
# Warmup Iteration   2: 8.446 ops/ms
# Warmup Iteration   3: 9.703 ops/ms
Iteration   1: 10.053 ops/ms
Iteration   2: 10.253 ops/ms
Iteration   3: 10.277 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.194 ±(99.9%) 2.249 ops/ms [Average]
  (min, avg, max) = (10.053, 10.194, 10.277), stdev = 0.123
  CI (99.9%): [7.945, 12.444] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.245 ops/ms
# Warmup Iteration   2: 10.106 ops/ms
# Warmup Iteration   3: 10.704 ops/ms
Iteration   1: 10.999 ops/ms
Iteration   2: 10.952 ops/ms
Iteration   3: 10.963 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.971 ±(99.9%) 0.446 ops/ms [Average]
  (min, avg, max) = (10.952, 10.971, 10.999), stdev = 0.024
  CI (99.9%): [10.525, 11.418] (assumes normal distribution)


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
# Warmup Iteration   1: 6.858 ops/ms
# Warmup Iteration   2: 9.796 ops/ms
# Warmup Iteration   3: 10.401 ops/ms
Iteration   1: 10.482 ops/ms
Iteration   2: 10.345 ops/ms
Iteration   3: 10.466 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.431 ±(99.9%) 1.360 ops/ms [Average]
  (min, avg, max) = (10.345, 10.431, 10.482), stdev = 0.075
  CI (99.9%): [9.071, 11.791] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.465 ops/ms
# Warmup Iteration   2: 7.552 ops/ms
# Warmup Iteration   3: 7.703 ops/ms
Iteration   1: 7.821 ops/ms
Iteration   2: 8.114 ops/ms
Iteration   3: 7.913 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.949 ±(99.9%) 2.734 ops/ms [Average]
  (min, avg, max) = (7.821, 7.949, 8.114), stdev = 0.150
  CI (99.9%): [5.215, 10.683] (assumes normal distribution)


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
# Warmup Iteration   1: 4.310 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.220 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.056 ±(99.9%) 0.003 ms/op
Iteration   1: 3.031 ±(99.9%) 0.003 ms/op
Iteration   2: 3.063 ±(99.9%) 0.003 ms/op
Iteration   3: 3.129 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.074 ±(99.9%) 0.908 ms/op [Average]
  (min, avg, max) = (3.031, 3.074, 3.129), stdev = 0.050
  CI (99.9%): [2.166, 3.982] (assumes normal distribution)


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
# Warmup Iteration   1: 3.709 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.084 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.051 ±(99.9%) 0.002 ms/op
Iteration   1: 2.913 ±(99.9%) 0.003 ms/op
Iteration   2: 2.931 ±(99.9%) 0.001 ms/op
Iteration   3: 2.891 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.912 ±(99.9%) 0.364 ms/op [Average]
  (min, avg, max) = (2.891, 2.912, 2.931), stdev = 0.020
  CI (99.9%): [2.548, 3.276] (assumes normal distribution)


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
# Warmup Iteration   1: 4.260 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.224 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.034 ±(99.9%) 0.003 ms/op
Iteration   1: 3.059 ±(99.9%) 0.002 ms/op
Iteration   2: 3.033 ±(99.9%) 0.003 ms/op
Iteration   3: 3.051 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.047 ±(99.9%) 0.245 ms/op [Average]
  (min, avg, max) = (3.033, 3.047, 3.059), stdev = 0.013
  CI (99.9%): [2.802, 3.293] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.720 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.151 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 3.994 ±(99.9%) 0.033 ms/op
Iteration   1: 3.945 ±(99.9%) 0.008 ms/op
Iteration   2: 3.809 ±(99.9%) 0.014 ms/op
Iteration   3: 3.897 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.884 ±(99.9%) 1.252 ms/op [Average]
  (min, avg, max) = (3.809, 3.884, 3.945), stdev = 0.069
  CI (99.9%): [2.632, 5.136] (assumes normal distribution)


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
# Warmup Iteration   1: 4.420 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.253 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.055 ±(99.9%) 0.006 ms/op
Iteration   1: 3.043 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.351 ms/op
                 createUser·p0.50:   3.015 ms/op
                 createUser·p0.90:   3.539 ms/op
                 createUser·p0.95:   3.744 ms/op
                 createUser·p0.99:   4.350 ms/op
                 createUser·p0.999:  6.886 ms/op
                 createUser·p0.9999: 16.285 ms/op
                 createUser·p1.00:   17.302 ms/op

Iteration   2: 3.037 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.752 ms/op
                 createUser·p0.50:   3.015 ms/op
                 createUser·p0.90:   3.551 ms/op
                 createUser·p0.95:   3.760 ms/op
                 createUser·p0.99:   4.563 ms/op
                 createUser·p0.999:  8.452 ms/op
                 createUser·p0.9999: 19.086 ms/op
                 createUser·p1.00:   19.399 ms/op

Iteration   3: 3.081 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.626 ms/op
                 createUser·p0.50:   3.039 ms/op
                 createUser·p0.90:   3.617 ms/op
                 createUser·p0.95:   3.850 ms/op
                 createUser·p0.99:   4.792 ms/op
                 createUser·p0.999:  13.402 ms/op
                 createUser·p0.9999: 21.922 ms/op
                 createUser·p1.00:   22.479 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 314368
  mean =      3.054 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23631 
    [ 2.500,  5.000) = 288804 
    [ 5.000,  7.500) = 1411 
    [ 7.500, 10.000) = 223 
    [10.000, 12.500) = 40 
    [12.500, 15.000) = 45 
    [15.000, 17.500) = 86 
    [17.500, 20.000) = 84 
    [20.000, 22.500) = 44 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.351 ms/op
     p(50.0000) =      3.023 ms/op
     p(90.0000) =      3.572 ms/op
     p(95.0000) =      3.789 ms/op
     p(99.0000) =      4.530 ms/op
     p(99.9000) =      9.191 ms/op
     p(99.9900) =     20.152 ms/op
     p(99.9990) =     22.315 ms/op
     p(99.9999) =     22.479 ms/op
    p(100.0000) =     22.479 ms/op


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
# Warmup Iteration   1: 4.035 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.032 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.936 ±(99.9%) 0.005 ms/op
Iteration   1: 2.896 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.870 ms/op
                 existUser·p0.50:   2.859 ms/op
                 existUser·p0.90:   3.281 ms/op
                 existUser·p0.95:   3.555 ms/op
                 existUser·p0.99:   4.211 ms/op
                 existUser·p0.999:  7.910 ms/op
                 existUser·p0.9999: 19.988 ms/op
                 existUser·p1.00:   20.644 ms/op

Iteration   2: 2.927 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.836 ms/op
                 existUser·p0.50:   2.912 ms/op
                 existUser·p0.90:   3.387 ms/op
                 existUser·p0.95:   3.539 ms/op
                 existUser·p0.99:   4.162 ms/op
                 existUser·p0.999:  6.855 ms/op
                 existUser·p0.9999: 21.466 ms/op
                 existUser·p1.00:   21.692 ms/op

Iteration   3: 2.897 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.645 ms/op
                 existUser·p0.50:   2.879 ms/op
                 existUser·p0.90:   3.252 ms/op
                 existUser·p0.95:   3.437 ms/op
                 existUser·p0.99:   3.994 ms/op
                 existUser·p0.999:  6.833 ms/op
                 existUser·p0.9999: 18.867 ms/op
                 existUser·p1.00:   19.857 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 330084
  mean =      2.907 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 33218 
    [ 2.500,  5.000) = 295778 
    [ 5.000,  7.500) = 772 
    [ 7.500, 10.000) = 121 
    [10.000, 12.500) = 35 
    [12.500, 15.000) = 49 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 48 
    [20.000, 22.500) = 42 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.645 ms/op
     p(50.0000) =      2.884 ms/op
     p(90.0000) =      3.322 ms/op
     p(95.0000) =      3.506 ms/op
     p(99.0000) =      4.129 ms/op
     p(99.9000) =      7.404 ms/op
     p(99.9900) =     20.643 ms/op
     p(99.9990) =     21.650 ms/op
     p(99.9999) =     21.692 ms/op
    p(100.0000) =     21.692 ms/op


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
# Warmup Iteration   1: 4.405 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.283 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.089 ±(99.9%) 0.007 ms/op
Iteration   1: 3.069 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.725 ms/op
                 getUser·p0.50:   3.023 ms/op
                 getUser·p0.90:   3.650 ms/op
                 getUser·p0.95:   3.936 ms/op
                 getUser·p0.99:   4.801 ms/op
                 getUser·p0.999:  9.204 ms/op
                 getUser·p0.9999: 18.842 ms/op
                 getUser·p1.00:   19.137 ms/op

Iteration   2: 3.072 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.750 ms/op
                 getUser·p0.50:   3.035 ms/op
                 getUser·p0.90:   3.572 ms/op
                 getUser·p0.95:   3.830 ms/op
                 getUser·p0.99:   4.522 ms/op
                 getUser·p0.999:  8.083 ms/op
                 getUser·p0.9999: 14.453 ms/op
                 getUser·p1.00:   14.975 ms/op

Iteration   3: 3.106 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.326 ms/op
                 getUser·p0.50:   3.064 ms/op
                 getUser·p0.90:   3.629 ms/op
                 getUser·p0.95:   3.830 ms/op
                 getUser·p0.99:   4.563 ms/op
                 getUser·p0.999:  7.505 ms/op
                 getUser·p0.9999: 27.375 ms/op
                 getUser·p1.00:   27.754 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 311423
  mean =      3.083 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17267 
    [ 2.500,  5.000) = 292202 
    [ 5.000,  7.500) = 1569 
    [ 7.500, 10.000) = 170 
    [10.000, 12.500) = 41 
    [12.500, 15.000) = 78 
    [15.000, 17.500) = 43 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 26 

  Percentiles, ms/op:
      p(0.0000) =      0.326 ms/op
     p(50.0000) =      3.039 ms/op
     p(90.0000) =      3.617 ms/op
     p(95.0000) =      3.867 ms/op
     p(99.0000) =      4.653 ms/op
     p(99.9000) =      8.118 ms/op
     p(99.9900) =     26.402 ms/op
     p(99.9990) =     27.649 ms/op
     p(99.9999) =     27.754 ms/op
    p(100.0000) =     27.754 ms/op


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
# Warmup Iteration   1: 5.574 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.310 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.997 ±(99.9%) 0.011 ms/op
Iteration   1: 4.005 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.348 ms/op
                 listUser·p0.50:   3.858 ms/op
                 listUser·p0.90:   4.882 ms/op
                 listUser·p0.95:   5.767 ms/op
                 listUser·p0.99:   7.176 ms/op
                 listUser·p0.999:  14.371 ms/op
                 listUser·p0.9999: 27.886 ms/op
                 listUser·p1.00:   29.524 ms/op

Iteration   2: 4.007 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.118 ms/op
                 listUser·p0.50:   3.846 ms/op
                 listUser·p0.90:   5.003 ms/op
                 listUser·p0.95:   5.882 ms/op
                 listUser·p0.99:   7.004 ms/op
                 listUser·p0.999:  15.026 ms/op
                 listUser·p0.9999: 18.252 ms/op
                 listUser·p1.00:   23.265 ms/op

Iteration   3: 4.054 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.460 ms/op
                 listUser·p0.50:   3.903 ms/op
                 listUser·p0.90:   4.882 ms/op
                 listUser·p0.95:   5.538 ms/op
                 listUser·p0.99:   6.988 ms/op
                 listUser·p0.999:  15.503 ms/op
                 listUser·p0.9999: 30.412 ms/op
                 listUser·p1.00:   31.752 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 238617
  mean =      4.022 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2270 
    [ 2.500,  5.000) = 214305 
    [ 5.000,  7.500) = 20580 
    [ 7.500, 10.000) = 1003 
    [10.000, 12.500) = 107 
    [12.500, 15.000) = 99 
    [15.000, 17.500) = 114 
    [17.500, 20.000) = 37 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 21 
    [27.500, 30.000) = 27 
    [30.000, 32.500) = 15 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.118 ms/op
     p(50.0000) =      3.871 ms/op
     p(90.0000) =      4.915 ms/op
     p(95.0000) =      5.743 ms/op
     p(99.0000) =      7.053 ms/op
     p(99.9000) =     15.194 ms/op
     p(99.9900) =     29.730 ms/op
     p(99.9990) =     30.653 ms/op
     p(99.9999) =     31.752 ms/op
    p(100.0000) =     31.752 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.194 ± 2.249  ops/ms
ClientGrpc.existUser                       thrpt       3  10.971 ± 0.446  ops/ms
ClientGrpc.getUser                         thrpt       3  10.431 ± 1.360  ops/ms
ClientGrpc.listUser                        thrpt       3   7.949 ± 2.734  ops/ms
ClientGrpc.createUser                       avgt       3   3.074 ± 0.908   ms/op
ClientGrpc.existUser                        avgt       3   2.912 ± 0.364   ms/op
ClientGrpc.getUser                          avgt       3   3.047 ± 0.245   ms/op
ClientGrpc.listUser                         avgt       3   3.884 ± 1.252   ms/op
ClientGrpc.createUser                     sample  314368   3.054 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.351           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.023           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.572           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.789           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.530           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.191           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.152           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.479           ms/op
ClientGrpc.existUser                      sample  330084   2.907 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.645           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.884           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.322           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.506           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.129           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.404           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.643           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.692           ms/op
ClientGrpc.getUser                        sample  311423   3.083 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.326           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.039           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.617           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.867           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.653           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.118           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          26.402           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          27.754           ms/op
ClientGrpc.listUser                       sample  238617   4.022 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.118           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.871           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.915           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.743           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.053           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.194           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          29.730           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          31.752           ms/op
