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
# Warmup Iteration   1: 2.388 ops/ms
# Warmup Iteration   2: 5.563 ops/ms
# Warmup Iteration   3: 6.866 ops/ms
Iteration   1: 7.099 ops/ms
Iteration   2: 7.142 ops/ms
Iteration   3: 7.435 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.225 ±(99.9%) 3.335 ops/ms [Average]
  (min, avg, max) = (7.099, 7.225, 7.435), stdev = 0.183
  CI (99.9%): [3.891, 10.560] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 4.453 ops/ms
# Warmup Iteration   2: 7.302 ops/ms
# Warmup Iteration   3: 7.362 ops/ms
Iteration   1: 7.373 ops/ms
Iteration   2: 7.317 ops/ms
Iteration   3: 7.580 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.423 ±(99.9%) 2.533 ops/ms [Average]
  (min, avg, max) = (7.317, 7.423, 7.580), stdev = 0.139
  CI (99.9%): [4.890, 9.957] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 3.957 ops/ms
# Warmup Iteration   2: 6.491 ops/ms
# Warmup Iteration   3: 7.265 ops/ms
Iteration   1: 7.387 ops/ms
Iteration   2: 7.547 ops/ms
Iteration   3: 7.672 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.535 ±(99.9%) 2.601 ops/ms [Average]
  (min, avg, max) = (7.387, 7.535, 7.672), stdev = 0.143
  CI (99.9%): [4.934, 10.136] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 3.739 ops/ms
# Warmup Iteration   2: 5.403 ops/ms
# Warmup Iteration   3: 7.211 ops/ms
Iteration   1: 7.824 ops/ms
Iteration   2: 7.661 ops/ms
Iteration   3: 7.433 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.639 ±(99.9%) 3.585 ops/ms [Average]
  (min, avg, max) = (7.433, 7.639, 7.824), stdev = 0.197
  CI (99.9%): [4.054, 11.225] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 8.288 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 5.511 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 5.227 ±(99.9%) 0.014 ms/op
Iteration   1: 5.011 ±(99.9%) 0.001 ms/op
Iteration   2: 4.958 ±(99.9%) 0.005 ms/op
Iteration   3: 5.061 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  5.010 ±(99.9%) 0.938 ms/op [Average]
  (min, avg, max) = (4.958, 5.010, 5.061), stdev = 0.051
  CI (99.9%): [4.072, 5.948] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 6.932 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 5.134 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.904 ±(99.9%) 0.002 ms/op
Iteration   1: 4.607 ±(99.9%) 0.002 ms/op
Iteration   2: 4.737 ±(99.9%) 0.003 ms/op
Iteration   3: 4.439 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.594 ±(99.9%) 2.722 ms/op [Average]
  (min, avg, max) = (4.439, 4.594, 4.737), stdev = 0.149
  CI (99.9%): [1.872, 7.317] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 7.530 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 5.277 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 5.169 ±(99.9%) 0.003 ms/op
Iteration   1: 5.016 ±(99.9%) 0.002 ms/op
Iteration   2: 5.106 ±(99.9%) 0.002 ms/op
Iteration   3: 5.119 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  5.080 ±(99.9%) 1.025 ms/op [Average]
  (min, avg, max) = (5.016, 5.080, 5.119), stdev = 0.056
  CI (99.9%): [4.055, 6.105] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 11.014 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 6.676 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.830 ±(99.9%) 0.013 ms/op
Iteration   1: 5.630 ±(99.9%) 0.006 ms/op
Iteration   2: 5.510 ±(99.9%) 0.005 ms/op
Iteration   3: 5.610 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.584 ±(99.9%) 1.173 ms/op [Average]
  (min, avg, max) = (5.510, 5.584, 5.630), stdev = 0.064
  CI (99.9%): [4.410, 6.757] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 8.263 ±(99.9%) 0.120 ms/op
# Warmup Iteration   2: 5.393 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 4.916 ±(99.9%) 0.020 ms/op
Iteration   1: 5.018 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   1.272 ms/op
                 createUser·p0.50:   4.661 ms/op
                 createUser·p0.90:   6.824 ms/op
                 createUser·p0.95:   8.225 ms/op
                 createUser·p0.99:   11.043 ms/op
                 createUser·p0.999:  14.650 ms/op
                 createUser·p0.9999: 17.203 ms/op
                 createUser·p1.00:   17.498 ms/op

Iteration   2: 4.890 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   1.159 ms/op
                 createUser·p0.50:   4.596 ms/op
                 createUser·p0.90:   6.431 ms/op
                 createUser·p0.95:   7.512 ms/op
                 createUser·p0.99:   10.831 ms/op
                 createUser·p0.999:  15.444 ms/op
                 createUser·p0.9999: 27.437 ms/op
                 createUser·p1.00:   28.082 ms/op

