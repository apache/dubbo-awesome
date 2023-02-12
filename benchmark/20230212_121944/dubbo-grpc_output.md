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
# Warmup Iteration   1: 2.319 ops/ms
# Warmup Iteration   2: 5.266 ops/ms
# Warmup Iteration   3: 6.683 ops/ms
Iteration   1: 6.784 ops/ms
Iteration   2: 6.773 ops/ms
Iteration   3: 6.849 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  6.802 ±(99.9%) 0.747 ops/ms [Average]
  (min, avg, max) = (6.773, 6.802, 6.849), stdev = 0.041
  CI (99.9%): [6.055, 7.549] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.435 ops/ms
# Warmup Iteration   2: 6.776 ops/ms
# Warmup Iteration   3: 7.259 ops/ms
Iteration   1: 7.118 ops/ms
Iteration   2: 7.398 ops/ms
Iteration   3: 7.287 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.268 ±(99.9%) 2.570 ops/ms [Average]
  (min, avg, max) = (7.118, 7.268, 7.398), stdev = 0.141
  CI (99.9%): [4.697, 9.838] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 4.105 ops/ms
# Warmup Iteration   2: 6.491 ops/ms
# Warmup Iteration   3: 6.710 ops/ms
Iteration   1: 6.753 ops/ms
Iteration   2: 6.824 ops/ms
Iteration   3: 6.975 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  6.850 ±(99.9%) 2.067 ops/ms [Average]
  (min, avg, max) = (6.753, 6.850, 6.975), stdev = 0.113
  CI (99.9%): [4.783, 8.917] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 3.363 ops/ms
# Warmup Iteration   2: 4.935 ops/ms
# Warmup Iteration   3: 5.258 ops/ms
Iteration   1: 5.334 ops/ms
Iteration   2: 5.400 ops/ms
Iteration   3: 5.330 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.355 ±(99.9%) 0.719 ops/ms [Average]
  (min, avg, max) = (5.330, 5.355, 5.400), stdev = 0.039
  CI (99.9%): [4.636, 6.073] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 6.922 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.902 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.713 ±(99.9%) 0.004 ms/op
Iteration   1: 4.782 ±(99.9%) 0.003 ms/op
Iteration   2: 4.751 ±(99.9%) 0.004 ms/op
Iteration   3: 4.837 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.790 ±(99.9%) 0.788 ms/op [Average]
  (min, avg, max) = (4.751, 4.790, 4.837), stdev = 0.043
  CI (99.9%): [4.002, 5.578] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 6.336 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.615 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.509 ±(99.9%) 0.006 ms/op
Iteration   1: 4.366 ±(99.9%) 0.004 ms/op
Iteration   2: 4.357 ±(99.9%) 0.004 ms/op
Iteration   3: 4.447 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.390 ±(99.9%) 0.903 ms/op [Average]
  (min, avg, max) = (4.357, 4.390, 4.447), stdev = 0.050
  CI (99.9%): [3.487, 5.293] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 6.759 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 4.978 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.771 ±(99.9%) 0.004 ms/op
Iteration   1: 4.887 ±(99.9%) 0.005 ms/op
Iteration   2: 4.838 ±(99.9%) 0.003 ms/op
Iteration   3: 4.878 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.868 ±(99.9%) 0.476 ms/op [Average]
  (min, avg, max) = (4.838, 4.868, 4.887), stdev = 0.026
  CI (99.9%): [4.391, 5.344] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 7.947 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 6.481 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 6.071 ±(99.9%) 0.026 ms/op
Iteration   1: 5.979 ±(99.9%) 0.013 ms/op
Iteration   2: 5.812 ±(99.9%) 0.009 ms/op
Iteration   3: 5.783 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.858 ±(99.9%) 1.929 ms/op [Average]
  (min, avg, max) = (5.783, 5.858, 5.979), stdev = 0.106
  CI (99.9%): [3.929, 7.787] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 7.079 ±(99.9%) 0.093 ms/op
# Warmup Iteration   2: 4.897 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.942 ±(99.9%) 0.016 ms/op
Iteration   1: 4.783 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.065 ms/op
                 createUser·p0.50:   4.645 ms/op
                 createUser·p0.90:   6.136 ms/op
                 createUser·p0.95:   6.742 ms/op
                 createUser·p0.99:   8.815 ms/op
                 createUser·p0.999:  12.149 ms/op
                 createUser·p0.9999: 17.594 ms/op
                 createUser·p1.00:   18.088 ms/op

Iteration   2: 4.769 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.137 ms/op
                 createUser·p0.50:   4.694 ms/op
                 createUser·p0.90:   6.087 ms/op
                 createUser·p0.95:   6.504 ms/op
                 createUser·p0.99:   7.627 ms/op
                 createUser·p0.999:  11.108 ms/op
                 createUser·p0.9999: 18.416 ms/op
                 createUser·p1.00:   18.809 ms/op

