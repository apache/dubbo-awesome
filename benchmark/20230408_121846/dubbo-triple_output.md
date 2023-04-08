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
# Warmup Iteration   1: 2.128 ops/ms
# Warmup Iteration   2: 6.058 ops/ms
# Warmup Iteration   3: 8.055 ops/ms
Iteration   1: 8.850 ops/ms
Iteration   2: 9.225 ops/ms
Iteration   3: 9.281 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.119 ±(99.9%) 4.281 ops/ms [Average]
  (min, avg, max) = (8.850, 9.119, 9.281), stdev = 0.235
  CI (99.9%): [4.837, 13.400] (assumes normal distribution)


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
# Warmup Iteration   1: 3.012 ops/ms
# Warmup Iteration   2: 8.744 ops/ms
# Warmup Iteration   3: 9.476 ops/ms
Iteration   1: 9.733 ops/ms
Iteration   2: 9.864 ops/ms
Iteration   3: 9.317 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.638 ±(99.9%) 5.214 ops/ms [Average]
  (min, avg, max) = (9.317, 9.638, 9.864), stdev = 0.286
  CI (99.9%): [4.424, 14.853] (assumes normal distribution)


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
# Warmup Iteration   1: 2.902 ops/ms
# Warmup Iteration   2: 8.414 ops/ms
# Warmup Iteration   3: 9.147 ops/ms
Iteration   1: 8.918 ops/ms
Iteration   2: 9.437 ops/ms
Iteration   3: 8.676 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.010 ±(99.9%) 7.091 ops/ms [Average]
  (min, avg, max) = (8.676, 9.010, 9.437), stdev = 0.389
  CI (99.9%): [1.919, 16.101] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 2.980 ops/ms
# Warmup Iteration   2: 7.277 ops/ms
# Warmup Iteration   3: 7.747 ops/ms
Iteration   1: 8.259 ops/ms
Iteration   2: 7.676 ops/ms
Iteration   3: 8.214 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.050 ±(99.9%) 5.914 ops/ms [Average]
  (min, avg, max) = (7.676, 8.050, 8.259), stdev = 0.324
  CI (99.9%): [2.135, 13.964] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 11.136 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.913 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.439 ±(99.9%) 0.012 ms/op
Iteration   1: 3.501 ±(99.9%) 0.004 ms/op
Iteration   2: 3.446 ±(99.9%) 0.012 ms/op
Iteration   3: 3.346 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.431 ±(99.9%) 1.437 ms/op [Average]
  (min, avg, max) = (3.346, 3.431, 3.501), stdev = 0.079
  CI (99.9%): [1.994, 4.868] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 8.403 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.595 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.424 ±(99.9%) 0.007 ms/op
Iteration   1: 3.389 ±(99.9%) 0.003 ms/op
Iteration   2: 3.310 ±(99.9%) 0.002 ms/op
Iteration   3: 3.253 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.317 ±(99.9%) 1.251 ms/op [Average]
  (min, avg, max) = (3.253, 3.317, 3.389), stdev = 0.069
  CI (99.9%): [2.066, 4.569] (assumes normal distribution)


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
# Warmup Iteration   1: 9.666 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.667 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.432 ±(99.9%) 0.004 ms/op
Iteration   1: 3.587 ±(99.9%) 0.004 ms/op
Iteration   2: 3.398 ±(99.9%) 0.003 ms/op
Iteration   3: 3.467 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.484 ±(99.9%) 1.746 ms/op [Average]
  (min, avg, max) = (3.398, 3.484, 3.587), stdev = 0.096
  CI (99.9%): [1.738, 5.230] (assumes normal distribution)


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
# Warmup Iteration   1: 9.509 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.479 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.938 ±(99.9%) 0.014 ms/op
Iteration   1: 3.921 ±(99.9%) 0.011 ms/op
Iteration   2: 4.095 ±(99.9%) 0.006 ms/op
Iteration   3: 3.922 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.979 ±(99.9%) 1.828 ms/op [Average]
  (min, avg, max) = (3.921, 3.979, 4.095), stdev = 0.100
  CI (99.9%): [2.152, 5.807] (assumes normal distribution)


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
# Warmup Iteration   1: 10.217 ±(99.9%) 0.124 ms/op
# Warmup Iteration   2: 3.980 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.428 ±(99.9%) 0.010 ms/op
Iteration   1: 3.630 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.395 ms/op
                 createUser·p0.50:   3.420 ms/op
                 createUser·p0.90:   4.162 ms/op
                 createUser·p0.95:   5.784 ms/op
                 createUser·p0.99:   7.242 ms/op
                 createUser·p0.999:  20.611 ms/op
                 createUser·p0.9999: 25.015 ms/op
                 createUser·p1.00:   26.083 ms/op

