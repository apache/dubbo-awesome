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
# Warmup Iteration   1: 4.982 ops/ms
# Warmup Iteration   2: 12.109 ops/ms
# Warmup Iteration   3: 12.223 ops/ms
Iteration   1: 12.458 ops/ms
Iteration   2: 12.584 ops/ms
Iteration   3: 12.540 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.527 ±(99.9%) 1.163 ops/ms [Average]
  (min, avg, max) = (12.458, 12.527, 12.584), stdev = 0.064
  CI (99.9%): [11.364, 13.691] (assumes normal distribution)


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
# Warmup Iteration   1: 8.329 ops/ms
# Warmup Iteration   2: 13.123 ops/ms
# Warmup Iteration   3: 13.150 ops/ms
Iteration   1: 13.096 ops/ms
Iteration   2: 13.068 ops/ms
Iteration   3: 12.964 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.043 ±(99.9%) 1.266 ops/ms [Average]
  (min, avg, max) = (12.964, 13.043, 13.096), stdev = 0.069
  CI (99.9%): [11.776, 14.309] (assumes normal distribution)


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
# Warmup Iteration   1: 7.257 ops/ms
# Warmup Iteration   2: 12.449 ops/ms
# Warmup Iteration   3: 12.751 ops/ms
Iteration   1: 12.737 ops/ms
Iteration   2: 12.791 ops/ms
Iteration   3: 12.862 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.797 ±(99.9%) 1.142 ops/ms [Average]
  (min, avg, max) = (12.737, 12.797, 12.862), stdev = 0.063
  CI (99.9%): [11.655, 13.938] (assumes normal distribution)


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
# Warmup Iteration   1: 6.772 ops/ms
# Warmup Iteration   2: 10.371 ops/ms
# Warmup Iteration   3: 10.457 ops/ms
Iteration   1: 10.521 ops/ms
Iteration   2: 10.575 ops/ms
Iteration   3: 10.549 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.548 ±(99.9%) 0.493 ops/ms [Average]
  (min, avg, max) = (10.521, 10.548, 10.575), stdev = 0.027
  CI (99.9%): [10.056, 11.041] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.972 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.544 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.489 ±(99.9%) 0.004 ms/op
Iteration   1: 2.500 ±(99.9%) 0.004 ms/op
Iteration   2: 2.549 ±(99.9%) 0.004 ms/op
Iteration   3: 2.480 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.510 ±(99.9%) 0.650 ms/op [Average]
  (min, avg, max) = (2.480, 2.510, 2.549), stdev = 0.036
  CI (99.9%): [1.860, 3.160] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.608 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.438 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.451 ±(99.9%) 0.004 ms/op
Iteration   1: 2.459 ±(99.9%) 0.003 ms/op
Iteration   2: 2.412 ±(99.9%) 0.004 ms/op
Iteration   3: 2.410 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.427 ±(99.9%) 0.510 ms/op [Average]
  (min, avg, max) = (2.410, 2.427, 2.459), stdev = 0.028
  CI (99.9%): [1.917, 2.936] (assumes normal distribution)


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
# Warmup Iteration   1: 3.688 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.505 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.524 ±(99.9%) 0.004 ms/op
Iteration   1: 2.511 ±(99.9%) 0.004 ms/op
Iteration   2: 2.485 ±(99.9%) 0.004 ms/op
Iteration   3: 2.467 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.488 ±(99.9%) 0.406 ms/op [Average]
  (min, avg, max) = (2.467, 2.488, 2.511), stdev = 0.022
  CI (99.9%): [2.082, 2.894] (assumes normal distribution)


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
# Warmup Iteration   1: 4.467 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.031 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.991 ±(99.9%) 0.006 ms/op
Iteration   1: 2.980 ±(99.9%) 0.005 ms/op
Iteration   2: 2.993 ±(99.9%) 0.005 ms/op
Iteration   3: 2.967 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.980 ±(99.9%) 0.242 ms/op [Average]
  (min, avg, max) = (2.967, 2.980, 2.993), stdev = 0.013
  CI (99.9%): [2.738, 3.222] (assumes normal distribution)


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
# Warmup Iteration   1: 4.088 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.634 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.502 ±(99.9%) 0.005 ms/op
Iteration   1: 2.486 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.978 ms/op
                 createUser·p0.50:   2.585 ms/op
                 createUser·p0.90:   3.006 ms/op
                 createUser·p0.95:   3.101 ms/op
                 createUser·p0.99:   3.593 ms/op
                 createUser·p0.999:  8.536 ms/op
                 createUser·p0.9999: 14.376 ms/op
                 createUser·p1.00:   16.351 ms/op

Iteration   2: 2.512 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.996 ms/op
                 createUser·p0.50:   2.601 ms/op
                 createUser·p0.90:   3.043 ms/op
                 createUser·p0.95:   3.154 ms/op
                 createUser·p0.99:   3.777 ms/op
                 createUser·p0.999:  9.499 ms/op
                 createUser·p0.9999: 12.616 ms/op
                 createUser·p1.00:   12.960 ms/op

