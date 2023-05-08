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
# Warmup Iteration   1: 0.970 ops/ms
# Warmup Iteration   2: 2.186 ops/ms
# Warmup Iteration   3: 4.609 ops/ms
Iteration   1: 5.228 ops/ms
Iteration   2: 5.538 ops/ms
Iteration   3: 5.525 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.430 ±(99.9%) 3.197 ops/ms [Average]
  (min, avg, max) = (5.228, 5.430, 5.538), stdev = 0.175
  CI (99.9%): [2.233, 8.628] (assumes normal distribution)


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
# Warmup Iteration   1: 1.655 ops/ms
# Warmup Iteration   2: 4.496 ops/ms
# Warmup Iteration   3: 5.339 ops/ms
Iteration   1: 5.716 ops/ms
Iteration   2: 5.595 ops/ms
Iteration   3: 5.764 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.692 ±(99.9%) 1.586 ops/ms [Average]
  (min, avg, max) = (5.595, 5.692, 5.764), stdev = 0.087
  CI (99.9%): [4.106, 7.278] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:04
# Fork: 1 of 1
# Warmup Iteration   1: 1.356 ops/ms
# Warmup Iteration   2: 4.128 ops/ms
# Warmup Iteration   3: 5.174 ops/ms
Iteration   1: 5.352 ops/ms
Iteration   2: 5.509 ops/ms
Iteration   3: 5.464 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.442 ±(99.9%) 1.469 ops/ms [Average]
  (min, avg, max) = (5.352, 5.442, 5.509), stdev = 0.081
  CI (99.9%): [3.972, 6.911] (assumes normal distribution)


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
# Warmup Iteration   1: 1.516 ops/ms
# Warmup Iteration   2: 3.349 ops/ms
# Warmup Iteration   3: 4.490 ops/ms
Iteration   1: 4.574 ops/ms
Iteration   2: 4.677 ops/ms
Iteration   3: 4.826 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.692 ±(99.9%) 2.319 ops/ms [Average]
  (min, avg, max) = (4.574, 4.692, 4.826), stdev = 0.127
  CI (99.9%): [2.374, 7.011] (assumes normal distribution)


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
# Warmup Iteration   1: 18.973 ±(99.9%) 0.105 ms/op
# Warmup Iteration   2: 7.351 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 6.089 ±(99.9%) 0.008 ms/op
Iteration   1: 6.376 ±(99.9%) 0.012 ms/op
Iteration   2: 6.106 ±(99.9%) 0.010 ms/op
Iteration   3: 5.971 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.151 ±(99.9%) 3.757 ms/op [Average]
  (min, avg, max) = (5.971, 6.151, 6.376), stdev = 0.206
  CI (99.9%): [2.394, 9.908] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 17.513 ±(99.9%) 0.074 ms/op
# Warmup Iteration   2: 7.464 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.936 ±(99.9%) 0.010 ms/op
Iteration   1: 5.725 ±(99.9%) 0.017 ms/op
Iteration   2: 5.496 ±(99.9%) 0.015 ms/op
Iteration   3: 5.648 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.623 ±(99.9%) 2.128 ms/op [Average]
  (min, avg, max) = (5.496, 5.623, 5.725), stdev = 0.117
  CI (99.9%): [3.495, 7.751] (assumes normal distribution)


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
# Warmup Iteration   1: 18.503 ±(99.9%) 0.092 ms/op
# Warmup Iteration   2: 7.430 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 6.063 ±(99.9%) 0.012 ms/op
Iteration   1: 6.180 ±(99.9%) 0.009 ms/op
Iteration   2: 5.910 ±(99.9%) 0.012 ms/op
Iteration   3: 5.821 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.970 ±(99.9%) 3.411 ms/op [Average]
  (min, avg, max) = (5.821, 5.970, 6.180), stdev = 0.187
  CI (99.9%): [2.560, 9.381] (assumes normal distribution)


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
# Warmup Iteration   1: 23.331 ±(99.9%) 0.118 ms/op
# Warmup Iteration   2: 8.311 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 7.120 ±(99.9%) 0.022 ms/op
Iteration   1: 6.674 ±(99.9%) 0.026 ms/op
Iteration   2: 6.967 ±(99.9%) 0.013 ms/op
Iteration   3: 6.674 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.771 ±(99.9%) 3.094 ms/op [Average]
  (min, avg, max) = (6.674, 6.771, 6.967), stdev = 0.170
  CI (99.9%): [3.677, 9.866] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 20.493 ±(99.9%) 0.341 ms/op
