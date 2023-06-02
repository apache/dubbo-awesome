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
# Warmup Iteration   1: 4.475 ops/ms
# Warmup Iteration   2: 9.438 ops/ms
# Warmup Iteration   3: 10.374 ops/ms
Iteration   1: 10.565 ops/ms
Iteration   2: 10.594 ops/ms
Iteration   3: 10.578 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.579 ±(99.9%) 0.264 ops/ms [Average]
  (min, avg, max) = (10.565, 10.579, 10.594), stdev = 0.014
  CI (99.9%): [10.315, 10.842] (assumes normal distribution)


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
# Warmup Iteration   1: 8.605 ops/ms
# Warmup Iteration   2: 10.764 ops/ms
# Warmup Iteration   3: 11.199 ops/ms
Iteration   1: 11.131 ops/ms
Iteration   2: 11.021 ops/ms
Iteration   3: 11.217 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.123 ±(99.9%) 1.792 ops/ms [Average]
  (min, avg, max) = (11.021, 11.123, 11.217), stdev = 0.098
  CI (99.9%): [9.331, 12.915] (assumes normal distribution)


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
# Warmup Iteration   1: 7.763 ops/ms
# Warmup Iteration   2: 10.259 ops/ms
# Warmup Iteration   3: 10.655 ops/ms
Iteration   1: 10.898 ops/ms
Iteration   2: 10.810 ops/ms
Iteration   3: 10.721 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.810 ±(99.9%) 1.609 ops/ms [Average]
  (min, avg, max) = (10.721, 10.810, 10.898), stdev = 0.088
  CI (99.9%): [9.201, 12.419] (assumes normal distribution)


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
# Warmup Iteration   1: 5.459 ops/ms
# Warmup Iteration   2: 8.033 ops/ms
# Warmup Iteration   3: 7.937 ops/ms
Iteration   1: 8.031 ops/ms
Iteration   2: 7.952 ops/ms
Iteration   3: 7.867 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.950 ±(99.9%) 1.497 ops/ms [Average]
  (min, avg, max) = (7.867, 7.950, 8.031), stdev = 0.082
  CI (99.9%): [6.453, 9.447] (assumes normal distribution)


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
# Warmup Iteration   1: 4.157 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.109 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.018 ±(99.9%) 0.003 ms/op
Iteration   1: 3.031 ±(99.9%) 0.003 ms/op
Iteration   2: 3.015 ±(99.9%) 0.002 ms/op
Iteration   3: 3.054 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.033 ±(99.9%) 0.356 ms/op [Average]
  (min, avg, max) = (3.015, 3.033, 3.054), stdev = 0.020
  CI (99.9%): [2.677, 3.389] (assumes normal distribution)


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
# Warmup Iteration   1: 3.947 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.931 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.922 ±(99.9%) 0.002 ms/op
Iteration   1: 2.887 ±(99.9%) 0.003 ms/op
Iteration   2: 2.946 ±(99.9%) 0.002 ms/op
Iteration   3: 2.890 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.908 ±(99.9%) 0.609 ms/op [Average]
  (min, avg, max) = (2.887, 2.908, 2.946), stdev = 0.033
  CI (99.9%): [2.299, 3.517] (assumes normal distribution)


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
# Warmup Iteration   1: 4.053 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.105 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.059 ±(99.9%) 0.003 ms/op
Iteration   1: 3.052 ±(99.9%) 0.003 ms/op
Iteration   2: 3.020 ±(99.9%) 0.002 ms/op
Iteration   3: 2.987 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.020 ±(99.9%) 0.597 ms/op [Average]
  (min, avg, max) = (2.987, 3.020, 3.052), stdev = 0.033
  CI (99.9%): [2.423, 3.616] (assumes normal distribution)


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
# Warmup Iteration   1: 5.072 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 4.081 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 3.984 ±(99.9%) 0.020 ms/op
Iteration   1: 3.934 ±(99.9%) 0.012 ms/op
Iteration   2: 3.883 ±(99.9%) 0.052 ms/op
Iteration   3: 3.768 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.862 ±(99.9%) 1.554 ms/op [Average]
  (min, avg, max) = (3.768, 3.862, 3.934), stdev = 0.085
  CI (99.9%): [2.308, 5.416] (assumes normal distribution)


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
# Warmup Iteration   1: 3.938 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.152 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.002 ±(99.9%) 0.006 ms/op
Iteration   1: 2.958 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.559 ms/op
                 createUser·p0.50:   2.957 ms/op
                 createUser·p0.90:   3.445 ms/op
                 createUser·p0.95:   3.641 ms/op
                 createUser·p0.99:   4.432 ms/op
                 createUser·p0.999:  6.978 ms/op
                 createUser·p0.9999: 13.864 ms/op
                 createUser·p1.00:   14.746 ms/op

