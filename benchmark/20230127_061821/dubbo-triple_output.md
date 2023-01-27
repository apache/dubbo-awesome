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
# Warmup Iteration   1: 2.740 ops/ms
# Warmup Iteration   2: 6.162 ops/ms
# Warmup Iteration   3: 9.138 ops/ms
Iteration   1: 9.762 ops/ms
Iteration   2: 9.975 ops/ms
Iteration   3: 10.021 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.919 ±(99.9%) 2.523 ops/ms [Average]
  (min, avg, max) = (9.762, 9.919, 10.021), stdev = 0.138
  CI (99.9%): [7.396, 12.442] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:05
# Fork: 1 of 1
# Warmup Iteration   1: 3.839 ops/ms
# Warmup Iteration   2: 9.699 ops/ms
# Warmup Iteration   3: 10.258 ops/ms
Iteration   1: 10.116 ops/ms
Iteration   2: 10.399 ops/ms
Iteration   3: 10.711 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.408 ±(99.9%) 5.432 ops/ms [Average]
  (min, avg, max) = (10.116, 10.408, 10.711), stdev = 0.298
  CI (99.9%): [4.976, 15.840] (assumes normal distribution)


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
# Warmup Iteration   1: 3.938 ops/ms
# Warmup Iteration   2: 9.113 ops/ms
# Warmup Iteration   3: 9.994 ops/ms
Iteration   1: 10.138 ops/ms
Iteration   2: 10.194 ops/ms
Iteration   3: 9.651 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.994 ±(99.9%) 5.452 ops/ms [Average]
  (min, avg, max) = (9.651, 9.994, 10.194), stdev = 0.299
  CI (99.9%): [4.542, 15.447] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.614 ops/ms
# Warmup Iteration   2: 7.890 ops/ms
# Warmup Iteration   3: 8.143 ops/ms
Iteration   1: 8.166 ops/ms
Iteration   2: 8.690 ops/ms
Iteration   3: 8.698 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.518 ±(99.9%) 5.558 ops/ms [Average]
  (min, avg, max) = (8.166, 8.518, 8.698), stdev = 0.305
  CI (99.9%): [2.960, 14.076] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 8.286 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.592 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.392 ±(99.9%) 0.001 ms/op
Iteration   1: 3.182 ±(99.9%) 0.005 ms/op
Iteration   2: 3.131 ±(99.9%) 0.004 ms/op
Iteration   3: 3.045 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.119 ±(99.9%) 1.266 ms/op [Average]
  (min, avg, max) = (3.045, 3.119, 3.182), stdev = 0.069
  CI (99.9%): [1.854, 4.385] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 6.299 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.249 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.130 ±(99.9%) 0.005 ms/op
Iteration   1: 3.041 ±(99.9%) 0.006 ms/op
Iteration   2: 2.929 ±(99.9%) 0.006 ms/op
Iteration   3: 3.016 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.995 ±(99.9%) 1.070 ms/op [Average]
  (min, avg, max) = (2.929, 2.995, 3.041), stdev = 0.059
  CI (99.9%): [1.925, 4.065] (assumes normal distribution)


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
# Warmup Iteration   1: 6.920 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.246 ±(99.9%) 0.001 ms/op
# Warmup Iteration   3: 3.244 ±(99.9%) 0.006 ms/op
Iteration   1: 3.268 ±(99.9%) 0.006 ms/op
Iteration   2: 3.063 ±(99.9%) 0.004 ms/op
Iteration   3: 3.120 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.151 ±(99.9%) 1.933 ms/op [Average]
  (min, avg, max) = (3.063, 3.151, 3.268), stdev = 0.106
  CI (99.9%): [1.217, 5.084] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 9.295 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 4.136 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.861 ±(99.9%) 0.004 ms/op
Iteration   1: 3.721 ±(99.9%) 0.006 ms/op
Iteration   2: 3.715 ±(99.9%) 0.007 ms/op
Iteration   3: 3.788 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.741 ±(99.9%) 0.745 ms/op [Average]
  (min, avg, max) = (3.715, 3.741, 3.788), stdev = 0.041
  CI (99.9%): [2.996, 4.486] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 7.877 ±(99.9%) 0.085 ms/op
# Warmup Iteration   2: 3.535 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.105 ±(99.9%) 0.008 ms/op
Iteration   1: 3.227 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.296 ms/op
                 createUser·p0.50:   3.109 ms/op
                 createUser·p0.90:   3.672 ms/op
                 createUser·p0.95:   4.456 ms/op
                 createUser·p0.99:   6.365 ms/op
                 createUser·p0.999:  10.468 ms/op
                 createUser·p0.9999: 21.046 ms/op
                 createUser·p1.00:   21.725 ms/op

Iteration   2: 3.209 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.021 ms/op
                 createUser·p0.50:   3.072 ms/op
                 createUser·p0.90:   3.637 ms/op
                 createUser·p0.95:   4.035 ms/op
                 createUser·p0.99:   5.706 ms/op
                 createUser·p0.999:  14.435 ms/op
                 createUser·p0.9999: 22.120 ms/op
                 createUser·p1.00:   22.512 ms/op

