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
# Warmup Iteration   1: 2.253 ops/ms
# Warmup Iteration   2: 6.347 ops/ms
# Warmup Iteration   3: 8.625 ops/ms
Iteration   1: 9.052 ops/ms
Iteration   2: 9.279 ops/ms
Iteration   3: 9.282 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.204 ±(99.9%) 2.401 ops/ms [Average]
  (min, avg, max) = (9.052, 9.204, 9.282), stdev = 0.132
  CI (99.9%): [6.803, 11.605] (assumes normal distribution)


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
# Warmup Iteration   1: 3.221 ops/ms
# Warmup Iteration   2: 8.985 ops/ms
# Warmup Iteration   3: 9.747 ops/ms
Iteration   1: 9.877 ops/ms
Iteration   2: 10.078 ops/ms
Iteration   3: 9.957 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.971 ±(99.9%) 1.851 ops/ms [Average]
  (min, avg, max) = (9.877, 9.971, 10.078), stdev = 0.101
  CI (99.9%): [8.119, 11.822] (assumes normal distribution)


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
# Warmup Iteration   1: 3.308 ops/ms
# Warmup Iteration   2: 8.562 ops/ms
# Warmup Iteration   3: 9.258 ops/ms
Iteration   1: 9.327 ops/ms
Iteration   2: 9.387 ops/ms
Iteration   3: 9.126 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.280 ±(99.9%) 2.490 ops/ms [Average]
  (min, avg, max) = (9.126, 9.280, 9.387), stdev = 0.136
  CI (99.9%): [6.790, 11.770] (assumes normal distribution)


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
# Warmup Iteration   1: 2.804 ops/ms
# Warmup Iteration   2: 7.166 ops/ms
# Warmup Iteration   3: 7.757 ops/ms
Iteration   1: 8.170 ops/ms
Iteration   2: 7.963 ops/ms
Iteration   3: 8.007 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.047 ±(99.9%) 1.997 ops/ms [Average]
  (min, avg, max) = (7.963, 8.047, 8.170), stdev = 0.109
  CI (99.9%): [6.050, 10.043] (assumes normal distribution)


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
# Warmup Iteration   1: 9.936 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.928 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.513 ±(99.9%) 0.004 ms/op
Iteration   1: 3.442 ±(99.9%) 0.011 ms/op
Iteration   2: 3.360 ±(99.9%) 0.010 ms/op
Iteration   3: 3.295 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.366 ±(99.9%) 1.345 ms/op [Average]
  (min, avg, max) = (3.295, 3.366, 3.442), stdev = 0.074
  CI (99.9%): [2.021, 4.710] (assumes normal distribution)


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
# Warmup Iteration   1: 8.064 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.468 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.408 ±(99.9%) 0.003 ms/op
Iteration   1: 3.204 ±(99.9%) 0.007 ms/op
Iteration   2: 3.147 ±(99.9%) 0.008 ms/op
Iteration   3: 3.354 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.235 ±(99.9%) 1.943 ms/op [Average]
  (min, avg, max) = (3.147, 3.235, 3.354), stdev = 0.107
  CI (99.9%): [1.292, 5.179] (assumes normal distribution)


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
# Warmup Iteration   1: 8.752 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.777 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.644 ±(99.9%) 0.004 ms/op
Iteration   1: 3.608 ±(99.9%) 0.004 ms/op
Iteration   2: 3.395 ±(99.9%) 0.006 ms/op
Iteration   3: 3.469 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.491 ±(99.9%) 1.975 ms/op [Average]
  (min, avg, max) = (3.395, 3.491, 3.608), stdev = 0.108
  CI (99.9%): [1.516, 5.466] (assumes normal distribution)


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
# Warmup Iteration   1: 12.111 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 4.582 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.044 ±(99.9%) 0.010 ms/op
Iteration   1: 4.059 ±(99.9%) 0.009 ms/op
Iteration   2: 3.993 ±(99.9%) 0.009 ms/op
Iteration   3: 3.904 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.985 ±(99.9%) 1.419 ms/op [Average]
  (min, avg, max) = (3.904, 3.985, 4.059), stdev = 0.078
  CI (99.9%): [2.567, 5.404] (assumes normal distribution)


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
# Warmup Iteration   1: 8.660 ±(99.9%) 0.112 ms/op
# Warmup Iteration   2: 3.837 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.472 ±(99.9%) 0.010 ms/op
Iteration   1: 3.400 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.421 ms/op
                 createUser·p0.50:   3.273 ms/op
                 createUser·p0.90:   3.863 ms/op
                 createUser·p0.95:   4.190 ms/op
                 createUser·p0.99:   5.661 ms/op
                 createUser·p0.999:  20.968 ms/op
                 createUser·p0.9999: 26.653 ms/op
                 createUser·p1.00:   28.475 ms/op

