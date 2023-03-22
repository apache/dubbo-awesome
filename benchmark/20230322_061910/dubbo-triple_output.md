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
# Warmup Iteration   1: 2.331 ops/ms
# Warmup Iteration   2: 5.254 ops/ms
# Warmup Iteration   3: 8.959 ops/ms
Iteration   1: 9.859 ops/ms
Iteration   2: 9.875 ops/ms
Iteration   3: 10.031 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.922 ±(99.9%) 1.733 ops/ms [Average]
  (min, avg, max) = (9.859, 9.922, 10.031), stdev = 0.095
  CI (99.9%): [8.189, 11.655] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 3.355 ops/ms
# Warmup Iteration   2: 9.298 ops/ms
# Warmup Iteration   3: 10.033 ops/ms
Iteration   1: 10.294 ops/ms
Iteration   2: 10.445 ops/ms
Iteration   3: 10.684 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.474 ±(99.9%) 3.594 ops/ms [Average]
  (min, avg, max) = (10.294, 10.474, 10.684), stdev = 0.197
  CI (99.9%): [6.880, 14.068] (assumes normal distribution)


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
# Warmup Iteration   1: 3.173 ops/ms
# Warmup Iteration   2: 8.941 ops/ms
# Warmup Iteration   3: 9.672 ops/ms
Iteration   1: 10.174 ops/ms
Iteration   2: 10.303 ops/ms
Iteration   3: 10.105 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.194 ±(99.9%) 1.832 ops/ms [Average]
  (min, avg, max) = (10.105, 10.194, 10.303), stdev = 0.100
  CI (99.9%): [8.362, 12.026] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 3.414 ops/ms
# Warmup Iteration   2: 7.753 ops/ms
# Warmup Iteration   3: 8.260 ops/ms
Iteration   1: 8.474 ops/ms
Iteration   2: 8.390 ops/ms
Iteration   3: 8.697 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.521 ±(99.9%) 2.896 ops/ms [Average]
  (min, avg, max) = (8.390, 8.521, 8.697), stdev = 0.159
  CI (99.9%): [5.625, 11.416] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 9.159 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.711 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.325 ±(99.9%) 0.004 ms/op
Iteration   1: 3.171 ±(99.9%) 0.002 ms/op
Iteration   2: 3.115 ±(99.9%) 0.002 ms/op
Iteration   3: 3.102 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.129 ±(99.9%) 0.675 ms/op [Average]
  (min, avg, max) = (3.102, 3.129, 3.171), stdev = 0.037
  CI (99.9%): [2.455, 3.804] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 6.631 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.286 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.140 ±(99.9%) 0.006 ms/op
Iteration   1: 2.987 ±(99.9%) 0.006 ms/op
Iteration   2: 3.111 ±(99.9%) 0.006 ms/op
Iteration   3: 3.137 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.078 ±(99.9%) 1.465 ms/op [Average]
  (min, avg, max) = (2.987, 3.078, 3.137), stdev = 0.080
  CI (99.9%): [1.613, 4.544] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 7.052 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.413 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.305 ±(99.9%) 0.002 ms/op
Iteration   1: 3.323 ±(99.9%) 0.004 ms/op
Iteration   2: 3.266 ±(99.9%) 0.005 ms/op
Iteration   3: 3.088 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.226 ±(99.9%) 2.241 ms/op [Average]
  (min, avg, max) = (3.088, 3.226, 3.323), stdev = 0.123
  CI (99.9%): [0.985, 5.466] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 9.212 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 4.128 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.842 ±(99.9%) 0.004 ms/op
Iteration   1: 3.679 ±(99.9%) 0.010 ms/op
Iteration   2: 3.614 ±(99.9%) 0.011 ms/op
Iteration   3: 3.578 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.624 ±(99.9%) 0.933 ms/op [Average]
  (min, avg, max) = (3.578, 3.624, 3.679), stdev = 0.051
  CI (99.9%): [2.691, 4.557] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 7.572 ±(99.9%) 0.085 ms/op
# Warmup Iteration   2: 3.636 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.148 ±(99.9%) 0.008 ms/op
Iteration   1: 3.121 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.499 ms/op
                 createUser·p0.50:   3.150 ms/op
                 createUser·p0.90:   3.265 ms/op
                 createUser·p0.95:   3.387 ms/op
                 createUser·p0.99:   5.054 ms/op
                 createUser·p0.999:  8.208 ms/op
                 createUser·p0.9999: 23.912 ms/op
                 createUser·p1.00:   25.362 ms/op

Iteration   2: 3.166 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.734 ms/op
                 createUser·p0.50:   3.035 ms/op
                 createUser·p0.90:   3.561 ms/op
                 createUser·p0.95:   4.100 ms/op
                 createUser·p0.99:   5.423 ms/op
                 createUser·p0.999:  15.712 ms/op
                 createUser·p0.9999: 20.939 ms/op
                 createUser·p1.00:   25.592 ms/op

