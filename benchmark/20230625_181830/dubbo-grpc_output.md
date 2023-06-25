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
# Warmup Iteration   1: 3.094 ops/ms
# Warmup Iteration   2: 6.928 ops/ms
# Warmup Iteration   3: 8.180 ops/ms
Iteration   1: 8.905 ops/ms
Iteration   2: 8.612 ops/ms
Iteration   3: 8.804 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.774 ±(99.9%) 2.713 ops/ms [Average]
  (min, avg, max) = (8.612, 8.774, 8.905), stdev = 0.149
  CI (99.9%): [6.061, 11.487] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 5.762 ops/ms
# Warmup Iteration   2: 8.537 ops/ms
# Warmup Iteration   3: 9.051 ops/ms
Iteration   1: 9.068 ops/ms
Iteration   2: 9.317 ops/ms
Iteration   3: 9.181 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.189 ±(99.9%) 2.276 ops/ms [Average]
  (min, avg, max) = (9.068, 9.189, 9.317), stdev = 0.125
  CI (99.9%): [6.913, 11.464] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 5.575 ops/ms
# Warmup Iteration   2: 8.244 ops/ms
# Warmup Iteration   3: 8.644 ops/ms
Iteration   1: 9.090 ops/ms
Iteration   2: 9.153 ops/ms
Iteration   3: 9.142 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.128 ±(99.9%) 0.610 ops/ms [Average]
  (min, avg, max) = (9.090, 9.128, 9.153), stdev = 0.033
  CI (99.9%): [8.518, 9.738] (assumes normal distribution)


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
# Warmup Iteration   1: 4.207 ops/ms
# Warmup Iteration   2: 6.299 ops/ms
# Warmup Iteration   3: 6.559 ops/ms
Iteration   1: 6.735 ops/ms
Iteration   2: 6.537 ops/ms
Iteration   3: 6.563 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.612 ±(99.9%) 1.965 ops/ms [Average]
  (min, avg, max) = (6.537, 6.612, 6.735), stdev = 0.108
  CI (99.9%): [4.647, 8.577] (assumes normal distribution)


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
# Warmup Iteration   1: 5.295 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.861 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 3.764 ±(99.9%) 0.004 ms/op
Iteration   1: 3.620 ±(99.9%) 0.004 ms/op
Iteration   2: 3.598 ±(99.9%) 0.004 ms/op
Iteration   3: 3.621 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.613 ±(99.9%) 0.242 ms/op [Average]
  (min, avg, max) = (3.598, 3.613, 3.621), stdev = 0.013
  CI (99.9%): [3.371, 3.855] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 4.998 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.747 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.529 ±(99.9%) 0.003 ms/op
Iteration   1: 3.519 ±(99.9%) 0.004 ms/op
Iteration   2: 3.522 ±(99.9%) 0.002 ms/op
Iteration   3: 3.548 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.529 ±(99.9%) 0.288 ms/op [Average]
  (min, avg, max) = (3.519, 3.529, 3.548), stdev = 0.016
  CI (99.9%): [3.242, 3.817] (assumes normal distribution)


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
# Warmup Iteration   1: 5.075 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.990 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.854 ±(99.9%) 0.004 ms/op
Iteration   1: 3.780 ±(99.9%) 0.004 ms/op
Iteration   2: 3.596 ±(99.9%) 0.004 ms/op
Iteration   3: 3.664 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.680 ±(99.9%) 1.703 ms/op [Average]
  (min, avg, max) = (3.596, 3.680, 3.780), stdev = 0.093
  CI (99.9%): [1.977, 5.383] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 6.875 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 5.018 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.834 ±(99.9%) 0.019 ms/op
Iteration   1: 4.714 ±(99.9%) 0.010 ms/op
Iteration   2: 4.855 ±(99.9%) 0.017 ms/op
Iteration   3: 4.759 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.776 ±(99.9%) 1.313 ms/op [Average]
  (min, avg, max) = (4.714, 4.776, 4.855), stdev = 0.072
  CI (99.9%): [3.463, 6.089] (assumes normal distribution)


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
# Warmup Iteration   1: 5.536 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 4.026 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.693 ±(99.9%) 0.009 ms/op
Iteration   1: 3.638 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.912 ms/op
                 createUser·p0.50:   3.576 ms/op
                 createUser·p0.90:   4.309 ms/op
                 createUser·p0.95:   4.678 ms/op
                 createUser·p0.99:   6.038 ms/op
                 createUser·p0.999:  10.947 ms/op
                 createUser·p0.9999: 17.370 ms/op
                 createUser·p1.00:   19.202 ms/op

