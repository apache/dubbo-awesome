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
# Warmup Iteration   1: 4.288 ops/ms
# Warmup Iteration   2: 9.418 ops/ms
# Warmup Iteration   3: 10.301 ops/ms
Iteration   1: 10.766 ops/ms
Iteration   2: 10.772 ops/ms
Iteration   3: 10.679 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.739 ±(99.9%) 0.950 ops/ms [Average]
  (min, avg, max) = (10.679, 10.739, 10.772), stdev = 0.052
  CI (99.9%): [9.789, 11.689] (assumes normal distribution)


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
# Warmup Iteration   1: 7.939 ops/ms
# Warmup Iteration   2: 11.045 ops/ms
# Warmup Iteration   3: 11.130 ops/ms
Iteration   1: 11.460 ops/ms
Iteration   2: 11.347 ops/ms
Iteration   3: 11.306 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.371 ±(99.9%) 1.449 ops/ms [Average]
  (min, avg, max) = (11.306, 11.371, 11.460), stdev = 0.079
  CI (99.9%): [9.922, 12.820] (assumes normal distribution)


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
# Warmup Iteration   1: 7.821 ops/ms
# Warmup Iteration   2: 10.523 ops/ms
# Warmup Iteration   3: 10.680 ops/ms
Iteration   1: 10.827 ops/ms
Iteration   2: 10.854 ops/ms
Iteration   3: 10.983 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.888 ±(99.9%) 1.524 ops/ms [Average]
  (min, avg, max) = (10.827, 10.888, 10.983), stdev = 0.084
  CI (99.9%): [9.364, 12.412] (assumes normal distribution)


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
# Warmup Iteration   1: 6.258 ops/ms
# Warmup Iteration   2: 8.236 ops/ms
# Warmup Iteration   3: 8.487 ops/ms
Iteration   1: 8.504 ops/ms
Iteration   2: 8.314 ops/ms
Iteration   3: 8.528 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.449 ±(99.9%) 2.136 ops/ms [Average]
  (min, avg, max) = (8.314, 8.449, 8.528), stdev = 0.117
  CI (99.9%): [6.312, 10.585] (assumes normal distribution)


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
# Warmup Iteration   1: 4.075 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.060 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.956 ±(99.9%) 0.003 ms/op
Iteration   1: 2.963 ±(99.9%) 0.004 ms/op
Iteration   2: 2.956 ±(99.9%) 0.003 ms/op
Iteration   3: 2.984 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.967 ±(99.9%) 0.271 ms/op [Average]
  (min, avg, max) = (2.956, 2.967, 2.984), stdev = 0.015
  CI (99.9%): [2.697, 3.238] (assumes normal distribution)


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
# Warmup Iteration   1: 3.728 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.880 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.868 ±(99.9%) 0.003 ms/op
Iteration   1: 2.864 ±(99.9%) 0.003 ms/op
Iteration   2: 2.826 ±(99.9%) 0.003 ms/op
Iteration   3: 2.793 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.828 ±(99.9%) 0.647 ms/op [Average]
  (min, avg, max) = (2.793, 2.828, 2.864), stdev = 0.035
  CI (99.9%): [2.180, 3.475] (assumes normal distribution)


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
# Warmup Iteration   1: 3.927 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.027 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.978 ±(99.9%) 0.002 ms/op
Iteration   1: 2.950 ±(99.9%) 0.003 ms/op
Iteration   2: 2.930 ±(99.9%) 0.003 ms/op
Iteration   3: 2.945 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.942 ±(99.9%) 0.193 ms/op [Average]
  (min, avg, max) = (2.930, 2.942, 2.950), stdev = 0.011
  CI (99.9%): [2.749, 3.134] (assumes normal distribution)


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
# Warmup Iteration   1: 4.813 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.858 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 3.857 ±(99.9%) 0.009 ms/op
Iteration   1: 3.796 ±(99.9%) 0.017 ms/op
Iteration   2: 3.750 ±(99.9%) 0.026 ms/op
Iteration   3: 3.744 ±(99.9%) 0.027 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.764 ±(99.9%) 0.519 ms/op [Average]
  (min, avg, max) = (3.744, 3.764, 3.796), stdev = 0.028
  CI (99.9%): [3.245, 4.282] (assumes normal distribution)


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
# Warmup Iteration   1: 3.791 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.083 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.991 ±(99.9%) 0.006 ms/op
Iteration   1: 2.956 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.811 ms/op
                 createUser·p0.50:   2.937 ms/op
                 createUser·p0.90:   3.498 ms/op
                 createUser·p0.95:   3.736 ms/op
                 createUser·p0.99:   4.489 ms/op
                 createUser·p0.999:  5.929 ms/op
                 createUser·p0.9999: 12.261 ms/op
                 createUser·p1.00:   12.616 ms/op

