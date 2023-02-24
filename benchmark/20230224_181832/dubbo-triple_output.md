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
# Warmup Iteration   1: 2.576 ops/ms
# Warmup Iteration   2: 6.151 ops/ms
# Warmup Iteration   3: 9.517 ops/ms
Iteration   1: 10.149 ops/ms
Iteration   2: 9.758 ops/ms
Iteration   3: 10.017 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.975 ±(99.9%) 3.630 ops/ms [Average]
  (min, avg, max) = (9.758, 9.975, 10.149), stdev = 0.199
  CI (99.9%): [6.345, 13.605] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 3.882 ops/ms
# Warmup Iteration   2: 9.321 ops/ms
# Warmup Iteration   3: 10.390 ops/ms
Iteration   1: 9.988 ops/ms
Iteration   2: 10.633 ops/ms
Iteration   3: 10.345 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.322 ±(99.9%) 5.900 ops/ms [Average]
  (min, avg, max) = (9.988, 10.322, 10.633), stdev = 0.323
  CI (99.9%): [4.422, 16.222] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.339 ops/ms
# Warmup Iteration   2: 9.881 ops/ms
# Warmup Iteration   3: 9.421 ops/ms
Iteration   1: 10.050 ops/ms
Iteration   2: 10.030 ops/ms
Iteration   3: 10.183 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.088 ±(99.9%) 1.523 ops/ms [Average]
  (min, avg, max) = (10.030, 10.088, 10.183), stdev = 0.083
  CI (99.9%): [8.565, 11.611] (assumes normal distribution)


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
# Warmup Iteration   1: 3.240 ops/ms
# Warmup Iteration   2: 7.722 ops/ms
# Warmup Iteration   3: 8.190 ops/ms
Iteration   1: 8.620 ops/ms
Iteration   2: 8.667 ops/ms
Iteration   3: 8.493 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.593 ±(99.9%) 1.639 ops/ms [Average]
  (min, avg, max) = (8.493, 8.593, 8.667), stdev = 0.090
  CI (99.9%): [6.954, 10.233] (assumes normal distribution)


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
# Warmup Iteration   1: 8.682 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.501 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.365 ±(99.9%) 0.005 ms/op
Iteration   1: 3.081 ±(99.9%) 0.004 ms/op
Iteration   2: 3.277 ±(99.9%) 0.005 ms/op
Iteration   3: 3.278 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.212 ±(99.9%) 2.070 ms/op [Average]
  (min, avg, max) = (3.081, 3.212, 3.278), stdev = 0.113
  CI (99.9%): [1.142, 5.282] (assumes normal distribution)


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
# Warmup Iteration   1: 8.000 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.360 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.090 ±(99.9%) 0.004 ms/op
Iteration   1: 2.996 ±(99.9%) 0.003 ms/op
Iteration   2: 2.993 ±(99.9%) 0.005 ms/op
Iteration   3: 3.120 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.037 ±(99.9%) 1.326 ms/op [Average]
  (min, avg, max) = (2.993, 3.037, 3.120), stdev = 0.073
  CI (99.9%): [1.710, 4.363] (assumes normal distribution)


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
# Warmup Iteration   1: 7.699 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.406 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.230 ±(99.9%) 0.002 ms/op
Iteration   1: 3.135 ±(99.9%) 0.003 ms/op
Iteration   2: 3.160 ±(99.9%) 0.005 ms/op
Iteration   3: 3.127 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.141 ±(99.9%) 0.315 ms/op [Average]
  (min, avg, max) = (3.127, 3.141, 3.160), stdev = 0.017
  CI (99.9%): [2.826, 3.455] (assumes normal distribution)


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
# Warmup Iteration   1: 8.600 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 4.052 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.804 ±(99.9%) 0.009 ms/op
Iteration   1: 3.605 ±(99.9%) 0.011 ms/op
Iteration   2: 3.648 ±(99.9%) 0.007 ms/op
Iteration   3: 3.609 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.621 ±(99.9%) 0.436 ms/op [Average]
  (min, avg, max) = (3.605, 3.621, 3.648), stdev = 0.024
  CI (99.9%): [3.185, 4.057] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 7.594 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 3.562 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.148 ±(99.9%) 0.009 ms/op
Iteration   1: 3.150 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.001 ms/op
                 createUser·p0.50:   3.146 ms/op
                 createUser·p0.90:   3.367 ms/op
                 createUser·p0.95:   3.715 ms/op
                 createUser·p0.99:   5.177 ms/op
                 createUser·p0.999:  10.294 ms/op
                 createUser·p0.9999: 21.032 ms/op
                 createUser·p1.00:   21.496 ms/op

Iteration   2: 3.272 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.509 ms/op
                 createUser·p0.50:   3.187 ms/op
                 createUser·p0.90:   3.731 ms/op
                 createUser·p0.95:   4.080 ms/op
                 createUser·p0.99:   5.956 ms/op
                 createUser·p0.999:  19.800 ms/op
                 createUser·p0.9999: 23.740 ms/op
                 createUser·p1.00:   28.639 ms/op

