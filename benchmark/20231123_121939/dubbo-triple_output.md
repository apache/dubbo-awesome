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
# Warmup Iteration   1: 5.042 ops/ms
# Warmup Iteration   2: 11.919 ops/ms
# Warmup Iteration   3: 12.229 ops/ms
Iteration   1: 12.409 ops/ms
Iteration   2: 12.521 ops/ms
Iteration   3: 12.506 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.479 ±(99.9%) 1.111 ops/ms [Average]
  (min, avg, max) = (12.409, 12.479, 12.521), stdev = 0.061
  CI (99.9%): [11.368, 13.590] (assumes normal distribution)


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
# Warmup Iteration   1: 8.488 ops/ms
# Warmup Iteration   2: 13.125 ops/ms
# Warmup Iteration   3: 13.095 ops/ms
Iteration   1: 13.026 ops/ms
Iteration   2: 13.132 ops/ms
Iteration   3: 13.030 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.063 ±(99.9%) 1.099 ops/ms [Average]
  (min, avg, max) = (13.026, 13.063, 13.132), stdev = 0.060
  CI (99.9%): [11.964, 14.161] (assumes normal distribution)


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
# Warmup Iteration   1: 7.842 ops/ms
# Warmup Iteration   2: 12.755 ops/ms
# Warmup Iteration   3: 12.799 ops/ms
Iteration   1: 13.074 ops/ms
Iteration   2: 12.649 ops/ms
Iteration   3: 12.976 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.899 ±(99.9%) 4.059 ops/ms [Average]
  (min, avg, max) = (12.649, 12.899, 13.074), stdev = 0.222
  CI (99.9%): [8.841, 16.958] (assumes normal distribution)


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
# Warmup Iteration   1: 6.652 ops/ms
# Warmup Iteration   2: 10.546 ops/ms
# Warmup Iteration   3: 10.666 ops/ms
Iteration   1: 10.675 ops/ms
Iteration   2: 10.633 ops/ms
Iteration   3: 10.667 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.658 ±(99.9%) 0.412 ops/ms [Average]
  (min, avg, max) = (10.633, 10.658, 10.675), stdev = 0.023
  CI (99.9%): [10.246, 11.070] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:38
# Fork: 1 of 1
# Warmup Iteration   1: 3.951 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 2.525 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.490 ±(99.9%) 0.005 ms/op
Iteration   1: 2.511 ±(99.9%) 0.004 ms/op
Iteration   2: 2.530 ±(99.9%) 0.004 ms/op
Iteration   3: 2.480 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.507 ±(99.9%) 0.458 ms/op [Average]
  (min, avg, max) = (2.480, 2.507, 2.530), stdev = 0.025
  CI (99.9%): [2.049, 2.966] (assumes normal distribution)


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
# Warmup Iteration   1: 3.602 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.458 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.454 ±(99.9%) 0.004 ms/op
Iteration   1: 2.453 ±(99.9%) 0.004 ms/op
Iteration   2: 2.454 ±(99.9%) 0.004 ms/op
Iteration   3: 2.456 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.455 ±(99.9%) 0.031 ms/op [Average]
  (min, avg, max) = (2.453, 2.455, 2.456), stdev = 0.002
  CI (99.9%): [2.423, 2.486] (assumes normal distribution)


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
# Warmup Iteration   1: 3.936 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.537 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.495 ±(99.9%) 0.004 ms/op
Iteration   1: 2.487 ±(99.9%) 0.003 ms/op
Iteration   2: 2.463 ±(99.9%) 0.004 ms/op
Iteration   3: 2.488 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.479 ±(99.9%) 0.259 ms/op [Average]
  (min, avg, max) = (2.463, 2.479, 2.488), stdev = 0.014
  CI (99.9%): [2.220, 2.738] (assumes normal distribution)


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
# Warmup Iteration   1: 4.658 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.035 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.044 ±(99.9%) 0.005 ms/op
Iteration   1: 3.019 ±(99.9%) 0.005 ms/op
Iteration   2: 3.019 ±(99.9%) 0.005 ms/op
Iteration   3: 3.002 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.013 ±(99.9%) 0.171 ms/op [Average]
  (min, avg, max) = (3.002, 3.013, 3.019), stdev = 0.009
  CI (99.9%): [2.842, 3.184] (assumes normal distribution)


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
# Warmup Iteration   1: 4.129 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.615 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.505 ±(99.9%) 0.006 ms/op
Iteration   1: 2.495 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.846 ms/op
                 createUser·p0.50:   2.560 ms/op
                 createUser·p0.90:   3.027 ms/op
                 createUser·p0.95:   3.142 ms/op
                 createUser·p0.99:   3.744 ms/op
                 createUser·p0.999:  11.202 ms/op
                 createUser·p0.9999: 13.978 ms/op
                 createUser·p1.00:   14.582 ms/op

