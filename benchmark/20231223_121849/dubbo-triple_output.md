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
# Warmup Iteration   1: 4.405 ops/ms
# Warmup Iteration   2: 11.548 ops/ms
# Warmup Iteration   3: 12.046 ops/ms
Iteration   1: 12.342 ops/ms
Iteration   2: 12.489 ops/ms
Iteration   3: 12.290 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.374 ±(99.9%) 1.885 ops/ms [Average]
  (min, avg, max) = (12.290, 12.374, 12.489), stdev = 0.103
  CI (99.9%): [10.489, 14.258] (assumes normal distribution)


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
# Warmup Iteration   1: 7.826 ops/ms
# Warmup Iteration   2: 12.707 ops/ms
# Warmup Iteration   3: 12.820 ops/ms
Iteration   1: 12.831 ops/ms
Iteration   2: 12.837 ops/ms
Iteration   3: 12.939 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.869 ±(99.9%) 1.104 ops/ms [Average]
  (min, avg, max) = (12.831, 12.869, 12.939), stdev = 0.061
  CI (99.9%): [11.765, 13.973] (assumes normal distribution)


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
# Warmup Iteration   1: 7.360 ops/ms
# Warmup Iteration   2: 12.289 ops/ms
# Warmup Iteration   3: 12.382 ops/ms
Iteration   1: 12.578 ops/ms
Iteration   2: 12.513 ops/ms
Iteration   3: 12.383 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.491 ±(99.9%) 1.809 ops/ms [Average]
  (min, avg, max) = (12.383, 12.491, 12.578), stdev = 0.099
  CI (99.9%): [10.682, 14.300] (assumes normal distribution)


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
# Warmup Iteration   1: 6.243 ops/ms
# Warmup Iteration   2: 10.071 ops/ms
# Warmup Iteration   3: 10.132 ops/ms
Iteration   1: 10.177 ops/ms
Iteration   2: 10.252 ops/ms
Iteration   3: 10.289 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.239 ±(99.9%) 1.040 ops/ms [Average]
  (min, avg, max) = (10.177, 10.239, 10.289), stdev = 0.057
  CI (99.9%): [9.199, 11.280] (assumes normal distribution)


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
# Warmup Iteration   1: 4.223 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.619 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.528 ±(99.9%) 0.005 ms/op
Iteration   1: 2.537 ±(99.9%) 0.004 ms/op
Iteration   2: 2.555 ±(99.9%) 0.005 ms/op
Iteration   3: 2.583 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.558 ±(99.9%) 0.430 ms/op [Average]
  (min, avg, max) = (2.537, 2.558, 2.583), stdev = 0.024
  CI (99.9%): [2.128, 2.988] (assumes normal distribution)


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
# Warmup Iteration   1: 3.750 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.480 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.495 ±(99.9%) 0.004 ms/op
Iteration   1: 2.468 ±(99.9%) 0.004 ms/op
Iteration   2: 2.482 ±(99.9%) 0.004 ms/op
Iteration   3: 2.470 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.473 ±(99.9%) 0.143 ms/op [Average]
  (min, avg, max) = (2.468, 2.473, 2.482), stdev = 0.008
  CI (99.9%): [2.331, 2.616] (assumes normal distribution)


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
# Warmup Iteration   1: 3.793 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.522 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.507 ±(99.9%) 0.004 ms/op
Iteration   1: 2.516 ±(99.9%) 0.003 ms/op
Iteration   2: 2.515 ±(99.9%) 0.004 ms/op
Iteration   3: 2.532 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.521 ±(99.9%) 0.171 ms/op [Average]
  (min, avg, max) = (2.515, 2.521, 2.532), stdev = 0.009
  CI (99.9%): [2.349, 2.692] (assumes normal distribution)


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
# Warmup Iteration   1: 4.719 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.052 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.029 ±(99.9%) 0.007 ms/op
Iteration   1: 3.003 ±(99.9%) 0.006 ms/op
Iteration   2: 3.012 ±(99.9%) 0.006 ms/op
Iteration   3: 2.994 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.003 ±(99.9%) 0.163 ms/op [Average]
  (min, avg, max) = (2.994, 3.003, 3.012), stdev = 0.009
  CI (99.9%): [2.841, 3.166] (assumes normal distribution)


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
# Warmup Iteration   1: 4.417 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 2.694 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.552 ±(99.9%) 0.006 ms/op
Iteration   1: 2.551 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.933 ms/op
                 createUser·p0.50:   2.630 ms/op
                 createUser·p0.90:   3.088 ms/op
                 createUser·p0.95:   3.199 ms/op
                 createUser·p0.99:   3.827 ms/op
                 createUser·p0.999:  11.479 ms/op
                 createUser·p0.9999: 16.843 ms/op
                 createUser·p1.00:   17.039 ms/op

Iteration   2: 2.566 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.938 ms/op
                 createUser·p0.50:   2.642 ms/op
                 createUser·p0.90:   3.113 ms/op
                 createUser·p0.95:   3.224 ms/op
                 createUser·p0.99:   3.776 ms/op
                 createUser·p0.999:  9.942 ms/op
                 createUser·p0.9999: 17.483 ms/op
                 createUser·p1.00:   18.743 ms/op

