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
# Warmup Iteration   1: 4.135 ops/ms
# Warmup Iteration   2: 9.141 ops/ms
# Warmup Iteration   3: 9.925 ops/ms
Iteration   1: 10.385 ops/ms
Iteration   2: 10.561 ops/ms
Iteration   3: 10.488 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.478 ±(99.9%) 1.616 ops/ms [Average]
  (min, avg, max) = (10.385, 10.478, 10.561), stdev = 0.089
  CI (99.9%): [8.862, 12.094] (assumes normal distribution)


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
# Warmup Iteration   1: 8.158 ops/ms
# Warmup Iteration   2: 10.520 ops/ms
# Warmup Iteration   3: 10.645 ops/ms
Iteration   1: 11.269 ops/ms
Iteration   2: 11.068 ops/ms
Iteration   3: 11.267 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.201 ±(99.9%) 2.110 ops/ms [Average]
  (min, avg, max) = (11.068, 11.201, 11.269), stdev = 0.116
  CI (99.9%): [9.091, 13.312] (assumes normal distribution)


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
# Warmup Iteration   1: 7.475 ops/ms
# Warmup Iteration   2: 10.139 ops/ms
# Warmup Iteration   3: 10.676 ops/ms
Iteration   1: 10.634 ops/ms
Iteration   2: 10.712 ops/ms
Iteration   3: 10.808 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.718 ±(99.9%) 1.592 ops/ms [Average]
  (min, avg, max) = (10.634, 10.718, 10.808), stdev = 0.087
  CI (99.9%): [9.126, 12.310] (assumes normal distribution)


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
# Warmup Iteration   1: 6.155 ops/ms
# Warmup Iteration   2: 7.897 ops/ms
# Warmup Iteration   3: 8.344 ops/ms
Iteration   1: 8.221 ops/ms
Iteration   2: 8.143 ops/ms
Iteration   3: 8.145 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.170 ±(99.9%) 0.813 ops/ms [Average]
  (min, avg, max) = (8.143, 8.170, 8.221), stdev = 0.045
  CI (99.9%): [7.357, 8.983] (assumes normal distribution)


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
# Warmup Iteration   1: 4.362 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.166 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.044 ±(99.9%) 0.008 ms/op
Iteration   1: 3.067 ±(99.9%) 0.003 ms/op
Iteration   2: 3.011 ±(99.9%) 0.003 ms/op
Iteration   3: 3.062 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.047 ±(99.9%) 0.563 ms/op [Average]
  (min, avg, max) = (3.011, 3.047, 3.067), stdev = 0.031
  CI (99.9%): [2.484, 3.610] (assumes normal distribution)


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
# Warmup Iteration   1: 3.862 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 3.059 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.943 ±(99.9%) 0.002 ms/op
Iteration   1: 2.901 ±(99.9%) 0.003 ms/op
Iteration   2: 2.793 ±(99.9%) 0.002 ms/op
Iteration   3: 2.929 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.874 ±(99.9%) 1.313 ms/op [Average]
  (min, avg, max) = (2.793, 2.874, 2.929), stdev = 0.072
  CI (99.9%): [1.561, 4.187] (assumes normal distribution)


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
# Warmup Iteration   1: 4.363 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.141 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.085 ±(99.9%) 0.003 ms/op
Iteration   1: 3.045 ±(99.9%) 0.004 ms/op
Iteration   2: 3.061 ±(99.9%) 0.003 ms/op
Iteration   3: 3.043 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.050 ±(99.9%) 0.173 ms/op [Average]
  (min, avg, max) = (3.043, 3.050, 3.061), stdev = 0.009
  CI (99.9%): [2.877, 3.223] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.512 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.031 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.957 ±(99.9%) 0.019 ms/op
Iteration   1: 3.904 ±(99.9%) 0.015 ms/op
Iteration   2: 3.928 ±(99.9%) 0.013 ms/op
Iteration   3: 3.899 ±(99.9%) 0.023 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.910 ±(99.9%) 0.280 ms/op [Average]
  (min, avg, max) = (3.899, 3.910, 3.928), stdev = 0.015
  CI (99.9%): [3.630, 4.190] (assumes normal distribution)


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
# Warmup Iteration   1: 4.420 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.241 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.082 ±(99.9%) 0.006 ms/op
Iteration   1: 2.999 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.772 ms/op
                 createUser·p0.50:   2.982 ms/op
                 createUser·p0.90:   3.387 ms/op
                 createUser·p0.95:   3.588 ms/op
                 createUser·p0.99:   4.211 ms/op
                 createUser·p0.999:  7.526 ms/op
                 createUser·p0.9999: 11.573 ms/op
                 createUser·p1.00:   11.731 ms/op

