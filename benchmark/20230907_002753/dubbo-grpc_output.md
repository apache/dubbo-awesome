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
# Warmup Iteration   1: 4.746 ops/ms
# Warmup Iteration   2: 9.131 ops/ms
# Warmup Iteration   3: 10.630 ops/ms
Iteration   1: 10.510 ops/ms
Iteration   2: 10.853 ops/ms
Iteration   3: 10.683 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.682 ±(99.9%) 3.130 ops/ms [Average]
  (min, avg, max) = (10.510, 10.682, 10.853), stdev = 0.172
  CI (99.9%): [7.552, 13.812] (assumes normal distribution)


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
# Warmup Iteration   1: 7.887 ops/ms
# Warmup Iteration   2: 10.803 ops/ms
# Warmup Iteration   3: 11.224 ops/ms
Iteration   1: 11.257 ops/ms
Iteration   2: 11.293 ops/ms
Iteration   3: 11.374 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.308 ±(99.9%) 1.099 ops/ms [Average]
  (min, avg, max) = (11.257, 11.308, 11.374), stdev = 0.060
  CI (99.9%): [10.209, 12.407] (assumes normal distribution)


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
# Warmup Iteration   1: 7.865 ops/ms
# Warmup Iteration   2: 10.403 ops/ms
# Warmup Iteration   3: 10.801 ops/ms
Iteration   1: 10.709 ops/ms
Iteration   2: 10.659 ops/ms
Iteration   3: 10.870 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.746 ±(99.9%) 2.009 ops/ms [Average]
  (min, avg, max) = (10.659, 10.746, 10.870), stdev = 0.110
  CI (99.9%): [8.737, 12.755] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 7.175 ops/ms
# Warmup Iteration   2: 7.682 ops/ms
# Warmup Iteration   3: 8.305 ops/ms
Iteration   1: 8.350 ops/ms
Iteration   2: 8.413 ops/ms
Iteration   3: 8.198 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.321 ±(99.9%) 2.015 ops/ms [Average]
  (min, avg, max) = (8.198, 8.321, 8.413), stdev = 0.110
  CI (99.9%): [6.306, 10.335] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.549 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.069 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.049 ±(99.9%) 0.002 ms/op
Iteration   1: 2.942 ±(99.9%) 0.002 ms/op
Iteration   2: 2.973 ±(99.9%) 0.003 ms/op
Iteration   3: 3.001 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.972 ±(99.9%) 0.532 ms/op [Average]
  (min, avg, max) = (2.942, 2.972, 3.001), stdev = 0.029
  CI (99.9%): [2.440, 3.504] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.653 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.000 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.915 ±(99.9%) 0.003 ms/op
Iteration   1: 2.810 ±(99.9%) 0.004 ms/op
Iteration   2: 2.832 ±(99.9%) 0.004 ms/op
Iteration   3: 2.778 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.807 ±(99.9%) 0.494 ms/op [Average]
  (min, avg, max) = (2.778, 2.807, 2.832), stdev = 0.027
  CI (99.9%): [2.313, 3.301] (assumes normal distribution)


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
# Warmup Iteration   1: 3.865 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.027 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 2.929 ±(99.9%) 0.003 ms/op
Iteration   1: 3.023 ±(99.9%) 0.003 ms/op
Iteration   2: 2.964 ±(99.9%) 0.002 ms/op
Iteration   3: 2.947 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.978 ±(99.9%) 0.726 ms/op [Average]
  (min, avg, max) = (2.947, 2.978, 3.023), stdev = 0.040
  CI (99.9%): [2.252, 3.704] (assumes normal distribution)


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
# Warmup Iteration   1: 4.933 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.919 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.916 ±(99.9%) 0.009 ms/op
Iteration   1: 3.912 ±(99.9%) 0.032 ms/op
Iteration   2: 3.843 ±(99.9%) 0.054 ms/op
Iteration   3: 3.896 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.883 ±(99.9%) 0.659 ms/op [Average]
  (min, avg, max) = (3.843, 3.883, 3.912), stdev = 0.036
  CI (99.9%): [3.224, 4.543] (assumes normal distribution)


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
# Warmup Iteration   1: 4.019 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.085 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.957 ±(99.9%) 0.006 ms/op
Iteration   1: 2.942 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.340 ms/op
                 createUser·p0.50:   2.933 ms/op
                 createUser·p0.90:   3.367 ms/op
                 createUser·p0.95:   3.555 ms/op
                 createUser·p0.99:   4.399 ms/op
                 createUser·p0.999:  7.866 ms/op
                 createUser·p0.9999: 13.437 ms/op
                 createUser·p1.00:   13.599 ms/op

