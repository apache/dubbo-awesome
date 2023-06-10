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
# Warmup Iteration   1: 1.977 ops/ms
# Warmup Iteration   2: 5.449 ops/ms
# Warmup Iteration   3: 8.304 ops/ms
Iteration   1: 9.288 ops/ms
Iteration   2: 8.592 ops/ms
Iteration   3: 9.535 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.138 ±(99.9%) 8.922 ops/ms [Average]
  (min, avg, max) = (8.592, 9.138, 9.535), stdev = 0.489
  CI (99.9%): [0.216, 18.060] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.025 ops/ms
# Warmup Iteration   2: 8.719 ops/ms
# Warmup Iteration   3: 9.003 ops/ms
Iteration   1: 9.509 ops/ms
Iteration   2: 9.797 ops/ms
Iteration   3: 9.797 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.701 ±(99.9%) 3.035 ops/ms [Average]
  (min, avg, max) = (9.509, 9.701, 9.797), stdev = 0.166
  CI (99.9%): [6.666, 12.736] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 3.052 ops/ms
# Warmup Iteration   2: 7.854 ops/ms
# Warmup Iteration   3: 8.945 ops/ms
Iteration   1: 8.717 ops/ms
Iteration   2: 8.958 ops/ms
Iteration   3: 9.290 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.988 ±(99.9%) 5.244 ops/ms [Average]
  (min, avg, max) = (8.717, 8.988, 9.290), stdev = 0.287
  CI (99.9%): [3.744, 14.233] (assumes normal distribution)


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
# Warmup Iteration   1: 2.611 ops/ms
# Warmup Iteration   2: 7.215 ops/ms
# Warmup Iteration   3: 7.708 ops/ms
Iteration   1: 8.130 ops/ms
Iteration   2: 8.100 ops/ms
Iteration   3: 8.003 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.078 ±(99.9%) 1.217 ops/ms [Average]
  (min, avg, max) = (8.003, 8.078, 8.130), stdev = 0.067
  CI (99.9%): [6.861, 9.295] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 9.227 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.901 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.550 ±(99.9%) 0.014 ms/op
Iteration   1: 3.557 ±(99.9%) 0.004 ms/op
Iteration   2: 3.537 ±(99.9%) 0.003 ms/op
Iteration   3: 3.364 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.486 ±(99.9%) 1.931 ms/op [Average]
  (min, avg, max) = (3.364, 3.486, 3.557), stdev = 0.106
  CI (99.9%): [1.555, 5.417] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 8.428 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.588 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.501 ±(99.9%) 0.003 ms/op
Iteration   1: 3.397 ±(99.9%) 0.009 ms/op
Iteration   2: 3.356 ±(99.9%) 0.007 ms/op
Iteration   3: 3.325 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.360 ±(99.9%) 0.660 ms/op [Average]
  (min, avg, max) = (3.325, 3.360, 3.397), stdev = 0.036
  CI (99.9%): [2.699, 4.020] (assumes normal distribution)


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
# Warmup Iteration   1: 9.466 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.795 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.694 ±(99.9%) 0.006 ms/op
Iteration   1: 3.632 ±(99.9%) 0.005 ms/op
Iteration   2: 3.546 ±(99.9%) 0.006 ms/op
Iteration   3: 3.509 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.562 ±(99.9%) 1.152 ms/op [Average]
  (min, avg, max) = (3.509, 3.562, 3.632), stdev = 0.063
  CI (99.9%): [2.410, 4.715] (assumes normal distribution)


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
# Warmup Iteration   1: 12.304 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 4.444 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.267 ±(99.9%) 0.004 ms/op
Iteration   1: 4.132 ±(99.9%) 0.008 ms/op
Iteration   2: 4.003 ±(99.9%) 0.012 ms/op
Iteration   3: 4.012 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.049 ±(99.9%) 1.319 ms/op [Average]
  (min, avg, max) = (4.003, 4.049, 4.132), stdev = 0.072
  CI (99.9%): [2.730, 5.368] (assumes normal distribution)


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
# Warmup Iteration   1: 10.879 ±(99.9%) 0.141 ms/op
# Warmup Iteration   2: 4.192 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.988 ±(99.9%) 0.014 ms/op
Iteration   1: 3.521 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.272 ms/op
                 createUser·p0.50:   3.494 ms/op
                 createUser·p0.90:   3.879 ms/op
                 createUser·p0.95:   4.190 ms/op
                 createUser·p0.99:   5.759 ms/op
                 createUser·p0.999:  19.706 ms/op
                 createUser·p0.9999: 22.997 ms/op
                 createUser·p1.00:   23.626 ms/op

Iteration   2: 3.549 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.540 ms/op
                 createUser·p0.50:   3.461 ms/op
                 createUser·p0.90:   3.953 ms/op
                 createUser·p0.95:   4.268 ms/op
                 createUser·p0.99:   5.857 ms/op
                 createUser·p0.999:  22.512 ms/op
                 createUser·p0.9999: 25.263 ms/op
                 createUser·p1.00:   25.985 ms/op

