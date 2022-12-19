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
# Warmup Iteration   1: 1.065 ops/ms
# Warmup Iteration   2: 2.457 ops/ms
# Warmup Iteration   3: 5.060 ops/ms
Iteration   1: 5.425 ops/ms
Iteration   2: 5.744 ops/ms
Iteration   3: 5.711 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.627 ±(99.9%) 3.194 ops/ms [Average]
  (min, avg, max) = (5.425, 5.627, 5.744), stdev = 0.175
  CI (99.9%): [2.433, 8.821] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 1.475 ops/ms
# Warmup Iteration   2: 5.072 ops/ms
# Warmup Iteration   3: 5.891 ops/ms
Iteration   1: 6.103 ops/ms
Iteration   2: 5.992 ops/ms
Iteration   3: 5.982 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.026 ±(99.9%) 1.226 ops/ms [Average]
  (min, avg, max) = (5.982, 6.026, 6.103), stdev = 0.067
  CI (99.9%): [4.800, 7.252] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.568 ops/ms
# Warmup Iteration   2: 4.606 ops/ms
# Warmup Iteration   3: 5.541 ops/ms
Iteration   1: 5.622 ops/ms
Iteration   2: 5.442 ops/ms
Iteration   3: 5.741 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.602 ±(99.9%) 2.753 ops/ms [Average]
  (min, avg, max) = (5.442, 5.602, 5.741), stdev = 0.151
  CI (99.9%): [2.849, 8.355] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 1.478 ops/ms
# Warmup Iteration   2: 3.936 ops/ms
# Warmup Iteration   3: 4.655 ops/ms
Iteration   1: 4.699 ops/ms
Iteration   2: 4.775 ops/ms
Iteration   3: 4.807 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.760 ±(99.9%) 1.018 ops/ms [Average]
  (min, avg, max) = (4.699, 4.760, 4.807), stdev = 0.056
  CI (99.9%): [3.742, 5.778] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 17.208 ±(99.9%) 0.075 ms/op
# Warmup Iteration   2: 7.261 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 6.025 ±(99.9%) 0.013 ms/op
Iteration   1: 5.681 ±(99.9%) 0.007 ms/op
Iteration   2: 5.687 ±(99.9%) 0.017 ms/op
Iteration   3: 5.527 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.632 ±(99.9%) 1.656 ms/op [Average]
  (min, avg, max) = (5.527, 5.632, 5.687), stdev = 0.091
  CI (99.9%): [3.976, 7.288] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 19.530 ±(99.9%) 0.081 ms/op
# Warmup Iteration   2: 6.829 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 5.514 ±(99.9%) 0.009 ms/op
Iteration   1: 5.559 ±(99.9%) 0.008 ms/op
Iteration   2: 5.493 ±(99.9%) 0.010 ms/op
Iteration   3: 5.362 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.471 ±(99.9%) 1.835 ms/op [Average]
  (min, avg, max) = (5.362, 5.471, 5.559), stdev = 0.101
  CI (99.9%): [3.637, 7.306] (assumes normal distribution)


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
# Warmup Iteration   1: 18.547 ±(99.9%) 0.119 ms/op
# Warmup Iteration   2: 7.139 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 5.707 ±(99.9%) 0.010 ms/op
Iteration   1: 5.466 ±(99.9%) 0.010 ms/op
Iteration   2: 5.970 ±(99.9%) 0.006 ms/op
Iteration   3: 5.473 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.636 ±(99.9%) 5.273 ms/op [Average]
  (min, avg, max) = (5.466, 5.636, 5.970), stdev = 0.289
  CI (99.9%): [0.363, 10.909] (assumes normal distribution)


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
# Warmup Iteration   1: 19.081 ±(99.9%) 0.108 ms/op
# Warmup Iteration   2: 8.230 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 6.711 ±(99.9%) 0.015 ms/op
Iteration   1: 6.675 ±(99.9%) 0.014 ms/op
Iteration   2: 6.695 ±(99.9%) 0.013 ms/op
Iteration   3: 6.803 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.724 ±(99.9%) 1.257 ms/op [Average]
  (min, avg, max) = (6.675, 6.724, 6.803), stdev = 0.069
  CI (99.9%): [5.467, 7.982] (assumes normal distribution)


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
# Warmup Iteration   1: 20.459 ±(99.9%) 0.316 ms/op
# Warmup Iteration   2: 7.907 ±(99.9%) 0.063 ms/op
# Warmup Iteration   3: 6.739 ±(99.9%) 0.036 ms/op
Iteration   1: 5.807 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   1.915 ms/op
                 createUser·p0.50:   5.513 ms/op
                 createUser·p0.90:   7.012 ms/op
                 createUser·p0.95:   8.339 ms/op
                 createUser·p0.99:   11.321 ms/op
                 createUser·p0.999:  24.478 ms/op
                 createUser·p0.9999: 27.672 ms/op
                 createUser·p1.00:   27.886 ms/op

