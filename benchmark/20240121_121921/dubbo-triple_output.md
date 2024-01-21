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
# Warmup Iteration   1: 5.267 ops/ms
# Warmup Iteration   2: 12.526 ops/ms
# Warmup Iteration   3: 12.824 ops/ms
Iteration   1: 12.960 ops/ms
Iteration   2: 13.047 ops/ms
Iteration   3: 12.900 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.969 ±(99.9%) 1.344 ops/ms [Average]
  (min, avg, max) = (12.900, 12.969, 13.047), stdev = 0.074
  CI (99.9%): [11.625, 14.313] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:51
# Fork: 1 of 1
# Warmup Iteration   1: 8.323 ops/ms
# Warmup Iteration   2: 12.934 ops/ms
# Warmup Iteration   3: 13.293 ops/ms
Iteration   1: 13.291 ops/ms
Iteration   2: 13.267 ops/ms
Iteration   3: 13.232 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.263 ±(99.9%) 0.541 ops/ms [Average]
  (min, avg, max) = (13.232, 13.263, 13.291), stdev = 0.030
  CI (99.9%): [12.723, 13.804] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:46
# Fork: 1 of 1
# Warmup Iteration   1: 7.923 ops/ms
# Warmup Iteration   2: 12.805 ops/ms
# Warmup Iteration   3: 12.940 ops/ms
Iteration   1: 12.958 ops/ms
Iteration   2: 12.803 ops/ms
Iteration   3: 12.842 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.868 ±(99.9%) 1.471 ops/ms [Average]
  (min, avg, max) = (12.803, 12.868, 12.958), stdev = 0.081
  CI (99.9%): [11.397, 14.338] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.613 ops/ms
# Warmup Iteration   2: 10.638 ops/ms
# Warmup Iteration   3: 10.799 ops/ms
Iteration   1: 10.839 ops/ms
Iteration   2: 10.926 ops/ms
Iteration   3: 10.882 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.882 ±(99.9%) 0.795 ops/ms [Average]
  (min, avg, max) = (10.839, 10.882, 10.926), stdev = 0.044
  CI (99.9%): [10.087, 11.677] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.053 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.591 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.469 ±(99.9%) 0.004 ms/op
Iteration   1: 2.482 ±(99.9%) 0.004 ms/op
Iteration   2: 2.502 ±(99.9%) 0.004 ms/op
Iteration   3: 2.489 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.491 ±(99.9%) 0.188 ms/op [Average]
  (min, avg, max) = (2.482, 2.491, 2.502), stdev = 0.010
  CI (99.9%): [2.303, 2.679] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:32
# Fork: 1 of 1
# Warmup Iteration   1: 3.738 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.412 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.426 ±(99.9%) 0.003 ms/op
Iteration   1: 2.400 ±(99.9%) 0.003 ms/op
Iteration   2: 2.423 ±(99.9%) 0.005 ms/op
Iteration   3: 2.420 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.414 ±(99.9%) 0.228 ms/op [Average]
  (min, avg, max) = (2.400, 2.414, 2.423), stdev = 0.012
  CI (99.9%): [2.186, 2.642] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:28
# Fork: 1 of 1
# Warmup Iteration   1: 4.001 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.573 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.486 ±(99.9%) 0.004 ms/op
Iteration   1: 2.483 ±(99.9%) 0.004 ms/op
Iteration   2: 2.478 ±(99.9%) 0.004 ms/op
Iteration   3: 2.482 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.481 ±(99.9%) 0.052 ms/op [Average]
  (min, avg, max) = (2.478, 2.481, 2.483), stdev = 0.003
  CI (99.9%): [2.429, 2.532] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:23
# Fork: 1 of 1
# Warmup Iteration   1: 4.747 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 2.978 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.937 ±(99.9%) 0.006 ms/op
Iteration   1: 2.951 ±(99.9%) 0.005 ms/op
Iteration   2: 2.939 ±(99.9%) 0.006 ms/op
Iteration   3: 2.941 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.944 ±(99.9%) 0.119 ms/op [Average]
  (min, avg, max) = (2.939, 2.944, 2.951), stdev = 0.007
  CI (99.9%): [2.825, 3.062] (assumes normal distribution)


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
# Warmup Iteration   1: 4.164 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.586 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.489 ±(99.9%) 0.006 ms/op
Iteration   1: 2.491 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.999 ms/op
                 createUser·p0.50:   2.572 ms/op
                 createUser·p0.90:   3.019 ms/op
                 createUser·p0.95:   3.117 ms/op
                 createUser·p0.99:   3.621 ms/op
                 createUser·p0.999:  10.065 ms/op
                 createUser·p0.9999: 13.844 ms/op
                 createUser·p1.00:   15.729 ms/op

Iteration   2: 2.482 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.005 ms/op
                 createUser·p0.50:   2.568 ms/op
                 createUser·p0.90:   3.011 ms/op
                 createUser·p0.95:   3.113 ms/op
                 createUser·p0.99:   3.576 ms/op
                 createUser·p0.999:  7.730 ms/op
                 createUser·p0.9999: 12.288 ms/op
                 createUser·p1.00:   12.747 ms/op

