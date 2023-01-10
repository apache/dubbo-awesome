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
# Warmup Iteration   1: 2.477 ops/ms
# Warmup Iteration   2: 6.380 ops/ms
# Warmup Iteration   3: 9.353 ops/ms
Iteration   1: 9.944 ops/ms
Iteration   2: 9.500 ops/ms
Iteration   3: 9.838 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.761 ±(99.9%) 4.226 ops/ms [Average]
  (min, avg, max) = (9.500, 9.761, 9.944), stdev = 0.232
  CI (99.9%): [5.534, 13.987] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 3.476 ops/ms
# Warmup Iteration   2: 9.518 ops/ms
# Warmup Iteration   3: 10.006 ops/ms
Iteration   1: 10.505 ops/ms
Iteration   2: 10.638 ops/ms
Iteration   3: 9.863 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.335 ±(99.9%) 7.561 ops/ms [Average]
  (min, avg, max) = (9.863, 10.335, 10.638), stdev = 0.414
  CI (99.9%): [2.775, 17.896] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.284 ops/ms
# Warmup Iteration   2: 9.213 ops/ms
# Warmup Iteration   3: 9.127 ops/ms
Iteration   1: 10.094 ops/ms
Iteration   2: 10.102 ops/ms
Iteration   3: 9.859 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.018 ±(99.9%) 2.510 ops/ms [Average]
  (min, avg, max) = (9.859, 10.018, 10.102), stdev = 0.138
  CI (99.9%): [7.509, 12.528] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.080 ops/ms
# Warmup Iteration   2: 7.532 ops/ms
# Warmup Iteration   3: 8.412 ops/ms
Iteration   1: 8.325 ops/ms
Iteration   2: 8.358 ops/ms
Iteration   3: 8.576 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.419 ±(99.9%) 2.488 ops/ms [Average]
  (min, avg, max) = (8.325, 8.419, 8.576), stdev = 0.136
  CI (99.9%): [5.932, 10.907] (assumes normal distribution)


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
# Warmup Iteration   1: 7.919 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.562 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.310 ±(99.9%) 0.003 ms/op
Iteration   1: 3.174 ±(99.9%) 0.004 ms/op
Iteration   2: 3.062 ±(99.9%) 0.004 ms/op
Iteration   3: 3.255 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.164 ±(99.9%) 1.770 ms/op [Average]
  (min, avg, max) = (3.062, 3.164, 3.255), stdev = 0.097
  CI (99.9%): [1.393, 4.934] (assumes normal distribution)


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
# Warmup Iteration   1: 6.789 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.247 ±(99.9%) 0.001 ms/op
# Warmup Iteration   3: 3.144 ±(99.9%) 0.005 ms/op
Iteration   1: 3.078 ±(99.9%) 0.005 ms/op
Iteration   2: 3.026 ±(99.9%) 0.003 ms/op
Iteration   3: 3.049 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.051 ±(99.9%) 0.481 ms/op [Average]
  (min, avg, max) = (3.026, 3.051, 3.078), stdev = 0.026
  CI (99.9%): [2.570, 3.532] (assumes normal distribution)


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
# Warmup Iteration   1: 8.228 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.372 ±(99.9%) 0.001 ms/op
# Warmup Iteration   3: 3.459 ±(99.9%) 0.005 ms/op
Iteration   1: 3.149 ±(99.9%) 0.004 ms/op
Iteration   2: 3.129 ±(99.9%) 0.009 ms/op
Iteration   3: 3.283 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.187 ±(99.9%) 1.521 ms/op [Average]
  (min, avg, max) = (3.129, 3.187, 3.283), stdev = 0.083
  CI (99.9%): [1.666, 4.708] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 8.579 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.045 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.779 ±(99.9%) 0.006 ms/op
Iteration   1: 3.637 ±(99.9%) 0.007 ms/op
Iteration   2: 3.723 ±(99.9%) 0.009 ms/op
Iteration   3: 3.707 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.689 ±(99.9%) 0.831 ms/op [Average]
  (min, avg, max) = (3.637, 3.689, 3.723), stdev = 0.046
  CI (99.9%): [2.858, 4.521] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 9.521 ±(99.9%) 0.112 ms/op
# Warmup Iteration   2: 3.765 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.124 ±(99.9%) 0.008 ms/op
Iteration   1: 3.285 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.149 ms/op
                 createUser·p0.50:   3.219 ms/op
                 createUser·p0.90:   3.858 ms/op
                 createUser·p0.95:   4.202 ms/op
                 createUser·p0.99:   5.497 ms/op
                 createUser·p0.999:  9.781 ms/op
                 createUser·p0.9999: 24.060 ms/op
                 createUser·p1.00:   25.559 ms/op

Iteration   2: 3.122 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.143 ms/op
                 createUser·p0.50:   3.027 ms/op
                 createUser·p0.90:   3.363 ms/op
                 createUser·p0.95:   3.621 ms/op
                 createUser·p0.99:   6.193 ms/op
                 createUser·p0.999:  19.684 ms/op
                 createUser·p0.9999: 21.350 ms/op
                 createUser·p1.00:   25.788 ms/op

