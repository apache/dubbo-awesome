# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.078 ops/ms
# Warmup Iteration   2: 5.100 ops/ms
# Warmup Iteration   3: 8.592 ops/ms
Iteration   1: 8.895 ops/ms
Iteration   2: 8.881 ops/ms
Iteration   3: 9.289 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.022 ±(99.9%) 4.226 ops/ms [Average]
  (min, avg, max) = (8.881, 9.022, 9.289), stdev = 0.232
  CI (99.9%): [4.796, 13.248] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.424 ops/ms
# Warmup Iteration   2: 8.983 ops/ms
# Warmup Iteration   3: 9.223 ops/ms
Iteration   1: 9.259 ops/ms
Iteration   2: 9.483 ops/ms
Iteration   3: 9.255 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.332 ±(99.9%) 2.381 ops/ms [Average]
  (min, avg, max) = (9.255, 9.332, 9.483), stdev = 0.130
  CI (99.9%): [6.952, 11.713] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 2.815 ops/ms
# Warmup Iteration   2: 7.997 ops/ms
# Warmup Iteration   3: 8.937 ops/ms
Iteration   1: 8.896 ops/ms
Iteration   2: 9.055 ops/ms
Iteration   3: 9.018 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.990 ±(99.9%) 1.520 ops/ms [Average]
  (min, avg, max) = (8.896, 8.990, 9.055), stdev = 0.083
  CI (99.9%): [7.469, 10.510] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 3.028 ops/ms
# Warmup Iteration   2: 6.958 ops/ms
# Warmup Iteration   3: 7.381 ops/ms
Iteration   1: 7.407 ops/ms
Iteration   2: 7.694 ops/ms
Iteration   3: 7.602 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.568 ±(99.9%) 2.668 ops/ms [Average]
  (min, avg, max) = (7.407, 7.568, 7.694), stdev = 0.146
  CI (99.9%): [4.899, 10.236] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 10.846 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.733 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.899 ±(99.9%) 0.004 ms/op
Iteration   1: 3.560 ±(99.9%) 0.004 ms/op
Iteration   2: 3.536 ±(99.9%) 0.003 ms/op
Iteration   3: 3.599 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.565 ±(99.9%) 0.579 ms/op [Average]
  (min, avg, max) = (3.536, 3.565, 3.599), stdev = 0.032
  CI (99.9%): [2.986, 4.145] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 9.765 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.683 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.491 ±(99.9%) 0.003 ms/op
Iteration   1: 3.395 ±(99.9%) 0.007 ms/op
Iteration   2: 3.469 ±(99.9%) 0.003 ms/op
Iteration   3: 3.325 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.396 ±(99.9%) 1.321 ms/op [Average]
  (min, avg, max) = (3.325, 3.396, 3.469), stdev = 0.072
  CI (99.9%): [2.076, 4.717] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 9.555 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.785 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.681 ±(99.9%) 0.004 ms/op
Iteration   1: 3.608 ±(99.9%) 0.005 ms/op
Iteration   2: 3.512 ±(99.9%) 0.005 ms/op
Iteration   3: 3.555 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.559 ±(99.9%) 0.871 ms/op [Average]
  (min, avg, max) = (3.512, 3.559, 3.608), stdev = 0.048
  CI (99.9%): [2.687, 4.430] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 11.746 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.534 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.309 ±(99.9%) 0.008 ms/op
Iteration   1: 4.219 ±(99.9%) 0.005 ms/op
Iteration   2: 4.239 ±(99.9%) 0.006 ms/op
Iteration   3: 4.106 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.188 ±(99.9%) 1.307 ms/op [Average]
  (min, avg, max) = (4.106, 4.188, 4.239), stdev = 0.072
  CI (99.9%): [2.881, 5.495] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 9.517 ±(99.9%) 0.125 ms/op
# Warmup Iteration   2: 4.089 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.533 ±(99.9%) 0.011 ms/op
Iteration   1: 3.495 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.217 ms/op
                 createUser·p0.50:   3.301 ms/op
                 createUser·p0.90:   3.953 ms/op
                 createUser·p0.95:   4.309 ms/op
                 createUser·p0.99:   6.898 ms/op
                 createUser·p0.999:  21.797 ms/op
                 createUser·p0.9999: 34.397 ms/op
                 createUser·p1.00:   36.372 ms/op

Iteration   2: 3.637 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.319 ms/op
                 createUser·p0.50:   3.465 ms/op
                 createUser·p0.90:   4.227 ms/op
                 createUser·p0.95:   4.530 ms/op
                 createUser·p0.99:   7.332 ms/op
                 createUser·p0.999:  13.513 ms/op
                 createUser·p0.9999: 26.418 ms/op
                 createUser·p1.00:   27.558 ms/op

