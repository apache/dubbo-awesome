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
# Warmup Iteration   1: 2.685 ops/ms
# Warmup Iteration   2: 7.138 ops/ms
# Warmup Iteration   3: 9.039 ops/ms
Iteration   1: 9.839 ops/ms
Iteration   2: 10.058 ops/ms
Iteration   3: 10.085 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.994 ±(99.9%) 2.467 ops/ms [Average]
  (min, avg, max) = (9.839, 9.994, 10.085), stdev = 0.135
  CI (99.9%): [7.527, 12.461] (assumes normal distribution)


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
# Warmup Iteration   1: 3.479 ops/ms
# Warmup Iteration   2: 9.477 ops/ms
# Warmup Iteration   3: 9.989 ops/ms
Iteration   1: 10.595 ops/ms
Iteration   2: 10.600 ops/ms
Iteration   3: 10.692 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.629 ±(99.9%) 0.997 ops/ms [Average]
  (min, avg, max) = (10.595, 10.629, 10.692), stdev = 0.055
  CI (99.9%): [9.632, 11.626] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.606 ops/ms
# Warmup Iteration   2: 8.952 ops/ms
# Warmup Iteration   3: 9.383 ops/ms
Iteration   1: 9.787 ops/ms
Iteration   2: 9.613 ops/ms
Iteration   3: 9.723 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.708 ±(99.9%) 1.604 ops/ms [Average]
  (min, avg, max) = (9.613, 9.708, 9.787), stdev = 0.088
  CI (99.9%): [8.103, 11.312] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.259 ops/ms
# Warmup Iteration   2: 7.624 ops/ms
# Warmup Iteration   3: 8.010 ops/ms
Iteration   1: 8.053 ops/ms
Iteration   2: 8.251 ops/ms
Iteration   3: 8.598 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.301 ±(99.9%) 5.038 ops/ms [Average]
  (min, avg, max) = (8.053, 8.301, 8.598), stdev = 0.276
  CI (99.9%): [3.263, 13.339] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 9.054 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.532 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.266 ±(99.9%) 0.006 ms/op
Iteration   1: 3.252 ±(99.9%) 0.006 ms/op
Iteration   2: 3.209 ±(99.9%) 0.011 ms/op
Iteration   3: 3.132 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.198 ±(99.9%) 1.106 ms/op [Average]
  (min, avg, max) = (3.132, 3.198, 3.252), stdev = 0.061
  CI (99.9%): [2.092, 4.304] (assumes normal distribution)


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
# Warmup Iteration   1: 7.757 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.306 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.124 ±(99.9%) 0.002 ms/op
Iteration   1: 3.152 ±(99.9%) 0.007 ms/op
Iteration   2: 3.062 ±(99.9%) 0.009 ms/op
Iteration   3: 3.179 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.131 ±(99.9%) 1.122 ms/op [Average]
  (min, avg, max) = (3.062, 3.131, 3.179), stdev = 0.061
  CI (99.9%): [2.009, 4.253] (assumes normal distribution)


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
# Warmup Iteration   1: 6.948 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.619 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.318 ±(99.9%) 0.002 ms/op
Iteration   1: 3.204 ±(99.9%) 0.006 ms/op
Iteration   2: 3.079 ±(99.9%) 0.005 ms/op
Iteration   3: 3.213 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.166 ±(99.9%) 1.367 ms/op [Average]
  (min, avg, max) = (3.079, 3.166, 3.213), stdev = 0.075
  CI (99.9%): [1.799, 4.533] (assumes normal distribution)


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
# Warmup Iteration   1: 9.090 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 4.124 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.808 ±(99.9%) 0.005 ms/op
Iteration   1: 3.635 ±(99.9%) 0.009 ms/op
Iteration   2: 3.773 ±(99.9%) 0.005 ms/op
Iteration   3: 3.660 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.689 ±(99.9%) 1.344 ms/op [Average]
  (min, avg, max) = (3.635, 3.689, 3.773), stdev = 0.074
  CI (99.9%): [2.346, 5.033] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 8.126 ±(99.9%) 0.093 ms/op
# Warmup Iteration   2: 3.708 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.230 ±(99.9%) 0.010 ms/op
Iteration   1: 3.343 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.053 ms/op
                 createUser·p0.50:   3.265 ms/op
                 createUser·p0.90:   3.813 ms/op
                 createUser·p0.95:   4.235 ms/op
                 createUser·p0.99:   5.734 ms/op
                 createUser·p0.999:  19.601 ms/op
                 createUser·p0.9999: 23.883 ms/op
                 createUser·p1.00:   25.100 ms/op

Iteration   2: 3.332 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.491 ms/op
                 createUser·p0.50:   3.265 ms/op
                 createUser·p0.90:   3.731 ms/op
                 createUser·p0.95:   4.334 ms/op
                 createUser·p0.99:   6.341 ms/op
                 createUser·p0.999:  17.601 ms/op
                 createUser·p0.9999: 32.945 ms/op
                 createUser·p1.00:   38.273 ms/op

