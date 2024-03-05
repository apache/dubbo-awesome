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
# Warmup Iteration   1: 4.925 ops/ms
# Warmup Iteration   2: 12.154 ops/ms
# Warmup Iteration   3: 12.311 ops/ms
Iteration   1: 12.522 ops/ms
Iteration   2: 12.648 ops/ms
Iteration   3: 12.721 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.630 ±(99.9%) 1.842 ops/ms [Average]
  (min, avg, max) = (12.522, 12.630, 12.721), stdev = 0.101
  CI (99.9%): [10.789, 14.472] (assumes normal distribution)


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
# Warmup Iteration   1: 8.022 ops/ms
# Warmup Iteration   2: 13.201 ops/ms
# Warmup Iteration   3: 13.473 ops/ms
Iteration   1: 13.454 ops/ms
Iteration   2: 13.491 ops/ms
Iteration   3: 13.349 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.431 ±(99.9%) 1.338 ops/ms [Average]
  (min, avg, max) = (13.349, 13.431, 13.491), stdev = 0.073
  CI (99.9%): [12.094, 14.769] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 8.012 ops/ms
# Warmup Iteration   2: 12.842 ops/ms
# Warmup Iteration   3: 12.977 ops/ms
Iteration   1: 13.091 ops/ms
Iteration   2: 13.140 ops/ms
Iteration   3: 12.973 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.068 ±(99.9%) 1.565 ops/ms [Average]
  (min, avg, max) = (12.973, 13.068, 13.140), stdev = 0.086
  CI (99.9%): [11.503, 14.634] (assumes normal distribution)


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
# Warmup Iteration   1: 6.763 ops/ms
# Warmup Iteration   2: 10.511 ops/ms
# Warmup Iteration   3: 10.745 ops/ms
Iteration   1: 10.729 ops/ms
Iteration   2: 10.729 ops/ms
Iteration   3: 10.702 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.720 ±(99.9%) 0.282 ops/ms [Average]
  (min, avg, max) = (10.702, 10.720, 10.729), stdev = 0.015
  CI (99.9%): [10.438, 11.002] (assumes normal distribution)


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
# Warmup Iteration   1: 3.987 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.565 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.471 ±(99.9%) 0.004 ms/op
Iteration   1: 2.490 ±(99.9%) 0.005 ms/op
Iteration   2: 2.495 ±(99.9%) 0.004 ms/op
Iteration   3: 2.496 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.494 ±(99.9%) 0.056 ms/op [Average]
  (min, avg, max) = (2.490, 2.494, 2.496), stdev = 0.003
  CI (99.9%): [2.438, 2.550] (assumes normal distribution)


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
# Warmup Iteration   1: 3.597 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.448 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.451 ±(99.9%) 0.004 ms/op
Iteration   1: 2.432 ±(99.9%) 0.003 ms/op
Iteration   2: 2.427 ±(99.9%) 0.004 ms/op
Iteration   3: 2.426 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.428 ±(99.9%) 0.052 ms/op [Average]
  (min, avg, max) = (2.426, 2.428, 2.432), stdev = 0.003
  CI (99.9%): [2.376, 2.481] (assumes normal distribution)


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
# Warmup Iteration   1: 3.679 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.496 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.460 ±(99.9%) 0.005 ms/op
Iteration   1: 2.464 ±(99.9%) 0.004 ms/op
Iteration   2: 2.447 ±(99.9%) 0.006 ms/op
Iteration   3: 2.461 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.458 ±(99.9%) 0.165 ms/op [Average]
  (min, avg, max) = (2.447, 2.458, 2.464), stdev = 0.009
  CI (99.9%): [2.293, 2.623] (assumes normal distribution)


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
# Warmup Iteration   1: 4.544 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.984 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.997 ±(99.9%) 0.006 ms/op
Iteration   1: 2.981 ±(99.9%) 0.005 ms/op
Iteration   2: 2.970 ±(99.9%) 0.005 ms/op
Iteration   3: 2.986 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.979 ±(99.9%) 0.151 ms/op [Average]
  (min, avg, max) = (2.970, 2.979, 2.986), stdev = 0.008
  CI (99.9%): [2.827, 3.130] (assumes normal distribution)


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
# Warmup Iteration   1: 3.861 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.590 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.455 ±(99.9%) 0.005 ms/op
Iteration   1: 2.420 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.966 ms/op
                 createUser·p0.50:   2.490 ms/op
                 createUser·p0.90:   2.941 ms/op
                 createUser·p0.95:   3.068 ms/op
                 createUser·p0.99:   3.596 ms/op
                 createUser·p0.999:  6.060 ms/op
                 createUser·p0.9999: 13.169 ms/op
                 createUser·p1.00:   14.189 ms/op

Iteration   2: 2.419 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.998 ms/op
                 createUser·p0.50:   2.523 ms/op
                 createUser·p0.90:   2.925 ms/op
                 createUser·p0.95:   3.031 ms/op
                 createUser·p0.99:   3.531 ms/op
                 createUser·p0.999:  6.177 ms/op
                 createUser·p0.9999: 12.268 ms/op
                 createUser·p1.00:   13.058 ms/op

