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
# Warmup Iteration   1: 4.664 ops/ms
# Warmup Iteration   2: 9.754 ops/ms
# Warmup Iteration   3: 10.361 ops/ms
Iteration   1: 10.411 ops/ms
Iteration   2: 11.114 ops/ms
Iteration   3: 10.304 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.610 ±(99.9%) 8.028 ops/ms [Average]
  (min, avg, max) = (10.304, 10.610, 11.114), stdev = 0.440
  CI (99.9%): [2.582, 18.638] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 7.938 ops/ms
# Warmup Iteration   2: 10.621 ops/ms
# Warmup Iteration   3: 10.754 ops/ms
Iteration   1: 10.965 ops/ms
Iteration   2: 10.888 ops/ms
Iteration   3: 10.903 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.919 ±(99.9%) 0.743 ops/ms [Average]
  (min, avg, max) = (10.888, 10.919, 10.965), stdev = 0.041
  CI (99.9%): [10.175, 11.662] (assumes normal distribution)


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
# Warmup Iteration   1: 8.043 ops/ms
# Warmup Iteration   2: 10.388 ops/ms
# Warmup Iteration   3: 10.532 ops/ms
Iteration   1: 10.626 ops/ms
Iteration   2: 10.714 ops/ms
Iteration   3: 10.548 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.629 ±(99.9%) 1.520 ops/ms [Average]
  (min, avg, max) = (10.548, 10.629, 10.714), stdev = 0.083
  CI (99.9%): [9.110, 12.149] (assumes normal distribution)


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
# Warmup Iteration   1: 6.880 ops/ms
# Warmup Iteration   2: 7.991 ops/ms
# Warmup Iteration   3: 8.074 ops/ms
Iteration   1: 7.953 ops/ms
Iteration   2: 8.021 ops/ms
Iteration   3: 8.295 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.089 ±(99.9%) 3.310 ops/ms [Average]
  (min, avg, max) = (7.953, 8.089, 8.295), stdev = 0.181
  CI (99.9%): [4.779, 11.400] (assumes normal distribution)


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
# Warmup Iteration   1: 3.702 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.018 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.017 ±(99.9%) 0.004 ms/op
Iteration   1: 3.156 ±(99.9%) 0.002 ms/op
Iteration   2: 2.905 ±(99.9%) 0.002 ms/op
Iteration   3: 3.002 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.021 ±(99.9%) 2.312 ms/op [Average]
  (min, avg, max) = (2.905, 3.021, 3.156), stdev = 0.127
  CI (99.9%): [0.709, 5.332] (assumes normal distribution)


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
# Warmup Iteration   1: 3.668 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.882 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.957 ±(99.9%) 0.002 ms/op
Iteration   1: 2.928 ±(99.9%) 0.003 ms/op
Iteration   2: 2.964 ±(99.9%) 0.001 ms/op
Iteration   3: 2.915 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.936 ±(99.9%) 0.468 ms/op [Average]
  (min, avg, max) = (2.915, 2.936, 2.964), stdev = 0.026
  CI (99.9%): [2.468, 3.403] (assumes normal distribution)


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
# Warmup Iteration   1: 3.718 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.136 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.029 ±(99.9%) 0.003 ms/op
Iteration   1: 3.055 ±(99.9%) 0.002 ms/op
Iteration   2: 3.047 ±(99.9%) 0.002 ms/op
Iteration   3: 3.038 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.047 ±(99.9%) 0.151 ms/op [Average]
  (min, avg, max) = (3.038, 3.047, 3.055), stdev = 0.008
  CI (99.9%): [2.896, 3.197] (assumes normal distribution)


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
# Warmup Iteration   1: 5.078 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 4.078 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 4.012 ±(99.9%) 0.014 ms/op
Iteration   1: 4.007 ±(99.9%) 0.017 ms/op
Iteration   2: 3.866 ±(99.9%) 0.024 ms/op
Iteration   3: 3.955 ±(99.9%) 0.052 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.943 ±(99.9%) 1.300 ms/op [Average]
  (min, avg, max) = (3.866, 3.943, 4.007), stdev = 0.071
  CI (99.9%): [2.643, 5.243] (assumes normal distribution)


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
# Warmup Iteration   1: 3.925 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.126 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.027 ±(99.9%) 0.007 ms/op
Iteration   1: 3.127 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.804 ms/op
                 createUser·p0.50:   3.117 ms/op
                 createUser·p0.90:   3.834 ms/op
                 createUser·p0.95:   3.994 ms/op
                 createUser·p0.99:   4.301 ms/op
                 createUser·p0.999:  8.006 ms/op
                 createUser·p0.9999: 14.615 ms/op
                 createUser·p1.00:   14.893 ms/op

