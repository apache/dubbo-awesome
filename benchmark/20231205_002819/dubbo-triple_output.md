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
# Warmup Iteration   1: 5.092 ops/ms
# Warmup Iteration   2: 11.950 ops/ms
# Warmup Iteration   3: 12.146 ops/ms
Iteration   1: 12.387 ops/ms
Iteration   2: 12.695 ops/ms
Iteration   3: 12.593 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.558 ±(99.9%) 2.860 ops/ms [Average]
  (min, avg, max) = (12.387, 12.558, 12.695), stdev = 0.157
  CI (99.9%): [9.699, 15.418] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.994 ops/ms
# Warmup Iteration   2: 12.948 ops/ms
# Warmup Iteration   3: 13.002 ops/ms
Iteration   1: 13.014 ops/ms
Iteration   2: 13.088 ops/ms
Iteration   3: 13.061 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.054 ±(99.9%) 0.685 ops/ms [Average]
  (min, avg, max) = (13.014, 13.054, 13.088), stdev = 0.038
  CI (99.9%): [12.369, 13.739] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.789 ops/ms
# Warmup Iteration   2: 12.339 ops/ms
# Warmup Iteration   3: 12.632 ops/ms
Iteration   1: 12.700 ops/ms
Iteration   2: 12.783 ops/ms
Iteration   3: 12.776 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.753 ±(99.9%) 0.837 ops/ms [Average]
  (min, avg, max) = (12.700, 12.753, 12.783), stdev = 0.046
  CI (99.9%): [11.916, 13.591] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.696 ops/ms
# Warmup Iteration   2: 10.361 ops/ms
# Warmup Iteration   3: 10.348 ops/ms
Iteration   1: 10.613 ops/ms
Iteration   2: 10.552 ops/ms
Iteration   3: 10.468 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.544 ±(99.9%) 1.327 ops/ms [Average]
  (min, avg, max) = (10.468, 10.544, 10.613), stdev = 0.073
  CI (99.9%): [9.217, 11.872] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.085 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 2.562 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.552 ±(99.9%) 0.004 ms/op
Iteration   1: 2.523 ±(99.9%) 0.005 ms/op
Iteration   2: 2.572 ±(99.9%) 0.005 ms/op
Iteration   3: 2.524 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.540 ±(99.9%) 0.511 ms/op [Average]
  (min, avg, max) = (2.523, 2.540, 2.572), stdev = 0.028
  CI (99.9%): [2.029, 3.051] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:32
# Fork: 1 of 1
# Warmup Iteration   1: 3.694 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.493 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.448 ±(99.9%) 0.004 ms/op
Iteration   1: 2.451 ±(99.9%) 0.004 ms/op
Iteration   2: 2.467 ±(99.9%) 0.005 ms/op
Iteration   3: 2.448 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.455 ±(99.9%) 0.185 ms/op [Average]
  (min, avg, max) = (2.448, 2.455, 2.467), stdev = 0.010
  CI (99.9%): [2.270, 2.640] (assumes normal distribution)


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
# Warmup Iteration   1: 3.926 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.562 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.511 ±(99.9%) 0.005 ms/op
Iteration   1: 2.517 ±(99.9%) 0.005 ms/op
Iteration   2: 2.525 ±(99.9%) 0.004 ms/op
Iteration   3: 2.511 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.518 ±(99.9%) 0.131 ms/op [Average]
  (min, avg, max) = (2.511, 2.518, 2.525), stdev = 0.007
  CI (99.9%): [2.387, 2.648] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:23
# Fork: 1 of 1
# Warmup Iteration   1: 4.774 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.038 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.026 ±(99.9%) 0.006 ms/op
Iteration   1: 3.046 ±(99.9%) 0.005 ms/op
Iteration   2: 3.038 ±(99.9%) 0.006 ms/op
Iteration   3: 3.023 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.036 ±(99.9%) 0.209 ms/op [Average]
  (min, avg, max) = (3.023, 3.036, 3.046), stdev = 0.011
  CI (99.9%): [2.827, 3.245] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:18
# Fork: 1 of 1
# Warmup Iteration   1: 4.152 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.696 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.550 ±(99.9%) 0.006 ms/op
Iteration   1: 2.588 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.958 ms/op
                 createUser·p0.50:   2.630 ms/op
                 createUser·p0.90:   3.142 ms/op
                 createUser·p0.95:   3.326 ms/op
                 createUser·p0.99:   4.358 ms/op
                 createUser·p0.999:  11.469 ms/op
                 createUser·p0.9999: 14.297 ms/op
                 createUser·p1.00:   14.565 ms/op

Iteration   2: 2.534 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.901 ms/op
                 createUser·p0.50:   2.630 ms/op
                 createUser·p0.90:   3.064 ms/op
                 createUser·p0.95:   3.174 ms/op
                 createUser·p0.99:   3.740 ms/op
                 createUser·p0.999:  10.045 ms/op
                 createUser·p0.9999: 13.234 ms/op
                 createUser·p1.00:   13.648 ms/op