Iteration   3: 2.541 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.016 ms/op
                 createUser·p0.50:   2.605 ms/op
                 createUser·p0.90:   3.088 ms/op
                 createUser·p0.95:   3.228 ms/op
                 createUser·p0.99:   3.965 ms/op
                 createUser·p0.999:  9.047 ms/op
                 createUser·p0.9999: 12.313 ms/op
                 createUser·p1.00:   13.107 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 375759
  mean =      2.553 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 47 
    [ 1.250,  2.500) = 179562 
    [ 2.500,  3.750) = 191662 
    [ 3.750,  5.000) = 3432 
    [ 5.000,  6.250) = 592 
    [ 6.250,  7.500) = 54 
    [ 7.500,  8.750) = 24 
    [ 8.750, 10.000) = 68 
    [10.000, 11.250) = 84 
    [11.250, 12.500) = 79 
    [12.500, 13.750) = 47 
    [13.750, 15.000) = 12 
    [15.000, 16.250) = 30 
    [16.250, 17.500) = 55 
    [17.500, 18.750) = 11 

  Percentiles, ms/op:
      p(0.0000) =      0.933 ms/op
     p(50.0000) =      2.621 ms/op
     p(90.0000) =      3.097 ms/op
     p(95.0000) =      3.215 ms/op
     p(99.0000) =      3.850 ms/op
     p(99.9000) =      9.081 ms/op
     p(99.9900) =     16.922 ms/op
     p(99.9990) =     18.252 ms/op
     p(99.9999) =     18.743 ms/op
    p(100.0000) =     18.743 ms/op


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
# Warmup Iteration   1: 3.797 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.497 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.524 ±(99.9%) 0.005 ms/op
Iteration   1: 2.520 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.899 ms/op
                 existUser·p0.50:   2.605 ms/op
                 existUser·p0.90:   3.056 ms/op
                 existUser·p0.95:   3.174 ms/op
                 existUser·p0.99:   3.891 ms/op
                 existUser·p0.999:  10.963 ms/op
                 existUser·p0.9999: 13.653 ms/op
                 existUser·p1.00:   14.369 ms/op

Iteration   2: 2.477 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.838 ms/op
                 existUser·p0.50:   2.621 ms/op
                 existUser·p0.90:   2.994 ms/op
                 existUser·p0.95:   3.080 ms/op
                 existUser·p0.99:   3.482 ms/op
                 existUser·p0.999:  7.587 ms/op
                 existUser·p0.9999: 13.042 ms/op
                 existUser·p1.00:   14.172 ms/op

Iteration   3: 2.538 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.979 ms/op
                 existUser·p0.50:   2.613 ms/op
                 existUser·p0.90:   3.101 ms/op
                 existUser·p0.95:   3.240 ms/op
                 existUser·p0.99:   3.944 ms/op
                 existUser·p0.999:  6.152 ms/op
                 existUser·p0.9999: 12.501 ms/op
                 existUser·p1.00:   13.255 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 381915
  mean =      2.511 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 39 
    [ 1.250,  2.500) = 182188 
    [ 2.500,  3.750) = 195497 
    [ 3.750,  5.000) = 3322 
    [ 5.000,  6.250) = 488 
    [ 6.250,  7.500) = 17 
    [ 7.500,  8.750) = 30 
    [ 8.750, 10.000) = 42 
    [10.000, 11.250) = 72 
    [11.250, 12.500) = 97 
    [12.500, 13.750) = 109 
    [13.750, 15.000) = 14 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.838 ms/op
     p(50.0000) =      2.613 ms/op
     p(90.0000) =      3.047 ms/op
     p(95.0000) =      3.166 ms/op
     p(99.0000) =      3.809 ms/op
     p(99.9000) =      6.244 ms/op
     p(99.9900) =     13.333 ms/op
     p(99.9990) =     14.102 ms/op
     p(99.9999) =     14.369 ms/op
    p(100.0000) =     14.369 ms/op


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
# Warmup Iteration   1: 4.024 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.545 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.504 ±(99.9%) 0.006 ms/op
Iteration   1: 2.503 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.937 ms/op
                 getUser·p0.50:   2.523 ms/op
                 getUser·p0.90:   3.056 ms/op
                 getUser·p0.95:   3.191 ms/op
                 getUser·p0.99:   3.772 ms/op
                 getUser·p0.999:  11.477 ms/op
                 getUser·p0.9999: 17.039 ms/op
                 getUser·p1.00:   17.334 ms/op

Iteration   2: 2.477 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.018 ms/op
                 getUser·p0.50:   2.527 ms/op
                 getUser·p0.90:   3.011 ms/op
                 getUser·p0.95:   3.146 ms/op
                 getUser·p0.99:   3.887 ms/op
                 getUser·p0.999:  6.799 ms/op
                 getUser·p0.9999: 13.372 ms/op
                 getUser·p1.00:   15.155 ms/op

