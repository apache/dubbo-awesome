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
# Warmup Iteration   1: 2.938 ops/ms
# Warmup Iteration   2: 7.094 ops/ms
# Warmup Iteration   3: 8.037 ops/ms
Iteration   1: 8.651 ops/ms
Iteration   2: 8.546 ops/ms
Iteration   3: 8.530 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.576 ±(99.9%) 1.200 ops/ms [Average]
  (min, avg, max) = (8.530, 8.576, 8.651), stdev = 0.066
  CI (99.9%): [7.375, 9.776] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:01
# Fork: 1 of 1
# Warmup Iteration   1: 5.953 ops/ms
# Warmup Iteration   2: 8.686 ops/ms
# Warmup Iteration   3: 8.944 ops/ms
Iteration   1: 8.818 ops/ms
Iteration   2: 9.232 ops/ms
Iteration   3: 9.002 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.017 ±(99.9%) 3.785 ops/ms [Average]
  (min, avg, max) = (8.818, 9.017, 9.232), stdev = 0.207
  CI (99.9%): [5.232, 12.802] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 5.502 ops/ms
# Warmup Iteration   2: 8.122 ops/ms
# Warmup Iteration   3: 8.535 ops/ms
Iteration   1: 8.444 ops/ms
Iteration   2: 8.676 ops/ms
Iteration   3: 8.200 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.440 ±(99.9%) 4.342 ops/ms [Average]
  (min, avg, max) = (8.200, 8.440, 8.676), stdev = 0.238
  CI (99.9%): [4.098, 12.782] (assumes normal distribution)


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
# Warmup Iteration   1: 4.177 ops/ms
# Warmup Iteration   2: 5.987 ops/ms
# Warmup Iteration   3: 6.327 ops/ms
Iteration   1: 6.365 ops/ms
Iteration   2: 6.429 ops/ms
Iteration   3: 6.647 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.480 ±(99.9%) 2.692 ops/ms [Average]
  (min, avg, max) = (6.365, 6.480, 6.647), stdev = 0.148
  CI (99.9%): [3.789, 9.172] (assumes normal distribution)


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
# Warmup Iteration   1: 5.533 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 4.022 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 3.864 ±(99.9%) 0.006 ms/op
Iteration   1: 3.849 ±(99.9%) 0.003 ms/op
Iteration   2: 3.687 ±(99.9%) 0.005 ms/op
Iteration   3: 3.710 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.749 ±(99.9%) 1.603 ms/op [Average]
  (min, avg, max) = (3.687, 3.749, 3.849), stdev = 0.088
  CI (99.9%): [2.145, 5.352] (assumes normal distribution)


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
# Warmup Iteration   1: 5.356 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.648 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.602 ±(99.9%) 0.005 ms/op
Iteration   1: 3.440 ±(99.9%) 0.003 ms/op
Iteration   2: 3.493 ±(99.9%) 0.004 ms/op
Iteration   3: 3.503 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.479 ±(99.9%) 0.609 ms/op [Average]
  (min, avg, max) = (3.440, 3.479, 3.503), stdev = 0.033
  CI (99.9%): [2.870, 4.087] (assumes normal distribution)


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
# Warmup Iteration   1: 5.034 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.844 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.664 ±(99.9%) 0.005 ms/op
Iteration   1: 3.718 ±(99.9%) 0.004 ms/op
Iteration   2: 3.637 ±(99.9%) 0.003 ms/op
Iteration   3: 3.611 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.655 ±(99.9%) 1.010 ms/op [Average]
  (min, avg, max) = (3.611, 3.655, 3.718), stdev = 0.055
  CI (99.9%): [2.645, 4.665] (assumes normal distribution)


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
# Warmup Iteration   1: 6.360 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 5.432 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.954 ±(99.9%) 0.009 ms/op
Iteration   1: 4.907 ±(99.9%) 0.020 ms/op
Iteration   2: 4.949 ±(99.9%) 0.014 ms/op
Iteration   3: 4.939 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.932 ±(99.9%) 0.398 ms/op [Average]
  (min, avg, max) = (4.907, 4.932, 4.949), stdev = 0.022
  CI (99.9%): [4.534, 5.330] (assumes normal distribution)


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
# Warmup Iteration   1: 5.169 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 3.931 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.743 ±(99.9%) 0.010 ms/op
Iteration   1: 3.751 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.956 ms/op
                 createUser·p0.50:   3.641 ms/op
                 createUser·p0.90:   4.538 ms/op
                 createUser·p0.95:   5.005 ms/op
                 createUser·p0.99:   7.021 ms/op
                 createUser·p0.999:  11.715 ms/op
                 createUser·p0.9999: 34.275 ms/op
                 createUser·p1.00:   34.537 ms/op

