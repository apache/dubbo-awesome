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
# Warmup Iteration   1: 4.415 ops/ms
# Warmup Iteration   2: 9.272 ops/ms
# Warmup Iteration   3: 10.098 ops/ms
Iteration   1: 10.442 ops/ms
Iteration   2: 10.500 ops/ms
Iteration   3: 10.452 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.464 ±(99.9%) 0.566 ops/ms [Average]
  (min, avg, max) = (10.442, 10.464, 10.500), stdev = 0.031
  CI (99.9%): [9.898, 11.031] (assumes normal distribution)


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
# Warmup Iteration   1: 8.255 ops/ms
# Warmup Iteration   2: 10.704 ops/ms
# Warmup Iteration   3: 10.768 ops/ms
Iteration   1: 10.985 ops/ms
Iteration   2: 11.150 ops/ms
Iteration   3: 11.116 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.084 ±(99.9%) 1.590 ops/ms [Average]
  (min, avg, max) = (10.985, 11.084, 11.150), stdev = 0.087
  CI (99.9%): [9.494, 12.674] (assumes normal distribution)


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
# Warmup Iteration   1: 7.550 ops/ms
# Warmup Iteration   2: 10.347 ops/ms
# Warmup Iteration   3: 10.530 ops/ms
Iteration   1: 10.776 ops/ms
Iteration   2: 10.701 ops/ms
Iteration   3: 10.665 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.714 ±(99.9%) 1.035 ops/ms [Average]
  (min, avg, max) = (10.665, 10.714, 10.776), stdev = 0.057
  CI (99.9%): [9.679, 11.749] (assumes normal distribution)


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
# Warmup Iteration   1: 5.498 ops/ms
# Warmup Iteration   2: 7.886 ops/ms
# Warmup Iteration   3: 8.080 ops/ms
Iteration   1: 8.156 ops/ms
Iteration   2: 8.098 ops/ms
Iteration   3: 8.090 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.115 ±(99.9%) 0.662 ops/ms [Average]
  (min, avg, max) = (8.090, 8.115, 8.156), stdev = 0.036
  CI (99.9%): [7.453, 8.777] (assumes normal distribution)


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
# Warmup Iteration   1: 4.040 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.090 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 2.933 ±(99.9%) 0.004 ms/op
Iteration   1: 3.015 ±(99.9%) 0.003 ms/op
Iteration   2: 2.983 ±(99.9%) 0.003 ms/op
Iteration   3: 3.026 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.008 ±(99.9%) 0.410 ms/op [Average]
  (min, avg, max) = (2.983, 3.008, 3.026), stdev = 0.022
  CI (99.9%): [2.598, 3.418] (assumes normal distribution)


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
# Warmup Iteration   1: 3.433 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.931 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.897 ±(99.9%) 0.003 ms/op
Iteration   1: 2.930 ±(99.9%) 0.003 ms/op
Iteration   2: 2.909 ±(99.9%) 0.002 ms/op
Iteration   3: 2.872 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.904 ±(99.9%) 0.534 ms/op [Average]
  (min, avg, max) = (2.872, 2.904, 2.930), stdev = 0.029
  CI (99.9%): [2.370, 3.438] (assumes normal distribution)


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
# Warmup Iteration   1: 3.920 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.078 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.000 ±(99.9%) 0.003 ms/op
Iteration   1: 3.005 ±(99.9%) 0.002 ms/op
Iteration   2: 2.978 ±(99.9%) 0.003 ms/op
Iteration   3: 2.999 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.994 ±(99.9%) 0.254 ms/op [Average]
  (min, avg, max) = (2.978, 2.994, 3.005), stdev = 0.014
  CI (99.9%): [2.740, 3.248] (assumes normal distribution)


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
# Warmup Iteration   1: 5.253 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.997 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 3.843 ±(99.9%) 0.010 ms/op
Iteration   1: 3.900 ±(99.9%) 0.018 ms/op
Iteration   2: 3.945 ±(99.9%) 0.009 ms/op
Iteration   3: 3.759 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.868 ±(99.9%) 1.773 ms/op [Average]
  (min, avg, max) = (3.759, 3.868, 3.945), stdev = 0.097
  CI (99.9%): [2.096, 5.641] (assumes normal distribution)


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
# Warmup Iteration   1: 3.860 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.127 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.977 ±(99.9%) 0.006 ms/op
Iteration   1: 2.940 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.373 ms/op
                 createUser·p0.50:   2.961 ms/op
                 createUser·p0.90:   3.359 ms/op
                 createUser·p0.95:   3.621 ms/op
                 createUser·p0.99:   4.375 ms/op
                 createUser·p0.999:  9.228 ms/op
                 createUser·p0.9999: 11.846 ms/op
                 createUser·p1.00:   16.040 ms/op

