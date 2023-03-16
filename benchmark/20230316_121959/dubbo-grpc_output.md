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
# Warmup Iteration   1: 4.791 ops/ms
# Warmup Iteration   2: 9.622 ops/ms
# Warmup Iteration   3: 10.616 ops/ms
Iteration   1: 10.505 ops/ms
Iteration   2: 10.663 ops/ms
Iteration   3: 10.817 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.662 ±(99.9%) 2.846 ops/ms [Average]
  (min, avg, max) = (10.505, 10.662, 10.817), stdev = 0.156
  CI (99.9%): [7.815, 13.508] (assumes normal distribution)


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
# Warmup Iteration   1: 7.979 ops/ms
# Warmup Iteration   2: 10.981 ops/ms
# Warmup Iteration   3: 11.377 ops/ms
Iteration   1: 11.147 ops/ms
Iteration   2: 11.352 ops/ms
Iteration   3: 11.274 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.257 ±(99.9%) 1.886 ops/ms [Average]
  (min, avg, max) = (11.147, 11.257, 11.352), stdev = 0.103
  CI (99.9%): [9.372, 13.143] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 9.513 ops/ms
# Warmup Iteration   2: 10.136 ops/ms
# Warmup Iteration   3: 10.774 ops/ms
Iteration   1: 10.832 ops/ms
Iteration   2: 10.872 ops/ms
Iteration   3: 10.677 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.793 ±(99.9%) 1.882 ops/ms [Average]
  (min, avg, max) = (10.677, 10.793, 10.872), stdev = 0.103
  CI (99.9%): [8.912, 12.675] (assumes normal distribution)


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
# Warmup Iteration   1: 5.848 ops/ms
# Warmup Iteration   2: 8.183 ops/ms
# Warmup Iteration   3: 8.192 ops/ms
Iteration   1: 8.160 ops/ms
Iteration   2: 8.239 ops/ms
Iteration   3: 8.316 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.238 ±(99.9%) 1.426 ops/ms [Average]
  (min, avg, max) = (8.160, 8.238, 8.316), stdev = 0.078
  CI (99.9%): [6.812, 9.665] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 4.073 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 3.129 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.018 ±(99.9%) 0.003 ms/op
Iteration   1: 3.004 ±(99.9%) 0.006 ms/op
Iteration   2: 2.983 ±(99.9%) 0.003 ms/op
Iteration   3: 2.971 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.986 ±(99.9%) 0.302 ms/op [Average]
  (min, avg, max) = (2.971, 2.986, 3.004), stdev = 0.017
  CI (99.9%): [2.684, 3.289] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.642 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.860 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.818 ±(99.9%) 0.004 ms/op
Iteration   1: 2.826 ±(99.9%) 0.005 ms/op
Iteration   2: 2.834 ±(99.9%) 0.002 ms/op
Iteration   3: 2.856 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.839 ±(99.9%) 0.287 ms/op [Average]
  (min, avg, max) = (2.826, 2.839, 2.856), stdev = 0.016
  CI (99.9%): [2.551, 3.126] (assumes normal distribution)


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
# Warmup Iteration   1: 4.008 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.073 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.956 ±(99.9%) 0.004 ms/op
Iteration   1: 2.954 ±(99.9%) 0.002 ms/op
Iteration   2: 2.970 ±(99.9%) 0.003 ms/op
Iteration   3: 2.969 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.965 ±(99.9%) 0.163 ms/op [Average]
  (min, avg, max) = (2.954, 2.965, 2.970), stdev = 0.009
  CI (99.9%): [2.802, 3.128] (assumes normal distribution)


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
# Warmup Iteration   1: 4.599 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.971 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 3.913 ±(99.9%) 0.011 ms/op
Iteration   1: 3.862 ±(99.9%) 0.040 ms/op
Iteration   2: 3.846 ±(99.9%) 0.044 ms/op
Iteration   3: 3.885 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.864 ±(99.9%) 0.355 ms/op [Average]
  (min, avg, max) = (3.846, 3.864, 3.885), stdev = 0.019
  CI (99.9%): [3.510, 4.219] (assumes normal distribution)


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
# Warmup Iteration   1: 3.979 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.125 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.970 ±(99.9%) 0.006 ms/op
Iteration   1: 2.974 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.810 ms/op
                 createUser·p0.50:   2.957 ms/op
                 createUser·p0.90:   3.478 ms/op
                 createUser·p0.95:   3.650 ms/op
                 createUser·p0.99:   4.235 ms/op
                 createUser·p0.999:  7.576 ms/op
                 createUser·p0.9999: 11.272 ms/op
                 createUser·p1.00:   11.387 ms/op

