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
# Warmup Iteration   1: 5.340 ops/ms
# Warmup Iteration   2: 12.425 ops/ms
# Warmup Iteration   3: 12.485 ops/ms
Iteration   1: 12.629 ops/ms
Iteration   2: 12.683 ops/ms
Iteration   3: 12.799 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.704 ±(99.9%) 1.578 ops/ms [Average]
  (min, avg, max) = (12.629, 12.704, 12.799), stdev = 0.087
  CI (99.9%): [11.125, 14.282] (assumes normal distribution)


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
# Warmup Iteration   1: 8.968 ops/ms
# Warmup Iteration   2: 13.225 ops/ms
# Warmup Iteration   3: 13.265 ops/ms
Iteration   1: 13.345 ops/ms
Iteration   2: 13.294 ops/ms
Iteration   3: 13.227 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.289 ±(99.9%) 1.080 ops/ms [Average]
  (min, avg, max) = (13.227, 13.289, 13.345), stdev = 0.059
  CI (99.9%): [12.208, 14.369] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:46
# Fork: 1 of 1
# Warmup Iteration   1: 7.846 ops/ms
# Warmup Iteration   2: 12.767 ops/ms
# Warmup Iteration   3: 12.830 ops/ms
Iteration   1: 12.756 ops/ms
Iteration   2: 12.848 ops/ms
Iteration   3: 12.958 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.854 ±(99.9%) 1.845 ops/ms [Average]
  (min, avg, max) = (12.756, 12.854, 12.958), stdev = 0.101
  CI (99.9%): [11.009, 14.698] (assumes normal distribution)


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
# Warmup Iteration   1: 6.676 ops/ms
# Warmup Iteration   2: 10.472 ops/ms
# Warmup Iteration   3: 10.625 ops/ms
Iteration   1: 10.652 ops/ms
Iteration   2: 10.664 ops/ms
Iteration   3: 10.569 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.628 ±(99.9%) 0.941 ops/ms [Average]
  (min, avg, max) = (10.569, 10.628, 10.664), stdev = 0.052
  CI (99.9%): [9.688, 11.569] (assumes normal distribution)


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
# Warmup Iteration   1: 3.900 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.589 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.511 ±(99.9%) 0.004 ms/op
Iteration   1: 2.533 ±(99.9%) 0.004 ms/op
Iteration   2: 2.534 ±(99.9%) 0.004 ms/op
Iteration   3: 2.505 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.524 ±(99.9%) 0.305 ms/op [Average]
  (min, avg, max) = (2.505, 2.524, 2.534), stdev = 0.017
  CI (99.9%): [2.219, 2.829] (assumes normal distribution)


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
# Warmup Iteration   1: 3.992 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.478 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.452 ±(99.9%) 0.004 ms/op
Iteration   1: 2.467 ±(99.9%) 0.004 ms/op
Iteration   2: 2.447 ±(99.9%) 0.004 ms/op
Iteration   3: 2.452 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.455 ±(99.9%) 0.190 ms/op [Average]
  (min, avg, max) = (2.447, 2.455, 2.467), stdev = 0.010
  CI (99.9%): [2.265, 2.646] (assumes normal distribution)


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
# Warmup Iteration   1: 3.815 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.523 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.504 ±(99.9%) 0.005 ms/op
Iteration   1: 2.490 ±(99.9%) 0.004 ms/op
Iteration   2: 2.512 ±(99.9%) 0.005 ms/op
Iteration   3: 2.487 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.497 ±(99.9%) 0.255 ms/op [Average]
  (min, avg, max) = (2.487, 2.497, 2.512), stdev = 0.014
  CI (99.9%): [2.242, 2.751] (assumes normal distribution)


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
# Warmup Iteration   1: 4.581 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.004 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.983 ±(99.9%) 0.006 ms/op
Iteration   1: 2.953 ±(99.9%) 0.005 ms/op
Iteration   2: 2.970 ±(99.9%) 0.005 ms/op
Iteration   3: 2.988 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.971 ±(99.9%) 0.319 ms/op [Average]
  (min, avg, max) = (2.953, 2.971, 2.988), stdev = 0.018
  CI (99.9%): [2.651, 3.290] (assumes normal distribution)


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
# Warmup Iteration   1: 4.072 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.613 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.490 ±(99.9%) 0.005 ms/op
Iteration   1: 2.493 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.949 ms/op
                 createUser·p0.50:   2.576 ms/op
                 createUser·p0.90:   3.031 ms/op
                 createUser·p0.95:   3.142 ms/op
                 createUser·p0.99:   3.609 ms/op
                 createUser·p0.999:  9.643 ms/op
                 createUser·p0.9999: 14.795 ms/op
                 createUser·p1.00:   15.581 ms/op

Iteration   2: 2.489 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.991 ms/op
                 createUser·p0.50:   2.597 ms/op
                 createUser·p0.90:   3.015 ms/op
                 createUser·p0.95:   3.117 ms/op
                 createUser·p0.99:   3.547 ms/op
                 createUser·p0.999:  8.032 ms/op
                 createUser·p0.9999: 13.014 ms/op
                 createUser·p1.00:   13.599 ms/op