Iteration   3: 3.627 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.225 ms/op
                 createUser·p0.50:   3.518 ms/op
                 createUser·p0.90:   4.108 ms/op
                 createUser·p0.95:   4.702 ms/op
                 createUser·p0.99:   6.414 ms/op
                 createUser·p0.999:  21.005 ms/op
                 createUser·p0.9999: 26.188 ms/op
                 createUser·p1.00:   27.165 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 269194
  mean =      3.565 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4652 
    [ 2.500,  5.000) = 257190 
    [ 5.000,  7.500) = 6229 
    [ 7.500, 10.000) = 585 
    [10.000, 12.500) = 166 
    [12.500, 15.000) = 31 
    [15.000, 17.500) = 12 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 136 
    [22.500, 25.000) = 136 
    [25.000, 27.500) = 37 

  Percentiles, ms/op:
      p(0.0000) =      1.225 ms/op
     p(50.0000) =      3.490 ms/op
     p(90.0000) =      3.985 ms/op
     p(95.0000) =      4.334 ms/op
     p(99.0000) =      5.980 ms/op
     p(99.9000) =     20.900 ms/op
     p(99.9900) =     25.133 ms/op
     p(99.9990) =     26.915 ms/op
     p(99.9999) =     27.165 ms/op
    p(100.0000) =     27.165 ms/op


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
# Warmup Iteration   1: 10.339 ±(99.9%) 0.118 ms/op
# Warmup Iteration   2: 3.723 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.346 ±(99.9%) 0.009 ms/op
Iteration   1: 3.355 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.632 ms/op
                 existUser·p0.50:   3.191 ms/op
                 existUser·p0.90:   3.645 ms/op
                 existUser·p0.95:   4.125 ms/op
                 existUser·p0.99:   6.939 ms/op
                 existUser·p0.999:  21.017 ms/op
                 existUser·p0.9999: 23.134 ms/op
                 existUser·p1.00:   23.855 ms/op

Iteration   2: 3.470 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.143 ms/op
                 existUser·p0.50:   3.367 ms/op
                 existUser·p0.90:   3.990 ms/op
                 existUser·p0.95:   4.325 ms/op
                 existUser·p0.99:   6.092 ms/op
                 existUser·p0.999:  20.000 ms/op
                 existUser·p0.9999: 23.877 ms/op
                 existUser·p1.00:   24.314 ms/op

Iteration   3: 3.532 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.634 ms/op
                 existUser·p0.50:   3.428 ms/op
                 existUser·p0.90:   4.174 ms/op
                 existUser·p0.95:   4.596 ms/op
                 existUser·p0.99:   6.201 ms/op
                 existUser·p0.999:  8.706 ms/op
                 existUser·p0.9999: 22.796 ms/op
                 existUser·p1.00:   23.790 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 278257
  mean =      3.451 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11794 
    [ 2.500,  5.000) = 257935 
    [ 5.000,  7.500) = 7464 
    [ 7.500, 10.000) = 642 
    [10.000, 12.500) = 107 
    [12.500, 15.000) = 49 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 161 
    [22.500, 25.000) = 91 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.143 ms/op
     p(50.0000) =      3.342 ms/op
     p(90.0000) =      3.961 ms/op
     p(95.0000) =      4.432 ms/op
     p(99.0000) =      6.349 ms/op
     p(99.9000) =     14.844 ms/op
     p(99.9900) =     23.364 ms/op
     p(99.9990) =     24.281 ms/op
     p(99.9999) =     24.314 ms/op
    p(100.0000) =     24.314 ms/op


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
# Warmup Iteration   1: 9.843 ±(99.9%) 0.128 ms/op
# Warmup Iteration   2: 3.874 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.640 ±(99.9%) 0.011 ms/op
Iteration   1: 3.494 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.794 ms/op
                 getUser·p0.50:   3.314 ms/op
                 getUser·p0.90:   3.854 ms/op
                 getUser·p0.95:   4.719 ms/op
                 getUser·p0.99:   6.799 ms/op
                 getUser·p0.999:  10.349 ms/op
                 getUser·p0.9999: 22.769 ms/op
                 getUser·p1.00:   23.167 ms/op

Iteration   2: 3.437 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.550 ms/op
                 getUser·p0.50:   3.310 ms/op
                 getUser·p0.90:   3.772 ms/op
                 getUser·p0.95:   3.973 ms/op
                 getUser·p0.99:   6.013 ms/op
                 getUser·p0.999:  19.088 ms/op
                 getUser·p0.9999: 28.312 ms/op
                 getUser·p1.00:   28.967 ms/op

