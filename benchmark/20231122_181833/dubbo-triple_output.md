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
# Warmup Iteration   1: 5.267 ops/ms
# Warmup Iteration   2: 12.135 ops/ms
# Warmup Iteration   3: 12.426 ops/ms
Iteration   1: 12.540 ops/ms
Iteration   2: 12.775 ops/ms
Iteration   3: 12.819 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.711 ±(99.9%) 2.742 ops/ms [Average]
  (min, avg, max) = (12.540, 12.711, 12.819), stdev = 0.150
  CI (99.9%): [9.970, 15.453] (assumes normal distribution)


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
# Warmup Iteration   1: 7.680 ops/ms
# Warmup Iteration   2: 13.003 ops/ms
# Warmup Iteration   3: 12.990 ops/ms
Iteration   1: 12.990 ops/ms
Iteration   2: 13.097 ops/ms
Iteration   3: 12.909 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.999 ±(99.9%) 1.719 ops/ms [Average]
  (min, avg, max) = (12.909, 12.999, 13.097), stdev = 0.094
  CI (99.9%): [11.280, 14.717] (assumes normal distribution)


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
# Warmup Iteration   1: 7.540 ops/ms
# Warmup Iteration   2: 12.288 ops/ms
# Warmup Iteration   3: 12.496 ops/ms
Iteration   1: 12.744 ops/ms
Iteration   2: 12.712 ops/ms
Iteration   3: 12.717 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.724 ±(99.9%) 0.320 ops/ms [Average]
  (min, avg, max) = (12.712, 12.724, 12.744), stdev = 0.018
  CI (99.9%): [12.404, 13.045] (assumes normal distribution)


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
# Warmup Iteration   1: 6.765 ops/ms
# Warmup Iteration   2: 10.373 ops/ms
# Warmup Iteration   3: 10.516 ops/ms
Iteration   1: 10.646 ops/ms
Iteration   2: 10.478 ops/ms
Iteration   3: 10.579 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.568 ±(99.9%) 1.540 ops/ms [Average]
  (min, avg, max) = (10.478, 10.568, 10.646), stdev = 0.084
  CI (99.9%): [9.028, 12.107] (assumes normal distribution)


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
# Warmup Iteration   1: 4.027 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.586 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.518 ±(99.9%) 0.003 ms/op
Iteration   1: 2.525 ±(99.9%) 0.003 ms/op
Iteration   2: 2.513 ±(99.9%) 0.003 ms/op
Iteration   3: 2.503 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.514 ±(99.9%) 0.195 ms/op [Average]
  (min, avg, max) = (2.503, 2.514, 2.525), stdev = 0.011
  CI (99.9%): [2.319, 2.709] (assumes normal distribution)


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
# Warmup Iteration   1: 3.655 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.447 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.403 ±(99.9%) 0.003 ms/op
Iteration   1: 2.446 ±(99.9%) 0.004 ms/op
Iteration   2: 2.434 ±(99.9%) 0.003 ms/op
Iteration   3: 2.441 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.440 ±(99.9%) 0.108 ms/op [Average]
  (min, avg, max) = (2.434, 2.440, 2.446), stdev = 0.006
  CI (99.9%): [2.333, 2.548] (assumes normal distribution)


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
# Warmup Iteration   1: 3.849 ±(99.9%) 0.008 ms/op
# Warmup Iteration   2: 2.540 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.496 ±(99.9%) 0.005 ms/op
Iteration   1: 2.486 ±(99.9%) 0.003 ms/op
Iteration   2: 2.483 ±(99.9%) 0.004 ms/op
Iteration   3: 2.488 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.486 ±(99.9%) 0.050 ms/op [Average]
  (min, avg, max) = (2.483, 2.486, 2.488), stdev = 0.003
  CI (99.9%): [2.435, 2.536] (assumes normal distribution)


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
# Warmup Iteration   1: 5.178 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.048 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.047 ±(99.9%) 0.006 ms/op
Iteration   1: 3.039 ±(99.9%) 0.005 ms/op
Iteration   2: 3.022 ±(99.9%) 0.005 ms/op
Iteration   3: 3.042 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.034 ±(99.9%) 0.195 ms/op [Average]
  (min, avg, max) = (3.022, 3.034, 3.042), stdev = 0.011
  CI (99.9%): [2.839, 3.229] (assumes normal distribution)


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
# Warmup Iteration   1: 4.149 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.680 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.568 ±(99.9%) 0.006 ms/op
Iteration   1: 2.539 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.998 ms/op
                 createUser·p0.50:   2.630 ms/op
                 createUser·p0.90:   3.072 ms/op
                 createUser·p0.95:   3.183 ms/op
                 createUser·p0.99:   3.953 ms/op
                 createUser·p0.999:  12.403 ms/op
                 createUser·p0.9999: 14.057 ms/op
                 createUser·p1.00:   14.369 ms/op

