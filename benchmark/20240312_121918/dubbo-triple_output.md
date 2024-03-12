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
# Warmup Iteration   1: 5.049 ops/ms
# Warmup Iteration   2: 12.420 ops/ms
# Warmup Iteration   3: 12.711 ops/ms
Iteration   1: 12.744 ops/ms
Iteration   2: 12.799 ops/ms
Iteration   3: 12.780 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.774 ±(99.9%) 0.514 ops/ms [Average]
  (min, avg, max) = (12.744, 12.774, 12.799), stdev = 0.028
  CI (99.9%): [12.260, 13.289] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:51
# Fork: 1 of 1
# Warmup Iteration   1: 8.207 ops/ms
# Warmup Iteration   2: 13.268 ops/ms
# Warmup Iteration   3: 13.376 ops/ms
Iteration   1: 13.431 ops/ms
Iteration   2: 13.350 ops/ms
Iteration   3: 13.376 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.386 ±(99.9%) 0.758 ops/ms [Average]
  (min, avg, max) = (13.350, 13.386, 13.431), stdev = 0.042
  CI (99.9%): [12.628, 14.144] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.980 ops/ms
# Warmup Iteration   2: 12.761 ops/ms
# Warmup Iteration   3: 13.069 ops/ms
Iteration   1: 12.977 ops/ms
Iteration   2: 12.967 ops/ms
Iteration   3: 13.077 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.007 ±(99.9%) 1.113 ops/ms [Average]
  (min, avg, max) = (12.967, 13.007, 13.077), stdev = 0.061
  CI (99.9%): [11.894, 14.119] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:44
# Fork: 1 of 1
# Warmup Iteration   1: 6.696 ops/ms
# Warmup Iteration   2: 10.747 ops/ms
# Warmup Iteration   3: 10.773 ops/ms
Iteration   1: 10.637 ops/ms
Iteration   2: 10.774 ops/ms
Iteration   3: 10.798 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.737 ±(99.9%) 1.584 ops/ms [Average]
  (min, avg, max) = (10.637, 10.737, 10.798), stdev = 0.087
  CI (99.9%): [9.152, 12.321] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 3.736 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.537 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.504 ±(99.9%) 0.003 ms/op
Iteration   1: 2.504 ±(99.9%) 0.004 ms/op
Iteration   2: 2.482 ±(99.9%) 0.005 ms/op
Iteration   3: 2.495 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.494 ±(99.9%) 0.200 ms/op [Average]
  (min, avg, max) = (2.482, 2.494, 2.504), stdev = 0.011
  CI (99.9%): [2.294, 2.693] (assumes normal distribution)


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
# Warmup Iteration   1: 3.572 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.398 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.419 ±(99.9%) 0.004 ms/op
Iteration   1: 2.389 ±(99.9%) 0.003 ms/op
Iteration   2: 2.394 ±(99.9%) 0.004 ms/op
Iteration   3: 2.389 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.390 ±(99.9%) 0.059 ms/op [Average]
  (min, avg, max) = (2.389, 2.390, 2.394), stdev = 0.003
  CI (99.9%): [2.331, 2.450] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:29
# Fork: 1 of 1
# Warmup Iteration   1: 3.585 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.465 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.427 ±(99.9%) 0.004 ms/op
Iteration   1: 2.398 ±(99.9%) 0.004 ms/op
Iteration   2: 2.426 ±(99.9%) 0.004 ms/op
Iteration   3: 2.405 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.410 ±(99.9%) 0.266 ms/op [Average]
  (min, avg, max) = (2.398, 2.410, 2.426), stdev = 0.015
  CI (99.9%): [2.144, 2.676] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 4.629 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.996 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.942 ±(99.9%) 0.005 ms/op
Iteration   1: 2.940 ±(99.9%) 0.005 ms/op
Iteration   2: 2.913 ±(99.9%) 0.005 ms/op
Iteration   3: 2.925 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.926 ±(99.9%) 0.247 ms/op [Average]
  (min, avg, max) = (2.913, 2.926, 2.940), stdev = 0.014
  CI (99.9%): [2.679, 3.173] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.954 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.611 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.518 ±(99.9%) 0.005 ms/op
Iteration   1: 2.512 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.927 ms/op
                 createUser·p0.50:   2.585 ms/op
                 createUser·p0.90:   3.043 ms/op
                 createUser·p0.95:   3.162 ms/op
                 createUser·p0.99:   3.760 ms/op
                 createUser·p0.999:  11.076 ms/op
                 createUser·p0.9999: 13.090 ms/op
                 createUser·p1.00:   13.484 ms/op

Iteration   2: 2.502 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.990 ms/op
                 createUser·p0.50:   2.548 ms/op
                 createUser·p0.90:   3.035 ms/op
                 createUser·p0.95:   3.138 ms/op
                 createUser·p0.99:   3.547 ms/op
                 createUser·p0.999:  9.715 ms/op
                 createUser·p0.9999: 12.796 ms/op
                 createUser·p1.00:   13.124 ms/op

