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
# Warmup Iteration   1: 5.091 ops/ms
# Warmup Iteration   2: 12.198 ops/ms
# Warmup Iteration   3: 12.600 ops/ms
Iteration   1: 12.801 ops/ms
Iteration   2: 12.796 ops/ms
Iteration   3: 12.798 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.798 ±(99.9%) 0.040 ops/ms [Average]
  (min, avg, max) = (12.796, 12.798, 12.801), stdev = 0.002
  CI (99.9%): [12.758, 12.838] (assumes normal distribution)


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
# Warmup Iteration   1: 8.557 ops/ms
# Warmup Iteration   2: 13.401 ops/ms
# Warmup Iteration   3: 13.592 ops/ms
Iteration   1: 13.637 ops/ms
Iteration   2: 13.649 ops/ms
Iteration   3: 13.558 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.615 ±(99.9%) 0.899 ops/ms [Average]
  (min, avg, max) = (13.558, 13.615, 13.649), stdev = 0.049
  CI (99.9%): [12.715, 14.514] (assumes normal distribution)


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
# Warmup Iteration   1: 8.074 ops/ms
# Warmup Iteration   2: 12.976 ops/ms
# Warmup Iteration   3: 13.225 ops/ms
Iteration   1: 13.307 ops/ms
Iteration   2: 13.042 ops/ms
Iteration   3: 13.162 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.170 ±(99.9%) 2.418 ops/ms [Average]
  (min, avg, max) = (13.042, 13.170, 13.307), stdev = 0.133
  CI (99.9%): [10.753, 15.588] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:44
# Fork: 1 of 1
# Warmup Iteration   1: 6.609 ops/ms
# Warmup Iteration   2: 10.657 ops/ms
# Warmup Iteration   3: 10.685 ops/ms
Iteration   1: 10.769 ops/ms
Iteration   2: 10.703 ops/ms
Iteration   3: 10.659 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.710 ±(99.9%) 1.015 ops/ms [Average]
  (min, avg, max) = (10.659, 10.710, 10.769), stdev = 0.056
  CI (99.9%): [9.695, 11.725] (assumes normal distribution)


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
# Warmup Iteration   1: 3.847 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.553 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.501 ±(99.9%) 0.004 ms/op
Iteration   1: 2.505 ±(99.9%) 0.004 ms/op
Iteration   2: 2.482 ±(99.9%) 0.004 ms/op
Iteration   3: 2.516 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.501 ±(99.9%) 0.311 ms/op [Average]
  (min, avg, max) = (2.482, 2.501, 2.516), stdev = 0.017
  CI (99.9%): [2.190, 2.812] (assumes normal distribution)


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
# Warmup Iteration   1: 3.663 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.410 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.380 ±(99.9%) 0.004 ms/op
Iteration   1: 2.385 ±(99.9%) 0.004 ms/op
Iteration   2: 2.393 ±(99.9%) 0.004 ms/op
Iteration   3: 2.432 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.403 ±(99.9%) 0.456 ms/op [Average]
  (min, avg, max) = (2.385, 2.403, 2.432), stdev = 0.025
  CI (99.9%): [1.947, 2.859] (assumes normal distribution)


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
# Warmup Iteration   1: 3.852 ±(99.9%) 0.008 ms/op
# Warmup Iteration   2: 2.468 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.424 ±(99.9%) 0.004 ms/op
Iteration   1: 2.425 ±(99.9%) 0.005 ms/op
Iteration   2: 2.435 ±(99.9%) 0.005 ms/op
Iteration   3: 2.419 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.426 ±(99.9%) 0.141 ms/op [Average]
  (min, avg, max) = (2.419, 2.426, 2.435), stdev = 0.008
  CI (99.9%): [2.285, 2.568] (assumes normal distribution)


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
# Warmup Iteration   1: 4.699 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.017 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.015 ±(99.9%) 0.005 ms/op
Iteration   1: 2.986 ±(99.9%) 0.004 ms/op
Iteration   2: 2.996 ±(99.9%) 0.005 ms/op
Iteration   3: 2.972 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.984 ±(99.9%) 0.221 ms/op [Average]
  (min, avg, max) = (2.972, 2.984, 2.996), stdev = 0.012
  CI (99.9%): [2.763, 3.206] (assumes normal distribution)


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
# Warmup Iteration   1: 3.966 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.601 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.455 ±(99.9%) 0.005 ms/op
Iteration   1: 2.435 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.804 ms/op
                 createUser·p0.50:   2.486 ms/op
                 createUser·p0.90:   2.957 ms/op
                 createUser·p0.95:   3.088 ms/op
                 createUser·p0.99:   3.740 ms/op
                 createUser·p0.999:  6.151 ms/op
                 createUser·p0.9999: 13.400 ms/op
                 createUser·p1.00:   13.943 ms/op

Iteration   2: 2.427 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.920 ms/op
                 createUser·p0.50:   2.507 ms/op
                 createUser·p0.90:   2.937 ms/op
                 createUser·p0.95:   3.043 ms/op
                 createUser·p0.99:   3.494 ms/op
                 createUser·p0.999:  6.846 ms/op
                 createUser·p0.9999: 12.394 ms/op
                 createUser·p1.00:   12.730 ms/op