Iteration   2: 2.958 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.677 ms/op
                 createUser·p0.50:   2.957 ms/op
                 createUser·p0.90:   3.473 ms/op
                 createUser·p0.95:   3.678 ms/op
                 createUser·p0.99:   4.235 ms/op
                 createUser·p0.999:  6.234 ms/op
                 createUser·p0.9999: 22.419 ms/op
                 createUser·p1.00:   22.577 ms/op

Iteration   3: 2.925 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.561 ms/op
                 createUser·p0.50:   2.933 ms/op
                 createUser·p0.90:   3.334 ms/op
                 createUser·p0.95:   3.510 ms/op
                 createUser·p0.99:   4.325 ms/op
                 createUser·p0.999:  7.972 ms/op
                 createUser·p0.9999: 15.516 ms/op
                 createUser·p1.00:   15.614 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 325949
  mean =      2.946 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 35333 
    [ 2.500,  5.000) = 289682 
    [ 5.000,  7.500) = 639 
    [ 7.500, 10.000) = 39 
    [10.000, 12.500) = 131 
    [12.500, 15.000) = 38 
    [15.000, 17.500) = 55 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.561 ms/op
     p(50.0000) =      2.941 ms/op
     p(90.0000) =      3.437 ms/op
     p(95.0000) =      3.662 ms/op
     p(99.0000) =      4.350 ms/op
     p(99.9000) =      7.152 ms/op
     p(99.9900) =     18.235 ms/op
     p(99.9990) =     22.536 ms/op
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
# Warmup Iteration   1: 3.604 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 2.881 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.880 ±(99.9%) 0.006 ms/op
Iteration   1: 2.896 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.640 ms/op
                 existUser·p0.50:   2.867 ms/op
                 existUser·p0.90:   3.424 ms/op
                 existUser·p0.95:   3.662 ms/op
                 existUser·p0.99:   4.399 ms/op
                 existUser·p0.999:  6.719 ms/op
                 existUser·p0.9999: 13.106 ms/op
                 existUser·p1.00:   13.648 ms/op

Iteration   2: 2.885 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.570 ms/op
                 existUser·p0.50:   2.875 ms/op
                 existUser·p0.90:   3.437 ms/op
                 existUser·p0.95:   3.625 ms/op
                 existUser·p0.99:   4.202 ms/op
                 existUser·p0.999:  6.341 ms/op
                 existUser·p0.9999: 12.598 ms/op
                 existUser·p1.00:   13.255 ms/op

Iteration   3: 2.907 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.595 ms/op
                 existUser·p0.50:   2.884 ms/op
                 existUser·p0.90:   3.416 ms/op
                 existUser·p0.95:   3.531 ms/op
                 existUser·p0.99:   4.276 ms/op
                 existUser·p0.999:  7.781 ms/op
                 existUser·p0.9999: 22.446 ms/op
                 existUser·p1.00:   22.675 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 331467
  mean =      2.896 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 49266 
    [ 2.500,  5.000) = 281259 
    [ 5.000,  7.500) = 724 
    [ 7.500, 10.000) = 26 
    [10.000, 12.500) = 74 
    [12.500, 15.000) = 69 
    [15.000, 17.500) = 17 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.570 ms/op
     p(50.0000) =      2.875 ms/op
     p(90.0000) =      3.424 ms/op
     p(95.0000) =      3.609 ms/op
     p(99.0000) =      4.301 ms/op
     p(99.9000) =      6.693 ms/op
     p(99.9900) =     15.993 ms/op
     p(99.9990) =     22.610 ms/op
     p(99.9999) =     22.675 ms/op
    p(100.0000) =     22.675 ms/op


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
# Warmup Iteration   1: 4.025 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.015 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.951 ±(99.9%) 0.006 ms/op
Iteration   1: 2.940 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.745 ms/op
                 getUser·p0.50:   2.945 ms/op
                 getUser·p0.90:   3.510 ms/op
                 getUser·p0.95:   3.723 ms/op
                 getUser·p0.99:   4.301 ms/op
                 getUser·p0.999:  7.786 ms/op
                 getUser·p0.9999: 12.212 ms/op
                 getUser·p1.00:   12.583 ms/op

Iteration   2: 2.913 ±(99.9%) 0.004 ms/op
                 getUser·p0.00:   0.617 ms/op
                 getUser·p0.50:   2.929 ms/op
                 getUser·p0.90:   3.265 ms/op
                 getUser·p0.95:   3.346 ms/op
                 getUser·p0.99:   3.941 ms/op
                 getUser·p0.999:  6.082 ms/op
                 getUser·p0.9999: 12.632 ms/op
                 getUser·p1.00:   12.763 ms/op

