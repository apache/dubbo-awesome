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
# Warmup Iteration   1: 4.974 ops/ms
# Warmup Iteration   2: 10.096 ops/ms
# Warmup Iteration   3: 10.671 ops/ms
Iteration   1: 11.120 ops/ms
Iteration   2: 11.783 ops/ms
Iteration   3: 10.854 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  11.253 ±(99.9%) 8.730 ops/ms [Average]
  (min, avg, max) = (10.854, 11.253, 11.783), stdev = 0.479
  CI (99.9%): [2.523, 19.983] (assumes normal distribution)


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
# Warmup Iteration   1: 8.317 ops/ms
# Warmup Iteration   2: 10.975 ops/ms
# Warmup Iteration   3: 10.932 ops/ms
Iteration   1: 10.726 ops/ms
Iteration   2: 10.850 ops/ms
Iteration   3: 11.492 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.023 ±(99.9%) 7.497 ops/ms [Average]
  (min, avg, max) = (10.726, 11.023, 11.492), stdev = 0.411
  CI (99.9%): [3.526, 18.520] (assumes normal distribution)


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
# Warmup Iteration   1: 6.958 ops/ms
# Warmup Iteration   2: 9.975 ops/ms
# Warmup Iteration   3: 10.909 ops/ms
Iteration   1: 11.288 ops/ms
Iteration   2: 10.632 ops/ms
Iteration   3: 11.045 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.988 ±(99.9%) 6.051 ops/ms [Average]
  (min, avg, max) = (10.632, 10.988, 11.288), stdev = 0.332
  CI (99.9%): [4.937, 17.039] (assumes normal distribution)


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
# Warmup Iteration   1: 5.694 ops/ms
# Warmup Iteration   2: 8.221 ops/ms
# Warmup Iteration   3: 8.011 ops/ms
Iteration   1: 8.272 ops/ms
Iteration   2: 8.153 ops/ms
Iteration   3: 8.186 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.204 ±(99.9%) 1.124 ops/ms [Average]
  (min, avg, max) = (8.153, 8.204, 8.272), stdev = 0.062
  CI (99.9%): [7.079, 9.328] (assumes normal distribution)


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
# Warmup Iteration   1: 4.219 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.080 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.937 ±(99.9%) 0.008 ms/op
Iteration   1: 3.047 ±(99.9%) 0.002 ms/op
Iteration   2: 2.928 ±(99.9%) 0.002 ms/op
Iteration   3: 2.883 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.952 ±(99.9%) 1.543 ms/op [Average]
  (min, avg, max) = (2.883, 2.952, 3.047), stdev = 0.085
  CI (99.9%): [1.410, 4.495] (assumes normal distribution)


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
# Warmup Iteration   1: 3.596 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 3.024 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.743 ±(99.9%) 0.002 ms/op
Iteration   1: 2.797 ±(99.9%) 0.003 ms/op
Iteration   2: 2.957 ±(99.9%) 0.003 ms/op
Iteration   3: 2.913 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.889 ±(99.9%) 1.511 ms/op [Average]
  (min, avg, max) = (2.797, 2.889, 2.957), stdev = 0.083
  CI (99.9%): [1.378, 4.400] (assumes normal distribution)


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
# Warmup Iteration   1: 4.232 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.931 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.843 ±(99.9%) 0.003 ms/op
Iteration   1: 3.093 ±(99.9%) 0.002 ms/op
Iteration   2: 2.948 ±(99.9%) 0.003 ms/op
Iteration   3: 2.936 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.992 ±(99.9%) 1.586 ms/op [Average]
  (min, avg, max) = (2.936, 2.992, 3.093), stdev = 0.087
  CI (99.9%): [1.407, 4.578] (assumes normal distribution)


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
# Warmup Iteration   1: 5.176 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.810 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.881 ±(99.9%) 0.020 ms/op
Iteration   1: 3.667 ±(99.9%) 0.021 ms/op
Iteration   2: 3.871 ±(99.9%) 0.010 ms/op
Iteration   3: 3.689 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.742 ±(99.9%) 2.047 ms/op [Average]
  (min, avg, max) = (3.667, 3.742, 3.871), stdev = 0.112
  CI (99.9%): [1.696, 5.789] (assumes normal distribution)


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
# Warmup Iteration   1: 3.910 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 2.996 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.945 ±(99.9%) 0.006 ms/op
Iteration   1: 2.990 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.822 ms/op
                 createUser·p0.50:   2.982 ms/op
                 createUser·p0.90:   3.658 ms/op
                 createUser·p0.95:   3.813 ms/op
                 createUser·p0.99:   4.084 ms/op
                 createUser·p0.999:  7.349 ms/op
                 createUser·p0.9999: 13.658 ms/op
                 createUser·p1.00:   14.008 ms/op

