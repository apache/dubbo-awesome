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
# Warmup Iteration   1: 5.066 ops/ms
# Warmup Iteration   2: 12.104 ops/ms
# Warmup Iteration   3: 12.574 ops/ms
Iteration   1: 12.737 ops/ms
Iteration   2: 12.903 ops/ms
Iteration   3: 12.759 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.799 ±(99.9%) 1.643 ops/ms [Average]
  (min, avg, max) = (12.737, 12.799, 12.903), stdev = 0.090
  CI (99.9%): [11.156, 14.443] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 7.954 ops/ms
# Warmup Iteration   2: 13.313 ops/ms
# Warmup Iteration   3: 13.226 ops/ms
Iteration   1: 13.321 ops/ms
Iteration   2: 13.208 ops/ms
Iteration   3: 13.315 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.282 ±(99.9%) 1.159 ops/ms [Average]
  (min, avg, max) = (13.208, 13.282, 13.321), stdev = 0.064
  CI (99.9%): [12.123, 14.440] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 8.246 ops/ms
# Warmup Iteration   2: 12.614 ops/ms
# Warmup Iteration   3: 12.888 ops/ms
Iteration   1: 12.989 ops/ms
Iteration   2: 13.030 ops/ms
Iteration   3: 12.891 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.970 ±(99.9%) 1.304 ops/ms [Average]
  (min, avg, max) = (12.891, 12.970, 13.030), stdev = 0.071
  CI (99.9%): [11.666, 14.275] (assumes normal distribution)


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
# Warmup Iteration   1: 6.927 ops/ms
# Warmup Iteration   2: 10.806 ops/ms
# Warmup Iteration   3: 10.865 ops/ms
Iteration   1: 10.935 ops/ms
Iteration   2: 10.790 ops/ms
Iteration   3: 10.803 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.843 ±(99.9%) 1.464 ops/ms [Average]
  (min, avg, max) = (10.790, 10.843, 10.935), stdev = 0.080
  CI (99.9%): [9.378, 12.307] (assumes normal distribution)


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
# Warmup Iteration   1: 3.818 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.543 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.507 ±(99.9%) 0.002 ms/op
Iteration   1: 2.505 ±(99.9%) 0.005 ms/op
Iteration   2: 2.473 ±(99.9%) 0.003 ms/op
Iteration   3: 2.469 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.482 ±(99.9%) 0.364 ms/op [Average]
  (min, avg, max) = (2.469, 2.482, 2.505), stdev = 0.020
  CI (99.9%): [2.118, 2.846] (assumes normal distribution)


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
# Warmup Iteration   1: 3.691 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.455 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.439 ±(99.9%) 0.003 ms/op
Iteration   1: 2.445 ±(99.9%) 0.004 ms/op
Iteration   2: 2.432 ±(99.9%) 0.005 ms/op
Iteration   3: 2.410 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.429 ±(99.9%) 0.325 ms/op [Average]
  (min, avg, max) = (2.410, 2.429, 2.445), stdev = 0.018
  CI (99.9%): [2.103, 2.754] (assumes normal distribution)


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
# Warmup Iteration   1: 3.716 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.531 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.506 ±(99.9%) 0.005 ms/op
Iteration   1: 2.488 ±(99.9%) 0.003 ms/op
Iteration   2: 2.471 ±(99.9%) 0.004 ms/op
Iteration   3: 2.510 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.490 ±(99.9%) 0.359 ms/op [Average]
  (min, avg, max) = (2.471, 2.490, 2.510), stdev = 0.020
  CI (99.9%): [2.130, 2.849] (assumes normal distribution)


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
# Warmup Iteration   1: 4.618 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.015 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.959 ±(99.9%) 0.006 ms/op
Iteration   1: 2.944 ±(99.9%) 0.004 ms/op
Iteration   2: 2.931 ±(99.9%) 0.004 ms/op
Iteration   3: 2.932 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.936 ±(99.9%) 0.129 ms/op [Average]
  (min, avg, max) = (2.931, 2.936, 2.944), stdev = 0.007
  CI (99.9%): [2.807, 3.064] (assumes normal distribution)


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
# Warmup Iteration   1: 4.129 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.648 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.537 ±(99.9%) 0.005 ms/op
Iteration   1: 2.520 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.973 ms/op
                 createUser·p0.50:   2.585 ms/op
                 createUser·p0.90:   3.052 ms/op
                 createUser·p0.95:   3.154 ms/op
                 createUser·p0.99:   3.641 ms/op
                 createUser·p0.999:  11.731 ms/op
                 createUser·p0.9999: 13.445 ms/op
                 createUser·p1.00:   14.008 ms/op

