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
# Warmup Iteration   1: 3.445 ops/ms
# Warmup Iteration   2: 6.171 ops/ms
# Warmup Iteration   3: 7.981 ops/ms
Iteration   1: 8.184 ops/ms
Iteration   2: 8.518 ops/ms
Iteration   3: 8.542 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.415 ±(99.9%) 3.649 ops/ms [Average]
  (min, avg, max) = (8.184, 8.415, 8.542), stdev = 0.200
  CI (99.9%): [4.765, 12.064] (assumes normal distribution)


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
# Warmup Iteration   1: 5.840 ops/ms
# Warmup Iteration   2: 8.583 ops/ms
# Warmup Iteration   3: 8.822 ops/ms
Iteration   1: 8.773 ops/ms
Iteration   2: 9.012 ops/ms
Iteration   3: 8.937 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.907 ±(99.9%) 2.236 ops/ms [Average]
  (min, avg, max) = (8.773, 8.907, 9.012), stdev = 0.123
  CI (99.9%): [6.672, 11.143] (assumes normal distribution)


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
# Warmup Iteration   1: 5.452 ops/ms
# Warmup Iteration   2: 8.396 ops/ms
# Warmup Iteration   3: 8.641 ops/ms
Iteration   1: 8.786 ops/ms
Iteration   2: 8.513 ops/ms
Iteration   3: 8.648 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.649 ±(99.9%) 2.485 ops/ms [Average]
  (min, avg, max) = (8.513, 8.649, 8.786), stdev = 0.136
  CI (99.9%): [6.164, 11.134] (assumes normal distribution)


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
# Warmup Iteration   1: 4.199 ops/ms
# Warmup Iteration   2: 6.360 ops/ms
# Warmup Iteration   3: 6.506 ops/ms
Iteration   1: 6.617 ops/ms
Iteration   2: 6.863 ops/ms
Iteration   3: 6.821 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.767 ±(99.9%) 2.399 ops/ms [Average]
  (min, avg, max) = (6.617, 6.767, 6.863), stdev = 0.132
  CI (99.9%): [4.368, 9.167] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 5.416 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.984 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.907 ±(99.9%) 0.009 ms/op
Iteration   1: 3.747 ±(99.9%) 0.004 ms/op
Iteration   2: 3.801 ±(99.9%) 0.003 ms/op
Iteration   3: 3.650 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.733 ±(99.9%) 1.395 ms/op [Average]
  (min, avg, max) = (3.650, 3.733, 3.801), stdev = 0.076
  CI (99.9%): [2.338, 5.128] (assumes normal distribution)


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
# Warmup Iteration   1: 4.955 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.661 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.580 ±(99.9%) 0.004 ms/op
Iteration   1: 3.489 ±(99.9%) 0.003 ms/op
Iteration   2: 3.526 ±(99.9%) 0.003 ms/op
Iteration   3: 3.479 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.498 ±(99.9%) 0.455 ms/op [Average]
  (min, avg, max) = (3.479, 3.498, 3.526), stdev = 0.025
  CI (99.9%): [3.043, 3.954] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 5.193 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.980 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.984 ±(99.9%) 0.004 ms/op
Iteration   1: 3.898 ±(99.9%) 0.004 ms/op
Iteration   2: 3.798 ±(99.9%) 0.007 ms/op
Iteration   3: 3.802 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.833 ±(99.9%) 1.037 ms/op [Average]
  (min, avg, max) = (3.798, 3.833, 3.898), stdev = 0.057
  CI (99.9%): [2.796, 4.869] (assumes normal distribution)


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
# Warmup Iteration   1: 6.309 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 5.466 ±(99.9%) 0.041 ms/op
# Warmup Iteration   3: 4.864 ±(99.9%) 0.015 ms/op
Iteration   1: 4.807 ±(99.9%) 0.020 ms/op
Iteration   2: 4.834 ±(99.9%) 0.023 ms/op
Iteration   3: 4.869 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.837 ±(99.9%) 0.564 ms/op [Average]
  (min, avg, max) = (4.807, 4.837, 4.869), stdev = 0.031
  CI (99.9%): [4.273, 5.400] (assumes normal distribution)


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
# Warmup Iteration   1: 5.827 ±(99.9%) 0.065 ms/op
# Warmup Iteration   2: 4.102 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.878 ±(99.9%) 0.011 ms/op
Iteration   1: 3.804 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.030 ms/op
                 createUser·p0.50:   3.719 ms/op
                 createUser·p0.90:   4.555 ms/op
                 createUser·p0.95:   4.948 ms/op
                 createUser·p0.99:   6.267 ms/op
                 createUser·p0.999:  11.908 ms/op
                 createUser·p0.9999: 19.431 ms/op
                 createUser·p1.00:   20.480 ms/op

