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
# Warmup Iteration   1: 4.236 ops/ms
# Warmup Iteration   2: 11.414 ops/ms
# Warmup Iteration   3: 11.576 ops/ms
Iteration   1: 12.028 ops/ms
Iteration   2: 12.093 ops/ms
Iteration   3: 12.095 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.072 ±(99.9%) 0.697 ops/ms [Average]
  (min, avg, max) = (12.028, 12.072, 12.095), stdev = 0.038
  CI (99.9%): [11.375, 12.770] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:55
# Fork: 1 of 1
# Warmup Iteration   1: 7.047 ops/ms
# Warmup Iteration   2: 12.205 ops/ms
# Warmup Iteration   3: 12.425 ops/ms
Iteration   1: 12.196 ops/ms
Iteration   2: 12.453 ops/ms
Iteration   3: 12.216 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.288 ±(99.9%) 2.604 ops/ms [Average]
  (min, avg, max) = (12.196, 12.288, 12.453), stdev = 0.143
  CI (99.9%): [9.685, 14.892] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:49
# Fork: 1 of 1
# Warmup Iteration   1: 6.975 ops/ms
# Warmup Iteration   2: 12.003 ops/ms
# Warmup Iteration   3: 12.340 ops/ms
Iteration   1: 12.483 ops/ms
Iteration   2: 12.242 ops/ms
Iteration   3: 12.540 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.422 ±(99.9%) 2.883 ops/ms [Average]
  (min, avg, max) = (12.242, 12.422, 12.540), stdev = 0.158
  CI (99.9%): [9.538, 15.305] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 5.916 ops/ms
# Warmup Iteration   2: 10.072 ops/ms
# Warmup Iteration   3: 10.201 ops/ms
Iteration   1: 10.303 ops/ms
Iteration   2: 10.420 ops/ms
Iteration   3: 10.222 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.315 ±(99.9%) 1.811 ops/ms [Average]
  (min, avg, max) = (10.222, 10.315, 10.420), stdev = 0.099
  CI (99.9%): [8.504, 12.126] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:39
# Fork: 1 of 1
# Warmup Iteration   1: 4.641 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 2.651 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.625 ±(99.9%) 0.004 ms/op
Iteration   1: 2.609 ±(99.9%) 0.005 ms/op
Iteration   2: 2.636 ±(99.9%) 0.005 ms/op
Iteration   3: 2.611 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.618 ±(99.9%) 0.278 ms/op [Average]
  (min, avg, max) = (2.609, 2.618, 2.636), stdev = 0.015
  CI (99.9%): [2.340, 2.896] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:34
# Fork: 1 of 1
# Warmup Iteration   1: 3.890 ±(99.9%) 0.008 ms/op
# Warmup Iteration   2: 2.554 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.563 ±(99.9%) 0.003 ms/op
Iteration   1: 2.530 ±(99.9%) 0.004 ms/op
Iteration   2: 2.554 ±(99.9%) 0.003 ms/op
Iteration   3: 2.544 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.543 ±(99.9%) 0.219 ms/op [Average]
  (min, avg, max) = (2.530, 2.543, 2.554), stdev = 0.012
  CI (99.9%): [2.324, 2.762] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:29
