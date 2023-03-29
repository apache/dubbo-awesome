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
# Warmup Iteration   1: 0.983 ops/ms
# Warmup Iteration   2: 2.439 ops/ms
# Warmup Iteration   3: 5.408 ops/ms
Iteration   1: 5.655 ops/ms
Iteration   2: 6.113 ops/ms
Iteration   3: 6.092 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.954 ±(99.9%) 4.720 ops/ms [Average]
  (min, avg, max) = (5.655, 5.954, 6.113), stdev = 0.259
  CI (99.9%): [1.234, 10.673] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 1.545 ops/ms
# Warmup Iteration   2: 5.111 ops/ms
# Warmup Iteration   3: 6.165 ops/ms
Iteration   1: 6.538 ops/ms
Iteration   2: 6.337 ops/ms
Iteration   3: 6.547 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.474 ±(99.9%) 2.164 ops/ms [Average]
  (min, avg, max) = (6.337, 6.474, 6.547), stdev = 0.119
  CI (99.9%): [4.310, 8.639] (assumes normal distribution)


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
# Warmup Iteration   1: 1.403 ops/ms
# Warmup Iteration   2: 4.621 ops/ms
# Warmup Iteration   3: 5.914 ops/ms
Iteration   1: 5.766 ops/ms
Iteration   2: 6.068 ops/ms
Iteration   3: 6.194 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.009 ±(99.9%) 4.008 ops/ms [Average]
  (min, avg, max) = (5.766, 6.009, 6.194), stdev = 0.220
  CI (99.9%): [2.001, 10.018] (assumes normal distribution)


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
# Warmup Iteration   1: 1.567 ops/ms
# Warmup Iteration   2: 4.445 ops/ms
# Warmup Iteration   3: 5.261 ops/ms
Iteration   1: 5.339 ops/ms
Iteration   2: 5.292 ops/ms
Iteration   3: 5.378 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.336 ±(99.9%) 0.782 ops/ms [Average]
  (min, avg, max) = (5.292, 5.336, 5.378), stdev = 0.043
  CI (99.9%): [4.554, 6.118] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:51
# Fork: 1 of 1
# Warmup Iteration   1: 19.427 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 6.516 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 5.538 ±(99.9%) 0.008 ms/op
Iteration   1: 5.192 ±(99.9%) 0.017 ms/op
Iteration   2: 5.242 ±(99.9%) 0.017 ms/op
Iteration   3: 5.155 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.197 ±(99.9%) 0.802 ms/op [Average]
  (min, avg, max) = (5.155, 5.197, 5.242), stdev = 0.044
  CI (99.9%): [4.395, 5.998] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:45
# Fork: 1 of 1
# Warmup Iteration   1: 19.074 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 6.362 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 5.166 ±(99.9%) 0.011 ms/op
Iteration   1: 5.213 ±(99.9%) 0.011 ms/op
Iteration   2: 5.100 ±(99.9%) 0.008 ms/op
Iteration   3: 5.033 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.116 ±(99.9%) 1.663 ms/op [Average]
  (min, avg, max) = (5.033, 5.116, 5.213), stdev = 0.091
  CI (99.9%): [3.452, 6.779] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:38
# Fork: 1 of 1
# Warmup Iteration   1: 19.610 ±(99.9%) 0.128 ms/op
# Warmup Iteration   2: 7.551 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.364 ±(99.9%) 0.015 ms/op
Iteration   1: 5.405 ±(99.9%) 0.007 ms/op
Iteration   2: 5.184 ±(99.9%) 0.009 ms/op
Iteration   3: 5.135 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.241 ±(99.9%) 2.623 ms/op [Average]
  (min, avg, max) = (5.135, 5.241, 5.405), stdev = 0.144
  CI (99.9%): [2.619, 7.864] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 19.354 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 7.240 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 6.016 ±(99.9%) 0.013 ms/op
