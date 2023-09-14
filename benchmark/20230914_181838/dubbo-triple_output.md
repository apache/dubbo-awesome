# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.618 ops/ms
# Warmup Iteration   2: 5.868 ops/ms
# Warmup Iteration   3: 9.087 ops/ms
Iteration   1: 9.504 ops/ms
Iteration   2: 9.639 ops/ms
Iteration   3: 9.718 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.620 ±(99.9%) 1.971 ops/ms [Average]
  (min, avg, max) = (9.504, 9.620, 9.718), stdev = 0.108
  CI (99.9%): [7.649, 11.591] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.294 ops/ms
# Warmup Iteration   2: 8.951 ops/ms
# Warmup Iteration   3: 9.754 ops/ms
Iteration   1: 10.299 ops/ms
Iteration   2: 10.276 ops/ms
Iteration   3: 10.079 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.218 ±(99.9%) 2.206 ops/ms [Average]
  (min, avg, max) = (10.079, 10.218, 10.299), stdev = 0.121
  CI (99.9%): [8.012, 12.423] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 3.259 ops/ms
# Warmup Iteration   2: 8.687 ops/ms
# Warmup Iteration   3: 9.861 ops/ms
Iteration   1: 9.587 ops/ms
Iteration   2: 9.878 ops/ms
Iteration   3: 9.774 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.746 ±(99.9%) 2.689 ops/ms [Average]
  (min, avg, max) = (9.587, 9.746, 9.878), stdev = 0.147
  CI (99.9%): [7.057, 12.435] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 3.294 ops/ms
# Warmup Iteration   2: 7.516 ops/ms
# Warmup Iteration   3: 7.905 ops/ms
Iteration   1: 8.264 ops/ms
Iteration   2: 8.344 ops/ms
Iteration   3: 8.244 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.284 ±(99.9%) 0.972 ops/ms [Average]
  (min, avg, max) = (8.244, 8.284, 8.344), stdev = 0.053
  CI (99.9%): [7.312, 9.256] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 8.870 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.661 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.388 ±(99.9%) 0.003 ms/op
Iteration   1: 3.481 ±(99.9%) 0.003 ms/op
Iteration   2: 3.189 ±(99.9%) 0.003 ms/op
Iteration   3: 3.239 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.303 ±(99.9%) 2.850 ms/op [Average]
  (min, avg, max) = (3.189, 3.303, 3.481), stdev = 0.156
  CI (99.9%): [0.453, 6.153] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 7.700 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.371 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.172 ±(99.9%) 0.003 ms/op
Iteration   1: 3.153 ±(99.9%) 0.003 ms/op
Iteration   2: 3.199 ±(99.9%) 0.003 ms/op
Iteration   3: 3.140 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.164 ±(99.9%) 0.562 ms/op [Average]
  (min, avg, max) = (3.140, 3.164, 3.199), stdev = 0.031
  CI (99.9%): [2.602, 3.726] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 7.941 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.440 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.305 ±(99.9%) 0.003 ms/op
Iteration   1: 3.250 ±(99.9%) 0.004 ms/op
Iteration   2: 3.294 ±(99.9%) 0.002 ms/op
Iteration   3: 3.308 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.284 ±(99.9%) 0.554 ms/op [Average]
  (min, avg, max) = (3.250, 3.284, 3.308), stdev = 0.030
  CI (99.9%): [2.730, 3.838] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 9.884 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 4.090 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.930 ±(99.9%) 0.004 ms/op
Iteration   1: 3.971 ±(99.9%) 0.004 ms/op
Iteration   2: 3.847 ±(99.9%) 0.003 ms/op
Iteration   3: 3.856 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.891 ±(99.9%) 1.254 ms/op [Average]
  (min, avg, max) = (3.847, 3.891, 3.971), stdev = 0.069
  CI (99.9%): [2.637, 5.145] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 7.874 ±(99.9%) 0.093 ms/op
# Warmup Iteration   2: 3.740 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.302 ±(99.9%) 0.009 ms/op
Iteration   1: 3.309 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.940 ms/op
                 createUser·p0.50:   3.232 ms/op
                 createUser·p0.90:   3.731 ms/op
                 createUser·p0.95:   4.047 ms/op
                 createUser·p0.99:   5.677 ms/op
                 createUser·p0.999:  18.983 ms/op
                 createUser·p0.9999: 21.004 ms/op
                 createUser·p1.00:   21.823 ms/op

Iteration   2: 3.297 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.319 ms/op
                 createUser·p0.50:   3.219 ms/op
                 createUser·p0.90:   3.707 ms/op
                 createUser·p0.95:   3.981 ms/op
                 createUser·p0.99:   5.571 ms/op
                 createUser·p0.999:  13.304 ms/op
                 createUser·p0.9999: 23.167 ms/op
                 createUser·p1.00:   23.953 ms/op

