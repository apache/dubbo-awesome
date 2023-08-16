# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.375 ops/ms
# Warmup Iteration   2: 2.962 ops/ms
# Warmup Iteration   3: 6.265 ops/ms
Iteration   1: 7.139 ops/ms
Iteration   2: 7.530 ops/ms
Iteration   3: 7.685 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.452 ±(99.9%) 5.133 ops/ms [Average]
  (min, avg, max) = (7.139, 7.452, 7.685), stdev = 0.281
  CI (99.9%): [2.319, 12.584] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 2.047 ops/ms
# Warmup Iteration   2: 6.438 ops/ms
# Warmup Iteration   3: 8.025 ops/ms
Iteration   1: 8.037 ops/ms
Iteration   2: 7.589 ops/ms
Iteration   3: 8.390 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.005 ±(99.9%) 7.320 ops/ms [Average]
  (min, avg, max) = (7.589, 8.005, 8.390), stdev = 0.401
  CI (99.9%): [0.685, 15.326] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.214 ops/ms
# Warmup Iteration   2: 7.208 ops/ms
# Warmup Iteration   3: 8.471 ops/ms
Iteration   1: 8.807 ops/ms
Iteration   2: 8.757 ops/ms
Iteration   3: 8.291 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.619 ±(99.9%) 5.192 ops/ms [Average]
  (min, avg, max) = (8.291, 8.619, 8.807), stdev = 0.285
  CI (99.9%): [3.426, 13.811] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 2.388 ops/ms
# Warmup Iteration   2: 6.169 ops/ms
# Warmup Iteration   3: 7.041 ops/ms
Iteration   1: 6.920 ops/ms
Iteration   2: 7.202 ops/ms
Iteration   3: 6.967 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.030 ±(99.9%) 2.755 ops/ms [Average]
  (min, avg, max) = (6.920, 7.030, 7.202), stdev = 0.151
  CI (99.9%): [4.275, 9.785] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 12.709 ±(99.9%) 0.069 ms/op
# Warmup Iteration   2: 4.025 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.830 ±(99.9%) 0.005 ms/op
Iteration   1: 3.483 ±(99.9%) 0.012 ms/op
Iteration   2: 3.684 ±(99.9%) 0.006 ms/op
Iteration   3: 3.728 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.632 ±(99.9%) 2.385 ms/op [Average]
  (min, avg, max) = (3.483, 3.632, 3.728), stdev = 0.131
  CI (99.9%): [1.247, 6.017] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 8.952 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.799 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.631 ±(99.9%) 0.004 ms/op
Iteration   1: 3.478 ±(99.9%) 0.007 ms/op
Iteration   2: 3.745 ±(99.9%) 0.003 ms/op
Iteration   3: 3.701 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.641 ±(99.9%) 2.612 ms/op [Average]
  (min, avg, max) = (3.478, 3.641, 3.745), stdev = 0.143
  CI (99.9%): [1.029, 6.253] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 11.439 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 4.457 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.094 ±(99.9%) 0.005 ms/op
Iteration   1: 3.775 ±(99.9%) 0.006 ms/op
Iteration   2: 3.872 ±(99.9%) 0.006 ms/op
Iteration   3: 3.892 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.846 ±(99.9%) 1.142 ms/op [Average]
  (min, avg, max) = (3.775, 3.846, 3.892), stdev = 0.063
  CI (99.9%): [2.705, 4.988] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 12.561 ±(99.9%) 0.061 ms/op
# Warmup Iteration   2: 4.931 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.751 ±(99.9%) 0.009 ms/op
Iteration   1: 4.593 ±(99.9%) 0.012 ms/op
Iteration   2: 4.372 ±(99.9%) 0.009 ms/op
Iteration   3: 4.295 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.420 ±(99.9%) 2.822 ms/op [Average]
  (min, avg, max) = (4.295, 4.420, 4.593), stdev = 0.155
  CI (99.9%): [1.598, 7.242] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 11.727 ±(99.9%) 0.155 ms/op
# Warmup Iteration   2: 4.379 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.096 ±(99.9%) 0.017 ms/op
Iteration   1: 3.871 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.296 ms/op
                 createUser·p0.50:   3.678 ms/op
                 createUser·p0.90:   4.669 ms/op
                 createUser·p0.95:   5.726 ms/op
                 createUser·p0.99:   7.804 ms/op
                 createUser·p0.999:  12.190 ms/op
                 createUser·p0.9999: 26.667 ms/op
                 createUser·p1.00:   27.427 ms/op

Iteration   2: 3.602 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.188 ms/op
                 createUser·p0.50:   3.490 ms/op
                 createUser·p0.90:   4.194 ms/op
                 createUser·p0.95:   4.661 ms/op
                 createUser·p0.99:   6.693 ms/op
                 createUser·p0.999:  23.764 ms/op
                 createUser·p0.9999: 32.477 ms/op
                 createUser·p1.00:   33.391 ms/op

