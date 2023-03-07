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
# Warmup Iteration   1: 1.226 ops/ms
# Warmup Iteration   2: 3.002 ops/ms
# Warmup Iteration   3: 6.181 ops/ms
Iteration   1: 6.280 ops/ms
Iteration   2: 6.554 ops/ms
Iteration   3: 6.629 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.487 ±(99.9%) 3.350 ops/ms [Average]
  (min, avg, max) = (6.280, 6.487, 6.629), stdev = 0.184
  CI (99.9%): [3.137, 9.837] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.043 ops/ms
# Warmup Iteration   2: 5.905 ops/ms
# Warmup Iteration   3: 7.170 ops/ms
Iteration   1: 7.092 ops/ms
Iteration   2: 6.923 ops/ms
Iteration   3: 7.167 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  7.061 ±(99.9%) 2.284 ops/ms [Average]
  (min, avg, max) = (6.923, 7.061, 7.167), stdev = 0.125
  CI (99.9%): [4.777, 9.344] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.884 ops/ms
# Warmup Iteration   2: 5.637 ops/ms
# Warmup Iteration   3: 6.351 ops/ms
Iteration   1: 6.321 ops/ms
Iteration   2: 6.342 ops/ms
Iteration   3: 6.531 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.398 ±(99.9%) 2.112 ops/ms [Average]
  (min, avg, max) = (6.321, 6.398, 6.531), stdev = 0.116
  CI (99.9%): [4.286, 8.510] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 1.656 ops/ms
# Warmup Iteration   2: 4.701 ops/ms
# Warmup Iteration   3: 5.785 ops/ms
Iteration   1: 5.858 ops/ms
Iteration   2: 5.659 ops/ms
Iteration   3: 5.861 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.793 ±(99.9%) 2.115 ops/ms [Average]
  (min, avg, max) = (5.659, 5.793, 5.861), stdev = 0.116
  CI (99.9%): [3.678, 7.908] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:50
# Fork: 1 of 1
# Warmup Iteration   1: 16.916 ±(99.9%) 0.081 ms/op
# Warmup Iteration   2: 5.640 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 5.065 ±(99.9%) 0.010 ms/op
Iteration   1: 4.910 ±(99.9%) 0.012 ms/op
Iteration   2: 4.667 ±(99.9%) 0.014 ms/op
Iteration   3: 4.850 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.809 ±(99.9%) 2.305 ms/op [Average]
  (min, avg, max) = (4.667, 4.809, 4.910), stdev = 0.126
  CI (99.9%): [2.503, 7.114] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 13.703 ±(99.9%) 0.061 ms/op
# Warmup Iteration   2: 5.016 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.701 ±(99.9%) 0.010 ms/op
Iteration   1: 4.524 ±(99.9%) 0.011 ms/op
Iteration   2: 4.550 ±(99.9%) 0.016 ms/op
Iteration   3: 4.528 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.534 ±(99.9%) 0.257 ms/op [Average]
  (min, avg, max) = (4.524, 4.534, 4.550), stdev = 0.014
  CI (99.9%): [4.277, 4.791] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 15.086 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 5.427 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.770 ±(99.9%) 0.010 ms/op
Iteration   1: 4.826 ±(99.9%) 0.008 ms/op
Iteration   2: 4.925 ±(99.9%) 0.011 ms/op
Iteration   3: 4.660 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.804 ±(99.9%) 2.441 ms/op [Average]
  (min, avg, max) = (4.660, 4.804, 4.925), stdev = 0.134
  CI (99.9%): [2.363, 7.245] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 16.592 ±(99.9%) 0.071 ms/op
# Warmup Iteration   2: 6.063 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 5.822 ±(99.9%) 0.011 ms/op
Iteration   1: 5.402 ±(99.9%) 0.016 ms/op
Iteration   2: 5.346 ±(99.9%) 0.017 ms/op
Iteration   3: 5.145 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.298 ±(99.9%) 2.471 ms/op [Average]
  (min, avg, max) = (5.145, 5.298, 5.402), stdev = 0.135
  CI (99.9%): [2.826, 7.769] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 16.127 ±(99.9%) 0.228 ms/op
