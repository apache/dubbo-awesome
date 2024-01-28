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
# Warmup Iteration   1: 5.040 ops/ms
# Warmup Iteration   2: 12.364 ops/ms
# Warmup Iteration   3: 12.538 ops/ms
Iteration   1: 12.836 ops/ms
Iteration   2: 12.792 ops/ms
Iteration   3: 12.905 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.844 ±(99.9%) 1.033 ops/ms [Average]
  (min, avg, max) = (12.792, 12.844, 12.905), stdev = 0.057
  CI (99.9%): [11.811, 13.878] (assumes normal distribution)


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
# Warmup Iteration   1: 8.380 ops/ms
# Warmup Iteration   2: 13.263 ops/ms
# Warmup Iteration   3: 13.121 ops/ms
Iteration   1: 13.207 ops/ms
Iteration   2: 12.936 ops/ms
Iteration   3: 13.101 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.081 ±(99.9%) 2.492 ops/ms [Average]
  (min, avg, max) = (12.936, 13.081, 13.207), stdev = 0.137
  CI (99.9%): [10.589, 15.573] (assumes normal distribution)


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
# Warmup Iteration   1: 7.648 ops/ms
# Warmup Iteration   2: 12.483 ops/ms
# Warmup Iteration   3: 12.970 ops/ms
Iteration   1: 12.998 ops/ms
Iteration   2: 13.154 ops/ms
Iteration   3: 13.028 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.060 ±(99.9%) 1.512 ops/ms [Average]
  (min, avg, max) = (12.998, 13.060, 13.154), stdev = 0.083
  CI (99.9%): [11.548, 14.572] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.505 ops/ms
# Warmup Iteration   2: 10.412 ops/ms
# Warmup Iteration   3: 10.579 ops/ms
Iteration   1: 10.518 ops/ms
Iteration   2: 10.643 ops/ms
Iteration   3: 10.679 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.613 ±(99.9%) 1.541 ops/ms [Average]
  (min, avg, max) = (10.518, 10.613, 10.679), stdev = 0.084
  CI (99.9%): [9.072, 12.155] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:37
# Fork: 1 of 1
# Warmup Iteration   1: 3.980 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.519 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.463 ±(99.9%) 0.004 ms/op
Iteration   1: 2.486 ±(99.9%) 0.004 ms/op
Iteration   2: 2.503 ±(99.9%) 0.004 ms/op
Iteration   3: 2.470 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.486 ±(99.9%) 0.300 ms/op [Average]
  (min, avg, max) = (2.470, 2.486, 2.503), stdev = 0.016
  CI (99.9%): [2.186, 2.786] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:32
# Fork: 1 of 1
# Warmup Iteration   1: 3.847 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.502 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.518 ±(99.9%) 0.004 ms/op
Iteration   1: 2.502 ±(99.9%) 0.004 ms/op
Iteration   2: 2.502 ±(99.9%) 0.003 ms/op
Iteration   3: 2.493 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.499 ±(99.9%) 0.092 ms/op [Average]
  (min, avg, max) = (2.493, 2.499, 2.502), stdev = 0.005
  CI (99.9%): [2.408, 2.591] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.919 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.524 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.492 ±(99.9%) 0.004 ms/op
Iteration   1: 2.462 ±(99.9%) 0.004 ms/op
Iteration   2: 2.462 ±(99.9%) 0.004 ms/op
Iteration   3: 2.469 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.464 ±(99.9%) 0.081 ms/op [Average]
  (min, avg, max) = (2.462, 2.464, 2.469), stdev = 0.004
  CI (99.9%): [2.383, 2.545] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:23
# Fork: 1 of 1
# Warmup Iteration   1: 4.776 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.084 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.025 ±(99.9%) 0.006 ms/op
Iteration   1: 2.999 ±(99.9%) 0.005 ms/op
Iteration   2: 2.989 ±(99.9%) 0.006 ms/op
Iteration   3: 3.017 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.002 ±(99.9%) 0.256 ms/op [Average]
  (min, avg, max) = (2.989, 3.002, 3.017), stdev = 0.014
  CI (99.9%): [2.746, 3.257] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:18
# Fork: 1 of 1
# Warmup Iteration   1: 4.046 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.626 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.507 ±(99.9%) 0.006 ms/op
Iteration   1: 2.498 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.949 ms/op
                 createUser·p0.50:   2.568 ms/op
                 createUser·p0.90:   3.023 ms/op
                 createUser·p0.95:   3.121 ms/op
                 createUser·p0.99:   3.617 ms/op
                 createUser·p0.999:  11.420 ms/op
                 createUser·p0.9999: 13.418 ms/op
                 createUser·p1.00:   14.287 ms/op

Iteration   2: 2.486 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.990 ms/op
                 createUser·p0.50:   2.572 ms/op
                 createUser·p0.90:   3.015 ms/op
                 createUser·p0.95:   3.113 ms/op
                 createUser·p0.99:   3.580 ms/op
                 createUser·p0.999:  8.614 ms/op
                 createUser·p0.9999: 11.071 ms/op
                 createUser·p1.00:   11.780 ms/op

