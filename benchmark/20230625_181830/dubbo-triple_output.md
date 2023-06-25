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
# Warmup Iteration   1: 2.402 ops/ms
# Warmup Iteration   2: 6.128 ops/ms
# Warmup Iteration   3: 9.081 ops/ms
Iteration   1: 9.526 ops/ms
Iteration   2: 9.935 ops/ms
Iteration   3: 9.560 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.674 ±(99.9%) 4.145 ops/ms [Average]
  (min, avg, max) = (9.526, 9.674, 9.935), stdev = 0.227
  CI (99.9%): [5.529, 13.819] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.735 ops/ms
# Warmup Iteration   2: 9.300 ops/ms
# Warmup Iteration   3: 10.600 ops/ms
Iteration   1: 10.688 ops/ms
Iteration   2: 10.694 ops/ms
Iteration   3: 9.944 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.442 ±(99.9%) 7.868 ops/ms [Average]
  (min, avg, max) = (9.944, 10.442, 10.694), stdev = 0.431
  CI (99.9%): [2.574, 18.310] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.933 ops/ms
# Warmup Iteration   2: 8.291 ops/ms
# Warmup Iteration   3: 9.546 ops/ms
Iteration   1: 10.348 ops/ms
Iteration   2: 10.109 ops/ms
Iteration   3: 9.622 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.026 ±(99.9%) 6.753 ops/ms [Average]
  (min, avg, max) = (9.622, 10.026, 10.348), stdev = 0.370
  CI (99.9%): [3.274, 16.779] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.420 ops/ms
# Warmup Iteration   2: 7.975 ops/ms
# Warmup Iteration   3: 8.380 ops/ms
Iteration   1: 8.709 ops/ms
Iteration   2: 8.602 ops/ms
Iteration   3: 8.423 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.578 ±(99.9%) 2.635 ops/ms [Average]
  (min, avg, max) = (8.423, 8.578, 8.709), stdev = 0.144
  CI (99.9%): [5.943, 11.213] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 9.104 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.580 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.208 ±(99.9%) 0.007 ms/op
Iteration   1: 3.220 ±(99.9%) 0.010 ms/op
Iteration   2: 3.156 ±(99.9%) 0.007 ms/op
Iteration   3: 3.288 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.222 ±(99.9%) 1.204 ms/op [Average]
  (min, avg, max) = (3.156, 3.222, 3.288), stdev = 0.066
  CI (99.9%): [2.017, 4.426] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 7.173 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.260 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.172 ±(99.9%) 0.007 ms/op
Iteration   1: 3.066 ±(99.9%) 0.009 ms/op
Iteration   2: 3.107 ±(99.9%) 0.002 ms/op
Iteration   3: 3.166 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.113 ±(99.9%) 0.913 ms/op [Average]
  (min, avg, max) = (3.066, 3.113, 3.166), stdev = 0.050
  CI (99.9%): [2.200, 4.026] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 7.081 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.391 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.220 ±(99.9%) 0.004 ms/op
Iteration   1: 3.416 ±(99.9%) 0.008 ms/op
Iteration   2: 3.248 ±(99.9%) 0.009 ms/op
Iteration   3: 3.086 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.250 ±(99.9%) 3.007 ms/op [Average]
  (min, avg, max) = (3.086, 3.250, 3.416), stdev = 0.165
  CI (99.9%): [0.243, 6.257] (assumes normal distribution)


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
# Warmup Iteration   1: 8.644 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.920 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.847 ±(99.9%) 0.003 ms/op
Iteration   1: 3.706 ±(99.9%) 0.013 ms/op
Iteration   2: 3.640 ±(99.9%) 0.011 ms/op
Iteration   3: 3.789 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.712 ±(99.9%) 1.366 ms/op [Average]
  (min, avg, max) = (3.640, 3.712, 3.789), stdev = 0.075
  CI (99.9%): [2.345, 5.078] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 7.629 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 3.746 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.134 ±(99.9%) 0.008 ms/op
Iteration   1: 3.211 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.260 ms/op
                 createUser·p0.50:   3.113 ms/op
                 createUser·p0.90:   3.592 ms/op
                 createUser·p0.95:   4.051 ms/op
                 createUser·p0.99:   5.874 ms/op
                 createUser·p0.999:  13.769 ms/op
                 createUser·p0.9999: 20.261 ms/op
                 createUser·p1.00:   21.070 ms/op

Iteration   2: 3.122 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.065 ms/op
                 createUser·p0.50:   3.006 ms/op
                 createUser·p0.90:   3.281 ms/op
                 createUser·p0.95:   3.592 ms/op
                 createUser·p0.99:   5.702 ms/op
                 createUser·p0.999:  19.844 ms/op
                 createUser·p0.9999: 23.282 ms/op
                 createUser·p1.00:   23.953 ms/op

