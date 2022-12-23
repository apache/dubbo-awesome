# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.614 ops/ms
# Warmup Iteration   2: 6.980 ops/ms
# Warmup Iteration   3: 9.383 ops/ms
Iteration   1: 10.163 ops/ms
Iteration   2: 9.936 ops/ms
Iteration   3: 9.868 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.989 ±(99.9%) 2.820 ops/ms [Average]
  (min, avg, max) = (9.868, 9.989, 10.163), stdev = 0.155
  CI (99.9%): [7.169, 12.809] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 3.477 ops/ms
# Warmup Iteration   2: 9.777 ops/ms
# Warmup Iteration   3: 10.374 ops/ms
Iteration   1: 10.856 ops/ms
Iteration   2: 10.184 ops/ms
Iteration   3: 10.386 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.475 ±(99.9%) 6.290 ops/ms [Average]
  (min, avg, max) = (10.184, 10.475, 10.856), stdev = 0.345
  CI (99.9%): [4.186, 16.765] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.198 ops/ms
# Warmup Iteration   2: 9.031 ops/ms
# Warmup Iteration   3: 9.371 ops/ms
Iteration   1: 10.374 ops/ms
Iteration   2: 10.156 ops/ms
Iteration   3: 10.014 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.182 ±(99.9%) 3.307 ops/ms [Average]
  (min, avg, max) = (10.014, 10.182, 10.374), stdev = 0.181
  CI (99.9%): [6.874, 13.489] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.235 ops/ms
# Warmup Iteration   2: 7.802 ops/ms
# Warmup Iteration   3: 8.370 ops/ms
Iteration   1: 8.452 ops/ms
Iteration   2: 8.498 ops/ms
Iteration   3: 8.495 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.482 ±(99.9%) 0.475 ops/ms [Average]
  (min, avg, max) = (8.452, 8.482, 8.498), stdev = 0.026
  CI (99.9%): [8.007, 8.956] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 8.128 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.477 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.206 ±(99.9%) 0.005 ms/op
Iteration   1: 3.253 ±(99.9%) 0.002 ms/op
Iteration   2: 3.067 ±(99.9%) 0.003 ms/op
Iteration   3: 3.222 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.181 ±(99.9%) 1.816 ms/op [Average]
  (min, avg, max) = (3.067, 3.181, 3.253), stdev = 0.100
  CI (99.9%): [1.365, 4.996] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 6.962 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.269 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.234 ±(99.9%) 0.005 ms/op
Iteration   1: 2.965 ±(99.9%) 0.002 ms/op
Iteration   2: 3.136 ±(99.9%) 0.006 ms/op
Iteration   3: 2.960 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.020 ±(99.9%) 1.820 ms/op [Average]
  (min, avg, max) = (2.960, 3.020, 3.136), stdev = 0.100
  CI (99.9%): [1.200, 4.840] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 7.104 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.402 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.220 ±(99.9%) 0.005 ms/op
Iteration   1: 3.138 ±(99.9%) 0.007 ms/op
Iteration   2: 3.192 ±(99.9%) 0.003 ms/op
Iteration   3: 3.067 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.132 ±(99.9%) 1.143 ms/op [Average]
  (min, avg, max) = (3.067, 3.132, 3.192), stdev = 0.063
  CI (99.9%): [1.989, 4.275] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 9.318 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.984 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.886 ±(99.9%) 0.008 ms/op
Iteration   1: 3.602 ±(99.9%) 0.012 ms/op
Iteration   2: 3.748 ±(99.9%) 0.007 ms/op
Iteration   3: 3.723 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.691 ±(99.9%) 1.418 ms/op [Average]
  (min, avg, max) = (3.602, 3.691, 3.748), stdev = 0.078
  CI (99.9%): [2.273, 5.109] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 7.978 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 3.817 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.100 ±(99.9%) 0.009 ms/op
Iteration   1: 3.113 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.948 ms/op
                 createUser·p0.50:   3.019 ms/op
                 createUser·p0.90:   3.490 ms/op
                 createUser·p0.95:   3.760 ms/op
                 createUser·p0.99:   5.448 ms/op
                 createUser·p0.999:  10.690 ms/op
                 createUser·p0.9999: 19.759 ms/op
                 createUser·p1.00:   20.152 ms/op

Iteration   2: 3.277 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.330 ms/op
                 createUser·p0.50:   3.183 ms/op
                 createUser·p0.90:   3.793 ms/op
                 createUser·p0.95:   4.108 ms/op
                 createUser·p0.99:   5.538 ms/op
                 createUser·p0.999:  18.520 ms/op
                 createUser·p0.9999: 25.598 ms/op
                 createUser·p1.00:   26.870 ms/op

