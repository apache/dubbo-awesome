# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 5.087 ops/ms
# Warmup Iteration   2: 12.221 ops/ms
# Warmup Iteration   3: 12.494 ops/ms
Iteration   1: 12.532 ops/ms
Iteration   2: 12.684 ops/ms
Iteration   3: 12.680 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.632 ±(99.9%) 1.576 ops/ms [Average]
  (min, avg, max) = (12.532, 12.632, 12.684), stdev = 0.086
  CI (99.9%): [11.056, 14.208] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 8.262 ops/ms
# Warmup Iteration   2: 13.075 ops/ms
# Warmup Iteration   3: 12.967 ops/ms
Iteration   1: 12.997 ops/ms
Iteration   2: 12.997 ops/ms
Iteration   3: 12.837 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.944 ±(99.9%) 1.682 ops/ms [Average]
  (min, avg, max) = (12.837, 12.944, 12.997), stdev = 0.092
  CI (99.9%): [11.262, 14.626] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.757 ops/ms
# Warmup Iteration   2: 12.209 ops/ms
# Warmup Iteration   3: 12.762 ops/ms
Iteration   1: 12.770 ops/ms
Iteration   2: 12.595 ops/ms
Iteration   3: 12.641 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.669 ±(99.9%) 1.656 ops/ms [Average]
  (min, avg, max) = (12.595, 12.669, 12.770), stdev = 0.091
  CI (99.9%): [11.013, 14.325] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 6.661 ops/ms
# Warmup Iteration   2: 10.489 ops/ms
# Warmup Iteration   3: 10.467 ops/ms
Iteration   1: 10.491 ops/ms
Iteration   2: 10.547 ops/ms
Iteration   3: 10.537 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.525 ±(99.9%) 0.549 ops/ms [Average]
  (min, avg, max) = (10.491, 10.525, 10.547), stdev = 0.030
  CI (99.9%): [9.976, 11.074] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:39
# Fork: 1 of 1
# Warmup Iteration   1: 4.115 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 2.678 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.578 ±(99.9%) 0.003 ms/op
Iteration   1: 2.618 ±(99.9%) 0.004 ms/op
Iteration   2: 2.579 ±(99.9%) 0.005 ms/op
Iteration   3: 2.602 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.600 ±(99.9%) 0.362 ms/op [Average]
  (min, avg, max) = (2.579, 2.600, 2.618), stdev = 0.020
  CI (99.9%): [2.238, 2.961] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:34
# Fork: 1 of 1
# Warmup Iteration   1: 3.698 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 2.479 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.506 ±(99.9%) 0.004 ms/op
Iteration   1: 2.515 ±(99.9%) 0.003 ms/op
Iteration   2: 2.530 ±(99.9%) 0.004 ms/op
Iteration   3: 2.505 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.517 ±(99.9%) 0.228 ms/op [Average]
  (min, avg, max) = (2.505, 2.517, 2.530), stdev = 0.012
  CI (99.9%): [2.289, 2.745] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:29
# Fork: 1 of 1
# Warmup Iteration   1: 3.947 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.562 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.560 ±(99.9%) 0.004 ms/op
Iteration   1: 2.549 ±(99.9%) 0.004 ms/op
Iteration   2: 2.545 ±(99.9%) 0.003 ms/op
Iteration   3: 2.542 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.545 ±(99.9%) 0.059 ms/op [Average]
  (min, avg, max) = (2.542, 2.545, 2.549), stdev = 0.003
  CI (99.9%): [2.487, 2.604] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 4.806 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.007 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.033 ±(99.9%) 0.006 ms/op
Iteration   1: 2.997 ±(99.9%) 0.006 ms/op
Iteration   2: 2.984 ±(99.9%) 0.005 ms/op
Iteration   3: 2.952 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.978 ±(99.9%) 0.426 ms/op [Average]
  (min, avg, max) = (2.952, 2.978, 2.997), stdev = 0.023
  CI (99.9%): [2.552, 3.403] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:19
# Fork: 1 of 1
# Warmup Iteration   1: 4.198 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.725 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.566 ±(99.9%) 0.006 ms/op
Iteration   1: 2.588 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.854 ms/op
                 createUser·p0.50:   2.658 ms/op
                 createUser·p0.90:   3.138 ms/op
                 createUser·p0.95:   3.248 ms/op
                 createUser·p0.99:   3.805 ms/op
                 createUser·p0.999:  11.567 ms/op
                 createUser·p0.9999: 13.571 ms/op
                 createUser·p1.00:   14.205 ms/op

Iteration   2: 2.563 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.124 ms/op
                 createUser·p0.50:   2.658 ms/op
                 createUser·p0.90:   3.105 ms/op
                 createUser·p0.95:   3.199 ms/op
                 createUser·p0.99:   3.682 ms/op
                 createUser·p0.999:  9.720 ms/op
                 createUser·p0.9999: 12.404 ms/op
                 createUser·p1.00:   12.730 ms/op