Iteration   2: 2.998 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.859 ms/op
                 createUser·p0.50:   2.986 ms/op
                 createUser·p0.90:   3.518 ms/op
                 createUser·p0.95:   3.707 ms/op
                 createUser·p0.99:   4.571 ms/op
                 createUser·p0.999:  8.203 ms/op
                 createUser·p0.9999: 13.981 ms/op
                 createUser·p1.00:   15.221 ms/op

Iteration   3: 3.024 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.748 ms/op
                 createUser·p0.50:   2.994 ms/op
                 createUser·p0.90:   3.437 ms/op
                 createUser·p0.95:   3.637 ms/op
                 createUser·p0.99:   4.366 ms/op
                 createUser·p0.999:  9.964 ms/op
                 createUser·p0.9999: 27.754 ms/op
                 createUser·p1.00:   27.787 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 319157
  mean =      3.007 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21442 
    [ 2.500,  5.000) = 296308 
    [ 5.000,  7.500) = 1002 
    [ 7.500, 10.000) = 140 
    [10.000, 12.500) = 76 
    [12.500, 15.000) = 96 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 42 

  Percentiles, ms/op:
      p(0.0000) =      0.748 ms/op
     p(50.0000) =      2.990 ms/op
     p(90.0000) =      3.453 ms/op
     p(95.0000) =      3.645 ms/op
     p(99.0000) =      4.366 ms/op
     p(99.9000) =      8.517 ms/op
     p(99.9900) =     26.285 ms/op
     p(99.9990) =     27.787 ms/op
     p(99.9999) =     27.787 ms/op
    p(100.0000) =     27.787 ms/op


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
# Warmup Iteration   1: 4.053 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.040 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.935 ±(99.9%) 0.005 ms/op
Iteration   1: 2.891 ±(99.9%) 0.004 ms/op
                 existUser·p0.00:   0.943 ms/op
                 existUser·p0.50:   2.892 ms/op
                 existUser·p0.90:   3.187 ms/op
                 existUser·p0.95:   3.289 ms/op
                 existUser·p0.99:   3.932 ms/op
                 existUser·p0.999:  5.302 ms/op
                 existUser·p0.9999: 12.582 ms/op
                 existUser·p1.00:   12.730 ms/op

Iteration   2: 2.949 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.750 ms/op
                 existUser·p0.50:   2.904 ms/op
                 existUser·p0.90:   3.437 ms/op
                 existUser·p0.95:   3.674 ms/op
                 existUser·p0.99:   4.530 ms/op
                 existUser·p0.999:  9.060 ms/op
                 existUser·p0.9999: 15.761 ms/op
                 existUser·p1.00:   16.581 ms/op

Iteration   3: 2.862 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.567 ms/op
                 existUser·p0.50:   2.867 ms/op
                 existUser·p0.90:   3.301 ms/op
                 existUser·p0.95:   3.498 ms/op
                 existUser·p0.99:   4.145 ms/op
                 existUser·p0.999:  6.108 ms/op
                 existUser·p0.9999: 16.349 ms/op
                 existUser·p1.00:   16.728 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 330871
  mean =      2.900 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1011 
    [ 1.250,  2.500) = 33606 
    [ 2.500,  3.750) = 287625 
    [ 3.750,  5.000) = 7490 
    [ 5.000,  6.250) = 599 
    [ 6.250,  7.500) = 188 
    [ 7.500,  8.750) = 78 
    [ 8.750, 10.000) = 111 
    [10.000, 11.250) = 3 
    [11.250, 12.500) = 14 
    [12.500, 13.750) = 18 
    [13.750, 15.000) = 62 
    [15.000, 16.250) = 47 
    [16.250, 17.500) = 19 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.567 ms/op
     p(50.0000) =      2.888 ms/op
     p(90.0000) =      3.301 ms/op
     p(95.0000) =      3.506 ms/op
     p(99.0000) =      4.235 ms/op
     p(99.9000) =      7.553 ms/op
     p(99.9900) =     16.007 ms/op
     p(99.9990) =     16.592 ms/op
     p(99.9999) =     16.728 ms/op
    p(100.0000) =     16.728 ms/op


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
# Warmup Iteration   1: 4.092 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.139 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.066 ±(99.9%) 0.007 ms/op
Iteration   1: 3.059 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.769 ms/op
                 getUser·p0.50:   3.023 ms/op
                 getUser·p0.90:   3.539 ms/op
                 getUser·p0.95:   3.723 ms/op
                 getUser·p0.99:   4.571 ms/op
                 getUser·p0.999:  7.318 ms/op
                 getUser·p0.9999: 13.174 ms/op
                 getUser·p1.00:   13.369 ms/op

