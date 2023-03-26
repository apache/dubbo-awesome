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
# Warmup Iteration   1: 2.300 ops/ms
# Warmup Iteration   2: 5.441 ops/ms
# Warmup Iteration   3: 8.872 ops/ms
Iteration   1: 9.383 ops/ms
Iteration   2: 8.993 ops/ms
Iteration   3: 9.468 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.282 ±(99.9%) 4.625 ops/ms [Average]
  (min, avg, max) = (8.993, 9.282, 9.468), stdev = 0.254
  CI (99.9%): [4.657, 13.907] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.082 ops/ms
# Warmup Iteration   2: 8.459 ops/ms
# Warmup Iteration   3: 9.782 ops/ms
Iteration   1: 10.048 ops/ms
Iteration   2: 10.028 ops/ms
Iteration   3: 9.623 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.900 ±(99.9%) 4.375 ops/ms [Average]
  (min, avg, max) = (9.623, 9.900, 10.048), stdev = 0.240
  CI (99.9%): [5.525, 14.274] (assumes normal distribution)


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
# Warmup Iteration   1: 3.607 ops/ms
# Warmup Iteration   2: 8.900 ops/ms
# Warmup Iteration   3: 8.667 ops/ms
Iteration   1: 9.083 ops/ms
Iteration   2: 9.544 ops/ms
Iteration   3: 9.342 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.323 ±(99.9%) 4.217 ops/ms [Average]
  (min, avg, max) = (9.083, 9.323, 9.544), stdev = 0.231
  CI (99.9%): [5.106, 13.539] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.214 ops/ms
# Warmup Iteration   2: 7.337 ops/ms
# Warmup Iteration   3: 7.841 ops/ms
Iteration   1: 7.994 ops/ms
Iteration   2: 8.207 ops/ms
Iteration   3: 7.959 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.053 ±(99.9%) 2.447 ops/ms [Average]
  (min, avg, max) = (7.959, 8.053, 8.207), stdev = 0.134
  CI (99.9%): [5.606, 10.501] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 8.906 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.717 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.574 ±(99.9%) 0.003 ms/op
Iteration   1: 3.313 ±(99.9%) 0.012 ms/op
Iteration   2: 3.451 ±(99.9%) 0.006 ms/op
Iteration   3: 3.335 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.366 ±(99.9%) 1.358 ms/op [Average]
  (min, avg, max) = (3.313, 3.366, 3.451), stdev = 0.074
  CI (99.9%): [2.008, 4.725] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 7.549 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.524 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.308 ±(99.9%) 0.002 ms/op
Iteration   1: 3.192 ±(99.9%) 0.008 ms/op
Iteration   2: 3.174 ±(99.9%) 0.009 ms/op
Iteration   3: 3.217 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.194 ±(99.9%) 0.398 ms/op [Average]
  (min, avg, max) = (3.174, 3.194, 3.217), stdev = 0.022
  CI (99.9%): [2.796, 3.592] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 8.859 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.668 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.498 ±(99.9%) 0.009 ms/op
Iteration   1: 3.312 ±(99.9%) 0.009 ms/op
Iteration   2: 3.316 ±(99.9%) 0.005 ms/op
Iteration   3: 3.506 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.378 ±(99.9%) 2.021 ms/op [Average]
  (min, avg, max) = (3.312, 3.378, 3.506), stdev = 0.111
  CI (99.9%): [1.357, 5.399] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 11.499 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 4.259 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.053 ±(99.9%) 0.008 ms/op
Iteration   1: 3.921 ±(99.9%) 0.013 ms/op
Iteration   2: 4.004 ±(99.9%) 0.008 ms/op
Iteration   3: 3.995 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.973 ±(99.9%) 0.836 ms/op [Average]
  (min, avg, max) = (3.921, 3.973, 4.004), stdev = 0.046
  CI (99.9%): [3.137, 4.810] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 8.965 ±(99.9%) 0.116 ms/op
# Warmup Iteration   2: 3.813 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.546 ±(99.9%) 0.013 ms/op
Iteration   1: 3.339 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.755 ms/op
                 createUser·p0.50:   3.297 ms/op
                 createUser·p0.90:   3.600 ms/op
                 createUser·p0.95:   3.977 ms/op
                 createUser·p0.99:   5.554 ms/op
                 createUser·p0.999:  21.296 ms/op
                 createUser·p0.9999: 27.552 ms/op
                 createUser·p1.00:   28.574 ms/op

Iteration   2: 3.326 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.341 ms/op
                 createUser·p0.50:   3.273 ms/op
                 createUser·p0.90:   3.584 ms/op
                 createUser·p0.95:   4.030 ms/op
                 createUser·p0.99:   5.587 ms/op
                 createUser·p0.999:  18.455 ms/op
                 createUser·p0.9999: 23.998 ms/op
                 createUser·p1.00:   24.707 ms/op

