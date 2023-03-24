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
# Warmup Iteration   1: 2.652 ops/ms
# Warmup Iteration   2: 6.261 ops/ms
# Warmup Iteration   3: 9.153 ops/ms
Iteration   1: 9.994 ops/ms
Iteration   2: 10.097 ops/ms
Iteration   3: 10.345 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  10.145 ±(99.9%) 3.296 ops/ms [Average]
  (min, avg, max) = (9.994, 10.145, 10.345), stdev = 0.181
  CI (99.9%): [6.849, 13.441] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.829 ops/ms
# Warmup Iteration   2: 9.375 ops/ms
# Warmup Iteration   3: 10.646 ops/ms
Iteration   1: 10.009 ops/ms
Iteration   2: 9.770 ops/ms
Iteration   3: 10.093 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.957 ±(99.9%) 3.050 ops/ms [Average]
  (min, avg, max) = (9.770, 9.957, 10.093), stdev = 0.167
  CI (99.9%): [6.907, 13.008] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.423 ops/ms
# Warmup Iteration   2: 9.617 ops/ms
# Warmup Iteration   3: 10.151 ops/ms
Iteration   1: 10.060 ops/ms
Iteration   2: 10.032 ops/ms
Iteration   3: 10.048 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.047 ±(99.9%) 0.254 ops/ms [Average]
  (min, avg, max) = (10.032, 10.047, 10.060), stdev = 0.014
  CI (99.9%): [9.793, 10.300] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.717 ops/ms
# Warmup Iteration   2: 8.018 ops/ms
# Warmup Iteration   3: 8.282 ops/ms
Iteration   1: 8.608 ops/ms
Iteration   2: 8.670 ops/ms
Iteration   3: 8.739 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.672 ±(99.9%) 1.200 ops/ms [Average]
  (min, avg, max) = (8.608, 8.672, 8.739), stdev = 0.066
  CI (99.9%): [7.472, 9.872] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 7.405 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.332 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.325 ±(99.9%) 0.004 ms/op
Iteration   1: 3.204 ±(99.9%) 0.008 ms/op
Iteration   2: 3.104 ±(99.9%) 0.002 ms/op
Iteration   3: 3.063 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.124 ±(99.9%) 1.321 ms/op [Average]
  (min, avg, max) = (3.063, 3.124, 3.204), stdev = 0.072
  CI (99.9%): [1.802, 4.445] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 7.179 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.309 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.113 ±(99.9%) 0.005 ms/op
Iteration   1: 3.006 ±(99.9%) 0.003 ms/op
Iteration   2: 2.952 ±(99.9%) 0.005 ms/op
Iteration   3: 3.008 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.989 ±(99.9%) 0.576 ms/op [Average]
  (min, avg, max) = (2.952, 2.989, 3.008), stdev = 0.032
  CI (99.9%): [2.413, 3.564] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 6.577 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.474 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.227 ±(99.9%) 0.003 ms/op
Iteration   1: 3.184 ±(99.9%) 0.008 ms/op
Iteration   2: 3.223 ±(99.9%) 0.005 ms/op
Iteration   3: 3.125 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.177 ±(99.9%) 0.902 ms/op [Average]
  (min, avg, max) = (3.125, 3.177, 3.223), stdev = 0.049
  CI (99.9%): [2.275, 4.080] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 8.480 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.036 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.816 ±(99.9%) 0.005 ms/op
Iteration   1: 3.689 ±(99.9%) 0.008 ms/op
Iteration   2: 3.640 ±(99.9%) 0.012 ms/op
Iteration   3: 3.685 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.671 ±(99.9%) 0.495 ms/op [Average]
  (min, avg, max) = (3.640, 3.671, 3.689), stdev = 0.027
  CI (99.9%): [3.176, 4.166] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 8.545 ±(99.9%) 0.112 ms/op
# Warmup Iteration   2: 3.751 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.552 ±(99.9%) 0.010 ms/op
Iteration   1: 3.300 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.450 ms/op
                 createUser·p0.50:   3.236 ms/op
                 createUser·p0.90:   3.731 ms/op
                 createUser·p0.95:   4.088 ms/op
                 createUser·p0.99:   5.734 ms/op
                 createUser·p0.999:  12.069 ms/op
                 createUser·p0.9999: 21.309 ms/op
                 createUser·p1.00:   22.577 ms/op

Iteration   2: 3.317 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.616 ms/op
                 createUser·p0.50:   3.256 ms/op
                 createUser·p0.90:   3.604 ms/op
                 createUser·p0.95:   3.850 ms/op
                 createUser·p0.99:   6.128 ms/op
                 createUser·p0.999:  21.352 ms/op
                 createUser·p0.9999: 24.424 ms/op
                 createUser·p1.00:   25.821 ms/op

