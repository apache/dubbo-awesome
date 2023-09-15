# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.145 ops/ms
# Warmup Iteration   2: 8.924 ops/ms
# Warmup Iteration   3: 9.886 ops/ms
Iteration   1: 9.837 ops/ms
Iteration   2: 10.209 ops/ms
Iteration   3: 10.078 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.041 ±(99.9%) 3.447 ops/ms [Average]
  (min, avg, max) = (9.837, 10.041, 10.209), stdev = 0.189
  CI (99.9%): [6.594, 13.488] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 7.610 ops/ms
# Warmup Iteration   2: 10.294 ops/ms
# Warmup Iteration   3: 10.641 ops/ms
Iteration   1: 10.644 ops/ms
Iteration   2: 10.498 ops/ms
Iteration   3: 10.622 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.588 ±(99.9%) 1.430 ops/ms [Average]
  (min, avg, max) = (10.498, 10.588, 10.644), stdev = 0.078
  CI (99.9%): [9.158, 12.018] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 6.735 ops/ms
# Warmup Iteration   2: 10.012 ops/ms
# Warmup Iteration   3: 9.834 ops/ms
Iteration   1: 10.266 ops/ms
Iteration   2: 10.231 ops/ms
Iteration   3: 10.281 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.259 ±(99.9%) 0.463 ops/ms [Average]
  (min, avg, max) = (10.231, 10.259, 10.281), stdev = 0.025
  CI (99.9%): [9.796, 10.723] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.728 ops/ms
# Warmup Iteration   2: 7.920 ops/ms
# Warmup Iteration   3: 7.984 ops/ms
Iteration   1: 8.436 ops/ms
Iteration   2: 8.085 ops/ms
Iteration   3: 8.229 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.250 ±(99.9%) 3.220 ops/ms [Average]
  (min, avg, max) = (8.085, 8.250, 8.436), stdev = 0.176
  CI (99.9%): [5.030, 11.470] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.859 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.206 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.095 ±(99.9%) 0.001 ms/op
Iteration   1: 3.106 ±(99.9%) 0.003 ms/op
Iteration   2: 3.110 ±(99.9%) 0.003 ms/op
Iteration   3: 3.136 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.117 ±(99.9%) 0.294 ms/op [Average]
  (min, avg, max) = (3.106, 3.117, 3.136), stdev = 0.016
  CI (99.9%): [2.823, 3.411] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.919 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.990 ±(99.9%) 0.001 ms/op
# Warmup Iteration   3: 3.004 ±(99.9%) 0.002 ms/op
Iteration   1: 2.967 ±(99.9%) 0.002 ms/op
Iteration   2: 2.958 ±(99.9%) 0.002 ms/op
Iteration   3: 2.992 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.973 ±(99.9%) 0.322 ms/op [Average]
  (min, avg, max) = (2.958, 2.973, 2.992), stdev = 0.018
  CI (99.9%): [2.651, 3.295] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.216 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.218 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.113 ±(99.9%) 0.003 ms/op
Iteration   1: 3.101 ±(99.9%) 0.003 ms/op
Iteration   2: 3.061 ±(99.9%) 0.004 ms/op
Iteration   3: 3.082 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.081 ±(99.9%) 0.367 ms/op [Average]
  (min, avg, max) = (3.061, 3.081, 3.101), stdev = 0.020
  CI (99.9%): [2.714, 3.448] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.326 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 4.054 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 3.941 ±(99.9%) 0.015 ms/op
Iteration   1: 3.867 ±(99.9%) 0.028 ms/op
Iteration   2: 3.859 ±(99.9%) 0.021 ms/op
Iteration   3: 3.963 ±(99.9%) 0.029 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.896 ±(99.9%) 1.049 ms/op [Average]
  (min, avg, max) = (3.859, 3.896, 3.963), stdev = 0.058
  CI (99.9%): [2.847, 4.946] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.214 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.200 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.009 ±(99.9%) 0.006 ms/op
Iteration   1: 3.081 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.700 ms/op
                 createUser·p0.50:   3.023 ms/op
                 createUser·p0.90:   3.621 ms/op
                 createUser·p0.95:   3.801 ms/op
                 createUser·p0.99:   4.456 ms/op
                 createUser·p0.999:  7.980 ms/op
                 createUser·p0.9999: 23.822 ms/op
                 createUser·p1.00:   24.576 ms/op

Iteration   2: 3.119 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.542 ms/op
                 createUser·p0.50:   3.084 ms/op
                 createUser·p0.90:   3.633 ms/op
                 createUser·p0.95:   3.744 ms/op
                 createUser·p0.99:   4.102 ms/op
                 createUser·p0.999:  7.700 ms/op
                 createUser·p0.9999: 24.887 ms/op
                 createUser·p1.00:   25.395 ms/op