Iteration   3: 3.945 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.290 ms/op
                 createUser·p0.50:   3.731 ms/op
                 createUser·p0.90:   4.661 ms/op
                 createUser·p0.95:   5.054 ms/op
                 createUser·p0.99:   8.001 ms/op
                 createUser·p0.999:  28.121 ms/op
                 createUser·p0.9999: 33.817 ms/op
                 createUser·p1.00:   35.127 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 252753
  mean =      3.801 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3479 
    [ 2.500,  5.000) = 235898 
    [ 5.000,  7.500) = 10775 
    [ 7.500, 10.000) = 1770 
    [10.000, 12.500) = 501 
    [12.500, 15.000) = 42 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 74 
    [25.000, 27.500) = 74 
    [27.500, 30.000) = 19 
    [30.000, 32.500) = 55 
    [32.500, 35.000) = 40 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.188 ms/op
     p(50.0000) =      3.633 ms/op
     p(90.0000) =      4.538 ms/op
     p(95.0000) =      5.063 ms/op
     p(99.0000) =      7.537 ms/op
     p(99.9000) =     23.691 ms/op
     p(99.9900) =     33.119 ms/op
     p(99.9990) =     34.106 ms/op
     p(99.9999) =     35.127 ms/op
    p(100.0000) =     35.127 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 10.426 ±(99.9%) 0.143 ms/op
# Warmup Iteration   2: 3.888 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.660 ±(99.9%) 0.011 ms/op
Iteration   1: 3.601 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.219 ms/op
                 existUser·p0.50:   3.506 ms/op
                 existUser·p0.90:   4.002 ms/op
                 existUser·p0.95:   4.604 ms/op
                 existUser·p0.99:   7.627 ms/op
                 existUser·p0.999:  12.600 ms/op
                 existUser·p0.9999: 25.992 ms/op
                 existUser·p1.00:   26.706 ms/op

Iteration   2: 3.674 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.577 ms/op
                 existUser·p0.50:   3.478 ms/op
                 existUser·p0.90:   4.375 ms/op
                 existUser·p0.95:   4.956 ms/op
                 existUser·p0.99:   7.340 ms/op
                 existUser·p0.999:  24.506 ms/op
                 existUser·p0.9999: 26.903 ms/op
                 existUser·p1.00:   27.525 ms/op

Iteration   3: 3.565 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.640 ms/op
                 existUser·p0.50:   3.531 ms/op
                 existUser·p0.90:   3.973 ms/op
                 existUser·p0.95:   4.456 ms/op
                 existUser·p0.99:   6.357 ms/op
                 existUser·p0.999:  18.383 ms/op
                 existUser·p0.9999: 29.624 ms/op
                 existUser·p1.00:   29.983 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 265762
  mean =      3.613 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7120 
    [ 2.500,  5.000) = 248127 
    [ 5.000,  7.500) = 8264 
    [ 7.500, 10.000) = 1412 
    [10.000, 12.500) = 384 
    [12.500, 15.000) = 164 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 42 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 59 
    [25.000, 27.500) = 89 

  Percentiles, ms/op:
      p(0.0000) =      1.219 ms/op
     p(50.0000) =      3.506 ms/op
     p(90.0000) =      4.141 ms/op
     p(95.0000) =      4.702 ms/op
     p(99.0000) =      7.266 ms/op
     p(99.9000) =     17.596 ms/op
     p(99.9900) =     29.210 ms/op
     p(99.9990) =     29.831 ms/op
     p(99.9999) =     29.983 ms/op
    p(100.0000) =     29.983 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 12.159 ±(99.9%) 0.141 ms/op
# Warmup Iteration   2: 4.443 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.015 ±(99.9%) 0.014 ms/op
Iteration   1: 3.730 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.630 ms/op
                 getUser·p0.50:   3.596 ms/op
                 getUser·p0.90:   4.440 ms/op
                 getUser·p0.95:   4.940 ms/op
                 getUser·p0.99:   7.889 ms/op
                 getUser·p0.999:  13.279 ms/op
                 getUser·p0.9999: 25.150 ms/op
                 getUser·p1.00:   26.935 ms/op

Iteration   2: 3.864 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.274 ms/op
                 getUser·p0.50:   3.703 ms/op
                 getUser·p0.90:   4.276 ms/op
                 getUser·p0.95:   4.973 ms/op
                 getUser·p0.99:   8.192 ms/op
                 getUser·p0.999:  21.897 ms/op
                 getUser·p0.9999: 25.040 ms/op
                 getUser·p1.00:   25.625 ms/op

