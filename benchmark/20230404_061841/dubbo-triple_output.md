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
# Warmup Iteration   1: 1.069 ops/ms
# Warmup Iteration   2: 2.524 ops/ms
# Warmup Iteration   3: 5.380 ops/ms
Iteration   1: 5.905 ops/ms
Iteration   2: 6.097 ops/ms
Iteration   3: 6.172 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.058 ±(99.9%) 2.514 ops/ms [Average]
  (min, avg, max) = (5.905, 6.058, 6.172), stdev = 0.138
  CI (99.9%): [3.544, 8.572] (assumes normal distribution)


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
# Warmup Iteration   1: 1.814 ops/ms
# Warmup Iteration   2: 5.435 ops/ms
# Warmup Iteration   3: 6.426 ops/ms
Iteration   1: 6.533 ops/ms
Iteration   2: 6.632 ops/ms
Iteration   3: 6.396 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.520 ±(99.9%) 2.159 ops/ms [Average]
  (min, avg, max) = (6.396, 6.520, 6.632), stdev = 0.118
  CI (99.9%): [4.361, 8.679] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:07
# Fork: 1 of 1
# Warmup Iteration   1: 1.721 ops/ms
# Warmup Iteration   2: 5.083 ops/ms
# Warmup Iteration   3: 6.021 ops/ms
Iteration   1: 6.105 ops/ms
Iteration   2: 6.148 ops/ms
Iteration   3: 6.323 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.192 ±(99.9%) 2.105 ops/ms [Average]
  (min, avg, max) = (6.105, 6.192, 6.323), stdev = 0.115
  CI (99.9%): [4.087, 8.296] (assumes normal distribution)


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
# Warmup Iteration   1: 1.643 ops/ms
# Warmup Iteration   2: 4.741 ops/ms
# Warmup Iteration   3: 5.535 ops/ms
Iteration   1: 5.457 ops/ms
Iteration   2: 5.400 ops/ms
Iteration   3: 5.537 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.465 ±(99.9%) 1.252 ops/ms [Average]
  (min, avg, max) = (5.400, 5.465, 5.537), stdev = 0.069
  CI (99.9%): [4.213, 6.716] (assumes normal distribution)


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
# Warmup Iteration   1: 17.762 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 6.338 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 5.526 ±(99.9%) 0.011 ms/op
Iteration   1: 4.962 ±(99.9%) 0.026 ms/op
Iteration   2: 5.179 ±(99.9%) 0.010 ms/op
Iteration   3: 5.050 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.064 ±(99.9%) 1.988 ms/op [Average]
  (min, avg, max) = (4.962, 5.064, 5.179), stdev = 0.109
  CI (99.9%): [3.076, 7.052] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 15.150 ±(99.9%) 0.091 ms/op
# Warmup Iteration   2: 5.823 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.994 ±(99.9%) 0.007 ms/op
Iteration   1: 4.813 ±(99.9%) 0.009 ms/op
Iteration   2: 4.747 ±(99.9%) 0.009 ms/op
Iteration   3: 4.954 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.838 ±(99.9%) 1.922 ms/op [Average]
  (min, avg, max) = (4.747, 4.838, 4.954), stdev = 0.105
  CI (99.9%): [2.915, 6.760] (assumes normal distribution)


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
# Warmup Iteration   1: 16.448 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 6.389 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 5.235 ±(99.9%) 0.008 ms/op
Iteration   1: 5.273 ±(99.9%) 0.010 ms/op
Iteration   2: 5.085 ±(99.9%) 0.015 ms/op
Iteration   3: 4.965 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.108 ±(99.9%) 2.830 ms/op [Average]
  (min, avg, max) = (4.965, 5.108, 5.273), stdev = 0.155
  CI (99.9%): [2.278, 7.938] (assumes normal distribution)


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
# Warmup Iteration   1: 20.727 ±(99.9%) 0.106 ms/op
# Warmup Iteration   2: 6.898 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 6.018 ±(99.9%) 0.014 ms/op
Iteration   1: 5.864 ±(99.9%) 0.016 ms/op
Iteration   2: 5.773 ±(99.9%) 0.012 ms/op
Iteration   3: 5.718 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.785 ±(99.9%) 1.346 ms/op [Average]
  (min, avg, max) = (5.718, 5.785, 5.864), stdev = 0.074
  CI (99.9%): [4.439, 7.131] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 17.015 ±(99.9%) 0.256 ms/op
