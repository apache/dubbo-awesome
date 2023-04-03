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
# Warmup Iteration   1: 2.483 ops/ms
# Warmup Iteration   2: 6.069 ops/ms
# Warmup Iteration   3: 9.176 ops/ms
Iteration   1: 10.082 ops/ms
Iteration   2: 9.774 ops/ms
Iteration   3: 9.588 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.815 ±(99.9%) 4.554 ops/ms [Average]
  (min, avg, max) = (9.588, 9.815, 10.082), stdev = 0.250
  CI (99.9%): [5.261, 14.369] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.513 ops/ms
# Warmup Iteration   2: 8.369 ops/ms
# Warmup Iteration   3: 10.179 ops/ms
Iteration   1: 10.533 ops/ms
Iteration   2: 10.749 ops/ms
Iteration   3: 10.175 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.486 ±(99.9%) 5.293 ops/ms [Average]
  (min, avg, max) = (10.175, 10.486, 10.749), stdev = 0.290
  CI (99.9%): [5.192, 15.779] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.563 ops/ms
# Warmup Iteration   2: 8.846 ops/ms
# Warmup Iteration   3: 9.569 ops/ms
Iteration   1: 9.997 ops/ms
Iteration   2: 10.152 ops/ms
Iteration   3: 10.122 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.091 ±(99.9%) 1.502 ops/ms [Average]
  (min, avg, max) = (9.997, 10.091, 10.152), stdev = 0.082
  CI (99.9%): [8.589, 11.592] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.147 ops/ms
# Warmup Iteration   2: 7.954 ops/ms
# Warmup Iteration   3: 8.540 ops/ms
Iteration   1: 8.651 ops/ms
Iteration   2: 8.526 ops/ms
Iteration   3: 8.601 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.592 ±(99.9%) 1.148 ops/ms [Average]
  (min, avg, max) = (8.526, 8.592, 8.651), stdev = 0.063
  CI (99.9%): [7.444, 9.740] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 7.966 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.555 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.471 ±(99.9%) 0.005 ms/op
Iteration   1: 3.318 ±(99.9%) 0.008 ms/op
Iteration   2: 3.361 ±(99.9%) 0.003 ms/op
Iteration   3: 3.359 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.346 ±(99.9%) 0.445 ms/op [Average]
  (min, avg, max) = (3.318, 3.346, 3.361), stdev = 0.024
  CI (99.9%): [2.901, 3.791] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 7.757 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.184 ±(99.9%) 0.001 ms/op
# Warmup Iteration   3: 3.127 ±(99.9%) 0.005 ms/op
Iteration   1: 3.131 ±(99.9%) 0.005 ms/op
Iteration   2: 3.123 ±(99.9%) 0.003 ms/op
Iteration   3: 3.206 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.154 ±(99.9%) 0.837 ms/op [Average]
  (min, avg, max) = (3.123, 3.154, 3.206), stdev = 0.046
  CI (99.9%): [2.317, 3.991] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 7.993 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.434 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.593 ±(99.9%) 0.005 ms/op
Iteration   1: 3.149 ±(99.9%) 0.008 ms/op
Iteration   2: 3.299 ±(99.9%) 0.004 ms/op
Iteration   3: 3.165 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.204 ±(99.9%) 1.502 ms/op [Average]
  (min, avg, max) = (3.149, 3.204, 3.299), stdev = 0.082
  CI (99.9%): [1.702, 4.706] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 9.835 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 4.308 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.955 ±(99.9%) 0.006 ms/op
Iteration   1: 3.632 ±(99.9%) 0.013 ms/op
Iteration   2: 3.825 ±(99.9%) 0.006 ms/op
Iteration   3: 3.667 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.708 ±(99.9%) 1.879 ms/op [Average]
  (min, avg, max) = (3.632, 3.708, 3.825), stdev = 0.103
  CI (99.9%): [1.829, 5.588] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 8.542 ±(99.9%) 0.101 ms/op
# Warmup Iteration   2: 3.637 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.367 ±(99.9%) 0.009 ms/op
Iteration   1: 3.257 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.532 ms/op
                 createUser·p0.50:   3.203 ms/op
                 createUser·p0.90:   3.641 ms/op
                 createUser·p0.95:   4.293 ms/op
                 createUser·p0.99:   5.423 ms/op
                 createUser·p0.999:  9.931 ms/op
                 createUser·p0.9999: 20.387 ms/op
                 createUser·p1.00:   20.808 ms/op

Iteration   2: 3.344 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.159 ms/op
                 createUser·p0.50:   3.281 ms/op
                 createUser·p0.90:   3.768 ms/op
                 createUser·p0.95:   4.085 ms/op
                 createUser·p0.99:   5.595 ms/op
                 createUser·p0.999:  20.340 ms/op
                 createUser·p0.9999: 23.209 ms/op
                 createUser·p1.00:   25.002 ms/op

