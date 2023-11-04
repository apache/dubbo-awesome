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
# Warmup Iteration   1: 4.767 ops/ms
# Warmup Iteration   2: 11.616 ops/ms
# Warmup Iteration   3: 12.319 ops/ms
Iteration   1: 12.342 ops/ms
Iteration   2: 12.373 ops/ms
Iteration   3: 12.526 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.414 ±(99.9%) 1.795 ops/ms [Average]
  (min, avg, max) = (12.342, 12.414, 12.526), stdev = 0.098
  CI (99.9%): [10.619, 14.208] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:54
# Fork: 1 of 1
# Warmup Iteration   1: 7.755 ops/ms
# Warmup Iteration   2: 12.853 ops/ms
# Warmup Iteration   3: 12.958 ops/ms
Iteration   1: 12.887 ops/ms
Iteration   2: 12.867 ops/ms
Iteration   3: 12.900 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.885 ±(99.9%) 0.303 ops/ms [Average]
  (min, avg, max) = (12.867, 12.885, 12.900), stdev = 0.017
  CI (99.9%): [12.582, 13.188] (assumes normal distribution)


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
# Warmup Iteration   1: 6.819 ops/ms
# Warmup Iteration   2: 12.453 ops/ms
# Warmup Iteration   3: 12.541 ops/ms
Iteration   1: 12.641 ops/ms
Iteration   2: 12.599 ops/ms
Iteration   3: 12.650 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.630 ±(99.9%) 0.499 ops/ms [Average]
  (min, avg, max) = (12.599, 12.630, 12.650), stdev = 0.027
  CI (99.9%): [12.131, 13.129] (assumes normal distribution)


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
# Warmup Iteration   1: 6.155 ops/ms
# Warmup Iteration   2: 10.350 ops/ms
# Warmup Iteration   3: 10.408 ops/ms
Iteration   1: 10.345 ops/ms
Iteration   2: 10.465 ops/ms
Iteration   3: 10.394 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.401 ±(99.9%) 1.107 ops/ms [Average]
  (min, avg, max) = (10.345, 10.401, 10.465), stdev = 0.061
  CI (99.9%): [9.294, 11.509] (assumes normal distribution)


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
# Warmup Iteration   1: 4.174 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.647 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.544 ±(99.9%) 0.004 ms/op
Iteration   1: 2.581 ±(99.9%) 0.004 ms/op
Iteration   2: 2.582 ±(99.9%) 0.004 ms/op
Iteration   3: 2.551 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.571 ±(99.9%) 0.322 ms/op [Average]
  (min, avg, max) = (2.551, 2.571, 2.582), stdev = 0.018
  CI (99.9%): [2.250, 2.893] (assumes normal distribution)


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
# Warmup Iteration   1: 3.946 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.508 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.511 ±(99.9%) 0.003 ms/op
Iteration   1: 2.480 ±(99.9%) 0.003 ms/op
Iteration   2: 2.468 ±(99.9%) 0.005 ms/op
Iteration   3: 2.457 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.468 ±(99.9%) 0.211 ms/op [Average]
  (min, avg, max) = (2.457, 2.468, 2.480), stdev = 0.012
  CI (99.9%): [2.257, 2.679] (assumes normal distribution)


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
# Warmup Iteration   1: 4.115 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.623 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.553 ±(99.9%) 0.004 ms/op
Iteration   1: 2.571 ±(99.9%) 0.004 ms/op
Iteration   2: 2.570 ±(99.9%) 0.004 ms/op
Iteration   3: 2.552 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.565 ±(99.9%) 0.194 ms/op [Average]
  (min, avg, max) = (2.552, 2.565, 2.571), stdev = 0.011
  CI (99.9%): [2.370, 2.759] (assumes normal distribution)


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
# Warmup Iteration   1: 4.931 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.144 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.044 ±(99.9%) 0.004 ms/op
Iteration   1: 3.076 ±(99.9%) 0.005 ms/op
Iteration   2: 3.073 ±(99.9%) 0.006 ms/op
Iteration   3: 3.031 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.060 ±(99.9%) 0.460 ms/op [Average]
  (min, avg, max) = (3.031, 3.060, 3.076), stdev = 0.025
  CI (99.9%): [2.600, 3.520] (assumes normal distribution)


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
# Warmup Iteration   1: 4.496 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 2.781 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.592 ±(99.9%) 0.006 ms/op
Iteration   1: 2.597 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.018 ms/op
                 createUser·p0.50:   2.646 ms/op
                 createUser·p0.90:   3.158 ms/op
                 createUser·p0.95:   3.285 ms/op
                 createUser·p0.99:   3.981 ms/op
                 createUser·p0.999:  12.009 ms/op
                 createUser·p0.9999: 14.185 ms/op
                 createUser·p1.00:   15.368 ms/op

Iteration   2: 2.566 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.047 ms/op
                 createUser·p0.50:   2.638 ms/op
                 createUser·p0.90:   3.109 ms/op
                 createUser·p0.95:   3.219 ms/op
                 createUser·p0.99:   3.809 ms/op
                 createUser·p0.999:  11.253 ms/op
                 createUser·p0.9999: 13.468 ms/op
                 createUser·p1.00:   13.779 ms/op

