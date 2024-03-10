# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 5.476 ops/ms
# Warmup Iteration   2: 12.358 ops/ms
# Warmup Iteration   3: 12.747 ops/ms
Iteration   1: 13.302 ops/ms
Iteration   2: 12.796 ops/ms
Iteration   3: 13.076 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  13.058 ±(99.9%) 4.616 ops/ms [Average]
  (min, avg, max) = (12.796, 13.058, 13.302), stdev = 0.253
  CI (99.9%): [8.442, 17.674] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:52
# Fork: 1 of 1
# Warmup Iteration   1: 8.822 ops/ms
# Warmup Iteration   2: 13.697 ops/ms
# Warmup Iteration   3: 13.505 ops/ms
Iteration   1: 13.623 ops/ms
Iteration   2: 13.794 ops/ms
Iteration   3: 13.803 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.740 ±(99.9%) 1.856 ops/ms [Average]
  (min, avg, max) = (13.623, 13.740, 13.803), stdev = 0.102
  CI (99.9%): [11.884, 15.595] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.529 ops/ms
# Warmup Iteration   2: 12.835 ops/ms
# Warmup Iteration   3: 13.400 ops/ms
Iteration   1: 13.441 ops/ms
Iteration   2: 13.404 ops/ms
Iteration   3: 13.539 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.461 ±(99.9%) 1.279 ops/ms [Average]
  (min, avg, max) = (13.404, 13.461, 13.539), stdev = 0.070
  CI (99.9%): [12.183, 14.740] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.872 ops/ms
# Warmup Iteration   2: 10.866 ops/ms
# Warmup Iteration   3: 11.126 ops/ms
Iteration   1: 11.003 ops/ms
Iteration   2: 11.262 ops/ms
Iteration   3: 11.075 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  11.113 ±(99.9%) 2.440 ops/ms [Average]
  (min, avg, max) = (11.003, 11.113, 11.262), stdev = 0.134
  CI (99.9%): [8.673, 13.553] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:39
# Fork: 1 of 1
# Warmup Iteration   1: 3.927 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.532 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.430 ±(99.9%) 0.007 ms/op
Iteration   1: 2.444 ±(99.9%) 0.007 ms/op
Iteration   2: 2.413 ±(99.9%) 0.006 ms/op
Iteration   3: 2.407 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.421 ±(99.9%) 0.361 ms/op [Average]
  (min, avg, max) = (2.407, 2.421, 2.444), stdev = 0.020
  CI (99.9%): [2.060, 2.782] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.815 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.426 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.359 ±(99.9%) 0.006 ms/op
Iteration   1: 2.298 ±(99.9%) 0.007 ms/op
Iteration   2: 2.374 ±(99.9%) 0.004 ms/op
Iteration   3: 2.346 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.339 ±(99.9%) 0.695 ms/op [Average]
  (min, avg, max) = (2.298, 2.339, 2.374), stdev = 0.038
  CI (99.9%): [1.644, 3.035] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.834 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.514 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.466 ±(99.9%) 0.004 ms/op
Iteration   1: 2.465 ±(99.9%) 0.004 ms/op
Iteration   2: 2.494 ±(99.9%) 0.003 ms/op
Iteration   3: 2.494 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.485 ±(99.9%) 0.306 ms/op [Average]
  (min, avg, max) = (2.465, 2.485, 2.494), stdev = 0.017
  CI (99.9%): [2.179, 2.790] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.868 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.038 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.974 ±(99.9%) 0.005 ms/op
Iteration   1: 2.957 ±(99.9%) 0.006 ms/op
Iteration   2: 2.986 ±(99.9%) 0.007 ms/op
Iteration   3: 2.964 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.969 ±(99.9%) 0.272 ms/op [Average]
  (min, avg, max) = (2.957, 2.969, 2.986), stdev = 0.015
  CI (99.9%): [2.697, 3.241] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:19
# Fork: 1 of 1
# Warmup Iteration   1: 4.369 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 2.669 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.527 ±(99.9%) 0.006 ms/op
Iteration   1: 2.505 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.931 ms/op
                 createUser·p0.50:   2.560 ms/op
                 createUser·p0.90:   3.039 ms/op
                 createUser·p0.95:   3.154 ms/op
                 createUser·p0.99:   3.772 ms/op
                 createUser·p0.999:  11.426 ms/op
                 createUser·p0.9999: 14.364 ms/op
                 createUser·p1.00:   14.778 ms/op

Iteration   2: 2.508 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.055 ms/op
                 createUser·p0.50:   2.564 ms/op
                 createUser·p0.90:   3.039 ms/op
                 createUser·p0.95:   3.158 ms/op
                 createUser·p0.99:   3.723 ms/op
                 createUser·p0.999:  9.248 ms/op
                 createUser·p0.9999: 20.316 ms/op
                 createUser·p1.00:   22.217 ms/op