Iteration   3: 3.092 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.992 ms/op
                 createUser·p0.50:   2.978 ms/op
                 createUser·p0.90:   3.445 ms/op
                 createUser·p0.95:   3.662 ms/op
                 createUser·p0.99:   5.136 ms/op
                 createUser·p0.999:  15.474 ms/op
                 createUser·p0.9999: 20.567 ms/op
                 createUser·p1.00:   21.103 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 302285
  mean =      3.175 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13169 
    [ 2.500,  5.000) = 281220 
    [ 5.000,  7.500) = 6828 
    [ 7.500, 10.000) = 643 
    [10.000, 12.500) = 73 
    [12.500, 15.000) = 53 
    [15.000, 17.500) = 102 
    [17.500, 20.000) = 107 
    [20.000, 22.500) = 89 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.992 ms/op
     p(50.0000) =      3.031 ms/op
     p(90.0000) =      3.576 ms/op
     p(95.0000) =      3.957 ms/op
     p(99.0000) =      5.792 ms/op
     p(99.9000) =     14.490 ms/op
     p(99.9900) =     21.423 ms/op
     p(99.9990) =     22.478 ms/op
     p(99.9999) =     22.512 ms/op
    p(100.0000) =     22.512 ms/op


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
# Warmup Iteration   1: 7.032 ±(99.9%) 0.082 ms/op
# Warmup Iteration   2: 3.456 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.216 ±(99.9%) 0.009 ms/op
Iteration   1: 3.092 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.284 ms/op
                 existUser·p0.50:   3.052 ms/op
                 existUser·p0.90:   3.322 ms/op
                 existUser·p0.95:   3.699 ms/op
                 existUser·p0.99:   5.448 ms/op
                 existUser·p0.999:  9.692 ms/op
                 existUser·p0.9999: 19.364 ms/op
                 existUser·p1.00:   20.283 ms/op

Iteration   2: 3.130 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.194 ms/op
                 existUser·p0.50:   3.113 ms/op
                 existUser·p0.90:   3.400 ms/op
                 existUser·p0.95:   3.764 ms/op
                 existUser·p0.99:   5.333 ms/op
                 existUser·p0.999:  9.454 ms/op
                 existUser·p0.9999: 27.223 ms/op
                 existUser·p1.00:   27.558 ms/op

Iteration   3: 3.088 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.593 ms/op
                 existUser·p0.50:   3.035 ms/op
                 existUser·p0.90:   3.322 ms/op
                 existUser·p0.95:   3.555 ms/op
                 existUser·p0.99:   5.582 ms/op
                 existUser·p0.999:  13.634 ms/op
                 existUser·p0.9999: 26.957 ms/op
                 existUser·p1.00:   27.591 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 309202
  mean =      3.103 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25428 
    [ 2.500,  5.000) = 277775 
    [ 5.000,  7.500) = 5351 
    [ 7.500, 10.000) = 260 
    [10.000, 12.500) = 63 
    [12.500, 15.000) = 37 
    [15.000, 17.500) = 44 
    [17.500, 20.000) = 96 
    [20.000, 22.500) = 84 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 58 

  Percentiles, ms/op:
      p(0.0000) =      1.194 ms/op
     p(50.0000) =      3.072 ms/op
     p(90.0000) =      3.346 ms/op
     p(95.0000) =      3.670 ms/op
     p(99.0000) =      5.399 ms/op
     p(99.9000) =     12.976 ms/op
     p(99.9900) =     26.364 ms/op
     p(99.9990) =     27.555 ms/op
     p(99.9999) =     27.591 ms/op
    p(100.0000) =     27.591 ms/op


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
# Warmup Iteration   1: 7.502 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 3.348 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.270 ±(99.9%) 0.011 ms/op
Iteration   1: 3.110 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.812 ms/op
                 getUser·p0.50:   2.994 ms/op
                 getUser·p0.90:   3.371 ms/op
                 getUser·p0.95:   3.645 ms/op
                 getUser·p0.99:   5.841 ms/op
                 getUser·p0.999:  14.400 ms/op
                 getUser·p0.9999: 20.157 ms/op
                 getUser·p1.00:   20.873 ms/op

Iteration   2: 3.134 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.360 ms/op
                 getUser·p0.50:   3.002 ms/op
                 getUser·p0.90:   3.387 ms/op
                 getUser·p0.95:   3.756 ms/op
                 getUser·p0.99:   6.226 ms/op
                 getUser·p0.999:  11.491 ms/op
                 getUser·p0.9999: 21.791 ms/op
                 getUser·p1.00:   22.741 ms/op

