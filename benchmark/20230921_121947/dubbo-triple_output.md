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
# Warmup Iteration   1: 2.155 ops/ms
# Warmup Iteration   2: 6.271 ops/ms
# Warmup Iteration   3: 8.840 ops/ms
Iteration   1: 9.133 ops/ms
Iteration   2: 9.827 ops/ms
Iteration   3: 9.373 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.445 ±(99.9%) 6.432 ops/ms [Average]
  (min, avg, max) = (9.133, 9.445, 9.827), stdev = 0.353
  CI (99.9%): [3.012, 15.877] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.346 ops/ms
# Warmup Iteration   2: 8.773 ops/ms
# Warmup Iteration   3: 9.607 ops/ms
Iteration   1: 9.960 ops/ms
Iteration   2: 10.065 ops/ms
Iteration   3: 10.189 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.071 ±(99.9%) 2.090 ops/ms [Average]
  (min, avg, max) = (9.960, 10.071, 10.189), stdev = 0.115
  CI (99.9%): [7.981, 12.162] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 3.199 ops/ms
# Warmup Iteration   2: 9.314 ops/ms
# Warmup Iteration   3: 9.712 ops/ms
Iteration   1: 9.802 ops/ms
Iteration   2: 9.768 ops/ms
Iteration   3: 9.664 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.745 ±(99.9%) 1.307 ops/ms [Average]
  (min, avg, max) = (9.664, 9.745, 9.802), stdev = 0.072
  CI (99.9%): [8.438, 11.052] (assumes normal distribution)


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
# Warmup Iteration   1: 3.364 ops/ms
# Warmup Iteration   2: 7.523 ops/ms
# Warmup Iteration   3: 8.226 ops/ms
Iteration   1: 8.200 ops/ms
Iteration   2: 8.340 ops/ms
Iteration   3: 8.444 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.328 ±(99.9%) 2.234 ops/ms [Average]
  (min, avg, max) = (8.200, 8.328, 8.444), stdev = 0.122
  CI (99.9%): [6.094, 10.563] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 9.389 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.561 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.466 ±(99.9%) 0.004 ms/op
Iteration   1: 3.209 ±(99.9%) 0.003 ms/op
Iteration   2: 3.287 ±(99.9%) 0.002 ms/op
Iteration   3: 3.309 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.268 ±(99.9%) 0.958 ms/op [Average]
  (min, avg, max) = (3.209, 3.268, 3.309), stdev = 0.053
  CI (99.9%): [2.310, 4.226] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 8.136 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.366 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.254 ±(99.9%) 0.001 ms/op
Iteration   1: 3.183 ±(99.9%) 0.004 ms/op
Iteration   2: 3.089 ±(99.9%) 0.002 ms/op
Iteration   3: 3.290 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.187 ±(99.9%) 1.832 ms/op [Average]
  (min, avg, max) = (3.089, 3.187, 3.290), stdev = 0.100
  CI (99.9%): [1.356, 5.019] (assumes normal distribution)


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
# Warmup Iteration   1: 7.951 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.392 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.364 ±(99.9%) 0.002 ms/op
Iteration   1: 3.278 ±(99.9%) 0.003 ms/op
Iteration   2: 3.225 ±(99.9%) 0.003 ms/op
Iteration   3: 3.228 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.244 ±(99.9%) 0.537 ms/op [Average]
  (min, avg, max) = (3.225, 3.244, 3.278), stdev = 0.029
  CI (99.9%): [2.707, 3.780] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 9.232 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 4.209 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.875 ±(99.9%) 0.003 ms/op
Iteration   1: 3.877 ±(99.9%) 0.005 ms/op
Iteration   2: 3.857 ±(99.9%) 0.003 ms/op
Iteration   3: 3.884 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.873 ±(99.9%) 0.262 ms/op [Average]
  (min, avg, max) = (3.857, 3.873, 3.884), stdev = 0.014
  CI (99.9%): [3.611, 4.134] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 7.520 ±(99.9%) 0.102 ms/op
# Warmup Iteration   2: 3.666 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.305 ±(99.9%) 0.008 ms/op
Iteration   1: 3.307 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.292 ms/op
                 createUser·p0.50:   3.215 ms/op
                 createUser·p0.90:   3.670 ms/op
                 createUser·p0.95:   4.071 ms/op
                 createUser·p0.99:   6.169 ms/op
                 createUser·p0.999:  19.137 ms/op
                 createUser·p0.9999: 22.457 ms/op
                 createUser·p1.00:   23.167 ms/op

Iteration   2: 3.250 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.548 ms/op
                 createUser·p0.50:   3.178 ms/op
                 createUser·p0.90:   3.514 ms/op
                 createUser·p0.95:   3.781 ms/op
                 createUser·p0.99:   5.480 ms/op
                 createUser·p0.999:  16.206 ms/op
                 createUser·p0.9999: 24.019 ms/op
                 createUser·p1.00:   25.133 ms/op

