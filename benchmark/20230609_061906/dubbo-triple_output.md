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
# Warmup Iteration   1: 2.451 ops/ms
# Warmup Iteration   2: 6.224 ops/ms
# Warmup Iteration   3: 9.003 ops/ms
Iteration   1: 9.666 ops/ms
Iteration   2: 9.609 ops/ms
Iteration   3: 9.884 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.719 ±(99.9%) 2.648 ops/ms [Average]
  (min, avg, max) = (9.609, 9.719, 9.884), stdev = 0.145
  CI (99.9%): [7.071, 12.368] (assumes normal distribution)


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
# Warmup Iteration   1: 3.434 ops/ms
# Warmup Iteration   2: 9.262 ops/ms
# Warmup Iteration   3: 9.941 ops/ms
Iteration   1: 10.411 ops/ms
Iteration   2: 10.346 ops/ms
Iteration   3: 10.472 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.410 ±(99.9%) 1.149 ops/ms [Average]
  (min, avg, max) = (10.346, 10.410, 10.472), stdev = 0.063
  CI (99.9%): [9.261, 11.559] (assumes normal distribution)


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
# Warmup Iteration   1: 3.429 ops/ms
# Warmup Iteration   2: 8.565 ops/ms
# Warmup Iteration   3: 9.385 ops/ms
Iteration   1: 9.960 ops/ms
Iteration   2: 9.632 ops/ms
Iteration   3: 9.509 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.700 ±(99.9%) 4.259 ops/ms [Average]
  (min, avg, max) = (9.509, 9.700, 9.960), stdev = 0.233
  CI (99.9%): [5.442, 13.959] (assumes normal distribution)


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
# Warmup Iteration   1: 3.370 ops/ms
# Warmup Iteration   2: 7.808 ops/ms
# Warmup Iteration   3: 8.265 ops/ms
Iteration   1: 8.341 ops/ms
Iteration   2: 8.649 ops/ms
Iteration   3: 8.412 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.467 ±(99.9%) 2.948 ops/ms [Average]
  (min, avg, max) = (8.341, 8.467, 8.649), stdev = 0.162
  CI (99.9%): [5.519, 11.415] (assumes normal distribution)


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
# Warmup Iteration   1: 9.037 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.658 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.309 ±(99.9%) 0.003 ms/op
Iteration   1: 3.254 ±(99.9%) 0.002 ms/op
Iteration   2: 3.176 ±(99.9%) 0.008 ms/op
Iteration   3: 3.295 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.242 ±(99.9%) 1.096 ms/op [Average]
  (min, avg, max) = (3.176, 3.242, 3.295), stdev = 0.060
  CI (99.9%): [2.146, 4.338] (assumes normal distribution)


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
# Warmup Iteration   1: 6.969 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.223 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.209 ±(99.9%) 0.007 ms/op
Iteration   1: 3.263 ±(99.9%) 0.006 ms/op
Iteration   2: 3.076 ±(99.9%) 0.005 ms/op
Iteration   3: 3.143 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.161 ±(99.9%) 1.731 ms/op [Average]
  (min, avg, max) = (3.076, 3.161, 3.263), stdev = 0.095
  CI (99.9%): [1.430, 4.892] (assumes normal distribution)


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
# Warmup Iteration   1: 7.367 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.265 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.423 ±(99.9%) 0.003 ms/op
Iteration   1: 3.168 ±(99.9%) 0.004 ms/op
Iteration   2: 3.137 ±(99.9%) 0.004 ms/op
Iteration   3: 3.261 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.189 ±(99.9%) 1.173 ms/op [Average]
  (min, avg, max) = (3.137, 3.189, 3.261), stdev = 0.064
  CI (99.9%): [2.015, 4.362] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 9.334 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.196 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.860 ±(99.9%) 0.008 ms/op
Iteration   1: 3.765 ±(99.9%) 0.010 ms/op
Iteration   2: 3.881 ±(99.9%) 0.007 ms/op
Iteration   3: 3.802 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.816 ±(99.9%) 1.090 ms/op [Average]
  (min, avg, max) = (3.765, 3.816, 3.881), stdev = 0.060
  CI (99.9%): [2.726, 4.905] (assumes normal distribution)


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
# Warmup Iteration   1: 8.263 ±(99.9%) 0.100 ms/op
# Warmup Iteration   2: 3.713 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.193 ±(99.9%) 0.008 ms/op
Iteration   1: 3.193 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.237 ms/op
                 createUser·p0.50:   3.047 ms/op
                 createUser·p0.90:   3.596 ms/op
                 createUser·p0.95:   3.895 ms/op
                 createUser·p0.99:   5.579 ms/op
                 createUser·p0.999:  10.778 ms/op
                 createUser·p0.9999: 22.184 ms/op
                 createUser·p1.00:   27.984 ms/op

