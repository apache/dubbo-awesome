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
# Warmup Iteration   1: 3.239 ops/ms
# Warmup Iteration   2: 6.248 ops/ms
# Warmup Iteration   3: 7.921 ops/ms
Iteration   1: 8.258 ops/ms
Iteration   2: 8.379 ops/ms
Iteration   3: 8.411 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.349 ±(99.9%) 1.472 ops/ms [Average]
  (min, avg, max) = (8.258, 8.349, 8.411), stdev = 0.081
  CI (99.9%): [6.878, 9.821] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:04
# Fork: 1 of 1
# Warmup Iteration   1: 5.537 ops/ms
# Warmup Iteration   2: 8.492 ops/ms
# Warmup Iteration   3: 8.856 ops/ms
Iteration   1: 8.939 ops/ms
Iteration   2: 9.218 ops/ms
Iteration   3: 9.332 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.163 ±(99.9%) 3.692 ops/ms [Average]
  (min, avg, max) = (8.939, 9.163, 9.332), stdev = 0.202
  CI (99.9%): [5.471, 12.855] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 5.229 ops/ms
# Warmup Iteration   2: 8.308 ops/ms
# Warmup Iteration   3: 8.420 ops/ms
Iteration   1: 8.484 ops/ms
Iteration   2: 8.968 ops/ms
Iteration   3: 8.670 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.707 ±(99.9%) 4.449 ops/ms [Average]
  (min, avg, max) = (8.484, 8.707, 8.968), stdev = 0.244
  CI (99.9%): [4.258, 13.157] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 4.587 ops/ms
# Warmup Iteration   2: 6.333 ops/ms
# Warmup Iteration   3: 6.518 ops/ms
Iteration   1: 6.572 ops/ms
Iteration   2: 6.739 ops/ms
Iteration   3: 6.657 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.656 ±(99.9%) 1.526 ops/ms [Average]
  (min, avg, max) = (6.572, 6.656, 6.739), stdev = 0.084
  CI (99.9%): [5.130, 8.182] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 5.044 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.773 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 3.640 ±(99.9%) 0.004 ms/op
Iteration   1: 3.573 ±(99.9%) 0.004 ms/op
Iteration   2: 3.507 ±(99.9%) 0.003 ms/op
Iteration   3: 3.637 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.573 ±(99.9%) 1.184 ms/op [Average]
  (min, avg, max) = (3.507, 3.573, 3.637), stdev = 0.065
  CI (99.9%): [2.389, 4.756] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 5.023 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.540 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.333 ±(99.9%) 0.004 ms/op
Iteration   1: 3.304 ±(99.9%) 0.004 ms/op
Iteration   2: 3.249 ±(99.9%) 0.003 ms/op
Iteration   3: 3.308 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.287 ±(99.9%) 0.605 ms/op [Average]
  (min, avg, max) = (3.249, 3.287, 3.308), stdev = 0.033
  CI (99.9%): [2.682, 3.892] (assumes normal distribution)


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
# Warmup Iteration   1: 4.778 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.596 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.333 ±(99.9%) 0.004 ms/op
Iteration   1: 3.343 ±(99.9%) 0.006 ms/op
Iteration   2: 3.487 ±(99.9%) 0.003 ms/op
Iteration   3: 3.624 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.485 ±(99.9%) 2.565 ms/op [Average]
  (min, avg, max) = (3.343, 3.485, 3.624), stdev = 0.141
  CI (99.9%): [0.919, 6.050] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 7.583 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 4.791 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 4.476 ±(99.9%) 0.013 ms/op
Iteration   1: 4.685 ±(99.9%) 0.018 ms/op
Iteration   2: 4.726 ±(99.9%) 0.023 ms/op
Iteration   3: 5.311 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.907 ±(99.9%) 6.388 ms/op [Average]
  (min, avg, max) = (4.685, 4.907, 5.311), stdev = 0.350
  CI (99.9%): [≈ 0, 11.295] (assumes normal distribution)


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
# Warmup Iteration   1: 5.214 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 3.652 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.434 ±(99.9%) 0.008 ms/op
Iteration   1: 3.380 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.748 ms/op
                 createUser·p0.50:   3.334 ms/op
                 createUser·p0.90:   4.035 ms/op
                 createUser·p0.95:   4.342 ms/op
                 createUser·p0.99:   5.497 ms/op
                 createUser·p0.999:  11.423 ms/op
                 createUser·p0.9999: 15.878 ms/op
                 createUser·p1.00:   17.760 ms/op

