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
# Warmup Iteration   1: 2.513 ops/ms
# Warmup Iteration   2: 5.769 ops/ms
# Warmup Iteration   3: 9.309 ops/ms
Iteration   1: 9.715 ops/ms
Iteration   2: 10.142 ops/ms
Iteration   3: 9.559 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.806 ±(99.9%) 5.508 ops/ms [Average]
  (min, avg, max) = (9.559, 9.806, 10.142), stdev = 0.302
  CI (99.9%): [4.298, 15.313] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.952 ops/ms
# Warmup Iteration   2: 9.374 ops/ms
# Warmup Iteration   3: 9.975 ops/ms
Iteration   1: 10.421 ops/ms
Iteration   2: 9.812 ops/ms
Iteration   3: 10.708 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.314 ±(99.9%) 8.342 ops/ms [Average]
  (min, avg, max) = (9.812, 10.314, 10.708), stdev = 0.457
  CI (99.9%): [1.971, 18.656] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.538 ops/ms
# Warmup Iteration   2: 8.921 ops/ms
# Warmup Iteration   3: 10.050 ops/ms
Iteration   1: 9.932 ops/ms
Iteration   2: 9.958 ops/ms
Iteration   3: 10.346 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.079 ±(99.9%) 4.233 ops/ms [Average]
  (min, avg, max) = (9.932, 10.079, 10.346), stdev = 0.232
  CI (99.9%): [5.846, 14.312] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.659 ops/ms
# Warmup Iteration   2: 7.876 ops/ms
# Warmup Iteration   3: 8.265 ops/ms
Iteration   1: 8.667 ops/ms
Iteration   2: 8.490 ops/ms
Iteration   3: 8.730 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.629 ±(99.9%) 2.267 ops/ms [Average]
  (min, avg, max) = (8.490, 8.629, 8.730), stdev = 0.124
  CI (99.9%): [6.362, 10.897] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 8.993 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.658 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.320 ±(99.9%) 0.001 ms/op
Iteration   1: 3.190 ±(99.9%) 0.002 ms/op
Iteration   2: 3.365 ±(99.9%) 0.006 ms/op
Iteration   3: 3.158 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.237 ±(99.9%) 2.029 ms/op [Average]
  (min, avg, max) = (3.158, 3.237, 3.365), stdev = 0.111
  CI (99.9%): [1.208, 5.267] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 7.952 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.490 ±(99.9%) 0.001 ms/op
# Warmup Iteration   3: 3.320 ±(99.9%) 0.007 ms/op
Iteration   1: 3.086 ±(99.9%) 0.005 ms/op
Iteration   2: 3.101 ±(99.9%) 0.008 ms/op
Iteration   3: 3.118 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.102 ±(99.9%) 0.291 ms/op [Average]
  (min, avg, max) = (3.086, 3.102, 3.118), stdev = 0.016
  CI (99.9%): [2.811, 3.393] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 7.480 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.360 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.392 ±(99.9%) 0.004 ms/op
Iteration   1: 3.238 ±(99.9%) 0.003 ms/op
Iteration   2: 3.275 ±(99.9%) 0.004 ms/op
Iteration   3: 3.212 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.242 ±(99.9%) 0.584 ms/op [Average]
  (min, avg, max) = (3.212, 3.242, 3.275), stdev = 0.032
  CI (99.9%): [2.658, 3.826] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 8.298 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.988 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.831 ±(99.9%) 0.009 ms/op
Iteration   1: 3.623 ±(99.9%) 0.012 ms/op
Iteration   2: 3.724 ±(99.9%) 0.004 ms/op
Iteration   3: 3.741 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.696 ±(99.9%) 1.158 ms/op [Average]
  (min, avg, max) = (3.623, 3.696, 3.741), stdev = 0.063
  CI (99.9%): [2.538, 4.854] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 8.738 ±(99.9%) 0.096 ms/op
# Warmup Iteration   2: 3.748 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.298 ±(99.9%) 0.009 ms/op
Iteration   1: 3.166 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.971 ms/op
                 createUser·p0.50:   3.076 ms/op
                 createUser·p0.90:   3.510 ms/op
                 createUser·p0.95:   3.736 ms/op
                 createUser·p0.99:   5.513 ms/op
                 createUser·p0.999:  17.334 ms/op
                 createUser·p0.9999: 25.968 ms/op
                 createUser·p1.00:   26.411 ms/op

Iteration   2: 3.289 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.484 ms/op
                 createUser·p0.50:   3.269 ms/op
                 createUser·p0.90:   3.678 ms/op
                 createUser·p0.95:   3.990 ms/op
                 createUser·p0.99:   5.366 ms/op
                 createUser·p0.999:  10.285 ms/op
                 createUser·p0.9999: 22.086 ms/op
                 createUser·p1.00:   22.512 ms/op

