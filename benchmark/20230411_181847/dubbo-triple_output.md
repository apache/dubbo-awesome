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
# Warmup Iteration   1: 1.903 ops/ms
# Warmup Iteration   2: 5.150 ops/ms
# Warmup Iteration   3: 8.367 ops/ms
Iteration   1: 8.882 ops/ms
Iteration   2: 9.154 ops/ms
Iteration   3: 9.508 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.181 ±(99.9%) 5.726 ops/ms [Average]
  (min, avg, max) = (8.882, 9.181, 9.508), stdev = 0.314
  CI (99.9%): [3.456, 14.907] (assumes normal distribution)


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
# Warmup Iteration   1: 2.302 ops/ms
# Warmup Iteration   2: 8.069 ops/ms
# Warmup Iteration   3: 8.689 ops/ms
Iteration   1: 9.717 ops/ms
Iteration   2: 9.582 ops/ms
Iteration   3: 10.101 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.800 ±(99.9%) 4.920 ops/ms [Average]
  (min, avg, max) = (9.582, 9.800, 10.101), stdev = 0.270
  CI (99.9%): [4.880, 14.720] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 2.630 ops/ms
# Warmup Iteration   2: 7.857 ops/ms
# Warmup Iteration   3: 8.735 ops/ms
Iteration   1: 8.735 ops/ms
Iteration   2: 9.039 ops/ms
Iteration   3: 9.089 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.954 ±(99.9%) 3.497 ops/ms [Average]
  (min, avg, max) = (8.735, 8.954, 9.089), stdev = 0.192
  CI (99.9%): [5.458, 12.451] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 2.600 ops/ms
# Warmup Iteration   2: 6.623 ops/ms
# Warmup Iteration   3: 7.724 ops/ms
Iteration   1: 7.698 ops/ms
Iteration   2: 7.721 ops/ms
Iteration   3: 7.890 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.770 ±(99.9%) 1.910 ops/ms [Average]
  (min, avg, max) = (7.698, 7.770, 7.890), stdev = 0.105
  CI (99.9%): [5.859, 9.680] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 10.506 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 4.277 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.524 ±(99.9%) 0.009 ms/op
Iteration   1: 3.502 ±(99.9%) 0.007 ms/op
Iteration   2: 3.375 ±(99.9%) 0.008 ms/op
Iteration   3: 3.414 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.431 ±(99.9%) 1.188 ms/op [Average]
  (min, avg, max) = (3.375, 3.431, 3.502), stdev = 0.065
  CI (99.9%): [2.243, 4.618] (assumes normal distribution)


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
# Warmup Iteration   1: 10.602 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.694 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.365 ±(99.9%) 0.002 ms/op
Iteration   1: 3.530 ±(99.9%) 0.007 ms/op
Iteration   2: 3.440 ±(99.9%) 0.007 ms/op
Iteration   3: 3.293 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.421 ±(99.9%) 2.181 ms/op [Average]
  (min, avg, max) = (3.293, 3.421, 3.530), stdev = 0.120
  CI (99.9%): [1.239, 5.602] (assumes normal distribution)


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
# Warmup Iteration   1: 9.121 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.873 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.676 ±(99.9%) 0.007 ms/op
Iteration   1: 3.657 ±(99.9%) 0.005 ms/op
Iteration   2: 3.414 ±(99.9%) 0.005 ms/op
Iteration   3: 3.572 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.548 ±(99.9%) 2.250 ms/op [Average]
  (min, avg, max) = (3.414, 3.548, 3.657), stdev = 0.123
  CI (99.9%): [1.298, 5.798] (assumes normal distribution)


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
# Warmup Iteration   1: 11.165 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.543 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.117 ±(99.9%) 0.009 ms/op
Iteration   1: 4.148 ±(99.9%) 0.008 ms/op
Iteration   2: 3.933 ±(99.9%) 0.018 ms/op
Iteration   3: 4.047 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.043 ±(99.9%) 1.956 ms/op [Average]
  (min, avg, max) = (3.933, 4.043, 4.148), stdev = 0.107
  CI (99.9%): [2.086, 5.999] (assumes normal distribution)


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
# Warmup Iteration   1: 10.889 ±(99.9%) 0.155 ms/op
# Warmup Iteration   2: 4.168 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 3.770 ±(99.9%) 0.013 ms/op
Iteration   1: 3.494 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.754 ms/op
                 createUser·p0.50:   3.400 ms/op
                 createUser·p0.90:   3.969 ms/op
                 createUser·p0.95:   4.342 ms/op
                 createUser·p0.99:   6.338 ms/op
                 createUser·p0.999:  19.857 ms/op
                 createUser·p0.9999: 24.478 ms/op
                 createUser·p1.00:   27.460 ms/op

