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
# Warmup Iteration   1: 1.824 ops/ms
# Warmup Iteration   2: 4.364 ops/ms
# Warmup Iteration   3: 7.279 ops/ms
Iteration   1: 7.534 ops/ms
Iteration   2: 7.851 ops/ms
Iteration   3: 8.119 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.835 ±(99.9%) 5.342 ops/ms [Average]
  (min, avg, max) = (7.534, 7.835, 8.119), stdev = 0.293
  CI (99.9%): [2.493, 13.177] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:09
# Fork: 1 of 1
# Warmup Iteration   1: 2.519 ops/ms
# Warmup Iteration   2: 8.145 ops/ms
# Warmup Iteration   3: 9.064 ops/ms
Iteration   1: 9.415 ops/ms
Iteration   2: 8.783 ops/ms
Iteration   3: 9.339 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.179 ±(99.9%) 6.292 ops/ms [Average]
  (min, avg, max) = (8.783, 9.179, 9.415), stdev = 0.345
  CI (99.9%): [2.887, 15.471] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 2.493 ops/ms
# Warmup Iteration   2: 7.183 ops/ms
# Warmup Iteration   3: 8.690 ops/ms
Iteration   1: 8.656 ops/ms
Iteration   2: 8.420 ops/ms
Iteration   3: 8.719 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.598 ±(99.9%) 2.877 ops/ms [Average]
  (min, avg, max) = (8.420, 8.598, 8.719), stdev = 0.158
  CI (99.9%): [5.722, 11.475] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 2.077 ops/ms
# Warmup Iteration   2: 6.065 ops/ms
# Warmup Iteration   3: 6.839 ops/ms
Iteration   1: 6.701 ops/ms
Iteration   2: 6.895 ops/ms
Iteration   3: 6.861 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.819 ±(99.9%) 1.891 ops/ms [Average]
  (min, avg, max) = (6.701, 6.819, 6.895), stdev = 0.104
  CI (99.9%): [4.928, 8.709] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 14.049 ±(99.9%) 0.066 ms/op
# Warmup Iteration   2: 5.111 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.976 ±(99.9%) 0.010 ms/op
Iteration   1: 3.864 ±(99.9%) 0.005 ms/op
Iteration   2: 3.943 ±(99.9%) 0.006 ms/op
Iteration   3: 3.958 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.921 ±(99.9%) 0.923 ms/op [Average]
  (min, avg, max) = (3.864, 3.921, 3.958), stdev = 0.051
  CI (99.9%): [2.999, 4.844] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 11.237 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 4.239 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.779 ±(99.9%) 0.010 ms/op
Iteration   1: 3.710 ±(99.9%) 0.011 ms/op
Iteration   2: 3.773 ±(99.9%) 0.010 ms/op
Iteration   3: 3.728 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.737 ±(99.9%) 0.599 ms/op [Average]
  (min, avg, max) = (3.710, 3.737, 3.773), stdev = 0.033
  CI (99.9%): [3.138, 4.336] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 13.229 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 4.085 ±(99.9%) 0.001 ms/op
# Warmup Iteration   3: 3.779 ±(99.9%) 0.007 ms/op
Iteration   1: 3.781 ±(99.9%) 0.008 ms/op
Iteration   2: 3.763 ±(99.9%) 0.004 ms/op
Iteration   3: 3.576 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.707 ±(99.9%) 2.070 ms/op [Average]
  (min, avg, max) = (3.576, 3.707, 3.781), stdev = 0.113
  CI (99.9%): [1.637, 5.777] (assumes normal distribution)


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
# Warmup Iteration   1: 13.228 ±(99.9%) 0.066 ms/op
# Warmup Iteration   2: 4.837 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.521 ±(99.9%) 0.009 ms/op
Iteration   1: 4.364 ±(99.9%) 0.012 ms/op
Iteration   2: 4.622 ±(99.9%) 0.005 ms/op
Iteration   3: 4.660 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.549 ±(99.9%) 2.941 ms/op [Average]
  (min, avg, max) = (4.364, 4.549, 4.660), stdev = 0.161
  CI (99.9%): [1.608, 7.490] (assumes normal distribution)


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
# Warmup Iteration   1: 12.291 ±(99.9%) 0.181 ms/op
# Warmup Iteration   2: 6.693 ±(99.9%) 0.049 ms/op
# Warmup Iteration   3: 4.702 ±(99.9%) 0.026 ms/op
Iteration   1: 4.118 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.731 ms/op
                 createUser·p0.50:   3.858 ms/op
                 createUser·p0.90:   4.923 ms/op
                 createUser·p0.95:   6.021 ms/op
                 createUser·p0.99:   8.389 ms/op
                 createUser·p0.999:  15.595 ms/op
                 createUser·p0.9999: 26.018 ms/op
                 createUser·p1.00:   27.263 ms/op

