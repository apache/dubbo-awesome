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
# Warmup Iteration   1: 4.997 ops/ms
# Warmup Iteration   2: 12.278 ops/ms
# Warmup Iteration   3: 12.272 ops/ms
Iteration   1: 12.756 ops/ms
Iteration   2: 12.685 ops/ms
Iteration   3: 12.641 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.694 ±(99.9%) 1.064 ops/ms [Average]
  (min, avg, max) = (12.641, 12.694, 12.756), stdev = 0.058
  CI (99.9%): [11.630, 13.758] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:51
# Fork: 1 of 1
# Warmup Iteration   1: 8.313 ops/ms
# Warmup Iteration   2: 13.025 ops/ms
# Warmup Iteration   3: 12.798 ops/ms
Iteration   1: 12.915 ops/ms
Iteration   2: 12.986 ops/ms
Iteration   3: 12.899 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.933 ±(99.9%) 0.844 ops/ms [Average]
  (min, avg, max) = (12.899, 12.933, 12.986), stdev = 0.046
  CI (99.9%): [12.089, 13.777] (assumes normal distribution)


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
# Warmup Iteration   1: 7.586 ops/ms
# Warmup Iteration   2: 12.597 ops/ms
# Warmup Iteration   3: 12.809 ops/ms
Iteration   1: 12.924 ops/ms
Iteration   2: 12.884 ops/ms
Iteration   3: 12.852 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.887 ±(99.9%) 0.660 ops/ms [Average]
  (min, avg, max) = (12.852, 12.887, 12.924), stdev = 0.036
  CI (99.9%): [12.227, 13.547] (assumes normal distribution)


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
# Warmup Iteration   1: 7.050 ops/ms
# Warmup Iteration   2: 10.316 ops/ms
# Warmup Iteration   3: 10.689 ops/ms
Iteration   1: 10.700 ops/ms
Iteration   2: 10.573 ops/ms
Iteration   3: 10.639 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.637 ±(99.9%) 1.163 ops/ms [Average]
  (min, avg, max) = (10.573, 10.637, 10.700), stdev = 0.064
  CI (99.9%): [9.475, 11.800] (assumes normal distribution)


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
# Warmup Iteration   1: 3.887 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 2.596 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.491 ±(99.9%) 0.005 ms/op
Iteration   1: 2.519 ±(99.9%) 0.003 ms/op
Iteration   2: 2.570 ±(99.9%) 0.004 ms/op
Iteration   3: 2.527 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.538 ±(99.9%) 0.499 ms/op [Average]
  (min, avg, max) = (2.519, 2.538, 2.570), stdev = 0.027
  CI (99.9%): [2.039, 3.037] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:32
# Fork: 1 of 1
# Warmup Iteration   1: 3.659 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.446 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.461 ±(99.9%) 0.003 ms/op
Iteration   1: 2.454 ±(99.9%) 0.003 ms/op
Iteration   2: 2.452 ±(99.9%) 0.003 ms/op
Iteration   3: 2.440 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.449 ±(99.9%) 0.137 ms/op [Average]
  (min, avg, max) = (2.440, 2.449, 2.454), stdev = 0.007
  CI (99.9%): [2.312, 2.585] (assumes normal distribution)


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
# Warmup Iteration   1: 3.993 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.505 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.477 ±(99.9%) 0.003 ms/op
Iteration   1: 2.500 ±(99.9%) 0.004 ms/op
Iteration   2: 2.464 ±(99.9%) 0.003 ms/op
Iteration   3: 2.488 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.484 ±(99.9%) 0.335 ms/op [Average]
  (min, avg, max) = (2.464, 2.484, 2.500), stdev = 0.018
  CI (99.9%): [2.149, 2.819] (assumes normal distribution)


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
# Warmup Iteration   1: 4.544 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.013 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.021 ±(99.9%) 0.006 ms/op
Iteration   1: 3.011 ±(99.9%) 0.006 ms/op
Iteration   2: 3.011 ±(99.9%) 0.007 ms/op
Iteration   3: 3.032 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.018 ±(99.9%) 0.230 ms/op [Average]
  (min, avg, max) = (3.011, 3.018, 3.032), stdev = 0.013
  CI (99.9%): [2.788, 3.248] (assumes normal distribution)


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
# Warmup Iteration   1: 4.257 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.579 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.534 ±(99.9%) 0.006 ms/op
Iteration   1: 2.528 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.990 ms/op
                 createUser·p0.50:   2.601 ms/op
                 createUser·p0.90:   3.056 ms/op
                 createUser·p0.95:   3.162 ms/op
                 createUser·p0.99:   3.781 ms/op
                 createUser·p0.999:  12.174 ms/op
                 createUser·p0.9999: 13.654 ms/op
                 createUser·p1.00:   14.123 ms/op

