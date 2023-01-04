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
# Warmup Iteration   1: 2.540 ops/ms
# Warmup Iteration   2: 5.552 ops/ms
# Warmup Iteration   3: 9.225 ops/ms
Iteration   1: 9.511 ops/ms
Iteration   2: 10.362 ops/ms
Iteration   3: 10.328 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  10.067 ±(99.9%) 8.798 ops/ms [Average]
  (min, avg, max) = (9.511, 10.067, 10.362), stdev = 0.482
  CI (99.9%): [1.269, 18.864] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.980 ops/ms
# Warmup Iteration   2: 9.185 ops/ms
# Warmup Iteration   3: 9.732 ops/ms
Iteration   1: 10.839 ops/ms
Iteration   2: 10.546 ops/ms
Iteration   3: 10.507 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.631 ±(99.9%) 3.309 ops/ms [Average]
  (min, avg, max) = (10.507, 10.631, 10.839), stdev = 0.181
  CI (99.9%): [7.322, 13.939] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.770 ops/ms
# Warmup Iteration   2: 9.129 ops/ms
# Warmup Iteration   3: 9.740 ops/ms
Iteration   1: 9.989 ops/ms
Iteration   2: 10.362 ops/ms
Iteration   3: 10.022 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.124 ±(99.9%) 3.768 ops/ms [Average]
  (min, avg, max) = (9.989, 10.124, 10.362), stdev = 0.207
  CI (99.9%): [6.356, 13.892] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 3.904 ops/ms
# Warmup Iteration   2: 7.931 ops/ms
# Warmup Iteration   3: 8.333 ops/ms
Iteration   1: 8.567 ops/ms
Iteration   2: 8.844 ops/ms
Iteration   3: 8.828 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.746 ±(99.9%) 2.830 ops/ms [Average]
  (min, avg, max) = (8.567, 8.746, 8.844), stdev = 0.155
  CI (99.9%): [5.917, 11.576] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 8.099 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.374 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.200 ±(99.9%) 0.006 ms/op
Iteration   1: 3.209 ±(99.9%) 0.006 ms/op
Iteration   2: 3.087 ±(99.9%) 0.005 ms/op
Iteration   3: 3.195 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.164 ±(99.9%) 1.215 ms/op [Average]
  (min, avg, max) = (3.087, 3.164, 3.209), stdev = 0.067
  CI (99.9%): [1.948, 4.379] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 7.110 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.397 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.974 ±(99.9%) 0.003 ms/op
Iteration   1: 2.952 ±(99.9%) 0.005 ms/op
Iteration   2: 2.991 ±(99.9%) 0.003 ms/op
Iteration   3: 3.094 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.012 ±(99.9%) 1.337 ms/op [Average]
  (min, avg, max) = (2.952, 3.012, 3.094), stdev = 0.073
  CI (99.9%): [1.676, 4.349] (assumes normal distribution)


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
# Warmup Iteration   1: 6.944 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.315 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.274 ±(99.9%) 0.004 ms/op
Iteration   1: 3.096 ±(99.9%) 0.004 ms/op
Iteration   2: 3.163 ±(99.9%) 0.004 ms/op
Iteration   3: 3.089 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.116 ±(99.9%) 0.750 ms/op [Average]
  (min, avg, max) = (3.089, 3.116, 3.163), stdev = 0.041
  CI (99.9%): [2.366, 3.866] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 8.992 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 4.081 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.806 ±(99.9%) 0.004 ms/op
Iteration   1: 3.590 ±(99.9%) 0.010 ms/op
Iteration   2: 3.662 ±(99.9%) 0.008 ms/op
Iteration   3: 3.636 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.629 ±(99.9%) 0.661 ms/op [Average]
  (min, avg, max) = (3.590, 3.629, 3.662), stdev = 0.036
  CI (99.9%): [2.968, 4.290] (assumes normal distribution)


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
# Warmup Iteration   1: 7.730 ±(99.9%) 0.089 ms/op
# Warmup Iteration   2: 3.617 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.264 ±(99.9%) 0.009 ms/op
Iteration   1: 3.144 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.436 ms/op
                 createUser·p0.50:   3.052 ms/op
                 createUser·p0.90:   3.559 ms/op
                 createUser·p0.95:   3.916 ms/op
                 createUser·p0.99:   5.005 ms/op
                 createUser·p0.999:  10.945 ms/op
                 createUser·p0.9999: 22.625 ms/op
                 createUser·p1.00:   23.527 ms/op

Iteration   2: 3.221 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.212 ms/op
                 createUser·p0.50:   3.129 ms/op
                 createUser·p0.90:   3.531 ms/op
                 createUser·p0.95:   4.055 ms/op
                 createUser·p0.99:   6.545 ms/op
                 createUser·p0.999:  11.979 ms/op
                 createUser·p0.9999: 40.898 ms/op
                 createUser·p1.00:   45.482 ms/op

