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
# Warmup Iteration   1: 4.706 ops/ms
# Warmup Iteration   2: 11.741 ops/ms
# Warmup Iteration   3: 12.122 ops/ms
Iteration   1: 12.419 ops/ms
Iteration   2: 12.373 ops/ms
Iteration   3: 12.479 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.424 ±(99.9%) 0.973 ops/ms [Average]
  (min, avg, max) = (12.373, 12.424, 12.479), stdev = 0.053
  CI (99.9%): [11.451, 13.396] (assumes normal distribution)


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
# Warmup Iteration   1: 7.512 ops/ms
# Warmup Iteration   2: 13.030 ops/ms
# Warmup Iteration   3: 12.979 ops/ms
Iteration   1: 13.028 ops/ms
Iteration   2: 12.879 ops/ms
Iteration   3: 12.850 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.919 ±(99.9%) 1.741 ops/ms [Average]
  (min, avg, max) = (12.850, 12.919, 13.028), stdev = 0.095
  CI (99.9%): [11.177, 14.660] (assumes normal distribution)


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
# Warmup Iteration   1: 7.030 ops/ms
# Warmup Iteration   2: 12.253 ops/ms
# Warmup Iteration   3: 12.384 ops/ms
Iteration   1: 12.429 ops/ms
Iteration   2: 12.455 ops/ms
Iteration   3: 12.466 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.450 ±(99.9%) 0.352 ops/ms [Average]
  (min, avg, max) = (12.429, 12.450, 12.466), stdev = 0.019
  CI (99.9%): [12.098, 12.802] (assumes normal distribution)


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
# Warmup Iteration   1: 6.404 ops/ms
# Warmup Iteration   2: 10.393 ops/ms
# Warmup Iteration   3: 10.422 ops/ms
Iteration   1: 10.356 ops/ms
Iteration   2: 10.741 ops/ms
Iteration   3: 10.493 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.530 ±(99.9%) 3.563 ops/ms [Average]
  (min, avg, max) = (10.356, 10.530, 10.741), stdev = 0.195
  CI (99.9%): [6.967, 14.093] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 4.080 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.553 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.537 ±(99.9%) 0.004 ms/op
Iteration   1: 2.509 ±(99.9%) 0.004 ms/op
Iteration   2: 2.579 ±(99.9%) 0.004 ms/op
Iteration   3: 2.534 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.541 ±(99.9%) 0.648 ms/op [Average]
  (min, avg, max) = (2.509, 2.541, 2.579), stdev = 0.035
  CI (99.9%): [1.893, 3.188] (assumes normal distribution)


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
# Warmup Iteration   1: 3.609 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.512 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.461 ±(99.9%) 0.004 ms/op
Iteration   1: 2.468 ±(99.9%) 0.004 ms/op
Iteration   2: 2.466 ±(99.9%) 0.004 ms/op
Iteration   3: 2.490 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.475 ±(99.9%) 0.242 ms/op [Average]
  (min, avg, max) = (2.466, 2.475, 2.490), stdev = 0.013
  CI (99.9%): [2.232, 2.717] (assumes normal distribution)


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
# Warmup Iteration   1: 4.075 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.554 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.509 ±(99.9%) 0.003 ms/op
Iteration   1: 2.484 ±(99.9%) 0.004 ms/op
Iteration   2: 2.466 ±(99.9%) 0.005 ms/op
Iteration   3: 2.482 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.478 ±(99.9%) 0.177 ms/op [Average]
  (min, avg, max) = (2.466, 2.478, 2.484), stdev = 0.010
  CI (99.9%): [2.300, 2.655] (assumes normal distribution)


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
# Warmup Iteration   1: 4.635 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.123 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.060 ±(99.9%) 0.005 ms/op
Iteration   1: 3.060 ±(99.9%) 0.005 ms/op
Iteration   2: 3.086 ±(99.9%) 0.005 ms/op
Iteration   3: 3.076 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.074 ±(99.9%) 0.233 ms/op [Average]
  (min, avg, max) = (3.060, 3.074, 3.086), stdev = 0.013
  CI (99.9%): [2.841, 3.307] (assumes normal distribution)


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
# Warmup Iteration   1: 4.346 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 2.703 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.552 ±(99.9%) 0.005 ms/op
Iteration   1: 2.532 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.196 ms/op
                 createUser·p0.50:   2.597 ms/op
                 createUser·p0.90:   3.072 ms/op
                 createUser·p0.95:   3.187 ms/op
                 createUser·p0.99:   3.727 ms/op
                 createUser·p0.999:  11.649 ms/op
                 createUser·p0.9999: 14.840 ms/op
                 createUser·p1.00:   15.073 ms/op

Iteration   2: 2.557 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.053 ms/op
                 createUser·p0.50:   2.593 ms/op
                 createUser·p0.90:   3.121 ms/op
                 createUser·p0.95:   3.219 ms/op
                 createUser·p0.99:   3.600 ms/op
                 createUser·p0.999:  9.732 ms/op
                 createUser·p0.9999: 12.993 ms/op
                 createUser·p1.00:   14.287 ms/op