Iteration   2: 2.972 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.700 ms/op
                 createUser·p0.50:   2.978 ms/op
                 createUser·p0.90:   3.473 ms/op
                 createUser·p0.95:   3.662 ms/op
                 createUser·p0.99:   4.284 ms/op
                 createUser·p0.999:  6.442 ms/op
                 createUser·p0.9999: 13.586 ms/op
                 createUser·p1.00:   13.779 ms/op

Iteration   3: 3.013 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.772 ms/op
                 createUser·p0.50:   2.978 ms/op
                 createUser·p0.90:   3.514 ms/op
                 createUser·p0.95:   3.744 ms/op
                 createUser·p0.99:   4.399 ms/op
                 createUser·p0.999:  8.258 ms/op
                 createUser·p0.9999: 26.575 ms/op
                 createUser·p1.00:   26.804 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 322685
  mean =      2.975 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 28078 
    [ 2.500,  5.000) = 293188 
    [ 5.000,  7.500) = 1086 
    [ 7.500, 10.000) = 106 
    [10.000, 12.500) = 70 
    [12.500, 15.000) = 92 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.373 ms/op
     p(50.0000) =      2.970 ms/op
     p(90.0000) =      3.461 ms/op
     p(95.0000) =      3.682 ms/op
     p(99.0000) =      4.350 ms/op
     p(99.9000) =      8.258 ms/op
     p(99.9900) =     23.826 ms/op
     p(99.9990) =     26.764 ms/op
     p(99.9999) =     26.804 ms/op
    p(100.0000) =     26.804 ms/op


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
# Warmup Iteration   1: 3.808 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 2.997 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.894 ±(99.9%) 0.006 ms/op
Iteration   1: 2.866 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.681 ms/op
                 existUser·p0.50:   2.875 ms/op
                 existUser·p0.90:   3.400 ms/op
                 existUser·p0.95:   3.629 ms/op
                 existUser·p0.99:   4.473 ms/op
                 existUser·p0.999:  6.655 ms/op
                 existUser·p0.9999: 12.660 ms/op
                 existUser·p1.00:   13.025 ms/op

Iteration   2: 2.902 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.743 ms/op
                 existUser·p0.50:   2.896 ms/op
                 existUser·p0.90:   3.420 ms/op
                 existUser·p0.95:   3.609 ms/op
                 existUser·p0.99:   4.383 ms/op
                 existUser·p0.999:  6.399 ms/op
                 existUser·p0.9999: 13.858 ms/op
                 existUser·p1.00:   15.041 ms/op

Iteration   3: 2.920 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.581 ms/op
                 existUser·p0.50:   2.920 ms/op
                 existUser·p0.90:   3.432 ms/op
                 existUser·p0.95:   3.654 ms/op
                 existUser·p0.99:   4.252 ms/op
                 existUser·p0.999:  7.345 ms/op
                 existUser·p0.9999: 16.765 ms/op
                 existUser·p1.00:   18.350 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 331550
  mean =      2.896 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3398 
    [ 1.250,  2.500) = 41443 
    [ 2.500,  3.750) = 274537 
    [ 3.750,  5.000) = 10984 
    [ 5.000,  6.250) = 705 
    [ 6.250,  7.500) = 245 
    [ 7.500,  8.750) = 45 
    [ 8.750, 10.000) = 19 
    [10.000, 11.250) = 33 
    [11.250, 12.500) = 33 
    [12.500, 13.750) = 34 
    [13.750, 15.000) = 19 
    [15.000, 16.250) = 44 
    [16.250, 17.500) = 3 
    [17.500, 18.750) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.581 ms/op
     p(50.0000) =      2.896 ms/op
     p(90.0000) =      3.420 ms/op
     p(95.0000) =      3.633 ms/op
     p(99.0000) =      4.399 ms/op
     p(99.9000) =      6.794 ms/op
     p(99.9900) =     15.620 ms/op
     p(99.9990) =     18.307 ms/op
     p(99.9999) =     18.350 ms/op
    p(100.0000) =     18.350 ms/op


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
# Warmup Iteration   1: 3.995 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.140 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.024 ±(99.9%) 0.007 ms/op
Iteration   1: 2.989 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.778 ms/op
                 getUser·p0.50:   2.970 ms/op
                 getUser·p0.90:   3.523 ms/op
                 getUser·p0.95:   3.809 ms/op
                 getUser·p0.99:   4.588 ms/op
                 getUser·p0.999:  6.193 ms/op
                 getUser·p0.9999: 12.047 ms/op
                 getUser·p1.00:   12.419 ms/op

Iteration   2: 2.939 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.733 ms/op
                 getUser·p0.50:   2.970 ms/op
                 getUser·p0.90:   3.363 ms/op
                 getUser·p0.95:   3.609 ms/op
                 getUser·p0.99:   4.317 ms/op
                 getUser·p0.999:  7.087 ms/op
                 getUser·p0.9999: 14.504 ms/op
                 getUser·p1.00:   14.959 ms/op

