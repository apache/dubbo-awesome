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
# Warmup Iteration   1: 2.465 ops/ms
# Warmup Iteration   2: 6.274 ops/ms
# Warmup Iteration   3: 9.255 ops/ms
Iteration   1: 10.120 ops/ms
Iteration   2: 9.777 ops/ms
Iteration   3: 9.658 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.852 ±(99.9%) 4.374 ops/ms [Average]
  (min, avg, max) = (9.658, 9.852, 10.120), stdev = 0.240
  CI (99.9%): [5.478, 14.225] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.454 ops/ms
# Warmup Iteration   2: 8.970 ops/ms
# Warmup Iteration   3: 10.234 ops/ms
Iteration   1: 10.625 ops/ms
Iteration   2: 10.241 ops/ms
Iteration   3: 9.922 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.263 ±(99.9%) 6.420 ops/ms [Average]
  (min, avg, max) = (9.922, 10.263, 10.625), stdev = 0.352
  CI (99.9%): [3.843, 16.682] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.552 ops/ms
# Warmup Iteration   2: 9.087 ops/ms
# Warmup Iteration   3: 9.433 ops/ms
Iteration   1: 9.820 ops/ms
Iteration   2: 10.251 ops/ms
Iteration   3: 9.787 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.953 ±(99.9%) 4.723 ops/ms [Average]
  (min, avg, max) = (9.787, 9.953, 10.251), stdev = 0.259
  CI (99.9%): [5.229, 14.676] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.297 ops/ms
# Warmup Iteration   2: 7.623 ops/ms
# Warmup Iteration   3: 8.588 ops/ms
Iteration   1: 8.532 ops/ms
Iteration   2: 8.364 ops/ms
Iteration   3: 8.422 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.439 ±(99.9%) 1.555 ops/ms [Average]
  (min, avg, max) = (8.364, 8.439, 8.532), stdev = 0.085
  CI (99.9%): [6.884, 9.995] (assumes normal distribution)


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
# Warmup Iteration   1: 8.406 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.577 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.326 ±(99.9%) 0.005 ms/op
Iteration   1: 3.296 ±(99.9%) 0.004 ms/op
Iteration   2: 3.216 ±(99.9%) 0.008 ms/op
Iteration   3: 3.136 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.216 ±(99.9%) 1.461 ms/op [Average]
  (min, avg, max) = (3.136, 3.216, 3.296), stdev = 0.080
  CI (99.9%): [1.755, 4.677] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 7.858 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.366 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.107 ±(99.9%) 0.003 ms/op
Iteration   1: 3.061 ±(99.9%) 0.005 ms/op
Iteration   2: 3.084 ±(99.9%) 0.011 ms/op
Iteration   3: 3.083 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.076 ±(99.9%) 0.234 ms/op [Average]
  (min, avg, max) = (3.061, 3.076, 3.084), stdev = 0.013
  CI (99.9%): [2.842, 3.310] (assumes normal distribution)


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
# Warmup Iteration   1: 7.522 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.481 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.376 ±(99.9%) 0.003 ms/op
Iteration   1: 3.406 ±(99.9%) 0.006 ms/op
Iteration   2: 3.298 ±(99.9%) 0.004 ms/op
Iteration   3: 3.457 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.387 ±(99.9%) 1.482 ms/op [Average]
  (min, avg, max) = (3.298, 3.387, 3.457), stdev = 0.081
  CI (99.9%): [1.905, 4.869] (assumes normal distribution)


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
# Warmup Iteration   1: 8.686 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.244 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.902 ±(99.9%) 0.007 ms/op
Iteration   1: 3.854 ±(99.9%) 0.004 ms/op
Iteration   2: 3.718 ±(99.9%) 0.008 ms/op
Iteration   3: 3.670 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.747 ±(99.9%) 1.736 ms/op [Average]
  (min, avg, max) = (3.670, 3.747, 3.854), stdev = 0.095
  CI (99.9%): [2.012, 5.483] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 8.414 ±(99.9%) 0.099 ms/op
# Warmup Iteration   2: 3.701 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.249 ±(99.9%) 0.009 ms/op
Iteration   1: 3.289 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.395 ms/op
                 createUser·p0.50:   3.162 ms/op
                 createUser·p0.90:   3.826 ms/op
                 createUser·p0.95:   4.243 ms/op
                 createUser·p0.99:   6.144 ms/op
                 createUser·p0.999:  16.671 ms/op
                 createUser·p0.9999: 20.555 ms/op
                 createUser·p1.00:   21.004 ms/op

Iteration   2: 3.110 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.292 ms/op
                 createUser·p0.50:   3.088 ms/op
                 createUser·p0.90:   3.228 ms/op
                 createUser·p0.95:   3.408 ms/op
                 createUser·p0.99:   5.316 ms/op
                 createUser·p0.999:  11.849 ms/op
                 createUser·p0.9999: 23.239 ms/op
                 createUser·p1.00:   24.642 ms/op

