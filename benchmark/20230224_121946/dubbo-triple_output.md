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
# Warmup Iteration   1: 2.631 ops/ms
# Warmup Iteration   2: 6.473 ops/ms
# Warmup Iteration   3: 9.197 ops/ms
Iteration   1: 9.900 ops/ms
Iteration   2: 9.862 ops/ms
Iteration   3: 9.746 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.836 ±(99.9%) 1.461 ops/ms [Average]
  (min, avg, max) = (9.746, 9.836, 9.900), stdev = 0.080
  CI (99.9%): [8.375, 11.297] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 3.606 ops/ms
# Warmup Iteration   2: 9.304 ops/ms
# Warmup Iteration   3: 9.792 ops/ms
Iteration   1: 10.262 ops/ms
Iteration   2: 10.612 ops/ms
Iteration   3: 10.124 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.333 ±(99.9%) 4.589 ops/ms [Average]
  (min, avg, max) = (10.124, 10.333, 10.612), stdev = 0.252
  CI (99.9%): [5.744, 14.922] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.888 ops/ms
# Warmup Iteration   2: 8.903 ops/ms
# Warmup Iteration   3: 10.047 ops/ms
Iteration   1: 9.851 ops/ms
Iteration   2: 10.284 ops/ms
Iteration   3: 10.043 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.060 ±(99.9%) 3.957 ops/ms [Average]
  (min, avg, max) = (9.851, 10.060, 10.284), stdev = 0.217
  CI (99.9%): [6.102, 14.017] (assumes normal distribution)


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
# Warmup Iteration   1: 3.124 ops/ms
# Warmup Iteration   2: 7.705 ops/ms
# Warmup Iteration   3: 8.381 ops/ms
Iteration   1: 8.539 ops/ms
Iteration   2: 8.589 ops/ms
Iteration   3: 8.706 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.612 ±(99.9%) 1.567 ops/ms [Average]
  (min, avg, max) = (8.539, 8.612, 8.706), stdev = 0.086
  CI (99.9%): [7.045, 10.178] (assumes normal distribution)


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
# Warmup Iteration   1: 8.354 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.653 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.355 ±(99.9%) 0.004 ms/op
Iteration   1: 3.217 ±(99.9%) 0.003 ms/op
Iteration   2: 3.145 ±(99.9%) 0.004 ms/op
Iteration   3: 3.188 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.183 ±(99.9%) 0.662 ms/op [Average]
  (min, avg, max) = (3.145, 3.183, 3.217), stdev = 0.036
  CI (99.9%): [2.521, 3.845] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 7.101 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.244 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.091 ±(99.9%) 0.003 ms/op
Iteration   1: 2.966 ±(99.9%) 0.004 ms/op
Iteration   2: 3.053 ±(99.9%) 0.005 ms/op
Iteration   3: 3.031 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.016 ±(99.9%) 0.826 ms/op [Average]
  (min, avg, max) = (2.966, 3.016, 3.053), stdev = 0.045
  CI (99.9%): [2.190, 3.843] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 7.855 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.356 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.178 ±(99.9%) 0.002 ms/op
Iteration   1: 3.284 ±(99.9%) 0.002 ms/op
Iteration   2: 3.104 ±(99.9%) 0.005 ms/op
Iteration   3: 3.246 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.211 ±(99.9%) 1.733 ms/op [Average]
  (min, avg, max) = (3.104, 3.211, 3.284), stdev = 0.095
  CI (99.9%): [1.478, 4.944] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 9.748 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 4.191 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.737 ±(99.9%) 0.010 ms/op
Iteration   1: 3.670 ±(99.9%) 0.008 ms/op
Iteration   2: 3.669 ±(99.9%) 0.006 ms/op
Iteration   3: 3.638 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.659 ±(99.9%) 0.335 ms/op [Average]
  (min, avg, max) = (3.638, 3.659, 3.670), stdev = 0.018
  CI (99.9%): [3.323, 3.994] (assumes normal distribution)


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
# Warmup Iteration   1: 8.189 ±(99.9%) 0.094 ms/op
# Warmup Iteration   2: 3.856 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.221 ±(99.9%) 0.008 ms/op
Iteration   1: 3.299 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.190 ms/op
                 createUser·p0.50:   3.146 ms/op
                 createUser·p0.90:   4.178 ms/op
                 createUser·p0.95:   4.555 ms/op
                 createUser·p0.99:   5.734 ms/op
                 createUser·p0.999:  11.160 ms/op
                 createUser·p0.9999: 19.704 ms/op
                 createUser·p1.00:   21.594 ms/op

Iteration   2: 3.311 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.374 ms/op
                 createUser·p0.50:   3.232 ms/op
                 createUser·p0.90:   3.777 ms/op
                 createUser·p0.95:   4.260 ms/op
                 createUser·p0.99:   5.792 ms/op
                 createUser·p0.999:  17.199 ms/op
                 createUser·p0.9999: 21.791 ms/op
                 createUser·p1.00:   22.348 ms/op

