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
# Warmup Iteration   1: 4.808 ops/ms
# Warmup Iteration   2: 12.188 ops/ms
# Warmup Iteration   3: 12.246 ops/ms
Iteration   1: 12.356 ops/ms
Iteration   2: 12.478 ops/ms
Iteration   3: 12.419 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.418 ±(99.9%) 1.112 ops/ms [Average]
  (min, avg, max) = (12.356, 12.418, 12.478), stdev = 0.061
  CI (99.9%): [11.305, 13.530] (assumes normal distribution)


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
# Warmup Iteration   1: 7.997 ops/ms
# Warmup Iteration   2: 13.059 ops/ms
# Warmup Iteration   3: 12.969 ops/ms
Iteration   1: 12.999 ops/ms
Iteration   2: 13.093 ops/ms
Iteration   3: 12.992 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.028 ±(99.9%) 1.035 ops/ms [Average]
  (min, avg, max) = (12.992, 13.028, 13.093), stdev = 0.057
  CI (99.9%): [11.993, 14.063] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.539 ops/ms
# Warmup Iteration   2: 12.642 ops/ms
# Warmup Iteration   3: 12.641 ops/ms
Iteration   1: 12.801 ops/ms
Iteration   2: 12.782 ops/ms
Iteration   3: 12.741 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.774 ±(99.9%) 0.559 ops/ms [Average]
  (min, avg, max) = (12.741, 12.774, 12.801), stdev = 0.031
  CI (99.9%): [12.216, 13.333] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 6.811 ops/ms
# Warmup Iteration   2: 10.470 ops/ms
# Warmup Iteration   3: 10.519 ops/ms
Iteration   1: 10.656 ops/ms
Iteration   2: 10.622 ops/ms
Iteration   3: 10.626 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.635 ±(99.9%) 0.338 ops/ms [Average]
  (min, avg, max) = (10.622, 10.635, 10.656), stdev = 0.019
  CI (99.9%): [10.297, 10.973] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 3.907 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.599 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.536 ±(99.9%) 0.004 ms/op
Iteration   1: 2.599 ±(99.9%) 0.004 ms/op
Iteration   2: 2.520 ±(99.9%) 0.004 ms/op
Iteration   3: 2.540 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.553 ±(99.9%) 0.745 ms/op [Average]
  (min, avg, max) = (2.520, 2.553, 2.599), stdev = 0.041
  CI (99.9%): [1.808, 3.299] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 3.707 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.467 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.454 ±(99.9%) 0.005 ms/op
Iteration   1: 2.450 ±(99.9%) 0.003 ms/op
Iteration   2: 2.426 ±(99.9%) 0.003 ms/op
Iteration   3: 2.419 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.432 ±(99.9%) 0.299 ms/op [Average]
  (min, avg, max) = (2.419, 2.432, 2.450), stdev = 0.016
  CI (99.9%): [2.133, 2.731] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 3.976 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.546 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.476 ±(99.9%) 0.004 ms/op
Iteration   1: 2.509 ±(99.9%) 0.004 ms/op
Iteration   2: 2.464 ±(99.9%) 0.004 ms/op
Iteration   3: 2.473 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.482 ±(99.9%) 0.428 ms/op [Average]
  (min, avg, max) = (2.464, 2.482, 2.509), stdev = 0.023
  CI (99.9%): [2.054, 2.910] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.525 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.023 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.001 ±(99.9%) 0.005 ms/op
Iteration   1: 2.993 ±(99.9%) 0.005 ms/op
Iteration   2: 2.959 ±(99.9%) 0.006 ms/op
Iteration   3: 2.989 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.980 ±(99.9%) 0.345 ms/op [Average]
  (min, avg, max) = (2.959, 2.980, 2.993), stdev = 0.019
  CI (99.9%): [2.635, 3.326] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.174 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.666 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.516 ±(99.9%) 0.006 ms/op
Iteration   1: 2.505 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.988 ms/op
                 createUser·p0.50:   2.613 ms/op
                 createUser·p0.90:   3.035 ms/op
                 createUser·p0.95:   3.138 ms/op
                 createUser·p0.99:   3.559 ms/op
                 createUser·p0.999:  11.819 ms/op
                 createUser·p0.9999: 17.138 ms/op
                 createUser·p1.00:   18.022 ms/op

Iteration   2: 2.529 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.929 ms/op
                 createUser·p0.50:   2.617 ms/op
                 createUser·p0.90:   3.072 ms/op
                 createUser·p0.95:   3.178 ms/op
                 createUser·p0.99:   3.707 ms/op
                 createUser·p0.999:  10.125 ms/op
                 createUser·p0.9999: 13.435 ms/op
                 createUser·p1.00:   13.615 ms/op

