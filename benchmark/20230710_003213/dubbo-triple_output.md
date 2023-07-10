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
# Warmup Iteration   1: 2.571 ops/ms
# Warmup Iteration   2: 6.641 ops/ms
# Warmup Iteration   3: 9.238 ops/ms
Iteration   1: 9.882 ops/ms
Iteration   2: 9.629 ops/ms
Iteration   3: 9.569 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.693 ±(99.9%) 3.028 ops/ms [Average]
  (min, avg, max) = (9.569, 9.693, 9.882), stdev = 0.166
  CI (99.9%): [6.665, 12.722] (assumes normal distribution)


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
# Warmup Iteration   1: 3.227 ops/ms
# Warmup Iteration   2: 9.371 ops/ms
# Warmup Iteration   3: 10.630 ops/ms
Iteration   1: 10.316 ops/ms
Iteration   2: 10.601 ops/ms
Iteration   3: 10.480 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.466 ±(99.9%) 2.607 ops/ms [Average]
  (min, avg, max) = (10.316, 10.466, 10.601), stdev = 0.143
  CI (99.9%): [7.858, 13.073] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.550 ops/ms
# Warmup Iteration   2: 8.938 ops/ms
# Warmup Iteration   3: 9.838 ops/ms
Iteration   1: 10.160 ops/ms
Iteration   2: 9.988 ops/ms
Iteration   3: 9.797 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.982 ±(99.9%) 3.310 ops/ms [Average]
  (min, avg, max) = (9.797, 9.982, 10.160), stdev = 0.181
  CI (99.9%): [6.671, 13.292] (assumes normal distribution)


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
# Warmup Iteration   1: 3.312 ops/ms
# Warmup Iteration   2: 7.720 ops/ms
# Warmup Iteration   3: 8.506 ops/ms
Iteration   1: 8.511 ops/ms
Iteration   2: 8.817 ops/ms
Iteration   3: 8.717 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.681 ±(99.9%) 2.850 ops/ms [Average]
  (min, avg, max) = (8.511, 8.681, 8.817), stdev = 0.156
  CI (99.9%): [5.831, 11.532] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 8.564 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.670 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.471 ±(99.9%) 0.007 ms/op
Iteration   1: 3.275 ±(99.9%) 0.008 ms/op
Iteration   2: 3.197 ±(99.9%) 0.007 ms/op
Iteration   3: 3.118 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.197 ±(99.9%) 1.431 ms/op [Average]
  (min, avg, max) = (3.118, 3.197, 3.275), stdev = 0.078
  CI (99.9%): [1.766, 4.627] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 6.528 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.445 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.134 ±(99.9%) 0.008 ms/op
Iteration   1: 3.061 ±(99.9%) 0.002 ms/op
Iteration   2: 2.980 ±(99.9%) 0.002 ms/op
Iteration   3: 3.070 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.037 ±(99.9%) 0.902 ms/op [Average]
  (min, avg, max) = (2.980, 3.037, 3.070), stdev = 0.049
  CI (99.9%): [2.135, 3.939] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 6.730 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.384 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.197 ±(99.9%) 0.003 ms/op
Iteration   1: 3.219 ±(99.9%) 0.006 ms/op
Iteration   2: 3.236 ±(99.9%) 0.003 ms/op
Iteration   3: 3.183 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.213 ±(99.9%) 0.496 ms/op [Average]
  (min, avg, max) = (3.183, 3.213, 3.236), stdev = 0.027
  CI (99.9%): [2.717, 3.709] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 7.638 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.057 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.745 ±(99.9%) 0.003 ms/op
Iteration   1: 3.830 ±(99.9%) 0.007 ms/op
Iteration   2: 3.736 ±(99.9%) 0.007 ms/op
Iteration   3: 3.646 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.738 ±(99.9%) 1.681 ms/op [Average]
  (min, avg, max) = (3.646, 3.738, 3.830), stdev = 0.092
  CI (99.9%): [2.057, 5.419] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 7.537 ±(99.9%) 0.086 ms/op
# Warmup Iteration   2: 3.678 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.264 ±(99.9%) 0.009 ms/op
Iteration   1: 3.212 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.384 ms/op
                 createUser·p0.50:   3.191 ms/op
                 createUser·p0.90:   3.355 ms/op
                 createUser·p0.95:   3.846 ms/op
                 createUser·p0.99:   5.554 ms/op
                 createUser·p0.999:  15.903 ms/op
                 createUser·p0.9999: 23.038 ms/op
                 createUser·p1.00:   23.953 ms/op

Iteration   2: 3.303 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.842 ms/op
                 createUser·p0.50:   3.236 ms/op
                 createUser·p0.90:   3.744 ms/op
                 createUser·p0.95:   4.116 ms/op
                 createUser·p0.99:   5.726 ms/op
                 createUser·p0.999:  17.066 ms/op
                 createUser·p0.9999: 23.013 ms/op
                 createUser·p1.00:   23.658 ms/op

