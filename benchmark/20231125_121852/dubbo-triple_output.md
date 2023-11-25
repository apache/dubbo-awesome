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
# Warmup Iteration   1: 4.683 ops/ms
# Warmup Iteration   2: 12.139 ops/ms
# Warmup Iteration   3: 12.386 ops/ms
Iteration   1: 12.649 ops/ms
Iteration   2: 12.605 ops/ms
Iteration   3: 12.751 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.668 ±(99.9%) 1.367 ops/ms [Average]
  (min, avg, max) = (12.605, 12.668, 12.751), stdev = 0.075
  CI (99.9%): [11.301, 14.035] (assumes normal distribution)


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
# Warmup Iteration   1: 8.160 ops/ms
# Warmup Iteration   2: 12.854 ops/ms
# Warmup Iteration   3: 12.899 ops/ms
Iteration   1: 12.988 ops/ms
Iteration   2: 13.065 ops/ms
Iteration   3: 13.018 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.024 ±(99.9%) 0.711 ops/ms [Average]
  (min, avg, max) = (12.988, 13.024, 13.065), stdev = 0.039
  CI (99.9%): [12.313, 13.734] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:48
# Fork: 1 of 1
# Warmup Iteration   1: 7.990 ops/ms
# Warmup Iteration   2: 12.672 ops/ms
# Warmup Iteration   3: 12.659 ops/ms
Iteration   1: 12.872 ops/ms
Iteration   2: 12.750 ops/ms
Iteration   3: 12.803 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.808 ±(99.9%) 1.121 ops/ms [Average]
  (min, avg, max) = (12.750, 12.808, 12.872), stdev = 0.061
  CI (99.9%): [11.688, 13.929] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:43
# Fork: 1 of 1
# Warmup Iteration   1: 6.764 ops/ms
# Warmup Iteration   2: 10.468 ops/ms
# Warmup Iteration   3: 10.315 ops/ms
Iteration   1: 10.671 ops/ms
Iteration   2: 10.516 ops/ms
Iteration   3: 10.589 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.592 ±(99.9%) 1.413 ops/ms [Average]
  (min, avg, max) = (10.516, 10.592, 10.671), stdev = 0.077
  CI (99.9%): [9.179, 12.005] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 4.047 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.596 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.563 ±(99.9%) 0.004 ms/op
Iteration   1: 2.580 ±(99.9%) 0.005 ms/op
Iteration   2: 2.543 ±(99.9%) 0.004 ms/op
Iteration   3: 2.549 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.557 ±(99.9%) 0.368 ms/op [Average]
  (min, avg, max) = (2.543, 2.557, 2.580), stdev = 0.020
  CI (99.9%): [2.190, 2.925] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.816 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.482 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.468 ±(99.9%) 0.003 ms/op
Iteration   1: 2.497 ±(99.9%) 0.004 ms/op
Iteration   2: 2.512 ±(99.9%) 0.004 ms/op
Iteration   3: 2.490 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.500 ±(99.9%) 0.199 ms/op [Average]
  (min, avg, max) = (2.490, 2.500, 2.512), stdev = 0.011
  CI (99.9%): [2.301, 2.699] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.875 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.553 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.511 ±(99.9%) 0.004 ms/op
Iteration   1: 2.500 ±(99.9%) 0.004 ms/op
Iteration   2: 2.533 ±(99.9%) 0.004 ms/op
Iteration   3: 2.494 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.509 ±(99.9%) 0.381 ms/op [Average]
  (min, avg, max) = (2.494, 2.509, 2.533), stdev = 0.021
  CI (99.9%): [2.128, 2.889] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.698 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.036 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.994 ±(99.9%) 0.005 ms/op
Iteration   1: 2.977 ±(99.9%) 0.007 ms/op
Iteration   2: 2.975 ±(99.9%) 0.005 ms/op
Iteration   3: 2.986 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.979 ±(99.9%) 0.101 ms/op [Average]
  (min, avg, max) = (2.975, 2.979, 2.986), stdev = 0.006
  CI (99.9%): [2.879, 3.080] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.287 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 2.663 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.485 ±(99.9%) 0.005 ms/op
Iteration   1: 2.523 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.863 ms/op
                 createUser·p0.50:   2.568 ms/op
                 createUser·p0.90:   3.076 ms/op
                 createUser·p0.95:   3.228 ms/op
                 createUser·p0.99:   4.076 ms/op
                 createUser·p0.999:  12.190 ms/op
                 createUser·p0.9999: 13.855 ms/op
                 createUser·p1.00:   14.402 ms/op

Iteration   2: 2.476 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.992 ms/op
                 createUser·p0.50:   2.589 ms/op
                 createUser·p0.90:   2.982 ms/op
                 createUser·p0.95:   3.080 ms/op
                 createUser·p0.99:   3.682 ms/op
                 createUser·p0.999:  10.289 ms/op
                 createUser·p0.9999: 14.043 ms/op
                 createUser·p1.00:   16.335 ms/op