Iteration   2: 3.440 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.762 ms/op
                 createUser·p0.50:   3.363 ms/op
                 createUser·p0.90:   4.166 ms/op
                 createUser·p0.95:   4.514 ms/op
                 createUser·p0.99:   5.825 ms/op
                 createUser·p0.999:  9.811 ms/op
                 createUser·p0.9999: 20.873 ms/op
                 createUser·p1.00:   21.266 ms/op

Iteration   3: 3.615 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.368 ms/op
                 createUser·p0.50:   3.518 ms/op
                 createUser·p0.90:   4.358 ms/op
                 createUser·p0.95:   4.784 ms/op
                 createUser·p0.99:   6.218 ms/op
                 createUser·p0.999:  11.214 ms/op
                 createUser·p0.9999: 24.412 ms/op
                 createUser·p1.00:   24.773 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 276483
  mean =      3.476 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10768 
    [ 2.500,  5.000) = 258843 
    [ 5.000,  7.500) = 5693 
    [ 7.500, 10.000) = 829 
    [10.000, 12.500) = 157 
    [12.500, 15.000) = 74 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 37 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.368 ms/op
     p(50.0000) =      3.404 ms/op
     p(90.0000) =      4.182 ms/op
     p(95.0000) =      4.555 ms/op
     p(99.0000) =      5.874 ms/op
     p(99.9000) =     10.994 ms/op
     p(99.9900) =     22.544 ms/op
     p(99.9990) =     24.748 ms/op
     p(99.9999) =     24.773 ms/op
    p(100.0000) =     24.773 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 4.541 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.660 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.432 ±(99.9%) 0.008 ms/op
Iteration   1: 3.287 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.771 ms/op
                 existUser·p0.50:   3.228 ms/op
                 existUser·p0.90:   3.949 ms/op
                 existUser·p0.95:   4.219 ms/op
                 existUser·p0.99:   4.989 ms/op
                 existUser·p0.999:  9.361 ms/op
                 existUser·p0.9999: 16.245 ms/op
                 existUser·p1.00:   16.531 ms/op

Iteration   2: 3.272 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.471 ms/op
                 existUser·p0.50:   3.228 ms/op
                 existUser·p0.90:   3.908 ms/op
                 existUser·p0.95:   4.137 ms/op
                 existUser·p0.99:   5.038 ms/op
                 existUser·p0.999:  11.436 ms/op
                 existUser·p0.9999: 29.112 ms/op
                 existUser·p1.00:   29.426 ms/op

Iteration   3: 3.325 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.791 ms/op
                 existUser·p0.50:   3.269 ms/op
                 existUser·p0.90:   3.940 ms/op
                 existUser·p0.95:   4.243 ms/op
                 existUser·p0.99:   5.480 ms/op
                 existUser·p0.999:  9.355 ms/op
                 existUser·p0.9999: 20.197 ms/op
                 existUser·p1.00:   20.644 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 291533
  mean =      3.295 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13929 
    [ 2.500,  5.000) = 274208 
    [ 5.000,  7.500) = 2758 
    [ 7.500, 10.000) = 333 
    [10.000, 12.500) = 198 
    [12.500, 15.000) = 11 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.471 ms/op
     p(50.0000) =      3.244 ms/op
     p(90.0000) =      3.932 ms/op
     p(95.0000) =      4.194 ms/op
     p(99.0000) =      5.120 ms/op
     p(99.9000) =     10.306 ms/op
     p(99.9900) =     27.843 ms/op
     p(99.9990) =     29.330 ms/op
     p(99.9999) =     29.426 ms/op
    p(100.0000) =     29.426 ms/op


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
# Warmup Iteration   1: 4.620 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.563 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.425 ±(99.9%) 0.008 ms/op
Iteration   1: 3.373 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.937 ms/op
                 getUser·p0.50:   3.305 ms/op
                 getUser·p0.90:   3.944 ms/op
                 getUser·p0.95:   4.252 ms/op
                 getUser·p0.99:   5.584 ms/op
                 getUser·p0.999:  12.535 ms/op
                 getUser·p0.9999: 16.573 ms/op
                 getUser·p1.00:   17.302 ms/op

Iteration   2: 3.493 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.793 ms/op
                 getUser·p0.50:   3.424 ms/op
                 getUser·p0.90:   4.219 ms/op
                 getUser·p0.95:   4.522 ms/op
                 getUser·p0.99:   5.530 ms/op
                 getUser·p0.999:  12.319 ms/op
                 getUser·p0.9999: 17.400 ms/op
                 getUser·p1.00:   18.940 ms/op

