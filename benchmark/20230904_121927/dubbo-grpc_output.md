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
# Warmup Iteration   1: 4.104 ops/ms
# Warmup Iteration   2: 8.593 ops/ms
# Warmup Iteration   3: 10.013 ops/ms
Iteration   1: 10.219 ops/ms
Iteration   2: 10.464 ops/ms
Iteration   3: 10.347 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.343 ±(99.9%) 2.238 ops/ms [Average]
  (min, avg, max) = (10.219, 10.343, 10.464), stdev = 0.123
  CI (99.9%): [8.106, 12.581] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.060 ops/ms
# Warmup Iteration   2: 10.072 ops/ms
# Warmup Iteration   3: 10.748 ops/ms
Iteration   1: 10.725 ops/ms
Iteration   2: 10.890 ops/ms
Iteration   3: 10.765 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.793 ±(99.9%) 1.568 ops/ms [Average]
  (min, avg, max) = (10.725, 10.793, 10.890), stdev = 0.086
  CI (99.9%): [9.226, 12.361] (assumes normal distribution)


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
# Warmup Iteration   1: 6.374 ops/ms
# Warmup Iteration   2: 9.902 ops/ms
# Warmup Iteration   3: 10.098 ops/ms
Iteration   1: 10.280 ops/ms
Iteration   2: 10.418 ops/ms
Iteration   3: 10.289 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.329 ±(99.9%) 1.404 ops/ms [Average]
  (min, avg, max) = (10.280, 10.329, 10.418), stdev = 0.077
  CI (99.9%): [8.925, 11.733] (assumes normal distribution)


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
# Warmup Iteration   1: 4.772 ops/ms
# Warmup Iteration   2: 7.416 ops/ms
# Warmup Iteration   3: 7.745 ops/ms
Iteration   1: 7.864 ops/ms
Iteration   2: 7.764 ops/ms
Iteration   3: 7.797 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.808 ±(99.9%) 0.934 ops/ms [Average]
  (min, avg, max) = (7.764, 7.808, 7.864), stdev = 0.051
  CI (99.9%): [6.874, 8.743] (assumes normal distribution)


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
# Warmup Iteration   1: 4.562 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.281 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.109 ±(99.9%) 0.003 ms/op
Iteration   1: 3.101 ±(99.9%) 0.008 ms/op
Iteration   2: 3.098 ±(99.9%) 0.002 ms/op
Iteration   3: 3.063 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.088 ±(99.9%) 0.381 ms/op [Average]
  (min, avg, max) = (3.063, 3.088, 3.101), stdev = 0.021
  CI (99.9%): [2.706, 3.469] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.286 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.144 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.024 ±(99.9%) 0.002 ms/op
Iteration   1: 2.974 ±(99.9%) 0.002 ms/op
Iteration   2: 2.923 ±(99.9%) 0.002 ms/op
Iteration   3: 2.918 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.939 ±(99.9%) 0.560 ms/op [Average]
  (min, avg, max) = (2.918, 2.939, 2.974), stdev = 0.031
  CI (99.9%): [2.379, 3.498] (assumes normal distribution)


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
# Warmup Iteration   1: 4.411 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.251 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.144 ±(99.9%) 0.003 ms/op
Iteration   1: 3.128 ±(99.9%) 0.004 ms/op
Iteration   2: 3.183 ±(99.9%) 0.001 ms/op
Iteration   3: 3.098 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.136 ±(99.9%) 0.795 ms/op [Average]
  (min, avg, max) = (3.098, 3.136, 3.183), stdev = 0.044
  CI (99.9%): [2.341, 3.931] (assumes normal distribution)


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
# Warmup Iteration   1: 5.392 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 4.378 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.177 ±(99.9%) 0.009 ms/op
Iteration   1: 4.191 ±(99.9%) 0.015 ms/op
Iteration   2: 4.088 ±(99.9%) 0.011 ms/op
Iteration   3: 4.065 ±(99.9%) 0.023 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.115 ±(99.9%) 1.220 ms/op [Average]
  (min, avg, max) = (4.065, 4.115, 4.191), stdev = 0.067
  CI (99.9%): [2.895, 5.335] (assumes normal distribution)


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
# Warmup Iteration   1: 4.712 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.253 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.206 ±(99.9%) 0.007 ms/op
Iteration   1: 3.082 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.905 ms/op
                 createUser·p0.50:   3.047 ms/op
                 createUser·p0.90:   3.625 ms/op
                 createUser·p0.95:   3.944 ms/op
                 createUser·p0.99:   4.817 ms/op
                 createUser·p0.999:  9.523 ms/op
                 createUser·p0.9999: 17.531 ms/op
                 createUser·p1.00:   17.859 ms/op

