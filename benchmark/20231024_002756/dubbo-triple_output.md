# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.957 ops/ms
# Warmup Iteration   2: 5.012 ops/ms
# Warmup Iteration   3: 8.629 ops/ms
Iteration   1: 9.221 ops/ms
Iteration   2: 9.310 ops/ms
Iteration   3: 9.392 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.308 ±(99.9%) 1.558 ops/ms [Average]
  (min, avg, max) = (9.221, 9.308, 9.392), stdev = 0.085
  CI (99.9%): [7.750, 10.865] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:09
# Fork: 1 of 1
# Warmup Iteration   1: 2.868 ops/ms
# Warmup Iteration   2: 8.680 ops/ms
# Warmup Iteration   3: 9.372 ops/ms
Iteration   1: 9.705 ops/ms
Iteration   2: 9.450 ops/ms
Iteration   3: 9.618 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.591 ±(99.9%) 2.367 ops/ms [Average]
  (min, avg, max) = (9.450, 9.591, 9.705), stdev = 0.130
  CI (99.9%): [7.225, 11.958] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 2.868 ops/ms
# Warmup Iteration   2: 8.598 ops/ms
# Warmup Iteration   3: 8.864 ops/ms
Iteration   1: 8.938 ops/ms
Iteration   2: 9.100 ops/ms
Iteration   3: 9.134 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.057 ±(99.9%) 1.908 ops/ms [Average]
  (min, avg, max) = (8.938, 9.057, 9.134), stdev = 0.105
  CI (99.9%): [7.150, 10.965] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 2.321 ops/ms
# Warmup Iteration   2: 6.891 ops/ms
# Warmup Iteration   3: 7.580 ops/ms
Iteration   1: 7.674 ops/ms
Iteration   2: 7.654 ops/ms
Iteration   3: 7.724 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.684 ±(99.9%) 0.651 ops/ms [Average]
  (min, avg, max) = (7.654, 7.684, 7.724), stdev = 0.036
  CI (99.9%): [7.033, 8.335] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 9.549 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 4.014 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.604 ±(99.9%) 0.006 ms/op
Iteration   1: 3.607 ±(99.9%) 0.003 ms/op
Iteration   2: 3.560 ±(99.9%) 0.005 ms/op
Iteration   3: 3.477 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.548 ±(99.9%) 1.200 ms/op [Average]
  (min, avg, max) = (3.477, 3.548, 3.607), stdev = 0.066
  CI (99.9%): [2.349, 4.748] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 8.674 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.503 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.441 ±(99.9%) 0.005 ms/op
Iteration   1: 3.291 ±(99.9%) 0.003 ms/op
Iteration   2: 3.382 ±(99.9%) 0.003 ms/op
Iteration   3: 3.289 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.321 ±(99.9%) 0.961 ms/op [Average]
  (min, avg, max) = (3.289, 3.321, 3.382), stdev = 0.053
  CI (99.9%): [2.360, 4.281] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 11.284 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.777 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.570 ±(99.9%) 0.004 ms/op
Iteration   1: 3.610 ±(99.9%) 0.003 ms/op
Iteration   2: 3.414 ±(99.9%) 0.004 ms/op
Iteration   3: 3.434 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.486 ±(99.9%) 1.967 ms/op [Average]
  (min, avg, max) = (3.414, 3.486, 3.610), stdev = 0.108
  CI (99.9%): [1.519, 5.453] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 10.935 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 4.366 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.220 ±(99.9%) 0.006 ms/op
Iteration   1: 4.190 ±(99.9%) 0.007 ms/op
Iteration   2: 4.172 ±(99.9%) 0.007 ms/op
Iteration   3: 4.059 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.140 ±(99.9%) 1.296 ms/op [Average]
  (min, avg, max) = (4.059, 4.140, 4.190), stdev = 0.071
  CI (99.9%): [2.844, 5.436] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 9.620 ±(99.9%) 0.134 ms/op
# Warmup Iteration   2: 4.171 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.504 ±(99.9%) 0.009 ms/op
Iteration   1: 3.460 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.370 ms/op
                 createUser·p0.50:   3.379 ms/op
                 createUser·p0.90:   3.850 ms/op
                 createUser·p0.95:   4.194 ms/op
                 createUser·p0.99:   5.857 ms/op
                 createUser·p0.999:  20.771 ms/op
                 createUser·p0.9999: 24.305 ms/op
                 createUser·p1.00:   24.740 ms/op

Iteration   2: 3.478 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.407 ms/op
                 createUser·p0.50:   3.404 ms/op
                 createUser·p0.90:   3.871 ms/op
                 createUser·p0.95:   4.129 ms/op
                 createUser·p0.99:   5.640 ms/op
                 createUser·p0.999:  23.760 ms/op
                 createUser·p0.9999: 29.550 ms/op
                 createUser·p1.00:   29.950 ms/op