Iteration   3: 3.103 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.151 ms/op
                 getUser·p0.50:   2.998 ms/op
                 getUser·p0.90:   3.351 ms/op
                 getUser·p0.95:   3.584 ms/op
                 getUser·p0.99:   5.472 ms/op
                 getUser·p0.999:  9.519 ms/op
                 getUser·p0.9999: 18.832 ms/op
                 getUser·p1.00:   20.021 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 307830
  mean =      3.115 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9070 
    [ 2.500,  5.000) = 292256 
    [ 5.000,  7.500) = 5450 
    [ 7.500, 10.000) = 637 
    [10.000, 12.500) = 99 
    [12.500, 15.000) = 58 
    [15.000, 17.500) = 55 
    [17.500, 20.000) = 145 
    [20.000, 22.500) = 57 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.812 ms/op
     p(50.0000) =      2.998 ms/op
     p(90.0000) =      3.371 ms/op
     p(95.0000) =      3.654 ms/op
     p(99.0000) =      5.743 ms/op
     p(99.9000) =     12.800 ms/op
     p(99.9900) =     20.684 ms/op
     p(99.9990) =     22.541 ms/op
     p(99.9999) =     22.741 ms/op
    p(100.0000) =     22.741 ms/op


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
# Warmup Iteration   1: 8.773 ±(99.9%) 0.109 ms/op
# Warmup Iteration   2: 4.128 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.754 ±(99.9%) 0.012 ms/op
Iteration   1: 3.642 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.659 ms/op
                 listUser·p0.50:   3.551 ms/op
                 listUser·p0.90:   3.908 ms/op
                 listUser·p0.95:   4.202 ms/op
                 listUser·p0.99:   6.608 ms/op
                 listUser·p0.999:  14.486 ms/op
                 listUser·p0.9999: 17.742 ms/op
                 listUser·p1.00:   19.071 ms/op

Iteration   2: 3.672 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.040 ms/op
                 listUser·p0.50:   3.596 ms/op
                 listUser·p0.90:   3.949 ms/op
                 listUser·p0.95:   4.342 ms/op
                 listUser·p0.99:   6.799 ms/op
                 listUser·p0.999:  12.911 ms/op
                 listUser·p0.9999: 16.237 ms/op
                 listUser·p1.00:   16.450 ms/op

Iteration   3: 3.842 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.134 ms/op
                 listUser·p0.50:   3.744 ms/op
                 listUser·p0.90:   4.112 ms/op
                 listUser·p0.95:   4.350 ms/op
                 listUser·p0.99:   7.533 ms/op
                 listUser·p0.999:  14.221 ms/op
                 listUser·p0.9999: 22.839 ms/op
                 listUser·p1.00:   22.905 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 258103
  mean =      3.716 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 88 
    [ 2.500,  5.000) = 251165 
    [ 5.000,  7.500) = 4921 
    [ 7.500, 10.000) = 1298 
    [10.000, 12.500) = 256 
    [12.500, 15.000) = 203 
    [15.000, 17.500) = 90 
    [17.500, 20.000) = 62 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.659 ms/op
     p(50.0000) =      3.613 ms/op
     p(90.0000) =      4.043 ms/op
     p(95.0000) =      4.301 ms/op
     p(99.0000) =      6.955 ms/op
     p(99.9000) =     13.826 ms/op
     p(99.9900) =     19.857 ms/op
     p(99.9990) =     22.886 ms/op
     p(99.9999) =     22.905 ms/op
    p(100.0000) =     22.905 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.919 ± 2.523  ops/ms
ClientPb.existUser                       thrpt       3  10.408 ± 5.432  ops/ms
ClientPb.getUser                         thrpt       3   9.994 ± 5.452  ops/ms
ClientPb.listUser                        thrpt       3   8.518 ± 5.558  ops/ms
ClientPb.createUser                       avgt       3   3.119 ± 1.266   ms/op
ClientPb.existUser                        avgt       3   2.995 ± 1.070   ms/op
ClientPb.getUser                          avgt       3   3.151 ± 1.933   ms/op
ClientPb.listUser                         avgt       3   3.741 ± 0.745   ms/op
ClientPb.createUser                     sample  302285   3.175 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.992           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.031           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.576           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.957           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.792           ms/op
ClientPb.createUser:createUser·p0.999   sample          14.490           ms/op
ClientPb.createUser:createUser·p0.9999  sample          21.423           ms/op
ClientPb.createUser:createUser·p1.00    sample          22.512           ms/op
ClientPb.existUser                      sample  309202   3.103 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.194           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.072           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.346           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.670           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.399           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.976           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.364           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.591           ms/op
ClientPb.getUser                        sample  307830   3.115 ± 0.004   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.812           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.998           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.371           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.654           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.743           ms/op
ClientPb.getUser:getUser·p0.999         sample          12.800           ms/op
ClientPb.getUser:getUser·p0.9999        sample          20.684           ms/op
ClientPb.getUser:getUser·p1.00          sample          22.741           ms/op
ClientPb.listUser                       sample  258103   3.716 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.659           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.613           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.043           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.301           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.955           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.826           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.857           ms/op
ClientPb.listUser:listUser·p1.00        sample          22.905           ms/op
