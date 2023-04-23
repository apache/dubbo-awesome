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
# Warmup Iteration   1: 4.801 ops/ms
# Warmup Iteration   2: 9.326 ops/ms
# Warmup Iteration   3: 10.599 ops/ms
Iteration   1: 10.803 ops/ms
Iteration   2: 10.661 ops/ms
Iteration   3: 10.964 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.809 ±(99.9%) 2.759 ops/ms [Average]
  (min, avg, max) = (10.661, 10.809, 10.964), stdev = 0.151
  CI (99.9%): [8.051, 13.568] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.727 ops/ms
# Warmup Iteration   2: 10.884 ops/ms
# Warmup Iteration   3: 11.504 ops/ms
Iteration   1: 11.406 ops/ms
Iteration   2: 11.106 ops/ms
Iteration   3: 11.181 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.231 ±(99.9%) 2.851 ops/ms [Average]
  (min, avg, max) = (11.106, 11.231, 11.406), stdev = 0.156
  CI (99.9%): [8.380, 14.083] (assumes normal distribution)


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
# Warmup Iteration   1: 8.134 ops/ms
# Warmup Iteration   2: 10.723 ops/ms
# Warmup Iteration   3: 10.857 ops/ms
Iteration   1: 10.971 ops/ms
Iteration   2: 11.005 ops/ms
Iteration   3: 10.945 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.974 ±(99.9%) 0.541 ops/ms [Average]
  (min, avg, max) = (10.945, 10.974, 11.005), stdev = 0.030
  CI (99.9%): [10.433, 11.515] (assumes normal distribution)


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
# Warmup Iteration   1: 6.210 ops/ms
# Warmup Iteration   2: 8.007 ops/ms
# Warmup Iteration   3: 8.284 ops/ms
Iteration   1: 8.253 ops/ms
Iteration   2: 8.277 ops/ms
Iteration   3: 8.372 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.301 ±(99.9%) 1.143 ops/ms [Average]
  (min, avg, max) = (8.253, 8.301, 8.372), stdev = 0.063
  CI (99.9%): [7.157, 9.444] (assumes normal distribution)


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
# Warmup Iteration   1: 3.894 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.053 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.948 ±(99.9%) 0.003 ms/op
Iteration   1: 2.967 ±(99.9%) 0.008 ms/op
Iteration   2: 2.913 ±(99.9%) 0.002 ms/op
Iteration   3: 2.940 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.940 ±(99.9%) 0.491 ms/op [Average]
  (min, avg, max) = (2.913, 2.940, 2.967), stdev = 0.027
  CI (99.9%): [2.449, 3.431] (assumes normal distribution)


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
# Warmup Iteration   1: 3.730 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.971 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.840 ±(99.9%) 0.003 ms/op
Iteration   1: 2.810 ±(99.9%) 0.003 ms/op
Iteration   2: 2.822 ±(99.9%) 0.003 ms/op
Iteration   3: 2.816 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.816 ±(99.9%) 0.108 ms/op [Average]
  (min, avg, max) = (2.810, 2.816, 2.822), stdev = 0.006
  CI (99.9%): [2.708, 2.924] (assumes normal distribution)


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
# Warmup Iteration   1: 3.705 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.001 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.939 ±(99.9%) 0.002 ms/op
Iteration   1: 2.943 ±(99.9%) 0.003 ms/op
Iteration   2: 2.996 ±(99.9%) 0.001 ms/op
Iteration   3: 2.992 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.977 ±(99.9%) 0.538 ms/op [Average]
  (min, avg, max) = (2.943, 2.977, 2.996), stdev = 0.029
  CI (99.9%): [2.439, 3.515] (assumes normal distribution)


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
# Warmup Iteration   1: 5.076 ±(99.9%) 0.067 ms/op
# Warmup Iteration   2: 3.863 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.797 ±(99.9%) 0.020 ms/op
Iteration   1: 3.766 ±(99.9%) 0.047 ms/op
Iteration   2: 3.780 ±(99.9%) 0.039 ms/op
Iteration   3: 3.784 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.776 ±(99.9%) 0.176 ms/op [Average]
  (min, avg, max) = (3.766, 3.776, 3.784), stdev = 0.010
  CI (99.9%): [3.601, 3.952] (assumes normal distribution)


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
# Warmup Iteration   1: 3.952 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.082 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.017 ±(99.9%) 0.007 ms/op
Iteration   1: 2.985 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.591 ms/op
                 createUser·p0.50:   2.957 ms/op
                 createUser·p0.90:   3.531 ms/op
                 createUser·p0.95:   3.727 ms/op
                 createUser·p0.99:   4.194 ms/op
                 createUser·p0.999:  7.867 ms/op
                 createUser·p0.9999: 15.148 ms/op
                 createUser·p1.00:   15.385 ms/op

