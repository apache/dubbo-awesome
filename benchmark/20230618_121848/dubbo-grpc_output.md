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
# Warmup Iteration   1: 4.560 ops/ms
# Warmup Iteration   2: 9.340 ops/ms
# Warmup Iteration   3: 10.286 ops/ms
Iteration   1: 10.459 ops/ms
Iteration   2: 10.542 ops/ms
Iteration   3: 10.553 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.518 ±(99.9%) 0.938 ops/ms [Average]
  (min, avg, max) = (10.459, 10.518, 10.553), stdev = 0.051
  CI (99.9%): [9.580, 11.457] (assumes normal distribution)


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
# Warmup Iteration   1: 7.719 ops/ms
# Warmup Iteration   2: 10.748 ops/ms
# Warmup Iteration   3: 11.347 ops/ms
Iteration   1: 11.176 ops/ms
Iteration   2: 10.853 ops/ms
Iteration   3: 11.076 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.035 ±(99.9%) 3.019 ops/ms [Average]
  (min, avg, max) = (10.853, 11.035, 11.176), stdev = 0.165
  CI (99.9%): [8.016, 14.054] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.680 ops/ms
# Warmup Iteration   2: 10.440 ops/ms
# Warmup Iteration   3: 10.533 ops/ms
Iteration   1: 10.734 ops/ms
Iteration   2: 10.711 ops/ms
Iteration   3: 10.758 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.734 ±(99.9%) 0.424 ops/ms [Average]
  (min, avg, max) = (10.711, 10.734, 10.758), stdev = 0.023
  CI (99.9%): [10.310, 11.158] (assumes normal distribution)


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
# Warmup Iteration   1: 5.866 ops/ms
# Warmup Iteration   2: 8.204 ops/ms
# Warmup Iteration   3: 8.285 ops/ms
Iteration   1: 8.310 ops/ms
Iteration   2: 8.344 ops/ms
Iteration   3: 8.710 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.455 ±(99.9%) 4.044 ops/ms [Average]
  (min, avg, max) = (8.310, 8.455, 8.710), stdev = 0.222
  CI (99.9%): [4.410, 12.499] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 3.803 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.105 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 2.955 ±(99.9%) 0.007 ms/op
Iteration   1: 3.026 ±(99.9%) 0.002 ms/op
Iteration   2: 2.966 ±(99.9%) 0.003 ms/op
Iteration   3: 2.989 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.994 ±(99.9%) 0.554 ms/op [Average]
  (min, avg, max) = (2.966, 2.994, 3.026), stdev = 0.030
  CI (99.9%): [2.440, 3.547] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.722 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 2.959 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.901 ±(99.9%) 0.003 ms/op
Iteration   1: 2.916 ±(99.9%) 0.002 ms/op
Iteration   2: 2.915 ±(99.9%) 0.003 ms/op
Iteration   3: 2.830 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.887 ±(99.9%) 0.898 ms/op [Average]
  (min, avg, max) = (2.830, 2.887, 2.916), stdev = 0.049
  CI (99.9%): [1.988, 3.785] (assumes normal distribution)


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
# Warmup Iteration   1: 3.952 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.116 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.005 ±(99.9%) 0.004 ms/op
Iteration   1: 3.002 ±(99.9%) 0.002 ms/op
Iteration   2: 3.013 ±(99.9%) 0.003 ms/op
Iteration   3: 3.004 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.006 ±(99.9%) 0.111 ms/op [Average]
  (min, avg, max) = (3.002, 3.006, 3.013), stdev = 0.006
  CI (99.9%): [2.895, 3.118] (assumes normal distribution)


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
# Warmup Iteration   1: 4.711 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.976 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.892 ±(99.9%) 0.008 ms/op
Iteration   1: 3.799 ±(99.9%) 0.013 ms/op
Iteration   2: 3.861 ±(99.9%) 0.069 ms/op
Iteration   3: 3.796 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.819 ±(99.9%) 0.665 ms/op [Average]
  (min, avg, max) = (3.796, 3.819, 3.861), stdev = 0.036
  CI (99.9%): [3.154, 4.483] (assumes normal distribution)


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
# Warmup Iteration   1: 4.017 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.233 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.087 ±(99.9%) 0.007 ms/op
Iteration   1: 3.060 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.780 ms/op
                 createUser·p0.50:   3.052 ms/op
                 createUser·p0.90:   3.539 ms/op
                 createUser·p0.95:   3.801 ms/op
                 createUser·p0.99:   4.432 ms/op
                 createUser·p0.999:  7.655 ms/op
                 createUser·p0.9999: 16.058 ms/op
                 createUser·p1.00:   16.450 ms/op

