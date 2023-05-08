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
# Warmup Iteration   1: 4.469 ops/ms
# Warmup Iteration   2: 9.455 ops/ms
# Warmup Iteration   3: 10.345 ops/ms
Iteration   1: 10.685 ops/ms
Iteration   2: 10.808 ops/ms
Iteration   3: 10.672 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.722 ±(99.9%) 1.364 ops/ms [Average]
  (min, avg, max) = (10.672, 10.722, 10.808), stdev = 0.075
  CI (99.9%): [9.358, 12.085] (assumes normal distribution)


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
# Warmup Iteration   1: 8.601 ops/ms
# Warmup Iteration   2: 10.860 ops/ms
# Warmup Iteration   3: 11.341 ops/ms
Iteration   1: 11.020 ops/ms
Iteration   2: 11.263 ops/ms
Iteration   3: 11.097 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.127 ±(99.9%) 2.273 ops/ms [Average]
  (min, avg, max) = (11.020, 11.127, 11.263), stdev = 0.125
  CI (99.9%): [8.854, 13.399] (assumes normal distribution)


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
# Warmup Iteration   1: 7.646 ops/ms
# Warmup Iteration   2: 10.034 ops/ms
# Warmup Iteration   3: 10.403 ops/ms
Iteration   1: 10.701 ops/ms
Iteration   2: 10.568 ops/ms
Iteration   3: 10.869 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.713 ±(99.9%) 2.745 ops/ms [Average]
  (min, avg, max) = (10.568, 10.713, 10.869), stdev = 0.150
  CI (99.9%): [7.968, 13.458] (assumes normal distribution)


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
# Warmup Iteration   1: 5.808 ops/ms
# Warmup Iteration   2: 7.931 ops/ms
# Warmup Iteration   3: 8.042 ops/ms
Iteration   1: 8.097 ops/ms
Iteration   2: 7.971 ops/ms
Iteration   3: 8.154 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.074 ±(99.9%) 1.714 ops/ms [Average]
  (min, avg, max) = (7.971, 8.074, 8.154), stdev = 0.094
  CI (99.9%): [6.360, 9.788] (assumes normal distribution)


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
# Warmup Iteration   1: 4.248 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.155 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.002 ±(99.9%) 0.004 ms/op
Iteration   1: 3.009 ±(99.9%) 0.003 ms/op
Iteration   2: 2.981 ±(99.9%) 0.003 ms/op
Iteration   3: 3.028 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.006 ±(99.9%) 0.423 ms/op [Average]
  (min, avg, max) = (2.981, 3.006, 3.028), stdev = 0.023
  CI (99.9%): [2.583, 3.429] (assumes normal distribution)


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
# Warmup Iteration   1: 3.741 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.995 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.953 ±(99.9%) 0.002 ms/op
Iteration   1: 2.824 ±(99.9%) 0.003 ms/op
Iteration   2: 2.914 ±(99.9%) 0.003 ms/op
Iteration   3: 2.867 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.868 ±(99.9%) 0.817 ms/op [Average]
  (min, avg, max) = (2.824, 2.868, 2.914), stdev = 0.045
  CI (99.9%): [2.051, 3.685] (assumes normal distribution)


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
# Warmup Iteration   1: 4.088 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.043 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.014 ±(99.9%) 0.005 ms/op
Iteration   1: 2.996 ±(99.9%) 0.002 ms/op
Iteration   2: 3.027 ±(99.9%) 0.002 ms/op
Iteration   3: 2.979 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.001 ±(99.9%) 0.447 ms/op [Average]
  (min, avg, max) = (2.979, 3.001, 3.027), stdev = 0.025
  CI (99.9%): [2.554, 3.448] (assumes normal distribution)


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
# Warmup Iteration   1: 4.931 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.949 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.017 ±(99.9%) 0.016 ms/op
Iteration   1: 3.947 ±(99.9%) 0.024 ms/op
Iteration   2: 3.971 ±(99.9%) 0.010 ms/op
Iteration   3: 3.928 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.949 ±(99.9%) 0.398 ms/op [Average]
  (min, avg, max) = (3.928, 3.949, 3.971), stdev = 0.022
  CI (99.9%): [3.550, 4.347] (assumes normal distribution)


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
# Warmup Iteration   1: 3.981 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.203 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.049 ±(99.9%) 0.007 ms/op
Iteration   1: 2.971 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.578 ms/op
                 createUser·p0.50:   2.970 ms/op
                 createUser·p0.90:   3.617 ms/op
                 createUser·p0.95:   3.924 ms/op
                 createUser·p0.99:   4.735 ms/op
                 createUser·p0.999:  7.092 ms/op
                 createUser·p0.9999: 11.747 ms/op
                 createUser·p1.00:   12.435 ms/op

