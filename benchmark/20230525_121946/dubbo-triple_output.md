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
# Warmup Iteration   1: 2.033 ops/ms
# Warmup Iteration   2: 5.724 ops/ms
# Warmup Iteration   3: 8.539 ops/ms
Iteration   1: 8.859 ops/ms
Iteration   2: 9.424 ops/ms
Iteration   3: 9.550 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.278 ±(99.9%) 6.712 ops/ms [Average]
  (min, avg, max) = (8.859, 9.278, 9.550), stdev = 0.368
  CI (99.9%): [2.565, 15.990] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.534 ops/ms
# Warmup Iteration   2: 8.936 ops/ms
# Warmup Iteration   3: 9.625 ops/ms
Iteration   1: 10.032 ops/ms
Iteration   2: 10.021 ops/ms
Iteration   3: 10.026 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.026 ±(99.9%) 0.102 ops/ms [Average]
  (min, avg, max) = (10.021, 10.026, 10.032), stdev = 0.006
  CI (99.9%): [9.924, 10.129] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.857 ops/ms
# Warmup Iteration   2: 8.491 ops/ms
# Warmup Iteration   3: 9.539 ops/ms
Iteration   1: 9.749 ops/ms
Iteration   2: 9.250 ops/ms
Iteration   3: 9.529 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.510 ±(99.9%) 4.564 ops/ms [Average]
  (min, avg, max) = (9.250, 9.510, 9.749), stdev = 0.250
  CI (99.9%): [4.946, 14.073] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 2.714 ops/ms
# Warmup Iteration   2: 7.240 ops/ms
# Warmup Iteration   3: 7.940 ops/ms
Iteration   1: 8.032 ops/ms
Iteration   2: 8.109 ops/ms
Iteration   3: 8.121 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.087 ±(99.9%) 0.883 ops/ms [Average]
  (min, avg, max) = (8.032, 8.087, 8.121), stdev = 0.048
  CI (99.9%): [7.204, 8.970] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 9.721 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.727 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.491 ±(99.9%) 0.003 ms/op
Iteration   1: 3.336 ±(99.9%) 0.010 ms/op
Iteration   2: 3.301 ±(99.9%) 0.009 ms/op
Iteration   3: 3.368 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.335 ±(99.9%) 0.610 ms/op [Average]
  (min, avg, max) = (3.301, 3.335, 3.368), stdev = 0.033
  CI (99.9%): [2.725, 3.945] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 8.546 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.509 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.187 ±(99.9%) 0.006 ms/op
Iteration   1: 3.147 ±(99.9%) 0.008 ms/op
Iteration   2: 3.098 ±(99.9%) 0.004 ms/op
Iteration   3: 3.160 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.135 ±(99.9%) 0.602 ms/op [Average]
  (min, avg, max) = (3.098, 3.135, 3.160), stdev = 0.033
  CI (99.9%): [2.533, 3.737] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 9.043 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.725 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.583 ±(99.9%) 0.006 ms/op
Iteration   1: 3.395 ±(99.9%) 0.007 ms/op
Iteration   2: 3.481 ±(99.9%) 0.007 ms/op
Iteration   3: 3.375 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.417 ±(99.9%) 1.028 ms/op [Average]
  (min, avg, max) = (3.375, 3.417, 3.481), stdev = 0.056
  CI (99.9%): [2.389, 4.445] (assumes normal distribution)


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
# Warmup Iteration   1: 9.258 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 4.135 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.040 ±(99.9%) 0.013 ms/op
Iteration   1: 3.937 ±(99.9%) 0.006 ms/op
Iteration   2: 3.841 ±(99.9%) 0.011 ms/op
Iteration   3: 3.989 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.922 ±(99.9%) 1.372 ms/op [Average]
  (min, avg, max) = (3.841, 3.922, 3.989), stdev = 0.075
  CI (99.9%): [2.550, 5.294] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 8.987 ±(99.9%) 0.119 ms/op
# Warmup Iteration   2: 3.779 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.421 ±(99.9%) 0.009 ms/op
Iteration   1: 3.281 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.178 ms/op
                 createUser·p0.50:   3.183 ms/op
                 createUser·p0.90:   3.641 ms/op
                 createUser·p0.95:   3.887 ms/op
                 createUser·p0.99:   5.349 ms/op
                 createUser·p0.999:  13.824 ms/op
                 createUser·p0.9999: 22.070 ms/op
                 createUser·p1.00:   23.364 ms/op

Iteration   2: 3.314 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.579 ms/op
                 createUser·p0.50:   3.236 ms/op
                 createUser·p0.90:   3.424 ms/op
                 createUser·p0.95:   3.927 ms/op
                 createUser·p0.99:   6.095 ms/op
                 createUser·p0.999:  21.682 ms/op
                 createUser·p0.9999: 24.980 ms/op
                 createUser·p1.00:   25.297 ms/op

