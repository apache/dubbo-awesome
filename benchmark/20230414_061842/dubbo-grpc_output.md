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
# Warmup Iteration   1: 4.367 ops/ms
# Warmup Iteration   2: 9.084 ops/ms
# Warmup Iteration   3: 10.108 ops/ms
Iteration   1: 10.414 ops/ms
Iteration   2: 10.692 ops/ms
Iteration   3: 10.489 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.532 ±(99.9%) 2.620 ops/ms [Average]
  (min, avg, max) = (10.414, 10.532, 10.692), stdev = 0.144
  CI (99.9%): [7.912, 13.151] (assumes normal distribution)


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
# Warmup Iteration   1: 7.728 ops/ms
# Warmup Iteration   2: 10.623 ops/ms
# Warmup Iteration   3: 10.918 ops/ms
Iteration   1: 11.042 ops/ms
Iteration   2: 11.208 ops/ms
Iteration   3: 11.061 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.103 ±(99.9%) 1.658 ops/ms [Average]
  (min, avg, max) = (11.042, 11.103, 11.208), stdev = 0.091
  CI (99.9%): [9.445, 12.761] (assumes normal distribution)


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
# Warmup Iteration   1: 7.093 ops/ms
# Warmup Iteration   2: 10.319 ops/ms
# Warmup Iteration   3: 10.551 ops/ms
Iteration   1: 10.716 ops/ms
Iteration   2: 10.646 ops/ms
Iteration   3: 10.654 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.672 ±(99.9%) 0.705 ops/ms [Average]
  (min, avg, max) = (10.646, 10.672, 10.716), stdev = 0.039
  CI (99.9%): [9.966, 11.377] (assumes normal distribution)


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
# Warmup Iteration   1: 5.408 ops/ms
# Warmup Iteration   2: 7.828 ops/ms
# Warmup Iteration   3: 8.147 ops/ms
Iteration   1: 8.122 ops/ms
Iteration   2: 8.239 ops/ms
Iteration   3: 8.298 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.220 ±(99.9%) 1.631 ops/ms [Average]
  (min, avg, max) = (8.122, 8.220, 8.298), stdev = 0.089
  CI (99.9%): [6.589, 9.851] (assumes normal distribution)


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
# Warmup Iteration   1: 4.301 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.143 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 3.061 ±(99.9%) 0.004 ms/op
Iteration   1: 3.020 ±(99.9%) 0.005 ms/op
Iteration   2: 3.038 ±(99.9%) 0.003 ms/op
Iteration   3: 2.965 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.008 ±(99.9%) 0.690 ms/op [Average]
  (min, avg, max) = (2.965, 3.008, 3.038), stdev = 0.038
  CI (99.9%): [2.318, 3.697] (assumes normal distribution)


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
# Warmup Iteration   1: 3.935 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.036 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.953 ±(99.9%) 0.003 ms/op
Iteration   1: 2.868 ±(99.9%) 0.003 ms/op
Iteration   2: 2.963 ±(99.9%) 0.002 ms/op
Iteration   3: 2.932 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.921 ±(99.9%) 0.882 ms/op [Average]
  (min, avg, max) = (2.868, 2.921, 2.963), stdev = 0.048
  CI (99.9%): [2.039, 3.802] (assumes normal distribution)


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
# Warmup Iteration   1: 4.254 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.104 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.064 ±(99.9%) 0.004 ms/op
Iteration   1: 3.035 ±(99.9%) 0.003 ms/op
Iteration   2: 3.023 ±(99.9%) 0.003 ms/op
Iteration   3: 3.016 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.025 ±(99.9%) 0.178 ms/op [Average]
  (min, avg, max) = (3.016, 3.025, 3.035), stdev = 0.010
  CI (99.9%): [2.846, 3.203] (assumes normal distribution)


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
# Warmup Iteration   1: 4.954 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.118 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 3.867 ±(99.9%) 0.030 ms/op
Iteration   1: 3.911 ±(99.9%) 0.018 ms/op
Iteration   2: 3.854 ±(99.9%) 0.012 ms/op
Iteration   3: 3.866 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.877 ±(99.9%) 0.552 ms/op [Average]
  (min, avg, max) = (3.854, 3.877, 3.911), stdev = 0.030
  CI (99.9%): [3.325, 4.429] (assumes normal distribution)


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
# Warmup Iteration   1: 4.169 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.162 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.044 ±(99.9%) 0.006 ms/op
Iteration   1: 2.984 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.951 ms/op
                 createUser·p0.50:   2.970 ms/op
                 createUser·p0.90:   3.498 ms/op
                 createUser·p0.95:   3.760 ms/op
                 createUser·p0.99:   4.293 ms/op
                 createUser·p0.999:  7.291 ms/op
                 createUser·p0.9999: 18.842 ms/op
                 createUser·p1.00:   19.038 ms/op