Iteration   2: 2.987 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.712 ms/op
                 createUser·p0.50:   2.961 ms/op
                 createUser·p0.90:   3.547 ms/op
                 createUser·p0.95:   3.842 ms/op
                 createUser·p0.99:   4.743 ms/op
                 createUser·p0.999:  11.025 ms/op
                 createUser·p0.9999: 16.695 ms/op
                 createUser·p1.00:   17.760 ms/op

Iteration   3: 3.055 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.863 ms/op
                 createUser·p0.50:   3.015 ms/op
                 createUser·p0.90:   3.596 ms/op
                 createUser·p0.95:   3.834 ms/op
                 createUser·p0.99:   4.776 ms/op
                 createUser·p0.999:  9.339 ms/op
                 createUser·p0.9999: 15.122 ms/op
                 createUser·p1.00:   15.630 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 319385
  mean =      3.004 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2078 
    [ 1.250,  2.500) = 31137 
    [ 2.500,  3.750) = 264939 
    [ 3.750,  5.000) = 19004 
    [ 5.000,  6.250) = 1358 
    [ 6.250,  7.500) = 409 
    [ 7.500,  8.750) = 136 
    [ 8.750, 10.000) = 30 
    [10.000, 11.250) = 69 
    [11.250, 12.500) = 54 
    [12.500, 13.750) = 63 
    [13.750, 15.000) = 41 
    [15.000, 16.250) = 40 
    [16.250, 17.500) = 26 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.578 ms/op
     p(50.0000) =      2.982 ms/op
     p(90.0000) =      3.588 ms/op
     p(95.0000) =      3.867 ms/op
     p(99.0000) =      4.751 ms/op
     p(99.9000) =      8.864 ms/op
     p(99.9900) =     16.094 ms/op
     p(99.9990) =     17.184 ms/op
     p(99.9999) =     17.760 ms/op
    p(100.0000) =     17.760 ms/op


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
# Warmup Iteration   1: 3.435 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.002 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.831 ±(99.9%) 0.006 ms/op
Iteration   1: 2.886 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.528 ms/op
                 existUser·p0.50:   2.863 ms/op
                 existUser·p0.90:   3.367 ms/op
                 existUser·p0.95:   3.588 ms/op
                 existUser·p0.99:   4.440 ms/op
                 existUser·p0.999:  7.226 ms/op
                 existUser·p0.9999: 11.860 ms/op
                 existUser·p1.00:   12.091 ms/op

Iteration   2: 2.888 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.714 ms/op
                 existUser·p0.50:   2.867 ms/op
                 existUser·p0.90:   3.424 ms/op
                 existUser·p0.95:   3.703 ms/op
                 existUser·p0.99:   4.907 ms/op
                 existUser·p0.999:  10.945 ms/op
                 existUser·p0.9999: 25.196 ms/op
                 existUser·p1.00:   25.395 ms/op

Iteration   3: 2.854 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.672 ms/op
                 existUser·p0.50:   2.851 ms/op
                 existUser·p0.90:   3.326 ms/op
                 existUser·p0.95:   3.625 ms/op
                 existUser·p0.99:   4.555 ms/op
                 existUser·p0.999:  7.438 ms/op
                 existUser·p0.9999: 22.610 ms/op
                 existUser·p1.00:   22.970 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 333897
  mean =      2.876 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 46450 
    [ 2.500,  5.000) = 285343 
    [ 5.000,  7.500) = 1694 
    [ 7.500, 10.000) = 137 
    [10.000, 12.500) = 123 
    [12.500, 15.000) = 18 
    [15.000, 17.500) = 72 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 19 

  Percentiles, ms/op:
      p(0.0000) =      0.528 ms/op
     p(50.0000) =      2.859 ms/op
     p(90.0000) =      3.375 ms/op
     p(95.0000) =      3.641 ms/op
     p(99.0000) =      4.645 ms/op
     p(99.9000) =      8.285 ms/op
     p(99.9900) =     22.663 ms/op
     p(99.9990) =     25.286 ms/op
     p(99.9999) =     25.395 ms/op
    p(100.0000) =     25.395 ms/op


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
# Warmup Iteration   1: 4.082 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.130 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.054 ±(99.9%) 0.008 ms/op
Iteration   1: 2.991 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.785 ms/op
                 getUser·p0.50:   2.994 ms/op
                 getUser·p0.90:   3.637 ms/op
                 getUser·p0.95:   3.903 ms/op
                 getUser·p0.99:   4.768 ms/op
                 getUser·p0.999:  6.801 ms/op
                 getUser·p0.9999: 13.040 ms/op
                 getUser·p1.00:   13.418 ms/op

Iteration   2: 3.034 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.680 ms/op
                 getUser·p0.50:   3.015 ms/op
                 getUser·p0.90:   3.568 ms/op
                 getUser·p0.95:   3.805 ms/op
                 getUser·p0.99:   5.145 ms/op
                 getUser·p0.999:  9.035 ms/op
                 getUser·p0.9999: 18.183 ms/op
                 getUser·p1.00:   21.037 ms/op