Iteration   3: 3.408 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.391 ms/op
                 createUser·p0.50:   3.281 ms/op
                 createUser·p0.90:   3.850 ms/op
                 createUser·p0.95:   4.084 ms/op
                 createUser·p0.99:   5.595 ms/op
                 createUser·p0.999:  18.022 ms/op
                 createUser·p0.9999: 24.353 ms/op
                 createUser·p1.00:   25.788 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 288088
  mean =      3.333 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8497 
    [ 2.500,  5.000) = 274321 
    [ 5.000,  7.500) = 4311 
    [ 7.500, 10.000) = 482 
    [10.000, 12.500) = 111 
    [12.500, 15.000) = 42 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 51 
    [20.000, 22.500) = 158 
    [22.500, 25.000) = 98 
    [25.000, 27.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      0.579 ms/op
     p(50.0000) =      3.224 ms/op
     p(90.0000) =      3.707 ms/op
     p(95.0000) =      3.994 ms/op
     p(99.0000) =      5.628 ms/op
     p(99.9000) =     19.464 ms/op
     p(99.9900) =     24.510 ms/op
     p(99.9990) =     25.320 ms/op
     p(99.9999) =     25.788 ms/op
    p(100.0000) =     25.788 ms/op


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
# Warmup Iteration   1: 8.510 ±(99.9%) 0.111 ms/op
# Warmup Iteration   2: 3.494 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.404 ±(99.9%) 0.009 ms/op
Iteration   1: 3.230 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.317 ms/op
                 existUser·p0.50:   3.092 ms/op
                 existUser·p0.90:   3.564 ms/op
                 existUser·p0.95:   4.465 ms/op
                 existUser·p0.99:   5.685 ms/op
                 existUser·p0.999:  11.779 ms/op
                 existUser·p0.9999: 21.823 ms/op
                 existUser·p1.00:   22.446 ms/op

Iteration   2: 3.173 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.417 ms/op
                 existUser·p0.50:   3.076 ms/op
                 existUser·p0.90:   3.326 ms/op
                 existUser·p0.95:   3.740 ms/op
                 existUser·p0.99:   6.070 ms/op
                 existUser·p0.999:  10.781 ms/op
                 existUser·p0.9999: 23.787 ms/op
                 existUser·p1.00:   24.347 ms/op

Iteration   3: 3.347 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.702 ms/op
                 existUser·p0.50:   3.277 ms/op
                 existUser·p0.90:   3.801 ms/op
                 existUser·p0.95:   4.252 ms/op
                 existUser·p0.99:   5.538 ms/op
                 existUser·p0.999:  21.585 ms/op
                 existUser·p0.9999: 29.047 ms/op
                 existUser·p1.00:   29.295 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 295617
  mean =      3.248 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15631 
    [ 2.500,  5.000) = 273629 
    [ 5.000,  7.500) = 5538 
    [ 7.500, 10.000) = 486 
    [10.000, 12.500) = 45 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 103 
    [22.500, 25.000) = 119 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.317 ms/op
     p(50.0000) =      3.158 ms/op
     p(90.0000) =      3.576 ms/op
     p(95.0000) =      4.125 ms/op
     p(99.0000) =      5.710 ms/op
     p(99.9000) =     11.148 ms/op
     p(99.9900) =     27.638 ms/op
     p(99.9990) =     29.263 ms/op
     p(99.9999) =     29.295 ms/op
    p(100.0000) =     29.295 ms/op


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
# Warmup Iteration   1: 9.573 ±(99.9%) 0.111 ms/op
# Warmup Iteration   2: 3.710 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.503 ±(99.9%) 0.011 ms/op
Iteration   1: 3.352 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.102 ms/op
                 getUser·p0.50:   3.244 ms/op
                 getUser·p0.90:   3.731 ms/op
                 getUser·p0.95:   4.039 ms/op
                 getUser·p0.99:   6.216 ms/op
                 getUser·p0.999:  21.515 ms/op
                 getUser·p0.9999: 23.298 ms/op
                 getUser·p1.00:   25.461 ms/op

Iteration   2: 3.331 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.524 ms/op
                 getUser·p0.50:   3.260 ms/op
                 getUser·p0.90:   3.711 ms/op
                 getUser·p0.95:   3.973 ms/op
                 getUser·p0.99:   5.612 ms/op
                 getUser·p0.999:  8.716 ms/op
                 getUser·p0.9999: 24.491 ms/op
                 getUser·p1.00:   24.838 ms/op

Iteration   3: 3.472 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.464 ms/op
                 getUser·p0.50:   3.346 ms/op
                 getUser·p0.90:   4.059 ms/op
                 getUser·p0.95:   4.407 ms/op
                 getUser·p0.99:   5.775 ms/op
                 getUser·p0.999:  9.208 ms/op
                 getUser·p0.9999: 28.304 ms/op
                 getUser·p1.00:   29.622 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 283696
  mean =      3.384 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13690 
    [ 2.500,  5.000) = 263287 
    [ 5.000,  7.500) = 5799 
    [ 7.500, 10.000) = 566 
    [10.000, 12.500) = 67 
    [12.500, 15.000) = 31 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 116 
    [22.500, 25.000) = 95 
    [25.000, 27.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      0.464 ms/op
     p(50.0000) =      3.285 ms/op
     p(90.0000) =      3.854 ms/op
     p(95.0000) =      4.182 ms/op
     p(99.0000) =      5.808 ms/op
     p(99.9000) =     12.555 ms/op
     p(99.9900) =     25.888 ms/op
     p(99.9990) =     29.464 ms/op
     p(99.9999) =     29.622 ms/op
    p(100.0000) =     29.622 ms/op


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
# Warmup Iteration   1: 9.305 ±(99.9%) 0.126 ms/op
# Warmup Iteration   2: 4.253 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.919 ±(99.9%) 0.012 ms/op
Iteration   1: 4.014 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.298 ms/op
                 listUser·p0.50:   3.871 ms/op
                 listUser·p0.90:   4.375 ms/op
                 listUser·p0.95:   5.046 ms/op
                 listUser·p0.99:   7.070 ms/op
                 listUser·p0.999:  18.986 ms/op
                 listUser·p0.9999: 22.053 ms/op
                 listUser·p1.00:   23.560 ms/op

Iteration   2: 4.032 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.569 ms/op
                 listUser·p0.50:   3.879 ms/op
                 listUser·p0.90:   4.334 ms/op
                 listUser·p0.95:   4.719 ms/op
                 listUser·p0.99:   7.709 ms/op
                 listUser·p0.999:  14.483 ms/op
                 listUser·p0.9999: 21.580 ms/op
                 listUser·p1.00:   22.675 ms/op

Iteration   3: 4.004 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.322 ms/op
                 listUser·p0.50:   3.887 ms/op
                 listUser·p0.90:   4.301 ms/op
                 listUser·p0.95:   4.571 ms/op
                 listUser·p0.99:   7.889 ms/op
                 listUser·p0.999:  18.285 ms/op
                 listUser·p0.9999: 22.748 ms/op
                 listUser·p1.00:   23.298 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 238997
  mean =      4.017 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 53 
    [ 2.500,  5.000) = 228801 
    [ 5.000,  7.500) = 7685 
    [ 7.500, 10.000) = 1596 
    [10.000, 12.500) = 306 
    [12.500, 15.000) = 243 
    [15.000, 17.500) = 44 
    [17.500, 20.000) = 145 
    [20.000, 22.500) = 98 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.298 ms/op
     p(50.0000) =      3.875 ms/op
     p(90.0000) =      4.334 ms/op
     p(95.0000) =      4.743 ms/op
     p(99.0000) =      7.578 ms/op
     p(99.9000) =     18.186 ms/op
     p(99.9900) =     22.544 ms/op
     p(99.9990) =     23.285 ms/op
     p(99.9999) =     23.560 ms/op
    p(100.0000) =     23.560 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.278 ± 6.712  ops/ms
ClientPb.existUser                       thrpt       3  10.026 ± 0.102  ops/ms
ClientPb.getUser                         thrpt       3   9.510 ± 4.564  ops/ms
ClientPb.listUser                        thrpt       3   8.087 ± 0.883  ops/ms
ClientPb.createUser                       avgt       3   3.335 ± 0.610   ms/op
ClientPb.existUser                        avgt       3   3.135 ± 0.602   ms/op
ClientPb.getUser                          avgt       3   3.417 ± 1.028   ms/op
ClientPb.listUser                         avgt       3   3.922 ± 1.372   ms/op
ClientPb.createUser                     sample  288088   3.333 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.579           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.224           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.707           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.994           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.628           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.464           ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.510           ms/op
ClientPb.createUser:createUser·p1.00    sample          25.788           ms/op
ClientPb.existUser                      sample  295617   3.248 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.317           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.158           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.576           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.125           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.710           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.148           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.638           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.295           ms/op
ClientPb.getUser                        sample  283696   3.384 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.464           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.285           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.854           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.182           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.808           ms/op
ClientPb.getUser:getUser·p0.999         sample          12.555           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.888           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.622           ms/op
ClientPb.listUser                       sample  238997   4.017 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.298           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.875           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.334           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.743           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.578           ms/op
ClientPb.listUser:listUser·p0.999       sample          18.186           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.544           ms/op
ClientPb.listUser:listUser·p1.00        sample          23.560           ms/op