Iteration   2: 3.752 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.777 ms/op
                 createUser·p0.50:   3.666 ms/op
                 createUser·p0.90:   4.465 ms/op
                 createUser·p0.95:   4.841 ms/op
                 createUser·p0.99:   6.046 ms/op
                 createUser·p0.999:  12.911 ms/op
                 createUser·p0.9999: 25.131 ms/op
                 createUser·p1.00:   25.723 ms/op

Iteration   3: 3.753 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.830 ms/op
                 createUser·p0.50:   3.662 ms/op
                 createUser·p0.90:   4.555 ms/op
                 createUser·p0.95:   4.981 ms/op
                 createUser·p0.99:   6.511 ms/op
                 createUser·p0.999:  11.452 ms/op
                 createUser·p0.9999: 24.966 ms/op
                 createUser·p1.00:   25.362 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 254644
  mean =      3.770 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6160 
    [ 2.500,  5.000) = 237238 
    [ 5.000,  7.500) = 10193 
    [ 7.500, 10.000) = 661 
    [10.000, 12.500) = 178 
    [12.500, 15.000) = 54 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 64 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 35 
    [25.000, 27.500) = 18 

  Percentiles, ms/op:
      p(0.0000) =      0.777 ms/op
     p(50.0000) =      3.682 ms/op
     p(90.0000) =      4.522 ms/op
     p(95.0000) =      4.923 ms/op
     p(99.0000) =      6.267 ms/op
     p(99.9000) =     11.759 ms/op
     p(99.9900) =     24.482 ms/op
     p(99.9990) =     25.604 ms/op
     p(99.9999) =     25.723 ms/op
    p(100.0000) =     25.723 ms/op


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
# Warmup Iteration   1: 5.360 ±(99.9%) 0.064 ms/op
# Warmup Iteration   2: 3.722 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.618 ±(99.9%) 0.008 ms/op
Iteration   1: 3.555 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.995 ms/op
                 existUser·p0.50:   3.506 ms/op
                 existUser·p0.90:   4.166 ms/op
                 existUser·p0.95:   4.497 ms/op
                 existUser·p0.99:   5.685 ms/op
                 existUser·p0.999:  8.715 ms/op
                 existUser·p0.9999: 15.122 ms/op
                 existUser·p1.00:   15.991 ms/op

Iteration   2: 3.673 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.774 ms/op
                 existUser·p0.50:   3.584 ms/op
                 existUser·p0.90:   4.407 ms/op
                 existUser·p0.95:   4.694 ms/op
                 existUser·p0.99:   6.185 ms/op
                 existUser·p0.999:  11.286 ms/op
                 existUser·p0.9999: 17.123 ms/op
                 existUser·p1.00:   17.695 ms/op

Iteration   3: 3.609 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.754 ms/op
                 existUser·p0.50:   3.531 ms/op
                 existUser·p0.90:   4.186 ms/op
                 existUser·p0.95:   4.506 ms/op
                 existUser·p0.99:   5.734 ms/op
                 existUser·p0.999:  9.421 ms/op
                 existUser·p0.9999: 19.802 ms/op
                 existUser·p1.00:   20.218 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 265728
  mean =      3.612 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4997 
    [ 2.500,  5.000) = 254405 
    [ 5.000,  7.500) = 5411 
    [ 7.500, 10.000) = 703 
    [10.000, 12.500) = 69 
    [12.500, 15.000) = 42 
    [15.000, 17.500) = 71 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.754 ms/op
     p(50.0000) =      3.535 ms/op
     p(90.0000) =      4.260 ms/op
     p(95.0000) =      4.579 ms/op
     p(99.0000) =      5.855 ms/op
     p(99.9000) =      9.601 ms/op
     p(99.9900) =     17.737 ms/op
     p(99.9990) =     20.109 ms/op
     p(99.9999) =     20.218 ms/op
    p(100.0000) =     20.218 ms/op


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
# Warmup Iteration   1: 5.161 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 4.000 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.767 ±(99.9%) 0.010 ms/op
Iteration   1: 3.746 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.716 ms/op
                 getUser·p0.50:   3.678 ms/op
                 getUser·p0.90:   4.497 ms/op
                 getUser·p0.95:   4.882 ms/op
                 getUser·p0.99:   6.201 ms/op
                 getUser·p0.999:  12.577 ms/op
                 getUser·p0.9999: 14.462 ms/op
                 getUser·p1.00:   15.892 ms/op

Iteration   2: 3.749 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.938 ms/op
                 getUser·p0.50:   3.662 ms/op
                 getUser·p0.90:   4.506 ms/op
                 getUser·p0.95:   4.956 ms/op
                 getUser·p0.99:   6.595 ms/op
                 getUser·p0.999:  11.141 ms/op
                 getUser·p0.9999: 16.235 ms/op
                 getUser·p1.00:   18.055 ms/op

