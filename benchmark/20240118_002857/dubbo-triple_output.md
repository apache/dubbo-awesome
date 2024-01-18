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
# Warmup Iteration   1: 4.873 ops/ms
# Warmup Iteration   2: 11.866 ops/ms
# Warmup Iteration   3: 12.312 ops/ms
Iteration   1: 12.419 ops/ms
Iteration   2: 12.668 ops/ms
Iteration   3: 12.680 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.589 ±(99.9%) 2.686 ops/ms [Average]
  (min, avg, max) = (12.419, 12.589, 12.680), stdev = 0.147
  CI (99.9%): [9.903, 15.275] (assumes normal distribution)


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
# Warmup Iteration   1: 7.771 ops/ms
# Warmup Iteration   2: 12.861 ops/ms
# Warmup Iteration   3: 12.635 ops/ms
Iteration   1: 12.965 ops/ms
Iteration   2: 13.009 ops/ms
Iteration   3: 12.957 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.977 ±(99.9%) 0.503 ops/ms [Average]
  (min, avg, max) = (12.957, 12.977, 13.009), stdev = 0.028
  CI (99.9%): [12.475, 13.480] (assumes normal distribution)


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
# Warmup Iteration   1: 7.751 ops/ms
# Warmup Iteration   2: 12.454 ops/ms
# Warmup Iteration   3: 12.869 ops/ms
Iteration   1: 13.050 ops/ms
Iteration   2: 13.008 ops/ms
Iteration   3: 12.982 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.013 ±(99.9%) 0.627 ops/ms [Average]
  (min, avg, max) = (12.982, 13.013, 13.050), stdev = 0.034
  CI (99.9%): [12.386, 13.640] (assumes normal distribution)


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
# Warmup Iteration   1: 6.713 ops/ms
# Warmup Iteration   2: 10.637 ops/ms
# Warmup Iteration   3: 10.680 ops/ms
Iteration   1: 10.695 ops/ms
Iteration   2: 10.671 ops/ms
Iteration   3: 10.718 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.695 ±(99.9%) 0.426 ops/ms [Average]
  (min, avg, max) = (10.671, 10.695, 10.718), stdev = 0.023
  CI (99.9%): [10.269, 11.121] (assumes normal distribution)


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
# Warmup Iteration   1: 3.924 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.563 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.517 ±(99.9%) 0.004 ms/op
Iteration   1: 2.577 ±(99.9%) 0.004 ms/op
Iteration   2: 2.545 ±(99.9%) 0.004 ms/op
Iteration   3: 2.552 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.558 ±(99.9%) 0.311 ms/op [Average]
  (min, avg, max) = (2.545, 2.558, 2.577), stdev = 0.017
  CI (99.9%): [2.247, 2.869] (assumes normal distribution)


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
# Warmup Iteration   1: 3.743 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.457 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.445 ±(99.9%) 0.005 ms/op
Iteration   1: 2.465 ±(99.9%) 0.004 ms/op
Iteration   2: 2.457 ±(99.9%) 0.004 ms/op
Iteration   3: 2.458 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.460 ±(99.9%) 0.087 ms/op [Average]
  (min, avg, max) = (2.457, 2.460, 2.465), stdev = 0.005
  CI (99.9%): [2.373, 2.547] (assumes normal distribution)


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
# Warmup Iteration   1: 3.937 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.513 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.521 ±(99.9%) 0.004 ms/op
Iteration   1: 2.475 ±(99.9%) 0.004 ms/op
Iteration   2: 2.537 ±(99.9%) 0.004 ms/op
Iteration   3: 2.482 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.498 ±(99.9%) 0.617 ms/op [Average]
  (min, avg, max) = (2.475, 2.498, 2.537), stdev = 0.034
  CI (99.9%): [1.881, 3.115] (assumes normal distribution)


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
# Warmup Iteration   1: 4.829 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.092 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.038 ±(99.9%) 0.007 ms/op
Iteration   1: 3.026 ±(99.9%) 0.004 ms/op
Iteration   2: 3.031 ±(99.9%) 0.004 ms/op
Iteration   3: 3.043 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.033 ±(99.9%) 0.157 ms/op [Average]
  (min, avg, max) = (3.026, 3.033, 3.043), stdev = 0.009
  CI (99.9%): [2.876, 3.191] (assumes normal distribution)


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
# Warmup Iteration   1: 4.273 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.703 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.555 ±(99.9%) 0.006 ms/op
Iteration   1: 2.566 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.696 ms/op
                 createUser·p0.50:   2.626 ms/op
                 createUser·p0.90:   3.125 ms/op
                 createUser·p0.95:   3.265 ms/op
                 createUser·p0.99:   3.863 ms/op
                 createUser·p0.999:  10.761 ms/op
                 createUser·p0.9999: 13.911 ms/op
                 createUser·p1.00:   14.139 ms/op

