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
# Warmup Iteration   1: 2.057 ops/ms
# Warmup Iteration   2: 5.026 ops/ms
# Warmup Iteration   3: 8.694 ops/ms
Iteration   1: 9.217 ops/ms
Iteration   2: 8.998 ops/ms
Iteration   3: 9.214 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.143 ±(99.9%) 2.291 ops/ms [Average]
  (min, avg, max) = (8.998, 9.143, 9.217), stdev = 0.126
  CI (99.9%): [6.853, 11.434] (assumes normal distribution)


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
# Warmup Iteration   1: 2.596 ops/ms
# Warmup Iteration   2: 8.432 ops/ms
# Warmup Iteration   3: 9.120 ops/ms
Iteration   1: 9.239 ops/ms
Iteration   2: 9.529 ops/ms
Iteration   3: 9.423 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.397 ±(99.9%) 2.674 ops/ms [Average]
  (min, avg, max) = (9.239, 9.397, 9.529), stdev = 0.147
  CI (99.9%): [6.723, 12.072] (assumes normal distribution)


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
# Warmup Iteration   1: 2.755 ops/ms
# Warmup Iteration   2: 8.308 ops/ms
# Warmup Iteration   3: 8.768 ops/ms
Iteration   1: 9.327 ops/ms
Iteration   2: 9.154 ops/ms
Iteration   3: 9.271 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.251 ±(99.9%) 1.615 ops/ms [Average]
  (min, avg, max) = (9.154, 9.251, 9.327), stdev = 0.089
  CI (99.9%): [7.636, 10.865] (assumes normal distribution)


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
# Warmup Iteration   1: 2.659 ops/ms
# Warmup Iteration   2: 7.390 ops/ms
# Warmup Iteration   3: 7.809 ops/ms
Iteration   1: 7.956 ops/ms
Iteration   2: 8.096 ops/ms
Iteration   3: 8.117 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.056 ±(99.9%) 1.597 ops/ms [Average]
  (min, avg, max) = (7.956, 8.056, 8.117), stdev = 0.088
  CI (99.9%): [6.459, 9.653] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 10.146 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 4.096 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.752 ±(99.9%) 0.006 ms/op
Iteration   1: 3.625 ±(99.9%) 0.006 ms/op
Iteration   2: 3.421 ±(99.9%) 0.010 ms/op
Iteration   3: 3.477 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.508 ±(99.9%) 1.922 ms/op [Average]
  (min, avg, max) = (3.421, 3.508, 3.625), stdev = 0.105
  CI (99.9%): [1.586, 5.429] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 10.062 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.599 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.394 ±(99.9%) 0.009 ms/op
Iteration   1: 3.270 ±(99.9%) 0.005 ms/op
Iteration   2: 3.452 ±(99.9%) 0.008 ms/op
Iteration   3: 3.263 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.329 ±(99.9%) 1.955 ms/op [Average]
  (min, avg, max) = (3.263, 3.329, 3.452), stdev = 0.107
  CI (99.9%): [1.373, 5.284] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 9.216 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.642 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.471 ±(99.9%) 0.008 ms/op
Iteration   1: 3.485 ±(99.9%) 0.008 ms/op
Iteration   2: 3.423 ±(99.9%) 0.004 ms/op
Iteration   3: 3.325 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.411 ±(99.9%) 1.469 ms/op [Average]
  (min, avg, max) = (3.325, 3.411, 3.485), stdev = 0.081
  CI (99.9%): [1.942, 4.880] (assumes normal distribution)


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
# Warmup Iteration   1: 10.240 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 4.480 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.152 ±(99.9%) 0.013 ms/op
Iteration   1: 3.967 ±(99.9%) 0.011 ms/op
Iteration   2: 3.953 ±(99.9%) 0.014 ms/op
Iteration   3: 4.106 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.009 ±(99.9%) 1.540 ms/op [Average]
  (min, avg, max) = (3.953, 4.009, 4.106), stdev = 0.084
  CI (99.9%): [2.468, 5.549] (assumes normal distribution)


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
# Warmup Iteration   1: 10.830 ±(99.9%) 0.134 ms/op
# Warmup Iteration   2: 4.256 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.740 ±(99.9%) 0.014 ms/op
Iteration   1: 3.379 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.661 ms/op
                 createUser·p0.50:   3.277 ms/op
                 createUser·p0.90:   3.695 ms/op
                 createUser·p0.95:   4.026 ms/op
                 createUser·p0.99:   5.734 ms/op
                 createUser·p0.999:  22.075 ms/op
                 createUser·p0.9999: 30.072 ms/op
                 createUser·p1.00:   30.736 ms/op

Iteration   2: 3.627 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.366 ms/op
                 createUser·p0.50:   3.453 ms/op
                 createUser·p0.90:   4.334 ms/op
                 createUser·p0.95:   4.579 ms/op
                 createUser·p0.99:   5.882 ms/op
                 createUser·p0.999:  23.095 ms/op
                 createUser·p0.9999: 28.225 ms/op
                 createUser·p1.00:   28.836 ms/op

