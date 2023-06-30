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
# Warmup Iteration   1: 1.652 ops/ms
# Warmup Iteration   2: 3.645 ops/ms
# Warmup Iteration   3: 7.074 ops/ms
Iteration   1: 7.407 ops/ms
Iteration   2: 8.272 ops/ms
Iteration   3: 7.787 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.822 ±(99.9%) 7.908 ops/ms [Average]
  (min, avg, max) = (7.407, 7.822, 8.272), stdev = 0.433
  CI (99.9%): [≈ 0, 15.730] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:10
# Fork: 1 of 1
# Warmup Iteration   1: 2.554 ops/ms
# Warmup Iteration   2: 6.466 ops/ms
# Warmup Iteration   3: 8.411 ops/ms
Iteration   1: 8.396 ops/ms
Iteration   2: 8.397 ops/ms
Iteration   3: 8.166 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.320 ±(99.9%) 2.434 ops/ms [Average]
  (min, avg, max) = (8.166, 8.320, 8.397), stdev = 0.133
  CI (99.9%): [5.885, 10.754] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 2.189 ops/ms
# Warmup Iteration   2: 6.631 ops/ms
# Warmup Iteration   3: 7.723 ops/ms
Iteration   1: 7.788 ops/ms
Iteration   2: 8.193 ops/ms
Iteration   3: 7.965 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.982 ±(99.9%) 3.707 ops/ms [Average]
  (min, avg, max) = (7.788, 7.982, 8.193), stdev = 0.203
  CI (99.9%): [4.276, 11.689] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 2.066 ops/ms
# Warmup Iteration   2: 5.600 ops/ms
# Warmup Iteration   3: 6.414 ops/ms
Iteration   1: 6.760 ops/ms
Iteration   2: 6.660 ops/ms
Iteration   3: 6.743 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.721 ±(99.9%) 0.978 ops/ms [Average]
  (min, avg, max) = (6.660, 6.721, 6.760), stdev = 0.054
  CI (99.9%): [5.743, 7.699] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 11.455 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 4.483 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.369 ±(99.9%) 0.008 ms/op
Iteration   1: 4.070 ±(99.9%) 0.009 ms/op
Iteration   2: 4.115 ±(99.9%) 0.006 ms/op
Iteration   3: 3.974 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.053 ±(99.9%) 1.311 ms/op [Average]
  (min, avg, max) = (3.974, 4.053, 4.115), stdev = 0.072
  CI (99.9%): [2.743, 5.364] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 12.228 ±(99.9%) 0.075 ms/op
# Warmup Iteration   2: 4.433 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.041 ±(99.9%) 0.008 ms/op
Iteration   1: 3.699 ±(99.9%) 0.010 ms/op
Iteration   2: 3.913 ±(99.9%) 0.008 ms/op
Iteration   3: 3.802 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.805 ±(99.9%) 1.956 ms/op [Average]
  (min, avg, max) = (3.699, 3.805, 3.913), stdev = 0.107
  CI (99.9%): [1.848, 5.761] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 12.801 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 4.395 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.177 ±(99.9%) 0.005 ms/op
Iteration   1: 4.110 ±(99.9%) 0.004 ms/op
Iteration   2: 4.123 ±(99.9%) 0.004 ms/op
Iteration   3: 3.916 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.050 ±(99.9%) 2.118 ms/op [Average]
  (min, avg, max) = (3.916, 4.050, 4.123), stdev = 0.116
  CI (99.9%): [1.931, 6.168] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 13.941 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 5.625 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.859 ±(99.9%) 0.013 ms/op
Iteration   1: 4.725 ±(99.9%) 0.013 ms/op
Iteration   2: 4.569 ±(99.9%) 0.013 ms/op
Iteration   3: 4.775 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.690 ±(99.9%) 1.965 ms/op [Average]
  (min, avg, max) = (4.569, 4.690, 4.775), stdev = 0.108
  CI (99.9%): [2.725, 6.655] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 12.959 ±(99.9%) 0.189 ms/op
# Warmup Iteration   2: 4.751 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.461 ±(99.9%) 0.018 ms/op
Iteration   1: 4.108 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.662 ms/op
                 createUser·p0.50:   3.924 ms/op
                 createUser·p0.90:   4.809 ms/op
                 createUser·p0.95:   5.251 ms/op
                 createUser·p0.99:   7.290 ms/op
                 createUser·p0.999:  23.036 ms/op
                 createUser·p0.9999: 25.166 ms/op
                 createUser·p1.00:   26.083 ms/op

Iteration   2: 4.044 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.663 ms/op
                 createUser·p0.50:   3.940 ms/op
                 createUser·p0.90:   4.628 ms/op
                 createUser·p0.95:   5.038 ms/op
                 createUser·p0.99:   7.414 ms/op
                 createUser·p0.999:  10.630 ms/op
                 createUser·p0.9999: 30.149 ms/op
                 createUser·p1.00:   31.457 ms/op

