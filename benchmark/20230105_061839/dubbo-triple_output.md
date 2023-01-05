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
# Warmup Iteration   1: 2.593 ops/ms
# Warmup Iteration   2: 6.001 ops/ms
# Warmup Iteration   3: 9.170 ops/ms
Iteration   1: 10.198 ops/ms
Iteration   2: 10.187 ops/ms
Iteration   3: 10.053 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  10.146 ±(99.9%) 1.475 ops/ms [Average]
  (min, avg, max) = (10.053, 10.146, 10.198), stdev = 0.081
  CI (99.9%): [8.671, 11.621] (assumes normal distribution)


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
# Warmup Iteration   1: 3.572 ops/ms
# Warmup Iteration   2: 9.165 ops/ms
# Warmup Iteration   3: 10.502 ops/ms
Iteration   1: 10.839 ops/ms
Iteration   2: 10.549 ops/ms
Iteration   3: 10.102 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.497 ±(99.9%) 6.768 ops/ms [Average]
  (min, avg, max) = (10.102, 10.497, 10.839), stdev = 0.371
  CI (99.9%): [3.729, 17.264] (assumes normal distribution)


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
# Warmup Iteration   1: 3.746 ops/ms
# Warmup Iteration   2: 9.472 ops/ms
# Warmup Iteration   3: 9.922 ops/ms
Iteration   1: 10.157 ops/ms
Iteration   2: 9.982 ops/ms
Iteration   3: 10.094 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.078 ±(99.9%) 1.619 ops/ms [Average]
  (min, avg, max) = (9.982, 10.078, 10.157), stdev = 0.089
  CI (99.9%): [8.459, 11.697] (assumes normal distribution)


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
# Warmup Iteration   1: 3.420 ops/ms
# Warmup Iteration   2: 8.128 ops/ms
# Warmup Iteration   3: 8.663 ops/ms
Iteration   1: 8.577 ops/ms
Iteration   2: 8.882 ops/ms
Iteration   3: 8.523 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.661 ±(99.9%) 3.533 ops/ms [Average]
  (min, avg, max) = (8.523, 8.661, 8.882), stdev = 0.194
  CI (99.9%): [5.128, 12.194] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 8.846 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.646 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.310 ±(99.9%) 0.005 ms/op
Iteration   1: 3.195 ±(99.9%) 0.002 ms/op
Iteration   2: 3.051 ±(99.9%) 0.007 ms/op
Iteration   3: 3.021 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.089 ±(99.9%) 1.694 ms/op [Average]
  (min, avg, max) = (3.021, 3.089, 3.195), stdev = 0.093
  CI (99.9%): [1.395, 4.783] (assumes normal distribution)


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
# Warmup Iteration   1: 7.249 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.413 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.244 ±(99.9%) 0.004 ms/op
Iteration   1: 3.028 ±(99.9%) 0.003 ms/op
Iteration   2: 3.015 ±(99.9%) 0.005 ms/op
Iteration   3: 3.108 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.050 ±(99.9%) 0.921 ms/op [Average]
  (min, avg, max) = (3.015, 3.050, 3.108), stdev = 0.050
  CI (99.9%): [2.130, 3.971] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 7.296 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.387 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.258 ±(99.9%) 0.002 ms/op
Iteration   1: 3.096 ±(99.9%) 0.003 ms/op
Iteration   2: 3.093 ±(99.9%) 0.006 ms/op
Iteration   3: 3.170 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.119 ±(99.9%) 0.797 ms/op [Average]
  (min, avg, max) = (3.093, 3.119, 3.170), stdev = 0.044
  CI (99.9%): [2.322, 3.917] (assumes normal distribution)


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
# Warmup Iteration   1: 9.011 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.986 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.922 ±(99.9%) 0.004 ms/op
Iteration   1: 3.838 ±(99.9%) 0.004 ms/op
Iteration   2: 3.793 ±(99.9%) 0.008 ms/op
Iteration   3: 3.683 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.771 ±(99.9%) 1.462 ms/op [Average]
  (min, avg, max) = (3.683, 3.771, 3.838), stdev = 0.080
  CI (99.9%): [2.309, 5.234] (assumes normal distribution)


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
# Warmup Iteration   1: 7.893 ±(99.9%) 0.092 ms/op
# Warmup Iteration   2: 3.513 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.202 ±(99.9%) 0.009 ms/op
Iteration   1: 3.259 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.577 ms/op
                 createUser·p0.50:   3.215 ms/op
                 createUser·p0.90:   3.704 ms/op
                 createUser·p0.95:   4.334 ms/op
                 createUser·p0.99:   5.407 ms/op
                 createUser·p0.999:  10.781 ms/op
                 createUser·p0.9999: 19.607 ms/op
                 createUser·p1.00:   20.316 ms/op

Iteration   2: 3.252 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.969 ms/op
                 createUser·p0.50:   3.105 ms/op
                 createUser·p0.90:   4.055 ms/op
                 createUser·p0.95:   4.383 ms/op
                 createUser·p0.99:   5.415 ms/op
                 createUser·p0.999:  11.424 ms/op
                 createUser·p0.9999: 24.019 ms/op
                 createUser·p1.00:   25.199 ms/op

