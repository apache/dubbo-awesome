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
# Warmup Iteration   1: 1.659 ops/ms
# Warmup Iteration   2: 3.391 ops/ms
# Warmup Iteration   3: 7.107 ops/ms
Iteration   1: 7.160 ops/ms
Iteration   2: 7.645 ops/ms
Iteration   3: 7.775 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.527 ±(99.9%) 5.914 ops/ms [Average]
  (min, avg, max) = (7.160, 7.527, 7.775), stdev = 0.324
  CI (99.9%): [1.612, 13.441] (assumes normal distribution)


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
# Warmup Iteration   1: 2.581 ops/ms
# Warmup Iteration   2: 7.493 ops/ms
# Warmup Iteration   3: 8.045 ops/ms
Iteration   1: 8.433 ops/ms
Iteration   2: 8.358 ops/ms
Iteration   3: 8.408 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.400 ±(99.9%) 0.695 ops/ms [Average]
  (min, avg, max) = (8.358, 8.400, 8.433), stdev = 0.038
  CI (99.9%): [7.704, 9.095] (assumes normal distribution)


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
# Warmup Iteration   1: 2.079 ops/ms
# Warmup Iteration   2: 6.249 ops/ms
# Warmup Iteration   3: 7.635 ops/ms
Iteration   1: 7.823 ops/ms
Iteration   2: 7.791 ops/ms
Iteration   3: 8.365 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.993 ±(99.9%) 5.881 ops/ms [Average]
  (min, avg, max) = (7.791, 7.993, 8.365), stdev = 0.322
  CI (99.9%): [2.113, 13.874] (assumes normal distribution)


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
# Warmup Iteration   1: 2.147 ops/ms
# Warmup Iteration   2: 5.093 ops/ms
# Warmup Iteration   3: 6.527 ops/ms
Iteration   1: 6.728 ops/ms
Iteration   2: 6.605 ops/ms
Iteration   3: 6.594 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.642 ±(99.9%) 1.354 ops/ms [Average]
  (min, avg, max) = (6.594, 6.642, 6.728), stdev = 0.074
  CI (99.9%): [5.288, 7.997] (assumes normal distribution)


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
# Warmup Iteration   1: 13.420 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 4.788 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.014 ±(99.9%) 0.007 ms/op
Iteration   1: 3.925 ±(99.9%) 0.013 ms/op
Iteration   2: 3.955 ±(99.9%) 0.007 ms/op
Iteration   3: 3.888 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.923 ±(99.9%) 0.609 ms/op [Average]
  (min, avg, max) = (3.888, 3.923, 3.955), stdev = 0.033
  CI (99.9%): [3.314, 4.531] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:45
# Fork: 1 of 1
# Warmup Iteration   1: 12.448 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 4.400 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.991 ±(99.9%) 0.004 ms/op
Iteration   1: 4.211 ±(99.9%) 0.006 ms/op
Iteration   2: 3.772 ±(99.9%) 0.005 ms/op
Iteration   3: 3.696 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.893 ±(99.9%) 5.073 ms/op [Average]
  (min, avg, max) = (3.696, 3.893, 4.211), stdev = 0.278
  CI (99.9%): [≈ 0, 8.966] (assumes normal distribution)


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
# Warmup Iteration   1: 12.133 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.621 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.534 ±(99.9%) 0.007 ms/op
Iteration   1: 4.389 ±(99.9%) 0.006 ms/op
Iteration   2: 4.022 ±(99.9%) 0.005 ms/op
Iteration   3: 4.085 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.165 ±(99.9%) 3.584 ms/op [Average]
  (min, avg, max) = (4.022, 4.165, 4.389), stdev = 0.196
  CI (99.9%): [0.582, 7.749] (assumes normal distribution)


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
# Warmup Iteration   1: 14.989 ±(99.9%) 0.063 ms/op
# Warmup Iteration   2: 5.859 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.856 ±(99.9%) 0.014 ms/op
Iteration   1: 4.985 ±(99.9%) 0.010 ms/op
Iteration   2: 5.088 ±(99.9%) 0.012 ms/op
Iteration   3: 4.910 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.994 ±(99.9%) 1.634 ms/op [Average]
  (min, avg, max) = (4.910, 4.994, 5.088), stdev = 0.090
  CI (99.9%): [3.360, 6.629] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 14.760 ±(99.9%) 0.190 ms/op
# Warmup Iteration   2: 6.023 ±(99.9%) 0.036 ms/op
# Warmup Iteration   3: 4.669 ±(99.9%) 0.022 ms/op
Iteration   1: 4.086 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.192 ms/op
                 createUser·p0.50:   3.830 ms/op
                 createUser·p0.90:   4.678 ms/op
                 createUser·p0.95:   5.628 ms/op
                 createUser·p0.99:   8.503 ms/op
                 createUser·p0.999:  12.091 ms/op
                 createUser·p0.9999: 25.543 ms/op
                 createUser·p1.00:   27.329 ms/op

