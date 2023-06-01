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
# Warmup Iteration   1: 4.814 ops/ms
# Warmup Iteration   2: 9.239 ops/ms
# Warmup Iteration   3: 10.398 ops/ms
Iteration   1: 10.568 ops/ms
Iteration   2: 10.850 ops/ms
Iteration   3: 10.720 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.713 ±(99.9%) 2.576 ops/ms [Average]
  (min, avg, max) = (10.568, 10.713, 10.850), stdev = 0.141
  CI (99.9%): [8.136, 13.289] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.905 ops/ms
# Warmup Iteration   2: 10.802 ops/ms
# Warmup Iteration   3: 11.184 ops/ms
Iteration   1: 11.135 ops/ms
Iteration   2: 11.594 ops/ms
Iteration   3: 11.336 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.355 ±(99.9%) 4.194 ops/ms [Average]
  (min, avg, max) = (11.135, 11.355, 11.594), stdev = 0.230
  CI (99.9%): [7.161, 15.549] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.030 ops/ms
# Warmup Iteration   2: 10.451 ops/ms
# Warmup Iteration   3: 10.681 ops/ms
Iteration   1: 10.848 ops/ms
Iteration   2: 10.689 ops/ms
Iteration   3: 10.865 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.801 ±(99.9%) 1.769 ops/ms [Average]
  (min, avg, max) = (10.689, 10.801, 10.865), stdev = 0.097
  CI (99.9%): [9.032, 12.570] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.375 ops/ms
# Warmup Iteration   2: 8.170 ops/ms
# Warmup Iteration   3: 8.477 ops/ms
Iteration   1: 8.300 ops/ms
Iteration   2: 8.666 ops/ms
Iteration   3: 8.412 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.459 ±(99.9%) 3.422 ops/ms [Average]
  (min, avg, max) = (8.300, 8.459, 8.666), stdev = 0.188
  CI (99.9%): [5.037, 11.881] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.140 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.115 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.038 ±(99.9%) 0.004 ms/op
Iteration   1: 2.995 ±(99.9%) 0.004 ms/op
Iteration   2: 2.990 ±(99.9%) 0.004 ms/op
Iteration   3: 2.919 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.968 ±(99.9%) 0.773 ms/op [Average]
  (min, avg, max) = (2.919, 2.968, 2.995), stdev = 0.042
  CI (99.9%): [2.195, 3.741] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.927 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 2.975 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.889 ±(99.9%) 0.004 ms/op
Iteration   1: 2.828 ±(99.9%) 0.002 ms/op
Iteration   2: 2.833 ±(99.9%) 0.004 ms/op
Iteration   3: 2.822 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.827 ±(99.9%) 0.100 ms/op [Average]
  (min, avg, max) = (2.822, 2.827, 2.833), stdev = 0.005
  CI (99.9%): [2.728, 2.927] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.989 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.061 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.996 ±(99.9%) 0.003 ms/op
Iteration   1: 2.981 ±(99.9%) 0.002 ms/op
Iteration   2: 2.978 ±(99.9%) 0.003 ms/op
Iteration   3: 2.931 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.964 ±(99.9%) 0.510 ms/op [Average]
  (min, avg, max) = (2.931, 2.964, 2.981), stdev = 0.028
  CI (99.9%): [2.454, 3.474] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.247 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 4.013 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.874 ±(99.9%) 0.016 ms/op
Iteration   1: 3.820 ±(99.9%) 0.024 ms/op
Iteration   2: 3.778 ±(99.9%) 0.007 ms/op
Iteration   3: 3.788 ±(99.9%) 0.036 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.795 ±(99.9%) 0.395 ms/op [Average]
  (min, avg, max) = (3.778, 3.795, 3.820), stdev = 0.022
  CI (99.9%): [3.400, 4.190] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.905 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.155 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.990 ±(99.9%) 0.006 ms/op
Iteration   1: 2.973 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.558 ms/op
                 createUser·p0.50:   2.949 ms/op
                 createUser·p0.90:   3.518 ms/op
                 createUser·p0.95:   3.785 ms/op
                 createUser·p0.99:   4.694 ms/op
                 createUser·p0.999:  8.039 ms/op
                 createUser·p0.9999: 19.120 ms/op
                 createUser·p1.00:   19.694 ms/op

Iteration   2: 2.970 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.211 ms/op
                 createUser·p0.50:   2.961 ms/op
                 createUser·p0.90:   3.449 ms/op
                 createUser·p0.95:   3.641 ms/op
                 createUser·p0.99:   4.497 ms/op
                 createUser·p0.999:  6.794 ms/op
                 createUser·p0.9999: 30.638 ms/op
                 createUser·p1.00:   30.835 ms/op