Iteration   2: 2.522 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.886 ms/op
                 createUser·p0.50:   2.605 ms/op
                 createUser·p0.90:   3.060 ms/op
                 createUser·p0.95:   3.158 ms/op
                 createUser·p0.99:   3.559 ms/op
                 createUser·p0.999:  8.602 ms/op
                 createUser·p0.9999: 10.835 ms/op
                 createUser·p1.00:   11.158 ms/op

Iteration   3: 2.537 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.909 ms/op
                 createUser·p0.50:   2.634 ms/op
                 createUser·p0.90:   3.068 ms/op
                 createUser·p0.95:   3.187 ms/op
                 createUser·p0.99:   3.916 ms/op
                 createUser·p0.999:  8.913 ms/op
                 createUser·p0.9999: 11.059 ms/op
                 createUser·p1.00:   12.206 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 379264
  mean =      2.529 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 45 
    [ 1.250,  2.500) = 182927 
    [ 2.500,  3.750) = 192523 
    [ 3.750,  5.000) = 2810 
    [ 5.000,  6.250) = 454 
    [ 6.250,  7.500) = 47 
    [ 7.500,  8.750) = 48 
    [ 8.750, 10.000) = 145 
    [10.000, 11.250) = 103 
    [11.250, 12.500) = 85 
    [12.500, 13.750) = 72 
    [13.750, 15.000) = 5 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.886 ms/op
     p(50.0000) =      2.613 ms/op
     p(90.0000) =      3.060 ms/op
     p(95.0000) =      3.170 ms/op
     p(99.0000) =      3.748 ms/op
     p(99.9000) =      9.077 ms/op
     p(99.9900) =     13.128 ms/op
     p(99.9990) =     13.874 ms/op
     p(99.9999) =     14.123 ms/op
    p(100.0000) =     14.123 ms/op


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
# Warmup Iteration   1: 3.717 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.494 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.441 ±(99.9%) 0.005 ms/op
Iteration   1: 2.453 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.991 ms/op
                 existUser·p0.50:   2.544 ms/op
                 existUser·p0.90:   2.970 ms/op
                 existUser·p0.95:   3.076 ms/op
                 existUser·p0.99:   3.543 ms/op
                 existUser·p0.999:  8.511 ms/op
                 existUser·p0.9999: 13.942 ms/op
                 existUser·p1.00:   14.287 ms/op

Iteration   2: 2.478 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.888 ms/op
                 existUser·p0.50:   2.548 ms/op
                 existUser·p0.90:   2.998 ms/op
                 existUser·p0.95:   3.117 ms/op
                 existUser·p0.99:   3.954 ms/op
                 existUser·p0.999:  7.629 ms/op
                 existUser·p0.9999: 12.666 ms/op
                 existUser·p1.00:   13.615 ms/op

Iteration   3: 2.446 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.039 ms/op
                 existUser·p0.50:   2.507 ms/op
                 existUser·p0.90:   2.970 ms/op
                 existUser·p0.95:   3.080 ms/op
                 existUser·p0.99:   3.523 ms/op
                 existUser·p0.999:  7.941 ms/op
                 existUser·p0.9999: 12.598 ms/op
                 existUser·p1.00:   13.255 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 389973
  mean =      2.459 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 49 
    [ 1.250,  2.500) = 192451 
    [ 2.500,  3.750) = 194082 
    [ 3.750,  5.000) = 2385 
    [ 5.000,  6.250) = 509 
    [ 6.250,  7.500) = 84 
    [ 7.500,  8.750) = 78 
    [ 8.750, 10.000) = 77 
    [10.000, 11.250) = 66 
    [11.250, 12.500) = 82 
    [12.500, 13.750) = 90 
    [13.750, 15.000) = 20 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.888 ms/op
     p(50.0000) =      2.531 ms/op
     p(90.0000) =      2.982 ms/op
     p(95.0000) =      3.092 ms/op
     p(99.0000) =      3.658 ms/op
     p(99.9000) =      7.938 ms/op
     p(99.9900) =     13.337 ms/op
     p(99.9990) =     14.177 ms/op
     p(99.9999) =     14.287 ms/op
    p(100.0000) =     14.287 ms/op


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
# Warmup Iteration   1: 3.911 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.581 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.565 ±(99.9%) 0.006 ms/op
Iteration   1: 2.513 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.958 ms/op
                 getUser·p0.50:   2.556 ms/op
                 getUser·p0.90:   3.047 ms/op
                 getUser·p0.95:   3.162 ms/op
                 getUser·p0.99:   3.711 ms/op
                 getUser·p0.999:  11.822 ms/op
                 getUser·p0.9999: 13.800 ms/op
                 getUser·p1.00:   14.860 ms/op

Iteration   2: 2.515 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.005 ms/op
                 getUser·p0.50:   2.568 ms/op
                 getUser·p0.90:   3.052 ms/op
                 getUser·p0.95:   3.162 ms/op
                 getUser·p0.99:   3.756 ms/op
                 getUser·p0.999:  9.467 ms/op
                 getUser·p0.9999: 12.864 ms/op
                 getUser·p1.00:   13.681 ms/op