Iteration   2: 4.096 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.540 ms/op
                 createUser·p0.50:   3.944 ms/op
                 createUser·p0.90:   4.694 ms/op
                 createUser·p0.95:   5.022 ms/op
                 createUser·p0.99:   7.602 ms/op
                 createUser·p0.999:  27.097 ms/op
                 createUser·p0.9999: 31.673 ms/op
                 createUser·p1.00:   32.309 ms/op

Iteration   3: 4.028 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.466 ms/op
                 createUser·p0.50:   3.858 ms/op
                 createUser·p0.90:   4.637 ms/op
                 createUser·p0.95:   5.505 ms/op
                 createUser·p0.99:   7.283 ms/op
                 createUser·p0.999:  28.590 ms/op
                 createUser·p0.9999: 31.557 ms/op
                 createUser·p1.00:   32.440 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 235877
  mean =      4.070 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 379 
    [ 2.500,  5.000) = 220851 
    [ 5.000,  7.500) = 11214 
    [ 7.500, 10.000) = 2549 
    [10.000, 12.500) = 491 
    [12.500, 15.000) = 102 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 51 
    [25.000, 27.500) = 38 
    [27.500, 30.000) = 102 
    [30.000, 32.500) = 63 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.192 ms/op
     p(50.0000) =      3.887 ms/op
     p(90.0000) =      4.669 ms/op
     p(95.0000) =      5.235 ms/op
     p(99.0000) =      8.233 ms/op
     p(99.9000) =     23.794 ms/op
     p(99.9900) =     31.386 ms/op
     p(99.9990) =     32.309 ms/op
     p(99.9999) =     32.440 ms/op
    p(100.0000) =     32.440 ms/op


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
# Warmup Iteration   1: 13.442 ±(99.9%) 0.169 ms/op
# Warmup Iteration   2: 4.836 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 3.961 ±(99.9%) 0.013 ms/op
Iteration   1: 3.833 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.350 ms/op
                 existUser·p0.50:   3.723 ms/op
                 existUser·p0.90:   4.202 ms/op
                 existUser·p0.95:   4.604 ms/op
                 existUser·p0.99:   6.701 ms/op
                 existUser·p0.999:  11.919 ms/op
                 existUser·p0.9999: 25.679 ms/op
                 existUser·p1.00:   26.182 ms/op

Iteration   2: 3.750 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.823 ms/op
                 existUser·p0.50:   3.707 ms/op
                 existUser·p0.90:   3.932 ms/op
                 existUser·p0.95:   4.178 ms/op
                 existUser·p0.99:   6.390 ms/op
                 existUser·p0.999:  24.216 ms/op
                 existUser·p0.9999: 26.132 ms/op
                 existUser·p1.00:   27.361 ms/op

Iteration   3: 4.006 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   2.179 ms/op
                 existUser·p0.50:   3.858 ms/op
                 existUser·p0.90:   4.661 ms/op
                 existUser·p0.95:   5.038 ms/op
                 existUser·p0.99:   6.742 ms/op
                 existUser·p0.999:  11.747 ms/op
                 existUser·p0.9999: 29.918 ms/op
                 existUser·p1.00:   30.441 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 248471
  mean =      3.860 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 208 
    [ 2.500,  5.000) = 239778 
    [ 5.000,  7.500) = 7062 
    [ 7.500, 10.000) = 858 
    [10.000, 12.500) = 254 
    [12.500, 15.000) = 76 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 94 
    [25.000, 27.500) = 75 
    [27.500, 30.000) = 46 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.350 ms/op
     p(50.0000) =      3.756 ms/op
     p(90.0000) =      4.334 ms/op
     p(95.0000) =      4.735 ms/op
     p(99.0000) =      6.676 ms/op
     p(99.9000) =     14.451 ms/op
     p(99.9900) =     28.846 ms/op
     p(99.9990) =     30.098 ms/op
     p(99.9999) =     30.441 ms/op
    p(100.0000) =     30.441 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 14.201 ±(99.9%) 0.224 ms/op
# Warmup Iteration   2: 5.080 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 4.299 ±(99.9%) 0.015 ms/op
Iteration   1: 3.951 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.798 ms/op
                 getUser·p0.50:   3.822 ms/op
                 getUser·p0.90:   4.268 ms/op
                 getUser·p0.95:   4.506 ms/op
                 getUser·p0.99:   7.455 ms/op
                 getUser·p0.999:  17.596 ms/op
                 getUser·p0.9999: 25.031 ms/op
                 getUser·p1.00:   25.919 ms/op

Iteration   2: 4.051 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   2.167 ms/op
                 getUser·p0.50:   3.891 ms/op
                 getUser·p0.90:   4.596 ms/op
                 getUser·p0.95:   5.079 ms/op
                 getUser·p0.99:   7.799 ms/op
                 getUser·p0.999:  24.912 ms/op
                 getUser·p0.9999: 27.754 ms/op
                 getUser·p1.00:   28.574 ms/op

