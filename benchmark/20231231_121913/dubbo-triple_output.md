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
# Warmup Iteration   1: 4.962 ops/ms
# Warmup Iteration   2: 11.781 ops/ms
# Warmup Iteration   3: 12.054 ops/ms
Iteration   1: 12.302 ops/ms
Iteration   2: 12.343 ops/ms
Iteration   3: 12.444 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.363 ±(99.9%) 1.331 ops/ms [Average]
  (min, avg, max) = (12.302, 12.363, 12.444), stdev = 0.073
  CI (99.9%): [11.032, 13.694] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 8.155 ops/ms
# Warmup Iteration   2: 12.662 ops/ms
# Warmup Iteration   3: 12.923 ops/ms
Iteration   1: 12.942 ops/ms
Iteration   2: 12.989 ops/ms
Iteration   3: 13.138 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.023 ±(99.9%) 1.870 ops/ms [Average]
  (min, avg, max) = (12.942, 13.023, 13.138), stdev = 0.102
  CI (99.9%): [11.153, 14.893] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.492 ops/ms
# Warmup Iteration   2: 12.616 ops/ms
# Warmup Iteration   3: 12.975 ops/ms
Iteration   1: 12.963 ops/ms
Iteration   2: 12.818 ops/ms
Iteration   3: 12.815 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.865 ±(99.9%) 1.540 ops/ms [Average]
  (min, avg, max) = (12.815, 12.865, 12.963), stdev = 0.084
  CI (99.9%): [11.325, 14.406] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 6.732 ops/ms
# Warmup Iteration   2: 10.325 ops/ms
# Warmup Iteration   3: 10.590 ops/ms
Iteration   1: 10.620 ops/ms
Iteration   2: 10.616 ops/ms
Iteration   3: 10.665 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.634 ±(99.9%) 0.502 ops/ms [Average]
  (min, avg, max) = (10.616, 10.634, 10.665), stdev = 0.028
  CI (99.9%): [10.132, 11.135] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:39
# Fork: 1 of 1
# Warmup Iteration   1: 4.077 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.625 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.576 ±(99.9%) 0.005 ms/op
Iteration   1: 2.631 ±(99.9%) 0.004 ms/op
Iteration   2: 2.563 ±(99.9%) 0.005 ms/op
Iteration   3: 2.525 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.573 ±(99.9%) 0.980 ms/op [Average]
  (min, avg, max) = (2.525, 2.573, 2.631), stdev = 0.054
  CI (99.9%): [1.593, 3.553] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:34
# Fork: 1 of 1
# Warmup Iteration   1: 3.882 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.523 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.496 ±(99.9%) 0.004 ms/op
Iteration   1: 2.481 ±(99.9%) 0.004 ms/op
Iteration   2: 2.477 ±(99.9%) 0.005 ms/op
Iteration   3: 2.464 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.474 ±(99.9%) 0.167 ms/op [Average]
  (min, avg, max) = (2.464, 2.474, 2.481), stdev = 0.009
  CI (99.9%): [2.308, 2.641] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:29
# Fork: 1 of 1
# Warmup Iteration   1: 4.109 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.618 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.556 ±(99.9%) 0.004 ms/op
Iteration   1: 2.540 ±(99.9%) 0.004 ms/op
Iteration   2: 2.572 ±(99.9%) 0.005 ms/op
Iteration   3: 2.550 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.554 ±(99.9%) 0.298 ms/op [Average]
  (min, avg, max) = (2.540, 2.554, 2.572), stdev = 0.016
  CI (99.9%): [2.256, 2.853] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 4.789 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.079 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.056 ±(99.9%) 0.005 ms/op
Iteration   1: 3.056 ±(99.9%) 0.005 ms/op
Iteration   2: 3.038 ±(99.9%) 0.007 ms/op
Iteration   3: 3.027 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.040 ±(99.9%) 0.267 ms/op [Average]
  (min, avg, max) = (3.027, 3.040, 3.056), stdev = 0.015
  CI (99.9%): [2.773, 3.308] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:19
# Fork: 1 of 1
# Warmup Iteration   1: 4.350 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.685 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.560 ±(99.9%) 0.006 ms/op
Iteration   1: 2.541 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.878 ms/op
                 createUser·p0.50:   2.605 ms/op
                 createUser·p0.90:   3.084 ms/op
                 createUser·p0.95:   3.199 ms/op
                 createUser·p0.99:   3.727 ms/op
                 createUser·p0.999:  11.622 ms/op
                 createUser·p0.9999: 13.402 ms/op
                 createUser·p1.00:   14.172 ms/op

Iteration   2: 2.557 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.852 ms/op
                 createUser·p0.50:   2.609 ms/op
                 createUser·p0.90:   3.109 ms/op
                 createUser·p0.95:   3.248 ms/op
                 createUser·p0.99:   3.998 ms/op
                 createUser·p0.999:  8.846 ms/op
                 createUser·p0.9999: 13.951 ms/op
                 createUser·p1.00:   14.713 ms/op

