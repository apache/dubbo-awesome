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
# Warmup Iteration   1: 4.877 ops/ms
# Warmup Iteration   2: 12.204 ops/ms
# Warmup Iteration   3: 12.373 ops/ms
Iteration   1: 12.575 ops/ms
Iteration   2: 12.563 ops/ms
Iteration   3: 12.737 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.625 ±(99.9%) 1.779 ops/ms [Average]
  (min, avg, max) = (12.563, 12.625, 12.737), stdev = 0.098
  CI (99.9%): [10.846, 14.404] (assumes normal distribution)


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
# Warmup Iteration   1: 8.490 ops/ms
# Warmup Iteration   2: 13.085 ops/ms
# Warmup Iteration   3: 13.140 ops/ms
Iteration   1: 13.117 ops/ms
Iteration   2: 13.197 ops/ms
Iteration   3: 13.226 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.180 ±(99.9%) 1.027 ops/ms [Average]
  (min, avg, max) = (13.117, 13.180, 13.226), stdev = 0.056
  CI (99.9%): [12.153, 14.208] (assumes normal distribution)


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
# Warmup Iteration   1: 7.828 ops/ms
# Warmup Iteration   2: 12.587 ops/ms
# Warmup Iteration   3: 12.534 ops/ms
Iteration   1: 12.824 ops/ms
Iteration   2: 12.724 ops/ms
Iteration   3: 12.815 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.788 ±(99.9%) 1.013 ops/ms [Average]
  (min, avg, max) = (12.724, 12.788, 12.824), stdev = 0.056
  CI (99.9%): [11.775, 13.801] (assumes normal distribution)


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
# Warmup Iteration   1: 6.748 ops/ms
# Warmup Iteration   2: 10.418 ops/ms
# Warmup Iteration   3: 10.427 ops/ms
Iteration   1: 10.590 ops/ms
Iteration   2: 10.642 ops/ms
Iteration   3: 10.477 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.570 ±(99.9%) 1.541 ops/ms [Average]
  (min, avg, max) = (10.477, 10.570, 10.642), stdev = 0.084
  CI (99.9%): [9.028, 12.111] (assumes normal distribution)


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
# Warmup Iteration   1: 4.058 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 2.573 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.557 ±(99.9%) 0.005 ms/op
Iteration   1: 2.563 ±(99.9%) 0.004 ms/op
Iteration   2: 2.492 ±(99.9%) 0.004 ms/op
Iteration   3: 2.495 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.517 ±(99.9%) 0.735 ms/op [Average]
  (min, avg, max) = (2.492, 2.517, 2.563), stdev = 0.040
  CI (99.9%): [1.781, 3.252] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:32
# Fork: 1 of 1
# Warmup Iteration   1: 3.587 ±(99.9%) 0.008 ms/op
# Warmup Iteration   2: 2.440 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.434 ±(99.9%) 0.005 ms/op
Iteration   1: 2.415 ±(99.9%) 0.004 ms/op
Iteration   2: 2.430 ±(99.9%) 0.004 ms/op
Iteration   3: 2.427 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.424 ±(99.9%) 0.141 ms/op [Average]
  (min, avg, max) = (2.415, 2.424, 2.430), stdev = 0.008
  CI (99.9%): [2.283, 2.566] (assumes normal distribution)


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
# Warmup Iteration   1: 3.983 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.565 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.499 ±(99.9%) 0.004 ms/op
Iteration   1: 2.497 ±(99.9%) 0.004 ms/op
Iteration   2: 2.497 ±(99.9%) 0.004 ms/op
Iteration   3: 2.494 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.496 ±(99.9%) 0.029 ms/op [Average]
  (min, avg, max) = (2.494, 2.496, 2.497), stdev = 0.002
  CI (99.9%): [2.467, 2.525] (assumes normal distribution)


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
# Warmup Iteration   1: 4.628 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.091 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.021 ±(99.9%) 0.006 ms/op
Iteration   1: 3.045 ±(99.9%) 0.006 ms/op
Iteration   2: 3.030 ±(99.9%) 0.005 ms/op
Iteration   3: 3.042 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.039 ±(99.9%) 0.150 ms/op [Average]
  (min, avg, max) = (3.030, 3.039, 3.045), stdev = 0.008
  CI (99.9%): [2.889, 3.190] (assumes normal distribution)


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
# Warmup Iteration   1: 4.454 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 2.636 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.527 ±(99.9%) 0.006 ms/op
Iteration   1: 2.515 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.002 ms/op
                 createUser·p0.50:   2.589 ms/op
                 createUser·p0.90:   3.052 ms/op
                 createUser·p0.95:   3.170 ms/op
                 createUser·p0.99:   3.695 ms/op
                 createUser·p0.999:  11.731 ms/op
                 createUser·p0.9999: 20.349 ms/op
                 createUser·p1.00:   21.070 ms/op