Iteration   2: 3.391 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.327 ms/op
                 createUser·p0.50:   3.269 ms/op
                 createUser·p0.90:   3.842 ms/op
                 createUser·p0.95:   4.076 ms/op
                 createUser·p0.99:   5.153 ms/op
                 createUser·p0.999:  22.894 ms/op
                 createUser·p0.9999: 27.169 ms/op
                 createUser·p1.00:   27.591 ms/op

Iteration   3: 3.383 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.309 ms/op
                 createUser·p0.50:   3.277 ms/op
                 createUser·p0.90:   3.789 ms/op
                 createUser·p0.95:   4.067 ms/op
                 createUser·p0.99:   5.784 ms/op
                 createUser·p0.999:  17.584 ms/op
                 createUser·p0.9999: 23.822 ms/op
                 createUser·p1.00:   24.838 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 282956
  mean =      3.391 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5530 
    [ 2.500,  5.000) = 272463 
    [ 5.000,  7.500) = 4110 
    [ 7.500, 10.000) = 427 
    [10.000, 12.500) = 84 
    [12.500, 15.000) = 24 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 34 
    [20.000, 22.500) = 84 
    [22.500, 25.000) = 99 
    [25.000, 27.500) = 63 

  Percentiles, ms/op:
      p(0.0000) =      1.309 ms/op
     p(50.0000) =      3.273 ms/op
     p(90.0000) =      3.830 ms/op
     p(95.0000) =      4.100 ms/op
     p(99.0000) =      5.636 ms/op
     p(99.9000) =     17.695 ms/op
     p(99.9900) =     26.467 ms/op
     p(99.9990) =     28.045 ms/op
     p(99.9999) =     28.475 ms/op
    p(100.0000) =     28.475 ms/op


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
# Warmup Iteration   1: 7.860 ±(99.9%) 0.098 ms/op
# Warmup Iteration   2: 3.490 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.230 ±(99.9%) 0.007 ms/op
Iteration   1: 3.210 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.286 ms/op
                 existUser·p0.50:   3.133 ms/op
                 existUser·p0.90:   3.412 ms/op
                 existUser·p0.95:   3.629 ms/op
                 existUser·p0.99:   5.480 ms/op
                 existUser·p0.999:  8.047 ms/op
                 existUser·p0.9999: 29.525 ms/op
                 existUser·p1.00:   30.179 ms/op

Iteration   2: 3.331 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.417 ms/op
                 existUser·p0.50:   3.232 ms/op
                 existUser·p0.90:   3.641 ms/op
                 existUser·p0.95:   4.325 ms/op
                 existUser·p0.99:   5.923 ms/op
                 existUser·p0.999:  12.234 ms/op
                 existUser·p0.9999: 21.103 ms/op
                 existUser·p1.00:   22.708 ms/op

Iteration   3: 3.290 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.167 ms/op
                 existUser·p0.50:   3.158 ms/op
                 existUser·p0.90:   3.576 ms/op
                 existUser·p0.95:   3.834 ms/op
                 existUser·p0.99:   5.743 ms/op
                 existUser·p0.999:  17.981 ms/op
                 existUser·p0.9999: 27.739 ms/op
                 existUser·p1.00:   29.164 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 293244
  mean =      3.276 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7369 
    [ 2.500,  5.000) = 281194 
    [ 5.000,  7.500) = 3689 
    [ 7.500, 10.000) = 449 
    [10.000, 12.500) = 216 
    [12.500, 15.000) = 70 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 60 
    [20.000, 22.500) = 48 
    [22.500, 25.000) = 58 
    [25.000, 27.500) = 47 
    [27.500, 30.000) = 41 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.167 ms/op
     p(50.0000) =      3.174 ms/op
     p(90.0000) =      3.543 ms/op
     p(95.0000) =      3.863 ms/op
     p(99.0000) =      5.652 ms/op
     p(99.9000) =     13.496 ms/op
     p(99.9900) =     28.389 ms/op
     p(99.9990) =     30.053 ms/op
     p(99.9999) =     30.179 ms/op
    p(100.0000) =     30.179 ms/op


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
# Warmup Iteration   1: 10.803 ±(99.9%) 0.120 ms/op
# Warmup Iteration   2: 3.835 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.583 ±(99.9%) 0.009 ms/op
Iteration   1: 3.507 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.589 ms/op
                 getUser·p0.50:   3.355 ms/op
                 getUser·p0.90:   3.863 ms/op
                 getUser·p0.95:   4.415 ms/op
                 getUser·p0.99:   6.726 ms/op
                 getUser·p0.999:  19.687 ms/op
                 getUser·p0.9999: 21.787 ms/op
                 getUser·p1.00:   23.003 ms/op

Iteration   2: 3.408 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.456 ms/op
                 getUser·p0.50:   3.355 ms/op
                 getUser·p0.90:   3.842 ms/op
                 getUser·p0.95:   4.096 ms/op
                 getUser·p0.99:   5.161 ms/op
                 getUser·p0.999:  22.388 ms/op
                 getUser·p0.9999: 27.644 ms/op
                 getUser·p1.00:   28.213 ms/op

