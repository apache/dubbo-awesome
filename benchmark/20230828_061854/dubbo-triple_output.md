# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.829 ops/ms
# Warmup Iteration   2: 4.567 ops/ms
# Warmup Iteration   3: 8.010 ops/ms
Iteration   1: 8.454 ops/ms
Iteration   2: 9.212 ops/ms
Iteration   3: 9.536 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.067 ±(99.9%) 10.128 ops/ms [Average]
  (min, avg, max) = (8.454, 9.067, 9.536), stdev = 0.555
  CI (99.9%): [≈ 0, 19.195] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:11
# Fork: 1 of 1
# Warmup Iteration   1: 3.651 ops/ms
# Warmup Iteration   2: 9.045 ops/ms
# Warmup Iteration   3: 9.868 ops/ms
Iteration   1: 10.123 ops/ms
Iteration   2: 9.820 ops/ms
Iteration   3: 9.512 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.818 ±(99.9%) 5.574 ops/ms [Average]
  (min, avg, max) = (9.512, 9.818, 10.123), stdev = 0.306
  CI (99.9%): [4.244, 15.392] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 2.766 ops/ms
# Warmup Iteration   2: 8.226 ops/ms
# Warmup Iteration   3: 9.291 ops/ms
Iteration   1: 9.487 ops/ms
Iteration   2: 9.576 ops/ms
Iteration   3: 9.890 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.651 ±(99.9%) 3.860 ops/ms [Average]
  (min, avg, max) = (9.487, 9.651, 9.890), stdev = 0.212
  CI (99.9%): [5.791, 13.510] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 3.042 ops/ms
# Warmup Iteration   2: 7.538 ops/ms
# Warmup Iteration   3: 8.043 ops/ms
Iteration   1: 7.885 ops/ms
Iteration   2: 8.151 ops/ms
Iteration   3: 8.239 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.092 ±(99.9%) 3.369 ops/ms [Average]
  (min, avg, max) = (7.885, 8.092, 8.239), stdev = 0.185
  CI (99.9%): [4.723, 11.460] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 9.709 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.845 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.580 ±(99.9%) 0.003 ms/op
Iteration   1: 3.336 ±(99.9%) 0.005 ms/op
Iteration   2: 3.407 ±(99.9%) 0.006 ms/op
Iteration   3: 3.251 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.332 ±(99.9%) 1.425 ms/op [Average]
  (min, avg, max) = (3.251, 3.332, 3.407), stdev = 0.078
  CI (99.9%): [1.907, 4.756] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 7.001 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.488 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.279 ±(99.9%) 0.004 ms/op
Iteration   1: 3.110 ±(99.9%) 0.005 ms/op
Iteration   2: 3.127 ±(99.9%) 0.007 ms/op
Iteration   3: 3.111 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.116 ±(99.9%) 0.179 ms/op [Average]
  (min, avg, max) = (3.110, 3.116, 3.127), stdev = 0.010
  CI (99.9%): [2.937, 3.295] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 8.272 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.597 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.446 ±(99.9%) 0.003 ms/op
Iteration   1: 3.290 ±(99.9%) 0.005 ms/op
Iteration   2: 3.273 ±(99.9%) 0.003 ms/op
Iteration   3: 3.208 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.257 ±(99.9%) 0.788 ms/op [Average]
  (min, avg, max) = (3.208, 3.257, 3.290), stdev = 0.043
  CI (99.9%): [2.469, 4.045] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 10.040 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 4.177 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.919 ±(99.9%) 0.004 ms/op
Iteration   1: 3.835 ±(99.9%) 0.008 ms/op
Iteration   2: 3.833 ±(99.9%) 0.008 ms/op
Iteration   3: 3.804 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.824 ±(99.9%) 0.310 ms/op [Average]
  (min, avg, max) = (3.804, 3.824, 3.835), stdev = 0.017
  CI (99.9%): [3.514, 4.135] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 8.838 ±(99.9%) 0.108 ms/op
