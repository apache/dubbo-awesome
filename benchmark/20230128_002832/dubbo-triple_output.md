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
# Warmup Iteration   1: 1.890 ops/ms
# Warmup Iteration   2: 4.234 ops/ms
# Warmup Iteration   3: 8.029 ops/ms
Iteration   1: 8.296 ops/ms
Iteration   2: 8.929 ops/ms
Iteration   3: 9.348 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.858 ±(99.9%) 9.658 ops/ms [Average]
  (min, avg, max) = (8.296, 8.858, 9.348), stdev = 0.529
  CI (99.9%): [≈ 0, 18.515] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 2.368 ops/ms
# Warmup Iteration   2: 7.610 ops/ms
# Warmup Iteration   3: 9.023 ops/ms
Iteration   1: 9.001 ops/ms
Iteration   2: 9.129 ops/ms
Iteration   3: 9.109 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.080 ±(99.9%) 1.257 ops/ms [Average]
  (min, avg, max) = (9.001, 9.080, 9.129), stdev = 0.069
  CI (99.9%): [7.823, 10.336] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 2.142 ops/ms
# Warmup Iteration   2: 6.430 ops/ms
# Warmup Iteration   3: 8.941 ops/ms
Iteration   1: 8.665 ops/ms
Iteration   2: 9.277 ops/ms
Iteration   3: 8.450 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.798 ±(99.9%) 7.831 ops/ms [Average]
  (min, avg, max) = (8.450, 8.798, 9.277), stdev = 0.429
  CI (99.9%): [0.966, 16.629] (assumes normal distribution)


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
# Warmup Iteration   1: 2.590 ops/ms
# Warmup Iteration   2: 6.813 ops/ms
# Warmup Iteration   3: 7.527 ops/ms
Iteration   1: 7.805 ops/ms
Iteration   2: 8.034 ops/ms
Iteration   3: 7.731 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.857 ±(99.9%) 2.881 ops/ms [Average]
  (min, avg, max) = (7.731, 7.857, 8.034), stdev = 0.158
  CI (99.9%): [4.975, 10.738] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 9.274 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.882 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.484 ±(99.9%) 0.007 ms/op
Iteration   1: 3.534 ±(99.9%) 0.009 ms/op
Iteration   2: 3.592 ±(99.9%) 0.005 ms/op
Iteration   3: 3.444 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.523 ±(99.9%) 1.360 ms/op [Average]
  (min, avg, max) = (3.444, 3.523, 3.592), stdev = 0.075
  CI (99.9%): [2.163, 4.884] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 9.882 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.870 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.407 ±(99.9%) 0.006 ms/op
Iteration   1: 3.293 ±(99.9%) 0.005 ms/op
Iteration   2: 3.374 ±(99.9%) 0.007 ms/op
Iteration   3: 3.396 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.354 ±(99.9%) 0.996 ms/op [Average]
  (min, avg, max) = (3.293, 3.354, 3.396), stdev = 0.055
  CI (99.9%): [2.358, 4.350] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 10.209 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.880 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.665 ±(99.9%) 0.004 ms/op
Iteration   1: 3.430 ±(99.9%) 0.006 ms/op
Iteration   2: 3.363 ±(99.9%) 0.005 ms/op
Iteration   3: 3.410 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.401 ±(99.9%) 0.630 ms/op [Average]
  (min, avg, max) = (3.363, 3.401, 3.430), stdev = 0.035
  CI (99.9%): [2.771, 4.031] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 10.672 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 4.718 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.183 ±(99.9%) 0.006 ms/op
Iteration   1: 4.129 ±(99.9%) 0.010 ms/op
Iteration   2: 3.898 ±(99.9%) 0.014 ms/op
Iteration   3: 3.975 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.001 ±(99.9%) 2.148 ms/op [Average]
  (min, avg, max) = (3.898, 4.001, 4.129), stdev = 0.118
  CI (99.9%): [1.852, 6.149] (assumes normal distribution)


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
# Warmup Iteration   1: 11.226 ±(99.9%) 0.168 ms/op
# Warmup Iteration   2: 4.016 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.893 ±(99.9%) 0.017 ms/op
Iteration   1: 3.492 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.284 ms/op
                 createUser·p0.50:   3.310 ms/op
                 createUser·p0.90:   4.055 ms/op
                 createUser·p0.95:   4.719 ms/op
                 createUser·p0.99:   5.890 ms/op
                 createUser·p0.999:  23.120 ms/op
                 createUser·p0.9999: 28.732 ms/op
                 createUser·p1.00:   29.721 ms/op

Iteration   2: 3.492 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.706 ms/op
                 createUser·p0.50:   3.379 ms/op
                 createUser·p0.90:   4.022 ms/op
                 createUser·p0.95:   4.375 ms/op
                 createUser·p0.99:   6.029 ms/op
                 createUser·p0.999:  22.896 ms/op
                 createUser·p0.9999: 27.974 ms/op
                 createUser·p1.00:   29.098 ms/op

