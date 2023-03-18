# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.165 ops/ms
# Warmup Iteration   2: 2.431 ops/ms
# Warmup Iteration   3: 4.631 ops/ms
Iteration   1: 5.662 ops/ms
Iteration   2: 5.598 ops/ms
Iteration   3: 5.752 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.671 ±(99.9%) 1.405 ops/ms [Average]
  (min, avg, max) = (5.598, 5.671, 5.752), stdev = 0.077
  CI (99.9%): [4.266, 7.076] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:15
# Fork: 1 of 1
# Warmup Iteration   1: 1.532 ops/ms
# Warmup Iteration   2: 4.766 ops/ms
# Warmup Iteration   3: 6.029 ops/ms
Iteration   1: 6.317 ops/ms
Iteration   2: 6.253 ops/ms
Iteration   3: 6.449 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.339 ±(99.9%) 1.825 ops/ms [Average]
  (min, avg, max) = (6.253, 6.339, 6.449), stdev = 0.100
  CI (99.9%): [4.515, 8.164] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:03
# Fork: 1 of 1
# Warmup Iteration   1: 1.679 ops/ms
# Warmup Iteration   2: 4.951 ops/ms
# Warmup Iteration   3: 6.039 ops/ms
Iteration   1: 5.984 ops/ms
Iteration   2: 5.971 ops/ms
Iteration   3: 6.045 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.000 ±(99.9%) 0.722 ops/ms [Average]
  (min, avg, max) = (5.971, 6.000, 6.045), stdev = 0.040
  CI (99.9%): [5.278, 6.722] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:57
# Fork: 1 of 1
# Warmup Iteration   1: 1.474 ops/ms
# Warmup Iteration   2: 3.771 ops/ms
# Warmup Iteration   3: 4.533 ops/ms
Iteration   1: 4.799 ops/ms
Iteration   2: 4.995 ops/ms
Iteration   3: 5.076 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.957 ±(99.9%) 2.602 ops/ms [Average]
  (min, avg, max) = (4.799, 4.957, 5.076), stdev = 0.143
  CI (99.9%): [2.354, 7.559] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:52
# Fork: 1 of 1
# Warmup Iteration   1: 19.997 ±(99.9%) 0.142 ms/op
# Warmup Iteration   2: 6.613 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 5.594 ±(99.9%) 0.013 ms/op
Iteration   1: 5.302 ±(99.9%) 0.015 ms/op
Iteration   2: 5.514 ±(99.9%) 0.008 ms/op
Iteration   3: 5.484 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.433 ±(99.9%) 2.086 ms/op [Average]
  (min, avg, max) = (5.302, 5.433, 5.514), stdev = 0.114
  CI (99.9%): [3.347, 7.519] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:45
# Fork: 1 of 1
# Warmup Iteration   1: 16.164 ±(99.9%) 0.086 ms/op
# Warmup Iteration   2: 5.968 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 5.503 ±(99.9%) 0.011 ms/op
Iteration   1: 5.426 ±(99.9%) 0.009 ms/op
Iteration   2: 5.094 ±(99.9%) 0.008 ms/op
Iteration   3: 5.170 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.230 ±(99.9%) 3.174 ms/op [Average]
  (min, avg, max) = (5.094, 5.230, 5.426), stdev = 0.174
  CI (99.9%): [2.057, 8.404] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:39
# Fork: 1 of 1
# Warmup Iteration   1: 15.595 ±(99.9%) 0.089 ms/op
# Warmup Iteration   2: 7.426 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.792 ±(99.9%) 0.012 ms/op
Iteration   1: 5.613 ±(99.9%) 0.007 ms/op
Iteration   2: 5.418 ±(99.9%) 0.009 ms/op
Iteration   3: 5.434 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.488 ±(99.9%) 1.974 ms/op [Average]
  (min, avg, max) = (5.418, 5.488, 5.613), stdev = 0.108
  CI (99.9%): [3.515, 7.462] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:32
# Fork: 1 of 1
# Warmup Iteration   1: 20.779 ±(99.9%) 0.109 ms/op
# Warmup Iteration   2: 8.240 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 6.328 ±(99.9%) 0.008 ms/op
Iteration   1: 6.063 ±(99.9%) 0.015 ms/op
Iteration   2: 6.178 ±(99.9%) 0.010 ms/op
Iteration   3: 6.541 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.261 ±(99.9%) 4.558 ms/op [Average]
  (min, avg, max) = (6.063, 6.261, 6.541), stdev = 0.250
  CI (99.9%): [1.703, 10.819] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 19.477 ±(99.9%) 0.349 ms/op
