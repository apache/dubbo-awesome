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
# Warmup Iteration   1: 2.619 ops/ms
# Warmup Iteration   2: 6.044 ops/ms
# Warmup Iteration   3: 9.556 ops/ms
Iteration   1: 9.449 ops/ms
Iteration   2: 9.829 ops/ms
Iteration   3: 9.712 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.664 ±(99.9%) 3.552 ops/ms [Average]
  (min, avg, max) = (9.449, 9.664, 9.829), stdev = 0.195
  CI (99.9%): [6.112, 13.216] (assumes normal distribution)


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
# Warmup Iteration   1: 3.169 ops/ms
# Warmup Iteration   2: 9.265 ops/ms
# Warmup Iteration   3: 10.389 ops/ms
Iteration   1: 10.617 ops/ms
Iteration   2: 10.147 ops/ms
Iteration   3: 10.080 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.281 ±(99.9%) 5.340 ops/ms [Average]
  (min, avg, max) = (10.080, 10.281, 10.617), stdev = 0.293
  CI (99.9%): [4.941, 15.621] (assumes normal distribution)


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
# Warmup Iteration   1: 3.618 ops/ms
# Warmup Iteration   2: 9.240 ops/ms
# Warmup Iteration   3: 9.796 ops/ms
Iteration   1: 10.239 ops/ms
Iteration   2: 10.260 ops/ms
Iteration   3: 10.136 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.212 ±(99.9%) 1.217 ops/ms [Average]
  (min, avg, max) = (10.136, 10.212, 10.260), stdev = 0.067
  CI (99.9%): [8.994, 11.429] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.653 ops/ms
# Warmup Iteration   2: 7.783 ops/ms
# Warmup Iteration   3: 8.558 ops/ms
Iteration   1: 8.646 ops/ms
Iteration   2: 8.397 ops/ms
Iteration   3: 8.749 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.597 ±(99.9%) 3.298 ops/ms [Average]
  (min, avg, max) = (8.397, 8.597, 8.749), stdev = 0.181
  CI (99.9%): [5.300, 11.895] (assumes normal distribution)


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
# Warmup Iteration   1: 8.678 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.629 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.186 ±(99.9%) 0.010 ms/op
Iteration   1: 3.176 ±(99.9%) 0.007 ms/op
Iteration   2: 3.142 ±(99.9%) 0.011 ms/op
Iteration   3: 3.308 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.209 ±(99.9%) 1.594 ms/op [Average]
  (min, avg, max) = (3.142, 3.209, 3.308), stdev = 0.087
  CI (99.9%): [1.615, 4.802] (assumes normal distribution)


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
# Warmup Iteration   1: 7.947 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.327 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.204 ±(99.9%) 0.007 ms/op
Iteration   1: 3.079 ±(99.9%) 0.006 ms/op
Iteration   2: 2.956 ±(99.9%) 0.005 ms/op
Iteration   3: 3.008 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.014 ±(99.9%) 1.123 ms/op [Average]
  (min, avg, max) = (2.956, 3.014, 3.079), stdev = 0.062
  CI (99.9%): [1.891, 4.137] (assumes normal distribution)


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
# Warmup Iteration   1: 7.510 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.496 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.366 ±(99.9%) 0.004 ms/op
Iteration   1: 3.226 ±(99.9%) 0.006 ms/op
Iteration   2: 3.259 ±(99.9%) 0.004 ms/op
Iteration   3: 3.251 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.245 ±(99.9%) 0.318 ms/op [Average]
  (min, avg, max) = (3.226, 3.245, 3.259), stdev = 0.017
  CI (99.9%): [2.927, 3.563] (assumes normal distribution)


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
# Warmup Iteration   1: 8.958 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.062 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.847 ±(99.9%) 0.006 ms/op
Iteration   1: 3.711 ±(99.9%) 0.007 ms/op
Iteration   2: 3.813 ±(99.9%) 0.006 ms/op
Iteration   3: 3.724 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.749 ±(99.9%) 1.006 ms/op [Average]
  (min, avg, max) = (3.711, 3.749, 3.813), stdev = 0.055
  CI (99.9%): [2.743, 4.755] (assumes normal distribution)


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
# Warmup Iteration   1: 7.325 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 3.759 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.182 ±(99.9%) 0.008 ms/op
Iteration   1: 3.179 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.438 ms/op
                 createUser·p0.50:   3.109 ms/op
                 createUser·p0.90:   3.572 ms/op
                 createUser·p0.95:   3.822 ms/op
                 createUser·p0.99:   5.374 ms/op
                 createUser·p0.999:  9.503 ms/op
                 createUser·p0.9999: 20.480 ms/op
                 createUser·p1.00:   21.332 ms/op

Iteration   2: 3.306 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.758 ms/op
                 createUser·p0.50:   3.281 ms/op
                 createUser·p0.90:   3.699 ms/op
                 createUser·p0.95:   3.957 ms/op
                 createUser·p0.99:   5.292 ms/op
                 createUser·p0.999:  13.050 ms/op
                 createUser·p0.9999: 24.847 ms/op
                 createUser·p1.00:   25.461 ms/op

