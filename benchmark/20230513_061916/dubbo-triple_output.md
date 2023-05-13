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
# Warmup Iteration   1: 0.847 ops/ms
# Warmup Iteration   2: 1.846 ops/ms
# Warmup Iteration   3: 3.583 ops/ms
Iteration   1: 4.074 ops/ms
Iteration   2: 4.496 ops/ms
Iteration   3: 4.548 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.373 ±(99.9%) 4.741 ops/ms [Average]
  (min, avg, max) = (4.074, 4.373, 4.548), stdev = 0.260
  CI (99.9%): [≈ 0, 9.114] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:20
# Fork: 1 of 1
# Warmup Iteration   1: 1.180 ops/ms
# Warmup Iteration   2: 3.371 ops/ms
# Warmup Iteration   3: 4.886 ops/ms
Iteration   1: 5.089 ops/ms
Iteration   2: 4.976 ops/ms
Iteration   3: 5.129 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.065 ±(99.9%) 1.451 ops/ms [Average]
  (min, avg, max) = (4.976, 5.065, 5.129), stdev = 0.080
  CI (99.9%): [3.614, 6.516] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:12
# Fork: 1 of 1
# Warmup Iteration   1: 1.224 ops/ms
# Warmup Iteration   2: 3.198 ops/ms
# Warmup Iteration   3: 4.585 ops/ms
Iteration   1: 4.952 ops/ms
Iteration   2: 4.781 ops/ms
Iteration   3: 4.703 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.812 ±(99.9%) 2.323 ops/ms [Average]
  (min, avg, max) = (4.703, 4.812, 4.952), stdev = 0.127
  CI (99.9%): [2.488, 7.135] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:10:02
# Fork: 1 of 1
# Warmup Iteration   1: 1.245 ops/ms
# Warmup Iteration   2: 2.427 ops/ms
# Warmup Iteration   3: 3.954 ops/ms
Iteration   1: 3.991 ops/ms
Iteration   2: 3.966 ops/ms
Iteration   3: 3.994 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.983 ±(99.9%) 0.278 ops/ms [Average]
  (min, avg, max) = (3.966, 3.983, 3.994), stdev = 0.015
  CI (99.9%): [3.706, 4.261] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:56
# Fork: 1 of 1
# Warmup Iteration   1: 22.905 ±(99.9%) 0.145 ms/op
# Warmup Iteration   2: 8.669 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 7.093 ±(99.9%) 0.020 ms/op
Iteration   1: 7.168 ±(99.9%) 0.020 ms/op
Iteration   2: 6.771 ±(99.9%) 0.013 ms/op
Iteration   3: 6.975 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.971 ±(99.9%) 3.623 ms/op [Average]
  (min, avg, max) = (6.771, 6.971, 7.168), stdev = 0.199
  CI (99.9%): [3.348, 10.594] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:48
# Fork: 1 of 1
# Warmup Iteration   1: 21.618 ±(99.9%) 0.113 ms/op
# Warmup Iteration   2: 8.004 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 6.742 ±(99.9%) 0.013 ms/op
Iteration   1: 7.169 ±(99.9%) 0.013 ms/op
Iteration   2: 6.647 ±(99.9%) 0.015 ms/op
Iteration   3: 6.464 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.760 ±(99.9%) 6.674 ms/op [Average]
  (min, avg, max) = (6.464, 6.760, 7.169), stdev = 0.366
  CI (99.9%): [0.086, 13.434] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:41
# Fork: 1 of 1
# Warmup Iteration   1: 21.776 ±(99.9%) 0.125 ms/op
# Warmup Iteration   2: 9.107 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 6.873 ±(99.9%) 0.016 ms/op
Iteration   1: 6.724 ±(99.9%) 0.012 ms/op
Iteration   2: 6.517 ±(99.9%) 0.013 ms/op
Iteration   3: 6.485 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.575 ±(99.9%) 2.372 ms/op [Average]
  (min, avg, max) = (6.485, 6.575, 6.724), stdev = 0.130
  CI (99.9%): [4.204, 8.947] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:34
# Fork: 1 of 1
# Warmup Iteration   1: 26.162 ±(99.9%) 0.181 ms/op
# Warmup Iteration   2: 11.728 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 8.080 ±(99.9%) 0.018 ms/op
Iteration   1: 7.841 ±(99.9%) 0.019 ms/op
Iteration   2: 7.881 ±(99.9%) 0.015 ms/op
Iteration   3: 8.104 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.942 ±(99.9%) 2.586 ms/op [Average]
  (min, avg, max) = (7.841, 7.942, 8.104), stdev = 0.142
  CI (99.9%): [5.356, 10.528] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:27
