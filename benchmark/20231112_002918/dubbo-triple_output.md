# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 5.083 ops/ms
# Warmup Iteration   2: 12.090 ops/ms
# Warmup Iteration   3: 12.508 ops/ms
Iteration   1: 12.809 ops/ms
Iteration   2: 12.665 ops/ms
Iteration   3: 12.778 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.750 ±(99.9%) 1.378 ops/ms [Average]
  (min, avg, max) = (12.665, 12.750, 12.809), stdev = 0.076
  CI (99.9%): [11.373, 14.128] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:53
# Fork: 1 of 1
# Warmup Iteration   1: 7.812 ops/ms
# Warmup Iteration   2: 13.226 ops/ms
# Warmup Iteration   3: 13.003 ops/ms
Iteration   1: 13.136 ops/ms
Iteration   2: 13.213 ops/ms
Iteration   3: 12.916 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.088 ±(99.9%) 2.807 ops/ms [Average]
  (min, avg, max) = (12.916, 13.088, 13.213), stdev = 0.154
  CI (99.9%): [10.281, 15.895] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:48
# Fork: 1 of 1
# Warmup Iteration   1: 7.987 ops/ms
# Warmup Iteration   2: 12.393 ops/ms
# Warmup Iteration   3: 12.782 ops/ms
Iteration   1: 12.716 ops/ms
Iteration   2: 12.883 ops/ms
Iteration   3: 12.726 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.775 ±(99.9%) 1.707 ops/ms [Average]
  (min, avg, max) = (12.716, 12.775, 12.883), stdev = 0.094
  CI (99.9%): [11.068, 14.482] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:43
# Fork: 1 of 1
# Warmup Iteration   1: 6.678 ops/ms
# Warmup Iteration   2: 10.510 ops/ms
# Warmup Iteration   3: 10.716 ops/ms
Iteration   1: 10.513 ops/ms
Iteration   2: 10.781 ops/ms
Iteration   3: 10.761 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.685 ±(99.9%) 2.727 ops/ms [Average]
  (min, avg, max) = (10.513, 10.685, 10.781), stdev = 0.150
  CI (99.9%): [7.958, 13.413] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:38
# Fork: 1 of 1
# Warmup Iteration   1: 3.951 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.553 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.485 ±(99.9%) 0.004 ms/op
Iteration   1: 2.486 ±(99.9%) 0.004 ms/op
Iteration   2: 2.539 ±(99.9%) 0.005 ms/op
Iteration   3: 2.493 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.506 ±(99.9%) 0.525 ms/op [Average]
  (min, avg, max) = (2.486, 2.506, 2.539), stdev = 0.029
  CI (99.9%): [1.982, 3.031] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:33
# Fork: 1 of 1
# Warmup Iteration   1: 3.794 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.477 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.473 ±(99.9%) 0.004 ms/op
Iteration   1: 2.478 ±(99.9%) 0.004 ms/op
Iteration   2: 2.449 ±(99.9%) 0.004 ms/op
Iteration   3: 2.481 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.469 ±(99.9%) 0.324 ms/op [Average]
  (min, avg, max) = (2.449, 2.469, 2.481), stdev = 0.018
  CI (99.9%): [2.145, 2.794] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.948 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.530 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.486 ±(99.9%) 0.004 ms/op
Iteration   1: 2.477 ±(99.9%) 0.004 ms/op
Iteration   2: 2.491 ±(99.9%) 0.004 ms/op
Iteration   3: 2.474 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.480 ±(99.9%) 0.163 ms/op [Average]
  (min, avg, max) = (2.474, 2.480, 2.491), stdev = 0.009
  CI (99.9%): [2.318, 2.643] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 4.763 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.035 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.022 ±(99.9%) 0.007 ms/op
Iteration   1: 2.987 ±(99.9%) 0.005 ms/op
Iteration   2: 2.979 ±(99.9%) 0.005 ms/op
Iteration   3: 2.996 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.987 ±(99.9%) 0.153 ms/op [Average]
  (min, avg, max) = (2.979, 2.987, 2.996), stdev = 0.008
  CI (99.9%): [2.834, 3.140] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:19
# Fork: 1 of 1
# Warmup Iteration   1: 4.068 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.697 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.544 ±(99.9%) 0.006 ms/op
Iteration   1: 2.556 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.037 ms/op
                 createUser·p0.50:   2.626 ms/op
                 createUser·p0.90:   3.105 ms/op
                 createUser·p0.95:   3.236 ms/op
                 createUser·p0.99:   3.994 ms/op
                 createUser·p0.999:  12.072 ms/op
                 createUser·p0.9999: 16.261 ms/op
                 createUser·p1.00:   17.531 ms/op

Iteration   2: 2.540 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.940 ms/op
                 createUser·p0.50:   2.605 ms/op
                 createUser·p0.90:   3.080 ms/op
                 createUser·p0.95:   3.211 ms/op
                 createUser·p0.99:   3.932 ms/op
                 createUser·p0.999:  9.570 ms/op
                 createUser·p0.9999: 13.022 ms/op
                 createUser·p1.00:   14.221 ms/op