Iteration   3: 3.080 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.329 ms/op
                 createUser·p0.50:   2.994 ms/op
                 createUser·p0.90:   3.301 ms/op
                 createUser·p0.95:   3.568 ms/op
                 createUser·p0.99:   5.304 ms/op
                 createUser·p0.999:  14.352 ms/op
                 createUser·p0.9999: 16.961 ms/op
                 createUser·p1.00:   17.334 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 303749
  mean =      3.160 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19913 
    [ 2.500,  5.000) = 277919 
    [ 5.000,  7.500) = 5120 
    [ 7.500, 10.000) = 346 
    [10.000, 12.500) = 34 
    [12.500, 15.000) = 118 
    [15.000, 17.500) = 52 
    [17.500, 20.000) = 122 
    [20.000, 22.500) = 99 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.143 ms/op
     p(50.0000) =      3.080 ms/op
     p(90.0000) =      3.461 ms/op
     p(95.0000) =      3.883 ms/op
     p(99.0000) =      5.603 ms/op
     p(99.9000) =     14.901 ms/op
     p(99.9900) =     22.217 ms/op
     p(99.9990) =     25.251 ms/op
     p(99.9999) =     25.788 ms/op
    p(100.0000) =     25.788 ms/op


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
# Warmup Iteration   1: 7.079 ±(99.9%) 0.086 ms/op
# Warmup Iteration   2: 3.418 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.019 ±(99.9%) 0.007 ms/op
Iteration   1: 3.085 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.296 ms/op
                 existUser·p0.50:   3.052 ms/op
                 existUser·p0.90:   3.355 ms/op
                 existUser·p0.95:   3.629 ms/op
                 existUser·p0.99:   5.226 ms/op
                 existUser·p0.999:  8.612 ms/op
                 existUser·p0.9999: 19.235 ms/op
                 existUser·p1.00:   20.480 ms/op

Iteration   2: 3.206 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.395 ms/op
                 existUser·p0.50:   3.150 ms/op
                 existUser·p0.90:   3.576 ms/op
                 existUser·p0.95:   3.965 ms/op
                 existUser·p0.99:   5.652 ms/op
                 existUser·p0.999:  9.273 ms/op
                 existUser·p0.9999: 21.726 ms/op
                 existUser·p1.00:   22.839 ms/op

Iteration   3: 3.150 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.370 ms/op
                 existUser·p0.50:   3.080 ms/op
                 existUser·p0.90:   3.584 ms/op
                 existUser·p0.95:   3.940 ms/op
                 existUser·p0.99:   5.841 ms/op
                 existUser·p0.999:  13.566 ms/op
                 existUser·p0.9999: 19.989 ms/op
                 existUser·p1.00:   21.004 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 305080
  mean =      3.146 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25806 
    [ 2.500,  5.000) = 273490 
    [ 5.000,  7.500) = 5223 
    [ 7.500, 10.000) = 209 
    [10.000, 12.500) = 17 
    [12.500, 15.000) = 81 
    [15.000, 17.500) = 41 
    [17.500, 20.000) = 124 
    [20.000, 22.500) = 87 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.296 ms/op
     p(50.0000) =      3.101 ms/op
     p(90.0000) =      3.494 ms/op
     p(95.0000) =      3.871 ms/op
     p(99.0000) =      5.718 ms/op
     p(99.9000) =     13.418 ms/op
     p(99.9900) =     21.250 ms/op
     p(99.9990) =     22.086 ms/op
     p(99.9999) =     22.839 ms/op
    p(100.0000) =     22.839 ms/op


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
# Warmup Iteration   1: 8.051 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 3.387 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.273 ±(99.9%) 0.010 ms/op
Iteration   1: 3.140 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.079 ms/op
                 getUser·p0.50:   3.027 ms/op
                 getUser·p0.90:   3.396 ms/op
                 getUser·p0.95:   3.674 ms/op
                 getUser·p0.99:   5.702 ms/op
                 getUser·p0.999:  14.844 ms/op
                 getUser·p0.9999: 20.998 ms/op
                 getUser·p1.00:   22.118 ms/op

Iteration   2: 3.225 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.912 ms/op
                 getUser·p0.50:   3.199 ms/op
                 getUser·p0.90:   3.719 ms/op
                 getUser·p0.95:   3.994 ms/op
                 getUser·p0.99:   5.267 ms/op
                 getUser·p0.999:  8.437 ms/op
                 getUser·p0.9999: 24.029 ms/op
                 getUser·p1.00:   25.494 ms/op