# Fork: 1 of 1
# Warmup Iteration   1: 4.165 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 2.632 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.625 ±(99.9%) 0.005 ms/op
Iteration   1: 2.585 ±(99.9%) 0.006 ms/op
Iteration   2: 2.592 ±(99.9%) 0.004 ms/op
Iteration   3: 2.583 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.587 ±(99.9%) 0.091 ms/op [Average]
  (min, avg, max) = (2.583, 2.587, 2.592), stdev = 0.005
  CI (99.9%): [2.495, 2.678] (assumes normal distribution)


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
# Warmup Iteration   1: 5.374 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.172 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.114 ±(99.9%) 0.006 ms/op
Iteration   1: 3.119 ±(99.9%) 0.007 ms/op
Iteration   2: 3.143 ±(99.9%) 0.006 ms/op
Iteration   3: 3.117 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.126 ±(99.9%) 0.260 ms/op [Average]
  (min, avg, max) = (3.117, 3.126, 3.143), stdev = 0.014
  CI (99.9%): [2.867, 3.386] (assumes normal distribution)


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
# Warmup Iteration   1: 4.996 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 2.799 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.642 ±(99.9%) 0.006 ms/op
Iteration   1: 2.643 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.600 ms/op
                 createUser·p0.50:   2.666 ms/op
                 createUser·p0.90:   3.232 ms/op
                 createUser·p0.95:   3.453 ms/op
                 createUser·p0.99:   4.702 ms/op
                 createUser·p0.999:  13.650 ms/op
                 createUser·p0.9999: 16.324 ms/op
                 createUser·p1.00:   19.005 ms/op

Iteration   2: 2.585 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.012 ms/op
                 createUser·p0.50:   2.638 ms/op
                 createUser·p0.90:   3.162 ms/op
                 createUser·p0.95:   3.301 ms/op
                 createUser·p0.99:   3.899 ms/op
                 createUser·p0.999:  10.158 ms/op
                 createUser·p0.9999: 16.143 ms/op
                 createUser·p1.00:   16.974 ms/op

Iteration   3: 2.625 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.977 ms/op
                 createUser·p0.50:   2.658 ms/op
                 createUser·p0.90:   3.224 ms/op
                 createUser·p0.95:   3.400 ms/op
                 createUser·p0.99:   4.157 ms/op
                 createUser·p0.999:  9.617 ms/op
                 createUser·p0.9999: 12.397 ms/op
                 createUser·p1.00:   12.550 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 366302
  mean =      2.617 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 57 
    [ 1.250,  2.500) = 168818 
    [ 2.500,  3.750) = 189875 
    [ 3.750,  5.000) = 5917 
    [ 5.000,  6.250) = 951 
    [ 6.250,  7.500) = 217 
    [ 7.500,  8.750) = 38 
    [ 8.750, 10.000) = 68 
    [10.000, 11.250) = 108 
    [11.250, 12.500) = 54 
    [12.500, 13.750) = 29 
    [13.750, 15.000) = 92 
    [15.000, 16.250) = 57 
    [16.250, 17.500) = 19 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.600 ms/op
     p(50.0000) =      2.654 ms/op
     p(90.0000) =      3.203 ms/op
     p(95.0000) =      3.379 ms/op
     p(99.0000) =      4.252 ms/op
     p(99.9000) =      9.961 ms/op
     p(99.9900) =     15.626 ms/op
     p(99.9990) =     16.843 ms/op
     p(99.9999) =     19.005 ms/op
    p(100.0000) =     19.005 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 4.152 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 2.552 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.559 ±(99.9%) 0.006 ms/op
Iteration   1: 2.576 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.909 ms/op
                 existUser·p0.50:   2.564 ms/op
                 existUser·p0.90:   3.178 ms/op
                 existUser·p0.95:   3.351 ms/op
                 existUser·p0.99:   4.188 ms/op
                 existUser·p0.999:  7.353 ms/op
                 existUser·p0.9999: 14.657 ms/op
                 existUser·p1.00:   15.221 ms/op

Iteration   2: 2.566 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.962 ms/op
                 existUser·p0.50:   2.589 ms/op
                 existUser·p0.90:   3.142 ms/op
                 existUser·p0.95:   3.285 ms/op
                 existUser·p0.99:   3.903 ms/op
                 existUser·p0.999:  13.484 ms/op
                 existUser·p0.9999: 17.302 ms/op
                 existUser·p1.00:   17.891 ms/op