Iteration   3: 2.477 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.901 ms/op
                 createUser·p0.50:   2.544 ms/op
                 createUser·p0.90:   3.011 ms/op
                 createUser·p0.95:   3.125 ms/op
                 createUser·p0.99:   3.695 ms/op
                 createUser·p0.999:  8.585 ms/op
                 createUser·p0.9999: 11.898 ms/op
                 createUser·p1.00:   12.403 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 384864
  mean =      2.492 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 63 
    [ 1.250,  2.500) = 186154 
    [ 2.500,  3.750) = 194338 
    [ 3.750,  5.000) = 3140 
    [ 5.000,  6.250) = 618 
    [ 6.250,  7.500) = 67 
    [ 7.500,  8.750) = 94 
    [ 8.750, 10.000) = 98 
    [10.000, 11.250) = 47 
    [11.250, 12.500) = 92 
    [12.500, 13.750) = 115 
    [13.750, 15.000) = 28 
    [15.000, 16.250) = 9 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.863 ms/op
     p(50.0000) =      2.568 ms/op
     p(90.0000) =      3.019 ms/op
     p(95.0000) =      3.146 ms/op
     p(99.0000) =      3.826 ms/op
     p(99.9000) =      8.798 ms/op
     p(99.9900) =     13.755 ms/op
     p(99.9990) =     15.481 ms/op
     p(99.9999) =     16.335 ms/op
    p(100.0000) =     16.335 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.768 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.500 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.460 ±(99.9%) 0.005 ms/op
Iteration   1: 2.469 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.941 ms/op
                 existUser·p0.50:   2.515 ms/op
                 existUser·p0.90:   3.006 ms/op
                 existUser·p0.95:   3.125 ms/op
                 existUser·p0.99:   3.752 ms/op
                 existUser·p0.999:  7.602 ms/op
                 existUser·p0.9999: 13.961 ms/op
                 existUser·p1.00:   14.942 ms/op

Iteration   2: 2.459 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.947 ms/op
                 existUser·p0.50:   2.527 ms/op
                 existUser·p0.90:   2.982 ms/op
                 existUser·p0.95:   3.092 ms/op
                 existUser·p0.99:   3.763 ms/op
                 existUser·p0.999:  6.267 ms/op
                 existUser·p0.9999: 12.845 ms/op
                 existUser·p1.00:   13.107 ms/op

Iteration   3: 2.458 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.817 ms/op
                 existUser·p0.50:   2.548 ms/op
                 existUser·p0.90:   2.970 ms/op
                 existUser·p0.95:   3.084 ms/op
                 existUser·p0.99:   3.867 ms/op
                 existUser·p0.999:  8.233 ms/op
                 existUser·p0.9999: 11.907 ms/op
                 existUser·p1.00:   12.255 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 389577
  mean =      2.462 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 54 
    [ 1.250,  2.500) = 192289 
    [ 2.500,  3.750) = 193134 
    [ 3.750,  5.000) = 3104 
    [ 5.000,  6.250) = 556 
    [ 6.250,  7.500) = 56 
    [ 7.500,  8.750) = 32 
    [ 8.750, 10.000) = 59 
    [10.000, 11.250) = 101 
    [11.250, 12.500) = 68 
    [12.500, 13.750) = 92 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.817 ms/op
     p(50.0000) =      2.531 ms/op
     p(90.0000) =      2.986 ms/op
     p(95.0000) =      3.101 ms/op
     p(99.0000) =      3.789 ms/op
     p(99.9000) =      7.294 ms/op
     p(99.9900) =     13.567 ms/op
     p(99.9990) =     14.718 ms/op
     p(99.9999) =     14.942 ms/op
    p(100.0000) =     14.942 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.927 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.565 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.558 ±(99.9%) 0.006 ms/op
Iteration   1: 2.513 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.962 ms/op
                 getUser·p0.50:   2.531 ms/op
                 getUser·p0.90:   3.056 ms/op
                 getUser·p0.95:   3.183 ms/op
                 getUser·p0.99:   3.894 ms/op
                 getUser·p0.999:  11.764 ms/op
                 getUser·p0.9999: 13.718 ms/op
                 getUser·p1.00:   14.385 ms/op

Iteration   2: 2.542 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.969 ms/op
                 getUser·p0.50:   2.560 ms/op
                 getUser·p0.90:   3.097 ms/op
                 getUser·p0.95:   3.215 ms/op
                 getUser·p0.99:   3.940 ms/op
                 getUser·p0.999:  9.228 ms/op
                 getUser·p0.9999: 17.119 ms/op
                 getUser·p1.00:   17.367 ms/op

