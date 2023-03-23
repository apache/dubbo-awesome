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
# Warmup Iteration   1: 2.195 ops/ms
# Warmup Iteration   2: 5.531 ops/ms
# Warmup Iteration   3: 8.794 ops/ms
Iteration   1: 9.255 ops/ms
Iteration   2: 9.585 ops/ms
Iteration   3: 9.650 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.497 ±(99.9%) 3.861 ops/ms [Average]
  (min, avg, max) = (9.255, 9.497, 9.650), stdev = 0.212
  CI (99.9%): [5.636, 13.357] (assumes normal distribution)


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
# Warmup Iteration   1: 3.167 ops/ms
# Warmup Iteration   2: 9.054 ops/ms
# Warmup Iteration   3: 9.620 ops/ms
Iteration   1: 10.102 ops/ms
Iteration   2: 9.718 ops/ms
Iteration   3: 9.601 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.807 ±(99.9%) 4.781 ops/ms [Average]
  (min, avg, max) = (9.601, 9.807, 10.102), stdev = 0.262
  CI (99.9%): [5.025, 14.588] (assumes normal distribution)


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
# Warmup Iteration   1: 3.184 ops/ms
# Warmup Iteration   2: 8.634 ops/ms
# Warmup Iteration   3: 8.927 ops/ms
Iteration   1: 9.537 ops/ms
Iteration   2: 9.569 ops/ms
Iteration   3: 9.453 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.519 ±(99.9%) 1.091 ops/ms [Average]
  (min, avg, max) = (9.453, 9.519, 9.569), stdev = 0.060
  CI (99.9%): [8.429, 10.610] (assumes normal distribution)


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
# Warmup Iteration   1: 2.834 ops/ms
# Warmup Iteration   2: 7.475 ops/ms
# Warmup Iteration   3: 7.861 ops/ms
Iteration   1: 7.935 ops/ms
Iteration   2: 8.270 ops/ms
Iteration   3: 8.288 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.164 ±(99.9%) 3.634 ops/ms [Average]
  (min, avg, max) = (7.935, 8.164, 8.288), stdev = 0.199
  CI (99.9%): [4.530, 11.798] (assumes normal distribution)


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
# Warmup Iteration   1: 9.904 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.763 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.525 ±(99.9%) 0.005 ms/op
Iteration   1: 3.367 ±(99.9%) 0.011 ms/op
Iteration   2: 3.436 ±(99.9%) 0.005 ms/op
Iteration   3: 3.357 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.386 ±(99.9%) 0.787 ms/op [Average]
  (min, avg, max) = (3.357, 3.386, 3.436), stdev = 0.043
  CI (99.9%): [2.599, 4.173] (assumes normal distribution)


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
# Warmup Iteration   1: 8.771 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.532 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.307 ±(99.9%) 0.004 ms/op
Iteration   1: 3.332 ±(99.9%) 0.004 ms/op
Iteration   2: 3.233 ±(99.9%) 0.009 ms/op
Iteration   3: 3.236 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.267 ±(99.9%) 1.026 ms/op [Average]
  (min, avg, max) = (3.233, 3.267, 3.332), stdev = 0.056
  CI (99.9%): [2.241, 4.293] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 8.791 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.573 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.489 ±(99.9%) 0.010 ms/op
Iteration   1: 3.405 ±(99.9%) 0.009 ms/op
Iteration   2: 3.511 ±(99.9%) 0.009 ms/op
Iteration   3: 3.362 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.426 ±(99.9%) 1.401 ms/op [Average]
  (min, avg, max) = (3.362, 3.426, 3.511), stdev = 0.077
  CI (99.9%): [2.025, 4.827] (assumes normal distribution)


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
# Warmup Iteration   1: 11.358 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 4.297 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.938 ±(99.9%) 0.009 ms/op
Iteration   1: 3.944 ±(99.9%) 0.009 ms/op
Iteration   2: 3.953 ±(99.9%) 0.011 ms/op
Iteration   3: 3.811 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.903 ±(99.9%) 1.449 ms/op [Average]
  (min, avg, max) = (3.811, 3.903, 3.953), stdev = 0.079
  CI (99.9%): [2.454, 5.352] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 9.313 ±(99.9%) 0.109 ms/op
# Warmup Iteration   2: 4.005 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.401 ±(99.9%) 0.010 ms/op
Iteration   1: 3.449 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.386 ms/op
                 createUser·p0.50:   3.322 ms/op
                 createUser·p0.90:   3.916 ms/op
                 createUser·p0.95:   4.182 ms/op
                 createUser·p0.99:   6.160 ms/op
                 createUser·p0.999:  20.479 ms/op
                 createUser·p0.9999: 27.853 ms/op
                 createUser·p1.00:   29.229 ms/op

