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
# Warmup Iteration   1: 4.952 ops/ms
# Warmup Iteration   2: 12.002 ops/ms
# Warmup Iteration   3: 12.482 ops/ms
Iteration   1: 12.646 ops/ms
Iteration   2: 12.579 ops/ms
Iteration   3: 12.584 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.603 ±(99.9%) 0.682 ops/ms [Average]
  (min, avg, max) = (12.579, 12.603, 12.646), stdev = 0.037
  CI (99.9%): [11.921, 13.286] (assumes normal distribution)


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
# Warmup Iteration   1: 8.303 ops/ms
# Warmup Iteration   2: 12.994 ops/ms
# Warmup Iteration   3: 12.868 ops/ms
Iteration   1: 12.770 ops/ms
Iteration   2: 13.175 ops/ms
Iteration   3: 12.980 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.975 ±(99.9%) 3.693 ops/ms [Average]
  (min, avg, max) = (12.770, 12.975, 13.175), stdev = 0.202
  CI (99.9%): [9.282, 16.668] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:48
# Fork: 1 of 1
# Warmup Iteration   1: 7.575 ops/ms
# Warmup Iteration   2: 12.625 ops/ms
# Warmup Iteration   3: 12.763 ops/ms
Iteration   1: 12.922 ops/ms
Iteration   2: 12.857 ops/ms
Iteration   3: 12.803 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.860 ±(99.9%) 1.087 ops/ms [Average]
  (min, avg, max) = (12.803, 12.860, 12.922), stdev = 0.060
  CI (99.9%): [11.774, 13.947] (assumes normal distribution)


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
# Warmup Iteration   1: 6.537 ops/ms
# Warmup Iteration   2: 10.344 ops/ms
# Warmup Iteration   3: 10.424 ops/ms
Iteration   1: 10.437 ops/ms
Iteration   2: 10.304 ops/ms
Iteration   3: 10.320 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.354 ±(99.9%) 1.326 ops/ms [Average]
  (min, avg, max) = (10.304, 10.354, 10.437), stdev = 0.073
  CI (99.9%): [9.028, 11.679] (assumes normal distribution)


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
# Warmup Iteration   1: 4.045 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 2.632 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.574 ±(99.9%) 0.004 ms/op
Iteration   1: 2.575 ±(99.9%) 0.004 ms/op
Iteration   2: 2.598 ±(99.9%) 0.004 ms/op
Iteration   3: 2.568 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.581 ±(99.9%) 0.291 ms/op [Average]
  (min, avg, max) = (2.568, 2.581, 2.598), stdev = 0.016
  CI (99.9%): [2.290, 2.871] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:33
# Fork: 1 of 1
# Warmup Iteration   1: 3.832 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.543 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.465 ±(99.9%) 0.004 ms/op
Iteration   1: 2.493 ±(99.9%) 0.004 ms/op
Iteration   2: 2.484 ±(99.9%) 0.003 ms/op
Iteration   3: 2.479 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.485 ±(99.9%) 0.127 ms/op [Average]
  (min, avg, max) = (2.479, 2.485, 2.493), stdev = 0.007
  CI (99.9%): [2.358, 2.613] (assumes normal distribution)


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
# Warmup Iteration   1: 3.994 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.612 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.540 ±(99.9%) 0.004 ms/op
Iteration   1: 2.572 ±(99.9%) 0.004 ms/op
Iteration   2: 2.575 ±(99.9%) 0.003 ms/op
Iteration   3: 2.560 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.569 ±(99.9%) 0.142 ms/op [Average]
  (min, avg, max) = (2.560, 2.569, 2.575), stdev = 0.008
  CI (99.9%): [2.427, 2.711] (assumes normal distribution)


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
# Warmup Iteration   1: 4.991 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.130 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.097 ±(99.9%) 0.006 ms/op
Iteration   1: 3.099 ±(99.9%) 0.007 ms/op
Iteration   2: 3.051 ±(99.9%) 0.006 ms/op
Iteration   3: 3.094 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.081 ±(99.9%) 0.480 ms/op [Average]
  (min, avg, max) = (3.051, 3.081, 3.099), stdev = 0.026
  CI (99.9%): [2.601, 3.562] (assumes normal distribution)


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
# Warmup Iteration   1: 4.377 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.718 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.578 ±(99.9%) 0.006 ms/op
Iteration   1: 2.567 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.816 ms/op
                 createUser·p0.50:   2.662 ms/op
                 createUser·p0.90:   3.109 ms/op
                 createUser·p0.95:   3.215 ms/op
                 createUser·p0.99:   3.891 ms/op
                 createUser·p0.999:  11.895 ms/op
                 createUser·p0.9999: 17.614 ms/op
                 createUser·p1.00:   19.399 ms/op

Iteration   2: 2.551 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.980 ms/op
                 createUser·p0.50:   2.646 ms/op
                 createUser·p0.90:   3.088 ms/op
                 createUser·p0.95:   3.207 ms/op
                 createUser·p0.99:   3.817 ms/op
                 createUser·p0.999:  10.600 ms/op
                 createUser·p0.9999: 14.655 ms/op
                 createUser·p1.00:   14.778 ms/op

