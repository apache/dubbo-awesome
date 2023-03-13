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
# Warmup Iteration   1: 1.033 ops/ms
# Warmup Iteration   2: 2.510 ops/ms
# Warmup Iteration   3: 5.373 ops/ms
Iteration   1: 5.453 ops/ms
Iteration   2: 5.869 ops/ms
Iteration   3: 6.045 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.789 ±(99.9%) 5.544 ops/ms [Average]
  (min, avg, max) = (5.453, 5.789, 6.045), stdev = 0.304
  CI (99.9%): [0.245, 11.334] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:14
# Fork: 1 of 1
# Warmup Iteration   1: 1.871 ops/ms
# Warmup Iteration   2: 5.080 ops/ms
# Warmup Iteration   3: 5.960 ops/ms
Iteration   1: 6.253 ops/ms
Iteration   2: 6.249 ops/ms
Iteration   3: 6.285 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.262 ±(99.9%) 0.362 ops/ms [Average]
  (min, avg, max) = (6.249, 6.262, 6.285), stdev = 0.020
  CI (99.9%): [5.900, 6.625] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:06
# Fork: 1 of 1
# Warmup Iteration   1: 1.570 ops/ms
# Warmup Iteration   2: 4.317 ops/ms
# Warmup Iteration   3: 5.520 ops/ms
Iteration   1: 5.788 ops/ms
Iteration   2: 5.851 ops/ms
Iteration   3: 5.820 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.820 ±(99.9%) 0.575 ops/ms [Average]
  (min, avg, max) = (5.788, 5.820, 5.851), stdev = 0.032
  CI (99.9%): [5.244, 6.395] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:57
# Fork: 1 of 1
# Warmup Iteration   1: 1.489 ops/ms
# Warmup Iteration   2: 4.165 ops/ms
# Warmup Iteration   3: 4.842 ops/ms
Iteration   1: 5.108 ops/ms
Iteration   2: 5.003 ops/ms
Iteration   3: 5.121 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.077 ±(99.9%) 1.179 ops/ms [Average]
  (min, avg, max) = (5.003, 5.077, 5.121), stdev = 0.065
  CI (99.9%): [3.898, 6.256] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 19.270 ±(99.9%) 0.130 ms/op
# Warmup Iteration   2: 6.403 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.608 ±(99.9%) 0.011 ms/op
Iteration   1: 5.407 ±(99.9%) 0.010 ms/op
Iteration   2: 5.220 ±(99.9%) 0.015 ms/op
Iteration   3: 5.194 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.274 ±(99.9%) 2.121 ms/op [Average]
  (min, avg, max) = (5.194, 5.274, 5.407), stdev = 0.116
  CI (99.9%): [3.153, 7.395] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 16.645 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 5.740 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 5.251 ±(99.9%) 0.010 ms/op
Iteration   1: 4.953 ±(99.9%) 0.012 ms/op
Iteration   2: 5.157 ±(99.9%) 0.007 ms/op
Iteration   3: 4.922 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.011 ±(99.9%) 2.322 ms/op [Average]
  (min, avg, max) = (4.922, 5.011, 5.157), stdev = 0.127
  CI (99.9%): [2.688, 7.333] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 17.283 ±(99.9%) 0.086 ms/op
# Warmup Iteration   2: 6.382 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 5.571 ±(99.9%) 0.008 ms/op
Iteration   1: 5.361 ±(99.9%) 0.012 ms/op
Iteration   2: 5.586 ±(99.9%) 0.015 ms/op
Iteration   3: 5.425 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.457 ±(99.9%) 2.111 ms/op [Average]
  (min, avg, max) = (5.361, 5.457, 5.586), stdev = 0.116
  CI (99.9%): [3.346, 7.568] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 18.372 ±(99.9%) 0.086 ms/op
# Warmup Iteration   2: 7.363 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 6.416 ±(99.9%) 0.013 ms/op
Iteration   1: 6.366 ±(99.9%) 0.015 ms/op
Iteration   2: 6.723 ±(99.9%) 0.012 ms/op
Iteration   3: 6.619 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.569 ±(99.9%) 3.348 ms/op [Average]
  (min, avg, max) = (6.366, 6.569, 6.723), stdev = 0.184
  CI (99.9%): [3.221, 9.917] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 16.315 ±(99.9%) 0.272 ms/op
