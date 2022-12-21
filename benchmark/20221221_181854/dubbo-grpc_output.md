# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.933 ops/ms
# Warmup Iteration   2: 9.671 ops/ms
# Warmup Iteration   3: 10.518 ops/ms
Iteration   1: 10.070 ops/ms
Iteration   2: 10.085 ops/ms
Iteration   3: 10.208 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.121 ±(99.9%) 1.381 ops/ms [Average]
  (min, avg, max) = (10.070, 10.121, 10.208), stdev = 0.076
  CI (99.9%): [8.740, 11.502] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 8.416 ops/ms
# Warmup Iteration   2: 10.706 ops/ms
# Warmup Iteration   3: 10.933 ops/ms
Iteration   1: 10.887 ops/ms
Iteration   2: 11.031 ops/ms
Iteration   3: 10.777 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.898 ±(99.9%) 2.318 ops/ms [Average]
  (min, avg, max) = (10.777, 10.898, 11.031), stdev = 0.127
  CI (99.9%): [8.580, 13.216] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:50
# Fork: 1 of 1
# Warmup Iteration   1: 8.393 ops/ms
# Warmup Iteration   2: 10.223 ops/ms
# Warmup Iteration   3: 10.347 ops/ms
Iteration   1: 10.345 ops/ms
Iteration   2: 10.763 ops/ms
Iteration   3: 10.391 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.500 ±(99.9%) 4.179 ops/ms [Average]
  (min, avg, max) = (10.345, 10.500, 10.763), stdev = 0.229
  CI (99.9%): [6.320, 14.679] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 5.510 ops/ms
# Warmup Iteration   2: 7.593 ops/ms
# Warmup Iteration   3: 7.808 ops/ms
Iteration   1: 8.074 ops/ms
Iteration   2: 7.867 ops/ms
Iteration   3: 8.142 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.028 ±(99.9%) 2.612 ops/ms [Average]
  (min, avg, max) = (7.867, 8.028, 8.142), stdev = 0.143
  CI (99.9%): [5.416, 10.639] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 4.005 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.126 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.048 ±(99.9%) 0.003 ms/op
Iteration   1: 3.056 ±(99.9%) 0.002 ms/op
Iteration   2: 3.151 ±(99.9%) 0.002 ms/op
Iteration   3: 3.052 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.086 ±(99.9%) 1.020 ms/op [Average]
  (min, avg, max) = (3.052, 3.086, 3.151), stdev = 0.056
  CI (99.9%): [2.067, 4.106] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.436 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 3.002 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.902 ±(99.9%) 0.003 ms/op
Iteration   1: 2.925 ±(99.9%) 0.003 ms/op
Iteration   2: 2.952 ±(99.9%) 0.002 ms/op
Iteration   3: 2.909 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.929 ±(99.9%) 0.396 ms/op [Average]
  (min, avg, max) = (2.909, 2.929, 2.952), stdev = 0.022
  CI (99.9%): [2.532, 3.325] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.958 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.093 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.025 ±(99.9%) 0.002 ms/op
Iteration   1: 3.110 ±(99.9%) 0.002 ms/op
Iteration   2: 3.117 ±(99.9%) 0.002 ms/op
Iteration   3: 2.987 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.071 ±(99.9%) 1.338 ms/op [Average]
  (min, avg, max) = (2.987, 3.071, 3.117), stdev = 0.073
  CI (99.9%): [1.733, 4.409] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.922 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 4.118 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 4.032 ±(99.9%) 0.033 ms/op
Iteration   1: 4.102 ±(99.9%) 0.012 ms/op
Iteration   2: 4.066 ±(99.9%) 0.008 ms/op
Iteration   3: 4.058 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.075 ±(99.9%) 0.431 ms/op [Average]
  (min, avg, max) = (4.058, 4.075, 4.102), stdev = 0.024
  CI (99.9%): [3.645, 4.506] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.036 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.145 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.172 ±(99.9%) 0.007 ms/op
Iteration   1: 3.075 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.335 ms/op
                 createUser·p0.50:   3.047 ms/op
                 createUser·p0.90:   3.727 ms/op
                 createUser·p0.95:   3.932 ms/op
                 createUser·p0.99:   4.309 ms/op
                 createUser·p0.999:  8.479 ms/op
                 createUser·p0.9999: 16.017 ms/op
                 createUser·p1.00:   17.007 ms/op

Iteration   2: 3.066 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.682 ms/op
                 createUser·p0.50:   3.060 ms/op
                 createUser·p0.90:   3.682 ms/op
                 createUser·p0.95:   3.863 ms/op
                 createUser·p0.99:   4.182 ms/op
                 createUser·p0.999:  7.484 ms/op
                 createUser·p0.9999: 15.428 ms/op
                 createUser·p1.00:   15.729 ms/op

