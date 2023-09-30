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
# Warmup Iteration   1: 3.013 ops/ms
# Warmup Iteration   2: 6.490 ops/ms
# Warmup Iteration   3: 8.201 ops/ms
Iteration   1: 8.295 ops/ms
Iteration   2: 8.609 ops/ms
Iteration   3: 8.532 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.479 ±(99.9%) 2.990 ops/ms [Average]
  (min, avg, max) = (8.295, 8.479, 8.609), stdev = 0.164
  CI (99.9%): [5.489, 11.468] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 5.503 ops/ms
# Warmup Iteration   2: 8.341 ops/ms
# Warmup Iteration   3: 9.100 ops/ms
Iteration   1: 9.314 ops/ms
Iteration   2: 8.976 ops/ms
Iteration   3: 9.263 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.185 ±(99.9%) 3.322 ops/ms [Average]
  (min, avg, max) = (8.976, 9.185, 9.314), stdev = 0.182
  CI (99.9%): [5.862, 12.507] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 5.359 ops/ms
# Warmup Iteration   2: 8.014 ops/ms
# Warmup Iteration   3: 8.304 ops/ms
Iteration   1: 8.762 ops/ms
Iteration   2: 8.657 ops/ms
Iteration   3: 8.396 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.605 ±(99.9%) 3.435 ops/ms [Average]
  (min, avg, max) = (8.396, 8.605, 8.762), stdev = 0.188
  CI (99.9%): [5.170, 12.040] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 4.261 ops/ms
# Warmup Iteration   2: 6.299 ops/ms
# Warmup Iteration   3: 6.573 ops/ms
Iteration   1: 6.586 ops/ms
Iteration   2: 6.711 ops/ms
Iteration   3: 6.493 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.596 ±(99.9%) 1.997 ops/ms [Average]
  (min, avg, max) = (6.493, 6.596, 6.711), stdev = 0.109
  CI (99.9%): [4.599, 8.594] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 5.470 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 4.069 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.793 ±(99.9%) 0.005 ms/op
Iteration   1: 3.799 ±(99.9%) 0.004 ms/op
Iteration   2: 3.747 ±(99.9%) 0.006 ms/op
Iteration   3: 3.705 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.750 ±(99.9%) 0.864 ms/op [Average]
  (min, avg, max) = (3.705, 3.750, 3.799), stdev = 0.047
  CI (99.9%): [2.887, 4.614] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 5.162 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.780 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.616 ±(99.9%) 0.003 ms/op
Iteration   1: 3.594 ±(99.9%) 0.004 ms/op
Iteration   2: 3.451 ±(99.9%) 0.004 ms/op
Iteration   3: 3.616 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.554 ±(99.9%) 1.629 ms/op [Average]
  (min, avg, max) = (3.451, 3.554, 3.616), stdev = 0.089
  CI (99.9%): [1.925, 5.182] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 5.234 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.973 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.893 ±(99.9%) 0.005 ms/op
Iteration   1: 3.863 ±(99.9%) 0.003 ms/op
Iteration   2: 3.668 ±(99.9%) 0.008 ms/op
Iteration   3: 3.736 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.755 ±(99.9%) 1.805 ms/op [Average]
  (min, avg, max) = (3.668, 3.755, 3.863), stdev = 0.099
  CI (99.9%): [1.950, 5.561] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 6.468 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 5.138 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.901 ±(99.9%) 0.018 ms/op
Iteration   1: 4.765 ±(99.9%) 0.013 ms/op
Iteration   2: 4.760 ±(99.9%) 0.013 ms/op
Iteration   3: 4.626 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.717 ±(99.9%) 1.442 ms/op [Average]
  (min, avg, max) = (4.626, 4.717, 4.765), stdev = 0.079
  CI (99.9%): [3.275, 6.159] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 5.772 ±(99.9%) 0.061 ms/op
# Warmup Iteration   2: 3.861 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.851 ±(99.9%) 0.011 ms/op
Iteration   1: 3.728 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.991 ms/op
                 createUser·p0.50:   3.645 ms/op
                 createUser·p0.90:   4.399 ms/op
                 createUser·p0.95:   4.727 ms/op
                 createUser·p0.99:   6.473 ms/op
                 createUser·p0.999:  12.115 ms/op
                 createUser·p0.9999: 15.604 ms/op
                 createUser·p1.00:   16.302 ms/op

Iteration   2: 3.635 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.871 ms/op
                 createUser·p0.50:   3.592 ms/op
                 createUser·p0.90:   4.309 ms/op
                 createUser·p0.95:   4.719 ms/op
                 createUser·p0.99:   6.332 ms/op
                 createUser·p0.999:  9.572 ms/op
                 createUser·p0.9999: 16.184 ms/op
                 createUser·p1.00:   17.891 ms/op

