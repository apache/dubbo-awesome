# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.565 ops/ms
# Warmup Iteration   2: 6.239 ops/ms
# Warmup Iteration   3: 9.382 ops/ms
Iteration   1: 9.519 ops/ms
Iteration   2: 10.249 ops/ms
Iteration   3: 9.876 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.881 ±(99.9%) 6.664 ops/ms [Average]
  (min, avg, max) = (9.519, 9.881, 10.249), stdev = 0.365
  CI (99.9%): [3.218, 16.545] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.986 ops/ms
# Warmup Iteration   2: 9.496 ops/ms
# Warmup Iteration   3: 9.769 ops/ms
Iteration   1: 10.199 ops/ms
Iteration   2: 10.604 ops/ms
Iteration   3: 10.839 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.547 ±(99.9%) 5.904 ops/ms [Average]
  (min, avg, max) = (10.199, 10.547, 10.839), stdev = 0.324
  CI (99.9%): [4.643, 16.451] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.715 ops/ms
# Warmup Iteration   2: 8.192 ops/ms
# Warmup Iteration   3: 10.093 ops/ms
Iteration   1: 10.074 ops/ms
Iteration   2: 10.203 ops/ms
Iteration   3: 10.046 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.108 ±(99.9%) 1.536 ops/ms [Average]
  (min, avg, max) = (10.046, 10.108, 10.203), stdev = 0.084
  CI (99.9%): [8.571, 11.644] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.121 ops/ms
# Warmup Iteration   2: 7.911 ops/ms
# Warmup Iteration   3: 8.352 ops/ms
Iteration   1: 8.600 ops/ms
Iteration   2: 8.763 ops/ms
Iteration   3: 8.734 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.699 ±(99.9%) 1.585 ops/ms [Average]
  (min, avg, max) = (8.600, 8.699, 8.763), stdev = 0.087
  CI (99.9%): [7.114, 10.284] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 9.164 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.678 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.201 ±(99.9%) 0.007 ms/op
Iteration   1: 3.198 ±(99.9%) 0.005 ms/op
Iteration   2: 3.204 ±(99.9%) 0.004 ms/op
Iteration   3: 3.183 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.195 ±(99.9%) 0.198 ms/op [Average]
  (min, avg, max) = (3.183, 3.195, 3.204), stdev = 0.011
  CI (99.9%): [2.997, 3.393] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 6.507 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.492 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.114 ±(99.9%) 0.003 ms/op
Iteration   1: 3.226 ±(99.9%) 0.004 ms/op
Iteration   2: 3.016 ±(99.9%) 0.003 ms/op
Iteration   3: 3.101 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.114 ±(99.9%) 1.929 ms/op [Average]
  (min, avg, max) = (3.016, 3.114, 3.226), stdev = 0.106
  CI (99.9%): [1.185, 5.043] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 8.016 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.404 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.270 ±(99.9%) 0.003 ms/op
Iteration   1: 3.074 ±(99.9%) 0.004 ms/op
Iteration   2: 3.182 ±(99.9%) 0.004 ms/op
Iteration   3: 3.089 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.115 ±(99.9%) 1.072 ms/op [Average]
  (min, avg, max) = (3.074, 3.115, 3.182), stdev = 0.059
  CI (99.9%): [2.043, 4.188] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 8.699 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.007 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.789 ±(99.9%) 0.008 ms/op
Iteration   1: 3.650 ±(99.9%) 0.008 ms/op
Iteration   2: 3.662 ±(99.9%) 0.006 ms/op
Iteration   3: 3.691 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.668 ±(99.9%) 0.386 ms/op [Average]
  (min, avg, max) = (3.650, 3.668, 3.691), stdev = 0.021
  CI (99.9%): [3.282, 4.054] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 8.299 ±(99.9%) 0.096 ms/op
# Warmup Iteration   2: 3.598 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.373 ±(99.9%) 0.009 ms/op
Iteration   1: 3.164 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.354 ms/op
                 createUser·p0.50:   2.974 ms/op
                 createUser·p0.90:   3.641 ms/op
                 createUser·p0.95:   4.358 ms/op
                 createUser·p0.99:   5.975 ms/op
                 createUser·p0.999:  11.431 ms/op
                 createUser·p0.9999: 21.099 ms/op
                 createUser·p1.00:   21.987 ms/op

Iteration   2: 3.251 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.948 ms/op
                 createUser·p0.50:   3.166 ms/op
                 createUser·p0.90:   3.801 ms/op
                 createUser·p0.95:   4.112 ms/op
                 createUser·p0.99:   5.595 ms/op
                 createUser·p0.999:  14.729 ms/op
                 createUser·p0.9999: 20.557 ms/op
                 createUser·p1.00:   21.463 ms/op

