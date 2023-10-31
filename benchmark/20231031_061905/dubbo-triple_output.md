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
# Warmup Iteration   1: 1.654 ops/ms
# Warmup Iteration   2: 4.081 ops/ms
# Warmup Iteration   3: 8.368 ops/ms
Iteration   1: 8.519 ops/ms
Iteration   2: 8.912 ops/ms
Iteration   3: 8.999 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.810 ±(99.9%) 4.664 ops/ms [Average]
  (min, avg, max) = (8.519, 8.810, 8.999), stdev = 0.256
  CI (99.9%): [4.146, 13.474] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:11
# Fork: 1 of 1
# Warmup Iteration   1: 3.009 ops/ms
# Warmup Iteration   2: 8.411 ops/ms
# Warmup Iteration   3: 9.617 ops/ms
Iteration   1: 9.535 ops/ms
Iteration   2: 9.496 ops/ms
Iteration   3: 9.422 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.484 ±(99.9%) 1.051 ops/ms [Average]
  (min, avg, max) = (9.422, 9.484, 9.535), stdev = 0.058
  CI (99.9%): [8.433, 10.535] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 2.546 ops/ms
# Warmup Iteration   2: 7.872 ops/ms
# Warmup Iteration   3: 8.813 ops/ms
Iteration   1: 9.115 ops/ms
Iteration   2: 9.308 ops/ms
Iteration   3: 9.246 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.223 ±(99.9%) 1.805 ops/ms [Average]
  (min, avg, max) = (9.115, 9.223, 9.308), stdev = 0.099
  CI (99.9%): [7.418, 11.028] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 2.233 ops/ms
# Warmup Iteration   2: 6.747 ops/ms
# Warmup Iteration   3: 7.395 ops/ms
Iteration   1: 7.523 ops/ms
Iteration   2: 7.707 ops/ms
Iteration   3: 7.358 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.529 ±(99.9%) 3.184 ops/ms [Average]
  (min, avg, max) = (7.358, 7.529, 7.707), stdev = 0.175
  CI (99.9%): [4.345, 10.713] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 11.072 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.925 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.561 ±(99.9%) 0.003 ms/op
Iteration   1: 3.471 ±(99.9%) 0.005 ms/op
Iteration   2: 3.568 ±(99.9%) 0.006 ms/op
Iteration   3: 3.496 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.512 ±(99.9%) 0.922 ms/op [Average]
  (min, avg, max) = (3.471, 3.512, 3.568), stdev = 0.051
  CI (99.9%): [2.589, 4.434] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 10.842 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.642 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.482 ±(99.9%) 0.001 ms/op
Iteration   1: 3.334 ±(99.9%) 0.003 ms/op
Iteration   2: 3.368 ±(99.9%) 0.002 ms/op
Iteration   3: 3.345 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.349 ±(99.9%) 0.323 ms/op [Average]
  (min, avg, max) = (3.334, 3.349, 3.368), stdev = 0.018
  CI (99.9%): [3.026, 3.672] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 11.912 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 4.094 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.610 ±(99.9%) 0.006 ms/op
Iteration   1: 3.695 ±(99.9%) 0.006 ms/op
Iteration   2: 3.648 ±(99.9%) 0.002 ms/op
Iteration   3: 3.576 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.640 ±(99.9%) 1.091 ms/op [Average]
  (min, avg, max) = (3.576, 3.640, 3.695), stdev = 0.060
  CI (99.9%): [2.549, 4.731] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 11.946 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 4.609 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.355 ±(99.9%) 0.007 ms/op
Iteration   1: 4.217 ±(99.9%) 0.005 ms/op
Iteration   2: 4.156 ±(99.9%) 0.007 ms/op
Iteration   3: 4.183 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.185 ±(99.9%) 0.560 ms/op [Average]
  (min, avg, max) = (4.156, 4.185, 4.217), stdev = 0.031
  CI (99.9%): [3.625, 4.746] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 10.377 ±(99.9%) 0.130 ms/op
# Warmup Iteration   2: 4.084 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.745 ±(99.9%) 0.014 ms/op
Iteration   1: 3.558 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.812 ms/op
                 createUser·p0.50:   3.408 ms/op
                 createUser·p0.90:   4.129 ms/op
                 createUser·p0.95:   4.456 ms/op
                 createUser·p0.99:   6.549 ms/op
                 createUser·p0.999:  12.620 ms/op
                 createUser·p0.9999: 24.511 ms/op
                 createUser·p1.00:   25.887 ms/op

Iteration   2: 3.491 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.962 ms/op
                 createUser·p0.50:   3.338 ms/op
                 createUser·p0.90:   3.932 ms/op
                 createUser·p0.95:   4.219 ms/op
                 createUser·p0.99:   6.062 ms/op
                 createUser·p0.999:  23.101 ms/op
                 createUser·p0.9999: 40.980 ms/op
                 createUser·p1.00:   42.861 ms/op