Iteration   1: 5.934 ±(99.9%) 0.017 ms/op
Iteration   2: 6.201 ±(99.9%) 0.019 ms/op
Iteration   3: 5.835 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.990 ±(99.9%) 3.455 ms/op [Average]
  (min, avg, max) = (5.835, 5.990, 6.201), stdev = 0.189
  CI (99.9%): [2.535, 9.444] (assumes normal distribution)


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
# Warmup Iteration   1: 17.657 ±(99.9%) 0.283 ms/op
# Warmup Iteration   2: 6.872 ±(99.9%) 0.046 ms/op
# Warmup Iteration   3: 5.677 ±(99.9%) 0.025 ms/op
Iteration   1: 5.341 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   2.183 ms/op
                 createUser·p0.50:   5.005 ms/op
                 createUser·p0.90:   6.619 ms/op
                 createUser·p0.95:   7.746 ms/op
                 createUser·p0.99:   11.354 ms/op
                 createUser·p0.999:  22.463 ms/op
                 createUser·p0.9999: 28.050 ms/op
                 createUser·p1.00:   29.032 ms/op

Iteration   2: 5.168 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   2.073 ms/op
                 createUser·p0.50:   4.907 ms/op
                 createUser·p0.90:   6.267 ms/op
                 createUser·p0.95:   7.152 ms/op
                 createUser·p0.99:   9.604 ms/op
                 createUser·p0.999:  24.100 ms/op
                 createUser·p0.9999: 28.928 ms/op
                 createUser·p1.00:   29.458 ms/op

Iteration   3: 5.172 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   2.433 ms/op
                 createUser·p0.50:   4.940 ms/op
                 createUser·p0.90:   6.169 ms/op
                 createUser·p0.95:   6.758 ms/op
                 createUser·p0.99:   9.699 ms/op
                 createUser·p0.999:  24.609 ms/op
                 createUser·p0.9999: 28.544 ms/op
                 createUser·p1.00:   30.900 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 183479
  mean =      5.225 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 44 
    [ 2.500,  5.000) = 97331 
    [ 5.000,  7.500) = 78371 
    [ 7.500, 10.000) = 5664 
    [10.000, 12.500) = 1275 
    [12.500, 15.000) = 446 
    [15.000, 17.500) = 62 
    [17.500, 20.000) = 49 
    [20.000, 22.500) = 42 
    [22.500, 25.000) = 62 
    [25.000, 27.500) = 81 
    [27.500, 30.000) = 50 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.073 ms/op
     p(50.0000) =      4.948 ms/op
     p(90.0000) =      6.324 ms/op
     p(95.0000) =      7.217 ms/op
     p(99.0000) =     10.371 ms/op
     p(99.9000) =     23.479 ms/op
     p(99.9900) =     28.267 ms/op
     p(99.9990) =     30.681 ms/op
     p(99.9999) =     30.900 ms/op
    p(100.0000) =     30.900 ms/op


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
# Warmup Iteration   1: 16.687 ±(99.9%) 0.245 ms/op
# Warmup Iteration   2: 5.939 ±(99.9%) 0.034 ms/op
# Warmup Iteration   3: 5.235 ±(99.9%) 0.019 ms/op
Iteration   1: 5.142 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   1.837 ms/op
                 existUser·p0.50:   4.841 ms/op
                 existUser·p0.90:   6.324 ms/op
                 existUser·p0.95:   7.209 ms/op
                 existUser·p0.99:   9.880 ms/op
                 existUser·p0.999:  23.750 ms/op
                 existUser·p0.9999: 27.092 ms/op
                 existUser·p1.00:   27.492 ms/op

Iteration   2: 5.031 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   2.249 ms/op
                 existUser·p0.50:   4.792 ms/op
                 existUser·p0.90:   5.947 ms/op
                 existUser·p0.95:   6.701 ms/op
                 existUser·p0.99:   9.454 ms/op
                 existUser·p0.999:  23.549 ms/op
                 existUser·p0.9999: 27.829 ms/op
                 existUser·p1.00:   28.344 ms/op

