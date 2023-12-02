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
# Warmup Iteration   1: 4.852 ops/ms
# Warmup Iteration   2: 11.973 ops/ms
# Warmup Iteration   3: 12.341 ops/ms
Iteration   1: 12.593 ops/ms
Iteration   2: 12.673 ops/ms
Iteration   3: 12.769 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.678 ±(99.9%) 1.604 ops/ms [Average]
  (min, avg, max) = (12.593, 12.678, 12.769), stdev = 0.088
  CI (99.9%): [11.074, 14.282] (assumes normal distribution)


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
# Warmup Iteration   1: 8.497 ops/ms
# Warmup Iteration   2: 12.958 ops/ms
# Warmup Iteration   3: 12.811 ops/ms
Iteration   1: 12.991 ops/ms
Iteration   2: 12.946 ops/ms
Iteration   3: 13.082 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.006 ±(99.9%) 1.257 ops/ms [Average]
  (min, avg, max) = (12.946, 13.006, 13.082), stdev = 0.069
  CI (99.9%): [11.749, 14.264] (assumes normal distribution)


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
# Warmup Iteration   1: 7.231 ops/ms
# Warmup Iteration   2: 12.593 ops/ms
# Warmup Iteration   3: 12.651 ops/ms
Iteration   1: 12.718 ops/ms
Iteration   2: 12.784 ops/ms
Iteration   3: 12.718 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.740 ±(99.9%) 0.692 ops/ms [Average]
  (min, avg, max) = (12.718, 12.740, 12.784), stdev = 0.038
  CI (99.9%): [12.048, 13.431] (assumes normal distribution)


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
# Warmup Iteration   1: 6.527 ops/ms
# Warmup Iteration   2: 10.246 ops/ms
# Warmup Iteration   3: 10.282 ops/ms
Iteration   1: 10.210 ops/ms
Iteration   2: 10.330 ops/ms
Iteration   3: 10.503 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.348 ±(99.9%) 2.685 ops/ms [Average]
  (min, avg, max) = (10.210, 10.348, 10.503), stdev = 0.147
  CI (99.9%): [7.662, 13.033] (assumes normal distribution)


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
# Warmup Iteration   1: 4.293 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 2.628 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.545 ±(99.9%) 0.004 ms/op
Iteration   1: 2.535 ±(99.9%) 0.004 ms/op
Iteration   2: 2.545 ±(99.9%) 0.004 ms/op
Iteration   3: 2.536 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.538 ±(99.9%) 0.107 ms/op [Average]
  (min, avg, max) = (2.535, 2.538, 2.545), stdev = 0.006
  CI (99.9%): [2.432, 2.645] (assumes normal distribution)


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
# Warmup Iteration   1: 3.739 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.478 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.500 ±(99.9%) 0.004 ms/op
Iteration   1: 2.454 ±(99.9%) 0.005 ms/op
Iteration   2: 2.459 ±(99.9%) 0.004 ms/op
Iteration   3: 2.470 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.461 ±(99.9%) 0.148 ms/op [Average]
  (min, avg, max) = (2.454, 2.461, 2.470), stdev = 0.008
  CI (99.9%): [2.313, 2.609] (assumes normal distribution)


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
# Warmup Iteration   1: 3.784 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.595 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.528 ±(99.9%) 0.004 ms/op
Iteration   1: 2.504 ±(99.9%) 0.003 ms/op
Iteration   2: 2.508 ±(99.9%) 0.005 ms/op
Iteration   3: 2.504 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.505 ±(99.9%) 0.042 ms/op [Average]
  (min, avg, max) = (2.504, 2.505, 2.508), stdev = 0.002
  CI (99.9%): [2.463, 2.547] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:23
# Fork: 1 of 1
# Warmup Iteration   1: 4.619 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.029 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.993 ±(99.9%) 0.005 ms/op
Iteration   1: 2.983 ±(99.9%) 0.004 ms/op
Iteration   2: 3.012 ±(99.9%) 0.005 ms/op
Iteration   3: 2.996 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.997 ±(99.9%) 0.270 ms/op [Average]
  (min, avg, max) = (2.983, 2.997, 3.012), stdev = 0.015
  CI (99.9%): [2.727, 3.267] (assumes normal distribution)


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
# Warmup Iteration   1: 4.312 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.701 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.569 ±(99.9%) 0.006 ms/op
Iteration   1: 2.560 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.046 ms/op
                 createUser·p0.50:   2.617 ms/op
                 createUser·p0.90:   3.109 ms/op
                 createUser·p0.95:   3.236 ms/op
                 createUser·p0.99:   3.854 ms/op
                 createUser·p0.999:  11.207 ms/op
                 createUser·p0.9999: 14.025 ms/op
                 createUser·p1.00:   14.647 ms/op