Iteration   2: 3.000 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.811 ms/op
                 createUser·p0.50:   2.966 ms/op
                 createUser·p0.90:   3.490 ms/op
                 createUser·p0.95:   3.695 ms/op
                 createUser·p0.99:   4.538 ms/op
                 createUser·p0.999:  8.036 ms/op
                 createUser·p0.9999: 20.306 ms/op
                 createUser·p1.00:   21.725 ms/op

Iteration   3: 2.973 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.626 ms/op
                 createUser·p0.50:   2.949 ms/op
                 createUser·p0.90:   3.490 ms/op
                 createUser·p0.95:   3.752 ms/op
                 createUser·p0.99:   4.530 ms/op
                 createUser·p0.999:  10.617 ms/op
                 createUser·p0.9999: 16.736 ms/op
                 createUser·p1.00:   17.596 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 321335
  mean =      2.986 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 29874 
    [ 2.500,  5.000) = 290134 
    [ 5.000,  7.500) = 961 
    [ 7.500, 10.000) = 118 
    [10.000, 12.500) = 69 
    [12.500, 15.000) = 53 
    [15.000, 17.500) = 60 
    [17.500, 20.000) = 49 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.626 ms/op
     p(50.0000) =      2.961 ms/op
     p(90.0000) =      3.490 ms/op
     p(95.0000) =      3.731 ms/op
     p(99.0000) =      4.440 ms/op
     p(99.9000) =      7.990 ms/op
     p(99.9900) =     19.407 ms/op
     p(99.9990) =     21.620 ms/op
     p(99.9999) =     21.725 ms/op
    p(100.0000) =     21.725 ms/op


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
# Warmup Iteration   1: 4.041 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 2.968 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.936 ±(99.9%) 0.006 ms/op
Iteration   1: 2.874 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.741 ms/op
                 existUser·p0.50:   2.884 ms/op
                 existUser·p0.90:   3.387 ms/op
                 existUser·p0.95:   3.551 ms/op
                 existUser·p0.99:   4.002 ms/op
                 existUser·p0.999:  6.228 ms/op
                 existUser·p0.9999: 12.304 ms/op
                 existUser·p1.00:   12.599 ms/op

Iteration   2: 2.952 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.766 ms/op
                 existUser·p0.50:   2.912 ms/op
                 existUser·p0.90:   3.535 ms/op
                 existUser·p0.95:   3.719 ms/op
                 existUser·p0.99:   4.166 ms/op
                 existUser·p0.999:  6.245 ms/op
                 existUser·p0.9999: 20.720 ms/op
                 existUser·p1.00:   21.004 ms/op

Iteration   3: 2.837 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.497 ms/op
                 existUser·p0.50:   2.847 ms/op
                 existUser·p0.90:   3.363 ms/op
                 existUser·p0.95:   3.613 ms/op
                 existUser·p0.99:   4.252 ms/op
                 existUser·p0.999:  6.293 ms/op
                 existUser·p0.9999: 26.706 ms/op
                 existUser·p1.00:   27.263 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 332535
  mean =      2.887 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 53307 
    [ 2.500,  5.000) = 278158 
    [ 5.000,  7.500) = 910 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 29 
    [12.500, 15.000) = 36 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.497 ms/op
     p(50.0000) =      2.879 ms/op
     p(90.0000) =      3.432 ms/op
     p(95.0000) =      3.641 ms/op
     p(99.0000) =      4.153 ms/op
     p(99.9000) =      6.250 ms/op
     p(99.9900) =     20.996 ms/op
     p(99.9990) =     27.187 ms/op
     p(99.9999) =     27.263 ms/op
    p(100.0000) =     27.263 ms/op


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
# Warmup Iteration   1: 4.054 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.169 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.020 ±(99.9%) 0.006 ms/op
Iteration   1: 3.015 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.551 ms/op
                 getUser·p0.50:   2.986 ms/op
                 getUser·p0.90:   3.555 ms/op
                 getUser·p0.95:   3.781 ms/op
                 getUser·p0.99:   4.579 ms/op
                 getUser·p0.999:  6.610 ms/op
                 getUser·p0.9999: 12.691 ms/op
                 getUser·p1.00:   12.960 ms/op

Iteration   2: 2.989 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.717 ms/op
                 getUser·p0.50:   2.966 ms/op
                 getUser·p0.90:   3.437 ms/op
                 getUser·p0.95:   3.686 ms/op
                 getUser·p0.99:   4.432 ms/op
                 getUser·p0.999:  5.906 ms/op
                 getUser·p0.9999: 21.768 ms/op
                 getUser·p1.00:   21.955 ms/op

