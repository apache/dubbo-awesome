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
# Warmup Iteration   1: 2.125 ops/ms
# Warmup Iteration   2: 5.318 ops/ms
# Warmup Iteration   3: 8.606 ops/ms
Iteration   1: 9.076 ops/ms
Iteration   2: 9.160 ops/ms
Iteration   3: 9.085 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.107 ±(99.9%) 0.839 ops/ms [Average]
  (min, avg, max) = (9.076, 9.107, 9.160), stdev = 0.046
  CI (99.9%): [8.268, 9.946] (assumes normal distribution)


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
# Warmup Iteration   1: 2.811 ops/ms
# Warmup Iteration   2: 8.535 ops/ms
# Warmup Iteration   3: 9.090 ops/ms
Iteration   1: 9.488 ops/ms
Iteration   2: 9.261 ops/ms
Iteration   3: 9.680 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.476 ±(99.9%) 3.825 ops/ms [Average]
  (min, avg, max) = (9.261, 9.476, 9.680), stdev = 0.210
  CI (99.9%): [5.651, 13.301] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 2.978 ops/ms
# Warmup Iteration   2: 7.861 ops/ms
# Warmup Iteration   3: 8.771 ops/ms
Iteration   1: 9.099 ops/ms
Iteration   2: 9.051 ops/ms
Iteration   3: 9.007 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.052 ±(99.9%) 0.842 ops/ms [Average]
  (min, avg, max) = (9.007, 9.052, 9.099), stdev = 0.046
  CI (99.9%): [8.210, 9.895] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 2.598 ops/ms
# Warmup Iteration   2: 6.932 ops/ms
# Warmup Iteration   3: 7.496 ops/ms
Iteration   1: 7.856 ops/ms
Iteration   2: 7.852 ops/ms
Iteration   3: 7.783 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.830 ±(99.9%) 0.750 ops/ms [Average]
  (min, avg, max) = (7.783, 7.830, 7.856), stdev = 0.041
  CI (99.9%): [7.081, 8.580] (assumes normal distribution)


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
# Warmup Iteration   1: 9.870 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.853 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.604 ±(99.9%) 0.007 ms/op
Iteration   1: 3.499 ±(99.9%) 0.011 ms/op
Iteration   2: 3.597 ±(99.9%) 0.007 ms/op
Iteration   3: 3.612 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.570 ±(99.9%) 1.123 ms/op [Average]
  (min, avg, max) = (3.499, 3.570, 3.612), stdev = 0.062
  CI (99.9%): [2.446, 4.693] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 8.878 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.718 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.433 ±(99.9%) 0.007 ms/op
Iteration   1: 3.437 ±(99.9%) 0.010 ms/op
Iteration   2: 3.258 ±(99.9%) 0.009 ms/op
Iteration   3: 3.293 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.329 ±(99.9%) 1.734 ms/op [Average]
  (min, avg, max) = (3.258, 3.329, 3.437), stdev = 0.095
  CI (99.9%): [1.595, 5.063] (assumes normal distribution)


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
# Warmup Iteration   1: 9.940 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.794 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.636 ±(99.9%) 0.007 ms/op
Iteration   1: 3.467 ±(99.9%) 0.008 ms/op
Iteration   2: 3.637 ±(99.9%) 0.004 ms/op
Iteration   3: 3.345 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.483 ±(99.9%) 2.675 ms/op [Average]
  (min, avg, max) = (3.345, 3.483, 3.637), stdev = 0.147
  CI (99.9%): [0.808, 6.158] (assumes normal distribution)


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
# Warmup Iteration   1: 10.818 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 4.480 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.243 ±(99.9%) 0.006 ms/op
Iteration   1: 4.155 ±(99.9%) 0.009 ms/op
Iteration   2: 4.161 ±(99.9%) 0.011 ms/op
Iteration   3: 4.102 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.140 ±(99.9%) 0.595 ms/op [Average]
  (min, avg, max) = (4.102, 4.140, 4.161), stdev = 0.033
  CI (99.9%): [3.545, 4.734] (assumes normal distribution)


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
# Warmup Iteration   1: 9.560 ±(99.9%) 0.132 ms/op
# Warmup Iteration   2: 4.086 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 3.569 ±(99.9%) 0.012 ms/op
Iteration   1: 3.485 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.245 ms/op
                 createUser·p0.50:   3.305 ms/op
                 createUser·p0.90:   3.977 ms/op
                 createUser·p0.95:   4.432 ms/op
                 createUser·p0.99:   7.200 ms/op
                 createUser·p0.999:  22.590 ms/op
                 createUser·p0.9999: 27.558 ms/op
                 createUser·p1.00:   28.180 ms/op

Iteration   2: 3.411 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.389 ms/op
                 createUser·p0.50:   3.301 ms/op
                 createUser·p0.90:   3.777 ms/op
                 createUser·p0.95:   4.186 ms/op
                 createUser·p0.99:   6.111 ms/op
                 createUser·p0.999:  23.462 ms/op
                 createUser·p0.9999: 26.956 ms/op
                 createUser·p1.00:   27.427 ms/op