Iteration   3: 4.766 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.194 ms/op
                 createUser·p0.50:   4.686 ms/op
                 createUser·p0.90:   6.070 ms/op
                 createUser·p0.95:   6.447 ms/op
                 createUser·p0.99:   7.594 ms/op
                 createUser·p0.999:  13.426 ms/op
                 createUser·p0.9999: 22.438 ms/op
                 createUser·p1.00:   22.675 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 200991
  mean =      4.773 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2475 
    [ 2.500,  5.000) = 122285 
    [ 5.000,  7.500) = 73002 
    [ 7.500, 10.000) = 2657 
    [10.000, 12.500) = 395 
    [12.500, 15.000) = 49 
    [15.000, 17.500) = 36 
    [17.500, 20.000) = 58 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.065 ms/op
     p(50.0000) =      4.678 ms/op
     p(90.0000) =      6.095 ms/op
     p(95.0000) =      6.545 ms/op
     p(99.0000) =      8.077 ms/op
     p(99.9000) =     12.141 ms/op
     p(99.9900) =     21.591 ms/op
     p(99.9990) =     22.643 ms/op
     p(99.9999) =     22.675 ms/op
    p(100.0000) =     22.675 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.029 ±(99.9%) 0.073 ms/op
# Warmup Iteration   2: 4.730 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.377 ±(99.9%) 0.014 ms/op
Iteration   1: 4.367 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.053 ms/op
                 existUser·p0.50:   4.268 ms/op
                 existUser·p0.90:   5.448 ms/op
                 existUser·p0.95:   5.898 ms/op
                 existUser·p0.99:   7.862 ms/op
                 existUser·p0.999:  13.140 ms/op
                 existUser·p0.9999: 19.672 ms/op
                 existUser·p1.00:   20.251 ms/op

Iteration   2: 4.404 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.079 ms/op
                 existUser·p0.50:   4.317 ms/op
                 existUser·p0.90:   5.595 ms/op
                 existUser·p0.95:   5.988 ms/op
                 existUser·p0.99:   7.081 ms/op
                 existUser·p0.999:  11.120 ms/op
                 existUser·p0.9999: 20.349 ms/op
                 existUser·p1.00:   20.611 ms/op

Iteration   3: 4.544 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   1.019 ms/op
                 existUser·p0.50:   4.440 ms/op
                 existUser·p0.90:   5.743 ms/op
                 existUser·p0.95:   6.201 ms/op
                 existUser·p0.99:   8.036 ms/op
                 existUser·p0.999:  14.997 ms/op
                 existUser·p0.9999: 23.822 ms/op
                 existUser·p1.00:   24.674 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 216528
  mean =      4.437 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3488 
    [ 2.500,  5.000) = 160388 
    [ 5.000,  7.500) = 50384 
    [ 7.500, 10.000) = 1639 
    [10.000, 12.500) = 351 
    [12.500, 15.000) = 123 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 51 
    [20.000, 22.500) = 56 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.019 ms/op
     p(50.0000) =      4.334 ms/op
     p(90.0000) =      5.603 ms/op
     p(95.0000) =      6.038 ms/op
     p(99.0000) =      7.578 ms/op
     p(99.9000) =     13.763 ms/op
     p(99.9900) =     23.364 ms/op
     p(99.9990) =     24.352 ms/op
     p(99.9999) =     24.674 ms/op
    p(100.0000) =     24.674 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 6.722 ±(99.9%) 0.082 ms/op
# Warmup Iteration   2: 4.926 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.729 ±(99.9%) 0.015 ms/op
Iteration   1: 4.668 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.311 ms/op
                 getUser·p0.50:   4.588 ms/op
                 getUser·p0.90:   5.988 ms/op
                 getUser·p0.95:   6.390 ms/op
                 getUser·p0.99:   7.627 ms/op
                 getUser·p0.999:  10.887 ms/op
                 getUser·p0.9999: 16.807 ms/op
                 getUser·p1.00:   18.481 ms/op

Iteration   2: 4.747 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.073 ms/op
                 getUser·p0.50:   4.661 ms/op
                 getUser·p0.90:   6.038 ms/op
                 getUser·p0.95:   6.447 ms/op
                 getUser·p0.99:   7.660 ms/op
                 getUser·p0.999:  14.084 ms/op
                 getUser·p0.9999: 19.300 ms/op
                 getUser·p1.00:   19.366 ms/op