Iteration   3: 3.498 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.033 ms/op
                 createUser·p0.50:   3.346 ms/op
                 createUser·p0.90:   4.100 ms/op
                 createUser·p0.95:   4.407 ms/op
                 createUser·p0.99:   6.218 ms/op
                 createUser·p0.999:  22.330 ms/op
                 createUser·p0.9999: 29.581 ms/op
                 createUser·p1.00:   30.343 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 284531
  mean =      3.369 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16865 
    [ 2.500,  5.000) = 261550 
    [ 5.000,  7.500) = 4979 
    [ 7.500, 10.000) = 580 
    [10.000, 12.500) = 106 
    [12.500, 15.000) = 61 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 47 
    [20.000, 22.500) = 199 
    [22.500, 25.000) = 78 
    [25.000, 27.500) = 10 
    [27.500, 30.000) = 31 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.033 ms/op
     p(50.0000) =      3.285 ms/op
     p(90.0000) =      3.817 ms/op
     p(95.0000) =      4.211 ms/op
     p(99.0000) =      6.021 ms/op
     p(99.9000) =     20.513 ms/op
     p(99.9900) =     27.820 ms/op
     p(99.9990) =     29.862 ms/op
     p(99.9999) =     30.343 ms/op
    p(100.0000) =     30.343 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 6.999 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 3.268 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.160 ±(99.9%) 0.008 ms/op
Iteration   1: 3.192 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.663 ms/op
                 existUser·p0.50:   3.146 ms/op
                 existUser·p0.90:   3.559 ms/op
                 existUser·p0.95:   3.961 ms/op
                 existUser·p0.99:   5.374 ms/op
                 existUser·p0.999:  10.846 ms/op
                 existUser·p0.9999: 28.648 ms/op
                 existUser·p1.00:   29.131 ms/op

Iteration   2: 3.052 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.442 ms/op
                 existUser·p0.50:   2.970 ms/op
                 existUser·p0.90:   3.297 ms/op
                 existUser·p0.95:   3.465 ms/op
                 existUser·p0.99:   5.267 ms/op
                 existUser·p0.999:  10.334 ms/op
                 existUser·p0.9999: 21.021 ms/op
                 existUser·p1.00:   21.463 ms/op

Iteration   3: 3.053 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.403 ms/op
                 existUser·p0.50:   3.072 ms/op
                 existUser·p0.90:   3.187 ms/op
                 existUser·p0.95:   3.314 ms/op
                 existUser·p0.99:   5.177 ms/op
                 existUser·p0.999:  15.513 ms/op
                 existUser·p0.9999: 21.463 ms/op
                 existUser·p1.00:   22.020 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 309650
  mean =      3.098 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22279 
    [ 2.500,  5.000) = 282143 
    [ 5.000,  7.500) = 4426 
    [ 7.500, 10.000) = 380 
    [10.000, 12.500) = 83 
    [12.500, 15.000) = 42 
    [15.000, 17.500) = 33 
    [17.500, 20.000) = 144 
    [20.000, 22.500) = 88 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 22 

  Percentiles, ms/op:
      p(0.0000) =      0.663 ms/op
     p(50.0000) =      3.076 ms/op
     p(90.0000) =      3.330 ms/op
     p(95.0000) =      3.609 ms/op
     p(99.0000) =      5.317 ms/op
     p(99.9000) =     14.276 ms/op
     p(99.9900) =     25.323 ms/op
     p(99.9990) =     28.928 ms/op
     p(99.9999) =     29.131 ms/op
    p(100.0000) =     29.131 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 7.289 ±(99.9%) 0.079 ms/op
# Warmup Iteration   2: 3.508 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.218 ±(99.9%) 0.009 ms/op
Iteration   1: 3.148 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.274 ms/op
                 getUser·p0.50:   3.002 ms/op
                 getUser·p0.90:   3.453 ms/op
                 getUser·p0.95:   3.953 ms/op
                 getUser·p0.99:   6.152 ms/op
                 getUser·p0.999:  9.590 ms/op
                 getUser·p0.9999: 20.054 ms/op
                 getUser·p1.00:   20.611 ms/op

Iteration   2: 3.210 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.087 ms/op
                 getUser·p0.50:   3.158 ms/op
                 getUser·p0.90:   3.592 ms/op
                 getUser·p0.95:   3.846 ms/op
                 getUser·p0.99:   5.333 ms/op
                 getUser·p0.999:  15.996 ms/op
                 getUser·p0.9999: 24.318 ms/op
                 getUser·p1.00:   25.231 ms/op