Iteration   2: 2.856 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.551 ms/op
                 createUser·p0.50:   2.822 ms/op
                 createUser·p0.90:   3.408 ms/op
                 createUser·p0.95:   3.588 ms/op
                 createUser·p0.99:   3.977 ms/op
                 createUser·p0.999:  6.953 ms/op
                 createUser·p0.9999: 21.234 ms/op
                 createUser·p1.00:   21.561 ms/op

Iteration   3: 3.012 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.667 ms/op
                 createUser·p0.50:   2.998 ms/op
                 createUser·p0.90:   3.514 ms/op
                 createUser·p0.95:   3.768 ms/op
                 createUser·p0.99:   4.555 ms/op
                 createUser·p0.999:  9.434 ms/op
                 createUser·p0.9999: 16.802 ms/op
                 createUser·p1.00:   18.022 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 325249
  mean =      2.951 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 51987 
    [ 2.500,  5.000) = 272094 
    [ 5.000,  7.500) = 827 
    [ 7.500, 10.000) = 83 
    [10.000, 12.500) = 65 
    [12.500, 15.000) = 101 
    [15.000, 17.500) = 56 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.551 ms/op
     p(50.0000) =      2.933 ms/op
     p(90.0000) =      3.543 ms/op
     p(95.0000) =      3.740 ms/op
     p(99.0000) =      4.211 ms/op
     p(99.9000) =      7.676 ms/op
     p(99.9900) =     19.345 ms/op
     p(99.9990) =     21.479 ms/op
     p(99.9999) =     21.561 ms/op
    p(100.0000) =     21.561 ms/op


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
# Warmup Iteration   1: 3.737 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.078 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.751 ±(99.9%) 0.007 ms/op
Iteration   1: 2.952 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.805 ms/op
                 existUser·p0.50:   2.933 ms/op
                 existUser·p0.90:   3.551 ms/op
                 existUser·p0.95:   3.707 ms/op
                 existUser·p0.99:   4.039 ms/op
                 existUser·p0.999:  6.559 ms/op
                 existUser·p0.9999: 14.705 ms/op
                 existUser·p1.00:   16.499 ms/op

Iteration   2: 2.854 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.633 ms/op
                 existUser·p0.50:   2.830 ms/op
                 existUser·p0.90:   3.490 ms/op
                 existUser·p0.95:   3.670 ms/op
                 existUser·p0.99:   3.961 ms/op
                 existUser·p0.999:  6.884 ms/op
                 existUser·p0.9999: 18.303 ms/op
                 existUser·p1.00:   19.661 ms/op

Iteration   3: 2.796 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.696 ms/op
                 existUser·p0.50:   2.793 ms/op
                 existUser·p0.90:   3.383 ms/op
                 existUser·p0.95:   3.539 ms/op
                 existUser·p0.99:   3.838 ms/op
                 existUser·p0.999:  9.481 ms/op
                 existUser·p0.9999: 21.580 ms/op
                 existUser·p1.00:   22.217 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 334907
  mean =      2.866 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 74391 
    [ 2.500,  5.000) = 259608 
    [ 5.000,  7.500) = 550 
    [ 7.500, 10.000) = 163 
    [10.000, 12.500) = 35 
    [12.500, 15.000) = 24 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 54 
    [20.000, 22.500) = 48 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.633 ms/op
     p(50.0000) =      2.855 ms/op
     p(90.0000) =      3.478 ms/op
     p(95.0000) =      3.645 ms/op
     p(99.0000) =      3.957 ms/op
     p(99.9000) =      7.890 ms/op
     p(99.9900) =     20.398 ms/op
     p(99.9990) =     21.887 ms/op
     p(99.9999) =     22.217 ms/op
    p(100.0000) =     22.217 ms/op


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
# Warmup Iteration   1: 4.011 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 2.959 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.904 ±(99.9%) 0.009 ms/op
Iteration   1: 2.825 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.843 ms/op
                 getUser·p0.50:   2.793 ms/op
                 getUser·p0.90:   3.346 ms/op
                 getUser·p0.95:   3.531 ms/op
                 getUser·p0.99:   3.891 ms/op
                 getUser·p0.999:  6.403 ms/op
                 getUser·p0.9999: 14.232 ms/op
                 getUser·p1.00:   14.582 ms/op

Iteration   2: 3.037 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.736 ms/op
                 getUser·p0.50:   3.006 ms/op
                 getUser·p0.90:   3.645 ms/op
                 getUser·p0.95:   3.834 ms/op
                 getUser·p0.99:   4.637 ms/op
                 getUser·p0.999:  8.222 ms/op
                 getUser·p0.9999: 18.428 ms/op
                 getUser·p1.00:   18.973 ms/op