Iteration   3: 2.510 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.984 ms/op
                 createUser·p0.50:   2.544 ms/op
                 createUser·p0.90:   3.052 ms/op
                 createUser·p0.95:   3.162 ms/op
                 createUser·p0.99:   3.695 ms/op
                 createUser·p0.999:  9.262 ms/op
                 createUser·p0.9999: 11.396 ms/op
                 createUser·p1.00:   12.501 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 383903
  mean =      2.498 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 57 
    [ 1.250,  2.500) = 187593 
    [ 2.500,  3.750) = 193085 
    [ 3.750,  5.000) = 2467 
    [ 5.000,  6.250) = 210 
    [ 6.250,  7.500) = 53 
    [ 7.500,  8.750) = 42 
    [ 8.750, 10.000) = 103 
    [10.000, 11.250) = 142 
    [11.250, 12.500) = 74 
    [12.500, 13.750) = 76 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.949 ms/op
     p(50.0000) =      2.560 ms/op
     p(90.0000) =      3.031 ms/op
     p(95.0000) =      3.133 ms/op
     p(99.0000) =      3.637 ms/op
     p(99.9000) =      8.918 ms/op
     p(99.9900) =     13.173 ms/op
     p(99.9990) =     13.508 ms/op
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
# Warmup Iteration   1: 3.673 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.418 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.406 ±(99.9%) 0.005 ms/op
Iteration   1: 2.400 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.998 ms/op
                 existUser·p0.50:   2.499 ms/op
                 existUser·p0.90:   2.904 ms/op
                 existUser·p0.95:   2.986 ms/op
                 existUser·p0.99:   3.273 ms/op
                 existUser·p0.999:  5.595 ms/op
                 existUser·p0.9999: 14.331 ms/op
                 existUser·p1.00:   15.172 ms/op

Iteration   2: 2.425 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.757 ms/op
                 existUser·p0.50:   2.462 ms/op
                 existUser·p0.90:   2.949 ms/op
                 existUser·p0.95:   3.052 ms/op
                 existUser·p0.99:   3.621 ms/op
                 existUser·p0.999:  6.235 ms/op
                 existUser·p0.9999: 12.976 ms/op
                 existUser·p1.00:   13.206 ms/op

Iteration   3: 2.390 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.884 ms/op
                 existUser·p0.50:   2.429 ms/op
                 existUser·p0.90:   2.912 ms/op
                 existUser·p0.95:   3.023 ms/op
                 existUser·p0.99:   3.490 ms/op
                 existUser·p0.999:  5.033 ms/op
                 existUser·p0.9999: 11.265 ms/op
                 existUser·p1.00:   15.532 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 398661
  mean =      2.405 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 48 
    [ 1.250,  2.500) = 202898 
    [ 2.500,  3.750) = 193126 
    [ 3.750,  5.000) = 1930 
    [ 5.000,  6.250) = 299 
    [ 6.250,  7.500) = 6 
    [ 7.500,  8.750) = 4 
    [ 8.750, 10.000) = 74 
    [10.000, 11.250) = 105 
    [11.250, 12.500) = 97 
    [12.500, 13.750) = 48 
    [13.750, 15.000) = 24 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.757 ms/op
     p(50.0000) =      2.458 ms/op
     p(90.0000) =      2.920 ms/op
     p(95.0000) =      3.023 ms/op
     p(99.0000) =      3.457 ms/op
     p(99.9000) =      5.636 ms/op
     p(99.9900) =     13.142 ms/op
     p(99.9990) =     14.652 ms/op
     p(99.9999) =     15.532 ms/op
    p(100.0000) =     15.532 ms/op


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
# Warmup Iteration   1: 3.885 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.537 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.480 ±(99.9%) 0.006 ms/op
Iteration   1: 2.463 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.930 ms/op
                 getUser·p0.50:   2.503 ms/op
                 getUser·p0.90:   2.998 ms/op
                 getUser·p0.95:   3.097 ms/op
                 getUser·p0.99:   3.584 ms/op
                 getUser·p0.999:  5.753 ms/op
                 getUser·p0.9999: 13.566 ms/op
                 getUser·p1.00:   13.910 ms/op

Iteration   2: 2.495 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.988 ms/op
                 getUser·p0.50:   2.490 ms/op
                 getUser·p0.90:   3.052 ms/op
                 getUser·p0.95:   3.166 ms/op
                 getUser·p0.99:   3.727 ms/op
                 getUser·p0.999:  9.381 ms/op
                 getUser·p0.9999: 12.275 ms/op
                 getUser·p1.00:   12.550 ms/op