Iteration   3: 2.540 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.991 ms/op
                 createUser·p0.50:   2.613 ms/op
                 createUser·p0.90:   3.084 ms/op
                 createUser·p0.95:   3.207 ms/op
                 createUser·p0.99:   4.006 ms/op
                 createUser·p0.999:  8.357 ms/op
                 createUser·p0.9999: 10.499 ms/op
                 createUser·p1.00:   10.928 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 375600
  mean =      2.553 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 33 
    [ 1.250,  2.500) = 178117 
    [ 2.500,  3.750) = 191570 
    [ 3.750,  5.000) = 4243 
    [ 5.000,  6.250) = 1134 
    [ 6.250,  7.500) = 111 
    [ 7.500,  8.750) = 28 
    [ 8.750, 10.000) = 78 
    [10.000, 11.250) = 100 
    [11.250, 12.500) = 87 
    [12.500, 13.750) = 65 
    [13.750, 15.000) = 34 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.901 ms/op
     p(50.0000) =      2.626 ms/op
     p(90.0000) =      3.097 ms/op
     p(95.0000) =      3.228 ms/op
     p(99.0000) =      4.075 ms/op
     p(99.9000) =      8.389 ms/op
     p(99.9900) =     13.602 ms/op
     p(99.9990) =     14.565 ms/op
     p(99.9999) =     14.565 ms/op
    p(100.0000) =     14.565 ms/op


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
# Warmup Iteration   1: 3.811 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.535 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.522 ±(99.9%) 0.005 ms/op
Iteration   1: 2.510 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.945 ms/op
                 existUser·p0.50:   2.572 ms/op
                 existUser·p0.90:   3.047 ms/op
                 existUser·p0.95:   3.170 ms/op
                 existUser·p0.99:   3.764 ms/op
                 existUser·p0.999:  11.692 ms/op
                 existUser·p0.9999: 13.374 ms/op
                 existUser·p1.00:   13.763 ms/op

Iteration   2: 2.498 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.969 ms/op
                 existUser·p0.50:   2.560 ms/op
                 existUser·p0.90:   3.031 ms/op
                 existUser·p0.95:   3.129 ms/op
                 existUser·p0.99:   3.749 ms/op
                 existUser·p0.999:  8.766 ms/op
                 existUser·p0.9999: 13.287 ms/op
                 existUser·p1.00:   13.746 ms/op

Iteration   3: 2.489 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.882 ms/op
                 existUser·p0.50:   2.597 ms/op
                 existUser·p0.90:   3.027 ms/op
                 existUser·p0.95:   3.142 ms/op
                 existUser·p0.99:   3.838 ms/op
                 existUser·p0.999:  8.277 ms/op
                 existUser·p0.9999: 14.538 ms/op
                 existUser·p1.00:   16.187 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 383734
  mean =      2.499 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 32 
    [ 1.250,  2.500) = 186426 
    [ 2.500,  3.750) = 193252 
    [ 3.750,  5.000) = 3034 
    [ 5.000,  6.250) = 494 
    [ 6.250,  7.500) = 84 
    [ 7.500,  8.750) = 28 
    [ 8.750, 10.000) = 93 
    [10.000, 11.250) = 93 
    [11.250, 12.500) = 55 
    [12.500, 13.750) = 112 
    [13.750, 15.000) = 23 
    [15.000, 16.250) = 8 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.882 ms/op
     p(50.0000) =      2.576 ms/op
     p(90.0000) =      3.035 ms/op
     p(95.0000) =      3.146 ms/op
     p(99.0000) =      3.785 ms/op
     p(99.9000) =      8.770 ms/op
     p(99.9900) =     13.636 ms/op
     p(99.9990) =     15.590 ms/op
     p(99.9999) =     16.187 ms/op
    p(100.0000) =     16.187 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.882 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.610 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.515 ±(99.9%) 0.005 ms/op
Iteration   1: 2.526 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.641 ms/op
                 getUser·p0.50:   2.527 ms/op
                 getUser·p0.90:   3.084 ms/op
                 getUser·p0.95:   3.236 ms/op
                 getUser·p0.99:   3.949 ms/op
                 getUser·p0.999:  11.433 ms/op
                 getUser·p0.9999: 22.403 ms/op
                 getUser·p1.00:   23.593 ms/op

Iteration   2: 2.548 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.994 ms/op
                 getUser·p0.50:   2.564 ms/op
                 getUser·p0.90:   3.117 ms/op
                 getUser·p0.95:   3.285 ms/op
                 getUser·p0.99:   4.030 ms/op
                 getUser·p0.999:  9.765 ms/op
                 getUser·p0.9999: 12.787 ms/op
                 getUser·p1.00:   13.992 ms/op