Iteration   2: 2.511 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.814 ms/op
                 createUser·p0.50:   2.585 ms/op
                 createUser·p0.90:   3.043 ms/op
                 createUser·p0.95:   3.154 ms/op
                 createUser·p0.99:   3.824 ms/op
                 createUser·p0.999:  8.967 ms/op
                 createUser·p0.9999: 11.780 ms/op
                 createUser·p1.00:   12.419 ms/op

Iteration   3: 2.518 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.925 ms/op
                 createUser·p0.50:   2.621 ms/op
                 createUser·p0.90:   3.043 ms/op
                 createUser·p0.95:   3.142 ms/op
                 createUser·p0.99:   3.609 ms/op
                 createUser·p0.999:  8.357 ms/op
                 createUser·p0.9999: 11.107 ms/op
                 createUser·p1.00:   11.665 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 381122
  mean =      2.516 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 40 
    [ 1.250,  2.500) = 184830 
    [ 2.500,  3.750) = 192815 
    [ 3.750,  5.000) = 2732 
    [ 5.000,  6.250) = 242 
    [ 6.250,  7.500) = 10 
    [ 7.500,  8.750) = 62 
    [ 8.750, 10.000) = 94 
    [10.000, 11.250) = 116 
    [11.250, 12.500) = 112 
    [12.500, 13.750) = 64 
    [13.750, 15.000) = 5 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.814 ms/op
     p(50.0000) =      2.597 ms/op
     p(90.0000) =      3.047 ms/op
     p(95.0000) =      3.150 ms/op
     p(99.0000) =      3.695 ms/op
     p(99.9000) =      8.978 ms/op
     p(99.9900) =     13.058 ms/op
     p(99.9990) =     13.851 ms/op
     p(99.9999) =     14.008 ms/op
    p(100.0000) =     14.008 ms/op


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
# Warmup Iteration   1: 3.565 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 2.481 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.463 ±(99.9%) 0.006 ms/op
Iteration   1: 2.430 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.886 ms/op
                 existUser·p0.50:   2.478 ms/op
                 existUser·p0.90:   2.957 ms/op
                 existUser·p0.95:   3.064 ms/op
                 existUser·p0.99:   3.492 ms/op
                 existUser·p0.999:  6.982 ms/op
                 existUser·p0.9999: 13.844 ms/op
                 existUser·p1.00:   14.139 ms/op

Iteration   2: 2.435 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.519 ms/op
                 existUser·p0.50:   2.519 ms/op
                 existUser·p0.90:   2.961 ms/op
                 existUser·p0.95:   3.056 ms/op
                 existUser·p0.99:   3.555 ms/op
                 existUser·p0.999:  7.723 ms/op
                 existUser·p0.9999: 12.771 ms/op
                 existUser·p1.00:   13.320 ms/op

Iteration   3: 2.442 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.998 ms/op
                 existUser·p0.50:   2.499 ms/op
                 existUser·p0.90:   2.974 ms/op
                 existUser·p0.95:   3.088 ms/op
                 existUser·p0.99:   3.650 ms/op
                 existUser·p0.999:  7.998 ms/op
                 existUser·p0.9999: 11.646 ms/op
                 existUser·p1.00:   12.141 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 393703
  mean =      2.436 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 62 
    [ 1.250,  2.500) = 197070 
    [ 2.500,  3.750) = 193672 
    [ 3.750,  5.000) = 2139 
    [ 5.000,  6.250) = 338 
    [ 6.250,  7.500) = 30 
    [ 7.500,  8.750) = 16 
    [ 8.750, 10.000) = 101 
    [10.000, 11.250) = 108 
    [11.250, 12.500) = 79 
    [12.500, 13.750) = 74 
    [13.750, 15.000) = 14 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.519 ms/op
     p(50.0000) =      2.499 ms/op
     p(90.0000) =      2.961 ms/op
     p(95.0000) =      3.068 ms/op
     p(99.0000) =      3.572 ms/op
     p(99.9000) =      7.263 ms/op
     p(99.9900) =     13.177 ms/op
     p(99.9990) =     14.059 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.675 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.563 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.499 ±(99.9%) 0.006 ms/op
Iteration   1: 2.462 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.844 ms/op
                 getUser·p0.50:   2.486 ms/op
                 getUser·p0.90:   3.002 ms/op
                 getUser·p0.95:   3.133 ms/op
                 getUser·p0.99:   3.715 ms/op
                 getUser·p0.999:  7.858 ms/op
                 getUser·p0.9999: 13.963 ms/op
                 getUser·p1.00:   14.582 ms/op

Iteration   2: 2.488 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.896 ms/op
                 getUser·p0.50:   2.499 ms/op
                 getUser·p0.90:   3.035 ms/op
                 getUser·p0.95:   3.207 ms/op
                 getUser·p0.99:   4.316 ms/op
                 getUser·p0.999:  6.659 ms/op
                 getUser·p0.9999: 12.293 ms/op
                 getUser·p1.00:   12.796 ms/op