Iteration   3: 3.159 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.120 ms/op
                 createUser·p0.50:   3.101 ms/op
                 createUser·p0.90:   3.494 ms/op
                 createUser·p0.95:   3.797 ms/op
                 createUser·p0.99:   5.530 ms/op
                 createUser·p0.999:  16.382 ms/op
                 createUser·p0.9999: 22.610 ms/op
                 createUser·p1.00:   23.298 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 300518
  mean =      3.191 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16758 
    [ 2.500,  5.000) = 277629 
    [ 5.000,  7.500) = 5104 
    [ 7.500, 10.000) = 510 
    [10.000, 12.500) = 152 
    [12.500, 15.000) = 61 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 209 
    [20.000, 22.500) = 56 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.948 ms/op
     p(50.0000) =      3.072 ms/op
     p(90.0000) =      3.670 ms/op
     p(95.0000) =      4.088 ms/op
     p(99.0000) =      5.757 ms/op
     p(99.9000) =     15.334 ms/op
     p(99.9900) =     21.168 ms/op
     p(99.9990) =     23.199 ms/op
     p(99.9999) =     23.298 ms/op
    p(100.0000) =     23.298 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 9.169 ±(99.9%) 0.101 ms/op
# Warmup Iteration   2: 3.558 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.081 ±(99.9%) 0.007 ms/op
Iteration   1: 3.050 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.987 ms/op
                 existUser·p0.50:   3.060 ms/op
                 existUser·p0.90:   3.174 ms/op
                 existUser·p0.95:   3.297 ms/op
                 existUser·p0.99:   5.210 ms/op
                 existUser·p0.999:  9.863 ms/op
                 existUser·p0.9999: 19.710 ms/op
                 existUser·p1.00:   21.037 ms/op

Iteration   2: 2.999 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.245 ms/op
                 existUser·p0.50:   2.970 ms/op
                 existUser·p0.90:   3.097 ms/op
                 existUser·p0.95:   3.154 ms/op
                 existUser·p0.99:   5.341 ms/op
                 existUser·p0.999:  17.342 ms/op
                 existUser·p0.9999: 20.653 ms/op
                 existUser·p1.00:   21.168 ms/op

Iteration   3: 3.034 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.036 ms/op
                 existUser·p0.50:   2.945 ms/op
                 existUser·p0.90:   3.174 ms/op
                 existUser·p0.95:   3.416 ms/op
                 existUser·p0.99:   5.415 ms/op
                 existUser·p0.999:  12.772 ms/op
                 existUser·p0.9999: 23.164 ms/op
                 existUser·p1.00:   23.757 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 317215
  mean =      3.027 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23412 
    [ 2.500,  5.000) = 288347 
    [ 5.000,  7.500) = 4593 
    [ 7.500, 10.000) = 355 
    [10.000, 12.500) = 134 
    [12.500, 15.000) = 108 
    [15.000, 17.500) = 51 
    [17.500, 20.000) = 137 
    [20.000, 22.500) = 57 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.987 ms/op
     p(50.0000) =      2.990 ms/op
     p(90.0000) =      3.154 ms/op
     p(95.0000) =      3.297 ms/op
     p(99.0000) =      5.308 ms/op
     p(99.9000) =     13.333 ms/op
     p(99.9900) =     21.359 ms/op
     p(99.9990) =     23.626 ms/op
     p(99.9999) =     23.757 ms/op
    p(100.0000) =     23.757 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 7.805 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 3.512 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.181 ±(99.9%) 0.008 ms/op
Iteration   1: 3.270 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.200 ms/op
                 getUser·p0.50:   3.105 ms/op
                 getUser·p0.90:   3.637 ms/op
                 getUser·p0.95:   4.891 ms/op
                 getUser·p0.99:   6.603 ms/op
                 getUser·p0.999:  14.529 ms/op
                 getUser·p0.9999: 20.127 ms/op
                 getUser·p1.00:   23.855 ms/op

Iteration   2: 3.189 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.728 ms/op
                 getUser·p0.50:   3.097 ms/op
                 getUser·p0.90:   3.555 ms/op
                 getUser·p0.95:   3.731 ms/op
                 getUser·p0.99:   5.415 ms/op
                 getUser·p0.999:  16.770 ms/op
                 getUser·p0.9999: 23.887 ms/op
                 getUser·p1.00:   24.707 ms/op

