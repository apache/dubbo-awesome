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
# Warmup Iteration   1: 1.581 ops/ms
# Warmup Iteration   2: 3.267 ops/ms
# Warmup Iteration   3: 6.794 ops/ms
Iteration   1: 7.411 ops/ms
Iteration   2: 7.719 ops/ms
Iteration   3: 7.896 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.676 ±(99.9%) 4.474 ops/ms [Average]
  (min, avg, max) = (7.411, 7.676, 7.896), stdev = 0.245
  CI (99.9%): [3.201, 12.150] (assumes normal distribution)


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
# Warmup Iteration   1: 1.988 ops/ms
# Warmup Iteration   2: 6.302 ops/ms
# Warmup Iteration   3: 7.818 ops/ms
Iteration   1: 8.200 ops/ms
Iteration   2: 8.291 ops/ms
Iteration   3: 8.206 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.232 ±(99.9%) 0.925 ops/ms [Average]
  (min, avg, max) = (8.200, 8.232, 8.291), stdev = 0.051
  CI (99.9%): [7.307, 9.158] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:05
# Fork: 1 of 1
# Warmup Iteration   1: 2.026 ops/ms
# Warmup Iteration   2: 6.141 ops/ms
# Warmup Iteration   3: 7.367 ops/ms
Iteration   1: 7.582 ops/ms
Iteration   2: 7.935 ops/ms
Iteration   3: 7.982 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.833 ±(99.9%) 3.988 ops/ms [Average]
  (min, avg, max) = (7.582, 7.833, 7.982), stdev = 0.219
  CI (99.9%): [3.845, 11.822] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:58
# Fork: 1 of 1
# Warmup Iteration   1: 1.967 ops/ms
# Warmup Iteration   2: 5.322 ops/ms
# Warmup Iteration   3: 6.509 ops/ms
Iteration   1: 6.455 ops/ms
Iteration   2: 6.727 ops/ms
Iteration   3: 6.349 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.510 ±(99.9%) 3.555 ops/ms [Average]
  (min, avg, max) = (6.349, 6.510, 6.727), stdev = 0.195
  CI (99.9%): [2.955, 10.065] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:52
# Fork: 1 of 1
# Warmup Iteration   1: 15.170 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 4.990 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.326 ±(99.9%) 0.004 ms/op
Iteration   1: 4.164 ±(99.9%) 0.008 ms/op
Iteration   2: 4.198 ±(99.9%) 0.007 ms/op
Iteration   3: 3.949 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.104 ±(99.9%) 2.464 ms/op [Average]
  (min, avg, max) = (3.949, 4.104, 4.198), stdev = 0.135
  CI (99.9%): [1.639, 6.568] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:46
# Fork: 1 of 1
# Warmup Iteration   1: 12.513 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 4.336 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.015 ±(99.9%) 0.007 ms/op
Iteration   1: 3.959 ±(99.9%) 0.005 ms/op
Iteration   2: 3.905 ±(99.9%) 0.003 ms/op
Iteration   3: 3.884 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.916 ±(99.9%) 0.706 ms/op [Average]
  (min, avg, max) = (3.884, 3.916, 3.959), stdev = 0.039
  CI (99.9%): [3.211, 4.622] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:39
# Fork: 1 of 1
# Warmup Iteration   1: 14.079 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 4.911 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.304 ±(99.9%) 0.006 ms/op
Iteration   1: 4.152 ±(99.9%) 0.005 ms/op
Iteration   2: 4.062 ±(99.9%) 0.011 ms/op
Iteration   3: 4.195 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.136 ±(99.9%) 1.236 ms/op [Average]
  (min, avg, max) = (4.062, 4.136, 4.195), stdev = 0.068
  CI (99.9%): [2.900, 5.372] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:32
