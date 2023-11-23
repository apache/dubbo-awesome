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
# Warmup Iteration   1: 4.337 ops/ms
# Warmup Iteration   2: 11.998 ops/ms
# Warmup Iteration   3: 12.229 ops/ms
Iteration   1: 12.425 ops/ms
Iteration   2: 12.488 ops/ms
Iteration   3: 12.511 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.475 ±(99.9%) 0.805 ops/ms [Average]
  (min, avg, max) = (12.425, 12.475, 12.511), stdev = 0.044
  CI (99.9%): [11.669, 13.280] (assumes normal distribution)


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
# Warmup Iteration   1: 7.668 ops/ms
# Warmup Iteration   2: 12.603 ops/ms
# Warmup Iteration   3: 12.788 ops/ms
Iteration   1: 12.639 ops/ms
Iteration   2: 12.639 ops/ms
Iteration   3: 12.712 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.663 ±(99.9%) 0.772 ops/ms [Average]
  (min, avg, max) = (12.639, 12.663, 12.712), stdev = 0.042
  CI (99.9%): [11.891, 13.435] (assumes normal distribution)


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
# Warmup Iteration   1: 7.340 ops/ms
# Warmup Iteration   2: 12.378 ops/ms
# Warmup Iteration   3: 12.346 ops/ms
Iteration   1: 12.604 ops/ms
Iteration   2: 12.605 ops/ms
Iteration   3: 12.752 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.654 ±(99.9%) 1.550 ops/ms [Average]
  (min, avg, max) = (12.604, 12.654, 12.752), stdev = 0.085
  CI (99.9%): [11.104, 14.203] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:44
# Fork: 1 of 1
# Warmup Iteration   1: 6.312 ops/ms
# Warmup Iteration   2: 10.355 ops/ms
# Warmup Iteration   3: 10.534 ops/ms
Iteration   1: 10.430 ops/ms
Iteration   2: 10.542 ops/ms
Iteration   3: 10.279 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.417 ±(99.9%) 2.408 ops/ms [Average]
  (min, avg, max) = (10.279, 10.417, 10.542), stdev = 0.132
  CI (99.9%): [8.009, 12.825] (assumes normal distribution)


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
# Warmup Iteration   1: 3.904 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.580 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.541 ±(99.9%) 0.004 ms/op
Iteration   1: 2.504 ±(99.9%) 0.004 ms/op
Iteration   2: 2.565 ±(99.9%) 0.004 ms/op
Iteration   3: 2.490 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.520 ±(99.9%) 0.729 ms/op [Average]
  (min, avg, max) = (2.490, 2.520, 2.565), stdev = 0.040
  CI (99.9%): [1.791, 3.249] (assumes normal distribution)


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
# Warmup Iteration   1: 3.842 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.511 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.501 ±(99.9%) 0.003 ms/op
Iteration   1: 2.475 ±(99.9%) 0.004 ms/op
Iteration   2: 2.493 ±(99.9%) 0.003 ms/op
Iteration   3: 2.520 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.496 ±(99.9%) 0.414 ms/op [Average]
  (min, avg, max) = (2.475, 2.496, 2.520), stdev = 0.023
  CI (99.9%): [2.082, 2.909] (assumes normal distribution)


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
# Warmup Iteration   1: 4.189 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.583 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.572 ±(99.9%) 0.004 ms/op
Iteration   1: 2.603 ±(99.9%) 0.004 ms/op
Iteration   2: 2.540 ±(99.9%) 0.004 ms/op
Iteration   3: 2.532 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.559 ±(99.9%) 0.703 ms/op [Average]
  (min, avg, max) = (2.532, 2.559, 2.603), stdev = 0.039
  CI (99.9%): [1.855, 3.262] (assumes normal distribution)


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
# Warmup Iteration   1: 4.846 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.094 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.004 ±(99.9%) 0.005 ms/op
Iteration   1: 3.014 ±(99.9%) 0.005 ms/op
Iteration   2: 3.007 ±(99.9%) 0.006 ms/op
Iteration   3: 2.997 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.006 ±(99.9%) 0.160 ms/op [Average]
  (min, avg, max) = (2.997, 3.006, 3.014), stdev = 0.009
  CI (99.9%): [2.846, 3.166] (assumes normal distribution)


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
# Warmup Iteration   1: 4.205 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.671 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.632 ±(99.9%) 0.006 ms/op
Iteration   1: 2.579 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.022 ms/op
                 createUser·p0.50:   2.617 ms/op
                 createUser·p0.90:   3.129 ms/op
                 createUser·p0.95:   3.248 ms/op
                 createUser·p0.99:   3.928 ms/op
                 createUser·p0.999:  12.814 ms/op
                 createUser·p0.9999: 14.880 ms/op
                 createUser·p1.00:   15.860 ms/op

