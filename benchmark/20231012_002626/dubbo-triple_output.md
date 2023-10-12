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
# Warmup Iteration   1: 1.537 ops/ms
# Warmup Iteration   2: 3.721 ops/ms
# Warmup Iteration   3: 7.457 ops/ms
Iteration   1: 7.403 ops/ms
Iteration   2: 7.656 ops/ms
Iteration   3: 7.721 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.593 ±(99.9%) 3.062 ops/ms [Average]
  (min, avg, max) = (7.403, 7.593, 7.721), stdev = 0.168
  CI (99.9%): [4.531, 10.655] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:11
# Fork: 1 of 1
# Warmup Iteration   1: 2.562 ops/ms
# Warmup Iteration   2: 7.266 ops/ms
# Warmup Iteration   3: 7.610 ops/ms
Iteration   1: 8.244 ops/ms
Iteration   2: 8.035 ops/ms
Iteration   3: 8.001 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.094 ±(99.9%) 2.401 ops/ms [Average]
  (min, avg, max) = (8.001, 8.094, 8.244), stdev = 0.132
  CI (99.9%): [5.693, 10.495] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 2.278 ops/ms
# Warmup Iteration   2: 6.729 ops/ms
# Warmup Iteration   3: 8.213 ops/ms
Iteration   1: 7.969 ops/ms
Iteration   2: 8.069 ops/ms
Iteration   3: 7.992 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.010 ±(99.9%) 0.957 ops/ms [Average]
  (min, avg, max) = (7.969, 8.010, 8.069), stdev = 0.052
  CI (99.9%): [7.053, 8.968] (assumes normal distribution)


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
# Warmup Iteration   1: 2.018 ops/ms
# Warmup Iteration   2: 5.522 ops/ms
# Warmup Iteration   3: 6.227 ops/ms
Iteration   1: 6.405 ops/ms
Iteration   2: 6.622 ops/ms
Iteration   3: 6.547 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.525 ±(99.9%) 2.010 ops/ms [Average]
  (min, avg, max) = (6.405, 6.525, 6.622), stdev = 0.110
  CI (99.9%): [4.515, 8.535] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 11.625 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 4.597 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.430 ±(99.9%) 0.004 ms/op
Iteration   1: 4.071 ±(99.9%) 0.004 ms/op
Iteration   2: 4.075 ±(99.9%) 0.007 ms/op
Iteration   3: 4.020 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.055 ±(99.9%) 0.567 ms/op [Average]
  (min, avg, max) = (4.020, 4.055, 4.075), stdev = 0.031
  CI (99.9%): [3.488, 4.623] (assumes normal distribution)


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
# Warmup Iteration   1: 11.773 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 4.451 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.039 ±(99.9%) 0.004 ms/op
Iteration   1: 3.938 ±(99.9%) 0.006 ms/op
Iteration   2: 4.034 ±(99.9%) 0.003 ms/op
Iteration   3: 3.959 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.977 ±(99.9%) 0.924 ms/op [Average]
  (min, avg, max) = (3.938, 3.977, 4.034), stdev = 0.051
  CI (99.9%): [3.054, 4.901] (assumes normal distribution)


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
# Warmup Iteration   1: 14.325 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 4.463 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.078 ±(99.9%) 0.003 ms/op
Iteration   1: 3.982 ±(99.9%) 0.006 ms/op
Iteration   2: 3.942 ±(99.9%) 0.004 ms/op
Iteration   3: 3.996 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.974 ±(99.9%) 0.514 ms/op [Average]
  (min, avg, max) = (3.942, 3.974, 3.996), stdev = 0.028
  CI (99.9%): [3.460, 4.487] (assumes normal distribution)


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
# Warmup Iteration   1: 13.926 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 6.068 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.980 ±(99.9%) 0.004 ms/op
Iteration   1: 4.750 ±(99.9%) 0.007 ms/op
Iteration   2: 4.751 ±(99.9%) 0.015 ms/op
Iteration   3: 4.923 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.808 ±(99.9%) 1.820 ms/op [Average]
  (min, avg, max) = (4.750, 4.808, 4.923), stdev = 0.100
  CI (99.9%): [2.988, 6.628] (assumes normal distribution)


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
# Warmup Iteration   1: 13.677 ±(99.9%) 0.177 ms/op
# Warmup Iteration   2: 5.328 ±(99.9%) 0.031 ms/op
# Warmup Iteration   3: 4.605 ±(99.9%) 0.024 ms/op
Iteration   1: 4.068 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   1.241 ms/op
                 createUser·p0.50:   3.903 ms/op
                 createUser·p0.90:   4.522 ms/op
                 createUser·p0.95:   5.095 ms/op
                 createUser·p0.99:   8.307 ms/op
                 createUser·p0.999:  25.723 ms/op
                 createUser·p0.9999: 32.159 ms/op
                 createUser·p1.00:   34.669 ms/op