Iteration   2: 3.097 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.876 ms/op
                 createUser·p0.50:   3.072 ms/op
                 createUser·p0.90:   3.645 ms/op
                 createUser·p0.95:   3.809 ms/op
                 createUser·p0.99:   4.514 ms/op
                 createUser·p0.999:  6.869 ms/op
                 createUser·p0.9999: 14.336 ms/op
                 createUser·p1.00:   14.352 ms/op

Iteration   3: 3.088 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.766 ms/op
                 createUser·p0.50:   3.072 ms/op
                 createUser·p0.90:   3.666 ms/op
                 createUser·p0.95:   3.887 ms/op
                 createUser·p0.99:   4.555 ms/op
                 createUser·p0.999:  10.393 ms/op
                 createUser·p0.9999: 18.371 ms/op
                 createUser·p1.00:   19.694 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 311278
  mean =      3.081 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 899 
    [ 1.250,  2.500) = 19677 
    [ 2.500,  3.750) = 270038 
    [ 3.750,  5.000) = 19386 
    [ 5.000,  6.250) = 674 
    [ 6.250,  7.500) = 246 
    [ 7.500,  8.750) = 56 
    [ 8.750, 10.000) = 37 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 59 
    [12.500, 13.750) = 58 
    [13.750, 15.000) = 34 
    [15.000, 16.250) = 46 
    [16.250, 17.500) = 20 
    [17.500, 18.750) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.766 ms/op
     p(50.0000) =      3.064 ms/op
     p(90.0000) =      3.625 ms/op
     p(95.0000) =      3.834 ms/op
     p(99.0000) =      4.506 ms/op
     p(99.9000) =      8.534 ms/op
     p(99.9900) =     16.398 ms/op
     p(99.9990) =     19.496 ms/op
     p(99.9999) =     19.694 ms/op
    p(100.0000) =     19.694 ms/op


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
# Warmup Iteration   1: 3.634 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 2.979 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.898 ±(99.9%) 0.005 ms/op
Iteration   1: 2.847 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.599 ms/op
                 existUser·p0.50:   2.859 ms/op
                 existUser·p0.90:   3.289 ms/op
                 existUser·p0.95:   3.486 ms/op
                 existUser·p0.99:   4.309 ms/op
                 existUser·p0.999:  6.019 ms/op
                 existUser·p0.9999: 12.160 ms/op
                 existUser·p1.00:   12.583 ms/op

Iteration   2: 2.857 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.492 ms/op
                 existUser·p0.50:   2.875 ms/op
                 existUser·p0.90:   3.305 ms/op
                 existUser·p0.95:   3.580 ms/op
                 existUser·p0.99:   4.174 ms/op
                 existUser·p0.999:  5.388 ms/op
                 existUser·p0.9999: 13.297 ms/op
                 existUser·p1.00:   13.451 ms/op

Iteration   3: 2.871 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.648 ms/op
                 existUser·p0.50:   2.867 ms/op
                 existUser·p0.90:   3.338 ms/op
                 existUser·p0.95:   3.600 ms/op
                 existUser·p0.99:   4.407 ms/op
                 existUser·p0.999:  7.193 ms/op
                 existUser·p0.9999: 26.051 ms/op
                 existUser·p1.00:   26.280 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 335883
  mean =      2.859 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 45446 
    [ 2.500,  5.000) = 289571 
    [ 5.000,  7.500) = 680 
    [ 7.500, 10.000) = 26 
    [10.000, 12.500) = 61 
    [12.500, 15.000) = 53 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.492 ms/op
     p(50.0000) =      2.867 ms/op
     p(90.0000) =      3.310 ms/op
     p(95.0000) =      3.559 ms/op
     p(99.0000) =      4.293 ms/op
     p(99.9000) =      6.021 ms/op
     p(99.9900) =     16.716 ms/op
     p(99.9990) =     26.191 ms/op
     p(99.9999) =     26.280 ms/op
    p(100.0000) =     26.280 ms/op


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
# Warmup Iteration   1: 3.988 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.112 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.995 ±(99.9%) 0.005 ms/op
Iteration   1: 2.988 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.624 ms/op
                 getUser·p0.50:   3.011 ms/op
                 getUser·p0.90:   3.523 ms/op
                 getUser·p0.95:   3.736 ms/op
                 getUser·p0.99:   4.432 ms/op
                 getUser·p0.999:  6.865 ms/op
                 getUser·p0.9999: 16.961 ms/op
                 getUser·p1.00:   17.334 ms/op

Iteration   2: 2.981 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.765 ms/op
                 getUser·p0.50:   2.990 ms/op
                 getUser·p0.90:   3.465 ms/op
                 getUser·p0.95:   3.662 ms/op
                 getUser·p0.99:   4.301 ms/op
                 getUser·p0.999:  6.842 ms/op
                 getUser·p0.9999: 12.887 ms/op
                 getUser·p1.00:   13.402 ms/op