Iteration   2: 2.563 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.950 ms/op
                 createUser·p0.50:   2.646 ms/op
                 createUser·p0.90:   3.105 ms/op
                 createUser·p0.95:   3.236 ms/op
                 createUser·p0.99:   3.910 ms/op
                 createUser·p0.999:  10.130 ms/op
                 createUser·p0.9999: 12.797 ms/op
                 createUser·p1.00:   13.730 ms/op

Iteration   3: 2.562 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.911 ms/op
                 createUser·p0.50:   2.601 ms/op
                 createUser·p0.90:   3.121 ms/op
                 createUser·p0.95:   3.252 ms/op
                 createUser·p0.99:   3.985 ms/op
                 createUser·p0.999:  8.508 ms/op
                 createUser·p0.9999: 12.592 ms/op
                 createUser·p1.00:   13.746 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 373443
  mean =      2.568 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 52 
    [ 1.250,  2.500) = 178194 
    [ 2.500,  3.750) = 190145 
    [ 3.750,  5.000) = 3938 
    [ 5.000,  6.250) = 609 
    [ 6.250,  7.500) = 107 
    [ 7.500,  8.750) = 31 
    [ 8.750, 10.000) = 70 
    [10.000, 11.250) = 58 
    [11.250, 12.500) = 72 
    [12.500, 13.750) = 88 
    [13.750, 15.000) = 71 
    [15.000, 16.250) = 8 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.911 ms/op
     p(50.0000) =      2.621 ms/op
     p(90.0000) =      3.117 ms/op
     p(95.0000) =      3.248 ms/op
     p(99.0000) =      3.944 ms/op
     p(99.9000) =      8.585 ms/op
     p(99.9900) =     14.609 ms/op
     p(99.9990) =     15.676 ms/op
     p(99.9999) =     15.860 ms/op
    p(100.0000) =     15.860 ms/op


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
# Warmup Iteration   1: 4.305 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 2.601 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.480 ±(99.9%) 0.005 ms/op
Iteration   1: 2.495 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.862 ms/op
                 existUser·p0.50:   2.552 ms/op
                 existUser·p0.90:   3.039 ms/op
                 existUser·p0.95:   3.174 ms/op
                 existUser·p0.99:   3.924 ms/op
                 existUser·p0.999:  7.214 ms/op
                 existUser·p0.9999: 14.025 ms/op
                 existUser·p1.00:   14.533 ms/op

Iteration   2: 2.455 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.980 ms/op
                 existUser·p0.50:   2.519 ms/op
                 existUser·p0.90:   2.978 ms/op
                 existUser·p0.95:   3.084 ms/op
                 existUser·p0.99:   3.568 ms/op
                 existUser·p0.999:  8.427 ms/op
                 existUser·p0.9999: 13.746 ms/op
                 existUser·p1.00:   14.385 ms/op

Iteration   3: 2.491 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.004 ms/op
                 existUser·p0.50:   2.499 ms/op
                 existUser·p0.90:   3.047 ms/op
                 existUser·p0.95:   3.195 ms/op
                 existUser·p0.99:   4.133 ms/op
                 existUser·p0.999:  8.559 ms/op
                 existUser·p0.9999: 11.452 ms/op
                 existUser·p1.00:   11.960 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 386626
  mean =      2.480 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 59 
    [ 1.250,  2.500) = 191357 
    [ 2.500,  3.750) = 190751 
    [ 3.750,  5.000) = 3324 
    [ 5.000,  6.250) = 619 
    [ 6.250,  7.500) = 84 
    [ 7.500,  8.750) = 83 
    [ 8.750, 10.000) = 68 
    [10.000, 11.250) = 103 
    [11.250, 12.500) = 43 
    [12.500, 13.750) = 90 
    [13.750, 15.000) = 45 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.862 ms/op
     p(50.0000) =      2.519 ms/op
     p(90.0000) =      3.019 ms/op
     p(95.0000) =      3.150 ms/op
     p(99.0000) =      3.863 ms/op
     p(99.9000) =      8.165 ms/op
     p(99.9900) =     13.817 ms/op
     p(99.9990) =     14.385 ms/op
     p(99.9999) =     14.533 ms/op
    p(100.0000) =     14.533 ms/op


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
# Warmup Iteration   1: 3.880 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.562 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.525 ±(99.9%) 0.006 ms/op
Iteration   1: 2.482 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.038 ms/op
                 getUser·p0.50:   2.486 ms/op
                 getUser·p0.90:   3.023 ms/op
                 getUser·p0.95:   3.150 ms/op
                 getUser·p0.99:   3.841 ms/op
                 getUser·p0.999:  9.640 ms/op
                 getUser·p0.9999: 13.865 ms/op
                 getUser·p1.00:   14.778 ms/op

Iteration   2: 2.505 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.844 ms/op
                 getUser·p0.50:   2.548 ms/op
                 getUser·p0.90:   3.039 ms/op
                 getUser·p0.95:   3.162 ms/op
                 getUser·p0.99:   4.006 ms/op
                 getUser·p0.999:  10.273 ms/op
                 getUser·p0.9999: 14.839 ms/op
                 getUser·p1.00:   15.630 ms/op

