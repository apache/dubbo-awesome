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
# Warmup Iteration   1: 2.572 ops/ms
# Warmup Iteration   2: 6.492 ops/ms
# Warmup Iteration   3: 8.878 ops/ms
Iteration   1: 9.956 ops/ms
Iteration   2: 9.847 ops/ms
Iteration   3: 9.937 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.913 ±(99.9%) 1.059 ops/ms [Average]
  (min, avg, max) = (9.847, 9.913, 9.956), stdev = 0.058
  CI (99.9%): [8.854, 10.973] (assumes normal distribution)


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
# Warmup Iteration   1: 3.788 ops/ms
# Warmup Iteration   2: 9.156 ops/ms
# Warmup Iteration   3: 9.671 ops/ms
Iteration   1: 9.964 ops/ms
Iteration   2: 9.951 ops/ms
Iteration   3: 10.251 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.055 ±(99.9%) 3.094 ops/ms [Average]
  (min, avg, max) = (9.951, 10.055, 10.251), stdev = 0.170
  CI (99.9%): [6.961, 13.149] (assumes normal distribution)


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
# Warmup Iteration   1: 3.561 ops/ms
# Warmup Iteration   2: 9.181 ops/ms
# Warmup Iteration   3: 9.920 ops/ms
Iteration   1: 9.917 ops/ms
Iteration   2: 10.117 ops/ms
Iteration   3: 9.972 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.002 ±(99.9%) 1.886 ops/ms [Average]
  (min, avg, max) = (9.917, 10.002, 10.117), stdev = 0.103
  CI (99.9%): [8.117, 11.888] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.473 ops/ms
# Warmup Iteration   2: 7.973 ops/ms
# Warmup Iteration   3: 8.467 ops/ms
Iteration   1: 8.673 ops/ms
Iteration   2: 8.518 ops/ms
Iteration   3: 8.445 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.545 ±(99.9%) 2.119 ops/ms [Average]
  (min, avg, max) = (8.445, 8.545, 8.673), stdev = 0.116
  CI (99.9%): [6.426, 10.664] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 8.318 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.469 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.223 ±(99.9%) 0.004 ms/op
Iteration   1: 3.131 ±(99.9%) 0.008 ms/op
Iteration   2: 3.161 ±(99.9%) 0.005 ms/op
Iteration   3: 3.091 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.128 ±(99.9%) 0.641 ms/op [Average]
  (min, avg, max) = (3.091, 3.128, 3.161), stdev = 0.035
  CI (99.9%): [2.487, 3.769] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 6.987 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.406 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.259 ±(99.9%) 0.007 ms/op
Iteration   1: 3.246 ±(99.9%) 0.006 ms/op
Iteration   2: 3.008 ±(99.9%) 0.005 ms/op
Iteration   3: 3.046 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.100 ±(99.9%) 2.333 ms/op [Average]
  (min, avg, max) = (3.008, 3.100, 3.246), stdev = 0.128
  CI (99.9%): [0.767, 5.433] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 7.613 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.486 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.429 ±(99.9%) 0.004 ms/op
Iteration   1: 3.136 ±(99.9%) 0.006 ms/op
Iteration   2: 3.307 ±(99.9%) 0.006 ms/op
Iteration   3: 3.279 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.241 ±(99.9%) 1.673 ms/op [Average]
  (min, avg, max) = (3.136, 3.241, 3.307), stdev = 0.092
  CI (99.9%): [1.568, 4.913] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 9.722 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 4.417 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.823 ±(99.9%) 0.006 ms/op
Iteration   1: 3.720 ±(99.9%) 0.009 ms/op
Iteration   2: 3.725 ±(99.9%) 0.008 ms/op
Iteration   3: 3.757 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.734 ±(99.9%) 0.371 ms/op [Average]
  (min, avg, max) = (3.720, 3.734, 3.757), stdev = 0.020
  CI (99.9%): [3.363, 4.105] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 7.765 ±(99.9%) 0.093 ms/op
# Warmup Iteration   2: 3.933 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.204 ±(99.9%) 0.008 ms/op
Iteration   1: 3.194 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.057 ms/op
                 createUser·p0.50:   3.146 ms/op
                 createUser·p0.90:   3.551 ms/op
                 createUser·p0.95:   3.834 ms/op
                 createUser·p0.99:   5.587 ms/op
                 createUser·p0.999:  13.222 ms/op
                 createUser·p0.9999: 20.251 ms/op
                 createUser·p1.00:   21.332 ms/op

Iteration   2: 3.149 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.208 ms/op
                 createUser·p0.50:   3.088 ms/op
                 createUser·p0.90:   3.449 ms/op
                 createUser·p0.95:   3.781 ms/op
                 createUser·p0.99:   5.505 ms/op
                 createUser·p0.999:  20.414 ms/op
                 createUser·p0.9999: 21.889 ms/op
                 createUser·p1.00:   22.348 ms/op

