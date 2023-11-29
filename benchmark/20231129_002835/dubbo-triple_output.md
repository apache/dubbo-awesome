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
# Warmup Iteration   1: 4.559 ops/ms
# Warmup Iteration   2: 11.714 ops/ms
# Warmup Iteration   3: 11.976 ops/ms
Iteration   1: 12.152 ops/ms
Iteration   2: 12.288 ops/ms
Iteration   3: 12.476 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.305 ±(99.9%) 2.965 ops/ms [Average]
  (min, avg, max) = (12.152, 12.305, 12.476), stdev = 0.162
  CI (99.9%): [9.341, 15.270] (assumes normal distribution)


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
# Warmup Iteration   1: 7.293 ops/ms
# Warmup Iteration   2: 12.535 ops/ms
# Warmup Iteration   3: 12.624 ops/ms
Iteration   1: 12.669 ops/ms
Iteration   2: 12.719 ops/ms
Iteration   3: 12.724 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.704 ±(99.9%) 0.555 ops/ms [Average]
  (min, avg, max) = (12.669, 12.704, 12.724), stdev = 0.030
  CI (99.9%): [12.149, 13.259] (assumes normal distribution)


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
# Warmup Iteration   1: 7.497 ops/ms
# Warmup Iteration   2: 12.346 ops/ms
# Warmup Iteration   3: 12.503 ops/ms
Iteration   1: 12.586 ops/ms
Iteration   2: 12.566 ops/ms
Iteration   3: 12.740 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.631 ±(99.9%) 1.738 ops/ms [Average]
  (min, avg, max) = (12.566, 12.631, 12.740), stdev = 0.095
  CI (99.9%): [10.893, 14.369] (assumes normal distribution)


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
# Warmup Iteration   1: 6.408 ops/ms
# Warmup Iteration   2: 10.309 ops/ms
# Warmup Iteration   3: 10.444 ops/ms
Iteration   1: 10.380 ops/ms
Iteration   2: 10.443 ops/ms
Iteration   3: 10.514 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.446 ±(99.9%) 1.219 ops/ms [Average]
  (min, avg, max) = (10.380, 10.446, 10.514), stdev = 0.067
  CI (99.9%): [9.227, 11.665] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 4.045 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 2.648 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.603 ±(99.9%) 0.004 ms/op
Iteration   1: 2.612 ±(99.9%) 0.005 ms/op
Iteration   2: 2.656 ±(99.9%) 0.004 ms/op
Iteration   3: 2.551 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.606 ±(99.9%) 0.961 ms/op [Average]
  (min, avg, max) = (2.551, 2.606, 2.656), stdev = 0.053
  CI (99.9%): [1.646, 3.567] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.812 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.510 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.516 ±(99.9%) 0.004 ms/op
Iteration   1: 2.483 ±(99.9%) 0.003 ms/op
Iteration   2: 2.481 ±(99.9%) 0.003 ms/op
Iteration   3: 2.502 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.489 ±(99.9%) 0.211 ms/op [Average]
  (min, avg, max) = (2.481, 2.489, 2.502), stdev = 0.012
  CI (99.9%): [2.277, 2.700] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.941 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.508 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.480 ±(99.9%) 0.004 ms/op
Iteration   1: 2.447 ±(99.9%) 0.004 ms/op
Iteration   2: 2.457 ±(99.9%) 0.003 ms/op
Iteration   3: 2.441 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.448 ±(99.9%) 0.143 ms/op [Average]
  (min, avg, max) = (2.441, 2.448, 2.457), stdev = 0.008
  CI (99.9%): [2.305, 2.592] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.779 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.101 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.056 ±(99.9%) 0.004 ms/op
Iteration   1: 3.032 ±(99.9%) 0.006 ms/op
Iteration   2: 3.034 ±(99.9%) 0.006 ms/op
Iteration   3: 3.055 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.041 ±(99.9%) 0.232 ms/op [Average]
  (min, avg, max) = (3.032, 3.041, 3.055), stdev = 0.013
  CI (99.9%): [2.809, 3.272] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.165 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.690 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.537 ±(99.9%) 0.006 ms/op
Iteration   1: 2.533 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.841 ms/op
                 createUser·p0.50:   2.576 ms/op
                 createUser·p0.90:   3.080 ms/op
                 createUser·p0.95:   3.207 ms/op
                 createUser·p0.99:   3.793 ms/op
                 createUser·p0.999:  11.403 ms/op
                 createUser·p0.9999: 13.763 ms/op
                 createUser·p1.00:   14.320 ms/op

Iteration   2: 2.509 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.937 ms/op
                 createUser·p0.50:   2.589 ms/op
                 createUser·p0.90:   3.047 ms/op
                 createUser·p0.95:   3.154 ms/op
                 createUser·p0.99:   3.666 ms/op
                 createUser·p0.999:  9.686 ms/op
                 createUser·p0.9999: 11.862 ms/op
                 createUser·p1.00:   12.534 ms/op

