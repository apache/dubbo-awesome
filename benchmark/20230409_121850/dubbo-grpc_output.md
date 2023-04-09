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
# Warmup Iteration   1: 3.967 ops/ms
# Warmup Iteration   2: 8.940 ops/ms
# Warmup Iteration   3: 10.209 ops/ms
Iteration   1: 10.358 ops/ms
Iteration   2: 10.381 ops/ms
Iteration   3: 10.950 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.563 ±(99.9%) 6.117 ops/ms [Average]
  (min, avg, max) = (10.358, 10.563, 10.950), stdev = 0.335
  CI (99.9%): [4.446, 16.680] (assumes normal distribution)


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
# Warmup Iteration   1: 8.508 ops/ms
# Warmup Iteration   2: 10.445 ops/ms
# Warmup Iteration   3: 11.244 ops/ms
Iteration   1: 11.036 ops/ms
Iteration   2: 11.396 ops/ms
Iteration   3: 11.113 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.181 ±(99.9%) 3.456 ops/ms [Average]
  (min, avg, max) = (11.036, 11.181, 11.396), stdev = 0.189
  CI (99.9%): [7.725, 14.638] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 6.945 ops/ms
# Warmup Iteration   2: 10.271 ops/ms
# Warmup Iteration   3: 10.524 ops/ms
Iteration   1: 10.552 ops/ms
Iteration   2: 10.585 ops/ms
Iteration   3: 10.549 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.562 ±(99.9%) 0.369 ops/ms [Average]
  (min, avg, max) = (10.549, 10.562, 10.585), stdev = 0.020
  CI (99.9%): [10.193, 10.931] (assumes normal distribution)


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
# Warmup Iteration   1: 5.305 ops/ms
# Warmup Iteration   2: 7.834 ops/ms
# Warmup Iteration   3: 8.049 ops/ms
Iteration   1: 7.997 ops/ms
Iteration   2: 7.978 ops/ms
Iteration   3: 8.224 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.066 ±(99.9%) 2.495 ops/ms [Average]
  (min, avg, max) = (7.978, 8.066, 8.224), stdev = 0.137
  CI (99.9%): [5.571, 10.561] (assumes normal distribution)


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
# Warmup Iteration   1: 4.272 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.195 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.087 ±(99.9%) 0.002 ms/op
Iteration   1: 3.063 ±(99.9%) 0.003 ms/op
Iteration   2: 3.102 ±(99.9%) 0.003 ms/op
Iteration   3: 3.049 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.071 ±(99.9%) 0.501 ms/op [Average]
  (min, avg, max) = (3.049, 3.071, 3.102), stdev = 0.027
  CI (99.9%): [2.570, 3.573] (assumes normal distribution)


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
# Warmup Iteration   1: 4.083 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.963 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.933 ±(99.9%) 0.002 ms/op
Iteration   1: 2.948 ±(99.9%) 0.002 ms/op
Iteration   2: 2.854 ±(99.9%) 0.002 ms/op
Iteration   3: 2.832 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.878 ±(99.9%) 1.122 ms/op [Average]
  (min, avg, max) = (2.832, 2.878, 2.948), stdev = 0.061
  CI (99.9%): [1.756, 4.000] (assumes normal distribution)


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
# Warmup Iteration   1: 4.352 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.228 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.080 ±(99.9%) 0.004 ms/op
Iteration   1: 3.044 ±(99.9%) 0.004 ms/op
Iteration   2: 3.067 ±(99.9%) 0.002 ms/op
Iteration   3: 3.027 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.046 ±(99.9%) 0.369 ms/op [Average]
  (min, avg, max) = (3.027, 3.046, 3.067), stdev = 0.020
  CI (99.9%): [2.677, 3.415] (assumes normal distribution)


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
# Warmup Iteration   1: 4.973 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 4.102 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.906 ±(99.9%) 0.012 ms/op
Iteration   1: 3.916 ±(99.9%) 0.016 ms/op
Iteration   2: 3.963 ±(99.9%) 0.014 ms/op
Iteration   3: 3.915 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.931 ±(99.9%) 0.501 ms/op [Average]
  (min, avg, max) = (3.915, 3.931, 3.963), stdev = 0.027
  CI (99.9%): [3.430, 4.433] (assumes normal distribution)


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
# Warmup Iteration   1: 4.388 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.198 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.986 ±(99.9%) 0.006 ms/op
Iteration   1: 2.995 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.355 ms/op
                 createUser·p0.50:   2.970 ms/op
                 createUser·p0.90:   3.523 ms/op
                 createUser·p0.95:   3.711 ms/op
                 createUser·p0.99:   4.317 ms/op
                 createUser·p0.999:  8.707 ms/op
                 createUser·p0.9999: 12.976 ms/op
                 createUser·p1.00:   13.271 ms/op