Iteration   2: 3.007 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.274 ms/op
                 createUser·p0.50:   2.986 ms/op
                 createUser·p0.90:   3.453 ms/op
                 createUser·p0.95:   3.748 ms/op
                 createUser·p0.99:   4.358 ms/op
                 createUser·p0.999:  7.725 ms/op
                 createUser·p0.9999: 19.902 ms/op
                 createUser·p1.00:   20.382 ms/op

Iteration   3: 3.002 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.521 ms/op
                 createUser·p0.50:   2.994 ms/op
                 createUser·p0.90:   3.498 ms/op
                 createUser·p0.95:   3.736 ms/op
                 createUser·p0.99:   4.489 ms/op
                 createUser·p0.999:  10.781 ms/op
                 createUser·p0.9999: 16.384 ms/op
                 createUser·p1.00:   18.973 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 315117
  mean =      3.044 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 28016 
    [ 2.500,  5.000) = 285691 
    [ 5.000,  7.500) = 1020 
    [ 7.500, 10.000) = 107 
    [10.000, 12.500) = 97 
    [12.500, 15.000) = 80 
    [15.000, 17.500) = 73 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.274 ms/op
     p(50.0000) =      3.015 ms/op
     p(90.0000) =      3.654 ms/op
     p(95.0000) =      3.879 ms/op
     p(99.0000) =      4.375 ms/op
     p(99.9000) =      9.022 ms/op
     p(99.9900) =     19.038 ms/op
     p(99.9990) =     20.273 ms/op
     p(99.9999) =     20.382 ms/op
    p(100.0000) =     20.382 ms/op


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
# Warmup Iteration   1: 3.681 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 2.990 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.008 ±(99.9%) 0.007 ms/op
Iteration   1: 2.921 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.809 ms/op
                 existUser·p0.50:   2.871 ms/op
                 existUser·p0.90:   3.670 ms/op
                 existUser·p0.95:   3.858 ms/op
                 existUser·p0.99:   4.301 ms/op
                 existUser·p0.999:  7.012 ms/op
                 existUser·p0.9999: 11.554 ms/op
                 existUser·p1.00:   12.157 ms/op

Iteration   2: 3.010 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.552 ms/op
                 existUser·p0.50:   2.990 ms/op
                 existUser·p0.90:   3.719 ms/op
                 existUser·p0.95:   3.891 ms/op
                 existUser·p0.99:   4.186 ms/op
                 existUser·p0.999:  5.945 ms/op
                 existUser·p0.9999: 22.675 ms/op
                 existUser·p1.00:   23.265 ms/op

Iteration   3: 2.942 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.561 ms/op
                 existUser·p0.50:   2.933 ms/op
                 existUser·p0.90:   3.486 ms/op
                 existUser·p0.95:   3.670 ms/op
                 existUser·p0.99:   4.174 ms/op
                 existUser·p0.999:  6.435 ms/op
                 existUser·p0.9999: 25.690 ms/op
                 existUser·p1.00:   25.887 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 324566
  mean =      2.957 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 54735 
    [ 2.500,  5.000) = 269037 
    [ 5.000,  7.500) = 595 
    [ 7.500, 10.000) = 38 
    [10.000, 12.500) = 33 
    [12.500, 15.000) = 29 
    [15.000, 17.500) = 35 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 27 

  Percentiles, ms/op:
      p(0.0000) =      0.552 ms/op
     p(50.0000) =      2.933 ms/op
     p(90.0000) =      3.633 ms/op
     p(95.0000) =      3.830 ms/op
     p(99.0000) =      4.219 ms/op
     p(99.9000) =      6.451 ms/op
     p(99.9900) =     23.354 ms/op
     p(99.9990) =     25.813 ms/op
     p(99.9999) =     25.887 ms/op
    p(100.0000) =     25.887 ms/op


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
# Warmup Iteration   1: 4.141 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.139 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.024 ±(99.9%) 0.006 ms/op
Iteration   1: 3.063 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.656 ms/op
                 getUser·p0.50:   3.035 ms/op
                 getUser·p0.90:   3.678 ms/op
                 getUser·p0.95:   3.895 ms/op
                 getUser·p0.99:   4.358 ms/op
                 getUser·p0.999:  9.234 ms/op
                 getUser·p0.9999: 15.840 ms/op
                 getUser·p1.00:   16.777 ms/op

Iteration   2: 3.114 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.764 ms/op
                 getUser·p0.50:   3.105 ms/op
                 getUser·p0.90:   3.768 ms/op
                 getUser·p0.95:   3.924 ms/op
                 getUser·p0.99:   4.284 ms/op
                 getUser·p0.999:  7.130 ms/op
                 getUser·p0.9999: 15.843 ms/op
                 getUser·p1.00:   16.105 ms/op