Iteration   2: 4.178 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   1.534 ms/op
                 createUser·p0.50:   3.912 ms/op
                 createUser·p0.90:   4.940 ms/op
                 createUser·p0.95:   5.644 ms/op
                 createUser·p0.99:   8.020 ms/op
                 createUser·p0.999:  26.425 ms/op
                 createUser·p0.9999: 38.295 ms/op
                 createUser·p1.00:   42.140 ms/op

Iteration   3: 4.008 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.610 ms/op
                 createUser·p0.50:   3.867 ms/op
                 createUser·p0.90:   4.637 ms/op
                 createUser·p0.95:   4.973 ms/op
                 createUser·p0.99:   6.988 ms/op
                 createUser·p0.999:  17.302 ms/op
                 createUser·p0.9999: 30.836 ms/op
                 createUser·p1.00:   33.194 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 234122
  mean =      4.100 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 216358 
    [ 5.000, 10.000) = 16955 
    [10.000, 15.000) = 504 
    [15.000, 20.000) = 81 
    [20.000, 25.000) = 35 
    [25.000, 30.000) = 121 
    [30.000, 35.000) = 39 
    [35.000, 40.000) = 26 
    [40.000, 45.000) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.610 ms/op
     p(50.0000) =      3.883 ms/op
     p(90.0000) =      4.825 ms/op
     p(95.0000) =      5.423 ms/op
     p(99.0000) =      7.913 ms/op
     p(99.9000) =     17.596 ms/op
     p(99.9900) =     36.418 ms/op
     p(99.9990) =     41.058 ms/op
     p(99.9999) =     42.140 ms/op
    p(100.0000) =     42.140 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 13.682 ±(99.9%) 0.183 ms/op
# Warmup Iteration   2: 4.704 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.104 ±(99.9%) 0.012 ms/op
Iteration   1: 4.147 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.530 ms/op
                 existUser·p0.50:   3.875 ms/op
                 existUser·p0.90:   5.079 ms/op
                 existUser·p0.95:   5.775 ms/op
                 existUser·p0.99:   7.774 ms/op
                 existUser·p0.999:  15.073 ms/op
                 existUser·p0.9999: 30.015 ms/op
                 existUser·p1.00:   30.802 ms/op

Iteration   2: 3.981 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.421 ms/op
                 existUser·p0.50:   3.777 ms/op
                 existUser·p0.90:   4.522 ms/op
                 existUser·p0.95:   5.341 ms/op
                 existUser·p0.99:   8.290 ms/op
                 existUser·p0.999:  11.906 ms/op
                 existUser·p0.9999: 28.596 ms/op
                 existUser·p1.00:   30.212 ms/op

Iteration   3: 4.022 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.348 ms/op
                 existUser·p0.50:   3.822 ms/op
                 existUser·p0.90:   4.768 ms/op
                 existUser·p0.95:   5.130 ms/op
                 existUser·p0.99:   6.660 ms/op
                 existUser·p0.999:  28.279 ms/op
                 existUser·p0.9999: 32.048 ms/op
                 existUser·p1.00:   32.899 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 237094
  mean =      4.049 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 415 
    [ 2.500,  5.000) = 217877 
    [ 5.000,  7.500) = 15698 
    [ 7.500, 10.000) = 2410 
    [10.000, 12.500) = 405 
    [12.500, 15.000) = 44 
    [15.000, 17.500) = 19 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 61 
    [27.500, 30.000) = 70 
    [30.000, 32.500) = 58 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.348 ms/op
     p(50.0000) =      3.813 ms/op
     p(90.0000) =      4.825 ms/op
     p(95.0000) =      5.399 ms/op
     p(99.0000) =      7.913 ms/op
     p(99.9000) =     15.090 ms/op
     p(99.9900) =     31.303 ms/op
     p(99.9990) =     32.818 ms/op
     p(99.9999) =     32.899 ms/op
    p(100.0000) =     32.899 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 12.419 ±(99.9%) 0.164 ms/op
# Warmup Iteration   2: 4.768 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.149 ±(99.9%) 0.015 ms/op
Iteration   1: 4.005 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.430 ms/op
                 getUser·p0.50:   3.736 ms/op
                 getUser·p0.90:   4.497 ms/op
                 getUser·p0.95:   6.349 ms/op
                 getUser·p0.99:   8.143 ms/op
                 getUser·p0.999:  15.471 ms/op
                 getUser·p0.9999: 26.379 ms/op
                 getUser·p1.00:   26.673 ms/op

Iteration   2: 3.831 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.497 ms/op
                 getUser·p0.50:   3.715 ms/op
                 getUser·p0.90:   4.202 ms/op
                 getUser·p0.95:   4.489 ms/op
                 getUser·p0.99:   6.578 ms/op
                 getUser·p0.999:  23.200 ms/op
                 getUser·p0.9999: 25.515 ms/op
                 getUser·p1.00:   26.509 ms/op

