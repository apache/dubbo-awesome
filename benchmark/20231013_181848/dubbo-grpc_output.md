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
# Warmup Iteration   1: 3.103 ops/ms
# Warmup Iteration   2: 7.124 ops/ms
# Warmup Iteration   3: 8.524 ops/ms
Iteration   1: 8.729 ops/ms
Iteration   2: 9.024 ops/ms
Iteration   3: 8.813 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.855 ±(99.9%) 2.768 ops/ms [Average]
  (min, avg, max) = (8.729, 8.855, 9.024), stdev = 0.152
  CI (99.9%): [6.088, 11.623] (assumes normal distribution)


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
# Warmup Iteration   1: 6.302 ops/ms
# Warmup Iteration   2: 8.654 ops/ms
# Warmup Iteration   3: 9.254 ops/ms
Iteration   1: 9.198 ops/ms
Iteration   2: 9.348 ops/ms
Iteration   3: 9.316 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.287 ±(99.9%) 1.447 ops/ms [Average]
  (min, avg, max) = (9.198, 9.287, 9.348), stdev = 0.079
  CI (99.9%): [7.841, 10.734] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 5.616 ops/ms
# Warmup Iteration   2: 8.252 ops/ms
# Warmup Iteration   3: 8.639 ops/ms
Iteration   1: 8.958 ops/ms
Iteration   2: 8.732 ops/ms
Iteration   3: 8.774 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.821 ±(99.9%) 2.196 ops/ms [Average]
  (min, avg, max) = (8.732, 8.821, 8.958), stdev = 0.120
  CI (99.9%): [6.626, 11.017] (assumes normal distribution)


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
# Warmup Iteration   1: 4.591 ops/ms
# Warmup Iteration   2: 6.434 ops/ms
# Warmup Iteration   3: 6.958 ops/ms
Iteration   1: 6.950 ops/ms
Iteration   2: 6.838 ops/ms
Iteration   3: 7.002 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.930 ±(99.9%) 1.528 ops/ms [Average]
  (min, avg, max) = (6.838, 6.930, 7.002), stdev = 0.084
  CI (99.9%): [5.402, 8.458] (assumes normal distribution)


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
# Warmup Iteration   1: 5.533 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 3.870 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.729 ±(99.9%) 0.010 ms/op
Iteration   1: 3.671 ±(99.9%) 0.003 ms/op
Iteration   2: 3.619 ±(99.9%) 0.005 ms/op
Iteration   3: 3.645 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.645 ±(99.9%) 0.475 ms/op [Average]
  (min, avg, max) = (3.619, 3.645, 3.671), stdev = 0.026
  CI (99.9%): [3.170, 4.120] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 4.932 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.723 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.440 ±(99.9%) 0.003 ms/op
Iteration   1: 3.449 ±(99.9%) 0.004 ms/op
Iteration   2: 3.545 ±(99.9%) 0.002 ms/op
Iteration   3: 3.544 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.513 ±(99.9%) 1.010 ms/op [Average]
  (min, avg, max) = (3.449, 3.513, 3.545), stdev = 0.055
  CI (99.9%): [2.503, 4.523] (assumes normal distribution)


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
# Warmup Iteration   1: 5.090 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.721 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.664 ±(99.9%) 0.004 ms/op
Iteration   1: 3.683 ±(99.9%) 0.003 ms/op
Iteration   2: 3.655 ±(99.9%) 0.008 ms/op
Iteration   3: 3.672 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.670 ±(99.9%) 0.263 ms/op [Average]
  (min, avg, max) = (3.655, 3.670, 3.683), stdev = 0.014
  CI (99.9%): [3.407, 3.933] (assumes normal distribution)


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
# Warmup Iteration   1: 5.668 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.834 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.675 ±(99.9%) 0.013 ms/op
Iteration   1: 4.599 ±(99.9%) 0.021 ms/op
Iteration   2: 4.587 ±(99.9%) 0.014 ms/op
Iteration   3: 4.665 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.617 ±(99.9%) 0.767 ms/op [Average]
  (min, avg, max) = (4.587, 4.617, 4.665), stdev = 0.042
  CI (99.9%): [3.850, 5.384] (assumes normal distribution)


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
# Warmup Iteration   1: 5.455 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 3.850 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.575 ±(99.9%) 0.009 ms/op
Iteration   1: 3.610 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.563 ms/op
                 createUser·p0.50:   3.572 ms/op
                 createUser·p0.90:   4.211 ms/op
                 createUser·p0.95:   4.432 ms/op
                 createUser·p0.99:   5.612 ms/op
                 createUser·p0.999:  12.377 ms/op
                 createUser·p0.9999: 18.916 ms/op
                 createUser·p1.00:   20.316 ms/op

