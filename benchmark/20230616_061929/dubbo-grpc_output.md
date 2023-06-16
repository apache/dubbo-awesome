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
# Warmup Iteration   1: 4.349 ops/ms
# Warmup Iteration   2: 9.440 ops/ms
# Warmup Iteration   3: 10.187 ops/ms
Iteration   1: 10.664 ops/ms
Iteration   2: 10.751 ops/ms
Iteration   3: 10.726 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.714 ±(99.9%) 0.815 ops/ms [Average]
  (min, avg, max) = (10.664, 10.714, 10.751), stdev = 0.045
  CI (99.9%): [9.899, 11.529] (assumes normal distribution)


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
# Warmup Iteration   1: 7.861 ops/ms
# Warmup Iteration   2: 10.695 ops/ms
# Warmup Iteration   3: 11.109 ops/ms
Iteration   1: 11.311 ops/ms
Iteration   2: 11.334 ops/ms
Iteration   3: 11.335 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.326 ±(99.9%) 0.248 ops/ms [Average]
  (min, avg, max) = (11.311, 11.326, 11.335), stdev = 0.014
  CI (99.9%): [11.079, 11.574] (assumes normal distribution)


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
# Warmup Iteration   1: 7.715 ops/ms
# Warmup Iteration   2: 10.566 ops/ms
# Warmup Iteration   3: 10.719 ops/ms
Iteration   1: 10.984 ops/ms
Iteration   2: 11.028 ops/ms
Iteration   3: 10.848 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.953 ±(99.9%) 1.709 ops/ms [Average]
  (min, avg, max) = (10.848, 10.953, 11.028), stdev = 0.094
  CI (99.9%): [9.244, 12.663] (assumes normal distribution)


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
# Warmup Iteration   1: 6.752 ops/ms
# Warmup Iteration   2: 7.990 ops/ms
# Warmup Iteration   3: 8.071 ops/ms
Iteration   1: 8.324 ops/ms
Iteration   2: 8.751 ops/ms
Iteration   3: 8.273 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.449 ±(99.9%) 4.783 ops/ms [Average]
  (min, avg, max) = (8.273, 8.449, 8.751), stdev = 0.262
  CI (99.9%): [3.667, 13.232] (assumes normal distribution)


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
# Warmup Iteration   1: 4.158 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.063 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 2.999 ±(99.9%) 0.002 ms/op
Iteration   1: 2.956 ±(99.9%) 0.002 ms/op
Iteration   2: 2.935 ±(99.9%) 0.002 ms/op
Iteration   3: 2.887 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.926 ±(99.9%) 0.648 ms/op [Average]
  (min, avg, max) = (2.887, 2.926, 2.956), stdev = 0.036
  CI (99.9%): [2.278, 3.574] (assumes normal distribution)


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
# Warmup Iteration   1: 3.272 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.939 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.868 ±(99.9%) 0.004 ms/op
Iteration   1: 2.829 ±(99.9%) 0.003 ms/op
Iteration   2: 2.818 ±(99.9%) 0.003 ms/op
Iteration   3: 2.840 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.829 ±(99.9%) 0.198 ms/op [Average]
  (min, avg, max) = (2.818, 2.829, 2.840), stdev = 0.011
  CI (99.9%): [2.631, 3.027] (assumes normal distribution)


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
# Warmup Iteration   1: 4.104 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.098 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.973 ±(99.9%) 0.002 ms/op
Iteration   1: 2.958 ±(99.9%) 0.002 ms/op
Iteration   2: 2.982 ±(99.9%) 0.003 ms/op
Iteration   3: 2.974 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.971 ±(99.9%) 0.230 ms/op [Average]
  (min, avg, max) = (2.958, 2.971, 2.982), stdev = 0.013
  CI (99.9%): [2.742, 3.201] (assumes normal distribution)


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
# Warmup Iteration   1: 5.089 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 4.012 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.835 ±(99.9%) 0.013 ms/op
Iteration   1: 3.812 ±(99.9%) 0.032 ms/op
Iteration   2: 3.830 ±(99.9%) 0.039 ms/op
Iteration   3: 3.853 ±(99.9%) 0.023 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.832 ±(99.9%) 0.377 ms/op [Average]
  (min, avg, max) = (3.812, 3.832, 3.853), stdev = 0.021
  CI (99.9%): [3.454, 4.209] (assumes normal distribution)


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
# Warmup Iteration   1: 4.052 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.085 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.996 ±(99.9%) 0.006 ms/op
Iteration   1: 2.955 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.728 ms/op
                 createUser·p0.50:   2.929 ms/op
                 createUser·p0.90:   3.383 ms/op
                 createUser·p0.95:   3.604 ms/op
                 createUser·p0.99:   4.108 ms/op
                 createUser·p0.999:  6.781 ms/op
                 createUser·p0.9999: 13.405 ms/op
                 createUser·p1.00:   13.648 ms/op

