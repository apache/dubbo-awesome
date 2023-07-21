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
# Warmup Iteration   1: 2.156 ops/ms
# Warmup Iteration   2: 5.462 ops/ms
# Warmup Iteration   3: 8.395 ops/ms
Iteration   1: 9.210 ops/ms
Iteration   2: 9.335 ops/ms
Iteration   3: 9.138 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.228 ±(99.9%) 1.812 ops/ms [Average]
  (min, avg, max) = (9.138, 9.228, 9.335), stdev = 0.099
  CI (99.9%): [7.415, 11.040] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 3.119 ops/ms
# Warmup Iteration   2: 8.475 ops/ms
# Warmup Iteration   3: 9.627 ops/ms
Iteration   1: 9.671 ops/ms
Iteration   2: 9.463 ops/ms
Iteration   3: 9.618 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.584 ±(99.9%) 1.967 ops/ms [Average]
  (min, avg, max) = (9.463, 9.584, 9.671), stdev = 0.108
  CI (99.9%): [7.617, 11.552] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 2.818 ops/ms
# Warmup Iteration   2: 8.494 ops/ms
# Warmup Iteration   3: 9.518 ops/ms
Iteration   1: 9.377 ops/ms
Iteration   2: 9.235 ops/ms
Iteration   3: 9.024 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.212 ±(99.9%) 3.244 ops/ms [Average]
  (min, avg, max) = (9.024, 9.212, 9.377), stdev = 0.178
  CI (99.9%): [5.968, 12.456] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 2.729 ops/ms
# Warmup Iteration   2: 7.368 ops/ms
# Warmup Iteration   3: 7.608 ops/ms
Iteration   1: 7.986 ops/ms
Iteration   2: 7.905 ops/ms
Iteration   3: 8.147 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.013 ±(99.9%) 2.251 ops/ms [Average]
  (min, avg, max) = (7.905, 8.013, 8.147), stdev = 0.123
  CI (99.9%): [5.761, 10.264] (assumes normal distribution)


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
# Warmup Iteration   1: 8.640 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.761 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.710 ±(99.9%) 0.008 ms/op
Iteration   1: 3.385 ±(99.9%) 0.011 ms/op
Iteration   2: 3.384 ±(99.9%) 0.010 ms/op
Iteration   3: 3.313 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.361 ±(99.9%) 0.745 ms/op [Average]
  (min, avg, max) = (3.313, 3.361, 3.385), stdev = 0.041
  CI (99.9%): [2.615, 4.106] (assumes normal distribution)


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
# Warmup Iteration   1: 8.624 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.630 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.336 ±(99.9%) 0.006 ms/op
Iteration   1: 3.195 ±(99.9%) 0.010 ms/op
Iteration   2: 3.289 ±(99.9%) 0.007 ms/op
Iteration   3: 3.446 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.310 ±(99.9%) 2.313 ms/op [Average]
  (min, avg, max) = (3.195, 3.310, 3.446), stdev = 0.127
  CI (99.9%): [0.997, 5.623] (assumes normal distribution)


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
# Warmup Iteration   1: 10.234 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.688 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.644 ±(99.9%) 0.007 ms/op
Iteration   1: 3.398 ±(99.9%) 0.005 ms/op
Iteration   2: 3.400 ±(99.9%) 0.004 ms/op
Iteration   3: 3.321 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.373 ±(99.9%) 0.826 ms/op [Average]
  (min, avg, max) = (3.321, 3.373, 3.400), stdev = 0.045
  CI (99.9%): [2.547, 4.199] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 10.100 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 4.180 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.021 ±(99.9%) 0.009 ms/op
Iteration   1: 3.857 ±(99.9%) 0.011 ms/op
Iteration   2: 3.845 ±(99.9%) 0.011 ms/op
Iteration   3: 3.905 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.869 ±(99.9%) 0.582 ms/op [Average]
  (min, avg, max) = (3.845, 3.869, 3.905), stdev = 0.032
  CI (99.9%): [3.287, 4.451] (assumes normal distribution)


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
# Warmup Iteration   1: 8.954 ±(99.9%) 0.111 ms/op
# Warmup Iteration   2: 4.069 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.538 ±(99.9%) 0.011 ms/op
Iteration   1: 3.503 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.698 ms/op
                 createUser·p0.50:   3.375 ms/op
                 createUser·p0.90:   4.125 ms/op
                 createUser·p0.95:   4.432 ms/op
                 createUser·p0.99:   6.185 ms/op
                 createUser·p0.999:  20.865 ms/op
                 createUser·p0.9999: 24.195 ms/op
                 createUser·p1.00:   24.707 ms/op

Iteration   2: 3.455 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.567 ms/op
                 createUser·p0.50:   3.330 ms/op
                 createUser·p0.90:   4.051 ms/op
                 createUser·p0.95:   4.506 ms/op
                 createUser·p0.99:   5.538 ms/op
                 createUser·p0.999:  22.807 ms/op
                 createUser·p0.9999: 28.074 ms/op
                 createUser·p1.00:   28.410 ms/op