Iteration   3: 3.488 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.975 ms/op
                 createUser·p0.50:   3.367 ms/op
                 createUser·p0.90:   3.940 ms/op
                 createUser·p0.95:   4.235 ms/op
                 createUser·p0.99:   6.300 ms/op
                 createUser·p0.999:  18.940 ms/op
                 createUser·p0.9999: 32.134 ms/op
                 createUser·p1.00:   32.571 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 274642
  mean =      3.495 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7931 
    [ 2.500,  5.000) = 260930 
    [ 5.000,  7.500) = 4901 
    [ 7.500, 10.000) = 460 
    [10.000, 12.500) = 63 
    [12.500, 15.000) = 50 
    [15.000, 17.500) = 15 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 111 
    [25.000, 27.500) = 54 
    [27.500, 30.000) = 44 
    [30.000, 32.500) = 40 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.975 ms/op
     p(50.0000) =      3.367 ms/op
     p(90.0000) =      4.076 ms/op
     p(95.0000) =      4.383 ms/op
     p(99.0000) =      5.906 ms/op
     p(99.9000) =     19.270 ms/op
     p(99.9900) =     31.293 ms/op
     p(99.9990) =     32.449 ms/op
     p(99.9999) =     32.571 ms/op
    p(100.0000) =     32.571 ms/op


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
# Warmup Iteration   1: 9.154 ±(99.9%) 0.119 ms/op
# Warmup Iteration   2: 3.602 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.501 ±(99.9%) 0.011 ms/op
Iteration   1: 3.371 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.647 ms/op
                 existUser·p0.50:   3.215 ms/op
                 existUser·p0.90:   3.867 ms/op
                 existUser·p0.95:   4.293 ms/op
                 existUser·p0.99:   5.808 ms/op
                 existUser·p0.999:  9.339 ms/op
                 existUser·p0.9999: 34.047 ms/op
                 existUser·p1.00:   35.389 ms/op

Iteration   2: 3.232 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.651 ms/op
                 existUser·p0.50:   3.154 ms/op
                 existUser·p0.90:   3.469 ms/op
                 existUser·p0.95:   3.690 ms/op
                 existUser·p0.99:   5.702 ms/op
                 existUser·p0.999:  14.693 ms/op
                 existUser·p0.9999: 26.775 ms/op
                 existUser·p1.00:   27.197 ms/op

