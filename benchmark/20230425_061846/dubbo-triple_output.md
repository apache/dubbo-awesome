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
# Warmup Iteration   1: 2.168 ops/ms
# Warmup Iteration   2: 5.387 ops/ms
# Warmup Iteration   3: 8.430 ops/ms
Iteration   1: 9.006 ops/ms
Iteration   2: 9.075 ops/ms
Iteration   3: 9.500 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.194 ±(99.9%) 4.882 ops/ms [Average]
  (min, avg, max) = (9.006, 9.194, 9.500), stdev = 0.268
  CI (99.9%): [4.311, 14.076] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.068 ops/ms
# Warmup Iteration   2: 8.445 ops/ms
# Warmup Iteration   3: 9.542 ops/ms
Iteration   1: 9.505 ops/ms
Iteration   2: 9.693 ops/ms
Iteration   3: 9.825 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.674 ±(99.9%) 2.939 ops/ms [Average]
  (min, avg, max) = (9.505, 9.674, 9.825), stdev = 0.161
  CI (99.9%): [6.736, 12.613] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.055 ops/ms
# Warmup Iteration   2: 8.181 ops/ms
# Warmup Iteration   3: 8.595 ops/ms
Iteration   1: 9.291 ops/ms
Iteration   2: 9.288 ops/ms
Iteration   3: 9.030 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.203 ±(99.9%) 2.730 ops/ms [Average]
  (min, avg, max) = (9.030, 9.203, 9.291), stdev = 0.150
  CI (99.9%): [6.473, 11.933] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.025 ops/ms
# Warmup Iteration   2: 7.488 ops/ms
# Warmup Iteration   3: 7.819 ops/ms
Iteration   1: 7.912 ops/ms
Iteration   2: 8.010 ops/ms
Iteration   3: 7.764 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.895 ±(99.9%) 2.256 ops/ms [Average]
  (min, avg, max) = (7.764, 7.895, 8.010), stdev = 0.124
  CI (99.9%): [5.640, 10.151] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 10.087 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 4.018 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.534 ±(99.9%) 0.004 ms/op
Iteration   1: 3.457 ±(99.9%) 0.009 ms/op
Iteration   2: 3.537 ±(99.9%) 0.009 ms/op
Iteration   3: 3.344 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.446 ±(99.9%) 1.772 ms/op [Average]
  (min, avg, max) = (3.344, 3.446, 3.537), stdev = 0.097
  CI (99.9%): [1.674, 5.218] (assumes normal distribution)


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
# Warmup Iteration   1: 7.963 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.593 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.313 ±(99.9%) 0.004 ms/op
Iteration   1: 3.250 ±(99.9%) 0.008 ms/op
Iteration   2: 3.214 ±(99.9%) 0.010 ms/op
Iteration   3: 3.275 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.247 ±(99.9%) 0.556 ms/op [Average]
  (min, avg, max) = (3.214, 3.247, 3.275), stdev = 0.030
  CI (99.9%): [2.691, 3.802] (assumes normal distribution)


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
# Warmup Iteration   1: 8.458 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.889 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.576 ±(99.9%) 0.007 ms/op
Iteration   1: 3.574 ±(99.9%) 0.006 ms/op
Iteration   2: 3.466 ±(99.9%) 0.003 ms/op
Iteration   3: 3.372 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.471 ±(99.9%) 1.849 ms/op [Average]
  (min, avg, max) = (3.372, 3.471, 3.574), stdev = 0.101
  CI (99.9%): [1.622, 5.319] (assumes normal distribution)


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
# Warmup Iteration   1: 10.276 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.559 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.258 ±(99.9%) 0.008 ms/op
Iteration   1: 4.016 ±(99.9%) 0.011 ms/op
Iteration   2: 4.003 ±(99.9%) 0.015 ms/op
Iteration   3: 3.992 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.004 ±(99.9%) 0.225 ms/op [Average]
  (min, avg, max) = (3.992, 4.004, 4.016), stdev = 0.012
  CI (99.9%): [3.779, 4.229] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 9.475 ±(99.9%) 0.136 ms/op
# Warmup Iteration   2: 4.080 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.714 ±(99.9%) 0.010 ms/op
Iteration   1: 3.556 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.139 ms/op
                 createUser·p0.50:   3.465 ms/op
                 createUser·p0.90:   4.108 ms/op
                 createUser·p0.95:   4.456 ms/op
                 createUser·p0.99:   5.982 ms/op
                 createUser·p0.999:  21.758 ms/op
                 createUser·p0.9999: 27.067 ms/op
                 createUser·p1.00:   27.984 ms/op