# Fork: 1 of 1
# Warmup Iteration   1: 14.616 ±(99.9%) 0.064 ms/op
# Warmup Iteration   2: 5.557 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.816 ±(99.9%) 0.013 ms/op
Iteration   1: 4.845 ±(99.9%) 0.010 ms/op
Iteration   2: 4.775 ±(99.9%) 0.009 ms/op
Iteration   3: 4.973 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.864 ±(99.9%) 1.825 ms/op [Average]
  (min, avg, max) = (4.775, 4.864, 4.973), stdev = 0.100
  CI (99.9%): [3.039, 6.690] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:26
# Fork: 1 of 1
# Warmup Iteration   1: 13.851 ±(99.9%) 0.197 ms/op
# Warmup Iteration   2: 5.046 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 4.537 ±(99.9%) 0.020 ms/op
Iteration   1: 4.224 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.591 ms/op
                 createUser·p0.50:   3.985 ms/op
                 createUser·p0.90:   5.022 ms/op
                 createUser·p0.95:   5.751 ms/op
                 createUser·p0.99:   8.323 ms/op
                 createUser·p0.999:  24.389 ms/op
                 createUser·p0.9999: 32.604 ms/op
                 createUser·p1.00:   32.997 ms/op

Iteration   2: 4.101 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.571 ms/op
                 createUser·p0.50:   3.969 ms/op
                 createUser·p0.90:   4.702 ms/op
                 createUser·p0.95:   5.177 ms/op
                 createUser·p0.99:   8.069 ms/op
                 createUser·p0.999:  14.892 ms/op
                 createUser·p0.9999: 30.212 ms/op
                 createUser·p1.00:   30.736 ms/op

Iteration   3: 4.063 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.665 ms/op
                 createUser·p0.50:   3.883 ms/op
                 createUser·p0.90:   4.555 ms/op
                 createUser·p0.95:   5.079 ms/op
                 createUser·p0.99:   8.243 ms/op
                 createUser·p0.999:  28.974 ms/op
                 createUser·p0.9999: 32.190 ms/op
                 createUser·p1.00:   32.735 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 232534
  mean =      4.129 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 303 
    [ 2.500,  5.000) = 215480 
    [ 5.000,  7.500) = 13611 
    [ 7.500, 10.000) = 2158 
    [10.000, 12.500) = 510 
    [12.500, 15.000) = 173 
    [15.000, 17.500) = 33 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 66 
    [25.000, 27.500) = 42 
    [27.500, 30.000) = 61 
    [30.000, 32.500) = 77 
    [32.500, 35.000) = 14 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.571 ms/op
     p(50.0000) =      3.944 ms/op
     p(90.0000) =      4.784 ms/op
     p(95.0000) =      5.341 ms/op
     p(99.0000) =      8.217 ms/op
     p(99.9000) =     24.117 ms/op
     p(99.9900) =     31.727 ms/op
     p(99.9990) =     32.735 ms/op
     p(99.9999) =     32.997 ms/op
    p(100.0000) =     32.997 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 12.214 ±(99.9%) 0.167 ms/op
# Warmup Iteration   2: 4.808 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 4.155 ±(99.9%) 0.013 ms/op
Iteration   1: 4.083 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.776 ms/op
                 existUser·p0.50:   3.899 ms/op
                 existUser·p0.90:   4.538 ms/op
                 existUser·p0.95:   6.259 ms/op
                 existUser·p0.99:   8.552 ms/op
                 existUser·p0.999:  15.499 ms/op
                 existUser·p0.9999: 24.849 ms/op
                 existUser·p1.00:   26.313 ms/op

Iteration   2: 3.913 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.599 ms/op
                 existUser·p0.50:   3.715 ms/op
                 existUser·p0.90:   4.309 ms/op
                 existUser·p0.95:   4.989 ms/op
                 existUser·p0.99:   8.200 ms/op
                 existUser·p0.999:  23.101 ms/op
                 existUser·p0.9999: 29.164 ms/op
                 existUser·p1.00:   29.983 ms/op

