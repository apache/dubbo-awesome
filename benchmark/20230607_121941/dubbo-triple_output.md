# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.619 ops/ms
# Warmup Iteration   2: 6.205 ops/ms
# Warmup Iteration   3: 9.366 ops/ms
Iteration   1: 10.012 ops/ms
Iteration   2: 9.976 ops/ms
Iteration   3: 9.850 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.946 ±(99.9%) 1.551 ops/ms [Average]
  (min, avg, max) = (9.850, 9.946, 10.012), stdev = 0.085
  CI (99.9%): [8.395, 11.497] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 3.481 ops/ms
# Warmup Iteration   2: 9.580 ops/ms
# Warmup Iteration   3: 9.876 ops/ms
Iteration   1: 10.049 ops/ms
Iteration   2: 10.033 ops/ms
Iteration   3: 10.710 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.264 ±(99.9%) 7.046 ops/ms [Average]
  (min, avg, max) = (10.033, 10.264, 10.710), stdev = 0.386
  CI (99.9%): [3.218, 17.310] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.173 ops/ms
# Warmup Iteration   2: 9.010 ops/ms
# Warmup Iteration   3: 9.889 ops/ms
Iteration   1: 10.002 ops/ms
Iteration   2: 9.805 ops/ms
Iteration   3: 10.219 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.009 ±(99.9%) 3.779 ops/ms [Average]
  (min, avg, max) = (9.805, 10.009, 10.219), stdev = 0.207
  CI (99.9%): [6.230, 13.788] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.074 ops/ms
# Warmup Iteration   2: 7.597 ops/ms
# Warmup Iteration   3: 8.124 ops/ms
Iteration   1: 8.498 ops/ms
Iteration   2: 8.425 ops/ms
Iteration   3: 8.565 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.496 ±(99.9%) 1.283 ops/ms [Average]
  (min, avg, max) = (8.425, 8.496, 8.565), stdev = 0.070
  CI (99.9%): [7.213, 9.779] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 8.221 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.616 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.263 ±(99.9%) 0.007 ms/op
Iteration   1: 3.213 ±(99.9%) 0.008 ms/op
Iteration   2: 3.122 ±(99.9%) 0.007 ms/op
Iteration   3: 3.241 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.192 ±(99.9%) 1.134 ms/op [Average]
  (min, avg, max) = (3.122, 3.192, 3.241), stdev = 0.062
  CI (99.9%): [2.058, 4.327] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 7.021 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.342 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.170 ±(99.9%) 0.006 ms/op
Iteration   1: 3.172 ±(99.9%) 0.006 ms/op
Iteration   2: 3.124 ±(99.9%) 0.007 ms/op
Iteration   3: 3.052 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.116 ±(99.9%) 1.103 ms/op [Average]
  (min, avg, max) = (3.052, 3.116, 3.172), stdev = 0.060
  CI (99.9%): [2.013, 4.219] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 9.364 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.604 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.218 ±(99.9%) 0.004 ms/op
Iteration   1: 3.181 ±(99.9%) 0.004 ms/op
Iteration   2: 3.191 ±(99.9%) 0.006 ms/op
Iteration   3: 3.254 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.209 ±(99.9%) 0.721 ms/op [Average]
  (min, avg, max) = (3.181, 3.209, 3.254), stdev = 0.040
  CI (99.9%): [2.488, 3.930] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 9.809 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 4.147 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.936 ±(99.9%) 0.006 ms/op
Iteration   1: 3.761 ±(99.9%) 0.005 ms/op
Iteration   2: 3.782 ±(99.9%) 0.007 ms/op
Iteration   3: 3.815 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.786 ±(99.9%) 0.498 ms/op [Average]
  (min, avg, max) = (3.761, 3.786, 3.815), stdev = 0.027
  CI (99.9%): [3.288, 4.285] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 7.796 ±(99.9%) 0.103 ms/op
# Warmup Iteration   2: 3.598 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.284 ±(99.9%) 0.008 ms/op
Iteration   1: 3.198 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.031 ms/op
                 createUser·p0.50:   3.183 ms/op
                 createUser·p0.90:   3.400 ms/op
                 createUser·p0.95:   3.699 ms/op
                 createUser·p0.99:   5.562 ms/op
                 createUser·p0.999:  18.776 ms/op
                 createUser·p0.9999: 20.578 ms/op
                 createUser·p1.00:   21.201 ms/op

Iteration   2: 3.272 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.782 ms/op
                 createUser·p0.50:   3.109 ms/op
                 createUser·p0.90:   3.781 ms/op
                 createUser·p0.95:   4.448 ms/op
                 createUser·p0.99:   5.720 ms/op
                 createUser·p0.999:  14.048 ms/op
                 createUser·p0.9999: 22.675 ms/op
                 createUser·p1.00:   23.003 ms/op

