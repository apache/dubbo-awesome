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
# Warmup Iteration   1: 4.499 ops/ms
# Warmup Iteration   2: 9.069 ops/ms
# Warmup Iteration   3: 10.054 ops/ms
Iteration   1: 10.407 ops/ms
Iteration   2: 10.434 ops/ms
Iteration   3: 10.207 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.349 ±(99.9%) 2.269 ops/ms [Average]
  (min, avg, max) = (10.207, 10.349, 10.434), stdev = 0.124
  CI (99.9%): [8.081, 12.618] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.544 ops/ms
# Warmup Iteration   2: 10.388 ops/ms
# Warmup Iteration   3: 10.927 ops/ms
Iteration   1: 10.795 ops/ms
Iteration   2: 10.681 ops/ms
Iteration   3: 10.741 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.739 ±(99.9%) 1.046 ops/ms [Average]
  (min, avg, max) = (10.681, 10.739, 10.795), stdev = 0.057
  CI (99.9%): [9.693, 11.785] (assumes normal distribution)


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
# Warmup Iteration   1: 7.307 ops/ms
# Warmup Iteration   2: 9.933 ops/ms
# Warmup Iteration   3: 10.324 ops/ms
Iteration   1: 10.187 ops/ms
Iteration   2: 10.253 ops/ms
Iteration   3: 10.318 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.253 ±(99.9%) 1.197 ops/ms [Average]
  (min, avg, max) = (10.187, 10.253, 10.318), stdev = 0.066
  CI (99.9%): [9.055, 11.450] (assumes normal distribution)


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
# Warmup Iteration   1: 5.611 ops/ms
# Warmup Iteration   2: 7.863 ops/ms
# Warmup Iteration   3: 8.095 ops/ms
Iteration   1: 7.982 ops/ms
Iteration   2: 8.183 ops/ms
Iteration   3: 8.145 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.103 ±(99.9%) 1.948 ops/ms [Average]
  (min, avg, max) = (7.982, 8.103, 8.183), stdev = 0.107
  CI (99.9%): [6.156, 10.051] (assumes normal distribution)


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
# Warmup Iteration   1: 4.569 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.189 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.164 ±(99.9%) 0.007 ms/op
Iteration   1: 3.185 ±(99.9%) 0.003 ms/op
Iteration   2: 3.181 ±(99.9%) 0.001 ms/op
Iteration   3: 3.161 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.176 ±(99.9%) 0.235 ms/op [Average]
  (min, avg, max) = (3.161, 3.176, 3.185), stdev = 0.013
  CI (99.9%): [2.941, 3.411] (assumes normal distribution)


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
# Warmup Iteration   1: 3.869 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.013 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.036 ±(99.9%) 0.002 ms/op
Iteration   1: 3.034 ±(99.9%) 0.002 ms/op
Iteration   2: 3.030 ±(99.9%) 0.001 ms/op
Iteration   3: 2.987 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.017 ±(99.9%) 0.472 ms/op [Average]
  (min, avg, max) = (2.987, 3.017, 3.034), stdev = 0.026
  CI (99.9%): [2.546, 3.489] (assumes normal distribution)


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
# Warmup Iteration   1: 4.327 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.211 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.172 ±(99.9%) 0.003 ms/op
Iteration   1: 3.115 ±(99.9%) 0.001 ms/op
Iteration   2: 3.130 ±(99.9%) 0.004 ms/op
Iteration   3: 3.186 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.144 ±(99.9%) 0.676 ms/op [Average]
  (min, avg, max) = (3.115, 3.144, 3.186), stdev = 0.037
  CI (99.9%): [2.468, 3.820] (assumes normal distribution)


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
# Warmup Iteration   1: 4.495 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 4.335 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.999 ±(99.9%) 0.021 ms/op
Iteration   1: 3.939 ±(99.9%) 0.009 ms/op
Iteration   2: 3.929 ±(99.9%) 0.007 ms/op
Iteration   3: 3.869 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.912 ±(99.9%) 0.686 ms/op [Average]
  (min, avg, max) = (3.869, 3.912, 3.939), stdev = 0.038
  CI (99.9%): [3.227, 4.598] (assumes normal distribution)


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
# Warmup Iteration   1: 4.316 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.214 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.095 ±(99.9%) 0.007 ms/op
Iteration   1: 3.178 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.838 ms/op
                 createUser·p0.50:   3.162 ms/op
                 createUser·p0.90:   3.863 ms/op
                 createUser·p0.95:   4.043 ms/op
                 createUser·p0.99:   4.383 ms/op
                 createUser·p0.999:  9.040 ms/op
                 createUser·p0.9999: 14.040 ms/op
                 createUser·p1.00:   15.483 ms/op

Iteration   2: 3.058 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.861 ms/op
                 createUser·p0.50:   3.039 ms/op
                 createUser·p0.90:   3.658 ms/op
                 createUser·p0.95:   3.875 ms/op
                 createUser·p0.99:   4.555 ms/op
                 createUser·p0.999:  6.685 ms/op
                 createUser·p0.9999: 16.926 ms/op
                 createUser·p1.00:   17.924 ms/op

