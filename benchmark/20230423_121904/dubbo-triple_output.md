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
# Warmup Iteration   1: 2.738 ops/ms
# Warmup Iteration   2: 6.463 ops/ms
# Warmup Iteration   3: 8.984 ops/ms
Iteration   1: 9.878 ops/ms
Iteration   2: 9.872 ops/ms
Iteration   3: 9.757 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.836 ±(99.9%) 1.250 ops/ms [Average]
  (min, avg, max) = (9.757, 9.836, 9.878), stdev = 0.069
  CI (99.9%): [8.586, 11.086] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.703 ops/ms
# Warmup Iteration   2: 9.351 ops/ms
# Warmup Iteration   3: 10.341 ops/ms
Iteration   1: 10.455 ops/ms
Iteration   2: 10.814 ops/ms
Iteration   3: 10.437 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.568 ±(99.9%) 3.879 ops/ms [Average]
  (min, avg, max) = (10.437, 10.568, 10.814), stdev = 0.213
  CI (99.9%): [6.690, 14.447] (assumes normal distribution)


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
# Warmup Iteration   1: 3.674 ops/ms
# Warmup Iteration   2: 9.374 ops/ms
# Warmup Iteration   3: 9.680 ops/ms
Iteration   1: 9.797 ops/ms
Iteration   2: 10.018 ops/ms
Iteration   3: 9.830 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.882 ±(99.9%) 2.179 ops/ms [Average]
  (min, avg, max) = (9.797, 9.882, 10.018), stdev = 0.119
  CI (99.9%): [7.703, 12.061] (assumes normal distribution)


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
# Warmup Iteration   1: 3.076 ops/ms
# Warmup Iteration   2: 7.661 ops/ms
# Warmup Iteration   3: 8.415 ops/ms
Iteration   1: 8.657 ops/ms
Iteration   2: 8.715 ops/ms
Iteration   3: 8.510 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.627 ±(99.9%) 1.923 ops/ms [Average]
  (min, avg, max) = (8.510, 8.627, 8.715), stdev = 0.105
  CI (99.9%): [6.705, 10.550] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 8.526 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.578 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.342 ±(99.9%) 0.006 ms/op
Iteration   1: 3.350 ±(99.9%) 0.005 ms/op
Iteration   2: 3.215 ±(99.9%) 0.002 ms/op
Iteration   3: 3.278 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.281 ±(99.9%) 1.236 ms/op [Average]
  (min, avg, max) = (3.215, 3.281, 3.350), stdev = 0.068
  CI (99.9%): [2.045, 4.517] (assumes normal distribution)


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
# Warmup Iteration   1: 7.367 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.342 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.172 ±(99.9%) 0.004 ms/op
Iteration   1: 2.987 ±(99.9%) 0.005 ms/op
Iteration   2: 3.071 ±(99.9%) 0.003 ms/op
Iteration   3: 3.118 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.058 ±(99.9%) 1.212 ms/op [Average]
  (min, avg, max) = (2.987, 3.058, 3.118), stdev = 0.066
  CI (99.9%): [1.847, 4.270] (assumes normal distribution)


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
# Warmup Iteration   1: 7.310 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.380 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.243 ±(99.9%) 0.003 ms/op
Iteration   1: 3.265 ±(99.9%) 0.005 ms/op
Iteration   2: 3.122 ±(99.9%) 0.006 ms/op
Iteration   3: 3.111 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.166 ±(99.9%) 1.570 ms/op [Average]
  (min, avg, max) = (3.111, 3.166, 3.265), stdev = 0.086
  CI (99.9%): [1.597, 4.736] (assumes normal distribution)


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
# Warmup Iteration   1: 8.920 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.105 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.756 ±(99.9%) 0.008 ms/op
Iteration   1: 3.717 ±(99.9%) 0.006 ms/op
Iteration   2: 3.662 ±(99.9%) 0.011 ms/op
Iteration   3: 3.713 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.697 ±(99.9%) 0.561 ms/op [Average]
  (min, avg, max) = (3.662, 3.697, 3.717), stdev = 0.031
  CI (99.9%): [3.136, 4.259] (assumes normal distribution)


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
# Warmup Iteration   1: 7.845 ±(99.9%) 0.084 ms/op
# Warmup Iteration   2: 3.646 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.171 ±(99.9%) 0.008 ms/op
Iteration   1: 3.108 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.384 ms/op
                 createUser·p0.50:   3.052 ms/op
                 createUser·p0.90:   3.330 ms/op
                 createUser·p0.95:   3.621 ms/op
                 createUser·p0.99:   5.210 ms/op
                 createUser·p0.999:  11.685 ms/op
                 createUser·p0.9999: 19.848 ms/op
                 createUser·p1.00:   20.251 ms/op

Iteration   2: 3.140 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.910 ms/op
                 createUser·p0.50:   3.027 ms/op
                 createUser·p0.90:   3.482 ms/op
                 createUser·p0.95:   3.756 ms/op
                 createUser·p0.99:   5.407 ms/op
                 createUser·p0.999:  10.648 ms/op
                 createUser·p0.9999: 23.046 ms/op
                 createUser·p1.00:   24.150 ms/op

