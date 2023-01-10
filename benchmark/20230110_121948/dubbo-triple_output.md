# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.591 ops/ms
# Warmup Iteration   2: 4.192 ops/ms
# Warmup Iteration   3: 7.365 ops/ms
Iteration   1: 7.615 ops/ms
Iteration   2: 8.281 ops/ms
Iteration   3: 8.197 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.031 ±(99.9%) 6.614 ops/ms [Average]
  (min, avg, max) = (7.615, 8.031, 8.281), stdev = 0.363
  CI (99.9%): [1.417, 14.645] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 2.082 ops/ms
# Warmup Iteration   2: 6.622 ops/ms
# Warmup Iteration   3: 8.166 ops/ms
Iteration   1: 8.796 ops/ms
Iteration   2: 8.407 ops/ms
Iteration   3: 8.454 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.552 ±(99.9%) 3.879 ops/ms [Average]
  (min, avg, max) = (8.407, 8.552, 8.796), stdev = 0.213
  CI (99.9%): [4.673, 12.432] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.197 ops/ms
# Warmup Iteration   2: 6.343 ops/ms
# Warmup Iteration   3: 7.845 ops/ms
Iteration   1: 7.702 ops/ms
Iteration   2: 8.254 ops/ms
Iteration   3: 8.097 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.018 ±(99.9%) 5.188 ops/ms [Average]
  (min, avg, max) = (7.702, 8.018, 8.254), stdev = 0.284
  CI (99.9%): [2.830, 13.206] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:56
# Fork: 1 of 1
# Warmup Iteration   1: 1.885 ops/ms
# Warmup Iteration   2: 5.296 ops/ms
# Warmup Iteration   3: 6.558 ops/ms
Iteration   1: 6.824 ops/ms
Iteration   2: 6.877 ops/ms
Iteration   3: 6.793 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.831 ±(99.9%) 0.771 ops/ms [Average]
  (min, avg, max) = (6.793, 6.831, 6.877), stdev = 0.042
  CI (99.9%): [6.060, 7.602] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 13.667 ±(99.9%) 0.075 ms/op
# Warmup Iteration   2: 4.520 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.199 ±(99.9%) 0.005 ms/op
Iteration   1: 4.135 ±(99.9%) 0.006 ms/op
Iteration   2: 4.252 ±(99.9%) 0.005 ms/op
Iteration   3: 4.312 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.233 ±(99.9%) 1.642 ms/op [Average]
  (min, avg, max) = (4.135, 4.233, 4.312), stdev = 0.090
  CI (99.9%): [2.591, 5.875] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 11.782 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 4.658 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.186 ±(99.9%) 0.006 ms/op
Iteration   1: 3.917 ±(99.9%) 0.006 ms/op
Iteration   2: 3.775 ±(99.9%) 0.005 ms/op
Iteration   3: 3.769 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.821 ±(99.9%) 1.533 ms/op [Average]
  (min, avg, max) = (3.769, 3.821, 3.917), stdev = 0.084
  CI (99.9%): [2.288, 5.353] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 10.665 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 4.810 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.011 ±(99.9%) 0.004 ms/op
Iteration   1: 4.215 ±(99.9%) 0.007 ms/op
Iteration   2: 3.979 ±(99.9%) 0.004 ms/op
Iteration   3: 4.090 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.095 ±(99.9%) 2.161 ms/op [Average]
  (min, avg, max) = (3.979, 4.095, 4.215), stdev = 0.118
  CI (99.9%): [1.934, 6.255] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 15.394 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 5.518 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.791 ±(99.9%) 0.012 ms/op
Iteration   1: 4.623 ±(99.9%) 0.013 ms/op
Iteration   2: 4.839 ±(99.9%) 0.014 ms/op
Iteration   3: 4.771 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.744 ±(99.9%) 2.022 ms/op [Average]
  (min, avg, max) = (4.623, 4.744, 4.839), stdev = 0.111
  CI (99.9%): [2.723, 6.766] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 11.718 ±(99.9%) 0.164 ms/op
# Warmup Iteration   2: 5.059 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 4.690 ±(99.9%) 0.022 ms/op
Iteration   1: 4.170 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.368 ms/op
                 createUser·p0.50:   3.973 ms/op
                 createUser·p0.90:   4.907 ms/op
                 createUser·p0.95:   5.456 ms/op
                 createUser·p0.99:   8.366 ms/op
                 createUser·p0.999:  24.717 ms/op
                 createUser·p0.9999: 26.258 ms/op
                 createUser·p1.00:   27.623 ms/op

Iteration   2: 4.096 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.833 ms/op
                 createUser·p0.50:   3.863 ms/op
                 createUser·p0.90:   4.801 ms/op
                 createUser·p0.95:   5.536 ms/op
                 createUser·p0.99:   7.332 ms/op
                 createUser·p0.999:  13.975 ms/op
                 createUser·p0.9999: 27.564 ms/op
                 createUser·p1.00:   28.606 ms/op

