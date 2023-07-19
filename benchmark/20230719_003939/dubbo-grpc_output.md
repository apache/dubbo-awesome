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
# Warmup Iteration   1: 2.660 ops/ms
# Warmup Iteration   2: 6.817 ops/ms
# Warmup Iteration   3: 8.103 ops/ms
Iteration   1: 8.270 ops/ms
Iteration   2: 8.697 ops/ms
Iteration   3: 8.389 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.452 ±(99.9%) 4.021 ops/ms [Average]
  (min, avg, max) = (8.270, 8.452, 8.697), stdev = 0.220
  CI (99.9%): [4.431, 12.474] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 5.393 ops/ms
# Warmup Iteration   2: 8.599 ops/ms
# Warmup Iteration   3: 9.004 ops/ms
Iteration   1: 9.355 ops/ms
Iteration   2: 9.144 ops/ms
Iteration   3: 9.154 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.218 ±(99.9%) 2.178 ops/ms [Average]
  (min, avg, max) = (9.144, 9.218, 9.355), stdev = 0.119
  CI (99.9%): [7.039, 11.396] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:54
# Fork: 1 of 1
# Warmup Iteration   1: 4.911 ops/ms
# Warmup Iteration   2: 7.554 ops/ms
# Warmup Iteration   3: 8.161 ops/ms
Iteration   1: 8.473 ops/ms
Iteration   2: 8.452 ops/ms
Iteration   3: 8.606 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.510 ±(99.9%) 1.528 ops/ms [Average]
  (min, avg, max) = (8.452, 8.510, 8.606), stdev = 0.084
  CI (99.9%): [6.982, 10.038] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.935 ops/ms
# Warmup Iteration   2: 6.137 ops/ms
# Warmup Iteration   3: 6.400 ops/ms
Iteration   1: 6.583 ops/ms
Iteration   2: 6.609 ops/ms
Iteration   3: 6.716 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.636 ±(99.9%) 1.281 ops/ms [Average]
  (min, avg, max) = (6.583, 6.636, 6.716), stdev = 0.070
  CI (99.9%): [5.355, 7.917] (assumes normal distribution)


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
# Warmup Iteration   1: 5.972 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.123 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.926 ±(99.9%) 0.006 ms/op
Iteration   1: 3.749 ±(99.9%) 0.004 ms/op
Iteration   2: 3.636 ±(99.9%) 0.003 ms/op
Iteration   3: 3.707 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.697 ±(99.9%) 1.043 ms/op [Average]
  (min, avg, max) = (3.636, 3.697, 3.749), stdev = 0.057
  CI (99.9%): [2.654, 4.741] (assumes normal distribution)


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
# Warmup Iteration   1: 5.187 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.815 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.700 ±(99.9%) 0.004 ms/op
Iteration   1: 3.614 ±(99.9%) 0.003 ms/op
Iteration   2: 3.556 ±(99.9%) 0.002 ms/op
Iteration   3: 3.484 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.551 ±(99.9%) 1.189 ms/op [Average]
  (min, avg, max) = (3.484, 3.551, 3.614), stdev = 0.065
  CI (99.9%): [2.362, 4.740] (assumes normal distribution)


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
# Warmup Iteration   1: 5.651 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.928 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.742 ±(99.9%) 0.004 ms/op
Iteration   1: 3.723 ±(99.9%) 0.003 ms/op
Iteration   2: 3.719 ±(99.9%) 0.003 ms/op
Iteration   3: 3.785 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.742 ±(99.9%) 0.679 ms/op [Average]
  (min, avg, max) = (3.719, 3.742, 3.785), stdev = 0.037
  CI (99.9%): [3.063, 4.421] (assumes normal distribution)


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
# Warmup Iteration   1: 7.687 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 5.233 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 4.826 ±(99.9%) 0.013 ms/op
Iteration   1: 4.834 ±(99.9%) 0.011 ms/op
Iteration   2: 4.801 ±(99.9%) 0.011 ms/op
Iteration   3: 4.903 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.846 ±(99.9%) 0.947 ms/op [Average]
  (min, avg, max) = (4.801, 4.846, 4.903), stdev = 0.052
  CI (99.9%): [3.899, 5.793] (assumes normal distribution)


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
# Warmup Iteration   1: 6.110 ±(99.9%) 0.068 ms/op
# Warmup Iteration   2: 4.082 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.769 ±(99.9%) 0.010 ms/op
Iteration   1: 3.742 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.921 ms/op
                 createUser·p0.50:   3.617 ms/op
                 createUser·p0.90:   4.661 ms/op
                 createUser·p0.95:   5.095 ms/op
                 createUser·p0.99:   6.463 ms/op
                 createUser·p0.999:  13.606 ms/op
                 createUser·p0.9999: 16.555 ms/op
                 createUser·p1.00:   16.974 ms/op

