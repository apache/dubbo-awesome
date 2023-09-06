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
# Warmup Iteration   1: 1.609 ops/ms
# Warmup Iteration   2: 3.556 ops/ms
# Warmup Iteration   3: 7.176 ops/ms
Iteration   1: 7.448 ops/ms
Iteration   2: 7.889 ops/ms
Iteration   3: 7.767 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.701 ±(99.9%) 4.156 ops/ms [Average]
  (min, avg, max) = (7.448, 7.701, 7.889), stdev = 0.228
  CI (99.9%): [3.546, 11.857] (assumes normal distribution)


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
# Warmup Iteration   1: 2.143 ops/ms
# Warmup Iteration   2: 6.150 ops/ms
# Warmup Iteration   3: 7.779 ops/ms
Iteration   1: 8.285 ops/ms
Iteration   2: 7.877 ops/ms
Iteration   3: 8.304 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.155 ±(99.9%) 4.397 ops/ms [Average]
  (min, avg, max) = (7.877, 8.155, 8.304), stdev = 0.241
  CI (99.9%): [3.758, 12.552] (assumes normal distribution)


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
# Warmup Iteration   1: 2.208 ops/ms
# Warmup Iteration   2: 6.103 ops/ms
# Warmup Iteration   3: 7.472 ops/ms
Iteration   1: 7.696 ops/ms
Iteration   2: 7.906 ops/ms
Iteration   3: 7.708 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.770 ±(99.9%) 2.152 ops/ms [Average]
  (min, avg, max) = (7.696, 7.770, 7.906), stdev = 0.118
  CI (99.9%): [5.618, 9.922] (assumes normal distribution)


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
# Warmup Iteration   1: 1.866 ops/ms
# Warmup Iteration   2: 5.286 ops/ms
# Warmup Iteration   3: 6.579 ops/ms
Iteration   1: 6.605 ops/ms
Iteration   2: 6.526 ops/ms
Iteration   3: 6.573 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.568 ±(99.9%) 0.723 ops/ms [Average]
  (min, avg, max) = (6.526, 6.568, 6.605), stdev = 0.040
  CI (99.9%): [5.845, 7.291] (assumes normal distribution)


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
# Warmup Iteration   1: 13.958 ±(99.9%) 0.073 ms/op
# Warmup Iteration   2: 4.952 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.470 ±(99.9%) 0.004 ms/op
Iteration   1: 4.152 ±(99.9%) 0.008 ms/op
Iteration   2: 4.064 ±(99.9%) 0.009 ms/op
Iteration   3: 3.945 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.054 ±(99.9%) 1.897 ms/op [Average]
  (min, avg, max) = (3.945, 4.054, 4.152), stdev = 0.104
  CI (99.9%): [2.157, 5.951] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 11.666 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 4.299 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.890 ±(99.9%) 0.012 ms/op
Iteration   1: 3.877 ±(99.9%) 0.006 ms/op
Iteration   2: 3.774 ±(99.9%) 0.006 ms/op
Iteration   3: 3.939 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.863 ±(99.9%) 1.528 ms/op [Average]
  (min, avg, max) = (3.774, 3.863, 3.939), stdev = 0.084
  CI (99.9%): [2.336, 5.391] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 12.592 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 4.534 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.245 ±(99.9%) 0.005 ms/op
Iteration   1: 4.215 ±(99.9%) 0.003 ms/op
Iteration   2: 4.091 ±(99.9%) 0.006 ms/op
Iteration   3: 4.111 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.139 ±(99.9%) 1.212 ms/op [Average]
  (min, avg, max) = (4.091, 4.139, 4.215), stdev = 0.066
  CI (99.9%): [2.927, 5.351] (assumes normal distribution)


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
# Warmup Iteration   1: 14.795 ±(99.9%) 0.070 ms/op
# Warmup Iteration   2: 5.639 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.855 ±(99.9%) 0.009 ms/op
Iteration   1: 4.758 ±(99.9%) 0.008 ms/op
Iteration   2: 4.745 ±(99.9%) 0.010 ms/op
Iteration   3: 4.767 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.757 ±(99.9%) 0.201 ms/op [Average]
  (min, avg, max) = (4.745, 4.757, 4.767), stdev = 0.011
  CI (99.9%): [4.555, 4.958] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 14.017 ±(99.9%) 0.204 ms/op
