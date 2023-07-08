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
# Warmup Iteration   1: 1.018 ops/ms
# Warmup Iteration   2: 2.408 ops/ms
# Warmup Iteration   3: 5.131 ops/ms
Iteration   1: 5.372 ops/ms
Iteration   2: 5.386 ops/ms
Iteration   3: 5.677 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.479 ±(99.9%) 3.146 ops/ms [Average]
  (min, avg, max) = (5.372, 5.479, 5.677), stdev = 0.172
  CI (99.9%): [2.333, 8.624] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 1.391 ops/ms
# Warmup Iteration   2: 4.386 ops/ms
# Warmup Iteration   3: 5.611 ops/ms
Iteration   1: 5.905 ops/ms
Iteration   2: 5.930 ops/ms
Iteration   3: 5.695 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.843 ±(99.9%) 2.358 ops/ms [Average]
  (min, avg, max) = (5.695, 5.843, 5.930), stdev = 0.129
  CI (99.9%): [3.486, 8.201] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 1.393 ops/ms
# Warmup Iteration   2: 4.164 ops/ms
# Warmup Iteration   3: 5.429 ops/ms
Iteration   1: 5.717 ops/ms
Iteration   2: 5.670 ops/ms
Iteration   3: 5.747 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.711 ±(99.9%) 0.702 ops/ms [Average]
  (min, avg, max) = (5.670, 5.711, 5.747), stdev = 0.038
  CI (99.9%): [5.009, 6.413] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:56
# Fork: 1 of 1
# Warmup Iteration   1: 1.445 ops/ms
# Warmup Iteration   2: 3.871 ops/ms
# Warmup Iteration   3: 4.662 ops/ms
Iteration   1: 4.752 ops/ms
Iteration   2: 4.844 ops/ms
Iteration   3: 4.832 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.809 ±(99.9%) 0.911 ops/ms [Average]
  (min, avg, max) = (4.752, 4.809, 4.844), stdev = 0.050
  CI (99.9%): [3.899, 5.720] (assumes normal distribution)


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
# Warmup Iteration   1: 20.536 ±(99.9%) 0.107 ms/op
# Warmup Iteration   2: 7.458 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 5.814 ±(99.9%) 0.008 ms/op
Iteration   1: 5.927 ±(99.9%) 0.013 ms/op
Iteration   2: 5.793 ±(99.9%) 0.010 ms/op
Iteration   3: 6.134 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.951 ±(99.9%) 3.140 ms/op [Average]
  (min, avg, max) = (5.793, 5.951, 6.134), stdev = 0.172
  CI (99.9%): [2.812, 9.091] (assumes normal distribution)


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
# Warmup Iteration   1: 16.700 ±(99.9%) 0.080 ms/op
# Warmup Iteration   2: 6.667 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 5.885 ±(99.9%) 0.011 ms/op
Iteration   1: 5.723 ±(99.9%) 0.013 ms/op
Iteration   2: 5.593 ±(99.9%) 0.015 ms/op
Iteration   3: 5.639 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.652 ±(99.9%) 1.204 ms/op [Average]
  (min, avg, max) = (5.593, 5.652, 5.723), stdev = 0.066
  CI (99.9%): [4.447, 6.856] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 19.256 ±(99.9%) 0.076 ms/op
# Warmup Iteration   2: 7.173 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 6.069 ±(99.9%) 0.010 ms/op
Iteration   1: 6.011 ±(99.9%) 0.011 ms/op
Iteration   2: 5.849 ±(99.9%) 0.014 ms/op
Iteration   3: 5.796 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.885 ±(99.9%) 2.040 ms/op [Average]
  (min, avg, max) = (5.796, 5.885, 6.011), stdev = 0.112
  CI (99.9%): [3.845, 7.925] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 21.383 ±(99.9%) 0.100 ms/op
# Warmup Iteration   2: 8.736 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 7.087 ±(99.9%) 0.010 ms/op
Iteration   1: 6.675 ±(99.9%) 0.012 ms/op
Iteration   2: 6.577 ±(99.9%) 0.010 ms/op
Iteration   3: 6.568 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.606 ±(99.9%) 1.082 ms/op [Average]
  (min, avg, max) = (6.568, 6.606, 6.675), stdev = 0.059
  CI (99.9%): [5.524, 7.689] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 18.414 ±(99.9%) 0.285 ms/op