Iteration   3: 3.501 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.761 ms/op
                 createUser·p0.50:   3.371 ms/op
                 createUser·p0.90:   3.965 ms/op
                 createUser·p0.95:   4.260 ms/op
                 createUser·p0.99:   6.259 ms/op
                 createUser·p0.999:  16.798 ms/op
                 createUser·p0.9999: 27.319 ms/op
                 createUser·p1.00:   27.853 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 275888
  mean =      3.479 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7935 
    [ 2.500,  5.000) = 262786 
    [ 5.000,  7.500) = 4067 
    [ 7.500, 10.000) = 529 
    [10.000, 12.500) = 191 
    [12.500, 15.000) = 70 
    [15.000, 17.500) = 35 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 38 
    [22.500, 25.000) = 130 
    [25.000, 27.500) = 56 

  Percentiles, ms/op:
      p(0.0000) =      1.370 ms/op
     p(50.0000) =      3.387 ms/op
     p(90.0000) =      3.899 ms/op
     p(95.0000) =      4.194 ms/op
     p(99.0000) =      5.931 ms/op
     p(99.9000) =     17.443 ms/op
     p(99.9900) =     27.754 ms/op
     p(99.9990) =     29.827 ms/op
     p(99.9999) =     29.950 ms/op
    p(100.0000) =     29.950 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 8.051 ±(99.9%) 0.098 ms/op
# Warmup Iteration   2: 3.562 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.352 ±(99.9%) 0.008 ms/op
Iteration   1: 3.376 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.384 ms/op
                 existUser·p0.50:   3.305 ms/op
                 existUser·p0.90:   3.744 ms/op
                 existUser·p0.95:   3.985 ms/op
                 existUser·p0.99:   5.284 ms/op
                 existUser·p0.999:  10.093 ms/op
                 existUser·p0.9999: 22.282 ms/op
                 existUser·p1.00:   23.003 ms/op

Iteration   2: 3.385 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.475 ms/op
                 existUser·p0.50:   3.252 ms/op
                 existUser·p0.90:   3.748 ms/op
                 existUser·p0.95:   4.133 ms/op
                 existUser·p0.99:   6.365 ms/op
                 existUser·p0.999:  21.062 ms/op
                 existUser·p0.9999: 24.266 ms/op
                 existUser·p1.00:   24.642 ms/op

Iteration   3: 3.360 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.067 ms/op
                 existUser·p0.50:   3.265 ms/op
                 existUser·p0.90:   3.686 ms/op
                 existUser·p0.95:   3.961 ms/op
                 existUser·p0.99:   6.062 ms/op
                 existUser·p0.999:  21.332 ms/op
                 existUser·p0.9999: 26.558 ms/op
                 existUser·p1.00:   28.639 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 284429
  mean =      3.374 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6495 
    [ 2.500,  5.000) = 272865 
    [ 5.000,  7.500) = 3966 
    [ 7.500, 10.000) = 544 
    [10.000, 12.500) = 225 
    [12.500, 15.000) = 10 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 53 
    [20.000, 22.500) = 102 
    [22.500, 25.000) = 89 
    [25.000, 27.500) = 46 

  Percentiles, ms/op:
      p(0.0000) =      1.067 ms/op
     p(50.0000) =      3.273 ms/op
     p(90.0000) =      3.727 ms/op
     p(95.0000) =      4.022 ms/op
     p(99.0000) =      5.988 ms/op
     p(99.9000) =     18.139 ms/op
     p(99.9900) =     25.854 ms/op
     p(99.9990) =     28.100 ms/op
     p(99.9999) =     28.639 ms/op
    p(100.0000) =     28.639 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 9.032 ±(99.9%) 0.109 ms/op
# Warmup Iteration   2: 3.766 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.576 ±(99.9%) 0.010 ms/op
Iteration   1: 3.656 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.957 ms/op
                 getUser·p0.50:   3.469 ms/op
                 getUser·p0.90:   4.051 ms/op
                 getUser·p0.95:   4.997 ms/op
                 getUser·p0.99:   7.520 ms/op
                 getUser·p0.999:  16.024 ms/op
                 getUser·p0.9999: 23.822 ms/op
                 getUser·p1.00:   24.281 ms/op

Iteration   2: 3.460 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.323 ms/op
                 getUser·p0.50:   3.346 ms/op
                 getUser·p0.90:   3.781 ms/op
                 getUser·p0.95:   3.990 ms/op
                 getUser·p0.99:   5.759 ms/op
                 getUser·p0.999:  23.094 ms/op
                 getUser·p0.9999: 25.944 ms/op
                 getUser·p1.00:   27.099 ms/op