Iteration   2: 2.986 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.561 ms/op
                 createUser·p0.50:   2.961 ms/op
                 createUser·p0.90:   3.453 ms/op
                 createUser·p0.95:   3.613 ms/op
                 createUser·p0.99:   4.057 ms/op
                 createUser·p0.999:  10.510 ms/op
                 createUser·p0.9999: 13.058 ms/op
                 createUser·p1.00:   13.287 ms/op

Iteration   3: 2.934 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.687 ms/op
                 createUser·p0.50:   2.929 ms/op
                 createUser·p0.90:   3.416 ms/op
                 createUser·p0.95:   3.633 ms/op
                 createUser·p0.99:   4.424 ms/op
                 createUser·p0.999:  8.984 ms/op
                 createUser·p0.9999: 18.454 ms/op
                 createUser·p1.00:   18.776 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 323593
  mean =      2.968 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1119 
    [ 1.250,  2.500) = 28624 
    [ 2.500,  3.750) = 281925 
    [ 3.750,  5.000) = 10780 
    [ 5.000,  6.250) = 467 
    [ 6.250,  7.500) = 246 
    [ 7.500,  8.750) = 104 
    [ 8.750, 10.000) = 37 
    [10.000, 11.250) = 91 
    [11.250, 12.500) = 47 
    [12.500, 13.750) = 47 
    [13.750, 15.000) = 64 
    [15.000, 16.250) = 19 
    [16.250, 17.500) = 10 
    [17.500, 18.750) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.561 ms/op
     p(50.0000) =      2.949 ms/op
     p(90.0000) =      3.465 ms/op
     p(95.0000) =      3.658 ms/op
     p(99.0000) =      4.243 ms/op
     p(99.9000) =      8.844 ms/op
     p(99.9900) =     15.225 ms/op
     p(99.9990) =     18.695 ms/op
     p(99.9999) =     18.776 ms/op
    p(100.0000) =     18.776 ms/op


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
# Warmup Iteration   1: 3.707 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 2.934 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.827 ±(99.9%) 0.006 ms/op
Iteration   1: 2.757 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.812 ms/op
                 existUser·p0.50:   2.781 ms/op
                 existUser·p0.90:   3.162 ms/op
                 existUser·p0.95:   3.371 ms/op
                 existUser·p0.99:   4.260 ms/op
                 existUser·p0.999:  7.389 ms/op
                 existUser·p0.9999: 17.531 ms/op
                 existUser·p1.00:   17.793 ms/op

Iteration   2: 2.838 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.521 ms/op
                 existUser·p0.50:   2.847 ms/op
                 existUser·p0.90:   3.224 ms/op
                 existUser·p0.95:   3.437 ms/op
                 existUser·p0.99:   4.138 ms/op
                 existUser·p0.999:  6.367 ms/op
                 existUser·p0.9999: 14.061 ms/op
                 existUser·p1.00:   14.500 ms/op

Iteration   3: 2.821 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.501 ms/op
                 existUser·p0.50:   2.830 ms/op
                 existUser·p0.90:   3.191 ms/op
                 existUser·p0.95:   3.404 ms/op
                 existUser·p0.99:   4.366 ms/op
                 existUser·p0.999:  7.984 ms/op
                 existUser·p0.9999: 16.455 ms/op
                 existUser·p1.00:   17.236 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 342032
  mean =      2.805 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 4101 
    [ 1.250,  2.500) = 48893 
    [ 2.500,  3.750) = 280896 
    [ 3.750,  5.000) = 7121 
    [ 5.000,  6.250) = 574 
    [ 6.250,  7.500) = 145 
    [ 7.500,  8.750) = 46 
    [ 8.750, 10.000) = 28 
    [10.000, 11.250) = 56 
    [11.250, 12.500) = 12 
    [12.500, 13.750) = 13 
    [13.750, 15.000) = 28 
    [15.000, 16.250) = 67 
    [16.250, 17.500) = 40 
    [17.500, 18.750) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.501 ms/op
     p(50.0000) =      2.818 ms/op
     p(90.0000) =      3.191 ms/op
     p(95.0000) =      3.408 ms/op
     p(99.0000) =      4.268 ms/op
     p(99.9000) =      7.094 ms/op
     p(99.9900) =     17.085 ms/op
     p(99.9990) =     17.746 ms/op
     p(99.9999) =     17.793 ms/op
    p(100.0000) =     17.793 ms/op


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
# Warmup Iteration   1: 3.762 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.024 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.993 ±(99.9%) 0.006 ms/op
Iteration   1: 2.904 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.660 ms/op
                 getUser·p0.50:   2.912 ms/op
                 getUser·p0.90:   3.428 ms/op
                 getUser·p0.95:   3.674 ms/op
                 getUser·p0.99:   4.227 ms/op
                 getUser·p0.999:  7.258 ms/op
                 getUser·p0.9999: 17.629 ms/op
                 getUser·p1.00:   17.990 ms/op