# Warmup Iteration   2: 5.834 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 5.515 ±(99.9%) 0.027 ms/op
Iteration   1: 4.792 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   2.126 ms/op
                 createUser·p0.50:   4.588 ms/op
                 createUser·p0.90:   5.685 ms/op
                 createUser·p0.95:   6.349 ms/op
                 createUser·p0.99:   9.142 ms/op
                 createUser·p0.999:  16.433 ms/op
                 createUser·p0.9999: 26.662 ms/op
                 createUser·p1.00:   27.165 ms/op

Iteration   2: 4.806 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.296 ms/op
                 createUser·p0.50:   4.637 ms/op
                 createUser·p0.90:   5.751 ms/op
                 createUser·p0.95:   6.218 ms/op
                 createUser·p0.99:   8.241 ms/op
                 createUser·p0.999:  16.260 ms/op
                 createUser·p0.9999: 32.235 ms/op
                 createUser·p1.00:   33.489 ms/op

Iteration   3: 4.766 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   1.972 ms/op
                 createUser·p0.50:   4.579 ms/op
                 createUser·p0.90:   5.685 ms/op
                 createUser·p0.95:   6.250 ms/op
                 createUser·p0.99:   8.561 ms/op
                 createUser·p0.999:  25.392 ms/op
                 createUser·p0.9999: 29.327 ms/op
                 createUser·p1.00:   30.212 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 200327
  mean =      4.788 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 62 
    [ 2.500,  5.000) = 143607 
    [ 5.000,  7.500) = 52959 
    [ 7.500, 10.000) = 2602 
    [10.000, 12.500) = 563 
    [12.500, 15.000) = 230 
    [15.000, 17.500) = 79 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 88 
    [25.000, 27.500) = 63 
    [27.500, 30.000) = 32 
    [30.000, 32.500) = 29 
    [32.500, 35.000) = 4 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.296 ms/op
     p(50.0000) =      4.604 ms/op
     p(90.0000) =      5.710 ms/op
     p(95.0000) =      6.259 ms/op
     p(99.0000) =      8.667 ms/op
     p(99.9000) =     23.560 ms/op
     p(99.9900) =     31.456 ms/op
     p(99.9990) =     33.095 ms/op
     p(99.9999) =     33.489 ms/op
    p(100.0000) =     33.489 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 15.614 ±(99.9%) 0.215 ms/op
# Warmup Iteration   2: 5.888 ±(99.9%) 0.035 ms/op
# Warmup Iteration   3: 4.940 ±(99.9%) 0.017 ms/op
Iteration   1: 4.461 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   2.220 ms/op
                 existUser·p0.50:   4.202 ms/op
                 existUser·p0.90:   5.202 ms/op
                 existUser·p0.95:   5.844 ms/op
                 existUser·p0.99:   8.798 ms/op
                 existUser·p0.999:  19.235 ms/op
                 existUser·p0.9999: 24.216 ms/op
                 existUser·p1.00:   24.281 ms/op

Iteration   2: 4.572 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.509 ms/op
                 existUser·p0.50:   4.334 ms/op
                 existUser·p0.90:   5.472 ms/op
                 existUser·p0.95:   6.193 ms/op
                 existUser·p0.99:   8.339 ms/op
                 existUser·p0.999:  14.907 ms/op
                 existUser·p0.9999: 28.377 ms/op
                 existUser·p1.00:   29.196 ms/op

