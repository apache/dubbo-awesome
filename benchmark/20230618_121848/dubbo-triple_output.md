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
# Warmup Iteration   1: 2.383 ops/ms
# Warmup Iteration   2: 6.133 ops/ms
# Warmup Iteration   3: 9.085 ops/ms
Iteration   1: 9.929 ops/ms
Iteration   2: 9.798 ops/ms
Iteration   3: 9.935 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.887 ±(99.9%) 1.411 ops/ms [Average]
  (min, avg, max) = (9.798, 9.887, 9.935), stdev = 0.077
  CI (99.9%): [8.476, 11.298] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.386 ops/ms
# Warmup Iteration   2: 9.389 ops/ms
# Warmup Iteration   3: 9.938 ops/ms
Iteration   1: 10.224 ops/ms
Iteration   2: 10.603 ops/ms
Iteration   3: 10.106 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.311 ±(99.9%) 4.735 ops/ms [Average]
  (min, avg, max) = (10.106, 10.311, 10.603), stdev = 0.260
  CI (99.9%): [5.576, 15.046] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 2.863 ops/ms
# Warmup Iteration   2: 7.363 ops/ms
# Warmup Iteration   3: 8.878 ops/ms
Iteration   1: 9.813 ops/ms
Iteration   2: 9.730 ops/ms
Iteration   3: 10.063 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.869 ±(99.9%) 3.161 ops/ms [Average]
  (min, avg, max) = (9.730, 9.869, 10.063), stdev = 0.173
  CI (99.9%): [6.708, 13.030] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 2.986 ops/ms
# Warmup Iteration   2: 7.747 ops/ms
# Warmup Iteration   3: 8.153 ops/ms
Iteration   1: 8.209 ops/ms
Iteration   2: 8.161 ops/ms
Iteration   3: 8.447 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.272 ±(99.9%) 2.790 ops/ms [Average]
  (min, avg, max) = (8.161, 8.272, 8.447), stdev = 0.153
  CI (99.9%): [5.482, 11.062] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 7.519 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.839 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.483 ±(99.9%) 0.004 ms/op
Iteration   1: 3.294 ±(99.9%) 0.006 ms/op
Iteration   2: 3.307 ±(99.9%) 0.004 ms/op
Iteration   3: 3.380 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.327 ±(99.9%) 0.839 ms/op [Average]
  (min, avg, max) = (3.294, 3.327, 3.380), stdev = 0.046
  CI (99.9%): [2.488, 4.166] (assumes normal distribution)


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
# Warmup Iteration   1: 10.111 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.391 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.171 ±(99.9%) 0.004 ms/op
Iteration   1: 3.157 ±(99.9%) 0.005 ms/op
Iteration   2: 3.096 ±(99.9%) 0.004 ms/op
Iteration   3: 3.064 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.106 ±(99.9%) 0.856 ms/op [Average]
  (min, avg, max) = (3.064, 3.106, 3.157), stdev = 0.047
  CI (99.9%): [2.250, 3.962] (assumes normal distribution)


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
# Warmup Iteration   1: 7.972 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.663 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.598 ±(99.9%) 0.005 ms/op
Iteration   1: 3.437 ±(99.9%) 0.003 ms/op
Iteration   2: 3.334 ±(99.9%) 0.004 ms/op
Iteration   3: 3.424 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.398 ±(99.9%) 1.026 ms/op [Average]
  (min, avg, max) = (3.334, 3.398, 3.437), stdev = 0.056
  CI (99.9%): [2.372, 4.425] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 11.408 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.244 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.979 ±(99.9%) 0.007 ms/op
Iteration   1: 3.766 ±(99.9%) 0.010 ms/op
Iteration   2: 3.785 ±(99.9%) 0.008 ms/op
Iteration   3: 3.812 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.788 ±(99.9%) 0.420 ms/op [Average]
  (min, avg, max) = (3.766, 3.788, 3.812), stdev = 0.023
  CI (99.9%): [3.368, 4.208] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 8.454 ±(99.9%) 0.117 ms/op
# Warmup Iteration   2: 3.681 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.121 ±(99.9%) 0.009 ms/op
Iteration   1: 3.271 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.567 ms/op
                 createUser·p0.50:   3.224 ms/op
                 createUser·p0.90:   3.645 ms/op
                 createUser·p0.95:   4.080 ms/op
                 createUser·p0.99:   5.505 ms/op
                 createUser·p0.999:  21.758 ms/op
                 createUser·p0.9999: 28.077 ms/op
                 createUser·p1.00:   29.426 ms/op

Iteration   2: 3.297 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.304 ms/op
                 createUser·p0.50:   3.236 ms/op
                 createUser·p0.90:   3.777 ms/op
                 createUser·p0.95:   4.059 ms/op
                 createUser·p0.99:   5.972 ms/op
                 createUser·p0.999:  15.974 ms/op
                 createUser·p0.9999: 26.551 ms/op
                 createUser·p1.00:   27.853 ms/op

