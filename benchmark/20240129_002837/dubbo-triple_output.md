# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.630 ops/ms
# Warmup Iteration   2: 11.866 ops/ms
# Warmup Iteration   3: 12.356 ops/ms
Iteration   1: 12.508 ops/ms
Iteration   2: 12.616 ops/ms
Iteration   3: 12.668 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.597 ±(99.9%) 1.491 ops/ms [Average]
  (min, avg, max) = (12.508, 12.597, 12.668), stdev = 0.082
  CI (99.9%): [11.106, 14.089] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 7.794 ops/ms
# Warmup Iteration   2: 12.990 ops/ms
# Warmup Iteration   3: 12.855 ops/ms
Iteration   1: 13.002 ops/ms
Iteration   2: 12.964 ops/ms
Iteration   3: 13.035 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.000 ±(99.9%) 0.649 ops/ms [Average]
  (min, avg, max) = (12.964, 13.000, 13.035), stdev = 0.036
  CI (99.9%): [12.351, 13.649] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.237 ops/ms
# Warmup Iteration   2: 12.544 ops/ms
# Warmup Iteration   3: 12.918 ops/ms
Iteration   1: 12.924 ops/ms
Iteration   2: 12.846 ops/ms
Iteration   3: 12.852 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.874 ±(99.9%) 0.789 ops/ms [Average]
  (min, avg, max) = (12.846, 12.874, 12.924), stdev = 0.043
  CI (99.9%): [12.086, 13.663] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 6.437 ops/ms
# Warmup Iteration   2: 10.439 ops/ms
# Warmup Iteration   3: 10.592 ops/ms
Iteration   1: 10.680 ops/ms
Iteration   2: 10.599 ops/ms
Iteration   3: 10.700 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.660 ±(99.9%) 0.978 ops/ms [Average]
  (min, avg, max) = (10.599, 10.660, 10.700), stdev = 0.054
  CI (99.9%): [9.682, 11.637] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:39
# Fork: 1 of 1
# Warmup Iteration   1: 4.154 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.626 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.535 ±(99.9%) 0.004 ms/op
Iteration   1: 2.537 ±(99.9%) 0.003 ms/op
Iteration   2: 2.577 ±(99.9%) 0.004 ms/op
Iteration   3: 2.546 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.553 ±(99.9%) 0.385 ms/op [Average]
  (min, avg, max) = (2.537, 2.553, 2.577), stdev = 0.021
  CI (99.9%): [2.168, 2.938] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:34
# Fork: 1 of 1
# Warmup Iteration   1: 3.731 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.447 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.444 ±(99.9%) 0.003 ms/op
Iteration   1: 2.426 ±(99.9%) 0.004 ms/op
Iteration   2: 2.440 ±(99.9%) 0.004 ms/op
Iteration   3: 2.456 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.441 ±(99.9%) 0.281 ms/op [Average]
  (min, avg, max) = (2.426, 2.441, 2.456), stdev = 0.015
  CI (99.9%): [2.160, 2.722] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:29
# Fork: 1 of 1
# Warmup Iteration   1: 3.967 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.511 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.472 ±(99.9%) 0.004 ms/op
Iteration   1: 2.473 ±(99.9%) 0.004 ms/op
Iteration   2: 2.475 ±(99.9%) 0.003 ms/op
Iteration   3: 2.504 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.484 ±(99.9%) 0.317 ms/op [Average]
  (min, avg, max) = (2.473, 2.484, 2.504), stdev = 0.017
  CI (99.9%): [2.167, 2.802] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 4.931 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.039 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.046 ±(99.9%) 0.005 ms/op
Iteration   1: 3.004 ±(99.9%) 0.006 ms/op
Iteration   2: 3.028 ±(99.9%) 0.007 ms/op
Iteration   3: 3.037 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.023 ±(99.9%) 0.308 ms/op [Average]
  (min, avg, max) = (3.004, 3.023, 3.037), stdev = 0.017
  CI (99.9%): [2.715, 3.331] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:19
# Fork: 1 of 1
# Warmup Iteration   1: 4.461 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 2.689 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.548 ±(99.9%) 0.006 ms/op
Iteration   1: 2.520 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.976 ms/op
                 createUser·p0.50:   2.576 ms/op
                 createUser·p0.90:   3.064 ms/op
                 createUser·p0.95:   3.178 ms/op
                 createUser·p0.99:   3.645 ms/op
                 createUser·p0.999:  11.667 ms/op
                 createUser·p0.9999: 22.282 ms/op
                 createUser·p1.00:   23.658 ms/op

