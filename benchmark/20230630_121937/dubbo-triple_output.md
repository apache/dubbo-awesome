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
# Warmup Iteration   1: 1.707 ops/ms
# Warmup Iteration   2: 4.890 ops/ms
# Warmup Iteration   3: 8.675 ops/ms
Iteration   1: 9.373 ops/ms
Iteration   2: 9.566 ops/ms
Iteration   3: 9.680 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.540 ±(99.9%) 2.829 ops/ms [Average]
  (min, avg, max) = (9.373, 9.540, 9.680), stdev = 0.155
  CI (99.9%): [6.711, 12.368] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.352 ops/ms
# Warmup Iteration   2: 9.249 ops/ms
# Warmup Iteration   3: 9.584 ops/ms
Iteration   1: 9.819 ops/ms
Iteration   2: 9.688 ops/ms
Iteration   3: 9.041 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.516 ±(99.9%) 7.599 ops/ms [Average]
  (min, avg, max) = (9.041, 9.516, 9.819), stdev = 0.417
  CI (99.9%): [1.917, 17.115] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.206 ops/ms
# Warmup Iteration   2: 8.741 ops/ms
# Warmup Iteration   3: 9.380 ops/ms
Iteration   1: 9.702 ops/ms
Iteration   2: 9.790 ops/ms
Iteration   3: 9.352 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.615 ±(99.9%) 4.223 ops/ms [Average]
  (min, avg, max) = (9.352, 9.615, 9.790), stdev = 0.231
  CI (99.9%): [5.392, 13.838] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 2.630 ops/ms
# Warmup Iteration   2: 6.543 ops/ms
# Warmup Iteration   3: 7.865 ops/ms
Iteration   1: 8.174 ops/ms
Iteration   2: 8.300 ops/ms
Iteration   3: 8.140 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.205 ±(99.9%) 1.543 ops/ms [Average]
  (min, avg, max) = (8.140, 8.205, 8.300), stdev = 0.085
  CI (99.9%): [6.662, 9.747] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 10.190 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.842 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.683 ±(99.9%) 0.008 ms/op
Iteration   1: 3.347 ±(99.9%) 0.010 ms/op
Iteration   2: 3.482 ±(99.9%) 0.007 ms/op
Iteration   3: 3.560 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.463 ±(99.9%) 1.964 ms/op [Average]
  (min, avg, max) = (3.347, 3.463, 3.560), stdev = 0.108
  CI (99.9%): [1.499, 5.428] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 9.437 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.587 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.355 ±(99.9%) 0.008 ms/op
Iteration   1: 3.278 ±(99.9%) 0.007 ms/op
Iteration   2: 3.277 ±(99.9%) 0.007 ms/op
Iteration   3: 3.257 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.270 ±(99.9%) 0.217 ms/op [Average]
  (min, avg, max) = (3.257, 3.270, 3.278), stdev = 0.012
  CI (99.9%): [3.053, 3.488] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 9.376 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.774 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.465 ±(99.9%) 0.005 ms/op
Iteration   1: 3.391 ±(99.9%) 0.005 ms/op
Iteration   2: 3.335 ±(99.9%) 0.008 ms/op
Iteration   3: 3.277 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.335 ±(99.9%) 1.041 ms/op [Average]
  (min, avg, max) = (3.277, 3.335, 3.391), stdev = 0.057
  CI (99.9%): [2.294, 4.375] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 10.116 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 4.356 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.026 ±(99.9%) 0.008 ms/op
Iteration   1: 4.076 ±(99.9%) 0.007 ms/op
Iteration   2: 4.014 ±(99.9%) 0.009 ms/op
Iteration   3: 3.873 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.988 ±(99.9%) 1.901 ms/op [Average]
  (min, avg, max) = (3.873, 3.988, 4.076), stdev = 0.104
  CI (99.9%): [2.087, 5.889] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 9.001 ±(99.9%) 0.138 ms/op
# Warmup Iteration   2: 3.986 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.526 ±(99.9%) 0.012 ms/op
Iteration   1: 3.283 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.051 ms/op
                 createUser·p0.50:   3.178 ms/op
                 createUser·p0.90:   3.826 ms/op
                 createUser·p0.95:   4.514 ms/op
                 createUser·p0.99:   5.841 ms/op
                 createUser·p0.999:  13.081 ms/op
                 createUser·p0.9999: 23.873 ms/op
                 createUser·p1.00:   24.576 ms/op

Iteration   2: 3.403 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.307 ms/op
                 createUser·p0.50:   3.338 ms/op
                 createUser·p0.90:   3.903 ms/op
                 createUser·p0.95:   4.211 ms/op
                 createUser·p0.99:   5.726 ms/op
                 createUser·p0.999:  21.131 ms/op
                 createUser·p0.9999: 30.350 ms/op
                 createUser·p1.00:   31.392 ms/op