Iteration   2: 3.472 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.378 ms/op
                 createUser·p0.50:   3.400 ms/op
                 createUser·p0.90:   3.920 ms/op
                 createUser·p0.95:   4.293 ms/op
                 createUser·p0.99:   5.849 ms/op
                 createUser·p0.999:  24.576 ms/op
                 createUser·p0.9999: 30.261 ms/op
                 createUser·p1.00:   30.573 ms/op

Iteration   3: 3.470 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.043 ms/op
                 createUser·p0.50:   3.293 ms/op
                 createUser·p0.90:   3.944 ms/op
                 createUser·p0.95:   4.268 ms/op
                 createUser·p0.99:   6.881 ms/op
                 createUser·p0.999:  17.826 ms/op
                 createUser·p0.9999: 25.308 ms/op
                 createUser·p1.00:   26.214 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 277009
  mean =      3.463 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6912 
    [ 2.500,  5.000) = 262902 
    [ 5.000,  7.500) = 5864 
    [ 7.500, 10.000) = 812 
    [10.000, 12.500) = 134 
    [12.500, 15.000) = 65 
    [15.000, 17.500) = 22 
    [17.500, 20.000) = 58 
    [20.000, 22.500) = 41 
    [22.500, 25.000) = 56 
    [25.000, 27.500) = 67 
    [27.500, 30.000) = 67 
    [30.000, 32.500) = 9 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.043 ms/op
     p(50.0000) =      3.351 ms/op
     p(90.0000) =      3.928 ms/op
     p(95.0000) =      4.243 ms/op
     p(99.0000) =      6.283 ms/op
     p(99.9000) =     17.891 ms/op
     p(99.9900) =     29.196 ms/op
     p(99.9990) =     30.573 ms/op
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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 8.533 ±(99.9%) 0.111 ms/op
# Warmup Iteration   2: 3.672 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.336 ±(99.9%) 0.008 ms/op
Iteration   1: 3.327 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.167 ms/op
                 existUser·p0.50:   3.183 ms/op
                 existUser·p0.90:   3.637 ms/op
                 existUser·p0.95:   4.026 ms/op
                 existUser·p0.99:   6.151 ms/op
                 existUser·p0.999:  11.731 ms/op
                 existUser·p0.9999: 23.740 ms/op
                 existUser·p1.00:   25.002 ms/op

Iteration   2: 3.304 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.977 ms/op
                 existUser·p0.50:   3.211 ms/op
                 existUser·p0.90:   3.635 ms/op
                 existUser·p0.95:   3.936 ms/op
                 existUser·p0.99:   5.684 ms/op
                 existUser·p0.999:  15.189 ms/op
                 existUser·p0.9999: 25.012 ms/op
                 existUser·p1.00:   25.985 ms/op

Iteration   3: 3.300 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.681 ms/op
                 existUser·p0.50:   3.170 ms/op
                 existUser·p0.90:   3.686 ms/op
                 existUser·p0.95:   3.940 ms/op
                 existUser·p0.99:   5.874 ms/op
                 existUser·p0.999:  16.109 ms/op
                 existUser·p0.9999: 25.373 ms/op
                 existUser·p1.00:   26.116 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 289704
  mean =      3.311 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4360 
    [ 2.500,  5.000) = 279577 
    [ 5.000,  7.500) = 4653 
    [ 7.500, 10.000) = 666 
    [10.000, 12.500) = 138 
    [12.500, 15.000) = 51 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 158 
    [25.000, 27.500) = 24 

  Percentiles, ms/op:
      p(0.0000) =      0.977 ms/op
     p(50.0000) =      3.191 ms/op
     p(90.0000) =      3.654 ms/op
     p(95.0000) =      3.953 ms/op
     p(99.0000) =      5.964 ms/op
     p(99.9000) =     12.616 ms/op
     p(99.9900) =     24.904 ms/op
     p(99.9990) =     25.691 ms/op
     p(99.9999) =     26.116 ms/op
    p(100.0000) =     26.116 ms/op


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
# Warmup Iteration   1: 8.378 ±(99.9%) 0.098 ms/op
# Warmup Iteration   2: 3.823 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.540 ±(99.9%) 0.012 ms/op
Iteration   1: 3.345 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.133 ms/op
                 getUser·p0.50:   3.207 ms/op
                 getUser·p0.90:   3.699 ms/op
                 getUser·p0.95:   3.908 ms/op
                 getUser·p0.99:   6.283 ms/op
                 getUser·p0.999:  18.204 ms/op
                 getUser·p0.9999: 21.379 ms/op
                 getUser·p1.00:   21.660 ms/op

Iteration   2: 3.474 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.118 ms/op
                 getUser·p0.50:   3.355 ms/op
                 getUser·p0.90:   3.838 ms/op
                 getUser·p0.95:   4.342 ms/op
                 getUser·p0.99:   6.840 ms/op
                 getUser·p0.999:  19.197 ms/op
                 getUser·p0.9999: 22.151 ms/op
                 getUser·p1.00:   22.774 ms/op

