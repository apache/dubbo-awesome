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
# Warmup Iteration   1: 3.043 ops/ms
# Warmup Iteration   2: 6.731 ops/ms
# Warmup Iteration   3: 8.105 ops/ms
Iteration   1: 8.791 ops/ms
Iteration   2: 8.790 ops/ms
Iteration   3: 9.019 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.867 ±(99.9%) 2.401 ops/ms [Average]
  (min, avg, max) = (8.790, 8.867, 9.019), stdev = 0.132
  CI (99.9%): [6.466, 11.268] (assumes normal distribution)


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
# Warmup Iteration   1: 6.087 ops/ms
# Warmup Iteration   2: 8.717 ops/ms
# Warmup Iteration   3: 9.345 ops/ms
Iteration   1: 8.921 ops/ms
Iteration   2: 9.301 ops/ms
Iteration   3: 9.430 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.217 ±(99.9%) 4.832 ops/ms [Average]
  (min, avg, max) = (8.921, 9.217, 9.430), stdev = 0.265
  CI (99.9%): [4.386, 14.049] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 5.260 ops/ms
# Warmup Iteration   2: 8.292 ops/ms
# Warmup Iteration   3: 8.486 ops/ms
Iteration   1: 8.733 ops/ms
Iteration   2: 8.838 ops/ms
Iteration   3: 8.739 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.770 ±(99.9%) 1.076 ops/ms [Average]
  (min, avg, max) = (8.733, 8.770, 8.838), stdev = 0.059
  CI (99.9%): [7.695, 9.846] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 4.359 ops/ms
# Warmup Iteration   2: 6.194 ops/ms
# Warmup Iteration   3: 6.581 ops/ms
Iteration   1: 6.551 ops/ms
Iteration   2: 6.636 ops/ms
Iteration   3: 6.701 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.629 ±(99.9%) 1.371 ops/ms [Average]
  (min, avg, max) = (6.551, 6.629, 6.701), stdev = 0.075
  CI (99.9%): [5.259, 8.000] (assumes normal distribution)


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
# Warmup Iteration   1: 5.249 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.832 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.704 ±(99.9%) 0.008 ms/op
Iteration   1: 3.568 ±(99.9%) 0.004 ms/op
Iteration   2: 3.633 ±(99.9%) 0.002 ms/op
Iteration   3: 3.545 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.582 ±(99.9%) 0.837 ms/op [Average]
  (min, avg, max) = (3.545, 3.582, 3.633), stdev = 0.046
  CI (99.9%): [2.745, 4.419] (assumes normal distribution)


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
# Warmup Iteration   1: 5.033 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.579 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.496 ±(99.9%) 0.003 ms/op
Iteration   1: 3.426 ±(99.9%) 0.003 ms/op
Iteration   2: 3.441 ±(99.9%) 0.005 ms/op
Iteration   3: 3.416 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.428 ±(99.9%) 0.229 ms/op [Average]
  (min, avg, max) = (3.416, 3.428, 3.441), stdev = 0.013
  CI (99.9%): [3.199, 3.657] (assumes normal distribution)


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
# Warmup Iteration   1: 5.477 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.771 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.675 ±(99.9%) 0.004 ms/op
Iteration   1: 3.625 ±(99.9%) 0.005 ms/op
Iteration   2: 3.580 ±(99.9%) 0.003 ms/op
Iteration   3: 3.652 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.619 ±(99.9%) 0.660 ms/op [Average]
  (min, avg, max) = (3.580, 3.619, 3.652), stdev = 0.036
  CI (99.9%): [2.959, 4.279] (assumes normal distribution)


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
# Warmup Iteration   1: 7.084 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 5.020 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.809 ±(99.9%) 0.014 ms/op
Iteration   1: 4.738 ±(99.9%) 0.008 ms/op
Iteration   2: 4.661 ±(99.9%) 0.010 ms/op
Iteration   3: 4.719 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.706 ±(99.9%) 0.727 ms/op [Average]
  (min, avg, max) = (4.661, 4.706, 4.738), stdev = 0.040
  CI (99.9%): [3.979, 5.433] (assumes normal distribution)


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
# Warmup Iteration   1: 5.413 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 4.022 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.820 ±(99.9%) 0.010 ms/op
Iteration   1: 3.700 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.946 ms/op
                 createUser·p0.50:   3.645 ms/op
                 createUser·p0.90:   4.317 ms/op
                 createUser·p0.95:   4.678 ms/op
                 createUser·p0.99:   5.726 ms/op
                 createUser·p0.999:  12.288 ms/op
                 createUser·p0.9999: 20.611 ms/op
                 createUser·p1.00:   21.365 ms/op

