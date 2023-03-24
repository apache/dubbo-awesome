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
# Warmup Iteration   1: 3.494 ops/ms
# Warmup Iteration   2: 7.347 ops/ms
# Warmup Iteration   3: 8.564 ops/ms
Iteration   1: 8.824 ops/ms
Iteration   2: 9.005 ops/ms
Iteration   3: 8.871 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.900 ±(99.9%) 1.721 ops/ms [Average]
  (min, avg, max) = (8.824, 8.900, 9.005), stdev = 0.094
  CI (99.9%): [7.179, 10.621] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:01
# Fork: 1 of 1
# Warmup Iteration   1: 6.156 ops/ms
# Warmup Iteration   2: 8.939 ops/ms
# Warmup Iteration   3: 9.396 ops/ms
Iteration   1: 9.456 ops/ms
Iteration   2: 9.577 ops/ms
Iteration   3: 9.541 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.525 ±(99.9%) 1.137 ops/ms [Average]
  (min, avg, max) = (9.456, 9.525, 9.577), stdev = 0.062
  CI (99.9%): [8.387, 10.662] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 5.686 ops/ms
# Warmup Iteration   2: 8.491 ops/ms
# Warmup Iteration   3: 9.018 ops/ms
Iteration   1: 9.012 ops/ms
Iteration   2: 9.202 ops/ms
Iteration   3: 9.134 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.116 ±(99.9%) 1.751 ops/ms [Average]
  (min, avg, max) = (9.012, 9.116, 9.202), stdev = 0.096
  CI (99.9%): [7.364, 10.867] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 5.301 ops/ms
# Warmup Iteration   2: 6.160 ops/ms
# Warmup Iteration   3: 6.831 ops/ms
Iteration   1: 6.934 ops/ms
Iteration   2: 6.998 ops/ms
Iteration   3: 6.930 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.954 ±(99.9%) 0.692 ops/ms [Average]
  (min, avg, max) = (6.930, 6.954, 6.998), stdev = 0.038
  CI (99.9%): [6.262, 7.646] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 5.172 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.763 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.726 ±(99.9%) 0.009 ms/op
Iteration   1: 3.599 ±(99.9%) 0.002 ms/op
Iteration   2: 3.502 ±(99.9%) 0.004 ms/op
Iteration   3: 3.564 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.555 ±(99.9%) 0.896 ms/op [Average]
  (min, avg, max) = (3.502, 3.555, 3.599), stdev = 0.049
  CI (99.9%): [2.659, 4.451] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 4.874 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.612 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.381 ±(99.9%) 0.004 ms/op
Iteration   1: 3.310 ±(99.9%) 0.003 ms/op
Iteration   2: 3.310 ±(99.9%) 0.004 ms/op
Iteration   3: 3.341 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.321 ±(99.9%) 0.328 ms/op [Average]
  (min, avg, max) = (3.310, 3.321, 3.341), stdev = 0.018
  CI (99.9%): [2.992, 3.649] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 5.315 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.619 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.558 ±(99.9%) 0.004 ms/op
Iteration   1: 3.476 ±(99.9%) 0.005 ms/op
Iteration   2: 3.476 ±(99.9%) 0.009 ms/op
Iteration   3: 3.482 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.478 ±(99.9%) 0.061 ms/op [Average]
  (min, avg, max) = (3.476, 3.478, 3.482), stdev = 0.003
  CI (99.9%): [3.417, 3.539] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 6.680 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.778 ±(99.9%) 0.031 ms/op
# Warmup Iteration   3: 4.557 ±(99.9%) 0.031 ms/op
Iteration   1: 4.466 ±(99.9%) 0.010 ms/op
Iteration   2: 4.562 ±(99.9%) 0.023 ms/op
Iteration   3: 4.475 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.501 ±(99.9%) 0.963 ms/op [Average]
  (min, avg, max) = (4.466, 4.501, 4.562), stdev = 0.053
  CI (99.9%): [3.538, 5.464] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 5.357 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 3.790 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.530 ±(99.9%) 0.007 ms/op
Iteration   1: 3.456 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.069 ms/op
                 createUser·p0.50:   3.449 ms/op
                 createUser·p0.90:   3.961 ms/op
                 createUser·p0.95:   4.211 ms/op
                 createUser·p0.99:   4.678 ms/op
                 createUser·p0.999:  7.572 ms/op
                 createUser·p0.9999: 13.578 ms/op
                 createUser·p1.00:   13.795 ms/op

Iteration   2: 3.533 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.083 ms/op
                 createUser·p0.50:   3.510 ms/op
                 createUser·p0.90:   4.116 ms/op
                 createUser·p0.95:   4.366 ms/op
                 createUser·p0.99:   5.218 ms/op
                 createUser·p0.999:  7.447 ms/op
                 createUser·p0.9999: 15.578 ms/op
                 createUser·p1.00:   15.843 ms/op