Iteration   2: 2.521 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.018 ms/op
                 createUser·p0.50:   2.597 ms/op
                 createUser·p0.90:   3.068 ms/op
                 createUser·p0.95:   3.178 ms/op
                 createUser·p0.99:   3.600 ms/op
                 createUser·p0.999:  10.495 ms/op
                 createUser·p0.9999: 12.658 ms/op
                 createUser·p1.00:   13.435 ms/op

Iteration   3: 2.531 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.829 ms/op
                 createUser·p0.50:   2.597 ms/op
                 createUser·p0.90:   3.084 ms/op
                 createUser·p0.95:   3.228 ms/op
                 createUser·p0.99:   3.912 ms/op
                 createUser·p0.999:  9.041 ms/op
                 createUser·p0.9999: 12.684 ms/op
                 createUser·p1.00:   16.482 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 380055
  mean =      2.523 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 182003 
    [ 2.500,  5.000) = 197364 
    [ 5.000,  7.500) = 271 
    [ 7.500, 10.000) = 104 
    [10.000, 12.500) = 177 
    [12.500, 15.000) = 103 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.829 ms/op
     p(50.0000) =      2.593 ms/op
     p(90.0000) =      3.068 ms/op
     p(95.0000) =      3.191 ms/op
     p(99.0000) =      3.736 ms/op
     p(99.9000) =      9.059 ms/op
     p(99.9900) =     14.647 ms/op
     p(99.9990) =     20.644 ms/op
     p(99.9999) =     21.070 ms/op
    p(100.0000) =     21.070 ms/op


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
# Warmup Iteration   1: 3.648 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.467 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.466 ±(99.9%) 0.005 ms/op
Iteration   1: 2.443 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.930 ms/op
                 existUser·p0.50:   2.482 ms/op
                 existUser·p0.90:   2.970 ms/op
                 existUser·p0.95:   3.080 ms/op
                 existUser·p0.99:   3.518 ms/op
                 existUser·p0.999:  5.881 ms/op
                 existUser·p0.9999: 13.925 ms/op
                 existUser·p1.00:   14.975 ms/op

Iteration   2: 2.441 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.014 ms/op
                 existUser·p0.50:   2.531 ms/op
                 existUser·p0.90:   2.957 ms/op
                 existUser·p0.95:   3.056 ms/op
                 existUser·p0.99:   3.469 ms/op
                 existUser·p0.999:  7.365 ms/op
                 existUser·p0.9999: 12.501 ms/op
                 existUser·p1.00:   13.533 ms/op

Iteration   3: 2.460 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.916 ms/op
                 existUser·p0.50:   2.490 ms/op
                 existUser·p0.90:   2.998 ms/op
                 existUser·p0.95:   3.117 ms/op
                 existUser·p0.99:   3.822 ms/op
                 existUser·p0.999:  6.513 ms/op
                 existUser·p0.9999: 12.452 ms/op
                 existUser·p1.00:   13.140 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 391814
  mean =      2.448 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 46 
    [ 1.250,  2.500) = 195994 
    [ 2.500,  3.750) = 192664 
    [ 3.750,  5.000) = 2544 
    [ 5.000,  6.250) = 170 
    [ 6.250,  7.500) = 38 
    [ 7.500,  8.750) = 4 
    [ 8.750, 10.000) = 51 
    [10.000, 11.250) = 97 
    [11.250, 12.500) = 107 
    [12.500, 13.750) = 72 
    [13.750, 15.000) = 27 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.916 ms/op
     p(50.0000) =      2.499 ms/op
     p(90.0000) =      2.978 ms/op
     p(95.0000) =      3.084 ms/op
     p(99.0000) =      3.596 ms/op
     p(99.9000) =      6.499 ms/op
     p(99.9900) =     13.238 ms/op
     p(99.9990) =     14.453 ms/op
     p(99.9999) =     14.975 ms/op
    p(100.0000) =     14.975 ms/op


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
# Warmup Iteration   1: 3.981 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.579 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.510 ±(99.9%) 0.006 ms/op
Iteration   1: 2.468 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.756 ms/op
                 getUser·p0.50:   2.511 ms/op
                 getUser·p0.90:   2.994 ms/op
                 getUser·p0.95:   3.084 ms/op
                 getUser·p0.99:   3.478 ms/op
                 getUser·p0.999:  6.270 ms/op
                 getUser·p0.9999: 13.764 ms/op
                 getUser·p1.00:   14.729 ms/op

Iteration   2: 2.493 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.890 ms/op
                 getUser·p0.50:   2.511 ms/op
                 getUser·p0.90:   3.039 ms/op
                 getUser·p0.95:   3.166 ms/op
                 getUser·p0.99:   3.752 ms/op
                 getUser·p0.999:  7.994 ms/op
                 getUser·p0.9999: 10.423 ms/op
                 getUser·p1.00:   11.158 ms/op

