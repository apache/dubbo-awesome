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
# Warmup Iteration   1: 3.105 ops/ms
# Warmup Iteration   2: 7.028 ops/ms
# Warmup Iteration   3: 8.515 ops/ms
Iteration   1: 8.703 ops/ms
Iteration   2: 8.779 ops/ms
Iteration   3: 8.841 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.774 ±(99.9%) 1.266 ops/ms [Average]
  (min, avg, max) = (8.703, 8.774, 8.841), stdev = 0.069
  CI (99.9%): [7.509, 10.040] (assumes normal distribution)


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
# Warmup Iteration   1: 5.844 ops/ms
# Warmup Iteration   2: 8.713 ops/ms
# Warmup Iteration   3: 9.270 ops/ms
Iteration   1: 9.644 ops/ms
Iteration   2: 9.490 ops/ms
Iteration   3: 9.523 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.552 ±(99.9%) 1.479 ops/ms [Average]
  (min, avg, max) = (9.490, 9.552, 9.644), stdev = 0.081
  CI (99.9%): [8.073, 11.031] (assumes normal distribution)


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
# Warmup Iteration   1: 5.363 ops/ms
# Warmup Iteration   2: 8.441 ops/ms
# Warmup Iteration   3: 8.551 ops/ms
Iteration   1: 8.925 ops/ms
Iteration   2: 9.009 ops/ms
Iteration   3: 8.918 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.951 ±(99.9%) 0.929 ops/ms [Average]
  (min, avg, max) = (8.918, 8.951, 9.009), stdev = 0.051
  CI (99.9%): [8.021, 9.880] (assumes normal distribution)


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
# Warmup Iteration   1: 4.212 ops/ms
# Warmup Iteration   2: 6.580 ops/ms
# Warmup Iteration   3: 6.955 ops/ms
Iteration   1: 6.844 ops/ms
Iteration   2: 6.941 ops/ms
Iteration   3: 6.875 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.887 ±(99.9%) 0.905 ops/ms [Average]
  (min, avg, max) = (6.844, 6.887, 6.941), stdev = 0.050
  CI (99.9%): [5.982, 7.792] (assumes normal distribution)


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
# Warmup Iteration   1: 5.246 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.764 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.739 ±(99.9%) 0.005 ms/op
Iteration   1: 3.578 ±(99.9%) 0.003 ms/op
Iteration   2: 3.624 ±(99.9%) 0.003 ms/op
Iteration   3: 3.611 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.604 ±(99.9%) 0.435 ms/op [Average]
  (min, avg, max) = (3.578, 3.604, 3.624), stdev = 0.024
  CI (99.9%): [3.169, 4.040] (assumes normal distribution)


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
# Warmup Iteration   1: 4.857 ±(99.9%) 0.073 ms/op
# Warmup Iteration   2: 3.674 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.428 ±(99.9%) 0.003 ms/op
Iteration   1: 3.417 ±(99.9%) 0.002 ms/op
Iteration   2: 3.302 ±(99.9%) 0.003 ms/op
Iteration   3: 3.360 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.360 ±(99.9%) 1.054 ms/op [Average]
  (min, avg, max) = (3.302, 3.360, 3.417), stdev = 0.058
  CI (99.9%): [2.306, 4.413] (assumes normal distribution)


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
# Warmup Iteration   1: 4.967 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.766 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.698 ±(99.9%) 0.003 ms/op
Iteration   1: 3.696 ±(99.9%) 0.005 ms/op
Iteration   2: 3.496 ±(99.9%) 0.006 ms/op
Iteration   3: 3.635 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.609 ±(99.9%) 1.874 ms/op [Average]
  (min, avg, max) = (3.496, 3.609, 3.696), stdev = 0.103
  CI (99.9%): [1.735, 5.483] (assumes normal distribution)


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
# Warmup Iteration   1: 6.772 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 4.813 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.551 ±(99.9%) 0.014 ms/op
Iteration   1: 4.650 ±(99.9%) 0.011 ms/op
Iteration   2: 4.482 ±(99.9%) 0.026 ms/op
Iteration   3: 4.494 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.542 ±(99.9%) 1.708 ms/op [Average]
  (min, avg, max) = (4.482, 4.542, 4.650), stdev = 0.094
  CI (99.9%): [2.834, 6.249] (assumes normal distribution)


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
# Warmup Iteration   1: 5.277 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 3.869 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.635 ±(99.9%) 0.009 ms/op
Iteration   1: 3.602 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.859 ms/op
                 createUser·p0.50:   3.543 ms/op
                 createUser·p0.90:   4.293 ms/op
                 createUser·p0.95:   4.637 ms/op
                 createUser·p0.99:   5.915 ms/op
                 createUser·p0.999:  15.781 ms/op
                 createUser·p0.9999: 18.624 ms/op
                 createUser·p1.00:   28.279 ms/op