Iteration   3: 3.904 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.997 ms/op
                 getUser·p0.50:   3.760 ms/op
                 getUser·p0.90:   4.293 ms/op
                 getUser·p0.95:   4.636 ms/op
                 getUser·p0.99:   7.045 ms/op
                 getUser·p0.999:  12.109 ms/op
                 getUser·p0.9999: 32.231 ms/op
                 getUser·p1.00:   32.735 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 241826
  mean =      3.967 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 71 
    [ 2.500,  5.000) = 232189 
    [ 5.000,  7.500) = 7058 
    [ 7.500, 10.000) = 1731 
    [10.000, 12.500) = 412 
    [12.500, 15.000) = 92 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 70 
    [25.000, 27.500) = 79 
    [27.500, 30.000) = 39 
    [30.000, 32.500) = 26 
    [32.500, 35.000) = 5 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.798 ms/op
     p(50.0000) =      3.813 ms/op
     p(90.0000) =      4.383 ms/op
     p(95.0000) =      4.784 ms/op
     p(99.0000) =      7.543 ms/op
     p(99.9000) =     17.569 ms/op
     p(99.9900) =     31.112 ms/op
     p(99.9990) =     32.610 ms/op
     p(99.9999) =     32.735 ms/op
    p(100.0000) =     32.735 ms/op


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
# Warmup Iteration   1: 16.684 ±(99.9%) 0.254 ms/op
# Warmup Iteration   2: 6.227 ±(99.9%) 0.037 ms/op
# Warmup Iteration   3: 5.179 ±(99.9%) 0.020 ms/op
Iteration   1: 4.973 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   2.433 ms/op
                 listUser·p0.50:   4.620 ms/op
                 listUser·p0.90:   5.767 ms/op
                 listUser·p0.95:   6.922 ms/op
                 listUser·p0.99:   10.212 ms/op
                 listUser·p0.999:  25.068 ms/op
                 listUser·p0.9999: 27.894 ms/op
                 listUser·p1.00:   30.573 ms/op

Iteration   2: 4.824 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.960 ms/op
                 listUser·p0.50:   4.653 ms/op
                 listUser·p0.90:   5.226 ms/op
                 listUser·p0.95:   5.767 ms/op
                 listUser·p0.99:   9.365 ms/op
                 listUser·p0.999:  20.260 ms/op
                 listUser·p0.9999: 27.734 ms/op
                 listUser·p1.00:   29.819 ms/op

Iteration   3: 4.735 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.763 ms/op
                 listUser·p0.50:   4.588 ms/op
                 listUser·p0.90:   5.145 ms/op
                 listUser·p0.95:   5.489 ms/op
                 listUser·p0.99:   7.908 ms/op
                 listUser·p0.999:  18.942 ms/op
                 listUser·p0.9999: 23.217 ms/op
                 listUser·p1.00:   23.921 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 198072
  mean =      4.842 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19 
    [ 2.500,  5.000) = 156634 
    [ 5.000,  7.500) = 36003 
    [ 7.500, 10.000) = 3977 
    [10.000, 12.500) = 819 
    [12.500, 15.000) = 181 
    [15.000, 17.500) = 100 
    [17.500, 20.000) = 102 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 94 
    [25.000, 27.500) = 89 
    [27.500, 30.000) = 20 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.763 ms/op
     p(50.0000) =      4.612 ms/op
     p(90.0000) =      5.366 ms/op
     p(95.0000) =      6.087 ms/op
     p(99.0000) =      9.306 ms/op
     p(99.9000) =     22.608 ms/op
     p(99.9900) =     27.623 ms/op
     p(99.9990) =     29.833 ms/op
     p(99.9999) =     30.573 ms/op
    p(100.0000) =     30.573 ms/op


# Run complete. Total time: 00:13:17

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.527 ± 5.914  ops/ms
ClientPb.existUser                       thrpt       3   8.400 ± 0.695  ops/ms
ClientPb.getUser                         thrpt       3   7.993 ± 5.881  ops/ms
ClientPb.listUser                        thrpt       3   6.642 ± 1.354  ops/ms
ClientPb.createUser                       avgt       3   3.923 ± 0.609   ms/op
ClientPb.existUser                        avgt       3   3.893 ± 5.073   ms/op
ClientPb.getUser                          avgt       3   4.165 ± 3.584   ms/op
ClientPb.listUser                         avgt       3   4.994 ± 1.634   ms/op
ClientPb.createUser                     sample  235877   4.070 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.192           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.887           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.669           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.235           ms/op
ClientPb.createUser:createUser·p0.99    sample           8.233           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.794           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.386           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.440           ms/op
ClientPb.existUser                      sample  248471   3.860 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.350           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.756           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.334           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.735           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.676           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.451           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.846           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.441           ms/op
ClientPb.getUser                        sample  241826   3.967 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.798           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.813           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.383           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.784           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.543           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.569           ms/op
ClientPb.getUser:getUser·p0.9999        sample          31.112           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.735           ms/op
ClientPb.listUser                       sample  198072   4.842 ± 0.009   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.763           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.612           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.366           ms/op
ClientPb.listUser:listUser·p0.95        sample           6.087           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.306           ms/op
ClientPb.listUser:listUser·p0.999       sample          22.608           ms/op
ClientPb.listUser:listUser·p0.9999      sample          27.623           ms/op
ClientPb.listUser:listUser·p1.00        sample          30.573           ms/op
