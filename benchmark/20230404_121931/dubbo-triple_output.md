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
# Warmup Iteration   1: 2.469 ops/ms
# Warmup Iteration   2: 6.157 ops/ms
# Warmup Iteration   3: 8.969 ops/ms
Iteration   1: 9.316 ops/ms
Iteration   2: 9.300 ops/ms
Iteration   3: 9.219 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.278 ±(99.9%) 0.947 ops/ms [Average]
  (min, avg, max) = (9.219, 9.278, 9.316), stdev = 0.052
  CI (99.9%): [8.331, 10.226] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 2.974 ops/ms
# Warmup Iteration   2: 8.862 ops/ms
# Warmup Iteration   3: 9.917 ops/ms
Iteration   1: 10.266 ops/ms
Iteration   2: 9.674 ops/ms
Iteration   3: 9.999 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.980 ±(99.9%) 5.410 ops/ms [Average]
  (min, avg, max) = (9.674, 9.980, 10.266), stdev = 0.297
  CI (99.9%): [4.569, 15.390] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 2.966 ops/ms
# Warmup Iteration   2: 8.738 ops/ms
# Warmup Iteration   3: 8.393 ops/ms
Iteration   1: 9.166 ops/ms
Iteration   2: 9.285 ops/ms
Iteration   3: 9.395 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.282 ±(99.9%) 2.090 ops/ms [Average]
  (min, avg, max) = (9.166, 9.282, 9.395), stdev = 0.115
  CI (99.9%): [7.191, 11.372] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.812 ops/ms
# Warmup Iteration   2: 7.688 ops/ms
# Warmup Iteration   3: 8.148 ops/ms
Iteration   1: 7.994 ops/ms
Iteration   2: 8.058 ops/ms
Iteration   3: 7.796 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.949 ±(99.9%) 2.492 ops/ms [Average]
  (min, avg, max) = (7.796, 7.949, 8.058), stdev = 0.137
  CI (99.9%): [5.457, 10.441] (assumes normal distribution)


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
# Warmup Iteration   1: 10.069 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.709 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.585 ±(99.9%) 0.005 ms/op
Iteration   1: 3.336 ±(99.9%) 0.010 ms/op
Iteration   2: 3.399 ±(99.9%) 0.006 ms/op
Iteration   3: 3.373 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.369 ±(99.9%) 0.580 ms/op [Average]
  (min, avg, max) = (3.336, 3.369, 3.399), stdev = 0.032
  CI (99.9%): [2.789, 3.949] (assumes normal distribution)


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
# Warmup Iteration   1: 7.856 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.540 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.368 ±(99.9%) 0.003 ms/op
Iteration   1: 3.217 ±(99.9%) 0.007 ms/op
Iteration   2: 3.283 ±(99.9%) 0.006 ms/op
Iteration   3: 3.286 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.262 ±(99.9%) 0.712 ms/op [Average]
  (min, avg, max) = (3.217, 3.262, 3.286), stdev = 0.039
  CI (99.9%): [2.551, 3.974] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 9.043 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.615 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.397 ±(99.9%) 0.002 ms/op
Iteration   1: 3.436 ±(99.9%) 0.008 ms/op
Iteration   2: 3.398 ±(99.9%) 0.005 ms/op
Iteration   3: 3.244 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.360 ±(99.9%) 1.857 ms/op [Average]
  (min, avg, max) = (3.244, 3.360, 3.436), stdev = 0.102
  CI (99.9%): [1.503, 5.216] (assumes normal distribution)


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
# Warmup Iteration   1: 11.357 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 4.351 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.951 ±(99.9%) 0.010 ms/op
Iteration   1: 3.954 ±(99.9%) 0.008 ms/op
Iteration   2: 3.963 ±(99.9%) 0.010 ms/op
Iteration   3: 3.864 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.927 ±(99.9%) 1.004 ms/op [Average]
  (min, avg, max) = (3.864, 3.927, 3.963), stdev = 0.055
  CI (99.9%): [2.923, 4.931] (assumes normal distribution)


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
# Warmup Iteration   1: 8.689 ±(99.9%) 0.112 ms/op
# Warmup Iteration   2: 4.037 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.465 ±(99.9%) 0.010 ms/op
Iteration   1: 3.517 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.137 ms/op
                 createUser·p0.50:   3.375 ms/op
                 createUser·p0.90:   4.084 ms/op
                 createUser·p0.95:   4.432 ms/op
                 createUser·p0.99:   6.177 ms/op
                 createUser·p0.999:  19.895 ms/op
                 createUser·p0.9999: 23.885 ms/op
                 createUser·p1.00:   25.199 ms/op

Iteration   2: 3.516 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.217 ms/op
                 createUser·p0.50:   3.310 ms/op
                 createUser·p0.90:   4.293 ms/op
                 createUser·p0.95:   4.669 ms/op
                 createUser·p0.99:   5.906 ms/op
                 createUser·p0.999:  21.823 ms/op
                 createUser·p0.9999: 25.392 ms/op
                 createUser·p1.00:   26.083 ms/op