Iteration   3: 2.540 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.092 ms/op
                 createUser·p0.50:   2.617 ms/op
                 createUser·p0.90:   3.092 ms/op
                 createUser·p0.95:   3.211 ms/op
                 createUser·p0.99:   3.740 ms/op
                 createUser·p0.999:  8.130 ms/op
                 createUser·p0.9999: 9.851 ms/op
                 createUser·p1.00:   10.715 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 375694
  mean =      2.553 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 52 
    [ 1.250,  2.500) = 179837 
    [ 2.500,  3.750) = 191624 
    [ 3.750,  5.000) = 3403 
    [ 5.000,  6.250) = 307 
    [ 6.250,  7.500) = 47 
    [ 7.500,  8.750) = 41 
    [ 8.750, 10.000) = 101 
    [10.000, 11.250) = 54 
    [11.250, 12.500) = 101 
    [12.500, 13.750) = 63 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 17 
    [17.500, 18.750) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.816 ms/op
     p(50.0000) =      2.638 ms/op
     p(90.0000) =      3.097 ms/op
     p(95.0000) =      3.211 ms/op
     p(99.0000) =      3.813 ms/op
     p(99.9000) =      8.815 ms/op
     p(99.9900) =     14.713 ms/op
     p(99.9990) =     19.268 ms/op
     p(99.9999) =     19.399 ms/op
    p(100.0000) =     19.399 ms/op


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
# Warmup Iteration   1: 3.914 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.515 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.491 ±(99.9%) 0.005 ms/op
Iteration   1: 2.469 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.999 ms/op
                 existUser·p0.50:   2.527 ms/op
                 existUser·p0.90:   3.011 ms/op
                 existUser·p0.95:   3.121 ms/op
                 existUser·p0.99:   3.572 ms/op
                 existUser·p0.999:  7.103 ms/op
                 existUser·p0.9999: 14.441 ms/op
                 existUser·p1.00:   14.926 ms/op

Iteration   2: 2.488 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.873 ms/op
                 existUser·p0.50:   2.535 ms/op
                 existUser·p0.90:   3.031 ms/op
                 existUser·p0.95:   3.162 ms/op
                 existUser·p0.99:   3.842 ms/op
                 existUser·p0.999:  7.353 ms/op
                 existUser·p0.9999: 13.004 ms/op
                 existUser·p1.00:   13.976 ms/op

Iteration   3: 2.488 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.032 ms/op
                 existUser·p0.50:   2.531 ms/op
                 existUser·p0.90:   3.035 ms/op
                 existUser·p0.95:   3.166 ms/op
                 existUser·p0.99:   3.903 ms/op
                 existUser·p0.999:  8.676 ms/op
                 existUser·p0.9999: 11.958 ms/op
                 existUser·p1.00:   12.960 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 386407
  mean =      2.482 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 62 
    [ 1.250,  2.500) = 190097 
    [ 2.500,  3.750) = 192277 
    [ 3.750,  5.000) = 2984 
    [ 5.000,  6.250) = 540 
    [ 6.250,  7.500) = 35 
    [ 7.500,  8.750) = 62 
    [ 8.750, 10.000) = 46 
    [10.000, 11.250) = 43 
    [11.250, 12.500) = 127 
    [12.500, 13.750) = 95 
    [13.750, 15.000) = 39 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.873 ms/op
     p(50.0000) =      2.531 ms/op
     p(90.0000) =      3.027 ms/op
     p(95.0000) =      3.150 ms/op
     p(99.0000) =      3.768 ms/op
     p(99.9000) =      7.694 ms/op
     p(99.9900) =     13.763 ms/op
     p(99.9990) =     14.867 ms/op
     p(99.9999) =     14.926 ms/op
    p(100.0000) =     14.926 ms/op


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
# Warmup Iteration   1: 4.013 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.614 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.549 ±(99.9%) 0.006 ms/op
Iteration   1: 2.542 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.705 ms/op
                 getUser·p0.50:   2.585 ms/op
                 getUser·p0.90:   3.097 ms/op
                 getUser·p0.95:   3.219 ms/op
                 getUser·p0.99:   3.895 ms/op
                 getUser·p0.999:  11.911 ms/op
                 getUser·p0.9999: 14.530 ms/op
                 getUser·p1.00:   15.516 ms/op

Iteration   2: 2.574 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.979 ms/op
                 getUser·p0.50:   2.605 ms/op
                 getUser·p0.90:   3.129 ms/op
                 getUser·p0.95:   3.289 ms/op
                 getUser·p0.99:   4.293 ms/op
                 getUser·p0.999:  9.748 ms/op
                 getUser·p0.9999: 13.838 ms/op
                 getUser·p1.00:   14.369 ms/op