Iteration   2: 3.713 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.742 ms/op
                 createUser·p0.50:   3.641 ms/op
                 createUser·p0.90:   4.424 ms/op
                 createUser·p0.95:   4.776 ms/op
                 createUser·p0.99:   6.267 ms/op
                 createUser·p0.999:  9.699 ms/op
                 createUser·p0.9999: 22.864 ms/op
                 createUser·p1.00:   23.200 ms/op

Iteration   3: 3.678 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.826 ms/op
                 createUser·p0.50:   3.600 ms/op
                 createUser·p0.90:   4.334 ms/op
                 createUser·p0.95:   4.702 ms/op
                 createUser·p0.99:   6.078 ms/op
                 createUser·p0.999:  16.268 ms/op
                 createUser·p0.9999: 24.248 ms/op
                 createUser·p1.00:   25.723 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 258465
  mean =      3.714 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8016 
    [ 2.500,  5.000) = 240296 
    [ 5.000,  7.500) = 8649 
    [ 7.500, 10.000) = 1100 
    [10.000, 12.500) = 207 
    [12.500, 15.000) = 5 
    [15.000, 17.500) = 41 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 38 
    [22.500, 25.000) = 52 
    [25.000, 27.500) = 6 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 29 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.742 ms/op
     p(50.0000) =      3.625 ms/op
     p(90.0000) =      4.432 ms/op
     p(95.0000) =      4.833 ms/op
     p(99.0000) =      6.439 ms/op
     p(99.9000) =     11.485 ms/op
     p(99.9900) =     33.554 ms/op
     p(99.9990) =     34.472 ms/op
     p(99.9999) =     34.537 ms/op
    p(100.0000) =     34.537 ms/op


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
# Warmup Iteration   1: 5.002 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.797 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.658 ±(99.9%) 0.010 ms/op
Iteration   1: 3.528 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.702 ms/op
                 existUser·p0.50:   3.498 ms/op
                 existUser·p0.90:   4.202 ms/op
                 existUser·p0.95:   4.653 ms/op
                 existUser·p0.99:   6.242 ms/op
                 existUser·p0.999:  12.709 ms/op
                 existUser·p0.9999: 20.021 ms/op
                 existUser·p1.00:   20.578 ms/op

Iteration   2: 3.449 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.787 ms/op
                 existUser·p0.50:   3.449 ms/op
                 existUser·p0.90:   4.202 ms/op
                 existUser·p0.95:   4.669 ms/op
                 existUser·p0.99:   6.308 ms/op
                 existUser·p0.999:  12.014 ms/op
                 existUser·p0.9999: 22.929 ms/op
                 existUser·p1.00:   23.888 ms/op

Iteration   3: 3.489 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.866 ms/op
                 existUser·p0.50:   3.478 ms/op
                 existUser·p0.90:   4.268 ms/op
                 existUser·p0.95:   4.628 ms/op
                 existUser·p0.99:   6.130 ms/op
                 existUser·p0.999:  12.102 ms/op
                 existUser·p0.9999: 22.113 ms/op
                 existUser·p1.00:   23.724 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 275028
  mean =      3.488 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23745 
    [ 2.500,  5.000) = 242530 
    [ 5.000,  7.500) = 7409 
    [ 7.500, 10.000) = 886 
    [10.000, 12.500) = 191 
    [12.500, 15.000) = 132 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 35 
    [20.000, 22.500) = 51 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.702 ms/op
     p(50.0000) =      3.473 ms/op
     p(90.0000) =      4.227 ms/op
     p(95.0000) =      4.653 ms/op
     p(99.0000) =      6.234 ms/op
     p(99.9000) =     12.435 ms/op
     p(99.9900) =     22.118 ms/op
     p(99.9990) =     23.855 ms/op
     p(99.9999) =     23.888 ms/op
    p(100.0000) =     23.888 ms/op


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
# Warmup Iteration   1: 5.408 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 4.062 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.771 ±(99.9%) 0.011 ms/op
Iteration   1: 3.825 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.953 ms/op
                 getUser·p0.50:   3.727 ms/op
                 getUser·p0.90:   4.637 ms/op
                 getUser·p0.95:   4.989 ms/op
                 getUser·p0.99:   6.750 ms/op
                 getUser·p0.999:  11.354 ms/op
                 getUser·p0.9999: 19.866 ms/op
                 getUser·p1.00:   20.349 ms/op

Iteration   2: 3.674 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.771 ms/op
                 getUser·p0.50:   3.625 ms/op
                 getUser·p0.90:   4.383 ms/op
                 getUser·p0.95:   4.784 ms/op
                 getUser·p0.99:   5.988 ms/op
                 getUser·p0.999:  10.746 ms/op
                 getUser·p0.9999: 22.006 ms/op
                 getUser·p1.00:   22.479 ms/op