# Warmup Iteration   2: 3.720 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.344 ±(99.9%) 0.009 ms/op
Iteration   1: 3.375 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.048 ms/op
                 createUser·p0.50:   3.293 ms/op
                 createUser·p0.90:   3.723 ms/op
                 createUser·p0.95:   4.252 ms/op
                 createUser·p0.99:   6.513 ms/op
                 createUser·p0.999:  17.189 ms/op
                 createUser·p0.9999: 26.214 ms/op
                 createUser·p1.00:   28.115 ms/op

Iteration   2: 3.364 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.775 ms/op
                 createUser·p0.50:   3.260 ms/op
                 createUser·p0.90:   3.863 ms/op
                 createUser·p0.95:   4.268 ms/op
                 createUser·p0.99:   6.185 ms/op
                 createUser·p0.999:  19.562 ms/op
                 createUser·p0.9999: 22.527 ms/op
                 createUser·p1.00:   23.003 ms/op

Iteration   3: 3.330 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.298 ms/op
                 createUser·p0.50:   3.273 ms/op
                 createUser·p0.90:   3.707 ms/op
                 createUser·p0.95:   4.157 ms/op
                 createUser·p0.99:   6.095 ms/op
                 createUser·p0.999:  20.285 ms/op
                 createUser·p0.9999: 24.950 ms/op
                 createUser·p1.00:   25.657 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 285895
  mean =      3.356 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22058 
    [ 2.500,  5.000) = 255071 
    [ 5.000,  7.500) = 7185 
    [ 7.500, 10.000) = 948 
    [10.000, 12.500) = 301 
    [12.500, 15.000) = 25 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 34 
    [20.000, 22.500) = 138 
    [22.500, 25.000) = 86 
    [25.000, 27.500) = 25 

  Percentiles, ms/op:
      p(0.0000) =      0.298 ms/op
     p(50.0000) =      3.277 ms/op
     p(90.0000) =      3.768 ms/op
     p(95.0000) =      4.243 ms/op
     p(99.0000) =      6.267 ms/op
     p(99.9000) =     18.091 ms/op
     p(99.9900) =     25.035 ms/op
     p(99.9990) =     27.886 ms/op
     p(99.9999) =     28.115 ms/op
    p(100.0000) =     28.115 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.726 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 3.450 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.326 ±(99.9%) 0.009 ms/op
Iteration   1: 3.145 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.124 ms/op
                 existUser·p0.50:   3.056 ms/op
                 existUser·p0.90:   3.498 ms/op
                 existUser·p0.95:   3.858 ms/op
                 existUser·p0.99:   5.423 ms/op
                 existUser·p0.999:  10.027 ms/op
                 existUser·p0.9999: 25.941 ms/op
                 existUser·p1.00:   26.608 ms/op

Iteration   2: 3.284 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.483 ms/op
                 existUser·p0.50:   3.174 ms/op
                 existUser·p0.90:   3.748 ms/op
                 existUser·p0.95:   4.116 ms/op
                 existUser·p0.99:   5.923 ms/op
                 existUser·p0.999:  11.731 ms/op
                 existUser·p0.9999: 29.139 ms/op
                 existUser·p1.00:   30.704 ms/op

Iteration   3: 3.504 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   1.358 ms/op
                 existUser·p0.50:   3.154 ms/op
                 existUser·p0.90:   4.334 ms/op
                 existUser·p0.95:   6.005 ms/op
                 existUser·p0.99:   9.503 ms/op
                 existUser·p0.999:  17.752 ms/op
                 existUser·p0.9999: 39.313 ms/op
                 existUser·p1.00:   40.108 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 290338
  mean =      3.304 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 278860 
    [ 5.000, 10.000) = 10473 
    [10.000, 15.000) = 677 
    [15.000, 20.000) = 113 
    [20.000, 25.000) = 134 
    [25.000, 30.000) = 46 
    [30.000, 35.000) = 3 
    [35.000, 40.000) = 29 
    [40.000, 45.000) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.124 ms/op
     p(50.0000) =      3.133 ms/op
     p(90.0000) =      3.756 ms/op
     p(95.0000) =      4.383 ms/op
     p(99.0000) =      7.692 ms/op
     p(99.9000) =     17.520 ms/op
     p(99.9900) =     37.747 ms/op
     p(99.9990) =     40.049 ms/op
     p(99.9999) =     40.108 ms/op
    p(100.0000) =     40.108 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 8.070 ±(99.9%) 0.094 ms/op