Iteration   3: 2.544 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.976 ms/op
                 getUser·p0.50:   2.580 ms/op
                 getUser·p0.90:   3.101 ms/op
                 getUser·p0.95:   3.219 ms/op
                 getUser·p0.99:   3.846 ms/op
                 getUser·p0.999:  8.195 ms/op
                 getUser·p0.9999: 10.984 ms/op
                 getUser·p1.00:   11.354 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 375655
  mean =      2.553 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 71 
    [ 1.250,  2.500) = 181963 
    [ 2.500,  3.750) = 188228 
    [ 3.750,  5.000) = 4247 
    [ 5.000,  6.250) = 642 
    [ 6.250,  7.500) = 85 
    [ 7.500,  8.750) = 51 
    [ 8.750, 10.000) = 93 
    [10.000, 11.250) = 108 
    [11.250, 12.500) = 24 
    [12.500, 13.750) = 100 
    [13.750, 15.000) = 38 
    [15.000, 16.250) = 5 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.705 ms/op
     p(50.0000) =      2.593 ms/op
     p(90.0000) =      3.109 ms/op
     p(95.0000) =      3.240 ms/op
     p(99.0000) =      3.985 ms/op
     p(99.9000) =      8.305 ms/op
     p(99.9900) =     13.786 ms/op
     p(99.9990) =     15.147 ms/op
     p(99.9999) =     15.516 ms/op
    p(100.0000) =     15.516 ms/op


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
# Warmup Iteration   1: 4.939 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 3.154 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.060 ±(99.9%) 0.009 ms/op
Iteration   1: 3.038 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.969 ms/op
                 listUser·p0.50:   2.978 ms/op
                 listUser·p0.90:   3.879 ms/op
                 listUser·p0.95:   4.342 ms/op
                 listUser·p0.99:   5.448 ms/op
                 listUser·p0.999:  8.962 ms/op
                 listUser·p0.9999: 10.796 ms/op
                 listUser·p1.00:   11.354 ms/op

Iteration   2: 3.053 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.938 ms/op
                 listUser·p0.50:   2.998 ms/op
                 listUser·p0.90:   3.957 ms/op
                 listUser·p0.95:   4.456 ms/op
                 listUser·p0.99:   5.628 ms/op
                 listUser·p0.999:  9.442 ms/op
                 listUser·p0.9999: 13.427 ms/op
                 listUser·p1.00:   14.369 ms/op

Iteration   3: 3.054 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.902 ms/op
                 listUser·p0.50:   2.990 ms/op
                 listUser·p0.90:   3.940 ms/op
                 listUser·p0.95:   4.456 ms/op
                 listUser·p0.99:   5.669 ms/op
                 listUser·p0.999:  10.425 ms/op
                 listUser·p0.9999: 13.043 ms/op
                 listUser·p1.00:   13.451 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 314627
  mean =      3.049 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 131 
    [ 1.250,  2.500) = 84117 
    [ 2.500,  3.750) = 188948 
    [ 3.750,  5.000) = 34219 
    [ 5.000,  6.250) = 5942 
    [ 6.250,  7.500) = 577 
    [ 7.500,  8.750) = 204 
    [ 8.750, 10.000) = 258 
    [10.000, 11.250) = 108 
    [11.250, 12.500) = 52 
    [12.500, 13.750) = 62 
    [13.750, 15.000) = 9 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.902 ms/op
     p(50.0000) =      2.990 ms/op
     p(90.0000) =      3.924 ms/op
     p(95.0000) =      4.415 ms/op
     p(99.0000) =      5.595 ms/op
     p(99.9000) =      9.634 ms/op
     p(99.9900) =     12.976 ms/op
     p(99.9990) =     13.973 ms/op
     p(99.9999) =     14.369 ms/op
    p(100.0000) =     14.369 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.603 ± 0.682  ops/ms
ClientPb.existUser                       thrpt       3  12.975 ± 3.693  ops/ms
ClientPb.getUser                         thrpt       3  12.860 ± 1.087  ops/ms
ClientPb.listUser                        thrpt       3  10.354 ± 1.326  ops/ms
ClientPb.createUser                       avgt       3   2.581 ± 0.291   ms/op
ClientPb.existUser                        avgt       3   2.485 ± 0.127   ms/op
ClientPb.getUser                          avgt       3   2.569 ± 0.142   ms/op
ClientPb.listUser                         avgt       3   3.081 ± 0.480   ms/op
ClientPb.createUser                     sample  375694   2.553 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.816           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.638           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.097           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.211           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.813           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.815           ms/op
ClientPb.createUser:createUser·p0.9999  sample          14.713           ms/op
ClientPb.createUser:createUser·p1.00    sample          19.399           ms/op
ClientPb.existUser                      sample  386407   2.482 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.873           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.531           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.027           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.150           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.768           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.694           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.763           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.926           ms/op
ClientPb.getUser                        sample  375655   2.553 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.705           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.593           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.109           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.240           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.985           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.305           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.786           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.516           ms/op
ClientPb.listUser                       sample  314627   3.049 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.902           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.990           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.924           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.415           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.595           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.634           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.976           ms/op
ClientPb.listUser:listUser·p1.00        sample          14.369           ms/op
