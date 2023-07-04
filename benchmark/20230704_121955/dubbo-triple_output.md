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
# Warmup Iteration   1: 2.222 ops/ms
# Warmup Iteration   2: 6.020 ops/ms
# Warmup Iteration   3: 8.794 ops/ms
Iteration   1: 9.264 ops/ms
Iteration   2: 9.229 ops/ms
Iteration   3: 9.320 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.271 ±(99.9%) 0.839 ops/ms [Average]
  (min, avg, max) = (9.229, 9.271, 9.320), stdev = 0.046
  CI (99.9%): [8.432, 10.110] (assumes normal distribution)


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
# Warmup Iteration   1: 3.184 ops/ms
# Warmup Iteration   2: 8.913 ops/ms
# Warmup Iteration   3: 9.797 ops/ms
Iteration   1: 9.946 ops/ms
Iteration   2: 10.146 ops/ms
Iteration   3: 10.141 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.078 ±(99.9%) 2.078 ops/ms [Average]
  (min, avg, max) = (9.946, 10.078, 10.146), stdev = 0.114
  CI (99.9%): [8.000, 12.156] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.887 ops/ms
# Warmup Iteration   2: 8.647 ops/ms
# Warmup Iteration   3: 8.720 ops/ms
Iteration   1: 9.709 ops/ms
Iteration   2: 9.530 ops/ms
Iteration   3: 9.583 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.607 ±(99.9%) 1.677 ops/ms [Average]
  (min, avg, max) = (9.530, 9.607, 9.709), stdev = 0.092
  CI (99.9%): [7.930, 11.284] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.998 ops/ms
# Warmup Iteration   2: 7.454 ops/ms
# Warmup Iteration   3: 7.726 ops/ms
Iteration   1: 7.931 ops/ms
Iteration   2: 7.979 ops/ms
Iteration   3: 7.979 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.963 ±(99.9%) 0.506 ops/ms [Average]
  (min, avg, max) = (7.931, 7.963, 7.979), stdev = 0.028
  CI (99.9%): [7.457, 8.469] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 8.759 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.726 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.532 ±(99.9%) 0.009 ms/op
Iteration   1: 3.427 ±(99.9%) 0.007 ms/op
Iteration   2: 3.372 ±(99.9%) 0.007 ms/op
Iteration   3: 3.328 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.376 ±(99.9%) 0.910 ms/op [Average]
  (min, avg, max) = (3.328, 3.376, 3.427), stdev = 0.050
  CI (99.9%): [2.465, 4.286] (assumes normal distribution)


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
# Warmup Iteration   1: 8.374 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.465 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.354 ±(99.9%) 0.006 ms/op
Iteration   1: 3.348 ±(99.9%) 0.008 ms/op
Iteration   2: 3.427 ±(99.9%) 0.009 ms/op
Iteration   3: 3.315 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.363 ±(99.9%) 1.050 ms/op [Average]
  (min, avg, max) = (3.315, 3.363, 3.427), stdev = 0.058
  CI (99.9%): [2.313, 4.413] (assumes normal distribution)


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
# Warmup Iteration   1: 9.078 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.615 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.489 ±(99.9%) 0.004 ms/op
Iteration   1: 3.283 ±(99.9%) 0.006 ms/op
Iteration   2: 3.332 ±(99.9%) 0.011 ms/op
Iteration   3: 3.283 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.299 ±(99.9%) 0.511 ms/op [Average]
  (min, avg, max) = (3.283, 3.299, 3.332), stdev = 0.028
  CI (99.9%): [2.788, 3.811] (assumes normal distribution)


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
# Warmup Iteration   1: 10.024 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 4.206 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.003 ±(99.9%) 0.007 ms/op
Iteration   1: 3.913 ±(99.9%) 0.015 ms/op
Iteration   2: 4.048 ±(99.9%) 0.009 ms/op
Iteration   3: 3.964 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.975 ±(99.9%) 1.246 ms/op [Average]
  (min, avg, max) = (3.913, 3.975, 4.048), stdev = 0.068
  CI (99.9%): [2.729, 5.221] (assumes normal distribution)


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
# Warmup Iteration   1: 9.637 ±(99.9%) 0.113 ms/op
# Warmup Iteration   2: 3.880 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.431 ±(99.9%) 0.010 ms/op
Iteration   1: 3.334 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.964 ms/op
                 createUser·p0.50:   3.301 ms/op
                 createUser·p0.90:   3.490 ms/op
                 createUser·p0.95:   3.695 ms/op
                 createUser·p0.99:   5.521 ms/op
                 createUser·p0.999:  20.940 ms/op
                 createUser·p0.9999: 31.229 ms/op
                 createUser·p1.00:   33.391 ms/op

Iteration   2: 3.461 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.807 ms/op
                 createUser·p0.50:   3.297 ms/op
                 createUser·p0.90:   4.002 ms/op
                 createUser·p0.95:   4.514 ms/op
                 createUser·p0.99:   5.604 ms/op
                 createUser·p0.999:  23.134 ms/op
                 createUser·p0.9999: 28.279 ms/op
                 createUser·p1.00:   29.688 ms/op