Iteration   3: 3.467 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.006 ms/op
                 getUser·p0.50:   3.326 ms/op
                 getUser·p0.90:   3.772 ms/op
                 getUser·p0.95:   4.022 ms/op
                 getUser·p0.99:   6.267 ms/op
                 getUser·p0.999:  18.907 ms/op
                 getUser·p0.9999: 26.444 ms/op
                 getUser·p1.00:   31.261 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 277307
  mean =      3.460 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4741 
    [ 2.500,  5.000) = 265355 
    [ 5.000,  7.500) = 5994 
    [ 7.500, 10.000) = 680 
    [10.000, 12.500) = 136 
    [12.500, 15.000) = 88 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 89 
    [22.500, 25.000) = 97 
    [25.000, 27.500) = 51 
    [27.500, 30.000) = 10 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.006 ms/op
     p(50.0000) =      3.346 ms/op
     p(90.0000) =      3.822 ms/op
     p(95.0000) =      4.133 ms/op
     p(99.0000) =      6.210 ms/op
     p(99.9000) =     19.431 ms/op
     p(99.9900) =     26.518 ms/op
     p(99.9990) =     28.087 ms/op
     p(99.9999) =     31.261 ms/op
    p(100.0000) =     31.261 ms/op


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
# Warmup Iteration   1: 11.374 ±(99.9%) 0.153 ms/op
# Warmup Iteration   2: 4.447 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.137 ±(99.9%) 0.014 ms/op
Iteration   1: 3.977 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.221 ms/op
                 listUser·p0.50:   3.875 ms/op
                 listUser·p0.90:   4.243 ms/op
                 listUser·p0.95:   4.497 ms/op
                 listUser·p0.99:   7.111 ms/op
                 listUser·p0.999:  20.369 ms/op
                 listUser·p0.9999: 23.592 ms/op
                 listUser·p1.00:   24.216 ms/op

Iteration   2: 4.007 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.404 ms/op
                 listUser·p0.50:   3.879 ms/op
                 listUser·p0.90:   4.366 ms/op
                 listUser·p0.95:   4.579 ms/op
                 listUser·p0.99:   6.971 ms/op
                 listUser·p0.999:  15.958 ms/op
                 listUser·p0.9999: 17.990 ms/op
                 listUser·p1.00:   18.219 ms/op

Iteration   3: 3.975 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.318 ms/op
                 listUser·p0.50:   3.830 ms/op
                 listUser·p0.90:   4.383 ms/op
                 listUser·p0.95:   4.596 ms/op
                 listUser·p0.99:   6.914 ms/op
                 listUser·p0.999:  15.078 ms/op
                 listUser·p0.9999: 17.465 ms/op
                 listUser·p1.00:   20.775 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 240540
  mean =      3.986 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 37 
    [ 2.500,  5.000) = 234037 
    [ 5.000,  7.500) = 4585 
    [ 7.500, 10.000) = 1060 
    [10.000, 12.500) = 273 
    [12.500, 15.000) = 153 
    [15.000, 17.500) = 246 
    [17.500, 20.000) = 59 
    [20.000, 22.500) = 72 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.221 ms/op
     p(50.0000) =      3.863 ms/op
     p(90.0000) =      4.334 ms/op
     p(95.0000) =      4.563 ms/op
     p(99.0000) =      7.009 ms/op
     p(99.9000) =     16.555 ms/op
     p(99.9900) =     22.348 ms/op
     p(99.9990) =     24.123 ms/op
     p(99.9999) =     24.216 ms/op
    p(100.0000) =     24.216 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.204 ± 2.401  ops/ms
ClientPb.existUser                       thrpt       3   9.971 ± 1.851  ops/ms
ClientPb.getUser                         thrpt       3   9.280 ± 2.490  ops/ms
ClientPb.listUser                        thrpt       3   8.047 ± 1.997  ops/ms
ClientPb.createUser                       avgt       3   3.366 ± 1.345   ms/op
ClientPb.existUser                        avgt       3   3.235 ± 1.943   ms/op
ClientPb.getUser                          avgt       3   3.491 ± 1.975   ms/op
ClientPb.listUser                         avgt       3   3.985 ± 1.419   ms/op
ClientPb.createUser                     sample  282956   3.391 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.309           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.273           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.830           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.100           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.636           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.695           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.467           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.475           ms/op
ClientPb.existUser                      sample  293244   3.276 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.167           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.174           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.543           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.863           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.652           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.496           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.389           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.179           ms/op
ClientPb.getUser                        sample  277307   3.460 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.006           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.346           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.822           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.133           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.210           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.431           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.518           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.261           ms/op
ClientPb.listUser                       sample  240540   3.986 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.221           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.863           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.334           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.563           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.009           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.555           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.348           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.216           ms/op
