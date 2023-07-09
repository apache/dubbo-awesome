# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.951 ops/ms
# Warmup Iteration   2: 4.981 ops/ms
# Warmup Iteration   3: 8.767 ops/ms
Iteration   1: 9.325 ops/ms
Iteration   2: 9.502 ops/ms
Iteration   3: 9.412 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.413 ±(99.9%) 1.617 ops/ms [Average]
  (min, avg, max) = (9.325, 9.413, 9.502), stdev = 0.089
  CI (99.9%): [7.796, 11.030] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.082 ops/ms
# Warmup Iteration   2: 9.038 ops/ms
# Warmup Iteration   3: 9.440 ops/ms
Iteration   1: 9.842 ops/ms
Iteration   2: 10.095 ops/ms
Iteration   3: 9.590 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.842 ±(99.9%) 4.602 ops/ms [Average]
  (min, avg, max) = (9.590, 9.842, 10.095), stdev = 0.252
  CI (99.9%): [5.240, 14.444] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 2.571 ops/ms
# Warmup Iteration   2: 8.107 ops/ms
# Warmup Iteration   3: 8.840 ops/ms
Iteration   1: 8.677 ops/ms
Iteration   2: 9.503 ops/ms
Iteration   3: 9.402 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.194 ±(99.9%) 8.225 ops/ms [Average]
  (min, avg, max) = (8.677, 9.194, 9.503), stdev = 0.451
  CI (99.9%): [0.969, 17.419] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.000 ops/ms
# Warmup Iteration   2: 7.166 ops/ms
# Warmup Iteration   3: 7.651 ops/ms
Iteration   1: 8.001 ops/ms
Iteration   2: 7.914 ops/ms
Iteration   3: 7.922 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.946 ±(99.9%) 0.876 ops/ms [Average]
  (min, avg, max) = (7.914, 7.946, 8.001), stdev = 0.048
  CI (99.9%): [7.070, 8.821] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 8.763 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.804 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.648 ±(99.9%) 0.002 ms/op
Iteration   1: 3.481 ±(99.9%) 0.005 ms/op
Iteration   2: 3.363 ±(99.9%) 0.010 ms/op
Iteration   3: 3.392 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.412 ±(99.9%) 1.128 ms/op [Average]
  (min, avg, max) = (3.363, 3.412, 3.481), stdev = 0.062
  CI (99.9%): [2.284, 4.540] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 10.346 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.688 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.275 ±(99.9%) 0.007 ms/op
Iteration   1: 3.168 ±(99.9%) 0.008 ms/op
Iteration   2: 3.274 ±(99.9%) 0.006 ms/op
Iteration   3: 3.327 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.256 ±(99.9%) 1.484 ms/op [Average]
  (min, avg, max) = (3.168, 3.256, 3.327), stdev = 0.081
  CI (99.9%): [1.773, 4.740] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 9.496 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.778 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.515 ±(99.9%) 0.011 ms/op
Iteration   1: 3.545 ±(99.9%) 0.005 ms/op
Iteration   2: 3.511 ±(99.9%) 0.008 ms/op
Iteration   3: 3.551 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.536 ±(99.9%) 0.401 ms/op [Average]
  (min, avg, max) = (3.511, 3.536, 3.551), stdev = 0.022
  CI (99.9%): [3.135, 3.937] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 11.668 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 4.474 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.987 ±(99.9%) 0.011 ms/op
Iteration   1: 4.019 ±(99.9%) 0.011 ms/op
Iteration   2: 3.863 ±(99.9%) 0.014 ms/op
Iteration   3: 3.902 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.928 ±(99.9%) 1.480 ms/op [Average]
  (min, avg, max) = (3.863, 3.928, 4.019), stdev = 0.081
  CI (99.9%): [2.448, 5.408] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 8.631 ±(99.9%) 0.118 ms/op
# Warmup Iteration   2: 4.285 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 3.575 ±(99.9%) 0.011 ms/op
Iteration   1: 3.360 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.784 ms/op
                 createUser·p0.50:   3.260 ms/op
                 createUser·p0.90:   3.748 ms/op
                 createUser·p0.95:   3.932 ms/op
                 createUser·p0.99:   4.841 ms/op
                 createUser·p0.999:  19.899 ms/op
                 createUser·p0.9999: 22.691 ms/op
                 createUser·p1.00:   23.200 ms/op

Iteration   2: 3.536 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.669 ms/op
                 createUser·p0.50:   3.428 ms/op
                 createUser·p0.90:   4.043 ms/op
                 createUser·p0.95:   4.506 ms/op
                 createUser·p0.99:   6.234 ms/op
                 createUser·p0.999:  23.193 ms/op
                 createUser·p0.9999: 26.830 ms/op
                 createUser·p1.00:   27.623 ms/op

