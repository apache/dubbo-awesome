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
# Warmup Iteration   1: 4.448 ops/ms
# Warmup Iteration   2: 9.368 ops/ms
# Warmup Iteration   3: 10.409 ops/ms
Iteration   1: 10.463 ops/ms
Iteration   2: 10.766 ops/ms
Iteration   3: 10.713 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.648 ±(99.9%) 2.952 ops/ms [Average]
  (min, avg, max) = (10.463, 10.648, 10.766), stdev = 0.162
  CI (99.9%): [7.695, 13.600] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.434 ops/ms
# Warmup Iteration   2: 10.927 ops/ms
# Warmup Iteration   3: 11.370 ops/ms
Iteration   1: 11.089 ops/ms
Iteration   2: 11.302 ops/ms
Iteration   3: 11.363 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.251 ±(99.9%) 2.628 ops/ms [Average]
  (min, avg, max) = (11.089, 11.251, 11.363), stdev = 0.144
  CI (99.9%): [8.623, 13.879] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 6.779 ops/ms
# Warmup Iteration   2: 10.274 ops/ms
# Warmup Iteration   3: 10.595 ops/ms
Iteration   1: 10.773 ops/ms
Iteration   2: 10.776 ops/ms
Iteration   3: 10.700 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.750 ±(99.9%) 0.793 ops/ms [Average]
  (min, avg, max) = (10.700, 10.750, 10.776), stdev = 0.043
  CI (99.9%): [9.957, 11.543] (assumes normal distribution)


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
# Warmup Iteration   1: 5.409 ops/ms
# Warmup Iteration   2: 8.019 ops/ms
# Warmup Iteration   3: 8.110 ops/ms
Iteration   1: 8.195 ops/ms
Iteration   2: 8.240 ops/ms
Iteration   3: 8.226 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.220 ±(99.9%) 0.424 ops/ms [Average]
  (min, avg, max) = (8.195, 8.220, 8.240), stdev = 0.023
  CI (99.9%): [7.797, 8.644] (assumes normal distribution)


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
# Warmup Iteration   1: 4.026 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.126 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.994 ±(99.9%) 0.003 ms/op
Iteration   1: 2.968 ±(99.9%) 0.005 ms/op
Iteration   2: 2.990 ±(99.9%) 0.003 ms/op
Iteration   3: 2.947 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.968 ±(99.9%) 0.395 ms/op [Average]
  (min, avg, max) = (2.947, 2.968, 2.990), stdev = 0.022
  CI (99.9%): [2.573, 3.364] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.872 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 2.928 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.858 ±(99.9%) 0.003 ms/op
Iteration   1: 2.895 ±(99.9%) 0.003 ms/op
Iteration   2: 2.879 ±(99.9%) 0.001 ms/op
Iteration   3: 2.900 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.891 ±(99.9%) 0.197 ms/op [Average]
  (min, avg, max) = (2.879, 2.891, 2.900), stdev = 0.011
  CI (99.9%): [2.694, 3.089] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.960 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.104 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.987 ±(99.9%) 0.004 ms/op
Iteration   1: 2.964 ±(99.9%) 0.004 ms/op
Iteration   2: 2.973 ±(99.9%) 0.004 ms/op
Iteration   3: 3.001 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.979 ±(99.9%) 0.352 ms/op [Average]
  (min, avg, max) = (2.964, 2.979, 3.001), stdev = 0.019
  CI (99.9%): [2.627, 3.332] (assumes normal distribution)


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
# Warmup Iteration   1: 5.418 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.058 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.983 ±(99.9%) 0.015 ms/op
Iteration   1: 3.951 ±(99.9%) 0.012 ms/op
Iteration   2: 3.941 ±(99.9%) 0.018 ms/op
Iteration   3: 3.907 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.933 ±(99.9%) 0.416 ms/op [Average]
  (min, avg, max) = (3.907, 3.933, 3.951), stdev = 0.023
  CI (99.9%): [3.517, 4.349] (assumes normal distribution)


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
# Warmup Iteration   1: 4.238 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.233 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.963 ±(99.9%) 0.006 ms/op
Iteration   1: 2.930 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.887 ms/op
                 createUser·p0.50:   2.925 ms/op
                 createUser·p0.90:   3.351 ms/op
                 createUser·p0.95:   3.568 ms/op
                 createUser·p0.99:   4.246 ms/op
                 createUser·p0.999:  8.323 ms/op
                 createUser·p0.9999: 12.882 ms/op
                 createUser·p1.00:   13.124 ms/op

Iteration   2: 2.998 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.581 ms/op
                 createUser·p0.50:   2.957 ms/op
                 createUser·p0.90:   3.461 ms/op
                 createUser·p0.95:   3.645 ms/op
                 createUser·p0.99:   4.182 ms/op
                 createUser·p0.999:  7.288 ms/op
                 createUser·p0.9999: 15.013 ms/op
                 createUser·p1.00:   15.319 ms/op

