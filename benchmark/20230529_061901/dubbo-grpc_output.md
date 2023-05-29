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
# Warmup Iteration   1: 4.191 ops/ms
# Warmup Iteration   2: 8.970 ops/ms
# Warmup Iteration   3: 9.611 ops/ms
Iteration   1: 10.171 ops/ms
Iteration   2: 10.483 ops/ms
Iteration   3: 10.430 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.361 ±(99.9%) 3.048 ops/ms [Average]
  (min, avg, max) = (10.171, 10.361, 10.483), stdev = 0.167
  CI (99.9%): [7.314, 13.409] (assumes normal distribution)


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
# Warmup Iteration   1: 8.288 ops/ms
# Warmup Iteration   2: 10.634 ops/ms
# Warmup Iteration   3: 11.099 ops/ms
Iteration   1: 11.255 ops/ms
Iteration   2: 11.113 ops/ms
Iteration   3: 11.184 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.184 ±(99.9%) 1.294 ops/ms [Average]
  (min, avg, max) = (11.113, 11.184, 11.255), stdev = 0.071
  CI (99.9%): [9.890, 12.478] (assumes normal distribution)


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
# Warmup Iteration   1: 6.453 ops/ms
# Warmup Iteration   2: 10.003 ops/ms
# Warmup Iteration   3: 10.370 ops/ms
Iteration   1: 10.635 ops/ms
Iteration   2: 10.644 ops/ms
Iteration   3: 10.829 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.703 ±(99.9%) 1.995 ops/ms [Average]
  (min, avg, max) = (10.635, 10.703, 10.829), stdev = 0.109
  CI (99.9%): [8.707, 12.698] (assumes normal distribution)


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
# Warmup Iteration   1: 5.924 ops/ms
# Warmup Iteration   2: 7.854 ops/ms
# Warmup Iteration   3: 8.120 ops/ms
Iteration   1: 8.074 ops/ms
Iteration   2: 8.054 ops/ms
Iteration   3: 8.057 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.062 ±(99.9%) 0.196 ops/ms [Average]
  (min, avg, max) = (8.054, 8.062, 8.074), stdev = 0.011
  CI (99.9%): [7.866, 8.258] (assumes normal distribution)


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
# Warmup Iteration   1: 4.590 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.179 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.963 ±(99.9%) 0.003 ms/op
Iteration   1: 2.960 ±(99.9%) 0.001 ms/op
Iteration   2: 2.997 ±(99.9%) 0.002 ms/op
Iteration   3: 2.973 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.977 ±(99.9%) 0.337 ms/op [Average]
  (min, avg, max) = (2.960, 2.977, 2.997), stdev = 0.018
  CI (99.9%): [2.640, 3.314] (assumes normal distribution)


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
# Warmup Iteration   1: 4.080 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.990 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.822 ±(99.9%) 0.002 ms/op
Iteration   1: 2.824 ±(99.9%) 0.002 ms/op
Iteration   2: 2.911 ±(99.9%) 0.002 ms/op
Iteration   3: 2.883 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.872 ±(99.9%) 0.811 ms/op [Average]
  (min, avg, max) = (2.824, 2.872, 2.911), stdev = 0.044
  CI (99.9%): [2.062, 3.683] (assumes normal distribution)


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
# Warmup Iteration   1: 4.413 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.144 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.994 ±(99.9%) 0.004 ms/op
Iteration   1: 3.008 ±(99.9%) 0.003 ms/op
Iteration   2: 2.954 ±(99.9%) 0.004 ms/op
Iteration   3: 3.031 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.997 ±(99.9%) 0.725 ms/op [Average]
  (min, avg, max) = (2.954, 2.997, 3.031), stdev = 0.040
  CI (99.9%): [2.273, 3.722] (assumes normal distribution)


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
# Warmup Iteration   1: 5.633 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.138 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.934 ±(99.9%) 0.014 ms/op
Iteration   1: 3.982 ±(99.9%) 0.010 ms/op
Iteration   2: 3.958 ±(99.9%) 0.010 ms/op
Iteration   3: 3.910 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.950 ±(99.9%) 0.672 ms/op [Average]
  (min, avg, max) = (3.910, 3.950, 3.982), stdev = 0.037
  CI (99.9%): [3.278, 4.622] (assumes normal distribution)


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
# Warmup Iteration   1: 4.198 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.180 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.997 ±(99.9%) 0.005 ms/op
Iteration   1: 2.981 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.650 ms/op
                 createUser·p0.50:   2.949 ms/op
                 createUser·p0.90:   3.441 ms/op
                 createUser·p0.95:   3.727 ms/op
                 createUser·p0.99:   4.448 ms/op
                 createUser·p0.999:  7.537 ms/op
                 createUser·p0.9999: 12.584 ms/op
                 createUser·p1.00:   13.107 ms/op