Iteration   2: 3.402 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.681 ms/op
                 createUser·p0.50:   3.322 ms/op
                 createUser·p0.90:   3.600 ms/op
                 createUser·p0.95:   4.100 ms/op
                 createUser·p0.99:   5.956 ms/op
                 createUser·p0.999:  22.479 ms/op
                 createUser·p0.9999: 28.082 ms/op
                 createUser·p1.00:   30.015 ms/op

Iteration   3: 3.542 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.599 ms/op
                 createUser·p0.50:   3.473 ms/op
                 createUser·p0.90:   4.002 ms/op
                 createUser·p0.95:   4.268 ms/op
                 createUser·p0.99:   5.923 ms/op
                 createUser·p0.999:  12.042 ms/op
                 createUser·p0.9999: 27.586 ms/op
                 createUser·p1.00:   29.327 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 275801
  mean =      3.478 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11094 
    [ 2.500,  5.000) = 258407 
    [ 5.000,  7.500) = 5260 
    [ 7.500, 10.000) = 608 
    [10.000, 12.500) = 136 
    [12.500, 15.000) = 6 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 9 
    [20.000, 22.500) = 99 
    [22.500, 25.000) = 74 
    [25.000, 27.500) = 77 
    [27.500, 30.000) = 27 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.754 ms/op
     p(50.0000) =      3.391 ms/op
     p(90.0000) =      3.912 ms/op
     p(95.0000) =      4.260 ms/op
     p(99.0000) =      6.054 ms/op
     p(99.9000) =     20.054 ms/op
     p(99.9900) =     27.572 ms/op
     p(99.9990) =     29.966 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 9.697 ±(99.9%) 0.126 ms/op
# Warmup Iteration   2: 3.943 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.487 ±(99.9%) 0.011 ms/op
Iteration   1: 3.340 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.370 ms/op
                 existUser·p0.50:   3.211 ms/op
                 existUser·p0.90:   3.658 ms/op
                 existUser·p0.95:   4.022 ms/op
                 existUser·p0.99:   5.857 ms/op
                 existUser·p0.999:  22.839 ms/op
                 existUser·p0.9999: 27.244 ms/op
                 existUser·p1.00:   27.656 ms/op

Iteration   2: 3.293 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.709 ms/op
                 existUser·p0.50:   3.183 ms/op
                 existUser·p0.90:   3.633 ms/op
                 existUser·p0.95:   3.834 ms/op
                 existUser·p0.99:   5.136 ms/op
                 existUser·p0.999:  12.857 ms/op
                 existUser·p0.9999: 27.174 ms/op
                 existUser·p1.00:   27.623 ms/op

Iteration   3: 3.354 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.620 ms/op
                 existUser·p0.50:   3.355 ms/op
                 existUser·p0.90:   3.604 ms/op
                 existUser·p0.95:   3.908 ms/op
                 existUser·p0.99:   5.308 ms/op
                 existUser·p0.999:  8.874 ms/op
                 existUser·p0.9999: 30.048 ms/op
                 existUser·p1.00:   30.769 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 288187
  mean =      3.329 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7799 
    [ 2.500,  5.000) = 275731 
    [ 5.000,  7.500) = 3933 
    [ 7.500, 10.000) = 396 
    [10.000, 12.500) = 71 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 73 
    [25.000, 27.500) = 152 
    [27.500, 30.000) = 20 
    [30.000, 32.500) = 11 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.709 ms/op
     p(50.0000) =      3.244 ms/op
     p(90.0000) =      3.629 ms/op
     p(95.0000) =      3.903 ms/op
     p(99.0000) =      5.554 ms/op
     p(99.9000) =     11.108 ms/op
     p(99.9900) =     27.531 ms/op
     p(99.9990) =     30.216 ms/op
     p(99.9999) =     30.769 ms/op
    p(100.0000) =     30.769 ms/op


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
# Warmup Iteration   1: 11.479 ±(99.9%) 0.142 ms/op
# Warmup Iteration   2: 3.924 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.674 ±(99.9%) 0.013 ms/op
Iteration   1: 3.471 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.860 ms/op
                 getUser·p0.50:   3.244 ms/op
                 getUser·p0.90:   3.830 ms/op
                 getUser·p0.95:   5.046 ms/op
                 getUser·p0.99:   7.569 ms/op
                 getUser·p0.999:  23.069 ms/op
                 getUser·p0.9999: 35.834 ms/op
                 getUser·p1.00:   35.979 ms/op

Iteration   2: 3.525 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.835 ms/op
                 getUser·p0.50:   3.396 ms/op
                 getUser·p0.90:   4.088 ms/op
                 getUser·p0.95:   4.383 ms/op
                 getUser·p0.99:   6.193 ms/op
                 getUser·p0.999:  23.855 ms/op
                 getUser·p0.9999: 28.604 ms/op
                 getUser·p1.00:   30.212 ms/op