Iteration   3: 3.129 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.741 ms/op
                 createUser·p0.50:   3.072 ms/op
                 createUser·p0.90:   3.682 ms/op
                 createUser·p0.95:   3.854 ms/op
                 createUser·p0.99:   4.391 ms/op
                 createUser·p0.999:  10.500 ms/op
                 createUser·p0.9999: 25.059 ms/op
                 createUser·p1.00:   26.182 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 308867
  mean =      3.110 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14441 
    [ 2.500,  5.000) = 292630 
    [ 5.000,  7.500) = 1297 
    [ 7.500, 10.000) = 244 
    [10.000, 12.500) = 63 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 38 
    [22.500, 25.000) = 104 
    [25.000, 27.500) = 20 

  Percentiles, ms/op:
      p(0.0000) =      0.542 ms/op
     p(50.0000) =      3.060 ms/op
     p(90.0000) =      3.645 ms/op
     p(95.0000) =      3.797 ms/op
     p(99.0000) =      4.301 ms/op
     p(99.9000) =      9.030 ms/op
     p(99.9900) =     24.773 ms/op
     p(99.9990) =     25.963 ms/op
     p(99.9999) =     26.182 ms/op
    p(100.0000) =     26.182 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.839 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.085 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.044 ±(99.9%) 0.005 ms/op
Iteration   1: 3.015 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.848 ms/op
                 existUser·p0.50:   2.994 ms/op
                 existUser·p0.90:   3.506 ms/op
                 existUser·p0.95:   3.637 ms/op
                 existUser·p0.99:   4.071 ms/op
                 existUser·p0.999:  6.119 ms/op
                 existUser·p0.9999: 11.387 ms/op
                 existUser·p1.00:   11.551 ms/op

Iteration   2: 2.957 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.773 ms/op
                 existUser·p0.50:   2.908 ms/op
                 existUser·p0.90:   3.408 ms/op
                 existUser·p0.95:   3.650 ms/op
                 existUser·p0.99:   4.350 ms/op
                 existUser·p0.999:  7.471 ms/op
                 existUser·p0.9999: 13.145 ms/op
                 existUser·p1.00:   13.320 ms/op

Iteration   3: 2.985 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.743 ms/op
                 existUser·p0.50:   2.961 ms/op
                 existUser·p0.90:   3.572 ms/op
                 existUser·p0.95:   3.736 ms/op
                 existUser·p0.99:   4.465 ms/op
                 existUser·p0.999:  8.273 ms/op
                 existUser·p0.9999: 14.811 ms/op
                 existUser·p1.00:   15.172 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 321602
  mean =      2.986 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1177 
    [ 1.250,  2.500) = 25401 
    [ 2.500,  3.750) = 283308 
    [ 3.750,  5.000) = 10150 
    [ 5.000,  6.250) = 896 
    [ 6.250,  7.500) = 360 
    [ 7.500,  8.750) = 108 
    [ 8.750, 10.000) = 10 
    [10.000, 11.250) = 44 
    [11.250, 12.500) = 27 
    [12.500, 13.750) = 79 
    [13.750, 15.000) = 37 
    [15.000, 16.250) = 5 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.743 ms/op
     p(50.0000) =      2.953 ms/op
     p(90.0000) =      3.506 ms/op
     p(95.0000) =      3.682 ms/op
     p(99.0000) =      4.227 ms/op
     p(99.9000) =      7.392 ms/op
     p(99.9900) =     13.888 ms/op
     p(99.9990) =     15.125 ms/op
     p(99.9999) =     15.172 ms/op
    p(100.0000) =     15.172 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.307 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.240 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.179 ±(99.9%) 0.007 ms/op
Iteration   1: 3.103 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.008 ms/op
                 getUser·p0.50:   3.056 ms/op
                 getUser·p0.90:   3.584 ms/op
                 getUser·p0.95:   3.793 ms/op
                 getUser·p0.99:   4.219 ms/op
                 getUser·p0.999:  7.062 ms/op
                 getUser·p0.9999: 14.878 ms/op
                 getUser·p1.00:   16.007 ms/op

Iteration   2: 3.107 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.888 ms/op
                 getUser·p0.50:   3.047 ms/op
                 getUser·p0.90:   3.703 ms/op
                 getUser·p0.95:   3.850 ms/op
                 getUser·p0.99:   4.669 ms/op
                 getUser·p0.999:  9.259 ms/op
                 getUser·p0.9999: 16.932 ms/op
                 getUser·p1.00:   17.433 ms/op

