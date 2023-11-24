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
# Warmup Iteration   1: 4.231 ops/ms
# Warmup Iteration   2: 11.665 ops/ms
# Warmup Iteration   3: 12.110 ops/ms
Iteration   1: 12.119 ops/ms
Iteration   2: 12.037 ops/ms
Iteration   3: 12.375 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.177 ±(99.9%) 3.214 ops/ms [Average]
  (min, avg, max) = (12.037, 12.177, 12.375), stdev = 0.176
  CI (99.9%): [8.963, 15.390] (assumes normal distribution)


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
# Warmup Iteration   1: 7.521 ops/ms
# Warmup Iteration   2: 12.590 ops/ms
# Warmup Iteration   3: 12.748 ops/ms
Iteration   1: 12.846 ops/ms
Iteration   2: 12.781 ops/ms
Iteration   3: 12.826 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.818 ±(99.9%) 0.602 ops/ms [Average]
  (min, avg, max) = (12.781, 12.818, 12.846), stdev = 0.033
  CI (99.9%): [12.216, 13.420] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 7.248 ops/ms
# Warmup Iteration   2: 12.542 ops/ms
# Warmup Iteration   3: 12.750 ops/ms
Iteration   1: 12.869 ops/ms
Iteration   2: 12.734 ops/ms
Iteration   3: 12.407 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.670 ±(99.9%) 4.340 ops/ms [Average]
  (min, avg, max) = (12.407, 12.670, 12.869), stdev = 0.238
  CI (99.9%): [8.330, 17.010] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.200 ops/ms
# Warmup Iteration   2: 10.282 ops/ms
# Warmup Iteration   3: 10.285 ops/ms
Iteration   1: 10.497 ops/ms
Iteration   2: 10.483 ops/ms
Iteration   3: 10.526 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.502 ±(99.9%) 0.404 ops/ms [Average]
  (min, avg, max) = (10.483, 10.502, 10.526), stdev = 0.022
  CI (99.9%): [10.098, 10.906] (assumes normal distribution)


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
# Warmup Iteration   1: 4.225 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.593 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.562 ±(99.9%) 0.004 ms/op
Iteration   1: 2.570 ±(99.9%) 0.005 ms/op
Iteration   2: 2.615 ±(99.9%) 0.005 ms/op
Iteration   3: 2.577 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.587 ±(99.9%) 0.440 ms/op [Average]
  (min, avg, max) = (2.570, 2.587, 2.615), stdev = 0.024
  CI (99.9%): [2.147, 3.027] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.743 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.493 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.449 ±(99.9%) 0.004 ms/op
Iteration   1: 2.420 ±(99.9%) 0.003 ms/op
Iteration   2: 2.543 ±(99.9%) 0.004 ms/op
Iteration   3: 2.454 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.472 ±(99.9%) 1.157 ms/op [Average]
  (min, avg, max) = (2.420, 2.472, 2.543), stdev = 0.063
  CI (99.9%): [1.315, 3.630] (assumes normal distribution)


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
# Warmup Iteration   1: 4.113 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.549 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.513 ±(99.9%) 0.004 ms/op
Iteration   1: 2.517 ±(99.9%) 0.004 ms/op
Iteration   2: 2.501 ±(99.9%) 0.005 ms/op
Iteration   3: 2.594 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.537 ±(99.9%) 0.910 ms/op [Average]
  (min, avg, max) = (2.501, 2.537, 2.594), stdev = 0.050
  CI (99.9%): [1.628, 3.447] (assumes normal distribution)


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
# Warmup Iteration   1: 4.665 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.061 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.028 ±(99.9%) 0.005 ms/op
Iteration   1: 3.055 ±(99.9%) 0.005 ms/op
Iteration   2: 3.034 ±(99.9%) 0.007 ms/op
Iteration   3: 3.026 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.039 ±(99.9%) 0.274 ms/op [Average]
  (min, avg, max) = (3.026, 3.039, 3.055), stdev = 0.015
  CI (99.9%): [2.764, 3.313] (assumes normal distribution)


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
# Warmup Iteration   1: 4.106 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.643 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.545 ±(99.9%) 0.006 ms/op
Iteration   1: 2.522 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.617 ms/op
                 createUser·p0.50:   2.585 ms/op
                 createUser·p0.90:   3.064 ms/op
                 createUser·p0.95:   3.178 ms/op
                 createUser·p0.99:   3.777 ms/op
                 createUser·p0.999:  11.071 ms/op
                 createUser·p0.9999: 14.100 ms/op
                 createUser·p1.00:   14.926 ms/op

Iteration   2: 2.539 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.845 ms/op
                 createUser·p0.50:   2.638 ms/op
                 createUser·p0.90:   3.072 ms/op
                 createUser·p0.95:   3.187 ms/op
                 createUser·p0.99:   3.777 ms/op
                 createUser·p0.999:  9.735 ms/op
                 createUser·p0.9999: 12.013 ms/op
                 createUser·p1.00:   12.845 ms/op

