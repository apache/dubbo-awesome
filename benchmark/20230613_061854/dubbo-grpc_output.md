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
# Warmup Iteration   1: 3.115 ops/ms
# Warmup Iteration   2: 7.357 ops/ms
# Warmup Iteration   3: 8.491 ops/ms
Iteration   1: 8.658 ops/ms
Iteration   2: 8.845 ops/ms
Iteration   3: 8.866 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.790 ±(99.9%) 2.088 ops/ms [Average]
  (min, avg, max) = (8.658, 8.790, 8.866), stdev = 0.114
  CI (99.9%): [6.702, 10.877] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 6.297 ops/ms
# Warmup Iteration   2: 9.140 ops/ms
# Warmup Iteration   3: 9.334 ops/ms
Iteration   1: 9.736 ops/ms
Iteration   2: 9.796 ops/ms
Iteration   3: 9.394 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.642 ±(99.9%) 3.962 ops/ms [Average]
  (min, avg, max) = (9.394, 9.642, 9.796), stdev = 0.217
  CI (99.9%): [5.680, 13.605] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:54
# Fork: 1 of 1
# Warmup Iteration   1: 5.959 ops/ms
# Warmup Iteration   2: 8.341 ops/ms
# Warmup Iteration   3: 8.799 ops/ms
Iteration   1: 8.801 ops/ms
Iteration   2: 8.917 ops/ms
Iteration   3: 9.166 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.962 ±(99.9%) 3.402 ops/ms [Average]
  (min, avg, max) = (8.801, 8.962, 9.166), stdev = 0.186
  CI (99.9%): [5.560, 12.364] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 4.316 ops/ms
# Warmup Iteration   2: 6.194 ops/ms
# Warmup Iteration   3: 6.808 ops/ms
Iteration   1: 6.694 ops/ms
Iteration   2: 6.568 ops/ms
Iteration   3: 6.924 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.729 ±(99.9%) 3.297 ops/ms [Average]
  (min, avg, max) = (6.568, 6.729, 6.924), stdev = 0.181
  CI (99.9%): [3.432, 10.025] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 5.350 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.942 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.677 ±(99.9%) 0.012 ms/op
Iteration   1: 3.693 ±(99.9%) 0.003 ms/op
Iteration   2: 3.567 ±(99.9%) 0.002 ms/op
Iteration   3: 3.474 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.578 ±(99.9%) 2.012 ms/op [Average]
  (min, avg, max) = (3.474, 3.578, 3.693), stdev = 0.110
  CI (99.9%): [1.566, 5.590] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.966 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.569 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.416 ±(99.9%) 0.003 ms/op
Iteration   1: 3.326 ±(99.9%) 0.002 ms/op
Iteration   2: 3.363 ±(99.9%) 0.002 ms/op
Iteration   3: 3.425 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.372 ±(99.9%) 0.911 ms/op [Average]
  (min, avg, max) = (3.326, 3.372, 3.425), stdev = 0.050
  CI (99.9%): [2.461, 4.282] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 5.132 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.736 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.621 ±(99.9%) 0.003 ms/op
Iteration   1: 3.708 ±(99.9%) 0.006 ms/op
Iteration   2: 3.549 ±(99.9%) 0.002 ms/op
Iteration   3: 3.562 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.606 ±(99.9%) 1.612 ms/op [Average]
  (min, avg, max) = (3.549, 3.606, 3.708), stdev = 0.088
  CI (99.9%): [1.995, 5.218] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 6.741 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.840 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.853 ±(99.9%) 0.013 ms/op
Iteration   1: 4.817 ±(99.9%) 0.009 ms/op
Iteration   2: 4.739 ±(99.9%) 0.012 ms/op
Iteration   3: 4.700 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.752 ±(99.9%) 1.083 ms/op [Average]
  (min, avg, max) = (4.700, 4.752, 4.817), stdev = 0.059
  CI (99.9%): [3.669, 5.835] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.990 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.719 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.573 ±(99.9%) 0.010 ms/op
Iteration   1: 3.601 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.108 ms/op
                 createUser·p0.50:   3.506 ms/op
                 createUser·p0.90:   4.440 ms/op
                 createUser·p0.95:   4.801 ms/op
                 createUser·p0.99:   5.828 ms/op
                 createUser·p0.999:  9.839 ms/op
                 createUser·p0.9999: 21.204 ms/op
                 createUser·p1.00:   21.561 ms/op

Iteration   2: 3.541 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.935 ms/op
                 createUser·p0.50:   3.437 ms/op
                 createUser·p0.90:   4.366 ms/op
                 createUser·p0.95:   4.702 ms/op
                 createUser·p0.99:   5.849 ms/op
                 createUser·p0.999:  9.313 ms/op
                 createUser·p0.9999: 20.281 ms/op
                 createUser·p1.00:   20.677 ms/op

