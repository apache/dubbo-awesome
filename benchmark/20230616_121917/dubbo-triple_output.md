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
# Warmup Iteration   1: 2.359 ops/ms
# Warmup Iteration   2: 5.651 ops/ms
# Warmup Iteration   3: 9.658 ops/ms
Iteration   1: 9.989 ops/ms
Iteration   2: 9.668 ops/ms
Iteration   3: 10.342 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.999 ±(99.9%) 6.146 ops/ms [Average]
  (min, avg, max) = (9.668, 9.999, 10.342), stdev = 0.337
  CI (99.9%): [3.853, 16.146] (assumes normal distribution)


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
# Warmup Iteration   1: 3.817 ops/ms
# Warmup Iteration   2: 9.511 ops/ms
# Warmup Iteration   3: 10.256 ops/ms
Iteration   1: 10.605 ops/ms
Iteration   2: 10.756 ops/ms
Iteration   3: 10.409 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.590 ±(99.9%) 3.175 ops/ms [Average]
  (min, avg, max) = (10.409, 10.590, 10.756), stdev = 0.174
  CI (99.9%): [7.415, 13.765] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.148 ops/ms
# Warmup Iteration   2: 9.004 ops/ms
# Warmup Iteration   3: 9.838 ops/ms
Iteration   1: 9.777 ops/ms
Iteration   2: 9.728 ops/ms
Iteration   3: 9.955 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.820 ±(99.9%) 2.171 ops/ms [Average]
  (min, avg, max) = (9.728, 9.820, 9.955), stdev = 0.119
  CI (99.9%): [7.650, 11.991] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.204 ops/ms
# Warmup Iteration   2: 7.760 ops/ms
# Warmup Iteration   3: 8.303 ops/ms
Iteration   1: 8.463 ops/ms
Iteration   2: 8.355 ops/ms
Iteration   3: 8.539 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.452 ±(99.9%) 1.692 ops/ms [Average]
  (min, avg, max) = (8.355, 8.452, 8.539), stdev = 0.093
  CI (99.9%): [6.761, 10.144] (assumes normal distribution)


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
# Warmup Iteration   1: 8.444 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.565 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.372 ±(99.9%) 0.003 ms/op
Iteration   1: 3.182 ±(99.9%) 0.008 ms/op
Iteration   2: 3.268 ±(99.9%) 0.009 ms/op
Iteration   3: 3.068 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.172 ±(99.9%) 1.828 ms/op [Average]
  (min, avg, max) = (3.068, 3.172, 3.268), stdev = 0.100
  CI (99.9%): [1.344, 5.001] (assumes normal distribution)


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
# Warmup Iteration   1: 7.240 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.231 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.152 ±(99.9%) 0.003 ms/op
Iteration   1: 3.075 ±(99.9%) 0.004 ms/op
Iteration   2: 3.202 ±(99.9%) 0.008 ms/op
Iteration   3: 3.203 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.160 ±(99.9%) 1.350 ms/op [Average]
  (min, avg, max) = (3.075, 3.160, 3.203), stdev = 0.074
  CI (99.9%): [1.810, 4.510] (assumes normal distribution)


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
# Warmup Iteration   1: 7.566 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.396 ±(99.9%) 0.001 ms/op
# Warmup Iteration   3: 3.285 ±(99.9%) 0.002 ms/op
Iteration   1: 3.172 ±(99.9%) 0.008 ms/op
Iteration   2: 3.234 ±(99.9%) 0.007 ms/op
Iteration   3: 3.272 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.226 ±(99.9%) 0.922 ms/op [Average]
  (min, avg, max) = (3.172, 3.226, 3.272), stdev = 0.051
  CI (99.9%): [2.304, 4.148] (assumes normal distribution)


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
# Warmup Iteration   1: 9.674 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 4.040 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.933 ±(99.9%) 0.006 ms/op
Iteration   1: 3.782 ±(99.9%) 0.007 ms/op
Iteration   2: 3.855 ±(99.9%) 0.005 ms/op
Iteration   3: 3.751 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.796 ±(99.9%) 0.975 ms/op [Average]
  (min, avg, max) = (3.751, 3.796, 3.855), stdev = 0.053
  CI (99.9%): [2.821, 4.770] (assumes normal distribution)


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
# Warmup Iteration   1: 7.818 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 3.756 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.263 ±(99.9%) 0.010 ms/op
Iteration   1: 3.405 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.251 ms/op
                 createUser·p0.50:   3.232 ms/op
                 createUser·p0.90:   4.092 ms/op
                 createUser·p0.95:   4.571 ms/op
                 createUser·p0.99:   5.700 ms/op
                 createUser·p0.999:  17.471 ms/op
                 createUser·p0.9999: 20.808 ms/op
                 createUser·p1.00:   21.856 ms/op