Iteration   3: 3.128 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.769 ms/op
                 createUser·p0.50:   3.109 ms/op
                 createUser·p0.90:   3.813 ms/op
                 createUser·p0.95:   3.967 ms/op
                 createUser·p0.99:   4.241 ms/op
                 createUser·p0.999:  8.125 ms/op
                 createUser·p0.9999: 15.368 ms/op
                 createUser·p1.00:   15.729 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 310953
  mean =      3.089 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1566 
    [ 1.250,  2.500) = 25282 
    [ 2.500,  3.750) = 253535 
    [ 3.750,  5.000) = 29410 
    [ 5.000,  6.250) = 535 
    [ 6.250,  7.500) = 250 
    [ 7.500,  8.750) = 126 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 39 
    [11.250, 12.500) = 61 
    [12.500, 13.750) = 33 
    [13.750, 15.000) = 52 
    [15.000, 16.250) = 57 
    [16.250, 17.500) = 5 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.335 ms/op
     p(50.0000) =      3.068 ms/op
     p(90.0000) =      3.744 ms/op
     p(95.0000) =      3.924 ms/op
     p(99.0000) =      4.243 ms/op
     p(99.9000) =      7.956 ms/op
     p(99.9900) =     15.466 ms/op
     p(99.9990) =     16.464 ms/op
     p(99.9999) =     17.007 ms/op
    p(100.0000) =     17.007 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.754 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 2.962 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.951 ±(99.9%) 0.006 ms/op
Iteration   1: 2.928 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.668 ms/op
                 existUser·p0.50:   2.929 ms/op
                 existUser·p0.90:   3.547 ms/op
                 existUser·p0.95:   3.752 ms/op
                 existUser·p0.99:   4.375 ms/op
                 existUser·p0.999:  7.535 ms/op
                 existUser·p0.9999: 18.156 ms/op
                 existUser·p1.00:   18.547 ms/op

Iteration   2: 2.963 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.634 ms/op
                 existUser·p0.50:   2.945 ms/op
                 existUser·p0.90:   3.621 ms/op
                 existUser·p0.95:   3.793 ms/op
                 existUser·p0.99:   4.149 ms/op
                 existUser·p0.999:  6.203 ms/op
                 existUser·p0.9999: 22.125 ms/op
                 existUser·p1.00:   22.741 ms/op

Iteration   3: 2.992 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.598 ms/op
                 existUser·p0.50:   2.970 ms/op
                 existUser·p0.90:   3.650 ms/op
                 existUser·p0.95:   3.834 ms/op
                 existUser·p0.99:   4.150 ms/op
                 existUser·p0.999:  6.474 ms/op
                 existUser·p0.9999: 15.477 ms/op
                 existUser·p1.00:   15.942 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 323984
  mean =      2.961 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 46955 
    [ 2.500,  5.000) = 275993 
    [ 5.000,  7.500) = 783 
    [ 7.500, 10.000) = 29 
    [10.000, 12.500) = 96 
    [12.500, 15.000) = 10 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 42 
    [20.000, 22.500) = 48 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.598 ms/op
     p(50.0000) =      2.949 ms/op
     p(90.0000) =      3.604 ms/op
     p(95.0000) =      3.797 ms/op
     p(99.0000) =      4.211 ms/op
     p(99.9000) =      6.750 ms/op
     p(99.9900) =     21.332 ms/op
     p(99.9990) =     22.463 ms/op
     p(99.9999) =     22.741 ms/op
    p(100.0000) =     22.741 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.607 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.091 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.034 ±(99.9%) 0.006 ms/op
Iteration   1: 3.081 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.821 ms/op
                 getUser·p0.50:   3.060 ms/op
                 getUser·p0.90:   3.666 ms/op
                 getUser·p0.95:   3.882 ms/op
                 getUser·p0.99:   4.284 ms/op
                 getUser·p0.999:  6.750 ms/op
                 getUser·p0.9999: 13.379 ms/op
                 getUser·p1.00:   13.566 ms/op

Iteration   2: 3.091 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.260 ms/op
                 getUser·p0.50:   3.097 ms/op
                 getUser·p0.90:   3.736 ms/op
                 getUser·p0.95:   3.912 ms/op
                 getUser·p0.99:   4.301 ms/op
                 getUser·p0.999:  6.625 ms/op
                 getUser·p0.9999: 13.495 ms/op
                 getUser·p1.00:   13.763 ms/op