Iteration   3: 2.505 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.993 ms/op
                 createUser·p0.50:   2.605 ms/op
                 createUser·p0.90:   3.031 ms/op
                 createUser·p0.95:   3.158 ms/op
                 createUser·p0.99:   3.867 ms/op
                 createUser·p0.999:  8.651 ms/op
                 createUser·p0.9999: 11.358 ms/op
                 createUser·p1.00:   11.960 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 384418
  mean =      2.496 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 44 
    [ 1.250,  2.500) = 184672 
    [ 2.500,  3.750) = 196354 
    [ 3.750,  5.000) = 2495 
    [ 5.000,  6.250) = 333 
    [ 6.250,  7.500) = 83 
    [ 7.500,  8.750) = 67 
    [ 8.750, 10.000) = 75 
    [10.000, 11.250) = 55 
    [11.250, 12.500) = 100 
    [12.500, 13.750) = 90 
    [13.750, 15.000) = 44 
    [15.000, 16.250) = 6 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.949 ms/op
     p(50.0000) =      2.593 ms/op
     p(90.0000) =      3.023 ms/op
     p(95.0000) =      3.138 ms/op
     p(99.0000) =      3.666 ms/op
     p(99.9000) =      8.651 ms/op
     p(99.9900) =     14.098 ms/op
     p(99.9990) =     15.455 ms/op
     p(99.9999) =     15.581 ms/op
    p(100.0000) =     15.581 ms/op


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
# Warmup Iteration   1: 3.631 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.482 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.494 ±(99.9%) 0.005 ms/op
Iteration   1: 2.463 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.946 ms/op
                 existUser·p0.50:   2.560 ms/op
                 existUser·p0.90:   2.990 ms/op
                 existUser·p0.95:   3.084 ms/op
                 existUser·p0.99:   3.424 ms/op
                 existUser·p0.999:  6.839 ms/op
                 existUser·p0.9999: 13.992 ms/op
                 existUser·p1.00:   14.598 ms/op

Iteration   2: 2.443 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.016 ms/op
                 existUser·p0.50:   2.519 ms/op
                 existUser·p0.90:   2.961 ms/op
                 existUser·p0.95:   3.060 ms/op
                 existUser·p0.99:   3.588 ms/op
                 existUser·p0.999:  5.905 ms/op
                 existUser·p0.9999: 12.975 ms/op
                 existUser·p1.00:   13.926 ms/op

Iteration   3: 2.466 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.796 ms/op
                 existUser·p0.50:   2.458 ms/op
                 existUser·p0.90:   3.015 ms/op
                 existUser·p0.95:   3.125 ms/op
                 existUser·p0.99:   3.731 ms/op
                 existUser·p0.999:  7.630 ms/op
                 existUser·p0.9999: 11.583 ms/op
                 existUser·p1.00:   15.188 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 390197
  mean =      2.457 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 46 
    [ 1.250,  2.500) = 194634 
    [ 2.500,  3.750) = 192520 
    [ 3.750,  5.000) = 2234 
    [ 5.000,  6.250) = 367 
    [ 6.250,  7.500) = 10 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 81 
    [10.000, 11.250) = 108 
    [11.250, 12.500) = 111 
    [12.500, 13.750) = 63 
    [13.750, 15.000) = 21 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.796 ms/op
     p(50.0000) =      2.507 ms/op
     p(90.0000) =      2.990 ms/op
     p(95.0000) =      3.092 ms/op
     p(99.0000) =      3.584 ms/op
     p(99.9000) =      6.621 ms/op
     p(99.9900) =     13.320 ms/op
     p(99.9990) =     14.429 ms/op
     p(99.9999) =     15.188 ms/op
    p(100.0000) =     15.188 ms/op


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
# Warmup Iteration   1: 3.926 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.623 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.549 ±(99.9%) 0.006 ms/op
Iteration   1: 2.527 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.933 ms/op
                 getUser·p0.50:   2.544 ms/op
                 getUser·p0.90:   3.076 ms/op
                 getUser·p0.95:   3.187 ms/op
                 getUser·p0.99:   3.785 ms/op
                 getUser·p0.999:  11.796 ms/op
                 getUser·p0.9999: 13.604 ms/op
                 getUser·p1.00:   13.926 ms/op

Iteration   2: 2.560 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.069 ms/op
                 getUser·p0.50:   2.556 ms/op
                 getUser·p0.90:   3.121 ms/op
                 getUser·p0.95:   3.297 ms/op
                 getUser·p0.99:   4.473 ms/op
                 getUser·p0.999:  9.634 ms/op
                 getUser·p0.9999: 13.190 ms/op
                 getUser·p1.00:   13.828 ms/op

