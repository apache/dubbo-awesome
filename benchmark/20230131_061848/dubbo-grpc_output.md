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
# Warmup Iteration   1: 4.565 ops/ms
# Warmup Iteration   2: 9.357 ops/ms
# Warmup Iteration   3: 10.727 ops/ms
Iteration   1: 10.363 ops/ms
Iteration   2: 10.384 ops/ms
Iteration   3: 10.252 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.333 ±(99.9%) 1.301 ops/ms [Average]
  (min, avg, max) = (10.252, 10.333, 10.384), stdev = 0.071
  CI (99.9%): [9.032, 11.634] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 8.094 ops/ms
# Warmup Iteration   2: 10.748 ops/ms
# Warmup Iteration   3: 10.908 ops/ms
Iteration   1: 10.884 ops/ms
Iteration   2: 10.798 ops/ms
Iteration   3: 10.690 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.791 ±(99.9%) 1.771 ops/ms [Average]
  (min, avg, max) = (10.690, 10.791, 10.884), stdev = 0.097
  CI (99.9%): [9.020, 12.561] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.963 ops/ms
# Warmup Iteration   2: 10.106 ops/ms
# Warmup Iteration   3: 10.521 ops/ms
Iteration   1: 10.488 ops/ms
Iteration   2: 10.631 ops/ms
Iteration   3: 10.436 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.518 ±(99.9%) 1.840 ops/ms [Average]
  (min, avg, max) = (10.436, 10.518, 10.631), stdev = 0.101
  CI (99.9%): [8.679, 12.358] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.692 ops/ms
# Warmup Iteration   2: 7.693 ops/ms
# Warmup Iteration   3: 7.799 ops/ms
Iteration   1: 8.031 ops/ms
Iteration   2: 7.978 ops/ms
Iteration   3: 7.962 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.990 ±(99.9%) 0.666 ops/ms [Average]
  (min, avg, max) = (7.962, 7.990, 8.031), stdev = 0.036
  CI (99.9%): [7.325, 8.656] (assumes normal distribution)


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
# Warmup Iteration   1: 4.017 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.067 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.034 ±(99.9%) 0.002 ms/op
Iteration   1: 3.148 ±(99.9%) 0.002 ms/op
Iteration   2: 3.052 ±(99.9%) 0.001 ms/op
Iteration   3: 3.087 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.096 ±(99.9%) 0.889 ms/op [Average]
  (min, avg, max) = (3.052, 3.096, 3.148), stdev = 0.049
  CI (99.9%): [2.206, 3.985] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.864 ±(99.9%) 0.008 ms/op
# Warmup Iteration   2: 3.053 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.978 ±(99.9%) 0.002 ms/op
Iteration   1: 2.911 ±(99.9%) 0.003 ms/op
Iteration   2: 3.009 ±(99.9%) 0.002 ms/op
Iteration   3: 2.914 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.945 ±(99.9%) 1.022 ms/op [Average]
  (min, avg, max) = (2.911, 2.945, 3.009), stdev = 0.056
  CI (99.9%): [1.923, 3.967] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 4.063 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.114 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.051 ±(99.9%) 0.002 ms/op
Iteration   1: 3.017 ±(99.9%) 0.002 ms/op
Iteration   2: 2.996 ±(99.9%) 0.003 ms/op
Iteration   3: 3.085 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.033 ±(99.9%) 0.849 ms/op [Average]
  (min, avg, max) = (2.996, 3.033, 3.085), stdev = 0.047
  CI (99.9%): [2.183, 3.882] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.872 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 4.082 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.971 ±(99.9%) 0.037 ms/op
Iteration   1: 4.051 ±(99.9%) 0.024 ms/op
Iteration   2: 3.926 ±(99.9%) 0.007 ms/op
Iteration   3: 3.828 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.935 ±(99.9%) 2.036 ms/op [Average]
  (min, avg, max) = (3.828, 3.935, 4.051), stdev = 0.112
  CI (99.9%): [1.899, 5.971] (assumes normal distribution)


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
# Warmup Iteration   1: 4.027 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.139 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.063 ±(99.9%) 0.006 ms/op
Iteration   1: 3.072 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.458 ms/op
                 createUser·p0.50:   3.052 ms/op
                 createUser·p0.90:   3.662 ms/op
                 createUser·p0.95:   3.875 ms/op
                 createUser·p0.99:   4.309 ms/op
                 createUser·p0.999:  7.962 ms/op
                 createUser·p0.9999: 11.633 ms/op
                 createUser·p1.00:   11.862 ms/op