Iteration   2: 5.662 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   2.220 ms/op
                 createUser·p0.50:   5.317 ms/op
                 createUser·p0.90:   6.857 ms/op
                 createUser·p0.95:   8.126 ms/op
                 createUser·p0.99:   11.469 ms/op
                 createUser·p0.999:  27.935 ms/op
                 createUser·p0.9999: 32.575 ms/op
                 createUser·p1.00:   33.620 ms/op

Iteration   3: 5.575 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   2.507 ms/op
                 createUser·p0.50:   5.267 ms/op
                 createUser·p0.90:   6.660 ms/op
                 createUser·p0.95:   7.499 ms/op
                 createUser·p0.99:   11.125 ms/op
                 createUser·p0.999:  26.933 ms/op
                 createUser·p0.9999: 30.310 ms/op
                 createUser·p1.00:   30.704 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 168884
  mean =      5.680 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17 
    [ 2.500,  5.000) = 46604 
    [ 5.000,  7.500) = 111762 
    [ 7.500, 10.000) = 7380 
    [10.000, 12.500) = 2035 
    [12.500, 15.000) = 654 
    [15.000, 17.500) = 163 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 56 
    [27.500, 30.000) = 88 
    [30.000, 32.500) = 30 
    [32.500, 35.000) = 6 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.915 ms/op
     p(50.0000) =      5.358 ms/op
     p(90.0000) =      6.849 ms/op
     p(95.0000) =      8.004 ms/op
     p(99.0000) =     11.338 ms/op
     p(99.9000) =     25.625 ms/op
     p(99.9900) =     31.537 ms/op
     p(99.9990) =     33.575 ms/op
     p(99.9999) =     33.620 ms/op
    p(100.0000) =     33.620 ms/op


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
# Warmup Iteration   1: 18.366 ±(99.9%) 0.296 ms/op
# Warmup Iteration   2: 6.208 ±(99.9%) 0.033 ms/op
# Warmup Iteration   3: 5.589 ±(99.9%) 0.020 ms/op
Iteration   1: 5.518 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   2.331 ms/op
                 existUser·p0.50:   5.169 ms/op
                 existUser·p0.90:   6.832 ms/op
                 existUser·p0.95:   8.094 ms/op
                 existUser·p0.99:   10.940 ms/op
                 existUser·p0.999:  17.924 ms/op
                 existUser·p0.9999: 26.417 ms/op
                 existUser·p1.00:   27.558 ms/op

Iteration   2: 5.416 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   0.811 ms/op
                 existUser·p0.50:   5.161 ms/op
                 existUser·p0.90:   6.463 ms/op
                 existUser·p0.95:   7.367 ms/op
                 existUser·p0.99:   10.994 ms/op
                 existUser·p0.999:  27.227 ms/op
                 existUser·p0.9999: 34.954 ms/op
                 existUser·p1.00:   38.797 ms/op

