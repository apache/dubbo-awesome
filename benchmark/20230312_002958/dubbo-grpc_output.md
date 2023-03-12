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
# Warmup Iteration   1: 4.377 ops/ms
# Warmup Iteration   2: 9.294 ops/ms
# Warmup Iteration   3: 10.167 ops/ms
Iteration   1: 10.584 ops/ms
Iteration   2: 10.631 ops/ms
Iteration   3: 10.552 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.589 ±(99.9%) 0.727 ops/ms [Average]
  (min, avg, max) = (10.552, 10.589, 10.631), stdev = 0.040
  CI (99.9%): [9.862, 11.316] (assumes normal distribution)


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
# Warmup Iteration   1: 7.692 ops/ms
# Warmup Iteration   2: 10.854 ops/ms
# Warmup Iteration   3: 11.127 ops/ms
Iteration   1: 11.319 ops/ms
Iteration   2: 11.060 ops/ms
Iteration   3: 11.325 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.235 ±(99.9%) 2.761 ops/ms [Average]
  (min, avg, max) = (11.060, 11.235, 11.325), stdev = 0.151
  CI (99.9%): [8.474, 13.996] (assumes normal distribution)


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
# Warmup Iteration   1: 7.338 ops/ms
# Warmup Iteration   2: 10.294 ops/ms
# Warmup Iteration   3: 10.643 ops/ms
Iteration   1: 10.593 ops/ms
Iteration   2: 10.632 ops/ms
Iteration   3: 10.516 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.580 ±(99.9%) 1.080 ops/ms [Average]
  (min, avg, max) = (10.516, 10.580, 10.632), stdev = 0.059
  CI (99.9%): [9.500, 11.660] (assumes normal distribution)


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
# Warmup Iteration   1: 6.472 ops/ms
# Warmup Iteration   2: 8.013 ops/ms
# Warmup Iteration   3: 8.255 ops/ms
Iteration   1: 8.163 ops/ms
Iteration   2: 8.157 ops/ms
Iteration   3: 8.124 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.148 ±(99.9%) 0.380 ops/ms [Average]
  (min, avg, max) = (8.124, 8.148, 8.163), stdev = 0.021
  CI (99.9%): [7.768, 8.528] (assumes normal distribution)


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
# Warmup Iteration   1: 4.132 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.150 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.033 ±(99.9%) 0.002 ms/op
Iteration   1: 2.989 ±(99.9%) 0.009 ms/op
Iteration   2: 2.968 ±(99.9%) 0.002 ms/op
Iteration   3: 2.968 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.975 ±(99.9%) 0.220 ms/op [Average]
  (min, avg, max) = (2.968, 2.975, 2.989), stdev = 0.012
  CI (99.9%): [2.755, 3.195] (assumes normal distribution)


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
# Warmup Iteration   1: 4.011 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 2.912 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.939 ±(99.9%) 0.003 ms/op
Iteration   1: 2.903 ±(99.9%) 0.003 ms/op
Iteration   2: 2.893 ±(99.9%) 0.002 ms/op
Iteration   3: 2.871 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.889 ±(99.9%) 0.300 ms/op [Average]
  (min, avg, max) = (2.871, 2.889, 2.903), stdev = 0.016
  CI (99.9%): [2.589, 3.190] (assumes normal distribution)


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
# Warmup Iteration   1: 4.355 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.058 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.005 ±(99.9%) 0.003 ms/op
Iteration   1: 3.020 ±(99.9%) 0.003 ms/op
Iteration   2: 2.999 ±(99.9%) 0.003 ms/op
Iteration   3: 2.918 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.979 ±(99.9%) 0.982 ms/op [Average]
  (min, avg, max) = (2.918, 2.979, 3.020), stdev = 0.054
  CI (99.9%): [1.997, 3.961] (assumes normal distribution)


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
# Warmup Iteration   1: 4.790 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 4.134 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.935 ±(99.9%) 0.016 ms/op
Iteration   1: 3.826 ±(99.9%) 0.014 ms/op
Iteration   2: 3.839 ±(99.9%) 0.018 ms/op
Iteration   3: 3.878 ±(99.9%) 0.028 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.848 ±(99.9%) 0.499 ms/op [Average]
  (min, avg, max) = (3.826, 3.848, 3.878), stdev = 0.027
  CI (99.9%): [3.349, 4.347] (assumes normal distribution)


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
# Warmup Iteration   1: 4.201 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.186 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.024 ±(99.9%) 0.006 ms/op
Iteration   1: 2.998 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.774 ms/op
                 createUser·p0.50:   2.998 ms/op
                 createUser·p0.90:   3.637 ms/op
                 createUser·p0.95:   3.867 ms/op
                 createUser·p0.99:   4.415 ms/op
                 createUser·p0.999:  7.623 ms/op
                 createUser·p0.9999: 15.505 ms/op
                 createUser·p1.00:   17.269 ms/op