Iteration   3: 3.140 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.573 ms/op
                 createUser·p0.50:   3.117 ms/op
                 createUser·p0.90:   3.351 ms/op
                 createUser·p0.95:   3.604 ms/op
                 createUser·p0.99:   4.801 ms/op
                 createUser·p0.999:  14.520 ms/op
                 createUser·p0.9999: 31.031 ms/op
                 createUser·p1.00:   31.261 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 301822
  mean =      3.178 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18764 
    [ 2.500,  5.000) = 278322 
    [ 5.000,  7.500) = 3898 
    [ 7.500, 10.000) = 376 
    [10.000, 12.500) = 108 
    [12.500, 15.000) = 60 
    [15.000, 17.500) = 63 
    [17.500, 20.000) = 77 
    [20.000, 22.500) = 100 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.292 ms/op
     p(50.0000) =      3.117 ms/op
     p(90.0000) =      3.510 ms/op
     p(95.0000) =      3.830 ms/op
     p(99.0000) =      5.472 ms/op
     p(99.9000) =     14.765 ms/op
     p(99.9900) =     30.769 ms/op
     p(99.9990) =     31.225 ms/op
     p(99.9999) =     31.261 ms/op
    p(100.0000) =     31.261 ms/op


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
# Warmup Iteration   1: 7.113 ±(99.9%) 0.081 ms/op
# Warmup Iteration   2: 3.316 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.173 ±(99.9%) 0.009 ms/op
Iteration   1: 3.079 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.133 ms/op
                 existUser·p0.50:   2.949 ms/op
                 existUser·p0.90:   3.301 ms/op
                 existUser·p0.95:   3.637 ms/op
                 existUser·p0.99:   5.890 ms/op
                 existUser·p0.999:  13.068 ms/op
                 existUser·p0.9999: 24.674 ms/op
                 existUser·p1.00:   25.657 ms/op

Iteration   2: 3.064 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.323 ms/op
                 existUser·p0.50:   2.986 ms/op
                 existUser·p0.90:   3.330 ms/op
                 existUser·p0.95:   3.617 ms/op
                 existUser·p0.99:   4.604 ms/op
                 existUser·p0.999:  12.943 ms/op
                 existUser·p0.9999: 24.332 ms/op
                 existUser·p1.00:   24.838 ms/op