Iteration   3: 2.953 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.634 ms/op
                 createUser·p0.50:   2.937 ms/op
                 createUser·p0.90:   3.449 ms/op
                 createUser·p0.95:   3.690 ms/op
                 createUser·p0.99:   4.268 ms/op
                 createUser·p0.999:  8.649 ms/op
                 createUser·p0.9999: 25.335 ms/op
                 createUser·p1.00:   25.723 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 324137
  mean =      2.960 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 30375 
    [ 2.500,  5.000) = 292443 
    [ 5.000,  7.500) = 882 
    [ 7.500, 10.000) = 237 
    [10.000, 12.500) = 60 
    [12.500, 15.000) = 65 
    [15.000, 17.500) = 40 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 23 

  Percentiles, ms/op:
      p(0.0000) =      0.581 ms/op
     p(50.0000) =      2.941 ms/op
     p(90.0000) =      3.416 ms/op
     p(95.0000) =      3.641 ms/op
     p(99.0000) =      4.235 ms/op
     p(99.9000) =      8.084 ms/op
     p(99.9900) =     22.051 ms/op
     p(99.9990) =     25.617 ms/op
     p(99.9999) =     25.723 ms/op
    p(100.0000) =     25.723 ms/op


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
# Warmup Iteration   1: 3.961 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 2.925 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.910 ±(99.9%) 0.005 ms/op
Iteration   1: 2.903 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.805 ms/op
                 existUser·p0.50:   2.888 ms/op
                 existUser·p0.90:   3.342 ms/op
                 existUser·p0.95:   3.498 ms/op
                 existUser·p0.99:   4.174 ms/op
                 existUser·p0.999:  6.625 ms/op
                 existUser·p0.9999: 12.025 ms/op
                 existUser·p1.00:   12.239 ms/op

Iteration   2: 2.837 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.574 ms/op
                 existUser·p0.50:   2.843 ms/op
                 existUser·p0.90:   3.285 ms/op
                 existUser·p0.95:   3.494 ms/op
                 existUser·p0.99:   4.342 ms/op
                 existUser·p0.999:  7.274 ms/op
                 existUser·p0.9999: 15.396 ms/op
                 existUser·p1.00:   16.433 ms/op

Iteration   3: 2.946 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.711 ms/op
                 existUser·p0.50:   2.925 ms/op
                 existUser·p0.90:   3.428 ms/op
                 existUser·p0.95:   3.613 ms/op
                 existUser·p0.99:   4.170 ms/op
                 existUser·p0.999:  8.789 ms/op
                 existUser·p0.9999: 14.959 ms/op
                 existUser·p1.00:   16.663 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 331889
  mean =      2.895 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1415 
    [ 1.250,  2.500) = 41431 
    [ 2.500,  3.750) = 280640 
    [ 3.750,  5.000) = 7360 
    [ 5.000,  6.250) = 535 
    [ 6.250,  7.500) = 192 
    [ 7.500,  8.750) = 46 
    [ 8.750, 10.000) = 46 
    [10.000, 11.250) = 6 
    [11.250, 12.500) = 122 
    [12.500, 13.750) = 5 
    [13.750, 15.000) = 55 
    [15.000, 16.250) = 28 
    [16.250, 17.500) = 8 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.574 ms/op
     p(50.0000) =      2.884 ms/op
     p(90.0000) =      3.355 ms/op
     p(95.0000) =      3.543 ms/op
     p(99.0000) =      4.219 ms/op
     p(99.9000) =      7.307 ms/op
     p(99.9900) =     15.137 ms/op
     p(99.9990) =     16.538 ms/op
     p(99.9999) =     16.663 ms/op
    p(100.0000) =     16.663 ms/op


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
# Warmup Iteration   1: 4.203 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.142 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.017 ±(99.9%) 0.007 ms/op
Iteration   1: 2.990 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.667 ms/op
                 getUser·p0.50:   2.957 ms/op
                 getUser·p0.90:   3.568 ms/op
                 getUser·p0.95:   3.838 ms/op
                 getUser·p0.99:   4.678 ms/op
                 getUser·p0.999:  8.208 ms/op
                 getUser·p0.9999: 16.329 ms/op
                 getUser·p1.00:   18.383 ms/op

Iteration   2: 2.993 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.740 ms/op
                 getUser·p0.50:   2.953 ms/op
                 getUser·p0.90:   3.424 ms/op
                 getUser·p0.95:   3.690 ms/op
                 getUser·p0.99:   4.530 ms/op
                 getUser·p0.999:  6.588 ms/op
                 getUser·p0.9999: 17.738 ms/op
                 getUser·p1.00:   18.055 ms/op

