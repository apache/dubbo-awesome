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
# Warmup Iteration   1: 4.851 ops/ms
# Warmup Iteration   2: 12.300 ops/ms
# Warmup Iteration   3: 12.783 ops/ms
Iteration   1: 12.829 ops/ms
Iteration   2: 12.864 ops/ms
Iteration   3: 13.051 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.915 ±(99.9%) 2.182 ops/ms [Average]
  (min, avg, max) = (12.829, 12.915, 13.051), stdev = 0.120
  CI (99.9%): [10.733, 15.096] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:53
# Fork: 1 of 1
# Warmup Iteration   1: 8.357 ops/ms
# Warmup Iteration   2: 13.168 ops/ms
# Warmup Iteration   3: 13.209 ops/ms
Iteration   1: 12.980 ops/ms
Iteration   2: 13.203 ops/ms
Iteration   3: 13.037 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.073 ±(99.9%) 2.119 ops/ms [Average]
  (min, avg, max) = (12.980, 13.073, 13.203), stdev = 0.116
  CI (99.9%): [10.955, 15.192] (assumes normal distribution)


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
# Warmup Iteration   1: 7.607 ops/ms
# Warmup Iteration   2: 12.663 ops/ms
# Warmup Iteration   3: 12.773 ops/ms
Iteration   1: 12.748 ops/ms
Iteration   2: 13.018 ops/ms
Iteration   3: 13.123 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.963 ±(99.9%) 3.538 ops/ms [Average]
  (min, avg, max) = (12.748, 12.963, 13.123), stdev = 0.194
  CI (99.9%): [9.425, 16.501] (assumes normal distribution)


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
# Warmup Iteration   1: 6.636 ops/ms
# Warmup Iteration   2: 10.594 ops/ms
# Warmup Iteration   3: 10.703 ops/ms
Iteration   1: 10.784 ops/ms
Iteration   2: 10.791 ops/ms
Iteration   3: 10.764 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.780 ±(99.9%) 0.255 ops/ms [Average]
  (min, avg, max) = (10.764, 10.780, 10.791), stdev = 0.014
  CI (99.9%): [10.525, 11.035] (assumes normal distribution)


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
# Warmup Iteration   1: 3.932 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 2.555 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.501 ±(99.9%) 0.003 ms/op
Iteration   1: 2.528 ±(99.9%) 0.003 ms/op
Iteration   2: 2.551 ±(99.9%) 0.003 ms/op
Iteration   3: 2.547 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.542 ±(99.9%) 0.222 ms/op [Average]
  (min, avg, max) = (2.528, 2.542, 2.551), stdev = 0.012
  CI (99.9%): [2.320, 2.764] (assumes normal distribution)


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
# Warmup Iteration   1: 3.743 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.453 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.413 ±(99.9%) 0.003 ms/op
Iteration   1: 2.397 ±(99.9%) 0.003 ms/op
Iteration   2: 2.426 ±(99.9%) 0.005 ms/op
Iteration   3: 2.428 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.417 ±(99.9%) 0.315 ms/op [Average]
  (min, avg, max) = (2.397, 2.417, 2.428), stdev = 0.017
  CI (99.9%): [2.102, 2.732] (assumes normal distribution)


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
# Warmup Iteration   1: 3.679 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.562 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.474 ±(99.9%) 0.003 ms/op
Iteration   1: 2.467 ±(99.9%) 0.004 ms/op
Iteration   2: 2.467 ±(99.9%) 0.004 ms/op
Iteration   3: 2.509 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.481 ±(99.9%) 0.439 ms/op [Average]
  (min, avg, max) = (2.467, 2.481, 2.509), stdev = 0.024
  CI (99.9%): [2.042, 2.920] (assumes normal distribution)


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
# Warmup Iteration   1: 4.642 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.022 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.008 ±(99.9%) 0.006 ms/op
Iteration   1: 3.028 ±(99.9%) 0.006 ms/op
Iteration   2: 3.011 ±(99.9%) 0.006 ms/op
Iteration   3: 3.007 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.015 ±(99.9%) 0.199 ms/op [Average]
  (min, avg, max) = (3.007, 3.015, 3.028), stdev = 0.011
  CI (99.9%): [2.816, 3.214] (assumes normal distribution)


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
# Warmup Iteration   1: 4.121 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 2.679 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.505 ±(99.9%) 0.005 ms/op
Iteration   1: 2.497 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.843 ms/op
                 createUser·p0.50:   2.556 ms/op
                 createUser·p0.90:   3.031 ms/op
                 createUser·p0.95:   3.142 ms/op
                 createUser·p0.99:   3.628 ms/op
                 createUser·p0.999:  12.369 ms/op
                 createUser·p0.9999: 13.697 ms/op
                 createUser·p1.00:   14.303 ms/op

Iteration   2: 2.510 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.987 ms/op
                 createUser·p0.50:   2.593 ms/op
                 createUser·p0.90:   3.052 ms/op
                 createUser·p0.95:   3.166 ms/op
                 createUser·p0.99:   3.678 ms/op
                 createUser·p0.999:  10.255 ms/op
                 createUser·p0.9999: 13.308 ms/op
                 createUser·p1.00:   14.008 ms/op

