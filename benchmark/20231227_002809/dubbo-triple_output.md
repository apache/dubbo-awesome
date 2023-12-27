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
# Warmup Iteration   1: 5.069 ops/ms
# Warmup Iteration   2: 12.113 ops/ms
# Warmup Iteration   3: 12.210 ops/ms
Iteration   1: 12.440 ops/ms
Iteration   2: 12.409 ops/ms
Iteration   3: 12.549 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.466 ±(99.9%) 1.339 ops/ms [Average]
  (min, avg, max) = (12.409, 12.466, 12.549), stdev = 0.073
  CI (99.9%): [11.127, 13.805] (assumes normal distribution)


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
# Warmup Iteration   1: 7.802 ops/ms
# Warmup Iteration   2: 12.666 ops/ms
# Warmup Iteration   3: 12.865 ops/ms
Iteration   1: 12.894 ops/ms
Iteration   2: 12.928 ops/ms
Iteration   3: 12.995 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.939 ±(99.9%) 0.937 ops/ms [Average]
  (min, avg, max) = (12.894, 12.939, 12.995), stdev = 0.051
  CI (99.9%): [12.001, 13.876] (assumes normal distribution)


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
# Warmup Iteration   1: 7.264 ops/ms
# Warmup Iteration   2: 12.676 ops/ms
# Warmup Iteration   3: 12.928 ops/ms
Iteration   1: 12.859 ops/ms
Iteration   2: 12.769 ops/ms
Iteration   3: 12.909 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.845 ±(99.9%) 1.291 ops/ms [Average]
  (min, avg, max) = (12.769, 12.845, 12.909), stdev = 0.071
  CI (99.9%): [11.555, 14.136] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 6.231 ops/ms
# Warmup Iteration   2: 10.152 ops/ms
# Warmup Iteration   3: 10.358 ops/ms
Iteration   1: 10.362 ops/ms
Iteration   2: 10.430 ops/ms
Iteration   3: 10.360 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.384 ±(99.9%) 0.729 ops/ms [Average]
  (min, avg, max) = (10.360, 10.384, 10.430), stdev = 0.040
  CI (99.9%): [9.655, 11.113] (assumes normal distribution)


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
# Warmup Iteration   1: 4.305 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 2.589 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.542 ±(99.9%) 0.004 ms/op
Iteration   1: 2.510 ±(99.9%) 0.004 ms/op
Iteration   2: 2.534 ±(99.9%) 0.004 ms/op
Iteration   3: 2.537 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.527 ±(99.9%) 0.271 ms/op [Average]
  (min, avg, max) = (2.510, 2.527, 2.537), stdev = 0.015
  CI (99.9%): [2.256, 2.799] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:34
# Fork: 1 of 1
# Warmup Iteration   1: 3.775 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.555 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.522 ±(99.9%) 0.003 ms/op
Iteration   1: 2.504 ±(99.9%) 0.005 ms/op
Iteration   2: 2.509 ±(99.9%) 0.003 ms/op
Iteration   3: 2.502 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.505 ±(99.9%) 0.071 ms/op [Average]
  (min, avg, max) = (2.502, 2.505, 2.509), stdev = 0.004
  CI (99.9%): [2.434, 2.576] (assumes normal distribution)


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
# Warmup Iteration   1: 4.012 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.577 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.521 ±(99.9%) 0.005 ms/op
Iteration   1: 2.511 ±(99.9%) 0.004 ms/op
Iteration   2: 2.517 ±(99.9%) 0.004 ms/op
Iteration   3: 2.527 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.518 ±(99.9%) 0.150 ms/op [Average]
  (min, avg, max) = (2.511, 2.518, 2.527), stdev = 0.008
  CI (99.9%): [2.368, 2.668] (assumes normal distribution)


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
# Warmup Iteration   1: 4.851 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.106 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.088 ±(99.9%) 0.006 ms/op
Iteration   1: 3.056 ±(99.9%) 0.006 ms/op
Iteration   2: 3.099 ±(99.9%) 0.005 ms/op
Iteration   3: 3.067 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.074 ±(99.9%) 0.413 ms/op [Average]
  (min, avg, max) = (3.056, 3.074, 3.099), stdev = 0.023
  CI (99.9%): [2.661, 3.487] (assumes normal distribution)


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
# Warmup Iteration   1: 4.238 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.717 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.538 ±(99.9%) 0.006 ms/op
Iteration   1: 2.530 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.010 ms/op
                 createUser·p0.50:   2.560 ms/op
                 createUser·p0.90:   3.088 ms/op
                 createUser·p0.95:   3.207 ms/op
                 createUser·p0.99:   3.707 ms/op
                 createUser·p0.999:  12.029 ms/op
                 createUser·p0.9999: 23.235 ms/op
                 createUser·p1.00:   23.986 ms/op

