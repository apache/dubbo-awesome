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
# Warmup Iteration   1: 0.888 ops/ms
# Warmup Iteration   2: 2.050 ops/ms
# Warmup Iteration   3: 4.613 ops/ms
Iteration   1: 5.302 ops/ms
Iteration   2: 5.291 ops/ms
Iteration   3: 5.494 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.363 ±(99.9%) 2.082 ops/ms [Average]
  (min, avg, max) = (5.291, 5.363, 5.494), stdev = 0.114
  CI (99.9%): [3.281, 7.445] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:18
# Fork: 1 of 1
# Warmup Iteration   1: 1.304 ops/ms
# Warmup Iteration   2: 4.086 ops/ms
# Warmup Iteration   3: 5.233 ops/ms
Iteration   1: 5.599 ops/ms
Iteration   2: 5.649 ops/ms
Iteration   3: 5.618 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.622 ±(99.9%) 0.460 ops/ms [Average]
  (min, avg, max) = (5.599, 5.622, 5.649), stdev = 0.025
  CI (99.9%): [5.162, 6.081] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:10
# Fork: 1 of 1
# Warmup Iteration   1: 1.558 ops/ms
# Warmup Iteration   2: 4.261 ops/ms
# Warmup Iteration   3: 5.329 ops/ms
Iteration   1: 5.575 ops/ms
Iteration   2: 5.490 ops/ms
Iteration   3: 5.603 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.556 ±(99.9%) 1.079 ops/ms [Average]
  (min, avg, max) = (5.490, 5.556, 5.603), stdev = 0.059
  CI (99.9%): [4.478, 6.635] (assumes normal distribution)


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
# Warmup Iteration   1: 1.539 ops/ms
# Warmup Iteration   2: 3.882 ops/ms
# Warmup Iteration   3: 4.544 ops/ms
Iteration   1: 4.667 ops/ms
Iteration   2: 4.629 ops/ms
Iteration   3: 4.779 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.692 ±(99.9%) 1.423 ops/ms [Average]
  (min, avg, max) = (4.629, 4.692, 4.779), stdev = 0.078
  CI (99.9%): [3.269, 6.114] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:55
# Fork: 1 of 1
# Warmup Iteration   1: 18.993 ±(99.9%) 0.093 ms/op
# Warmup Iteration   2: 7.212 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 6.353 ±(99.9%) 0.011 ms/op
Iteration   1: 5.791 ±(99.9%) 0.011 ms/op
Iteration   2: 5.859 ±(99.9%) 0.014 ms/op
Iteration   3: 5.824 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.825 ±(99.9%) 0.626 ms/op [Average]
  (min, avg, max) = (5.791, 5.825, 5.859), stdev = 0.034
  CI (99.9%): [5.198, 6.451] (assumes normal distribution)


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
# Warmup Iteration   1: 15.937 ±(99.9%) 0.070 ms/op
# Warmup Iteration   2: 6.085 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.569 ±(99.9%) 0.008 ms/op
Iteration   1: 5.410 ±(99.9%) 0.013 ms/op
Iteration   2: 5.517 ±(99.9%) 0.009 ms/op
Iteration   3: 5.203 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.376 ±(99.9%) 2.918 ms/op [Average]
  (min, avg, max) = (5.203, 5.376, 5.517), stdev = 0.160
  CI (99.9%): [2.459, 8.294] (assumes normal distribution)


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
# Warmup Iteration   1: 18.944 ±(99.9%) 0.086 ms/op
# Warmup Iteration   2: 7.416 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 6.150 ±(99.9%) 0.008 ms/op
Iteration   1: 6.003 ±(99.9%) 0.010 ms/op
Iteration   2: 5.931 ±(99.9%) 0.009 ms/op
Iteration   3: 5.762 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.899 ±(99.9%) 2.255 ms/op [Average]
  (min, avg, max) = (5.762, 5.899, 6.003), stdev = 0.124
  CI (99.9%): [3.643, 8.154] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:33