Iteration   2: 3.013 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.772 ms/op
                 getUser·p0.50:   2.990 ms/op
                 getUser·p0.90:   3.461 ms/op
                 getUser·p0.95:   3.723 ms/op
                 getUser·p0.99:   4.412 ms/op
                 getUser·p0.999:  7.455 ms/op
                 getUser·p0.9999: 19.608 ms/op
                 getUser·p1.00:   20.480 ms/op

Iteration   3: 3.051 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.649 ms/op
                 getUser·p0.50:   3.023 ms/op
                 getUser·p0.90:   3.539 ms/op
                 getUser·p0.95:   3.699 ms/op
                 getUser·p0.99:   4.268 ms/op
                 getUser·p0.999:  7.677 ms/op
                 getUser·p0.9999: 27.689 ms/op
                 getUser·p1.00:   27.886 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 315636
  mean =      3.041 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16268 
    [ 2.500,  5.000) = 297884 
    [ 5.000,  7.500) = 1159 
    [ 7.500, 10.000) = 132 
    [10.000, 12.500) = 33 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 23 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.649 ms/op
     p(50.0000) =      3.011 ms/op
     p(90.0000) =      3.518 ms/op
     p(95.0000) =      3.711 ms/op
     p(99.0000) =      4.415 ms/op
     p(99.9000) =      7.578 ms/op
     p(99.9900) =     26.777 ms/op
     p(99.9990) =     27.848 ms/op
     p(99.9999) =     27.886 ms/op
    p(100.0000) =     27.886 ms/op


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
# Warmup Iteration   1: 4.645 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 4.129 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.907 ±(99.9%) 0.011 ms/op
Iteration   1: 3.973 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.169 ms/op
                 listUser·p0.50:   3.801 ms/op
                 listUser·p0.90:   5.079 ms/op
                 listUser·p0.95:   5.865 ms/op
                 listUser·p0.99:   6.955 ms/op
                 listUser·p0.999:  13.648 ms/op
                 listUser·p0.9999: 20.441 ms/op
                 listUser·p1.00:   21.758 ms/op

Iteration   2: 3.955 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.409 ms/op
                 listUser·p0.50:   3.809 ms/op
                 listUser·p0.90:   4.653 ms/op
                 listUser·p0.95:   5.640 ms/op
                 listUser·p0.99:   7.037 ms/op
                 listUser·p0.999:  15.958 ms/op
                 listUser·p0.9999: 17.725 ms/op
                 listUser·p1.00:   18.252 ms/op

Iteration   3: 3.849 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.272 ms/op
                 listUser·p0.50:   3.727 ms/op
                 listUser·p0.90:   4.497 ms/op
                 listUser·p0.95:   5.218 ms/op
                 listUser·p0.99:   6.660 ms/op
                 listUser·p0.999:  14.741 ms/op
                 listUser·p0.9999: 17.334 ms/op
                 listUser·p1.00:   18.383 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 244602
  mean =      3.925 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2782 
    [ 2.500,  5.000) = 221553 
    [ 5.000,  7.500) = 19044 
    [ 7.500, 10.000) = 717 
    [10.000, 12.500) = 77 
    [12.500, 15.000) = 198 
    [15.000, 17.500) = 180 
    [17.500, 20.000) = 39 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.169 ms/op
     p(50.0000) =      3.781 ms/op
     p(90.0000) =      4.784 ms/op
     p(95.0000) =      5.620 ms/op
     p(99.0000) =      6.865 ms/op
     p(99.9000) =     14.877 ms/op
     p(99.9900) =     19.169 ms/op
     p(99.9990) =     21.561 ms/op
     p(99.9999) =     21.758 ms/op
    p(100.0000) =     21.758 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.478 ± 1.616  ops/ms
ClientGrpc.existUser                       thrpt       3  11.201 ± 2.110  ops/ms
ClientGrpc.getUser                         thrpt       3  10.718 ± 1.592  ops/ms
ClientGrpc.listUser                        thrpt       3   8.170 ± 0.813  ops/ms
ClientGrpc.createUser                       avgt       3   3.047 ± 0.563   ms/op
ClientGrpc.existUser                        avgt       3   2.874 ± 1.313   ms/op
ClientGrpc.getUser                          avgt       3   3.050 ± 0.173   ms/op
ClientGrpc.listUser                         avgt       3   3.910 ± 0.280   ms/op
ClientGrpc.createUser                     sample  319157   3.007 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.748           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.990           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.453           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.645           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.366           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.517           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          26.285           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          27.787           ms/op
ClientGrpc.existUser                      sample  330871   2.900 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.567           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.888           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.301           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.506           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.235           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.553           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.007           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          16.728           ms/op
ClientGrpc.getUser                        sample  315636   3.041 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.649           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.011           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.518           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.711           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.415           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.578           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          26.777           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          27.886           ms/op
ClientGrpc.listUser                       sample  244602   3.925 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.169           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.781           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.784           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.620           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.865           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.877           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          19.169           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          21.758           ms/op