Iteration   3: 3.073 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.663 ms/op
                 createUser·p0.50:   3.043 ms/op
                 createUser·p0.90:   3.326 ms/op
                 createUser·p0.95:   3.551 ms/op
                 createUser·p0.99:   5.041 ms/op
                 createUser·p0.999:  9.749 ms/op
                 createUser·p0.9999: 20.972 ms/op
                 createUser·p1.00:   22.053 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 303233
  mean =      3.163 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24591 
    [ 2.500,  5.000) = 273354 
    [ 5.000,  7.500) = 4481 
    [ 7.500, 10.000) = 463 
    [10.000, 12.500) = 24 
    [12.500, 15.000) = 18 
    [15.000, 17.500) = 38 
    [17.500, 20.000) = 112 
    [20.000, 22.500) = 118 
    [22.500, 25.000) = 33 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.001 ms/op
     p(50.0000) =      3.121 ms/op
     p(90.0000) =      3.514 ms/op
     p(95.0000) =      3.805 ms/op
     p(99.0000) =      5.472 ms/op
     p(99.9000) =     14.303 ms/op
     p(99.9900) =     22.611 ms/op
     p(99.9990) =     24.870 ms/op
     p(99.9999) =     28.639 ms/op
    p(100.0000) =     28.639 ms/op


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
# Warmup Iteration   1: 8.090 ±(99.9%) 0.084 ms/op
# Warmup Iteration   2: 3.328 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.107 ±(99.9%) 0.007 ms/op
Iteration   1: 3.083 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.374 ms/op
                 existUser·p0.50:   3.097 ms/op
                 existUser·p0.90:   3.244 ms/op
                 existUser·p0.95:   3.396 ms/op
                 existUser·p0.99:   5.235 ms/op
                 existUser·p0.999:  8.536 ms/op
                 existUser·p0.9999: 19.366 ms/op
                 existUser·p1.00:   20.480 ms/op

Iteration   2: 2.964 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.098 ms/op
                 existUser·p0.50:   2.904 ms/op
                 existUser·p0.90:   3.129 ms/op
                 existUser·p0.95:   3.285 ms/op
                 existUser·p0.99:   4.194 ms/op
                 existUser·p0.999:  10.979 ms/op
                 existUser·p0.9999: 23.724 ms/op
                 existUser·p1.00:   24.609 ms/op

Iteration   3: 3.050 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.829 ms/op
                 existUser·p0.50:   3.015 ms/op
                 existUser·p0.90:   3.244 ms/op
                 existUser·p0.95:   3.420 ms/op
                 existUser·p0.99:   5.456 ms/op
                 existUser·p0.999:  10.767 ms/op
                 existUser·p0.9999: 18.433 ms/op
                 existUser·p1.00:   19.431 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 316450
  mean =      3.032 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21518 
    [ 2.500,  5.000) = 290691 
    [ 5.000,  7.500) = 3581 
    [ 7.500, 10.000) = 313 
    [10.000, 12.500) = 50 
    [12.500, 15.000) = 35 
    [15.000, 17.500) = 50 
    [17.500, 20.000) = 137 
    [20.000, 22.500) = 42 
    [22.500, 25.000) = 33 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.829 ms/op
     p(50.0000) =      3.002 ms/op
     p(90.0000) =      3.219 ms/op
     p(95.0000) =      3.367 ms/op
     p(99.0000) =      5.186 ms/op
     p(99.9000) =     10.928 ms/op
     p(99.9900) =     22.633 ms/op
     p(99.9990) =     24.041 ms/op
     p(99.9999) =     24.609 ms/op
    p(100.0000) =     24.609 ms/op


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
# Warmup Iteration   1: 8.414 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 3.522 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.136 ±(99.9%) 0.008 ms/op
Iteration   1: 3.252 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.153 ms/op
                 getUser·p0.50:   3.072 ms/op
                 getUser·p0.90:   3.727 ms/op
                 getUser·p0.95:   4.735 ms/op
                 getUser·p0.99:   6.308 ms/op
                 getUser·p0.999:  16.687 ms/op
                 getUser·p0.9999: 19.993 ms/op
                 getUser·p1.00:   21.004 ms/op

Iteration   2: 3.131 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.403 ms/op
                 getUser·p0.50:   3.015 ms/op
                 getUser·p0.90:   3.355 ms/op
                 getUser·p0.95:   3.613 ms/op
                 getUser·p0.99:   5.792 ms/op
                 getUser·p0.999:  19.230 ms/op
                 getUser·p0.9999: 26.994 ms/op
                 getUser·p1.00:   27.492 ms/op