# Fork: 1 of 1
# Warmup Iteration   1: 21.315 ±(99.9%) 0.092 ms/op
# Warmup Iteration   2: 8.697 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 6.764 ±(99.9%) 0.015 ms/op
Iteration   1: 6.570 ±(99.9%) 0.009 ms/op
Iteration   2: 6.590 ±(99.9%) 0.011 ms/op
Iteration   3: 6.333 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.498 ±(99.9%) 2.607 ms/op [Average]
  (min, avg, max) = (6.333, 6.498, 6.590), stdev = 0.143
  CI (99.9%): [3.891, 9.105] (assumes normal distribution)


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
# Warmup Iteration   1: 18.498 ±(99.9%) 0.285 ms/op
# Warmup Iteration   2: 7.131 ±(99.9%) 0.048 ms/op
# Warmup Iteration   3: 5.666 ±(99.9%) 0.024 ms/op
Iteration   1: 5.632 ±(99.9%) 0.022 ms/op
                 createUser·p0.00:   2.046 ms/op
                 createUser·p0.50:   5.243 ms/op
                 createUser·p0.90:   7.356 ms/op
                 createUser·p0.95:   8.258 ms/op
                 createUser·p0.99:   10.863 ms/op
                 createUser·p0.999:  24.871 ms/op
                 createUser·p0.9999: 34.645 ms/op
                 createUser·p1.00:   37.224 ms/op

Iteration   2: 5.416 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   2.630 ms/op
                 createUser·p0.50:   5.038 ms/op
                 createUser·p0.90:   6.873 ms/op
                 createUser·p0.95:   7.733 ms/op
                 createUser·p0.99:   10.420 ms/op
                 createUser·p0.999:  27.722 ms/op
                 createUser·p0.9999: 30.540 ms/op
                 createUser·p1.00:   32.834 ms/op

