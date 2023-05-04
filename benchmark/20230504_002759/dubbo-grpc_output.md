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
# Warmup Iteration   1: 3.027 ops/ms
# Warmup Iteration   2: 6.772 ops/ms
# Warmup Iteration   3: 8.229 ops/ms
Iteration   1: 8.502 ops/ms
Iteration   2: 8.771 ops/ms
Iteration   3: 8.828 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.700 ±(99.9%) 3.173 ops/ms [Average]
  (min, avg, max) = (8.502, 8.700, 8.828), stdev = 0.174
  CI (99.9%): [5.528, 11.873] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 5.959 ops/ms
# Warmup Iteration   2: 8.822 ops/ms
# Warmup Iteration   3: 8.974 ops/ms
Iteration   1: 9.232 ops/ms
Iteration   2: 9.129 ops/ms
Iteration   3: 9.209 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.190 ±(99.9%) 0.993 ops/ms [Average]
  (min, avg, max) = (9.129, 9.190, 9.232), stdev = 0.054
  CI (99.9%): [8.197, 10.183] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 5.914 ops/ms
# Warmup Iteration   2: 7.846 ops/ms
# Warmup Iteration   3: 8.517 ops/ms
Iteration   1: 8.807 ops/ms
Iteration   2: 8.756 ops/ms
Iteration   3: 8.653 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.739 ±(99.9%) 1.432 ops/ms [Average]
  (min, avg, max) = (8.653, 8.739, 8.807), stdev = 0.078
  CI (99.9%): [7.307, 10.171] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 4.445 ops/ms
# Warmup Iteration   2: 6.347 ops/ms
# Warmup Iteration   3: 6.789 ops/ms
Iteration   1: 7.003 ops/ms
Iteration   2: 6.830 ops/ms
Iteration   3: 6.841 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.891 ±(99.9%) 1.764 ops/ms [Average]
  (min, avg, max) = (6.830, 6.891, 7.003), stdev = 0.097
  CI (99.9%): [5.127, 8.655] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 5.454 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.790 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.727 ±(99.9%) 0.021 ms/op
Iteration   1: 3.626 ±(99.9%) 0.003 ms/op
Iteration   2: 3.630 ±(99.9%) 0.004 ms/op
Iteration   3: 3.590 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.616 ±(99.9%) 0.408 ms/op [Average]
  (min, avg, max) = (3.590, 3.616, 3.630), stdev = 0.022
  CI (99.9%): [3.208, 4.023] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 4.854 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.597 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.447 ±(99.9%) 0.003 ms/op
Iteration   1: 3.476 ±(99.9%) 0.004 ms/op
Iteration   2: 3.458 ±(99.9%) 0.003 ms/op
Iteration   3: 3.492 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.476 ±(99.9%) 0.309 ms/op [Average]
  (min, avg, max) = (3.458, 3.476, 3.492), stdev = 0.017
  CI (99.9%): [3.167, 3.784] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 5.464 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.803 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.688 ±(99.9%) 0.005 ms/op
Iteration   1: 3.606 ±(99.9%) 0.003 ms/op
Iteration   2: 3.617 ±(99.9%) 0.004 ms/op
Iteration   3: 3.563 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.595 ±(99.9%) 0.519 ms/op [Average]
  (min, avg, max) = (3.563, 3.595, 3.617), stdev = 0.028
  CI (99.9%): [3.076, 4.115] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 6.782 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.950 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.696 ±(99.9%) 0.014 ms/op
Iteration   1: 4.654 ±(99.9%) 0.022 ms/op
Iteration   2: 4.663 ±(99.9%) 0.008 ms/op
Iteration   3: 4.723 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.680 ±(99.9%) 0.680 ms/op [Average]
  (min, avg, max) = (4.654, 4.680, 4.723), stdev = 0.037
  CI (99.9%): [4.000, 5.360] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 5.241 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 3.918 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.662 ±(99.9%) 0.009 ms/op
Iteration   1: 3.648 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.861 ms/op
                 createUser·p0.50:   3.592 ms/op
                 createUser·p0.90:   4.317 ms/op
                 createUser·p0.95:   4.612 ms/op
                 createUser·p0.99:   5.267 ms/op
                 createUser·p0.999:  8.438 ms/op
                 createUser·p0.9999: 28.064 ms/op
                 createUser·p1.00:   28.443 ms/op

Iteration   2: 3.534 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.904 ms/op
                 createUser·p0.50:   3.531 ms/op
                 createUser·p0.90:   4.080 ms/op
                 createUser·p0.95:   4.342 ms/op
                 createUser·p0.99:   5.389 ms/op
                 createUser·p0.999:  7.928 ms/op
                 createUser·p0.9999: 22.129 ms/op
                 createUser·p1.00:   22.741 ms/op