Iteration   3: 2.495 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.065 ms/op
                 createUser·p0.50:   2.597 ms/op
                 createUser·p0.90:   3.019 ms/op
                 createUser·p0.95:   3.125 ms/op
                 createUser·p0.99:   3.699 ms/op
                 createUser·p0.999:  8.551 ms/op
                 createUser·p0.9999: 10.650 ms/op
                 createUser·p1.00:   10.994 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 383236
  mean =      2.503 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 185626 
    [ 2.500,  5.000) = 196878 
    [ 5.000,  7.500) = 345 
    [ 7.500, 10.000) = 79 
    [10.000, 12.500) = 203 
    [12.500, 15.000) = 73 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.931 ms/op
     p(50.0000) =      2.572 ms/op
     p(90.0000) =      3.031 ms/op
     p(95.0000) =      3.146 ms/op
     p(99.0000) =      3.731 ms/op
     p(99.9000) =      8.590 ms/op
     p(99.9900) =     14.538 ms/op
     p(99.9990) =     20.617 ms/op
     p(99.9999) =     22.217 ms/op
    p(100.0000) =     22.217 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.834 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.477 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.427 ±(99.9%) 0.005 ms/op
Iteration   1: 2.450 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.108 ms/op
                 existUser·p0.50:   2.482 ms/op
                 existUser·p0.90:   2.986 ms/op
                 existUser·p0.95:   3.084 ms/op
                 existUser·p0.99:   3.420 ms/op
                 existUser·p0.999:  4.944 ms/op
                 existUser·p0.9999: 13.942 ms/op
                 existUser·p1.00:   14.320 ms/op

Iteration   2: 2.474 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.071 ms/op
                 existUser·p0.50:   2.515 ms/op
                 existUser·p0.90:   3.011 ms/op
                 existUser·p0.95:   3.113 ms/op
                 existUser·p0.99:   3.539 ms/op
                 existUser·p0.999:  6.881 ms/op
                 existUser·p0.9999: 13.092 ms/op
                 existUser·p1.00:   13.730 ms/op

Iteration   3: 2.484 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.947 ms/op
                 existUser·p0.50:   2.531 ms/op
                 existUser·p0.90:   3.023 ms/op
                 existUser·p0.95:   3.138 ms/op
                 existUser·p0.99:   3.678 ms/op
                 existUser·p0.999:  9.086 ms/op
                 existUser·p0.9999: 12.014 ms/op
                 existUser·p1.00:   12.370 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 388430
  mean =      2.469 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 38 
    [ 1.250,  2.500) = 193663 
    [ 2.500,  3.750) = 191988 
    [ 3.750,  5.000) = 2078 
    [ 5.000,  6.250) = 271 
    [ 6.250,  7.500) = 28 
    [ 7.500,  8.750) = 26 
    [ 8.750, 10.000) = 62 
    [10.000, 11.250) = 104 
    [11.250, 12.500) = 85 
    [12.500, 13.750) = 72 
    [13.750, 15.000) = 15 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.947 ms/op
     p(50.0000) =      2.507 ms/op
     p(90.0000) =      3.006 ms/op
     p(95.0000) =      3.113 ms/op
     p(99.0000) =      3.543 ms/op
     p(99.9000) =      6.275 ms/op
     p(99.9900) =     13.206 ms/op
     p(99.9990) =     14.100 ms/op
     p(99.9999) =     14.320 ms/op
    p(100.0000) =     14.320 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 4.092 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.590 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.524 ±(99.9%) 0.006 ms/op
Iteration   1: 2.492 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.927 ms/op
                 getUser·p0.50:   2.519 ms/op
                 getUser·p0.90:   3.027 ms/op
                 getUser·p0.95:   3.154 ms/op
                 getUser·p0.99:   3.969 ms/op
                 getUser·p0.999:  10.103 ms/op
                 getUser·p0.9999: 13.989 ms/op
                 getUser·p1.00:   14.402 ms/op

Iteration   2: 2.472 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.805 ms/op
                 getUser·p0.50:   2.511 ms/op
                 getUser·p0.90:   2.998 ms/op
                 getUser·p0.95:   3.129 ms/op
                 getUser·p0.99:   3.916 ms/op
                 getUser·p0.999:  7.291 ms/op
                 getUser·p0.9999: 25.430 ms/op
                 getUser·p1.00:   28.672 ms/op