Iteration   2: 2.509 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.944 ms/op
                 createUser·p0.50:   2.609 ms/op
                 createUser·p0.90:   3.052 ms/op
                 createUser·p0.95:   3.178 ms/op
                 createUser·p0.99:   3.813 ms/op
                 createUser·p0.999:  10.013 ms/op
                 createUser·p0.9999: 12.615 ms/op
                 createUser·p1.00:   13.320 ms/op

Iteration   3: 2.523 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.976 ms/op
                 createUser·p0.50:   2.601 ms/op
                 createUser·p0.90:   3.060 ms/op
                 createUser·p0.95:   3.191 ms/op
                 createUser·p0.99:   4.096 ms/op
                 createUser·p0.999:  9.002 ms/op
                 createUser·p0.9999: 11.632 ms/op
                 createUser·p1.00:   13.353 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 382455
  mean =      2.509 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 52 
    [ 1.250,  2.500) = 183451 
    [ 2.500,  3.750) = 194360 
    [ 3.750,  5.000) = 3593 
    [ 5.000,  6.250) = 506 
    [ 6.250,  7.500) = 43 
    [ 7.500,  8.750) = 58 
    [ 8.750, 10.000) = 79 
    [10.000, 11.250) = 106 
    [11.250, 12.500) = 71 
    [12.500, 13.750) = 92 
    [13.750, 15.000) = 44 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.846 ms/op
     p(50.0000) =      2.589 ms/op
     p(90.0000) =      3.043 ms/op
     p(95.0000) =      3.170 ms/op
     p(99.0000) =      3.871 ms/op
     p(99.9000) =      9.013 ms/op
     p(99.9900) =     13.779 ms/op
     p(99.9990) =     14.368 ms/op
     p(99.9999) =     14.582 ms/op
    p(100.0000) =     14.582 ms/op


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
# Warmup Iteration   1: 3.774 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.480 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.479 ±(99.9%) 0.005 ms/op
Iteration   1: 2.485 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.042 ms/op
                 existUser·p0.50:   2.580 ms/op
                 existUser·p0.90:   3.002 ms/op
                 existUser·p0.95:   3.129 ms/op
                 existUser·p0.99:   4.264 ms/op
                 existUser·p0.999:  6.660 ms/op
                 existUser·p0.9999: 13.976 ms/op
                 existUser·p1.00:   14.156 ms/op

Iteration   2: 2.464 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.169 ms/op
                 existUser·p0.50:   2.613 ms/op
                 existUser·p0.90:   2.970 ms/op
                 existUser·p0.95:   3.056 ms/op
                 existUser·p0.99:   3.432 ms/op
                 existUser·p0.999:  6.675 ms/op
                 existUser·p0.9999: 14.304 ms/op
                 existUser·p1.00:   16.581 ms/op

Iteration   3: 2.487 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.994 ms/op
                 existUser·p0.50:   2.544 ms/op
                 existUser·p0.90:   3.023 ms/op
                 existUser·p0.95:   3.154 ms/op
                 existUser·p0.99:   3.879 ms/op
                 existUser·p0.999:  8.074 ms/op
                 existUser·p0.9999: 12.354 ms/op
                 existUser·p1.00:   13.042 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 386893
  mean =      2.479 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 28 
    [ 1.250,  2.500) = 186638 
    [ 2.500,  3.750) = 195863 
    [ 3.750,  5.000) = 3176 
    [ 5.000,  6.250) = 683 
    [ 6.250,  7.500) = 140 
    [ 7.500,  8.750) = 17 
    [ 8.750, 10.000) = 93 
    [10.000, 11.250) = 49 
    [11.250, 12.500) = 99 
    [12.500, 13.750) = 69 
    [13.750, 15.000) = 28 
    [15.000, 16.250) = 9 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.994 ms/op
     p(50.0000) =      2.576 ms/op
     p(90.0000) =      2.998 ms/op
     p(95.0000) =      3.109 ms/op
     p(99.0000) =      3.850 ms/op
     p(99.9000) =      7.135 ms/op
     p(99.9900) =     13.761 ms/op
     p(99.9990) =     15.516 ms/op
     p(99.9999) =     16.581 ms/op
    p(100.0000) =     16.581 ms/op


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
# Warmup Iteration   1: 4.033 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.580 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.502 ±(99.9%) 0.005 ms/op
Iteration   1: 2.555 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.929 ms/op
                 getUser·p0.50:   2.605 ms/op
                 getUser·p0.90:   3.113 ms/op
                 getUser·p0.95:   3.326 ms/op
                 getUser·p0.99:   4.448 ms/op
                 getUser·p0.999:  12.302 ms/op
                 getUser·p0.9999: 13.803 ms/op
                 getUser·p1.00:   17.236 ms/op

Iteration   2: 2.486 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.607 ms/op
                 getUser·p0.50:   2.531 ms/op
                 getUser·p0.90:   3.019 ms/op
                 getUser·p0.95:   3.129 ms/op
                 getUser·p0.99:   3.686 ms/op
                 getUser·p0.999:  8.063 ms/op
                 getUser·p0.9999: 14.174 ms/op
                 getUser·p1.00:   15.041 ms/op

