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
# Warmup Iteration   1: 3.140 ops/ms
# Warmup Iteration   2: 6.670 ops/ms
# Warmup Iteration   3: 8.073 ops/ms
Iteration   1: 8.495 ops/ms
Iteration   2: 8.546 ops/ms
Iteration   3: 8.933 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.658 ±(99.9%) 4.363 ops/ms [Average]
  (min, avg, max) = (8.495, 8.658, 8.933), stdev = 0.239
  CI (99.9%): [4.295, 13.021] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:04
# Fork: 1 of 1
# Warmup Iteration   1: 6.014 ops/ms
# Warmup Iteration   2: 8.758 ops/ms
# Warmup Iteration   3: 9.217 ops/ms
Iteration   1: 9.265 ops/ms
Iteration   2: 9.323 ops/ms
Iteration   3: 9.187 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.258 ±(99.9%) 1.246 ops/ms [Average]
  (min, avg, max) = (9.187, 9.258, 9.323), stdev = 0.068
  CI (99.9%): [8.012, 10.504] (assumes normal distribution)


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
# Warmup Iteration   1: 5.162 ops/ms
# Warmup Iteration   2: 8.249 ops/ms
# Warmup Iteration   3: 8.629 ops/ms
Iteration   1: 8.737 ops/ms
Iteration   2: 8.834 ops/ms
Iteration   3: 8.773 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.781 ±(99.9%) 0.897 ops/ms [Average]
  (min, avg, max) = (8.737, 8.781, 8.834), stdev = 0.049
  CI (99.9%): [7.884, 9.678] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 4.013 ops/ms
# Warmup Iteration   2: 6.124 ops/ms
# Warmup Iteration   3: 6.474 ops/ms
Iteration   1: 6.666 ops/ms
Iteration   2: 6.609 ops/ms
Iteration   3: 6.692 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.656 ±(99.9%) 0.776 ops/ms [Average]
  (min, avg, max) = (6.609, 6.656, 6.692), stdev = 0.043
  CI (99.9%): [5.880, 7.431] (assumes normal distribution)


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
# Warmup Iteration   1: 5.658 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.842 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.737 ±(99.9%) 0.024 ms/op
Iteration   1: 3.647 ±(99.9%) 0.004 ms/op
Iteration   2: 3.662 ±(99.9%) 0.004 ms/op
Iteration   3: 3.632 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.647 ±(99.9%) 0.276 ms/op [Average]
  (min, avg, max) = (3.632, 3.647, 3.662), stdev = 0.015
  CI (99.9%): [3.371, 3.922] (assumes normal distribution)


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
# Warmup Iteration   1: 5.117 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.675 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.437 ±(99.9%) 0.004 ms/op
Iteration   1: 3.419 ±(99.9%) 0.004 ms/op
Iteration   2: 3.449 ±(99.9%) 0.002 ms/op
Iteration   3: 3.455 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.441 ±(99.9%) 0.348 ms/op [Average]
  (min, avg, max) = (3.419, 3.441, 3.455), stdev = 0.019
  CI (99.9%): [3.093, 3.789] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 5.286 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.741 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.667 ±(99.9%) 0.003 ms/op
Iteration   1: 3.666 ±(99.9%) 0.003 ms/op
Iteration   2: 3.529 ±(99.9%) 0.006 ms/op
Iteration   3: 3.641 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.612 ±(99.9%) 1.329 ms/op [Average]
  (min, avg, max) = (3.529, 3.612, 3.666), stdev = 0.073
  CI (99.9%): [2.283, 4.942] (assumes normal distribution)


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
# Warmup Iteration   1: 6.553 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 5.233 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.827 ±(99.9%) 0.018 ms/op
Iteration   1: 4.741 ±(99.9%) 0.018 ms/op
Iteration   2: 4.726 ±(99.9%) 0.014 ms/op
Iteration   3: 4.723 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.730 ±(99.9%) 0.172 ms/op [Average]
  (min, avg, max) = (4.723, 4.730, 4.741), stdev = 0.009
  CI (99.9%): [4.558, 4.902] (assumes normal distribution)


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
# Warmup Iteration   1: 5.403 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 3.883 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.679 ±(99.9%) 0.009 ms/op
Iteration   1: 3.613 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.738 ms/op
                 createUser·p0.50:   3.592 ms/op
                 createUser·p0.90:   4.170 ms/op
                 createUser·p0.95:   4.497 ms/op
                 createUser·p0.99:   5.825 ms/op
                 createUser·p0.999:  11.622 ms/op
                 createUser·p0.9999: 33.948 ms/op
                 createUser·p1.00:   34.144 ms/op