Iteration   3: 3.167 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.114 ms/op
                 createUser·p0.50:   3.072 ms/op
                 createUser·p0.90:   3.473 ms/op
                 createUser·p0.95:   3.793 ms/op
                 createUser·p0.99:   5.292 ms/op
                 createUser·p0.999:  16.500 ms/op
                 createUser·p0.9999: 20.873 ms/op
                 createUser·p1.00:   21.365 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 299445
  mean =      3.206 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19094 
    [ 2.500,  5.000) = 275073 
    [ 5.000,  7.500) = 4585 
    [ 7.500, 10.000) = 313 
    [10.000, 12.500) = 28 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 105 
    [17.500, 20.000) = 129 
    [20.000, 22.500) = 68 
    [22.500, 25.000) = 34 
    [25.000, 27.500) = 16 

  Percentiles, ms/op:
      p(0.0000) =      0.484 ms/op
     p(50.0000) =      3.170 ms/op
     p(90.0000) =      3.547 ms/op
     p(95.0000) =      3.850 ms/op
     p(99.0000) =      5.407 ms/op
     p(99.9000) =     17.025 ms/op
     p(99.9900) =     24.150 ms/op
     p(99.9990) =     26.378 ms/op
     p(99.9999) =     26.411 ms/op
    p(100.0000) =     26.411 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 6.872 ±(99.9%) 0.092 ms/op
# Warmup Iteration   2: 3.371 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.097 ±(99.9%) 0.007 ms/op
Iteration   1: 3.039 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.346 ms/op
                 existUser·p0.50:   3.060 ms/op
                 existUser·p0.90:   3.170 ms/op
                 existUser·p0.95:   3.314 ms/op
                 existUser·p0.99:   5.038 ms/op
                 existUser·p0.999:  9.945 ms/op
                 existUser·p0.9999: 20.087 ms/op
                 existUser·p1.00:   21.234 ms/op

Iteration   2: 3.078 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.311 ms/op
                 existUser·p0.50:   3.076 ms/op
                 existUser·p0.90:   3.240 ms/op
                 existUser·p0.95:   3.432 ms/op
                 existUser·p0.99:   5.341 ms/op
                 existUser·p0.999:  14.598 ms/op
                 existUser·p0.9999: 23.701 ms/op
                 existUser·p1.00:   24.183 ms/op

Iteration   3: 3.070 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.141 ms/op
                 existUser·p0.50:   3.080 ms/op
                 existUser·p0.90:   3.195 ms/op
                 existUser·p0.95:   3.437 ms/op
                 existUser·p0.99:   5.169 ms/op
                 existUser·p0.999:  9.830 ms/op
                 existUser·p0.9999: 21.056 ms/op
                 existUser·p1.00:   22.610 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 313336
  mean =      3.062 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 32289 
    [ 2.500,  5.000) = 277028 
    [ 5.000,  7.500) = 3297 
    [ 7.500, 10.000) = 343 
    [10.000, 12.500) = 41 
    [12.500, 15.000) = 82 
    [15.000, 17.500) = 15 
    [17.500, 20.000) = 142 
    [20.000, 22.500) = 72 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.141 ms/op
     p(50.0000) =      3.072 ms/op
     p(90.0000) =      3.211 ms/op
     p(95.0000) =      3.400 ms/op
     p(99.0000) =      5.161 ms/op
     p(99.9000) =     13.156 ms/op
     p(99.9900) =     21.791 ms/op
     p(99.9990) =     23.916 ms/op
     p(99.9999) =     24.183 ms/op
    p(100.0000) =     24.183 ms/op


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
# Warmup Iteration   1: 7.491 ±(99.9%) 0.096 ms/op
# Warmup Iteration   2: 3.597 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.389 ±(99.9%) 0.010 ms/op
Iteration   1: 3.369 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.425 ms/op
                 getUser·p0.50:   3.158 ms/op
                 getUser·p0.90:   4.293 ms/op
                 getUser·p0.95:   4.948 ms/op
                 getUser·p0.99:   6.136 ms/op
                 getUser·p0.999:  17.574 ms/op
                 getUser·p0.9999: 20.694 ms/op
                 getUser·p1.00:   21.823 ms/op

Iteration   2: 3.148 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.106 ms/op
                 getUser·p0.50:   3.052 ms/op
                 getUser·p0.90:   3.437 ms/op
                 getUser·p0.95:   3.600 ms/op
                 getUser·p0.99:   5.423 ms/op
                 getUser·p0.999:  12.812 ms/op
                 getUser·p0.9999: 22.683 ms/op
                 getUser·p1.00:   23.233 ms/op

