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
# Warmup Iteration   2: 11.863 ops/ms
# Warmup Iteration   3: 12.408 ops/ms
Iteration   1: 12.368 ops/ms
Iteration   2: 12.446 ops/ms
Iteration   3: 12.518 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.444 ±(99.9%) 1.369 ops/ms [Average]
  (min, avg, max) = (12.368, 12.444, 12.518), stdev = 0.075
  CI (99.9%): [11.075, 13.812] (assumes normal distribution)


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
# Warmup Iteration   1: 8.072 ops/ms
# Warmup Iteration   2: 12.897 ops/ms
# Warmup Iteration   3: 12.877 ops/ms
Iteration   1: 12.822 ops/ms
Iteration   2: 13.127 ops/ms
Iteration   3: 12.776 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.908 ±(99.9%) 3.474 ops/ms [Average]
  (min, avg, max) = (12.776, 12.908, 13.127), stdev = 0.190
  CI (99.9%): [9.434, 16.382] (assumes normal distribution)


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
# Warmup Iteration   1: 7.667 ops/ms
# Warmup Iteration   2: 12.471 ops/ms
# Warmup Iteration   3: 12.589 ops/ms
Iteration   1: 12.602 ops/ms
Iteration   2: 12.773 ops/ms
Iteration   3: 12.691 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.689 ±(99.9%) 1.559 ops/ms [Average]
  (min, avg, max) = (12.602, 12.689, 12.773), stdev = 0.085
  CI (99.9%): [11.130, 14.248] (assumes normal distribution)


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
# Warmup Iteration   1: 6.392 ops/ms
# Warmup Iteration   2: 10.358 ops/ms
# Warmup Iteration   3: 10.410 ops/ms
Iteration   1: 10.472 ops/ms
Iteration   2: 10.458 ops/ms
Iteration   3: 10.288 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.406 ±(99.9%) 1.874 ops/ms [Average]
  (min, avg, max) = (10.288, 10.406, 10.472), stdev = 0.103
  CI (99.9%): [8.532, 12.280] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.181 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 2.639 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.586 ±(99.9%) 0.005 ms/op
Iteration   1: 2.601 ±(99.9%) 0.004 ms/op
Iteration   2: 2.604 ±(99.9%) 0.004 ms/op
Iteration   3: 2.620 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.608 ±(99.9%) 0.182 ms/op [Average]
  (min, avg, max) = (2.601, 2.608, 2.620), stdev = 0.010
  CI (99.9%): [2.426, 2.791] (assumes normal distribution)


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
# Warmup Iteration   1: 3.768 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.471 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.514 ±(99.9%) 0.004 ms/op
Iteration   1: 2.486 ±(99.9%) 0.003 ms/op
Iteration   2: 2.480 ±(99.9%) 0.005 ms/op
Iteration   3: 2.484 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.483 ±(99.9%) 0.056 ms/op [Average]
  (min, avg, max) = (2.480, 2.483, 2.486), stdev = 0.003
  CI (99.9%): [2.427, 2.540] (assumes normal distribution)


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
# Warmup Iteration   1: 4.077 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.595 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.526 ±(99.9%) 0.006 ms/op
Iteration   1: 2.524 ±(99.9%) 0.004 ms/op
Iteration   2: 2.541 ±(99.9%) 0.004 ms/op
Iteration   3: 2.507 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.524 ±(99.9%) 0.308 ms/op [Average]
  (min, avg, max) = (2.507, 2.524, 2.541), stdev = 0.017
  CI (99.9%): [2.216, 2.832] (assumes normal distribution)


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
# Warmup Iteration   1: 4.838 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.120 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.074 ±(99.9%) 0.006 ms/op
Iteration   1: 3.060 ±(99.9%) 0.005 ms/op
Iteration   2: 3.070 ±(99.9%) 0.005 ms/op
Iteration   3: 3.061 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.064 ±(99.9%) 0.102 ms/op [Average]
  (min, avg, max) = (3.060, 3.064, 3.070), stdev = 0.006
  CI (99.9%): [2.962, 3.166] (assumes normal distribution)


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
# Warmup Iteration   1: 4.320 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 2.609 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.593 ±(99.9%) 0.006 ms/op
Iteration   1: 2.567 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.020 ms/op
                 createUser·p0.50:   2.617 ms/op
                 createUser·p0.90:   3.121 ms/op
                 createUser·p0.95:   3.265 ms/op
                 createUser·p0.99:   3.961 ms/op
                 createUser·p0.999:  11.280 ms/op
                 createUser·p0.9999: 14.205 ms/op
                 createUser·p1.00:   14.877 ms/op

Iteration   2: 2.568 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.002 ms/op
                 createUser·p0.50:   2.642 ms/op
                 createUser·p0.90:   3.121 ms/op
                 createUser·p0.95:   3.256 ms/op
                 createUser·p0.99:   3.854 ms/op
                 createUser·p0.999:  10.412 ms/op
                 createUser·p0.9999: 13.961 ms/op
                 createUser·p1.00:   14.303 ms/op