Iteration   3: 3.587 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.984 ms/op
                 getUser·p0.50:   3.498 ms/op
                 getUser·p0.90:   4.227 ms/op
                 getUser·p0.95:   4.620 ms/op
                 getUser·p0.99:   6.275 ms/op
                 getUser·p0.999:  10.867 ms/op
                 getUser·p0.9999: 20.551 ms/op
                 getUser·p1.00:   21.856 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 275729
  mean =      3.482 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7798 
    [ 2.500,  5.000) = 261804 
    [ 5.000,  7.500) = 5115 
    [ 7.500, 10.000) = 634 
    [10.000, 12.500) = 138 
    [12.500, 15.000) = 133 
    [15.000, 17.500) = 72 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.793 ms/op
     p(50.0000) =      3.408 ms/op
     p(90.0000) =      4.145 ms/op
     p(95.0000) =      4.473 ms/op
     p(99.0000) =      5.784 ms/op
     p(99.9000) =     12.091 ms/op
     p(99.9900) =     20.049 ms/op
     p(99.9990) =     20.848 ms/op
     p(99.9999) =     21.856 ms/op
    p(100.0000) =     21.856 ms/op


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
# Warmup Iteration   1: 6.642 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 4.865 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.421 ±(99.9%) 0.014 ms/op
Iteration   1: 4.307 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.970 ms/op
                 listUser·p0.50:   4.153 ms/op
                 listUser·p0.90:   5.538 ms/op
                 listUser·p0.95:   6.332 ms/op
                 listUser·p0.99:   7.545 ms/op
                 listUser·p0.999:  16.564 ms/op
                 listUser·p0.9999: 20.007 ms/op
                 listUser·p1.00:   20.840 ms/op

Iteration   2: 4.357 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.292 ms/op
                 listUser·p0.50:   4.178 ms/op
                 listUser·p0.90:   5.554 ms/op
                 listUser·p0.95:   6.300 ms/op
                 listUser·p0.99:   7.831 ms/op
                 listUser·p0.999:  14.991 ms/op
                 listUser·p0.9999: 17.596 ms/op
                 listUser·p1.00:   18.121 ms/op

Iteration   3: 4.372 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   0.934 ms/op
                 listUser·p0.50:   4.162 ms/op
                 listUser·p0.90:   5.489 ms/op
                 listUser·p0.95:   6.267 ms/op
                 listUser·p0.99:   8.094 ms/op
                 listUser·p0.999:  22.610 ms/op
                 listUser·p0.9999: 25.257 ms/op
                 listUser·p1.00:   25.821 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 220760
  mean =      4.345 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1765 
    [ 2.500,  5.000) = 184189 
    [ 5.000,  7.500) = 31926 
    [ 7.500, 10.000) = 2213 
    [10.000, 12.500) = 215 
    [12.500, 15.000) = 149 
    [15.000, 17.500) = 163 
    [17.500, 20.000) = 37 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 68 
    [25.000, 27.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.934 ms/op
     p(50.0000) =      4.162 ms/op
     p(90.0000) =      5.530 ms/op
     p(95.0000) =      6.300 ms/op
     p(99.0000) =      7.766 ms/op
     p(99.9000) =     16.412 ms/op
     p(99.9900) =     24.475 ms/op
     p(99.9990) =     25.702 ms/op
     p(99.9999) =     25.821 ms/op
    p(100.0000) =     25.821 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.349 ± 1.472  ops/ms
ClientGrpc.existUser                       thrpt       3   9.163 ± 3.692  ops/ms
ClientGrpc.getUser                         thrpt       3   8.707 ± 4.449  ops/ms
ClientGrpc.listUser                        thrpt       3   6.656 ± 1.526  ops/ms
ClientGrpc.createUser                       avgt       3   3.573 ± 1.184   ms/op
ClientGrpc.existUser                        avgt       3   3.287 ± 0.605   ms/op
ClientGrpc.getUser                          avgt       3   3.485 ± 2.565   ms/op
ClientGrpc.listUser                         avgt       3   4.907 ± 6.388   ms/op
ClientGrpc.createUser                     sample  276483   3.476 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.368           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.404           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.182           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.555           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.874           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.994           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          22.544           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          24.773           ms/op
ClientGrpc.existUser                      sample  291533   3.295 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.471           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.244           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.932           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.194           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.120           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.306           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          27.843           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          29.426           ms/op
ClientGrpc.getUser                        sample  275729   3.482 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.793           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.408           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.145           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.473           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.784           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.091           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.049           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.856           ms/op
ClientGrpc.listUser                       sample  220760   4.345 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.934           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.162           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.530           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.300           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.766           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.412           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.475           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.821           ms/op