Iteration   2: 3.233 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.905 ms/op
                 createUser·p0.50:   3.080 ms/op
                 createUser·p0.90:   3.682 ms/op
                 createUser·p0.95:   4.076 ms/op
                 createUser·p0.99:   5.792 ms/op
                 createUser·p0.999:  19.104 ms/op
                 createUser·p0.9999: 27.698 ms/op
                 createUser·p1.00:   28.639 ms/op

Iteration   3: 3.250 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.268 ms/op
                 createUser·p0.50:   3.113 ms/op
                 createUser·p0.90:   3.686 ms/op
                 createUser·p0.95:   3.940 ms/op
                 createUser·p0.99:   5.595 ms/op
                 createUser·p0.999:  15.445 ms/op
                 createUser·p0.9999: 25.284 ms/op
                 createUser·p1.00:   26.673 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 291313
  mean =      3.294 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7584 
    [ 2.500,  5.000) = 276795 
    [ 5.000,  7.500) = 6064 
    [ 7.500, 10.000) = 437 
    [10.000, 12.500) = 71 
    [12.500, 15.000) = 35 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 100 
    [20.000, 22.500) = 96 
    [22.500, 25.000) = 58 
    [25.000, 27.500) = 35 

  Percentiles, ms/op:
      p(0.0000) =      0.905 ms/op
     p(50.0000) =      3.146 ms/op
     p(90.0000) =      3.822 ms/op
     p(95.0000) =      4.260 ms/op
     p(99.0000) =      5.652 ms/op
     p(99.9000) =     18.286 ms/op
     p(99.9900) =     26.800 ms/op
     p(99.9990) =     28.481 ms/op
     p(99.9999) =     28.639 ms/op
    p(100.0000) =     28.639 ms/op


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
# Warmup Iteration   1: 7.399 ±(99.9%) 0.086 ms/op
# Warmup Iteration   2: 3.330 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.118 ±(99.9%) 0.008 ms/op
Iteration   1: 3.178 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.257 ms/op
                 existUser·p0.50:   2.986 ms/op
                 existUser·p0.90:   3.871 ms/op
                 existUser·p0.95:   4.166 ms/op
                 existUser·p0.99:   5.148 ms/op
                 existUser·p0.999:  8.102 ms/op
                 existUser·p0.9999: 20.702 ms/op
                 existUser·p1.00:   21.692 ms/op

Iteration   2: 3.043 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.288 ms/op
                 existUser·p0.50:   3.039 ms/op
                 existUser·p0.90:   3.150 ms/op
                 existUser·p0.95:   3.219 ms/op
                 existUser·p0.99:   5.505 ms/op
                 existUser·p0.999:  12.436 ms/op
                 existUser·p0.9999: 23.822 ms/op
                 existUser·p1.00:   25.002 ms/op

