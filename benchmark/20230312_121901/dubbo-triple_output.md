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
# Warmup Iteration   1: 1.884 ops/ms
# Warmup Iteration   2: 5.443 ops/ms
# Warmup Iteration   3: 8.573 ops/ms
Iteration   1: 9.197 ops/ms
Iteration   2: 9.159 ops/ms
Iteration   3: 9.227 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.194 ±(99.9%) 0.623 ops/ms [Average]
  (min, avg, max) = (9.159, 9.194, 9.227), stdev = 0.034
  CI (99.9%): [8.572, 9.817] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 3.004 ops/ms
# Warmup Iteration   2: 8.810 ops/ms
# Warmup Iteration   3: 9.338 ops/ms
Iteration   1: 9.733 ops/ms
Iteration   2: 9.788 ops/ms
Iteration   3: 9.653 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.725 ±(99.9%) 1.241 ops/ms [Average]
  (min, avg, max) = (9.653, 9.725, 9.788), stdev = 0.068
  CI (99.9%): [8.484, 10.966] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 2.692 ops/ms
# Warmup Iteration   2: 8.080 ops/ms
# Warmup Iteration   3: 9.339 ops/ms
Iteration   1: 9.150 ops/ms
Iteration   2: 9.099 ops/ms
Iteration   3: 9.357 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.202 ±(99.9%) 2.496 ops/ms [Average]
  (min, avg, max) = (9.099, 9.202, 9.357), stdev = 0.137
  CI (99.9%): [6.706, 11.698] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.781 ops/ms
# Warmup Iteration   2: 7.345 ops/ms
# Warmup Iteration   3: 7.830 ops/ms
Iteration   1: 8.070 ops/ms
Iteration   2: 8.006 ops/ms
Iteration   3: 8.222 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.099 ±(99.9%) 2.022 ops/ms [Average]
  (min, avg, max) = (8.006, 8.099, 8.222), stdev = 0.111
  CI (99.9%): [6.077, 10.122] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 10.623 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.934 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.519 ±(99.9%) 0.005 ms/op
Iteration   1: 3.383 ±(99.9%) 0.011 ms/op
Iteration   2: 3.380 ±(99.9%) 0.006 ms/op
Iteration   3: 3.330 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.364 ±(99.9%) 0.546 ms/op [Average]
  (min, avg, max) = (3.330, 3.364, 3.383), stdev = 0.030
  CI (99.9%): [2.819, 3.910] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 9.714 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.638 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.331 ±(99.9%) 0.004 ms/op
Iteration   1: 3.290 ±(99.9%) 0.004 ms/op
Iteration   2: 3.275 ±(99.9%) 0.007 ms/op
Iteration   3: 3.337 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.301 ±(99.9%) 0.591 ms/op [Average]
  (min, avg, max) = (3.275, 3.301, 3.337), stdev = 0.032
  CI (99.9%): [2.710, 3.892] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 9.265 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.655 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.391 ±(99.9%) 0.006 ms/op
Iteration   1: 3.521 ±(99.9%) 0.006 ms/op
Iteration   2: 3.420 ±(99.9%) 0.009 ms/op
Iteration   3: 3.390 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.444 ±(99.9%) 1.252 ms/op [Average]
  (min, avg, max) = (3.390, 3.444, 3.521), stdev = 0.069
  CI (99.9%): [2.192, 4.696] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 11.906 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 4.611 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.051 ±(99.9%) 0.015 ms/op
Iteration   1: 4.073 ±(99.9%) 0.009 ms/op
Iteration   2: 3.913 ±(99.9%) 0.010 ms/op
Iteration   3: 3.851 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.946 ±(99.9%) 2.091 ms/op [Average]
  (min, avg, max) = (3.851, 3.946, 4.073), stdev = 0.115
  CI (99.9%): [1.855, 6.037] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 10.543 ±(99.9%) 0.142 ms/op
# Warmup Iteration   2: 4.275 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 3.743 ±(99.9%) 0.013 ms/op
Iteration   1: 3.452 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.579 ms/op
                 createUser·p0.50:   3.400 ms/op
                 createUser·p0.90:   3.695 ms/op
                 createUser·p0.95:   4.375 ms/op
                 createUser·p0.99:   6.226 ms/op
                 createUser·p0.999:  21.831 ms/op
                 createUser·p0.9999: 28.860 ms/op
                 createUser·p1.00:   30.212 ms/op

Iteration   2: 3.405 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.612 ms/op
                 createUser·p0.50:   3.310 ms/op
                 createUser·p0.90:   3.813 ms/op
                 createUser·p0.95:   4.157 ms/op
                 createUser·p0.99:   5.759 ms/op
                 createUser·p0.999:  23.279 ms/op
                 createUser·p0.9999: 26.104 ms/op
                 createUser·p1.00:   27.492 ms/op