Iteration   2: 2.573 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.823 ms/op
                 createUser·p0.50:   2.630 ms/op
                 createUser·p0.90:   3.129 ms/op
                 createUser·p0.95:   3.260 ms/op
                 createUser·p0.99:   3.830 ms/op
                 createUser·p0.999:  9.491 ms/op
                 createUser·p0.9999: 11.724 ms/op
                 createUser·p1.00:   12.468 ms/op

Iteration   3: 2.602 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.426 ms/op
                 createUser·p0.50:   2.626 ms/op
                 createUser·p0.90:   3.187 ms/op
                 createUser·p0.95:   3.371 ms/op
                 createUser·p0.99:   4.325 ms/op
                 createUser·p0.999:  8.376 ms/op
                 createUser·p0.9999: 11.808 ms/op
                 createUser·p1.00:   12.321 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 371716
  mean =      2.580 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 87 
    [ 1.250,  2.500) = 173478 
    [ 2.500,  3.750) = 192312 
    [ 3.750,  5.000) = 4878 
    [ 5.000,  6.250) = 452 
    [ 6.250,  7.500) = 89 
    [ 7.500,  8.750) = 46 
    [ 8.750, 10.000) = 85 
    [10.000, 11.250) = 102 
    [11.250, 12.500) = 124 
    [12.500, 13.750) = 46 
    [13.750, 15.000) = 17 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.426 ms/op
     p(50.0000) =      2.626 ms/op
     p(90.0000) =      3.146 ms/op
     p(95.0000) =      3.293 ms/op
     p(99.0000) =      4.014 ms/op
     p(99.9000) =      8.812 ms/op
     p(99.9900) =     12.973 ms/op
     p(99.9990) =     14.034 ms/op
     p(99.9999) =     14.139 ms/op
    p(100.0000) =     14.139 ms/op


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
# Warmup Iteration   1: 3.820 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.417 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.428 ±(99.9%) 0.005 ms/op
Iteration   1: 2.409 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.878 ms/op
                 existUser·p0.50:   2.511 ms/op
                 existUser·p0.90:   2.916 ms/op
                 existUser·p0.95:   3.019 ms/op
                 existUser·p0.99:   3.490 ms/op
                 existUser·p0.999:  5.345 ms/op
                 existUser·p0.9999: 13.791 ms/op
                 existUser·p1.00:   14.582 ms/op

Iteration   2: 2.411 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.992 ms/op
                 existUser·p0.50:   2.535 ms/op
                 existUser·p0.90:   2.912 ms/op
                 existUser·p0.95:   3.006 ms/op
                 existUser·p0.99:   3.416 ms/op
                 existUser·p0.999:  7.008 ms/op
                 existUser·p0.9999: 12.673 ms/op
                 existUser·p1.00:   13.009 ms/op

Iteration   3: 2.445 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.694 ms/op
                 existUser·p0.50:   2.486 ms/op
                 existUser·p0.90:   2.978 ms/op
                 existUser·p0.95:   3.113 ms/op
                 existUser·p0.99:   3.875 ms/op
                 existUser·p0.999:  7.782 ms/op
                 existUser·p0.9999: 11.907 ms/op
                 existUser·p1.00:   12.501 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 396117
  mean =      2.421 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 51 
    [ 1.250,  2.500) = 196808 
    [ 2.500,  3.750) = 196111 
    [ 3.750,  5.000) = 2384 
    [ 5.000,  6.250) = 281 
    [ 6.250,  7.500) = 85 
    [ 7.500,  8.750) = 19 
    [ 8.750, 10.000) = 102 
    [10.000, 11.250) = 95 
    [11.250, 12.500) = 93 
    [12.500, 13.750) = 71 
    [13.750, 15.000) = 17 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.694 ms/op
     p(50.0000) =      2.511 ms/op
     p(90.0000) =      2.933 ms/op
     p(95.0000) =      3.043 ms/op
     p(99.0000) =      3.609 ms/op
     p(99.9000) =      7.527 ms/op
     p(99.9900) =     13.015 ms/op
     p(99.9990) =     14.308 ms/op
     p(99.9999) =     14.582 ms/op
    p(100.0000) =     14.582 ms/op


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
# Warmup Iteration   1: 3.933 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.593 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.558 ±(99.9%) 0.006 ms/op
Iteration   1: 2.517 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.942 ms/op
                 getUser·p0.50:   2.568 ms/op
                 getUser·p0.90:   3.056 ms/op
                 getUser·p0.95:   3.150 ms/op
                 getUser·p0.99:   3.559 ms/op
                 getUser·p0.999:  11.124 ms/op
                 getUser·p0.9999: 13.751 ms/op
                 getUser·p1.00:   14.320 ms/op

Iteration   2: 2.588 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.031 ms/op
                 getUser·p0.50:   2.626 ms/op
                 getUser·p0.90:   3.146 ms/op
                 getUser·p0.95:   3.326 ms/op
                 getUser·p0.99:   4.588 ms/op
                 getUser·p0.999:  9.084 ms/op
                 getUser·p0.9999: 13.183 ms/op
                 getUser·p1.00:   14.090 ms/op