Iteration   3: 4.051 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.925 ms/op
                 existUser·p0.50:   3.912 ms/op
                 existUser·p0.90:   4.473 ms/op
                 existUser·p0.95:   5.210 ms/op
                 existUser·p0.99:   8.208 ms/op
                 existUser·p0.999:  18.645 ms/op
                 existUser·p0.9999: 26.840 ms/op
                 existUser·p1.00:   27.099 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 239168
  mean =      4.014 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 170 
    [ 2.500,  5.000) = 224865 
    [ 5.000,  7.500) = 9349 
    [ 7.500, 10.000) = 3949 
    [10.000, 12.500) = 390 
    [12.500, 15.000) = 106 
    [15.000, 17.500) = 90 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 112 
    [25.000, 27.500) = 76 

  Percentiles, ms/op:
      p(0.0000) =      1.599 ms/op
     p(50.0000) =      3.867 ms/op
     p(90.0000) =      4.424 ms/op
     p(95.0000) =      5.325 ms/op
     p(99.0000) =      8.364 ms/op
     p(99.9000) =     18.645 ms/op
     p(99.9900) =     27.397 ms/op
     p(99.9990) =     29.531 ms/op
     p(99.9999) =     29.983 ms/op
    p(100.0000) =     29.983 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 14.529 ±(99.9%) 0.212 ms/op
# Warmup Iteration   2: 5.172 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 4.241 ±(99.9%) 0.014 ms/op
Iteration   1: 4.122 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.274 ms/op
                 getUser·p0.50:   3.908 ms/op
                 getUser·p0.90:   4.702 ms/op
                 getUser·p0.95:   5.872 ms/op
                 getUser·p0.99:   8.569 ms/op
                 getUser·p0.999:  18.967 ms/op
                 getUser·p0.9999: 24.428 ms/op
                 getUser·p1.00:   25.068 ms/op

Iteration   2: 3.984 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   2.212 ms/op
                 getUser·p0.50:   3.809 ms/op
                 getUser·p0.90:   4.391 ms/op
                 getUser·p0.95:   4.754 ms/op
                 getUser·p0.99:   7.452 ms/op
                 getUser·p0.999:  11.742 ms/op
                 getUser·p0.9999: 22.858 ms/op
                 getUser·p1.00:   23.429 ms/op

Iteration   3: 3.993 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   2.109 ms/op
                 getUser·p0.50:   3.842 ms/op
                 getUser·p0.90:   4.465 ms/op
                 getUser·p0.95:   4.760 ms/op
                 getUser·p0.99:   7.067 ms/op
                 getUser·p0.999:  23.854 ms/op
                 getUser·p0.9999: 26.608 ms/op
                 getUser·p1.00:   27.460 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 237947
  mean =      4.032 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 57 
    [ 2.500,  5.000) = 225780 
    [ 5.000,  7.500) = 9214 
    [ 7.500, 10.000) = 1864 
    [10.000, 12.500) = 603 
    [12.500, 15.000) = 127 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 68 
    [20.000, 22.500) = 83 
    [22.500, 25.000) = 74 
    [25.000, 27.500) = 53 

  Percentiles, ms/op:
      p(0.0000) =      1.274 ms/op
     p(50.0000) =      3.854 ms/op
     p(90.0000) =      4.506 ms/op
     p(95.0000) =      5.022 ms/op
     p(99.0000) =      7.807 ms/op
     p(99.9000) =     18.845 ms/op
     p(99.9900) =     25.599 ms/op
     p(99.9990) =     27.251 ms/op
     p(99.9999) =     27.460 ms/op
    p(100.0000) =     27.460 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 14.350 ±(99.9%) 0.216 ms/op
# Warmup Iteration   2: 5.225 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 5.034 ±(99.9%) 0.019 ms/op
Iteration   1: 4.785 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   2.372 ms/op
                 listUser·p0.50:   4.506 ms/op
                 listUser·p0.90:   5.325 ms/op
                 listUser·p0.95:   6.152 ms/op
                 listUser·p0.99:   9.732 ms/op
                 listUser·p0.999:  24.809 ms/op
                 listUser·p0.9999: 32.241 ms/op
                 listUser·p1.00:   33.096 ms/op