Iteration   3: 2.561 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.894 ms/op
                 createUser·p0.50:   2.613 ms/op
                 createUser·p0.90:   3.121 ms/op
                 createUser·p0.95:   3.236 ms/op
                 createUser·p0.99:   3.727 ms/op
                 createUser·p0.999:  8.360 ms/op
                 createUser·p0.9999: 10.699 ms/op
                 createUser·p1.00:   13.124 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 375655
  mean =      2.553 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 57 
    [ 1.250,  2.500) = 179655 
    [ 2.500,  3.750) = 191688 
    [ 3.750,  5.000) = 3440 
    [ 5.000,  6.250) = 417 
    [ 6.250,  7.500) = 10 
    [ 7.500,  8.750) = 24 
    [ 8.750, 10.000) = 83 
    [10.000, 11.250) = 107 
    [11.250, 12.500) = 76 
    [12.500, 13.750) = 75 
    [13.750, 15.000) = 23 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.852 ms/op
     p(50.0000) =      2.609 ms/op
     p(90.0000) =      3.105 ms/op
     p(95.0000) =      3.228 ms/op
     p(99.0000) =      3.817 ms/op
     p(99.9000) =      8.405 ms/op
     p(99.9900) =     13.376 ms/op
     p(99.9990) =     14.110 ms/op
     p(99.9999) =     14.713 ms/op
    p(100.0000) =     14.713 ms/op


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
# Warmup Iteration   1: 3.781 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.512 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.474 ±(99.9%) 0.005 ms/op
Iteration   1: 2.482 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.993 ms/op
                 existUser·p0.50:   2.507 ms/op
                 existUser·p0.90:   3.035 ms/op
                 existUser·p0.95:   3.154 ms/op
                 existUser·p0.99:   3.768 ms/op
                 existUser·p0.999:  5.547 ms/op
                 existUser·p0.9999: 13.797 ms/op
                 existUser·p1.00:   14.221 ms/op

Iteration   2: 2.468 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.081 ms/op
                 existUser·p0.50:   2.544 ms/op
                 existUser·p0.90:   2.986 ms/op
                 existUser·p0.95:   3.080 ms/op
                 existUser·p0.99:   3.547 ms/op
                 existUser·p0.999:  7.892 ms/op
                 existUser·p0.9999: 13.518 ms/op
                 existUser·p1.00:   13.713 ms/op

Iteration   3: 2.515 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.752 ms/op
                 existUser·p0.50:   2.568 ms/op
                 existUser·p0.90:   3.056 ms/op
                 existUser·p0.95:   3.195 ms/op
                 existUser·p0.99:   4.211 ms/op
                 existUser·p0.999:  8.847 ms/op
                 existUser·p0.9999: 11.954 ms/op
                 existUser·p1.00:   12.517 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 385406
  mean =      2.488 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 33 
    [ 1.250,  2.500) = 189911 
    [ 2.500,  3.750) = 191121 
    [ 3.750,  5.000) = 3404 
    [ 5.000,  6.250) = 477 
    [ 6.250,  7.500) = 39 
    [ 7.500,  8.750) = 76 
    [ 8.750, 10.000) = 72 
    [10.000, 11.250) = 64 
    [11.250, 12.500) = 70 
    [12.500, 13.750) = 125 
    [13.750, 15.000) = 14 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.752 ms/op
     p(50.0000) =      2.535 ms/op
     p(90.0000) =      3.027 ms/op
     p(95.0000) =      3.142 ms/op
     p(99.0000) =      3.830 ms/op
     p(99.9000) =      8.454 ms/op
     p(99.9900) =     13.426 ms/op
     p(99.9990) =     14.076 ms/op
     p(99.9999) =     14.221 ms/op
    p(100.0000) =     14.221 ms/op


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
# Warmup Iteration   1: 4.253 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.576 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.501 ±(99.9%) 0.005 ms/op
Iteration   1: 2.523 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.884 ms/op
                 getUser·p0.50:   2.544 ms/op
                 getUser·p0.90:   3.072 ms/op
                 getUser·p0.95:   3.203 ms/op
                 getUser·p0.99:   3.920 ms/op
                 getUser·p0.999:  11.506 ms/op
                 getUser·p0.9999: 13.599 ms/op
                 getUser·p1.00:   14.680 ms/op

Iteration   2: 2.519 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.969 ms/op
                 getUser·p0.50:   2.511 ms/op
                 getUser·p0.90:   3.080 ms/op
                 getUser·p0.95:   3.219 ms/op
                 getUser·p0.99:   4.010 ms/op
                 getUser·p0.999:  10.045 ms/op
                 getUser·p0.9999: 13.969 ms/op
                 getUser·p1.00:   14.549 ms/op

