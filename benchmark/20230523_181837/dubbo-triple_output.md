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
# Warmup Iteration   1: 1.700 ops/ms
# Warmup Iteration   2: 3.768 ops/ms
# Warmup Iteration   3: 7.417 ops/ms
Iteration   1: 7.641 ops/ms
Iteration   2: 8.194 ops/ms
Iteration   3: 8.195 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.010 ±(99.9%) 5.833 ops/ms [Average]
  (min, avg, max) = (7.641, 8.010, 8.195), stdev = 0.320
  CI (99.9%): [2.177, 13.843] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 2.279 ops/ms
# Warmup Iteration   2: 7.446 ops/ms
# Warmup Iteration   3: 8.166 ops/ms
Iteration   1: 8.334 ops/ms
Iteration   2: 8.562 ops/ms
Iteration   3: 8.568 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.488 ±(99.9%) 2.432 ops/ms [Average]
  (min, avg, max) = (8.334, 8.488, 8.568), stdev = 0.133
  CI (99.9%): [6.056, 10.921] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 2.279 ops/ms
# Warmup Iteration   2: 6.559 ops/ms
# Warmup Iteration   3: 7.513 ops/ms
Iteration   1: 8.016 ops/ms
Iteration   2: 7.964 ops/ms
Iteration   3: 7.729 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.903 ±(99.9%) 2.789 ops/ms [Average]
  (min, avg, max) = (7.729, 7.903, 8.016), stdev = 0.153
  CI (99.9%): [5.113, 10.692] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 2.220 ops/ms
# Warmup Iteration   2: 6.143 ops/ms
# Warmup Iteration   3: 6.873 ops/ms
Iteration   1: 6.736 ops/ms
Iteration   2: 7.085 ops/ms
Iteration   3: 6.924 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.915 ±(99.9%) 3.188 ops/ms [Average]
  (min, avg, max) = (6.736, 6.915, 7.085), stdev = 0.175
  CI (99.9%): [3.727, 10.103] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 12.772 ±(99.9%) 0.065 ms/op
# Warmup Iteration   2: 5.116 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.109 ±(99.9%) 0.004 ms/op
Iteration   1: 3.827 ±(99.9%) 0.012 ms/op
Iteration   2: 3.776 ±(99.9%) 0.009 ms/op
Iteration   3: 3.845 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.816 ±(99.9%) 0.651 ms/op [Average]
  (min, avg, max) = (3.776, 3.816, 3.845), stdev = 0.036
  CI (99.9%): [3.165, 4.468] (assumes normal distribution)


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
# Warmup Iteration   1: 12.553 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 4.641 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.815 ±(99.9%) 0.008 ms/op
Iteration   1: 3.846 ±(99.9%) 0.005 ms/op
Iteration   2: 3.713 ±(99.9%) 0.010 ms/op
Iteration   3: 3.710 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.756 ±(99.9%) 1.416 ms/op [Average]
  (min, avg, max) = (3.710, 3.756, 3.846), stdev = 0.078
  CI (99.9%): [2.341, 5.172] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 12.042 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 4.252 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.910 ±(99.9%) 0.005 ms/op
Iteration   1: 4.017 ±(99.9%) 0.004 ms/op
Iteration   2: 4.094 ±(99.9%) 0.005 ms/op
Iteration   3: 3.863 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.991 ±(99.9%) 2.146 ms/op [Average]
  (min, avg, max) = (3.863, 3.991, 4.094), stdev = 0.118
  CI (99.9%): [1.845, 6.138] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 13.922 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 5.299 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.700 ±(99.9%) 0.012 ms/op
Iteration   1: 4.534 ±(99.9%) 0.012 ms/op
Iteration   2: 4.604 ±(99.9%) 0.013 ms/op
Iteration   3: 4.445 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.528 ±(99.9%) 1.448 ms/op [Average]
  (min, avg, max) = (4.445, 4.528, 4.604), stdev = 0.079
  CI (99.9%): [3.080, 5.975] (assumes normal distribution)


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
# Warmup Iteration   1: 11.685 ±(99.9%) 0.178 ms/op
# Warmup Iteration   2: 5.008 ±(99.9%) 0.031 ms/op
# Warmup Iteration   3: 4.502 ±(99.9%) 0.020 ms/op
Iteration   1: 4.105 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   2.009 ms/op
                 createUser·p0.50:   3.944 ms/op
                 createUser·p0.90:   4.792 ms/op
                 createUser·p0.95:   5.808 ms/op
                 createUser·p0.99:   7.954 ms/op
                 createUser·p0.999:  20.414 ms/op
                 createUser·p0.9999: 25.164 ms/op
                 createUser·p1.00:   26.903 ms/op

Iteration   2: 3.995 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.602 ms/op
                 createUser·p0.50:   3.842 ms/op
                 createUser·p0.90:   4.637 ms/op
                 createUser·p0.95:   5.267 ms/op
                 createUser·p0.99:   8.014 ms/op
                 createUser·p0.999:  22.708 ms/op
                 createUser·p0.9999: 26.181 ms/op
                 createUser·p1.00:   26.542 ms/op

