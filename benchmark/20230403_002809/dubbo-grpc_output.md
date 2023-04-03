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
# Warmup Iteration   1: 3.591 ops/ms
# Warmup Iteration   2: 8.479 ops/ms
# Warmup Iteration   3: 9.804 ops/ms
Iteration   1: 10.230 ops/ms
Iteration   2: 10.339 ops/ms
Iteration   3: 10.375 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.315 ±(99.9%) 1.374 ops/ms [Average]
  (min, avg, max) = (10.230, 10.315, 10.375), stdev = 0.075
  CI (99.9%): [8.941, 11.689] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.335 ops/ms
# Warmup Iteration   2: 10.138 ops/ms
# Warmup Iteration   3: 10.723 ops/ms
Iteration   1: 11.054 ops/ms
Iteration   2: 11.139 ops/ms
Iteration   3: 11.112 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.102 ±(99.9%) 0.789 ops/ms [Average]
  (min, avg, max) = (11.054, 11.102, 11.139), stdev = 0.043
  CI (99.9%): [10.313, 11.891] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 6.729 ops/ms
# Warmup Iteration   2: 10.178 ops/ms
# Warmup Iteration   3: 10.571 ops/ms
Iteration   1: 10.578 ops/ms
Iteration   2: 10.569 ops/ms
Iteration   3: 10.411 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.519 ±(99.9%) 1.714 ops/ms [Average]
  (min, avg, max) = (10.411, 10.519, 10.578), stdev = 0.094
  CI (99.9%): [8.805, 12.233] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.187 ops/ms
# Warmup Iteration   2: 7.620 ops/ms
# Warmup Iteration   3: 8.041 ops/ms
Iteration   1: 8.000 ops/ms
Iteration   2: 8.108 ops/ms
Iteration   3: 8.181 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.096 ±(99.9%) 1.659 ops/ms [Average]
  (min, avg, max) = (8.000, 8.096, 8.181), stdev = 0.091
  CI (99.9%): [6.437, 9.755] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.379 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.219 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.083 ±(99.9%) 0.003 ms/op
Iteration   1: 3.045 ±(99.9%) 0.002 ms/op
Iteration   2: 3.028 ±(99.9%) 0.003 ms/op
Iteration   3: 3.052 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.042 ±(99.9%) 0.223 ms/op [Average]
  (min, avg, max) = (3.028, 3.042, 3.052), stdev = 0.012
  CI (99.9%): [2.819, 3.265] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.996 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.047 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.932 ±(99.9%) 0.003 ms/op
Iteration   1: 2.909 ±(99.9%) 0.001 ms/op
Iteration   2: 2.946 ±(99.9%) 0.002 ms/op
Iteration   3: 2.930 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.929 ±(99.9%) 0.332 ms/op [Average]
  (min, avg, max) = (2.909, 2.929, 2.946), stdev = 0.018
  CI (99.9%): [2.596, 3.261] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.378 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.140 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.085 ±(99.9%) 0.003 ms/op
Iteration   1: 3.070 ±(99.9%) 0.003 ms/op
Iteration   2: 3.046 ±(99.9%) 0.002 ms/op
Iteration   3: 3.056 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.057 ±(99.9%) 0.222 ms/op [Average]
  (min, avg, max) = (3.046, 3.057, 3.070), stdev = 0.012
  CI (99.9%): [2.835, 3.279] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.792 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.119 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.987 ±(99.9%) 0.008 ms/op
Iteration   1: 3.986 ±(99.9%) 0.009 ms/op
Iteration   2: 3.813 ±(99.9%) 0.011 ms/op
Iteration   3: 3.986 ±(99.9%) 0.024 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.928 ±(99.9%) 1.818 ms/op [Average]
  (min, avg, max) = (3.813, 3.928, 3.986), stdev = 0.100
  CI (99.9%): [2.110, 5.746] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.348 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.189 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.048 ±(99.9%) 0.006 ms/op
Iteration   1: 3.022 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.795 ms/op
                 createUser·p0.50:   2.998 ms/op
                 createUser·p0.90:   3.527 ms/op
                 createUser·p0.95:   3.711 ms/op
                 createUser·p0.99:   4.599 ms/op
                 createUser·p0.999:  7.619 ms/op
                 createUser·p0.9999: 12.285 ms/op
                 createUser·p1.00:   13.943 ms/op

Iteration   2: 3.072 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.816 ms/op
                 createUser·p0.50:   3.027 ms/op
                 createUser·p0.90:   3.613 ms/op
                 createUser·p0.95:   3.850 ms/op
                 createUser·p0.99:   4.579 ms/op
                 createUser·p0.999:  7.406 ms/op
                 createUser·p0.9999: 14.454 ms/op
                 createUser·p1.00:   14.844 ms/op