# Fork: 1 of 1
# Warmup Iteration   1: 22.453 ±(99.9%) 0.433 ms/op
# Warmup Iteration   2: 9.452 ±(99.9%) 0.080 ms/op
# Warmup Iteration   3: 7.628 ±(99.9%) 0.049 ms/op
Iteration   1: 6.944 ±(99.9%) 0.034 ms/op
                 createUser·p0.00:   2.765 ms/op
                 createUser·p0.50:   6.390 ms/op
                 createUser·p0.90:   9.601 ms/op
                 createUser·p0.95:   11.125 ms/op
                 createUser·p0.99:   14.533 ms/op
                 createUser·p0.999:  27.853 ms/op
                 createUser·p0.9999: 31.864 ms/op
                 createUser·p1.00:   33.423 ms/op

Iteration   2: 7.231 ±(99.9%) 0.038 ms/op
                 createUser·p0.00:   2.597 ms/op
                 createUser·p0.50:   6.603 ms/op
                 createUser·p0.90:   10.158 ms/op
                 createUser·p0.95:   11.633 ms/op
                 createUser·p0.99:   14.615 ms/op
                 createUser·p0.999:  31.470 ms/op
                 createUser·p0.9999: 37.683 ms/op
                 createUser·p1.00:   39.715 ms/op

Iteration   3: 7.348 ±(99.9%) 0.039 ms/op
                 createUser·p0.00:   2.871 ms/op
                 createUser·p0.50:   6.783 ms/op
                 createUser·p0.90:   10.224 ms/op
                 createUser·p0.95:   11.780 ms/op
                 createUser·p0.99:   15.401 ms/op
                 createUser·p0.999:  21.561 ms/op
                 createUser·p0.9999: 46.049 ms/op
                 createUser·p1.00:   46.334 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 133867
  mean =      7.170 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 10600 
    [ 5.000, 10.000) = 109975 
    [10.000, 15.000) = 12054 
    [15.000, 20.000) = 942 
    [20.000, 25.000) = 119 
    [25.000, 30.000) = 47 
    [30.000, 35.000) = 84 
    [35.000, 40.000) = 14 
    [40.000, 45.000) = 25 

  Percentiles, ms/op:
      p(0.0000) =      2.597 ms/op
     p(50.0000) =      6.578 ms/op
     p(90.0000) =      9.994 ms/op
     p(95.0000) =     11.534 ms/op
     p(99.0000) =     14.811 ms/op
     p(99.9000) =     29.106 ms/op
     p(99.9900) =     44.499 ms/op
     p(99.9990) =     46.312 ms/op
     p(99.9999) =     46.334 ms/op
    p(100.0000) =     46.334 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:20
# Fork: 1 of 1
# Warmup Iteration   1: 22.292 ±(99.9%) 0.492 ms/op
# Warmup Iteration   2: 9.517 ±(99.9%) 0.085 ms/op
# Warmup Iteration   3: 7.077 ±(99.9%) 0.039 ms/op
Iteration   1: 6.695 ±(99.9%) 0.034 ms/op
                 existUser·p0.00:   1.239 ms/op
                 existUser·p0.50:   6.185 ms/op
                 existUser·p0.90:   9.159 ms/op
                 existUser·p0.95:   10.437 ms/op
                 existUser·p0.99:   14.025 ms/op
                 existUser·p0.999:  32.848 ms/op
                 existUser·p0.9999: 42.416 ms/op
                 existUser·p1.00:   43.647 ms/op

Iteration   2: 6.659 ±(99.9%) 0.034 ms/op
                 existUser·p0.00:   0.515 ms/op
                 existUser·p0.50:   6.128 ms/op
                 existUser·p0.90:   8.978 ms/op
                 existUser·p0.95:   10.502 ms/op
                 existUser·p0.99:   14.909 ms/op
                 existUser·p0.999:  30.109 ms/op
                 existUser·p0.9999: 35.140 ms/op
                 existUser·p1.00:   35.717 ms/op

