# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.126 ops/ms
# Warmup Iteration   2: 5.451 ops/ms
# Warmup Iteration   3: 8.705 ops/ms
Iteration   1: 9.238 ops/ms
Iteration   2: 9.114 ops/ms
Iteration   3: 9.511 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.288 ±(99.9%) 3.701 ops/ms [Average]
  (min, avg, max) = (9.114, 9.288, 9.511), stdev = 0.203
  CI (99.9%): [5.587, 12.988] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.289 ops/ms
# Warmup Iteration   2: 9.086 ops/ms
# Warmup Iteration   3: 9.539 ops/ms
Iteration   1: 9.493 ops/ms
Iteration   2: 9.559 ops/ms
Iteration   3: 9.560 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.537 ±(99.9%) 0.700 ops/ms [Average]
  (min, avg, max) = (9.493, 9.537, 9.560), stdev = 0.038
  CI (99.9%): [8.837, 10.237] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.880 ops/ms
# Warmup Iteration   2: 8.363 ops/ms
# Warmup Iteration   3: 9.185 ops/ms
Iteration   1: 9.240 ops/ms
Iteration   2: 9.298 ops/ms
Iteration   3: 9.323 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.287 ±(99.9%) 0.778 ops/ms [Average]
  (min, avg, max) = (9.240, 9.287, 9.323), stdev = 0.043
  CI (99.9%): [8.509, 10.065] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.804 ops/ms
# Warmup Iteration   2: 7.291 ops/ms
# Warmup Iteration   3: 7.797 ops/ms
Iteration   1: 7.749 ops/ms
Iteration   2: 7.664 ops/ms
Iteration   3: 7.811 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.741 ±(99.9%) 1.347 ops/ms [Average]
  (min, avg, max) = (7.664, 7.741, 7.811), stdev = 0.074
  CI (99.9%): [6.394, 9.088] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 9.247 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.893 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.592 ±(99.9%) 0.003 ms/op
Iteration   1: 3.455 ±(99.9%) 0.004 ms/op
Iteration   2: 3.406 ±(99.9%) 0.008 ms/op
Iteration   3: 3.414 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.425 ±(99.9%) 0.484 ms/op [Average]
  (min, avg, max) = (3.406, 3.425, 3.455), stdev = 0.027
  CI (99.9%): [2.941, 3.909] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 8.159 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.546 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.408 ±(99.9%) 0.005 ms/op
Iteration   1: 3.369 ±(99.9%) 0.004 ms/op
Iteration   2: 3.313 ±(99.9%) 0.005 ms/op
Iteration   3: 3.266 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.316 ±(99.9%) 0.942 ms/op [Average]
  (min, avg, max) = (3.266, 3.316, 3.369), stdev = 0.052
  CI (99.9%): [2.374, 4.257] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 10.047 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.682 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.479 ±(99.9%) 0.003 ms/op
Iteration   1: 3.446 ±(99.9%) 0.004 ms/op
Iteration   2: 3.513 ±(99.9%) 0.002 ms/op
Iteration   3: 3.479 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.479 ±(99.9%) 0.616 ms/op [Average]
  (min, avg, max) = (3.446, 3.479, 3.513), stdev = 0.034
  CI (99.9%): [2.864, 4.095] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 12.956 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 4.846 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.375 ±(99.9%) 0.007 ms/op
Iteration   1: 4.109 ±(99.9%) 0.007 ms/op
Iteration   2: 4.064 ±(99.9%) 0.007 ms/op
Iteration   3: 4.070 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.081 ±(99.9%) 0.450 ms/op [Average]
  (min, avg, max) = (4.064, 4.081, 4.109), stdev = 0.025
  CI (99.9%): [3.631, 4.531] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 9.461 ±(99.9%) 0.137 ms/op
# Warmup Iteration   2: 4.030 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.463 ±(99.9%) 0.010 ms/op
Iteration   1: 3.607 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.409 ms/op
                 createUser·p0.50:   3.457 ms/op
                 createUser·p0.90:   4.227 ms/op
                 createUser·p0.95:   4.514 ms/op
                 createUser·p0.99:   6.652 ms/op
                 createUser·p0.999:  17.802 ms/op
                 createUser·p0.9999: 20.718 ms/op
                 createUser·p1.00:   21.103 ms/op

Iteration   2: 3.395 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.320 ms/op
                 createUser·p0.50:   3.375 ms/op
                 createUser·p0.90:   3.727 ms/op
                 createUser·p0.95:   4.006 ms/op
                 createUser·p0.99:   5.513 ms/op
                 createUser·p0.999:  18.737 ms/op
                 createUser·p0.9999: 21.725 ms/op
                 createUser·p1.00:   24.642 ms/op

