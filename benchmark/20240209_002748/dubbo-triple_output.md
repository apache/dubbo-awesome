# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 5.261 ops/ms
# Warmup Iteration   2: 12.230 ops/ms
# Warmup Iteration   3: 12.315 ops/ms
Iteration   1: 12.462 ops/ms
Iteration   2: 12.688 ops/ms
Iteration   3: 12.793 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.648 ±(99.9%) 3.087 ops/ms [Average]
  (min, avg, max) = (12.462, 12.648, 12.793), stdev = 0.169
  CI (99.9%): [9.561, 15.735] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:52
# Fork: 1 of 1
# Warmup Iteration   1: 8.378 ops/ms
# Warmup Iteration   2: 13.132 ops/ms
# Warmup Iteration   3: 12.948 ops/ms
Iteration   1: 13.318 ops/ms
Iteration   2: 13.347 ops/ms
Iteration   3: 12.976 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.214 ±(99.9%) 3.759 ops/ms [Average]
  (min, avg, max) = (12.976, 13.214, 13.347), stdev = 0.206
  CI (99.9%): [9.455, 16.973] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.886 ops/ms
# Warmup Iteration   2: 12.797 ops/ms
# Warmup Iteration   3: 12.964 ops/ms
Iteration   1: 13.138 ops/ms
Iteration   2: 12.974 ops/ms
Iteration   3: 13.071 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.061 ±(99.9%) 1.513 ops/ms [Average]
  (min, avg, max) = (12.974, 13.061, 13.138), stdev = 0.083
  CI (99.9%): [11.548, 14.574] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.682 ops/ms
# Warmup Iteration   2: 10.809 ops/ms
# Warmup Iteration   3: 10.788 ops/ms
Iteration   1: 10.785 ops/ms
Iteration   2: 10.836 ops/ms
Iteration   3: 10.815 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.812 ±(99.9%) 0.475 ops/ms [Average]
  (min, avg, max) = (10.785, 10.812, 10.836), stdev = 0.026
  CI (99.9%): [10.337, 11.287] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:37
# Fork: 1 of 1
# Warmup Iteration   1: 3.842 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.538 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.484 ±(99.9%) 0.003 ms/op
Iteration   1: 2.480 ±(99.9%) 0.004 ms/op
Iteration   2: 2.467 ±(99.9%) 0.003 ms/op
Iteration   3: 2.468 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.472 ±(99.9%) 0.128 ms/op [Average]
  (min, avg, max) = (2.467, 2.472, 2.480), stdev = 0.007
  CI (99.9%): [2.344, 2.599] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:32
# Fork: 1 of 1
# Warmup Iteration   1: 3.640 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.408 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.377 ±(99.9%) 0.004 ms/op
Iteration   1: 2.398 ±(99.9%) 0.003 ms/op
Iteration   2: 2.378 ±(99.9%) 0.003 ms/op
Iteration   3: 2.368 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.381 ±(99.9%) 0.278 ms/op [Average]
  (min, avg, max) = (2.368, 2.381, 2.398), stdev = 0.015
  CI (99.9%): [2.103, 2.659] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.710 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.490 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.475 ±(99.9%) 0.003 ms/op
Iteration   1: 2.484 ±(99.9%) 0.004 ms/op
Iteration   2: 2.452 ±(99.9%) 0.004 ms/op
Iteration   3: 2.453 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.463 ±(99.9%) 0.328 ms/op [Average]
  (min, avg, max) = (2.452, 2.463, 2.484), stdev = 0.018
  CI (99.9%): [2.136, 2.791] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 4.520 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 2.988 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.963 ±(99.9%) 0.004 ms/op
Iteration   1: 2.941 ±(99.9%) 0.005 ms/op
Iteration   2: 2.960 ±(99.9%) 0.006 ms/op
Iteration   3: 2.949 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.950 ±(99.9%) 0.174 ms/op [Average]
  (min, avg, max) = (2.941, 2.950, 2.960), stdev = 0.010
  CI (99.9%): [2.776, 3.124] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:19
# Fork: 1 of 1
# Warmup Iteration   1: 4.081 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.603 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.431 ±(99.9%) 0.005 ms/op
Iteration   1: 2.443 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.842 ms/op
                 createUser·p0.50:   2.466 ms/op
                 createUser·p0.90:   2.982 ms/op
                 createUser·p0.95:   3.105 ms/op
                 createUser·p0.99:   3.633 ms/op
                 createUser·p0.999:  10.591 ms/op
                 createUser·p0.9999: 13.281 ms/op
                 createUser·p1.00:   13.959 ms/op

Iteration   2: 2.414 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.812 ms/op
                 createUser·p0.50:   2.490 ms/op
                 createUser·p0.90:   2.925 ms/op
                 createUser·p0.95:   3.023 ms/op
                 createUser·p0.99:   3.437 ms/op
                 createUser·p0.999:  9.372 ms/op
                 createUser·p0.9999: 11.518 ms/op
                 createUser·p1.00:   13.009 ms/op

