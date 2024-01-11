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
# Warmup Iteration   1: 4.929 ops/ms
# Warmup Iteration   2: 11.817 ops/ms
# Warmup Iteration   3: 12.106 ops/ms
Iteration   1: 12.239 ops/ms
Iteration   2: 12.291 ops/ms
Iteration   3: 12.532 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.354 ±(99.9%) 2.853 ops/ms [Average]
  (min, avg, max) = (12.239, 12.354, 12.532), stdev = 0.156
  CI (99.9%): [9.500, 15.207] (assumes normal distribution)


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
# Warmup Iteration   1: 8.247 ops/ms
# Warmup Iteration   2: 12.798 ops/ms
# Warmup Iteration   3: 12.906 ops/ms
Iteration   1: 12.889 ops/ms
Iteration   2: 12.870 ops/ms
Iteration   3: 12.974 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.911 ±(99.9%) 1.010 ops/ms [Average]
  (min, avg, max) = (12.870, 12.911, 12.974), stdev = 0.055
  CI (99.9%): [11.902, 13.921] (assumes normal distribution)


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
# Warmup Iteration   1: 7.844 ops/ms
# Warmup Iteration   2: 12.465 ops/ms
# Warmup Iteration   3: 12.481 ops/ms
Iteration   1: 12.352 ops/ms
Iteration   2: 12.511 ops/ms
Iteration   3: 12.444 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.435 ±(99.9%) 1.458 ops/ms [Average]
  (min, avg, max) = (12.352, 12.435, 12.511), stdev = 0.080
  CI (99.9%): [10.978, 13.893] (assumes normal distribution)


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
# Warmup Iteration   1: 6.781 ops/ms
# Warmup Iteration   2: 10.446 ops/ms
# Warmup Iteration   3: 10.369 ops/ms
Iteration   1: 10.517 ops/ms
Iteration   2: 10.501 ops/ms
Iteration   3: 10.575 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.531 ±(99.9%) 0.712 ops/ms [Average]
  (min, avg, max) = (10.501, 10.531, 10.575), stdev = 0.039
  CI (99.9%): [9.819, 11.242] (assumes normal distribution)


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
# Warmup Iteration   1: 4.395 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 2.630 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.580 ±(99.9%) 0.005 ms/op
Iteration   1: 2.589 ±(99.9%) 0.004 ms/op
Iteration   2: 2.548 ±(99.9%) 0.004 ms/op
Iteration   3: 2.560 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.566 ±(99.9%) 0.387 ms/op [Average]
  (min, avg, max) = (2.548, 2.566, 2.589), stdev = 0.021
  CI (99.9%): [2.179, 2.953] (assumes normal distribution)


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
# Warmup Iteration   1: 3.823 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.516 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.468 ±(99.9%) 0.004 ms/op
Iteration   1: 2.497 ±(99.9%) 0.003 ms/op
Iteration   2: 2.489 ±(99.9%) 0.005 ms/op
Iteration   3: 2.477 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.488 ±(99.9%) 0.177 ms/op [Average]
  (min, avg, max) = (2.477, 2.488, 2.497), stdev = 0.010
  CI (99.9%): [2.310, 2.665] (assumes normal distribution)


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
# Warmup Iteration   1: 4.131 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.603 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.593 ±(99.9%) 0.005 ms/op
Iteration   1: 2.573 ±(99.9%) 0.005 ms/op
Iteration   2: 2.596 ±(99.9%) 0.004 ms/op
Iteration   3: 2.562 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.577 ±(99.9%) 0.322 ms/op [Average]
  (min, avg, max) = (2.562, 2.577, 2.596), stdev = 0.018
  CI (99.9%): [2.255, 2.899] (assumes normal distribution)


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
# Warmup Iteration   1: 4.883 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.094 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.051 ±(99.9%) 0.004 ms/op
Iteration   1: 3.048 ±(99.9%) 0.006 ms/op
Iteration   2: 3.061 ±(99.9%) 0.005 ms/op
Iteration   3: 3.023 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.044 ±(99.9%) 0.358 ms/op [Average]
  (min, avg, max) = (3.023, 3.044, 3.061), stdev = 0.020
  CI (99.9%): [2.686, 3.402] (assumes normal distribution)


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
# Warmup Iteration   1: 4.299 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 2.713 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.552 ±(99.9%) 0.006 ms/op
Iteration   1: 2.567 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.725 ms/op
                 createUser·p0.50:   2.626 ms/op
                 createUser·p0.90:   3.121 ms/op
                 createUser·p0.95:   3.236 ms/op
                 createUser·p0.99:   3.809 ms/op
                 createUser·p0.999:  12.104 ms/op
                 createUser·p0.9999: 13.631 ms/op
                 createUser·p1.00:   14.451 ms/op