# Warmup Iteration   2: 8.058 ±(99.9%) 0.054 ms/op
# Warmup Iteration   3: 6.467 ±(99.9%) 0.030 ms/op
Iteration   1: 6.224 ±(99.9%) 0.024 ms/op
                 createUser·p0.00:   2.462 ms/op
                 createUser·p0.50:   5.931 ms/op
                 createUser·p0.90:   7.856 ms/op
                 createUser·p0.95:   8.995 ms/op
                 createUser·p0.99:   11.715 ms/op
                 createUser·p0.999:  26.272 ms/op
                 createUser·p0.9999: 30.867 ms/op
                 createUser·p1.00:   31.883 ms/op

Iteration   2: 6.076 ±(99.9%) 0.024 ms/op
                 createUser·p0.00:   2.298 ms/op
                 createUser·p0.50:   5.882 ms/op
                 createUser·p0.90:   7.610 ms/op
                 createUser·p0.95:   8.716 ms/op
                 createUser·p0.99:   11.387 ms/op
                 createUser·p0.999:  28.915 ms/op
                 createUser·p0.9999: 31.530 ms/op
                 createUser·p1.00:   32.506 ms/op

Iteration   3: 5.740 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   2.666 ms/op
                 createUser·p0.50:   5.513 ms/op
                 createUser·p0.90:   7.102 ms/op
                 createUser·p0.95:   7.848 ms/op
                 createUser·p0.99:   10.240 ms/op
                 createUser·p0.999:  14.096 ms/op
                 createUser·p0.9999: 32.899 ms/op
                 createUser·p1.00:   33.751 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 159642
  mean =      6.007 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5 
    [ 2.500,  5.000) = 37951 
    [ 5.000,  7.500) = 105142 
    [ 7.500, 10.000) = 13364 
    [10.000, 12.500) = 2352 
    [12.500, 15.000) = 490 
    [15.000, 17.500) = 94 
    [17.500, 20.000) = 34 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 36 
    [27.500, 30.000) = 70 
    [30.000, 32.500) = 51 
    [32.500, 35.000) = 15 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.298 ms/op
     p(50.0000) =      5.784 ms/op
     p(90.0000) =      7.537 ms/op
     p(95.0000) =      8.503 ms/op
     p(99.0000) =     11.272 ms/op
     p(99.9000) =     26.313 ms/op
     p(99.9900) =     32.316 ms/op
     p(99.9990) =     33.517 ms/op
     p(99.9999) =     33.751 ms/op
    p(100.0000) =     33.751 ms/op


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
# Warmup Iteration   1: 18.531 ±(99.9%) 0.327 ms/op
# Warmup Iteration   2: 6.741 ±(99.9%) 0.044 ms/op
# Warmup Iteration   3: 5.780 ±(99.9%) 0.023 ms/op
Iteration   1: 5.609 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   1.606 ms/op
                 existUser·p0.50:   5.161 ms/op
                 existUser·p0.90:   7.037 ms/op
                 existUser·p0.95:   8.094 ms/op
                 existUser·p0.99:   10.764 ms/op
                 existUser·p0.999:  15.483 ms/op
                 existUser·p0.9999: 28.167 ms/op
                 existUser·p1.00:   29.164 ms/op

Iteration   2: 5.875 ±(99.9%) 0.026 ms/op
                 existUser·p0.00:   1.819 ms/op
                 existUser·p0.50:   5.513 ms/op
                 existUser·p0.90:   7.406 ms/op
                 existUser·p0.95:   8.421 ms/op
                 existUser·p0.99:   12.973 ms/op
                 existUser·p0.999:  29.365 ms/op
                 existUser·p0.9999: 41.208 ms/op
                 existUser·p1.00:   42.009 ms/op

