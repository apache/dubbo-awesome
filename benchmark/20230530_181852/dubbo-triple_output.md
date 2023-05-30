# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.097 ops/ms
# Warmup Iteration   2: 5.719 ops/ms
# Warmup Iteration   3: 8.442 ops/ms
Iteration   1: 9.428 ops/ms
Iteration   2: 9.348 ops/ms
Iteration   3: 9.454 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.410 ±(99.9%) 1.008 ops/ms [Average]
  (min, avg, max) = (9.348, 9.410, 9.454), stdev = 0.055
  CI (99.9%): [8.402, 10.418] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.030 ops/ms
# Warmup Iteration   2: 8.929 ops/ms
# Warmup Iteration   3: 9.468 ops/ms
Iteration   1: 9.858 ops/ms
Iteration   2: 10.046 ops/ms
Iteration   3: 9.753 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.886 ±(99.9%) 2.709 ops/ms [Average]
  (min, avg, max) = (9.753, 9.886, 10.046), stdev = 0.149
  CI (99.9%): [7.176, 12.595] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.192 ops/ms
# Warmup Iteration   2: 8.657 ops/ms
# Warmup Iteration   3: 8.871 ops/ms
Iteration   1: 9.543 ops/ms
Iteration   2: 9.569 ops/ms
Iteration   3: 9.036 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.383 ±(99.9%) 5.481 ops/ms [Average]
  (min, avg, max) = (9.036, 9.383, 9.569), stdev = 0.300
  CI (99.9%): [3.901, 14.864] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 2.954 ops/ms
# Warmup Iteration   2: 7.308 ops/ms
# Warmup Iteration   3: 7.783 ops/ms
Iteration   1: 8.116 ops/ms
Iteration   2: 8.148 ops/ms
Iteration   3: 7.762 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.009 ±(99.9%) 3.902 ops/ms [Average]
  (min, avg, max) = (7.762, 8.009, 8.148), stdev = 0.214
  CI (99.9%): [4.107, 11.910] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 9.640 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.664 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.630 ±(99.9%) 0.005 ms/op
Iteration   1: 3.497 ±(99.9%) 0.004 ms/op
Iteration   2: 3.288 ±(99.9%) 0.013 ms/op
Iteration   3: 3.329 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.371 ±(99.9%) 2.014 ms/op [Average]
  (min, avg, max) = (3.288, 3.371, 3.497), stdev = 0.110
  CI (99.9%): [1.357, 5.385] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 9.798 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.615 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.379 ±(99.9%) 0.008 ms/op
Iteration   1: 3.315 ±(99.9%) 0.005 ms/op
Iteration   2: 3.173 ±(99.9%) 0.006 ms/op
Iteration   3: 3.207 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.232 ±(99.9%) 1.355 ms/op [Average]
  (min, avg, max) = (3.173, 3.232, 3.315), stdev = 0.074
  CI (99.9%): [1.877, 4.586] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 8.697 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.648 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.563 ±(99.9%) 0.006 ms/op
Iteration   1: 3.394 ±(99.9%) 0.006 ms/op
Iteration   2: 3.315 ±(99.9%) 0.008 ms/op
Iteration   3: 3.548 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.419 ±(99.9%) 2.158 ms/op [Average]
  (min, avg, max) = (3.315, 3.419, 3.548), stdev = 0.118
  CI (99.9%): [1.261, 5.577] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 11.426 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 4.361 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.067 ±(99.9%) 0.012 ms/op
Iteration   1: 3.937 ±(99.9%) 0.015 ms/op
Iteration   2: 3.973 ±(99.9%) 0.011 ms/op
Iteration   3: 3.909 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.940 ±(99.9%) 0.585 ms/op [Average]
  (min, avg, max) = (3.909, 3.940, 3.973), stdev = 0.032
  CI (99.9%): [3.355, 4.525] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 9.158 ±(99.9%) 0.126 ms/op
# Warmup Iteration   2: 3.823 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.509 ±(99.9%) 0.011 ms/op
Iteration   1: 3.563 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.217 ms/op
                 createUser·p0.50:   3.363 ms/op
                 createUser·p0.90:   4.342 ms/op
                 createUser·p0.95:   4.874 ms/op
                 createUser·p0.99:   6.259 ms/op
                 createUser·p0.999:  19.898 ms/op
                 createUser·p0.9999: 23.004 ms/op
                 createUser·p1.00:   25.395 ms/op

Iteration   2: 3.330 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.473 ms/op
                 createUser·p0.50:   3.330 ms/op
                 createUser·p0.90:   3.506 ms/op
                 createUser·p0.95:   3.891 ms/op
                 createUser·p0.99:   4.833 ms/op
                 createUser·p0.999:  20.417 ms/op
                 createUser·p0.9999: 24.949 ms/op
                 createUser·p1.00:   26.149 ms/op

