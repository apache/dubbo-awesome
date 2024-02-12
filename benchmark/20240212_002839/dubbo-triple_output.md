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
# Warmup Iteration   1: 5.286 ops/ms
# Warmup Iteration   2: 12.157 ops/ms
# Warmup Iteration   3: 12.304 ops/ms
Iteration   1: 12.482 ops/ms
Iteration   2: 12.621 ops/ms
Iteration   3: 12.515 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.539 ±(99.9%) 1.322 ops/ms [Average]
  (min, avg, max) = (12.482, 12.539, 12.621), stdev = 0.072
  CI (99.9%): [11.217, 13.862] (assumes normal distribution)


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
# Warmup Iteration   1: 8.213 ops/ms
# Warmup Iteration   2: 12.830 ops/ms
# Warmup Iteration   3: 13.019 ops/ms
Iteration   1: 12.916 ops/ms
Iteration   2: 13.071 ops/ms
Iteration   3: 12.774 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.920 ±(99.9%) 2.708 ops/ms [Average]
  (min, avg, max) = (12.774, 12.920, 13.071), stdev = 0.148
  CI (99.9%): [10.212, 15.628] (assumes normal distribution)


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
# Warmup Iteration   1: 7.171 ops/ms
# Warmup Iteration   2: 12.440 ops/ms
# Warmup Iteration   3: 12.486 ops/ms
Iteration   1: 12.672 ops/ms
Iteration   2: 12.637 ops/ms
Iteration   3: 12.626 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.645 ±(99.9%) 0.441 ops/ms [Average]
  (min, avg, max) = (12.626, 12.645, 12.672), stdev = 0.024
  CI (99.9%): [12.204, 13.086] (assumes normal distribution)


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
# Warmup Iteration   1: 6.525 ops/ms
# Warmup Iteration   2: 10.352 ops/ms
# Warmup Iteration   3: 10.455 ops/ms
Iteration   1: 10.595 ops/ms
Iteration   2: 10.519 ops/ms
Iteration   3: 10.565 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.560 ±(99.9%) 0.706 ops/ms [Average]
  (min, avg, max) = (10.519, 10.560, 10.595), stdev = 0.039
  CI (99.9%): [9.854, 11.265] (assumes normal distribution)


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
# Warmup Iteration   1: 4.101 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.584 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.564 ±(99.9%) 0.004 ms/op
Iteration   1: 2.534 ±(99.9%) 0.005 ms/op
Iteration   2: 2.536 ±(99.9%) 0.004 ms/op
Iteration   3: 2.550 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.540 ±(99.9%) 0.159 ms/op [Average]
  (min, avg, max) = (2.534, 2.540, 2.550), stdev = 0.009
  CI (99.9%): [2.381, 2.700] (assumes normal distribution)


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
# Warmup Iteration   1: 3.571 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.474 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.486 ±(99.9%) 0.004 ms/op
Iteration   1: 2.489 ±(99.9%) 0.004 ms/op
Iteration   2: 2.477 ±(99.9%) 0.004 ms/op
Iteration   3: 2.510 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.492 ±(99.9%) 0.306 ms/op [Average]
  (min, avg, max) = (2.477, 2.492, 2.510), stdev = 0.017
  CI (99.9%): [2.186, 2.798] (assumes normal distribution)


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
# Warmup Iteration   1: 3.962 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.572 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.538 ±(99.9%) 0.004 ms/op
Iteration   1: 2.506 ±(99.9%) 0.005 ms/op
Iteration   2: 2.476 ±(99.9%) 0.004 ms/op
Iteration   3: 2.494 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.492 ±(99.9%) 0.277 ms/op [Average]
  (min, avg, max) = (2.476, 2.492, 2.506), stdev = 0.015
  CI (99.9%): [2.214, 2.769] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:23
# Fork: 1 of 1
# Warmup Iteration   1: 4.540 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.022 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.996 ±(99.9%) 0.006 ms/op
Iteration   1: 2.971 ±(99.9%) 0.005 ms/op
Iteration   2: 2.996 ±(99.9%) 0.006 ms/op
Iteration   3: 2.979 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.982 ±(99.9%) 0.235 ms/op [Average]
  (min, avg, max) = (2.971, 2.982, 2.996), stdev = 0.013
  CI (99.9%): [2.748, 3.217] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:18
# Fork: 1 of 1
# Warmup Iteration   1: 4.104 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.722 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.535 ±(99.9%) 0.005 ms/op
Iteration   1: 2.509 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.911 ms/op
                 createUser·p0.50:   2.593 ms/op
                 createUser·p0.90:   3.035 ms/op
                 createUser·p0.95:   3.142 ms/op
                 createUser·p0.99:   3.654 ms/op
                 createUser·p0.999:  10.892 ms/op
                 createUser·p0.9999: 14.123 ms/op
                 createUser·p1.00:   14.352 ms/op