Iteration   2: 3.639 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.903 ms/op
                 createUser·p0.50:   3.625 ms/op
                 createUser·p0.90:   4.202 ms/op
                 createUser·p0.95:   4.456 ms/op
                 createUser·p0.99:   5.505 ms/op
                 createUser·p0.999:  18.125 ms/op
                 createUser·p0.9999: 20.611 ms/op
                 createUser·p1.00:   20.742 ms/op

Iteration   3: 3.660 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.669 ms/op
                 createUser·p0.50:   3.629 ms/op
                 createUser·p0.90:   4.194 ms/op
                 createUser·p0.95:   4.497 ms/op
                 createUser·p0.99:   5.720 ms/op
                 createUser·p0.999:  9.491 ms/op
                 createUser·p0.9999: 23.167 ms/op
                 createUser·p1.00:   24.773 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 261802
  mean =      3.666 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6056 
    [ 2.500,  5.000) = 250069 
    [ 5.000,  7.500) = 5053 
    [ 7.500, 10.000) = 313 
    [10.000, 12.500) = 65 
    [12.500, 15.000) = 46 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 87 
    [20.000, 22.500) = 58 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.669 ms/op
     p(50.0000) =      3.633 ms/op
     p(90.0000) =      4.235 ms/op
     p(95.0000) =      4.547 ms/op
     p(99.0000) =      5.661 ms/op
     p(99.9000) =     11.980 ms/op
     p(99.9900) =     22.768 ms/op
     p(99.9990) =     23.771 ms/op
     p(99.9999) =     24.773 ms/op
    p(100.0000) =     24.773 ms/op


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
# Warmup Iteration   1: 4.736 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.548 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.405 ±(99.9%) 0.007 ms/op
Iteration   1: 3.443 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.812 ms/op
                 existUser·p0.50:   3.432 ms/op
                 existUser·p0.90:   3.903 ms/op
                 existUser·p0.95:   4.137 ms/op
                 existUser·p0.99:   5.210 ms/op
                 existUser·p0.999:  8.984 ms/op
                 existUser·p0.9999: 19.717 ms/op
                 existUser·p1.00:   20.120 ms/op

Iteration   2: 3.499 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.081 ms/op
                 existUser·p0.50:   3.441 ms/op
                 existUser·p0.90:   4.076 ms/op
                 existUser·p0.95:   4.375 ms/op
                 existUser·p0.99:   5.292 ms/op
                 existUser·p0.999:  7.598 ms/op
                 existUser·p0.9999: 16.950 ms/op
                 existUser·p1.00:   17.629 ms/op

Iteration   3: 3.500 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.839 ms/op
                 existUser·p0.50:   3.449 ms/op
                 existUser·p0.90:   4.100 ms/op
                 existUser·p0.95:   4.358 ms/op
                 existUser·p0.99:   4.915 ms/op
                 existUser·p0.999:  8.033 ms/op
                 existUser·p0.9999: 19.329 ms/op
                 existUser·p1.00:   21.168 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 275743
  mean =      3.480 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6091 
    [ 2.500,  5.000) = 266492 
    [ 5.000,  7.500) = 2774 
    [ 7.500, 10.000) = 212 
    [10.000, 12.500) = 14 
    [12.500, 15.000) = 20 
    [15.000, 17.500) = 42 
    [17.500, 20.000) = 89 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.812 ms/op
     p(50.0000) =      3.441 ms/op
     p(90.0000) =      4.018 ms/op
     p(95.0000) =      4.317 ms/op
     p(99.0000) =      5.120 ms/op
     p(99.9000) =      7.918 ms/op
     p(99.9900) =     19.413 ms/op
     p(99.9990) =     20.879 ms/op
     p(99.9999) =     21.168 ms/op
    p(100.0000) =     21.168 ms/op


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
# Warmup Iteration   1: 5.385 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 3.887 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.742 ±(99.9%) 0.008 ms/op
Iteration   1: 3.721 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.001 ms/op
                 getUser·p0.50:   3.666 ms/op
                 getUser·p0.90:   4.399 ms/op
                 getUser·p0.95:   4.678 ms/op
                 getUser·p0.99:   5.857 ms/op
                 getUser·p0.999:  11.273 ms/op
                 getUser·p0.9999: 15.729 ms/op
                 getUser·p1.00:   18.678 ms/op

Iteration   2: 3.643 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.013 ms/op
                 getUser·p0.50:   3.604 ms/op
                 getUser·p0.90:   4.219 ms/op
                 getUser·p0.95:   4.465 ms/op
                 getUser·p0.99:   5.169 ms/op
                 getUser·p0.999:  8.298 ms/op
                 getUser·p0.9999: 17.859 ms/op
                 getUser·p1.00:   18.285 ms/op

