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
# Warmup Iteration   1: 1.841 ops/ms
# Warmup Iteration   2: 5.518 ops/ms
# Warmup Iteration   3: 8.822 ops/ms
Iteration   1: 9.526 ops/ms
Iteration   2: 9.359 ops/ms
Iteration   3: 9.591 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.492 ±(99.9%) 2.187 ops/ms [Average]
  (min, avg, max) = (9.359, 9.492, 9.591), stdev = 0.120
  CI (99.9%): [7.306, 11.679] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 2.905 ops/ms
# Warmup Iteration   2: 8.555 ops/ms
# Warmup Iteration   3: 9.552 ops/ms
Iteration   1: 9.827 ops/ms
Iteration   2: 9.763 ops/ms
Iteration   3: 9.746 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.779 ±(99.9%) 0.783 ops/ms [Average]
  (min, avg, max) = (9.746, 9.779, 9.827), stdev = 0.043
  CI (99.9%): [8.995, 10.562] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 2.919 ops/ms
# Warmup Iteration   2: 8.592 ops/ms
# Warmup Iteration   3: 9.227 ops/ms
Iteration   1: 9.357 ops/ms
Iteration   2: 9.245 ops/ms
Iteration   3: 9.456 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.353 ±(99.9%) 1.919 ops/ms [Average]
  (min, avg, max) = (9.245, 9.353, 9.456), stdev = 0.105
  CI (99.9%): [7.434, 11.271] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 2.775 ops/ms
# Warmup Iteration   2: 7.384 ops/ms
# Warmup Iteration   3: 7.862 ops/ms
Iteration   1: 8.246 ops/ms
Iteration   2: 7.784 ops/ms
Iteration   3: 7.964 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.998 ±(99.9%) 4.256 ops/ms [Average]
  (min, avg, max) = (7.784, 7.998, 8.246), stdev = 0.233
  CI (99.9%): [3.742, 12.254] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 11.282 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 3.885 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.607 ±(99.9%) 0.009 ms/op
Iteration   1: 3.581 ±(99.9%) 0.008 ms/op
Iteration   2: 3.441 ±(99.9%) 0.009 ms/op
Iteration   3: 3.481 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.501 ±(99.9%) 1.314 ms/op [Average]
  (min, avg, max) = (3.441, 3.501, 3.581), stdev = 0.072
  CI (99.9%): [2.187, 4.815] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 8.739 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.548 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.343 ±(99.9%) 0.006 ms/op
Iteration   1: 3.287 ±(99.9%) 0.005 ms/op
Iteration   2: 3.211 ±(99.9%) 0.009 ms/op
Iteration   3: 3.367 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.288 ±(99.9%) 1.415 ms/op [Average]
  (min, avg, max) = (3.211, 3.288, 3.367), stdev = 0.078
  CI (99.9%): [1.873, 4.704] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 10.234 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.617 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.534 ±(99.9%) 0.004 ms/op
Iteration   1: 3.427 ±(99.9%) 0.008 ms/op
Iteration   2: 3.311 ±(99.9%) 0.006 ms/op
Iteration   3: 3.376 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.371 ±(99.9%) 1.053 ms/op [Average]
  (min, avg, max) = (3.311, 3.371, 3.427), stdev = 0.058
  CI (99.9%): [2.318, 4.425] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 11.537 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 4.413 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.127 ±(99.9%) 0.008 ms/op
Iteration   1: 4.101 ±(99.9%) 0.006 ms/op
Iteration   2: 4.052 ±(99.9%) 0.010 ms/op
Iteration   3: 4.134 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.096 ±(99.9%) 0.753 ms/op [Average]
  (min, avg, max) = (4.052, 4.096, 4.134), stdev = 0.041
  CI (99.9%): [3.342, 4.849] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 10.446 ±(99.9%) 0.154 ms/op
# Warmup Iteration   2: 3.848 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.672 ±(99.9%) 0.015 ms/op
Iteration   1: 3.503 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.556 ms/op
                 createUser·p0.50:   3.334 ms/op
                 createUser·p0.90:   4.059 ms/op
                 createUser·p0.95:   4.637 ms/op
                 createUser·p0.99:   6.685 ms/op
                 createUser·p0.999:  21.483 ms/op
                 createUser·p0.9999: 23.982 ms/op
                 createUser·p1.00:   24.904 ms/op

Iteration   2: 3.263 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.262 ms/op
                 createUser·p0.50:   3.265 ms/op
                 createUser·p0.90:   3.416 ms/op
                 createUser·p0.95:   3.576 ms/op
                 createUser·p0.99:   4.935 ms/op
                 createUser·p0.999:  10.602 ms/op
                 createUser·p0.9999: 26.595 ms/op
                 createUser·p1.00:   28.246 ms/op

