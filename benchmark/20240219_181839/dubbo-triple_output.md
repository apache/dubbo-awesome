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
# Warmup Iteration   1: 4.980 ops/ms
# Warmup Iteration   2: 12.080 ops/ms
# Warmup Iteration   3: 12.052 ops/ms
Iteration   1: 12.367 ops/ms
Iteration   2: 12.390 ops/ms
Iteration   3: 12.589 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.448 ±(99.9%) 2.227 ops/ms [Average]
  (min, avg, max) = (12.367, 12.448, 12.589), stdev = 0.122
  CI (99.9%): [10.222, 14.675] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:52
# Fork: 1 of 1
# Warmup Iteration   1: 8.374 ops/ms
# Warmup Iteration   2: 13.097 ops/ms
# Warmup Iteration   3: 13.072 ops/ms
Iteration   1: 13.161 ops/ms
Iteration   2: 13.156 ops/ms
Iteration   3: 13.190 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.169 ±(99.9%) 0.334 ops/ms [Average]
  (min, avg, max) = (13.156, 13.169, 13.190), stdev = 0.018
  CI (99.9%): [12.835, 13.503] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.795 ops/ms
# Warmup Iteration   2: 12.371 ops/ms
# Warmup Iteration   3: 12.650 ops/ms
Iteration   1: 12.580 ops/ms
Iteration   2: 12.710 ops/ms
Iteration   3: 12.607 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.632 ±(99.9%) 1.251 ops/ms [Average]
  (min, avg, max) = (12.580, 12.632, 12.710), stdev = 0.069
  CI (99.9%): [11.381, 13.884] (assumes normal distribution)


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
# Warmup Iteration   1: 6.601 ops/ms
# Warmup Iteration   2: 10.622 ops/ms
# Warmup Iteration   3: 10.631 ops/ms
Iteration   1: 10.693 ops/ms
Iteration   2: 10.791 ops/ms
Iteration   3: 10.814 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.766 ±(99.9%) 1.177 ops/ms [Average]
  (min, avg, max) = (10.693, 10.766, 10.814), stdev = 0.064
  CI (99.9%): [9.589, 11.942] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.898 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.596 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.522 ±(99.9%) 0.003 ms/op
Iteration   1: 2.537 ±(99.9%) 0.005 ms/op
Iteration   2: 2.509 ±(99.9%) 0.003 ms/op
Iteration   3: 2.513 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.520 ±(99.9%) 0.282 ms/op [Average]
  (min, avg, max) = (2.509, 2.520, 2.537), stdev = 0.015
  CI (99.9%): [2.237, 2.802] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.740 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.500 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.481 ±(99.9%) 0.004 ms/op
Iteration   1: 2.492 ±(99.9%) 0.004 ms/op
Iteration   2: 2.467 ±(99.9%) 0.004 ms/op
Iteration   3: 2.470 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.477 ±(99.9%) 0.252 ms/op [Average]
  (min, avg, max) = (2.467, 2.477, 2.492), stdev = 0.014
  CI (99.9%): [2.224, 2.729] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.866 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.595 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.541 ±(99.9%) 0.003 ms/op
Iteration   1: 2.544 ±(99.9%) 0.004 ms/op
Iteration   2: 2.514 ±(99.9%) 0.004 ms/op
Iteration   3: 2.529 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.529 ±(99.9%) 0.272 ms/op [Average]
  (min, avg, max) = (2.514, 2.529, 2.544), stdev = 0.015
  CI (99.9%): [2.257, 2.801] (assumes normal distribution)


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
# Warmup Iteration   1: 4.555 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.094 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.043 ±(99.9%) 0.005 ms/op
Iteration   1: 3.017 ±(99.9%) 0.005 ms/op
Iteration   2: 3.009 ±(99.9%) 0.006 ms/op
Iteration   3: 3.012 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.013 ±(99.9%) 0.070 ms/op [Average]
  (min, avg, max) = (3.009, 3.013, 3.017), stdev = 0.004
  CI (99.9%): [2.942, 3.083] (assumes normal distribution)


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
# Warmup Iteration   1: 4.029 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.614 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.526 ±(99.9%) 0.005 ms/op
Iteration   1: 2.509 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.883 ms/op
                 createUser·p0.50:   2.585 ms/op
                 createUser·p0.90:   3.047 ms/op
                 createUser·p0.95:   3.154 ms/op
                 createUser·p0.99:   3.629 ms/op
                 createUser·p0.999:  10.884 ms/op
                 createUser·p0.9999: 13.554 ms/op
                 createUser·p1.00:   14.287 ms/op

Iteration   2: 2.504 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.051 ms/op
                 createUser·p0.50:   2.613 ms/op
                 createUser·p0.90:   3.027 ms/op
                 createUser·p0.95:   3.129 ms/op
                 createUser·p0.99:   3.719 ms/op
                 createUser·p0.999:  9.355 ms/op
                 createUser·p0.9999: 11.698 ms/op
                 createUser·p1.00:   12.354 ms/op