Iteration   3: 3.509 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.954 ms/op
                 createUser·p0.50:   3.494 ms/op
                 createUser·p0.90:   3.944 ms/op
                 createUser·p0.95:   4.100 ms/op
                 createUser·p0.99:   4.923 ms/op
                 createUser·p0.999:  8.272 ms/op
                 createUser·p0.9999: 18.203 ms/op
                 createUser·p1.00:   18.809 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 274476
  mean =      3.499 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 112 
    [ 1.250,  2.500) = 6113 
    [ 2.500,  3.750) = 200710 
    [ 3.750,  5.000) = 65050 
    [ 5.000,  6.250) = 1843 
    [ 6.250,  7.500) = 343 
    [ 7.500,  8.750) = 109 
    [ 8.750, 10.000) = 4 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 74 
    [13.750, 15.000) = 20 
    [15.000, 16.250) = 51 
    [16.250, 17.500) = 25 
    [17.500, 18.750) = 20 

  Percentiles, ms/op:
      p(0.0000) =      0.954 ms/op
     p(50.0000) =      3.486 ms/op
     p(90.0000) =      4.006 ms/op
     p(95.0000) =      4.243 ms/op
     p(99.0000) =      4.940 ms/op
     p(99.9000) =      7.651 ms/op
     p(99.9900) =     17.239 ms/op
     p(99.9990) =     18.629 ms/op
     p(99.9999) =     18.809 ms/op
    p(100.0000) =     18.809 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.932 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.498 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.356 ±(99.9%) 0.006 ms/op
Iteration   1: 3.356 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.855 ms/op
                 existUser·p0.50:   3.334 ms/op
                 existUser·p0.90:   3.813 ms/op
                 existUser·p0.95:   3.994 ms/op
                 existUser·p0.99:   4.899 ms/op
                 existUser·p0.999:  11.798 ms/op
                 existUser·p0.9999: 16.296 ms/op
                 existUser·p1.00:   17.138 ms/op

Iteration   2: 3.371 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.632 ms/op
                 existUser·p0.50:   3.355 ms/op
                 existUser·p0.90:   3.760 ms/op
                 existUser·p0.95:   3.903 ms/op
                 existUser·p0.99:   4.756 ms/op
                 existUser·p0.999:  10.830 ms/op
                 existUser·p0.9999: 17.662 ms/op
                 existUser·p1.00:   18.055 ms/op

Iteration   3: 3.392 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.935 ms/op
                 existUser·p0.50:   3.375 ms/op
                 existUser·p0.90:   3.797 ms/op
                 existUser·p0.95:   3.981 ms/op
                 existUser·p0.99:   5.087 ms/op
                 existUser·p0.999:  7.657 ms/op
                 existUser·p0.9999: 19.974 ms/op
                 existUser·p1.00:   20.218 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 284604
  mean =      3.373 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5713 
    [ 2.500,  5.000) = 276212 
    [ 5.000,  7.500) = 2160 
    [ 7.500, 10.000) = 169 
    [10.000, 12.500) = 183 
    [12.500, 15.000) = 39 
    [15.000, 17.500) = 59 
    [17.500, 20.000) = 62 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.632 ms/op
     p(50.0000) =      3.355 ms/op
     p(90.0000) =      3.789 ms/op
     p(95.0000) =      3.957 ms/op
     p(99.0000) =      4.915 ms/op
     p(99.9000) =     10.574 ms/op
     p(99.9900) =     19.646 ms/op
     p(99.9990) =     20.157 ms/op
     p(99.9999) =     20.218 ms/op
    p(100.0000) =     20.218 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.427 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 3.688 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.629 ±(99.9%) 0.010 ms/op
Iteration   1: 3.562 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.971 ms/op
                 getUser·p0.50:   3.510 ms/op
                 getUser·p0.90:   4.202 ms/op
                 getUser·p0.95:   4.579 ms/op
                 getUser·p0.99:   5.743 ms/op
                 getUser·p0.999:  10.813 ms/op
                 getUser·p0.9999: 16.843 ms/op
                 getUser·p1.00:   17.203 ms/op

Iteration   2: 3.563 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.043 ms/op
                 getUser·p0.50:   3.531 ms/op
                 getUser·p0.90:   4.112 ms/op
                 getUser·p0.95:   4.366 ms/op
                 getUser·p0.99:   5.176 ms/op
                 getUser·p0.999:  7.998 ms/op
                 getUser·p0.9999: 20.056 ms/op
                 getUser·p1.00:   20.480 ms/op