Iteration   2: 3.631 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.048 ms/op
                 createUser·p0.50:   3.568 ms/op
                 createUser·p0.90:   4.186 ms/op
                 createUser·p0.95:   4.481 ms/op
                 createUser·p0.99:   5.498 ms/op
                 createUser·p0.999:  9.334 ms/op
                 createUser·p0.9999: 25.178 ms/op
                 createUser·p1.00:   25.526 ms/op

Iteration   3: 3.653 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.806 ms/op
                 createUser·p0.50:   3.568 ms/op
                 createUser·p0.90:   4.301 ms/op
                 createUser·p0.95:   4.686 ms/op
                 createUser·p0.99:   5.571 ms/op
                 createUser·p0.999:  9.264 ms/op
                 createUser·p0.9999: 22.659 ms/op
                 createUser·p1.00:   23.134 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 263448
  mean =      3.641 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4462 
    [ 2.500,  5.000) = 252977 
    [ 5.000,  7.500) = 5320 
    [ 7.500, 10.000) = 436 
    [10.000, 12.500) = 54 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 64 
    [17.500, 20.000) = 35 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 34 
    [25.000, 27.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      0.806 ms/op
     p(50.0000) =      3.572 ms/op
     p(90.0000) =      4.260 ms/op
     p(95.0000) =      4.620 ms/op
     p(99.0000) =      5.685 ms/op
     p(99.9000) =      9.619 ms/op
     p(99.9900) =     24.313 ms/op
     p(99.9990) =     25.473 ms/op
     p(99.9999) =     25.526 ms/op
    p(100.0000) =     25.526 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 5.054 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.614 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.483 ±(99.9%) 0.007 ms/op
Iteration   1: 3.530 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.745 ms/op
                 existUser·p0.50:   3.482 ms/op
                 existUser·p0.90:   4.145 ms/op
                 existUser·p0.95:   4.342 ms/op
                 existUser·p0.99:   5.358 ms/op
                 existUser·p0.999:  8.487 ms/op
                 existUser·p0.9999: 14.646 ms/op
                 existUser·p1.00:   14.746 ms/op

Iteration   2: 3.499 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.829 ms/op
                 existUser·p0.50:   3.428 ms/op
                 existUser·p0.90:   4.071 ms/op
                 existUser·p0.95:   4.391 ms/op
                 existUser·p0.99:   5.612 ms/op
                 existUser·p0.999:  11.689 ms/op
                 existUser·p0.9999: 26.303 ms/op
                 existUser·p1.00:   26.739 ms/op

Iteration   3: 3.381 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.894 ms/op
                 existUser·p0.50:   3.367 ms/op
                 existUser·p0.90:   3.957 ms/op
                 existUser·p0.95:   4.227 ms/op
                 existUser·p0.99:   5.292 ms/op
                 existUser·p0.999:  12.206 ms/op
                 existUser·p0.9999: 20.972 ms/op
                 existUser·p1.00:   21.168 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 276813
  mean =      3.469 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9649 
    [ 2.500,  5.000) = 262453 
    [ 5.000,  7.500) = 4014 
    [ 7.500, 10.000) = 366 
    [10.000, 12.500) = 149 
    [12.500, 15.000) = 88 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 26 

  Percentiles, ms/op:
      p(0.0000) =      0.745 ms/op
     p(50.0000) =      3.424 ms/op
     p(90.0000) =      4.071 ms/op
     p(95.0000) =      4.317 ms/op
     p(99.0000) =      5.448 ms/op
     p(99.9000) =     10.636 ms/op
     p(99.9900) =     24.892 ms/op
     p(99.9990) =     26.598 ms/op
     p(99.9999) =     26.739 ms/op
    p(100.0000) =     26.739 ms/op


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
# Warmup Iteration   1: 5.453 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 3.838 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.652 ±(99.9%) 0.008 ms/op
Iteration   1: 3.645 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.667 ms/op
                 getUser·p0.50:   3.588 ms/op
                 getUser·p0.90:   4.399 ms/op
                 getUser·p0.95:   4.817 ms/op
                 getUser·p0.99:   5.898 ms/op
                 getUser·p0.999:  9.372 ms/op
                 getUser·p0.9999: 13.934 ms/op
                 getUser·p1.00:   15.696 ms/op

Iteration   2: 3.580 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.364 ms/op
                 getUser·p0.50:   3.539 ms/op
                 getUser·p0.90:   4.018 ms/op
                 getUser·p0.95:   4.317 ms/op
                 getUser·p0.99:   5.505 ms/op
                 getUser·p0.999:  8.045 ms/op
                 getUser·p0.9999: 14.715 ms/op
                 getUser·p1.00:   15.909 ms/op

Iteration   3: 3.662 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.891 ms/op
                 getUser·p0.50:   3.596 ms/op
                 getUser·p0.90:   4.407 ms/op
                 getUser·p0.95:   4.760 ms/op
                 getUser·p0.99:   5.857 ms/op
                 getUser·p0.999:  12.485 ms/op
                 getUser·p0.9999: 21.382 ms/op
                 getUser·p1.00:   21.823 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 264520
  mean =      3.629 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7782 
    [ 2.500,  5.000) = 249195 
    [ 5.000,  7.500) = 6969 
    [ 7.500, 10.000) = 374 
    [10.000, 12.500) = 40 
    [12.500, 15.000) = 94 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 34 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.364 ms/op
     p(50.0000) =      3.572 ms/op
     p(90.0000) =      4.284 ms/op
     p(95.0000) =      4.678 ms/op
     p(99.0000) =      5.792 ms/op
     p(99.9000) =      9.159 ms/op
     p(99.9900) =     19.956 ms/op
     p(99.9990) =     21.737 ms/op
     p(99.9999) =     21.823 ms/op
    p(100.0000) =     21.823 ms/op


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
# Warmup Iteration   1: 5.945 ±(99.9%) 0.061 ms/op
# Warmup Iteration   2: 5.176 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.736 ±(99.9%) 0.013 ms/op
Iteration   1: 4.722 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.022 ms/op
                 listUser·p0.50:   4.522 ms/op
                 listUser·p0.90:   5.833 ms/op
                 listUser·p0.95:   6.644 ms/op
                 listUser·p0.99:   8.618 ms/op
                 listUser·p0.999:  15.771 ms/op
                 listUser·p0.9999: 22.552 ms/op
                 listUser·p1.00:   25.952 ms/op

Iteration   2: 4.707 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.489 ms/op
                 listUser·p0.50:   4.522 ms/op
                 listUser·p0.90:   5.743 ms/op
                 listUser·p0.95:   6.783 ms/op
                 listUser·p0.99:   8.405 ms/op
                 listUser·p0.999:  18.778 ms/op
                 listUser·p0.9999: 20.742 ms/op
                 listUser·p1.00:   20.939 ms/op

Iteration   3: 4.712 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.021 ms/op
                 listUser·p0.50:   4.563 ms/op
                 listUser·p0.90:   5.480 ms/op
                 listUser·p0.95:   6.690 ms/op
                 listUser·p0.99:   8.143 ms/op
                 listUser·p0.999:  20.588 ms/op
                 listUser·p0.9999: 28.485 ms/op
                 listUser·p1.00:   29.262 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 203502
  mean =      4.714 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 343 
    [ 2.500,  5.000) = 160435 
    [ 5.000,  7.500) = 37970 
    [ 7.500, 10.000) = 4094 
    [10.000, 12.500) = 306 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 56 
    [17.500, 20.000) = 93 
    [20.000, 22.500) = 69 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 47 

  Percentiles, ms/op:
      p(0.0000) =      1.021 ms/op
     p(50.0000) =      4.538 ms/op
     p(90.0000) =      5.702 ms/op
     p(95.0000) =      6.709 ms/op
     p(99.0000) =      8.372 ms/op
     p(99.9000) =     18.301 ms/op
     p(99.9900) =     27.132 ms/op
     p(99.9990) =     29.157 ms/op
     p(99.9999) =     29.262 ms/op
    p(100.0000) =     29.262 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.774 ± 2.713  ops/ms
ClientGrpc.existUser                       thrpt       3   9.189 ± 2.276  ops/ms
ClientGrpc.getUser                         thrpt       3   9.128 ± 0.610  ops/ms
ClientGrpc.listUser                        thrpt       3   6.612 ± 1.965  ops/ms
ClientGrpc.createUser                       avgt       3   3.613 ± 0.242   ms/op
ClientGrpc.existUser                        avgt       3   3.529 ± 0.288   ms/op
ClientGrpc.getUser                          avgt       3   3.680 ± 1.703   ms/op
ClientGrpc.listUser                         avgt       3   4.776 ± 1.313   ms/op
ClientGrpc.createUser                     sample  263448   3.641 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.806           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.572           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.260           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.620           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.685           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.619           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          24.313           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          25.526           ms/op
ClientGrpc.existUser                      sample  276813   3.469 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.745           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.424           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.071           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.317           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.448           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.636           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          24.892           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          26.739           ms/op
ClientGrpc.getUser                        sample  264520   3.629 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.364           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.572           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.284           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.678           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.792           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.159           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.956           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.823           ms/op
ClientGrpc.listUser                       sample  203502   4.714 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.021           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.538           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.702           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.709           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.372           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.301           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          27.132           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          29.262           ms/op
