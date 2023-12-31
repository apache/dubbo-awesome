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
# Warmup Iteration   1: 4.862 ops/ms
# Warmup Iteration   2: 11.963 ops/ms
# Warmup Iteration   3: 12.335 ops/ms
Iteration   1: 12.536 ops/ms
Iteration   2: 12.679 ops/ms
Iteration   3: 12.725 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.647 ±(99.9%) 1.799 ops/ms [Average]
  (min, avg, max) = (12.536, 12.647, 12.725), stdev = 0.099
  CI (99.9%): [10.848, 14.445] (assumes normal distribution)


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
# Warmup Iteration   1: 8.309 ops/ms
# Warmup Iteration   2: 13.010 ops/ms
# Warmup Iteration   3: 13.042 ops/ms
Iteration   1: 13.152 ops/ms
Iteration   2: 13.131 ops/ms
Iteration   3: 13.061 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.115 ±(99.9%) 0.866 ops/ms [Average]
  (min, avg, max) = (13.061, 13.115, 13.152), stdev = 0.047
  CI (99.9%): [12.249, 13.980] (assumes normal distribution)


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
# Warmup Iteration   1: 7.839 ops/ms
# Warmup Iteration   2: 12.293 ops/ms
# Warmup Iteration   3: 12.429 ops/ms
Iteration   1: 12.654 ops/ms
Iteration   2: 12.605 ops/ms
Iteration   3: 12.630 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.630 ±(99.9%) 0.453 ops/ms [Average]
  (min, avg, max) = (12.605, 12.630, 12.654), stdev = 0.025
  CI (99.9%): [12.176, 13.083] (assumes normal distribution)


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
# Warmup Iteration   1: 6.523 ops/ms
# Warmup Iteration   2: 10.326 ops/ms
# Warmup Iteration   3: 10.432 ops/ms
Iteration   1: 10.499 ops/ms
Iteration   2: 10.475 ops/ms
Iteration   3: 10.470 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.481 ±(99.9%) 0.286 ops/ms [Average]
  (min, avg, max) = (10.470, 10.481, 10.499), stdev = 0.016
  CI (99.9%): [10.196, 10.767] (assumes normal distribution)


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
# Warmup Iteration   1: 3.996 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 2.550 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.579 ±(99.9%) 0.004 ms/op
Iteration   1: 2.514 ±(99.9%) 0.003 ms/op
Iteration   2: 2.507 ±(99.9%) 0.004 ms/op
Iteration   3: 2.519 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.514 ±(99.9%) 0.112 ms/op [Average]
  (min, avg, max) = (2.507, 2.514, 2.519), stdev = 0.006
  CI (99.9%): [2.402, 2.625] (assumes normal distribution)


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
# Warmup Iteration   1: 3.732 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.563 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.483 ±(99.9%) 0.004 ms/op
Iteration   1: 2.518 ±(99.9%) 0.004 ms/op
Iteration   2: 2.497 ±(99.9%) 0.004 ms/op
Iteration   3: 2.528 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.514 ±(99.9%) 0.283 ms/op [Average]
  (min, avg, max) = (2.497, 2.514, 2.528), stdev = 0.016
  CI (99.9%): [2.231, 2.797] (assumes normal distribution)


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
# Warmup Iteration   1: 3.868 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.546 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.530 ±(99.9%) 0.004 ms/op
Iteration   1: 2.451 ±(99.9%) 0.003 ms/op
Iteration   2: 2.522 ±(99.9%) 0.004 ms/op
Iteration   3: 2.528 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.500 ±(99.9%) 0.782 ms/op [Average]
  (min, avg, max) = (2.451, 2.500, 2.528), stdev = 0.043
  CI (99.9%): [1.719, 3.282] (assumes normal distribution)


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
# Warmup Iteration   1: 4.614 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.082 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.045 ±(99.9%) 0.005 ms/op
Iteration   1: 3.017 ±(99.9%) 0.005 ms/op
Iteration   2: 3.047 ±(99.9%) 0.005 ms/op
Iteration   3: 3.021 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.028 ±(99.9%) 0.295 ms/op [Average]
  (min, avg, max) = (3.017, 3.028, 3.047), stdev = 0.016
  CI (99.9%): [2.733, 3.324] (assumes normal distribution)


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
# Warmup Iteration   1: 4.169 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.708 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.576 ±(99.9%) 0.006 ms/op
Iteration   1: 2.580 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.902 ms/op
                 createUser·p0.50:   2.634 ms/op
                 createUser·p0.90:   3.142 ms/op
                 createUser·p0.95:   3.285 ms/op
                 createUser·p0.99:   4.063 ms/op
                 createUser·p0.999:  11.649 ms/op
                 createUser·p0.9999: 13.527 ms/op
                 createUser·p1.00:   13.894 ms/op

