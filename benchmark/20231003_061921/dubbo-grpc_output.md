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
# Warmup Iteration   1: 2.857 ops/ms
# Warmup Iteration   2: 6.526 ops/ms
# Warmup Iteration   3: 8.052 ops/ms
Iteration   1: 8.453 ops/ms
Iteration   2: 8.736 ops/ms
Iteration   3: 8.591 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.594 ±(99.9%) 2.580 ops/ms [Average]
  (min, avg, max) = (8.453, 8.594, 8.736), stdev = 0.141
  CI (99.9%): [6.014, 11.173] (assumes normal distribution)


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
# Warmup Iteration   1: 5.826 ops/ms
# Warmup Iteration   2: 8.744 ops/ms
# Warmup Iteration   3: 9.016 ops/ms
Iteration   1: 8.997 ops/ms
Iteration   2: 8.893 ops/ms
Iteration   3: 9.538 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.143 ±(99.9%) 6.321 ops/ms [Average]
  (min, avg, max) = (8.893, 9.143, 9.538), stdev = 0.346
  CI (99.9%): [2.821, 15.464] (assumes normal distribution)


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
# Warmup Iteration   1: 5.351 ops/ms
# Warmup Iteration   2: 7.943 ops/ms
# Warmup Iteration   3: 8.612 ops/ms
Iteration   1: 8.670 ops/ms
Iteration   2: 8.682 ops/ms
Iteration   3: 8.546 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.633 ±(99.9%) 1.374 ops/ms [Average]
  (min, avg, max) = (8.546, 8.633, 8.682), stdev = 0.075
  CI (99.9%): [7.259, 10.007] (assumes normal distribution)


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
# Warmup Iteration   1: 4.338 ops/ms
# Warmup Iteration   2: 5.887 ops/ms
# Warmup Iteration   3: 6.759 ops/ms
Iteration   1: 6.882 ops/ms
Iteration   2: 6.742 ops/ms
Iteration   3: 6.790 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.805 ±(99.9%) 1.294 ops/ms [Average]
  (min, avg, max) = (6.742, 6.805, 6.882), stdev = 0.071
  CI (99.9%): [5.511, 8.098] (assumes normal distribution)


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
# Warmup Iteration   1: 5.548 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.985 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.934 ±(99.9%) 0.008 ms/op
Iteration   1: 3.788 ±(99.9%) 0.003 ms/op
Iteration   2: 3.830 ±(99.9%) 0.002 ms/op
Iteration   3: 3.727 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.781 ±(99.9%) 0.943 ms/op [Average]
  (min, avg, max) = (3.727, 3.781, 3.830), stdev = 0.052
  CI (99.9%): [2.839, 4.724] (assumes normal distribution)


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
# Warmup Iteration   1: 4.967 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.659 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.516 ±(99.9%) 0.003 ms/op
Iteration   1: 3.545 ±(99.9%) 0.004 ms/op
Iteration   2: 3.544 ±(99.9%) 0.002 ms/op
Iteration   3: 3.450 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.513 ±(99.9%) 1.000 ms/op [Average]
  (min, avg, max) = (3.450, 3.513, 3.545), stdev = 0.055
  CI (99.9%): [2.513, 4.513] (assumes normal distribution)


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
# Warmup Iteration   1: 5.547 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.919 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.689 ±(99.9%) 0.004 ms/op
Iteration   1: 3.686 ±(99.9%) 0.002 ms/op
Iteration   2: 3.709 ±(99.9%) 0.005 ms/op
Iteration   3: 3.689 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.695 ±(99.9%) 0.223 ms/op [Average]
  (min, avg, max) = (3.686, 3.695, 3.709), stdev = 0.012
  CI (99.9%): [3.472, 3.917] (assumes normal distribution)


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
# Warmup Iteration   1: 6.596 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 5.007 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.715 ±(99.9%) 0.008 ms/op
Iteration   1: 4.652 ±(99.9%) 0.010 ms/op
Iteration   2: 4.670 ±(99.9%) 0.013 ms/op
Iteration   3: 4.648 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.657 ±(99.9%) 0.214 ms/op [Average]
  (min, avg, max) = (4.648, 4.657, 4.670), stdev = 0.012
  CI (99.9%): [4.443, 4.870] (assumes normal distribution)


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
# Warmup Iteration   1: 5.455 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 3.905 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.746 ±(99.9%) 0.009 ms/op
Iteration   1: 3.716 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.067 ms/op
                 createUser·p0.50:   3.621 ms/op
                 createUser·p0.90:   4.350 ms/op
                 createUser·p0.95:   4.645 ms/op
                 createUser·p0.99:   6.087 ms/op
                 createUser·p0.999:  12.730 ms/op
                 createUser·p0.9999: 20.251 ms/op
                 createUser·p1.00:   20.873 ms/op