Iteration   3: 3.166 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.620 ms/op
                 createUser·p0.50:   3.011 ms/op
                 createUser·p0.90:   3.551 ms/op
                 createUser·p0.95:   3.887 ms/op
                 createUser·p0.99:   5.947 ms/op
                 createUser·p0.999:  15.221 ms/op
                 createUser·p0.9999: 24.180 ms/op
                 createUser·p1.00:   25.494 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 302182
  mean =      3.177 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 295954 
    [ 5.000, 10.000) = 5807 
    [10.000, 15.000) = 126 
    [15.000, 20.000) = 167 
    [20.000, 25.000) = 89 
    [25.000, 30.000) = 7 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 19 
    [40.000, 45.000) = 12 

  Percentiles, ms/op:
      p(0.0000) =      1.212 ms/op
     p(50.0000) =      3.076 ms/op
     p(90.0000) =      3.551 ms/op
     p(95.0000) =      3.944 ms/op
     p(99.0000) =      6.005 ms/op
     p(99.9000) =     14.595 ms/op
     p(99.9900) =     37.079 ms/op
     p(99.9990) =     44.624 ms/op
     p(99.9999) =     45.482 ms/op
    p(100.0000) =     45.482 ms/op


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
# Warmup Iteration   1: 7.152 ±(99.9%) 0.082 ms/op
# Warmup Iteration   2: 3.342 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.097 ±(99.9%) 0.007 ms/op
Iteration   1: 3.104 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.464 ms/op
                 existUser·p0.50:   3.080 ms/op
                 existUser·p0.90:   3.297 ms/op
                 existUser·p0.95:   4.022 ms/op
                 existUser·p0.99:   5.054 ms/op
                 existUser·p0.999:  9.354 ms/op
                 existUser·p0.9999: 25.713 ms/op
                 existUser·p1.00:   27.394 ms/op

Iteration   2: 3.031 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.235 ms/op
                 existUser·p0.50:   2.933 ms/op
                 existUser·p0.90:   3.314 ms/op
                 existUser·p0.95:   3.486 ms/op
                 existUser·p0.99:   4.637 ms/op
                 existUser·p0.999:  17.302 ms/op
                 existUser·p0.9999: 21.332 ms/op
                 existUser·p1.00:   22.708 ms/op

Iteration   3: 2.991 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.618 ms/op
                 existUser·p0.50:   2.925 ms/op
                 existUser·p0.90:   3.187 ms/op
                 existUser·p0.95:   3.351 ms/op
                 existUser·p0.99:   5.300 ms/op
                 existUser·p0.999:  7.670 ms/op
                 existUser·p0.9999: 21.965 ms/op
                 existUser·p1.00:   23.069 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 315449
  mean =      3.041 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18637 
    [ 2.500,  5.000) = 292876 
    [ 5.000,  7.500) = 3419 
    [ 7.500, 10.000) = 149 
    [10.000, 12.500) = 48 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 62 
    [17.500, 20.000) = 94 
    [20.000, 22.500) = 95 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 22 

  Percentiles, ms/op:
      p(0.0000) =      1.235 ms/op
     p(50.0000) =      2.990 ms/op
     p(90.0000) =      3.269 ms/op
     p(95.0000) =      3.531 ms/op
     p(99.0000) =      5.079 ms/op
     p(99.9000) =     14.221 ms/op
     p(99.9900) =     24.409 ms/op
     p(99.9990) =     27.165 ms/op
     p(99.9999) =     27.394 ms/op
    p(100.0000) =     27.394 ms/op


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
# Warmup Iteration   1: 7.689 ±(99.9%) 0.085 ms/op
# Warmup Iteration   2: 3.925 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.244 ±(99.9%) 0.009 ms/op
Iteration   1: 3.201 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.055 ms/op
                 getUser·p0.50:   3.117 ms/op
                 getUser·p0.90:   3.543 ms/op
                 getUser·p0.95:   4.194 ms/op
                 getUser·p0.99:   5.652 ms/op
                 getUser·p0.999:  18.088 ms/op
                 getUser·p0.9999: 25.461 ms/op
                 getUser·p1.00:   26.804 ms/op

Iteration   2: 3.167 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.243 ms/op
                 getUser·p0.50:   3.080 ms/op
                 getUser·p0.90:   3.482 ms/op
                 getUser·p0.95:   3.727 ms/op
                 getUser·p0.99:   5.620 ms/op
                 getUser·p0.999:  13.585 ms/op
                 getUser·p0.9999: 26.741 ms/op
                 getUser·p1.00:   28.606 ms/op