Iteration   3: 2.522 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.110 ms/op
                 getUser·p0.50:   2.560 ms/op
                 getUser·p0.90:   3.068 ms/op
                 getUser·p0.95:   3.174 ms/op
                 getUser·p0.99:   3.703 ms/op
                 getUser·p0.999:  9.507 ms/op
                 getUser·p0.9999: 11.682 ms/op
                 getUser·p1.00:   13.074 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 378235
  mean =      2.536 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 57 
    [ 1.250,  2.500) = 185297 
    [ 2.500,  3.750) = 187740 
    [ 3.750,  5.000) = 3881 
    [ 5.000,  6.250) = 775 
    [ 6.250,  7.500) = 62 
    [ 7.500,  8.750) = 10 
    [ 8.750, 10.000) = 70 
    [10.000, 11.250) = 106 
    [11.250, 12.500) = 88 
    [12.500, 13.750) = 138 
    [13.750, 15.000) = 11 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.933 ms/op
     p(50.0000) =      2.552 ms/op
     p(90.0000) =      3.084 ms/op
     p(95.0000) =      3.211 ms/op
     p(99.0000) =      3.949 ms/op
     p(99.9000) =      9.548 ms/op
     p(99.9900) =     13.451 ms/op
     p(99.9990) =     13.828 ms/op
     p(99.9999) =     13.926 ms/op
    p(100.0000) =     13.926 ms/op


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
# Warmup Iteration   1: 4.421 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 2.997 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.958 ±(99.9%) 0.008 ms/op
Iteration   1: 2.950 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.833 ms/op
                 listUser·p0.50:   2.904 ms/op
                 listUser·p0.90:   3.789 ms/op
                 listUser·p0.95:   4.301 ms/op
                 listUser·p0.99:   5.480 ms/op
                 listUser·p0.999:  9.359 ms/op
                 listUser·p0.9999: 13.681 ms/op
                 listUser·p1.00:   14.500 ms/op

Iteration   2: 2.965 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.871 ms/op
                 listUser·p0.50:   2.908 ms/op
                 listUser·p0.90:   3.826 ms/op
                 listUser·p0.95:   4.325 ms/op
                 listUser·p0.99:   5.489 ms/op
                 listUser·p0.999:  9.784 ms/op
                 listUser·p0.9999: 12.812 ms/op
                 listUser·p1.00:   12.993 ms/op

Iteration   3: 2.952 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.680 ms/op
                 listUser·p0.50:   2.884 ms/op
                 listUser·p0.90:   3.801 ms/op
                 listUser·p0.95:   4.309 ms/op
                 listUser·p0.99:   5.437 ms/op
                 listUser·p0.999:  9.568 ms/op
                 listUser·p0.9999: 12.982 ms/op
                 listUser·p1.00:   14.221 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 324544
  mean =      2.955 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 140 
    [ 1.250,  2.500) = 103360 
    [ 2.500,  3.750) = 185746 
    [ 3.750,  5.000) = 28922 
    [ 5.000,  6.250) = 5186 
    [ 6.250,  7.500) = 507 
    [ 7.500,  8.750) = 280 
    [ 8.750, 10.000) = 145 
    [10.000, 11.250) = 122 
    [11.250, 12.500) = 83 
    [12.500, 13.750) = 45 
    [13.750, 15.000) = 8 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.680 ms/op
     p(50.0000) =      2.900 ms/op
     p(90.0000) =      3.805 ms/op
     p(95.0000) =      4.309 ms/op
     p(99.0000) =      5.464 ms/op
     p(99.9000) =      9.454 ms/op
     p(99.9900) =     12.838 ms/op
     p(99.9990) =     13.935 ms/op
     p(99.9999) =     14.500 ms/op
    p(100.0000) =     14.500 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.704 ± 1.578  ops/ms
ClientPb.existUser                       thrpt       3  13.289 ± 1.080  ops/ms
ClientPb.getUser                         thrpt       3  12.854 ± 1.845  ops/ms
ClientPb.listUser                        thrpt       3  10.628 ± 0.941  ops/ms
ClientPb.createUser                       avgt       3   2.524 ± 0.305   ms/op
ClientPb.existUser                        avgt       3   2.455 ± 0.190   ms/op
ClientPb.getUser                          avgt       3   2.497 ± 0.255   ms/op
ClientPb.listUser                         avgt       3   2.971 ± 0.319   ms/op
ClientPb.createUser                     sample  384418   2.496 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.949           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.593           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.023           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.138           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.666           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.651           ms/op
ClientPb.createUser:createUser·p0.9999  sample          14.098           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.581           ms/op
ClientPb.existUser                      sample  390197   2.457 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.796           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.507           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.990           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.092           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.584           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.621           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.320           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.188           ms/op
ClientPb.getUser                        sample  378235   2.536 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.933           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.552           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.084           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.211           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.949           ms/op
ClientPb.getUser:getUser·p0.999         sample           9.548           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.451           ms/op
ClientPb.getUser:getUser·p1.00          sample          13.926           ms/op
ClientPb.listUser                       sample  324544   2.955 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.680           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.900           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.805           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.309           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.464           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.454           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.838           ms/op
ClientPb.listUser:listUser·p1.00        sample          14.500           ms/op