Iteration   3: 2.998 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.571 ms/op
                 createUser·p0.50:   2.961 ms/op
                 createUser·p0.90:   3.555 ms/op
                 createUser·p0.95:   3.764 ms/op
                 createUser·p0.99:   4.506 ms/op
                 createUser·p0.999:  9.814 ms/op
                 createUser·p0.9999: 31.643 ms/op
                 createUser·p1.00:   32.670 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 321855
  mean =      2.981 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 34924 
    [ 2.500,  5.000) = 285278 
    [ 5.000,  7.500) = 1312 
    [ 7.500, 10.000) = 104 
    [10.000, 12.500) = 13 
    [12.500, 15.000) = 59 
    [15.000, 17.500) = 64 
    [17.500, 20.000) = 37 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 63 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.211 ms/op
     p(50.0000) =      2.957 ms/op
     p(90.0000) =      3.506 ms/op
     p(95.0000) =      3.740 ms/op
     p(99.0000) =      4.571 ms/op
     p(99.9000) =      8.236 ms/op
     p(99.9900) =     31.128 ms/op
     p(99.9990) =     31.869 ms/op
     p(99.9999) =     32.670 ms/op
    p(100.0000) =     32.670 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.788 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 2.927 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.794 ±(99.9%) 0.007 ms/op
Iteration   1: 2.878 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.654 ms/op
                 existUser·p0.50:   2.879 ms/op
                 existUser·p0.90:   3.416 ms/op
                 existUser·p0.95:   3.645 ms/op
                 existUser·p0.99:   4.448 ms/op
                 existUser·p0.999:  7.055 ms/op
                 existUser·p0.9999: 11.516 ms/op
                 existUser·p1.00:   11.829 ms/op

Iteration   2: 2.905 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.374 ms/op
                 existUser·p0.50:   2.900 ms/op
                 existUser·p0.90:   3.432 ms/op
                 existUser·p0.95:   3.641 ms/op
                 existUser·p0.99:   4.481 ms/op
                 existUser·p0.999:  9.221 ms/op
                 existUser·p0.9999: 12.763 ms/op
                 existUser·p1.00:   13.025 ms/op

Iteration   3: 2.853 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.712 ms/op
                 existUser·p0.50:   2.867 ms/op
                 existUser·p0.90:   3.305 ms/op
                 existUser·p0.95:   3.502 ms/op
                 existUser·p0.99:   4.465 ms/op
                 existUser·p0.999:  8.567 ms/op
                 existUser·p0.9999: 14.411 ms/op
                 existUser·p1.00:   14.991 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 333485
  mean =      2.878 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 4306 
    [ 1.250,  2.500) = 40068 
    [ 2.500,  3.750) = 278489 
    [ 3.750,  5.000) = 9139 
    [ 5.000,  6.250) = 849 
    [ 6.250,  7.500) = 261 
    [ 7.500,  8.750) = 62 
    [ 8.750, 10.000) = 99 
    [10.000, 11.250) = 81 
    [11.250, 12.500) = 71 
    [12.500, 13.750) = 37 
    [13.750, 15.000) = 23 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.374 ms/op
     p(50.0000) =      2.884 ms/op
     p(90.0000) =      3.383 ms/op
     p(95.0000) =      3.604 ms/op
     p(99.0000) =      4.465 ms/op
     p(99.9000) =      8.386 ms/op
     p(99.9900) =     13.014 ms/op
     p(99.9990) =     14.855 ms/op
     p(99.9999) =     14.991 ms/op
    p(100.0000) =     14.991 ms/op


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
# Warmup Iteration   1: 3.902 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.077 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.025 ±(99.9%) 0.007 ms/op
Iteration   1: 2.988 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.777 ms/op
                 getUser·p0.50:   2.961 ms/op
                 getUser·p0.90:   3.432 ms/op
                 getUser·p0.95:   3.666 ms/op
                 getUser·p0.99:   4.637 ms/op
                 getUser·p0.999:  10.191 ms/op
                 getUser·p0.9999: 12.259 ms/op
                 getUser·p1.00:   13.287 ms/op

Iteration   2: 3.006 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.808 ms/op
                 getUser·p0.50:   2.978 ms/op
                 getUser·p0.90:   3.514 ms/op
                 getUser·p0.95:   3.662 ms/op
                 getUser·p0.99:   4.235 ms/op
                 getUser·p0.999:  6.160 ms/op
                 getUser·p0.9999: 18.853 ms/op
                 getUser·p1.00:   19.202 ms/op