Iteration   3: 2.580 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.067 ms/op
                 createUser·p0.50:   2.662 ms/op
                 createUser·p0.90:   3.129 ms/op
                 createUser·p0.95:   3.265 ms/op
                 createUser·p0.99:   4.030 ms/op
                 createUser·p0.999:  8.768 ms/op
                 createUser·p0.9999: 13.252 ms/op
                 createUser·p1.00:   15.385 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 371612
  mean =      2.581 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 33 
    [ 1.250,  2.500) = 175417 
    [ 2.500,  3.750) = 190918 
    [ 3.750,  5.000) = 4283 
    [ 5.000,  6.250) = 482 
    [ 6.250,  7.500) = 57 
    [ 7.500,  8.750) = 39 
    [ 8.750, 10.000) = 53 
    [10.000, 11.250) = 46 
    [11.250, 12.500) = 110 
    [12.500, 13.750) = 134 
    [13.750, 15.000) = 35 
    [15.000, 16.250) = 5 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.018 ms/op
     p(50.0000) =      2.650 ms/op
     p(90.0000) =      3.133 ms/op
     p(95.0000) =      3.256 ms/op
     p(99.0000) =      3.932 ms/op
     p(99.9000) =      9.355 ms/op
     p(99.9900) =     13.954 ms/op
     p(99.9990) =     15.012 ms/op
     p(99.9999) =     15.385 ms/op
    p(100.0000) =     15.385 ms/op


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
# Warmup Iteration   1: 3.900 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.495 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.495 ±(99.9%) 0.006 ms/op
Iteration   1: 2.486 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.919 ms/op
                 existUser·p0.50:   2.548 ms/op
                 existUser·p0.90:   3.023 ms/op
                 existUser·p0.95:   3.142 ms/op
                 existUser·p0.99:   3.723 ms/op
                 existUser·p0.999:  5.518 ms/op
                 existUser·p0.9999: 14.177 ms/op
                 existUser·p1.00:   15.041 ms/op

Iteration   2: 2.482 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.984 ms/op
                 existUser·p0.50:   2.609 ms/op
                 existUser·p0.90:   3.002 ms/op
                 existUser·p0.95:   3.097 ms/op
                 existUser·p0.99:   3.482 ms/op
                 existUser·p0.999:  7.605 ms/op
                 existUser·p0.9999: 16.484 ms/op
                 existUser·p1.00:   17.498 ms/op

Iteration   3: 2.506 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.678 ms/op
                 existUser·p0.50:   2.564 ms/op
                 existUser·p0.90:   3.043 ms/op
                 existUser·p0.95:   3.178 ms/op
                 existUser·p0.99:   4.104 ms/op
                 existUser·p0.999:  8.536 ms/op
                 existUser·p0.9999: 11.604 ms/op
                 existUser·p1.00:   12.829 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 384957
  mean =      2.491 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 43 
    [ 1.250,  2.500) = 187289 
    [ 2.500,  3.750) = 193575 
    [ 3.750,  5.000) = 3152 
    [ 5.000,  6.250) = 386 
    [ 6.250,  7.500) = 142 
    [ 7.500,  8.750) = 29 
    [ 8.750, 10.000) = 17 
    [10.000, 11.250) = 73 
    [11.250, 12.500) = 79 
    [12.500, 13.750) = 74 
    [13.750, 15.000) = 63 
    [15.000, 16.250) = 10 
    [16.250, 17.500) = 25 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.678 ms/op
     p(50.0000) =      2.572 ms/op
     p(90.0000) =      3.023 ms/op
     p(95.0000) =      3.138 ms/op
     p(99.0000) =      3.785 ms/op
     p(99.9000) =      7.028 ms/op
     p(99.9900) =     14.910 ms/op
     p(99.9990) =     17.048 ms/op
     p(99.9999) =     17.498 ms/op
    p(100.0000) =     17.498 ms/op


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
# Warmup Iteration   1: 4.110 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.588 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.540 ±(99.9%) 0.006 ms/op
Iteration   1: 2.560 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.853 ms/op
                 getUser·p0.50:   2.564 ms/op
                 getUser·p0.90:   3.125 ms/op
                 getUser·p0.95:   3.289 ms/op
                 getUser·p0.99:   4.129 ms/op
                 getUser·p0.999:  12.026 ms/op
                 getUser·p0.9999: 14.197 ms/op
                 getUser·p1.00:   14.369 ms/op

Iteration   2: 2.545 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.034 ms/op
                 getUser·p0.50:   2.585 ms/op
                 getUser·p0.90:   3.088 ms/op
                 getUser·p0.95:   3.203 ms/op
                 getUser·p0.99:   3.842 ms/op
                 getUser·p0.999:  6.140 ms/op
                 getUser·p0.9999: 13.531 ms/op
                 getUser·p1.00:   14.746 ms/op