Iteration   3: 3.117 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.358 ms/op
                 getUser·p0.50:   2.994 ms/op
                 getUser·p0.90:   3.412 ms/op
                 getUser·p0.95:   3.748 ms/op
                 getUser·p0.99:   5.669 ms/op
                 getUser·p0.999:  9.073 ms/op
                 getUser·p0.9999: 18.636 ms/op
                 getUser·p1.00:   19.661 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 303828
  mean =      3.160 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17896 
    [ 2.500,  5.000) = 279140 
    [ 5.000,  7.500) = 5829 
    [ 7.500, 10.000) = 587 
    [10.000, 12.500) = 43 
    [12.500, 15.000) = 42 
    [15.000, 17.500) = 63 
    [17.500, 20.000) = 161 
    [20.000, 22.500) = 45 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.912 ms/op
     p(50.0000) =      3.080 ms/op
     p(90.0000) =      3.539 ms/op
     p(95.0000) =      3.871 ms/op
     p(99.0000) =      5.530 ms/op
     p(99.9000) =     14.729 ms/op
     p(99.9900) =     21.741 ms/op
     p(99.9990) =     24.703 ms/op
     p(99.9999) =     25.494 ms/op
    p(100.0000) =     25.494 ms/op


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
# Warmup Iteration   1: 8.619 ±(99.9%) 0.110 ms/op
# Warmup Iteration   2: 3.999 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.849 ±(99.9%) 0.012 ms/op
Iteration   1: 3.667 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.489 ms/op
                 listUser·p0.50:   3.555 ms/op
                 listUser·p0.90:   3.990 ms/op
                 listUser·p0.95:   4.178 ms/op
                 listUser·p0.99:   6.423 ms/op
                 listUser·p0.999:  15.306 ms/op
                 listUser·p0.9999: 20.161 ms/op
                 listUser·p1.00:   21.660 ms/op

Iteration   2: 3.878 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.655 ms/op
                 listUser·p0.50:   3.736 ms/op
                 listUser·p0.90:   4.342 ms/op
                 listUser·p0.95:   4.735 ms/op
                 listUser·p0.99:   7.463 ms/op
                 listUser·p0.999:  13.132 ms/op
                 listUser·p0.9999: 19.246 ms/op
                 listUser·p1.00:   20.185 ms/op

Iteration   3: 3.774 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.261 ms/op
                 listUser·p0.50:   3.699 ms/op
                 listUser·p0.90:   4.108 ms/op
                 listUser·p0.95:   4.350 ms/op
                 listUser·p0.99:   7.013 ms/op
                 listUser·p0.999:  13.401 ms/op
                 listUser·p0.9999: 19.792 ms/op
                 listUser·p1.00:   20.578 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 254343
  mean =      3.771 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 67 
    [ 2.500,  5.000) = 247093 
    [ 5.000,  7.500) = 5131 
    [ 7.500, 10.000) = 1375 
    [10.000, 12.500) = 234 
    [12.500, 15.000) = 241 
    [15.000, 17.500) = 76 
    [17.500, 20.000) = 111 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.489 ms/op
     p(50.0000) =      3.686 ms/op
     p(90.0000) =      4.137 ms/op
     p(95.0000) =      4.432 ms/op
     p(99.0000) =      7.029 ms/op
     p(99.9000) =     13.954 ms/op
     p(99.9900) =     19.792 ms/op
     p(99.9990) =     20.835 ms/op
     p(99.9999) =     21.660 ms/op
    p(100.0000) =     21.660 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.761 ± 4.226  ops/ms
ClientPb.existUser                       thrpt       3  10.335 ± 7.561  ops/ms
ClientPb.getUser                         thrpt       3  10.018 ± 2.510  ops/ms
ClientPb.listUser                        thrpt       3   8.419 ± 2.488  ops/ms
ClientPb.createUser                       avgt       3   3.164 ± 1.770   ms/op
ClientPb.existUser                        avgt       3   3.051 ± 0.481   ms/op
ClientPb.getUser                          avgt       3   3.187 ± 1.521   ms/op
ClientPb.listUser                         avgt       3   3.689 ± 0.831   ms/op
ClientPb.createUser                     sample  303749   3.160 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.143           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.080           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.461           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.883           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.603           ms/op
ClientPb.createUser:createUser·p0.999   sample          14.901           ms/op
ClientPb.createUser:createUser·p0.9999  sample          22.217           ms/op
ClientPb.createUser:createUser·p1.00    sample          25.788           ms/op
ClientPb.existUser                      sample  305080   3.146 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.296           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.101           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.494           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.871           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.718           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.418           ms/op
ClientPb.existUser:existUser·p0.9999    sample          21.250           ms/op
ClientPb.existUser:existUser·p1.00      sample          22.839           ms/op
ClientPb.getUser                        sample  303828   3.160 ± 0.004   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.912           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.080           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.539           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.871           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.530           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.729           ms/op
ClientPb.getUser:getUser·p0.9999        sample          21.741           ms/op
ClientPb.getUser:getUser·p1.00          sample          25.494           ms/op
ClientPb.listUser                       sample  254343   3.771 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.489           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.686           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.137           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.432           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.029           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.954           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.792           ms/op
ClientPb.listUser:listUser·p1.00        sample          21.660           ms/op