Iteration   3: 2.500 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.980 ms/op
                 createUser·p0.50:   2.572 ms/op
                 createUser·p0.90:   3.031 ms/op
                 createUser·p0.95:   3.158 ms/op
                 createUser·p0.99:   3.883 ms/op
                 createUser·p0.999:  8.170 ms/op
                 createUser·p0.9999: 10.460 ms/op
                 createUser·p1.00:   11.256 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 384996
  mean =      2.491 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 44 
    [ 1.250,  2.500) = 186992 
    [ 2.500,  3.750) = 194456 
    [ 3.750,  5.000) = 2634 
    [ 5.000,  6.250) = 406 
    [ 6.250,  7.500) = 59 
    [ 7.500,  8.750) = 43 
    [ 8.750, 10.000) = 87 
    [10.000, 11.250) = 115 
    [11.250, 12.500) = 88 
    [12.500, 13.750) = 54 
    [13.750, 15.000) = 13 
    [15.000, 16.250) = 5 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.980 ms/op
     p(50.0000) =      2.572 ms/op
     p(90.0000) =      3.019 ms/op
     p(95.0000) =      3.129 ms/op
     p(99.0000) =      3.699 ms/op
     p(99.9000) =      8.159 ms/op
     p(99.9900) =     13.296 ms/op
     p(99.9990) =     15.231 ms/op
     p(99.9999) =     15.729 ms/op
    p(100.0000) =     15.729 ms/op


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
# Warmup Iteration   1: 3.731 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.467 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.451 ±(99.9%) 0.005 ms/op
Iteration   1: 2.441 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.069 ms/op
                 existUser·p0.50:   2.511 ms/op
                 existUser·p0.90:   2.970 ms/op
                 existUser·p0.95:   3.068 ms/op
                 existUser·p0.99:   3.474 ms/op
                 existUser·p0.999:  5.587 ms/op
                 existUser·p0.9999: 13.235 ms/op
                 existUser·p1.00:   13.681 ms/op

Iteration   2: 2.467 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.890 ms/op
                 existUser·p0.50:   2.527 ms/op
                 existUser·p0.90:   3.006 ms/op
                 existUser·p0.95:   3.121 ms/op
                 existUser·p0.99:   3.781 ms/op
                 existUser·p0.999:  7.656 ms/op
                 existUser·p0.9999: 12.111 ms/op
                 existUser·p1.00:   12.845 ms/op

Iteration   3: 2.453 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.983 ms/op
                 existUser·p0.50:   2.490 ms/op
                 existUser·p0.90:   2.986 ms/op
                 existUser·p0.95:   3.097 ms/op
                 existUser·p0.99:   3.760 ms/op
                 existUser·p0.999:  7.719 ms/op
                 existUser·p0.9999: 11.975 ms/op
                 existUser·p1.00:   12.321 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 390973
  mean =      2.454 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 45 
    [ 1.250,  2.500) = 194673 
    [ 2.500,  3.750) = 192748 
    [ 3.750,  5.000) = 2620 
    [ 5.000,  6.250) = 438 
    [ 6.250,  7.500) = 58 
    [ 7.500,  8.750) = 28 
    [ 8.750, 10.000) = 92 
    [10.000, 11.250) = 77 
    [11.250, 12.500) = 137 
    [12.500, 13.750) = 57 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.890 ms/op
     p(50.0000) =      2.511 ms/op
     p(90.0000) =      2.986 ms/op
     p(95.0000) =      3.092 ms/op
     p(99.0000) =      3.674 ms/op
     p(99.9000) =      7.578 ms/op
     p(99.9900) =     12.698 ms/op
     p(99.9990) =     13.633 ms/op
     p(99.9999) =     13.681 ms/op
    p(100.0000) =     13.681 ms/op


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
# Warmup Iteration   1: 4.069 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.516 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.490 ±(99.9%) 0.005 ms/op
Iteration   1: 2.466 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.948 ms/op
                 getUser·p0.50:   2.494 ms/op
                 getUser·p0.90:   2.998 ms/op
                 getUser·p0.95:   3.109 ms/op
                 getUser·p0.99:   3.617 ms/op
                 getUser·p0.999:  6.360 ms/op
                 getUser·p0.9999: 12.960 ms/op
                 getUser·p1.00:   13.402 ms/op

Iteration   2: 2.491 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.654 ms/op
                 getUser·p0.50:   2.515 ms/op
                 getUser·p0.90:   3.023 ms/op
                 getUser·p0.95:   3.150 ms/op
                 getUser·p0.99:   4.255 ms/op
                 getUser·p0.999:  8.389 ms/op
                 getUser·p0.9999: 12.209 ms/op
                 getUser·p1.00:   13.582 ms/op