Iteration   2: 2.964 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.733 ms/op
                 createUser·p0.50:   2.961 ms/op
                 createUser·p0.90:   3.457 ms/op
                 createUser·p0.95:   3.658 ms/op
                 createUser·p0.99:   4.506 ms/op
                 createUser·p0.999:  7.135 ms/op
                 createUser·p0.9999: 13.331 ms/op
                 createUser·p1.00:   13.713 ms/op

Iteration   3: 3.029 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.648 ms/op
                 createUser·p0.50:   2.998 ms/op
                 createUser·p0.90:   3.531 ms/op
                 createUser·p0.95:   3.695 ms/op
                 createUser·p0.99:   4.251 ms/op
                 createUser·p0.999:  8.066 ms/op
                 createUser·p0.9999: 16.686 ms/op
                 createUser·p1.00:   17.203 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 321596
  mean =      2.983 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1159 
    [ 1.250,  2.500) = 27711 
    [ 2.500,  3.750) = 280376 
    [ 3.750,  5.000) = 11337 
    [ 5.000,  6.250) = 462 
    [ 6.250,  7.500) = 269 
    [ 7.500,  8.750) = 72 
    [ 8.750, 10.000) = 18 
    [10.000, 11.250) = 16 
    [11.250, 12.500) = 38 
    [12.500, 13.750) = 60 
    [13.750, 15.000) = 41 
    [15.000, 16.250) = 6 
    [16.250, 17.500) = 31 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.559 ms/op
     p(50.0000) =      2.970 ms/op
     p(90.0000) =      3.482 ms/op
     p(95.0000) =      3.670 ms/op
     p(99.0000) =      4.407 ms/op
     p(99.9000) =      7.135 ms/op
     p(99.9900) =     16.052 ms/op
     p(99.9990) =     17.131 ms/op
     p(99.9999) =     17.203 ms/op
    p(100.0000) =     17.203 ms/op


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
# Warmup Iteration   1: 3.713 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 2.949 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.841 ±(99.9%) 0.006 ms/op
Iteration   1: 2.925 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.771 ms/op
                 existUser·p0.50:   2.900 ms/op
                 existUser·p0.90:   3.478 ms/op
                 existUser·p0.95:   3.674 ms/op
                 existUser·p0.99:   4.391 ms/op
                 existUser·p0.999:  7.782 ms/op
                 existUser·p0.9999: 18.579 ms/op
                 existUser·p1.00:   18.940 ms/op

Iteration   2: 2.856 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.673 ms/op
                 existUser·p0.50:   2.871 ms/op
                 existUser·p0.90:   3.281 ms/op
                 existUser·p0.95:   3.527 ms/op
                 existUser·p0.99:   4.399 ms/op
                 existUser·p0.999:  6.299 ms/op
                 existUser·p0.9999: 14.123 ms/op
                 existUser·p1.00:   15.974 ms/op

Iteration   3: 2.871 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.523 ms/op
                 existUser·p0.50:   2.863 ms/op
                 existUser·p0.90:   3.236 ms/op
                 existUser·p0.95:   3.453 ms/op
                 existUser·p0.99:   4.190 ms/op
                 existUser·p0.999:  6.002 ms/op
                 existUser·p0.9999: 15.483 ms/op
                 existUser·p1.00:   18.612 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 332754
  mean =      2.884 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2453 
    [ 1.250,  2.500) = 36449 
    [ 2.500,  3.750) = 284109 
    [ 3.750,  5.000) = 8949 
    [ 5.000,  6.250) = 461 
    [ 6.250,  7.500) = 98 
    [ 7.500,  8.750) = 39 
    [ 8.750, 10.000) = 6 
    [10.000, 11.250) = 28 
    [11.250, 12.500) = 15 
    [12.500, 13.750) = 25 
    [13.750, 15.000) = 57 
    [15.000, 16.250) = 27 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.523 ms/op
     p(50.0000) =      2.875 ms/op
     p(90.0000) =      3.330 ms/op
     p(95.0000) =      3.580 ms/op
     p(99.0000) =      4.350 ms/op
     p(99.9000) =      6.253 ms/op
     p(99.9900) =     17.718 ms/op
     p(99.9990) =     18.853 ms/op
     p(99.9999) =     18.940 ms/op
    p(100.0000) =     18.940 ms/op


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
# Warmup Iteration   1: 4.111 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.108 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.963 ±(99.9%) 0.006 ms/op
Iteration   1: 3.127 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.978 ms/op
                 getUser·p0.50:   3.105 ms/op
                 getUser·p0.90:   3.650 ms/op
                 getUser·p0.95:   3.793 ms/op
                 getUser·p0.99:   4.293 ms/op
                 getUser·p0.999:  6.662 ms/op
                 getUser·p0.9999: 10.158 ms/op
                 getUser·p1.00:   10.469 ms/op

