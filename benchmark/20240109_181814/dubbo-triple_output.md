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
# Warmup Iteration   1: 4.897 ops/ms
# Warmup Iteration   2: 11.976 ops/ms
# Warmup Iteration   3: 12.283 ops/ms
Iteration   1: 12.407 ops/ms
Iteration   2: 12.541 ops/ms
Iteration   3: 12.621 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.523 ±(99.9%) 1.967 ops/ms [Average]
  (min, avg, max) = (12.407, 12.523, 12.621), stdev = 0.108
  CI (99.9%): [10.556, 14.490] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.827 ops/ms
# Warmup Iteration   2: 13.041 ops/ms
# Warmup Iteration   3: 13.059 ops/ms
Iteration   1: 13.126 ops/ms
Iteration   2: 13.109 ops/ms
Iteration   3: 13.108 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.114 ±(99.9%) 0.179 ops/ms [Average]
  (min, avg, max) = (13.108, 13.114, 13.126), stdev = 0.010
  CI (99.9%): [12.936, 13.293] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:47
# Fork: 1 of 1
# Warmup Iteration   1: 6.958 ops/ms
# Warmup Iteration   2: 12.538 ops/ms
# Warmup Iteration   3: 12.637 ops/ms
Iteration   1: 12.790 ops/ms
Iteration   2: 12.844 ops/ms
Iteration   3: 12.651 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.762 ±(99.9%) 1.820 ops/ms [Average]
  (min, avg, max) = (12.651, 12.762, 12.844), stdev = 0.100
  CI (99.9%): [10.942, 14.582] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.081 ops/ms
# Warmup Iteration   2: 10.422 ops/ms
# Warmup Iteration   3: 10.406 ops/ms
Iteration   1: 10.584 ops/ms
Iteration   2: 10.605 ops/ms
Iteration   3: 10.503 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.564 ±(99.9%) 0.986 ops/ms [Average]
  (min, avg, max) = (10.503, 10.564, 10.605), stdev = 0.054
  CI (99.9%): [9.578, 11.550] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.172 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.557 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.528 ±(99.9%) 0.004 ms/op
Iteration   1: 2.584 ±(99.9%) 0.003 ms/op
Iteration   2: 2.539 ±(99.9%) 0.004 ms/op
Iteration   3: 2.528 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.550 ±(99.9%) 0.546 ms/op [Average]
  (min, avg, max) = (2.528, 2.550, 2.584), stdev = 0.030
  CI (99.9%): [2.004, 3.096] (assumes normal distribution)


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
# Warmup Iteration   1: 3.819 ±(99.9%) 0.008 ms/op
# Warmup Iteration   2: 2.479 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.453 ±(99.9%) 0.004 ms/op
Iteration   1: 2.465 ±(99.9%) 0.004 ms/op
Iteration   2: 2.497 ±(99.9%) 0.004 ms/op
Iteration   3: 2.470 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.478 ±(99.9%) 0.317 ms/op [Average]
  (min, avg, max) = (2.465, 2.478, 2.497), stdev = 0.017
  CI (99.9%): [2.160, 2.795] (assumes normal distribution)


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
# Warmup Iteration   1: 3.970 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.571 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.532 ±(99.9%) 0.005 ms/op
Iteration   1: 2.494 ±(99.9%) 0.003 ms/op
Iteration   2: 2.551 ±(99.9%) 0.005 ms/op
Iteration   3: 2.501 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.515 ±(99.9%) 0.562 ms/op [Average]
  (min, avg, max) = (2.494, 2.515, 2.551), stdev = 0.031
  CI (99.9%): [1.953, 3.077] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:23
# Fork: 1 of 1
# Warmup Iteration   1: 4.697 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.076 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.010 ±(99.9%) 0.006 ms/op
Iteration   1: 3.051 ±(99.9%) 0.005 ms/op
Iteration   2: 2.987 ±(99.9%) 0.006 ms/op
Iteration   3: 2.972 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.003 ±(99.9%) 0.772 ms/op [Average]
  (min, avg, max) = (2.972, 3.003, 3.051), stdev = 0.042
  CI (99.9%): [2.231, 3.775] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:18
# Fork: 1 of 1
# Warmup Iteration   1: 4.158 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 2.695 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.604 ±(99.9%) 0.006 ms/op
Iteration   1: 2.599 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.980 ms/op
                 createUser·p0.50:   2.642 ms/op
                 createUser·p0.90:   3.174 ms/op
                 createUser·p0.95:   3.301 ms/op
                 createUser·p0.99:   3.826 ms/op
                 createUser·p0.999:  11.420 ms/op
                 createUser·p0.9999: 13.945 ms/op
                 createUser·p1.00:   14.549 ms/op

Iteration   2: 2.571 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.954 ms/op
                 createUser·p0.50:   2.671 ms/op
                 createUser·p0.90:   3.117 ms/op
                 createUser·p0.95:   3.215 ms/op
                 createUser·p0.99:   3.779 ms/op
                 createUser·p0.999:  9.579 ms/op
                 createUser·p0.9999: 12.838 ms/op
                 createUser·p1.00:   13.206 ms/op