Iteration   3: 3.065 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.624 ms/op
                 getUser·p0.50:   2.978 ms/op
                 getUser·p0.90:   3.838 ms/op
                 getUser·p0.95:   4.018 ms/op
                 getUser·p0.99:   4.350 ms/op
                 getUser·p0.999:  7.315 ms/op
                 getUser·p0.9999: 16.959 ms/op
                 getUser·p1.00:   17.334 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 323153
  mean =      2.972 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 476 
    [ 1.250,  2.500) = 53217 
    [ 2.500,  3.750) = 246912 
    [ 3.750,  5.000) = 21203 
    [ 5.000,  6.250) = 610 
    [ 6.250,  7.500) = 409 
    [ 7.500,  8.750) = 119 
    [ 8.750, 10.000) = 15 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 5 
    [13.750, 15.000) = 28 
    [15.000, 16.250) = 28 
    [16.250, 17.500) = 71 
    [17.500, 18.750) = 25 

  Percentiles, ms/op:
      p(0.0000) =      0.624 ms/op
     p(50.0000) =      2.908 ms/op
     p(90.0000) =      3.629 ms/op
     p(95.0000) =      3.854 ms/op
     p(99.0000) =      4.317 ms/op
     p(99.9000) =      7.544 ms/op
     p(99.9900) =     17.334 ms/op
     p(99.9990) =     18.794 ms/op
     p(99.9999) =     18.973 ms/op
    p(100.0000) =     18.973 ms/op


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
# Warmup Iteration   1: 4.940 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.806 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.818 ±(99.9%) 0.011 ms/op
Iteration   1: 3.727 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.343 ms/op
                 listUser·p0.50:   3.564 ms/op
                 listUser·p0.90:   4.694 ms/op
                 listUser·p0.95:   5.390 ms/op
                 listUser·p0.99:   6.603 ms/op
                 listUser·p0.999:  13.290 ms/op
                 listUser·p0.9999: 15.197 ms/op
                 listUser·p1.00:   18.776 ms/op

Iteration   2: 3.690 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.077 ms/op
                 listUser·p0.50:   3.518 ms/op
                 listUser·p0.90:   4.710 ms/op
                 listUser·p0.95:   5.366 ms/op
                 listUser·p0.99:   6.507 ms/op
                 listUser·p0.999:  16.013 ms/op
                 listUser·p0.9999: 21.987 ms/op
                 listUser·p1.00:   22.577 ms/op

Iteration   3: 3.836 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.081 ms/op
                 listUser·p0.50:   3.641 ms/op
                 listUser·p0.90:   4.907 ms/op
                 listUser·p0.95:   5.448 ms/op
                 listUser·p0.99:   6.701 ms/op
                 listUser·p0.999:  15.204 ms/op
                 listUser·p0.9999: 21.233 ms/op
                 listUser·p1.00:   21.856 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 255957
  mean =      3.750 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4300 
    [ 2.500,  5.000) = 231555 
    [ 5.000,  7.500) = 19110 
    [ 7.500, 10.000) = 521 
    [10.000, 12.500) = 88 
    [12.500, 15.000) = 152 
    [15.000, 17.500) = 118 
    [17.500, 20.000) = 44 
    [20.000, 22.500) = 68 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.077 ms/op
     p(50.0000) =      3.576 ms/op
     p(90.0000) =      4.784 ms/op
     p(95.0000) =      5.407 ms/op
     p(99.0000) =      6.603 ms/op
     p(99.9000) =     14.615 ms/op
     p(99.9900) =     21.050 ms/op
     p(99.9990) =     22.424 ms/op
     p(99.9999) =     22.577 ms/op
    p(100.0000) =     22.577 ms/op


# Run complete. Total time: 00:13:02

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  11.253 ± 8.730  ops/ms
ClientGrpc.existUser                       thrpt       3  11.023 ± 7.497  ops/ms
ClientGrpc.getUser                         thrpt       3  10.988 ± 6.051  ops/ms
ClientGrpc.listUser                        thrpt       3   8.204 ± 1.124  ops/ms
ClientGrpc.createUser                       avgt       3   2.952 ± 1.543   ms/op
ClientGrpc.existUser                        avgt       3   2.889 ± 1.511   ms/op
ClientGrpc.getUser                          avgt       3   2.992 ± 1.586   ms/op
ClientGrpc.listUser                         avgt       3   3.742 ± 2.047   ms/op
ClientGrpc.createUser                     sample  325249   2.951 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.551           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.933           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.543           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.740           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.211           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.676           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.345           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.561           ms/op
ClientGrpc.existUser                      sample  334907   2.866 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.633           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.855           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.478           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.645           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           3.957           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.890           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.398           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.217           ms/op
ClientGrpc.getUser                        sample  323153   2.972 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.624           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.908           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.629           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.854           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.317           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.544           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.334           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.973           ms/op
ClientGrpc.listUser                       sample  255957   3.750 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.077           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.576           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.784           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.407           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.603           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.615           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.050           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          22.577           ms/op