Iteration   3: 2.521 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.098 ms/op
                 createUser·p0.50:   2.560 ms/op
                 createUser·p0.90:   3.064 ms/op
                 createUser·p0.95:   3.199 ms/op
                 createUser·p0.99:   3.961 ms/op
                 createUser·p0.999:  8.618 ms/op
                 createUser·p0.9999: 12.075 ms/op
                 createUser·p1.00:   12.239 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 377776
  mean =      2.539 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 41 
    [ 1.250,  2.500) = 180244 
    [ 2.500,  3.750) = 192232 
    [ 3.750,  5.000) = 4143 
    [ 5.000,  6.250) = 575 
    [ 6.250,  7.500) = 104 
    [ 7.500,  8.750) = 68 
    [ 8.750, 10.000) = 73 
    [10.000, 11.250) = 91 
    [11.250, 12.500) = 66 
    [12.500, 13.750) = 97 
    [13.750, 15.000) = 10 
    [15.000, 16.250) = 20 
    [16.250, 17.500) = 11 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.940 ms/op
     p(50.0000) =      2.593 ms/op
     p(90.0000) =      3.084 ms/op
     p(95.0000) =      3.219 ms/op
     p(99.0000) =      3.965 ms/op
     p(99.9000) =      8.700 ms/op
     p(99.9900) =     13.848 ms/op
     p(99.9990) =     17.050 ms/op
     p(99.9999) =     17.531 ms/op
    p(100.0000) =     17.531 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.868 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.479 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.456 ±(99.9%) 0.005 ms/op
Iteration   1: 2.456 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.005 ms/op
                 existUser·p0.50:   2.511 ms/op
                 existUser·p0.90:   2.990 ms/op
                 existUser·p0.95:   3.113 ms/op
                 existUser·p0.99:   3.786 ms/op
                 existUser·p0.999:  7.461 ms/op
                 existUser·p0.9999: 13.959 ms/op
                 existUser·p1.00:   14.369 ms/op

Iteration   2: 2.473 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.925 ms/op
                 existUser·p0.50:   2.556 ms/op
                 existUser·p0.90:   3.006 ms/op
                 existUser·p0.95:   3.138 ms/op
                 existUser·p0.99:   3.871 ms/op
                 existUser·p0.999:  5.995 ms/op
                 existUser·p0.9999: 15.860 ms/op
                 existUser·p1.00:   16.581 ms/op

Iteration   3: 2.455 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.884 ms/op
                 existUser·p0.50:   2.490 ms/op
                 existUser·p0.90:   2.994 ms/op
                 existUser·p0.95:   3.121 ms/op
                 existUser·p0.99:   3.817 ms/op
                 existUser·p0.999:  7.291 ms/op
                 existUser·p0.9999: 13.117 ms/op
                 existUser·p1.00:   13.779 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 389573
  mean =      2.461 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 50 
    [ 1.250,  2.500) = 193048 
    [ 2.500,  3.750) = 192088 
    [ 3.750,  5.000) = 3409 
    [ 5.000,  6.250) = 557 
    [ 6.250,  7.500) = 62 
    [ 7.500,  8.750) = 42 
    [ 8.750, 10.000) = 62 
    [10.000, 11.250) = 42 
    [11.250, 12.500) = 23 
    [12.500, 13.750) = 121 
    [13.750, 15.000) = 37 
    [15.000, 16.250) = 29 
    [16.250, 17.500) = 3 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.884 ms/op
     p(50.0000) =      2.515 ms/op
     p(90.0000) =      2.998 ms/op
     p(95.0000) =      3.121 ms/op
     p(99.0000) =      3.834 ms/op
     p(99.9000) =      6.633 ms/op
     p(99.9900) =     14.191 ms/op
     p(99.9990) =     16.141 ms/op
     p(99.9999) =     16.581 ms/op
    p(100.0000) =     16.581 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.970 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.616 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 2.517 ±(99.9%) 0.006 ms/op
Iteration   1: 2.513 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.037 ms/op
                 getUser·p0.50:   2.515 ms/op
                 getUser·p0.90:   3.064 ms/op
                 getUser·p0.95:   3.195 ms/op
                 getUser·p0.99:   3.932 ms/op
                 getUser·p0.999:  11.842 ms/op
                 getUser·p0.9999: 14.239 ms/op
                 getUser·p1.00:   14.696 ms/op

Iteration   2: 2.539 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.912 ms/op
                 getUser·p0.50:   2.552 ms/op
                 getUser·p0.90:   3.097 ms/op
                 getUser·p0.95:   3.285 ms/op
                 getUser·p0.99:   4.424 ms/op
                 getUser·p0.999:  9.944 ms/op
                 getUser·p0.9999: 13.458 ms/op
                 getUser·p1.00:   14.270 ms/op