Iteration   3: 2.432 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.991 ms/op
                 createUser·p0.50:   2.499 ms/op
                 createUser·p0.90:   2.953 ms/op
                 createUser·p0.95:   3.088 ms/op
                 createUser·p0.99:   3.850 ms/op
                 createUser·p0.999:  7.711 ms/op
                 createUser·p0.9999: 9.793 ms/op
                 createUser·p1.00:   10.191 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 394857
  mean =      2.429 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 74 
    [ 1.250,  2.500) = 199062 
    [ 2.500,  3.750) = 192452 
    [ 3.750,  5.000) = 2526 
    [ 5.000,  6.250) = 243 
    [ 6.250,  7.500) = 36 
    [ 7.500,  8.750) = 48 
    [ 8.750, 10.000) = 157 
    [10.000, 11.250) = 103 
    [11.250, 12.500) = 84 
    [12.500, 13.750) = 66 
    [13.750, 15.000) = 6 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.812 ms/op
     p(50.0000) =      2.486 ms/op
     p(90.0000) =      2.953 ms/op
     p(95.0000) =      3.072 ms/op
     p(99.0000) =      3.645 ms/op
     p(99.9000) =      8.880 ms/op
     p(99.9900) =     12.796 ms/op
     p(99.9990) =     13.911 ms/op
     p(99.9999) =     13.959 ms/op
    p(100.0000) =     13.959 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.633 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.456 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.394 ±(99.9%) 0.005 ms/op
Iteration   1: 2.411 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.059 ms/op
                 existUser·p0.50:   2.462 ms/op
                 existUser·p0.90:   2.929 ms/op
                 existUser·p0.95:   3.019 ms/op
                 existUser·p0.99:   3.387 ms/op
                 existUser·p0.999:  5.794 ms/op
                 existUser·p0.9999: 13.365 ms/op
                 existUser·p1.00:   14.107 ms/op

Iteration   2: 2.443 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.980 ms/op
                 existUser·p0.50:   2.527 ms/op
                 existUser·p0.90:   2.957 ms/op
                 existUser·p0.95:   3.076 ms/op
                 existUser·p0.99:   3.846 ms/op
                 existUser·p0.999:  5.795 ms/op
                 existUser·p0.9999: 12.221 ms/op
                 existUser·p1.00:   13.566 ms/op

Iteration   3: 2.451 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.539 ms/op
                 existUser·p0.50:   2.507 ms/op
                 existUser·p0.90:   2.978 ms/op
                 existUser·p0.95:   3.101 ms/op
                 existUser·p0.99:   3.883 ms/op
                 existUser·p0.999:  8.221 ms/op
                 existUser·p0.9999: 11.550 ms/op
                 existUser·p1.00:   12.272 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 393888
  mean =      2.435 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 85 
    [ 1.250,  2.500) = 197191 
    [ 2.500,  3.750) = 192906 
    [ 3.750,  5.000) = 2957 
    [ 5.000,  6.250) = 330 
    [ 6.250,  7.500) = 46 
    [ 7.500,  8.750) = 45 
    [ 8.750, 10.000) = 68 
    [10.000, 11.250) = 75 
    [11.250, 12.500) = 153 
    [12.500, 13.750) = 27 
    [13.750, 15.000) = 5 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.539 ms/op
     p(50.0000) =      2.499 ms/op
     p(90.0000) =      2.953 ms/op
     p(95.0000) =      3.064 ms/op
     p(99.0000) =      3.707 ms/op
     p(99.9000) =      6.833 ms/op
     p(99.9900) =     12.468 ms/op
     p(99.9990) =     13.978 ms/op
     p(99.9999) =     14.107 ms/op
    p(100.0000) =     14.107 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.904 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.553 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.451 ±(99.9%) 0.005 ms/op
Iteration   1: 2.466 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.011 ms/op
                 getUser·p0.50:   2.474 ms/op
                 getUser·p0.90:   3.006 ms/op
                 getUser·p0.95:   3.129 ms/op
                 getUser·p0.99:   3.695 ms/op
                 getUser·p0.999:  6.592 ms/op
                 getUser·p0.9999: 13.484 ms/op
                 getUser·p1.00:   13.910 ms/op

Iteration   2: 2.488 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.024 ms/op
                 getUser·p0.50:   2.540 ms/op
                 getUser·p0.90:   3.019 ms/op
                 getUser·p0.95:   3.158 ms/op
                 getUser·p0.99:   4.043 ms/op
                 getUser·p0.999:  9.578 ms/op
                 getUser·p0.9999: 12.850 ms/op
                 getUser·p1.00:   13.468 ms/op