Iteration   3: 2.559 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.985 ms/op
                 existUser·p0.50:   2.589 ms/op
                 existUser·p0.90:   3.142 ms/op
                 existUser·p0.95:   3.297 ms/op
                 existUser·p0.99:   4.096 ms/op
                 existUser·p0.999:  10.699 ms/op
                 existUser·p0.9999: 12.411 ms/op
                 existUser·p1.00:   13.402 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 373527
  mean =      2.567 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 63 
    [ 1.250,  2.500) = 179425 
    [ 2.500,  3.750) = 188211 
    [ 3.750,  5.000) = 4434 
    [ 5.000,  6.250) = 923 
    [ 6.250,  7.500) = 97 
    [ 7.500,  8.750) = 21 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 40 
    [11.250, 12.500) = 80 
    [12.500, 13.750) = 43 
    [13.750, 15.000) = 120 
    [15.000, 16.250) = 34 
    [16.250, 17.500) = 31 
    [17.500, 18.750) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.909 ms/op
     p(50.0000) =      2.580 ms/op
     p(90.0000) =      3.154 ms/op
     p(95.0000) =      3.310 ms/op
     p(99.0000) =      4.063 ms/op
     p(99.9000) =      7.508 ms/op
     p(99.9900) =     16.185 ms/op
     p(99.9990) =     17.679 ms/op
     p(99.9999) =     17.891 ms/op
    p(100.0000) =     17.891 ms/op


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
# Warmup Iteration   1: 4.486 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 2.731 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.632 ±(99.9%) 0.006 ms/op
Iteration   1: 2.597 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.963 ms/op
                 getUser·p0.50:   2.617 ms/op
                 getUser·p0.90:   3.178 ms/op
                 getUser·p0.95:   3.367 ms/op
                 getUser·p0.99:   4.350 ms/op
                 getUser·p0.999:  12.558 ms/op
                 getUser·p0.9999: 16.418 ms/op
                 getUser·p1.00:   19.333 ms/op

Iteration   2: 2.604 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.061 ms/op
                 getUser·p0.50:   2.642 ms/op
                 getUser·p0.90:   3.191 ms/op
                 getUser·p0.95:   3.355 ms/op
                 getUser·p0.99:   4.141 ms/op
                 getUser·p0.999:  11.928 ms/op
                 getUser·p0.9999: 15.904 ms/op
                 getUser·p1.00:   17.138 ms/op

Iteration   3: 2.630 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.621 ms/op
                 getUser·p0.50:   2.626 ms/op
                 getUser·p0.90:   3.232 ms/op
                 getUser·p0.95:   3.441 ms/op
                 getUser·p0.99:   4.904 ms/op
                 getUser·p0.999:  9.477 ms/op
                 getUser·p0.9999: 14.380 ms/op
                 getUser·p1.00:   14.811 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 367406
  mean =      2.610 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 64 
    [ 1.250,  2.500) = 172514 
    [ 2.500,  3.750) = 186696 
    [ 3.750,  5.000) = 5939 
    [ 5.000,  6.250) = 1594 
    [ 6.250,  7.500) = 200 
    [ 7.500,  8.750) = 15 
    [ 8.750, 10.000) = 22 
    [10.000, 11.250) = 58 
    [11.250, 12.500) = 30 
    [12.500, 13.750) = 110 
    [13.750, 15.000) = 92 
    [15.000, 16.250) = 45 
    [16.250, 17.500) = 25 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.621 ms/op
     p(50.0000) =      2.626 ms/op
     p(90.0000) =      3.199 ms/op
     p(95.0000) =      3.387 ms/op
     p(99.0000) =      4.407 ms/op
     p(99.9000) =      9.822 ms/op
     p(99.9900) =     15.913 ms/op
     p(99.9990) =     17.311 ms/op
     p(99.9999) =     19.333 ms/op
    p(100.0000) =     19.333 ms/op


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
# Warmup Iteration   1: 5.204 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 3.209 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.128 ±(99.9%) 0.010 ms/op
Iteration   1: 3.074 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.970 ms/op
                 listUser·p0.50:   3.002 ms/op
                 listUser·p0.90:   3.940 ms/op
                 listUser·p0.95:   4.424 ms/op
                 listUser·p0.99:   5.669 ms/op
                 listUser·p0.999:  9.798 ms/op
                 listUser·p0.9999: 11.708 ms/op
                 listUser·p1.00:   12.501 ms/op

