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
# Warmup Iteration   1: 2.568 ops/ms
# Warmup Iteration   2: 7.190 ops/ms
# Warmup Iteration   3: 9.157 ops/ms
Iteration   1: 9.786 ops/ms
Iteration   2: 9.931 ops/ms
Iteration   3: 10.191 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.969 ±(99.9%) 3.740 ops/ms [Average]
  (min, avg, max) = (9.786, 9.969, 10.191), stdev = 0.205
  CI (99.9%): [6.230, 13.709] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.271 ops/ms
# Warmup Iteration   2: 9.459 ops/ms
# Warmup Iteration   3: 10.260 ops/ms
Iteration   1: 10.516 ops/ms
Iteration   2: 10.086 ops/ms
Iteration   3: 10.613 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.405 ±(99.9%) 5.108 ops/ms [Average]
  (min, avg, max) = (10.086, 10.405, 10.613), stdev = 0.280
  CI (99.9%): [5.297, 15.513] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.725 ops/ms
# Warmup Iteration   2: 9.179 ops/ms
# Warmup Iteration   3: 10.072 ops/ms
Iteration   1: 10.420 ops/ms
Iteration   2: 10.148 ops/ms
Iteration   3: 10.263 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.277 ±(99.9%) 2.496 ops/ms [Average]
  (min, avg, max) = (10.148, 10.277, 10.420), stdev = 0.137
  CI (99.9%): [7.781, 12.773] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.655 ops/ms
# Warmup Iteration   2: 7.821 ops/ms
# Warmup Iteration   3: 8.366 ops/ms
Iteration   1: 8.528 ops/ms
Iteration   2: 8.506 ops/ms
Iteration   3: 8.610 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.548 ±(99.9%) 0.997 ops/ms [Average]
  (min, avg, max) = (8.506, 8.548, 8.610), stdev = 0.055
  CI (99.9%): [7.551, 9.545] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 8.486 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.528 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.400 ±(99.9%) 0.003 ms/op
Iteration   1: 3.079 ±(99.9%) 0.006 ms/op
Iteration   2: 3.184 ±(99.9%) 0.006 ms/op
Iteration   3: 3.173 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.145 ±(99.9%) 1.055 ms/op [Average]
  (min, avg, max) = (3.079, 3.145, 3.184), stdev = 0.058
  CI (99.9%): [2.090, 4.200] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 7.027 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.306 ±(99.9%) 0.001 ms/op
# Warmup Iteration   3: 3.116 ±(99.9%) 0.006 ms/op
Iteration   1: 2.975 ±(99.9%) 0.006 ms/op
Iteration   2: 3.133 ±(99.9%) 0.003 ms/op
Iteration   3: 2.984 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.031 ±(99.9%) 1.623 ms/op [Average]
  (min, avg, max) = (2.975, 3.031, 3.133), stdev = 0.089
  CI (99.9%): [1.408, 4.653] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 7.058 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.454 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.199 ±(99.9%) 0.005 ms/op
Iteration   1: 3.157 ±(99.9%) 0.007 ms/op
Iteration   2: 3.135 ±(99.9%) 0.003 ms/op
Iteration   3: 3.254 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.182 ±(99.9%) 1.156 ms/op [Average]
  (min, avg, max) = (3.135, 3.182, 3.254), stdev = 0.063
  CI (99.9%): [2.026, 4.338] (assumes normal distribution)


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
# Warmup Iteration   1: 8.074 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.963 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.733 ±(99.9%) 0.006 ms/op
Iteration   1: 3.749 ±(99.9%) 0.007 ms/op
Iteration   2: 3.716 ±(99.9%) 0.005 ms/op
Iteration   3: 3.717 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.727 ±(99.9%) 0.337 ms/op [Average]
  (min, avg, max) = (3.716, 3.727, 3.749), stdev = 0.018
  CI (99.9%): [3.390, 4.064] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 7.607 ±(99.9%) 0.091 ms/op
# Warmup Iteration   2: 3.660 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.263 ±(99.9%) 0.009 ms/op
Iteration   1: 3.257 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.255 ms/op
                 createUser·p0.50:   3.195 ms/op
                 createUser·p0.90:   3.674 ms/op
                 createUser·p0.95:   4.415 ms/op
                 createUser·p0.99:   5.489 ms/op
                 createUser·p0.999:  10.863 ms/op
                 createUser·p0.9999: 21.383 ms/op
                 createUser·p1.00:   22.413 ms/op

Iteration   2: 3.101 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.011 ms/op
                 createUser·p0.50:   3.113 ms/op
                 createUser·p0.90:   3.289 ms/op
                 createUser·p0.95:   3.535 ms/op
                 createUser·p0.99:   4.235 ms/op
                 createUser·p0.999:  13.924 ms/op
                 createUser·p0.9999: 21.529 ms/op
                 createUser·p1.00:   22.118 ms/op