Iteration   3: 3.063 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.532 ms/op
                 createUser·p0.50:   2.994 ms/op
                 createUser·p0.90:   3.187 ms/op
                 createUser·p0.95:   3.535 ms/op
                 createUser·p0.99:   4.435 ms/op
                 createUser·p0.999:  15.024 ms/op
                 createUser·p0.9999: 26.513 ms/op
                 createUser·p1.00:   27.197 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 304838
  mean =      3.148 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18080 
    [ 2.500,  5.000) = 282171 
    [ 5.000,  7.500) = 3821 
    [ 7.500, 10.000) = 315 
    [10.000, 12.500) = 75 
    [12.500, 15.000) = 56 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 142 
    [20.000, 22.500) = 41 
    [22.500, 25.000) = 61 
    [25.000, 27.500) = 48 

  Percentiles, ms/op:
      p(0.0000) =      0.330 ms/op
     p(50.0000) =      3.056 ms/op
     p(90.0000) =      3.564 ms/op
     p(95.0000) =      3.863 ms/op
     p(99.0000) =      5.407 ms/op
     p(99.9000) =     15.406 ms/op
     p(99.9900) =     25.593 ms/op
     p(99.9990) =     26.901 ms/op
     p(99.9999) =     27.197 ms/op
    p(100.0000) =     27.197 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.798 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 3.345 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.104 ±(99.9%) 0.008 ms/op
Iteration   1: 3.145 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.024 ms/op
                 existUser·p0.50:   3.060 ms/op
                 existUser·p0.90:   3.568 ms/op
                 existUser·p0.95:   3.858 ms/op
                 existUser·p0.99:   5.308 ms/op
                 existUser·p0.999:  8.209 ms/op
                 existUser·p0.9999: 20.403 ms/op
                 existUser·p1.00:   20.808 ms/op

Iteration   2: 3.181 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.145 ms/op
                 existUser·p0.50:   3.129 ms/op
                 existUser·p0.90:   3.437 ms/op
                 existUser·p0.95:   3.850 ms/op
                 existUser·p0.99:   6.136 ms/op
                 existUser·p0.999:  14.338 ms/op
                 existUser·p0.9999: 24.246 ms/op
                 existUser·p1.00:   24.871 ms/op

Iteration   3: 3.088 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.206 ms/op
                 existUser·p0.50:   2.974 ms/op
                 existUser·p0.90:   3.408 ms/op
                 existUser·p0.95:   4.028 ms/op
                 existUser·p0.99:   5.292 ms/op
                 existUser·p0.999:  13.950 ms/op
                 existUser·p0.9999: 22.315 ms/op
                 existUser·p1.00:   22.970 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 305921
  mean =      3.137 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20239 
    [ 2.500,  5.000) = 279717 
    [ 5.000,  7.500) = 4981 
    [ 7.500, 10.000) = 555 
    [10.000, 12.500) = 75 
    [12.500, 15.000) = 83 
    [15.000, 17.500) = 15 
    [17.500, 20.000) = 91 
    [20.000, 22.500) = 120 
    [22.500, 25.000) = 45 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.024 ms/op
     p(50.0000) =      3.072 ms/op
     p(90.0000) =      3.494 ms/op
     p(95.0000) =      3.908 ms/op
     p(99.0000) =      5.530 ms/op
     p(99.9000) =     13.575 ms/op
     p(99.9900) =     23.036 ms/op
     p(99.9990) =     24.410 ms/op
     p(99.9999) =     24.871 ms/op
    p(100.0000) =     24.871 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 7.311 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 3.375 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.588 ±(99.9%) 0.018 ms/op
Iteration   1: 3.169 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.284 ms/op
                 getUser·p0.50:   3.056 ms/op
                 getUser·p0.90:   3.457 ms/op
                 getUser·p0.95:   3.736 ms/op
                 getUser·p0.99:   5.603 ms/op
                 getUser·p0.999:  14.958 ms/op
                 getUser·p0.9999: 20.703 ms/op
                 getUser·p1.00:   21.955 ms/op

Iteration   2: 3.164 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.384 ms/op
                 getUser·p0.50:   3.121 ms/op
                 getUser·p0.90:   3.568 ms/op
                 getUser·p0.95:   3.895 ms/op
                 getUser·p0.99:   5.390 ms/op
                 getUser·p0.999:  11.665 ms/op
                 getUser·p0.9999: 23.950 ms/op
                 getUser·p1.00:   24.576 ms/op