Iteration   3: 3.520 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.466 ms/op
                 createUser·p0.50:   3.441 ms/op
                 createUser·p0.90:   4.006 ms/op
                 createUser·p0.95:   4.293 ms/op
                 createUser·p0.99:   6.742 ms/op
                 createUser·p0.999:  23.824 ms/op
                 createUser·p0.9999: 31.982 ms/op
                 createUser·p1.00:   32.276 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 272339
  mean =      3.523 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 265598 
    [ 5.000, 10.000) = 6203 
    [10.000, 15.000) = 262 
    [15.000, 20.000) = 20 
    [20.000, 25.000) = 143 
    [25.000, 30.000) = 71 
    [30.000, 35.000) = 10 
    [35.000, 40.000) = 20 
    [40.000, 45.000) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.962 ms/op
     p(50.0000) =      3.404 ms/op
     p(90.0000) =      4.022 ms/op
     p(95.0000) =      4.334 ms/op
     p(99.0000) =      6.390 ms/op
     p(99.9000) =     16.285 ms/op
     p(99.9900) =     38.797 ms/op
     p(99.9990) =     42.492 ms/op
     p(99.9999) =     42.861 ms/op
    p(100.0000) =     42.861 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 8.322 ±(99.9%) 0.106 ms/op
# Warmup Iteration   2: 3.588 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.408 ±(99.9%) 0.009 ms/op
Iteration   1: 3.391 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.696 ms/op
                 existUser·p0.50:   3.293 ms/op
                 existUser·p0.90:   3.875 ms/op
                 existUser·p0.95:   4.334 ms/op
                 existUser·p0.99:   5.939 ms/op
                 existUser·p0.999:  9.023 ms/op
                 existUser·p0.9999: 25.625 ms/op
                 existUser·p1.00:   26.182 ms/op

Iteration   2: 3.423 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.176 ms/op
                 existUser·p0.50:   3.322 ms/op
                 existUser·p0.90:   3.842 ms/op
                 existUser·p0.95:   4.211 ms/op
                 existUser·p0.99:   5.841 ms/op
                 existUser·p0.999:  22.884 ms/op
                 existUser·p0.9999: 26.793 ms/op
                 existUser·p1.00:   27.460 ms/op

Iteration   3: 3.521 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.477 ms/op
                 existUser·p0.50:   3.404 ms/op
                 existUser·p0.90:   4.018 ms/op
                 existUser·p0.95:   4.334 ms/op
                 existUser·p0.99:   6.767 ms/op
                 existUser·p0.999:  20.283 ms/op
                 existUser·p0.9999: 28.417 ms/op
                 existUser·p1.00:   29.393 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 278529
  mean =      3.444 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11715 
    [ 2.500,  5.000) = 260268 
    [ 5.000,  7.500) = 5473 
    [ 7.500, 10.000) = 596 
    [10.000, 12.500) = 78 
    [12.500, 15.000) = 120 
    [15.000, 17.500) = 22 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 46 
    [22.500, 25.000) = 106 
    [25.000, 27.500) = 84 

  Percentiles, ms/op:
      p(0.0000) =      1.176 ms/op
     p(50.0000) =      3.342 ms/op
     p(90.0000) =      3.924 ms/op
     p(95.0000) =      4.301 ms/op
     p(99.0000) =      6.152 ms/op
     p(99.9000) =     15.015 ms/op
     p(99.9900) =     27.179 ms/op
     p(99.9990) =     29.086 ms/op
     p(99.9999) =     29.393 ms/op
    p(100.0000) =     29.393 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 10.533 ±(99.9%) 0.128 ms/op
# Warmup Iteration   2: 3.822 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.683 ±(99.9%) 0.014 ms/op
Iteration   1: 3.573 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.079 ms/op
                 getUser·p0.50:   3.432 ms/op
                 getUser·p0.90:   4.035 ms/op
                 getUser·p0.95:   4.350 ms/op
                 getUser·p0.99:   6.767 ms/op
                 getUser·p0.999:  21.323 ms/op
                 getUser·p0.9999: 24.150 ms/op
                 getUser·p1.00:   24.642 ms/op

Iteration   2: 3.525 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.094 ms/op
                 getUser·p0.50:   3.412 ms/op
                 getUser·p0.90:   3.899 ms/op
                 getUser·p0.95:   4.141 ms/op
                 getUser·p0.99:   6.095 ms/op
                 getUser·p0.999:  23.187 ms/op
                 getUser·p0.9999: 27.394 ms/op
                 getUser·p1.00:   28.869 ms/op

