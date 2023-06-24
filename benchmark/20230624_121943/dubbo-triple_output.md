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
# Warmup Iteration   1: 1.560 ops/ms
# Warmup Iteration   2: 3.569 ops/ms
# Warmup Iteration   3: 6.801 ops/ms
Iteration   1: 7.035 ops/ms
Iteration   2: 7.736 ops/ms
Iteration   3: 7.879 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.550 ±(99.9%) 8.242 ops/ms [Average]
  (min, avg, max) = (7.035, 7.550, 7.879), stdev = 0.452
  CI (99.9%): [≈ 0, 15.792] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:14
# Fork: 1 of 1
# Warmup Iteration   1: 2.265 ops/ms
# Warmup Iteration   2: 6.675 ops/ms
# Warmup Iteration   3: 7.974 ops/ms
Iteration   1: 7.942 ops/ms
Iteration   2: 8.395 ops/ms
Iteration   3: 8.478 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.272 ±(99.9%) 5.258 ops/ms [Average]
  (min, avg, max) = (7.942, 8.272, 8.478), stdev = 0.288
  CI (99.9%): [3.013, 13.530] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:05
# Fork: 1 of 1
# Warmup Iteration   1: 2.126 ops/ms
# Warmup Iteration   2: 5.858 ops/ms
# Warmup Iteration   3: 7.570 ops/ms
Iteration   1: 7.630 ops/ms
Iteration   2: 7.675 ops/ms
Iteration   3: 7.967 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.757 ±(99.9%) 3.340 ops/ms [Average]
  (min, avg, max) = (7.630, 7.757, 7.967), stdev = 0.183
  CI (99.9%): [4.418, 11.097] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:59
# Fork: 1 of 1
# Warmup Iteration   1: 1.900 ops/ms
# Warmup Iteration   2: 5.185 ops/ms
# Warmup Iteration   3: 6.589 ops/ms
Iteration   1: 6.542 ops/ms
Iteration   2: 6.719 ops/ms
Iteration   3: 6.860 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.707 ±(99.9%) 2.908 ops/ms [Average]
  (min, avg, max) = (6.542, 6.707, 6.860), stdev = 0.159
  CI (99.9%): [3.799, 9.615] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:52
# Fork: 1 of 1
# Warmup Iteration   1: 13.920 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 4.694 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.249 ±(99.9%) 0.007 ms/op
Iteration   1: 4.005 ±(99.9%) 0.003 ms/op
Iteration   2: 3.888 ±(99.9%) 0.012 ms/op
Iteration   3: 3.903 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.932 ±(99.9%) 1.157 ms/op [Average]
  (min, avg, max) = (3.888, 3.932, 4.005), stdev = 0.063
  CI (99.9%): [2.775, 5.089] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:44
# Fork: 1 of 1
# Warmup Iteration   1: 12.682 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 4.476 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.033 ±(99.9%) 0.006 ms/op
Iteration   1: 3.914 ±(99.9%) 0.006 ms/op
Iteration   2: 3.952 ±(99.9%) 0.002 ms/op
Iteration   3: 3.791 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.886 ±(99.9%) 1.534 ms/op [Average]
  (min, avg, max) = (3.791, 3.886, 3.952), stdev = 0.084
  CI (99.9%): [2.352, 5.419] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:38
# Fork: 1 of 1
# Warmup Iteration   1: 13.671 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.930 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.132 ±(99.9%) 0.007 ms/op
Iteration   1: 4.265 ±(99.9%) 0.004 ms/op
Iteration   2: 3.992 ±(99.9%) 0.009 ms/op
Iteration   3: 4.068 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.109 ±(99.9%) 2.568 ms/op [Average]
  (min, avg, max) = (3.992, 4.109, 4.265), stdev = 0.141
  CI (99.9%): [1.540, 6.677] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:32
# Fork: 1 of 1
# Warmup Iteration   1: 14.730 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 5.778 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.931 ±(99.9%) 0.012 ms/op
Iteration   1: 4.832 ±(99.9%) 0.010 ms/op
Iteration   2: 4.874 ±(99.9%) 0.010 ms/op
Iteration   3: 4.865 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.857 ±(99.9%) 0.406 ms/op [Average]
  (min, avg, max) = (4.832, 4.857, 4.874), stdev = 0.022
  CI (99.9%): [4.451, 5.263] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 14.008 ±(99.9%) 0.197 ms/op
# Warmup Iteration   2: 5.185 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 4.444 ±(99.9%) 0.018 ms/op
Iteration   1: 4.253 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.937 ms/op
                 createUser·p0.50:   4.006 ms/op
                 createUser·p0.90:   5.030 ms/op
                 createUser·p0.95:   6.308 ms/op
                 createUser·p0.99:   8.405 ms/op
                 createUser·p0.999:  15.414 ms/op
                 createUser·p0.9999: 25.966 ms/op
                 createUser·p1.00:   27.689 ms/op

Iteration   2: 4.092 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.614 ms/op
                 createUser·p0.50:   3.846 ms/op
                 createUser·p0.90:   4.596 ms/op
                 createUser·p0.95:   5.497 ms/op
                 createUser·p0.99:   8.266 ms/op
                 createUser·p0.999:  25.585 ms/op
                 createUser·p0.9999: 28.082 ms/op
                 createUser·p1.00:   29.557 ms/op