Iteration   3: 2.460 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.796 ms/op
                 getUser·p0.50:   2.470 ms/op
                 getUser·p0.90:   3.006 ms/op
                 getUser·p0.95:   3.138 ms/op
                 getUser·p0.99:   3.766 ms/op
                 getUser·p0.999:  7.638 ms/op
                 getUser·p0.9999: 11.141 ms/op
                 getUser·p1.00:   11.715 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 388362
  mean =      2.470 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 95 
    [ 1.250,  2.500) = 195884 
    [ 2.500,  3.750) = 187521 
    [ 3.750,  5.000) = 3806 
    [ 5.000,  6.250) = 640 
    [ 6.250,  7.500) = 37 
    [ 7.500,  8.750) = 34 
    [ 8.750, 10.000) = 44 
    [10.000, 11.250) = 104 
    [11.250, 12.500) = 116 
    [12.500, 13.750) = 68 
    [13.750, 15.000) = 13 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.796 ms/op
     p(50.0000) =      2.486 ms/op
     p(90.0000) =      3.015 ms/op
     p(95.0000) =      3.158 ms/op
     p(99.0000) =      3.887 ms/op
     p(99.9000) =      7.050 ms/op
     p(99.9900) =     13.183 ms/op
     p(99.9990) =     14.489 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 5.070 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.034 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.007 ±(99.9%) 0.008 ms/op
Iteration   1: 2.995 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.884 ms/op
                 listUser·p0.50:   2.933 ms/op
                 listUser·p0.90:   3.863 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   5.683 ms/op
                 listUser·p0.999:  8.998 ms/op
                 listUser·p0.9999: 10.380 ms/op
                 listUser·p1.00:   11.665 ms/op

Iteration   2: 2.981 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.925 ms/op
                 listUser·p0.50:   2.933 ms/op
                 listUser·p0.90:   3.805 ms/op
                 listUser·p0.95:   4.260 ms/op
                 listUser·p0.99:   5.428 ms/op
                 listUser·p0.999:  9.499 ms/op
                 listUser·p0.9999: 12.805 ms/op
                 listUser·p1.00:   12.993 ms/op

Iteration   3: 2.989 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.945 ms/op
                 listUser·p0.50:   2.929 ms/op
                 listUser·p0.90:   3.887 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   5.573 ms/op
                 listUser·p0.999:  9.798 ms/op
                 listUser·p0.9999: 11.605 ms/op
                 listUser·p1.00:   11.944 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 321035
  mean =      2.988 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 123 
    [ 1.250,  2.500) = 97110 
    [ 2.500,  3.750) = 186568 
    [ 3.750,  5.000) = 30458 
    [ 5.000,  6.250) = 5346 
    [ 6.250,  7.500) = 764 
    [ 7.500,  8.750) = 209 
    [ 8.750, 10.000) = 273 
    [10.000, 11.250) = 139 
    [11.250, 12.500) = 33 
    [12.500, 13.750) = 12 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.884 ms/op
     p(50.0000) =      2.933 ms/op
     p(90.0000) =      3.850 ms/op
     p(95.0000) =      4.342 ms/op
     p(99.0000) =      5.562 ms/op
     p(99.9000) =      9.256 ms/op
     p(99.9900) =     11.593 ms/op
     p(99.9990) =     12.911 ms/op
     p(99.9999) =     12.993 ms/op
    p(100.0000) =     12.993 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.799 ± 1.643  ops/ms
ClientPb.existUser                       thrpt       3  13.282 ± 1.159  ops/ms
ClientPb.getUser                         thrpt       3  12.970 ± 1.304  ops/ms
ClientPb.listUser                        thrpt       3  10.843 ± 1.464  ops/ms
ClientPb.createUser                       avgt       3   2.482 ± 0.364   ms/op
ClientPb.existUser                        avgt       3   2.429 ± 0.325   ms/op
ClientPb.getUser                          avgt       3   2.490 ± 0.359   ms/op
ClientPb.listUser                         avgt       3   2.936 ± 0.129   ms/op
ClientPb.createUser                     sample  381122   2.516 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.814           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.597           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.047           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.150           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.695           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.978           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.058           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.008           ms/op
ClientPb.existUser                      sample  393703   2.436 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.519           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.499           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.961           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.068           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.572           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.263           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.177           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.139           ms/op
ClientPb.getUser                        sample  388362   2.470 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.796           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.486           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.015           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.158           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.887           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.050           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.183           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.582           ms/op
ClientPb.listUser                       sample  321035   2.988 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.884           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.933           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.850           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.342           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.562           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.256           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.593           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.993           ms/op