Iteration   3: 3.365 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.300 ms/op
                 createUser·p0.50:   3.342 ms/op
                 createUser·p0.90:   3.531 ms/op
                 createUser·p0.95:   3.953 ms/op
                 createUser·p0.99:   5.726 ms/op
                 createUser·p0.999:  16.217 ms/op
                 createUser·p0.9999: 26.296 ms/op
                 createUser·p1.00:   27.001 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 279017
  mean =      3.440 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13328 
    [ 2.500,  5.000) = 259233 
    [ 5.000,  7.500) = 5407 
    [ 7.500, 10.000) = 554 
    [10.000, 12.500) = 95 
    [12.500, 15.000) = 57 
    [15.000, 17.500) = 49 
    [17.500, 20.000) = 46 
    [20.000, 22.500) = 81 
    [22.500, 25.000) = 65 
    [25.000, 27.500) = 86 

  Percentiles, ms/op:
      p(0.0000) =      1.300 ms/op
     p(50.0000) =      3.351 ms/op
     p(90.0000) =      3.961 ms/op
     p(95.0000) =      4.366 ms/op
     p(99.0000) =      5.759 ms/op
     p(99.9000) =     19.169 ms/op
     p(99.9900) =     27.040 ms/op
     p(99.9990) =     28.267 ms/op
     p(99.9999) =     28.410 ms/op
    p(100.0000) =     28.410 ms/op


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
# Warmup Iteration   1: 8.411 ±(99.9%) 0.113 ms/op
# Warmup Iteration   2: 3.630 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.305 ±(99.9%) 0.007 ms/op
Iteration   1: 3.188 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.907 ms/op
                 existUser·p0.50:   3.170 ms/op
                 existUser·p0.90:   3.326 ms/op
                 existUser·p0.95:   3.469 ms/op
                 existUser·p0.99:   5.489 ms/op
                 existUser·p0.999:  9.667 ms/op
                 existUser·p0.9999: 23.525 ms/op
                 existUser·p1.00:   23.986 ms/op

Iteration   2: 3.384 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.499 ms/op
                 existUser·p0.50:   3.232 ms/op
                 existUser·p0.90:   3.875 ms/op
                 existUser·p0.95:   4.366 ms/op
                 existUser·p0.99:   5.809 ms/op
                 existUser·p0.999:  19.154 ms/op
                 existUser·p0.9999: 23.203 ms/op
                 existUser·p1.00:   23.658 ms/op

Iteration   3: 3.334 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.362 ms/op
                 existUser·p0.50:   3.240 ms/op
                 existUser·p0.90:   3.813 ms/op
                 existUser·p0.95:   4.166 ms/op
                 existUser·p0.99:   5.800 ms/op
                 existUser·p0.999:  17.924 ms/op
                 existUser·p0.9999: 26.195 ms/op
                 existUser·p1.00:   26.935 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 290728
  mean =      3.300 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14415 
    [ 2.500,  5.000) = 271323 
    [ 5.000,  7.500) = 3992 
    [ 7.500, 10.000) = 650 
    [10.000, 12.500) = 59 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 99 
    [20.000, 22.500) = 93 
    [22.500, 25.000) = 61 
    [25.000, 27.500) = 35 

  Percentiles, ms/op:
      p(0.0000) =      0.907 ms/op
     p(50.0000) =      3.207 ms/op
     p(90.0000) =      3.699 ms/op
     p(95.0000) =      4.084 ms/op
     p(99.0000) =      5.685 ms/op
     p(99.9000) =     12.225 ms/op
     p(99.9900) =     25.655 ms/op
     p(99.9990) =     26.516 ms/op
     p(99.9999) =     26.935 ms/op
    p(100.0000) =     26.935 ms/op


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
# Warmup Iteration   1: 8.802 ±(99.9%) 0.117 ms/op
# Warmup Iteration   2: 3.770 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.606 ±(99.9%) 0.012 ms/op
Iteration   1: 3.384 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.499 ms/op
                 getUser·p0.50:   3.273 ms/op
                 getUser·p0.90:   3.690 ms/op
                 getUser·p0.95:   3.842 ms/op
                 getUser·p0.99:   6.160 ms/op
                 getUser·p0.999:  18.562 ms/op
                 getUser·p0.9999: 22.824 ms/op
                 getUser·p1.00:   23.527 ms/op

Iteration   2: 3.356 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.241 ms/op
                 getUser·p0.50:   3.244 ms/op
                 getUser·p0.90:   3.699 ms/op
                 getUser·p0.95:   3.867 ms/op
                 getUser·p0.99:   5.865 ms/op
                 getUser·p0.999:  19.154 ms/op
                 getUser·p0.9999: 25.690 ms/op
                 getUser·p1.00:   26.903 ms/op