Iteration   3: 3.159 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.325 ms/op
                 createUser·p0.50:   3.158 ms/op
                 createUser·p0.90:   3.346 ms/op
                 createUser·p0.95:   3.629 ms/op
                 createUser·p0.99:   5.186 ms/op
                 createUser·p0.999:  16.575 ms/op
                 createUser·p0.9999: 20.639 ms/op
                 createUser·p1.00:   21.070 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 295364
  mean =      3.251 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22758 
    [ 2.500,  5.000) = 266942 
    [ 5.000,  7.500) = 4930 
    [ 7.500, 10.000) = 326 
    [10.000, 12.500) = 29 
    [12.500, 15.000) = 41 
    [15.000, 17.500) = 50 
    [17.500, 20.000) = 143 
    [20.000, 22.500) = 120 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.159 ms/op
     p(50.0000) =      3.211 ms/op
     p(90.0000) =      3.617 ms/op
     p(95.0000) =      3.998 ms/op
     p(99.0000) =      5.374 ms/op
     p(99.9000) =     17.007 ms/op
     p(99.9900) =     22.413 ms/op
     p(99.9990) =     24.424 ms/op
     p(99.9999) =     25.002 ms/op
    p(100.0000) =     25.002 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.299 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 3.456 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.134 ±(99.9%) 0.007 ms/op
Iteration   1: 3.109 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.200 ms/op
                 existUser·p0.50:   3.109 ms/op
                 existUser·p0.90:   3.277 ms/op
                 existUser·p0.95:   3.527 ms/op
                 existUser·p0.99:   5.267 ms/op
                 existUser·p0.999:  11.932 ms/op
                 existUser·p0.9999: 20.111 ms/op
                 existUser·p1.00:   20.447 ms/op

Iteration   2: 3.020 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.262 ms/op
                 existUser·p0.50:   2.970 ms/op
                 existUser·p0.90:   3.203 ms/op
                 existUser·p0.95:   3.371 ms/op
                 existUser·p0.99:   4.501 ms/op
                 existUser·p0.999:  11.502 ms/op
                 existUser·p0.9999: 23.495 ms/op
                 existUser·p1.00:   24.543 ms/op

Iteration   3: 3.133 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.984 ms/op
                 existUser·p0.50:   3.109 ms/op
                 existUser·p0.90:   3.375 ms/op
                 existUser·p0.95:   3.580 ms/op
                 existUser·p0.99:   5.251 ms/op
                 existUser·p0.999:  11.726 ms/op
                 existUser·p0.9999: 20.997 ms/op
                 existUser·p1.00:   21.496 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 310771
  mean =      3.087 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23839 
    [ 2.500,  5.000) = 283133 
    [ 5.000,  7.500) = 3113 
    [ 7.500, 10.000) = 231 
    [10.000, 12.500) = 158 
    [12.500, 15.000) = 37 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 126 
    [20.000, 22.500) = 104 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.984 ms/op
     p(50.0000) =      3.076 ms/op
     p(90.0000) =      3.310 ms/op
     p(95.0000) =      3.486 ms/op
     p(99.0000) =      5.202 ms/op
     p(99.9000) =     11.693 ms/op
     p(99.9900) =     22.275 ms/op
     p(99.9990) =     24.471 ms/op
     p(99.9999) =     24.543 ms/op
    p(100.0000) =     24.543 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 8.564 ±(99.9%) 0.089 ms/op
# Warmup Iteration   2: 3.566 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.207 ±(99.9%) 0.009 ms/op
Iteration   1: 3.344 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.176 ms/op
                 getUser·p0.50:   3.195 ms/op
                 getUser·p0.90:   3.850 ms/op
                 getUser·p0.95:   4.538 ms/op
                 getUser·p0.99:   6.603 ms/op
                 getUser·p0.999:  16.920 ms/op
                 getUser·p0.9999: 19.937 ms/op
                 getUser·p1.00:   20.742 ms/op

Iteration   2: 3.160 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.450 ms/op
                 getUser·p0.50:   3.080 ms/op
                 getUser·p0.90:   3.490 ms/op
                 getUser·p0.95:   3.686 ms/op
                 getUser·p0.99:   5.226 ms/op
                 getUser·p0.999:  9.721 ms/op
                 getUser·p0.9999: 26.833 ms/op
                 getUser·p1.00:   27.754 ms/op