Iteration   3: 2.579 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.652 ms/op
                 createUser·p0.50:   2.658 ms/op
                 createUser·p0.90:   3.125 ms/op
                 createUser·p0.95:   3.260 ms/op
                 createUser·p0.99:   3.998 ms/op
                 createUser·p0.999:  8.684 ms/op
                 createUser·p0.9999: 10.414 ms/op
                 createUser·p1.00:   12.321 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 372959
  mean =      2.571 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 52 
    [ 1.250,  2.500) = 175532 
    [ 2.500,  3.750) = 192106 
    [ 3.750,  5.000) = 4341 
    [ 5.000,  6.250) = 418 
    [ 6.250,  7.500) = 68 
    [ 7.500,  8.750) = 71 
    [ 8.750, 10.000) = 85 
    [10.000, 11.250) = 66 
    [11.250, 12.500) = 106 
    [12.500, 13.750) = 67 
    [13.750, 15.000) = 47 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.652 ms/op
     p(50.0000) =      2.638 ms/op
     p(90.0000) =      3.121 ms/op
     p(95.0000) =      3.260 ms/op
     p(99.0000) =      3.936 ms/op
     p(99.9000) =      8.749 ms/op
     p(99.9900) =     13.943 ms/op
     p(99.9990) =     14.775 ms/op
     p(99.9999) =     14.877 ms/op
    p(100.0000) =     14.877 ms/op


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
# Warmup Iteration   1: 3.740 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.533 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.487 ±(99.9%) 0.005 ms/op
Iteration   1: 2.453 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.933 ms/op
                 existUser·p0.50:   2.544 ms/op
                 existUser·p0.90:   2.982 ms/op
                 existUser·p0.95:   3.080 ms/op
                 existUser·p0.99:   3.469 ms/op
                 existUser·p0.999:  5.557 ms/op
                 existUser·p0.9999: 13.795 ms/op
                 existUser·p1.00:   14.385 ms/op

Iteration   2: 2.482 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.081 ms/op
                 existUser·p0.50:   2.535 ms/op
                 existUser·p0.90:   3.027 ms/op
                 existUser·p0.95:   3.142 ms/op
                 existUser·p0.99:   3.699 ms/op
                 existUser·p0.999:  8.159 ms/op
                 existUser·p0.9999: 13.648 ms/op
                 existUser·p1.00:   14.107 ms/op

Iteration   3: 2.489 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.874 ms/op
                 existUser·p0.50:   2.535 ms/op
                 existUser·p0.90:   3.035 ms/op
                 existUser·p0.95:   3.166 ms/op
                 existUser·p0.99:   3.858 ms/op
                 existUser·p0.999:  8.595 ms/op
                 existUser·p0.9999: 12.607 ms/op
                 existUser·p1.00:   13.042 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 387501
  mean =      2.475 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 41 
    [ 1.250,  2.500) = 190425 
    [ 2.500,  3.750) = 193633 
    [ 3.750,  5.000) = 2547 
    [ 5.000,  6.250) = 433 
    [ 6.250,  7.500) = 64 
    [ 7.500,  8.750) = 18 
    [ 8.750, 10.000) = 56 
    [10.000, 11.250) = 37 
    [11.250, 12.500) = 97 
    [12.500, 13.750) = 124 
    [13.750, 15.000) = 26 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.874 ms/op
     p(50.0000) =      2.540 ms/op
     p(90.0000) =      3.015 ms/op
     p(95.0000) =      3.129 ms/op
     p(99.0000) =      3.678 ms/op
     p(99.9000) =      6.631 ms/op
     p(99.9900) =     13.631 ms/op
     p(99.9990) =     14.109 ms/op
     p(99.9999) =     14.385 ms/op
    p(100.0000) =     14.385 ms/op


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
# Warmup Iteration   1: 4.053 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.514 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.502 ±(99.9%) 0.006 ms/op
Iteration   1: 2.469 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.868 ms/op
                 getUser·p0.50:   2.494 ms/op
                 getUser·p0.90:   3.002 ms/op
                 getUser·p0.95:   3.138 ms/op
                 getUser·p0.99:   3.748 ms/op
                 getUser·p0.999:  7.090 ms/op
                 getUser·p0.9999: 13.656 ms/op
                 getUser·p1.00:   14.369 ms/op

Iteration   2: 2.476 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.880 ms/op
                 getUser·p0.50:   2.486 ms/op
                 getUser·p0.90:   3.027 ms/op
                 getUser·p0.95:   3.162 ms/op
                 getUser·p0.99:   3.715 ms/op
                 getUser·p0.999:  7.375 ms/op
                 getUser·p0.9999: 13.844 ms/op
                 getUser·p1.00:   14.565 ms/op

