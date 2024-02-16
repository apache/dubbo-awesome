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
# Warmup Iteration   1: 5.314 ops/ms
# Warmup Iteration   2: 12.378 ops/ms
# Warmup Iteration   3: 12.736 ops/ms
Iteration   1: 12.885 ops/ms
Iteration   2: 13.019 ops/ms
Iteration   3: 12.992 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.965 ±(99.9%) 1.293 ops/ms [Average]
  (min, avg, max) = (12.885, 12.965, 13.019), stdev = 0.071
  CI (99.9%): [11.672, 14.258] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 8.747 ops/ms
# Warmup Iteration   2: 13.258 ops/ms
# Warmup Iteration   3: 13.276 ops/ms
Iteration   1: 13.315 ops/ms
Iteration   2: 13.309 ops/ms
Iteration   3: 13.212 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.279 ±(99.9%) 1.048 ops/ms [Average]
  (min, avg, max) = (13.212, 13.279, 13.315), stdev = 0.057
  CI (99.9%): [12.230, 14.327] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.927 ops/ms
# Warmup Iteration   2: 12.946 ops/ms
# Warmup Iteration   3: 13.141 ops/ms
Iteration   1: 13.216 ops/ms
Iteration   2: 13.104 ops/ms
Iteration   3: 13.183 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.167 ±(99.9%) 1.054 ops/ms [Average]
  (min, avg, max) = (13.104, 13.167, 13.216), stdev = 0.058
  CI (99.9%): [12.113, 14.222] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:44
# Fork: 1 of 1
# Warmup Iteration   1: 6.659 ops/ms
# Warmup Iteration   2: 10.630 ops/ms
# Warmup Iteration   3: 10.793 ops/ms
Iteration   1: 10.731 ops/ms
Iteration   2: 10.780 ops/ms
Iteration   3: 10.825 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.779 ±(99.9%) 0.861 ops/ms [Average]
  (min, avg, max) = (10.731, 10.779, 10.825), stdev = 0.047
  CI (99.9%): [9.918, 11.640] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:39
# Fork: 1 of 1
# Warmup Iteration   1: 4.015 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 2.529 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.467 ±(99.9%) 0.004 ms/op
Iteration   1: 2.462 ±(99.9%) 0.004 ms/op
Iteration   2: 2.459 ±(99.9%) 0.005 ms/op
Iteration   3: 2.483 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.468 ±(99.9%) 0.239 ms/op [Average]
  (min, avg, max) = (2.459, 2.468, 2.483), stdev = 0.013
  CI (99.9%): [2.230, 2.707] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:34
# Fork: 1 of 1
# Warmup Iteration   1: 3.679 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.475 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.457 ±(99.9%) 0.004 ms/op
Iteration   1: 2.452 ±(99.9%) 0.003 ms/op
Iteration   2: 2.459 ±(99.9%) 0.004 ms/op
Iteration   3: 2.471 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.461 ±(99.9%) 0.178 ms/op [Average]
  (min, avg, max) = (2.452, 2.461, 2.471), stdev = 0.010
  CI (99.9%): [2.283, 2.638] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:29
# Fork: 1 of 1
# Warmup Iteration   1: 4.095 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.599 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.483 ±(99.9%) 0.004 ms/op
Iteration   1: 2.475 ±(99.9%) 0.004 ms/op
Iteration   2: 2.455 ±(99.9%) 0.005 ms/op
Iteration   3: 2.475 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.468 ±(99.9%) 0.214 ms/op [Average]
  (min, avg, max) = (2.455, 2.468, 2.475), stdev = 0.012
  CI (99.9%): [2.254, 2.683] (assumes normal distribution)


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
# Warmup Iteration   1: 4.741 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 2.955 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.947 ±(99.9%) 0.006 ms/op
Iteration   1: 2.999 ±(99.9%) 0.006 ms/op
Iteration   2: 2.960 ±(99.9%) 0.005 ms/op
Iteration   3: 2.965 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.975 ±(99.9%) 0.386 ms/op [Average]
  (min, avg, max) = (2.960, 2.975, 2.999), stdev = 0.021
  CI (99.9%): [2.589, 3.361] (assumes normal distribution)


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
# Warmup Iteration   1: 4.212 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.621 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.535 ±(99.9%) 0.006 ms/op
Iteration   1: 2.470 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.942 ms/op
                 createUser·p0.50:   2.548 ms/op
                 createUser·p0.90:   2.998 ms/op
                 createUser·p0.95:   3.109 ms/op
                 createUser·p0.99:   3.559 ms/op
                 createUser·p0.999:  6.018 ms/op
                 createUser·p0.9999: 13.363 ms/op
                 createUser·p1.00:   13.992 ms/op

Iteration   2: 2.473 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.916 ms/op
                 createUser·p0.50:   2.544 ms/op
                 createUser·p0.90:   3.002 ms/op
                 createUser·p0.95:   3.117 ms/op
                 createUser·p0.99:   3.620 ms/op
                 createUser·p0.999:  9.676 ms/op
                 createUser·p0.9999: 11.749 ms/op
                 createUser·p1.00:   12.419 ms/op