Iteration   3: 2.490 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.962 ms/op
                 getUser·p0.50:   2.523 ms/op
                 getUser·p0.90:   3.015 ms/op
                 getUser·p0.95:   3.150 ms/op
                 getUser·p0.99:   4.399 ms/op
                 getUser·p0.999:  8.612 ms/op
                 getUser·p0.9999: 11.619 ms/op
                 getUser·p1.00:   13.107 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 385163
  mean =      2.490 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 76 
    [ 1.250,  2.500) = 190510 
    [ 2.500,  3.750) = 189645 
    [ 3.750,  5.000) = 3568 
    [ 5.000,  6.250) = 871 
    [ 6.250,  7.500) = 71 
    [ 7.500,  8.750) = 45 
    [ 8.750, 10.000) = 63 
    [10.000, 11.250) = 103 
    [11.250, 12.500) = 73 
    [12.500, 13.750) = 39 
    [13.750, 15.000) = 23 
    [15.000, 16.250) = 44 
    [16.250, 17.500) = 32 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.937 ms/op
     p(50.0000) =      2.523 ms/op
     p(90.0000) =      3.027 ms/op
     p(95.0000) =      3.162 ms/op
     p(99.0000) =      3.928 ms/op
     p(99.9000) =      8.602 ms/op
     p(99.9900) =     16.179 ms/op
     p(99.9990) =     17.246 ms/op
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
# Warmup Iteration   1: 4.826 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.096 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.077 ±(99.9%) 0.009 ms/op
Iteration   1: 3.062 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.709 ms/op
                 listUser·p0.50:   3.002 ms/op
                 listUser·p0.90:   3.940 ms/op
                 listUser·p0.95:   4.448 ms/op
                 listUser·p0.99:   5.628 ms/op
                 listUser·p0.999:  9.273 ms/op
                 listUser·p0.9999: 10.532 ms/op
                 listUser·p1.00:   11.158 ms/op

Iteration   2: 3.056 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.863 ms/op
                 listUser·p0.50:   2.998 ms/op
                 listUser·p0.90:   3.953 ms/op
                 listUser·p0.95:   4.465 ms/op
                 listUser·p0.99:   5.775 ms/op
                 listUser·p0.999:  9.444 ms/op
                 listUser·p0.9999: 11.200 ms/op
                 listUser·p1.00:   12.681 ms/op

Iteration   3: 3.047 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.949 ms/op
                 listUser·p0.50:   2.986 ms/op
                 listUser·p0.90:   3.944 ms/op
                 listUser·p0.95:   4.465 ms/op
                 listUser·p0.99:   5.636 ms/op
                 listUser·p0.999:  9.471 ms/op
                 listUser·p0.9999: 13.869 ms/op
                 listUser·p1.00:   15.499 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 313942
  mean =      3.055 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 107 
    [ 1.250,  2.500) = 83907 
    [ 2.500,  3.750) = 188047 
    [ 3.750,  5.000) = 34009 
    [ 5.000,  6.250) = 6395 
    [ 6.250,  7.500) = 825 
    [ 7.500,  8.750) = 200 
    [ 8.750, 10.000) = 272 
    [10.000, 11.250) = 118 
    [11.250, 12.500) = 28 
    [12.500, 13.750) = 20 
    [13.750, 15.000) = 13 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.709 ms/op
     p(50.0000) =      2.994 ms/op
     p(90.0000) =      3.944 ms/op
     p(95.0000) =      4.456 ms/op
     p(99.0000) =      5.669 ms/op
     p(99.9000) =      9.405 ms/op
     p(99.9900) =     12.846 ms/op
     p(99.9990) =     14.269 ms/op
     p(99.9999) =     15.499 ms/op
    p(100.0000) =     15.499 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.374 ± 1.885  ops/ms
ClientPb.existUser                       thrpt       3  12.869 ± 1.104  ops/ms
ClientPb.getUser                         thrpt       3  12.491 ± 1.809  ops/ms
ClientPb.listUser                        thrpt       3  10.239 ± 1.040  ops/ms
ClientPb.createUser                       avgt       3   2.558 ± 0.430   ms/op
ClientPb.existUser                        avgt       3   2.473 ± 0.143   ms/op
ClientPb.getUser                          avgt       3   2.521 ± 0.171   ms/op
ClientPb.listUser                         avgt       3   3.003 ± 0.163   ms/op
ClientPb.createUser                     sample  375759   2.553 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.933           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.621           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.097           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.215           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.850           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.081           ms/op
ClientPb.createUser:createUser·p0.9999  sample          16.922           ms/op
ClientPb.createUser:createUser·p1.00    sample          18.743           ms/op
ClientPb.existUser                      sample  381915   2.511 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.838           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.613           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.047           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.166           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.809           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.244           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.333           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.369           ms/op
ClientPb.getUser                        sample  385163   2.490 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.937           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.523           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.027           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.162           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.928           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.602           ms/op
ClientPb.getUser:getUser·p0.9999        sample          16.179           ms/op
ClientPb.getUser:getUser·p1.00          sample          17.334           ms/op
ClientPb.listUser                       sample  313942   3.055 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.709           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.994           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.944           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.456           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.669           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.405           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.846           ms/op
ClientPb.listUser:listUser·p1.00        sample          15.499           ms/op