Iteration   2: 3.715 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.053 ms/op
                 createUser·p0.50:   3.641 ms/op
                 createUser·p0.90:   4.456 ms/op
                 createUser·p0.95:   4.776 ms/op
                 createUser·p0.99:   6.201 ms/op
                 createUser·p0.999:  13.271 ms/op
                 createUser·p0.9999: 16.036 ms/op
                 createUser·p1.00:   16.548 ms/op

Iteration   3: 3.771 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.161 ms/op
                 createUser·p0.50:   3.707 ms/op
                 createUser·p0.90:   4.407 ms/op
                 createUser·p0.95:   4.620 ms/op
                 createUser·p0.99:   5.949 ms/op
                 createUser·p0.999:  9.890 ms/op
                 createUser·p0.9999: 19.137 ms/op
                 createUser·p1.00:   21.332 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 257048
  mean =      3.734 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3786 
    [ 2.500,  5.000) = 246591 
    [ 5.000,  7.500) = 5426 
    [ 7.500, 10.000) = 916 
    [10.000, 12.500) = 67 
    [12.500, 15.000) = 126 
    [15.000, 17.500) = 42 
    [17.500, 20.000) = 66 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.053 ms/op
     p(50.0000) =      3.654 ms/op
     p(90.0000) =      4.407 ms/op
     p(95.0000) =      4.678 ms/op
     p(99.0000) =      6.103 ms/op
     p(99.9000) =     12.615 ms/op
     p(99.9900) =     20.054 ms/op
     p(99.9990) =     21.248 ms/op
     p(99.9999) =     21.332 ms/op
    p(100.0000) =     21.332 ms/op


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
# Warmup Iteration   1: 4.802 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.681 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.536 ±(99.9%) 0.007 ms/op
Iteration   1: 3.457 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.799 ms/op
                 existUser·p0.50:   3.449 ms/op
                 existUser·p0.90:   4.035 ms/op
                 existUser·p0.95:   4.301 ms/op
                 existUser·p0.99:   5.390 ms/op
                 existUser·p0.999:  9.757 ms/op
                 existUser·p0.9999: 14.877 ms/op
                 existUser·p1.00:   17.138 ms/op

Iteration   2: 3.558 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.684 ms/op
                 existUser·p0.50:   3.502 ms/op
                 existUser·p0.90:   4.243 ms/op
                 existUser·p0.95:   4.514 ms/op
                 existUser·p0.99:   5.579 ms/op
                 existUser·p0.999:  11.387 ms/op
                 existUser·p0.9999: 17.302 ms/op
                 existUser·p1.00:   17.596 ms/op

Iteration   3: 3.549 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.924 ms/op
                 existUser·p0.50:   3.490 ms/op
                 existUser·p0.90:   4.125 ms/op
                 existUser·p0.95:   4.383 ms/op
                 existUser·p0.99:   5.513 ms/op
                 existUser·p0.999:  9.858 ms/op
                 existUser·p0.9999: 24.903 ms/op
                 existUser·p1.00:   25.395 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 272487
  mean =      3.521 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9582 
    [ 2.500,  5.000) = 258598 
    [ 5.000,  7.500) = 3424 
    [ 7.500, 10.000) = 524 
    [10.000, 12.500) = 199 
    [12.500, 15.000) = 58 
    [15.000, 17.500) = 60 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.684 ms/op
     p(50.0000) =      3.478 ms/op
     p(90.0000) =      4.133 ms/op
     p(95.0000) =      4.415 ms/op
     p(99.0000) =      5.489 ms/op
     p(99.9000) =     10.633 ms/op
     p(99.9900) =     23.552 ms/op
     p(99.9990) =     25.282 ms/op
     p(99.9999) =     25.395 ms/op
    p(100.0000) =     25.395 ms/op


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
# Warmup Iteration   1: 5.180 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.905 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.850 ±(99.9%) 0.010 ms/op
Iteration   1: 3.851 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.087 ms/op
                 getUser·p0.50:   3.772 ms/op
                 getUser·p0.90:   4.637 ms/op
                 getUser·p0.95:   4.882 ms/op
                 getUser·p0.99:   5.939 ms/op
                 getUser·p0.999:  9.650 ms/op
                 getUser·p0.9999: 15.658 ms/op
                 getUser·p1.00:   16.007 ms/op

Iteration   2: 3.666 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.024 ms/op
                 getUser·p0.50:   3.629 ms/op
                 getUser·p0.90:   4.301 ms/op
                 getUser·p0.95:   4.538 ms/op
                 getUser·p0.99:   5.281 ms/op
                 getUser·p0.999:  8.794 ms/op
                 getUser·p0.9999: 14.764 ms/op
                 getUser·p1.00:   15.352 ms/op