Iteration   2: 3.495 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.104 ms/op
                 createUser·p0.50:   3.355 ms/op
                 createUser·p0.90:   3.928 ms/op
                 createUser·p0.95:   4.325 ms/op
                 createUser·p0.99:   7.021 ms/op
                 createUser·p0.999:  22.312 ms/op
                 createUser·p0.9999: 26.182 ms/op
                 createUser·p1.00:   27.427 ms/op

Iteration   3: 3.436 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.757 ms/op
                 createUser·p0.50:   3.301 ms/op
                 createUser·p0.90:   3.838 ms/op
                 createUser·p0.95:   4.055 ms/op
                 createUser·p0.99:   5.644 ms/op
                 createUser·p0.999:  20.573 ms/op
                 createUser·p0.9999: 27.318 ms/op
                 createUser·p1.00:   27.460 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 272786
  mean =      3.519 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6058 
    [ 2.500,  5.000) = 255560 
    [ 5.000,  7.500) = 9636 
    [ 7.500, 10.000) = 1012 
    [10.000, 12.500) = 126 
    [12.500, 15.000) = 70 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 76 
    [22.500, 25.000) = 141 
    [25.000, 27.500) = 74 

  Percentiles, ms/op:
      p(0.0000) =      1.104 ms/op
     p(50.0000) =      3.371 ms/op
     p(90.0000) =      3.924 ms/op
     p(95.0000) =      4.448 ms/op
     p(99.0000) =      7.062 ms/op
     p(99.9000) =     20.651 ms/op
     p(99.9900) =     25.976 ms/op
     p(99.9990) =     27.427 ms/op
     p(99.9999) =     27.460 ms/op
    p(100.0000) =     27.460 ms/op


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
# Warmup Iteration   1: 7.846 ±(99.9%) 0.111 ms/op
# Warmup Iteration   2: 3.646 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.338 ±(99.9%) 0.008 ms/op
Iteration   1: 3.303 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.161 ms/op
                 existUser·p0.50:   3.252 ms/op
                 existUser·p0.90:   3.715 ms/op
                 existUser·p0.95:   4.022 ms/op
                 existUser·p0.99:   5.505 ms/op
                 existUser·p0.999:  8.520 ms/op
                 existUser·p0.9999: 26.608 ms/op
                 existUser·p1.00:   27.263 ms/op

Iteration   2: 3.323 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.337 ms/op
                 existUser·p0.50:   3.285 ms/op
                 existUser·p0.90:   3.564 ms/op
                 existUser·p0.95:   4.010 ms/op
                 existUser·p0.99:   5.947 ms/op
                 existUser·p0.999:  18.468 ms/op
                 existUser·p0.9999: 27.406 ms/op
                 existUser·p1.00:   27.722 ms/op

Iteration   3: 3.323 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.200 ms/op
                 existUser·p0.50:   3.310 ms/op
                 existUser·p0.90:   3.510 ms/op
                 existUser·p0.95:   3.973 ms/op
                 existUser·p0.99:   5.355 ms/op
                 existUser·p0.999:  21.124 ms/op
                 existUser·p0.9999: 27.669 ms/op
                 existUser·p1.00:   28.312 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 289139
  mean =      3.316 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23347 
    [ 2.500,  5.000) = 260487 
    [ 5.000,  7.500) = 4653 
    [ 7.500, 10.000) = 287 
    [10.000, 12.500) = 65 
    [12.500, 15.000) = 31 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 65 
    [22.500, 25.000) = 100 
    [25.000, 27.500) = 73 

  Percentiles, ms/op:
      p(0.0000) =      1.161 ms/op
     p(50.0000) =      3.285 ms/op
     p(90.0000) =      3.592 ms/op
     p(95.0000) =      4.006 ms/op
     p(99.0000) =      5.767 ms/op
     p(99.9000) =     12.627 ms/op
     p(99.9900) =     27.099 ms/op
     p(99.9990) =     27.961 ms/op
     p(99.9999) =     28.312 ms/op
    p(100.0000) =     28.312 ms/op


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
# Warmup Iteration   1: 9.120 ±(99.9%) 0.108 ms/op
# Warmup Iteration   2: 3.698 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.526 ±(99.9%) 0.011 ms/op
Iteration   1: 3.396 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.806 ms/op
                 getUser·p0.50:   3.236 ms/op
                 getUser·p0.90:   3.707 ms/op
                 getUser·p0.95:   4.014 ms/op
                 getUser·p0.99:   6.832 ms/op
                 getUser·p0.999:  20.485 ms/op
                 getUser·p0.9999: 22.850 ms/op
                 getUser·p1.00:   23.364 ms/op

Iteration   2: 3.447 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.949 ms/op
                 getUser·p0.50:   3.367 ms/op
                 getUser·p0.90:   3.838 ms/op
                 getUser·p0.95:   4.129 ms/op
                 getUser·p0.99:   5.857 ms/op
                 getUser·p0.999:  23.050 ms/op
                 getUser·p0.9999: 28.237 ms/op
                 getUser·p1.00:   29.295 ms/op