Iteration   3: 5.556 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   1.767 ms/op
                 createUser·p0.50:   5.284 ms/op
                 createUser·p0.90:   6.873 ms/op
                 createUser·p0.95:   7.897 ms/op
                 createUser·p0.99:   10.748 ms/op
                 createUser·p0.999:  28.574 ms/op
                 createUser·p0.9999: 34.734 ms/op
                 createUser·p1.00:   36.700 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 173388
  mean =      5.533 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15 
    [ 2.500,  5.000) = 70211 
    [ 5.000,  7.500) = 90827 
    [ 7.500, 10.000) = 9904 
    [10.000, 12.500) = 1707 
    [12.500, 15.000) = 400 
    [15.000, 17.500) = 82 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 37 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 30 
    [27.500, 30.000) = 75 
    [30.000, 32.500) = 40 
    [32.500, 35.000) = 31 
    [35.000, 37.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      1.767 ms/op
     p(50.0000) =      5.177 ms/op
     p(90.0000) =      7.012 ms/op
     p(95.0000) =      8.012 ms/op
     p(99.0000) =     10.666 ms/op
     p(99.9000) =     25.448 ms/op
     p(99.9900) =     34.472 ms/op
     p(99.9990) =     36.840 ms/op
     p(99.9999) =     37.224 ms/op
    p(100.0000) =     37.224 ms/op


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
# Warmup Iteration   1: 16.916 ±(99.9%) 0.284 ms/op
# Warmup Iteration   2: 6.424 ±(99.9%) 0.040 ms/op
# Warmup Iteration   3: 5.645 ±(99.9%) 0.022 ms/op
Iteration   1: 5.347 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   2.003 ms/op
                 existUser·p0.50:   4.964 ms/op
                 existUser·p0.90:   6.783 ms/op
                 existUser·p0.95:   7.954 ms/op
                 existUser·p0.99:   11.092 ms/op
                 existUser·p0.999:  24.773 ms/op
                 existUser·p0.9999: 29.329 ms/op
                 existUser·p1.00:   30.179 ms/op

Iteration   2: 5.455 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   1.298 ms/op
                 existUser·p0.50:   5.030 ms/op
                 existUser·p0.90:   6.980 ms/op
                 existUser·p0.95:   8.200 ms/op
                 existUser·p0.99:   11.158 ms/op
                 existUser·p0.999:  17.359 ms/op
                 existUser·p0.9999: 36.700 ms/op
                 existUser·p1.00:   37.028 ms/op

Iteration   3: 5.456 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   2.367 ms/op
                 existUser·p0.50:   5.112 ms/op
                 existUser·p0.90:   6.996 ms/op
                 existUser·p0.95:   7.856 ms/op
                 existUser·p0.99:   10.420 ms/op
                 existUser·p0.999:  26.519 ms/op
                 existUser·p0.9999: 33.133 ms/op
                 existUser·p1.00:   33.686 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 177003
  mean =      5.419 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 35 
    [ 2.500,  5.000) = 85336 
    [ 5.000,  7.500) = 79581 
    [ 7.500, 10.000) = 9103 
    [10.000, 12.500) = 2156 
    [12.500, 15.000) = 521 
    [15.000, 17.500) = 86 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 41 
    [27.500, 30.000) = 44 
    [30.000, 32.500) = 21 
    [32.500, 35.000) = 16 
    [35.000, 37.500) = 29 

  Percentiles, ms/op:
      p(0.0000) =      1.298 ms/op
     p(50.0000) =      5.030 ms/op
     p(90.0000) =      6.922 ms/op
     p(95.0000) =      7.995 ms/op
     p(99.0000) =     10.945 ms/op
     p(99.9000) =     17.793 ms/op
     p(99.9900) =     35.783 ms/op
     p(99.9990) =     37.028 ms/op
     p(99.9999) =     37.028 ms/op
    p(100.0000) =     37.028 ms/op


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
# Warmup Iteration   1: 18.222 ±(99.9%) 0.308 ms/op
# Warmup Iteration   2: 6.610 ±(99.9%) 0.040 ms/op
# Warmup Iteration   3: 5.756 ±(99.9%) 0.021 ms/op
Iteration   1: 5.781 ±(99.9%) 0.028 ms/op
                 getUser·p0.00:   1.923 ms/op
                 getUser·p0.50:   5.251 ms/op
                 getUser·p0.90:   7.496 ms/op
                 getUser·p0.95:   9.093 ms/op
                 getUser·p0.99:   14.156 ms/op
                 getUser·p0.999:  27.630 ms/op
                 getUser·p0.9999: 33.817 ms/op
                 getUser·p1.00:   34.144 ms/op

Iteration   2: 5.828 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   1.901 ms/op
                 getUser·p0.50:   5.505 ms/op
                 getUser·p0.90:   7.479 ms/op
                 getUser·p0.95:   8.487 ms/op
                 getUser·p0.99:   11.469 ms/op
                 getUser·p0.999:  27.016 ms/op
                 getUser·p0.9999: 30.807 ms/op
                 getUser·p1.00:   31.261 ms/op

Iteration   3: 5.729 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   2.818 ms/op
                 getUser·p0.50:   5.399 ms/op
                 getUser·p0.90:   7.086 ms/op
                 getUser·p0.95:   8.315 ms/op
                 getUser·p0.99:   11.354 ms/op
                 getUser·p0.999:  15.015 ms/op
                 getUser·p0.9999: 34.303 ms/op
                 getUser·p1.00:   34.537 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 165934
  mean =      5.779 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3 
    [ 2.500,  5.000) = 47202 
    [ 5.000,  7.500) = 103480 
    [ 7.500, 10.000) = 10851 
    [10.000, 12.500) = 2868 
    [12.500, 15.000) = 887 
    [15.000, 17.500) = 274 
    [17.500, 20.000) = 135 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 48 
    [27.500, 30.000) = 61 
    [30.000, 32.500) = 52 
    [32.500, 35.000) = 24 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.901 ms/op
     p(50.0000) =      5.390 ms/op
     p(90.0000) =      7.340 ms/op
     p(95.0000) =      8.651 ms/op
     p(99.0000) =     12.222 ms/op
     p(99.9000) =     26.249 ms/op
     p(99.9900) =     33.267 ms/op
     p(99.9990) =     34.451 ms/op
     p(99.9999) =     34.537 ms/op
    p(100.0000) =     34.537 ms/op


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
# Warmup Iteration   1: 19.864 ±(99.9%) 0.335 ms/op
# Warmup Iteration   2: 8.184 ±(99.9%) 0.055 ms/op
# Warmup Iteration   3: 6.600 ±(99.9%) 0.029 ms/op
Iteration   1: 6.480 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   2.593 ms/op
                 listUser·p0.50:   5.988 ms/op
                 listUser·p0.90:   8.151 ms/op
                 listUser·p0.95:   9.470 ms/op
                 listUser·p0.99:   13.468 ms/op
                 listUser·p0.999:  29.185 ms/op
                 listUser·p0.9999: 31.130 ms/op
                 listUser·p1.00:   31.621 ms/op

Iteration   2: 6.433 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   1.954 ms/op
                 listUser·p0.50:   6.021 ms/op
                 listUser·p0.90:   7.922 ms/op
                 listUser·p0.95:   8.962 ms/op
                 listUser·p0.99:   11.944 ms/op
                 listUser·p0.999:  29.247 ms/op
                 listUser·p0.9999: 39.194 ms/op
                 listUser·p1.00:   39.649 ms/op

Iteration   3: 6.382 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   2.013 ms/op
                 listUser·p0.50:   5.972 ms/op
                 listUser·p0.90:   7.807 ms/op
                 listUser·p0.95:   9.028 ms/op
                 listUser·p0.99:   12.501 ms/op
                 listUser·p0.999:  24.572 ms/op
                 listUser·p0.9999: 29.360 ms/op
                 listUser·p1.00:   30.474 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 149177
  mean =      6.431 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8 
    [ 2.500,  5.000) = 6570 
    [ 5.000,  7.500) = 121932 
    [ 7.500, 10.000) = 15723 
    [10.000, 12.500) = 3420 
    [12.500, 15.000) = 840 
    [15.000, 17.500) = 280 
    [17.500, 20.000) = 68 
    [20.000, 22.500) = 71 
    [22.500, 25.000) = 36 
    [25.000, 27.500) = 51 
    [27.500, 30.000) = 115 
    [30.000, 32.500) = 31 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      1.954 ms/op
     p(50.0000) =      5.988 ms/op
     p(90.0000) =      7.971 ms/op
     p(95.0000) =      9.159 ms/op
     p(99.0000) =     12.550 ms/op
     p(99.9000) =     28.475 ms/op
     p(99.9900) =     37.820 ms/op
     p(99.9990) =     39.585 ms/op
     p(99.9999) =     39.649 ms/op
    p(100.0000) =     39.649 ms/op


# Run complete. Total time: 00:13:22

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.363 ± 2.082  ops/ms
ClientPb.existUser                       thrpt       3   5.622 ± 0.460  ops/ms
ClientPb.getUser                         thrpt       3   5.556 ± 1.079  ops/ms
ClientPb.listUser                        thrpt       3   4.692 ± 1.423  ops/ms
ClientPb.createUser                       avgt       3   5.825 ± 0.626   ms/op
ClientPb.existUser                        avgt       3   5.376 ± 2.918   ms/op
ClientPb.getUser                          avgt       3   5.899 ± 2.255   ms/op
ClientPb.listUser                         avgt       3   6.498 ± 2.607   ms/op
ClientPb.createUser                     sample  173388   5.533 ± 0.012   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.767           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.177           ms/op
ClientPb.createUser:createUser·p0.90    sample           7.012           ms/op
ClientPb.createUser:createUser·p0.95    sample           8.012           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.666           ms/op
ClientPb.createUser:createUser·p0.999   sample          25.448           ms/op
ClientPb.createUser:createUser·p0.9999  sample          34.472           ms/op
ClientPb.createUser:createUser·p1.00    sample          37.224           ms/op
ClientPb.existUser                      sample  177003   5.419 ± 0.012   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.298           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.030           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.922           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.995           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.945           ms/op
ClientPb.existUser:existUser·p0.999     sample          17.793           ms/op
ClientPb.existUser:existUser·p0.9999    sample          35.783           ms/op
ClientPb.existUser:existUser·p1.00      sample          37.028           ms/op
ClientPb.getUser                        sample  165934   5.779 ± 0.014   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.901           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.390           ms/op
ClientPb.getUser:getUser·p0.90          sample           7.340           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.651           ms/op
ClientPb.getUser:getUser·p0.99          sample          12.222           ms/op
ClientPb.getUser:getUser·p0.999         sample          26.249           ms/op
ClientPb.getUser:getUser·p0.9999        sample          33.267           ms/op
ClientPb.getUser:getUser·p1.00          sample          34.537           ms/op
ClientPb.listUser                       sample  149177   6.431 ± 0.015   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.954           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.988           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.971           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.159           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.550           ms/op
ClientPb.listUser:listUser·p0.999       sample          28.475           ms/op
ClientPb.listUser:listUser·p0.9999      sample          37.820           ms/op
ClientPb.listUser:listUser·p1.00        sample          39.649           ms/op
