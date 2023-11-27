# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 5.302 ops/ms
# Warmup Iteration   2: 11.932 ops/ms
# Warmup Iteration   3: 12.097 ops/ms
Iteration   1: 12.436 ops/ms
Iteration   2: 12.450 ops/ms
Iteration   3: 12.502 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.462 ±(99.9%) 0.634 ops/ms [Average]
  (min, avg, max) = (12.436, 12.462, 12.502), stdev = 0.035
  CI (99.9%): [11.828, 13.097] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:53
# Fork: 1 of 1
# Warmup Iteration   1: 8.148 ops/ms
# Warmup Iteration   2: 12.962 ops/ms
# Warmup Iteration   3: 12.957 ops/ms
Iteration   1: 12.941 ops/ms
Iteration   2: 13.023 ops/ms
Iteration   3: 12.913 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.959 ±(99.9%) 1.048 ops/ms [Average]
  (min, avg, max) = (12.913, 12.959, 13.023), stdev = 0.057
  CI (99.9%): [11.911, 14.007] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:48
# Fork: 1 of 1
# Warmup Iteration   1: 7.513 ops/ms
# Warmup Iteration   2: 12.465 ops/ms
# Warmup Iteration   3: 12.729 ops/ms
Iteration   1: 12.548 ops/ms
Iteration   2: 12.569 ops/ms
Iteration   3: 12.559 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.558 ±(99.9%) 0.194 ops/ms [Average]
  (min, avg, max) = (12.548, 12.558, 12.569), stdev = 0.011
  CI (99.9%): [12.364, 12.752] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:43
# Fork: 1 of 1
# Warmup Iteration   1: 6.455 ops/ms
# Warmup Iteration   2: 10.312 ops/ms
# Warmup Iteration   3: 10.576 ops/ms
Iteration   1: 10.696 ops/ms
Iteration   2: 10.530 ops/ms
Iteration   3: 10.549 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.592 ±(99.9%) 1.657 ops/ms [Average]
  (min, avg, max) = (10.530, 10.592, 10.696), stdev = 0.091
  CI (99.9%): [8.935, 12.249] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:38
# Fork: 1 of 1
# Warmup Iteration   1: 4.138 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.617 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.551 ±(99.9%) 0.004 ms/op
Iteration   1: 2.592 ±(99.9%) 0.005 ms/op
Iteration   2: 2.551 ±(99.9%) 0.004 ms/op
Iteration   3: 2.544 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.562 ±(99.9%) 0.470 ms/op [Average]
  (min, avg, max) = (2.544, 2.562, 2.592), stdev = 0.026
  CI (99.9%): [2.092, 3.033] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:33
# Fork: 1 of 1
# Warmup Iteration   1: 3.612 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.498 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.414 ±(99.9%) 0.004 ms/op
Iteration   1: 2.465 ±(99.9%) 0.004 ms/op
Iteration   2: 2.450 ±(99.9%) 0.003 ms/op
Iteration   3: 2.438 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.451 ±(99.9%) 0.249 ms/op [Average]
  (min, avg, max) = (2.438, 2.451, 2.465), stdev = 0.014
  CI (99.9%): [2.202, 2.700] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.945 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.586 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.539 ±(99.9%) 0.004 ms/op
Iteration   1: 2.539 ±(99.9%) 0.004 ms/op
Iteration   2: 2.513 ±(99.9%) 0.003 ms/op
Iteration   3: 2.494 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.515 ±(99.9%) 0.417 ms/op [Average]
  (min, avg, max) = (2.494, 2.515, 2.539), stdev = 0.023
  CI (99.9%): [2.099, 2.932] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 4.596 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.070 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.046 ±(99.9%) 0.005 ms/op
Iteration   1: 3.040 ±(99.9%) 0.005 ms/op
Iteration   2: 3.039 ±(99.9%) 0.006 ms/op
Iteration   3: 3.032 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.037 ±(99.9%) 0.079 ms/op [Average]
  (min, avg, max) = (3.032, 3.037, 3.040), stdev = 0.004
  CI (99.9%): [2.958, 3.116] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:19
# Fork: 1 of 1
# Warmup Iteration   1: 4.204 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.621 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.563 ±(99.9%) 0.006 ms/op
Iteration   1: 2.548 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.989 ms/op
                 createUser·p0.50:   2.597 ms/op
                 createUser·p0.90:   3.101 ms/op
                 createUser·p0.95:   3.224 ms/op
                 createUser·p0.99:   3.895 ms/op
                 createUser·p0.999:  11.747 ms/op
                 createUser·p0.9999: 13.770 ms/op
                 createUser·p1.00:   13.959 ms/op

Iteration   2: 2.567 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.972 ms/op
                 createUser·p0.50:   2.658 ms/op
                 createUser·p0.90:   3.097 ms/op
                 createUser·p0.95:   3.219 ms/op
                 createUser·p0.99:   4.194 ms/op
                 createUser·p0.999:  10.358 ms/op
                 createUser·p0.9999: 13.257 ms/op
                 createUser·p1.00:   13.648 ms/op