Iteration   3: 2.412 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.585 ms/op
                 createUser·p0.50:   2.494 ms/op
                 createUser·p0.90:   2.925 ms/op
                 createUser·p0.95:   3.039 ms/op
                 createUser·p0.99:   3.641 ms/op
                 createUser·p0.999:  7.431 ms/op
                 createUser·p0.9999: 11.231 ms/op
                 createUser·p1.00:   12.468 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 396799
  mean =      2.417 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 61 
    [ 1.250,  2.500) = 198363 
    [ 2.500,  3.750) = 195433 
    [ 3.750,  5.000) = 2236 
    [ 5.000,  6.250) = 296 
    [ 6.250,  7.500) = 22 
    [ 7.500,  8.750) = 12 
    [ 8.750, 10.000) = 121 
    [10.000, 11.250) = 82 
    [11.250, 12.500) = 109 
    [12.500, 13.750) = 62 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.585 ms/op
     p(50.0000) =      2.499 ms/op
     p(90.0000) =      2.929 ms/op
     p(95.0000) =      3.043 ms/op
     p(99.0000) =      3.584 ms/op
     p(99.9000) =      6.560 ms/op
     p(99.9900) =     12.829 ms/op
     p(99.9990) =     13.522 ms/op
     p(99.9999) =     14.189 ms/op
    p(100.0000) =     14.189 ms/op


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
# Warmup Iteration   1: 3.505 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 2.388 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.356 ±(99.9%) 0.005 ms/op
Iteration   1: 2.375 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.864 ms/op
                 existUser·p0.50:   2.437 ms/op
                 existUser·p0.90:   2.888 ms/op
                 existUser·p0.95:   2.998 ms/op
                 existUser·p0.99:   3.531 ms/op
                 existUser·p0.999:  5.659 ms/op
                 existUser·p0.9999: 13.682 ms/op
                 existUser·p1.00:   14.467 ms/op

Iteration   2: 2.363 ±(99.9%) 0.004 ms/op
                 existUser·p0.00:   1.002 ms/op
                 existUser·p0.50:   2.458 ms/op
                 existUser·p0.90:   2.863 ms/op
                 existUser·p0.95:   2.953 ms/op
                 existUser·p0.99:   3.387 ms/op
                 existUser·p0.999:  6.027 ms/op
                 existUser·p0.9999: 10.543 ms/op
                 existUser·p1.00:   10.781 ms/op

Iteration   3: 2.384 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.840 ms/op
                 existUser·p0.50:   2.454 ms/op
                 existUser·p0.90:   2.888 ms/op
                 existUser·p0.95:   3.006 ms/op
                 existUser·p0.99:   3.670 ms/op
                 existUser·p0.999:  8.847 ms/op
                 existUser·p0.9999: 12.216 ms/op
                 existUser·p1.00:   13.320 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 403951
  mean =      2.374 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 72 
    [ 1.250,  2.500) = 209485 
    [ 2.500,  3.750) = 191500 
    [ 3.750,  5.000) = 2207 
    [ 5.000,  6.250) = 266 
    [ 6.250,  7.500) = 32 
    [ 7.500,  8.750) = 25 
    [ 8.750, 10.000) = 153 
    [10.000, 11.250) = 41 
    [11.250, 12.500) = 124 
    [12.500, 13.750) = 35 
    [13.750, 15.000) = 11 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.840 ms/op
     p(50.0000) =      2.449 ms/op
     p(90.0000) =      2.879 ms/op
     p(95.0000) =      2.986 ms/op
     p(99.0000) =      3.551 ms/op
     p(99.9000) =      6.693 ms/op
     p(99.9900) =     12.626 ms/op
     p(99.9990) =     14.415 ms/op
     p(99.9999) =     14.467 ms/op
    p(100.0000) =     14.467 ms/op


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
# Warmup Iteration   1: 3.805 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.564 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.509 ±(99.9%) 0.006 ms/op
Iteration   1: 2.451 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.933 ms/op
                 getUser·p0.50:   2.482 ms/op
                 getUser·p0.90:   2.974 ms/op
                 getUser·p0.95:   3.076 ms/op
                 getUser·p0.99:   3.514 ms/op
                 getUser·p0.999:  6.284 ms/op
                 getUser·p0.9999: 14.434 ms/op
                 getUser·p1.00:   15.368 ms/op

Iteration   2: 2.492 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.838 ms/op
                 getUser·p0.50:   2.527 ms/op
                 getUser·p0.90:   3.011 ms/op
                 getUser·p0.95:   3.133 ms/op
                 getUser·p0.99:   4.439 ms/op
                 getUser·p0.999:  7.545 ms/op
                 getUser·p0.9999: 12.567 ms/op
                 getUser·p1.00:   17.564 ms/op