Iteration   3: 2.582 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.997 ms/op
                 getUser·p0.50:   2.626 ms/op
                 getUser·p0.90:   3.138 ms/op
                 getUser·p0.95:   3.305 ms/op
                 getUser·p0.99:   4.506 ms/op
                 getUser·p0.999:  8.030 ms/op
                 getUser·p0.9999: 12.282 ms/op
                 getUser·p1.00:   12.648 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 374291
  mean =      2.562 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 60 
    [ 1.250,  2.500) = 180848 
    [ 2.500,  3.750) = 187051 
    [ 3.750,  5.000) = 4812 
    [ 5.000,  6.250) = 1061 
    [ 6.250,  7.500) = 85 
    [ 7.500,  8.750) = 30 
    [ 8.750, 10.000) = 47 
    [10.000, 11.250) = 60 
    [11.250, 12.500) = 84 
    [12.500, 13.750) = 120 
    [13.750, 15.000) = 33 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.853 ms/op
     p(50.0000) =      2.593 ms/op
     p(90.0000) =      3.117 ms/op
     p(95.0000) =      3.265 ms/op
     p(99.0000) =      4.125 ms/op
     p(99.9000) =      7.551 ms/op
     p(99.9900) =     13.706 ms/op
     p(99.9990) =     14.623 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.722 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.113 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.076 ±(99.9%) 0.009 ms/op
Iteration   1: 3.063 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.603 ms/op
                 listUser·p0.50:   3.002 ms/op
                 listUser·p0.90:   3.957 ms/op
                 listUser·p0.95:   4.465 ms/op
                 listUser·p0.99:   5.644 ms/op
                 listUser·p0.999:  9.519 ms/op
                 listUser·p0.9999: 11.562 ms/op
                 listUser·p1.00:   11.878 ms/op

Iteration   2: 3.061 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.930 ms/op
                 listUser·p0.50:   3.002 ms/op
                 listUser·p0.90:   3.953 ms/op
                 listUser·p0.95:   4.481 ms/op
                 listUser·p0.99:   5.693 ms/op
                 listUser·p0.999:  9.578 ms/op
                 listUser·p0.9999: 13.053 ms/op
                 listUser·p1.00:   14.287 ms/op

Iteration   3: 3.104 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.059 ms/op
                 listUser·p0.50:   3.027 ms/op
                 listUser·p0.90:   4.030 ms/op
                 listUser·p0.95:   4.530 ms/op
                 listUser·p0.99:   5.898 ms/op
                 listUser·p0.999:  9.372 ms/op
                 listUser·p0.9999: 11.297 ms/op
                 listUser·p1.00:   12.829 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 311801
  mean =      3.076 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 91 
    [ 1.250,  2.500) = 82134 
    [ 2.500,  3.750) = 185704 
    [ 3.750,  5.000) = 35606 
    [ 5.000,  6.250) = 6582 
    [ 6.250,  7.500) = 968 
    [ 7.500,  8.750) = 237 
    [ 8.750, 10.000) = 282 
    [10.000, 11.250) = 137 
    [11.250, 12.500) = 38 
    [12.500, 13.750) = 21 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.603 ms/op
     p(50.0000) =      3.011 ms/op
     p(90.0000) =      3.981 ms/op
     p(95.0000) =      4.497 ms/op
     p(99.0000) =      5.759 ms/op
     p(99.9000) =      9.470 ms/op
     p(99.9900) =     12.088 ms/op
     p(99.9990) =     13.702 ms/op
     p(99.9999) =     14.287 ms/op
    p(100.0000) =     14.287 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.414 ± 1.795  ops/ms
ClientPb.existUser                       thrpt       3  12.885 ± 0.303  ops/ms
ClientPb.getUser                         thrpt       3  12.630 ± 0.499  ops/ms
ClientPb.listUser                        thrpt       3  10.401 ± 1.107  ops/ms
ClientPb.createUser                       avgt       3   2.571 ± 0.322   ms/op
ClientPb.existUser                        avgt       3   2.468 ± 0.211   ms/op
ClientPb.getUser                          avgt       3   2.565 ± 0.194   ms/op
ClientPb.listUser                         avgt       3   3.060 ± 0.460   ms/op
ClientPb.createUser                     sample  371612   2.581 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.018           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.650           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.133           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.256           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.932           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.355           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.954           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.385           ms/op
ClientPb.existUser                      sample  384957   2.491 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.678           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.572           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.023           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.138           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.785           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.028           ms/op
ClientPb.existUser:existUser·p0.9999    sample          14.910           ms/op
ClientPb.existUser:existUser·p1.00      sample          17.498           ms/op
ClientPb.getUser                        sample  374291   2.562 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.853           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.593           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.117           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.265           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.125           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.551           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.706           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.746           ms/op
ClientPb.listUser                       sample  311801   3.076 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.603           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.011           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.981           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.497           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.759           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.470           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.088           ms/op
ClientPb.listUser:listUser·p1.00        sample          14.287           ms/op