Iteration   3: 5.736 ±(99.9%) 0.023 ms/op
                 existUser·p0.00:   2.523 ms/op
                 existUser·p0.50:   5.358 ms/op
                 existUser·p0.90:   7.283 ms/op
                 existUser·p0.95:   8.110 ms/op
                 existUser·p0.99:   10.939 ms/op
                 existUser·p0.999:  28.362 ms/op
                 existUser·p0.9999: 35.352 ms/op
                 existUser·p1.00:   36.635 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 167180
  mean =      5.738 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 60184 
    [ 5.000, 10.000) = 103874 
    [10.000, 15.000) = 2639 
    [15.000, 20.000) = 282 
    [20.000, 25.000) = 41 
    [25.000, 30.000) = 65 
    [30.000, 35.000) = 57 
    [35.000, 40.000) = 24 
    [40.000, 45.000) = 14 

  Percentiles, ms/op:
      p(0.0000) =      1.606 ms/op
     p(50.0000) =      5.374 ms/op
     p(90.0000) =      7.242 ms/op
     p(95.0000) =      8.200 ms/op
     p(99.0000) =     11.567 ms/op
     p(99.9000) =     24.478 ms/op
     p(99.9900) =     39.555 ms/op
     p(99.9990) =     41.744 ms/op
     p(99.9999) =     42.009 ms/op
    p(100.0000) =     42.009 ms/op


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
# Warmup Iteration   1: 18.844 ±(99.9%) 0.299 ms/op
# Warmup Iteration   2: 6.990 ±(99.9%) 0.042 ms/op
# Warmup Iteration   3: 6.440 ±(99.9%) 0.030 ms/op
Iteration   1: 6.296 ±(99.9%) 0.032 ms/op
                 getUser·p0.00:   2.437 ms/op
                 getUser·p0.50:   5.964 ms/op
                 getUser·p0.90:   7.971 ms/op
                 getUser·p0.95:   9.929 ms/op
                 getUser·p0.99:   15.122 ms/op
                 getUser·p0.999:  25.553 ms/op
                 getUser·p0.9999: 42.068 ms/op
                 getUser·p1.00:   43.188 ms/op

Iteration   2: 6.030 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   2.892 ms/op
                 getUser·p0.50:   5.874 ms/op
                 getUser·p0.90:   7.545 ms/op
                 getUser·p0.95:   8.298 ms/op
                 getUser·p0.99:   10.142 ms/op
                 getUser·p0.999:  27.426 ms/op
                 getUser·p0.9999: 31.293 ms/op
                 getUser·p1.00:   31.982 ms/op

Iteration   3: 5.909 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   2.634 ms/op
                 getUser·p0.50:   5.644 ms/op
                 getUser·p0.90:   7.160 ms/op
                 getUser·p0.95:   8.282 ms/op
                 getUser·p0.99:   11.190 ms/op
                 getUser·p0.999:  15.856 ms/op
                 getUser·p0.9999: 34.472 ms/op
                 getUser·p1.00:   34.931 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 158026
  mean =      6.074 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 33405 
    [ 5.000, 10.000) = 120449 
    [10.000, 15.000) = 3453 
    [15.000, 20.000) = 544 
    [20.000, 25.000) = 27 
    [25.000, 30.000) = 49 
    [30.000, 35.000) = 55 
    [35.000, 40.000) = 8 
    [40.000, 45.000) = 36 

  Percentiles, ms/op:
      p(0.0000) =      2.437 ms/op
     p(50.0000) =      5.800 ms/op
     p(90.0000) =      7.528 ms/op
     p(95.0000) =      8.651 ms/op
     p(99.0000) =     12.206 ms/op
     p(99.9000) =     24.128 ms/op
     p(99.9900) =     41.523 ms/op
     p(99.9990) =     43.188 ms/op
     p(99.9999) =     43.188 ms/op
    p(100.0000) =     43.188 ms/op


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
# Warmup Iteration   1: 23.145 ±(99.9%) 0.398 ms/op
# Warmup Iteration   2: 8.739 ±(99.9%) 0.070 ms/op
# Warmup Iteration   3: 7.188 ±(99.9%) 0.033 ms/op
Iteration   1: 6.878 ±(99.9%) 0.029 ms/op
                 listUser·p0.00:   3.088 ms/op
                 listUser·p0.50:   6.414 ms/op
                 listUser·p0.90:   8.995 ms/op
                 listUser·p0.95:   10.355 ms/op
                 listUser·p0.99:   13.198 ms/op
                 listUser·p0.999:  26.917 ms/op
                 listUser·p0.9999: 29.068 ms/op
                 listUser·p1.00:   30.704 ms/op