Iteration   3: 3.114 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.877 ms/op
                 existUser·p0.50:   3.092 ms/op
                 existUser·p0.90:   3.244 ms/op
                 existUser·p0.95:   3.600 ms/op
                 existUser·p0.99:   5.595 ms/op
                 existUser·p0.999:  13.696 ms/op
                 existUser·p0.9999: 22.437 ms/op
                 existUser·p1.00:   22.970 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 311068
  mean =      3.085 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18709 
    [ 2.500,  5.000) = 286528 
    [ 5.000,  7.500) = 4823 
    [ 7.500, 10.000) = 499 
    [10.000, 12.500) = 154 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 55 
    [20.000, 22.500) = 117 
    [22.500, 25.000) = 85 
    [25.000, 27.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.877 ms/op
     p(50.0000) =      3.019 ms/op
     p(90.0000) =      3.289 ms/op
     p(95.0000) =      3.617 ms/op
     p(99.0000) =      5.562 ms/op
     p(99.9000) =     13.548 ms/op
     p(99.9900) =     24.179 ms/op
     p(99.9990) =     25.166 ms/op
     p(99.9999) =     25.657 ms/op
    p(100.0000) =     25.657 ms/op


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
# Warmup Iteration   1: 7.327 ±(99.9%) 0.104 ms/op
# Warmup Iteration   2: 3.325 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.248 ±(99.9%) 0.009 ms/op
Iteration   1: 3.111 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.227 ms/op
                 getUser·p0.50:   3.023 ms/op
                 getUser·p0.90:   3.363 ms/op
                 getUser·p0.95:   3.518 ms/op
                 getUser·p0.99:   5.284 ms/op
                 getUser·p0.999:  18.681 ms/op
                 getUser·p0.9999: 21.154 ms/op
                 getUser·p1.00:   22.151 ms/op

Iteration   2: 3.349 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.114 ms/op
                 getUser·p0.50:   3.244 ms/op
                 getUser·p0.90:   3.879 ms/op
                 getUser·p0.95:   4.678 ms/op
                 getUser·p0.99:   6.013 ms/op
                 getUser·p0.999:  10.041 ms/op
                 getUser·p0.9999: 22.868 ms/op
                 getUser·p1.00:   23.462 ms/op

Iteration   3: 3.238 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.688 ms/op
                 getUser·p0.50:   3.097 ms/op
                 getUser·p0.90:   3.666 ms/op
                 getUser·p0.95:   4.108 ms/op
                 getUser·p0.99:   5.931 ms/op
                 getUser·p0.999:  13.943 ms/op
                 getUser·p0.9999: 21.938 ms/op
                 getUser·p1.00:   23.265 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 297265
  mean =      3.229 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11741 
    [ 2.500,  5.000) = 279126 
    [ 5.000,  7.500) = 5382 
    [ 7.500, 10.000) = 530 
    [10.000, 12.500) = 109 
    [12.500, 15.000) = 105 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 107 
    [20.000, 22.500) = 120 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.114 ms/op
     p(50.0000) =      3.113 ms/op
     p(90.0000) =      3.629 ms/op
     p(95.0000) =      4.059 ms/op
     p(99.0000) =      5.743 ms/op
     p(99.9000) =     13.943 ms/op
     p(99.9900) =     22.184 ms/op
     p(99.9990) =     23.233 ms/op
     p(99.9999) =     23.462 ms/op
    p(100.0000) =     23.462 ms/op


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
# Warmup Iteration   1: 10.698 ±(99.9%) 0.118 ms/op
# Warmup Iteration   2: 4.587 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 3.824 ±(99.9%) 0.012 ms/op
Iteration   1: 3.778 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.305 ms/op
                 listUser·p0.50:   3.719 ms/op
                 listUser·p0.90:   3.879 ms/op
                 listUser·p0.95:   4.350 ms/op
                 listUser·p0.99:   7.012 ms/op
                 listUser·p0.999:  15.516 ms/op
                 listUser·p0.9999: 25.873 ms/op
                 listUser·p1.00:   27.165 ms/op

Iteration   2: 3.751 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.880 ms/op
                 listUser·p0.50:   3.678 ms/op
                 listUser·p0.90:   4.100 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   6.608 ms/op
                 listUser·p0.999:  14.107 ms/op
                 listUser·p0.9999: 19.825 ms/op
                 listUser·p1.00:   20.054 ms/op

Iteration   3: 3.767 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.700 ms/op
                 listUser·p0.50:   3.707 ms/op
                 listUser·p0.90:   3.908 ms/op
                 listUser·p0.95:   4.342 ms/op
                 listUser·p0.99:   6.963 ms/op
                 listUser·p0.999:  12.190 ms/op
                 listUser·p0.9999: 15.475 ms/op
                 listUser·p1.00:   15.516 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 254924
  mean =      3.765 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 111 
    [ 2.500,  5.000) = 246874 
    [ 5.000,  7.500) = 6278 
    [ 7.500, 10.000) = 1073 
    [10.000, 12.500) = 194 
    [12.500, 15.000) = 232 
    [15.000, 17.500) = 66 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 22 

  Percentiles, ms/op:
      p(0.0000) =      0.700 ms/op
     p(50.0000) =      3.703 ms/op
     p(90.0000) =      3.965 ms/op
     p(95.0000) =      4.350 ms/op
     p(99.0000) =      6.865 ms/op
     p(99.9000) =     14.107 ms/op
     p(99.9900) =     24.480 ms/op
     p(99.9990) =     26.728 ms/op
     p(99.9999) =     27.165 ms/op
    p(100.0000) =     27.165 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.852 ± 4.374  ops/ms
ClientPb.existUser                       thrpt       3  10.263 ± 6.420  ops/ms
ClientPb.getUser                         thrpt       3   9.953 ± 4.723  ops/ms
ClientPb.listUser                        thrpt       3   8.439 ± 1.555  ops/ms
ClientPb.createUser                       avgt       3   3.216 ± 1.461   ms/op
ClientPb.existUser                        avgt       3   3.076 ± 0.234   ms/op
ClientPb.getUser                          avgt       3   3.387 ± 1.482   ms/op
ClientPb.listUser                         avgt       3   3.747 ± 1.736   ms/op
ClientPb.createUser                     sample  301822   3.178 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.292           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.117           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.510           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.830           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.472           ms/op
ClientPb.createUser:createUser·p0.999   sample          14.765           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.769           ms/op
ClientPb.createUser:createUser·p1.00    sample          31.261           ms/op
ClientPb.existUser                      sample  311068   3.085 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.877           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.019           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.289           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.617           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.562           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.548           ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.179           ms/op
ClientPb.existUser:existUser·p1.00      sample          25.657           ms/op
ClientPb.getUser                        sample  297265   3.229 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.114           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.113           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.629           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.059           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.743           ms/op
ClientPb.getUser:getUser·p0.999         sample          13.943           ms/op
ClientPb.getUser:getUser·p0.9999        sample          22.184           ms/op
ClientPb.getUser:getUser·p1.00          sample          23.462           ms/op
ClientPb.listUser                       sample  254924   3.765 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.700           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.703           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.965           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.350           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.865           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.107           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.480           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.165           ms/op