Iteration   3: 2.500 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.892 ms/op
                 createUser·p0.50:   2.535 ms/op
                 createUser·p0.90:   3.039 ms/op
                 createUser·p0.95:   3.162 ms/op
                 createUser·p0.99:   3.756 ms/op
                 createUser·p0.999:  8.755 ms/op
                 createUser·p0.9999: 14.860 ms/op
                 createUser·p1.00:   17.334 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 382833
  mean =      2.505 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 66 
    [ 1.250,  2.500) = 187337 
    [ 2.500,  3.750) = 192000 
    [ 3.750,  5.000) = 2729 
    [ 5.000,  6.250) = 236 
    [ 6.250,  7.500) = 28 
    [ 7.500,  8.750) = 54 
    [ 8.750, 10.000) = 86 
    [10.000, 11.250) = 112 
    [11.250, 12.500) = 111 
    [12.500, 13.750) = 57 
    [13.750, 15.000) = 10 
    [15.000, 16.250) = 6 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.892 ms/op
     p(50.0000) =      2.556 ms/op
     p(90.0000) =      3.039 ms/op
     p(95.0000) =      3.154 ms/op
     p(99.0000) =      3.695 ms/op
     p(99.9000) =      8.785 ms/op
     p(99.9900) =     12.983 ms/op
     p(99.9990) =     15.813 ms/op
     p(99.9999) =     17.334 ms/op
    p(100.0000) =     17.334 ms/op


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
# Warmup Iteration   1: 3.656 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 2.433 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.391 ±(99.9%) 0.005 ms/op
Iteration   1: 2.383 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.972 ms/op
                 existUser·p0.50:   2.441 ms/op
                 existUser·p0.90:   2.892 ms/op
                 existUser·p0.95:   3.002 ms/op
                 existUser·p0.99:   3.564 ms/op
                 existUser·p0.999:  7.074 ms/op
                 existUser·p0.9999: 13.356 ms/op
                 existUser·p1.00:   13.746 ms/op

Iteration   2: 2.393 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.094 ms/op
                 existUser·p0.50:   2.470 ms/op
                 existUser·p0.90:   2.900 ms/op
                 existUser·p0.95:   3.002 ms/op
                 existUser·p0.99:   3.432 ms/op
                 existUser·p0.999:  6.987 ms/op
                 existUser·p0.9999: 12.714 ms/op
                 existUser·p1.00:   13.140 ms/op

Iteration   3: 2.392 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.839 ms/op
                 existUser·p0.50:   2.486 ms/op
                 existUser·p0.90:   2.900 ms/op
                 existUser·p0.95:   3.002 ms/op
                 existUser·p0.99:   3.584 ms/op
                 existUser·p0.999:  8.185 ms/op
                 existUser·p0.9999: 10.674 ms/op
                 existUser·p1.00:   10.994 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 401366
  mean =      2.389 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 34 
    [ 1.250,  2.500) = 204909 
    [ 2.500,  3.750) = 193631 
    [ 3.750,  5.000) = 2056 
    [ 5.000,  6.250) = 298 
    [ 6.250,  7.500) = 41 
    [ 7.500,  8.750) = 43 
    [ 8.750, 10.000) = 87 
    [10.000, 11.250) = 97 
    [11.250, 12.500) = 95 
    [12.500, 13.750) = 75 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.839 ms/op
     p(50.0000) =      2.466 ms/op
     p(90.0000) =      2.896 ms/op
     p(95.0000) =      3.002 ms/op
     p(99.0000) =      3.532 ms/op
     p(99.9000) =      7.149 ms/op
     p(99.9900) =     12.869 ms/op
     p(99.9990) =     13.468 ms/op
     p(99.9999) =     13.746 ms/op
    p(100.0000) =     13.746 ms/op


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
# Warmup Iteration   1: 3.734 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.521 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.479 ±(99.9%) 0.006 ms/op
Iteration   1: 2.445 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.757 ms/op
                 getUser·p0.50:   2.458 ms/op
                 getUser·p0.90:   2.970 ms/op
                 getUser·p0.95:   3.080 ms/op
                 getUser·p0.99:   3.641 ms/op
                 getUser·p0.999:  6.331 ms/op
                 getUser·p0.9999: 14.008 ms/op
                 getUser·p1.00:   14.238 ms/op

Iteration   2: 2.489 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.971 ms/op
                 getUser·p0.50:   2.503 ms/op
                 getUser·p0.90:   3.035 ms/op
                 getUser·p0.95:   3.228 ms/op
                 getUser·p0.99:   4.580 ms/op
                 getUser·p0.999:  6.645 ms/op
                 getUser·p0.9999: 12.143 ms/op
                 getUser·p1.00:   13.091 ms/op

