# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.329 ops/ms
# Warmup Iteration   2: 11.933 ops/ms
# Warmup Iteration   3: 12.604 ops/ms
Iteration   1: 12.814 ops/ms
Iteration   2: 12.996 ops/ms
Iteration   3: 12.890 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.900 ±(99.9%) 1.670 ops/ms [Average]
  (min, avg, max) = (12.814, 12.900, 12.996), stdev = 0.092
  CI (99.9%): [11.230, 14.570] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:52
# Fork: 1 of 1
# Warmup Iteration   1: 8.469 ops/ms
# Warmup Iteration   2: 13.053 ops/ms
# Warmup Iteration   3: 13.289 ops/ms
Iteration   1: 13.404 ops/ms
Iteration   2: 13.389 ops/ms
Iteration   3: 13.279 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.358 ±(99.9%) 1.243 ops/ms [Average]
  (min, avg, max) = (13.279, 13.358, 13.404), stdev = 0.068
  CI (99.9%): [12.115, 14.600] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.847 ops/ms
# Warmup Iteration   2: 12.804 ops/ms
# Warmup Iteration   3: 12.855 ops/ms
Iteration   1: 12.900 ops/ms
Iteration   2: 12.942 ops/ms
Iteration   3: 12.816 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.886 ±(99.9%) 1.171 ops/ms [Average]
  (min, avg, max) = (12.816, 12.886, 12.942), stdev = 0.064
  CI (99.9%): [11.715, 14.056] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.571 ops/ms
# Warmup Iteration   2: 10.525 ops/ms
# Warmup Iteration   3: 10.597 ops/ms
Iteration   1: 10.650 ops/ms
Iteration   2: 10.577 ops/ms
Iteration   3: 10.542 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.590 ±(99.9%) 0.997 ops/ms [Average]
  (min, avg, max) = (10.542, 10.590, 10.650), stdev = 0.055
  CI (99.9%): [9.593, 11.587] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.385 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.575 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.525 ±(99.9%) 0.003 ms/op
Iteration   1: 2.553 ±(99.9%) 0.004 ms/op
Iteration   2: 2.509 ±(99.9%) 0.004 ms/op
Iteration   3: 2.555 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.539 ±(99.9%) 0.469 ms/op [Average]
  (min, avg, max) = (2.509, 2.539, 2.555), stdev = 0.026
  CI (99.9%): [2.070, 3.008] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:33
# Fork: 1 of 1
# Warmup Iteration   1: 3.579 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.471 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.463 ±(99.9%) 0.004 ms/op
Iteration   1: 2.541 ±(99.9%) 0.004 ms/op
Iteration   2: 2.404 ±(99.9%) 0.004 ms/op
Iteration   3: 2.432 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.459 ±(99.9%) 1.323 ms/op [Average]
  (min, avg, max) = (2.404, 2.459, 2.541), stdev = 0.073
  CI (99.9%): [1.136, 3.782] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.796 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.530 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.540 ±(99.9%) 0.004 ms/op
Iteration   1: 2.489 ±(99.9%) 0.004 ms/op
Iteration   2: 2.519 ±(99.9%) 0.005 ms/op
Iteration   3: 2.500 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.503 ±(99.9%) 0.280 ms/op [Average]
  (min, avg, max) = (2.489, 2.503, 2.519), stdev = 0.015
  CI (99.9%): [2.222, 2.783] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:23
# Fork: 1 of 1
# Warmup Iteration   1: 4.632 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.056 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.038 ±(99.9%) 0.006 ms/op
Iteration   1: 2.981 ±(99.9%) 0.005 ms/op
Iteration   2: 2.971 ±(99.9%) 0.005 ms/op
Iteration   3: 2.985 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.979 ±(99.9%) 0.134 ms/op [Average]
  (min, avg, max) = (2.971, 2.979, 2.985), stdev = 0.007
  CI (99.9%): [2.845, 3.113] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:18
# Fork: 1 of 1
# Warmup Iteration   1: 4.208 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 2.650 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.522 ±(99.9%) 0.006 ms/op
Iteration   1: 2.509 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.990 ms/op
                 createUser·p0.50:   2.572 ms/op
                 createUser·p0.90:   3.056 ms/op
                 createUser·p0.95:   3.183 ms/op
                 createUser·p0.99:   3.821 ms/op
                 createUser·p0.999:  10.528 ms/op
                 createUser·p0.9999: 13.526 ms/op
                 createUser·p1.00:   14.172 ms/op

Iteration   2: 2.493 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.745 ms/op
                 createUser·p0.50:   2.556 ms/op
                 createUser·p0.90:   3.031 ms/op
                 createUser·p0.95:   3.146 ms/op
                 createUser·p0.99:   3.740 ms/op
                 createUser·p0.999:  9.167 ms/op
                 createUser·p0.9999: 12.075 ms/op
                 createUser·p1.00:   12.632 ms/op