Iteration   3: 4.872 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   0.698 ms/op
                 createUser·p0.50:   4.588 ms/op
                 createUser·p0.90:   6.431 ms/op
                 createUser·p0.95:   7.455 ms/op
                 createUser·p0.99:   10.453 ms/op
                 createUser·p0.999:  16.306 ms/op
                 createUser·p0.9999: 25.428 ms/op
                 createUser·p1.00:   25.559 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 194814
  mean =      4.926 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 726 
    [ 2.500,  5.000) = 122974 
    [ 5.000,  7.500) = 60119 
    [ 7.500, 10.000) = 7866 
    [10.000, 12.500) = 2478 
    [12.500, 15.000) = 457 
    [15.000, 17.500) = 112 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 34 

  Percentiles, ms/op:
      p(0.0000) =      0.698 ms/op
     p(50.0000) =      4.612 ms/op
     p(90.0000) =      6.554 ms/op
     p(95.0000) =      7.733 ms/op
     p(99.0000) =     10.797 ms/op
     p(99.9000) =     14.994 ms/op
     p(99.9900) =     26.674 ms/op
     p(99.9990) =     27.771 ms/op
     p(99.9999) =     28.082 ms/op
    p(100.0000) =     28.082 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 7.292 ±(99.9%) 0.102 ms/op
# Warmup Iteration   2: 5.030 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 4.873 ±(99.9%) 0.021 ms/op
Iteration   1: 4.725 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   1.085 ms/op
                 existUser·p0.50:   4.465 ms/op
                 existUser·p0.90:   6.218 ms/op
                 existUser·p0.95:   7.307 ms/op
                 existUser·p0.99:   10.207 ms/op
                 existUser·p0.999:  15.320 ms/op
                 existUser·p0.9999: 17.564 ms/op
                 existUser·p1.00:   18.612 ms/op

Iteration   2: 4.828 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   1.356 ms/op
                 existUser·p0.50:   4.465 ms/op
                 existUser·p0.90:   6.472 ms/op
                 existUser·p0.95:   8.061 ms/op
                 existUser·p0.99:   11.403 ms/op
                 existUser·p0.999:  15.499 ms/op
                 existUser·p0.9999: 20.681 ms/op
                 existUser·p1.00:   22.086 ms/op

Iteration   3: 4.699 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   1.071 ms/op
                 existUser·p0.50:   4.375 ms/op
                 existUser·p0.90:   6.406 ms/op
                 existUser·p0.95:   7.733 ms/op
                 existUser·p0.99:   10.611 ms/op
                 existUser·p0.999:  13.051 ms/op
                 existUser·p0.9999: 23.906 ms/op
                 existUser·p1.00:   24.379 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 202027
  mean =      4.750 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1531 
    [ 2.500,  5.000) = 138329 
    [ 5.000,  7.500) = 51157 
    [ 7.500, 10.000) = 7770 
    [10.000, 12.500) = 2560 
    [12.500, 15.000) = 484 
    [15.000, 17.500) = 123 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.071 ms/op
     p(50.0000) =      4.432 ms/op
     p(90.0000) =      6.357 ms/op
     p(95.0000) =      7.692 ms/op
     p(99.0000) =     10.764 ms/op
     p(99.9000) =     14.959 ms/op
     p(99.9900) =     22.970 ms/op
     p(99.9990) =     24.280 ms/op
     p(99.9999) =     24.379 ms/op
    p(100.0000) =     24.379 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 8.219 ±(99.9%) 0.118 ms/op
# Warmup Iteration   2: 5.691 ±(99.9%) 0.037 ms/op
# Warmup Iteration   3: 5.037 ±(99.9%) 0.022 ms/op
Iteration   1: 4.493 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   1.096 ms/op
                 getUser·p0.50:   4.108 ms/op
                 getUser·p0.90:   6.226 ms/op
                 getUser·p0.95:   7.881 ms/op
                 getUser·p0.99:   11.043 ms/op
                 getUser·p0.999:  14.776 ms/op
                 getUser·p0.9999: 18.641 ms/op
                 getUser·p1.00:   20.939 ms/op

Iteration   2: 4.260 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   0.997 ms/op
                 getUser·p0.50:   3.944 ms/op
                 getUser·p0.90:   5.759 ms/op
                 getUser·p0.95:   6.849 ms/op
                 getUser·p0.99:   9.847 ms/op
                 getUser·p0.999:  15.558 ms/op
                 getUser·p0.9999: 28.557 ms/op
                 getUser·p1.00:   33.948 ms/op