Iteration   2: 2.558 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.110 ms/op
                 createUser·p0.50:   2.634 ms/op
                 createUser·p0.90:   3.109 ms/op
                 createUser·p0.95:   3.219 ms/op
                 createUser·p0.99:   3.686 ms/op
                 createUser·p0.999:  9.781 ms/op
                 createUser·p0.9999: 14.328 ms/op
                 createUser·p1.00:   16.073 ms/op

Iteration   3: 2.563 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.083 ms/op
                 createUser·p0.50:   2.613 ms/op
                 createUser·p0.90:   3.129 ms/op
                 createUser·p0.95:   3.252 ms/op
                 createUser·p0.99:   3.854 ms/op
                 createUser·p0.999:  8.779 ms/op
                 createUser·p0.9999: 10.792 ms/op
                 createUser·p1.00:   12.304 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 376139
  mean =      2.550 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 180893 
    [ 2.500,  5.000) = 194525 
    [ 5.000,  7.500) = 300 
    [ 7.500, 10.000) = 165 
    [10.000, 12.500) = 120 
    [12.500, 15.000) = 101 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.010 ms/op
     p(50.0000) =      2.601 ms/op
     p(90.0000) =      3.109 ms/op
     p(95.0000) =      3.228 ms/op
     p(99.0000) =      3.752 ms/op
     p(99.9000) =      8.859 ms/op
     p(99.9900) =     14.562 ms/op
     p(99.9990) =     23.871 ms/op
     p(99.9999) =     23.986 ms/op
    p(100.0000) =     23.986 ms/op


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
# Warmup Iteration   1: 3.806 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.467 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.426 ±(99.9%) 0.006 ms/op
Iteration   1: 2.436 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.840 ms/op
                 existUser·p0.50:   2.486 ms/op
                 existUser·p0.90:   2.957 ms/op
                 existUser·p0.95:   3.064 ms/op
                 existUser·p0.99:   3.580 ms/op
                 existUser·p0.999:  7.266 ms/op
                 existUser·p0.9999: 17.388 ms/op
                 existUser·p1.00:   17.826 ms/op

Iteration   2: 2.407 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.071 ms/op
                 existUser·p0.50:   2.441 ms/op
                 existUser·p0.90:   2.933 ms/op
                 existUser·p0.95:   3.047 ms/op
                 existUser·p0.99:   3.572 ms/op
                 existUser·p0.999:  6.817 ms/op
                 existUser·p0.9999: 13.650 ms/op
                 existUser·p1.00:   14.811 ms/op

Iteration   3: 2.447 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.037 ms/op
                 existUser·p0.50:   2.540 ms/op
                 existUser·p0.90:   2.978 ms/op
                 existUser·p0.95:   3.092 ms/op
                 existUser·p0.99:   3.699 ms/op
                 existUser·p0.999:  5.893 ms/op
                 existUser·p0.9999: 11.467 ms/op
                 existUser·p1.00:   11.747 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 394707
  mean =      2.430 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 58 
    [ 1.250,  2.500) = 199283 
    [ 2.500,  3.750) = 192142 
    [ 3.750,  5.000) = 2485 
    [ 5.000,  6.250) = 341 
    [ 6.250,  7.500) = 44 
    [ 7.500,  8.750) = 22 
    [ 8.750, 10.000) = 65 
    [10.000, 11.250) = 84 
    [11.250, 12.500) = 41 
    [12.500, 13.750) = 37 
    [13.750, 15.000) = 61 
    [15.000, 16.250) = 16 
    [16.250, 17.500) = 20 
    [17.500, 18.750) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.840 ms/op
     p(50.0000) =      2.482 ms/op
     p(90.0000) =      2.957 ms/op
     p(95.0000) =      3.068 ms/op
     p(99.0000) =      3.621 ms/op
     p(99.9000) =      6.310 ms/op
     p(99.9900) =     15.524 ms/op
     p(99.9990) =     17.629 ms/op
     p(99.9999) =     17.826 ms/op
    p(100.0000) =     17.826 ms/op


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
# Warmup Iteration   1: 4.089 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.629 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.548 ±(99.9%) 0.006 ms/op
Iteration   1: 2.516 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.682 ms/op
                 getUser·p0.50:   2.540 ms/op
                 getUser·p0.90:   3.068 ms/op
                 getUser·p0.95:   3.191 ms/op
                 getUser·p0.99:   3.682 ms/op
                 getUser·p0.999:  11.639 ms/op
                 getUser·p0.9999: 15.018 ms/op
                 getUser·p1.00:   15.794 ms/op

Iteration   2: 2.543 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.958 ms/op
                 getUser·p0.50:   2.560 ms/op
                 getUser·p0.90:   3.105 ms/op
                 getUser·p0.95:   3.260 ms/op
                 getUser·p0.99:   4.086 ms/op
                 getUser·p0.999:  10.052 ms/op
                 getUser·p0.9999: 14.434 ms/op
                 getUser·p1.00:   14.762 ms/op

