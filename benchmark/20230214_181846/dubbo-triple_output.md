# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.277 ops/ms
# Warmup Iteration   2: 5.172 ops/ms
# Warmup Iteration   3: 8.210 ops/ms
Iteration   1: 9.188 ops/ms
Iteration   2: 9.397 ops/ms
Iteration   3: 9.459 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.348 ±(99.9%) 2.588 ops/ms [Average]
  (min, avg, max) = (9.188, 9.348, 9.459), stdev = 0.142
  CI (99.9%): [6.760, 11.936] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 3.166 ops/ms
# Warmup Iteration   2: 8.853 ops/ms
# Warmup Iteration   3: 9.336 ops/ms
Iteration   1: 9.797 ops/ms
Iteration   2: 9.798 ops/ms
Iteration   3: 9.380 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.658 ±(99.9%) 4.396 ops/ms [Average]
  (min, avg, max) = (9.380, 9.658, 9.798), stdev = 0.241
  CI (99.9%): [5.262, 14.055] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 3.150 ops/ms
# Warmup Iteration   2: 8.475 ops/ms
# Warmup Iteration   3: 9.032 ops/ms
Iteration   1: 9.144 ops/ms
Iteration   2: 9.506 ops/ms
Iteration   3: 9.085 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.245 ±(99.9%) 4.155 ops/ms [Average]
  (min, avg, max) = (9.085, 9.245, 9.506), stdev = 0.228
  CI (99.9%): [5.090, 13.400] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.890 ops/ms
# Warmup Iteration   2: 7.387 ops/ms
# Warmup Iteration   3: 7.577 ops/ms
Iteration   1: 7.844 ops/ms
Iteration   2: 8.059 ops/ms
Iteration   3: 8.313 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.072 ±(99.9%) 4.279 ops/ms [Average]
  (min, avg, max) = (7.844, 8.072, 8.313), stdev = 0.235
  CI (99.9%): [3.793, 12.351] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 10.683 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 4.131 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.697 ±(99.9%) 0.005 ms/op
Iteration   1: 3.461 ±(99.9%) 0.004 ms/op
Iteration   2: 3.545 ±(99.9%) 0.005 ms/op
Iteration   3: 3.530 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.512 ±(99.9%) 0.817 ms/op [Average]
  (min, avg, max) = (3.461, 3.512, 3.545), stdev = 0.045
  CI (99.9%): [2.695, 4.329] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 9.949 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.615 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.354 ±(99.9%) 0.002 ms/op
Iteration   1: 3.380 ±(99.9%) 0.006 ms/op
Iteration   2: 3.209 ±(99.9%) 0.008 ms/op
Iteration   3: 3.287 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.292 ±(99.9%) 1.562 ms/op [Average]
  (min, avg, max) = (3.209, 3.292, 3.380), stdev = 0.086
  CI (99.9%): [1.730, 4.854] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 10.035 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.848 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.485 ±(99.9%) 0.005 ms/op
Iteration   1: 3.378 ±(99.9%) 0.006 ms/op
Iteration   2: 3.336 ±(99.9%) 0.011 ms/op
Iteration   3: 3.446 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.387 ±(99.9%) 1.015 ms/op [Average]
  (min, avg, max) = (3.336, 3.387, 3.446), stdev = 0.056
  CI (99.9%): [2.372, 4.402] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 9.628 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.324 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.034 ±(99.9%) 0.010 ms/op
Iteration   1: 3.955 ±(99.9%) 0.010 ms/op
Iteration   2: 4.018 ±(99.9%) 0.008 ms/op
Iteration   3: 3.967 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.980 ±(99.9%) 0.610 ms/op [Average]
  (min, avg, max) = (3.955, 3.980, 4.018), stdev = 0.033
  CI (99.9%): [3.370, 4.590] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 9.543 ±(99.9%) 0.120 ms/op
# Warmup Iteration   2: 3.996 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.480 ±(99.9%) 0.010 ms/op
Iteration   1: 3.426 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.520 ms/op
                 createUser·p0.50:   3.367 ms/op
                 createUser·p0.90:   3.867 ms/op
                 createUser·p0.95:   4.235 ms/op
                 createUser·p0.99:   5.661 ms/op
                 createUser·p0.999:  20.840 ms/op
                 createUser·p0.9999: 27.776 ms/op
                 createUser·p1.00:   28.213 ms/op

Iteration   2: 3.355 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.305 ms/op
                 createUser·p0.50:   3.326 ms/op
                 createUser·p0.90:   3.654 ms/op
                 createUser·p0.95:   4.026 ms/op
                 createUser·p0.99:   5.276 ms/op
                 createUser·p0.999:  22.338 ms/op
                 createUser·p0.9999: 28.587 ms/op
                 createUser·p1.00:   29.295 ms/op