Iteration   3: 2.496 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.929 ms/op
                 getUser·p0.50:   2.515 ms/op
                 getUser·p0.90:   3.056 ms/op
                 getUser·p0.95:   3.215 ms/op
                 getUser·p0.99:   4.137 ms/op
                 getUser·p0.999:  7.939 ms/op
                 getUser·p0.9999: 11.010 ms/op
                 getUser·p1.00:   11.977 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 385978
  mean =      2.485 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 84 
    [ 1.250,  2.500) = 192763 
    [ 2.500,  3.750) = 188539 
    [ 3.750,  5.000) = 3888 
    [ 5.000,  6.250) = 271 
    [ 6.250,  7.500) = 27 
    [ 7.500,  8.750) = 61 
    [ 8.750, 10.000) = 87 
    [10.000, 11.250) = 77 
    [11.250, 12.500) = 130 
    [12.500, 13.750) = 45 
    [13.750, 15.000) = 6 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.929 ms/op
     p(50.0000) =      2.503 ms/op
     p(90.0000) =      3.031 ms/op
     p(95.0000) =      3.154 ms/op
     p(99.0000) =      3.843 ms/op
     p(99.9000) =      7.882 ms/op
     p(99.9900) =     12.966 ms/op
     p(99.9990) =     13.814 ms/op
     p(99.9999) =     13.910 ms/op
    p(100.0000) =     13.910 ms/op


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
# Warmup Iteration   1: 4.603 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.058 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.994 ±(99.9%) 0.009 ms/op
Iteration   1: 3.032 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.892 ms/op
                 listUser·p0.50:   2.966 ms/op
                 listUser·p0.90:   3.969 ms/op
                 listUser·p0.95:   4.530 ms/op
                 listUser·p0.99:   5.718 ms/op
                 listUser·p0.999:  8.733 ms/op
                 listUser·p0.9999: 10.878 ms/op
                 listUser·p1.00:   11.633 ms/op

Iteration   2: 2.991 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.839 ms/op
                 listUser·p0.50:   2.929 ms/op
                 listUser·p0.90:   3.858 ms/op
                 listUser·p0.95:   4.334 ms/op
                 listUser·p0.99:   5.456 ms/op
                 listUser·p0.999:  11.667 ms/op
                 listUser·p0.9999: 18.434 ms/op
                 listUser·p1.00:   19.825 ms/op

Iteration   3: 2.996 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.856 ms/op
                 listUser·p0.50:   2.925 ms/op
                 listUser·p0.90:   3.903 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   5.652 ms/op
                 listUser·p0.999:  9.610 ms/op
                 listUser·p0.9999: 11.769 ms/op
                 listUser·p1.00:   14.598 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 319034
  mean =      3.006 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 182 
    [ 1.250,  2.500) = 94060 
    [ 2.500,  3.750) = 184691 
    [ 3.750,  5.000) = 32304 
    [ 5.000,  6.250) = 6370 
    [ 6.250,  7.500) = 801 
    [ 7.500,  8.750) = 232 
    [ 8.750, 10.000) = 141 
    [10.000, 11.250) = 96 
    [11.250, 12.500) = 74 
    [12.500, 13.750) = 49 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 26 

  Percentiles, ms/op:
      p(0.0000) =      0.839 ms/op
     p(50.0000) =      2.937 ms/op
     p(90.0000) =      3.908 ms/op
     p(95.0000) =      4.424 ms/op
     p(99.0000) =      5.628 ms/op
     p(99.9000) =      9.420 ms/op
     p(99.9900) =     17.763 ms/op
     p(99.9990) =     19.636 ms/op
     p(99.9999) =     19.825 ms/op
    p(100.0000) =     19.825 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.844 ± 1.033  ops/ms
ClientPb.existUser                       thrpt       3  13.081 ± 2.492  ops/ms
ClientPb.getUser                         thrpt       3  13.060 ± 1.512  ops/ms
ClientPb.listUser                        thrpt       3  10.613 ± 1.541  ops/ms
ClientPb.createUser                       avgt       3   2.486 ± 0.300   ms/op
ClientPb.existUser                        avgt       3   2.499 ± 0.092   ms/op
ClientPb.getUser                          avgt       3   2.464 ± 0.081   ms/op
ClientPb.listUser                         avgt       3   3.002 ± 0.256   ms/op
ClientPb.createUser                     sample  383903   2.498 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.949           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.560           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.031           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.133           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.637           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.918           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.173           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.287           ms/op
ClientPb.existUser                      sample  398661   2.405 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.757           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.458           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.920           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.023           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.457           ms/op
ClientPb.existUser:existUser·p0.999     sample           5.636           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.142           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.532           ms/op
ClientPb.getUser                        sample  385978   2.485 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.929           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.503           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.031           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.154           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.843           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.882           ms/op
ClientPb.getUser:getUser·p0.9999        sample          12.966           ms/op
ClientPb.getUser:getUser·p1.00          sample          13.910           ms/op
ClientPb.listUser                       sample  319034   3.006 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.839           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.937           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.908           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.424           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.628           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.420           ms/op
ClientPb.listUser:listUser·p0.9999      sample          17.763           ms/op
ClientPb.listUser:listUser·p1.00        sample          19.825           ms/op