Iteration   3: 3.019 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.532 ms/op
                 getUser·p0.50:   3.047 ms/op
                 getUser·p0.90:   3.633 ms/op
                 getUser·p0.95:   3.875 ms/op
                 getUser·p0.99:   4.301 ms/op
                 getUser·p0.999:  7.793 ms/op
                 getUser·p0.9999: 15.604 ms/op
                 getUser·p1.00:   16.007 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 313298
  mean =      3.063 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2624 
    [ 1.250,  2.500) = 23352 
    [ 2.500,  3.750) = 261763 
    [ 3.750,  5.000) = 24547 
    [ 5.000,  6.250) = 510 
    [ 6.250,  7.500) = 249 
    [ 7.500,  8.750) = 88 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 14 
    [12.500, 13.750) = 108 
    [13.750, 15.000) = 24 
    [15.000, 16.250) = 19 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.260 ms/op
     p(50.0000) =      3.068 ms/op
     p(90.0000) =      3.686 ms/op
     p(95.0000) =      3.891 ms/op
     p(99.0000) =      4.301 ms/op
     p(99.9000) =      7.075 ms/op
     p(99.9900) =     13.861 ms/op
     p(99.9990) =     15.935 ms/op
     p(99.9999) =     16.007 ms/op
    p(100.0000) =     16.007 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.310 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 4.175 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.010 ±(99.9%) 0.011 ms/op
Iteration   1: 3.959 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.041 ms/op
                 listUser·p0.50:   3.801 ms/op
                 listUser·p0.90:   5.120 ms/op
                 listUser·p0.95:   5.595 ms/op
                 listUser·p0.99:   6.799 ms/op
                 listUser·p0.999:  12.648 ms/op
                 listUser·p0.9999: 18.711 ms/op
                 listUser·p1.00:   19.137 ms/op

Iteration   2: 4.050 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.808 ms/op
                 listUser·p0.50:   3.912 ms/op
                 listUser·p0.90:   5.046 ms/op
                 listUser·p0.95:   5.489 ms/op
                 listUser·p0.99:   6.619 ms/op
                 listUser·p0.999:  13.629 ms/op
                 listUser·p0.9999: 24.618 ms/op
                 listUser·p1.00:   25.657 ms/op

Iteration   3: 4.018 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.770 ms/op
                 listUser·p0.50:   3.858 ms/op
                 listUser·p0.90:   5.095 ms/op
                 listUser·p0.95:   5.579 ms/op
                 listUser·p0.99:   6.922 ms/op
                 listUser·p0.999:  15.015 ms/op
                 listUser·p0.9999: 17.830 ms/op
                 listUser·p1.00:   18.743 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 239416
  mean =      4.009 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3641 
    [ 2.500,  5.000) = 208454 
    [ 5.000,  7.500) = 26195 
    [ 7.500, 10.000) = 706 
    [10.000, 12.500) = 56 
    [12.500, 15.000) = 183 
    [15.000, 17.500) = 81 
    [17.500, 20.000) = 68 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.770 ms/op
     p(50.0000) =      3.858 ms/op
     p(90.0000) =      5.087 ms/op
     p(95.0000) =      5.554 ms/op
     p(99.0000) =      6.783 ms/op
     p(99.9000) =     13.631 ms/op
     p(99.9900) =     23.691 ms/op
     p(99.9990) =     25.553 ms/op
     p(99.9999) =     25.657 ms/op
    p(100.0000) =     25.657 ms/op


# Run complete. Total time: 00:13:02

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.121 ± 1.381  ops/ms
ClientGrpc.existUser                       thrpt       3  10.898 ± 2.318  ops/ms
ClientGrpc.getUser                         thrpt       3  10.500 ± 4.179  ops/ms
ClientGrpc.listUser                        thrpt       3   8.028 ± 2.612  ops/ms
ClientGrpc.createUser                       avgt       3   3.086 ± 1.020   ms/op
ClientGrpc.existUser                        avgt       3   2.929 ± 0.396   ms/op
ClientGrpc.getUser                          avgt       3   3.071 ± 1.338   ms/op
ClientGrpc.listUser                         avgt       3   4.075 ± 0.431   ms/op
ClientGrpc.createUser                     sample  310953   3.089 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.335           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.068           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.744           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.924           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.243           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.956           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          15.466           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          17.007           ms/op
ClientGrpc.existUser                      sample  323984   2.961 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.598           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.949           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.604           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.797           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.211           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.750           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          21.332           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.741           ms/op
ClientGrpc.getUser                        sample  313298   3.063 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.260           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.068           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.686           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.891           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.301           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.075           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          13.861           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          16.007           ms/op
ClientGrpc.listUser                       sample  239416   4.009 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.770           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.858           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.087           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.554           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.783           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.631           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.691           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.657           ms/op