Iteration   3: 3.531 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.509 ms/op
                 createUser·p0.50:   3.285 ms/op
                 createUser·p0.90:   4.112 ms/op
                 createUser·p0.95:   4.627 ms/op
                 createUser·p0.99:   6.660 ms/op
                 createUser·p0.999:  21.627 ms/op
                 createUser·p0.9999: 29.751 ms/op
                 createUser·p1.00:   30.573 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 273924
  mean =      3.505 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3921 
    [ 2.500,  5.000) = 261164 
    [ 5.000,  7.500) = 7578 
    [ 7.500, 10.000) = 723 
    [10.000, 12.500) = 203 
    [12.500, 15.000) = 15 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 85 
    [25.000, 27.500) = 116 
    [27.500, 30.000) = 70 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.284 ms/op
     p(50.0000) =      3.334 ms/op
     p(90.0000) =      4.059 ms/op
     p(95.0000) =      4.522 ms/op
     p(99.0000) =      6.119 ms/op
     p(99.9000) =     22.683 ms/op
     p(99.9900) =     29.032 ms/op
     p(99.9990) =     30.393 ms/op
     p(99.9999) =     30.573 ms/op
    p(100.0000) =     30.573 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 8.390 ±(99.9%) 0.105 ms/op
# Warmup Iteration   2: 3.719 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.502 ±(99.9%) 0.009 ms/op
Iteration   1: 3.374 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.526 ms/op
                 existUser·p0.50:   3.248 ms/op
                 existUser·p0.90:   3.666 ms/op
                 existUser·p0.95:   4.243 ms/op
                 existUser·p0.99:   5.931 ms/op
                 existUser·p0.999:  20.020 ms/op
                 existUser·p0.9999: 24.233 ms/op
                 existUser·p1.00:   25.330 ms/op

Iteration   2: 3.347 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.864 ms/op
                 existUser·p0.50:   3.334 ms/op
                 existUser·p0.90:   3.551 ms/op
                 existUser·p0.95:   3.858 ms/op
                 existUser·p0.99:   5.399 ms/op
                 existUser·p0.999:  24.083 ms/op
                 existUser·p0.9999: 26.720 ms/op
                 existUser·p1.00:   28.246 ms/op

Iteration   3: 3.441 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.401 ms/op
                 existUser·p0.50:   3.273 ms/op
                 existUser·p0.90:   3.977 ms/op
                 existUser·p0.95:   4.252 ms/op
                 existUser·p0.99:   5.685 ms/op
                 existUser·p0.999:  10.093 ms/op
                 existUser·p0.9999: 28.043 ms/op
                 existUser·p1.00:   28.672 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 283352
  mean =      3.387 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10639 
    [ 2.500,  5.000) = 267352 
    [ 5.000,  7.500) = 4293 
    [ 7.500, 10.000) = 728 
    [10.000, 12.500) = 84 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 42 
    [22.500, 25.000) = 83 
    [25.000, 27.500) = 111 

  Percentiles, ms/op:
      p(0.0000) =      0.401 ms/op
     p(50.0000) =      3.297 ms/op
     p(90.0000) =      3.752 ms/op
     p(95.0000) =      4.133 ms/op
     p(99.0000) =      5.726 ms/op
     p(99.9000) =     10.715 ms/op
     p(99.9900) =     26.935 ms/op
     p(99.9990) =     28.525 ms/op
     p(99.9999) =     28.672 ms/op
    p(100.0000) =     28.672 ms/op


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
# Warmup Iteration   1: 10.712 ±(99.9%) 0.123 ms/op
# Warmup Iteration   2: 3.989 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.894 ±(99.9%) 0.015 ms/op
Iteration   1: 3.501 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.264 ms/op
                 getUser·p0.50:   3.363 ms/op
                 getUser·p0.90:   3.830 ms/op
                 getUser·p0.95:   4.084 ms/op
                 getUser·p0.99:   6.691 ms/op
                 getUser·p0.999:  11.944 ms/op
                 getUser·p0.9999: 24.740 ms/op
                 getUser·p1.00:   25.297 ms/op

Iteration   2: 3.492 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.655 ms/op
                 getUser·p0.50:   3.310 ms/op
                 getUser·p0.90:   3.785 ms/op
                 getUser·p0.95:   4.235 ms/op
                 getUser·p0.99:   7.111 ms/op
                 getUser·p0.999:  23.427 ms/op
                 getUser·p0.9999: 26.741 ms/op
                 getUser·p1.00:   28.803 ms/op