Iteration   3: 3.014 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.671 ms/op
                 getUser·p0.50:   2.978 ms/op
                 getUser·p0.90:   3.473 ms/op
                 getUser·p0.95:   3.731 ms/op
                 getUser·p0.99:   4.334 ms/op
                 getUser·p0.999:  7.102 ms/op
                 getUser·p0.9999: 20.861 ms/op
                 getUser·p1.00:   21.660 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 319899
  mean =      2.999 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24460 
    [ 2.500,  5.000) = 294028 
    [ 5.000,  7.500) = 1133 
    [ 7.500, 10.000) = 73 
    [10.000, 12.500) = 13 
    [12.500, 15.000) = 5 
    [15.000, 17.500) = 98 
    [17.500, 20.000) = 56 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.667 ms/op
     p(50.0000) =      2.961 ms/op
     p(90.0000) =      3.490 ms/op
     p(95.0000) =      3.756 ms/op
     p(99.0000) =      4.538 ms/op
     p(99.9000) =      7.136 ms/op
     p(99.9900) =     20.022 ms/op
     p(99.9990) =     21.424 ms/op
     p(99.9999) =     21.660 ms/op
    p(100.0000) =     21.660 ms/op


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
# Warmup Iteration   1: 5.825 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.000 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.938 ±(99.9%) 0.010 ms/op
Iteration   1: 3.969 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.614 ms/op
                 listUser·p0.50:   3.817 ms/op
                 listUser·p0.90:   4.858 ms/op
                 listUser·p0.95:   5.562 ms/op
                 listUser·p0.99:   6.892 ms/op
                 listUser·p0.999:  13.320 ms/op
                 listUser·p0.9999: 14.663 ms/op
                 listUser·p1.00:   14.926 ms/op

Iteration   2: 3.908 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.270 ms/op
                 listUser·p0.50:   3.744 ms/op
                 listUser·p0.90:   4.899 ms/op
                 listUser·p0.95:   5.751 ms/op
                 listUser·p0.99:   6.898 ms/op
                 listUser·p0.999:  13.664 ms/op
                 listUser·p0.9999: 17.295 ms/op
                 listUser·p1.00:   17.629 ms/op

Iteration   3: 3.897 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.315 ms/op
                 listUser·p0.50:   3.744 ms/op
                 listUser·p0.90:   4.628 ms/op
                 listUser·p0.95:   5.620 ms/op
                 listUser·p0.99:   6.832 ms/op
                 listUser·p0.999:  14.795 ms/op
                 listUser·p0.9999: 18.252 ms/op
                 listUser·p1.00:   19.202 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 244596
  mean =      3.924 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 2907 
    [ 2.500,  3.750) = 115309 
    [ 3.750,  5.000) = 105840 
    [ 5.000,  6.250) = 14847 
    [ 6.250,  7.500) = 4363 
    [ 7.500,  8.750) = 575 
    [ 8.750, 10.000) = 165 
    [10.000, 11.250) = 121 
    [11.250, 12.500) = 77 
    [12.500, 13.750) = 158 
    [13.750, 15.000) = 110 
    [15.000, 16.250) = 59 
    [16.250, 17.500) = 54 
    [17.500, 18.750) = 6 

  Percentiles, ms/op:
      p(0.0000) =      1.270 ms/op
     p(50.0000) =      3.768 ms/op
     p(90.0000) =      4.817 ms/op
     p(95.0000) =      5.661 ms/op
     p(99.0000) =      6.865 ms/op
     p(99.9000) =     13.664 ms/op
     p(99.9900) =     17.138 ms/op
     p(99.9990) =     19.075 ms/op
     p(99.9999) =     19.202 ms/op
    p(100.0000) =     19.202 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.648 ± 2.952  ops/ms
ClientGrpc.existUser                       thrpt       3  11.251 ± 2.628  ops/ms
ClientGrpc.getUser                         thrpt       3  10.750 ± 0.793  ops/ms
ClientGrpc.listUser                        thrpt       3   8.220 ± 0.424  ops/ms
ClientGrpc.createUser                       avgt       3   2.968 ± 0.395   ms/op
ClientGrpc.existUser                        avgt       3   2.891 ± 0.197   ms/op
ClientGrpc.getUser                          avgt       3   2.979 ± 0.352   ms/op
ClientGrpc.listUser                         avgt       3   3.933 ± 0.416   ms/op
ClientGrpc.createUser                     sample  324137   2.960 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.581           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.941           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.416           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.641           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.235           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.084           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          22.051           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          25.723           ms/op
ClientGrpc.existUser                      sample  331889   2.895 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.574           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.884           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.355           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.543           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.219           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.307           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.137           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          16.663           ms/op
ClientGrpc.getUser                        sample  319899   2.999 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.667           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.961           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.490           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.756           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.538           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.136           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.022           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.660           ms/op
ClientGrpc.listUser                       sample  244596   3.924 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.270           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.768           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.817           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.661           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.865           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.664           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          17.138           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          19.202           ms/op