Iteration   2: 2.972 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.677 ms/op
                 getUser·p0.50:   2.994 ms/op
                 getUser·p0.90:   3.387 ms/op
                 getUser·p0.95:   3.625 ms/op
                 getUser·p0.99:   4.366 ms/op
                 getUser·p0.999:  5.816 ms/op
                 getUser·p0.9999: 12.677 ms/op
                 getUser·p1.00:   12.927 ms/op

Iteration   3: 3.005 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.534 ms/op
                 getUser·p0.50:   3.002 ms/op
                 getUser·p0.90:   3.486 ms/op
                 getUser·p0.95:   3.654 ms/op
                 getUser·p0.99:   4.317 ms/op
                 getUser·p0.999:  6.773 ms/op
                 getUser·p0.9999: 24.314 ms/op
                 getUser·p1.00:   25.461 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 316397
  mean =      3.034 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19308 
    [ 2.500,  5.000) = 296138 
    [ 5.000,  7.500) = 729 
    [ 7.500, 10.000) = 53 
    [10.000, 12.500) = 88 
    [12.500, 15.000) = 17 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.534 ms/op
     p(50.0000) =      3.023 ms/op
     p(90.0000) =      3.547 ms/op
     p(95.0000) =      3.711 ms/op
     p(99.0000) =      4.317 ms/op
     p(99.9000) =      6.396 ms/op
     p(99.9900) =     23.048 ms/op
     p(99.9990) =     25.326 ms/op
     p(99.9999) =     25.461 ms/op
    p(100.0000) =     25.461 ms/op


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
# Warmup Iteration   1: 4.330 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 4.221 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.940 ±(99.9%) 0.010 ms/op
Iteration   1: 4.000 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.243 ms/op
                 listUser·p0.50:   3.805 ms/op
                 listUser·p0.90:   5.186 ms/op
                 listUser·p0.95:   5.734 ms/op
                 listUser·p0.99:   7.104 ms/op
                 listUser·p0.999:  12.976 ms/op
                 listUser·p0.9999: 19.530 ms/op
                 listUser·p1.00:   20.021 ms/op

Iteration   2: 4.013 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.900 ms/op
                 listUser·p0.50:   3.879 ms/op
                 listUser·p0.90:   4.866 ms/op
                 listUser·p0.95:   5.734 ms/op
                 listUser·p0.99:   6.849 ms/op
                 listUser·p0.999:  16.033 ms/op
                 listUser·p0.9999: 22.808 ms/op
                 listUser·p1.00:   23.200 ms/op

Iteration   3: 3.900 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   0.578 ms/op
                 listUser·p0.50:   3.719 ms/op
                 listUser·p0.90:   5.030 ms/op
                 listUser·p0.95:   5.915 ms/op
                 listUser·p0.99:   7.021 ms/op
                 listUser·p0.999:  20.085 ms/op
                 listUser·p0.9999: 23.947 ms/op
                 listUser·p1.00:   24.838 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 241695
  mean =      3.970 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5015 
    [ 2.500,  5.000) = 210386 
    [ 5.000,  7.500) = 24898 
    [ 7.500, 10.000) = 812 
    [10.000, 12.500) = 144 
    [12.500, 15.000) = 143 
    [15.000, 17.500) = 116 
    [17.500, 20.000) = 66 
    [20.000, 22.500) = 68 
    [22.500, 25.000) = 47 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.578 ms/op
     p(50.0000) =      3.809 ms/op
     p(90.0000) =      5.079 ms/op
     p(95.0000) =      5.800 ms/op
     p(99.0000) =      6.980 ms/op
     p(99.9000) =     16.007 ms/op
     p(99.9900) =     23.364 ms/op
     p(99.9990) =     24.732 ms/op
     p(99.9999) =     24.838 ms/op
    p(100.0000) =     24.838 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.579 ± 0.264  ops/ms
ClientGrpc.existUser                       thrpt       3  11.123 ± 1.792  ops/ms
ClientGrpc.getUser                         thrpt       3  10.810 ± 1.609  ops/ms
ClientGrpc.listUser                        thrpt       3   7.950 ± 1.497  ops/ms
ClientGrpc.createUser                       avgt       3   3.033 ± 0.356   ms/op
ClientGrpc.existUser                        avgt       3   2.908 ± 0.609   ms/op
ClientGrpc.getUser                          avgt       3   3.020 ± 0.597   ms/op
ClientGrpc.listUser                         avgt       3   3.862 ± 1.554   ms/op
ClientGrpc.createUser                     sample  321596   2.983 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.559           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.970           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.482           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.670           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.407           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.135           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          16.052           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          17.203           ms/op
ClientGrpc.existUser                      sample  332754   2.884 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.523           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.875           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.330           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.580           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.350           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.253           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.718           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.940           ms/op
ClientGrpc.getUser                        sample  316397   3.034 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.534           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.023           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.547           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.711           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.317           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.396           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          23.048           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          25.461           ms/op
ClientGrpc.listUser                       sample  241695   3.970 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.578           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.809           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.079           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.800           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.980           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.007           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.364           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.838           ms/op