Iteration   3: 3.455 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.638 ms/op
                 getUser·p0.50:   3.326 ms/op
                 getUser·p0.90:   3.744 ms/op
                 getUser·p0.95:   4.006 ms/op
                 getUser·p0.99:   6.021 ms/op
                 getUser·p0.999:  24.495 ms/op
                 getUser·p0.9999: 32.571 ms/op
                 getUser·p1.00:   33.554 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 275411
  mean =      3.482 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 957 
    [ 2.500,  5.000) = 265994 
    [ 5.000,  7.500) = 7047 
    [ 7.500, 10.000) = 911 
    [10.000, 12.500) = 243 
    [12.500, 15.000) = 2 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 113 
    [25.000, 27.500) = 90 
    [27.500, 30.000) = 19 
    [30.000, 32.500) = 19 
    [32.500, 35.000) = 13 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.264 ms/op
     p(50.0000) =      3.330 ms/op
     p(90.0000) =      3.793 ms/op
     p(95.0000) =      4.108 ms/op
     p(99.0000) =      6.791 ms/op
     p(99.9000) =     11.960 ms/op
     p(99.9900) =     30.915 ms/op
     p(99.9990) =     33.390 ms/op
     p(99.9999) =     33.554 ms/op
    p(100.0000) =     33.554 ms/op


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
# Warmup Iteration   1: 10.452 ±(99.9%) 0.156 ms/op
# Warmup Iteration   2: 4.334 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.198 ±(99.9%) 0.014 ms/op
Iteration   1: 4.044 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.538 ms/op
                 listUser·p0.50:   3.871 ms/op
                 listUser·p0.90:   4.489 ms/op
                 listUser·p0.95:   4.710 ms/op
                 listUser·p0.99:   7.307 ms/op
                 listUser·p0.999:  20.412 ms/op
                 listUser·p0.9999: 25.402 ms/op
                 listUser·p1.00:   27.591 ms/op

Iteration   2: 4.182 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.322 ms/op
                 listUser·p0.50:   3.994 ms/op
                 listUser·p0.90:   4.547 ms/op
                 listUser·p0.95:   5.186 ms/op
                 listUser·p0.99:   8.118 ms/op
                 listUser·p0.999:  18.907 ms/op
                 listUser·p0.9999: 22.282 ms/op
                 listUser·p1.00:   22.413 ms/op

Iteration   3: 3.938 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.837 ms/op
                 listUser·p0.50:   3.797 ms/op
                 listUser·p0.90:   4.293 ms/op
                 listUser·p0.95:   4.522 ms/op
                 listUser·p0.99:   6.586 ms/op
                 listUser·p0.999:  16.466 ms/op
                 listUser·p0.9999: 20.695 ms/op
                 listUser·p1.00:   22.675 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 236673
  mean =      4.052 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 40 
    [ 2.500,  5.000) = 227960 
    [ 5.000,  7.500) = 6124 
    [ 7.500, 10.000) = 1544 
    [10.000, 12.500) = 486 
    [12.500, 15.000) = 142 
    [15.000, 17.500) = 92 
    [17.500, 20.000) = 126 
    [20.000, 22.500) = 113 
    [22.500, 25.000) = 34 
    [25.000, 27.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      1.538 ms/op
     p(50.0000) =      3.867 ms/op
     p(90.0000) =      4.456 ms/op
     p(95.0000) =      4.735 ms/op
     p(99.0000) =      7.627 ms/op
     p(99.9000) =     18.688 ms/op
     p(99.9900) =     24.248 ms/op
     p(99.9990) =     26.937 ms/op
     p(99.9999) =     27.591 ms/op
    p(100.0000) =     27.591 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.858 ± 9.658  ops/ms
ClientPb.existUser                       thrpt       3   9.080 ± 1.257  ops/ms
ClientPb.getUser                         thrpt       3   8.798 ± 7.831  ops/ms
ClientPb.listUser                        thrpt       3   7.857 ± 2.881  ops/ms
ClientPb.createUser                       avgt       3   3.523 ± 1.360   ms/op
ClientPb.existUser                        avgt       3   3.354 ± 0.996   ms/op
ClientPb.getUser                          avgt       3   3.401 ± 0.630   ms/op
ClientPb.listUser                         avgt       3   4.001 ± 2.148   ms/op
ClientPb.createUser                     sample  273924   3.505 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.284           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.334           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.059           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.522           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.119           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.683           ms/op
ClientPb.createUser:createUser·p0.9999  sample          29.032           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.573           ms/op
ClientPb.existUser                      sample  283352   3.387 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.401           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.297           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.752           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.133           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.726           ms/op
ClientPb.existUser:existUser·p0.999     sample          10.715           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.935           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.672           ms/op
ClientPb.getUser                        sample  275411   3.482 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.264           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.330           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.793           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.108           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.791           ms/op
ClientPb.getUser:getUser·p0.999         sample          11.960           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.915           ms/op
ClientPb.getUser:getUser·p1.00          sample          33.554           ms/op
ClientPb.listUser                       sample  236673   4.052 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.538           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.867           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.456           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.735           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.627           ms/op
ClientPb.listUser:listUser·p0.999       sample          18.688           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.248           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.591           ms/op