Iteration   3: 2.528 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.000 ms/op
                 getUser·p0.50:   2.531 ms/op
                 getUser·p0.90:   3.092 ms/op
                 getUser·p0.95:   3.232 ms/op
                 getUser·p0.99:   3.954 ms/op
                 getUser·p0.999:  8.049 ms/op
                 getUser·p0.9999: 9.799 ms/op
                 getUser·p1.00:   10.617 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 379478
  mean =      2.528 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 67 
    [ 1.250,  2.500) = 186790 
    [ 2.500,  3.750) = 187616 
    [ 3.750,  5.000) = 4062 
    [ 5.000,  6.250) = 505 
    [ 6.250,  7.500) = 46 
    [ 7.500,  8.750) = 49 
    [ 8.750, 10.000) = 89 
    [10.000, 11.250) = 55 
    [11.250, 12.500) = 49 
    [12.500, 13.750) = 109 
    [13.750, 15.000) = 9 
    [15.000, 16.250) = 6 
    [16.250, 17.500) = 26 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.962 ms/op
     p(50.0000) =      2.540 ms/op
     p(90.0000) =      3.080 ms/op
     p(95.0000) =      3.211 ms/op
     p(99.0000) =      3.932 ms/op
     p(99.9000) =      8.381 ms/op
     p(99.9900) =     13.813 ms/op
     p(99.9990) =     17.341 ms/op
     p(99.9999) =     17.367 ms/op
    p(100.0000) =     17.367 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.715 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.057 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.017 ±(99.9%) 0.009 ms/op
Iteration   1: 2.999 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.915 ms/op
                 listUser·p0.50:   2.933 ms/op
                 listUser·p0.90:   3.895 ms/op
                 listUser·p0.95:   4.424 ms/op
                 listUser·p0.99:   5.636 ms/op
                 listUser·p0.999:  8.936 ms/op
                 listUser·p0.9999: 11.627 ms/op
                 listUser·p1.00:   11.764 ms/op

Iteration   2: 2.989 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.677 ms/op
                 listUser·p0.50:   2.925 ms/op
                 listUser·p0.90:   3.875 ms/op
                 listUser·p0.95:   4.383 ms/op
                 listUser·p0.99:   5.530 ms/op
                 listUser·p0.999:  9.306 ms/op
                 listUser·p0.9999: 11.921 ms/op
                 listUser·p1.00:   12.206 ms/op

Iteration   3: 2.994 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.858 ms/op
                 listUser·p0.50:   2.937 ms/op
                 listUser·p0.90:   3.867 ms/op
                 listUser·p0.95:   4.342 ms/op
                 listUser·p0.99:   5.480 ms/op
                 listUser·p0.999:  9.693 ms/op
                 listUser·p0.9999: 10.786 ms/op
                 listUser·p1.00:   11.649 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 320337
  mean =      2.994 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 139 
    [ 1.250,  2.500) = 96307 
    [ 2.500,  3.750) = 185308 
    [ 3.750,  5.000) = 31552 
    [ 5.000,  6.250) = 5775 
    [ 6.250,  7.500) = 609 
    [ 7.500,  8.750) = 206 
    [ 8.750, 10.000) = 235 
    [10.000, 11.250) = 154 
    [11.250, 12.500) = 52 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.677 ms/op
     p(50.0000) =      2.933 ms/op
     p(90.0000) =      3.879 ms/op
     p(95.0000) =      4.383 ms/op
     p(99.0000) =      5.546 ms/op
     p(99.9000) =      9.317 ms/op
     p(99.9900) =     11.616 ms/op
     p(99.9990) =     12.131 ms/op
     p(99.9999) =     12.206 ms/op
    p(100.0000) =     12.206 ms/op


# Run complete. Total time: 00:13:01

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.668 ± 1.367  ops/ms
ClientPb.existUser                       thrpt       3  13.024 ± 0.711  ops/ms
ClientPb.getUser                         thrpt       3  12.808 ± 1.121  ops/ms
ClientPb.listUser                        thrpt       3  10.592 ± 1.413  ops/ms
ClientPb.createUser                       avgt       3   2.557 ± 0.368   ms/op
ClientPb.existUser                        avgt       3   2.500 ± 0.199   ms/op
ClientPb.getUser                          avgt       3   2.509 ± 0.381   ms/op
ClientPb.listUser                         avgt       3   2.979 ± 0.101   ms/op
ClientPb.createUser                     sample  384864   2.492 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.863           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.568           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.019           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.146           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.826           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.798           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.755           ms/op
ClientPb.createUser:createUser·p1.00    sample          16.335           ms/op
ClientPb.existUser                      sample  389577   2.462 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.817           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.531           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.986           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.101           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.789           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.294           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.567           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.942           ms/op
ClientPb.getUser                        sample  379478   2.528 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.962           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.540           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.080           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.211           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.932           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.381           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.813           ms/op
ClientPb.getUser:getUser·p1.00          sample          17.367           ms/op
ClientPb.listUser                       sample  320337   2.994 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.677           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.933           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.879           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.383           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.546           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.317           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.616           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.206           ms/op