Iteration   3: 3.791 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.005 ms/op
                 getUser·p0.50:   3.695 ms/op
                 getUser·p0.90:   4.530 ms/op
                 getUser·p0.95:   4.850 ms/op
                 getUser·p0.99:   6.152 ms/op
                 getUser·p0.999:  10.781 ms/op
                 getUser·p0.9999: 22.890 ms/op
                 getUser·p1.00:   23.069 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 255311
  mean =      3.762 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7382 
    [ 2.500,  5.000) = 237121 
    [ 5.000,  7.500) = 9569 
    [ 7.500, 10.000) = 820 
    [10.000, 12.500) = 205 
    [12.500, 15.000) = 117 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.716 ms/op
     p(50.0000) =      3.678 ms/op
     p(90.0000) =      4.514 ms/op
     p(95.0000) =      4.899 ms/op
     p(99.0000) =      6.316 ms/op
     p(99.9000) =     11.765 ms/op
     p(99.9900) =     22.068 ms/op
     p(99.9990) =     23.036 ms/op
     p(99.9999) =     23.069 ms/op
    p(100.0000) =     23.069 ms/op


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
# Warmup Iteration   1: 6.114 ±(99.9%) 0.070 ms/op
# Warmup Iteration   2: 5.396 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.912 ±(99.9%) 0.015 ms/op
Iteration   1: 4.931 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.733 ms/op
                 listUser·p0.50:   4.661 ms/op
                 listUser·p0.90:   6.431 ms/op
                 listUser·p0.95:   7.389 ms/op
                 listUser·p0.99:   9.421 ms/op
                 listUser·p0.999:  15.452 ms/op
                 listUser·p0.9999: 19.317 ms/op
                 listUser·p1.00:   21.299 ms/op

Iteration   2: 4.994 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.303 ms/op
                 listUser·p0.50:   4.719 ms/op
                 listUser·p0.90:   6.414 ms/op
                 listUser·p0.95:   7.234 ms/op
                 listUser·p0.99:   9.257 ms/op
                 listUser·p0.999:  18.443 ms/op
                 listUser·p0.9999: 29.215 ms/op
                 listUser·p1.00:   30.179 ms/op

Iteration   3: 4.922 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.104 ms/op
                 listUser·p0.50:   4.628 ms/op
                 listUser·p0.90:   6.431 ms/op
                 listUser·p0.95:   7.299 ms/op
                 listUser·p0.99:   9.224 ms/op
                 listUser·p0.999:  24.248 ms/op
                 listUser·p0.9999: 39.581 ms/op
                 listUser·p1.00:   40.042 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 194009
  mean =      4.949 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 130395 
    [ 5.000, 10.000) = 62439 
    [10.000, 15.000) = 867 
    [15.000, 20.000) = 130 
    [20.000, 25.000) = 89 
    [25.000, 30.000) = 55 
    [30.000, 35.000) = 13 
    [35.000, 40.000) = 18 
    [40.000, 45.000) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.104 ms/op
     p(50.0000) =      4.669 ms/op
     p(90.0000) =      6.423 ms/op
     p(95.0000) =      7.315 ms/op
     p(99.0000) =      9.306 ms/op
     p(99.9000) =     18.972 ms/op
     p(99.9900) =     35.206 ms/op
     p(99.9990) =     40.042 ms/op
     p(99.9999) =     40.042 ms/op
    p(100.0000) =     40.042 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.415 ± 3.649  ops/ms
ClientGrpc.existUser                       thrpt       3   8.907 ± 2.236  ops/ms
ClientGrpc.getUser                         thrpt       3   8.649 ± 2.485  ops/ms
ClientGrpc.listUser                        thrpt       3   6.767 ± 2.399  ops/ms
ClientGrpc.createUser                       avgt       3   3.733 ± 1.395   ms/op
ClientGrpc.existUser                        avgt       3   3.498 ± 0.455   ms/op
ClientGrpc.getUser                          avgt       3   3.833 ± 1.037   ms/op
ClientGrpc.listUser                         avgt       3   4.837 ± 0.564   ms/op
ClientGrpc.createUser                     sample  254644   3.770 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.777           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.682           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.522           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.923           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.267           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.759           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          24.482           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          25.723           ms/op
ClientGrpc.existUser                      sample  265728   3.612 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.754           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.535           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.260           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.579           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.855           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.601           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.737           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.218           ms/op
ClientGrpc.getUser                        sample  255311   3.762 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.716           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.678           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.514           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.899           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.316           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.765           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          22.068           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.069           ms/op
ClientGrpc.listUser                       sample  194009   4.949 ± 0.010   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.104           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.669           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.423           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.315           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.306           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.972           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          35.206           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          40.042           ms/op