Iteration   2: 2.959 ±(99.9%) 0.004 ms/op
                 createUser·p0.00:   0.863 ms/op
                 createUser·p0.50:   2.949 ms/op
                 createUser·p0.90:   3.273 ms/op
                 createUser·p0.95:   3.396 ms/op
                 createUser·p0.99:   4.108 ms/op
                 createUser·p0.999:  6.945 ms/op
                 createUser·p0.9999: 12.717 ms/op
                 createUser·p1.00:   12.911 ms/op

Iteration   3: 2.951 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.559 ms/op
                 createUser·p0.50:   2.941 ms/op
                 createUser·p0.90:   3.400 ms/op
                 createUser·p0.95:   3.621 ms/op
                 createUser·p0.99:   4.604 ms/op
                 createUser·p0.999:  10.240 ms/op
                 createUser·p0.9999: 14.617 ms/op
                 createUser·p1.00:   14.909 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 325341
  mean =      2.951 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1404 
    [ 1.250,  2.500) = 23878 
    [ 2.500,  3.750) = 290780 
    [ 3.750,  5.000) = 7517 
    [ 5.000,  6.250) = 932 
    [ 6.250,  7.500) = 405 
    [ 7.500,  8.750) = 153 
    [ 8.750, 10.000) = 15 
    [10.000, 11.250) = 63 
    [11.250, 12.500) = 40 
    [12.500, 13.750) = 102 
    [13.750, 15.000) = 52 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.340 ms/op
     p(50.0000) =      2.941 ms/op
     p(90.0000) =      3.342 ms/op
     p(95.0000) =      3.535 ms/op
     p(99.0000) =      4.432 ms/op
     p(99.9000) =      8.271 ms/op
     p(99.9900) =     14.147 ms/op
     p(99.9990) =     14.709 ms/op
     p(99.9999) =     14.909 ms/op
    p(100.0000) =     14.909 ms/op


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
# Warmup Iteration   1: 3.779 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 2.983 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.938 ±(99.9%) 0.006 ms/op
Iteration   1: 2.907 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.546 ms/op
                 existUser·p0.50:   2.875 ms/op
                 existUser·p0.90:   3.445 ms/op
                 existUser·p0.95:   3.637 ms/op
                 existUser·p0.99:   4.383 ms/op
                 existUser·p0.999:  7.372 ms/op
                 existUser·p0.9999: 10.994 ms/op
                 existUser·p1.00:   11.108 ms/op

Iteration   2: 2.800 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.520 ms/op
                 existUser·p0.50:   2.834 ms/op
                 existUser·p0.90:   3.248 ms/op
                 existUser·p0.95:   3.502 ms/op
                 existUser·p0.99:   4.596 ms/op
                 existUser·p0.999:  7.593 ms/op
                 existUser·p0.9999: 13.906 ms/op
                 existUser·p1.00:   14.287 ms/op

Iteration   3: 2.827 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.621 ms/op
                 existUser·p0.50:   2.847 ms/op
                 existUser·p0.90:   3.482 ms/op
                 existUser·p0.95:   3.736 ms/op
                 existUser·p0.99:   4.547 ms/op
                 existUser·p0.999:  7.232 ms/op
                 existUser·p0.9999: 26.128 ms/op
                 existUser·p1.00:   26.640 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 337286
  mean =      2.844 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 56606 
    [ 2.500,  5.000) = 279208 
    [ 5.000,  7.500) = 1151 
    [ 7.500, 10.000) = 170 
    [10.000, 12.500) = 57 
    [12.500, 15.000) = 62 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.520 ms/op
     p(50.0000) =      2.851 ms/op
     p(90.0000) =      3.400 ms/op
     p(95.0000) =      3.650 ms/op
     p(99.0000) =      4.506 ms/op
     p(99.9000) =      7.430 ms/op
     p(99.9900) =     14.251 ms/op
     p(99.9990) =     26.530 ms/op
     p(99.9999) =     26.640 ms/op
    p(100.0000) =     26.640 ms/op


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
# Warmup Iteration   1: 3.880 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.004 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.982 ±(99.9%) 0.006 ms/op
Iteration   1: 2.970 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.458 ms/op
                 getUser·p0.50:   2.945 ms/op
                 getUser·p0.90:   3.453 ms/op
                 getUser·p0.95:   3.674 ms/op
                 getUser·p0.99:   4.466 ms/op
                 getUser·p0.999:  8.110 ms/op
                 getUser·p0.9999: 11.296 ms/op
                 getUser·p1.00:   11.846 ms/op

Iteration   2: 2.951 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.722 ms/op
                 getUser·p0.50:   2.941 ms/op
                 getUser·p0.90:   3.334 ms/op
                 getUser·p0.95:   3.584 ms/op
                 getUser·p0.99:   4.465 ms/op
                 getUser·p0.999:  7.455 ms/op
                 getUser·p0.9999: 21.533 ms/op
                 getUser·p1.00:   21.856 ms/op