Iteration   2: 2.528 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.980 ms/op
                 createUser·p0.50:   2.613 ms/op
                 createUser·p0.90:   3.064 ms/op
                 createUser·p0.95:   3.191 ms/op
                 createUser·p0.99:   3.977 ms/op
                 createUser·p0.999:  8.905 ms/op
                 createUser·p0.9999: 12.540 ms/op
                 createUser·p1.00:   12.960 ms/op

Iteration   3: 2.507 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.938 ms/op
                 createUser·p0.50:   2.601 ms/op
                 createUser·p0.90:   3.039 ms/op
                 createUser·p0.95:   3.142 ms/op
                 createUser·p0.99:   3.703 ms/op
                 createUser·p0.999:  8.323 ms/op
                 createUser·p0.9999: 10.330 ms/op
                 createUser·p1.00:   10.977 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 381385
  mean =      2.515 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 39 
    [ 1.250,  2.500) = 183338 
    [ 2.500,  3.750) = 194065 
    [ 3.750,  5.000) = 3110 
    [ 5.000,  6.250) = 415 
    [ 6.250,  7.500) = 28 
    [ 7.500,  8.750) = 21 
    [ 8.750, 10.000) = 148 
    [10.000, 11.250) = 65 
    [11.250, 12.500) = 75 
    [12.500, 13.750) = 65 
    [13.750, 15.000) = 16 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.911 ms/op
     p(50.0000) =      2.601 ms/op
     p(90.0000) =      3.047 ms/op
     p(95.0000) =      3.158 ms/op
     p(99.0000) =      3.768 ms/op
     p(99.9000) =      8.379 ms/op
     p(99.9900) =     13.201 ms/op
     p(99.9990) =     14.241 ms/op
     p(99.9999) =     14.352 ms/op
    p(100.0000) =     14.352 ms/op


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
# Warmup Iteration   1: 3.795 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.481 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.472 ±(99.9%) 0.005 ms/op
Iteration   1: 2.473 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.031 ms/op
                 existUser·p0.50:   2.527 ms/op
                 existUser·p0.90:   3.002 ms/op
                 existUser·p0.95:   3.101 ms/op
                 existUser·p0.99:   3.502 ms/op
                 existUser·p0.999:  8.224 ms/op
                 existUser·p0.9999: 13.600 ms/op
                 existUser·p1.00:   14.156 ms/op

Iteration   2: 2.463 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.239 ms/op
                 existUser·p0.50:   2.576 ms/op
                 existUser·p0.90:   2.990 ms/op
                 existUser·p0.95:   3.084 ms/op
                 existUser·p0.99:   3.580 ms/op
                 existUser·p0.999:  6.657 ms/op
                 existUser·p0.9999: 12.306 ms/op
                 existUser·p1.00:   12.714 ms/op

Iteration   3: 2.482 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.940 ms/op
                 existUser·p0.50:   2.560 ms/op
                 existUser·p0.90:   3.019 ms/op
                 existUser·p0.95:   3.129 ms/op
                 existUser·p0.99:   3.740 ms/op
                 existUser·p0.999:  7.367 ms/op
                 existUser·p0.9999: 11.848 ms/op
                 existUser·p1.00:   12.861 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 387802
  mean =      2.473 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 22 
    [ 1.250,  2.500) = 190263 
    [ 2.500,  3.750) = 194453 
    [ 3.750,  5.000) = 2320 
    [ 5.000,  6.250) = 332 
    [ 6.250,  7.500) = 26 
    [ 7.500,  8.750) = 12 
    [ 8.750, 10.000) = 103 
    [10.000, 11.250) = 83 
    [11.250, 12.500) = 121 
    [12.500, 13.750) = 61 
    [13.750, 15.000) = 6 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.940 ms/op
     p(50.0000) =      2.556 ms/op
     p(90.0000) =      3.002 ms/op
     p(95.0000) =      3.105 ms/op
     p(99.0000) =      3.617 ms/op
     p(99.9000) =      6.726 ms/op
     p(99.9900) =     12.894 ms/op
     p(99.9990) =     13.883 ms/op
     p(99.9999) =     14.156 ms/op
    p(100.0000) =     14.156 ms/op


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
# Warmup Iteration   1: 4.020 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.589 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.512 ±(99.9%) 0.006 ms/op
Iteration   1: 2.519 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.893 ms/op
                 getUser·p0.50:   2.572 ms/op
                 getUser·p0.90:   3.064 ms/op
                 getUser·p0.95:   3.178 ms/op
                 getUser·p0.99:   3.830 ms/op
                 getUser·p0.999:  10.551 ms/op
                 getUser·p0.9999: 13.096 ms/op
                 getUser·p1.00:   13.959 ms/op

Iteration   2: 2.518 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.717 ms/op
                 getUser·p0.50:   2.552 ms/op
                 getUser·p0.90:   3.072 ms/op
                 getUser·p0.95:   3.224 ms/op
                 getUser·p0.99:   4.057 ms/op
                 getUser·p0.999:  5.711 ms/op
                 getUser·p0.9999: 12.309 ms/op
                 getUser·p1.00:   14.008 ms/op