Iteration   2: 2.565 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.936 ms/op
                 createUser·p0.50:   2.630 ms/op
                 createUser·p0.90:   3.117 ms/op
                 createUser·p0.95:   3.232 ms/op
                 createUser·p0.99:   3.772 ms/op
                 createUser·p0.999:  9.498 ms/op
                 createUser·p0.9999: 14.577 ms/op
                 createUser·p1.00:   15.221 ms/op

Iteration   3: 2.567 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.018 ms/op
                 createUser·p0.50:   2.613 ms/op
                 createUser·p0.90:   3.125 ms/op
                 createUser·p0.95:   3.265 ms/op
                 createUser·p0.99:   3.957 ms/op
                 createUser·p0.999:  8.298 ms/op
                 createUser·p0.9999: 10.611 ms/op
                 createUser·p1.00:   11.354 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 373739
  mean =      2.566 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 54 
    [ 1.250,  2.500) = 178272 
    [ 2.500,  3.750) = 190960 
    [ 3.750,  5.000) = 3685 
    [ 5.000,  6.250) = 341 
    [ 6.250,  7.500) = 40 
    [ 7.500,  8.750) = 31 
    [ 8.750, 10.000) = 87 
    [10.000, 11.250) = 79 
    [11.250, 12.500) = 60 
    [12.500, 13.750) = 96 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.725 ms/op
     p(50.0000) =      2.621 ms/op
     p(90.0000) =      3.121 ms/op
     p(95.0000) =      3.244 ms/op
     p(99.0000) =      3.854 ms/op
     p(99.9000) =      8.508 ms/op
     p(99.9900) =     13.664 ms/op
     p(99.9990) =     14.848 ms/op
     p(99.9999) =     15.221 ms/op
    p(100.0000) =     15.221 ms/op


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
# Warmup Iteration   1: 3.758 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.524 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.485 ±(99.9%) 0.005 ms/op
Iteration   1: 2.485 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.055 ms/op
                 existUser·p0.50:   2.494 ms/op
                 existUser·p0.90:   3.039 ms/op
                 existUser·p0.95:   3.154 ms/op
                 existUser·p0.99:   3.547 ms/op
                 existUser·p0.999:  7.876 ms/op
                 existUser·p0.9999: 14.142 ms/op
                 existUser·p1.00:   14.746 ms/op

Iteration   2: 2.485 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.918 ms/op
                 existUser·p0.50:   2.544 ms/op
                 existUser·p0.90:   3.027 ms/op
                 existUser·p0.95:   3.138 ms/op
                 existUser·p0.99:   3.703 ms/op
                 existUser·p0.999:  5.267 ms/op
                 existUser·p0.9999: 14.811 ms/op
                 existUser·p1.00:   15.581 ms/op

Iteration   3: 2.509 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.031 ms/op
                 existUser·p0.50:   2.589 ms/op
                 existUser·p0.90:   3.060 ms/op
                 existUser·p0.95:   3.183 ms/op
                 existUser·p0.99:   4.051 ms/op
                 existUser·p0.999:  7.455 ms/op
                 existUser·p0.9999: 10.905 ms/op
                 existUser·p1.00:   12.108 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 384710
  mean =      2.493 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 24 
    [ 1.250,  2.500) = 189577 
    [ 2.500,  3.750) = 191212 
    [ 3.750,  5.000) = 3020 
    [ 5.000,  6.250) = 463 
    [ 6.250,  7.500) = 62 
    [ 7.500,  8.750) = 32 
    [ 8.750, 10.000) = 80 
    [10.000, 11.250) = 49 
    [11.250, 12.500) = 65 
    [12.500, 13.750) = 58 
    [13.750, 15.000) = 67 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.918 ms/op
     p(50.0000) =      2.540 ms/op
     p(90.0000) =      3.043 ms/op
     p(95.0000) =      3.158 ms/op
     p(99.0000) =      3.760 ms/op
     p(99.9000) =      6.703 ms/op
     p(99.9900) =     14.354 ms/op
     p(99.9990) =     14.860 ms/op
     p(99.9999) =     15.581 ms/op
    p(100.0000) =     15.581 ms/op


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
# Warmup Iteration   1: 3.974 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.632 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.529 ±(99.9%) 0.006 ms/op
Iteration   1: 2.506 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.984 ms/op
                 getUser·p0.50:   2.531 ms/op
                 getUser·p0.90:   3.043 ms/op
                 getUser·p0.95:   3.133 ms/op
                 getUser·p0.99:   3.469 ms/op
                 getUser·p0.999:  12.040 ms/op
                 getUser·p0.9999: 14.491 ms/op
                 getUser·p1.00:   15.237 ms/op

Iteration   2: 2.529 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.898 ms/op
                 getUser·p0.50:   2.535 ms/op
                 getUser·p0.90:   3.080 ms/op
                 getUser·p0.95:   3.207 ms/op
                 getUser·p0.99:   3.871 ms/op
                 getUser·p0.999:  9.585 ms/op
                 getUser·p0.9999: 13.561 ms/op
                 getUser·p1.00:   14.270 ms/op