Iteration   3: 2.439 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.819 ms/op
                 getUser·p0.50:   2.474 ms/op
                 getUser·p0.90:   2.970 ms/op
                 getUser·p0.95:   3.072 ms/op
                 getUser·p0.99:   3.600 ms/op
                 getUser·p0.999:  5.831 ms/op
                 getUser·p0.9999: 11.243 ms/op
                 getUser·p1.00:   11.633 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 389163
  mean =      2.464 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 68 
    [ 1.250,  2.500) = 195192 
    [ 2.500,  3.750) = 190000 
    [ 3.750,  5.000) = 2823 
    [ 5.000,  6.250) = 655 
    [ 6.250,  7.500) = 30 
    [ 7.500,  8.750) = 25 
    [ 8.750, 10.000) = 92 
    [10.000, 11.250) = 70 
    [11.250, 12.500) = 101 
    [12.500, 13.750) = 101 
    [13.750, 15.000) = 6 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.819 ms/op
     p(50.0000) =      2.490 ms/op
     p(90.0000) =      2.998 ms/op
     p(95.0000) =      3.117 ms/op
     p(99.0000) =      3.752 ms/op
     p(99.9000) =      8.133 ms/op
     p(99.9900) =     13.307 ms/op
     p(99.9990) =     13.879 ms/op
     p(99.9999) =     13.910 ms/op
    p(100.0000) =     13.910 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.609 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.016 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.983 ±(99.9%) 0.008 ms/op
Iteration   1: 2.972 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.647 ms/op
                 listUser·p0.50:   2.912 ms/op
                 listUser·p0.90:   3.822 ms/op
                 listUser·p0.95:   4.317 ms/op
                 listUser·p0.99:   5.480 ms/op
                 listUser·p0.999:  9.158 ms/op
                 listUser·p0.9999: 12.440 ms/op
                 listUser·p1.00:   13.992 ms/op

Iteration   2: 2.986 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.877 ms/op
                 listUser·p0.50:   2.916 ms/op
                 listUser·p0.90:   3.883 ms/op
                 listUser·p0.95:   4.448 ms/op
                 listUser·p0.99:   5.628 ms/op
                 listUser·p0.999:  9.534 ms/op
                 listUser·p0.9999: 13.292 ms/op
                 listUser·p1.00:   17.400 ms/op

Iteration   3: 2.971 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.752 ms/op
                 listUser·p0.50:   2.908 ms/op
                 listUser·p0.90:   3.817 ms/op
                 listUser·p0.95:   4.293 ms/op
                 listUser·p0.99:   5.464 ms/op
                 listUser·p0.999:  9.175 ms/op
                 listUser·p0.9999: 10.854 ms/op
                 listUser·p1.00:   11.731 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 322197
  mean =      2.977 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 143 
    [ 1.250,  2.500) = 98897 
    [ 2.500,  3.750) = 186308 
    [ 3.750,  5.000) = 29880 
    [ 5.000,  6.250) = 5796 
    [ 6.250,  7.500) = 507 
    [ 7.500,  8.750) = 193 
    [ 8.750, 10.000) = 279 
    [10.000, 11.250) = 130 
    [11.250, 12.500) = 33 
    [12.500, 13.750) = 28 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.647 ms/op
     p(50.0000) =      2.912 ms/op
     p(90.0000) =      3.838 ms/op
     p(95.0000) =      4.350 ms/op
     p(99.0000) =      5.530 ms/op
     p(99.9000) =      9.339 ms/op
     p(99.9900) =     12.477 ms/op
     p(99.9990) =     13.764 ms/op
     p(99.9999) =     17.400 ms/op
    p(100.0000) =     17.400 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.648 ± 3.087  ops/ms
ClientPb.existUser                       thrpt       3  13.214 ± 3.759  ops/ms
ClientPb.getUser                         thrpt       3  13.061 ± 1.513  ops/ms
ClientPb.listUser                        thrpt       3  10.812 ± 0.475  ops/ms
ClientPb.createUser                       avgt       3   2.472 ± 0.128   ms/op
ClientPb.existUser                        avgt       3   2.381 ± 0.278   ms/op
ClientPb.getUser                          avgt       3   2.463 ± 0.328   ms/op
ClientPb.listUser                         avgt       3   2.950 ± 0.174   ms/op
ClientPb.createUser                     sample  394857   2.429 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.812           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.486           ms/op
ClientPb.createUser:createUser·p0.90    sample           2.953           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.072           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.645           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.880           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.796           ms/op
ClientPb.createUser:createUser·p1.00    sample          13.959           ms/op
ClientPb.existUser                      sample  393888   2.435 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.539           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.499           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.953           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.064           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.707           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.833           ms/op
ClientPb.existUser:existUser·p0.9999    sample          12.468           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.107           ms/op
ClientPb.getUser                        sample  389163   2.464 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.819           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.490           ms/op
ClientPb.getUser:getUser·p0.90          sample           2.998           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.117           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.752           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.133           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.307           ms/op
ClientPb.getUser:getUser·p1.00          sample          13.910           ms/op
ClientPb.listUser                       sample  322197   2.977 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.647           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.912           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.838           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.350           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.530           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.339           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.477           ms/op
ClientPb.listUser:listUser·p1.00        sample          17.400           ms/op