# Warmup Iteration   2: 6.597 ±(99.9%) 0.043 ms/op
# Warmup Iteration   3: 5.743 ±(99.9%) 0.025 ms/op
Iteration   1: 5.260 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   1.589 ms/op
                 createUser·p0.50:   5.014 ms/op
                 createUser·p0.90:   6.308 ms/op
                 createUser·p0.95:   7.201 ms/op
                 createUser·p0.99:   10.338 ms/op
                 createUser·p0.999:  21.044 ms/op
                 createUser·p0.9999: 26.680 ms/op
                 createUser·p1.00:   27.492 ms/op

Iteration   2: 5.268 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   1.009 ms/op
                 createUser·p0.50:   4.874 ms/op
                 createUser·p0.90:   6.529 ms/op
                 createUser·p0.95:   7.619 ms/op
                 createUser·p0.99:   11.420 ms/op
                 createUser·p0.999:  22.675 ms/op
                 createUser·p0.9999: 27.744 ms/op
                 createUser·p1.00:   28.803 ms/op

Iteration   3: 5.299 ±(99.9%) 0.022 ms/op
                 createUser·p0.00:   2.146 ms/op
                 createUser·p0.50:   5.030 ms/op
                 createUser·p0.90:   6.308 ms/op
                 createUser·p0.95:   7.160 ms/op
                 createUser·p0.99:   10.813 ms/op
                 createUser·p0.999:  24.969 ms/op
                 createUser·p0.9999: 44.431 ms/op
                 createUser·p1.00:   45.023 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 181932
  mean =      5.276 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 94164 
    [ 5.000, 10.000) = 85326 
    [10.000, 15.000) = 1941 
    [15.000, 20.000) = 212 
    [20.000, 25.000) = 172 
    [25.000, 30.000) = 84 
    [30.000, 35.000) = 1 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 31 

  Percentiles, ms/op:
      p(0.0000) =      1.009 ms/op
     p(50.0000) =      4.973 ms/op
     p(90.0000) =      6.365 ms/op
     p(95.0000) =      7.365 ms/op
     p(99.0000) =     10.895 ms/op
     p(99.9000) =     22.675 ms/op
     p(99.9900) =     43.150 ms/op
     p(99.9990) =     44.916 ms/op
     p(99.9999) =     45.023 ms/op
    p(100.0000) =     45.023 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 15.632 ±(99.9%) 0.238 ms/op
# Warmup Iteration   2: 5.768 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 5.031 ±(99.9%) 0.016 ms/op
Iteration   1: 4.697 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   2.425 ms/op
                 existUser·p0.50:   4.481 ms/op
                 existUser·p0.90:   5.505 ms/op
                 existUser·p0.95:   6.062 ms/op
                 existUser·p0.99:   8.200 ms/op
                 existUser·p0.999:  12.648 ms/op
                 existUser·p0.9999: 26.483 ms/op
                 existUser·p1.00:   26.903 ms/op

Iteration   2: 4.840 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   1.974 ms/op
                 existUser·p0.50:   4.596 ms/op
                 existUser·p0.90:   5.743 ms/op
                 existUser·p0.95:   6.341 ms/op
                 existUser·p0.99:   8.592 ms/op
                 existUser·p0.999:  19.233 ms/op
                 existUser·p0.9999: 31.908 ms/op
                 existUser·p1.00:   32.506 ms/op

