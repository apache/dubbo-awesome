# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.512 ops/ms
# Warmup Iteration   2: 7.189 ops/ms
# Warmup Iteration   3: 8.160 ops/ms
Iteration   1: 8.670 ops/ms
Iteration   2: 8.955 ops/ms
Iteration   3: 8.778 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.801 ±(99.9%) 2.630 ops/ms [Average]
  (min, avg, max) = (8.670, 8.801, 8.955), stdev = 0.144
  CI (99.9%): [6.171, 11.431] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 6.102 ops/ms
# Warmup Iteration   2: 8.390 ops/ms
# Warmup Iteration   3: 8.531 ops/ms
Iteration   1: 9.042 ops/ms
Iteration   2: 8.699 ops/ms
Iteration   3: 8.843 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.861 ±(99.9%) 3.139 ops/ms [Average]
  (min, avg, max) = (8.699, 8.861, 9.042), stdev = 0.172
  CI (99.9%): [5.722, 12.000] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:54
# Fork: 1 of 1
# Warmup Iteration   1: 5.797 ops/ms
# Warmup Iteration   2: 8.267 ops/ms
# Warmup Iteration   3: 8.622 ops/ms
Iteration   1: 8.867 ops/ms
Iteration   2: 8.939 ops/ms
Iteration   3: 8.193 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.666 ±(99.9%) 7.503 ops/ms [Average]
  (min, avg, max) = (8.193, 8.666, 8.939), stdev = 0.411
  CI (99.9%): [1.163, 16.170] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 4.362 ops/ms
# Warmup Iteration   2: 6.457 ops/ms
# Warmup Iteration   3: 6.777 ops/ms
Iteration   1: 6.730 ops/ms
Iteration   2: 6.961 ops/ms
Iteration   3: 7.127 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.939 ±(99.9%) 3.639 ops/ms [Average]
  (min, avg, max) = (6.730, 6.939, 7.127), stdev = 0.199
  CI (99.9%): [3.300, 10.578] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 5.321 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.933 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.685 ±(99.9%) 0.002 ms/op
Iteration   1: 3.870 ±(99.9%) 0.003 ms/op
Iteration   2: 3.914 ±(99.9%) 0.003 ms/op
Iteration   3: 3.974 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.920 ±(99.9%) 0.950 ms/op [Average]
  (min, avg, max) = (3.870, 3.920, 3.974), stdev = 0.052
  CI (99.9%): [2.969, 4.870] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 4.907 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.798 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.697 ±(99.9%) 0.004 ms/op
Iteration   1: 3.712 ±(99.9%) 0.003 ms/op
Iteration   2: 3.756 ±(99.9%) 0.006 ms/op
Iteration   3: 3.612 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.693 ±(99.9%) 1.352 ms/op [Average]
  (min, avg, max) = (3.612, 3.693, 3.756), stdev = 0.074
  CI (99.9%): [2.341, 5.046] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 5.400 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.882 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.786 ±(99.9%) 0.004 ms/op
Iteration   1: 3.773 ±(99.9%) 0.003 ms/op
Iteration   2: 3.825 ±(99.9%) 0.003 ms/op
Iteration   3: 3.787 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.795 ±(99.9%) 0.489 ms/op [Average]
  (min, avg, max) = (3.773, 3.795, 3.825), stdev = 0.027
  CI (99.9%): [3.306, 4.284] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 5.930 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 5.077 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 4.678 ±(99.9%) 0.014 ms/op
Iteration   1: 4.719 ±(99.9%) 0.010 ms/op
Iteration   2: 4.660 ±(99.9%) 0.014 ms/op
Iteration   3: 4.715 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.698 ±(99.9%) 0.604 ms/op [Average]
  (min, avg, max) = (4.660, 4.698, 4.719), stdev = 0.033
  CI (99.9%): [4.094, 5.302] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 4.972 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.993 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.759 ±(99.9%) 0.010 ms/op
Iteration   1: 3.642 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.795 ms/op
                 createUser·p0.50:   3.588 ms/op
                 createUser·p0.90:   4.506 ms/op
                 createUser·p0.95:   4.809 ms/op
                 createUser·p0.99:   5.893 ms/op
                 createUser·p0.999:  10.078 ms/op
                 createUser·p0.9999: 16.471 ms/op
                 createUser·p1.00:   16.941 ms/op

Iteration   2: 3.618 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.878 ms/op
                 createUser·p0.50:   3.584 ms/op
                 createUser·p0.90:   4.465 ms/op
                 createUser·p0.95:   4.735 ms/op
                 createUser·p0.99:   5.464 ms/op
                 createUser·p0.999:  7.232 ms/op
                 createUser·p0.9999: 19.643 ms/op
                 createUser·p1.00:   20.283 ms/op