Iteration   3: 3.219 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.288 ms/op
                 createUser·p0.50:   3.052 ms/op
                 createUser·p0.90:   3.604 ms/op
                 createUser·p0.95:   4.055 ms/op
                 createUser·p0.99:   5.407 ms/op
                 createUser·p0.999:  17.700 ms/op
                 createUser·p0.9999: 28.120 ms/op
                 createUser·p1.00:   29.655 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 295670
  mean =      3.244 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22488 
    [ 2.500,  5.000) = 266360 
    [ 5.000,  7.500) = 5943 
    [ 7.500, 10.000) = 416 
    [10.000, 12.500) = 46 
    [12.500, 15.000) = 30 
    [15.000, 17.500) = 95 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 160 
    [22.500, 25.000) = 59 
    [25.000, 27.500) = 19 

  Percentiles, ms/op:
      p(0.0000) =      0.842 ms/op
     p(50.0000) =      3.187 ms/op
     p(90.0000) =      3.613 ms/op
     p(95.0000) =      4.039 ms/op
     p(99.0000) =      5.571 ms/op
     p(99.9000) =     17.170 ms/op
     p(99.9900) =     26.075 ms/op
     p(99.9990) =     29.182 ms/op
     p(99.9999) =     29.655 ms/op
    p(100.0000) =     29.655 ms/op


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
# Warmup Iteration   1: 8.223 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 3.423 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.158 ±(99.9%) 0.008 ms/op
Iteration   1: 3.092 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.913 ms/op
                 existUser·p0.50:   2.982 ms/op
                 existUser·p0.90:   3.330 ms/op
                 existUser·p0.95:   3.641 ms/op
                 existUser·p0.99:   5.603 ms/op
                 existUser·p0.999:  9.486 ms/op
                 existUser·p0.9999: 20.251 ms/op
                 existUser·p1.00:   21.791 ms/op

Iteration   2: 3.092 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.192 ms/op
                 existUser·p0.50:   2.996 ms/op
                 existUser·p0.90:   3.334 ms/op
                 existUser·p0.95:   3.645 ms/op
                 existUser·p0.99:   5.038 ms/op
                 existUser·p0.999:  13.311 ms/op
                 existUser·p0.9999: 30.287 ms/op
                 existUser·p1.00:   31.359 ms/op

Iteration   3: 3.169 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.857 ms/op
                 existUser·p0.50:   3.178 ms/op
                 existUser·p0.90:   3.310 ms/op
                 existUser·p0.95:   3.539 ms/op
                 existUser·p0.99:   5.382 ms/op
                 existUser·p0.999:  9.142 ms/op
                 existUser·p0.9999: 19.857 ms/op
                 existUser·p1.00:   21.463 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 308177
  mean =      3.117 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21114 
    [ 2.500,  5.000) = 280847 
    [ 5.000,  7.500) = 5426 
    [ 7.500, 10.000) = 400 
    [10.000, 12.500) = 85 
    [12.500, 15.000) = 44 
    [15.000, 17.500) = 51 
    [17.500, 20.000) = 99 
    [20.000, 22.500) = 69 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 1 
    [27.500, 30.000) = 10 
    [30.000, 32.500) = 19 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.857 ms/op
     p(50.0000) =      3.076 ms/op
     p(90.0000) =      3.322 ms/op
     p(95.0000) =      3.625 ms/op
     p(99.0000) =      5.399 ms/op
     p(99.9000) =     12.032 ms/op
     p(99.9900) =     24.895 ms/op
     p(99.9990) =     31.190 ms/op
     p(99.9999) =     31.359 ms/op
    p(100.0000) =     31.359 ms/op


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
# Warmup Iteration   1: 9.200 ±(99.9%) 0.097 ms/op
# Warmup Iteration   2: 3.558 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.324 ±(99.9%) 0.010 ms/op
Iteration   1: 3.154 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.317 ms/op
                 getUser·p0.50:   3.125 ms/op
                 getUser·p0.90:   3.559 ms/op
                 getUser·p0.95:   3.965 ms/op
                 getUser·p0.99:   5.226 ms/op
                 getUser·p0.999:  14.411 ms/op
                 getUser·p0.9999: 23.331 ms/op
                 getUser·p1.00:   24.084 ms/op

Iteration   2: 3.176 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.425 ms/op
                 getUser·p0.50:   3.060 ms/op
                 getUser·p0.90:   3.453 ms/op
                 getUser·p0.95:   3.891 ms/op
                 getUser·p0.99:   5.825 ms/op
                 getUser·p0.999:  12.440 ms/op
                 getUser·p0.9999: 23.527 ms/op
                 getUser·p1.00:   26.051 ms/op