Iteration   3: 2.526 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.760 ms/op
                 createUser·p0.50:   2.589 ms/op
                 createUser·p0.90:   3.076 ms/op
                 createUser·p0.95:   3.203 ms/op
                 createUser·p0.99:   3.899 ms/op
                 createUser·p0.999:  8.601 ms/op
                 createUser·p0.9999: 11.960 ms/op
                 createUser·p1.00:   12.927 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 382189
  mean =      2.509 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 69 
    [ 1.250,  2.500) = 184388 
    [ 2.500,  3.750) = 193290 
    [ 3.750,  5.000) = 3731 
    [ 5.000,  6.250) = 307 
    [ 6.250,  7.500) = 14 
    [ 7.500,  8.750) = 12 
    [ 8.750, 10.000) = 63 
    [10.000, 11.250) = 130 
    [11.250, 12.500) = 119 
    [12.500, 13.750) = 62 
    [13.750, 15.000) = 4 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.745 ms/op
     p(50.0000) =      2.572 ms/op
     p(90.0000) =      3.056 ms/op
     p(95.0000) =      3.178 ms/op
     p(99.0000) =      3.822 ms/op
     p(99.9000) =      8.612 ms/op
     p(99.9900) =     12.871 ms/op
     p(99.9990) =     13.794 ms/op
     p(99.9999) =     14.172 ms/op
    p(100.0000) =     14.172 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.619 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.486 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.465 ±(99.9%) 0.005 ms/op
Iteration   1: 2.497 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.986 ms/op
                 existUser·p0.50:   2.494 ms/op
                 existUser·p0.90:   3.056 ms/op
                 existUser·p0.95:   3.194 ms/op
                 existUser·p0.99:   3.932 ms/op
                 existUser·p0.999:  11.570 ms/op
                 existUser·p0.9999: 13.615 ms/op
                 existUser·p1.00:   15.385 ms/op

Iteration   2: 2.458 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.998 ms/op
                 existUser·p0.50:   2.470 ms/op
                 existUser·p0.90:   3.002 ms/op
                 existUser·p0.95:   3.109 ms/op
                 existUser·p0.99:   3.650 ms/op
                 existUser·p0.999:  7.600 ms/op
                 existUser·p0.9999: 13.779 ms/op
                 existUser·p1.00:   14.631 ms/op

Iteration   3: 2.413 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.914 ms/op
                 existUser·p0.50:   2.486 ms/op
                 existUser·p0.90:   2.933 ms/op
                 existUser·p0.95:   3.043 ms/op
                 existUser·p0.99:   3.518 ms/op
                 existUser·p0.999:  5.742 ms/op
                 existUser·p0.9999: 11.318 ms/op
                 existUser·p1.00:   11.600 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 390535
  mean =      2.455 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 58 
    [ 1.250,  2.500) = 196945 
    [ 2.500,  3.750) = 189919 
    [ 3.750,  5.000) = 2814 
    [ 5.000,  6.250) = 366 
    [ 6.250,  7.500) = 62 
    [ 7.500,  8.750) = 24 
    [ 8.750, 10.000) = 34 
    [10.000, 11.250) = 101 
    [11.250, 12.500) = 80 
    [12.500, 13.750) = 115 
    [13.750, 15.000) = 15 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.914 ms/op
     p(50.0000) =      2.482 ms/op
     p(90.0000) =      2.998 ms/op
     p(95.0000) =      3.121 ms/op
     p(99.0000) =      3.695 ms/op
     p(99.9000) =      6.709 ms/op
     p(99.9900) =     13.564 ms/op
     p(99.9990) =     14.586 ms/op
     p(99.9999) =     15.385 ms/op
    p(100.0000) =     15.385 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.877 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.567 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.548 ±(99.9%) 0.006 ms/op
Iteration   1: 2.534 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.943 ms/op
                 getUser·p0.50:   2.548 ms/op
                 getUser·p0.90:   3.080 ms/op
                 getUser·p0.95:   3.211 ms/op
                 getUser·p0.99:   4.035 ms/op
                 getUser·p0.999:  12.370 ms/op
                 getUser·p0.9999: 14.420 ms/op
                 getUser·p1.00:   14.778 ms/op

Iteration   2: 2.464 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.959 ms/op
                 getUser·p0.50:   2.519 ms/op
                 getUser·p0.90:   2.998 ms/op
                 getUser·p0.95:   3.092 ms/op
                 getUser·p0.99:   3.559 ms/op
                 getUser·p0.999:  6.646 ms/op
                 getUser·p0.9999: 13.517 ms/op
                 getUser·p1.00:   14.598 ms/op