Iteration   3: 3.425 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.067 ms/op
                 createUser·p0.50:   3.334 ms/op
                 createUser·p0.90:   3.944 ms/op
                 createUser·p0.95:   4.325 ms/op
                 createUser·p0.99:   5.857 ms/op
                 createUser·p0.999:  19.493 ms/op
                 createUser·p0.9999: 31.949 ms/op
                 createUser·p1.00:   32.801 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 284387
  mean =      3.369 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9974 
    [ 2.500,  5.000) = 267877 
    [ 5.000,  7.500) = 5675 
    [ 7.500, 10.000) = 383 
    [10.000, 12.500) = 129 
    [12.500, 15.000) = 7 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 46 
    [20.000, 22.500) = 85 
    [22.500, 25.000) = 89 
    [25.000, 27.500) = 41 
    [27.500, 30.000) = 24 
    [30.000, 32.500) = 35 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.051 ms/op
     p(50.0000) =      3.285 ms/op
     p(90.0000) =      3.899 ms/op
     p(95.0000) =      4.334 ms/op
     p(99.0000) =      5.800 ms/op
     p(99.9000) =     19.497 ms/op
     p(99.9900) =     30.212 ms/op
     p(99.9990) =     32.014 ms/op
     p(99.9999) =     32.801 ms/op
    p(100.0000) =     32.801 ms/op


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
# Warmup Iteration   1: 8.567 ±(99.9%) 0.103 ms/op
# Warmup Iteration   2: 3.567 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.421 ±(99.9%) 0.009 ms/op
Iteration   1: 3.250 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.401 ms/op
                 existUser·p0.50:   3.203 ms/op
                 existUser·p0.90:   3.715 ms/op
                 existUser·p0.95:   4.043 ms/op
                 existUser·p0.99:   5.480 ms/op
                 existUser·p0.999:  9.554 ms/op
                 existUser·p0.9999: 23.276 ms/op
                 existUser·p1.00:   25.133 ms/op

Iteration   2: 3.676 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.037 ms/op
                 existUser·p0.50:   3.543 ms/op
                 existUser·p0.90:   4.399 ms/op
                 existUser·p0.95:   4.841 ms/op
                 existUser·p0.99:   6.455 ms/op
                 existUser·p0.999:  23.862 ms/op
                 existUser·p0.9999: 27.427 ms/op
                 existUser·p1.00:   28.049 ms/op

Iteration   3: 3.380 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.618 ms/op
                 existUser·p0.50:   3.277 ms/op
                 existUser·p0.90:   4.006 ms/op
                 existUser·p0.95:   4.375 ms/op
                 existUser·p0.99:   5.931 ms/op
                 existUser·p0.999:  20.886 ms/op
                 existUser·p0.9999: 29.330 ms/op
                 existUser·p1.00:   29.721 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 279919
  mean =      3.426 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8466 
    [ 2.500,  5.000) = 264693 
    [ 5.000,  7.500) = 5828 
    [ 7.500, 10.000) = 469 
    [10.000, 12.500) = 154 
    [12.500, 15.000) = 49 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 70 
    [22.500, 25.000) = 75 
    [25.000, 27.500) = 89 

  Percentiles, ms/op:
      p(0.0000) =      1.037 ms/op
     p(50.0000) =      3.326 ms/op
     p(90.0000) =      4.092 ms/op
     p(95.0000) =      4.489 ms/op
     p(99.0000) =      6.038 ms/op
     p(99.9000) =     13.420 ms/op
     p(99.9900) =     27.394 ms/op
     p(99.9990) =     29.629 ms/op
     p(99.9999) =     29.721 ms/op
    p(100.0000) =     29.721 ms/op


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
# Warmup Iteration   1: 10.411 ±(99.9%) 0.115 ms/op
# Warmup Iteration   2: 3.696 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.563 ±(99.9%) 0.011 ms/op
Iteration   1: 3.425 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.967 ms/op
                 getUser·p0.50:   3.318 ms/op
                 getUser·p0.90:   4.055 ms/op
                 getUser·p0.95:   4.588 ms/op
                 getUser·p0.99:   6.398 ms/op
                 getUser·p0.999:  20.149 ms/op
                 getUser·p0.9999: 25.504 ms/op
                 getUser·p1.00:   25.821 ms/op

Iteration   2: 3.394 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.720 ms/op
                 getUser·p0.50:   3.301 ms/op
                 getUser·p0.90:   4.014 ms/op
                 getUser·p0.95:   4.473 ms/op
                 getUser·p0.99:   6.054 ms/op
                 getUser·p0.999:  20.866 ms/op
                 getUser·p0.9999: 31.883 ms/op
                 getUser·p1.00:   32.309 ms/op

