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
# Warmup Iteration   1: 2.066 ops/ms
# Warmup Iteration   2: 5.237 ops/ms
# Warmup Iteration   3: 8.567 ops/ms
Iteration   1: 9.485 ops/ms
Iteration   2: 9.285 ops/ms
Iteration   3: 9.534 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.434 ±(99.9%) 2.405 ops/ms [Average]
  (min, avg, max) = (9.285, 9.434, 9.534), stdev = 0.132
  CI (99.9%): [7.030, 11.839] (assumes normal distribution)


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
# Warmup Iteration   1: 2.882 ops/ms
# Warmup Iteration   2: 8.756 ops/ms
# Warmup Iteration   3: 9.212 ops/ms
Iteration   1: 9.977 ops/ms
Iteration   2: 9.597 ops/ms
Iteration   3: 9.933 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.836 ±(99.9%) 3.795 ops/ms [Average]
  (min, avg, max) = (9.597, 9.836, 9.977), stdev = 0.208
  CI (99.9%): [6.041, 13.631] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 2.670 ops/ms
# Warmup Iteration   2: 8.314 ops/ms
# Warmup Iteration   3: 8.801 ops/ms
Iteration   1: 9.273 ops/ms
Iteration   2: 9.128 ops/ms
Iteration   3: 9.262 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.221 ±(99.9%) 1.469 ops/ms [Average]
  (min, avg, max) = (9.128, 9.221, 9.273), stdev = 0.080
  CI (99.9%): [7.752, 10.690] (assumes normal distribution)


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
# Warmup Iteration   1: 2.829 ops/ms
# Warmup Iteration   2: 6.620 ops/ms
# Warmup Iteration   3: 7.874 ops/ms
Iteration   1: 7.868 ops/ms
Iteration   2: 8.148 ops/ms
Iteration   3: 8.108 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.041 ±(99.9%) 2.765 ops/ms [Average]
  (min, avg, max) = (7.868, 8.041, 8.148), stdev = 0.152
  CI (99.9%): [5.276, 10.807] (assumes normal distribution)


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
# Warmup Iteration   1: 9.789 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.762 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.557 ±(99.9%) 0.004 ms/op
Iteration   1: 3.569 ±(99.9%) 0.006 ms/op
Iteration   2: 3.390 ±(99.9%) 0.009 ms/op
Iteration   3: 3.521 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.493 ±(99.9%) 1.687 ms/op [Average]
  (min, avg, max) = (3.390, 3.493, 3.569), stdev = 0.092
  CI (99.9%): [1.806, 5.180] (assumes normal distribution)


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
# Warmup Iteration   1: 9.795 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.540 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.286 ±(99.9%) 0.003 ms/op
Iteration   1: 3.226 ±(99.9%) 0.005 ms/op
Iteration   2: 3.251 ±(99.9%) 0.007 ms/op
Iteration   3: 3.209 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.229 ±(99.9%) 0.388 ms/op [Average]
  (min, avg, max) = (3.209, 3.229, 3.251), stdev = 0.021
  CI (99.9%): [2.841, 3.616] (assumes normal distribution)


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
# Warmup Iteration   1: 10.234 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.879 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.354 ±(99.9%) 0.005 ms/op
Iteration   1: 3.507 ±(99.9%) 0.007 ms/op
Iteration   2: 3.487 ±(99.9%) 0.007 ms/op
Iteration   3: 3.439 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.478 ±(99.9%) 0.639 ms/op [Average]
  (min, avg, max) = (3.439, 3.478, 3.507), stdev = 0.035
  CI (99.9%): [2.839, 4.116] (assumes normal distribution)


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
# Warmup Iteration   1: 10.457 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 4.438 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.064 ±(99.9%) 0.004 ms/op
Iteration   1: 4.158 ±(99.9%) 0.003 ms/op
Iteration   2: 3.921 ±(99.9%) 0.010 ms/op
Iteration   3: 3.991 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.023 ±(99.9%) 2.217 ms/op [Average]
  (min, avg, max) = (3.921, 4.023, 4.158), stdev = 0.122
  CI (99.9%): [1.806, 6.241] (assumes normal distribution)


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
# Warmup Iteration   1: 8.379 ±(99.9%) 0.105 ms/op
# Warmup Iteration   2: 4.147 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.429 ±(99.9%) 0.009 ms/op
Iteration   1: 3.380 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.487 ms/op
                 createUser·p0.50:   3.371 ms/op
                 createUser·p0.90:   3.486 ms/op
                 createUser·p0.95:   3.690 ms/op
                 createUser·p0.99:   6.431 ms/op
                 createUser·p0.999:  18.498 ms/op
                 createUser·p0.9999: 27.329 ms/op
                 createUser·p1.00:   28.017 ms/op

Iteration   2: 3.330 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.274 ms/op
                 createUser·p0.50:   3.297 ms/op
                 createUser·p0.90:   3.498 ms/op
                 createUser·p0.95:   3.760 ms/op
                 createUser·p0.99:   5.638 ms/op
                 createUser·p0.999:  20.048 ms/op
                 createUser·p0.9999: 23.147 ms/op
                 createUser·p1.00:   23.855 ms/op