Iteration   3: 2.416 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.991 ms/op
                 createUser·p0.50:   2.482 ms/op
                 createUser·p0.90:   2.937 ms/op
                 createUser·p0.95:   3.052 ms/op
                 createUser·p0.99:   3.617 ms/op
                 createUser·p0.999:  7.723 ms/op
                 createUser·p0.9999: 11.612 ms/op
                 createUser·p1.00:   11.928 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 395343
  mean =      2.426 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 74 
    [ 1.250,  2.500) = 198772 
    [ 2.500,  3.750) = 193404 
    [ 3.750,  5.000) = 2345 
    [ 5.000,  6.250) = 336 
    [ 6.250,  7.500) = 22 
    [ 7.500,  8.750) = 13 
    [ 8.750, 10.000) = 101 
    [10.000, 11.250) = 67 
    [11.250, 12.500) = 136 
    [12.500, 13.750) = 70 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.804 ms/op
     p(50.0000) =      2.490 ms/op
     p(90.0000) =      2.941 ms/op
     p(95.0000) =      3.060 ms/op
     p(99.0000) =      3.621 ms/op
     p(99.9000) =      6.788 ms/op
     p(99.9900) =     13.033 ms/op
     p(99.9990) =     13.700 ms/op
     p(99.9999) =     13.943 ms/op
    p(100.0000) =     13.943 ms/op


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
# Warmup Iteration   1: 3.637 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.380 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.381 ±(99.9%) 0.005 ms/op
Iteration   1: 2.366 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.943 ms/op
                 existUser·p0.50:   2.396 ms/op
                 existUser·p0.90:   2.875 ms/op
                 existUser·p0.95:   2.982 ms/op
                 existUser·p0.99:   3.437 ms/op
                 existUser·p0.999:  5.983 ms/op
                 existUser·p0.9999: 13.909 ms/op
                 existUser·p1.00:   14.254 ms/op

Iteration   2: 2.366 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.738 ms/op
                 existUser·p0.50:   2.454 ms/op
                 existUser·p0.90:   2.859 ms/op
                 existUser·p0.95:   2.953 ms/op
                 existUser·p0.99:   3.404 ms/op
                 existUser·p0.999:  6.079 ms/op
                 existUser·p0.9999: 12.599 ms/op
                 existUser·p1.00:   13.206 ms/op

Iteration   3: 2.385 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.473 ms/op
                 existUser·p0.50:   2.425 ms/op
                 existUser·p0.90:   2.900 ms/op
                 existUser·p0.95:   3.027 ms/op
                 existUser·p0.99:   3.654 ms/op
                 existUser·p0.999:  7.762 ms/op
                 existUser·p0.9999: 12.042 ms/op
                 existUser·p1.00:   12.911 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 404298
  mean =      2.372 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 97 
    [ 1.250,  2.500) = 211447 
    [ 2.500,  3.750) = 190067 
    [ 3.750,  5.000) = 2038 
    [ 5.000,  6.250) = 225 
    [ 6.250,  7.500) = 32 
    [ 7.500,  8.750) = 52 
    [ 8.750, 10.000) = 76 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 120 
    [12.500, 13.750) = 95 
    [13.750, 15.000) = 17 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.473 ms/op
     p(50.0000) =      2.421 ms/op
     p(90.0000) =      2.879 ms/op
     p(95.0000) =      2.986 ms/op
     p(99.0000) =      3.502 ms/op
     p(99.9000) =      7.021 ms/op
     p(99.9900) =     13.255 ms/op
     p(99.9990) =     14.221 ms/op
     p(99.9999) =     14.254 ms/op
    p(100.0000) =     14.254 ms/op


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
# Warmup Iteration   1: 3.942 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.540 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.461 ±(99.9%) 0.005 ms/op
Iteration   1: 2.450 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.643 ms/op
                 getUser·p0.50:   2.470 ms/op
                 getUser·p0.90:   2.978 ms/op
                 getUser·p0.95:   3.092 ms/op
                 getUser·p0.99:   3.674 ms/op
                 getUser·p0.999:  6.165 ms/op
                 getUser·p0.9999: 13.303 ms/op
                 getUser·p1.00:   13.713 ms/op

Iteration   2: 2.497 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.903 ms/op
                 getUser·p0.50:   2.515 ms/op
                 getUser·p0.90:   3.031 ms/op
                 getUser·p0.95:   3.170 ms/op
                 getUser·p0.99:   4.309 ms/op
                 getUser·p0.999:  9.547 ms/op
                 getUser·p0.9999: 13.291 ms/op
                 getUser·p1.00:   14.008 ms/op