Iteration   2: 2.569 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.731 ms/op
                 createUser·p0.50:   2.597 ms/op
                 createUser·p0.90:   3.133 ms/op
                 createUser·p0.95:   3.273 ms/op
                 createUser·p0.99:   3.994 ms/op
                 createUser·p0.999:  9.683 ms/op
                 createUser·p0.9999: 16.941 ms/op
                 createUser·p1.00:   17.138 ms/op

Iteration   3: 2.563 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.955 ms/op
                 createUser·p0.50:   2.642 ms/op
                 createUser·p0.90:   3.109 ms/op
                 createUser·p0.95:   3.260 ms/op
                 createUser·p0.99:   4.530 ms/op
                 createUser·p0.999:  8.290 ms/op
                 createUser·p0.9999: 12.425 ms/op
                 createUser·p1.00:   13.206 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 374002
  mean =      2.564 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 52 
    [ 1.250,  2.500) = 177262 
    [ 2.500,  3.750) = 190899 
    [ 3.750,  5.000) = 4663 
    [ 5.000,  6.250) = 691 
    [ 6.250,  7.500) = 38 
    [ 7.500,  8.750) = 38 
    [ 8.750, 10.000) = 71 
    [10.000, 11.250) = 63 
    [11.250, 12.500) = 93 
    [12.500, 13.750) = 79 
    [13.750, 15.000) = 21 
    [15.000, 16.250) = 14 
    [16.250, 17.500) = 18 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.731 ms/op
     p(50.0000) =      2.617 ms/op
     p(90.0000) =      3.117 ms/op
     p(95.0000) =      3.256 ms/op
     p(99.0000) =      4.063 ms/op
     p(99.9000) =      8.339 ms/op
     p(99.9900) =     14.149 ms/op
     p(99.9990) =     17.056 ms/op
     p(99.9999) =     17.138 ms/op
    p(100.0000) =     17.138 ms/op


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
# Warmup Iteration   1: 3.608 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 2.518 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.473 ±(99.9%) 0.005 ms/op
Iteration   1: 2.494 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.924 ms/op
                 existUser·p0.50:   2.527 ms/op
                 existUser·p0.90:   3.031 ms/op
                 existUser·p0.95:   3.166 ms/op
                 existUser·p0.99:   3.891 ms/op
                 existUser·p0.999:  11.432 ms/op
                 existUser·p0.9999: 21.338 ms/op
                 existUser·p1.00:   21.725 ms/op

Iteration   2: 2.510 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.094 ms/op
                 existUser·p0.50:   2.585 ms/op
                 existUser·p0.90:   3.035 ms/op
                 existUser·p0.95:   3.162 ms/op
                 existUser·p0.99:   4.194 ms/op
                 existUser·p0.999:  9.393 ms/op
                 existUser·p0.9999: 12.993 ms/op
                 existUser·p1.00:   14.025 ms/op

Iteration   3: 2.486 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.966 ms/op
                 existUser·p0.50:   2.548 ms/op
                 existUser·p0.90:   3.019 ms/op
                 existUser·p0.95:   3.125 ms/op
                 existUser·p0.99:   3.645 ms/op
                 existUser·p0.999:  6.118 ms/op
                 existUser·p0.9999: 11.373 ms/op
                 existUser·p1.00:   12.370 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 384144
  mean =      2.497 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 188216 
    [ 2.500,  5.000) = 194879 
    [ 5.000,  7.500) = 681 
    [ 7.500, 10.000) = 85 
    [10.000, 12.500) = 157 
    [12.500, 15.000) = 94 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.924 ms/op
     p(50.0000) =      2.552 ms/op
     p(90.0000) =      3.031 ms/op
     p(95.0000) =      3.146 ms/op
     p(99.0000) =      3.891 ms/op
     p(99.9000) =      6.750 ms/op
     p(99.9900) =     13.812 ms/op
     p(99.9990) =     21.599 ms/op
     p(99.9999) =     21.725 ms/op
    p(100.0000) =     21.725 ms/op


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
# Warmup Iteration   1: 4.061 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.594 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.542 ±(99.9%) 0.006 ms/op
Iteration   1: 2.516 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.908 ms/op
                 getUser·p0.50:   2.540 ms/op
                 getUser·p0.90:   3.076 ms/op
                 getUser·p0.95:   3.219 ms/op
                 getUser·p0.99:   3.985 ms/op
                 getUser·p0.999:  11.644 ms/op
                 getUser·p0.9999: 13.456 ms/op
                 getUser·p1.00:   14.090 ms/op

Iteration   2: 2.501 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.932 ms/op
                 getUser·p0.50:   2.531 ms/op
                 getUser·p0.90:   3.056 ms/op
                 getUser·p0.95:   3.174 ms/op
                 getUser·p0.99:   3.777 ms/op
                 getUser·p0.999:  10.179 ms/op
                 getUser·p0.9999: 12.131 ms/op
                 getUser·p1.00:   12.435 ms/op