Iteration   3: 2.519 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.817 ms/op
                 createUser·p0.50:   2.572 ms/op
                 createUser·p0.90:   3.060 ms/op
                 createUser·p0.95:   3.187 ms/op
                 createUser·p0.99:   3.846 ms/op
                 createUser·p0.999:  8.784 ms/op
                 createUser·p0.9999: 10.807 ms/op
                 createUser·p1.00:   13.451 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 380495
  mean =      2.521 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 51 
    [ 1.250,  2.500) = 183656 
    [ 2.500,  3.750) = 192806 
    [ 3.750,  5.000) = 3139 
    [ 5.000,  6.250) = 294 
    [ 6.250,  7.500) = 155 
    [ 7.500,  8.750) = 11 
    [ 8.750, 10.000) = 78 
    [10.000, 11.250) = 131 
    [11.250, 12.500) = 79 
    [12.500, 13.750) = 82 
    [13.750, 15.000) = 13 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.817 ms/op
     p(50.0000) =      2.580 ms/op
     p(90.0000) =      3.060 ms/op
     p(95.0000) =      3.183 ms/op
     p(99.0000) =      3.772 ms/op
     p(99.9000) =      8.839 ms/op
     p(99.9900) =     13.369 ms/op
     p(99.9990) =     13.897 ms/op
     p(99.9999) =     14.320 ms/op
    p(100.0000) =     14.320 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.693 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.484 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.457 ±(99.9%) 0.005 ms/op
Iteration   1: 2.440 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.519 ms/op
                 existUser·p0.50:   2.494 ms/op
                 existUser·p0.90:   2.957 ms/op
                 existUser·p0.95:   3.072 ms/op
                 existUser·p0.99:   3.670 ms/op
                 existUser·p0.999:  5.635 ms/op
                 existUser·p0.9999: 14.056 ms/op
                 existUser·p1.00:   14.418 ms/op

Iteration   2: 2.459 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.949 ms/op
                 existUser·p0.50:   2.511 ms/op
                 existUser·p0.90:   2.982 ms/op
                 existUser·p0.95:   3.084 ms/op
                 existUser·p0.99:   3.731 ms/op
                 existUser·p0.999:  7.348 ms/op
                 existUser·p0.9999: 13.877 ms/op
                 existUser·p1.00:   15.106 ms/op

Iteration   3: 2.475 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.923 ms/op
                 existUser·p0.50:   2.503 ms/op
                 existUser·p0.90:   3.002 ms/op
                 existUser·p0.95:   3.150 ms/op
                 existUser·p0.99:   4.301 ms/op
                 existUser·p0.999:  9.126 ms/op
                 existUser·p0.9999: 12.142 ms/op
                 existUser·p1.00:   12.370 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 390151
  mean =      2.458 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 59 
    [ 1.250,  2.500) = 194886 
    [ 2.500,  3.750) = 190620 
    [ 3.750,  5.000) = 3346 
    [ 5.000,  6.250) = 728 
    [ 6.250,  7.500) = 119 
    [ 7.500,  8.750) = 15 
    [ 8.750, 10.000) = 119 
    [10.000, 11.250) = 81 
    [11.250, 12.500) = 69 
    [12.500, 13.750) = 74 
    [13.750, 15.000) = 34 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.519 ms/op
     p(50.0000) =      2.503 ms/op
     p(90.0000) =      2.982 ms/op
     p(95.0000) =      3.101 ms/op
     p(99.0000) =      3.887 ms/op
     p(99.9000) =      8.129 ms/op
     p(99.9900) =     13.615 ms/op
     p(99.9990) =     14.403 ms/op
     p(99.9999) =     15.106 ms/op
    p(100.0000) =     15.106 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.897 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.588 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.492 ±(99.9%) 0.006 ms/op
Iteration   1: 2.476 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.834 ms/op
                 getUser·p0.50:   2.515 ms/op
                 getUser·p0.90:   3.006 ms/op
                 getUser·p0.95:   3.117 ms/op
                 getUser·p0.99:   3.719 ms/op
                 getUser·p0.999:  12.547 ms/op
                 getUser·p0.9999: 14.117 ms/op
                 getUser·p1.00:   14.762 ms/op

Iteration   2: 2.512 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.009 ms/op
                 getUser·p0.50:   2.531 ms/op
                 getUser·p0.90:   3.056 ms/op
                 getUser·p0.95:   3.252 ms/op
                 getUser·p0.99:   4.440 ms/op
                 getUser·p0.999:  10.055 ms/op
                 getUser·p0.9999: 15.820 ms/op
                 getUser·p1.00:   16.646 ms/op