Iteration   3: 3.001 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.583 ms/op
                 getUser·p0.50:   2.974 ms/op
                 getUser·p0.90:   3.518 ms/op
                 getUser·p0.95:   3.826 ms/op
                 getUser·p0.99:   5.030 ms/op
                 getUser·p0.999:  7.332 ms/op
                 getUser·p0.9999: 17.378 ms/op
                 getUser·p1.00:   19.005 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 319110
  mean =      3.009 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 31118 
    [ 2.500,  5.000) = 284936 
    [ 5.000,  7.500) = 2655 
    [ 7.500, 10.000) = 209 
    [10.000, 12.500) = 43 
    [12.500, 15.000) = 47 
    [15.000, 17.500) = 55 
    [17.500, 20.000) = 46 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.583 ms/op
     p(50.0000) =      2.994 ms/op
     p(90.0000) =      3.576 ms/op
     p(95.0000) =      3.854 ms/op
     p(99.0000) =      4.964 ms/op
     p(99.9000) =      7.903 ms/op
     p(99.9900) =     17.730 ms/op
     p(99.9990) =     18.495 ms/op
     p(99.9999) =     21.037 ms/op
    p(100.0000) =     21.037 ms/op


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
# Warmup Iteration   1: 4.800 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.947 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.872 ±(99.9%) 0.010 ms/op
Iteration   1: 3.895 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.118 ms/op
                 listUser·p0.50:   3.768 ms/op
                 listUser·p0.90:   4.817 ms/op
                 listUser·p0.95:   5.423 ms/op
                 listUser·p0.99:   6.627 ms/op
                 listUser·p0.999:  12.434 ms/op
                 listUser·p0.9999: 16.991 ms/op
                 listUser·p1.00:   17.334 ms/op

Iteration   2: 3.879 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.266 ms/op
                 listUser·p0.50:   3.744 ms/op
                 listUser·p0.90:   4.932 ms/op
                 listUser·p0.95:   5.628 ms/op
                 listUser·p0.99:   6.939 ms/op
                 listUser·p0.999:  13.615 ms/op
                 listUser·p0.9999: 15.626 ms/op
                 listUser·p1.00:   15.909 ms/op

Iteration   3: 3.914 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.821 ms/op
                 listUser·p0.50:   3.748 ms/op
                 listUser·p0.90:   5.087 ms/op
                 listUser·p0.95:   5.865 ms/op
                 listUser·p0.99:   6.888 ms/op
                 listUser·p0.999:  14.952 ms/op
                 listUser·p0.9999: 18.945 ms/op
                 listUser·p1.00:   19.857 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 246250
  mean =      3.896 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 13 
    [ 1.250,  2.500) = 6363 
    [ 2.500,  3.750) = 115835 
    [ 3.750,  5.000) = 101169 
    [ 5.000,  6.250) = 17546 
    [ 6.250,  7.500) = 3992 
    [ 7.500,  8.750) = 556 
    [ 8.750, 10.000) = 188 
    [10.000, 11.250) = 105 
    [11.250, 12.500) = 88 
    [12.500, 13.750) = 144 
    [13.750, 15.000) = 105 
    [15.000, 16.250) = 99 
    [16.250, 17.500) = 36 
    [17.500, 18.750) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.821 ms/op
     p(50.0000) =      3.752 ms/op
     p(90.0000) =      4.923 ms/op
     p(95.0000) =      5.652 ms/op
     p(99.0000) =      6.808 ms/op
     p(99.9000) =     13.779 ms/op
     p(99.9900) =     16.691 ms/op
     p(99.9990) =     19.746 ms/op
     p(99.9999) =     19.857 ms/op
    p(100.0000) =     19.857 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.722 ± 1.364  ops/ms
ClientGrpc.existUser                       thrpt       3  11.127 ± 2.273  ops/ms
ClientGrpc.getUser                         thrpt       3  10.713 ± 2.745  ops/ms
ClientGrpc.listUser                        thrpt       3   8.074 ± 1.714  ops/ms
ClientGrpc.createUser                       avgt       3   3.006 ± 0.423   ms/op
ClientGrpc.existUser                        avgt       3   2.868 ± 0.817   ms/op
ClientGrpc.getUser                          avgt       3   3.001 ± 0.447   ms/op
ClientGrpc.listUser                         avgt       3   3.949 ± 0.398   ms/op
ClientGrpc.createUser                     sample  319385   3.004 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.578           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.982           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.588           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.867           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.751           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.864           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          16.094           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          17.760           ms/op
ClientGrpc.existUser                      sample  333897   2.876 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.528           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.859           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.375           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.641           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.645           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.285           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          22.663           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          25.395           ms/op
ClientGrpc.getUser                        sample  319110   3.009 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.583           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.994           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.576           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.854           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.964           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.903           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.730           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.037           ms/op
ClientGrpc.listUser                       sample  246250   3.896 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.821           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.752           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.923           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.652           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.808           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.779           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          16.691           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          19.857           ms/op