Iteration   3: 3.582 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.983 ms/op
                 createUser·p0.50:   3.535 ms/op
                 createUser·p0.90:   4.055 ms/op
                 createUser·p0.95:   4.342 ms/op
                 createUser·p0.99:   5.022 ms/op
                 createUser·p0.999:  21.061 ms/op
                 createUser·p0.9999: 26.575 ms/op
                 createUser·p1.00:   26.608 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 267594
  mean =      3.587 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7587 
    [ 2.500,  5.000) = 256241 
    [ 5.000,  7.500) = 3237 
    [ 7.500, 10.000) = 235 
    [10.000, 12.500) = 38 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 59 
    [20.000, 22.500) = 70 
    [22.500, 25.000) = 45 
    [25.000, 27.500) = 35 

  Percentiles, ms/op:
      p(0.0000) =      0.861 ms/op
     p(50.0000) =      3.551 ms/op
     p(90.0000) =      4.149 ms/op
     p(95.0000) =      4.448 ms/op
     p(99.0000) =      5.251 ms/op
     p(99.9000) =     11.833 ms/op
     p(99.9900) =     26.051 ms/op
     p(99.9990) =     28.289 ms/op
     p(99.9999) =     28.443 ms/op
    p(100.0000) =     28.443 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 4.589 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.747 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.442 ±(99.9%) 0.007 ms/op
Iteration   1: 3.453 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.973 ms/op
                 existUser·p0.50:   3.465 ms/op
                 existUser·p0.90:   3.965 ms/op
                 existUser·p0.95:   4.235 ms/op
                 existUser·p0.99:   5.259 ms/op
                 existUser·p0.999:  8.277 ms/op
                 existUser·p0.9999: 16.682 ms/op
                 existUser·p1.00:   16.876 ms/op

Iteration   2: 3.435 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.987 ms/op
                 existUser·p0.50:   3.432 ms/op
                 existUser·p0.90:   3.830 ms/op
                 existUser·p0.95:   3.940 ms/op
                 existUser·p0.99:   4.555 ms/op
                 existUser·p0.999:  6.865 ms/op
                 existUser·p0.9999: 15.969 ms/op
                 existUser·p1.00:   16.187 ms/op

Iteration   3: 3.406 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.861 ms/op
                 existUser·p0.50:   3.428 ms/op
                 existUser·p0.90:   3.899 ms/op
                 existUser·p0.95:   4.121 ms/op
                 existUser·p0.99:   4.891 ms/op
                 existUser·p0.999:  7.250 ms/op
                 existUser·p0.9999: 20.021 ms/op
                 existUser·p1.00:   20.808 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 279614
  mean =      3.431 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10265 
    [ 2.500,  5.000) = 266990 
    [ 5.000,  7.500) = 2088 
    [ 7.500, 10.000) = 111 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 2 
    [15.000, 17.500) = 96 
    [17.500, 20.000) = 52 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.861 ms/op
     p(50.0000) =      3.441 ms/op
     p(90.0000) =      3.891 ms/op
     p(95.0000) =      4.092 ms/op
     p(99.0000) =      4.891 ms/op
     p(99.9000) =      7.466 ms/op
     p(99.9900) =     19.169 ms/op
     p(99.9990) =     20.441 ms/op
     p(99.9999) =     20.808 ms/op
    p(100.0000) =     20.808 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.515 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 3.909 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.702 ±(99.9%) 0.009 ms/op
Iteration   1: 3.636 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.935 ms/op
                 getUser·p0.50:   3.600 ms/op
                 getUser·p0.90:   4.342 ms/op
                 getUser·p0.95:   4.661 ms/op
                 getUser·p0.99:   6.005 ms/op
                 getUser·p0.999:  10.077 ms/op
                 getUser·p0.9999: 15.060 ms/op
                 getUser·p1.00:   15.434 ms/op

Iteration   2: 3.670 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.141 ms/op
                 getUser·p0.50:   3.633 ms/op
                 getUser·p0.90:   4.268 ms/op
                 getUser·p0.95:   4.473 ms/op
                 getUser·p0.99:   5.325 ms/op
                 getUser·p0.999:  9.372 ms/op
                 getUser·p0.9999: 17.334 ms/op
                 getUser·p1.00:   17.367 ms/op