Iteration   3: 2.551 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.961 ms/op
                 createUser·p0.50:   2.630 ms/op
                 createUser·p0.90:   3.101 ms/op
                 createUser·p0.95:   3.211 ms/op
                 createUser·p0.99:   3.883 ms/op
                 createUser·p0.999:  9.006 ms/op
                 createUser·p0.9999: 11.387 ms/op
                 createUser·p1.00:   11.846 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 376661
  mean =      2.547 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 30 
    [ 1.250,  2.500) = 182037 
    [ 2.500,  3.750) = 190837 
    [ 3.750,  5.000) = 3002 
    [ 5.000,  6.250) = 337 
    [ 6.250,  7.500) = 25 
    [ 7.500,  8.750) = 6 
    [ 8.750, 10.000) = 63 
    [10.000, 11.250) = 113 
    [11.250, 12.500) = 105 
    [12.500, 13.750) = 62 
    [13.750, 15.000) = 41 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.961 ms/op
     p(50.0000) =      2.605 ms/op
     p(90.0000) =      3.101 ms/op
     p(95.0000) =      3.207 ms/op
     p(99.0000) =      3.748 ms/op
     p(99.9000) =      9.033 ms/op
     p(99.9900) =     13.997 ms/op
     p(99.9990) =     14.970 ms/op
     p(99.9999) =     15.073 ms/op
    p(100.0000) =     15.073 ms/op


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
# Warmup Iteration   1: 3.884 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.535 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.532 ±(99.9%) 0.005 ms/op
Iteration   1: 2.500 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.955 ms/op
                 existUser·p0.50:   2.580 ms/op
                 existUser·p0.90:   3.043 ms/op
                 existUser·p0.95:   3.142 ms/op
                 existUser·p0.99:   3.588 ms/op
                 existUser·p0.999:  11.013 ms/op
                 existUser·p0.9999: 13.586 ms/op
                 existUser·p1.00:   15.450 ms/op

Iteration   2: 2.513 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.915 ms/op
                 existUser·p0.50:   2.585 ms/op
                 existUser·p0.90:   3.052 ms/op
                 existUser·p0.95:   3.158 ms/op
                 existUser·p0.99:   3.641 ms/op
                 existUser·p0.999:  6.118 ms/op
                 existUser·p0.9999: 13.526 ms/op
                 existUser·p1.00:   14.107 ms/op

Iteration   3: 2.501 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.025 ms/op
                 existUser·p0.50:   2.544 ms/op
                 existUser·p0.90:   3.052 ms/op
                 existUser·p0.95:   3.170 ms/op
                 existUser·p0.99:   3.727 ms/op
                 existUser·p0.999:  8.641 ms/op
                 existUser·p0.9999: 12.537 ms/op
                 existUser·p1.00:   13.664 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 382818
  mean =      2.505 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 54 
    [ 1.250,  2.500) = 186400 
    [ 2.500,  3.750) = 193143 
    [ 3.750,  5.000) = 2359 
    [ 5.000,  6.250) = 437 
    [ 6.250,  7.500) = 35 
    [ 7.500,  8.750) = 40 
    [ 8.750, 10.000) = 63 
    [10.000, 11.250) = 88 
    [11.250, 12.500) = 80 
    [12.500, 13.750) = 106 
    [13.750, 15.000) = 7 
    [15.000, 16.250) = 6 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.915 ms/op
     p(50.0000) =      2.568 ms/op
     p(90.0000) =      3.047 ms/op
     p(95.0000) =      3.154 ms/op
     p(99.0000) =      3.658 ms/op
     p(99.9000) =      7.918 ms/op
     p(99.9900) =     13.353 ms/op
     p(99.9990) =     15.156 ms/op
     p(99.9999) =     15.450 ms/op
    p(100.0000) =     15.450 ms/op


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
# Warmup Iteration   1: 4.091 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.590 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.504 ±(99.9%) 0.006 ms/op
Iteration   1: 2.487 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.963 ms/op
                 getUser·p0.50:   2.515 ms/op
                 getUser·p0.90:   3.015 ms/op
                 getUser·p0.95:   3.117 ms/op
                 getUser·p0.99:   3.637 ms/op
                 getUser·p0.999:  8.982 ms/op
                 getUser·p0.9999: 18.617 ms/op
                 getUser·p1.00:   19.497 ms/op

Iteration   2: 2.498 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.980 ms/op
                 getUser·p0.50:   2.503 ms/op
                 getUser·p0.90:   3.056 ms/op
                 getUser·p0.95:   3.158 ms/op
                 getUser·p0.99:   3.650 ms/op
                 getUser·p0.999:  5.399 ms/op
                 getUser·p0.9999: 10.152 ms/op
                 getUser·p1.00:   11.108 ms/op