# Warmup Iteration   2: 7.353 ±(99.9%) 0.052 ms/op
# Warmup Iteration   3: 6.437 ±(99.9%) 0.034 ms/op
Iteration   1: 5.985 ±(99.9%) 0.028 ms/op
                 createUser·p0.00:   1.331 ms/op
                 createUser·p0.50:   5.472 ms/op
                 createUser·p0.90:   8.135 ms/op
                 createUser·p0.95:   9.437 ms/op
                 createUser·p0.99:   13.484 ms/op
                 createUser·p0.999:  27.837 ms/op
                 createUser·p0.9999: 31.130 ms/op
                 createUser·p1.00:   32.539 ms/op

Iteration   2: 5.918 ±(99.9%) 0.025 ms/op
                 createUser·p0.00:   0.933 ms/op
                 createUser·p0.50:   5.530 ms/op
                 createUser·p0.90:   7.668 ms/op
                 createUser·p0.95:   8.782 ms/op
                 createUser·p0.99:   12.009 ms/op
                 createUser·p0.999:  27.161 ms/op
                 createUser·p0.9999: 36.766 ms/op
                 createUser·p1.00:   37.224 ms/op

Iteration   3: 5.865 ±(99.9%) 0.027 ms/op
                 createUser·p0.00:   2.593 ms/op
                 createUser·p0.50:   5.530 ms/op
                 createUser·p0.90:   7.528 ms/op
                 createUser·p0.95:   8.487 ms/op
                 createUser·p0.99:   11.010 ms/op
                 createUser·p0.999:  35.941 ms/op
                 createUser·p0.9999: 44.928 ms/op
                 createUser·p1.00:   46.662 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 162157
  mean =      5.922 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 46123 
    [ 5.000, 10.000) = 111617 
    [10.000, 15.000) = 3824 
    [15.000, 20.000) = 304 
    [20.000, 25.000) = 55 
    [25.000, 30.000) = 93 
    [30.000, 35.000) = 68 
    [35.000, 40.000) = 41 
    [40.000, 45.000) = 28 

  Percentiles, ms/op:
      p(0.0000) =      0.933 ms/op
     p(50.0000) =      5.513 ms/op
     p(90.0000) =      7.725 ms/op
     p(95.0000) =      8.897 ms/op
     p(99.0000) =     12.190 ms/op
     p(99.9000) =     28.541 ms/op
     p(99.9900) =     43.043 ms/op
     p(99.9990) =     46.458 ms/op
     p(99.9999) =     46.662 ms/op
    p(100.0000) =     46.662 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 16.298 ±(99.9%) 0.234 ms/op
# Warmup Iteration   2: 7.290 ±(99.9%) 0.053 ms/op
# Warmup Iteration   3: 5.637 ±(99.9%) 0.024 ms/op
Iteration   1: 5.527 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   2.515 ms/op
                 existUser·p0.50:   5.136 ms/op
                 existUser·p0.90:   7.242 ms/op
                 existUser·p0.95:   8.585 ms/op
                 existUser·p0.99:   11.534 ms/op
                 existUser·p0.999:  16.843 ms/op
                 existUser·p0.9999: 32.120 ms/op
                 existUser·p1.00:   32.768 ms/op

Iteration   2: 5.428 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   0.465 ms/op
                 existUser·p0.50:   5.120 ms/op
                 existUser·p0.90:   6.914 ms/op
                 existUser·p0.95:   7.881 ms/op
                 existUser·p0.99:   10.093 ms/op
                 existUser·p0.999:  30.575 ms/op
                 existUser·p0.9999: 35.127 ms/op
                 existUser·p1.00:   35.717 ms/op

