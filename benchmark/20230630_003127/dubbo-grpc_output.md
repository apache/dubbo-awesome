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
# Warmup Iteration   1: 3.428 ops/ms
# Warmup Iteration   2: 6.890 ops/ms
# Warmup Iteration   3: 8.263 ops/ms
Iteration   1: 8.583 ops/ms
Iteration   2: 8.524 ops/ms
Iteration   3: 8.771 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.626 ±(99.9%) 2.348 ops/ms [Average]
  (min, avg, max) = (8.524, 8.626, 8.771), stdev = 0.129
  CI (99.9%): [6.278, 10.974] (assumes normal distribution)


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
# Warmup Iteration   1: 6.230 ops/ms
# Warmup Iteration   2: 8.612 ops/ms
# Warmup Iteration   3: 9.441 ops/ms
Iteration   1: 9.412 ops/ms
Iteration   2: 9.571 ops/ms
Iteration   3: 9.463 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.482 ±(99.9%) 1.486 ops/ms [Average]
  (min, avg, max) = (9.412, 9.482, 9.571), stdev = 0.081
  CI (99.9%): [7.996, 10.968] (assumes normal distribution)


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
# Warmup Iteration   1: 5.611 ops/ms
# Warmup Iteration   2: 8.671 ops/ms
# Warmup Iteration   3: 8.910 ops/ms
Iteration   1: 8.935 ops/ms
Iteration   2: 9.180 ops/ms
Iteration   3: 9.015 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.043 ±(99.9%) 2.278 ops/ms [Average]
  (min, avg, max) = (8.935, 9.043, 9.180), stdev = 0.125
  CI (99.9%): [6.766, 11.321] (assumes normal distribution)


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
# Warmup Iteration   1: 4.646 ops/ms
# Warmup Iteration   2: 6.349 ops/ms
# Warmup Iteration   3: 6.815 ops/ms
Iteration   1: 6.922 ops/ms
Iteration   2: 6.853 ops/ms
Iteration   3: 6.875 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.883 ±(99.9%) 0.642 ops/ms [Average]
  (min, avg, max) = (6.853, 6.883, 6.922), stdev = 0.035
  CI (99.9%): [6.242, 7.525] (assumes normal distribution)


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
# Warmup Iteration   1: 5.163 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.782 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.691 ±(99.9%) 0.002 ms/op
Iteration   1: 3.653 ±(99.9%) 0.004 ms/op
Iteration   2: 3.514 ±(99.9%) 0.003 ms/op
Iteration   3: 3.582 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.583 ±(99.9%) 1.260 ms/op [Average]
  (min, avg, max) = (3.514, 3.583, 3.653), stdev = 0.069
  CI (99.9%): [2.323, 4.843] (assumes normal distribution)


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
# Warmup Iteration   1: 4.625 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.661 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.377 ±(99.9%) 0.007 ms/op
Iteration   1: 3.394 ±(99.9%) 0.005 ms/op
Iteration   2: 3.408 ±(99.9%) 0.003 ms/op
Iteration   3: 3.404 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.402 ±(99.9%) 0.134 ms/op [Average]
  (min, avg, max) = (3.394, 3.402, 3.408), stdev = 0.007
  CI (99.9%): [3.268, 3.536] (assumes normal distribution)


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
# Warmup Iteration   1: 5.305 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.813 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.819 ±(99.9%) 0.009 ms/op
Iteration   1: 3.778 ±(99.9%) 0.005 ms/op
Iteration   2: 3.686 ±(99.9%) 0.002 ms/op
Iteration   3: 3.746 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.737 ±(99.9%) 0.855 ms/op [Average]
  (min, avg, max) = (3.686, 3.737, 3.778), stdev = 0.047
  CI (99.9%): [2.882, 4.591] (assumes normal distribution)


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
# Warmup Iteration   1: 6.477 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 5.017 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.797 ±(99.9%) 0.011 ms/op
Iteration   1: 4.800 ±(99.9%) 0.015 ms/op
Iteration   2: 4.624 ±(99.9%) 0.010 ms/op
Iteration   3: 4.754 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.726 ±(99.9%) 1.656 ms/op [Average]
  (min, avg, max) = (4.624, 4.726, 4.800), stdev = 0.091
  CI (99.9%): [3.070, 6.381] (assumes normal distribution)


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
# Warmup Iteration   1: 5.207 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 3.915 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.761 ±(99.9%) 0.010 ms/op
Iteration   1: 3.722 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.902 ms/op
                 createUser·p0.50:   3.654 ms/op
                 createUser·p0.90:   4.465 ms/op
                 createUser·p0.95:   4.784 ms/op
                 createUser·p0.99:   5.923 ms/op
                 createUser·p0.999:  8.962 ms/op
                 createUser·p0.9999: 14.766 ms/op
                 createUser·p1.00:   15.073 ms/op