Iteration   3: 3.248 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.632 ms/op
                 createUser·p0.50:   3.133 ms/op
                 createUser·p0.90:   3.625 ms/op
                 createUser·p0.95:   3.912 ms/op
                 createUser·p0.99:   6.390 ms/op
                 createUser·p0.999:  15.545 ms/op
                 createUser·p0.9999: 27.169 ms/op
                 createUser·p1.00:   28.508 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 295957
  mean =      3.244 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17126 
    [ 2.500,  5.000) = 272735 
    [ 5.000,  7.500) = 5380 
    [ 7.500, 10.000) = 317 
    [10.000, 12.500) = 92 
    [12.500, 15.000) = 10 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 104 
    [20.000, 22.500) = 72 
    [22.500, 25.000) = 48 
    [25.000, 27.500) = 36 

  Percentiles, ms/op:
      p(0.0000) =      0.758 ms/op
     p(50.0000) =      3.203 ms/op
     p(90.0000) =      3.629 ms/op
     p(95.0000) =      3.895 ms/op
     p(99.0000) =      5.562 ms/op
     p(99.9000) =     15.060 ms/op
     p(99.9900) =     25.540 ms/op
     p(99.9990) =     28.444 ms/op
     p(99.9999) =     28.508 ms/op
    p(100.0000) =     28.508 ms/op


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
# Warmup Iteration   1: 6.839 ±(99.9%) 0.082 ms/op
# Warmup Iteration   2: 3.352 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.134 ±(99.9%) 0.007 ms/op
Iteration   1: 3.265 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.157 ms/op
                 existUser·p0.50:   3.133 ms/op
                 existUser·p0.90:   3.969 ms/op
                 existUser·p0.95:   4.194 ms/op
                 existUser·p0.99:   5.808 ms/op
                 existUser·p0.999:  14.299 ms/op
                 existUser·p0.9999: 24.543 ms/op
                 existUser·p1.00:   25.100 ms/op

Iteration   2: 3.151 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.278 ms/op
                 existUser·p0.50:   3.142 ms/op
                 existUser·p0.90:   3.437 ms/op
                 existUser·p0.95:   3.723 ms/op
                 existUser·p0.99:   5.210 ms/op
                 existUser·p0.999:  8.577 ms/op
                 existUser·p0.9999: 27.062 ms/op
                 existUser·p1.00:   27.689 ms/op

Iteration   3: 3.126 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.304 ms/op
                 existUser·p0.50:   3.056 ms/op
                 existUser·p0.90:   3.432 ms/op
                 existUser·p0.95:   3.883 ms/op
                 existUser·p0.99:   5.825 ms/op
                 existUser·p0.999:  7.829 ms/op
                 existUser·p0.9999: 23.389 ms/op
                 existUser·p1.00:   25.395 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 301731
  mean =      3.180 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23700 
    [ 2.500,  5.000) = 271466 
    [ 5.000,  7.500) = 5945 
    [ 7.500, 10.000) = 351 
    [10.000, 12.500) = 7 
    [12.500, 15.000) = 6 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 133 
    [22.500, 25.000) = 62 
    [25.000, 27.500) = 33 

  Percentiles, ms/op:
      p(0.0000) =      0.304 ms/op
     p(50.0000) =      3.121 ms/op
     p(90.0000) =      3.609 ms/op
     p(95.0000) =      4.055 ms/op
     p(99.0000) =      5.669 ms/op
     p(99.9000) =      9.081 ms/op
     p(99.9900) =     26.340 ms/op
     p(99.9990) =     27.457 ms/op
     p(99.9999) =     27.689 ms/op
    p(100.0000) =     27.689 ms/op


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
# Warmup Iteration   1: 8.011 ±(99.9%) 0.093 ms/op
# Warmup Iteration   2: 3.370 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.275 ±(99.9%) 0.010 ms/op
Iteration   1: 3.256 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.298 ms/op
                 getUser·p0.50:   3.199 ms/op
                 getUser·p0.90:   3.736 ms/op
                 getUser·p0.95:   4.186 ms/op
                 getUser·p0.99:   5.685 ms/op
                 getUser·p0.999:  18.801 ms/op
                 getUser·p0.9999: 20.393 ms/op
                 getUser·p1.00:   21.266 ms/op

Iteration   2: 3.191 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.137 ms/op
                 getUser·p0.50:   3.150 ms/op
                 getUser·p0.90:   3.604 ms/op
                 getUser·p0.95:   3.908 ms/op
                 getUser·p0.99:   5.661 ms/op
                 getUser·p0.999:  9.748 ms/op
                 getUser·p0.9999: 22.774 ms/op
                 getUser·p1.00:   24.248 ms/op