Iteration   3: 2.473 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.957 ms/op
                 createUser·p0.50:   2.531 ms/op
                 createUser·p0.90:   2.998 ms/op
                 createUser·p0.95:   3.125 ms/op
                 createUser·p0.99:   3.826 ms/op
                 createUser·p0.999:  8.582 ms/op
                 createUser·p0.9999: 10.127 ms/op
                 createUser·p1.00:   10.895 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 387874
  mean =      2.472 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 41 
    [ 1.250,  2.500) = 190055 
    [ 2.500,  3.750) = 194492 
    [ 3.750,  5.000) = 2560 
    [ 5.000,  6.250) = 242 
    [ 6.250,  7.500) = 48 
    [ 7.500,  8.750) = 34 
    [ 8.750, 10.000) = 143 
    [10.000, 11.250) = 83 
    [11.250, 12.500) = 104 
    [12.500, 13.750) = 64 
    [13.750, 15.000) = 8 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.916 ms/op
     p(50.0000) =      2.540 ms/op
     p(90.0000) =      3.002 ms/op
     p(95.0000) =      3.117 ms/op
     p(99.0000) =      3.658 ms/op
     p(99.9000) =      8.980 ms/op
     p(99.9900) =     12.996 ms/op
     p(99.9990) =     13.945 ms/op
     p(99.9999) =     13.992 ms/op
    p(100.0000) =     13.992 ms/op


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
# Warmup Iteration   1: 3.591 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.446 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.413 ±(99.9%) 0.005 ms/op
Iteration   1: 2.378 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.813 ms/op
                 existUser·p0.50:   2.367 ms/op
                 existUser·p0.90:   2.900 ms/op
                 existUser·p0.95:   3.023 ms/op
                 existUser·p0.99:   3.711 ms/op
                 existUser·p0.999:  7.693 ms/op
                 existUser·p0.9999: 13.650 ms/op
                 existUser·p1.00:   14.352 ms/op

Iteration   2: 2.387 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.922 ms/op
                 existUser·p0.50:   2.445 ms/op
                 existUser·p0.90:   2.892 ms/op
                 existUser·p0.95:   2.994 ms/op
                 existUser·p0.99:   3.559 ms/op
                 existUser·p0.999:  8.260 ms/op
                 existUser·p0.9999: 13.785 ms/op
                 existUser·p1.00:   14.778 ms/op

Iteration   3: 2.389 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.985 ms/op
                 existUser·p0.50:   2.376 ms/op
                 existUser·p0.90:   2.933 ms/op
                 existUser·p0.95:   3.047 ms/op
                 existUser·p0.99:   3.613 ms/op
                 existUser·p0.999:  7.405 ms/op
                 existUser·p0.9999: 10.371 ms/op
                 existUser·p1.00:   12.747 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 402048
  mean =      2.385 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 129 
    [ 1.250,  2.500) = 215825 
    [ 2.500,  3.750) = 182760 
    [ 3.750,  5.000) = 2521 
    [ 5.000,  6.250) = 326 
    [ 6.250,  7.500) = 71 
    [ 7.500,  8.750) = 29 
    [ 8.750, 10.000) = 79 
    [10.000, 11.250) = 92 
    [11.250, 12.500) = 96 
    [12.500, 13.750) = 97 
    [13.750, 15.000) = 23 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.813 ms/op
     p(50.0000) =      2.388 ms/op
     p(90.0000) =      2.908 ms/op
     p(95.0000) =      3.023 ms/op
     p(99.0000) =      3.629 ms/op
     p(99.9000) =      8.124 ms/op
     p(99.9900) =     13.386 ms/op
     p(99.9990) =     14.368 ms/op
     p(99.9999) =     14.778 ms/op
    p(100.0000) =     14.778 ms/op


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
# Warmup Iteration   1: 3.901 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.535 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.482 ±(99.9%) 0.005 ms/op
Iteration   1: 2.475 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.900 ms/op
                 getUser·p0.50:   2.482 ms/op
                 getUser·p0.90:   3.019 ms/op
                 getUser·p0.95:   3.142 ms/op
                 getUser·p0.99:   3.752 ms/op
                 getUser·p0.999:  6.410 ms/op
                 getUser·p0.9999: 13.256 ms/op
                 getUser·p1.00:   13.582 ms/op

Iteration   2: 2.462 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.712 ms/op
                 getUser·p0.50:   2.478 ms/op
                 getUser·p0.90:   3.006 ms/op
                 getUser·p0.95:   3.133 ms/op
                 getUser·p0.99:   3.736 ms/op
                 getUser·p0.999:  5.194 ms/op
                 getUser·p0.9999: 11.584 ms/op
                 getUser·p1.00:   13.107 ms/op