Iteration   3: 3.125 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.450 ms/op
                 getUser·p0.50:   3.027 ms/op
                 getUser·p0.90:   3.408 ms/op
                 getUser·p0.95:   3.666 ms/op
                 getUser·p0.99:   5.587 ms/op
                 getUser·p0.999:  9.646 ms/op
                 getUser·p0.9999: 21.259 ms/op
                 getUser·p1.00:   21.955 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 304539
  mean =      3.151 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18038 
    [ 2.500,  5.000) = 280956 
    [ 5.000,  7.500) = 4630 
    [ 7.500, 10.000) = 521 
    [10.000, 12.500) = 71 
    [12.500, 15.000) = 34 
    [15.000, 17.500) = 42 
    [17.500, 20.000) = 76 
    [20.000, 22.500) = 120 
    [22.500, 25.000) = 48 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.317 ms/op
     p(50.0000) =      3.076 ms/op
     p(90.0000) =      3.469 ms/op
     p(95.0000) =      3.850 ms/op
     p(99.0000) =      5.562 ms/op
     p(99.9000) =     14.260 ms/op
     p(99.9900) =     23.167 ms/op
     p(99.9990) =     25.899 ms/op
     p(99.9999) =     26.051 ms/op
    p(100.0000) =     26.051 ms/op


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
# Warmup Iteration   1: 8.998 ±(99.9%) 0.106 ms/op
# Warmup Iteration   2: 4.052 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.801 ±(99.9%) 0.012 ms/op
Iteration   1: 3.768 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.098 ms/op
                 listUser·p0.50:   3.604 ms/op
                 listUser·p0.90:   4.141 ms/op
                 listUser·p0.95:   4.415 ms/op
                 listUser·p0.99:   7.643 ms/op
                 listUser·p0.999:  14.549 ms/op
                 listUser·p0.9999: 24.576 ms/op
                 listUser·p1.00:   26.182 ms/op

Iteration   2: 3.713 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.081 ms/op
                 listUser·p0.50:   3.568 ms/op
                 listUser·p0.90:   4.043 ms/op
                 listUser·p0.95:   4.235 ms/op
                 listUser·p0.99:   7.315 ms/op
                 listUser·p0.999:  13.566 ms/op
                 listUser·p0.9999: 15.712 ms/op
                 listUser·p1.00:   16.040 ms/op

Iteration   3: 3.687 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.134 ms/op
                 listUser·p0.50:   3.564 ms/op
                 listUser·p0.90:   3.957 ms/op
                 listUser·p0.95:   4.219 ms/op
                 listUser·p0.99:   6.627 ms/op
                 listUser·p0.999:  13.173 ms/op
                 listUser·p0.9999: 14.728 ms/op
                 listUser·p1.00:   16.105 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 257869
  mean =      3.722 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 91 
    [ 2.500,  5.000) = 250113 
    [ 5.000,  7.500) = 5394 
    [ 7.500, 10.000) = 1532 
    [10.000, 12.500) = 213 
    [12.500, 15.000) = 424 
    [15.000, 17.500) = 63 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      1.098 ms/op
     p(50.0000) =      3.580 ms/op
     p(90.0000) =      4.051 ms/op
     p(95.0000) =      4.301 ms/op
     p(99.0000) =      7.242 ms/op
     p(99.9000) =     13.697 ms/op
     p(99.9900) =     23.167 ms/op
     p(99.9990) =     25.882 ms/op
     p(99.9999) =     26.182 ms/op
    p(100.0000) =     26.182 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.693 ± 3.028  ops/ms
ClientPb.existUser                       thrpt       3  10.466 ± 2.607  ops/ms
ClientPb.getUser                         thrpt       3   9.982 ± 3.310  ops/ms
ClientPb.listUser                        thrpt       3   8.681 ± 2.850  ops/ms
ClientPb.createUser                       avgt       3   3.197 ± 1.431   ms/op
ClientPb.existUser                        avgt       3   3.037 ± 0.902   ms/op
ClientPb.getUser                          avgt       3   3.213 ± 0.496   ms/op
ClientPb.listUser                         avgt       3   3.738 ± 1.681   ms/op
ClientPb.createUser                     sample  295670   3.244 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.842           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.187           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.613           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.039           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.571           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.170           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.075           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.655           ms/op
ClientPb.existUser                      sample  308177   3.117 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.857           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.076           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.322           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.625           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.399           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.032           ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.895           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.359           ms/op
ClientPb.getUser                        sample  304539   3.151 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.317           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.076           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.469           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.850           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.562           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.260           ms/op
ClientPb.getUser:getUser·p0.9999        sample          23.167           ms/op
ClientPb.getUser:getUser·p1.00          sample          26.051           ms/op
ClientPb.listUser                       sample  257869   3.722 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.098           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.580           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.051           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.301           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.242           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.697           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.167           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.182           ms/op
