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
# Warmup Iteration   1: 3.199 ops/ms
# Warmup Iteration   2: 7.072 ops/ms
# Warmup Iteration   3: 7.939 ops/ms
Iteration   1: 8.240 ops/ms
Iteration   2: 8.570 ops/ms
Iteration   3: 8.640 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.483 ±(99.9%) 3.903 ops/ms [Average]
  (min, avg, max) = (8.240, 8.483, 8.640), stdev = 0.214
  CI (99.9%): [4.580, 12.386] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 5.881 ops/ms
# Warmup Iteration   2: 8.379 ops/ms
# Warmup Iteration   3: 8.788 ops/ms
Iteration   1: 8.874 ops/ms
Iteration   2: 9.140 ops/ms
Iteration   3: 9.370 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.128 ±(99.9%) 4.520 ops/ms [Average]
  (min, avg, max) = (8.874, 9.128, 9.370), stdev = 0.248
  CI (99.9%): [4.608, 13.648] (assumes normal distribution)


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
# Warmup Iteration   1: 5.045 ops/ms
# Warmup Iteration   2: 7.953 ops/ms
# Warmup Iteration   3: 8.414 ops/ms
Iteration   1: 8.606 ops/ms
Iteration   2: 8.789 ops/ms
Iteration   3: 8.798 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.731 ±(99.9%) 1.973 ops/ms [Average]
  (min, avg, max) = (8.606, 8.731, 8.798), stdev = 0.108
  CI (99.9%): [6.758, 10.704] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 4.082 ops/ms
# Warmup Iteration   2: 6.500 ops/ms
# Warmup Iteration   3: 6.801 ops/ms
Iteration   1: 6.751 ops/ms
Iteration   2: 6.871 ops/ms
Iteration   3: 6.862 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.828 ±(99.9%) 1.218 ops/ms [Average]
  (min, avg, max) = (6.751, 6.828, 6.871), stdev = 0.067
  CI (99.9%): [5.610, 8.046] (assumes normal distribution)


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
# Warmup Iteration   1: 5.311 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.896 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.747 ±(99.9%) 0.028 ms/op
Iteration   1: 3.715 ±(99.9%) 0.004 ms/op
Iteration   2: 3.620 ±(99.9%) 0.002 ms/op
Iteration   3: 3.598 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.644 ±(99.9%) 1.139 ms/op [Average]
  (min, avg, max) = (3.598, 3.644, 3.715), stdev = 0.062
  CI (99.9%): [2.505, 4.784] (assumes normal distribution)


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
# Warmup Iteration   1: 4.824 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.641 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.568 ±(99.9%) 0.002 ms/op
Iteration   1: 3.473 ±(99.9%) 0.004 ms/op
Iteration   2: 3.365 ±(99.9%) 0.003 ms/op
Iteration   3: 3.443 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.427 ±(99.9%) 1.021 ms/op [Average]
  (min, avg, max) = (3.365, 3.427, 3.473), stdev = 0.056
  CI (99.9%): [2.406, 4.448] (assumes normal distribution)


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
# Warmup Iteration   1: 5.087 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.846 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.666 ±(99.9%) 0.004 ms/op
Iteration   1: 3.637 ±(99.9%) 0.003 ms/op
Iteration   2: 3.681 ±(99.9%) 0.003 ms/op
Iteration   3: 3.702 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.673 ±(99.9%) 0.605 ms/op [Average]
  (min, avg, max) = (3.637, 3.673, 3.702), stdev = 0.033
  CI (99.9%): [3.068, 4.279] (assumes normal distribution)


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
# Warmup Iteration   1: 6.876 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.933 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.792 ±(99.9%) 0.024 ms/op
Iteration   1: 4.686 ±(99.9%) 0.019 ms/op
Iteration   2: 4.717 ±(99.9%) 0.021 ms/op
Iteration   3: 4.646 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.683 ±(99.9%) 0.646 ms/op [Average]
  (min, avg, max) = (4.646, 4.683, 4.717), stdev = 0.035
  CI (99.9%): [4.037, 5.329] (assumes normal distribution)


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
# Warmup Iteration   1: 5.323 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 3.937 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.613 ±(99.9%) 0.008 ms/op
Iteration   1: 3.631 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.956 ms/op
                 createUser·p0.50:   3.568 ms/op
                 createUser·p0.90:   4.276 ms/op
                 createUser·p0.95:   4.555 ms/op
                 createUser·p0.99:   5.759 ms/op
                 createUser·p0.999:  11.023 ms/op
                 createUser·p0.9999: 19.104 ms/op
                 createUser·p1.00:   20.087 ms/op

