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
# Warmup Iteration   1: 1.558 ops/ms
# Warmup Iteration   2: 3.479 ops/ms
# Warmup Iteration   3: 7.117 ops/ms
Iteration   1: 7.538 ops/ms
Iteration   2: 7.935 ops/ms
Iteration   3: 7.980 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.818 ±(99.9%) 4.436 ops/ms [Average]
  (min, avg, max) = (7.538, 7.818, 7.980), stdev = 0.243
  CI (99.9%): [3.382, 12.253] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:13
# Fork: 1 of 1
# Warmup Iteration   1: 2.378 ops/ms
# Warmup Iteration   2: 7.207 ops/ms
# Warmup Iteration   3: 8.617 ops/ms
Iteration   1: 8.880 ops/ms
Iteration   2: 8.560 ops/ms
Iteration   3: 8.406 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.615 ±(99.9%) 4.415 ops/ms [Average]
  (min, avg, max) = (8.406, 8.615, 8.880), stdev = 0.242
  CI (99.9%): [4.200, 13.031] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.113 ops/ms
# Warmup Iteration   2: 6.672 ops/ms
# Warmup Iteration   3: 8.221 ops/ms
Iteration   1: 8.451 ops/ms
Iteration   2: 7.975 ops/ms
Iteration   3: 8.120 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.182 ±(99.9%) 4.453 ops/ms [Average]
  (min, avg, max) = (7.975, 8.182, 8.451), stdev = 0.244
  CI (99.9%): [3.729, 12.635] (assumes normal distribution)


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
# Warmup Iteration   1: 2.488 ops/ms
# Warmup Iteration   2: 6.046 ops/ms
# Warmup Iteration   3: 6.673 ops/ms
Iteration   1: 6.699 ops/ms
Iteration   2: 7.025 ops/ms
Iteration   3: 6.949 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.891 ±(99.9%) 3.107 ops/ms [Average]
  (min, avg, max) = (6.699, 6.891, 7.025), stdev = 0.170
  CI (99.9%): [3.784, 9.998] (assumes normal distribution)


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
# Warmup Iteration   1: 10.462 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 4.463 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.298 ±(99.9%) 0.006 ms/op
Iteration   1: 4.103 ±(99.9%) 0.007 ms/op
Iteration   2: 4.040 ±(99.9%) 0.005 ms/op
Iteration   3: 4.014 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.053 ±(99.9%) 0.836 ms/op [Average]
  (min, avg, max) = (4.014, 4.053, 4.103), stdev = 0.046
  CI (99.9%): [3.217, 4.888] (assumes normal distribution)


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
# Warmup Iteration   1: 11.296 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 4.200 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.931 ±(99.9%) 0.004 ms/op
Iteration   1: 3.946 ±(99.9%) 0.008 ms/op
Iteration   2: 3.826 ±(99.9%) 0.004 ms/op
Iteration   3: 3.849 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.874 ±(99.9%) 1.157 ms/op [Average]
  (min, avg, max) = (3.826, 3.874, 3.946), stdev = 0.063
  CI (99.9%): [2.717, 5.031] (assumes normal distribution)


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
# Warmup Iteration   1: 11.161 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 4.252 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.964 ±(99.9%) 0.010 ms/op
Iteration   1: 3.940 ±(99.9%) 0.008 ms/op
Iteration   2: 4.028 ±(99.9%) 0.007 ms/op
Iteration   3: 3.905 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.958 ±(99.9%) 1.151 ms/op [Average]
  (min, avg, max) = (3.905, 3.958, 4.028), stdev = 0.063
  CI (99.9%): [2.807, 5.108] (assumes normal distribution)


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
# Warmup Iteration   1: 11.406 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 4.981 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.353 ±(99.9%) 0.012 ms/op
Iteration   1: 4.762 ±(99.9%) 0.010 ms/op
Iteration   2: 4.622 ±(99.9%) 0.009 ms/op
Iteration   3: 4.465 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.616 ±(99.9%) 2.704 ms/op [Average]
  (min, avg, max) = (4.465, 4.616, 4.762), stdev = 0.148
  CI (99.9%): [1.913, 7.320] (assumes normal distribution)


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
# Warmup Iteration   1: 12.150 ±(99.9%) 0.170 ms/op
# Warmup Iteration   2: 4.574 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 3.969 ±(99.9%) 0.015 ms/op
Iteration   1: 3.727 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.518 ms/op
                 createUser·p0.50:   3.613 ms/op
                 createUser·p0.90:   4.301 ms/op
                 createUser·p0.95:   4.948 ms/op
                 createUser·p0.99:   7.636 ms/op
                 createUser·p0.999:  22.388 ms/op
                 createUser·p0.9999: 24.748 ms/op
                 createUser·p1.00:   26.706 ms/op