Iteration   3: 2.508 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.692 ms/op
                 createUser·p0.50:   2.589 ms/op
                 createUser·p0.90:   3.047 ms/op
                 createUser·p0.95:   3.199 ms/op
                 createUser·p0.99:   3.940 ms/op
                 createUser·p0.999:  8.262 ms/op
                 createUser·p0.9999: 10.998 ms/op
                 createUser·p1.00:   11.469 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 380084
  mean =      2.523 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 61 
    [ 1.250,  2.500) = 181238 
    [ 2.500,  3.750) = 194332 
    [ 3.750,  5.000) = 3476 
    [ 5.000,  6.250) = 518 
    [ 6.250,  7.500) = 43 
    [ 7.500,  8.750) = 61 
    [ 8.750, 10.000) = 76 
    [10.000, 11.250) = 114 
    [11.250, 12.500) = 83 
    [12.500, 13.750) = 53 
    [13.750, 15.000) = 29 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.617 ms/op
     p(50.0000) =      2.601 ms/op
     p(90.0000) =      3.060 ms/op
     p(95.0000) =      3.187 ms/op
     p(99.0000) =      3.842 ms/op
     p(99.9000) =      8.313 ms/op
     p(99.9900) =     13.598 ms/op
     p(99.9990) =     14.716 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.919 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.424 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.461 ±(99.9%) 0.005 ms/op
Iteration   1: 2.409 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.946 ms/op
                 existUser·p0.50:   2.515 ms/op
                 existUser·p0.90:   2.908 ms/op
                 existUser·p0.95:   3.011 ms/op
                 existUser·p0.99:   3.592 ms/op
                 existUser·p0.999:  5.814 ms/op
                 existUser·p0.9999: 13.749 ms/op
                 existUser·p1.00:   14.156 ms/op

Iteration   2: 2.423 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.880 ms/op
                 existUser·p0.50:   2.470 ms/op
                 existUser·p0.90:   2.953 ms/op
                 existUser·p0.95:   3.068 ms/op
                 existUser·p0.99:   3.604 ms/op
                 existUser·p0.999:  5.432 ms/op
                 existUser·p0.9999: 12.465 ms/op
                 existUser·p1.00:   12.714 ms/op

Iteration   3: 2.441 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.922 ms/op
                 existUser·p0.50:   2.470 ms/op
                 existUser·p0.90:   2.978 ms/op
                 existUser·p0.95:   3.113 ms/op
                 existUser·p0.99:   3.822 ms/op
                 existUser·p0.999:  9.012 ms/op
                 existUser·p0.9999: 12.648 ms/op
                 existUser·p1.00:   12.993 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 395687
  mean =      2.424 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 63 
    [ 1.250,  2.500) = 199436 
    [ 2.500,  3.750) = 192625 
    [ 3.750,  5.000) = 2759 
    [ 5.000,  6.250) = 383 
    [ 6.250,  7.500) = 44 
    [ 7.500,  8.750) = 40 
    [ 8.750, 10.000) = 55 
    [10.000, 11.250) = 77 
    [11.250, 12.500) = 62 
    [12.500, 13.750) = 130 
    [13.750, 15.000) = 13 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.880 ms/op
     p(50.0000) =      2.486 ms/op
     p(90.0000) =      2.945 ms/op
     p(95.0000) =      3.064 ms/op
     p(99.0000) =      3.682 ms/op
     p(99.9000) =      6.690 ms/op
     p(99.9900) =     13.245 ms/op
     p(99.9990) =     14.107 ms/op
     p(99.9999) =     14.156 ms/op
    p(100.0000) =     14.156 ms/op


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
# Warmup Iteration   1: 4.020 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.633 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.510 ±(99.9%) 0.006 ms/op
Iteration   1: 2.500 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.870 ms/op
                 getUser·p0.50:   2.531 ms/op
                 getUser·p0.90:   3.039 ms/op
                 getUser·p0.95:   3.166 ms/op
                 getUser·p0.99:   3.949 ms/op
                 getUser·p0.999:  12.042 ms/op
                 getUser·p0.9999: 14.772 ms/op
                 getUser·p1.00:   15.122 ms/op

Iteration   2: 2.502 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.908 ms/op
                 getUser·p0.50:   2.535 ms/op
                 getUser·p0.90:   3.047 ms/op
                 getUser·p0.95:   3.187 ms/op
                 getUser·p0.99:   3.994 ms/op
                 getUser·p0.999:  9.463 ms/op
                 getUser·p0.9999: 13.959 ms/op
                 getUser·p1.00:   14.336 ms/op