Iteration   3: 2.509 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.938 ms/op
                 createUser·p0.50:   2.568 ms/op
                 createUser·p0.90:   3.052 ms/op
                 createUser·p0.95:   3.170 ms/op
                 createUser·p0.99:   3.772 ms/op
                 createUser·p0.999:  8.765 ms/op
                 createUser·p0.9999: 11.751 ms/op
                 createUser·p1.00:   14.287 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 383317
  mean =      2.503 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 39 
    [ 1.250,  2.500) = 185091 
    [ 2.500,  3.750) = 194576 
    [ 3.750,  5.000) = 2886 
    [ 5.000,  6.250) = 301 
    [ 6.250,  7.500) = 13 
    [ 7.500,  8.750) = 26 
    [ 8.750, 10.000) = 61 
    [10.000, 11.250) = 120 
    [11.250, 12.500) = 81 
    [12.500, 13.750) = 81 
    [13.750, 15.000) = 34 
    [15.000, 16.250) = 7 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.938 ms/op
     p(50.0000) =      2.585 ms/op
     p(90.0000) =      3.035 ms/op
     p(95.0000) =      3.142 ms/op
     p(99.0000) =      3.711 ms/op
     p(99.9000) =      8.765 ms/op
     p(99.9900) =     13.861 ms/op
     p(99.9990) =     16.081 ms/op
     p(99.9999) =     16.351 ms/op
    p(100.0000) =     16.351 ms/op


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
# Warmup Iteration   1: 3.574 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 2.493 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.466 ±(99.9%) 0.005 ms/op
Iteration   1: 2.453 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.053 ms/op
                 existUser·p0.50:   2.535 ms/op
                 existUser·p0.90:   2.970 ms/op
                 existUser·p0.95:   3.068 ms/op
                 existUser·p0.99:   3.531 ms/op
                 existUser·p0.999:  7.931 ms/op
                 existUser·p0.9999: 15.892 ms/op
                 existUser·p1.00:   16.876 ms/op

Iteration   2: 2.457 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.053 ms/op
                 existUser·p0.50:   2.556 ms/op
                 existUser·p0.90:   2.982 ms/op
                 existUser·p0.95:   3.080 ms/op
                 existUser·p0.99:   3.654 ms/op
                 existUser·p0.999:  7.720 ms/op
                 existUser·p0.9999: 13.335 ms/op
                 existUser·p1.00:   14.451 ms/op

Iteration   3: 2.464 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.885 ms/op
                 existUser·p0.50:   2.576 ms/op
                 existUser·p0.90:   2.986 ms/op
                 existUser·p0.95:   3.080 ms/op
                 existUser·p0.99:   3.609 ms/op
                 existUser·p0.999:  6.654 ms/op
                 existUser·p0.9999: 12.567 ms/op
                 existUser·p1.00:   13.713 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 390146
  mean =      2.458 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 26 
    [ 1.250,  2.500) = 190849 
    [ 2.500,  3.750) = 196237 
    [ 3.750,  5.000) = 2246 
    [ 5.000,  6.250) = 352 
    [ 6.250,  7.500) = 61 
    [ 7.500,  8.750) = 59 
    [ 8.750, 10.000) = 70 
    [10.000, 11.250) = 49 
    [11.250, 12.500) = 65 
    [12.500, 13.750) = 55 
    [13.750, 15.000) = 43 
    [15.000, 16.250) = 33 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.885 ms/op
     p(50.0000) =      2.556 ms/op
     p(90.0000) =      2.978 ms/op
     p(95.0000) =      3.076 ms/op
     p(99.0000) =      3.600 ms/op
     p(99.9000) =      6.726 ms/op
     p(99.9900) =     14.860 ms/op
     p(99.9990) =     16.105 ms/op
     p(99.9999) =     16.876 ms/op
    p(100.0000) =     16.876 ms/op


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
# Warmup Iteration   1: 4.178 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.608 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.510 ±(99.9%) 0.006 ms/op
Iteration   1: 2.511 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.976 ms/op
                 getUser·p0.50:   2.535 ms/op
                 getUser·p0.90:   3.056 ms/op
                 getUser·p0.95:   3.162 ms/op
                 getUser·p0.99:   3.678 ms/op
                 getUser·p0.999:  11.764 ms/op
                 getUser·p0.9999: 15.536 ms/op
                 getUser·p1.00:   17.334 ms/op

Iteration   2: 2.509 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.842 ms/op
                 getUser·p0.50:   2.548 ms/op
                 getUser·p0.90:   3.043 ms/op
                 getUser·p0.95:   3.150 ms/op
                 getUser·p0.99:   3.752 ms/op
                 getUser·p0.999:  10.225 ms/op
                 getUser·p0.9999: 13.795 ms/op
                 getUser·p1.00:   14.205 ms/op