Iteration   3: 3.254 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.221 ms/op
                 createUser·p0.50:   3.252 ms/op
                 createUser·p0.90:   3.482 ms/op
                 createUser·p0.95:   3.899 ms/op
                 createUser·p0.99:   5.267 ms/op
                 createUser·p0.999:  14.007 ms/op
                 createUser·p0.9999: 25.723 ms/op
                 createUser·p1.00:   26.903 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 290164
  mean =      3.309 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 28546 
    [ 2.500,  5.000) = 253830 
    [ 5.000,  7.500) = 6967 
    [ 7.500, 10.000) = 377 
    [10.000, 12.500) = 50 
    [12.500, 15.000) = 86 
    [15.000, 17.500) = 19 
    [17.500, 20.000) = 98 
    [20.000, 22.500) = 55 
    [22.500, 25.000) = 59 
    [25.000, 27.500) = 45 
    [27.500, 30.000) = 20 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.491 ms/op
     p(50.0000) =      3.260 ms/op
     p(90.0000) =      3.699 ms/op
     p(95.0000) =      4.149 ms/op
     p(99.0000) =      5.792 ms/op
     p(99.9000) =     16.887 ms/op
     p(99.9900) =     28.639 ms/op
     p(99.9990) =     37.906 ms/op
     p(99.9999) =     38.273 ms/op
    p(100.0000) =     38.273 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 6.691 ±(99.9%) 0.082 ms/op
# Warmup Iteration   2: 3.384 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.128 ±(99.9%) 0.007 ms/op
Iteration   1: 3.124 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.296 ms/op
                 existUser·p0.50:   2.986 ms/op
                 existUser·p0.90:   3.322 ms/op
                 existUser·p0.95:   4.276 ms/op
                 existUser·p0.99:   5.512 ms/op
                 existUser·p0.999:  13.113 ms/op
                 existUser·p0.9999: 21.332 ms/op
                 existUser·p1.00:   23.396 ms/op

Iteration   2: 3.258 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.458 ms/op
                 existUser·p0.50:   3.248 ms/op
                 existUser·p0.90:   3.486 ms/op
                 existUser·p0.95:   3.895 ms/op
                 existUser·p0.99:   6.095 ms/op
                 existUser·p0.999:  8.167 ms/op
                 existUser·p0.9999: 21.927 ms/op
                 existUser·p1.00:   22.348 ms/op

Iteration   3: 3.073 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.190 ms/op
                 existUser·p0.50:   2.986 ms/op
                 existUser·p0.90:   3.297 ms/op
                 existUser·p0.95:   3.441 ms/op
                 existUser·p0.99:   5.325 ms/op
                 existUser·p0.999:  11.930 ms/op
                 existUser·p0.9999: 23.855 ms/op
                 existUser·p1.00:   24.445 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 304663
  mean =      3.150 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17675 
    [ 2.500,  5.000) = 280773 
    [ 5.000,  7.500) = 5562 
    [ 7.500, 10.000) = 326 
    [10.000, 12.500) = 62 
    [12.500, 15.000) = 8 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 83 
    [20.000, 22.500) = 132 
    [22.500, 25.000) = 42 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.190 ms/op
     p(50.0000) =      3.080 ms/op
     p(90.0000) =      3.379 ms/op
     p(95.0000) =      3.703 ms/op
     p(99.0000) =      5.603 ms/op
     p(99.9000) =     10.666 ms/op
     p(99.9900) =     22.922 ms/op
     p(99.9990) =     24.183 ms/op
     p(99.9999) =     24.445 ms/op
    p(100.0000) =     24.445 ms/op


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
# Warmup Iteration   1: 8.273 ±(99.9%) 0.107 ms/op
# Warmup Iteration   2: 3.458 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.268 ±(99.9%) 0.008 ms/op
Iteration   1: 3.276 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.401 ms/op
                 getUser·p0.50:   3.150 ms/op
                 getUser·p0.90:   3.686 ms/op
                 getUser·p0.95:   4.465 ms/op
                 getUser·p0.99:   6.349 ms/op
                 getUser·p0.999:  16.482 ms/op
                 getUser·p0.9999: 19.759 ms/op
                 getUser·p1.00:   20.447 ms/op

Iteration   2: 3.182 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.857 ms/op
                 getUser·p0.50:   3.080 ms/op
                 getUser·p0.90:   3.531 ms/op
                 getUser·p0.95:   3.867 ms/op
                 getUser·p0.99:   5.571 ms/op
                 getUser·p0.999:  8.978 ms/op
                 getUser·p0.9999: 22.639 ms/op
                 getUser·p1.00:   23.626 ms/op