Iteration   3: 2.498 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.962 ms/op
                 getUser·p0.50:   2.540 ms/op
                 getUser·p0.90:   3.039 ms/op
                 getUser·p0.95:   3.191 ms/op
                 getUser·p0.99:   4.133 ms/op
                 getUser·p0.999:  6.046 ms/op
                 getUser·p0.9999: 12.426 ms/op
                 getUser·p1.00:   12.698 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 384327
  mean =      2.496 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 78 
    [ 1.250,  2.500) = 189414 
    [ 2.500,  3.750) = 188764 
    [ 3.750,  5.000) = 4635 
    [ 5.000,  6.250) = 978 
    [ 6.250,  7.500) = 71 
    [ 7.500,  8.750) = 32 
    [ 8.750, 10.000) = 36 
    [10.000, 11.250) = 52 
    [11.250, 12.500) = 60 
    [12.500, 13.750) = 132 
    [13.750, 15.000) = 49 
    [15.000, 16.250) = 16 
    [16.250, 17.500) = 10 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.834 ms/op
     p(50.0000) =      2.527 ms/op
     p(90.0000) =      3.031 ms/op
     p(95.0000) =      3.178 ms/op
     p(99.0000) =      4.080 ms/op
     p(99.9000) =      7.791 ms/op
     p(99.9900) =     14.631 ms/op
     p(99.9990) =     16.504 ms/op
     p(99.9999) =     16.646 ms/op
    p(100.0000) =     16.646 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.785 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.127 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.083 ±(99.9%) 0.009 ms/op
Iteration   1: 3.082 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.880 ms/op
                 listUser·p0.50:   3.015 ms/op
                 listUser·p0.90:   4.043 ms/op
                 listUser·p0.95:   4.555 ms/op
                 listUser·p0.99:   5.767 ms/op
                 listUser·p0.999:  9.060 ms/op
                 listUser·p0.9999: 10.064 ms/op
                 listUser·p1.00:   11.076 ms/op

Iteration   2: 3.084 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.928 ms/op
                 listUser·p0.50:   3.011 ms/op
                 listUser·p0.90:   3.994 ms/op
                 listUser·p0.95:   4.538 ms/op
                 listUser·p0.99:   5.857 ms/op
                 listUser·p0.999:  10.311 ms/op
                 listUser·p0.9999: 12.185 ms/op
                 listUser·p1.00:   14.664 ms/op

Iteration   3: 3.068 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.049 ms/op
                 listUser·p0.50:   2.998 ms/op
                 listUser·p0.90:   3.977 ms/op
                 listUser·p0.95:   4.522 ms/op
                 listUser·p0.99:   5.890 ms/op
                 listUser·p0.999:  9.716 ms/op
                 listUser·p0.9999: 13.824 ms/op
                 listUser·p1.00:   14.336 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 311694
  mean =      3.078 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 109 
    [ 1.250,  2.500) = 82225 
    [ 2.500,  3.750) = 185155 
    [ 3.750,  5.000) = 35209 
    [ 5.000,  6.250) = 7275 
    [ 6.250,  7.500) = 1014 
    [ 7.500,  8.750) = 197 
    [ 8.750, 10.000) = 284 
    [10.000, 11.250) = 164 
    [11.250, 12.500) = 36 
    [12.500, 13.750) = 11 
    [13.750, 15.000) = 15 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.880 ms/op
     p(50.0000) =      3.006 ms/op
     p(90.0000) =      4.006 ms/op
     p(95.0000) =      4.538 ms/op
     p(99.0000) =      5.833 ms/op
     p(99.9000) =      9.601 ms/op
     p(99.9900) =     11.892 ms/op
     p(99.9990) =     14.154 ms/op
     p(99.9999) =     14.664 ms/op
    p(100.0000) =     14.664 ms/op


# Run complete. Total time: 00:13:01

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.305 ± 2.965  ops/ms
ClientPb.existUser                       thrpt       3  12.704 ± 0.555  ops/ms
ClientPb.getUser                         thrpt       3  12.631 ± 1.738  ops/ms
ClientPb.listUser                        thrpt       3  10.446 ± 1.219  ops/ms
ClientPb.createUser                       avgt       3   2.606 ± 0.961   ms/op
ClientPb.existUser                        avgt       3   2.489 ± 0.211   ms/op
ClientPb.getUser                          avgt       3   2.448 ± 0.143   ms/op
ClientPb.listUser                         avgt       3   3.041 ± 0.232   ms/op
ClientPb.createUser                     sample  380495   2.521 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.817           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.580           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.060           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.183           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.772           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.839           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.369           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.320           ms/op
ClientPb.existUser                      sample  390151   2.458 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.519           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.503           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.982           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.101           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.887           ms/op
ClientPb.existUser:existUser·p0.999     sample           8.129           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.615           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.106           ms/op
ClientPb.getUser                        sample  384327   2.496 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.834           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.527           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.031           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.178           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.080           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.791           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.631           ms/op
ClientPb.getUser:getUser·p1.00          sample          16.646           ms/op
ClientPb.listUser                       sample  311694   3.078 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.880           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.006           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.006           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.538           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.833           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.601           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.892           ms/op
ClientPb.listUser:listUser·p1.00        sample          14.664           ms/op