Iteration   3: 3.111 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.657 ms/op
                 getUser·p0.50:   2.994 ms/op
                 getUser·p0.90:   3.412 ms/op
                 getUser·p0.95:   3.666 ms/op
                 getUser·p0.99:   5.505 ms/op
                 getUser·p0.999:  15.949 ms/op
                 getUser·p0.9999: 22.765 ms/op
                 getUser·p1.00:   23.298 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 304037
  mean =      3.156 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11967 
    [ 2.500,  5.000) = 285443 
    [ 5.000,  7.500) = 5800 
    [ 7.500, 10.000) = 442 
    [10.000, 12.500) = 27 
    [12.500, 15.000) = 26 
    [15.000, 17.500) = 96 
    [17.500, 20.000) = 120 
    [20.000, 22.500) = 69 
    [22.500, 25.000) = 44 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.087 ms/op
     p(50.0000) =      3.047 ms/op
     p(90.0000) =      3.506 ms/op
     p(95.0000) =      3.797 ms/op
     p(99.0000) =      5.677 ms/op
     p(99.9000) =     15.843 ms/op
     p(99.9900) =     23.121 ms/op
     p(99.9990) =     25.029 ms/op
     p(99.9999) =     25.231 ms/op
    p(100.0000) =     25.231 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 10.306 ±(99.9%) 0.128 ms/op
# Warmup Iteration   2: 4.178 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.807 ±(99.9%) 0.012 ms/op
Iteration   1: 3.698 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.202 ms/op
                 listUser·p0.50:   3.559 ms/op
                 listUser·p0.90:   4.014 ms/op
                 listUser·p0.95:   4.293 ms/op
                 listUser·p0.99:   6.816 ms/op
                 listUser·p0.999:  15.581 ms/op
                 listUser·p0.9999: 19.771 ms/op
                 listUser·p1.00:   21.004 ms/op

Iteration   2: 3.825 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.109 ms/op
                 listUser·p0.50:   3.682 ms/op
                 listUser·p0.90:   4.293 ms/op
                 listUser·p0.95:   4.653 ms/op
                 listUser·p0.99:   7.381 ms/op
                 listUser·p0.999:  13.533 ms/op
                 listUser·p0.9999: 16.378 ms/op
                 listUser·p1.00:   18.350 ms/op

Iteration   3: 3.678 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.208 ms/op
                 listUser·p0.50:   3.539 ms/op
                 listUser·p0.90:   3.940 ms/op
                 listUser·p0.95:   4.149 ms/op
                 listUser·p0.99:   6.980 ms/op
                 listUser·p0.999:  16.155 ms/op
                 listUser·p0.9999: 17.734 ms/op
                 listUser·p1.00:   19.169 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 257142
  mean =      3.733 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 58 
    [ 2.500,  5.000) = 249169 
    [ 5.000,  7.500) = 6039 
    [ 7.500, 10.000) = 1274 
    [10.000, 12.500) = 204 
    [12.500, 15.000) = 177 
    [15.000, 17.500) = 136 
    [17.500, 20.000) = 80 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.202 ms/op
     p(50.0000) =      3.613 ms/op
     p(90.0000) =      4.088 ms/op
     p(95.0000) =      4.407 ms/op
     p(99.0000) =      7.127 ms/op
     p(99.9000) =     14.189 ms/op
     p(99.9900) =     19.104 ms/op
     p(99.9990) =     20.967 ms/op
     p(99.9999) =     21.004 ms/op
    p(100.0000) =     21.004 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  10.145 ± 3.296  ops/ms
ClientPb.existUser                       thrpt       3   9.957 ± 3.050  ops/ms
ClientPb.getUser                         thrpt       3  10.047 ± 0.254  ops/ms
ClientPb.listUser                        thrpt       3   8.672 ± 1.200  ops/ms
ClientPb.createUser                       avgt       3   3.124 ± 1.321   ms/op
ClientPb.existUser                        avgt       3   2.989 ± 0.576   ms/op
ClientPb.getUser                          avgt       3   3.177 ± 0.902   ms/op
ClientPb.listUser                         avgt       3   3.671 ± 0.495   ms/op
ClientPb.createUser                     sample  284531   3.369 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.033           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.285           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.817           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.211           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.021           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.513           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.820           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.343           ms/op
ClientPb.existUser                      sample  309650   3.098 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.663           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.076           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.330           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.609           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.317           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.276           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.323           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.131           ms/op
ClientPb.getUser                        sample  304037   3.156 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.087           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.047           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.506           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.797           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.677           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.843           ms/op
ClientPb.getUser:getUser·p0.9999        sample          23.121           ms/op
ClientPb.getUser:getUser·p1.00          sample          25.231           ms/op
ClientPb.listUser                       sample  257142   3.733 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.202           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.613           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.088           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.407           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.127           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.189           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.104           ms/op
ClientPb.listUser:listUser·p1.00        sample          21.004           ms/op
