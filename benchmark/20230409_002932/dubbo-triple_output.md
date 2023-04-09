# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 0.956 ops/ms
# Warmup Iteration   2: 2.374 ops/ms
# Warmup Iteration   3: 5.086 ops/ms
Iteration   1: 5.066 ops/ms
Iteration   2: 5.544 ops/ms
Iteration   3: 5.710 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.440 ±(99.9%) 6.103 ops/ms [Average]
  (min, avg, max) = (5.066, 5.440, 5.710), stdev = 0.335
  CI (99.9%): [≈ 0, 11.543] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:17
# Fork: 1 of 1
# Warmup Iteration   1: 1.623 ops/ms
# Warmup Iteration   2: 4.243 ops/ms
# Warmup Iteration   3: 5.799 ops/ms
Iteration   1: 5.764 ops/ms
Iteration   2: 5.817 ops/ms
Iteration   3: 5.790 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.790 ±(99.9%) 0.488 ops/ms [Average]
  (min, avg, max) = (5.764, 5.790, 5.817), stdev = 0.027
  CI (99.9%): [5.302, 6.278] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:09
# Fork: 1 of 1
# Warmup Iteration   1: 1.496 ops/ms
# Warmup Iteration   2: 4.150 ops/ms
# Warmup Iteration   3: 5.174 ops/ms
Iteration   1: 5.166 ops/ms
Iteration   2: 5.216 ops/ms
Iteration   3: 5.559 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.314 ±(99.9%) 3.905 ops/ms [Average]
  (min, avg, max) = (5.166, 5.314, 5.559), stdev = 0.214
  CI (99.9%): [1.409, 9.219] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:10:02
# Fork: 1 of 1
# Warmup Iteration   1: 1.357 ops/ms
# Warmup Iteration   2: 3.427 ops/ms
# Warmup Iteration   3: 4.506 ops/ms
Iteration   1: 4.648 ops/ms
Iteration   2: 4.746 ops/ms
Iteration   3: 4.832 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.742 ±(99.9%) 1.674 ops/ms [Average]
  (min, avg, max) = (4.648, 4.742, 4.832), stdev = 0.092
  CI (99.9%): [3.069, 6.416] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:53
# Fork: 1 of 1
# Warmup Iteration   1: 19.415 ±(99.9%) 0.122 ms/op
# Warmup Iteration   2: 7.038 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 6.152 ±(99.9%) 0.015 ms/op
Iteration   1: 5.872 ±(99.9%) 0.011 ms/op
Iteration   2: 5.570 ±(99.9%) 0.011 ms/op
Iteration   3: 5.652 ±(99.9%) 0.031 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.698 ±(99.9%) 2.854 ms/op [Average]
  (min, avg, max) = (5.570, 5.698, 5.872), stdev = 0.156
  CI (99.9%): [2.844, 8.552] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:47
# Fork: 1 of 1
# Warmup Iteration   1: 17.458 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 7.111 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.754 ±(99.9%) 0.009 ms/op
Iteration   1: 5.768 ±(99.9%) 0.009 ms/op
Iteration   2: 5.672 ±(99.9%) 0.006 ms/op
Iteration   3: 5.553 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.664 ±(99.9%) 1.970 ms/op [Average]
  (min, avg, max) = (5.553, 5.664, 5.768), stdev = 0.108
  CI (99.9%): [3.694, 7.634] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:40
# Fork: 1 of 1
# Warmup Iteration   1: 19.016 ±(99.9%) 0.107 ms/op
# Warmup Iteration   2: 6.992 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.548 ±(99.9%) 0.019 ms/op
Iteration   1: 5.576 ±(99.9%) 0.012 ms/op
Iteration   2: 5.733 ±(99.9%) 0.015 ms/op
Iteration   3: 5.868 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.725 ±(99.9%) 2.665 ms/op [Average]
  (min, avg, max) = (5.576, 5.725, 5.868), stdev = 0.146
  CI (99.9%): [3.060, 8.391] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:32