Iteration   2: 5.017 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   2.585 ms/op
                 listUser·p0.50:   4.751 ms/op
                 listUser·p0.90:   5.620 ms/op
                 listUser·p0.95:   7.206 ms/op
                 listUser·p0.99:   10.273 ms/op
                 listUser·p0.999:  20.724 ms/op
                 listUser·p0.9999: 23.691 ms/op
                 listUser·p1.00:   24.379 ms/op

Iteration   3: 4.787 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   2.150 ms/op
                 listUser·p0.50:   4.530 ms/op
                 listUser·p0.90:   5.300 ms/op
                 listUser·p0.95:   5.931 ms/op
                 listUser·p0.99:   9.585 ms/op
                 listUser·p0.999:  17.836 ms/op
                 listUser·p0.9999: 25.133 ms/op
                 listUser·p1.00:   25.199 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 197441
  mean =      4.861 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6 
    [ 2.500,  5.000) = 154400 
    [ 5.000,  7.500) = 35865 
    [ 7.500, 10.000) = 5255 
    [10.000, 12.500) = 1259 
    [12.500, 15.000) = 203 
    [15.000, 17.500) = 165 
    [17.500, 20.000) = 49 
    [20.000, 22.500) = 57 
    [22.500, 25.000) = 105 
    [25.000, 27.500) = 45 
    [27.500, 30.000) = 10 
    [30.000, 32.500) = 19 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.150 ms/op
     p(50.0000) =      4.588 ms/op
     p(90.0000) =      5.415 ms/op
     p(95.0000) =      6.480 ms/op
     p(99.0000) =      9.938 ms/op
     p(99.9000) =     21.827 ms/op
     p(99.9900) =     30.204 ms/op
     p(99.9990) =     32.617 ms/op
     p(99.9999) =     33.096 ms/op
    p(100.0000) =     33.096 ms/op


# Run complete. Total time: 00:13:19

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.676 ± 4.474  ops/ms
ClientPb.existUser                       thrpt       3   8.232 ± 0.925  ops/ms
ClientPb.getUser                         thrpt       3   7.833 ± 3.988  ops/ms
ClientPb.listUser                        thrpt       3   6.510 ± 3.555  ops/ms
ClientPb.createUser                       avgt       3   4.104 ± 2.464   ms/op
ClientPb.existUser                        avgt       3   3.916 ± 0.706   ms/op
ClientPb.getUser                          avgt       3   4.136 ± 1.236   ms/op
ClientPb.listUser                         avgt       3   4.864 ± 1.825   ms/op
ClientPb.createUser                     sample  232534   4.129 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.571           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.944           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.784           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.341           ms/op
ClientPb.createUser:createUser·p0.99    sample           8.217           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.117           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.727           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.997           ms/op
ClientPb.existUser                      sample  239168   4.014 ± 0.008   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.599           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.867           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.424           ms/op
ClientPb.existUser:existUser·p0.95      sample           5.325           ms/op
ClientPb.existUser:existUser·p0.99      sample           8.364           ms/op
ClientPb.existUser:existUser·p0.999     sample          18.645           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.397           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.983           ms/op
ClientPb.getUser                        sample  237947   4.032 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.274           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.854           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.506           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.022           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.807           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.845           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.599           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.460           ms/op
ClientPb.listUser                       sample  197441   4.861 ± 0.009   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.150           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.588           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.415           ms/op
ClientPb.listUser:listUser·p0.95        sample           6.480           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.938           ms/op
ClientPb.listUser:listUser·p0.999       sample          21.827           ms/op
ClientPb.listUser:listUser·p0.9999      sample          30.204           ms/op
ClientPb.listUser:listUser·p1.00        sample          33.096           ms/op
