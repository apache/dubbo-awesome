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
# Warmup Iteration   1: 2.224 ops/ms
# Warmup Iteration   2: 5.346 ops/ms
# Warmup Iteration   3: 8.626 ops/ms
Iteration   1: 8.979 ops/ms
Iteration   2: 9.440 ops/ms
Iteration   3: 9.240 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.220 ±(99.9%) 4.225 ops/ms [Average]
  (min, avg, max) = (8.979, 9.220, 9.440), stdev = 0.232
  CI (99.9%): [4.995, 13.444] (assumes normal distribution)


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
# Warmup Iteration   1: 2.784 ops/ms
# Warmup Iteration   2: 8.746 ops/ms
# Warmup Iteration   3: 9.172 ops/ms
Iteration   1: 9.454 ops/ms
Iteration   2: 9.814 ops/ms
Iteration   3: 10.039 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.769 ±(99.9%) 5.384 ops/ms [Average]
  (min, avg, max) = (9.454, 9.769, 10.039), stdev = 0.295
  CI (99.9%): [4.385, 15.153] (assumes normal distribution)


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
# Warmup Iteration   1: 3.257 ops/ms
# Warmup Iteration   2: 8.139 ops/ms
# Warmup Iteration   3: 8.980 ops/ms
Iteration   1: 9.137 ops/ms
Iteration   2: 9.493 ops/ms
Iteration   3: 9.497 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.375 ±(99.9%) 3.772 ops/ms [Average]
  (min, avg, max) = (9.137, 9.375, 9.497), stdev = 0.207
  CI (99.9%): [5.603, 13.148] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 2.954 ops/ms
# Warmup Iteration   2: 7.165 ops/ms
# Warmup Iteration   3: 7.982 ops/ms
Iteration   1: 8.319 ops/ms
Iteration   2: 8.120 ops/ms
Iteration   3: 8.200 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.213 ±(99.9%) 1.822 ops/ms [Average]
  (min, avg, max) = (8.120, 8.213, 8.319), stdev = 0.100
  CI (99.9%): [6.391, 10.035] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 9.737 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.855 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.523 ±(99.9%) 0.011 ms/op
Iteration   1: 3.367 ±(99.9%) 0.010 ms/op
Iteration   2: 3.379 ±(99.9%) 0.008 ms/op
Iteration   3: 3.432 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.392 ±(99.9%) 0.632 ms/op [Average]
  (min, avg, max) = (3.367, 3.392, 3.432), stdev = 0.035
  CI (99.9%): [2.760, 4.025] (assumes normal distribution)


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
# Warmup Iteration   1: 8.214 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.521 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.304 ±(99.9%) 0.006 ms/op
Iteration   1: 3.188 ±(99.9%) 0.011 ms/op
Iteration   2: 3.286 ±(99.9%) 0.005 ms/op
Iteration   3: 3.188 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.221 ±(99.9%) 1.035 ms/op [Average]
  (min, avg, max) = (3.188, 3.221, 3.286), stdev = 0.057
  CI (99.9%): [2.186, 4.256] (assumes normal distribution)


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
# Warmup Iteration   1: 9.694 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.746 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.579 ±(99.9%) 0.005 ms/op
Iteration   1: 3.401 ±(99.9%) 0.009 ms/op
Iteration   2: 3.349 ±(99.9%) 0.009 ms/op
Iteration   3: 3.416 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.389 ±(99.9%) 0.643 ms/op [Average]
  (min, avg, max) = (3.349, 3.389, 3.416), stdev = 0.035
  CI (99.9%): [2.746, 4.032] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 10.435 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 4.233 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.101 ±(99.9%) 0.006 ms/op
Iteration   1: 3.868 ±(99.9%) 0.014 ms/op
Iteration   2: 3.864 ±(99.9%) 0.010 ms/op
Iteration   3: 3.855 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.862 ±(99.9%) 0.115 ms/op [Average]
  (min, avg, max) = (3.855, 3.862, 3.868), stdev = 0.006
  CI (99.9%): [3.748, 3.977] (assumes normal distribution)


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
# Warmup Iteration   1: 9.473 ±(99.9%) 0.129 ms/op
# Warmup Iteration   2: 3.848 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.484 ±(99.9%) 0.010 ms/op
Iteration   1: 3.298 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.362 ms/op
                 createUser·p0.50:   3.248 ms/op
                 createUser·p0.90:   3.449 ms/op
                 createUser·p0.95:   3.548 ms/op
                 createUser·p0.99:   5.890 ms/op
                 createUser·p0.999:  10.403 ms/op
                 createUser·p0.9999: 23.570 ms/op
                 createUser·p1.00:   24.117 ms/op