Iteration   3: 6.589 ±(99.9%) 0.033 ms/op
                 existUser·p0.00:   2.220 ms/op
                 existUser·p0.50:   6.119 ms/op
                 existUser·p0.90:   8.651 ms/op
                 existUser·p0.95:   9.896 ms/op
                 existUser·p0.99:   14.598 ms/op
                 existUser·p0.999:  32.932 ms/op
                 existUser·p0.9999: 46.550 ms/op
                 existUser·p1.00:   48.169 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 144320
  mean =      6.647 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 19635 
    [ 5.000, 10.000) = 116390 
    [10.000, 15.000) = 7096 
    [15.000, 20.000) = 838 
    [20.000, 25.000) = 146 
    [25.000, 30.000) = 39 
    [30.000, 35.000) = 106 
    [35.000, 40.000) = 20 
    [40.000, 45.000) = 19 

  Percentiles, ms/op:
      p(0.0000) =      0.515 ms/op
     p(50.0000) =      6.144 ms/op
     p(90.0000) =      8.946 ms/op
     p(95.0000) =     10.289 ms/op
     p(99.0000) =     14.516 ms/op
     p(99.9000) =     31.578 ms/op
     p(99.9900) =     45.941 ms/op
     p(99.9990) =     48.140 ms/op
     p(99.9999) =     48.169 ms/op
    p(100.0000) =     48.169 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 24.083 ±(99.9%) 0.426 ms/op
# Warmup Iteration   2: 8.588 ±(99.9%) 0.068 ms/op
# Warmup Iteration   3: 6.938 ±(99.9%) 0.035 ms/op
Iteration   1: 6.759 ±(99.9%) 0.032 ms/op
                 getUser·p0.00:   0.801 ms/op
                 getUser·p0.50:   6.291 ms/op
                 getUser·p0.90:   8.962 ms/op
                 getUser·p0.95:   10.338 ms/op
                 getUser·p0.99:   14.467 ms/op
                 getUser·p0.999:  29.106 ms/op
                 getUser·p0.9999: 32.951 ms/op
                 getUser·p1.00:   35.389 ms/op

Iteration   2: 6.973 ±(99.9%) 0.038 ms/op
                 getUser·p0.00:   1.798 ms/op
                 getUser·p0.50:   6.447 ms/op
                 getUser·p0.90:   9.126 ms/op
                 getUser·p0.95:   10.953 ms/op
                 getUser·p0.99:   17.678 ms/op
                 getUser·p0.999:  31.162 ms/op
                 getUser·p0.9999: 32.659 ms/op
                 getUser·p1.00:   33.260 ms/op

Iteration   3: 6.628 ±(99.9%) 0.031 ms/op
                 getUser·p0.00:   2.830 ms/op
                 getUser·p0.50:   6.152 ms/op
                 getUser·p0.90:   8.864 ms/op
                 getUser·p0.95:   10.060 ms/op
                 getUser·p0.99:   13.861 ms/op
                 getUser·p0.999:  24.430 ms/op
                 getUser·p0.9999: 40.185 ms/op
                 getUser·p1.00:   48.234 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 141451
  mean =      6.784 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 13449 
    [ 5.000, 10.000) = 119602 
    [10.000, 15.000) = 6914 
    [15.000, 20.000) = 981 
    [20.000, 25.000) = 294 
    [25.000, 30.000) = 66 
    [30.000, 35.000) = 104 
    [35.000, 40.000) = 34 
    [40.000, 45.000) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.801 ms/op
     p(50.0000) =      6.291 ms/op
     p(90.0000) =      8.978 ms/op
     p(95.0000) =     10.404 ms/op
     p(99.0000) =     15.155 ms/op
     p(99.9000) =     30.048 ms/op
     p(99.9900) =     39.452 ms/op
     p(99.9990) =     45.110 ms/op
     p(99.9999) =     48.234 ms/op
    p(100.0000) =     48.234 ms/op


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
# Warmup Iteration   1: 26.369 ±(99.9%) 0.532 ms/op
# Warmup Iteration   2: 11.369 ±(99.9%) 0.111 ms/op
# Warmup Iteration   3: 8.163 ±(99.9%) 0.038 ms/op
Iteration   1: 8.126 ±(99.9%) 0.039 ms/op
                 listUser·p0.00:   3.342 ms/op
                 listUser·p0.50:   7.602 ms/op
                 listUser·p0.90:   10.600 ms/op
                 listUser·p0.95:   11.960 ms/op
                 listUser·p0.99:   15.876 ms/op
                 listUser·p0.999:  32.199 ms/op
                 listUser·p0.9999: 37.093 ms/op
                 listUser·p1.00:   37.552 ms/op

Iteration   2: 7.828 ±(99.9%) 0.034 ms/op
                 listUser·p0.00:   1.407 ms/op
                 listUser·p0.50:   7.332 ms/op
                 listUser·p0.90:   10.338 ms/op
                 listUser·p0.95:   11.796 ms/op
                 listUser·p0.99:   14.336 ms/op
                 listUser·p0.999:  31.677 ms/op
                 listUser·p0.9999: 37.088 ms/op
                 listUser·p1.00:   37.421 ms/op