Iteration   3: 4.748 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   1.090 ms/op
                 getUser·p0.50:   4.440 ms/op
                 getUser·p0.90:   6.382 ms/op
                 getUser·p0.95:   7.496 ms/op
                 getUser·p0.99:   10.158 ms/op
                 getUser·p0.999:  14.265 ms/op
                 getUser·p0.9999: 21.317 ms/op
                 getUser·p1.00:   21.561 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 213574
  mean =      4.492 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2636 
    [ 2.500,  5.000) = 159632 
    [ 5.000,  7.500) = 41092 
    [ 7.500, 10.000) = 7517 
    [10.000, 12.500) = 2120 
    [12.500, 15.000) = 396 
    [15.000, 17.500) = 108 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 14 
    [27.500, 30.000) = 14 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 4 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.997 ms/op
     p(50.0000) =      4.153 ms/op
     p(90.0000) =      6.136 ms/op
     p(95.0000) =      7.406 ms/op
     p(99.0000) =     10.404 ms/op
     p(99.9000) =     14.678 ms/op
     p(99.9900) =     27.186 ms/op
     p(99.9990) =     33.768 ms/op
     p(99.9999) =     33.948 ms/op
    p(100.0000) =     33.948 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 9.648 ±(99.9%) 0.160 ms/op
# Warmup Iteration   2: 6.781 ±(99.9%) 0.043 ms/op
# Warmup Iteration   3: 5.943 ±(99.9%) 0.033 ms/op
Iteration   1: 5.428 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   2.216 ms/op
                 listUser·p0.50:   4.923 ms/op
                 listUser·p0.90:   7.586 ms/op
                 listUser·p0.95:   8.765 ms/op
                 listUser·p0.99:   12.304 ms/op
                 listUser·p0.999:  20.513 ms/op
                 listUser·p0.9999: 33.823 ms/op
                 listUser·p1.00:   34.144 ms/op

Iteration   2: 5.241 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   1.253 ms/op
                 listUser·p0.50:   4.751 ms/op
                 listUser·p0.90:   7.447 ms/op
                 listUser·p0.95:   8.929 ms/op
                 listUser·p0.99:   12.812 ms/op
                 listUser·p0.999:  22.869 ms/op
                 listUser·p0.9999: 25.941 ms/op
                 listUser·p1.00:   26.280 ms/op

Iteration   3: 5.696 ±(99.9%) 0.029 ms/op
                 listUser·p0.00:   1.749 ms/op
                 listUser·p0.50:   5.112 ms/op
                 listUser·p0.90:   8.053 ms/op
                 listUser·p0.95:   9.486 ms/op
                 listUser·p0.99:   13.763 ms/op
                 listUser·p0.999:  23.678 ms/op
                 listUser·p0.9999: 28.566 ms/op
                 listUser·p1.00:   34.013 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 176299
  mean =      5.449 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 137 
    [ 2.500,  5.000) = 92498 
    [ 5.000,  7.500) = 64204 
    [ 7.500, 10.000) = 13822 
    [10.000, 12.500) = 3504 
    [12.500, 15.000) = 1186 
    [15.000, 17.500) = 500 
    [17.500, 20.000) = 141 
    [20.000, 22.500) = 114 
    [22.500, 25.000) = 105 
    [25.000, 27.500) = 40 
    [27.500, 30.000) = 15 
    [30.000, 32.500) = 14 
    [32.500, 35.000) = 19 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.253 ms/op
     p(50.0000) =      4.932 ms/op
     p(90.0000) =      7.692 ms/op
     p(95.0000) =      9.060 ms/op
     p(99.0000) =     13.058 ms/op
     p(99.9000) =     22.829 ms/op
     p(99.9900) =     32.677 ms/op
     p(99.9990) =     34.144 ms/op
     p(99.9999) =     34.144 ms/op
    p(100.0000) =     34.144 ms/op


# Run complete. Total time: 00:13:16

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.225 ± 3.335  ops/ms
ClientGrpc.existUser                       thrpt       3   7.423 ± 2.533  ops/ms
ClientGrpc.getUser                         thrpt       3   7.535 ± 2.601  ops/ms
ClientGrpc.listUser                        thrpt       3   7.639 ± 3.585  ops/ms
ClientGrpc.createUser                       avgt       3   5.010 ± 0.938   ms/op
ClientGrpc.existUser                        avgt       3   4.594 ± 2.722   ms/op
ClientGrpc.getUser                          avgt       3   5.080 ± 1.025   ms/op
ClientGrpc.listUser                         avgt       3   5.584 ± 1.173   ms/op
ClientGrpc.createUser                     sample  194814   4.926 ± 0.011   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.698           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.612           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           6.554           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           7.733           ms/op
ClientGrpc.createUser:createUser·p0.99    sample          10.797           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          14.994           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          26.674           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          28.082           ms/op
ClientGrpc.existUser                      sample  202027   4.750 ± 0.011   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           1.071           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.432           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           6.357           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           7.692           ms/op
ClientGrpc.existUser:existUser·p0.99      sample          10.764           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          14.959           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          22.970           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          24.379           ms/op
ClientGrpc.getUser                        sample  213574   4.492 ± 0.011   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.997           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.153           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           6.136           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           7.406           ms/op
ClientGrpc.getUser:getUser·p0.99          sample          10.404           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          14.678           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          27.186           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          33.948           ms/op
ClientGrpc.listUser                       sample  176299   5.449 ± 0.016   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.253           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.932           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.692           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           9.060           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          13.058           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          22.829           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          32.677           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          34.144           ms/op
