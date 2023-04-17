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
# Warmup Iteration   1: 4.666 ops/ms
# Warmup Iteration   2: 9.189 ops/ms
# Warmup Iteration   3: 10.513 ops/ms
Iteration   1: 10.501 ops/ms
Iteration   2: 10.613 ops/ms
Iteration   3: 10.687 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.601 ±(99.9%) 1.715 ops/ms [Average]
  (min, avg, max) = (10.501, 10.601, 10.687), stdev = 0.094
  CI (99.9%): [8.886, 12.316] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.855 ops/ms
# Warmup Iteration   2: 10.912 ops/ms
# Warmup Iteration   3: 10.958 ops/ms
Iteration   1: 11.289 ops/ms
Iteration   2: 11.215 ops/ms
Iteration   3: 11.291 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.265 ±(99.9%) 0.794 ops/ms [Average]
  (min, avg, max) = (11.215, 11.265, 11.291), stdev = 0.044
  CI (99.9%): [10.471, 12.059] (assumes normal distribution)


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
# Warmup Iteration   1: 7.075 ops/ms
# Warmup Iteration   2: 10.430 ops/ms
# Warmup Iteration   3: 10.696 ops/ms
Iteration   1: 10.746 ops/ms
Iteration   2: 10.555 ops/ms
Iteration   3: 10.328 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.543 ±(99.9%) 3.824 ops/ms [Average]
  (min, avg, max) = (10.328, 10.543, 10.746), stdev = 0.210
  CI (99.9%): [6.719, 14.367] (assumes normal distribution)


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
# Warmup Iteration   1: 5.720 ops/ms
# Warmup Iteration   2: 8.079 ops/ms
# Warmup Iteration   3: 8.446 ops/ms
Iteration   1: 8.329 ops/ms
Iteration   2: 8.345 ops/ms
Iteration   3: 8.586 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.420 ±(99.9%) 2.621 ops/ms [Average]
  (min, avg, max) = (8.329, 8.420, 8.586), stdev = 0.144
  CI (99.9%): [5.799, 11.041] (assumes normal distribution)


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
# Warmup Iteration   1: 3.741 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.047 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.038 ±(99.9%) 0.006 ms/op
Iteration   1: 3.022 ±(99.9%) 0.003 ms/op
Iteration   2: 3.005 ±(99.9%) 0.003 ms/op
Iteration   3: 3.015 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.014 ±(99.9%) 0.157 ms/op [Average]
  (min, avg, max) = (3.005, 3.014, 3.022), stdev = 0.009
  CI (99.9%): [2.857, 3.170] (assumes normal distribution)


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
# Warmup Iteration   1: 3.693 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.979 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.864 ±(99.9%) 0.003 ms/op
Iteration   1: 2.915 ±(99.9%) 0.003 ms/op
Iteration   2: 2.844 ±(99.9%) 0.004 ms/op
Iteration   3: 2.847 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.869 ±(99.9%) 0.735 ms/op [Average]
  (min, avg, max) = (2.844, 2.869, 2.915), stdev = 0.040
  CI (99.9%): [2.134, 3.603] (assumes normal distribution)


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
# Warmup Iteration   1: 4.085 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.014 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.994 ±(99.9%) 0.003 ms/op
Iteration   1: 2.964 ±(99.9%) 0.003 ms/op
Iteration   2: 2.936 ±(99.9%) 0.003 ms/op
Iteration   3: 3.002 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.967 ±(99.9%) 0.609 ms/op [Average]
  (min, avg, max) = (2.936, 2.967, 3.002), stdev = 0.033
  CI (99.9%): [2.358, 3.576] (assumes normal distribution)


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
# Warmup Iteration   1: 4.916 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.919 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 3.883 ±(99.9%) 0.030 ms/op
Iteration   1: 3.782 ±(99.9%) 0.009 ms/op
Iteration   2: 3.798 ±(99.9%) 0.022 ms/op
Iteration   3: 3.740 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.773 ±(99.9%) 0.549 ms/op [Average]
  (min, avg, max) = (3.740, 3.773, 3.798), stdev = 0.030
  CI (99.9%): [3.224, 4.322] (assumes normal distribution)


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
# Warmup Iteration   1: 3.850 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.131 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.999 ±(99.9%) 0.007 ms/op
Iteration   1: 3.004 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.629 ms/op
                 createUser·p0.50:   2.982 ms/op
                 createUser·p0.90:   3.527 ms/op
                 createUser·p0.95:   3.719 ms/op
                 createUser·p0.99:   4.407 ms/op
                 createUser·p0.999:  6.730 ms/op
                 createUser·p0.9999: 11.518 ms/op
                 createUser·p1.00:   11.715 ms/op

