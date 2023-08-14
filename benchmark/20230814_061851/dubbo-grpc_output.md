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
# Warmup Iteration   1: 4.738 ops/ms
# Warmup Iteration   2: 9.725 ops/ms
# Warmup Iteration   3: 10.412 ops/ms
Iteration   1: 10.899 ops/ms
Iteration   2: 10.807 ops/ms
Iteration   3: 10.874 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.860 ±(99.9%) 0.875 ops/ms [Average]
  (min, avg, max) = (10.807, 10.860, 10.899), stdev = 0.048
  CI (99.9%): [9.985, 11.735] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 8.027 ops/ms
# Warmup Iteration   2: 10.774 ops/ms
# Warmup Iteration   3: 11.208 ops/ms
Iteration   1: 11.273 ops/ms
Iteration   2: 11.167 ops/ms
Iteration   3: 11.321 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.254 ±(99.9%) 1.438 ops/ms [Average]
  (min, avg, max) = (11.167, 11.254, 11.321), stdev = 0.079
  CI (99.9%): [9.816, 12.692] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 8.169 ops/ms
# Warmup Iteration   2: 10.336 ops/ms
# Warmup Iteration   3: 10.744 ops/ms
Iteration   1: 10.870 ops/ms
Iteration   2: 10.933 ops/ms
Iteration   3: 10.818 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.874 ±(99.9%) 1.052 ops/ms [Average]
  (min, avg, max) = (10.818, 10.874, 10.933), stdev = 0.058
  CI (99.9%): [9.822, 11.926] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 7.193 ops/ms
# Warmup Iteration   2: 8.011 ops/ms
# Warmup Iteration   3: 8.168 ops/ms
Iteration   1: 8.481 ops/ms
Iteration   2: 8.241 ops/ms
Iteration   3: 8.317 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.346 ±(99.9%) 2.245 ops/ms [Average]
  (min, avg, max) = (8.241, 8.346, 8.481), stdev = 0.123
  CI (99.9%): [6.102, 10.591] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 3.853 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.121 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.961 ±(99.9%) 0.003 ms/op
Iteration   1: 3.030 ±(99.9%) 0.004 ms/op
Iteration   2: 3.039 ±(99.9%) 0.002 ms/op
Iteration   3: 2.988 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.019 ±(99.9%) 0.495 ms/op [Average]
  (min, avg, max) = (2.988, 3.019, 3.039), stdev = 0.027
  CI (99.9%): [2.525, 3.514] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.593 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 2.890 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.765 ±(99.9%) 0.005 ms/op
Iteration   1: 2.732 ±(99.9%) 0.004 ms/op
Iteration   2: 2.841 ±(99.9%) 0.002 ms/op
Iteration   3: 2.821 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.798 ±(99.9%) 1.053 ms/op [Average]
  (min, avg, max) = (2.732, 2.798, 2.841), stdev = 0.058
  CI (99.9%): [1.745, 3.851] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.876 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.039 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.022 ±(99.9%) 0.003 ms/op
Iteration   1: 2.946 ±(99.9%) 0.003 ms/op
Iteration   2: 2.943 ±(99.9%) 0.002 ms/op
Iteration   3: 2.937 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.942 ±(99.9%) 0.091 ms/op [Average]
  (min, avg, max) = (2.937, 2.942, 2.946), stdev = 0.005
  CI (99.9%): [2.851, 3.033] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 5.175 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.015 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 3.887 ±(99.9%) 0.018 ms/op
Iteration   1: 3.912 ±(99.9%) 0.025 ms/op
Iteration   2: 3.868 ±(99.9%) 0.013 ms/op
Iteration   3: 3.840 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.873 ±(99.9%) 0.662 ms/op [Average]
  (min, avg, max) = (3.840, 3.873, 3.912), stdev = 0.036
  CI (99.9%): [3.211, 4.536] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.556 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.136 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.006 ±(99.9%) 0.008 ms/op
Iteration   1: 2.943 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.406 ms/op
                 createUser·p0.50:   2.929 ms/op
                 createUser·p0.90:   3.424 ms/op
                 createUser·p0.95:   3.736 ms/op
                 createUser·p0.99:   4.588 ms/op
                 createUser·p0.999:  7.538 ms/op
                 createUser·p0.9999: 15.600 ms/op
                 createUser·p1.00:   15.892 ms/op

Iteration   2: 2.964 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.554 ms/op
                 createUser·p0.50:   2.949 ms/op
                 createUser·p0.90:   3.523 ms/op
                 createUser·p0.95:   3.781 ms/op
                 createUser·p0.99:   4.579 ms/op
                 createUser·p0.999:  7.209 ms/op
                 createUser·p0.9999: 17.341 ms/op
                 createUser·p1.00:   17.564 ms/op