Iteration   3: 3.684 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.813 ms/op
                 createUser·p0.50:   3.580 ms/op
                 createUser·p0.90:   4.579 ms/op
                 createUser·p0.95:   4.899 ms/op
                 createUser·p0.99:   5.874 ms/op
                 createUser·p0.999:  20.480 ms/op
                 createUser·p0.9999: 24.990 ms/op
                 createUser·p1.00:   25.330 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 266046
  mean =      3.608 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5096 
    [ 2.500,  5.000) = 251776 
    [ 5.000,  7.500) = 8387 
    [ 7.500, 10.000) = 520 
    [10.000, 12.500) = 68 
    [12.500, 15.000) = 7 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 34 
    [20.000, 22.500) = 86 
    [22.500, 25.000) = 40 
    [25.000, 27.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.813 ms/op
     p(50.0000) =      3.502 ms/op
     p(90.0000) =      4.473 ms/op
     p(95.0000) =      4.809 ms/op
     p(99.0000) =      5.849 ms/op
     p(99.9000) =     10.027 ms/op
     p(99.9900) =     23.160 ms/op
     p(99.9990) =     25.188 ms/op
     p(99.9999) =     25.330 ms/op
    p(100.0000) =     25.330 ms/op


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
# Warmup Iteration   1: 4.949 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.532 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.457 ±(99.9%) 0.008 ms/op
Iteration   1: 3.304 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.741 ms/op
                 existUser·p0.50:   3.228 ms/op
                 existUser·p0.90:   4.059 ms/op
                 existUser·p0.95:   4.399 ms/op
                 existUser·p0.99:   5.358 ms/op
                 existUser·p0.999:  9.101 ms/op
                 existUser·p0.9999: 15.165 ms/op
                 existUser·p1.00:   17.531 ms/op

Iteration   2: 3.431 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.932 ms/op
                 existUser·p0.50:   3.342 ms/op
                 existUser·p0.90:   4.211 ms/op
                 existUser·p0.95:   4.547 ms/op
                 existUser·p0.99:   5.390 ms/op
                 existUser·p0.999:  10.289 ms/op
                 existUser·p0.9999: 25.155 ms/op
                 existUser·p1.00:   25.264 ms/op

Iteration   3: 3.361 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.767 ms/op
                 existUser·p0.50:   3.281 ms/op
                 existUser·p0.90:   4.116 ms/op
                 existUser·p0.95:   4.432 ms/op
                 existUser·p0.99:   5.431 ms/op
                 existUser·p0.999:  10.699 ms/op
                 existUser·p0.9999: 19.791 ms/op
                 existUser·p1.00:   20.447 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 285321
  mean =      3.364 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12845 
    [ 2.500,  5.000) = 267303 
    [ 5.000,  7.500) = 4459 
    [ 7.500, 10.000) = 348 
    [10.000, 12.500) = 171 
    [12.500, 15.000) = 61 
    [15.000, 17.500) = 44 
    [17.500, 20.000) = 63 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 18 

  Percentiles, ms/op:
      p(0.0000) =      0.741 ms/op
     p(50.0000) =      3.281 ms/op
     p(90.0000) =      4.133 ms/op
     p(95.0000) =      4.465 ms/op
     p(99.0000) =      5.390 ms/op
     p(99.9000) =     10.366 ms/op
     p(99.9900) =     19.954 ms/op
     p(99.9990) =     25.264 ms/op
     p(99.9999) =     25.264 ms/op
    p(100.0000) =     25.264 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 5.399 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 3.689 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.656 ±(99.9%) 0.008 ms/op
Iteration   1: 3.674 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.949 ms/op
                 getUser·p0.50:   3.576 ms/op
                 getUser·p0.90:   4.538 ms/op
                 getUser·p0.95:   4.948 ms/op
                 getUser·p0.99:   6.210 ms/op
                 getUser·p0.999:  10.387 ms/op
                 getUser·p0.9999: 15.867 ms/op
                 getUser·p1.00:   16.515 ms/op

Iteration   2: 3.679 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.995 ms/op
                 getUser·p0.50:   3.592 ms/op
                 getUser·p0.90:   4.620 ms/op
                 getUser·p0.95:   4.964 ms/op
                 getUser·p0.99:   5.923 ms/op
                 getUser·p0.999:  7.914 ms/op
                 getUser·p0.9999: 19.595 ms/op
                 getUser·p1.00:   19.956 ms/op

Iteration   3: 3.567 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.946 ms/op
                 getUser·p0.50:   3.473 ms/op
                 getUser·p0.90:   4.350 ms/op
                 getUser·p0.95:   4.710 ms/op
                 getUser·p0.99:   5.984 ms/op
                 getUser·p0.999:  10.453 ms/op
                 getUser·p0.9999: 19.433 ms/op
                 getUser·p1.00:   20.316 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 263771
  mean =      3.639 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5552 
    [ 2.500,  5.000) = 247557 
    [ 5.000,  7.500) = 9826 
    [ 7.500, 10.000) = 605 
    [10.000, 12.500) = 71 
    [12.500, 15.000) = 13 
    [15.000, 17.500) = 90 
    [17.500, 20.000) = 51 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.946 ms/op
     p(50.0000) =      3.543 ms/op
     p(90.0000) =      4.514 ms/op
     p(95.0000) =      4.882 ms/op
     p(99.0000) =      6.038 ms/op
     p(99.9000) =      9.556 ms/op
     p(99.9900) =     19.038 ms/op
     p(99.9990) =     20.131 ms/op
     p(99.9999) =     20.316 ms/op
    p(100.0000) =     20.316 ms/op


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
# Warmup Iteration   1: 7.089 ±(99.9%) 0.076 ms/op
# Warmup Iteration   2: 4.909 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.863 ±(99.9%) 0.017 ms/op
Iteration   1: 4.608 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.372 ms/op
                 listUser·p0.50:   4.407 ms/op
                 listUser·p0.90:   5.865 ms/op
                 listUser·p0.95:   6.562 ms/op
                 listUser·p0.99:   8.217 ms/op
                 listUser·p0.999:  16.705 ms/op
                 listUser·p0.9999: 23.298 ms/op
                 listUser·p1.00:   23.691 ms/op

Iteration   2: 4.579 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.358 ms/op
                 listUser·p0.50:   4.350 ms/op
                 listUser·p0.90:   5.792 ms/op
                 listUser·p0.95:   6.758 ms/op
                 listUser·p0.99:   8.602 ms/op
                 listUser·p0.999:  20.546 ms/op
                 listUser·p0.9999: 26.706 ms/op
                 listUser·p1.00:   27.197 ms/op

Iteration   3: 4.716 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.610 ms/op
                 listUser·p0.50:   4.481 ms/op
                 listUser·p0.90:   6.144 ms/op
                 listUser·p0.95:   6.971 ms/op
                 listUser·p0.99:   8.716 ms/op
                 listUser·p0.999:  19.007 ms/op
                 listUser·p0.9999: 27.492 ms/op
                 listUser·p1.00:   27.623 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 207218
  mean =      4.634 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 660 
    [ 2.500,  5.000) = 156574 
    [ 5.000,  7.500) = 44809 
    [ 7.500, 10.000) = 4394 
    [10.000, 12.500) = 382 
    [12.500, 15.000) = 46 
    [15.000, 17.500) = 73 
    [17.500, 20.000) = 142 
    [20.000, 22.500) = 54 
    [22.500, 25.000) = 43 
    [25.000, 27.500) = 38 

  Percentiles, ms/op:
      p(0.0000) =      1.358 ms/op
     p(50.0000) =      4.415 ms/op
     p(90.0000) =      5.939 ms/op
     p(95.0000) =      6.767 ms/op
     p(99.0000) =      8.536 ms/op
     p(99.9000) =     19.071 ms/op
     p(99.9900) =     26.793 ms/op
     p(99.9990) =     27.586 ms/op
     p(99.9999) =     27.623 ms/op
    p(100.0000) =     27.623 ms/op


# Run complete. Total time: 00:13:06

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.790 ± 2.088  ops/ms
ClientGrpc.existUser                       thrpt       3   9.642 ± 3.962  ops/ms
ClientGrpc.getUser                         thrpt       3   8.962 ± 3.402  ops/ms
ClientGrpc.listUser                        thrpt       3   6.729 ± 3.297  ops/ms
ClientGrpc.createUser                       avgt       3   3.578 ± 2.012   ms/op
ClientGrpc.existUser                        avgt       3   3.372 ± 0.911   ms/op
ClientGrpc.getUser                          avgt       3   3.606 ± 1.612   ms/op
ClientGrpc.listUser                         avgt       3   4.752 ± 1.083   ms/op
ClientGrpc.createUser                     sample  266046   3.608 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.813           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.502           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.473           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.809           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.849           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.027           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          23.160           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          25.330           ms/op
ClientGrpc.existUser                      sample  285321   3.364 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.741           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.281           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.133           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.465           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.390           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.366           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.954           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          25.264           ms/op
ClientGrpc.getUser                        sample  263771   3.639 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.946           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.543           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.514           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.882           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.038           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.556           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.038           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.316           ms/op
ClientGrpc.listUser                       sample  207218   4.634 ± 0.009   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.358           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.415           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.939           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.767           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.536           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          19.071           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          26.793           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.623           ms/op