Iteration   2: 2.567 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.023 ms/op
                 createUser·p0.50:   2.617 ms/op
                 createUser·p0.90:   3.125 ms/op
                 createUser·p0.95:   3.240 ms/op
                 createUser·p0.99:   3.772 ms/op
                 createUser·p0.999:  9.961 ms/op
                 createUser·p0.9999: 12.608 ms/op
                 createUser·p1.00:   12.829 ms/op

Iteration   3: 2.570 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.008 ms/op
                 createUser·p0.50:   2.630 ms/op
                 createUser·p0.90:   3.125 ms/op
                 createUser·p0.95:   3.248 ms/op
                 createUser·p0.99:   3.813 ms/op
                 createUser·p0.999:  8.133 ms/op
                 createUser·p0.9999: 10.783 ms/op
                 createUser·p1.00:   11.387 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 372894
  mean =      2.572 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 65 
    [ 1.250,  2.500) = 177305 
    [ 2.500,  3.750) = 190865 
    [ 3.750,  5.000) = 3871 
    [ 5.000,  6.250) = 370 
    [ 6.250,  7.500) = 33 
    [ 7.500,  8.750) = 18 
    [ 8.750, 10.000) = 61 
    [10.000, 11.250) = 107 
    [11.250, 12.500) = 117 
    [12.500, 13.750) = 78 
    [13.750, 15.000) = 4 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.902 ms/op
     p(50.0000) =      2.626 ms/op
     p(90.0000) =      3.129 ms/op
     p(95.0000) =      3.256 ms/op
     p(99.0000) =      3.887 ms/op
     p(99.9000) =      8.259 ms/op
     p(99.9900) =     12.943 ms/op
     p(99.9990) =     13.788 ms/op
     p(99.9999) =     13.894 ms/op
    p(100.0000) =     13.894 ms/op


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
# Warmup Iteration   1: 3.928 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.521 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.472 ±(99.9%) 0.005 ms/op
Iteration   1: 2.498 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.970 ms/op
                 existUser·p0.50:   2.560 ms/op
                 existUser·p0.90:   3.039 ms/op
                 existUser·p0.95:   3.166 ms/op
                 existUser·p0.99:   3.748 ms/op
                 existUser·p0.999:  11.420 ms/op
                 existUser·p0.9999: 13.586 ms/op
                 existUser·p1.00:   14.205 ms/op

Iteration   2: 2.478 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.008 ms/op
                 existUser·p0.50:   2.544 ms/op
                 existUser·p0.90:   3.002 ms/op
                 existUser·p0.95:   3.101 ms/op
                 existUser·p0.99:   3.600 ms/op
                 existUser·p0.999:  9.929 ms/op
                 existUser·p0.9999: 13.127 ms/op
                 existUser·p1.00:   14.008 ms/op

Iteration   3: 2.500 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.534 ms/op
                 existUser·p0.50:   2.527 ms/op
                 existUser·p0.90:   3.056 ms/op
                 existUser·p0.95:   3.187 ms/op
                 existUser·p0.99:   3.903 ms/op
                 existUser·p0.999:  6.694 ms/op
                 existUser·p0.9999: 11.128 ms/op
                 existUser·p1.00:   11.895 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 384878
  mean =      2.492 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 64 
    [ 1.250,  2.500) = 188925 
    [ 2.500,  3.750) = 191958 
    [ 3.750,  5.000) = 3026 
    [ 5.000,  6.250) = 486 
    [ 6.250,  7.500) = 54 
    [ 7.500,  8.750) = 9 
    [ 8.750, 10.000) = 58 
    [10.000, 11.250) = 113 
    [11.250, 12.500) = 87 
    [12.500, 13.750) = 93 
    [13.750, 15.000) = 5 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.534 ms/op
     p(50.0000) =      2.544 ms/op
     p(90.0000) =      3.031 ms/op
     p(95.0000) =      3.150 ms/op
     p(99.0000) =      3.764 ms/op
     p(99.9000) =      6.942 ms/op
     p(99.9900) =     12.993 ms/op
     p(99.9990) =     13.976 ms/op
     p(99.9999) =     14.205 ms/op
    p(100.0000) =     14.205 ms/op


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
# Warmup Iteration   1: 3.883 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.604 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.588 ±(99.9%) 0.006 ms/op
Iteration   1: 2.583 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.842 ms/op
                 getUser·p0.50:   2.601 ms/op
                 getUser·p0.90:   3.133 ms/op
                 getUser·p0.95:   3.289 ms/op
                 getUser·p0.99:   4.413 ms/op
                 getUser·p0.999:  10.997 ms/op
                 getUser·p0.9999: 13.588 ms/op
                 getUser·p1.00:   14.057 ms/op

Iteration   2: 2.558 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.024 ms/op
                 getUser·p0.50:   2.556 ms/op
                 getUser·p0.90:   3.125 ms/op
                 getUser·p0.95:   3.240 ms/op
                 getUser·p0.99:   3.797 ms/op
                 getUser·p0.999:  9.290 ms/op
                 getUser·p0.9999: 13.304 ms/op
                 getUser·p1.00:   14.123 ms/op