Iteration   3: 2.496 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.814 ms/op
                 createUser·p0.50:   2.568 ms/op
                 createUser·p0.90:   3.031 ms/op
                 createUser·p0.95:   3.158 ms/op
                 createUser·p0.99:   3.727 ms/op
                 createUser·p0.999:  8.339 ms/op
                 createUser·p0.9999: 10.666 ms/op
                 createUser·p1.00:   11.174 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 383483
  mean =      2.501 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 59 
    [ 1.250,  2.500) = 184790 
    [ 2.500,  3.750) = 195326 
    [ 3.750,  5.000) = 2581 
    [ 5.000,  6.250) = 228 
    [ 6.250,  7.500) = 64 
    [ 7.500,  8.750) = 27 
    [ 8.750, 10.000) = 67 
    [10.000, 11.250) = 118 
    [11.250, 12.500) = 78 
    [12.500, 13.750) = 125 
    [13.750, 15.000) = 20 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.814 ms/op
     p(50.0000) =      2.572 ms/op
     p(90.0000) =      3.039 ms/op
     p(95.0000) =      3.154 ms/op
     p(99.0000) =      3.678 ms/op
     p(99.9000) =      9.413 ms/op
     p(99.9900) =     13.418 ms/op
     p(99.9990) =     14.137 ms/op
     p(99.9999) =     14.303 ms/op
    p(100.0000) =     14.303 ms/op


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
# Warmup Iteration   1: 3.795 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.437 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.420 ±(99.9%) 0.005 ms/op
Iteration   1: 2.410 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.947 ms/op
                 existUser·p0.50:   2.474 ms/op
                 existUser·p0.90:   2.920 ms/op
                 existUser·p0.95:   3.011 ms/op
                 existUser·p0.99:   3.363 ms/op
                 existUser·p0.999:  5.240 ms/op
                 existUser·p0.9999: 14.807 ms/op
                 existUser·p1.00:   15.483 ms/op

Iteration   2: 2.411 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.947 ms/op
                 existUser·p0.50:   2.511 ms/op
                 existUser·p0.90:   2.920 ms/op
                 existUser·p0.95:   3.011 ms/op
                 existUser·p0.99:   3.404 ms/op
                 existUser·p0.999:  7.691 ms/op
                 existUser·p0.9999: 12.857 ms/op
                 existUser·p1.00:   13.664 ms/op

Iteration   3: 2.448 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.911 ms/op
                 existUser·p0.50:   2.474 ms/op
                 existUser·p0.90:   2.990 ms/op
                 existUser·p0.95:   3.105 ms/op
                 existUser·p0.99:   3.658 ms/op
                 existUser·p0.999:  8.831 ms/op
                 existUser·p0.9999: 11.416 ms/op
                 existUser·p1.00:   12.386 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 395840
  mean =      2.423 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 52 
    [ 1.250,  2.500) = 199113 
    [ 2.500,  3.750) = 194166 
    [ 3.750,  5.000) = 1919 
    [ 5.000,  6.250) = 178 
    [ 6.250,  7.500) = 16 
    [ 7.500,  8.750) = 32 
    [ 8.750, 10.000) = 108 
    [10.000, 11.250) = 108 
    [11.250, 12.500) = 60 
    [12.500, 13.750) = 51 
    [13.750, 15.000) = 29 
    [15.000, 16.250) = 8 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.911 ms/op
     p(50.0000) =      2.486 ms/op
     p(90.0000) =      2.945 ms/op
     p(95.0000) =      3.043 ms/op
     p(99.0000) =      3.494 ms/op
     p(99.9000) =      7.603 ms/op
     p(99.9900) =     13.607 ms/op
     p(99.9990) =     15.417 ms/op
     p(99.9999) =     15.483 ms/op
    p(100.0000) =     15.483 ms/op


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
# Warmup Iteration   1: 3.847 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.539 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.431 ±(99.9%) 0.005 ms/op
Iteration   1: 2.433 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.952 ms/op
                 getUser·p0.50:   2.445 ms/op
                 getUser·p0.90:   2.970 ms/op
                 getUser·p0.95:   3.097 ms/op
                 getUser·p0.99:   3.748 ms/op
                 getUser·p0.999:  5.562 ms/op
                 getUser·p0.9999: 15.544 ms/op
                 getUser·p1.00:   16.384 ms/op

Iteration   2: 2.486 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.994 ms/op
                 getUser·p0.50:   2.515 ms/op
                 getUser·p0.90:   3.011 ms/op
                 getUser·p0.95:   3.170 ms/op
                 getUser·p0.99:   4.278 ms/op
                 getUser·p0.999:  10.338 ms/op
                 getUser·p0.9999: 13.550 ms/op
                 getUser·p1.00:   13.828 ms/op