# Warmup Iteration   2: 7.276 ±(99.9%) 0.049 ms/op
# Warmup Iteration   3: 5.921 ±(99.9%) 0.031 ms/op
Iteration   1: 5.750 ±(99.9%) 0.024 ms/op
                 createUser·p0.00:   1.309 ms/op
                 createUser·p0.50:   5.333 ms/op
                 createUser·p0.90:   7.537 ms/op
                 createUser·p0.95:   8.634 ms/op
                 createUser·p0.99:   12.075 ms/op
                 createUser·p0.999:  25.690 ms/op
                 createUser·p0.9999: 34.013 ms/op
                 createUser·p1.00:   34.341 ms/op

Iteration   2: 5.563 ±(99.9%) 0.023 ms/op
                 createUser·p0.00:   2.195 ms/op
                 createUser·p0.50:   5.210 ms/op
                 createUser·p0.90:   7.152 ms/op
                 createUser·p0.95:   8.208 ms/op
                 createUser·p0.99:   11.567 ms/op
                 createUser·p0.999:  25.606 ms/op
                 createUser·p0.9999: 28.459 ms/op
                 createUser·p1.00:   29.721 ms/op

Iteration   3: 5.531 ±(99.9%) 0.023 ms/op
                 createUser·p0.00:   2.253 ms/op
                 createUser·p0.50:   5.186 ms/op
                 createUser·p0.90:   7.004 ms/op
                 createUser·p0.95:   7.971 ms/op
                 createUser·p0.99:   10.945 ms/op
                 createUser·p0.999:  30.892 ms/op
                 createUser·p0.9999: 37.899 ms/op
                 createUser·p1.00:   38.863 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 171040
  mean =      5.613 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 29 
    [ 2.500,  5.000) = 66381 
    [ 5.000,  7.500) = 90323 
    [ 7.500, 10.000) = 11119 
    [10.000, 12.500) = 1946 
    [12.500, 15.000) = 753 
    [15.000, 17.500) = 158 
    [17.500, 20.000) = 91 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 55 
    [27.500, 30.000) = 45 
    [30.000, 32.500) = 31 
    [32.500, 35.000) = 31 
    [35.000, 37.500) = 21 

  Percentiles, ms/op:
      p(0.0000) =      1.309 ms/op
     p(50.0000) =      5.243 ms/op
     p(90.0000) =      7.250 ms/op
     p(95.0000) =      8.249 ms/op
     p(99.0000) =     11.583 ms/op
     p(99.9000) =     26.016 ms/op
     p(99.9900) =     37.087 ms/op
     p(99.9990) =     38.816 ms/op
     p(99.9999) =     38.863 ms/op
    p(100.0000) =     38.863 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 15.928 ±(99.9%) 0.291 ms/op
# Warmup Iteration   2: 6.247 ±(99.9%) 0.040 ms/op
# Warmup Iteration   3: 5.616 ±(99.9%) 0.024 ms/op
Iteration   1: 5.424 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   2.013 ms/op
                 existUser·p0.50:   5.038 ms/op
                 existUser·p0.90:   7.070 ms/op
                 existUser·p0.95:   8.241 ms/op
                 existUser·p0.99:   11.682 ms/op
                 existUser·p0.999:  17.201 ms/op
                 existUser·p0.9999: 30.779 ms/op
                 existUser·p1.00:   31.621 ms/op

Iteration   2: 5.435 ±(99.9%) 0.023 ms/op
                 existUser·p0.00:   2.216 ms/op
                 existUser·p0.50:   4.997 ms/op
                 existUser·p0.90:   7.152 ms/op
                 existUser·p0.95:   8.323 ms/op
                 existUser·p0.99:   11.846 ms/op
                 existUser·p0.999:  25.147 ms/op
                 existUser·p0.9999: 32.418 ms/op
                 existUser·p1.00:   35.783 ms/op