Iteration   3: 3.405 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.971 ms/op
                 getUser·p0.50:   3.285 ms/op
                 getUser·p0.90:   3.842 ms/op
                 getUser·p0.95:   4.358 ms/op
                 getUser·p0.99:   6.341 ms/op
                 getUser·p0.999:  18.396 ms/op
                 getUser·p0.9999: 27.958 ms/op
                 getUser·p1.00:   29.262 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 292327
  mean =      3.285 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14413 
    [ 2.500,  5.000) = 268023 
    [ 5.000,  7.500) = 9016 
    [ 7.500, 10.000) = 504 
    [10.000, 12.500) = 30 
    [12.500, 15.000) = 28 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 124 
    [20.000, 22.500) = 90 
    [22.500, 25.000) = 39 
    [25.000, 27.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.857 ms/op
     p(50.0000) =      3.170 ms/op
     p(90.0000) =      3.719 ms/op
     p(95.0000) =      4.194 ms/op
     p(99.0000) =      6.128 ms/op
     p(99.9000) =     16.390 ms/op
     p(99.9900) =     25.864 ms/op
     p(99.9990) =     28.490 ms/op
     p(99.9999) =     29.262 ms/op
    p(100.0000) =     29.262 ms/op


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
# Warmup Iteration   1: 9.241 ±(99.9%) 0.112 ms/op
# Warmup Iteration   2: 4.067 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.878 ±(99.9%) 0.011 ms/op
Iteration   1: 3.741 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.530 ms/op
                 listUser·p0.50:   3.625 ms/op
                 listUser·p0.90:   4.166 ms/op
                 listUser·p0.95:   4.514 ms/op
                 listUser·p0.99:   6.685 ms/op
                 listUser·p0.999:  13.591 ms/op
                 listUser·p0.9999: 18.547 ms/op
                 listUser·p1.00:   19.333 ms/op

Iteration   2: 3.769 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.171 ms/op
                 listUser·p0.50:   3.637 ms/op
                 listUser·p0.90:   4.010 ms/op
                 listUser·p0.95:   4.219 ms/op
                 listUser·p0.99:   7.274 ms/op
                 listUser·p0.999:  15.368 ms/op
                 listUser·p0.9999: 19.366 ms/op
                 listUser·p1.00:   19.759 ms/op

Iteration   3: 3.660 ±(99.9%) 0.007 ms/op
                 listUser·p0.00:   2.175 ms/op
                 listUser·p0.50:   3.568 ms/op
                 listUser·p0.90:   3.936 ms/op
                 listUser·p0.95:   4.116 ms/op
                 listUser·p0.99:   6.423 ms/op
                 listUser·p0.999:  11.725 ms/op
                 listUser·p0.9999: 13.386 ms/op
                 listUser·p1.00:   13.435 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 257745
  mean =      3.723 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 62 
    [ 2.500,  3.750) = 188690 
    [ 3.750,  5.000) = 62068 
    [ 5.000,  6.250) = 2545 
    [ 6.250,  7.500) = 2673 
    [ 7.500,  8.750) = 819 
    [ 8.750, 10.000) = 265 
    [10.000, 11.250) = 92 
    [11.250, 12.500) = 137 
    [12.500, 13.750) = 150 
    [13.750, 15.000) = 66 
    [15.000, 16.250) = 47 
    [16.250, 17.500) = 70 
    [17.500, 18.750) = 28 

  Percentiles, ms/op:
      p(0.0000) =      1.530 ms/op
     p(50.0000) =      3.609 ms/op
     p(90.0000) =      4.010 ms/op
     p(95.0000) =      4.309 ms/op
     p(99.0000) =      6.816 ms/op
     p(99.9000) =     13.615 ms/op
     p(99.9900) =     19.250 ms/op
     p(99.9990) =     19.604 ms/op
     p(99.9999) =     19.759 ms/op
    p(100.0000) =     19.759 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.994 ± 2.467  ops/ms
ClientPb.existUser                       thrpt       3  10.629 ± 0.997  ops/ms
ClientPb.getUser                         thrpt       3   9.708 ± 1.604  ops/ms
ClientPb.listUser                        thrpt       3   8.301 ± 5.038  ops/ms
ClientPb.createUser                       avgt       3   3.198 ± 1.106   ms/op
ClientPb.existUser                        avgt       3   3.131 ± 1.122   ms/op
ClientPb.getUser                          avgt       3   3.166 ± 1.367   ms/op
ClientPb.listUser                         avgt       3   3.689 ± 1.344   ms/op
ClientPb.createUser                     sample  290164   3.309 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.491           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.260           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.699           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.149           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.792           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.887           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.639           ms/op
ClientPb.createUser:createUser·p1.00    sample          38.273           ms/op
ClientPb.existUser                      sample  304663   3.150 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.190           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.080           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.379           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.703           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.603           ms/op
ClientPb.existUser:existUser·p0.999     sample          10.666           ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.922           ms/op
ClientPb.existUser:existUser·p1.00      sample          24.445           ms/op
ClientPb.getUser                        sample  292327   3.285 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.857           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.170           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.719           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.194           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.128           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.390           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.864           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.262           ms/op
ClientPb.listUser                       sample  257745   3.723 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.530           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.609           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.010           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.309           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.816           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.615           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.250           ms/op
ClientPb.listUser:listUser·p1.00        sample          19.759           ms/op