Iteration   3: 2.476 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.886 ms/op
                 getUser·p0.50:   2.511 ms/op
                 getUser·p0.90:   3.023 ms/op
                 getUser·p0.95:   3.158 ms/op
                 getUser·p0.99:   3.838 ms/op
                 getUser·p0.999:  6.731 ms/op
                 getUser·p0.9999: 11.174 ms/op
                 getUser·p1.00:   11.469 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 386761
  mean =      2.480 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 192102 
    [ 2.500,  5.000) = 193323 
    [ 5.000,  7.500) = 951 
    [ 7.500, 10.000) = 78 
    [10.000, 12.500) = 198 
    [12.500, 15.000) = 77 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 20 

  Percentiles, ms/op:
      p(0.0000) =      0.805 ms/op
     p(50.0000) =      2.515 ms/op
     p(90.0000) =      3.019 ms/op
     p(95.0000) =      3.150 ms/op
     p(99.0000) =      3.899 ms/op
     p(99.9000) =      7.249 ms/op
     p(99.9900) =     14.134 ms/op
     p(99.9990) =     26.129 ms/op
     p(99.9999) =     28.672 ms/op
    p(100.0000) =     28.672 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.718 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.053 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.011 ±(99.9%) 0.009 ms/op
Iteration   1: 3.014 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.872 ms/op
                 listUser·p0.50:   2.945 ms/op
                 listUser·p0.90:   3.908 ms/op
                 listUser·p0.95:   4.440 ms/op
                 listUser·p0.99:   5.603 ms/op
                 listUser·p0.999:  9.321 ms/op
                 listUser·p0.9999: 11.190 ms/op
                 listUser·p1.00:   12.255 ms/op

Iteration   2: 3.032 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.889 ms/op
                 listUser·p0.50:   2.957 ms/op
                 listUser·p0.90:   3.953 ms/op
                 listUser·p0.95:   4.497 ms/op
                 listUser·p0.99:   5.669 ms/op
                 listUser·p0.999:  9.847 ms/op
                 listUser·p0.9999: 12.459 ms/op
                 listUser·p1.00:   13.451 ms/op

Iteration   3: 3.019 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.876 ms/op
                 listUser·p0.50:   2.949 ms/op
                 listUser·p0.90:   3.887 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   5.571 ms/op
                 listUser·p0.999:  9.741 ms/op
                 listUser·p0.9999: 11.164 ms/op
                 listUser·p1.00:   12.091 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 317370
  mean =      3.022 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 107 
    [ 1.250,  2.500) = 89650 
    [ 2.500,  3.750) = 186970 
    [ 3.750,  5.000) = 32802 
    [ 5.000,  6.250) = 6429 
    [ 6.250,  7.500) = 764 
    [ 7.500,  8.750) = 196 
    [ 8.750, 10.000) = 223 
    [10.000, 11.250) = 176 
    [11.250, 12.500) = 45 
    [12.500, 13.750) = 8 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.872 ms/op
     p(50.0000) =      2.953 ms/op
     p(90.0000) =      3.916 ms/op
     p(95.0000) =      4.432 ms/op
     p(99.0000) =      5.612 ms/op
     p(99.9000) =      9.611 ms/op
     p(99.9900) =     11.584 ms/op
     p(99.9990) =     12.894 ms/op
     p(99.9999) =     13.451 ms/op
    p(100.0000) =     13.451 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  13.058 ± 4.616  ops/ms
ClientPb.existUser                       thrpt       3  13.740 ± 1.856  ops/ms
ClientPb.getUser                         thrpt       3  13.461 ± 1.279  ops/ms
ClientPb.listUser                        thrpt       3  11.113 ± 2.440  ops/ms
ClientPb.createUser                       avgt       3   2.421 ± 0.361   ms/op
ClientPb.existUser                        avgt       3   2.339 ± 0.695   ms/op
ClientPb.getUser                          avgt       3   2.485 ± 0.306   ms/op
ClientPb.listUser                         avgt       3   2.969 ± 0.272   ms/op
ClientPb.createUser                     sample  383236   2.503 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.931           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.572           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.031           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.146           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.731           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.590           ms/op
ClientPb.createUser:createUser·p0.9999  sample          14.538           ms/op
ClientPb.createUser:createUser·p1.00    sample          22.217           ms/op
ClientPb.existUser                      sample  388430   2.469 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.947           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.507           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.006           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.113           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.543           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.275           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.206           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.320           ms/op
ClientPb.getUser                        sample  386761   2.480 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.805           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.515           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.019           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.150           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.899           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.249           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.134           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.672           ms/op
ClientPb.listUser                       sample  317370   3.022 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.872           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.953           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.916           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.432           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.612           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.611           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.584           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.451           ms/op