Iteration   3: 2.602 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.017 ms/op
                 createUser·p0.50:   2.654 ms/op
                 createUser·p0.90:   3.162 ms/op
                 createUser·p0.95:   3.301 ms/op
                 createUser·p0.99:   4.223 ms/op
                 createUser·p0.999:  9.191 ms/op
                 createUser·p0.9999: 12.239 ms/op
                 createUser·p1.00:   13.304 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 371145
  mean =      2.584 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 33 
    [ 1.250,  2.500) = 177026 
    [ 2.500,  3.750) = 189442 
    [ 3.750,  5.000) = 3663 
    [ 5.000,  6.250) = 472 
    [ 6.250,  7.500) = 54 
    [ 7.500,  8.750) = 58 
    [ 8.750, 10.000) = 98 
    [10.000, 11.250) = 93 
    [11.250, 12.500) = 99 
    [12.500, 13.750) = 103 
    [13.750, 15.000) = 4 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.854 ms/op
     p(50.0000) =      2.654 ms/op
     p(90.0000) =      3.133 ms/op
     p(95.0000) =      3.248 ms/op
     p(99.0000) =      3.891 ms/op
     p(99.9000) =      9.238 ms/op
     p(99.9900) =     13.304 ms/op
     p(99.9990) =     13.772 ms/op
     p(99.9999) =     14.205 ms/op
    p(100.0000) =     14.205 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.508 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 2.489 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.433 ±(99.9%) 0.005 ms/op
Iteration   1: 2.436 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.014 ms/op
                 existUser·p0.50:   2.523 ms/op
                 existUser·p0.90:   2.953 ms/op
                 existUser·p0.95:   3.056 ms/op
                 existUser·p0.99:   3.506 ms/op
                 existUser·p0.999:  5.020 ms/op
                 existUser·p0.9999: 13.769 ms/op
                 existUser·p1.00:   14.074 ms/op

Iteration   2: 2.476 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.954 ms/op
                 existUser·p0.50:   2.527 ms/op
                 existUser·p0.90:   2.998 ms/op
                 existUser·p0.95:   3.097 ms/op
                 existUser·p0.99:   3.600 ms/op
                 existUser·p0.999:  9.485 ms/op
                 existUser·p0.9999: 12.718 ms/op
                 existUser·p1.00:   14.238 ms/op

Iteration   3: 2.478 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.959 ms/op
                 existUser·p0.50:   2.531 ms/op
                 existUser·p0.90:   3.019 ms/op
                 existUser·p0.95:   3.125 ms/op
                 existUser·p0.99:   3.731 ms/op
                 existUser·p0.999:  8.995 ms/op
                 existUser·p0.9999: 11.993 ms/op
                 existUser·p1.00:   12.239 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 389307
  mean =      2.463 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 37 
    [ 1.250,  2.500) = 192720 
    [ 2.500,  3.750) = 193461 
    [ 3.750,  5.000) = 2414 
    [ 5.000,  6.250) = 219 
    [ 6.250,  7.500) = 27 
    [ 7.500,  8.750) = 22 
    [ 8.750, 10.000) = 146 
    [10.000, 11.250) = 91 
    [11.250, 12.500) = 92 
    [12.500, 13.750) = 61 
    [13.750, 15.000) = 17 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.954 ms/op
     p(50.0000) =      2.527 ms/op
     p(90.0000) =      2.994 ms/op
     p(95.0000) =      3.092 ms/op
     p(99.0000) =      3.613 ms/op
     p(99.9000) =      8.929 ms/op
     p(99.9900) =     13.127 ms/op
     p(99.9990) =     13.933 ms/op
     p(99.9999) =     14.238 ms/op
    p(100.0000) =     14.238 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 4.042 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.576 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.526 ±(99.9%) 0.005 ms/op
Iteration   1: 2.491 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.553 ms/op
                 getUser·p0.50:   2.519 ms/op
                 getUser·p0.90:   3.035 ms/op
                 getUser·p0.95:   3.146 ms/op
                 getUser·p0.99:   3.654 ms/op
                 getUser·p0.999:  9.333 ms/op
                 getUser·p0.9999: 13.599 ms/op
                 getUser·p1.00:   14.434 ms/op

Iteration   2: 2.544 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.889 ms/op
                 getUser·p0.50:   2.576 ms/op
                 getUser·p0.90:   3.088 ms/op
                 getUser·p0.95:   3.269 ms/op
                 getUser·p0.99:   4.801 ms/op
                 getUser·p0.999:  9.421 ms/op
                 getUser·p0.9999: 12.836 ms/op
                 getUser·p1.00:   13.156 ms/op

