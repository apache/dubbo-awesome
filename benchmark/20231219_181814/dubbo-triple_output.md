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
# Warmup Iteration   1: 5.372 ops/ms
# Warmup Iteration   2: 12.105 ops/ms
# Warmup Iteration   3: 12.118 ops/ms
Iteration   1: 12.505 ops/ms
Iteration   2: 12.654 ops/ms
Iteration   3: 12.664 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.608 ±(99.9%) 1.622 ops/ms [Average]
  (min, avg, max) = (12.505, 12.608, 12.664), stdev = 0.089
  CI (99.9%): [10.985, 14.230] (assumes normal distribution)


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
# Warmup Iteration   1: 7.945 ops/ms
# Warmup Iteration   2: 12.945 ops/ms
# Warmup Iteration   3: 13.038 ops/ms
Iteration   1: 13.092 ops/ms
Iteration   2: 13.210 ops/ms
Iteration   3: 13.057 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.120 ±(99.9%) 1.465 ops/ms [Average]
  (min, avg, max) = (13.057, 13.120, 13.210), stdev = 0.080
  CI (99.9%): [11.655, 14.585] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.760 ops/ms
# Warmup Iteration   2: 12.822 ops/ms
# Warmup Iteration   3: 12.926 ops/ms
Iteration   1: 12.842 ops/ms
Iteration   2: 13.067 ops/ms
Iteration   3: 12.979 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.963 ±(99.9%) 2.066 ops/ms [Average]
  (min, avg, max) = (12.842, 12.963, 13.067), stdev = 0.113
  CI (99.9%): [10.896, 15.029] (assumes normal distribution)


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
# Warmup Iteration   1: 6.845 ops/ms
# Warmup Iteration   2: 10.513 ops/ms
# Warmup Iteration   3: 10.689 ops/ms
Iteration   1: 10.736 ops/ms
Iteration   2: 10.649 ops/ms
Iteration   3: 10.630 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.672 ±(99.9%) 1.031 ops/ms [Average]
  (min, avg, max) = (10.630, 10.672, 10.736), stdev = 0.057
  CI (99.9%): [9.640, 11.703] (assumes normal distribution)


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
# Warmup Iteration   1: 4.013 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.564 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.498 ±(99.9%) 0.004 ms/op
Iteration   1: 2.519 ±(99.9%) 0.004 ms/op
Iteration   2: 2.491 ±(99.9%) 0.005 ms/op
Iteration   3: 2.527 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.512 ±(99.9%) 0.349 ms/op [Average]
  (min, avg, max) = (2.491, 2.512, 2.527), stdev = 0.019
  CI (99.9%): [2.164, 2.861] (assumes normal distribution)


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
# Warmup Iteration   1: 3.620 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.461 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.413 ±(99.9%) 0.004 ms/op
Iteration   1: 2.414 ±(99.9%) 0.004 ms/op
Iteration   2: 2.427 ±(99.9%) 0.003 ms/op
Iteration   3: 2.453 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.431 ±(99.9%) 0.366 ms/op [Average]
  (min, avg, max) = (2.414, 2.431, 2.453), stdev = 0.020
  CI (99.9%): [2.065, 2.797] (assumes normal distribution)


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
# Warmup Iteration   1: 3.782 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.520 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.472 ±(99.9%) 0.004 ms/op
Iteration   1: 2.465 ±(99.9%) 0.004 ms/op
Iteration   2: 2.485 ±(99.9%) 0.004 ms/op
Iteration   3: 2.451 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.467 ±(99.9%) 0.313 ms/op [Average]
  (min, avg, max) = (2.451, 2.467, 2.485), stdev = 0.017
  CI (99.9%): [2.154, 2.779] (assumes normal distribution)


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
# Warmup Iteration   1: 4.710 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.993 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.987 ±(99.9%) 0.005 ms/op
Iteration   1: 2.994 ±(99.9%) 0.006 ms/op
Iteration   2: 3.010 ±(99.9%) 0.006 ms/op
Iteration   3: 2.983 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.995 ±(99.9%) 0.250 ms/op [Average]
  (min, avg, max) = (2.983, 2.995, 3.010), stdev = 0.014
  CI (99.9%): [2.746, 3.245] (assumes normal distribution)


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
# Warmup Iteration   1: 4.194 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.650 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.508 ±(99.9%) 0.005 ms/op
Iteration   1: 2.499 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.979 ms/op
                 createUser·p0.50:   2.576 ms/op
                 createUser·p0.90:   3.031 ms/op
                 createUser·p0.95:   3.150 ms/op
                 createUser·p0.99:   3.802 ms/op
                 createUser·p0.999:  10.879 ms/op
                 createUser·p0.9999: 14.130 ms/op
                 createUser·p1.00:   15.139 ms/op