Iteration   3: 3.026 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.754 ms/op
                 getUser·p0.50:   2.998 ms/op
                 getUser·p0.90:   3.600 ms/op
                 getUser·p0.95:   3.813 ms/op
                 getUser·p0.99:   4.514 ms/op
                 getUser·p0.999:  7.429 ms/op
                 getUser·p0.9999: 25.639 ms/op
                 getUser·p1.00:   25.985 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 320018
  mean =      2.998 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 28070 
    [ 2.500,  5.000) = 290724 
    [ 5.000,  7.500) = 942 
    [ 7.500, 10.000) = 84 
    [10.000, 12.500) = 82 
    [12.500, 15.000) = 52 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 27 

  Percentiles, ms/op:
      p(0.0000) =      0.624 ms/op
     p(50.0000) =      2.998 ms/op
     p(90.0000) =      3.531 ms/op
     p(95.0000) =      3.740 ms/op
     p(99.0000) =      4.415 ms/op
     p(99.9000) =      7.217 ms/op
     p(99.9900) =     24.857 ms/op
     p(99.9990) =     25.906 ms/op
     p(99.9999) =     25.985 ms/op
    p(100.0000) =     25.985 ms/op


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
# Warmup Iteration   1: 5.032 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.931 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.832 ±(99.9%) 0.009 ms/op
Iteration   1: 3.883 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.130 ms/op
                 listUser·p0.50:   3.752 ms/op
                 listUser·p0.90:   4.801 ms/op
                 listUser·p0.95:   5.546 ms/op
                 listUser·p0.99:   6.431 ms/op
                 listUser·p0.999:  12.571 ms/op
                 listUser·p0.9999: 18.736 ms/op
                 listUser·p1.00:   19.071 ms/op

Iteration   2: 3.724 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.321 ms/op
                 listUser·p0.50:   3.609 ms/op
                 listUser·p0.90:   4.858 ms/op
                 listUser·p0.95:   5.415 ms/op
                 listUser·p0.99:   6.799 ms/op
                 listUser·p0.999:  13.484 ms/op
                 listUser·p0.9999: 15.270 ms/op
                 listUser·p1.00:   16.548 ms/op

Iteration   3: 3.857 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.899 ms/op
                 listUser·p0.50:   3.719 ms/op
                 listUser·p0.90:   4.825 ms/op
                 listUser·p0.95:   5.571 ms/op
                 listUser·p0.99:   6.439 ms/op
                 listUser·p0.999:  15.202 ms/op
                 listUser·p0.9999: 21.453 ms/op
                 listUser·p1.00:   22.512 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 251424
  mean =      3.820 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7832 
    [ 2.500,  5.000) = 222811 
    [ 5.000,  7.500) = 19768 
    [ 7.500, 10.000) = 545 
    [10.000, 12.500) = 129 
    [12.500, 15.000) = 195 
    [15.000, 17.500) = 56 
    [17.500, 20.000) = 52 
    [20.000, 22.500) = 35 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.321 ms/op
     p(50.0000) =      3.699 ms/op
     p(90.0000) =      4.833 ms/op
     p(95.0000) =      5.505 ms/op
     p(99.0000) =      6.537 ms/op
     p(99.9000) =     13.435 ms/op
     p(99.9900) =     20.344 ms/op
     p(99.9990) =     21.625 ms/op
     p(99.9999) =     22.512 ms/op
    p(100.0000) =     22.512 ms/op


# Run complete. Total time: 00:13:02

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.518 ± 0.938  ops/ms
ClientGrpc.existUser                       thrpt       3  11.035 ± 3.019  ops/ms
ClientGrpc.getUser                         thrpt       3  10.734 ± 0.424  ops/ms
ClientGrpc.listUser                        thrpt       3   8.455 ± 4.044  ops/ms
ClientGrpc.createUser                       avgt       3   2.994 ± 0.554   ms/op
ClientGrpc.existUser                        avgt       3   2.887 ± 0.898   ms/op
ClientGrpc.getUser                          avgt       3   3.006 ± 0.111   ms/op
ClientGrpc.listUser                         avgt       3   3.819 ± 0.665   ms/op
ClientGrpc.createUser                     sample  311278   3.081 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.766           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.064           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.625           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.834           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.506           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.534           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          16.398           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          19.694           ms/op
ClientGrpc.existUser                      sample  335883   2.859 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.492           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.867           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.310           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.559           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.293           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.021           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.716           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          26.280           ms/op
ClientGrpc.getUser                        sample  320018   2.998 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.624           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.998           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.531           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.740           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.415           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.217           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          24.857           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          25.985           ms/op
ClientGrpc.listUser                       sample  251424   3.820 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.321           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.699           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.833           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.505           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.537           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.435           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          20.344           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          22.512           ms/op
