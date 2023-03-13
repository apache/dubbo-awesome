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
# Warmup Iteration   1: 3.121 ops/ms
# Warmup Iteration   2: 6.883 ops/ms
# Warmup Iteration   3: 8.149 ops/ms
Iteration   1: 9.146 ops/ms
Iteration   2: 8.903 ops/ms
Iteration   3: 8.650 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.899 ±(99.9%) 4.527 ops/ms [Average]
  (min, avg, max) = (8.650, 8.899, 9.146), stdev = 0.248
  CI (99.9%): [4.373, 13.426] (assumes normal distribution)


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
# Warmup Iteration   1: 6.017 ops/ms
# Warmup Iteration   2: 8.644 ops/ms
# Warmup Iteration   3: 9.245 ops/ms
Iteration   1: 9.287 ops/ms
Iteration   2: 9.549 ops/ms
Iteration   3: 9.515 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.451 ±(99.9%) 2.595 ops/ms [Average]
  (min, avg, max) = (9.287, 9.451, 9.549), stdev = 0.142
  CI (99.9%): [6.856, 12.045] (assumes normal distribution)


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
# Warmup Iteration   1: 5.719 ops/ms
# Warmup Iteration   2: 8.218 ops/ms
# Warmup Iteration   3: 8.533 ops/ms
Iteration   1: 8.804 ops/ms
Iteration   2: 8.830 ops/ms
Iteration   3: 8.356 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.663 ±(99.9%) 4.863 ops/ms [Average]
  (min, avg, max) = (8.356, 8.663, 8.830), stdev = 0.267
  CI (99.9%): [3.801, 13.526] (assumes normal distribution)


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
# Warmup Iteration   1: 4.087 ops/ms
# Warmup Iteration   2: 6.409 ops/ms
# Warmup Iteration   3: 6.653 ops/ms
Iteration   1: 6.656 ops/ms
Iteration   2: 6.697 ops/ms
Iteration   3: 6.677 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.677 ±(99.9%) 0.373 ops/ms [Average]
  (min, avg, max) = (6.656, 6.677, 6.697), stdev = 0.020
  CI (99.9%): [6.304, 7.050] (assumes normal distribution)


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
# Warmup Iteration   1: 5.252 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.987 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.912 ±(99.9%) 0.006 ms/op
Iteration   1: 3.886 ±(99.9%) 0.003 ms/op
Iteration   2: 3.817 ±(99.9%) 0.002 ms/op
Iteration   3: 3.766 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.823 ±(99.9%) 1.100 ms/op [Average]
  (min, avg, max) = (3.766, 3.823, 3.886), stdev = 0.060
  CI (99.9%): [2.723, 4.923] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 5.049 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.894 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.772 ±(99.9%) 0.002 ms/op
Iteration   1: 3.589 ±(99.9%) 0.003 ms/op
Iteration   2: 3.647 ±(99.9%) 0.003 ms/op
Iteration   3: 3.641 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.626 ±(99.9%) 0.579 ms/op [Average]
  (min, avg, max) = (3.589, 3.626, 3.647), stdev = 0.032
  CI (99.9%): [3.046, 4.205] (assumes normal distribution)


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
# Warmup Iteration   1: 5.305 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 4.025 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 3.971 ±(99.9%) 0.002 ms/op
Iteration   1: 3.954 ±(99.9%) 0.010 ms/op
Iteration   2: 3.830 ±(99.9%) 0.002 ms/op
Iteration   3: 3.761 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.848 ±(99.9%) 1.782 ms/op [Average]
  (min, avg, max) = (3.761, 3.848, 3.954), stdev = 0.098
  CI (99.9%): [2.067, 5.630] (assumes normal distribution)


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
# Warmup Iteration   1: 6.917 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 5.167 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.914 ±(99.9%) 0.020 ms/op
Iteration   1: 4.835 ±(99.9%) 0.015 ms/op
Iteration   2: 4.750 ±(99.9%) 0.007 ms/op
Iteration   3: 4.797 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.794 ±(99.9%) 0.777 ms/op [Average]
  (min, avg, max) = (4.750, 4.794, 4.835), stdev = 0.043
  CI (99.9%): [4.017, 5.571] (assumes normal distribution)


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
# Warmup Iteration   1: 5.302 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 4.196 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.832 ±(99.9%) 0.009 ms/op
Iteration   1: 4.008 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.942 ms/op
                 createUser·p0.50:   3.953 ms/op
                 createUser·p0.90:   4.874 ms/op
                 createUser·p0.95:   5.202 ms/op
                 createUser·p0.99:   6.611 ms/op
                 createUser·p0.999:  10.912 ms/op
                 createUser·p0.9999: 16.647 ms/op
                 createUser·p1.00:   17.105 ms/op