Iteration   3: 2.544 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.874 ms/op
                 createUser·p0.50:   2.593 ms/op
                 createUser·p0.90:   3.101 ms/op
                 createUser·p0.95:   3.252 ms/op
                 createUser·p0.99:   4.006 ms/op
                 createUser·p0.999:  8.761 ms/op
                 createUser·p0.9999: 11.676 ms/op
                 createUser·p1.00:   12.534 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 380660
  mean =      2.519 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 29 
    [ 1.250,  2.500) = 183095 
    [ 2.500,  3.750) = 193441 
    [ 3.750,  5.000) = 3162 
    [ 5.000,  6.250) = 413 
    [ 6.250,  7.500) = 98 
    [ 7.500,  8.750) = 40 
    [ 8.750, 10.000) = 55 
    [10.000, 11.250) = 134 
    [11.250, 12.500) = 140 
    [12.500, 13.750) = 44 
    [13.750, 15.000) = 9 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.874 ms/op
     p(50.0000) =      2.597 ms/op
     p(90.0000) =      3.056 ms/op
     p(95.0000) =      3.178 ms/op
     p(99.0000) =      3.789 ms/op
     p(99.9000) =      8.940 ms/op
     p(99.9900) =     12.714 ms/op
     p(99.9990) =     13.828 ms/op
     p(99.9999) =     14.287 ms/op
    p(100.0000) =     14.287 ms/op


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
# Warmup Iteration   1: 3.843 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.458 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.428 ±(99.9%) 0.005 ms/op
Iteration   1: 2.437 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.908 ms/op
                 existUser·p0.50:   2.474 ms/op
                 existUser·p0.90:   2.966 ms/op
                 existUser·p0.95:   3.080 ms/op
                 existUser·p0.99:   3.670 ms/op
                 existUser·p0.999:  6.600 ms/op
                 existUser·p0.9999: 13.386 ms/op
                 existUser·p1.00:   14.074 ms/op

Iteration   2: 2.441 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.889 ms/op
                 existUser·p0.50:   2.572 ms/op
                 existUser·p0.90:   2.953 ms/op
                 existUser·p0.95:   3.052 ms/op
                 existUser·p0.99:   3.592 ms/op
                 existUser·p0.999:  5.399 ms/op
                 existUser·p0.9999: 13.432 ms/op
                 existUser·p1.00:   13.943 ms/op

Iteration   3: 2.432 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.026 ms/op
                 existUser·p0.50:   2.499 ms/op
                 existUser·p0.90:   2.949 ms/op
                 existUser·p0.95:   3.056 ms/op
                 existUser·p0.99:   3.686 ms/op
                 existUser·p0.999:  8.112 ms/op
                 existUser·p0.9999: 14.998 ms/op
                 existUser·p1.00:   15.827 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 393669
  mean =      2.437 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 61 
    [ 1.250,  2.500) = 195881 
    [ 2.500,  3.750) = 194386 
    [ 3.750,  5.000) = 2623 
    [ 5.000,  6.250) = 329 
    [ 6.250,  7.500) = 31 
    [ 7.500,  8.750) = 29 
    [ 8.750, 10.000) = 31 
    [10.000, 11.250) = 74 
    [11.250, 12.500) = 70 
    [12.500, 13.750) = 113 
    [13.750, 15.000) = 28 
    [15.000, 16.250) = 13 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.889 ms/op
     p(50.0000) =      2.511 ms/op
     p(90.0000) =      2.957 ms/op
     p(95.0000) =      3.060 ms/op
     p(99.0000) =      3.654 ms/op
     p(99.9000) =      6.051 ms/op
     p(99.9900) =     13.816 ms/op
     p(99.9990) =     15.537 ms/op
     p(99.9999) =     15.827 ms/op
    p(100.0000) =     15.827 ms/op


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
# Warmup Iteration   1: 4.010 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.625 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.536 ±(99.9%) 0.006 ms/op
Iteration   1: 2.534 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.891 ms/op
                 getUser·p0.50:   2.552 ms/op
                 getUser·p0.90:   3.088 ms/op
                 getUser·p0.95:   3.215 ms/op
                 getUser·p0.99:   3.748 ms/op
                 getUser·p0.999:  11.397 ms/op
                 getUser·p0.9999: 14.522 ms/op
                 getUser·p1.00:   15.155 ms/op

Iteration   2: 2.573 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.883 ms/op
                 getUser·p0.50:   2.609 ms/op
                 getUser·p0.90:   3.125 ms/op
                 getUser·p0.95:   3.256 ms/op
                 getUser·p0.99:   4.202 ms/op
                 getUser·p0.999:  10.822 ms/op
                 getUser·p0.9999: 14.444 ms/op
                 getUser·p1.00:   15.466 ms/op

