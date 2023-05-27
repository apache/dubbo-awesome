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
# Warmup Iteration   1: 4.367 ops/ms
# Warmup Iteration   2: 9.448 ops/ms
# Warmup Iteration   3: 10.429 ops/ms
Iteration   1: 10.682 ops/ms
Iteration   2: 10.865 ops/ms
Iteration   3: 10.911 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.819 ±(99.9%) 2.209 ops/ms [Average]
  (min, avg, max) = (10.682, 10.819, 10.911), stdev = 0.121
  CI (99.9%): [8.610, 13.028] (assumes normal distribution)


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
# Warmup Iteration   1: 8.416 ops/ms
# Warmup Iteration   2: 10.549 ops/ms
# Warmup Iteration   3: 11.072 ops/ms
Iteration   1: 11.038 ops/ms
Iteration   2: 11.061 ops/ms
Iteration   3: 11.374 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.158 ±(99.9%) 3.420 ops/ms [Average]
  (min, avg, max) = (11.038, 11.158, 11.374), stdev = 0.187
  CI (99.9%): [7.737, 14.578] (assumes normal distribution)


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
# Warmup Iteration   1: 7.671 ops/ms
# Warmup Iteration   2: 10.536 ops/ms
# Warmup Iteration   3: 10.776 ops/ms
Iteration   1: 10.981 ops/ms
Iteration   2: 10.763 ops/ms
Iteration   3: 10.946 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.897 ±(99.9%) 2.140 ops/ms [Average]
  (min, avg, max) = (10.763, 10.897, 10.981), stdev = 0.117
  CI (99.9%): [8.757, 13.037] (assumes normal distribution)


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
# Warmup Iteration   1: 5.799 ops/ms
# Warmup Iteration   2: 8.127 ops/ms
# Warmup Iteration   3: 8.397 ops/ms
Iteration   1: 8.425 ops/ms
Iteration   2: 8.426 ops/ms
Iteration   3: 8.363 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.405 ±(99.9%) 0.661 ops/ms [Average]
  (min, avg, max) = (8.363, 8.405, 8.426), stdev = 0.036
  CI (99.9%): [7.743, 9.066] (assumes normal distribution)


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
# Warmup Iteration   1: 4.120 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.143 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.018 ±(99.9%) 0.003 ms/op
Iteration   1: 2.991 ±(99.9%) 0.003 ms/op
Iteration   2: 2.968 ±(99.9%) 0.004 ms/op
Iteration   3: 3.006 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.988 ±(99.9%) 0.349 ms/op [Average]
  (min, avg, max) = (2.968, 2.988, 3.006), stdev = 0.019
  CI (99.9%): [2.639, 3.338] (assumes normal distribution)


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
# Warmup Iteration   1: 3.958 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.988 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.901 ±(99.9%) 0.002 ms/op
Iteration   1: 2.999 ±(99.9%) 0.003 ms/op
Iteration   2: 2.884 ±(99.9%) 0.004 ms/op
Iteration   3: 2.911 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.931 ±(99.9%) 1.091 ms/op [Average]
  (min, avg, max) = (2.884, 2.931, 2.999), stdev = 0.060
  CI (99.9%): [1.840, 4.022] (assumes normal distribution)


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
# Warmup Iteration   1: 3.891 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.045 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.988 ±(99.9%) 0.003 ms/op
Iteration   1: 3.000 ±(99.9%) 0.002 ms/op
Iteration   2: 2.968 ±(99.9%) 0.003 ms/op
Iteration   3: 2.950 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.973 ±(99.9%) 0.463 ms/op [Average]
  (min, avg, max) = (2.950, 2.973, 3.000), stdev = 0.025
  CI (99.9%): [2.510, 3.436] (assumes normal distribution)


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
# Warmup Iteration   1: 4.978 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.936 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 3.852 ±(99.9%) 0.023 ms/op
Iteration   1: 3.856 ±(99.9%) 0.023 ms/op
Iteration   2: 3.797 ±(99.9%) 0.007 ms/op
Iteration   3: 3.723 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.792 ±(99.9%) 1.210 ms/op [Average]
  (min, avg, max) = (3.723, 3.792, 3.856), stdev = 0.066
  CI (99.9%): [2.582, 5.002] (assumes normal distribution)


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
# Warmup Iteration   1: 3.947 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.144 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.035 ±(99.9%) 0.006 ms/op
Iteration   1: 3.026 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.880 ms/op
                 createUser·p0.50:   2.998 ms/op
                 createUser·p0.90:   3.502 ms/op
                 createUser·p0.95:   3.690 ms/op
                 createUser·p0.99:   4.579 ms/op
                 createUser·p0.999:  9.100 ms/op
                 createUser·p0.9999: 17.531 ms/op
                 createUser·p1.00:   17.793 ms/op