Iteration   3: 2.547 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.017 ms/op
                 getUser·p0.50:   2.580 ms/op
                 getUser·p0.90:   3.105 ms/op
                 getUser·p0.95:   3.219 ms/op
                 getUser·p0.99:   3.813 ms/op
                 getUser·p0.999:  8.421 ms/op
                 getUser·p0.9999: 12.157 ms/op
                 getUser·p1.00:   12.485 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 376097
  mean =      2.550 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 34 
    [ 1.250,  2.500) = 182957 
    [ 2.500,  3.750) = 187432 
    [ 3.750,  5.000) = 4472 
    [ 5.000,  6.250) = 703 
    [ 6.250,  7.500) = 98 
    [ 7.500,  8.750) = 27 
    [ 8.750, 10.000) = 100 
    [10.000, 11.250) = 88 
    [11.250, 12.500) = 92 
    [12.500, 13.750) = 77 
    [13.750, 15.000) = 17 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.942 ms/op
     p(50.0000) =      2.597 ms/op
     p(90.0000) =      3.101 ms/op
     p(95.0000) =      3.224 ms/op
     p(99.0000) =      4.080 ms/op
     p(99.9000) =      8.616 ms/op
     p(99.9900) =     13.402 ms/op
     p(99.9990) =     14.138 ms/op
     p(99.9999) =     14.320 ms/op
    p(100.0000) =     14.320 ms/op


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
# Warmup Iteration   1: 4.755 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.063 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.053 ±(99.9%) 0.009 ms/op
Iteration   1: 3.058 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.910 ms/op
                 listUser·p0.50:   3.002 ms/op
                 listUser·p0.90:   3.949 ms/op
                 listUser·p0.95:   4.473 ms/op
                 listUser·p0.99:   5.718 ms/op
                 listUser·p0.999:  9.756 ms/op
                 listUser·p0.9999: 11.259 ms/op
                 listUser·p1.00:   12.960 ms/op

Iteration   2: 3.024 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.893 ms/op
                 listUser·p0.50:   2.974 ms/op
                 listUser·p0.90:   3.850 ms/op
                 listUser·p0.95:   4.293 ms/op
                 listUser·p0.99:   5.415 ms/op
                 listUser·p0.999:  10.621 ms/op
                 listUser·p0.9999: 13.573 ms/op
                 listUser·p1.00:   13.926 ms/op

Iteration   3: 3.019 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.990 ms/op
                 listUser·p0.50:   2.974 ms/op
                 listUser·p0.90:   3.850 ms/op
                 listUser·p0.95:   4.342 ms/op
                 listUser·p0.99:   5.538 ms/op
                 listUser·p0.999:  9.535 ms/op
                 listUser·p0.9999: 12.354 ms/op
                 listUser·p1.00:   12.812 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 316165
  mean =      3.034 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 109 
    [ 1.250,  2.500) = 86651 
    [ 2.500,  3.750) = 190798 
    [ 3.750,  5.000) = 31673 
    [ 5.000,  6.250) = 5618 
    [ 6.250,  7.500) = 657 
    [ 7.500,  8.750) = 176 
    [ 8.750, 10.000) = 225 
    [10.000, 11.250) = 134 
    [11.250, 12.500) = 83 
    [12.500, 13.750) = 36 
    [13.750, 15.000) = 5 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.893 ms/op
     p(50.0000) =      2.982 ms/op
     p(90.0000) =      3.879 ms/op
     p(95.0000) =      4.366 ms/op
     p(99.0000) =      5.546 ms/op
     p(99.9000) =      9.732 ms/op
     p(99.9900) =     13.156 ms/op
     p(99.9990) =     13.902 ms/op
     p(99.9999) =     13.926 ms/op
    p(100.0000) =     13.926 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.589 ± 2.686  ops/ms
ClientPb.existUser                       thrpt       3  12.977 ± 0.503  ops/ms
ClientPb.getUser                         thrpt       3  13.013 ± 0.627  ops/ms
ClientPb.listUser                        thrpt       3  10.695 ± 0.426  ops/ms
ClientPb.createUser                       avgt       3   2.558 ± 0.311   ms/op
ClientPb.existUser                        avgt       3   2.460 ± 0.087   ms/op
ClientPb.getUser                          avgt       3   2.498 ± 0.617   ms/op
ClientPb.listUser                         avgt       3   3.033 ± 0.157   ms/op
ClientPb.createUser                     sample  371716   2.580 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.426           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.626           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.146           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.293           ms/op
ClientPb.createUser:createUser·p0.99    sample           4.014           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.812           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.973           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.139           ms/op
ClientPb.existUser                      sample  396117   2.421 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.694           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.511           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.933           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.043           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.609           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.527           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.015           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.582           ms/op
ClientPb.getUser                        sample  376097   2.550 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.942           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.597           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.101           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.224           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.080           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.616           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.402           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.320           ms/op
ClientPb.listUser                       sample  316165   3.034 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.893           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.982           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.879           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.366           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.546           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.732           ms/op
ClientPb.listUser:listUser·p0.9999      sample          13.156           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.926           ms/op