Iteration   2: 3.038 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.723 ms/op
                 createUser·p0.50:   2.986 ms/op
                 createUser·p0.90:   3.506 ms/op
                 createUser·p0.95:   3.740 ms/op
                 createUser·p0.99:   4.432 ms/op
                 createUser·p0.999:  9.077 ms/op
                 createUser·p0.9999: 22.232 ms/op
                 createUser·p1.00:   22.544 ms/op

Iteration   3: 2.937 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.384 ms/op
                 createUser·p0.50:   2.929 ms/op
                 createUser·p0.90:   3.424 ms/op
                 createUser·p0.95:   3.641 ms/op
                 createUser·p0.99:   4.325 ms/op
                 createUser·p0.999:  8.781 ms/op
                 createUser·p0.9999: 20.581 ms/op
                 createUser·p1.00:   20.972 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 322617
  mean =      2.976 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26767 
    [ 2.500,  5.000) = 294510 
    [ 5.000,  7.500) = 819 
    [ 7.500, 10.000) = 261 
    [10.000, 12.500) = 69 
    [12.500, 15.000) = 122 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 55 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.384 ms/op
     p(50.0000) =      2.945 ms/op
     p(90.0000) =      3.441 ms/op
     p(95.0000) =      3.670 ms/op
     p(99.0000) =      4.299 ms/op
     p(99.9000) =      8.897 ms/op
     p(99.9900) =     21.262 ms/op
     p(99.9990) =     22.479 ms/op
     p(99.9999) =     22.544 ms/op
    p(100.0000) =     22.544 ms/op


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
# Warmup Iteration   1: 3.949 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 2.974 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.841 ±(99.9%) 0.006 ms/op
Iteration   1: 2.854 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.675 ms/op
                 existUser·p0.50:   2.855 ms/op
                 existUser·p0.90:   3.281 ms/op
                 existUser·p0.95:   3.461 ms/op
                 existUser·p0.99:   4.174 ms/op
                 existUser·p0.999:  5.791 ms/op
                 existUser·p0.9999: 16.217 ms/op
                 existUser·p1.00:   16.695 ms/op

Iteration   2: 2.870 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.579 ms/op
                 existUser·p0.50:   2.875 ms/op
                 existUser·p0.90:   3.334 ms/op
                 existUser·p0.95:   3.609 ms/op
                 existUser·p0.99:   4.366 ms/op
                 existUser·p0.999:  6.549 ms/op
                 existUser·p0.9999: 19.492 ms/op
                 existUser·p1.00:   20.447 ms/op

Iteration   3: 2.846 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.510 ms/op
                 existUser·p0.50:   2.863 ms/op
                 existUser·p0.90:   3.219 ms/op
                 existUser·p0.95:   3.461 ms/op
                 existUser·p0.99:   4.227 ms/op
                 existUser·p0.999:  6.215 ms/op
                 existUser·p0.9999: 13.660 ms/op
                 existUser·p1.00:   14.008 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 336010
  mean =      2.857 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 41379 
    [ 2.500,  5.000) = 293678 
    [ 5.000,  7.500) = 760 
    [ 7.500, 10.000) = 35 
    [10.000, 12.500) = 61 
    [12.500, 15.000) = 33 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.510 ms/op
     p(50.0000) =      2.863 ms/op
     p(90.0000) =      3.277 ms/op
     p(95.0000) =      3.510 ms/op
     p(99.0000) =      4.268 ms/op
     p(99.9000) =      6.234 ms/op
     p(99.9900) =     16.646 ms/op
     p(99.9990) =     20.370 ms/op
     p(99.9999) =     20.447 ms/op
    p(100.0000) =     20.447 ms/op


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
# Warmup Iteration   1: 3.865 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.063 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.030 ±(99.9%) 0.005 ms/op
Iteration   1: 2.945 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.803 ms/op
                 getUser·p0.50:   2.961 ms/op
                 getUser·p0.90:   3.502 ms/op
                 getUser·p0.95:   3.785 ms/op
                 getUser·p0.99:   4.415 ms/op
                 getUser·p0.999:  7.511 ms/op
                 getUser·p0.9999: 12.077 ms/op
                 getUser·p1.00:   16.302 ms/op

Iteration   2: 2.893 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.637 ms/op
                 getUser·p0.50:   2.925 ms/op
                 getUser·p0.90:   3.305 ms/op
                 getUser·p0.95:   3.502 ms/op
                 getUser·p0.99:   4.219 ms/op
                 getUser·p0.999:  6.675 ms/op
                 getUser·p0.9999: 15.382 ms/op
                 getUser·p1.00:   15.630 ms/op