Iteration   2: 2.989 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.550 ms/op
                 createUser·p0.50:   2.982 ms/op
                 createUser·p0.90:   3.449 ms/op
                 createUser·p0.95:   3.625 ms/op
                 createUser·p0.99:   4.227 ms/op
                 createUser·p0.999:  6.293 ms/op
                 createUser·p0.9999: 13.302 ms/op
                 createUser·p1.00:   13.631 ms/op

Iteration   3: 3.039 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.586 ms/op
                 createUser·p0.50:   2.998 ms/op
                 createUser·p0.90:   3.650 ms/op
                 createUser·p0.95:   3.903 ms/op
                 createUser·p0.99:   4.596 ms/op
                 createUser·p0.999:  7.324 ms/op
                 createUser·p0.9999: 15.736 ms/op
                 createUser·p1.00:   16.318 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 318209
  mean =      3.018 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1327 
    [ 1.250,  2.500) = 20563 
    [ 2.500,  3.750) = 279956 
    [ 3.750,  5.000) = 14859 
    [ 5.000,  6.250) = 930 
    [ 6.250,  7.500) = 210 
    [ 7.500,  8.750) = 86 
    [ 8.750, 10.000) = 21 
    [10.000, 11.250) = 35 
    [11.250, 12.500) = 63 
    [12.500, 13.750) = 84 
    [13.750, 15.000) = 26 
    [15.000, 16.250) = 14 
    [16.250, 17.500) = 23 
    [17.500, 18.750) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.550 ms/op
     p(50.0000) =      2.994 ms/op
     p(90.0000) =      3.518 ms/op
     p(95.0000) =      3.760 ms/op
     p(99.0000) =      4.481 ms/op
     p(99.9000) =      8.036 ms/op
     p(99.9900) =     16.628 ms/op
     p(99.9990) =     17.722 ms/op
     p(99.9999) =     17.793 ms/op
    p(100.0000) =     17.793 ms/op


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
# Warmup Iteration   1: 3.685 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 2.971 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.915 ±(99.9%) 0.006 ms/op
Iteration   1: 2.864 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.519 ms/op
                 existUser·p0.50:   2.863 ms/op
                 existUser·p0.90:   3.330 ms/op
                 existUser·p0.95:   3.543 ms/op
                 existUser·p0.99:   4.432 ms/op
                 existUser·p0.999:  5.893 ms/op
                 existUser·p0.9999: 12.009 ms/op
                 existUser·p1.00:   12.419 ms/op

Iteration   2: 2.919 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.674 ms/op
                 existUser·p0.50:   2.900 ms/op
                 existUser·p0.90:   3.457 ms/op
                 existUser·p0.95:   3.604 ms/op
                 existUser·p0.99:   4.383 ms/op
                 existUser·p0.999:  7.440 ms/op
                 existUser·p0.9999: 19.728 ms/op
                 existUser·p1.00:   20.251 ms/op

Iteration   3: 2.878 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.563 ms/op
                 existUser·p0.50:   2.859 ms/op
                 existUser·p0.90:   3.375 ms/op
                 existUser·p0.95:   3.531 ms/op
                 existUser·p0.99:   4.268 ms/op
                 existUser·p0.999:  9.729 ms/op
                 existUser·p0.9999: 14.727 ms/op
                 existUser·p1.00:   14.844 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 332677
  mean =      2.887 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 47640 
    [ 2.500,  5.000) = 283932 
    [ 5.000,  7.500) = 780 
    [ 7.500, 10.000) = 154 
    [10.000, 12.500) = 75 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.519 ms/op
     p(50.0000) =      2.871 ms/op
     p(90.0000) =      3.396 ms/op
     p(95.0000) =      3.568 ms/op
     p(99.0000) =      4.366 ms/op
     p(99.9000) =      7.447 ms/op
     p(99.9900) =     14.844 ms/op
     p(99.9990) =     20.098 ms/op
     p(99.9999) =     20.251 ms/op
    p(100.0000) =     20.251 ms/op


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
# Warmup Iteration   1: 4.110 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.047 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.044 ±(99.9%) 0.007 ms/op
Iteration   1: 2.971 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.732 ms/op
                 getUser·p0.50:   2.974 ms/op
                 getUser·p0.90:   3.559 ms/op
                 getUser·p0.95:   3.801 ms/op
                 getUser·p0.99:   4.571 ms/op
                 getUser·p0.999:  6.922 ms/op
                 getUser·p0.9999: 18.711 ms/op
                 getUser·p1.00:   18.907 ms/op

Iteration   2: 2.958 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.618 ms/op
                 getUser·p0.50:   2.957 ms/op
                 getUser·p0.90:   3.510 ms/op
                 getUser·p0.95:   3.744 ms/op
                 getUser·p0.99:   4.424 ms/op
                 getUser·p0.999:  7.171 ms/op
                 getUser·p0.9999: 22.020 ms/op
                 getUser·p1.00:   22.807 ms/op