Iteration   3: 2.537 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.973 ms/op
                 createUser·p0.50:   2.597 ms/op
                 createUser·p0.90:   3.080 ms/op
                 createUser·p0.95:   3.191 ms/op
                 createUser·p0.99:   3.719 ms/op
                 createUser·p0.999:  8.355 ms/op
                 createUser·p0.9999: 10.856 ms/op
                 createUser·p1.00:   11.256 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 376021
  mean =      2.550 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 54 
    [ 1.250,  2.500) = 180026 
    [ 2.500,  3.750) = 191039 
    [ 3.750,  5.000) = 3833 
    [ 5.000,  6.250) = 637 
    [ 6.250,  7.500) = 45 
    [ 7.500,  8.750) = 18 
    [ 8.750, 10.000) = 65 
    [10.000, 11.250) = 81 
    [11.250, 12.500) = 88 
    [12.500, 13.750) = 122 
    [13.750, 15.000) = 13 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.972 ms/op
     p(50.0000) =      2.613 ms/op
     p(90.0000) =      3.092 ms/op
     p(95.0000) =      3.211 ms/op
     p(99.0000) =      3.920 ms/op
     p(99.9000) =      8.617 ms/op
     p(99.9900) =     13.163 ms/op
     p(99.9990) =     13.885 ms/op
     p(99.9999) =     13.959 ms/op
    p(100.0000) =     13.959 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.851 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.505 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.472 ±(99.9%) 0.005 ms/op
Iteration   1: 2.464 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.897 ms/op
                 existUser·p0.50:   2.499 ms/op
                 existUser·p0.90:   2.990 ms/op
                 existUser·p0.95:   3.105 ms/op
                 existUser·p0.99:   3.715 ms/op
                 existUser·p0.999:  7.791 ms/op
                 existUser·p0.9999: 13.828 ms/op
                 existUser·p1.00:   14.746 ms/op

Iteration   2: 2.507 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.753 ms/op
                 existUser·p0.50:   2.576 ms/op
                 existUser·p0.90:   3.027 ms/op
                 existUser·p0.95:   3.178 ms/op
                 existUser·p0.99:   4.686 ms/op
                 existUser·p0.999:  9.289 ms/op
                 existUser·p0.9999: 12.939 ms/op
                 existUser·p1.00:   13.304 ms/op

Iteration   3: 2.478 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.981 ms/op
                 existUser·p0.50:   2.535 ms/op
                 existUser·p0.90:   3.011 ms/op
                 existUser·p0.95:   3.142 ms/op
                 existUser·p0.99:   3.964 ms/op
                 existUser·p0.999:  5.841 ms/op
                 existUser·p0.9999: 10.859 ms/op
                 existUser·p1.00:   11.305 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 386307
  mean =      2.483 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 49 
    [ 1.250,  2.500) = 190082 
    [ 2.500,  3.750) = 190578 
    [ 3.750,  5.000) = 4072 
    [ 5.000,  6.250) = 1102 
    [ 6.250,  7.500) = 31 
    [ 7.500,  8.750) = 60 
    [ 8.750, 10.000) = 85 
    [10.000, 11.250) = 55 
    [11.250, 12.500) = 88 
    [12.500, 13.750) = 87 
    [13.750, 15.000) = 18 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.753 ms/op
     p(50.0000) =      2.535 ms/op
     p(90.0000) =      3.011 ms/op
     p(95.0000) =      3.142 ms/op
     p(99.0000) =      4.076 ms/op
     p(99.9000) =      7.978 ms/op
     p(99.9900) =     13.238 ms/op
     p(99.9990) =     14.568 ms/op
     p(99.9999) =     14.746 ms/op
    p(100.0000) =     14.746 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.085 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.595 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.535 ±(99.9%) 0.006 ms/op
Iteration   1: 2.517 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.918 ms/op
                 getUser·p0.50:   2.523 ms/op
                 getUser·p0.90:   3.076 ms/op
                 getUser·p0.95:   3.224 ms/op
                 getUser·p0.99:   4.010 ms/op
                 getUser·p0.999:  11.630 ms/op
                 getUser·p0.9999: 14.041 ms/op
                 getUser·p1.00:   14.467 ms/op

Iteration   2: 2.519 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.861 ms/op
                 getUser·p0.50:   2.535 ms/op
                 getUser·p0.90:   3.068 ms/op
                 getUser·p0.95:   3.211 ms/op
                 getUser·p0.99:   4.157 ms/op
                 getUser·p0.999:  9.454 ms/op
                 getUser·p0.9999: 14.008 ms/op
                 getUser·p1.00:   14.664 ms/op