Iteration   3: 3.275 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.311 ms/op
                 createUser·p0.50:   3.195 ms/op
                 createUser·p0.90:   3.736 ms/op
                 createUser·p0.95:   4.342 ms/op
                 createUser·p0.99:   5.915 ms/op
                 createUser·p0.999:  16.358 ms/op
                 createUser·p0.9999: 20.521 ms/op
                 createUser·p1.00:   21.234 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 292582
  mean =      3.281 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26957 
    [ 2.500,  5.000) = 258338 
    [ 5.000,  7.500) = 6332 
    [ 7.500, 10.000) = 537 
    [10.000, 12.500) = 52 
    [12.500, 15.000) = 22 
    [15.000, 17.500) = 66 
    [17.500, 20.000) = 45 
    [20.000, 22.500) = 96 
    [22.500, 25.000) = 83 
    [25.000, 27.500) = 39 

  Percentiles, ms/op:
      p(0.0000) =      0.304 ms/op
     p(50.0000) =      3.219 ms/op
     p(90.0000) =      3.727 ms/op
     p(95.0000) =      4.137 ms/op
     p(99.0000) =      5.702 ms/op
     p(99.9000) =     17.105 ms/op
     p(99.9900) =     26.730 ms/op
     p(99.9990) =     28.713 ms/op
     p(99.9999) =     29.426 ms/op
    p(100.0000) =     29.426 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 8.005 ±(99.9%) 0.093 ms/op
# Warmup Iteration   2: 3.375 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.124 ±(99.9%) 0.008 ms/op
Iteration   1: 3.126 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.104 ms/op
                 existUser·p0.50:   3.133 ms/op
                 existUser·p0.90:   3.334 ms/op
                 existUser·p0.95:   3.613 ms/op
                 existUser·p0.99:   5.317 ms/op
                 existUser·p0.999:  10.645 ms/op
                 existUser·p0.9999: 20.309 ms/op
                 existUser·p1.00:   20.709 ms/op

Iteration   2: 3.056 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.965 ms/op
                 existUser·p0.50:   3.039 ms/op
                 existUser·p0.90:   3.265 ms/op
                 existUser·p0.95:   3.453 ms/op
                 existUser·p0.99:   5.325 ms/op
                 existUser·p0.999:  9.980 ms/op
                 existUser·p0.9999: 25.675 ms/op
                 existUser·p1.00:   27.591 ms/op

Iteration   3: 3.123 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.329 ms/op
                 existUser·p0.50:   3.023 ms/op
                 existUser·p0.90:   3.416 ms/op
                 existUser·p0.95:   3.629 ms/op
                 existUser·p0.99:   5.235 ms/op
                 existUser·p0.999:  11.846 ms/op
                 existUser·p0.9999: 24.061 ms/op
                 existUser·p1.00:   24.543 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 309314
  mean =      3.101 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19428 
    [ 2.500,  5.000) = 285702 
    [ 5.000,  7.500) = 3330 
    [ 7.500, 10.000) = 473 
    [10.000, 12.500) = 93 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 127 
    [20.000, 22.500) = 44 
    [22.500, 25.000) = 63 
    [25.000, 27.500) = 22 

  Percentiles, ms/op:
      p(0.0000) =      0.965 ms/op
     p(50.0000) =      3.068 ms/op
     p(90.0000) =      3.351 ms/op
     p(95.0000) =      3.568 ms/op
     p(99.0000) =      5.284 ms/op
     p(99.9000) =     11.370 ms/op
     p(99.9900) =     24.674 ms/op
     p(99.9990) =     27.426 ms/op
     p(99.9999) =     27.591 ms/op
    p(100.0000) =     27.591 ms/op


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
# Warmup Iteration   1: 8.801 ±(99.9%) 0.108 ms/op
# Warmup Iteration   2: 3.701 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.477 ±(99.9%) 0.012 ms/op
Iteration   1: 3.207 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.397 ms/op
                 getUser·p0.50:   3.113 ms/op
                 getUser·p0.90:   3.527 ms/op
                 getUser·p0.95:   3.785 ms/op
                 getUser·p0.99:   5.530 ms/op
                 getUser·p0.999:  13.204 ms/op
                 getUser·p0.9999: 24.744 ms/op
                 getUser·p1.00:   25.330 ms/op

Iteration   2: 3.346 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.161 ms/op
                 getUser·p0.50:   3.211 ms/op
                 getUser·p0.90:   3.695 ms/op
                 getUser·p0.95:   4.149 ms/op
                 getUser·p0.99:   6.888 ms/op
                 getUser·p0.999:  21.004 ms/op
                 getUser·p0.9999: 27.834 ms/op
                 getUser·p1.00:   28.705 ms/op