Iteration   3: 3.184 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.202 ms/op
                 existUser·p0.50:   3.117 ms/op
                 existUser·p0.90:   3.625 ms/op
                 existUser·p0.95:   4.157 ms/op
                 existUser·p0.99:   5.284 ms/op
                 existUser·p0.999:  9.198 ms/op
                 existUser·p0.9999: 25.623 ms/op
                 existUser·p1.00:   26.313 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 306161
  mean =      3.134 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20170 
    [ 2.500,  5.000) = 281200 
    [ 5.000,  7.500) = 4258 
    [ 7.500, 10.000) = 215 
    [10.000, 12.500) = 22 
    [12.500, 15.000) = 18 
    [15.000, 17.500) = 52 
    [17.500, 20.000) = 79 
    [20.000, 22.500) = 92 
    [22.500, 25.000) = 38 
    [25.000, 27.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      1.202 ms/op
     p(50.0000) =      3.056 ms/op
     p(90.0000) =      3.555 ms/op
     p(95.0000) =      4.055 ms/op
     p(99.0000) =      5.292 ms/op
     p(99.9000) =     11.215 ms/op
     p(99.9900) =     24.241 ms/op
     p(99.9990) =     25.854 ms/op
     p(99.9999) =     26.313 ms/op
    p(100.0000) =     26.313 ms/op


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
# Warmup Iteration   1: 8.855 ±(99.9%) 0.103 ms/op
# Warmup Iteration   2: 3.497 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.467 ±(99.9%) 0.011 ms/op
Iteration   1: 3.174 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.151 ms/op
                 getUser·p0.50:   3.113 ms/op
                 getUser·p0.90:   3.523 ms/op
                 getUser·p0.95:   3.772 ms/op
                 getUser·p0.99:   5.603 ms/op
                 getUser·p0.999:  17.831 ms/op
                 getUser·p0.9999: 26.630 ms/op
                 getUser·p1.00:   26.771 ms/op

Iteration   2: 3.194 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.268 ms/op
                 getUser·p0.50:   3.138 ms/op
                 getUser·p0.90:   3.559 ms/op
                 getUser·p0.95:   3.801 ms/op
                 getUser·p0.99:   5.489 ms/op
                 getUser·p0.999:  10.666 ms/op
                 getUser·p0.9999: 25.100 ms/op
                 getUser·p1.00:   26.247 ms/op

Iteration   3: 3.201 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.421 ms/op
                 getUser·p0.50:   3.092 ms/op
                 getUser·p0.90:   3.502 ms/op
                 getUser·p0.95:   3.826 ms/op
                 getUser·p0.99:   5.956 ms/op
                 getUser·p0.999:  11.270 ms/op
                 getUser·p0.9999: 27.627 ms/op
                 getUser·p1.00:   28.508 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 300628
  mean =      3.190 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15065 
    [ 2.500,  5.000) = 280494 
    [ 5.000,  7.500) = 4285 
    [ 7.500, 10.000) = 408 
    [10.000, 12.500) = 42 
    [12.500, 15.000) = 13 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 108 
    [20.000, 22.500) = 82 
    [22.500, 25.000) = 45 
    [25.000, 27.500) = 48 

  Percentiles, ms/op:
      p(0.0000) =      1.151 ms/op
     p(50.0000) =      3.113 ms/op
     p(90.0000) =      3.531 ms/op
     p(95.0000) =      3.797 ms/op
     p(99.0000) =      5.661 ms/op
     p(99.9000) =     17.334 ms/op
     p(99.9900) =     26.640 ms/op
     p(99.9990) =     28.049 ms/op
     p(99.9999) =     28.508 ms/op
    p(100.0000) =     28.508 ms/op


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
# Warmup Iteration   1: 10.107 ±(99.9%) 0.124 ms/op
# Warmup Iteration   2: 4.086 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.760 ±(99.9%) 0.011 ms/op
Iteration   1: 3.749 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.175 ms/op
                 listUser·p0.50:   3.596 ms/op
                 listUser·p0.90:   4.100 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   6.816 ms/op
                 listUser·p0.999:  16.498 ms/op
                 listUser·p0.9999: 22.273 ms/op
                 listUser·p1.00:   22.905 ms/op

Iteration   2: 3.777 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.265 ms/op
                 listUser·p0.50:   3.658 ms/op
                 listUser·p0.90:   4.252 ms/op
                 listUser·p0.95:   4.596 ms/op
                 listUser·p0.99:   6.955 ms/op
                 listUser·p0.999:  14.342 ms/op
                 listUser·p0.9999: 15.017 ms/op
                 listUser·p1.00:   15.204 ms/op

Iteration   3: 3.673 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.485 ms/op
                 listUser·p0.50:   3.609 ms/op
                 listUser·p0.90:   3.789 ms/op
                 listUser·p0.95:   4.153 ms/op
                 listUser·p0.99:   6.627 ms/op
                 listUser·p0.999:  14.189 ms/op
                 listUser·p0.9999: 16.302 ms/op
                 listUser·p1.00:   16.351 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 257070
  mean =      3.732 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 69 
    [ 2.500,  5.000) = 249071 
    [ 5.000,  7.500) = 6193 
    [ 7.500, 10.000) = 995 
    [10.000, 12.500) = 140 
    [12.500, 15.000) = 444 
    [15.000, 17.500) = 86 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 54 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.485 ms/op
     p(50.0000) =      3.625 ms/op
     p(90.0000) =      4.084 ms/op
     p(95.0000) =      4.415 ms/op
     p(99.0000) =      6.818 ms/op
     p(99.9000) =     14.434 ms/op
     p(99.9900) =     21.220 ms/op
     p(99.9990) =     22.685 ms/op
     p(99.9999) =     22.905 ms/op
    p(100.0000) =     22.905 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.999 ± 6.146  ops/ms
ClientPb.existUser                       thrpt       3  10.590 ± 3.175  ops/ms
ClientPb.getUser                         thrpt       3   9.820 ± 2.171  ops/ms
ClientPb.listUser                        thrpt       3   8.452 ± 1.692  ops/ms
ClientPb.createUser                       avgt       3   3.172 ± 1.828   ms/op
ClientPb.existUser                        avgt       3   3.160 ± 1.350   ms/op
ClientPb.getUser                          avgt       3   3.226 ± 0.922   ms/op
ClientPb.listUser                         avgt       3   3.796 ± 0.975   ms/op
ClientPb.createUser                     sample  291313   3.294 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.905           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.146           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.822           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.260           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.652           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.286           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.800           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.639           ms/op
ClientPb.existUser                      sample  306161   3.134 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.202           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.056           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.555           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.055           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.292           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.215           ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.241           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.313           ms/op
ClientPb.getUser                        sample  300628   3.190 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.151           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.113           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.531           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.797           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.661           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.334           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.640           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.508           ms/op
ClientPb.listUser                       sample  257070   3.732 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.485           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.625           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.084           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.415           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.818           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.434           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.220           ms/op
ClientPb.listUser:listUser·p1.00        sample          22.905           ms/op