Iteration   3: 3.201 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.260 ms/op
                 getUser·p0.50:   3.150 ms/op
                 getUser·p0.90:   3.572 ms/op
                 getUser·p0.95:   4.194 ms/op
                 getUser·p0.99:   5.800 ms/op
                 getUser·p0.999:  10.846 ms/op
                 getUser·p0.9999: 19.202 ms/op
                 getUser·p1.00:   19.595 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 300524
  mean =      3.194 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10636 
    [ 2.500,  5.000) = 280426 
    [ 5.000,  7.500) = 8417 
    [ 7.500, 10.000) = 554 
    [10.000, 12.500) = 150 
    [12.500, 15.000) = 57 
    [15.000, 17.500) = 42 
    [17.500, 20.000) = 150 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 36 

  Percentiles, ms/op:
      p(0.0000) =      1.153 ms/op
     p(50.0000) =      3.080 ms/op
     p(90.0000) =      3.510 ms/op
     p(95.0000) =      4.252 ms/op
     p(99.0000) =      6.070 ms/op
     p(99.9000) =     14.025 ms/op
     p(99.9900) =     25.645 ms/op
     p(99.9990) =     27.328 ms/op
     p(99.9999) =     27.492 ms/op
    p(100.0000) =     27.492 ms/op


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
# Warmup Iteration   1: 8.809 ±(99.9%) 0.109 ms/op
# Warmup Iteration   2: 4.080 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.853 ±(99.9%) 0.013 ms/op
Iteration   1: 3.738 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.896 ms/op
                 listUser·p0.50:   3.670 ms/op
                 listUser·p0.90:   4.002 ms/op
                 listUser·p0.95:   4.252 ms/op
                 listUser·p0.99:   6.701 ms/op
                 listUser·p0.999:  13.468 ms/op
                 listUser·p0.9999: 20.101 ms/op
                 listUser·p1.00:   21.660 ms/op

Iteration   2: 3.713 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.550 ms/op
                 listUser·p0.50:   3.625 ms/op
                 listUser·p0.90:   3.985 ms/op
                 listUser·p0.95:   4.350 ms/op
                 listUser·p0.99:   6.709 ms/op
                 listUser·p0.999:  13.808 ms/op
                 listUser·p0.9999: 16.702 ms/op
                 listUser·p1.00:   20.087 ms/op

Iteration   3: 3.668 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.183 ms/op
                 listUser·p0.50:   3.547 ms/op
                 listUser·p0.90:   3.961 ms/op
                 listUser·p0.95:   4.121 ms/op
                 listUser·p0.99:   6.832 ms/op
                 listUser·p0.999:  13.271 ms/op
                 listUser·p0.9999: 18.219 ms/op
                 listUser·p1.00:   18.514 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 258764
  mean =      3.706 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 56 
    [ 2.500,  5.000) = 251915 
    [ 5.000,  7.500) = 5145 
    [ 7.500, 10.000) = 969 
    [10.000, 12.500) = 305 
    [12.500, 15.000) = 200 
    [15.000, 17.500) = 97 
    [17.500, 20.000) = 66 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.550 ms/op
     p(50.0000) =      3.617 ms/op
     p(90.0000) =      3.981 ms/op
     p(95.0000) =      4.227 ms/op
     p(99.0000) =      6.734 ms/op
     p(99.9000) =     13.402 ms/op
     p(99.9900) =     18.903 ms/op
     p(99.9990) =     21.369 ms/op
     p(99.9999) =     21.660 ms/op
    p(100.0000) =     21.660 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.975 ± 3.630  ops/ms
ClientPb.existUser                       thrpt       3  10.322 ± 5.900  ops/ms
ClientPb.getUser                         thrpt       3  10.088 ± 1.523  ops/ms
ClientPb.listUser                        thrpt       3   8.593 ± 1.639  ops/ms
ClientPb.createUser                       avgt       3   3.212 ± 2.070   ms/op
ClientPb.existUser                        avgt       3   3.037 ± 1.326   ms/op
ClientPb.getUser                          avgt       3   3.141 ± 0.315   ms/op
ClientPb.listUser                         avgt       3   3.621 ± 0.436   ms/op
ClientPb.createUser                     sample  303233   3.163 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.001           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.121           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.514           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.805           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.472           ms/op
ClientPb.createUser:createUser·p0.999   sample          14.303           ms/op
ClientPb.createUser:createUser·p0.9999  sample          22.611           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.639           ms/op
ClientPb.existUser                      sample  316450   3.032 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.829           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.002           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.219           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.367           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.186           ms/op
ClientPb.existUser:existUser·p0.999     sample          10.928           ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.633           ms/op
ClientPb.existUser:existUser·p1.00      sample          24.609           ms/op
ClientPb.getUser                        sample  300524   3.194 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.153           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.080           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.510           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.252           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.070           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.025           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.645           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.492           ms/op
ClientPb.listUser                       sample  258764   3.706 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.550           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.617           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.981           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.227           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.734           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.402           ms/op
ClientPb.listUser:listUser·p0.9999      sample          18.903           ms/op
ClientPb.listUser:listUser·p1.00        sample          21.660           ms/op