Iteration   2: 3.601 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.393 ms/op
                 createUser·p0.50:   3.461 ms/op
                 createUser·p0.90:   4.186 ms/op
                 createUser·p0.95:   4.473 ms/op
                 createUser·p0.99:   6.119 ms/op
                 createUser·p0.999:  21.672 ms/op
                 createUser·p0.9999: 26.382 ms/op
                 createUser·p1.00:   27.525 ms/op

Iteration   3: 3.558 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.104 ms/op
                 createUser·p0.50:   3.482 ms/op
                 createUser·p0.90:   3.961 ms/op
                 createUser·p0.95:   4.334 ms/op
                 createUser·p0.99:   6.095 ms/op
                 createUser·p0.999:  20.944 ms/op
                 createUser·p0.9999: 40.698 ms/op
                 createUser·p1.00:   41.681 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 268509
  mean =      3.572 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 261721 
    [ 5.000, 10.000) = 6184 
    [10.000, 15.000) = 249 
    [15.000, 20.000) = 57 
    [20.000, 25.000) = 185 
    [25.000, 30.000) = 81 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 19 
    [40.000, 45.000) = 13 

  Percentiles, ms/op:
      p(0.0000) =      1.104 ms/op
     p(50.0000) =      3.469 ms/op
     p(90.0000) =      4.104 ms/op
     p(95.0000) =      4.432 ms/op
     p(99.0000) =      6.078 ms/op
     p(99.9000) =     21.676 ms/op
     p(99.9900) =     38.882 ms/op
     p(99.9990) =     41.526 ms/op
     p(99.9999) =     41.681 ms/op
    p(100.0000) =     41.681 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 8.228 ±(99.9%) 0.096 ms/op
# Warmup Iteration   2: 3.670 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.712 ±(99.9%) 0.049 ms/op
Iteration   1: 4.158 ±(99.9%) 0.079 ms/op
                 existUser·p0.00:   1.235 ms/op
                 existUser·p0.50:   3.346 ms/op
                 existUser·p0.90:   4.133 ms/op
                 existUser·p0.95:   5.251 ms/op
                 existUser·p0.99:   31.646 ms/op
                 existUser·p0.999:  94.241 ms/op
                 existUser·p0.9999: 150.995 ms/op
                 existUser·p1.00:   153.616 ms/op

Iteration   2: 3.835 ±(99.9%) 0.063 ms/op
                 existUser·p0.00:   1.720 ms/op
                 existUser·p0.50:   3.203 ms/op
                 existUser·p0.90:   3.617 ms/op
                 existUser·p0.95:   3.920 ms/op
                 existUser·p0.99:   23.495 ms/op
                 existUser·p0.999:  80.216 ms/op
                 existUser·p0.9999: 97.578 ms/op
                 existUser·p1.00:   102.892 ms/op