Iteration   3: 2.511 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.636 ms/op
                 getUser·p0.50:   2.540 ms/op
                 getUser·p0.90:   3.060 ms/op
                 getUser·p0.95:   3.191 ms/op
                 getUser·p0.99:   3.813 ms/op
                 getUser·p0.999:  8.782 ms/op
                 getUser·p0.9999: 11.384 ms/op
                 getUser·p1.00:   12.386 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 381287
  mean =      2.515 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 58 
    [ 1.250,  2.500) = 187820 
    [ 2.500,  3.750) = 189715 
    [ 3.750,  5.000) = 2882 
    [ 5.000,  6.250) = 371 
    [ 6.250,  7.500) = 57 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 76 
    [10.000, 11.250) = 84 
    [11.250, 12.500) = 90 
    [12.500, 13.750) = 84 
    [13.750, 15.000) = 47 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.636 ms/op
     p(50.0000) =      2.535 ms/op
     p(90.0000) =      3.060 ms/op
     p(95.0000) =      3.174 ms/op
     p(99.0000) =      3.731 ms/op
     p(99.9000) =      8.782 ms/op
     p(99.9900) =     13.877 ms/op
     p(99.9990) =     14.932 ms/op
     p(99.9999) =     15.237 ms/op
    p(100.0000) =     15.237 ms/op


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
# Warmup Iteration   1: 4.683 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.138 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.049 ±(99.9%) 0.009 ms/op
Iteration   1: 3.067 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.899 ms/op
                 listUser·p0.50:   3.002 ms/op
                 listUser·p0.90:   3.972 ms/op
                 listUser·p0.95:   4.489 ms/op
                 listUser·p0.99:   5.677 ms/op
                 listUser·p0.999:  8.942 ms/op
                 listUser·p0.9999: 11.010 ms/op
                 listUser·p1.00:   11.616 ms/op

Iteration   2: 3.055 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.008 ms/op
                 listUser·p0.50:   2.998 ms/op
                 listUser·p0.90:   3.920 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   5.513 ms/op
                 listUser·p0.999:  10.387 ms/op
                 listUser·p0.9999: 13.804 ms/op
                 listUser·p1.00:   14.729 ms/op

Iteration   3: 3.064 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.024 ms/op
                 listUser·p0.50:   3.011 ms/op
                 listUser·p0.90:   3.944 ms/op
                 listUser·p0.95:   4.415 ms/op
                 listUser·p0.99:   5.554 ms/op
                 listUser·p0.999:  9.126 ms/op
                 listUser·p0.9999: 11.766 ms/op
                 listUser·p1.00:   12.845 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 313242
  mean =      3.062 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 94 
    [ 1.250,  2.500) = 82720 
    [ 2.500,  3.750) = 187645 
    [ 3.750,  5.000) = 35414 
    [ 5.000,  6.250) = 6090 
    [ 6.250,  7.500) = 706 
    [ 7.500,  8.750) = 134 
    [ 8.750, 10.000) = 167 
    [10.000, 11.250) = 196 
    [11.250, 12.500) = 43 
    [12.500, 13.750) = 19 
    [13.750, 15.000) = 14 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.899 ms/op
     p(50.0000) =      3.002 ms/op
     p(90.0000) =      3.944 ms/op
     p(95.0000) =      4.432 ms/op
     p(99.0000) =      5.595 ms/op
     p(99.9000) =      9.585 ms/op
     p(99.9900) =     12.610 ms/op
     p(99.9990) =     14.313 ms/op
     p(99.9999) =     14.729 ms/op
    p(100.0000) =     14.729 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.354 ± 2.853  ops/ms
ClientPb.existUser                       thrpt       3  12.911 ± 1.010  ops/ms
ClientPb.getUser                         thrpt       3  12.435 ± 1.458  ops/ms
ClientPb.listUser                        thrpt       3  10.531 ± 0.712  ops/ms
ClientPb.createUser                       avgt       3   2.566 ± 0.387   ms/op
ClientPb.existUser                        avgt       3   2.488 ± 0.177   ms/op
ClientPb.getUser                          avgt       3   2.577 ± 0.322   ms/op
ClientPb.listUser                         avgt       3   3.044 ± 0.358   ms/op
ClientPb.createUser                     sample  373739   2.566 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.725           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.621           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.121           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.244           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.854           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.508           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.664           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.221           ms/op
ClientPb.existUser                      sample  384710   2.493 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.918           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.540           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.043           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.158           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.760           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.703           ms/op
ClientPb.existUser:existUser·p0.9999    sample          14.354           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.581           ms/op
ClientPb.getUser                        sample  381287   2.515 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.636           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.535           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.060           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.174           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.731           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.782           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.877           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.237           ms/op
ClientPb.listUser                       sample  313242   3.062 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.899           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.002           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.944           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.432           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.595           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.585           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.610           ms/op
ClientPb.listUser:listUser·p1.00        sample          14.729           ms/op