Iteration   2: 2.970 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.573 ms/op
                 createUser·p0.50:   2.970 ms/op
                 createUser·p0.90:   3.277 ms/op
                 createUser·p0.95:   3.355 ms/op
                 createUser·p0.99:   3.908 ms/op
                 createUser·p0.999:  7.362 ms/op
                 createUser·p0.9999: 14.949 ms/op
                 createUser·p1.00:   15.286 ms/op

Iteration   3: 2.954 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.645 ms/op
                 createUser·p0.50:   2.949 ms/op
                 createUser·p0.90:   3.379 ms/op
                 createUser·p0.95:   3.555 ms/op
                 createUser·p0.99:   4.284 ms/op
                 createUser·p0.999:  8.035 ms/op
                 createUser·p0.9999: 19.541 ms/op
                 createUser·p1.00:   19.988 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 322637
  mean =      2.976 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1237 
    [ 1.250,  2.500) = 19168 
    [ 2.500,  3.750) = 292948 
    [ 3.750,  5.000) = 8315 
    [ 5.000,  6.250) = 471 
    [ 6.250,  7.500) = 185 
    [ 7.500,  8.750) = 64 
    [ 8.750, 10.000) = 19 
    [10.000, 11.250) = 33 
    [11.250, 12.500) = 38 
    [12.500, 13.750) = 65 
    [13.750, 15.000) = 21 
    [15.000, 16.250) = 38 
    [16.250, 17.500) = 3 
    [17.500, 18.750) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.573 ms/op
     p(50.0000) =      2.966 ms/op
     p(90.0000) =      3.383 ms/op
     p(95.0000) =      3.576 ms/op
     p(99.0000) =      4.211 ms/op
     p(99.9000) =      7.441 ms/op
     p(99.9900) =     17.483 ms/op
     p(99.9990) =     19.850 ms/op
     p(99.9999) =     19.988 ms/op
    p(100.0000) =     19.988 ms/op


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
# Warmup Iteration   1: 3.751 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 2.912 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.879 ±(99.9%) 0.005 ms/op
Iteration   1: 2.923 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.499 ms/op
                 existUser·p0.50:   2.888 ms/op
                 existUser·p0.90:   3.404 ms/op
                 existUser·p0.95:   3.609 ms/op
                 existUser·p0.99:   4.076 ms/op
                 existUser·p0.999:  5.956 ms/op
                 existUser·p0.9999: 11.191 ms/op
                 existUser·p1.00:   11.338 ms/op

Iteration   2: 2.926 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.540 ms/op
                 existUser·p0.50:   2.900 ms/op
                 existUser·p0.90:   3.486 ms/op
                 existUser·p0.95:   3.666 ms/op
                 existUser·p0.99:   4.202 ms/op
                 existUser·p0.999:  6.742 ms/op
                 existUser·p0.9999: 20.974 ms/op
                 existUser·p1.00:   21.135 ms/op

Iteration   3: 2.902 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.511 ms/op
                 existUser·p0.50:   2.896 ms/op
                 existUser·p0.90:   3.535 ms/op
                 existUser·p0.95:   3.719 ms/op
                 existUser·p0.99:   4.342 ms/op
                 existUser·p0.999:  6.701 ms/op
                 existUser·p0.9999: 16.334 ms/op
                 existUser·p1.00:   16.777 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 328741
  mean =      2.917 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 39474 
    [ 2.500,  5.000) = 288251 
    [ 5.000,  7.500) = 766 
    [ 7.500, 10.000) = 48 
    [10.000, 12.500) = 74 
    [12.500, 15.000) = 73 
    [15.000, 17.500) = 23 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.499 ms/op
     p(50.0000) =      2.892 ms/op
     p(90.0000) =      3.478 ms/op
     p(95.0000) =      3.670 ms/op
     p(99.0000) =      4.211 ms/op
     p(99.9000) =      6.539 ms/op
     p(99.9900) =     17.247 ms/op
     p(99.9990) =     21.093 ms/op
     p(99.9999) =     21.135 ms/op
    p(100.0000) =     21.135 ms/op


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
# Warmup Iteration   1: 4.043 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.124 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.934 ±(99.9%) 0.006 ms/op
Iteration   1: 3.013 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.865 ms/op
                 getUser·p0.50:   3.011 ms/op
                 getUser·p0.90:   3.576 ms/op
                 getUser·p0.95:   3.785 ms/op
                 getUser·p0.99:   4.366 ms/op
                 getUser·p0.999:  6.159 ms/op
                 getUser·p0.9999: 12.251 ms/op
                 getUser·p1.00:   12.599 ms/op

Iteration   2: 2.963 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.696 ms/op
                 getUser·p0.50:   2.949 ms/op
                 getUser·p0.90:   3.408 ms/op
                 getUser·p0.95:   3.637 ms/op
                 getUser·p0.99:   4.317 ms/op
                 getUser·p0.999:  6.091 ms/op
                 getUser·p0.9999: 12.845 ms/op
                 getUser·p1.00:   13.009 ms/op