Iteration   2: 2.995 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.895 ms/op
                 createUser·p0.50:   2.978 ms/op
                 createUser·p0.90:   3.527 ms/op
                 createUser·p0.95:   3.756 ms/op
                 createUser·p0.99:   4.178 ms/op
                 createUser·p0.999:  6.619 ms/op
                 createUser·p0.9999: 13.615 ms/op
                 createUser·p1.00:   13.812 ms/op

Iteration   3: 3.034 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.717 ms/op
                 createUser·p0.50:   3.002 ms/op
                 createUser·p0.90:   3.559 ms/op
                 createUser·p0.95:   3.744 ms/op
                 createUser·p0.99:   4.350 ms/op
                 createUser·p0.999:  8.098 ms/op
                 createUser·p0.9999: 22.690 ms/op
                 createUser·p1.00:   24.281 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 319001
  mean =      3.008 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27739 
    [ 2.500,  5.000) = 290170 
    [ 5.000,  7.500) = 782 
    [ 7.500, 10.000) = 54 
    [10.000, 12.500) = 57 
    [12.500, 15.000) = 110 
    [15.000, 17.500) = 51 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.355 ms/op
     p(50.0000) =      2.982 ms/op
     p(90.0000) =      3.535 ms/op
     p(95.0000) =      3.736 ms/op
     p(99.0000) =      4.284 ms/op
     p(99.9000) =      7.414 ms/op
     p(99.9900) =     22.135 ms/op
     p(99.9990) =     23.938 ms/op
     p(99.9999) =     24.281 ms/op
    p(100.0000) =     24.281 ms/op


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
# Warmup Iteration   1: 4.081 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.041 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.924 ±(99.9%) 0.006 ms/op
Iteration   1: 2.924 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.772 ms/op
                 existUser·p0.50:   2.900 ms/op
                 existUser·p0.90:   3.404 ms/op
                 existUser·p0.95:   3.564 ms/op
                 existUser·p0.99:   4.112 ms/op
                 existUser·p0.999:  6.600 ms/op
                 existUser·p0.9999: 16.947 ms/op
                 existUser·p1.00:   17.367 ms/op

Iteration   2: 2.876 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.725 ms/op
                 existUser·p0.50:   2.871 ms/op
                 existUser·p0.90:   3.310 ms/op
                 existUser·p0.95:   3.490 ms/op
                 existUser·p0.99:   4.384 ms/op
                 existUser·p0.999:  6.547 ms/op
                 existUser·p0.9999: 16.907 ms/op
                 existUser·p1.00:   17.498 ms/op

Iteration   3: 2.912 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.678 ms/op
                 existUser·p0.50:   2.900 ms/op
                 existUser·p0.90:   3.351 ms/op
                 existUser·p0.95:   3.531 ms/op
                 existUser·p0.99:   4.035 ms/op
                 existUser·p0.999:  10.246 ms/op
                 existUser·p0.9999: 20.135 ms/op
                 existUser·p1.00:   21.398 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 330552
  mean =      2.904 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 40510 
    [ 2.500,  5.000) = 288951 
    [ 5.000,  7.500) = 800 
    [ 7.500, 10.000) = 58 
    [10.000, 12.500) = 73 
    [12.500, 15.000) = 6 
    [15.000, 17.500) = 94 
    [17.500, 20.000) = 45 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.678 ms/op
     p(50.0000) =      2.892 ms/op
     p(90.0000) =      3.355 ms/op
     p(95.0000) =      3.535 ms/op
     p(99.0000) =      4.149 ms/op
     p(99.9000) =      7.072 ms/op
     p(99.9900) =     19.462 ms/op
     p(99.9990) =     21.289 ms/op
     p(99.9999) =     21.398 ms/op
    p(100.0000) =     21.398 ms/op


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
# Warmup Iteration   1: 4.321 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.159 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.056 ±(99.9%) 0.006 ms/op
Iteration   1: 3.058 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.680 ms/op
                 getUser·p0.50:   3.031 ms/op
                 getUser·p0.90:   3.645 ms/op
                 getUser·p0.95:   3.830 ms/op
                 getUser·p0.99:   4.489 ms/op
                 getUser·p0.999:  7.756 ms/op
                 getUser·p0.9999: 12.575 ms/op
                 getUser·p1.00:   12.747 ms/op

Iteration   2: 3.017 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.963 ms/op
                 getUser·p0.50:   2.998 ms/op
                 getUser·p0.90:   3.518 ms/op
                 getUser·p0.95:   3.740 ms/op
                 getUser·p0.99:   4.334 ms/op
                 getUser·p0.999:  6.750 ms/op
                 getUser·p0.9999: 14.637 ms/op
                 getUser·p1.00:   15.008 ms/op

