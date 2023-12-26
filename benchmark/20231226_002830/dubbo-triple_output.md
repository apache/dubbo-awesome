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
# Warmup Iteration   1: 4.711 ops/ms
# Warmup Iteration   2: 11.897 ops/ms
# Warmup Iteration   3: 12.262 ops/ms
Iteration   1: 12.393 ops/ms
Iteration   2: 12.413 ops/ms
Iteration   3: 12.475 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.427 ±(99.9%) 0.776 ops/ms [Average]
  (min, avg, max) = (12.393, 12.427, 12.475), stdev = 0.043
  CI (99.9%): [11.651, 13.204] (assumes normal distribution)


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
# Warmup Iteration   1: 8.193 ops/ms
# Warmup Iteration   2: 12.830 ops/ms
# Warmup Iteration   3: 12.742 ops/ms
Iteration   1: 12.717 ops/ms
Iteration   2: 12.714 ops/ms
Iteration   3: 12.715 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.715 ±(99.9%) 0.025 ops/ms [Average]
  (min, avg, max) = (12.714, 12.715, 12.717), stdev = 0.001
  CI (99.9%): [12.690, 12.741] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.574 ops/ms
# Warmup Iteration   2: 12.270 ops/ms
# Warmup Iteration   3: 12.653 ops/ms
Iteration   1: 12.432 ops/ms
Iteration   2: 12.594 ops/ms
Iteration   3: 12.553 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.526 ±(99.9%) 1.545 ops/ms [Average]
  (min, avg, max) = (12.432, 12.526, 12.594), stdev = 0.085
  CI (99.9%): [10.981, 14.072] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 6.836 ops/ms
# Warmup Iteration   2: 10.429 ops/ms
# Warmup Iteration   3: 10.542 ops/ms
Iteration   1: 10.551 ops/ms
Iteration   2: 10.532 ops/ms
Iteration   3: 10.571 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.551 ±(99.9%) 0.355 ops/ms [Average]
  (min, avg, max) = (10.532, 10.551, 10.571), stdev = 0.019
  CI (99.9%): [10.197, 10.906] (assumes normal distribution)


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
# Warmup Iteration   1: 4.108 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.632 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.565 ±(99.9%) 0.004 ms/op
Iteration   1: 2.594 ±(99.9%) 0.004 ms/op
Iteration   2: 2.577 ±(99.9%) 0.005 ms/op
Iteration   3: 2.568 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.580 ±(99.9%) 0.238 ms/op [Average]
  (min, avg, max) = (2.568, 2.580, 2.594), stdev = 0.013
  CI (99.9%): [2.341, 2.818] (assumes normal distribution)


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
# Warmup Iteration   1: 3.694 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.526 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.460 ±(99.9%) 0.004 ms/op
Iteration   1: 2.471 ±(99.9%) 0.004 ms/op
Iteration   2: 2.479 ±(99.9%) 0.004 ms/op
Iteration   3: 2.481 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.477 ±(99.9%) 0.092 ms/op [Average]
  (min, avg, max) = (2.471, 2.477, 2.481), stdev = 0.005
  CI (99.9%): [2.386, 2.569] (assumes normal distribution)


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
# Warmup Iteration   1: 3.972 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.595 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.513 ±(99.9%) 0.003 ms/op
Iteration   1: 2.535 ±(99.9%) 0.003 ms/op
Iteration   2: 2.529 ±(99.9%) 0.004 ms/op
Iteration   3: 2.545 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.536 ±(99.9%) 0.151 ms/op [Average]
  (min, avg, max) = (2.529, 2.536, 2.545), stdev = 0.008
  CI (99.9%): [2.386, 2.687] (assumes normal distribution)


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
# Warmup Iteration   1: 4.790 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.078 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.064 ±(99.9%) 0.005 ms/op
Iteration   1: 3.061 ±(99.9%) 0.005 ms/op
Iteration   2: 3.025 ±(99.9%) 0.005 ms/op
Iteration   3: 3.021 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.036 ±(99.9%) 0.402 ms/op [Average]
  (min, avg, max) = (3.021, 3.036, 3.061), stdev = 0.022
  CI (99.9%): [2.634, 3.437] (assumes normal distribution)


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
# Warmup Iteration   1: 4.235 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 2.714 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.615 ±(99.9%) 0.006 ms/op
Iteration   1: 2.582 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.967 ms/op
                 createUser·p0.50:   2.650 ms/op
                 createUser·p0.90:   3.133 ms/op
                 createUser·p0.95:   3.244 ms/op
                 createUser·p0.99:   3.842 ms/op
                 createUser·p0.999:  11.734 ms/op
                 createUser·p0.9999: 14.094 ms/op
                 createUser·p1.00:   15.876 ms/op