Iteration   3: 3.323 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.456 ms/op
                 getUser·p0.50:   3.215 ms/op
                 getUser·p0.90:   3.789 ms/op
                 getUser·p0.95:   4.432 ms/op
                 getUser·p0.99:   6.046 ms/op
                 getUser·p0.999:  15.315 ms/op
                 getUser·p0.9999: 21.140 ms/op
                 getUser·p1.00:   22.053 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 297050
  mean =      3.229 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16099 
    [ 2.500,  5.000) = 272859 
    [ 5.000,  7.500) = 7082 
    [ 7.500, 10.000) = 581 
    [10.000, 12.500) = 34 
    [12.500, 15.000) = 70 
    [15.000, 17.500) = 49 
    [17.500, 20.000) = 107 
    [20.000, 22.500) = 76 
    [22.500, 25.000) = 46 
    [25.000, 27.500) = 43 

  Percentiles, ms/op:
      p(0.0000) =      1.055 ms/op
     p(50.0000) =      3.146 ms/op
     p(90.0000) =      3.604 ms/op
     p(95.0000) =      4.145 ms/op
     p(99.0000) =      5.784 ms/op
     p(99.9000) =     16.219 ms/op
     p(99.9900) =     25.733 ms/op
     p(99.9990) =     27.631 ms/op
     p(99.9999) =     28.606 ms/op
    p(100.0000) =     28.606 ms/op


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
# Warmup Iteration   1: 9.168 ±(99.9%) 0.118 ms/op
# Warmup Iteration   2: 4.160 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.731 ±(99.9%) 0.011 ms/op
Iteration   1: 3.678 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.477 ms/op
                 listUser·p0.50:   3.588 ms/op
                 listUser·p0.90:   4.047 ms/op
                 listUser·p0.95:   4.309 ms/op
                 listUser·p0.99:   6.414 ms/op
                 listUser·p0.999:  13.566 ms/op
                 listUser·p0.9999: 19.100 ms/op
                 listUser·p1.00:   19.792 ms/op

Iteration   2: 3.597 ±(99.9%) 0.007 ms/op
                 listUser·p0.00:   1.888 ms/op
                 listUser·p0.50:   3.535 ms/op
                 listUser·p0.90:   3.719 ms/op
                 listUser·p0.95:   3.994 ms/op
                 listUser·p0.99:   6.193 ms/op
                 listUser·p0.999:  14.664 ms/op
                 listUser·p0.9999: 18.612 ms/op
                 listUser·p1.00:   20.251 ms/op

Iteration   3: 3.753 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.236 ms/op
                 listUser·p0.50:   3.678 ms/op
                 listUser·p0.90:   4.162 ms/op
                 listUser·p0.95:   4.424 ms/op
                 listUser·p0.99:   6.791 ms/op
                 listUser·p0.999:  13.582 ms/op
                 listUser·p0.9999: 18.350 ms/op
                 listUser·p1.00:   18.416 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 261127
  mean =      3.675 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 62 
    [ 2.500,  5.000) = 254824 
    [ 5.000,  7.500) = 4883 
    [ 7.500, 10.000) = 747 
    [10.000, 12.500) = 164 
    [12.500, 15.000) = 294 
    [15.000, 17.500) = 73 
    [17.500, 20.000) = 78 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.477 ms/op
     p(50.0000) =      3.609 ms/op
     p(90.0000) =      3.969 ms/op
     p(95.0000) =      4.284 ms/op
     p(99.0000) =      6.562 ms/op
     p(99.9000) =     14.301 ms/op
     p(99.9900) =     18.576 ms/op
     p(99.9990) =     19.998 ms/op
     p(99.9999) =     20.251 ms/op
    p(100.0000) =     20.251 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  10.067 ± 8.798  ops/ms
ClientPb.existUser                       thrpt       3  10.631 ± 3.309  ops/ms
ClientPb.getUser                         thrpt       3  10.124 ± 3.768  ops/ms
ClientPb.listUser                        thrpt       3   8.746 ± 2.830  ops/ms
ClientPb.createUser                       avgt       3   3.164 ± 1.215   ms/op
ClientPb.existUser                        avgt       3   3.012 ± 1.337   ms/op
ClientPb.getUser                          avgt       3   3.116 ± 0.750   ms/op
ClientPb.listUser                         avgt       3   3.629 ± 0.661   ms/op
ClientPb.createUser                     sample  302182   3.177 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.212           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.076           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.551           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.944           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.005           ms/op
ClientPb.createUser:createUser·p0.999   sample          14.595           ms/op
ClientPb.createUser:createUser·p0.9999  sample          37.079           ms/op
ClientPb.createUser:createUser·p1.00    sample          45.482           ms/op
ClientPb.existUser                      sample  315449   3.041 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.235           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.990           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.269           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.531           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.079           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.221           ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.409           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.394           ms/op
ClientPb.getUser                        sample  297050   3.229 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.055           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.146           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.604           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.145           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.784           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.219           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.733           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.606           ms/op
ClientPb.listUser                       sample  261127   3.675 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.477           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.609           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.969           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.284           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.562           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.301           ms/op
ClientPb.listUser:listUser·p0.9999      sample          18.576           ms/op
ClientPb.listUser:listUser·p1.00        sample          20.251           ms/op