Iteration   3: 2.467 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.417 ms/op
                 getUser·p0.50:   2.507 ms/op
                 getUser·p0.90:   3.006 ms/op
                 getUser·p0.95:   3.109 ms/op
                 getUser·p0.99:   3.564 ms/op
                 getUser·p0.999:  7.022 ms/op
                 getUser·p0.9999: 12.027 ms/op
                 getUser·p1.00:   12.796 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 385525
  mean =      2.488 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 62 
    [ 1.250,  2.500) = 191153 
    [ 2.500,  3.750) = 190639 
    [ 3.750,  5.000) = 2742 
    [ 5.000,  6.250) = 512 
    [ 6.250,  7.500) = 34 
    [ 7.500,  8.750) = 24 
    [ 8.750, 10.000) = 77 
    [10.000, 11.250) = 63 
    [11.250, 12.500) = 71 
    [12.500, 13.750) = 97 
    [13.750, 15.000) = 51 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.417 ms/op
     p(50.0000) =      2.527 ms/op
     p(90.0000) =      3.027 ms/op
     p(95.0000) =      3.138 ms/op
     p(99.0000) =      3.723 ms/op
     p(99.9000) =      7.249 ms/op
     p(99.9900) =     13.894 ms/op
     p(99.9990) =     14.704 ms/op
     p(99.9999) =     14.778 ms/op
    p(100.0000) =     14.778 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.886 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.069 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.057 ±(99.9%) 0.009 ms/op
Iteration   1: 3.034 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.938 ms/op
                 listUser·p0.50:   2.982 ms/op
                 listUser·p0.90:   3.895 ms/op
                 listUser·p0.95:   4.383 ms/op
                 listUser·p0.99:   5.464 ms/op
                 listUser·p0.999:  8.851 ms/op
                 listUser·p0.9999: 11.935 ms/op
                 listUser·p1.00:   12.239 ms/op

Iteration   2: 3.067 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.982 ms/op
                 listUser·p0.50:   2.998 ms/op
                 listUser·p0.90:   3.961 ms/op
                 listUser·p0.95:   4.415 ms/op
                 listUser·p0.99:   5.620 ms/op
                 listUser·p0.999:  9.740 ms/op
                 listUser·p0.9999: 11.481 ms/op
                 listUser·p1.00:   12.616 ms/op

Iteration   3: 3.027 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.784 ms/op
                 listUser·p0.50:   2.966 ms/op
                 listUser·p0.90:   3.887 ms/op
                 listUser·p0.95:   4.350 ms/op
                 listUser·p0.99:   5.554 ms/op
                 listUser·p0.999:  9.525 ms/op
                 listUser·p0.9999: 11.731 ms/op
                 listUser·p1.00:   13.206 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 315256
  mean =      3.042 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 113 
    [ 1.250,  2.500) = 83904 
    [ 2.500,  3.750) = 190239 
    [ 3.750,  5.000) = 34172 
    [ 5.000,  6.250) = 5536 
    [ 6.250,  7.500) = 588 
    [ 7.500,  8.750) = 257 
    [ 8.750, 10.000) = 261 
    [10.000, 11.250) = 129 
    [11.250, 12.500) = 54 
    [12.500, 13.750) = 3 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.784 ms/op
     p(50.0000) =      2.982 ms/op
     p(90.0000) =      3.916 ms/op
     p(95.0000) =      4.383 ms/op
     p(99.0000) =      5.546 ms/op
     p(99.9000) =      9.454 ms/op
     p(99.9900) =     11.682 ms/op
     p(99.9990) =     12.578 ms/op
     p(99.9999) =     13.206 ms/op
    p(100.0000) =     13.206 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.900 ± 1.670  ops/ms
ClientPb.existUser                       thrpt       3  13.358 ± 1.243  ops/ms
ClientPb.getUser                         thrpt       3  12.886 ± 1.171  ops/ms
ClientPb.listUser                        thrpt       3  10.590 ± 0.997  ops/ms
ClientPb.createUser                       avgt       3   2.539 ± 0.469   ms/op
ClientPb.existUser                        avgt       3   2.459 ± 1.323   ms/op
ClientPb.getUser                          avgt       3   2.503 ± 0.280   ms/op
ClientPb.listUser                         avgt       3   2.979 ± 0.134   ms/op
ClientPb.createUser                     sample  382189   2.509 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.745           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.572           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.056           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.178           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.822           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.612           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.871           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.172           ms/op
ClientPb.existUser                      sample  390535   2.455 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.914           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.482           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.998           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.121           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.695           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.709           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.564           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.385           ms/op
ClientPb.getUser                        sample  385525   2.488 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.417           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.527           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.027           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.138           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.723           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.249           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.894           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.778           ms/op
ClientPb.listUser                       sample  315256   3.042 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.784           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.982           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.916           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.383           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.546           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.454           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.682           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.206           ms/op