Iteration   3: 3.555 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.969 ms/op
                 getUser·p0.50:   3.482 ms/op
                 getUser·p0.90:   3.879 ms/op
                 getUser·p0.95:   4.076 ms/op
                 getUser·p0.99:   5.890 ms/op
                 getUser·p0.999:  18.940 ms/op
                 getUser·p0.9999: 26.870 ms/op
                 getUser·p1.00:   31.130 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 269844
  mean =      3.555 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1987 
    [ 2.500,  5.000) = 260474 
    [ 5.000,  7.500) = 5897 
    [ 7.500, 10.000) = 836 
    [10.000, 12.500) = 275 
    [12.500, 15.000) = 75 
    [15.000, 17.500) = 39 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 37 
    [22.500, 25.000) = 103 
    [25.000, 27.500) = 96 
    [27.500, 30.000) = 2 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.957 ms/op
     p(50.0000) =      3.428 ms/op
     p(90.0000) =      3.895 ms/op
     p(95.0000) =      4.211 ms/op
     p(99.0000) =      6.906 ms/op
     p(99.9000) =     17.229 ms/op
     p(99.9900) =     26.281 ms/op
     p(99.9990) =     27.765 ms/op
     p(99.9999) =     31.130 ms/op
    p(100.0000) =     31.130 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 11.461 ±(99.9%) 0.147 ms/op
# Warmup Iteration   2: 4.830 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.300 ±(99.9%) 0.013 ms/op
Iteration   1: 4.155 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.883 ms/op
                 listUser·p0.50:   4.010 ms/op
                 listUser·p0.90:   4.530 ms/op
                 listUser·p0.95:   4.817 ms/op
                 listUser·p0.99:   7.702 ms/op
                 listUser·p0.999:  18.413 ms/op
                 listUser·p0.9999: 22.962 ms/op
                 listUser·p1.00:   23.396 ms/op

Iteration   2: 4.244 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.774 ms/op
                 listUser·p0.50:   4.063 ms/op
                 listUser·p0.90:   4.735 ms/op
                 listUser·p0.95:   5.136 ms/op
                 listUser·p0.99:   7.709 ms/op
                 listUser·p0.999:  15.920 ms/op
                 listUser·p0.9999: 20.004 ms/op
                 listUser·p1.00:   22.512 ms/op

Iteration   3: 4.110 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.449 ms/op
                 listUser·p0.50:   3.957 ms/op
                 listUser·p0.90:   4.579 ms/op
                 listUser·p0.95:   4.817 ms/op
                 listUser·p0.99:   7.111 ms/op
                 listUser·p0.999:  15.519 ms/op
                 listUser·p0.9999: 16.941 ms/op
                 listUser·p1.00:   17.498 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 230217
  mean =      4.169 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27 
    [ 2.500,  5.000) = 220130 
    [ 5.000,  7.500) = 7899 
    [ 7.500, 10.000) = 1316 
    [10.000, 12.500) = 232 
    [12.500, 15.000) = 254 
    [15.000, 17.500) = 228 
    [17.500, 20.000) = 78 
    [20.000, 22.500) = 43 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.883 ms/op
     p(50.0000) =      3.998 ms/op
     p(90.0000) =      4.620 ms/op
     p(95.0000) =      4.915 ms/op
     p(99.0000) =      7.397 ms/op
     p(99.9000) =     16.335 ms/op
     p(99.9900) =     20.840 ms/op
     p(99.9990) =     23.354 ms/op
     p(99.9999) =     23.396 ms/op
    p(100.0000) =     23.396 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.308 ± 1.558  ops/ms
ClientPb.existUser                       thrpt       3   9.591 ± 2.367  ops/ms
ClientPb.getUser                         thrpt       3   9.057 ± 1.908  ops/ms
ClientPb.listUser                        thrpt       3   7.684 ± 0.651  ops/ms
ClientPb.createUser                       avgt       3   3.548 ± 1.200   ms/op
ClientPb.existUser                        avgt       3   3.321 ± 0.961   ms/op
ClientPb.getUser                          avgt       3   3.486 ± 1.967   ms/op
ClientPb.listUser                         avgt       3   4.140 ± 1.296   ms/op
ClientPb.createUser                     sample  275888   3.479 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.370           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.387           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.899           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.194           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.931           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.443           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.754           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.950           ms/op
ClientPb.existUser                      sample  284429   3.374 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.067           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.273           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.727           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.022           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.988           ms/op
ClientPb.existUser:existUser·p0.999     sample          18.139           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.854           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.639           ms/op
ClientPb.getUser                        sample  269844   3.555 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.957           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.428           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.895           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.211           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.906           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.229           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.281           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.130           ms/op
ClientPb.listUser                       sample  230217   4.169 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.883           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.998           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.620           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.915           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.397           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.335           ms/op
ClientPb.listUser:listUser·p0.9999      sample          20.840           ms/op
ClientPb.listUser:listUser·p1.00        sample          23.396           ms/op