Iteration   2: 2.529 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.015 ms/op
                 createUser·p0.50:   2.572 ms/op
                 createUser·p0.90:   3.076 ms/op
                 createUser·p0.95:   3.191 ms/op
                 createUser·p0.99:   3.650 ms/op
                 createUser·p0.999:  9.437 ms/op
                 createUser·p0.9999: 13.807 ms/op
                 createUser·p1.00:   14.795 ms/op

Iteration   3: 2.548 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.998 ms/op
                 createUser·p0.50:   2.621 ms/op
                 createUser·p0.90:   3.097 ms/op
                 createUser·p0.95:   3.211 ms/op
                 createUser·p0.99:   3.867 ms/op
                 createUser·p0.999:  8.438 ms/op
                 createUser·p0.9999: 10.879 ms/op
                 createUser·p1.00:   11.436 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 378707
  mean =      2.532 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 183225 
    [ 2.500,  5.000) = 194686 
    [ 5.000,  7.500) = 395 
    [ 7.500, 10.000) = 104 
    [10.000, 12.500) = 169 
    [12.500, 15.000) = 96 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.976 ms/op
     p(50.0000) =      2.585 ms/op
     p(90.0000) =      3.080 ms/op
     p(95.0000) =      3.195 ms/op
     p(99.0000) =      3.719 ms/op
     p(99.9000) =      8.494 ms/op
     p(99.9900) =     13.992 ms/op
     p(99.9990) =     22.872 ms/op
     p(99.9999) =     23.658 ms/op
    p(100.0000) =     23.658 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.792 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.482 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.470 ±(99.9%) 0.005 ms/op
Iteration   1: 2.456 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.911 ms/op
                 existUser·p0.50:   2.507 ms/op
                 existUser·p0.90:   2.986 ms/op
                 existUser·p0.95:   3.088 ms/op
                 existUser·p0.99:   3.527 ms/op
                 existUser·p0.999:  5.723 ms/op
                 existUser·p0.9999: 15.105 ms/op
                 existUser·p1.00:   15.466 ms/op

Iteration   2: 2.447 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.858 ms/op
                 existUser·p0.50:   2.535 ms/op
                 existUser·p0.90:   2.966 ms/op
                 existUser·p0.95:   3.076 ms/op
                 existUser·p0.99:   3.678 ms/op
                 existUser·p0.999:  7.383 ms/op
                 existUser·p0.9999: 13.128 ms/op
                 existUser·p1.00:   13.943 ms/op

Iteration   3: 2.454 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.915 ms/op
                 existUser·p0.50:   2.519 ms/op
                 existUser·p0.90:   2.986 ms/op
                 existUser·p0.95:   3.088 ms/op
                 existUser·p0.99:   3.617 ms/op
                 existUser·p0.999:  5.726 ms/op
                 existUser·p0.9999: 13.106 ms/op
                 existUser·p1.00:   13.550 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 391056
  mean =      2.453 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 40 
    [ 1.250,  2.500) = 193815 
    [ 2.500,  3.750) = 194094 
    [ 3.750,  5.000) = 2454 
    [ 5.000,  6.250) = 246 
    [ 6.250,  7.500) = 42 
    [ 7.500,  8.750) = 35 
    [ 8.750, 10.000) = 42 
    [10.000, 11.250) = 45 
    [11.250, 12.500) = 119 
    [12.500, 13.750) = 87 
    [13.750, 15.000) = 23 
    [15.000, 16.250) = 14 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.858 ms/op
     p(50.0000) =      2.519 ms/op
     p(90.0000) =      2.978 ms/op
     p(95.0000) =      3.084 ms/op
     p(99.0000) =      3.609 ms/op
     p(99.9000) =      6.642 ms/op
     p(99.9900) =     13.548 ms/op
     p(99.9990) =     15.271 ms/op
     p(99.9999) =     15.466 ms/op
    p(100.0000) =     15.466 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 4.083 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 2.598 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.499 ±(99.9%) 0.005 ms/op
Iteration   1: 2.522 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.891 ms/op
                 getUser·p0.50:   2.527 ms/op
                 getUser·p0.90:   3.088 ms/op
                 getUser·p0.95:   3.260 ms/op
                 getUser·p0.99:   4.014 ms/op
                 getUser·p0.999:  5.657 ms/op
                 getUser·p0.9999: 14.226 ms/op
                 getUser·p1.00:   15.434 ms/op

Iteration   2: 2.518 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.943 ms/op
                 getUser·p0.50:   2.580 ms/op
                 getUser·p0.90:   3.047 ms/op
                 getUser·p0.95:   3.174 ms/op
                 getUser·p0.99:   4.100 ms/op
                 getUser·p0.999:  9.634 ms/op
                 getUser·p0.9999: 14.952 ms/op
                 getUser·p1.00:   15.614 ms/op