Iteration   2: 2.570 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.910 ms/op
                 createUser·p0.50:   2.650 ms/op
                 createUser·p0.90:   3.117 ms/op
                 createUser·p0.95:   3.240 ms/op
                 createUser·p0.99:   3.831 ms/op
                 createUser·p0.999:  10.191 ms/op
                 createUser·p0.9999: 13.739 ms/op
                 createUser·p1.00:   14.008 ms/op

Iteration   3: 2.579 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.073 ms/op
                 createUser·p0.50:   2.613 ms/op
                 createUser·p0.90:   3.138 ms/op
                 createUser·p0.95:   3.265 ms/op
                 createUser·p0.99:   3.998 ms/op
                 createUser·p0.999:  9.297 ms/op
                 createUser·p0.9999: 10.748 ms/op
                 createUser·p1.00:   14.287 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 374186
  mean =      2.563 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 59 
    [ 1.250,  2.500) = 178272 
    [ 2.500,  3.750) = 190944 
    [ 3.750,  5.000) = 3716 
    [ 5.000,  6.250) = 708 
    [ 6.250,  7.500) = 81 
    [ 7.500,  8.750) = 21 
    [ 8.750, 10.000) = 63 
    [10.000, 11.250) = 106 
    [11.250, 12.500) = 53 
    [12.500, 13.750) = 137 
    [13.750, 15.000) = 26 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.910 ms/op
     p(50.0000) =      2.630 ms/op
     p(90.0000) =      3.109 ms/op
     p(95.0000) =      3.232 ms/op
     p(99.0000) =      3.924 ms/op
     p(99.9000) =      9.451 ms/op
     p(99.9900) =     13.700 ms/op
     p(99.9990) =     14.295 ms/op
     p(99.9999) =     14.369 ms/op
    p(100.0000) =     14.369 ms/op


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
# Warmup Iteration   1: 3.654 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.514 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.459 ±(99.9%) 0.005 ms/op
Iteration   1: 2.443 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.043 ms/op
                 existUser·p0.50:   2.490 ms/op
                 existUser·p0.90:   2.961 ms/op
                 existUser·p0.95:   3.056 ms/op
                 existUser·p0.99:   3.383 ms/op
                 existUser·p0.999:  9.370 ms/op
                 existUser·p0.9999: 13.992 ms/op
                 existUser·p1.00:   14.565 ms/op

Iteration   2: 2.471 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.903 ms/op
                 existUser·p0.50:   2.593 ms/op
                 existUser·p0.90:   2.982 ms/op
                 existUser·p0.95:   3.088 ms/op
                 existUser·p0.99:   4.002 ms/op
                 existUser·p0.999:  5.886 ms/op
                 existUser·p0.9999: 13.682 ms/op
                 existUser·p1.00:   13.763 ms/op

Iteration   3: 2.463 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.075 ms/op
                 existUser·p0.50:   2.519 ms/op
                 existUser·p0.90:   2.982 ms/op
                 existUser·p0.95:   3.092 ms/op
                 existUser·p0.99:   3.682 ms/op
                 existUser·p0.999:  8.725 ms/op
                 existUser·p0.9999: 12.649 ms/op
                 existUser·p1.00:   13.189 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 390097
  mean =      2.459 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 33 
    [ 1.250,  2.500) = 192489 
    [ 2.500,  3.750) = 194088 
    [ 3.750,  5.000) = 2707 
    [ 5.000,  6.250) = 349 
    [ 6.250,  7.500) = 52 
    [ 7.500,  8.750) = 25 
    [ 8.750, 10.000) = 65 
    [10.000, 11.250) = 63 
    [11.250, 12.500) = 73 
    [12.500, 13.750) = 110 
    [13.750, 15.000) = 43 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.903 ms/op
     p(50.0000) =      2.535 ms/op
     p(90.0000) =      2.974 ms/op
     p(95.0000) =      3.080 ms/op
     p(99.0000) =      3.662 ms/op
     p(99.9000) =      7.126 ms/op
     p(99.9900) =     13.795 ms/op
     p(99.9990) =     14.229 ms/op
     p(99.9999) =     14.565 ms/op
    p(100.0000) =     14.565 ms/op


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
# Warmup Iteration   1: 3.871 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.546 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.506 ±(99.9%) 0.006 ms/op
Iteration   1: 2.481 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.017 ms/op
                 getUser·p0.50:   2.507 ms/op
                 getUser·p0.90:   3.027 ms/op
                 getUser·p0.95:   3.183 ms/op
                 getUser·p0.99:   3.957 ms/op
                 getUser·p0.999:  7.611 ms/op
                 getUser·p0.9999: 14.061 ms/op
                 getUser·p1.00:   14.516 ms/op

Iteration   2: 2.494 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.818 ms/op
                 getUser·p0.50:   2.519 ms/op
                 getUser·p0.90:   3.043 ms/op
                 getUser·p0.95:   3.211 ms/op
                 getUser·p0.99:   4.375 ms/op
                 getUser·p0.999:  9.105 ms/op
                 getUser·p0.9999: 13.569 ms/op
                 getUser·p1.00:   14.516 ms/op