Iteration   2: 3.960 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.399 ms/op
                 createUser·p0.50:   3.809 ms/op
                 createUser·p0.90:   4.530 ms/op
                 createUser·p0.95:   5.005 ms/op
                 createUser·p0.99:   7.832 ms/op
                 createUser·p0.999:  13.724 ms/op
                 createUser·p0.9999: 27.686 ms/op
                 createUser·p1.00:   28.279 ms/op

Iteration   3: 4.039 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   1.610 ms/op
                 createUser·p0.50:   3.883 ms/op
                 createUser·p0.90:   4.588 ms/op
                 createUser·p0.95:   5.112 ms/op
                 createUser·p0.99:   8.487 ms/op
                 createUser·p0.999:  28.574 ms/op
                 createUser·p0.9999: 34.865 ms/op
                 createUser·p1.00:   35.258 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 238694
  mean =      4.022 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 938 
    [ 2.500,  5.000) = 225048 
    [ 5.000,  7.500) = 8408 
    [ 7.500, 10.000) = 3254 
    [10.000, 12.500) = 391 
    [12.500, 15.000) = 243 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 35 
    [22.500, 25.000) = 42 
    [25.000, 27.500) = 116 
    [27.500, 30.000) = 57 
    [30.000, 32.500) = 59 
    [32.500, 35.000) = 25 
    [35.000, 37.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      1.241 ms/op
     p(50.0000) =      3.867 ms/op
     p(90.0000) =      4.547 ms/op
     p(95.0000) =      5.063 ms/op
     p(99.0000) =      8.274 ms/op
     p(99.9000) =     25.503 ms/op
     p(99.9900) =     33.174 ms/op
     p(99.9990) =     35.127 ms/op
     p(99.9999) =     35.258 ms/op
    p(100.0000) =     35.258 ms/op


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
# Warmup Iteration   1: 11.293 ±(99.9%) 0.171 ms/op
# Warmup Iteration   2: 4.380 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.917 ±(99.9%) 0.012 ms/op
Iteration   1: 4.031 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.618 ms/op
                 existUser·p0.50:   3.895 ms/op
                 existUser·p0.90:   4.555 ms/op
                 existUser·p0.95:   5.210 ms/op
                 existUser·p0.99:   8.094 ms/op
                 existUser·p0.999:  17.912 ms/op
                 existUser·p0.9999: 21.434 ms/op
                 existUser·p1.00:   22.807 ms/op

Iteration   2: 3.875 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.921 ms/op
                 existUser·p0.50:   3.707 ms/op
                 existUser·p0.90:   4.309 ms/op
                 existUser·p0.95:   4.801 ms/op
                 existUser·p0.99:   8.290 ms/op
                 existUser·p0.999:  14.915 ms/op
                 existUser·p0.9999: 22.774 ms/op
                 existUser·p1.00:   24.674 ms/op

Iteration   3: 3.858 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.128 ms/op
                 existUser·p0.50:   3.678 ms/op
                 existUser·p0.90:   4.157 ms/op
                 existUser·p0.95:   4.563 ms/op
                 existUser·p0.99:   7.815 ms/op
                 existUser·p0.999:  22.583 ms/op
                 existUser·p0.9999: 25.975 ms/op
                 existUser·p1.00:   27.263 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 244786
  mean =      3.920 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 540 
    [ 2.500,  5.000) = 232577 
    [ 5.000,  7.500) = 7659 
    [ 7.500, 10.000) = 3017 
    [10.000, 12.500) = 480 
    [12.500, 15.000) = 139 
    [15.000, 17.500) = 95 
    [17.500, 20.000) = 70 
    [20.000, 22.500) = 107 
    [22.500, 25.000) = 76 
    [25.000, 27.500) = 26 

  Percentiles, ms/op:
      p(0.0000) =      0.618 ms/op
     p(50.0000) =      3.772 ms/op
     p(90.0000) =      4.342 ms/op
     p(95.0000) =      4.940 ms/op
     p(99.0000) =      8.012 ms/op
     p(99.9000) =     18.266 ms/op
     p(99.9900) =     25.002 ms/op
     p(99.9990) =     26.236 ms/op
     p(99.9999) =     27.263 ms/op
    p(100.0000) =     27.263 ms/op


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
# Warmup Iteration   1: 12.662 ±(99.9%) 0.177 ms/op
# Warmup Iteration   2: 4.558 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.246 ±(99.9%) 0.018 ms/op
Iteration   1: 4.094 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.749 ms/op
                 getUser·p0.50:   3.899 ms/op
                 getUser·p0.90:   4.678 ms/op
                 getUser·p0.95:   5.415 ms/op
                 getUser·p0.99:   8.847 ms/op
                 getUser·p0.999:  22.905 ms/op
                 getUser·p0.9999: 25.598 ms/op
                 getUser·p1.00:   26.378 ms/op

Iteration   2: 3.885 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.866 ms/op
                 getUser·p0.50:   3.740 ms/op
                 getUser·p0.90:   4.424 ms/op
                 getUser·p0.95:   4.735 ms/op
                 getUser·p0.99:   6.939 ms/op
                 getUser·p0.999:  11.682 ms/op
                 getUser·p0.9999: 29.632 ms/op
                 getUser·p1.00:   30.736 ms/op

Iteration   3: 4.021 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   1.239 ms/op
                 getUser·p0.50:   3.817 ms/op
                 getUser·p0.90:   4.579 ms/op
                 getUser·p0.95:   5.325 ms/op
                 getUser·p0.99:   8.634 ms/op
                 getUser·p0.999:  28.163 ms/op
                 getUser·p0.9999: 30.935 ms/op
                 getUser·p1.00:   31.359 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 240008
  mean =      3.998 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 673 
    [ 2.500,  5.000) = 226391 
    [ 5.000,  7.500) = 9478 
    [ 7.500, 10.000) = 2340 
    [10.000, 12.500) = 623 
    [12.500, 15.000) = 181 
    [15.000, 17.500) = 42 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 85 
    [25.000, 27.500) = 44 
    [27.500, 30.000) = 83 
    [30.000, 32.500) = 41 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.239 ms/op
     p(50.0000) =      3.822 ms/op
     p(90.0000) =      4.555 ms/op
     p(95.0000) =      5.095 ms/op
     p(99.0000) =      8.217 ms/op
     p(99.9000) =     22.905 ms/op
     p(99.9900) =     30.310 ms/op
     p(99.9990) =     31.280 ms/op
     p(99.9999) =     31.359 ms/op
    p(100.0000) =     31.359 ms/op


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
# Warmup Iteration   1: 13.750 ±(99.9%) 0.187 ms/op
# Warmup Iteration   2: 5.631 ±(99.9%) 0.031 ms/op
# Warmup Iteration   3: 5.047 ±(99.9%) 0.019 ms/op
Iteration   1: 4.877 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   0.638 ms/op
                 listUser·p0.50:   4.694 ms/op
                 listUser·p0.90:   5.407 ms/op
                 listUser·p0.95:   5.964 ms/op
                 listUser·p0.99:   9.322 ms/op
                 listUser·p0.999:  25.116 ms/op
                 listUser·p0.9999: 27.667 ms/op
                 listUser·p1.00:   28.803 ms/op

Iteration   2: 4.980 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   2.001 ms/op
                 listUser·p0.50:   4.751 ms/op
                 listUser·p0.90:   5.456 ms/op
                 listUser·p0.95:   6.513 ms/op
                 listUser·p0.99:   10.502 ms/op
                 listUser·p0.999:  20.460 ms/op
                 listUser·p0.9999: 29.988 ms/op
                 listUser·p1.00:   34.079 ms/op

Iteration   3: 4.852 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.351 ms/op
                 listUser·p0.50:   4.669 ms/op
                 listUser·p0.90:   5.333 ms/op
                 listUser·p0.95:   5.925 ms/op
                 listUser·p0.99:   9.372 ms/op
                 listUser·p0.999:  18.222 ms/op
                 listUser·p0.9999: 20.861 ms/op
                 listUser·p1.00:   22.282 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 195637
  mean =      4.902 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 37 
    [ 2.500,  5.000) = 144530 
    [ 5.000,  7.500) = 44592 
    [ 7.500, 10.000) = 4890 
    [10.000, 12.500) = 671 
    [12.500, 15.000) = 298 
    [15.000, 17.500) = 165 
    [17.500, 20.000) = 198 
    [20.000, 22.500) = 72 
    [22.500, 25.000) = 89 
    [25.000, 27.500) = 70 
    [27.500, 30.000) = 19 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.638 ms/op
     p(50.0000) =      4.702 ms/op
     p(90.0000) =      5.399 ms/op
     p(95.0000) =      6.103 ms/op
     p(99.0000) =      9.634 ms/op
     p(99.9000) =     22.032 ms/op
     p(99.9900) =     27.670 ms/op
     p(99.9990) =     30.914 ms/op
     p(99.9999) =     34.079 ms/op
    p(100.0000) =     34.079 ms/op


# Run complete. Total time: 00:13:16

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.593 ± 3.062  ops/ms
ClientPb.existUser                       thrpt       3   8.094 ± 2.401  ops/ms
ClientPb.getUser                         thrpt       3   8.010 ± 0.957  ops/ms
ClientPb.listUser                        thrpt       3   6.525 ± 2.010  ops/ms
ClientPb.createUser                       avgt       3   4.055 ± 0.567   ms/op
ClientPb.existUser                        avgt       3   3.977 ± 0.924   ms/op
ClientPb.getUser                          avgt       3   3.974 ± 0.514   ms/op
ClientPb.listUser                         avgt       3   4.808 ± 1.820   ms/op
ClientPb.createUser                     sample  238694   4.022 ± 0.009   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.241           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.867           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.547           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.063           ms/op
ClientPb.createUser:createUser·p0.99    sample           8.274           ms/op
ClientPb.createUser:createUser·p0.999   sample          25.503           ms/op
ClientPb.createUser:createUser·p0.9999  sample          33.174           ms/op
ClientPb.createUser:createUser·p1.00    sample          35.258           ms/op
ClientPb.existUser                      sample  244786   3.920 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.618           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.772           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.342           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.940           ms/op
ClientPb.existUser:existUser·p0.99      sample           8.012           ms/op
ClientPb.existUser:existUser·p0.999     sample          18.266           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.002           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.263           ms/op
ClientPb.getUser                        sample  240008   3.998 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.239           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.822           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.555           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.095           ms/op
ClientPb.getUser:getUser·p0.99          sample           8.217           ms/op
ClientPb.getUser:getUser·p0.999         sample          22.905           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.310           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.359           ms/op
ClientPb.listUser                       sample  195637   4.902 ± 0.010   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.638           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.702           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.399           ms/op
ClientPb.listUser:listUser·p0.95        sample           6.103           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.634           ms/op
ClientPb.listUser:listUser·p0.999       sample          22.032           ms/op
ClientPb.listUser:listUser·p0.9999      sample          27.670           ms/op
ClientPb.listUser:listUser·p1.00        sample          34.079           ms/op