Iteration   3: 3.545 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.972 ms/op
                 getUser·p0.50:   3.510 ms/op
                 getUser·p0.90:   4.227 ms/op
                 getUser·p0.95:   4.481 ms/op
                 getUser·p0.99:   5.489 ms/op
                 getUser·p0.999:  10.122 ms/op
                 getUser·p0.9999: 21.922 ms/op
                 getUser·p1.00:   21.987 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 269938
  mean =      3.557 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8391 
    [ 2.500,  5.000) = 256621 
    [ 5.000,  7.500) = 4287 
    [ 7.500, 10.000) = 342 
    [10.000, 12.500) = 129 
    [12.500, 15.000) = 27 
    [15.000, 17.500) = 57 
    [17.500, 20.000) = 57 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.971 ms/op
     p(50.0000) =      3.518 ms/op
     p(90.0000) =      4.182 ms/op
     p(95.0000) =      4.473 ms/op
     p(99.0000) =      5.497 ms/op
     p(99.9000) =     10.240 ms/op
     p(99.9900) =     20.021 ms/op
     p(99.9990) =     21.987 ms/op
     p(99.9999) =     21.987 ms/op
    p(100.0000) =     21.987 ms/op


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
# Warmup Iteration   1: 5.941 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 4.857 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.673 ±(99.9%) 0.014 ms/op
Iteration   1: 4.695 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.743 ms/op
                 listUser·p0.50:   4.489 ms/op
                 listUser·p0.90:   6.119 ms/op
                 listUser·p0.95:   6.889 ms/op
                 listUser·p0.99:   8.061 ms/op
                 listUser·p0.999:  16.158 ms/op
                 listUser·p0.9999: 19.044 ms/op
                 listUser·p1.00:   19.792 ms/op

Iteration   2: 4.638 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.534 ms/op
                 listUser·p0.50:   4.522 ms/op
                 listUser·p0.90:   5.407 ms/op
                 listUser·p0.95:   6.440 ms/op
                 listUser·p0.99:   7.954 ms/op
                 listUser·p0.999:  15.909 ms/op
                 listUser·p0.9999: 19.071 ms/op
                 listUser·p1.00:   19.923 ms/op

Iteration   3: 4.611 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.046 ms/op
                 listUser·p0.50:   4.415 ms/op
                 listUser·p0.90:   5.685 ms/op
                 listUser·p0.95:   6.373 ms/op
                 listUser·p0.99:   8.045 ms/op
                 listUser·p0.999:  19.518 ms/op
                 listUser·p0.9999: 24.096 ms/op
                 listUser·p1.00:   25.199 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 206528
  mean =      4.648 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 593 
    [ 2.500,  5.000) = 166789 
    [ 5.000,  7.500) = 35452 
    [ 7.500, 10.000) = 3121 
    [10.000, 12.500) = 226 
    [12.500, 15.000) = 45 
    [15.000, 17.500) = 101 
    [17.500, 20.000) = 136 
    [20.000, 22.500) = 38 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      1.046 ms/op
     p(50.0000) =      4.481 ms/op
     p(90.0000) =      5.775 ms/op
     p(95.0000) =      6.619 ms/op
     p(99.0000) =      8.028 ms/op
     p(99.9000) =     17.433 ms/op
     p(99.9900) =     23.234 ms/op
     p(99.9990) =     25.068 ms/op
     p(99.9999) =     25.199 ms/op
    p(100.0000) =     25.199 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.900 ± 1.721  ops/ms
ClientGrpc.existUser                       thrpt       3   9.525 ± 1.137  ops/ms
ClientGrpc.getUser                         thrpt       3   9.116 ± 1.751  ops/ms
ClientGrpc.listUser                        thrpt       3   6.954 ± 0.692  ops/ms
ClientGrpc.createUser                       avgt       3   3.555 ± 0.896   ms/op
ClientGrpc.existUser                        avgt       3   3.321 ± 0.328   ms/op
ClientGrpc.getUser                          avgt       3   3.478 ± 0.061   ms/op
ClientGrpc.listUser                         avgt       3   4.501 ± 0.963   ms/op
ClientGrpc.createUser                     sample  274476   3.499 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.954           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.486           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.006           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.243           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.940           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.651           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.239           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          18.809           ms/op
ClientGrpc.existUser                      sample  284604   3.373 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.632           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.355           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.789           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.957           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.915           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.574           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.646           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.218           ms/op
ClientGrpc.getUser                        sample  269938   3.557 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.971           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.518           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.182           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.473           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.497           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.240           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.021           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.987           ms/op
ClientGrpc.listUser                       sample  206528   4.648 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.046           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.481           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.775           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.619           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.028           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.433           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.234           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.199           ms/op