# Warmup Iteration   2: 3.638 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.481 ±(99.9%) 0.013 ms/op
Iteration   1: 3.378 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.444 ms/op
                 getUser·p0.50:   3.244 ms/op
                 getUser·p0.90:   3.842 ms/op
                 getUser·p0.95:   4.383 ms/op
                 getUser·p0.99:   6.799 ms/op
                 getUser·p0.999:  16.636 ms/op
                 getUser·p0.9999: 20.530 ms/op
                 getUser·p1.00:   21.725 ms/op

Iteration   2: 3.212 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.544 ms/op
                 getUser·p0.50:   3.117 ms/op
                 getUser·p0.90:   3.523 ms/op
                 getUser·p0.95:   3.768 ms/op
                 getUser·p0.99:   5.562 ms/op
                 getUser·p0.999:  14.311 ms/op
                 getUser·p0.9999: 27.100 ms/op
                 getUser·p1.00:   28.410 ms/op

Iteration   3: 3.257 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   2.085 ms/op
                 getUser·p0.50:   3.101 ms/op
                 getUser·p0.90:   3.486 ms/op
                 getUser·p0.95:   3.854 ms/op
                 getUser·p0.99:   6.742 ms/op
                 getUser·p0.999:  12.970 ms/op
                 getUser·p0.9999: 25.774 ms/op
                 getUser·p1.00:   26.444 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 292409
  mean =      3.281 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10644 
    [ 2.500,  5.000) = 273730 
    [ 5.000,  7.500) = 6425 
    [ 7.500, 10.000) = 975 
    [10.000, 12.500) = 294 
    [12.500, 15.000) = 38 
    [15.000, 17.500) = 47 
    [17.500, 20.000) = 110 
    [20.000, 22.500) = 40 
    [22.500, 25.000) = 59 
    [25.000, 27.500) = 43 

  Percentiles, ms/op:
      p(0.0000) =      1.444 ms/op
     p(50.0000) =      3.150 ms/op
     p(90.0000) =      3.645 ms/op
     p(95.0000) =      4.039 ms/op
     p(99.0000) =      6.537 ms/op
     p(99.9000) =     15.909 ms/op
     p(99.9900) =     26.542 ms/op
     p(99.9990) =     27.994 ms/op
     p(99.9999) =     28.410 ms/op
    p(100.0000) =     28.410 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 9.458 ±(99.9%) 0.127 ms/op
# Warmup Iteration   2: 4.276 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.017 ±(99.9%) 0.013 ms/op
Iteration   1: 3.882 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.321 ms/op
                 listUser·p0.50:   3.740 ms/op
                 listUser·p0.90:   4.162 ms/op
                 listUser·p0.95:   4.489 ms/op
                 listUser·p0.99:   7.504 ms/op
                 listUser·p0.999:  15.745 ms/op
                 listUser·p0.9999: 22.446 ms/op
                 listUser·p1.00:   24.543 ms/op

Iteration   2: 3.942 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.150 ms/op
                 listUser·p0.50:   3.805 ms/op
                 listUser·p0.90:   4.284 ms/op
                 listUser·p0.95:   4.579 ms/op
                 listUser·p0.99:   7.858 ms/op
                 listUser·p0.999:  14.582 ms/op
                 listUser·p0.9999: 17.220 ms/op
                 listUser·p1.00:   18.383 ms/op