Iteration   3: 3.416 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.647 ms/op
                 createUser·p0.50:   3.371 ms/op
                 createUser·p0.90:   3.875 ms/op
                 createUser·p0.95:   4.186 ms/op
                 createUser·p0.99:   5.497 ms/op
                 createUser·p0.999:  22.387 ms/op
                 createUser·p0.9999: 29.744 ms/op
                 createUser·p1.00:   30.835 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 285986
  mean =      3.360 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19657 
    [ 2.500,  5.000) = 261236 
    [ 5.000,  7.500) = 4092 
    [ 7.500, 10.000) = 508 
    [10.000, 12.500) = 166 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 6 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 69 
    [22.500, 25.000) = 140 
    [25.000, 27.500) = 43 
    [27.500, 30.000) = 33 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.341 ms/op
     p(50.0000) =      3.310 ms/op
     p(90.0000) =      3.670 ms/op
     p(95.0000) =      4.092 ms/op
     p(99.0000) =      5.546 ms/op
     p(99.9000) =     21.267 ms/op
     p(99.9900) =     28.863 ms/op
     p(99.9990) =     30.384 ms/op
     p(99.9999) =     30.835 ms/op
    p(100.0000) =     30.835 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 8.321 ±(99.9%) 0.127 ms/op
# Warmup Iteration   2: 3.494 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.275 ±(99.9%) 0.009 ms/op
Iteration   1: 3.344 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.098 ms/op
                 existUser·p0.50:   3.256 ms/op
                 existUser·p0.90:   3.736 ms/op
                 existUser·p0.95:   4.047 ms/op
                 existUser·p0.99:   5.341 ms/op
                 existUser·p0.999:  19.169 ms/op
                 existUser·p0.9999: 27.787 ms/op
                 existUser·p1.00:   28.049 ms/op

Iteration   2: 3.276 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.966 ms/op
                 existUser·p0.50:   3.187 ms/op
                 existUser·p0.90:   3.531 ms/op
                 existUser·p0.95:   4.637 ms/op
                 existUser·p0.99:   5.373 ms/op
                 existUser·p0.999:  12.812 ms/op
                 existUser·p0.9999: 24.092 ms/op
                 existUser·p1.00:   24.674 ms/op

Iteration   3: 3.319 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.765 ms/op
                 existUser·p0.50:   3.244 ms/op
                 existUser·p0.90:   3.633 ms/op
                 existUser·p0.95:   3.940 ms/op
                 existUser·p0.99:   5.800 ms/op
                 existUser·p0.999:  16.496 ms/op
                 existUser·p0.9999: 24.339 ms/op
                 existUser·p1.00:   25.133 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 289406
  mean =      3.313 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11905 
    [ 2.500,  5.000) = 272766 
    [ 5.000,  7.500) = 4035 
    [ 7.500, 10.000) = 353 
    [10.000, 12.500) = 50 
    [12.500, 15.000) = 8 
    [15.000, 17.500) = 18 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 48 
    [22.500, 25.000) = 153 
    [25.000, 27.500) = 25 

  Percentiles, ms/op:
      p(0.0000) =      0.966 ms/op
     p(50.0000) =      3.219 ms/op
     p(90.0000) =      3.670 ms/op
     p(95.0000) =      4.080 ms/op
     p(99.0000) =      5.472 ms/op
     p(99.9000) =     14.930 ms/op
     p(99.9900) =     27.230 ms/op
     p(99.9990) =     28.049 ms/op
     p(99.9999) =     28.049 ms/op
    p(100.0000) =     28.049 ms/op


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
# Warmup Iteration   1: 8.369 ±(99.9%) 0.110 ms/op
# Warmup Iteration   2: 3.807 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.469 ±(99.9%) 0.010 ms/op
Iteration   1: 3.554 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.017 ms/op
                 getUser·p0.50:   3.387 ms/op
                 getUser·p0.90:   3.936 ms/op
                 getUser·p0.95:   5.120 ms/op
                 getUser·p0.99:   7.258 ms/op
                 getUser·p0.999:  20.054 ms/op
                 getUser·p0.9999: 25.099 ms/op
                 getUser·p1.00:   25.461 ms/op

Iteration   2: 3.356 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.027 ms/op
                 getUser·p0.50:   3.281 ms/op
                 getUser·p0.90:   3.662 ms/op
                 getUser·p0.95:   3.813 ms/op
                 getUser·p0.99:   5.228 ms/op
                 getUser·p0.999:  21.512 ms/op
                 getUser·p0.9999: 25.672 ms/op
                 getUser·p1.00:   26.575 ms/op