Iteration   3: 4.023 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.247 ms/op
                 createUser·p0.50:   3.817 ms/op
                 createUser·p0.90:   4.612 ms/op
                 createUser·p0.95:   5.022 ms/op
                 createUser·p0.99:   6.865 ms/op
                 createUser·p0.999:  28.344 ms/op
                 createUser·p0.9999: 30.972 ms/op
                 createUser·p1.00:   33.554 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 236725
  mean =      4.058 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 284 
    [ 2.500,  5.000) = 222599 
    [ 5.000,  7.500) = 11861 
    [ 7.500, 10.000) = 1462 
    [10.000, 12.500) = 178 
    [12.500, 15.000) = 80 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 96 
    [25.000, 27.500) = 26 
    [27.500, 30.000) = 100 
    [30.000, 32.500) = 25 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.662 ms/op
     p(50.0000) =      3.903 ms/op
     p(90.0000) =      4.686 ms/op
     p(95.0000) =      5.095 ms/op
     p(99.0000) =      7.184 ms/op
     p(99.9000) =     23.045 ms/op
     p(99.9900) =     30.255 ms/op
     p(99.9990) =     33.233 ms/op
     p(99.9999) =     33.554 ms/op
    p(100.0000) =     33.554 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 12.572 ±(99.9%) 0.157 ms/op
# Warmup Iteration   2: 4.738 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 3.943 ±(99.9%) 0.011 ms/op
Iteration   1: 3.856 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.960 ms/op
                 existUser·p0.50:   3.699 ms/op
                 existUser·p0.90:   4.309 ms/op
                 existUser·p0.95:   4.841 ms/op
                 existUser·p0.99:   7.160 ms/op
                 existUser·p0.999:  18.153 ms/op
                 existUser·p0.9999: 25.048 ms/op
                 existUser·p1.00:   26.509 ms/op

Iteration   2: 3.918 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.894 ms/op
                 existUser·p0.50:   3.748 ms/op
                 existUser·p0.90:   4.391 ms/op
                 existUser·p0.95:   4.964 ms/op
                 existUser·p0.99:   7.537 ms/op
                 existUser·p0.999:  17.448 ms/op
                 existUser·p0.9999: 21.818 ms/op
                 existUser·p1.00:   22.905 ms/op