Iteration   3: 3.379 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.751 ms/op
                 createUser·p0.50:   3.346 ms/op
                 createUser·p0.90:   3.662 ms/op
                 createUser·p0.95:   4.121 ms/op
                 createUser·p0.99:   5.575 ms/op
                 createUser·p0.999:  16.187 ms/op
                 createUser·p0.9999: 29.017 ms/op
                 createUser·p1.00:   29.524 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 280605
  mean =      3.421 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19056 
    [ 2.500,  5.000) = 255059 
    [ 5.000,  7.500) = 5338 
    [ 7.500, 10.000) = 678 
    [10.000, 12.500) = 125 
    [12.500, 15.000) = 61 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 81 
    [22.500, 25.000) = 93 
    [25.000, 27.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      1.217 ms/op
     p(50.0000) =      3.342 ms/op
     p(90.0000) =      3.957 ms/op
     p(95.0000) =      4.325 ms/op
     p(99.0000) =      5.775 ms/op
     p(99.9000) =     16.400 ms/op
     p(99.9900) =     27.712 ms/op
     p(99.9990) =     29.340 ms/op
     p(99.9999) =     29.524 ms/op
    p(100.0000) =     29.524 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 8.612 ±(99.9%) 0.106 ms/op
# Warmup Iteration   2: 3.526 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.377 ±(99.9%) 0.011 ms/op
Iteration   1: 3.462 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.253 ms/op
                 existUser·p0.50:   3.207 ms/op
                 existUser·p0.90:   4.612 ms/op
                 existUser·p0.95:   4.874 ms/op
                 existUser·p0.99:   6.197 ms/op
                 existUser·p0.999:  20.326 ms/op
                 existUser·p0.9999: 27.674 ms/op
                 existUser·p1.00:   28.180 ms/op

Iteration   2: 3.237 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.874 ms/op
                 existUser·p0.50:   3.256 ms/op
                 existUser·p0.90:   3.375 ms/op
                 existUser·p0.95:   3.510 ms/op
                 existUser·p0.99:   5.341 ms/op
                 existUser·p0.999:  11.567 ms/op
                 existUser·p0.9999: 25.723 ms/op
                 existUser·p1.00:   27.099 ms/op

Iteration   3: 3.330 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.724 ms/op
                 existUser·p0.50:   3.232 ms/op
                 existUser·p0.90:   3.949 ms/op
                 existUser·p0.95:   4.506 ms/op
                 existUser·p0.99:   5.988 ms/op
                 existUser·p0.999:  17.179 ms/op
                 existUser·p0.9999: 26.555 ms/op
                 existUser·p1.00:   26.837 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 287161
  mean =      3.340 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21772 
    [ 2.500,  5.000) = 257617 
    [ 5.000,  7.500) = 6847 
    [ 7.500, 10.000) = 528 
    [10.000, 12.500) = 86 
    [12.500, 15.000) = 21 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 85 
    [22.500, 25.000) = 88 
    [25.000, 27.500) = 85 

  Percentiles, ms/op:
      p(0.0000) =      0.874 ms/op
     p(50.0000) =      3.240 ms/op
     p(90.0000) =      3.813 ms/op
     p(95.0000) =      4.612 ms/op
     p(99.0000) =      5.956 ms/op
     p(99.9000) =     17.335 ms/op
     p(99.9900) =     26.608 ms/op
     p(99.9990) =     28.029 ms/op
     p(99.9999) =     28.180 ms/op
    p(100.0000) =     28.180 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 10.350 ±(99.9%) 0.142 ms/op
# Warmup Iteration   2: 3.870 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.608 ±(99.9%) 0.012 ms/op
Iteration   1: 3.475 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.403 ms/op
                 getUser·p0.50:   3.285 ms/op
                 getUser·p0.90:   3.916 ms/op
                 getUser·p0.95:   4.841 ms/op
                 getUser·p0.99:   6.939 ms/op
                 getUser·p0.999:  19.068 ms/op
                 getUser·p0.9999: 23.881 ms/op
                 getUser·p1.00:   27.132 ms/op

Iteration   2: 3.435 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.159 ms/op
                 getUser·p0.50:   3.232 ms/op
                 getUser·p0.90:   3.895 ms/op
                 getUser·p0.95:   4.981 ms/op
                 getUser·p0.99:   6.275 ms/op
                 getUser·p0.999:  17.560 ms/op
                 getUser·p0.9999: 23.556 ms/op
                 getUser·p1.00:   24.347 ms/op

Iteration   3: 3.374 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.182 ms/op
                 getUser·p0.50:   3.252 ms/op
                 getUser·p0.90:   3.707 ms/op
                 getUser·p0.95:   3.936 ms/op
                 getUser·p0.99:   6.130 ms/op
                 getUser·p0.999:  21.323 ms/op
                 getUser·p0.9999: 24.707 ms/op
                 getUser·p1.00:   25.821 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 279799
  mean =      3.428 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5050 
    [ 2.500,  5.000) = 263882 
    [ 5.000,  7.500) = 9778 
    [ 7.500, 10.000) = 661 
    [10.000, 12.500) = 46 
    [12.500, 15.000) = 19 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 148 
    [20.000, 22.500) = 49 
    [22.500, 25.000) = 134 
    [25.000, 27.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      1.159 ms/op
     p(50.0000) =      3.256 ms/op
     p(90.0000) =      3.834 ms/op
     p(95.0000) =      4.407 ms/op
     p(99.0000) =      6.414 ms/op
     p(99.9000) =     18.586 ms/op
     p(99.9900) =     24.216 ms/op
     p(99.9990) =     25.560 ms/op
     p(99.9999) =     27.132 ms/op
    p(100.0000) =     27.132 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 11.247 ±(99.9%) 0.155 ms/op
# Warmup Iteration   2: 4.603 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.263 ±(99.9%) 0.014 ms/op
Iteration   1: 4.033 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.204 ms/op
                 listUser·p0.50:   3.924 ms/op
                 listUser·p0.90:   4.293 ms/op
                 listUser·p0.95:   4.547 ms/op
                 listUser·p0.99:   7.168 ms/op
                 listUser·p0.999:  21.236 ms/op
                 listUser·p0.9999: 24.714 ms/op
                 listUser·p1.00:   25.330 ms/op

Iteration   2: 3.922 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.968 ms/op
                 listUser·p0.50:   3.891 ms/op
                 listUser·p0.90:   4.035 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   6.865 ms/op
                 listUser·p0.999:  15.651 ms/op
                 listUser·p0.9999: 21.496 ms/op
                 listUser·p1.00:   21.561 ms/op

Iteration   3: 3.969 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.224 ms/op
                 listUser·p0.50:   3.850 ms/op
                 listUser·p0.90:   4.375 ms/op
                 listUser·p0.95:   4.588 ms/op
                 listUser·p0.99:   6.906 ms/op
                 listUser·p0.999:  15.441 ms/op
                 listUser·p0.9999: 17.857 ms/op
                 listUser·p1.00:   19.169 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 241641
  mean =      3.974 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 32 
    [ 2.500,  5.000) = 235387 
    [ 5.000,  7.500) = 4384 
    [ 7.500, 10.000) = 1057 
    [10.000, 12.500) = 220 
    [12.500, 15.000) = 150 
    [15.000, 17.500) = 197 
    [17.500, 20.000) = 75 
    [20.000, 22.500) = 91 
    [22.500, 25.000) = 43 
    [25.000, 27.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      1.968 ms/op
     p(50.0000) =      3.891 ms/op
     p(90.0000) =      4.268 ms/op
     p(95.0000) =      4.530 ms/op
     p(99.0000) =      6.939 ms/op
     p(99.9000) =     16.920 ms/op
     p(99.9900) =     23.484 ms/op
     p(99.9990) =     25.185 ms/op
     p(99.9999) =     25.330 ms/op
    p(100.0000) =     25.330 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.410 ± 1.008  ops/ms
ClientPb.existUser                       thrpt       3   9.886 ± 2.709  ops/ms
ClientPb.getUser                         thrpt       3   9.383 ± 5.481  ops/ms
ClientPb.listUser                        thrpt       3   8.009 ± 3.902  ops/ms
ClientPb.createUser                       avgt       3   3.371 ± 2.014   ms/op
ClientPb.existUser                        avgt       3   3.232 ± 1.355   ms/op
ClientPb.getUser                          avgt       3   3.419 ± 2.158   ms/op
ClientPb.listUser                         avgt       3   3.940 ± 0.585   ms/op
ClientPb.createUser                     sample  280605   3.421 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.217           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.342           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.957           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.325           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.775           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.400           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.712           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.524           ms/op
ClientPb.existUser                      sample  287161   3.340 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.874           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.240           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.813           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.612           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.956           ms/op
ClientPb.existUser:existUser·p0.999     sample          17.335           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.608           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.180           ms/op
ClientPb.getUser                        sample  279799   3.428 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.159           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.256           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.834           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.407           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.414           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.586           ms/op
ClientPb.getUser:getUser·p0.9999        sample          24.216           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.132           ms/op
ClientPb.listUser                       sample  241641   3.974 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.968           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.891           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.268           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.530           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.939           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.920           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.484           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.330           ms/op