Iteration   3: 2.533 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.952 ms/op
                 getUser·p0.50:   2.548 ms/op
                 getUser·p0.90:   3.088 ms/op
                 getUser·p0.95:   3.228 ms/op
                 getUser·p0.99:   4.088 ms/op
                 getUser·p0.999:  8.913 ms/op
                 getUser·p0.9999: 11.590 ms/op
                 getUser·p1.00:   12.337 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 379060
  mean =      2.530 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 103 
    [ 1.250,  2.500) = 185213 
    [ 2.500,  3.750) = 188590 
    [ 3.750,  5.000) = 4187 
    [ 5.000,  6.250) = 518 
    [ 6.250,  7.500) = 60 
    [ 7.500,  8.750) = 5 
    [ 8.750, 10.000) = 73 
    [10.000, 11.250) = 92 
    [11.250, 12.500) = 65 
    [12.500, 13.750) = 56 
    [13.750, 15.000) = 86 
    [15.000, 16.250) = 12 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.682 ms/op
     p(50.0000) =      2.552 ms/op
     p(90.0000) =      3.088 ms/op
     p(95.0000) =      3.224 ms/op
     p(99.0000) =      3.936 ms/op
     p(99.9000) =      8.945 ms/op
     p(99.9900) =     14.601 ms/op
     p(99.9990) =     15.335 ms/op
     p(99.9999) =     15.794 ms/op
    p(100.0000) =     15.794 ms/op


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
# Warmup Iteration   1: 4.754 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.122 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.089 ±(99.9%) 0.009 ms/op
Iteration   1: 3.050 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.914 ms/op
                 listUser·p0.50:   2.998 ms/op
                 listUser·p0.90:   3.912 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   5.595 ms/op
                 listUser·p0.999:  8.815 ms/op
                 listUser·p0.9999: 11.141 ms/op
                 listUser·p1.00:   12.239 ms/op

Iteration   2: 3.048 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.788 ms/op
                 listUser·p0.50:   2.974 ms/op
                 listUser·p0.90:   3.936 ms/op
                 listUser·p0.95:   4.465 ms/op
                 listUser·p0.99:   5.857 ms/op
                 listUser·p0.999:  10.357 ms/op
                 listUser·p0.9999: 11.862 ms/op
                 listUser·p1.00:   12.059 ms/op

Iteration   3: 2.996 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.881 ms/op
                 listUser·p0.50:   2.925 ms/op
                 listUser·p0.90:   3.850 ms/op
                 listUser·p0.95:   4.350 ms/op
                 listUser·p0.99:   5.710 ms/op
                 listUser·p0.999:  9.475 ms/op
                 listUser·p0.9999: 11.043 ms/op
                 listUser·p1.00:   11.993 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 316454
  mean =      3.031 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 116 
    [ 1.250,  2.500) = 88228 
    [ 2.500,  3.750) = 188135 
    [ 3.750,  5.000) = 32089 
    [ 5.000,  6.250) = 6278 
    [ 6.250,  7.500) = 888 
    [ 7.500,  8.750) = 215 
    [ 8.750, 10.000) = 274 
    [10.000, 11.250) = 178 
    [11.250, 12.500) = 53 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.788 ms/op
     p(50.0000) =      2.966 ms/op
     p(90.0000) =      3.899 ms/op
     p(95.0000) =      4.399 ms/op
     p(99.0000) =      5.710 ms/op
     p(99.9000) =      9.601 ms/op
     p(99.9900) =     11.731 ms/op
     p(99.9990) =     12.051 ms/op
     p(99.9999) =     12.239 ms/op
    p(100.0000) =     12.239 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.466 ± 1.339  ops/ms
ClientPb.existUser                       thrpt       3  12.939 ± 0.937  ops/ms
ClientPb.getUser                         thrpt       3  12.845 ± 1.291  ops/ms
ClientPb.listUser                        thrpt       3  10.384 ± 0.729  ops/ms
ClientPb.createUser                       avgt       3   2.527 ± 0.271   ms/op
ClientPb.existUser                        avgt       3   2.505 ± 0.071   ms/op
ClientPb.getUser                          avgt       3   2.518 ± 0.150   ms/op
ClientPb.listUser                         avgt       3   3.074 ± 0.413   ms/op
ClientPb.createUser                     sample  376139   2.550 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.010           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.601           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.109           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.228           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.752           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.859           ms/op
ClientPb.createUser:createUser·p0.9999  sample          14.562           ms/op
ClientPb.createUser:createUser·p1.00    sample          23.986           ms/op
ClientPb.existUser                      sample  394707   2.430 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.840           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.482           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.957           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.068           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.621           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.310           ms/op
ClientPb.existUser:existUser·p0.9999    sample          15.524           ms/op
ClientPb.existUser:existUser·p1.00      sample          17.826           ms/op
ClientPb.getUser                        sample  379060   2.530 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.682           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.552           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.088           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.224           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.936           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.945           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.601           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.794           ms/op
ClientPb.listUser                       sample  316454   3.031 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.788           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.966           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.899           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.399           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.710           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.601           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.731           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.239           ms/op