Iteration   3: 3.463 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.382 ms/op
                 createUser·p0.50:   3.371 ms/op
                 createUser·p0.90:   3.940 ms/op
                 createUser·p0.95:   4.235 ms/op
                 createUser·p0.99:   5.767 ms/op
                 createUser·p0.999:  17.531 ms/op
                 createUser·p0.9999: 24.576 ms/op
                 createUser·p1.00:   27.001 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 275196
  mean =      3.486 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8558 
    [ 2.500,  5.000) = 260748 
    [ 5.000,  7.500) = 4956 
    [ 7.500, 10.000) = 481 
    [10.000, 12.500) = 134 
    [12.500, 15.000) = 22 
    [15.000, 17.500) = 16 
    [17.500, 20.000) = 154 
    [20.000, 22.500) = 92 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.320 ms/op
     p(50.0000) =      3.387 ms/op
     p(90.0000) =      4.014 ms/op
     p(95.0000) =      4.309 ms/op
     p(99.0000) =      6.046 ms/op
     p(99.9000) =     17.662 ms/op
     p(99.9900) =     22.986 ms/op
     p(99.9990) =     25.190 ms/op
     p(99.9999) =     27.001 ms/op
    p(100.0000) =     27.001 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 8.049 ±(99.9%) 0.114 ms/op
# Warmup Iteration   2: 3.614 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.387 ±(99.9%) 0.009 ms/op
Iteration   1: 3.342 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.589 ms/op
                 existUser·p0.50:   3.236 ms/op
                 existUser·p0.90:   3.736 ms/op
                 existUser·p0.95:   4.047 ms/op
                 existUser·p0.99:   5.587 ms/op
                 existUser·p0.999:  12.796 ms/op
                 existUser·p0.9999: 23.377 ms/op
                 existUser·p1.00:   24.052 ms/op

Iteration   2: 3.347 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.822 ms/op
                 existUser·p0.50:   3.248 ms/op
                 existUser·p0.90:   3.650 ms/op
                 existUser·p0.95:   3.990 ms/op
                 existUser·p0.99:   6.275 ms/op
                 existUser·p0.999:  21.214 ms/op
                 existUser·p0.9999: 31.603 ms/op
                 existUser·p1.00:   33.128 ms/op

Iteration   3: 3.426 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.624 ms/op
                 existUser·p0.50:   3.244 ms/op
                 existUser·p0.90:   3.797 ms/op
                 existUser·p0.95:   4.514 ms/op
                 existUser·p0.99:   6.996 ms/op
                 existUser·p0.999:  21.070 ms/op
                 existUser·p0.9999: 28.366 ms/op
                 existUser·p1.00:   29.098 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 284766
  mean =      3.371 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7287 
    [ 2.500,  5.000) = 269655 
    [ 5.000,  7.500) = 6615 
    [ 7.500, 10.000) = 659 
    [10.000, 12.500) = 150 
    [12.500, 15.000) = 105 
    [15.000, 17.500) = 23 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 63 
    [22.500, 25.000) = 105 
    [25.000, 27.500) = 42 
    [27.500, 30.000) = 14 
    [30.000, 32.500) = 31 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.822 ms/op
     p(50.0000) =      3.244 ms/op
     p(90.0000) =      3.723 ms/op
     p(95.0000) =      4.125 ms/op
     p(99.0000) =      6.406 ms/op
     p(99.9000) =     16.013 ms/op
     p(99.9900) =     30.917 ms/op
     p(99.9990) =     31.895 ms/op
     p(99.9999) =     33.128 ms/op
    p(100.0000) =     33.128 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 9.027 ±(99.9%) 0.108 ms/op
# Warmup Iteration   2: 3.834 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.526 ±(99.9%) 0.010 ms/op
Iteration   1: 3.501 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.501 ms/op
                 getUser·p0.50:   3.375 ms/op
                 getUser·p0.90:   3.916 ms/op
                 getUser·p0.95:   4.276 ms/op
                 getUser·p0.99:   6.570 ms/op
                 getUser·p0.999:  15.598 ms/op
                 getUser·p0.9999: 23.097 ms/op
                 getUser·p1.00:   23.855 ms/op

Iteration   2: 3.552 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.407 ms/op
                 getUser·p0.50:   3.416 ms/op
                 getUser·p0.90:   3.899 ms/op
                 getUser·p0.95:   4.211 ms/op
                 getUser·p0.99:   6.988 ms/op
                 getUser·p0.999:  23.461 ms/op
                 getUser·p0.9999: 26.509 ms/op
                 getUser·p1.00:   27.329 ms/op