Iteration   3: 7.987 ±(99.9%) 0.042 ms/op
                 listUser·p0.00:   3.244 ms/op
                 listUser·p0.50:   7.479 ms/op
                 listUser·p0.90:   10.142 ms/op
                 listUser·p0.95:   11.452 ms/op
                 listUser·p0.99:   15.794 ms/op
                 listUser·p0.999:  37.683 ms/op
                 listUser·p0.9999: 41.418 ms/op
                 listUser·p1.00:   42.992 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 120251
  mean =      7.979 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 743 
    [ 5.000, 10.000) = 105108 
    [10.000, 15.000) = 13156 
    [15.000, 20.000) = 798 
    [20.000, 25.000) = 114 
    [25.000, 30.000) = 69 
    [30.000, 35.000) = 146 
    [35.000, 40.000) = 103 
    [40.000, 45.000) = 14 

  Percentiles, ms/op:
      p(0.0000) =      1.407 ms/op
     p(50.0000) =      7.463 ms/op
     p(90.0000) =     10.371 ms/op
     p(95.0000) =     11.731 ms/op
     p(99.0000) =     15.122 ms/op
     p(99.9000) =     34.865 ms/op
     p(99.9900) =     40.237 ms/op
     p(99.9990) =     42.806 ms/op
     p(99.9999) =     42.992 ms/op
    p(100.0000) =     42.992 ms/op


# Run complete. Total time: 00:13:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   4.373 ± 4.741  ops/ms
ClientPb.existUser                       thrpt       3   5.065 ± 1.451  ops/ms
ClientPb.getUser                         thrpt       3   4.812 ± 2.323  ops/ms
ClientPb.listUser                        thrpt       3   3.983 ± 0.278  ops/ms
ClientPb.createUser                       avgt       3   6.971 ± 3.623   ms/op
ClientPb.existUser                        avgt       3   6.760 ± 6.674   ms/op
ClientPb.getUser                          avgt       3   6.575 ± 2.372   ms/op
ClientPb.listUser                         avgt       3   7.942 ± 2.586   ms/op
ClientPb.createUser                     sample  133867   7.170 ± 0.021   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.597           ms/op
ClientPb.createUser:createUser·p0.50    sample           6.578           ms/op
ClientPb.createUser:createUser·p0.90    sample           9.994           ms/op
ClientPb.createUser:createUser·p0.95    sample          11.534           ms/op
ClientPb.createUser:createUser·p0.99    sample          14.811           ms/op
ClientPb.createUser:createUser·p0.999   sample          29.106           ms/op
ClientPb.createUser:createUser·p0.9999  sample          44.499           ms/op
ClientPb.createUser:createUser·p1.00    sample          46.334           ms/op
ClientPb.existUser                      sample  144320   6.647 ± 0.019   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.515           ms/op
ClientPb.existUser:existUser·p0.50      sample           6.144           ms/op
ClientPb.existUser:existUser·p0.90      sample           8.946           ms/op
ClientPb.existUser:existUser·p0.95      sample          10.289           ms/op
ClientPb.existUser:existUser·p0.99      sample          14.516           ms/op
ClientPb.existUser:existUser·p0.999     sample          31.578           ms/op
ClientPb.existUser:existUser·p0.9999    sample          45.941           ms/op
ClientPb.existUser:existUser·p1.00      sample          48.169           ms/op
ClientPb.getUser                        sample  141451   6.784 ± 0.020   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.801           ms/op
ClientPb.getUser:getUser·p0.50          sample           6.291           ms/op
ClientPb.getUser:getUser·p0.90          sample           8.978           ms/op
ClientPb.getUser:getUser·p0.95          sample          10.404           ms/op
ClientPb.getUser:getUser·p0.99          sample          15.155           ms/op
ClientPb.getUser:getUser·p0.999         sample          30.048           ms/op
ClientPb.getUser:getUser·p0.9999        sample          39.452           ms/op
ClientPb.getUser:getUser·p1.00          sample          48.234           ms/op
ClientPb.listUser                       sample  120251   7.979 ± 0.022   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.407           ms/op
ClientPb.listUser:listUser·p0.50        sample           7.463           ms/op
ClientPb.listUser:listUser·p0.90        sample          10.371           ms/op
ClientPb.listUser:listUser·p0.95        sample          11.731           ms/op
ClientPb.listUser:listUser·p0.99        sample          15.122           ms/op
ClientPb.listUser:listUser·p0.999       sample          34.865           ms/op
ClientPb.listUser:listUser·p0.9999      sample          40.237           ms/op
ClientPb.listUser:listUser·p1.00        sample          42.992           ms/op