Iteration   3: 5.372 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   2.339 ms/op
                 existUser·p0.50:   5.030 ms/op
                 existUser·p0.90:   6.889 ms/op
                 existUser·p0.95:   7.864 ms/op
                 existUser·p0.99:   10.635 ms/op
                 existUser·p0.999:  27.804 ms/op
                 existUser·p0.9999: 33.478 ms/op
                 existUser·p1.00:   34.669 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 177355
  mean =      5.410 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 37 
    [ 2.500,  5.000) = 86707 
    [ 5.000,  7.500) = 77379 
    [ 7.500, 10.000) = 10133 
    [10.000, 12.500) = 1907 
    [12.500, 15.000) = 708 
    [15.000, 17.500) = 275 
    [17.500, 20.000) = 48 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 29 
    [27.500, 30.000) = 57 
    [30.000, 32.500) = 44 
    [32.500, 35.000) = 23 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      2.013 ms/op
     p(50.0000) =      5.022 ms/op
     p(90.0000) =      7.021 ms/op
     p(95.0000) =      8.126 ms/op
     p(99.0000) =     11.329 ms/op
     p(99.9000) =     18.699 ms/op
     p(99.9900) =     32.827 ms/op
     p(99.9990) =     35.580 ms/op
     p(99.9999) =     35.783 ms/op
    p(100.0000) =     35.783 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 17.272 ±(99.9%) 0.263 ms/op
# Warmup Iteration   2: 6.193 ±(99.9%) 0.032 ms/op
# Warmup Iteration   3: 5.349 ±(99.9%) 0.020 ms/op
Iteration   1: 5.437 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   1.718 ms/op
                 getUser·p0.50:   5.071 ms/op
                 getUser·p0.90:   6.996 ms/op
                 getUser·p0.95:   8.159 ms/op
                 getUser·p0.99:   11.026 ms/op
                 getUser·p0.999:  21.429 ms/op
                 getUser·p0.9999: 28.869 ms/op
                 getUser·p1.00:   29.196 ms/op

Iteration   2: 5.549 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   2.302 ms/op
                 getUser·p0.50:   5.112 ms/op
                 getUser·p0.90:   7.291 ms/op
                 getUser·p0.95:   8.569 ms/op
                 getUser·p0.99:   11.598 ms/op
                 getUser·p0.999:  28.555 ms/op
                 getUser·p0.9999: 33.013 ms/op
                 getUser·p1.00:   33.751 ms/op

Iteration   3: 5.254 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   2.245 ms/op
                 getUser·p0.50:   4.923 ms/op
                 getUser·p0.90:   6.644 ms/op
                 getUser·p0.95:   7.594 ms/op
                 getUser·p0.99:   10.322 ms/op
                 getUser·p0.999:  15.791 ms/op
                 getUser·p0.9999: 46.590 ms/op
                 getUser·p1.00:   47.186 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 177223
  mean =      5.410 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 85610 
    [ 5.000, 10.000) = 88531 
    [10.000, 15.000) = 2652 
    [15.000, 20.000) = 218 
    [20.000, 25.000) = 84 
    [25.000, 30.000) = 56 
    [30.000, 35.000) = 40 
    [35.000, 40.000) = 2 
    [40.000, 45.000) = 20 

  Percentiles, ms/op:
      p(0.0000) =      1.718 ms/op
     p(50.0000) =      5.038 ms/op
     p(90.0000) =      6.955 ms/op
     p(95.0000) =      8.110 ms/op
     p(99.0000) =     10.994 ms/op
     p(99.9000) =     20.738 ms/op
     p(99.9900) =     44.171 ms/op
     p(99.9990) =     47.135 ms/op
     p(99.9999) =     47.186 ms/op
    p(100.0000) =     47.186 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 19.179 ±(99.9%) 0.338 ms/op
# Warmup Iteration   2: 8.125 ±(99.9%) 0.060 ms/op
# Warmup Iteration   3: 6.640 ±(99.9%) 0.030 ms/op
Iteration   1: 6.538 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   2.511 ms/op
                 listUser·p0.50:   6.103 ms/op
                 listUser·p0.90:   8.298 ms/op
                 listUser·p0.95:   9.568 ms/op
                 listUser·p0.99:   13.222 ms/op
                 listUser·p0.999:  27.525 ms/op
                 listUser·p0.9999: 30.069 ms/op
                 listUser·p1.00:   31.850 ms/op