Iteration   3: 3.421 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.497 ms/op
                 getUser·p0.50:   3.314 ms/op
                 getUser·p0.90:   3.740 ms/op
                 getUser·p0.95:   3.903 ms/op
                 getUser·p0.99:   6.029 ms/op
                 getUser·p0.999:  21.054 ms/op
                 getUser·p0.9999: 30.048 ms/op
                 getUser·p1.00:   31.687 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 274898
  mean =      3.490 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3797 
    [ 2.500,  5.000) = 263275 
    [ 5.000,  7.500) = 6688 
    [ 7.500, 10.000) = 619 
    [10.000, 12.500) = 206 
    [12.500, 15.000) = 21 
    [15.000, 17.500) = 35 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 81 
    [22.500, 25.000) = 78 
    [25.000, 27.500) = 64 
    [27.500, 30.000) = 20 
    [30.000, 32.500) = 12 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.497 ms/op
     p(50.0000) =      3.367 ms/op
     p(90.0000) =      3.850 ms/op
     p(95.0000) =      4.125 ms/op
     p(99.0000) =      6.742 ms/op
     p(99.9000) =     15.648 ms/op
     p(99.9900) =     28.508 ms/op
     p(99.9990) =     30.991 ms/op
     p(99.9999) =     31.687 ms/op
    p(100.0000) =     31.687 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 10.474 ±(99.9%) 0.139 ms/op
# Warmup Iteration   2: 4.326 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.289 ±(99.9%) 0.014 ms/op
Iteration   1: 4.132 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.573 ms/op
                 listUser·p0.50:   3.961 ms/op
                 listUser·p0.90:   4.579 ms/op
                 listUser·p0.95:   4.841 ms/op
                 listUser·p0.99:   7.264 ms/op
                 listUser·p0.999:  16.574 ms/op
                 listUser·p0.9999: 24.200 ms/op
                 listUser·p1.00:   27.165 ms/op

Iteration   2: 4.079 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.905 ms/op
                 listUser·p0.50:   3.916 ms/op
                 listUser·p0.90:   4.465 ms/op
                 listUser·p0.95:   4.850 ms/op
                 listUser·p0.99:   7.537 ms/op
                 listUser·p0.999:  16.763 ms/op
                 listUser·p0.9999: 21.141 ms/op
                 listUser·p1.00:   28.606 ms/op

Iteration   3: 4.055 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.071 ms/op
                 listUser·p0.50:   3.936 ms/op
                 listUser·p0.90:   4.399 ms/op
                 listUser·p0.95:   4.588 ms/op
                 listUser·p0.99:   7.079 ms/op
                 listUser·p0.999:  15.108 ms/op
                 listUser·p0.9999: 16.681 ms/op
                 listUser·p1.00:   20.382 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 234722
  mean =      4.088 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 52 
    [ 2.500,  5.000) = 226409 
    [ 5.000,  7.500) = 6166 
    [ 7.500, 10.000) = 1276 
    [10.000, 12.500) = 317 
    [12.500, 15.000) = 184 
    [15.000, 17.500) = 187 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 47 
    [22.500, 25.000) = 38 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      1.573 ms/op
     p(50.0000) =      3.936 ms/op
     p(90.0000) =      4.489 ms/op
     p(95.0000) =      4.751 ms/op
     p(99.0000) =      7.250 ms/op
     p(99.9000) =     15.974 ms/op
     p(99.9900) =     23.610 ms/op
     p(99.9990) =     27.421 ms/op
     p(99.9999) =     28.606 ms/op
    p(100.0000) =     28.606 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.288 ± 3.701  ops/ms
ClientPb.existUser                       thrpt       3   9.537 ± 0.700  ops/ms
ClientPb.getUser                         thrpt       3   9.287 ± 0.778  ops/ms
ClientPb.listUser                        thrpt       3   7.741 ± 1.347  ops/ms
ClientPb.createUser                       avgt       3   3.425 ± 0.484   ms/op
ClientPb.existUser                        avgt       3   3.316 ± 0.942   ms/op
ClientPb.getUser                          avgt       3   3.479 ± 0.616   ms/op
ClientPb.listUser                         avgt       3   4.081 ± 0.450   ms/op
ClientPb.createUser                     sample  275196   3.486 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.320           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.387           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.014           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.309           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.046           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.662           ms/op
ClientPb.createUser:createUser·p0.9999  sample          22.986           ms/op
ClientPb.createUser:createUser·p1.00    sample          27.001           ms/op
ClientPb.existUser                      sample  284766   3.371 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.822           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.244           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.723           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.125           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.406           ms/op
ClientPb.existUser:existUser·p0.999     sample          16.013           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.917           ms/op
ClientPb.existUser:existUser·p1.00      sample          33.128           ms/op
ClientPb.getUser                        sample  274898   3.490 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.497           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.367           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.850           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.125           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.742           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.648           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.508           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.687           ms/op
ClientPb.listUser                       sample  234722   4.088 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.573           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.936           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.489           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.751           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.250           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.974           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.610           ms/op
ClientPb.listUser:listUser·p1.00        sample          28.606           ms/op