Iteration   3: 2.936 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.614 ms/op
                 getUser·p0.50:   2.925 ms/op
                 getUser·p0.90:   3.371 ms/op
                 getUser·p0.95:   3.609 ms/op
                 getUser·p0.99:   4.383 ms/op
                 getUser·p0.999:  7.807 ms/op
                 getUser·p0.9999: 17.603 ms/op
                 getUser·p1.00:   19.038 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 325248
  mean =      2.952 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 28023 
    [ 2.500,  5.000) = 295401 
    [ 5.000,  7.500) = 1399 
    [ 7.500, 10.000) = 241 
    [10.000, 12.500) = 56 
    [12.500, 15.000) = 57 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.458 ms/op
     p(50.0000) =      2.937 ms/op
     p(90.0000) =      3.387 ms/op
     p(95.0000) =      3.625 ms/op
     p(99.0000) =      4.432 ms/op
     p(99.9000) =      7.848 ms/op
     p(99.9900) =     19.832 ms/op
     p(99.9990) =     21.807 ms/op
     p(99.9999) =     21.856 ms/op
    p(100.0000) =     21.856 ms/op


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
# Warmup Iteration   1: 4.609 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 4.039 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.929 ±(99.9%) 0.010 ms/op
Iteration   1: 3.799 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.051 ms/op
                 listUser·p0.50:   3.662 ms/op
                 listUser·p0.90:   4.874 ms/op
                 listUser·p0.95:   5.480 ms/op
                 listUser·p0.99:   6.904 ms/op
                 listUser·p0.999:  12.971 ms/op
                 listUser·p0.9999: 14.539 ms/op
                 listUser·p1.00:   15.319 ms/op

Iteration   2: 3.884 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.959 ms/op
                 listUser·p0.50:   3.727 ms/op
                 listUser·p0.90:   4.858 ms/op
                 listUser·p0.95:   5.390 ms/op
                 listUser·p0.99:   6.939 ms/op
                 listUser·p0.999:  15.283 ms/op
                 listUser·p0.9999: 24.953 ms/op
                 listUser·p1.00:   25.264 ms/op

Iteration   3: 3.898 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.522 ms/op
                 listUser·p0.50:   3.752 ms/op
                 listUser·p0.90:   4.801 ms/op
                 listUser·p0.95:   5.562 ms/op
                 listUser·p0.99:   7.021 ms/op
                 listUser·p0.999:  20.762 ms/op
                 listUser·p0.9999: 24.543 ms/op
                 listUser·p1.00:   24.773 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 249004
  mean =      3.860 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5405 
    [ 2.500,  5.000) = 222577 
    [ 5.000,  7.500) = 19499 
    [ 7.500, 10.000) = 1003 
    [10.000, 12.500) = 93 
    [12.500, 15.000) = 148 
    [15.000, 17.500) = 58 
    [17.500, 20.000) = 60 
    [20.000, 22.500) = 83 
    [22.500, 25.000) = 71 
    [25.000, 27.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.522 ms/op
     p(50.0000) =      3.715 ms/op
     p(90.0000) =      4.850 ms/op
     p(95.0000) =      5.480 ms/op
     p(99.0000) =      6.955 ms/op
     p(99.9000) =     16.171 ms/op
     p(99.9900) =     24.248 ms/op
     p(99.9990) =     25.134 ms/op
     p(99.9999) =     25.264 ms/op
    p(100.0000) =     25.264 ms/op


# Run complete. Total time: 00:13:02

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.682 ± 3.130  ops/ms
ClientGrpc.existUser                       thrpt       3  11.308 ± 1.099  ops/ms
ClientGrpc.getUser                         thrpt       3  10.746 ± 2.009  ops/ms
ClientGrpc.listUser                        thrpt       3   8.321 ± 2.015  ops/ms
ClientGrpc.createUser                       avgt       3   2.972 ± 0.532   ms/op
ClientGrpc.existUser                        avgt       3   2.807 ± 0.494   ms/op
ClientGrpc.getUser                          avgt       3   2.978 ± 0.726   ms/op
ClientGrpc.listUser                         avgt       3   3.883 ± 0.659   ms/op
ClientGrpc.createUser                     sample  325341   2.951 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.340           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.941           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.342           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.535           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.432           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.271           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          14.147           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          14.909           ms/op
ClientGrpc.existUser                      sample  337286   2.844 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.520           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.851           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.400           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.650           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.506           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.430           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.251           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          26.640           ms/op
ClientGrpc.getUser                        sample  325248   2.952 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.458           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.937           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.387           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.625           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.432           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.848           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.832           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.856           ms/op
ClientGrpc.listUser                       sample  249004   3.860 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.522           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.715           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.850           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.480           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.955           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.171           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.248           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.264           ms/op
