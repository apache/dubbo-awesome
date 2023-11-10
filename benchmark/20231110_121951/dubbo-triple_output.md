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
# Warmup Iteration   1: 4.916 ops/ms
# Warmup Iteration   2: 12.353 ops/ms
# Warmup Iteration   3: 11.989 ops/ms
Iteration   1: 12.469 ops/ms
Iteration   2: 12.731 ops/ms
Iteration   3: 12.700 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.633 ±(99.9%) 2.618 ops/ms [Average]
  (min, avg, max) = (12.469, 12.633, 12.731), stdev = 0.143
  CI (99.9%): [10.016, 15.251] (assumes normal distribution)


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
# Warmup Iteration   1: 7.823 ops/ms
# Warmup Iteration   2: 12.697 ops/ms
# Warmup Iteration   3: 12.655 ops/ms
Iteration   1: 12.582 ops/ms
Iteration   2: 12.482 ops/ms
Iteration   3: 12.548 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.537 ±(99.9%) 0.926 ops/ms [Average]
  (min, avg, max) = (12.482, 12.537, 12.582), stdev = 0.051
  CI (99.9%): [11.612, 13.463] (assumes normal distribution)


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
# Warmup Iteration   1: 7.458 ops/ms
# Warmup Iteration   2: 12.529 ops/ms
# Warmup Iteration   3: 12.554 ops/ms
Iteration   1: 12.443 ops/ms
Iteration   2: 12.351 ops/ms
Iteration   3: 12.567 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.454 ±(99.9%) 1.984 ops/ms [Average]
  (min, avg, max) = (12.351, 12.454, 12.567), stdev = 0.109
  CI (99.9%): [10.470, 14.438] (assumes normal distribution)


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
# Warmup Iteration   1: 6.267 ops/ms
# Warmup Iteration   2: 10.220 ops/ms
# Warmup Iteration   3: 10.360 ops/ms
Iteration   1: 10.332 ops/ms
Iteration   2: 10.360 ops/ms
Iteration   3: 10.361 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.351 ±(99.9%) 0.298 ops/ms [Average]
  (min, avg, max) = (10.332, 10.351, 10.361), stdev = 0.016
  CI (99.9%): [10.053, 10.649] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:39
# Fork: 1 of 1
# Warmup Iteration   1: 4.128 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.625 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.525 ±(99.9%) 0.004 ms/op
Iteration   1: 2.545 ±(99.9%) 0.004 ms/op
Iteration   2: 2.573 ±(99.9%) 0.004 ms/op
Iteration   3: 2.576 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.564 ±(99.9%) 0.315 ms/op [Average]
  (min, avg, max) = (2.545, 2.564, 2.576), stdev = 0.017
  CI (99.9%): [2.250, 2.879] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:34
# Fork: 1 of 1
# Warmup Iteration   1: 3.957 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.538 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.587 ±(99.9%) 0.004 ms/op
Iteration   1: 2.601 ±(99.9%) 0.004 ms/op
Iteration   2: 2.636 ±(99.9%) 0.005 ms/op
Iteration   3: 2.628 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.622 ±(99.9%) 0.333 ms/op [Average]
  (min, avg, max) = (2.601, 2.622, 2.636), stdev = 0.018
  CI (99.9%): [2.289, 2.955] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:29