Iteration   3: 2.517 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.032 ms/op
                 getUser·p0.50:   2.552 ms/op
                 getUser·p0.90:   3.060 ms/op
                 getUser·p0.95:   3.203 ms/op
                 getUser·p0.99:   4.022 ms/op
                 getUser·p0.999:  8.552 ms/op
                 getUser·p0.9999: 18.547 ms/op
                 getUser·p1.00:   19.562 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 380884
  mean =      2.518 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 62 
    [ 1.250,  2.500) = 186437 
    [ 2.500,  3.750) = 188908 
    [ 3.750,  5.000) = 4451 
    [ 5.000,  6.250) = 606 
    [ 6.250,  7.500) = 58 
    [ 7.500,  8.750) = 23 
    [ 8.750, 10.000) = 92 
    [10.000, 11.250) = 44 
    [11.250, 12.500) = 97 
    [12.500, 13.750) = 71 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 6 
    [17.500, 18.750) = 20 

  Percentiles, ms/op:
      p(0.0000) =      0.717 ms/op
     p(50.0000) =      2.556 ms/op
     p(90.0000) =      3.064 ms/op
     p(95.0000) =      3.199 ms/op
     p(99.0000) =      3.965 ms/op
     p(99.9000) =      7.062 ms/op
     p(99.9900) =     13.444 ms/op
     p(99.9990) =     19.333 ms/op
     p(99.9999) =     19.562 ms/op
    p(100.0000) =     19.562 ms/op


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
# Warmup Iteration   1: 4.662 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.081 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.021 ±(99.9%) 0.009 ms/op
Iteration   1: 3.001 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.818 ms/op
                 listUser·p0.50:   2.945 ms/op
                 listUser·p0.90:   3.867 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   5.620 ms/op
                 listUser·p0.999:  8.692 ms/op
                 listUser·p0.9999: 10.617 ms/op
                 listUser·p1.00:   10.961 ms/op

Iteration   2: 3.031 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.922 ms/op
                 listUser·p0.50:   2.974 ms/op
                 listUser·p0.90:   3.875 ms/op
                 listUser·p0.95:   4.383 ms/op
                 listUser·p0.99:   5.571 ms/op
                 listUser·p0.999:  9.241 ms/op
                 listUser·p0.9999: 10.508 ms/op
                 listUser·p1.00:   11.321 ms/op

Iteration   3: 3.005 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.818 ms/op
                 listUser·p0.50:   2.949 ms/op
                 listUser·p0.90:   3.867 ms/op
                 listUser·p0.95:   4.334 ms/op
                 listUser·p0.99:   5.489 ms/op
                 listUser·p0.999:  9.585 ms/op
                 listUser·p0.9999: 11.491 ms/op
                 listUser·p1.00:   12.714 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 318371
  mean =      3.012 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 131 
    [ 1.250,  2.500) = 91646 
    [ 2.500,  3.750) = 188625 
    [ 3.750,  5.000) = 30945 
    [ 5.000,  6.250) = 5765 
    [ 6.250,  7.500) = 622 
    [ 7.500,  8.750) = 216 
    [ 8.750, 10.000) = 272 
    [10.000, 11.250) = 136 
    [11.250, 12.500) = 12 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.818 ms/op
     p(50.0000) =      2.957 ms/op
     p(90.0000) =      3.871 ms/op
     p(95.0000) =      4.375 ms/op
     p(99.0000) =      5.562 ms/op
     p(99.9000) =      9.191 ms/op
     p(99.9900) =     10.770 ms/op
     p(99.9990) =     11.804 ms/op
     p(99.9999) =     12.714 ms/op
    p(100.0000) =     12.714 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.539 ± 1.322  ops/ms
ClientPb.existUser                       thrpt       3  12.920 ± 2.708  ops/ms
ClientPb.getUser                         thrpt       3  12.645 ± 0.441  ops/ms
ClientPb.listUser                        thrpt       3  10.560 ± 0.706  ops/ms
ClientPb.createUser                       avgt       3   2.540 ± 0.159   ms/op
ClientPb.existUser                        avgt       3   2.492 ± 0.306   ms/op
ClientPb.getUser                          avgt       3   2.492 ± 0.277   ms/op
ClientPb.listUser                         avgt       3   2.982 ± 0.235   ms/op
ClientPb.createUser                     sample  381385   2.515 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.911           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.601           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.047           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.158           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.768           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.379           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.201           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.352           ms/op
ClientPb.existUser                      sample  387802   2.473 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.940           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.556           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.002           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.105           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.617           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.726           ms/op
ClientPb.existUser:existUser·p0.9999    sample          12.894           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.156           ms/op
ClientPb.getUser                        sample  380884   2.518 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.717           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.556           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.064           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.199           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.965           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.062           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.444           ms/op
ClientPb.getUser:getUser·p1.00          sample          19.562           ms/op
ClientPb.listUser                       sample  318371   3.012 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.818           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.957           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.871           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.375           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.562           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.191           ms/op
ClientPb.listUser:listUser·p0.9999      sample          10.770           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.714           ms/op
