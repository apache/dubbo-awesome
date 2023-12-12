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
# Warmup Iteration   1: 4.747 ops/ms
# Warmup Iteration   2: 11.565 ops/ms
# Warmup Iteration   3: 12.059 ops/ms
Iteration   1: 12.215 ops/ms
Iteration   2: 12.273 ops/ms
Iteration   3: 12.469 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.319 ±(99.9%) 2.423 ops/ms [Average]
  (min, avg, max) = (12.215, 12.319, 12.469), stdev = 0.133
  CI (99.9%): [9.896, 14.742] (assumes normal distribution)


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
# Warmup Iteration   1: 7.924 ops/ms
# Warmup Iteration   2: 12.702 ops/ms
# Warmup Iteration   3: 12.847 ops/ms
Iteration   1: 12.739 ops/ms
Iteration   2: 12.856 ops/ms
Iteration   3: 12.797 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.797 ±(99.9%) 1.065 ops/ms [Average]
  (min, avg, max) = (12.739, 12.797, 12.856), stdev = 0.058
  CI (99.9%): [11.732, 13.863] (assumes normal distribution)


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
# Warmup Iteration   1: 7.840 ops/ms
# Warmup Iteration   2: 12.436 ops/ms
# Warmup Iteration   3: 12.587 ops/ms
Iteration   1: 12.530 ops/ms
Iteration   2: 12.600 ops/ms
Iteration   3: 12.845 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.658 ±(99.9%) 3.017 ops/ms [Average]
  (min, avg, max) = (12.530, 12.658, 12.845), stdev = 0.165
  CI (99.9%): [9.641, 15.675] (assumes normal distribution)


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
# Warmup Iteration   1: 6.568 ops/ms
# Warmup Iteration   2: 10.498 ops/ms
# Warmup Iteration   3: 10.344 ops/ms
Iteration   1: 10.527 ops/ms
Iteration   2: 10.568 ops/ms
Iteration   3: 10.499 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.531 ±(99.9%) 0.628 ops/ms [Average]
  (min, avg, max) = (10.499, 10.531, 10.568), stdev = 0.034
  CI (99.9%): [9.903, 11.160] (assumes normal distribution)


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
# Warmup Iteration   1: 4.035 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 2.624 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.540 ±(99.9%) 0.004 ms/op
Iteration   1: 2.551 ±(99.9%) 0.004 ms/op
Iteration   2: 2.561 ±(99.9%) 0.003 ms/op
Iteration   3: 2.568 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.560 ±(99.9%) 0.155 ms/op [Average]
  (min, avg, max) = (2.551, 2.560, 2.568), stdev = 0.008
  CI (99.9%): [2.405, 2.715] (assumes normal distribution)


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
# Warmup Iteration   1: 3.827 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.476 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.479 ±(99.9%) 0.004 ms/op
Iteration   1: 2.442 ±(99.9%) 0.003 ms/op
Iteration   2: 2.458 ±(99.9%) 0.005 ms/op
Iteration   3: 2.450 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.450 ±(99.9%) 0.143 ms/op [Average]
  (min, avg, max) = (2.442, 2.450, 2.458), stdev = 0.008
  CI (99.9%): [2.308, 2.593] (assumes normal distribution)


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
# Warmup Iteration   1: 3.914 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.570 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.504 ±(99.9%) 0.003 ms/op
Iteration   1: 2.499 ±(99.9%) 0.005 ms/op
Iteration   2: 2.509 ±(99.9%) 0.004 ms/op
Iteration   3: 2.500 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.503 ±(99.9%) 0.102 ms/op [Average]
  (min, avg, max) = (2.499, 2.503, 2.509), stdev = 0.006
  CI (99.9%): [2.401, 2.604] (assumes normal distribution)


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
# Warmup Iteration   1: 4.745 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.101 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.082 ±(99.9%) 0.005 ms/op
Iteration   1: 3.050 ±(99.9%) 0.006 ms/op
Iteration   2: 3.040 ±(99.9%) 0.005 ms/op
Iteration   3: 3.037 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.042 ±(99.9%) 0.124 ms/op [Average]
  (min, avg, max) = (3.037, 3.042, 3.050), stdev = 0.007
  CI (99.9%): [2.918, 3.166] (assumes normal distribution)


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
# Warmup Iteration   1: 4.442 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 2.677 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.560 ±(99.9%) 0.006 ms/op
Iteration   1: 2.551 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.019 ms/op
                 createUser·p0.50:   2.589 ms/op
                 createUser·p0.90:   3.097 ms/op
                 createUser·p0.95:   3.215 ms/op
                 createUser·p0.99:   3.841 ms/op
                 createUser·p0.999:  12.304 ms/op
                 createUser·p0.9999: 14.136 ms/op
                 createUser·p1.00:   14.418 ms/op

Iteration   2: 2.576 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.102 ms/op
                 createUser·p0.50:   2.630 ms/op
                 createUser·p0.90:   3.133 ms/op
                 createUser·p0.95:   3.248 ms/op
                 createUser·p0.99:   3.764 ms/op
                 createUser·p0.999:  9.394 ms/op
                 createUser·p0.9999: 11.914 ms/op
                 createUser·p1.00:   12.943 ms/op