Iteration   3: 5.076 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   2.212 ms/op
                 existUser·p0.50:   4.760 ms/op
                 existUser·p0.90:   6.136 ms/op
                 existUser·p0.95:   7.225 ms/op
                 existUser·p0.99:   10.863 ms/op
                 existUser·p0.999:  26.827 ms/op
                 existUser·p0.9999: 31.034 ms/op
                 existUser·p1.00:   31.982 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 188800
  mean =      5.083 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 42 
    [ 2.500,  5.000) = 117715 
    [ 5.000,  7.500) = 63666 
    [ 7.500, 10.000) = 5400 
    [10.000, 12.500) = 1371 
    [12.500, 15.000) = 346 
    [15.000, 17.500) = 67 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 45 
    [25.000, 27.500) = 82 
    [27.500, 30.000) = 47 
    [30.000, 32.500) = 18 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.837 ms/op
     p(50.0000) =      4.792 ms/op
     p(90.0000) =      6.136 ms/op
     p(95.0000) =      7.045 ms/op
     p(99.0000) =     10.093 ms/op
     p(99.9000) =     23.685 ms/op
     p(99.9900) =     29.904 ms/op
     p(99.9990) =     31.865 ms/op
     p(99.9999) =     31.982 ms/op
    p(100.0000) =     31.982 ms/op


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
# Warmup Iteration   1: 18.917 ±(99.9%) 0.331 ms/op
# Warmup Iteration   2: 7.129 ±(99.9%) 0.050 ms/op
# Warmup Iteration   3: 5.291 ±(99.9%) 0.022 ms/op
Iteration   1: 5.347 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   1.702 ms/op
                 getUser·p0.50:   5.005 ms/op
                 getUser·p0.90:   6.865 ms/op
                 getUser·p0.95:   7.873 ms/op
                 getUser·p0.99:   10.502 ms/op
                 getUser·p0.999:  23.151 ms/op
                 getUser·p0.9999: 26.608 ms/op
                 getUser·p1.00:   29.983 ms/op

Iteration   2: 5.284 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   2.363 ms/op
                 getUser·p0.50:   5.005 ms/op
                 getUser·p0.90:   6.357 ms/op
                 getUser·p0.95:   7.602 ms/op
                 getUser·p0.99:   10.011 ms/op
                 getUser·p0.999:  24.510 ms/op
                 getUser·p0.9999: 32.857 ms/op
                 getUser·p1.00:   33.554 ms/op

Iteration   3: 5.273 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   1.925 ms/op
                 getUser·p0.50:   4.997 ms/op
                 getUser·p0.90:   6.275 ms/op
                 getUser·p0.95:   7.356 ms/op
                 getUser·p0.99:   10.502 ms/op
                 getUser·p0.999:  24.880 ms/op
                 getUser·p0.9999: 30.144 ms/op
                 getUser·p1.00:   31.785 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 181013
  mean =      5.301 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20 
    [ 2.500,  5.000) = 90471 
    [ 5.000,  7.500) = 80600 
    [ 7.500, 10.000) = 7834 
    [10.000, 12.500) = 1328 
    [12.500, 15.000) = 479 
    [15.000, 17.500) = 85 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 45 
    [25.000, 27.500) = 80 
    [27.500, 30.000) = 34 
    [30.000, 32.500) = 25 
    [32.500, 35.000) = 8 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.702 ms/op
     p(50.0000) =      5.005 ms/op
     p(90.0000) =      6.513 ms/op
     p(95.0000) =      7.660 ms/op
     p(99.0000) =     10.371 ms/op
     p(99.9000) =     24.052 ms/op
     p(99.9900) =     31.126 ms/op
     p(99.9990) =     33.183 ms/op
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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 19.952 ±(99.9%) 0.299 ms/op
# Warmup Iteration   2: 7.887 ±(99.9%) 0.058 ms/op
# Warmup Iteration   3: 5.976 ±(99.9%) 0.022 ms/op
Iteration   1: 6.035 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   2.867 ms/op
                 listUser·p0.50:   5.677 ms/op
                 listUser·p0.90:   7.217 ms/op
                 listUser·p0.95:   8.634 ms/op
                 listUser·p0.99:   12.108 ms/op
                 listUser·p0.999:  23.985 ms/op
                 listUser·p0.9999: 26.129 ms/op
                 listUser·p1.00:   26.771 ms/op