Iteration   3: 2.930 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.544 ms/op
                 getUser·p0.50:   2.949 ms/op
                 getUser·p0.90:   3.273 ms/op
                 getUser·p0.95:   3.391 ms/op
                 getUser·p0.99:   4.043 ms/op
                 getUser·p0.999:  7.101 ms/op
                 getUser·p0.9999: 15.746 ms/op
                 getUser·p1.00:   16.073 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 327694
  mean =      2.928 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2510 
    [ 1.250,  2.500) = 23305 
    [ 2.500,  3.750) = 293132 
    [ 3.750,  5.000) = 7854 
    [ 5.000,  6.250) = 434 
    [ 6.250,  7.500) = 176 
    [ 7.500,  8.750) = 78 
    [ 8.750, 10.000) = 13 
    [10.000, 11.250) = 7 
    [11.250, 12.500) = 98 
    [12.500, 13.750) = 39 
    [13.750, 15.000) = 17 
    [15.000, 16.250) = 31 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.544 ms/op
     p(50.0000) =      2.941 ms/op
     p(90.0000) =      3.326 ms/op
     p(95.0000) =      3.523 ms/op
     p(99.0000) =      4.137 ms/op
     p(99.9000) =      7.211 ms/op
     p(99.9900) =     14.975 ms/op
     p(99.9990) =     15.965 ms/op
     p(99.9999) =     16.073 ms/op
    p(100.0000) =     16.073 ms/op


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
# Warmup Iteration   1: 5.090 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 4.016 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.868 ±(99.9%) 0.010 ms/op
Iteration   1: 3.824 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.350 ms/op
                 listUser·p0.50:   3.715 ms/op
                 listUser·p0.90:   4.260 ms/op
                 listUser·p0.95:   5.317 ms/op
                 listUser·p0.99:   6.528 ms/op
                 listUser·p0.999:  12.042 ms/op
                 listUser·p0.9999: 14.728 ms/op
                 listUser·p1.00:   15.335 ms/op

Iteration   2: 3.817 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.507 ms/op
                 listUser·p0.50:   3.682 ms/op
                 listUser·p0.90:   4.694 ms/op
                 listUser·p0.95:   5.489 ms/op
                 listUser·p0.99:   6.521 ms/op
                 listUser·p0.999:  12.701 ms/op
                 listUser·p0.9999: 19.865 ms/op
                 listUser·p1.00:   21.332 ms/op

Iteration   3: 3.848 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.783 ms/op
                 listUser·p0.50:   3.703 ms/op
                 listUser·p0.90:   4.932 ms/op
                 listUser·p0.95:   5.439 ms/op
                 listUser·p0.99:   6.611 ms/op
                 listUser·p0.999:  13.599 ms/op
                 listUser·p0.9999: 20.306 ms/op
                 listUser·p1.00:   20.873 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 250633
  mean =      3.830 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4669 
    [ 2.500,  5.000) = 227535 
    [ 5.000,  7.500) = 17447 
    [ 7.500, 10.000) = 542 
    [10.000, 12.500) = 164 
    [12.500, 15.000) = 200 
    [15.000, 17.500) = 12 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.783 ms/op
     p(50.0000) =      3.699 ms/op
     p(90.0000) =      4.694 ms/op
     p(95.0000) =      5.431 ms/op
     p(99.0000) =      6.554 ms/op
     p(99.9000) =     12.665 ms/op
     p(99.9900) =     19.988 ms/op
     p(99.9990) =     20.823 ms/op
     p(99.9999) =     21.332 ms/op
    p(100.0000) =     21.332 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.739 ± 0.950  ops/ms
ClientGrpc.existUser                       thrpt       3  11.371 ± 1.449  ops/ms
ClientGrpc.getUser                         thrpt       3  10.888 ± 1.524  ops/ms
ClientGrpc.listUser                        thrpt       3   8.449 ± 2.136  ops/ms
ClientGrpc.createUser                       avgt       3   2.967 ± 0.271   ms/op
ClientGrpc.existUser                        avgt       3   2.828 ± 0.647   ms/op
ClientGrpc.getUser                          avgt       3   2.942 ± 0.193   ms/op
ClientGrpc.listUser                         avgt       3   3.764 ± 0.519   ms/op
ClientGrpc.createUser                     sample  325949   2.946 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.561           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.941           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.437           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.662           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.350           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.152           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.235           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.577           ms/op
ClientGrpc.existUser                      sample  331467   2.896 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.570           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.875           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.424           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.609           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.301           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.693           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.993           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.675           ms/op
ClientGrpc.getUser                        sample  327694   2.928 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.544           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.941           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.326           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.523           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.137           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.211           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          14.975           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          16.073           ms/op
ClientGrpc.listUser                       sample  250633   3.830 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.783           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.699           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.694           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.431           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.554           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          12.665           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          19.988           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          21.332           ms/op