Iteration   3: 2.557 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.689 ms/op
                 getUser·p0.50:   2.580 ms/op
                 getUser·p0.90:   3.117 ms/op
                 getUser·p0.95:   3.269 ms/op
                 getUser·p0.99:   4.260 ms/op
                 getUser·p0.999:  7.807 ms/op
                 getUser·p0.9999: 11.289 ms/op
                 getUser·p1.00:   11.485 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 377083
  mean =      2.543 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 182909 
    [ 2.500,  5.000) = 193005 
    [ 5.000,  7.500) = 779 
    [ 7.500, 10.000) = 62 
    [10.000, 12.500) = 217 
    [12.500, 15.000) = 79 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.641 ms/op
     p(50.0000) =      2.556 ms/op
     p(90.0000) =      3.109 ms/op
     p(95.0000) =      3.265 ms/op
     p(99.0000) =      4.080 ms/op
     p(99.9000) =      8.420 ms/op
     p(99.9900) =     14.189 ms/op
     p(99.9990) =     23.220 ms/op
     p(99.9999) =     23.593 ms/op
    p(100.0000) =     23.593 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.703 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.173 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.060 ±(99.9%) 0.009 ms/op
Iteration   1: 3.067 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.879 ms/op
                 listUser·p0.50:   3.011 ms/op
                 listUser·p0.90:   3.928 ms/op
                 listUser·p0.95:   4.465 ms/op
                 listUser·p0.99:   5.775 ms/op
                 listUser·p0.999:  8.646 ms/op
                 listUser·p0.9999: 12.861 ms/op
                 listUser·p1.00:   13.926 ms/op

Iteration   2: 3.072 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.829 ms/op
                 listUser·p0.50:   3.002 ms/op
                 listUser·p0.90:   4.002 ms/op
                 listUser·p0.95:   4.522 ms/op
                 listUser·p0.99:   5.628 ms/op
                 listUser·p0.999:  9.878 ms/op
                 listUser·p0.9999: 11.839 ms/op
                 listUser·p1.00:   12.403 ms/op

Iteration   3: 3.069 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.684 ms/op
                 listUser·p0.50:   3.002 ms/op
                 listUser·p0.90:   3.949 ms/op
                 listUser·p0.95:   4.497 ms/op
                 listUser·p0.99:   5.603 ms/op
                 listUser·p0.999:  9.781 ms/op
                 listUser·p0.9999: 13.683 ms/op
                 listUser·p1.00:   14.516 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 312562
  mean =      3.069 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 134 
    [ 1.250,  2.500) = 81554 
    [ 2.500,  3.750) = 187890 
    [ 3.750,  5.000) = 34841 
    [ 5.000,  6.250) = 6718 
    [ 6.250,  7.500) = 761 
    [ 7.500,  8.750) = 176 
    [ 8.750, 10.000) = 279 
    [10.000, 11.250) = 111 
    [11.250, 12.500) = 56 
    [12.500, 13.750) = 31 
    [13.750, 15.000) = 11 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.684 ms/op
     p(50.0000) =      3.002 ms/op
     p(90.0000) =      3.961 ms/op
     p(95.0000) =      4.497 ms/op
     p(99.0000) =      5.669 ms/op
     p(99.9000) =      9.617 ms/op
     p(99.9900) =     12.857 ms/op
     p(99.9990) =     14.479 ms/op
     p(99.9999) =     14.516 ms/op
    p(100.0000) =     14.516 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.558 ± 2.860  ops/ms
ClientPb.existUser                       thrpt       3  13.054 ± 0.685  ops/ms
ClientPb.getUser                         thrpt       3  12.753 ± 0.837  ops/ms
ClientPb.listUser                        thrpt       3  10.544 ± 1.327  ops/ms
ClientPb.createUser                       avgt       3   2.540 ± 0.511   ms/op
ClientPb.existUser                        avgt       3   2.455 ± 0.185   ms/op
ClientPb.getUser                          avgt       3   2.518 ± 0.131   ms/op
ClientPb.listUser                         avgt       3   3.036 ± 0.209   ms/op
ClientPb.createUser                     sample  375600   2.553 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.901           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.626           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.097           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.228           ms/op
ClientPb.createUser:createUser·p0.99    sample           4.075           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.389           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.602           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.565           ms/op
ClientPb.existUser                      sample  383734   2.499 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.882           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.576           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.035           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.146           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.785           ms/op
ClientPb.existUser:existUser·p0.999     sample           8.770           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.636           ms/op
ClientPb.existUser:existUser·p1.00      sample          16.187           ms/op
ClientPb.getUser                        sample  377083   2.543 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.641           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.556           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.109           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.265           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.080           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.420           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.189           ms/op
ClientPb.getUser:getUser·p1.00          sample          23.593           ms/op
ClientPb.listUser                       sample  312562   3.069 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.684           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.002           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.961           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.497           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.669           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.617           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.857           ms/op
ClientPb.listUser:listUser·p1.00        sample          14.516           ms/op