Iteration   2: 3.491 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.319 ms/op
                 createUser·p0.50:   3.359 ms/op
                 createUser·p0.90:   4.235 ms/op
                 createUser·p0.95:   4.506 ms/op
                 createUser·p0.99:   5.784 ms/op
                 createUser·p0.999:  21.312 ms/op
                 createUser·p0.9999: 24.014 ms/op
                 createUser·p1.00:   25.199 ms/op

Iteration   3: 3.366 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.626 ms/op
                 createUser·p0.50:   3.305 ms/op
                 createUser·p0.90:   3.715 ms/op
                 createUser·p0.95:   3.990 ms/op
                 createUser·p0.99:   5.546 ms/op
                 createUser·p0.999:  19.048 ms/op
                 createUser·p0.9999: 27.050 ms/op
                 createUser·p1.00:   27.918 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 283549
  mean =      3.383 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14653 
    [ 2.500,  5.000) = 263033 
    [ 5.000,  7.500) = 4860 
    [ 7.500, 10.000) = 568 
    [10.000, 12.500) = 132 
    [12.500, 15.000) = 8 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 107 
    [22.500, 25.000) = 136 
    [25.000, 27.500) = 21 

  Percentiles, ms/op:
      p(0.0000) =      0.362 ms/op
     p(50.0000) =      3.310 ms/op
     p(90.0000) =      3.748 ms/op
     p(95.0000) =      4.260 ms/op
     p(99.0000) =      5.743 ms/op
     p(99.9000) =     19.413 ms/op
     p(99.9900) =     24.281 ms/op
     p(99.9990) =     27.382 ms/op
     p(99.9999) =     27.918 ms/op
    p(100.0000) =     27.918 ms/op


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
# Warmup Iteration   1: 8.859 ±(99.9%) 0.107 ms/op
# Warmup Iteration   2: 3.566 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.274 ±(99.9%) 0.008 ms/op
Iteration   1: 3.197 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.137 ms/op
                 existUser·p0.50:   3.101 ms/op
                 existUser·p0.90:   3.514 ms/op
                 existUser·p0.95:   3.723 ms/op
                 existUser·p0.99:   5.106 ms/op
                 existUser·p0.999:  8.684 ms/op
                 existUser·p0.9999: 22.610 ms/op
                 existUser·p1.00:   23.233 ms/op

Iteration   2: 3.399 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.317 ms/op
                 existUser·p0.50:   3.289 ms/op
                 existUser·p0.90:   3.801 ms/op
                 existUser·p0.95:   4.157 ms/op
                 existUser·p0.99:   6.676 ms/op
                 existUser·p0.999:  20.510 ms/op
                 existUser·p0.9999: 24.595 ms/op
                 existUser·p1.00:   25.494 ms/op

Iteration   3: 3.426 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.534 ms/op
                 existUser·p0.50:   3.285 ms/op
                 existUser·p0.90:   3.883 ms/op
                 existUser·p0.95:   4.243 ms/op
                 existUser·p0.99:   6.570 ms/op
                 existUser·p0.999:  11.104 ms/op
                 existUser·p0.9999: 25.407 ms/op
                 existUser·p1.00:   26.477 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 287388
  mean =      3.338 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6958 
    [ 2.500,  5.000) = 274200 
    [ 5.000,  7.500) = 5008 
    [ 7.500, 10.000) = 796 
    [10.000, 12.500) = 163 
    [12.500, 15.000) = 6 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 100 
    [22.500, 25.000) = 124 
    [25.000, 27.500) = 20 

  Percentiles, ms/op:
      p(0.0000) =      1.137 ms/op
     p(50.0000) =      3.228 ms/op
     p(90.0000) =      3.740 ms/op
     p(95.0000) =      4.080 ms/op
     p(99.0000) =      6.119 ms/op
     p(99.9000) =     12.190 ms/op
     p(99.9900) =     24.757 ms/op
     p(99.9990) =     26.288 ms/op
     p(99.9999) =     26.477 ms/op
    p(100.0000) =     26.477 ms/op


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
# Warmup Iteration   1: 9.846 ±(99.9%) 0.118 ms/op
# Warmup Iteration   2: 3.995 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.425 ±(99.9%) 0.009 ms/op
Iteration   1: 3.396 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.757 ms/op
                 getUser·p0.50:   3.244 ms/op
                 getUser·p0.90:   3.744 ms/op
                 getUser·p0.95:   4.010 ms/op
                 getUser·p0.99:   6.504 ms/op
                 getUser·p0.999:  18.554 ms/op
                 getUser·p0.9999: 22.897 ms/op
                 getUser·p1.00:   23.331 ms/op

Iteration   2: 3.454 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.278 ms/op
                 getUser·p0.50:   3.367 ms/op
                 getUser·p0.90:   3.949 ms/op
                 getUser·p0.95:   4.440 ms/op
                 getUser·p0.99:   5.800 ms/op
                 getUser·p0.999:  21.176 ms/op
                 getUser·p0.9999: 26.673 ms/op
                 getUser·p1.00:   27.623 ms/op