Iteration   3: 3.251 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.634 ms/op
                 createUser·p0.50:   3.195 ms/op
                 createUser·p0.90:   3.719 ms/op
                 createUser·p0.95:   3.977 ms/op
                 createUser·p0.99:   5.685 ms/op
                 createUser·p0.999:  14.304 ms/op
                 createUser·p0.9999: 19.830 ms/op
                 createUser·p1.00:   20.709 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 299997
  mean =      3.197 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21610 
    [ 2.500,  5.000) = 273121 
    [ 5.000,  7.500) = 4451 
    [ 7.500, 10.000) = 330 
    [10.000, 12.500) = 128 
    [12.500, 15.000) = 36 
    [15.000, 17.500) = 48 
    [17.500, 20.000) = 135 
    [20.000, 22.500) = 138 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.057 ms/op
     p(50.0000) =      3.154 ms/op
     p(90.0000) =      3.584 ms/op
     p(95.0000) =      3.883 ms/op
     p(99.0000) =      5.562 ms/op
     p(99.9000) =     16.876 ms/op
     p(99.9900) =     21.463 ms/op
     p(99.9990) =     22.282 ms/op
     p(99.9999) =     22.348 ms/op
    p(100.0000) =     22.348 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.883 ±(99.9%) 0.089 ms/op
# Warmup Iteration   2: 3.327 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.129 ±(99.9%) 0.008 ms/op
Iteration   1: 3.045 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.124 ms/op
                 existUser·p0.50:   2.957 ms/op
                 existUser·p0.90:   3.345 ms/op
                 existUser·p0.95:   3.486 ms/op
                 existUser·p0.99:   4.309 ms/op
                 existUser·p0.999:  9.011 ms/op
                 existUser·p0.9999: 20.120 ms/op
                 existUser·p1.00:   21.201 ms/op

Iteration   2: 3.145 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.452 ms/op
                 existUser·p0.50:   3.109 ms/op
                 existUser·p0.90:   3.314 ms/op
                 existUser·p0.95:   3.949 ms/op
                 existUser·p0.99:   5.494 ms/op
                 existUser·p0.999:  13.623 ms/op
                 existUser·p0.9999: 22.965 ms/op
                 existUser·p1.00:   23.396 ms/op

Iteration   3: 3.111 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.174 ms/op
                 existUser·p0.50:   3.080 ms/op
                 existUser·p0.90:   3.310 ms/op
                 existUser·p0.95:   3.985 ms/op
                 existUser·p0.99:   5.633 ms/op
                 existUser·p0.999:  8.487 ms/op
                 existUser·p0.9999: 21.323 ms/op
                 existUser·p1.00:   21.823 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 309273
  mean =      3.100 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20397 
    [ 2.500,  5.000) = 284129 
    [ 5.000,  7.500) = 4056 
    [ 7.500, 10.000) = 353 
    [10.000, 12.500) = 27 
    [12.500, 15.000) = 33 
    [15.000, 17.500) = 53 
    [17.500, 20.000) = 86 
    [20.000, 22.500) = 121 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.124 ms/op
     p(50.0000) =      3.072 ms/op
     p(90.0000) =      3.330 ms/op
     p(95.0000) =      3.699 ms/op
     p(99.0000) =      5.358 ms/op
     p(99.9000) =     13.302 ms/op
     p(99.9900) =     22.090 ms/op
     p(99.9990) =     23.191 ms/op
     p(99.9999) =     23.396 ms/op
    p(100.0000) =     23.396 ms/op


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
# Warmup Iteration   1: 7.537 ±(99.9%) 0.085 ms/op
# Warmup Iteration   2: 3.406 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.290 ±(99.9%) 0.010 ms/op
Iteration   1: 3.156 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.440 ms/op
                 getUser·p0.50:   3.043 ms/op
                 getUser·p0.90:   3.502 ms/op
                 getUser·p0.95:   4.174 ms/op
                 getUser·p0.99:   5.636 ms/op
                 getUser·p0.999:  17.783 ms/op
                 getUser·p0.9999: 22.868 ms/op
                 getUser·p1.00:   23.888 ms/op

Iteration   2: 3.200 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.023 ms/op
                 getUser·p0.50:   3.113 ms/op
                 getUser·p0.90:   3.600 ms/op
                 getUser·p0.95:   4.194 ms/op
                 getUser·p0.99:   5.603 ms/op
                 getUser·p0.999:  13.697 ms/op
                 getUser·p0.9999: 22.447 ms/op
                 getUser·p1.00:   23.790 ms/op