Iteration   3: 3.356 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.442 ms/op
                 createUser·p0.50:   3.265 ms/op
                 createUser·p0.90:   3.727 ms/op
                 createUser·p0.95:   4.051 ms/op
                 createUser·p0.99:   5.358 ms/op
                 createUser·p0.999:  19.464 ms/op
                 createUser·p0.9999: 24.395 ms/op
                 createUser·p1.00:   25.428 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 285986
  mean =      3.355 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15371 
    [ 2.500,  5.000) = 265594 
    [ 5.000,  7.500) = 4079 
    [ 7.500, 10.000) = 419 
    [10.000, 12.500) = 129 
    [12.500, 15.000) = 43 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 87 
    [20.000, 22.500) = 127 
    [22.500, 25.000) = 81 
    [25.000, 27.500) = 33 

  Percentiles, ms/op:
      p(0.0000) =      1.274 ms/op
     p(50.0000) =      3.326 ms/op
     p(90.0000) =      3.535 ms/op
     p(95.0000) =      3.879 ms/op
     p(99.0000) =      5.744 ms/op
     p(99.9000) =     19.039 ms/op
     p(99.9900) =     25.769 ms/op
     p(99.9990) =     27.661 ms/op
     p(99.9999) =     28.017 ms/op
    p(100.0000) =     28.017 ms/op


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
# Warmup Iteration   1: 8.819 ±(99.9%) 0.112 ms/op
# Warmup Iteration   2: 3.610 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.465 ±(99.9%) 0.009 ms/op
Iteration   1: 3.318 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.233 ms/op
                 existUser·p0.50:   3.228 ms/op
                 existUser·p0.90:   3.650 ms/op
                 existUser·p0.95:   4.096 ms/op
                 existUser·p0.99:   6.177 ms/op
                 existUser·p0.999:  17.231 ms/op
                 existUser·p0.9999: 23.113 ms/op
                 existUser·p1.00:   24.052 ms/op

Iteration   2: 3.219 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.657 ms/op
                 existUser·p0.50:   3.199 ms/op
                 existUser·p0.90:   3.391 ms/op
                 existUser·p0.95:   3.609 ms/op
                 existUser·p0.99:   5.284 ms/op
                 existUser·p0.999:  13.369 ms/op
                 existUser·p0.9999: 27.985 ms/op
                 existUser·p1.00:   28.475 ms/op