Iteration   3: 3.081 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.163 ms/op
                 getUser·p0.50:   2.990 ms/op
                 getUser·p0.90:   3.342 ms/op
                 getUser·p0.95:   3.531 ms/op
                 getUser·p0.99:   5.346 ms/op
                 getUser·p0.999:  10.633 ms/op
                 getUser·p0.9999: 22.020 ms/op
                 getUser·p1.00:   22.512 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 301763
  mean =      3.178 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10057 
    [ 2.500,  5.000) = 284442 
    [ 5.000,  7.500) = 6292 
    [ 7.500, 10.000) = 512 
    [10.000, 12.500) = 64 
    [12.500, 15.000) = 81 
    [15.000, 17.500) = 61 
    [17.500, 20.000) = 121 
    [20.000, 22.500) = 94 
    [22.500, 25.000) = 39 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.728 ms/op
     p(50.0000) =      3.056 ms/op
     p(90.0000) =      3.506 ms/op
     p(95.0000) =      3.797 ms/op
     p(99.0000) =      6.103 ms/op
     p(99.9000) =     15.281 ms/op
     p(99.9900) =     22.756 ms/op
     p(99.9990) =     24.665 ms/op
     p(99.9999) =     24.707 ms/op
    p(100.0000) =     24.707 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 9.306 ±(99.9%) 0.106 ms/op
# Warmup Iteration   2: 4.077 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.733 ±(99.9%) 0.012 ms/op
Iteration   1: 3.709 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.993 ms/op
                 listUser·p0.50:   3.547 ms/op
                 listUser·p0.90:   3.990 ms/op
                 listUser·p0.95:   4.448 ms/op
                 listUser·p0.99:   7.196 ms/op
                 listUser·p0.999:  14.582 ms/op
                 listUser·p0.9999: 19.005 ms/op
                 listUser·p1.00:   19.530 ms/op

Iteration   2: 3.697 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.944 ms/op
                 listUser·p0.50:   3.641 ms/op
                 listUser·p0.90:   3.895 ms/op
                 listUser·p0.95:   4.112 ms/op
                 listUser·p0.99:   6.423 ms/op
                 listUser·p0.999:  15.884 ms/op
                 listUser·p0.9999: 22.118 ms/op
                 listUser·p1.00:   22.184 ms/op

Iteration   3: 3.645 ±(99.9%) 0.007 ms/op
                 listUser·p0.00:   1.321 ms/op
                 listUser·p0.50:   3.621 ms/op
                 listUser·p0.90:   3.817 ms/op
                 listUser·p0.95:   4.092 ms/op
                 listUser·p0.99:   6.242 ms/op
                 listUser·p0.999:  13.304 ms/op
                 listUser·p0.9999: 14.680 ms/op
                 listUser·p1.00:   16.695 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 260497
  mean =      3.683 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 101 
    [ 2.500,  5.000) = 252698 
    [ 5.000,  7.500) = 6127 
    [ 7.500, 10.000) = 894 
    [10.000, 12.500) = 215 
    [12.500, 15.000) = 286 
    [15.000, 17.500) = 89 
    [17.500, 20.000) = 55 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.321 ms/op
     p(50.0000) =      3.604 ms/op
     p(90.0000) =      3.908 ms/op
     p(95.0000) =      4.202 ms/op
     p(99.0000) =      6.668 ms/op
     p(99.9000) =     14.107 ms/op
     p(99.9900) =     21.332 ms/op
     p(99.9990) =     22.151 ms/op
     p(99.9999) =     22.184 ms/op
    p(100.0000) =     22.184 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.881 ± 6.664  ops/ms
ClientPb.existUser                       thrpt       3  10.547 ± 5.904  ops/ms
ClientPb.getUser                         thrpt       3  10.108 ± 1.536  ops/ms
ClientPb.listUser                        thrpt       3   8.699 ± 1.585  ops/ms
ClientPb.createUser                       avgt       3   3.195 ± 0.198   ms/op
ClientPb.existUser                        avgt       3   3.114 ± 1.929   ms/op
ClientPb.getUser                          avgt       3   3.115 ± 1.072   ms/op
ClientPb.listUser                         avgt       3   3.668 ± 0.386   ms/op
ClientPb.createUser                     sample  300518   3.191 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.948           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.072           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.670           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.088           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.757           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.334           ms/op
ClientPb.createUser:createUser·p0.9999  sample          21.168           ms/op
ClientPb.createUser:createUser·p1.00    sample          23.298           ms/op
ClientPb.existUser                      sample  317215   3.027 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.987           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.990           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.154           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.297           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.308           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.333           ms/op
ClientPb.existUser:existUser·p0.9999    sample          21.359           ms/op
ClientPb.existUser:existUser·p1.00      sample          23.757           ms/op
ClientPb.getUser                        sample  301763   3.178 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.728           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.056           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.506           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.797           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.103           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.281           ms/op
ClientPb.getUser:getUser·p0.9999        sample          22.756           ms/op
ClientPb.getUser:getUser·p1.00          sample          24.707           ms/op
ClientPb.listUser                       sample  260497   3.683 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.321           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.604           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.908           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.202           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.668           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.107           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.332           ms/op
ClientPb.listUser:listUser·p1.00        sample          22.184           ms/op