Iteration   2: 3.684 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.937 ms/op
                 createUser·p0.50:   3.621 ms/op
                 createUser·p0.90:   4.350 ms/op
                 createUser·p0.95:   4.604 ms/op
                 createUser·p0.99:   5.800 ms/op
                 createUser·p0.999:  10.751 ms/op
                 createUser·p0.9999: 19.813 ms/op
                 createUser·p1.00:   20.611 ms/op

Iteration   3: 3.640 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.966 ms/op
                 createUser·p0.50:   3.580 ms/op
                 createUser·p0.90:   4.202 ms/op
                 createUser·p0.95:   4.473 ms/op
                 createUser·p0.99:   5.448 ms/op
                 createUser·p0.999:  11.192 ms/op
                 createUser·p0.9999: 26.575 ms/op
                 createUser·p1.00:   27.132 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 262720
  mean =      3.652 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4492 
    [ 2.500,  5.000) = 253108 
    [ 5.000,  7.500) = 4317 
    [ 7.500, 10.000) = 460 
    [10.000, 12.500) = 150 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 94 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 49 

  Percentiles, ms/op:
      p(0.0000) =      0.937 ms/op
     p(50.0000) =      3.588 ms/op
     p(90.0000) =      4.284 ms/op
     p(95.0000) =      4.555 ms/op
     p(99.0000) =      5.693 ms/op
     p(99.9000) =     10.895 ms/op
     p(99.9900) =     26.426 ms/op
     p(99.9990) =     27.001 ms/op
     p(99.9999) =     27.132 ms/op
    p(100.0000) =     27.132 ms/op


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
# Warmup Iteration   1: 4.901 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.538 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.519 ±(99.9%) 0.007 ms/op
Iteration   1: 3.465 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.867 ms/op
                 existUser·p0.50:   3.424 ms/op
                 existUser·p0.90:   4.063 ms/op
                 existUser·p0.95:   4.334 ms/op
                 existUser·p0.99:   5.389 ms/op
                 existUser·p0.999:  7.955 ms/op
                 existUser·p0.9999: 14.943 ms/op
                 existUser·p1.00:   15.221 ms/op

Iteration   2: 3.503 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.770 ms/op
                 existUser·p0.50:   3.445 ms/op
                 existUser·p0.90:   3.990 ms/op
                 existUser·p0.95:   4.291 ms/op
                 existUser·p0.99:   5.616 ms/op
                 existUser·p0.999:  11.924 ms/op
                 existUser·p0.9999: 21.529 ms/op
                 existUser·p1.00:   21.692 ms/op

Iteration   3: 3.452 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.017 ms/op
                 existUser·p0.50:   3.437 ms/op
                 existUser·p0.90:   3.891 ms/op
                 existUser·p0.95:   4.112 ms/op
                 existUser·p0.99:   4.948 ms/op
                 existUser·p0.999:  6.521 ms/op
                 existUser·p0.9999: 18.594 ms/op
                 existUser·p1.00:   18.973 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 276534
  mean =      3.473 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6352 
    [ 2.500,  5.000) = 266325 
    [ 5.000,  7.500) = 3330 
    [ 7.500, 10.000) = 353 
    [10.000, 12.500) = 42 
    [12.500, 15.000) = 34 
    [15.000, 17.500) = 52 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.770 ms/op
     p(50.0000) =      3.437 ms/op
     p(90.0000) =      3.977 ms/op
     p(95.0000) =      4.260 ms/op
     p(99.0000) =      5.333 ms/op
     p(99.9000) =      8.798 ms/op
     p(99.9900) =     20.426 ms/op
     p(99.9990) =     21.594 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.305 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.867 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.726 ±(99.9%) 0.010 ms/op
Iteration   1: 3.709 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.957 ms/op
                 getUser·p0.50:   3.654 ms/op
                 getUser·p0.90:   4.465 ms/op
                 getUser·p0.95:   4.817 ms/op
                 getUser·p0.99:   6.103 ms/op
                 getUser·p0.999:  13.630 ms/op
                 getUser·p0.9999: 17.482 ms/op
                 getUser·p1.00:   19.366 ms/op

Iteration   2: 3.789 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.114 ms/op
                 getUser·p0.50:   3.731 ms/op
                 getUser·p0.90:   4.522 ms/op
                 getUser·p0.95:   4.760 ms/op
                 getUser·p0.99:   5.792 ms/op
                 getUser·p0.999:  10.735 ms/op
                 getUser·p0.9999: 16.828 ms/op
                 getUser·p1.00:   17.465 ms/op