Iteration   2: 3.621 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.778 ms/op
                 createUser·p0.50:   3.564 ms/op
                 createUser·p0.90:   4.309 ms/op
                 createUser·p0.95:   4.563 ms/op
                 createUser·p0.99:   5.652 ms/op
                 createUser·p0.999:  11.176 ms/op
                 createUser·p0.9999: 21.665 ms/op
                 createUser·p1.00:   23.396 ms/op

Iteration   3: 3.623 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.825 ms/op
                 createUser·p0.50:   3.551 ms/op
                 createUser·p0.90:   4.334 ms/op
                 createUser·p0.95:   4.579 ms/op
                 createUser·p0.99:   5.284 ms/op
                 createUser·p0.999:  17.843 ms/op
                 createUser·p0.9999: 27.957 ms/op
                 createUser·p1.00:   28.115 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 265206
  mean =      3.618 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5907 
    [ 2.500,  5.000) = 254889 
    [ 5.000,  7.500) = 3517 
    [ 7.500, 10.000) = 389 
    [10.000, 12.500) = 220 
    [12.500, 15.000) = 18 
    [15.000, 17.500) = 85 
    [17.500, 20.000) = 50 
    [20.000, 22.500) = 69 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.563 ms/op
     p(50.0000) =      3.564 ms/op
     p(90.0000) =      4.276 ms/op
     p(95.0000) =      4.530 ms/op
     p(99.0000) =      5.505 ms/op
     p(99.9000) =     15.086 ms/op
     p(99.9900) =     25.525 ms/op
     p(99.9990) =     28.094 ms/op
     p(99.9999) =     28.115 ms/op
    p(100.0000) =     28.115 ms/op


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
# Warmup Iteration   1: 4.632 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.638 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.566 ±(99.9%) 0.008 ms/op
Iteration   1: 3.475 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.920 ms/op
                 existUser·p0.50:   3.437 ms/op
                 existUser·p0.90:   4.043 ms/op
                 existUser·p0.95:   4.334 ms/op
                 existUser·p0.99:   4.956 ms/op
                 existUser·p0.999:  8.010 ms/op
                 existUser·p0.9999: 14.631 ms/op
                 existUser·p1.00:   14.893 ms/op

Iteration   2: 3.426 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.811 ms/op
                 existUser·p0.50:   3.400 ms/op
                 existUser·p0.90:   3.949 ms/op
                 existUser·p0.95:   4.235 ms/op
                 existUser·p0.99:   5.067 ms/op
                 existUser·p0.999:  12.146 ms/op
                 existUser·p0.9999: 18.612 ms/op
                 existUser·p1.00:   19.890 ms/op

Iteration   3: 3.346 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.800 ms/op
                 existUser·p0.50:   3.375 ms/op
                 existUser·p0.90:   3.883 ms/op
                 existUser·p0.95:   4.145 ms/op
                 existUser·p0.99:   5.046 ms/op
                 existUser·p0.999:  9.601 ms/op
                 existUser·p0.9999: 18.674 ms/op
                 existUser·p1.00:   18.874 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 280973
  mean =      3.415 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 364 
    [ 1.250,  2.500) = 11543 
    [ 2.500,  3.750) = 212234 
    [ 3.750,  5.000) = 53952 
    [ 5.000,  6.250) = 1882 
    [ 6.250,  7.500) = 498 
    [ 7.500,  8.750) = 142 
    [ 8.750, 10.000) = 112 
    [10.000, 11.250) = 52 
    [11.250, 12.500) = 6 
    [12.500, 13.750) = 25 
    [13.750, 15.000) = 58 
    [15.000, 16.250) = 30 
    [16.250, 17.500) = 42 
    [17.500, 18.750) = 27 

  Percentiles, ms/op:
      p(0.0000) =      0.800 ms/op
     p(50.0000) =      3.404 ms/op
     p(90.0000) =      3.961 ms/op
     p(95.0000) =      4.243 ms/op
     p(99.0000) =      5.022 ms/op
     p(99.9000) =      9.699 ms/op
     p(99.9900) =     18.579 ms/op
     p(99.9990) =     18.848 ms/op
     p(99.9999) =     19.890 ms/op
    p(100.0000) =     19.890 ms/op


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
# Warmup Iteration   1: 5.156 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 3.879 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.686 ±(99.9%) 0.008 ms/op
Iteration   1: 3.662 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.882 ms/op
                 getUser·p0.50:   3.613 ms/op
                 getUser·p0.90:   4.334 ms/op
                 getUser·p0.95:   4.637 ms/op
                 getUser·p0.99:   5.677 ms/op
                 getUser·p0.999:  12.714 ms/op
                 getUser·p0.9999: 16.078 ms/op
                 getUser·p1.00:   17.072 ms/op

Iteration   2: 3.587 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.927 ms/op
                 getUser·p0.50:   3.543 ms/op
                 getUser·p0.90:   4.153 ms/op
                 getUser·p0.95:   4.448 ms/op
                 getUser·p0.99:   5.726 ms/op
                 getUser·p0.999:  8.187 ms/op
                 getUser·p0.9999: 22.741 ms/op
                 getUser·p1.00:   22.938 ms/op