Iteration   3: 3.547 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.332 ms/op
                 createUser·p0.50:   3.469 ms/op
                 createUser·p0.90:   4.018 ms/op
                 createUser·p0.95:   4.260 ms/op
                 createUser·p0.99:   5.773 ms/op
                 createUser·p0.999:  23.265 ms/op
                 createUser·p0.9999: 27.492 ms/op
                 createUser·p1.00:   30.835 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 275790
  mean =      3.479 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7140 
    [ 2.500,  5.000) = 263273 
    [ 5.000,  7.500) = 4303 
    [ 7.500, 10.000) = 696 
    [10.000, 12.500) = 51 
    [12.500, 15.000) = 7 
    [15.000, 17.500) = 15 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 80 
    [22.500, 25.000) = 114 
    [25.000, 27.500) = 80 
    [27.500, 30.000) = 7 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.332 ms/op
     p(50.0000) =      3.412 ms/op
     p(90.0000) =      3.920 ms/op
     p(95.0000) =      4.211 ms/op
     p(99.0000) =      5.801 ms/op
     p(99.9000) =     20.159 ms/op
     p(99.9900) =     26.673 ms/op
     p(99.9990) =     30.118 ms/op
     p(99.9999) =     30.835 ms/op
    p(100.0000) =     30.835 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.786 ±(99.9%) 0.105 ms/op
# Warmup Iteration   2: 3.562 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.376 ±(99.9%) 0.008 ms/op
Iteration   1: 3.302 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.239 ms/op
                 existUser·p0.50:   3.215 ms/op
                 existUser·p0.90:   3.613 ms/op
                 existUser·p0.95:   3.801 ms/op
                 existUser·p0.99:   5.530 ms/op
                 existUser·p0.999:  8.702 ms/op
                 existUser·p0.9999: 22.720 ms/op
                 existUser·p1.00:   23.921 ms/op

Iteration   2: 3.311 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.493 ms/op
                 existUser·p0.50:   3.265 ms/op
                 existUser·p0.90:   3.473 ms/op
                 existUser·p0.95:   3.711 ms/op
                 existUser·p0.99:   5.816 ms/op
                 existUser·p0.999:  16.773 ms/op
                 existUser·p0.9999: 25.952 ms/op
                 existUser·p1.00:   26.870 ms/op

Iteration   3: 3.449 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.593 ms/op
                 existUser·p0.50:   3.322 ms/op
                 existUser·p0.90:   3.953 ms/op
                 existUser·p0.95:   4.293 ms/op
                 existUser·p0.99:   6.324 ms/op
                 existUser·p0.999:  17.316 ms/op
                 existUser·p0.9999: 26.673 ms/op
                 existUser·p1.00:   26.968 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 286091
  mean =      3.353 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8491 
    [ 2.500,  5.000) = 272271 
    [ 5.000,  7.500) = 4301 
    [ 7.500, 10.000) = 609 
    [10.000, 12.500) = 103 
    [12.500, 15.000) = 58 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 83 
    [22.500, 25.000) = 64 
    [25.000, 27.500) = 80 

  Percentiles, ms/op:
      p(0.0000) =      1.239 ms/op
     p(50.0000) =      3.265 ms/op
     p(90.0000) =      3.674 ms/op
     p(95.0000) =      4.002 ms/op
     p(99.0000) =      5.882 ms/op
     p(99.9000) =     13.173 ms/op
     p(99.9900) =     26.444 ms/op
     p(99.9990) =     26.903 ms/op
     p(99.9999) =     26.968 ms/op
    p(100.0000) =     26.968 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 9.109 ±(99.9%) 0.137 ms/op
# Warmup Iteration   2: 3.686 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.393 ±(99.9%) 0.009 ms/op
Iteration   1: 3.461 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.167 ms/op
                 getUser·p0.50:   3.281 ms/op
                 getUser·p0.90:   3.727 ms/op
                 getUser·p0.95:   4.395 ms/op
                 getUser·p0.99:   6.832 ms/op
                 getUser·p0.999:  18.855 ms/op
                 getUser·p0.9999: 22.463 ms/op
                 getUser·p1.00:   23.036 ms/op

Iteration   2: 3.465 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.130 ms/op
                 getUser·p0.50:   3.330 ms/op
                 getUser·p0.90:   3.903 ms/op
                 getUser·p0.95:   4.243 ms/op
                 getUser·p0.99:   6.144 ms/op
                 getUser·p0.999:  19.452 ms/op
                 getUser·p0.9999: 21.882 ms/op
                 getUser·p1.00:   22.774 ms/op