Iteration   3: 3.112 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.669 ms/op
                 getUser·p0.50:   3.088 ms/op
                 getUser·p0.90:   3.785 ms/op
                 getUser·p0.95:   3.977 ms/op
                 getUser·p0.99:   4.375 ms/op
                 getUser·p0.999:  8.623 ms/op
                 getUser·p0.9999: 17.620 ms/op
                 getUser·p1.00:   17.957 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 309971
  mean =      3.096 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1228 
    [ 1.250,  2.500) = 27938 
    [ 2.500,  3.750) = 249888 
    [ 3.750,  5.000) = 29598 
    [ 5.000,  6.250) = 664 
    [ 6.250,  7.500) = 257 
    [ 7.500,  8.750) = 121 
    [ 8.750, 10.000) = 22 
    [10.000, 11.250) = 2 
    [11.250, 12.500) = 10 
    [12.500, 13.750) = 37 
    [13.750, 15.000) = 91 
    [15.000, 16.250) = 79 
    [16.250, 17.500) = 21 
    [17.500, 18.750) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.656 ms/op
     p(50.0000) =      3.076 ms/op
     p(90.0000) =      3.748 ms/op
     p(95.0000) =      3.936 ms/op
     p(99.0000) =      4.334 ms/op
     p(99.9000) =      8.217 ms/op
     p(99.9900) =     17.203 ms/op
     p(99.9990) =     17.823 ms/op
     p(99.9999) =     17.957 ms/op
    p(100.0000) =     17.957 ms/op


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
# Warmup Iteration   1: 4.462 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 4.218 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.062 ±(99.9%) 0.012 ms/op
Iteration   1: 3.911 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.247 ms/op
                 listUser·p0.50:   3.744 ms/op
                 listUser·p0.90:   5.153 ms/op
                 listUser·p0.95:   5.751 ms/op
                 listUser·p0.99:   6.832 ms/op
                 listUser·p0.999:  13.275 ms/op
                 listUser·p0.9999: 14.508 ms/op
                 listUser·p1.00:   14.942 ms/op

Iteration   2: 3.938 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.638 ms/op
                 listUser·p0.50:   3.805 ms/op
                 listUser·p0.90:   4.743 ms/op
                 listUser·p0.95:   5.439 ms/op
                 listUser·p0.99:   6.562 ms/op
                 listUser·p0.999:  14.171 ms/op
                 listUser·p0.9999: 21.127 ms/op
                 listUser·p1.00:   21.955 ms/op

Iteration   3: 3.913 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.906 ms/op
                 listUser·p0.50:   3.785 ms/op
                 listUser·p0.90:   4.801 ms/op
                 listUser·p0.95:   5.513 ms/op
                 listUser·p0.99:   6.742 ms/op
                 listUser·p0.999:  19.956 ms/op
                 listUser·p0.9999: 23.504 ms/op
                 listUser·p1.00:   24.642 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 244751
  mean =      3.921 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3323 
    [ 2.500,  5.000) = 218825 
    [ 5.000,  7.500) = 21564 
    [ 7.500, 10.000) = 650 
    [10.000, 12.500) = 79 
    [12.500, 15.000) = 113 
    [15.000, 17.500) = 53 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 85 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.638 ms/op
     p(50.0000) =      3.781 ms/op
     p(90.0000) =      4.915 ms/op
     p(95.0000) =      5.587 ms/op
     p(99.0000) =      6.717 ms/op
     p(99.9000) =     13.828 ms/op
     p(99.9900) =     22.660 ms/op
     p(99.9990) =     24.514 ms/op
     p(99.9999) =     24.642 ms/op
    p(100.0000) =     24.642 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.610 ± 8.028  ops/ms
ClientGrpc.existUser                       thrpt       3  10.919 ± 0.743  ops/ms
ClientGrpc.getUser                         thrpt       3  10.629 ± 1.520  ops/ms
ClientGrpc.listUser                        thrpt       3   8.089 ± 3.310  ops/ms
ClientGrpc.createUser                       avgt       3   3.021 ± 2.312   ms/op
ClientGrpc.existUser                        avgt       3   2.936 ± 0.468   ms/op
ClientGrpc.getUser                          avgt       3   3.047 ± 0.151   ms/op
ClientGrpc.listUser                         avgt       3   3.943 ± 1.300   ms/op
ClientGrpc.createUser                     sample  315117   3.044 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.274           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.015           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.654           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.879           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.375           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.022           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.038           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          20.382           ms/op
ClientGrpc.existUser                      sample  324566   2.957 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.552           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.933           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.633           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.830           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.219           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.451           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          23.354           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          25.887           ms/op
ClientGrpc.getUser                        sample  309971   3.096 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.656           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.076           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.748           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.936           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.334           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.217           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.203           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          17.957           ms/op
ClientGrpc.listUser                       sample  244751   3.921 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.638           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.781           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.915           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.587           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.717           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.828           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.660           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.642           ms/op