Iteration   3: 3.170 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.331 ms/op
                 createUser·p0.50:   3.105 ms/op
                 createUser·p0.90:   3.346 ms/op
                 createUser·p0.95:   3.617 ms/op
                 createUser·p0.99:   5.194 ms/op
                 createUser·p0.999:  13.386 ms/op
                 createUser·p0.9999: 19.129 ms/op
                 createUser·p1.00:   19.792 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 295896
  mean =      3.241 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15607 
    [ 2.500,  5.000) = 275130 
    [ 5.000,  7.500) = 4138 
    [ 7.500, 10.000) = 433 
    [10.000, 12.500) = 237 
    [12.500, 15.000) = 33 
    [15.000, 17.500) = 66 
    [17.500, 20.000) = 125 
    [20.000, 22.500) = 78 
    [22.500, 25.000) = 46 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.548 ms/op
     p(50.0000) =      3.158 ms/op
     p(90.0000) =      3.527 ms/op
     p(95.0000) =      3.817 ms/op
     p(99.0000) =      5.751 ms/op
     p(99.9000) =     16.042 ms/op
     p(99.9900) =     23.003 ms/op
     p(99.9990) =     25.007 ms/op
     p(99.9999) =     25.133 ms/op
    p(100.0000) =     25.133 ms/op


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
# Warmup Iteration   1: 7.453 ±(99.9%) 0.092 ms/op
# Warmup Iteration   2: 3.467 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.108 ±(99.9%) 0.008 ms/op
Iteration   1: 3.250 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.462 ms/op
                 existUser·p0.50:   3.109 ms/op
                 existUser·p0.90:   3.777 ms/op
                 existUser·p0.95:   4.026 ms/op
                 existUser·p0.99:   5.710 ms/op
                 existUser·p0.999:  9.497 ms/op
                 existUser·p0.9999: 24.652 ms/op
                 existUser·p1.00:   24.871 ms/op

Iteration   2: 3.251 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.661 ms/op
                 existUser·p0.50:   3.117 ms/op
                 existUser·p0.90:   3.543 ms/op
                 existUser·p0.95:   4.268 ms/op
                 existUser·p0.99:   6.791 ms/op
                 existUser·p0.999:  14.094 ms/op
                 existUser·p0.9999: 21.730 ms/op
                 existUser·p1.00:   22.675 ms/op