Iteration   3: 2.551 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.887 ms/op
                 getUser·p0.50:   2.576 ms/op
                 getUser·p0.90:   3.101 ms/op
                 getUser·p0.95:   3.207 ms/op
                 getUser·p0.99:   3.736 ms/op
                 getUser·p0.999:  9.378 ms/op
                 getUser·p0.9999: 12.016 ms/op
                 getUser·p1.00:   12.616 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 374119
  mean =      2.564 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 57 
    [ 1.250,  2.500) = 182614 
    [ 2.500,  3.750) = 186471 
    [ 3.750,  5.000) = 3755 
    [ 5.000,  6.250) = 739 
    [ 6.250,  7.500) = 78 
    [ 7.500,  8.750) = 15 
    [ 8.750, 10.000) = 55 
    [10.000, 11.250) = 145 
    [11.250, 12.500) = 76 
    [12.500, 13.750) = 102 
    [13.750, 15.000) = 12 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.842 ms/op
     p(50.0000) =      2.576 ms/op
     p(90.0000) =      3.121 ms/op
     p(95.0000) =      3.240 ms/op
     p(99.0000) =      3.932 ms/op
     p(99.9000) =      9.339 ms/op
     p(99.9900) =     13.248 ms/op
     p(99.9990) =     13.996 ms/op
     p(99.9999) =     14.123 ms/op
    p(100.0000) =     14.123 ms/op


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
# Warmup Iteration   1: 4.783 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.087 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.033 ±(99.9%) 0.009 ms/op
Iteration   1: 3.033 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.962 ms/op
                 listUser·p0.50:   2.974 ms/op
                 listUser·p0.90:   3.912 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   5.603 ms/op
                 listUser·p0.999:  8.907 ms/op
                 listUser·p0.9999: 11.042 ms/op
                 listUser·p1.00:   13.894 ms/op

Iteration   2: 3.018 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.916 ms/op
                 listUser·p0.50:   2.953 ms/op
                 listUser·p0.90:   3.891 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   5.644 ms/op
                 listUser·p0.999:  9.535 ms/op
                 listUser·p0.9999: 11.754 ms/op
                 listUser·p1.00:   14.369 ms/op

Iteration   3: 3.015 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.787 ms/op
                 listUser·p0.50:   2.957 ms/op
                 listUser·p0.90:   3.899 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   5.595 ms/op
                 listUser·p0.999:  8.929 ms/op
                 listUser·p0.9999: 11.007 ms/op
                 listUser·p1.00:   12.255 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 317361
  mean =      3.022 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 105 
    [ 1.250,  2.500) = 90312 
    [ 2.500,  3.750) = 187165 
    [ 3.750,  5.000) = 32363 
    [ 5.000,  6.250) = 6003 
    [ 6.250,  7.500) = 749 
    [ 7.500,  8.750) = 260 
    [ 8.750, 10.000) = 245 
    [10.000, 11.250) = 124 
    [11.250, 12.500) = 25 
    [12.500, 13.750) = 8 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.787 ms/op
     p(50.0000) =      2.961 ms/op
     p(90.0000) =      3.899 ms/op
     p(95.0000) =      4.399 ms/op
     p(99.0000) =      5.612 ms/op
     p(99.9000) =      9.126 ms/op
     p(99.9900) =     11.531 ms/op
     p(99.9990) =     13.491 ms/op
     p(99.9999) =     14.369 ms/op
    p(100.0000) =     14.369 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.647 ± 1.799  ops/ms
ClientPb.existUser                       thrpt       3  13.115 ± 0.866  ops/ms
ClientPb.getUser                         thrpt       3  12.630 ± 0.453  ops/ms
ClientPb.listUser                        thrpt       3  10.481 ± 0.286  ops/ms
ClientPb.createUser                       avgt       3   2.514 ± 0.112   ms/op
ClientPb.existUser                        avgt       3   2.514 ± 0.283   ms/op
ClientPb.getUser                          avgt       3   2.500 ± 0.782   ms/op
ClientPb.listUser                         avgt       3   3.028 ± 0.295   ms/op
ClientPb.createUser                     sample  372894   2.572 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.902           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.626           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.129           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.256           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.887           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.259           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.943           ms/op
ClientPb.createUser:createUser·p1.00    sample          13.894           ms/op
ClientPb.existUser                      sample  384878   2.492 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.534           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.544           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.031           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.150           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.764           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.942           ms/op
ClientPb.existUser:existUser·p0.9999    sample          12.993           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.205           ms/op
ClientPb.getUser                        sample  374119   2.564 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.842           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.576           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.121           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.240           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.932           ms/op
ClientPb.getUser:getUser·p0.999         sample           9.339           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.248           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.123           ms/op
ClientPb.listUser                       sample  317361   3.022 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.787           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.961           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.899           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.399           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.612           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.126           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.531           ms/op
ClientPb.listUser:listUser·p1.00        sample          14.369           ms/op
