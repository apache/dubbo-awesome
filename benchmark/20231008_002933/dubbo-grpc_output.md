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
# Warmup Iteration   1: 3.433 ops/ms
# Warmup Iteration   2: 7.371 ops/ms
# Warmup Iteration   3: 8.502 ops/ms
Iteration   1: 8.648 ops/ms
Iteration   2: 8.841 ops/ms
Iteration   3: 8.951 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.813 ±(99.9%) 2.799 ops/ms [Average]
  (min, avg, max) = (8.648, 8.813, 8.951), stdev = 0.153
  CI (99.9%): [6.014, 11.613] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 6.533 ops/ms
# Warmup Iteration   2: 8.882 ops/ms
# Warmup Iteration   3: 8.955 ops/ms
Iteration   1: 9.068 ops/ms
Iteration   2: 9.273 ops/ms
Iteration   3: 9.535 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.292 ±(99.9%) 4.275 ops/ms [Average]
  (min, avg, max) = (9.068, 9.292, 9.535), stdev = 0.234
  CI (99.9%): [5.017, 13.567] (assumes normal distribution)


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
# Warmup Iteration   1: 5.875 ops/ms
# Warmup Iteration   2: 8.493 ops/ms
# Warmup Iteration   3: 8.911 ops/ms
Iteration   1: 8.963 ops/ms
Iteration   2: 9.048 ops/ms
Iteration   3: 9.136 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.049 ±(99.9%) 1.579 ops/ms [Average]
  (min, avg, max) = (8.963, 9.049, 9.136), stdev = 0.087
  CI (99.9%): [7.470, 10.628] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 5.327 ops/ms
# Warmup Iteration   2: 6.455 ops/ms
# Warmup Iteration   3: 6.901 ops/ms
Iteration   1: 7.197 ops/ms
Iteration   2: 7.036 ops/ms
Iteration   3: 7.044 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.092 ±(99.9%) 1.655 ops/ms [Average]
  (min, avg, max) = (7.036, 7.092, 7.197), stdev = 0.091
  CI (99.9%): [5.437, 8.747] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 5.457 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.694 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.592 ±(99.9%) 0.003 ms/op
Iteration   1: 3.637 ±(99.9%) 0.018 ms/op
Iteration   2: 3.616 ±(99.9%) 0.002 ms/op
Iteration   3: 3.541 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.598 ±(99.9%) 0.914 ms/op [Average]
  (min, avg, max) = (3.541, 3.598, 3.637), stdev = 0.050
  CI (99.9%): [2.684, 4.512] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 4.751 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.623 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.487 ±(99.9%) 0.004 ms/op
Iteration   1: 3.419 ±(99.9%) 0.003 ms/op
Iteration   2: 3.380 ±(99.9%) 0.003 ms/op
Iteration   3: 3.479 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.426 ±(99.9%) 0.907 ms/op [Average]
  (min, avg, max) = (3.380, 3.426, 3.479), stdev = 0.050
  CI (99.9%): [2.519, 4.333] (assumes normal distribution)


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
# Warmup Iteration   1: 4.844 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.735 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.602 ±(99.9%) 0.003 ms/op
Iteration   1: 3.559 ±(99.9%) 0.004 ms/op
Iteration   2: 3.677 ±(99.9%) 0.004 ms/op
Iteration   3: 3.567 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.601 ±(99.9%) 1.195 ms/op [Average]
  (min, avg, max) = (3.559, 3.601, 3.677), stdev = 0.066
  CI (99.9%): [2.406, 4.796] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 6.536 ±(99.9%) 0.113 ms/op
# Warmup Iteration   2: 4.708 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 4.501 ±(99.9%) 0.039 ms/op
Iteration   1: 4.423 ±(99.9%) 0.029 ms/op
Iteration   2: 4.437 ±(99.9%) 0.029 ms/op
Iteration   3: 4.407 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.423 ±(99.9%) 0.268 ms/op [Average]
  (min, avg, max) = (4.407, 4.423, 4.437), stdev = 0.015
  CI (99.9%): [4.155, 4.691] (assumes normal distribution)


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
# Warmup Iteration   1: 4.957 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.786 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.668 ±(99.9%) 0.009 ms/op
Iteration   1: 3.588 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.032 ms/op
                 createUser·p0.50:   3.490 ms/op
                 createUser·p0.90:   4.309 ms/op
                 createUser·p0.95:   4.563 ms/op
                 createUser·p0.99:   5.554 ms/op
                 createUser·p0.999:  10.633 ms/op
                 createUser·p0.9999: 19.567 ms/op
                 createUser·p1.00:   20.021 ms/op