# Fork: 1 of 1
# Warmup Iteration   1: 4.401 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.733 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.683 ±(99.9%) 0.004 ms/op
Iteration   1: 2.615 ±(99.9%) 0.004 ms/op
Iteration   2: 2.632 ±(99.9%) 0.004 ms/op
Iteration   3: 2.614 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.621 ±(99.9%) 0.185 ms/op [Average]
  (min, avg, max) = (2.614, 2.621, 2.632), stdev = 0.010
  CI (99.9%): [2.435, 2.806] (assumes normal distribution)


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
# Warmup Iteration   1: 5.025 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.073 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.055 ±(99.9%) 0.005 ms/op
Iteration   1: 3.052 ±(99.9%) 0.006 ms/op
Iteration   2: 3.050 ±(99.9%) 0.006 ms/op
Iteration   3: 3.035 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.046 ±(99.9%) 0.166 ms/op [Average]
  (min, avg, max) = (3.035, 3.046, 3.052), stdev = 0.009
  CI (99.9%): [2.880, 3.212] (assumes normal distribution)


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
# Warmup Iteration   1: 4.476 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 2.639 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.607 ±(99.9%) 0.007 ms/op
Iteration   1: 2.590 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.730 ms/op
                 createUser·p0.50:   2.650 ms/op
                 createUser·p0.90:   3.150 ms/op
                 createUser·p0.95:   3.301 ms/op
                 createUser·p0.99:   4.071 ms/op
                 createUser·p0.999:  11.190 ms/op
                 createUser·p0.9999: 16.100 ms/op
                 createUser·p1.00:   17.236 ms/op

Iteration   2: 2.551 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.795 ms/op
                 createUser·p0.50:   2.626 ms/op
                 createUser·p0.90:   3.101 ms/op
                 createUser·p0.95:   3.228 ms/op
                 createUser·p0.99:   3.801 ms/op
                 createUser·p0.999:  10.219 ms/op
                 createUser·p0.9999: 12.417 ms/op
                 createUser·p1.00:   13.353 ms/op

Iteration   3: 2.530 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.182 ms/op
                 createUser·p0.50:   2.613 ms/op
                 createUser·p0.90:   3.068 ms/op
                 createUser·p0.95:   3.187 ms/op
                 createUser·p0.99:   3.977 ms/op
                 createUser·p0.999:  9.244 ms/op
                 createUser·p0.9999: 11.000 ms/op
                 createUser·p1.00:   11.239 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 375103
  mean =      2.557 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 43 
    [ 1.250,  2.500) = 177779 
    [ 2.500,  3.750) = 191999 
    [ 3.750,  5.000) = 4171 
    [ 5.000,  6.250) = 658 
    [ 6.250,  7.500) = 54 
    [ 7.500,  8.750) = 6 
    [ 8.750, 10.000) = 62 
    [10.000, 11.250) = 153 
    [11.250, 12.500) = 72 
    [12.500, 13.750) = 56 
    [13.750, 15.000) = 36 
    [15.000, 16.250) = 6 
    [16.250, 17.500) = 8 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.730 ms/op
     p(50.0000) =      2.630 ms/op
     p(90.0000) =      3.109 ms/op
     p(95.0000) =      3.240 ms/op
     p(99.0000) =      3.969 ms/op
     p(99.9000) =      9.337 ms/op
     p(99.9900) =     14.074 ms/op
     p(99.9990) =     17.039 ms/op
     p(99.9999) =     17.236 ms/op
    p(100.0000) =     17.236 ms/op


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
# Warmup Iteration   1: 3.940 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.567 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.535 ±(99.9%) 0.006 ms/op
Iteration   1: 2.510 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.720 ms/op
                 existUser·p0.50:   2.552 ms/op
                 existUser·p0.90:   3.060 ms/op
                 existUser·p0.95:   3.187 ms/op
                 existUser·p0.99:   3.785 ms/op
                 existUser·p0.999:  5.497 ms/op
                 existUser·p0.9999: 15.389 ms/op
                 existUser·p1.00:   15.909 ms/op

Iteration   2: 2.583 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.955 ms/op
                 existUser·p0.50:   2.601 ms/op
                 existUser·p0.90:   3.097 ms/op
                 existUser·p0.95:   3.232 ms/op
                 existUser·p0.99:   5.206 ms/op
                 existUser·p0.999:  12.583 ms/op
                 existUser·p0.9999: 23.122 ms/op
                 existUser·p1.00:   23.495 ms/op