Iteration   3: 4.005 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.894 ms/op
                 createUser·p0.50:   3.846 ms/op
                 createUser·p0.90:   4.522 ms/op
                 createUser·p0.95:   4.809 ms/op
                 createUser·p0.99:   6.849 ms/op
                 createUser·p0.999:  12.915 ms/op
                 createUser·p0.9999: 30.549 ms/op
                 createUser·p1.00:   32.014 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 233169
  mean =      4.114 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 287 
    [ 2.500,  5.000) = 217553 
    [ 5.000,  7.500) = 12098 
    [ 7.500, 10.000) = 2358 
    [10.000, 12.500) = 415 
    [12.500, 15.000) = 178 
    [15.000, 17.500) = 46 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 39 
    [25.000, 27.500) = 100 
    [27.500, 30.000) = 71 
    [30.000, 32.500) = 14 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.614 ms/op
     p(50.0000) =      3.908 ms/op
     p(90.0000) =      4.686 ms/op
     p(95.0000) =      5.317 ms/op
     p(99.0000) =      8.014 ms/op
     p(99.9000) =     18.626 ms/op
     p(99.9900) =     29.448 ms/op
     p(99.9990) =     31.611 ms/op
     p(99.9999) =     32.014 ms/op
    p(100.0000) =     32.014 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 12.723 ±(99.9%) 0.169 ms/op
# Warmup Iteration   2: 4.327 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.167 ±(99.9%) 0.013 ms/op
Iteration   1: 4.086 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.915 ms/op
                 existUser·p0.50:   3.891 ms/op
                 existUser·p0.90:   4.817 ms/op
                 existUser·p0.95:   5.947 ms/op
                 existUser·p0.99:   7.856 ms/op
                 existUser·p0.999:  12.206 ms/op
                 existUser·p0.9999: 25.099 ms/op
                 existUser·p1.00:   25.821 ms/op

Iteration   2: 3.824 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.968 ms/op
                 existUser·p0.50:   3.781 ms/op
                 existUser·p0.90:   4.035 ms/op
                 existUser·p0.95:   4.555 ms/op
                 existUser·p0.99:   6.636 ms/op
                 existUser·p0.999:  14.519 ms/op
                 existUser·p0.9999: 26.441 ms/op
                 existUser·p1.00:   27.165 ms/op

Iteration   3: 4.034 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   2.007 ms/op
                 existUser·p0.50:   3.854 ms/op
                 existUser·p0.90:   4.694 ms/op
                 existUser·p0.95:   5.243 ms/op
                 existUser·p0.99:   7.504 ms/op
                 existUser·p0.999:  27.729 ms/op
                 existUser·p0.9999: 30.722 ms/op
                 existUser·p1.00:   32.047 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 241237
  mean =      3.978 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 286 
    [ 2.500,  5.000) = 226139 
    [ 5.000,  7.500) = 12261 
    [ 7.500, 10.000) = 1915 
    [10.000, 12.500) = 323 
    [12.500, 15.000) = 71 
    [15.000, 17.500) = 18 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 67 
    [25.000, 27.500) = 62 
    [27.500, 30.000) = 53 
    [30.000, 32.500) = 30 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.915 ms/op
     p(50.0000) =      3.826 ms/op
     p(90.0000) =      4.538 ms/op
     p(95.0000) =      5.218 ms/op
     p(99.0000) =      7.569 ms/op
     p(99.9000) =     15.127 ms/op
     p(99.9900) =     30.208 ms/op
     p(99.9990) =     31.949 ms/op
     p(99.9999) =     32.047 ms/op
    p(100.0000) =     32.047 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 12.769 ±(99.9%) 0.167 ms/op
# Warmup Iteration   2: 4.891 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 4.341 ±(99.9%) 0.013 ms/op
Iteration   1: 4.089 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.522 ms/op
                 getUser·p0.50:   3.854 ms/op
                 getUser·p0.90:   4.637 ms/op
                 getUser·p0.95:   5.932 ms/op
                 getUser·p0.99:   8.569 ms/op
                 getUser·p0.999:  17.687 ms/op
                 getUser·p0.9999: 26.220 ms/op
                 getUser·p1.00:   26.608 ms/op

Iteration   2: 3.939 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.434 ms/op
                 getUser·p0.50:   3.789 ms/op
                 getUser·p0.90:   4.276 ms/op
                 getUser·p0.95:   4.522 ms/op
                 getUser·p0.99:   7.627 ms/op
                 getUser·p0.999:  25.678 ms/op
                 getUser·p0.9999: 29.767 ms/op
                 getUser·p1.00:   32.276 ms/op