Iteration   3: 3.958 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.989 ms/op
                 createUser·p0.50:   3.756 ms/op
                 createUser·p0.90:   4.424 ms/op
                 createUser·p0.95:   4.948 ms/op
                 createUser·p0.99:   7.741 ms/op
                 createUser·p0.999:  27.314 ms/op
                 createUser·p0.9999: 32.727 ms/op
                 createUser·p1.00:   34.275 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 235564
  mean =      4.073 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 233 
    [ 2.500,  5.000) = 218746 
    [ 5.000,  7.500) = 13984 
    [ 7.500, 10.000) = 1683 
    [10.000, 12.500) = 464 
    [12.500, 15.000) = 137 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 36 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 139 
    [27.500, 30.000) = 55 
    [30.000, 32.500) = 20 
    [32.500, 35.000) = 13 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.368 ms/op
     p(50.0000) =      3.883 ms/op
     p(90.0000) =      4.743 ms/op
     p(95.0000) =      5.341 ms/op
     p(99.0000) =      7.709 ms/op
     p(99.9000) =     24.707 ms/op
     p(99.9900) =     31.650 ms/op
     p(99.9990) =     34.079 ms/op
     p(99.9999) =     34.275 ms/op
    p(100.0000) =     34.275 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 12.066 ±(99.9%) 0.177 ms/op
# Warmup Iteration   2: 5.012 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 4.141 ±(99.9%) 0.015 ms/op
Iteration   1: 4.069 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.825 ms/op
                 existUser·p0.50:   3.842 ms/op
                 existUser·p0.90:   4.882 ms/op
                 existUser·p0.95:   5.571 ms/op
                 existUser·p0.99:   7.561 ms/op
                 existUser·p0.999:  14.205 ms/op
                 existUser·p0.9999: 27.768 ms/op
                 existUser·p1.00:   28.901 ms/op

Iteration   2: 3.781 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.980 ms/op
                 existUser·p0.50:   3.604 ms/op
                 existUser·p0.90:   4.129 ms/op
                 existUser·p0.95:   4.456 ms/op
                 existUser·p0.99:   7.594 ms/op
                 existUser·p0.999:  25.330 ms/op
                 existUser·p0.9999: 30.114 ms/op
                 existUser·p1.00:   31.195 ms/op

Iteration   3: 3.839 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.683 ms/op
                 existUser·p0.50:   3.703 ms/op
                 existUser·p0.90:   4.260 ms/op
                 existUser·p0.95:   4.661 ms/op
                 existUser·p0.99:   6.767 ms/op
                 existUser·p0.999:  11.647 ms/op
                 existUser·p0.9999: 37.619 ms/op
                 existUser·p1.00:   39.649 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 246369
  mean =      3.893 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 269 
    [ 2.500,  5.000) = 233930 
    [ 5.000,  7.500) = 9974 
    [ 7.500, 10.000) = 1457 
    [10.000, 12.500) = 318 
    [12.500, 15.000) = 153 
    [15.000, 17.500) = 15 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 40 
    [25.000, 27.500) = 71 
    [27.500, 30.000) = 39 
    [30.000, 32.500) = 18 
    [32.500, 35.000) = 27 
    [35.000, 37.500) = 21 

  Percentiles, ms/op:
      p(0.0000) =      0.980 ms/op
     p(50.0000) =      3.727 ms/op
     p(90.0000) =      4.456 ms/op
     p(95.0000) =      4.989 ms/op
     p(99.0000) =      7.332 ms/op
     p(99.9000) =     19.047 ms/op
     p(99.9900) =     36.092 ms/op
     p(99.9990) =     38.819 ms/op
     p(99.9999) =     39.649 ms/op
    p(100.0000) =     39.649 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 13.297 ±(99.9%) 0.209 ms/op
# Warmup Iteration   2: 5.103 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 4.387 ±(99.9%) 0.016 ms/op
Iteration   1: 4.112 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.751 ms/op
                 getUser·p0.50:   3.879 ms/op
                 getUser·p0.90:   4.792 ms/op
                 getUser·p0.95:   5.612 ms/op
                 getUser·p0.99:   8.438 ms/op
                 getUser·p0.999:  25.607 ms/op
                 getUser·p0.9999: 34.589 ms/op
                 getUser·p1.00:   35.914 ms/op

Iteration   2: 4.123 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   2.220 ms/op
                 getUser·p0.50:   3.924 ms/op
                 getUser·p0.90:   4.932 ms/op
                 getUser·p0.95:   5.775 ms/op
                 getUser·p0.99:   7.995 ms/op
                 getUser·p0.999:  16.482 ms/op
                 getUser·p0.9999: 33.128 ms/op
                 getUser·p1.00:   34.472 ms/op