Iteration   3: 3.419 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.806 ms/op
                 existUser·p0.50:   3.297 ms/op
                 existUser·p0.90:   4.024 ms/op
                 existUser·p0.95:   4.366 ms/op
                 existUser·p0.99:   6.005 ms/op
                 existUser·p0.999:  21.066 ms/op
                 existUser·p0.9999: 28.120 ms/op
                 existUser·p1.00:   31.982 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 287374
  mean =      3.339 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12010 
    [ 2.500,  5.000) = 269714 
    [ 5.000,  7.500) = 4834 
    [ 7.500, 10.000) = 359 
    [10.000, 12.500) = 96 
    [12.500, 15.000) = 91 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 75 
    [25.000, 27.500) = 64 
    [27.500, 30.000) = 62 
    [30.000, 32.500) = 10 
    [32.500, 35.000) = 23 
    [35.000, 37.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.647 ms/op
     p(50.0000) =      3.232 ms/op
     p(90.0000) =      3.805 ms/op
     p(95.0000) =      4.202 ms/op
     p(99.0000) =      5.857 ms/op
     p(99.9000) =     14.002 ms/op
     p(99.9900) =     32.383 ms/op
     p(99.9990) =     35.070 ms/op
     p(99.9999) =     35.389 ms/op
    p(100.0000) =     35.389 ms/op


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
# Warmup Iteration   1: 10.357 ±(99.9%) 0.122 ms/op
# Warmup Iteration   2: 3.816 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.647 ±(99.9%) 0.013 ms/op
Iteration   1: 3.564 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.532 ms/op
                 getUser·p0.50:   3.326 ms/op
                 getUser·p0.90:   3.899 ms/op
                 getUser·p0.95:   5.644 ms/op
                 getUser·p0.99:   7.487 ms/op
                 getUser·p0.999:  20.447 ms/op
                 getUser·p0.9999: 24.674 ms/op
                 getUser·p1.00:   25.461 ms/op

Iteration   2: 3.399 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.851 ms/op
                 getUser·p0.50:   3.318 ms/op
                 getUser·p0.90:   3.752 ms/op
                 getUser·p0.95:   3.940 ms/op
                 getUser·p0.99:   5.693 ms/op
                 getUser·p0.999:  21.821 ms/op
                 getUser·p0.9999: 25.434 ms/op
                 getUser·p1.00:   26.804 ms/op

Iteration   3: 3.476 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.522 ms/op
                 getUser·p0.50:   3.334 ms/op
                 getUser·p0.90:   3.846 ms/op
                 getUser·p0.95:   4.121 ms/op
                 getUser·p0.99:   6.300 ms/op
                 getUser·p0.999:  25.233 ms/op
                 getUser·p0.9999: 28.049 ms/op
                 getUser·p1.00:   28.377 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 275753
  mean =      3.478 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4108 
    [ 2.500,  5.000) = 262601 
    [ 5.000,  7.500) = 7483 
    [ 7.500, 10.000) = 988 
    [10.000, 12.500) = 257 
    [12.500, 15.000) = 26 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 70 
    [22.500, 25.000) = 105 
    [25.000, 27.500) = 82 

  Percentiles, ms/op:
      p(0.0000) =      1.522 ms/op
     p(50.0000) =      3.326 ms/op
     p(90.0000) =      3.822 ms/op
     p(95.0000) =      4.194 ms/op
     p(99.0000) =      7.012 ms/op
     p(99.9000) =     20.750 ms/op
     p(99.9900) =     27.558 ms/op
     p(99.9990) =     28.245 ms/op
     p(99.9999) =     28.377 ms/op
    p(100.0000) =     28.377 ms/op


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
# Warmup Iteration   1: 12.124 ±(99.9%) 0.169 ms/op
# Warmup Iteration   2: 4.633 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.147 ±(99.9%) 0.013 ms/op
Iteration   1: 4.208 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.577 ms/op
                 listUser·p0.50:   3.973 ms/op
                 listUser·p0.90:   4.669 ms/op
                 listUser·p0.95:   5.210 ms/op
                 listUser·p0.99:   8.143 ms/op
                 listUser·p0.999:  21.921 ms/op
                 listUser·p0.9999: 24.445 ms/op
                 listUser·p1.00:   25.100 ms/op

Iteration   2: 3.968 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.331 ms/op
                 listUser·p0.50:   3.916 ms/op
                 listUser·p0.90:   4.149 ms/op
                 listUser·p0.95:   4.735 ms/op
                 listUser·p0.99:   6.701 ms/op
                 listUser·p0.999:  16.824 ms/op
                 listUser·p0.9999: 25.625 ms/op
                 listUser·p1.00:   25.690 ms/op

Iteration   3: 4.089 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.372 ms/op
                 listUser·p0.50:   4.002 ms/op
                 listUser·p0.90:   4.391 ms/op
                 listUser·p0.95:   4.612 ms/op
                 listUser·p0.99:   6.996 ms/op
                 listUser·p0.999:  15.953 ms/op
                 listUser·p0.9999: 25.106 ms/op
                 listUser·p1.00:   26.182 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 234903
  mean =      4.086 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 39 
    [ 2.500,  5.000) = 225657 
    [ 5.000,  7.500) = 7066 
    [ 7.500, 10.000) = 1337 
    [10.000, 12.500) = 269 
    [12.500, 15.000) = 78 
    [15.000, 17.500) = 177 
    [17.500, 20.000) = 98 
    [20.000, 22.500) = 72 
    [22.500, 25.000) = 82 
    [25.000, 27.500) = 28 

  Percentiles, ms/op:
      p(0.0000) =      1.577 ms/op
     p(50.0000) =      3.940 ms/op
     p(90.0000) =      4.481 ms/op
     p(95.0000) =      4.825 ms/op
     p(99.0000) =      7.340 ms/op
     p(99.9000) =     17.859 ms/op
     p(99.9900) =     25.117 ms/op
     p(99.9990) =     25.679 ms/op
     p(99.9999) =     26.182 ms/op
    p(100.0000) =     26.182 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.143 ± 2.291  ops/ms
ClientPb.existUser                       thrpt       3   9.397 ± 2.674  ops/ms
ClientPb.getUser                         thrpt       3   9.251 ± 1.615  ops/ms
ClientPb.listUser                        thrpt       3   8.056 ± 1.597  ops/ms
ClientPb.createUser                       avgt       3   3.508 ± 1.922   ms/op
ClientPb.existUser                        avgt       3   3.329 ± 1.955   ms/op
ClientPb.getUser                          avgt       3   3.411 ± 1.469   ms/op
ClientPb.listUser                         avgt       3   4.009 ± 1.540   ms/op
ClientPb.createUser                     sample  274642   3.495 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.975           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.367           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.076           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.383           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.906           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.270           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.293           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.571           ms/op
ClientPb.existUser                      sample  287374   3.339 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.647           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.232           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.805           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.202           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.857           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.002           ms/op
ClientPb.existUser:existUser·p0.9999    sample          32.383           ms/op
ClientPb.existUser:existUser·p1.00      sample          35.389           ms/op
ClientPb.getUser                        sample  275753   3.478 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.522           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.326           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.822           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.194           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.012           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.750           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.558           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.377           ms/op
ClientPb.listUser                       sample  234903   4.086 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.577           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.940           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.481           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.825           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.340           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.859           ms/op
ClientPb.listUser:listUser·p0.9999      sample          25.117           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.182           ms/op