Iteration   3: 4.031 ±(99.9%) 0.076 ms/op
                 existUser·p0.00:   1.200 ms/op
                 existUser·p0.50:   3.310 ms/op
                 existUser·p0.90:   4.088 ms/op
                 existUser·p0.95:   4.596 ms/op
                 existUser·p0.99:   25.836 ms/op
                 existUser·p0.999:  93.932 ms/op
                 existUser·p0.9999: 124.937 ms/op
                 existUser·p1.00:   144.179 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 240065
  mean =      4.004 ±(99.9%) 0.042 ms/op

  Histogram, ms/op:
    [  0.000,  12.500) = 236943 
    [ 12.500,  25.000) = 697 
    [ 25.000,  37.500) = 444 
    [ 37.500,  50.000) = 445 
    [ 50.000,  62.500) = 457 
    [ 62.500,  75.000) = 455 
    [ 75.000,  87.500) = 373 
    [ 87.500, 100.000) = 151 
    [100.000, 112.500) = 57 
    [112.500, 125.000) = 23 
    [125.000, 137.500) = 7 
    [137.500, 150.000) = 5 
    [150.000, 162.500) = 8 
    [162.500, 175.000) = 0 
    [175.000, 187.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.200 ms/op
     p(50.0000) =      3.297 ms/op
     p(90.0000) =      3.879 ms/op
     p(95.0000) =      4.588 ms/op
     p(99.0000) =     25.636 ms/op
     p(99.9000) =     88.736 ms/op
     p(99.9900) =    123.994 ms/op
     p(99.9990) =    152.620 ms/op
     p(99.9999) =    153.616 ms/op
    p(100.0000) =    153.616 ms/op


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
# Warmup Iteration   1: 13.480 ±(99.9%) 0.385 ms/op
# Warmup Iteration   2: 4.255 ±(99.9%) 0.056 ms/op
# Warmup Iteration   3: 4.323 ±(99.9%) 0.081 ms/op
Iteration   1: 4.149 ±(99.9%) 0.067 ms/op
                 getUser·p0.00:   1.495 ms/op
                 getUser·p0.50:   3.469 ms/op
                 getUser·p0.90:   4.243 ms/op
                 getUser·p0.95:   4.932 ms/op
                 getUser·p0.99:   19.309 ms/op
                 getUser·p0.999:  84.112 ms/op
                 getUser·p0.9999: 94.539 ms/op
                 getUser·p1.00:   100.270 ms/op

Iteration   2: 4.115 ±(99.9%) 0.073 ms/op
                 getUser·p0.00:   1.055 ms/op
                 getUser·p0.50:   3.359 ms/op
                 getUser·p0.90:   3.981 ms/op
                 getUser·p0.95:   4.809 ms/op
                 getUser·p0.99:   21.258 ms/op
                 getUser·p0.999:  90.987 ms/op
                 getUser·p0.9999: 151.918 ms/op
                 getUser·p1.00:   161.481 ms/op

Iteration   3: 4.196 ±(99.9%) 0.082 ms/op
                 getUser·p0.00:   2.017 ms/op
                 getUser·p0.50:   3.396 ms/op
                 getUser·p0.90:   4.170 ms/op
                 getUser·p0.95:   4.628 ms/op
                 getUser·p0.99:   25.887 ms/op
                 getUser·p0.999:  95.241 ms/op
                 getUser·p0.9999: 158.409 ms/op
                 getUser·p1.00:   162.267 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 232281
  mean =      4.153 ±(99.9%) 0.043 ms/op

  Histogram, ms/op:
    [  0.000,  12.500) = 229428 
    [ 12.500,  25.000) = 691 
    [ 25.000,  37.500) = 375 
    [ 37.500,  50.000) = 311 
    [ 50.000,  62.500) = 369 
    [ 62.500,  75.000) = 443 
    [ 75.000,  87.500) = 430 
    [ 87.500, 100.000) = 123 
    [100.000, 112.500) = 42 
    [112.500, 125.000) = 21 
    [125.000, 137.500) = 11 
    [137.500, 150.000) = 7 
    [150.000, 162.500) = 30 
    [162.500, 175.000) = 0 
    [175.000, 187.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.055 ms/op
     p(50.0000) =      3.420 ms/op
     p(90.0000) =      4.145 ms/op
     p(95.0000) =      4.751 ms/op
     p(99.0000) =     22.151 ms/op
     p(99.9000) =     87.650 ms/op
     p(99.9900) =    153.759 ms/op
     p(99.9990) =    162.013 ms/op
     p(99.9999) =    162.267 ms/op
    p(100.0000) =    162.267 ms/op


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
# Warmup Iteration   1: 11.811 ±(99.9%) 0.156 ms/op
# Warmup Iteration   2: 4.819 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 4.161 ±(99.9%) 0.014 ms/op
Iteration   1: 4.161 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.882 ms/op
                 listUser·p0.50:   4.002 ms/op
                 listUser·p0.90:   4.538 ms/op
                 listUser·p0.95:   4.956 ms/op
                 listUser·p0.99:   7.660 ms/op
                 listUser·p0.999:  21.075 ms/op
                 listUser·p0.9999: 26.552 ms/op
                 listUser·p1.00:   27.001 ms/op

Iteration   2: 4.054 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.997 ms/op
                 listUser·p0.50:   3.809 ms/op
                 listUser·p0.90:   4.538 ms/op
                 listUser·p0.95:   5.079 ms/op
                 listUser·p0.99:   7.938 ms/op
                 listUser·p0.999:  15.548 ms/op
                 listUser·p0.9999: 18.612 ms/op
                 listUser·p1.00:   18.678 ms/op

Iteration   3: 3.961 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.482 ms/op
                 listUser·p0.50:   3.809 ms/op
                 listUser·p0.90:   4.399 ms/op
                 listUser·p0.95:   4.661 ms/op
                 listUser·p0.99:   7.041 ms/op
                 listUser·p0.999:  14.127 ms/op
                 listUser·p0.9999: 16.843 ms/op
                 listUser·p1.00:   17.433 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 236575
  mean =      4.057 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 33 
    [ 2.500,  5.000) = 226224 
    [ 5.000,  7.500) = 7674 
    [ 7.500, 10.000) = 1813 
    [10.000, 12.500) = 284 
    [12.500, 15.000) = 234 
    [15.000, 17.500) = 197 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 46 

  Percentiles, ms/op:
      p(0.0000) =      1.882 ms/op
     p(50.0000) =      3.858 ms/op
     p(90.0000) =      4.497 ms/op
     p(95.0000) =      4.858 ms/op
     p(99.0000) =      7.643 ms/op
     p(99.9000) =     15.752 ms/op
     p(99.9900) =     25.734 ms/op
     p(99.9990) =     26.694 ms/op
     p(99.9999) =     27.001 ms/op
    p(100.0000) =     27.001 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt    Score   Error   Units
ClientPb.createUser                      thrpt       3    9.194 ± 4.882  ops/ms
ClientPb.existUser                       thrpt       3    9.674 ± 2.939  ops/ms
ClientPb.getUser                         thrpt       3    9.203 ± 2.730  ops/ms
ClientPb.listUser                        thrpt       3    7.895 ± 2.256  ops/ms
ClientPb.createUser                       avgt       3    3.446 ± 1.772   ms/op
ClientPb.existUser                        avgt       3    3.247 ± 0.556   ms/op
ClientPb.getUser                          avgt       3    3.471 ± 1.849   ms/op
ClientPb.listUser                         avgt       3    4.004 ± 0.225   ms/op
ClientPb.createUser                     sample  268509    3.572 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample            1.104           ms/op
ClientPb.createUser:createUser·p0.50    sample            3.469           ms/op
ClientPb.createUser:createUser·p0.90    sample            4.104           ms/op
ClientPb.createUser:createUser·p0.95    sample            4.432           ms/op
ClientPb.createUser:createUser·p0.99    sample            6.078           ms/op
ClientPb.createUser:createUser·p0.999   sample           21.676           ms/op
ClientPb.createUser:createUser·p0.9999  sample           38.882           ms/op
ClientPb.createUser:createUser·p1.00    sample           41.681           ms/op
ClientPb.existUser                      sample  240065    4.004 ± 0.042   ms/op
ClientPb.existUser:existUser·p0.00      sample            1.200           ms/op
ClientPb.existUser:existUser·p0.50      sample            3.297           ms/op
ClientPb.existUser:existUser·p0.90      sample            3.879           ms/op
ClientPb.existUser:existUser·p0.95      sample            4.588           ms/op
ClientPb.existUser:existUser·p0.99      sample           25.636           ms/op
ClientPb.existUser:existUser·p0.999     sample           88.736           ms/op
ClientPb.existUser:existUser·p0.9999    sample          123.994           ms/op
ClientPb.existUser:existUser·p1.00      sample          153.616           ms/op
ClientPb.getUser                        sample  232281    4.153 ± 0.043   ms/op
ClientPb.getUser:getUser·p0.00          sample            1.055           ms/op
ClientPb.getUser:getUser·p0.50          sample            3.420           ms/op
ClientPb.getUser:getUser·p0.90          sample            4.145           ms/op
ClientPb.getUser:getUser·p0.95          sample            4.751           ms/op
ClientPb.getUser:getUser·p0.99          sample           22.151           ms/op
ClientPb.getUser:getUser·p0.999         sample           87.650           ms/op
ClientPb.getUser:getUser·p0.9999        sample          153.759           ms/op
ClientPb.getUser:getUser·p1.00          sample          162.267           ms/op
ClientPb.listUser                       sample  236575    4.057 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample            1.882           ms/op
ClientPb.listUser:listUser·p0.50        sample            3.858           ms/op
ClientPb.listUser:listUser·p0.90        sample            4.497           ms/op
ClientPb.listUser:listUser·p0.95        sample            4.858           ms/op
ClientPb.listUser:listUser·p0.99        sample            7.643           ms/op
ClientPb.listUser:listUser·p0.999       sample           15.752           ms/op
ClientPb.listUser:listUser·p0.9999      sample           25.734           ms/op
ClientPb.listUser:listUser·p1.00        sample           27.001           ms/op