Iteration   3: 3.459 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.532 ms/op
                 createUser·p0.50:   3.285 ms/op
                 createUser·p0.90:   3.936 ms/op
                 createUser·p0.95:   4.243 ms/op
                 createUser·p0.99:   5.956 ms/op
                 createUser·p0.999:  22.171 ms/op
                 createUser·p0.9999: 29.975 ms/op
                 createUser·p1.00:   30.474 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 278918
  mean =      3.439 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10300 
    [ 2.500,  5.000) = 261616 
    [ 5.000,  7.500) = 5863 
    [ 7.500, 10.000) = 775 
    [10.000, 12.500) = 58 
    [12.500, 15.000) = 16 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 134 
    [25.000, 27.500) = 50 
    [27.500, 30.000) = 70 
    [30.000, 32.500) = 9 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.532 ms/op
     p(50.0000) =      3.346 ms/op
     p(90.0000) =      3.858 ms/op
     p(95.0000) =      4.252 ms/op
     p(99.0000) =      5.898 ms/op
     p(99.9000) =     21.957 ms/op
     p(99.9900) =     28.918 ms/op
     p(99.9990) =     30.252 ms/op
     p(99.9999) =     30.474 ms/op
    p(100.0000) =     30.474 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 8.142 ±(99.9%) 0.111 ms/op
# Warmup Iteration   2: 3.564 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.364 ±(99.9%) 0.009 ms/op
Iteration   1: 3.255 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.491 ms/op
                 existUser·p0.50:   3.174 ms/op
                 existUser·p0.90:   3.523 ms/op
                 existUser·p0.95:   3.748 ms/op
                 existUser·p0.99:   5.374 ms/op
                 existUser·p0.999:  10.127 ms/op
                 existUser·p0.9999: 24.090 ms/op
                 existUser·p1.00:   24.936 ms/op

Iteration   2: 3.300 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.661 ms/op
                 existUser·p0.50:   3.203 ms/op
                 existUser·p0.90:   3.727 ms/op
                 existUser·p0.95:   4.014 ms/op
                 existUser·p0.99:   5.464 ms/op
                 existUser·p0.999:  16.634 ms/op
                 existUser·p0.9999: 31.926 ms/op
                 existUser·p1.00:   32.309 ms/op

Iteration   3: 3.348 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.778 ms/op
                 existUser·p0.50:   3.252 ms/op
                 existUser·p0.90:   3.723 ms/op
                 existUser·p0.95:   4.325 ms/op
                 existUser·p0.99:   6.152 ms/op
                 existUser·p0.999:  18.973 ms/op
                 existUser·p0.9999: 25.835 ms/op
                 existUser·p1.00:   28.180 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 290734
  mean =      3.301 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12062 
    [ 2.500,  5.000) = 273129 
    [ 5.000,  7.500) = 4645 
    [ 7.500, 10.000) = 544 
    [10.000, 12.500) = 64 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 74 
    [22.500, 25.000) = 127 
    [25.000, 27.500) = 39 
    [27.500, 30.000) = 1 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.491 ms/op
     p(50.0000) =      3.211 ms/op
     p(90.0000) =      3.633 ms/op
     p(95.0000) =      4.039 ms/op
     p(99.0000) =      5.669 ms/op
     p(99.9000) =     12.344 ms/op
     p(99.9900) =     30.923 ms/op
     p(99.9990) =     32.181 ms/op
     p(99.9999) =     32.309 ms/op
    p(100.0000) =     32.309 ms/op


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
# Warmup Iteration   1: 10.601 ±(99.9%) 0.134 ms/op
# Warmup Iteration   2: 3.870 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.609 ±(99.9%) 0.010 ms/op
Iteration   1: 3.518 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.241 ms/op
                 getUser·p0.50:   3.297 ms/op
                 getUser·p0.90:   4.002 ms/op
                 getUser·p0.95:   4.989 ms/op
                 getUser·p0.99:   7.029 ms/op
                 getUser·p0.999:  21.463 ms/op
                 getUser·p0.9999: 23.953 ms/op
                 getUser·p1.00:   24.478 ms/op

Iteration   2: 3.739 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.118 ms/op
                 getUser·p0.50:   3.473 ms/op
                 getUser·p0.90:   5.071 ms/op
                 getUser·p0.95:   5.349 ms/op
                 getUser·p0.99:   6.396 ms/op
                 getUser·p0.999:  24.854 ms/op
                 getUser·p0.9999: 27.861 ms/op
                 getUser·p1.00:   29.327 ms/op