Iteration   3: 3.346 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.305 ms/op
                 createUser·p0.50:   3.260 ms/op
                 createUser·p0.90:   3.785 ms/op
                 createUser·p0.95:   4.030 ms/op
                 createUser·p0.99:   5.538 ms/op
                 createUser·p0.999:  17.381 ms/op
                 createUser·p0.9999: 30.522 ms/op
                 createUser·p1.00:   31.162 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 289252
  mean =      3.317 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11353 
    [ 2.500,  5.000) = 273343 
    [ 5.000,  7.500) = 3324 
    [ 7.500, 10.000) = 534 
    [10.000, 12.500) = 289 
    [12.500, 15.000) = 19 
    [15.000, 17.500) = 76 
    [17.500, 20.000) = 153 
    [20.000, 22.500) = 104 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 2 
    [27.500, 30.000) = 10 
    [30.000, 32.500) = 20 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.940 ms/op
     p(50.0000) =      3.236 ms/op
     p(90.0000) =      3.744 ms/op
     p(95.0000) =      4.018 ms/op
     p(99.0000) =      5.612 ms/op
     p(99.9000) =     18.055 ms/op
     p(99.9900) =     29.529 ms/op
     p(99.9990) =     30.907 ms/op
     p(99.9999) =     31.162 ms/op
    p(100.0000) =     31.162 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.259 ±(99.9%) 0.084 ms/op
# Warmup Iteration   2: 3.364 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.181 ±(99.9%) 0.008 ms/op
Iteration   1: 3.202 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.497 ms/op
                 existUser·p0.50:   3.146 ms/op
                 existUser·p0.90:   3.527 ms/op
                 existUser·p0.95:   3.817 ms/op
                 existUser·p0.99:   5.620 ms/op
                 existUser·p0.999:  13.610 ms/op
                 existUser·p0.9999: 20.286 ms/op
                 existUser·p1.00:   21.758 ms/op

Iteration   2: 3.170 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.149 ms/op
                 existUser·p0.50:   3.142 ms/op
                 existUser·p0.90:   3.432 ms/op
                 existUser·p0.95:   3.641 ms/op
                 existUser·p0.99:   5.176 ms/op
                 existUser·p0.999:  12.109 ms/op
                 existUser·p0.9999: 23.164 ms/op
                 existUser·p1.00:   24.150 ms/op

Iteration   3: 3.202 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.348 ms/op
                 existUser·p0.50:   3.178 ms/op
                 existUser·p0.90:   3.486 ms/op
                 existUser·p0.95:   3.768 ms/op
                 existUser·p0.99:   5.651 ms/op
                 existUser·p0.999:  11.603 ms/op
                 existUser·p0.9999: 22.512 ms/op
                 existUser·p1.00:   22.839 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 300547
  mean =      3.191 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18156 
    [ 2.500,  5.000) = 278197 
    [ 5.000,  7.500) = 3424 
    [ 7.500, 10.000) = 354 
    [10.000, 12.500) = 134 
    [12.500, 15.000) = 26 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 86 
    [20.000, 22.500) = 116 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.149 ms/op
     p(50.0000) =      3.154 ms/op
     p(90.0000) =      3.482 ms/op
     p(95.0000) =      3.744 ms/op
     p(99.0000) =      5.497 ms/op
     p(99.9000) =     12.009 ms/op
     p(99.9900) =     22.149 ms/op
     p(99.9990) =     23.756 ms/op
     p(99.9999) =     24.150 ms/op
    p(100.0000) =     24.150 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 8.441 ±(99.9%) 0.115 ms/op
# Warmup Iteration   2: 3.445 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.248 ±(99.9%) 0.009 ms/op
Iteration   1: 3.440 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.077 ms/op
                 getUser·p0.50:   3.269 ms/op
                 getUser·p0.90:   3.789 ms/op
                 getUser·p0.95:   4.538 ms/op
                 getUser·p0.99:   7.651 ms/op
                 getUser·p0.999:  18.219 ms/op
                 getUser·p0.9999: 22.010 ms/op
                 getUser·p1.00:   22.315 ms/op

Iteration   2: 3.254 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.194 ms/op
                 getUser·p0.50:   3.219 ms/op
                 getUser·p0.90:   3.629 ms/op
                 getUser·p0.95:   3.899 ms/op
                 getUser·p0.99:   5.202 ms/op
                 getUser·p0.999:  13.112 ms/op
                 getUser·p0.9999: 24.418 ms/op
                 getUser·p1.00:   24.904 ms/op