Iteration   2: 3.037 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.922 ms/op
                 createUser·p0.50:   3.006 ms/op
                 createUser·p0.90:   3.523 ms/op
                 createUser·p0.95:   3.678 ms/op
                 createUser·p0.99:   4.260 ms/op
                 createUser·p0.999:  7.873 ms/op
                 createUser·p0.9999: 19.988 ms/op
                 createUser·p1.00:   20.447 ms/op

Iteration   3: 3.005 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.713 ms/op
                 createUser·p0.50:   2.970 ms/op
                 createUser·p0.90:   3.469 ms/op
                 createUser·p0.95:   3.699 ms/op
                 createUser·p0.99:   4.284 ms/op
                 createUser·p0.999:  9.388 ms/op
                 createUser·p0.9999: 21.660 ms/op
                 createUser·p1.00:   21.922 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 319239
  mean =      3.007 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25747 
    [ 2.500,  5.000) = 292037 
    [ 5.000,  7.500) = 1098 
    [ 7.500, 10.000) = 101 
    [10.000, 12.500) = 52 
    [12.500, 15.000) = 93 
    [15.000, 17.500) = 46 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 41 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.650 ms/op
     p(50.0000) =      2.974 ms/op
     p(90.0000) =      3.486 ms/op
     p(95.0000) =      3.699 ms/op
     p(99.0000) =      4.334 ms/op
     p(99.9000) =      9.176 ms/op
     p(99.9900) =     20.482 ms/op
     p(99.9990) =     21.850 ms/op
     p(99.9999) =     21.922 ms/op
    p(100.0000) =     21.922 ms/op


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
# Warmup Iteration   1: 3.889 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 2.984 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.912 ±(99.9%) 0.006 ms/op
Iteration   1: 2.904 ±(99.9%) 0.004 ms/op
                 existUser·p0.00:   0.758 ms/op
                 existUser·p0.50:   2.892 ms/op
                 existUser·p0.90:   3.334 ms/op
                 existUser·p0.95:   3.539 ms/op
                 existUser·p0.99:   3.953 ms/op
                 existUser·p0.999:  5.560 ms/op
                 existUser·p0.9999: 12.664 ms/op
                 existUser·p1.00:   13.091 ms/op

Iteration   2: 2.887 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.826 ms/op
                 existUser·p0.50:   2.875 ms/op
                 existUser·p0.90:   3.359 ms/op
                 existUser·p0.95:   3.502 ms/op
                 existUser·p0.99:   4.149 ms/op
                 existUser·p0.999:  8.507 ms/op
                 existUser·p0.9999: 15.401 ms/op
                 existUser·p1.00:   15.761 ms/op

Iteration   3: 2.872 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.805 ms/op
                 existUser·p0.50:   2.851 ms/op
                 existUser·p0.90:   3.277 ms/op
                 existUser·p0.95:   3.453 ms/op
                 existUser·p0.99:   3.932 ms/op
                 existUser·p0.999:  6.812 ms/op
                 existUser·p0.9999: 16.800 ms/op
                 existUser·p1.00:   18.285 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 332338
  mean =      2.888 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1218 
    [ 1.250,  2.500) = 41566 
    [ 2.500,  3.750) = 283070 
    [ 3.750,  5.000) = 5555 
    [ 5.000,  6.250) = 443 
    [ 6.250,  7.500) = 205 
    [ 7.500,  8.750) = 57 
    [ 8.750, 10.000) = 32 
    [10.000, 11.250) = 12 
    [11.250, 12.500) = 51 
    [12.500, 13.750) = 33 
    [13.750, 15.000) = 36 
    [15.000, 16.250) = 39 
    [16.250, 17.500) = 14 
    [17.500, 18.750) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.758 ms/op
     p(50.0000) =      2.871 ms/op
     p(90.0000) =      3.326 ms/op
     p(95.0000) =      3.498 ms/op
     p(99.0000) =      4.006 ms/op
     p(99.9000) =      6.963 ms/op
     p(99.9900) =     15.679 ms/op
     p(99.9990) =     18.132 ms/op
     p(99.9999) =     18.285 ms/op
    p(100.0000) =     18.285 ms/op


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
# Warmup Iteration   1: 4.265 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.143 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.084 ±(99.9%) 0.007 ms/op
Iteration   1: 3.054 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.578 ms/op
                 getUser·p0.50:   3.015 ms/op
                 getUser·p0.90:   3.650 ms/op
                 getUser·p0.95:   3.899 ms/op
                 getUser·p0.99:   4.801 ms/op
                 getUser·p0.999:  7.269 ms/op
                 getUser·p0.9999: 13.617 ms/op
                 getUser·p1.00:   14.238 ms/op

Iteration   2: 3.043 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.809 ms/op
                 getUser·p0.50:   3.011 ms/op
                 getUser·p0.90:   3.514 ms/op
                 getUser·p0.95:   3.707 ms/op
                 getUser·p0.99:   4.342 ms/op
                 getUser·p0.999:  7.780 ms/op
                 getUser·p0.9999: 23.167 ms/op
                 getUser·p1.00:   23.462 ms/op