Iteration   3: 3.007 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.750 ms/op
                 getUser·p0.50:   2.986 ms/op
                 getUser·p0.90:   3.420 ms/op
                 getUser·p0.95:   3.621 ms/op
                 getUser·p0.99:   4.588 ms/op
                 getUser·p0.999:  7.234 ms/op
                 getUser·p0.9999: 21.162 ms/op
                 getUser·p1.00:   21.692 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 317028
  mean =      3.027 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21705 
    [ 2.500,  5.000) = 293745 
    [ 5.000,  7.500) = 1280 
    [ 7.500, 10.000) = 106 
    [10.000, 12.500) = 43 
    [12.500, 15.000) = 89 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.680 ms/op
     p(50.0000) =      3.002 ms/op
     p(90.0000) =      3.535 ms/op
     p(95.0000) =      3.752 ms/op
     p(99.0000) =      4.473 ms/op
     p(99.9000) =      7.299 ms/op
     p(99.9900) =     19.189 ms/op
     p(99.9990) =     21.583 ms/op
     p(99.9999) =     21.692 ms/op
    p(100.0000) =     21.692 ms/op


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
# Warmup Iteration   1: 5.429 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 4.027 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.987 ±(99.9%) 0.010 ms/op
Iteration   1: 3.951 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.475 ms/op
                 listUser·p0.50:   3.801 ms/op
                 listUser·p0.90:   4.784 ms/op
                 listUser·p0.95:   5.358 ms/op
                 listUser·p0.99:   6.754 ms/op
                 listUser·p0.999:  13.895 ms/op
                 listUser·p0.9999: 23.256 ms/op
                 listUser·p1.00:   23.626 ms/op

Iteration   2: 3.977 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.229 ms/op
                 listUser·p0.50:   3.801 ms/op
                 listUser·p0.90:   5.087 ms/op
                 listUser·p0.95:   5.923 ms/op
                 listUser·p0.99:   6.808 ms/op
                 listUser·p0.999:  14.500 ms/op
                 listUser·p0.9999: 17.136 ms/op
                 listUser·p1.00:   17.400 ms/op

Iteration   3: 3.968 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.167 ms/op
                 listUser·p0.50:   3.830 ms/op
                 listUser·p0.90:   4.841 ms/op
                 listUser·p0.95:   5.521 ms/op
                 listUser·p0.99:   6.816 ms/op
                 listUser·p0.999:  15.440 ms/op
                 listUser·p0.9999: 23.953 ms/op
                 listUser·p1.00:   25.657 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 241901
  mean =      3.965 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2621 
    [ 2.500,  5.000) = 217605 
    [ 5.000,  7.500) = 20542 
    [ 7.500, 10.000) = 678 
    [10.000, 12.500) = 71 
    [12.500, 15.000) = 173 
    [15.000, 17.500) = 115 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 39 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      1.167 ms/op
     p(50.0000) =      3.809 ms/op
     p(90.0000) =      4.907 ms/op
     p(95.0000) =      5.652 ms/op
     p(99.0000) =      6.791 ms/op
     p(99.9000) =     14.451 ms/op
     p(99.9900) =     23.560 ms/op
     p(99.9990) =     25.537 ms/op
     p(99.9999) =     25.657 ms/op
    p(100.0000) =     25.657 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.563 ± 6.117  ops/ms
ClientGrpc.existUser                       thrpt       3  11.181 ± 3.456  ops/ms
ClientGrpc.getUser                         thrpt       3  10.562 ± 0.369  ops/ms
ClientGrpc.listUser                        thrpt       3   8.066 ± 2.495  ops/ms
ClientGrpc.createUser                       avgt       3   3.071 ± 0.501   ms/op
ClientGrpc.existUser                        avgt       3   2.878 ± 1.122   ms/op
ClientGrpc.getUser                          avgt       3   3.046 ± 0.369   ms/op
ClientGrpc.listUser                         avgt       3   3.931 ± 0.501   ms/op
ClientGrpc.createUser                     sample  319001   3.008 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.355           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.982           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.535           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.736           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.284           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.414           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          22.135           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          24.281           ms/op
ClientGrpc.existUser                      sample  330552   2.904 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.678           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.892           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.355           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.535           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.149           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.072           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.462           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.398           ms/op
ClientGrpc.getUser                        sample  317028   3.027 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.680           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.002           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.535           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.752           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.473           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.299           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.189           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.692           ms/op
ClientGrpc.listUser                       sample  241901   3.965 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.167           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.809           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.907           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.652           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.791           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.451           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.560           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.657           ms/op