Iteration   2: 6.150 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   2.318 ms/op
                 listUser·p0.50:   5.833 ms/op
                 listUser·p0.90:   7.406 ms/op
                 listUser·p0.95:   8.516 ms/op
                 listUser·p0.99:   11.076 ms/op
                 listUser·p0.999:  27.916 ms/op
                 listUser·p0.9999: 32.633 ms/op
                 listUser·p1.00:   33.817 ms/op

Iteration   3: 6.013 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   2.322 ms/op
                 listUser·p0.50:   5.669 ms/op
                 listUser·p0.90:   7.176 ms/op
                 listUser·p0.95:   8.536 ms/op
                 listUser·p0.99:   11.731 ms/op
                 listUser·p0.999:  20.991 ms/op
                 listUser·p0.9999: 29.219 ms/op
                 listUser·p1.00:   29.458 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 158315
  mean =      6.066 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8 
    [ 2.500,  5.000) = 13779 
    [ 5.000,  7.500) = 130821 
    [ 7.500, 10.000) = 10003 
    [10.000, 12.500) = 2624 
    [12.500, 15.000) = 635 
    [15.000, 17.500) = 125 
    [17.500, 20.000) = 46 
    [20.000, 22.500) = 54 
    [22.500, 25.000) = 92 
    [25.000, 27.500) = 53 
    [27.500, 30.000) = 51 
    [30.000, 32.500) = 19 
    [32.500, 35.000) = 5 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.318 ms/op
     p(50.0000) =      5.718 ms/op
     p(90.0000) =      7.291 ms/op
     p(95.0000) =      8.552 ms/op
     p(99.0000) =     11.698 ms/op
     p(99.9000) =     24.281 ms/op
     p(99.9900) =     30.453 ms/op
     p(99.9990) =     33.377 ms/op
     p(99.9999) =     33.817 ms/op
    p(100.0000) =     33.817 ms/op


# Run complete. Total time: 00:13:18

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.954 ± 4.720  ops/ms
ClientPb.existUser                       thrpt       3   6.474 ± 2.164  ops/ms
ClientPb.getUser                         thrpt       3   6.009 ± 4.008  ops/ms
ClientPb.listUser                        thrpt       3   5.336 ± 0.782  ops/ms
ClientPb.createUser                       avgt       3   5.197 ± 0.802   ms/op
ClientPb.existUser                        avgt       3   5.116 ± 1.663   ms/op
ClientPb.getUser                          avgt       3   5.241 ± 2.623   ms/op
ClientPb.listUser                         avgt       3   5.990 ± 3.455   ms/op
ClientPb.createUser                     sample  183479   5.225 ± 0.011   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.073           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.948           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.324           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.217           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.371           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.479           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.267           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.900           ms/op
ClientPb.existUser                      sample  188800   5.083 ± 0.010   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.837           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.792           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.136           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.045           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.093           ms/op
ClientPb.existUser:existUser·p0.999     sample          23.685           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.904           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.982           ms/op
ClientPb.getUser                        sample  181013   5.301 ± 0.011   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.702           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.005           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.513           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.660           ms/op
ClientPb.getUser:getUser·p0.99          sample          10.371           ms/op
ClientPb.getUser:getUser·p0.999         sample          24.052           ms/op
ClientPb.getUser:getUser·p0.9999        sample          31.126           ms/op
ClientPb.getUser:getUser·p1.00          sample          33.554           ms/op
ClientPb.listUser                       sample  158315   6.066 ± 0.012   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.318           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.718           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.291           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.552           ms/op
ClientPb.listUser:listUser·p0.99        sample          11.698           ms/op
ClientPb.listUser:listUser·p0.999       sample          24.281           ms/op
ClientPb.listUser:listUser·p0.9999      sample          30.453           ms/op
ClientPb.listUser:listUser·p1.00        sample          33.817           ms/op