Iteration   3: 3.137 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.323 ms/op
                 createUser·p0.50:   3.142 ms/op
                 createUser·p0.90:   3.293 ms/op
                 createUser·p0.95:   3.498 ms/op
                 createUser·p0.99:   5.292 ms/op
                 createUser·p0.999:  18.223 ms/op
                 createUser·p0.9999: 22.482 ms/op
                 createUser·p1.00:   23.364 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 295560
  mean =      3.247 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24389 
    [ 2.500,  5.000) = 263695 
    [ 5.000,  7.500) = 6700 
    [ 7.500, 10.000) = 375 
    [10.000, 12.500) = 26 
    [12.500, 15.000) = 18 
    [15.000, 17.500) = 52 
    [17.500, 20.000) = 169 
    [20.000, 22.500) = 126 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.190 ms/op
     p(50.0000) =      3.174 ms/op
     p(90.0000) =      3.686 ms/op
     p(95.0000) =      4.375 ms/op
     p(99.0000) =      5.628 ms/op
     p(99.9000) =     17.760 ms/op
     p(99.9900) =     21.889 ms/op
     p(99.9990) =     22.978 ms/op
     p(99.9999) =     23.364 ms/op
    p(100.0000) =     23.364 ms/op


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
# Warmup Iteration   1: 6.918 ±(99.9%) 0.084 ms/op
# Warmup Iteration   2: 3.312 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.083 ±(99.9%) 0.007 ms/op
Iteration   1: 3.035 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.904 ms/op
                 existUser·p0.50:   2.990 ms/op
                 existUser·p0.90:   3.183 ms/op
                 existUser·p0.95:   3.547 ms/op
                 existUser·p0.99:   5.404 ms/op
                 existUser·p0.999:  9.272 ms/op
                 existUser·p0.9999: 20.527 ms/op
                 existUser·p1.00:   21.791 ms/op

Iteration   2: 3.044 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.354 ms/op
                 existUser·p0.50:   2.978 ms/op
                 existUser·p0.90:   3.289 ms/op
                 existUser·p0.95:   3.514 ms/op
                 existUser·p0.99:   4.753 ms/op
                 existUser·p0.999:  11.928 ms/op
                 existUser·p0.9999: 35.914 ms/op
                 existUser·p1.00:   37.814 ms/op

Iteration   3: 3.030 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.305 ms/op
                 existUser·p0.50:   2.941 ms/op
                 existUser·p0.90:   3.281 ms/op
                 existUser·p0.95:   3.482 ms/op
                 existUser·p0.99:   5.054 ms/op
                 existUser·p0.999:  7.941 ms/op
                 existUser·p0.9999: 24.459 ms/op
                 existUser·p1.00:   25.985 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 316216
  mean =      3.036 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16144 
    [ 2.500,  5.000) = 296246 
    [ 5.000,  7.500) = 3190 
    [ 7.500, 10.000) = 294 
    [10.000, 12.500) = 52 
    [12.500, 15.000) = 2 
    [15.000, 17.500) = 9 
    [17.500, 20.000) = 137 
    [20.000, 22.500) = 72 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 7 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 9 
    [35.000, 37.500) = 21 

  Percentiles, ms/op:
      p(0.0000) =      0.904 ms/op
     p(50.0000) =      2.966 ms/op
     p(90.0000) =      3.260 ms/op
     p(95.0000) =      3.510 ms/op
     p(99.0000) =      5.120 ms/op
     p(99.9000) =     11.527 ms/op
     p(99.9900) =     34.734 ms/op
     p(99.9990) =     37.357 ms/op
     p(99.9999) =     37.814 ms/op
    p(100.0000) =     37.814 ms/op


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
# Warmup Iteration   1: 8.573 ±(99.9%) 0.093 ms/op
# Warmup Iteration   2: 3.401 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.306 ±(99.9%) 0.010 ms/op
Iteration   1: 3.249 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.039 ms/op
                 getUser·p0.50:   3.043 ms/op
                 getUser·p0.90:   3.551 ms/op
                 getUser·p0.95:   4.923 ms/op
                 getUser·p0.99:   6.349 ms/op
                 getUser·p0.999:  18.285 ms/op
                 getUser·p0.9999: 27.694 ms/op
                 getUser·p1.00:   27.984 ms/op

Iteration   2: 3.239 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.890 ms/op
                 getUser·p0.50:   3.183 ms/op
                 getUser·p0.90:   3.777 ms/op
                 getUser·p0.95:   4.170 ms/op
                 getUser·p0.99:   5.505 ms/op
                 getUser·p0.999:  9.097 ms/op
                 getUser·p0.9999: 22.446 ms/op
                 getUser·p1.00:   23.396 ms/op