Iteration   3: 3.241 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.536 ms/op
                 createUser·p0.50:   3.191 ms/op
                 createUser·p0.90:   3.682 ms/op
                 createUser·p0.95:   3.957 ms/op
                 createUser·p0.99:   5.620 ms/op
                 createUser·p0.999:  13.865 ms/op
                 createUser·p0.9999: 20.873 ms/op
                 createUser·p1.00:   23.265 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 303403
  mean =      3.162 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18960 
    [ 2.500,  5.000) = 279902 
    [ 5.000,  7.500) = 3737 
    [ 7.500, 10.000) = 414 
    [10.000, 12.500) = 68 
    [12.500, 15.000) = 55 
    [15.000, 17.500) = 11 
    [17.500, 20.000) = 166 
    [20.000, 22.500) = 62 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.536 ms/op
     p(50.0000) =      3.105 ms/op
     p(90.0000) =      3.498 ms/op
     p(95.0000) =      3.826 ms/op
     p(99.0000) =      5.407 ms/op
     p(99.9000) =     13.844 ms/op
     p(99.9900) =     22.435 ms/op
     p(99.9990) =     23.622 ms/op
     p(99.9999) =     24.150 ms/op
    p(100.0000) =     24.150 ms/op


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
# Warmup Iteration   1: 7.691 ±(99.9%) 0.103 ms/op
# Warmup Iteration   2: 3.388 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.118 ±(99.9%) 0.007 ms/op
Iteration   1: 3.077 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.260 ms/op
                 existUser·p0.50:   3.060 ms/op
                 existUser·p0.90:   3.367 ms/op
                 existUser·p0.95:   3.752 ms/op
                 existUser·p0.99:   5.136 ms/op
                 existUser·p0.999:  10.535 ms/op
                 existUser·p0.9999: 22.748 ms/op
                 existUser·p1.00:   24.019 ms/op

Iteration   2: 3.179 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.161 ms/op
                 existUser·p0.50:   3.121 ms/op
                 existUser·p0.90:   3.629 ms/op
                 existUser·p0.95:   3.985 ms/op
                 existUser·p0.99:   5.661 ms/op
                 existUser·p0.999:  14.408 ms/op
                 existUser·p0.9999: 18.249 ms/op
                 existUser·p1.00:   19.169 ms/op

Iteration   3: 3.111 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.085 ms/op
                 existUser·p0.50:   3.035 ms/op
                 existUser·p0.90:   3.375 ms/op
                 existUser·p0.95:   4.096 ms/op
                 existUser·p0.99:   5.505 ms/op
                 existUser·p0.999:  10.785 ms/op
                 existUser·p0.9999: 22.470 ms/op
                 existUser·p1.00:   23.560 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 307471
  mean =      3.122 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18498 
    [ 2.500,  5.000) = 283413 
    [ 5.000,  7.500) = 4799 
    [ 7.500, 10.000) = 432 
    [10.000, 12.500) = 33 
    [12.500, 15.000) = 29 
    [15.000, 17.500) = 145 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 53 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.085 ms/op
     p(50.0000) =      3.064 ms/op
     p(90.0000) =      3.478 ms/op
     p(95.0000) =      3.920 ms/op
     p(99.0000) =      5.480 ms/op
     p(99.9000) =     10.781 ms/op
     p(99.9900) =     22.446 ms/op
     p(99.9990) =     23.550 ms/op
     p(99.9999) =     24.019 ms/op
    p(100.0000) =     24.019 ms/op


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
# Warmup Iteration   1: 8.200 ±(99.9%) 0.089 ms/op
# Warmup Iteration   2: 3.375 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.290 ±(99.9%) 0.009 ms/op
Iteration   1: 3.162 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.130 ms/op
                 getUser·p0.50:   3.019 ms/op
                 getUser·p0.90:   3.428 ms/op
                 getUser·p0.95:   3.662 ms/op
                 getUser·p0.99:   5.908 ms/op
                 getUser·p0.999:  16.295 ms/op
                 getUser·p0.9999: 19.923 ms/op
                 getUser·p1.00:   20.808 ms/op

Iteration   2: 3.203 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.947 ms/op
                 getUser·p0.50:   3.105 ms/op
                 getUser·p0.90:   3.641 ms/op
                 getUser·p0.95:   3.985 ms/op
                 getUser·p0.99:   5.497 ms/op
                 getUser·p0.999:  15.000 ms/op
                 getUser·p0.9999: 23.167 ms/op
                 getUser·p1.00:   23.691 ms/op