Iteration   3: 3.027 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.571 ms/op
                 createUser·p0.50:   3.006 ms/op
                 createUser·p0.90:   3.596 ms/op
                 createUser·p0.95:   3.867 ms/op
                 createUser·p0.99:   4.751 ms/op
                 createUser·p0.999:  8.925 ms/op
                 createUser·p0.9999: 18.168 ms/op
                 createUser·p1.00:   18.579 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 315598
  mean =      3.040 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 726 
    [ 1.250,  2.500) = 24438 
    [ 2.500,  3.750) = 271801 
    [ 3.750,  5.000) = 16694 
    [ 5.000,  6.250) = 1077 
    [ 6.250,  7.500) = 416 
    [ 7.500,  8.750) = 159 
    [ 8.750, 10.000) = 80 
    [10.000, 11.250) = 16 
    [11.250, 12.500) = 59 
    [12.500, 13.750) = 6 
    [13.750, 15.000) = 62 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 36 
    [17.500, 18.750) = 28 

  Percentiles, ms/op:
      p(0.0000) =      0.571 ms/op
     p(50.0000) =      3.011 ms/op
     p(90.0000) =      3.576 ms/op
     p(95.0000) =      3.809 ms/op
     p(99.0000) =      4.637 ms/op
     p(99.9000) =      8.487 ms/op
     p(99.9900) =     17.381 ms/op
     p(99.9990) =     18.411 ms/op
     p(99.9999) =     18.579 ms/op
    p(100.0000) =     18.579 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.631 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.006 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.988 ±(99.9%) 0.006 ms/op
Iteration   1: 2.954 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.706 ms/op
                 existUser·p0.50:   2.929 ms/op
                 existUser·p0.90:   3.453 ms/op
                 existUser·p0.95:   3.666 ms/op
                 existUser·p0.99:   4.276 ms/op
                 existUser·p0.999:  6.324 ms/op
                 existUser·p0.9999: 12.798 ms/op
                 existUser·p1.00:   12.993 ms/op

Iteration   2: 2.928 ±(99.9%) 0.004 ms/op
                 existUser·p0.00:   0.821 ms/op
                 existUser·p0.50:   2.904 ms/op
                 existUser·p0.90:   3.342 ms/op
                 existUser·p0.95:   3.490 ms/op
                 existUser·p0.99:   3.973 ms/op
                 existUser·p0.999:  5.780 ms/op
                 existUser·p0.9999: 14.814 ms/op
                 existUser·p1.00:   15.139 ms/op

Iteration   3: 2.968 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.772 ms/op
                 existUser·p0.50:   2.937 ms/op
                 existUser·p0.90:   3.502 ms/op
                 existUser·p0.95:   3.703 ms/op
                 existUser·p0.99:   4.243 ms/op
                 existUser·p0.999:  9.028 ms/op
                 existUser·p0.9999: 16.739 ms/op
                 existUser·p1.00:   16.941 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 325395
  mean =      2.950 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 602 
    [ 1.250,  2.500) = 29658 
    [ 2.500,  3.750) = 284361 
    [ 3.750,  5.000) = 9616 
    [ 5.000,  6.250) = 754 
    [ 6.250,  7.500) = 165 
    [ 7.500,  8.750) = 15 
    [ 8.750, 10.000) = 61 
    [10.000, 11.250) = 3 
    [11.250, 12.500) = 19 
    [12.500, 13.750) = 45 
    [13.750, 15.000) = 57 
    [15.000, 16.250) = 20 
    [16.250, 17.500) = 19 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.706 ms/op
     p(50.0000) =      2.925 ms/op
     p(90.0000) =      3.424 ms/op
     p(95.0000) =      3.637 ms/op
     p(99.0000) =      4.166 ms/op
     p(99.9000) =      6.496 ms/op
     p(99.9900) =     15.634 ms/op
     p(99.9990) =     16.908 ms/op
     p(99.9999) =     16.941 ms/op
    p(100.0000) =     16.941 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.128 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.117 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.091 ±(99.9%) 0.007 ms/op
Iteration   1: 3.043 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.890 ms/op
                 getUser·p0.50:   3.002 ms/op
                 getUser·p0.90:   3.559 ms/op
                 getUser·p0.95:   3.813 ms/op
                 getUser·p0.99:   4.473 ms/op
                 getUser·p0.999:  7.314 ms/op
                 getUser·p0.9999: 14.434 ms/op
                 getUser·p1.00:   14.680 ms/op

Iteration   2: 3.041 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.894 ms/op
                 getUser·p0.50:   3.011 ms/op
                 getUser·p0.90:   3.527 ms/op
                 getUser·p0.95:   3.707 ms/op
                 getUser·p0.99:   4.276 ms/op
                 getUser·p0.999:  6.469 ms/op
                 getUser·p0.9999: 15.376 ms/op
                 getUser·p1.00:   15.991 ms/op