# Fork: 1 of 1
# Warmup Iteration   1: 22.303 ±(99.9%) 0.106 ms/op
# Warmup Iteration   2: 8.527 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 6.905 ±(99.9%) 0.011 ms/op
Iteration   1: 6.839 ±(99.9%) 0.027 ms/op
Iteration   2: 6.692 ±(99.9%) 0.023 ms/op
Iteration   3: 6.859 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.797 ±(99.9%) 1.660 ms/op [Average]
  (min, avg, max) = (6.692, 6.797, 6.859), stdev = 0.091
  CI (99.9%): [5.137, 8.456] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:26
# Fork: 1 of 1
# Warmup Iteration   1: 18.444 ±(99.9%) 0.331 ms/op
# Warmup Iteration   2: 7.479 ±(99.9%) 0.049 ms/op
# Warmup Iteration   3: 6.320 ±(99.9%) 0.031 ms/op
Iteration   1: 5.789 ±(99.9%) 0.022 ms/op
                 createUser·p0.00:   2.736 ms/op
                 createUser·p0.50:   5.341 ms/op
                 createUser·p0.90:   7.184 ms/op
                 createUser·p0.95:   8.217 ms/op
                 createUser·p0.99:   11.534 ms/op
                 createUser·p0.999:  25.355 ms/op
                 createUser·p0.9999: 27.787 ms/op
                 createUser·p1.00:   28.180 ms/op

Iteration   2: 5.737 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   2.585 ms/op
                 createUser·p0.50:   5.439 ms/op
                 createUser·p0.90:   7.029 ms/op
                 createUser·p0.95:   7.540 ms/op
                 createUser·p0.99:   9.716 ms/op
                 createUser·p0.999:  29.728 ms/op
                 createUser·p0.9999: 33.554 ms/op
                 createUser·p1.00:   33.817 ms/op

Iteration   3: 5.836 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   2.294 ms/op
                 createUser·p0.50:   5.571 ms/op
                 createUser·p0.90:   7.111 ms/op
                 createUser·p0.95:   7.809 ms/op
                 createUser·p0.99:   9.798 ms/op
                 createUser·p0.999:  14.385 ms/op
                 createUser·p0.9999: 31.547 ms/op
                 createUser·p1.00:   33.194 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 165785
  mean =      5.787 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1 
    [ 2.500,  5.000) = 38429 
    [ 5.000,  7.500) = 116522 
    [ 7.500, 10.000) = 8547 
    [10.000, 12.500) = 1765 
    [12.500, 15.000) = 290 
    [15.000, 17.500) = 71 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 48 
    [27.500, 30.000) = 33 
    [30.000, 32.500) = 53 
    [32.500, 35.000) = 22 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.294 ms/op
     p(50.0000) =      5.456 ms/op
     p(90.0000) =      7.102 ms/op
     p(95.0000) =      7.799 ms/op
     p(99.0000) =     10.715 ms/op
     p(99.9000) =     17.203 ms/op
     p(99.9900) =     32.725 ms/op
     p(99.9990) =     33.687 ms/op
     p(99.9999) =     33.817 ms/op
    p(100.0000) =     33.817 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 16.541 ±(99.9%) 0.284 ms/op
# Warmup Iteration   2: 6.526 ±(99.9%) 0.041 ms/op
# Warmup Iteration   3: 5.784 ±(99.9%) 0.021 ms/op
Iteration   1: 5.594 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   1.710 ms/op
                 existUser·p0.50:   5.267 ms/op
                 existUser·p0.90:   6.799 ms/op
                 existUser·p0.95:   7.840 ms/op
                 existUser·p0.99:   11.198 ms/op
                 existUser·p0.999:  25.042 ms/op
                 existUser·p0.9999: 30.212 ms/op
                 existUser·p1.00:   30.835 ms/op

Iteration   2: 5.612 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   2.552 ms/op
                 existUser·p0.50:   5.317 ms/op
                 existUser·p0.90:   6.840 ms/op
                 existUser·p0.95:   7.651 ms/op
                 existUser·p0.99:   10.600 ms/op
                 existUser·p0.999:  27.298 ms/op
                 existUser·p0.9999: 33.050 ms/op
                 existUser·p1.00:   33.817 ms/op