Iteration   2: 3.900 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.943 ms/op
                 createUser·p0.50:   3.863 ms/op
                 createUser·p0.90:   4.563 ms/op
                 createUser·p0.95:   4.899 ms/op
                 createUser·p0.99:   6.234 ms/op
                 createUser·p0.999:  8.387 ms/op
                 createUser·p0.9999: 17.648 ms/op
                 createUser·p1.00:   18.252 ms/op

Iteration   3: 3.934 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.759 ms/op
                 createUser·p0.50:   3.858 ms/op
                 createUser·p0.90:   4.588 ms/op
                 createUser·p0.95:   4.989 ms/op
                 createUser·p0.99:   6.496 ms/op
                 createUser·p0.999:  19.277 ms/op
                 createUser·p0.9999: 23.711 ms/op
                 createUser·p1.00:   23.986 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 243284
  mean =      3.947 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7137 
    [ 2.500,  5.000) = 222757 
    [ 5.000,  7.500) = 12290 
    [ 7.500, 10.000) = 744 
    [10.000, 12.500) = 153 
    [12.500, 15.000) = 50 
    [15.000, 17.500) = 48 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 42 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.759 ms/op
     p(50.0000) =      3.887 ms/op
     p(90.0000) =      4.686 ms/op
     p(95.0000) =      5.046 ms/op
     p(99.0000) =      6.455 ms/op
     p(99.9000) =     11.235 ms/op
     p(99.9900) =     21.889 ms/op
     p(99.9990) =     23.892 ms/op
     p(99.9999) =     23.986 ms/op
    p(100.0000) =     23.986 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 5.023 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.763 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.783 ±(99.9%) 0.009 ms/op
Iteration   1: 3.698 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.884 ms/op
                 existUser·p0.50:   3.678 ms/op
                 existUser·p0.90:   4.448 ms/op
                 existUser·p0.95:   4.760 ms/op
                 existUser·p0.99:   5.751 ms/op
                 existUser·p0.999:  8.733 ms/op
                 existUser·p0.9999: 15.499 ms/op
                 existUser·p1.00:   15.630 ms/op

Iteration   2: 3.653 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.721 ms/op
                 existUser·p0.50:   3.654 ms/op
                 existUser·p0.90:   4.194 ms/op
                 existUser·p0.95:   4.432 ms/op
                 existUser·p0.99:   5.226 ms/op
                 existUser·p0.999:  12.528 ms/op
                 existUser·p0.9999: 23.076 ms/op
                 existUser·p1.00:   24.412 ms/op

Iteration   3: 3.792 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.083 ms/op
                 existUser·p0.50:   3.723 ms/op
                 existUser·p0.90:   4.456 ms/op
                 existUser·p0.95:   4.702 ms/op
                 existUser·p0.99:   5.546 ms/op
                 existUser·p0.999:  9.273 ms/op
                 existUser·p0.9999: 20.859 ms/op
                 existUser·p1.00:   21.266 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 258492
  mean =      3.713 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8462 
    [ 2.500,  5.000) = 244353 
    [ 5.000,  7.500) = 5086 
    [ 7.500, 10.000) = 396 
    [10.000, 12.500) = 12 
    [12.500, 15.000) = 63 
    [15.000, 17.500) = 46 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.721 ms/op
     p(50.0000) =      3.682 ms/op
     p(90.0000) =      4.366 ms/op
     p(95.0000) =      4.661 ms/op
     p(99.0000) =      5.530 ms/op
     p(99.9000) =      9.028 ms/op
     p(99.9900) =     22.615 ms/op
     p(99.9990) =     24.341 ms/op
     p(99.9999) =     24.412 ms/op
    p(100.0000) =     24.412 ms/op


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
# Warmup Iteration   1: 5.367 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 4.067 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.850 ±(99.9%) 0.009 ms/op
Iteration   1: 3.793 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.888 ms/op
                 getUser·p0.50:   3.752 ms/op
                 getUser·p0.90:   4.497 ms/op
                 getUser·p0.95:   4.825 ms/op
                 getUser·p0.99:   6.242 ms/op
                 getUser·p0.999:  9.689 ms/op
                 getUser·p0.9999: 23.204 ms/op
                 getUser·p1.00:   23.527 ms/op

Iteration   2: 3.840 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.007 ms/op
                 getUser·p0.50:   3.809 ms/op
                 getUser·p0.90:   4.555 ms/op
                 getUser·p0.95:   4.858 ms/op
                 getUser·p0.99:   5.890 ms/op
                 getUser·p0.999:  8.864 ms/op
                 getUser·p0.9999: 20.654 ms/op
                 getUser·p1.00:   21.135 ms/op