Iteration   2: 2.602 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.940 ms/op
                 createUser·p0.50:   2.646 ms/op
                 createUser·p0.90:   3.170 ms/op
                 createUser·p0.95:   3.281 ms/op
                 createUser·p0.99:   3.875 ms/op
                 createUser·p0.999:  9.851 ms/op
                 createUser·p0.9999: 13.360 ms/op
                 createUser·p1.00:   14.254 ms/op

Iteration   3: 2.603 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.982 ms/op
                 createUser·p0.50:   2.642 ms/op
                 createUser·p0.90:   3.162 ms/op
                 createUser·p0.95:   3.297 ms/op
                 createUser·p0.99:   4.055 ms/op
                 createUser·p0.999:  9.414 ms/op
                 createUser·p0.9999: 19.530 ms/op
                 createUser·p1.00:   20.873 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 369396
  mean =      2.596 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 175900 
    [ 2.500,  5.000) = 192565 
    [ 5.000,  7.500) = 508 
    [ 7.500, 10.000) = 98 
    [10.000, 12.500) = 187 
    [12.500, 15.000) = 107 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.940 ms/op
     p(50.0000) =      2.646 ms/op
     p(90.0000) =      3.154 ms/op
     p(95.0000) =      3.273 ms/op
     p(99.0000) =      3.920 ms/op
     p(99.9000) =      9.578 ms/op
     p(99.9900) =     14.263 ms/op
     p(99.9990) =     20.358 ms/op
     p(99.9999) =     20.873 ms/op
    p(100.0000) =     20.873 ms/op


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
# Warmup Iteration   1: 3.810 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.501 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.488 ±(99.9%) 0.005 ms/op
Iteration   1: 2.488 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.004 ms/op
                 existUser·p0.50:   2.540 ms/op
                 existUser·p0.90:   3.019 ms/op
                 existUser·p0.95:   3.121 ms/op
                 existUser·p0.99:   3.473 ms/op
                 existUser·p0.999:  8.261 ms/op
                 existUser·p0.9999: 14.355 ms/op
                 existUser·p1.00:   15.122 ms/op

Iteration   2: 2.482 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.011 ms/op
                 existUser·p0.50:   2.589 ms/op
                 existUser·p0.90:   3.002 ms/op
                 existUser·p0.95:   3.084 ms/op
                 existUser·p0.99:   3.391 ms/op
                 existUser·p0.999:  9.093 ms/op
                 existUser·p0.9999: 13.357 ms/op
                 existUser·p1.00:   13.959 ms/op

Iteration   3: 2.492 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.029 ms/op
                 existUser·p0.50:   2.548 ms/op
                 existUser·p0.90:   3.027 ms/op
                 existUser·p0.95:   3.138 ms/op
                 existUser·p0.99:   3.817 ms/op
                 existUser·p0.999:  8.525 ms/op
                 existUser·p0.9999: 12.160 ms/op
                 existUser·p1.00:   12.485 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 385441
  mean =      2.487 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 27 
    [ 1.250,  2.500) = 188997 
    [ 2.500,  3.750) = 193653 
    [ 3.750,  5.000) = 2084 
    [ 5.000,  6.250) = 244 
    [ 6.250,  7.500) = 12 
    [ 7.500,  8.750) = 28 
    [ 8.750, 10.000) = 75 
    [10.000, 11.250) = 105 
    [11.250, 12.500) = 95 
    [12.500, 13.750) = 81 
    [13.750, 15.000) = 38 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.004 ms/op
     p(50.0000) =      2.556 ms/op
     p(90.0000) =      3.015 ms/op
     p(95.0000) =      3.113 ms/op
     p(99.0000) =      3.559 ms/op
     p(99.9000) =      9.037 ms/op
     p(99.9900) =     13.852 ms/op
     p(99.9990) =     14.898 ms/op
     p(99.9999) =     15.122 ms/op
    p(100.0000) =     15.122 ms/op


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
# Warmup Iteration   1: 4.122 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.665 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.595 ±(99.9%) 0.006 ms/op
Iteration   1: 2.556 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.820 ms/op
                 getUser·p0.50:   2.580 ms/op
                 getUser·p0.90:   3.109 ms/op
                 getUser·p0.95:   3.224 ms/op
                 getUser·p0.99:   3.842 ms/op
                 getUser·p0.999:  11.680 ms/op
                 getUser·p0.9999: 13.975 ms/op
                 getUser·p1.00:   14.336 ms/op

Iteration   2: 2.657 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.905 ms/op
                 getUser·p0.50:   2.687 ms/op
                 getUser·p0.90:   3.244 ms/op
                 getUser·p0.95:   3.539 ms/op
                 getUser·p0.99:   4.823 ms/op
                 getUser·p0.999:  9.765 ms/op
                 getUser·p0.9999: 13.762 ms/op
                 getUser·p1.00:   14.123 ms/op