Iteration   3: 2.496 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.055 ms/op
                 getUser·p0.50:   2.531 ms/op
                 getUser·p0.90:   3.047 ms/op
                 getUser·p0.95:   3.178 ms/op
                 getUser·p0.99:   3.740 ms/op
                 getUser·p0.999:  8.031 ms/op
                 getUser·p0.9999: 10.751 ms/op
                 getUser·p1.00:   12.141 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 382113
  mean =      2.510 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 84 
    [ 1.250,  2.500) = 187514 
    [ 2.500,  3.750) = 189482 
    [ 3.750,  5.000) = 3574 
    [ 5.000,  6.250) = 1026 
    [ 6.250,  7.500) = 49 
    [ 7.500,  8.750) = 11 
    [ 8.750, 10.000) = 123 
    [10.000, 11.250) = 90 
    [11.250, 12.500) = 50 
    [12.500, 13.750) = 102 
    [13.750, 15.000) = 8 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.553 ms/op
     p(50.0000) =      2.548 ms/op
     p(90.0000) =      3.056 ms/op
     p(95.0000) =      3.191 ms/op
     p(99.0000) =      3.944 ms/op
     p(99.9000) =      8.155 ms/op
     p(99.9900) =     13.333 ms/op
     p(99.9990) =     14.090 ms/op
     p(99.9999) =     14.434 ms/op
    p(100.0000) =     14.434 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.617 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 3.053 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.005 ±(99.9%) 0.008 ms/op
Iteration   1: 3.057 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.825 ms/op
                 listUser·p0.50:   2.982 ms/op
                 listUser·p0.90:   4.010 ms/op
                 listUser·p0.95:   4.571 ms/op
                 listUser·p0.99:   5.669 ms/op
                 listUser·p0.999:  9.139 ms/op
                 listUser·p0.9999: 11.160 ms/op
                 listUser·p1.00:   12.747 ms/op

Iteration   2: 3.008 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.821 ms/op
                 listUser·p0.50:   2.945 ms/op
                 listUser·p0.90:   3.854 ms/op
                 listUser·p0.95:   4.334 ms/op
                 listUser·p0.99:   5.562 ms/op
                 listUser·p0.999:  9.503 ms/op
                 listUser·p0.9999: 11.786 ms/op
                 listUser·p1.00:   13.500 ms/op

Iteration   3: 3.025 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.792 ms/op
                 listUser·p0.50:   2.961 ms/op
                 listUser·p0.90:   3.908 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   5.636 ms/op
                 listUser·p0.999:  9.508 ms/op
                 listUser·p0.9999: 12.169 ms/op
                 listUser·p1.00:   13.533 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 316546
  mean =      3.030 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 152 
    [ 1.250,  2.500) = 88530 
    [ 2.500,  3.750) = 187024 
    [ 3.750,  5.000) = 32766 
    [ 5.000,  6.250) = 6791 
    [ 6.250,  7.500) = 645 
    [ 7.500,  8.750) = 189 
    [ 8.750, 10.000) = 244 
    [10.000, 11.250) = 146 
    [11.250, 12.500) = 48 
    [12.500, 13.750) = 11 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.792 ms/op
     p(50.0000) =      2.966 ms/op
     p(90.0000) =      3.924 ms/op
     p(95.0000) =      4.432 ms/op
     p(99.0000) =      5.620 ms/op
     p(99.9000) =      9.378 ms/op
     p(99.9900) =     11.868 ms/op
     p(99.9990) =     13.479 ms/op
     p(99.9999) =     13.533 ms/op
    p(100.0000) =     13.533 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.632 ± 1.576  ops/ms
ClientPb.existUser                       thrpt       3  12.944 ± 1.682  ops/ms
ClientPb.getUser                         thrpt       3  12.669 ± 1.656  ops/ms
ClientPb.listUser                        thrpt       3  10.525 ± 0.549  ops/ms
ClientPb.createUser                       avgt       3   2.600 ± 0.362   ms/op
ClientPb.existUser                        avgt       3   2.517 ± 0.228   ms/op
ClientPb.getUser                          avgt       3   2.545 ± 0.059   ms/op
ClientPb.listUser                         avgt       3   2.978 ± 0.426   ms/op
ClientPb.createUser                     sample  371145   2.584 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.854           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.654           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.133           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.248           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.891           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.238           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.304           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.205           ms/op
ClientPb.existUser                      sample  389307   2.463 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.954           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.527           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.994           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.092           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.613           ms/op
ClientPb.existUser:existUser·p0.999     sample           8.929           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.127           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.238           ms/op
ClientPb.getUser                        sample  382113   2.510 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.553           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.548           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.056           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.191           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.944           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.155           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.333           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.434           ms/op
ClientPb.listUser                       sample  316546   3.030 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.792           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.966           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.924           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.432           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.620           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.378           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.868           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.533           ms/op