Iteration   3: 3.617 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.795 ms/op
                 createUser·p0.50:   3.564 ms/op
                 createUser·p0.90:   4.506 ms/op
                 createUser·p0.95:   4.801 ms/op
                 createUser·p0.99:   5.693 ms/op
                 createUser·p0.999:  17.105 ms/op
                 createUser·p0.9999: 40.894 ms/op
                 createUser·p1.00:   41.026 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 264782
  mean =      3.626 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 256999 
    [ 5.000, 10.000) = 7562 
    [10.000, 15.000) = 61 
    [15.000, 20.000) = 93 
    [20.000, 25.000) = 35 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 10 
    [40.000, 45.000) = 22 

  Percentiles, ms/op:
      p(0.0000) =      0.795 ms/op
     p(50.0000) =      3.580 ms/op
     p(90.0000) =      4.489 ms/op
     p(95.0000) =      4.776 ms/op
     p(99.0000) =      5.669 ms/op
     p(99.9000) =      9.342 ms/op
     p(99.9900) =     38.797 ms/op
     p(99.9990) =     40.960 ms/op
     p(99.9999) =     41.026 ms/op
    p(100.0000) =     41.026 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.867 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.535 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.811 ±(99.9%) 0.009 ms/op
Iteration   1: 3.677 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.885 ms/op
                 existUser·p0.50:   3.633 ms/op
                 existUser·p0.90:   4.620 ms/op
                 existUser·p0.95:   4.948 ms/op
                 existUser·p0.99:   5.915 ms/op
                 existUser·p0.999:  9.421 ms/op
                 existUser·p0.9999: 15.848 ms/op
                 existUser·p1.00:   16.187 ms/op

Iteration   2: 3.528 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.699 ms/op
                 existUser·p0.50:   3.469 ms/op
                 existUser·p0.90:   4.440 ms/op
                 existUser·p0.95:   4.719 ms/op
                 existUser·p0.99:   5.439 ms/op
                 existUser·p0.999:  11.542 ms/op
                 existUser·p0.9999: 19.230 ms/op
                 existUser·p1.00:   19.694 ms/op

Iteration   3: 3.538 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.854 ms/op
                 existUser·p0.50:   3.498 ms/op
                 existUser·p0.90:   4.383 ms/op
                 existUser·p0.95:   4.661 ms/op
                 existUser·p0.99:   5.521 ms/op
                 existUser·p0.999:  11.239 ms/op
                 existUser·p0.9999: 23.622 ms/op
                 existUser·p1.00:   25.199 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 268219
  mean =      3.580 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15255 
    [ 2.500,  5.000) = 244804 
    [ 5.000,  7.500) = 7497 
    [ 7.500, 10.000) = 367 
    [10.000, 12.500) = 111 
    [12.500, 15.000) = 62 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 57 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.699 ms/op
     p(50.0000) =      3.531 ms/op
     p(90.0000) =      4.481 ms/op
     p(95.0000) =      4.776 ms/op
     p(99.0000) =      5.669 ms/op
     p(99.9000) =     10.650 ms/op
     p(99.9900) =     22.649 ms/op
     p(99.9990) =     24.562 ms/op
     p(99.9999) =     25.199 ms/op
    p(100.0000) =     25.199 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.275 ±(99.9%) 0.072 ms/op
# Warmup Iteration   2: 3.736 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.786 ±(99.9%) 0.011 ms/op
Iteration   1: 3.702 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.014 ms/op
                 getUser·p0.50:   3.666 ms/op
                 getUser·p0.90:   4.596 ms/op
                 getUser·p0.95:   4.907 ms/op
                 getUser·p0.99:   5.767 ms/op
                 getUser·p0.999:  8.577 ms/op
                 getUser·p0.9999: 17.969 ms/op
                 getUser·p1.00:   18.907 ms/op

Iteration   2: 3.661 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.904 ms/op
                 getUser·p0.50:   3.576 ms/op
                 getUser·p0.90:   4.497 ms/op
                 getUser·p0.95:   4.817 ms/op
                 getUser·p0.99:   5.857 ms/op
                 getUser·p0.999:  12.888 ms/op
                 getUser·p0.9999: 35.275 ms/op
                 getUser·p1.00:   35.652 ms/op