Iteration   3: 2.499 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.963 ms/op
                 getUser·p0.50:   2.507 ms/op
                 getUser·p0.90:   3.039 ms/op
                 getUser·p0.95:   3.138 ms/op
                 getUser·p0.99:   3.768 ms/op
                 getUser·p0.999:  8.536 ms/op
                 getUser·p0.9999: 10.260 ms/op
                 getUser·p1.00:   10.568 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 382661
  mean =      2.506 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 47 
    [ 1.250,  2.500) = 189625 
    [ 2.500,  3.750) = 189303 
    [ 3.750,  5.000) = 2911 
    [ 5.000,  6.250) = 314 
    [ 6.250,  7.500) = 72 
    [ 7.500,  8.750) = 21 
    [ 8.750, 10.000) = 86 
    [10.000, 11.250) = 56 
    [11.250, 12.500) = 79 
    [12.500, 13.750) = 101 
    [13.750, 15.000) = 14 
    [15.000, 16.250) = 29 
    [16.250, 17.500) = 3 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.842 ms/op
     p(50.0000) =      2.527 ms/op
     p(90.0000) =      3.047 ms/op
     p(95.0000) =      3.150 ms/op
     p(99.0000) =      3.727 ms/op
     p(99.9000) =      8.602 ms/op
     p(99.9900) =     13.857 ms/op
     p(99.9990) =     16.335 ms/op
     p(99.9999) =     17.334 ms/op
    p(100.0000) =     17.334 ms/op


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
# Warmup Iteration   1: 4.611 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.072 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.004 ±(99.9%) 0.008 ms/op
Iteration   1: 2.984 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.999 ms/op
                 listUser·p0.50:   2.920 ms/op
                 listUser·p0.90:   3.850 ms/op
                 listUser·p0.95:   4.334 ms/op
                 listUser·p0.99:   5.628 ms/op
                 listUser·p0.999:  8.962 ms/op
                 listUser·p0.9999: 10.774 ms/op
                 listUser·p1.00:   11.059 ms/op

Iteration   2: 2.991 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.821 ms/op
                 listUser·p0.50:   2.929 ms/op
                 listUser·p0.90:   3.838 ms/op
                 listUser·p0.95:   4.325 ms/op
                 listUser·p0.99:   5.505 ms/op
                 listUser·p0.999:  9.325 ms/op
                 listUser·p0.9999: 10.753 ms/op
                 listUser·p1.00:   11.846 ms/op

Iteration   3: 2.975 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.828 ms/op
                 listUser·p0.50:   2.916 ms/op
                 listUser·p0.90:   3.826 ms/op
                 listUser·p0.95:   4.334 ms/op
                 listUser·p0.99:   5.489 ms/op
                 listUser·p0.999:  9.315 ms/op
                 listUser·p0.9999: 11.633 ms/op
                 listUser·p1.00:   11.944 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 321441
  mean =      2.984 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 142 
    [ 1.250,  2.500) = 95706 
    [ 2.500,  3.750) = 188923 
    [ 3.750,  5.000) = 29873 
    [ 5.000,  6.250) = 5480 
    [ 6.250,  7.500) = 627 
    [ 7.500,  8.750) = 292 
    [ 8.750, 10.000) = 258 
    [10.000, 11.250) = 113 
    [11.250, 12.500) = 27 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.821 ms/op
     p(50.0000) =      2.920 ms/op
     p(90.0000) =      3.838 ms/op
     p(95.0000) =      4.334 ms/op
     p(99.0000) =      5.538 ms/op
     p(99.9000) =      9.241 ms/op
     p(99.9900) =     11.043 ms/op
     p(99.9990) =     11.826 ms/op
     p(99.9999) =     11.944 ms/op
    p(100.0000) =     11.944 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.527 ± 1.163  ops/ms
ClientPb.existUser                       thrpt       3  13.043 ± 1.266  ops/ms
ClientPb.getUser                         thrpt       3  12.797 ± 1.142  ops/ms
ClientPb.listUser                        thrpt       3  10.548 ± 0.493  ops/ms
ClientPb.createUser                       avgt       3   2.510 ± 0.650   ms/op
ClientPb.existUser                        avgt       3   2.427 ± 0.510   ms/op
ClientPb.getUser                          avgt       3   2.488 ± 0.406   ms/op
ClientPb.listUser                         avgt       3   2.980 ± 0.242   ms/op
ClientPb.createUser                     sample  383317   2.503 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.938           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.585           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.035           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.142           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.711           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.765           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.861           ms/op
ClientPb.createUser:createUser·p1.00    sample          16.351           ms/op
ClientPb.existUser                      sample  390146   2.458 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.885           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.556           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.978           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.076           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.600           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.726           ms/op
ClientPb.existUser:existUser·p0.9999    sample          14.860           ms/op
ClientPb.existUser:existUser·p1.00      sample          16.876           ms/op
ClientPb.getUser                        sample  382661   2.506 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.842           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.527           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.047           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.150           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.727           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.602           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.857           ms/op
ClientPb.getUser:getUser·p1.00          sample          17.334           ms/op
ClientPb.listUser                       sample  321441   2.984 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.821           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.920           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.838           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.334           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.538           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.241           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.043           ms/op
ClientPb.listUser:listUser·p1.00        sample          11.944           ms/op