Iteration   3: 3.840 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.214 ms/op
                 createUser·p0.50:   3.707 ms/op
                 createUser·p0.90:   4.293 ms/op
                 createUser·p0.95:   4.596 ms/op
                 createUser·p0.99:   6.537 ms/op
                 createUser·p0.999:  15.458 ms/op
                 createUser·p0.9999: 39.147 ms/op
                 createUser·p1.00:   39.715 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 241443
  mean =      3.977 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 237 
    [ 2.500,  5.000) = 227319 
    [ 5.000,  7.500) = 11363 
    [ 7.500, 10.000) = 1692 
    [10.000, 12.500) = 438 
    [12.500, 15.000) = 101 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 54 
    [22.500, 25.000) = 99 
    [25.000, 27.500) = 56 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      1.214 ms/op
     p(50.0000) =      3.854 ms/op
     p(90.0000) =      4.555 ms/op
     p(95.0000) =      5.136 ms/op
     p(99.0000) =      7.623 ms/op
     p(99.9000) =     20.127 ms/op
     p(99.9900) =     37.580 ms/op
     p(99.9990) =     39.660 ms/op
     p(99.9999) =     39.715 ms/op
    p(100.0000) =     39.715 ms/op


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
# Warmup Iteration   1: 12.016 ±(99.9%) 0.172 ms/op
# Warmup Iteration   2: 4.263 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.012 ±(99.9%) 0.012 ms/op
Iteration   1: 3.841 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.448 ms/op
                 existUser·p0.50:   3.686 ms/op
                 existUser·p0.90:   4.383 ms/op
                 existUser·p0.95:   4.907 ms/op
                 existUser·p0.99:   7.242 ms/op
                 existUser·p0.999:  23.487 ms/op
                 existUser·p0.9999: 27.973 ms/op
                 existUser·p1.00:   30.409 ms/op

Iteration   2: 3.723 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.911 ms/op
                 existUser·p0.50:   3.592 ms/op
                 existUser·p0.90:   4.116 ms/op
                 existUser·p0.95:   4.407 ms/op
                 existUser·p0.99:   6.537 ms/op
                 existUser·p0.999:  10.788 ms/op
                 existUser·p0.9999: 36.007 ms/op
                 existUser·p1.00:   36.962 ms/op

Iteration   3: 3.921 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.524 ms/op
                 existUser·p0.50:   3.830 ms/op
                 existUser·p0.90:   4.506 ms/op
                 existUser·p0.95:   4.940 ms/op
                 existUser·p0.99:   7.131 ms/op
                 existUser·p0.999:  14.057 ms/op
                 existUser·p0.9999: 32.609 ms/op
                 existUser·p1.00:   33.620 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 250763
  mean =      3.827 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 320 
    [ 2.500,  5.000) = 240595 
    [ 5.000,  7.500) = 8114 
    [ 7.500, 10.000) = 1222 
    [10.000, 12.500) = 223 
    [12.500, 15.000) = 47 
    [15.000, 17.500) = 11 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 50 
    [25.000, 27.500) = 82 
    [27.500, 30.000) = 26 
    [30.000, 32.500) = 26 
    [32.500, 35.000) = 22 
    [35.000, 37.500) = 18 

  Percentiles, ms/op:
      p(0.0000) =      1.448 ms/op
     p(50.0000) =      3.715 ms/op
     p(90.0000) =      4.325 ms/op
     p(95.0000) =      4.801 ms/op
     p(99.0000) =      6.930 ms/op
     p(99.9000) =     14.090 ms/op
     p(99.9900) =     34.790 ms/op
     p(99.9990) =     36.896 ms/op
     p(99.9999) =     36.962 ms/op
    p(100.0000) =     36.962 ms/op


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
# Warmup Iteration   1: 13.702 ±(99.9%) 0.185 ms/op
# Warmup Iteration   2: 4.499 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.333 ±(99.9%) 0.018 ms/op
Iteration   1: 4.225 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   2.253 ms/op
                 getUser·p0.50:   3.949 ms/op
                 getUser·p0.90:   5.104 ms/op
                 getUser·p0.95:   6.087 ms/op
                 getUser·p0.99:   8.847 ms/op
                 getUser·p0.999:  25.108 ms/op
                 getUser·p0.9999: 27.361 ms/op
                 getUser·p1.00:   28.312 ms/op

Iteration   2: 4.008 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.202 ms/op
                 getUser·p0.50:   3.887 ms/op
                 getUser·p0.90:   4.702 ms/op
                 getUser·p0.95:   5.259 ms/op
                 getUser·p0.99:   7.905 ms/op
                 getUser·p0.999:  12.435 ms/op
                 getUser·p0.9999: 27.264 ms/op
                 getUser·p1.00:   27.951 ms/op