Iteration   3: 3.585 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.849 ms/op
                 getUser·p0.50:   3.568 ms/op
                 getUser·p0.90:   4.104 ms/op
                 getUser·p0.95:   4.391 ms/op
                 getUser·p0.99:   5.407 ms/op
                 getUser·p0.999:  8.520 ms/op
                 getUser·p0.9999: 19.016 ms/op
                 getUser·p1.00:   19.726 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 264299
  mean =      3.630 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 123 
    [ 1.250,  2.500) = 8411 
    [ 2.500,  3.750) = 159351 
    [ 3.750,  5.000) = 91525 
    [ 5.000,  6.250) = 3431 
    [ 6.250,  7.500) = 864 
    [ 7.500,  8.750) = 295 
    [ 8.750, 10.000) = 72 
    [10.000, 11.250) = 42 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 23 
    [13.750, 15.000) = 33 
    [15.000, 16.250) = 44 
    [16.250, 17.500) = 43 
    [17.500, 18.750) = 28 

  Percentiles, ms/op:
      p(0.0000) =      0.849 ms/op
     p(50.0000) =      3.596 ms/op
     p(90.0000) =      4.252 ms/op
     p(95.0000) =      4.514 ms/op
     p(99.0000) =      5.677 ms/op
     p(99.9000) =      9.149 ms/op
     p(99.9900) =     18.514 ms/op
     p(99.9990) =     19.511 ms/op
     p(99.9999) =     19.726 ms/op
    p(100.0000) =     19.726 ms/op


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
# Warmup Iteration   1: 5.688 ±(99.9%) 0.066 ms/op
# Warmup Iteration   2: 5.189 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.835 ±(99.9%) 0.016 ms/op
Iteration   1: 4.515 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   0.800 ms/op
                 listUser·p0.50:   4.309 ms/op
                 listUser·p0.90:   5.743 ms/op
                 listUser·p0.95:   6.726 ms/op
                 listUser·p0.99:   8.331 ms/op
                 listUser·p0.999:  15.188 ms/op
                 listUser·p0.9999: 19.333 ms/op
                 listUser·p1.00:   22.282 ms/op

Iteration   2: 4.701 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   0.933 ms/op
                 listUser·p0.50:   4.497 ms/op
                 listUser·p0.90:   5.898 ms/op
                 listUser·p0.95:   6.570 ms/op
                 listUser·p0.99:   8.135 ms/op
                 listUser·p0.999:  18.054 ms/op
                 listUser·p0.9999: 26.153 ms/op
                 listUser·p1.00:   27.165 ms/op

Iteration   3: 4.614 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.233 ms/op
                 listUser·p0.50:   4.497 ms/op
                 listUser·p0.90:   5.153 ms/op
                 listUser·p0.95:   5.857 ms/op
                 listUser·p0.99:   7.922 ms/op
                 listUser·p0.999:  20.840 ms/op
                 listUser·p0.9999: 28.543 ms/op
                 listUser·p1.00:   29.065 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 208129
  mean =      4.608 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 498 
    [ 2.500,  5.000) = 170641 
    [ 5.000,  7.500) = 32897 
    [ 7.500, 10.000) = 3500 
    [10.000, 12.500) = 171 
    [12.500, 15.000) = 109 
    [15.000, 17.500) = 61 
    [17.500, 20.000) = 129 
    [20.000, 22.500) = 48 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 27 

  Percentiles, ms/op:
      p(0.0000) =      0.800 ms/op
     p(50.0000) =      4.440 ms/op
     p(90.0000) =      5.603 ms/op
     p(95.0000) =      6.463 ms/op
     p(99.0000) =      8.151 ms/op
     p(99.9000) =     18.186 ms/op
     p(99.9900) =     27.007 ms/op
     p(99.9990) =     28.954 ms/op
     p(99.9999) =     29.065 ms/op
    p(100.0000) =     29.065 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.700 ± 3.173  ops/ms
ClientGrpc.existUser                       thrpt       3   9.190 ± 0.993  ops/ms
ClientGrpc.getUser                         thrpt       3   8.739 ± 1.432  ops/ms
ClientGrpc.listUser                        thrpt       3   6.891 ± 1.764  ops/ms
ClientGrpc.createUser                       avgt       3   3.616 ± 0.408   ms/op
ClientGrpc.existUser                        avgt       3   3.476 ± 0.309   ms/op
ClientGrpc.getUser                          avgt       3   3.595 ± 0.519   ms/op
ClientGrpc.listUser                         avgt       3   4.680 ± 0.680   ms/op
ClientGrpc.createUser                     sample  267594   3.587 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.861           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.551           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.149           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.448           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.251           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.833           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          26.051           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          28.443           ms/op
ClientGrpc.existUser                      sample  279614   3.431 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.861           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.441           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.891           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.092           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.891           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.466           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.169           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.808           ms/op
ClientGrpc.getUser                        sample  264299   3.630 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.849           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.596           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.252           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.514           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.677           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.149           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.514           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.726           ms/op
ClientGrpc.listUser                       sample  208129   4.608 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.800           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.440           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.603           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.463           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.151           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.186           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          27.007           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          29.065           ms/op