Iteration   3: 3.720 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.913 ms/op
                 createUser·p0.50:   3.633 ms/op
                 createUser·p0.90:   4.391 ms/op
                 createUser·p0.95:   4.784 ms/op
                 createUser·p0.99:   6.578 ms/op
                 createUser·p0.999:  18.348 ms/op
                 createUser·p0.9999: 23.999 ms/op
                 createUser·p1.00:   27.984 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 259826
  mean =      3.694 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8624 
    [ 2.500,  5.000) = 242150 
    [ 5.000,  7.500) = 7472 
    [ 7.500, 10.000) = 1083 
    [10.000, 12.500) = 204 
    [12.500, 15.000) = 126 
    [15.000, 17.500) = 56 
    [17.500, 20.000) = 55 
    [20.000, 22.500) = 39 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.871 ms/op
     p(50.0000) =      3.621 ms/op
     p(90.0000) =      4.375 ms/op
     p(95.0000) =      4.743 ms/op
     p(99.0000) =      6.455 ms/op
     p(99.9000) =     13.083 ms/op
     p(99.9900) =     21.169 ms/op
     p(99.9990) =     26.246 ms/op
     p(99.9999) =     27.984 ms/op
    p(100.0000) =     27.984 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.314 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.699 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.608 ±(99.9%) 0.008 ms/op
Iteration   1: 3.565 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.816 ms/op
                 existUser·p0.50:   3.510 ms/op
                 existUser·p0.90:   4.276 ms/op
                 existUser·p0.95:   4.620 ms/op
                 existUser·p0.99:   5.906 ms/op
                 existUser·p0.999:  8.824 ms/op
                 existUser·p0.9999: 21.496 ms/op
                 existUser·p1.00:   26.870 ms/op

Iteration   2: 3.616 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.762 ms/op
                 existUser·p0.50:   3.531 ms/op
                 existUser·p0.90:   4.284 ms/op
                 existUser·p0.95:   4.628 ms/op
                 existUser·p0.99:   6.242 ms/op
                 existUser·p0.999:  14.209 ms/op
                 existUser·p0.9999: 17.475 ms/op
                 existUser·p1.00:   19.431 ms/op

Iteration   3: 3.514 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.849 ms/op
                 existUser·p0.50:   3.453 ms/op
                 existUser·p0.90:   4.071 ms/op
                 existUser·p0.95:   4.415 ms/op
                 existUser·p0.99:   5.710 ms/op
                 existUser·p0.999:  13.121 ms/op
                 existUser·p0.9999: 17.357 ms/op
                 existUser·p1.00:   18.252 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 269412
  mean =      3.564 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8854 
    [ 2.500,  5.000) = 253743 
    [ 5.000,  7.500) = 5822 
    [ 7.500, 10.000) = 665 
    [10.000, 12.500) = 93 
    [12.500, 15.000) = 118 
    [15.000, 17.500) = 85 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.762 ms/op
     p(50.0000) =      3.494 ms/op
     p(90.0000) =      4.227 ms/op
     p(95.0000) =      4.563 ms/op
     p(99.0000) =      5.939 ms/op
     p(99.9000) =     11.420 ms/op
     p(99.9900) =     17.961 ms/op
     p(99.9990) =     26.870 ms/op
     p(99.9999) =     26.870 ms/op
    p(100.0000) =     26.870 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.386 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 3.948 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.797 ±(99.9%) 0.010 ms/op
Iteration   1: 3.776 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.812 ms/op
                 getUser·p0.50:   3.711 ms/op
                 getUser·p0.90:   4.465 ms/op
                 getUser·p0.95:   4.751 ms/op
                 getUser·p0.99:   6.128 ms/op
                 getUser·p0.999:  10.795 ms/op
                 getUser·p0.9999: 23.597 ms/op
                 getUser·p1.00:   26.116 ms/op

Iteration   2: 3.694 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.772 ms/op
                 getUser·p0.50:   3.650 ms/op
                 getUser·p0.90:   4.448 ms/op
                 getUser·p0.95:   4.809 ms/op
                 getUser·p0.99:   6.021 ms/op
                 getUser·p0.999:  9.568 ms/op
                 getUser·p0.9999: 24.533 ms/op
                 getUser·p1.00:   24.969 ms/op