Iteration   3: 3.233 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.255 ms/op
                 existUser·p0.50:   3.154 ms/op
                 existUser·p0.90:   3.473 ms/op
                 existUser·p0.95:   4.276 ms/op
                 existUser·p0.99:   6.586 ms/op
                 existUser·p0.999:  13.698 ms/op
                 existUser·p0.9999: 24.969 ms/op
                 existUser·p1.00:   26.542 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 295622
  mean =      3.245 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17199 
    [ 2.500,  5.000) = 269675 
    [ 5.000,  7.500) = 7581 
    [ 7.500, 10.000) = 686 
    [10.000, 12.500) = 140 
    [12.500, 15.000) = 61 
    [15.000, 17.500) = 43 
    [17.500, 20.000) = 46 
    [20.000, 22.500) = 100 
    [22.500, 25.000) = 83 
    [25.000, 27.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      1.255 ms/op
     p(50.0000) =      3.129 ms/op
     p(90.0000) =      3.650 ms/op
     p(95.0000) =      4.141 ms/op
     p(99.0000) =      6.537 ms/op
     p(99.9000) =     13.945 ms/op
     p(99.9900) =     24.525 ms/op
     p(99.9990) =     25.535 ms/op
     p(99.9999) =     26.542 ms/op
    p(100.0000) =     26.542 ms/op


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
# Warmup Iteration   1: 7.510 ±(99.9%) 0.092 ms/op
# Warmup Iteration   2: 3.632 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.494 ±(99.9%) 0.012 ms/op
Iteration   1: 3.371 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.372 ms/op
                 getUser·p0.50:   3.174 ms/op
                 getUser·p0.90:   3.944 ms/op
                 getUser·p0.95:   4.899 ms/op
                 getUser·p0.99:   6.930 ms/op
                 getUser·p0.999:  16.982 ms/op
                 getUser·p0.9999: 19.138 ms/op
                 getUser·p1.00:   19.694 ms/op

Iteration   2: 3.302 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.397 ms/op
                 getUser·p0.50:   3.248 ms/op
                 getUser·p0.90:   3.678 ms/op
                 getUser·p0.95:   4.104 ms/op
                 getUser·p0.99:   5.497 ms/op
                 getUser·p0.999:  11.484 ms/op
                 getUser·p0.9999: 20.916 ms/op
                 getUser·p1.00:   21.234 ms/op

Iteration   3: 3.426 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.395 ms/op
                 getUser·p0.50:   3.289 ms/op
                 getUser·p0.90:   3.846 ms/op
                 getUser·p0.95:   4.424 ms/op
                 getUser·p0.99:   6.951 ms/op
                 getUser·p0.999:  19.529 ms/op
                 getUser·p0.9999: 23.407 ms/op
                 getUser·p1.00:   23.953 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 285167
  mean =      3.366 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13244 
    [ 2.500,  5.000) = 262252 
    [ 5.000,  7.500) = 8478 
    [ 7.500, 10.000) = 739 
    [10.000, 12.500) = 38 
    [12.500, 15.000) = 43 
    [15.000, 17.500) = 92 
    [17.500, 20.000) = 161 
    [20.000, 22.500) = 90 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.372 ms/op
     p(50.0000) =      3.232 ms/op
     p(90.0000) =      3.813 ms/op
     p(95.0000) =      4.481 ms/op
     p(99.0000) =      6.767 ms/op
     p(99.9000) =     17.433 ms/op
     p(99.9900) =     22.852 ms/op
     p(99.9990) =     23.532 ms/op
     p(99.9999) =     23.953 ms/op
    p(100.0000) =     23.953 ms/op


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
# Warmup Iteration   1: 9.724 ±(99.9%) 0.126 ms/op
# Warmup Iteration   2: 4.220 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.877 ±(99.9%) 0.010 ms/op
Iteration   1: 3.913 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.300 ms/op
                 listUser·p0.50:   3.760 ms/op
                 listUser·p0.90:   4.268 ms/op
                 listUser·p0.95:   4.678 ms/op
                 listUser·p0.99:   7.389 ms/op
                 listUser·p0.999:  16.782 ms/op
                 listUser·p0.9999: 23.331 ms/op
                 listUser·p1.00:   24.216 ms/op

Iteration   2: 3.879 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.134 ms/op
                 listUser·p0.50:   3.781 ms/op
                 listUser·p0.90:   4.211 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   6.988 ms/op
                 listUser·p0.999:  13.271 ms/op
                 listUser·p0.9999: 14.795 ms/op
                 listUser·p1.00:   15.860 ms/op

Iteration   3: 3.765 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.614 ms/op
                 listUser·p0.50:   3.678 ms/op
                 listUser·p0.90:   4.026 ms/op
                 listUser·p0.95:   4.219 ms/op
                 listUser·p0.99:   6.570 ms/op
                 listUser·p0.999:  12.943 ms/op
                 listUser·p0.9999: 15.589 ms/op
                 listUser·p1.00:   15.729 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 249279
  mean =      3.851 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 114 
    [ 2.500,  5.000) = 241542 
    [ 5.000,  7.500) = 5850 
    [ 7.500, 10.000) = 970 
    [10.000, 12.500) = 235 
    [12.500, 15.000) = 429 
    [15.000, 17.500) = 86 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.300 ms/op
     p(50.0000) =      3.727 ms/op
     p(90.0000) =      4.190 ms/op
     p(95.0000) =      4.424 ms/op
     p(99.0000) =      6.930 ms/op
     p(99.9000) =     13.861 ms/op
     p(99.9900) =     21.697 ms/op
     p(99.9990) =     24.101 ms/op
     p(99.9999) =     24.216 ms/op
    p(100.0000) =     24.216 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.445 ± 6.432  ops/ms
ClientPb.existUser                       thrpt       3  10.071 ± 2.090  ops/ms
ClientPb.getUser                         thrpt       3   9.745 ± 1.307  ops/ms
ClientPb.listUser                        thrpt       3   8.328 ± 2.234  ops/ms
ClientPb.createUser                       avgt       3   3.268 ± 0.958   ms/op
ClientPb.existUser                        avgt       3   3.187 ± 1.832   ms/op
ClientPb.getUser                          avgt       3   3.244 ± 0.537   ms/op
ClientPb.listUser                         avgt       3   3.873 ± 0.262   ms/op
ClientPb.createUser                     sample  295896   3.241 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.548           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.158           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.527           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.817           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.751           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.042           ms/op
ClientPb.createUser:createUser·p0.9999  sample          23.003           ms/op
ClientPb.createUser:createUser·p1.00    sample          25.133           ms/op
ClientPb.existUser                      sample  295622   3.245 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.255           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.129           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.650           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.141           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.537           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.945           ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.525           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.542           ms/op
ClientPb.getUser                        sample  285167   3.366 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.372           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.232           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.813           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.481           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.767           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.433           ms/op
ClientPb.getUser:getUser·p0.9999        sample          22.852           ms/op
ClientPb.getUser:getUser·p1.00          sample          23.953           ms/op
ClientPb.listUser                       sample  249279   3.851 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.300           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.727           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.190           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.424           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.930           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.861           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.697           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.216           ms/op