Iteration   3: 3.236 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.862 ms/op
                 getUser·p0.50:   3.109 ms/op
                 getUser·p0.90:   3.629 ms/op
                 getUser·p0.95:   4.047 ms/op
                 getUser·p0.99:   6.013 ms/op
                 getUser·p0.999:  11.731 ms/op
                 getUser·p0.9999: 20.902 ms/op
                 getUser·p1.00:   22.315 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 295167
  mean =      3.249 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6229 
    [ 2.500,  5.000) = 280850 
    [ 5.000,  7.500) = 7217 
    [ 7.500, 10.000) = 460 
    [10.000, 12.500) = 76 
    [12.500, 15.000) = 49 
    [15.000, 17.500) = 52 
    [17.500, 20.000) = 95 
    [20.000, 22.500) = 126 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.862 ms/op
     p(50.0000) =      3.097 ms/op
     p(90.0000) =      3.617 ms/op
     p(95.0000) =      4.415 ms/op
     p(99.0000) =      5.841 ms/op
     p(99.9000) =     14.909 ms/op
     p(99.9900) =     21.856 ms/op
     p(99.9990) =     23.037 ms/op
     p(99.9999) =     23.233 ms/op
    p(100.0000) =     23.233 ms/op


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
# Warmup Iteration   1: 9.198 ±(99.9%) 0.124 ms/op
# Warmup Iteration   2: 4.110 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.783 ±(99.9%) 0.011 ms/op
Iteration   1: 3.721 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.951 ms/op
                 listUser·p0.50:   3.584 ms/op
                 listUser·p0.90:   4.043 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   6.832 ms/op
                 listUser·p0.999:  15.504 ms/op
                 listUser·p0.9999: 21.738 ms/op
                 listUser·p1.00:   23.527 ms/op

Iteration   2: 3.715 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.827 ms/op
                 listUser·p0.50:   3.604 ms/op
                 listUser·p0.90:   4.014 ms/op
                 listUser·p0.95:   4.309 ms/op
                 listUser·p0.99:   7.062 ms/op
                 listUser·p0.999:  12.763 ms/op
                 listUser·p0.9999: 15.417 ms/op
                 listUser·p1.00:   15.483 ms/op

Iteration   3: 3.788 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.236 ms/op
                 listUser·p0.50:   3.690 ms/op
                 listUser·p0.90:   4.133 ms/op
                 listUser·p0.95:   4.481 ms/op
                 listUser·p0.99:   7.766 ms/op
                 listUser·p0.999:  12.880 ms/op
                 listUser·p0.9999: 15.663 ms/op
                 listUser·p1.00:   15.712 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 256477
  mean =      3.741 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 109 
    [ 2.500,  5.000) = 247946 
    [ 5.000,  7.500) = 6138 
    [ 7.500, 10.000) = 1550 
    [10.000, 12.500) = 370 
    [12.500, 15.000) = 230 
    [15.000, 17.500) = 87 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.951 ms/op
     p(50.0000) =      3.645 ms/op
     p(90.0000) =      4.063 ms/op
     p(95.0000) =      4.399 ms/op
     p(99.0000) =      7.324 ms/op
     p(99.9000) =     13.025 ms/op
     p(99.9900) =     19.618 ms/op
     p(99.9990) =     23.079 ms/op
     p(99.9999) =     23.527 ms/op
    p(100.0000) =     23.527 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.806 ± 5.508  ops/ms
ClientPb.existUser                       thrpt       3  10.314 ± 8.342  ops/ms
ClientPb.getUser                         thrpt       3  10.079 ± 4.233  ops/ms
ClientPb.listUser                        thrpt       3   8.629 ± 2.267  ops/ms
ClientPb.createUser                       avgt       3   3.237 ± 2.029   ms/op
ClientPb.existUser                        avgt       3   3.102 ± 0.291   ms/op
ClientPb.getUser                          avgt       3   3.242 ± 0.584   ms/op
ClientPb.listUser                         avgt       3   3.696 ± 1.158   ms/op
ClientPb.createUser                     sample  299445   3.206 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.484           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.170           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.547           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.850           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.407           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.025           ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.150           ms/op
ClientPb.createUser:createUser·p1.00    sample          26.411           ms/op
ClientPb.existUser                      sample  313336   3.062 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.141           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.072           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.211           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.400           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.161           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.156           ms/op
ClientPb.existUser:existUser·p0.9999    sample          21.791           ms/op
ClientPb.existUser:existUser·p1.00      sample          24.183           ms/op
ClientPb.getUser                        sample  295167   3.249 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.862           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.097           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.617           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.415           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.841           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.909           ms/op
ClientPb.getUser:getUser·p0.9999        sample          21.856           ms/op
ClientPb.getUser:getUser·p1.00          sample          23.233           ms/op
ClientPb.listUser                       sample  256477   3.741 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.951           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.645           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.063           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.399           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.324           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.025           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.618           ms/op
ClientPb.listUser:listUser·p1.00        sample          23.527           ms/op