Iteration   3: 4.459 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.978 ms/op
                 existUser·p0.50:   4.276 ms/op
                 existUser·p0.90:   5.112 ms/op
                 existUser·p0.95:   5.612 ms/op
                 existUser·p0.99:   8.118 ms/op
                 existUser·p0.999:  24.070 ms/op
                 existUser·p0.9999: 30.353 ms/op
                 existUser·p1.00:   31.425 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 213528
  mean =      4.497 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 108 
    [ 2.500,  5.000) = 182588 
    [ 5.000,  7.500) = 26995 
    [ 7.500, 10.000) = 2799 
    [10.000, 12.500) = 551 
    [12.500, 15.000) = 185 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 66 
    [20.000, 22.500) = 54 
    [22.500, 25.000) = 61 
    [25.000, 27.500) = 42 
    [27.500, 30.000) = 38 
    [30.000, 32.500) = 11 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.509 ms/op
     p(50.0000) =      4.268 ms/op
     p(90.0000) =      5.267 ms/op
     p(95.0000) =      5.898 ms/op
     p(99.0000) =      8.454 ms/op
     p(99.9000) =     19.742 ms/op
     p(99.9900) =     28.857 ms/op
     p(99.9990) =     30.902 ms/op
     p(99.9999) =     31.425 ms/op
    p(100.0000) =     31.425 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 14.939 ±(99.9%) 0.228 ms/op
# Warmup Iteration   2: 5.584 ±(99.9%) 0.032 ms/op
# Warmup Iteration   3: 4.876 ±(99.9%) 0.016 ms/op
Iteration   1: 4.942 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   1.493 ms/op
                 getUser·p0.50:   4.628 ms/op
                 getUser·p0.90:   6.078 ms/op
                 getUser·p0.95:   7.078 ms/op
                 getUser·p0.99:   10.626 ms/op
                 getUser·p0.999:  17.051 ms/op
                 getUser·p0.9999: 23.415 ms/op
                 getUser·p1.00:   26.739 ms/op

Iteration   2: 4.815 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   2.298 ms/op
                 getUser·p0.50:   4.571 ms/op
                 getUser·p0.90:   5.579 ms/op
                 getUser·p0.95:   6.357 ms/op
                 getUser·p0.99:   10.109 ms/op
                 getUser·p0.999:  20.597 ms/op
                 getUser·p0.9999: 30.551 ms/op
                 getUser·p1.00:   31.654 ms/op

Iteration   3: 4.774 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.348 ms/op
                 getUser·p0.50:   4.571 ms/op
                 getUser·p0.90:   5.849 ms/op
                 getUser·p0.95:   6.414 ms/op
                 getUser·p0.99:   8.241 ms/op
                 getUser·p0.999:  14.377 ms/op
                 getUser·p0.9999: 25.717 ms/op
                 getUser·p1.00:   26.444 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 198162
  mean =      4.843 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 37 
    [ 2.500,  5.000) = 141945 
    [ 5.000,  7.500) = 50598 
    [ 7.500, 10.000) = 3798 
    [10.000, 12.500) = 1189 
    [12.500, 15.000) = 333 
    [15.000, 17.500) = 50 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 55 
    [22.500, 25.000) = 65 
    [25.000, 27.500) = 56 
    [27.500, 30.000) = 21 
    [30.000, 32.500) = 8 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.348 ms/op
     p(50.0000) =      4.588 ms/op
     p(90.0000) =      5.833 ms/op
     p(95.0000) =      6.636 ms/op
     p(99.0000) =      9.683 ms/op
     p(99.9000) =     20.311 ms/op
     p(99.9900) =     28.907 ms/op
     p(99.9990) =     31.204 ms/op
     p(99.9999) =     31.654 ms/op
    p(100.0000) =     31.654 ms/op


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
# Warmup Iteration   1: 16.828 ±(99.9%) 0.280 ms/op
# Warmup Iteration   2: 6.225 ±(99.9%) 0.032 ms/op
# Warmup Iteration   3: 5.594 ±(99.9%) 0.021 ms/op
Iteration   1: 5.739 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   2.327 ms/op
                 listUser·p0.50:   5.456 ms/op
                 listUser·p0.90:   6.783 ms/op
                 listUser·p0.95:   7.954 ms/op
                 listUser·p0.99:   11.076 ms/op
                 listUser·p0.999:  25.177 ms/op
                 listUser·p0.9999: 29.708 ms/op
                 listUser·p1.00:   30.573 ms/op