Iteration   3: 2.466 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.709 ms/op
                 getUser·p0.50:   2.499 ms/op
                 getUser·p0.90:   3.002 ms/op
                 getUser·p0.95:   3.121 ms/op
                 getUser·p0.99:   3.674 ms/op
                 getUser·p0.999:  5.508 ms/op
                 getUser·p0.9999: 10.830 ms/op
                 getUser·p1.00:   11.518 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 388451
  mean =      2.469 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 58 
    [ 1.250,  2.500) = 194046 
    [ 2.500,  3.750) = 190464 
    [ 3.750,  5.000) = 2741 
    [ 5.000,  6.250) = 666 
    [ 6.250,  7.500) = 83 
    [ 7.500,  8.750) = 54 
    [ 8.750, 10.000) = 51 
    [10.000, 11.250) = 105 
    [11.250, 12.500) = 74 
    [12.500, 13.750) = 76 
    [13.750, 15.000) = 27 
    [15.000, 16.250) = 4 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.709 ms/op
     p(50.0000) =      2.503 ms/op
     p(90.0000) =      2.994 ms/op
     p(95.0000) =      3.109 ms/op
     p(99.0000) =      3.748 ms/op
     p(99.9000) =      7.528 ms/op
     p(99.9900) =     13.664 ms/op
     p(99.9990) =     15.238 ms/op
     p(99.9999) =     17.564 ms/op
    p(100.0000) =     17.564 ms/op


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
# Warmup Iteration   1: 4.614 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.063 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.995 ±(99.9%) 0.009 ms/op
Iteration   1: 3.013 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.940 ms/op
                 listUser·p0.50:   2.937 ms/op
                 listUser·p0.90:   3.903 ms/op
                 listUser·p0.95:   4.456 ms/op
                 listUser·p0.99:   5.652 ms/op
                 listUser·p0.999:  10.124 ms/op
                 listUser·p0.9999: 12.585 ms/op
                 listUser·p1.00:   13.386 ms/op

Iteration   2: 3.000 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.874 ms/op
                 listUser·p0.50:   2.941 ms/op
                 listUser·p0.90:   3.883 ms/op
                 listUser·p0.95:   4.383 ms/op
                 listUser·p0.99:   5.628 ms/op
                 listUser·p0.999:  9.707 ms/op
                 listUser·p0.9999: 11.759 ms/op
                 listUser·p1.00:   12.304 ms/op

Iteration   3: 3.023 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.939 ms/op
                 listUser·p0.50:   2.953 ms/op
                 listUser·p0.90:   3.916 ms/op
                 listUser·p0.95:   4.415 ms/op
                 listUser·p0.99:   5.571 ms/op
                 listUser·p0.999:  9.290 ms/op
                 listUser·p0.9999: 10.933 ms/op
                 listUser·p1.00:   11.600 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 318382
  mean =      3.012 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 139 
    [ 1.250,  2.500) = 91753 
    [ 2.500,  3.750) = 186412 
    [ 3.750,  5.000) = 32582 
    [ 5.000,  6.250) = 6067 
    [ 6.250,  7.500) = 685 
    [ 7.500,  8.750) = 232 
    [ 8.750, 10.000) = 229 
    [10.000, 11.250) = 208 
    [11.250, 12.500) = 63 
    [12.500, 13.750) = 12 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.874 ms/op
     p(50.0000) =      2.945 ms/op
     p(90.0000) =      3.899 ms/op
     p(95.0000) =      4.415 ms/op
     p(99.0000) =      5.612 ms/op
     p(99.9000) =      9.716 ms/op
     p(99.9900) =     11.829 ms/op
     p(99.9990) =     13.281 ms/op
     p(99.9999) =     13.386 ms/op
    p(100.0000) =     13.386 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.630 ± 1.842  ops/ms
ClientPb.existUser                       thrpt       3  13.431 ± 1.338  ops/ms
ClientPb.getUser                         thrpt       3  13.068 ± 1.565  ops/ms
ClientPb.listUser                        thrpt       3  10.720 ± 0.282  ops/ms
ClientPb.createUser                       avgt       3   2.494 ± 0.056   ms/op
ClientPb.existUser                        avgt       3   2.428 ± 0.052   ms/op
ClientPb.getUser                          avgt       3   2.458 ± 0.165   ms/op
ClientPb.listUser                         avgt       3   2.979 ± 0.151   ms/op
ClientPb.createUser                     sample  396799   2.417 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.585           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.499           ms/op
ClientPb.createUser:createUser·p0.90    sample           2.929           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.043           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.584           ms/op
ClientPb.createUser:createUser·p0.999   sample           6.560           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.829           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.189           ms/op
ClientPb.existUser                      sample  403951   2.374 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.840           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.449           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.879           ms/op
ClientPb.existUser:existUser·p0.95      sample           2.986           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.551           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.693           ms/op
ClientPb.existUser:existUser·p0.9999    sample          12.626           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.467           ms/op
ClientPb.getUser                        sample  388451   2.469 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.709           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.503           ms/op
ClientPb.getUser:getUser·p0.90          sample           2.994           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.109           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.748           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.528           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.664           ms/op
ClientPb.getUser:getUser·p1.00          sample          17.564           ms/op
ClientPb.listUser                       sample  318382   3.012 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.874           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.945           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.899           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.415           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.612           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.716           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.829           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.386           ms/op