Iteration   2: 3.026 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.634 ms/op
                 createUser·p0.50:   3.039 ms/op
                 createUser·p0.90:   3.572 ms/op
                 createUser·p0.95:   3.883 ms/op
                 createUser·p0.99:   4.514 ms/op
                 createUser·p0.999:  12.457 ms/op
                 createUser·p0.9999: 13.861 ms/op
                 createUser·p1.00:   14.926 ms/op

Iteration   3: 3.090 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.727 ms/op
                 createUser·p0.50:   3.068 ms/op
                 createUser·p0.90:   3.695 ms/op
                 createUser·p0.95:   3.858 ms/op
                 createUser·p0.99:   4.260 ms/op
                 createUser·p0.999:  13.912 ms/op
                 createUser·p0.9999: 24.563 ms/op
                 createUser·p1.00:   25.035 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 313789
  mean =      3.063 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26347 
    [ 2.500,  5.000) = 286072 
    [ 5.000,  7.500) = 816 
    [ 7.500, 10.000) = 232 
    [10.000, 12.500) = 95 
    [12.500, 15.000) = 160 
    [15.000, 17.500) = 35 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.458 ms/op
     p(50.0000) =      3.047 ms/op
     p(90.0000) =      3.658 ms/op
     p(95.0000) =      3.871 ms/op
     p(99.0000) =      4.334 ms/op
     p(99.9000) =     10.722 ms/op
     p(99.9900) =     23.863 ms/op
     p(99.9990) =     24.904 ms/op
     p(99.9999) =     25.035 ms/op
    p(100.0000) =     25.035 ms/op


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
# Warmup Iteration   1: 3.739 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.099 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.008 ±(99.9%) 0.006 ms/op
Iteration   1: 2.922 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.749 ms/op
                 existUser·p0.50:   2.900 ms/op
                 existUser·p0.90:   3.637 ms/op
                 existUser·p0.95:   3.846 ms/op
                 existUser·p0.99:   4.182 ms/op
                 existUser·p0.999:  5.510 ms/op
                 existUser·p0.9999: 11.584 ms/op
                 existUser·p1.00:   12.239 ms/op

Iteration   2: 2.989 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.569 ms/op
                 existUser·p0.50:   2.966 ms/op
                 existUser·p0.90:   3.637 ms/op
                 existUser·p0.95:   3.801 ms/op
                 existUser·p0.99:   4.100 ms/op
                 existUser·p0.999:  5.620 ms/op
                 existUser·p0.9999: 15.013 ms/op
                 existUser·p1.00:   15.270 ms/op

Iteration   3: 2.933 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.253 ms/op
                 existUser·p0.50:   2.925 ms/op
                 existUser·p0.90:   3.539 ms/op
                 existUser·p0.95:   3.740 ms/op
                 existUser·p0.99:   4.104 ms/op
                 existUser·p0.999:  6.659 ms/op
                 existUser·p0.9999: 17.438 ms/op
                 existUser·p1.00:   17.924 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 325600
  mean =      2.948 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1838 
    [ 1.250,  2.500) = 48475 
    [ 2.500,  3.750) = 255429 
    [ 3.750,  5.000) = 19263 
    [ 5.000,  6.250) = 294 
    [ 6.250,  7.500) = 137 
    [ 7.500,  8.750) = 4 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 13 
    [11.250, 12.500) = 19 
    [12.500, 13.750) = 20 
    [13.750, 15.000) = 64 
    [15.000, 16.250) = 20 
    [16.250, 17.500) = 15 
    [17.500, 18.750) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.253 ms/op
     p(50.0000) =      2.929 ms/op
     p(90.0000) =      3.609 ms/op
     p(95.0000) =      3.797 ms/op
     p(99.0000) =      4.133 ms/op
     p(99.9000) =      6.103 ms/op
     p(99.9900) =     15.472 ms/op
     p(99.9990) =     17.735 ms/op
     p(99.9999) =     17.924 ms/op
    p(100.0000) =     17.924 ms/op


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
# Warmup Iteration   1: 4.134 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.172 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.049 ±(99.9%) 0.007 ms/op
Iteration   1: 3.136 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.710 ms/op
                 getUser·p0.50:   3.121 ms/op
                 getUser·p0.90:   3.842 ms/op
                 getUser·p0.95:   4.022 ms/op
                 getUser·p0.99:   4.391 ms/op
                 getUser·p0.999:  7.891 ms/op
                 getUser·p0.9999: 11.905 ms/op
                 getUser·p1.00:   12.157 ms/op

Iteration   2: 3.130 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.631 ms/op
                 getUser·p0.50:   3.105 ms/op
                 getUser·p0.90:   3.793 ms/op
                 getUser·p0.95:   4.010 ms/op
                 getUser·p0.99:   4.334 ms/op
                 getUser·p0.999:  6.729 ms/op
                 getUser·p0.9999: 16.501 ms/op
                 getUser·p1.00:   16.941 ms/op