Iteration   3: 3.848 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.489 ms/op
                 existUser·p0.50:   3.744 ms/op
                 existUser·p0.90:   4.284 ms/op
                 existUser·p0.95:   4.645 ms/op
                 existUser·p0.99:   6.611 ms/op
                 existUser·p0.999:  10.666 ms/op
                 existUser·p0.9999: 24.342 ms/op
                 existUser·p1.00:   24.904 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 247569
  mean =      3.874 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 455 
    [ 2.500,  5.000) = 236758 
    [ 5.000,  7.500) = 8471 
    [ 7.500, 10.000) = 1383 
    [10.000, 12.500) = 214 
    [12.500, 15.000) = 19 
    [15.000, 17.500) = 51 
    [17.500, 20.000) = 69 
    [20.000, 22.500) = 81 
    [22.500, 25.000) = 59 
    [25.000, 27.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      1.489 ms/op
     p(50.0000) =      3.727 ms/op
     p(90.0000) =      4.325 ms/op
     p(95.0000) =      4.817 ms/op
     p(99.0000) =      7.102 ms/op
     p(99.9000) =     16.936 ms/op
     p(99.9900) =     24.445 ms/op
     p(99.9990) =     26.288 ms/op
     p(99.9999) =     26.509 ms/op
    p(100.0000) =     26.509 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 11.646 ±(99.9%) 0.161 ms/op
# Warmup Iteration   2: 4.446 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.987 ±(99.9%) 0.012 ms/op
Iteration   1: 4.111 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.610 ms/op
                 getUser·p0.50:   3.834 ms/op
                 getUser·p0.90:   4.825 ms/op
                 getUser·p0.95:   6.463 ms/op
                 getUser·p0.99:   8.880 ms/op
                 getUser·p0.999:  20.062 ms/op
                 getUser·p0.9999: 27.777 ms/op
                 getUser·p1.00:   28.148 ms/op

Iteration   2: 3.894 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.628 ms/op
                 getUser·p0.50:   3.760 ms/op
                 getUser·p0.90:   4.211 ms/op
                 getUser·p0.95:   4.473 ms/op
                 getUser·p0.99:   6.840 ms/op
                 getUser·p0.999:  25.821 ms/op
                 getUser·p0.9999: 29.124 ms/op
                 getUser·p1.00:   29.590 ms/op

Iteration   3: 3.871 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   2.384 ms/op
                 getUser·p0.50:   3.846 ms/op
                 getUser·p0.90:   4.432 ms/op
                 getUser·p0.95:   4.850 ms/op
                 getUser·p0.99:   6.300 ms/op
                 getUser·p0.999:  9.741 ms/op
                 getUser·p0.9999: 27.926 ms/op
                 getUser·p1.00:   29.295 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 242497
  mean =      3.956 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 103 
    [ 2.500,  5.000) = 229352 
    [ 5.000,  7.500) = 10630 
    [ 7.500, 10.000) = 1766 
    [10.000, 12.500) = 369 
    [12.500, 15.000) = 12 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 105 

  Percentiles, ms/op:
      p(0.0000) =      1.610 ms/op
     p(50.0000) =      3.813 ms/op
     p(90.0000) =      4.440 ms/op
     p(95.0000) =      5.120 ms/op
     p(99.0000) =      7.496 ms/op
     p(99.9000) =     19.956 ms/op
     p(99.9900) =     28.197 ms/op
     p(99.9990) =     29.295 ms/op
     p(99.9999) =     29.590 ms/op
    p(100.0000) =     29.590 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 14.542 ±(99.9%) 0.232 ms/op
# Warmup Iteration   2: 5.571 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 4.808 ±(99.9%) 0.016 ms/op
Iteration   1: 4.647 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.335 ms/op
                 listUser·p0.50:   4.465 ms/op
                 listUser·p0.90:   5.038 ms/op
                 listUser·p0.95:   5.407 ms/op
                 listUser·p0.99:   8.274 ms/op
                 listUser·p0.999:  25.068 ms/op
                 listUser·p0.9999: 31.134 ms/op
                 listUser·p1.00:   31.752 ms/op

Iteration   2: 4.715 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   2.064 ms/op
                 listUser·p0.50:   4.547 ms/op
                 listUser·p0.90:   5.136 ms/op
                 listUser·p0.95:   5.751 ms/op
                 listUser·p0.99:   8.667 ms/op
                 listUser·p0.999:  20.021 ms/op
                 listUser·p0.9999: 24.674 ms/op
                 listUser·p1.00:   25.100 ms/op

Iteration   3: 4.662 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.499 ms/op
                 listUser·p0.50:   4.432 ms/op
                 listUser·p0.90:   5.128 ms/op
                 listUser·p0.95:   5.784 ms/op
                 listUser·p0.99:   8.995 ms/op
                 listUser·p0.999:  16.548 ms/op
                 listUser·p0.9999: 18.756 ms/op
                 listUser·p1.00:   20.316 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 205316
  mean =      4.675 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11 
    [ 2.500,  5.000) = 179173 
    [ 5.000,  7.500) = 20975 
    [ 7.500, 10.000) = 4107 
    [10.000, 12.500) = 491 
    [12.500, 15.000) = 135 
    [15.000, 17.500) = 123 
    [17.500, 20.000) = 72 
    [20.000, 22.500) = 62 
    [22.500, 25.000) = 94 
    [25.000, 27.500) = 41 
    [27.500, 30.000) = 12 
    [30.000, 32.500) = 20 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.335 ms/op
     p(50.0000) =      4.481 ms/op
     p(90.0000) =      5.095 ms/op
     p(95.0000) =      5.628 ms/op
     p(99.0000) =      8.667 ms/op
     p(99.9000) =     20.928 ms/op
     p(99.9900) =     29.981 ms/op
     p(99.9990) =     31.643 ms/op
     p(99.9999) =     31.752 ms/op
    p(100.0000) =     31.752 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.822 ± 7.908  ops/ms
ClientPb.existUser                       thrpt       3   8.320 ± 2.434  ops/ms
ClientPb.getUser                         thrpt       3   7.982 ± 3.707  ops/ms
ClientPb.listUser                        thrpt       3   6.721 ± 0.978  ops/ms
ClientPb.createUser                       avgt       3   4.053 ± 1.311   ms/op
ClientPb.existUser                        avgt       3   3.805 ± 1.956   ms/op
ClientPb.getUser                          avgt       3   4.050 ± 2.118   ms/op
ClientPb.listUser                         avgt       3   4.690 ± 1.965   ms/op
ClientPb.createUser                     sample  236725   4.058 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.662           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.903           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.686           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.095           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.184           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.045           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.255           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.554           ms/op
ClientPb.existUser                      sample  247569   3.874 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.489           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.727           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.325           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.817           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.102           ms/op
ClientPb.existUser:existUser·p0.999     sample          16.936           ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.445           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.509           ms/op
ClientPb.getUser                        sample  242497   3.956 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.610           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.813           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.440           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.120           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.496           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.956           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.197           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.590           ms/op
ClientPb.listUser                       sample  205316   4.675 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.335           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.481           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.095           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.628           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.667           ms/op
ClientPb.listUser:listUser·p0.999       sample          20.928           ms/op
ClientPb.listUser:listUser·p0.9999      sample          29.981           ms/op
ClientPb.listUser:listUser·p1.00        sample          31.752           ms/op