Iteration   3: 2.496 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.706 ms/op
                 getUser·p0.50:   2.499 ms/op
                 getUser·p0.90:   3.043 ms/op
                 getUser·p0.95:   3.236 ms/op
                 getUser·p0.99:   4.407 ms/op
                 getUser·p0.999:  9.108 ms/op
                 getUser·p0.9999: 12.648 ms/op
                 getUser·p1.00:   13.451 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 387254
  mean =      2.476 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 106 
    [ 1.250,  2.500) = 194979 
    [ 2.500,  3.750) = 185766 
    [ 3.750,  5.000) = 5145 
    [ 5.000,  6.250) = 828 
    [ 6.250,  7.500) = 68 
    [ 7.500,  8.750) = 9 
    [ 8.750, 10.000) = 59 
    [10.000, 11.250) = 55 
    [11.250, 12.500) = 119 
    [12.500, 13.750) = 99 
    [13.750, 15.000) = 21 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.706 ms/op
     p(50.0000) =      2.486 ms/op
     p(90.0000) =      3.015 ms/op
     p(95.0000) =      3.174 ms/op
     p(99.0000) =      4.202 ms/op
     p(99.9000) =      6.629 ms/op
     p(99.9900) =     13.357 ms/op
     p(99.9990) =     14.127 ms/op
     p(99.9999) =     14.238 ms/op
    p(100.0000) =     14.238 ms/op


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
# Warmup Iteration   1: 4.600 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.023 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.004 ±(99.9%) 0.008 ms/op
Iteration   1: 3.000 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.748 ms/op
                 listUser·p0.50:   2.933 ms/op
                 listUser·p0.90:   3.895 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   5.677 ms/op
                 listUser·p0.999:  9.699 ms/op
                 listUser·p0.9999: 11.731 ms/op
                 listUser·p1.00:   12.075 ms/op

Iteration   2: 2.970 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.944 ms/op
                 listUser·p0.50:   2.912 ms/op
                 listUser·p0.90:   3.813 ms/op
                 listUser·p0.95:   4.284 ms/op
                 listUser·p0.99:   5.554 ms/op
                 listUser·p0.999:  8.897 ms/op
                 listUser·p0.9999: 10.244 ms/op
                 listUser·p1.00:   10.551 ms/op

Iteration   3: 2.972 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.946 ms/op
                 listUser·p0.50:   2.904 ms/op
                 listUser·p0.90:   3.846 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   5.743 ms/op
                 listUser·p0.999:  9.372 ms/op
                 listUser·p0.9999: 11.223 ms/op
                 listUser·p1.00:   12.534 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 321789
  mean =      2.981 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 133 
    [ 1.250,  2.500) = 98236 
    [ 2.500,  3.750) = 186099 
    [ 3.750,  5.000) = 29857 
    [ 5.000,  6.250) = 6009 
    [ 6.250,  7.500) = 715 
    [ 7.500,  8.750) = 270 
    [ 8.750, 10.000) = 330 
    [10.000, 11.250) = 107 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.748 ms/op
     p(50.0000) =      2.916 ms/op
     p(90.0000) =      3.850 ms/op
     p(95.0000) =      4.350 ms/op
     p(99.0000) =      5.652 ms/op
     p(99.9000) =      9.290 ms/op
     p(99.9900) =     11.545 ms/op
     p(99.9990) =     12.071 ms/op
     p(99.9999) =     12.534 ms/op
    p(100.0000) =     12.534 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.774 ± 0.514  ops/ms
ClientPb.existUser                       thrpt       3  13.386 ± 0.758  ops/ms
ClientPb.getUser                         thrpt       3  13.007 ± 1.113  ops/ms
ClientPb.listUser                        thrpt       3  10.737 ± 1.584  ops/ms
ClientPb.createUser                       avgt       3   2.494 ± 0.200   ms/op
ClientPb.existUser                        avgt       3   2.390 ± 0.059   ms/op
ClientPb.getUser                          avgt       3   2.410 ± 0.266   ms/op
ClientPb.listUser                         avgt       3   2.926 ± 0.247   ms/op
ClientPb.createUser                     sample  382833   2.505 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.892           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.556           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.039           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.154           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.695           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.785           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.983           ms/op
ClientPb.createUser:createUser·p1.00    sample          17.334           ms/op
ClientPb.existUser                      sample  401366   2.389 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.839           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.466           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.896           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.002           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.532           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.149           ms/op
ClientPb.existUser:existUser·p0.9999    sample          12.869           ms/op
ClientPb.existUser:existUser·p1.00      sample          13.746           ms/op
ClientPb.getUser                        sample  387254   2.476 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.706           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.486           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.015           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.174           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.202           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.629           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.357           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.238           ms/op
ClientPb.listUser                       sample  321789   2.981 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.748           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.916           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.850           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.350           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.652           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.290           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.545           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.534           ms/op