Iteration   3: 3.054 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.714 ms/op
                 getUser·p0.50:   3.023 ms/op
                 getUser·p0.90:   3.621 ms/op
                 getUser·p0.95:   3.781 ms/op
                 getUser·p0.99:   4.357 ms/op
                 getUser·p0.999:  8.447 ms/op
                 getUser·p0.9999: 15.475 ms/op
                 getUser·p1.00:   17.302 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 320476
  mean =      2.994 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 31757 
    [ 2.500,  5.000) = 287262 
    [ 5.000,  7.500) = 1102 
    [ 7.500, 10.000) = 137 
    [10.000, 12.500) = 48 
    [12.500, 15.000) = 71 
    [15.000, 17.500) = 49 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.618 ms/op
     p(50.0000) =      2.982 ms/op
     p(90.0000) =      3.572 ms/op
     p(95.0000) =      3.777 ms/op
     p(99.0000) =      4.465 ms/op
     p(99.9000) =      7.795 ms/op
     p(99.9900) =     20.280 ms/op
     p(99.9990) =     22.655 ms/op
     p(99.9999) =     22.807 ms/op
    p(100.0000) =     22.807 ms/op


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
# Warmup Iteration   1: 4.727 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.895 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.868 ±(99.9%) 0.010 ms/op
Iteration   1: 3.848 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.077 ms/op
                 listUser·p0.50:   3.731 ms/op
                 listUser·p0.90:   4.612 ms/op
                 listUser·p0.95:   5.226 ms/op
                 listUser·p0.99:   6.434 ms/op
                 listUser·p0.999:  12.075 ms/op
                 listUser·p0.9999: 18.044 ms/op
                 listUser·p1.00:   18.481 ms/op

Iteration   2: 3.722 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.128 ms/op
                 listUser·p0.50:   3.617 ms/op
                 listUser·p0.90:   4.628 ms/op
                 listUser·p0.95:   5.366 ms/op
                 listUser·p0.99:   6.652 ms/op
                 listUser·p0.999:  13.569 ms/op
                 listUser·p0.9999: 15.516 ms/op
                 listUser·p1.00:   17.302 ms/op

Iteration   3: 3.683 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.560 ms/op
                 listUser·p0.50:   3.580 ms/op
                 listUser·p0.90:   4.506 ms/op
                 listUser·p0.95:   5.407 ms/op
                 listUser·p0.99:   6.423 ms/op
                 listUser·p0.999:  12.632 ms/op
                 listUser·p0.9999: 17.148 ms/op
                 listUser·p1.00:   21.103 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 256062
  mean =      3.749 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5438 
    [ 2.500,  5.000) = 233089 
    [ 5.000,  7.500) = 16638 
    [ 7.500, 10.000) = 494 
    [10.000, 12.500) = 129 
    [12.500, 15.000) = 148 
    [15.000, 17.500) = 103 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.560 ms/op
     p(50.0000) =      3.650 ms/op
     p(90.0000) =      4.579 ms/op
     p(95.0000) =      5.325 ms/op
     p(99.0000) =      6.504 ms/op
     p(99.9000) =     12.681 ms/op
     p(99.9900) =     17.334 ms/op
     p(99.9990) =     20.404 ms/op
     p(99.9999) =     21.103 ms/op
    p(100.0000) =     21.103 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.819 ± 2.209  ops/ms
ClientGrpc.existUser                       thrpt       3  11.158 ± 3.420  ops/ms
ClientGrpc.getUser                         thrpt       3  10.897 ± 2.140  ops/ms
ClientGrpc.listUser                        thrpt       3   8.405 ± 0.661  ops/ms
ClientGrpc.createUser                       avgt       3   2.988 ± 0.349   ms/op
ClientGrpc.existUser                        avgt       3   2.931 ± 1.091   ms/op
ClientGrpc.getUser                          avgt       3   2.973 ± 0.463   ms/op
ClientGrpc.listUser                         avgt       3   3.792 ± 1.210   ms/op
ClientGrpc.createUser                     sample  318209   3.018 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.550           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.994           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.518           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.760           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.481           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.036           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          16.628           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          17.793           ms/op
ClientGrpc.existUser                      sample  332677   2.887 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.519           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.871           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.396           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.568           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.366           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.447           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.844           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.251           ms/op
ClientGrpc.getUser                        sample  320476   2.994 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.618           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.982           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.572           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.777           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.465           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.795           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.280           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.807           ms/op
ClientGrpc.listUser                       sample  256062   3.749 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.560           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.650           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.579           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.325           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.504           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          12.681           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          17.334           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          21.103           ms/op