Iteration   3: 3.531 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.470 ms/op
                 createUser·p0.50:   3.375 ms/op
                 createUser·p0.90:   3.994 ms/op
                 createUser·p0.95:   4.276 ms/op
                 createUser·p0.99:   6.341 ms/op
                 createUser·p0.999:  24.104 ms/op
                 createUser·p0.9999: 51.446 ms/op
                 createUser·p1.00:   51.577 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 270062
  mean =      3.553 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 262404 
    [ 5.000, 10.000) = 6889 
    [10.000, 15.000) = 352 
    [15.000, 20.000) = 74 
    [20.000, 25.000) = 201 
    [25.000, 30.000) = 87 
    [30.000, 35.000) = 18 
    [35.000, 40.000) = 5 
    [40.000, 45.000) = 0 
    [45.000, 50.000) = 3 
    [50.000, 55.000) = 29 

  Percentiles, ms/op:
      p(0.0000) =      1.217 ms/op
     p(50.0000) =      3.383 ms/op
     p(90.0000) =      4.067 ms/op
     p(95.0000) =      4.391 ms/op
     p(99.0000) =      6.868 ms/op
     p(99.9000) =     21.955 ms/op
     p(99.9900) =     50.658 ms/op
     p(99.9990) =     51.511 ms/op
     p(99.9999) =     51.577 ms/op
    p(100.0000) =     51.577 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 8.124 ±(99.9%) 0.107 ms/op
# Warmup Iteration   2: 3.732 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.431 ±(99.9%) 0.009 ms/op
Iteration   1: 3.473 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.327 ms/op
                 existUser·p0.50:   3.314 ms/op
                 existUser·p0.90:   3.920 ms/op
                 existUser·p0.95:   4.342 ms/op
                 existUser·p0.99:   6.976 ms/op
                 existUser·p0.999:  18.243 ms/op
                 existUser·p0.9999: 30.526 ms/op
                 existUser·p1.00:   40.174 ms/op

Iteration   2: 3.419 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.565 ms/op
                 existUser·p0.50:   3.248 ms/op
                 existUser·p0.90:   3.756 ms/op
                 existUser·p0.95:   4.579 ms/op
                 existUser·p0.99:   7.193 ms/op
                 existUser·p0.999:  20.032 ms/op
                 existUser·p0.9999: 22.169 ms/op
                 existUser·p1.00:   22.970 ms/op

Iteration   3: 3.349 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.219 ms/op
                 existUser·p0.50:   3.244 ms/op
                 existUser·p0.90:   3.641 ms/op
                 existUser·p0.95:   3.940 ms/op
                 existUser·p0.99:   6.226 ms/op
                 existUser·p0.999:  18.317 ms/op
                 existUser·p0.9999: 28.457 ms/op
                 existUser·p1.00:   29.032 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 281446
  mean =      3.413 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 272316 
    [ 5.000, 10.000) = 8374 
    [10.000, 15.000) = 376 
    [15.000, 20.000) = 150 
    [20.000, 25.000) = 173 
    [25.000, 30.000) = 43 
    [30.000, 35.000) = 13 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.219 ms/op
     p(50.0000) =      3.265 ms/op
     p(90.0000) =      3.781 ms/op
     p(95.0000) =      4.252 ms/op
     p(99.0000) =      6.971 ms/op
     p(99.9000) =     18.317 ms/op
     p(99.9900) =     28.630 ms/op
     p(99.9990) =     32.405 ms/op
     p(99.9999) =     40.174 ms/op
    p(100.0000) =     40.174 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 9.453 ±(99.9%) 0.121 ms/op
# Warmup Iteration   2: 3.798 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.627 ±(99.9%) 0.011 ms/op
Iteration   1: 3.622 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.983 ms/op
                 getUser·p0.50:   3.441 ms/op
                 getUser·p0.90:   3.994 ms/op
                 getUser·p0.95:   4.571 ms/op
                 getUser·p0.99:   7.403 ms/op
                 getUser·p0.999:  16.340 ms/op
                 getUser·p0.9999: 22.348 ms/op
                 getUser·p1.00:   23.331 ms/op

Iteration   2: 3.573 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.276 ms/op
                 getUser·p0.50:   3.441 ms/op
                 getUser·p0.90:   3.928 ms/op
                 getUser·p0.95:   4.284 ms/op
                 getUser·p0.99:   6.734 ms/op
                 getUser·p0.999:  22.102 ms/op
                 getUser·p0.9999: 24.283 ms/op
                 getUser·p1.00:   24.609 ms/op