Iteration   3: 2.484 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.926 ms/op
                 getUser·p0.50:   2.515 ms/op
                 getUser·p0.90:   3.031 ms/op
                 getUser·p0.95:   3.170 ms/op
                 getUser·p0.99:   3.838 ms/op
                 getUser·p0.999:  5.595 ms/op
                 getUser·p0.9999: 10.523 ms/op
                 getUser·p1.00:   11.452 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 384421
  mean =      2.495 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 85 
    [ 1.250,  2.500) = 190052 
    [ 2.500,  3.750) = 189105 
    [ 3.750,  5.000) = 4259 
    [ 5.000,  6.250) = 530 
    [ 6.250,  7.500) = 38 
    [ 7.500,  8.750) = 8 
    [ 8.750, 10.000) = 74 
    [10.000, 11.250) = 100 
    [11.250, 12.500) = 23 
    [12.500, 13.750) = 87 
    [13.750, 15.000) = 53 
    [15.000, 16.250) = 7 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.870 ms/op
     p(50.0000) =      2.527 ms/op
     p(90.0000) =      3.039 ms/op
     p(95.0000) =      3.174 ms/op
     p(99.0000) =      3.932 ms/op
     p(99.9000) =      6.288 ms/op
     p(99.9900) =     14.107 ms/op
     p(99.9990) =     15.081 ms/op
     p(99.9999) =     15.122 ms/op
    p(100.0000) =     15.122 ms/op


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
# Warmup Iteration   1: 4.884 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.156 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.035 ±(99.9%) 0.009 ms/op
Iteration   1: 3.024 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.000 ms/op
                 listUser·p0.50:   2.961 ms/op
                 listUser·p0.90:   3.891 ms/op
                 listUser·p0.95:   4.424 ms/op
                 listUser·p0.99:   5.652 ms/op
                 listUser·p0.999:  9.830 ms/op
                 listUser·p0.9999: 11.108 ms/op
                 listUser·p1.00:   11.911 ms/op

Iteration   2: 3.048 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.807 ms/op
                 listUser·p0.50:   2.990 ms/op
                 listUser·p0.90:   3.961 ms/op
                 listUser·p0.95:   4.432 ms/op
                 listUser·p0.99:   5.540 ms/op
                 listUser·p0.999:  9.230 ms/op
                 listUser·p0.9999: 11.068 ms/op
                 listUser·p1.00:   11.993 ms/op

Iteration   3: 3.024 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.954 ms/op
                 listUser·p0.50:   2.966 ms/op
                 listUser·p0.90:   3.871 ms/op
                 listUser·p0.95:   4.309 ms/op
                 listUser·p0.99:   5.472 ms/op
                 listUser·p0.999:  8.672 ms/op
                 listUser·p0.9999: 10.469 ms/op
                 listUser·p1.00:   10.748 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 316335
  mean =      3.032 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 116 
    [ 1.250,  2.500) = 86137 
    [ 2.500,  3.750) = 189419 
    [ 3.750,  5.000) = 33547 
    [ 5.000,  6.250) = 5775 
    [ 6.250,  7.500) = 671 
    [ 7.500,  8.750) = 246 
    [ 8.750, 10.000) = 241 
    [10.000, 11.250) = 171 
    [11.250, 12.500) = 12 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.807 ms/op
     p(50.0000) =      2.970 ms/op
     p(90.0000) =      3.903 ms/op
     p(95.0000) =      4.391 ms/op
     p(99.0000) =      5.562 ms/op
     p(99.9000) =      9.241 ms/op
     p(99.9900) =     11.010 ms/op
     p(99.9990) =     11.925 ms/op
     p(99.9999) =     11.993 ms/op
    p(100.0000) =     11.993 ms/op


# Run complete. Total time: 00:13:00

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.177 ± 3.214  ops/ms
ClientPb.existUser                       thrpt       3  12.818 ± 0.602  ops/ms
ClientPb.getUser                         thrpt       3  12.670 ± 4.340  ops/ms
ClientPb.listUser                        thrpt       3  10.502 ± 0.404  ops/ms
ClientPb.createUser                       avgt       3   2.587 ± 0.440   ms/op
ClientPb.existUser                        avgt       3   2.472 ± 1.157   ms/op
ClientPb.getUser                          avgt       3   2.537 ± 0.910   ms/op
ClientPb.listUser                         avgt       3   3.039 ± 0.274   ms/op
ClientPb.createUser                     sample  380084   2.523 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.617           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.601           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.060           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.187           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.842           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.313           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.598           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.926           ms/op
ClientPb.existUser                      sample  395687   2.424 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.880           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.486           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.945           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.064           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.682           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.690           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.245           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.156           ms/op
ClientPb.getUser                        sample  384421   2.495 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.870           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.527           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.039           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.174           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.932           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.288           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.107           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.122           ms/op
ClientPb.listUser                       sample  316335   3.032 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.807           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.970           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.903           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.391           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.562           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.241           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.010           ms/op
ClientPb.listUser:listUser·p1.00        sample          11.993           ms/op