Iteration   3: 2.601 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.028 ms/op
                 createUser·p0.50:   2.613 ms/op
                 createUser·p0.90:   3.170 ms/op
                 createUser·p0.95:   3.305 ms/op
                 createUser·p0.99:   3.933 ms/op
                 createUser·p0.999:  9.585 ms/op
                 createUser·p0.9999: 14.823 ms/op
                 createUser·p1.00:   16.777 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 370194
  mean =      2.590 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 54 
    [ 1.250,  2.500) = 175507 
    [ 2.500,  3.750) = 190203 
    [ 3.750,  5.000) = 3625 
    [ 5.000,  6.250) = 280 
    [ 6.250,  7.500) = 32 
    [ 7.500,  8.750) = 44 
    [ 8.750, 10.000) = 122 
    [10.000, 11.250) = 100 
    [11.250, 12.500) = 117 
    [12.500, 13.750) = 68 
    [13.750, 15.000) = 34 
    [15.000, 16.250) = 6 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.954 ms/op
     p(50.0000) =      2.638 ms/op
     p(90.0000) =      3.150 ms/op
     p(95.0000) =      3.277 ms/op
     p(99.0000) =      3.846 ms/op
     p(99.9000) =      9.601 ms/op
     p(99.9900) =     13.860 ms/op
     p(99.9990) =     15.270 ms/op
     p(99.9999) =     16.777 ms/op
    p(100.0000) =     16.777 ms/op


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
# Warmup Iteration   1: 3.818 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.552 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.484 ±(99.9%) 0.005 ms/op
Iteration   1: 2.474 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.859 ms/op
                 existUser·p0.50:   2.470 ms/op
                 existUser·p0.90:   3.023 ms/op
                 existUser·p0.95:   3.138 ms/op
                 existUser·p0.99:   3.604 ms/op
                 existUser·p0.999:  4.962 ms/op
                 existUser·p0.9999: 18.350 ms/op
                 existUser·p1.00:   19.202 ms/op

Iteration   2: 2.476 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.973 ms/op
                 existUser·p0.50:   2.589 ms/op
                 existUser·p0.90:   2.998 ms/op
                 existUser·p0.95:   3.092 ms/op
                 existUser·p0.99:   3.539 ms/op
                 existUser·p0.999:  5.845 ms/op
                 existUser·p0.9999: 13.932 ms/op
                 existUser·p1.00:   14.139 ms/op

Iteration   3: 2.490 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.106 ms/op
                 existUser·p0.50:   2.523 ms/op
                 existUser·p0.90:   3.027 ms/op
                 existUser·p0.95:   3.133 ms/op
                 existUser·p0.99:   3.674 ms/op
                 existUser·p0.999:  9.332 ms/op
                 existUser·p0.9999: 12.517 ms/op
                 existUser·p1.00:   12.845 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 386887
  mean =      2.480 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 47 
    [ 1.250,  2.500) = 191891 
    [ 2.500,  3.750) = 191969 
    [ 3.750,  5.000) = 2328 
    [ 5.000,  6.250) = 277 
    [ 6.250,  7.500) = 51 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 34 
    [10.000, 11.250) = 96 
    [11.250, 12.500) = 36 
    [12.500, 13.750) = 92 
    [13.750, 15.000) = 33 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 27 

  Percentiles, ms/op:
      p(0.0000) =      0.859 ms/op
     p(50.0000) =      2.519 ms/op
     p(90.0000) =      3.015 ms/op
     p(95.0000) =      3.121 ms/op
     p(99.0000) =      3.601 ms/op
     p(99.9000) =      6.129 ms/op
     p(99.9900) =     14.226 ms/op
     p(99.9990) =     19.005 ms/op
     p(99.9999) =     19.202 ms/op
    p(100.0000) =     19.202 ms/op


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
# Warmup Iteration   1: 4.043 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.585 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.446 ±(99.9%) 0.005 ms/op
Iteration   1: 2.496 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.923 ms/op
                 getUser·p0.50:   2.490 ms/op
                 getUser·p0.90:   3.052 ms/op
                 getUser·p0.95:   3.203 ms/op
                 getUser·p0.99:   4.059 ms/op
                 getUser·p0.999:  5.832 ms/op
                 getUser·p0.9999: 18.186 ms/op
                 getUser·p1.00:   18.940 ms/op

Iteration   2: 2.483 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.641 ms/op
                 getUser·p0.50:   2.404 ms/op
                 getUser·p0.90:   3.080 ms/op
                 getUser·p0.95:   3.310 ms/op
                 getUser·p0.99:   4.424 ms/op
                 getUser·p0.999:  9.072 ms/op
                 getUser·p0.9999: 15.196 ms/op
                 getUser·p1.00:   16.695 ms/op