Iteration   3: 4.822 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   2.212 ms/op
                 existUser·p0.50:   4.563 ms/op
                 existUser·p0.90:   5.652 ms/op
                 existUser·p0.95:   6.496 ms/op
                 existUser·p0.99:   10.196 ms/op
                 existUser·p0.999:  20.900 ms/op
                 existUser·p0.9999: 27.275 ms/op
                 existUser·p1.00:   31.490 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 200482
  mean =      4.785 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 43 
    [ 2.500,  5.000) = 150844 
    [ 5.000,  7.500) = 45065 
    [ 7.500, 10.000) = 3262 
    [10.000, 12.500) = 706 
    [12.500, 15.000) = 286 
    [15.000, 17.500) = 56 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 62 
    [25.000, 27.500) = 90 
    [27.500, 30.000) = 6 
    [30.000, 32.500) = 28 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.974 ms/op
     p(50.0000) =      4.538 ms/op
     p(90.0000) =      5.636 ms/op
     p(95.0000) =      6.291 ms/op
     p(99.0000) =      8.798 ms/op
     p(99.9000) =     18.965 ms/op
     p(99.9900) =     30.605 ms/op
     p(99.9990) =     32.407 ms/op
     p(99.9999) =     32.506 ms/op
    p(100.0000) =     32.506 ms/op


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
# Warmup Iteration   1: 16.217 ±(99.9%) 0.258 ms/op
# Warmup Iteration   2: 6.220 ±(99.9%) 0.040 ms/op
# Warmup Iteration   3: 5.311 ±(99.9%) 0.020 ms/op
Iteration   1: 5.230 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   2.908 ms/op
                 getUser·p0.50:   4.915 ms/op
                 getUser·p0.90:   6.316 ms/op
                 getUser·p0.95:   7.733 ms/op
                 getUser·p0.99:   10.764 ms/op
                 getUser·p0.999:  23.757 ms/op
                 getUser·p0.9999: 27.489 ms/op
                 getUser·p1.00:   27.787 ms/op

Iteration   2: 5.360 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   1.747 ms/op
                 getUser·p0.50:   5.063 ms/op
                 getUser·p0.90:   6.480 ms/op
                 getUser·p0.95:   7.553 ms/op
                 getUser·p0.99:   10.362 ms/op
                 getUser·p0.999:  27.506 ms/op
                 getUser·p0.9999: 31.721 ms/op
                 getUser·p1.00:   32.080 ms/op

Iteration   3: 5.224 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   2.421 ms/op
                 getUser·p0.50:   4.874 ms/op
                 getUser·p0.90:   6.463 ms/op
                 getUser·p0.95:   7.684 ms/op
                 getUser·p0.99:   10.650 ms/op
                 getUser·p0.999:  25.783 ms/op
                 getUser·p0.9999: 30.208 ms/op
                 getUser·p1.00:   31.916 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 181960
  mean =      5.270 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25 
    [ 2.500,  5.000) = 96042 
    [ 5.000,  7.500) = 76054 
    [ 7.500, 10.000) = 7432 
    [10.000, 12.500) = 1557 
    [12.500, 15.000) = 481 
    [15.000, 17.500) = 51 
    [17.500, 20.000) = 59 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 48 
    [25.000, 27.500) = 95 
    [27.500, 30.000) = 59 
    [30.000, 32.500) = 40 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.747 ms/op
     p(50.0000) =      4.948 ms/op
     p(90.0000) =      6.423 ms/op
     p(95.0000) =      7.651 ms/op
     p(99.0000) =     10.617 ms/op
     p(99.9000) =     25.659 ms/op
     p(99.9900) =     31.451 ms/op
     p(99.9990) =     32.080 ms/op
     p(99.9999) =     32.080 ms/op
    p(100.0000) =     32.080 ms/op


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
# Warmup Iteration   1: 19.580 ±(99.9%) 0.301 ms/op
# Warmup Iteration   2: 7.604 ±(99.9%) 0.047 ms/op
# Warmup Iteration   3: 6.055 ±(99.9%) 0.024 ms/op
Iteration   1: 6.047 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   2.290 ms/op
                 listUser·p0.50:   5.759 ms/op
                 listUser·p0.90:   6.980 ms/op
                 listUser·p0.95:   8.045 ms/op
                 listUser·p0.99:   11.960 ms/op
                 listUser·p0.999:  27.594 ms/op
                 listUser·p0.9999: 38.254 ms/op
                 listUser·p1.00:   39.649 ms/op