Iteration   3: 3.424 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.403 ms/op
                 getUser·p0.50:   3.277 ms/op
                 getUser·p0.90:   3.789 ms/op
                 getUser·p0.95:   4.035 ms/op
                 getUser·p0.99:   6.472 ms/op
                 getUser·p0.999:  15.062 ms/op
                 getUser·p0.9999: 23.396 ms/op
                 getUser·p1.00:   24.904 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 278219
  mean =      3.450 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2712 
    [ 2.500,  5.000) = 266776 
    [ 5.000,  7.500) = 7373 
    [ 7.500, 10.000) = 786 
    [10.000, 12.500) = 178 
    [12.500, 15.000) = 40 
    [15.000, 17.500) = 87 
    [17.500, 20.000) = 83 
    [20.000, 22.500) = 158 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.130 ms/op
     p(50.0000) =      3.293 ms/op
     p(90.0000) =      3.817 ms/op
     p(95.0000) =      4.174 ms/op
     p(99.0000) =      6.603 ms/op
     p(99.9000) =     17.302 ms/op
     p(99.9900) =     22.365 ms/op
     p(99.9990) =     23.745 ms/op
     p(99.9999) =     24.904 ms/op
    p(100.0000) =     24.904 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 11.054 ±(99.9%) 0.153 ms/op
# Warmup Iteration   2: 4.415 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.086 ±(99.9%) 0.013 ms/op
Iteration   1: 3.990 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.274 ms/op
                 listUser·p0.50:   3.879 ms/op
                 listUser·p0.90:   4.227 ms/op
                 listUser·p0.95:   4.628 ms/op
                 listUser·p0.99:   7.889 ms/op
                 listUser·p0.999:  18.285 ms/op
                 listUser·p0.9999: 23.429 ms/op
                 listUser·p1.00:   24.248 ms/op

Iteration   2: 4.018 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.179 ms/op
                 listUser·p0.50:   3.871 ms/op
                 listUser·p0.90:   4.391 ms/op
                 listUser·p0.95:   4.596 ms/op
                 listUser·p0.99:   6.791 ms/op
                 listUser·p0.999:  15.016 ms/op
                 listUser·p0.9999: 17.500 ms/op
                 listUser·p1.00:   20.021 ms/op

Iteration   3: 4.027 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.241 ms/op
                 listUser·p0.50:   3.912 ms/op
                 listUser·p0.90:   4.366 ms/op
                 listUser·p0.95:   4.579 ms/op
                 listUser·p0.99:   6.988 ms/op
                 listUser·p0.999:  14.926 ms/op
                 listUser·p0.9999: 18.874 ms/op
                 listUser·p1.00:   18.940 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 238988
  mean =      4.012 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 34 
    [ 2.500,  5.000) = 231714 
    [ 5.000,  7.500) = 5182 
    [ 7.500, 10.000) = 1150 
    [10.000, 12.500) = 341 
    [12.500, 15.000) = 250 
    [15.000, 17.500) = 150 
    [17.500, 20.000) = 102 
    [20.000, 22.500) = 41 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.274 ms/op
     p(50.0000) =      3.883 ms/op
     p(90.0000) =      4.350 ms/op
     p(95.0000) =      4.596 ms/op
     p(99.0000) =      7.078 ms/op
     p(99.9000) =     15.696 ms/op
     p(99.9900) =     22.515 ms/op
     p(99.9990) =     24.068 ms/op
     p(99.9999) =     24.248 ms/op
    p(100.0000) =     24.248 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.413 ± 1.617  ops/ms
ClientPb.existUser                       thrpt       3   9.842 ± 4.602  ops/ms
ClientPb.getUser                         thrpt       3   9.194 ± 8.225  ops/ms
ClientPb.listUser                        thrpt       3   7.946 ± 0.876  ops/ms
ClientPb.createUser                       avgt       3   3.412 ± 1.128   ms/op
ClientPb.existUser                        avgt       3   3.256 ± 1.484   ms/op
ClientPb.getUser                          avgt       3   3.536 ± 0.401   ms/op
ClientPb.listUser                         avgt       3   3.928 ± 1.480   ms/op
ClientPb.createUser                     sample  275790   3.479 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.332           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.412           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.920           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.211           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.801           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.159           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.673           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.835           ms/op
ClientPb.existUser                      sample  286091   3.353 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.239           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.265           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.674           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.002           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.882           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.173           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.444           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.968           ms/op
ClientPb.getUser                        sample  278219   3.450 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.130           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.293           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.817           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.174           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.603           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.302           ms/op
ClientPb.getUser:getUser·p0.9999        sample          22.365           ms/op
ClientPb.getUser:getUser·p1.00          sample          24.904           ms/op
ClientPb.listUser                       sample  238988   4.012 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.274           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.883           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.350           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.596           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.078           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.696           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.515           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.248           ms/op