Iteration   3: 3.142 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.421 ms/op
                 createUser·p0.50:   3.064 ms/op
                 createUser·p0.90:   3.404 ms/op
                 createUser·p0.95:   3.699 ms/op
                 createUser·p0.99:   5.612 ms/op
                 createUser·p0.999:  11.460 ms/op
                 createUser·p0.9999: 20.108 ms/op
                 createUser·p1.00:   20.546 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 303196
  mean =      3.165 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24366 
    [ 2.500,  5.000) = 273296 
    [ 5.000,  7.500) = 4870 
    [ 7.500, 10.000) = 320 
    [10.000, 12.500) = 29 
    [12.500, 15.000) = 39 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 139 
    [20.000, 22.500) = 113 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.255 ms/op
     p(50.0000) =      3.138 ms/op
     p(90.0000) =      3.424 ms/op
     p(95.0000) =      3.801 ms/op
     p(99.0000) =      5.431 ms/op
     p(99.9000) =     13.609 ms/op
     p(99.9900) =     21.299 ms/op
     p(99.9990) =     22.182 ms/op
     p(99.9999) =     22.413 ms/op
    p(100.0000) =     22.413 ms/op


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
# Warmup Iteration   1: 7.273 ±(99.9%) 0.086 ms/op
# Warmup Iteration   2: 3.328 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.088 ±(99.9%) 0.007 ms/op
Iteration   1: 3.037 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.188 ms/op
                 existUser·p0.50:   2.929 ms/op
                 existUser·p0.90:   3.281 ms/op
                 existUser·p0.95:   3.621 ms/op
                 existUser·p0.99:   5.325 ms/op
                 existUser·p0.999:  9.634 ms/op
                 existUser·p0.9999: 22.184 ms/op
                 existUser·p1.00:   22.970 ms/op

Iteration   2: 3.075 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.057 ms/op
                 existUser·p0.50:   3.043 ms/op
                 existUser·p0.90:   3.260 ms/op
                 existUser·p0.95:   3.531 ms/op
                 existUser·p0.99:   5.341 ms/op
                 existUser·p0.999:  14.072 ms/op
                 existUser·p0.9999: 22.728 ms/op
                 existUser·p1.00:   24.019 ms/op

Iteration   3: 3.059 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.565 ms/op
                 existUser·p0.50:   3.060 ms/op
                 existUser·p0.90:   3.289 ms/op
                 existUser·p0.95:   3.490 ms/op
                 existUser·p0.99:   5.054 ms/op
                 existUser·p0.999:  12.550 ms/op
                 existUser·p0.9999: 19.449 ms/op
                 existUser·p1.00:   21.004 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 314011
  mean =      3.057 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21924 
    [ 2.500,  5.000) = 286982 
    [ 5.000,  7.500) = 4302 
    [ 7.500, 10.000) = 381 
    [10.000, 12.500) = 71 
    [12.500, 15.000) = 68 
    [15.000, 17.500) = 56 
    [17.500, 20.000) = 82 
    [20.000, 22.500) = 127 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.057 ms/op
     p(50.0000) =      3.019 ms/op
     p(90.0000) =      3.277 ms/op
     p(95.0000) =      3.535 ms/op
     p(99.0000) =      5.259 ms/op
     p(99.9000) =     13.451 ms/op
     p(99.9900) =     22.151 ms/op
     p(99.9990) =     23.874 ms/op
     p(99.9999) =     24.019 ms/op
    p(100.0000) =     24.019 ms/op


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
# Warmup Iteration   1: 7.780 ±(99.9%) 0.093 ms/op
# Warmup Iteration   2: 3.507 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.322 ±(99.9%) 0.010 ms/op
Iteration   1: 3.152 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.055 ms/op
                 getUser·p0.50:   3.047 ms/op
                 getUser·p0.90:   3.424 ms/op
                 getUser·p0.95:   3.727 ms/op
                 getUser·p0.99:   5.825 ms/op
                 getUser·p0.999:  9.896 ms/op
                 getUser·p0.9999: 20.830 ms/op
                 getUser·p1.00:   21.692 ms/op

Iteration   2: 3.176 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.214 ms/op
                 getUser·p0.50:   3.105 ms/op
                 getUser·p0.90:   3.502 ms/op
                 getUser·p0.95:   3.645 ms/op
                 getUser·p0.99:   5.390 ms/op
                 getUser·p0.999:  19.956 ms/op
                 getUser·p0.9999: 23.689 ms/op
                 getUser·p1.00:   24.379 ms/op