Iteration   2: 3.262 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.253 ms/op
                 createUser·p0.50:   3.142 ms/op
                 createUser·p0.90:   3.801 ms/op
                 createUser·p0.95:   4.190 ms/op
                 createUser·p0.99:   5.603 ms/op
                 createUser·p0.999:  17.992 ms/op
                 createUser·p0.9999: 28.097 ms/op
                 createUser·p1.00:   29.458 ms/op

Iteration   3: 3.225 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.405 ms/op
                 createUser·p0.50:   3.080 ms/op
                 createUser·p0.90:   3.662 ms/op
                 createUser·p0.95:   3.957 ms/op
                 createUser·p0.99:   5.341 ms/op
                 createUser·p0.999:  15.659 ms/op
                 createUser·p0.9999: 26.673 ms/op
                 createUser·p1.00:   28.082 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 297248
  mean =      3.226 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8938 
    [ 2.500,  5.000) = 282912 
    [ 5.000,  7.500) = 4613 
    [ 7.500, 10.000) = 381 
    [10.000, 12.500) = 40 
    [12.500, 15.000) = 43 
    [15.000, 17.500) = 23 
    [17.500, 20.000) = 91 
    [20.000, 22.500) = 133 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 41 

  Percentiles, ms/op:
      p(0.0000) =      1.237 ms/op
     p(50.0000) =      3.084 ms/op
     p(90.0000) =      3.678 ms/op
     p(95.0000) =      4.022 ms/op
     p(99.0000) =      5.521 ms/op
     p(99.9000) =     17.613 ms/op
     p(99.9900) =     26.736 ms/op
     p(99.9990) =     28.869 ms/op
     p(99.9999) =     29.458 ms/op
    p(100.0000) =     29.458 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 7.165 ±(99.9%) 0.100 ms/op
# Warmup Iteration   2: 3.369 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.166 ±(99.9%) 0.008 ms/op
Iteration   1: 3.186 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.599 ms/op
                 existUser·p0.50:   3.146 ms/op
                 existUser·p0.90:   3.559 ms/op
                 existUser·p0.95:   3.867 ms/op
                 existUser·p0.99:   5.456 ms/op
                 existUser·p0.999:  13.524 ms/op
                 existUser·p0.9999: 20.216 ms/op
                 existUser·p1.00:   20.873 ms/op

Iteration   2: 3.115 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.025 ms/op
                 existUser·p0.50:   3.043 ms/op
                 existUser·p0.90:   3.326 ms/op
                 existUser·p0.95:   3.740 ms/op
                 existUser·p0.99:   6.070 ms/op
                 existUser·p0.999:  9.732 ms/op
                 existUser·p0.9999: 21.938 ms/op
                 existUser·p1.00:   23.724 ms/op

Iteration   3: 3.005 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.468 ms/op
                 existUser·p0.50:   2.945 ms/op
                 existUser·p0.90:   3.162 ms/op
                 existUser·p0.95:   3.367 ms/op
                 existUser·p0.99:   4.555 ms/op
                 existUser·p0.999:  14.942 ms/op
                 existUser·p0.9999: 20.677 ms/op
                 existUser·p1.00:   21.168 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 309573
  mean =      3.100 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21921 
    [ 2.500,  5.000) = 281925 
    [ 5.000,  7.500) = 5035 
    [ 7.500, 10.000) = 287 
    [10.000, 12.500) = 52 
    [12.500, 15.000) = 62 
    [15.000, 17.500) = 62 
    [17.500, 20.000) = 111 
    [20.000, 22.500) = 113 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.025 ms/op
     p(50.0000) =      3.052 ms/op
     p(90.0000) =      3.346 ms/op
     p(95.0000) =      3.666 ms/op
     p(99.0000) =      5.431 ms/op
     p(99.9000) =     14.893 ms/op
     p(99.9900) =     21.430 ms/op
     p(99.9990) =     23.524 ms/op
     p(99.9999) =     23.724 ms/op
    p(100.0000) =     23.724 ms/op


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
# Warmup Iteration   1: 7.839 ±(99.9%) 0.104 ms/op
# Warmup Iteration   2: 3.467 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.410 ±(99.9%) 0.010 ms/op
Iteration   1: 3.352 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.614 ms/op
                 getUser·p0.50:   3.162 ms/op
                 getUser·p0.90:   3.760 ms/op
                 getUser·p0.95:   4.973 ms/op
                 getUser·p0.99:   6.922 ms/op
                 getUser·p0.999:  17.284 ms/op
                 getUser·p0.9999: 24.329 ms/op
                 getUser·p1.00:   25.002 ms/op

Iteration   2: 3.290 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.235 ms/op
                 getUser·p0.50:   3.203 ms/op
                 getUser·p0.90:   3.822 ms/op
                 getUser·p0.95:   4.276 ms/op
                 getUser·p0.99:   5.718 ms/op
                 getUser·p0.999:  17.302 ms/op
                 getUser·p0.9999: 23.602 ms/op
                 getUser·p1.00:   24.379 ms/op