Iteration   3: 2.586 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.677 ms/op
                 createUser·p0.50:   2.634 ms/op
                 createUser·p0.90:   3.146 ms/op
                 createUser·p0.95:   3.281 ms/op
                 createUser·p0.99:   4.125 ms/op
                 createUser·p0.999:  9.191 ms/op
                 createUser·p0.9999: 11.119 ms/op
                 createUser·p1.00:   11.698 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 373010
  mean =      2.571 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 53 
    [ 1.250,  2.500) = 177462 
    [ 2.500,  3.750) = 190632 
    [ 3.750,  5.000) = 3947 
    [ 5.000,  6.250) = 442 
    [ 6.250,  7.500) = 25 
    [ 7.500,  8.750) = 27 
    [ 8.750, 10.000) = 64 
    [10.000, 11.250) = 148 
    [11.250, 12.500) = 105 
    [12.500, 13.750) = 90 
    [13.750, 15.000) = 15 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.677 ms/op
     p(50.0000) =      2.617 ms/op
     p(90.0000) =      3.125 ms/op
     p(95.0000) =      3.248 ms/op
     p(99.0000) =      3.899 ms/op
     p(99.9000) =      9.699 ms/op
     p(99.9900) =     13.255 ms/op
     p(99.9990) =     14.385 ms/op
     p(99.9999) =     14.418 ms/op
    p(100.0000) =     14.418 ms/op


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
# Warmup Iteration   1: 3.701 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.484 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.482 ±(99.9%) 0.006 ms/op
Iteration   1: 2.470 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.769 ms/op
                 existUser·p0.50:   2.515 ms/op
                 existUser·p0.90:   3.006 ms/op
                 existUser·p0.95:   3.129 ms/op
                 existUser·p0.99:   3.740 ms/op
                 existUser·p0.999:  6.588 ms/op
                 existUser·p0.9999: 16.844 ms/op
                 existUser·p1.00:   17.269 ms/op

Iteration   2: 2.459 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.049 ms/op
                 existUser·p0.50:   2.515 ms/op
                 existUser·p0.90:   2.990 ms/op
                 existUser·p0.95:   3.097 ms/op
                 existUser·p0.99:   3.678 ms/op
                 existUser·p0.999:  6.758 ms/op
                 existUser·p0.9999: 15.712 ms/op
                 existUser·p1.00:   16.941 ms/op

Iteration   3: 2.467 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.962 ms/op
                 existUser·p0.50:   2.515 ms/op
                 existUser·p0.90:   3.002 ms/op
                 existUser·p0.95:   3.121 ms/op
                 existUser·p0.99:   3.744 ms/op
                 existUser·p0.999:  6.912 ms/op
                 existUser·p0.9999: 11.093 ms/op
                 existUser·p1.00:   11.420 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 389056
  mean =      2.466 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 53 
    [ 1.250,  2.500) = 193172 
    [ 2.500,  3.750) = 192105 
    [ 3.750,  5.000) = 2841 
    [ 5.000,  6.250) = 462 
    [ 6.250,  7.500) = 45 
    [ 7.500,  8.750) = 46 
    [ 8.750, 10.000) = 52 
    [10.000, 11.250) = 102 
    [11.250, 12.500) = 36 
    [12.500, 13.750) = 23 
    [13.750, 15.000) = 23 
    [15.000, 16.250) = 69 
    [16.250, 17.500) = 27 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.769 ms/op
     p(50.0000) =      2.515 ms/op
     p(90.0000) =      2.998 ms/op
     p(95.0000) =      3.117 ms/op
     p(99.0000) =      3.723 ms/op
     p(99.9000) =      6.863 ms/op
     p(99.9900) =     15.902 ms/op
     p(99.9990) =     17.108 ms/op
     p(99.9999) =     17.269 ms/op
    p(100.0000) =     17.269 ms/op


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
# Warmup Iteration   1: 4.139 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.656 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.567 ±(99.9%) 0.006 ms/op
Iteration   1: 2.546 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.853 ms/op
                 getUser·p0.50:   2.560 ms/op
                 getUser·p0.90:   3.101 ms/op
                 getUser·p0.95:   3.219 ms/op
                 getUser·p0.99:   3.752 ms/op
                 getUser·p0.999:  11.843 ms/op
                 getUser·p0.9999: 14.547 ms/op
                 getUser·p1.00:   14.877 ms/op

Iteration   2: 2.558 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.878 ms/op
                 getUser·p0.50:   2.564 ms/op
                 getUser·p0.90:   3.121 ms/op
                 getUser·p0.95:   3.265 ms/op
                 getUser·p0.99:   3.981 ms/op
                 getUser·p0.999:  9.978 ms/op
                 getUser·p0.9999: 13.836 ms/op
                 getUser·p1.00:   14.696 ms/op