# Warmup Iteration   2: 5.126 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 4.474 ±(99.9%) 0.019 ms/op
Iteration   1: 4.064 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.985 ms/op
                 createUser·p0.50:   3.846 ms/op
                 createUser·p0.90:   4.719 ms/op
                 createUser·p0.95:   5.374 ms/op
                 createUser·p0.99:   7.602 ms/op
                 createUser·p0.999:  24.225 ms/op
                 createUser·p0.9999: 29.124 ms/op
                 createUser·p1.00:   30.376 ms/op

Iteration   2: 3.967 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.731 ms/op
                 createUser·p0.50:   3.817 ms/op
                 createUser·p0.90:   4.432 ms/op
                 createUser·p0.95:   4.735 ms/op
                 createUser·p0.99:   7.306 ms/op
                 createUser·p0.999:  25.985 ms/op
                 createUser·p0.9999: 30.136 ms/op
                 createUser·p1.00:   30.671 ms/op

Iteration   3: 4.141 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   1.100 ms/op
                 createUser·p0.50:   3.940 ms/op
                 createUser·p0.90:   4.801 ms/op
                 createUser·p0.95:   5.480 ms/op
                 createUser·p0.99:   8.045 ms/op
                 createUser·p0.999:  29.989 ms/op
                 createUser·p0.9999: 32.440 ms/op
                 createUser·p1.00:   33.686 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 236587
  mean =      4.056 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 293 
    [ 2.500,  5.000) = 222005 
    [ 5.000,  7.500) = 11730 
    [ 7.500, 10.000) = 1575 
    [10.000, 12.500) = 491 
    [12.500, 15.000) = 107 
    [15.000, 17.500) = 37 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 49 
    [25.000, 27.500) = 100 
    [27.500, 30.000) = 64 
    [30.000, 32.500) = 83 
    [32.500, 35.000) = 5 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.100 ms/op
     p(50.0000) =      3.875 ms/op
     p(90.0000) =      4.637 ms/op
     p(95.0000) =      5.218 ms/op
     p(99.0000) =      7.660 ms/op
     p(99.9000) =     25.297 ms/op
     p(99.9900) =     31.621 ms/op
     p(99.9990) =     33.160 ms/op
     p(99.9999) =     33.686 ms/op
    p(100.0000) =     33.686 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 14.063 ±(99.9%) 0.175 ms/op
# Warmup Iteration   2: 4.635 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.249 ±(99.9%) 0.015 ms/op
Iteration   1: 4.017 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.974 ms/op
                 existUser·p0.50:   3.858 ms/op
                 existUser·p0.90:   4.669 ms/op
                 existUser·p0.95:   5.186 ms/op
                 existUser·p0.99:   7.643 ms/op
                 existUser·p0.999:  12.108 ms/op
                 existUser·p0.9999: 27.988 ms/op
                 existUser·p1.00:   28.639 ms/op

Iteration   2: 4.035 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   1.851 ms/op
                 existUser·p0.50:   3.789 ms/op
                 existUser·p0.90:   4.366 ms/op
                 existUser·p0.95:   5.235 ms/op
                 existUser·p0.99:   9.110 ms/op
                 existUser·p0.999:  25.837 ms/op
                 existUser·p0.9999: 53.553 ms/op
                 existUser·p1.00:   59.507 ms/op