Iteration   3: 3.224 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.348 ms/op
                 getUser·p0.50:   3.117 ms/op
                 getUser·p0.90:   3.674 ms/op
                 getUser·p0.95:   4.194 ms/op
                 getUser·p0.99:   6.128 ms/op
                 getUser·p0.999:  9.901 ms/op
                 getUser·p0.9999: 23.071 ms/op
                 getUser·p1.00:   24.117 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 301090
  mean =      3.185 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17918 
    [ 2.500,  5.000) = 275928 
    [ 5.000,  7.500) = 6489 
    [ 7.500, 10.000) = 359 
    [10.000, 12.500) = 92 
    [12.500, 15.000) = 40 
    [15.000, 17.500) = 42 
    [17.500, 20.000) = 69 
    [20.000, 22.500) = 86 
    [22.500, 25.000) = 67 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.284 ms/op
     p(50.0000) =      3.105 ms/op
     p(90.0000) =      3.572 ms/op
     p(95.0000) =      3.949 ms/op
     p(99.0000) =      5.620 ms/op
     p(99.9000) =     12.642 ms/op
     p(99.9900) =     23.429 ms/op
     p(99.9990) =     24.445 ms/op
     p(99.9999) =     24.576 ms/op
    p(100.0000) =     24.576 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 9.250 ±(99.9%) 0.125 ms/op
# Warmup Iteration   2: 4.017 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.730 ±(99.9%) 0.011 ms/op
Iteration   1: 3.727 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.509 ms/op
                 listUser·p0.50:   3.596 ms/op
                 listUser·p0.90:   4.006 ms/op
                 listUser·p0.95:   4.415 ms/op
                 listUser·p0.99:   7.250 ms/op
                 listUser·p0.999:  16.155 ms/op
                 listUser·p0.9999: 27.460 ms/op
                 listUser·p1.00:   27.754 ms/op

Iteration   2: 3.740 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.997 ms/op
                 listUser·p0.50:   3.670 ms/op
                 listUser·p0.90:   4.116 ms/op
                 listUser·p0.95:   4.522 ms/op
                 listUser·p0.99:   6.996 ms/op
                 listUser·p0.999:  14.336 ms/op
                 listUser·p0.9999: 15.687 ms/op
                 listUser·p1.00:   17.465 ms/op

Iteration   3: 3.767 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.034 ms/op
                 listUser·p0.50:   3.682 ms/op
                 listUser·p0.90:   4.252 ms/op
                 listUser·p0.95:   4.588 ms/op
                 listUser·p0.99:   6.463 ms/op
                 listUser·p0.999:  11.141 ms/op
                 listUser·p0.9999: 13.484 ms/op
                 listUser·p1.00:   13.697 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 256168
  mean =      3.745 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 97 
    [ 2.500,  5.000) = 246798 
    [ 5.000,  7.500) = 7623 
    [ 7.500, 10.000) = 930 
    [10.000, 12.500) = 269 
    [12.500, 15.000) = 299 
    [15.000, 17.500) = 84 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 56 

  Percentiles, ms/op:
      p(0.0000) =      1.509 ms/op
     p(50.0000) =      3.662 ms/op
     p(90.0000) =      4.121 ms/op
     p(95.0000) =      4.522 ms/op
     p(99.0000) =      6.865 ms/op
     p(99.9000) =     13.844 ms/op
     p(99.9900) =     27.197 ms/op
     p(99.9990) =     27.699 ms/op
     p(99.9999) =     27.754 ms/op
    p(100.0000) =     27.754 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.989 ± 2.820  ops/ms
ClientPb.existUser                       thrpt       3  10.475 ± 6.290  ops/ms
ClientPb.getUser                         thrpt       3  10.182 ± 3.307  ops/ms
ClientPb.listUser                        thrpt       3   8.482 ± 0.475  ops/ms
ClientPb.createUser                       avgt       3   3.181 ± 1.816   ms/op
ClientPb.existUser                        avgt       3   3.020 ± 1.820   ms/op
ClientPb.getUser                          avgt       3   3.132 ± 1.143   ms/op
ClientPb.listUser                         avgt       3   3.691 ± 1.418   ms/op
ClientPb.createUser                     sample  304838   3.148 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.330           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.056           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.564           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.863           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.407           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.406           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.593           ms/op
ClientPb.createUser:createUser·p1.00    sample          27.197           ms/op
ClientPb.existUser                      sample  305921   3.137 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.024           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.072           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.494           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.908           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.530           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.575           ms/op
ClientPb.existUser:existUser·p0.9999    sample          23.036           ms/op
ClientPb.existUser:existUser·p1.00      sample          24.871           ms/op
ClientPb.getUser                        sample  301090   3.185 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.284           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.105           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.572           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.949           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.620           ms/op
ClientPb.getUser:getUser·p0.999         sample          12.642           ms/op
ClientPb.getUser:getUser·p0.9999        sample          23.429           ms/op
ClientPb.getUser:getUser·p1.00          sample          24.576           ms/op
ClientPb.listUser                       sample  256168   3.745 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.509           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.662           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.121           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.522           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.865           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.844           ms/op
ClientPb.listUser:listUser·p0.9999      sample          27.197           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.754           ms/op