Iteration   3: 2.966 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.392 ms/op
                 getUser·p0.50:   2.957 ms/op
                 getUser·p0.90:   3.469 ms/op
                 getUser·p0.95:   3.678 ms/op
                 getUser·p0.99:   4.334 ms/op
                 getUser·p0.999:  6.579 ms/op
                 getUser·p0.9999: 14.683 ms/op
                 getUser·p1.00:   15.778 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 323766
  mean =      2.964 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1797 
    [ 1.250,  2.500) = 29618 
    [ 2.500,  3.750) = 277755 
    [ 3.750,  5.000) = 13564 
    [ 5.000,  6.250) = 631 
    [ 6.250,  7.500) = 177 
    [ 7.500,  8.750) = 25 
    [ 8.750, 10.000) = 7 
    [10.000, 11.250) = 9 
    [11.250, 12.500) = 66 
    [12.500, 13.750) = 65 
    [13.750, 15.000) = 49 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.392 ms/op
     p(50.0000) =      2.966 ms/op
     p(90.0000) =      3.453 ms/op
     p(95.0000) =      3.711 ms/op
     p(99.0000) =      4.391 ms/op
     p(99.9000) =      6.551 ms/op
     p(99.9900) =     14.582 ms/op
     p(99.9990) =     15.054 ms/op
     p(99.9999) =     15.778 ms/op
    p(100.0000) =     15.778 ms/op


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
# Warmup Iteration   1: 4.858 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 4.061 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.875 ±(99.9%) 0.011 ms/op
Iteration   1: 3.990 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.227 ms/op
                 listUser·p0.50:   3.846 ms/op
                 listUser·p0.90:   4.940 ms/op
                 listUser·p0.95:   5.587 ms/op
                 listUser·p0.99:   6.693 ms/op
                 listUser·p0.999:  12.962 ms/op
                 listUser·p0.9999: 20.708 ms/op
                 listUser·p1.00:   21.004 ms/op

Iteration   2: 3.965 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.488 ms/op
                 listUser·p0.50:   3.813 ms/op
                 listUser·p0.90:   4.948 ms/op
                 listUser·p0.95:   5.562 ms/op
                 listUser·p0.99:   6.726 ms/op
                 listUser·p0.999:  14.257 ms/op
                 listUser·p0.9999: 20.379 ms/op
                 listUser·p1.00:   21.823 ms/op

Iteration   3: 3.964 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.944 ms/op
                 listUser·p0.50:   3.826 ms/op
                 listUser·p0.90:   4.624 ms/op
                 listUser·p0.95:   5.523 ms/op
                 listUser·p0.99:   6.783 ms/op
                 listUser·p0.999:  19.110 ms/op
                 listUser·p0.9999: 22.544 ms/op
                 listUser·p1.00:   23.921 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 241923
  mean =      3.973 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2843 
    [ 2.500,  5.000) = 218002 
    [ 5.000,  7.500) = 20029 
    [ 7.500, 10.000) = 560 
    [10.000, 12.500) = 102 
    [12.500, 15.000) = 138 
    [15.000, 17.500) = 43 
    [17.500, 20.000) = 138 
    [20.000, 22.500) = 56 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.488 ms/op
     p(50.0000) =      3.830 ms/op
     p(90.0000) =      4.866 ms/op
     p(95.0000) =      5.562 ms/op
     p(99.0000) =      6.734 ms/op
     p(99.9000) =     15.325 ms/op
     p(99.9900) =     22.079 ms/op
     p(99.9990) =     23.281 ms/op
     p(99.9999) =     23.921 ms/op
    p(100.0000) =     23.921 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.464 ± 0.566  ops/ms
ClientGrpc.existUser                       thrpt       3  11.084 ± 1.590  ops/ms
ClientGrpc.getUser                         thrpt       3  10.714 ± 1.035  ops/ms
ClientGrpc.listUser                        thrpt       3   8.115 ± 0.662  ops/ms
ClientGrpc.createUser                       avgt       3   3.008 ± 0.410   ms/op
ClientGrpc.existUser                        avgt       3   2.904 ± 0.534   ms/op
ClientGrpc.getUser                          avgt       3   2.994 ± 0.254   ms/op
ClientGrpc.listUser                         avgt       3   3.868 ± 1.773   ms/op
ClientGrpc.createUser                     sample  322685   2.975 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.373           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.970           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.461           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.682           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.350           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.258           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          23.826           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          26.804           ms/op
ClientGrpc.existUser                      sample  331550   2.896 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.581           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.896           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.420           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.633           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.399           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.794           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.620           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.350           ms/op
ClientGrpc.getUser                        sample  323766   2.964 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.392           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.966           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.453           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.711           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.391           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.551           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          14.582           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          15.778           ms/op
ClientGrpc.listUser                       sample  241923   3.973 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.488           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.830           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.866           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.562           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.734           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.325           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.079           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.921           ms/op