Iteration   3: 3.340 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.982 ms/op
                 createUser·p0.50:   3.297 ms/op
                 createUser·p0.90:   3.781 ms/op
                 createUser·p0.95:   4.039 ms/op
                 createUser·p0.99:   5.571 ms/op
                 createUser·p0.999:  15.385 ms/op
                 createUser·p0.9999: 22.198 ms/op
                 createUser·p1.00:   22.413 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 297833
  mean =      3.222 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19715 
    [ 2.500,  5.000) = 271740 
    [ 5.000,  7.500) = 5498 
    [ 7.500, 10.000) = 428 
    [10.000, 12.500) = 48 
    [12.500, 15.000) = 70 
    [15.000, 17.500) = 57 
    [17.500, 20.000) = 144 
    [20.000, 22.500) = 110 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.982 ms/op
     p(50.0000) =      3.133 ms/op
     p(90.0000) =      3.613 ms/op
     p(95.0000) =      3.940 ms/op
     p(99.0000) =      5.677 ms/op
     p(99.9000) =     15.734 ms/op
     p(99.9900) =     22.315 ms/op
     p(99.9990) =     23.695 ms/op
     p(99.9999) =     23.953 ms/op
    p(100.0000) =     23.953 ms/op


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
# Warmup Iteration   1: 6.774 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 3.210 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.149 ±(99.9%) 0.008 ms/op
Iteration   1: 3.176 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.859 ms/op
                 existUser·p0.50:   3.170 ms/op
                 existUser·p0.90:   3.310 ms/op
                 existUser·p0.95:   3.838 ms/op
                 existUser·p0.99:   5.308 ms/op
                 existUser·p0.999:  12.585 ms/op
                 existUser·p0.9999: 20.117 ms/op
                 existUser·p1.00:   23.265 ms/op

Iteration   2: 3.260 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.257 ms/op
                 existUser·p0.50:   3.211 ms/op
                 existUser·p0.90:   3.699 ms/op
                 existUser·p0.95:   3.969 ms/op
                 existUser·p0.99:   5.480 ms/op
                 existUser·p0.999:  8.176 ms/op
                 existUser·p0.9999: 23.364 ms/op
                 existUser·p1.00:   23.921 ms/op

Iteration   3: 3.121 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.260 ms/op
                 existUser·p0.50:   3.080 ms/op
                 existUser·p0.90:   3.292 ms/op
                 existUser·p0.95:   3.953 ms/op
                 existUser·p0.99:   5.464 ms/op
                 existUser·p0.999:  8.585 ms/op
                 existUser·p0.9999: 23.643 ms/op
                 existUser·p1.00:   24.216 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 301106
  mean =      3.185 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 31920 
    [ 2.500,  5.000) = 262934 
    [ 5.000,  7.500) = 5664 
    [ 7.500, 10.000) = 298 
    [10.000, 12.500) = 29 
    [12.500, 15.000) = 24 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 101 
    [20.000, 22.500) = 74 
    [22.500, 25.000) = 49 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.859 ms/op
     p(50.0000) =      3.158 ms/op
     p(90.0000) =      3.482 ms/op
     p(95.0000) =      3.940 ms/op
     p(99.0000) =      5.423 ms/op
     p(99.9000) =      9.568 ms/op
     p(99.9900) =     23.262 ms/op
     p(99.9990) =     24.117 ms/op
     p(99.9999) =     24.216 ms/op
    p(100.0000) =     24.216 ms/op


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
# Warmup Iteration   1: 6.950 ±(99.9%) 0.093 ms/op
# Warmup Iteration   2: 3.332 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.194 ±(99.9%) 0.008 ms/op
Iteration   1: 3.196 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.546 ms/op
                 getUser·p0.50:   3.060 ms/op
                 getUser·p0.90:   3.523 ms/op
                 getUser·p0.95:   3.953 ms/op
                 getUser·p0.99:   6.234 ms/op
                 getUser·p0.999:  10.942 ms/op
                 getUser·p0.9999: 19.104 ms/op
                 getUser·p1.00:   19.923 ms/op

Iteration   2: 3.260 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.128 ms/op
                 getUser·p0.50:   3.138 ms/op
                 getUser·p0.90:   3.752 ms/op
                 getUser·p0.95:   3.994 ms/op
                 getUser·p0.99:   5.513 ms/op
                 getUser·p0.999:  9.053 ms/op
                 getUser·p0.9999: 23.302 ms/op
                 getUser·p1.00:   24.609 ms/op