Iteration   3: 3.782 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.386 ms/op
                 getUser·p0.50:   3.600 ms/op
                 getUser·p0.90:   4.497 ms/op
                 getUser·p0.95:   5.030 ms/op
                 getUser·p0.99:   7.660 ms/op
                 getUser·p0.999:  25.580 ms/op
                 getUser·p0.9999: 36.997 ms/op
                 getUser·p1.00:   39.387 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 253193
  mean =      3.791 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2250 
    [ 2.500,  5.000) = 238481 
    [ 5.000,  7.500) = 9288 
    [ 7.500, 10.000) = 2109 
    [10.000, 12.500) = 622 
    [12.500, 15.000) = 139 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 36 
    [20.000, 22.500) = 57 
    [22.500, 25.000) = 89 
    [25.000, 27.500) = 40 
    [27.500, 30.000) = 26 
    [30.000, 32.500) = 11 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 28 

  Percentiles, ms/op:
      p(0.0000) =      1.274 ms/op
     p(50.0000) =      3.633 ms/op
     p(90.0000) =      4.391 ms/op
     p(95.0000) =      4.989 ms/op
     p(99.0000) =      7.913 ms/op
     p(99.9000) =     20.192 ms/op
     p(99.9900) =     35.652 ms/op
     p(99.9990) =     37.814 ms/op
     p(99.9999) =     39.387 ms/op
    p(100.0000) =     39.387 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 11.692 ±(99.9%) 0.170 ms/op
# Warmup Iteration   2: 5.096 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 4.664 ±(99.9%) 0.017 ms/op
Iteration   1: 4.568 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   2.392 ms/op
                 listUser·p0.50:   4.407 ms/op
                 listUser·p0.90:   4.948 ms/op
                 listUser·p0.95:   5.382 ms/op
                 listUser·p0.99:   8.306 ms/op
                 listUser·p0.999:  23.461 ms/op
                 listUser·p0.9999: 27.427 ms/op
                 listUser·p1.00:   28.312 ms/op

Iteration   2: 4.769 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.831 ms/op
                 listUser·p0.50:   4.522 ms/op
                 listUser·p0.90:   5.439 ms/op
                 listUser·p0.95:   6.280 ms/op
                 listUser·p0.99:   9.470 ms/op
                 listUser·p0.999:  17.657 ms/op
                 listUser·p0.9999: 20.925 ms/op
                 listUser·p1.00:   22.413 ms/op

Iteration   3: 4.648 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.408 ms/op
                 listUser·p0.50:   4.465 ms/op
                 listUser·p0.90:   5.136 ms/op
                 listUser·p0.95:   5.784 ms/op
                 listUser·p0.99:   9.355 ms/op
                 listUser·p0.999:  17.924 ms/op
                 listUser·p0.9999: 21.107 ms/op
                 listUser·p1.00:   21.561 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 205930
  mean =      4.660 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6 
    [ 2.500,  5.000) = 175924 
    [ 5.000,  7.500) = 24729 
    [ 7.500, 10.000) = 3939 
    [10.000, 12.500) = 837 
    [12.500, 15.000) = 78 
    [15.000, 17.500) = 140 
    [17.500, 20.000) = 112 
    [20.000, 22.500) = 84 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 48 

  Percentiles, ms/op:
      p(0.0000) =      1.831 ms/op
     p(50.0000) =      4.456 ms/op
     p(90.0000) =      5.194 ms/op
     p(95.0000) =      5.808 ms/op
     p(99.0000) =      9.110 ms/op
     p(99.9000) =     19.071 ms/op
     p(99.9900) =     26.575 ms/op
     p(99.9990) =     27.803 ms/op
     p(99.9999) =     28.312 ms/op
    p(100.0000) =     28.312 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.452 ± 5.133  ops/ms
ClientPb.existUser                       thrpt       3   8.005 ± 7.320  ops/ms
ClientPb.getUser                         thrpt       3   8.619 ± 5.192  ops/ms
ClientPb.listUser                        thrpt       3   7.030 ± 2.755  ops/ms
ClientPb.createUser                       avgt       3   3.632 ± 2.385   ms/op
ClientPb.existUser                        avgt       3   3.641 ± 2.612   ms/op
ClientPb.getUser                          avgt       3   3.846 ± 1.142   ms/op
ClientPb.listUser                         avgt       3   4.420 ± 2.822   ms/op
ClientPb.createUser                     sample  252753   3.801 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.188           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.633           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.538           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.063           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.537           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.691           ms/op
ClientPb.createUser:createUser·p0.9999  sample          33.119           ms/op
ClientPb.createUser:createUser·p1.00    sample          35.127           ms/op
ClientPb.existUser                      sample  265762   3.613 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.219           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.506           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.141           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.702           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.266           ms/op
ClientPb.existUser:existUser·p0.999     sample          17.596           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.210           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.983           ms/op
ClientPb.getUser                        sample  253193   3.791 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.274           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.633           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.391           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.989           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.913           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.192           ms/op
ClientPb.getUser:getUser·p0.9999        sample          35.652           ms/op
ClientPb.getUser:getUser·p1.00          sample          39.387           ms/op
ClientPb.listUser                       sample  205930   4.660 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.831           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.456           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.194           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.808           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.110           ms/op
ClientPb.listUser:listUser·p0.999       sample          19.071           ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.575           ms/op
ClientPb.listUser:listUser·p1.00        sample          28.312           ms/op