Iteration   3: 3.185 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.868 ms/op
                 getUser·p0.50:   3.060 ms/op
                 getUser·p0.90:   3.498 ms/op
                 getUser·p0.95:   4.059 ms/op
                 getUser·p0.99:   5.571 ms/op
                 getUser·p0.999:  18.549 ms/op
                 getUser·p0.9999: 26.147 ms/op
                 getUser·p1.00:   27.689 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 298964
  mean =      3.211 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24319 
    [ 2.500,  5.000) = 267771 
    [ 5.000,  7.500) = 6105 
    [ 7.500, 10.000) = 375 
    [10.000, 12.500) = 40 
    [12.500, 15.000) = 2 
    [15.000, 17.500) = 12 
    [17.500, 20.000) = 172 
    [20.000, 22.500) = 123 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 24 

  Percentiles, ms/op:
      p(0.0000) =      0.868 ms/op
     p(50.0000) =      3.150 ms/op
     p(90.0000) =      3.625 ms/op
     p(95.0000) =      4.043 ms/op
     p(99.0000) =      5.661 ms/op
     p(99.9000) =     18.581 ms/op
     p(99.9900) =     23.944 ms/op
     p(99.9990) =     27.396 ms/op
     p(99.9999) =     27.689 ms/op
    p(100.0000) =     27.689 ms/op


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
# Warmup Iteration   1: 9.941 ±(99.9%) 0.128 ms/op
# Warmup Iteration   2: 4.139 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.800 ±(99.9%) 0.011 ms/op
Iteration   1: 3.828 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.530 ms/op
                 listUser·p0.50:   3.674 ms/op
                 listUser·p0.90:   4.145 ms/op
                 listUser·p0.95:   4.694 ms/op
                 listUser·p0.99:   7.062 ms/op
                 listUser·p0.999:  14.433 ms/op
                 listUser·p0.9999: 18.285 ms/op
                 listUser·p1.00:   19.333 ms/op

Iteration   2: 3.688 ±(99.9%) 0.007 ms/op
                 listUser·p0.00:   2.470 ms/op
                 listUser·p0.50:   3.580 ms/op
                 listUser·p0.90:   4.039 ms/op
                 listUser·p0.95:   4.235 ms/op
                 listUser·p0.99:   6.570 ms/op
                 listUser·p0.999:  12.669 ms/op
                 listUser·p0.9999: 15.685 ms/op
                 listUser·p1.00:   16.089 ms/op

Iteration   3: 3.718 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.944 ms/op
                 listUser·p0.50:   3.686 ms/op
                 listUser·p0.90:   3.817 ms/op
                 listUser·p0.95:   4.182 ms/op
                 listUser·p0.99:   6.627 ms/op
                 listUser·p0.999:  12.747 ms/op
                 listUser·p0.9999: 18.933 ms/op
                 listUser·p1.00:   20.283 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 256258
  mean =      3.744 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 41 
    [ 2.500,  5.000) = 249278 
    [ 5.000,  7.500) = 5289 
    [ 7.500, 10.000) = 1016 
    [10.000, 12.500) = 248 
    [12.500, 15.000) = 273 
    [15.000, 17.500) = 61 
    [17.500, 20.000) = 49 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.530 ms/op
     p(50.0000) =      3.654 ms/op
     p(90.0000) =      4.039 ms/op
     p(95.0000) =      4.317 ms/op
     p(99.0000) =      6.824 ms/op
     p(99.9000) =     13.066 ms/op
     p(99.9900) =     18.264 ms/op
     p(99.9990) =     20.218 ms/op
     p(99.9999) =     20.283 ms/op
    p(100.0000) =     20.283 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.664 ± 3.552  ops/ms
ClientPb.existUser                       thrpt       3  10.281 ± 5.340  ops/ms
ClientPb.getUser                         thrpt       3  10.212 ± 1.217  ops/ms
ClientPb.listUser                        thrpt       3   8.597 ± 3.298  ops/ms
ClientPb.createUser                       avgt       3   3.209 ± 1.594   ms/op
ClientPb.existUser                        avgt       3   3.014 ± 1.123   ms/op
ClientPb.getUser                          avgt       3   3.245 ± 0.318   ms/op
ClientPb.listUser                         avgt       3   3.749 ± 1.006   ms/op
ClientPb.createUser                     sample  295957   3.244 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.758           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.203           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.629           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.895           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.562           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.060           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.540           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.508           ms/op
ClientPb.existUser                      sample  301731   3.180 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.304           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.121           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.609           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.055           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.669           ms/op
ClientPb.existUser:existUser·p0.999     sample           9.081           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.340           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.689           ms/op
ClientPb.getUser                        sample  298964   3.211 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.868           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.150           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.625           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.043           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.661           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.581           ms/op
ClientPb.getUser:getUser·p0.9999        sample          23.944           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.689           ms/op
ClientPb.listUser                       sample  256258   3.744 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.530           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.654           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.039           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.317           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.824           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.066           ms/op
ClientPb.listUser:listUser·p0.9999      sample          18.264           ms/op
ClientPb.listUser:listUser·p1.00        sample          20.283           ms/op