Iteration   3: 3.552 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.331 ms/op
                 getUser·p0.50:   3.416 ms/op
                 getUser·p0.90:   3.940 ms/op
                 getUser·p0.95:   4.465 ms/op
                 getUser·p0.99:   6.753 ms/op
                 getUser·p0.999:  20.218 ms/op
                 getUser·p0.9999: 29.000 ms/op
                 getUser·p1.00:   31.195 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 272964
  mean =      3.516 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5549 
    [ 2.500,  5.000) = 257794 
    [ 5.000,  7.500) = 7749 
    [ 7.500, 10.000) = 1365 
    [10.000, 12.500) = 156 
    [12.500, 15.000) = 3 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 46 
    [22.500, 25.000) = 116 
    [25.000, 27.500) = 76 
    [27.500, 30.000) = 45 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 11 
    [35.000, 37.500) = 20 

  Percentiles, ms/op:
      p(0.0000) =      1.331 ms/op
     p(50.0000) =      3.338 ms/op
     p(90.0000) =      3.981 ms/op
     p(95.0000) =      4.481 ms/op
     p(99.0000) =      7.250 ms/op
     p(99.9000) =     22.420 ms/op
     p(99.9900) =     34.734 ms/op
     p(99.9990) =     35.914 ms/op
     p(99.9999) =     35.979 ms/op
    p(100.0000) =     35.979 ms/op


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
# Warmup Iteration   1: 12.477 ±(99.9%) 0.163 ms/op
# Warmup Iteration   2: 4.485 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.103 ±(99.9%) 0.014 ms/op
Iteration   1: 4.218 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.190 ms/op
                 listUser·p0.50:   4.030 ms/op
                 listUser·p0.90:   4.751 ms/op
                 listUser·p0.95:   5.202 ms/op
                 listUser·p0.99:   7.881 ms/op
                 listUser·p0.999:  21.201 ms/op
                 listUser·p0.9999: 27.598 ms/op
                 listUser·p1.00:   28.082 ms/op

Iteration   2: 4.045 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.568 ms/op
                 listUser·p0.50:   3.969 ms/op
                 listUser·p0.90:   4.317 ms/op
                 listUser·p0.95:   4.620 ms/op
                 listUser·p0.99:   6.816 ms/op
                 listUser·p0.999:  16.351 ms/op
                 listUser·p0.9999: 21.181 ms/op
                 listUser·p1.00:   22.217 ms/op

Iteration   3: 4.179 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   2.417 ms/op
                 listUser·p0.50:   3.842 ms/op
                 listUser·p0.90:   4.678 ms/op
                 listUser·p0.95:   6.070 ms/op
                 listUser·p0.99:   9.159 ms/op
                 listUser·p0.999:  16.105 ms/op
                 listUser·p0.9999: 19.533 ms/op
                 listUser·p1.00:   23.462 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 231433
  mean =      4.146 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14 
    [ 2.500,  5.000) = 218526 
    [ 5.000,  7.500) = 9632 
    [ 7.500, 10.000) = 2003 
    [10.000, 12.500) = 506 
    [12.500, 15.000) = 302 
    [15.000, 17.500) = 239 
    [17.500, 20.000) = 68 
    [20.000, 22.500) = 76 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 54 

  Percentiles, ms/op:
      p(0.0000) =      1.190 ms/op
     p(50.0000) =      3.969 ms/op
     p(90.0000) =      4.596 ms/op
     p(95.0000) =      5.112 ms/op
     p(99.0000) =      8.126 ms/op
     p(99.9000) =     16.974 ms/op
     p(99.9900) =     26.336 ms/op
     p(99.9990) =     27.953 ms/op
     p(99.9999) =     28.082 ms/op
    p(100.0000) =     28.082 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.181 ± 5.726  ops/ms
ClientPb.existUser                       thrpt       3   9.800 ± 4.920  ops/ms
ClientPb.getUser                         thrpt       3   8.954 ± 3.497  ops/ms
ClientPb.listUser                        thrpt       3   7.770 ± 1.910  ops/ms
ClientPb.createUser                       avgt       3   3.431 ± 1.188   ms/op
ClientPb.existUser                        avgt       3   3.421 ± 2.181   ms/op
ClientPb.getUser                          avgt       3   3.548 ± 2.250   ms/op
ClientPb.listUser                         avgt       3   4.043 ± 1.956   ms/op
ClientPb.createUser                     sample  275801   3.478 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.754           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.391           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.912           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.260           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.054           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.054           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.572           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.015           ms/op
ClientPb.existUser                      sample  288187   3.329 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.709           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.244           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.629           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.903           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.554           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.108           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.531           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.769           ms/op
ClientPb.getUser                        sample  272964   3.516 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.331           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.338           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.981           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.481           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.250           ms/op
ClientPb.getUser:getUser·p0.999         sample          22.420           ms/op
ClientPb.getUser:getUser·p0.9999        sample          34.734           ms/op
ClientPb.getUser:getUser·p1.00          sample          35.979           ms/op
ClientPb.listUser                       sample  231433   4.146 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.190           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.969           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.596           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.112           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.126           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.974           ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.336           ms/op
ClientPb.listUser:listUser·p1.00        sample          28.082           ms/op