Iteration   3: 3.390 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.337 ms/op
                 existUser·p0.50:   3.289 ms/op
                 existUser·p0.90:   3.949 ms/op
                 existUser·p0.95:   4.219 ms/op
                 existUser·p0.99:   5.571 ms/op
                 existUser·p0.999:  8.732 ms/op
                 existUser·p0.9999: 25.035 ms/op
                 existUser·p1.00:   25.494 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 290309
  mean =      3.308 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17606 
    [ 2.500,  5.000) = 267541 
    [ 5.000,  7.500) = 4500 
    [ 7.500, 10.000) = 271 
    [10.000, 12.500) = 103 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 69 
    [22.500, 25.000) = 125 
    [25.000, 27.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      1.233 ms/op
     p(50.0000) =      3.248 ms/op
     p(90.0000) =      3.707 ms/op
     p(95.0000) =      4.043 ms/op
     p(99.0000) =      5.587 ms/op
     p(99.9000) =     12.480 ms/op
     p(99.9900) =     26.443 ms/op
     p(99.9990) =     28.383 ms/op
     p(99.9999) =     28.475 ms/op
    p(100.0000) =     28.475 ms/op


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
# Warmup Iteration   1: 8.814 ±(99.9%) 0.112 ms/op
# Warmup Iteration   2: 3.658 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.500 ±(99.9%) 0.010 ms/op
Iteration   1: 3.448 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.536 ms/op
                 getUser·p0.50:   3.277 ms/op
                 getUser·p0.90:   3.756 ms/op
                 getUser·p0.95:   4.514 ms/op
                 getUser·p0.99:   6.623 ms/op
                 getUser·p0.999:  18.211 ms/op
                 getUser·p0.9999: 25.919 ms/op
                 getUser·p1.00:   26.477 ms/op

Iteration   2: 3.325 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.233 ms/op
                 getUser·p0.50:   3.211 ms/op
                 getUser·p0.90:   3.609 ms/op
                 getUser·p0.95:   3.813 ms/op
                 getUser·p0.99:   5.792 ms/op
                 getUser·p0.999:  19.391 ms/op
                 getUser·p0.9999: 32.707 ms/op
                 getUser·p1.00:   33.260 ms/op

Iteration   3: 3.363 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.528 ms/op
                 getUser·p0.50:   3.236 ms/op
                 getUser·p0.90:   3.752 ms/op
                 getUser·p0.95:   3.965 ms/op
                 getUser·p0.99:   5.759 ms/op
                 getUser·p0.999:  17.167 ms/op
                 getUser·p0.9999: 23.592 ms/op
                 getUser·p1.00:   24.904 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 284040
  mean =      3.378 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1658 
    [ 2.500,  5.000) = 274572 
    [ 5.000,  7.500) = 6599 
    [ 7.500, 10.000) = 713 
    [10.000, 12.500) = 149 
    [12.500, 15.000) = 24 
    [15.000, 17.500) = 44 
    [17.500, 20.000) = 56 
    [20.000, 22.500) = 112 
    [22.500, 25.000) = 69 
    [25.000, 27.500) = 12 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 20 
    [32.500, 35.000) = 12 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.233 ms/op
     p(50.0000) =      3.236 ms/op
     p(90.0000) =      3.707 ms/op
     p(95.0000) =      3.981 ms/op
     p(99.0000) =      6.078 ms/op
     p(99.9000) =     17.302 ms/op
     p(99.9900) =     31.457 ms/op
     p(99.9990) =     33.003 ms/op
     p(99.9999) =     33.260 ms/op
    p(100.0000) =     33.260 ms/op


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
# Warmup Iteration   1: 11.120 ±(99.9%) 0.151 ms/op
# Warmup Iteration   2: 4.598 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.248 ±(99.9%) 0.016 ms/op
Iteration   1: 4.037 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.700 ms/op
                 listUser·p0.50:   3.822 ms/op
                 listUser·p0.90:   4.465 ms/op
                 listUser·p0.95:   4.882 ms/op
                 listUser·p0.99:   7.496 ms/op
                 listUser·p0.999:  20.683 ms/op
                 listUser·p0.9999: 26.706 ms/op
                 listUser·p1.00:   27.918 ms/op

Iteration   2: 4.016 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.417 ms/op
                 listUser·p0.50:   3.834 ms/op
                 listUser·p0.90:   4.424 ms/op
                 listUser·p0.95:   4.710 ms/op
                 listUser·p0.99:   7.315 ms/op
                 listUser·p0.999:  21.922 ms/op
                 listUser·p0.9999: 26.018 ms/op
                 listUser·p1.00:   26.182 ms/op

Iteration   3: 3.954 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.458 ms/op
                 listUser·p0.50:   3.764 ms/op
                 listUser·p0.90:   4.481 ms/op
                 listUser·p0.95:   4.710 ms/op
                 listUser·p0.99:   7.266 ms/op
                 listUser·p0.999:  16.815 ms/op
                 listUser·p0.9999: 20.709 ms/op
                 listUser·p1.00:   22.381 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 239651
  mean =      4.002 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 70 
    [ 2.500,  5.000) = 230593 
    [ 5.000,  7.500) = 6779 
    [ 7.500, 10.000) = 1453 
    [10.000, 12.500) = 231 
    [12.500, 15.000) = 72 
    [15.000, 17.500) = 130 
    [17.500, 20.000) = 96 
    [20.000, 22.500) = 114 
    [22.500, 25.000) = 74 
    [25.000, 27.500) = 38 

  Percentiles, ms/op:
      p(0.0000) =      1.417 ms/op
     p(50.0000) =      3.809 ms/op
     p(90.0000) =      4.456 ms/op
     p(95.0000) =      4.751 ms/op
     p(99.0000) =      7.324 ms/op
     p(99.9000) =     19.738 ms/op
     p(99.9900) =     26.086 ms/op
     p(99.9990) =     27.348 ms/op
     p(99.9999) =     27.918 ms/op
    p(100.0000) =     27.918 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.434 ± 2.405  ops/ms
ClientPb.existUser                       thrpt       3   9.836 ± 3.795  ops/ms
ClientPb.getUser                         thrpt       3   9.221 ± 1.469  ops/ms
ClientPb.listUser                        thrpt       3   8.041 ± 2.765  ops/ms
ClientPb.createUser                       avgt       3   3.493 ± 1.687   ms/op
ClientPb.existUser                        avgt       3   3.229 ± 0.388   ms/op
ClientPb.getUser                          avgt       3   3.478 ± 0.639   ms/op
ClientPb.listUser                         avgt       3   4.023 ± 2.217   ms/op
ClientPb.createUser                     sample  285986   3.355 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.274           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.326           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.535           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.879           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.744           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.039           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.769           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.017           ms/op
ClientPb.existUser                      sample  290309   3.308 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.233           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.248           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.707           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.043           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.587           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.480           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.443           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.475           ms/op
ClientPb.getUser                        sample  284040   3.378 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.233           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.236           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.707           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.981           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.078           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.302           ms/op
ClientPb.getUser:getUser·p0.9999        sample          31.457           ms/op
ClientPb.getUser:getUser·p1.00          sample          33.260           ms/op
ClientPb.listUser                       sample  239651   4.002 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.417           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.809           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.456           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.751           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.324           ms/op
ClientPb.listUser:listUser·p0.999       sample          19.738           ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.086           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.918           ms/op