Iteration   3: 3.854 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.921 ms/op
                 existUser·p0.50:   3.727 ms/op
                 existUser·p0.90:   4.080 ms/op
                 existUser·p0.95:   4.522 ms/op
                 existUser·p0.99:   7.897 ms/op
                 existUser·p0.999:  13.451 ms/op
                 existUser·p0.9999: 32.251 ms/op
                 existUser·p1.00:   33.260 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 241837
  mean =      3.967 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 229449 
    [ 5.000, 10.000) = 11252 
    [10.000, 15.000) = 859 
    [15.000, 20.000) = 35 
    [20.000, 25.000) = 37 
    [25.000, 30.000) = 137 
    [30.000, 35.000) = 36 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 0 
    [45.000, 50.000) = 0 
    [50.000, 55.000) = 30 

  Percentiles, ms/op:
      p(0.0000) =      1.851 ms/op
     p(50.0000) =      3.789 ms/op
     p(90.0000) =      4.407 ms/op
     p(95.0000) =      5.030 ms/op
     p(99.0000) =      8.520 ms/op
     p(99.9000) =     20.042 ms/op
     p(99.9900) =     52.691 ms/op
     p(99.9990) =     57.560 ms/op
     p(99.9999) =     59.507 ms/op
    p(100.0000) =     59.507 ms/op


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
# Warmup Iteration   1: 14.262 ±(99.9%) 0.233 ms/op
# Warmup Iteration   2: 5.092 ±(99.9%) 0.031 ms/op
# Warmup Iteration   3: 4.273 ±(99.9%) 0.014 ms/op
Iteration   1: 4.231 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   2.015 ms/op
                 getUser·p0.50:   4.022 ms/op
                 getUser·p0.90:   4.653 ms/op
                 getUser·p0.95:   5.964 ms/op
                 getUser·p0.99:   8.913 ms/op
                 getUser·p0.999:  21.037 ms/op
                 getUser·p0.9999: 31.832 ms/op
                 getUser·p1.00:   32.702 ms/op

Iteration   2: 4.012 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   2.253 ms/op
                 getUser·p0.50:   3.846 ms/op
                 getUser·p0.90:   4.506 ms/op
                 getUser·p0.95:   5.202 ms/op
                 getUser·p0.99:   7.856 ms/op
                 getUser·p0.999:  25.767 ms/op
                 getUser·p0.9999: 28.875 ms/op
                 getUser·p1.00:   31.982 ms/op

Iteration   3: 4.109 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.950 ms/op
                 getUser·p0.50:   3.944 ms/op
                 getUser·p0.90:   4.530 ms/op
                 getUser·p0.95:   4.956 ms/op
                 getUser·p0.99:   7.619 ms/op
                 getUser·p0.999:  14.615 ms/op
                 getUser·p0.9999: 29.414 ms/op
                 getUser·p1.00:   30.245 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 233065
  mean =      4.115 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 49 
    [ 2.500,  5.000) = 219332 
    [ 5.000,  7.500) = 10302 
    [ 7.500, 10.000) = 2154 
    [10.000, 12.500) = 804 
    [12.500, 15.000) = 149 
    [15.000, 17.500) = 19 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 111 
    [27.500, 30.000) = 77 
    [30.000, 32.500) = 22 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.950 ms/op
     p(50.0000) =      3.928 ms/op
     p(90.0000) =      4.563 ms/op
     p(95.0000) =      5.259 ms/op
     p(99.0000) =      8.290 ms/op
     p(99.9000) =     21.103 ms/op
     p(99.9900) =     30.038 ms/op
     p(99.9990) =     32.572 ms/op
     p(99.9999) =     32.702 ms/op
    p(100.0000) =     32.702 ms/op


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
# Warmup Iteration   1: 16.158 ±(99.9%) 0.262 ms/op
# Warmup Iteration   2: 5.945 ±(99.9%) 0.033 ms/op
# Warmup Iteration   3: 5.159 ±(99.9%) 0.021 ms/op
Iteration   1: 4.889 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.931 ms/op
                 listUser·p0.50:   4.563 ms/op
                 listUser·p0.90:   5.497 ms/op
                 listUser·p0.95:   6.980 ms/op
                 listUser·p0.99:   10.371 ms/op
                 listUser·p0.999:  26.496 ms/op
                 listUser·p0.9999: 36.614 ms/op
                 listUser·p1.00:   37.552 ms/op

