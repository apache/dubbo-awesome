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
# Warmup Iteration   1: 2.694 ops/ms
# Warmup Iteration   2: 6.533 ops/ms
# Warmup Iteration   3: 8.992 ops/ms
Iteration   1: 9.851 ops/ms
Iteration   2: 9.944 ops/ms
Iteration   3: 9.974 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.923 ±(99.9%) 1.170 ops/ms [Average]
  (min, avg, max) = (9.851, 9.923, 9.974), stdev = 0.064
  CI (99.9%): [8.753, 11.093] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.824 ops/ms
# Warmup Iteration   2: 9.443 ops/ms
# Warmup Iteration   3: 10.675 ops/ms
Iteration   1: 10.471 ops/ms
Iteration   2: 10.430 ops/ms
Iteration   3: 10.770 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.557 ±(99.9%) 3.390 ops/ms [Average]
  (min, avg, max) = (10.430, 10.557, 10.770), stdev = 0.186
  CI (99.9%): [7.167, 13.946] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.490 ops/ms
# Warmup Iteration   2: 8.985 ops/ms
# Warmup Iteration   3: 9.958 ops/ms
Iteration   1: 10.181 ops/ms
Iteration   2: 10.354 ops/ms
Iteration   3: 9.501 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.012 ±(99.9%) 8.225 ops/ms [Average]
  (min, avg, max) = (9.501, 10.012, 10.354), stdev = 0.451
  CI (99.9%): [1.787, 18.237] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.667 ops/ms
# Warmup Iteration   2: 8.130 ops/ms
# Warmup Iteration   3: 8.336 ops/ms
Iteration   1: 8.314 ops/ms
Iteration   2: 8.518 ops/ms
Iteration   3: 8.637 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.490 ±(99.9%) 2.978 ops/ms [Average]
  (min, avg, max) = (8.314, 8.490, 8.637), stdev = 0.163
  CI (99.9%): [5.511, 11.468] (assumes normal distribution)


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
# Warmup Iteration   1: 8.241 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.526 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.185 ±(99.9%) 0.003 ms/op
Iteration   1: 3.276 ±(99.9%) 0.005 ms/op
Iteration   2: 3.108 ±(99.9%) 0.004 ms/op
Iteration   3: 3.110 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.164 ±(99.9%) 1.757 ms/op [Average]
  (min, avg, max) = (3.108, 3.164, 3.276), stdev = 0.096
  CI (99.9%): [1.407, 4.922] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 8.123 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.378 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.014 ±(99.9%) 0.004 ms/op
Iteration   1: 3.020 ±(99.9%) 0.002 ms/op
Iteration   2: 2.938 ±(99.9%) 0.005 ms/op
Iteration   3: 3.030 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.996 ±(99.9%) 0.916 ms/op [Average]
  (min, avg, max) = (2.938, 2.996, 3.030), stdev = 0.050
  CI (99.9%): [2.080, 3.912] (assumes normal distribution)


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
# Warmup Iteration   1: 7.510 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.440 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.271 ±(99.9%) 0.004 ms/op
Iteration   1: 3.286 ±(99.9%) 0.002 ms/op
Iteration   2: 3.197 ±(99.9%) 0.005 ms/op
Iteration   3: 3.173 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.219 ±(99.9%) 1.081 ms/op [Average]
  (min, avg, max) = (3.173, 3.219, 3.286), stdev = 0.059
  CI (99.9%): [2.138, 4.300] (assumes normal distribution)


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
# Warmup Iteration   1: 8.975 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 4.064 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.633 ±(99.9%) 0.008 ms/op
Iteration   1: 3.797 ±(99.9%) 0.003 ms/op
Iteration   2: 3.595 ±(99.9%) 0.008 ms/op
Iteration   3: 3.607 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.666 ±(99.9%) 2.071 ms/op [Average]
  (min, avg, max) = (3.595, 3.666, 3.797), stdev = 0.113
  CI (99.9%): [1.596, 5.737] (assumes normal distribution)


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
# Warmup Iteration   1: 8.548 ±(99.9%) 0.097 ms/op
# Warmup Iteration   2: 3.736 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.190 ±(99.9%) 0.008 ms/op
Iteration   1: 3.235 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.317 ms/op
                 createUser·p0.50:   3.195 ms/op
                 createUser·p0.90:   3.604 ms/op
                 createUser·p0.95:   4.063 ms/op
                 createUser·p0.99:   5.456 ms/op
                 createUser·p0.999:  11.198 ms/op
                 createUser·p0.9999: 21.504 ms/op
                 createUser·p1.00:   22.118 ms/op

Iteration   2: 3.111 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.309 ms/op
                 createUser·p0.50:   2.990 ms/op
                 createUser·p0.90:   3.437 ms/op
                 createUser·p0.95:   3.637 ms/op
                 createUser·p0.99:   5.456 ms/op
                 createUser·p0.999:  18.153 ms/op
                 createUser·p0.9999: 26.345 ms/op
                 createUser·p1.00:   27.754 ms/op