Iteration   3: 2.444 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.954 ms/op
                 getUser·p0.50:   2.466 ms/op
                 getUser·p0.90:   2.970 ms/op
                 getUser·p0.95:   3.092 ms/op
                 getUser·p0.99:   3.768 ms/op
                 getUser·p0.999:  6.962 ms/op
                 getUser·p0.9999: 14.959 ms/op
                 getUser·p1.00:   15.532 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 390826
  mean =      2.454 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 95 
    [ 1.250,  2.500) = 198000 
    [ 2.500,  3.750) = 187737 
    [ 3.750,  5.000) = 3813 
    [ 5.000,  6.250) = 571 
    [ 6.250,  7.500) = 99 
    [ 7.500,  8.750) = 98 
    [ 8.750, 10.000) = 45 
    [10.000, 11.250) = 122 
    [11.250, 12.500) = 77 
    [12.500, 13.750) = 71 
    [13.750, 15.000) = 48 
    [15.000, 16.250) = 49 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.952 ms/op
     p(50.0000) =      2.474 ms/op
     p(90.0000) =      2.986 ms/op
     p(95.0000) =      3.117 ms/op
     p(99.0000) =      3.924 ms/op
     p(99.9000) =      9.667 ms/op
     p(99.9900) =     15.106 ms/op
     p(99.9990) =     16.156 ms/op
     p(99.9999) =     16.384 ms/op
    p(100.0000) =     16.384 ms/op


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
# Warmup Iteration   1: 4.782 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.095 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.014 ±(99.9%) 0.008 ms/op
Iteration   1: 3.001 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.771 ms/op
                 listUser·p0.50:   2.941 ms/op
                 listUser·p0.90:   3.850 ms/op
                 listUser·p0.95:   4.342 ms/op
                 listUser·p0.99:   5.489 ms/op
                 listUser·p0.999:  9.887 ms/op
                 listUser·p0.9999: 11.420 ms/op
                 listUser·p1.00:   13.484 ms/op

Iteration   2: 3.019 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.945 ms/op
                 listUser·p0.50:   2.949 ms/op
                 listUser·p0.90:   3.916 ms/op
                 listUser·p0.95:   4.424 ms/op
                 listUser·p0.99:   5.546 ms/op
                 listUser·p0.999:  8.897 ms/op
                 listUser·p0.9999: 11.348 ms/op
                 listUser·p1.00:   11.911 ms/op

Iteration   3: 3.006 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.827 ms/op
                 listUser·p0.50:   2.933 ms/op
                 listUser·p0.90:   3.899 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   5.636 ms/op
                 listUser·p0.999:  9.421 ms/op
                 listUser·p0.9999: 11.470 ms/op
                 listUser·p1.00:   11.698 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 318803
  mean =      3.009 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 117 
    [ 1.250,  2.500) = 92024 
    [ 2.500,  3.750) = 187372 
    [ 3.750,  5.000) = 31947 
    [ 5.000,  6.250) = 6124 
    [ 6.250,  7.500) = 569 
    [ 7.500,  8.750) = 186 
    [ 8.750, 10.000) = 227 
    [10.000, 11.250) = 195 
    [11.250, 12.500) = 37 
    [12.500, 13.750) = 5 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.771 ms/op
     p(50.0000) =      2.941 ms/op
     p(90.0000) =      3.887 ms/op
     p(95.0000) =      4.391 ms/op
     p(99.0000) =      5.554 ms/op
     p(99.9000) =      9.732 ms/op
     p(99.9900) =     11.405 ms/op
     p(99.9990) =     13.243 ms/op
     p(99.9999) =     13.484 ms/op
    p(100.0000) =     13.484 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.915 ± 2.182  ops/ms
ClientPb.existUser                       thrpt       3  13.073 ± 2.119  ops/ms
ClientPb.getUser                         thrpt       3  12.963 ± 3.538  ops/ms
ClientPb.listUser                        thrpt       3  10.780 ± 0.255  ops/ms
ClientPb.createUser                       avgt       3   2.542 ± 0.222   ms/op
ClientPb.existUser                        avgt       3   2.417 ± 0.315   ms/op
ClientPb.getUser                          avgt       3   2.481 ± 0.439   ms/op
ClientPb.listUser                         avgt       3   3.015 ± 0.199   ms/op
ClientPb.createUser                     sample  383483   2.501 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.814           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.572           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.039           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.154           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.678           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.413           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.418           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.303           ms/op
ClientPb.existUser                      sample  395840   2.423 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.911           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.486           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.945           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.043           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.494           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.603           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.607           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.483           ms/op
ClientPb.getUser                        sample  390826   2.454 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.952           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.474           ms/op
ClientPb.getUser:getUser·p0.90          sample           2.986           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.117           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.924           ms/op
ClientPb.getUser:getUser·p0.999         sample           9.667           ms/op
ClientPb.getUser:getUser·p0.9999        sample          15.106           ms/op
ClientPb.getUser:getUser·p1.00          sample          16.384           ms/op
ClientPb.listUser                       sample  318803   3.009 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.771           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.941           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.887           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.391           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.554           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.732           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.405           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.484           ms/op