Iteration   3: 3.820 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.401 ms/op
                 getUser·p0.50:   3.699 ms/op
                 getUser·p0.90:   4.284 ms/op
                 getUser·p0.95:   4.555 ms/op
                 getUser·p0.99:   6.332 ms/op
                 getUser·p0.999:  10.411 ms/op
                 getUser·p0.9999: 29.491 ms/op
                 getUser·p1.00:   31.097 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 246965
  mean =      3.884 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 196 
    [ 2.500,  5.000) = 235826 
    [ 5.000,  7.500) = 8150 
    [ 7.500, 10.000) = 2209 
    [10.000, 12.500) = 315 
    [12.500, 15.000) = 14 
    [15.000, 17.500) = 17 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 38 
    [22.500, 25.000) = 101 
    [25.000, 27.500) = 47 
    [27.500, 30.000) = 26 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.401 ms/op
     p(50.0000) =      3.715 ms/op
     p(90.0000) =      4.293 ms/op
     p(95.0000) =      4.809 ms/op
     p(99.0000) =      7.660 ms/op
     p(99.9000) =     15.893 ms/op
     p(99.9900) =     28.319 ms/op
     p(99.9990) =     30.278 ms/op
     p(99.9999) =     31.097 ms/op
    p(100.0000) =     31.097 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 14.504 ±(99.9%) 0.217 ms/op
# Warmup Iteration   2: 5.383 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 4.772 ±(99.9%) 0.017 ms/op
Iteration   1: 4.523 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.464 ms/op
                 listUser·p0.50:   4.350 ms/op
                 listUser·p0.90:   5.038 ms/op
                 listUser·p0.95:   5.349 ms/op
                 listUser·p0.99:   8.249 ms/op
                 listUser·p0.999:  22.151 ms/op
                 listUser·p0.9999: 25.229 ms/op
                 listUser·p1.00:   26.083 ms/op

Iteration   2: 4.716 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   2.042 ms/op
                 listUser·p0.50:   4.522 ms/op
                 listUser·p0.90:   5.063 ms/op
                 listUser·p0.95:   5.505 ms/op
                 listUser·p0.99:   9.552 ms/op
                 listUser·p0.999:  22.678 ms/op
                 listUser·p0.9999: 26.698 ms/op
                 listUser·p1.00:   27.623 ms/op

Iteration   3: 4.769 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   2.687 ms/op
                 listUser·p0.50:   4.579 ms/op
                 listUser·p0.90:   5.308 ms/op
                 listUser·p0.95:   5.988 ms/op
                 listUser·p0.99:   9.339 ms/op
                 listUser·p0.999:  17.036 ms/op
                 listUser·p0.9999: 21.263 ms/op
                 listUser·p1.00:   21.594 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 205629
  mean =      4.667 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18 
    [ 2.500,  5.000) = 179470 
    [ 5.000,  7.500) = 21417 
    [ 7.500, 10.000) = 3243 
    [10.000, 12.500) = 778 
    [12.500, 15.000) = 242 
    [15.000, 17.500) = 155 
    [17.500, 20.000) = 55 
    [20.000, 22.500) = 120 
    [22.500, 25.000) = 75 
    [25.000, 27.500) = 55 

  Percentiles, ms/op:
      p(0.0000) =      1.464 ms/op
     p(50.0000) =      4.497 ms/op
     p(90.0000) =      5.128 ms/op
     p(95.0000) =      5.603 ms/op
     p(99.0000) =      9.110 ms/op
     p(99.9000) =     21.168 ms/op
     p(99.9900) =     26.116 ms/op
     p(99.9990) =     27.392 ms/op
     p(99.9999) =     27.623 ms/op
    p(100.0000) =     27.623 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.835 ± 5.342  ops/ms
ClientPb.existUser                       thrpt       3   9.179 ± 6.292  ops/ms
ClientPb.getUser                         thrpt       3   8.598 ± 2.877  ops/ms
ClientPb.listUser                        thrpt       3   6.819 ± 1.891  ops/ms
ClientPb.createUser                       avgt       3   3.921 ± 0.923   ms/op
ClientPb.existUser                        avgt       3   3.737 ± 0.599   ms/op
ClientPb.getUser                          avgt       3   3.707 ± 2.070   ms/op
ClientPb.listUser                         avgt       3   4.549 ± 2.941   ms/op
ClientPb.createUser                     sample  234122   4.100 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.610           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.883           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.825           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.423           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.913           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.596           ms/op
ClientPb.createUser:createUser·p0.9999  sample          36.418           ms/op
ClientPb.createUser:createUser·p1.00    sample          42.140           ms/op
ClientPb.existUser                      sample  237094   4.049 ± 0.008   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.348           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.813           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.825           ms/op
ClientPb.existUser:existUser·p0.95      sample           5.399           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.913           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.090           ms/op
ClientPb.existUser:existUser·p0.9999    sample          31.303           ms/op
ClientPb.existUser:existUser·p1.00      sample          32.899           ms/op
ClientPb.getUser                        sample  246965   3.884 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.401           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.715           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.293           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.809           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.660           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.893           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.319           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.097           ms/op
ClientPb.listUser                       sample  205629   4.667 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.464           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.497           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.128           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.603           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.110           ms/op
ClientPb.listUser:listUser·p0.999       sample          21.168           ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.116           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.623           ms/op