Iteration   2: 3.675 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.833 ms/op
                 createUser·p0.50:   3.609 ms/op
                 createUser·p0.90:   4.350 ms/op
                 createUser·p0.95:   4.710 ms/op
                 createUser·p0.99:   5.964 ms/op
                 createUser·p0.999:  9.920 ms/op
                 createUser·p0.9999: 19.384 ms/op
                 createUser·p1.00:   19.792 ms/op

Iteration   3: 3.632 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.851 ms/op
                 createUser·p0.50:   3.543 ms/op
                 createUser·p0.90:   4.141 ms/op
                 createUser·p0.95:   4.522 ms/op
                 createUser·p0.99:   6.136 ms/op
                 createUser·p0.999:  18.121 ms/op
                 createUser·p0.9999: 25.899 ms/op
                 createUser·p1.00:   26.280 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 261256
  mean =      3.676 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5632 
    [ 2.500,  5.000) = 247747 
    [ 5.000,  7.500) = 6778 
    [ 7.500, 10.000) = 752 
    [10.000, 12.500) = 77 
    [12.500, 15.000) = 128 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 65 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 19 

  Percentiles, ms/op:
      p(0.0000) =      0.833 ms/op
     p(50.0000) =      3.596 ms/op
     p(90.0000) =      4.342 ms/op
     p(95.0000) =      4.694 ms/op
     p(99.0000) =      6.005 ms/op
     p(99.9000) =     12.710 ms/op
     p(99.9900) =     24.596 ms/op
     p(99.9990) =     26.247 ms/op
     p(99.9999) =     26.280 ms/op
    p(100.0000) =     26.280 ms/op


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
# Warmup Iteration   1: 4.879 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.682 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.525 ±(99.9%) 0.008 ms/op
Iteration   1: 3.371 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.793 ms/op
                 existUser·p0.50:   3.355 ms/op
                 existUser·p0.90:   4.104 ms/op
                 existUser·p0.95:   4.424 ms/op
                 existUser·p0.99:   5.554 ms/op
                 existUser·p0.999:  10.670 ms/op
                 existUser·p0.9999: 20.038 ms/op
                 existUser·p1.00:   20.414 ms/op

Iteration   2: 3.403 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.791 ms/op
                 existUser·p0.50:   3.375 ms/op
                 existUser·p0.90:   4.076 ms/op
                 existUser·p0.95:   4.383 ms/op
                 existUser·p0.99:   5.317 ms/op
                 existUser·p0.999:  8.340 ms/op
                 existUser·p0.9999: 15.673 ms/op
                 existUser·p1.00:   17.400 ms/op

Iteration   3: 3.482 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.983 ms/op
                 existUser·p0.50:   3.420 ms/op
                 existUser·p0.90:   4.047 ms/op
                 existUser·p0.95:   4.309 ms/op
                 existUser·p0.99:   5.456 ms/op
                 existUser·p0.999:  11.484 ms/op
                 existUser·p0.9999: 21.253 ms/op
                 existUser·p1.00:   23.265 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 280953
  mean =      3.418 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14076 
    [ 2.500,  5.000) = 262315 
    [ 5.000,  7.500) = 3763 
    [ 7.500, 10.000) = 557 
    [10.000, 12.500) = 72 
    [12.500, 15.000) = 52 
    [15.000, 17.500) = 39 
    [17.500, 20.000) = 34 
    [20.000, 22.500) = 41 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.791 ms/op
     p(50.0000) =      3.383 ms/op
     p(90.0000) =      4.071 ms/op
     p(95.0000) =      4.375 ms/op
     p(99.0000) =      5.431 ms/op
     p(99.9000) =      9.601 ms/op
     p(99.9900) =     20.539 ms/op
     p(99.9990) =     22.885 ms/op
     p(99.9999) =     23.265 ms/op
    p(100.0000) =     23.265 ms/op


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
# Warmup Iteration   1: 5.234 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.742 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.631 ±(99.9%) 0.008 ms/op
Iteration   1: 3.566 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.928 ms/op
                 getUser·p0.50:   3.498 ms/op
                 getUser·p0.90:   4.342 ms/op
                 getUser·p0.95:   4.637 ms/op
                 getUser·p0.99:   5.759 ms/op
                 getUser·p0.999:  9.011 ms/op
                 getUser·p0.9999: 17.433 ms/op
                 getUser·p1.00:   17.662 ms/op

Iteration   2: 3.590 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.083 ms/op
                 getUser·p0.50:   3.539 ms/op
                 getUser·p0.90:   4.276 ms/op
                 getUser·p0.95:   4.604 ms/op
                 getUser·p0.99:   5.931 ms/op
                 getUser·p0.999:  8.264 ms/op
                 getUser·p0.9999: 17.302 ms/op
                 getUser·p1.00:   17.793 ms/op