Iteration   3: 2.589 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.998 ms/op
                 getUser·p0.50:   2.609 ms/op
                 getUser·p0.90:   3.170 ms/op
                 getUser·p0.95:   3.314 ms/op
                 getUser·p0.99:   4.060 ms/op
                 getUser·p0.999:  8.849 ms/op
                 getUser·p0.9999: 10.977 ms/op
                 getUser·p1.00:   11.960 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 368878
  mean =      2.600 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 52 
    [ 1.250,  2.500) = 175938 
    [ 2.500,  3.750) = 184560 
    [ 3.750,  5.000) = 6797 
    [ 5.000,  6.250) = 979 
    [ 6.250,  7.500) = 135 
    [ 7.500,  8.750) = 28 
    [ 8.750, 10.000) = 98 
    [10.000, 11.250) = 103 
    [11.250, 12.500) = 64 
    [12.500, 13.750) = 92 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.820 ms/op
     p(50.0000) =      2.630 ms/op
     p(90.0000) =      3.170 ms/op
     p(95.0000) =      3.334 ms/op
     p(99.0000) =      4.284 ms/op
     p(99.9000) =      9.148 ms/op
     p(99.9900) =     13.652 ms/op
     p(99.9990) =     14.128 ms/op
     p(99.9999) =     14.336 ms/op
    p(100.0000) =     14.336 ms/op


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
# Warmup Iteration   1: 4.565 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.129 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.062 ±(99.9%) 0.009 ms/op
Iteration   1: 3.030 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.861 ms/op
                 listUser·p0.50:   2.966 ms/op
                 listUser·p0.90:   3.920 ms/op
                 listUser·p0.95:   4.424 ms/op
                 listUser·p0.99:   5.587 ms/op
                 listUser·p0.999:  9.814 ms/op
                 listUser·p0.9999: 11.225 ms/op
                 listUser·p1.00:   12.255 ms/op

Iteration   2: 3.026 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.856 ms/op
                 listUser·p0.50:   2.961 ms/op
                 listUser·p0.90:   3.903 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   5.641 ms/op
                 listUser·p0.999:  9.793 ms/op
                 listUser·p0.9999: 12.033 ms/op
                 listUser·p1.00:   12.468 ms/op

Iteration   3: 3.037 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.871 ms/op
                 listUser·p0.50:   2.974 ms/op
                 listUser·p0.90:   3.932 ms/op
                 listUser·p0.95:   4.448 ms/op
                 listUser·p0.99:   5.693 ms/op
                 listUser·p0.999:  9.634 ms/op
                 listUser·p0.9999: 10.969 ms/op
                 listUser·p1.00:   11.469 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 316455
  mean =      3.031 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 98 
    [ 1.250,  2.500) = 87702 
    [ 2.500,  3.750) = 187974 
    [ 3.750,  5.000) = 33270 
    [ 5.000,  6.250) = 6100 
    [ 6.250,  7.500) = 646 
    [ 7.500,  8.750) = 159 
    [ 8.750, 10.000) = 261 
    [10.000, 11.250) = 187 
    [11.250, 12.500) = 58 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.856 ms/op
     p(50.0000) =      2.970 ms/op
     p(90.0000) =      3.916 ms/op
     p(95.0000) =      4.424 ms/op
     p(99.0000) =      5.636 ms/op
     p(99.9000) =      9.732 ms/op
     p(99.9900) =     11.568 ms/op
     p(99.9990) =     12.389 ms/op
     p(99.9999) =     12.468 ms/op
    p(100.0000) =     12.468 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.427 ± 0.776  ops/ms
ClientPb.existUser                       thrpt       3  12.715 ± 0.025  ops/ms
ClientPb.getUser                         thrpt       3  12.526 ± 1.545  ops/ms
ClientPb.listUser                        thrpt       3  10.551 ± 0.355  ops/ms
ClientPb.createUser                       avgt       3   2.580 ± 0.238   ms/op
ClientPb.existUser                        avgt       3   2.477 ± 0.092   ms/op
ClientPb.getUser                          avgt       3   2.536 ± 0.151   ms/op
ClientPb.listUser                         avgt       3   3.036 ± 0.402   ms/op
ClientPb.createUser                     sample  369396   2.596 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.940           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.646           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.154           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.273           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.920           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.578           ms/op
ClientPb.createUser:createUser·p0.9999  sample          14.263           ms/op
ClientPb.createUser:createUser·p1.00    sample          20.873           ms/op
ClientPb.existUser                      sample  385441   2.487 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.004           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.556           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.015           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.113           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.559           ms/op
ClientPb.existUser:existUser·p0.999     sample           9.037           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.852           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.122           ms/op
ClientPb.getUser                        sample  368878   2.600 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.820           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.630           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.170           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.334           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.284           ms/op
ClientPb.getUser:getUser·p0.999         sample           9.148           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.652           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.336           ms/op
ClientPb.listUser                       sample  316455   3.031 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.856           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.970           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.916           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.424           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.636           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.732           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.568           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.468           ms/op