Iteration   3: 3.315 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.229 ms/op
                 createUser·p0.50:   3.289 ms/op
                 createUser·p0.90:   3.584 ms/op
                 createUser·p0.95:   4.137 ms/op
                 createUser·p0.99:   5.513 ms/op
                 createUser·p0.999:  15.904 ms/op
                 createUser·p0.9999: 20.000 ms/op
                 createUser·p1.00:   22.446 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 294328
  mean =      3.261 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22950 
    [ 2.500,  5.000) = 264479 
    [ 5.000,  7.500) = 6013 
    [ 7.500, 10.000) = 356 
    [10.000, 12.500) = 121 
    [12.500, 15.000) = 59 
    [15.000, 17.500) = 58 
    [17.500, 20.000) = 176 
    [20.000, 22.500) = 103 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.782 ms/op
     p(50.0000) =      3.199 ms/op
     p(90.0000) =      3.572 ms/op
     p(95.0000) =      4.141 ms/op
     p(99.0000) =      5.571 ms/op
     p(99.9000) =     17.334 ms/op
     p(99.9900) =     22.118 ms/op
     p(99.9990) =     22.743 ms/op
     p(99.9999) =     23.003 ms/op
    p(100.0000) =     23.003 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.732 ±(99.9%) 0.094 ms/op
# Warmup Iteration   2: 3.431 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.126 ±(99.9%) 0.008 ms/op
Iteration   1: 3.265 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.270 ms/op
                 existUser·p0.50:   3.215 ms/op
                 existUser·p0.90:   3.637 ms/op
                 existUser·p0.95:   4.039 ms/op
                 existUser·p0.99:   5.915 ms/op
                 existUser·p0.999:  18.160 ms/op
                 existUser·p0.9999: 20.782 ms/op
                 existUser·p1.00:   24.347 ms/op

Iteration   2: 3.101 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.624 ms/op
                 existUser·p0.50:   3.006 ms/op
                 existUser·p0.90:   3.387 ms/op
                 existUser·p0.95:   3.621 ms/op
                 existUser·p0.99:   5.423 ms/op
                 existUser·p0.999:  8.730 ms/op
                 existUser·p0.9999: 22.436 ms/op
                 existUser·p1.00:   23.200 ms/op

Iteration   3: 3.081 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.399 ms/op
                 existUser·p0.50:   3.006 ms/op
                 existUser·p0.90:   3.277 ms/op
                 existUser·p0.95:   3.502 ms/op
                 existUser·p0.99:   5.374 ms/op
                 existUser·p0.999:  9.072 ms/op
                 existUser·p0.9999: 21.791 ms/op
                 existUser·p1.00:   23.298 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 304612
  mean =      3.147 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15372 
    [ 2.500,  5.000) = 283916 
    [ 5.000,  7.500) = 4570 
    [ 7.500, 10.000) = 448 
    [10.000, 12.500) = 3 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 35 
    [17.500, 20.000) = 106 
    [20.000, 22.500) = 146 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.270 ms/op
     p(50.0000) =      3.076 ms/op
     p(90.0000) =      3.449 ms/op
     p(95.0000) =      3.748 ms/op
     p(99.0000) =      5.513 ms/op
     p(99.9000) =     10.533 ms/op
     p(99.9900) =     22.086 ms/op
     p(99.9990) =     23.200 ms/op
     p(99.9999) =     24.347 ms/op
    p(100.0000) =     24.347 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 9.415 ±(99.9%) 0.111 ms/op
# Warmup Iteration   2: 3.647 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.224 ±(99.9%) 0.009 ms/op
Iteration   1: 3.318 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.241 ms/op
                 getUser·p0.50:   3.195 ms/op
                 getUser·p0.90:   3.793 ms/op
                 getUser·p0.95:   4.514 ms/op
                 getUser·p0.99:   6.103 ms/op
                 getUser·p0.999:  14.752 ms/op
                 getUser·p0.9999: 19.219 ms/op
                 getUser·p1.00:   20.087 ms/op

Iteration   2: 3.293 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.395 ms/op
                 getUser·p0.50:   3.146 ms/op
                 getUser·p0.90:   3.801 ms/op
                 getUser·p0.95:   4.440 ms/op
                 getUser·p0.99:   5.628 ms/op
                 getUser·p0.999:  8.491 ms/op
                 getUser·p0.9999: 25.371 ms/op
                 getUser·p1.00:   26.280 ms/op