Iteration   2: 3.015 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.665 ms/op
                 createUser·p0.50:   2.974 ms/op
                 createUser·p0.90:   3.441 ms/op
                 createUser·p0.95:   3.706 ms/op
                 createUser·p0.99:   4.551 ms/op
                 createUser·p0.999:  11.715 ms/op
                 createUser·p0.9999: 28.796 ms/op
                 createUser·p1.00:   29.295 ms/op

Iteration   3: 3.008 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.569 ms/op
                 createUser·p0.50:   2.970 ms/op
                 createUser·p0.90:   3.437 ms/op
                 createUser·p0.95:   3.682 ms/op
                 createUser·p0.99:   4.358 ms/op
                 createUser·p0.999:  8.285 ms/op
                 createUser·p0.9999: 21.540 ms/op
                 createUser·p1.00:   22.741 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 319366
  mean =      3.007 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26794 
    [ 2.500,  5.000) = 290894 
    [ 5.000,  7.500) = 1227 
    [ 7.500, 10.000) = 163 
    [10.000, 12.500) = 92 
    [12.500, 15.000) = 33 
    [15.000, 17.500) = 41 
    [17.500, 20.000) = 35 
    [20.000, 22.500) = 51 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.569 ms/op
     p(50.0000) =      2.978 ms/op
     p(90.0000) =      3.510 ms/op
     p(95.0000) =      3.764 ms/op
     p(99.0000) =      4.424 ms/op
     p(99.9000) =      8.307 ms/op
     p(99.9900) =     27.494 ms/op
     p(99.9990) =     29.184 ms/op
     p(99.9999) =     29.295 ms/op
    p(100.0000) =     29.295 ms/op


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
# Warmup Iteration   1: 3.764 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 2.936 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.834 ±(99.9%) 0.005 ms/op
Iteration   1: 2.865 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.771 ms/op
                 existUser·p0.50:   2.863 ms/op
                 existUser·p0.90:   3.359 ms/op
                 existUser·p0.95:   3.531 ms/op
                 existUser·p0.99:   4.076 ms/op
                 existUser·p0.999:  7.704 ms/op
                 existUser·p0.9999: 13.181 ms/op
                 existUser·p1.00:   15.024 ms/op

Iteration   2: 2.835 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.718 ms/op
                 existUser·p0.50:   2.834 ms/op
                 existUser·p0.90:   3.252 ms/op
                 existUser·p0.95:   3.441 ms/op
                 existUser·p0.99:   4.182 ms/op
                 existUser·p0.999:  6.613 ms/op
                 existUser·p0.9999: 13.381 ms/op
                 existUser·p1.00:   14.402 ms/op

Iteration   3: 2.876 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.560 ms/op
                 existUser·p0.50:   2.843 ms/op
                 existUser·p0.90:   3.228 ms/op
                 existUser·p0.95:   3.375 ms/op
                 existUser·p0.99:   4.052 ms/op
                 existUser·p0.999:  11.190 ms/op
                 existUser·p0.9999: 28.603 ms/op
                 existUser·p1.00:   29.065 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 335539
  mean =      2.859 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 46772 
    [ 2.500,  5.000) = 287692 
    [ 5.000,  7.500) = 692 
    [ 7.500, 10.000) = 127 
    [10.000, 12.500) = 99 
    [12.500, 15.000) = 101 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.560 ms/op
     p(50.0000) =      2.847 ms/op
     p(90.0000) =      3.281 ms/op
     p(95.0000) =      3.457 ms/op
     p(99.0000) =      4.100 ms/op
     p(99.9000) =      7.987 ms/op
     p(99.9900) =     16.887 ms/op
     p(99.9990) =     28.955 ms/op
     p(99.9999) =     29.065 ms/op
    p(100.0000) =     29.065 ms/op


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
# Warmup Iteration   1: 4.167 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.136 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.063 ±(99.9%) 0.006 ms/op
Iteration   1: 2.982 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.971 ms/op
                 getUser·p0.50:   2.957 ms/op
                 getUser·p0.90:   3.428 ms/op
                 getUser·p0.95:   3.625 ms/op
                 getUser·p0.99:   4.268 ms/op
                 getUser·p0.999:  7.424 ms/op
                 getUser·p0.9999: 18.851 ms/op
                 getUser·p1.00:   19.268 ms/op

Iteration   2: 2.997 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.597 ms/op
                 getUser·p0.50:   2.978 ms/op
                 getUser·p0.90:   3.551 ms/op
                 getUser·p0.95:   3.719 ms/op
                 getUser·p0.99:   4.340 ms/op
                 getUser·p0.999:  6.275 ms/op
                 getUser·p0.9999: 17.017 ms/op
                 getUser·p1.00:   17.302 ms/op