Iteration   3: 3.815 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.879 ms/op
                 getUser·p0.50:   3.707 ms/op
                 getUser·p0.90:   4.604 ms/op
                 getUser·p0.95:   4.956 ms/op
                 getUser·p0.99:   6.881 ms/op
                 getUser·p0.999:  16.088 ms/op
                 getUser·p0.9999: 31.195 ms/op
                 getUser·p1.00:   32.178 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 255133
  mean =      3.761 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8700 
    [ 2.500,  5.000) = 236720 
    [ 5.000,  7.500) = 8308 
    [ 7.500, 10.000) = 1004 
    [10.000, 12.500) = 193 
    [12.500, 15.000) = 7 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 42 
    [22.500, 25.000) = 51 
    [25.000, 27.500) = 36 
    [27.500, 30.000) = 7 
    [30.000, 32.500) = 24 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.772 ms/op
     p(50.0000) =      3.690 ms/op
     p(90.0000) =      4.506 ms/op
     p(95.0000) =      4.841 ms/op
     p(99.0000) =      6.283 ms/op
     p(99.9000) =     11.567 ms/op
     p(99.9900) =     29.949 ms/op
     p(99.9990) =     32.127 ms/op
     p(99.9999) =     32.178 ms/op
    p(100.0000) =     32.178 ms/op


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
# Warmup Iteration   1: 6.792 ±(99.9%) 0.085 ms/op
# Warmup Iteration   2: 5.169 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.928 ±(99.9%) 0.017 ms/op
Iteration   1: 4.922 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.366 ms/op
                 listUser·p0.50:   4.653 ms/op
                 listUser·p0.90:   6.586 ms/op
                 listUser·p0.95:   7.487 ms/op
                 listUser·p0.99:   9.193 ms/op
                 listUser·p0.999:  18.675 ms/op
                 listUser·p0.9999: 29.753 ms/op
                 listUser·p1.00:   30.179 ms/op

Iteration   2: 4.962 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.001 ms/op
                 listUser·p0.50:   4.620 ms/op
                 listUser·p0.90:   6.857 ms/op
                 listUser·p0.95:   7.692 ms/op
                 listUser·p0.99:   9.339 ms/op
                 listUser·p0.999:  20.584 ms/op
                 listUser·p0.9999: 26.331 ms/op
                 listUser·p1.00:   26.345 ms/op

Iteration   3: 4.906 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.092 ms/op
                 listUser·p0.50:   4.588 ms/op
                 listUser·p0.90:   6.709 ms/op
                 listUser·p0.95:   7.610 ms/op
                 listUser·p0.99:   9.617 ms/op
                 listUser·p0.999:  21.680 ms/op
                 listUser·p0.9999: 35.717 ms/op
                 listUser·p1.00:   37.552 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 194825
  mean =      4.930 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 640 
    [ 2.500,  5.000) = 132516 
    [ 5.000,  7.500) = 50867 
    [ 7.500, 10.000) = 9442 
    [10.000, 12.500) = 831 
    [12.500, 15.000) = 179 
    [15.000, 17.500) = 56 
    [17.500, 20.000) = 72 
    [20.000, 22.500) = 100 
    [22.500, 25.000) = 46 
    [25.000, 27.500) = 12 
    [27.500, 30.000) = 30 
    [30.000, 32.500) = 11 
    [32.500, 35.000) = 14 
    [35.000, 37.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      1.001 ms/op
     p(50.0000) =      4.620 ms/op
     p(90.0000) =      6.717 ms/op
     p(95.0000) =      7.602 ms/op
     p(99.0000) =      9.372 ms/op
     p(99.9000) =     20.715 ms/op
     p(99.9900) =     32.702 ms/op
     p(99.9990) =     36.185 ms/op
     p(99.9999) =     37.552 ms/op
    p(100.0000) =     37.552 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.479 ± 2.990  ops/ms
ClientGrpc.existUser                       thrpt       3   9.185 ± 3.322  ops/ms
ClientGrpc.getUser                         thrpt       3   8.605 ± 3.435  ops/ms
ClientGrpc.listUser                        thrpt       3   6.596 ± 1.997  ops/ms
ClientGrpc.createUser                       avgt       3   3.750 ± 0.864   ms/op
ClientGrpc.existUser                        avgt       3   3.554 ± 1.629   ms/op
ClientGrpc.getUser                          avgt       3   3.755 ± 1.805   ms/op
ClientGrpc.listUser                         avgt       3   4.717 ± 1.442   ms/op
ClientGrpc.createUser                     sample  259826   3.694 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.871           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.621           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.375           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.743           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.455           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.083           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.169           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          27.984           ms/op
ClientGrpc.existUser                      sample  269412   3.564 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.762           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.494           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.227           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.563           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.939           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.420           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.961           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          26.870           ms/op
ClientGrpc.getUser                        sample  255133   3.761 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.772           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.690           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.506           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.841           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.283           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.567           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          29.949           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          32.178           ms/op
ClientGrpc.listUser                       sample  194825   4.930 ± 0.011   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.001           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.620           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.717           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.602           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.372           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          20.715           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          32.702           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          37.552           ms/op