Iteration   2: 7.004 ±(99.9%) 0.029 ms/op
                 listUser·p0.00:   2.527 ms/op
                 listUser·p0.50:   6.685 ms/op
                 listUser·p0.90:   8.831 ms/op
                 listUser·p0.95:   9.781 ms/op
                 listUser·p0.99:   12.845 ms/op
                 listUser·p0.999:  31.174 ms/op
                 listUser·p0.9999: 38.490 ms/op
                 listUser·p1.00:   39.715 ms/op

Iteration   3: 6.754 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   2.482 ms/op
                 listUser·p0.50:   6.406 ms/op
                 listUser·p0.90:   8.143 ms/op
                 listUser·p0.95:   9.077 ms/op
                 listUser·p0.99:   12.337 ms/op
                 listUser·p0.999:  30.745 ms/op
                 listUser·p0.9999: 35.096 ms/op
                 listUser·p1.00:   35.914 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 139540
  mean =      6.877 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2 
    [ 2.500,  5.000) = 3336 
    [ 5.000,  7.500) = 105146 
    [ 7.500, 10.000) = 24908 
    [10.000, 12.500) = 4530 
    [12.500, 15.000) = 980 
    [15.000, 17.500) = 233 
    [17.500, 20.000) = 102 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 65 
    [27.500, 30.000) = 101 
    [30.000, 32.500) = 56 
    [32.500, 35.000) = 23 
    [35.000, 37.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      2.482 ms/op
     p(50.0000) =      6.496 ms/op
     p(90.0000) =      8.651 ms/op
     p(95.0000) =      9.781 ms/op
     p(99.0000) =     12.861 ms/op
     p(99.9000) =     29.065 ms/op
     p(99.9900) =     36.569 ms/op
     p(99.9990) =     39.430 ms/op
     p(99.9999) =     39.715 ms/op
    p(100.0000) =     39.715 ms/op


# Run complete. Total time: 00:13:17

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.430 ± 3.197  ops/ms
ClientPb.existUser                       thrpt       3   5.692 ± 1.586  ops/ms
ClientPb.getUser                         thrpt       3   5.442 ± 1.469  ops/ms
ClientPb.listUser                        thrpt       3   4.692 ± 2.319  ops/ms
ClientPb.createUser                       avgt       3   6.151 ± 3.757   ms/op
ClientPb.existUser                        avgt       3   5.623 ± 2.128   ms/op
ClientPb.getUser                          avgt       3   5.970 ± 3.411   ms/op
ClientPb.listUser                         avgt       3   6.771 ± 3.094   ms/op
ClientPb.createUser                     sample  159642   6.007 ± 0.013   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.298           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.784           ms/op
ClientPb.createUser:createUser·p0.90    sample           7.537           ms/op
ClientPb.createUser:createUser·p0.95    sample           8.503           ms/op
ClientPb.createUser:createUser·p0.99    sample          11.272           ms/op
ClientPb.createUser:createUser·p0.999   sample          26.313           ms/op
ClientPb.createUser:createUser·p0.9999  sample          32.316           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.751           ms/op
ClientPb.existUser                      sample  167180   5.738 ± 0.013   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.606           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.374           ms/op
ClientPb.existUser:existUser·p0.90      sample           7.242           ms/op
ClientPb.existUser:existUser·p0.95      sample           8.200           ms/op
ClientPb.existUser:existUser·p0.99      sample          11.567           ms/op
ClientPb.existUser:existUser·p0.999     sample          24.478           ms/op
ClientPb.existUser:existUser·p0.9999    sample          39.555           ms/op
ClientPb.existUser:existUser·p1.00      sample          42.009           ms/op
ClientPb.getUser                        sample  158026   6.074 ± 0.014   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.437           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.800           ms/op
ClientPb.getUser:getUser·p0.90          sample           7.528           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.651           ms/op
ClientPb.getUser:getUser·p0.99          sample          12.206           ms/op
ClientPb.getUser:getUser·p0.999         sample          24.128           ms/op
ClientPb.getUser:getUser·p0.9999        sample          41.523           ms/op
ClientPb.getUser:getUser·p1.00          sample          43.188           ms/op
ClientPb.listUser                       sample  139540   6.877 ± 0.016   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.482           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.496           ms/op
ClientPb.listUser:listUser·p0.90        sample           8.651           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.781           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.861           ms/op
ClientPb.listUser:listUser·p0.999       sample          29.065           ms/op
ClientPb.listUser:listUser·p0.9999      sample          36.569           ms/op
ClientPb.listUser:listUser·p1.00        sample          39.715           ms/op