Iteration   3: 2.540 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.944 ms/op
                 getUser·p0.50:   2.585 ms/op
                 getUser·p0.90:   3.092 ms/op
                 getUser·p0.95:   3.228 ms/op
                 getUser·p0.99:   3.969 ms/op
                 getUser·p0.999:  8.768 ms/op
                 getUser·p0.9999: 11.132 ms/op
                 getUser·p1.00:   11.600 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 376291
  mean =      2.549 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 55 
    [ 1.250,  2.500) = 182723 
    [ 2.500,  3.750) = 188400 
    [ 3.750,  5.000) = 4062 
    [ 5.000,  6.250) = 524 
    [ 6.250,  7.500) = 116 
    [ 7.500,  8.750) = 22 
    [ 8.750, 10.000) = 88 
    [10.000, 11.250) = 55 
    [11.250, 12.500) = 97 
    [12.500, 13.750) = 84 
    [13.750, 15.000) = 61 
    [15.000, 16.250) = 4 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.883 ms/op
     p(50.0000) =      2.580 ms/op
     p(90.0000) =      3.105 ms/op
     p(95.0000) =      3.232 ms/op
     p(99.0000) =      3.961 ms/op
     p(99.9000) =      8.990 ms/op
     p(99.9900) =     14.244 ms/op
     p(99.9990) =     15.163 ms/op
     p(99.9999) =     15.466 ms/op
    p(100.0000) =     15.466 ms/op


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
# Warmup Iteration   1: 4.713 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.172 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.106 ±(99.9%) 0.009 ms/op
Iteration   1: 3.078 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.627 ms/op
                 listUser·p0.50:   3.019 ms/op
                 listUser·p0.90:   3.973 ms/op
                 listUser·p0.95:   4.481 ms/op
                 listUser·p0.99:   5.661 ms/op
                 listUser·p0.999:  9.044 ms/op
                 listUser·p0.9999: 11.135 ms/op
                 listUser·p1.00:   11.911 ms/op

Iteration   2: 3.072 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.843 ms/op
                 listUser·p0.50:   3.006 ms/op
                 listUser·p0.90:   3.969 ms/op
                 listUser·p0.95:   4.465 ms/op
                 listUser·p0.99:   5.702 ms/op
                 listUser·p0.999:  9.732 ms/op
                 listUser·p0.9999: 11.056 ms/op
                 listUser·p1.00:   11.534 ms/op

Iteration   3: 3.046 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.984 ms/op
                 listUser·p0.50:   2.978 ms/op
                 listUser·p0.90:   3.965 ms/op
                 listUser·p0.95:   4.481 ms/op
                 listUser·p0.99:   5.669 ms/op
                 listUser·p0.999:  9.355 ms/op
                 listUser·p0.9999: 11.051 ms/op
                 listUser·p1.00:   11.633 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 312869
  mean =      3.066 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 118 
    [ 1.250,  2.500) = 82357 
    [ 2.500,  3.750) = 187499 
    [ 3.750,  5.000) = 34594 
    [ 5.000,  6.250) = 6870 
    [ 6.250,  7.500) = 784 
    [ 7.500,  8.750) = 190 
    [ 8.750, 10.000) = 269 
    [10.000, 11.250) = 172 
    [11.250, 12.500) = 16 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.627 ms/op
     p(50.0000) =      3.002 ms/op
     p(90.0000) =      3.969 ms/op
     p(95.0000) =      4.473 ms/op
     p(99.0000) =      5.677 ms/op
     p(99.9000) =      9.355 ms/op
     p(99.9900) =     11.071 ms/op
     p(99.9990) =     11.759 ms/op
     p(99.9999) =     11.911 ms/op
    p(100.0000) =     11.911 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.448 ± 2.227  ops/ms
ClientPb.existUser                       thrpt       3  13.169 ± 0.334  ops/ms
ClientPb.getUser                         thrpt       3  12.632 ± 1.251  ops/ms
ClientPb.listUser                        thrpt       3  10.766 ± 1.177  ops/ms
ClientPb.createUser                       avgt       3   2.520 ± 0.282   ms/op
ClientPb.existUser                        avgt       3   2.477 ± 0.252   ms/op
ClientPb.getUser                          avgt       3   2.529 ± 0.272   ms/op
ClientPb.listUser                         avgt       3   3.013 ± 0.070   ms/op
ClientPb.createUser                     sample  380660   2.519 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.874           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.597           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.056           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.178           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.789           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.940           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.714           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.287           ms/op
ClientPb.existUser                      sample  393669   2.437 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.889           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.511           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.957           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.060           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.654           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.051           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.816           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.827           ms/op
ClientPb.getUser                        sample  376291   2.549 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.883           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.580           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.105           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.232           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.961           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.990           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.244           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.466           ms/op
ClientPb.listUser                       sample  312869   3.066 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.627           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.002           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.969           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.473           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.677           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.355           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.071           ms/op
ClientPb.listUser:listUser·p1.00        sample          11.911           ms/op