Iteration   3: 2.512 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.921 ms/op
                 getUser·p0.50:   2.515 ms/op
                 getUser·p0.90:   3.072 ms/op
                 getUser·p0.95:   3.203 ms/op
                 getUser·p0.99:   3.801 ms/op
                 getUser·p0.999:  8.859 ms/op
                 getUser·p0.9999: 10.715 ms/op
                 getUser·p1.00:   11.731 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 380429
  mean =      2.521 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 73 
    [ 1.250,  2.500) = 187855 
    [ 2.500,  3.750) = 186506 
    [ 3.750,  5.000) = 4903 
    [ 5.000,  6.250) = 632 
    [ 6.250,  7.500) = 61 
    [ 7.500,  8.750) = 15 
    [ 8.750, 10.000) = 94 
    [10.000, 11.250) = 81 
    [11.250, 12.500) = 52 
    [12.500, 13.750) = 120 
    [13.750, 15.000) = 37 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.912 ms/op
     p(50.0000) =      2.527 ms/op
     p(90.0000) =      3.076 ms/op
     p(95.0000) =      3.224 ms/op
     p(99.0000) =      4.108 ms/op
     p(99.9000) =      8.897 ms/op
     p(99.9900) =     13.745 ms/op
     p(99.9990) =     14.585 ms/op
     p(99.9999) =     14.696 ms/op
    p(100.0000) =     14.696 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.588 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.018 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.988 ±(99.9%) 0.008 ms/op
Iteration   1: 3.090 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.816 ms/op
                 listUser·p0.50:   2.966 ms/op
                 listUser·p0.90:   4.178 ms/op
                 listUser·p0.95:   4.940 ms/op
                 listUser·p0.99:   6.201 ms/op
                 listUser·p0.999:  9.381 ms/op
                 listUser·p0.9999: 10.879 ms/op
                 listUser·p1.00:   12.304 ms/op

Iteration   2: 2.998 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.889 ms/op
                 listUser·p0.50:   2.937 ms/op
                 listUser·p0.90:   3.883 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   5.579 ms/op
                 listUser·p0.999:  9.547 ms/op
                 listUser·p0.9999: 12.818 ms/op
                 listUser·p1.00:   13.533 ms/op

Iteration   3: 2.986 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.878 ms/op
                 listUser·p0.50:   2.912 ms/op
                 listUser·p0.90:   3.867 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   5.562 ms/op
                 listUser·p0.999:  10.191 ms/op
                 listUser·p0.9999: 12.696 ms/op
                 listUser·p1.00:   13.795 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 317167
  mean =      3.024 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 106 
    [ 1.250,  2.500) = 93689 
    [ 2.500,  3.750) = 181351 
    [ 3.750,  5.000) = 32236 
    [ 5.000,  6.250) = 7937 
    [ 6.250,  7.500) = 1036 
    [ 7.500,  8.750) = 211 
    [ 8.750, 10.000) = 331 
    [10.000, 11.250) = 139 
    [11.250, 12.500) = 97 
    [12.500, 13.750) = 33 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.816 ms/op
     p(50.0000) =      2.937 ms/op
     p(90.0000) =      3.961 ms/op
     p(95.0000) =      4.530 ms/op
     p(99.0000) =      5.833 ms/op
     p(99.9000) =      9.910 ms/op
     p(99.9900) =     12.576 ms/op
     p(99.9990) =     13.516 ms/op
     p(99.9999) =     13.795 ms/op
    p(100.0000) =     13.795 ms/op


# Run complete. Total time: 00:13:00

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.750 ± 1.378  ops/ms
ClientPb.existUser                       thrpt       3  13.088 ± 2.807  ops/ms
ClientPb.getUser                         thrpt       3  12.775 ± 1.707  ops/ms
ClientPb.listUser                        thrpt       3  10.685 ± 2.727  ops/ms
ClientPb.createUser                       avgt       3   2.506 ± 0.525   ms/op
ClientPb.existUser                        avgt       3   2.469 ± 0.324   ms/op
ClientPb.getUser                          avgt       3   2.480 ± 0.163   ms/op
ClientPb.listUser                         avgt       3   2.987 ± 0.153   ms/op
ClientPb.createUser                     sample  377776   2.539 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.940           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.593           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.084           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.219           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.965           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.700           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.848           ms/op
ClientPb.createUser:createUser·p1.00    sample          17.531           ms/op
ClientPb.existUser                      sample  389573   2.461 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.884           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.515           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.998           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.121           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.834           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.633           ms/op
ClientPb.existUser:existUser·p0.9999    sample          14.191           ms/op
ClientPb.existUser:existUser·p1.00      sample          16.581           ms/op
ClientPb.getUser                        sample  380429   2.521 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.912           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.527           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.076           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.224           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.108           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.897           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.745           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.696           ms/op
ClientPb.listUser                       sample  317167   3.024 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.816           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.937           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.961           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.530           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.833           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.910           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.576           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.795           ms/op