Iteration   3: 3.393 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.268 ms/op
                 getUser·p0.50:   3.277 ms/op
                 getUser·p0.90:   3.707 ms/op
                 getUser·p0.95:   3.916 ms/op
                 getUser·p0.99:   5.865 ms/op
                 getUser·p0.999:  18.867 ms/op
                 getUser·p0.9999: 25.657 ms/op
                 getUser·p1.00:   27.099 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 282005
  mean =      3.403 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3943 
    [ 2.500,  5.000) = 270980 
    [ 5.000,  7.500) = 5823 
    [ 7.500, 10.000) = 746 
    [10.000, 12.500) = 155 
    [12.500, 15.000) = 49 
    [15.000, 17.500) = 16 
    [17.500, 20.000) = 99 
    [20.000, 22.500) = 127 
    [22.500, 25.000) = 38 
    [25.000, 27.500) = 29 

  Percentiles, ms/op:
      p(0.0000) =      1.118 ms/op
     p(50.0000) =      3.285 ms/op
     p(90.0000) =      3.744 ms/op
     p(95.0000) =      4.018 ms/op
     p(99.0000) =      6.373 ms/op
     p(99.9000) =     18.645 ms/op
     p(99.9900) =     25.028 ms/op
     p(99.9990) =     26.076 ms/op
     p(99.9999) =     27.099 ms/op
    p(100.0000) =     27.099 ms/op


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
# Warmup Iteration   1: 11.875 ±(99.9%) 0.167 ms/op
# Warmup Iteration   2: 4.399 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.093 ±(99.9%) 0.013 ms/op
Iteration   1: 4.040 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.972 ms/op
                 listUser·p0.50:   3.908 ms/op
                 listUser·p0.90:   4.391 ms/op
                 listUser·p0.95:   4.768 ms/op
                 listUser·p0.99:   7.091 ms/op
                 listUser·p0.999:  19.984 ms/op
                 listUser·p0.9999: 23.825 ms/op
                 listUser·p1.00:   24.838 ms/op

Iteration   2: 4.012 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.335 ms/op
                 listUser·p0.50:   3.871 ms/op
                 listUser·p0.90:   4.465 ms/op
                 listUser·p0.95:   4.809 ms/op
                 listUser·p0.99:   8.159 ms/op
                 listUser·p0.999:  15.448 ms/op
                 listUser·p0.9999: 18.153 ms/op
                 listUser·p1.00:   24.084 ms/op

Iteration   3: 3.946 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.642 ms/op
                 listUser·p0.50:   3.822 ms/op
                 listUser·p0.90:   4.366 ms/op
                 listUser·p0.95:   4.628 ms/op
                 listUser·p0.99:   6.521 ms/op
                 listUser·p0.999:  15.303 ms/op
                 listUser·p0.9999: 21.423 ms/op
                 listUser·p1.00:   21.889 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 239760
  mean =      3.999 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 55 
    [ 2.500,  5.000) = 230806 
    [ 5.000,  7.500) = 6857 
    [ 7.500, 10.000) = 1177 
    [10.000, 12.500) = 341 
    [12.500, 15.000) = 154 
    [15.000, 17.500) = 184 
    [17.500, 20.000) = 85 
    [20.000, 22.500) = 71 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.972 ms/op
     p(50.0000) =      3.863 ms/op
     p(90.0000) =      4.407 ms/op
     p(95.0000) =      4.727 ms/op
     p(99.0000) =      7.078 ms/op
     p(99.9000) =     16.383 ms/op
     p(99.9900) =     22.807 ms/op
     p(99.9990) =     24.124 ms/op
     p(99.9999) =     24.838 ms/op
    p(100.0000) =     24.838 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.497 ± 3.861  ops/ms
ClientPb.existUser                       thrpt       3   9.807 ± 4.781  ops/ms
ClientPb.getUser                         thrpt       3   9.519 ± 1.091  ops/ms
ClientPb.listUser                        thrpt       3   8.164 ± 3.634  ops/ms
ClientPb.createUser                       avgt       3   3.386 ± 0.787   ms/op
ClientPb.existUser                        avgt       3   3.267 ± 1.026   ms/op
ClientPb.getUser                          avgt       3   3.426 ± 1.401   ms/op
ClientPb.listUser                         avgt       3   3.903 ± 1.449   ms/op
ClientPb.createUser                     sample  277009   3.463 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.043           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.351           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.928           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.243           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.283           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.891           ms/op
ClientPb.createUser:createUser·p0.9999  sample          29.196           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.573           ms/op
ClientPb.existUser                      sample  289704   3.311 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.977           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.191           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.654           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.953           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.964           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.616           ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.904           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.116           ms/op
ClientPb.getUser                        sample  282005   3.403 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.118           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.285           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.744           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.018           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.373           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.645           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.028           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.099           ms/op
ClientPb.listUser                       sample  239760   3.999 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.972           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.863           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.407           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.727           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.078           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.383           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.807           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.838           ms/op