Iteration   3: 2.964 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.707 ms/op
                 getUser·p0.50:   2.929 ms/op
                 getUser·p0.90:   3.576 ms/op
                 getUser·p0.95:   3.858 ms/op
                 getUser·p0.99:   4.612 ms/op
                 getUser·p0.999:  6.540 ms/op
                 getUser·p0.9999: 16.286 ms/op
                 getUser·p1.00:   17.990 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 321229
  mean =      2.986 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 901 
    [ 1.250,  2.500) = 27687 
    [ 2.500,  3.750) = 278379 
    [ 3.750,  5.000) = 12820 
    [ 5.000,  6.250) = 798 
    [ 6.250,  7.500) = 211 
    [ 7.500,  8.750) = 123 
    [ 8.750, 10.000) = 63 
    [10.000, 11.250) = 106 
    [11.250, 12.500) = 58 
    [12.500, 13.750) = 19 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 21 
    [16.250, 17.500) = 4 
    [17.500, 18.750) = 26 

  Percentiles, ms/op:
      p(0.0000) =      0.707 ms/op
     p(50.0000) =      2.957 ms/op
     p(90.0000) =      3.502 ms/op
     p(95.0000) =      3.715 ms/op
     p(99.0000) =      4.538 ms/op
     p(99.9000) =      8.356 ms/op
     p(99.9900) =     18.220 ms/op
     p(99.9990) =     19.104 ms/op
     p(99.9999) =     19.202 ms/op
    p(100.0000) =     19.202 ms/op


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
# Warmup Iteration   1: 4.030 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 4.120 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.890 ±(99.9%) 0.010 ms/op
Iteration   1: 3.822 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.260 ms/op
                 listUser·p0.50:   3.678 ms/op
                 listUser·p0.90:   4.784 ms/op
                 listUser·p0.95:   5.497 ms/op
                 listUser·p0.99:   6.685 ms/op
                 listUser·p0.999:  12.145 ms/op
                 listUser·p0.9999: 14.832 ms/op
                 listUser·p1.00:   16.761 ms/op

Iteration   2: 3.843 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.830 ms/op
                 listUser·p0.50:   3.707 ms/op
                 listUser·p0.90:   4.882 ms/op
                 listUser·p0.95:   5.579 ms/op
                 listUser·p0.99:   6.619 ms/op
                 listUser·p0.999:  14.692 ms/op
                 listUser·p0.9999: 22.840 ms/op
                 listUser·p1.00:   25.657 ms/op

Iteration   3: 3.826 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.782 ms/op
                 listUser·p0.50:   3.686 ms/op
                 listUser·p0.90:   4.727 ms/op
                 listUser·p0.95:   5.472 ms/op
                 listUser·p0.99:   6.660 ms/op
                 listUser·p0.999:  13.966 ms/op
                 listUser·p0.9999: 24.159 ms/op
                 listUser·p1.00:   24.740 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 250590
  mean =      3.830 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5732 
    [ 2.500,  5.000) = 224450 
    [ 5.000,  7.500) = 19327 
    [ 7.500, 10.000) = 599 
    [10.000, 12.500) = 116 
    [12.500, 15.000) = 250 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 51 
    [22.500, 25.000) = 34 
    [25.000, 27.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.782 ms/op
     p(50.0000) =      3.690 ms/op
     p(90.0000) =      4.801 ms/op
     p(95.0000) =      5.513 ms/op
     p(99.0000) =      6.652 ms/op
     p(99.9000) =     13.730 ms/op
     p(99.9900) =     22.872 ms/op
     p(99.9990) =     25.559 ms/op
     p(99.9999) =     25.657 ms/op
    p(100.0000) =     25.657 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.713 ± 2.576  ops/ms
ClientGrpc.existUser                       thrpt       3  11.355 ± 4.194  ops/ms
ClientGrpc.getUser                         thrpt       3  10.801 ± 1.769  ops/ms
ClientGrpc.listUser                        thrpt       3   8.459 ± 3.422  ops/ms
ClientGrpc.createUser                       avgt       3   2.968 ± 0.773   ms/op
ClientGrpc.existUser                        avgt       3   2.827 ± 0.100   ms/op
ClientGrpc.getUser                          avgt       3   2.964 ± 0.510   ms/op
ClientGrpc.listUser                         avgt       3   3.795 ± 0.395   ms/op
ClientGrpc.createUser                     sample  321855   2.981 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.211           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.957           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.506           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.740           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.571           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.236           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          31.128           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          32.670           ms/op
ClientGrpc.existUser                      sample  333485   2.878 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.374           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.884           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.383           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.604           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.465           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.386           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          13.014           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          14.991           ms/op
ClientGrpc.getUser                        sample  321229   2.986 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.707           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.957           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.502           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.715           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.538           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.356           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.220           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.202           ms/op
ClientGrpc.listUser                       sample  250590   3.830 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.782           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.690           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.801           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.513           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.652           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.730           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.872           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.657           ms/op