Iteration   3: 3.849 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.882 ms/op
                 listUser·p0.50:   3.752 ms/op
                 listUser·p0.90:   4.153 ms/op
                 listUser·p0.95:   4.661 ms/op
                 listUser·p0.99:   7.324 ms/op
                 listUser·p0.999:  15.270 ms/op
                 listUser·p0.9999: 17.138 ms/op
                 listUser·p1.00:   19.137 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 246663
  mean =      3.890 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 90 
    [ 2.500,  5.000) = 237495 
    [ 5.000,  7.500) = 6563 
    [ 7.500, 10.000) = 1553 
    [10.000, 12.500) = 520 
    [12.500, 15.000) = 177 
    [15.000, 17.500) = 194 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.321 ms/op
     p(50.0000) =      3.764 ms/op
     p(90.0000) =      4.219 ms/op
     p(95.0000) =      4.579 ms/op
     p(99.0000) =      7.589 ms/op
     p(99.9000) =     15.226 ms/op
     p(99.9900) =     21.791 ms/op
     p(99.9990) =     23.991 ms/op
     p(99.9999) =     24.543 ms/op
    p(100.0000) =     24.543 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score    Error   Units
ClientPb.createUser                      thrpt       3   9.067 ± 10.128  ops/ms
ClientPb.existUser                       thrpt       3   9.818 ±  5.574  ops/ms
ClientPb.getUser                         thrpt       3   9.651 ±  3.860  ops/ms
ClientPb.listUser                        thrpt       3   8.092 ±  3.369  ops/ms
ClientPb.createUser                       avgt       3   3.332 ±  1.425   ms/op
ClientPb.existUser                        avgt       3   3.116 ±  0.179   ms/op
ClientPb.getUser                          avgt       3   3.257 ±  0.788   ms/op
ClientPb.listUser                         avgt       3   3.824 ±  0.310   ms/op
ClientPb.createUser                     sample  285895   3.356 ±  0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.298            ms/op
ClientPb.createUser:createUser·p0.50    sample           3.277            ms/op
ClientPb.createUser:createUser·p0.90    sample           3.768            ms/op
ClientPb.createUser:createUser·p0.95    sample           4.243            ms/op
ClientPb.createUser:createUser·p0.99    sample           6.267            ms/op
ClientPb.createUser:createUser·p0.999   sample          18.091            ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.035            ms/op
ClientPb.createUser:createUser·p1.00    sample          28.115            ms/op
ClientPb.existUser                      sample  290338   3.304 ±  0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.124            ms/op
ClientPb.existUser:existUser·p0.50      sample           3.133            ms/op
ClientPb.existUser:existUser·p0.90      sample           3.756            ms/op
ClientPb.existUser:existUser·p0.95      sample           4.383            ms/op
ClientPb.existUser:existUser·p0.99      sample           7.692            ms/op
ClientPb.existUser:existUser·p0.999     sample          17.520            ms/op
ClientPb.existUser:existUser·p0.9999    sample          37.747            ms/op
ClientPb.existUser:existUser·p1.00      sample          40.108            ms/op
ClientPb.getUser                        sample  292409   3.281 ±  0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.444            ms/op
ClientPb.getUser:getUser·p0.50          sample           3.150            ms/op
ClientPb.getUser:getUser·p0.90          sample           3.645            ms/op
ClientPb.getUser:getUser·p0.95          sample           4.039            ms/op
ClientPb.getUser:getUser·p0.99          sample           6.537            ms/op
ClientPb.getUser:getUser·p0.999         sample          15.909            ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.542            ms/op
ClientPb.getUser:getUser·p1.00          sample          28.410            ms/op
ClientPb.listUser                       sample  246663   3.890 ±  0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.321            ms/op
ClientPb.listUser:listUser·p0.50        sample           3.764            ms/op
ClientPb.listUser:listUser·p0.90        sample           4.219            ms/op
ClientPb.listUser:listUser·p0.95        sample           4.579            ms/op
ClientPb.listUser:listUser·p0.99        sample           7.589            ms/op
ClientPb.listUser:listUser·p0.999       sample          15.226            ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.791            ms/op
ClientPb.listUser:listUser·p1.00        sample          24.543            ms/op