Iteration   3: 2.519 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.941 ms/op
                 getUser·p0.50:   2.544 ms/op
                 getUser·p0.90:   3.080 ms/op
                 getUser·p0.95:   3.224 ms/op
                 getUser·p0.99:   3.846 ms/op
                 getUser·p0.999:  8.586 ms/op
                 getUser·p0.9999: 11.534 ms/op
                 getUser·p1.00:   11.764 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 381893
  mean =      2.512 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 51 
    [ 1.250,  2.500) = 187826 
    [ 2.500,  3.750) = 189256 
    [ 3.750,  5.000) = 3834 
    [ 5.000,  6.250) = 487 
    [ 6.250,  7.500) = 27 
    [ 7.500,  8.750) = 31 
    [ 8.750, 10.000) = 82 
    [10.000, 11.250) = 110 
    [11.250, 12.500) = 105 
    [12.500, 13.750) = 81 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.908 ms/op
     p(50.0000) =      2.540 ms/op
     p(90.0000) =      3.068 ms/op
     p(95.0000) =      3.207 ms/op
     p(99.0000) =      3.858 ms/op
     p(99.9000) =      8.751 ms/op
     p(99.9900) =     13.167 ms/op
     p(99.9990) =     13.779 ms/op
     p(99.9999) =     14.090 ms/op
    p(100.0000) =     14.090 ms/op


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
# Warmup Iteration   1: 4.661 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.106 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.039 ±(99.9%) 0.009 ms/op
Iteration   1: 3.032 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.949 ms/op
                 listUser·p0.50:   2.974 ms/op
                 listUser·p0.90:   3.924 ms/op
                 listUser·p0.95:   4.424 ms/op
                 listUser·p0.99:   5.718 ms/op
                 listUser·p0.999:  9.708 ms/op
                 listUser·p0.9999: 11.922 ms/op
                 listUser·p1.00:   12.861 ms/op

Iteration   2: 3.011 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.906 ms/op
                 listUser·p0.50:   2.941 ms/op
                 listUser·p0.90:   3.908 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   5.652 ms/op
                 listUser·p0.999:  10.568 ms/op
                 listUser·p0.9999: 12.956 ms/op
                 listUser·p1.00:   13.533 ms/op

Iteration   3: 3.012 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.744 ms/op
                 listUser·p0.50:   2.945 ms/op
                 listUser·p0.90:   3.883 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   5.603 ms/op
                 listUser·p0.999:  9.549 ms/op
                 listUser·p0.9999: 10.721 ms/op
                 listUser·p1.00:   11.698 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 317752
  mean =      3.018 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 128 
    [ 1.250,  2.500) = 92002 
    [ 2.500,  3.750) = 185381 
    [ 3.750,  5.000) = 32580 
    [ 5.000,  6.250) = 6128 
    [ 6.250,  7.500) = 892 
    [ 7.500,  8.750) = 157 
    [ 8.750, 10.000) = 164 
    [10.000, 11.250) = 239 
    [11.250, 12.500) = 68 
    [12.500, 13.750) = 13 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.744 ms/op
     p(50.0000) =      2.953 ms/op
     p(90.0000) =      3.908 ms/op
     p(95.0000) =      4.407 ms/op
     p(99.0000) =      5.652 ms/op
     p(99.9000) =     10.031 ms/op
     p(99.9900) =     12.190 ms/op
     p(99.9990) =     13.465 ms/op
     p(99.9999) =     13.533 ms/op
    p(100.0000) =     13.533 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.678 ± 1.604  ops/ms
ClientPb.existUser                       thrpt       3  13.006 ± 1.257  ops/ms
ClientPb.getUser                         thrpt       3  12.740 ± 0.692  ops/ms
ClientPb.listUser                        thrpt       3  10.348 ± 2.685  ops/ms
ClientPb.createUser                       avgt       3   2.538 ± 0.107   ms/op
ClientPb.existUser                        avgt       3   2.461 ± 0.148   ms/op
ClientPb.getUser                          avgt       3   2.505 ± 0.042   ms/op
ClientPb.listUser                         avgt       3   2.997 ± 0.270   ms/op
ClientPb.createUser                     sample  374002   2.564 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.731           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.617           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.117           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.256           ms/op
ClientPb.createUser:createUser·p0.99    sample           4.063           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.339           ms/op
ClientPb.createUser:createUser·p0.9999  sample          14.149           ms/op
ClientPb.createUser:createUser·p1.00    sample          17.138           ms/op
ClientPb.existUser                      sample  384144   2.497 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.924           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.552           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.031           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.146           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.891           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.750           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.812           ms/op
ClientPb.existUser:existUser·p1.00      sample          21.725           ms/op
ClientPb.getUser                        sample  381893   2.512 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.908           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.540           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.068           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.207           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.858           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.751           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.167           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.090           ms/op
ClientPb.listUser                       sample  317752   3.018 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.744           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.953           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.908           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.407           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.652           ms/op
ClientPb.listUser:listUser·p0.999       sample          10.031           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.190           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.533           ms/op