Iteration   3: 2.554 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.943 ms/op
                 getUser·p0.50:   2.589 ms/op
                 getUser·p0.90:   3.105 ms/op
                 getUser·p0.95:   3.301 ms/op
                 getUser·p0.99:   4.579 ms/op
                 getUser·p0.999:  9.431 ms/op
                 getUser·p0.9999: 11.667 ms/op
                 getUser·p1.00:   12.812 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 381808
  mean =      2.513 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 53 
    [ 1.250,  2.500) = 188299 
    [ 2.500,  3.750) = 188149 
    [ 3.750,  5.000) = 4124 
    [ 5.000,  6.250) = 786 
    [ 6.250,  7.500) = 45 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 111 
    [10.000, 11.250) = 96 
    [11.250, 12.500) = 23 
    [12.500, 13.750) = 69 
    [13.750, 15.000) = 18 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 7 
    [17.500, 18.750) = 19 

  Percentiles, ms/op:
      p(0.0000) =      0.943 ms/op
     p(50.0000) =      2.540 ms/op
     p(90.0000) =      3.056 ms/op
     p(95.0000) =      3.183 ms/op
     p(99.0000) =      4.002 ms/op
     p(99.9000) =      6.473 ms/op
     p(99.9900) =     14.245 ms/op
     p(99.9990) =     19.253 ms/op
     p(99.9999) =     19.497 ms/op
    p(100.0000) =     19.497 ms/op


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
# Warmup Iteration   1: 4.767 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.066 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.013 ±(99.9%) 0.009 ms/op
Iteration   1: 2.991 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.860 ms/op
                 listUser·p0.50:   2.937 ms/op
                 listUser·p0.90:   3.854 ms/op
                 listUser·p0.95:   4.325 ms/op
                 listUser·p0.99:   5.562 ms/op
                 listUser·p0.999:  8.915 ms/op
                 listUser·p0.9999: 11.043 ms/op
                 listUser·p1.00:   11.911 ms/op

Iteration   2: 3.000 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.844 ms/op
                 listUser·p0.50:   2.945 ms/op
                 listUser·p0.90:   3.850 ms/op
                 listUser·p0.95:   4.309 ms/op
                 listUser·p0.99:   5.423 ms/op
                 listUser·p0.999:  9.386 ms/op
                 listUser·p0.9999: 11.081 ms/op
                 listUser·p1.00:   11.944 ms/op

Iteration   3: 3.024 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.768 ms/op
                 listUser·p0.50:   2.966 ms/op
                 listUser·p0.90:   3.912 ms/op
                 listUser·p0.95:   4.432 ms/op
                 listUser·p0.99:   5.726 ms/op
                 listUser·p0.999:  8.798 ms/op
                 listUser·p0.9999: 10.174 ms/op
                 listUser·p1.00:   10.502 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 319174
  mean =      3.005 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 139 
    [ 1.250,  2.500) = 92223 
    [ 2.500,  3.750) = 188324 
    [ 3.750,  5.000) = 31578 
    [ 5.000,  6.250) = 5498 
    [ 6.250,  7.500) = 657 
    [ 7.500,  8.750) = 372 
    [ 8.750, 10.000) = 284 
    [10.000, 11.250) = 84 
    [11.250, 12.500) = 15 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.768 ms/op
     p(50.0000) =      2.949 ms/op
     p(90.0000) =      3.871 ms/op
     p(95.0000) =      4.350 ms/op
     p(99.0000) =      5.562 ms/op
     p(99.9000) =      9.044 ms/op
     p(99.9900) =     10.595 ms/op
     p(99.9990) =     11.902 ms/op
     p(99.9999) =     11.944 ms/op
    p(100.0000) =     11.944 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.424 ± 0.973  ops/ms
ClientPb.existUser                       thrpt       3  12.919 ± 1.741  ops/ms
ClientPb.getUser                         thrpt       3  12.450 ± 0.352  ops/ms
ClientPb.listUser                        thrpt       3  10.530 ± 3.563  ops/ms
ClientPb.createUser                       avgt       3   2.541 ± 0.648   ms/op
ClientPb.existUser                        avgt       3   2.475 ± 0.242   ms/op
ClientPb.getUser                          avgt       3   2.478 ± 0.177   ms/op
ClientPb.listUser                         avgt       3   3.074 ± 0.233   ms/op
ClientPb.createUser                     sample  376661   2.547 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.961           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.605           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.101           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.207           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.748           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.033           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.997           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.073           ms/op
ClientPb.existUser                      sample  382818   2.505 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.915           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.568           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.047           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.154           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.658           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.918           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.353           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.450           ms/op
ClientPb.getUser                        sample  381808   2.513 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.943           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.540           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.056           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.183           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.002           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.473           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.245           ms/op
ClientPb.getUser:getUser·p1.00          sample          19.497           ms/op
ClientPb.listUser                       sample  319174   3.005 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.768           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.949           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.871           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.350           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.562           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.044           ms/op
ClientPb.listUser:listUser·p0.9999      sample          10.595           ms/op
ClientPb.listUser:listUser·p1.00        sample          11.944           ms/op