Iteration   3: 2.553 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.847 ms/op
                 getUser·p0.50:   2.548 ms/op
                 getUser·p0.90:   3.121 ms/op
                 getUser·p0.95:   3.265 ms/op
                 getUser·p0.99:   4.084 ms/op
                 getUser·p0.999:  8.287 ms/op
                 getUser·p0.9999: 11.349 ms/op
                 getUser·p1.00:   12.157 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 375795
  mean =      2.552 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 60 
    [ 1.250,  2.500) = 183221 
    [ 2.500,  3.750) = 187416 
    [ 3.750,  5.000) = 4032 
    [ 5.000,  6.250) = 592 
    [ 6.250,  7.500) = 78 
    [ 7.500,  8.750) = 30 
    [ 8.750, 10.000) = 61 
    [10.000, 11.250) = 106 
    [11.250, 12.500) = 61 
    [12.500, 13.750) = 74 
    [13.750, 15.000) = 64 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.847 ms/op
     p(50.0000) =      2.560 ms/op
     p(90.0000) =      3.113 ms/op
     p(95.0000) =      3.248 ms/op
     p(99.0000) =      3.924 ms/op
     p(99.9000) =      8.428 ms/op
     p(99.9900) =     14.032 ms/op
     p(99.9990) =     14.799 ms/op
     p(99.9999) =     14.877 ms/op
    p(100.0000) =     14.877 ms/op


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
# Warmup Iteration   1: 4.831 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.185 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.093 ±(99.9%) 0.009 ms/op
Iteration   1: 3.090 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.930 ms/op
                 listUser·p0.50:   3.035 ms/op
                 listUser·p0.90:   3.981 ms/op
                 listUser·p0.95:   4.465 ms/op
                 listUser·p0.99:   5.693 ms/op
                 listUser·p0.999:  9.757 ms/op
                 listUser·p0.9999: 15.712 ms/op
                 listUser·p1.00:   16.531 ms/op

Iteration   2: 3.094 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.988 ms/op
                 listUser·p0.50:   3.031 ms/op
                 listUser·p0.90:   3.973 ms/op
                 listUser·p0.95:   4.497 ms/op
                 listUser·p0.99:   5.825 ms/op
                 listUser·p0.999:  9.973 ms/op
                 listUser·p0.9999: 11.398 ms/op
                 listUser·p1.00:   11.764 ms/op

Iteration   3: 3.071 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.860 ms/op
                 listUser·p0.50:   3.006 ms/op
                 listUser·p0.90:   3.957 ms/op
                 listUser·p0.95:   4.481 ms/op
                 listUser·p0.99:   5.743 ms/op
                 listUser·p0.999:  9.224 ms/op
                 listUser·p0.9999: 10.977 ms/op
                 listUser·p1.00:   11.354 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 310868
  mean =      3.085 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 95 
    [ 1.250,  2.500) = 79772 
    [ 2.500,  3.750) = 187178 
    [ 3.750,  5.000) = 35489 
    [ 5.000,  6.250) = 6760 
    [ 6.250,  7.500) = 912 
    [ 7.500,  8.750) = 187 
    [ 8.750, 10.000) = 242 
    [10.000, 11.250) = 149 
    [11.250, 12.500) = 29 
    [12.500, 13.750) = 15 
    [13.750, 15.000) = 18 
    [15.000, 16.250) = 19 
    [16.250, 17.500) = 3 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.860 ms/op
     p(50.0000) =      3.023 ms/op
     p(90.0000) =      3.969 ms/op
     p(95.0000) =      4.481 ms/op
     p(99.0000) =      5.759 ms/op
     p(99.9000) =      9.568 ms/op
     p(99.9900) =     14.729 ms/op
     p(99.9990) =     16.243 ms/op
     p(99.9999) =     16.531 ms/op
    p(100.0000) =     16.531 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.319 ± 2.423  ops/ms
ClientPb.existUser                       thrpt       3  12.797 ± 1.065  ops/ms
ClientPb.getUser                         thrpt       3  12.658 ± 3.017  ops/ms
ClientPb.listUser                        thrpt       3  10.531 ± 0.628  ops/ms
ClientPb.createUser                       avgt       3   2.560 ± 0.155   ms/op
ClientPb.existUser                        avgt       3   2.450 ± 0.143   ms/op
ClientPb.getUser                          avgt       3   2.503 ± 0.102   ms/op
ClientPb.listUser                         avgt       3   3.042 ± 0.124   ms/op
ClientPb.createUser                     sample  373010   2.571 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.677           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.617           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.125           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.248           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.899           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.699           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.255           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.418           ms/op
ClientPb.existUser                      sample  389056   2.466 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.769           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.515           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.998           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.117           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.723           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.863           ms/op
ClientPb.existUser:existUser·p0.9999    sample          15.902           ms/op
ClientPb.existUser:existUser·p1.00      sample          17.269           ms/op
ClientPb.getUser                        sample  375795   2.552 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.847           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.560           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.113           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.248           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.924           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.428           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.032           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.877           ms/op
ClientPb.listUser                       sample  310868   3.085 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.860           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.023           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.969           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.481           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.759           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.568           ms/op
ClientPb.listUser:listUser·p0.9999      sample          14.729           ms/op
ClientPb.listUser:listUser·p1.00        sample          16.531           ms/op