Iteration   3: 2.615 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.850 ms/op
                 existUser·p0.50:   2.654 ms/op
                 existUser·p0.90:   3.117 ms/op
                 existUser·p0.95:   3.318 ms/op
                 existUser·p0.99:   6.603 ms/op
                 existUser·p0.999:  10.350 ms/op
                 existUser·p0.9999: 11.969 ms/op
                 existUser·p1.00:   13.271 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 373410
  mean =      2.568 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 179327 
    [ 2.500,  5.000) = 190366 
    [ 5.000,  7.500) = 2143 
    [ 7.500, 10.000) = 1022 
    [10.000, 12.500) = 329 
    [12.500, 15.000) = 170 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.720 ms/op
     p(50.0000) =      2.601 ms/op
     p(90.0000) =      3.092 ms/op
     p(95.0000) =      3.236 ms/op
     p(99.0000) =      4.997 ms/op
     p(99.9000) =     10.774 ms/op
     p(99.9900) =     15.706 ms/op
     p(99.9990) =     23.372 ms/op
     p(99.9999) =     23.495 ms/op
    p(100.0000) =     23.495 ms/op


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
# Warmup Iteration   1: 4.596 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 2.718 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 2.677 ±(99.9%) 0.008 ms/op
Iteration   1: 2.575 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.952 ms/op
                 getUser·p0.50:   2.634 ms/op
                 getUser·p0.90:   3.125 ms/op
                 getUser·p0.95:   3.248 ms/op
                 getUser·p0.99:   3.998 ms/op
                 getUser·p0.999:  12.550 ms/op
                 getUser·p0.9999: 14.214 ms/op
                 getUser·p1.00:   14.909 ms/op

Iteration   2: 2.593 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.934 ms/op
                 getUser·p0.50:   2.589 ms/op
                 getUser·p0.90:   3.142 ms/op
                 getUser·p0.95:   3.318 ms/op
                 getUser·p0.99:   4.955 ms/op
                 getUser·p0.999:  9.842 ms/op
                 getUser·p0.9999: 15.221 ms/op
                 getUser·p1.00:   16.105 ms/op

Iteration   3: 2.546 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.044 ms/op
                 getUser·p0.50:   2.585 ms/op
                 getUser·p0.90:   3.097 ms/op
                 getUser·p0.95:   3.207 ms/op
                 getUser·p0.99:   3.707 ms/op
                 getUser·p0.999:  5.681 ms/op
                 getUser·p0.9999: 10.673 ms/op
                 getUser·p1.00:   10.895 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 373095
  mean =      2.571 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 41 
    [ 1.250,  2.500) = 180679 
    [ 2.500,  3.750) = 186272 
    [ 3.750,  5.000) = 4369 
    [ 5.000,  6.250) = 1269 
    [ 6.250,  7.500) = 100 
    [ 7.500,  8.750) = 17 
    [ 8.750, 10.000) = 63 
    [10.000, 11.250) = 79 
    [11.250, 12.500) = 18 
    [12.500, 13.750) = 95 
    [13.750, 15.000) = 67 
    [15.000, 16.250) = 26 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.934 ms/op
     p(50.0000) =      2.601 ms/op
     p(90.0000) =      3.121 ms/op
     p(95.0000) =      3.252 ms/op
     p(99.0000) =      4.153 ms/op
     p(99.9000) =      7.274 ms/op
     p(99.9900) =     14.631 ms/op
     p(99.9990) =     15.869 ms/op
     p(99.9999) =     16.105 ms/op
    p(100.0000) =     16.105 ms/op


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
# Warmup Iteration   1: 4.868 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 3.137 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.087 ±(99.9%) 0.009 ms/op
Iteration   1: 3.100 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.963 ms/op
                 listUser·p0.50:   3.039 ms/op
                 listUser·p0.90:   4.010 ms/op
                 listUser·p0.95:   4.530 ms/op
                 listUser·p0.99:   5.677 ms/op
                 listUser·p0.999:  10.039 ms/op
                 listUser·p0.9999: 11.928 ms/op
                 listUser·p1.00:   12.681 ms/op