Iteration   3: 3.684 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.722 ms/op
                 getUser·p0.50:   3.617 ms/op
                 getUser·p0.90:   4.317 ms/op
                 getUser·p0.95:   4.579 ms/op
                 getUser·p0.99:   5.661 ms/op
                 getUser·p0.999:  10.489 ms/op
                 getUser·p0.9999: 27.415 ms/op
                 getUser·p1.00:   27.787 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 257414
  mean =      3.727 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6873 
    [ 2.500,  5.000) = 243277 
    [ 5.000,  7.500) = 6373 
    [ 7.500, 10.000) = 549 
    [10.000, 12.500) = 141 
    [12.500, 15.000) = 80 
    [15.000, 17.500) = 49 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 26 

  Percentiles, ms/op:
      p(0.0000) =      0.722 ms/op
     p(50.0000) =      3.662 ms/op
     p(90.0000) =      4.448 ms/op
     p(95.0000) =      4.727 ms/op
     p(99.0000) =      5.857 ms/op
     p(99.9000) =     11.207 ms/op
     p(99.9900) =     25.273 ms/op
     p(99.9990) =     27.717 ms/op
     p(99.9999) =     27.787 ms/op
    p(100.0000) =     27.787 ms/op


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
# Warmup Iteration   1: 6.636 ±(99.9%) 0.067 ms/op
# Warmup Iteration   2: 5.139 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.873 ±(99.9%) 0.015 ms/op
Iteration   1: 4.837 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   0.921 ms/op
                 listUser·p0.50:   4.596 ms/op
                 listUser·p0.90:   6.259 ms/op
                 listUser·p0.95:   7.012 ms/op
                 listUser·p0.99:   8.765 ms/op
                 listUser·p0.999:  14.545 ms/op
                 listUser·p0.9999: 18.703 ms/op
                 listUser·p1.00:   19.137 ms/op

Iteration   2: 4.880 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.274 ms/op
                 listUser·p0.50:   4.702 ms/op
                 listUser·p0.90:   5.890 ms/op
                 listUser·p0.95:   6.554 ms/op
                 listUser·p0.99:   8.514 ms/op
                 listUser·p0.999:  19.611 ms/op
                 listUser·p0.9999: 29.145 ms/op
                 listUser·p1.00:   29.590 ms/op

Iteration   3: 4.875 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.124 ms/op
                 listUser·p0.50:   4.628 ms/op
                 listUser·p0.90:   6.128 ms/op
                 listUser·p0.95:   7.094 ms/op
                 listUser·p0.99:   9.306 ms/op
                 listUser·p0.999:  21.063 ms/op
                 listUser·p0.9999: 25.358 ms/op
                 listUser·p1.00:   26.214 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 197342
  mean =      4.864 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 211 
    [ 2.500,  5.000) = 138944 
    [ 5.000,  7.500) = 52237 
    [ 7.500, 10.000) = 4908 
    [10.000, 12.500) = 631 
    [12.500, 15.000) = 172 
    [15.000, 17.500) = 44 
    [17.500, 20.000) = 65 
    [20.000, 22.500) = 43 
    [22.500, 25.000) = 45 
    [25.000, 27.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      0.921 ms/op
     p(50.0000) =      4.645 ms/op
     p(90.0000) =      6.087 ms/op
     p(95.0000) =      6.914 ms/op
     p(99.0000) =      8.929 ms/op
     p(99.9000) =     16.591 ms/op
     p(99.9900) =     28.403 ms/op
     p(99.9990) =     29.462 ms/op
     p(99.9999) =     29.590 ms/op
    p(100.0000) =     29.590 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.483 ± 3.903  ops/ms
ClientGrpc.existUser                       thrpt       3   9.128 ± 4.520  ops/ms
ClientGrpc.getUser                         thrpt       3   8.731 ± 1.973  ops/ms
ClientGrpc.listUser                        thrpt       3   6.828 ± 1.218  ops/ms
ClientGrpc.createUser                       avgt       3   3.644 ± 1.139   ms/op
ClientGrpc.existUser                        avgt       3   3.427 ± 1.021   ms/op
ClientGrpc.getUser                          avgt       3   3.673 ± 0.605   ms/op
ClientGrpc.listUser                         avgt       3   4.683 ± 0.646   ms/op
ClientGrpc.createUser                     sample  262720   3.652 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.937           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.588           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.284           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.555           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.693           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.895           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          26.426           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          27.132           ms/op
ClientGrpc.existUser                      sample  276534   3.473 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.770           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.437           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.977           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.260           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.333           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.798           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.426           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.692           ms/op
ClientGrpc.getUser                        sample  257414   3.727 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.722           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.662           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.448           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.727           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.857           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.207           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          25.273           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          27.787           ms/op
ClientGrpc.listUser                       sample  197342   4.864 ± 0.009   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.921           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.645           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.087           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.914           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.929           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.591           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          28.403           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          29.590           ms/op