Iteration   3: 2.454 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.014 ms/op
                 getUser·p0.50:   2.462 ms/op
                 getUser·p0.90:   2.990 ms/op
                 getUser·p0.95:   3.092 ms/op
                 getUser·p0.99:   3.584 ms/op
                 getUser·p0.999:  6.132 ms/op
                 getUser·p0.9999: 10.731 ms/op
                 getUser·p1.00:   11.158 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 388766
  mean =      2.467 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 84 
    [ 1.250,  2.500) = 195623 
    [ 2.500,  3.750) = 188794 
    [ 3.750,  5.000) = 3388 
    [ 5.000,  6.250) = 475 
    [ 6.250,  7.500) = 18 
    [ 7.500,  8.750) = 37 
    [ 8.750, 10.000) = 78 
    [10.000, 11.250) = 74 
    [11.250, 12.500) = 100 
    [12.500, 13.750) = 89 
    [13.750, 15.000) = 6 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.643 ms/op
     p(50.0000) =      2.482 ms/op
     p(90.0000) =      2.998 ms/op
     p(95.0000) =      3.117 ms/op
     p(99.0000) =      3.813 ms/op
     p(99.9000) =      6.431 ms/op
     p(99.9900) =     13.126 ms/op
     p(99.9990) =     13.946 ms/op
     p(99.9999) =     14.008 ms/op
    p(100.0000) =     14.008 ms/op


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
# Warmup Iteration   1: 4.889 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.034 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.982 ±(99.9%) 0.009 ms/op
Iteration   1: 2.980 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.902 ms/op
                 listUser·p0.50:   2.925 ms/op
                 listUser·p0.90:   3.850 ms/op
                 listUser·p0.95:   4.350 ms/op
                 listUser·p0.99:   5.636 ms/op
                 listUser·p0.999:  8.466 ms/op
                 listUser·p0.9999: 10.670 ms/op
                 listUser·p1.00:   11.174 ms/op

Iteration   2: 2.965 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.937 ms/op
                 listUser·p0.50:   2.900 ms/op
                 listUser·p0.90:   3.834 ms/op
                 listUser·p0.95:   4.284 ms/op
                 listUser·p0.99:   5.489 ms/op
                 listUser·p0.999:  9.050 ms/op
                 listUser·p0.9999: 13.154 ms/op
                 listUser·p1.00:   13.992 ms/op

Iteration   3: 2.967 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.926 ms/op
                 listUser·p0.50:   2.900 ms/op
                 listUser·p0.90:   3.817 ms/op
                 listUser·p0.95:   4.301 ms/op
                 listUser·p0.99:   5.497 ms/op
                 listUser·p0.999:  9.126 ms/op
                 listUser·p0.9999: 15.588 ms/op
                 listUser·p1.00:   16.105 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 322873
  mean =      2.970 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 169 
    [ 1.250,  2.500) = 98833 
    [ 2.500,  3.750) = 187095 
    [ 3.750,  5.000) = 30024 
    [ 5.000,  6.250) = 5631 
    [ 6.250,  7.500) = 514 
    [ 7.500,  8.750) = 243 
    [ 8.750, 10.000) = 241 
    [10.000, 11.250) = 57 
    [11.250, 12.500) = 19 
    [12.500, 13.750) = 14 
    [13.750, 15.000) = 14 
    [15.000, 16.250) = 19 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.902 ms/op
     p(50.0000) =      2.908 ms/op
     p(90.0000) =      3.834 ms/op
     p(95.0000) =      4.317 ms/op
     p(99.0000) =      5.530 ms/op
     p(99.9000) =      8.913 ms/op
     p(99.9900) =     14.039 ms/op
     p(99.9990) =     16.021 ms/op
     p(99.9999) =     16.105 ms/op
    p(100.0000) =     16.105 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.798 ± 0.040  ops/ms
ClientPb.existUser                       thrpt       3  13.615 ± 0.899  ops/ms
ClientPb.getUser                         thrpt       3  13.170 ± 2.418  ops/ms
ClientPb.listUser                        thrpt       3  10.710 ± 1.015  ops/ms
ClientPb.createUser                       avgt       3   2.501 ± 0.311   ms/op
ClientPb.existUser                        avgt       3   2.403 ± 0.456   ms/op
ClientPb.getUser                          avgt       3   2.426 ± 0.141   ms/op
ClientPb.listUser                         avgt       3   2.984 ± 0.221   ms/op
ClientPb.createUser                     sample  395343   2.426 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.804           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.490           ms/op
ClientPb.createUser:createUser·p0.90    sample           2.941           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.060           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.621           ms/op
ClientPb.createUser:createUser·p0.999   sample           6.788           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.033           ms/op
ClientPb.createUser:createUser·p1.00    sample          13.943           ms/op
ClientPb.existUser                      sample  404298   2.372 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.473           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.421           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.879           ms/op
ClientPb.existUser:existUser·p0.95      sample           2.986           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.502           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.021           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.255           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.254           ms/op
ClientPb.getUser                        sample  388766   2.467 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.643           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.482           ms/op
ClientPb.getUser:getUser·p0.90          sample           2.998           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.117           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.813           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.431           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.126           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.008           ms/op
ClientPb.listUser                       sample  322873   2.970 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.902           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.908           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.834           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.317           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.530           ms/op
ClientPb.listUser:listUser·p0.999       sample           8.913           ms/op
ClientPb.listUser:listUser·p0.9999      sample          14.039           ms/op
ClientPb.listUser:listUser·p1.00        sample          16.105           ms/op
