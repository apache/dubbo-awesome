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
# Warmup Iteration   1: 1.664 ops/ms
# Warmup Iteration   2: 3.626 ops/ms
# Warmup Iteration   3: 7.194 ops/ms
Iteration   1: 7.688 ops/ms
Iteration   2: 8.174 ops/ms
Iteration   3: 8.241 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.034 ±(99.9%) 5.513 ops/ms [Average]
  (min, avg, max) = (7.688, 8.034, 8.241), stdev = 0.302
  CI (99.9%): [2.521, 13.547] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:12
# Fork: 1 of 1
# Warmup Iteration   1: 2.267 ops/ms
# Warmup Iteration   2: 6.886 ops/ms
# Warmup Iteration   3: 8.034 ops/ms
Iteration   1: 8.072 ops/ms
Iteration   2: 8.243 ops/ms
Iteration   3: 8.117 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.144 ±(99.9%) 1.621 ops/ms [Average]
  (min, avg, max) = (8.072, 8.144, 8.243), stdev = 0.089
  CI (99.9%): [6.523, 9.765] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:05
# Fork: 1 of 1
# Warmup Iteration   1: 2.188 ops/ms
# Warmup Iteration   2: 6.609 ops/ms
# Warmup Iteration   3: 7.550 ops/ms
Iteration   1: 8.240 ops/ms
Iteration   2: 8.280 ops/ms
Iteration   3: 8.064 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.195 ±(99.9%) 2.096 ops/ms [Average]
  (min, avg, max) = (8.064, 8.195, 8.280), stdev = 0.115
  CI (99.9%): [6.099, 10.291] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:58
# Fork: 1 of 1
# Warmup Iteration   1: 2.057 ops/ms
# Warmup Iteration   2: 5.499 ops/ms
# Warmup Iteration   3: 6.594 ops/ms
Iteration   1: 6.657 ops/ms
Iteration   2: 7.014 ops/ms
Iteration   3: 7.041 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.904 ±(99.9%) 3.905 ops/ms [Average]
  (min, avg, max) = (6.657, 6.904, 7.041), stdev = 0.214
  CI (99.9%): [2.999, 10.809] (assumes normal distribution)


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
# Warmup Iteration   1: 12.204 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 5.450 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.395 ±(99.9%) 0.011 ms/op
Iteration   1: 3.974 ±(99.9%) 0.007 ms/op
Iteration   2: 4.005 ±(99.9%) 0.011 ms/op
Iteration   3: 3.932 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.970 ±(99.9%) 0.674 ms/op [Average]
  (min, avg, max) = (3.932, 3.970, 4.005), stdev = 0.037
  CI (99.9%): [3.296, 4.644] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 11.490 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 4.185 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.910 ±(99.9%) 0.004 ms/op
Iteration   1: 3.772 ±(99.9%) 0.007 ms/op
Iteration   2: 3.955 ±(99.9%) 0.003 ms/op
Iteration   3: 3.747 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.825 ±(99.9%) 2.072 ms/op [Average]
  (min, avg, max) = (3.747, 3.825, 3.955), stdev = 0.114
  CI (99.9%): [1.752, 5.897] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 11.686 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 4.307 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.015 ±(99.9%) 0.006 ms/op
Iteration   1: 3.863 ±(99.9%) 0.008 ms/op
Iteration   2: 3.854 ±(99.9%) 0.011 ms/op
Iteration   3: 3.879 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.866 ±(99.9%) 0.237 ms/op [Average]
  (min, avg, max) = (3.854, 3.866, 3.879), stdev = 0.013
  CI (99.9%): [3.629, 4.102] (assumes normal distribution)


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
# Warmup Iteration   1: 13.991 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 5.636 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.741 ±(99.9%) 0.013 ms/op
Iteration   1: 4.556 ±(99.9%) 0.017 ms/op
Iteration   2: 4.562 ±(99.9%) 0.019 ms/op
Iteration   3: 4.617 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.578 ±(99.9%) 0.610 ms/op [Average]
  (min, avg, max) = (4.556, 4.578, 4.617), stdev = 0.033
  CI (99.9%): [3.968, 5.189] (assumes normal distribution)


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
# Warmup Iteration   1: 12.092 ±(99.9%) 0.156 ms/op
# Warmup Iteration   2: 4.782 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.446 ±(99.9%) 0.019 ms/op
Iteration   1: 3.888 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.583 ms/op
                 createUser·p0.50:   3.715 ms/op
                 createUser·p0.90:   4.407 ms/op
                 createUser·p0.95:   4.973 ms/op
                 createUser·p0.99:   7.315 ms/op
                 createUser·p0.999:  24.347 ms/op
                 createUser·p0.9999: 29.120 ms/op
                 createUser·p1.00:   31.425 ms/op

Iteration   2: 4.010 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.290 ms/op
                 createUser·p0.50:   3.813 ms/op
                 createUser·p0.90:   4.760 ms/op
                 createUser·p0.95:   5.169 ms/op
                 createUser·p0.99:   6.545 ms/op
                 createUser·p0.999:  25.985 ms/op
                 createUser·p0.9999: 30.376 ms/op
                 createUser·p1.00:   31.228 ms/op