Iteration   3: 3.722 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.112 ms/op
                 getUser·p0.50:   3.650 ms/op
                 getUser·p0.90:   4.325 ms/op
                 getUser·p0.95:   4.637 ms/op
                 getUser·p0.99:   5.743 ms/op
                 getUser·p0.999:  11.683 ms/op
                 getUser·p0.9999: 18.861 ms/op
                 getUser·p1.00:   20.087 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 256240
  mean =      3.745 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4010 
    [ 2.500,  5.000) = 245909 
    [ 5.000,  7.500) = 5556 
    [ 7.500, 10.000) = 534 
    [10.000, 12.500) = 58 
    [12.500, 15.000) = 90 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 55 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.024 ms/op
     p(50.0000) =      3.674 ms/op
     p(90.0000) =      4.440 ms/op
     p(95.0000) =      4.719 ms/op
     p(99.0000) =      5.669 ms/op
     p(99.9000) =      9.728 ms/op
     p(99.9900) =     18.395 ms/op
     p(99.9990) =     19.302 ms/op
     p(99.9999) =     20.087 ms/op
    p(100.0000) =     20.087 ms/op


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
# Warmup Iteration   1: 7.040 ±(99.9%) 0.077 ms/op
# Warmup Iteration   2: 5.148 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.788 ±(99.9%) 0.015 ms/op
Iteration   1: 4.714 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.247 ms/op
                 listUser·p0.50:   4.596 ms/op
                 listUser·p0.90:   5.267 ms/op
                 listUser·p0.95:   6.210 ms/op
                 listUser·p0.99:   8.124 ms/op
                 listUser·p0.999:  18.558 ms/op
                 listUser·p0.9999: 21.232 ms/op
                 listUser·p1.00:   21.889 ms/op

Iteration   2: 4.710 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.075 ms/op
                 listUser·p0.50:   4.596 ms/op
                 listUser·p0.90:   5.267 ms/op
                 listUser·p0.95:   6.078 ms/op
                 listUser·p0.99:   8.012 ms/op
                 listUser·p0.999:  18.651 ms/op
                 listUser·p0.9999: 22.689 ms/op
                 listUser·p1.00:   25.854 ms/op

Iteration   3: 4.759 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.879 ms/op
                 listUser·p0.50:   4.620 ms/op
                 listUser·p0.90:   5.530 ms/op
                 listUser·p0.95:   6.234 ms/op
                 listUser·p0.99:   7.971 ms/op
                 listUser·p0.999:  19.202 ms/op
                 listUser·p0.9999: 22.777 ms/op
                 listUser·p1.00:   23.265 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 202993
  mean =      4.728 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 210 
    [ 2.500,  5.000) = 162348 
    [ 5.000,  7.500) = 36793 
    [ 7.500, 10.000) = 3040 
    [10.000, 12.500) = 253 
    [12.500, 15.000) = 20 
    [15.000, 17.500) = 50 
    [17.500, 20.000) = 183 
    [20.000, 22.500) = 79 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.879 ms/op
     p(50.0000) =      4.604 ms/op
     p(90.0000) =      5.349 ms/op
     p(95.0000) =      6.185 ms/op
     p(99.0000) =      8.028 ms/op
     p(99.9000) =     18.940 ms/op
     p(99.9900) =     22.426 ms/op
     p(99.9990) =     23.329 ms/op
     p(99.9999) =     25.854 ms/op
    p(100.0000) =     25.854 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.594 ± 2.580  ops/ms
ClientGrpc.existUser                       thrpt       3   9.143 ± 6.321  ops/ms
ClientGrpc.getUser                         thrpt       3   8.633 ± 1.374  ops/ms
ClientGrpc.listUser                        thrpt       3   6.805 ± 1.294  ops/ms
ClientGrpc.createUser                       avgt       3   3.781 ± 0.943   ms/op
ClientGrpc.existUser                        avgt       3   3.513 ± 1.000   ms/op
ClientGrpc.getUser                          avgt       3   3.695 ± 0.223   ms/op
ClientGrpc.listUser                         avgt       3   4.657 ± 0.214   ms/op
ClientGrpc.createUser                     sample  257048   3.734 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           1.053           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.654           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.407           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.678           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.103           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.615           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.054           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.332           ms/op
ClientGrpc.existUser                      sample  272487   3.521 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.684           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.478           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.133           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.415           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.489           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.633           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          23.552           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          25.395           ms/op
ClientGrpc.getUser                        sample  256240   3.745 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           1.024           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.674           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.440           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.719           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.669           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.728           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.395           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.087           ms/op
ClientGrpc.listUser                       sample  202993   4.728 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.879           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.604           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.349           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.185           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.028           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.940           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.426           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.854           ms/op
