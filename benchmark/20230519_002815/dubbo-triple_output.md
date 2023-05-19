# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.004 ops/ms
# Warmup Iteration   2: 4.572 ops/ms
# Warmup Iteration   3: 8.984 ops/ms
Iteration   1: 9.323 ops/ms
Iteration   2: 9.542 ops/ms
Iteration   3: 9.472 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.446 ±(99.9%) 2.038 ops/ms [Average]
  (min, avg, max) = (9.323, 9.446, 9.542), stdev = 0.112
  CI (99.9%): [7.408, 11.483] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.012 ops/ms
# Warmup Iteration   2: 8.615 ops/ms
# Warmup Iteration   3: 9.647 ops/ms
Iteration   1: 9.849 ops/ms
Iteration   2: 9.787 ops/ms
Iteration   3: 9.785 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.807 ±(99.9%) 0.662 ops/ms [Average]
  (min, avg, max) = (9.785, 9.807, 9.849), stdev = 0.036
  CI (99.9%): [9.145, 10.469] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 2.956 ops/ms
# Warmup Iteration   2: 8.128 ops/ms
# Warmup Iteration   3: 9.187 ops/ms
Iteration   1: 9.308 ops/ms
Iteration   2: 9.198 ops/ms
Iteration   3: 9.207 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.237 ±(99.9%) 1.113 ops/ms [Average]
  (min, avg, max) = (9.198, 9.237, 9.308), stdev = 0.061
  CI (99.9%): [8.124, 10.350] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.460 ops/ms
# Warmup Iteration   2: 6.733 ops/ms
# Warmup Iteration   3: 7.633 ops/ms
Iteration   1: 8.020 ops/ms
Iteration   2: 8.180 ops/ms
Iteration   3: 7.923 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.041 ±(99.9%) 2.370 ops/ms [Average]
  (min, avg, max) = (7.923, 8.041, 8.180), stdev = 0.130
  CI (99.9%): [5.671, 10.411] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 11.006 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 4.022 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.577 ±(99.9%) 0.009 ms/op
Iteration   1: 3.522 ±(99.9%) 0.005 ms/op
Iteration   2: 3.459 ±(99.9%) 0.004 ms/op
Iteration   3: 3.450 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.477 ±(99.9%) 0.715 ms/op [Average]
  (min, avg, max) = (3.450, 3.477, 3.522), stdev = 0.039
  CI (99.9%): [2.762, 4.192] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 8.209 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.574 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.243 ±(99.9%) 0.011 ms/op
Iteration   1: 3.251 ±(99.9%) 0.012 ms/op
Iteration   2: 3.291 ±(99.9%) 0.008 ms/op
Iteration   3: 3.338 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.293 ±(99.9%) 0.786 ms/op [Average]
  (min, avg, max) = (3.251, 3.293, 3.338), stdev = 0.043
  CI (99.9%): [2.507, 4.080] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 9.914 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.785 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.521 ±(99.9%) 0.007 ms/op
Iteration   1: 3.324 ±(99.9%) 0.006 ms/op
Iteration   2: 3.543 ±(99.9%) 0.005 ms/op
Iteration   3: 3.305 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.391 ±(99.9%) 2.413 ms/op [Average]
  (min, avg, max) = (3.305, 3.391, 3.543), stdev = 0.132
  CI (99.9%): [0.978, 5.803] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 10.400 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 4.326 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.041 ±(99.9%) 0.012 ms/op
Iteration   1: 3.953 ±(99.9%) 0.009 ms/op
Iteration   2: 3.859 ±(99.9%) 0.016 ms/op
Iteration   3: 4.031 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.948 ±(99.9%) 1.568 ms/op [Average]
  (min, avg, max) = (3.859, 3.948, 4.031), stdev = 0.086
  CI (99.9%): [2.380, 5.516] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 10.278 ±(99.9%) 0.144 ms/op
# Warmup Iteration   2: 4.117 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.421 ±(99.9%) 0.010 ms/op
Iteration   1: 3.636 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.454 ms/op
                 createUser·p0.50:   3.371 ms/op
                 createUser·p0.90:   4.309 ms/op
                 createUser·p0.95:   5.931 ms/op
                 createUser·p0.99:   7.717 ms/op
                 createUser·p0.999:  22.381 ms/op
                 createUser·p0.9999: 31.398 ms/op
                 createUser·p1.00:   32.014 ms/op

Iteration   2: 3.519 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.941 ms/op
                 createUser·p0.50:   3.391 ms/op
                 createUser·p0.90:   4.133 ms/op
                 createUser·p0.95:   4.530 ms/op
                 createUser·p0.99:   6.176 ms/op
                 createUser·p0.999:  23.730 ms/op
                 createUser·p0.9999: 30.799 ms/op
                 createUser·p1.00:   32.539 ms/op

