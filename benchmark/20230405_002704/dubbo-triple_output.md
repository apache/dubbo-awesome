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
# Warmup Iteration   1: 2.396 ops/ms
# Warmup Iteration   2: 6.048 ops/ms
# Warmup Iteration   3: 8.562 ops/ms
Iteration   1: 9.127 ops/ms
Iteration   2: 9.149 ops/ms
Iteration   3: 9.419 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.232 ±(99.9%) 2.969 ops/ms [Average]
  (min, avg, max) = (9.127, 9.232, 9.419), stdev = 0.163
  CI (99.9%): [6.263, 12.200] (assumes normal distribution)


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
# Warmup Iteration   1: 3.886 ops/ms
# Warmup Iteration   2: 8.993 ops/ms
# Warmup Iteration   3: 9.406 ops/ms
Iteration   1: 9.390 ops/ms
Iteration   2: 9.597 ops/ms
Iteration   3: 9.765 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.584 ±(99.9%) 3.432 ops/ms [Average]
  (min, avg, max) = (9.390, 9.584, 9.765), stdev = 0.188
  CI (99.9%): [6.152, 13.016] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.239 ops/ms
# Warmup Iteration   2: 8.509 ops/ms
# Warmup Iteration   3: 9.176 ops/ms
Iteration   1: 9.309 ops/ms
Iteration   2: 9.322 ops/ms
Iteration   3: 9.421 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.351 ±(99.9%) 1.114 ops/ms [Average]
  (min, avg, max) = (9.309, 9.351, 9.421), stdev = 0.061
  CI (99.9%): [8.236, 10.465] (assumes normal distribution)


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
# Warmup Iteration   1: 3.057 ops/ms
# Warmup Iteration   2: 7.333 ops/ms
# Warmup Iteration   3: 7.661 ops/ms
Iteration   1: 7.765 ops/ms
Iteration   2: 8.019 ops/ms
Iteration   3: 7.890 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.891 ±(99.9%) 2.317 ops/ms [Average]
  (min, avg, max) = (7.765, 7.891, 8.019), stdev = 0.127
  CI (99.9%): [5.574, 10.208] (assumes normal distribution)


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
# Warmup Iteration   1: 10.202 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.886 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.474 ±(99.9%) 0.006 ms/op
Iteration   1: 3.429 ±(99.9%) 0.013 ms/op
Iteration   2: 3.480 ±(99.9%) 0.008 ms/op
Iteration   3: 3.366 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.425 ±(99.9%) 1.043 ms/op [Average]
  (min, avg, max) = (3.366, 3.425, 3.480), stdev = 0.057
  CI (99.9%): [2.382, 4.467] (assumes normal distribution)


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
# Warmup Iteration   1: 9.595 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.686 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.441 ±(99.9%) 0.008 ms/op
Iteration   1: 3.363 ±(99.9%) 0.009 ms/op
Iteration   2: 3.374 ±(99.9%) 0.003 ms/op
Iteration   3: 3.278 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.338 ±(99.9%) 0.958 ms/op [Average]
  (min, avg, max) = (3.278, 3.338, 3.374), stdev = 0.053
  CI (99.9%): [2.380, 4.296] (assumes normal distribution)


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
# Warmup Iteration   1: 7.984 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.768 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.470 ±(99.9%) 0.005 ms/op
Iteration   1: 3.665 ±(99.9%) 0.006 ms/op
Iteration   2: 3.399 ±(99.9%) 0.005 ms/op
Iteration   3: 3.447 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.503 ±(99.9%) 2.584 ms/op [Average]
  (min, avg, max) = (3.399, 3.503, 3.665), stdev = 0.142
  CI (99.9%): [0.919, 6.087] (assumes normal distribution)


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
# Warmup Iteration   1: 9.394 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.305 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.142 ±(99.9%) 0.006 ms/op
Iteration   1: 3.978 ±(99.9%) 0.010 ms/op
Iteration   2: 4.071 ±(99.9%) 0.008 ms/op
Iteration   3: 3.938 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.996 ±(99.9%) 1.245 ms/op [Average]
  (min, avg, max) = (3.938, 3.996, 4.071), stdev = 0.068
  CI (99.9%): [2.751, 5.241] (assumes normal distribution)


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
# Warmup Iteration   1: 9.569 ±(99.9%) 0.113 ms/op
# Warmup Iteration   2: 4.043 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.663 ±(99.9%) 0.010 ms/op
Iteration   1: 3.570 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.959 ms/op
                 createUser·p0.50:   3.494 ms/op
                 createUser·p0.90:   4.104 ms/op
                 createUser·p0.95:   4.506 ms/op
                 createUser·p0.99:   6.095 ms/op
                 createUser·p0.999:  18.200 ms/op
                 createUser·p0.9999: 21.792 ms/op
                 createUser·p1.00:   22.348 ms/op