Iteration   3: 2.497 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.419 ms/op
                 getUser·p0.50:   2.494 ms/op
                 getUser·p0.90:   3.047 ms/op
                 getUser·p0.95:   3.162 ms/op
                 getUser·p0.99:   3.666 ms/op
                 getUser·p0.999:  8.573 ms/op
                 getUser·p0.9999: 11.325 ms/op
                 getUser·p1.00:   11.518 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 381686
  mean =      2.513 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 105 
    [ 1.250,  2.500) = 189522 
    [ 2.500,  3.750) = 187449 
    [ 3.750,  5.000) = 3542 
    [ 5.000,  6.250) = 576 
    [ 6.250,  7.500) = 78 
    [ 7.500,  8.750) = 31 
    [ 8.750, 10.000) = 71 
    [10.000, 11.250) = 104 
    [11.250, 12.500) = 95 
    [12.500, 13.750) = 85 
    [13.750, 15.000) = 28 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.419 ms/op
     p(50.0000) =      2.515 ms/op
     p(90.0000) =      3.064 ms/op
     p(95.0000) =      3.195 ms/op
     p(99.0000) =      3.871 ms/op
     p(99.9000) =      8.798 ms/op
     p(99.9900) =     13.500 ms/op
     p(99.9990) =     14.522 ms/op
     p(99.9999) =     14.680 ms/op
    p(100.0000) =     14.680 ms/op


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
# Warmup Iteration   1: 4.790 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 3.080 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.022 ±(99.9%) 0.009 ms/op
Iteration   1: 2.993 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.954 ms/op
                 listUser·p0.50:   2.937 ms/op
                 listUser·p0.90:   3.858 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   5.628 ms/op
                 listUser·p0.999:  9.716 ms/op
                 listUser·p0.9999: 11.829 ms/op
                 listUser·p1.00:   12.534 ms/op

Iteration   2: 2.989 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.951 ms/op
                 listUser·p0.50:   2.929 ms/op
                 listUser·p0.90:   3.863 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   5.513 ms/op
                 listUser·p0.999:  10.043 ms/op
                 listUser·p0.9999: 13.019 ms/op
                 listUser·p1.00:   13.353 ms/op

Iteration   3: 2.997 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.835 ms/op
                 listUser·p0.50:   2.941 ms/op
                 listUser·p0.90:   3.867 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   5.448 ms/op
                 listUser·p0.999:  9.716 ms/op
                 listUser·p0.9999: 11.966 ms/op
                 listUser·p1.00:   13.124 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 320422
  mean =      2.993 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 119 
    [ 1.250,  2.500) = 96646 
    [ 2.500,  3.750) = 185709 
    [ 3.750,  5.000) = 31144 
    [ 5.000,  6.250) = 5657 
    [ 6.250,  7.500) = 504 
    [ 7.500,  8.750) = 139 
    [ 8.750, 10.000) = 233 
    [10.000, 11.250) = 166 
    [11.250, 12.500) = 64 
    [12.500, 13.750) = 41 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.835 ms/op
     p(50.0000) =      2.937 ms/op
     p(90.0000) =      3.863 ms/op
     p(95.0000) =      4.366 ms/op
     p(99.0000) =      5.530 ms/op
     p(99.9000) =      9.758 ms/op
     p(99.9900) =     12.632 ms/op
     p(99.9990) =     13.189 ms/op
     p(99.9999) =     13.353 ms/op
    p(100.0000) =     13.353 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.363 ± 1.331  ops/ms
ClientPb.existUser                       thrpt       3  13.023 ± 1.870  ops/ms
ClientPb.getUser                         thrpt       3  12.865 ± 1.540  ops/ms
ClientPb.listUser                        thrpt       3  10.634 ± 0.502  ops/ms
ClientPb.createUser                       avgt       3   2.573 ± 0.980   ms/op
ClientPb.existUser                        avgt       3   2.474 ± 0.167   ms/op
ClientPb.getUser                          avgt       3   2.554 ± 0.298   ms/op
ClientPb.listUser                         avgt       3   3.040 ± 0.267   ms/op
ClientPb.createUser                     sample  375655   2.553 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.852           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.609           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.105           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.228           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.817           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.405           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.376           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.713           ms/op
ClientPb.existUser                      sample  385406   2.488 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.752           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.535           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.027           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.142           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.830           ms/op
ClientPb.existUser:existUser·p0.999     sample           8.454           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.426           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.221           ms/op
ClientPb.getUser                        sample  381686   2.513 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.419           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.515           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.064           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.195           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.871           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.798           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.500           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.680           ms/op
ClientPb.listUser                       sample  320422   2.993 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.835           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.937           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.863           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.366           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.530           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.758           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.632           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.353           ms/op