Iteration   3: 2.473 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.507 ms/op
                 getUser·p0.50:   2.494 ms/op
                 getUser·p0.90:   3.015 ms/op
                 getUser·p0.95:   3.166 ms/op
                 getUser·p0.99:   3.998 ms/op
                 getUser·p0.999:  7.563 ms/op
                 getUser·p0.9999: 12.633 ms/op
                 getUser·p1.00:   13.468 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 386332
  mean =      2.483 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 103 
    [ 1.250,  2.500) = 192552 
    [ 2.500,  3.750) = 187718 
    [ 3.750,  5.000) = 4742 
    [ 5.000,  6.250) = 782 
    [ 6.250,  7.500) = 42 
    [ 7.500,  8.750) = 25 
    [ 8.750, 10.000) = 29 
    [10.000, 11.250) = 79 
    [11.250, 12.500) = 74 
    [12.500, 13.750) = 143 
    [13.750, 15.000) = 43 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.507 ms/op
     p(50.0000) =      2.507 ms/op
     p(90.0000) =      3.027 ms/op
     p(95.0000) =      3.187 ms/op
     p(99.0000) =      4.088 ms/op
     p(99.9000) =      7.575 ms/op
     p(99.9900) =     13.891 ms/op
     p(99.9990) =     14.488 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.665 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.103 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.057 ±(99.9%) 0.009 ms/op
Iteration   1: 3.084 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.867 ms/op
                 listUser·p0.50:   3.015 ms/op
                 listUser·p0.90:   4.063 ms/op
                 listUser·p0.95:   4.645 ms/op
                 listUser·p0.99:   5.931 ms/op
                 listUser·p0.999:  8.677 ms/op
                 listUser·p0.9999: 12.642 ms/op
                 listUser·p1.00:   13.877 ms/op

Iteration   2: 3.045 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.015 ms/op
                 listUser·p0.50:   2.982 ms/op
                 listUser·p0.90:   3.953 ms/op
                 listUser·p0.95:   4.456 ms/op
                 listUser·p0.99:   5.693 ms/op
                 listUser·p0.999:  9.454 ms/op
                 listUser·p0.9999: 10.453 ms/op
                 listUser·p1.00:   11.796 ms/op

Iteration   3: 3.023 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.668 ms/op
                 listUser·p0.50:   2.970 ms/op
                 listUser·p0.90:   3.916 ms/op
                 listUser·p0.95:   4.440 ms/op
                 listUser·p0.99:   5.612 ms/op
                 listUser·p0.999:  8.901 ms/op
                 listUser·p0.9999: 10.770 ms/op
                 listUser·p1.00:   11.108 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 314405
  mean =      3.051 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 126 
    [ 1.250,  2.500) = 88528 
    [ 2.500,  3.750) = 182614 
    [ 3.750,  5.000) = 34706 
    [ 5.000,  6.250) = 6692 
    [ 6.250,  7.500) = 1034 
    [ 7.500,  8.750) = 295 
    [ 8.750, 10.000) = 304 
    [10.000, 11.250) = 83 
    [11.250, 12.500) = 13 
    [12.500, 13.750) = 9 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.668 ms/op
     p(50.0000) =      2.990 ms/op
     p(90.0000) =      3.977 ms/op
     p(95.0000) =      4.506 ms/op
     p(99.0000) =      5.751 ms/op
     p(99.9000) =      9.142 ms/op
     p(99.9900) =     11.078 ms/op
     p(99.9990) =     13.657 ms/op
     p(99.9999) =     13.877 ms/op
    p(100.0000) =     13.877 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.711 ± 2.742  ops/ms
ClientPb.existUser                       thrpt       3  12.999 ± 1.719  ops/ms
ClientPb.getUser                         thrpt       3  12.724 ± 0.320  ops/ms
ClientPb.listUser                        thrpt       3  10.568 ± 1.540  ops/ms
ClientPb.createUser                       avgt       3   2.514 ± 0.195   ms/op
ClientPb.existUser                        avgt       3   2.440 ± 0.108   ms/op
ClientPb.getUser                          avgt       3   2.486 ± 0.050   ms/op
ClientPb.listUser                         avgt       3   3.034 ± 0.195   ms/op
ClientPb.createUser                     sample  374186   2.563 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.910           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.630           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.109           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.232           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.924           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.451           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.700           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.369           ms/op
ClientPb.existUser                      sample  390097   2.459 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.903           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.535           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.974           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.080           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.662           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.126           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.795           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.565           ms/op
ClientPb.getUser                        sample  386332   2.483 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.507           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.507           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.027           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.187           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.088           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.575           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.891           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.516           ms/op
ClientPb.listUser                       sample  314405   3.051 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.668           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.990           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.977           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.506           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.751           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.142           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.078           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.877           ms/op