Iteration   3: 3.456 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.374 ms/op
                 getUser·p0.50:   3.387 ms/op
                 getUser·p0.90:   3.924 ms/op
                 getUser·p0.95:   4.129 ms/op
                 getUser·p0.99:   5.874 ms/op
                 getUser·p0.999:  12.330 ms/op
                 getUser·p0.9999: 26.960 ms/op
                 getUser·p1.00:   27.951 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 280152
  mean =      3.425 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10075 
    [ 2.500,  5.000) = 262397 
    [ 5.000,  7.500) = 6656 
    [ 7.500, 10.000) = 643 
    [10.000, 12.500) = 108 
    [12.500, 15.000) = 17 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 84 
    [22.500, 25.000) = 87 
    [25.000, 27.500) = 50 
    [27.500, 30.000) = 12 
    [30.000, 32.500) = 23 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.967 ms/op
     p(50.0000) =      3.334 ms/op
     p(90.0000) =      3.981 ms/op
     p(95.0000) =      4.383 ms/op
     p(99.0000) =      6.169 ms/op
     p(99.9000) =     12.433 ms/op
     p(99.9900) =     29.655 ms/op
     p(99.9990) =     32.198 ms/op
     p(99.9999) =     32.309 ms/op
    p(100.0000) =     32.309 ms/op


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
# Warmup Iteration   1: 10.800 ±(99.9%) 0.154 ms/op
# Warmup Iteration   2: 4.585 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.063 ±(99.9%) 0.014 ms/op
Iteration   1: 4.020 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.624 ms/op
                 listUser·p0.50:   3.854 ms/op
                 listUser·p0.90:   4.588 ms/op
                 listUser·p0.95:   4.998 ms/op
                 listUser·p0.99:   8.258 ms/op
                 listUser·p0.999:  23.069 ms/op
                 listUser·p0.9999: 25.325 ms/op
                 listUser·p1.00:   27.034 ms/op

Iteration   2: 3.985 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.150 ms/op
                 listUser·p0.50:   3.842 ms/op
                 listUser·p0.90:   4.653 ms/op
                 listUser·p0.95:   5.169 ms/op
                 listUser·p0.99:   7.324 ms/op
                 listUser·p0.999:  15.200 ms/op
                 listUser·p0.9999: 19.557 ms/op
                 listUser·p1.00:   20.087 ms/op

Iteration   3: 3.851 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.001 ms/op
                 listUser·p0.50:   3.760 ms/op
                 listUser·p0.90:   4.342 ms/op
                 listUser·p0.95:   4.604 ms/op
                 listUser·p0.99:   7.029 ms/op
                 listUser·p0.999:  15.795 ms/op
                 listUser·p0.9999: 18.897 ms/op
                 listUser·p1.00:   19.268 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 242731
  mean =      3.950 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 198 
    [ 2.500,  5.000) = 231707 
    [ 5.000,  7.500) = 8245 
    [ 7.500, 10.000) = 1536 
    [10.000, 12.500) = 440 
    [12.500, 15.000) = 255 
    [15.000, 17.500) = 132 
    [17.500, 20.000) = 94 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 77 
    [25.000, 27.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      1.624 ms/op
     p(50.0000) =      3.813 ms/op
     p(90.0000) =      4.522 ms/op
     p(95.0000) =      4.915 ms/op
     p(99.0000) =      7.594 ms/op
     p(99.9000) =     16.725 ms/op
     p(99.9900) =     24.689 ms/op
     p(99.9990) =     26.987 ms/op
     p(99.9999) =     27.034 ms/op
    p(100.0000) =     27.034 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.540 ± 2.829  ops/ms
ClientPb.existUser                       thrpt       3   9.516 ± 7.599  ops/ms
ClientPb.getUser                         thrpt       3   9.615 ± 4.223  ops/ms
ClientPb.listUser                        thrpt       3   8.205 ± 1.543  ops/ms
ClientPb.createUser                       avgt       3   3.463 ± 1.964   ms/op
ClientPb.existUser                        avgt       3   3.270 ± 0.217   ms/op
ClientPb.getUser                          avgt       3   3.335 ± 1.041   ms/op
ClientPb.listUser                         avgt       3   3.988 ± 1.901   ms/op
ClientPb.createUser                     sample  284387   3.369 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.051           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.285           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.899           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.334           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.800           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.497           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.212           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.801           ms/op
ClientPb.existUser                      sample  279919   3.426 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.037           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.326           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.092           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.489           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.038           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.420           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.394           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.721           ms/op
ClientPb.getUser                        sample  280152   3.425 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.967           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.334           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.981           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.383           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.169           ms/op
ClientPb.getUser:getUser·p0.999         sample          12.433           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.655           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.309           ms/op
ClientPb.listUser                       sample  242731   3.950 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.624           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.813           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.522           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.915           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.594           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.725           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.689           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.034           ms/op