Iteration   3: 3.460 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.520 ms/op
                 createUser·p0.50:   3.289 ms/op
                 createUser·p0.90:   3.957 ms/op
                 createUser·p0.95:   4.293 ms/op
                 createUser·p0.99:   5.988 ms/op
                 createUser·p0.999:  22.400 ms/op
                 createUser·p0.9999: 27.918 ms/op
                 createUser·p1.00:   28.836 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 281744
  mean =      3.405 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10330 
    [ 2.500,  5.000) = 264086 
    [ 5.000,  7.500) = 6114 
    [ 7.500, 10.000) = 754 
    [10.000, 12.500) = 139 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 18 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 50 
    [22.500, 25.000) = 138 
    [25.000, 27.500) = 85 

  Percentiles, ms/op:
      p(0.0000) =      1.262 ms/op
     p(50.0000) =      3.289 ms/op
     p(90.0000) =      3.858 ms/op
     p(95.0000) =      4.219 ms/op
     p(99.0000) =      6.193 ms/op
     p(99.9000) =     21.537 ms/op
     p(99.9900) =     26.656 ms/op
     p(99.9990) =     28.428 ms/op
     p(99.9999) =     28.836 ms/op
    p(100.0000) =     28.836 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 10.051 ±(99.9%) 0.135 ms/op
# Warmup Iteration   2: 3.730 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.248 ±(99.9%) 0.008 ms/op
Iteration   1: 3.309 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.700 ms/op
                 existUser·p0.50:   3.174 ms/op
                 existUser·p0.90:   3.629 ms/op
                 existUser·p0.95:   3.965 ms/op
                 existUser·p0.99:   6.193 ms/op
                 existUser·p0.999:  17.874 ms/op
                 existUser·p0.9999: 24.391 ms/op
                 existUser·p1.00:   24.936 ms/op

Iteration   2: 3.268 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.755 ms/op
                 existUser·p0.50:   3.265 ms/op
                 existUser·p0.90:   3.469 ms/op
                 existUser·p0.95:   3.752 ms/op
                 existUser·p0.99:   5.505 ms/op
                 existUser·p0.999:  9.741 ms/op
                 existUser·p0.9999: 23.994 ms/op
                 existUser·p1.00:   25.330 ms/op

Iteration   3: 3.259 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.671 ms/op
                 existUser·p0.50:   3.178 ms/op
                 existUser·p0.90:   3.510 ms/op
                 existUser·p0.95:   3.707 ms/op
                 existUser·p0.99:   5.339 ms/op
                 existUser·p0.999:  13.695 ms/op
                 existUser·p0.9999: 25.598 ms/op
                 existUser·p1.00:   27.492 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 292474
  mean =      3.279 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13655 
    [ 2.500,  5.000) = 273860 
    [ 5.000,  7.500) = 3875 
    [ 7.500, 10.000) = 630 
    [10.000, 12.500) = 129 
    [12.500, 15.000) = 60 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 62 
    [22.500, 25.000) = 159 
    [25.000, 27.500) = 42 

  Percentiles, ms/op:
      p(0.0000) =      1.671 ms/op
     p(50.0000) =      3.215 ms/op
     p(90.0000) =      3.539 ms/op
     p(95.0000) =      3.801 ms/op
     p(99.0000) =      5.808 ms/op
     p(99.9000) =     13.189 ms/op
     p(99.9900) =     25.281 ms/op
     p(99.9990) =     26.393 ms/op
     p(99.9999) =     27.492 ms/op
    p(100.0000) =     27.492 ms/op


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
# Warmup Iteration   1: 9.192 ±(99.9%) 0.117 ms/op
# Warmup Iteration   2: 3.818 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.558 ±(99.9%) 0.010 ms/op
Iteration   1: 3.512 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.573 ms/op
                 getUser·p0.50:   3.351 ms/op
                 getUser·p0.90:   4.055 ms/op
                 getUser·p0.95:   4.620 ms/op
                 getUser·p0.99:   6.578 ms/op
                 getUser·p0.999:  19.595 ms/op
                 getUser·p0.9999: 22.147 ms/op
                 getUser·p1.00:   22.807 ms/op

Iteration   2: 3.530 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.300 ms/op
                 getUser·p0.50:   3.416 ms/op
                 getUser·p0.90:   4.051 ms/op
                 getUser·p0.95:   4.432 ms/op
                 getUser·p0.99:   6.439 ms/op
                 getUser·p0.999:  22.446 ms/op
                 getUser·p0.9999: 30.439 ms/op
                 getUser·p1.00:   30.802 ms/op