Iteration   2: 3.091 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.001 ms/op
                 createUser·p0.50:   3.060 ms/op
                 createUser·p0.90:   3.584 ms/op
                 createUser·p0.95:   3.777 ms/op
                 createUser·p0.99:   4.694 ms/op
                 createUser·p0.999:  9.699 ms/op
                 createUser·p0.9999: 26.072 ms/op
                 createUser·p1.00:   27.165 ms/op

Iteration   3: 3.077 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.387 ms/op
                 createUser·p0.50:   3.056 ms/op
                 createUser·p0.90:   3.547 ms/op
                 createUser·p0.95:   3.772 ms/op
                 createUser·p0.99:   4.596 ms/op
                 createUser·p0.999:  10.765 ms/op
                 createUser·p0.9999: 18.435 ms/op
                 createUser·p1.00:   18.514 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 311191
  mean =      3.083 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18133 
    [ 2.500,  5.000) = 290671 
    [ 5.000,  7.500) = 1658 
    [ 7.500, 10.000) = 416 
    [10.000, 12.500) = 91 
    [12.500, 15.000) = 93 
    [15.000, 17.500) = 60 
    [17.500, 20.000) = 37 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.387 ms/op
     p(50.0000) =      3.056 ms/op
     p(90.0000) =      3.580 ms/op
     p(95.0000) =      3.830 ms/op
     p(99.0000) =      4.719 ms/op
     p(99.9000) =     10.027 ms/op
     p(99.9900) =     25.146 ms/op
     p(99.9990) =     26.436 ms/op
     p(99.9999) =     27.165 ms/op
    p(100.0000) =     27.165 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.182 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.127 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.016 ±(99.9%) 0.005 ms/op
Iteration   1: 2.946 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.779 ms/op
                 existUser·p0.50:   2.933 ms/op
                 existUser·p0.90:   3.375 ms/op
                 existUser·p0.95:   3.568 ms/op
                 existUser·p0.99:   4.317 ms/op
                 existUser·p0.999:  8.983 ms/op
                 existUser·p0.9999: 13.605 ms/op
                 existUser·p1.00:   13.877 ms/op

Iteration   2: 2.931 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.611 ms/op
                 existUser·p0.50:   2.920 ms/op
                 existUser·p0.90:   3.379 ms/op
                 existUser·p0.95:   3.633 ms/op
                 existUser·p0.99:   4.653 ms/op
                 existUser·p0.999:  10.364 ms/op
                 existUser·p0.9999: 23.107 ms/op
                 existUser·p1.00:   23.364 ms/op

Iteration   3: 2.881 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.614 ms/op
                 existUser·p0.50:   2.920 ms/op
                 existUser·p0.90:   3.420 ms/op
                 existUser·p0.95:   3.662 ms/op
                 existUser·p0.99:   4.891 ms/op
                 existUser·p0.999:  9.700 ms/op
                 existUser·p0.9999: 20.667 ms/op
                 existUser·p1.00:   21.201 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 328852
  mean =      2.919 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 38549 
    [ 2.500,  5.000) = 288194 
    [ 5.000,  7.500) = 1545 
    [ 7.500, 10.000) = 286 
    [10.000, 12.500) = 60 
    [12.500, 15.000) = 123 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 44 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.611 ms/op
     p(50.0000) =      2.925 ms/op
     p(90.0000) =      3.391 ms/op
     p(95.0000) =      3.613 ms/op
     p(99.0000) =      4.653 ms/op
     p(99.9000) =      9.650 ms/op
     p(99.9900) =     21.041 ms/op
     p(99.9990) =     23.321 ms/op
     p(99.9999) =     23.364 ms/op
    p(100.0000) =     23.364 ms/op


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
# Warmup Iteration   1: 4.366 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.237 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.117 ±(99.9%) 0.007 ms/op
Iteration   1: 3.102 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.975 ms/op
                 getUser·p0.50:   3.068 ms/op
                 getUser·p0.90:   3.535 ms/op
                 getUser·p0.95:   3.789 ms/op
                 getUser·p0.99:   4.743 ms/op
                 getUser·p0.999:  9.763 ms/op
                 getUser·p0.9999: 15.265 ms/op
                 getUser·p1.00:   15.581 ms/op

Iteration   2: 3.092 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.799 ms/op
                 getUser·p0.50:   3.047 ms/op
                 getUser·p0.90:   3.555 ms/op
                 getUser·p0.95:   3.805 ms/op
                 getUser·p0.99:   4.899 ms/op
                 getUser·p0.999:  10.420 ms/op
                 getUser·p0.9999: 15.707 ms/op
                 getUser·p1.00:   16.482 ms/op