Iteration   3: 5.631 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   2.589 ms/op
                 existUser·p0.50:   5.300 ms/op
                 existUser·p0.90:   6.857 ms/op
                 existUser·p0.95:   7.758 ms/op
                 existUser·p0.99:   10.912 ms/op
                 existUser·p0.999:  20.528 ms/op
                 existUser·p0.9999: 32.570 ms/op
                 existUser·p1.00:   36.569 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 170879
  mean =      5.612 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5 
    [ 2.500,  5.000) = 54884 
    [ 5.000,  7.500) = 105982 
    [ 7.500, 10.000) = 7430 
    [10.000, 12.500) = 1661 
    [12.500, 15.000) = 561 
    [15.000, 17.500) = 138 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 26 
    [27.500, 30.000) = 70 
    [30.000, 32.500) = 44 
    [32.500, 35.000) = 19 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.710 ms/op
     p(50.0000) =      5.300 ms/op
     p(90.0000) =      6.832 ms/op
     p(95.0000) =      7.758 ms/op
     p(99.0000) =     10.945 ms/op
     p(99.9000) =     23.658 ms/op
     p(99.9900) =     32.667 ms/op
     p(99.9990) =     35.454 ms/op
     p(99.9999) =     36.569 ms/op
    p(100.0000) =     36.569 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 19.213 ±(99.9%) 0.302 ms/op
# Warmup Iteration   2: 6.900 ±(99.9%) 0.039 ms/op
# Warmup Iteration   3: 5.943 ±(99.9%) 0.021 ms/op
Iteration   1: 6.019 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   2.626 ms/op
                 getUser·p0.50:   5.603 ms/op
                 getUser·p0.90:   7.479 ms/op
                 getUser·p0.95:   9.077 ms/op
                 getUser·p0.99:   12.714 ms/op
                 getUser·p0.999:  25.416 ms/op
                 getUser·p0.9999: 29.022 ms/op
                 getUser·p1.00:   30.081 ms/op

Iteration   2: 6.210 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   2.753 ms/op
                 getUser·p0.50:   6.111 ms/op
                 getUser·p0.90:   7.438 ms/op
                 getUser·p0.95:   8.151 ms/op
                 getUser·p0.99:   11.115 ms/op
                 getUser·p0.999:  15.981 ms/op
                 getUser·p0.9999: 35.547 ms/op
                 getUser·p1.00:   36.635 ms/op