Iteration   3: 3.339 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.981 ms/op
                 getUser·p0.50:   3.248 ms/op
                 getUser·p0.90:   3.834 ms/op
                 getUser·p0.95:   4.194 ms/op
                 getUser·p0.99:   5.677 ms/op
                 getUser·p0.999:  14.951 ms/op
                 getUser·p0.9999: 29.884 ms/op
                 getUser·p1.00:   31.752 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 288358
  mean =      3.327 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20251 
    [ 2.500,  5.000) = 258741 
    [ 5.000,  7.500) = 8060 
    [ 7.500, 10.000) = 728 
    [10.000, 12.500) = 173 
    [12.500, 15.000) = 83 
    [15.000, 17.500) = 53 
    [17.500, 20.000) = 55 
    [20.000, 22.500) = 93 
    [22.500, 25.000) = 88 
    [25.000, 27.500) = 4 
    [27.500, 30.000) = 21 
    [30.000, 32.500) = 8 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.981 ms/op
     p(50.0000) =      3.215 ms/op
     p(90.0000) =      3.813 ms/op
     p(95.0000) =      4.317 ms/op
     p(99.0000) =      6.529 ms/op
     p(99.9000) =     15.730 ms/op
     p(99.9900) =     27.585 ms/op
     p(99.9990) =     31.633 ms/op
     p(99.9999) =     31.752 ms/op
    p(100.0000) =     31.752 ms/op


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
# Warmup Iteration   1: 9.617 ±(99.9%) 0.123 ms/op
# Warmup Iteration   2: 4.214 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.891 ±(99.9%) 0.012 ms/op
Iteration   1: 3.814 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.534 ms/op
                 listUser·p0.50:   3.629 ms/op
                 listUser·p0.90:   4.116 ms/op
                 listUser·p0.95:   4.678 ms/op
                 listUser·p0.99:   7.389 ms/op
                 listUser·p0.999:  15.057 ms/op
                 listUser·p0.9999: 21.483 ms/op
                 listUser·p1.00:   23.429 ms/op

Iteration   2: 3.906 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.183 ms/op
                 listUser·p0.50:   3.744 ms/op
                 listUser·p0.90:   4.424 ms/op
                 listUser·p0.95:   4.792 ms/op
                 listUser·p0.99:   7.283 ms/op
                 listUser·p0.999:  13.698 ms/op
                 listUser·p0.9999: 16.450 ms/op
                 listUser·p1.00:   16.515 ms/op

Iteration   3: 3.831 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.322 ms/op
                 listUser·p0.50:   3.682 ms/op
                 listUser·p0.90:   4.202 ms/op
                 listUser·p0.95:   4.465 ms/op
                 listUser·p0.99:   7.389 ms/op
                 listUser·p0.999:  14.303 ms/op
                 listUser·p0.9999: 16.433 ms/op
                 listUser·p1.00:   16.613 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 249403
  mean =      3.850 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 47 
    [ 2.500,  5.000) = 239623 
    [ 5.000,  7.500) = 7541 
    [ 7.500, 10.000) = 1492 
    [10.000, 12.500) = 310 
    [12.500, 15.000) = 209 
    [15.000, 17.500) = 117 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.534 ms/op
     p(50.0000) =      3.695 ms/op
     p(90.0000) =      4.252 ms/op
     p(95.0000) =      4.661 ms/op
     p(99.0000) =      7.356 ms/op
     p(99.9000) =     14.303 ms/op
     p(99.9900) =     20.644 ms/op
     p(99.9990) =     22.938 ms/op
     p(99.9999) =     23.429 ms/op
    p(100.0000) =     23.429 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.719 ± 2.648  ops/ms
ClientPb.existUser                       thrpt       3  10.410 ± 1.149  ops/ms
ClientPb.getUser                         thrpt       3   9.700 ± 4.259  ops/ms
ClientPb.listUser                        thrpt       3   8.467 ± 2.948  ops/ms
ClientPb.createUser                       avgt       3   3.242 ± 1.096   ms/op
ClientPb.existUser                        avgt       3   3.161 ± 1.731   ms/op
ClientPb.getUser                          avgt       3   3.189 ± 1.173   ms/op
ClientPb.listUser                         avgt       3   3.816 ± 1.090   ms/op
ClientPb.createUser                     sample  297248   3.226 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.237           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.084           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.678           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.022           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.521           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.613           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.736           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.458           ms/op
ClientPb.existUser                      sample  309573   3.100 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.025           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.052           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.346           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.666           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.431           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.893           ms/op
ClientPb.existUser:existUser·p0.9999    sample          21.430           ms/op
ClientPb.existUser:existUser·p1.00      sample          23.724           ms/op
ClientPb.getUser                        sample  288358   3.327 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.981           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.215           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.813           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.317           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.529           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.730           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.585           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.752           ms/op
ClientPb.listUser                       sample  249403   3.850 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.534           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.695           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.252           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.661           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.356           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.303           ms/op
ClientPb.listUser:listUser·p0.9999      sample          20.644           ms/op
ClientPb.listUser:listUser·p1.00        sample          23.429           ms/op