Iteration   3: 3.827 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.018 ms/op
                 getUser·p0.50:   3.740 ms/op
                 getUser·p0.90:   4.735 ms/op
                 getUser·p0.95:   5.063 ms/op
                 getUser·p0.99:   6.048 ms/op
                 getUser·p0.999:  9.690 ms/op
                 getUser·p0.9999: 23.876 ms/op
                 getUser·p1.00:   24.510 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 257422
  mean =      3.729 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8442 
    [ 2.500,  5.000) = 237787 
    [ 5.000,  7.500) = 10526 
    [ 7.500, 10.000) = 425 
    [10.000, 12.500) = 47 
    [12.500, 15.000) = 63 
    [15.000, 17.500) = 6 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 9 
    [32.500, 35.000) = 42 
    [35.000, 37.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      0.904 ms/op
     p(50.0000) =      3.662 ms/op
     p(90.0000) =      4.612 ms/op
     p(95.0000) =      4.940 ms/op
     p(99.0000) =      5.898 ms/op
     p(99.9000) =      9.692 ms/op
     p(99.9900) =     33.882 ms/op
     p(99.9990) =     35.455 ms/op
     p(99.9999) =     35.652 ms/op
    p(100.0000) =     35.652 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 7.637 ±(99.9%) 0.089 ms/op
# Warmup Iteration   2: 5.247 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.801 ±(99.9%) 0.017 ms/op
Iteration   1: 4.672 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.399 ms/op
                 listUser·p0.50:   4.432 ms/op
                 listUser·p0.90:   6.111 ms/op
                 listUser·p0.95:   6.930 ms/op
                 listUser·p0.99:   8.618 ms/op
                 listUser·p0.999:  14.844 ms/op
                 listUser·p0.9999: 17.594 ms/op
                 listUser·p1.00:   18.416 ms/op

Iteration   2: 4.500 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.231 ms/op
                 listUser·p0.50:   4.301 ms/op
                 listUser·p0.90:   5.775 ms/op
                 listUser·p0.95:   6.586 ms/op
                 listUser·p0.99:   8.110 ms/op
                 listUser·p0.999:  17.713 ms/op
                 listUser·p0.9999: 22.381 ms/op
                 listUser·p1.00:   23.658 ms/op

Iteration   3: 4.534 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   0.842 ms/op
                 listUser·p0.50:   4.301 ms/op
                 listUser·p0.90:   5.906 ms/op
                 listUser·p0.95:   6.734 ms/op
                 listUser·p0.99:   8.217 ms/op
                 listUser·p0.999:  19.595 ms/op
                 listUser·p0.9999: 25.031 ms/op
                 listUser·p1.00:   25.592 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 210078
  mean =      4.567 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 693 
    [ 2.500,  5.000) = 162486 
    [ 5.000,  7.500) = 41902 
    [ 7.500, 10.000) = 4294 
    [10.000, 12.500) = 330 
    [12.500, 15.000) = 91 
    [15.000, 17.500) = 75 
    [17.500, 20.000) = 99 
    [20.000, 22.500) = 77 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.842 ms/op
     p(50.0000) =      4.342 ms/op
     p(90.0000) =      5.939 ms/op
     p(95.0000) =      6.758 ms/op
     p(99.0000) =      8.339 ms/op
     p(99.9000) =     17.425 ms/op
     p(99.9900) =     23.527 ms/op
     p(99.9990) =     25.513 ms/op
     p(99.9999) =     25.592 ms/op
    p(100.0000) =     25.592 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.801 ± 2.630  ops/ms
ClientGrpc.existUser                       thrpt       3   8.861 ± 3.139  ops/ms
ClientGrpc.getUser                         thrpt       3   8.666 ± 7.503  ops/ms
ClientGrpc.listUser                        thrpt       3   6.939 ± 3.639  ops/ms
ClientGrpc.createUser                       avgt       3   3.920 ± 0.950   ms/op
ClientGrpc.existUser                        avgt       3   3.693 ± 1.352   ms/op
ClientGrpc.getUser                          avgt       3   3.795 ± 0.489   ms/op
ClientGrpc.listUser                         avgt       3   4.698 ± 0.604   ms/op
ClientGrpc.createUser                     sample  264782   3.626 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.795           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.580           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.489           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.776           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.669           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.342           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          38.797           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          41.026           ms/op
ClientGrpc.existUser                      sample  268219   3.580 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.699           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.531           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.481           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.776           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.669           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.650           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          22.649           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          25.199           ms/op
ClientGrpc.getUser                        sample  257422   3.729 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.904           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.662           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.612           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.940           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.898           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.692           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          33.882           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          35.652           ms/op
ClientGrpc.listUser                       sample  210078   4.567 ± 0.009   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.842           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.342           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.939           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.758           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.339           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.425           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.527           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.592           ms/op