Iteration   3: 3.168 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.522 ms/op
                 getUser·p0.50:   3.019 ms/op
                 getUser·p0.90:   3.490 ms/op
                 getUser·p0.95:   3.781 ms/op
                 getUser·p0.99:   5.915 ms/op
                 getUser·p0.999:  10.994 ms/op
                 getUser·p0.9999: 23.000 ms/op
                 getUser·p1.00:   23.691 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 299321
  mean =      3.207 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7485 
    [ 2.500,  5.000) = 283624 
    [ 5.000,  7.500) = 7487 
    [ 7.500, 10.000) = 399 
    [10.000, 12.500) = 35 
    [12.500, 15.000) = 10 
    [15.000, 17.500) = 75 
    [17.500, 20.000) = 89 
    [20.000, 22.500) = 78 
    [22.500, 25.000) = 39 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.128 ms/op
     p(50.0000) =      3.056 ms/op
     p(90.0000) =      3.609 ms/op
     p(95.0000) =      3.940 ms/op
     p(99.0000) =      5.915 ms/op
     p(99.9000) =     10.988 ms/op
     p(99.9900) =     22.872 ms/op
     p(99.9990) =     23.889 ms/op
     p(99.9999) =     24.609 ms/op
    p(100.0000) =     24.609 ms/op


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
# Warmup Iteration   1: 8.929 ±(99.9%) 0.109 ms/op
# Warmup Iteration   2: 4.055 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.724 ±(99.9%) 0.011 ms/op
Iteration   1: 3.822 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.265 ms/op
                 listUser·p0.50:   3.686 ms/op
                 listUser·p0.90:   4.182 ms/op
                 listUser·p0.95:   4.497 ms/op
                 listUser·p0.99:   7.455 ms/op
                 listUser·p0.999:  14.877 ms/op
                 listUser·p0.9999: 18.535 ms/op
                 listUser·p1.00:   19.169 ms/op

Iteration   2: 3.671 ±(99.9%) 0.007 ms/op
                 listUser·p0.00:   2.187 ms/op
                 listUser·p0.50:   3.580 ms/op
                 listUser·p0.90:   3.912 ms/op
                 listUser·p0.95:   4.121 ms/op
                 listUser·p0.99:   5.964 ms/op
                 listUser·p0.999:  12.976 ms/op
                 listUser·p0.9999: 13.779 ms/op
                 listUser·p1.00:   13.877 ms/op

Iteration   3: 3.721 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.318 ms/op
                 listUser·p0.50:   3.654 ms/op
                 listUser·p0.90:   3.973 ms/op
                 listUser·p0.95:   4.174 ms/op
                 listUser·p0.99:   6.757 ms/op
                 listUser·p0.999:  13.353 ms/op
                 listUser·p0.9999: 16.876 ms/op
                 listUser·p1.00:   18.776 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 256842
  mean =      3.737 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 20 
    [ 2.500,  3.750) = 184036 
    [ 3.750,  5.000) = 66439 
    [ 5.000,  6.250) = 1909 
    [ 6.250,  7.500) = 2645 
    [ 7.500,  8.750) = 860 
    [ 8.750, 10.000) = 192 
    [10.000, 11.250) = 165 
    [11.250, 12.500) = 140 
    [12.500, 13.750) = 221 
    [13.750, 15.000) = 106 
    [15.000, 16.250) = 37 
    [16.250, 17.500) = 30 
    [17.500, 18.750) = 39 

  Percentiles, ms/op:
      p(0.0000) =      2.187 ms/op
     p(50.0000) =      3.650 ms/op
     p(90.0000) =      4.043 ms/op
     p(95.0000) =      4.252 ms/op
     p(99.0000) =      6.857 ms/op
     p(99.9000) =     13.369 ms/op
     p(99.9900) =     18.164 ms/op
     p(99.9990) =     18.818 ms/op
     p(99.9999) =     19.169 ms/op
    p(100.0000) =     19.169 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.674 ± 4.145  ops/ms
ClientPb.existUser                       thrpt       3  10.442 ± 7.868  ops/ms
ClientPb.getUser                         thrpt       3  10.026 ± 6.753  ops/ms
ClientPb.listUser                        thrpt       3   8.578 ± 2.635  ops/ms
ClientPb.createUser                       avgt       3   3.222 ± 1.204   ms/op
ClientPb.existUser                        avgt       3   3.113 ± 0.913   ms/op
ClientPb.getUser                          avgt       3   3.250 ± 3.007   ms/op
ClientPb.listUser                         avgt       3   3.712 ± 1.366   ms/op
ClientPb.createUser                     sample  297833   3.222 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.982           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.133           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.613           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.940           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.677           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.734           ms/op
ClientPb.createUser:createUser·p0.9999  sample          22.315           ms/op
ClientPb.createUser:createUser·p1.00    sample          23.953           ms/op
ClientPb.existUser                      sample  301106   3.185 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.859           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.158           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.482           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.940           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.423           ms/op
ClientPb.existUser:existUser·p0.999     sample           9.568           ms/op
ClientPb.existUser:existUser·p0.9999    sample          23.262           ms/op
ClientPb.existUser:existUser·p1.00      sample          24.216           ms/op
ClientPb.getUser                        sample  299321   3.207 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.128           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.056           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.609           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.940           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.915           ms/op
ClientPb.getUser:getUser·p0.999         sample          10.988           ms/op
ClientPb.getUser:getUser·p0.9999        sample          22.872           ms/op
ClientPb.getUser:getUser·p1.00          sample          24.609           ms/op
ClientPb.listUser                       sample  256842   3.737 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.187           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.650           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.043           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.252           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.857           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.369           ms/op
ClientPb.listUser:listUser·p0.9999      sample          18.164           ms/op
ClientPb.listUser:listUser·p1.00        sample          19.169           ms/op