Iteration   3: 3.222 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.204 ms/op
                 createUser·p0.50:   3.150 ms/op
                 createUser·p0.90:   3.817 ms/op
                 createUser·p0.95:   4.174 ms/op
                 createUser·p0.99:   5.333 ms/op
                 createUser·p0.999:  15.367 ms/op
                 createUser·p0.9999: 18.615 ms/op
                 createUser·p1.00:   22.970 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 295584
  mean =      3.244 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19856 
    [ 2.500,  5.000) = 268833 
    [ 5.000,  7.500) = 6107 
    [ 7.500, 10.000) = 416 
    [10.000, 12.500) = 51 
    [12.500, 15.000) = 5 
    [15.000, 17.500) = 82 
    [17.500, 20.000) = 150 
    [20.000, 22.500) = 49 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.969 ms/op
     p(50.0000) =      3.158 ms/op
     p(90.0000) =      3.871 ms/op
     p(95.0000) =      4.284 ms/op
     p(99.0000) =      5.399 ms/op
     p(99.9000) =     15.319 ms/op
     p(99.9900) =     23.167 ms/op
     p(99.9990) =     25.036 ms/op
     p(99.9999) =     25.199 ms/op
    p(100.0000) =     25.199 ms/op


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
# Warmup Iteration   1: 7.426 ±(99.9%) 0.086 ms/op
# Warmup Iteration   2: 3.211 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.182 ±(99.9%) 0.008 ms/op
Iteration   1: 2.949 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.973 ms/op
                 existUser·p0.50:   2.961 ms/op
                 existUser·p0.90:   3.072 ms/op
                 existUser·p0.95:   3.121 ms/op
                 existUser·p0.99:   4.268 ms/op
                 existUser·p0.999:  8.429 ms/op
                 existUser·p0.9999: 23.925 ms/op
                 existUser·p1.00:   24.609 ms/op

Iteration   2: 3.146 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.902 ms/op
                 existUser·p0.50:   2.957 ms/op
                 existUser·p0.90:   3.854 ms/op
                 existUser·p0.95:   4.276 ms/op
                 existUser·p0.99:   5.612 ms/op
                 existUser·p0.999:  10.797 ms/op
                 existUser·p0.9999: 21.378 ms/op
                 existUser·p1.00:   22.348 ms/op

Iteration   3: 2.998 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.032 ms/op
                 existUser·p0.50:   3.006 ms/op
                 existUser·p0.90:   3.170 ms/op
                 existUser·p0.95:   3.367 ms/op
                 existUser·p0.99:   5.054 ms/op
                 existUser·p0.999:  9.884 ms/op
                 existUser·p0.9999: 19.147 ms/op
                 existUser·p1.00:   19.628 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 316813
  mean =      3.029 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21184 
    [ 2.500,  5.000) = 290548 
    [ 5.000,  7.500) = 4489 
    [ 7.500, 10.000) = 284 
    [10.000, 12.500) = 19 
    [12.500, 15.000) = 51 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 117 
    [20.000, 22.500) = 63 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.902 ms/op
     p(50.0000) =      2.974 ms/op
     p(90.0000) =      3.240 ms/op
     p(95.0000) =      3.719 ms/op
     p(99.0000) =      5.210 ms/op
     p(99.9000) =      9.912 ms/op
     p(99.9900) =     22.358 ms/op
     p(99.9990) =     24.248 ms/op
     p(99.9999) =     24.609 ms/op
    p(100.0000) =     24.609 ms/op


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
# Warmup Iteration   1: 7.335 ±(99.9%) 0.103 ms/op
# Warmup Iteration   2: 3.323 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.205 ±(99.9%) 0.009 ms/op
Iteration   1: 3.285 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.106 ms/op
                 getUser·p0.50:   3.129 ms/op
                 getUser·p0.90:   3.723 ms/op
                 getUser·p0.95:   4.522 ms/op
                 getUser·p0.99:   6.537 ms/op
                 getUser·p0.999:  18.092 ms/op
                 getUser·p0.9999: 19.826 ms/op
                 getUser·p1.00:   21.004 ms/op

Iteration   2: 3.190 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.358 ms/op
                 getUser·p0.50:   3.133 ms/op
                 getUser·p0.90:   3.568 ms/op
                 getUser·p0.95:   3.830 ms/op
                 getUser·p0.99:   5.341 ms/op
                 getUser·p0.999:  19.595 ms/op
                 getUser·p0.9999: 25.262 ms/op
                 getUser·p1.00:   25.854 ms/op