Iteration   3: 5.607 ±(99.9%) 0.024 ms/op
                 existUser·p0.00:   2.187 ms/op
                 existUser·p0.50:   5.218 ms/op
                 existUser·p0.90:   7.225 ms/op
                 existUser·p0.95:   8.627 ms/op
                 existUser·p0.99:   12.108 ms/op
                 existUser·p0.999:  27.393 ms/op
                 existUser·p0.9999: 30.550 ms/op
                 existUser·p1.00:   31.228 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 173817
  mean =      5.520 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24 
    [ 2.500,  5.000) = 74152 
    [ 5.000,  7.500) = 85862 
    [ 7.500, 10.000) = 10434 
    [10.000, 12.500) = 2371 
    [12.500, 15.000) = 644 
    [15.000, 17.500) = 147 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 12 
    [27.500, 30.000) = 43 
    [30.000, 32.500) = 60 
    [32.500, 35.000) = 39 
    [35.000, 37.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.465 ms/op
     p(50.0000) =      5.161 ms/op
     p(90.0000) =      7.119 ms/op
     p(95.0000) =      8.308 ms/op
     p(99.0000) =     11.236 ms/op
     p(99.9000) =     18.291 ms/op
     p(99.9900) =     34.537 ms/op
     p(99.9990) =     35.524 ms/op
     p(99.9999) =     35.717 ms/op
    p(100.0000) =     35.717 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 18.494 ±(99.9%) 0.369 ms/op
# Warmup Iteration   2: 7.661 ±(99.9%) 0.060 ms/op
# Warmup Iteration   3: 5.716 ±(99.9%) 0.023 ms/op
Iteration   1: 5.584 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   2.097 ms/op
                 getUser·p0.50:   5.202 ms/op
                 getUser·p0.90:   7.225 ms/op
                 getUser·p0.95:   8.372 ms/op
                 getUser·p0.99:   11.321 ms/op
                 getUser·p0.999:  29.317 ms/op
                 getUser·p0.9999: 32.121 ms/op
                 getUser·p1.00:   32.899 ms/op

Iteration   2: 5.745 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   2.437 ms/op
                 getUser·p0.50:   5.333 ms/op
                 getUser·p0.90:   7.569 ms/op
                 getUser·p0.95:   8.880 ms/op
                 getUser·p0.99:   11.829 ms/op
                 getUser·p0.999:  17.334 ms/op
                 getUser·p0.9999: 30.961 ms/op
                 getUser·p1.00:   31.687 ms/op

Iteration   3: 5.896 ±(99.9%) 0.026 ms/op
                 getUser·p0.00:   2.130 ms/op
                 getUser·p0.50:   5.489 ms/op
                 getUser·p0.90:   7.774 ms/op
                 getUser·p0.95:   8.995 ms/op
                 getUser·p0.99:   11.796 ms/op
                 getUser·p0.999:  28.204 ms/op
                 getUser·p0.9999: 34.931 ms/op
                 getUser·p1.00:   37.552 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 167139
  mean =      5.739 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12 
    [ 2.500,  5.000) = 57699 
    [ 5.000,  7.500) = 92489 
    [ 7.500, 10.000) = 12674 
    [10.000, 12.500) = 3095 
    [12.500, 15.000) = 691 
    [15.000, 17.500) = 178 
    [17.500, 20.000) = 97 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 14 
    [27.500, 30.000) = 94 
    [30.000, 32.500) = 62 
    [32.500, 35.000) = 18 
    [35.000, 37.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      2.097 ms/op
     p(50.0000) =      5.333 ms/op
     p(90.0000) =      7.520 ms/op
     p(95.0000) =      8.765 ms/op
     p(99.0000) =     11.682 ms/op
     p(99.9000) =     28.148 ms/op
     p(99.9900) =     32.820 ms/op
     p(99.9990) =     37.420 ms/op
     p(99.9999) =     37.552 ms/op
    p(100.0000) =     37.552 ms/op


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
# Warmup Iteration   1: 20.271 ±(99.9%) 0.376 ms/op
# Warmup Iteration   2: 9.367 ±(99.9%) 0.086 ms/op
# Warmup Iteration   3: 7.078 ±(99.9%) 0.034 ms/op
Iteration   1: 6.835 ±(99.9%) 0.028 ms/op
                 listUser·p0.00:   2.638 ms/op
                 listUser·p0.50:   6.390 ms/op
                 listUser·p0.90:   8.897 ms/op
                 listUser·p0.95:   10.306 ms/op
                 listUser·p0.99:   13.205 ms/op
                 listUser·p0.999:  25.697 ms/op
                 listUser·p0.9999: 30.245 ms/op
                 listUser·p1.00:   30.999 ms/op

Iteration   2: 6.825 ±(99.9%) 0.033 ms/op
                 listUser·p0.00:   2.683 ms/op
                 listUser·p0.50:   6.275 ms/op
                 listUser·p0.90:   8.897 ms/op
                 listUser·p0.95:   10.420 ms/op
                 listUser·p0.99:   14.418 ms/op
                 listUser·p0.999:  33.686 ms/op
                 listUser·p0.9999: 40.587 ms/op
                 listUser·p1.00:   41.550 ms/op

Iteration   3: 6.884 ±(99.9%) 0.030 ms/op
                 listUser·p0.00:   1.419 ms/op
                 listUser·p0.50:   6.414 ms/op
                 listUser·p0.90:   8.897 ms/op
                 listUser·p0.95:   10.224 ms/op
                 listUser·p0.99:   13.976 ms/op
                 listUser·p0.999:  28.198 ms/op
                 listUser·p0.9999: 31.534 ms/op
                 listUser·p1.00:   32.440 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 140105
  mean =      6.848 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 6029 
    [ 5.000, 10.000) = 125996 
    [10.000, 15.000) = 7210 
    [15.000, 20.000) = 527 
    [20.000, 25.000) = 112 
    [25.000, 30.000) = 140 
    [30.000, 35.000) = 68 
    [35.000, 40.000) = 16 
    [40.000, 45.000) = 7 

  Percentiles, ms/op:
      p(0.0000) =      1.419 ms/op
     p(50.0000) =      6.357 ms/op
     p(90.0000) =      8.897 ms/op
     p(95.0000) =     10.306 ms/op
     p(99.0000) =     13.779 ms/op
     p(99.9000) =     28.111 ms/op
     p(99.9900) =     36.241 ms/op
     p(99.9990) =     41.366 ms/op
     p(99.9999) =     41.550 ms/op
    p(100.0000) =     41.550 ms/op


# Run complete. Total time: 00:13:18

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.479 ± 3.146  ops/ms
ClientPb.existUser                       thrpt       3   5.843 ± 2.358  ops/ms
ClientPb.getUser                         thrpt       3   5.711 ± 0.702  ops/ms
ClientPb.listUser                        thrpt       3   4.809 ± 0.911  ops/ms
ClientPb.createUser                       avgt       3   5.951 ± 3.140   ms/op
ClientPb.existUser                        avgt       3   5.652 ± 1.204   ms/op
ClientPb.getUser                          avgt       3   5.885 ± 2.040   ms/op
ClientPb.listUser                         avgt       3   6.606 ± 1.082   ms/op
ClientPb.createUser                     sample  162157   5.922 ± 0.015   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.933           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.513           ms/op
ClientPb.createUser:createUser·p0.90    sample           7.725           ms/op
ClientPb.createUser:createUser·p0.95    sample           8.897           ms/op
ClientPb.createUser:createUser·p0.99    sample          12.190           ms/op
ClientPb.createUser:createUser·p0.999   sample          28.541           ms/op
ClientPb.createUser:createUser·p0.9999  sample          43.043           ms/op
ClientPb.createUser:createUser·p1.00    sample          46.662           ms/op
ClientPb.existUser                      sample  173817   5.520 ± 0.013   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.465           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.161           ms/op
ClientPb.existUser:existUser·p0.90      sample           7.119           ms/op
ClientPb.existUser:existUser·p0.95      sample           8.308           ms/op
ClientPb.existUser:existUser·p0.99      sample          11.236           ms/op
ClientPb.existUser:existUser·p0.999     sample          18.291           ms/op
ClientPb.existUser:existUser·p0.9999    sample          34.537           ms/op
ClientPb.existUser:existUser·p1.00      sample          35.717           ms/op
ClientPb.getUser                        sample  167139   5.739 ± 0.014   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.097           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.333           ms/op
ClientPb.getUser:getUser·p0.90          sample           7.520           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.765           ms/op
ClientPb.getUser:getUser·p0.99          sample          11.682           ms/op
ClientPb.getUser:getUser·p0.999         sample          28.148           ms/op
ClientPb.getUser:getUser·p0.9999        sample          32.820           ms/op
ClientPb.getUser:getUser·p1.00          sample          37.552           ms/op
ClientPb.listUser                       sample  140105   6.848 ± 0.018   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.419           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.357           ms/op
ClientPb.listUser:listUser·p0.90        sample           8.897           ms/op
ClientPb.listUser:listUser·p0.95        sample          10.306           ms/op
ClientPb.listUser:listUser·p0.99        sample          13.779           ms/op
ClientPb.listUser:listUser·p0.999       sample          28.111           ms/op
ClientPb.listUser:listUser·p0.9999      sample          36.241           ms/op
ClientPb.listUser:listUser·p1.00        sample          41.550           ms/op