Iteration   3: 3.563 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.775 ms/op
                 getUser·p0.50:   3.428 ms/op
                 getUser·p0.90:   4.035 ms/op
                 getUser·p0.95:   4.440 ms/op
                 getUser·p0.99:   7.537 ms/op
                 getUser·p0.999:  13.178 ms/op
                 getUser·p0.9999: 29.035 ms/op
                 getUser·p1.00:   30.376 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 270007
  mean =      3.553 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4521 
    [ 2.500,  5.000) = 257919 
    [ 5.000,  7.500) = 5843 
    [ 7.500, 10.000) = 1280 
    [10.000, 12.500) = 141 
    [12.500, 15.000) = 43 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 37 
    [22.500, 25.000) = 97 
    [25.000, 27.500) = 93 
    [27.500, 30.000) = 26 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.775 ms/op
     p(50.0000) =      3.424 ms/op
     p(90.0000) =      3.990 ms/op
     p(95.0000) =      4.309 ms/op
     p(99.0000) =      6.955 ms/op
     p(99.9000) =     13.827 ms/op
     p(99.9900) =     27.787 ms/op
     p(99.9990) =     30.078 ms/op
     p(99.9999) =     30.376 ms/op
    p(100.0000) =     30.376 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 12.338 ±(99.9%) 0.171 ms/op
# Warmup Iteration   2: 4.633 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.231 ±(99.9%) 0.013 ms/op
Iteration   1: 4.271 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.101 ms/op
                 listUser·p0.50:   4.178 ms/op
                 listUser·p0.90:   4.637 ms/op
                 listUser·p0.95:   4.899 ms/op
                 listUser·p0.99:   7.193 ms/op
                 listUser·p0.999:  22.137 ms/op
                 listUser·p0.9999: 25.478 ms/op
                 listUser·p1.00:   26.149 ms/op

Iteration   2: 4.174 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.650 ms/op
                 listUser·p0.50:   4.030 ms/op
                 listUser·p0.90:   4.579 ms/op
                 listUser·p0.95:   4.833 ms/op
                 listUser·p0.99:   7.266 ms/op
                 listUser·p0.999:  16.777 ms/op
                 listUser·p0.9999: 17.542 ms/op
                 listUser·p1.00:   18.416 ms/op

Iteration   3: 4.230 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.089 ms/op
                 listUser·p0.50:   4.133 ms/op
                 listUser·p0.90:   4.645 ms/op
                 listUser·p0.95:   4.882 ms/op
                 listUser·p0.99:   7.283 ms/op
                 listUser·p0.999:  15.942 ms/op
                 listUser·p0.9999: 17.447 ms/op
                 listUser·p1.00:   18.088 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 226997
  mean =      4.225 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 28 
    [ 2.500,  5.000) = 217827 
    [ 5.000,  7.500) = 7274 
    [ 7.500, 10.000) = 1058 
    [10.000, 12.500) = 171 
    [12.500, 15.000) = 228 
    [15.000, 17.500) = 254 
    [17.500, 20.000) = 36 
    [20.000, 22.500) = 56 
    [22.500, 25.000) = 50 
    [25.000, 27.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      2.089 ms/op
     p(50.0000) =      4.121 ms/op
     p(90.0000) =      4.620 ms/op
     p(95.0000) =      4.874 ms/op
     p(99.0000) =      7.234 ms/op
     p(99.9000) =     16.974 ms/op
     p(99.9900) =     24.527 ms/op
     p(99.9990) =     26.105 ms/op
     p(99.9999) =     26.149 ms/op
    p(100.0000) =     26.149 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.810 ± 4.664  ops/ms
ClientPb.existUser                       thrpt       3   9.484 ± 1.051  ops/ms
ClientPb.getUser                         thrpt       3   9.223 ± 1.805  ops/ms
ClientPb.listUser                        thrpt       3   7.529 ± 3.184  ops/ms
ClientPb.createUser                       avgt       3   3.512 ± 0.922   ms/op
ClientPb.existUser                        avgt       3   3.349 ± 0.323   ms/op
ClientPb.getUser                          avgt       3   3.640 ± 1.091   ms/op
ClientPb.listUser                         avgt       3   4.185 ± 0.560   ms/op
ClientPb.createUser                     sample  272339   3.523 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.962           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.404           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.022           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.334           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.390           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.285           ms/op
ClientPb.createUser:createUser·p0.9999  sample          38.797           ms/op
ClientPb.createUser:createUser·p1.00    sample          42.861           ms/op
ClientPb.existUser                      sample  278529   3.444 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.176           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.342           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.924           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.301           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.152           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.015           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.179           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.393           ms/op
ClientPb.getUser                        sample  270007   3.553 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.775           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.424           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.990           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.309           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.955           ms/op
ClientPb.getUser:getUser·p0.999         sample          13.827           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.787           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.376           ms/op
ClientPb.listUser                       sample  226997   4.225 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.089           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.121           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.620           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.874           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.234           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.974           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.527           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.149           ms/op