Iteration   3: 2.532 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.858 ms/op
                 getUser·p0.50:   2.580 ms/op
                 getUser·p0.90:   3.072 ms/op
                 getUser·p0.95:   3.219 ms/op
                 getUser·p0.99:   4.187 ms/op
                 getUser·p0.999:  8.421 ms/op
                 getUser·p0.9999: 11.092 ms/op
                 getUser·p1.00:   11.551 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 380587
  mean =      2.520 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 58 
    [ 1.250,  2.500) = 186241 
    [ 2.500,  3.750) = 189759 
    [ 3.750,  5.000) = 3618 
    [ 5.000,  6.250) = 497 
    [ 6.250,  7.500) = 30 
    [ 7.500,  8.750) = 6 
    [ 8.750, 10.000) = 65 
    [10.000, 11.250) = 120 
    [11.250, 12.500) = 61 
    [12.500, 13.750) = 114 
    [13.750, 15.000) = 18 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.858 ms/op
     p(50.0000) =      2.568 ms/op
     p(90.0000) =      3.056 ms/op
     p(95.0000) =      3.178 ms/op
     p(99.0000) =      3.846 ms/op
     p(99.9000) =      8.445 ms/op
     p(99.9900) =     13.418 ms/op
     p(99.9990) =     14.339 ms/op
     p(99.9999) =     14.860 ms/op
    p(100.0000) =     14.860 ms/op


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
# Warmup Iteration   1: 4.757 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.026 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.014 ±(99.9%) 0.009 ms/op
Iteration   1: 3.011 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.930 ms/op
                 listUser·p0.50:   2.945 ms/op
                 listUser·p0.90:   3.932 ms/op
                 listUser·p0.95:   4.432 ms/op
                 listUser·p0.99:   5.571 ms/op
                 listUser·p0.999:  9.634 ms/op
                 listUser·p0.9999: 12.163 ms/op
                 listUser·p1.00:   13.025 ms/op

Iteration   2: 2.995 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.847 ms/op
                 listUser·p0.50:   2.937 ms/op
                 listUser·p0.90:   3.883 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   5.620 ms/op
                 listUser·p0.999:  9.769 ms/op
                 listUser·p0.9999: 11.791 ms/op
                 listUser·p1.00:   14.549 ms/op

Iteration   3: 3.019 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.971 ms/op
                 listUser·p0.50:   2.957 ms/op
                 listUser·p0.90:   3.957 ms/op
                 listUser·p0.95:   4.530 ms/op
                 listUser·p0.99:   5.685 ms/op
                 listUser·p0.999:  9.087 ms/op
                 listUser·p0.9999: 12.517 ms/op
                 listUser·p1.00:   13.140 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 318832
  mean =      3.009 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 119 
    [ 1.250,  2.500) = 96663 
    [ 2.500,  3.750) = 181740 
    [ 3.750,  5.000) = 32281 
    [ 5.000,  6.250) = 6700 
    [ 6.250,  7.500) = 677 
    [ 7.500,  8.750) = 191 
    [ 8.750, 10.000) = 241 
    [10.000, 11.250) = 144 
    [11.250, 12.500) = 52 
    [12.500, 13.750) = 23 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.847 ms/op
     p(50.0000) =      2.949 ms/op
     p(90.0000) =      3.924 ms/op
     p(95.0000) =      4.456 ms/op
     p(99.0000) =      5.636 ms/op
     p(99.9000) =      9.555 ms/op
     p(99.9900) =     12.108 ms/op
     p(99.9990) =     13.025 ms/op
     p(99.9999) =     14.549 ms/op
    p(100.0000) =     14.549 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.694 ± 1.064  ops/ms
ClientPb.existUser                       thrpt       3  12.933 ± 0.844  ops/ms
ClientPb.getUser                         thrpt       3  12.887 ± 0.660  ops/ms
ClientPb.listUser                        thrpt       3  10.637 ± 1.163  ops/ms
ClientPb.createUser                       avgt       3   2.538 ± 0.499   ms/op
ClientPb.existUser                        avgt       3   2.449 ± 0.137   ms/op
ClientPb.getUser                          avgt       3   2.484 ± 0.335   ms/op
ClientPb.listUser                         avgt       3   3.018 ± 0.230   ms/op
ClientPb.createUser                     sample  379264   2.529 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.886           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.613           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.060           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.170           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.748           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.077           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.128           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.123           ms/op
ClientPb.existUser                      sample  389973   2.459 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.888           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.531           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.982           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.092           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.658           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.938           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.337           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.287           ms/op
ClientPb.getUser                        sample  380587   2.520 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.858           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.568           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.056           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.178           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.846           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.445           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.418           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.860           ms/op
ClientPb.listUser                       sample  318832   3.009 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.847           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.949           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.924           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.456           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.636           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.555           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.108           ms/op
ClientPb.listUser:listUser·p1.00        sample          14.549           ms/op