Iteration   2: 3.660 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.041 ms/op
                 createUser·p0.50:   3.596 ms/op
                 createUser·p0.90:   4.334 ms/op
                 createUser·p0.95:   4.637 ms/op
                 createUser·p0.99:   5.841 ms/op
                 createUser·p0.999:  9.257 ms/op
                 createUser·p0.9999: 19.538 ms/op
                 createUser·p1.00:   21.594 ms/op

Iteration   3: 3.575 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.989 ms/op
                 createUser·p0.50:   3.539 ms/op
                 createUser·p0.90:   4.243 ms/op
                 createUser·p0.95:   4.555 ms/op
                 createUser·p0.99:   5.797 ms/op
                 createUser·p0.999:  11.197 ms/op
                 createUser·p0.9999: 25.272 ms/op
                 createUser·p1.00:   26.444 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 265838
  mean =      3.612 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9409 
    [ 2.500,  5.000) = 250132 
    [ 5.000,  7.500) = 5255 
    [ 7.500, 10.000) = 719 
    [10.000, 12.500) = 108 
    [12.500, 15.000) = 23 
    [15.000, 17.500) = 49 
    [17.500, 20.000) = 76 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      0.859 ms/op
     p(50.0000) =      3.559 ms/op
     p(90.0000) =      4.293 ms/op
     p(95.0000) =      4.612 ms/op
     p(99.0000) =      5.857 ms/op
     p(99.9000) =     11.010 ms/op
     p(99.9900) =     24.467 ms/op
     p(99.9990) =     26.444 ms/op
     p(99.9999) =     28.279 ms/op
    p(100.0000) =     28.279 ms/op


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
# Warmup Iteration   1: 5.065 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.704 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.480 ±(99.9%) 0.008 ms/op
Iteration   1: 3.285 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.495 ms/op
                 existUser·p0.50:   3.355 ms/op
                 existUser·p0.90:   3.994 ms/op
                 existUser·p0.95:   4.276 ms/op
                 existUser·p0.99:   5.186 ms/op
                 existUser·p0.999:  8.792 ms/op
                 existUser·p0.9999: 15.529 ms/op
                 existUser·p1.00:   15.925 ms/op

Iteration   2: 3.492 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.806 ms/op
                 existUser·p0.50:   3.441 ms/op
                 existUser·p0.90:   4.104 ms/op
                 existUser·p0.95:   4.448 ms/op
                 existUser·p0.99:   5.718 ms/op
                 existUser·p0.999:  9.804 ms/op
                 existUser·p0.9999: 14.844 ms/op
                 existUser·p1.00:   16.876 ms/op

Iteration   3: 3.578 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.800 ms/op
                 existUser·p0.50:   3.478 ms/op
                 existUser·p0.90:   4.211 ms/op
                 existUser·p0.95:   4.538 ms/op
                 existUser·p0.99:   5.917 ms/op
                 existUser·p0.999:  16.056 ms/op
                 existUser·p0.9999: 27.558 ms/op
                 existUser·p1.00:   27.754 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 278432
  mean =      3.447 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16453 
    [ 2.500,  5.000) = 257060 
    [ 5.000,  7.500) = 4043 
    [ 7.500, 10.000) = 574 
    [10.000, 12.500) = 71 
    [12.500, 15.000) = 116 
    [15.000, 17.500) = 50 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 20 

  Percentiles, ms/op:
      p(0.0000) =      0.495 ms/op
     p(50.0000) =      3.424 ms/op
     p(90.0000) =      4.100 ms/op
     p(95.0000) =      4.424 ms/op
     p(99.0000) =      5.628 ms/op
     p(99.9000) =     10.340 ms/op
     p(99.9900) =     27.394 ms/op
     p(99.9990) =     27.696 ms/op
     p(99.9999) =     27.754 ms/op
    p(100.0000) =     27.754 ms/op


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
# Warmup Iteration   1: 5.370 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 3.763 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.668 ±(99.9%) 0.009 ms/op
Iteration   1: 3.667 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.806 ms/op
                 getUser·p0.50:   3.609 ms/op
                 getUser·p0.90:   4.489 ms/op
                 getUser·p0.95:   4.858 ms/op
                 getUser·p0.99:   6.087 ms/op
                 getUser·p0.999:  10.430 ms/op
                 getUser·p0.9999: 19.342 ms/op
                 getUser·p1.00:   19.530 ms/op

Iteration   2: 3.562 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.714 ms/op
                 getUser·p0.50:   3.514 ms/op
                 getUser·p0.90:   4.125 ms/op
                 getUser·p0.95:   4.440 ms/op
                 getUser·p0.99:   5.571 ms/op
                 getUser·p0.999:  9.913 ms/op
                 getUser·p0.9999: 23.888 ms/op
                 getUser·p1.00:   24.379 ms/op