Iteration   3: 2.481 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.940 ms/op
                 getUser·p0.50:   2.523 ms/op
                 getUser·p0.90:   3.019 ms/op
                 getUser·p0.95:   3.133 ms/op
                 getUser·p0.99:   3.715 ms/op
                 getUser·p0.999:  6.799 ms/op
                 getUser·p0.9999: 12.406 ms/op
                 getUser·p1.00:   13.107 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 385288
  mean =      2.489 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 64 
    [ 1.250,  2.500) = 191622 
    [ 2.500,  3.750) = 189158 
    [ 3.750,  5.000) = 3413 
    [ 5.000,  6.250) = 581 
    [ 6.250,  7.500) = 52 
    [ 7.500,  8.750) = 6 
    [ 8.750, 10.000) = 42 
    [10.000, 11.250) = 61 
    [11.250, 12.500) = 118 
    [12.500, 13.750) = 122 
    [13.750, 15.000) = 39 
    [15.000, 16.250) = 10 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.844 ms/op
     p(50.0000) =      2.513 ms/op
     p(90.0000) =      3.027 ms/op
     p(95.0000) =      3.146 ms/op
     p(99.0000) =      3.846 ms/op
     p(99.9000) =      9.165 ms/op
     p(99.9900) =     13.852 ms/op
     p(99.9990) =     15.331 ms/op
     p(99.9999) =     15.630 ms/op
    p(100.0000) =     15.630 ms/op


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
# Warmup Iteration   1: 4.748 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.061 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.038 ±(99.9%) 0.009 ms/op
Iteration   1: 3.023 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.808 ms/op
                 listUser·p0.50:   2.966 ms/op
                 listUser·p0.90:   3.895 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   5.685 ms/op
                 listUser·p0.999:  8.966 ms/op
                 listUser·p0.9999: 11.195 ms/op
                 listUser·p1.00:   12.370 ms/op

Iteration   2: 3.035 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.915 ms/op
                 listUser·p0.50:   2.970 ms/op
                 listUser·p0.90:   3.944 ms/op
                 listUser·p0.95:   4.465 ms/op
                 listUser·p0.99:   5.661 ms/op
                 listUser·p0.999:  9.826 ms/op
                 listUser·p0.9999: 11.181 ms/op
                 listUser·p1.00:   11.780 ms/op

Iteration   3: 3.040 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.945 ms/op
                 listUser·p0.50:   2.982 ms/op
                 listUser·p0.90:   3.924 ms/op
                 listUser·p0.95:   4.456 ms/op
                 listUser·p0.99:   5.718 ms/op
                 listUser·p0.999:  9.598 ms/op
                 listUser·p0.9999: 11.108 ms/op
                 listUser·p1.00:   11.469 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 316254
  mean =      3.033 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 115 
    [ 1.250,  2.500) = 89769 
    [ 2.500,  3.750) = 185705 
    [ 3.750,  5.000) = 32492 
    [ 5.000,  6.250) = 6643 
    [ 6.250,  7.500) = 868 
    [ 7.500,  8.750) = 222 
    [ 8.750, 10.000) = 230 
    [10.000, 11.250) = 187 
    [11.250, 12.500) = 23 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.808 ms/op
     p(50.0000) =      2.970 ms/op
     p(90.0000) =      3.920 ms/op
     p(95.0000) =      4.440 ms/op
     p(99.0000) =      5.685 ms/op
     p(99.9000) =      9.388 ms/op
     p(99.9900) =     11.158 ms/op
     p(99.9990) =     12.266 ms/op
     p(99.9999) =     12.370 ms/op
    p(100.0000) =     12.370 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.475 ± 0.805  ops/ms
ClientPb.existUser                       thrpt       3  12.663 ± 0.772  ops/ms
ClientPb.getUser                         thrpt       3  12.654 ± 1.550  ops/ms
ClientPb.listUser                        thrpt       3  10.417 ± 2.408  ops/ms
ClientPb.createUser                       avgt       3   2.520 ± 0.729   ms/op
ClientPb.existUser                        avgt       3   2.496 ± 0.414   ms/op
ClientPb.getUser                          avgt       3   2.559 ± 0.703   ms/op
ClientPb.listUser                         avgt       3   3.006 ± 0.160   ms/op
ClientPb.createUser                     sample  373443   2.568 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.911           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.621           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.117           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.248           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.944           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.585           ms/op
ClientPb.createUser:createUser·p0.9999  sample          14.609           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.860           ms/op
ClientPb.existUser                      sample  386626   2.480 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.862           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.519           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.019           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.150           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.863           ms/op
ClientPb.existUser:existUser·p0.999     sample           8.165           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.817           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.533           ms/op
ClientPb.getUser                        sample  385288   2.489 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.844           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.513           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.027           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.146           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.846           ms/op
ClientPb.getUser:getUser·p0.999         sample           9.165           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.852           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.630           ms/op
ClientPb.listUser                       sample  316254   3.033 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.808           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.970           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.920           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.440           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.685           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.388           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.158           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.370           ms/op