Iteration   2: 2.539 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.874 ms/op
                 createUser·p0.50:   2.556 ms/op
                 createUser·p0.90:   3.113 ms/op
                 createUser·p0.95:   3.244 ms/op
                 createUser·p0.99:   3.727 ms/op
                 createUser·p0.999:  9.737 ms/op
                 createUser·p0.9999: 13.081 ms/op
                 createUser·p1.00:   13.320 ms/op

Iteration   3: 2.499 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.818 ms/op
                 createUser·p0.50:   2.560 ms/op
                 createUser·p0.90:   3.035 ms/op
                 createUser·p0.95:   3.154 ms/op
                 createUser·p0.99:   3.842 ms/op
                 createUser·p0.999:  8.667 ms/op
                 createUser·p0.9999: 11.312 ms/op
                 createUser·p1.00:   14.680 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 381834
  mean =      2.512 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 56 
    [ 1.250,  2.500) = 185467 
    [ 2.500,  3.750) = 192230 
    [ 3.750,  5.000) = 3330 
    [ 5.000,  6.250) = 291 
    [ 6.250,  7.500) = 23 
    [ 7.500,  8.750) = 67 
    [ 8.750, 10.000) = 77 
    [10.000, 11.250) = 117 
    [11.250, 12.500) = 103 
    [12.500, 13.750) = 56 
    [13.750, 15.000) = 12 
    [15.000, 16.250) = 5 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.818 ms/op
     p(50.0000) =      2.564 ms/op
     p(90.0000) =      3.060 ms/op
     p(95.0000) =      3.187 ms/op
     p(99.0000) =      3.785 ms/op
     p(99.9000) =      8.670 ms/op
     p(99.9900) =     13.107 ms/op
     p(99.9990) =     15.041 ms/op
     p(99.9999) =     15.139 ms/op
    p(100.0000) =     15.139 ms/op


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
# Warmup Iteration   1: 3.670 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.469 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.471 ±(99.9%) 0.005 ms/op
Iteration   1: 2.440 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.903 ms/op
                 existUser·p0.50:   2.462 ms/op
                 existUser·p0.90:   2.978 ms/op
                 existUser·p0.95:   3.092 ms/op
                 existUser·p0.99:   3.609 ms/op
                 existUser·p0.999:  6.992 ms/op
                 existUser·p0.9999: 14.107 ms/op
                 existUser·p1.00:   14.516 ms/op

Iteration   2: 2.460 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.850 ms/op
                 existUser·p0.50:   2.490 ms/op
                 existUser·p0.90:   3.015 ms/op
                 existUser·p0.95:   3.138 ms/op
                 existUser·p0.99:   3.592 ms/op
                 existUser·p0.999:  5.743 ms/op
                 existUser·p0.9999: 13.795 ms/op
                 existUser·p1.00:   14.172 ms/op

Iteration   3: 2.442 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.893 ms/op
                 existUser·p0.50:   2.474 ms/op
                 existUser·p0.90:   2.974 ms/op
                 existUser·p0.95:   3.084 ms/op
                 existUser·p0.99:   3.573 ms/op
                 existUser·p0.999:  7.182 ms/op
                 existUser·p0.9999: 11.862 ms/op
                 existUser·p1.00:   12.108 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 391879
  mean =      2.447 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 59 
    [ 1.250,  2.500) = 198374 
    [ 2.500,  3.750) = 190500 
    [ 3.750,  5.000) = 2180 
    [ 5.000,  6.250) = 325 
    [ 6.250,  7.500) = 84 
    [ 7.500,  8.750) = 14 
    [ 8.750, 10.000) = 49 
    [10.000, 11.250) = 83 
    [11.250, 12.500) = 122 
    [12.500, 13.750) = 58 
    [13.750, 15.000) = 31 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.850 ms/op
     p(50.0000) =      2.474 ms/op
     p(90.0000) =      2.990 ms/op
     p(95.0000) =      3.105 ms/op
     p(99.0000) =      3.588 ms/op
     p(99.9000) =      6.653 ms/op
     p(99.9900) =     13.514 ms/op
     p(99.9990) =     14.321 ms/op
     p(99.9999) =     14.516 ms/op
    p(100.0000) =     14.516 ms/op


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
# Warmup Iteration   1: 3.910 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 2.528 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.482 ±(99.9%) 0.006 ms/op
Iteration   1: 2.488 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.972 ms/op
                 getUser·p0.50:   2.507 ms/op
                 getUser·p0.90:   3.035 ms/op
                 getUser·p0.95:   3.183 ms/op
                 getUser·p0.99:   3.863 ms/op
                 getUser·p0.999:  11.690 ms/op
                 getUser·p0.9999: 13.978 ms/op
                 getUser·p1.00:   15.483 ms/op

Iteration   2: 2.483 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.899 ms/op
                 getUser·p0.50:   2.494 ms/op
                 getUser·p0.90:   3.035 ms/op
                 getUser·p0.95:   3.178 ms/op
                 getUser·p0.99:   3.883 ms/op
                 getUser·p0.999:  7.172 ms/op
                 getUser·p0.9999: 13.951 ms/op
                 getUser·p1.00:   14.828 ms/op