Iteration   2: 3.620 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.124 ms/op
                 createUser·p0.50:   3.564 ms/op
                 createUser·p0.90:   4.309 ms/op
                 createUser·p0.95:   4.530 ms/op
                 createUser·p0.99:   5.358 ms/op
                 createUser·p0.999:  7.741 ms/op
                 createUser·p0.9999: 20.480 ms/op
                 createUser·p1.00:   22.479 ms/op

Iteration   3: 3.615 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.935 ms/op
                 createUser·p0.50:   3.527 ms/op
                 createUser·p0.90:   4.235 ms/op
                 createUser·p0.95:   4.530 ms/op
                 createUser·p0.99:   5.595 ms/op
                 createUser·p0.999:  17.008 ms/op
                 createUser·p0.9999: 22.774 ms/op
                 createUser·p1.00:   23.396 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 266226
  mean =      3.607 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2357 
    [ 2.500,  5.000) = 259780 
    [ 5.000,  7.500) = 3218 
    [ 7.500, 10.000) = 530 
    [10.000, 12.500) = 146 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 53 
    [17.500, 20.000) = 52 
    [20.000, 22.500) = 70 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.935 ms/op
     p(50.0000) =      3.527 ms/op
     p(90.0000) =      4.284 ms/op
     p(95.0000) =      4.538 ms/op
     p(99.0000) =      5.472 ms/op
     p(99.9000) =     10.387 ms/op
     p(99.9900) =     22.446 ms/op
     p(99.9990) =     23.255 ms/op
     p(99.9999) =     23.396 ms/op
    p(100.0000) =     23.396 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.728 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.595 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.493 ±(99.9%) 0.006 ms/op
Iteration   1: 3.537 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.188 ms/op
                 existUser·p0.50:   3.453 ms/op
                 existUser·p0.90:   4.190 ms/op
                 existUser·p0.95:   4.440 ms/op
                 existUser·p0.99:   5.472 ms/op
                 existUser·p0.999:  8.804 ms/op
                 existUser·p0.9999: 18.940 ms/op
                 existUser·p1.00:   19.399 ms/op

Iteration   2: 3.308 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.909 ms/op
                 existUser·p0.50:   3.310 ms/op
                 existUser·p0.90:   3.842 ms/op
                 existUser·p0.95:   4.166 ms/op
                 existUser·p0.99:   5.415 ms/op
                 existUser·p0.999:  7.365 ms/op
                 existUser·p0.9999: 14.352 ms/op
                 existUser·p1.00:   15.368 ms/op

Iteration   3: 3.366 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.846 ms/op
                 existUser·p0.50:   3.330 ms/op
                 existUser·p0.90:   3.961 ms/op
                 existUser·p0.95:   4.153 ms/op
                 existUser·p0.99:   4.579 ms/op
                 existUser·p0.999:  6.676 ms/op
                 existUser·p0.9999: 17.498 ms/op
                 existUser·p1.00:   17.531 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 282503
  mean =      3.401 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 656 
    [ 1.250,  2.500) = 7794 
    [ 2.500,  3.750) = 218053 
    [ 3.750,  5.000) = 52483 
    [ 5.000,  6.250) = 2598 
    [ 6.250,  7.500) = 615 
    [ 7.500,  8.750) = 129 
    [ 8.750, 10.000) = 32 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 14 
    [12.500, 13.750) = 23 
    [13.750, 15.000) = 40 
    [15.000, 16.250) = 4 
    [16.250, 17.500) = 26 
    [17.500, 18.750) = 23 

  Percentiles, ms/op:
      p(0.0000) =      0.846 ms/op
     p(50.0000) =      3.359 ms/op
     p(90.0000) =      4.018 ms/op
     p(95.0000) =      4.276 ms/op
     p(99.0000) =      5.235 ms/op
     p(99.9000) =      7.606 ms/op
     p(99.9900) =     18.080 ms/op
     p(99.9990) =     19.273 ms/op
     p(99.9999) =     19.399 ms/op
    p(100.0000) =     19.399 ms/op


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
# Warmup Iteration   1: 5.077 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 3.747 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.630 ±(99.9%) 0.009 ms/op
Iteration   1: 3.679 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.806 ms/op
                 getUser·p0.50:   3.588 ms/op
                 getUser·p0.90:   4.547 ms/op
                 getUser·p0.95:   4.882 ms/op
                 getUser·p0.99:   6.259 ms/op
                 getUser·p0.999:  11.095 ms/op
                 getUser·p0.9999: 14.253 ms/op
                 getUser·p1.00:   16.646 ms/op

Iteration   2: 3.712 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.948 ms/op
                 getUser·p0.50:   3.633 ms/op
                 getUser·p0.90:   4.473 ms/op
                 getUser·p0.95:   4.694 ms/op
                 getUser·p0.99:   5.390 ms/op
                 getUser·p0.999:  7.994 ms/op
                 getUser·p0.9999: 21.127 ms/op
                 getUser·p1.00:   21.627 ms/op