Iteration   3: 3.945 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.722 ms/op
                 getUser·p0.50:   3.768 ms/op
                 getUser·p0.90:   4.415 ms/op
                 getUser·p0.95:   4.997 ms/op
                 getUser·p0.99:   6.685 ms/op
                 getUser·p0.999:  12.140 ms/op
                 getUser·p0.9999: 29.483 ms/op
                 getUser·p1.00:   30.343 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 240472
  mean =      3.990 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 79 
    [ 2.500,  5.000) = 228035 
    [ 5.000,  7.500) = 9457 
    [ 7.500, 10.000) = 2013 
    [10.000, 12.500) = 482 
    [12.500, 15.000) = 117 
    [15.000, 17.500) = 43 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 35 
    [25.000, 27.500) = 89 
    [27.500, 30.000) = 92 
    [30.000, 32.500) = 8 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.434 ms/op
     p(50.0000) =      3.793 ms/op
     p(90.0000) =      4.432 ms/op
     p(95.0000) =      5.054 ms/op
     p(99.0000) =      7.791 ms/op
     p(99.9000) =     17.614 ms/op
     p(99.9900) =     29.095 ms/op
     p(99.9990) =     30.467 ms/op
     p(99.9999) =     32.276 ms/op
    p(100.0000) =     32.276 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 13.707 ±(99.9%) 0.215 ms/op
# Warmup Iteration   2: 5.421 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 4.856 ±(99.9%) 0.016 ms/op
Iteration   1: 4.816 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.892 ms/op
                 listUser·p0.50:   4.645 ms/op
                 listUser·p0.90:   5.284 ms/op
                 listUser·p0.95:   6.144 ms/op
                 listUser·p0.99:   8.934 ms/op
                 listUser·p0.999:  25.934 ms/op
                 listUser·p0.9999: 28.148 ms/op
                 listUser·p1.00:   29.295 ms/op

Iteration   2: 4.776 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   2.712 ms/op
                 listUser·p0.50:   4.604 ms/op
                 listUser·p0.90:   5.226 ms/op
                 listUser·p0.95:   6.816 ms/op
                 listUser·p0.99:   8.339 ms/op
                 listUser·p0.999:  18.153 ms/op
                 listUser·p0.9999: 24.137 ms/op
                 listUser·p1.00:   25.231 ms/op

Iteration   3: 4.703 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.789 ms/op
                 listUser·p0.50:   4.514 ms/op
                 listUser·p0.90:   5.177 ms/op
                 listUser·p0.95:   5.587 ms/op
                 listUser·p0.99:   9.129 ms/op
                 listUser·p0.999:  15.664 ms/op
                 listUser·p0.9999: 20.185 ms/op
                 listUser·p1.00:   20.251 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 201576
  mean =      4.765 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6 
    [ 2.500,  5.000) = 173522 
    [ 5.000,  7.500) = 22187 
    [ 7.500, 10.000) = 4660 
    [10.000, 12.500) = 587 
    [12.500, 15.000) = 159 
    [15.000, 17.500) = 168 
    [17.500, 20.000) = 51 
    [20.000, 22.500) = 52 
    [22.500, 25.000) = 100 
    [25.000, 27.500) = 68 

  Percentiles, ms/op:
      p(0.0000) =      1.892 ms/op
     p(50.0000) =      4.596 ms/op
     p(90.0000) =      5.210 ms/op
     p(95.0000) =      6.006 ms/op
     p(99.0000) =      8.667 ms/op
     p(99.9000) =     21.162 ms/op
     p(99.9900) =     26.935 ms/op
     p(99.9990) =     29.256 ms/op
     p(99.9999) =     29.295 ms/op
    p(100.0000) =     29.295 ms/op


# Run complete. Total time: 00:13:17

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.550 ± 8.242  ops/ms
ClientPb.existUser                       thrpt       3   8.272 ± 5.258  ops/ms
ClientPb.getUser                         thrpt       3   7.757 ± 3.340  ops/ms
ClientPb.listUser                        thrpt       3   6.707 ± 2.908  ops/ms
ClientPb.createUser                       avgt       3   3.932 ± 1.157   ms/op
ClientPb.existUser                        avgt       3   3.886 ± 1.534   ms/op
ClientPb.getUser                          avgt       3   4.109 ± 2.568   ms/op
ClientPb.listUser                         avgt       3   4.857 ± 0.406   ms/op
ClientPb.createUser                     sample  233169   4.114 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.614           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.908           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.686           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.317           ms/op
ClientPb.createUser:createUser·p0.99    sample           8.014           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.626           ms/op
ClientPb.createUser:createUser·p0.9999  sample          29.448           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.014           ms/op
ClientPb.existUser                      sample  241237   3.978 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.915           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.826           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.538           ms/op
ClientPb.existUser:existUser·p0.95      sample           5.218           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.569           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.127           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.208           ms/op
ClientPb.existUser:existUser·p1.00      sample          32.047           ms/op
ClientPb.getUser                        sample  240472   3.990 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.434           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.793           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.432           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.054           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.791           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.614           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.095           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.276           ms/op
ClientPb.listUser                       sample  201576   4.765 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.892           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.596           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.210           ms/op
ClientPb.listUser:listUser·p0.95        sample           6.006           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.667           ms/op
ClientPb.listUser:listUser·p0.999       sample          21.162           ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.935           ms/op
ClientPb.listUser:listUser·p1.00        sample          29.295           ms/op