Iteration   3: 2.526 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.919 ms/op
                 createUser·p0.50:   2.589 ms/op
                 createUser·p0.90:   3.068 ms/op
                 createUser·p0.95:   3.191 ms/op
                 createUser·p0.99:   3.850 ms/op
                 createUser·p0.999:  8.807 ms/op
                 createUser·p0.9999: 11.802 ms/op
                 createUser·p1.00:   15.155 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 380479
  mean =      2.520 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 54 
    [ 1.250,  2.500) = 182483 
    [ 2.500,  3.750) = 194430 
    [ 3.750,  5.000) = 2719 
    [ 5.000,  6.250) = 376 
    [ 6.250,  7.500) = 31 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 58 
    [10.000, 11.250) = 100 
    [11.250, 12.500) = 62 
    [12.500, 13.750) = 118 
    [13.750, 15.000) = 13 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 26 
    [17.500, 18.750) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.919 ms/op
     p(50.0000) =      2.605 ms/op
     p(90.0000) =      3.060 ms/op
     p(95.0000) =      3.170 ms/op
     p(99.0000) =      3.707 ms/op
     p(99.9000) =      9.167 ms/op
     p(99.9900) =     14.237 ms/op
     p(99.9990) =     17.845 ms/op
     p(99.9999) =     18.022 ms/op
    p(100.0000) =     18.022 ms/op


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
# Warmup Iteration   1: 3.789 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.485 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.483 ±(99.9%) 0.005 ms/op
Iteration   1: 2.473 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.961 ms/op
                 existUser·p0.50:   2.519 ms/op
                 existUser·p0.90:   3.015 ms/op
                 existUser·p0.95:   3.121 ms/op
                 existUser·p0.99:   3.564 ms/op
                 existUser·p0.999:  6.742 ms/op
                 existUser·p0.9999: 14.254 ms/op
                 existUser·p1.00:   14.975 ms/op

Iteration   2: 2.462 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.809 ms/op
                 existUser·p0.50:   2.511 ms/op
                 existUser·p0.90:   2.994 ms/op
                 existUser·p0.95:   3.097 ms/op
                 existUser·p0.99:   3.502 ms/op
                 existUser·p0.999:  8.284 ms/op
                 existUser·p0.9999: 13.157 ms/op
                 existUser·p1.00:   13.500 ms/op

Iteration   3: 2.466 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.593 ms/op
                 existUser·p0.50:   2.478 ms/op
                 existUser·p0.90:   3.019 ms/op
                 existUser·p0.95:   3.150 ms/op
                 existUser·p0.99:   3.785 ms/op
                 existUser·p0.999:  6.143 ms/op
                 existUser·p0.9999: 12.371 ms/op
                 existUser·p1.00:   13.304 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 388626
  mean =      2.467 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 39 
    [ 1.250,  2.500) = 194449 
    [ 2.500,  3.750) = 191047 
    [ 3.750,  5.000) = 2360 
    [ 5.000,  6.250) = 320 
    [ 6.250,  7.500) = 53 
    [ 7.500,  8.750) = 9 
    [ 8.750, 10.000) = 70 
    [10.000, 11.250) = 62 
    [11.250, 12.500) = 89 
    [12.500, 13.750) = 103 
    [13.750, 15.000) = 25 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.593 ms/op
     p(50.0000) =      2.499 ms/op
     p(90.0000) =      3.011 ms/op
     p(95.0000) =      3.121 ms/op
     p(99.0000) =      3.625 ms/op
     p(99.9000) =      6.590 ms/op
     p(99.9900) =     13.500 ms/op
     p(99.9990) =     14.764 ms/op
     p(99.9999) =     14.975 ms/op
    p(100.0000) =     14.975 ms/op


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
# Warmup Iteration   1: 4.155 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 2.628 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.536 ±(99.9%) 0.006 ms/op
Iteration   1: 2.556 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.815 ms/op
                 getUser·p0.50:   2.572 ms/op
                 getUser·p0.90:   3.113 ms/op
                 getUser·p0.95:   3.219 ms/op
                 getUser·p0.99:   3.781 ms/op
                 getUser·p0.999:  11.557 ms/op
                 getUser·p0.9999: 14.459 ms/op
                 getUser·p1.00:   15.434 ms/op

Iteration   2: 2.567 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.981 ms/op
                 getUser·p0.50:   2.580 ms/op
                 getUser·p0.90:   3.125 ms/op
                 getUser·p0.95:   3.260 ms/op
                 getUser·p0.99:   4.202 ms/op
                 getUser·p0.999:  8.985 ms/op
                 getUser·p0.9999: 14.230 ms/op
                 getUser·p1.00:   15.172 ms/op