Iteration   3: 3.520 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.593 ms/op
                 getUser·p0.50:   3.400 ms/op
                 getUser·p0.90:   4.104 ms/op
                 getUser·p0.95:   4.637 ms/op
                 getUser·p0.99:   6.275 ms/op
                 getUser·p0.999:  21.922 ms/op
                 getUser·p0.9999: 27.951 ms/op
                 getUser·p1.00:   28.901 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 267335
  mean =      3.589 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8145 
    [ 2.500,  5.000) = 243299 
    [ 5.000,  7.500) = 14700 
    [ 7.500, 10.000) = 708 
    [10.000, 12.500) = 150 
    [12.500, 15.000) = 29 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 78 
    [22.500, 25.000) = 80 
    [25.000, 27.500) = 106 

  Percentiles, ms/op:
      p(0.0000) =      1.118 ms/op
     p(50.0000) =      3.396 ms/op
     p(90.0000) =      4.293 ms/op
     p(95.0000) =      5.136 ms/op
     p(99.0000) =      6.595 ms/op
     p(99.9000) =     21.714 ms/op
     p(99.9900) =     27.787 ms/op
     p(99.9990) =     28.813 ms/op
     p(99.9999) =     29.327 ms/op
    p(100.0000) =     29.327 ms/op


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
# Warmup Iteration   1: 11.519 ±(99.9%) 0.164 ms/op
# Warmup Iteration   2: 4.558 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.076 ±(99.9%) 0.013 ms/op
Iteration   1: 3.906 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.571 ms/op
                 listUser·p0.50:   3.846 ms/op
                 listUser·p0.90:   4.026 ms/op
                 listUser·p0.95:   4.514 ms/op
                 listUser·p0.99:   6.087 ms/op
                 listUser·p0.999:  21.171 ms/op
                 listUser·p0.9999: 24.229 ms/op
                 listUser·p1.00:   27.034 ms/op

Iteration   2: 3.971 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.903 ms/op
                 listUser·p0.50:   3.793 ms/op
                 listUser·p0.90:   4.342 ms/op
                 listUser·p0.95:   4.612 ms/op
                 listUser·p0.99:   7.168 ms/op
                 listUser·p0.999:  17.122 ms/op
                 listUser·p0.9999: 24.674 ms/op
                 listUser·p1.00:   25.526 ms/op

Iteration   3: 4.017 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.372 ms/op
                 listUser·p0.50:   3.903 ms/op
                 listUser·p0.90:   4.334 ms/op
                 listUser·p0.95:   4.563 ms/op
                 listUser·p0.99:   7.089 ms/op
                 listUser·p0.999:  15.679 ms/op
                 listUser·p0.9999: 25.626 ms/op
                 listUser·p1.00:   25.788 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 242100
  mean =      3.964 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 41 
    [ 2.500,  5.000) = 235292 
    [ 5.000,  7.500) = 4854 
    [ 7.500, 10.000) = 1120 
    [10.000, 12.500) = 259 
    [12.500, 15.000) = 116 
    [15.000, 17.500) = 166 
    [17.500, 20.000) = 108 
    [20.000, 22.500) = 60 
    [22.500, 25.000) = 72 
    [25.000, 27.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      1.571 ms/op
     p(50.0000) =      3.846 ms/op
     p(90.0000) =      4.293 ms/op
     p(95.0000) =      4.563 ms/op
     p(99.0000) =      6.980 ms/op
     p(99.9000) =     17.596 ms/op
     p(99.9900) =     24.635 ms/op
     p(99.9990) =     26.415 ms/op
     p(99.9999) =     27.034 ms/op
    p(100.0000) =     27.034 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.194 ± 0.623  ops/ms
ClientPb.existUser                       thrpt       3   9.725 ± 1.241  ops/ms
ClientPb.getUser                         thrpt       3   9.202 ± 2.496  ops/ms
ClientPb.listUser                        thrpt       3   8.099 ± 2.022  ops/ms
ClientPb.createUser                       avgt       3   3.364 ± 0.546   ms/op
ClientPb.existUser                        avgt       3   3.301 ± 0.591   ms/op
ClientPb.getUser                          avgt       3   3.444 ± 1.252   ms/op
ClientPb.listUser                         avgt       3   3.946 ± 2.091   ms/op
ClientPb.createUser                     sample  278918   3.439 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.532           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.346           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.858           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.252           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.898           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.957           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.918           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.474           ms/op
ClientPb.existUser                      sample  290734   3.301 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.491           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.211           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.633           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.039           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.669           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.344           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.923           ms/op
ClientPb.existUser:existUser·p1.00      sample          32.309           ms/op
ClientPb.getUser                        sample  267335   3.589 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.118           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.396           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.293           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.136           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.595           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.714           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.787           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.327           ms/op
ClientPb.listUser                       sample  242100   3.964 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.571           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.846           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.293           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.563           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.980           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.596           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.635           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.034           ms/op