Iteration   3: 3.371 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.436 ms/op
                 getUser·p0.50:   3.248 ms/op
                 getUser·p0.90:   3.789 ms/op
                 getUser·p0.95:   4.637 ms/op
                 getUser·p0.99:   6.439 ms/op
                 getUser·p0.999:  14.270 ms/op
                 getUser·p0.9999: 25.004 ms/op
                 getUser·p1.00:   26.575 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 288529
  mean =      3.327 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12608 
    [ 2.500,  5.000) = 267197 
    [ 5.000,  7.500) = 7738 
    [ 7.500, 10.000) = 622 
    [10.000, 12.500) = 71 
    [12.500, 15.000) = 21 
    [15.000, 17.500) = 41 
    [17.500, 20.000) = 129 
    [20.000, 22.500) = 39 
    [22.500, 25.000) = 42 
    [25.000, 27.500) = 21 

  Percentiles, ms/op:
      p(0.0000) =      0.395 ms/op
     p(50.0000) =      3.203 ms/op
     p(90.0000) =      3.793 ms/op
     p(95.0000) =      4.522 ms/op
     p(99.0000) =      6.005 ms/op
     p(99.9000) =     14.145 ms/op
     p(99.9900) =     24.838 ms/op
     p(99.9990) =     26.077 ms/op
     p(99.9999) =     26.575 ms/op
    p(100.0000) =     26.575 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 8.328 ±(99.9%) 0.116 ms/op
# Warmup Iteration   2: 3.947 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.895 ±(99.9%) 0.012 ms/op
Iteration   1: 3.772 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.845 ms/op
                 listUser·p0.50:   3.629 ms/op
                 listUser·p0.90:   4.026 ms/op
                 listUser·p0.95:   4.301 ms/op
                 listUser·p0.99:   7.586 ms/op
                 listUser·p0.999:  15.652 ms/op
                 listUser·p0.9999: 24.642 ms/op
                 listUser·p1.00:   26.444 ms/op

Iteration   2: 3.872 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.423 ms/op
                 listUser·p0.50:   3.817 ms/op
                 listUser·p0.90:   4.219 ms/op
                 listUser·p0.95:   4.563 ms/op
                 listUser·p0.99:   6.652 ms/op
                 listUser·p0.999:  14.389 ms/op
                 listUser·p0.9999: 16.499 ms/op
                 listUser·p1.00:   16.499 ms/op

Iteration   3: 3.995 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.425 ms/op
                 listUser·p0.50:   3.834 ms/op
                 listUser·p0.90:   4.432 ms/op
                 listUser·p0.95:   5.243 ms/op
                 listUser·p0.99:   7.733 ms/op
                 listUser·p0.999:  15.450 ms/op
                 listUser·p0.9999: 18.547 ms/op
                 listUser·p1.00:   18.579 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 247674
  mean =      3.877 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 36 
    [ 2.500,  5.000) = 237772 
    [ 5.000,  7.500) = 7430 
    [ 7.500, 10.000) = 1657 
    [10.000, 12.500) = 266 
    [12.500, 15.000) = 285 
    [15.000, 17.500) = 135 
    [17.500, 20.000) = 56 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      1.423 ms/op
     p(50.0000) =      3.781 ms/op
     p(90.0000) =      4.252 ms/op
     p(95.0000) =      4.653 ms/op
     p(99.0000) =      7.471 ms/op
     p(99.9000) =     14.669 ms/op
     p(99.9900) =     23.863 ms/op
     p(99.9990) =     26.033 ms/op
     p(99.9999) =     26.444 ms/op
    p(100.0000) =     26.444 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.946 ± 1.551  ops/ms
ClientPb.existUser                       thrpt       3  10.264 ± 7.046  ops/ms
ClientPb.getUser                         thrpt       3  10.009 ± 3.779  ops/ms
ClientPb.listUser                        thrpt       3   8.496 ± 1.283  ops/ms
ClientPb.createUser                       avgt       3   3.192 ± 1.134   ms/op
ClientPb.existUser                        avgt       3   3.116 ± 1.103   ms/op
ClientPb.getUser                          avgt       3   3.209 ± 0.721   ms/op
ClientPb.listUser                         avgt       3   3.786 ± 0.498   ms/op
ClientPb.createUser                     sample  294328   3.261 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.782           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.199           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.572           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.141           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.571           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.334           ms/op
ClientPb.createUser:createUser·p0.9999  sample          22.118           ms/op
ClientPb.createUser:createUser·p1.00    sample          23.003           ms/op
ClientPb.existUser                      sample  304612   3.147 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.270           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.076           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.449           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.748           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.513           ms/op
ClientPb.existUser:existUser·p0.999     sample          10.533           ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.086           ms/op
ClientPb.existUser:existUser·p1.00      sample          24.347           ms/op
ClientPb.getUser                        sample  288529   3.327 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.395           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.203           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.793           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.522           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.005           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.145           ms/op
ClientPb.getUser:getUser·p0.9999        sample          24.838           ms/op
ClientPb.getUser:getUser·p1.00          sample          26.575           ms/op
ClientPb.listUser                       sample  247674   3.877 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.423           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.781           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.252           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.653           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.471           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.669           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.863           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.444           ms/op