Iteration   3: 2.999 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.667 ms/op
                 getUser·p0.50:   2.978 ms/op
                 getUser·p0.90:   3.482 ms/op
                 getUser·p0.95:   3.662 ms/op
                 getUser·p0.99:   4.268 ms/op
                 getUser·p0.999:  10.369 ms/op
                 getUser·p0.9999: 16.040 ms/op
                 getUser·p1.00:   17.203 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 326136
  mean =      2.945 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1796 
    [ 1.250,  2.500) = 31464 
    [ 2.500,  3.750) = 279898 
    [ 3.750,  5.000) = 11832 
    [ 5.000,  6.250) = 631 
    [ 6.250,  7.500) = 163 
    [ 7.500,  8.750) = 65 
    [ 8.750, 10.000) = 17 
    [10.000, 11.250) = 59 
    [11.250, 12.500) = 72 
    [12.500, 13.750) = 21 
    [13.750, 15.000) = 39 
    [15.000, 16.250) = 74 
    [16.250, 17.500) = 5 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.637 ms/op
     p(50.0000) =      2.953 ms/op
     p(90.0000) =      3.428 ms/op
     p(95.0000) =      3.662 ms/op
     p(99.0000) =      4.301 ms/op
     p(99.9000) =      8.010 ms/op
     p(99.9900) =     15.581 ms/op
     p(99.9990) =     16.326 ms/op
     p(99.9999) =     17.203 ms/op
    p(100.0000) =     17.203 ms/op


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
# Warmup Iteration   1: 5.004 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 4.055 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.900 ±(99.9%) 0.010 ms/op
Iteration   1: 3.872 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.325 ms/op
                 listUser·p0.50:   3.748 ms/op
                 listUser·p0.90:   4.719 ms/op
                 listUser·p0.95:   5.702 ms/op
                 listUser·p0.99:   6.865 ms/op
                 listUser·p0.999:  11.796 ms/op
                 listUser·p0.9999: 16.031 ms/op
                 listUser·p1.00:   16.433 ms/op

Iteration   2: 3.924 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.272 ms/op
                 listUser·p0.50:   3.768 ms/op
                 listUser·p0.90:   4.882 ms/op
                 listUser·p0.95:   5.759 ms/op
                 listUser·p0.99:   6.793 ms/op
                 listUser·p0.999:  15.344 ms/op
                 listUser·p0.9999: 20.891 ms/op
                 listUser·p1.00:   21.463 ms/op

Iteration   3: 3.902 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.006 ms/op
                 listUser·p0.50:   3.752 ms/op
                 listUser·p0.90:   4.776 ms/op
                 listUser·p0.95:   5.554 ms/op
                 listUser·p0.99:   6.660 ms/op
                 listUser·p0.999:  14.435 ms/op
                 listUser·p0.9999: 18.704 ms/op
                 listUser·p1.00:   18.809 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 246081
  mean =      3.899 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4061 
    [ 2.500,  5.000) = 221495 
    [ 5.000,  7.500) = 19275 
    [ 7.500, 10.000) = 767 
    [10.000, 12.500) = 170 
    [12.500, 15.000) = 103 
    [15.000, 17.500) = 157 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.006 ms/op
     p(50.0000) =      3.756 ms/op
     p(90.0000) =      4.801 ms/op
     p(95.0000) =      5.669 ms/op
     p(99.0000) =      6.767 ms/op
     p(99.9000) =     14.496 ms/op
     p(99.9900) =     19.497 ms/op
     p(99.9990) =     21.319 ms/op
     p(99.9999) =     21.463 ms/op
    p(100.0000) =     21.463 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.714 ± 0.815  ops/ms
ClientGrpc.existUser                       thrpt       3  11.326 ± 0.248  ops/ms
ClientGrpc.getUser                         thrpt       3  10.953 ± 1.709  ops/ms
ClientGrpc.listUser                        thrpt       3   8.449 ± 4.783  ops/ms
ClientGrpc.createUser                       avgt       3   2.926 ± 0.648   ms/op
ClientGrpc.existUser                        avgt       3   2.829 ± 0.198   ms/op
ClientGrpc.getUser                          avgt       3   2.971 ± 0.230   ms/op
ClientGrpc.listUser                         avgt       3   3.832 ± 0.377   ms/op
ClientGrpc.createUser                     sample  322617   2.976 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.384           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.945           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.441           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.670           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.299           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.897           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.262           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.544           ms/op
ClientGrpc.existUser                      sample  336010   2.857 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.510           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.863           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.277           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.510           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.268           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.234           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.646           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.447           ms/op
ClientGrpc.getUser                        sample  326136   2.945 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.637           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.953           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.428           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.662           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.301           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.010           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          15.581           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          17.203           ms/op
ClientGrpc.listUser                       sample  246081   3.899 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.006           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.756           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.801           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.669           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.767           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.496           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          19.497           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          21.463           ms/op