Iteration   3: 3.401 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.298 ms/op
                 createUser·p0.50:   3.305 ms/op
                 createUser·p0.90:   3.817 ms/op
                 createUser·p0.95:   4.309 ms/op
                 createUser·p0.99:   5.464 ms/op
                 createUser·p0.999:  19.098 ms/op
                 createUser·p0.9999: 23.401 ms/op
                 createUser·p1.00:   23.986 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 282291
  mean =      3.398 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12215 
    [ 2.500,  5.000) = 264124 
    [ 5.000,  7.500) = 4960 
    [ 7.500, 10.000) = 507 
    [10.000, 12.500) = 80 
    [12.500, 15.000) = 39 
    [15.000, 17.500) = 42 
    [17.500, 20.000) = 51 
    [20.000, 22.500) = 140 
    [22.500, 25.000) = 78 
    [25.000, 27.500) = 21 
    [27.500, 30.000) = 24 
    [30.000, 32.500) = 8 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.807 ms/op
     p(50.0000) =      3.301 ms/op
     p(90.0000) =      3.792 ms/op
     p(95.0000) =      4.235 ms/op
     p(99.0000) =      5.505 ms/op
     p(99.9000) =     19.815 ms/op
     p(99.9900) =     28.140 ms/op
     p(99.9990) =     32.630 ms/op
     p(99.9999) =     33.391 ms/op
    p(100.0000) =     33.391 ms/op


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
# Warmup Iteration   1: 7.936 ±(99.9%) 0.119 ms/op
# Warmup Iteration   2: 3.771 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.313 ±(99.9%) 0.008 ms/op
Iteration   1: 3.456 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.696 ms/op
                 existUser·p0.50:   3.314 ms/op
                 existUser·p0.90:   4.067 ms/op
                 existUser·p0.95:   4.391 ms/op
                 existUser·p0.99:   5.549 ms/op
                 existUser·p0.999:  8.969 ms/op
                 existUser·p0.9999: 21.430 ms/op
                 existUser·p1.00:   21.660 ms/op

Iteration   2: 3.231 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.251 ms/op
                 existUser·p0.50:   3.195 ms/op
                 existUser·p0.90:   3.408 ms/op
                 existUser·p0.95:   3.682 ms/op
                 existUser·p0.99:   5.628 ms/op
                 existUser·p0.999:  10.453 ms/op
                 existUser·p0.9999: 27.139 ms/op
                 existUser·p1.00:   27.951 ms/op

Iteration   3: 3.250 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.493 ms/op
                 existUser·p0.50:   3.228 ms/op
                 existUser·p0.90:   3.442 ms/op
                 existUser·p0.95:   3.621 ms/op
                 existUser·p0.99:   5.677 ms/op
                 existUser·p0.999:  9.139 ms/op
                 existUser·p0.9999: 26.362 ms/op
                 existUser·p1.00:   26.870 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 289765
  mean =      3.309 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14623 
    [ 2.500,  5.000) = 269560 
    [ 5.000,  7.500) = 4823 
    [ 7.500, 10.000) = 445 
    [10.000, 12.500) = 57 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 42 
    [20.000, 22.500) = 70 
    [22.500, 25.000) = 87 
    [25.000, 27.500) = 55 

  Percentiles, ms/op:
      p(0.0000) =      1.251 ms/op
     p(50.0000) =      3.236 ms/op
     p(90.0000) =      3.707 ms/op
     p(95.0000) =      4.051 ms/op
     p(99.0000) =      5.622 ms/op
     p(99.9000) =     10.174 ms/op
     p(99.9900) =     26.576 ms/op
     p(99.9990) =     27.502 ms/op
     p(99.9999) =     27.951 ms/op
    p(100.0000) =     27.951 ms/op


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
# Warmup Iteration   1: 8.677 ±(99.9%) 0.115 ms/op
# Warmup Iteration   2: 3.667 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.495 ±(99.9%) 0.010 ms/op
Iteration   1: 3.293 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.450 ms/op
                 getUser·p0.50:   3.248 ms/op
                 getUser·p0.90:   3.600 ms/op
                 getUser·p0.95:   3.887 ms/op
                 getUser·p0.99:   5.505 ms/op
                 getUser·p0.999:  12.567 ms/op
                 getUser·p0.9999: 24.950 ms/op
                 getUser·p1.00:   25.428 ms/op

Iteration   2: 3.529 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.483 ms/op
                 getUser·p0.50:   3.359 ms/op
                 getUser·p0.90:   4.194 ms/op
                 getUser·p0.95:   4.555 ms/op
                 getUser·p0.99:   6.242 ms/op
                 getUser·p0.999:  22.951 ms/op
                 getUser·p0.9999: 27.749 ms/op
                 getUser·p1.00:   28.017 ms/op