Iteration   3: 3.309 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.640 ms/op
                 getUser·p0.50:   3.150 ms/op
                 getUser·p0.90:   3.564 ms/op
                 getUser·p0.95:   3.924 ms/op
                 getUser·p0.99:   6.764 ms/op
                 getUser·p0.999:  21.115 ms/op
                 getUser·p0.9999: 23.986 ms/op
                 getUser·p1.00:   24.445 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 291952
  mean =      3.286 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9113 
    [ 2.500,  5.000) = 275528 
    [ 5.000,  7.500) = 5565 
    [ 7.500, 10.000) = 874 
    [10.000, 12.500) = 344 
    [12.500, 15.000) = 130 
    [15.000, 17.500) = 40 
    [17.500, 20.000) = 54 
    [20.000, 22.500) = 182 
    [22.500, 25.000) = 86 
    [25.000, 27.500) = 25 

  Percentiles, ms/op:
      p(0.0000) =      1.161 ms/op
     p(50.0000) =      3.162 ms/op
     p(90.0000) =      3.596 ms/op
     p(95.0000) =      3.949 ms/op
     p(99.0000) =      6.373 ms/op
     p(99.9000) =     20.120 ms/op
     p(99.9900) =     26.411 ms/op
     p(99.9990) =     28.456 ms/op
     p(99.9999) =     28.705 ms/op
    p(100.0000) =     28.705 ms/op


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
# Warmup Iteration   1: 10.868 ±(99.9%) 0.145 ms/op
# Warmup Iteration   2: 4.526 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.074 ±(99.9%) 0.014 ms/op
Iteration   1: 3.999 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.894 ms/op
                 listUser·p0.50:   3.854 ms/op
                 listUser·p0.90:   4.342 ms/op
                 listUser·p0.95:   4.989 ms/op
                 listUser·p0.99:   7.381 ms/op
                 listUser·p0.999:  19.144 ms/op
                 listUser·p0.9999: 24.478 ms/op
                 listUser·p1.00:   25.264 ms/op

Iteration   2: 3.972 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.363 ms/op
                 listUser·p0.50:   3.785 ms/op
                 listUser·p0.90:   4.424 ms/op
                 listUser·p0.95:   5.177 ms/op
                 listUser·p0.99:   7.635 ms/op
                 listUser·p0.999:  18.857 ms/op
                 listUser·p0.9999: 23.526 ms/op
                 listUser·p1.00:   24.314 ms/op

Iteration   3: 4.058 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.322 ms/op
                 listUser·p0.50:   3.928 ms/op
                 listUser·p0.90:   4.448 ms/op
                 listUser·p0.95:   5.104 ms/op
                 listUser·p0.99:   7.381 ms/op
                 listUser·p0.999:  16.571 ms/op
                 listUser·p0.9999: 18.661 ms/op
                 listUser·p1.00:   19.530 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 239267
  mean =      4.009 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 29 
    [ 2.500,  5.000) = 226459 
    [ 5.000,  7.500) = 10381 
    [ 7.500, 10.000) = 1482 
    [10.000, 12.500) = 335 
    [12.500, 15.000) = 193 
    [15.000, 17.500) = 108 
    [17.500, 20.000) = 161 
    [20.000, 22.500) = 35 
    [22.500, 25.000) = 80 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      1.894 ms/op
     p(50.0000) =      3.863 ms/op
     p(90.0000) =      4.407 ms/op
     p(95.0000) =      5.087 ms/op
     p(99.0000) =      7.504 ms/op
     p(99.9000) =     17.891 ms/op
     p(99.9900) =     23.759 ms/op
     p(99.9990) =     25.160 ms/op
     p(99.9999) =     25.264 ms/op
    p(100.0000) =     25.264 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.887 ± 1.411  ops/ms
ClientPb.existUser                       thrpt       3  10.311 ± 4.735  ops/ms
ClientPb.getUser                         thrpt       3   9.869 ± 3.161  ops/ms
ClientPb.listUser                        thrpt       3   8.272 ± 2.790  ops/ms
ClientPb.createUser                       avgt       3   3.327 ± 0.839   ms/op
ClientPb.existUser                        avgt       3   3.106 ± 0.856   ms/op
ClientPb.getUser                          avgt       3   3.398 ± 1.026   ms/op
ClientPb.listUser                         avgt       3   3.788 ± 0.420   ms/op
ClientPb.createUser                     sample  292582   3.281 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.304           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.219           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.727           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.137           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.702           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.105           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.730           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.426           ms/op
ClientPb.existUser                      sample  309314   3.101 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.965           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.068           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.351           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.568           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.284           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.370           ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.674           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.591           ms/op
ClientPb.getUser                        sample  291952   3.286 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.161           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.162           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.596           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.949           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.373           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.120           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.411           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.705           ms/op
ClientPb.listUser                       sample  239267   4.009 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.894           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.863           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.407           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.087           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.504           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.891           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.759           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.264           ms/op