Iteration   3: 4.719 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.083 ms/op
                 getUser·p0.50:   4.637 ms/op
                 getUser·p0.90:   6.054 ms/op
                 getUser·p0.95:   6.480 ms/op
                 getUser·p0.99:   7.610 ms/op
                 getUser·p0.999:  11.312 ms/op
                 getUser·p0.9999: 22.424 ms/op
                 getUser·p1.00:   24.117 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 203659
  mean =      4.711 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3082 
    [ 2.500,  5.000) = 126087 
    [ 5.000,  7.500) = 72201 
    [ 7.500, 10.000) = 1798 
    [10.000, 12.500) = 295 
    [12.500, 15.000) = 96 
    [15.000, 17.500) = 48 
    [17.500, 20.000) = 45 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.073 ms/op
     p(50.0000) =      4.628 ms/op
     p(90.0000) =      6.029 ms/op
     p(95.0000) =      6.439 ms/op
     p(99.0000) =      7.627 ms/op
     p(99.9000) =     12.337 ms/op
     p(99.9900) =     19.288 ms/op
     p(99.9990) =     23.349 ms/op
     p(99.9999) =     24.117 ms/op
    p(100.0000) =     24.117 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 7.511 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 6.407 ±(99.9%) 0.031 ms/op
# Warmup Iteration   3: 5.957 ±(99.9%) 0.022 ms/op
Iteration   1: 5.928 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.489 ms/op
                 listUser·p0.50:   5.636 ms/op
                 listUser·p0.90:   7.725 ms/op
                 listUser·p0.95:   8.684 ms/op
                 listUser·p0.99:   11.026 ms/op
                 listUser·p0.999:  16.972 ms/op
                 listUser·p0.9999: 19.648 ms/op
                 listUser·p1.00:   20.021 ms/op

Iteration   2: 5.772 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   2.150 ms/op
                 listUser·p0.50:   5.538 ms/op
                 listUser·p0.90:   7.315 ms/op
                 listUser·p0.95:   8.200 ms/op
                 listUser·p0.99:   10.229 ms/op
                 listUser·p0.999:  17.286 ms/op
                 listUser·p0.9999: 20.521 ms/op
                 listUser·p1.00:   21.004 ms/op

Iteration   3: 5.719 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.026 ms/op
                 listUser·p0.50:   5.464 ms/op
                 listUser·p0.90:   7.406 ms/op
                 listUser·p0.95:   8.233 ms/op
                 listUser·p0.99:   10.158 ms/op
                 listUser·p0.999:  21.010 ms/op
                 listUser·p0.9999: 26.818 ms/op
                 listUser·p1.00:   29.327 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 165429
  mean =      5.805 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 49 
    [ 2.500,  5.000) = 44398 
    [ 5.000,  7.500) = 104681 
    [ 7.500, 10.000) = 13985 
    [10.000, 12.500) = 1744 
    [12.500, 15.000) = 290 
    [15.000, 17.500) = 101 
    [17.500, 20.000) = 99 
    [20.000, 22.500) = 42 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      1.026 ms/op
     p(50.0000) =      5.546 ms/op
     p(90.0000) =      7.479 ms/op
     p(95.0000) =      8.372 ms/op
     p(99.0000) =     10.502 ms/op
     p(99.9000) =     17.943 ms/op
     p(99.9900) =     24.797 ms/op
     p(99.9990) =     28.556 ms/op
     p(99.9999) =     29.327 ms/op
    p(100.0000) =     29.327 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   6.802 ± 0.747  ops/ms
ClientGrpc.existUser                       thrpt       3   7.268 ± 2.570  ops/ms
ClientGrpc.getUser                         thrpt       3   6.850 ± 2.067  ops/ms
ClientGrpc.listUser                        thrpt       3   5.355 ± 0.719  ops/ms
ClientGrpc.createUser                       avgt       3   4.790 ± 0.788   ms/op
ClientGrpc.existUser                        avgt       3   4.390 ± 0.903   ms/op
ClientGrpc.getUser                          avgt       3   4.868 ± 0.476   ms/op
ClientGrpc.listUser                         avgt       3   5.858 ± 1.929   ms/op
ClientGrpc.createUser                     sample  200991   4.773 ± 0.008   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           1.065           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.678           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           6.095           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           6.545           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           8.077           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.141           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.591           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.675           ms/op
ClientGrpc.existUser                      sample  216528   4.437 ± 0.008   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           1.019           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.334           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.603           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           6.038           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.578           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          13.763           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          23.364           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          24.674           ms/op
ClientGrpc.getUser                        sample  203659   4.711 ± 0.008   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           1.073           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.628           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           6.029           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.439           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.627           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.337           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.288           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          24.117           ms/op
ClientGrpc.listUser                       sample  165429   5.805 ± 0.011   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.026           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.546           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.479           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.372           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.502           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.943           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.797           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          29.327           ms/op