Iteration   3: 3.114 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.186 ms/op
                 getUser·p0.50:   3.006 ms/op
                 getUser·p0.90:   3.428 ms/op
                 getUser·p0.95:   3.740 ms/op
                 getUser·p0.99:   5.284 ms/op
                 getUser·p0.999:  11.076 ms/op
                 getUser·p0.9999: 24.943 ms/op
                 getUser·p1.00:   25.821 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 303922
  mean =      3.156 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16121 
    [ 2.500,  5.000) = 281637 
    [ 5.000,  7.500) = 5250 
    [ 7.500, 10.000) = 460 
    [10.000, 12.500) = 106 
    [12.500, 15.000) = 22 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 95 
    [20.000, 22.500) = 148 
    [22.500, 25.000) = 47 
    [25.000, 27.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      1.023 ms/op
     p(50.0000) =      3.047 ms/op
     p(90.0000) =      3.510 ms/op
     p(95.0000) =      3.973 ms/op
     p(99.0000) =      5.521 ms/op
     p(99.9000) =     17.433 ms/op
     p(99.9900) =     23.593 ms/op
     p(99.9990) =     25.459 ms/op
     p(99.9999) =     25.821 ms/op
    p(100.0000) =     25.821 ms/op


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
# Warmup Iteration   1: 8.928 ±(99.9%) 0.124 ms/op
# Warmup Iteration   2: 4.063 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.878 ±(99.9%) 0.012 ms/op
Iteration   1: 3.778 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.931 ms/op
                 listUser·p0.50:   3.690 ms/op
                 listUser·p0.90:   3.920 ms/op
                 listUser·p0.95:   4.432 ms/op
                 listUser·p0.99:   7.070 ms/op
                 listUser·p0.999:  16.204 ms/op
                 listUser·p0.9999: 20.840 ms/op
                 listUser·p1.00:   22.315 ms/op

Iteration   2: 3.759 ±(99.9%) 0.007 ms/op
                 listUser·p0.00:   0.798 ms/op
                 listUser·p0.50:   3.727 ms/op
                 listUser·p0.90:   4.080 ms/op
                 listUser·p0.95:   4.284 ms/op
                 listUser·p0.99:   6.111 ms/op
                 listUser·p0.999:  13.254 ms/op
                 listUser·p0.9999: 14.664 ms/op
                 listUser·p1.00:   14.942 ms/op

Iteration   3: 3.783 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.808 ms/op
                 listUser·p0.50:   3.736 ms/op
                 listUser·p0.90:   4.063 ms/op
                 listUser·p0.95:   4.350 ms/op
                 listUser·p0.99:   6.398 ms/op
                 listUser·p0.999:  12.911 ms/op
                 listUser·p0.9999: 16.220 ms/op
                 listUser·p1.00:   16.777 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 254375
  mean =      3.773 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 99 
    [ 2.500,  5.000) = 247406 
    [ 5.000,  7.500) = 5299 
    [ 7.500, 10.000) = 924 
    [10.000, 12.500) = 182 
    [12.500, 15.000) = 326 
    [15.000, 17.500) = 71 
    [17.500, 20.000) = 50 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.798 ms/op
     p(50.0000) =      3.719 ms/op
     p(90.0000) =      4.030 ms/op
     p(95.0000) =      4.334 ms/op
     p(99.0000) =      6.611 ms/op
     p(99.9000) =     13.910 ms/op
     p(99.9900) =     19.810 ms/op
     p(99.9990) =     21.429 ms/op
     p(99.9999) =     22.315 ms/op
    p(100.0000) =     22.315 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.913 ± 1.059  ops/ms
ClientPb.existUser                       thrpt       3  10.055 ± 3.094  ops/ms
ClientPb.getUser                         thrpt       3  10.002 ± 1.886  ops/ms
ClientPb.listUser                        thrpt       3   8.545 ± 2.119  ops/ms
ClientPb.createUser                       avgt       3   3.128 ± 0.641   ms/op
ClientPb.existUser                        avgt       3   3.100 ± 2.333   ms/op
ClientPb.getUser                          avgt       3   3.241 ± 1.673   ms/op
ClientPb.listUser                         avgt       3   3.734 ± 0.371   ms/op
ClientPb.createUser                     sample  299997   3.197 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.057           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.154           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.584           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.883           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.562           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.876           ms/op
ClientPb.createUser:createUser·p0.9999  sample          21.463           ms/op
ClientPb.createUser:createUser·p1.00    sample          22.348           ms/op
ClientPb.existUser                      sample  309273   3.100 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.124           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.072           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.330           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.699           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.358           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.302           ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.090           ms/op
ClientPb.existUser:existUser·p1.00      sample          23.396           ms/op
ClientPb.getUser                        sample  303922   3.156 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.023           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.047           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.510           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.973           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.521           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.433           ms/op
ClientPb.getUser:getUser·p0.9999        sample          23.593           ms/op
ClientPb.getUser:getUser·p1.00          sample          25.821           ms/op
ClientPb.listUser                       sample  254375   3.773 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.798           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.719           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.030           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.334           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.611           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.910           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.810           ms/op
ClientPb.listUser:listUser·p1.00        sample          22.315           ms/op
