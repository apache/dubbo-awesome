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
# Warmup Iteration   1: 1.420 ops/ms
# Warmup Iteration   2: 3.191 ops/ms
# Warmup Iteration   3: 6.682 ops/ms
Iteration   1: 7.524 ops/ms
Iteration   2: 7.996 ops/ms
Iteration   3: 7.465 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.662 ±(99.9%) 5.308 ops/ms [Average]
  (min, avg, max) = (7.465, 7.662, 7.996), stdev = 0.291
  CI (99.9%): [2.354, 12.969] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:12
# Fork: 1 of 1
# Warmup Iteration   1: 2.080 ops/ms
# Warmup Iteration   2: 7.029 ops/ms
# Warmup Iteration   3: 8.070 ops/ms
Iteration   1: 7.923 ops/ms
Iteration   2: 8.195 ops/ms
Iteration   3: 8.126 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.082 ±(99.9%) 2.581 ops/ms [Average]
  (min, avg, max) = (7.923, 8.082, 8.195), stdev = 0.141
  CI (99.9%): [5.501, 10.662] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:05
# Fork: 1 of 1
# Warmup Iteration   1: 1.806 ops/ms
# Warmup Iteration   2: 5.634 ops/ms
# Warmup Iteration   3: 7.620 ops/ms
Iteration   1: 7.845 ops/ms
Iteration   2: 8.035 ops/ms
Iteration   3: 8.093 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.991 ±(99.9%) 2.370 ops/ms [Average]
  (min, avg, max) = (7.845, 7.991, 8.093), stdev = 0.130
  CI (99.9%): [5.621, 10.361] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 2.100 ops/ms
# Warmup Iteration   2: 5.468 ops/ms
# Warmup Iteration   3: 6.559 ops/ms
Iteration   1: 6.481 ops/ms
Iteration   2: 6.450 ops/ms
Iteration   3: 6.520 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.483 ±(99.9%) 0.640 ops/ms [Average]
  (min, avg, max) = (6.450, 6.483, 6.520), stdev = 0.035
  CI (99.9%): [5.844, 7.123] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:50
# Fork: 1 of 1
# Warmup Iteration   1: 14.176 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 4.802 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.287 ±(99.9%) 0.008 ms/op
Iteration   1: 4.162 ±(99.9%) 0.005 ms/op
Iteration   2: 4.025 ±(99.9%) 0.005 ms/op
Iteration   3: 4.075 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.087 ±(99.9%) 1.272 ms/op [Average]
  (min, avg, max) = (4.025, 4.087, 4.162), stdev = 0.070
  CI (99.9%): [2.815, 5.359] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 11.871 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 4.294 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.172 ±(99.9%) 0.003 ms/op
Iteration   1: 3.870 ±(99.9%) 0.004 ms/op
Iteration   2: 3.916 ±(99.9%) 0.006 ms/op
Iteration   3: 3.944 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.910 ±(99.9%) 0.687 ms/op [Average]
  (min, avg, max) = (3.870, 3.910, 3.944), stdev = 0.038
  CI (99.9%): [3.223, 4.597] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 12.740 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.616 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.160 ±(99.9%) 0.003 ms/op
Iteration   1: 4.166 ±(99.9%) 0.009 ms/op
Iteration   2: 4.105 ±(99.9%) 0.007 ms/op
Iteration   3: 4.101 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.124 ±(99.9%) 0.667 ms/op [Average]
  (min, avg, max) = (4.101, 4.124, 4.166), stdev = 0.037
  CI (99.9%): [3.457, 4.791] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 14.688 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 5.644 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.007 ±(99.9%) 0.008 ms/op
Iteration   1: 4.614 ±(99.9%) 0.011 ms/op
Iteration   2: 4.553 ±(99.9%) 0.013 ms/op
Iteration   3: 4.595 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.587 ±(99.9%) 0.569 ms/op [Average]
  (min, avg, max) = (4.553, 4.587, 4.614), stdev = 0.031
  CI (99.9%): [4.018, 5.156] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 13.457 ±(99.9%) 0.189 ms/op