Iteration   3: 3.180 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.438 ms/op
                 createUser·p0.50:   3.088 ms/op
                 createUser·p0.90:   3.580 ms/op
                 createUser·p0.95:   4.018 ms/op
                 createUser·p0.99:   5.513 ms/op
                 createUser·p0.999:  14.500 ms/op
                 createUser·p0.9999: 17.584 ms/op
                 createUser·p1.00:   18.809 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 304197
  mean =      3.155 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22059 
    [ 2.500,  5.000) = 277216 
    [ 5.000,  7.500) = 4107 
    [ 7.500, 10.000) = 429 
    [10.000, 12.500) = 51 
    [12.500, 15.000) = 55 
    [15.000, 17.500) = 91 
    [17.500, 20.000) = 102 
    [20.000, 22.500) = 56 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.734 ms/op
     p(50.0000) =      3.105 ms/op
     p(90.0000) =      3.449 ms/op
     p(95.0000) =      3.936 ms/op
     p(99.0000) =      5.390 ms/op
     p(99.9000) =     14.533 ms/op
     p(99.9900) =     22.512 ms/op
     p(99.9990) =     25.290 ms/op
     p(99.9999) =     25.592 ms/op
    p(100.0000) =     25.592 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 8.434 ±(99.9%) 0.093 ms/op
# Warmup Iteration   2: 3.382 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.033 ±(99.9%) 0.006 ms/op
Iteration   1: 3.016 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.073 ms/op
                 existUser·p0.50:   2.949 ms/op
                 existUser·p0.90:   3.248 ms/op
                 existUser·p0.95:   3.432 ms/op
                 existUser·p0.99:   5.226 ms/op
                 existUser·p0.999:  9.994 ms/op
                 existUser·p0.9999: 19.300 ms/op
                 existUser·p1.00:   19.792 ms/op

Iteration   2: 3.087 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.713 ms/op
                 existUser·p0.50:   3.011 ms/op
                 existUser·p0.90:   3.498 ms/op
                 existUser·p0.95:   3.891 ms/op
                 existUser·p0.99:   5.317 ms/op
                 existUser·p0.999:  12.386 ms/op
                 existUser·p0.9999: 25.896 ms/op
                 existUser·p1.00:   27.230 ms/op

Iteration   3: 3.002 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.011 ms/op
                 existUser·p0.50:   2.966 ms/op
                 existUser·p0.90:   3.158 ms/op
                 existUser·p0.95:   3.338 ms/op
                 existUser·p0.99:   4.932 ms/op
                 existUser·p0.999:  8.897 ms/op
                 existUser·p0.9999: 24.817 ms/op
                 existUser·p1.00:   25.592 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 316290
  mean =      3.035 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19365 
    [ 2.500,  5.000) = 292667 
    [ 5.000,  7.500) = 3652 
    [ 7.500, 10.000) = 243 
    [10.000, 12.500) = 66 
    [12.500, 15.000) = 41 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 124 
    [20.000, 22.500) = 60 
    [22.500, 25.000) = 36 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.713 ms/op
     p(50.0000) =      2.974 ms/op
     p(90.0000) =      3.260 ms/op
     p(95.0000) =      3.555 ms/op
     p(99.0000) =      5.210 ms/op
     p(99.9000) =     12.049 ms/op
     p(99.9900) =     25.002 ms/op
     p(99.9990) =     26.897 ms/op
     p(99.9999) =     27.230 ms/op
    p(100.0000) =     27.230 ms/op


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
# Warmup Iteration   1: 7.471 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 3.383 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.234 ±(99.9%) 0.010 ms/op
Iteration   1: 3.156 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.808 ms/op
                 getUser·p0.50:   3.027 ms/op
                 getUser·p0.90:   3.391 ms/op
                 getUser·p0.95:   3.629 ms/op
                 getUser·p0.99:   5.898 ms/op
                 getUser·p0.999:  13.943 ms/op
                 getUser·p0.9999: 24.554 ms/op
                 getUser·p1.00:   25.461 ms/op

Iteration   2: 3.167 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.186 ms/op
                 getUser·p0.50:   3.068 ms/op
                 getUser·p0.90:   3.469 ms/op
                 getUser·p0.95:   3.967 ms/op
                 getUser·p0.99:   5.276 ms/op
                 getUser·p0.999:  9.470 ms/op
                 getUser·p0.9999: 26.262 ms/op
                 getUser·p1.00:   27.951 ms/op