Iteration   3: 3.612 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.975 ms/op
                 getUser·p0.50:   3.584 ms/op
                 getUser·p0.90:   4.157 ms/op
                 getUser·p0.95:   4.465 ms/op
                 getUser·p0.99:   5.235 ms/op
                 getUser·p0.999:  7.732 ms/op
                 getUser·p0.9999: 20.054 ms/op
                 getUser·p1.00:   20.775 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 262446
  mean =      3.658 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6094 
    [ 2.500,  5.000) = 251389 
    [ 5.000,  7.500) = 4302 
    [ 7.500, 10.000) = 432 
    [10.000, 12.500) = 64 
    [12.500, 15.000) = 28 
    [15.000, 17.500) = 64 
    [17.500, 20.000) = 64 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.975 ms/op
     p(50.0000) =      3.617 ms/op
     p(90.0000) =      4.268 ms/op
     p(95.0000) =      4.547 ms/op
     p(99.0000) =      5.439 ms/op
     p(99.9000) =      9.603 ms/op
     p(99.9900) =     18.408 ms/op
     p(99.9990) =     20.566 ms/op
     p(99.9999) =     20.775 ms/op
    p(100.0000) =     20.775 ms/op


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
# Warmup Iteration   1: 6.936 ±(99.9%) 0.074 ms/op
# Warmup Iteration   2: 4.966 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.691 ±(99.9%) 0.012 ms/op
Iteration   1: 4.796 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.067 ms/op
                 listUser·p0.50:   4.628 ms/op
                 listUser·p0.90:   5.718 ms/op
                 listUser·p0.95:   6.496 ms/op
                 listUser·p0.99:   8.159 ms/op
                 listUser·p0.999:  15.537 ms/op
                 listUser·p0.9999: 23.702 ms/op
                 listUser·p1.00:   25.068 ms/op

Iteration   2: 4.731 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.507 ms/op
                 listUser·p0.50:   4.596 ms/op
                 listUser·p0.90:   5.431 ms/op
                 listUser·p0.95:   6.257 ms/op
                 listUser·p0.99:   8.012 ms/op
                 listUser·p0.999:  15.521 ms/op
                 listUser·p0.9999: 26.230 ms/op
                 listUser·p1.00:   27.558 ms/op

Iteration   3: 4.754 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.364 ms/op
                 listUser·p0.50:   4.571 ms/op
                 listUser·p0.90:   5.857 ms/op
                 listUser·p0.95:   6.636 ms/op
                 listUser·p0.99:   8.318 ms/op
                 listUser·p0.999:  18.866 ms/op
                 listUser·p0.9999: 22.768 ms/op
                 listUser·p1.00:   23.298 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 201553
  mean =      4.760 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 336 
    [ 2.500,  5.000) = 155768 
    [ 5.000,  7.500) = 41445 
    [ 7.500, 10.000) = 3444 
    [10.000, 12.500) = 223 
    [12.500, 15.000) = 59 
    [15.000, 17.500) = 115 
    [17.500, 20.000) = 51 
    [20.000, 22.500) = 45 
    [22.500, 25.000) = 43 
    [25.000, 27.500) = 23 

  Percentiles, ms/op:
      p(0.0000) =      1.067 ms/op
     p(50.0000) =      4.604 ms/op
     p(90.0000) =      5.677 ms/op
     p(95.0000) =      6.463 ms/op
     p(99.0000) =      8.159 ms/op
     p(99.9000) =     15.925 ms/op
     p(99.9900) =     25.342 ms/op
     p(99.9990) =     26.540 ms/op
     p(99.9999) =     27.558 ms/op
    p(100.0000) =     27.558 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.867 ± 2.401  ops/ms
ClientGrpc.existUser                       thrpt       3   9.217 ± 4.832  ops/ms
ClientGrpc.getUser                         thrpt       3   8.770 ± 1.076  ops/ms
ClientGrpc.listUser                        thrpt       3   6.629 ± 1.371  ops/ms
ClientGrpc.createUser                       avgt       3   3.582 ± 0.837   ms/op
ClientGrpc.existUser                        avgt       3   3.428 ± 0.229   ms/op
ClientGrpc.getUser                          avgt       3   3.619 ± 0.660   ms/op
ClientGrpc.listUser                         avgt       3   4.706 ± 0.727   ms/op
ClientGrpc.createUser                     sample  261802   3.666 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.669           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.633           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.235           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.547           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.661           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.980           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          22.768           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          24.773           ms/op
ClientGrpc.existUser                      sample  275743   3.480 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.812           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.441           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.018           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.317           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.120           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.918           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.413           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.168           ms/op
ClientGrpc.getUser                        sample  262446   3.658 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.975           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.617           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.268           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.547           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.439           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.603           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.408           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.775           ms/op
ClientGrpc.listUser                       sample  201553   4.760 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.067           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.604           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.677           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.463           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.159           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.925           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.342           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.558           ms/op