Iteration   3: 3.058 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.604 ms/op
                 getUser·p0.50:   3.027 ms/op
                 getUser·p0.90:   3.559 ms/op
                 getUser·p0.95:   3.891 ms/op
                 getUser·p0.99:   4.874 ms/op
                 getUser·p0.999:  8.425 ms/op
                 getUser·p0.9999: 18.022 ms/op
                 getUser·p1.00:   18.907 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 311322
  mean =      3.084 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 610 
    [ 1.250,  2.500) = 16406 
    [ 2.500,  3.750) = 275601 
    [ 3.750,  5.000) = 16157 
    [ 5.000,  6.250) = 1410 
    [ 6.250,  7.500) = 351 
    [ 7.500,  8.750) = 393 
    [ 8.750, 10.000) = 131 
    [10.000, 11.250) = 39 
    [11.250, 12.500) = 8 
    [12.500, 13.750) = 24 
    [13.750, 15.000) = 37 
    [15.000, 16.250) = 99 
    [16.250, 17.500) = 28 
    [17.500, 18.750) = 27 

  Percentiles, ms/op:
      p(0.0000) =      0.604 ms/op
     p(50.0000) =      3.047 ms/op
     p(90.0000) =      3.547 ms/op
     p(95.0000) =      3.830 ms/op
     p(99.0000) =      4.841 ms/op
     p(99.9000) =      9.421 ms/op
     p(99.9900) =     17.465 ms/op
     p(99.9990) =     18.565 ms/op
     p(99.9999) =     18.907 ms/op
    p(100.0000) =     18.907 ms/op


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
# Warmup Iteration   1: 5.847 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 4.219 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.028 ±(99.9%) 0.011 ms/op
Iteration   1: 4.083 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.614 ms/op
                 listUser·p0.50:   3.928 ms/op
                 listUser·p0.90:   4.940 ms/op
                 listUser·p0.95:   5.890 ms/op
                 listUser·p0.99:   7.348 ms/op
                 listUser·p0.999:  13.479 ms/op
                 listUser·p0.9999: 22.036 ms/op
                 listUser·p1.00:   22.512 ms/op

Iteration   2: 4.030 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.335 ms/op
                 listUser·p0.50:   3.891 ms/op
                 listUser·p0.90:   4.702 ms/op
                 listUser·p0.95:   5.841 ms/op
                 listUser·p0.99:   7.438 ms/op
                 listUser·p0.999:  16.282 ms/op
                 listUser·p0.9999: 23.467 ms/op
                 listUser·p1.00:   23.855 ms/op

Iteration   3: 4.053 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.079 ms/op
                 listUser·p0.50:   3.903 ms/op
                 listUser·p0.90:   4.899 ms/op
                 listUser·p0.95:   5.816 ms/op
                 listUser·p0.99:   7.135 ms/op
                 listUser·p0.999:  16.237 ms/op
                 listUser·p0.9999: 24.969 ms/op
                 listUser·p1.00:   25.592 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 236558
  mean =      4.055 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2059 
    [ 2.500,  5.000) = 213073 
    [ 5.000,  7.500) = 19409 
    [ 7.500, 10.000) = 1487 
    [10.000, 12.500) = 133 
    [12.500, 15.000) = 129 
    [15.000, 17.500) = 136 
    [17.500, 20.000) = 39 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 51 
    [25.000, 27.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      1.079 ms/op
     p(50.0000) =      3.908 ms/op
     p(90.0000) =      4.850 ms/op
     p(95.0000) =      5.857 ms/op
     p(99.0000) =      7.315 ms/op
     p(99.9000) =     15.310 ms/op
     p(99.9900) =     23.790 ms/op
     p(99.9990) =     25.502 ms/op
     p(99.9999) =     25.592 ms/op
    p(100.0000) =     25.592 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.343 ± 2.238  ops/ms
ClientGrpc.existUser                       thrpt       3  10.793 ± 1.568  ops/ms
ClientGrpc.getUser                         thrpt       3  10.329 ± 1.404  ops/ms
ClientGrpc.listUser                        thrpt       3   7.808 ± 0.934  ops/ms
ClientGrpc.createUser                       avgt       3   3.088 ± 0.381   ms/op
ClientGrpc.existUser                        avgt       3   2.939 ± 0.560   ms/op
ClientGrpc.getUser                          avgt       3   3.136 ± 0.795   ms/op
ClientGrpc.listUser                         avgt       3   4.115 ± 1.220   ms/op
ClientGrpc.createUser                     sample  311191   3.083 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.387           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.056           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.580           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.830           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.719           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.027           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          25.146           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          27.165           ms/op
ClientGrpc.existUser                      sample  328852   2.919 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.611           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.925           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.391           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.613           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.653           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.650           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          21.041           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          23.364           ms/op
ClientGrpc.getUser                        sample  311322   3.084 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.604           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.047           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.547           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.830           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.841           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.421           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.465           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.907           ms/op
ClientGrpc.listUser                       sample  236558   4.055 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.079           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.908           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.850           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.857           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.315           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.310           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.790           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.592           ms/op