Iteration   3: 3.442 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.513 ms/op
                 createUser·p0.50:   3.363 ms/op
                 createUser·p0.90:   3.899 ms/op
                 createUser·p0.95:   4.133 ms/op
                 createUser·p0.99:   5.389 ms/op
                 createUser·p0.999:  16.816 ms/op
                 createUser·p0.9999: 26.388 ms/op
                 createUser·p1.00:   27.525 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 281478
  mean =      3.407 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15659 
    [ 2.500,  5.000) = 260587 
    [ 5.000,  7.500) = 4475 
    [ 7.500, 10.000) = 357 
    [10.000, 12.500) = 88 
    [12.500, 15.000) = 22 
    [15.000, 17.500) = 15 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 77 
    [22.500, 25.000) = 76 
    [25.000, 27.500) = 53 

  Percentiles, ms/op:
      p(0.0000) =      1.305 ms/op
     p(50.0000) =      3.351 ms/op
     p(90.0000) =      3.838 ms/op
     p(95.0000) =      4.137 ms/op
     p(99.0000) =      5.480 ms/op
     p(99.9000) =     17.190 ms/op
     p(99.9900) =     28.105 ms/op
     p(99.9990) =     29.131 ms/op
     p(99.9999) =     29.295 ms/op
    p(100.0000) =     29.295 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.396 ±(99.9%) 0.099 ms/op
# Warmup Iteration   2: 3.634 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.231 ±(99.9%) 0.008 ms/op
Iteration   1: 3.250 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.237 ms/op
                 existUser·p0.50:   3.125 ms/op
                 existUser·p0.90:   3.514 ms/op
                 existUser·p0.95:   3.740 ms/op
                 existUser·p0.99:   6.300 ms/op
                 existUser·p0.999:  8.897 ms/op
                 existUser·p0.9999: 27.797 ms/op
                 existUser·p1.00:   28.705 ms/op

Iteration   2: 3.385 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.337 ms/op
                 existUser·p0.50:   3.195 ms/op
                 existUser·p0.90:   3.801 ms/op
                 existUser·p0.95:   4.579 ms/op
                 existUser·p0.99:   6.930 ms/op
                 existUser·p0.999:  21.111 ms/op
                 existUser·p0.9999: 25.002 ms/op
                 existUser·p1.00:   26.214 ms/op

Iteration   3: 3.227 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.383 ms/op
                 existUser·p0.50:   3.125 ms/op
                 existUser·p0.90:   3.478 ms/op
                 existUser·p0.95:   3.641 ms/op
                 existUser·p0.99:   5.661 ms/op
                 existUser·p0.999:  14.257 ms/op
                 existUser·p0.9999: 37.755 ms/op
                 existUser·p1.00:   39.453 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 292163
  mean =      3.286 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3804 
    [ 2.500,  5.000) = 280850 
    [ 5.000,  7.500) = 6311 
    [ 7.500, 10.000) = 737 
    [10.000, 12.500) = 150 
    [12.500, 15.000) = 55 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 52 
    [22.500, 25.000) = 103 
    [25.000, 27.500) = 29 
    [27.500, 30.000) = 13 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 16 

  Percentiles, ms/op:
      p(0.0000) =      0.383 ms/op
     p(50.0000) =      3.146 ms/op
     p(90.0000) =      3.576 ms/op
     p(95.0000) =      3.912 ms/op
     p(99.0000) =      6.521 ms/op
     p(99.9000) =     12.728 ms/op
     p(99.9900) =     35.931 ms/op
     p(99.9990) =     39.387 ms/op
     p(99.9999) =     39.453 ms/op
    p(100.0000) =     39.453 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 9.090 ±(99.9%) 0.120 ms/op
# Warmup Iteration   2: 3.710 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.604 ±(99.9%) 0.012 ms/op
Iteration   1: 3.491 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.468 ms/op
                 getUser·p0.50:   3.281 ms/op
                 getUser·p0.90:   3.957 ms/op
                 getUser·p0.95:   5.325 ms/op
                 getUser·p0.99:   7.135 ms/op
                 getUser·p0.999:  14.278 ms/op
                 getUser·p0.9999: 22.702 ms/op
                 getUser·p1.00:   23.265 ms/op

Iteration   2: 3.449 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.677 ms/op
                 getUser·p0.50:   3.275 ms/op
                 getUser·p0.90:   3.887 ms/op
                 getUser·p0.95:   4.194 ms/op
                 getUser·p0.99:   5.909 ms/op
                 getUser·p0.999:  22.352 ms/op
                 getUser·p0.9999: 29.112 ms/op
                 getUser·p1.00:   30.015 ms/op