Iteration   3: 2.507 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.935 ms/op
                 getUser·p0.50:   2.519 ms/op
                 getUser·p0.90:   3.064 ms/op
                 getUser·p0.95:   3.211 ms/op
                 getUser·p0.99:   3.965 ms/op
                 getUser·p0.999:  5.693 ms/op
                 getUser·p0.9999: 11.567 ms/op
                 getUser·p1.00:   12.091 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 385343
  mean =      2.489 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 96 
    [ 1.250,  2.500) = 191524 
    [ 2.500,  3.750) = 189904 
    [ 3.750,  5.000) = 3195 
    [ 5.000,  6.250) = 262 
    [ 6.250,  7.500) = 10 
    [ 7.500,  8.750) = 22 
    [ 8.750, 10.000) = 96 
    [10.000, 11.250) = 93 
    [11.250, 12.500) = 70 
    [12.500, 13.750) = 55 
    [13.750, 15.000) = 16 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.756 ms/op
     p(50.0000) =      2.515 ms/op
     p(90.0000) =      3.031 ms/op
     p(95.0000) =      3.154 ms/op
     p(99.0000) =      3.744 ms/op
     p(99.9000) =      5.857 ms/op
     p(99.9900) =     13.091 ms/op
     p(99.9990) =     14.526 ms/op
     p(99.9999) =     14.729 ms/op
    p(100.0000) =     14.729 ms/op


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
# Warmup Iteration   1: 4.700 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.072 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.059 ±(99.9%) 0.009 ms/op
Iteration   1: 3.072 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.975 ms/op
                 listUser·p0.50:   3.019 ms/op
                 listUser·p0.90:   3.949 ms/op
                 listUser·p0.95:   4.456 ms/op
                 listUser·p0.99:   5.710 ms/op
                 listUser·p0.999:  9.535 ms/op
                 listUser·p0.9999: 10.944 ms/op
                 listUser·p1.00:   11.928 ms/op

Iteration   2: 3.086 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.929 ms/op
                 listUser·p0.50:   3.019 ms/op
                 listUser·p0.90:   3.973 ms/op
                 listUser·p0.95:   4.538 ms/op
                 listUser·p0.99:   5.751 ms/op
                 listUser·p0.999:  8.952 ms/op
                 listUser·p0.9999: 10.556 ms/op
                 listUser·p1.00:   11.125 ms/op

Iteration   3: 3.077 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.994 ms/op
                 listUser·p0.50:   3.023 ms/op
                 listUser·p0.90:   3.965 ms/op
                 listUser·p0.95:   4.473 ms/op
                 listUser·p0.99:   5.677 ms/op
                 listUser·p0.999:  9.226 ms/op
                 listUser·p0.9999: 11.410 ms/op
                 listUser·p1.00:   12.648 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 311548
  mean =      3.078 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 102 
    [ 1.250,  2.500) = 81161 
    [ 2.500,  3.750) = 186961 
    [ 3.750,  5.000) = 35239 
    [ 5.000,  6.250) = 6594 
    [ 6.250,  7.500) = 811 
    [ 7.500,  8.750) = 259 
    [ 8.750, 10.000) = 281 
    [10.000, 11.250) = 122 
    [11.250, 12.500) = 17 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.929 ms/op
     p(50.0000) =      3.019 ms/op
     p(90.0000) =      3.961 ms/op
     p(95.0000) =      4.489 ms/op
     p(99.0000) =      5.718 ms/op
     p(99.9000) =      9.241 ms/op
     p(99.9900) =     10.895 ms/op
     p(99.9990) =     12.124 ms/op
     p(99.9999) =     12.648 ms/op
    p(100.0000) =     12.648 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.625 ± 1.779  ops/ms
ClientPb.existUser                       thrpt       3  13.180 ± 1.027  ops/ms
ClientPb.getUser                         thrpt       3  12.788 ± 1.013  ops/ms
ClientPb.listUser                        thrpt       3  10.570 ± 1.541  ops/ms
ClientPb.createUser                       avgt       3   2.517 ± 0.735   ms/op
ClientPb.existUser                        avgt       3   2.424 ± 0.141   ms/op
ClientPb.getUser                          avgt       3   2.496 ± 0.029   ms/op
ClientPb.listUser                         avgt       3   3.039 ± 0.150   ms/op
ClientPb.createUser                     sample  380055   2.523 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.829           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.593           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.068           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.191           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.736           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.059           ms/op
ClientPb.createUser:createUser·p0.9999  sample          14.647           ms/op
ClientPb.createUser:createUser·p1.00    sample          21.070           ms/op
ClientPb.existUser                      sample  391814   2.448 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.916           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.499           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.978           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.084           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.596           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.499           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.238           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.975           ms/op
ClientPb.getUser                        sample  385343   2.489 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.756           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.515           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.031           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.154           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.744           ms/op
ClientPb.getUser:getUser·p0.999         sample           5.857           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.091           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.729           ms/op
ClientPb.listUser                       sample  311548   3.078 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.929           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.019           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.961           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.489           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.718           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.241           ms/op
ClientPb.listUser:listUser·p0.9999      sample          10.895           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.648           ms/op