# Warmup Iteration   2: 7.788 ±(99.9%) 0.068 ms/op
# Warmup Iteration   3: 5.794 ±(99.9%) 0.028 ms/op
Iteration   1: 5.351 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   2.249 ms/op
                 createUser·p0.50:   5.063 ms/op
                 createUser·p0.90:   6.578 ms/op
                 createUser·p0.95:   7.758 ms/op
                 createUser·p0.99:   11.280 ms/op
                 createUser·p0.999:  21.168 ms/op
                 createUser·p0.9999: 28.116 ms/op
                 createUser·p1.00:   28.639 ms/op

Iteration   2: 5.293 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   2.462 ms/op
                 createUser·p0.50:   4.989 ms/op
                 createUser·p0.90:   6.537 ms/op
                 createUser·p0.95:   7.741 ms/op
                 createUser·p0.99:   11.239 ms/op
                 createUser·p0.999:  25.598 ms/op
                 createUser·p0.9999: 31.978 ms/op
                 createUser·p1.00:   32.899 ms/op

Iteration   3: 5.509 ±(99.9%) 0.026 ms/op
                 createUser·p0.00:   2.179 ms/op
                 createUser·p0.50:   5.054 ms/op
                 createUser·p0.90:   7.217 ms/op
                 createUser·p0.95:   8.520 ms/op
                 createUser·p0.99:   12.501 ms/op
                 createUser·p0.999:  28.342 ms/op
                 createUser·p0.9999: 36.897 ms/op
                 createUser·p1.00:   37.290 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 178234
  mean =      5.383 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 34 
    [ 2.500,  5.000) = 85992 
    [ 5.000,  7.500) = 80371 
    [ 7.500, 10.000) = 8258 
    [10.000, 12.500) = 2285 
    [12.500, 15.000) = 700 
    [15.000, 17.500) = 180 
    [17.500, 20.000) = 109 
    [20.000, 22.500) = 38 
    [22.500, 25.000) = 72 
    [25.000, 27.500) = 78 
    [27.500, 30.000) = 50 
    [30.000, 32.500) = 54 
    [32.500, 35.000) = 5 
    [35.000, 37.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      2.179 ms/op
     p(50.0000) =      5.030 ms/op
     p(90.0000) =      6.734 ms/op
     p(95.0000) =      8.047 ms/op
     p(99.0000) =     11.682 ms/op
     p(99.9000) =     25.740 ms/op
     p(99.9900) =     31.982 ms/op
     p(99.9990) =     37.136 ms/op
     p(99.9999) =     37.290 ms/op
    p(100.0000) =     37.290 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 15.289 ±(99.9%) 0.233 ms/op
# Warmup Iteration   2: 5.699 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 5.123 ±(99.9%) 0.019 ms/op
Iteration   1: 5.115 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   2.154 ms/op
                 existUser·p0.50:   4.760 ms/op
                 existUser·p0.90:   6.513 ms/op
                 existUser·p0.95:   7.856 ms/op
                 existUser·p0.99:   10.617 ms/op
                 existUser·p0.999:  22.591 ms/op
                 existUser·p0.9999: 27.099 ms/op
                 existUser·p1.00:   27.820 ms/op

Iteration   2: 5.035 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   2.339 ms/op
                 existUser·p0.50:   4.743 ms/op
                 existUser·p0.90:   6.275 ms/op
                 existUser·p0.95:   7.242 ms/op
                 existUser·p0.99:   9.662 ms/op
                 existUser·p0.999:  22.708 ms/op
                 existUser·p0.9999: 44.846 ms/op
                 existUser·p1.00:   45.679 ms/op

Iteration   3: 5.200 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   1.350 ms/op
                 existUser·p0.50:   4.817 ms/op
                 existUser·p0.90:   6.652 ms/op
                 existUser·p0.95:   7.815 ms/op
                 existUser·p0.99:   11.389 ms/op
                 existUser·p0.999:  25.970 ms/op
                 existUser·p0.9999: 34.807 ms/op
                 existUser·p1.00:   35.717 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 187588
  mean =      5.116 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 118412 
    [ 5.000, 10.000) = 66736 
    [10.000, 15.000) = 2085 
    [15.000, 20.000) = 121 
    [20.000, 25.000) = 94 
    [25.000, 30.000) = 76 
    [30.000, 35.000) = 27 
    [35.000, 40.000) = 5 
    [40.000, 45.000) = 29 

  Percentiles, ms/op:
      p(0.0000) =      1.350 ms/op
     p(50.0000) =      4.768 ms/op
     p(90.0000) =      6.463 ms/op
     p(95.0000) =      7.635 ms/op
     p(99.0000) =     10.650 ms/op
     p(99.9000) =     22.643 ms/op
     p(99.9900) =     43.532 ms/op
     p(99.9990) =     45.105 ms/op
     p(99.9999) =     45.679 ms/op
    p(100.0000) =     45.679 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 16.487 ±(99.9%) 0.288 ms/op
# Warmup Iteration   2: 6.195 ±(99.9%) 0.035 ms/op
# Warmup Iteration   3: 5.475 ±(99.9%) 0.020 ms/op
Iteration   1: 5.609 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   2.150 ms/op
                 getUser·p0.50:   5.202 ms/op
                 getUser·p0.90:   7.021 ms/op
                 getUser·p0.95:   8.471 ms/op
                 getUser·p0.99:   11.478 ms/op
                 getUser·p0.999:  26.672 ms/op
                 getUser·p0.9999: 33.074 ms/op
                 getUser·p1.00:   34.210 ms/op

Iteration   2: 5.435 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   2.445 ms/op
                 getUser·p0.50:   5.104 ms/op
                 getUser·p0.90:   6.545 ms/op
                 getUser·p0.95:   7.791 ms/op
                 getUser·p0.99:   11.289 ms/op
                 getUser·p0.999:  25.445 ms/op
                 getUser·p0.9999: 28.899 ms/op
                 getUser·p1.00:   30.573 ms/op

Iteration   3: 5.527 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   2.085 ms/op
                 getUser·p0.50:   5.251 ms/op
                 getUser·p0.90:   6.787 ms/op
                 getUser·p0.95:   7.823 ms/op
                 getUser·p0.99:   9.798 ms/op
                 getUser·p0.999:  24.314 ms/op
                 getUser·p0.9999: 29.658 ms/op
                 getUser·p1.00:   30.474 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 173661
  mean =      5.522 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7 
    [ 2.500,  5.000) = 66728 
    [ 5.000,  7.500) = 95514 
    [ 7.500, 10.000) = 8787 
    [10.000, 12.500) = 1814 
    [12.500, 15.000) = 340 
    [15.000, 17.500) = 134 
    [17.500, 20.000) = 74 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 96 
    [27.500, 30.000) = 82 
    [30.000, 32.500) = 19 
    [32.500, 35.000) = 7 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.085 ms/op
     p(50.0000) =      5.186 ms/op
     p(90.0000) =      6.775 ms/op
     p(95.0000) =      7.995 ms/op
     p(99.0000) =     10.797 ms/op
     p(99.9000) =     25.767 ms/op
     p(99.9900) =     30.573 ms/op
     p(99.9990) =     34.065 ms/op
     p(99.9999) =     34.210 ms/op
    p(100.0000) =     34.210 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 19.827 ±(99.9%) 0.361 ms/op
# Warmup Iteration   2: 7.827 ±(99.9%) 0.059 ms/op
# Warmup Iteration   3: 6.462 ±(99.9%) 0.029 ms/op
Iteration   1: 6.502 ±(99.9%) 0.031 ms/op
                 listUser·p0.00:   2.343 ms/op
                 listUser·p0.50:   5.931 ms/op
                 listUser·p0.90:   8.716 ms/op
                 listUser·p0.95:   10.289 ms/op
                 listUser·p0.99:   14.221 ms/op
                 listUser·p0.999:  27.616 ms/op
                 listUser·p0.9999: 37.028 ms/op
                 listUser·p1.00:   39.387 ms/op

Iteration   2: 6.942 ±(99.9%) 0.034 ms/op
                 listUser·p0.00:   1.835 ms/op
                 listUser·p0.50:   6.250 ms/op
                 listUser·p0.90:   9.650 ms/op
                 listUser·p0.95:   10.863 ms/op
                 listUser·p0.99:   14.683 ms/op
                 listUser·p0.999:  31.086 ms/op
                 listUser·p0.9999: 37.116 ms/op
                 listUser·p1.00:   38.339 ms/op

Iteration   3: 7.005 ±(99.9%) 0.033 ms/op
                 listUser·p0.00:   3.072 ms/op
                 listUser·p0.50:   6.373 ms/op
                 listUser·p0.90:   9.454 ms/op
                 listUser·p0.95:   11.207 ms/op
                 listUser·p0.99:   15.172 ms/op
                 listUser·p0.999:  26.128 ms/op
                 listUser·p0.9999: 32.844 ms/op
                 listUser·p1.00:   33.292 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 140919
  mean =      6.808 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2 
    [ 2.500,  5.000) = 7145 
    [ 5.000,  7.500) = 104692 
    [ 7.500, 10.000) = 18828 
    [10.000, 12.500) = 6842 
    [12.500, 15.000) = 2093 
    [15.000, 17.500) = 844 
    [17.500, 20.000) = 147 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 50 
    [25.000, 27.500) = 68 
    [27.500, 30.000) = 58 
    [30.000, 32.500) = 57 
    [32.500, 35.000) = 28 
    [35.000, 37.500) = 35 

  Percentiles, ms/op:
      p(0.0000) =      1.835 ms/op
     p(50.0000) =      6.177 ms/op
     p(90.0000) =      9.290 ms/op
     p(95.0000) =     10.764 ms/op
     p(99.0000) =     14.811 ms/op
     p(99.9000) =     29.426 ms/op
     p(99.9900) =     36.760 ms/op
     p(99.9990) =     38.958 ms/op
     p(99.9999) =     39.387 ms/op
    p(100.0000) =     39.387 ms/op


# Run complete. Total time: 00:13:19

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.671 ± 1.405  ops/ms
ClientPb.existUser                       thrpt       3   6.339 ± 1.825  ops/ms
ClientPb.getUser                         thrpt       3   6.000 ± 0.722  ops/ms
ClientPb.listUser                        thrpt       3   4.957 ± 2.602  ops/ms
ClientPb.createUser                       avgt       3   5.433 ± 2.086   ms/op
ClientPb.existUser                        avgt       3   5.230 ± 3.174   ms/op
ClientPb.getUser                          avgt       3   5.488 ± 1.974   ms/op
ClientPb.listUser                         avgt       3   6.261 ± 4.558   ms/op
ClientPb.createUser                     sample  178234   5.383 ± 0.013   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.179           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.030           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.734           ms/op
ClientPb.createUser:createUser·p0.95    sample           8.047           ms/op
ClientPb.createUser:createUser·p0.99    sample          11.682           ms/op
ClientPb.createUser:createUser·p0.999   sample          25.740           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.982           ms/op
ClientPb.createUser:createUser·p1.00    sample          37.290           ms/op
ClientPb.existUser                      sample  187588   5.116 ± 0.012   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.350           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.768           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.463           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.635           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.650           ms/op
ClientPb.existUser:existUser·p0.999     sample          22.643           ms/op
ClientPb.existUser:existUser·p0.9999    sample          43.532           ms/op
ClientPb.existUser:existUser·p1.00      sample          45.679           ms/op
ClientPb.getUser                        sample  173661   5.522 ± 0.012   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.085           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.186           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.775           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.995           ms/op
ClientPb.getUser:getUser·p0.99          sample          10.797           ms/op
ClientPb.getUser:getUser·p0.999         sample          25.767           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.573           ms/op
ClientPb.getUser:getUser·p1.00          sample          34.210           ms/op
ClientPb.listUser                       sample  140919   6.808 ± 0.019   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.835           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.177           ms/op
ClientPb.listUser:listUser·p0.90        sample           9.290           ms/op
ClientPb.listUser:listUser·p0.95        sample          10.764           ms/op
ClientPb.listUser:listUser·p0.99        sample          14.811           ms/op
ClientPb.listUser:listUser·p0.999       sample          29.426           ms/op
ClientPb.listUser:listUser·p0.9999      sample          36.760           ms/op
ClientPb.listUser:listUser·p1.00        sample          39.387           ms/op