Iteration   3: 3.674 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.872 ms/op
                 getUser·p0.50:   3.600 ms/op
                 getUser·p0.90:   4.342 ms/op
                 getUser·p0.95:   4.604 ms/op
                 getUser·p0.99:   5.554 ms/op
                 getUser·p0.999:  10.093 ms/op
                 getUser·p0.9999: 23.341 ms/op
                 getUser·p1.00:   23.724 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 260147
  mean =      3.688 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4579 
    [ 2.500,  5.000) = 248805 
    [ 5.000,  7.500) = 6025 
    [ 7.500, 10.000) = 504 
    [10.000, 12.500) = 59 
    [12.500, 15.000) = 75 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 44 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.806 ms/op
     p(50.0000) =      3.609 ms/op
     p(90.0000) =      4.456 ms/op
     p(95.0000) =      4.719 ms/op
     p(99.0000) =      5.775 ms/op
     p(99.9000) =      9.650 ms/op
     p(99.9900) =     21.920 ms/op
     p(99.9990) =     23.639 ms/op
     p(99.9999) =     23.724 ms/op
    p(100.0000) =     23.724 ms/op


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
# Warmup Iteration   1: 6.641 ±(99.9%) 0.072 ms/op
# Warmup Iteration   2: 4.745 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.522 ±(99.9%) 0.012 ms/op
Iteration   1: 4.453 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.563 ms/op
                 listUser·p0.50:   4.342 ms/op
                 listUser·p0.90:   5.120 ms/op
                 listUser·p0.95:   6.177 ms/op
                 listUser·p0.99:   7.578 ms/op
                 listUser·p0.999:  13.568 ms/op
                 listUser·p0.9999: 15.710 ms/op
                 listUser·p1.00:   16.105 ms/op

Iteration   2: 4.388 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.985 ms/op
                 listUser·p0.50:   4.293 ms/op
                 listUser·p0.90:   5.030 ms/op
                 listUser·p0.95:   5.702 ms/op
                 listUser·p0.99:   7.463 ms/op
                 listUser·p0.999:  16.162 ms/op
                 listUser·p0.9999: 18.453 ms/op
                 listUser·p1.00:   18.874 ms/op

Iteration   3: 4.388 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.227 ms/op
                 listUser·p0.50:   4.301 ms/op
                 listUser·p0.90:   5.014 ms/op
                 listUser·p0.95:   5.603 ms/op
                 listUser·p0.99:   7.430 ms/op
                 listUser·p0.999:  18.550 ms/op
                 listUser·p0.9999: 28.246 ms/op
                 listUser·p1.00:   28.705 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 217706
  mean =      4.409 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 316 
    [ 2.500,  5.000) = 193859 
    [ 5.000,  7.500) = 21385 
    [ 7.500, 10.000) = 1620 
    [10.000, 12.500) = 188 
    [12.500, 15.000) = 84 
    [15.000, 17.500) = 136 
    [17.500, 20.000) = 92 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.227 ms/op
     p(50.0000) =      4.309 ms/op
     p(90.0000) =      5.046 ms/op
     p(95.0000) =      5.808 ms/op
     p(99.0000) =      7.487 ms/op
     p(99.9000) =     15.439 ms/op
     p(99.9900) =     20.747 ms/op
     p(99.9990) =     28.622 ms/op
     p(99.9999) =     28.705 ms/op
    p(100.0000) =     28.705 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.813 ± 2.799  ops/ms
ClientGrpc.existUser                       thrpt       3   9.292 ± 4.275  ops/ms
ClientGrpc.getUser                         thrpt       3   9.049 ± 1.579  ops/ms
ClientGrpc.listUser                        thrpt       3   7.092 ± 1.655  ops/ms
ClientGrpc.createUser                       avgt       3   3.598 ± 0.914   ms/op
ClientGrpc.existUser                        avgt       3   3.426 ± 0.907   ms/op
ClientGrpc.getUser                          avgt       3   3.601 ± 1.195   ms/op
ClientGrpc.listUser                         avgt       3   4.423 ± 0.268   ms/op
ClientGrpc.createUser                     sample  266226   3.607 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.935           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.527           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.284           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.538           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.472           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.387           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          22.446           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.396           ms/op
ClientGrpc.existUser                      sample  282503   3.401 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.846           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.359           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.018           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.276           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.235           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.606           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.080           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.399           ms/op
ClientGrpc.getUser                        sample  260147   3.688 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.806           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.609           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.456           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.719           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.775           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.650           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.920           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.724           ms/op
ClientGrpc.listUser                       sample  217706   4.409 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.227           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.309           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.046           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.808           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.487           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.439           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          20.747           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          28.705           ms/op