Iteration   3: 2.483 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.905 ms/op
                 getUser·p0.50:   2.527 ms/op
                 getUser·p0.90:   3.015 ms/op
                 getUser·p0.95:   3.138 ms/op
                 getUser·p0.99:   4.104 ms/op
                 getUser·p0.999:  7.250 ms/op
                 getUser·p0.9999: 11.113 ms/op
                 getUser·p1.00:   11.780 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 386748
  mean =      2.480 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 55 
    [ 1.250,  2.500) = 192701 
    [ 2.500,  3.750) = 189217 
    [ 3.750,  5.000) = 3664 
    [ 5.000,  6.250) = 696 
    [ 6.250,  7.500) = 30 
    [ 7.500,  8.750) = 6 
    [ 8.750, 10.000) = 104 
    [10.000, 11.250) = 107 
    [11.250, 12.500) = 113 
    [12.500, 13.750) = 55 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.654 ms/op
     p(50.0000) =      2.511 ms/op
     p(90.0000) =      3.015 ms/op
     p(95.0000) =      3.133 ms/op
     p(99.0000) =      3.916 ms/op
     p(99.9000) =      7.375 ms/op
     p(99.9900) =     12.670 ms/op
     p(99.9990) =     13.258 ms/op
     p(99.9999) =     13.582 ms/op
    p(100.0000) =     13.582 ms/op


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
# Warmup Iteration   1: 4.582 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.049 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.972 ±(99.9%) 0.008 ms/op
Iteration   1: 3.009 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.944 ms/op
                 listUser·p0.50:   2.937 ms/op
                 listUser·p0.90:   3.920 ms/op
                 listUser·p0.95:   4.456 ms/op
                 listUser·p0.99:   5.693 ms/op
                 listUser·p0.999:  9.355 ms/op
                 listUser·p0.9999: 12.288 ms/op
                 listUser·p1.00:   13.451 ms/op

Iteration   2: 2.972 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.849 ms/op
                 listUser·p0.50:   2.925 ms/op
                 listUser·p0.90:   3.809 ms/op
                 listUser·p0.95:   4.293 ms/op
                 listUser·p0.99:   5.448 ms/op
                 listUser·p0.999:  8.667 ms/op
                 listUser·p0.9999: 10.579 ms/op
                 listUser·p1.00:   11.272 ms/op

Iteration   3: 2.985 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.719 ms/op
                 listUser·p0.50:   2.933 ms/op
                 listUser·p0.90:   3.883 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   5.538 ms/op
                 listUser·p0.999:  8.895 ms/op
                 listUser·p0.9999: 10.561 ms/op
                 listUser·p1.00:   12.993 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 320892
  mean =      2.989 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 107 
    [ 1.250,  2.500) = 96852 
    [ 2.500,  3.750) = 185683 
    [ 3.750,  5.000) = 31439 
    [ 5.000,  6.250) = 5449 
    [ 6.250,  7.500) = 645 
    [ 7.500,  8.750) = 329 
    [ 8.750, 10.000) = 247 
    [10.000, 11.250) = 113 
    [11.250, 12.500) = 19 
    [12.500, 13.750) = 9 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.719 ms/op
     p(50.0000) =      2.933 ms/op
     p(90.0000) =      3.871 ms/op
     p(95.0000) =      4.366 ms/op
     p(99.0000) =      5.562 ms/op
     p(99.9000) =      8.962 ms/op
     p(99.9900) =     11.174 ms/op
     p(99.9990) =     13.415 ms/op
     p(99.9999) =     13.451 ms/op
    p(100.0000) =     13.451 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.969 ± 1.344  ops/ms
ClientPb.existUser                       thrpt       3  13.263 ± 0.541  ops/ms
ClientPb.getUser                         thrpt       3  12.868 ± 1.471  ops/ms
ClientPb.listUser                        thrpt       3  10.882 ± 0.795  ops/ms
ClientPb.createUser                       avgt       3   2.491 ± 0.188   ms/op
ClientPb.existUser                        avgt       3   2.414 ± 0.228   ms/op
ClientPb.getUser                          avgt       3   2.481 ± 0.052   ms/op
ClientPb.listUser                         avgt       3   2.944 ± 0.119   ms/op
ClientPb.createUser                     sample  384996   2.491 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.980           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.572           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.019           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.129           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.699           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.159           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.296           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.729           ms/op
ClientPb.existUser                      sample  390973   2.454 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.890           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.511           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.986           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.092           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.674           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.578           ms/op
ClientPb.existUser:existUser·p0.9999    sample          12.698           ms/op
ClientPb.existUser:existUser·p1.00      sample          13.681           ms/op
ClientPb.getUser                        sample  386748   2.480 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.654           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.511           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.015           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.133           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.916           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.375           ms/op
ClientPb.getUser:getUser·p0.9999        sample          12.670           ms/op
ClientPb.getUser:getUser·p1.00          sample          13.582           ms/op
ClientPb.listUser                       sample  320892   2.989 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.719           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.933           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.871           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.366           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.562           ms/op
ClientPb.listUser:listUser·p0.999       sample           8.962           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.174           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.451           ms/op