Iteration   3: 3.022 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.634 ms/op
                 getUser·p0.50:   2.990 ms/op
                 getUser·p0.90:   3.535 ms/op
                 getUser·p0.95:   3.744 ms/op
                 getUser·p0.99:   4.473 ms/op
                 getUser·p0.999:  6.834 ms/op
                 getUser·p0.9999: 26.523 ms/op
                 getUser·p1.00:   27.329 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 315563
  mean =      3.040 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20899 
    [ 2.500,  5.000) = 293046 
    [ 5.000,  7.500) = 1344 
    [ 7.500, 10.000) = 94 
    [10.000, 12.500) = 20 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 37 
    [25.000, 27.500) = 27 

  Percentiles, ms/op:
      p(0.0000) =      0.578 ms/op
     p(50.0000) =      3.002 ms/op
     p(90.0000) =      3.555 ms/op
     p(95.0000) =      3.793 ms/op
     p(99.0000) =      4.588 ms/op
     p(99.9000) =      7.221 ms/op
     p(99.9900) =     24.853 ms/op
     p(99.9990) =     27.215 ms/op
     p(99.9999) =     27.329 ms/op
    p(100.0000) =     27.329 ms/op


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
# Warmup Iteration   1: 5.152 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 4.166 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.998 ±(99.9%) 0.011 ms/op
Iteration   1: 4.009 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.264 ms/op
                 listUser·p0.50:   3.858 ms/op
                 listUser·p0.90:   4.964 ms/op
                 listUser·p0.95:   5.743 ms/op
                 listUser·p0.99:   6.938 ms/op
                 listUser·p0.999:  14.893 ms/op
                 listUser·p0.9999: 20.055 ms/op
                 listUser·p1.00:   20.611 ms/op

Iteration   2: 4.018 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.943 ms/op
                 listUser·p0.50:   3.867 ms/op
                 listUser·p0.90:   4.964 ms/op
                 listUser·p0.95:   5.702 ms/op
                 listUser·p0.99:   6.988 ms/op
                 listUser·p0.999:  13.534 ms/op
                 listUser·p0.9999: 15.946 ms/op
                 listUser·p1.00:   17.170 ms/op

Iteration   3: 3.966 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.055 ms/op
                 listUser·p0.50:   3.822 ms/op
                 listUser·p0.90:   4.882 ms/op
                 listUser·p0.95:   5.702 ms/op
                 listUser·p0.99:   6.786 ms/op
                 listUser·p0.999:  17.509 ms/op
                 listUser·p0.9999: 19.102 ms/op
                 listUser·p1.00:   21.004 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 240299
  mean =      3.998 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3271 
    [ 2.500,  5.000) = 214507 
    [ 5.000,  7.500) = 21276 
    [ 7.500, 10.000) = 826 
    [10.000, 12.500) = 76 
    [12.500, 15.000) = 108 
    [15.000, 17.500) = 116 
    [17.500, 20.000) = 109 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.943 ms/op
     p(50.0000) =      3.850 ms/op
     p(90.0000) =      4.940 ms/op
     p(95.0000) =      5.710 ms/op
     p(99.0000) =      6.889 ms/op
     p(99.9000) =     14.927 ms/op
     p(99.9900) =     19.038 ms/op
     p(99.9990) =     20.585 ms/op
     p(99.9999) =     21.004 ms/op
    p(100.0000) =     21.004 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.361 ± 3.048  ops/ms
ClientGrpc.existUser                       thrpt       3  11.184 ± 1.294  ops/ms
ClientGrpc.getUser                         thrpt       3  10.703 ± 1.995  ops/ms
ClientGrpc.listUser                        thrpt       3   8.062 ± 0.196  ops/ms
ClientGrpc.createUser                       avgt       3   2.977 ± 0.337   ms/op
ClientGrpc.existUser                        avgt       3   2.872 ± 0.811   ms/op
ClientGrpc.getUser                          avgt       3   2.997 ± 0.725   ms/op
ClientGrpc.listUser                         avgt       3   3.950 ± 0.672   ms/op
ClientGrpc.createUser                     sample  319239   3.007 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.650           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.974           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.486           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.699           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.334           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.176           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.482           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.922           ms/op
ClientGrpc.existUser                      sample  332338   2.888 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.758           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.871           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.326           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.498           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.006           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.963           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.679           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.285           ms/op
ClientGrpc.getUser                        sample  315563   3.040 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.578           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.002           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.555           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.793           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.588           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.221           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          24.853           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          27.329           ms/op
ClientGrpc.listUser                       sample  240299   3.998 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.943           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.850           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.940           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.710           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.889           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.927           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          19.038           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          21.004           ms/op