Iteration   3: 3.583 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.751 ms/op
                 getUser·p0.50:   3.535 ms/op
                 getUser·p0.90:   4.219 ms/op
                 getUser·p0.95:   4.571 ms/op
                 getUser·p0.99:   5.751 ms/op
                 getUser·p0.999:  8.197 ms/op
                 getUser·p0.9999: 41.489 ms/op
                 getUser·p1.00:   42.336 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 266365
  mean =      3.603 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 259510 
    [ 5.000, 10.000) = 6607 
    [10.000, 15.000) = 88 
    [15.000, 20.000) = 88 
    [20.000, 25.000) = 40 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.714 ms/op
     p(50.0000) =      3.547 ms/op
     p(90.0000) =      4.293 ms/op
     p(95.0000) =      4.645 ms/op
     p(99.0000) =      5.808 ms/op
     p(99.9000) =      9.880 ms/op
     p(99.9900) =     40.436 ms/op
     p(99.9990) =     41.944 ms/op
     p(99.9999) =     42.336 ms/op
    p(100.0000) =     42.336 ms/op


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
# Warmup Iteration   1: 5.916 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 5.108 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.765 ±(99.9%) 0.016 ms/op
Iteration   1: 4.612 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.430 ms/op
                 listUser·p0.50:   4.391 ms/op
                 listUser·p0.90:   5.759 ms/op
                 listUser·p0.95:   6.750 ms/op
                 listUser·p0.99:   8.569 ms/op
                 listUser·p0.999:  15.209 ms/op
                 listUser·p0.9999: 18.750 ms/op
                 listUser·p1.00:   19.399 ms/op

Iteration   2: 4.583 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.063 ms/op
                 listUser·p0.50:   4.325 ms/op
                 listUser·p0.90:   6.095 ms/op
                 listUser·p0.95:   6.849 ms/op
                 listUser·p0.99:   8.258 ms/op
                 listUser·p0.999:  16.500 ms/op
                 listUser·p0.9999: 21.202 ms/op
                 listUser·p1.00:   21.627 ms/op

Iteration   3: 4.639 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.245 ms/op
                 listUser·p0.50:   4.415 ms/op
                 listUser·p0.90:   5.865 ms/op
                 listUser·p0.95:   6.881 ms/op
                 listUser·p0.99:   8.743 ms/op
                 listUser·p0.999:  24.879 ms/op
                 listUser·p0.9999: 30.186 ms/op
                 listUser·p1.00:   30.769 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 208201
  mean =      4.611 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 293 
    [ 2.500,  5.000) = 166060 
    [ 5.000,  7.500) = 36473 
    [ 7.500, 10.000) = 4550 
    [10.000, 12.500) = 445 
    [12.500, 15.000) = 80 
    [15.000, 17.500) = 114 
    [17.500, 20.000) = 69 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 32 
    [27.500, 30.000) = 26 
    [30.000, 32.500) = 10 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.063 ms/op
     p(50.0000) =      4.383 ms/op
     p(90.0000) =      5.931 ms/op
     p(95.0000) =      6.824 ms/op
     p(99.0000) =      8.520 ms/op
     p(99.9000) =     16.902 ms/op
     p(99.9900) =     28.487 ms/op
     p(99.9990) =     30.701 ms/op
     p(99.9999) =     30.769 ms/op
    p(100.0000) =     30.769 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.774 ± 1.266  ops/ms
ClientGrpc.existUser                       thrpt       3   9.552 ± 1.479  ops/ms
ClientGrpc.getUser                         thrpt       3   8.951 ± 0.929  ops/ms
ClientGrpc.listUser                        thrpt       3   6.887 ± 0.905  ops/ms
ClientGrpc.createUser                       avgt       3   3.604 ± 0.435   ms/op
ClientGrpc.existUser                        avgt       3   3.360 ± 1.054   ms/op
ClientGrpc.getUser                          avgt       3   3.609 ± 1.874   ms/op
ClientGrpc.listUser                         avgt       3   4.542 ± 1.708   ms/op
ClientGrpc.createUser                     sample  265838   3.612 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.859           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.559           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.293           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.612           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.857           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.010           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          24.467           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          28.279           ms/op
ClientGrpc.existUser                      sample  278432   3.447 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.495           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.424           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.100           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.424           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.628           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.340           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          27.394           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          27.754           ms/op
ClientGrpc.getUser                        sample  266365   3.603 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.714           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.547           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.293           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.645           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.808           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.880           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          40.436           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          42.336           ms/op
ClientGrpc.listUser                       sample  208201   4.611 ± 0.009   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.063           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.383           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.931           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.824           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.520           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.902           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          28.487           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          30.769           ms/op