Iteration   3: 3.621 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.190 ms/op
                 getUser·p0.50:   3.486 ms/op
                 getUser·p0.90:   4.010 ms/op
                 getUser·p0.95:   4.352 ms/op
                 getUser·p0.99:   6.963 ms/op
                 getUser·p0.999:  19.938 ms/op
                 getUser·p0.9999: 27.083 ms/op
                 getUser·p1.00:   28.836 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 266107
  mean =      3.605 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2864 
    [ 2.500,  5.000) = 253626 
    [ 5.000,  7.500) = 7620 
    [ 7.500, 10.000) = 1149 
    [10.000, 12.500) = 401 
    [12.500, 15.000) = 76 
    [15.000, 17.500) = 85 
    [17.500, 20.000) = 39 
    [20.000, 22.500) = 95 
    [22.500, 25.000) = 120 
    [25.000, 27.500) = 26 

  Percentiles, ms/op:
      p(0.0000) =      0.983 ms/op
     p(50.0000) =      3.453 ms/op
     p(90.0000) =      3.977 ms/op
     p(95.0000) =      4.391 ms/op
     p(99.0000) =      7.127 ms/op
     p(99.9000) =     18.543 ms/op
     p(99.9900) =     25.610 ms/op
     p(99.9990) =     28.290 ms/op
     p(99.9999) =     28.836 ms/op
    p(100.0000) =     28.836 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 11.840 ±(99.9%) 0.166 ms/op
# Warmup Iteration   2: 4.626 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.297 ±(99.9%) 0.014 ms/op
Iteration   1: 4.247 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.810 ms/op
                 listUser·p0.50:   4.100 ms/op
                 listUser·p0.90:   4.637 ms/op
                 listUser·p0.95:   4.964 ms/op
                 listUser·p0.99:   7.954 ms/op
                 listUser·p0.999:  19.300 ms/op
                 listUser·p0.9999: 32.111 ms/op
                 listUser·p1.00:   32.735 ms/op

Iteration   2: 4.246 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.269 ms/op
                 listUser·p0.50:   4.100 ms/op
                 listUser·p0.90:   4.620 ms/op
                 listUser·p0.95:   4.981 ms/op
                 listUser·p0.99:   8.389 ms/op
                 listUser·p0.999:  15.312 ms/op
                 listUser·p0.9999: 19.726 ms/op
                 listUser·p1.00:   20.251 ms/op

Iteration   3: 4.205 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.432 ms/op
                 listUser·p0.50:   4.022 ms/op
                 listUser·p0.90:   4.669 ms/op
                 listUser·p0.95:   5.186 ms/op
                 listUser·p0.99:   8.461 ms/op
                 listUser·p0.999:  15.499 ms/op
                 listUser·p0.9999: 25.336 ms/op
                 listUser·p1.00:   26.182 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 226765
  mean =      4.232 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 99 
    [ 2.500,  5.000) = 214889 
    [ 5.000,  7.500) = 8105 
    [ 7.500, 10.000) = 2692 
    [10.000, 12.500) = 279 
    [12.500, 15.000) = 301 
    [15.000, 17.500) = 203 
    [17.500, 20.000) = 104 
    [20.000, 22.500) = 44 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 10 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 17 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.432 ms/op
     p(50.0000) =      4.076 ms/op
     p(90.0000) =      4.645 ms/op
     p(95.0000) =      5.038 ms/op
     p(99.0000) =      8.323 ms/op
     p(99.9000) =     16.924 ms/op
     p(99.9900) =     25.547 ms/op
     p(99.9990) =     32.521 ms/op
     p(99.9999) =     32.735 ms/op
    p(100.0000) =     32.735 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.022 ± 4.226  ops/ms
ClientPb.existUser                       thrpt       3   9.332 ± 2.381  ops/ms
ClientPb.getUser                         thrpt       3   8.990 ± 1.520  ops/ms
ClientPb.listUser                        thrpt       3   7.568 ± 2.668  ops/ms
ClientPb.createUser                       avgt       3   3.565 ± 0.579   ms/op
ClientPb.existUser                        avgt       3   3.396 ± 1.321   ms/op
ClientPb.getUser                          avgt       3   3.559 ± 0.871   ms/op
ClientPb.listUser                         avgt       3   4.188 ± 1.307   ms/op
ClientPb.createUser                     sample  270062   3.553 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.217           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.383           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.067           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.391           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.868           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.955           ms/op
ClientPb.createUser:createUser·p0.9999  sample          50.658           ms/op
ClientPb.createUser:createUser·p1.00    sample          51.577           ms/op
ClientPb.existUser                      sample  281446   3.413 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.219           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.265           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.781           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.252           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.971           ms/op
ClientPb.existUser:existUser·p0.999     sample          18.317           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.630           ms/op
ClientPb.existUser:existUser·p1.00      sample          40.174           ms/op
ClientPb.getUser                        sample  266107   3.605 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.983           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.453           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.977           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.391           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.127           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.543           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.610           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.836           ms/op
ClientPb.listUser                       sample  226765   4.232 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.432           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.076           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.645           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.038           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.323           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.924           ms/op
ClientPb.listUser:listUser·p0.9999      sample          25.547           ms/op
ClientPb.listUser:listUser·p1.00        sample          32.735           ms/op