Iteration   2: 3.618 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.775 ms/op
                 createUser·p0.50:   3.531 ms/op
                 createUser·p0.90:   4.456 ms/op
                 createUser·p0.95:   4.932 ms/op
                 createUser·p0.99:   6.382 ms/op
                 createUser·p0.999:  14.811 ms/op
                 createUser·p0.9999: 18.636 ms/op
                 createUser·p1.00:   21.922 ms/op

Iteration   3: 3.707 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.947 ms/op
                 createUser·p0.50:   3.596 ms/op
                 createUser·p0.90:   4.563 ms/op
                 createUser·p0.95:   4.973 ms/op
                 createUser·p0.99:   6.529 ms/op
                 createUser·p0.999:  15.003 ms/op
                 createUser·p0.9999: 20.713 ms/op
                 createUser·p1.00:   21.463 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 260374
  mean =      3.688 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7902 
    [ 2.500,  5.000) = 239308 
    [ 5.000,  7.500) = 11790 
    [ 7.500, 10.000) = 788 
    [10.000, 12.500) = 198 
    [12.500, 15.000) = 175 
    [15.000, 17.500) = 159 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.775 ms/op
     p(50.0000) =      3.580 ms/op
     p(90.0000) =      4.563 ms/op
     p(95.0000) =      5.005 ms/op
     p(99.0000) =      6.439 ms/op
     p(99.9000) =     14.301 ms/op
     p(99.9900) =     20.312 ms/op
     p(99.9990) =     21.731 ms/op
     p(99.9999) =     21.922 ms/op
    p(100.0000) =     21.922 ms/op


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
# Warmup Iteration   1: 5.332 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 3.720 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.601 ±(99.9%) 0.010 ms/op
Iteration   1: 3.376 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.907 ms/op
                 existUser·p0.50:   3.346 ms/op
                 existUser·p0.90:   4.268 ms/op
                 existUser·p0.95:   4.678 ms/op
                 existUser·p0.99:   5.825 ms/op
                 existUser·p0.999:  8.737 ms/op
                 existUser·p0.9999: 16.377 ms/op
                 existUser·p1.00:   17.269 ms/op

Iteration   2: 3.496 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.727 ms/op
                 existUser·p0.50:   3.408 ms/op
                 existUser·p0.90:   4.284 ms/op
                 existUser·p0.95:   4.661 ms/op
                 existUser·p0.99:   5.874 ms/op
                 existUser·p0.999:  9.437 ms/op
                 existUser·p0.9999: 18.181 ms/op
                 existUser·p1.00:   18.514 ms/op

Iteration   3: 3.615 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.969 ms/op
                 existUser·p0.50:   3.494 ms/op
                 existUser·p0.90:   4.448 ms/op
                 existUser·p0.95:   4.822 ms/op
                 existUser·p0.99:   6.660 ms/op
                 existUser·p0.999:  13.604 ms/op
                 existUser·p0.9999: 19.796 ms/op
                 existUser·p1.00:   20.120 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 274850
  mean =      3.493 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13204 
    [ 2.500,  5.000) = 252870 
    [ 5.000,  7.500) = 7717 
    [ 7.500, 10.000) = 783 
    [10.000, 12.500) = 116 
    [12.500, 15.000) = 16 
    [15.000, 17.500) = 57 
    [17.500, 20.000) = 85 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.727 ms/op
     p(50.0000) =      3.412 ms/op
     p(90.0000) =      4.342 ms/op
     p(95.0000) =      4.727 ms/op
     p(99.0000) =      6.054 ms/op
     p(99.9000) =     10.013 ms/op
     p(99.9900) =     19.268 ms/op
     p(99.9990) =     19.997 ms/op
     p(99.9999) =     20.120 ms/op
    p(100.0000) =     20.120 ms/op


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
# Warmup Iteration   1: 5.941 ±(99.9%) 0.068 ms/op
# Warmup Iteration   2: 3.953 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.808 ±(99.9%) 0.011 ms/op
Iteration   1: 3.659 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.024 ms/op
                 getUser·p0.50:   3.559 ms/op
                 getUser·p0.90:   4.538 ms/op
                 getUser·p0.95:   4.997 ms/op
                 getUser·p0.99:   6.389 ms/op
                 getUser·p0.999:  9.126 ms/op
                 getUser·p0.9999: 16.917 ms/op
                 getUser·p1.00:   17.302 ms/op

Iteration   2: 3.825 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.026 ms/op
                 getUser·p0.50:   3.727 ms/op
                 getUser·p0.90:   4.661 ms/op
                 getUser·p0.95:   5.005 ms/op
                 getUser·p0.99:   6.300 ms/op
                 getUser·p0.999:  13.132 ms/op
                 getUser·p0.9999: 26.530 ms/op
                 getUser·p1.00:   27.361 ms/op