Iteration   2: 5.978 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   2.017 ms/op
                 listUser·p0.50:   5.603 ms/op
                 listUser·p0.90:   6.963 ms/op
                 listUser·p0.95:   8.503 ms/op
                 listUser·p0.99:   12.288 ms/op
                 listUser·p0.999:  25.428 ms/op
                 listUser·p0.9999: 30.189 ms/op
                 listUser·p1.00:   32.145 ms/op

Iteration   3: 5.988 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   2.388 ms/op
                 listUser·p0.50:   5.677 ms/op
                 listUser·p0.90:   7.086 ms/op
                 listUser·p0.95:   8.061 ms/op
                 listUser·p0.99:   11.518 ms/op
                 listUser·p0.999:  22.398 ms/op
                 listUser·p0.9999: 25.865 ms/op
                 listUser·p1.00:   26.116 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 159713
  mean =      6.004 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11 
    [ 2.500,  5.000) = 13448 
    [ 5.000,  7.500) = 135143 
    [ 7.500, 10.000) = 7594 
    [10.000, 12.500) = 2242 
    [12.500, 15.000) = 616 
    [15.000, 17.500) = 232 
    [17.500, 20.000) = 102 
    [20.000, 22.500) = 72 
    [22.500, 25.000) = 107 
    [25.000, 27.500) = 67 
    [27.500, 30.000) = 40 
    [30.000, 32.500) = 14 
    [32.500, 35.000) = 5 
    [35.000, 37.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      2.017 ms/op
     p(50.0000) =      5.685 ms/op
     p(90.0000) =      7.012 ms/op
     p(95.0000) =      8.184 ms/op
     p(99.0000) =     11.862 ms/op
     p(99.9000) =     24.749 ms/op
     p(99.9900) =     36.438 ms/op
     p(99.9990) =     39.649 ms/op
     p(99.9999) =     39.649 ms/op
    p(100.0000) =     39.649 ms/op


# Run complete. Total time: 00:13:18

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   6.058 ± 2.514  ops/ms
ClientPb.existUser                       thrpt       3   6.520 ± 2.159  ops/ms
ClientPb.getUser                         thrpt       3   6.192 ± 2.105  ops/ms
ClientPb.listUser                        thrpt       3   5.465 ± 1.252  ops/ms
ClientPb.createUser                       avgt       3   5.064 ± 1.988   ms/op
ClientPb.existUser                        avgt       3   4.838 ± 1.922   ms/op
ClientPb.getUser                          avgt       3   5.108 ± 2.830   ms/op
ClientPb.listUser                         avgt       3   5.785 ± 1.346   ms/op
ClientPb.createUser                     sample  181932   5.276 ± 0.012   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.009           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.973           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.365           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.365           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.895           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.675           ms/op
ClientPb.createUser:createUser·p0.9999  sample          43.150           ms/op
ClientPb.createUser:createUser·p1.00    sample          45.023           ms/op
ClientPb.existUser                      sample  200482   4.785 ± 0.009   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.974           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.538           ms/op
ClientPb.existUser:existUser·p0.90      sample           5.636           ms/op
ClientPb.existUser:existUser·p0.95      sample           6.291           ms/op
ClientPb.existUser:existUser·p0.99      sample           8.798           ms/op
ClientPb.existUser:existUser·p0.999     sample          18.965           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.605           ms/op
ClientPb.existUser:existUser·p1.00      sample          32.506           ms/op
ClientPb.getUser                        sample  181960   5.270 ± 0.011   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.747           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.948           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.423           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.651           ms/op
ClientPb.getUser:getUser·p0.99          sample          10.617           ms/op
ClientPb.getUser:getUser·p0.999         sample          25.659           ms/op
ClientPb.getUser:getUser·p0.9999        sample          31.451           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.080           ms/op
ClientPb.listUser                       sample  159713   6.004 ± 0.013   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.017           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.685           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.012           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.184           ms/op
ClientPb.listUser:listUser·p0.99        sample          11.862           ms/op
ClientPb.listUser:listUser·p0.999       sample          24.749           ms/op
ClientPb.listUser:listUser·p0.9999      sample          36.438           ms/op
ClientPb.listUser:listUser·p1.00        sample          39.649           ms/op