Iteration   2: 5.432 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   2.765 ms/op
                 listUser·p0.50:   5.186 ms/op
                 listUser·p0.90:   6.332 ms/op
                 listUser·p0.95:   7.250 ms/op
                 listUser·p0.99:   10.387 ms/op
                 listUser·p0.999:  21.538 ms/op
                 listUser·p0.9999: 26.954 ms/op
                 listUser·p1.00:   27.525 ms/op

Iteration   3: 5.551 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.950 ms/op
                 listUser·p0.50:   5.317 ms/op
                 listUser·p0.90:   6.496 ms/op
                 listUser·p0.95:   7.201 ms/op
                 listUser·p0.99:   10.158 ms/op
                 listUser·p0.999:  18.722 ms/op
                 listUser·p0.9999: 21.398 ms/op
                 listUser·p1.00:   21.987 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 172157
  mean =      5.571 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8 
    [ 2.500,  5.000) = 49571 
    [ 5.000,  7.500) = 114210 
    [ 7.500, 10.000) = 6069 
    [10.000, 12.500) = 1592 
    [12.500, 15.000) = 276 
    [15.000, 17.500) = 111 
    [17.500, 20.000) = 71 
    [20.000, 22.500) = 80 
    [22.500, 25.000) = 81 
    [25.000, 27.500) = 72 
    [27.500, 30.000) = 12 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.950 ms/op
     p(50.0000) =      5.317 ms/op
     p(90.0000) =      6.554 ms/op
     p(95.0000) =      7.455 ms/op
     p(99.0000) =     10.617 ms/op
     p(99.9000) =     22.277 ms/op
     p(99.9900) =     27.387 ms/op
     p(99.9990) =     30.478 ms/op
     p(99.9999) =     30.573 ms/op
    p(100.0000) =     30.573 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   6.487 ± 3.350  ops/ms
ClientPb.existUser                       thrpt       3   7.061 ± 2.284  ops/ms
ClientPb.getUser                         thrpt       3   6.398 ± 2.112  ops/ms
ClientPb.listUser                        thrpt       3   5.793 ± 2.115  ops/ms
ClientPb.createUser                       avgt       3   4.809 ± 2.305   ms/op
ClientPb.existUser                        avgt       3   4.534 ± 0.257   ms/op
ClientPb.getUser                          avgt       3   4.804 ± 2.441   ms/op
ClientPb.listUser                         avgt       3   5.298 ± 2.471   ms/op
ClientPb.createUser                     sample  200327   4.788 ± 0.009   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.296           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.604           ms/op
ClientPb.createUser:createUser·p0.90    sample           5.710           ms/op
ClientPb.createUser:createUser·p0.95    sample           6.259           ms/op
ClientPb.createUser:createUser·p0.99    sample           8.667           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.560           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.456           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.489           ms/op
ClientPb.existUser                      sample  213528   4.497 ± 0.008   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.509           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.268           ms/op
ClientPb.existUser:existUser·p0.90      sample           5.267           ms/op
ClientPb.existUser:existUser·p0.95      sample           5.898           ms/op
ClientPb.existUser:existUser·p0.99      sample           8.454           ms/op
ClientPb.existUser:existUser·p0.999     sample          19.742           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.857           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.425           ms/op
ClientPb.getUser                        sample  198162   4.843 ± 0.009   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.348           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.588           ms/op
ClientPb.getUser:getUser·p0.90          sample           5.833           ms/op
ClientPb.getUser:getUser·p0.95          sample           6.636           ms/op
ClientPb.getUser:getUser·p0.99          sample           9.683           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.311           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.907           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.654           ms/op
ClientPb.listUser                       sample  172157   5.571 ± 0.011   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.950           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.317           ms/op
ClientPb.listUser:listUser·p0.90        sample           6.554           ms/op
ClientPb.listUser:listUser·p0.95        sample           7.455           ms/op
ClientPb.listUser:listUser·p0.99        sample          10.617           ms/op
ClientPb.listUser:listUser·p0.999       sample          22.277           ms/op
ClientPb.listUser:listUser·p0.9999      sample          27.387           ms/op
ClientPb.listUser:listUser·p1.00        sample          30.573           ms/op