Iteration   3: 5.875 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   2.855 ms/op
                 getUser·p0.50:   5.595 ms/op
                 getUser·p0.90:   7.094 ms/op
                 getUser·p0.95:   8.421 ms/op
                 getUser·p0.99:   11.158 ms/op
                 getUser·p0.999:  26.673 ms/op
                 getUser·p0.9999: 30.147 ms/op
                 getUser·p1.00:   30.343 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 159013
  mean =      6.032 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 29466 
    [ 5.000,  7.500) = 115326 
    [ 7.500, 10.000) = 10624 
    [10.000, 12.500) = 2436 
    [12.500, 15.000) = 782 
    [15.000, 17.500) = 165 
    [17.500, 20.000) = 50 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 61 
    [27.500, 30.000) = 47 
    [30.000, 32.500) = 25 
    [32.500, 35.000) = 11 
    [35.000, 37.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      2.626 ms/op
     p(50.0000) =      5.751 ms/op
     p(90.0000) =      7.348 ms/op
     p(95.0000) =      8.438 ms/op
     p(99.0000) =     11.878 ms/op
     p(99.9000) =     24.346 ms/op
     p(99.9900) =     32.709 ms/op
     p(99.9990) =     36.557 ms/op
     p(99.9999) =     36.635 ms/op
    p(100.0000) =     36.635 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 22.063 ±(99.9%) 0.375 ms/op
# Warmup Iteration   2: 8.844 ±(99.9%) 0.059 ms/op
# Warmup Iteration   3: 7.039 ±(99.9%) 0.026 ms/op
Iteration   1: 6.680 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   2.392 ms/op
                 listUser·p0.50:   6.447 ms/op
                 listUser·p0.90:   7.776 ms/op
                 listUser·p0.95:   8.765 ms/op
                 listUser·p0.99:   11.261 ms/op
                 listUser·p0.999:  29.668 ms/op
                 listUser·p0.9999: 34.093 ms/op
                 listUser·p1.00:   35.914 ms/op

Iteration   2: 6.669 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   3.178 ms/op
                 listUser·p0.50:   6.349 ms/op
                 listUser·p0.90:   7.741 ms/op
                 listUser·p0.95:   8.880 ms/op
                 listUser·p0.99:   12.304 ms/op
                 listUser·p0.999:  31.955 ms/op
                 listUser·p0.9999: 34.344 ms/op
                 listUser·p1.00:   35.717 ms/op

Iteration   3: 7.121 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   3.396 ms/op
                 listUser·p0.50:   6.799 ms/op
                 listUser·p0.90:   8.815 ms/op
                 listUser·p0.95:   9.650 ms/op
                 listUser·p0.99:   12.513 ms/op
                 listUser·p0.999:  30.736 ms/op
                 listUser·p0.9999: 36.668 ms/op
                 listUser·p1.00:   37.159 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 140693
  mean =      6.817 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2 
    [ 2.500,  5.000) = 1776 
    [ 5.000,  7.500) = 112570 
    [ 7.500, 10.000) = 22141 
    [10.000, 12.500) = 3085 
    [12.500, 15.000) = 681 
    [15.000, 17.500) = 110 
    [17.500, 20.000) = 35 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 40 
    [27.500, 30.000) = 57 
    [30.000, 32.500) = 87 
    [32.500, 35.000) = 65 
    [35.000, 37.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      2.392 ms/op
     p(50.0000) =      6.504 ms/op
     p(90.0000) =      8.225 ms/op
     p(95.0000) =      9.175 ms/op
     p(99.0000) =     12.042 ms/op
     p(99.9000) =     30.605 ms/op
     p(99.9900) =     34.791 ms/op
     p(99.9990) =     36.999 ms/op
     p(99.9999) =     37.159 ms/op
    p(100.0000) =     37.159 ms/op


# Run complete. Total time: 00:13:19

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.440 ± 6.103  ops/ms
ClientPb.existUser                       thrpt       3   5.790 ± 0.488  ops/ms
ClientPb.getUser                         thrpt       3   5.314 ± 3.905  ops/ms
ClientPb.listUser                        thrpt       3   4.742 ± 1.674  ops/ms
ClientPb.createUser                       avgt       3   5.698 ± 2.854   ms/op
ClientPb.existUser                        avgt       3   5.664 ± 1.970   ms/op
ClientPb.getUser                          avgt       3   5.725 ± 2.665   ms/op
ClientPb.listUser                         avgt       3   6.797 ± 1.660   ms/op
ClientPb.createUser                     sample  165785   5.787 ± 0.011   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.294           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.456           ms/op
ClientPb.createUser:createUser·p0.90    sample           7.102           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.799           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.715           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.203           ms/op
ClientPb.createUser:createUser·p0.9999  sample          32.725           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.817           ms/op
ClientPb.existUser                      sample  170879   5.612 ± 0.012   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.710           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.300           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.832           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.758           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.945           ms/op
ClientPb.existUser:existUser·p0.999     sample          23.658           ms/op
ClientPb.existUser:existUser·p0.9999    sample          32.667           ms/op
ClientPb.existUser:existUser·p1.00      sample          36.569           ms/op
ClientPb.getUser                        sample  159013   6.032 ± 0.013   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.626           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.751           ms/op
ClientPb.getUser:getUser·p0.90          sample           7.348           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.438           ms/op
ClientPb.getUser:getUser·p0.99          sample          11.878           ms/op
ClientPb.getUser:getUser·p0.999         sample          24.346           ms/op
ClientPb.getUser:getUser·p0.9999        sample          32.709           ms/op
ClientPb.getUser:getUser·p1.00          sample          36.635           ms/op
ClientPb.listUser                       sample  140693   6.817 ± 0.015   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.392           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.504           ms/op
ClientPb.listUser:listUser·p0.90        sample           8.225           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.175           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.042           ms/op
ClientPb.listUser:listUser·p0.999       sample          30.605           ms/op
ClientPb.listUser:listUser·p0.9999      sample          34.791           ms/op
ClientPb.listUser:listUser·p1.00        sample          37.159           ms/op