Iteration   3: 3.194 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.315 ms/op
                 getUser·p0.50:   3.105 ms/op
                 getUser·p0.90:   3.510 ms/op
                 getUser·p0.95:   3.846 ms/op
                 getUser·p0.99:   5.734 ms/op
                 getUser·p0.999:  10.273 ms/op
                 getUser·p0.9999: 21.036 ms/op
                 getUser·p1.00:   22.086 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 297061
  mean =      3.231 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14463 
    [ 2.500,  5.000) = 275332 
    [ 5.000,  7.500) = 6320 
    [ 7.500, 10.000) = 597 
    [10.000, 12.500) = 58 
    [12.500, 15.000) = 35 
    [15.000, 17.500) = 15 
    [17.500, 20.000) = 117 
    [20.000, 22.500) = 87 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 24 

  Percentiles, ms/op:
      p(0.0000) =      1.176 ms/op
     p(50.0000) =      3.121 ms/op
     p(90.0000) =      3.613 ms/op
     p(95.0000) =      3.998 ms/op
     p(99.0000) =      6.095 ms/op
     p(99.9000) =     10.551 ms/op
     p(99.9900) =     24.825 ms/op
     p(99.9990) =     27.493 ms/op
     p(99.9999) =     27.754 ms/op
    p(100.0000) =     27.754 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 8.864 ±(99.9%) 0.108 ms/op
# Warmup Iteration   2: 4.187 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.821 ±(99.9%) 0.012 ms/op
Iteration   1: 3.676 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.675 ms/op
                 listUser·p0.50:   3.617 ms/op
                 listUser·p0.90:   3.842 ms/op
                 listUser·p0.95:   4.129 ms/op
                 listUser·p0.99:   6.726 ms/op
                 listUser·p0.999:  15.614 ms/op
                 listUser·p0.9999: 26.804 ms/op
                 listUser·p1.00:   26.837 ms/op

Iteration   2: 3.753 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.351 ms/op
                 listUser·p0.50:   3.641 ms/op
                 listUser·p0.90:   3.977 ms/op
                 listUser·p0.95:   4.153 ms/op
                 listUser·p0.99:   7.193 ms/op
                 listUser·p0.999:  17.826 ms/op
                 listUser·p0.9999: 20.677 ms/op
                 listUser·p1.00:   21.332 ms/op

Iteration   3: 3.784 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.788 ms/op
                 listUser·p0.50:   3.625 ms/op
                 listUser·p0.90:   4.071 ms/op
                 listUser·p0.95:   4.301 ms/op
                 listUser·p0.99:   7.979 ms/op
                 listUser·p0.999:  12.804 ms/op
                 listUser·p0.9999: 15.729 ms/op
                 listUser·p1.00:   16.105 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 256728
  mean =      3.737 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20 
    [ 2.500,  5.000) = 250168 
    [ 5.000,  7.500) = 4115 
    [ 7.500, 10.000) = 1733 
    [10.000, 12.500) = 249 
    [12.500, 15.000) = 180 
    [15.000, 17.500) = 100 
    [17.500, 20.000) = 97 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      1.675 ms/op
     p(50.0000) =      3.625 ms/op
     p(90.0000) =      3.998 ms/op
     p(95.0000) =      4.194 ms/op
     p(99.0000) =      7.370 ms/op
     p(99.9000) =     15.385 ms/op
     p(99.9900) =     25.919 ms/op
     p(99.9990) =     26.804 ms/op
     p(99.9999) =     26.837 ms/op
    p(100.0000) =     26.837 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.815 ± 4.554  ops/ms
ClientPb.existUser                       thrpt       3  10.486 ± 5.293  ops/ms
ClientPb.getUser                         thrpt       3  10.091 ± 1.502  ops/ms
ClientPb.listUser                        thrpt       3   8.592 ± 1.148  ops/ms
ClientPb.createUser                       avgt       3   3.346 ± 0.445   ms/op
ClientPb.existUser                        avgt       3   3.154 ± 0.837   ms/op
ClientPb.getUser                          avgt       3   3.204 ± 1.502   ms/op
ClientPb.listUser                         avgt       3   3.708 ± 1.879   ms/op
ClientPb.createUser                     sample  295364   3.251 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.159           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.211           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.617           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.998           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.374           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.007           ms/op
ClientPb.createUser:createUser·p0.9999  sample          22.413           ms/op
ClientPb.createUser:createUser·p1.00    sample          25.002           ms/op
ClientPb.existUser                      sample  310771   3.087 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.984           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.076           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.310           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.486           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.202           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.693           ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.275           ms/op
ClientPb.existUser:existUser·p1.00      sample          24.543           ms/op
ClientPb.getUser                        sample  297061   3.231 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.176           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.121           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.613           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.998           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.095           ms/op
ClientPb.getUser:getUser·p0.999         sample          10.551           ms/op
ClientPb.getUser:getUser·p0.9999        sample          24.825           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.754           ms/op
ClientPb.listUser                       sample  256728   3.737 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.675           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.625           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.998           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.194           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.370           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.385           ms/op
ClientPb.listUser:listUser·p0.9999      sample          25.919           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.837           ms/op