Iteration   3: 2.473 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.675 ms/op
                 getUser·p0.50:   2.499 ms/op
                 getUser·p0.90:   3.027 ms/op
                 getUser·p0.95:   3.166 ms/op
                 getUser·p0.99:   3.817 ms/op
                 getUser·p0.999:  6.781 ms/op
                 getUser·p0.9999: 11.798 ms/op
                 getUser·p1.00:   12.304 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 386549
  mean =      2.481 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 86 
    [ 1.250,  2.500) = 193214 
    [ 2.500,  3.750) = 188549 
    [ 3.750,  5.000) = 3774 
    [ 5.000,  6.250) = 528 
    [ 6.250,  7.500) = 11 
    [ 7.500,  8.750) = 15 
    [ 8.750, 10.000) = 82 
    [10.000, 11.250) = 63 
    [11.250, 12.500) = 83 
    [12.500, 13.750) = 103 
    [13.750, 15.000) = 39 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.675 ms/op
     p(50.0000) =      2.499 ms/op
     p(90.0000) =      3.031 ms/op
     p(95.0000) =      3.178 ms/op
     p(99.0000) =      3.854 ms/op
     p(99.9000) =      8.228 ms/op
     p(99.9900) =     13.774 ms/op
     p(99.9990) =     14.785 ms/op
     p(99.9999) =     15.483 ms/op
    p(100.0000) =     15.483 ms/op


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
# Warmup Iteration   1: 4.599 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.034 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.008 ±(99.9%) 0.008 ms/op
Iteration   1: 2.967 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.642 ms/op
                 listUser·p0.50:   2.900 ms/op
                 listUser·p0.90:   3.826 ms/op
                 listUser·p0.95:   4.309 ms/op
                 listUser·p0.99:   5.600 ms/op
                 listUser·p0.999:  9.421 ms/op
                 listUser·p0.9999: 10.702 ms/op
                 listUser·p1.00:   11.190 ms/op

Iteration   2: 2.957 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.868 ms/op
                 listUser·p0.50:   2.900 ms/op
                 listUser·p0.90:   3.805 ms/op
                 listUser·p0.95:   4.276 ms/op
                 listUser·p0.99:   5.415 ms/op
                 listUser·p0.999:  9.614 ms/op
                 listUser·p0.9999: 11.158 ms/op
                 listUser·p1.00:   12.386 ms/op

Iteration   3: 2.944 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.939 ms/op
                 listUser·p0.50:   2.892 ms/op
                 listUser·p0.90:   3.793 ms/op
                 listUser·p0.95:   4.268 ms/op
                 listUser·p0.99:   5.374 ms/op
                 listUser·p0.999:  9.067 ms/op
                 listUser·p0.9999: 10.450 ms/op
                 listUser·p1.00:   11.370 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 324443
  mean =      2.956 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 127 
    [ 1.250,  2.500) = 101788 
    [ 2.500,  3.750) = 187016 
    [ 3.750,  5.000) = 29395 
    [ 5.000,  6.250) = 4870 
    [ 6.250,  7.500) = 518 
    [ 7.500,  8.750) = 272 
    [ 8.750, 10.000) = 290 
    [10.000, 11.250) = 158 
    [11.250, 12.500) = 9 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.642 ms/op
     p(50.0000) =      2.896 ms/op
     p(90.0000) =      3.809 ms/op
     p(95.0000) =      4.284 ms/op
     p(99.0000) =      5.472 ms/op
     p(99.9000) =      9.348 ms/op
     p(99.9900) =     10.945 ms/op
     p(99.9990) =     11.831 ms/op
     p(99.9999) =     12.386 ms/op
    p(100.0000) =     12.386 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.608 ± 1.622  ops/ms
ClientPb.existUser                       thrpt       3  13.120 ± 1.465  ops/ms
ClientPb.getUser                         thrpt       3  12.963 ± 2.066  ops/ms
ClientPb.listUser                        thrpt       3  10.672 ± 1.031  ops/ms
ClientPb.createUser                       avgt       3   2.512 ± 0.349   ms/op
ClientPb.existUser                        avgt       3   2.431 ± 0.366   ms/op
ClientPb.getUser                          avgt       3   2.467 ± 0.313   ms/op
ClientPb.listUser                         avgt       3   2.995 ± 0.250   ms/op
ClientPb.createUser                     sample  381834   2.512 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.818           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.564           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.060           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.187           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.785           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.670           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.107           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.139           ms/op
ClientPb.existUser                      sample  391879   2.447 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.850           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.474           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.990           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.105           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.588           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.653           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.514           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.516           ms/op
ClientPb.getUser                        sample  386549   2.481 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.675           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.499           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.031           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.178           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.854           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.228           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.774           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.483           ms/op
ClientPb.listUser                       sample  324443   2.956 ± 0.004   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.642           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.896           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.809           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.284           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.472           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.348           ms/op
ClientPb.listUser:listUser·p0.9999      sample          10.945           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.386           ms/op