Iteration   3: 3.857 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.738 ms/op
                 getUser·p0.50:   3.830 ms/op
                 getUser·p0.90:   4.571 ms/op
                 getUser·p0.95:   4.882 ms/op
                 getUser·p0.99:   6.038 ms/op
                 getUser·p0.999:  9.948 ms/op
                 getUser·p0.9999: 20.199 ms/op
                 getUser·p1.00:   25.231 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 250593
  mean =      3.830 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8475 
    [ 2.500,  5.000) = 232819 
    [ 5.000,  7.500) = 8391 
    [ 7.500, 10.000) = 691 
    [10.000, 12.500) = 28 
    [12.500, 15.000) = 29 
    [15.000, 17.500) = 33 
    [17.500, 20.000) = 63 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 37 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.738 ms/op
     p(50.0000) =      3.797 ms/op
     p(90.0000) =      4.538 ms/op
     p(95.0000) =      4.858 ms/op
     p(99.0000) =      6.070 ms/op
     p(99.9000) =      9.582 ms/op
     p(99.9900) =     22.903 ms/op
     p(99.9990) =     24.951 ms/op
     p(99.9999) =     25.231 ms/op
    p(100.0000) =     25.231 ms/op


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
# Warmup Iteration   1: 6.876 ±(99.9%) 0.075 ms/op
# Warmup Iteration   2: 5.158 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 5.003 ±(99.9%) 0.016 ms/op
Iteration   1: 4.871 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.450 ms/op
                 listUser·p0.50:   4.653 ms/op
                 listUser·p0.90:   6.128 ms/op
                 listUser·p0.95:   7.119 ms/op
                 listUser·p0.99:   8.913 ms/op
                 listUser·p0.999:  17.170 ms/op
                 listUser·p0.9999: 24.248 ms/op
                 listUser·p1.00:   25.330 ms/op

Iteration   2: 4.839 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.378 ms/op
                 listUser·p0.50:   4.661 ms/op
                 listUser·p0.90:   5.980 ms/op
                 listUser·p0.95:   6.808 ms/op
                 listUser·p0.99:   8.380 ms/op
                 listUser·p0.999:  17.367 ms/op
                 listUser·p0.9999: 21.607 ms/op
                 listUser·p1.00:   22.610 ms/op

Iteration   3: 4.689 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.214 ms/op
                 listUser·p0.50:   4.538 ms/op
                 listUser·p0.90:   5.620 ms/op
                 listUser·p0.95:   6.373 ms/op
                 listUser·p0.99:   8.258 ms/op
                 listUser·p0.999:  19.431 ms/op
                 listUser·p0.9999: 34.692 ms/op
                 listUser·p1.00:   35.062 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 199888
  mean =      4.798 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 565 
    [ 2.500,  5.000) = 147907 
    [ 5.000,  7.500) = 45973 
    [ 7.500, 10.000) = 4696 
    [10.000, 12.500) = 320 
    [12.500, 15.000) = 131 
    [15.000, 17.500) = 111 
    [17.500, 20.000) = 86 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 2 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 31 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.214 ms/op
     p(50.0000) =      4.620 ms/op
     p(90.0000) =      5.915 ms/op
     p(95.0000) =      6.775 ms/op
     p(99.0000) =      8.487 ms/op
     p(99.9000) =     17.400 ms/op
     p(99.9900) =     34.341 ms/op
     p(99.9990) =     34.931 ms/op
     p(99.9999) =     35.062 ms/op
    p(100.0000) =     35.062 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.899 ± 4.527  ops/ms
ClientGrpc.existUser                       thrpt       3   9.451 ± 2.595  ops/ms
ClientGrpc.getUser                         thrpt       3   8.663 ± 4.863  ops/ms
ClientGrpc.listUser                        thrpt       3   6.677 ± 0.373  ops/ms
ClientGrpc.createUser                       avgt       3   3.823 ± 1.100   ms/op
ClientGrpc.existUser                        avgt       3   3.626 ± 0.579   ms/op
ClientGrpc.getUser                          avgt       3   3.848 ± 1.782   ms/op
ClientGrpc.listUser                         avgt       3   4.794 ± 0.777   ms/op
ClientGrpc.createUser                     sample  243284   3.947 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.759           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.887           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.686           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.046           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.455           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.235           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.889           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.986           ms/op
ClientGrpc.existUser                      sample  258492   3.713 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.721           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.682           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.366           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.661           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.530           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.028           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          22.615           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          24.412           ms/op
ClientGrpc.getUser                        sample  250593   3.830 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.738           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.797           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.538           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.858           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.070           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.582           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          22.903           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          25.231           ms/op
ClientGrpc.listUser                       sample  199888   4.798 ± 0.009   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.214           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.620           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.915           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.775           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.487           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.400           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          34.341           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          35.062           ms/op