Iteration   3: 3.391 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.614 ms/op
                 createUser·p0.50:   3.252 ms/op
                 createUser·p0.90:   3.809 ms/op
                 createUser·p0.95:   4.123 ms/op
                 createUser·p0.99:   5.595 ms/op
                 createUser·p0.999:  21.987 ms/op
                 createUser·p0.9999: 30.704 ms/op
                 createUser·p1.00:   32.342 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 279671
  mean =      3.429 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7354 
    [ 2.500,  5.000) = 265037 
    [ 5.000,  7.500) = 5837 
    [ 7.500, 10.000) = 797 
    [10.000, 12.500) = 237 
    [12.500, 15.000) = 100 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 113 
    [25.000, 27.500) = 108 
    [27.500, 30.000) = 37 
    [30.000, 32.500) = 21 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.389 ms/op
     p(50.0000) =      3.285 ms/op
     p(90.0000) =      3.854 ms/op
     p(95.0000) =      4.252 ms/op
     p(99.0000) =      6.275 ms/op
     p(99.9000) =     22.490 ms/op
     p(99.9900) =     29.463 ms/op
     p(99.9990) =     31.124 ms/op
     p(99.9999) =     32.342 ms/op
    p(100.0000) =     32.342 ms/op


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
# Warmup Iteration   1: 10.306 ±(99.9%) 0.131 ms/op
# Warmup Iteration   2: 3.768 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.519 ±(99.9%) 0.010 ms/op
Iteration   1: 3.307 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.460 ms/op
                 existUser·p0.50:   3.215 ms/op
                 existUser·p0.90:   3.613 ms/op
                 existUser·p0.95:   3.875 ms/op
                 existUser·p0.99:   5.712 ms/op
                 existUser·p0.999:  16.266 ms/op
                 existUser·p0.9999: 28.410 ms/op
                 existUser·p1.00:   29.557 ms/op

Iteration   2: 3.306 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.878 ms/op
                 existUser·p0.50:   3.334 ms/op
                 existUser·p0.90:   3.449 ms/op
                 existUser·p0.95:   3.543 ms/op
                 existUser·p0.99:   5.317 ms/op
                 existUser·p0.999:  9.470 ms/op
                 existUser·p0.9999: 26.561 ms/op
                 existUser·p1.00:   27.427 ms/op

Iteration   3: 3.413 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.716 ms/op
                 existUser·p0.50:   3.363 ms/op
                 existUser·p0.90:   3.752 ms/op
                 existUser·p0.95:   4.176 ms/op
                 existUser·p0.99:   6.095 ms/op
                 existUser·p0.999:  23.839 ms/op
                 existUser·p0.9999: 33.243 ms/op
                 existUser·p1.00:   33.882 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 287280
  mean =      3.341 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18105 
    [ 2.500,  5.000) = 263939 
    [ 5.000,  7.500) = 4323 
    [ 7.500, 10.000) = 540 
    [10.000, 12.500) = 107 
    [12.500, 15.000) = 10 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 74 
    [25.000, 27.500) = 101 
    [27.500, 30.000) = 49 
    [30.000, 32.500) = 17 
    [32.500, 35.000) = 15 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.460 ms/op
     p(50.0000) =      3.318 ms/op
     p(90.0000) =      3.559 ms/op
     p(95.0000) =      3.912 ms/op
     p(99.0000) =      5.661 ms/op
     p(99.9000) =     11.731 ms/op
     p(99.9900) =     31.687 ms/op
     p(99.9990) =     33.751 ms/op
     p(99.9999) =     33.882 ms/op
    p(100.0000) =     33.882 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 10.279 ±(99.9%) 0.123 ms/op
# Warmup Iteration   2: 4.059 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.591 ±(99.9%) 0.011 ms/op
Iteration   1: 3.663 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.169 ms/op
                 getUser·p0.50:   3.420 ms/op
                 getUser·p0.90:   4.530 ms/op
                 getUser·p0.95:   5.464 ms/op
                 getUser·p0.99:   7.504 ms/op
                 getUser·p0.999:  23.335 ms/op
                 getUser·p0.9999: 27.191 ms/op
                 getUser·p1.00:   28.606 ms/op

Iteration   2: 3.449 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.606 ms/op
                 getUser·p0.50:   3.359 ms/op
                 getUser·p0.90:   3.781 ms/op
                 getUser·p0.95:   4.006 ms/op
                 getUser·p0.99:   5.718 ms/op
                 getUser·p0.999:  25.965 ms/op
                 getUser·p0.9999: 35.044 ms/op
                 getUser·p1.00:   36.176 ms/op