Iteration   2: 2.967 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.639 ms/op
                 createUser·p0.50:   2.976 ms/op
                 createUser·p0.90:   3.404 ms/op
                 createUser·p0.95:   3.625 ms/op
                 createUser·p0.99:   4.530 ms/op
                 createUser·p0.999:  11.915 ms/op
                 createUser·p0.9999: 18.055 ms/op
                 createUser·p1.00:   22.577 ms/op

Iteration   3: 2.968 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.209 ms/op
                 createUser·p0.50:   2.968 ms/op
                 createUser·p0.90:   3.473 ms/op
                 createUser·p0.95:   3.698 ms/op
                 createUser·p0.99:   4.268 ms/op
                 createUser·p0.999:  8.957 ms/op
                 createUser·p0.9999: 14.524 ms/op
                 createUser·p1.00:   16.581 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 323145
  mean =      2.969 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 32779 
    [ 2.500,  5.000) = 289002 
    [ 5.000,  7.500) = 821 
    [ 7.500, 10.000) = 221 
    [10.000, 12.500) = 174 
    [12.500, 15.000) = 92 
    [15.000, 17.500) = 17 
    [17.500, 20.000) = 36 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.209 ms/op
     p(50.0000) =      2.966 ms/op
     p(90.0000) =      3.453 ms/op
     p(95.0000) =      3.662 ms/op
     p(99.0000) =      4.366 ms/op
     p(99.9000) =      9.959 ms/op
     p(99.9900) =     17.891 ms/op
     p(99.9990) =     20.036 ms/op
     p(99.9999) =     22.577 ms/op
    p(100.0000) =     22.577 ms/op


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
# Warmup Iteration   1: 3.732 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 2.883 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.875 ±(99.9%) 0.006 ms/op
Iteration   1: 2.834 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.557 ms/op
                 existUser·p0.50:   2.839 ms/op
                 existUser·p0.90:   3.240 ms/op
                 existUser·p0.95:   3.465 ms/op
                 existUser·p0.99:   4.407 ms/op
                 existUser·p0.999:  7.300 ms/op
                 existUser·p0.9999: 11.066 ms/op
                 existUser·p1.00:   11.403 ms/op

Iteration   2: 2.884 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.847 ms/op
                 existUser·p0.50:   2.863 ms/op
                 existUser·p0.90:   3.359 ms/op
                 existUser·p0.95:   3.527 ms/op
                 existUser·p0.99:   4.432 ms/op
                 existUser·p0.999:  6.128 ms/op
                 existUser·p0.9999: 16.974 ms/op
                 existUser·p1.00:   18.678 ms/op

Iteration   3: 2.868 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.734 ms/op
                 existUser·p0.50:   2.879 ms/op
                 existUser·p0.90:   3.391 ms/op
                 existUser·p0.95:   3.543 ms/op
                 existUser·p0.99:   4.193 ms/op
                 existUser·p0.999:  5.705 ms/op
                 existUser·p0.9999: 13.301 ms/op
                 existUser·p1.00:   13.517 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 335474
  mean =      2.862 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2547 
    [ 1.250,  2.500) = 47133 
    [ 2.500,  3.750) = 277304 
    [ 3.750,  5.000) = 7415 
    [ 5.000,  6.250) = 718 
    [ 6.250,  7.500) = 146 
    [ 7.500,  8.750) = 18 
    [ 8.750, 10.000) = 21 
    [10.000, 11.250) = 72 
    [11.250, 12.500) = 33 
    [12.500, 13.750) = 35 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 31 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.557 ms/op
     p(50.0000) =      2.859 ms/op
     p(90.0000) =      3.338 ms/op
     p(95.0000) =      3.523 ms/op
     p(99.0000) =      4.350 ms/op
     p(99.9000) =      6.308 ms/op
     p(99.9900) =     13.499 ms/op
     p(99.9990) =     17.388 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.939 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.052 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.017 ±(99.9%) 0.006 ms/op
Iteration   1: 3.018 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.563 ms/op
                 getUser·p0.50:   3.002 ms/op
                 getUser·p0.90:   3.617 ms/op
                 getUser·p0.95:   3.785 ms/op
                 getUser·p0.99:   4.317 ms/op
                 getUser·p0.999:  6.611 ms/op
                 getUser·p0.9999: 11.672 ms/op
                 getUser·p1.00:   12.091 ms/op

Iteration   2: 2.994 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.881 ms/op
                 getUser·p0.50:   2.982 ms/op
                 getUser·p0.90:   3.412 ms/op
                 getUser·p0.95:   3.604 ms/op
                 getUser·p0.99:   4.342 ms/op
                 getUser·p0.999:  6.005 ms/op
                 getUser·p0.9999: 19.202 ms/op
                 getUser·p1.00:   19.235 ms/op