Iteration   3: 2.914 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.689 ms/op
                 createUser·p0.50:   2.900 ms/op
                 createUser·p0.90:   3.334 ms/op
                 createUser·p0.95:   3.641 ms/op
                 createUser·p0.99:   4.538 ms/op
                 createUser·p0.999:  7.835 ms/op
                 createUser·p0.9999: 22.381 ms/op
                 createUser·p1.00:   22.741 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 326568
  mean =      2.940 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 35226 
    [ 2.500,  5.000) = 289646 
    [ 5.000,  7.500) = 1356 
    [ 7.500, 10.000) = 138 
    [10.000, 12.500) = 10 
    [12.500, 15.000) = 35 
    [15.000, 17.500) = 98 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.406 ms/op
     p(50.0000) =      2.925 ms/op
     p(90.0000) =      3.432 ms/op
     p(95.0000) =      3.731 ms/op
     p(99.0000) =      4.571 ms/op
     p(99.9000) =      7.569 ms/op
     p(99.9900) =     19.142 ms/op
     p(99.9990) =     22.593 ms/op
     p(99.9999) =     22.741 ms/op
    p(100.0000) =     22.741 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.800 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 2.881 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.872 ±(99.9%) 0.006 ms/op
Iteration   1: 2.815 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.487 ms/op
                 existUser·p0.50:   2.839 ms/op
                 existUser·p0.90:   3.449 ms/op
                 existUser·p0.95:   3.711 ms/op
                 existUser·p0.99:   4.514 ms/op
                 existUser·p0.999:  7.788 ms/op
                 existUser·p0.9999: 11.801 ms/op
                 existUser·p1.00:   12.239 ms/op

Iteration   2: 2.813 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.557 ms/op
                 existUser·p0.50:   2.843 ms/op
                 existUser·p0.90:   3.355 ms/op
                 existUser·p0.95:   3.658 ms/op
                 existUser·p0.99:   4.555 ms/op
                 existUser·p0.999:  7.527 ms/op
                 existUser·p0.9999: 17.485 ms/op
                 existUser·p1.00:   19.333 ms/op

Iteration   3: 2.891 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.602 ms/op
                 existUser·p0.50:   2.863 ms/op
                 existUser·p0.90:   3.367 ms/op
                 existUser·p0.95:   3.617 ms/op
                 existUser·p0.99:   4.530 ms/op
                 existUser·p0.999:  9.290 ms/op
                 existUser·p0.9999: 15.385 ms/op
                 existUser·p1.00:   16.433 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 338136
  mean =      2.839 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 6523 
    [ 1.250,  2.500) = 50616 
    [ 2.500,  3.750) = 267743 
    [ 3.750,  5.000) = 11573 
    [ 5.000,  6.250) = 868 
    [ 6.250,  7.500) = 357 
    [ 7.500,  8.750) = 196 
    [ 8.750, 10.000) = 36 
    [10.000, 11.250) = 18 
    [11.250, 12.500) = 46 
    [12.500, 13.750) = 51 
    [13.750, 15.000) = 27 
    [15.000, 16.250) = 22 
    [16.250, 17.500) = 50 
    [17.500, 18.750) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.487 ms/op
     p(50.0000) =      2.847 ms/op
     p(90.0000) =      3.391 ms/op
     p(95.0000) =      3.662 ms/op
     p(99.0000) =      4.530 ms/op
     p(99.9000) =      7.953 ms/op
     p(99.9900) =     17.039 ms/op
     p(99.9990) =     19.243 ms/op
     p(99.9999) =     19.333 ms/op
    p(100.0000) =     19.333 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.791 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.045 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.942 ±(99.9%) 0.006 ms/op
Iteration   1: 3.002 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.665 ms/op
                 getUser·p0.50:   2.970 ms/op
                 getUser·p0.90:   3.387 ms/op
                 getUser·p0.95:   3.531 ms/op
                 getUser·p0.99:   4.538 ms/op
                 getUser·p0.999:  8.036 ms/op
                 getUser·p0.9999: 13.096 ms/op
                 getUser·p1.00:   13.287 ms/op

Iteration   2: 2.969 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.757 ms/op
                 getUser·p0.50:   2.933 ms/op
                 getUser·p0.90:   3.400 ms/op
                 getUser·p0.95:   3.719 ms/op
                 getUser·p0.99:   4.973 ms/op
                 getUser·p0.999:  8.991 ms/op
                 getUser·p0.9999: 20.127 ms/op
                 getUser·p1.00:   20.349 ms/op

