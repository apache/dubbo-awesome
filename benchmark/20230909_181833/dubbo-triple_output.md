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
# Warmup Iteration   1: 1.842 ops/ms
# Warmup Iteration   2: 4.551 ops/ms
# Warmup Iteration   3: 8.019 ops/ms
Iteration   1: 8.300 ops/ms
Iteration   2: 8.698 ops/ms
Iteration   3: 8.473 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.490 ±(99.9%) 3.640 ops/ms [Average]
  (min, avg, max) = (8.300, 8.490, 8.698), stdev = 0.199
  CI (99.9%): [4.851, 12.130] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.547 ops/ms
# Warmup Iteration   2: 7.984 ops/ms
# Warmup Iteration   3: 8.859 ops/ms
Iteration   1: 9.470 ops/ms
Iteration   2: 9.258 ops/ms
Iteration   3: 9.029 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.252 ±(99.9%) 4.021 ops/ms [Average]
  (min, avg, max) = (9.029, 9.252, 9.470), stdev = 0.220
  CI (99.9%): [5.231, 13.273] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 2.714 ops/ms
# Warmup Iteration   2: 7.983 ops/ms
# Warmup Iteration   3: 8.204 ops/ms
Iteration   1: 8.613 ops/ms
Iteration   2: 8.907 ops/ms
Iteration   3: 8.429 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.650 ±(99.9%) 4.395 ops/ms [Average]
  (min, avg, max) = (8.429, 8.650, 8.907), stdev = 0.241
  CI (99.9%): [4.254, 13.045] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 2.513 ops/ms
# Warmup Iteration   2: 6.629 ops/ms
# Warmup Iteration   3: 7.120 ops/ms
Iteration   1: 7.254 ops/ms
Iteration   2: 7.250 ops/ms
Iteration   3: 7.277 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.260 ±(99.9%) 0.265 ops/ms [Average]
  (min, avg, max) = (7.250, 7.260, 7.277), stdev = 0.015
  CI (99.9%): [6.995, 7.525] (assumes normal distribution)


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
# Warmup Iteration   1: 13.600 ±(99.9%) 0.070 ms/op
# Warmup Iteration   2: 4.314 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.940 ±(99.9%) 0.004 ms/op
Iteration   1: 3.733 ±(99.9%) 0.008 ms/op
Iteration   2: 3.753 ±(99.9%) 0.008 ms/op
Iteration   3: 3.676 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.720 ±(99.9%) 0.728 ms/op [Average]
  (min, avg, max) = (3.676, 3.720, 3.753), stdev = 0.040
  CI (99.9%): [2.992, 4.449] (assumes normal distribution)


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
# Warmup Iteration   1: 10.851 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.890 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.707 ±(99.9%) 0.002 ms/op
Iteration   1: 3.703 ±(99.9%) 0.003 ms/op
Iteration   2: 3.634 ±(99.9%) 0.006 ms/op
Iteration   3: 3.616 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.651 ±(99.9%) 0.831 ms/op [Average]
  (min, avg, max) = (3.616, 3.651, 3.703), stdev = 0.046
  CI (99.9%): [2.820, 4.482] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 10.461 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 4.057 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.785 ±(99.9%) 0.003 ms/op
Iteration   1: 3.768 ±(99.9%) 0.004 ms/op
Iteration   2: 3.825 ±(99.9%) 0.007 ms/op
Iteration   3: 3.666 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.753 ±(99.9%) 1.467 ms/op [Average]
  (min, avg, max) = (3.666, 3.753, 3.825), stdev = 0.080
  CI (99.9%): [2.286, 5.220] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 12.997 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 5.084 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.530 ±(99.9%) 0.005 ms/op
Iteration   1: 4.358 ±(99.9%) 0.010 ms/op
Iteration   2: 4.335 ±(99.9%) 0.008 ms/op
Iteration   3: 4.507 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.400 ±(99.9%) 1.700 ms/op [Average]
  (min, avg, max) = (4.335, 4.400, 4.507), stdev = 0.093
  CI (99.9%): [2.701, 6.100] (assumes normal distribution)


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
# Warmup Iteration   1: 11.019 ±(99.9%) 0.137 ms/op
# Warmup Iteration   2: 4.648 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.150 ±(99.9%) 0.018 ms/op
Iteration   1: 3.837 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.632 ms/op
                 createUser·p0.50:   3.645 ms/op
                 createUser·p0.90:   4.432 ms/op
                 createUser·p0.95:   5.284 ms/op
                 createUser·p0.99:   7.537 ms/op
                 createUser·p0.999:  23.895 ms/op
                 createUser·p0.9999: 26.924 ms/op
                 createUser·p1.00:   27.754 ms/op

Iteration   2: 3.731 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.520 ms/op
                 createUser·p0.50:   3.604 ms/op
                 createUser·p0.90:   4.317 ms/op
                 createUser·p0.95:   4.645 ms/op
                 createUser·p0.99:   6.666 ms/op
                 createUser·p0.999:  12.978 ms/op
                 createUser·p0.9999: 31.556 ms/op
                 createUser·p1.00:   32.637 ms/op