Iteration   3: 3.484 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.481 ms/op
                 createUser·p0.50:   3.432 ms/op
                 createUser·p0.90:   3.838 ms/op
                 createUser·p0.95:   4.243 ms/op
                 createUser·p0.99:   5.849 ms/op
                 createUser·p0.999:  18.186 ms/op
                 createUser·p0.9999: 27.001 ms/op
                 createUser·p1.00:   28.574 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 270652
  mean =      3.545 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14479 
    [ 2.500,  5.000) = 243896 
    [ 5.000,  7.500) = 10386 
    [ 7.500, 10.000) = 1331 
    [10.000, 12.500) = 220 
    [12.500, 15.000) = 45 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 37 
    [22.500, 25.000) = 106 
    [25.000, 27.500) = 51 
    [27.500, 30.000) = 27 
    [30.000, 32.500) = 34 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.481 ms/op
     p(50.0000) =      3.404 ms/op
     p(90.0000) =      4.076 ms/op
     p(95.0000) =      4.760 ms/op
     p(99.0000) =      7.201 ms/op
     p(99.9000) =     18.756 ms/op
     p(99.9900) =     30.507 ms/op
     p(99.9990) =     31.737 ms/op
     p(99.9999) =     32.539 ms/op
    p(100.0000) =     32.539 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 9.107 ±(99.9%) 0.120 ms/op
# Warmup Iteration   2: 3.658 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.362 ±(99.9%) 0.008 ms/op
Iteration   1: 3.376 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.031 ms/op
                 existUser·p0.50:   3.326 ms/op
                 existUser·p0.90:   3.678 ms/op
                 existUser·p0.95:   4.252 ms/op
                 existUser·p0.99:   5.603 ms/op
                 existUser·p0.999:  19.964 ms/op
                 existUser·p0.9999: 24.397 ms/op
                 existUser·p1.00:   27.394 ms/op

Iteration   2: 3.394 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.466 ms/op
                 existUser·p0.50:   3.297 ms/op
                 existUser·p0.90:   3.756 ms/op
                 existUser·p0.95:   4.014 ms/op
                 existUser·p0.99:   5.734 ms/op
                 existUser·p0.999:  21.234 ms/op
                 existUser·p0.9999: 29.412 ms/op
                 existUser·p1.00:   29.950 ms/op

Iteration   3: 3.375 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.618 ms/op
                 existUser·p0.50:   3.305 ms/op
                 existUser·p0.90:   3.805 ms/op
                 existUser·p0.95:   4.137 ms/op
                 existUser·p0.99:   5.683 ms/op
                 existUser·p0.999:  10.207 ms/op
                 existUser·p0.9999: 26.116 ms/op
                 existUser·p1.00:   26.903 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 283673
  mean =      3.381 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13685 
    [ 2.500,  5.000) = 263756 
    [ 5.000,  7.500) = 5336 
    [ 7.500, 10.000) = 487 
    [10.000, 12.500) = 130 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 78 
    [22.500, 25.000) = 83 
    [25.000, 27.500) = 60 

  Percentiles, ms/op:
      p(0.0000) =      1.031 ms/op
     p(50.0000) =      3.314 ms/op
     p(90.0000) =      3.764 ms/op
     p(95.0000) =      4.125 ms/op
     p(99.0000) =      5.669 ms/op
     p(99.9000) =     11.715 ms/op
     p(99.9900) =     28.103 ms/op
     p(99.9990) =     29.775 ms/op
     p(99.9999) =     29.950 ms/op
    p(100.0000) =     29.950 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 9.813 ±(99.9%) 0.127 ms/op
# Warmup Iteration   2: 3.810 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.630 ±(99.9%) 0.012 ms/op
Iteration   1: 3.419 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.485 ms/op
                 getUser·p0.50:   3.301 ms/op
                 getUser·p0.90:   3.920 ms/op
                 getUser·p0.95:   4.235 ms/op
                 getUser·p0.99:   6.226 ms/op
                 getUser·p0.999:  21.330 ms/op
                 getUser·p0.9999: 24.466 ms/op
                 getUser·p1.00:   25.166 ms/op

Iteration   2: 3.398 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.438 ms/op
                 getUser·p0.50:   3.244 ms/op
                 getUser·p0.90:   3.863 ms/op
                 getUser·p0.95:   4.211 ms/op
                 getUser·p0.99:   5.931 ms/op
                 getUser·p0.999:  23.215 ms/op
                 getUser·p0.9999: 31.293 ms/op
                 getUser·p1.00:   32.211 ms/op