Iteration   3: 3.472 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.583 ms/op
                 getUser·p0.50:   3.367 ms/op
                 getUser·p0.90:   4.055 ms/op
                 getUser·p0.95:   4.383 ms/op
                 getUser·p0.99:   5.652 ms/op
                 getUser·p0.999:  21.955 ms/op
                 getUser·p0.9999: 25.919 ms/op
                 getUser·p1.00:   27.165 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 279827
  mean =      3.428 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17419 
    [ 2.500,  5.000) = 255430 
    [ 5.000,  7.500) = 6136 
    [ 7.500, 10.000) = 511 
    [10.000, 12.500) = 16 
    [12.500, 15.000) = 27 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 64 
    [22.500, 25.000) = 128 
    [25.000, 27.500) = 84 

  Percentiles, ms/op:
      p(0.0000) =      0.583 ms/op
     p(50.0000) =      3.326 ms/op
     p(90.0000) =      4.022 ms/op
     p(95.0000) =      4.325 ms/op
     p(99.0000) =      5.857 ms/op
     p(99.9000) =     20.546 ms/op
     p(99.9900) =     26.804 ms/op
     p(99.9990) =     27.958 ms/op
     p(99.9999) =     28.017 ms/op
    p(100.0000) =     28.017 ms/op


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
# Warmup Iteration   1: 9.568 ±(99.9%) 0.129 ms/op
# Warmup Iteration   2: 4.366 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.047 ±(99.9%) 0.013 ms/op
Iteration   1: 4.036 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.907 ms/op
                 listUser·p0.50:   3.858 ms/op
                 listUser·p0.90:   4.366 ms/op
                 listUser·p0.95:   4.825 ms/op
                 listUser·p0.99:   7.455 ms/op
                 listUser·p0.999:  16.588 ms/op
                 listUser·p0.9999: 27.045 ms/op
                 listUser·p1.00:   32.899 ms/op

Iteration   2: 4.024 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.183 ms/op
                 listUser·p0.50:   3.834 ms/op
                 listUser·p0.90:   4.424 ms/op
                 listUser·p0.95:   4.709 ms/op
                 listUser·p0.99:   7.553 ms/op
                 listUser·p0.999:  16.237 ms/op
                 listUser·p0.9999: 19.005 ms/op
                 listUser·p1.00:   20.316 ms/op

Iteration   3: 3.917 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.294 ms/op
                 listUser·p0.50:   3.793 ms/op
                 listUser·p0.90:   4.276 ms/op
                 listUser·p0.95:   4.473 ms/op
                 listUser·p0.99:   6.720 ms/op
                 listUser·p0.999:  15.106 ms/op
                 listUser·p0.9999: 18.864 ms/op
                 listUser·p1.00:   20.972 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 240337
  mean =      3.992 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 54 
    [ 2.500,  5.000) = 231987 
    [ 5.000,  7.500) = 6215 
    [ 7.500, 10.000) = 1440 
    [10.000, 12.500) = 164 
    [12.500, 15.000) = 137 
    [15.000, 17.500) = 213 
    [17.500, 20.000) = 77 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 21 
    [27.500, 30.000) = 1 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.907 ms/op
     p(50.0000) =      3.826 ms/op
     p(90.0000) =      4.358 ms/op
     p(95.0000) =      4.620 ms/op
     p(99.0000) =      7.324 ms/op
     p(99.9000) =     15.892 ms/op
     p(99.9900) =     24.900 ms/op
     p(99.9990) =     27.459 ms/op
     p(99.9999) =     32.899 ms/op
    p(100.0000) =     32.899 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.271 ± 0.839  ops/ms
ClientPb.existUser                       thrpt       3  10.078 ± 2.078  ops/ms
ClientPb.getUser                         thrpt       3   9.607 ± 1.677  ops/ms
ClientPb.listUser                        thrpt       3   7.963 ± 0.506  ops/ms
ClientPb.createUser                       avgt       3   3.376 ± 0.910   ms/op
ClientPb.existUser                        avgt       3   3.363 ± 1.050   ms/op
ClientPb.getUser                          avgt       3   3.299 ± 0.511   ms/op
ClientPb.listUser                         avgt       3   3.975 ± 1.246   ms/op
ClientPb.createUser                     sample  282291   3.398 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.807           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.301           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.792           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.235           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.505           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.815           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.140           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.391           ms/op
ClientPb.existUser                      sample  289765   3.309 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.251           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.236           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.707           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.051           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.622           ms/op
ClientPb.existUser:existUser·p0.999     sample          10.174           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.576           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.951           ms/op
ClientPb.getUser                        sample  279827   3.428 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.583           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.326           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.022           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.325           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.857           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.546           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.804           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.017           ms/op
ClientPb.listUser                       sample  240337   3.992 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.907           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.826           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.358           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.620           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.324           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.892           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.900           ms/op
ClientPb.listUser:listUser·p1.00        sample          32.899           ms/op