Iteration   3: 3.546 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.824 ms/op
                 getUser·p0.50:   3.490 ms/op
                 getUser·p0.90:   4.227 ms/op
                 getUser·p0.95:   4.538 ms/op
                 getUser·p0.99:   5.439 ms/op
                 getUser·p0.999:  7.818 ms/op
                 getUser·p0.9999: 21.823 ms/op
                 getUser·p1.00:   22.086 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 269013
  mean =      3.567 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8927 
    [ 2.500,  5.000) = 253731 
    [ 5.000,  7.500) = 5736 
    [ 7.500, 10.000) = 431 
    [10.000, 12.500) = 28 
    [12.500, 15.000) = 10 
    [15.000, 17.500) = 78 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 52 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.824 ms/op
     p(50.0000) =      3.510 ms/op
     p(90.0000) =      4.284 ms/op
     p(95.0000) =      4.596 ms/op
     p(99.0000) =      5.677 ms/op
     p(99.9000) =      8.749 ms/op
     p(99.9900) =     21.398 ms/op
     p(99.9990) =     21.975 ms/op
     p(99.9999) =     22.086 ms/op
    p(100.0000) =     22.086 ms/op


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
# Warmup Iteration   1: 5.339 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 5.241 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.684 ±(99.9%) 0.015 ms/op
Iteration   1: 4.749 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.554 ms/op
                 listUser·p0.50:   4.547 ms/op
                 listUser·p0.90:   6.062 ms/op
                 listUser·p0.95:   6.849 ms/op
                 listUser·p0.99:   8.298 ms/op
                 listUser·p0.999:  15.750 ms/op
                 listUser·p0.9999: 19.219 ms/op
                 listUser·p1.00:   19.595 ms/op

Iteration   2: 4.683 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.329 ms/op
                 listUser·p0.50:   4.497 ms/op
                 listUser·p0.90:   5.693 ms/op
                 listUser·p0.95:   6.431 ms/op
                 listUser·p0.99:   8.454 ms/op
                 listUser·p0.999:  16.105 ms/op
                 listUser·p0.9999: 18.858 ms/op
                 listUser·p1.00:   22.086 ms/op

Iteration   3: 4.761 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.257 ms/op
                 listUser·p0.50:   4.530 ms/op
                 listUser·p0.90:   6.062 ms/op
                 listUser·p0.95:   6.922 ms/op
                 listUser·p0.99:   8.733 ms/op
                 listUser·p0.999:  20.465 ms/op
                 listUser·p0.9999: 23.948 ms/op
                 listUser·p1.00:   24.510 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 202939
  mean =      4.731 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 466 
    [ 2.500,  5.000) = 155040 
    [ 5.000,  7.500) = 42311 
    [ 7.500, 10.000) = 4442 
    [10.000, 12.500) = 339 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 132 
    [17.500, 20.000) = 68 
    [20.000, 22.500) = 43 
    [22.500, 25.000) = 34 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.257 ms/op
     p(50.0000) =      4.522 ms/op
     p(90.0000) =      5.939 ms/op
     p(95.0000) =      6.775 ms/op
     p(99.0000) =      8.464 ms/op
     p(99.9000) =     16.318 ms/op
     p(99.9900) =     23.626 ms/op
     p(99.9990) =     24.309 ms/op
     p(99.9999) =     24.510 ms/op
    p(100.0000) =     24.510 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.626 ± 2.348  ops/ms
ClientGrpc.existUser                       thrpt       3   9.482 ± 1.486  ops/ms
ClientGrpc.getUser                         thrpt       3   9.043 ± 2.278  ops/ms
ClientGrpc.listUser                        thrpt       3   6.883 ± 0.642  ops/ms
ClientGrpc.createUser                       avgt       3   3.583 ± 1.260   ms/op
ClientGrpc.existUser                        avgt       3   3.402 ± 0.134   ms/op
ClientGrpc.getUser                          avgt       3   3.737 ± 0.855   ms/op
ClientGrpc.listUser                         avgt       3   4.726 ± 1.656   ms/op
ClientGrpc.createUser                     sample  261256   3.676 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.833           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.596           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.342           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.694           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.005           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.710           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          24.596           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          26.280           ms/op
ClientGrpc.existUser                      sample  280953   3.418 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.791           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.383           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.071           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.375           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.431           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.601           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.539           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          23.265           ms/op
ClientGrpc.getUser                        sample  269013   3.567 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.824           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.510           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.284           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.596           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.677           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.749           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.398           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.086           ms/op
ClientGrpc.listUser                       sample  202939   4.731 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.257           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.522           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.939           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.775           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.464           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.318           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.626           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.510           ms/op
