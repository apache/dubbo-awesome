# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.433 ops/ms
# Warmup Iteration   2: 6.330 ops/ms
# Warmup Iteration   3: 8.871 ops/ms
Iteration   1: 9.639 ops/ms
Iteration   2: 9.715 ops/ms
Iteration   3: 9.701 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.685 ±(99.9%) 0.737 ops/ms [Average]
  (min, avg, max) = (9.639, 9.685, 9.715), stdev = 0.040
  CI (99.9%): [8.948, 10.422] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 3.418 ops/ms
# Warmup Iteration   2: 9.355 ops/ms
# Warmup Iteration   3: 10.239 ops/ms
Iteration   1: 9.974 ops/ms
Iteration   2: 10.330 ops/ms
Iteration   3: 10.067 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.124 ±(99.9%) 3.366 ops/ms [Average]
  (min, avg, max) = (9.974, 10.124, 10.330), stdev = 0.184
  CI (99.9%): [6.758, 13.489] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.232 ops/ms
# Warmup Iteration   2: 8.655 ops/ms
# Warmup Iteration   3: 9.633 ops/ms
Iteration   1: 9.945 ops/ms
Iteration   2: 9.943 ops/ms
Iteration   3: 9.935 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.941 ±(99.9%) 0.101 ops/ms [Average]
  (min, avg, max) = (9.935, 9.941, 9.945), stdev = 0.006
  CI (99.9%): [9.840, 10.042] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 3.597 ops/ms
# Warmup Iteration   2: 8.043 ops/ms
# Warmup Iteration   3: 8.209 ops/ms
Iteration   1: 8.248 ops/ms
Iteration   2: 8.501 ops/ms
Iteration   3: 8.460 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.403 ±(99.9%) 2.481 ops/ms [Average]
  (min, avg, max) = (8.248, 8.403, 8.501), stdev = 0.136
  CI (99.9%): [5.922, 10.883] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 8.296 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.451 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.319 ±(99.9%) 0.002 ms/op
Iteration   1: 3.208 ±(99.9%) 0.004 ms/op
Iteration   2: 3.245 ±(99.9%) 0.002 ms/op
Iteration   3: 3.189 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.214 ±(99.9%) 0.525 ms/op [Average]
  (min, avg, max) = (3.189, 3.214, 3.245), stdev = 0.029
  CI (99.9%): [2.689, 3.739] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 7.647 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.357 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.194 ±(99.9%) 0.003 ms/op
Iteration   1: 3.150 ±(99.9%) 0.005 ms/op
Iteration   2: 3.141 ±(99.9%) 0.002 ms/op
Iteration   3: 3.145 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.145 ±(99.9%) 0.076 ms/op [Average]
  (min, avg, max) = (3.141, 3.145, 3.150), stdev = 0.004
  CI (99.9%): [3.069, 3.221] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 8.930 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.503 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.304 ±(99.9%) 0.002 ms/op
Iteration   1: 3.240 ±(99.9%) 0.003 ms/op
Iteration   2: 3.137 ±(99.9%) 0.003 ms/op
Iteration   3: 3.188 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.188 ±(99.9%) 0.935 ms/op [Average]
  (min, avg, max) = (3.137, 3.188, 3.240), stdev = 0.051
  CI (99.9%): [2.253, 4.123] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 9.891 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.107 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.869 ±(99.9%) 0.005 ms/op
Iteration   1: 3.786 ±(99.9%) 0.005 ms/op
Iteration   2: 3.733 ±(99.9%) 0.007 ms/op
Iteration   3: 3.802 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.773 ±(99.9%) 0.662 ms/op [Average]
  (min, avg, max) = (3.733, 3.773, 3.802), stdev = 0.036
  CI (99.9%): [3.112, 4.435] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 7.334 ±(99.9%) 0.091 ms/op
# Warmup Iteration   2: 3.881 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.285 ±(99.9%) 0.008 ms/op
Iteration   1: 3.307 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.032 ms/op
                 createUser·p0.50:   3.195 ms/op
                 createUser·p0.90:   3.736 ms/op
                 createUser·p0.95:   4.076 ms/op
                 createUser·p0.99:   6.431 ms/op
                 createUser·p0.999:  17.023 ms/op
                 createUser·p0.9999: 21.113 ms/op
                 createUser·p1.00:   21.430 ms/op

Iteration   2: 3.246 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.284 ms/op
                 createUser·p0.50:   3.150 ms/op
                 createUser·p0.90:   3.658 ms/op
                 createUser·p0.95:   3.936 ms/op
                 createUser·p0.99:   5.620 ms/op
                 createUser·p0.999:  20.102 ms/op
                 createUser·p0.9999: 24.390 ms/op
                 createUser·p1.00:   25.592 ms/op