Iteration   3: 3.410 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.520 ms/op
                 getUser·p0.50:   3.293 ms/op
                 getUser·p0.90:   3.924 ms/op
                 getUser·p0.95:   4.334 ms/op
                 getUser·p0.99:   5.994 ms/op
                 getUser·p0.999:  23.068 ms/op
                 getUser·p0.9999: 26.575 ms/op
                 getUser·p1.00:   27.787 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 278248
  mean =      3.450 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10396 
    [ 2.500,  5.000) = 258160 
    [ 5.000,  7.500) = 8405 
    [ 7.500, 10.000) = 865 
    [10.000, 12.500) = 99 
    [12.500, 15.000) = 26 
    [15.000, 17.500) = 23 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 51 
    [22.500, 25.000) = 120 
    [25.000, 27.500) = 57 
    [27.500, 30.000) = 28 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.520 ms/op
     p(50.0000) =      3.285 ms/op
     p(90.0000) =      3.912 ms/op
     p(95.0000) =      4.440 ms/op
     p(99.0000) =      6.742 ms/op
     p(99.9000) =     17.031 ms/op
     p(99.9900) =     28.219 ms/op
     p(99.9990) =     29.855 ms/op
     p(99.9999) =     30.015 ms/op
    p(100.0000) =     30.015 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 10.679 ±(99.9%) 0.127 ms/op
# Warmup Iteration   2: 4.478 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.145 ±(99.9%) 0.012 ms/op
Iteration   1: 4.126 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.716 ms/op
                 listUser·p0.50:   3.965 ms/op
                 listUser·p0.90:   4.424 ms/op
                 listUser·p0.95:   5.079 ms/op
                 listUser·p0.99:   7.774 ms/op
                 listUser·p0.999:  20.218 ms/op
                 listUser·p0.9999: 29.934 ms/op
                 listUser·p1.00:   31.850 ms/op

Iteration   2: 4.026 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.372 ms/op
                 listUser·p0.50:   3.846 ms/op
                 listUser·p0.90:   4.399 ms/op
                 listUser·p0.95:   4.645 ms/op
                 listUser·p0.99:   7.653 ms/op
                 listUser·p0.999:  15.352 ms/op
                 listUser·p0.9999: 25.626 ms/op
                 listUser·p1.00:   25.690 ms/op

Iteration   3: 3.900 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.580 ms/op
                 listUser·p0.50:   3.789 ms/op
                 listUser·p0.90:   4.260 ms/op
                 listUser·p0.95:   4.555 ms/op
                 listUser·p0.99:   6.068 ms/op
                 listUser·p0.999:  15.074 ms/op
                 listUser·p0.9999: 16.089 ms/op
                 listUser·p1.00:   16.253 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 238942
  mean =      4.015 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18 
    [ 2.500,  5.000) = 230681 
    [ 5.000,  7.500) = 6087 
    [ 7.500, 10.000) = 1260 
    [10.000, 12.500) = 321 
    [12.500, 15.000) = 208 
    [15.000, 17.500) = 174 
    [17.500, 20.000) = 84 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 50 
    [27.500, 30.000) = 27 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.716 ms/op
     p(50.0000) =      3.846 ms/op
     p(90.0000) =      4.375 ms/op
     p(95.0000) =      4.661 ms/op
     p(99.0000) =      7.299 ms/op
     p(99.9000) =     15.974 ms/op
     p(99.9900) =     28.070 ms/op
     p(99.9990) =     30.461 ms/op
     p(99.9999) =     31.850 ms/op
    p(100.0000) =     31.850 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.348 ± 2.588  ops/ms
ClientPb.existUser                       thrpt       3   9.658 ± 4.396  ops/ms
ClientPb.getUser                         thrpt       3   9.245 ± 4.155  ops/ms
ClientPb.listUser                        thrpt       3   8.072 ± 4.279  ops/ms
ClientPb.createUser                       avgt       3   3.512 ± 0.817   ms/op
ClientPb.existUser                        avgt       3   3.292 ± 1.562   ms/op
ClientPb.getUser                          avgt       3   3.387 ± 1.015   ms/op
ClientPb.listUser                         avgt       3   3.980 ± 0.610   ms/op
ClientPb.createUser                     sample  281478   3.407 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.305           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.351           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.838           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.137           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.480           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.190           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.105           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.295           ms/op
ClientPb.existUser                      sample  292163   3.286 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.383           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.146           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.576           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.912           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.521           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.728           ms/op
ClientPb.existUser:existUser·p0.9999    sample          35.931           ms/op
ClientPb.existUser:existUser·p1.00      sample          39.453           ms/op
ClientPb.getUser                        sample  278248   3.450 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.520           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.285           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.912           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.440           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.742           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.031           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.219           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.015           ms/op
ClientPb.listUser                       sample  238942   4.015 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.716           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.846           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.375           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.661           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.299           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.974           ms/op
ClientPb.listUser:listUser·p0.9999      sample          28.070           ms/op
ClientPb.listUser:listUser·p1.00        sample          31.850           ms/op