Iteration   3: 3.478 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.926 ms/op
                 getUser·p0.50:   3.396 ms/op
                 getUser·p0.90:   3.940 ms/op
                 getUser·p0.95:   4.301 ms/op
                 getUser·p0.99:   5.857 ms/op
                 getUser·p0.999:  18.320 ms/op
                 getUser·p0.9999: 24.715 ms/op
                 getUser·p1.00:   25.068 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 278884
  mean =      3.440 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8017 
    [ 2.500,  5.000) = 263460 
    [ 5.000,  7.500) = 6407 
    [ 7.500, 10.000) = 473 
    [10.000, 12.500) = 116 
    [12.500, 15.000) = 90 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 98 
    [22.500, 25.000) = 114 
    [25.000, 27.500) = 27 

  Percentiles, ms/op:
      p(0.0000) =      0.926 ms/op
     p(50.0000) =      3.338 ms/op
     p(90.0000) =      3.846 ms/op
     p(95.0000) =      4.178 ms/op
     p(99.0000) =      6.349 ms/op
     p(99.9000) =     18.922 ms/op
     p(99.9900) =     27.631 ms/op
     p(99.9990) =     28.824 ms/op
     p(99.9999) =     29.295 ms/op
    p(100.0000) =     29.295 ms/op


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
# Warmup Iteration   1: 11.480 ±(99.9%) 0.168 ms/op
# Warmup Iteration   2: 4.420 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.279 ±(99.9%) 0.016 ms/op
Iteration   1: 4.041 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.064 ms/op
                 listUser·p0.50:   3.854 ms/op
                 listUser·p0.90:   4.456 ms/op
                 listUser·p0.95:   4.782 ms/op
                 listUser·p0.99:   7.053 ms/op
                 listUser·p0.999:  21.496 ms/op
                 listUser·p0.9999: 32.541 ms/op
                 listUser·p1.00:   33.227 ms/op

Iteration   2: 3.938 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.466 ms/op
                 listUser·p0.50:   3.854 ms/op
                 listUser·p0.90:   4.252 ms/op
                 listUser·p0.95:   4.555 ms/op
                 listUser·p0.99:   6.570 ms/op
                 listUser·p0.999:  15.679 ms/op
                 listUser·p0.9999: 16.843 ms/op
                 listUser·p1.00:   17.170 ms/op

Iteration   3: 4.074 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.449 ms/op
                 listUser·p0.50:   3.932 ms/op
                 listUser·p0.90:   4.415 ms/op
                 listUser·p0.95:   4.735 ms/op
                 listUser·p0.99:   7.766 ms/op
                 listUser·p0.999:  14.074 ms/op
                 listUser·p0.9999: 16.843 ms/op
                 listUser·p1.00:   17.629 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 239151
  mean =      4.017 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24 
    [ 2.500,  5.000) = 230825 
    [ 5.000,  7.500) = 6058 
    [ 7.500, 10.000) = 1393 
    [10.000, 12.500) = 334 
    [12.500, 15.000) = 171 
    [15.000, 17.500) = 221 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 21 
    [30.000, 32.500) = 33 
    [32.500, 35.000) = 10 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.064 ms/op
     p(50.0000) =      3.875 ms/op
     p(90.0000) =      4.391 ms/op
     p(95.0000) =      4.686 ms/op
     p(99.0000) =      7.291 ms/op
     p(99.9000) =     15.956 ms/op
     p(99.9900) =     32.115 ms/op
     p(99.9990) =     33.039 ms/op
     p(99.9999) =     33.227 ms/op
    p(100.0000) =     33.227 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.119 ± 4.281  ops/ms
ClientPb.existUser                       thrpt       3   9.638 ± 5.214  ops/ms
ClientPb.getUser                         thrpt       3   9.010 ± 7.091  ops/ms
ClientPb.listUser                        thrpt       3   8.050 ± 5.914  ops/ms
ClientPb.createUser                       avgt       3   3.431 ± 1.437   ms/op
ClientPb.existUser                        avgt       3   3.317 ± 1.251   ms/op
ClientPb.getUser                          avgt       3   3.484 ± 1.746   ms/op
ClientPb.listUser                         avgt       3   3.979 ± 1.828   ms/op
ClientPb.createUser                     sample  272786   3.519 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.104           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.371           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.924           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.448           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.062           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.651           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.976           ms/op
ClientPb.createUser:createUser·p1.00    sample          27.460           ms/op
ClientPb.existUser                      sample  289139   3.316 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.161           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.285           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.592           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.006           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.767           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.627           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.099           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.312           ms/op
ClientPb.getUser                        sample  278884   3.440 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.926           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.338           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.846           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.178           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.349           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.922           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.631           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.295           ms/op
ClientPb.listUser                       sample  239151   4.017 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.064           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.875           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.391           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.686           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.291           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.956           ms/op
ClientPb.listUser:listUser·p0.9999      sample          32.115           ms/op
ClientPb.listUser:listUser·p1.00        sample          33.227           ms/op