Iteration   3: 3.310 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.204 ms/op
                 createUser·p0.50:   3.277 ms/op
                 createUser·p0.90:   3.704 ms/op
                 createUser·p0.95:   3.969 ms/op
                 createUser·p0.99:   5.689 ms/op
                 createUser·p0.999:  14.534 ms/op
                 createUser·p0.9999: 18.416 ms/op
                 createUser·p1.00:   18.907 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 291911
  mean =      3.288 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13789 
    [ 2.500,  5.000) = 272285 
    [ 5.000,  7.500) = 4755 
    [ 7.500, 10.000) = 506 
    [10.000, 12.500) = 206 
    [12.500, 15.000) = 45 
    [15.000, 17.500) = 84 
    [17.500, 20.000) = 100 
    [20.000, 22.500) = 108 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      1.032 ms/op
     p(50.0000) =      3.211 ms/op
     p(90.0000) =      3.699 ms/op
     p(95.0000) =      3.990 ms/op
     p(99.0000) =      5.882 ms/op
     p(99.9000) =     15.617 ms/op
     p(99.9900) =     23.167 ms/op
     p(99.9990) =     25.529 ms/op
     p(99.9999) =     25.592 ms/op
    p(100.0000) =     25.592 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.895 ±(99.9%) 0.079 ms/op
# Warmup Iteration   2: 3.373 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.218 ±(99.9%) 0.008 ms/op
Iteration   1: 3.167 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.356 ms/op
                 existUser·p0.50:   3.109 ms/op
                 existUser·p0.90:   3.445 ms/op
                 existUser·p0.95:   3.817 ms/op
                 existUser·p0.99:   5.538 ms/op
                 existUser·p0.999:  16.269 ms/op
                 existUser·p0.9999: 20.542 ms/op
                 existUser·p1.00:   22.970 ms/op

Iteration   2: 3.249 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.311 ms/op
                 existUser·p0.50:   3.232 ms/op
                 existUser·p0.90:   3.564 ms/op
                 existUser·p0.95:   3.805 ms/op
                 existUser·p0.99:   5.497 ms/op
                 existUser·p0.999:  12.583 ms/op
                 existUser·p0.9999: 22.418 ms/op
                 existUser·p1.00:   23.626 ms/op