Iteration   3: 3.585 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   0.343 ms/op
                 getUser·p0.50:   3.375 ms/op
                 getUser·p0.90:   4.149 ms/op
                 getUser·p0.95:   5.415 ms/op
                 getUser·p0.99:   8.978 ms/op
                 getUser·p0.999:  23.249 ms/op
                 getUser·p0.9999: 30.746 ms/op
                 getUser·p1.00:   37.749 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 277031
  mean =      3.465 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11303 
    [ 2.500,  5.000) = 255779 
    [ 5.000,  7.500) = 7641 
    [ 7.500, 10.000) = 1666 
    [10.000, 12.500) = 334 
    [12.500, 15.000) = 20 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 38 
    [22.500, 25.000) = 124 
    [25.000, 27.500) = 51 
    [27.500, 30.000) = 27 
    [30.000, 32.500) = 47 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.343 ms/op
     p(50.0000) =      3.322 ms/op
     p(90.0000) =      3.965 ms/op
     p(95.0000) =      4.415 ms/op
     p(99.0000) =      6.996 ms/op
     p(99.9000) =     21.529 ms/op
     p(99.9900) =     30.943 ms/op
     p(99.9990) =     32.226 ms/op
     p(99.9999) =     37.749 ms/op
    p(100.0000) =     37.749 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 11.790 ±(99.9%) 0.164 ms/op
# Warmup Iteration   2: 4.761 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 4.035 ±(99.9%) 0.013 ms/op
Iteration   1: 4.101 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.722 ms/op
                 listUser·p0.50:   3.949 ms/op
                 listUser·p0.90:   4.424 ms/op
                 listUser·p0.95:   4.784 ms/op
                 listUser·p0.99:   8.151 ms/op
                 listUser·p0.999:  22.873 ms/op
                 listUser·p0.9999: 26.464 ms/op
                 listUser·p1.00:   27.230 ms/op

Iteration   2: 3.901 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.634 ms/op
                 listUser·p0.50:   3.764 ms/op
                 listUser·p0.90:   4.276 ms/op
                 listUser·p0.95:   4.489 ms/op
                 listUser·p0.99:   6.873 ms/op
                 listUser·p0.999:  16.253 ms/op
                 listUser·p0.9999: 17.039 ms/op
                 listUser·p1.00:   17.400 ms/op

Iteration   3: 3.963 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.347 ms/op
                 listUser·p0.50:   3.756 ms/op
                 listUser·p0.90:   4.424 ms/op
                 listUser·p0.95:   4.669 ms/op
                 listUser·p0.99:   7.432 ms/op
                 listUser·p0.999:  16.029 ms/op
                 listUser·p0.9999: 19.525 ms/op
                 listUser·p1.00:   21.299 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 240580
  mean =      3.987 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 43 
    [ 2.500,  5.000) = 232614 
    [ 5.000,  7.500) = 5473 
    [ 7.500, 10.000) = 1520 
    [10.000, 12.500) = 344 
    [12.500, 15.000) = 160 
    [15.000, 17.500) = 239 
    [17.500, 20.000) = 83 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 56 
    [25.000, 27.500) = 29 

  Percentiles, ms/op:
      p(0.0000) =      1.634 ms/op
     p(50.0000) =      3.797 ms/op
     p(90.0000) =      4.383 ms/op
     p(95.0000) =      4.637 ms/op
     p(99.0000) =      7.546 ms/op
     p(99.9000) =     16.768 ms/op
     p(99.9900) =     25.262 ms/op
     p(99.9990) =     26.926 ms/op
     p(99.9999) =     27.230 ms/op
    p(100.0000) =     27.230 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.446 ± 2.038  ops/ms
ClientPb.existUser                       thrpt       3   9.807 ± 0.662  ops/ms
ClientPb.getUser                         thrpt       3   9.237 ± 1.113  ops/ms
ClientPb.listUser                        thrpt       3   8.041 ± 2.370  ops/ms
ClientPb.createUser                       avgt       3   3.477 ± 0.715   ms/op
ClientPb.existUser                        avgt       3   3.293 ± 0.786   ms/op
ClientPb.getUser                          avgt       3   3.391 ± 2.413   ms/op
ClientPb.listUser                         avgt       3   3.948 ± 1.568   ms/op
ClientPb.createUser                     sample  270652   3.545 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.481           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.404           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.076           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.760           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.201           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.756           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.507           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.539           ms/op
ClientPb.existUser                      sample  283673   3.381 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.031           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.314           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.764           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.125           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.669           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.715           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.103           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.950           ms/op
ClientPb.getUser                        sample  277031   3.465 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.343           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.322           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.965           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.415           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.996           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.529           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.943           ms/op
ClientPb.getUser:getUser·p1.00          sample          37.749           ms/op
ClientPb.listUser                       sample  240580   3.987 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.634           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.797           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.383           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.637           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.546           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.768           ms/op
ClientPb.listUser:listUser·p0.9999      sample          25.262           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.230           ms/op