Iteration   2: 3.609 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.777 ms/op
                 createUser·p0.50:   3.592 ms/op
                 createUser·p0.90:   4.202 ms/op
                 createUser·p0.95:   4.481 ms/op
                 createUser·p0.99:   5.538 ms/op
                 createUser·p0.999:  9.333 ms/op
                 createUser·p0.9999: 20.808 ms/op
                 createUser·p1.00:   21.496 ms/op

Iteration   3: 3.648 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.918 ms/op
                 createUser·p0.50:   3.584 ms/op
                 createUser·p0.90:   4.243 ms/op
                 createUser·p0.95:   4.563 ms/op
                 createUser·p0.99:   5.677 ms/op
                 createUser·p0.999:  13.517 ms/op
                 createUser·p0.9999: 24.412 ms/op
                 createUser·p1.00:   24.707 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 264879
  mean =      3.624 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8394 
    [ 2.500,  5.000) = 250991 
    [ 5.000,  7.500) = 4520 
    [ 7.500, 10.000) = 635 
    [10.000, 12.500) = 115 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 43 
    [22.500, 25.000) = 80 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 32 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.738 ms/op
     p(50.0000) =      3.588 ms/op
     p(90.0000) =      4.202 ms/op
     p(95.0000) =      4.514 ms/op
     p(99.0000) =      5.693 ms/op
     p(99.9000) =     11.176 ms/op
     p(99.9900) =     33.473 ms/op
     p(99.9990) =     34.079 ms/op
     p(99.9999) =     34.144 ms/op
    p(100.0000) =     34.144 ms/op


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
# Warmup Iteration   1: 5.033 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.702 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.523 ±(99.9%) 0.007 ms/op
Iteration   1: 3.547 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.944 ms/op
                 existUser·p0.50:   3.482 ms/op
                 existUser·p0.90:   4.166 ms/op
                 existUser·p0.95:   4.415 ms/op
                 existUser·p0.99:   5.489 ms/op
                 existUser·p0.999:  11.302 ms/op
                 existUser·p0.9999: 24.576 ms/op
                 existUser·p1.00:   27.296 ms/op

Iteration   2: 3.436 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.972 ms/op
                 existUser·p0.50:   3.445 ms/op
                 existUser·p0.90:   3.990 ms/op
                 existUser·p0.95:   4.350 ms/op
                 existUser·p0.99:   5.579 ms/op
                 existUser·p0.999:  8.270 ms/op
                 existUser·p0.9999: 14.239 ms/op
                 existUser·p1.00:   15.892 ms/op

Iteration   3: 3.540 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.808 ms/op
                 existUser·p0.50:   3.510 ms/op
                 existUser·p0.90:   4.092 ms/op
                 existUser·p0.95:   4.309 ms/op
                 existUser·p0.99:   4.973 ms/op
                 existUser·p0.999:  8.940 ms/op
                 existUser·p0.9999: 18.480 ms/op
                 existUser·p1.00:   18.973 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 273707
  mean =      3.507 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8666 
    [ 2.500,  5.000) = 261070 
    [ 5.000,  7.500) = 3180 
    [ 7.500, 10.000) = 601 
    [10.000, 12.500) = 62 
    [12.500, 15.000) = 57 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.808 ms/op
     p(50.0000) =      3.478 ms/op
     p(90.0000) =      4.089 ms/op
     p(95.0000) =      4.358 ms/op
     p(99.0000) =      5.431 ms/op
     p(99.9000) =      9.103 ms/op
     p(99.9900) =     19.839 ms/op
     p(99.9990) =     25.052 ms/op
     p(99.9999) =     27.296 ms/op
    p(100.0000) =     27.296 ms/op


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
# Warmup Iteration   1: 4.933 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.835 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.614 ±(99.9%) 0.008 ms/op
Iteration   1: 3.631 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.866 ms/op
                 getUser·p0.50:   3.576 ms/op
                 getUser·p0.90:   4.125 ms/op
                 getUser·p0.95:   4.407 ms/op
                 getUser·p0.99:   5.546 ms/op
                 getUser·p0.999:  10.533 ms/op
                 getUser·p0.9999: 14.391 ms/op
                 getUser·p1.00:   14.533 ms/op

Iteration   2: 3.578 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.696 ms/op
                 getUser·p0.50:   3.531 ms/op
                 getUser·p0.90:   4.153 ms/op
                 getUser·p0.95:   4.497 ms/op
                 getUser·p0.99:   5.833 ms/op
                 getUser·p0.999:  10.898 ms/op
                 getUser·p0.9999: 19.152 ms/op
                 getUser·p1.00:   19.759 ms/op