Iteration   3: 3.882 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.945 ms/op
                 getUser·p0.50:   3.797 ms/op
                 getUser·p0.90:   4.702 ms/op
                 getUser·p0.95:   5.063 ms/op
                 getUser·p0.99:   6.832 ms/op
                 getUser·p0.999:  10.551 ms/op
                 getUser·p0.9999: 24.396 ms/op
                 getUser·p1.00:   24.838 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 253265
  mean =      3.792 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8370 
    [ 2.500,  5.000) = 233336 
    [ 5.000,  7.500) = 10102 
    [ 7.500, 10.000) = 1013 
    [10.000, 12.500) = 261 
    [12.500, 15.000) = 35 
    [15.000, 17.500) = 11 
    [17.500, 20.000) = 54 
    [20.000, 22.500) = 60 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.771 ms/op
     p(50.0000) =      3.707 ms/op
     p(90.0000) =      4.604 ms/op
     p(95.0000) =      4.948 ms/op
     p(99.0000) =      6.504 ms/op
     p(99.9000) =     11.026 ms/op
     p(99.9900) =     22.392 ms/op
     p(99.9990) =     24.738 ms/op
     p(99.9999) =     24.838 ms/op
    p(100.0000) =     24.838 ms/op


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
# Warmup Iteration   1: 7.452 ±(99.9%) 0.081 ms/op
# Warmup Iteration   2: 5.426 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.979 ±(99.9%) 0.016 ms/op
Iteration   1: 5.084 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.712 ms/op
                 listUser·p0.50:   4.776 ms/op
                 listUser·p0.90:   6.652 ms/op
                 listUser·p0.95:   7.512 ms/op
                 listUser·p0.99:   9.798 ms/op
                 listUser·p0.999:  16.535 ms/op
                 listUser·p0.9999: 17.797 ms/op
                 listUser·p1.00:   19.595 ms/op

Iteration   2: 5.011 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.532 ms/op
                 listUser·p0.50:   4.743 ms/op
                 listUser·p0.90:   6.414 ms/op
                 listUser·p0.95:   7.356 ms/op
                 listUser·p0.99:   9.585 ms/op
                 listUser·p0.999:  16.259 ms/op
                 listUser·p0.9999: 27.021 ms/op
                 listUser·p1.00:   27.197 ms/op

Iteration   3: 5.094 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.395 ms/op
                 listUser·p0.50:   4.776 ms/op
                 listUser·p0.90:   6.439 ms/op
                 listUser·p0.95:   7.422 ms/op
                 listUser·p0.99:   10.485 ms/op
                 listUser·p0.999:  21.692 ms/op
                 listUser·p0.9999: 32.145 ms/op
                 listUser·p1.00:   32.178 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 189668
  mean =      5.063 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 356 
    [ 2.500,  5.000) = 116823 
    [ 5.000,  7.500) = 63554 
    [ 7.500, 10.000) = 7109 
    [10.000, 12.500) = 1210 
    [12.500, 15.000) = 215 
    [15.000, 17.500) = 186 
    [17.500, 20.000) = 91 
    [20.000, 22.500) = 47 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 34 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.395 ms/op
     p(50.0000) =      4.768 ms/op
     p(90.0000) =      6.504 ms/op
     p(95.0000) =      7.430 ms/op
     p(99.0000) =      9.929 ms/op
     p(99.9000) =     17.946 ms/op
     p(99.9900) =     32.047 ms/op
     p(99.9990) =     32.178 ms/op
     p(99.9999) =     32.178 ms/op
    p(100.0000) =     32.178 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.576 ± 1.200  ops/ms
ClientGrpc.existUser                       thrpt       3   9.017 ± 3.785  ops/ms
ClientGrpc.getUser                         thrpt       3   8.440 ± 4.342  ops/ms
ClientGrpc.listUser                        thrpt       3   6.480 ± 2.692  ops/ms
ClientGrpc.createUser                       avgt       3   3.749 ± 1.603   ms/op
ClientGrpc.existUser                        avgt       3   3.479 ± 0.609   ms/op
ClientGrpc.getUser                          avgt       3   3.655 ± 1.010   ms/op
ClientGrpc.listUser                         avgt       3   4.932 ± 0.398   ms/op
ClientGrpc.createUser                     sample  258465   3.714 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.742           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.625           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.432           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.833           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.439           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.485           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          33.554           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          34.537           ms/op
ClientGrpc.existUser                      sample  275028   3.488 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.702           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.473           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.227           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.653           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.234           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          12.435           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          22.118           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          23.888           ms/op
ClientGrpc.getUser                        sample  253265   3.792 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.771           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.707           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.604           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.948           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.504           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.026           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          22.392           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          24.838           ms/op
ClientGrpc.listUser                       sample  189668   5.063 ± 0.011   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.395           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.768           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.504           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.430           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.929           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.946           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          32.047           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          32.178           ms/op