Iteration   3: 3.393 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.769 ms/op
                 getUser·p0.50:   3.252 ms/op
                 getUser·p0.90:   3.731 ms/op
                 getUser·p0.95:   4.061 ms/op
                 getUser·p0.99:   6.685 ms/op
                 getUser·p0.999:  18.048 ms/op
                 getUser·p0.9999: 25.283 ms/op
                 getUser·p1.00:   25.756 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 284102
  mean =      3.378 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2261 
    [ 2.500,  5.000) = 276324 
    [ 5.000,  7.500) = 4375 
    [ 7.500, 10.000) = 711 
    [10.000, 12.500) = 122 
    [12.500, 15.000) = 5 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 113 
    [20.000, 22.500) = 95 
    [22.500, 25.000) = 66 
    [25.000, 27.500) = 29 

  Percentiles, ms/op:
      p(0.0000) =      1.241 ms/op
     p(50.0000) =      3.256 ms/op
     p(90.0000) =      3.703 ms/op
     p(95.0000) =      3.895 ms/op
     p(99.0000) =      6.193 ms/op
     p(99.9000) =     18.055 ms/op
     p(99.9900) =     25.021 ms/op
     p(99.9990) =     26.251 ms/op
     p(99.9999) =     26.903 ms/op
    p(100.0000) =     26.903 ms/op


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
# Warmup Iteration   1: 10.641 ±(99.9%) 0.151 ms/op
# Warmup Iteration   2: 4.408 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.141 ±(99.9%) 0.014 ms/op
Iteration   1: 4.072 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.686 ms/op
                 listUser·p0.50:   3.969 ms/op
                 listUser·p0.90:   4.481 ms/op
                 listUser·p0.95:   4.899 ms/op
                 listUser·p0.99:   7.348 ms/op
                 listUser·p0.999:  18.343 ms/op
                 listUser·p0.9999: 27.984 ms/op
                 listUser·p1.00:   28.869 ms/op

Iteration   2: 3.971 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.669 ms/op
                 listUser·p0.50:   3.883 ms/op
                 listUser·p0.90:   4.309 ms/op
                 listUser·p0.95:   4.817 ms/op
                 listUser·p0.99:   6.701 ms/op
                 listUser·p0.999:  15.957 ms/op
                 listUser·p0.9999: 20.775 ms/op
                 listUser·p1.00:   20.775 ms/op

Iteration   3: 4.126 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.739 ms/op
                 listUser·p0.50:   3.940 ms/op
                 listUser·p0.90:   4.653 ms/op
                 listUser·p0.95:   5.251 ms/op
                 listUser·p0.99:   7.815 ms/op
                 listUser·p0.999:  15.465 ms/op
                 listUser·p0.9999: 17.481 ms/op
                 listUser·p1.00:   18.252 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 236660
  mean =      4.056 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 45 
    [ 2.500,  5.000) = 225756 
    [ 5.000,  7.500) = 8706 
    [ 7.500, 10.000) = 1385 
    [10.000, 12.500) = 256 
    [12.500, 15.000) = 150 
    [15.000, 17.500) = 214 
    [17.500, 20.000) = 85 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      0.669 ms/op
     p(50.0000) =      3.920 ms/op
     p(90.0000) =      4.522 ms/op
     p(95.0000) =      4.923 ms/op
     p(99.0000) =      7.299 ms/op
     p(99.9000) =     16.368 ms/op
     p(99.9900) =     26.302 ms/op
     p(99.9990) =     28.513 ms/op
     p(99.9999) =     28.869 ms/op
    p(100.0000) =     28.869 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.228 ± 1.812  ops/ms
ClientPb.existUser                       thrpt       3   9.584 ± 1.967  ops/ms
ClientPb.getUser                         thrpt       3   9.212 ± 3.244  ops/ms
ClientPb.listUser                        thrpt       3   8.013 ± 2.251  ops/ms
ClientPb.createUser                       avgt       3   3.361 ± 0.745   ms/op
ClientPb.existUser                        avgt       3   3.310 ± 2.313   ms/op
ClientPb.getUser                          avgt       3   3.373 ± 0.826   ms/op
ClientPb.listUser                         avgt       3   3.869 ± 0.582   ms/op
ClientPb.createUser                     sample  279017   3.440 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.300           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.351           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.961           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.366           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.759           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.169           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.040           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.410           ms/op
ClientPb.existUser                      sample  290728   3.300 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.907           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.207           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.699           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.084           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.685           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.225           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.655           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.935           ms/op
ClientPb.getUser                        sample  284102   3.378 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.241           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.256           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.703           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.895           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.193           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.055           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.021           ms/op
ClientPb.getUser:getUser·p1.00          sample          26.903           ms/op
ClientPb.listUser                       sample  236660   4.056 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.669           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.920           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.522           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.923           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.299           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.368           ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.302           ms/op
ClientPb.listUser:listUser·p1.00        sample          28.869           ms/op