Iteration   2: 3.548 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.767 ms/op
                 createUser·p0.50:   3.416 ms/op
                 createUser·p0.90:   4.063 ms/op
                 createUser·p0.95:   4.383 ms/op
                 createUser·p0.99:   5.997 ms/op
                 createUser·p0.999:  20.541 ms/op
                 createUser·p0.9999: 25.625 ms/op
                 createUser·p1.00:   26.051 ms/op

Iteration   3: 3.551 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.528 ms/op
                 createUser·p0.50:   3.441 ms/op
                 createUser·p0.90:   3.998 ms/op
                 createUser·p0.95:   4.284 ms/op
                 createUser·p0.99:   5.800 ms/op
                 createUser·p0.999:  17.891 ms/op
                 createUser·p0.9999: 26.113 ms/op
                 createUser·p1.00:   27.394 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 269932
  mean =      3.556 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5109 
    [ 2.500,  5.000) = 258004 
    [ 5.000,  7.500) = 5780 
    [ 7.500, 10.000) = 449 
    [10.000, 12.500) = 195 
    [12.500, 15.000) = 69 
    [15.000, 17.500) = 35 
    [17.500, 20.000) = 72 
    [20.000, 22.500) = 113 
    [22.500, 25.000) = 72 
    [25.000, 27.500) = 34 

  Percentiles, ms/op:
      p(0.0000) =      0.959 ms/op
     p(50.0000) =      3.457 ms/op
     p(90.0000) =      4.047 ms/op
     p(95.0000) =      4.391 ms/op
     p(99.0000) =      5.956 ms/op
     p(99.9000) =     18.057 ms/op
     p(99.9900) =     25.625 ms/op
     p(99.9990) =     27.302 ms/op
     p(99.9999) =     27.394 ms/op
    p(100.0000) =     27.394 ms/op


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
# Warmup Iteration   1: 7.858 ±(99.9%) 0.105 ms/op
# Warmup Iteration   2: 3.647 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.369 ±(99.9%) 0.007 ms/op
Iteration   1: 3.266 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.053 ms/op
                 existUser·p0.50:   3.248 ms/op
                 existUser·p0.90:   3.465 ms/op
                 existUser·p0.95:   3.613 ms/op
                 existUser·p0.99:   4.760 ms/op
                 existUser·p0.999:  10.758 ms/op
                 existUser·p0.9999: 22.265 ms/op
                 existUser·p1.00:   23.364 ms/op

Iteration   2: 3.326 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.315 ms/op
                 existUser·p0.50:   3.224 ms/op
                 existUser·p0.90:   3.645 ms/op
                 existUser·p0.95:   3.838 ms/op
                 existUser·p0.99:   5.661 ms/op
                 existUser·p0.999:  18.391 ms/op
                 existUser·p0.9999: 24.961 ms/op
                 existUser·p1.00:   26.018 ms/op