Iteration   3: 3.720 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.723 ms/op
                 getUser·p0.50:   3.641 ms/op
                 getUser·p0.90:   4.489 ms/op
                 getUser·p0.95:   4.694 ms/op
                 getUser·p0.99:   5.382 ms/op
                 getUser·p0.999:  10.011 ms/op
                 getUser·p0.9999: 23.422 ms/op
                 getUser·p1.00:   23.921 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 262702
  mean =      3.656 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5641 
    [ 2.500,  5.000) = 252142 
    [ 5.000,  7.500) = 4260 
    [ 7.500, 10.000) = 367 
    [10.000, 12.500) = 64 
    [12.500, 15.000) = 113 
    [15.000, 17.500) = 49 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 36 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.723 ms/op
     p(50.0000) =      3.596 ms/op
     p(90.0000) =      4.342 ms/op
     p(95.0000) =      4.620 ms/op
     p(99.0000) =      5.603 ms/op
     p(99.9000) =     11.334 ms/op
     p(99.9900) =     22.765 ms/op
     p(99.9990) =     23.781 ms/op
     p(99.9999) =     23.921 ms/op
    p(100.0000) =     23.921 ms/op


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
# Warmup Iteration   1: 6.579 ±(99.9%) 0.075 ms/op
# Warmup Iteration   2: 4.760 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.627 ±(99.9%) 0.013 ms/op
Iteration   1: 4.581 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.579 ms/op
                 listUser·p0.50:   4.448 ms/op
                 listUser·p0.90:   5.325 ms/op
                 listUser·p0.95:   6.537 ms/op
                 listUser·p0.99:   7.930 ms/op
                 listUser·p0.999:  14.698 ms/op
                 listUser·p0.9999: 17.368 ms/op
                 listUser·p1.00:   17.990 ms/op

Iteration   2: 4.510 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.022 ms/op
                 listUser·p0.50:   4.391 ms/op
                 listUser·p0.90:   5.022 ms/op
                 listUser·p0.95:   5.816 ms/op
                 listUser·p0.99:   7.873 ms/op
                 listUser·p0.999:  16.728 ms/op
                 listUser·p0.9999: 23.291 ms/op
                 listUser·p1.00:   25.625 ms/op

Iteration   3: 4.633 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   0.739 ms/op
                 listUser·p0.50:   4.497 ms/op
                 listUser·p0.90:   5.415 ms/op
                 listUser·p0.95:   6.308 ms/op
                 listUser·p0.99:   7.938 ms/op
                 listUser·p0.999:  18.415 ms/op
                 listUser·p0.9999: 29.465 ms/op
                 listUser·p1.00:   30.441 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 209938
  mean =      4.574 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 489 
    [ 2.500,  5.000) = 179223 
    [ 5.000,  7.500) = 26787 
    [ 7.500, 10.000) = 2664 
    [10.000, 12.500) = 354 
    [12.500, 15.000) = 144 
    [15.000, 17.500) = 139 
    [17.500, 20.000) = 64 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 17 
    [27.500, 30.000) = 23 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.739 ms/op
     p(50.0000) =      4.440 ms/op
     p(90.0000) =      5.235 ms/op
     p(95.0000) =      6.226 ms/op
     p(99.0000) =      7.922 ms/op
     p(99.9000) =     15.712 ms/op
     p(99.9900) =     28.148 ms/op
     p(99.9990) =     30.163 ms/op
     p(99.9999) =     30.441 ms/op
    p(100.0000) =     30.441 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.855 ± 2.768  ops/ms
ClientGrpc.existUser                       thrpt       3   9.287 ± 1.447  ops/ms
ClientGrpc.getUser                         thrpt       3   8.821 ± 2.196  ops/ms
ClientGrpc.listUser                        thrpt       3   6.930 ± 1.528  ops/ms
ClientGrpc.createUser                       avgt       3   3.645 ± 0.475   ms/op
ClientGrpc.existUser                        avgt       3   3.513 ± 1.010   ms/op
ClientGrpc.getUser                          avgt       3   3.670 ± 0.263   ms/op
ClientGrpc.listUser                         avgt       3   4.617 ± 0.767   ms/op
ClientGrpc.createUser                     sample  265206   3.618 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.563           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.564           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.276           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.530           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.505           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          15.086           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          25.525           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          28.115           ms/op
ClientGrpc.existUser                      sample  280973   3.415 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.800           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.404           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.961           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.243           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.022           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.699           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.579           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.890           ms/op
ClientGrpc.getUser                        sample  262702   3.656 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.723           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.596           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.342           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.620           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.603           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.334           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          22.765           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.921           ms/op
ClientGrpc.listUser                       sample  209938   4.574 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.739           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.440           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.235           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.226           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.922           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.712           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          28.148           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          30.441           ms/op