Iteration   3: 2.482 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.971 ms/op
                 getUser·p0.50:   2.535 ms/op
                 getUser·p0.90:   3.015 ms/op
                 getUser·p0.95:   3.129 ms/op
                 getUser·p0.99:   3.809 ms/op
                 getUser·p0.999:  7.098 ms/op
                 getUser·p0.9999: 10.340 ms/op
                 getUser·p1.00:   11.321 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 382794
  mean =      2.506 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 51 
    [ 1.250,  2.500) = 189046 
    [ 2.500,  3.750) = 188281 
    [ 3.750,  5.000) = 4250 
    [ 5.000,  6.250) = 715 
    [ 6.250,  7.500) = 67 
    [ 7.500,  8.750) = 27 
    [ 8.750, 10.000) = 75 
    [10.000, 11.250) = 68 
    [11.250, 12.500) = 54 
    [12.500, 13.750) = 119 
    [13.750, 15.000) = 41 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.861 ms/op
     p(50.0000) =      2.531 ms/op
     p(90.0000) =      3.052 ms/op
     p(95.0000) =      3.191 ms/op
     p(99.0000) =      3.998 ms/op
     p(99.9000) =      7.923 ms/op
     p(99.9900) =     13.884 ms/op
     p(99.9990) =     14.355 ms/op
     p(99.9999) =     14.664 ms/op
    p(100.0000) =     14.664 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.729 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.079 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.051 ±(99.9%) 0.009 ms/op
Iteration   1: 3.046 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.825 ms/op
                 listUser·p0.50:   2.986 ms/op
                 listUser·p0.90:   3.936 ms/op
                 listUser·p0.95:   4.448 ms/op
                 listUser·p0.99:   5.665 ms/op
                 listUser·p0.999:  8.881 ms/op
                 listUser·p0.9999: 11.985 ms/op
                 listUser·p1.00:   14.254 ms/op

Iteration   2: 3.026 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.979 ms/op
                 listUser·p0.50:   2.961 ms/op
                 listUser·p0.90:   3.899 ms/op
                 listUser·p0.95:   4.383 ms/op
                 listUser·p0.99:   5.652 ms/op
                 listUser·p0.999:  10.049 ms/op
                 listUser·p0.9999: 12.047 ms/op
                 listUser·p1.00:   12.976 ms/op

Iteration   3: 3.032 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.908 ms/op
                 listUser·p0.50:   2.974 ms/op
                 listUser·p0.90:   3.887 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   5.480 ms/op
                 listUser·p0.999:  9.372 ms/op
                 listUser·p0.9999: 10.867 ms/op
                 listUser·p1.00:   11.305 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 316039
  mean =      3.035 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 122 
    [ 1.250,  2.500) = 86487 
    [ 2.500,  3.750) = 188870 
    [ 3.750,  5.000) = 33246 
    [ 5.000,  6.250) = 5905 
    [ 6.250,  7.500) = 723 
    [ 7.500,  8.750) = 187 
    [ 8.750, 10.000) = 283 
    [10.000, 11.250) = 159 
    [11.250, 12.500) = 46 
    [12.500, 13.750) = 10 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.825 ms/op
     p(50.0000) =      2.974 ms/op
     p(90.0000) =      3.908 ms/op
     p(95.0000) =      4.415 ms/op
     p(99.0000) =      5.612 ms/op
     p(99.9000) =      9.502 ms/op
     p(99.9900) =     11.875 ms/op
     p(99.9990) =     13.009 ms/op
     p(99.9999) =     14.254 ms/op
    p(100.0000) =     14.254 ms/op


# Run complete. Total time: 00:13:00

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.462 ± 0.634  ops/ms
ClientPb.existUser                       thrpt       3  12.959 ± 1.048  ops/ms
ClientPb.getUser                         thrpt       3  12.558 ± 0.194  ops/ms
ClientPb.listUser                        thrpt       3  10.592 ± 1.657  ops/ms
ClientPb.createUser                       avgt       3   2.562 ± 0.470   ms/op
ClientPb.existUser                        avgt       3   2.451 ± 0.249   ms/op
ClientPb.getUser                          avgt       3   2.515 ± 0.417   ms/op
ClientPb.listUser                         avgt       3   3.037 ± 0.079   ms/op
ClientPb.createUser                     sample  376021   2.550 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.972           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.613           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.092           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.211           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.920           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.617           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.163           ms/op
ClientPb.createUser:createUser·p1.00    sample          13.959           ms/op
ClientPb.existUser                      sample  386307   2.483 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.753           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.535           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.011           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.142           ms/op
ClientPb.existUser:existUser·p0.99      sample           4.076           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.978           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.238           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.746           ms/op
ClientPb.getUser                        sample  382794   2.506 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.861           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.531           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.052           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.191           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.998           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.923           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.884           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.664           ms/op
ClientPb.listUser                       sample  316039   3.035 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.825           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.974           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.908           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.415           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.612           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.502           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.875           ms/op
ClientPb.listUser:listUser·p1.00        sample          14.254           ms/op