Iteration   3: 3.195 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.847 ms/op
                 createUser·p0.50:   3.158 ms/op
                 createUser·p0.90:   3.908 ms/op
                 createUser·p0.95:   4.067 ms/op
                 createUser·p0.99:   4.424 ms/op
                 createUser·p0.999:  11.158 ms/op
                 createUser·p0.9999: 18.349 ms/op
                 createUser·p1.00:   18.678 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 305649
  mean =      3.142 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 718 
    [ 1.250,  2.500) = 29484 
    [ 2.500,  3.750) = 236351 
    [ 3.750,  5.000) = 37649 
    [ 5.000,  6.250) = 648 
    [ 6.250,  7.500) = 252 
    [ 7.500,  8.750) = 153 
    [ 8.750, 10.000) = 74 
    [10.000, 11.250) = 64 
    [11.250, 12.500) = 53 
    [12.500, 13.750) = 78 
    [13.750, 15.000) = 50 
    [15.000, 16.250) = 9 
    [16.250, 17.500) = 41 
    [17.500, 18.750) = 25 

  Percentiles, ms/op:
      p(0.0000) =      0.838 ms/op
     p(50.0000) =      3.109 ms/op
     p(90.0000) =      3.830 ms/op
     p(95.0000) =      4.018 ms/op
     p(99.0000) =      4.440 ms/op
     p(99.9000) =     10.306 ms/op
     p(99.9900) =     16.988 ms/op
     p(99.9990) =     18.545 ms/op
     p(99.9999) =     18.678 ms/op
    p(100.0000) =     18.678 ms/op


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
# Warmup Iteration   1: 4.079 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.096 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.009 ±(99.9%) 0.006 ms/op
Iteration   1: 3.065 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.910 ms/op
                 existUser·p0.50:   3.052 ms/op
                 existUser·p0.90:   3.723 ms/op
                 existUser·p0.95:   3.887 ms/op
                 existUser·p0.99:   4.219 ms/op
                 existUser·p0.999:  6.433 ms/op
                 existUser·p0.9999: 14.111 ms/op
                 existUser·p1.00:   14.959 ms/op

Iteration   2: 3.021 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.848 ms/op
                 existUser·p0.50:   3.015 ms/op
                 existUser·p0.90:   3.715 ms/op
                 existUser·p0.95:   3.903 ms/op
                 existUser·p0.99:   4.293 ms/op
                 existUser·p0.999:  7.168 ms/op
                 existUser·p0.9999: 14.169 ms/op
                 existUser·p1.00:   14.467 ms/op

Iteration   3: 3.034 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.731 ms/op
                 existUser·p0.50:   3.019 ms/op
                 existUser·p0.90:   3.703 ms/op
                 existUser·p0.95:   3.863 ms/op
                 existUser·p0.99:   4.145 ms/op
                 existUser·p0.999:  8.716 ms/op
                 existUser·p0.9999: 18.383 ms/op
                 existUser·p1.00:   19.366 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 315858
  mean =      3.040 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1112 
    [ 1.250,  2.500) = 41409 
    [ 2.500,  3.750) = 245598 
    [ 3.750,  5.000) = 26749 
    [ 5.000,  6.250) = 461 
    [ 6.250,  7.500) = 206 
    [ 7.500,  8.750) = 113 
    [ 8.750, 10.000) = 49 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 5 
    [12.500, 13.750) = 52 
    [13.750, 15.000) = 42 
    [15.000, 16.250) = 12 
    [16.250, 17.500) = 18 
    [17.500, 18.750) = 25 

  Percentiles, ms/op:
      p(0.0000) =      0.731 ms/op
     p(50.0000) =      3.027 ms/op
     p(90.0000) =      3.715 ms/op
     p(95.0000) =      3.883 ms/op
     p(99.0000) =      4.219 ms/op
     p(99.9000) =      7.586 ms/op
     p(99.9900) =     17.473 ms/op
     p(99.9990) =     19.186 ms/op
     p(99.9999) =     19.366 ms/op
    p(100.0000) =     19.366 ms/op


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
# Warmup Iteration   1: 4.223 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.208 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.162 ±(99.9%) 0.006 ms/op
Iteration   1: 3.124 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.040 ms/op
                 getUser·p0.50:   3.092 ms/op
                 getUser·p0.90:   3.789 ms/op
                 getUser·p0.95:   4.002 ms/op
                 getUser·p0.99:   4.481 ms/op
                 getUser·p0.999:  7.963 ms/op
                 getUser·p0.9999: 13.312 ms/op
                 getUser·p1.00:   13.697 ms/op

Iteration   2: 3.088 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.901 ms/op
                 getUser·p0.50:   3.056 ms/op
                 getUser·p0.90:   3.731 ms/op
                 getUser·p0.95:   3.932 ms/op
                 getUser·p0.99:   4.350 ms/op
                 getUser·p0.999:  7.650 ms/op
                 getUser·p0.9999: 14.275 ms/op
                 getUser·p1.00:   14.483 ms/op