Iteration   3: 3.025 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.867 ms/op
                 getUser·p0.50:   3.006 ms/op
                 getUser·p0.90:   3.478 ms/op
                 getUser·p0.95:   3.633 ms/op
                 getUser·p0.99:   4.219 ms/op
                 getUser·p0.999:  6.447 ms/op
                 getUser·p0.9999: 16.646 ms/op
                 getUser·p1.00:   18.481 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 318800
  mean =      3.010 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23798 
    [ 2.500,  5.000) = 293837 
    [ 5.000,  7.500) = 942 
    [ 7.500, 10.000) = 31 
    [10.000, 12.500) = 48 
    [12.500, 15.000) = 49 
    [15.000, 17.500) = 62 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.551 ms/op
     p(50.0000) =      2.986 ms/op
     p(90.0000) =      3.490 ms/op
     p(95.0000) =      3.703 ms/op
     p(99.0000) =      4.407 ms/op
     p(99.9000) =      6.513 ms/op
     p(99.9900) =     21.270 ms/op
     p(99.9990) =     21.889 ms/op
     p(99.9999) =     21.955 ms/op
    p(100.0000) =     21.955 ms/op


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
# Warmup Iteration   1: 5.334 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 4.077 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.889 ±(99.9%) 0.010 ms/op
Iteration   1: 3.847 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.532 ms/op
                 listUser·p0.50:   3.690 ms/op
                 listUser·p0.90:   4.702 ms/op
                 listUser·p0.95:   5.579 ms/op
                 listUser·p0.99:   6.873 ms/op
                 listUser·p0.999:  13.330 ms/op
                 listUser·p0.9999: 18.680 ms/op
                 listUser·p1.00:   19.399 ms/op

Iteration   2: 3.960 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.348 ms/op
                 listUser·p0.50:   3.793 ms/op
                 listUser·p0.90:   4.915 ms/op
                 listUser·p0.95:   5.669 ms/op
                 listUser·p0.99:   6.799 ms/op
                 listUser·p0.999:  15.581 ms/op
                 listUser·p0.9999: 24.150 ms/op
                 listUser·p1.00:   25.166 ms/op

Iteration   3: 3.899 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.681 ms/op
                 listUser·p0.50:   3.744 ms/op
                 listUser·p0.90:   4.776 ms/op
                 listUser·p0.95:   5.661 ms/op
                 listUser·p0.99:   6.857 ms/op
                 listUser·p0.999:  14.972 ms/op
                 listUser·p0.9999: 18.940 ms/op
                 listUser·p1.00:   19.268 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 246111
  mean =      3.901 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2780 
    [ 2.500,  5.000) = 222660 
    [ 5.000,  7.500) = 19468 
    [ 7.500, 10.000) = 783 
    [10.000, 12.500) = 36 
    [12.500, 15.000) = 159 
    [15.000, 17.500) = 71 
    [17.500, 20.000) = 90 
    [20.000, 22.500) = 49 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.681 ms/op
     p(50.0000) =      3.744 ms/op
     p(90.0000) =      4.809 ms/op
     p(95.0000) =      5.644 ms/op
     p(99.0000) =      6.849 ms/op
     p(99.9000) =     14.777 ms/op
     p(99.9900) =     22.262 ms/op
     p(99.9990) =     25.103 ms/op
     p(99.9999) =     25.166 ms/op
    p(100.0000) =     25.166 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.532 ± 2.620  ops/ms
ClientGrpc.existUser                       thrpt       3  11.103 ± 1.658  ops/ms
ClientGrpc.getUser                         thrpt       3  10.672 ± 0.705  ops/ms
ClientGrpc.listUser                        thrpt       3   8.220 ± 1.631  ops/ms
ClientGrpc.createUser                       avgt       3   3.008 ± 0.690   ms/op
ClientGrpc.existUser                        avgt       3   2.921 ± 0.882   ms/op
ClientGrpc.getUser                          avgt       3   3.025 ± 0.178   ms/op
ClientGrpc.listUser                         avgt       3   3.877 ± 0.552   ms/op
ClientGrpc.createUser                     sample  321335   2.986 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.626           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.961           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.490           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.731           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.440           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.990           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.407           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.725           ms/op
ClientGrpc.existUser                      sample  332535   2.887 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.497           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.879           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.432           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.641           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.153           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.250           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.996           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          27.263           ms/op
ClientGrpc.getUser                        sample  318800   3.010 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.551           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.986           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.490           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.703           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.407           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.513           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.270           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.955           ms/op
ClientGrpc.listUser                       sample  246111   3.901 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.681           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.744           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.809           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.644           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.849           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.777           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.262           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.166           ms/op