Iteration   3: 2.987 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.573 ms/op
                 getUser·p0.50:   2.961 ms/op
                 getUser·p0.90:   3.535 ms/op
                 getUser·p0.95:   3.785 ms/op
                 getUser·p0.99:   4.391 ms/op
                 getUser·p0.999:  10.223 ms/op
                 getUser·p0.9999: 13.641 ms/op
                 getUser·p1.00:   14.729 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 319961
  mean =      3.000 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1282 
    [ 1.250,  2.500) = 24788 
    [ 2.500,  3.750) = 277867 
    [ 3.750,  5.000) = 15169 
    [ 5.000,  6.250) = 444 
    [ 6.250,  7.500) = 160 
    [ 7.500,  8.750) = 11 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 90 
    [11.250, 12.500) = 51 
    [12.500, 13.750) = 59 
    [13.750, 15.000) = 8 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.563 ms/op
     p(50.0000) =      2.982 ms/op
     p(90.0000) =      3.531 ms/op
     p(95.0000) =      3.752 ms/op
     p(99.0000) =      4.350 ms/op
     p(99.9000) =      6.652 ms/op
     p(99.9900) =     18.416 ms/op
     p(99.9990) =     19.235 ms/op
     p(99.9999) =     19.235 ms/op
    p(100.0000) =     19.235 ms/op


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
# Warmup Iteration   1: 4.804 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 4.031 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.904 ±(99.9%) 0.010 ms/op
Iteration   1: 3.889 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.075 ms/op
                 listUser·p0.50:   3.781 ms/op
                 listUser·p0.90:   4.710 ms/op
                 listUser·p0.95:   5.489 ms/op
                 listUser·p0.99:   6.570 ms/op
                 listUser·p0.999:  12.953 ms/op
                 listUser·p0.9999: 17.097 ms/op
                 listUser·p1.00:   17.695 ms/op

Iteration   2: 3.927 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.970 ms/op
                 listUser·p0.50:   3.801 ms/op
                 listUser·p0.90:   4.784 ms/op
                 listUser·p0.95:   5.464 ms/op
                 listUser·p0.99:   6.832 ms/op
                 listUser·p0.999:  15.544 ms/op
                 listUser·p0.9999: 19.595 ms/op
                 listUser·p1.00:   20.185 ms/op

Iteration   3: 3.955 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.788 ms/op
                 listUser·p0.50:   3.805 ms/op
                 listUser·p0.90:   4.964 ms/op
                 listUser·p0.95:   5.595 ms/op
                 listUser·p0.99:   6.930 ms/op
                 listUser·p0.999:  14.041 ms/op
                 listUser·p0.9999: 16.965 ms/op
                 listUser·p1.00:   21.725 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 244680
  mean =      3.924 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5529 
    [ 2.500,  5.000) = 219058 
    [ 5.000,  7.500) = 18896 
    [ 7.500, 10.000) = 683 
    [10.000, 12.500) = 93 
    [12.500, 15.000) = 211 
    [15.000, 17.500) = 150 
    [17.500, 20.000) = 54 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.788 ms/op
     p(50.0000) =      3.797 ms/op
     p(90.0000) =      4.833 ms/op
     p(95.0000) =      5.530 ms/op
     p(99.0000) =      6.783 ms/op
     p(99.9000) =     14.533 ms/op
     p(99.9900) =     19.121 ms/op
     p(99.9990) =     20.516 ms/op
     p(99.9999) =     21.725 ms/op
    p(100.0000) =     21.725 ms/op


# Run complete. Total time: 00:13:02

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.662 ± 2.846  ops/ms
ClientGrpc.existUser                       thrpt       3  11.257 ± 1.886  ops/ms
ClientGrpc.getUser                         thrpt       3  10.793 ± 1.882  ops/ms
ClientGrpc.listUser                        thrpt       3   8.238 ± 1.426  ops/ms
ClientGrpc.createUser                       avgt       3   2.986 ± 0.302   ms/op
ClientGrpc.existUser                        avgt       3   2.839 ± 0.287   ms/op
ClientGrpc.getUser                          avgt       3   2.965 ± 0.163   ms/op
ClientGrpc.listUser                         avgt       3   3.864 ± 0.355   ms/op
ClientGrpc.createUser                     sample  323145   2.969 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.209           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.966           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.453           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.662           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.366           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.959           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.891           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.577           ms/op
ClientGrpc.existUser                      sample  335474   2.862 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.557           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.859           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.338           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.523           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.350           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.308           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          13.499           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.678           ms/op
ClientGrpc.getUser                        sample  319961   3.000 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.563           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.982           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.531           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.752           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.350           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.652           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.416           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.235           ms/op
ClientGrpc.listUser                       sample  244680   3.924 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.788           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.797           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.833           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.530           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.783           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.533           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          19.121           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          21.725           ms/op