Iteration   3: 3.698 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.649 ms/op
                 createUser·p0.50:   3.572 ms/op
                 createUser·p0.90:   4.162 ms/op
                 createUser·p0.95:   4.628 ms/op
                 createUser·p0.99:   7.315 ms/op
                 createUser·p0.999:  24.954 ms/op
                 createUser·p0.9999: 34.954 ms/op
                 createUser·p1.00:   35.914 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 255478
  mean =      3.755 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1734 
    [ 2.500,  5.000) = 243189 
    [ 5.000,  7.500) = 8345 
    [ 7.500, 10.000) = 1549 
    [10.000, 12.500) = 334 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 71 
    [25.000, 27.500) = 87 
    [27.500, 30.000) = 23 
    [30.000, 32.500) = 45 
    [32.500, 35.000) = 23 
    [35.000, 37.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      1.520 ms/op
     p(50.0000) =      3.604 ms/op
     p(90.0000) =      4.301 ms/op
     p(95.0000) =      4.776 ms/op
     p(99.0000) =      7.307 ms/op
     p(99.9000) =     22.983 ms/op
     p(99.9900) =     33.143 ms/op
     p(99.9990) =     35.768 ms/op
     p(99.9999) =     35.914 ms/op
    p(100.0000) =     35.914 ms/op


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
# Warmup Iteration   1: 11.108 ±(99.9%) 0.143 ms/op
# Warmup Iteration   2: 3.997 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.613 ±(99.9%) 0.010 ms/op
Iteration   1: 3.600 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.257 ms/op
                 existUser·p0.50:   3.486 ms/op
                 existUser·p0.90:   4.202 ms/op
                 existUser·p0.95:   4.932 ms/op
                 existUser·p0.99:   6.840 ms/op
                 existUser·p0.999:  20.709 ms/op
                 existUser·p0.9999: 23.302 ms/op
                 existUser·p1.00:   24.150 ms/op

Iteration   2: 3.698 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.573 ms/op
                 existUser·p0.50:   3.576 ms/op
                 existUser·p0.90:   4.301 ms/op
                 existUser·p0.95:   4.866 ms/op
                 existUser·p0.99:   7.176 ms/op
                 existUser·p0.999:  22.922 ms/op
                 existUser·p0.9999: 26.205 ms/op
                 existUser·p1.00:   26.870 ms/op

Iteration   3: 3.470 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.378 ms/op
                 existUser·p0.50:   3.367 ms/op
                 existUser·p0.90:   3.871 ms/op
                 existUser·p0.95:   4.178 ms/op
                 existUser·p0.99:   6.131 ms/op
                 existUser·p0.999:  24.642 ms/op
                 existUser·p0.9999: 28.959 ms/op
                 existUser·p1.00:   31.293 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 267635
  mean =      3.587 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5970 
    [ 2.500,  5.000) = 251887 
    [ 5.000,  7.500) = 7899 
    [ 7.500, 10.000) = 1006 
    [10.000, 12.500) = 470 
    [12.500, 15.000) = 46 
    [15.000, 17.500) = 58 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 70 
    [22.500, 25.000) = 97 
    [25.000, 27.500) = 94 
    [27.500, 30.000) = 26 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.257 ms/op
     p(50.0000) =      3.473 ms/op
     p(90.0000) =      4.100 ms/op
     p(95.0000) =      4.694 ms/op
     p(99.0000) =      6.767 ms/op
     p(99.9000) =     21.192 ms/op
     p(99.9900) =     27.573 ms/op
     p(99.9990) =     29.466 ms/op
     p(99.9999) =     31.293 ms/op
    p(100.0000) =     31.293 ms/op


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
# Warmup Iteration   1: 12.313 ±(99.9%) 0.162 ms/op
# Warmup Iteration   2: 4.150 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.967 ±(99.9%) 0.014 ms/op
Iteration   1: 3.925 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   1.708 ms/op
                 getUser·p0.50:   3.641 ms/op
                 getUser·p0.90:   4.391 ms/op
                 getUser·p0.95:   6.103 ms/op
                 getUser·p0.99:   9.765 ms/op
                 getUser·p0.999:  22.430 ms/op
                 getUser·p0.9999: 28.475 ms/op
                 getUser·p1.00:   29.131 ms/op

Iteration   2: 3.762 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.522 ms/op
                 getUser·p0.50:   3.629 ms/op
                 getUser·p0.90:   4.309 ms/op
                 getUser·p0.95:   5.046 ms/op
                 getUser·p0.99:   6.962 ms/op
                 getUser·p0.999:  12.009 ms/op
                 getUser·p0.9999: 25.526 ms/op
                 getUser·p1.00:   26.608 ms/op

Iteration   3: 3.620 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.901 ms/op
                 getUser·p0.50:   3.531 ms/op
                 getUser·p0.90:   4.014 ms/op
                 getUser·p0.95:   4.293 ms/op
                 getUser·p0.99:   6.268 ms/op
                 getUser·p0.999:  25.829 ms/op
                 getUser·p0.9999: 30.343 ms/op
                 getUser·p1.00:   30.802 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 254905
  mean =      3.765 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1659 
    [ 2.500,  5.000) = 240514 
    [ 5.000,  7.500) = 9201 
    [ 7.500, 10.000) = 2326 
    [10.000, 12.500) = 780 
    [12.500, 15.000) = 110 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 35 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 81 
    [25.000, 27.500) = 82 
    [27.500, 30.000) = 61 
    [30.000, 32.500) = 13 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.522 ms/op
     p(50.0000) =      3.600 ms/op
     p(90.0000) =      4.211 ms/op
     p(95.0000) =      4.997 ms/op
     p(99.0000) =      8.077 ms/op
     p(99.9000) =     21.485 ms/op
     p(99.9900) =     29.214 ms/op
     p(99.9990) =     30.489 ms/op
     p(99.9999) =     30.802 ms/op
    p(100.0000) =     30.802 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 11.598 ±(99.9%) 0.171 ms/op
# Warmup Iteration   2: 4.853 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.655 ±(99.9%) 0.018 ms/op
Iteration   1: 4.325 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.970 ms/op
                 listUser·p0.50:   4.149 ms/op
                 listUser·p0.90:   4.694 ms/op
                 listUser·p0.95:   5.030 ms/op
                 listUser·p0.99:   9.208 ms/op
                 listUser·p0.999:  23.560 ms/op
                 listUser·p0.9999: 27.250 ms/op
                 listUser·p1.00:   28.443 ms/op

Iteration   2: 4.251 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.154 ms/op
                 listUser·p0.50:   4.125 ms/op
                 listUser·p0.90:   4.686 ms/op
                 listUser·p0.95:   5.136 ms/op
                 listUser·p0.99:   8.045 ms/op
                 listUser·p0.999:  16.888 ms/op
                 listUser·p0.9999: 20.135 ms/op
                 listUser·p1.00:   20.611 ms/op

Iteration   3: 4.316 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.171 ms/op
                 listUser·p0.50:   4.137 ms/op
                 listUser·p0.90:   4.964 ms/op
                 listUser·p0.95:   5.407 ms/op
                 listUser·p0.99:   7.957 ms/op
                 listUser·p0.999:  15.079 ms/op
                 listUser·p0.9999: 17.138 ms/op
                 listUser·p1.00:   17.662 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 223391
  mean =      4.297 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 43 
    [ 2.500,  5.000) = 208203 
    [ 5.000,  7.500) = 11510 
    [ 7.500, 10.000) = 2340 
    [10.000, 12.500) = 698 
    [12.500, 15.000) = 267 
    [15.000, 17.500) = 134 
    [17.500, 20.000) = 57 
    [20.000, 22.500) = 40 
    [22.500, 25.000) = 48 
    [25.000, 27.500) = 46 

  Percentiles, ms/op:
      p(0.0000) =      1.970 ms/op
     p(50.0000) =      4.137 ms/op
     p(90.0000) =      4.784 ms/op
     p(95.0000) =      5.259 ms/op
     p(99.0000) =      8.405 ms/op
     p(99.9000) =     17.072 ms/op
     p(99.9900) =     26.542 ms/op
     p(99.9990) =     27.863 ms/op
     p(99.9999) =     28.443 ms/op
    p(100.0000) =     28.443 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.490 ± 3.640  ops/ms
ClientPb.existUser                       thrpt       3   9.252 ± 4.021  ops/ms
ClientPb.getUser                         thrpt       3   8.650 ± 4.395  ops/ms
ClientPb.listUser                        thrpt       3   7.260 ± 0.265  ops/ms
ClientPb.createUser                       avgt       3   3.720 ± 0.728   ms/op
ClientPb.existUser                        avgt       3   3.651 ± 0.831   ms/op
ClientPb.getUser                          avgt       3   3.753 ± 1.467   ms/op
ClientPb.listUser                         avgt       3   4.400 ± 1.700   ms/op
ClientPb.createUser                     sample  255478   3.755 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.520           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.604           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.301           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.776           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.307           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.983           ms/op
ClientPb.createUser:createUser·p0.9999  sample          33.143           ms/op
ClientPb.createUser:createUser·p1.00    sample          35.914           ms/op
ClientPb.existUser                      sample  267635   3.587 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.257           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.473           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.100           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.694           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.767           ms/op
ClientPb.existUser:existUser·p0.999     sample          21.192           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.573           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.293           ms/op
ClientPb.getUser                        sample  254905   3.765 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.522           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.600           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.211           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.997           ms/op
ClientPb.getUser:getUser·p0.99          sample           8.077           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.485           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.214           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.802           ms/op
ClientPb.listUser                       sample  223391   4.297 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.970           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.137           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.784           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.259           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.405           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.072           ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.542           ms/op
ClientPb.listUser:listUser·p1.00        sample          28.443           ms/op