# Warmup Iteration   2: 5.509 ±(99.9%) 0.031 ms/op
# Warmup Iteration   3: 4.765 ±(99.9%) 0.023 ms/op
Iteration   1: 4.235 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.622 ms/op
                 createUser·p0.50:   3.920 ms/op
                 createUser·p0.90:   5.079 ms/op
                 createUser·p0.95:   6.611 ms/op
                 createUser·p0.99:   8.503 ms/op
                 createUser·p0.999:  14.664 ms/op
                 createUser·p0.9999: 26.172 ms/op
                 createUser·p1.00:   27.623 ms/op

Iteration   2: 4.090 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.903 ms/op
                 createUser·p0.50:   3.965 ms/op
                 createUser·p0.90:   4.661 ms/op
                 createUser·p0.95:   5.120 ms/op
                 createUser·p0.99:   7.610 ms/op
                 createUser·p0.999:  25.887 ms/op
                 createUser·p0.9999: 34.234 ms/op
                 createUser·p1.00:   35.521 ms/op

Iteration   3: 4.290 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.841 ms/op
                 createUser·p0.50:   4.055 ms/op
                 createUser·p0.90:   5.161 ms/op
                 createUser·p0.95:   5.980 ms/op
                 createUser·p0.99:   8.196 ms/op
                 createUser·p0.999:  17.957 ms/op
                 createUser·p0.9999: 34.114 ms/op
                 createUser·p1.00:   35.389 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 228246
  mean =      4.203 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 334 
    [ 2.500,  5.000) = 206376 
    [ 5.000,  7.500) = 17851 
    [ 7.500, 10.000) = 2645 
    [10.000, 12.500) = 639 
    [12.500, 15.000) = 145 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 36 
    [25.000, 27.500) = 80 
    [27.500, 30.000) = 26 
    [30.000, 32.500) = 49 
    [32.500, 35.000) = 27 
    [35.000, 37.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      1.622 ms/op
     p(50.0000) =      3.977 ms/op
     p(90.0000) =      4.956 ms/op
     p(95.0000) =      5.857 ms/op
     p(99.0000) =      8.135 ms/op
     p(99.9000) =     18.022 ms/op
     p(99.9900) =     33.495 ms/op
     p(99.9990) =     35.371 ms/op
     p(99.9999) =     35.521 ms/op
    p(100.0000) =     35.521 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 13.315 ±(99.9%) 0.185 ms/op
# Warmup Iteration   2: 4.756 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 4.048 ±(99.9%) 0.013 ms/op
Iteration   1: 3.718 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.767 ms/op
                 existUser·p0.50:   3.613 ms/op
                 existUser·p0.90:   3.977 ms/op
                 existUser·p0.95:   4.309 ms/op
                 existUser·p0.99:   6.619 ms/op
                 existUser·p0.999:  22.511 ms/op
                 existUser·p0.9999: 27.623 ms/op
                 existUser·p1.00:   28.836 ms/op

Iteration   2: 3.923 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.883 ms/op
                 existUser·p0.50:   3.703 ms/op
                 existUser·p0.90:   4.358 ms/op
                 existUser·p0.95:   5.284 ms/op
                 existUser·p0.99:   8.503 ms/op
                 existUser·p0.999:  18.219 ms/op
                 existUser·p0.9999: 27.014 ms/op
                 existUser·p1.00:   28.443 ms/op

Iteration   3: 3.847 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   2.044 ms/op
                 existUser·p0.50:   3.662 ms/op
                 existUser·p0.90:   4.325 ms/op
                 existUser·p0.95:   4.907 ms/op
                 existUser·p0.99:   7.520 ms/op
                 existUser·p0.999:  12.042 ms/op
                 existUser·p0.9999: 32.496 ms/op
                 existUser·p1.00:   33.391 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 250568
  mean =      3.827 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 242 
    [ 2.500,  5.000) = 239461 
    [ 5.000,  7.500) = 7710 
    [ 7.500, 10.000) = 2224 
    [10.000, 12.500) = 641 
    [12.500, 15.000) = 37 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 40 
    [25.000, 27.500) = 114 
    [27.500, 30.000) = 28 
    [30.000, 32.500) = 24 
    [32.500, 35.000) = 8 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.883 ms/op
     p(50.0000) =      3.650 ms/op
     p(90.0000) =      4.235 ms/op
     p(95.0000) =      4.792 ms/op
     p(99.0000) =      7.905 ms/op
     p(99.9000) =     17.701 ms/op
     p(99.9900) =     31.228 ms/op
     p(99.9990) =     33.160 ms/op
     p(99.9999) =     33.391 ms/op
    p(100.0000) =     33.391 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 11.811 ±(99.9%) 0.188 ms/op
# Warmup Iteration   2: 4.740 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 4.573 ±(99.9%) 0.018 ms/op
Iteration   1: 4.083 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.640 ms/op
                 getUser·p0.50:   3.871 ms/op
                 getUser·p0.90:   4.465 ms/op
                 getUser·p0.95:   5.194 ms/op
                 getUser·p0.99:   8.274 ms/op
                 getUser·p0.999:  23.444 ms/op
                 getUser·p0.9999: 25.650 ms/op
                 getUser·p1.00:   26.640 ms/op

Iteration   2: 4.183 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.540 ms/op
                 getUser·p0.50:   3.940 ms/op
                 getUser·p0.90:   4.899 ms/op
                 getUser·p0.95:   6.414 ms/op
                 getUser·p0.99:   8.765 ms/op
                 getUser·p0.999:  12.059 ms/op
                 getUser·p0.9999: 29.175 ms/op
                 getUser·p1.00:   29.655 ms/op

Iteration   3: 4.231 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   1.649 ms/op
                 getUser·p0.50:   3.969 ms/op
                 getUser·p0.90:   5.128 ms/op
                 getUser·p0.95:   5.956 ms/op
                 getUser·p0.99:   8.503 ms/op
                 getUser·p0.999:  29.978 ms/op
                 getUser·p0.9999: 32.910 ms/op
                 getUser·p1.00:   33.260 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 230282
  mean =      4.165 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 108 
    [ 2.500,  5.000) = 210852 
    [ 5.000,  7.500) = 14869 
    [ 7.500, 10.000) = 3286 
    [10.000, 12.500) = 746 
    [12.500, 15.000) = 73 
    [15.000, 17.500) = 40 
    [17.500, 20.000) = 50 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 72 
    [25.000, 27.500) = 61 
    [27.500, 30.000) = 46 
    [30.000, 32.500) = 64 
    [32.500, 35.000) = 11 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.540 ms/op
     p(50.0000) =      3.928 ms/op
     p(90.0000) =      4.760 ms/op
     p(95.0000) =      5.972 ms/op
     p(99.0000) =      8.569 ms/op
     p(99.9000) =     23.560 ms/op
     p(99.9900) =     31.981 ms/op
     p(99.9990) =     33.260 ms/op
     p(99.9999) =     33.260 ms/op
    p(100.0000) =     33.260 ms/op


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
# Warmup Iteration   1: 15.238 ±(99.9%) 0.248 ms/op
# Warmup Iteration   2: 6.057 ±(99.9%) 0.035 ms/op
# Warmup Iteration   3: 4.961 ±(99.9%) 0.018 ms/op
Iteration   1: 4.919 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   2.042 ms/op
                 listUser·p0.50:   4.571 ms/op
                 listUser·p0.90:   5.669 ms/op
                 listUser·p0.95:   7.070 ms/op
                 listUser·p0.99:   10.617 ms/op
                 listUser·p0.999:  23.295 ms/op
                 listUser·p0.9999: 25.542 ms/op
                 listUser·p1.00:   26.051 ms/op

Iteration   2: 4.861 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.800 ms/op
                 listUser·p0.50:   4.563 ms/op
                 listUser·p0.90:   5.439 ms/op
                 listUser·p0.95:   6.504 ms/op
                 listUser·p0.99:   9.907 ms/op
                 listUser·p0.999:  22.217 ms/op
                 listUser·p0.9999: 27.782 ms/op
                 listUser·p1.00:   28.377 ms/op

Iteration   3: 5.060 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   2.269 ms/op
                 listUser·p0.50:   4.727 ms/op
                 listUser·p0.90:   5.947 ms/op
                 listUser·p0.95:   7.127 ms/op
                 listUser·p0.99:   10.551 ms/op
                 listUser·p0.999:  17.400 ms/op
                 listUser·p0.9999: 24.621 ms/op
                 listUser·p1.00:   25.231 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 194054
  mean =      4.945 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9 
    [ 2.500,  5.000) = 140911 
    [ 5.000,  7.500) = 45376 
    [ 7.500, 10.000) = 5430 
    [10.000, 12.500) = 1398 
    [12.500, 15.000) = 435 
    [15.000, 17.500) = 167 
    [17.500, 20.000) = 89 
    [20.000, 22.500) = 78 
    [22.500, 25.000) = 112 
    [25.000, 27.500) = 40 

  Percentiles, ms/op:
      p(0.0000) =      1.800 ms/op
     p(50.0000) =      4.604 ms/op
     p(90.0000) =      5.702 ms/op
     p(95.0000) =      6.922 ms/op
     p(99.0000) =     10.338 ms/op
     p(99.9000) =     21.955 ms/op
     p(99.9900) =     26.070 ms/op
     p(99.9990) =     28.346 ms/op
     p(99.9999) =     28.377 ms/op
    p(100.0000) =     28.377 ms/op


# Run complete. Total time: 00:13:18

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.662 ± 5.308  ops/ms
ClientPb.existUser                       thrpt       3   8.082 ± 2.581  ops/ms
ClientPb.getUser                         thrpt       3   7.991 ± 2.370  ops/ms
ClientPb.listUser                        thrpt       3   6.483 ± 0.640  ops/ms
ClientPb.createUser                       avgt       3   4.087 ± 1.272   ms/op
ClientPb.existUser                        avgt       3   3.910 ± 0.687   ms/op
ClientPb.getUser                          avgt       3   4.124 ± 0.667   ms/op
ClientPb.listUser                         avgt       3   4.587 ± 0.569   ms/op
ClientPb.createUser                     sample  228246   4.203 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.622           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.977           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.956           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.857           ms/op
ClientPb.createUser:createUser·p0.99    sample           8.135           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.022           ms/op
ClientPb.createUser:createUser·p0.9999  sample          33.495           ms/op
ClientPb.createUser:createUser·p1.00    sample          35.521           ms/op
ClientPb.existUser                      sample  250568   3.827 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.883           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.650           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.235           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.792           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.905           ms/op
ClientPb.existUser:existUser·p0.999     sample          17.701           ms/op
ClientPb.existUser:existUser·p0.9999    sample          31.228           ms/op
ClientPb.existUser:existUser·p1.00      sample          33.391           ms/op
ClientPb.getUser                        sample  230282   4.165 ± 0.009   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.540           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.928           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.760           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.972           ms/op
ClientPb.getUser:getUser·p0.99          sample           8.569           ms/op
ClientPb.getUser:getUser·p0.999         sample          23.560           ms/op
ClientPb.getUser:getUser·p0.9999        sample          31.981           ms/op
ClientPb.getUser:getUser·p1.00          sample          33.260           ms/op
ClientPb.listUser                       sample  194054   4.945 ± 0.010   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.800           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.604           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.702           ms/op
ClientPb.listUser:listUser·p0.95        sample           6.922           ms/op
ClientPb.listUser:listUser·p0.99        sample          10.338           ms/op
ClientPb.listUser:listUser·p0.999       sample          21.955           ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.070           ms/op
ClientPb.listUser:listUser·p1.00        sample          28.377           ms/op