Iteration   3: 3.464 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.667 ms/op
                 createUser·p0.50:   3.371 ms/op
                 createUser·p0.90:   3.936 ms/op
                 createUser·p0.95:   4.317 ms/op
                 createUser·p0.99:   6.463 ms/op
                 createUser·p0.999:  16.700 ms/op
                 createUser·p0.9999: 25.875 ms/op
                 createUser·p1.00:   26.673 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 274229
  mean =      3.499 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12573 
    [ 2.500,  5.000) = 253210 
    [ 5.000,  7.500) = 7195 
    [ 7.500, 10.000) = 717 
    [10.000, 12.500) = 154 
    [12.500, 15.000) = 42 
    [15.000, 17.500) = 64 
    [17.500, 20.000) = 34 
    [20.000, 22.500) = 91 
    [22.500, 25.000) = 104 
    [25.000, 27.500) = 45 

  Percentiles, ms/op:
      p(0.0000) =      1.137 ms/op
     p(50.0000) =      3.363 ms/op
     p(90.0000) =      4.096 ms/op
     p(95.0000) =      4.530 ms/op
     p(99.0000) =      6.169 ms/op
     p(99.9000) =     17.574 ms/op
     p(99.9900) =     25.297 ms/op
     p(99.9990) =     26.479 ms/op
     p(99.9999) =     26.673 ms/op
    p(100.0000) =     26.673 ms/op


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
# Warmup Iteration   1: 7.919 ±(99.9%) 0.101 ms/op
# Warmup Iteration   2: 3.519 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.264 ±(99.9%) 0.009 ms/op
Iteration   1: 3.292 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.726 ms/op
                 existUser·p0.50:   3.265 ms/op
                 existUser·p0.90:   3.523 ms/op
                 existUser·p0.95:   3.895 ms/op
                 existUser·p0.99:   5.947 ms/op
                 existUser·p0.999:  8.913 ms/op
                 existUser·p0.9999: 22.203 ms/op
                 existUser·p1.00:   22.708 ms/op

Iteration   2: 3.423 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.221 ms/op
                 existUser·p0.50:   3.203 ms/op
                 existUser·p0.90:   4.047 ms/op
                 existUser·p0.95:   4.817 ms/op
                 existUser·p0.99:   6.095 ms/op
                 existUser·p0.999:  21.463 ms/op
                 existUser·p0.9999: 25.461 ms/op
                 existUser·p1.00:   26.345 ms/op

Iteration   3: 3.318 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.888 ms/op
                 existUser·p0.50:   3.183 ms/op
                 existUser·p0.90:   3.690 ms/op
                 existUser·p0.95:   4.055 ms/op
                 existUser·p0.99:   6.259 ms/op
                 existUser·p0.999:  16.758 ms/op
                 existUser·p0.9999: 26.718 ms/op
                 existUser·p1.00:   28.115 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 286782
  mean =      3.343 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11929 
    [ 2.500,  5.000) = 267906 
    [ 5.000,  7.500) = 6052 
    [ 7.500, 10.000) = 499 
    [10.000, 12.500) = 124 
    [12.500, 15.000) = 16 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 107 
    [22.500, 25.000) = 76 
    [25.000, 27.500) = 42 

  Percentiles, ms/op:
      p(0.0000) =      0.888 ms/op
     p(50.0000) =      3.236 ms/op
     p(90.0000) =      3.723 ms/op
     p(95.0000) =      4.325 ms/op
     p(99.0000) =      6.095 ms/op
     p(99.9000) =     12.091 ms/op
     p(99.9900) =     25.875 ms/op
     p(99.9990) =     28.049 ms/op
     p(99.9999) =     28.115 ms/op
    p(100.0000) =     28.115 ms/op


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
# Warmup Iteration   1: 8.118 ±(99.9%) 0.108 ms/op
# Warmup Iteration   2: 3.746 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.552 ±(99.9%) 0.013 ms/op
Iteration   1: 3.550 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.878 ms/op
                 getUser·p0.50:   3.355 ms/op
                 getUser·p0.90:   4.260 ms/op
                 getUser·p0.95:   4.899 ms/op
                 getUser·p0.99:   6.357 ms/op
                 getUser·p0.999:  10.027 ms/op
                 getUser·p0.9999: 28.115 ms/op
                 getUser·p1.00:   28.672 ms/op

Iteration   2: 3.386 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.169 ms/op
                 getUser·p0.50:   3.240 ms/op
                 getUser·p0.90:   3.707 ms/op
                 getUser·p0.95:   4.227 ms/op
                 getUser·p0.99:   5.939 ms/op
                 getUser·p0.999:  20.933 ms/op
                 getUser·p0.9999: 29.131 ms/op
                 getUser·p1.00:   29.753 ms/op