Iteration   2: 6.247 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   2.769 ms/op
                 listUser·p0.50:   5.751 ms/op
                 listUser·p0.90:   7.995 ms/op
                 listUser·p0.95:   9.175 ms/op
                 listUser·p0.99:   12.550 ms/op
                 listUser·p0.999:  27.356 ms/op
                 listUser·p0.9999: 29.243 ms/op
                 listUser·p1.00:   29.753 ms/op

Iteration   3: 6.441 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   2.585 ms/op
                 listUser·p0.50:   5.964 ms/op
                 listUser·p0.90:   8.323 ms/op
                 listUser·p0.95:   9.617 ms/op
                 listUser·p0.99:   12.820 ms/op
                 listUser·p0.999:  23.473 ms/op
                 listUser·p0.9999: 31.457 ms/op
                 listUser·p1.00:   31.883 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 149725
  mean =      6.407 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 11738 
    [ 5.000,  7.500) = 114886 
    [ 7.500, 10.000) = 17435 
    [10.000, 12.500) = 3886 
    [12.500, 15.000) = 1067 
    [15.000, 17.500) = 280 
    [17.500, 20.000) = 68 
    [20.000, 22.500) = 98 
    [22.500, 25.000) = 46 
    [25.000, 27.500) = 105 
    [27.500, 30.000) = 103 
    [30.000, 32.500) = 13 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.511 ms/op
     p(50.0000) =      5.947 ms/op
     p(90.0000) =      8.192 ms/op
     p(95.0000) =      9.454 ms/op
     p(99.0000) =     12.927 ms/op
     p(99.9000) =     27.230 ms/op
     p(99.9900) =     29.983 ms/op
     p(99.9990) =     31.867 ms/op
     p(99.9999) =     31.883 ms/op
    p(100.0000) =     31.883 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.789 ± 5.544  ops/ms
ClientPb.existUser                       thrpt       3   6.262 ± 0.362  ops/ms
ClientPb.getUser                         thrpt       3   5.820 ± 0.575  ops/ms
ClientPb.listUser                        thrpt       3   5.077 ± 1.179  ops/ms
ClientPb.createUser                       avgt       3   5.274 ± 2.121   ms/op
ClientPb.existUser                        avgt       3   5.011 ± 2.322   ms/op
ClientPb.getUser                          avgt       3   5.457 ± 2.111   ms/op
ClientPb.listUser                         avgt       3   6.569 ± 3.348   ms/op
ClientPb.createUser                     sample  171040   5.613 ± 0.014   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.309           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.243           ms/op
ClientPb.createUser:createUser·p0.90    sample           7.250           ms/op
ClientPb.createUser:createUser·p0.95    sample           8.249           ms/op
ClientPb.createUser:createUser·p0.99    sample          11.583           ms/op
ClientPb.createUser:createUser·p0.999   sample          26.016           ms/op
ClientPb.createUser:createUser·p0.9999  sample          37.087           ms/op
ClientPb.createUser:createUser·p1.00    sample          38.863           ms/op
ClientPb.existUser                      sample  177355   5.410 ± 0.013   ms/op
ClientPb.existUser:existUser·p0.00      sample           2.013           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.022           ms/op
ClientPb.existUser:existUser·p0.90      sample           7.021           ms/op
ClientPb.existUser:existUser·p0.95      sample           8.126           ms/op
ClientPb.existUser:existUser·p0.99      sample          11.329           ms/op
ClientPb.existUser:existUser·p0.999     sample          18.699           ms/op
ClientPb.existUser:existUser·p0.9999    sample          32.827           ms/op
ClientPb.existUser:existUser·p1.00      sample          35.783           ms/op
ClientPb.getUser                        sample  177223   5.410 ± 0.013   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.718           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.038           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.955           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.110           ms/op
ClientPb.getUser:getUser·p0.99          sample          10.994           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.738           ms/op
ClientPb.getUser:getUser·p0.9999        sample          44.171           ms/op
ClientPb.getUser:getUser·p1.00          sample          47.186           ms/op
ClientPb.listUser                       sample  149725   6.407 ± 0.015   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.511           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.947           ms/op
ClientPb.listUser:listUser·p0.90        sample           8.192           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.454           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.927           ms/op
ClientPb.listUser:listUser·p0.999       sample          27.230           ms/op
ClientPb.listUser:listUser·p0.9999      sample          29.983           ms/op
ClientPb.listUser:listUser·p1.00        sample          31.883           ms/op