Iteration   3: 3.016 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.802 ms/op
                 getUser·p0.50:   2.990 ms/op
                 getUser·p0.90:   3.539 ms/op
                 getUser·p0.95:   3.768 ms/op
                 getUser·p0.99:   4.276 ms/op
                 getUser·p0.999:  6.585 ms/op
                 getUser·p0.9999: 14.932 ms/op
                 getUser·p1.00:   15.106 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 320331
  mean =      2.997 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 902 
    [ 1.250,  2.500) = 24450 
    [ 2.500,  3.750) = 279705 
    [ 3.750,  5.000) = 14163 
    [ 5.000,  6.250) = 777 
    [ 6.250,  7.500) = 95 
    [ 7.500,  8.750) = 45 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 33 
    [11.250, 12.500) = 54 
    [12.500, 13.750) = 73 
    [13.750, 15.000) = 26 
    [15.000, 16.250) = 8 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.696 ms/op
     p(50.0000) =      2.982 ms/op
     p(90.0000) =      3.518 ms/op
     p(95.0000) =      3.736 ms/op
     p(99.0000) =      4.317 ms/op
     p(99.9000) =      6.313 ms/op
     p(99.9900) =     14.575 ms/op
     p(99.9990) =     15.067 ms/op
     p(99.9999) =     15.106 ms/op
    p(100.0000) =     15.106 ms/op


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
# Warmup Iteration   1: 5.037 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.929 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.800 ±(99.9%) 0.008 ms/op
Iteration   1: 3.780 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.153 ms/op
                 listUser·p0.50:   3.658 ms/op
                 listUser·p0.90:   4.579 ms/op
                 listUser·p0.95:   5.612 ms/op
                 listUser·p0.99:   6.668 ms/op
                 listUser·p0.999:  11.853 ms/op
                 listUser·p0.9999: 18.571 ms/op
                 listUser·p1.00:   18.907 ms/op

Iteration   2: 3.812 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.176 ms/op
                 listUser·p0.50:   3.682 ms/op
                 listUser·p0.90:   4.678 ms/op
                 listUser·p0.95:   5.579 ms/op
                 listUser·p0.99:   6.676 ms/op
                 listUser·p0.999:  15.609 ms/op
                 listUser·p0.9999: 19.517 ms/op
                 listUser·p1.00:   20.120 ms/op

Iteration   3: 3.774 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.034 ms/op
                 listUser·p0.50:   3.645 ms/op
                 listUser·p0.90:   4.637 ms/op
                 listUser·p0.95:   5.390 ms/op
                 listUser·p0.99:   6.455 ms/op
                 listUser·p0.999:  13.475 ms/op
                 listUser·p0.9999: 22.923 ms/op
                 listUser·p1.00:   23.495 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 253321
  mean =      3.789 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6966 
    [ 2.500,  5.000) = 227415 
    [ 5.000,  7.500) = 17950 
    [ 7.500, 10.000) = 568 
    [10.000, 12.500) = 117 
    [12.500, 15.000) = 119 
    [15.000, 17.500) = 58 
    [17.500, 20.000) = 95 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.034 ms/op
     p(50.0000) =      3.662 ms/op
     p(90.0000) =      4.628 ms/op
     p(95.0000) =      5.530 ms/op
     p(99.0000) =      6.603 ms/op
     p(99.9000) =     13.544 ms/op
     p(99.9900) =     21.430 ms/op
     p(99.9990) =     23.361 ms/op
     p(99.9999) =     23.495 ms/op
    p(100.0000) =     23.495 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.601 ± 1.715  ops/ms
ClientGrpc.existUser                       thrpt       3  11.265 ± 0.794  ops/ms
ClientGrpc.getUser                         thrpt       3  10.543 ± 3.824  ops/ms
ClientGrpc.listUser                        thrpt       3   8.420 ± 2.621  ops/ms
ClientGrpc.createUser                       avgt       3   3.014 ± 0.157   ms/op
ClientGrpc.existUser                        avgt       3   2.869 ± 0.735   ms/op
ClientGrpc.getUser                          avgt       3   2.967 ± 0.609   ms/op
ClientGrpc.listUser                         avgt       3   3.773 ± 0.549   ms/op
ClientGrpc.createUser                     sample  322637   2.976 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.573           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.966           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.383           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.576           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.211           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.441           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.483           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          19.988           ms/op
ClientGrpc.existUser                      sample  328741   2.917 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.499           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.892           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.478           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.670           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.211           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.539           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.247           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.135           ms/op
ClientGrpc.getUser                        sample  320331   2.997 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.696           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.982           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.518           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.736           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.317           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.313           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          14.575           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          15.106           ms/op
ClientGrpc.listUser                       sample  253321   3.789 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.034           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.662           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.628           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.530           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.603           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.544           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.430           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.495           ms/op