Iteration   3: 3.424 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.251 ms/op
                 getUser·p0.50:   3.248 ms/op
                 getUser·p0.90:   3.830 ms/op
                 getUser·p0.95:   4.448 ms/op
                 getUser·p0.99:   6.722 ms/op
                 getUser·p0.999:  18.186 ms/op
                 getUser·p0.9999: 26.903 ms/op
                 getUser·p1.00:   29.032 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 277977
  mean =      3.452 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7527 
    [ 2.500,  5.000) = 259976 
    [ 5.000,  7.500) = 9163 
    [ 7.500, 10.000) = 918 
    [10.000, 12.500) = 123 
    [12.500, 15.000) = 14 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 76 
    [22.500, 25.000) = 66 
    [25.000, 27.500) = 40 

  Percentiles, ms/op:
      p(0.0000) =      0.878 ms/op
     p(50.0000) =      3.301 ms/op
     p(90.0000) =      3.965 ms/op
     p(95.0000) =      4.620 ms/op
     p(99.0000) =      6.308 ms/op
     p(99.9000) =     11.830 ms/op
     p(99.9900) =     28.180 ms/op
     p(99.9990) =     29.662 ms/op
     p(99.9999) =     29.753 ms/op
    p(100.0000) =     29.753 ms/op


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
# Warmup Iteration   1: 10.518 ±(99.9%) 0.132 ms/op
# Warmup Iteration   2: 4.438 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.194 ±(99.9%) 0.013 ms/op
Iteration   1: 4.008 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.778 ms/op
                 listUser·p0.50:   3.846 ms/op
                 listUser·p0.90:   4.293 ms/op
                 listUser·p0.95:   4.588 ms/op
                 listUser·p0.99:   7.283 ms/op
                 listUser·p0.999:  22.151 ms/op
                 listUser·p0.9999: 30.934 ms/op
                 listUser·p1.00:   32.604 ms/op

Iteration   2: 3.992 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.475 ms/op
                 listUser·p0.50:   3.916 ms/op
                 listUser·p0.90:   4.317 ms/op
                 listUser·p0.95:   4.481 ms/op
                 listUser·p0.99:   6.529 ms/op
                 listUser·p0.999:  16.013 ms/op
                 listUser·p0.9999: 24.871 ms/op
                 listUser·p1.00:   25.428 ms/op

Iteration   3: 3.962 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.281 ms/op
                 listUser·p0.50:   3.838 ms/op
                 listUser·p0.90:   4.497 ms/op
                 listUser·p0.95:   4.891 ms/op
                 listUser·p0.99:   7.381 ms/op
                 listUser·p0.999:  14.324 ms/op
                 listUser·p0.9999: 22.348 ms/op
                 listUser·p1.00:   22.446 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 240778
  mean =      3.987 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 52 
    [ 2.500,  5.000) = 232448 
    [ 5.000,  7.500) = 6363 
    [ 7.500, 10.000) = 1230 
    [10.000, 12.500) = 173 
    [12.500, 15.000) = 209 
    [15.000, 17.500) = 77 
    [17.500, 20.000) = 57 
    [20.000, 22.500) = 60 
    [22.500, 25.000) = 71 
    [25.000, 27.500) = 8 
    [27.500, 30.000) = 10 
    [30.000, 32.500) = 19 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.475 ms/op
     p(50.0000) =      3.854 ms/op
     p(90.0000) =      4.342 ms/op
     p(95.0000) =      4.661 ms/op
     p(99.0000) =      7.055 ms/op
     p(99.9000) =     16.273 ms/op
     p(99.9900) =     28.962 ms/op
     p(99.9990) =     32.348 ms/op
     p(99.9999) =     32.604 ms/op
    p(100.0000) =     32.604 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.278 ± 0.947  ops/ms
ClientPb.existUser                       thrpt       3   9.980 ± 5.410  ops/ms
ClientPb.getUser                         thrpt       3   9.282 ± 2.090  ops/ms
ClientPb.listUser                        thrpt       3   7.949 ± 2.492  ops/ms
ClientPb.createUser                       avgt       3   3.369 ± 0.580   ms/op
ClientPb.existUser                        avgt       3   3.262 ± 0.712   ms/op
ClientPb.getUser                          avgt       3   3.360 ± 1.857   ms/op
ClientPb.listUser                         avgt       3   3.927 ± 1.004   ms/op
ClientPb.createUser                     sample  274229   3.499 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.137           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.363           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.096           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.530           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.169           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.574           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.297           ms/op
ClientPb.createUser:createUser·p1.00    sample          26.673           ms/op
ClientPb.existUser                      sample  286782   3.343 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.888           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.236           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.723           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.325           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.095           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.091           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.875           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.115           ms/op
ClientPb.getUser                        sample  277977   3.452 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.878           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.301           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.965           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.620           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.308           ms/op
ClientPb.getUser:getUser·p0.999         sample          11.830           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.180           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.753           ms/op
ClientPb.listUser                       sample  240778   3.987 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.475           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.854           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.342           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.661           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.055           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.273           ms/op
ClientPb.listUser:listUser·p0.9999      sample          28.962           ms/op
ClientPb.listUser:listUser·p1.00        sample          32.604           ms/op