Iteration   3: 2.984 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.583 ms/op
                 getUser·p0.50:   2.966 ms/op
                 getUser·p0.90:   3.494 ms/op
                 getUser·p0.95:   3.731 ms/op
                 getUser·p0.99:   4.719 ms/op
                 getUser·p0.999:  6.675 ms/op
                 getUser·p0.9999: 14.816 ms/op
                 getUser·p1.00:   15.581 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 321251
  mean =      2.988 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 469 
    [ 1.250,  2.500) = 28336 
    [ 2.500,  3.750) = 279102 
    [ 3.750,  5.000) = 12059 
    [ 5.000,  6.250) = 843 
    [ 6.250,  7.500) = 225 
    [ 7.500,  8.750) = 20 
    [ 8.750, 10.000) = 5 
    [10.000, 11.250) = 16 
    [11.250, 12.500) = 16 
    [12.500, 13.750) = 28 
    [13.750, 15.000) = 28 
    [15.000, 16.250) = 8 
    [16.250, 17.500) = 63 
    [17.500, 18.750) = 20 

  Percentiles, ms/op:
      p(0.0000) =      0.583 ms/op
     p(50.0000) =      2.966 ms/op
     p(90.0000) =      3.494 ms/op
     p(95.0000) =      3.699 ms/op
     p(99.0000) =      4.432 ms/op
     p(99.9000) =      6.693 ms/op
     p(99.9900) =     17.990 ms/op
     p(99.9990) =     19.064 ms/op
     p(99.9999) =     19.268 ms/op
    p(100.0000) =     19.268 ms/op


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
# Warmup Iteration   1: 5.580 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 4.058 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.839 ±(99.9%) 0.010 ms/op
Iteration   1: 3.810 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.350 ms/op
                 listUser·p0.50:   3.645 ms/op
                 listUser·p0.90:   4.833 ms/op
                 listUser·p0.95:   5.553 ms/op
                 listUser·p0.99:   6.792 ms/op
                 listUser·p0.999:  12.186 ms/op
                 listUser·p0.9999: 14.008 ms/op
                 listUser·p1.00:   14.533 ms/op

Iteration   2: 3.685 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.190 ms/op
                 listUser·p0.50:   3.564 ms/op
                 listUser·p0.90:   4.678 ms/op
                 listUser·p0.95:   5.226 ms/op
                 listUser·p0.99:   6.521 ms/op
                 listUser·p0.999:  13.763 ms/op
                 listUser·p0.9999: 16.395 ms/op
                 listUser·p1.00:   16.630 ms/op

Iteration   3: 3.890 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.288 ms/op
                 listUser·p0.50:   3.686 ms/op
                 listUser·p0.90:   5.120 ms/op
                 listUser·p0.95:   5.816 ms/op
                 listUser·p0.99:   6.933 ms/op
                 listUser·p0.999:  17.924 ms/op
                 listUser·p0.9999: 24.673 ms/op
                 listUser·p1.00:   25.297 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 253103
  mean =      3.793 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6253 
    [ 2.500,  5.000) = 224903 
    [ 5.000,  7.500) = 20725 
    [ 7.500, 10.000) = 728 
    [10.000, 12.500) = 155 
    [12.500, 15.000) = 172 
    [15.000, 17.500) = 72 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 60 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.350 ms/op
     p(50.0000) =      3.633 ms/op
     p(90.0000) =      4.866 ms/op
     p(95.0000) =      5.562 ms/op
     p(99.0000) =      6.742 ms/op
     p(99.9000) =     13.566 ms/op
     p(99.9900) =     23.658 ms/op
     p(99.9990) =     25.179 ms/op
     p(99.9999) =     25.297 ms/op
    p(100.0000) =     25.297 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.589 ± 0.727  ops/ms
ClientGrpc.existUser                       thrpt       3  11.235 ± 2.761  ops/ms
ClientGrpc.getUser                         thrpt       3  10.580 ± 1.080  ops/ms
ClientGrpc.listUser                        thrpt       3   8.148 ± 0.380  ops/ms
ClientGrpc.createUser                       avgt       3   2.975 ± 0.220   ms/op
ClientGrpc.existUser                        avgt       3   2.889 ± 0.300   ms/op
ClientGrpc.getUser                          avgt       3   2.979 ± 0.982   ms/op
ClientGrpc.listUser                         avgt       3   3.848 ± 0.499   ms/op
ClientGrpc.createUser                     sample  319366   3.007 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.569           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.978           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.510           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.764           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.424           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.307           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          27.494           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          29.295           ms/op
ClientGrpc.existUser                      sample  335539   2.859 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.560           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.847           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.281           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.457           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.100           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.987           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.887           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          29.065           ms/op
ClientGrpc.getUser                        sample  321251   2.988 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.583           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.966           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.494           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.699           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.432           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.693           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.990           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.268           ms/op
ClientGrpc.listUser                       sample  253103   3.793 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.350           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.633           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.866           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.562           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.742           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.566           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.658           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.297           ms/op