Iteration   3: 3.233 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.999 ms/op
                 getUser·p0.50:   3.187 ms/op
                 getUser·p0.90:   3.695 ms/op
                 getUser·p0.95:   4.100 ms/op
                 getUser·p0.99:   5.759 ms/op
                 getUser·p0.999:  13.912 ms/op
                 getUser·p0.9999: 20.891 ms/op
                 getUser·p1.00:   22.020 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 296048
  mean =      3.240 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22407 
    [ 2.500,  5.000) = 264809 
    [ 5.000,  7.500) = 7902 
    [ 7.500, 10.000) = 496 
    [10.000, 12.500) = 60 
    [12.500, 15.000) = 54 
    [15.000, 17.500) = 51 
    [17.500, 20.000) = 53 
    [20.000, 22.500) = 158 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 20 

  Percentiles, ms/op:
      p(0.0000) =      0.890 ms/op
     p(50.0000) =      3.158 ms/op
     p(90.0000) =      3.699 ms/op
     p(95.0000) =      4.252 ms/op
     p(99.0000) =      5.997 ms/op
     p(99.9000) =     16.727 ms/op
     p(99.9900) =     25.834 ms/op
     p(99.9990) =     27.887 ms/op
     p(99.9999) =     27.984 ms/op
    p(100.0000) =     27.984 ms/op


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
# Warmup Iteration   1: 8.480 ±(99.9%) 0.113 ms/op
# Warmup Iteration   2: 4.094 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.765 ±(99.9%) 0.011 ms/op
Iteration   1: 3.742 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.901 ms/op
                 listUser·p0.50:   3.650 ms/op
                 listUser·p0.90:   3.944 ms/op
                 listUser·p0.95:   4.538 ms/op
                 listUser·p0.99:   6.728 ms/op
                 listUser·p0.999:  13.418 ms/op
                 listUser·p0.9999: 17.465 ms/op
                 listUser·p1.00:   18.711 ms/op

Iteration   2: 3.746 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.253 ms/op
                 listUser·p0.50:   3.650 ms/op
                 listUser·p0.90:   4.202 ms/op
                 listUser·p0.95:   4.604 ms/op
                 listUser·p0.99:   6.742 ms/op
                 listUser·p0.999:  13.369 ms/op
                 listUser·p0.9999: 16.171 ms/op
                 listUser·p1.00:   16.220 ms/op

Iteration   3: 3.698 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.224 ms/op
                 listUser·p0.50:   3.559 ms/op
                 listUser·p0.90:   4.043 ms/op
                 listUser·p0.95:   4.284 ms/op
                 listUser·p0.99:   7.157 ms/op
                 listUser·p0.999:  13.179 ms/op
                 listUser·p0.9999: 19.137 ms/op
                 listUser·p1.00:   21.889 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 257377
  mean =      3.729 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 79 
    [ 2.500,  5.000) = 248261 
    [ 5.000,  7.500) = 7486 
    [ 7.500, 10.000) = 891 
    [10.000, 12.500) = 225 
    [12.500, 15.000) = 329 
    [15.000, 17.500) = 70 
    [17.500, 20.000) = 35 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.901 ms/op
     p(50.0000) =      3.633 ms/op
     p(90.0000) =      4.076 ms/op
     p(95.0000) =      4.481 ms/op
     p(99.0000) =      6.865 ms/op
     p(99.9000) =     13.402 ms/op
     p(99.9900) =     17.662 ms/op
     p(99.9990) =     19.183 ms/op
     p(99.9999) =     21.889 ms/op
    p(100.0000) =     21.889 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.836 ± 1.461  ops/ms
ClientPb.existUser                       thrpt       3  10.333 ± 4.589  ops/ms
ClientPb.getUser                         thrpt       3  10.060 ± 3.957  ops/ms
ClientPb.listUser                        thrpt       3   8.612 ± 1.567  ops/ms
ClientPb.createUser                       avgt       3   3.183 ± 0.662   ms/op
ClientPb.existUser                        avgt       3   3.016 ± 0.826   ms/op
ClientPb.getUser                          avgt       3   3.211 ± 1.733   ms/op
ClientPb.listUser                         avgt       3   3.659 ± 0.335   ms/op
ClientPb.createUser                     sample  295560   3.247 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.190           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.174           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.686           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.375           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.628           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.760           ms/op
ClientPb.createUser:createUser·p0.9999  sample          21.889           ms/op
ClientPb.createUser:createUser·p1.00    sample          23.364           ms/op
ClientPb.existUser                      sample  316216   3.036 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.904           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.966           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.260           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.510           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.120           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.527           ms/op
ClientPb.existUser:existUser·p0.9999    sample          34.734           ms/op
ClientPb.existUser:existUser·p1.00      sample          37.814           ms/op
ClientPb.getUser                        sample  296048   3.240 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.890           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.158           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.699           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.252           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.997           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.727           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.834           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.984           ms/op
ClientPb.listUser                       sample  257377   3.729 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.901           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.633           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.076           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.481           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.865           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.402           ms/op
ClientPb.listUser:listUser·p0.9999      sample          17.662           ms/op
ClientPb.listUser:listUser·p1.00        sample          21.889           ms/op