Iteration   3: 3.591 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.245 ms/op
                 getUser·p0.50:   3.408 ms/op
                 getUser·p0.90:   4.137 ms/op
                 getUser·p0.95:   4.448 ms/op
                 getUser·p0.99:   6.889 ms/op
                 getUser·p0.999:  26.083 ms/op
                 getUser·p0.9999: 33.699 ms/op
                 getUser·p1.00:   34.603 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 269017
  mean =      3.565 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2657 
    [ 2.500,  5.000) = 254783 
    [ 5.000,  7.500) = 9774 
    [ 7.500, 10.000) = 1277 
    [10.000, 12.500) = 188 
    [12.500, 15.000) = 22 
    [15.000, 17.500) = 9 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 40 
    [25.000, 27.500) = 101 
    [27.500, 30.000) = 70 
    [30.000, 32.500) = 17 
    [32.500, 35.000) = 48 
    [35.000, 37.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      1.169 ms/op
     p(50.0000) =      3.391 ms/op
     p(90.0000) =      4.035 ms/op
     p(95.0000) =      4.727 ms/op
     p(99.0000) =      7.004 ms/op
     p(99.9000) =     24.017 ms/op
     p(99.9900) =     34.341 ms/op
     p(99.9990) =     35.950 ms/op
     p(99.9999) =     36.176 ms/op
    p(100.0000) =     36.176 ms/op


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
# Warmup Iteration   1: 10.483 ±(99.9%) 0.153 ms/op
# Warmup Iteration   2: 4.711 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.214 ±(99.9%) 0.015 ms/op
Iteration   1: 4.120 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.391 ms/op
                 listUser·p0.50:   3.957 ms/op
                 listUser·p0.90:   4.481 ms/op
                 listUser·p0.95:   4.727 ms/op
                 listUser·p0.99:   7.225 ms/op
                 listUser·p0.999:  23.433 ms/op
                 listUser·p0.9999: 31.858 ms/op
                 listUser·p1.00:   32.735 ms/op

Iteration   2: 4.008 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.474 ms/op
                 listUser·p0.50:   3.887 ms/op
                 listUser·p0.90:   4.317 ms/op
                 listUser·p0.95:   4.514 ms/op
                 listUser·p0.99:   6.259 ms/op
                 listUser·p0.999:  17.924 ms/op
                 listUser·p0.9999: 21.038 ms/op
                 listUser·p1.00:   21.430 ms/op

Iteration   3: 4.022 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.917 ms/op
                 listUser·p0.50:   3.875 ms/op
                 listUser·p0.90:   4.440 ms/op
                 listUser·p0.95:   4.686 ms/op
                 listUser·p0.99:   7.307 ms/op
                 listUser·p0.999:  16.310 ms/op
                 listUser·p0.9999: 20.972 ms/op
                 listUser·p1.00:   21.594 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 236859
  mean =      4.049 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 35 
    [ 2.500,  5.000) = 229974 
    [ 5.000,  7.500) = 4893 
    [ 7.500, 10.000) = 1052 
    [10.000, 12.500) = 347 
    [12.500, 15.000) = 89 
    [15.000, 17.500) = 205 
    [17.500, 20.000) = 102 
    [20.000, 22.500) = 74 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 1 
    [27.500, 30.000) = 31 
    [30.000, 32.500) = 31 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.391 ms/op
     p(50.0000) =      3.903 ms/op
     p(90.0000) =      4.415 ms/op
     p(95.0000) =      4.645 ms/op
     p(99.0000) =      7.184 ms/op
     p(99.9000) =     17.924 ms/op
     p(99.9900) =     30.769 ms/op
     p(99.9990) =     32.088 ms/op
     p(99.9999) =     32.735 ms/op
    p(100.0000) =     32.735 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.107 ± 0.839  ops/ms
ClientPb.existUser                       thrpt       3   9.476 ± 3.825  ops/ms
ClientPb.getUser                         thrpt       3   9.052 ± 0.842  ops/ms
ClientPb.listUser                        thrpt       3   7.830 ± 0.750  ops/ms
ClientPb.createUser                       avgt       3   3.570 ± 1.123   ms/op
ClientPb.existUser                        avgt       3   3.329 ± 1.734   ms/op
ClientPb.getUser                          avgt       3   3.483 ± 2.675   ms/op
ClientPb.listUser                         avgt       3   4.140 ± 0.595   ms/op
ClientPb.createUser                     sample  279671   3.429 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.389           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.285           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.854           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.252           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.275           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.490           ms/op
ClientPb.createUser:createUser·p0.9999  sample          29.463           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.342           ms/op
ClientPb.existUser                      sample  287280   3.341 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.460           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.318           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.559           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.912           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.661           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.731           ms/op
ClientPb.existUser:existUser·p0.9999    sample          31.687           ms/op
ClientPb.existUser:existUser·p1.00      sample          33.882           ms/op
ClientPb.getUser                        sample  269017   3.565 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.169           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.391           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.035           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.727           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.004           ms/op
ClientPb.getUser:getUser·p0.999         sample          24.017           ms/op
ClientPb.getUser:getUser·p0.9999        sample          34.341           ms/op
ClientPb.getUser:getUser·p1.00          sample          36.176           ms/op
ClientPb.listUser                       sample  236859   4.049 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.391           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.903           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.415           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.645           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.184           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.924           ms/op
ClientPb.listUser:listUser·p0.9999      sample          30.769           ms/op
ClientPb.listUser:listUser·p1.00        sample          32.735           ms/op