Iteration   3: 2.528 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.843 ms/op
                 getUser·p0.50:   2.564 ms/op
                 getUser·p0.90:   3.080 ms/op
                 getUser·p0.95:   3.183 ms/op
                 getUser·p0.99:   3.740 ms/op
                 getUser·p0.999:  8.348 ms/op
                 getUser·p0.9999: 11.530 ms/op
                 getUser·p1.00:   11.878 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 376137
  mean =      2.550 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 46 
    [ 1.250,  2.500) = 183521 
    [ 2.500,  3.750) = 188022 
    [ 3.750,  5.000) = 3672 
    [ 5.000,  6.250) = 440 
    [ 6.250,  7.500) = 19 
    [ 7.500,  8.750) = 51 
    [ 8.750, 10.000) = 102 
    [10.000, 11.250) = 57 
    [11.250, 12.500) = 79 
    [12.500, 13.750) = 74 
    [13.750, 15.000) = 52 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.815 ms/op
     p(50.0000) =      2.572 ms/op
     p(90.0000) =      3.105 ms/op
     p(95.0000) =      3.219 ms/op
     p(99.0000) =      3.867 ms/op
     p(99.9000) =      8.421 ms/op
     p(99.9900) =     14.244 ms/op
     p(99.9990) =     14.909 ms/op
     p(99.9999) =     15.434 ms/op
    p(100.0000) =     15.434 ms/op


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
# Warmup Iteration   1: 4.741 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 3.093 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.036 ±(99.9%) 0.009 ms/op
Iteration   1: 3.048 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.023 ms/op
                 listUser·p0.50:   2.986 ms/op
                 listUser·p0.90:   3.928 ms/op
                 listUser·p0.95:   4.448 ms/op
                 listUser·p0.99:   5.767 ms/op
                 listUser·p0.999:  9.499 ms/op
                 listUser·p0.9999: 14.197 ms/op
                 listUser·p1.00:   14.795 ms/op

Iteration   2: 3.036 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.063 ms/op
                 listUser·p0.50:   2.974 ms/op
                 listUser·p0.90:   3.908 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   5.562 ms/op
                 listUser·p0.999:  10.295 ms/op
                 listUser·p0.9999: 12.897 ms/op
                 listUser·p1.00:   14.205 ms/op

Iteration   3: 3.019 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.859 ms/op
                 listUser·p0.50:   2.961 ms/op
                 listUser·p0.90:   3.867 ms/op
                 listUser·p0.95:   4.350 ms/op
                 listUser·p0.99:   5.571 ms/op
                 listUser·p0.999:  9.750 ms/op
                 listUser·p0.9999: 12.095 ms/op
                 listUser·p1.00:   13.173 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 316080
  mean =      3.034 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 83 
    [ 1.250,  2.500) = 88257 
    [ 2.500,  3.750) = 187474 
    [ 3.750,  5.000) = 33043 
    [ 5.000,  6.250) = 5862 
    [ 6.250,  7.500) = 697 
    [ 7.500,  8.750) = 159 
    [ 8.750, 10.000) = 219 
    [10.000, 11.250) = 152 
    [11.250, 12.500) = 84 
    [12.500, 13.750) = 31 
    [13.750, 15.000) = 19 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.859 ms/op
     p(50.0000) =      2.974 ms/op
     p(90.0000) =      3.899 ms/op
     p(95.0000) =      4.399 ms/op
     p(99.0000) =      5.620 ms/op
     p(99.9000) =      9.863 ms/op
     p(99.9900) =     13.140 ms/op
     p(99.9990) =     14.386 ms/op
     p(99.9999) =     14.795 ms/op
    p(100.0000) =     14.795 ms/op


# Run complete. Total time: 00:13:00

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.418 ± 1.112  ops/ms
ClientPb.existUser                       thrpt       3  13.028 ± 1.035  ops/ms
ClientPb.getUser                         thrpt       3  12.774 ± 0.559  ops/ms
ClientPb.listUser                        thrpt       3  10.635 ± 0.338  ops/ms
ClientPb.createUser                       avgt       3   2.553 ± 0.745   ms/op
ClientPb.existUser                        avgt       3   2.432 ± 0.299   ms/op
ClientPb.getUser                          avgt       3   2.482 ± 0.428   ms/op
ClientPb.listUser                         avgt       3   2.980 ± 0.345   ms/op
ClientPb.createUser                     sample  380479   2.520 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.919           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.605           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.060           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.170           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.707           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.167           ms/op
ClientPb.createUser:createUser·p0.9999  sample          14.237           ms/op
ClientPb.createUser:createUser·p1.00    sample          18.022           ms/op
ClientPb.existUser                      sample  388626   2.467 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.593           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.499           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.011           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.121           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.625           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.590           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.500           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.975           ms/op
ClientPb.getUser                        sample  376137   2.550 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.815           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.572           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.105           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.219           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.867           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.421           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.244           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.434           ms/op
ClientPb.listUser                       sample  316080   3.034 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.859           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.974           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.899           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.399           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.620           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.863           ms/op
ClientPb.listUser:listUser·p0.9999      sample          13.140           ms/op
ClientPb.listUser:listUser·p1.00        sample          14.795           ms/op