Iteration   3: 3.343 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.405 ms/op
                 existUser·p0.50:   3.219 ms/op
                 existUser·p0.90:   3.658 ms/op
                 existUser·p0.95:   3.965 ms/op
                 existUser·p0.99:   5.743 ms/op
                 existUser·p0.999:  19.974 ms/op
                 existUser·p0.9999: 23.476 ms/op
                 existUser·p1.00:   23.888 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 289869
  mean =      3.311 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6959 
    [ 2.500,  5.000) = 278617 
    [ 5.000,  7.500) = 3355 
    [ 7.500, 10.000) = 516 
    [10.000, 12.500) = 119 
    [12.500, 15.000) = 15 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 162 
    [22.500, 25.000) = 107 
    [25.000, 27.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      1.053 ms/op
     p(50.0000) =      3.228 ms/op
     p(90.0000) =      3.584 ms/op
     p(95.0000) =      3.801 ms/op
     p(99.0000) =      5.603 ms/op
     p(99.9000) =     12.966 ms/op
     p(99.9900) =     24.380 ms/op
     p(99.9990) =     25.448 ms/op
     p(99.9999) =     26.018 ms/op
    p(100.0000) =     26.018 ms/op


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
# Warmup Iteration   1: 9.699 ±(99.9%) 0.135 ms/op
# Warmup Iteration   2: 3.954 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.526 ±(99.9%) 0.009 ms/op
Iteration   1: 3.491 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.356 ms/op
                 getUser·p0.50:   3.322 ms/op
                 getUser·p0.90:   3.777 ms/op
                 getUser·p0.95:   4.182 ms/op
                 getUser·p0.99:   6.881 ms/op
                 getUser·p0.999:  19.575 ms/op
                 getUser·p0.9999: 24.936 ms/op
                 getUser·p1.00:   26.214 ms/op

Iteration   2: 3.507 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.565 ms/op
                 getUser·p0.50:   3.404 ms/op
                 getUser·p0.90:   3.809 ms/op
                 getUser·p0.95:   3.990 ms/op
                 getUser·p0.99:   6.234 ms/op
                 getUser·p0.999:  10.331 ms/op
                 getUser·p0.9999: 32.698 ms/op
                 getUser·p1.00:   33.620 ms/op

Iteration   3: 3.570 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.282 ms/op
                 getUser·p0.50:   3.408 ms/op
                 getUser·p0.90:   4.116 ms/op
                 getUser·p0.95:   4.850 ms/op
                 getUser·p0.99:   6.038 ms/op
                 getUser·p0.999:  23.886 ms/op
                 getUser·p0.9999: 26.644 ms/op
                 getUser·p1.00:   28.377 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 272339
  mean =      3.522 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2223 
    [ 2.500,  5.000) = 260771 
    [ 5.000,  7.500) = 8091 
    [ 7.500, 10.000) = 822 
    [10.000, 12.500) = 146 
    [12.500, 15.000) = 5 
    [15.000, 17.500) = 6 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 41 
    [22.500, 25.000) = 108 
    [25.000, 27.500) = 60 
    [27.500, 30.000) = 2 
    [30.000, 32.500) = 19 
    [32.500, 35.000) = 13 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.282 ms/op
     p(50.0000) =      3.375 ms/op
     p(90.0000) =      3.879 ms/op
     p(95.0000) =      4.440 ms/op
     p(99.0000) =      6.455 ms/op
     p(99.9000) =     18.389 ms/op
     p(99.9900) =     30.927 ms/op
     p(99.9990) =     33.334 ms/op
     p(99.9999) =     33.620 ms/op
    p(100.0000) =     33.620 ms/op


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
# Warmup Iteration   1: 11.909 ±(99.9%) 0.154 ms/op
# Warmup Iteration   2: 4.725 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.139 ±(99.9%) 0.013 ms/op
Iteration   1: 4.051 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.249 ms/op
                 listUser·p0.50:   3.916 ms/op
                 listUser·p0.90:   4.375 ms/op
                 listUser·p0.95:   4.694 ms/op
                 listUser·p0.99:   7.733 ms/op
                 listUser·p0.999:  20.316 ms/op
                 listUser·p0.9999: 25.763 ms/op
                 listUser·p1.00:   26.903 ms/op

Iteration   2: 3.989 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.347 ms/op
                 listUser·p0.50:   3.858 ms/op
                 listUser·p0.90:   4.366 ms/op
                 listUser·p0.95:   4.538 ms/op
                 listUser·p0.99:   6.832 ms/op
                 listUser·p0.999:  14.156 ms/op
                 listUser·p0.9999: 16.678 ms/op
                 listUser·p1.00:   17.203 ms/op

Iteration   3: 3.955 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.101 ms/op
                 listUser·p0.50:   3.846 ms/op
                 listUser·p0.90:   4.227 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   6.971 ms/op
                 listUser·p0.999:  13.681 ms/op
                 listUser·p0.9999: 15.070 ms/op
                 listUser·p1.00:   15.139 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 239882
  mean =      3.998 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12 
    [ 2.500,  5.000) = 233441 
    [ 5.000,  7.500) = 4503 
    [ 7.500, 10.000) = 1222 
    [10.000, 12.500) = 199 
    [12.500, 15.000) = 294 
    [15.000, 17.500) = 115 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 50 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 20 

  Percentiles, ms/op:
      p(0.0000) =      2.101 ms/op
     p(50.0000) =      3.871 ms/op
     p(90.0000) =      4.317 ms/op
     p(95.0000) =      4.538 ms/op
     p(99.0000) =      7.152 ms/op
     p(99.9000) =     14.467 ms/op
     p(99.9900) =     24.805 ms/op
     p(99.9990) =     26.739 ms/op
     p(99.9999) =     26.903 ms/op
    p(100.0000) =     26.903 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.232 ± 2.969  ops/ms
ClientPb.existUser                       thrpt       3   9.584 ± 3.432  ops/ms
ClientPb.getUser                         thrpt       3   9.351 ± 1.114  ops/ms
ClientPb.listUser                        thrpt       3   7.891 ± 2.317  ops/ms
ClientPb.createUser                       avgt       3   3.425 ± 1.043   ms/op
ClientPb.existUser                        avgt       3   3.338 ± 0.958   ms/op
ClientPb.getUser                          avgt       3   3.503 ± 2.584   ms/op
ClientPb.listUser                         avgt       3   3.996 ± 1.245   ms/op
ClientPb.createUser                     sample  269932   3.556 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.959           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.457           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.047           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.391           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.956           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.057           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.625           ms/op
ClientPb.createUser:createUser·p1.00    sample          27.394           ms/op
ClientPb.existUser                      sample  289869   3.311 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.053           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.228           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.584           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.801           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.603           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.966           ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.380           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.018           ms/op
ClientPb.getUser                        sample  272339   3.522 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.282           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.375           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.879           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.440           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.455           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.389           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.927           ms/op
ClientPb.getUser:getUser·p1.00          sample          33.620           ms/op
ClientPb.listUser                       sample  239882   3.998 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.101           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.871           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.317           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.538           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.152           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.467           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.805           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.903           ms/op