Iteration   3: 3.127 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.801 ms/op
                 getUser·p0.50:   3.105 ms/op
                 getUser·p0.90:   3.805 ms/op
                 getUser·p0.95:   3.981 ms/op
                 getUser·p0.99:   4.293 ms/op
                 getUser·p0.999:  6.473 ms/op
                 getUser·p0.9999: 16.131 ms/op
                 getUser·p1.00:   16.597 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 308337
  mean =      3.113 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 499 
    [ 1.250,  2.500) = 27429 
    [ 2.500,  3.750) = 246591 
    [ 3.750,  5.000) = 32788 
    [ 5.000,  6.250) = 525 
    [ 6.250,  7.500) = 203 
    [ 7.500,  8.750) = 99 
    [ 8.750, 10.000) = 8 
    [10.000, 11.250) = 42 
    [11.250, 12.500) = 23 
    [12.500, 13.750) = 49 
    [13.750, 15.000) = 43 
    [15.000, 16.250) = 32 
    [16.250, 17.500) = 6 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.801 ms/op
     p(50.0000) =      3.084 ms/op
     p(90.0000) =      3.777 ms/op
     p(95.0000) =      3.973 ms/op
     p(99.0000) =      4.375 ms/op
     p(99.9000) =      7.354 ms/op
     p(99.9900) =     15.548 ms/op
     p(99.9990) =     16.493 ms/op
     p(99.9999) =     16.597 ms/op
    p(100.0000) =     16.597 ms/op


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
# Warmup Iteration   1: 5.172 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 4.166 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.045 ±(99.9%) 0.011 ms/op
Iteration   1: 4.071 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.497 ms/op
                 listUser·p0.50:   3.863 ms/op
                 listUser·p0.90:   5.243 ms/op
                 listUser·p0.95:   5.702 ms/op
                 listUser·p0.99:   7.016 ms/op
                 listUser·p0.999:  13.255 ms/op
                 listUser·p0.9999: 16.679 ms/op
                 listUser·p1.00:   19.890 ms/op

Iteration   2: 3.918 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.018 ms/op
                 listUser·p0.50:   3.789 ms/op
                 listUser·p0.90:   4.719 ms/op
                 listUser·p0.95:   5.439 ms/op
                 listUser·p0.99:   6.603 ms/op
                 listUser·p0.999:  14.135 ms/op
                 listUser·p0.9999: 16.616 ms/op
                 listUser·p1.00:   17.138 ms/op

Iteration   3: 3.871 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.963 ms/op
                 listUser·p0.50:   3.719 ms/op
                 listUser·p0.90:   4.874 ms/op
                 listUser·p0.95:   5.513 ms/op
                 listUser·p0.99:   6.750 ms/op
                 listUser·p0.999:  16.482 ms/op
                 listUser·p0.9999: 30.048 ms/op
                 listUser·p1.00:   30.736 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 242843
  mean =      3.951 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2137 
    [ 2.500,  5.000) = 215737 
    [ 5.000,  7.500) = 23846 
    [ 7.500, 10.000) = 718 
    [10.000, 12.500) = 48 
    [12.500, 15.000) = 158 
    [15.000, 17.500) = 126 
    [17.500, 20.000) = 9 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 10 
    [27.500, 30.000) = 12 
    [30.000, 32.500) = 10 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.497 ms/op
     p(50.0000) =      3.793 ms/op
     p(90.0000) =      5.030 ms/op
     p(95.0000) =      5.571 ms/op
     p(99.0000) =      6.799 ms/op
     p(99.9000) =     14.191 ms/op
     p(99.9900) =     26.370 ms/op
     p(99.9990) =     30.661 ms/op
     p(99.9999) =     30.736 ms/op
    p(100.0000) =     30.736 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.349 ± 2.269  ops/ms
ClientGrpc.existUser                       thrpt       3  10.739 ± 1.046  ops/ms
ClientGrpc.getUser                         thrpt       3  10.253 ± 1.197  ops/ms
ClientGrpc.listUser                        thrpt       3   8.103 ± 1.948  ops/ms
ClientGrpc.createUser                       avgt       3   3.176 ± 0.235   ms/op
ClientGrpc.existUser                        avgt       3   3.017 ± 0.472   ms/op
ClientGrpc.getUser                          avgt       3   3.144 ± 0.676   ms/op
ClientGrpc.listUser                         avgt       3   3.912 ± 0.686   ms/op
ClientGrpc.createUser                     sample  305649   3.142 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.838           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.109           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.830           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.018           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.440           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.306           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          16.988           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          18.678           ms/op
ClientGrpc.existUser                      sample  315858   3.040 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.731           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.027           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.715           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.883           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.219           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.586           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.473           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.366           ms/op
ClientGrpc.getUser                        sample  308337   3.113 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.801           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.084           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.777           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.973           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.375           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.354           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          15.548           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          16.597           ms/op
ClientGrpc.listUser                       sample  242843   3.951 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.497           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.793           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.030           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.571           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.799           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.191           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          26.370           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          30.736           ms/op