Iteration   3: 3.054 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.663 ms/op
                 getUser·p0.50:   3.027 ms/op
                 getUser·p0.90:   3.568 ms/op
                 getUser·p0.95:   3.727 ms/op
                 getUser·p0.99:   4.366 ms/op
                 getUser·p0.999:  6.466 ms/op
                 getUser·p0.9999: 19.514 ms/op
                 getUser·p1.00:   19.923 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 310631
  mean =      3.088 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 293 
    [ 1.250,  2.500) = 13831 
    [ 2.500,  3.750) = 277383 
    [ 3.750,  5.000) = 17418 
    [ 5.000,  6.250) = 1082 
    [ 6.250,  7.500) = 271 
    [ 7.500,  8.750) = 102 
    [ 8.750, 10.000) = 66 
    [10.000, 11.250) = 25 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 21 
    [13.750, 15.000) = 49 
    [15.000, 16.250) = 35 
    [16.250, 17.500) = 23 
    [17.500, 18.750) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.663 ms/op
     p(50.0000) =      3.043 ms/op
     p(90.0000) =      3.621 ms/op
     p(95.0000) =      3.797 ms/op
     p(99.0000) =      4.407 ms/op
     p(99.9000) =      7.944 ms/op
     p(99.9900) =     17.623 ms/op
     p(99.9990) =     19.756 ms/op
     p(99.9999) =     19.923 ms/op
    p(100.0000) =     19.923 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.970 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 4.076 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.964 ±(99.9%) 0.009 ms/op
Iteration   1: 3.905 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.335 ms/op
                 listUser·p0.50:   3.817 ms/op
                 listUser·p0.90:   4.407 ms/op
                 listUser·p0.95:   5.079 ms/op
                 listUser·p0.99:   6.570 ms/op
                 listUser·p0.999:  11.978 ms/op
                 listUser·p0.9999: 15.958 ms/op
                 listUser·p1.00:   16.613 ms/op

Iteration   2: 3.951 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.528 ms/op
                 listUser·p0.50:   3.850 ms/op
                 listUser·p0.90:   4.448 ms/op
                 listUser·p0.95:   5.194 ms/op
                 listUser·p0.99:   6.775 ms/op
                 listUser·p0.999:  14.865 ms/op
                 listUser·p0.9999: 19.625 ms/op
                 listUser·p1.00:   20.087 ms/op

Iteration   3: 3.959 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.180 ms/op
                 listUser·p0.50:   3.867 ms/op
                 listUser·p0.90:   4.530 ms/op
                 listUser·p0.95:   5.251 ms/op
                 listUser·p0.99:   6.660 ms/op
                 listUser·p0.999:  15.305 ms/op
                 listUser·p0.9999: 17.039 ms/op
                 listUser·p1.00:   17.433 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 243733
  mean =      3.938 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2166 
    [ 2.500,  5.000) = 227611 
    [ 5.000,  7.500) = 12966 
    [ 7.500, 10.000) = 519 
    [10.000, 12.500) = 161 
    [12.500, 15.000) = 127 
    [15.000, 17.500) = 164 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.180 ms/op
     p(50.0000) =      3.846 ms/op
     p(90.0000) =      4.465 ms/op
     p(95.0000) =      5.161 ms/op
     p(99.0000) =      6.668 ms/op
     p(99.9000) =     13.402 ms/op
     p(99.9900) =     17.220 ms/op
     p(99.9990) =     19.997 ms/op
     p(99.9999) =     20.087 ms/op
    p(100.0000) =     20.087 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.041 ± 3.447  ops/ms
ClientGrpc.existUser                       thrpt       3  10.588 ± 1.430  ops/ms
ClientGrpc.getUser                         thrpt       3  10.259 ± 0.463  ops/ms
ClientGrpc.listUser                        thrpt       3   8.250 ± 3.220  ops/ms
ClientGrpc.createUser                       avgt       3   3.117 ± 0.294   ms/op
ClientGrpc.existUser                        avgt       3   2.973 ± 0.322   ms/op
ClientGrpc.getUser                          avgt       3   3.081 ± 0.367   ms/op
ClientGrpc.listUser                         avgt       3   3.896 ± 1.049   ms/op
ClientGrpc.createUser                     sample  308867   3.110 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.542           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.060           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.645           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.797           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.301           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.030           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          24.773           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          26.182           ms/op
ClientGrpc.existUser                      sample  321602   2.986 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.743           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.953           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.506           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.682           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.227           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.392           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          13.888           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          15.172           ms/op
ClientGrpc.getUser                        sample  310631   3.088 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.663           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.043           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.621           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.797           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.407           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.944           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.623           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.923           ms/op
ClientGrpc.listUser                       sample  243733   3.938 ± 0.005   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.180           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.846           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.465           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.161           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.668           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.402           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          17.220           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          20.087           ms/op