Iteration   3: 3.385 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.143 ms/op
                 getUser·p0.50:   3.256 ms/op
                 getUser·p0.90:   3.936 ms/op
                 getUser·p0.95:   4.964 ms/op
                 getUser·p0.99:   6.185 ms/op
                 getUser·p0.999:  15.876 ms/op
                 getUser·p0.9999: 33.456 ms/op
                 getUser·p1.00:   33.620 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 296750
  mean =      3.232 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11551 
    [ 2.500,  5.000) = 276900 
    [ 5.000,  7.500) = 7394 
    [ 7.500, 10.000) = 501 
    [10.000, 12.500) = 64 
    [12.500, 15.000) = 39 
    [15.000, 17.500) = 52 
    [17.500, 20.000) = 78 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 75 
    [25.000, 27.500) = 35 
    [27.500, 30.000) = 1 
    [30.000, 32.500) = 16 
    [32.500, 35.000) = 16 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.808 ms/op
     p(50.0000) =      3.113 ms/op
     p(90.0000) =      3.629 ms/op
     p(95.0000) =      4.186 ms/op
     p(99.0000) =      5.743 ms/op
     p(99.9000) =     15.745 ms/op
     p(99.9900) =     31.468 ms/op
     p(99.9990) =     33.554 ms/op
     p(99.9999) =     33.620 ms/op
    p(100.0000) =     33.620 ms/op


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
# Warmup Iteration   1: 9.266 ±(99.9%) 0.116 ms/op
# Warmup Iteration   2: 4.081 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.790 ±(99.9%) 0.012 ms/op
Iteration   1: 3.686 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.587 ms/op
                 listUser·p0.50:   3.641 ms/op
                 listUser·p0.90:   3.912 ms/op
                 listUser·p0.95:   4.170 ms/op
                 listUser·p0.99:   6.103 ms/op
                 listUser·p0.999:  15.434 ms/op
                 listUser·p0.9999: 20.403 ms/op
                 listUser·p1.00:   21.627 ms/op

Iteration   2: 3.863 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.277 ms/op
                 listUser·p0.50:   3.740 ms/op
                 listUser·p0.90:   4.301 ms/op
                 listUser·p0.95:   5.205 ms/op
                 listUser·p0.99:   7.267 ms/op
                 listUser·p0.999:  13.062 ms/op
                 listUser·p0.9999: 15.696 ms/op
                 listUser·p1.00:   15.761 ms/op

Iteration   3: 3.734 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.898 ms/op
                 listUser·p0.50:   3.690 ms/op
                 listUser·p0.90:   4.055 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   6.570 ms/op
                 listUser·p0.999:  13.550 ms/op
                 listUser·p0.9999: 18.678 ms/op
                 listUser·p1.00:   18.711 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 255321
  mean =      3.759 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 78 
    [ 2.500,  5.000) = 246852 
    [ 5.000,  7.500) = 6916 
    [ 7.500, 10.000) = 926 
    [10.000, 12.500) = 104 
    [12.500, 15.000) = 309 
    [15.000, 17.500) = 43 
    [17.500, 20.000) = 78 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.587 ms/op
     p(50.0000) =      3.695 ms/op
     p(90.0000) =      4.092 ms/op
     p(95.0000) =      4.440 ms/op
     p(99.0000) =      6.726 ms/op
     p(99.9000) =     13.517 ms/op
     p(99.9900) =     19.412 ms/op
     p(99.9990) =     21.170 ms/op
     p(99.9999) =     21.627 ms/op
    p(100.0000) =     21.627 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.922 ± 1.733  ops/ms
ClientPb.existUser                       thrpt       3  10.474 ± 3.594  ops/ms
ClientPb.getUser                         thrpt       3  10.194 ± 1.832  ops/ms
ClientPb.listUser                        thrpt       3   8.521 ± 2.896  ops/ms
ClientPb.createUser                       avgt       3   3.129 ± 0.675   ms/op
ClientPb.existUser                        avgt       3   3.078 ± 1.465   ms/op
ClientPb.getUser                          avgt       3   3.226 ± 2.241   ms/op
ClientPb.listUser                         avgt       3   3.624 ± 0.933   ms/op
ClientPb.createUser                     sample  304197   3.155 ± 0.004   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.734           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.105           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.449           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.936           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.390           ms/op
ClientPb.createUser:createUser·p0.999   sample          14.533           ms/op
ClientPb.createUser:createUser·p0.9999  sample          22.512           ms/op
ClientPb.createUser:createUser·p1.00    sample          25.592           ms/op
ClientPb.existUser                      sample  316290   3.035 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.713           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.974           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.260           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.555           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.210           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.049           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.002           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.230           ms/op
ClientPb.getUser                        sample  296750   3.232 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.808           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.113           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.629           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.186           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.743           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.745           ms/op
ClientPb.getUser:getUser·p0.9999        sample          31.468           ms/op
ClientPb.getUser:getUser·p1.00          sample          33.620           ms/op
ClientPb.listUser                       sample  255321   3.759 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.587           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.695           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.092           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.440           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.726           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.517           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.412           ms/op
ClientPb.listUser:listUser·p1.00        sample          21.627           ms/op