Iteration   3: 4.030 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.503 ms/op
                 createUser·p0.50:   3.867 ms/op
                 createUser·p0.90:   4.694 ms/op
                 createUser·p0.95:   5.087 ms/op
                 createUser·p0.99:   6.922 ms/op
                 createUser·p0.999:  13.582 ms/op
                 createUser·p0.9999: 33.817 ms/op
                 createUser·p1.00:   35.521 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 241549
  mean =      3.975 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 131 
    [ 2.500,  5.000) = 227636 
    [ 5.000,  7.500) = 12060 
    [ 7.500, 10.000) = 1152 
    [10.000, 12.500) = 261 
    [12.500, 15.000) = 53 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 34 
    [25.000, 27.500) = 96 
    [27.500, 30.000) = 49 
    [30.000, 32.500) = 50 
    [32.500, 35.000) = 24 
    [35.000, 37.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.290 ms/op
     p(50.0000) =      3.809 ms/op
     p(90.0000) =      4.653 ms/op
     p(95.0000) =      5.095 ms/op
     p(99.0000) =      6.943 ms/op
     p(99.9000) =     24.361 ms/op
     p(99.9900) =     32.735 ms/op
     p(99.9990) =     35.297 ms/op
     p(99.9999) =     35.521 ms/op
    p(100.0000) =     35.521 ms/op


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
# Warmup Iteration   1: 11.592 ±(99.9%) 0.175 ms/op
# Warmup Iteration   2: 4.212 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.942 ±(99.9%) 0.012 ms/op
Iteration   1: 3.846 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.755 ms/op
                 existUser·p0.50:   3.707 ms/op
                 existUser·p0.90:   4.325 ms/op
                 existUser·p0.95:   4.981 ms/op
                 existUser·p0.99:   7.365 ms/op
                 existUser·p0.999:  22.381 ms/op
                 existUser·p0.9999: 26.761 ms/op
                 existUser·p1.00:   27.263 ms/op

Iteration   2: 3.941 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.937 ms/op
                 existUser·p0.50:   3.809 ms/op
                 existUser·p0.90:   4.686 ms/op
                 existUser·p0.95:   5.169 ms/op
                 existUser·p0.99:   6.979 ms/op
                 existUser·p0.999:  14.739 ms/op
                 existUser·p0.9999: 26.477 ms/op
                 existUser·p1.00:   26.903 ms/op

Iteration   3: 3.748 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.772 ms/op
                 existUser·p0.50:   3.690 ms/op
                 existUser·p0.90:   4.096 ms/op
                 existUser·p0.95:   4.432 ms/op
                 existUser·p0.99:   6.709 ms/op
                 existUser·p0.999:  10.224 ms/op
                 existUser·p0.9999: 29.406 ms/op
                 existUser·p1.00:   31.982 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 249852
  mean =      3.843 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 227 
    [ 2.500,  5.000) = 237938 
    [ 5.000,  7.500) = 9887 
    [ 7.500, 10.000) = 1326 
    [10.000, 12.500) = 172 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 46 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 63 
    [25.000, 27.500) = 98 
    [27.500, 30.000) = 39 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.755 ms/op
     p(50.0000) =      3.736 ms/op
     p(90.0000) =      4.375 ms/op
     p(95.0000) =      4.940 ms/op
     p(99.0000) =      7.045 ms/op
     p(99.9000) =     16.138 ms/op
     p(99.9900) =     28.606 ms/op
     p(99.9990) =     30.851 ms/op
     p(99.9999) =     31.982 ms/op
    p(100.0000) =     31.982 ms/op


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
# Warmup Iteration   1: 13.329 ±(99.9%) 0.196 ms/op
# Warmup Iteration   2: 4.446 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.045 ±(99.9%) 0.013 ms/op
Iteration   1: 4.063 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.935 ms/op
                 getUser·p0.50:   3.879 ms/op
                 getUser·p0.90:   4.448 ms/op
                 getUser·p0.95:   5.325 ms/op
                 getUser·p0.99:   8.184 ms/op
                 getUser·p0.999:  14.205 ms/op
                 getUser·p0.9999: 24.662 ms/op
                 getUser·p1.00:   25.428 ms/op

Iteration   2: 4.034 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   2.159 ms/op
                 getUser·p0.50:   3.879 ms/op
                 getUser·p0.90:   4.571 ms/op
                 getUser·p0.95:   4.932 ms/op
                 getUser·p0.99:   7.009 ms/op
                 getUser·p0.999:  23.905 ms/op
                 getUser·p0.9999: 26.676 ms/op
                 getUser·p1.00:   27.099 ms/op

Iteration   3: 4.001 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.260 ms/op
                 getUser·p0.50:   3.834 ms/op
                 getUser·p0.90:   4.604 ms/op
                 getUser·p0.95:   5.218 ms/op
                 getUser·p0.99:   7.371 ms/op
                 getUser·p0.999:  15.031 ms/op
                 getUser·p0.9999: 28.902 ms/op
                 getUser·p1.00:   29.491 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 237940
  mean =      4.032 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 114 
    [ 2.500,  5.000) = 224840 
    [ 5.000,  7.500) = 10478 
    [ 7.500, 10.000) = 1712 
    [10.000, 12.500) = 404 
    [12.500, 15.000) = 149 
    [15.000, 17.500) = 17 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 91 
    [25.000, 27.500) = 95 

  Percentiles, ms/op:
      p(0.0000) =      1.260 ms/op
     p(50.0000) =      3.858 ms/op
     p(90.0000) =      4.547 ms/op
     p(95.0000) =      5.112 ms/op
     p(99.0000) =      7.619 ms/op
     p(99.9000) =     15.281 ms/op
     p(99.9900) =     27.631 ms/op
     p(99.9990) =     29.167 ms/op
     p(99.9999) =     29.491 ms/op
    p(100.0000) =     29.491 ms/op


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
# Warmup Iteration   1: 12.784 ±(99.9%) 0.190 ms/op
# Warmup Iteration   2: 5.520 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 4.784 ±(99.9%) 0.017 ms/op
Iteration   1: 4.723 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   2.030 ms/op
                 listUser·p0.50:   4.563 ms/op
                 listUser·p0.90:   5.038 ms/op
                 listUser·p0.95:   5.497 ms/op
                 listUser·p0.99:   9.191 ms/op
                 listUser·p0.999:  26.706 ms/op
                 listUser·p0.9999: 28.916 ms/op
                 listUser·p1.00:   30.769 ms/op

Iteration   2: 4.560 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.097 ms/op
                 listUser·p0.50:   4.391 ms/op
                 listUser·p0.90:   4.915 ms/op
                 listUser·p0.95:   5.226 ms/op
                 listUser·p0.99:   8.438 ms/op
                 listUser·p0.999:  16.777 ms/op
                 listUser·p0.9999: 20.578 ms/op
                 listUser·p1.00:   21.529 ms/op

Iteration   3: 4.540 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.954 ms/op
                 listUser·p0.50:   4.350 ms/op
                 listUser·p0.90:   5.005 ms/op
                 listUser·p0.95:   5.333 ms/op
                 listUser·p0.99:   8.569 ms/op
                 listUser·p0.999:  18.072 ms/op
                 listUser·p0.9999: 22.281 ms/op
                 listUser·p1.00:   22.282 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 208421
  mean =      4.606 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19 
    [ 2.500,  5.000) = 188131 
    [ 5.000,  7.500) = 15965 
    [ 7.500, 10.000) = 3061 
    [10.000, 12.500) = 564 
    [12.500, 15.000) = 248 
    [15.000, 17.500) = 128 
    [17.500, 20.000) = 95 
    [20.000, 22.500) = 63 
    [22.500, 25.000) = 39 
    [25.000, 27.500) = 74 
    [27.500, 30.000) = 31 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.954 ms/op
     p(50.0000) =      4.424 ms/op
     p(90.0000) =      4.989 ms/op
     p(95.0000) =      5.341 ms/op
     p(99.0000) =      8.831 ms/op
     p(99.9000) =     20.176 ms/op
     p(99.9900) =     28.279 ms/op
     p(99.9990) =     30.627 ms/op
     p(99.9999) =     30.769 ms/op
    p(100.0000) =     30.769 ms/op


# Run complete. Total time: 00:13:16

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.034 ± 5.513  ops/ms
ClientPb.existUser                       thrpt       3   8.144 ± 1.621  ops/ms
ClientPb.getUser                         thrpt       3   8.195 ± 2.096  ops/ms
ClientPb.listUser                        thrpt       3   6.904 ± 3.905  ops/ms
ClientPb.createUser                       avgt       3   3.970 ± 0.674   ms/op
ClientPb.existUser                        avgt       3   3.825 ± 2.072   ms/op
ClientPb.getUser                          avgt       3   3.866 ± 0.237   ms/op
ClientPb.listUser                         avgt       3   4.578 ± 0.610   ms/op
ClientPb.createUser                     sample  241549   3.975 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.290           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.809           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.653           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.095           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.943           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.361           ms/op
ClientPb.createUser:createUser·p0.9999  sample          32.735           ms/op
ClientPb.createUser:createUser·p1.00    sample          35.521           ms/op
ClientPb.existUser                      sample  249852   3.843 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.755           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.736           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.375           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.940           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.045           ms/op
ClientPb.existUser:existUser·p0.999     sample          16.138           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.606           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.982           ms/op
ClientPb.getUser                        sample  237940   4.032 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.260           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.858           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.547           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.112           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.619           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.281           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.631           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.491           ms/op
ClientPb.listUser                       sample  208421   4.606 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.954           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.424           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.989           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.341           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.831           ms/op
ClientPb.listUser:listUser·p0.999       sample          20.176           ms/op
ClientPb.listUser:listUser·p0.9999      sample          28.279           ms/op
ClientPb.listUser:listUser·p1.00        sample          30.769           ms/op