Iteration   3: 3.046 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.742 ms/op
                 getUser·p0.50:   3.019 ms/op
                 getUser·p0.90:   3.469 ms/op
                 getUser·p0.95:   3.662 ms/op
                 getUser·p0.99:   4.350 ms/op
                 getUser·p0.999:  7.036 ms/op
                 getUser·p0.9999: 24.543 ms/op
                 getUser·p1.00:   24.838 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 315517
  mean =      3.043 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15324 
    [ 2.500,  5.000) = 298915 
    [ 5.000,  7.500) = 1037 
    [ 7.500, 10.000) = 49 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 101 
    [15.000, 17.500) = 61 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.742 ms/op
     p(50.0000) =      3.011 ms/op
     p(90.0000) =      3.514 ms/op
     p(95.0000) =      3.731 ms/op
     p(99.0000) =      4.375 ms/op
     p(99.9000) =      6.914 ms/op
     p(99.9900) =     16.985 ms/op
     p(99.9990) =     24.773 ms/op
     p(99.9999) =     24.838 ms/op
    p(100.0000) =     24.838 ms/op


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
# Warmup Iteration   1: 5.640 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 4.083 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.065 ±(99.9%) 0.014 ms/op
Iteration   1: 3.911 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.135 ms/op
                 listUser·p0.50:   3.736 ms/op
                 listUser·p0.90:   4.899 ms/op
                 listUser·p0.95:   5.497 ms/op
                 listUser·p0.99:   6.929 ms/op
                 listUser·p0.999:  16.746 ms/op
                 listUser·p0.9999: 21.018 ms/op
                 listUser·p1.00:   21.365 ms/op

Iteration   2: 3.957 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.417 ms/op
                 listUser·p0.50:   3.809 ms/op
                 listUser·p0.90:   4.735 ms/op
                 listUser·p0.95:   5.497 ms/op
                 listUser·p0.99:   7.036 ms/op
                 listUser·p0.999:  14.205 ms/op
                 listUser·p0.9999: 22.017 ms/op
                 listUser·p1.00:   24.052 ms/op

Iteration   3: 4.017 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.992 ms/op
                 listUser·p0.50:   3.834 ms/op
                 listUser·p0.90:   5.079 ms/op
                 listUser·p0.95:   5.775 ms/op
                 listUser·p0.99:   6.988 ms/op
                 listUser·p0.999:  18.887 ms/op
                 listUser·p0.9999: 26.708 ms/op
                 listUser·p1.00:   27.787 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 242379
  mean =      3.961 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2061 
    [ 2.500,  5.000) = 218042 
    [ 5.000,  7.500) = 20820 
    [ 7.500, 10.000) = 994 
    [10.000, 12.500) = 64 
    [12.500, 15.000) = 59 
    [15.000, 17.500) = 138 
    [17.500, 20.000) = 102 
    [20.000, 22.500) = 56 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 33 

  Percentiles, ms/op:
      p(0.0000) =      0.992 ms/op
     p(50.0000) =      3.793 ms/op
     p(90.0000) =      4.923 ms/op
     p(95.0000) =      5.595 ms/op
     p(99.0000) =      6.980 ms/op
     p(99.9000) =     16.761 ms/op
     p(99.9900) =     25.362 ms/op
     p(99.9990) =     27.151 ms/op
     p(99.9999) =     27.787 ms/op
    p(100.0000) =     27.787 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.315 ± 1.374  ops/ms
ClientGrpc.existUser                       thrpt       3  11.102 ± 0.789  ops/ms
ClientGrpc.getUser                         thrpt       3  10.519 ± 1.714  ops/ms
ClientGrpc.listUser                        thrpt       3   8.096 ± 1.659  ops/ms
ClientGrpc.createUser                       avgt       3   3.042 ± 0.223   ms/op
ClientGrpc.existUser                        avgt       3   2.929 ± 0.332   ms/op
ClientGrpc.getUser                          avgt       3   3.057 ± 0.222   ms/op
ClientGrpc.listUser                         avgt       3   3.928 ± 1.818   ms/op
ClientGrpc.createUser                     sample  315598   3.040 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.571           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.011           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.576           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.809           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.637           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.487           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.381           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          18.579           ms/op
ClientGrpc.existUser                      sample  325395   2.950 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.706           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.925           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.424           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.637           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.166           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.496           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.634           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          16.941           ms/op
ClientGrpc.getUser                        sample  315517   3.043 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.742           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.011           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.514           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.731           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.375           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.914           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.985           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          24.838           ms/op
ClientGrpc.listUser                       sample  242379   3.961 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.992           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.793           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.923           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.595           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.980           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.761           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.362           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.787           ms/op