Iteration   3: 3.192 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.352 ms/op
                 createUser·p0.50:   3.084 ms/op
                 createUser·p0.90:   3.727 ms/op
                 createUser·p0.95:   4.006 ms/op
                 createUser·p0.99:   5.366 ms/op
                 createUser·p0.999:  16.394 ms/op
                 createUser·p0.9999: 21.201 ms/op
                 createUser·p1.00:   22.610 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 301813
  mean =      3.179 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19142 
    [ 2.500,  5.000) = 276759 
    [ 5.000,  7.500) = 4903 
    [ 7.500, 10.000) = 522 
    [10.000, 12.500) = 102 
    [12.500, 15.000) = 6 
    [15.000, 17.500) = 87 
    [17.500, 20.000) = 173 
    [20.000, 22.500) = 86 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 27 

  Percentiles, ms/op:
      p(0.0000) =      1.309 ms/op
     p(50.0000) =      3.109 ms/op
     p(90.0000) =      3.576 ms/op
     p(95.0000) =      3.912 ms/op
     p(99.0000) =      5.407 ms/op
     p(99.9000) =     17.334 ms/op
     p(99.9900) =     25.750 ms/op
     p(99.9990) =     27.622 ms/op
     p(99.9999) =     27.754 ms/op
    p(100.0000) =     27.754 ms/op


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
# Warmup Iteration   1: 7.107 ±(99.9%) 0.080 ms/op
# Warmup Iteration   2: 3.451 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.124 ±(99.9%) 0.007 ms/op
Iteration   1: 3.029 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.434 ms/op
                 existUser·p0.50:   3.015 ms/op
                 existUser·p0.90:   3.187 ms/op
                 existUser·p0.95:   3.410 ms/op
                 existUser·p0.99:   5.210 ms/op
                 existUser·p0.999:  9.672 ms/op
                 existUser·p0.9999: 27.343 ms/op
                 existUser·p1.00:   27.787 ms/op

Iteration   2: 3.063 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.294 ms/op
                 existUser·p0.50:   2.920 ms/op
                 existUser·p0.90:   3.396 ms/op
                 existUser·p0.95:   4.014 ms/op
                 existUser·p0.99:   5.366 ms/op
                 existUser·p0.999:  10.921 ms/op
                 existUser·p0.9999: 21.594 ms/op
                 existUser·p1.00:   22.577 ms/op

Iteration   3: 3.013 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.618 ms/op
                 existUser·p0.50:   2.908 ms/op
                 existUser·p0.90:   3.236 ms/op
                 existUser·p0.95:   3.465 ms/op
                 existUser·p0.99:   5.235 ms/op
                 existUser·p0.999:  12.091 ms/op
                 existUser·p0.9999: 22.832 ms/op
                 existUser·p1.00:   23.462 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 316222
  mean =      3.035 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15886 
    [ 2.500,  5.000) = 295242 
    [ 5.000,  7.500) = 4309 
    [ 7.500, 10.000) = 352 
    [10.000, 12.500) = 145 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 107 
    [20.000, 22.500) = 97 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 26 

  Percentiles, ms/op:
      p(0.0000) =      1.294 ms/op
     p(50.0000) =      2.941 ms/op
     p(90.0000) =      3.273 ms/op
     p(95.0000) =      3.600 ms/op
     p(99.0000) =      5.243 ms/op
     p(99.9000) =     11.502 ms/op
     p(99.9900) =     25.879 ms/op
     p(99.9990) =     27.585 ms/op
     p(99.9999) =     27.787 ms/op
    p(100.0000) =     27.787 ms/op


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
# Warmup Iteration   1: 7.195 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 3.434 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.247 ±(99.9%) 0.011 ms/op
Iteration   1: 3.194 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.192 ms/op
                 getUser·p0.50:   2.994 ms/op
                 getUser·p0.90:   3.621 ms/op
                 getUser·p0.95:   4.563 ms/op
                 getUser·p0.99:   6.201 ms/op
                 getUser·p0.999:  20.573 ms/op
                 getUser·p0.9999: 25.690 ms/op
                 getUser·p1.00:   26.214 ms/op

Iteration   2: 3.084 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.038 ms/op
                 getUser·p0.50:   2.978 ms/op
                 getUser·p0.90:   3.359 ms/op
                 getUser·p0.95:   3.568 ms/op
                 getUser·p0.99:   5.210 ms/op
                 getUser·p0.999:  9.637 ms/op
                 getUser·p0.9999: 21.823 ms/op
                 getUser·p1.00:   22.741 ms/op