Iteration   2: 4.913 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   2.298 ms/op
                 listUser·p0.50:   4.743 ms/op
                 listUser·p0.90:   5.415 ms/op
                 listUser·p0.95:   6.013 ms/op
                 listUser·p0.99:   9.667 ms/op
                 listUser·p0.999:  19.592 ms/op
                 listUser·p0.9999: 25.313 ms/op
                 listUser·p1.00:   25.919 ms/op

Iteration   3: 4.825 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.931 ms/op
                 listUser·p0.50:   4.645 ms/op
                 listUser·p0.90:   5.218 ms/op
                 listUser·p0.95:   5.683 ms/op
                 listUser·p0.99:   9.273 ms/op
                 listUser·p0.999:  18.439 ms/op
                 listUser·p0.9999: 21.416 ms/op
                 listUser·p1.00:   22.446 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 196771
  mean =      4.875 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18 
    [ 2.500,  5.000) = 157581 
    [ 5.000,  7.500) = 32912 
    [ 7.500, 10.000) = 4477 
    [10.000, 12.500) = 1132 
    [12.500, 15.000) = 196 
    [15.000, 17.500) = 109 
    [17.500, 20.000) = 154 
    [20.000, 22.500) = 45 
    [22.500, 25.000) = 44 
    [25.000, 27.500) = 59 
    [27.500, 30.000) = 12 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 11 
    [35.000, 37.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      1.931 ms/op
     p(50.0000) =      4.645 ms/op
     p(90.0000) =      5.366 ms/op
     p(95.0000) =      6.201 ms/op
     p(99.0000) =      9.830 ms/op
     p(99.9000) =     19.759 ms/op
     p(99.9900) =     34.210 ms/op
     p(99.9990) =     37.235 ms/op
     p(99.9999) =     37.552 ms/op
    p(100.0000) =     37.552 ms/op


# Run complete. Total time: 00:13:17

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.701 ± 4.156  ops/ms
ClientPb.existUser                       thrpt       3   8.155 ± 4.397  ops/ms
ClientPb.getUser                         thrpt       3   7.770 ± 2.152  ops/ms
ClientPb.listUser                        thrpt       3   6.568 ± 0.723  ops/ms
ClientPb.createUser                       avgt       3   4.054 ± 1.897   ms/op
ClientPb.existUser                        avgt       3   3.863 ± 1.528   ms/op
ClientPb.getUser                          avgt       3   4.139 ± 1.212   ms/op
ClientPb.listUser                         avgt       3   4.757 ± 0.201   ms/op
ClientPb.createUser                     sample  236587   4.056 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.100           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.875           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.637           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.218           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.660           ms/op
ClientPb.createUser:createUser·p0.999   sample          25.297           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.621           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.686           ms/op
ClientPb.existUser                      sample  241837   3.967 ± 0.008   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.851           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.789           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.407           ms/op
ClientPb.existUser:existUser·p0.95      sample           5.030           ms/op
ClientPb.existUser:existUser·p0.99      sample           8.520           ms/op
ClientPb.existUser:existUser·p0.999     sample          20.042           ms/op
ClientPb.existUser:existUser·p0.9999    sample          52.691           ms/op
ClientPb.existUser:existUser·p1.00      sample          59.507           ms/op
ClientPb.getUser                        sample  233065   4.115 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.950           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.928           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.563           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.259           ms/op
ClientPb.getUser:getUser·p0.99          sample           8.290           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.103           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.038           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.702           ms/op
ClientPb.listUser                       sample  196771   4.875 ± 0.009   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.931           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.645           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.366           ms/op
ClientPb.listUser:listUser·p0.95        sample           6.201           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.830           ms/op
ClientPb.listUser:listUser·p0.999       sample          19.759           ms/op
ClientPb.listUser:listUser·p0.9999      sample          34.210           ms/op
ClientPb.listUser:listUser·p1.00        sample          37.552           ms/op