Iteration   2: 3.079 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.662 ms/op
                 listUser·p0.50:   3.011 ms/op
                 listUser·p0.90:   3.953 ms/op
                 listUser·p0.95:   4.456 ms/op
                 listUser·p0.99:   5.825 ms/op
                 listUser·p0.999:  9.898 ms/op
                 listUser·p0.9999: 11.040 ms/op
                 listUser·p1.00:   12.075 ms/op

Iteration   3: 3.129 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.785 ms/op
                 listUser·p0.50:   3.052 ms/op
                 listUser·p0.90:   4.063 ms/op
                 listUser·p0.95:   4.678 ms/op
                 listUser·p0.99:   6.074 ms/op
                 listUser·p0.999:  10.336 ms/op
                 listUser·p0.9999: 15.561 ms/op
                 listUser·p1.00:   16.269 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 309129
  mean =      3.102 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 104 
    [ 1.250,  2.500) = 77962 
    [ 2.500,  3.750) = 185372 
    [ 3.750,  5.000) = 36621 
    [ 5.000,  6.250) = 7273 
    [ 6.250,  7.500) = 1013 
    [ 7.500,  8.750) = 220 
    [ 8.750, 10.000) = 234 
    [10.000, 11.250) = 252 
    [11.250, 12.500) = 59 
    [12.500, 13.750) = 5 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 13 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.662 ms/op
     p(50.0000) =      3.031 ms/op
     p(90.0000) =      4.006 ms/op
     p(95.0000) =      4.547 ms/op
     p(99.0000) =      5.857 ms/op
     p(99.9000) =     10.076 ms/op
     p(99.9900) =     12.029 ms/op
     p(99.9990) =     16.113 ms/op
     p(99.9999) =     16.269 ms/op
    p(100.0000) =     16.269 ms/op


# Run complete. Total time: 00:13:00

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.633 ± 2.618  ops/ms
ClientPb.existUser                       thrpt       3  12.537 ± 0.926  ops/ms
ClientPb.getUser                         thrpt       3  12.454 ± 1.984  ops/ms
ClientPb.listUser                        thrpt       3  10.351 ± 0.298  ops/ms
ClientPb.createUser                       avgt       3   2.564 ± 0.315   ms/op
ClientPb.existUser                        avgt       3   2.622 ± 0.333   ms/op
ClientPb.getUser                          avgt       3   2.621 ± 0.185   ms/op
ClientPb.listUser                         avgt       3   3.046 ± 0.166   ms/op
ClientPb.createUser                     sample  375103   2.557 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.730           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.630           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.109           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.240           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.969           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.337           ms/op
ClientPb.createUser:createUser·p0.9999  sample          14.074           ms/op
ClientPb.createUser:createUser·p1.00    sample          17.236           ms/op
ClientPb.existUser                      sample  373410   2.568 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.720           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.601           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.092           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.236           ms/op
ClientPb.existUser:existUser·p0.99      sample           4.997           ms/op
ClientPb.existUser:existUser·p0.999     sample          10.774           ms/op
ClientPb.existUser:existUser·p0.9999    sample          15.706           ms/op
ClientPb.existUser:existUser·p1.00      sample          23.495           ms/op
ClientPb.getUser                        sample  373095   2.571 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.934           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.601           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.121           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.252           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.153           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.274           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.631           ms/op
ClientPb.getUser:getUser·p1.00          sample          16.105           ms/op
ClientPb.listUser                       sample  309129   3.102 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.662           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.031           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.006           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.547           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.857           ms/op
ClientPb.listUser:listUser·p0.999       sample          10.076           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.029           ms/op
ClientPb.listUser:listUser·p1.00        sample          16.269           ms/op