Iteration   3: 5.396 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   2.335 ms/op
                 existUser·p0.50:   5.177 ms/op
                 existUser·p0.90:   6.398 ms/op
                 existUser·p0.95:   7.029 ms/op
                 existUser·p0.99:   9.649 ms/op
                 existUser·p0.999:  27.976 ms/op
                 existUser·p0.9999: 36.504 ms/op
                 existUser·p1.00:   37.618 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 176445
  mean =      5.443 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23 
    [ 2.500,  5.000) = 67606 
    [ 5.000,  7.500) = 100092 
    [ 7.500, 10.000) = 6349 
    [10.000, 12.500) = 1556 
    [12.500, 15.000) = 459 
    [15.000, 17.500) = 144 
    [17.500, 20.000) = 37 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 30 
    [27.500, 30.000) = 36 
    [30.000, 32.500) = 39 
    [32.500, 35.000) = 24 
    [35.000, 37.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      0.811 ms/op
     p(50.0000) =      5.169 ms/op
     p(90.0000) =      6.537 ms/op
     p(95.0000) =      7.479 ms/op
     p(99.0000) =     10.568 ms/op
     p(99.9000) =     20.436 ms/op
     p(99.9900) =     34.804 ms/op
     p(99.9990) =     38.647 ms/op
     p(99.9999) =     38.797 ms/op
    p(100.0000) =     38.797 ms/op


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
# Warmup Iteration   1: 19.179 ±(99.9%) 0.332 ms/op
# Warmup Iteration   2: 7.130 ±(99.9%) 0.049 ms/op
# Warmup Iteration   3: 5.779 ±(99.9%) 0.021 ms/op
Iteration   1: 5.827 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   2.392 ms/op
                 getUser·p0.50:   5.382 ms/op
                 getUser·p0.90:   7.304 ms/op
                 getUser·p0.95:   9.437 ms/op
                 getUser·p0.99:   12.534 ms/op
                 getUser·p0.999:  17.051 ms/op
                 getUser·p0.9999: 28.148 ms/op
                 getUser·p1.00:   28.901 ms/op

Iteration   2: 5.818 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   2.388 ms/op
                 getUser·p0.50:   5.456 ms/op
                 getUser·p0.90:   7.225 ms/op
                 getUser·p0.95:   8.602 ms/op
                 getUser·p0.99:   12.131 ms/op
                 getUser·p0.999:  28.452 ms/op
                 getUser·p0.9999: 32.047 ms/op
                 getUser·p1.00:   32.506 ms/op

Iteration   3: 5.502 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   1.542 ms/op
                 getUser·p0.50:   5.210 ms/op
                 getUser·p0.90:   6.693 ms/op
                 getUser·p0.95:   7.725 ms/op
                 getUser·p0.99:   10.355 ms/op
                 getUser·p0.999:  26.798 ms/op
                 getUser·p0.9999: 29.563 ms/op
                 getUser·p1.00:   31.064 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 167984
  mean =      5.711 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5 
    [ 2.500,  5.000) = 45693 
    [ 5.000,  7.500) = 109312 
    [ 7.500, 10.000) = 8917 
    [10.000, 12.500) = 2840 
    [12.500, 15.000) = 736 
    [15.000, 17.500) = 207 
    [17.500, 20.000) = 67 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 67 
    [27.500, 30.000) = 104 
    [30.000, 32.500) = 23 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.542 ms/op
     p(50.0000) =      5.341 ms/op
     p(90.0000) =      7.070 ms/op
     p(95.0000) =      8.454 ms/op
     p(99.0000) =     11.567 ms/op
     p(99.9000) =     26.445 ms/op
     p(99.9900) =     30.468 ms/op
     p(99.9990) =     32.484 ms/op
     p(99.9999) =     32.506 ms/op
    p(100.0000) =     32.506 ms/op


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
# Warmup Iteration   1: 18.852 ±(99.9%) 0.322 ms/op
# Warmup Iteration   2: 8.861 ±(99.9%) 0.072 ms/op
# Warmup Iteration   3: 7.021 ±(99.9%) 0.033 ms/op
Iteration   1: 7.042 ±(99.9%) 0.031 ms/op
                 listUser·p0.00:   2.437 ms/op
                 listUser·p0.50:   6.504 ms/op
                 listUser·p0.90:   9.093 ms/op
                 listUser·p0.95:   10.650 ms/op
                 listUser·p0.99:   14.959 ms/op
                 listUser·p0.999:  28.344 ms/op
                 listUser·p0.9999: 32.460 ms/op
                 listUser·p1.00:   33.620 ms/op

Iteration   2: 6.613 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   3.199 ms/op
                 listUser·p0.50:   6.210 ms/op
                 listUser·p0.90:   7.799 ms/op
                 listUser·p0.95:   9.355 ms/op
                 listUser·p0.99:   13.763 ms/op
                 listUser·p0.999:  27.361 ms/op
                 listUser·p0.9999: 29.764 ms/op
                 listUser·p1.00:   30.114 ms/op

Iteration   3: 6.889 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   2.589 ms/op
                 listUser·p0.50:   6.504 ms/op
                 listUser·p0.90:   8.364 ms/op
                 listUser·p0.95:   9.572 ms/op
                 listUser·p0.99:   13.435 ms/op
                 listUser·p0.999:  24.314 ms/op
                 listUser·p0.9999: 31.874 ms/op
                 listUser·p1.00:   32.735 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 140132
  mean =      6.843 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1 
    [ 2.500,  5.000) = 2824 
    [ 5.000,  7.500) = 112883 
    [ 7.500, 10.000) = 17766 
    [10.000, 12.500) = 4375 
    [12.500, 15.000) = 1145 
    [15.000, 17.500) = 537 
    [17.500, 20.000) = 211 
    [20.000, 22.500) = 98 
    [22.500, 25.000) = 80 
    [25.000, 27.500) = 78 
    [27.500, 30.000) = 89 
    [30.000, 32.500) = 39 
    [32.500, 35.000) = 6 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.437 ms/op
     p(50.0000) =      6.382 ms/op
     p(90.0000) =      8.438 ms/op
     p(95.0000) =      9.880 ms/op
     p(99.0000) =     14.052 ms/op
     p(99.9000) =     27.390 ms/op
     p(99.9900) =     31.653 ms/op
     p(99.9990) =     33.554 ms/op
     p(99.9999) =     33.620 ms/op
    p(100.0000) =     33.620 ms/op


# Run complete. Total time: 00:13:16

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.627 ± 3.194  ops/ms
ClientPb.existUser                       thrpt       3   6.026 ± 1.226  ops/ms
ClientPb.getUser                         thrpt       3   5.602 ± 2.753  ops/ms
ClientPb.listUser                        thrpt       3   4.760 ± 1.018  ops/ms
ClientPb.createUser                       avgt       3   5.632 ± 1.656   ms/op
ClientPb.existUser                        avgt       3   5.471 ± 1.835   ms/op
ClientPb.getUser                          avgt       3   5.636 ± 5.273   ms/op
ClientPb.listUser                         avgt       3   6.724 ± 1.257   ms/op
ClientPb.createUser                     sample  168884   5.680 ± 0.012   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.915           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.358           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.849           ms/op
ClientPb.createUser:createUser·p0.95    sample           8.004           ms/op
ClientPb.createUser:createUser·p0.99    sample          11.338           ms/op
ClientPb.createUser:createUser·p0.999   sample          25.625           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.537           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.620           ms/op
ClientPb.existUser                      sample  176445   5.443 ± 0.011   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.811           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.169           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.537           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.479           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.568           ms/op
ClientPb.existUser:existUser·p0.999     sample          20.436           ms/op
ClientPb.existUser:existUser·p0.9999    sample          34.804           ms/op
ClientPb.existUser:existUser·p1.00      sample          38.797           ms/op
ClientPb.getUser                        sample  167984   5.711 ± 0.013   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.542           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.341           ms/op
ClientPb.getUser:getUser·p0.90          sample           7.070           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.454           ms/op
ClientPb.getUser:getUser·p0.99          sample          11.567           ms/op
ClientPb.getUser:getUser·p0.999         sample          26.445           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.468           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.506           ms/op
ClientPb.listUser                       sample  140132   6.843 ± 0.016   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.437           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.382           ms/op
ClientPb.listUser:listUser·p0.90        sample           8.438           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.880           ms/op
ClientPb.listUser:listUser·p0.99        sample          14.052           ms/op
ClientPb.listUser:listUser·p0.999       sample          27.390           ms/op
ClientPb.listUser:listUser·p0.9999      sample          31.653           ms/op
ClientPb.listUser:listUser·p1.00        sample          33.620           ms/op