Iteration   3: 3.418 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.315 ms/op
                 getUser·p0.50:   3.301 ms/op
                 getUser·p0.90:   3.736 ms/op
                 getUser·p0.95:   3.924 ms/op
                 getUser·p0.99:   5.900 ms/op
                 getUser·p0.999:  18.994 ms/op
                 getUser·p0.9999: 26.104 ms/op
                 getUser·p1.00:   27.034 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 279116
  mean =      3.440 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3618 
    [ 2.500,  5.000) = 267192 
    [ 5.000,  7.500) = 6998 
    [ 7.500, 10.000) = 922 
    [10.000, 12.500) = 98 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 96 
    [22.500, 25.000) = 117 
    [25.000, 27.500) = 57 

  Percentiles, ms/op:
      p(0.0000) =      1.017 ms/op
     p(50.0000) =      3.318 ms/op
     p(90.0000) =      3.764 ms/op
     p(95.0000) =      4.035 ms/op
     p(99.0000) =      6.603 ms/op
     p(99.9000) =     19.297 ms/op
     p(99.9900) =     25.467 ms/op
     p(99.9990) =     27.001 ms/op
     p(99.9999) =     27.034 ms/op
    p(100.0000) =     27.034 ms/op


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
# Warmup Iteration   1: 11.398 ±(99.9%) 0.153 ms/op
# Warmup Iteration   2: 4.507 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.127 ±(99.9%) 0.014 ms/op
Iteration   1: 3.972 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.763 ms/op
                 listUser·p0.50:   3.809 ms/op
                 listUser·p0.90:   4.375 ms/op
                 listUser·p0.95:   4.923 ms/op
                 listUser·p0.99:   7.160 ms/op
                 listUser·p0.999:  20.418 ms/op
                 listUser·p0.9999: 23.224 ms/op
                 listUser·p1.00:   25.068 ms/op

Iteration   2: 4.101 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.767 ms/op
                 listUser·p0.50:   4.030 ms/op
                 listUser·p0.90:   4.407 ms/op
                 listUser·p0.95:   4.604 ms/op
                 listUser·p0.99:   7.324 ms/op
                 listUser·p0.999:  15.877 ms/op
                 listUser·p0.9999: 18.560 ms/op
                 listUser·p1.00:   19.661 ms/op

Iteration   3: 4.056 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.413 ms/op
                 listUser·p0.50:   3.944 ms/op
                 listUser·p0.90:   4.358 ms/op
                 listUser·p0.95:   4.612 ms/op
                 listUser·p0.99:   7.860 ms/op
                 listUser·p0.999:  15.230 ms/op
                 listUser·p0.9999: 16.876 ms/op
                 listUser·p1.00:   17.170 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 237533
  mean =      4.042 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 33 
    [ 2.500,  5.000) = 228823 
    [ 5.000,  7.500) = 6329 
    [ 7.500, 10.000) = 1694 
    [10.000, 12.500) = 192 
    [12.500, 15.000) = 90 
    [15.000, 17.500) = 236 
    [17.500, 20.000) = 49 
    [20.000, 22.500) = 67 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.763 ms/op
     p(50.0000) =      3.903 ms/op
     p(90.0000) =      4.383 ms/op
     p(95.0000) =      4.678 ms/op
     p(99.0000) =      7.479 ms/op
     p(99.9000) =     16.015 ms/op
     p(99.9900) =     22.381 ms/op
     p(99.9990) =     24.088 ms/op
     p(99.9999) =     25.068 ms/op
    p(100.0000) =     25.068 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.282 ± 4.625  ops/ms
ClientPb.existUser                       thrpt       3   9.900 ± 4.375  ops/ms
ClientPb.getUser                         thrpt       3   9.323 ± 4.217  ops/ms
ClientPb.listUser                        thrpt       3   8.053 ± 2.447  ops/ms
ClientPb.createUser                       avgt       3   3.366 ± 1.358   ms/op
ClientPb.existUser                        avgt       3   3.194 ± 0.398   ms/op
ClientPb.getUser                          avgt       3   3.378 ± 2.021   ms/op
ClientPb.listUser                         avgt       3   3.973 ± 0.836   ms/op
ClientPb.createUser                     sample  285986   3.360 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.341           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.310           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.670           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.092           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.546           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.267           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.863           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.835           ms/op
ClientPb.existUser                      sample  289406   3.313 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.966           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.219           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.670           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.080           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.472           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.930           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.230           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.049           ms/op
ClientPb.getUser                        sample  279116   3.440 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.017           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.318           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.764           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.035           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.603           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.297           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.467           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.034           ms/op
ClientPb.listUser                       sample  237533   4.042 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.763           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.903           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.383           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.678           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.479           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.015           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.381           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.068           ms/op