Iteration   3: 3.929 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.950 ms/op
                 getUser·p0.50:   3.801 ms/op
                 getUser·p0.90:   4.284 ms/op
                 getUser·p0.95:   4.596 ms/op
                 getUser·p0.99:   7.021 ms/op
                 getUser·p0.999:  15.034 ms/op
                 getUser·p0.9999: 32.198 ms/op
                 getUser·p1.00:   33.260 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 236948
  mean =      4.050 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 77 
    [ 2.500,  5.000) = 220127 
    [ 5.000,  7.500) = 13711 
    [ 7.500, 10.000) = 2091 
    [10.000, 12.500) = 556 
    [12.500, 15.000) = 90 
    [15.000, 17.500) = 40 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 141 
    [27.500, 30.000) = 22 
    [30.000, 32.500) = 30 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.202 ms/op
     p(50.0000) =      3.887 ms/op
     p(90.0000) =      4.719 ms/op
     p(95.0000) =      5.374 ms/op
     p(99.0000) =      7.954 ms/op
     p(99.9000) =     18.976 ms/op
     p(99.9900) =     31.261 ms/op
     p(99.9990) =     32.494 ms/op
     p(99.9999) =     33.260 ms/op
    p(100.0000) =     33.260 ms/op


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
# Warmup Iteration   1: 16.291 ±(99.9%) 0.248 ms/op
# Warmup Iteration   2: 5.840 ±(99.9%) 0.035 ms/op
# Warmup Iteration   3: 4.712 ±(99.9%) 0.016 ms/op
Iteration   1: 4.778 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.782 ms/op
                 listUser·p0.50:   4.473 ms/op
                 listUser·p0.90:   5.374 ms/op
                 listUser·p0.95:   6.717 ms/op
                 listUser·p0.99:   9.617 ms/op
                 listUser·p0.999:  25.035 ms/op
                 listUser·p0.9999: 27.971 ms/op
                 listUser·p1.00:   29.098 ms/op

Iteration   2: 4.709 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.474 ms/op
                 listUser·p0.50:   4.547 ms/op
                 listUser·p0.90:   5.194 ms/op
                 listUser·p0.95:   5.734 ms/op
                 listUser·p0.99:   8.361 ms/op
                 listUser·p0.999:  18.090 ms/op
                 listUser·p0.9999: 21.785 ms/op
                 listUser·p1.00:   23.233 ms/op

Iteration   3: 4.731 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   2.437 ms/op
                 listUser·p0.50:   4.489 ms/op
                 listUser·p0.90:   5.489 ms/op
                 listUser·p0.95:   6.529 ms/op
                 listUser·p0.99:   9.535 ms/op
                 listUser·p0.999:  16.941 ms/op
                 listUser·p0.9999: 18.522 ms/op
                 listUser·p1.00:   19.202 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 202491
  mean =      4.739 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5 
    [ 2.500,  5.000) = 166829 
    [ 5.000,  7.500) = 29934 
    [ 7.500, 10.000) = 4427 
    [10.000, 12.500) = 744 
    [12.500, 15.000) = 117 
    [15.000, 17.500) = 134 
    [17.500, 20.000) = 109 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 94 
    [25.000, 27.500) = 55 

  Percentiles, ms/op:
      p(0.0000) =      1.782 ms/op
     p(50.0000) =      4.506 ms/op
     p(90.0000) =      5.341 ms/op
     p(95.0000) =      6.316 ms/op
     p(99.0000) =      9.126 ms/op
     p(99.9000) =     19.055 ms/op
     p(99.9900) =     26.206 ms/op
     p(99.9990) =     29.016 ms/op
     p(99.9999) =     29.098 ms/op
    p(100.0000) =     29.098 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.010 ± 5.833  ops/ms
ClientPb.existUser                       thrpt       3   8.488 ± 2.432  ops/ms
ClientPb.getUser                         thrpt       3   7.903 ± 2.789  ops/ms
ClientPb.listUser                        thrpt       3   6.915 ± 3.188  ops/ms
ClientPb.createUser                       avgt       3   3.816 ± 0.651   ms/op
ClientPb.existUser                        avgt       3   3.756 ± 1.416   ms/op
ClientPb.getUser                          avgt       3   3.991 ± 2.146   ms/op
ClientPb.listUser                         avgt       3   4.528 ± 1.448   ms/op
ClientPb.createUser                     sample  241443   3.977 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.214           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.854           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.555           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.136           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.623           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.127           ms/op
ClientPb.createUser:createUser·p0.9999  sample          37.580           ms/op
ClientPb.createUser:createUser·p1.00    sample          39.715           ms/op
ClientPb.existUser                      sample  250763   3.827 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.448           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.715           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.325           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.801           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.930           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.090           ms/op
ClientPb.existUser:existUser·p0.9999    sample          34.790           ms/op
ClientPb.existUser:existUser·p1.00      sample          36.962           ms/op
ClientPb.getUser                        sample  236948   4.050 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.202           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.887           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.719           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.374           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.954           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.976           ms/op
ClientPb.getUser:getUser·p0.9999        sample          31.261           ms/op
ClientPb.getUser:getUser·p1.00          sample          33.260           ms/op
ClientPb.listUser                       sample  202491   4.739 ± 0.009   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.782           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.506           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.341           ms/op
ClientPb.listUser:listUser·p0.95        sample           6.316           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.126           ms/op
ClientPb.listUser:listUser·p0.999       sample          19.055           ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.206           ms/op
ClientPb.listUser:listUser·p1.00        sample          29.098           ms/op