Iteration   3: 3.095 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.843 ms/op
                 getUser·p0.50:   3.068 ms/op
                 getUser·p0.90:   3.707 ms/op
                 getUser·p0.95:   3.920 ms/op
                 getUser·p0.99:   4.284 ms/op
                 getUser·p0.999:  6.344 ms/op
                 getUser·p0.9999: 13.970 ms/op
                 getUser·p1.00:   14.205 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 307588
  mean =      3.120 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1023 
    [ 1.250,  2.500) = 21956 
    [ 2.500,  3.750) = 249894 
    [ 3.750,  5.000) = 33917 
    [ 5.000,  6.250) = 404 
    [ 6.250,  7.500) = 168 
    [ 7.500,  8.750) = 65 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 41 
    [12.500, 13.750) = 25 
    [13.750, 15.000) = 31 
    [15.000, 16.250) = 17 
    [16.250, 17.500) = 15 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.631 ms/op
     p(50.0000) =      3.097 ms/op
     p(90.0000) =      3.789 ms/op
     p(95.0000) =      3.990 ms/op
     p(99.0000) =      4.334 ms/op
     p(99.9000) =      6.696 ms/op
     p(99.9900) =     15.634 ms/op
     p(99.9990) =     16.807 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.299 ±(99.9%) 0.071 ms/op
# Warmup Iteration   2: 4.208 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.068 ±(99.9%) 0.011 ms/op
Iteration   1: 3.955 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.946 ms/op
                 listUser·p0.50:   3.801 ms/op
                 listUser·p0.90:   5.128 ms/op
                 listUser·p0.95:   5.620 ms/op
                 listUser·p0.99:   6.845 ms/op
                 listUser·p0.999:  12.255 ms/op
                 listUser·p0.9999: 20.013 ms/op
                 listUser·p1.00:   20.546 ms/op

Iteration   2: 3.975 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.798 ms/op
                 listUser·p0.50:   3.813 ms/op
                 listUser·p0.90:   5.153 ms/op
                 listUser·p0.95:   5.841 ms/op
                 listUser·p0.99:   6.783 ms/op
                 listUser·p0.999:  15.183 ms/op
                 listUser·p0.9999: 23.686 ms/op
                 listUser·p1.00:   24.281 ms/op

Iteration   3: 3.912 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.764 ms/op
                 listUser·p0.50:   3.707 ms/op
                 listUser·p0.90:   5.186 ms/op
                 listUser·p0.95:   5.668 ms/op
                 listUser·p0.99:   7.004 ms/op
                 listUser·p0.999:  15.172 ms/op
                 listUser·p0.9999: 24.237 ms/op
                 listUser·p1.00:   24.576 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 243130
  mean =      3.947 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6530 
    [ 2.500,  5.000) = 207096 
    [ 5.000,  7.500) = 28285 
    [ 7.500, 10.000) = 768 
    [10.000, 12.500) = 124 
    [12.500, 15.000) = 128 
    [15.000, 17.500) = 73 
    [17.500, 20.000) = 54 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 38 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.764 ms/op
     p(50.0000) =      3.777 ms/op
     p(90.0000) =      5.161 ms/op
     p(95.0000) =      5.702 ms/op
     p(99.0000) =      6.873 ms/op
     p(99.9000) =     13.844 ms/op
     p(99.9900) =     23.058 ms/op
     p(99.9990) =     24.468 ms/op
     p(99.9999) =     24.576 ms/op
    p(100.0000) =     24.576 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.333 ± 1.301  ops/ms
ClientGrpc.existUser                       thrpt       3  10.791 ± 1.771  ops/ms
ClientGrpc.getUser                         thrpt       3  10.518 ± 1.840  ops/ms
ClientGrpc.listUser                        thrpt       3   7.990 ± 0.666  ops/ms
ClientGrpc.createUser                       avgt       3   3.096 ± 0.889   ms/op
ClientGrpc.existUser                        avgt       3   2.945 ± 1.022   ms/op
ClientGrpc.getUser                          avgt       3   3.033 ± 0.849   ms/op
ClientGrpc.listUser                         avgt       3   3.935 ± 2.036   ms/op
ClientGrpc.createUser                     sample  313789   3.063 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.458           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.047           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.658           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.871           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.334           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.722           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          23.863           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          25.035           ms/op
ClientGrpc.existUser                      sample  325600   2.948 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.253           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.929           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.609           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.797           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.133           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.103           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.472           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.924           ms/op
ClientGrpc.getUser                        sample  307588   3.120 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.631           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.097           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.789           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.990           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.334           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.696           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          15.634           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          16.941           ms/op
ClientGrpc.listUser                       sample  243130   3.947 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.764           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.777           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.161           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.702           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.873           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.844           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.058           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.576           ms/op