Iteration   3: 4.294 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   0.627 ms/op
                 getUser·p0.50:   4.014 ms/op
                 getUser·p0.90:   5.349 ms/op
                 getUser·p0.95:   6.177 ms/op
                 getUser·p0.99:   8.259 ms/op
                 getUser·p0.999:  15.581 ms/op
                 getUser·p0.9999: 42.926 ms/op
                 getUser·p1.00:   43.319 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 230044
  mean =      4.175 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 206456 
    [ 5.000, 10.000) = 22352 
    [10.000, 15.000) = 891 
    [15.000, 20.000) = 121 
    [20.000, 25.000) = 3 
    [25.000, 30.000) = 116 
    [30.000, 35.000) = 78 
    [35.000, 40.000) = 6 
    [40.000, 45.000) = 21 

  Percentiles, ms/op:
      p(0.0000) =      0.627 ms/op
     p(50.0000) =      3.932 ms/op
     p(90.0000) =      5.030 ms/op
     p(95.0000) =      5.898 ms/op
     p(99.0000) =      8.192 ms/op
     p(99.9000) =     19.661 ms/op
     p(99.9900) =     38.980 ms/op
     p(99.9990) =     43.103 ms/op
     p(99.9999) =     43.319 ms/op
    p(100.0000) =     43.319 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 14.574 ±(99.9%) 0.214 ms/op
# Warmup Iteration   2: 5.764 ±(99.9%) 0.032 ms/op
# Warmup Iteration   3: 5.032 ±(99.9%) 0.020 ms/op
Iteration   1: 4.726 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.927 ms/op
                 listUser·p0.50:   4.547 ms/op
                 listUser·p0.90:   5.194 ms/op
                 listUser·p0.95:   5.841 ms/op
                 listUser·p0.99:   8.520 ms/op
                 listUser·p0.999:  27.371 ms/op
                 listUser·p0.9999: 29.244 ms/op
                 listUser·p1.00:   31.490 ms/op

Iteration   2: 4.534 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.503 ms/op
                 listUser·p0.50:   4.309 ms/op
                 listUser·p0.90:   5.054 ms/op
                 listUser·p0.95:   5.382 ms/op
                 listUser·p0.99:   8.520 ms/op
                 listUser·p0.999:  18.612 ms/op
                 listUser·p0.9999: 26.441 ms/op
                 listUser·p1.00:   27.722 ms/op

Iteration   3: 4.500 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.585 ms/op
                 listUser·p0.50:   4.375 ms/op
                 listUser·p0.90:   4.825 ms/op
                 listUser·p0.95:   5.095 ms/op
                 listUser·p0.99:   8.045 ms/op
                 listUser·p0.999:  16.237 ms/op
                 listUser·p0.9999: 17.718 ms/op
                 listUser·p1.00:   18.514 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 209190
  mean =      4.585 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8 
    [ 2.500,  5.000) = 186749 
    [ 5.000,  7.500) = 18797 
    [ 7.500, 10.000) = 2516 
    [10.000, 12.500) = 425 
    [12.500, 15.000) = 218 
    [15.000, 17.500) = 233 
    [17.500, 20.000) = 69 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 86 
    [27.500, 30.000) = 62 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.503 ms/op
     p(50.0000) =      4.391 ms/op
     p(90.0000) =      5.030 ms/op
     p(95.0000) =      5.407 ms/op
     p(99.0000) =      8.438 ms/op
     p(99.9000) =     18.317 ms/op
     p(99.9900) =     28.246 ms/op
     p(99.9990) =     29.810 ms/op
     p(99.9999) =     31.490 ms/op
    p(100.0000) =     31.490 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.031 ± 6.614  ops/ms
ClientPb.existUser                       thrpt       3   8.552 ± 3.879  ops/ms
ClientPb.getUser                         thrpt       3   8.018 ± 5.188  ops/ms
ClientPb.listUser                        thrpt       3   6.831 ± 0.771  ops/ms
ClientPb.createUser                       avgt       3   4.233 ± 1.642   ms/op
ClientPb.existUser                        avgt       3   3.821 ± 1.533   ms/op
ClientPb.getUser                          avgt       3   4.095 ± 2.161   ms/op
ClientPb.listUser                         avgt       3   4.744 ± 2.022   ms/op
ClientPb.createUser                     sample  235564   4.073 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.368           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.883           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.743           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.341           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.709           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.707           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.650           ms/op
ClientPb.createUser:createUser·p1.00    sample          34.275           ms/op
ClientPb.existUser                      sample  246369   3.893 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.980           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.727           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.456           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.989           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.332           ms/op
ClientPb.existUser:existUser·p0.999     sample          19.047           ms/op
ClientPb.existUser:existUser·p0.9999    sample          36.092           ms/op
ClientPb.existUser:existUser·p1.00      sample          39.649           ms/op
ClientPb.getUser                        sample  230044   4.175 ± 0.009   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.627           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.932           ms/op
ClientPb.getUser:getUser·p0.90          sample           5.030           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.898           ms/op
ClientPb.getUser:getUser·p0.99          sample           8.192           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.661           ms/op
ClientPb.getUser:getUser·p0.9999        sample          38.980           ms/op
ClientPb.getUser:getUser·p1.00          sample          43.319           ms/op
ClientPb.listUser                       sample  209190   4.585 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.503           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.391           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.030           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.407           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.438           ms/op
ClientPb.listUser:listUser·p0.999       sample          18.317           ms/op
ClientPb.listUser:listUser·p0.9999      sample          28.246           ms/op
ClientPb.listUser:listUser·p1.00        sample          31.490           ms/op