Iteration   2: 2.983 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.637 ms/op
                 getUser·p0.50:   2.990 ms/op
                 getUser·p0.90:   3.592 ms/op
                 getUser·p0.95:   3.744 ms/op
                 getUser·p0.99:   4.268 ms/op
                 getUser·p0.999:  6.724 ms/op
                 getUser·p0.9999: 23.331 ms/op
                 getUser·p1.00:   24.347 ms/op

Iteration   3: 2.938 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.616 ms/op
                 getUser·p0.50:   2.933 ms/op
                 getUser·p0.90:   3.334 ms/op
                 getUser·p0.95:   3.510 ms/op
                 getUser·p0.99:   4.133 ms/op
                 getUser·p0.999:  7.468 ms/op
                 getUser·p0.9999: 15.601 ms/op
                 getUser·p1.00:   16.908 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 326094
  mean =      2.942 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 35254 
    [ 2.500,  5.000) = 289829 
    [ 5.000,  7.500) = 730 
    [ 7.500, 10.000) = 86 
    [10.000, 12.500) = 35 
    [12.500, 15.000) = 83 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.616 ms/op
     p(50.0000) =      2.937 ms/op
     p(90.0000) =      3.469 ms/op
     p(95.0000) =      3.674 ms/op
     p(99.0000) =      4.219 ms/op
     p(99.9000) =      7.191 ms/op
     p(99.9900) =     19.602 ms/op
     p(99.9990) =     24.305 ms/op
     p(99.9999) =     24.347 ms/op
    p(100.0000) =     24.347 ms/op


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
# Warmup Iteration   1: 4.491 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.972 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.828 ±(99.9%) 0.010 ms/op
Iteration   1: 3.831 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.997 ms/op
                 listUser·p0.50:   3.674 ms/op
                 listUser·p0.90:   4.801 ms/op
                 listUser·p0.95:   5.595 ms/op
                 listUser·p0.99:   6.775 ms/op
                 listUser·p0.999:  14.426 ms/op
                 listUser·p0.9999: 17.737 ms/op
                 listUser·p1.00:   17.990 ms/op

Iteration   2: 3.798 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.891 ms/op
                 listUser·p0.50:   3.686 ms/op
                 listUser·p0.90:   4.506 ms/op
                 listUser·p0.95:   5.366 ms/op
                 listUser·p0.99:   6.516 ms/op
                 listUser·p0.999:  16.332 ms/op
                 listUser·p0.9999: 20.742 ms/op
                 listUser·p1.00:   21.496 ms/op

Iteration   3: 3.838 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.461 ms/op
                 listUser·p0.50:   3.715 ms/op
                 listUser·p0.90:   4.465 ms/op
                 listUser·p0.95:   5.194 ms/op
                 listUser·p0.99:   6.529 ms/op
                 listUser·p0.999:  15.401 ms/op
                 listUser·p0.9999: 22.337 ms/op
                 listUser·p1.00:   25.068 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 250990
  mean =      3.822 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4522 
    [ 2.500,  5.000) = 229275 
    [ 5.000,  7.500) = 15957 
    [ 7.500, 10.000) = 666 
    [10.000, 12.500) = 169 
    [12.500, 15.000) = 117 
    [15.000, 17.500) = 136 
    [17.500, 20.000) = 115 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.461 ms/op
     p(50.0000) =      3.695 ms/op
     p(90.0000) =      4.596 ms/op
     p(95.0000) =      5.423 ms/op
     p(99.0000) =      6.627 ms/op
     p(99.9000) =     15.352 ms/op
     p(99.9900) =     20.867 ms/op
     p(99.9990) =     22.510 ms/op
     p(99.9999) =     25.068 ms/op
    p(100.0000) =     25.068 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.809 ± 2.759  ops/ms
ClientGrpc.existUser                       thrpt       3  11.231 ± 2.851  ops/ms
ClientGrpc.getUser                         thrpt       3  10.974 ± 0.541  ops/ms
ClientGrpc.listUser                        thrpt       3   8.301 ± 1.143  ops/ms
ClientGrpc.createUser                       avgt       3   2.940 ± 0.491   ms/op
ClientGrpc.existUser                        avgt       3   2.816 ± 0.108   ms/op
ClientGrpc.getUser                          avgt       3   2.977 ± 0.538   ms/op
ClientGrpc.listUser                         avgt       3   3.776 ± 0.176   ms/op
ClientGrpc.createUser                     sample  323593   2.968 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.561           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.949           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.465           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.658           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.243           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.844           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          15.225           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          18.776           ms/op
ClientGrpc.existUser                      sample  342032   2.805 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.501           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.818           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.191           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.408           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.268           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.094           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.085           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.793           ms/op
ClientGrpc.getUser                        sample  326094   2.942 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.616           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.937           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.469           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.674           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.219           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.191           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.602           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          24.347           ms/op
ClientGrpc.listUser                       sample  250990   3.822 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.461           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.695           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.596           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.423           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.627           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.352           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          20.867           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.068           ms/op