Iteration   3: 2.474 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.032 ms/op
                 getUser·p0.50:   2.494 ms/op
                 getUser·p0.90:   3.011 ms/op
                 getUser·p0.95:   3.113 ms/op
                 getUser·p0.99:   3.580 ms/op
                 getUser·p0.999:  6.471 ms/op
                 getUser·p0.9999: 11.602 ms/op
                 getUser·p1.00:   13.025 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 382885
  mean =      2.505 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 61 
    [ 1.250,  2.500) = 189000 
    [ 2.500,  3.750) = 188915 
    [ 3.750,  5.000) = 3925 
    [ 5.000,  6.250) = 603 
    [ 6.250,  7.500) = 29 
    [ 7.500,  8.750) = 9 
    [ 8.750, 10.000) = 62 
    [10.000, 11.250) = 77 
    [11.250, 12.500) = 74 
    [12.500, 13.750) = 75 
    [13.750, 15.000) = 43 
    [15.000, 16.250) = 12 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.891 ms/op
     p(50.0000) =      2.531 ms/op
     p(90.0000) =      3.047 ms/op
     p(95.0000) =      3.178 ms/op
     p(99.0000) =      3.895 ms/op
     p(99.9000) =      6.235 ms/op
     p(99.9900) =     14.184 ms/op
     p(99.9990) =     15.311 ms/op
     p(99.9999) =     15.614 ms/op
    p(100.0000) =     15.614 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.592 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.084 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.016 ±(99.9%) 0.009 ms/op
Iteration   1: 2.999 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.922 ms/op
                 listUser·p0.50:   2.933 ms/op
                 listUser·p0.90:   3.867 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   5.554 ms/op
                 listUser·p0.999:  9.296 ms/op
                 listUser·p0.9999: 10.841 ms/op
                 listUser·p1.00:   11.649 ms/op

Iteration   2: 3.012 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.988 ms/op
                 listUser·p0.50:   2.949 ms/op
                 listUser·p0.90:   3.883 ms/op
                 listUser·p0.95:   4.415 ms/op
                 listUser·p0.99:   5.603 ms/op
                 listUser·p0.999:  9.568 ms/op
                 listUser·p0.9999: 11.967 ms/op
                 listUser·p1.00:   12.878 ms/op

Iteration   3: 2.991 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.945 ms/op
                 listUser·p0.50:   2.933 ms/op
                 listUser·p0.90:   3.871 ms/op
                 listUser·p0.95:   4.383 ms/op
                 listUser·p0.99:   5.513 ms/op
                 listUser·p0.999:  9.355 ms/op
                 listUser·p0.9999: 11.326 ms/op
                 listUser·p1.00:   12.501 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 319667
  mean =      3.000 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 125 
    [ 1.250,  2.500) = 94951 
    [ 2.500,  3.750) = 185966 
    [ 3.750,  5.000) = 31499 
    [ 5.000,  6.250) = 5734 
    [ 6.250,  7.500) = 676 
    [ 7.500,  8.750) = 225 
    [ 8.750, 10.000) = 308 
    [10.000, 11.250) = 144 
    [11.250, 12.500) = 33 
    [12.500, 13.750) = 6 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.922 ms/op
     p(50.0000) =      2.937 ms/op
     p(90.0000) =      3.875 ms/op
     p(95.0000) =      4.391 ms/op
     p(99.0000) =      5.554 ms/op
     p(99.9000) =      9.388 ms/op
     p(99.9900) =     11.305 ms/op
     p(99.9990) =     12.832 ms/op
     p(99.9999) =     12.878 ms/op
    p(100.0000) =     12.878 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.597 ± 1.491  ops/ms
ClientPb.existUser                       thrpt       3  13.000 ± 0.649  ops/ms
ClientPb.getUser                         thrpt       3  12.874 ± 0.789  ops/ms
ClientPb.listUser                        thrpt       3  10.660 ± 0.978  ops/ms
ClientPb.createUser                       avgt       3   2.553 ± 0.385   ms/op
ClientPb.existUser                        avgt       3   2.441 ± 0.281   ms/op
ClientPb.getUser                          avgt       3   2.484 ± 0.317   ms/op
ClientPb.listUser                         avgt       3   3.023 ± 0.308   ms/op
ClientPb.createUser                     sample  378707   2.532 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.976           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.585           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.080           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.195           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.719           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.494           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.992           ms/op
ClientPb.createUser:createUser·p1.00    sample          23.658           ms/op
ClientPb.existUser                      sample  391056   2.453 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.858           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.519           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.978           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.084           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.609           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.642           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.548           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.466           ms/op
ClientPb.getUser                        sample  382885   2.505 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.891           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.531           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.047           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.178           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.895           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.235           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.184           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.614           ms/op
ClientPb.listUser                       sample  319667   3.000 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.922           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.937           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.875           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.391           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.554           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.388           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.305           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.878           ms/op