Iteration   3: 3.137 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.180 ms/op
                 existUser·p0.50:   3.146 ms/op
                 existUser·p0.90:   3.318 ms/op
                 existUser·p0.95:   3.551 ms/op
                 existUser·p0.99:   5.308 ms/op
                 existUser·p0.999:  9.437 ms/op
                 existUser·p0.9999: 24.799 ms/op
                 existUser·p1.00:   26.444 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 301407
  mean =      3.184 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23790 
    [ 2.500,  5.000) = 272495 
    [ 5.000,  7.500) = 4172 
    [ 7.500, 10.000) = 393 
    [10.000, 12.500) = 235 
    [12.500, 15.000) = 54 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 82 
    [20.000, 22.500) = 106 
    [22.500, 25.000) = 40 
    [25.000, 27.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      1.180 ms/op
     p(50.0000) =      3.162 ms/op
     p(90.0000) =      3.457 ms/op
     p(95.0000) =      3.731 ms/op
     p(99.0000) =      5.456 ms/op
     p(99.9000) =     12.599 ms/op
     p(99.9900) =     22.970 ms/op
     p(99.9990) =     26.182 ms/op
     p(99.9999) =     26.444 ms/op
    p(100.0000) =     26.444 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 8.205 ±(99.9%) 0.098 ms/op
# Warmup Iteration   2: 3.489 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.362 ±(99.9%) 0.011 ms/op
Iteration   1: 3.320 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.151 ms/op
                 getUser·p0.50:   3.244 ms/op
                 getUser·p0.90:   3.686 ms/op
                 getUser·p0.95:   3.944 ms/op
                 getUser·p0.99:   5.931 ms/op
                 getUser·p0.999:  18.568 ms/op
                 getUser·p0.9999: 23.200 ms/op
                 getUser·p1.00:   24.248 ms/op

Iteration   2: 3.273 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.184 ms/op
                 getUser·p0.50:   3.170 ms/op
                 getUser·p0.90:   3.740 ms/op
                 getUser·p0.95:   3.944 ms/op
                 getUser·p0.99:   5.005 ms/op
                 getUser·p0.999:  16.302 ms/op
                 getUser·p0.9999: 23.932 ms/op
                 getUser·p1.00:   25.821 ms/op

Iteration   3: 3.284 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.227 ms/op
                 getUser·p0.50:   3.236 ms/op
                 getUser·p0.90:   3.711 ms/op
                 getUser·p0.95:   3.998 ms/op
                 getUser·p0.99:   5.595 ms/op
                 getUser·p0.999:  11.600 ms/op
                 getUser·p0.9999: 22.586 ms/op
                 getUser·p1.00:   23.069 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 291394
  mean =      3.292 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12388 
    [ 2.500,  5.000) = 274005 
    [ 5.000,  7.500) = 4207 
    [ 7.500, 10.000) = 242 
    [10.000, 12.500) = 200 
    [12.500, 15.000) = 60 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 64 
    [20.000, 22.500) = 135 
    [22.500, 25.000) = 57 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.151 ms/op
     p(50.0000) =      3.228 ms/op
     p(90.0000) =      3.711 ms/op
     p(95.0000) =      3.957 ms/op
     p(99.0000) =      5.562 ms/op
     p(99.9000) =     15.028 ms/op
     p(99.9900) =     23.181 ms/op
     p(99.9990) =     25.031 ms/op
     p(99.9999) =     25.821 ms/op
    p(100.0000) =     25.821 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 8.543 ±(99.9%) 0.111 ms/op
# Warmup Iteration   2: 4.101 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.756 ±(99.9%) 0.009 ms/op
Iteration   1: 3.912 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.802 ms/op
                 listUser·p0.50:   3.760 ms/op
                 listUser·p0.90:   4.317 ms/op
                 listUser·p0.95:   4.538 ms/op
                 listUser·p0.99:   7.225 ms/op
                 listUser·p0.999:  17.146 ms/op
                 listUser·p0.9999: 19.182 ms/op
                 listUser·p1.00:   19.759 ms/op

Iteration   2: 3.799 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.970 ms/op
                 listUser·p0.50:   3.682 ms/op
                 listUser·p0.90:   4.100 ms/op
                 listUser·p0.95:   4.283 ms/op
                 listUser·p0.99:   6.963 ms/op
                 listUser·p0.999:  13.926 ms/op
                 listUser·p0.9999: 17.476 ms/op
                 listUser·p1.00:   20.120 ms/op

Iteration   3: 3.779 ±(99.9%) 0.007 ms/op
                 listUser·p0.00:   2.212 ms/op
                 listUser·p0.50:   3.695 ms/op
                 listUser·p0.90:   4.133 ms/op
                 listUser·p0.95:   4.334 ms/op
                 listUser·p0.99:   6.054 ms/op
                 listUser·p0.999:  12.507 ms/op
                 listUser·p0.9999: 18.383 ms/op
                 listUser·p1.00:   18.448 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 250530
  mean =      3.829 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 70 
    [ 2.500,  5.000) = 244390 
    [ 5.000,  7.500) = 4378 
    [ 7.500, 10.000) = 811 
    [10.000, 12.500) = 350 
    [12.500, 15.000) = 340 
    [15.000, 17.500) = 115 
    [17.500, 20.000) = 75 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.802 ms/op
     p(50.0000) =      3.711 ms/op
     p(90.0000) =      4.194 ms/op
     p(95.0000) =      4.407 ms/op
     p(99.0000) =      6.742 ms/op
     p(99.9000) =     14.008 ms/op
     p(99.9900) =     18.514 ms/op
     p(99.9990) =     19.857 ms/op
     p(99.9999) =     20.120 ms/op
    p(100.0000) =     20.120 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.685 ± 0.737  ops/ms
ClientPb.existUser                       thrpt       3  10.124 ± 3.366  ops/ms
ClientPb.getUser                         thrpt       3   9.941 ± 0.101  ops/ms
ClientPb.listUser                        thrpt       3   8.403 ± 2.481  ops/ms
ClientPb.createUser                       avgt       3   3.214 ± 0.525   ms/op
ClientPb.existUser                        avgt       3   3.145 ± 0.076   ms/op
ClientPb.getUser                          avgt       3   3.188 ± 0.935   ms/op
ClientPb.listUser                         avgt       3   3.773 ± 0.662   ms/op
ClientPb.createUser                     sample  291911   3.288 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.032           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.211           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.699           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.990           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.882           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.617           ms/op
ClientPb.createUser:createUser·p0.9999  sample          23.167           ms/op
ClientPb.createUser:createUser·p1.00    sample          25.592           ms/op
ClientPb.existUser                      sample  301407   3.184 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.180           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.162           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.457           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.731           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.456           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.599           ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.970           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.444           ms/op
ClientPb.getUser                        sample  291394   3.292 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.151           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.228           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.711           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.957           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.562           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.028           ms/op
ClientPb.getUser:getUser·p0.9999        sample          23.181           ms/op
ClientPb.getUser:getUser·p1.00          sample          25.821           ms/op
ClientPb.listUser                       sample  250530   3.829 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.802           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.711           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.194           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.407           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.742           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.008           ms/op
ClientPb.listUser:listUser·p0.9999      sample          18.514           ms/op
ClientPb.listUser:listUser·p1.00        sample          20.120           ms/op