Iteration   3: 3.559 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.806 ms/op
                 getUser·p0.50:   3.547 ms/op
                 getUser·p0.90:   3.965 ms/op
                 getUser·p0.95:   4.219 ms/op
                 getUser·p0.99:   4.940 ms/op
                 getUser·p0.999:  8.200 ms/op
                 getUser·p0.9999: 19.235 ms/op
                 getUser·p1.00:   19.726 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 267525
  mean =      3.589 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 134 
    [ 1.250,  2.500) = 5257 
    [ 2.500,  3.750) = 181796 
    [ 3.750,  5.000) = 76050 
    [ 5.000,  6.250) = 2845 
    [ 6.250,  7.500) = 605 
    [ 7.500,  8.750) = 406 
    [ 8.750, 10.000) = 144 
    [10.000, 11.250) = 128 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 8 
    [13.750, 15.000) = 34 
    [15.000, 16.250) = 17 
    [16.250, 17.500) = 12 
    [17.500, 18.750) = 29 

  Percentiles, ms/op:
      p(0.0000) =      0.696 ms/op
     p(50.0000) =      3.551 ms/op
     p(90.0000) =      4.080 ms/op
     p(95.0000) =      4.375 ms/op
     p(99.0000) =      5.554 ms/op
     p(99.9000) =     10.076 ms/op
     p(99.9900) =     18.907 ms/op
     p(99.9990) =     19.737 ms/op
     p(99.9999) =     19.759 ms/op
    p(100.0000) =     19.759 ms/op


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
# Warmup Iteration   1: 7.081 ±(99.9%) 0.079 ms/op
# Warmup Iteration   2: 4.872 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.757 ±(99.9%) 0.013 ms/op
Iteration   1: 4.720 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.556 ms/op
                 listUser·p0.50:   4.555 ms/op
                 listUser·p0.90:   5.652 ms/op
                 listUser·p0.95:   6.636 ms/op
                 listUser·p0.99:   8.274 ms/op
                 listUser·p0.999:  15.783 ms/op
                 listUser·p0.9999: 21.929 ms/op
                 listUser·p1.00:   23.298 ms/op

Iteration   2: 4.627 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.219 ms/op
                 listUser·p0.50:   4.407 ms/op
                 listUser·p0.90:   5.735 ms/op
                 listUser·p0.95:   6.619 ms/op
                 listUser·p0.99:   8.438 ms/op
                 listUser·p0.999:  18.507 ms/op
                 listUser·p0.9999: 22.908 ms/op
                 listUser·p1.00:   23.527 ms/op

Iteration   3: 4.629 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   0.793 ms/op
                 listUser·p0.50:   4.489 ms/op
                 listUser·p0.90:   5.349 ms/op
                 listUser·p0.95:   6.300 ms/op
                 listUser·p0.99:   8.004 ms/op
                 listUser·p0.999:  20.768 ms/op
                 listUser·p0.9999: 29.232 ms/op
                 listUser·p1.00:   31.097 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 205951
  mean =      4.658 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 247 
    [ 2.500,  5.000) = 168240 
    [ 5.000,  7.500) = 32847 
    [ 7.500, 10.000) = 3949 
    [10.000, 12.500) = 300 
    [12.500, 15.000) = 51 
    [15.000, 17.500) = 88 
    [17.500, 20.000) = 91 
    [20.000, 22.500) = 62 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 28 
    [27.500, 30.000) = 34 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.793 ms/op
     p(50.0000) =      4.481 ms/op
     p(90.0000) =      5.579 ms/op
     p(95.0000) =      6.529 ms/op
     p(99.0000) =      8.225 ms/op
     p(99.9000) =     18.057 ms/op
     p(99.9900) =     28.622 ms/op
     p(99.9990) =     30.472 ms/op
     p(99.9999) =     31.097 ms/op
    p(100.0000) =     31.097 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.658 ± 4.363  ops/ms
ClientGrpc.existUser                       thrpt       3   9.258 ± 1.246  ops/ms
ClientGrpc.getUser                         thrpt       3   8.781 ± 0.897  ops/ms
ClientGrpc.listUser                        thrpt       3   6.656 ± 0.776  ops/ms
ClientGrpc.createUser                       avgt       3   3.647 ± 0.276   ms/op
ClientGrpc.existUser                        avgt       3   3.441 ± 0.348   ms/op
ClientGrpc.getUser                          avgt       3   3.612 ± 1.329   ms/op
ClientGrpc.listUser                         avgt       3   4.730 ± 0.172   ms/op
ClientGrpc.createUser                     sample  264879   3.624 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.738           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.588           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.202           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.514           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.693           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.176           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          33.473           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          34.144           ms/op
ClientGrpc.existUser                      sample  273707   3.507 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.808           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.478           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.089           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.358           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.431           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.103           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.839           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          27.296           ms/op
ClientGrpc.getUser                        sample  267525   3.589 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.696           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.551           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.080           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.375           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.554           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.076           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.907           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.759           ms/op
ClientGrpc.listUser                       sample  205951   4.658 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.793           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.481           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.579           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.529           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.225           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.057           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          28.622           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          31.097           ms/op