Iteration   2: 3.137 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.952 ms/op
                 listUser·p0.50:   3.052 ms/op
                 listUser·p0.90:   4.080 ms/op
                 listUser·p0.95:   4.653 ms/op
                 listUser·p0.99:   5.890 ms/op
                 listUser·p0.999:  10.469 ms/op
                 listUser·p0.9999: 12.747 ms/op
                 listUser·p1.00:   13.926 ms/op

Iteration   3: 3.117 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.693 ms/op
                 listUser·p0.50:   3.039 ms/op
                 listUser·p0.90:   4.047 ms/op
                 listUser·p0.95:   4.628 ms/op
                 listUser·p0.99:   5.956 ms/op
                 listUser·p0.999:  9.388 ms/op
                 listUser·p0.9999: 13.480 ms/op
                 listUser·p1.00:   15.417 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 308380
  mean =      3.109 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 96 
    [ 1.250,  2.500) = 74544 
    [ 2.500,  3.750) = 187260 
    [ 3.750,  5.000) = 37472 
    [ 5.000,  6.250) = 7277 
    [ 6.250,  7.500) = 1042 
    [ 7.500,  8.750) = 152 
    [ 8.750, 10.000) = 232 
    [10.000, 11.250) = 186 
    [11.250, 12.500) = 80 
    [12.500, 13.750) = 29 
    [13.750, 15.000) = 9 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.693 ms/op
     p(50.0000) =      3.031 ms/op
     p(90.0000) =      4.022 ms/op
     p(95.0000) =      4.571 ms/op
     p(99.0000) =      5.849 ms/op
     p(99.9000) =      9.972 ms/op
     p(99.9900) =     12.700 ms/op
     p(99.9990) =     14.765 ms/op
     p(99.9999) =     15.417 ms/op
    p(100.0000) =     15.417 ms/op


# Run complete. Total time: 00:13:01

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.072 ± 0.697  ops/ms
ClientPb.existUser                       thrpt       3  12.288 ± 2.604  ops/ms
ClientPb.getUser                         thrpt       3  12.422 ± 2.883  ops/ms
ClientPb.listUser                        thrpt       3  10.315 ± 1.811  ops/ms
ClientPb.createUser                       avgt       3   2.618 ± 0.278   ms/op
ClientPb.existUser                        avgt       3   2.543 ± 0.219   ms/op
ClientPb.getUser                          avgt       3   2.587 ± 0.091   ms/op
ClientPb.listUser                         avgt       3   3.126 ± 0.260   ms/op
ClientPb.createUser                     sample  366302   2.617 ± 0.004   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.600           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.654           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.203           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.379           ms/op
ClientPb.createUser:createUser·p0.99    sample           4.252           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.961           ms/op
ClientPb.createUser:createUser·p0.9999  sample          15.626           ms/op
ClientPb.createUser:createUser·p1.00    sample          19.005           ms/op
ClientPb.existUser                      sample  373527   2.567 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.909           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.580           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.154           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.310           ms/op
ClientPb.existUser:existUser·p0.99      sample           4.063           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.508           ms/op
ClientPb.existUser:existUser·p0.9999    sample          16.185           ms/op
ClientPb.existUser:existUser·p1.00      sample          17.891           ms/op
ClientPb.getUser                        sample  367406   2.610 ± 0.004   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.621           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.626           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.199           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.387           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.407           ms/op
ClientPb.getUser:getUser·p0.999         sample           9.822           ms/op
ClientPb.getUser:getUser·p0.9999        sample          15.913           ms/op
ClientPb.getUser:getUser·p1.00          sample          19.333           ms/op
ClientPb.listUser                       sample  308380   3.109 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.693           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.031           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.022           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.571           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.849           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.972           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.700           ms/op
ClientPb.listUser:listUser·p1.00        sample          15.417           ms/op