Iteration   3: 3.145 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.608 ms/op
                 getUser·p0.50:   3.072 ms/op
                 getUser·p0.90:   3.510 ms/op
                 getUser·p0.95:   3.805 ms/op
                 getUser·p0.99:   5.882 ms/op
                 getUser·p0.999:  9.963 ms/op
                 getUser·p0.9999: 18.377 ms/op
                 getUser·p1.00:   19.857 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 305429
  mean =      3.140 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14656 
    [ 2.500,  5.000) = 282971 
    [ 5.000,  7.500) = 6991 
    [ 7.500, 10.000) = 454 
    [10.000, 12.500) = 24 
    [12.500, 15.000) = 30 
    [15.000, 17.500) = 57 
    [17.500, 20.000) = 72 
    [20.000, 22.500) = 145 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 23 

  Percentiles, ms/op:
      p(0.0000) =      1.038 ms/op
     p(50.0000) =      3.011 ms/op
     p(90.0000) =      3.469 ms/op
     p(95.0000) =      3.920 ms/op
     p(99.0000) =      6.087 ms/op
     p(99.9000) =     14.905 ms/op
     p(99.9900) =     22.446 ms/op
     p(99.9990) =     26.136 ms/op
     p(99.9999) =     26.214 ms/op
    p(100.0000) =     26.214 ms/op


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
# Warmup Iteration   1: 8.500 ±(99.9%) 0.113 ms/op
# Warmup Iteration   2: 4.137 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.730 ±(99.9%) 0.011 ms/op
Iteration   1: 3.687 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.028 ms/op
                 listUser·p0.50:   3.523 ms/op
                 listUser·p0.90:   4.026 ms/op
                 listUser·p0.95:   4.465 ms/op
                 listUser·p0.99:   6.758 ms/op
                 listUser·p0.999:  14.631 ms/op
                 listUser·p0.9999: 21.932 ms/op
                 listUser·p1.00:   22.118 ms/op

Iteration   2: 3.765 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.627 ms/op
                 listUser·p0.50:   3.670 ms/op
                 listUser·p0.90:   4.174 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   6.754 ms/op
                 listUser·p0.999:  12.703 ms/op
                 listUser·p0.9999: 15.450 ms/op
                 listUser·p1.00:   15.581 ms/op

Iteration   3: 3.677 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.261 ms/op
                 listUser·p0.50:   3.637 ms/op
                 listUser·p0.90:   3.908 ms/op
                 listUser·p0.95:   4.276 ms/op
                 listUser·p0.99:   6.455 ms/op
                 listUser·p0.999:  13.238 ms/op
                 listUser·p0.9999: 20.129 ms/op
                 listUser·p1.00:   20.251 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 258771
  mean =      3.709 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 65 
    [ 2.500,  5.000) = 251080 
    [ 5.000,  7.500) = 6059 
    [ 7.500, 10.000) = 949 
    [10.000, 12.500) = 247 
    [12.500, 15.000) = 201 
    [15.000, 17.500) = 36 
    [17.500, 20.000) = 87 
    [20.000, 22.500) = 47 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.627 ms/op
     p(50.0000) =      3.629 ms/op
     p(90.0000) =      4.084 ms/op
     p(95.0000) =      4.358 ms/op
     p(99.0000) =      6.627 ms/op
     p(99.9000) =     13.249 ms/op
     p(99.9900) =     21.037 ms/op
     p(99.9990) =     22.001 ms/op
     p(99.9999) =     22.118 ms/op
    p(100.0000) =     22.118 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.923 ± 1.170  ops/ms
ClientPb.existUser                       thrpt       3  10.557 ± 3.390  ops/ms
ClientPb.getUser                         thrpt       3  10.012 ± 8.225  ops/ms
ClientPb.listUser                        thrpt       3   8.490 ± 2.978  ops/ms
ClientPb.createUser                       avgt       3   3.164 ± 1.757   ms/op
ClientPb.existUser                        avgt       3   2.996 ± 0.916   ms/op
ClientPb.getUser                          avgt       3   3.219 ± 1.081   ms/op
ClientPb.listUser                         avgt       3   3.666 ± 2.071   ms/op
ClientPb.createUser                     sample  301813   3.179 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.309           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.109           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.576           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.912           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.407           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.334           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.750           ms/op
ClientPb.createUser:createUser·p1.00    sample          27.754           ms/op
ClientPb.existUser                      sample  316222   3.035 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.294           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.941           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.273           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.600           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.243           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.502           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.879           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.787           ms/op
ClientPb.getUser                        sample  305429   3.140 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.038           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.011           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.469           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.920           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.087           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.905           ms/op
ClientPb.getUser:getUser·p0.9999        sample          22.446           ms/op
ClientPb.getUser:getUser·p1.00          sample          26.214           ms/op
ClientPb.listUser                       sample  258771   3.709 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.627           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.629           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.084           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.358           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.627           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.249           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.037           ms/op
ClientPb.listUser:listUser·p1.00        sample          22.118           ms/op