Iteration   3: 3.283 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.309 ms/op
                 getUser·p0.50:   3.199 ms/op
                 getUser·p0.90:   3.777 ms/op
                 getUser·p0.95:   4.149 ms/op
                 getUser·p0.99:   5.800 ms/op
                 getUser·p0.999:  13.937 ms/op
                 getUser·p0.9999: 19.211 ms/op
                 getUser·p1.00:   19.497 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 299505
  mean =      3.203 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14934 
    [ 2.500,  5.000) = 278499 
    [ 5.000,  7.500) = 5234 
    [ 7.500, 10.000) = 383 
    [10.000, 12.500) = 113 
    [12.500, 15.000) = 38 
    [15.000, 17.500) = 46 
    [17.500, 20.000) = 138 
    [20.000, 22.500) = 79 
    [22.500, 25.000) = 41 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.055 ms/op
     p(50.0000) =      3.129 ms/op
     p(90.0000) =      3.588 ms/op
     p(95.0000) =      3.875 ms/op
     p(99.0000) =      5.693 ms/op
     p(99.9000) =     15.270 ms/op
     p(99.9900) =     22.905 ms/op
     p(99.9990) =     24.019 ms/op
     p(99.9999) =     24.379 ms/op
    p(100.0000) =     24.379 ms/op


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
# Warmup Iteration   1: 8.276 ±(99.9%) 0.102 ms/op
# Warmup Iteration   2: 4.007 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.756 ±(99.9%) 0.010 ms/op
Iteration   1: 3.804 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.733 ms/op
                 listUser·p0.50:   3.682 ms/op
                 listUser·p0.90:   4.235 ms/op
                 listUser·p0.95:   4.915 ms/op
                 listUser·p0.99:   6.799 ms/op
                 listUser·p0.999:  15.446 ms/op
                 listUser·p0.9999: 19.214 ms/op
                 listUser·p1.00:   21.037 ms/op

Iteration   2: 3.708 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.554 ms/op
                 listUser·p0.50:   3.576 ms/op
                 listUser·p0.90:   3.990 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   6.676 ms/op
                 listUser·p0.999:  13.857 ms/op
                 listUser·p0.9999: 17.727 ms/op
                 listUser·p1.00:   17.760 ms/op

Iteration   3: 3.630 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.257 ms/op
                 listUser·p0.50:   3.514 ms/op
                 listUser·p0.90:   3.883 ms/op
                 listUser·p0.95:   4.088 ms/op
                 listUser·p0.99:   6.652 ms/op
                 listUser·p0.999:  13.091 ms/op
                 listUser·p0.9999: 16.384 ms/op
                 listUser·p1.00:   18.186 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 258358
  mean =      3.713 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 74 
    [ 2.500,  5.000) = 248945 
    [ 5.000,  7.500) = 7905 
    [ 7.500, 10.000) = 717 
    [10.000, 12.500) = 291 
    [12.500, 15.000) = 207 
    [15.000, 17.500) = 166 
    [17.500, 20.000) = 51 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.554 ms/op
     p(50.0000) =      3.600 ms/op
     p(90.0000) =      4.014 ms/op
     p(95.0000) =      4.415 ms/op
     p(99.0000) =      6.701 ms/op
     p(99.9000) =     14.107 ms/op
     p(99.9900) =     18.061 ms/op
     p(99.9990) =     19.874 ms/op
     p(99.9999) =     21.037 ms/op
    p(100.0000) =     21.037 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.969 ± 3.740  ops/ms
ClientPb.existUser                       thrpt       3  10.405 ± 5.108  ops/ms
ClientPb.getUser                         thrpt       3  10.277 ± 2.496  ops/ms
ClientPb.listUser                        thrpt       3   8.548 ± 0.997  ops/ms
ClientPb.createUser                       avgt       3   3.145 ± 1.055   ms/op
ClientPb.existUser                        avgt       3   3.031 ± 1.623   ms/op
ClientPb.getUser                          avgt       3   3.182 ± 1.156   ms/op
ClientPb.listUser                         avgt       3   3.727 ± 0.337   ms/op
ClientPb.createUser                     sample  303196   3.165 ± 0.004   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.255           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.138           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.424           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.801           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.431           ms/op
ClientPb.createUser:createUser·p0.999   sample          13.609           ms/op
ClientPb.createUser:createUser·p0.9999  sample          21.299           ms/op
ClientPb.createUser:createUser·p1.00    sample          22.413           ms/op
ClientPb.existUser                      sample  314011   3.057 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.057           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.019           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.277           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.535           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.259           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.451           ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.151           ms/op
ClientPb.existUser:existUser·p1.00      sample          24.019           ms/op
ClientPb.getUser                        sample  299505   3.203 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.055           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.129           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.588           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.875           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.693           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.270           ms/op
ClientPb.getUser:getUser·p0.9999        sample          22.905           ms/op
ClientPb.getUser:getUser·p1.00          sample          24.379           ms/op
ClientPb.listUser                       sample  258358   3.713 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.554           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.600           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.014           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.415           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.701           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.107           ms/op
ClientPb.listUser:listUser·p0.9999      sample          18.061           ms/op
ClientPb.listUser:listUser·p1.00        sample          21.037           ms/op