Iteration   3: 3.663 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.047 ms/op
                 getUser·p0.50:   3.559 ms/op
                 getUser·p0.90:   4.563 ms/op
                 getUser·p0.95:   5.005 ms/op
                 getUser·p0.99:   6.371 ms/op
                 getUser·p0.999:  9.601 ms/op
                 getUser·p0.9999: 18.776 ms/op
                 getUser·p1.00:   19.071 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 258660
  mean =      3.714 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7235 
    [ 2.500,  5.000) = 238449 
    [ 5.000,  7.500) = 11879 
    [ 7.500, 10.000) = 820 
    [10.000, 12.500) = 86 
    [12.500, 15.000) = 63 
    [15.000, 17.500) = 33 
    [17.500, 20.000) = 47 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      1.024 ms/op
     p(50.0000) =      3.609 ms/op
     p(90.0000) =      4.596 ms/op
     p(95.0000) =      5.005 ms/op
     p(99.0000) =      6.349 ms/op
     p(99.9000) =     10.426 ms/op
     p(99.9900) =     25.797 ms/op
     p(99.9990) =     26.997 ms/op
     p(99.9999) =     27.361 ms/op
    p(100.0000) =     27.361 ms/op


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
# Warmup Iteration   1: 8.033 ±(99.9%) 0.096 ms/op
# Warmup Iteration   2: 5.292 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 5.137 ±(99.9%) 0.019 ms/op
Iteration   1: 5.109 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.735 ms/op
                 listUser·p0.50:   4.817 ms/op
                 listUser·p0.90:   6.816 ms/op
                 listUser·p0.95:   7.725 ms/op
                 listUser·p0.99:   9.688 ms/op
                 listUser·p0.999:  16.477 ms/op
                 listUser·p0.9999: 18.595 ms/op
                 listUser·p1.00:   20.087 ms/op

Iteration   2: 5.172 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.450 ms/op
                 listUser·p0.50:   4.891 ms/op
                 listUser·p0.90:   6.865 ms/op
                 listUser·p0.95:   7.692 ms/op
                 listUser·p0.99:   9.814 ms/op
                 listUser·p0.999:  22.315 ms/op
                 listUser·p0.9999: 25.717 ms/op
                 listUser·p1.00:   26.313 ms/op

Iteration   3: 5.128 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   0.476 ms/op
                 listUser·p0.50:   4.801 ms/op
                 listUser·p0.90:   6.914 ms/op
                 listUser·p0.95:   7.832 ms/op
                 listUser·p0.99:   10.437 ms/op
                 listUser·p0.999:  20.646 ms/op
                 listUser·p0.9999: 28.788 ms/op
                 listUser·p1.00:   30.278 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 187056
  mean =      5.136 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 542 
    [ 2.500,  5.000) = 106457 
    [ 5.000,  7.500) = 68544 
    [ 7.500, 10.000) = 9721 
    [10.000, 12.500) = 1143 
    [12.500, 15.000) = 314 
    [15.000, 17.500) = 113 
    [17.500, 20.000) = 59 
    [20.000, 22.500) = 62 
    [22.500, 25.000) = 44 
    [25.000, 27.500) = 33 
    [27.500, 30.000) = 21 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.476 ms/op
     p(50.0000) =      4.833 ms/op
     p(90.0000) =      6.865 ms/op
     p(95.0000) =      7.758 ms/op
     p(99.0000) =      9.945 ms/op
     p(99.9000) =     18.348 ms/op
     p(99.9900) =     27.797 ms/op
     p(99.9990) =     30.192 ms/op
     p(99.9999) =     30.278 ms/op
    p(100.0000) =     30.278 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.452 ± 4.021  ops/ms
ClientGrpc.existUser                       thrpt       3   9.218 ± 2.178  ops/ms
ClientGrpc.getUser                         thrpt       3   8.510 ± 1.528  ops/ms
ClientGrpc.listUser                        thrpt       3   6.636 ± 1.281  ops/ms
ClientGrpc.createUser                       avgt       3   3.697 ± 1.043   ms/op
ClientGrpc.existUser                        avgt       3   3.551 ± 1.189   ms/op
ClientGrpc.getUser                          avgt       3   3.742 ± 0.679   ms/op
ClientGrpc.listUser                         avgt       3   4.846 ± 0.947   ms/op
ClientGrpc.createUser                     sample  260374   3.688 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.775           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.580           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.563           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.005           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.439           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          14.301           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.312           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.922           ms/op
ClientGrpc.existUser                      sample  274850   3.493 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.727           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.412           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.342           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.727           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.054           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.013           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.268           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.120           ms/op
ClientGrpc.getUser                        sample  258660   3.714 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           1.024           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.609           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.596           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.005           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.349           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.426           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          25.797           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          27.361           ms/op
ClientGrpc.listUser                       sample  187056   5.136 ± 0.011   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.476           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.833           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.865           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.758           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.945           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.348           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          27.797           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          30.278           ms/op