Iteration   3: 2.504 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.860 ms/op
                 getUser·p0.50:   2.531 ms/op
                 getUser·p0.90:   3.039 ms/op
                 getUser·p0.95:   3.203 ms/op
                 getUser·p0.99:   4.719 ms/op
                 getUser·p0.999:  8.048 ms/op
                 getUser·p0.9999: 10.418 ms/op
                 getUser·p1.00:   11.223 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 386271
  mean =      2.483 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 53 
    [ 1.250,  2.500) = 192904 
    [ 2.500,  3.750) = 188261 
    [ 3.750,  5.000) = 3467 
    [ 5.000,  6.250) = 1168 
    [ 6.250,  7.500) = 34 
    [ 7.500,  8.750) = 8 
    [ 8.750, 10.000) = 72 
    [10.000, 11.250) = 119 
    [11.250, 12.500) = 59 
    [12.500, 13.750) = 93 
    [13.750, 15.000) = 33 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.860 ms/op
     p(50.0000) =      2.503 ms/op
     p(90.0000) =      3.023 ms/op
     p(95.0000) =      3.166 ms/op
     p(99.0000) =      3.936 ms/op
     p(99.9000) =      7.200 ms/op
     p(99.9900) =     13.463 ms/op
     p(99.9990) =     14.380 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.989 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.152 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.100 ±(99.9%) 0.009 ms/op
Iteration   1: 3.079 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.950 ms/op
                 listUser·p0.50:   3.011 ms/op
                 listUser·p0.90:   3.973 ms/op
                 listUser·p0.95:   4.489 ms/op
                 listUser·p0.99:   5.857 ms/op
                 listUser·p0.999:  9.364 ms/op
                 listUser·p0.9999: 10.959 ms/op
                 listUser·p1.00:   11.600 ms/op

Iteration   2: 3.090 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.822 ms/op
                 listUser·p0.50:   3.023 ms/op
                 listUser·p0.90:   4.030 ms/op
                 listUser·p0.95:   4.530 ms/op
                 listUser·p0.99:   5.718 ms/op
                 listUser·p0.999:  9.404 ms/op
                 listUser·p0.9999: 13.165 ms/op
                 listUser·p1.00:   14.860 ms/op

Iteration   3: 3.090 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.636 ms/op
                 listUser·p0.50:   3.019 ms/op
                 listUser·p0.90:   4.022 ms/op
                 listUser·p0.95:   4.588 ms/op
                 listUser·p0.99:   5.833 ms/op
                 listUser·p0.999:  10.174 ms/op
                 listUser·p0.9999: 12.697 ms/op
                 listUser·p1.00:   13.648 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 310744
  mean =      3.087 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 123 
    [ 1.250,  2.500) = 79660 
    [ 2.500,  3.750) = 185957 
    [ 3.750,  5.000) = 36169 
    [ 5.000,  6.250) = 6986 
    [ 6.250,  7.500) = 1131 
    [ 7.500,  8.750) = 224 
    [ 8.750, 10.000) = 209 
    [10.000, 11.250) = 205 
    [11.250, 12.500) = 56 
    [12.500, 13.750) = 20 
    [13.750, 15.000) = 4 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.636 ms/op
     p(50.0000) =      3.019 ms/op
     p(90.0000) =      4.010 ms/op
     p(95.0000) =      4.530 ms/op
     p(99.0000) =      5.796 ms/op
     p(99.9000) =      9.851 ms/op
     p(99.9900) =     12.173 ms/op
     p(99.9990) =     13.950 ms/op
     p(99.9999) =     14.860 ms/op
    p(100.0000) =     14.860 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.444 ± 1.369  ops/ms
ClientPb.existUser                       thrpt       3  12.908 ± 3.474  ops/ms
ClientPb.getUser                         thrpt       3  12.689 ± 1.559  ops/ms
ClientPb.listUser                        thrpt       3  10.406 ± 1.874  ops/ms
ClientPb.createUser                       avgt       3   2.608 ± 0.182   ms/op
ClientPb.existUser                        avgt       3   2.483 ± 0.056   ms/op
ClientPb.getUser                          avgt       3   2.524 ± 0.308   ms/op
ClientPb.listUser                         avgt       3   3.064 ± 0.102   ms/op
ClientPb.createUser                     sample  372959   2.571 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.652           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.638           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.121           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.260           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.936           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.749           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.943           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.877           ms/op
ClientPb.existUser                      sample  387501   2.475 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.874           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.540           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.015           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.129           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.678           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.631           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.631           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.385           ms/op
ClientPb.getUser                        sample  386271   2.483 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.860           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.503           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.023           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.166           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.936           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.200           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.463           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.565           ms/op
ClientPb.listUser                       sample  310744   3.087 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.636           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.019           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.010           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.530           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.796           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.851           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.173           ms/op
ClientPb.listUser:listUser·p1.00        sample          14.860           ms/op