Iteration   3: 2.444 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.817 ms/op
                 getUser·p0.50:   2.474 ms/op
                 getUser·p0.90:   2.978 ms/op
                 getUser·p0.95:   3.092 ms/op
                 getUser·p0.99:   3.625 ms/op
                 getUser·p0.999:  5.138 ms/op
                 getUser·p0.9999: 10.957 ms/op
                 getUser·p1.00:   11.895 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 389887
  mean =      2.460 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 75 
    [ 1.250,  2.500) = 197448 
    [ 2.500,  3.750) = 188873 
    [ 3.750,  5.000) = 2961 
    [ 5.000,  6.250) = 200 
    [ 6.250,  7.500) = 10 
    [ 7.500,  8.750) = 23 
    [ 8.750, 10.000) = 46 
    [10.000, 11.250) = 80 
    [11.250, 12.500) = 91 
    [12.500, 13.750) = 80 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.712 ms/op
     p(50.0000) =      2.474 ms/op
     p(90.0000) =      3.002 ms/op
     p(95.0000) =      3.125 ms/op
     p(99.0000) =      3.699 ms/op
     p(99.9000) =      5.325 ms/op
     p(99.9900) =     12.911 ms/op
     p(99.9990) =     13.520 ms/op
     p(99.9999) =     13.582 ms/op
    p(100.0000) =     13.582 ms/op


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
# Warmup Iteration   1: 4.557 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.036 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.992 ±(99.9%) 0.008 ms/op
Iteration   1: 2.998 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.871 ms/op
                 listUser·p0.50:   2.937 ms/op
                 listUser·p0.90:   3.895 ms/op
                 listUser·p0.95:   4.383 ms/op
                 listUser·p0.99:   5.538 ms/op
                 listUser·p0.999:  9.317 ms/op
                 listUser·p0.9999: 10.710 ms/op
                 listUser·p1.00:   11.796 ms/op

Iteration   2: 2.993 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.869 ms/op
                 listUser·p0.50:   2.937 ms/op
                 listUser·p0.90:   3.850 ms/op
                 listUser·p0.95:   4.350 ms/op
                 listUser·p0.99:   5.407 ms/op
                 listUser·p0.999:  8.719 ms/op
                 listUser·p0.9999: 10.676 ms/op
                 listUser·p1.00:   11.436 ms/op

Iteration   3: 2.968 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.934 ms/op
                 listUser·p0.50:   2.904 ms/op
                 listUser·p0.90:   3.801 ms/op
                 listUser·p0.95:   4.301 ms/op
                 listUser·p0.99:   5.480 ms/op
                 listUser·p0.999:  8.749 ms/op
                 listUser·p0.9999: 10.841 ms/op
                 listUser·p1.00:   11.633 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 321218
  mean =      2.986 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 142 
    [ 1.250,  2.500) = 94427 
    [ 2.500,  3.750) = 189257 
    [ 3.750,  5.000) = 30819 
    [ 5.000,  6.250) = 5424 
    [ 6.250,  7.500) = 489 
    [ 7.500,  8.750) = 315 
    [ 8.750, 10.000) = 221 
    [10.000, 11.250) = 106 
    [11.250, 12.500) = 18 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.869 ms/op
     p(50.0000) =      2.925 ms/op
     p(90.0000) =      3.846 ms/op
     p(95.0000) =      4.342 ms/op
     p(99.0000) =      5.480 ms/op
     p(99.9000) =      8.913 ms/op
     p(99.9900) =     10.779 ms/op
     p(99.9990) =     11.564 ms/op
     p(99.9999) =     11.796 ms/op
    p(100.0000) =     11.796 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.965 ± 1.293  ops/ms
ClientPb.existUser                       thrpt       3  13.279 ± 1.048  ops/ms
ClientPb.getUser                         thrpt       3  13.167 ± 1.054  ops/ms
ClientPb.listUser                        thrpt       3  10.779 ± 0.861  ops/ms
ClientPb.createUser                       avgt       3   2.468 ± 0.239   ms/op
ClientPb.existUser                        avgt       3   2.461 ± 0.178   ms/op
ClientPb.getUser                          avgt       3   2.468 ± 0.214   ms/op
ClientPb.listUser                         avgt       3   2.975 ± 0.386   ms/op
ClientPb.createUser                     sample  387874   2.472 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.916           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.540           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.002           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.117           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.658           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.980           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.996           ms/op
ClientPb.createUser:createUser·p1.00    sample          13.992           ms/op
ClientPb.existUser                      sample  402048   2.385 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.813           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.388           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.908           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.023           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.629           ms/op
ClientPb.existUser:existUser·p0.999     sample           8.124           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.386           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.778           ms/op
ClientPb.getUser                        sample  389887   2.460 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.712           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.474           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.002           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.125           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.699           ms/op
ClientPb.getUser:getUser·p0.999         sample           5.325           ms/op
ClientPb.getUser:getUser·p0.9999        sample          12.911           ms/op
ClientPb.getUser:getUser·p1.00          sample          13.582           ms/op
ClientPb.listUser                       sample  321218   2.986 ± 0.004   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.869           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.925           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.846           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.342           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.480           ms/op
ClientPb.listUser:listUser·p0.999       sample           8.913           ms/op
ClientPb.listUser:listUser·p0.9999      sample          10.779           ms/op
ClientPb.listUser:listUser·p1.00        sample          11.796           ms/op