Iteration   3: 2.519 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.880 ms/op
                 getUser·p0.50:   2.523 ms/op
                 getUser·p0.90:   3.064 ms/op
                 getUser·p0.95:   3.240 ms/op
                 getUser·p0.99:   4.415 ms/op
                 getUser·p0.999:  8.636 ms/op
                 getUser·p0.9999: 11.359 ms/op
                 getUser·p1.00:   11.698 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 380665
  mean =      2.520 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 87 
    [ 1.250,  2.500) = 185679 
    [ 2.500,  3.750) = 187892 
    [ 3.750,  5.000) = 5550 
    [ 5.000,  6.250) = 884 
    [ 6.250,  7.500) = 145 
    [ 7.500,  8.750) = 34 
    [ 8.750, 10.000) = 81 
    [10.000, 11.250) = 73 
    [11.250, 12.500) = 65 
    [12.500, 13.750) = 137 
    [13.750, 15.000) = 34 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 3 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.607 ms/op
     p(50.0000) =      2.560 ms/op
     p(90.0000) =      3.064 ms/op
     p(95.0000) =      3.224 ms/op
     p(99.0000) =      4.243 ms/op
     p(99.9000) =      9.017 ms/op
     p(99.9900) =     13.777 ms/op
     p(99.9990) =     15.367 ms/op
     p(99.9999) =     17.236 ms/op
    p(100.0000) =     17.236 ms/op


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
# Warmup Iteration   1: 5.010 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 3.071 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.048 ±(99.9%) 0.009 ms/op
Iteration   1: 3.007 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.941 ms/op
                 listUser·p0.50:   2.949 ms/op
                 listUser·p0.90:   3.875 ms/op
                 listUser·p0.95:   4.350 ms/op
                 listUser·p0.99:   5.644 ms/op
                 listUser·p0.999:  8.765 ms/op
                 listUser·p0.9999: 10.754 ms/op
                 listUser·p1.00:   11.600 ms/op

Iteration   2: 3.026 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.865 ms/op
                 listUser·p0.50:   2.970 ms/op
                 listUser·p0.90:   3.928 ms/op
                 listUser·p0.95:   4.415 ms/op
                 listUser·p0.99:   5.538 ms/op
                 listUser·p0.999:  9.912 ms/op
                 listUser·p0.9999: 13.325 ms/op
                 listUser·p1.00:   13.566 ms/op

Iteration   3: 3.042 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.965 ms/op
                 listUser·p0.50:   2.986 ms/op
                 listUser·p0.90:   3.961 ms/op
                 listUser·p0.95:   4.456 ms/op
                 listUser·p0.99:   5.587 ms/op
                 listUser·p0.999:  10.125 ms/op
                 listUser·p0.9999: 13.328 ms/op
                 listUser·p1.00:   13.894 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 317046
  mean =      3.025 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 105 
    [ 1.250,  2.500) = 91631 
    [ 2.500,  3.750) = 184730 
    [ 3.750,  5.000) = 33480 
    [ 5.000,  6.250) = 5742 
    [ 6.250,  7.500) = 687 
    [ 7.500,  8.750) = 208 
    [ 8.750, 10.000) = 215 
    [10.000, 11.250) = 183 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 28 
    [13.750, 15.000) = 5 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.865 ms/op
     p(50.0000) =      2.966 ms/op
     p(90.0000) =      3.920 ms/op
     p(95.0000) =      4.415 ms/op
     p(99.0000) =      5.587 ms/op
     p(99.9000) =      9.519 ms/op
     p(99.9900) =     12.748 ms/op
     p(99.9990) =     13.844 ms/op
     p(99.9999) =     13.894 ms/op
    p(100.0000) =     13.894 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.479 ± 1.111  ops/ms
ClientPb.existUser                       thrpt       3  13.063 ± 1.099  ops/ms
ClientPb.getUser                         thrpt       3  12.899 ± 4.059  ops/ms
ClientPb.listUser                        thrpt       3  10.658 ± 0.412  ops/ms
ClientPb.createUser                       avgt       3   2.507 ± 0.458   ms/op
ClientPb.existUser                        avgt       3   2.455 ± 0.031   ms/op
ClientPb.getUser                          avgt       3   2.479 ± 0.259   ms/op
ClientPb.listUser                         avgt       3   3.013 ± 0.171   ms/op
ClientPb.createUser                     sample  382455   2.509 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.846           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.589           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.043           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.170           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.871           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.013           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.779           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.582           ms/op
ClientPb.existUser                      sample  386893   2.479 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.994           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.576           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.998           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.109           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.850           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.135           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.761           ms/op
ClientPb.existUser:existUser·p1.00      sample          16.581           ms/op
ClientPb.getUser                        sample  380665   2.520 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.607           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.560           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.064           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.224           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.243           ms/op
ClientPb.getUser:getUser·p0.999         sample           9.017           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.777           ms/op
ClientPb.getUser:getUser·p1.00          sample          17.236           ms/op
ClientPb.listUser                       sample  317046   3.025 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.865           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.966           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.920           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.415           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.587           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.519           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.748           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.894           ms/op