Iteration   3: 3.252 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.872 ms/op
                 getUser·p0.50:   3.178 ms/op
                 getUser·p0.90:   3.666 ms/op
                 getUser·p0.95:   4.108 ms/op
                 getUser·p0.99:   6.082 ms/op
                 getUser·p0.999:  10.159 ms/op
                 getUser·p0.9999: 19.994 ms/op
                 getUser·p1.00:   20.546 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 296079
  mean =      3.242 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18407 
    [ 2.500,  5.000) = 269574 
    [ 5.000,  7.500) = 7001 
    [ 7.500, 10.000) = 681 
    [10.000, 12.500) = 83 
    [12.500, 15.000) = 51 
    [15.000, 17.500) = 36 
    [17.500, 20.000) = 139 
    [20.000, 22.500) = 52 
    [22.500, 25.000) = 44 
    [25.000, 27.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      1.106 ms/op
     p(50.0000) =      3.154 ms/op
     p(90.0000) =      3.637 ms/op
     p(95.0000) =      4.137 ms/op
     p(99.0000) =      6.062 ms/op
     p(99.9000) =     14.597 ms/op
     p(99.9900) =     24.065 ms/op
     p(99.9990) =     25.821 ms/op
     p(99.9999) =     25.854 ms/op
    p(100.0000) =     25.854 ms/op


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
# Warmup Iteration   1: 10.142 ±(99.9%) 0.129 ms/op
# Warmup Iteration   2: 4.213 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.750 ±(99.9%) 0.011 ms/op
Iteration   1: 3.888 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.800 ms/op
                 listUser·p0.50:   3.711 ms/op
                 listUser·p0.90:   4.260 ms/op
                 listUser·p0.95:   4.678 ms/op
                 listUser·p0.99:   7.545 ms/op
                 listUser·p0.999:  15.778 ms/op
                 listUser·p0.9999: 24.725 ms/op
                 listUser·p1.00:   25.854 ms/op

Iteration   2: 3.792 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.399 ms/op
                 listUser·p0.50:   3.674 ms/op
                 listUser·p0.90:   4.063 ms/op
                 listUser·p0.95:   4.432 ms/op
                 listUser·p0.99:   7.225 ms/op
                 listUser·p0.999:  15.745 ms/op
                 listUser·p0.9999: 19.032 ms/op
                 listUser·p1.00:   19.464 ms/op

Iteration   3: 3.599 ±(99.9%) 0.007 ms/op
                 listUser·p0.00:   2.212 ms/op
                 listUser·p0.50:   3.535 ms/op
                 listUser·p0.90:   3.813 ms/op
                 listUser·p0.95:   3.977 ms/op
                 listUser·p0.99:   5.366 ms/op
                 listUser·p0.999:  13.926 ms/op
                 listUser·p0.9999: 14.832 ms/op
                 listUser·p1.00:   15.172 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 255341
  mean =      3.756 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 61 
    [ 2.500,  5.000) = 247967 
    [ 5.000,  7.500) = 5362 
    [ 7.500, 10.000) = 1294 
    [10.000, 12.500) = 174 
    [12.500, 15.000) = 251 
    [15.000, 17.500) = 112 
    [17.500, 20.000) = 68 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      1.399 ms/op
     p(50.0000) =      3.637 ms/op
     p(90.0000) =      4.096 ms/op
     p(95.0000) =      4.342 ms/op
     p(99.0000) =      7.021 ms/op
     p(99.9000) =     14.713 ms/op
     p(99.9900) =     23.608 ms/op
     p(99.9990) =     25.541 ms/op
     p(99.9999) =     25.854 ms/op
    p(100.0000) =     25.854 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  10.146 ± 1.475  ops/ms
ClientPb.existUser                       thrpt       3  10.497 ± 6.768  ops/ms
ClientPb.getUser                         thrpt       3  10.078 ± 1.619  ops/ms
ClientPb.listUser                        thrpt       3   8.661 ± 3.533  ops/ms
ClientPb.createUser                       avgt       3   3.089 ± 1.694   ms/op
ClientPb.existUser                        avgt       3   3.050 ± 0.921   ms/op
ClientPb.getUser                          avgt       3   3.119 ± 0.797   ms/op
ClientPb.listUser                         avgt       3   3.771 ± 1.462   ms/op
ClientPb.createUser                     sample  295584   3.244 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.969           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.158           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.871           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.284           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.399           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.319           ms/op
ClientPb.createUser:createUser·p0.9999  sample          23.167           ms/op
ClientPb.createUser:createUser·p1.00    sample          25.199           ms/op
ClientPb.existUser                      sample  316813   3.029 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.902           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.974           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.240           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.719           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.210           ms/op
ClientPb.existUser:existUser·p0.999     sample           9.912           ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.358           ms/op
ClientPb.existUser:existUser·p1.00      sample          24.609           ms/op
ClientPb.getUser                        sample  296079   3.242 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.106           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.154           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.637           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.137           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.062           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.597           ms/op
ClientPb.getUser:getUser·p0.9999        sample          24.065           ms/op
ClientPb.getUser:getUser·p1.00          sample          25.854           ms/op
ClientPb.listUser                       sample  255341   3.756 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.399           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.637           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.096           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.342           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.021           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.713           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.608           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.854           ms/op