Iteration   3: 3.444 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.321 ms/op
                 getUser·p0.50:   3.297 ms/op
                 getUser·p0.90:   3.891 ms/op
                 getUser·p0.95:   4.243 ms/op
                 getUser·p0.99:   6.240 ms/op
                 getUser·p0.999:  22.086 ms/op
                 getUser·p0.9999: 26.009 ms/op
                 getUser·p1.00:   27.394 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 279544
  mean =      3.431 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10400 
    [ 2.500,  5.000) = 260517 
    [ 5.000,  7.500) = 7442 
    [ 7.500, 10.000) = 644 
    [10.000, 12.500) = 170 
    [12.500, 15.000) = 72 
    [15.000, 17.500) = 11 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 95 
    [22.500, 25.000) = 120 
    [25.000, 27.500) = 48 

  Percentiles, ms/op:
      p(0.0000) =      1.278 ms/op
     p(50.0000) =      3.326 ms/op
     p(90.0000) =      3.863 ms/op
     p(95.0000) =      4.252 ms/op
     p(99.0000) =      6.177 ms/op
     p(99.9000) =     19.217 ms/op
     p(99.9900) =     26.150 ms/op
     p(99.9990) =     27.421 ms/op
     p(99.9999) =     27.623 ms/op
    p(100.0000) =     27.623 ms/op


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
# Warmup Iteration   1: 10.915 ±(99.9%) 0.147 ms/op
# Warmup Iteration   2: 4.436 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.084 ±(99.9%) 0.013 ms/op
Iteration   1: 3.958 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.083 ms/op
                 listUser·p0.50:   3.858 ms/op
                 listUser·p0.90:   4.252 ms/op
                 listUser·p0.95:   4.424 ms/op
                 listUser·p0.99:   6.660 ms/op
                 listUser·p0.999:  21.110 ms/op
                 listUser·p0.9999: 23.527 ms/op
                 listUser·p1.00:   24.543 ms/op

Iteration   2: 3.972 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.220 ms/op
                 listUser·p0.50:   3.846 ms/op
                 listUser·p0.90:   4.268 ms/op
                 listUser·p0.95:   4.489 ms/op
                 listUser·p0.99:   7.250 ms/op
                 listUser·p0.999:  15.106 ms/op
                 listUser·p0.9999: 17.170 ms/op
                 listUser·p1.00:   22.938 ms/op

Iteration   3: 3.967 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.310 ms/op
                 listUser·p0.50:   3.805 ms/op
                 listUser·p0.90:   4.497 ms/op
                 listUser·p0.95:   4.801 ms/op
                 listUser·p0.99:   7.481 ms/op
                 listUser·p0.999:  14.565 ms/op
                 listUser·p0.9999: 18.198 ms/op
                 listUser·p1.00:   20.578 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 241660
  mean =      3.966 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 39 
    [ 2.500,  5.000) = 234346 
    [ 5.000,  7.500) = 5275 
    [ 7.500, 10.000) = 1193 
    [10.000, 12.500) = 270 
    [12.500, 15.000) = 246 
    [15.000, 17.500) = 171 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 65 
    [22.500, 25.000) = 34 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.083 ms/op
     p(50.0000) =      3.834 ms/op
     p(90.0000) =      4.325 ms/op
     p(95.0000) =      4.596 ms/op
     p(99.0000) =      7.176 ms/op
     p(99.9000) =     15.614 ms/op
     p(99.9900) =     22.834 ms/op
     p(99.9990) =     24.478 ms/op
     p(99.9999) =     24.543 ms/op
    p(100.0000) =     24.543 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.220 ± 4.225  ops/ms
ClientPb.existUser                       thrpt       3   9.769 ± 5.384  ops/ms
ClientPb.getUser                         thrpt       3   9.375 ± 3.772  ops/ms
ClientPb.listUser                        thrpt       3   8.213 ± 1.822  ops/ms
ClientPb.createUser                       avgt       3   3.392 ± 0.632   ms/op
ClientPb.existUser                        avgt       3   3.221 ± 1.035   ms/op
ClientPb.getUser                          avgt       3   3.389 ± 0.643   ms/op
ClientPb.listUser                         avgt       3   3.862 ± 0.115   ms/op
ClientPb.createUser                     sample  283549   3.383 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.362           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.310           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.748           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.260           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.743           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.413           ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.281           ms/op
ClientPb.createUser:createUser·p1.00    sample          27.918           ms/op
ClientPb.existUser                      sample  287388   3.338 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.137           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.228           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.740           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.080           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.119           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.190           ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.757           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.477           ms/op
ClientPb.getUser                        sample  279544   3.431 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.278           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.326           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.863           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.252           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.177           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.217           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.150           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.623           ms/op
ClientPb.listUser                       sample  241660   3.966 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.083           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.834           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.325           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.596           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.176           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.614           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.834           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.543           ms/op