Iteration   3: 2.467 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.429 ms/op
                 getUser·p0.50:   2.413 ms/op
                 getUser·p0.90:   3.035 ms/op
                 getUser·p0.95:   3.178 ms/op
                 getUser·p0.99:   3.813 ms/op
                 getUser·p0.999:  8.171 ms/op
                 getUser·p0.9999: 11.338 ms/op
                 getUser·p1.00:   12.501 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 386464
  mean =      2.482 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 160 
    [ 1.250,  2.500) = 203701 
    [ 2.500,  3.750) = 176199 
    [ 3.750,  5.000) = 5041 
    [ 5.000,  6.250) = 843 
    [ 6.250,  7.500) = 123 
    [ 7.500,  8.750) = 47 
    [ 8.750, 10.000) = 47 
    [10.000, 11.250) = 120 
    [11.250, 12.500) = 23 
    [12.500, 13.750) = 48 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 14 
    [16.250, 17.500) = 26 
    [17.500, 18.750) = 34 

  Percentiles, ms/op:
      p(0.0000) =      0.429 ms/op
     p(50.0000) =      2.429 ms/op
     p(90.0000) =      3.056 ms/op
     p(95.0000) =      3.224 ms/op
     p(99.0000) =      4.080 ms/op
     p(99.9000) =      7.599 ms/op
     p(99.9900) =     17.727 ms/op
     p(99.9990) =     18.874 ms/op
     p(99.9999) =     18.940 ms/op
    p(100.0000) =     18.940 ms/op


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
# Warmup Iteration   1: 4.824 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 3.076 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.026 ±(99.9%) 0.008 ms/op
Iteration   1: 3.056 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.852 ms/op
                 listUser·p0.50:   2.990 ms/op
                 listUser·p0.90:   3.949 ms/op
                 listUser·p0.95:   4.506 ms/op
                 listUser·p0.99:   5.792 ms/op
                 listUser·p0.999:  9.674 ms/op
                 listUser·p0.9999: 12.479 ms/op
                 listUser·p1.00:   13.337 ms/op

Iteration   2: 3.018 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.787 ms/op
                 listUser·p0.50:   2.957 ms/op
                 listUser·p0.90:   3.895 ms/op
                 listUser·p0.95:   4.424 ms/op
                 listUser·p0.99:   5.577 ms/op
                 listUser·p0.999:  9.667 ms/op
                 listUser·p0.9999: 10.787 ms/op
                 listUser·p1.00:   12.337 ms/op

Iteration   3: 3.008 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.757 ms/op
                 listUser·p0.50:   2.957 ms/op
                 listUser·p0.90:   3.846 ms/op
                 listUser·p0.95:   4.293 ms/op
                 listUser·p0.99:   5.472 ms/op
                 listUser·p0.999:  9.531 ms/op
                 listUser·p0.9999: 11.186 ms/op
                 listUser·p1.00:   11.796 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 316778
  mean =      3.027 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 123 
    [ 1.250,  2.500) = 89292 
    [ 2.500,  3.750) = 187833 
    [ 3.750,  5.000) = 31979 
    [ 5.000,  6.250) = 6276 
    [ 6.250,  7.500) = 586 
    [ 7.500,  8.750) = 161 
    [ 8.750, 10.000) = 320 
    [10.000, 11.250) = 171 
    [11.250, 12.500) = 27 
    [12.500, 13.750) = 10 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.757 ms/op
     p(50.0000) =      2.966 ms/op
     p(90.0000) =      3.895 ms/op
     p(95.0000) =      4.407 ms/op
     p(99.0000) =      5.620 ms/op
     p(99.9000) =      9.634 ms/op
     p(99.9900) =     11.376 ms/op
     p(99.9990) =     12.550 ms/op
     p(99.9999) =     13.337 ms/op
    p(100.0000) =     13.337 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.523 ± 1.967  ops/ms
ClientPb.existUser                       thrpt       3  13.114 ± 0.179  ops/ms
ClientPb.getUser                         thrpt       3  12.762 ± 1.820  ops/ms
ClientPb.listUser                        thrpt       3  10.564 ± 0.986  ops/ms
ClientPb.createUser                       avgt       3   2.550 ± 0.546   ms/op
ClientPb.existUser                        avgt       3   2.478 ± 0.317   ms/op
ClientPb.getUser                          avgt       3   2.515 ± 0.562   ms/op
ClientPb.listUser                         avgt       3   3.003 ± 0.772   ms/op
ClientPb.createUser                     sample  370194   2.590 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.954           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.638           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.150           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.277           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.846           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.601           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.860           ms/op
ClientPb.createUser:createUser·p1.00    sample          16.777           ms/op
ClientPb.existUser                      sample  386887   2.480 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.859           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.519           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.015           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.121           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.601           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.129           ms/op
ClientPb.existUser:existUser·p0.9999    sample          14.226           ms/op
ClientPb.existUser:existUser·p1.00      sample          19.202           ms/op
ClientPb.getUser                        sample  386464   2.482 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.429           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.429           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.056           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.224           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.080           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.599           ms/op
ClientPb.getUser:getUser·p0.9999        sample          17.727           ms/op
ClientPb.getUser:getUser·p1.00          sample          18.940           ms/op
ClientPb.listUser                       sample  316778   3.027 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.757           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.966           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.895           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.407           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.620           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.634           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.376           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.337           ms/op