Iteration   3: 3.218 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.959 ms/op
                 getUser·p0.50:   3.097 ms/op
                 getUser·p0.90:   3.625 ms/op
                 getUser·p0.95:   4.084 ms/op
                 getUser·p0.99:   5.775 ms/op
                 getUser·p0.999:  11.305 ms/op
                 getUser·p0.9999: 28.740 ms/op
                 getUser·p1.00:   29.721 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 300317
  mean =      3.194 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13634 
    [ 2.500,  5.000) = 278700 
    [ 5.000,  7.500) = 6954 
    [ 7.500, 10.000) = 619 
    [10.000, 12.500) = 65 
    [12.500, 15.000) = 34 
    [15.000, 17.500) = 45 
    [17.500, 20.000) = 131 
    [20.000, 22.500) = 68 
    [22.500, 25.000) = 35 
    [25.000, 27.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      0.947 ms/op
     p(50.0000) =      3.080 ms/op
     p(90.0000) =      3.572 ms/op
     p(95.0000) =      3.981 ms/op
     p(99.0000) =      5.700 ms/op
     p(99.9000) =     15.805 ms/op
     p(99.9900) =     26.639 ms/op
     p(99.9990) =     29.589 ms/op
     p(99.9999) =     29.721 ms/op
    p(100.0000) =     29.721 ms/op


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
# Warmup Iteration   1: 9.583 ±(99.9%) 0.113 ms/op
# Warmup Iteration   2: 4.072 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.900 ±(99.9%) 0.012 ms/op
Iteration   1: 3.781 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.278 ms/op
                 listUser·p0.50:   3.650 ms/op
                 listUser·p0.90:   4.018 ms/op
                 listUser·p0.95:   4.817 ms/op
                 listUser·p0.99:   7.152 ms/op
                 listUser·p0.999:  15.319 ms/op
                 listUser·p0.9999: 19.484 ms/op
                 listUser·p1.00:   21.266 ms/op

Iteration   2: 3.651 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.146 ms/op
                 listUser·p0.50:   3.576 ms/op
                 listUser·p0.90:   3.895 ms/op
                 listUser·p0.95:   4.096 ms/op
                 listUser·p0.99:   6.685 ms/op
                 listUser·p0.999:  13.294 ms/op
                 listUser·p0.9999: 17.847 ms/op
                 listUser·p1.00:   18.252 ms/op

Iteration   3: 3.739 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.265 ms/op
                 listUser·p0.50:   3.576 ms/op
                 listUser·p0.90:   4.051 ms/op
                 listUser·p0.95:   4.317 ms/op
                 listUser·p0.99:   7.217 ms/op
                 listUser·p0.999:  13.402 ms/op
                 listUser·p0.9999: 15.809 ms/op
                 listUser·p1.00:   15.958 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 257841
  mean =      3.723 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 58 
    [ 2.500,  5.000) = 249206 
    [ 5.000,  7.500) = 6757 
    [ 7.500, 10.000) = 1213 
    [10.000, 12.500) = 170 
    [12.500, 15.000) = 294 
    [15.000, 17.500) = 88 
    [17.500, 20.000) = 50 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.278 ms/op
     p(50.0000) =      3.600 ms/op
     p(90.0000) =      3.998 ms/op
     p(95.0000) =      4.268 ms/op
     p(99.0000) =      7.021 ms/op
     p(99.9000) =     13.861 ms/op
     p(99.9900) =     18.484 ms/op
     p(99.9990) =     20.211 ms/op
     p(99.9999) =     21.266 ms/op
    p(100.0000) =     21.266 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.836 ± 1.250  ops/ms
ClientPb.existUser                       thrpt       3  10.568 ± 3.879  ops/ms
ClientPb.getUser                         thrpt       3   9.882 ± 2.179  ops/ms
ClientPb.listUser                        thrpt       3   8.627 ± 1.923  ops/ms
ClientPb.createUser                       avgt       3   3.281 ± 1.236   ms/op
ClientPb.existUser                        avgt       3   3.058 ± 1.212   ms/op
ClientPb.getUser                          avgt       3   3.166 ± 1.570   ms/op
ClientPb.listUser                         avgt       3   3.697 ± 0.561   ms/op
ClientPb.createUser                     sample  303403   3.162 ± 0.004   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.536           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.105           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.498           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.826           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.407           ms/op
ClientPb.createUser:createUser·p0.999   sample          13.844           ms/op
ClientPb.createUser:createUser·p0.9999  sample          22.435           ms/op
ClientPb.createUser:createUser·p1.00    sample          24.150           ms/op
ClientPb.existUser                      sample  307471   3.122 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.085           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.064           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.478           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.920           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.480           ms/op
ClientPb.existUser:existUser·p0.999     sample          10.781           ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.446           ms/op
ClientPb.existUser:existUser·p1.00      sample          24.019           ms/op
ClientPb.getUser                        sample  300317   3.194 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.947           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.080           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.572           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.981           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.700           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.805           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.639           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.721           ms/op
ClientPb.listUser                       sample  257841   3.723 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.278           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.600           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.998           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.268           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.021           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.861           ms/op
ClientPb.listUser:listUser·p0.9999      sample          18.484           ms/op
ClientPb.listUser:listUser·p1.00        sample          21.266           ms/op