Iteration   3: 3.491 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.995 ms/op
                 getUser·p0.50:   3.330 ms/op
                 getUser·p0.90:   3.834 ms/op
                 getUser·p0.95:   4.374 ms/op
                 getUser·p0.99:   6.488 ms/op
                 getUser·p0.999:  21.971 ms/op
                 getUser·p0.9999: 26.864 ms/op
                 getUser·p1.00:   27.722 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 276204
  mean =      3.474 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1448 
    [ 2.500,  5.000) = 265348 
    [ 5.000,  7.500) = 8183 
    [ 7.500, 10.000) = 818 
    [10.000, 12.500) = 128 
    [12.500, 15.000) = 11 
    [15.000, 17.500) = 11 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 107 
    [22.500, 25.000) = 50 
    [25.000, 27.500) = 68 

  Percentiles, ms/op:
      p(0.0000) =      0.995 ms/op
     p(50.0000) =      3.318 ms/op
     p(90.0000) =      3.817 ms/op
     p(95.0000) =      4.211 ms/op
     p(99.0000) =      6.545 ms/op
     p(99.9000) =     13.687 ms/op
     p(99.9900) =     26.935 ms/op
     p(99.9990) =     28.876 ms/op
     p(99.9999) =     28.967 ms/op
    p(100.0000) =     28.967 ms/op


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
# Warmup Iteration   1: 10.795 ±(99.9%) 0.154 ms/op
# Warmup Iteration   2: 4.483 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.253 ±(99.9%) 0.014 ms/op
Iteration   1: 4.115 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.612 ms/op
                 listUser·p0.50:   3.957 ms/op
                 listUser·p0.90:   4.481 ms/op
                 listUser·p0.95:   4.825 ms/op
                 listUser·p0.99:   7.881 ms/op
                 listUser·p0.999:  20.064 ms/op
                 listUser·p0.9999: 24.015 ms/op
                 listUser·p1.00:   25.133 ms/op

Iteration   2: 3.925 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.335 ms/op
                 listUser·p0.50:   3.916 ms/op
                 listUser·p0.90:   4.039 ms/op
                 listUser·p0.95:   4.149 ms/op
                 listUser·p0.99:   6.264 ms/op
                 listUser·p0.999:  15.106 ms/op
                 listUser·p0.9999: 16.489 ms/op
                 listUser·p1.00:   19.235 ms/op

Iteration   3: 3.960 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.599 ms/op
                 listUser·p0.50:   3.838 ms/op
                 listUser·p0.90:   4.317 ms/op
                 listUser·p0.95:   4.571 ms/op
                 listUser·p0.99:   6.431 ms/op
                 listUser·p0.999:  14.205 ms/op
                 listUser·p0.9999: 15.434 ms/op
                 listUser·p1.00:   16.400 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 239902
  mean =      3.998 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 38 
    [ 2.500,  5.000) = 232757 
    [ 5.000,  7.500) = 5201 
    [ 7.500, 10.000) = 1087 
    [10.000, 12.500) = 234 
    [12.500, 15.000) = 279 
    [15.000, 17.500) = 176 
    [17.500, 20.000) = 52 
    [20.000, 22.500) = 41 
    [22.500, 25.000) = 35 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.599 ms/op
     p(50.0000) =      3.899 ms/op
     p(90.0000) =      4.309 ms/op
     p(95.0000) =      4.588 ms/op
     p(99.0000) =      7.070 ms/op
     p(99.9000) =     15.452 ms/op
     p(99.9900) =     23.003 ms/op
     p(99.9990) =     25.042 ms/op
     p(99.9999) =     25.133 ms/op
    p(100.0000) =     25.133 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.138 ± 8.922  ops/ms
ClientPb.existUser                       thrpt       3   9.701 ± 3.035  ops/ms
ClientPb.getUser                         thrpt       3   8.988 ± 5.244  ops/ms
ClientPb.listUser                        thrpt       3   8.078 ± 1.217  ops/ms
ClientPb.createUser                       avgt       3   3.486 ± 1.931   ms/op
ClientPb.existUser                        avgt       3   3.360 ± 0.660   ms/op
ClientPb.getUser                          avgt       3   3.562 ± 1.152   ms/op
ClientPb.listUser                         avgt       3   4.049 ± 1.319   ms/op
ClientPb.createUser                     sample  269194   3.565 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.225           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.490           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.985           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.334           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.980           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.900           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.133           ms/op
ClientPb.createUser:createUser·p1.00    sample          27.165           ms/op
ClientPb.existUser                      sample  278257   3.451 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.143           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.342           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.961           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.432           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.349           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.844           ms/op
ClientPb.existUser:existUser·p0.9999    sample          23.364           ms/op
ClientPb.existUser:existUser·p1.00      sample          24.314           ms/op
ClientPb.getUser                        sample  276204   3.474 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.995           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.318           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.817           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.211           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.545           ms/op
ClientPb.getUser:getUser·p0.999         sample          13.687           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.935           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.967           ms/op
ClientPb.listUser                       sample  239902   3.998 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.599           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.899           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.309           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.588           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.070           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.452           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.003           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.133           ms/op