Iteration   3: 3.451 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.920 ms/op
                 getUser·p0.50:   3.322 ms/op
                 getUser·p0.90:   3.826 ms/op
                 getUser·p0.95:   4.211 ms/op
                 getUser·p0.99:   6.382 ms/op
                 getUser·p0.999:  24.585 ms/op
                 getUser·p0.9999: 37.862 ms/op
                 getUser·p1.00:   38.076 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 274526
  mean =      3.498 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11659 
    [ 2.500,  5.000) = 253626 
    [ 5.000,  7.500) = 8117 
    [ 7.500, 10.000) = 673 
    [10.000, 12.500) = 86 
    [12.500, 15.000) = 67 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 79 
    [22.500, 25.000) = 63 
    [25.000, 27.500) = 21 
    [27.500, 30.000) = 18 
    [30.000, 32.500) = 31 
    [32.500, 35.000) = 19 
    [35.000, 37.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.920 ms/op
     p(50.0000) =      3.371 ms/op
     p(90.0000) =      3.985 ms/op
     p(95.0000) =      4.432 ms/op
     p(99.0000) =      6.455 ms/op
     p(99.9000) =     19.759 ms/op
     p(99.9900) =     36.962 ms/op
     p(99.9990) =     37.930 ms/op
     p(99.9999) =     38.076 ms/op
    p(100.0000) =     38.076 ms/op


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
# Warmup Iteration   1: 12.107 ±(99.9%) 0.172 ms/op
# Warmup Iteration   2: 4.702 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.162 ±(99.9%) 0.014 ms/op
Iteration   1: 4.095 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.622 ms/op
                 listUser·p0.50:   3.949 ms/op
                 listUser·p0.90:   4.588 ms/op
                 listUser·p0.95:   5.136 ms/op
                 listUser·p0.99:   7.692 ms/op
                 listUser·p0.999:  21.987 ms/op
                 listUser·p0.9999: 24.746 ms/op
                 listUser·p1.00:   25.264 ms/op

Iteration   2: 4.106 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.081 ms/op
                 listUser·p0.50:   3.908 ms/op
                 listUser·p0.90:   4.751 ms/op
                 listUser·p0.95:   5.112 ms/op
                 listUser·p0.99:   7.619 ms/op
                 listUser·p0.999:  17.331 ms/op
                 listUser·p0.9999: 20.316 ms/op
                 listUser·p1.00:   22.413 ms/op

Iteration   3: 3.932 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.425 ms/op
                 listUser·p0.50:   3.797 ms/op
                 listUser·p0.90:   4.391 ms/op
                 listUser·p0.95:   4.871 ms/op
                 listUser·p0.99:   6.701 ms/op
                 listUser·p0.999:  15.804 ms/op
                 listUser·p0.9999: 16.810 ms/op
                 listUser·p1.00:   16.908 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 237392
  mean =      4.043 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24 
    [ 2.500,  5.000) = 225055 
    [ 5.000,  7.500) = 9897 
    [ 7.500, 10.000) = 1541 
    [10.000, 12.500) = 345 
    [12.500, 15.000) = 112 
    [15.000, 17.500) = 214 
    [17.500, 20.000) = 96 
    [20.000, 22.500) = 43 
    [22.500, 25.000) = 62 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.622 ms/op
     p(50.0000) =      3.883 ms/op
     p(90.0000) =      4.628 ms/op
     p(95.0000) =      5.030 ms/op
     p(99.0000) =      7.528 ms/op
     p(99.9000) =     16.876 ms/op
     p(99.9900) =     24.146 ms/op
     p(99.9990) =     25.186 ms/op
     p(99.9999) =     25.264 ms/op
    p(100.0000) =     25.264 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.492 ± 2.187  ops/ms
ClientPb.existUser                       thrpt       3   9.779 ± 0.783  ops/ms
ClientPb.getUser                         thrpt       3   9.353 ± 1.919  ops/ms
ClientPb.listUser                        thrpt       3   7.998 ± 4.256  ops/ms
ClientPb.createUser                       avgt       3   3.501 ± 1.314   ms/op
ClientPb.existUser                        avgt       3   3.288 ± 1.415   ms/op
ClientPb.getUser                          avgt       3   3.371 ± 1.053   ms/op
ClientPb.listUser                         avgt       3   4.096 ± 0.753   ms/op
ClientPb.createUser                     sample  281744   3.405 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.262           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.289           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.858           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.219           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.193           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.537           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.656           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.836           ms/op
ClientPb.existUser                      sample  292474   3.279 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.671           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.215           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.539           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.801           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.808           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.189           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.281           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.492           ms/op
ClientPb.getUser                        sample  274526   3.498 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.920           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.371           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.985           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.432           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.455           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.759           ms/op
ClientPb.getUser:getUser·p0.9999        sample          36.962           ms/op
ClientPb.getUser:getUser·p1.00          sample          38.076           ms/op
ClientPb.listUser                       sample  237392   4.043 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.622           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.883           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.628           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.030           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.528           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.876           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.146           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.264           ms/op