Iteration   2: 3.803 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.522 ms/op
                 createUser·p0.50:   3.682 ms/op
                 createUser·p0.90:   4.293 ms/op
                 createUser·p0.95:   5.259 ms/op
                 createUser·p0.99:   7.848 ms/op
                 createUser·p0.999:  11.729 ms/op
                 createUser·p0.9999: 26.704 ms/op
                 createUser·p1.00:   27.689 ms/op

Iteration   3: 3.819 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.665 ms/op
                 createUser·p0.50:   3.617 ms/op
                 createUser·p0.90:   4.497 ms/op
                 createUser·p0.95:   5.267 ms/op
                 createUser·p0.99:   7.396 ms/op
                 createUser·p0.999:  26.135 ms/op
                 createUser·p0.9999: 39.059 ms/op
                 createUser·p1.00:   39.780 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 253688
  mean =      3.783 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2544 
    [ 2.500,  5.000) = 237277 
    [ 5.000,  7.500) = 11113 
    [ 7.500, 10.000) = 1976 
    [10.000, 12.500) = 401 
    [12.500, 15.000) = 79 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 107 
    [25.000, 27.500) = 97 
    [27.500, 30.000) = 6 
    [30.000, 32.500) = 19 
    [32.500, 35.000) = 12 
    [35.000, 37.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      1.518 ms/op
     p(50.0000) =      3.637 ms/op
     p(90.0000) =      4.375 ms/op
     p(95.0000) =      5.161 ms/op
     p(99.0000) =      7.692 ms/op
     p(99.9000) =     23.144 ms/op
     p(99.9900) =     37.618 ms/op
     p(99.9990) =     39.614 ms/op
     p(99.9999) =     39.780 ms/op
    p(100.0000) =     39.780 ms/op


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
# Warmup Iteration   1: 10.325 ±(99.9%) 0.139 ms/op
# Warmup Iteration   2: 4.215 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.814 ±(99.9%) 0.011 ms/op
Iteration   1: 3.717 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.524 ms/op
                 existUser·p0.50:   3.629 ms/op
                 existUser·p0.90:   3.944 ms/op
                 existUser·p0.95:   4.334 ms/op
                 existUser·p0.99:   7.550 ms/op
                 existUser·p0.999:  16.047 ms/op
                 existUser·p0.9999: 38.072 ms/op
                 existUser·p1.00:   41.091 ms/op

Iteration   2: 3.865 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   2.021 ms/op
                 existUser·p0.50:   3.666 ms/op
                 existUser·p0.90:   4.555 ms/op
                 existUser·p0.95:   5.169 ms/op
                 existUser·p0.99:   7.209 ms/op
                 existUser·p0.999:  17.400 ms/op
                 existUser·p0.9999: 28.007 ms/op
                 existUser·p1.00:   32.342 ms/op

Iteration   3: 3.827 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   1.849 ms/op
                 existUser·p0.50:   3.600 ms/op
                 existUser·p0.90:   4.342 ms/op
                 existUser·p0.95:   5.145 ms/op
                 existUser·p0.99:   7.593 ms/op
                 existUser·p0.999:  30.294 ms/op
                 existUser·p0.9999: 41.484 ms/op
                 existUser·p1.00:   42.861 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 252438
  mean =      3.802 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 239388 
    [ 5.000, 10.000) = 12041 
    [10.000, 15.000) = 708 
    [15.000, 20.000) = 65 
    [20.000, 25.000) = 34 
    [25.000, 30.000) = 73 
    [30.000, 35.000) = 71 
    [35.000, 40.000) = 27 
    [40.000, 45.000) = 31 

  Percentiles, ms/op:
      p(0.0000) =      1.524 ms/op
     p(50.0000) =      3.633 ms/op
     p(90.0000) =      4.276 ms/op
     p(95.0000) =      5.038 ms/op
     p(99.0000) =      7.447 ms/op
     p(99.9000) =     17.648 ms/op
     p(99.9900) =     40.223 ms/op
     p(99.9990) =     42.695 ms/op
     p(99.9999) =     42.861 ms/op
    p(100.0000) =     42.861 ms/op


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
# Warmup Iteration   1: 13.375 ±(99.9%) 0.187 ms/op
# Warmup Iteration   2: 5.043 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 4.335 ±(99.9%) 0.018 ms/op
Iteration   1: 4.091 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   2.042 ms/op
                 getUser·p0.50:   3.879 ms/op
                 getUser·p0.90:   4.555 ms/op
                 getUser·p0.95:   5.030 ms/op
                 getUser·p0.99:   8.503 ms/op
                 getUser·p0.999:  18.612 ms/op
                 getUser·p0.9999: 25.893 ms/op
                 getUser·p1.00:   27.394 ms/op

Iteration   2: 4.150 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.360 ms/op
                 getUser·p0.50:   3.912 ms/op
                 getUser·p0.90:   4.645 ms/op
                 getUser·p0.95:   5.644 ms/op
                 getUser·p0.99:   8.864 ms/op
                 getUser·p0.999:  24.674 ms/op
                 getUser·p0.9999: 27.853 ms/op
                 getUser·p1.00:   28.869 ms/op

Iteration   3: 3.920 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.864 ms/op
                 getUser·p0.50:   3.785 ms/op
                 getUser·p0.90:   4.309 ms/op
                 getUser·p0.95:   4.628 ms/op
                 getUser·p0.99:   7.750 ms/op
                 getUser·p0.999:  14.224 ms/op
                 getUser·p0.9999: 35.193 ms/op
                 getUser·p1.00:   37.290 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 236784
  mean =      4.051 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 67 
    [ 2.500,  5.000) = 224230 
    [ 5.000,  7.500) = 8251 
    [ 7.500, 10.000) = 3167 
    [10.000, 12.500) = 596 
    [12.500, 15.000) = 146 
    [15.000, 17.500) = 66 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 58 
    [25.000, 27.500) = 109 
    [27.500, 30.000) = 22 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 17 
    [35.000, 37.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      1.360 ms/op
     p(50.0000) =      3.858 ms/op
     p(90.0000) =      4.497 ms/op
     p(95.0000) =      5.071 ms/op
     p(99.0000) =      8.503 ms/op
     p(99.9000) =     18.612 ms/op
     p(99.9900) =     33.772 ms/op
     p(99.9990) =     35.389 ms/op
     p(99.9999) =     37.290 ms/op
    p(100.0000) =     37.290 ms/op


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
# Warmup Iteration   1: 14.877 ±(99.9%) 0.210 ms/op
# Warmup Iteration   2: 5.985 ±(99.9%) 0.037 ms/op
# Warmup Iteration   3: 4.780 ±(99.9%) 0.019 ms/op
Iteration   1: 4.816 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   2.327 ms/op
                 listUser·p0.50:   4.530 ms/op
                 listUser·p0.90:   5.341 ms/op
                 listUser·p0.95:   6.787 ms/op
                 listUser·p0.99:   9.830 ms/op
                 listUser·p0.999:  30.878 ms/op
                 listUser·p0.9999: 39.387 ms/op
                 listUser·p1.00:   40.108 ms/op

Iteration   2: 4.648 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.884 ms/op
                 listUser·p0.50:   4.489 ms/op
                 listUser·p0.90:   5.038 ms/op
                 listUser·p0.95:   5.628 ms/op
                 listUser·p0.99:   8.765 ms/op
                 listUser·p0.999:  19.042 ms/op
                 listUser·p0.9999: 23.921 ms/op
                 listUser·p1.00:   28.967 ms/op

Iteration   3: 4.779 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   2.552 ms/op
                 listUser·p0.50:   4.522 ms/op
                 listUser·p0.90:   5.374 ms/op
                 listUser·p0.95:   6.676 ms/op
                 listUser·p0.99:   9.667 ms/op
                 listUser·p0.999:  17.924 ms/op
                 listUser·p0.9999: 23.472 ms/op
                 listUser·p1.00:   25.068 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 202376
  mean =      4.747 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 169362 
    [ 5.000, 10.000) = 31581 
    [10.000, 15.000) = 1017 
    [15.000, 20.000) = 165 
    [20.000, 25.000) = 118 
    [25.000, 30.000) = 47 
    [30.000, 35.000) = 54 
    [35.000, 40.000) = 31 
    [40.000, 45.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.884 ms/op
     p(50.0000) =      4.506 ms/op
     p(90.0000) =      5.259 ms/op
     p(95.0000) =      6.391 ms/op
     p(99.0000) =      9.437 ms/op
     p(99.9000) =     21.463 ms/op
     p(99.9900) =     38.011 ms/op
     p(99.9990) =     39.713 ms/op
     p(99.9999) =     40.108 ms/op
    p(100.0000) =     40.108 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.818 ± 4.436  ops/ms
ClientPb.existUser                       thrpt       3   8.615 ± 4.415  ops/ms
ClientPb.getUser                         thrpt       3   8.182 ± 4.453  ops/ms
ClientPb.listUser                        thrpt       3   6.891 ± 3.107  ops/ms
ClientPb.createUser                       avgt       3   4.053 ± 0.836   ms/op
ClientPb.existUser                        avgt       3   3.874 ± 1.157   ms/op
ClientPb.getUser                          avgt       3   3.958 ± 1.151   ms/op
ClientPb.listUser                         avgt       3   4.616 ± 2.704   ms/op
ClientPb.createUser                     sample  253688   3.783 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.518           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.637           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.375           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.161           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.692           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.144           ms/op
ClientPb.createUser:createUser·p0.9999  sample          37.618           ms/op
ClientPb.createUser:createUser·p1.00    sample          39.780           ms/op
ClientPb.existUser                      sample  252438   3.802 ± 0.008   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.524           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.633           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.276           ms/op
ClientPb.existUser:existUser·p0.95      sample           5.038           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.447           ms/op
ClientPb.existUser:existUser·p0.999     sample          17.648           ms/op
ClientPb.existUser:existUser·p0.9999    sample          40.223           ms/op
ClientPb.existUser:existUser·p1.00      sample          42.861           ms/op
ClientPb.getUser                        sample  236784   4.051 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.360           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.858           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.497           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.071           ms/op
ClientPb.getUser:getUser·p0.99          sample           8.503           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.612           ms/op
ClientPb.getUser:getUser·p0.9999        sample          33.772           ms/op
ClientPb.getUser:getUser·p1.00          sample          37.290           ms/op
ClientPb.listUser                       sample  202376   4.747 ± 0.009   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.884           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.506           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.259           ms/op
ClientPb.listUser:listUser·p0.95        sample           6.391           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.437           ms/op
ClientPb.listUser:listUser·p0.999       sample          21.463           ms/op
ClientPb.listUser:listUser·p0.9999      sample          38.011           ms/op
ClientPb.listUser:listUser·p1.00        sample          40.108           ms/op