Iteration   3: 3.273 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.231 ms/op
                 getUser·p0.50:   3.195 ms/op
                 getUser·p0.90:   3.625 ms/op
                 getUser·p0.95:   3.871 ms/op
                 getUser·p0.99:   5.717 ms/op
                 getUser·p0.999:  8.753 ms/op
                 getUser·p0.9999: 21.541 ms/op
                 getUser·p1.00:   23.069 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 288936
  mean =      3.320 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13273 
    [ 2.500,  5.000) = 268670 
    [ 5.000,  7.500) = 5618 
    [ 7.500, 10.000) = 714 
    [10.000, 12.500) = 262 
    [12.500, 15.000) = 78 
    [15.000, 17.500) = 42 
    [17.500, 20.000) = 128 
    [20.000, 22.500) = 133 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.077 ms/op
     p(50.0000) =      3.224 ms/op
     p(90.0000) =      3.682 ms/op
     p(95.0000) =      4.006 ms/op
     p(99.0000) =      6.463 ms/op
     p(99.9000) =     16.814 ms/op
     p(99.9900) =     22.089 ms/op
     p(99.9990) =     24.747 ms/op
     p(99.9999) =     24.904 ms/op
    p(100.0000) =     24.904 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 10.259 ±(99.9%) 0.127 ms/op
# Warmup Iteration   2: 4.355 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.943 ±(99.9%) 0.011 ms/op
Iteration   1: 3.869 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.335 ms/op
                 listUser·p0.50:   3.744 ms/op
                 listUser·p0.90:   4.186 ms/op
                 listUser·p0.95:   4.415 ms/op
                 listUser·p0.99:   6.922 ms/op
                 listUser·p0.999:  16.326 ms/op
                 listUser·p0.9999: 19.896 ms/op
                 listUser·p1.00:   20.873 ms/op

Iteration   2: 3.883 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.159 ms/op
                 listUser·p0.50:   3.797 ms/op
                 listUser·p0.90:   4.260 ms/op
                 listUser·p0.95:   4.473 ms/op
                 listUser·p0.99:   6.666 ms/op
                 listUser·p0.999:  13.582 ms/op
                 listUser·p0.9999: 17.203 ms/op
                 listUser·p1.00:   17.662 ms/op

Iteration   3: 3.809 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.355 ms/op
                 listUser·p0.50:   3.686 ms/op
                 listUser·p0.90:   4.174 ms/op
                 listUser·p0.95:   4.350 ms/op
                 listUser·p0.99:   6.595 ms/op
                 listUser·p0.999:  14.025 ms/op
                 listUser·p0.9999: 14.854 ms/op
                 listUser·p1.00:   16.171 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 249083
  mean =      3.854 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 60 
    [ 2.500,  5.000) = 242356 
    [ 5.000,  7.500) = 5401 
    [ 7.500, 10.000) = 632 
    [10.000, 12.500) = 224 
    [12.500, 15.000) = 276 
    [15.000, 17.500) = 77 
    [17.500, 20.000) = 50 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.335 ms/op
     p(50.0000) =      3.744 ms/op
     p(90.0000) =      4.202 ms/op
     p(95.0000) =      4.415 ms/op
     p(99.0000) =      6.701 ms/op
     p(99.9000) =     14.089 ms/op
     p(99.9900) =     19.074 ms/op
     p(99.9990) =     20.514 ms/op
     p(99.9999) =     20.873 ms/op
    p(100.0000) =     20.873 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.620 ± 1.971  ops/ms
ClientPb.existUser                       thrpt       3  10.218 ± 2.206  ops/ms
ClientPb.getUser                         thrpt       3   9.746 ± 2.689  ops/ms
ClientPb.listUser                        thrpt       3   8.284 ± 0.972  ops/ms
ClientPb.createUser                       avgt       3   3.303 ± 2.850   ms/op
ClientPb.existUser                        avgt       3   3.164 ± 0.562   ms/op
ClientPb.getUser                          avgt       3   3.284 ± 0.554   ms/op
ClientPb.listUser                         avgt       3   3.891 ± 1.254   ms/op
ClientPb.createUser                     sample  289252   3.317 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.940           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.236           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.744           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.018           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.612           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.055           ms/op
ClientPb.createUser:createUser·p0.9999  sample          29.529           ms/op
ClientPb.createUser:createUser·p1.00    sample          31.162           ms/op
ClientPb.existUser                      sample  300547   3.191 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.149           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.154           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.482           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.744           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.497           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.009           ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.149           ms/op
ClientPb.existUser:existUser·p1.00      sample          24.150           ms/op
ClientPb.getUser                        sample  288936   3.320 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.077           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.224           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.682           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.006           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.463           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.814           ms/op
ClientPb.getUser:getUser·p0.9999        sample          22.089           ms/op
ClientPb.getUser:getUser·p1.00          sample          24.904           ms/op
ClientPb.listUser                       sample  249083   3.854 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.335           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.744           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.202           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.415           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.701           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.089           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.074           ms/op
ClientPb.listUser:listUser·p1.00        sample          20.873           ms/op