Iteration   3: 2.951 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.754 ms/op
                 getUser·p0.50:   2.941 ms/op
                 getUser·p0.90:   3.453 ms/op
                 getUser·p0.95:   3.703 ms/op
                 getUser·p0.99:   4.547 ms/op
                 getUser·p0.999:  9.363 ms/op
                 getUser·p0.9999: 14.720 ms/op
                 getUser·p1.00:   15.974 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 322888
  mean =      2.974 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25879 
    [ 2.500,  5.000) = 294631 
    [ 5.000,  7.500) = 1721 
    [ 7.500, 10.000) = 415 
    [10.000, 12.500) = 93 
    [12.500, 15.000) = 113 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.665 ms/op
     p(50.0000) =      2.949 ms/op
     p(90.0000) =      3.412 ms/op
     p(95.0000) =      3.641 ms/op
     p(99.0000) =      4.653 ms/op
     p(99.9000) =      8.521 ms/op
     p(99.9900) =     18.666 ms/op
     p(99.9990) =     20.276 ms/op
     p(99.9999) =     20.349 ms/op
    p(100.0000) =     20.349 ms/op


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
# Warmup Iteration   1: 4.618 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.945 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.794 ±(99.9%) 0.010 ms/op
Iteration   1: 3.926 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.810 ms/op
                 listUser·p0.50:   3.736 ms/op
                 listUser·p0.90:   5.186 ms/op
                 listUser·p0.95:   5.833 ms/op
                 listUser·p0.99:   7.209 ms/op
                 listUser·p0.999:  12.674 ms/op
                 listUser·p0.9999: 14.874 ms/op
                 listUser·p1.00:   15.221 ms/op

Iteration   2: 3.811 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.986 ms/op
                 listUser·p0.50:   3.695 ms/op
                 listUser·p0.90:   4.628 ms/op
                 listUser·p0.95:   5.333 ms/op
                 listUser·p0.99:   6.676 ms/op
                 listUser·p0.999:  22.388 ms/op
                 listUser·p0.9999: 26.995 ms/op
                 listUser·p1.00:   27.460 ms/op

Iteration   3: 3.757 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.016 ms/op
                 listUser·p0.50:   3.576 ms/op
                 listUser·p0.90:   4.997 ms/op
                 listUser·p0.95:   5.489 ms/op
                 listUser·p0.99:   7.056 ms/op
                 listUser·p0.999:  13.937 ms/op
                 listUser·p0.9999: 18.448 ms/op
                 listUser·p1.00:   18.711 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 250641
  mean =      3.830 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7543 
    [ 2.500,  5.000) = 219509 
    [ 5.000,  7.500) = 21929 
    [ 7.500, 10.000) = 1067 
    [10.000, 12.500) = 231 
    [12.500, 15.000) = 175 
    [15.000, 17.500) = 70 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 46 
    [25.000, 27.500) = 36 

  Percentiles, ms/op:
      p(0.0000) =      0.810 ms/op
     p(50.0000) =      3.674 ms/op
     p(90.0000) =      4.948 ms/op
     p(95.0000) =      5.579 ms/op
     p(99.0000) =      6.988 ms/op
     p(99.9000) =     14.063 ms/op
     p(99.9900) =     26.212 ms/op
     p(99.9990) =     27.394 ms/op
     p(99.9999) =     27.460 ms/op
    p(100.0000) =     27.460 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.860 ± 0.875  ops/ms
ClientGrpc.existUser                       thrpt       3  11.254 ± 1.438  ops/ms
ClientGrpc.getUser                         thrpt       3  10.874 ± 1.052  ops/ms
ClientGrpc.listUser                        thrpt       3   8.346 ± 2.245  ops/ms
ClientGrpc.createUser                       avgt       3   3.019 ± 0.495   ms/op
ClientGrpc.existUser                        avgt       3   2.798 ± 1.053   ms/op
ClientGrpc.getUser                          avgt       3   2.942 ± 0.091   ms/op
ClientGrpc.listUser                         avgt       3   3.873 ± 0.662   ms/op
ClientGrpc.createUser                     sample  326568   2.940 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.406           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.925           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.432           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.731           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.571           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.569           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.142           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.741           ms/op
ClientGrpc.existUser                      sample  338136   2.839 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.487           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.847           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.391           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.662           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.530           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.953           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.039           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.333           ms/op
ClientGrpc.getUser                        sample  322888   2.974 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.665           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.949           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.412           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.641           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.653           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.521           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.666           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.349           ms/op
ClientGrpc.listUser                       sample  250641   3.830 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.810           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.674           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.948           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.579           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.988           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.063           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          26.212           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.460           ms/op
